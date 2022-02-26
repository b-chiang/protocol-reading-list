# protocol-reading-list

A list of resources for understanding crypto protocols.

## Getting Started

- [MEV 101](https://github.com/0xmebius/mev/blob/main/MEV101.pdf) by [@0xmebius](https://twitter.com/0xmebius) is a good overview
- [DeFi MOOC (Fall 2021)](https://defi-learning.org/) from Dan Boneh Arthur Gervais, Andrew Miller, Christine Parlour, Dawn Song
- [Special Topics in DeFi](https://berkeley-defi.github.io/f21) from Dawn Song

Slides and videos available online for both.

### References

- [Algorithmic Game Theory](http://timroughgarden.org/f10/f10.html) from [Tim Roughgarden](http://theory.stanford.edu/~tim/)
  - [Foundations of Blockchains Playlist (youtube.com)](https://www.youtube.com/watch?v=KNJGPI0fuFA&list=PLEGCF-WLh2RLOHv_xUGLqRts_9JxrckiA)
  - [Tim Roughgarden's Channel](https://www.youtube.com/channel/UCcH4Ga14Y4ELFKrEYM1vXCg)
- [Convex Optimization](https://web.stanford.edu/class/ee364a/) by [Stephen Boyd](https://web.stanford.edu/~boyd/)
- [Mathematics of Finance](https://www.google.com/books/edition/Mathematics_of_Finance/K2SsDwAAQBAJ?hl=en) from [Don Saari](https://www.math.uci.edu/~dsaari/)
- [A Graduate Course in
  Applied Cryptography](https://toc.cryptobook.us/) from [Dan Boneh](https://crypto.stanford.edu/~dabo) and [Victor Shoup](https://www.shoup.net/)

## Constant Function Market Makers (CFMMs)

Trading via decentralized exchanges (DEXes) and automated market makers (AMMs).

### Uniswap

**V2**

- [Uniswap V1 Whitepaper (hackmd.io)](https://hackmd.io/@HaydenAdams/HJ9jLsfTz)
- [How Uniswap works - V2 (uniswap.org)](https://docs.uniswap.org/protocol/V2/concepts/protocol-overview/how-uniswap-works)
- [Uniswap V2 Whitepaper（PDF）](https://uniswap.org/whitepaper.pdf)

Also:

- [Uniswap: A Good Deal for Liquidity Providers? (medium.com)](https://pintail.medium.com/uniswap-a-good-deal-for-liquidity-providers-104c0b6816f2)
- [Understanding Uniswap Returns (medium.com)](https://pintail.medium.com/understanding-uniswap-returns-cc593f3499ef)
- [On AMMS (vitalik.ca)](https://vitalik.ca/general/2017/06/22/marketmakers.html)
- [Background on MMs in traditional finance (PDF)](http://stanford.edu/class/msande448/2018/Final/Reports/gr5.pdf)

**V3**

- [Introducing Uniswap V3 (uniswap.org/blog)](https://uniswap.org/blog/uniswap-v3)
- [What is Uniswap - V3 (docs.uniswap.org)](https://docs.uniswap.org/protocol/introduction)
- [Uniswap V3: The Universal AMM (paradigm.xyz)](https://www.paradigm.xyz/2021/06/uniswap-v3-the-universal-amm)
- [Uniswap V3 Whitepaper (PDF)](https://uniswap.org/whitepaper-v3.pdf)
- [Interactive graphs in Desmos for Uniswap V3](https://twitter.com/danrobinson/status/1430299243550593024?lang=en) from [@danrobinson](https://twitter.com/danrobinson)

Also:

- [Liquidity Mining on Uniswap v3 (paradigm.xyz)](https://www.paradigm.xyz/2021/05/liquidity-mining-on-uniswap-v3)
- [Uniswap V3 LP Tokens as Perpetual Put and Call Options](https://lambert-guillaume.medium.com/uniswap-v3-lp-tokens-as-perpetual-put-and-call-options-5b66219db827) from [Guillaume Lambert](https://lambertlab.io/)

### Curve

- [Curve StableSwap Whitepaper (PDF)](https://curve.fi/files/stableswap-paper.pdf)
- [Curve Crypto Pools Whitepaper (PDF)](https://curve.fi/files/crypto-pools-paper.pdf)
- [Curve DAO Whitepapers (PDF)](https://curve.fi/files/CurveDAO.pdf)
- [Understanding StableSwap (Curve)](https://miguelmota.com/blog/understanding-stableswap-curve/)
- [Curve Wars (every.to)](https://every.to/almanack/curve-wars) from [@nateliason](https://twitter.com/nateliason)
- [Department of Gauge Defense (Curve)](https://cryptorisks.substack.com/)

## Other Designs

- [Nested AMMs (dropbox.com)](https://www.dropbox.com/s/sxwly0gn4fyj1uc/nestedamm.pdf?dl=0) from [Anthony Lee Zhang](https://twitter.com/AnthonyLeeZhang)
- [TWAMM (paradigm.xyz)](https://www.paradigm.xyz/2021/07/twamm)
- [Mooniswap Whitepaper (PDF)](https://mooniswap.exchange/docs/MooniswapWhitePaper-v1.0.pdf)
- [dYdX Whitepaper (PDF)](https://whitepaper.dydx.exchange/)
- [Crocswap Whitepaper](https://www.crocswap.com/whitepaper)
- [Toxic Flow: Its Sources and Counter-Strategies (deribit.com)](https://insights.deribit.com/market-research/toxic-flow-its-sources-and-counter-strategies/)
- [Flash Boys 2.0 (PDF)](https://arxiv.org/pdf/1904.05234.pdf)

### CFMM Analysis

Work from [@GuilleAngeris](https://twitter.com/GuilleAngeris), [@tarunchitra](https://twitter.com/tarunchitra), [@alexhevans](https://twitter.com/alexhevans) and more

- [An analysis of Uniswap markets (PDF)](https://arxiv.org/pdf/1911.03380.pdf)
- [Multi-asset trades via convex optimization (PDF)](https://arxiv.org/pdf/2107.12484.pdf)
- [Improved Price Oracles: Constant Function Market Makers (PDF)](https://arxiv.org/abs/2003.10001)
- [Liquidity Provider Returns in Geometric Mean Markets](https://arxiv.org/pdf/2006.08806.pdf)
- [Optimal Fees for Geometric Mean Market Makers (PDF)](https://web.stanford.edu/~guillean/papers/g3m-optimal-fee.pdf)
- [Optimal Routing for Constant Function Market Makers (PDF)](https://web.stanford.edu/~guillean/papers/cfmm-routing.pdf)
- [When does the tail wag the dog? Curvature and market making (PDF)](https://arxiv.org/pdf/2012.08040.pdf)

### Privacy-preserving CFMMs

- [A Note on Privacy in Constant Function Market Makers (PDF)](https://arxiv.org/pdf/2103.01193.pdf)
- [Differential Privacy in Constant Function Market
  Makers (PDF)](https://eprint.iacr.org/2021/1101.pdf)
- Check out the interchain future @ [Osmosis](https://app.osmosis.zone/?from=ATOM&to=OSMO) + [Cosmos](https://v1.cosmos.network/resources/whitepaper)

### Options

- [Virtual AMM (vAMM): Perpetual Protocol](https://blog.perp.fi/a-deep-dive-into-our-virtual-amm-vamm-40345c522eeb)
- [Drift Dynamic AMM](https://docs.drift.trade/drift-dynamic-amm)
- [Replicating Market Makers](https://arxiv.org/abs/2103.14769)
- [Replicating Monotonic Payoffs Without Oracles](https://arxiv.org/pdf/2111.13740.pdf)
- [Primitive Finance](https://primitive.finance/whitepaper-rmm-01.pdf)
- [Why Stake When You Can Borrow?](https://arxiv.org/abs/2006.11156)

More resources at [0xperp/defi-derivatives#option-amms](https://github.com/0xperp/defi-derivatives#option-amms). The entire list on derivatives is also great.

### LPing on Uniswap V3

- [Strategic Liquidity Provision in Uniswap v3 (PDF)](https://arxiv.org/pdf/2106.12033.pdf)
- [Charm’s Alpha Vault, the Minimalist Uniswap v3 LP Strategy (PDF)](https://medium.com/blockchain-development-notes/charms-alpha-vault-the-minimalist-uniswap-v3-lp-strategy-23a059c924b)
- [Impermanent Loss in Uniswap v3 (PDF)](https://arxiv.org/pdf/2111.09192.pdf)

More resources at [GammaStrategies/awesome-uniswap-v3](https://github.com/GammaStrategies/awesome-uniswap-v3#research).

## Protocol Owned Liquidity (POL)

Read these:

- [Introducing OlympusDAO, An Algorithmic Currency Protocol (medium.com)](https://olympusdao.medium.com/introducing-olympusdao-a-true-digital-currency-protocol-648c00c572d2)
- [FAQ（docs.olympusdao.finance)](https://docs.olympusdao.finance/main/basics/basics)
- [A Beginner’s Guide to Navigating Olympus Pro (medium.com)](https://olympusdao.medium.com/a-beginners-guide-to-navigating-olympus-pro-5b1a9b710075)
- [A Primer on Bonding (medium.com)](https://olympusdao.medium.com/a-primer-on-oly-bonds-9763f125c124)

Then read these:

- [Feedback Control as a New Primitive for DeFi (medium.com/gauntlet-networks)](https://medium.com/gauntlet-networks/feedback-control-as-a-new-primitive-for-defi-27b493f25b1)
- [DeFi liquidity management via Optimal Control:
  Ohm as a case study (PDF)](https://people.eecs.berkeley.edu/~ksk/files/Ohm_Liquidity_Management.pdf)

And this:

- [Active liquidity management for protocols (substack.com)](https://kydo.substack.com/p/palm-protocol-owned-active-liquidity)

## Asset Management

- [Yearn Vaults](https://docs.yearn.finance/getting-started/products/yvaults/overview)
- [Rari Capital - Fuse (medium.com)](https://medium.com/rari-capital/fuse-explained-3ef2e0747953)

Similar to [Tetranode's Locker](https://app.rari.capital/fuse/pool/6) on Rari, there could be a service that allows influencers to create custom Yearn vaults that their followers can one-click deposit liquidity into. For followers: instant yield + no time wasted trying to manually strategies; for influencers: easy way to monetize their strategies. h/t John

### Balancer

- [Balancer Basics](https://token-engineering-balancer.gitbook.io/balancer-simulations/understanding-balancer-amms/balancer-basics)
- [Balancer Whitepaper (PDF)](https://balancer.fi/whitepaper.pdf)
- [Calculating Value, Impermanent Loss and Slippage for Balancer Pools (medium.com)](https://medium.com/balancer-protocol/calculating-value-impermanent-loss-and-slippage-for-balancer-pools-4371a21f1a86)
- [Capital-Efficient AMMs With Dynamically Adjusted Weights In Balancer V2 (medium.com)](https://medium.com/balancer-protocol/capital-efficient-amms-with-dynamically-adjusted-weights-in-balancer-v2-9a7104789cd7)

## Lending

Decentralized banks.

- [Aave Whitepaper (PDF)](https://github.com/aave/aave-protocol/blob/master/docs/Aave_Protocol_Whitepaper_v1_0.pdf)
- [Compound Whitepaper（PDF)](https://compound.finance/documents/Compound.Whitepaper.pdf)

## Stablecoins

- [USDC Whitepaper](https://f.hubspotusercontent30.net/hubfs/9304636/PDF/centre-whitepaper.pdf)
- [DAI Whitepaper](https://makerdao.com/whitepaper/Dai-Whitepaper-Dec17-en.pdf)
- [MakerDAO Whitepaper](https://makerdao.com/en/whitepaper/#abstract)
- [Fei Whitepaper](https://fei.money/static/media/whitepaper.7d5e2986.pdf)
- [Lemma Whitepaper](https://docs.lemma.finance/concepts-overview/perpetual-contracts)
  - Sections under "Concepts Overview"

## Ramps

- [tbDEX](https://github.com/TBD54566975/tbdex-whitepaper) for decentralized ramps
- [Sardine](https://www.sardine.ai/) for faster settlement

## Miscellaneous

- [Gauntlet Protocol Assessment Reports](https://gauntlet.network/research/)
- [Gauntlet Blog (medium.com)](https://medium.com/gauntlet-networks)
- [A list of open problems in DeFi](https://mirror.xyz/0xemperor.eth/0guEj0CYt5V8J5AKur2_UNKyOhONr1QJaG4NGDF0YoQ) by [0xemperor](https://twitter.com/0x_emperor)
- [0xalpharush/awesome-MEV-resources](https://github.com/0xalpharush/awesome-MEV-resources)
- [Chi Gastoken (blog.1inch.io)](https://blog.1inch.io/everything-you-wanted-to-know-about-chi-gastoken-a1ba0ea55bf3) - h/t Kai
- [Flexible Anonymous Transactions: Flax (PDF)](https://eprint.iacr.org/2021/1249.pdf)

## Applied ZK

Start with these:

- [ZK Learning Group Topics (notion.so)](https://0xparc.notion.site/ZK-Learning-Group-Topics-f53933eecc2f41438c6c2bdd5b42ee2d) from [0xPARC](https://0xparc.org/)
- [A Succinct Story of Zero Knowledge](https://nibnalin.me/assets/zk.pdf) from [nibnalin](https://nibnalin.me/)
- [ZK: Zero to Hero (notion.site)](https://steelperlot.notion.site/steelperlot/ZK-Zero-to-Hero-1157a665a4a249d9805aebd5efea6460) from [@eric_ruleman](https://twitter.com/eric_ruleman)

Then dive deeper with these:

- [Proofs, Arguments, and Zero-Knowledge](https://people.cs.georgetown.edu/jthaler/ProofsArgsAndZK.pdf) from [Justin Thaler](https://people.cs.georgetown.edu/jthaler/)
- https://people.eecs.berkeley.edu/~alexch/#teaching
  - Specifically [CS602: Foundations of Probabilistic Proofs (S2022)](https://people.eecs.berkeley.edu/~alexch/classes/CS602-S2022.html)
- [matter-labs/awesome-zero-knowledge-proofs](https://github.com/matter-labs/awesome-zero-knowledge-proofs)

And check out these hacks:

- https://0xparc.org/blog
- [guiltygyoza](https://github.com/guiltygyoza?tab=repositories) on [StarkNet + Cairo](https://www.cairo-lang.org/docs/)

For more background:

### Cryptography

**Asymetric Encryption**

- [RSA Algorithm](https://www.di-mgt.com.au/rsa_alg.html)
- [Math of Elliptic Curves](https://hackernoon.com/what-is-the-math-behind-elliptic-curve-cryptography-f61b25253da3)
- [Digital Signature Algorithm](https://en.wikipedia.org/wiki/Digital_Signature_Algorithm)
- [Elliptic Curve Signatures](https://en.wikipedia.org/wiki/Elliptic_Curve_Digital_Signature_Algorithm)
- [Shamirs Secret Sharing (youtube.com)](https://www.youtube.com/watch?v=iFY5SyY3IMQ)
- [Learning with errors post-quantum (youtube.com)](https://www.youtube.com/watch?v=Lo-_ZBqGa7I&t=3263s)

**SNARKs**

- [Gentle introduction to zk-SNARKs (PDF)](https://chriseth.github.io/notes/articles/zksnarks/zksnarks.pdf)
- [zk-SNARKs (vitalk.ca)](https://vitalik.ca/general/2021/01/26/snarks.html)
- [Halo (vitalik.ca)](https://vitalik.ca/general/2021/11/05/halo.html)
- [Halo Paper (PDF)](https://eprint.iacr.org/2020/1536.pdf)
- [Plonk Paper (PDF)](https://eprint.iacr.org/2019/953.pdf)
- [Plonk (vitalik.ca)](https://vitalik.ca/general/2019/09/22/plonk.html)
- [Bullet Proofs](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8418611&casa_token=fnoYbp0lh0EAAAAA:phMecxsJ9VkVcDXOdYsZU36kJf5QV8EFLbuzVOE6b28dIhjlCMzdg1D4qP-Iw0am_mArzCqf9Kw)
- [Nova Paper (PDF)](https://eprint.iacr.org/2021/370.pdf)

**Other**

- [keccak](https://keccak.team/keccak.html)
- [Pairings (youtube.com)](https://www.youtube.com/watch?v=8WDOpzxpnTE&t=4651s) from Dan Boneh
- [Pairings (vitalik.ca)](https://vitalik.ca/general/2017/01/14/exploring_ecp.html)
