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

Everyone begins as a `n00b`, including the [Econia][econia documentation] developers.
For example, here are 6 of the first 9 commits in the [Econia repository][econia]:

```zsh
* c34e9a4 Include jupyter notebook demo for tx tutorial
* 939080d Complete Aptos.dev Move tutorial through step 1
* 38f997f Complete official Move tutorial
* 9d4f7b5 Add official Move tutorial through step 6
* 263cd8b Add move tutorial up to step 5, Magnus6.eth ep. 2
* 6c2b34d Add AssetCoin move module per official tutorial
* d8a2f96 Add interface tools per TestCoin transfer tutorial
```

If ever you get discouraged, just remember there is a vibrant open-source community out there willing to help you on your [Move][move book] journey.
We are all in this together, and [Move][move book] is for everyone!

## How to use this guide

This guide contains two major sections:

- [Resources]
- [Recommended sequence]

The [Resources] section contains a helpful list of various resources for your reference.
The [Recommended sequence] section contains a recommended learning sequence that you can follow in order, which was put together by the [Econia][econia documentation] developers when they first began learning!

## Resources

### Reading

- [Block-STM paper]
- [The Move Book][move book]
- [Aptos Labs Medium page]
- [Aptos documentation]
- [Move specification language]
- [Unofficial Move Book]
- [The Genesis of Aptos]
- [The Aptos Vision]
- [Expanding the Aptos Community]
- [Aptos Labs' Block-STM Article]
- [Econia documentation]!
- [Move: An Auditor's Introduction]
- [Move Fast & Break Things]
- [BCS Specification]

### Repositories

- [aptos-core]
- [Aptos framework]
- [move]
- [move-cli]
- [move-stdlib]
- [move-prover]
- [econia]!

### Examples

- [Move documentation examples]
- [Aptos Move by Example]
- [Awesome Move]
- [aptos.tools]

### Tutorials

- [Aptos official tutorials]
- [Move official tutorial]
- [Wayne Culbreth's tutorials]
- [magnum6.eth tutorials] (same person, different website)
- [Zellic's Move Prover tutorial]

### Tools

- [Aptos CLI]
- [Aptos explorer]
- [Aptos SDKs]
- [Econia developer setup]
- [move-to-ts]
- [VS Code Move syntax extension]
- [VS Code Move analyzer extension]

## Recommended sequence

- Items marked `read` are to be completed before the beginning of the next item, but may be begun before the prior item.
  - It may be easier to break up reading and start early, interspersing with tutorials.
- When a tutorial is marked `do`, re-write all code.
  - Do not download sample code.
  - Do not copy-paste.
  - If necessary, running from within a provided repo is necessary as long as it is solely in the interest of duplicating behavior to be expected from the already re-written repo.
- When an item is marked `explore`, consider the following:
  - Re-implement examples but with modifications.
  - Create your own new examples using the provided library/framework.
  - Read whatever seems interesting!

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
1. - [ ] `explore` the [econia] repository!
1. - [ ] `explore` the [Econia documentation]!
1. - [ ] `explore` the [Aptos framework]
1. - [ ] `explore` the [Move prover][move-prover]

## Thank you

To all of the open-source folks who came before us!

[accounts]: https://aptos.dev/concepts/basics-accounts
[aptos cli]: https://aptos.dev/cli-tools/aptos-cli-tool/aptos-cli-index/
[aptos documentation]: https://aptos.dev/
[aptos explorer]: https://aptos-explorer.netlify.app/
[aptos framework]: https://github.com/aptos-labs/aptos-core/tree/main/aptos-move/framework
[aptos labs medium page]: https://aptoslabs.medium.com/
[aptos labs' block-stm article]: https://medium.com/aptoslabs/block-stm-how-we-execute-over-160k-transactions-per-second-on-the-aptos-blockchain-3b003657e4ba
[aptos move by example]: https://move-developers-dao.gitbook.io/aptos-move-by-example/
[aptos official tutorials]: https://aptos.dev/tutorials/aptos-quickstarts
[aptos sdks]: https://aptos.dev/sdks/aptos-sdk-overview
[aptos-core]: https://github.com/aptos-labs/aptos-core
[aptos.tools]: https://aptos.tools/
[awesome move]: https://github.com/MystenLabs/awesome-move
[bcs specification]: https://github.com/diem/bcs
[block-stm paper]: https://arxiv.org/pdf/2203.06871.pdf
[econia]: https://github.com/econia-labs/econia
[econia developer setup]: https://github.com/econia-labs/econia#developer-setup
[econia documentation]: https://econia.dev
[expanding the aptos community]: https://medium.com/aptoslabs/expanding-the-aptos-community-38c5b18a84b7
[getting started]: https://aptos.dev/guides/getting-started
[magnum6.eth baseline]: https://mirror.xyz/magnum6.eth/V1_HOcpDkjvpRuCY_UacOGVkBJjTS_zRDBkGGIUUoUA
[magnum6.eth create things]: https://mirror.xyz/magnum6.eth/kgZUk_kXg81AYQs5N5RygpjoK0OqAiH7TWRikznLcjg
[magnum6.eth tutorials]: https://mirror.xyz/magnum6.eth
[markdown checkbox]: https://www.markdownguide.org/extended-syntax/#task-lists
[move]: https://github.com/move-language/move
[move book]: https://move-language.github.io/move/introduction.html
[move documentation examples]: https://github.com/move-language/move/tree/main/language/documentation/examples
[move fast & break things]: https://blog.zellic.io/2022/09/06/move-fast-and-break-things-pt-1/
[move official tutorial]: https://github.com/move-language/move/tree/main/language/documentation/tutorial
[move specification language]: https://github.com/move-language/move/blob/main/language/move-prover/doc/user/spec-lang.md
[move-cli]: https://github.com/move-language/move/tree/main/language/tools/move-cli
[move-prover]: https://github.com/move-language/move/tree/main/language/move-prover
[move-stdlib]: https://github.com/move-language/move/tree/main/language/move-stdlib
[move-to-ts]: https://github.com/hippospace/move-to-ts
[move: an auditor's introduction]: https://osec.io/blog/tutorials/2022-09-06-move-introduction/
[recommended sequence]: #recommended-sequence
[resources]: #resources
[the aptos vision]: https://medium.com/aptoslabs/the-aptos-vision-1028ac56676e
[the genesis of aptos]: https://medium.com/aptoslabs/the-genesis-of-aptos-ff98d86e9445
[transactions and states]: https://aptos.dev/concepts/basics-txns-states
[unofficial move book]: https://move-book.com/
[vs code move analyzer extension]: https://marketplace.visualstudio.com/items?itemName=move.move-analyzer
[vs code move syntax extension]: https://marketplace.visualstudio.com/items?itemName=damirka.move-syntax
[wayne culbreth's episode 2]: https://medium.com/code-community-command/were-picking-up-where-we-left-off-at-the-last-episode-so-if-this-is-your-first-time-here-check-394ddb8950f0
[wayne culbreth's episode 3]: https://medium.com/code-community-command/aptos-tutorial-episode-3-deploy-things-94eb973a7a51
[wayne culbreth's episode 4]: https://medium.com/code-community-command/aptos-tutorial-episode-4-lets-table-this-for-now-part-1-2e465707f83d
[wayne culbreth's tutorials]: https://medium.com/code-community-command
[your first coin]: https://aptos.dev/tutorials/your-first-coin
[your first dapp]: https://aptos.dev/tutorials/your-first-dapp/
[your first move module]: https://aptos.dev/tutorials/first-move-module
[your first nft]: https://aptos.dev/tutorials/your-first-nft/
[your first transaction]: https://aptos.dev/tutorials/your-first-transaction
[zellic's move prover tutorial]: https://github.com/zellic/move-prover-examples
