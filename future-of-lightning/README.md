# The Future of Lightning

## Reading

| Content                                                                                       | Time  | Tags                    |
|-----------------------------------------------------------------------------------------------|-------|-------------------------|
[Breaking Down the Bitcoin Lightning Network: eltoo](https://medium.com/@brandonarvanaghi/breaking-down-the-bitcoin-lightning-network-eltoo-c48554f5ae02) | 11 min | eltoo |
[Eltoo and the Far Future](https://diyhpl.us/wiki/transcripts/chaincode-labs/2019-09-18-christian-decker-eltoo/) | 30 min | eltoo |
[Submarine Swaps](http://diyhpl.us/wiki/transcripts/magicalcryptoconference/2019/submarine-swaps/) | 5 min | submarine swaps |
[Loops](https://blog.lightning.engineering/posts/2019/03/20/loop.html) | 5 min | loops, liquidity |
[Submarine swaps/ Loops](https://youtu.be/qixhNBIHDyE) | 42 min | loops, submarine swaps, video |
[Splicing](https://youtu.be/ZzSveBMtUGI) | 22 min | BOLTs, video |
[Multi-party channels/Channel factories](https://youtu.be/PUDWGH_MvmQ) | 13 min | BOLTs, video |
[Dual funded channels](https://youtu.be/5wQUMtgsnPs) | 35 min | BOLTs, video |
[Payment Points: Replacing HTLCs](https://suredbits.com/payment-points-part-1/) | 10 min | payment points |
[Payment Points: "Stuckless" Payments](https://suredbits.com/payment-points-part-2-stuckless-payments/) | 10 min | payment points |

## Discussion Questions

### Breaking Down the Bitcoin Lightning Network: eltoo

1. Why do we need SIGHASH_NOINPUT for eltoo?
1. What do HTLCs look like for an Eltoo channel?

### Eltoo and the Far Future

1. How does a cooperative close work with Eltoo?
1. Can channels using Eltoo or PTLC be mixed with standard channels in a multi-hop payment?

### Submarine swaps and Loops

1. Can an adversary make a swap and then wait until a moment before the lock expiry to reveal the secret on one chain while using the signature on the other? If the blocks are fast, could an attacker be able to steal the money from both chains?

### Splicing

1. Is it easier to splice on an Eltoo channel?

### Multi-party channels/Channel factories

1. What are the advantages and disadvantages of multiparty channels?

### Dual funded channels

1. How do you split the fees in dual-funded channels?

### Payment Points: Replacing HTLCs

1. How does a wormhole attack work?
1. Can sender or receiver notice a wormhole attack?

### Payment Points: "Stuckless" Payments

