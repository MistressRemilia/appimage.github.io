---
layout: app

permalink: /tomomaster/
description: TomoChain Governance DApp
license: MIT

icons:
  - tomomaster/icons/128x128/tomomaster.png

screenshots:
  - tomomaster/screenshot.png

authors:
  - name: tomochain
    url: https://github.com/tomochain

links:
  - type: GitHub
    url: tomochain/tomomaster
  - type: Download
    url: https://github.com/tomochain/tomomaster/releases

desktop:
  Desktop Entry:
    Name: tomomaster
    Comment: TomoChain Governance DApp
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: tomomaster
    StartupWMClass: tomomaster
    X-AppImage-Version: 1.1.4.804
    Categories: Network
    X-AppImage-BuildId: 1EzMUDpgOR1EWxiuCd0yPlPG1W2
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
  main: elect.js
  repository:
    type: git
    url: git+https://github.com/tomochain/tomomaster.git
  author: ''
  license: MIT
  bugs:
    url: https://github.com/tomochain/tomomaster/issues
  homepage: https://github.com/tomochain/tomomaster#readme
  dependencies:
    "@chenfengyuan/vue-qrcode": "^1.0.0"
    "@fortawesome/fontawesome-svg-core": "^1.2.8"
    "@fortawesome/free-brands-svg-icons": "^5.5.0"
    "@fortawesome/free-solid-svg-icons": "^5.5.0"
    "@fortawesome/vue-fontawesome": "^0.1.2"
    "@ledgerhq/hw-app-eth": 4.24.0
    "@ledgerhq/hw-transport-u2f": 4.24.0
    axios: "^0.18.0"
    bignumber.js: "^7.2.1"
    bip39: "^2.5.0"
    body-parser: "^1.18.2"
    commander: "^2.17.1"
    config: "^1.30.0"
    ethereumjs-util: "^6.0.0"
    express: "^4.16.3"
    express-validator: "^5.1.2"
    highcharts: "^6.1.1"
    highcharts-vue: "^1.0.4"
    kue: "^0.11.6"
    lodash: "^4.17.10"
    moment: "^2.22.2"
    mongoose: "^5.0.17"
    request: "^2.88.0"
    store: "^2.0.12"
    truffle-hdwallet-provider: 0.0.6
    truffle-privatekey-provider: "^0.1.0"
    url-join: "^4.0.0"
    uuid: "^3.3.2"
    vue-clipboards: "^1.2.4"
    vue-toasted: "^1.1.24"
    vuex: "^3.0.1"
    web3: "^1.0.0-beta.36"
    websocket: "^1.0.26"
    winston: "^3.1.0"
---