# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [6.1.9-nightly.20220608](https://github.com/ionic-team/ionic/compare/v5.0.0-beta.4...v6.1.9-nightly.20220608) (2022-06-08)


### Bug Fixes

* **accordion-group:** ionChange is now fired properly in vue ([#24063](https://github.com/ionic-team/ionic/issues/24063)) ([61b99d1](https://github.com/ionic-team/ionic/commit/61b99d13bfab5c57617cbcdc7e54e43f88885f66)), closes [#23762](https://github.com/ionic-team/ionic/issues/23762)
* **accordion:** toggle icon now shows up in vue and react ([#23426](https://github.com/ionic-team/ionic/issues/23426)) ([c716617](https://github.com/ionic-team/ionic/commit/c7166179457a8e2c7e1702c5761bc6368dbd156f))
* **all:** improve compatibility with vite ([#25381](https://github.com/ionic-team/ionic/issues/25381)) ([d83bcd2](https://github.com/ionic-team/ionic/commit/d83bcd2b7f9937550008f995ff91517777584373)), closes [#23823](https://github.com/ionic-team/ionic/issues/23823)
* **angular, react,  vue:** overlays no longer throw errors when used inside tests ([#24681](https://github.com/ionic-team/ionic/issues/24681)) ([897ae4a](https://github.com/ionic-team/ionic/commit/897ae4a4546ac0dd811125d5513ef23d133a1589)), closes [#24549](https://github.com/ionic-team/ionic/issues/24549) [#24590](https://github.com/ionic-team/ionic/issues/24590)
* **icon:** update to ionicons 6 to resolve typescript 4.4 errors ([#24185](https://github.com/ionic-team/ionic/issues/24185)) ([118c606](https://github.com/ionic-team/ionic/commit/118c606703f792f830d92f1148882b5daa3f180f))
* **overlays:** overlay interfaces are now exported from framework packages and documented ([#23619](https://github.com/ionic-team/ionic/issues/23619)) ([773bbcb](https://github.com/ionic-team/ionic/commit/773bbcb211d3cf0caf38c25b44e666d98ddfafe5)), closes [#22790](https://github.com/ionic-team/ionic/issues/22790)
* **range:** interfaces are now correctly exported ([#25342](https://github.com/ionic-team/ionic/issues/25342)) ([15f0c06](https://github.com/ionic-team/ionic/commit/15f0c0669f7598386edf487f408462b90ed91a08)), closes [#25341](https://github.com/ionic-team/ionic/issues/25341)
* **react, vue:** correct view now chosen when going back inside tabs ([#23154](https://github.com/ionic-team/ionic/issues/23154)) ([7203190](https://github.com/ionic-team/ionic/commit/72031902347dc279045e2e099f69852a23dd8436)), closes [#23087](https://github.com/ionic-team/ionic/issues/23087) [#23101](https://github.com/ionic-team/ionic/issues/23101)
* **react, vue:** do not show back button when replacing to root page ([#22750](https://github.com/ionic-team/ionic/issues/22750)) ([9e9a372](https://github.com/ionic-team/ionic/commit/9e9a3724979e95f3df1a340be21d16d8664a013c)), closes [#22528](https://github.com/ionic-team/ionic/issues/22528)
* **react, vue:** remove sideeffects to improve treeshaking ([#24313](https://github.com/ionic-team/ionic/issues/24313)) ([13d4418](https://github.com/ionic-team/ionic/commit/13d4418588b98d301b05ebd94e0eac670163a553))
* **react,vue:** backdrop for inline modal/popover overlay ([#24453](https://github.com/ionic-team/ionic/issues/24453)) ([77f8412](https://github.com/ionic-team/ionic/commit/77f8412b746222793cd9d17f12f50d512ab5e886)), closes [#24449](https://github.com/ionic-team/ionic/issues/24449)
* **react:** setupIonicReact no longer crashes in SSR environment ([#24604](https://github.com/ionic-team/ionic/issues/24604)) ([360643d](https://github.com/ionic-team/ionic/commit/360643d96a03b345c83b88c9ff06e9aa254dee81))
* **vue:** account for event name changes in vue 3.0.6+ ([06d4c8e](https://github.com/ionic-team/ionic/commit/06d4c8e6f1897759b9edc921e453944c4c1d1dbf))
* **vue:** account for event name changes in vue 3.0.6+ for overlay components ([#23100](https://github.com/ionic-team/ionic/issues/23100)) ([27318cf](https://github.com/ionic-team/ionic/commit/27318cf58563c4b38d0b7045fb61451f45954a8f))
* **vue:** add missing tabs attribute to router outlet inside ion-tabs ([#22226](https://github.com/ionic-team/ionic/issues/22226)) ([ba4f07e](https://github.com/ionic-team/ionic/commit/ba4f07e270830d3eca67d71051a57ba7c7105f85))
* **vue:** adding non tab button elements inside ion-tab-bar no longer causes errors ([#22643](https://github.com/ionic-team/ionic/issues/22643)) ([61cf0c5](https://github.com/ionic-team/ionic/commit/61cf0c534e45ce09410be6bfb50bdc27b657d1bc)), closes [#22642](https://github.com/ionic-team/ionic/issues/22642)
* **vue:** all ionic vue components can now use router link ([#22743](https://github.com/ionic-team/ionic/issues/22743)) ([3d6ac13](https://github.com/ionic-team/ionic/commit/3d6ac1382e23663a3d010fd253d3c6017d3923e4))
* **vue:** back button now selects correct route when navigating from view multiple times ([#24060](https://github.com/ionic-team/ionic/issues/24060)) ([a09d7d4](https://github.com/ionic-team/ionic/commit/a09d7d4ab6dd0d90204015eaaf232ed190753c56)), closes [#23987](https://github.com/ionic-team/ionic/issues/23987)
* **vue:** canDismiss definition is now exposed ([#25195](https://github.com/ionic-team/ionic/issues/25195)) ([e5e0e24](https://github.com/ionic-team/ionic/commit/e5e0e24f76c15c1a49f759b1a140e337f5393edd))
* **vue:** canGoBack method now works correctly ([#24188](https://github.com/ionic-team/ionic/issues/24188)) ([7c43589](https://github.com/ionic-team/ionic/commit/7c43589b0a486f71ee2ae5a4cdcd73071fcd31b9)), closes [#24109](https://github.com/ionic-team/ionic/issues/24109)
* **vue:** canGoBack param should be optional ([2efab94](https://github.com/ionic-team/ionic/commit/2efab9403533455a1860fba23d3b74c204fda106))
* **vue:** components inside of ion-nav are now unmounted properly ([#23240](https://github.com/ionic-team/ionic/issues/23240)) ([f2f41e2](https://github.com/ionic-team/ionic/commit/f2f41e2af45ba9a36064d33e0b5c1b59da6b74ab)), closes [#23233](https://github.com/ionic-team/ionic/issues/23233)
* **vue:** components now integrate properly with vee-validate ([#23114](https://github.com/ionic-team/ionic/issues/23114)) ([ba51daf](https://github.com/ionic-team/ionic/commit/ba51daf17c4438aea6826882f82a04ebf8d6a5d8)), closes [#22886](https://github.com/ionic-team/ionic/issues/22886)
* **vue:** correct route is replaced when using router.replace ([#24533](https://github.com/ionic-team/ionic/issues/24533)) ([90458da](https://github.com/ionic-team/ionic/commit/90458da406e2f7a6675be185409ea78595a35128)), closes [#24226](https://github.com/ionic-team/ionic/issues/24226)
* **vue:** correct views are now unmounted in tabs ([#25270](https://github.com/ionic-team/ionic/issues/25270)) ([5e23fb1](https://github.com/ionic-team/ionic/commit/5e23fb1ce4e5b6e53828bde59268170f604167ba)), closes [#25255](https://github.com/ionic-team/ionic/issues/25255)
* **vue:** correctly determine leaving view when transitioning to a new instance of a previous page ([#22655](https://github.com/ionic-team/ionic/issues/22655)) ([e3a05bf](https://github.com/ionic-team/ionic/commit/e3a05bfeb55d8eaa38aa08a37859aa4df6ffa2d4)), closes [#22654](https://github.com/ionic-team/ionic/issues/22654) [#22658](https://github.com/ionic-team/ionic/issues/22658)
* **vue:** correctly handle platform specific icons ([#22200](https://github.com/ionic-team/ionic/issues/22200)) ([25d3ea6](https://github.com/ionic-team/ionic/commit/25d3ea6b8d78016e9122c4ec02016af33a2041e8)), closes [#19078](https://github.com/ionic-team/ionic/issues/19078)
* **vue:** correctly handle query params ([#22253](https://github.com/ionic-team/ionic/issues/22253)) ([6849dd3](https://github.com/ionic-team/ionic/commit/6849dd3483fb90aac1ff19834390a652c59a74de)), closes [#22229](https://github.com/ionic-team/ionic/issues/22229)
* **vue:** correctly pass route props to components ([#22476](https://github.com/ionic-team/ionic/issues/22476)) ([0956f8b](https://github.com/ionic-team/ionic/commit/0956f8bc5588836996c8c74f98166c347414a312)), closes [#22472](https://github.com/ionic-team/ionic/issues/22472)
* **vue:** correctly remove active state from tab button when navigating away from tab ([#23000](https://github.com/ionic-team/ionic/issues/23000)) ([a2763af](https://github.com/ionic-team/ionic/commit/a2763afe8e1fe1dc0decdbcb757a03bc5038045e)), closes [#22597](https://github.com/ionic-team/ionic/issues/22597)
* **vue:** correctly remove old view when replacing route ([#22566](https://github.com/ionic-team/ionic/issues/22566)) ([4f4f31b](https://github.com/ionic-team/ionic/commit/4f4f31b65e48294c3130ff24ae00b1a2aa1f9d31)), closes [#22492](https://github.com/ionic-team/ionic/issues/22492)
* **vue:** correctly render child pages in tabs ([#22141](https://github.com/ionic-team/ionic/issues/22141)) ([7e449a1](https://github.com/ionic-team/ionic/commit/7e449a1ca62956d36b92c32289e5db7a3acb6718))
* **vue:** correctly show ion-back-button when going back ([#22260](https://github.com/ionic-team/ionic/issues/22260)) ([39d2530](https://github.com/ionic-team/ionic/commit/39d2530427b1cd86975fc95ab2c8da9f4b0b27b3)), closes [#22217](https://github.com/ionic-team/ionic/issues/22217)
* **vue:** correctly switch tabs after going back ([#22309](https://github.com/ionic-team/ionic/issues/22309)) ([daf6a92](https://github.com/ionic-team/ionic/commit/daf6a92127d36c20f3445f83bd7bd3e739bb1b27)), closes [#22307](https://github.com/ionic-team/ionic/issues/22307)
* **vue:** correctly update property values ([#22218](https://github.com/ionic-team/ionic/issues/22218)) ([2527189](https://github.com/ionic-team/ionic/commit/25271897e2a5acd216f4076ab0284bb91023d424)), closes [#22079](https://github.com/ionic-team/ionic/issues/22079)
* **vue:** custom element internal properties are no longer overridden in vue 3.1.0 ([#23738](https://github.com/ionic-team/ionic/issues/23738)) ([ea39c70](https://github.com/ionic-team/ionic/commit/ea39c70b3ec78b2ea5ef64263e8528b543378784)), closes [#23539](https://github.com/ionic-team/ionic/issues/23539)
* **vue:** do not hide page content when using ion-page in non-routing contexts  ([#22302](https://github.com/ionic-team/ionic/issues/22302)) ([fff82d0](https://github.com/ionic-team/ionic/commit/fff82d0bdcd850e7c70947b39d554e88c4cdfd1e)), closes [#22300](https://github.com/ionic-team/ionic/issues/22300)
* **vue:** dynamic tabs are now correct recognized ([#23212](https://github.com/ionic-team/ionic/issues/23212)) ([004885b](https://github.com/ionic-team/ionic/commit/004885bfd4446487e6386876c868532a2795347f)), closes [#22847](https://github.com/ionic-team/ionic/issues/22847)
* **vue:** ensure dynamic classes are synced with internal Ionic component classes ([#22096](https://github.com/ionic-team/ionic/issues/22096)) ([9cb22be](https://github.com/ionic-team/ionic/commit/9cb22be91a232c395780f7ceb50c3e9ae28e7dc2)), closes [#22051](https://github.com/ionic-team/ionic/issues/22051)
* **vue:** ensure that only tab pages get added to the tab navigation stack ([#25045](https://github.com/ionic-team/ionic/issues/25045)) ([a0054a7](https://github.com/ionic-team/ionic/commit/a0054a7cbd52def24c18fd2dadfd2e49a42b8980)), closes [#24859](https://github.com/ionic-team/ionic/issues/24859)
* **vue:** ensure v-model value is properly synced before ionChange event ([#22749](https://github.com/ionic-team/ionic/issues/22749)) ([e1d6627](https://github.com/ionic-team/ionic/commit/e1d6627bf0ef1f47f980db1573c6b2a3d16d7677)), closes [#22610](https://github.com/ionic-team/ionic/issues/22610)
* **vue:** ensure view is updated correctly when replacing a route outside of a nav guard ([#22429](https://github.com/ionic-team/ionic/issues/22429)) ([5a4d0c0](https://github.com/ionic-team/ionic/commit/5a4d0c0217ce93f98364bdd4d8d163679f82a6b3)), closes [#22412](https://github.com/ionic-team/ionic/issues/22412)
* **vue:** ensure webpack does not eliminate core css ([#23465](https://github.com/ionic-team/ionic/issues/23465)) ([ee3a00f](https://github.com/ionic-team/ionic/commit/ee3a00fde61b4d1d3168d34b3d23bb97dd154154))
* **vue:** going back to a tabs outlet no loger causes classList error ([#24665](https://github.com/ionic-team/ionic/issues/24665)) ([6d7b144](https://github.com/ionic-team/ionic/commit/6d7b1444b63cca03158789fcd41b33a527f6abac)), closes [#24654](https://github.com/ionic-team/ionic/issues/24654)
* **vue:** going back with query params now goes to correct view ([#22350](https://github.com/ionic-team/ionic/issues/22350)) ([561a4ac](https://github.com/ionic-team/ionic/commit/561a4ac535432873860c3d0a4ac60481929d9089)), closes [#22324](https://github.com/ionic-team/ionic/issues/22324)
* **vue:** hide layout shift on ion-page components ([#22254](https://github.com/ionic-team/ionic/issues/22254)) ([2bad1bb](https://github.com/ionic-team/ionic/commit/2bad1bb82e0fa3fe9e3db54403565d210f636120)), closes [#22052](https://github.com/ionic-team/ionic/issues/22052)
* **vue:** improve accuracy of ion-page dev warning ([#23677](https://github.com/ionic-team/ionic/issues/23677)) ([fb260a9](https://github.com/ionic-team/ionic/commit/fb260a9e09e6f3912b30ef2ebf581d3216483fea)), closes [#23675](https://github.com/ionic-team/ionic/issues/23675)
* **vue:** improve compatibility with route guards ([#22371](https://github.com/ionic-team/ionic/issues/22371)) ([31f9bc8](https://github.com/ionic-team/ionic/commit/31f9bc81d6d0fa81f9abe20172bb606651a2d75d)), closes [#22344](https://github.com/ionic-team/ionic/issues/22344)
* **vue:** improve handling of parameterized urls ([#22360](https://github.com/ionic-team/ionic/issues/22360)) ([6fad0fe](https://github.com/ionic-team/ionic/commit/6fad0fe42814cde1126e6df264b99c069849c87a)), closes [#22359](https://github.com/ionic-team/ionic/issues/22359)
* **vue:** improve path matching when going back ([#22275](https://github.com/ionic-team/ionic/issues/22275)) ([b06ae16](https://github.com/ionic-team/ionic/commit/b06ae165912cbab811fe4a3c35b4e2b3fe0b425b)), closes [#22258](https://github.com/ionic-team/ionic/issues/22258)
* **vue:** improve path matching with tabs ([#22807](https://github.com/ionic-team/ionic/issues/22807)) ([2a3ce9a](https://github.com/ionic-team/ionic/commit/2a3ce9a74e85111a2f1f470b9d8bfe2cda793ca5)), closes [#22519](https://github.com/ionic-team/ionic/issues/22519)
* **vue:** improve query params handling in tabs ([#24355](https://github.com/ionic-team/ionic/issues/24355)) ([6309d5d](https://github.com/ionic-team/ionic/commit/6309d5ddbaa7da5e37eda4e19866baf380069578)), closes [#24353](https://github.com/ionic-team/ionic/issues/24353)
* **vue:** improve swipe to go back reliability ([#22288](https://github.com/ionic-team/ionic/issues/22288)) ([c74fd41](https://github.com/ionic-team/ionic/commit/c74fd4147b57e6b11c22dffdf6355568a763f30a)), closes [#22237](https://github.com/ionic-team/ionic/issues/22237)
* **vue:** improve v-model binding sync between vue wrappers and web components ([#22745](https://github.com/ionic-team/ionic/issues/22745)) ([64719f4](https://github.com/ionic-team/ionic/commit/64719f49f979c0296a01827d3c02599a48ba93a6)), closes [#22731](https://github.com/ionic-team/ionic/issues/22731)
* **vue:** improve v-model integration for Vue 3.1.0+ ([#23420](https://github.com/ionic-team/ionic/issues/23420)) ([f008628](https://github.com/ionic-team/ionic/commit/f0086288512bd7f7d1929d79bfd8bf702efc732e))
* **vue:** ion-nav now handles Vue components properly ([#22197](https://github.com/ionic-team/ionic/issues/22197)) ([2c6259c](https://github.com/ionic-team/ionic/commit/2c6259c1f6f715d46e32ae4ab6142f448dda631c)), closes [#22184](https://github.com/ionic-team/ionic/issues/22184)
* **vue:** ion-page component is properly shown with HMR ([#22319](https://github.com/ionic-team/ionic/issues/22319)) ([c5ab562](https://github.com/ionic-team/ionic/commit/c5ab562eaa098717407e6b3e8139abd2112246a2))
* **vue:** ion-tab-bar no longer throws undefined error when re-creating tabs ([#22261](https://github.com/ionic-team/ionic/issues/22261)) ([d746561](https://github.com/ionic-team/ionic/commit/d746561ea29e61db2cfb55d2765b5548fd8b5a78)), closes [#22255](https://github.com/ionic-team/ionic/issues/22255)
* **vue:** ionChange events now propagate correctly ([#22872](https://github.com/ionic-team/ionic/issues/22872)) ([ff0f1da](https://github.com/ionic-team/ionic/commit/ff0f1da9f11915b48c4258af7c48c4513785f3fc)), closes [#22870](https://github.com/ionic-team/ionic/issues/22870)
* **vue:** ionic lifecycle hooks now run when using vue 3.2 setup syntax ([#24253](https://github.com/ionic-team/ionic/issues/24253)) ([fb96ab5](https://github.com/ionic-team/ionic/commit/fb96ab5a26d87818a8b64ee82df0020355054183)), closes [#23824](https://github.com/ionic-team/ionic/issues/23824)
* **vue:** IonTabs can now accept IonRouterOutlet ([#23477](https://github.com/ionic-team/ionic/issues/23477)) ([a2a4cff](https://github.com/ionic-team/ionic/commit/a2a4cff3d0d67868f384e1e9eec7cc738e260a27)), closes [#23321](https://github.com/ionic-team/ionic/issues/23321)
* **vue:** lifecycle events are correctly fired in component context ([#22348](https://github.com/ionic-team/ionic/issues/22348)) ([bcef804](https://github.com/ionic-team/ionic/commit/bcef804deac4dea27def475460aff4cdf0d7d2fc)), closes [#22338](https://github.com/ionic-team/ionic/issues/22338)
* **vue:** modal and popover components now correctly pass properties ([#23761](https://github.com/ionic-team/ionic/issues/23761)) ([578b906](https://github.com/ionic-team/ionic/commit/578b9062dd793c8526b80a769d94aa7aad8fe368)), closes [#23698](https://github.com/ionic-team/ionic/issues/23698)
* **vue:** modal, popover, and nav are now created within application context ([#22282](https://github.com/ionic-team/ionic/issues/22282)) ([6026c65](https://github.com/ionic-team/ionic/commit/6026c65b1ae80af0f8604e7a3bcb220153267955)), closes [#22079](https://github.com/ionic-team/ionic/issues/22079)
* **vue:** mount correct views when navigating ([#24056](https://github.com/ionic-team/ionic/issues/24056)) ([24659a5](https://github.com/ionic-team/ionic/commit/24659a527abe0c70df7e8ae6da3dcb4017bf500c)), closes [#23914](https://github.com/ionic-team/ionic/issues/23914)
* **vue:** navigating between parameterized pages now results in page transition ([#23525](https://github.com/ionic-team/ionic/issues/23525)) ([e30b17c](https://github.com/ionic-team/ionic/commit/e30b17c5bbd1af6936a8d7a98d1f7a115073e029)), closes [#22662](https://github.com/ionic-team/ionic/issues/22662)
* **vue:** onBeforeRouteLeave and onBeforeRouteUpdate hooks now fire properly ([#22542](https://github.com/ionic-team/ionic/issues/22542)) ([8002114](https://github.com/ionic-team/ionic/commit/8002114e720361e60d7a7fe2d15ab88b49a72e1b)), closes [#22540](https://github.com/ionic-team/ionic/issues/22540)
* **vue:** output commonjs format for node environments ([#22766](https://github.com/ionic-team/ionic/issues/22766)) ([7ecae2e](https://github.com/ionic-team/ionic/commit/7ecae2e4cb5d0eebc6041a8a7a5acc156132c2e1))
* **vue:** overlay events can now be listened for without the "on" prefix, deprecated "on" prefix event listeners ([#23227](https://github.com/ionic-team/ionic/issues/23227)) ([dab927d](https://github.com/ionic-team/ionic/commit/dab927d2901658f4040c1d1aa6c777497d8714c8))
* **vue:** overlays function properly when used via controller or template ([#22155](https://github.com/ionic-team/ionic/issues/22155)) ([fe5fadf](https://github.com/ionic-team/ionic/commit/fe5fadf19cd63087311959c549e7e7c55261b459)), closes [#22090](https://github.com/ionic-team/ionic/issues/22090)
* **vue:** pages now render in correct outlet when using multiple nested outlets ([#22301](https://github.com/ionic-team/ionic/issues/22301)) ([52f655c](https://github.com/ionic-team/ionic/commit/52f655c9d40988cac36f88c88f24195b3f64c431)), closes [#22286](https://github.com/ionic-team/ionic/issues/22286)
* **vue:** pass in correct route to props function ([#22605](https://github.com/ionic-team/ionic/issues/22605)) ([01afdc4](https://github.com/ionic-team/ionic/commit/01afdc42e5b1598d4d15cb51761bbb3eb5d13893)), closes [#22602](https://github.com/ionic-team/ionic/issues/22602)
* **vue:** pass props to component when using modal and popover controller ([#22198](https://github.com/ionic-team/ionic/issues/22198)) ([e84f804](https://github.com/ionic-team/ionic/commit/e84f80493cb9e2c17e6bc5f3e68582eaf643f2cf)), closes [#22189](https://github.com/ionic-team/ionic/issues/22189)
* **vue:** passing params as props are correctly updated when switching pages ([#23049](https://github.com/ionic-team/ionic/issues/23049)) ([2f54bc1](https://github.com/ionic-team/ionic/commit/2f54bc14699656e6905452a4233d982f83d0001f)), closes [#23043](https://github.com/ionic-team/ionic/issues/23043)
* **vue:** preserve custom classes on IonPage ([#24776](https://github.com/ionic-team/ionic/issues/24776)) ([b401de1](https://github.com/ionic-team/ionic/commit/b401de1ab3385c67cc476ff90971ce131cefcc3f)), closes [#24772](https://github.com/ionic-team/ionic/issues/24772)
* **vue:** prevent race conditions when opening overlays ([#22883](https://github.com/ionic-team/ionic/issues/22883)) ([68a9b80](https://github.com/ionic-team/ionic/commit/68a9b800532f9c0b308a3b74ed18a7068a942301)), closes [#22880](https://github.com/ionic-team/ionic/issues/22880)
* **vue:** pushing a non-tabs page inside of tabs no longer renders it inside of the tabs outlet ([#22112](https://github.com/ionic-team/ionic/issues/22112)) ([6ac6810](https://github.com/ionic-team/ionic/commit/6ac6810148182a829348e8cac2e3b722448dad98)), closes [#22066](https://github.com/ionic-team/ionic/issues/22066)
* **vue:** replacing routes across nested outlets preserves previous route info ([#25171](https://github.com/ionic-team/ionic/issues/25171)) ([7b71607](https://github.com/ionic-team/ionic/commit/7b716076b66fbb5bd4620ea8ba74318bbbc1b7e8)), closes [#25017](https://github.com/ionic-team/ionic/issues/25017)
* **vue:** replacing routes now updates location state correctly ([#24721](https://github.com/ionic-team/ionic/issues/24721)) ([721a461](https://github.com/ionic-team/ionic/commit/721a461073bbd8e7218cd5ce02965d673f5a03e8)), closes [#24432](https://github.com/ionic-team/ionic/issues/24432)
* **vue:** router guards are now fired correctly when written in a component ([#23821](https://github.com/ionic-team/ionic/issues/23821)) ([3c44222](https://github.com/ionic-team/ionic/commit/3c442228ff746165fd823687a2661a24edd08820)), closes [#23820](https://github.com/ionic-team/ionic/issues/23820)
* **vue:** routing history is correctly replaced when overwriting browser history ([#24670](https://github.com/ionic-team/ionic/issues/24670)) ([0b18260](https://github.com/ionic-team/ionic/commit/0b18260da64334d8211c5a0cd806f7416274fc5e)), closes [#23873](https://github.com/ionic-team/ionic/issues/23873)
* **vue:** strongly typed controller methods ([#24388](https://github.com/ionic-team/ionic/issues/24388)) ([a5d56b3](https://github.com/ionic-team/ionic/commit/a5d56b3d5a0a64fd4c62f4beab69a3a1681c0b70)), closes [#24387](https://github.com/ionic-team/ionic/issues/24387)
* **vue:** swipe back gesture is properly disabled when swipeBackEnabled config is false ([#22568](https://github.com/ionic-team/ionic/issues/22568)) ([9d04c12](https://github.com/ionic-team/ionic/commit/9d04c127e817676983940b034a4c7efc92fdfbc6)), closes [#22567](https://github.com/ionic-team/ionic/issues/22567)
* **vue:** switching between tabs and going back resolves to correct route ([#25206](https://github.com/ionic-team/ionic/issues/25206)) ([b4ba70e](https://github.com/ionic-team/ionic/commit/b4ba70ea148d4f8fc7475d3de798b485238470c8)), closes [#24303](https://github.com/ionic-team/ionic/issues/24303)
* **vue:** switching between tabs preserves query string ([#24297](https://github.com/ionic-team/ionic/issues/24297)) ([047d3c7](https://github.com/ionic-team/ionic/commit/047d3c77729db08e4fd84f426f6c5c2af0eacc52)), closes [#23699](https://github.com/ionic-team/ionic/issues/23699)
* **vue:** tab bar now works with slot="top" ([#22461](https://github.com/ionic-team/ionic/issues/22461)) ([e17c822](https://github.com/ionic-team/ionic/commit/e17c822bfbc2a876226738b77a4c95c02e0b5953)), closes [#22456](https://github.com/ionic-team/ionic/issues/22456)
* **vue:** tabs correctly fire lifecycle events ([#22479](https://github.com/ionic-team/ionic/issues/22479)) ([cdc2fb6](https://github.com/ionic-team/ionic/commit/cdc2fb652fe5aa149eaa751a77fb506ac1f64195)), closes [#22466](https://github.com/ionic-team/ionic/issues/22466)
* **vue:** tabs no longer get unmounted when navigating back to a tabs context ([#24337](https://github.com/ionic-team/ionic/issues/24337)) ([bf8e436](https://github.com/ionic-team/ionic/commit/bf8e436ee3f7441ebbc7eaf53ec8d04545dab476)), closes [#24332](https://github.com/ionic-team/ionic/issues/24332)
* **vue:** tabs warning about user-provided router outlet change is now correctly logged ([#23724](https://github.com/ionic-team/ionic/issues/23724)) ([4a64e97](https://github.com/ionic-team/ionic/commit/4a64e97a3e390e365101bbb477acad0ddc4671ff)), closes [#23719](https://github.com/ionic-team/ionic/issues/23719)
* **vue:** tapping the active tab button now correctly resets the tab stack ([#24935](https://github.com/ionic-team/ionic/issues/24935)) ([4534c8b](https://github.com/ionic-team/ionic/commit/4534c8bc0b2bca7ab6eecd9886243116e9a039b7)), closes [#24934](https://github.com/ionic-team/ionic/issues/24934)
* **vue:** testing a routerLink-capable component no longer warns of missing router dependency ([#22532](https://github.com/ionic-team/ionic/issues/22532)) ([4e23aad](https://github.com/ionic-team/ionic/commit/4e23aad3d911188e4a2706545463a81332c00ce9)), closes [#22506](https://github.com/ionic-team/ionic/issues/22506)
* **vue:** update props when navigating to new parameterized route ([#23189](https://github.com/ionic-team/ionic/issues/23189)) ([35c8802](https://github.com/ionic-team/ionic/commit/35c8802c22c1f4bf213a01e1c28398ad62d1b7ac))
* **vue:** using refs with v-model now works properly ([#22092](https://github.com/ionic-team/ionic/issues/22092)) ([67fbb3b](https://github.com/ionic-team/ionic/commit/67fbb3b963e2e75284b578777057c0822720fb1e)), closes [#22076](https://github.com/ionic-team/ionic/issues/22076)
* **vue:** using router.go now shows correct view ([#23773](https://github.com/ionic-team/ionic/issues/23773)) ([621f4fa](https://github.com/ionic-team/ionic/commit/621f4faa1ab03137158127a56c7fe0aa1f7ae489)), closes [#22563](https://github.com/ionic-team/ionic/issues/22563)


### Code Refactoring

* **vue:** drop support for "on" prefixed overlay events and bump minimum required version of vue to 3.0.6 ([#23229](https://github.com/ionic-team/ionic/issues/23229)) ([6fcb3a6](https://github.com/ionic-team/ionic/commit/6fcb3a62b1b12c5ded11179e83854592d4309bdf))
* **vue:** remove support for child routes nested inside of tabs ([#22919](https://github.com/ionic-team/ionic/issues/22919)) ([75458ac](https://github.com/ionic-team/ionic/commit/75458ac7fb95f56a6ec460f85cf7d7720ce0c070))


### Features

* **accordion-group:** add animated property to disable animations ([#23530](https://github.com/ionic-team/ionic/issues/23530)) ([9a60dd0](https://github.com/ionic-team/ionic/commit/9a60dd0ea7c55acf0fdd1161433e5b4ed40778f2))
* **accordion:** add accordion and accordion-group components ([#22865](https://github.com/ionic-team/ionic/issues/22865)) ([073883a](https://github.com/ionic-team/ionic/commit/073883a0987149e9f6258ca43c46f5ed4bce0dc5)), closes [#17094](https://github.com/ionic-team/ionic/issues/17094)
* **alert, toast:** pass arbitrary HTML attributes to host element ([#23891](https://github.com/ionic-team/ionic/issues/23891)) ([73a1daf](https://github.com/ionic-team/ionic/commit/73a1daf0aaf6ffe8c7871619f2aec5f6fca1321a)), closes [#23825](https://github.com/ionic-team/ionic/issues/23825)
* **all:** add CustomEvents types to components that emit events ([#23956](https://github.com/ionic-team/ionic/issues/23956)) ([8708095](https://github.com/ionic-team/ionic/commit/87080951112a409893a4bac2def1deca06642b16)), closes [#22925](https://github.com/ionic-team/ionic/issues/22925)
* **breadcrumbs:** add breadcrumbs component ([#22701](https://github.com/ionic-team/ionic/issues/22701)) ([2f6b1e4](https://github.com/ionic-team/ionic/commit/2f6b1e4eea307c6f14345704e5824378ef079acb)), closes [#22770](https://github.com/ionic-team/ionic/issues/22770)
* **chip:** add disabled property ([#20658](https://github.com/ionic-team/ionic/issues/20658)) ([0a0cbd8](https://github.com/ionic-team/ionic/commit/0a0cbd8f2a505ad2b3d8afb60cb1e940ced52e0d)), closes [#19510](https://github.com/ionic-team/ionic/issues/19510)
* **datetime:** add calendar picker ([#23416](https://github.com/ionic-team/ionic/issues/23416)) ([932d3ca](https://github.com/ionic-team/ionic/commit/932d3ca62f3e3ef08acb065ce6ec46faa3811f96)), closes [#19423](https://github.com/ionic-team/ionic/issues/19423)
* **datetime:** add clear button ([#23920](https://github.com/ionic-team/ionic/issues/23920)) ([18765e7](https://github.com/ionic-team/ionic/commit/18765e7e39b9f205f47f394d26d6ecc4b53e17ef)), closes [#17482](https://github.com/ionic-team/ionic/issues/17482)
* **datetime:** add firstDayOfWeek property ([#23692](https://github.com/ionic-team/ionic/issues/23692)) ([ea348f0](https://github.com/ionic-team/ionic/commit/ea348f005aef7b2fda581a99338139f6fefcda63)), closes [#23556](https://github.com/ionic-team/ionic/issues/23556)
* **datetime:** add hourCycle property ([#23686](https://github.com/ionic-team/ionic/issues/23686)) ([6342fde](https://github.com/ionic-team/ionic/commit/6342fde56c7687703edd212b8383536c8b9a6400)), closes [#23661](https://github.com/ionic-team/ionic/issues/23661)
* **datetime:** add showDefaultTimeLabel property and time-label slot ([#23577](https://github.com/ionic-team/ionic/issues/23577)) ([7ac0109](https://github.com/ionic-team/ionic/commit/7ac010943b2c9ad42a1833153ea16ccffd169b91)), closes [#23555](https://github.com/ionic-team/ionic/issues/23555)
* **datetime:** add size property ([#23649](https://github.com/ionic-team/ionic/issues/23649)) ([321341d](https://github.com/ionic-team/ionic/commit/321341d97dff98b76b69a1efce58923a80e92bc4)), closes [#23518](https://github.com/ionic-team/ionic/issues/23518)
* **datetime:** isDateEnabled to enable/disable specific days  ([#24898](https://github.com/ionic-team/ionic/issues/24898)) ([e932a04](https://github.com/ionic-team/ionic/commit/e932a042237e6f44bf278bcbd895d8569fc17348)), closes [#24209](https://github.com/ionic-team/ionic/issues/24209)
* **header, footer:** add ios fading header style ([#24011](https://github.com/ionic-team/ionic/issues/24011)) ([7ce3959](https://github.com/ionic-team/ionic/commit/7ce3959b66a08e980c7dac3bb7d7df6bf0ae874e))
* **item:** add helper text, error text, counter, shape, and fill mode ([#23354](https://github.com/ionic-team/ionic/issues/23354)) ([faefe97](https://github.com/ionic-team/ionic/commit/faefe97da6a9d5beff1183d10efd0df9c4e3ebd7)), closes [#19619](https://github.com/ionic-team/ionic/issues/19619)
* **item:** counter formatter to customize counter text display ([#24336](https://github.com/ionic-team/ionic/issues/24336)) ([171020e](https://github.com/ionic-team/ionic/commit/171020e9d200ccfdef0f01c427b295bb50dd1fef)), closes [#24327](https://github.com/ionic-team/ionic/issues/24327)
* **modal:** modals can now be used inline ([#23341](https://github.com/ionic-team/ionic/issues/23341)) ([3be1c3d](https://github.com/ionic-team/ionic/commit/3be1c3dcd73e6039a89b19b409e63877cda37f6e)), closes [#20117](https://github.com/ionic-team/ionic/issues/20117) [#20263](https://github.com/ionic-team/ionic/issues/20263)
* **platform:** add ability to override platform detection methods ([#23915](https://github.com/ionic-team/ionic/issues/23915)) ([45cabae](https://github.com/ionic-team/ionic/commit/45cabae04bf9236cd069793fbf2ac8f68c372cc3)), closes [#19737](https://github.com/ionic-team/ionic/issues/19737)
* **popover:** popover can now be used inline ([#23231](https://github.com/ionic-team/ionic/issues/23231)) ([308fa1c](https://github.com/ionic-team/ionic/commit/308fa1c0dd054cfc2ea54d2edc99e7a4b549f6f0))
* **range:** add knobMoveStart and knobMoveEnd events ([#25011](https://github.com/ionic-team/ionic/issues/25011)) ([f5cb1f8](https://github.com/ionic-team/ionic/commit/f5cb1f8444ba050042e788f9f9ec7b6309bf1b60))
* **range:** add support for customizing pin format ([#22972](https://github.com/ionic-team/ionic/issues/22972)) ([8f2c4f7](https://github.com/ionic-team/ionic/commit/8f2c4f73db167503cdf60222f42bcaadf905b401))
* **react:** add setupIonicReact function ([#24254](https://github.com/ionic-team/ionic/issues/24254)) ([55db38d](https://github.com/ionic-team/ionic/commit/55db38ddc541c2632c7d3e4e4c9400ff5b5dfe8c)), closes [#24139](https://github.com/ionic-team/ionic/issues/24139)
* **searchbar:** add showClearIcon property ([#22759](https://github.com/ionic-team/ionic/issues/22759)) ([215eb5d](https://github.com/ionic-team/ionic/commit/215eb5d4efbb9ade942dba1687469caf61da21e7)), closes [#22738](https://github.com/ionic-team/ionic/issues/22738)
* **segment:** add keyboard navigation, add selectOnFocus property to control selection follow focus behavior ([#23590](https://github.com/ionic-team/ionic/issues/23590)) ([b6c53e5](https://github.com/ionic-team/ionic/commit/b6c53e539b0855fa95b0fe02e5fa74ce403b68b8)), closes [#23520](https://github.com/ionic-team/ionic/issues/23520)
* **segment:** add swipeGesture property to allow for disabling of the swipe gesture ([#22087](https://github.com/ionic-team/ionic/issues/22087)) ([65bc995](https://github.com/ionic-team/ionic/commit/65bc99577c44cce653dafd9937c4d8f9c45fff61)), closes [#22048](https://github.com/ionic-team/ionic/issues/22048)
* **select:** add event for when overlay is dismissed ([#24099](https://github.com/ionic-team/ionic/issues/24099)) ([c1ecf94](https://github.com/ionic-team/ionic/commit/c1ecf94e4e6e320b61606da3c889926f7372ced7))
* **select:** add event for when overlay is dismissed ([#24400](https://github.com/ionic-team/ionic/issues/24400)) ([b835b7c](https://github.com/ionic-team/ionic/commit/b835b7c0c7840f41c54f96743cc0a779ff474ab6))
* **slides:** add IonicSlides module for Swiper migration, deprecate ion-slides ([#23844](https://github.com/ionic-team/ionic/issues/23844)) ([11fda41](https://github.com/ionic-team/ionic/commit/11fda41420343886dabd97096690be38f1c40524)), closes [#23447](https://github.com/ionic-team/ionic/issues/23447)
* **slides:** add IonicSwiper modules, deprecate ion-slides, and add link to migration ([#23447](https://github.com/ionic-team/ionic/issues/23447)) ([623c84a](https://github.com/ionic-team/ionic/commit/623c84ab082668a996c654e18ffc9768f68b85dd))
* **slides:** add support for Swiper 7 ([#24190](https://github.com/ionic-team/ionic/issues/24190)) ([d0b6130](https://github.com/ionic-team/ionic/commit/d0b61307c6b7ff1589646c43f989260b59db1473))
* **vue:** add composition API ionic lifecycle hooks ([#22970](https://github.com/ionic-team/ionic/issues/22970)) ([dd1c8db](https://github.com/ionic-team/ionic/commit/dd1c8dbf3b20fbd423f70c96846d9c366d90e7c5)), closes [#22769](https://github.com/ionic-team/ionic/issues/22769)
* **vue:** add custom elements bundle ([#23458](https://github.com/ionic-team/ionic/issues/23458)) ([dc48a9f](https://github.com/ionic-team/ionic/commit/dc48a9f1a2dff8a2d644112bbe1df8b0b6811848))
* **vue:** add hardware back button hook ([#22069](https://github.com/ionic-team/ionic/issues/22069)) ([a7f564b](https://github.com/ionic-team/ionic/commit/a7f564b818a6ce5f97d999934d5cca77da1b2c83))
* **vue:** add hook to access Ionic Vue router ([#22072](https://github.com/ionic-team/ionic/issues/22072)) ([3d34b68](https://github.com/ionic-team/ionic/commit/3d34b68fbd25b724b6f89c01642788d325f6e909))
* **vue:** add ionic vue beta ([#22062](https://github.com/ionic-team/ionic/issues/22062)) ([5ffa65f](https://github.com/ionic-team/ionic/commit/5ffa65f84a037f265a89f0b3310552d73125b8cd))
* **vue:** add keyboard hook ([#22145](https://github.com/ionic-team/ionic/issues/22145)) ([b76bfa3](https://github.com/ionic-team/ionic/commit/b76bfa36c207ab18450d874cb876803aace58bea))
* **vue:** composition api lifecycle methods ([#22241](https://github.com/ionic-team/ionic/issues/22241)) ([f5b0299](https://github.com/ionic-team/ionic/commit/f5b0299729c2c639e432612e62fb7eaa189ca969))
* **vue:** extend useIonRouter hook for programmatic navigation with animation control  ([#23499](https://github.com/ionic-team/ionic/issues/23499)) ([fc9e1b4](https://github.com/ionic-team/ionic/commit/fc9e1b4b361938e5644683c395a565be2de1eab9)), closes [#23450](https://github.com/ionic-team/ionic/issues/23450)
* **vue:** vetur support ([#22403](https://github.com/ionic-team/ionic/issues/22403)) ([e76f79d](https://github.com/ionic-team/ionic/commit/e76f79d0548c97edd193808f5e0a19889cffae5b))
* **vue:** web-types support ([#22428](https://github.com/ionic-team/ionic/issues/22428)) ([639314a](https://github.com/ionic-team/ionic/commit/639314ab218b65a9a2de6040417b0e1b363e47ef)), closes [#19522](https://github.com/ionic-team/ionic/issues/19522)


### Performance Improvements

* **various:** don't use lazy-loaded icon names in components ([#24671](https://github.com/ionic-team/ionic/issues/24671)) ([484de50](https://github.com/ionic-team/ionic/commit/484de5074de212dffb4bf4f73bade7acec103fe8))
* **vue:** improve build with smaller bundle sizes ([#22131](https://github.com/ionic-team/ionic/issues/22131)) ([f82bac1](https://github.com/ionic-team/ionic/commit/f82bac17806e87772033b4602285fe0662d190e3))


### BREAKING CHANGES

* **all:** The `RadioChangeEventDetail` interface has been removed in favor of `RadioGroupChangeEventDetail`.
* **datetime:** The `ion-datetime` component has been revamped to use a new calendar style. As a result, some APIs have been removed. See https://github.com/ionic-team/ionic-framework/blob/master/BREAKING.md for more details.
* **popover:** Converted `ion-popover` to use the Shadow DOM.
* **vue:** - Dropped support for prefixed overlay events in favor of non prefixed events (I.e. `@onDidDismiss` becomes `@didDismiss`).
- Minimum required version of Vue is now Vue v3.0.6 or newer.
* **vue:** Support for child routes nested inside of tabs has been removed to better conform to Vue Router's best practices. Additional routes should be written as sibling routes with the parent tab as the path prefix.





## [6.1.8](https://github.com/ionic-team/ionic/compare/v6.1.7...v6.1.8) (2022-06-01)


### Bug Fixes

* **all:** improve compatibility with vite ([#25381](https://github.com/ionic-team/ionic/issues/25381)) ([d83bcd2](https://github.com/ionic-team/ionic/commit/d83bcd2b7f9937550008f995ff91517777584373)), closes [#23823](https://github.com/ionic-team/ionic/issues/23823)





## [6.1.7](https://github.com/ionic-team/ionic/compare/v6.1.6...v6.1.7) (2022-05-26)


### Bug Fixes

* **range:** interfaces are now correctly exported ([#25342](https://github.com/ionic-team/ionic/issues/25342)) ([15f0c06](https://github.com/ionic-team/ionic/commit/15f0c0669f7598386edf487f408462b90ed91a08)), closes [#25341](https://github.com/ionic-team/ionic/issues/25341)
* **vue:** correct views are now unmounted in tabs ([#25270](https://github.com/ionic-team/ionic/issues/25270)) ([5e23fb1](https://github.com/ionic-team/ionic/commit/5e23fb1ce4e5b6e53828bde59268170f604167ba)), closes [#25255](https://github.com/ionic-team/ionic/issues/25255)





## [6.1.6](https://github.com/ionic-team/ionic/compare/v6.1.5...v6.1.6) (2022-05-18)

**Note:** Version bump only for package @ionic/vue





## [6.1.5](https://github.com/ionic-team/ionic/compare/v6.1.4...v6.1.5) (2022-05-11)

**Note:** Version bump only for package @ionic/vue





## [6.1.4](https://github.com/ionic-team/ionic/compare/v6.1.3...v6.1.4) (2022-05-04)


### Bug Fixes

* **vue:** switching between tabs and going back resolves to correct route ([#25206](https://github.com/ionic-team/ionic/issues/25206)) ([b4ba70e](https://github.com/ionic-team/ionic/commit/b4ba70ea148d4f8fc7475d3de798b485238470c8)), closes [#24303](https://github.com/ionic-team/ionic/issues/24303)





## [6.1.3](https://github.com/ionic-team/ionic/compare/v6.1.2...v6.1.3) (2022-04-27)


### Bug Fixes

* **vue:** canDismiss definition is now exposed ([#25195](https://github.com/ionic-team/ionic/issues/25195)) ([e5e0e24](https://github.com/ionic-team/ionic/commit/e5e0e24f76c15c1a49f759b1a140e337f5393edd))
* **vue:** replacing routes across nested outlets preserves previous route info ([#25171](https://github.com/ionic-team/ionic/issues/25171)) ([7b71607](https://github.com/ionic-team/ionic/commit/7b716076b66fbb5bd4620ea8ba74318bbbc1b7e8)), closes [#25017](https://github.com/ionic-team/ionic/issues/25017)





## [6.1.2](https://github.com/ionic-team/ionic/compare/v6.1.1...v6.1.2) (2022-04-20)

**Note:** Version bump only for package @ionic/vue





## [6.1.1](https://github.com/ionic-team/ionic/compare/v6.1.0...v6.1.1) (2022-04-15)

**Note:** Version bump only for package @ionic/vue





# [6.1.0](https://github.com/ionic-team/ionic/compare/v6.0.14...v6.1.0) (2022-04-13)


### Bug Fixes

* **vue:** ensure that only tab pages get added to the tab navigation stack ([#25045](https://github.com/ionic-team/ionic/issues/25045)) ([a0054a7](https://github.com/ionic-team/ionic/commit/a0054a7cbd52def24c18fd2dadfd2e49a42b8980)), closes [#24859](https://github.com/ionic-team/ionic/issues/24859)


### Features

* **datetime:** isDateEnabled to enable/disable specific days  ([#24898](https://github.com/ionic-team/ionic/issues/24898)) ([e932a04](https://github.com/ionic-team/ionic/commit/e932a042237e6f44bf278bcbd895d8569fc17348)), closes [#24209](https://github.com/ionic-team/ionic/issues/24209)
* **item:** counter formatter to customize counter text display ([#24336](https://github.com/ionic-team/ionic/issues/24336)) ([171020e](https://github.com/ionic-team/ionic/commit/171020e9d200ccfdef0f01c427b295bb50dd1fef)), closes [#24327](https://github.com/ionic-team/ionic/issues/24327)
* **range:** add knobMoveStart and knobMoveEnd events ([#25011](https://github.com/ionic-team/ionic/issues/25011)) ([f5cb1f8](https://github.com/ionic-team/ionic/commit/f5cb1f8444ba050042e788f9f9ec7b6309bf1b60))
* **select:** add event for when overlay is dismissed ([#24400](https://github.com/ionic-team/ionic/issues/24400)) ([b835b7c](https://github.com/ionic-team/ionic/commit/b835b7c0c7840f41c54f96743cc0a779ff474ab6))





## [6.0.16](https://github.com/ionic-team/ionic/compare/v6.0.15...v6.0.16) (2022-04-08)

**Note:** Version bump only for package @ionic/vue





## [6.0.15](https://github.com/ionic-team/ionic/compare/v6.0.14...v6.0.15) (2022-04-06)

**Note:** Version bump only for package @ionic/vue





## [6.0.14](https://github.com/ionic-team/ionic/compare/v6.0.13...v6.0.14) (2022-03-30)

**Note:** Version bump only for package @ionic/vue





## [6.0.13](https://github.com/ionic-team/ionic/compare/v6.0.12...v6.0.13) (2022-03-23)

**Note:** Version bump only for package @ionic/vue





## [6.0.12](https://github.com/ionic-team/ionic/compare/v6.0.11...v6.0.12) (2022-03-16)


### Bug Fixes

* **vue:** tapping the active tab button now correctly resets the tab stack ([#24935](https://github.com/ionic-team/ionic/issues/24935)) ([4534c8b](https://github.com/ionic-team/ionic/commit/4534c8bc0b2bca7ab6eecd9886243116e9a039b7)), closes [#24934](https://github.com/ionic-team/ionic/issues/24934)





## [6.0.11](https://github.com/ionic-team/ionic/compare/v6.0.10...v6.0.11) (2022-03-09)

**Note:** Version bump only for package @ionic/vue





## [6.0.10](https://github.com/ionic-team/ionic/compare/v6.0.9...v6.0.10) (2022-03-02)

**Note:** Version bump only for package @ionic/vue





## [6.0.9](https://github.com/ionic-team/ionic/compare/v6.0.8...v6.0.9) (2022-02-23)

**Note:** Version bump only for package @ionic/vue





## [6.0.8](https://github.com/ionic-team/ionic/compare/v6.0.7...v6.0.8) (2022-02-15)


### Bug Fixes

* **vue:** preserve custom classes on IonPage ([#24776](https://github.com/ionic-team/ionic/issues/24776)) ([b401de1](https://github.com/ionic-team/ionic/commit/b401de1ab3385c67cc476ff90971ce131cefcc3f)), closes [#24772](https://github.com/ionic-team/ionic/issues/24772)





## [6.0.7](https://github.com/ionic-team/ionic/compare/v6.0.6...v6.0.7) (2022-02-09)

**Note:** Version bump only for package @ionic/vue





## [6.0.6](https://github.com/ionic-team/ionic/compare/v6.0.5...v6.0.6) (2022-02-09)


### Bug Fixes

* **angular, react,  vue:** overlays no longer throw errors when used inside tests ([#24681](https://github.com/ionic-team/ionic/issues/24681)) ([897ae4a](https://github.com/ionic-team/ionic/commit/897ae4a4546ac0dd811125d5513ef23d133a1589)), closes [#24549](https://github.com/ionic-team/ionic/issues/24549) [#24590](https://github.com/ionic-team/ionic/issues/24590)
* **vue:** replacing routes now updates location state correctly ([#24721](https://github.com/ionic-team/ionic/issues/24721)) ([721a461](https://github.com/ionic-team/ionic/commit/721a461073bbd8e7218cd5ce02965d673f5a03e8)), closes [#24432](https://github.com/ionic-team/ionic/issues/24432)
* **vue:** routing history is correctly replaced when overwriting browser history ([#24670](https://github.com/ionic-team/ionic/issues/24670)) ([0b18260](https://github.com/ionic-team/ionic/commit/0b18260da64334d8211c5a0cd806f7416274fc5e)), closes [#23873](https://github.com/ionic-team/ionic/issues/23873)





## [6.0.5](https://github.com/ionic-team/ionic/compare/v6.0.4...v6.0.5) (2022-02-02)


### Bug Fixes

* **vue:** going back to a tabs outlet no loger causes classList error ([#24665](https://github.com/ionic-team/ionic/issues/24665)) ([6d7b144](https://github.com/ionic-team/ionic/commit/6d7b1444b63cca03158789fcd41b33a527f6abac)), closes [#24654](https://github.com/ionic-team/ionic/issues/24654)


### Performance Improvements

* **various:** don't use lazy-loaded icon names in components ([#24671](https://github.com/ionic-team/ionic/issues/24671)) ([484de50](https://github.com/ionic-team/ionic/commit/484de5074de212dffb4bf4f73bade7acec103fe8))





## [6.0.4](https://github.com/ionic-team/ionic/compare/v6.0.3...v6.0.4) (2022-01-26)


### Bug Fixes

* **react:** setupIonicReact no longer crashes in SSR environment ([#24604](https://github.com/ionic-team/ionic/issues/24604)) ([360643d](https://github.com/ionic-team/ionic/commit/360643d96a03b345c83b88c9ff06e9aa254dee81))





## [6.0.3](https://github.com/ionic-team/ionic/compare/v6.0.2...v6.0.3) (2022-01-19)

**Note:** Version bump only for package @ionic/vue





## [6.0.2](https://github.com/ionic-team/ionic/compare/v6.0.1...v6.0.2) (2022-01-11)


### Bug Fixes

* **react,vue:** backdrop for inline modal/popover overlay ([#24453](https://github.com/ionic-team/ionic/issues/24453)) ([77f8412](https://github.com/ionic-team/ionic/commit/77f8412b746222793cd9d17f12f50d512ab5e886)), closes [#24449](https://github.com/ionic-team/ionic/issues/24449)
* **vue:** correct route is replaced when using router.replace ([#24533](https://github.com/ionic-team/ionic/issues/24533)) ([90458da](https://github.com/ionic-team/ionic/commit/90458da406e2f7a6675be185409ea78595a35128)), closes [#24226](https://github.com/ionic-team/ionic/issues/24226)
