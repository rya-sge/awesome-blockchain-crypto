# Solidity

official doc: [v0.8.23/](https://docs.soliditylang.org/en/v0.8.23/)

## General

| Title                                                        | Date    | Support | Author                                                       |
| ------------------------------------------------------------ | ------- | ------- | ------------------------------------------------------------ |
| [Storage Pointers in Solidity](https://blog.b9lab.com/storage-pointers-in-solidity-7dcfaa536089) | 11/2018 | Article | Rob Hitchens / b9lab                                         |
| [When to use Storage vs. Memory vs. Calldata in Solidity](https://docs.alchemy.com/docs/when-to-use-storage-vs-memory-vs-calldata-in-solidity) | 2023    | Article | alchemy                                                      |
| [Mastering Libraries In Solidity](https://medium.com/@ajaotosinserah/mastering-libraries-in-solidity-36d783409dfc) | 05/2023 | Article | [Oluwatosin Serah](https://medium.com/@ajaotosinserah?source=post_page-----36d783409dfc--------------------------------) |
| [soliditylang.org - Custom Errors in Solidity](https://soliditylang.org/blog/2021/04/21/custom-errors/) | 04/2021 | Article | Solidity Team                                                |
|                                                              |         |         |                                                              |





## Delegatecall

| Title                                                        | Date    | Description                                                  | Support | Author                                                       |
| ------------------------------------------------------------ | ------- | ------------------------------------------------------------ | ------- | ------------------------------------------------------------ |
| [delegateCall](https://github.com/LearnWeb3DAO/Delegate-Call) | 08/2022 |                                                              | Github  | LearnWeb3Dao                                                 |
| [Mastering Delegatecall in Solidity: A Comprehensive Guide with EVM Walkthrough](https://medium.com/@ajaotosinserah/mastering-delegatecall-in-solidity-a-comprehensive-guide-with-evm-walkthrough-6ddf027175c7) | 04/2023 |                                                              | Article | Serah                                                        |
| [Understanding delegatecall And How to Use It Safely](https://eip2535diamonds.substack.com/p/understanding-delegatecall-and-how) | 07/2021 |                                                              | Article | Nick Mudge                                                   |
| [Delegatecall & Contract Upgradability](https://journal0xrusowsky.substack.com/p/delegatecall-and-contract-upgradability) | 08/2022 | Ethernaut Level 16                                           | Article | [xRusowsky](https://substack.com/profile/46892425-0xrusowsky) |
| [Delegatecall Vulnerabilities In Solidity](https://www.halborn.com/blog/post/delegatecall-vulnerabilities-in-solidity) | 03/2023 | discuss how the `delegatecall` in Solidity can introduce vulnerabilities in smart contracts. | Article | Hallborn / [Rob Behnke](https://www.halborn.com/blog/author/rob-behnke) |
| [Intro to Smart Contract Security Audits- Delegatecall (1) ](https://slowmist.medium.com/c-delegatecall-i-c55c911ec2d0) | ****    |                                                              |         |                                                              |



## Create2

| Title                                                        | Description                                                  | Date    | Support | Author                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------- | ------- | ------------------------------------------------------- |
| [Pitfalls of Using CREATE, CREATE2 and EXTCODESIZE Opcodes](https://mixbytes.io/blog/pitfalls-of-using-cteate-cteate2-and-extcodesize-opcodes) |                                                              | <2024   | Article | MixBytes                                                |
| [Explained: Create2 Opcode in Solidity](https://www.immunebytes.com/blog/explained-create2-opcode-in-solidity/) | This article aims to deliver a thorough guide on the CREATE2 opcode,  exploring its rationale, appropriate use cases, its implementation, and  providing a practical example. | 01/2024 | Article | ImmuneBytes                                             |
| [The Ultimate Guide to **create**, create2 and create3](https://blog.solichain.com/the-ultimate-guide-to-create-create2-and-create3-cc6fe71c6d40) | This guide will give you a quick overview of what each one does and why they matter. | 11/2023 | Article | Adam Boudjemaa                                          |
| [Dark Side of CREATE2 opcode](https://medium.com/coinmonks/dark-side-of-create2-opcode-6b6838a42d71) | The combo of create2 and self-destruct are deadly and we are gonna explore about this in this article | 01/2022 | Article | Jayakumar/Coinmonks                                     |
| https://x.com/realScamSniffer/status/1723627800828195030     | Wallet Drainers are misusing Create2 to bypass security alerts in some wallets by generating new addresses for each malicious signature. | 11/2023 | Article | Scam Sniffer - Web3 Anti-scam                           |
| [Precompute Contract Address with Create2](https://solidity-by-example.org/app/create2/) | Example of use with CREATE2                                  | -       | Code    | [Solidity by Example](https://solidity-by-example.org/) |
| [Metamorphosis Smart Contracts using CREATE2](https://ethereum-blockchain-developer.com/110-upgrade-smart-contracts/12-metamorphosis-create2/) |                                                              |         |         |                                                         |



## Pattern

| Title                                                        | Description                                                  | Date    | Support        | Author                                                       |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------- | -------------- | ------------------------------------------------------------ |
| [Common Patterns](https://docs.soliditylang.org/en/latest/common-patterns.html) |                                                              | 2023    | Article        | soliditylang                                                 |
| [Smart Contract Design Patterns Explained](https://hedera.com/learning/smart-contracts/smart-contract-design-patterns) |                                                              | 2023    | Article        | Hedera                                                       |
| [useful-solidity-patterns](https://github.com/dragonfly-xyz/useful-solidity-patterns) |                                                              | 2022    | Github project | dragonfly-xyz                                                |
| [Enhancing Smart Contract Security with the Circuit Breaker Pattern](https://medium.com/@solidity101/%EF%B8%8F-enhancing-smart-contract-security-with-the-circuit-breaker-pattern-90c86d57c5ab) | Other article: [Circuit Breakers](https://consensys.github.io/smart-contract-best-practices/development-recommendations/precautions/circuit-breakers/) | 10/2023 | Article        | Solidity Academy                                             |
| [Factory Contract](https://research.csiro.au/blockchainpatterns/general-patterns/contract-structural-patterns/factory-contract/) |                                                              | 2023?   | Article        | csiro                                                        |
| [Commit Reveal](https://blockchain-academy.hs-mittweida.de/courses/solidity-coding-beginners-to-intermediate/lessons/solidity-11-coding-patterns/topic/commit-reveal/) | -                                                            | 09/2021 | Article        | [**Mario Oettler**](https://blockchain-academy.hs-mittweida.de/author/oettlerhs-mittweida-de/) / BCAM |



## Assembly / EVM

| Title                                                        | Description                                                  | Date    | Support | Author                                        |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------- | ------- | --------------------------------------------- |
| [Reversing and Debugging EVM Smart contracts : 5 Instructions to end/abort the Execution (Part 4)](https://trustchain.medium.com/reversing-and-debugging-evm-the-end-of-time-part-4-3eafe5b0511a) | In the EVM There is in total 5 ways to end the execution of a smart contract | 06/2022 | Article | Alain / Web3hackingLabs                       |
| [Reversing and debugging EVM Smart contracts: First steps in assembly (part 1)](https://trustchain.medium.com/reversing-and-debugging-evm-smart-contracts-392fdadef32d) | learn how to debug and reverse **EVM (Ethereum Virtual Machine)** smart contracts. | 06/2022 | Article | Alain                                         |
| [Revert](https://twitter.com/prady_v/status/1608767136331362306) | Thread twitter on Revert                                     | 12/2022 | Threads | prady.eth                                     |
| [Stack Too Deep](https://soliditydeveloper.com/stacktoodeep) |                                                              | 09/2020 | Article | Solidity developer                            |
| [Learn to read and understand EVM calldata](https://r4bbit.substack.com/p/abi-encoding-and-evm-calldata) | With foundry cast                                            | 04/2023 | Article | [r4bbit](https://substack.com/@r4bbit)        |
| [Reversing The EVM: Raw Calldata](https://degatchi.com/articles/reading-raw-evm-calldata/) |                                                              | 12/2022 | Article | DeGatchi                                      |
| [A deep-dive into Solidity – contract creation and the init code](https://leftasexercise.com/2021/09/05/a-deep-dive-into-solidity-contract-creation-and-the-init-code/) |                                                              | 09/2021 | Article | [LeftAsExercise](https://leftasexercise.com/) |
| [Ethereum precompiled contracts](https://www.rareskills.io/post/solidity-precompiles) | Ethereum precompiles behave like smart contracts built into the Ethereum protocol. | 04/2023 | Article | RareSkills                                    |
| [Understanding smart contract metadata](https://www.rareskills.io/post/solidity-metadata) | When solidity generates the bytecode for the smart contract to be deployed, it appends metadata about the compilation at the end of the bytecode. | 06/2023 | Article | RareSkills                                    |



## Test

| Title                                                        | Description                                             | Date    | Support | Author                                                       |
| ------------------------------------------------------------ | ------------------------------------------------------- | ------- | ------- | ------------------------------------------------------------ |
| [Solidity Security Practices Part X: Symbolic Execution](https://medium.com/coinmonks/solidity-security-practices-part-x-symbolic-execution-3af2b82f53aa) | detailed introduction to symbolic execution in Solidity | 04/2023 | Article | [Kaan Kaçar](https://medium.com/@kaankacar02?source=post_page-----3af2b82f53aa--------------------------------) |

