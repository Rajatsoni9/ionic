# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [6.1.9-nightly.20220609](https://github.com/ionic-team/ionic/compare/v5.0.0-beta.4...v6.1.9-nightly.20220609) (2022-06-09)


### Bug Fixes

* **build:** Fixes to dev build for react ([#21684](https://github.com/ionic-team/ionic/issues/21684)) ([a0735b9](https://github.com/ionic-team/ionic/commit/a0735b97bfbc48aa3f955faa8c397e93e25a5ff1))
* **item:** only add click event listener to items with inputs ([#22352](https://github.com/ionic-team/ionic/issues/22352)) ([9659ad6](https://github.com/ionic-team/ionic/commit/9659ad63349d5123ca2bd2548a43e37d5ee817e7)), closes [#22011](https://github.com/ionic-team/ionic/issues/22011)
* **react-router:** remove page transition flicker on outlet mounting ([#24667](https://github.com/ionic-team/ionic/issues/24667)) ([bdb5c42](https://github.com/ionic-team/ionic/commit/bdb5c421d2d1f72c123c254e50c6d31b3c1a8f42)), closes [#24666](https://github.com/ionic-team/ionic/issues/24666)
* **react, vue:** correct view now chosen when going back inside tabs ([#23154](https://github.com/ionic-team/ionic/issues/23154)) ([7203190](https://github.com/ionic-team/ionic/commit/72031902347dc279045e2e099f69852a23dd8436)), closes [#23087](https://github.com/ionic-team/ionic/issues/23087) [#23101](https://github.com/ionic-team/ionic/issues/23101)
* **react, vue:** do not show back button when replacing to root page ([#22750](https://github.com/ionic-team/ionic/issues/22750)) ([9e9a372](https://github.com/ionic-team/ionic/commit/9e9a3724979e95f3df1a340be21d16d8664a013c)), closes [#22528](https://github.com/ionic-team/ionic/issues/22528)
* **react, vue:** navigating using ion-back-button now selects correct page ([#22974](https://github.com/ionic-team/ionic/issues/22974)) ([cd8ffd8](https://github.com/ionic-team/ionic/commit/cd8ffd82a03ee69ef4cbd7922544bfc39680def9)), closes [#22830](https://github.com/ionic-team/ionic/issues/22830)
* **react, vue:** tab buttons no longer throw an error if href is undefined ([#22998](https://github.com/ionic-team/ionic/issues/22998)) ([943e3f6](https://github.com/ionic-team/ionic/commit/943e3f6ae37ecc56f21168f057dde77a05e4e144)), closes [#22997](https://github.com/ionic-team/ionic/issues/22997)
* **react:** add missing react memory router ([57eec1c](https://github.com/ionic-team/ionic/commit/57eec1cb0a45490fed2d2bca91daf24194de2cfb))
* **react:** adding custom history to IonReactRouter, closes [#20297](https://github.com/ionic-team/ionic/issues/20297) ([#21775](https://github.com/ionic-team/ionic/issues/21775)) ([d4a5fbd](https://github.com/ionic-team/ionic/commit/d4a5fbd955e8ecccba8b77491943d81fdf5a5ef4))
* **react:** adding dynamic class to ion-page no longer hides component ([#22666](https://github.com/ionic-team/ionic/issues/22666)) ([a01bdb8](https://github.com/ionic-team/ionic/commit/a01bdb8c8dfee760721eeb35a8b556954f3b5b13)), closes [#22631](https://github.com/ionic-team/ionic/issues/22631)
* **react:** android hardware button should invoke browser back ([36939e1](https://github.com/ionic-team/ionic/commit/36939e10ae0b8ac9a9275ee06d8e0d345de7c64f))
* **react:** correctly show ion-back-button when going back ([#23069](https://github.com/ionic-team/ionic/issues/23069)) ([1c93b75](https://github.com/ionic-team/ionic/commit/1c93b75e397961e374620eb43bee3d6bb4389836)), closes [#22692](https://github.com/ionic-team/ionic/issues/22692)
* **react:** Do a better job matching up route to sync, fixes [#20363](https://github.com/ionic-team/ionic/issues/20363) ([#20446](https://github.com/ionic-team/ionic/issues/20446)) ([c0aadd6](https://github.com/ionic-team/ionic/commit/c0aadd60077e5ba379959d93006e3a9c1418263c))
* **react:** dont remove pages when navigating between tabs, fixes [#20398](https://github.com/ionic-team/ionic/issues/20398) ([#20431](https://github.com/ionic-team/ionic/issues/20431)) ([b6fbe98](https://github.com/ionic-team/ionic/commit/b6fbe98812fbab5ef9e0723802605c0711581dd2))
* **react:** fix regression on IonTabsContext not working properly ([#21751](https://github.com/ionic-team/ionic/issues/21751)) ([1351b2e](https://github.com/ionic-team/ionic/commit/1351b2eafcc87065ce3f153c164d7a279a172833))
* **react:** fix regression with history.replace in new react router ([#21698](https://github.com/ionic-team/ionic/issues/21698)) ([81ef3f1](https://github.com/ionic-team/ionic/commit/81ef3f1ecd3d8b5fa32b57f69ceea76501e51feb))
* **react:** fixes swipe to go back regression ([#21791](https://github.com/ionic-team/ionic/issues/21791)) ([a15cd01](https://github.com/ionic-team/ionic/commit/a15cd01bc39a93e8fcd638d75662858bd97873fc))
* **react:** fixng ion-router-outlet ref regresssion ([#21786](https://github.com/ionic-team/ionic/issues/21786)) ([f4a08b7](https://github.com/ionic-team/ionic/commit/f4a08b7ed4a8d5dbacea72aa60040e4d8464f886))
* **react:** improve view matching logic ([#22569](https://github.com/ionic-team/ionic/issues/22569)) ([f891f66](https://github.com/ionic-team/ionic/commit/f891f667082d2deb5f1b5f0f27af46e46ed1ca0f))
* **react:** Keep a hold of previous routes when doing a redirect, closes [#22053](https://github.com/ionic-team/ionic/issues/22053) ([74af3cb](https://github.com/ionic-team/ionic/commit/74af3cb50b089a6bd60d515158e03b18b86455b8))
* **react:** nested router outlets will not reanimate entered views ([#24672](https://github.com/ionic-team/ionic/issues/24672)) ([43aa6c1](https://github.com/ionic-team/ionic/commit/43aa6c11f42fd5cf455c50419d5f5fbb327b2901)), closes [#24107](https://github.com/ionic-team/ionic/issues/24107)
* **react:** redirect routes should unmount leaving component, fixes [#22022](https://github.com/ionic-team/ionic/issues/22022) ([#22029](https://github.com/ionic-team/ionic/issues/22029)) ([b11e06c](https://github.com/ionic-team/ionic/commit/b11e06cec1d3c28bab9f29185fe2c3a2975b092f))
* **react:** remove @ionic/core dependency in @ionic/react-router to resolve yarn install warning ([#23351](https://github.com/ionic-team/ionic/issues/23351)) ([36bfa33](https://github.com/ionic-team/ionic/commit/36bfa3350354e09be6c62f4e4bee0c553c5981a3)), closes [#23346](https://github.com/ionic-team/ionic/issues/23346)
* **react:** remove hardware back button event listener when NavManager is unmounted ([#23224](https://github.com/ionic-team/ionic/issues/23224)) ([c501da7](https://github.com/ionic-team/ionic/commit/c501da73be879db0fea818c507bae4386a47d42e)), closes [#23170](https://github.com/ionic-team/ionic/issues/23170)
* **react:** remove leaving view when routerdirection is back, fixes [#20124](https://github.com/ionic-team/ionic/issues/20124) ([#20268](https://github.com/ionic-team/ionic/issues/20268)) ([5d8e0ed](https://github.com/ionic-team/ionic/commit/5d8e0ed7032265218b96c082d6d57a88d134a295))
* **react:** setting a ref should allow other props to be passed in, closes [#22609](https://github.com/ionic-team/ionic/issues/22609) ([31f45cd](https://github.com/ionic-team/ionic/commit/31f45cdcc953b08749d9db08321fa5ec6cbe2532))
* **react:** setting active tab properly on mount, closes [#21830](https://github.com/ionic-team/ionic/issues/21830) ([#21833](https://github.com/ionic-team/ionic/issues/21833)) ([f58424f](https://github.com/ionic-team/ionic/commit/f58424f62596b9eb82bebb8e07c211e1725c025a))
* **react:** support history@5 in preparation for react router 6 ([#23297](https://github.com/ionic-team/ionic/issues/23297)) ([4da5216](https://github.com/ionic-team/ionic/commit/4da5216b4f65f3d893cc81ebee77261835218f7f)), closes [#23294](https://github.com/ionic-team/ionic/issues/23294)
* **react:** support routes without a path for notfound routes, fixes [#20259](https://github.com/ionic-team/ionic/issues/20259) ([#20261](https://github.com/ionic-team/ionic/issues/20261)) ([85be000](https://github.com/ionic-team/ionic/commit/85be000a4c5b2bcdb82f73f883c2803180806e8a))
* **react:** using autonomous web component for safari support, closes [#21803](https://github.com/ionic-team/ionic/issues/21803) ([bfddb17](https://github.com/ionic-team/ionic/commit/bfddb170659224d0f826762744dfe44a85813d36))
* **reat:** fix tab currentHref when changing tabs, closes [#21834](https://github.com/ionic-team/ionic/issues/21834) ([#21835](https://github.com/ionic-team/ionic/issues/21835)) ([74468ab](https://github.com/ionic-team/ionic/commit/74468ab7972b174ba85bf239306c27080f253a4a))
* **router-outlet:** improve reliability of swipe back gesture when quickly swiping back ([#23527](https://github.com/ionic-team/ionic/issues/23527)) ([fa06942](https://github.com/ionic-team/ionic/commit/fa069424b265891852a07869b6d086a1cb041e93)), closes [#22895](https://github.com/ionic-team/ionic/issues/22895)


### Features

* add ability to continue processing hardware back button events ([#20613](https://github.com/ionic-team/ionic/issues/20613)) ([3821c04](https://github.com/ionic-team/ionic/commit/3821c0463ae9a02e67c835a221c4ea01fab306d1)), closes [#17824](https://github.com/ionic-team/ionic/issues/17824)
* **back-button:** add 'backButtonDefaultHref' property to Ionic Config ([#20491](https://github.com/ionic-team/ionic/issues/20491)) ([1b11ff7](https://github.com/ionic-team/ionic/commit/1b11ff7fb92b75f5c869c79d5e0d5dfd8889597f)), closes [#19305](https://github.com/ionic-team/ionic/issues/19305)
* **react:** add custom elements bundle ([#23896](https://github.com/ionic-team/ionic/issues/23896)) ([c50d895](https://github.com/ionic-team/ionic/commit/c50d895370a56d0809019dc59fe32ec840b72f03))
* **react:** add setupIonicReact function ([#24254](https://github.com/ionic-team/ionic/issues/24254)) ([55db38d](https://github.com/ionic-team/ionic/commit/55db38ddc541c2632c7d3e4e4c9400ff5b5dfe8c)), closes [#24139](https://github.com/ionic-team/ionic/issues/24139)
* **react:** React Router Enhancements ([#21693](https://github.com/ionic-team/ionic/issues/21693)) ([c171ccb](https://github.com/ionic-team/ionic/commit/c171ccbd37c1ee4b4934758a3a759170ff357cb2))





## [6.1.8](https://github.com/ionic-team/ionic/compare/v6.1.7...v6.1.8) (2022-06-01)

**Note:** Version bump only for package @ionic/react-router





## [6.1.7](https://github.com/ionic-team/ionic/compare/v6.1.6...v6.1.7) (2022-05-26)

**Note:** Version bump only for package @ionic/react-router





## [6.1.6](https://github.com/ionic-team/ionic/compare/v6.1.5...v6.1.6) (2022-05-18)

**Note:** Version bump only for package @ionic/react-router





## [6.1.5](https://github.com/ionic-team/ionic/compare/v6.1.4...v6.1.5) (2022-05-11)

**Note:** Version bump only for package @ionic/react-router





## [6.1.4](https://github.com/ionic-team/ionic/compare/v6.1.3...v6.1.4) (2022-05-04)

**Note:** Version bump only for package @ionic/react-router





## [6.1.3](https://github.com/ionic-team/ionic/compare/v6.1.2...v6.1.3) (2022-04-27)

**Note:** Version bump only for package @ionic/react-router





## [6.1.2](https://github.com/ionic-team/ionic/compare/v6.1.1...v6.1.2) (2022-04-20)

**Note:** Version bump only for package @ionic/react-router





## [6.1.1](https://github.com/ionic-team/ionic/compare/v6.1.0...v6.1.1) (2022-04-15)

**Note:** Version bump only for package @ionic/react-router





# [6.1.0](https://github.com/ionic-team/ionic/compare/v6.0.14...v6.1.0) (2022-04-13)

**Note:** Version bump only for package @ionic/react-router





## [6.0.16](https://github.com/ionic-team/ionic/compare/v6.0.15...v6.0.16) (2022-04-08)

**Note:** Version bump only for package @ionic/react-router





## [6.0.15](https://github.com/ionic-team/ionic/compare/v6.0.14...v6.0.15) (2022-04-06)

**Note:** Version bump only for package @ionic/react-router





## [6.0.14](https://github.com/ionic-team/ionic/compare/v6.0.13...v6.0.14) (2022-03-30)

**Note:** Version bump only for package @ionic/react-router





## [6.0.13](https://github.com/ionic-team/ionic/compare/v6.0.12...v6.0.13) (2022-03-23)

**Note:** Version bump only for package @ionic/react-router





## [6.0.12](https://github.com/ionic-team/ionic/compare/v6.0.11...v6.0.12) (2022-03-16)

**Note:** Version bump only for package @ionic/react-router





## [6.0.11](https://github.com/ionic-team/ionic/compare/v6.0.10...v6.0.11) (2022-03-09)

**Note:** Version bump only for package @ionic/react-router





## [6.0.10](https://github.com/ionic-team/ionic/compare/v6.0.9...v6.0.10) (2022-03-02)

**Note:** Version bump only for package @ionic/react-router





## [6.0.9](https://github.com/ionic-team/ionic/compare/v6.0.8...v6.0.9) (2022-02-23)

**Note:** Version bump only for package @ionic/react-router





## [6.0.8](https://github.com/ionic-team/ionic/compare/v6.0.7...v6.0.8) (2022-02-15)

**Note:** Version bump only for package @ionic/react-router





## [6.0.7](https://github.com/ionic-team/ionic/compare/v6.0.6...v6.0.7) (2022-02-09)

**Note:** Version bump only for package @ionic/react-router





## [6.0.6](https://github.com/ionic-team/ionic/compare/v6.0.5...v6.0.6) (2022-02-09)

**Note:** Version bump only for package @ionic/react-router





## [6.0.5](https://github.com/ionic-team/ionic/compare/v6.0.4...v6.0.5) (2022-02-02)


### Bug Fixes

* **react-router:** remove page transition flicker on outlet mounting ([#24667](https://github.com/ionic-team/ionic/issues/24667)) ([bdb5c42](https://github.com/ionic-team/ionic/commit/bdb5c421d2d1f72c123c254e50c6d31b3c1a8f42)), closes [#24666](https://github.com/ionic-team/ionic/issues/24666)
* **react:** nested router outlets will not reanimate entered views ([#24672](https://github.com/ionic-team/ionic/issues/24672)) ([43aa6c1](https://github.com/ionic-team/ionic/commit/43aa6c11f42fd5cf455c50419d5f5fbb327b2901)), closes [#24107](https://github.com/ionic-team/ionic/issues/24107)





## [6.0.4](https://github.com/ionic-team/ionic/compare/v6.0.3...v6.0.4) (2022-01-26)

**Note:** Version bump only for package @ionic/react-router





## [6.0.3](https://github.com/ionic-team/ionic/compare/v6.0.2...v6.0.3) (2022-01-19)

**Note:** Version bump only for package @ionic/react-router





## [6.0.2](https://github.com/ionic-team/ionic/compare/v6.0.1...v6.0.2) (2022-01-11)

**Note:** Version bump only for package @ionic/react-router
