# Uniswap

[https://uniswap.org/](https://uniswap.org/)

## Official documentation

| Title                                                        | Description | Date    | Support | Author       |
| ------------------------------------------------------------ | ----------- | ------- | ------- | ------------ |
| [Introducing UNI](https://blog.uniswap.org/uni)              | -           | 08/2020 | Article | Uniswap Labs |
| [What is Uniswap? A Complete Guide](https://blog.uniswap.org/what-is-uniswaphttps://blog.uniswap.org/what-is-uniswap) | -           | 06/2023 | Article | Uniswap Labs |
| [UniSwap v2 Overview](https://blog.uniswap.org/uniswap-v2)   | -           | 03/2023 | Article | Uniswap Labs |
| [Introducing Uniwsap v3](https://blog.uniswap.org/uniswap-v3) | -           | 03/2023 | Article | Uniswap Labs |



## General

| Title                                                        | Description                                                  | Date    | Support              | Author                                       |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------- | -------------------- | -------------------------------------------- |
| [Deep Dive into defi - Day68](https://github.com/spo0ds/Deep-Dive-into-DEFI/blob/main/Day68/Day68.md) | High Level Working of Uniswap / Comparison of Unswap v1 vs v2 vs v3 | 12/2022 | Markdown file GitHub | [spo0ds         ](https://github.com/spo0ds) |

### Uniswap v4

Documentation: [https://docs.uniswapfoundation.org/](https://docs.uniswapfoundation.org/)

| Title                                                        | Description   | Date    | Support | Author                                        |
| ------------------------------------------------------------ | ------------- | ------- | ------- | --------------------------------------------- |
| [What is the TWAMM hook?](https://blog.uniswap.org/v4-twamm-hook) | -             | 08/2023 | Article | Uniswap Labs                                  |
| [Uniswap v4 oracle truncated hook](https://blog.uniswap.org/uniswap-v4-truncated-oracle-hook) | -             | 09/2023 | Article | Uniswap Labs                                  |
| [Community Contributions to Uniswapv4](https://blog.uniswap.org/uniswap-v4-community-contributions) | -             | 10/2023 | Article | Uniswap Labs                                  |
| [Hook KYC](https://twitter.com/wh01s7/status/1730609242124464164) | Pool with kYC | 12/2023 | Tweet   | [Paul Kuryłowicz](https://twitter.com/wh01s7) |



### Uniswap v3

| Title                                                        | Description | Date    | Support | Author            |
| ------------------------------------------------------------ | ----------- | ------- | ------- | ----------------- |
| [New Era Of AMMs? Architecture Explained](https://www.youtube.com/watch?v=Ehm-OYBmlPM) | -           | 03/2021 | Video   | Finematics        |
| [PERPETUAL PROTOCOL - Next Level In Decentralized Trading? (Layer 2, Uniswap V3)](https://www.youtube.com/watch?v=pBoKtkoNZEY) | -           | 12/2021 |         | Finematics        |
| [Concentrated Liquidity, NFT LP Tokens, Licensing](https://www.youtube.com/watch?v=ClWR1570UQw) | -           | 09/2021 | Video   | Whiteboard Crypto |
|                                                              |             |         |         |                   |

#### Oracle integration

| Title                                                        | Description                                                  | Date    | Support           | Author                                                       |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------- | ----------------- | ------------------------------------------------------------ |
| [Uniswap - Price Oracle](https://uniswapv3book.com/milestone_5/price-oracle.html#price-oracle) | Official doc                                                 | <2024   | Online book       | Uniswap Labs                                                 |
| [uniswap oracle](https://docs.uniswap.org/concepts/protocol/oracle) | Official doc                                                 | -       | Article           | Uniswap Labs                                                 |
| [Uniswap V3 oracles do not work properly on Optimism/Base](https://github.com/code-423n4/2023-07-tapioca-findings/issues/112) | The Uniswap V3 documentation states that its oracles are not suitable  for Optimism because on that chain block.timestamp refers to the L1's  timestamp, and thus the oracle is much less costly to manipulate. | 07/2023 | Issue GitHub      | Code4Arena  warden                                           |
| [scsfg - Oracle manipulation attacks](https://scsfg.io/hackers/oracle-manipulation/) | The following sections provide examples illustrating common vulnerabilities and malfunctions involving oracles. | <2024   | Article           | scsfg.io                                                     |
| [uniswap-v3-oracle-hardhat-plugin](https://github.com/ChaosLabsInc/uniswap-v3-oracle-hardhat-plugin) | This repository hosts a hardhat plugin for configuring Uniswap V3 Oracle prices in a local hardhat mainnet fork testing environment. | 2022    | Github project    | [            ChaosLabsInc ](https://github.com/ChaosLabsInc) |
| [[M-10] `TapOracle` TWAP duration for Uniswap Oracle should be at least 30 mins](https://solodit.xyz/issues/m-10-taporacle-twap-duration-for-uniswap-oracle-should-be-at-least-30-mins-pashov-none-tapiocadao-markdown) | `TapOracle` uses a single price feed based on Uniswap V3 TWAP oracle for TAP/USDC pool. | 01/2024 | Solidit database  | Pashov Audit Group                                           |
| [Issue M-2: Oracle tick rounding the wrong direction can lead to Swapper overpaying for swap](https://github.com/sherlock-audit/2023-04-splits-judging?tab=readme-ov-file#issue-m-2-oracle-tick-rounding-the-wrong-direction-can-lead-to-swapper-overpaying-for-swap) | The UniV3Oracle is intended to be used in situations where asset values can be understated, but must not be overstated. As a result, all results are rounded down to the nearest tick. | 04/2023 | Github / Sherlock | Sherlock                                                     |
| [ast3ros - UniswapPriceAdaptor fails after updating impact](https://github.com/sherlock-audit/2023-04-jojo-judging/issues/364) | UniswapPriceAdaptor fails after updating impact              | 05/2023 | Github Issue      | Sherlock                                                     |



#### Concept

| Title                                                        | Description                          | Date    | Support | Author                    |
| ------------------------------------------------------------ | ------------------------------------ | ------- | ------- | ------------------------- |
| [Concentrated Liquidity](https://docs.uniswap.org/concepts/protocol/concentrated-liquidity#ticks) | -                                    |         | Article | Uniswap Labs              |
| [A primer on Uniswap v3 Math](https://blog.uniswap.org/uniswap-v3-math-primer) | Q Notation, current exchange rate?.. | 01/2023 | Article | Uniswap Labs              |
| [What are TWAP Oracles, and How are they different from Uniswap?](https://www.immunebytes.com/blog/what-are-twap-oracles-and-how-are-they-different-from-uniswap/) | TWAP on Uniswap v3                   | 07/2023 | Article | Immunebytes               |
| [Uniswap v3 TWAP Oracles in Proof of Stake](https://blog.uniswap.org/uniswap-v3-oracles) | -                                    | 10/2022 | Article | Uniswap Labs              |
| [UniswapV3:  The Math Of Providing Liquidity.](https://twitter.com/Bount3yHunt3r/status/1736909028788203627) | -                                    | 12/2023 | Tweet   | Bount3yHunt3r             |
| [UniswapV3:  Relationship between Tick and Price.](https://twitter.com/Bount3yHunt3r/status/1734013066453336324) | -                                    | 12/2023 | Tweet   | Bount3yHunt3r             |
| [Concentrated Liquidity Deep Dive!](https://twitter.com/Bount3yHunt3r/status/1730941847952859285) | -                                    | 12/2023 | Tweet   | Bount3yHunt3r             |
| [Uniswap V3 fee algorithm](https://x.com/ProgrammerSmart/status/1718504599408304427?t=KsLMLh1lT_qPs8FtLu0c3Q&s=19) | -                                    | 10/2023 | Tweet   | Smart Contract Programmer |



### Uniswap v2

| Title                                                        | Description                                                  | Date    | Support        | Author             |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------- | -------------- | ------------------ |
| [How the TWAP Oracle in Uniswap v2 Works](https://www.rareskills.io/post/twap-uniswap-v2) | -                                                            | 11/2023 | Article        | RareSkills         |
| [[C-01] Uniswap oracle manipulation to buy for a lower price](https://solodit.xyz/issues/c-01-uniswap-oracle-manipulation-to-buy-for-a-lower-price-pashov-none-forgottenplayland-markdown) | `uniswapV2Router.getAmountsIn()` is used to calculate the amount of `paymentToken` required for the amount in `referenceToken`. This feed is easily manipulated by a large swap in Uniswap pairs. | 03/2023 | Solodit report | Pashov Audit Group |
|                                                              |                                                              |         |                |                    |
|                                                              |                                                              |         |                |                    |

### Uniswap v1

[https://github.com/Uniswap/v1-contracts](https://github.com/Uniswap/v1-contracts)

[https://docs.uniswap.org/contracts/v1/overview](https://docs.uniswap.org/contracts/v1/overview)

| Title                                                        | Description | Date    | Support | Author      |
| ------------------------------------------------------------ | ----------- | ------- | ------- | ----------- |
| [Understanding Uniswap Theory & Code - Introduction to Decentralised Exchanges (DEX)  Uniswap v1](https://youtu.be/_15UAhVaARw) |             | 11/2021 | Article | Tchsurvives |



## Specific topic

### Governance

| Title                                                        | Description                                                  | Date    | Support | Author                                                       |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------- | ------- | ------------------------------------------------------------ |
| [[A Deep Dive of Uniswap’s Governance](https://gov.uniswap.org/t/a-deep-dive-of-uniswaps-governance/19792)](https://gov.uniswap.org/t/a-deep-dive-of-uniswaps-governance/19792) | [A Deep Dive of Uniswap’s Governance](https://gov.uniswap.org/t/a-deep-dive-of-uniswaps-governance/19792) | 2022    | Article | Penn Blockchain / FranklinDAO                                |
| [contentious-uniswap-vote](https://www.coindesk.com/tech/2023/02/08/contentious-uniswap-vote-highlights-the-opaqueness-of-decentralized-governance/) | Contentious Uniswap Vote Highlights the Opaqueness of Decentralized Governance | 02/2023 | Article | [Sam Kessler](https://www.coindesk.com/author/sam-kessler/) / coindesk |
| [uniswapfoundation.mirror.xyz/](https://uniswapfoundation.mirror.xyz/2P07K6h6kEIie2BIpvxGy3usVSHGAQ51lDhOxLmmtMA) | Strengthening Uniswap Governance                             | 06/2023 | Article | Devin / Uniswap Foundation                                   |

### Others

| Title                                                        | Description                                       | Date    | Support            | Author                                                       |
| ------------------------------------------------------------ | ------------------------------------------------- | ------- | ------------------ | ------------------------------------------------------------ |
| [Cross-Chain Bridge Assessment Process](https://gov.uniswap.org/t/cross-chain-bridge-assessment-process/20148) | Assessment process to choose a cross chain bridge | 01/2023 | Article            | [devinwalsh](https://gov.uniswap.org/u/devinwalsh) / gov.uniswap |
| [Bridge Assessment Report](https://uniswap.notion.site/Bridge-Assessment-Report-0c8477afadce425abac9c0bd175ca382) | 2023                                              | Report  | Uniswap Foundation |                                                              |



## Security

| Title                                                        | Description | Date    | Support | Author                               |
| ------------------------------------------------------------ | ----------- | ------- | ------- | ------------------------------------ |
| [Threats for UniswapV4 hooks](https://medium.com/vesperfinance/on-the-vesper-lend-beta-rari-fuse-pool-23-exploit-9043ccd40ac9) |             | 11/2021 | 11/2023 | Damian Rusinek / Composable Security |

### Past accident

| Title                                                        | Description                                                  | Date    | Support | Author         |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------- | ------- | -------------- |
| [Rari Fuse Pool exploit](https://medium.com/vesperfinance/on-the-vesper-lend-beta-rari-fuse-pool-23-exploit-9043ccd40ac9) | On the Vesper Lend Beta / Rari Fuse Pool #23 Exploit -  Uniswap v3 oracle | 11/2021 | Article | Vesper Finance |

# Lesson

| Title                                                        | Description | Date | Support          | Author      |
| ------------------------------------------------------------ | ----------- | ---- | ---------------- | ----------- |
| [A deep dive into Automated Market Maker Decentralized Exchanges (Uniswap v1)](https://learnweb3.io/lessons/a-deep-dive-into-automated-market-maker-decentralized-exchanges-uniswap-v1) | -           | 2022 | Article - Lesson | LearnWeb3   |
| [Uniswap v4 Hooks: Create a fully on-chain "take-profit" orders hook on Uniswap v4](https://learnweb3.io/lessons/uniswap-v4-hooks-create-a-fully-on-chain-take-profit-orders-hook-on-uniswap-v4) | -           | 2023 | Article - Lesson | LearnWeb387 |
