<img src="https://raw.githubusercontent.com/vapjs/docs/master/assets/vapjs-image.png" width="250" />

## Welcome

Welcome to `vapjs`, a simple set of modules and examples for the Vapory ecosystem.

## Experimental

Note, all `vapjs` modules are highly experimental. If you want to bring `vapjs` into production use, please help out, and start user testing `vapjs`!

We are aiming for **early January 2017** for production use.

## Web3.js

We love `web3.js`! [`web3.js`](https://github.com/vaporyco/web3.js) has brought us a first pass at a library for building Vapory dApps and apps. We hope to work closely with the developers and maintainers of web3 to foster better design, share knowledge and give alternative design insight.

However, there are some critical differences between `vapjs` and `web3.js`:
  - `vapjs` has no support for decimal numbers [read more](https://github.com/vapjs/vapjs/blob/master/docs/user-guide.md#big-numbersnumber-handling)
  - `vapjs` uses **BN.js**, not `BigNumber.js` [read more](https://github.com/vapjs/vapjs/blob/master/docs/user-guide.md#big-numbersnumber-handling)
  - `vapjs` is **async only** for all RPC/data packet methods
  - `vapjs` uses `Buffer.js` for handling of hex/utf-8 conversion
  - `vapjs` is highly optimized for the browser (about **30kb** smaller than web3.js minified)
  - `vapjs` has a module first approach, small isolated modules which make up the complex whole
  - `vapjs` is **ES6+ first**, published with **ES5** standard via `babel`
  - `vapjs` has a **100% build uptime/+99% coverage** policy across all repos
  - `vapjs` is designed with **high configurability** at every level of each module
  - `vapjs` has a fail loudly, early (preferably within async) policy
  - `vapjs` has an enforced [UNIX philosophy](https://en.wikipedia.org/wiki/Unix_philosophy) design policy

## Heads Up

Note, all `vapjs` modules may eventually be merged into the `vaporyjs` Github org. We are currently in discussions to find the best path forward for these modules.

## Relationship with [`vaporyjs`](https://github.com/vaporyjs)

`vapjs` is a set of modules that are part of the VaporyJS community. We dedicate all these modules to the javascript developers of the Vapory community in the hopes that they might be useful for dApps, apps and developers.

While we have no official affiliation with the Vapory foundation, we will be working closely with the Vapory community.

Please visit, [github.com/vaporyjs](https://github.com/vaporyjs) for more.

## Contributing

Please help better the ecosystem by submitting issues and pull requests to `vapjs`. We need all the help we can get to build the absolute best linting standards and utilities. We follow the AirBNB linting standard and the unix philosophy.

## Guides

You'll find more detailed information on using `vapjs` and tailoring it to your needs in our guides:

- [User guide](https://github.com/vapjs/vapjs/blob/master/docs/user-guide.md) - Usage, configuration, FAQ and complementary tools.
- [Developer guide](https://github.com/vapjs/vapjs/blob/master/docs/developer-guide.md) - Contributing to `vapjs` and writing your own code and coverage.
- [Examples](http://github.com/vapjs/examples) - Examples of `vapjs` in use.

## Module Guide

Here is a map of the `vapjs` modules with a brief explanation of each.

#### Interfaces
 - [vapjs](http://github.com/vapjs/vapjs) - a simple interface of various modules

#### Querying/RPC
 - [vapjs-query](http://github.com/vapjs/vapjs-query) - a module for querying the RPC layer with payload formatting
 - [etjs-rpc](http://github.com/vapjs/vapjs-rpc) - a module for querying the RPC layer without formatting

#### Providers
 - [vapjs-provider-signer](http://github.com/vapjs/vapjs-provider-signer) - sign raw transactions at the provider level
 - [vapjs-provider-http](http://github.com/vapjs/vapjs-provider-http) - a basic http provider

#### Unit Conversion
 - [vapjs-unit](http://github.com/vapjs/vapjs-unit) - convert between units such as `vapor` and `wei`

#### Formatting
 - [vapjs-format](http://github.com/vapjs/vapjs-format) - payload formatter for the Vapory RPC layer
 - [vapjs-schema](http://github.com/vapjs/vapjs-schema) - the entire Vapory RPC schema as a JSON object
 - [vapjs-abi](http://github.com/vapjs/vapjs-abi) - Solidity transaction formatting

#### Filtering/Events
 - [vapjs-filter](http://github.com/vapjs/vapjs-filter) - filter and event handling for Vapory RPC filters

#### Contract Handling
 - [vapjs-contract](http://github.com/vapjs/vapjs-contract) - a contract object abstraction

#### Transaction Signing
 - [vapjs-signer](http://github.com/vapjs/vapjs-signer) - a raw transaction signer

#### Accounts
 - [vapjs-account](http://github.com/vapjs/vapjs-account) - a module for creating and managing Vapory accounts

#### Utils
 - [vapjs-util](http://github.com/vapjs/vapjs-util) - simple utils mainly for handling strings and hex values

## Help out

There is always a lot of work to do, and will have many rules to maintain. So please help out in any way that you can:

- Create, enhance, and debug vapjs rules (see our guide to ["Working on rules"](./.github/CONTRIBUTING.md)).
- Improve documentation.
- Chime in on any open issue or pull request.
- Open new issues about your ideas for making `vapjs` better, and pull requests to show us how your idea works.
- Add new tests to *absolutely anything*.
- Create or contribute to ecosystem tools.
- Spread the word!

Please consult our [Code of Conduct](CODE_OF_CONDUCT.md) docs before helping out.

We communicate via [issues](https://github.com/vapjs/vapjs/issues) and [pull requests](https://github.com/vapjs/vapjs/pulls).

## Important documents

- [Code of Conduct](CODE_OF_CONDUCT.md)
- [License](https://raw.githubusercontent.com/vapjs/vapjs/master/LICENSE)

## Special Thanks

`vapjs` was built by a strong community of Vapory developers. A special thanks to:

- [Fabian Vogelsteller](https://twitter.com/feindura?lang=en) - for his work on `Mist` and `web3.js`
- [Tim Coulter](https://github.com/tcoulter) - for his work on `TestRPC` and `Truffle`
- [Aaron Davis](https://github.com/kumavis) - for his guidence and work on `MetaMask` and `vaporyjs`
- [Richard Moore](https://github.com/ricmoo) - for his work on `ethers-io` and `vapors-wallet` from which so much of `vapjs` is build from
- [Karl Floersch](https://twitter.com/karl_dot_tech?lang=en) - for his guidence and support
- [Martin B.](https://github.com/wanderer) - for his work on `vaporyjs`
- [Alex Beregszaszi](https://github.com/axic) - for his work on `vaporyjs`
- [Vitalik Buterin](https://twitter.com/VitalikButerin) - for creating `Vapory`
