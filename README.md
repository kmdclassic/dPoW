# dPoW client _iguana_

This repository is based on the original SuperNET codebase - commit [f29913e92b117399cd42e2fd05ff0d69d152c8fa](https://github.com/ca333/SuperNET/commit/f29913e92b117399cd42e2fd05ff0d69d152c8fa)

| Integration                      | Status                                                                                                                                          |
| -------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| CI build - Ubuntu (20.04, 22.04) | [![Build Status](https://github.com/komodoplatform/dpow/workflows/CI/badge.svg?maxAge=60)](https://github.com/KomodoPlatform/dPoW/actions)      |
| Codefactor analysis              | [![Grade](https://img.shields.io/codefactor/grade/github/komodoplatform/dpow)](https://www.codefactor.io/repository/github/komodoplatform/dpow) |
| Version                          | [![Version](https://img.shields.io/github/v/release/komodoplatform/dPoW)](https://github.com/KomodoPlatform/dPoW/releases)                      |
| Network Statistics               | https://stats.kmd.io/                                                                                                                           |

---

## Installation

General [Setup instructions](https://github.com/KomodoPlatform/Documentation/blob/nn_docs_update/docs/notary/setup-Komodo-Notary-Node.md)

### Build instructions for NN operations:

`cd iguana`

#### Build iguana for notary operations

`make`

#### Start main-net notarizations:

`./m_notary_main`

**Please note: Automatic UTXO split is deactivated by default.**

## dPoW asset status

#### [Notary Addresses](https://deckersu.github.io/notaries_addresses.html)

[![dPOW Status](https://badges.komodo.earth/svg/date_badge.svg?maxAge=60)](https://komodostats.com)

- active - last notarization less than 2.5 hours ago
- irregular - last notarization more than 2.5 and less than 24 hours ago
- inactive - last notarization more than 24 hours ago

| Coin     | src                                                      | Version/Tree                                                                                           | Status                                                                                                  | dPoW         |
| -------- | -------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------- | ------------ |
| KMDCL      | [kmdclassic](https://github.com/kmdclassic/KmdClassic)       | [6dc1aa2](https://github.com/kmdclassic/KmdClassic/commit/a7f053e6542cb1354f0a2038dd63877a46dc1aa2)    | [![dPOW Status](https://badges.komodo.earth/svg/KMD_badge.svg?maxAge=60)](https://komodostats.com)      | dPoW-Mainnet |
| LTC      | [litecoin](https://github.com/litecoin-project/litecoin) | [0.21.4](https://github.com/litecoin-project/litecoin/tree/beae01d62292a0aab363b7a4d3f606708cea7260)     | [![dPOW Status](https://badges.komodo.earth/svg/KMD_badge.svg?maxAge=60)](https://komodostats.com)      | dPoW-Mainnet |
| PIRATE   | [kmdclassic](https://github.com/kmdclassic/KmdClassic)       | [6dc1aa2](https://github.com/kmdclassic/KmdClassic/commit/a7f053e6542cb1354f0a2038dd63877a46dc1aa2)    | [![dPOW Status](https://badges.komodo.earth/svg/PIRATE_badge.svg?maxAge=60)](https://komodostats.com)   | dPoW-mainnet |
