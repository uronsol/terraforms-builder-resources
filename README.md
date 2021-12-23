# Terraforms by Mathcastles - Builder Resources

The goal of this repo is to provide resources for the [Terraforms by Mathcastles](https://discord.gg/nJ2tAYZPWm) metaverse hyper-on/in-chain project on the [Ethereum Blockchain](https://ethereum.org/en/) to help creators build or extend Terraforms.

- [Terraforms by Mathcastles - Builder Resources](#terraforms-by-mathcastles---builder-resources)
  - [Help Wanted](#help-wanted)
  - [What are Terraforms](#what-are-terraforms)
  - [Terraforms Contracts](#terraforms-contracts)
  - [Extending Terraforms and Derivatives](#extending-terraforms-and-derivatives)
  - [Terraforming](#terraforming)
  - [On-chain Best Practices](#on-chain-best-practices)
  - [Current sub-community missions](#current-sub-community-missions)
  - [Project Directory](#project-directory)
    - [Visualization Tools](#visualization-tools)
    - [The Bots](#the-bots)


-----

## Help Wanted

Contributions are encouraged and are needed for:

- [ ] General information about the project
- [ ] Extending Terraforms and using Terraforms in derivatives
- [ ] Terraforming
- [ ] On-chain best practices
- [ ] Current sub-community missions
- [ ] Project directory, please add yours through a PR!
- [ ] ???

This is a community repo and pull requests are highly encouraged to expand the repo and the documentation it provides to new builders entering the Terraforms ecosystem.

Extended privileges will be granted quickly to contributors of this repo to ensure that it can be maintained frequently.

## What are Terraforms

There is a [great document](https://docs.google.com/document/d/1e5qOhUCJx528HtDFDagy5r88IJK1LVKLYhd44weO7g4/edit) by `@astrostl` in the [Community Discord](https://discord.gg/nJ2tAYZPWm) that explains the project in detail. Please refer to this document if you're unsure of what Terraforms are.

## Terraforms Contracts

There are three Terraforms contracts:

- https://etherscan.io/address/0x49957Ca2F1E314c2cf70701816bf6283b7215811
  - Minting and terraforming contract
  - Provides read access to various attributes of a Terraform plot
- https://etherscan.io/address/0x2521beb44d433a5b916ad9d5ab51b98378870072
  - SVG contract
- https://etherscan.io/address/0x49957ca2f1e314c2cf70701816bf6283b7215811
  - Augmentation contract
- https://etherscan.io/address/0xa5afc9fe76a28fb12c60954ed6e2e5f8cef64ff2#readContract
  - Token contract

## Extending Terraforms and Derivatives

Help wanted :)

## Terraforming

Basic Terraforming is avaible in `@astrostl`'s [Unofficial FAQ](https://docs.google.com/document/d/1e5qOhUCJx528HtDFDagy5r88IJK1LVKLYhd44weO7g4/edit)

- https://docs.google.com/spreadsheets/d/1Uh1-bVoLarlGUbg-2QAAosLRazOzXzO8OvFMyTkiIeo/edit#gid=0
  - Tool to help visualize terraforming plots
  - Credit to `@RueLibbe`

## On-chain Best Practices

Help wanted :)

-----

## Current sub-community missions

Sub-community projects are listed here for individuals who would like to discover what they would like to work on for Terraforms. If your sub-community is not listed here please submit a PR.

- Level 5 Conservation Group
  - Intends to preserve level 5 in Terraforms as terrain

## Project Directory

### Visualization Tools

- https://github.com/uronsol/terraforms-characters-colors
  - Visualizes colors and character sets
  - https://terraforms.oolong.lol/search
  - JavaScript


- https://github.com/uronsol/terraforms-plot-3d
  - Visualizes Terraforms metadata in 3D
  - Python


- https://codepen.io/0x0112/pen/mdBMNPm
  - Drawing tool for a Terraform plot, simulated in a dream state
  - Credit to `0x0112.eth`
  - How to:
    1. In a separate tab, load your plot in the token viewer (https://tokens.mathcastles.xyz/terraforms/token-html/531)
    2. Right click the page, select "View Page Source" to view the HTML
    3. Select all, then copy the HTML content
    4. Paste the content into the HTML pane in codepen
  - Paint Controls (via keyboard)
    q - brush size
    a - brush (controls cell height)
    e - erase (must hold down e while "painting" to erase)
    c - copy dream to clipboard

Committing your dream
  Once you've copied your dream to your clipboard, you can paste it into the `dream` field of the `commitDreamToCanvas` write function of the contract (done via Etherscan)

### The Bots

- https://github.com/adriendulong/listen-dream
  - Twitter bot that tweets when a plot is terraformed
  - https://twitter.com/terradream_bot
