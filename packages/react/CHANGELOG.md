# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [6.1.9-nightly.20220608](https://github.com/ionic-team/ionic/compare/v5.0.0-beta.4...v6.1.9-nightly.20220608) (2022-06-08)


### Bug Fixes

* **accordion:** toggle icon now shows up in vue and react ([#23426](https://github.com/ionic-team/ionic/issues/23426)) ([c716617](https://github.com/ionic-team/ionic/commit/c7166179457a8e2c7e1702c5761bc6368dbd156f))
* **all:** improve compatibility with vite ([#25381](https://github.com/ionic-team/ionic/issues/25381)) ([d83bcd2](https://github.com/ionic-team/ionic/commit/d83bcd2b7f9937550008f995ff91517777584373)), closes [#23823](https://github.com/ionic-team/ionic/issues/23823)
* **angular, react,  vue:** overlays no longer throw errors when used inside tests ([#24681](https://github.com/ionic-team/ionic/issues/24681)) ([897ae4a](https://github.com/ionic-team/ionic/commit/897ae4a4546ac0dd811125d5513ef23d133a1589)), closes [#24549](https://github.com/ionic-team/ionic/issues/24549) [#24590](https://github.com/ionic-team/ionic/issues/24590)
* **breadcrumb:** support routerLink on breadcrumb ([#24509](https://github.com/ionic-team/ionic/issues/24509)) ([5bb1414](https://github.com/ionic-team/ionic/commit/5bb1414f7fa04ea07954cb3f68883ee2f162586a)), closes [#24493](https://github.com/ionic-team/ionic/issues/24493)
* **build:** Fixes to dev build for react ([#21684](https://github.com/ionic-team/ionic/issues/21684)) ([a0735b9](https://github.com/ionic-team/ionic/commit/a0735b97bfbc48aa3f955faa8c397e93e25a5ff1))
* **fab:** add close icon to internal icons for react ([#20490](https://github.com/ionic-team/ionic/issues/20490)) ([c4fb314](https://github.com/ionic-team/ionic/commit/c4fb31403eb4704bcf04e6c32bfa46422f08bf4f)), closes [#20489](https://github.com/ionic-team/ionic/issues/20489)
* **icon:** update to ionicons 6 to resolve typescript 4.4 errors ([#24185](https://github.com/ionic-team/ionic/issues/24185)) ([118c606](https://github.com/ionic-team/ionic/commit/118c606703f792f830d92f1148882b5daa3f180f))
* **item:** only add click event listener to items with inputs ([#22352](https://github.com/ionic-team/ionic/issues/22352)) ([9659ad6](https://github.com/ionic-team/ionic/commit/9659ad63349d5123ca2bd2548a43e37d5ee817e7)), closes [#22011](https://github.com/ionic-team/ionic/issues/22011)
* **nav:** insertPages method correctly inserts multiple pages with props ([#21725](https://github.com/ionic-team/ionic/issues/21725)) ([eb592b8](https://github.com/ionic-team/ionic/commit/eb592b8917b8a7412d8c346f41b47d3b79002b95)), closes [#21724](https://github.com/ionic-team/ionic/issues/21724)
* **overlays:** overlay interfaces are now exported from framework packages and documented ([#23619](https://github.com/ionic-team/ionic/issues/23619)) ([773bbcb](https://github.com/ionic-team/ionic/commit/773bbcb211d3cf0caf38c25b44e666d98ddfafe5)), closes [#22790](https://github.com/ionic-team/ionic/issues/22790)
* **range:** interfaces are now correctly exported ([#25342](https://github.com/ionic-team/ionic/issues/25342)) ([15f0c06](https://github.com/ionic-team/ionic/commit/15f0c0669f7598386edf487f408462b90ed91a08)), closes [#25341](https://github.com/ionic-team/ionic/issues/25341)
* **react-router:** remove page transition flicker on outlet mounting ([#24667](https://github.com/ionic-team/ionic/issues/24667)) ([bdb5c42](https://github.com/ionic-team/ionic/commit/bdb5c421d2d1f72c123c254e50c6d31b3c1a8f42)), closes [#24666](https://github.com/ionic-team/ionic/issues/24666)
* **react, vue:** remove sideeffects to improve treeshaking ([#24313](https://github.com/ionic-team/ionic/issues/24313)) ([13d4418](https://github.com/ionic-team/ionic/commit/13d4418588b98d301b05ebd94e0eac670163a553))
* **react,vue:** backdrop for inline modal/popover overlay ([#24453](https://github.com/ionic-team/ionic/issues/24453)) ([77f8412](https://github.com/ionic-team/ionic/commit/77f8412b746222793cd9d17f12f50d512ab5e886)), closes [#24449](https://github.com/ionic-team/ionic/issues/24449)
* **react:** add improved method for not unmounting component until overlay is dismissed ([#22813](https://github.com/ionic-team/ionic/issues/22813)) ([ab1fc8f](https://github.com/ionic-team/ionic/commit/ab1fc8f2311fd252146942c7a947ebc96efd054f)), closes [#22761](https://github.com/ionic-team/ionic/issues/22761)
* **react:** add param types to useIonPopover dismiss function ([#25311](https://github.com/ionic-team/ionic/issues/25311)) ([7111370](https://github.com/ionic-team/ionic/commit/7111370dd787fdec78a1e3368679bc4c73570b98))
* **react:** add SSR check to IonTabs ([#23696](https://github.com/ionic-team/ionic/issues/23696)) ([f2a05be](https://github.com/ionic-team/ionic/commit/f2a05bed1e2a1150e8f1823bfed2d12a219d6ad0)), closes [#23651](https://github.com/ionic-team/ionic/issues/23651)
* **react:** add useRef wrapper to useIonOverlay state to avoid stale references ([#24553](https://github.com/ionic-team/ionic/issues/24553)) ([bce849c](https://github.com/ionic-team/ionic/commit/bce849c5f324522002eff7f8a5e5023150e9201c))
* **react:** adding dynamic class to ion-page no longer hides component ([#22666](https://github.com/ionic-team/ionic/issues/22666)) ([a01bdb8](https://github.com/ionic-team/ionic/commit/a01bdb8c8dfee760721eeb35a8b556954f3b5b13)), closes [#22631](https://github.com/ionic-team/ionic/issues/22631)
* **react:** adding missing overlay component events, fixes [#19923](https://github.com/ionic-team/ionic/issues/19923) ([#20266](https://github.com/ionic-team/ionic/issues/20266)) ([9b2680d](https://github.com/ionic-team/ionic/commit/9b2680d40deeca4fafb52c8ca0e93728b092b857))
* **react:** android hardware button should invoke browser back ([36939e1](https://github.com/ionic-team/ionic/commit/36939e10ae0b8ac9a9275ee06d8e0d345de7c64f))
* **react:** building app for production now works correctly with vite ([#24515](https://github.com/ionic-team/ionic/issues/24515)) ([32fad3d](https://github.com/ionic-team/ionic/commit/32fad3d02cb6b012a772de03eafe3e3a6b1300e0)), closes [#24229](https://github.com/ionic-team/ionic/issues/24229)
* **react:** callback refs now work correctly with ionic components ([#23152](https://github.com/ionic-team/ionic/issues/23152)) ([0dd189e](https://github.com/ionic-team/ionic/commit/0dd189e2c05012659894a4c15cd3a9d407fe0a63)), closes [#23153](https://github.com/ionic-team/ionic/issues/23153)
* **react:** do not unmount overlay inner component until overlay is dismissed ([#22763](https://github.com/ionic-team/ionic/issues/22763)) ([14e8441](https://github.com/ionic-team/ionic/commit/14e8441706c230da4669afaaf0028aaeaf4dbe0e)), closes [#22761](https://github.com/ionic-team/ionic/issues/22761)
* **react:** Don't render overlay children if isOpen is false, fixes [#20225](https://github.com/ionic-team/ionic/issues/20225) ([#20226](https://github.com/ionic-team/ionic/issues/20226)) ([9a8057c](https://github.com/ionic-team/ionic/commit/9a8057cdf28a863673e6c20127672655a15e29a8))
* **react:** eliminate use of deprecated `findDOMNode`, resolves [#20972](https://github.com/ionic-team/ionic/issues/20972) ([5275332](https://github.com/ionic-team/ionic/commit/5275332e43694f3ee8738a1726c0d202b16c3052))
* **react:** ensure inline modal content is visible ([#23968](https://github.com/ionic-team/ionic/issues/23968)) ([285a371](https://github.com/ionic-team/ionic/commit/285a371101e714e74d6df68701cbee9dfe23605e))
* **react:** export accordion and accordion group components ([#23497](https://github.com/ionic-team/ionic/issues/23497)) ([a664d42](https://github.com/ionic-team/ionic/commit/a664d4268dea8e84ab9e3b150043ac8f87fb53c7))
* **react:** export correct animation types ([#21950](https://github.com/ionic-team/ionic/issues/21950)) ([36e4bf7](https://github.com/ionic-team/ionic/commit/36e4bf7dd76e396f910d28445566b5503cc84c8c))
* **react:** export proper types of animations and gestures ([#20311](https://github.com/ionic-team/ionic/issues/20311)) ([0034088](https://github.com/ionic-team/ionic/commit/00340885fb031d3dbc7c458fddeed9d28a2deda4))
* **react:** expose correct type for CreateAnimation ([#20775](https://github.com/ionic-team/ionic/issues/20775)) ([0897c3f](https://github.com/ionic-team/ionic/commit/0897c3f9c2591442b3f80d28a25ec4471da3c9d7)), closes [#20771](https://github.com/ionic-team/ionic/issues/20771)
* **react:** fix regression on IonTabsContext not working properly ([#21751](https://github.com/ionic-team/ionic/issues/21751)) ([1351b2e](https://github.com/ionic-team/ionic/commit/1351b2eafcc87065ce3f153c164d7a279a172833))
* **react:** fix to regression in overlay hooks dimiss method ([#24038](https://github.com/ionic-team/ionic/issues/24038)) ([655631d](https://github.com/ionic-team/ionic/commit/655631ddf059ce58066d5384d0ae186d7abc09a9)), closes [#24030](https://github.com/ionic-team/ionic/issues/24030)
* **react:** fixes swipe to go back regression ([#21791](https://github.com/ionic-team/ionic/issues/21791)) ([a15cd01](https://github.com/ionic-team/ionic/commit/a15cd01bc39a93e8fcd638d75662858bd97873fc))
* **react:** fixing type of icon in ToastOptions, ActionSheetOptions, fixes [#20100](https://github.com/ionic-team/ionic/issues/20100) ([432887b](https://github.com/ionic-team/ionic/commit/432887b410b1e209e7fcdf93f4ff9d661b2c21a9))
* **react:** fixng ion-router-outlet ref regresssion ([#21786](https://github.com/ionic-team/ionic/issues/21786)) ([f4a08b7](https://github.com/ionic-team/ionic/commit/f4a08b7ed4a8d5dbacea72aa60040e4d8464f886))
* **react:** icons with MD set should work in browser ([#20463](https://github.com/ionic-team/ionic/issues/20463)) ([82670fe](https://github.com/ionic-team/ionic/commit/82670fe4d0592451cbc243b3008beb3f8f483c30))
* **react:** improve component compatibility with preact ([#24132](https://github.com/ionic-team/ionic/issues/24132)) ([15fc293](https://github.com/ionic-team/ionic/commit/15fc293d75aa21426616459c2596b46e2d460f49)), closes [#23516](https://github.com/ionic-team/ionic/issues/23516)
* **react:** improve view matching logic ([#22569](https://github.com/ionic-team/ionic/issues/22569)) ([f891f66](https://github.com/ionic-team/ionic/commit/f891f667082d2deb5f1b5f0f27af46e46ed1ca0f))
* **react:** IonRouterOutlet now respects animated={false} prop ([#22905](https://github.com/ionic-team/ionic/issues/22905)) ([da1b7a0](https://github.com/ionic-team/ionic/commit/da1b7a0e7a9a5e6a9120dc4d5459c97d8bca5390)), closes [#22903](https://github.com/ionic-team/ionic/issues/22903)
* **react:** IonTabBar properly extends IonicReactProps ([#21009](https://github.com/ionic-team/ionic/issues/21009)) ([102a842](https://github.com/ionic-team/ionic/commit/102a842bd2a967c04a3cf42ed4e0811929bd4d99)), closes [#21006](https://github.com/ionic-team/ionic/issues/21006)
* **react:** IonTabButton will call custom onClick handlers ([#25313](https://github.com/ionic-team/ionic/issues/25313)) ([6034418](https://github.com/ionic-team/ionic/commit/6034418b33c32fdd682c470eaf61b9fcbe86c4bb)), closes [#22511](https://github.com/ionic-team/ionic/issues/22511)
* **react:** Keep a hold of previous routes when doing a redirect, closes [#22053](https://github.com/ionic-team/ionic/issues/22053) ([74af3cb](https://github.com/ionic-team/ionic/commit/74af3cb50b089a6bd60d515158e03b18b86455b8))
* **react:** modal now mounts child component independently of other modals ([#23903](https://github.com/ionic-team/ionic/issues/23903)) ([1e13429](https://github.com/ionic-team/ionic/commit/1e13429731c1d4b5200af7f5ca20aff1f3078bfe)), closes [#23904](https://github.com/ionic-team/ionic/issues/23904)
* **react:** nested router outlets will not reanimate entered views ([#24672](https://github.com/ionic-team/ionic/issues/24672)) ([43aa6c1](https://github.com/ionic-team/ionic/commit/43aa6c11f42fd5cf455c50419d5f5fbb327b2901)), closes [#24107](https://github.com/ionic-team/ionic/issues/24107)
* **react:** onIonTabsWillChange and onIonTabsDidChange event handlers are now properly bound to IonTabs ([#22233](https://github.com/ionic-team/ionic/issues/22233)) ([b064fde](https://github.com/ionic-team/ionic/commit/b064fdebef14018b77242b791914d5bb10863d39))
* **react:** only pass tab event props from IonTabs to IonTabBar if defined ([#23024](https://github.com/ionic-team/ionic/issues/23024)) ([f94e618](https://github.com/ionic-team/ionic/commit/f94e618a7b307b143eb39c061dc9e6b80e11f862)), closes [#23023](https://github.com/ionic-team/ionic/issues/23023)
* **react:** overlay hooks memorised properly to prevent re-renders ([#24010](https://github.com/ionic-team/ionic/issues/24010)) ([2c97712](https://github.com/ionic-team/ionic/commit/2c977126012ae0231d4e4fa63cc76a528bde699b)), closes [#23741](https://github.com/ionic-team/ionic/issues/23741)
* **react:** overlays now correctly unmount any child components after dismissing ([#23149](https://github.com/ionic-team/ionic/issues/23149)) ([dee6eb3](https://github.com/ionic-team/ionic/commit/dee6eb30df370047bbc872b00ab6d801dd11fa81)), closes [#23140](https://github.com/ionic-team/ionic/issues/23140)
* **react:** overlays shown with useIonModal and useIonPopover no longer render outside of main react tree ([f3e492c](https://github.com/ionic-team/ionic/commit/f3e492c897c8cda2b98050156f130654f4d7014a)), closes [#23516](https://github.com/ionic-team/ionic/issues/23516) [#23516](https://github.com/ionic-team/ionic/issues/23516)
* **react:** present and dismiss hooks return promises ([#24299](https://github.com/ionic-team/ionic/issues/24299)) ([4b26fea](https://github.com/ionic-team/ionic/commit/4b26feaa47efed4806aba565a52554db232b99e2))
* **react:** present controller overlays in React 18 ([#25361](https://github.com/ionic-team/ionic/issues/25361)) ([01c40ea](https://github.com/ionic-team/ionic/commit/01c40eae5509f1c150d79269a7a75c05112fa343)), closes [#25247](https://github.com/ionic-team/ionic/issues/25247)
* **react:** prevent errors when dismissing inline popover after containing element is removed ([#24569](https://github.com/ionic-team/ionic/issues/24569)) ([c8a392a](https://github.com/ionic-team/ionic/commit/c8a392aef5fbf25f59a573897d970c41abac04d2))
* **react:** properly check for custom elements to avoid errors in unit tests ([#24156](https://github.com/ionic-team/ionic/issues/24156)) ([8f188ea](https://github.com/ionic-team/ionic/commit/8f188eaae7422c9e81053868b9dd93b4ac738e98)), closes [#24149](https://github.com/ionic-team/ionic/issues/24149)
* **react:** re attach props on update, fixes 20192 ([#20228](https://github.com/ionic-team/ionic/issues/20228)) ([50dcab5](https://github.com/ionic-team/ionic/commit/50dcab5c322ec509541a23aae605d5df6e6ec932))
* **react:** redirect routes should unmount leaving component, fixes [#22022](https://github.com/ionic-team/ionic/issues/22022) ([#22029](https://github.com/ionic-team/ionic/issues/22029)) ([b11e06c](https://github.com/ionic-team/ionic/commit/b11e06cec1d3c28bab9f29185fe2c3a2975b092f))
* **react:** remove hardware back button event listener when NavManager is unmounted ([#23224](https://github.com/ionic-team/ionic/issues/23224)) ([c501da7](https://github.com/ionic-team/ionic/commit/c501da73be879db0fea818c507bae4386a47d42e)), closes [#23170](https://github.com/ionic-team/ionic/issues/23170)
* **react:** removed exporting of ionRenderToString to decrease bundle size, closes [#21917](https://github.com/ionic-team/ionic/issues/21917) ([#21928](https://github.com/ionic-team/ionic/issues/21928)) ([434befe](https://github.com/ionic-team/ionic/commit/434befea5f31aa599ee5b1b7edf29238912c23d9))
* **react:** scrolling to bottom of modal contents ([#24510](https://github.com/ionic-team/ionic/issues/24510)) ([1462cef](https://github.com/ionic-team/ionic/commit/1462cef69225e20582e2f9a0b8fd655ca2066b79)), closes [#24478](https://github.com/ionic-team/ionic/issues/24478)
* **react:** setting a ref should allow other props to be passed in, closes [#22609](https://github.com/ionic-team/ionic/issues/22609) ([31f45cd](https://github.com/ionic-team/ionic/commit/31f45cdcc953b08749d9db08321fa5ec6cbe2532))
* **react:** setting active tab properly on mount, closes [#21830](https://github.com/ionic-team/ionic/issues/21830) ([#21833](https://github.com/ionic-team/ionic/issues/21833)) ([f58424f](https://github.com/ionic-team/ionic/commit/f58424f62596b9eb82bebb8e07c211e1725c025a))
* **react:** setupIonicReact no longer crashes in SSR environment ([#24604](https://github.com/ionic-team/ionic/issues/24604)) ([360643d](https://github.com/ionic-team/ionic/commit/360643d96a03b345c83b88c9ff06e9aa254dee81))
* **react:** supporting ios and md props on icons ([#20170](https://github.com/ionic-team/ionic/issues/20170)) ([d294e67](https://github.com/ionic-team/ionic/commit/d294e67f521712a6ec60bca0f5778b64b03ac04d))
* **react:** treeshake ionic/core bundle ([#24989](https://github.com/ionic-team/ionic/issues/24989)) ([a296ca8](https://github.com/ionic-team/ionic/commit/a296ca875c18ec01bfc57972571e95a6d79f5678)), closes [#24497](https://github.com/ionic-team/ionic/issues/24497)
* **react:** update icon types to be a string as well, fixes [#20229](https://github.com/ionic-team/ionic/issues/20229) ([#20230](https://github.com/ionic-team/ionic/issues/20230)) ([f971f76](https://github.com/ionic-team/ionic/commit/f971f76b4b2d8c149ef25de0ad6a03785c6ad66c))
* **react:** update paths of tab buttons when href changes in ion buttons, fixes [#20321](https://github.com/ionic-team/ionic/issues/20321) ([#20480](https://github.com/ionic-team/ionic/issues/20480)) ([45d03ba](https://github.com/ionic-team/ionic/commit/45d03baf981d0e10eb1fe689908532adef2ba31d))
* **react:** updating icon type and add caret to internal icons ([#20216](https://github.com/ionic-team/ionic/issues/20216)) ([dc78f98](https://github.com/ionic-team/ionic/commit/dc78f981531960791a425b3b1b81d45d5065a263))
* **react:** useIonModal/useIonPopover dismiss accepts data and role ([#25209](https://github.com/ionic-team/ionic/issues/25209)) ([68b2f8b](https://github.com/ionic-team/ionic/commit/68b2f8bfe10946580b996e48c4ec1e2df94b8d49)), closes [#25208](https://github.com/ionic-team/ionic/issues/25208)
* **react:** using autonomous web component for safari support, closes [#21803](https://github.com/ionic-team/ionic/issues/21803) ([bfddb17](https://github.com/ionic-team/ionic/commit/bfddb170659224d0f826762744dfe44a85813d36))
* **reat:** fix tab currentHref when changing tabs, closes [#21834](https://github.com/ionic-team/ionic/issues/21834) ([#21835](https://github.com/ionic-team/ionic/issues/21835)) ([74468ab](https://github.com/ionic-team/ionic/commit/74468ab7972b174ba85bf239306c27080f253a4a))
* **vue:** canDismiss definition is now exposed ([#25195](https://github.com/ionic-team/ionic/issues/25195)) ([e5e0e24](https://github.com/ionic-team/ionic/commit/e5e0e24f76c15c1a49f759b1a140e337f5393edd))


### Features

* **all:** add ability to eject from Ionic sanitizer ([#20457](https://github.com/ionic-team/ionic/issues/20457)) ([fa9ddc9](https://github.com/ionic-team/ionic/commit/fa9ddc91bc9fefc2bb247cfe7511384f77335476)), closes [#18277](https://github.com/ionic-team/ionic/issues/18277)
* **all:** add CustomEvents types to components that emit events ([#23956](https://github.com/ionic-team/ionic/issues/23956)) ([8708095](https://github.com/ionic-team/ionic/commit/87080951112a409893a4bac2def1deca06642b16)), closes [#22925](https://github.com/ionic-team/ionic/issues/22925)
* **breadcrumbs:** add breadcrumbs component ([#22701](https://github.com/ionic-team/ionic/issues/22701)) ([2f6b1e4](https://github.com/ionic-team/ionic/commit/2f6b1e4eea307c6f14345704e5824378ef079acb)), closes [#22770](https://github.com/ionic-team/ionic/issues/22770)
* **modal:** modals can now be used inline ([#23341](https://github.com/ionic-team/ionic/issues/23341)) ([3be1c3d](https://github.com/ionic-team/ionic/commit/3be1c3dcd73e6039a89b19b409e63877cda37f6e)), closes [#20117](https://github.com/ionic-team/ionic/issues/20117) [#20263](https://github.com/ionic-team/ionic/issues/20263)
* **platform:** add ability to override platform detection methods ([#23915](https://github.com/ionic-team/ionic/issues/23915)) ([45cabae](https://github.com/ionic-team/ionic/commit/45cabae04bf9236cd069793fbf2ac8f68c372cc3)), closes [#19737](https://github.com/ionic-team/ionic/issues/19737)
* **popover:** popover can now be used inline ([#23231](https://github.com/ionic-team/ionic/issues/23231)) ([308fa1c](https://github.com/ionic-team/ionic/commit/308fa1c0dd054cfc2ea54d2edc99e7a4b549f6f0))
* **react:** add custom elements bundle ([#23896](https://github.com/ionic-team/ionic/issues/23896)) ([c50d895](https://github.com/ionic-team/ionic/commit/c50d895370a56d0809019dc59fe32ec840b72f03))
* **react:** add Ionic Animations wrapper (experimental) ([#20273](https://github.com/ionic-team/ionic/issues/20273)) ([b59d764](https://github.com/ionic-team/ionic/commit/b59d7647fd6f9a645a4ec0fe9aca526ea5eda4e0))
* **react:** Add IonTabsContext to add some missing element methods, closes [#19935](https://github.com/ionic-team/ionic/issues/19935) ([#21171](https://github.com/ionic-team/ionic/issues/21171)) ([43f9d24](https://github.com/ionic-team/ionic/commit/43f9d24824e4c1b679b350b3db05a6830d98fc0a))
* **react:** add react hooks to control overlay components ([#22484](https://github.com/ionic-team/ionic/issues/22484)) ([b83e009](https://github.com/ionic-team/ionic/commit/b83e00934e794a936c9d3d23d7f94bbe89cedcd5))
* **react:** add setupIonicReact function ([#24254](https://github.com/ionic-team/ionic/issues/24254)) ([55db38d](https://github.com/ionic-team/ionic/commit/55db38ddc541c2632c7d3e4e4c9400ff5b5dfe8c)), closes [#24139](https://github.com/ionic-team/ionic/issues/24139)
* **react:** React Router Enhancements ([#21693](https://github.com/ionic-team/ionic/issues/21693)) ([c171ccb](https://github.com/ionic-team/ionic/commit/c171ccbd37c1ee4b4934758a3a759170ff357cb2))
* **slides:** add IonicSlides module for Swiper migration, deprecate ion-slides ([#23844](https://github.com/ionic-team/ionic/issues/23844)) ([11fda41](https://github.com/ionic-team/ionic/commit/11fda41420343886dabd97096690be38f1c40524)), closes [#23447](https://github.com/ionic-team/ionic/issues/23447)
* **slides:** add IonicSwiper modules, deprecate ion-slides, and add link to migration ([#23447](https://github.com/ionic-team/ionic/issues/23447)) ([623c84a](https://github.com/ionic-team/ionic/commit/623c84ab082668a996c654e18ffc9768f68b85dd))
* **slides:** add support for Swiper 7 ([#24190](https://github.com/ionic-team/ionic/issues/24190)) ([d0b6130](https://github.com/ionic-team/ionic/commit/d0b61307c6b7ff1589646c43f989260b59db1473))


### Performance Improvements

* **various:** don't use lazy-loaded icon names in components ([#24671](https://github.com/ionic-team/ionic/issues/24671)) ([484de50](https://github.com/ionic-team/ionic/commit/484de5074de212dffb4bf4f73bade7acec103fe8))


### BREAKING CHANGES

* **all:** The `RadioChangeEventDetail` interface has been removed in favor of `RadioGroupChangeEventDetail`.
* **popover:** Converted `ion-popover` to use the Shadow DOM.





## [6.1.8](https://github.com/ionic-team/ionic/compare/v6.1.7...v6.1.8) (2022-06-01)


### Bug Fixes

* **all:** improve compatibility with vite ([#25381](https://github.com/ionic-team/ionic/issues/25381)) ([d83bcd2](https://github.com/ionic-team/ionic/commit/d83bcd2b7f9937550008f995ff91517777584373)), closes [#23823](https://github.com/ionic-team/ionic/issues/23823)
* **react:** present controller overlays in React 18 ([#25361](https://github.com/ionic-team/ionic/issues/25361)) ([01c40ea](https://github.com/ionic-team/ionic/commit/01c40eae5509f1c150d79269a7a75c05112fa343)), closes [#25247](https://github.com/ionic-team/ionic/issues/25247)





## [6.1.7](https://github.com/ionic-team/ionic/compare/v6.1.6...v6.1.7) (2022-05-26)


### Bug Fixes

* **range:** interfaces are now correctly exported ([#25342](https://github.com/ionic-team/ionic/issues/25342)) ([15f0c06](https://github.com/ionic-team/ionic/commit/15f0c0669f7598386edf487f408462b90ed91a08)), closes [#25341](https://github.com/ionic-team/ionic/issues/25341)
* **react:** add param types to useIonPopover dismiss function ([#25311](https://github.com/ionic-team/ionic/issues/25311)) ([7111370](https://github.com/ionic-team/ionic/commit/7111370dd787fdec78a1e3368679bc4c73570b98))
* **react:** IonTabButton will call custom onClick handlers ([#25313](https://github.com/ionic-team/ionic/issues/25313)) ([6034418](https://github.com/ionic-team/ionic/commit/6034418b33c32fdd682c470eaf61b9fcbe86c4bb)), closes [#22511](https://github.com/ionic-team/ionic/issues/22511)





## [6.1.6](https://github.com/ionic-team/ionic/compare/v6.1.5...v6.1.6) (2022-05-18)

**Note:** Version bump only for package @ionic/react





## [6.1.5](https://github.com/ionic-team/ionic/compare/v6.1.4...v6.1.5) (2022-05-11)

**Note:** Version bump only for package @ionic/react





## [6.1.4](https://github.com/ionic-team/ionic/compare/v6.1.3...v6.1.4) (2022-05-04)


### Bug Fixes

* **react:** useIonModal/useIonPopover dismiss accepts data and role ([#25209](https://github.com/ionic-team/ionic/issues/25209)) ([68b2f8b](https://github.com/ionic-team/ionic/commit/68b2f8bfe10946580b996e48c4ec1e2df94b8d49)), closes [#25208](https://github.com/ionic-team/ionic/issues/25208)





## [6.1.3](https://github.com/ionic-team/ionic/compare/v6.1.2...v6.1.3) (2022-04-27)


### Bug Fixes

* **vue:** canDismiss definition is now exposed ([#25195](https://github.com/ionic-team/ionic/issues/25195)) ([e5e0e24](https://github.com/ionic-team/ionic/commit/e5e0e24f76c15c1a49f759b1a140e337f5393edd))





## [6.1.2](https://github.com/ionic-team/ionic/compare/v6.1.1...v6.1.2) (2022-04-20)

**Note:** Version bump only for package @ionic/react





## [6.1.1](https://github.com/ionic-team/ionic/compare/v6.1.0...v6.1.1) (2022-04-15)

**Note:** Version bump only for package @ionic/react





# [6.1.0](https://github.com/ionic-team/ionic/compare/v6.0.14...v6.1.0) (2022-04-13)

**Note:** Version bump only for package @ionic/react





## [6.0.16](https://github.com/ionic-team/ionic/compare/v6.0.15...v6.0.16) (2022-04-08)

**Note:** Version bump only for package @ionic/react





## [6.0.15](https://github.com/ionic-team/ionic/compare/v6.0.14...v6.0.15) (2022-04-06)

**Note:** Version bump only for package @ionic/react





## [6.0.14](https://github.com/ionic-team/ionic/compare/v6.0.13...v6.0.14) (2022-03-30)


### Bug Fixes

* **react:** treeshake ionic/core bundle ([#24989](https://github.com/ionic-team/ionic/issues/24989)) ([a296ca8](https://github.com/ionic-team/ionic/commit/a296ca875c18ec01bfc57972571e95a6d79f5678)), closes [#24497](https://github.com/ionic-team/ionic/issues/24497)





## [6.0.13](https://github.com/ionic-team/ionic/compare/v6.0.12...v6.0.13) (2022-03-23)

**Note:** Version bump only for package @ionic/react





## [6.0.12](https://github.com/ionic-team/ionic/compare/v6.0.11...v6.0.12) (2022-03-16)

**Note:** Version bump only for package @ionic/react





## [6.0.11](https://github.com/ionic-team/ionic/compare/v6.0.10...v6.0.11) (2022-03-09)

**Note:** Version bump only for package @ionic/react





## [6.0.10](https://github.com/ionic-team/ionic/compare/v6.0.9...v6.0.10) (2022-03-02)

**Note:** Version bump only for package @ionic/react





## [6.0.9](https://github.com/ionic-team/ionic/compare/v6.0.8...v6.0.9) (2022-02-23)

**Note:** Version bump only for package @ionic/react





## [6.0.8](https://github.com/ionic-team/ionic/compare/v6.0.7...v6.0.8) (2022-02-15)

**Note:** Version bump only for package @ionic/react





## [6.0.7](https://github.com/ionic-team/ionic/compare/v6.0.6...v6.0.7) (2022-02-09)

**Note:** Version bump only for package @ionic/react





## [6.0.6](https://github.com/ionic-team/ionic/compare/v6.0.5...v6.0.6) (2022-02-09)


### Bug Fixes

* **angular, react,  vue:** overlays no longer throw errors when used inside tests ([#24681](https://github.com/ionic-team/ionic/issues/24681)) ([897ae4a](https://github.com/ionic-team/ionic/commit/897ae4a4546ac0dd811125d5513ef23d133a1589)), closes [#24549](https://github.com/ionic-team/ionic/issues/24549) [#24590](https://github.com/ionic-team/ionic/issues/24590)





## [6.0.5](https://github.com/ionic-team/ionic/compare/v6.0.4...v6.0.5) (2022-02-02)


### Bug Fixes

* **react-router:** remove page transition flicker on outlet mounting ([#24667](https://github.com/ionic-team/ionic/issues/24667)) ([bdb5c42](https://github.com/ionic-team/ionic/commit/bdb5c421d2d1f72c123c254e50c6d31b3c1a8f42)), closes [#24666](https://github.com/ionic-team/ionic/issues/24666)
* **react:** nested router outlets will not reanimate entered views ([#24672](https://github.com/ionic-team/ionic/issues/24672)) ([43aa6c1](https://github.com/ionic-team/ionic/commit/43aa6c11f42fd5cf455c50419d5f5fbb327b2901)), closes [#24107](https://github.com/ionic-team/ionic/issues/24107)


### Performance Improvements

* **various:** don't use lazy-loaded icon names in components ([#24671](https://github.com/ionic-team/ionic/issues/24671)) ([484de50](https://github.com/ionic-team/ionic/commit/484de5074de212dffb4bf4f73bade7acec103fe8))





## [6.0.4](https://github.com/ionic-team/ionic/compare/v6.0.3...v6.0.4) (2022-01-26)


### Bug Fixes

* **react:** setupIonicReact no longer crashes in SSR environment ([#24604](https://github.com/ionic-team/ionic/issues/24604)) ([360643d](https://github.com/ionic-team/ionic/commit/360643d96a03b345c83b88c9ff06e9aa254dee81))





## [6.0.3](https://github.com/ionic-team/ionic/compare/v6.0.2...v6.0.3) (2022-01-19)


### Bug Fixes

* **react:** add useRef wrapper to useIonOverlay state to avoid stale references ([#24553](https://github.com/ionic-team/ionic/issues/24553)) ([bce849c](https://github.com/ionic-team/ionic/commit/bce849c5f324522002eff7f8a5e5023150e9201c))
* **react:** prevent errors when dismissing inline popover after containing element is removed ([#24569](https://github.com/ionic-team/ionic/issues/24569)) ([c8a392a](https://github.com/ionic-team/ionic/commit/c8a392aef5fbf25f59a573897d970c41abac04d2))





## [6.0.2](https://github.com/ionic-team/ionic/compare/v6.0.1...v6.0.2) (2022-01-11)


### Bug Fixes

* **breadcrumb:** support routerLink on breadcrumb ([#24509](https://github.com/ionic-team/ionic/issues/24509)) ([5bb1414](https://github.com/ionic-team/ionic/commit/5bb1414f7fa04ea07954cb3f68883ee2f162586a)), closes [#24493](https://github.com/ionic-team/ionic/issues/24493)
* **react,vue:** backdrop for inline modal/popover overlay ([#24453](https://github.com/ionic-team/ionic/issues/24453)) ([77f8412](https://github.com/ionic-team/ionic/commit/77f8412b746222793cd9d17f12f50d512ab5e886)), closes [#24449](https://github.com/ionic-team/ionic/issues/24449)
* **react:** building app for production now works correctly with vite ([#24515](https://github.com/ionic-team/ionic/issues/24515)) ([32fad3d](https://github.com/ionic-team/ionic/commit/32fad3d02cb6b012a772de03eafe3e3a6b1300e0)), closes [#24229](https://github.com/ionic-team/ionic/issues/24229)
* **react:** scrolling to bottom of modal contents ([#24510](https://github.com/ionic-team/ionic/issues/24510)) ([1462cef](https://github.com/ionic-team/ionic/commit/1462cef69225e20582e2f9a0b8fd655ca2066b79)), closes [#24478](https://github.com/ionic-team/ionic/issues/24478)
