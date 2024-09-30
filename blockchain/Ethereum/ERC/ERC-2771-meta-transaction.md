# ERC-2771 - Secure Protocol for Native Meta Transactions

[eips.ethereum.org/EIPS/eip-2771](https://eips.ethereum.org/EIPS/eip-2771)

## General

| Title                                                        | Description | Date    | Support       | Author                                                       |
| ------------------------------------------------------------ | ----------- | ------- | ------------- | ------------------------------------------------------------ |
| [What are Meta Transactions (ERC-2771)](https://www.alchemy.com/overviews/meta-transactions) | -           | 08/2023 | Article       | [Harpalsinh Jadeja](https://www.alchemy.com/author/harpalsinh-jadeja) / Alchemy |
| [Standard EIP 2771 Approach](https://docs-gasless.biconomy.io/products/enable-gasless-transactions/choose-an-approach-to-enable-gasless/eip-2771) | -           |         | Article       | Biconomy                                                     |
| [Gelato - Relay ](https://docs.gelato.network/developer-services/relay) | -           |         | Documentation | Gelato                                                       |
| [OpenZeppelin - Meta Transaction](https://docs.openzeppelin.com/contracts/5.x/api/metatx) | -           | v5      | Documentation | OpenZeppelin                                                 |



## Security

| Title                                                        | Description                                                  | Date    | Support | Author                                 |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------- | ------- | -------------------------------------- |
| [Address Spoofing Attack: The Combination of ERC2771 and Multicall is a Bomb](https://blog.verichains.io/p/address-spoofing-attack-the-combination) | -                                                            | 12/2023 | Article | [Th13vn](https://substack.com/@th13vn) |
| [The Critical Thirdweb Vulnerability](https://dedaub.com/blog/critical-thirdweb-vulnerability) | The root cause of the thirdweb critical vulnerability is that independent libraries implementing ERC2771 & Multicall, such as OpenZeppelin Libraries, interact badly, when combined. This allows attackers to spoof the _msgSender() with all sorts of access control implications including **loss of funds**. | 12/2023 | Article | Neville Grech / Dedaub                 |
| [Unveiling the ERC-2771 Context and Multicall Vulnerability](https://blog.solidityscan.com/unveiling-the-erc-2771context-and-multicall-vulnerability-f96ffa5b499f) | On December 4th, 2023, OpenZeppelin was made aware of a crucial security disclosure from the Thirdweb team. They highlighted a potential vulnerability resulting from the integration of ERC-2771 and Multicall standards. This disclosure set in motion a rapid response from the OpenZeppelin team | 12/2023 | Article | Shashank / SolidityScan                |
|                                                              |                                                              |         |         |                                        |
