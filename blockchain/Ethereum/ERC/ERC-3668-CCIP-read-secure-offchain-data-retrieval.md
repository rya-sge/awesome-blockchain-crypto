# ERC-3668 - CCIP Read: Secure offchain data retrieval

See https://eips.ethereum.org/EIPS/eip-3668

Minimising storage and transaction costs on Ethereum has driven contract authors to adopt a variety of techniques for moving data offchain, including hashing, recursive hashing (eg Merkle Trees/Tries) and L2 solutions. While each solution has unique constraints and parameters, they all share in common the fact that enough information is stored onchain to validate the externally stored data when required.

Thus far, applications have tended to devise bespoke solutions rather than trying to define a universal standard. This is practical - although inefficient - when a single offchain data storage solution suffices, but rapidly becomes impractical in a system where multiple end-users may wish to make use of different data storage and availability solutions based on what suits their needs.

By defining a common specification allowing smart contract to fetch data from offchain, we facilitate writing clients that are entirely agnostic to the storage solution being used, which enables new applications that can operate without knowing about the underlying storage details of the contracts they interact with.

### Use

Use by Farcaster, see [docs.farcaster.xyz/learn/architecture/ens-names#registry](https://docs.farcaster.xyz/learn/architecture/ens-names#registry)

## General

| Title | Description | Date | Support | Author |
| ----- | ----------- | ---- | ------- | ------ |
|       |             |      |         |        |
|       |             |      |         |        |
|       |             |      |         |        |
|       |             |      |         |        |

