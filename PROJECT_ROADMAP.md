# The Ungovernable Internet Protocol (UIP) - Project Roadmap

## Vision
Create a censorship-resistant internet layer where:

- DNS is decentralized via blockchain
- Content is hosted peer-to-peer on user devices
- No central authority can shut it down without disabling entire networks

## Inspiration
Building upon Freenet's concepts but with:

- Stronger incentives for participation
- Blockchain-based trust mechanisms
- Mobile-first resilience

## Phase 1: Foundation (Months 1-3)

### Research & Specifications
- [ ] Whitepaper v0.1 documenting protocol design
- [ ] Threat model analysis (Sybil attacks, storage attacks)
- [ ] Blockchain selection (Ethereum, IPFS, or custom chain)
- [ ] Incentive mechanism design (token rewards for hosting?)

### Core Components
- [ ] Blockchain-based DNS prototype
- [ ] P2P content hosting proof-of-concept
- [ ] Minimal viable client (desktop first)

## Phase 2: Development (Months 4-9)

### Protocol Implementation
- [ ] UIP node software (Rust/Go)
- [ ] Smart contracts for DNS registry
- [ ] Content addressing system (IPFS-like but with mobile optimizations)
- [ ] Data replication and caching strategy

### Network Features

- [ ] Dark routing capability (Tor-like but decentralized)
- [ ] Reputation system for peers
- [ ] Storage proofs for hosting verification

## Phase 3: Mobile Resilience (Months 10-12)

### Mobile Integration

- [ ] Android reference implementation
- [ ] iOS workarounds (considering app store restrictions)
- [ ] Optimized for intermittent connectivity
- [ ] Background service that survives app closure

### Anti-Censorship

- [ ] Bootstrap node discovery that's resistant to blocking
- [ ] Protocol obfuscation (masquerading as normal traffic)
- [ ] Dead-man's switch for network persistence

## Phase 4: Ecosystem Growth (Ongoing)

### Community & Adoption

- [ ] Developer documentation portal
- [ ] Gateway tools for existing web compatibility
- [ ] Onboarding for non-technical users
- [ ] Bug bounty program

## Immediate Next Steps

1. Assemble core development team
2. Create GitHub organization and initial repos
3. Begin whitepaper drafting
4. Build PoC for blockchain DNS
5. Design minimal P2P hosting protocol
