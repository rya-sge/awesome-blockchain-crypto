# Proxy

Resources related to proxy

My article: [Programming proxy contracts with OpenZeppelin - Summary](https://rya-sge.github.io/access-denied/2022/10/31/proxy-contract-summary/)

Relevant ERC:

- [ERC-1967: Proxy Storage Slots](https://eips.ethereum.org/EIPS/eip-1967) (finalized)
- [ERC-1822: Universal Upgradeable Proxy Standard (UUPS) ](https://eips.ethereum.org/EIPS/eip-1822)
- [ERC-1167: Minimal Proxy Contract](https://eips.ethereum.org/EIPS/eip-1167) (finalized)
- [ERC-2535: Diamonds, Multi-Facet Proxy Create modular smart contract systems that can be extended after deployment](https://eips.ethereum.org/EIPS/eip-2535) (finalized)
- [ERC-7504: Dynamic Contracts](https://ethereum-magicians.org/t/erc-7504-dynamic-contracts/15551) (draft)

[TOC]





## General

| Title                                                        | Description                                                  | Date              | Support                 | Author                                   |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ----------------- | ----------------------- | ---------------------------------------- |
| [Upgradable Smart Contracts - What is a Smart Contract Proxy Pattern?](https://www.cyfrin.io/blog/upgradeable-proxy-smart-contract-pattern) | Proxy Smart Contracts patterns are a simple and effective way to create  upgradable smart contracts to keep your protocol up to date. | 04/2024           | Article                 | Ciara Nightingale / Cyfrin               |
| [OpenZeppelin - Proxy Upgrade Pattern](https://docs.openzeppelin.com/upgrades-plugins/1.x/proxies) | This article describes the "unstructured storage" proxy pattern, the fundamental building block of OpenZeppelin Upgrades. | -                 | Doc                     | OpenZeppelin                             |
| [Proxies in smart contracts thread](https://twitter.com/dimo_audit/status/1698324235595260398) | We'll go with diagrams one by one over: Eternal Storage Proxy Transparent Upgradeable Proxy UUPS, Minimal Proxies / Clones, Beacon Proxies | September 3, 2023 | Article                 | dimo_audit                               |
| [Proxy Patterns For Upgradeability Of Solidity Contracts: Transparent vs UUPS Proxies](https://mirror.xyz/0xB38709B8198d147cc9Ff9C133838a044d78B064B/M7oTptQkBGXxox-tk9VJjL66E1V8BUF0GF79MMK4YG0) |                                                              | March 22, 2022    | Article                 | Naveen                                   |
| [A Comprehensive Survey of Upgradeable Smart Contract Patterns](https://arxiv.org/pdf/2304.03405.pdf) |                                                              | ~2020             | Research  paper (arxiv) | Sajad Meisami, William Edward Bodell III |
| [yAcademy Proxies Research](https://proxies.yacademy.dev)    |                                                              | ?                 | Several articles        | yAcademy                                 |



## Specific topic

| Title                                                        | Description                                                  | Date               | Support | Author                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------ | ------- | ------------------------------ |
| [Minimal Proxy Compendium](https://banteg.xyz/posts/minimal-proxies/) | The history of minimal proxies and how to scan the blockchain on your laptop in seconds | September 12, 2023 | Article | banteg                         |
| [remix-Deploy & Run Proxy Contracts](https://remix-ide.readthedocs.io/en/latest/run_proxy_contracts.html) | Remix IDE has the functionality to assist in the handling of proxy contracts that use the UUPS pattern. | -                  | Article | Remix                          |
| [EIP-7504: Dynamic Smart Contracts](https://blog.thirdweb.com/erc-7504-dynamic-smart-contracts/) | A new Ethereum standard for client-friendly one-to-many proxy contracts. | 09/2023            | Article | Krishang Nadgauda / ThirdWeb   |
| [The initializable smart contract design pattern](https://www.rareskills.io/post/initializable-solidity) | How initializers work                                        | 07/08/2023         | Article | RareSkills / Joao Paulo Morais |

## Security

| Title                                                        | Description                | Date     | Support | Author                                                       |
| ------------------------------------------------------------ | -------------------------- | -------- | ------- | ------------------------------------------------------------ |
| [Improve security for Initializer.sol](https://banteg.xyz/posts/minimal-proxies/) |                            | 03/2023  | Article | [0xPhaze](https://github.com/0xPhaze)                        |
| [Auditor’s Notes: Initializing, Proxy, Oracles & Multi-Chain](https://blog.pessimistic.io/auditors-notes-initializing-proxy-oracles-multi-chain-e314ec0694b2) |                            | 08/2023  | Article | [Officer's Notes](https://officercia.medium.com/)            |
| [Upgradeable Proxy Contract Security Best Practices](https://www.certik.com/resources/blog/FnfYrOCsy3MG9s9gixfbJ-upgradeable-proxy-contract-security-best-practices) |                            | 11/2022  | Article | Certik                                                       |
| [blog.openzeppelin.com/proxy-patterns](https://blog.openzeppelin.com/proxy-patterns) | Introducing Proxy Patterns | 04/2018  | Article | OpenZeppelin                                                 |
| [Why you should never approve proxy smart contracts for token spending?](https://medium.com/easyblock-blockchain-technology-blog/why-you-should-never-approve-proxy-smart-contracts-for-token-spending-3797e542113b) |                            | 11/ 2022 | Article | [Doğu Deniz Uğur](https://medium.com/@dogudenizugur)         |
| [forum.openzeppelin.com/Risk on proxy initialize front-running risk](https://forum.openzeppelin.com/t/risk-on-proxy-initialize-front-running-risk/27280/1) |                            | 04/2022  | Article | [rareblocks](https://forum.openzeppelin.com/u/rareblocks)    |
| [twitter.com-Bug Challenge #3](https://twitter.com/bytes032/status/1611346854070861824) |                            | 01/ 2022 | Article | bytes032                                                     |
| [Delegatecall & Contract Upgradability](https://journal0xrusowsky.substack.com/p/delegatecall-and-contract-upgradability) |                            | 08/2022  | Article | [xRusowsky](https://substack.com/profile/46892425-0xrusowsky) |

### Accident

| Title                                                        | Description                                                  | Date    | Support | Author   |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------- | ------- | -------- |
| [SlowMist: Analysis of the Furucombo Hack](https://slowmist.medium.com/slowmist-analysis-of-the-furucombo-hack-28c9ae558db9) | The well-known DeFi project Furucombo was hacked and lost more than 15 million U.S. dollars. | 02/2021 | Article | SlowMist |
| [Replaying Ethereum Hacks - Furucombo](https://cmichel.io/replaying-ethereum-hacks-furucombo/) | Let’s dive into the attack, understand it by reading the code of the relevant contracts, and then replay the hack using a custom contract. | 02/2021 | Article | cmichael |
| [ ZKSYNC1-2021-01 Post Mortem](https://web.archive.org/web/20220929042509/https://docs.zksync.io/dev/security/ZKSYNC1-2021-01/#summary) | If the attacker sets `additionalZkSync` to an address that would execute the `SELFDESTRUCT` opcode on any entry, and then call any function on the zkSync main contract that uses logic from `additionalZkSync` via delegatecall, the main zkSync target contract could have been destroyed and all funds would have been frozen. | 2021    | Article | zkSync   |
| [Wormhole Uninitialized Proxy Bugfix Review](https://medium.com/immunefi/wormhole-uninitialized-proxy-bugfix-review-90250c41a43a) | This bug was an upgradeable proxy implementation self-destruct bug that could have led to a potential lockup of user funds. | 05/2022 | Article | Wormhole |
|                                                              |                                                              |         |         |          |

## UUPS Proxy

| Title                                                        | Description | Date         | Support         | Author                                   |
| ------------------------------------------------------------ | ----------- | ------------ | --------------- | ---------------------------------------- |
| [Report for KyberSwap](https://audits.sherlock.xyz/contests/103/report) |             | <2023 ?      | Sherlock report | MohammedRizwan                           |
| [Wormhole Uninitialized Proxy Bugfix Review](https://medium.com/immunefi/wormhole-uninitialized-proxy-bugfix-review-90250c41a43a) |             | May 20, 2022 | Article         | [Immunefi](https://medium.com/@immunefi) |

## Diamond proxy pattern

| Title                                                        | Description                                                  | Date             | Support        | Author                                                   |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------- | -------------- | -------------------------------------------------------- |
| [The Diamond Proxy Pattern Explained:  What You Need To Know (Advanced Proxy Pattern](https://www.youtube.com/watch?v=IoWe6VIctJQ) | -                                                            | January 19, 2023 | Video          | Jesper Kristensen                                        |
| [How To Implement The Diamond Standard](https://medium.com/@MarqyMarq/how-to-implement-the-diamond-standard-69e87dae44e6) | -                                                            | 02/2023          | Article        | Marq                                                     |
| [ERC20-Diamond-Proxy](https://github.com/KevinH2810/ERC20-Diamond-Proxy) | -                                                            | 2023             | GitHub project | KevinH2810                                               |
| [Understanding delegatecall And How to Use It Safely](https://eip2535diamonds.substack.com/p/understanding-delegatecall-and-how) | -                                                            | 07/2021          | Article        | Nick Mudge                                               |
| [The Diamond Proxy simply explained](https://twitter.com/CharlesWangP/status/1762915168558690549?t=_Y4rPZO0ewl-bxcEEUzt8w&s=35) | -                                                            | 02/2024          | Tweet          | Charles Wang                                             |
| [A Comparative Gas Cost Analysis of Proxy and Diamond Patterns in EVM Blockchains for Trusted Smart Contract Engineering](https://arxiv.org/pdf/2312.08945v2) | comparative analysis of gas costs for both patterns in contrast to a traditional non-upgradeable smart contract | 05/2024          | arxiv          | Anto Benedetti, Tiphaine Henry1, Sara Tucci-Piergiovanni |

## Beacon Proxy

| Title                                                        | Description | Date    | Support                                                      | Author                                       |
| ------------------------------------------------------------ | ----------- | ------- | ------------------------------------------------------------ | -------------------------------------------- |
| [Beacon-Proxy-Implementation-Hardhat-](https://github.com/ishinu/Beacon-Proxy-Implementation-Hardhat-) | -           | 2022    | GitHub project<br />[Gist](https://gist.github.com/yurenju/ef4c901a48c523ac74bf942b50ab5108) | ishinu                                       |
| [Astaria Beacon Proxy issue](https://twitter.com/apoorvlathey/status/1671308180545241088) | -           | 06/2023 | Twitter thread                                               | Apoorv Lathey                                |
| [Secure Proxy Models: Understanding Beacon Proxies](https://blog.rivanorth.com/secure-proxy-models-beacon-proxies) | -           | 10/2023 | Article                                                      | [Rivanorth](https://hashnode.com/@Rivanorth) |



## Lesson

| Title                                                        | Description | Date    | Support | Author     |
| ------------------------------------------------------------ | ----------- | ------- | ------- | ---------- |
| [Do Not Miss These 5 Upgradeability Vulnerabilities](https://www.youtube.com/watch?v=6aPyykZhglM) | -           | 01/2024 | Video   | Owen Thurm |
| [Smart Contract Upgradeability 101 \| 5 Upgradeability Methods](https://www.youtube.com/watch?v=e5lWvt1rIm0) | -           | 08/2023 | Video   | Owen Thurm |



## Interview question

- What are Uninitialized storage pointers?

- Explain the Diamond proxy pattern.

- Why shouldn’t upgradeable contracts use the constructor?

- What is the difference between UUPS and the Transparent Upgradeable Proxy pattern?

- What is a function selector clash in a proxy and how does it happen?

- What is a storage collision in a proxy contract?

- If a proxy makes a delegatecall to A, and A does address(this).balance, whose balance is returned, the proxy's or A?

  

Reference: [rareskills.io/post/solidity-interview-questions](https://www.rareskills.io/post/solidity-interview-questions)

