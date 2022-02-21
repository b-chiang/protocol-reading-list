# protocol-reading-list

A list of resources for people that want to understand how specific protocols work.

[MEV 101](https://github.com/0xmebius/mev/blob/main/MEV101.pdf) by [@0xmebius](https://twitter.com/0xmebius) is a good starting point if you're new.

## Constant Function Market Makers (CFMMs)

Decentralized exchanges (DEXes) and automated market makers (AMMs).

### Uniswap

- [How Uniswap works - V2 (uniswap.org)](https://docs.uniswap.org/protocol/V2/concepts/protocol-overview/how-uniswap-works)
- [Uniswap V1 Whitepaper (PDF)](https://hackmd.io/@HaydenAdams/HJ9jLsfTz)
- [Uniswap V2 Whitepaper（PDF）](https://uniswap.org/whitepaper.pdf)
- [Introducing Uniswap V3 (uniswap.org/blog)](https://uniswap.org/blog/uniswap-v3)
- [What is Uniswap - V3 (docs.uniswap.org)](https://docs.uniswap.org/protocol/introduction)
- [Uniswap V3 Whitepaper (PDF)](https://uniswap.org/whitepaper-v3.pdf)

### Curve

- [Curve StableSwap Whitepaper (PDF)](https://curve.fi/files/stableswap-paper.pdf)
- [Curve Crypto Pools Whitepaper (PDF)](https://curve.fi/files/crypto-pools-paper.pdf)
- [Curve DAO Whitepapers (PDF)](https://curve.fi/files/CurveDAO.pdf)
- [Curve Wars (every.to)](https://every.to/almanack/curve-wars) from [@nateliason](https://twitter.com/nateliason)

### CFMM Analysis

Mostly work from ACE and others.

- [An analysis of Uniswap markets (PDF)](https://arxiv.org/pdf/1911.03380.pdf)
- [Multi-asset trades via convex optimization (PDF)](https://arxiv.org/pdf/2107.12484.pdf)
- [Improved Price Oracles: Constant Function Market Makers (PDF)](https://arxiv.org/abs/2003.10001)
- [Optimal Fees for Geometric Mean Market Makers (PDF)](https://web.stanford.edu/~guillean/papers/g3m-optimal-fee.pdf)
- [Optimal Routing for Constant Function Market Makers (PDF)](https://web.stanford.edu/~guillean/papers/cfmm-routing.pdf)
- [When does the tail wag the dog? Curvature and market making (PDF)](https://arxiv.org/pdf/2012.08040.pdf)

Privacy-preserving CFMMs:

- [A Note on Privacy in Constant Function Market Makers (PDF)](https://arxiv.org/pdf/2103.01193.pdf)
- [Differential Privacy in Constant Function Market
  Makers (PDF)](https://eprint.iacr.org/2021/1101.pdf)
- [Osmosis](https://app.osmosis.zone/?from=ATOM&to=OSMO) + [Cosmos](https://v1.cosmos.network/resources/whitepaper)

### LPing on Uniswap V3

- [Strategic Liquidity Provision in Uniswap v3 (PDF)](https://arxiv.org/pdf/2106.12033.pdf)
- [Charm’s Alpha Vault, the Minimalist Uniswap v3 LP Strategy (PDF)](https://medium.com/blockchain-development-notes/charms-alpha-vault-the-minimalist-uniswap-v3-lp-strategy-23a059c924b)
- [Impermanent Loss in Uniswap v3 (PDF)](https://arxiv.org/pdf/2111.09192.pdf)

More Uniswap V3 research at [GammaStrategies/awesome-uniswap-v3](https://github.com/GammaStrategies/awesome-uniswap-v3#research).

## Protocol Owned Liquidity (POL)

Read these:

- [Introducing OlympusDAO, An Algorithmic Currency Protocol (medium.com)](https://olympusdao.medium.com/introducing-olympusdao-a-true-digital-currency-protocol-648c00c572d2)
- [FAQ（docs.olympusdao.finance)](https://docs.olympusdao.finance/main/basics/basics)
- [A Beginner’s Guide to Navigating Olympus Pro (medium.com)](https://olympusdao.medium.com/a-beginners-guide-to-navigating-olympus-pro-5b1a9b710075)
- [A Primer on Bonding (medium.com)](https://olympusdao.medium.com/a-primer-on-oly-bonds-9763f125c124)

Then read this:

- [DeFi liquidity management via Optimal Control:
  Ohm as a case study (PDF)](https://people.eecs.berkeley.edu/~ksk/files/Ohm_Liquidity_Management.pdf)

## Lending

- [Aave Whitepaper](https://github.com/aave/aave-protocol/blob/master/docs/Aave_Protocol_Whitepaper_v1_0.pdf)
- [Compound Whitepaper（PDF)](https://compound.finance/documents/Compound.Whitepaper.pdf)

## Stablecoins

- [USDC Whitepaper](https://f.hubspotusercontent30.net/hubfs/9304636/PDF/centre-whitepaper.pdf)
- [DAI Whitepaper](https://makerdao.com/whitepaper/Dai-Whitepaper-Dec17-en.pdf)
- [MakerDAO Whitepaper](https://makerdao.com/en/whitepaper/#abstract)
- [Fei Whitepaper](https://fei.money/static/media/whitepaper.7d5e2986.pdf)
- [Lemma Whitepaper](https://docs.lemma.finance/concepts-overview/perpetual-contracts)
  - The sections under "Concepts Overview"

## Derivatives

- [defi-derivatives](https://github.com/0xperp/defi-derivatives) from [0xperp](https://github.com/0xperp/defi-derivatives)
- [Why Stake When You Can Borrow?](https://arxiv.org/abs/2006.11156)

## Other

- [Crocswap](https://www.crocswap.com/whitepaper)
- [Protocol Assessment Reports](https://gauntlet.network/research/) from Gauntlet
- [A list of open problems in DeFi](https://mirror.xyz/0xemperor.eth/0guEj0CYt5V8J5AKur2_UNKyOhONr1QJaG4NGDF0YoQ) by [0xemperor](https://twitter.com/0x_emperor)
- How do we build better fiat on-ramps/off-ramps?
  - [tbDEX](https://github.com/TBD54566975/tbdex-whitepaper) for decentralized ramps
  - [Sardine](https://www.sardine.ai/) for faster settlement
- [matter-labs/awesome-zero-knowledge-proofs](https://github.com/matter-labs/awesome-zero-knowledge-proofs)
  - Applied ZK hacks from [0xPARC](https://0xparc.org/blog)
- Can we do more numerical computing on-chain?
  - [Aleo](https://www.aleo.org/blog)
  - [guiltygyoza](https://github.com/guiltygyoza?tab=repositories)
