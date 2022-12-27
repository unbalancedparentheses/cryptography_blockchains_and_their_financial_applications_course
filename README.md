# Practical Cryptography and Distributed Ledgers

- Pablo Deymonnaz
- Diego Kingston
- Federico Carrone

Disclaimer: We're still organizing everything. Some links might be in an incorrect section. We will finish organizing everything in the next 8 weeks.

# 1. Foundations of Cryptography
- Groups, Rings and Fields
- Finite Fields
- Modular Arithmetic
- Polynomials over a Field
- P versus NP problem
- Computationally Hard Problems: Factorization and the Discrete Logarithm
- Elliptic Curves
- Elliptic Curves Pairings and Field Extensions

## Readings
- [Chapter entitled Cryptography: Sections on Symmetric Crypto Primitives - Anderson Security Engineering](https://www.cl.cam.ac.uk/~rja14/Papers/SEv2-c05.pdf)
- [A (Relatively Easy To Understand) Primer on Elliptic Curve Cryptography - Nick Sullivan](https://blog.cloudflare.com/a-relatively-easy-to-understand-primer-on-elliptic-curve-cryptography/)
- [Exploring Elliptic Curve Pairings - Vitalik Buterin](https://vitalik.ca/general/2017/01/14/exploring_ecp.html)
- [Pairing](https://www.zeroknowledgeblog.com/index.php/the-pinocchio-protocol/pairing)
- [Ben Lynn's notes on cryptography, abstract algebra and number theory](https://crypto.stanford.edu/pbc/notes/)
- [Reed Solomon](https://mazzo.li/posts/reed-solomon.html)
- [Reed–Solomon codes for coders](https://en.wikiversity.org/wiki/Reed%E2%80%93Solomon_codes_for_coders)
- [Moonmath](https://leastauthority.com/community-matters/moonmath-manual/)

## Exercises
- [Programming Bitcoin: Learn How to Program Bitcoin from Scratch - Jimmy Song]()

# 2 Symmetric encryption
- Stream ciphers and block ciphers
- AES
- AES operation modes
- ChaCha20
- Security definitions.
- Attacks on block and stream ciphers.

# 3. Asymmetric encryption
- Diffie-Hellman Key Exchange
- ECDH
- ElGamal
- RSA
- PKCS

## Readings
- [Twenty Years of Attacks on the RSA Cryptosystem - Dan Boneh](https://crypto.stanford.edu/~dabo/papers/RSA-survey.pdf)

# 4. Hash Functions, MAC and Signatures
- Properties of cryptographic hash functions
- Merkle-Damgard construction
- MD5
- SHA1
- Sponge constructions
- Keccak - SHA3
- Message Authentication Codes
- ECDSA signature
- Schnor signature
- BLS signature

## Readings
- [What is a Cryptographic Hash Function? - Alin Tomescu](https://decentralizedthoughts.github.io/2020-08-28-what-is-a-cryptographic-hash-function/)
- [What is the BLS signature scheme? - David Wong](https://www.cryptologie.net/article/472/what-is-the-bls-signature-scheme/)
- [BLS Signatures - Remco Bloemen](https://xn--2-umb.com/22/bls-signatures/)

# 5. What is Money?
- [A Brief History of Money](https://nakamoto.com/a-brief-history-of-money/)
- [Shelling Out: The Origins of Money - Nick Szabo](https://nakamotoinstitute.org/shelling-out/)
- [What is Money anyway - Lyn Alden](https://www.lynalden.com/what-is-money/)
- [Money in the modern economy: an introduction](https://www.bankofengland.co.uk/-/media/boe/files/quarterly-bulletin/2014/money-in-the-modern-economy-an-introduction.pdf?la=en&hash=E43CDFDBB5A23D672F4D09B13DF135E6715EEDAC)
- [Money creation in the modern economy](https://www.bankofengland.co.uk/-/media/boe/files/quarterly-bulletin/2014/money-creation-in-the-modern-economy.pdf?la=en&hash=9A8788FD44A62D8BB927123544205CE476E01654)
- [The Cypherpunks](https://nakamoto.com/the-cypherpunks)

# 6. Introduction to blockchains and cryptocurrencies
- What is a blockchain?
- State Machines
- Consensus
- Merkle Trees

## Readings
- [Why cryptocurrencies are interesting?](https://mirror.xyz/0xaFaBa30769374EA0F971300dE79c62Bf94B464d5/us0MyyUNYwSXazM0YCrGscbRWr18s0aIIZqyHBbTWfM)
- [Cancelled Nickel Trades on the LME](https://youtu.be/tHXF5LyLI4M)
- [What is a Blockchain - Ittai Abraham](https://decentralizedthoughts.github.io/2022-09-05-what-is-a-blockchain/)
- [How does everything tie together?](https://mirror.xyz/0xaFaBa30769374EA0F971300dE79c62Bf94B464d5/nsEwS5WZjLeydpX2x9XybTpu7dA5LpLNyayj93HnovA)
- [Blockchains as Cryptographic Data Structures - Pramod Viswanath](https://courses.grainger.illinois.edu/ece598pv/sp2021/lectureslides2021/ECE_598_PV_course_notes2.pdf)
- [Hash functions](https://nakamoto.com/hash-functions/)
- [Merkle Tree](https://nakamoto.com/merkle-trees/)
- [What is a Merkle Tree](https://decentralizedthoughts.github.io/2020-12-22-what-is-a-merkle-tree/)
- [What is Consensus? - Kartik Nayak, Ittai Abraham](https://decentralizedthoughts.github.io/2019-06-27-defining-consensus/)
- [Flavours of State Machine Replication - Ittai Abraham](https://decentralizedthoughts.github.io/2019-10-25-flavours-of-state-machine-replication/)
- [Consensus for State Machine Replication - Kartik Nayak, Ittai Abraham](https://decentralizedthoughts.github.io/2019-10-15-consensus-for-state-machine-replication/)
- [From Single-Shot Agreement to State Machine Replication](https://decentralizedthoughts.github.io/2022-11-19-from-single-shot-to-smr/)

## Videos
- [E48: The role of decentralization, China/US break down & more with Bestie Guestie Balaji Srinivasan](https://youtu.be/B2iNXMiGEms) 

# 7. Bitcoin
- Two general's Problem
- What Is the Byzantine Generals Problem?

## Readings
- [The Byzantine Generals Problem](https://dl.acm.org/doi/10.1145/357172.357176)
- [Blockchain Basics & Consensus - MIT 15.S12 Blockchain and Money - Gary Gensler](https://www.youtube.com/watch?v=w7HDA8gUbpQ&list=PLUl4u3cNGP63UUkfL0onkxF6MYgVa04Fn)
- [Paxos(etcd) vs. Nakamoto(Bitcoin): consensus](https://gyuho.dev/paxos-etcd-vs-nakamoto-bitcoin-consensus.html)
- [Nakamoto's Longest-Chain Wins Protocol](https://decentralizedthoughts.github.io/2021-10-15-Nakamoto-Consensus/)
- [Learning-Bitcoin-from-the-Command-Line](https://github.com/BlockchainCommons/Learning-Bitcoin-from-the-Command-Line)
- [Bitcoin: A Peer-to-Peer Electronic Cash System](https://bitcoin.org/bitcoin.pdf)
- [But how does bitcoin actually work?](https://youtu.be/bBC-nXj3Ng4) 
- [Cryptoeconomics In 30 Minutes by Vitalik Buterin](https://youtu.be/GQR1xjQn5Pg)

# 8. Ethereum
- Solidity
- ERC20
- ERC721
- ERC-1155
- Merkle Patricia Trie Tree

## Readings
- [DEVCON1: Understanding the Ethereum Blockchain Protocol - Vitalik Buterin](https://youtu.be/gjwr-7PgpN8)
- [Ethereum Whitepaper](https://ethereum.org/en/whitepaper/)
- [Learn Solidity in Y Minutes](https://learnxinyminutes.com/docs/solidity/)
- [Getting Started with Solidity](https://cryptomarketpool.com/getting-started-with-solidity/)
- [OpenZeppelin](https://docs.openzeppelin.com/contracts/4.x/)
- [Go Ethereum](https://geth.ethereum.org/docs)
- [Trie, Merkle, Patricia: A Blockchain Story](https://kronosapiens.github.io/blog/2018/07/04/patricia-trees.html)
- [Ethereum development made easy with Foundry](https://www.notamonadtutorial.com/ethereum-development-made-easy-with-foundry/)
- [scaffold-eth: 🏗 forkable Ethereum dev stack focused on fast product iterations](https://github.com/scaffold-eth/scaffold-eth)
- [Scaffold-Eth Challenges](https://github.com/scaffold-eth/scaffold-eth-challenges)

# 9. Wallets, Dapps and DeFi
- DEX: Uniswap
- Lending: Aave
- Stablecoin: Maker/DAI
- dYdX
- [Metamask and other wallets]()
- DEMO: Uniswap, Curve, OpenSea NFTs, Maker/Oasis, Multisig
- [lil web3: Small, focused, utility-based smart contracts](https://github.com/m1guelpf/lil-web3)
- [Programming DeFi: Uniswap V2. Part 1](https://jeiwan.net/posts/programming-defi-uniswapv2-1/)
- [The Problems with DeFi & Crypto](https://www.lynalden.com/defi-problems/)
- [Programming DeFi: Uniswap V2. Part 1](https://ethereum.org/en/developers/tutorials/uniswap-v2-annotated-code/)
- [Programming DeFi: Uniswap V2. Part 2](https://jeiwan.net/posts/programming-defi-uniswapv2-2/)
- [Programming DeFi: Uniswap V2. Part 3](https://jeiwan.net/posts/programming-defi-uniswapv2-3/)
- [Uniswap V3 Development Book](https://uniswapv3book.com/)

# 9. Oracles, Bridges and Rollups
- Oracles
- Bridges
- [An Incomplete Guide to Rollups](https://vitalik.ca/general/2021/01/05/rollup.html)

# 10. EVM
- [EVM codes](https://www.evm.codes/?fork=merge)
- [EVM: From Solidity to byte code, memory and storage](https://youtu.be/RxL_1AfV7N4)
- [Ethereum Virtual Machine](https://www.youtube.com/watch?v=BsDq2mzC5tk)
- [EVM Deep Dives: The Path to Shadowy Super Coder 🥷 💻 - Part 1](https://noxx.substack.com/p/evm-deep-dives-the-path-to-shadowy)
- [ABI]()

# 11. Security
- [Capture the Ether](https://capturetheether.com/challenges/)
- [Ethernaut](https://ethernaut.openzeppelin.com/)
- [Damn Vulnerable DeFi](https://www.damnvulnerabledefi.xyz/)
- [Solidity Security: Comprehensive list of known attack vectors and common anti-patterns](https://blog.sigmaprime.io/solidity-security.html)

## Tools
- [echidna - Ethereum smart contract fuzzer](https://github.com/crytic/echidna)
- [manticore - Symbolic execution tool](https://github.com/trailofbits/manticore)
- [mythril - Security analysis tool for EVM bytecode](https://github.com/ConsenSys/mythril)

# 12. MEV
- [MEV](https://research.paradigm.xyz/MEV)
- [How To Get Front-Run on Ethereum mainnet](https://www.youtube.com/watch?v=UZ-NNd6yjFM)
- [Video: Honeypots in Ethereum And How To Avoid Them With Tenderly.co Transaction Simulation](https://youtu.be/DDn5mksOUCc)

# 13. Zcash, SNARKs and Privacy in blockchains**
- [Zcash](https://electriccoin.co/blog/category/technical/)
- [Aztec]()
- [zksnarks](https://zkhack.dev/whiteboard/module-one/)
- [arithmetization]()

# 14. Scaling blockchains
- Data Availability
- Optimistic versus Zero Knoweledge Rollups
- Circom, Cairo, Noir

## Readings
- [Data, Consensus, Execution: Three Scalability Bottlenecks for State Machine Replication - Ittai Abraham](https://decentralizedthoughts.github.io/2019-12-06-dce-the-three-scalability-bottlenecks-of-state-machine-replication)
- [Understanding Blockchain Latency and Throughput - Lefteris Kokoris-Kogias](https://www.paradigm.xyz/2022/07/consensus-throughput)
- [(Almost) Everything you need to know about Optimistic Rollup - Georgios Konstantopoulos](https://www.paradigm.xyz/2021/01/almost-everything-you-need-to-know-about-optimistic-rollup)
- [Why rollups + data shards are the only sustainable solution for high scalability - Polynya](https://polynya.medium.com/why-rollups-data-shards-are-the-only-sustainable-solution-for-high-scalability-c9aabd6fbb48)
- [Volitions: best of all worlds - Polynya](https://polynya.medium.com/volitions-best-of-all-worlds-cfd313aec9a8)

# 15. Tendermint, HotStuff and Narwhal
- [What is the difference between PBFT, Tendermint, SBFT and HotStuff? - Ittai Abraham](https://decentralizedthoughts.github.io/2019-06-23-what-is-the-difference-between/)
- [DAG Meets BFT - The Next Generation of BFT Consensus - Ittai Abraham](https://decentralizedthoughts.github.io/2022-06-28-DAG-meets-BFT/)

# 16. Bitcoin: SegWit, Taproot, Lightning Network and Covenants
- [Segregated Witness](https://github.com/bitcoin/bips/blob/master/bip-0141.mediawiki)
- [Taproot: SegWit version 1 spending rules](https://github.com/bitcoin/bips/blob/master/bip-0341.mediawiki)
- [Covenants: CHECKTEMPLATEVERIFY]()
- [A Look at the Lightning Network - Lyn Alden](https://www.lynalden.com/lightning-network/)
- [The Bitcoin Lightning Network: Scalable Off-Chain Instant Payments](https://berkeley-defi.github.io/assets/material/lightning-network-paper.pdf)

# Books
- [Bitcoin and Cryptocurrency Technologies: A Comprehensive Introduction - Arvind Narayanan, Joseph Bonneau, Edward Felten, Andrew Miller, and Steven Goldfeder](https://press.princeton.edu/books/hardcover/9780691171692/bitcoin-and-cryptocurrency-technologies)
- [Security Engineering — Ross Anderson](https://www.cl.cam.ac.uk/~rja14/book.html)

## Blockchain
- [Foundations of Distributed: Consensus and Blockchains - Elaine Shi](http://elaineshi.com/docs/blockchain-book.pdf)

## Cryptography
- [Handbook of Applied Cryptography -  Menezes, van Oorschot and Vanstone]()
- [Crypto 101 - lvh]()

## Abstract Algebra and Number Theory
- [An Introduction to Mathematical Cryptography - Jeffrey Hoffstein, Jill Pipher, Joseph H. Silverman]()
- [A Course in Number Theory and Cryptography - Neal Koblitz]()
- [Algebra for Applications - Arkadii Slinko]()
- [A Computational Introduction to Number Theory and Algebra - Victor Shoup]()
- [Elliptic Curves Number Theory and Cryptography - Lawrence C. Washington]()
- [The prime number conspiracy - Thomas Lin]()

# Courses
- [Practical Cryptographic Systems - Matthew Green](https://github.com/matthewdgreen/practicalcrypto/wiki/Spring-2020-Syllabus)
- [Cryptocurrency Class 2022 - Patrick McCorry](https://cryptocurrencyclass.github.io/)
- [Principles of Blockchains - Pramod Viswanath](https://courses.grainger.illinois.edu/ece598pv/sp2021/)
- [Blockchain And Money - Gary Gensler](https://ocw.mit.edu/courses/15-s12-blockchain-and-money-fall-2018/video_galleries/video-lectures/)
- [Decentralized Finance MOOC - Dan Boneh, Arthur Gervais, Andrew Miller, Christine Parlour and	Dawn Song](https://defi-learning.org/f22)
- [Stanford CS 251 Blockchain Technologies - Dan Boneh](https://cs251.stanford.edu/syllabus.html)
- [Stanford EE374 Blockchain Foundations - David Tse, Dionysis Zindros](https://web.stanford.edu/class/ee374/)
- [ECE595 Foundations of Blockchain Systems - Sreeram Kannan](https://ece595uwseattle.github.io/schedule)
- [CS598CAL Consensus Algorithms - Ling Ren](https://sites.google.com/view/cs598cal?pli=1)

---
# Missing topics
- Light Clients 
- UTXO vs Account model
- The Blockchain Trilemma
- PoS vs PoW
- Soft Forks vs Hard Forks
- Onchain vs offchain computation
- Chinese remainder theorem
- One Time Pad
- MAC
- Account Abstraction (argent x)
- Finality
- muun, non custodial wallets
- life depends onl https://twitter.com/argentHQ/status/1513488734498525184

**Links to add**
- [](https://ethereum.org/en/developers/tutorials/uniswap-v2-annotated-code/)
- https://crypto.stanford.edu/~dabo/courses/OnlineCrypto/
- https://www.youtube.com/channel/UCqeIoMMTKl9PK9O8BcEpNhQ
- https://youtu.be/-6BtBUbiUIU
- https://github.com/decrypto-org/blockchain-papers
- https://blog.ethereum.org/2016/05/09/on-settlement-finality/
- https://medium.com/mechanism-labs/finality-in-blockchain-consensus-d1f83c120a9a#:~:text=In%20the%20blockchain%20setting%2C%20finality,be%20arbitrarily%20changed%20or%20reversed
- https://github.com/Mechanism-Labs/MetaAnalysis-of-Alternative-Consensus-Protocols
- https://www.youtube.com/watch?v=O1Iq27ItGGg
- https://medium.com/@lightcoin/the-differences-between-a-hard-fork-a-soft-fork-and-a-chain-split-and-what-they-mean-for-the-769273f358c9
- https://dspace.mit.edu/handle/1721.1/127476
- https://medium.facilelogin.com/the-mystery-behind-block-time-63351e35603a
- https://dankradfeist.de/ethereum/2021/05/20/what-everyone-gets-wrong-about-51percent-attacks.html
- https://dinhtta.github.io/flpcap/
- https://www.the-paper-trail.org/post/2012-03-25-flp-and-cap-arent-the-same-thing/
- https://youtu.be/mDyBbGCiBUU
- https://medium.com/@alxlpsc/critical-privacy-vulnerability-getting-exposed-by-metamask-693c63c2ce94
- https://www.cnbc.com/2021/08/23/people-are-paying-millions-of-dollars-for-digital-pictures-of-rocks.html
- https://mudit.blog/miso-war-room/
- https://github.com/ConsenSys/surya
- https://youtu.be/DlNDYMNJ5zQ
- [Hayden Adams Explains Uniswap and the Rise of DeFi](https://open.spotify.com/episode/3TT6aFeMWnFPZTlfy5fxvv?si=KCw3uWvJQAaeBCZoH1RwNw&dl_branch=1)
- https://cryptomarketpool.com/getting-started-with-solidity/
- https://www.youtube.com/watch?v=U6q5gBnxgS0&list=PL9lJNCwSDOhVEf0ajBHkNNICFqNnoGx7r&index=4
- https://twitter.com/guiltygyoza/status/1447641997012082693?s=12
- https://blog.zkga.me/announcing-darkforest
- https://github.com/Rari-Capital/solmate
- https://youtu.be/7Kq3YWsysc0
- https://youtu.be/RxL_1AfV7N4
- https://dune.xyz/queries/1161
- https://www.youtube.com/watch?v=B2iNXMiGEms
- https://medium.com/starkware/volition-and-the-emerging-data-availability-spectrum-87e8bfa09bb
- https://jacob-eliosoff.medium.com/whats-the-simplest-possible-decentralized-stablecoin-4a25262cf5e8
- https://writings.flashbots.net/writings/the-anatomy-of-an-inspector/
- https://twitter.com/siegerhino2/status/1445024119112835073?s=21
- https://app.umbra.cash/faq#how-does-umbra-compare-to-tornado-cash-and-aztec
- https://www.samchepal.com/the-hidden-world-of/
- https://www.youtube.com/watch?v=cizLhxSKrAc&t=215s
- https://www.youtube.com/watch?v=Ehm-OYBmlPM
- https://github.com/Mikerah/awesome-foundations-of-DeFi
