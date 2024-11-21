# Trezor

## Official documentation

| Title                                                        | Description                                                  | Date    | Support | Author      |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------- | ------- | ----------- |
| [Accessing the same address using Trezor Suite, MyEtherWallet, and MetaMask](https://youtu.be/NxEBNCdX7Hg?si=e88CBUm15NiFmcRk) | -                                                            | 01/2022 | Video   | Trezor      |
| [Multiple accounts in Trezor Suite](https://trezor.io/learn/a/multiple-accounts-in-trezor-suite) | For each supported cryptocurrency, Trezor Suite allows you to manage multiple account | 2024    | Doc     | trezor      |
| [Bitcoin addresses and how to use them](https://blog.trezor.io/bitcoin-addresses-and-how-to-use-them-35e7312098ff) | What address type should you use to send and receive Bitcoin? | 11/2020 | Article | SatoshiLabs |
| [What is BIP44?](https://trezor.io/learn/a/what-is-bip44)    | BIP44 is a protocol that provides a structured method for creating and organizing keys in a deterministic wallet | 2024    | Doc     | Trezor      |
| [Use new address for each transaction](https://trezor.io/learn/a/use-new-address-for-each-transaction) | Information on Bitcoin addresses and why you shouldn't reuse them. | 2024    | Doc     | Trezor      |
| [What is a change address?](https://trezor.io/learn/a/what-is-a-change-address) | A change address is an address to which the remainder of a transaction's inputs are sent after the desired amount has been sent to the recipient. | 2024    | Doc     | Trezor      |
|                                                              |                                                              |         |         |             |



## General

| Title                                                        | Description                                    | Date    | Support | Author     |
| ------------------------------------------------------------ | ---------------------------------------------- | ------- | ------- | ---------- |
| [Trezor Model One Tutorial](https://youtu.be/HoMXLkMY5ok?si=kY43quS0qylrQi9K) | (How to Setup Trezor Model One & Trezor Suite) | 04/2023 | Video   | MoneyZG    |
| [Trezor One Review in 2 minutes (2023 Updated)](https://www.youtube.com/watch?v=UUDCcxldUdk) |                                                | 08/2020 | Video   | 99Bitcoins |
|                                                              |                                                |         |         |            |



# Security

| Title                                                        | Description                                                  | Date    | Support | Author                                                       |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------- | ------- | ------------------------------------------------------------ |
| [Security](https://trezor.io/security)                       | -                                                            | -       | Article | Trezor                                                       |
| [Public & Private Keys](https://trezor.io/learn/a/public-private-keys) | We are all familiar with the phrase "not your keys, not you coins," but what does that really mean? | 2024    | Doc     | Trezor                                                       |
| [Check the authenticity of Trezor Model one packaging and contents](https://trezor.io/learn/a/authenticate-model-one) | -                                                            | -       | Article | Trezor                                                       |
| [Case study: fake hardware cryptowallet](https://www.kaspersky.com/blog/fake-trezor-hardware-crypto-wallet/48155/) | ull review of a fake cryptowallet incident. It looks and feels like a Trezor wallet, but puts all your crypto-investments into the hands of criminals. | 05/2024 | Article | Stanislav Golovanov                                          |
| [Stay safe shopping for hardware wallets](https://blog.trezor.io/stay-safe-shopping-for-hardware-wallets-543f144e3d24) | Avoid the risk of supply chain attacks by buying from the official Trezor Shop or an*[**authorized reseller.**](https://trezor.io/resellers/) | 05/2022 | Article | [SatoshiLabs](https://medium.com/@satoshilabs?source=post_page-----543f144e3d24--------------------------------) |

## Vulnerability disclosure

See [Trezor - Past security issues ](https://trezor.io/learn/a/past-security-issues)

| Title                                                        | Issue                                                  | Description                                                  | Date    | Support        | Author          |
| ------------------------------------------------------------ | ------------------------------------------------------ | ------------------------------------------------------------ | ------- | -------------- | --------------- |
| [Extracting seeds from Wallets](https://www.ledger.com/blog/extracting-seeds) |                                                        | We demonstrated that physical access to the device would allow an  attacker to extract the seeds from Ellipal, **Trezor One**, KeepKey, and **Trezor T** | 11/2019 | Article        | Ledger / Donjon |
| [Breaking Trezor One with Side Channel Attacks](https://www.ledger.com/blog/Breaking-Trezor-One-with-SCA/) | [issue](https://github.com/orgs/trezor/discussions/24) | A Side Channel Attack on PIN verification allows an attacker with a stolen Trezor One to retrieve the correct value of the PIN  within a few minutes. Other reading: [Side-Channel assessment of Open Source<br/>Hardware Wallets](https://www.sstic.org/media/SSTIC2019/SSTIC-actes/side_channel_assessment_hardware_wallets/SSTIC2019-Article-side_channel_assessment_hardware_wallets-guillemet_san-pedro_servant.pdf) | 06/2019 | Article        | Ledger / Donjon |
| [Unfixable Seed Extraction on Trezor – A practical and reliable attack](https://www.ledger.com/blog/Unfixable-Key-Extraction-Attack-on-Trezor) |                                                        |                                                              | 01/2019 | Article        | Ledger / Donjon |
| [Kraken Identifies Critical Flaw in Trezor Hardware Wallets](https://blog.kraken.com/product/security/kraken-identifies-critical-flaw-in-trezor-hardware-wallets)<br />[Our Response to the Read Protection Downgrade Attack](https://blog.trezor.io/our-response-to-the-read-protection-downgrade-attack-28d23f8949c6) |                                                        | Kraken Security Labs has devised a way to extract seeds from both cryptocurrency hardware wallets offered from industry leader Trezor, the Trezor One and Trezor Model T. | 01/2020 | Article        | Kraken          |
| [SRAM dump via glitching the firmware update](https://github.com/orgs/trezor/discussions/28) | [issue](https://github.com/orgs/trezor/discussions/28) | Using a special glitching hardware an attacker could trick the device processor into Read Protection level 1 which allows readout of RAM. | 2018    | Article/GitHub | wallet.fail     |



- https://github.com/orgs/trezor/discussions/28





## Past accident



| Title                                                        | Description                                                  | Date    | Support | Author                                                       |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------- | ------- | ------------------------------------------------------------ |
| [Ongoing phishing attacks on Trezor users](https://blog.trezor.io/ongoing-phishing-attacks-on-trezor-users-edd840b17304) | The Mailchimp security team disclosed that a **malicious actor accessed an internal tool** used by customer-facing teams for customer support and account administration. | 04/2022 | Article | [SatoshiLabs](https://medium.com/@satoshilabs?source=post_page-----edd840b17304--------------------------------) |
|                                                              |                                                              |         |         |                                                              |
