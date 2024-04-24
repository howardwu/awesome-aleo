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
- [Core Libraries](#core-libraries)
- [Development Tools](#development-tools)
  - [Decompilers](#decompilers)
  - [Hardware Acceleration](#hardware-acceleration)
  - [Playgrounds](#playgrounds)
  - [Syntax Highlighters](#syntax-highlighters)
  - [Python Developer Tooling](#python-developer-tooling)
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
  - [Oracles](#oracles)
  - [Wallets](#wallets)

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
- [leo-elgamal](https://github.com/aerius-labs/leo-elgamal) - Multiplicative homomorphic encryption using ElGamal

### Art

- [art-factory](https://github.com/demox-labs/art-factory) - A fully functioning dapp, ready to deploy your own NFT collection with.
- [Privacy Pride](https://www.privacypride.com/) - A deployed, production version of art factory, hosting Aleo's first NFT collection.
- [Setup Ceremony NFTs](https://opensea.io/collection/fluctuations-by-aleo) - NFTs for the Aleo Setup Ceremony participants
- [Artgo](https://github.com/artgo-labs/artgo) - An AIGC-based NFT creating and trading platform
- [Aleo.store](https://aleo.store) - Aleo NFT Marketplace and Open source NFT standard proposition.

### Bridging

- [Eclipse](https://github.com/eqlabs/eclipse) - Bridging ecosystems by storing zero-knowledge proofs of Solana votes on Aleo
- [IZAR](https://github.com/izar-bridge/aleo-contracts) - A privacy-preserving cross-chain interoperability protocol between Ethereum and Aleo

### Decentralized Finance (DeFi)

- [aleo/token](https://github.com/AleoHQ/aleo/tree/testnet3/examples/token) - An Aleo custom asset example
- [ARC20 draft](https://github.com/Entropy1729/ARC20_leo) - An ARC20 token draft proposal
- [ARC-721 Draft](https://github.com/AleoHQ/ARCs/discussions/36) - An ARC-721 draft proposal
- [AtomiK](https://github.com/AtomicZK/atomiK-protocol) - DEX doing cross-chain atomic swaps with ZK for liquidity providing, increasing security in bridging between Aleo & XDC (EVM compatible chains).
- [AleoSwap](https://github.com/aleoswap-labs/aleoswap) - A decentralized exchange (DEX) built on the Aleo blockchain
- [Arcane Finance](https://github.com/arcane-finance-defi/rfq-aleo-dex) - A privacy-centric decentralized exchange (DEX) combining both RFQ and AMM models on Aleo
- [AleoPad](https://aleopad.com/)
- [DistroFund](https://github.com/weichain/DistroFund) - A Decentralized application that enables an end user to send a token to multiple addresses in a single transaction.
- [Privx](https://github.com/privx-exchange/privx-exchange-contract) - The First Orderbook DEX with On-chain Privacy on Aleo
- [Staking.xyz](https://staking.xyz/) - Making staking easy for everyone, starting with Aleo!

### Explorers

- [Aleo Explorer](https://www.aleo.network/) - The official blockchain explorer for Aleo
- [Hamp Explorer](https://explorer.hamp.app/) - Haruka's Aleo Explorer
- [Aleo123 Explorer](https://Aleo123.io/) - Aleo123 Explorer

### Identity & Authentication

- [Nemean](https://github.com/AleoHQ/nemean) - A CLI and SDK for custodians and engineers to interact with the Aleo network
  - [Introducing Nemean](https://blog.pinestreetlabs.com/pine-street-labs-aleo-introducing-nemean/) - Blog post written by Pine Street Labs explaining Nemean
  - [Aleo Grant Recipient: Pine Street Labs](https://www.aleo.org/post/aleo-grants-pine-street-labs) - Transcript interview with Pine Street Labs
  - [Pine Street Labs Fireside Chat](https://www.youtube.com/watch?v=B4lqbuyNozU&ab_channel=Aleo) - Fireside chat with the Pine Street Labs team
- [Spruce DID Kit](https://www.spruceid.dev/didkit/didkit-examples/core-functions-with-aleo) - Issuance and verification of verifiable credentials using Aleo accounts
  - [Spruce Fireside Chat](https://www.youtube.com/watch?v=9L9xSxgvuX8&ab_channel=Aleo) - Fireside chat with the Spruce team
- [zkDrop](https://github.com/4sm-ops/zkDrop/) - Digital ID and secure file sharing concept based on Aleo
- [ANS](https://github.com/S-T-Soft/aleo-name-service-contract) - The Aleo Naming Service
- [zkKYC](https://github.com/B1boid/zk-KYC) - A privacy preserving Know Your Customer (KYC) application built on Aleo.
- [AleoGuard](https://github.com/gitshreevatsa/AleoGuard) - A Privacy driven Identity aggregator for plug-and-play SSO built on Aleo
- [Alei](https://alei.ssiprotocol.com) - Leo apps secured by Tyron Social Recovery.

### Gaming

- [Where's Alex](https://github.com/puzzlehq/wheres_alex) - A multiparty hidden information game on Aleo
- [Treasure Hunt](https://treasures.puzzle.online/) - A multiparty hidden treasure hunt game on Aleo
- [Super Leo Lig](https://superleolig.online/) - - Challenge a friend to an on-chain soccer game with hidden strategies
- [Aleo Fortune](https://aleo-fortune.vercel.app/) - Play classic casino games like roulette and more on Aleo
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
- [Rock, Paper, Scissors](https://github.com/pineappleworkshop/aleo-roshambo) - Rock, Paper, Scissors on Aleo
- [Sudoku, Wordle, and Trivia](https://github.com/ruizehung/Zero-Knowledge-Sudoku-Wordle-Trivia) - Sudoku, Wordle, and Trivia in Leo
- [ZK Stratego](https://github.com/evan-schott/zk-stratego) A game of Stratego, themed as a crypto company
- [QuizGame](https://github.com/liolikus/QuizGame) Simple and fully documented React-based Quiz Game
- [Onchain VRF](https://github.com/onchain-vrf/aleo-onchain-vrf) An Onchain Verifiable Random Function for on-chain turn based games.
- [Memorygame](https://github.com/microbecode/zk-memorygame) A card guessing game on Aleo

### Governance

- [MACI](https://github.com/Entropy1729/aleo_minimum_anti_collusion_infrastructure) - Minimum Anti-Collusion Infrastructure on Aleo
- [Aleo-Vote](https://github.com/zkprivacy/aleo-vote) - A ZK voting application on Aleo
- [leo/vote](https://github.com/AleoHQ/leo/tree/testnet3/examples/vote) - An example propose and vote mechanism build using Leo
- [ZK Suggestion Box](https://github.com/demox-labs/zk-suggestion-box) - An anonymous suggestion box built on Aleo

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
- [Anonymous Rating Survey)(https://github.com/CredLancer/CredLancer_Aleo)- A program to add anonymous ratings to Dapps

### Oracles

- [Aleo Oracle](https://docs.aleooracle.xyz) - A general purpose, TEE-based blockchain oracle for Aleo 

### Wallets

- [Aleo Faucet](https://faucet.aleo.org) - The official Aleo Testnet Faucet
- [Puzzle Wallet](https://puzzle.online/) - A mobile and extension wallet with Aleo Account Abstraction to explore Aleo, play zkGames & earn rewards
- [Puzzle SDK](https://docs.puzzle.online/) - A SDK for integrating with Puzzle, Avail and any other WalletConnect based wallets.
- [Aleo Wallet Connect Standards](https://docs.puzzle.online/sdk-free/overview/) - A walletconnect standard for Aleo wallets
- [iOS Swift Aleo Wallet Starter Kit](https://github.com/puzzlehq/zksummit_ios_workshop) - A workshop & repo for getting started making your own Aleo iOS client
- [Metamask Snap - Aleo](https://github.com/bide-dev/aleo-wallet-snap) - A MetaMask-compatible wallet extension for Aleo accounts
- [(Unofficial) Account SDK](https://github.com/qqmee/aleo-sdk) - An unofficial account SDK for Aleo
- [Leo Wallet](https://leo.app/) - A simple and private wallet for Aleo. Early access waitlist now open.
- [Leo Wallet Adapter SDK](https://github.com/demox-labs/aleo-wallet-adapter) - A SDK for integrating with the Leo wallet
- [Avail](https://avail.global) - A mobile wallet on Aleo focused on enabling real world use of private self custody.
- [Coffer](https://github.com/coffer-aleo/coffer-wallet) - Multisig Smart Contract Wallet on Aleo
- [MetaMask Snap (Official)](https://snaps.metamask.io/snap/npm/chainsafe/aleo-snap/) - Official MetaMask Snap for Aleo
