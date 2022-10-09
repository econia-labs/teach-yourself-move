# Teach yourself Move on Aptos

<!--- This markdown file uses reference-style links, listed at the bottom -->

## Contents

<!--- This table of contents is automatically generated via the "Markdown All in One" extension for VS Code -->
- [Teach yourself Move on Aptos](#teach-yourself-move-on-aptos)
  - [Contents](#contents)
  - [Don't forget](#dont-forget)
  - [How to use this guide](#how-to-use-this-guide)
  - [Resources](#resources)
    - [Reading](#reading)
    - [Repositories](#repositories)
    - [Examples](#examples)
    - [Tutorials](#tutorials)
    - [Tools](#tools)
  - [Recommended sequence](#recommended-sequence)
    - [Checklist](#checklist)
  - [Thank you](#thank-you)

## Don't forget

Everyone begins as a `n00b`, including the [Econia][Econia documentation] developers.
For example, here are 6 of the first 9 commits in the [Econia repository][Econia]:

```zsh
* c34e9a4 Include jupyter notebook demo for tx tutorial
* 939080d Complete Aptos.dev Move tutorial through step 1
* 38f997f Complete official Move tutorial
* 9d4f7b5 Add official Move tutorial through step 6
* 263cd8b Add move tutorial up to step 5, Magnus6.eth ep. 2
* 6c2b34d Add AssetCoin move module per official tutorial
* d8a2f96 Add interface tools per TestCoin transfer tutorial
```

If ever you get discouraged, just remember there is a vibrant open-source community out there willing to help you on your [Move][Move book] journey.
We are all in this together, and [Move][Move book] is for everyone!

## How to use this guide

This guide contains two major sections:
  * [Resources]
  * [Recommended sequence]

The [Resources] section contains a helpful list of various resources for your reference.
The [Recommended sequence] section contains a recommended learning sequence that you can follow in order, which was put together by the [Econia][Econia documentation] developers when they first began learning!

## Resources

### Reading

* [Block-STM paper]
* [The Move Book][Move book]
* [Aptos Labs Medium page]
* [Aptos documentation]
* [Move specification language]
* [Unofficial Move Book]
* [The Genesis of Aptos]
* [The Aptos Vision]
* [Expanding the Aptos Community]
* [Aptos Labs' Block-STM Article]
* [Econia documentation]!
* [Move: An Auditor's Introduction]
* [Move Fast & Break Things]
* [BCS Specification]

### Repositories

* [aptos-core]
* [Aptos framework]
* [move]
* [move-cli]
* [move-stdlib]
* [move-prover]
* [econia][Econia]!

### Examples

* [Move documentation examples]
* [Awesome Move]
* [aptos.tools]

### Tutorials

* [Aptos official tutorials]
* [Move official tutorial]
* [Wayne Culbreth's tutorials]
* [magnum6.eth tutorials] (same person, different website)
* [Zellic's Move Prover tutorial]

### Tools

* [Aptos CLI]
* [Aptos explorer]
* [Aptos SDKs]
* [Econia developer setup]
* [move-to-ts]
* [VS Code Move syntax extension]
* [VS Code Move analyzer extension]

## Recommended sequence

* Items marked `read` are to be completed before the beginning of the next item, but may be begun before the prior item.
  * It may be easier to break up reading and start early, interspersing with tutorials.
* When a tutorial is marked `do`, re-write all code.
  * Do not download sample code.
  * Do not copy-paste.
  * If necessary, running from within a provided repo is necessary as long as it is solely in the interest of duplicating behavior to be expected from the already re-written repo.
* When an item is marked `explore`, consider the following:
  * Re-implement examples but with modifications.
  * Create your own new examples using the provided library/framework.
  * Read whatever seems interesting!

### Checklist

Feel free to clone this repo and [check off items][markdown checkbox] as you go!

1. - [x] `read` [This checklist's instructions](#checklist)
1. - [ ] `read` [The Genesis of Aptos]
1. - [ ] `read` [The Aptos Vision]
1. - [ ] `do` [Move official tutorial]
1. - [ ] `read` [Expanding the Aptos Community]
1. - [ ] `read` [Aptos Labs' Block-STM Article]
1. - [ ] `do` [Getting started]
1. - [ ] `read` [Block-STM paper] (sections 1 and 2)
1. - [ ] `read` [magnum6.eth baseline] article
1. - [ ] `do` [magnum6.eth create things] tutorial
1. - [ ] re-`read` [Block-STM paper] (sections 1 and 2)
1. - [ ] `do` [Wayne Culbreth's Episode 2] tutorial
1. - [ ] `read` [Aptos documentation] homepage
1. - [ ] `do` [Wayne Culbreth's Episode 3] tutorial
1. - [ ] `read` [Transactions and states]
1. - [ ] `do` [Your first transaction]
1. - [ ] `read` [Accounts]
1. - [ ] `do` [Your first NFT]
1. - [ ] `read` [Move book] (Introduction-4)
1. - [ ] `do` [move-cli] embedded tutorial
1. - [ ] `read` [Move book] (chapters 5-9)
1. - [ ] `do` [Your first Move module]
1. - [ ] `read` [Move book] (chapters 10-14)
1. - [ ] `do` [Your first dApp]
1. - [ ] `read` [Move book] (chapters 15-19)
1. - [ ] `do` [Your first coin]
1. - [ ] `read` [Move book] (chapters 20-23)
1. - [ ] `do` [Wayne Culbreth's Episode 4] tutorial
1. - [ ] `read` [Move book] (chapters 24-27)
1. - [ ] `do` [Zellic's Move Prover tutorial]
1. - [ ] `do` the [Econia developer setup]!
1. - [ ] `explore` the [econia][Econia] repository!
1. - [ ] `explore` the [Econia documentation]!
1. - [ ] `explore` the [Aptos framework]
1. - [ ] `explore` the [Move prover][move-prover]

## Thank you

To all of the open-source folks who came before us!

<!-- Alphabetized reference links -->
[Accounts]:                        https://aptos.dev/concepts/basics-accounts
[aptos-core]:                      https://github.com/aptos-labs/aptos-core
[aptos.tools]:                     https://aptos.tools/
[Aptos CLI]:                       https://aptos.dev/cli-tools/aptos-cli-tool/aptos-cli-index/
[Aptos documentation]:             https://aptos.dev/
[Aptos explorer]:                  https://aptos-explorer.netlify.app/
[Aptos framework]:                 https://github.com/aptos-labs/aptos-core/tree/main/aptos-move/framework
[Aptos Labs' Block-STM Article]:   https://medium.com/aptoslabs/block-stm-how-we-execute-over-160k-transactions-per-second-on-the-aptos-blockchain-3b003657e4ba
[Aptos Labs Medium page]:          https://aptoslabs.medium.com/
[Aptos official tutorials]:        https://aptos.dev/tutorials/aptos-quickstarts
[Aptos SDKs]:                      https://aptos.dev/sdks/aptos-sdk-overview
[Awesome Move]:                    https://github.com/MystenLabs/awesome-move
[BCS Specification]:               https://github.com/diem/bcs
[Block-STM paper]:                 https://arxiv.org/pdf/2203.06871.pdf
[Econia]:                          https://github.com/econia-labs/econia
[Econia documentation]:            https://econia.dev
[Econia developer setup]:          https://github.com/econia-labs/econia#developer-setup
[Expanding the Aptos Community]:   https://medium.com/aptoslabs/expanding-the-aptos-community-38c5b18a84b7
[Getting started]:                 https://aptos.dev/guides/getting-started
[markdown checkbox]:               https://www.markdownguide.org/extended-syntax/#task-lists
[move]:                            https://github.com/move-language/move
[move-cli]:                        https://github.com/move-language/move/tree/main/language/tools/move-cli
[move-prover]:                     https://github.com/move-language/move/tree/main/language/move-prover
[move-to-ts]:                      https://github.com/hippospace/move-to-ts
[move-stdlib]:                     https://github.com/move-language/move/tree/main/language/move-stdlib
[Move: An Auditor's Introduction]: https://osec.io/blog/tutorials/2022-09-06-move-introduction/
[Move book]:                       https://move-language.github.io/move/introduction.html
[Move documentation examples]:     https://github.com/move-language/move/tree/main/language/documentation/examples
[Move Fast & Break Things]:        https://blog.zellic.io/2022/09/06/move-fast-and-break-things-pt-1/
[Move official tutorial]:          https://github.com/move-language/move/tree/main/language/documentation/tutorial
[Move specification language]:     https://github.com/move-language/move/blob/main/language/move-prover/doc/user/spec-lang.md
[Recommended sequence]:            #recommended-sequence
[Resources]:                       #resources
[Transactions and states]:         https://aptos.dev/concepts/basics-txns-states
[Unofficial Move Book]:            https://move-book.com/
[Wayne Culbreth's tutorials]:      https://medium.com/code-community-command
[Wayne Culbreth's Episode 2]:      https://medium.com/code-community-command/were-picking-up-where-we-left-off-at-the-last-episode-so-if-this-is-your-first-time-here-check-394ddb8950f0
[Wayne Culbreth's Episode 3]:      https://medium.com/code-community-command/aptos-tutorial-episode-3-deploy-things-94eb973a7a51
[Wayne Culbreth's Episode 4]:      https://medium.com/code-community-command/aptos-tutorial-episode-4-lets-table-this-for-now-part-1-2e465707f83d
[magnum6.eth tutorials]:           https://mirror.xyz/magnum6.eth
[magnum6.eth baseline]:            https://mirror.xyz/magnum6.eth/V1_HOcpDkjvpRuCY_UacOGVkBJjTS_zRDBkGGIUUoUA
[magnum6.eth create things]:       https://mirror.xyz/magnum6.eth/kgZUk_kXg81AYQs5N5RygpjoK0OqAiH7TWRikznLcjg
[The Aptos Vision]:                https://medium.com/aptoslabs/the-aptos-vision-1028ac56676e
[The Genesis of Aptos]:            https://medium.com/aptoslabs/the-genesis-of-aptos-ff98d86e9445
[VS Code Move analyzer extension]: https://marketplace.visualstudio.com/items?itemName=move.move-analyzer
[VS Code Move syntax extension]:   https://marketplace.visualstudio.com/items?itemName=damirka.move-syntax
[Your first coin]:                 https://aptos.dev/tutorials/your-first-coin
[Your first dApp]:                 https://aptos.dev/tutorials/your-first-dapp/
[Your first transaction]:          https://aptos.dev/tutorials/your-first-transaction
[Your first Move module]:          https://aptos.dev/tutorials/first-move-module
[Your first NFT]:                  https://aptos.dev/tutorials/your-first-nft/
[Zellic's Move Prover tutorial]:   https://github.com/zellic/move-prover-examples