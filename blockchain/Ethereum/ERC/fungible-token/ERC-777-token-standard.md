# ERC-777

[https://eips.ethereum.org/EIPS/eip-777](https://eips.ethereum.org/EIPS/eip-777)

## Introduction

- ERC20 upgrade, with added functionalities
- Enhances token transfer and interaction processes

## General

| Title | Description | Date | Support | Author |
| ----- | ----------- | ---- | ------- | ------ |
|       |             |      |         |        |



## Specific

| Title                                                        | Description        | Date    | Support      | Author                              |
| ------------------------------------------------------------ | ------------------ | ------- | ------------ | ----------------------------------- |
| [Deprecate ERC777 implementation](https://github.com/OpenZeppelin/openzeppelin-contracts/issues/2620) | OpenZeppelin issue | 03/2021 | issue GitHub | **[k06a](https://github.com/k06a)** |
|                                                              |                    |         |              |                                     |

## Security

| Title                                                        | Description                                                  | Date    | Support      | Author                                                       |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------- | ------------ | ------------------------------------------------------------ |
| [One more problem with ERC777](https://mixbytes.io/blog/one-more-problem-with-erc777) | This bug takes advantage of the ERC-777 feature that enables setting a hook receiver. | ?       | Article      | Daniil Ogurtsov / MixBytes                                   |
| [A Dive With ERC-777 And Risk Mitigations](https://medium.com/coinmonks/a-dive-with-erc-777-and-risk-mitigations-9f3ffcac0f78) | This hook hands control flow over to the sender, which can lead to the exploitation of reentrancy vulnerabilities. | 08/2023 | Article      | [BrianKim](https://medium.com/@kimhiepninh02121997?source=post_page-----9f3ffcac0f78--------------------------------) |
| [ERC777 implementation and security clarifications](https://github.com/OpenZeppelin/openzeppelin-contracts/issues/1749) | OpenZeppelin issue                                           | 05/2019 | issue GitHub | guylando                                                     |
| [Skale token](https://consensys.io/diligence/audits/2020/01/skale-token/) | Audit By consensus. ERC-777 callback issue: [Link](https://consensys.io/diligence/audits/2020/01/skale-token/#erc-777-callback-issue) | 01/2020 | Article      | Consensys Diligence                                          |
