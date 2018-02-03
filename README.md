# Drops of Diamond

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/Drops-of-Diamond/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

This repo is an introduction to plans for developing an implementation of sharding in Javascript, with Drops of Diamond. The actual implementation is planned to be developed as a fork of EthereumJS-VM [here](https://github.com/Drops-of-Diamond/ethereumjs-vm), and maintain compatibility with the original repo in order to be potentially be merged with it.

For an introduction to Ethereum, see https://github.com/ethereum/wiki/wiki/Ethereum-introduction.

For an introduction to sharding, see https://github.com/ethereum/sharding/blob/develop/docs/doc.md.

This repo and the Drops of Diamond project it belongs to is not a part of or owned by the Ethereum Foundation, nor is it endorsed by the Foundation. A different project name and logo may be used (the logo could use a more modern design rather than just using a photo in the public domain), and alternative proposals are welcome. The Drops of Diamond project is not legally incorporated as of yet, so legally it is not an organisation. That should be done, but probably only as needed once the project is more well-developed.

It is expected that when [eWASM](https://github.com/ewasm/design) is implemented, after to Web Assembly, Javascript will be the second-most compatible and performant language with the virtual machine, due to [Web Assembly's design goals to implement compatibility with Javascipt](https://github.com/WebAssembly/design/blob/master/HighLevelGoals.md). Additionally, there is an operational [EthereumJS implementation](https://github.com/ethereumjs/ethereumjs-vm) to build a sharding implementation of, while eWASM is still under development, so it will be easier to build a sharding implementation on top of ethereumjs-vm than it will be to build on top of eWASM.

The very rough plans for development at this stage are to become more familiar with the [sharding code](https://github.com/ethereum/sharding) (a doc is available [here](https://github.com/ethereum/sharding/blob/develop/docs/doc.md)), as well as the [sharding implementation in Py-EVM as it develops](https://github.com/ethereum/py-evm/tree/sharding) and additionally the EthereumJS implementation, then build an implementation in Javascript, integrate it with ethereumJS and build a test network and a main network.

Compensation to developers at this stage can't be offered, as it would depend on some form of revenue, which isn't available at this stage. However, revenue will be more likely to be obtained the more service is demonstrated. All are welcome to contribute, in the spirit of open-soure code and friendly collaboration. If revenue is obtained it will be shared accordingly and fairly with a budget, after setting up a more formal organization, e.g. controlled in a similar fashion to how the Ethereum Foundation is run (or even, perhaps, more transparently). (A grant from the Ethereum Foundation has been applied for, as per [this blog post](https://blog.ethereum.org/2018/01/02/ethereum-scalability-research-development-subsidy-programs/).) If you are interested in making a donation but would prefer to not send it to an individual, please say so on Gitter (click the badge above). It's probably best to have an MVP, or alpha or beta release, before actively raising funds.
