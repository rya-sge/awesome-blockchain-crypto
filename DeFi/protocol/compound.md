# Compound

Codee: [github.com/compound-finance/compound-protocol](https://github.com/compound-finance/compound-protocol)

Website: [compound.finance](https://compound.finance)

Doc: [docs.compound.finance](https://docs.compound.finance)

Academy: [compound.education](https://compound.education)

[TOC]

## Official documentation

| Title                                                        | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [Interest Rates](https://docs.compound.finance/interest-rates/) | Users with a positive balance of the base asset earn interest, denominated in the base asset, based on a supply rate model; users with a negative balance pay interest based on a borrow rate model. |
| [Collateral & Borrowing](https://docs.compound.finance/collateral-and-borrowing/) | Users can add collateral assets to their account using the *[supply](https://docs.compound.finance/collateral-and-borrowing/#supply)* function. Collateral can only be added if the market is below its *[supplyCap](https://docs.compound.finance/helper-functions/#get-asset-info-by-address)*, which limits the protocol’s risk exposure to collateral assets. |
| [Liquidation](https://docs.compound.finance/liquidation/)    | Liquidation is determined by *[liquidation collateral factors](https://docs.compound.finance/helper-functions/#get-asset-info-by-address)*, which are separate and higher than borrow collateral factors (used to determine initial borrowing capacity), which protects borrowers & the protocol by ensuring a price buffer for all new positions. |
| [Account Management](https://docs.compound.finance/account-management/) | In addition to self-management, Compound III accounts can enable other addresses to have write permissions for their account. Account managers can withdraw or transfer collateral within the protocol on behalf of another account. |
| [Protocol Rewards](https://docs.compound.finance/protocol-rewards/) | Compound III has a built-in system for tracking rewards for accounts that use the protocol. The full history of accrual of rewards are tracked for suppliers and borrowers of the base asset. |
| [Governance](https://docs.compound.finance/governance/)      | Compound III is a decentralized protocol that is governed by holders and delegates of COMP. |
| [Helper Functions](https://docs.compound.finance/helper-functions/) | List of useful functions                                     |

## General

| Title                                                        | Description                                                  | Date    | Support | Author             |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------- | ------- | ------------------ |
| [Lending And Borrowing In DEFI Explained - Aave, Compound](https://www.youtube.com/watch?v=aTp9er6S73M) | How lending and borrowing works in DeFi? How are the supply and borrow rates determined? And what is the main difference between the most popular lending protocols such as Compound and Aave | 11/2020 | Video   | Finematics         |
| [Tokenization 101: Yield-bearing tokens, what are they and how do they work?](https://academy.synfutures.com/tokenization-101-yield-bearing-tokens-what-are-they-and-how-do-they-work/) | cToken is the proof of ownership of the loan and can be used to claim your deposit. | 03/2022 | Article | SynFutures Academy |
|                                                              |                                                              |         |         |                    |



## Specific topic

| Title                                                        | Description                                                  | Date | Support        | Author   |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ---- | -------------- | -------- |
| [Dai liquidation event](https://www.comp.xyz/t/dai-liquidation-event/642) | From approximately 12:00am to 1:00am PT on Thanksgiving morning, the  price of DAI on Coinbase Pro began trading at increasing prices and  volume across the DAI/USDC, DAI/USD, and ETH/DAI pairs, reaching as high as $1.30. | 2020 | Compound forum | rleshner |
|                                                              |                                                              |      |                |          |



## Learning

- [Compound V3 Book by RareSkills](https://www.rareskills.io/compound-v3-book)
-  [Compound Academy](https://compound.education)
