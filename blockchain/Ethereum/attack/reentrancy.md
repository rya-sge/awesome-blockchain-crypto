# Reentrancy Attack

- Single-Function Reentrancy
- Cross-Function Reentrancy
- Cross-Contract Reentrancy
- Cross-Chain Reentrancy
- Read-Only Reentrancy
- Tokens:
  - ERC-721
  - ERC-777/677
  - ERC-1155

### General

| Title                                                        | Description                                                  | Date    | Support        | Author                                                       |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------- | -------------- | ------------------------------------------------------------ |
| [Reentrancy Attack: The Ultimate Guide](https://www.immunebytes.com/blog/reentrancy-attack/) | working, type, and ways of saving your smart contract from them. | 07/2022 | Article        | IMMUNEBYTES                                                  |
| [Secure Smart Contract Development — Code Reentrancy in NFT](https://blocksecteam.medium.com/secure-smart-contract-development-code-reentrancy-in-nft-contracts-fa6799a3966c) | reentrancy issue in **NFT contracts** and how to mitigate the related vulnerability. | 08/2022 | Article        | Blocksec                                                     |
| [Reentrancy Vulnerability Identification in Ethereum<br/>Smart Contracts](https://arxiv.org/pdf/2105.02881) |                                                              | 05/2021 | Research paper | Noama Fatima Samreen, Manar H. Alalfi<br/>Department of Computer Science<br/>Ryerson University, Toronto |
| [Tutorial 9: Read-Only Reentrancy](https://zokyo-auditing-tutorials.gitbook.io/zokyo-tutorials/tutorial-9-read-only-reentrancy) |                                                              |         |                |                                                              |

### Twitter thread

| Title                                                        | Description                                                  | Date    | Support | Author                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------- | ------- | ------------------------------------------------------- |
| [Reentrancy Attack](https://twitter.com/0xNickLFranklin/status/1755148734076420248) | Single-function Reentrancy<br /> Cross-Function Attacks<br />Cross-Contract Reentrancy<br />Read-Only Reentrancy | 02/2024 | Twitter | [Nick L. Franklin](https://twitter.com/0xNickLFranklin) |
| [Reentrancy Attack](https://twitter.com/0xAdra/status/1762410955500134776) | Short explanation with schema                                | 02/2024 | Twitter | 0xAdra                                                  |
| [solidity reentrancy 101](https://twitter.com/blainemalone/status/1748409660472717401?s=20) | Short explanation with schema                                | 01/2024 | Twitter | blaine                                                  |
|                                                              |                                                              |         |         |                                                         |

## Specific

| Title                                                        | Description                                                  | Date    | Support | Author                                                       |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------- | ------- | ------------------------------------------------------------ |
| [Cross-Contract reentrancy](https://twitter.com/Smacaud1/status/1734897079007268937?t=K7Ik00fVQJFcCNjqbMn5Sg&s=35) |                                                              | 12/2023 | Twitter | Smacaud                                                      |
| [eth-reentrancy-attack-patterns](https://github.com/uni-due-syssec/eth-reentrancy-attack-patterns)(  https://github.com/uni-due-syssec/eth-reentrancy-attack-patterns) | Re-entrancy attack patterns from our paper "Sereum: Protecting Existing Smart Contracts Against Re-Entrancy Attacks" | 2019    | Github  | Rodler, Michael and Li, Wenting and Karame, Ghassan and Davi, Lucas |
| [How to Detect Reentrancy Attacks Using ZIION Tools](https://www.ziion.org/blog/post/How-to-Detect-Reentrancy-Attacks-Using-ZIION-Tools) | In this blog, we will take a closer look at [reentrancy attacks](https://www.halborn.com/blog/post/what-is-a-re-entrancy-attack), their impact on some well-known blockchain protocols, and the tools and    techniques to discover and mitigate them. | 05/2023 | Article | Zion / Halborn                                               |
| [TSTORE Low Gas Reentrancy](https://chainsecurity.com/tstore-low-gas-reentrancy/) | -                                                            | 2023    | Article | ChainSecurity                                                |

### Read-only

| Title                                                        | Description                                                  | Date    | Support | Author                                                       |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------- | ------- | ------------------------------------------------------------ |
| [Understanding the Threat of Read- Only Reentrancy Attacks on YourSmart Contracts](https://smartcontract.tips/articoli/understanding-the-threat-of-read-only-reentrancy-attacks-on-yoursmart-contracts/) | Explains the Sentiment Platform attack                       | 08/2023 | Article | SCT Italia                                                   |
| [Read-only reentrancy attacks: understanding the threat to your smart contracts](https://medium.com/zokyo-io/read-only-reentrancy-attacks-understanding-the-threat-to-your-smart-contracts-99444c0a7334) | Explains the Sentiment Platform attack                       | 04/2023 | Article | [Zokyo](https://medium.com/@zokyo.io?source=post_page-----99444c0a7334--------------------------------) |
| [Curve LP Oracle Manipulation: Post Mortem](https://chainsecurity.com/curve-lp-oracle-manipulation-post-mortem/) | On April 14, we informed Curve and affected projects about a read-only  reentrancy vulnerability in some Curve pools. More specifically, the  value of function `get_virtual_price` can be manipulated by  reentering it during the removal of liquidity. Now, since all teams  secured their projects, we are happy to share the technical details. | 04/2023 | Article | ChainSecurity                                                |
| [Vyper, Reentrancy, Curve Finance and the Danger to DeFi](https://blog.dragonscale.ai/vyper-reentrancy-curve-finance-and-the-danger-to-defi/) | A reentrancy attack enabled by a flaw in older versions of Vyper allowed attackers to steal [$110 million](https://decrypt.co/151336/curve-finance-chaos-is-110-million-gut-check-defi?ref=blog.dragonscale.ai) in late July ‘23. | 09/2023 | Article | [Dragonscale Industries](https://blog.dragonscale.ai/author/dragonscale/) |



## Lesson

| Title                                                        | Description                                                  | Date | Support | Author |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ---- | ------- | ------ |
| [The Ultimate Guide To Reentrancy](https://www.youtube.com/watch?v=3T1t2ginfTg) | [00:00](https://www.youtube.com/watch?v=3T1t2ginfTg&t=0s) - Intro [03:10](https://www.youtube.com/watch?v=3T1t2ginfTg&t=190s) - #1 Classic reentrancy [07:30](https://www.youtube.com/watch?v=3T1t2ginfTg&t=450s) - #2 Cross-function reentrancy [11:49](https://www.youtube.com/watch?v=3T1t2ginfTg&t=709s) - #3 Cross-contract reentrancy [17:36](https://www.youtube.com/watch?v=3T1t2ginfTg&t=1056s) - #4 Read-only reentrancy [23:53](https://www.youtube.com/watch?v=3T1t2ginfTg&t=1433s) - ERC777 & ERC721 reentrancies [25:13](https://www.youtube.com/watch?v=3T1t2ginfTg&t=1513s) - The system I use [29:21](https://www.youtube.com/watch?v=3T1t2ginfTg&t=1761s) - Join the Solidity lab [30:57](https://www.youtube.com/watch?v=3T1t2ginfTg&t=1857s) - Take $50 off! |      |         |        |
|                                                              |                                                              |      |         |        |
|                                                              |                                                              |      |         |        |

## Example

| Title                                                        | Description                                                  | Date    | Support | Author   |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------- | ------- | -------- |
| [jaypeggerz](https://twitter.com/BlockSecTeam/status/1608372475225866240?t=406f6CJOQNR98iN4QdBW7A&s=19) | Thisproject was attacked and the loss is around 15.32 Ether. It is a contract-level reentrancy attack that successfully manipulates the price of the JAY token. | 12/2022 | Tweet   | BlockSec |
