# The Ungovernable Internet Protocol (UIP)

A censorship-resistant internet layer that cannot be shut down without turning off all devices.

## Key Features
- 🛡️ Blockchain-anchored DNS - No single point of control
- 📱 Hosted by users - Content lives on phones and computers worldwide
- ⚡ Resilient - Designed to work even when governments try to block it

## How It Works
1. Naming: Decentralized DNS via smart contracts
2. Storage: Content distributed across participating nodes
3. Access: Encrypted peer-to-peer delivery with caching

## Getting Started
### Run a Node
`docker run -d ungovernable/uip-node`

### Develop Apps
See our SDK documentation at [docs.ungov.io]

## UIP Node Proof-of-Concept (Rust)

A minimal Rust node is available in `uip-node/` with the following features:
- Peer discovery (UDP broadcast)
- In-memory content storage
- Simulated blockchain DNS
- CLI commands: `start`, `status`, `discover`, `storage`, `dns`

To run locally:
```sh
cd uip-node
cargo run -- start
```
See `uip-node/README.md` for more CLI options and details.

## Roadmap Progress
- [x] Project structure, documentation, and specs scaffolded
- [x] Proof-of-concept Rust node with CLI and core modules
- [x] Solidity smart contract and CI for blockchain DNS
- [ ] Real smart contract integration
- [ ] Persistent storage and advanced networking
- [ ] Full UIP component integration

## Join the Movement
We're building the internet that can't be turned off. Contribute code, run nodes, or help spread the word.
