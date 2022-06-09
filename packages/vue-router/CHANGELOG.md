# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [6.1.9-nightly.20220609](https://github.com/ionic-team/ionic/compare/v5.0.0-beta.4...v6.1.9-nightly.20220609) (2022-06-09)


### Bug Fixes

* **react, vue:** correct view now chosen when going back inside tabs ([#23154](https://github.com/ionic-team/ionic/issues/23154)) ([7203190](https://github.com/ionic-team/ionic/commit/72031902347dc279045e2e099f69852a23dd8436)), closes [#23087](https://github.com/ionic-team/ionic/issues/23087) [#23101](https://github.com/ionic-team/ionic/issues/23101)
* **react, vue:** do not show back button when replacing to root page ([#22750](https://github.com/ionic-team/ionic/issues/22750)) ([9e9a372](https://github.com/ionic-team/ionic/commit/9e9a3724979e95f3df1a340be21d16d8664a013c)), closes [#22528](https://github.com/ionic-team/ionic/issues/22528)
* **react, vue:** navigating using ion-back-button now selects correct page ([#22974](https://github.com/ionic-team/ionic/issues/22974)) ([cd8ffd8](https://github.com/ionic-team/ionic/commit/cd8ffd82a03ee69ef4cbd7922544bfc39680def9)), closes [#22830](https://github.com/ionic-team/ionic/issues/22830)
* **react, vue:** tab buttons no longer throw an error if href is undefined ([#22998](https://github.com/ionic-team/ionic/issues/22998)) ([943e3f6](https://github.com/ionic-team/ionic/commit/943e3f6ae37ecc56f21168f057dde77a05e4e144)), closes [#22997](https://github.com/ionic-team/ionic/issues/22997)
* **vue:** back button now selects correct route when navigating from view multiple times ([#24060](https://github.com/ionic-team/ionic/issues/24060)) ([a09d7d4](https://github.com/ionic-team/ionic/commit/a09d7d4ab6dd0d90204015eaaf232ed190753c56)), closes [#23987](https://github.com/ionic-team/ionic/issues/23987)
* **vue:** canGoBack method now works correctly ([#24188](https://github.com/ionic-team/ionic/issues/24188)) ([7c43589](https://github.com/ionic-team/ionic/commit/7c43589b0a486f71ee2ae5a4cdcd73071fcd31b9)), closes [#24109](https://github.com/ionic-team/ionic/issues/24109)
* **vue:** canGoBack now returns correct result with initial load redirect ([#22071](https://github.com/ionic-team/ionic/issues/22071)) ([8227844](https://github.com/ionic-team/ionic/commit/8227844cbc6da252acb97bfa0f9a2cefa40185f9))
* **vue:** correct route is replaced when using router.replace ([#24533](https://github.com/ionic-team/ionic/issues/24533)) ([90458da](https://github.com/ionic-team/ionic/commit/90458da406e2f7a6675be185409ea78595a35128)), closes [#24226](https://github.com/ionic-team/ionic/issues/24226)
* **vue:** correct views are now unmounted in tabs ([#25270](https://github.com/ionic-team/ionic/issues/25270)) ([5e23fb1](https://github.com/ionic-team/ionic/commit/5e23fb1ce4e5b6e53828bde59268170f604167ba)), closes [#25255](https://github.com/ionic-team/ionic/issues/25255)
* **vue:** correctly determine leaving view when transitioning to a new instance of a previous page ([#22655](https://github.com/ionic-team/ionic/issues/22655)) ([e3a05bf](https://github.com/ionic-team/ionic/commit/e3a05bfeb55d8eaa38aa08a37859aa4df6ffa2d4)), closes [#22654](https://github.com/ionic-team/ionic/issues/22654) [#22658](https://github.com/ionic-team/ionic/issues/22658)
* **vue:** correctly handle navigation failures ([#22621](https://github.com/ionic-team/ionic/issues/22621)) ([216f51b](https://github.com/ionic-team/ionic/commit/216f51b12a8c4ae7b410f47ce3d350ea513b68a1)), closes [#22591](https://github.com/ionic-team/ionic/issues/22591)
* **vue:** correctly handle query params ([#22253](https://github.com/ionic-team/ionic/issues/22253)) ([6849dd3](https://github.com/ionic-team/ionic/commit/6849dd3483fb90aac1ff19834390a652c59a74de)), closes [#22229](https://github.com/ionic-team/ionic/issues/22229)
* **vue:** correctly pass route props to components ([#22476](https://github.com/ionic-team/ionic/issues/22476)) ([0956f8b](https://github.com/ionic-team/ionic/commit/0956f8bc5588836996c8c74f98166c347414a312)), closes [#22472](https://github.com/ionic-team/ionic/issues/22472)
* **vue:** correctly render child pages in tabs ([#22141](https://github.com/ionic-team/ionic/issues/22141)) ([7e449a1](https://github.com/ionic-team/ionic/commit/7e449a1ca62956d36b92c32289e5db7a3acb6718))
* **vue:** correctly show ion-back-button when going back ([#22260](https://github.com/ionic-team/ionic/issues/22260)) ([39d2530](https://github.com/ionic-team/ionic/commit/39d2530427b1cd86975fc95ab2c8da9f4b0b27b3)), closes [#22217](https://github.com/ionic-team/ionic/issues/22217)
* **vue:** correctly switch tabs after going back ([#22309](https://github.com/ionic-team/ionic/issues/22309)) ([daf6a92](https://github.com/ionic-team/ionic/commit/daf6a92127d36c20f3445f83bd7bd3e739bb1b27)), closes [#22307](https://github.com/ionic-team/ionic/issues/22307)
* **vue:** ensure that only tab pages get added to the tab navigation stack ([#25045](https://github.com/ionic-team/ionic/issues/25045)) ([a0054a7](https://github.com/ionic-team/ionic/commit/a0054a7cbd52def24c18fd2dadfd2e49a42b8980)), closes [#24859](https://github.com/ionic-team/ionic/issues/24859)
* **vue:** ensure view is updated correctly when replacing a route outside of a nav guard ([#22429](https://github.com/ionic-team/ionic/issues/22429)) ([5a4d0c0](https://github.com/ionic-team/ionic/commit/5a4d0c0217ce93f98364bdd4d8d163679f82a6b3)), closes [#22412](https://github.com/ionic-team/ionic/issues/22412)
* **vue:** going back with query params now goes to correct view ([#22350](https://github.com/ionic-team/ionic/issues/22350)) ([561a4ac](https://github.com/ionic-team/ionic/commit/561a4ac535432873860c3d0a4ac60481929d9089)), closes [#22324](https://github.com/ionic-team/ionic/issues/22324)
* **vue:** improve compatibility with route guards ([#22371](https://github.com/ionic-team/ionic/issues/22371)) ([31f9bc8](https://github.com/ionic-team/ionic/commit/31f9bc81d6d0fa81f9abe20172bb606651a2d75d)), closes [#22344](https://github.com/ionic-team/ionic/issues/22344)
* **vue:** improve handling of parameterized urls ([#22360](https://github.com/ionic-team/ionic/issues/22360)) ([6fad0fe](https://github.com/ionic-team/ionic/commit/6fad0fe42814cde1126e6df264b99c069849c87a)), closes [#22359](https://github.com/ionic-team/ionic/issues/22359)
* **vue:** improve path matching when going back ([#22275](https://github.com/ionic-team/ionic/issues/22275)) ([b06ae16](https://github.com/ionic-team/ionic/commit/b06ae165912cbab811fe4a3c35b4e2b3fe0b425b)), closes [#22258](https://github.com/ionic-team/ionic/issues/22258)
* **vue:** improve path matching with tabs ([#22807](https://github.com/ionic-team/ionic/issues/22807)) ([2a3ce9a](https://github.com/ionic-team/ionic/commit/2a3ce9a74e85111a2f1f470b9d8bfe2cda793ca5)), closes [#22519](https://github.com/ionic-team/ionic/issues/22519)
* **vue:** ion-page component is properly shown with HMR ([#22319](https://github.com/ionic-team/ionic/issues/22319)) ([c5ab562](https://github.com/ionic-team/ionic/commit/c5ab562eaa098717407e6b3e8139abd2112246a2))
* **vue:** lifecycle events are correctly fired in component context ([#22348](https://github.com/ionic-team/ionic/issues/22348)) ([bcef804](https://github.com/ionic-team/ionic/commit/bcef804deac4dea27def475460aff4cdf0d7d2fc)), closes [#22338](https://github.com/ionic-team/ionic/issues/22338)
* **vue:** mount correct views when navigating ([#24056](https://github.com/ionic-team/ionic/issues/24056)) ([24659a5](https://github.com/ionic-team/ionic/commit/24659a527abe0c70df7e8ae6da3dcb4017bf500c)), closes [#23914](https://github.com/ionic-team/ionic/issues/23914)
* **vue:** navigating between parameterized pages now results in page transition ([#23525](https://github.com/ionic-team/ionic/issues/23525)) ([e30b17c](https://github.com/ionic-team/ionic/commit/e30b17c5bbd1af6936a8d7a98d1f7a115073e029)), closes [#22662](https://github.com/ionic-team/ionic/issues/22662)
* **vue:** output commonjs format for node environments ([#22766](https://github.com/ionic-team/ionic/issues/22766)) ([7ecae2e](https://github.com/ionic-team/ionic/commit/7ecae2e4cb5d0eebc6041a8a7a5acc156132c2e1))
* **vue:** overlays function properly when used via controller or template ([#22155](https://github.com/ionic-team/ionic/issues/22155)) ([fe5fadf](https://github.com/ionic-team/ionic/commit/fe5fadf19cd63087311959c549e7e7c55261b459)), closes [#22090](https://github.com/ionic-team/ionic/issues/22090)
* **vue:** pages now render in correct outlet when using multiple nested outlets ([#22301](https://github.com/ionic-team/ionic/issues/22301)) ([52f655c](https://github.com/ionic-team/ionic/commit/52f655c9d40988cac36f88c88f24195b3f64c431)), closes [#22286](https://github.com/ionic-team/ionic/issues/22286)
* **vue:** pass in correct route to props function ([#22605](https://github.com/ionic-team/ionic/issues/22605)) ([01afdc4](https://github.com/ionic-team/ionic/commit/01afdc42e5b1598d4d15cb51761bbb3eb5d13893)), closes [#22602](https://github.com/ionic-team/ionic/issues/22602)
* **vue:** passing params as props are correctly updated when switching pages ([#23049](https://github.com/ionic-team/ionic/issues/23049)) ([2f54bc1](https://github.com/ionic-team/ionic/commit/2f54bc14699656e6905452a4233d982f83d0001f)), closes [#23043](https://github.com/ionic-team/ionic/issues/23043)
* **vue:** query strings are now correctly handled when navigating back ([#22615](https://github.com/ionic-team/ionic/issues/22615)) ([a94e2a8](https://github.com/ionic-team/ionic/commit/a94e2a87fb759e7b7daed2d0304c1199dbc7afd1)), closes [#22517](https://github.com/ionic-team/ionic/issues/22517)
* **vue:** replacing routes across nested outlets preserves previous route info ([#25171](https://github.com/ionic-team/ionic/issues/25171)) ([7b71607](https://github.com/ionic-team/ionic/commit/7b716076b66fbb5bd4620ea8ba74318bbbc1b7e8)), closes [#25017](https://github.com/ionic-team/ionic/issues/25017)
* **vue:** replacing routes now updates location state correctly ([#24721](https://github.com/ionic-team/ionic/issues/24721)) ([721a461](https://github.com/ionic-team/ionic/commit/721a461073bbd8e7218cd5ce02965d673f5a03e8)), closes [#24432](https://github.com/ionic-team/ionic/issues/24432)
* **vue:** router guards are now fired correctly when written in a component ([#23821](https://github.com/ionic-team/ionic/issues/23821)) ([3c44222](https://github.com/ionic-team/ionic/commit/3c442228ff746165fd823687a2661a24edd08820)), closes [#23820](https://github.com/ionic-team/ionic/issues/23820)
* **vue:** routing history is correctly replaced when overwriting browser history ([#24670](https://github.com/ionic-team/ionic/issues/24670)) ([0b18260](https://github.com/ionic-team/ionic/commit/0b18260da64334d8211c5a0cd806f7416274fc5e)), closes [#23873](https://github.com/ionic-team/ionic/issues/23873)
* **vue:** switching between tabs and going back resolves to correct route ([#25206](https://github.com/ionic-team/ionic/issues/25206)) ([b4ba70e](https://github.com/ionic-team/ionic/commit/b4ba70ea148d4f8fc7475d3de798b485238470c8)), closes [#24303](https://github.com/ionic-team/ionic/issues/24303)
* **vue:** tapping the active tab button now correctly resets the tab stack ([#24935](https://github.com/ionic-team/ionic/issues/24935)) ([4534c8b](https://github.com/ionic-team/ionic/commit/4534c8bc0b2bca7ab6eecd9886243116e9a039b7)), closes [#24934](https://github.com/ionic-team/ionic/issues/24934)
* **vue:** use correct history mode when doing ssr to avoid errors ([#23255](https://github.com/ionic-team/ionic/issues/23255)) ([2e00dab](https://github.com/ionic-team/ionic/commit/2e00dab95d3fefeab92c19cedb046ae2bb10879c)), closes [#23254](https://github.com/ionic-team/ionic/issues/23254)
* **vue:** using refs with v-model now works properly ([#22092](https://github.com/ionic-team/ionic/issues/22092)) ([67fbb3b](https://github.com/ionic-team/ionic/commit/67fbb3b963e2e75284b578777057c0822720fb1e)), closes [#22076](https://github.com/ionic-team/ionic/issues/22076)
* **vue:** using router.go now shows correct view ([#23773](https://github.com/ionic-team/ionic/issues/23773)) ([621f4fa](https://github.com/ionic-team/ionic/commit/621f4faa1ab03137158127a56c7fe0aa1f7ae489)), closes [#22563](https://github.com/ionic-team/ionic/issues/22563)


### Code Refactoring

* **vue:** remove support for child routes nested inside of tabs ([#22919](https://github.com/ionic-team/ionic/issues/22919)) ([75458ac](https://github.com/ionic-team/ionic/commit/75458ac7fb95f56a6ec460f85cf7d7720ce0c070))


### Features

* **vue:** add hardware back button hook ([#22069](https://github.com/ionic-team/ionic/issues/22069)) ([a7f564b](https://github.com/ionic-team/ionic/commit/a7f564b818a6ce5f97d999934d5cca77da1b2c83))
* **vue:** add ionic vue beta ([#22062](https://github.com/ionic-team/ionic/issues/22062)) ([5ffa65f](https://github.com/ionic-team/ionic/commit/5ffa65f84a037f265a89f0b3310552d73125b8cd))
* **vue:** add webHashHistory and memoryHistory options for router ([#22101](https://github.com/ionic-team/ionic/issues/22101)) ([fe2cf22](https://github.com/ionic-team/ionic/commit/fe2cf22f5dab4e13458be0a93d38d346a03f7e3d))
* **vue:** extend useIonRouter hook for programmatic navigation with animation control  ([#23499](https://github.com/ionic-team/ionic/issues/23499)) ([fc9e1b4](https://github.com/ionic-team/ionic/commit/fc9e1b4b361938e5644683c395a565be2de1eab9)), closes [#23450](https://github.com/ionic-team/ionic/issues/23450)
* **vue:** vetur support ([#22403](https://github.com/ionic-team/ionic/issues/22403)) ([e76f79d](https://github.com/ionic-team/ionic/commit/e76f79d0548c97edd193808f5e0a19889cffae5b))


### BREAKING CHANGES

* **vue:** Support for child routes nested inside of tabs has been removed to better conform to Vue Router's best practices. Additional routes should be written as sibling routes with the parent tab as the path prefix.





## [6.1.8](https://github.com/ionic-team/ionic/compare/v6.1.7...v6.1.8) (2022-06-01)

**Note:** Version bump only for package @ionic/vue-router





## [6.1.7](https://github.com/ionic-team/ionic/compare/v6.1.6...v6.1.7) (2022-05-26)


### Bug Fixes

* **vue:** correct views are now unmounted in tabs ([#25270](https://github.com/ionic-team/ionic/issues/25270)) ([5e23fb1](https://github.com/ionic-team/ionic/commit/5e23fb1ce4e5b6e53828bde59268170f604167ba)), closes [#25255](https://github.com/ionic-team/ionic/issues/25255)





## [6.1.6](https://github.com/ionic-team/ionic/compare/v6.1.5...v6.1.6) (2022-05-18)

**Note:** Version bump only for package @ionic/vue-router





## [6.1.5](https://github.com/ionic-team/ionic/compare/v6.1.4...v6.1.5) (2022-05-11)

**Note:** Version bump only for package @ionic/vue-router





## [6.1.4](https://github.com/ionic-team/ionic/compare/v6.1.3...v6.1.4) (2022-05-04)


### Bug Fixes

* **vue:** switching between tabs and going back resolves to correct route ([#25206](https://github.com/ionic-team/ionic/issues/25206)) ([b4ba70e](https://github.com/ionic-team/ionic/commit/b4ba70ea148d4f8fc7475d3de798b485238470c8)), closes [#24303](https://github.com/ionic-team/ionic/issues/24303)





## [6.1.3](https://github.com/ionic-team/ionic/compare/v6.1.2...v6.1.3) (2022-04-27)


### Bug Fixes

* **vue:** replacing routes across nested outlets preserves previous route info ([#25171](https://github.com/ionic-team/ionic/issues/25171)) ([7b71607](https://github.com/ionic-team/ionic/commit/7b716076b66fbb5bd4620ea8ba74318bbbc1b7e8)), closes [#25017](https://github.com/ionic-team/ionic/issues/25017)





## [6.1.2](https://github.com/ionic-team/ionic/compare/v6.1.1...v6.1.2) (2022-04-20)

**Note:** Version bump only for package @ionic/vue-router





## [6.1.1](https://github.com/ionic-team/ionic/compare/v6.1.0...v6.1.1) (2022-04-15)

**Note:** Version bump only for package @ionic/vue-router





# [6.1.0](https://github.com/ionic-team/ionic/compare/v6.0.14...v6.1.0) (2022-04-13)


### Bug Fixes

* **vue:** ensure that only tab pages get added to the tab navigation stack ([#25045](https://github.com/ionic-team/ionic/issues/25045)) ([a0054a7](https://github.com/ionic-team/ionic/commit/a0054a7cbd52def24c18fd2dadfd2e49a42b8980)), closes [#24859](https://github.com/ionic-team/ionic/issues/24859)





## [6.0.16](https://github.com/ionic-team/ionic/compare/v6.0.15...v6.0.16) (2022-04-08)

**Note:** Version bump only for package @ionic/vue-router





## [6.0.15](https://github.com/ionic-team/ionic/compare/v6.0.14...v6.0.15) (2022-04-06)

**Note:** Version bump only for package @ionic/vue-router





## [6.0.14](https://github.com/ionic-team/ionic/compare/v6.0.13...v6.0.14) (2022-03-30)

**Note:** Version bump only for package @ionic/vue-router





## [6.0.13](https://github.com/ionic-team/ionic/compare/v6.0.12...v6.0.13) (2022-03-23)

**Note:** Version bump only for package @ionic/vue-router





## [6.0.12](https://github.com/ionic-team/ionic/compare/v6.0.11...v6.0.12) (2022-03-16)


### Bug Fixes

* **vue:** tapping the active tab button now correctly resets the tab stack ([#24935](https://github.com/ionic-team/ionic/issues/24935)) ([4534c8b](https://github.com/ionic-team/ionic/commit/4534c8bc0b2bca7ab6eecd9886243116e9a039b7)), closes [#24934](https://github.com/ionic-team/ionic/issues/24934)





## [6.0.11](https://github.com/ionic-team/ionic/compare/v6.0.10...v6.0.11) (2022-03-09)

**Note:** Version bump only for package @ionic/vue-router





## [6.0.10](https://github.com/ionic-team/ionic/compare/v6.0.9...v6.0.10) (2022-03-02)

**Note:** Version bump only for package @ionic/vue-router





## [6.0.9](https://github.com/ionic-team/ionic/compare/v6.0.8...v6.0.9) (2022-02-23)

**Note:** Version bump only for package @ionic/vue-router





## [6.0.8](https://github.com/ionic-team/ionic/compare/v6.0.7...v6.0.8) (2022-02-15)

**Note:** Version bump only for package @ionic/vue-router





## [6.0.7](https://github.com/ionic-team/ionic/compare/v6.0.6...v6.0.7) (2022-02-09)

**Note:** Version bump only for package @ionic/vue-router





## [6.0.6](https://github.com/ionic-team/ionic/compare/v6.0.5...v6.0.6) (2022-02-09)


### Bug Fixes

* **vue:** replacing routes now updates location state correctly ([#24721](https://github.com/ionic-team/ionic/issues/24721)) ([721a461](https://github.com/ionic-team/ionic/commit/721a461073bbd8e7218cd5ce02965d673f5a03e8)), closes [#24432](https://github.com/ionic-team/ionic/issues/24432)
* **vue:** routing history is correctly replaced when overwriting browser history ([#24670](https://github.com/ionic-team/ionic/issues/24670)) ([0b18260](https://github.com/ionic-team/ionic/commit/0b18260da64334d8211c5a0cd806f7416274fc5e)), closes [#23873](https://github.com/ionic-team/ionic/issues/23873)





## [6.0.5](https://github.com/ionic-team/ionic/compare/v6.0.4...v6.0.5) (2022-02-02)

**Note:** Version bump only for package @ionic/vue-router





## [6.0.4](https://github.com/ionic-team/ionic/compare/v6.0.3...v6.0.4) (2022-01-26)

**Note:** Version bump only for package @ionic/vue-router





## [6.0.3](https://github.com/ionic-team/ionic/compare/v6.0.2...v6.0.3) (2022-01-19)

**Note:** Version bump only for package @ionic/vue-router





## [6.0.2](https://github.com/ionic-team/ionic/compare/v6.0.1...v6.0.2) (2022-01-11)


### Bug Fixes

* **vue:** correct route is replaced when using router.replace ([#24533](https://github.com/ionic-team/ionic/issues/24533)) ([90458da](https://github.com/ionic-team/ionic/commit/90458da406e2f7a6675be185409ea78595a35128)), closes [#24226](https://github.com/ionic-team/ionic/issues/24226)
