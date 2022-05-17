# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [6.1.6-nightly.20220517](https://github.com/ionic-team/ionic/compare/v5.5.2...v6.1.6-nightly.20220517) (2022-05-17)


### Bug Fixes

* **react, vue:** correct view now chosen when going back inside tabs ([#23154](https://github.com/ionic-team/ionic/issues/23154)) ([7203190](https://github.com/ionic-team/ionic/commit/72031902347dc279045e2e099f69852a23dd8436)), closes [#23087](https://github.com/ionic-team/ionic/issues/23087) [#23101](https://github.com/ionic-team/ionic/issues/23101)
* **react, vue:** do not show back button when replacing to root page ([#22750](https://github.com/ionic-team/ionic/issues/22750)) ([9e9a372](https://github.com/ionic-team/ionic/commit/9e9a3724979e95f3df1a340be21d16d8664a013c)), closes [#22528](https://github.com/ionic-team/ionic/issues/22528)
* **react, vue:** navigating using ion-back-button now selects correct page ([#22974](https://github.com/ionic-team/ionic/issues/22974)) ([cd8ffd8](https://github.com/ionic-team/ionic/commit/cd8ffd82a03ee69ef4cbd7922544bfc39680def9)), closes [#22830](https://github.com/ionic-team/ionic/issues/22830)
* **react, vue:** tab buttons no longer throw an error if href is undefined ([#22998](https://github.com/ionic-team/ionic/issues/22998)) ([943e3f6](https://github.com/ionic-team/ionic/commit/943e3f6ae37ecc56f21168f057dde77a05e4e144)), closes [#22997](https://github.com/ionic-team/ionic/issues/22997)
* **vue:** back button now selects correct route when navigating from view multiple times ([#24060](https://github.com/ionic-team/ionic/issues/24060)) ([a09d7d4](https://github.com/ionic-team/ionic/commit/a09d7d4ab6dd0d90204015eaaf232ed190753c56)), closes [#23987](https://github.com/ionic-team/ionic/issues/23987)
* **vue:** canGoBack method now works correctly ([#24188](https://github.com/ionic-team/ionic/issues/24188)) ([7c43589](https://github.com/ionic-team/ionic/commit/7c43589b0a486f71ee2ae5a4cdcd73071fcd31b9)), closes [#24109](https://github.com/ionic-team/ionic/issues/24109)
* **vue:** correct route is replaced when using router.replace ([#24533](https://github.com/ionic-team/ionic/issues/24533)) ([90458da](https://github.com/ionic-team/ionic/commit/90458da406e2f7a6675be185409ea78595a35128)), closes [#24226](https://github.com/ionic-team/ionic/issues/24226)
* **vue:** correctly determine leaving view when transitioning to a new instance of a previous page ([#22655](https://github.com/ionic-team/ionic/issues/22655)) ([e3a05bf](https://github.com/ionic-team/ionic/commit/e3a05bfeb55d8eaa38aa08a37859aa4df6ffa2d4)), closes [#22654](https://github.com/ionic-team/ionic/issues/22654) [#22658](https://github.com/ionic-team/ionic/issues/22658)
* **vue:** ensure that only tab pages get added to the tab navigation stack ([#25045](https://github.com/ionic-team/ionic/issues/25045)) ([a0054a7](https://github.com/ionic-team/ionic/commit/a0054a7cbd52def24c18fd2dadfd2e49a42b8980)), closes [#24859](https://github.com/ionic-team/ionic/issues/24859)
* **vue:** improve path matching with tabs ([#22807](https://github.com/ionic-team/ionic/issues/22807)) ([2a3ce9a](https://github.com/ionic-team/ionic/commit/2a3ce9a74e85111a2f1f470b9d8bfe2cda793ca5)), closes [#22519](https://github.com/ionic-team/ionic/issues/22519)
* **vue:** mount correct views when navigating ([#24056](https://github.com/ionic-team/ionic/issues/24056)) ([24659a5](https://github.com/ionic-team/ionic/commit/24659a527abe0c70df7e8ae6da3dcb4017bf500c)), closes [#23914](https://github.com/ionic-team/ionic/issues/23914)
* **vue:** navigating between parameterized pages now results in page transition ([#23525](https://github.com/ionic-team/ionic/issues/23525)) ([e30b17c](https://github.com/ionic-team/ionic/commit/e30b17c5bbd1af6936a8d7a98d1f7a115073e029)), closes [#22662](https://github.com/ionic-team/ionic/issues/22662)
* **vue:** output commonjs format for node environments ([#22766](https://github.com/ionic-team/ionic/issues/22766)) ([7ecae2e](https://github.com/ionic-team/ionic/commit/7ecae2e4cb5d0eebc6041a8a7a5acc156132c2e1))
* **vue:** passing params as props are correctly updated when switching pages ([#23049](https://github.com/ionic-team/ionic/issues/23049)) ([2f54bc1](https://github.com/ionic-team/ionic/commit/2f54bc14699656e6905452a4233d982f83d0001f)), closes [#23043](https://github.com/ionic-team/ionic/issues/23043)
* **vue:** replacing routes across nested outlets preserves previous route info ([#25171](https://github.com/ionic-team/ionic/issues/25171)) ([7b71607](https://github.com/ionic-team/ionic/commit/7b716076b66fbb5bd4620ea8ba74318bbbc1b7e8)), closes [#25017](https://github.com/ionic-team/ionic/issues/25017)
* **vue:** replacing routes now updates location state correctly ([#24721](https://github.com/ionic-team/ionic/issues/24721)) ([721a461](https://github.com/ionic-team/ionic/commit/721a461073bbd8e7218cd5ce02965d673f5a03e8)), closes [#24432](https://github.com/ionic-team/ionic/issues/24432)
* **vue:** router guards are now fired correctly when written in a component ([#23821](https://github.com/ionic-team/ionic/issues/23821)) ([3c44222](https://github.com/ionic-team/ionic/commit/3c442228ff746165fd823687a2661a24edd08820)), closes [#23820](https://github.com/ionic-team/ionic/issues/23820)
* **vue:** routing history is correctly replaced when overwriting browser history ([#24670](https://github.com/ionic-team/ionic/issues/24670)) ([0b18260](https://github.com/ionic-team/ionic/commit/0b18260da64334d8211c5a0cd806f7416274fc5e)), closes [#23873](https://github.com/ionic-team/ionic/issues/23873)
* **vue:** switching between tabs and going back resolves to correct route ([#25206](https://github.com/ionic-team/ionic/issues/25206)) ([b4ba70e](https://github.com/ionic-team/ionic/commit/b4ba70ea148d4f8fc7475d3de798b485238470c8)), closes [#24303](https://github.com/ionic-team/ionic/issues/24303)
* **vue:** tapping the active tab button now correctly resets the tab stack ([#24935](https://github.com/ionic-team/ionic/issues/24935)) ([4534c8b](https://github.com/ionic-team/ionic/commit/4534c8bc0b2bca7ab6eecd9886243116e9a039b7)), closes [#24934](https://github.com/ionic-team/ionic/issues/24934)
* **vue:** use correct history mode when doing ssr to avoid errors ([#23255](https://github.com/ionic-team/ionic/issues/23255)) ([2e00dab](https://github.com/ionic-team/ionic/commit/2e00dab95d3fefeab92c19cedb046ae2bb10879c)), closes [#23254](https://github.com/ionic-team/ionic/issues/23254)
* **vue:** using router.go now shows correct view ([#23773](https://github.com/ionic-team/ionic/issues/23773)) ([621f4fa](https://github.com/ionic-team/ionic/commit/621f4faa1ab03137158127a56c7fe0aa1f7ae489)), closes [#22563](https://github.com/ionic-team/ionic/issues/22563)


### Code Refactoring

* **vue:** remove support for child routes nested inside of tabs ([#22919](https://github.com/ionic-team/ionic/issues/22919)) ([75458ac](https://github.com/ionic-team/ionic/commit/75458ac7fb95f56a6ec460f85cf7d7720ce0c070))


### Features

* **vue:** extend useIonRouter hook for programmatic navigation with animation control  ([#23499](https://github.com/ionic-team/ionic/issues/23499)) ([fc9e1b4](https://github.com/ionic-team/ionic/commit/fc9e1b4b361938e5644683c395a565be2de1eab9)), closes [#23450](https://github.com/ionic-team/ionic/issues/23450)


### BREAKING CHANGES

* **vue:** Support for child routes nested inside of tabs has been removed to better conform to Vue Router's best practices. Additional routes should be written as sibling routes with the parent tab as the path prefix.





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
