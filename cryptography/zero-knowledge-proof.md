# Zero Knowledge Proof

[TOC]

See also my articles: [Main Concept Behind Zero-Knowledge Proof](https://rya-sge.github.io/access-denied/2024/06/17/zero-knowledge-proof-main-concepts/), [Overview of Zero-Knowledge development framework](https://rya-sge.github.io/access-denied/2024/06/10/zero-knowledge-development-framework/)

## General

| Title                                                        | Description                                                  | Date    | Support | Author                        |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------- | ------- | ----------------------------- |
| [Introduction to zk-SNARKs](https://consensys.io/blog/introduction-to-zk-snarks) | An overview of zero-knowledge proofs and how to integrate zk-SNARKs into Ethereum. | 03/2017 | Article | Consensys                     |
| [Zero-Knowledge Proof – How It Works](https://hacken.io/discover/zero-knowledge-proof/) | Introduction to ZKP                                          | 03/2023 | Article | Hacken                        |
| [On Interactive Proofs and Zero-Knowledge: A Primer](https://medium.com/magicofc/interactive-proofs-and-zero-knowledge-b32f6c8d66c3) | Basic understanding of the properties of proof systems, including  zero-knowledge, soundness and completeness and thus the fundamental  properties of zkSNARKs, zkSTARKs, or zkNIZKs | 01/2019 | Article | Yannik Goldgräbe              |
| [Zero Knowledge Proofs](https://ic-people.epfl.ch/~achiesa/docs/CS276-F2015/lecture-19.pdf) |                                                              | 10/2015 | Course  | EPFL CS276                    |
| [ Theory of Computing ](https://courses.cs.cornell.edu/cs6810/2021fa/lec19.pdf) |                                                              | 11/2021 | Course  | Cornell CS 6810               |
| [An Introduction to Zero-Knowledge Proofs in Blockchains<br/>and Economics](https://files.stlouisfed.org/files/htdocs/publications/review/2023/10/02/an-introduction-to-zero-knowledge-proofs-in-blockchains-and-economics.pdf) |                                                              | 10/2023 | Report  | Federal reserve Bank St.Louis |

## Specific

| Title                                                        | Description                                                  | Date    | Support        | Author             |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------- | -------------- | ------------------ |
| [nullifier](https://nmohnblatt.github.io/zk-jargon-decoder/definitions/nullifier.html) | A private value which, once revealed, invalidates (or “nullifies”) some associated object. | <2024   | Article        | nmohnblatt         |
| [Understanding Trusted Setups: A Guide](https://blog.pantherprotocol.io/a-guide-to-understanding-trusted-setups/) | In this article, we will explain the concept of trusted setups in detail along with the need for them, their inner workings, and the different  alternatives to trusted setups in cryptography. | 09/2022 | Article        | Panther            |
| ZK FAQ: What's a trusted setup? What's a Structured Reference String? What's toxic waste? | In proof systems, provers and the verifiers rely on a common set of parameters, sometimes referred to as the **common reference string (CRS)**. | 06/2022 | Article        | cryptologie.net    |
| [Commitment Schemes and<br/>Zero‐Knowledge Protocols](https://www.mimuw.edu.pl/~std/Dydaktyka/BISS09/BISS10.pdf) |                                                              | 03/2009 | Course/Lecture | University of Rome |

### Bulletproof

Specification: [Bulletproofs: Short Proofs for Confidential Transactions and More](https://eprint.iacr.org/2017/1066.pdf), [crypto.stanford.edu - Bulletproofs: Efficient Range Proofs for Confidential Transactions](https://crypto.stanford.edu/~dabo/pubs/abstracts/bulletproofs.html)

See also my article [Zero Knowledge Proofs with Bulletproof](https://rya-sge.github.io/access-denied/2024/08/13/bulletproof-zero-knowledge-proof/)

| Title                                                        | Description                                                  | Date      | Support        | Author               |
| ------------------------------------------------------------ | ------------------------------------------------------------ | --------- | -------------- | -------------------- |
| [Bulletproofs In Crypto – An introduction to a Non-Interactive ZKP](https://blog.pantherprotocol.io/bulletproofs-in-crypto-an-introduction-to-a-non-interactive-zk-proof/) |                                                              | 09/2022   | Article        | Panther team         |
| [What Are Bulletproofs? Guide to Confidential Cryptocurrency Transactions](https://blockonomi.com/bullet-proofs/) | Bulletproofs are an important innovation of zero-knowledge proofs &  other protocols used to secure and obfuscate cryptocurrency transactions | 10/2023   | Article        | blockonomi           |
| [Learning about Bulletproofs](https://tlu.tarilabs.com/learning-paths/bulletproofs) | Learning path                                                | 2018-2019 | Article        | Tari Labs University |
| [github.com/dalek-cryptography/bulletproofs](https://github.com/dalek-cryptography/bulletproofs) | Bulletproofs implementation                                  | 2019      | Github project | dalek-cryptography   |

## Security

| Title                                                        | Description                                                  | Date    | Support | Author                                                       |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------- | ------- | ------------------------------------------------------------ |
| [Fiat-Shamir Exploit to Attack a Plonk Verifier](https://medium.com/@cryptofairy/fiat-shamir-exploit-to-attack-a-plonk-verifier-d8ab544e9536) | This experiment was inspired by a recent YouTube [publication](https://www.youtube.com/watch?v=Sk-S8-n6Jo4) from the OpenZeppelin team titled “The Last Challenge Attack”, which focused on an incorrectly implemented Plonk verifier. | 12/2023 | Article | [Crypto Fairy](https://medium.com/@cryptofairy?source=post_page-----d8ab544e9536--------------------------------) |
|                                                              |                                                              |         |         |                                                              |