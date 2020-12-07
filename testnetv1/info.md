# Wormhole Testnet

This Wormhole testnet connects the following chains:

- Solana [Tour de Sol testnet](https://docs.solana.com/clusters#testnet).

- Ethereum [Goerli testnet](https://goerli.net).

## Network parameters

Gossip network name:

    /wormhole/testnet/1

Gossip bootstrap node:

    /dns4/wormhole-testnet-bootstrap.certus.one/udp/8999/quic/p2p/12D3KooWH3VP44t12yKQXrPfMQVKEqSHnk5GTN3RCSqNoakAkLCq

Connected chain contracts:

| Network            | Bridge contract addresss |
|--------------------|--------------------------|
| Ethereum Goerli    | `<TBD>`                  |
| Solana Tour de Sol | `<TBD>`                  |

## Guardian set

Current generation: **0**, containing only the Certus One bootstrap node with the
address `0x8b1c9eFA61eBF66Fa1a6deDCF46fb1e37708ce5c`.

See [v1.prototext](guardianset/v1.prototxt) for the first guardian set update that will be executed once everyone's
node on the network is live.
