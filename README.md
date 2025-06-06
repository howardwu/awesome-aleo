<h1 align="center">awesome-aleo</h1>
<h3 align="center">🏎️ A curated list of Aleo & Leo code and resources 🏎️</h3>

<p align="center">
    <a href="https://awesome.re"><img src="https://awesome.re/badge.svg"></a>
    <a href="https://twitter.com/AleoHQ"><img src="https://img.shields.io/twitter/url/https/twitter.com/AleoHQ.svg?style=social&label=Follow%20%40AleoHQ"></a>
    <a href="https://aleo.org/discord"><img src="https://img.shields.io/discord/700454073459015690?logo=discord"/></a>
</p>

If you'd like to contribute, please read [this](./CONTRIBUTING.md).

## Table of Contents

- [Table of Contents](#table-of-contents)
- [Announcements \& News](#announcements--news)
- [Presentations \& Talks](#presentations--talks)
- [Research Papers \& Resources](#research-papers--resources)
- [Workshops](#workshops)
- [Core Libraries](#core-libraries)
- [Development Tools](#development-tools)
  - [Decompilers](#decompilers)
  - [Hardware Acceleration](#hardware-acceleration)
  - [Playgrounds](#playgrounds)
  - [Syntax Highlighters](#syntax-highlighters)
  - [Python Developer Tooling](#python-developer-tooling)
  - [Testing Toolkit](#testing-toolkit)
  - [Security](#security)
- [Applications](#applications)
  - [Algorithms](#algorithms)
  - [Art](#art)
  - [Bridging](#bridging)
  - [Decentralized Finance (DeFi)](#decentralized-finance-defi)
  - [Explorers](#explorers)
  - [Identity \& Authentication](#identity--authentication)
  - [Gaming](#gaming)
  - [Governance](#governance)
  - [Machine Learning](#machine-learning)
  - [Marketplaces](#marketplaces)
  - [NFT Marketplaces \& Launchpads](#nft-marketplaces--launchpads)
  - [NFT Infrastructure ](#nft-infrastructure)
  - [Tools](#tools)
  - [Oracles](#oracles)
  - [Wallets](#wallets)
  - [Wallet SDKs \& More](#wallet-sdks--more)
  - [ZPass Integrations](#zpass-integrations)

## Announcements & News

- [Aleo Discord](https://aleo.org/discord) - The official Aleo Discord channel
- [Aleo Twitter](https://twitter.com/AleoHQ) - The official Aleo Twitter account

## Presentations & Talks

- [Introduction to zkSNARKs with Howard Wu](https://zeroknowledge.fm/38-2/) - Zero Knowledge Podcast: Episode 38
- [Demystifying Zero-Knowledge Programming](https://www.youtube.com/watch?v=-FrrylHITvg) - Introduction to the Record Model
- [zkWhiteBoard Session with Pratyush Mishra](https://zkhack.dev/whiteboard/module-eight/) - ZKHack: zkWhiteBoard Session on Zexe and Aleo
- [Aleo with Howard Wu](https://zeroknowledge.fm/144-2/) - Zero Knowledge Podcast: Episode 144
- [Efficient Private Delegation of zkSNARK Provers](https://www.youtube.com/watch?v=iT_s92f3wds) - ZKSummit 7: Pratyush Mishra
- [The Importance of Zero-knowledge Proof with Alex Pruden](https://player.fm/series/coingecko-podcast-bitcoin-cryptocurrency-insights/the-importance-of-zero-knowledge-proof-with-alex-pruden-coo-of-aleo-ep64) - CoinGecko Podcast

## Research Papers & Resources

- [Zexe](https://eprint.iacr.org/2018/962.pdf) - Zexe: Enabling Decentralized Private Computation
- [Marlin](https://eprint.iacr.org/2019/1047.pdf) - Marlin: Preprocessing zkSNARKs with Universal and Updatable SRS
- [Leo](https://eprint.iacr.org/2021/651.pdf) - Leo: A Programming Language for Formally Verified,
  Zero-Knowledge Applications
- [Poseidon](https://eprint.iacr.org/2019/458.pdf) - Poseidon: A New Hash Function for Zero-Knowledge Proof Systems
- [AVM Opcodes](https://github.com/AleoHQ/ARCs/tree/master/arc-0002) - Aleo Virtual Machine (AVM) Opcodes
- [PoNW](https://eprint.iacr.org/2020/190.pdf) - Proof of Necessary Work: Succinct State Verification with Fairness Guarantees

---

## Workshops

- [zkWorkshop | Programming with Leo - Zero-Knowledge DSL](https://www.youtube.com/watch?v=8lMMAGKps9A) – Pranav Gaddamadugu, ETHDenver (2025) 
- [zkWorkshop | Building Compliant Privacy-Preserving Tokens](https://www.youtube.com/watch?v=MnAZX4cn9kM) – Evan Marshall, ETHDenver (2025)
- [zkWorkshop | Universal Wallet Integration on Aleo](https://www.youtube.com/watch?v=5PELenxPPO0) – Matt Wyatt, ETHDenver (2025)
- [zkWorkshop | Scalable Private Identity Solutions with zPass](https://www.youtube.com/watch?v=lvQacYX-QIo) – ZK Lim, ETHDenver (2025)
- [zkWorkshop | Building Private DeFi Applications](https://www.youtube.com/watch?v=2nXWH_j0Tus) – Max Sultakov, ETHDenver (2025)
- [Technical Workshop by Laisha](https://www.youtube.com/watch?v=8RFpd8U2bHg) – House of ZK (2025)
- [Building a Private dApp on Aleo](https://www.youtube.com/watch?v=slVmiwqNiRw) – Building Auction Program (2024)
- [zPass and Verification Program Tutorial](https://www.youtube.com/watch?v=eZYw0q4Zans) –  zkWorkshop (2024)
- [The Aleo Advantage presented by Anthony](https://www.youtube.com/watch?v=Dv0zcy4YZLs) – Blockchain Futurist Conference (2023)
- [Aleo Workshop Part 1](https://www.youtube.com/watch?v=MN1vtf4q7GM) – ZK Hack (2022)
- [Aleo Workshop Part 2](https://www.youtube.com/watch?v=gwLoMBXKswc) – ZK Hack (2022)

---

## Core Libraries

- [SDK](https://github.com/AleoHQ/aleo) - A Software Development Kit (SDK) for Zero-Knowledge Transactions
- [Leo](https://github.com/AleoHQ/leo) - A Functional, Statically-Typed Language for Zero-Knowledge Applications
- [snarkOS](https://github.com/AleoHQ/snarkOS) - A Decentralized Operating System for Zero-Knowledge Applications
- [snarkVM](https://github.com/AleoHQ/snarkVM) - A Virtual Machine for Zero-Knowledge Executions

## Development Tools

### Decompilers

- [AleoVera](https://github.com/FuzzingLabs/aleovera) - The Aleo bytecode analyzer and disassembler
- [AleoPathy](https://github.com/HH-0rg/aleopath) - Online Disassembler and Decompiler

### Hardware Acceleration

- [ZPrize](https://zprize.io/) - Dedicated to Accelerating the Future of Zero-Knowledge Cryptography
- [Accelerating MSM on GPUs/FPGAs](https://github.com/z-prize/prize-gpu-fpga-msm) - Accelerating multi-scalar multiplications on GPUs/FPGAs
- [Accelerating MSM on Mobile](https://github.com/celo-org/zprize-mobile-harness) - Accelerating multi-scalar multiplications on mobile

### Playgrounds

- [Leo Playground](https://play.leo-lang.org/) - The official playground for Leo programs

### Syntax Highlighters

- [IntelliJ - Leo](https://plugins.jetbrains.com/plugin/19890-aleo-developer) - The official Leo plugin for IntelliJ
- [Sublime Text - Leo](https://packagecontrol.io/packages/LSP-leo) - The official Leo plugin for Sublime Text
- [VSCode - Leo](https://marketplace.visualstudio.com/items?itemName=aleohq.leo-extension) - The official Leo plugin for VSCode
- [vim - Aleo](https://github.com/julesdesmit/aleo.vim) - An unofficial Vim plugin for Aleo instructions

### Python Developer Tooling

- [Leo Program Runner](https://github.com/snowtigersoft/run_leo) - Python hooks to load and execute Leo programs

### Testing Toolkit

- [DokoJS](https://github.com/venture23-aleo/doko-js/tree/main) - Powerful and lightweight library designed for seamless interaction with the Aleo blockchain
- [Amareleo](https://github.com/kaxxa123/amareleo-chain) - Starting from the SnarkOS codebase, amareleo-chain delivers a minimal validator node for testing the deployment and execution of aleo programs

### Security
- [Vanguard for Aleo](https://github.com/Veridise/vanguard-aleo) - Static analyzer for Leo/Aleo programs
  - [aleo2json](https://github.com/Veridise/aleo2json) - Compiler for Aleo -> JSON
  - [aleo2llvm](https://github.com/Veridise-Partnerships/aleo2llvm) - Compiler for Aleo -> LLVM

## Applications

The following is a curated list of applications powered by Aleo.

### Algorithms

- [fixed-point numbers](https://github.com/zeroknowledgetutorials/leo-fixed-point-numbers) - An implementation of fixed-point numbers and calculations in Leo
- [is_prime](https://github.com/arosboro/is_prime) - An Aleo program to issue prime tokens
- [leo/bubblesort](https://github.com/AleoHQ/leo/tree/testnet3/examples/bubblesort) - A bubble-sort algorithm implementation in Leo
- [leo/groups](https://github.com/AleoHQ/leo/tree/testnet3/examples/groups) - An example of group operations in Leo
- [leo/twoadicity](https://github.com/AleoHQ/leo/tree/testnet3/examples/twoadicity) - An implementation of computing the two-adicity in Leo
- [leo-elgamal](https://github.com/ewynx/leo-elgamal) - Multiplicative homomorphic encryption using ElGamal

### Art

- [art-factory](https://github.com/demox-labs/art-factory) - A fully functioning dapp, ready to deploy your own NFT collection with.
- [Privacy Pride](https://www.privacypride.com/) - A deployed, production version of art factory, hosting Aleo's first NFT collection.
- [Setup Ceremony NFTs](https://opensea.io/collection/fluctuations-by-aleo) - NFTs for the Aleo Setup Ceremony participants
- [Artgo](https://github.com/artgo-labs/artgo) - An AIGC-based NFT creating and trading platform
- [Aleo.store](https://aleo.store) - Aleo NFT Marketplace and Open source NFT standard proposition.

### Bridging

- [Eclipse](https://github.com/eqlabs/eclipse) - Bridging ecosystems by storing zero-knowledge proofs of Solana votes on Aleo
- [IZAR](https://github.com/izar-bridge/aleo-contracts) - A privacy-preserving cross-chain interoperability protocol between Ethereum and Aleo
- [Verulink](https://github.com/venture23-aleo/verulink) - A trusted bridge platform that is designed to help move assets like ETH, USDC, and USDT between Aleo and Ethereum blockchain.

### Decentralized Finance (DeFi)

- [leo/token](https://github.com/ProvableHQ/leo-examples/tree/main/token) - An Aleo custom asset example
- [ARC20 draft](https://github.com/Entropy1729/ARC20_leo) - An ARC20 token draft proposal
- [ARC0721](https://github.com/ProvableHQ/ARCs/tree/master/arc-0721) - An ARC-721 implementation
- [AtomiK](https://github.com/AtomicZK/atomiK-protocol) - DEX doing cross-chain atomic swaps with ZK for liquidity providing, increasing security in bridging between Aleo & XDC (EVM compatible chains).
- [AleoSwap](https://github.com/aleoswap-labs/aleoswap) - A decentralized exchange (DEX) built on the Aleo blockchain
- [Arcane Finance](https://github.com/arcane-finance-defi/rfq-aleo-dex) - A privacy-centric decentralized exchange (DEX) combining both RFQ and AMM models on Aleo
- [DistroFund](https://github.com/weichain/DistroFund) - A Decentralized application that enables an end user to send a token to multiple addresses in a single transaction.
- [Privx](https://github.com/privx-exchange/privx-exchange-contract) - The First Orderbook DEX with On-chain Privacy on Aleo
- [Staking.xyz](https://staking.xyz/) - Making staking easy for everyone, starting with Aleo!
- [Spectre](https://github.com/spectrehq/spectre) - Spectre liquidity protocol on Aleo: Stake credits, earn rewards, and borrow assets.
- [Beta Staking](https://github.com/betastaking-labs) – Staking services  
- [Brale.xyz](https://github.com/Brale-xyz) – DeFi services focused to stablecoins 
- [Pondo.xyz](https://github.com/pondo-xyz) – Liquid staking service on Aleo
- [LSP Finance](https://www.lsp.finance/) – Staking services
- [Money Market](https://github.com/venture23-aleo/money-market) – *[In Development]*  
- [Proof of Bitcoin](https://github.com/vicsn/snarkvm-btc-balance-verification/tree/ecdsa) - Proof of Bitcoin reserves on Aleo: lock sats, generate zero-knowledge proofs, and publicly verify whale balances—no double-spend, all private by design.

### Explorers

- [Aleo Explorer](https://www.aleo.network/) - The official blockchain explorer for Aleo
- [Hamp Explorer](https://explorer.hamp.app/) - Haruka's Aleo Explorer
- [Aleo123 Explorer](https://Aleo123.io/) - Aleo123 Explorer
- [Aleo Info Explorer](https://aleo.info/) - Aleo Info Explorer
- [Aleo Box](https://aleobox.org/) – Discover applications on Aleo  

### Identity & Authentication

- [Nemean](https://github.com/AleoHQ/nemean) - A CLI and SDK for custodians and engineers to interact with the Aleo network
  - [Pine Street Labs Fireside Chat](https://www.youtube.com/watch?v=B4lqbuyNozU&ab_channel=Aleo) - Fireside chat with the Pine Street Labs team
- [Spruce DID Kit](https://www.spruceid.dev/didkit/didkit-examples/core-functions-with-aleo) - Issuance and verification of verifiable credentials using Aleo accounts
  - [Spruce Fireside Chat](https://www.youtube.com/watch?v=9L9xSxgvuX8&ab_channel=Aleo) - Fireside chat with the Spruce team
- [zkDrop](https://github.com/4sm-ops/zkDrop/) - Digital ID and secure file sharing concept based on Aleo
- [ANS](https://github.com/S-T-Soft/aleo-name-service-contract) - The Aleo Naming Service
- [zkKYC](https://github.com/B1boid/zk-KYC) - A privacy preserving Know Your Customer (KYC) application built on Aleo.
- [AleoGuard](https://github.com/gitshreevatsa/AleoGuard) - A Privacy driven Identity aggregator for plug-and-play SSO built on Aleo
- [Alei](https://alei.ssiprotocol.com) - Leo apps secured by Tyron Social Recovery.
- [Aleo Privacy Pool using zkpID](https://github.com/etoneclab/zkpid-aleo-demo) - A demo for threshold-based, privacy-preserving & KYC-ed Aleo transactions using a privacy pool.
- [Aleo Voice Mail](https://github.com/Elexy101/Aleo-Voice-Mail) - A voice text program designed for sending voice messages between two users (sender/receiver) on Aleo.
- [zkSign](https://github.com/lamdanghoang/zk_aleo) – Sign documents on Aleo
- [Wise Pass](https://www.wisepass.co/) – Lifestyle platform  
- [VerifAleo](https://github.com/esren0x/kycNFT) - Users mint an identity NFT with an expiry block so dApps can verify compliance without storing personal data

### Gaming

- [Where's Alex](https://github.com/puzzlehq/wheres_alex) - A multiparty hidden information game on Aleo
- [Super Leo Lig](https://superleolig.online/) - - Challenge a friend to an on-chain soccer game with hidden strategies
- [Puzzle SDK for zkGames](https://docs.puzzle.online/tutorials/build_your_first_zkgame/) - A SDK for building multiparty hidden information games on Aleo
- [Zenet](https://github.com/ZenetGame/ZenetAleo) - The ancient Egyptian game of Senet on Aleo
- [Battleship](https://github.com/demox-labs/zk-battleship) - ZK Battleship on Aleo
- [CoinFlip](https://github.com/demox-labs/zk-coinflip) - A 2-party random coin flip on Aleo
- [Roulette](https://github.com/Entropy1729/aleo_roulette) - A Roulette web app built on Aleo
- [leo/tictactoe](https://github.com/AleoHQ/leo/tree/testnet3/examples/tictactoe) - An implementation of TicTacToe in Leo
- [Boloney](https://github.com/Kryha/boloney) - An online multiplayer dice game showcasing the potential of Aleo's ZKP platform
- [ZK Gaming Toolkit](https://github.com/Kryha/zk-gaming-toolkit) - A toolkit with a variety of pre-built primitives written in Leo for ZK-powered games
- [ZK Commitments for atomic Sudoku swaps](https://github.com/dorebell/zksudoku) - Greg Maxwell’s Zero Knowledge Contingent Payments
- [Aleo Monopoly](https://github.com/Elexy101/Aleo-Monopoly) - Simple game of Monopoly written in Leo
- [Aleo Wordle](https://github.com/pineappleworkshop/aleo-zordle) - Wordle on Aleo
- [Rock, Paper, Scissors](https://github.com/pineappleworkshop/aleo-roshambo) - Rock, Paper, Scissors on Aleo.
- [Sudoku, Wordle, and Trivia](https://github.com/ruizehung/Zero-Knowledge-Sudoku-Wordle-Trivia) - Sudoku, Wordle, and Trivia in Leo.
- [ZK Stratego](https://github.com/evan-schott/zk-stratego) - A game of Stratego, themed as a crypto company.
- [QuizGame](https://github.com/liolikus/QuizGame) - Simple and fully documented React-based Quiz Game.
- [Onchain VRF](https://github.com/onchain-vrf/aleo-onchain-vrf) - An on-chain Verifiable Random Function (VRF) for on-chain, turn-based games.
- [Memorygame](https://github.com/microbecode/zk-memorygame) - A card guessing game on Aleo.
- [Heads or Tails](https://github.com/DyxaDevelop/headsortails.aleo) - A heads-or-tails game on Aleo.
- [BotBusters](https://github.com/Kryha/bot-busters) – Chat and spot the bots
- [zkPlanet](https://github.com/marlonedwards/zkPlanet) – A resource management and civilization game
- [Treasure Hunt](https://treasures.puzzle.online/) – Hidden treasure hunts by Puzzle
- [The Solo Gambit](https://github.com/mikebenfield/pawnstorm) - Chess with bombs: capture a piece and trigger a secret explosion zone that reshapes the board.
- [RetroBeatz](https://github.com/wei-provable/midi-player) - A lightning quiz of retro game tunes—guess the soundtrack from a few bars of 8-bit or 16-bit nostalgia.
- [Knightfall](https://github.com/dgrkotsonis/knightfall-aleo ) - Fog-of-war chess on Aleo

### Governance

- [MACI](https://github.com/Entropy1729/aleo_minimum_anti_collusion_infrastructure) - Minimum Anti-Collusion Infrastructure on Aleo
- [Aleo-Vote](https://github.com/zkprivacy/aleo-vote) - A ZK voting application on Aleo
- [leo/vote](https://github.com/AleoHQ/leo/tree/testnet3/examples/vote) - An example propose and vote mechanism build using Leo
- [ZK Suggestion Box](https://github.com/demox-labs/zk-suggestion-box) - An anonymous suggestion box built on Aleo
- [zVote](https://github.com/zsociety-io/zvote) – ZK voting system  
  - [zVote Official Site](https://www.zvote.io/)  
  
### Machine Learning

- [Neural Network Inference](https://github.com/zeroknowledgetutorials/leo-neural-networks) - An implementation of a neural network inference in Leo and Python
- [Numerical Optimization](https://github.com/vicsn/leo-numerical-optimization) - Proving stocastic gradient descent using Leo and Otti
- [Linear Regression](https://github.com/kpandl/leo-linear-regression) - Univariate linear regression in Leo
- [Run Leo](https://github.com/snowtigersoft/run_leo) - A python package that transpiles Leo code to Python
- [Generate Leo](https://github.com/stakemepro/aleo-zkml-initiative-1) - A python package that generates Leo code from Python
- [Boosting Models](https://github.com/Danielto1404/aleo-boosting) - Privacy preserving ML using Boosting models on Aleo
- [Gini Coefficient, Decision Tree, K-Means](https://github.com/storswiftlabs/zkML) - A library of machine learning algorithms implemented in Leo
- [zkKYC](https://github.com/B1boid/zk-KYC) - KYC platform using zkML (Zero-knowledge Machine Learning) algorithms on Aleo blockchain.
- [Zero Gravity](https://github.com/zkp-gravity/0g) - Proving an inference pass for a public Weightless Neural Network run on a private input.
- [Leo Quantization](https://github.com/storswiftlabs/leo-quantization) - Use quantized data in the zkML program in Leo and perform operations on quantized data.

### Marketplaces

- [leo/auction](https://github.com/AleoHQ/leo/tree/testnet3/examples/auction) - An auction record format built in Leo
- [Anonymous Rating Survey](https://github.com/CredLancer/CredLancer_Aleo) - A program to add anonymous ratings to Dapps
- [PriceProof](https://github.com/bendyarm/priceproof/tree/main/leo/price_proof_test_1) - On-chain price prediction markets secured by ZK proofs, so you can bet on future moves with absolute trust in the outcome.
- [lodive](https://github.com/alexpitsikoulis/lodive) - A ticketing platform that issues encrypted, non-transferable passes.

### NFT Marketplaces & Launchpads

- [Arcane Launchpad](https://launchpad.arcane.finance/) – Launch new NFT projects  
- [NFT Marketplace (Venture23)](https://venture23.io/) – In development  

### NFT Infrastructure 

- [Private NFT Mint](https://github.com/demox-labs/aleo-nft) – Mint in private  
- [Data Custody Protocol](https://github.com/zsociety-io/aleo-dcp) – Secure data ownership via NFTs  

### Tools

- [Aleomail](https://www.aleomail.xyz/) – Private email on Aleo  
- [Record Scanner](https://github.com/demox-labs/aleo-record-scanner) – Verify Aleo records  
- [ZKGaming Kit](https://github.com/Kryha/zk-gaming-toolkit) – Pre-built ZK primitives  
- [Obscura](https://obscura.build/) – Privacy-focused project  

### Oracles

- [Aleo Oracle](https://docs.aleooracle.xyz) - A general purpose, TEE-based blockchain oracle for Aleo
- [snorkle](https://github.com/d0cd/snorkle) - A privacy-preserving oracle that securely brings real-world data on-chain 

### Utility

- [Daddy's Orders](https://github.com/christianwwwwwwww/daddys-orders) - Randomized, zero-knowledge ordering system

### Wallets

- [Avail Wallet](https://github.com/AvailX/avail-wallet) – A mobile wallet on Aleo focused on enabling real world use of private self custody.
- [Coffer](https://github.com/coffer-aleo/coffer-wallet) - Multisig Smart Contract Wallet on Aleo
- [Leo Wallet](https://www.demoxlabs.xyz/) – A simple and private wallet for Aleo.
- [Fox Wallet](https://foxwallet.com/) – Multi-chain extension & mobile wallet.
- [Puzzle Wallet](https://puzzle.online/wallet) – A mobile and extension wallet with Aleo Account Abstraction to explore Aleo, play zkGames & earn rewards
- [Soter Wallet](https://sotertech.io/) – Digital crypto wallet for Aleo blockchain 

### Wallet SDKs & More
- [Aleo Faucet](https://faucet.aleo.org) - The official Aleo Testnet Faucet
- [Aleo Faucet Soter](https://faucetbeta.sotertech.io/) - Request Aleo Tokens from Soter on Testnet Beta
- [Puzzle SDK](https://docs.puzzle.online/) - A SDK for integrating with Puzzle, Avail and any other WalletConnect based wallets.
- [(Unofficial) Account SDK](https://github.com/qqmee/aleo-sdk) - An unofficial account SDK for Aleo
- [Leo Wallet Adapter SDK](https://github.com/demox-labs/aleo-wallet-adapter) - A SDK for integrating with the Leo wallet
- [Aleo Wallet Connect Standards](https://docs.puzzle.online/sdk-free/overview/) - A walletconnect standard for Aleo wallets
- [Aleo Wallet Hooks](https://github.com/OrdosHQ/aleo-hooks) – Integrate Aleo wallets easily  
- [iOS Swift Aleo Wallet Starter Kit](https://github.com/puzzlehq/zksummit_ios_workshop) - A workshop & repo for getting started making your own Aleo iOS client
- [Metamask Snap - Aleo](https://github.com/bide-dev/aleo-wallet-snap) - A MetaMask-compatible wallet extension for Aleo accounts
- [MetaMask Snap (Official)](https://snaps.metamask.io/snap/npm/chainsafe/aleo-snap/) - Official MetaMask Snap for Aleo

### ZPass Integrations

- [3oC (Three of Cups)](https://www.3oc.world/) – Zero-knowledge identity  
- [WORLD3](https://world3.ai/) – ZK-enabled AI & privacy  
- [PLAYSIDE.gg](https://www.playside.gg/) – ZK-powered gaming identity  
- [GENIE (The Genius School8)](https://genii-dao.gitbook.io/geniidao-loose-leaf-white-paper) – ZK learning platform  
