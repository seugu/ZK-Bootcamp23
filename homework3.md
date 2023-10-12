## Homework 3

Use Remix, Install the Zokrates plugin

1. Use the example file to generate a proof to show that a prover knows the square root of 25.
2. Try to create an invalid proof
3. Follow the example to build a proof that you know the preimage of a hash
https://zokrates.github.io/examples/sha256example.html
4. In principle how could you use Zokrates to verify that a certain address on Ethereum has more than say 1 ETH ?
- To prove a balance of account A has 1 ETH, we need to calculate the Merkle-Patrica Trie root in the given block number N by the taking leaves path regarding account A.
  Therefore when we can show that the calculated root is the same as in block N, we show that account A has 1 ETH. Any verifier can verify that account A has 1 ETH by verifying the proof without receiving any leaf path.  
   
```
// target=25 and root=5(private)
//We don't output anything just use assert
// When we create a invalid proof like setting root=6 and target=25 it throws error in compilation


import "hashes/sha256/512bitPacked" as sha256packed;

def proving_five(u8 target, private u8 root)  {
     assert(root*root==25);
     return;
}

// It takes more time to compile and compute since SHA256 is complex.
def preimage_of_0005(private field a, private field b, private field c, private field d) {
    field[2] h = sha256packed([a, b, c, d]);
    assert(h[0] == 263561599766550617289250058199814760685);
    assert(h[1] == 65303172752238645975888084098459749904);
    return;
}

```
