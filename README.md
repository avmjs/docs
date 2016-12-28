## Welcome

Welcome to `ethjs`, a simple set of modules and examples for the Ethereum ecosystem.

## About

`ethjs` is a set of small, highly composable modules and interfaces for the Ethereum ecosystem.

## Experimental

Note, all `ethjs` modules are highly experimental. If you want to bring `ethjs` into production use, please help out, and start user testing `ethjs`!

We are aiming for **early January 2017** for production use.

## Differences with Web3.js

We love `web3.js`! [`web3.js`](https://github.com/ethereum/web3.js) has brought us a first pass at a library for building Ethereum dApps and apps. We hope to work closely with the developers and maintainers of web3 to foster better design, share knowledge and give alternative design insight.

However, there are some critical differences:
  - `ethjs` has no support for decimal numbers [read more](https://github.com/ethjs/ethjs/blob/master/docs/user-guide.md#big-numbersnumber-handling)
  - `ethjs` uses `BN.js`, not `BigNumber.js`
  - `ethjs` uses `Buffer.js` for most of its handling of hex/utf-8 conversion
  - `ethjs` is highly optimized for the browser (about 30kb smaller than web3.js minified)
  - `ethjs` has a module first approach, small seperate isolated modules which make up the complex whole
  - `ethjs` is ES6+ first, published in ES5 compliance via `babel`
  - `ethjs` has a 100% build uptime/+99% coverage policy across all repos
  - `ethjs` is designed to be highly configurable at every level of each module
  - `ethjs` has an enforced UNIX philosophy design policy

## Heads Up

Note, all `ethjs` modules may eventually be merged into the `ethereumjs` Github org. We are currently in discussions to find the best path forward for these modules.

## Relationship with `ethereumjs`

`ethjs` is a set of modules that are part of the EthereumJS community. We dedicate all these modules to the javascript developers of the Ethereum community in the hopes that they might be useful for dApps, apps and developers.

While we have no official affiliation with the Ethereum foundation, we will be working closely with the Ethereum community.

## Contributing

Please help better the ecosystem by submitting issues and pull requests to `ethjs`. We need all the help we can get to build the absolute best linting standards and utilities. We follow the AirBNB linting standard and the unix philosophy.

## Guides

You'll find more detailed information on using `ethjs` and tailoring it to your needs in our guides:

- [User guide](https://github.com/ethjs/ethjs/blob/master/docs/user-guide.md) - Usage, configuration, FAQ and complementary tools.
- [Developer guide](https://github.com/ethjs/ethjs/blob/master/docs/developer-guide.md) - Contributing to `ethjs` and writing your own code and coverage.
- [Examples](http://github.com/ethjs/examples) - Examples of `ethjs` in use.

## Help out

There is always a lot of work to do, and will have many rules to maintain. So please help out in any way that you can:

- Create, enhance, and debug ethjs rules (see our guide to ["Working on rules"](./.github/CONTRIBUTING.md)).
- Improve documentation.
- Chime in on any open issue or pull request.
- Open new issues about your ideas for making `ethjs` better, and pull requests to show us how your idea works.
- Add new tests to *absolutely anything*.
- Create or contribute to ecosystem tools.
- Spread the word!

Please consult our [Code of Conduct](CODE_OF_CONDUCT.md) docs before helping out.

We communicate via [issues](https://github.com/ethjs/ethjs/issues) and [pull requests](https://github.com/ethjs/ethjs/pulls).

## Important documents

- [Code of Conduct](CODE_OF_CONDUCT.md)
- [License](https://raw.githubusercontent.com/ethjs/ethjs/master/LICENSE)

## Special Thanks

`ethjs` was built by a strong community of Ethereum developers. A special thanks to:

- [Fabian Vogelsteller](https://twitter.com/feindura?lang=en) - for his work on `Mist` and `web3.js`
- [Tim Coulter](https://github.com/tcoulter) - for his work on `TestRPC` and `Truffle`
- [Aaron Davis](https://github.com/kumavis) - for his guidence and work on `MetaMask` and `ethereumjs`
- [Richard Moore](https://github.com/ricmoo) - for his work on `ethers-io` and `ethers-wallet` from which so much of `ethjs` is build from
- [Karl Floersch](https://twitter.com/karl_dot_tech?lang=en) - for his guidence and support
- [Martin B.](https://github.com/wanderer) - for his work on `ethereumjs`
- [Alex Beregszaszi](https://github.com/axic) - for his work on `ethereumjs`
- [Vitalik Buterin](https://twitter.com/VitalikButerin) - for creating `Ethereum`