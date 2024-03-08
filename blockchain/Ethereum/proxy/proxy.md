# Proxy

Resources related to proxy

## General

| Title                                                        | Date               | Support                 | Author                                   |
| ------------------------------------------------------------ | ------------------ | ----------------------- | ---------------------------------------- |
| [Minimal Proxy Compendium](https://banteg.xyz/posts/minimal-proxies/) | September 12, 2023 | Article                 | banteg                                   |
| [Proxies in smart contracts thread](https://twitter.com/dimo_audit/status/1698324235595260398) | September 3, 2023  | Article                 | dimo_audit                               |
| [remix-Deploy & Run Proxy Contracts](https://remix-ide.readthedocs.io/en/latest/run_proxy_contracts.html) | -                  | Article                 | Remix                                    |
| [Proxy Patterns For Upgradeability Of Solidity Contracts: Transparent vs UUPS Proxies](https://mirror.xyz/0xB38709B8198d147cc9Ff9C133838a044d78B064B/M7oTptQkBGXxox-tk9VJjL66E1V8BUF0GF79MMK4YG0) | March 22, 2022     | Article                 | Naveen                                   |
| [A Comprehensive Survey of Upgradeable Smart Contract Patterns](https://arxiv.org/pdf/2304.03405.pdf) | ~2020              | Research  paper (arxiv) | Sajad Meisami, William Edward Bodell III |
| [yAcademy Proxies Research](https://proxies.yacademy.dev)    | ?                  | Several articles        | yAcademy                                 |
|                                                              |                    |                         |                                          |
|                                                              |                    |                         |                                          |



## Security

| Title                                                        | Date     | Description        | Support | Author                                                       |
| ------------------------------------------------------------ | -------- | ------------------ | ------- | ------------------------------------------------------------ |
| [Improve security for Initializer.sol](https://banteg.xyz/posts/minimal-proxies/) | 03/2023  |                    | Article | [0xPhaze](https://github.com/0xPhaze)                        |
| [Auditor’s Notes: Initializing, Proxy, Oracles & Multi-Chain](https://blog.pessimistic.io/auditors-notes-initializing-proxy-oracles-multi-chain-e314ec0694b2) | 08/2023  |                    | Article | [Officer's Notes](https://officercia.medium.com/)            |
| [Upgradeable Proxy Contract Security Best Practices](https://www.certik.com/resources/blog/FnfYrOCsy3MG9s9gixfbJ-upgradeable-proxy-contract-security-best-practices) | 11/2022  |                    | Article | Certik                                                       |
| [blog.openzeppelin.com/proxy-patterns](https://blog.openzeppelin.com/proxy-patterns) | 04/2018  |                    | Article | OpenZeppelin                                                 |
| [Why you should never approve proxy smart contracts for token spending?](https://medium.com/easyblock-blockchain-technology-blog/why-you-should-never-approve-proxy-smart-contracts-for-token-spending-3797e542113b) | 11/ 2022 |                    | Article | [Doğu Deniz Uğur](https://medium.com/@dogudenizugur)         |
| [forum.openzeppelin.com/Risk on proxy initialize front-running risk](https://forum.openzeppelin.com/t/risk-on-proxy-initialize-front-running-risk/27280/1) | 04/2022  |                    | Article | [rareblocks](https://forum.openzeppelin.com/u/rareblocks)    |
| [twitter.com-Bug Challenge #3](https://twitter.com/bytes032/status/1611346854070861824) | 01/ 2022 |                    | Article | bytes032                                                     |
| [ ZKSYNC1-2021-01 Post Mortem](https://web.archive.org/web/20220929042509/https://docs.zksync.io/dev/security/ZKSYNC1-2021-01/#summary) | 2021     |                    | Article | zkSync                                                       |
| [Delegatecall & Contract Upgradability](https://journal0xrusowsky.substack.com/p/delegatecall-and-contract-upgradability) | 08/2022  | Ethernaut Level 16 | Article | [xRusowsky](https://substack.com/profile/46892425-0xrusowsky) |



## UUPS

| Title                                                        | Date         | Support         | Author                                   |
| ------------------------------------------------------------ | ------------ | --------------- | ---------------------------------------- |
| [Report for KyberSwap](https://audits.sherlock.xyz/contests/103/report) | <2023 ?      | Sherlock report | MohammedRizwan                           |
| [Wormhole Uninitialized Proxy Bugfix Review](https://medium.com/immunefi/wormhole-uninitialized-proxy-bugfix-review-90250c41a43a) | May 20, 2022 | Article         | [Immunefi](https://medium.com/@immunefi) |

## Diamond proxy pattern

| Title                                                        | Date             | Support        | Author            |
| ------------------------------------------------------------ | ---------------- | -------------- | ----------------- |
| [The Diamond Proxy Pattern Explained:  What You Need To Know (Advanced Proxy Pattern](https://www.youtube.com/watch?v=IoWe6VIctJQ) | January 19, 2023 | Video          | Jesper Kristensen |
| [How To Implement The Diamond Standard](https://medium.com/@MarqyMarq/how-to-implement-the-diamond-standard-69e87dae44e6) | 02/2023          | Article        | Marq              |
| [ERC20-Diamond-Proxy](https://github.com/KevinH2810/ERC20-Diamond-Proxy) | 2023             | GitHub project | KevinH2810        |
| [Understanding delegatecall And How to Use It Safely](https://eip2535diamonds.substack.com/p/understanding-delegatecall-and-how) | 07/2021          | Article        | Nick Mudge        |
|                                                              |                  |                |                   |

## Beacon

| Title                                                        | Date    | Support                                                      | Author        |
| ------------------------------------------------------------ | ------- | ------------------------------------------------------------ | ------------- |
| [Beacon-Proxy-Implementation-Hardhat-](https://github.com/ishinu/Beacon-Proxy-Implementation-Hardhat-) | 2022    | GitHub project<br />[Gist](https://gist.github.com/yurenju/ef4c901a48c523ac74bf942b50ab5108) | ishinu        |
| [Astaria Beacon Proxy issue](https://twitter.com/apoorvlathey/status/1671308180545241088) | 06/2023 | Twitter thread                                               | Apoorv Lathey |
|                                                              |         |                                                              |               |

## Interview question

- What are Uninitialized storage pointers?

- Explain the Diamond proxy pattern.

- Why shouldn’t upgradeable contracts use the constructor?

- What is the difference between UUPS and the Transparent Upgradeable Proxy pattern?

- What is a function selector clash in a proxy and how does it happen?

- What is a storage collision in a proxy contract?

- If a proxy makes a delegatecall to A, and A does address(this).balance, whose balance is returned, the proxy's or A?

  

Reference: [https://www.rareskills.io/post/solidity-interview-questions](https://www.rareskills.io/post/solidity-interview-questions)

