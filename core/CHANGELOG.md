# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [6.1.9-nightly.20220608](https://github.com/ionic-team/ionic/compare/v5.0.0-beta.4...v6.1.9-nightly.20220608) (2022-06-08)


### Bug Fixes

* **a11y:** improve support for ids with special characters when getting label element ([#22680](https://github.com/ionic-team/ionic/issues/22680)) ([19d63f6](https://github.com/ionic-team/ionic/commit/19d63f62431ef9d8279f1726dd63fac2f0d4b46b)), closes [#22678](https://github.com/ionic-team/ionic/issues/22678)
* **a11y:** only preventDefault for the onClick event  ([#22573](https://github.com/ionic-team/ionic/issues/22573)) ([0786835](https://github.com/ionic-team/ionic/commit/07868354aaf88deebf7472a5bf0f34d7c823de17))
* **accordion-group:** ionChange is now fired properly in vue ([#24063](https://github.com/ionic-team/ionic/issues/24063)) ([61b99d1](https://github.com/ionic-team/ionic/commit/61b99d13bfab5c57617cbcdc7e54e43f88885f66)), closes [#23762](https://github.com/ionic-team/ionic/issues/23762)
* **accordion-group:** only allow keyboard interaction if header is focused ([#25091](https://github.com/ionic-team/ionic/issues/25091)) ([e1b555f](https://github.com/ionic-team/ionic/commit/e1b555f286956574876924068304fc44a78c027c))
* **accordion:** accordions expand when using binding ([#25322](https://github.com/ionic-team/ionic/issues/25322)) ([61e571e](https://github.com/ionic-team/ionic/commit/61e571e585ed8ad9b0ca2f98f57bb16616413ba6)), closes [#25307](https://github.com/ionic-team/ionic/issues/25307)
* **accordion:** improve functionality with nested accordions ([#24302](https://github.com/ionic-team/ionic/issues/24302)) ([0920797](https://github.com/ionic-team/ionic/commit/0920797612a5ee3aac1c38d8bffe4fd1e80b6987))
* **accordion:** improved reliability of accordion animations ([#23531](https://github.com/ionic-team/ionic/issues/23531)) ([6fbd60b](https://github.com/ionic-team/ionic/commit/6fbd60b0df56dc927226474a1ffa322d979c563e)), closes [#23504](https://github.com/ionic-team/ionic/issues/23504)
* **accordion:** items inside of the content now correct display borders ([#24618](https://github.com/ionic-team/ionic/issues/24618)) ([d3311df](https://github.com/ionic-team/ionic/commit/d3311df96765948d0a395e4ba99fb9117b44adcb)), closes [#24613](https://github.com/ionic-team/ionic/issues/24613)
* **accordion:** value can now be set as string when using multiple is true ([#23581](https://github.com/ionic-team/ionic/issues/23581)) ([8f172de](https://github.com/ionic-team/ionic/commit/8f172de355bc7c910d600ce4d8446b04a6212545)), closes [#23550](https://github.com/ionic-team/ionic/issues/23550)
* **action-sheet, alert:** resolve double click issue when running in iOS mode on chrome ([#21506](https://github.com/ionic-team/ionic/issues/21506)) ([bcccc21](https://github.com/ionic-team/ionic/commit/bcccc217b8833a284a1781e287db5e46043b3548))
* **action-sheet:** allow scrollable action-sheet with many options ([#20145](https://github.com/ionic-team/ionic/issues/20145)) ([53fad97](https://github.com/ionic-team/ionic/commit/53fad978c5a57efe34671db6cbede49c4a5af866)), closes [#17311](https://github.com/ionic-team/ionic/issues/17311)
* **action-sheet:** background includes safe area margin ([#24700](https://github.com/ionic-team/ionic/issues/24700)) ([8c22646](https://github.com/ionic-team/ionic/commit/8c22646d66e2077fc88aaacf350330097733bb9b)), closes [#24699](https://github.com/ionic-team/ionic/issues/24699)
* **action-sheet:** header, subheader, and icon alignment better matches native ios ([#23322](https://github.com/ionic-team/ionic/issues/23322)) ([39315bc](https://github.com/ionic-team/ionic/commit/39315bc857b850347dca386776665e21c9742cad)), closes [#23317](https://github.com/ionic-team/ionic/issues/23317)
* **action-sheet:** safe area is now accounted for in MD mode ([#24176](https://github.com/ionic-team/ionic/issues/24176)) ([642255e](https://github.com/ionic-team/ionic/commit/642255e514fd67238d9bd8ea90781111687c6d03)), closes [#24175](https://github.com/ionic-team/ionic/issues/24175)
* **action-sheet:** show correct cancel button background on dark mode ([#21084](https://github.com/ionic-team/ionic/issues/21084)) ([e442324](https://github.com/ionic-team/ionic/commit/e4423247537cbcda174305ab9fdde4a57c50a88e)), closes [#21082](https://github.com/ionic-team/ionic/issues/21082)
* **action-sheet:** subheader no longer overlaps action sheet buttons ([#23318](https://github.com/ionic-team/ionic/issues/23318)) ([d473a53](https://github.com/ionic-team/ionic/commit/d473a5385108ef5f39d7c9a2b2924e89fec631de)), closes [#23316](https://github.com/ionic-team/ionic/issues/23316)
* add missing vendor prefixes to css ([caa3afa](https://github.com/ionic-team/ionic/commit/caa3afa61313d8821435936f4a7b0f89a37ba304))
* **alert:** AlertButton role now has correct types ([#23791](https://github.com/ionic-team/ionic/issues/23791)) ([864212b](https://github.com/ionic-team/ionic/commit/864212b0f28d33daede5f4767aa03efa37c219ae))
* **alert:** correctly position alert when keyboard is open ([#22425](https://github.com/ionic-team/ionic/issues/22425)) ([9752cd6](https://github.com/ionic-team/ionic/commit/9752cd6371bc4a720e45871161e389e4a9ad8e8f))
* **alert:** made it easier to tell if alert is scrollable in MD mode ([#23976](https://github.com/ionic-team/ionic/issues/23976)) ([a262753](https://github.com/ionic-team/ionic/commit/a26275378f10835343ad8a6cdea50303e6c10a14))
* **alert:** update to follow accessibility guidelines outlined by wai-aria ([#22159](https://github.com/ionic-team/ionic/issues/22159)) ([e9b2cc8](https://github.com/ionic-team/ionic/commit/e9b2cc8453f5e1c45d44397df738f60ea5b32efd)), closes [#21744](https://github.com/ionic-team/ionic/issues/21744)
* **all:** gestures should use a passive listener ([#21038](https://github.com/ionic-team/ionic/issues/21038)) ([dea9248](https://github.com/ionic-team/ionic/commit/dea9248763737164e17678119c775cdfc0e53ccd))
* **all:** import path is now correct when using ionic in a stencil app ([#25123](https://github.com/ionic-team/ionic/issues/25123)) ([1b407ab](https://github.com/ionic-team/ionic/commit/1b407abdf5d8a2a18b6a2b9daca2d58b7b0f782b)), closes [#25122](https://github.com/ionic-team/ionic/issues/25122)
* **all:** improve compatibility with vite ([#25381](https://github.com/ionic-team/ionic/issues/25381)) ([d83bcd2](https://github.com/ionic-team/ionic/commit/d83bcd2b7f9937550008f995ff91517777584373)), closes [#23823](https://github.com/ionic-team/ionic/issues/23823)
* **all:** improve scroll assist reliability for below the fold inputs ([#21206](https://github.com/ionic-team/ionic/issues/21206)) ([7166a29](https://github.com/ionic-team/ionic/commit/7166a290cc1dd728e5bab2f7e39b8d41954e3808))
* **all:** Ionic components that use child Ionic components are now correctly defined ([#24191](https://github.com/ionic-team/ionic/issues/24191)) ([5a2a335](https://github.com/ionic-team/ionic/commit/5a2a335784aab581cda90448193e48f687df6b15)), closes [#23571](https://github.com/ionic-team/ionic/issues/23571) [#24116](https://github.com/ionic-team/ionic/issues/24116) [#24129](https://github.com/ionic-team/ionic/issues/24129)
* **all:** overlay components no longer display outline when focused ([#21226](https://github.com/ionic-team/ionic/issues/21226)) ([bb62023](https://github.com/ionic-team/ionic/commit/bb62023a0cdc5a64e956766c7d1704797fc8c9ae))
* **all:** reflect color property as an attribute for vue ([#23345](https://github.com/ionic-team/ionic/issues/23345)) ([dc430af](https://github.com/ionic-team/ionic/commit/dc430af906c608f948c8d404ad73ae0e0ac36076)), closes [#23323](https://github.com/ionic-team/ionic/issues/23323)
* **all:** ripple effect is no longer added when scrolling ([#25352](https://github.com/ionic-team/ionic/issues/25352)) ([0b275af](https://github.com/ionic-team/ionic/commit/0b275af5ac06f470b4d908b889f513956bf5d868)), closes [#22030](https://github.com/ionic-team/ionic/issues/22030)
* **all:** use proper undefined check when using Haptics plugin ([#21156](https://github.com/ionic-team/ionic/issues/21156)) ([c53b136](https://github.com/ionic-team/ionic/commit/c53b136dbe7ed7fc0fc298593f8b677a66c77910)), closes [#21148](https://github.com/ionic-team/ionic/issues/21148)
* **android:** setting hardwareBackButton: false in config now disabled default webview behavior ([#22555](https://github.com/ionic-team/ionic/issues/22555)) ([dc9faa6](https://github.com/ionic-team/ionic/commit/dc9faa6a0fbebb64c83c107c79cfd486cc0c096a)), closes [#18237](https://github.com/ionic-team/ionic/issues/18237)
* **angular, react,  vue:** overlays no longer throw errors when used inside tests ([#24681](https://github.com/ionic-team/ionic/issues/24681)) ([897ae4a](https://github.com/ionic-team/ionic/commit/897ae4a4546ac0dd811125d5513ef23d133a1589)), closes [#24549](https://github.com/ionic-team/ionic/issues/24549) [#24590](https://github.com/ionic-team/ionic/issues/24590)
* **angular:** fix issue where navAnimation was being incorrectly overridden ([#21508](https://github.com/ionic-team/ionic/issues/21508)) ([e968bd0](https://github.com/ionic-team/ionic/commit/e968bd029a4fb37b4001d96a490c6091a948785a))
* **angular:** inline modals now add .ion-page class correctly ([#24751](https://github.com/ionic-team/ionic/issues/24751)) ([ef46eaf](https://github.com/ionic-team/ionic/commit/ef46eafc9476a85ea3369e542f528d01d3cca0a8)), closes [#24750](https://github.com/ionic-team/ionic/issues/24750)
* **angular:** prevent duplicate event emissions ([#24200](https://github.com/ionic-team/ionic/issues/24200)) ([fc1eae9](https://github.com/ionic-team/ionic/commit/fc1eae982d7493f5b69fb18829f9c796f05a0d47))
* **animation:** add property conversions for CSS Animations ([#20252](https://github.com/ionic-team/ionic/issues/20252)) ([32a7401](https://github.com/ionic-team/ionic/commit/32a7401576a9c91fdee66d2cede06b6a16884d35)), closes [#20251](https://github.com/ionic-team/ionic/issues/20251)
* **animation:** reset all temporary flags when interrupting an animation ([#20627](https://github.com/ionic-team/ionic/issues/20627)) ([0e0e401](https://github.com/ionic-team/ionic/commit/0e0e401d86dabaa1dc804656e4d384154d6fdd05)), closes [#20602](https://github.com/ionic-team/ionic/issues/20602)
* **animation:** typescript interface has correct return value for progress methods ([#23536](https://github.com/ionic-team/ionic/issues/23536)) ([f3d6abb](https://github.com/ionic-team/ionic/commit/f3d6abbc1beeafe3b5e7f473d70d0b8ef4c79bc8))
* **app:** keyboard no longer hides when using contenteditable ([#22857](https://github.com/ionic-team/ionic/issues/22857)) ([b6b2d34](https://github.com/ionic-team/ionic/commit/b6b2d34fd446feb06cf0143946a014d19231a78e)), closes [#22856](https://github.com/ionic-team/ionic/issues/22856)
* **back-button, breadcrumb, item:** flip chevron icons on RTL ([#24705](https://github.com/ionic-team/ionic/issues/24705)) ([a093544](https://github.com/ionic-team/ionic/commit/a093544fdfc438ed03024285b2a35c5f645ea011))
* **back-button:** MD ripple now accounts for --ripple-color ([#23749](https://github.com/ionic-team/ionic/issues/23749)) ([6b18a89](https://github.com/ionic-team/ionic/commit/6b18a89ac2c446082ce7faebe329157eedb13a0e)), closes [#23748](https://github.com/ionic-team/ionic/issues/23748)
* **back-button:** pass aria-label to native element ([#24027](https://github.com/ionic-team/ionic/issues/24027)) ([68a7e43](https://github.com/ionic-team/ionic/commit/68a7e43345a0261fdeed6054198c5a22fbbcb584))
* **back-button:** screen readers correctly announce the back button text ([#21053](https://github.com/ionic-team/ionic/issues/21053)) ([14c226c](https://github.com/ionic-team/ionic/commit/14c226ce75958da14b66821028d6f3a6852d695c)), closes [#21043](https://github.com/ionic-team/ionic/issues/21043)
* **backdrop:** nvda no longer incorrectly announces backdrop ([#22481](https://github.com/ionic-team/ionic/issues/22481)) ([2d878fc](https://github.com/ionic-team/ionic/commit/2d878fc4f6c7a710dbfb722e188e3e402e1672f9)), closes [#22102](https://github.com/ionic-team/ionic/issues/22102)
* **breadcrumb:** support routerLink on breadcrumb ([#24509](https://github.com/ionic-team/ionic/issues/24509)) ([5bb1414](https://github.com/ionic-team/ionic/commit/5bb1414f7fa04ea07954cb3f68883ee2f162586a)), closes [#24493](https://github.com/ionic-team/ionic/issues/24493)
* **build:** add missing es5 output ([62dd16a](https://github.com/ionic-team/ionic/commit/62dd16a5ee3d98cc897422bec8069abfcb84316a))
* **button:** allow any element type to use the "icon-only" slot ([#22168](https://github.com/ionic-team/ionic/issues/22168)) ([c454c84](https://github.com/ionic-team/ionic/commit/c454c84ef46322143467600334a0263d4e7df6cb))
* **button:** allow aria-label to be inherited to inner button ([#22632](https://github.com/ionic-team/ionic/issues/22632)) ([818e387](https://github.com/ionic-team/ionic/commit/818e387fe81ac7026fb374d8865116dadd433c87)), closes [#22629](https://github.com/ionic-team/ionic/issues/22629)
* **button:** allow overflow to be overridden by the CSS variable ([#20738](https://github.com/ionic-team/ionic/issues/20738)) ([7ecde36](https://github.com/ionic-team/ionic/commit/7ecde36f9d31327a45f7b5023ed533edbb9cc709)), closes [#20726](https://github.com/ionic-team/ionic/issues/20726)
* **button:** buttons are now disabled during page transitions ([#23589](https://github.com/ionic-team/ionic/issues/23589)) ([3b803eb](https://github.com/ionic-team/ionic/commit/3b803ebe024be3dbcf814a30a18df51ce23c8880)), closes [#23588](https://github.com/ionic-team/ionic/issues/23588)
* **button:** buttons using fill and color properties now account for hover and focused opacity variables ([#23442](https://github.com/ionic-team/ionic/issues/23442)) ([68c0e71](https://github.com/ionic-team/ionic/commit/68c0e7136d3f8aad8a195a0371104f7dd5fa7060)), closes [#23441](https://github.com/ionic-team/ionic/issues/23441)
* **button:** reduce font size of icon only button in toolbar on iOS ([#20547](https://github.com/ionic-team/ionic/issues/20547)) ([59fa340](https://github.com/ionic-team/ionic/commit/59fa340650840b2abf86bd643350da7064ee9ead))
* **buttons:** use proper button colors based on CSS variables when inside of a toolbar ([#20633](https://github.com/ionic-team/ionic/issues/20633)) ([c1d7bf2](https://github.com/ionic-team/ionic/commit/c1d7bf229d10d0a12f90b6d2730d6d8ac78b48cd))
* **card:** inherit background in inner button ([#20461](https://github.com/ionic-team/ionic/issues/20461)) ([c16de96](https://github.com/ionic-team/ionic/commit/c16de9663329993698c10e4251dbb0b75167701f)), closes [#20458](https://github.com/ionic-team/ionic/issues/20458)
* **card:** remove top padding of content in iOS if under header ([#20223](https://github.com/ionic-team/ionic/issues/20223)) ([9232f16](https://github.com/ionic-team/ionic/commit/9232f16eea8163c1ac0797abd9b6e92da44bacb1))
* **checkbox, radio:** change event interfaces correctly use TypeScript generics for value ([#23044](https://github.com/ionic-team/ionic/issues/23044)) ([8a941fd](https://github.com/ionic-team/ionic/commit/8a941fd24cd138817a2e91c42898878a919538e4))
* **checkbox:** click events on ion-item now fire properly ([#22561](https://github.com/ionic-team/ionic/issues/22561)) ([c45c8d5](https://github.com/ionic-team/ionic/commit/c45c8d5564a20fa5e7254edcaadd7b3ea2f8c61f)), closes [#22557](https://github.com/ionic-team/ionic/issues/22557)
* **checkbox:** use a native input to fix a11y issues with axe and screen readers ([#22402](https://github.com/ionic-team/ionic/issues/22402)) ([7214a84](https://github.com/ionic-team/ionic/commit/7214a8401b709e1353155304cf6e9f97b2b4d294)), closes [#21644](https://github.com/ionic-team/ionic/issues/21644) [#20517](https://github.com/ionic-team/ionic/issues/20517) [#17796](https://github.com/ionic-team/ionic/issues/17796)
* **col:** col no longer errors when running in non-browser environment ([#24603](https://github.com/ionic-team/ionic/issues/24603)) ([af0135c](https://github.com/ionic-team/ionic/commit/af0135ce7dbe737b2df46094fd3dc8a41bdb60ae)), closes [#24446](https://github.com/ionic-team/ionic/issues/24446)
* **components:** fix issues with button states ([#20278](https://github.com/ionic-team/ionic/issues/20278)) ([628db18](https://github.com/ionic-team/ionic/commit/628db18a97293731ecfee8e4d2f0d8c1cf672c96)), closes [#20276](https://github.com/ionic-team/ionic/issues/20276)
* **components:** inherit text indent in all components with text inherit ([#20300](https://github.com/ionic-team/ionic/issues/20300)) ([767b005](https://github.com/ionic-team/ionic/commit/767b005eacf00b640973bfb381de4dcedf083399)), closes [#17786](https://github.com/ionic-team/ionic/issues/17786)
* **content:** add touch-action manipulation for a11y zoom and pan ([#23534](https://github.com/ionic-team/ionic/issues/23534)) ([6ca1780](https://github.com/ionic-team/ionic/commit/6ca17805b8b1ea38d7fc16d091324da16a4193c6)), closes [#22805](https://github.com/ionic-team/ionic/issues/22805)
* **content:** apply --offset-top and --offset-bottom values correctly ([#20790](https://github.com/ionic-team/ionic/issues/20790)) ([2707289](https://github.com/ionic-team/ionic/commit/2707289b36883ae495f86cfb2f2b6c84e090551b)), closes [#20735](https://github.com/ionic-team/ionic/issues/20735)
* **content:** change main child element to div when parent is menu ([#23160](https://github.com/ionic-team/ionic/issues/23160)) ([2d07d82](https://github.com/ionic-team/ionic/commit/2d07d8216af908b181c5e7e438e79a049bb6d8c2))
* **content:** ensure fixed slot renders on top of content in iOS ([#24300](https://github.com/ionic-team/ionic/issues/24300)) ([e41b0e0](https://github.com/ionic-team/ionic/commit/e41b0e0cf2a794972d7f4d8943a0bec3d1e08016))
* **content:** ensure scrollEl is always available in scroll methods ([#24255](https://github.com/ionic-team/ionic/issues/24255)) ([36a096c](https://github.com/ionic-team/ionic/commit/36a096c9b60bd6b3b086f2c966a1cd40dbc54473))
* **content:** only emit scroll events if enabled ([#20401](https://github.com/ionic-team/ionic/issues/20401)) ([fd1b44a](https://github.com/ionic-team/ionic/commit/fd1b44a40b741088e099f6538dd14caa0dc5540c))
* **content:** resolve height inheritance issues ([#20309](https://github.com/ionic-team/ionic/issues/20309)) ([09bef71](https://github.com/ionic-team/ionic/commit/09bef71ccd5a261233180bc19023bc562b905764)), closes [#20305](https://github.com/ionic-team/ionic/issues/20305)
* **content:** scroll-content div now takes up full height of container ([#20194](https://github.com/ionic-team/ionic/issues/20194)) ([9d63b41](https://github.com/ionic-team/ionic/commit/9d63b41a5296688524c64f828f92090d73d6b556)), closes [#20185](https://github.com/ionic-team/ionic/issues/20185)
* **content:** set min-height to allow for sticky headers([#20265](https://github.com/ionic-team/ionic/issues/20265)) ([e613f63](https://github.com/ionic-team/ionic/commit/e613f63590f3d6a4fa4f3a361811224394ba0be2)), closes [#20258](https://github.com/ionic-team/ionic/issues/20258)
* **content:** set overscroll-behavior based on the scroll direction ([#20011](https://github.com/ionic-team/ionic/issues/20011)) ([a3fc77b](https://github.com/ionic-team/ionic/commit/a3fc77be91ead6edc3f07c6127879753a063bd18)), closes [#20010](https://github.com/ionic-team/ionic/issues/20010)
* **core:** @axe-core/playwright should be a devDependency ([#25244](https://github.com/ionic-team/ionic/issues/25244)) ([617ec48](https://github.com/ionic-team/ionic/commit/617ec48265157d1502c443395472c21ebdb2989e)), closes [#25242](https://github.com/ionic-team/ionic/issues/25242)
* **core:** inherit aria attributes on host elements ([#25156](https://github.com/ionic-team/ionic/issues/25156)) ([611832b](https://github.com/ionic-team/ionic/commit/611832b0d51da295c1bf2897972c4e8baf6e23a3)), closes [#20127](https://github.com/ionic-team/ionic/issues/20127)
* **core:** updating type of input value to accept numbers, fixes [#20173](https://github.com/ionic-team/ionic/issues/20173) ([#20267](https://github.com/ionic-team/ionic/issues/20267)) ([3a56228](https://github.com/ionic-team/ionic/commit/3a562282909fddf8cfa65199f9154504f3da0f3a))
* **css:** inline css source in source maps ([#24514](https://github.com/ionic-team/ionic/issues/24514)) ([987d46c](https://github.com/ionic-team/ionic/commit/987d46cfa6e48a932330f04f2e8eb7054b11baf8)), closes [#24441](https://github.com/ionic-team/ionic/issues/24441)
* **datetime, input, textarea:** remove aria-labelledby when there is no adjacent ion-label ([#23211](https://github.com/ionic-team/ionic/issues/23211)) ([a31fb55](https://github.com/ionic-team/ionic/commit/a31fb55bac1ef03e014f3d7f6c22c24eff20feb5))
* **datetime:** account for 30 and 45 minute timezones when getting current date ([#25120](https://github.com/ionic-team/ionic/issues/25120)) ([96b2003](https://github.com/ionic-team/ionic/commit/96b2003b2bd5089d1faafe262e96c7445c5c3349)), closes [#25112](https://github.com/ionic-team/ionic/issues/25112)
* **datetime:** add ionBlur/ionFocus events to whole component ([#23980](https://github.com/ionic-team/ionic/issues/23980)) ([86a77bd](https://github.com/ionic-team/ionic/commit/86a77bd379c6dca57d5feb9694d18afe6d82934d))
* **datetime:** add keyboard year navigation ([#23585](https://github.com/ionic-team/ionic/issues/23585)) ([55bd1f7](https://github.com/ionic-team/ionic/commit/55bd1f749bac01cc691e16283728c42e755cc706)), closes [#21553](https://github.com/ionic-team/ionic/issues/21553) [#18122](https://github.com/ionic-team/ionic/issues/18122)
* **datetime:** add top padding to MD calendar month grid ([#24522](https://github.com/ionic-team/ionic/issues/24522)) ([bd82b5d](https://github.com/ionic-team/ionic/commit/bd82b5dc1d06ba22a5410858802d57735fdcf450)), closes [#24408](https://github.com/ionic-team/ionic/issues/24408)
* **datetime:** arrow navigation respects min/max values ([#25182](https://github.com/ionic-team/ionic/issues/25182)) ([6946e09](https://github.com/ionic-team/ionic/commit/6946e09815da605e37ff8e4d613a14288ea35fb0)), closes [#25073](https://github.com/ionic-team/ionic/issues/25073)
* **datetime:** change now emitted when picker is typed into ([#24018](https://github.com/ionic-team/ionic/issues/24018)) ([0320164](https://github.com/ionic-team/ionic/commit/03201643ba9ae34fa969c1542742d9cd95298c81))
* **datetime:** changing time emits ionChange ([#23463](https://github.com/ionic-team/ionic/issues/23463)) ([b0cce36](https://github.com/ionic-team/ionic/commit/b0cce360c83ac564e053523cc31b32d1deaeda0c))
* **datetime:** clear button is now rendered even if showDefaultButtons is false ([#24075](https://github.com/ionic-team/ionic/issues/24075)) ([e3996cf](https://github.com/ionic-team/ionic/commit/e3996cfbd50f5e9ae54ffcbe2594124e3b9969b0))
* **datetime:** confirm method now uses selected date ([#24827](https://github.com/ionic-team/ionic/issues/24827)) ([c35b898](https://github.com/ionic-team/ionic/commit/c35b898f1dc0fb706446b6971982df48fd72fe6d)), closes [#24823](https://github.com/ionic-team/ionic/issues/24823)
* **datetime:** datetime locale with h23 will respect max time range ([#24610](https://github.com/ionic-team/ionic/issues/24610)) ([5925e76](https://github.com/ionic-team/ionic/commit/5925e7608ef04f8877e4dd8a80b2c8bdc1cfd4bd)), closes [#24588](https://github.com/ionic-team/ionic/issues/24588)
* **datetime:** default sizing preserves shape of datetime ([#24104](https://github.com/ionic-team/ionic/issues/24104)) ([71fab0f](https://github.com/ionic-team/ionic/commit/71fab0fa124254f8cdc3b513627aa7b045993f4e))
* **datetime:** disable intersection observer during month update ([#24713](https://github.com/ionic-team/ionic/issues/24713)) ([aab4d30](https://github.com/ionic-team/ionic/commit/aab4d306f80851bfd8a02a6361e26d60faeaadb4)), closes [#24712](https://github.com/ionic-team/ionic/issues/24712)
* **datetime:** do not reset to am when changing hour and pm is set ([#21997](https://github.com/ionic-team/ionic/issues/21997)) ([8b85fe0](https://github.com/ionic-team/ionic/commit/8b85fe0d9eea39adfdcf790bf00d8ef91d5edbe7)), closes [#19175](https://github.com/ionic-team/ionic/issues/19175) [#19260](https://github.com/ionic-team/ionic/issues/19260) [#20026](https://github.com/ionic-team/ionic/issues/20026) [#16630](https://github.com/ionic-team/ionic/issues/16630)
* **datetime:** do not set ampm when the column doesn't exist ([#22220](https://github.com/ionic-team/ionic/issues/22220)) ([18fb885](https://github.com/ionic-team/ionic/commit/18fb8855e0c45fe65843b33811812c51c74de90f)), closes [#22149](https://github.com/ionic-team/ionic/issues/22149)
* **datetime:** don't update value on confirm call if no date was selected ([#25338](https://github.com/ionic-team/ionic/issues/25338)) ([9e5b10a](https://github.com/ionic-team/ionic/commit/9e5b10a2155c6b9de565931da384e0e49aeca7b7))
* **datetime:** emit ionChange for non-calendar picker presentation ([#25380](https://github.com/ionic-team/ionic/issues/25380)) ([4e6a60b](https://github.com/ionic-team/ionic/commit/4e6a60b6a42287e5091728aecb61f6097e131b83)), closes [#25375](https://github.com/ionic-team/ionic/issues/25375)
* **datetime:** ensure that default month shown is always in bounds ([#25351](https://github.com/ionic-team/ionic/issues/25351)) ([866d452](https://github.com/ionic-team/ionic/commit/866d4528ad1b8ffa65258595d553ea934daa4add)), closes [#25320](https://github.com/ionic-team/ionic/issues/25320)
* **datetime:** ensure year-only values are not affected by timezone when parsing ([#21309](https://github.com/ionic-team/ionic/issues/21309)) ([3937101](https://github.com/ionic-team/ionic/commit/3937101e5c2b181a6b7926eb8386c22b0f887716))
* **datetime:** fix datetime-ready class sometimes not being added due to race condition ([#24385](https://github.com/ionic-team/ionic/issues/24385)) ([e7d0674](https://github.com/ionic-team/ionic/commit/e7d06743ae2e09864510940bf8a97bc312ef1cf8))
* **datetime:** hide footer when month-year picker is open ([#25205](https://github.com/ionic-team/ionic/issues/25205)) ([aa5e1b9](https://github.com/ionic-team/ionic/commit/aa5e1b962150b9ed9629812ec566873784526c83))
* **datetime:** if no default value, don't highlight active day until one is selected ([#25151](https://github.com/ionic-team/ionic/issues/25151)) ([9896939](https://github.com/ionic-team/ionic/commit/98969395abd400cc44d2d3825581a63eb64a56e0))
* **datetime:** improve datetime sizing in modals ([#24762](https://github.com/ionic-team/ionic/issues/24762)) ([b0ac7de](https://github.com/ionic-team/ionic/commit/b0ac7de168c353ba4899cb74a2b38e25fd0cc0f1)), closes [#23992](https://github.com/ionic-team/ionic/issues/23992)
* **datetime:** ionChange is no longer called for out of range dates ([#23940](https://github.com/ionic-team/ionic/issues/23940)) ([ea39c6e](https://github.com/ionic-team/ionic/commit/ea39c6e5b3781ceb4c87277cf4a5e0be9c75bc20)), closes [#23939](https://github.com/ionic-team/ionic/issues/23939)
* **datetime:** keyboard navigation of time picker columns ([#24251](https://github.com/ionic-team/ionic/issues/24251)) ([8bdcd3c](https://github.com/ionic-team/ionic/commit/8bdcd3c6c99d84a0a46b0f08dceca6b6929fd8f8))
* **datetime:** locale inputs are now reactive ([#20826](https://github.com/ionic-team/ionic/issues/20826)) ([a75e8f3](https://github.com/ionic-team/ionic/commit/a75e8f34d608c167f8d429ddbf39e94173204a61)), closes [#20367](https://github.com/ionic-team/ionic/issues/20367)
* **datetime:** max property now works when hour, minute, or second set to 0 ([#20665](https://github.com/ionic-team/ionic/issues/20665)) ([2177461](https://github.com/ionic-team/ionic/commit/21774612d8d70ab7eda3eab0e6e9ac039b5c87d8)), closes [#20652](https://github.com/ionic-team/ionic/issues/20652)
* **datetime:** minutes only filtered when max hour matches current hour ([#24710](https://github.com/ionic-team/ionic/issues/24710)) ([231d6df](https://github.com/ionic-team/ionic/commit/231d6df622c1f5dd9ecdff6fed8f61a4bff332df)), closes [#24702](https://github.com/ionic-team/ionic/issues/24702)
* **datetime:** month and year column order is now locale aware ([#24802](https://github.com/ionic-team/ionic/issues/24802)) ([16647b2](https://github.com/ionic-team/ionic/commit/16647b2c7290389755a4093145788f281c84b7e2)), closes [#24548](https://github.com/ionic-team/ionic/issues/24548)
* **datetime:** month picker no longer gives duplicate months on ios 14 and older ([#24792](https://github.com/ionic-team/ionic/issues/24792)) ([b6d7e1c](https://github.com/ionic-team/ionic/commit/b6d7e1c75740a61dcd02c21692e4d4632fb8df5c)), closes [#24663](https://github.com/ionic-team/ionic/issues/24663)
* **datetime:** navigate to month within min range ([#24759](https://github.com/ionic-team/ionic/issues/24759)) ([7b3838c](https://github.com/ionic-team/ionic/commit/7b3838cc670de7845bb5937d204e86cdba93b6e6)), closes [#24757](https://github.com/ionic-team/ionic/issues/24757)
* **datetime:** persist minutes column on hour change ([#24829](https://github.com/ionic-team/ionic/issues/24829)) ([aacb58a](https://github.com/ionic-team/ionic/commit/aacb58a3224e3cc51c731d0c9aa52f52c9276692)), closes [#24821](https://github.com/ionic-team/ionic/issues/24821)
* **datetime:** presentation time emits ionChange once  ([#24968](https://github.com/ionic-team/ionic/issues/24968)) ([2909b08](https://github.com/ionic-team/ionic/commit/2909b080b7020299a4554c1459b4b190ff739085)), closes [#24967](https://github.com/ionic-team/ionic/issues/24967)
* **datetime:** prevent navigating to disabled months ([#24421](https://github.com/ionic-team/ionic/issues/24421)) ([b40fc46](https://github.com/ionic-team/ionic/commit/b40fc4632efcdc01f1062d9bcec826afff5cf4ea)), closes [#24208](https://github.com/ionic-team/ionic/issues/24208) [#24482](https://github.com/ionic-team/ionic/issues/24482)
* **datetime:** prevent vertical page scroll on interaction ([#23780](https://github.com/ionic-team/ionic/issues/23780)) ([950350a](https://github.com/ionic-team/ionic/commit/950350a948320f889589a0c9d2ec9045637215e5)), closes [#23554](https://github.com/ionic-team/ionic/issues/23554)
* **datetime:** reduce time presentation min height ([#23771](https://github.com/ionic-team/ionic/issues/23771)) ([bc4e826](https://github.com/ionic-team/ionic/commit/bc4e8267aa00e7f162cd01579d8d3adbf3cd7a83)), closes [#23690](https://github.com/ionic-team/ionic/issues/23690)
* **datetime:** reinit behavior on presentation change ([#24828](https://github.com/ionic-team/ionic/issues/24828)) ([d46e1e8](https://github.com/ionic-team/ionic/commit/d46e1e8506ca5095817b421e9edb37d41451e885))
* **datetime:** remove the automatic switching from am to pm ([#22207](https://github.com/ionic-team/ionic/issues/22207)) ([f81d18c](https://github.com/ionic-team/ionic/commit/f81d18c6f9f1bce056afda1cac4cf6d6ace0a7ca)), closes [#18924](https://github.com/ionic-team/ionic/issues/18924) [#22171](https://github.com/ionic-team/ionic/issues/22171) [#22199](https://github.com/ionic-team/ionic/issues/22199)
* **datetime:** remove unneeded combox role ([#21708](https://github.com/ionic-team/ionic/issues/21708)) ([f00ad8a](https://github.com/ionic-team/ionic/commit/f00ad8a8357ccd7fe85631dad0c841f2d4c72487))
* **datetime:** resolve month and year jumping issue on ios ([#24142](https://github.com/ionic-team/ionic/issues/24142)) ([27aef93](https://github.com/ionic-team/ionic/commit/27aef9343cada9a83adec8fe00e8bc3bafa8e049)), closes [#23910](https://github.com/ionic-team/ionic/issues/23910)
* **datetime:** resolve warnings when importing into Stencil app ([#25106](https://github.com/ionic-team/ionic/issues/25106)) ([a61c004](https://github.com/ionic-team/ionic/commit/a61c004fb0c10d9fb0eca0987edf798386251ec2))
* **datetime:** RTL will no longer infinitely scroll ([#24475](https://github.com/ionic-team/ionic/issues/24475)) ([8f00008](https://github.com/ionic-team/ionic/commit/8f000089c2986f292147c7f501f23c8c7d1df457)), closes [#24472](https://github.com/ionic-team/ionic/issues/24472)
* **datetime:** scroll position no longer gets reset when using datetime in overlay ([#23543](https://github.com/ionic-team/ionic/issues/23543)) ([b735b58](https://github.com/ionic-team/ionic/commit/b735b587cda777ac481bb580c883d9734145f31e))
* **datetime:** selecting time now works correctly on firefox ([#23583](https://github.com/ionic-team/ionic/issues/23583)) ([4188964](https://github.com/ionic-team/ionic/commit/4188964dc8da2c46494245b81864ca6e305611f5)), closes [#23545](https://github.com/ionic-team/ionic/issues/23545)
* **datetime:** showing calendar grid no longer causes month to switch on ios 15 ([#24554](https://github.com/ionic-team/ionic/issues/24554)) ([3d20959](https://github.com/ionic-team/ionic/commit/3d2095922147ea3763e977412977edd9586fec5d)), closes [#24405](https://github.com/ionic-team/ionic/issues/24405)
* **datetime:** text color on ios mode now accounts for color contrast ([#23729](https://github.com/ionic-team/ionic/issues/23729)) ([5980db4](https://github.com/ionic-team/ionic/commit/5980db44e5a765d15e681471325e916d566eca8d)), closes [#23723](https://github.com/ionic-team/ionic/issues/23723)
* **datetime:** time picker display matches dynamically set value ([#25010](https://github.com/ionic-team/ionic/issues/25010)) ([11493a0](https://github.com/ionic-team/ionic/commit/11493a086a4e3f2a4e9d3acdf5a9d49e810a5ef0)), closes [#24967](https://github.com/ionic-team/ionic/issues/24967)
* **datetime:** time picker format with hourCycle h23 ([#24476](https://github.com/ionic-team/ionic/issues/24476)) ([a3724e6](https://github.com/ionic-team/ionic/commit/a3724e6a5662c5bc1b724d80540530472827506e)), closes [#24474](https://github.com/ionic-team/ionic/issues/24474)
* **datetime:** time picker now scrolls to correct value ([#24879](https://github.com/ionic-team/ionic/issues/24879)) ([331ce6d](https://github.com/ionic-team/ionic/commit/331ce6d6769900e2aec9e30d35b52cfd40cbb889)), closes [#24878](https://github.com/ionic-team/ionic/issues/24878)
* **datetime:** time picker uses new iOS 15 style ([#23996](https://github.com/ionic-team/ionic/issues/23996)) ([0ab37b5](https://github.com/ionic-team/ionic/commit/0ab37b5061728bd60fd42781645b96add130a79f)), closes [#23768](https://github.com/ionic-team/ionic/issues/23768)
* **datetime:** timepicker popover will position relative to click target ([#24616](https://github.com/ionic-team/ionic/issues/24616)) ([378c632](https://github.com/ionic-team/ionic/commit/378c63264366964e6ea11e1a2ff8791a40f182d4)), closes [#24531](https://github.com/ionic-team/ionic/issues/24531) [#24415](https://github.com/ionic-team/ionic/issues/24415)
* **datetime:** update active calendar display when value changes ([#24244](https://github.com/ionic-team/ionic/issues/24244)) ([ec3bc52](https://github.com/ionic-team/ionic/commit/ec3bc52ff194f1e4db4ce49548c1418c259b8795))
* **datetime:** update active day styling when day is selected ([#24454](https://github.com/ionic-team/ionic/issues/24454)) ([4304391](https://github.com/ionic-team/ionic/commit/430439191dba824c11290d7f8622fea10ced6c40)), closes [#24414](https://github.com/ionic-team/ionic/issues/24414) [#24451](https://github.com/ionic-team/ionic/issues/24451)
* **datetime:** warn when parsing an invalid date value ([#25049](https://github.com/ionic-team/ionic/issues/25049)) ([982dc85](https://github.com/ionic-team/ionic/commit/982dc853befe8ccf54163a0b145e563da06f5dc1))
* **datetime:** wheel picker shows correct column order in rtl ([#24546](https://github.com/ionic-team/ionic/issues/24546)) ([c90ce31](https://github.com/ionic-team/ionic/commit/c90ce311a86ccb7c06b1cde91a4659f6682df04d)), closes [#24378](https://github.com/ionic-team/ionic/issues/24378)
* **datetime:** years displayed now more consistent with v5 datetime, max and min are now accounted for in MD mode ([#23616](https://github.com/ionic-team/ionic/issues/23616)) ([be219a2](https://github.com/ionic-team/ionic/commit/be219a2814800927e6328ff105616713003340b7)), closes [#23615](https://github.com/ionic-team/ionic/issues/23615)
* **display:** remove 1px gap between mutually exclusive breakpoints ([#21276](https://github.com/ionic-team/ionic/issues/21276)) ([703ef5c](https://github.com/ionic-team/ionic/commit/703ef5c99284f1e2b8d63c3af411c945dc756e20)), closes [#20993](https://github.com/ionic-team/ionic/issues/20993) [#20743](https://github.com/ionic-team/ionic/issues/20743)
* **fab:** show close icon on hover, focused, activated ([#20497](https://github.com/ionic-team/ionic/issues/20497)) ([e42c85d](https://github.com/ionic-team/ionic/commit/e42c85d64161b7fac7147325cb6c2ceff990042b))
* **gesture:** onEnd now correctly fires even if the event target was removed from the DOM  ([#23713](https://github.com/ionic-team/ionic/issues/23713)) ([4edb5e2](https://github.com/ionic-team/ionic/commit/4edb5e2fed55c8ea21eae50821d16d351bf3aebf)), closes [#22819](https://github.com/ionic-team/ionic/issues/22819)
* **header:** backdrop filter no longer distorts content with collapsible header ([#20388](https://github.com/ionic-team/ionic/issues/20388)) ([11d3945](https://github.com/ionic-team/ionic/commit/11d39457d56c091e9c41c180391d27464ae748b5)), closes [#20385](https://github.com/ionic-team/ionic/issues/20385)
* **header:** collapsable header should default to using content background ([#20736](https://github.com/ionic-team/ionic/issues/20736)) ([f6c3ba7](https://github.com/ionic-team/ionic/commit/f6c3ba7e5af2af9e32f75306cde7704509e82263)), closes [#20691](https://github.com/ionic-team/ionic/issues/20691)
* **header:** collapsed toolbar is no longer incorrectly shown when using ion-refresher ([#22937](https://github.com/ionic-team/ionic/issues/22937)) ([5300dcc](https://github.com/ionic-team/ionic/commit/5300dcc693caf51a726f8c346cfc9a44474fd3d1)), closes [#22829](https://github.com/ionic-team/ionic/issues/22829)
* **header:** collapsible header now works when navigating quickly ([#20728](https://github.com/ionic-team/ionic/issues/20728)) ([87a2721](https://github.com/ionic-team/ionic/commit/87a27216d011f1d02ac0fc0aeb3ae0400ecfbd8c)), closes [#20725](https://github.com/ionic-team/ionic/issues/20725)
* **header:** do not error on collapsable header on devices that do not support IntersectionObserve ([#21222](https://github.com/ionic-team/ionic/issues/21222)) ([0c13f25](https://github.com/ionic-team/ionic/commit/0c13f25bbb4d4674e76cd19b098900f698e7146e))
* **header:** fix race condition in collapsible header ([#20334](https://github.com/ionic-team/ionic/issues/20334)) ([215d55f](https://github.com/ionic-team/ionic/commit/215d55f1ebeb93988b513c5869faae14d1d51919))
* **header:** header opacity properly resets on collapsible titles ([#20202](https://github.com/ionic-team/ionic/issues/20202)) ([8e11f79](https://github.com/ionic-team/ionic/commit/8e11f79fcca94a9c50ccc7e18e0fe44ef9764b1d))
* **header:** large title transition works on older versions of iOS ([#21339](https://github.com/ionic-team/ionic/issues/21339)) ([2dac12c](https://github.com/ionic-team/ionic/commit/2dac12c577e0c7a5310857389dbda2b2b3dfadd1))
* **header:** role attribute can now be customized ([#23888](https://github.com/ionic-team/ionic/issues/23888)) ([8888e2b](https://github.com/ionic-team/ionic/commit/8888e2bafd76b59f32b932b5d4a6a961b52894d9)), closes [#21327](https://github.com/ionic-team/ionic/issues/21327)
* **icon:** update to ionicons 6 to resolve typescript 4.4 errors ([#24185](https://github.com/ionic-team/ionic/issues/24185)) ([118c606](https://github.com/ionic-team/ionic/commit/118c606703f792f830d92f1148882b5daa3f180f))
* **img:** correctly determine when to load image when scrolling quickly on slower devices ([#23704](https://github.com/ionic-team/ionic/issues/23704)) ([067e621](https://github.com/ionic-team/ionic/commit/067e621bbc3865184ae114b8c91122188c13c860)), closes [#23703](https://github.com/ionic-team/ionic/issues/23703)
* **img:** draggable attribute is now inherited to inner img element ([#24781](https://github.com/ionic-team/ionic/issues/24781)) ([19ac238](https://github.com/ionic-team/ionic/commit/19ac2389eb0843173f51a12de41ac808cd8f0569)), closes [#21325](https://github.com/ionic-team/ionic/issues/21325)
* **img:** use setTimeout fallback on older versions of chrome  ([#21358](https://github.com/ionic-team/ionic/issues/21358)) ([0bf9449](https://github.com/ionic-team/ionic/commit/0bf9449ee1f9b2498e35f61511cb3e018814c6ca))
* **infinite-scroll:** infinite scroll event now fired with custom elements build ([#24043](https://github.com/ionic-team/ionic/issues/24043)) ([8a86cfb](https://github.com/ionic-team/ionic/commit/8a86cfb7050989e914fa85ccc1ea755d73f58c90)), closes [#24034](https://github.com/ionic-team/ionic/issues/24034)
* **input, select, textarea:** change type of placeholder prop to string only ([#23500](https://github.com/ionic-team/ionic/issues/23500)) ([f3ae431](https://github.com/ionic-team/ionic/commit/f3ae4319bb64debab304973856a33e422ac910a1)), closes [#22976](https://github.com/ionic-team/ionic/issues/22976)
* **input:** add aria-label to clear button ([#21538](https://github.com/ionic-team/ionic/issues/21538)) ([d8b377f](https://github.com/ionic-team/ionic/commit/d8b377ffeb88eaae23b33eadeae5c8e54e1bc77c))
* **input:** check for tabindex and pass it properly to native input ([#21170](https://github.com/ionic-team/ionic/issues/21170)) ([dd4cb70](https://github.com/ionic-team/ionic/commit/dd4cb706ffeebc2069645ea03f0e7a96d6b14d43)), closes [#17515](https://github.com/ionic-team/ionic/issues/17515)
* **input:** clear button can now be tabbed to ([#21633](https://github.com/ionic-team/ionic/issues/21633)) ([1dcd9de](https://github.com/ionic-team/ionic/commit/1dcd9de50ae16bfa102e98120a022de5b0287baa))
* **input:** cursor position does not jump to end ([#24736](https://github.com/ionic-team/ionic/issues/24736)) ([4ff9524](https://github.com/ionic-team/ionic/commit/4ff9524e1057aa487069b5982c5f1ecdf51d982b)), closes [#24727](https://github.com/ionic-team/ionic/issues/24727)
* **input:** date type in ion-input now aligns correctly on iOS 15 ([#24213](https://github.com/ionic-team/ionic/issues/24213)) ([9cf7c89](https://github.com/ionic-team/ionic/commit/9cf7c897043854a9d0db81d18ad6c016eb964de8))
* **input:** date type in ion-input now aligns correctly on iOS 15 ([#24217](https://github.com/ionic-team/ionic/issues/24217)) ([0566ec0](https://github.com/ionic-team/ionic/commit/0566ec0da3b8a66a1a1ebb1b235e7297ec483c79))
* **input:** do not clear input if "Enter" key pressed ([#20462](https://github.com/ionic-team/ionic/issues/20462)) ([89bf08b](https://github.com/ionic-team/ionic/commit/89bf08b6276f2a25d66fc0e74ba3303f923af652)), closes [#20442](https://github.com/ionic-team/ionic/issues/20442)
* **input:** IME composition mode ([#24735](https://github.com/ionic-team/ionic/issues/24735)) ([c6381ce](https://github.com/ionic-team/ionic/commit/c6381ce4f90707774d1c8662bba874f7b306bd1c)), closes [#24669](https://github.com/ionic-team/ionic/issues/24669)
* **input:** improve reliability of scroll assist when accessory bar is enabled ([#21936](https://github.com/ionic-team/ionic/issues/21936)) ([22477fb](https://github.com/ionic-team/ionic/commit/22477fb9bf7c0637aa5c8d0aab34c8ccc521b0b9)), closes [#21912](https://github.com/ionic-team/ionic/issues/21912)
* **input:** inherit aria-label to input ([#23159](https://github.com/ionic-team/ionic/issues/23159)) ([61f094d](https://github.com/ionic-team/ionic/commit/61f094d30665c9afec428028883a5d9a085892d8))
* **input:** ion-input accepts any string value ([#24606](https://github.com/ionic-team/ionic/issues/24606)) ([43c5977](https://github.com/ionic-team/ionic/commit/43c5977d48cb12331c1d3107eb73f29b92c5e049)), closes [#19884](https://github.com/ionic-team/ionic/issues/19884)
* **input:** ionInput event emits with type of InputEvent ([#24111](https://github.com/ionic-team/ionic/issues/24111)) ([52cd5d0](https://github.com/ionic-team/ionic/commit/52cd5d0ccedb8013c860198fc69f6bc0d4e6d386))
* **input:** min/max compatibility with react-hook-form ([#24657](https://github.com/ionic-team/ionic/issues/24657)) ([1f91883](https://github.com/ionic-team/ionic/commit/1f918835f437a59f7a70fc59d9305647aa9c298d)), closes [#24489](https://github.com/ionic-team/ionic/issues/24489)
* **input:** only focus the first input / textarea when clicking on the parent item ([#22049](https://github.com/ionic-team/ionic/issues/22049)) ([99f2532](https://github.com/ionic-team/ionic/commit/99f2532ee174da79e2b6a462cfa124673edc1170)), closes [#22037](https://github.com/ionic-team/ionic/issues/22037) [#22032](https://github.com/ionic-team/ionic/issues/22032)
* **input:** only set native input value if different ([#24758](https://github.com/ionic-team/ionic/issues/24758)) ([fd031aa](https://github.com/ionic-team/ionic/commit/fd031aa1c3f05b7bfa3e0a0ee2a4793e29e22df5)), closes [#24753](https://github.com/ionic-team/ionic/issues/24753)
* **input:** properly focus the input when clicking the item padding in WebKit ([#21930](https://github.com/ionic-team/ionic/issues/21930)) ([e4964ff](https://github.com/ionic-team/ionic/commit/e4964ff77b317c92b201cf7c265787b55bdde4d4)), closes [#21509](https://github.com/ionic-team/ionic/issues/21509)
* **input:** remain focused in the input after pressing the clear button ([#21985](https://github.com/ionic-team/ionic/issues/21985)) ([6878fb9](https://github.com/ionic-team/ionic/commit/6878fb9eb99c17908f5630019efaa762b5b006e0)), closes [#21549](https://github.com/ionic-team/ionic/issues/21549)
* **input:** title attribute is automatically inherited ([#22493](https://github.com/ionic-team/ionic/issues/22493)) ([abad12f](https://github.com/ionic-team/ionic/commit/abad12fbdb1378066282fe8e9b7761747951b685)), closes [#22055](https://github.com/ionic-team/ionic/issues/22055)
* **ios, md:** double tapping back button no longer causes app to go back 2 pages ([#23526](https://github.com/ionic-team/ionic/issues/23526)) ([69be51d](https://github.com/ionic-team/ionic/commit/69be51dc54e670b2f75cbfac28a4a09517dbf355)), closes [#18455](https://github.com/ionic-team/ionic/issues/18455)
* **ios:** account for nested tabs with page transition ([#20955](https://github.com/ionic-team/ionic/issues/20955)) ([e23dec5](https://github.com/ionic-team/ionic/commit/e23dec5eb9fbb58eedffabefca8d7d643f49f7b9)), closes [#20948](https://github.com/ionic-team/ionic/issues/20948)
* **ios:** add haptic drag gesture for action sheet and alert components ([#21060](https://github.com/ionic-team/ionic/issues/21060)) ([33be1f0](https://github.com/ionic-team/ionic/commit/33be1f061ebbe27ee22e357c394f112af42ec360))
* **ios:** clamp out of bounds values for swipe to go back ([#20540](https://github.com/ionic-team/ionic/issues/20540)) ([dd32a5e](https://github.com/ionic-team/ionic/commit/dd32a5e2788a11a5c2be0d1840f5775c7307c57f)), closes [#20505](https://github.com/ionic-team/ionic/issues/20505)
* **ios:** contenteditable elements are now selectable on iOS ([#22404](https://github.com/ionic-team/ionic/issues/22404)) ([023fb18](https://github.com/ionic-team/ionic/commit/023fb1841259a61b361066ca369aeffd488efa3f))
* **ios:** improve scroll assist reliability on password inputs ([#21703](https://github.com/ionic-team/ionic/issues/21703)) ([3cbf9e7](https://github.com/ionic-team/ionic/commit/3cbf9e7c4c225d6b02237d8ea8f16fb924ba360e)), closes [#21688](https://github.com/ionic-team/ionic/issues/21688)
* **ios:** large title animation now works properly in a modal ([#20703](https://github.com/ionic-team/ionic/issues/20703)) ([ec4878a](https://github.com/ionic-team/ionic/commit/ec4878ac085d8ff92cb8b2ea0852523f174ab01b)), closes [#20696](https://github.com/ionic-team/ionic/issues/20696)
* **ios:** large title transition works properly in tabbed applications ([#20555](https://github.com/ionic-team/ionic/issues/20555)) ([7187541](https://github.com/ionic-team/ionic/commit/71875417f207d26bd7115655f239251460a1e3d8)), closes [#20482](https://github.com/ionic-team/ionic/issues/20482)
* **ios:** properly animate content when navigating from a tabbed page ([#20918](https://github.com/ionic-team/ionic/issues/20918)) ([8a02b28](https://github.com/ionic-team/ionic/commit/8a02b28efeca81c25176ff52508b4005441e8314)), closes [#20912](https://github.com/ionic-team/ionic/issues/20912)
* **ios:** respect toolbar opacity when doing nav transition ([#21512](https://github.com/ionic-team/ionic/issues/21512)) ([24cfdc3](https://github.com/ionic-team/ionic/commit/24cfdc308f63b7a55969ac58806eafd67116b017))
* **ios:** swipe to go back now works in rtl mode ([#24866](https://github.com/ionic-team/ionic/issues/24866)) ([2ac9105](https://github.com/ionic-team/ionic/commit/2ac9105796a0765fabc48592b5b44ac58c568579)), closes [#19488](https://github.com/ionic-team/ionic/issues/19488)
* **ios:** transition shadow properly sized regardless of footer ([#21095](https://github.com/ionic-team/ionic/issues/21095)) ([50678c0](https://github.com/ionic-team/ionic/commit/50678c03c9829a87408633dabd77b21da1650a84))
* **ios:** translucent toolbar blur no longer obscures entering page title ([#20314](https://github.com/ionic-team/ionic/issues/20314)) ([e580b88](https://github.com/ionic-team/ionic/commit/e580b884770a086ee5d8acf61588ea50181786e6)), closes [#19158](https://github.com/ionic-team/ionic/issues/19158)
* **item-divider:** update design to match native iOS ([#20854](https://github.com/ionic-team/ionic/issues/20854)) ([d91e22d](https://github.com/ionic-team/ionic/commit/d91e22d820f170ecfdfad835ca56701ad70e6f3d))
* **item-sliding:** account for swipe to go back gesture when opening item-options ([#20777](https://github.com/ionic-team/ionic/issues/20777)) ([f23ac44](https://github.com/ionic-team/ionic/commit/f23ac44c9a6646129762bb861cae6145690ca5a1)), closes [#20773](https://github.com/ionic-team/ionic/issues/20773)
* **item-sliding:** close() will maintain disabled state ([#24847](https://github.com/ionic-team/ionic/issues/24847)) ([ea4a9bb](https://github.com/ionic-team/ionic/commit/ea4a9bb69465f8e97746b36638f0b3a26e45da18)), closes [#24747](https://github.com/ionic-team/ionic/issues/24747)
* **item-sliding:** closing an item can no longer be interrupted ([#23973](https://github.com/ionic-team/ionic/issues/23973)) ([3ca0419](https://github.com/ionic-team/ionic/commit/3ca04197a4186c85d04cdf04fa9cb2689ca1bbfb)), closes [#23969](https://github.com/ionic-team/ionic/issues/23969)
* **item-sliding:** item-sliding accounts for multiple ion-item elements ([#23943](https://github.com/ionic-team/ionic/issues/23943)) ([8108edd](https://github.com/ionic-team/ionic/commit/8108edd876b10834015016385dc3cd5b8f31fbfa)), closes [#19312](https://github.com/ionic-team/ionic/issues/19312)
* **item-sliding:** opening item while other items are open no longer requires multiple swipes ([#23683](https://github.com/ionic-team/ionic/issues/23683)) ([792864f](https://github.com/ionic-team/ionic/commit/792864f8ab21dc178c1836a8a0d4fe2d305cc142)), closes [#21579](https://github.com/ionic-team/ionic/issues/21579)
* **item-sliding:** prevent scrolling during slide gesture ([#23774](https://github.com/ionic-team/ionic/issues/23774)) ([e0c4ad3](https://github.com/ionic-team/ionic/commit/e0c4ad30bec3f2bd325d65b210ffb0437149810f)), closes [#19564](https://github.com/ionic-team/ionic/issues/19564)
* **item-sliding:** swiping inside of virtual scroller now prevents scrolling ([#25345](https://github.com/ionic-team/ionic/issues/25345)) ([5a1a5f6](https://github.com/ionic-team/ionic/commit/5a1a5f6b4c2ab4059158986e907fff45d03be753))
* **item, list:** list aria roles are added ([#25336](https://github.com/ionic-team/ionic/issues/25336)) ([311c634](https://github.com/ionic-team/ionic/commit/311c634d20e9e597db676d6f54e4b79cfe742a61)), closes [#19939](https://github.com/ionic-team/ionic/issues/19939)
* **item:** allow click targets inside of label ([#24225](https://github.com/ionic-team/ionic/issues/24225)) ([3949a94](https://github.com/ionic-team/ionic/commit/3949a949dfe112668c69a36d64e5f01a5aef1435))
* **item:** apply proper margin left for slotted icon in RTL ([#20684](https://github.com/ionic-team/ionic/issues/20684)) ([d53595e](https://github.com/ionic-team/ionic/commit/d53595eb1629e0d60f7e832414e84c544e184346)), closes [#20653](https://github.com/ionic-team/ionic/issues/20653)
* **item:** counter defaults to false to make upgrade easier ([#24263](https://github.com/ionic-team/ionic/issues/24263)) ([f61f356](https://github.com/ionic-team/ionic/commit/f61f35600072c5df069a24c3b24eb8f283d586f8))
* **item:** counter has appropriate contrast ([#25266](https://github.com/ionic-team/ionic/issues/25266)) ([750be33](https://github.com/ionic-team/ionic/commit/750be33772e9ba71a3cda35709d17b7912aa68e2)), closes [#25262](https://github.com/ionic-team/ionic/issues/25262)
* **item:** detail icon is no longer announced by screen readers ([#23055](https://github.com/ionic-team/ionic/issues/23055)) ([c877061](https://github.com/ionic-team/ionic/commit/c877061a328c6ab6fa7248b9880d0205c6c4f6c1)), closes [#23054](https://github.com/ionic-team/ionic/issues/23054)
* **item:** detail icon now respects rtl mode ([#23081](https://github.com/ionic-team/ionic/issues/23081)) ([b04fb6e](https://github.com/ionic-team/ionic/commit/b04fb6e849bc9d6283271aaadc2b8aaae1f3961d)), closes [#23078](https://github.com/ionic-team/ionic/issues/23078)
* **item:** error slot visible in Safari ([#24579](https://github.com/ionic-team/ionic/issues/24579)) ([af01a8b](https://github.com/ionic-team/ionic/commit/af01a8b3073dce784cc042923d712b9492638d32)), closes [#24575](https://github.com/ionic-team/ionic/issues/24575)
* **item:** form validation states are now properly shown ([#23853](https://github.com/ionic-team/ionic/issues/23853)) ([5ca2ce9](https://github.com/ionic-team/ionic/commit/5ca2ce91971408218d7bdc52509ce61a6ebb46aa)), closes [#23733](https://github.com/ionic-team/ionic/issues/23733) [#23850](https://github.com/ionic-team/ionic/issues/23850)
* **item:** highlight now appears above helper/error text ([#23763](https://github.com/ionic-team/ionic/issues/23763)) ([2995e33](https://github.com/ionic-team/ionic/commit/2995e337c8b4612a87eb7111224ec702494fd1d7)), closes [#23510](https://github.com/ionic-team/ionic/issues/23510)
* **item:** inherit align-items from parent item ([#19278](https://github.com/ionic-team/ionic/issues/19278)) ([882f8fe](https://github.com/ionic-team/ionic/commit/882f8fef07dfb6ebda17ca09046d1af281075098)), closes [#18703](https://github.com/ionic-team/ionic/issues/18703)
* **item:** input-wrapper now inherits overflow ([#21282](https://github.com/ionic-team/ionic/issues/21282)) ([29d208d](https://github.com/ionic-team/ionic/commit/29d208de88f340e216e22badb6366bba4eda8bfb))
* **item:** label text aligns with input text ([#24620](https://github.com/ionic-team/ionic/issues/24620)) ([94d033c](https://github.com/ionic-team/ionic/commit/94d033c4216ae9978aed6346c1c0ea2aec4d375b)), closes [#24404](https://github.com/ionic-team/ionic/issues/24404)
* **item:** match material design character counter ([#24335](https://github.com/ionic-team/ionic/issues/24335)) ([54db1a1](https://github.com/ionic-team/ionic/commit/54db1a1e7c71c78e843370848fc768582768333e)), closes [#24334](https://github.com/ionic-team/ionic/issues/24334)
* **item:** mirror disabled prop to aria attribute ([#23544](https://github.com/ionic-team/ionic/issues/23544)) ([9021e7c](https://github.com/ionic-team/ionic/commit/9021e7cc4b48a69ccc94faa7d2ddcb10a2afa340)), closes [#23513](https://github.com/ionic-team/ionic/issues/23513)
* **item:** only add click event listener to items with inputs ([#22352](https://github.com/ionic-team/ionic/issues/22352)) ([9659ad6](https://github.com/ionic-team/ionic/commit/9659ad63349d5123ca2bd2548a43e37d5ee817e7)), closes [#22011](https://github.com/ionic-team/ionic/issues/22011)
* **item:** properly align datetime and select without labels and with fixed labels ([#22221](https://github.com/ionic-team/ionic/issues/22221)) ([f42c688](https://github.com/ionic-team/ionic/commit/f42c688f4630e3dc5d10b947e7f2bee9d5967d8c)), closes [#18773](https://github.com/ionic-team/ionic/issues/18773) [#18761](https://github.com/ionic-team/ionic/issues/18761) [#18779](https://github.com/ionic-team/ionic/issues/18779)
* **item:** remove empty padding space for item bottom ([#24323](https://github.com/ionic-team/ionic/issues/24323)) ([500985c](https://github.com/ionic-team/ionic/commit/500985ce04783f502a1f5c50fbd8b4c5e93294d7)), closes [#23892](https://github.com/ionic-team/ionic/issues/23892)
* **item:** remove unneeded box-shadow CSS variable ([#20412](https://github.com/ionic-team/ionic/issues/20412)) ([a6764c4](https://github.com/ionic-team/ionic/commit/a6764c4724e1e7eed19a1902b563aeb61bfde38e)), closes [#20392](https://github.com/ionic-team/ionic/issues/20392)
* **item:** using multiple items with inputs no longer results in console warnings ([#23429](https://github.com/ionic-team/ionic/issues/23429)) ([e27b5b6](https://github.com/ionic-team/ionic/commit/e27b5b6ae360c44d8521ac7191817cbbe0367c05)), closes [#23427](https://github.com/ionic-team/ionic/issues/23427)
* **keyboard:** keyboard events now consistently fire on android ([#21741](https://github.com/ionic-team/ionic/issues/21741)) ([020f3cc](https://github.com/ionic-team/ionic/commit/020f3cc56cb6dac23dd8766a3802422500b510e2)), closes [#21734](https://github.com/ionic-team/ionic/issues/21734)
* **label:** keep color when focused on a floating or stacked label ([#18576](https://github.com/ionic-team/ionic/issues/18576)) ([992580a](https://github.com/ionic-team/ionic/commit/992580a3830321bdf9591681ebe38e823205389d)), closes [#18531](https://github.com/ionic-team/ionic/issues/18531)
* **label:** label now only takes up as much space as needed when slotted ([#23807](https://github.com/ionic-team/ionic/issues/23807)) ([9932e26](https://github.com/ionic-team/ionic/commit/9932e26a2ef28317bc85761e71a8fc4d881b8ae8)), closes [#23806](https://github.com/ionic-team/ionic/issues/23806)
* **label:** only inherit color if color property is set on ion-item ([#23944](https://github.com/ionic-team/ionic/issues/23944)) ([ae1325c](https://github.com/ionic-team/ionic/commit/ae1325cee698066a71aae4e7deb953c4185c0926)), closes [#20125](https://github.com/ionic-team/ionic/issues/20125)
* **label:** only show placeholder with floating label when focused ([#22958](https://github.com/ionic-team/ionic/issues/22958)) ([9282aa6](https://github.com/ionic-team/ionic/commit/9282aa68715c088e9c8fcd915e78fb7ae91f551f)), closes [#17571](https://github.com/ionic-team/ionic/issues/17571)
* **label:** properly float labels for non-input items ([#23060](https://github.com/ionic-team/ionic/issues/23060)) ([c8a3999](https://github.com/ionic-team/ionic/commit/c8a3999da109b1719777f2acb791ab5388d371ea))
* **label:** remove subpixel font-size to prevent visual glitches ([#20415](https://github.com/ionic-team/ionic/issues/20415)) ([3d6f287](https://github.com/ionic-team/ionic/commit/3d6f287d87bfaa0d81a34182baf38192e08fb3c1)), closes [#20407](https://github.com/ionic-team/ionic/issues/20407)
* **label:** text contents will repaint on change ([#25395](https://github.com/ionic-team/ionic/issues/25395)) ([52ec741](https://github.com/ionic-team/ionic/commit/52ec74193b4e2478cb84a6dfea261cb2113dcbff))
* **label:** text overflow for slotted headings ([#20690](https://github.com/ionic-team/ionic/issues/20690)) ([4d34ce6](https://github.com/ionic-team/ionic/commit/4d34ce6a31eaa19859699646cc614f5be6239e10)), closes [#17087](https://github.com/ionic-team/ionic/issues/17087)
* **label:** use translateY so input caret shows up due to webkit issue ([#21949](https://github.com/ionic-team/ionic/issues/21949)) ([00eac33](https://github.com/ionic-team/ionic/commit/00eac33053f49dbebf22ef95fddcb66570ed117a)), closes [#21943](https://github.com/ionic-team/ionic/issues/21943)
* **list:** change inset border radius to match iOS 15 ([#23711](https://github.com/ionic-team/ionic/issues/23711)) ([fe2810b](https://github.com/ionic-team/ionic/commit/fe2810b227abc482e663b210cd89f29b76119ff5))
* **list:** show bottom border on last item in a list followed by a list ([#20798](https://github.com/ionic-team/ionic/issues/20798)) ([7bc5191](https://github.com/ionic-team/ionic/commit/7bc51911f6c538be8b91d1e569675b19832cb000))
* **loading:** screen readers no longer incorrectly announce spinner ([#21116](https://github.com/ionic-team/ionic/issues/21116)) ([63d8f62](https://github.com/ionic-team/ionic/commit/63d8f6239cc39e6a111108bd1a2557c297a256ae)), closes [#21107](https://github.com/ionic-team/ionic/issues/21107)
* **loading:** spinner now respects —spinner-color ([#25261](https://github.com/ionic-team/ionic/issues/25261)) ([65f4c74](https://github.com/ionic-team/ionic/commit/65f4c742e7a5e5756f6f72dd853e38e885f90385)), closes [#25180](https://github.com/ionic-team/ionic/issues/25180)
* **md/label:** apply error appearance when control is touched ([#24072](https://github.com/ionic-team/ionic/issues/24072)) ([009dff5](https://github.com/ionic-team/ionic/commit/009dff5584fea6398bb99aa55760d25dafd7fbcc))
* **md:** do not display blank screen when using MD page transition and swipe gesture ([#21058](https://github.com/ionic-team/ionic/issues/21058)) ([4973807](https://github.com/ionic-team/ionic/commit/497380743df4461688455bc8b8440d2f3cc7c247)), closes [#21056](https://github.com/ionic-team/ionic/issues/21056)
* **md:** do not hide page when swipe gesture is cancelled ([#21247](https://github.com/ionic-team/ionic/issues/21247)) ([f334e83](https://github.com/ionic-team/ionic/commit/f334e83a43f855ac1e36eaf73954df6ee27a03af))
* **menu-button:** custom aria-label can now be set ([#23608](https://github.com/ionic-team/ionic/issues/23608)) ([c08345d](https://github.com/ionic-team/ionic/commit/c08345df2ee3175f3f0d11ff877c7b6f1a102321)), closes [#23604](https://github.com/ionic-team/ionic/issues/23604)
* **menu-button:** screen readers now properly announce menu button ([#21324](https://github.com/ionic-team/ionic/issues/21324)) ([eaf4fb6](https://github.com/ionic-team/ionic/commit/eaf4fb6b2a6d68f5c3d8d49ef41b4885f096070d))
* **menu:** added focus trapping, improved compatibility with screen readers ([#24076](https://github.com/ionic-team/ionic/issues/24076)) ([bdb268a](https://github.com/ionic-team/ionic/commit/bdb268aa12c5bf411c96529672486d35e018cefa))
* **menu:** allow ssr to work properly with hardware back button updates ([#20629](https://github.com/ionic-team/ionic/issues/20629)) ([fe8d74d](https://github.com/ionic-team/ionic/commit/fe8d74d08cb919ed1c685262f0aed4a544c3a7e1))
* **menu:** clamp out of bounds swipe value ([#19684](https://github.com/ionic-team/ionic/issues/19684)) ([4bc3dc7](https://github.com/ionic-team/ionic/commit/4bc3dc73c1df57e44c34585af9e9171ce5863b06)), closes [#18927](https://github.com/ionic-team/ionic/issues/18927)
* **menu:** fix jump when dragging open ([#20288](https://github.com/ionic-team/ionic/issues/20288)) ([b144711](https://github.com/ionic-team/ionic/commit/b14471178ef69bbe6902c19572ff4c07173f1e70)), closes [#20286](https://github.com/ionic-team/ionic/issues/20286)
* **menu:** focus trapping with menu and overlays no longer results in errors ([#24611](https://github.com/ionic-team/ionic/issues/24611)) ([632dafc](https://github.com/ionic-team/ionic/commit/632dafcd57de5086deebdc7d586b01710aa1a3ce)), closes [#24361](https://github.com/ionic-team/ionic/issues/24361) [#24481](https://github.com/ionic-team/ionic/issues/24481)
* **menu:** hardware back button now dismisses side menu if open ([#20558](https://github.com/ionic-team/ionic/issues/20558)) ([6b2a929](https://github.com/ionic-team/ionic/commit/6b2a929cd7e70b16383cb3336b399a1aee2d6101)), closes [#20559](https://github.com/ionic-team/ionic/issues/20559)
* **menu:** preserve scroll position when focusing on open ([#25044](https://github.com/ionic-team/ionic/issues/25044)) ([da89684](https://github.com/ionic-team/ionic/commit/da896848776105ba1f7035c4412495786199bade))
* **menu:** remove main attribute that was supposed to removed in v5 ([#24565](https://github.com/ionic-team/ionic/issues/24565)) ([7704ac3](https://github.com/ionic-team/ionic/commit/7704ac3a3710396248590daecb945b76825a0539)), closes [#24563](https://github.com/ionic-team/ionic/issues/24563)
* **menu:** rtl menu no longer disappears on ios 15 ([#25309](https://github.com/ionic-team/ionic/issues/25309)) ([6005431](https://github.com/ionic-team/ionic/commit/60054310afbab6151f6c29ff6e74666acd181a41)), closes [#25192](https://github.com/ionic-team/ionic/issues/25192)
* **menu:** swipe gesture should not open menu when a modal is displayed ([#20546](https://github.com/ionic-team/ionic/issues/20546)) ([3252c2f](https://github.com/ionic-team/ionic/commit/3252c2f8dc46e0853a7f626baa6023a01ac21a25)), closes [#20467](https://github.com/ionic-team/ionic/issues/20467)
* **modal, popover:** do not dismiss when ionDismiss is emitted from select ([#25125](https://github.com/ionic-team/ionic/issues/25125)) ([90115db](https://github.com/ionic-team/ionic/commit/90115db98540a5fc67b611ac2742d1221b8e96ff)), closes [#25124](https://github.com/ionic-team/ionic/issues/25124)
* **modal, popover:** opening modal and popover now works even if overlay was added to ion-app directly ([#24174](https://github.com/ionic-team/ionic/issues/24174)) ([da339a8](https://github.com/ionic-team/ionic/commit/da339a8a743548f9bde8b5a22f1a9d6b191f6e7b)), closes [#23728](https://github.com/ionic-team/ionic/issues/23728)
* **modal, popover:** overlays now automatically determine if they are inline ([#23434](https://github.com/ionic-team/ionic/issues/23434)) ([8dbe8ba](https://github.com/ionic-team/ionic/commit/8dbe8ba7bc26792c5024f81cf4752f5b78317492))
* **modal, popover:** quickly opening modal/popover no longer presents duplicates ([#24697](https://github.com/ionic-team/ionic/issues/24697)) ([928c5fb](https://github.com/ionic-team/ionic/commit/928c5fbfcbf3ef1b2c3074464fc20dcf1fe143ae))
* **modal:** add additional padding to toolbars in iOS modal ([#23181](https://github.com/ionic-team/ionic/issues/23181)) ([d94739f](https://github.com/ionic-team/ionic/commit/d94739f39bc08446c17eb733ef2bdb0fc6a0301b)), closes [#22778](https://github.com/ionic-team/ionic/issues/22778)
* **modal:** add additional padding to toolbars in iOS modal ([#23262](https://github.com/ionic-team/ionic/issues/23262)) ([a037b65](https://github.com/ionic-team/ionic/commit/a037b65aad5cfc0477322a8f36105b9009366ec2)), closes [#22778](https://github.com/ionic-team/ionic/issues/22778)
* **modal:** add canDismiss option to modal options ([#25144](https://github.com/ionic-team/ionic/issues/25144)) ([2984ddf](https://github.com/ionic-team/ionic/commit/2984ddf111b6acbd9e47ed90830b6522179b6cee)), closes [#25143](https://github.com/ionic-team/ionic/issues/25143)
* **modal:** allow swipe to close animation to be overridden ([#20585](https://github.com/ionic-team/ionic/issues/20585)) ([8d3ce8d](https://github.com/ionic-team/ionic/commit/8d3ce8d29c9abd89ce47c882e0d7b2ac0f861966)), closes [#20577](https://github.com/ionic-team/ionic/issues/20577)
* **modal:** backdrop and box shadows no longer stack when opening multiple modals ([#20801](https://github.com/ionic-team/ionic/issues/20801)) ([253cd96](https://github.com/ionic-team/ionic/commit/253cd96164914a803f6bb42ff95ca74880c940d0)), closes [#20800](https://github.com/ionic-team/ionic/issues/20800)
* **modal:** backdrop is no longer tappable on card-style modal on smaller screens ([#20802](https://github.com/ionic-team/ionic/issues/20802)) ([12932dd](https://github.com/ionic-team/ionic/commit/12932dd20212bec7d780650166c70819d125f75a)), closes [#20783](https://github.com/ionic-team/ionic/issues/20783)
* **modal:** backdropBreakpoint allows interactivity behind sheet ([#24798](https://github.com/ionic-team/ionic/issues/24798)) ([fca3f56](https://github.com/ionic-team/ionic/commit/fca3f56ca4568e63fd493debda088263caa86c64)), closes [#24797](https://github.com/ionic-team/ionic/issues/24797)
* **modal:** backdropBreakpoint is now an exclusive value ([#23954](https://github.com/ionic-team/ionic/issues/23954)) ([ed455ab](https://github.com/ionic-team/ionic/commit/ed455ab4c6df73f801a3c941da21261c205c9634))
* **modal:** border radius is correctly set on card style modal ([#23461](https://github.com/ionic-team/ionic/issues/23461)) ([bccb8ad](https://github.com/ionic-team/ionic/commit/bccb8ad5fb5ec7f98a6cbfa62a403ecaca7fbdb6))
* **modal:** border radius is now correctly applied to card modals ([#24204](https://github.com/ionic-team/ionic/issues/24204)) ([1f4f8eb](https://github.com/ionic-team/ionic/commit/1f4f8eb6ca2b8adb543ade83c309177ac7f2044d))
* **modal:** card modal can now be swiped to close on the content ([#25185](https://github.com/ionic-team/ionic/issues/25185)) ([7633ddb](https://github.com/ionic-team/ionic/commit/7633ddbc845745dfe36b5c8025c54c22c083c2f4)), closes [#22046](https://github.com/ionic-team/ionic/issues/22046)
* **modal:** card modal no longer dismisses from content with refresher ([#25227](https://github.com/ionic-team/ionic/issues/25227)) ([c4f811f](https://github.com/ionic-team/ionic/commit/c4f811f1dde0dcbcdaebaa3a4f5ef87e192b5cc5))
* **modal:** card modal shadow now shows up correctly on ipad ([#24203](https://github.com/ionic-team/ionic/issues/24203)) ([5d4f5af](https://github.com/ionic-team/ionic/commit/5d4f5af36083eafcf7de91b22749ff307701087f))
* **modal:** card style modal no longer gets stuck when swiping quickly ([#21224](https://github.com/ionic-team/ionic/issues/21224)) ([448dfa0](https://github.com/ionic-team/ionic/commit/448dfa0a6955008ce4dc73354f5b8319ae1a1cc2))
* **modal:** card style modal now adds appropriate contrast ([#20604](https://github.com/ionic-team/ionic/issues/20604)) ([b5310ef](https://github.com/ionic-team/ionic/commit/b5310effe3f9b47459f22221da1853a55dbb0279))
* **modal:** card-style modal now opens at full width on larger devices ([#20256](https://github.com/ionic-team/ionic/issues/20256)) ([443cbd9](https://github.com/ionic-team/ionic/commit/443cbd9eb273767d8405b6a05ffabee037e9f3b7)), closes [#20255](https://github.com/ionic-team/ionic/issues/20255)
* **modal:** card-style modal offset now matches the iOS spec ([#20166](https://github.com/ionic-team/ionic/issues/20166)) ([cf287fd](https://github.com/ionic-team/ionic/commit/cf287fda7f67735657f63bb1f4cf79dd4e656886))
* **modal:** expose breakpoint props in ModalOptions interface ([#23867](https://github.com/ionic-team/ionic/issues/23867)) ([5fd80fd](https://github.com/ionic-team/ionic/commit/5fd80fd43885a5d0cd65f0eef4e0ff15e82c4fe0)), closes [#23866](https://github.com/ionic-team/ionic/issues/23866)
* **modal:** fix backdrop animation for sheets with off-center backdropBreakpoint ([#24061](https://github.com/ionic-team/ionic/issues/24061)) ([49db6d0](https://github.com/ionic-team/ionic/commit/49db6d02883b11b5f179300e2eaa298002a381e8))
* **modal:** fix timing issue when rapidly closing and opening controller modal ([#24380](https://github.com/ionic-team/ionic/issues/24380)) ([732f8e1](https://github.com/ionic-team/ionic/commit/732f8e10ce604f1a3e98518ae9c3a4afd7803e9a))
* **modal:** handle on sheet modal can now be turned off ([#23900](https://github.com/ionic-team/ionic/issues/23900)) ([e2d2ad6](https://github.com/ionic-team/ionic/commit/e2d2ad6f8eaf798c6f4b4a69f2b8176f0ac22d32))
* **modal:** inline modals inherit ion-page styling ([#24723](https://github.com/ionic-team/ionic/issues/24723)) ([596aad4](https://github.com/ionic-team/ionic/commit/596aad435b5102307da89dd626ca4682b78db452)), closes [#24706](https://github.com/ionic-team/ionic/issues/24706)
* **modal:** leave animation transitions modal completely out of viewport on ipad ([#20702](https://github.com/ionic-team/ionic/issues/20702)) ([22d5256](https://github.com/ionic-team/ionic/commit/22d52568100d8096ee36e3a61a19614f0d63d45f)), closes [#20697](https://github.com/ionic-team/ionic/issues/20697)
* **modal:** life cycle events for controller modals ([#24508](https://github.com/ionic-team/ionic/issues/24508)) ([9a15753](https://github.com/ionic-team/ionic/commit/9a15753fd95e32155abdeb490ec57cb72385ad1a)), closes [#24460](https://github.com/ionic-team/ionic/issues/24460)
* **modal:** modal displays in middle of screen on desktop ([#23911](https://github.com/ionic-team/ionic/issues/23911)) ([9d87028](https://github.com/ionic-team/ionic/commit/9d87028e81723a0f1498c8cf231319676078eda0))
* **modal:** native keyboard will dismiss when bottom sheet is dragged ([#24642](https://github.com/ionic-team/ionic/issues/24642)) ([525f01f](https://github.com/ionic-team/ionic/commit/525f01f086ebf95ab62af0162b876a25f50a3d4b)), closes [#23878](https://github.com/ionic-team/ionic/issues/23878)
* **modal:** presenting multiple card-style modals now adds border radius properly ([#20476](https://github.com/ionic-team/ionic/issues/20476)) ([abf594a](https://github.com/ionic-team/ionic/commit/abf594aa611562a76e3baecfa38456d41a1410f3)), closes [#20475](https://github.com/ionic-team/ionic/issues/20475)
* **modal:** prevent card style modal styles from being overridden ([#20470](https://github.com/ionic-team/ionic/issues/20470)) ([86ab77a](https://github.com/ionic-team/ionic/commit/86ab77a6e2cb124510c244110fc78a4bc0654cd1)), closes [#20469](https://github.com/ionic-team/ionic/issues/20469)
* **modal:** prevent double dismiss via gesture and backdrop tap on card-style modal ([#20203](https://github.com/ionic-team/ionic/issues/20203)) ([5b0400d](https://github.com/ionic-team/ionic/commit/5b0400d5afec308861408967a5f61c9b93af0004))
* **modal:** properly apply border radius on card-style modal ([#20852](https://github.com/ionic-team/ionic/issues/20852)) ([dff3816](https://github.com/ionic-team/ionic/commit/dff3816c049a1c051f94d3176c8b903a69603912)), closes [#20851](https://github.com/ionic-team/ionic/issues/20851)
* **modal:** properly inherit border radius for modals on Safari ([#20887](https://github.com/ionic-team/ionic/issues/20887)) ([bd64509](https://github.com/ionic-team/ionic/commit/bd64509bae9dd4c960134d986ce8150dc1a9d3b4)), closes [#20878](https://github.com/ionic-team/ionic/issues/20878)
* **modal:** properly remove safe area padding on card-modal ([#20853](https://github.com/ionic-team/ionic/issues/20853)) ([71f1182](https://github.com/ionic-team/ionic/commit/71f118201b0918f60c1a078d55afd10b39f17e86)), closes [#20799](https://github.com/ionic-team/ionic/issues/20799)
* **modal:** properly target card modal for iPadOS styles ([#20884](https://github.com/ionic-team/ionic/issues/20884)) ([5816cf5](https://github.com/ionic-team/ionic/commit/5816cf52a779acc4613c2d2da28b97c511360cc2))
* **modal:** re-enable swipe gestures when modal is dismissed ([#24846](https://github.com/ionic-team/ionic/issues/24846)) ([836c01c](https://github.com/ionic-team/ionic/commit/836c01c73e42caab0101ac4988f0a9b27cf96a5b)), closes [#24817](https://github.com/ionic-team/ionic/issues/24817)
* **modal:** reset breakpoint to initial breakpoint on present ([#25246](https://github.com/ionic-team/ionic/issues/25246)) ([2557bf3](https://github.com/ionic-team/ionic/commit/2557bf3c3eed9e33e89e07a8d73489da8d81bee3)), closes [#25245](https://github.com/ionic-team/ionic/issues/25245)
* **modal:** respect card-style modal spec for iPadOS ([#20750](https://github.com/ionic-team/ionic/issues/20750)) ([75bae40](https://github.com/ionic-team/ionic/commit/75bae403e917b20645675343734440ee95d31634)), closes [#20700](https://github.com/ionic-team/ionic/issues/20700)
* **modal:** set card-style modal height using the --height css variable ([#21453](https://github.com/ionic-team/ionic/issues/21453)) ([a4f0bdb](https://github.com/ionic-team/ionic/commit/a4f0bdb4c3ceeeaf902d520e9aa72e04a6ec2302))
* **modal:** sheet animation works correctly if breakpoints value does not include 1 ([#23927](https://github.com/ionic-team/ionic/issues/23927)) ([414f246](https://github.com/ionic-team/ionic/commit/414f24685cbc67a7fff142b7786d33ce1cd67a0c))
* **modal:** sheet modal handle is now positioned correctly ([#23901](https://github.com/ionic-team/ionic/issues/23901)) ([58a4ba2](https://github.com/ionic-team/ionic/commit/58a4ba285389e45276df49a0b4a3412daa95e92c))
* **modal:** sheet modal now accounts for safe area ([#23884](https://github.com/ionic-team/ionic/issues/23884)) ([195d817](https://github.com/ionic-team/ionic/commit/195d8179676155315f8532636b6371dd2a63e4b9)), closes [#23874](https://github.com/ionic-team/ionic/issues/23874)
* **modal:** sheet modal now allows input focusing when backdrop disabled ([#24840](https://github.com/ionic-team/ionic/issues/24840)) ([e4ec572](https://github.com/ionic-team/ionic/commit/e4ec572043e22bd2626dbcfd204fc22a7335282c)), closes [#24581](https://github.com/ionic-team/ionic/issues/24581)
* **modal:** swipe to close modal is no longer swipeable on footer ([#23401](https://github.com/ionic-team/ionic/issues/23401)) ([ae96563](https://github.com/ionic-team/ionic/commit/ae96563fb3c4612cb8585292b389ee746f5759f7)), closes [#23398](https://github.com/ionic-team/ionic/issues/23398)
* **modal:** swipe to close on content blocks scroll in ion-nav ([#25300](https://github.com/ionic-team/ionic/issues/25300)) ([fdc55c0](https://github.com/ionic-team/ionic/commit/fdc55c072765c87ad7c783e6d8a238b007f5f3ff)), closes [#25298](https://github.com/ionic-team/ionic/issues/25298)
* **modal:** swipeable modal background should be able to be overridden ([#20584](https://github.com/ionic-team/ionic/issues/20584)) ([ad6fac8](https://github.com/ionic-team/ionic/commit/ad6fac83cb7c4acb377b4b1620ab1a3f852bc6d3)), closes [#20572](https://github.com/ionic-team/ionic/issues/20572)
* **modal:** swipeable modal now works in firefox ([#20714](https://github.com/ionic-team/ionic/issues/20714)) ([7d260b9](https://github.com/ionic-team/ionic/commit/7d260b96a73958709fa93a4fe58f816a445471ee)), closes [#20706](https://github.com/ionic-team/ionic/issues/20706)
* **modal:** swipeable modal styles only apply to ios ([#20571](https://github.com/ionic-team/ionic/issues/20571)) ([3a2d828](https://github.com/ionic-team/ionic/commit/3a2d82814b22a3987a5abfe4412d83a93a97b6b7)), closes [#20569](https://github.com/ionic-team/ionic/issues/20569)
* **modal:** swipeToClose property is now reactive ([#21073](https://github.com/ionic-team/ionic/issues/21073)) ([4bd9134](https://github.com/ionic-team/ionic/commit/4bd91344730bd26c66a8d838436d94045dc21f78)), closes [#21072](https://github.com/ionic-team/ionic/issues/21072)
* **nav:** custom animation is now used correctly ([#23779](https://github.com/ionic-team/ionic/issues/23779)) ([f9415ef](https://github.com/ionic-team/ionic/commit/f9415ef8a689e26078bdd01623348c79f9f818ad)), closes [#23777](https://github.com/ionic-team/ionic/issues/23777)
* **nav:** insertPages method correctly inserts multiple pages with props ([#21725](https://github.com/ionic-team/ionic/issues/21725)) ([eb592b8](https://github.com/ionic-team/ionic/commit/eb592b8917b8a7412d8c346f41b47d3b79002b95)), closes [#21724](https://github.com/ionic-team/ionic/issues/21724)
* **nav:** swipe to go back works inside card modal ([#25333](https://github.com/ionic-team/ionic/issues/25333)) ([0156be6](https://github.com/ionic-team/ionic/commit/0156be61cbf73b25cb3c2cba1bd20adebbb3db4f)), closes [#25327](https://github.com/ionic-team/ionic/issues/25327)
* only cascade mode from parent Ionic components ([#20828](https://github.com/ionic-team/ionic/issues/20828)) ([6ed1c51](https://github.com/ionic-team/ionic/commit/6ed1c51321d781ff92efbf623790af91cb16a5af)), closes [#20055](https://github.com/ionic-team/ionic/issues/20055)
* **overlay:** do not try to trap focus on hidden inputs ([#21799](https://github.com/ionic-team/ionic/issues/21799)) ([bcbe8cb](https://github.com/ionic-team/ionic/commit/bcbe8cbb8de86a0310bc61b05c6a1bb54ce11df0))
* overlays now present correctly when using custom elements build ([#23039](https://github.com/ionic-team/ionic/issues/23039)) ([e4bf052](https://github.com/ionic-team/ionic/commit/e4bf052794af9aac07f887013b9250d2a045eba3)), closes [#23029](https://github.com/ionic-team/ionic/issues/23029)
* **overlays:** declarative modals now work properly with the hardware back button ([#24165](https://github.com/ionic-team/ionic/issues/24165)) ([b3759ae](https://github.com/ionic-team/ionic/commit/b3759aed5bd1ec6a7c744af03d0dac9c8055c5af))
* **overlays:** define children custom elements ([#24372](https://github.com/ionic-team/ionic/issues/24372)) ([7c700b4](https://github.com/ionic-team/ionic/commit/7c700b4caa35d7eb50c877d794f9db9fad6ed88b)), closes [#24366](https://github.com/ionic-team/ionic/issues/24366)
* **overlays:** define custom element children ([#24439](https://github.com/ionic-team/ionic/issues/24439)) ([4715b83](https://github.com/ionic-team/ionic/commit/4715b83abb30ec5930710d16e5bfe8fc88a940ce)), closes [#24393](https://github.com/ionic-team/ionic/issues/24393)
* **overlays:** focus overlay when presented ([#20997](https://github.com/ionic-team/ionic/issues/20997)) ([fc2be8d](https://github.com/ionic-team/ionic/commit/fc2be8d08bbb495df911783f808d7ca511942172)), closes [#19882](https://github.com/ionic-team/ionic/issues/19882) [#17126](https://github.com/ionic-team/ionic/issues/17126)
* **overlays:** getTop now returns the top-most presented overlay ([#24547](https://github.com/ionic-team/ionic/issues/24547)) ([f5b4382](https://github.com/ionic-team/ionic/commit/f5b4382fd5728365e4badf39bc1dd0c149b45c2c)), closes [#19111](https://github.com/ionic-team/ionic/issues/19111)
* **overlays:** move prepareOverlay to connectedCallback ([7951846](https://github.com/ionic-team/ionic/commit/79518468dd289d1eef4a0397efc610d45f0a1ef1))
* **overlays:** overlay interfaces are now exported from framework packages and documented ([#23619](https://github.com/ionic-team/ionic/issues/23619)) ([773bbcb](https://github.com/ionic-team/ionic/commit/773bbcb211d3cf0caf38c25b44e666d98ddfafe5)), closes [#22790](https://github.com/ionic-team/ionic/issues/22790)
* **overlays:** prevent accidental clicks when dismissing overlays ([#21093](https://github.com/ionic-team/ionic/issues/21093)) ([671802f](https://github.com/ionic-team/ionic/commit/671802f9a2050d9942e9dfb2db9f9c58bdc58620)), closes [#21092](https://github.com/ionic-team/ionic/issues/21092)
* **overlays:** prevent accidental dismiss of overlays when tapping screen twice ([#20683](https://github.com/ionic-team/ionic/issues/20683)) ([b6c2a77](https://github.com/ionic-team/ionic/commit/b6c2a77deb1c09eb1fd414f7737794e208ab5081)), closes [#20608](https://github.com/ionic-team/ionic/issues/20608)
* **overlays:** prevent focus from being stolen when presenting another overlay from within a modal ([#21856](https://github.com/ionic-team/ionic/issues/21856)) ([5c177d7](https://github.com/ionic-team/ionic/commit/5c177d756f7755e766d5b619d49825c4799aee47)), closes [#21840](https://github.com/ionic-team/ionic/issues/21840)
* **overlays:** respect keyboardClose property when opening overlays ([#21240](https://github.com/ionic-team/ionic/issues/21240)) ([9d0dcbb](https://github.com/ionic-team/ionic/commit/9d0dcbbd31fc34ad8952eacb9864ad1b31636113))
* **overlays:** return focus to presenting element after dismissal ([#22167](https://github.com/ionic-team/ionic/issues/22167)) ([cc45ad8](https://github.com/ionic-team/ionic/commit/cc45ad815c002c5d890f2e105c546b4c3b3a58c0)), closes [#21768](https://github.com/ionic-team/ionic/issues/21768)
* **overlays:** screen readers no longer read content behind overlays ([#23284](https://github.com/ionic-team/ionic/issues/23284)) ([a9b12a5](https://github.com/ionic-team/ionic/commit/a9b12a5aa4c150a1f8a80a826dda0df350bc0092)), closes [#22714](https://github.com/ionic-team/ionic/issues/22714)
* **overlays:** thrown errors are no longer suppressed ([#23831](https://github.com/ionic-team/ionic/issues/23831)) ([a212eb5](https://github.com/ionic-team/ionic/commit/a212eb52599e35d3706e2d3cef751e490e3a7259)), closes [#22724](https://github.com/ionic-team/ionic/issues/22724)
* **overlays:** trap focus inside overlay components except toast ([#21716](https://github.com/ionic-team/ionic/issues/21716)) ([fff4aec](https://github.com/ionic-team/ionic/commit/fff4aec6cfbd48566594a05f4af57dd0578977a8)), closes [#21647](https://github.com/ionic-team/ionic/issues/21647)
* **picker-column-internal:** center active item when rapidly opened ([#25155](https://github.com/ionic-team/ionic/issues/25155)) ([8e17fa9](https://github.com/ionic-team/ionic/commit/8e17fa9d5f9b00139693e34bc93b1f9c718ea3cf)), closes [#25154](https://github.com/ionic-team/ionic/issues/25154)
* **picker-column-internal:** prevent multiple items from being highlighted at once ([#24268](https://github.com/ionic-team/ionic/issues/24268)) ([c2bef8d](https://github.com/ionic-team/ionic/commit/c2bef8df14111dc00c382a3ab36c27a08a92f0b7))
* **picker-column:** add cancelable check to avoid intervention error in chrome ([#22140](https://github.com/ionic-team/ionic/issues/22140)) ([a24a041](https://github.com/ionic-team/ionic/commit/a24a041064fd9ce6ca161d3522083d50e585e9dd)), closes [#22137](https://github.com/ionic-team/ionic/issues/22137)
* **picker-column:** column renders correctly with selected value ([#24988](https://github.com/ionic-team/ionic/issues/24988)) ([8318659](https://github.com/ionic-team/ionic/commit/83186598ed6cf08b0f0421076c4afb3ab53e1e57)), closes [#17664](https://github.com/ionic-team/ionic/issues/17664)
* **picker:** haptics now work properly ([#21268](https://github.com/ionic-team/ionic/issues/21268)) ([8e11ecc](https://github.com/ionic-team/ionic/commit/8e11ecc136c61e925e76c0e48ab21611e09b5898))
* **picker:** include showBackdrop in interface ([#20301](https://github.com/ionic-team/ionic/issues/20301)) ([33186ba](https://github.com/ionic-team/ionic/commit/33186ba716de77edc92ae8e7d307f90fff8b8ed1)), closes [#18893](https://github.com/ionic-team/ionic/issues/18893)
* **picker:** pick correct option at low velocities ([#19660](https://github.com/ionic-team/ionic/issues/19660)) ([39d1262](https://github.com/ionic-team/ionic/commit/39d12629dbc12e4a86037b09350ec1c49ed6e2e4)), closes [#19659](https://github.com/ionic-team/ionic/issues/19659)
* **popover:** allow arrow configuration with controller approach ([#24512](https://github.com/ionic-team/ionic/issues/24512)) ([b39003a](https://github.com/ionic-team/ionic/commit/b39003a4c67cd7e01d09be012c9e12d99ca1730a)), closes [#24487](https://github.com/ionic-team/ionic/issues/24487)
* **popover:** allow arrow on desktop ([#25056](https://github.com/ionic-team/ionic/issues/25056)) ([bcd00c7](https://github.com/ionic-team/ionic/commit/bcd00c7a6ebb6a00193f04458976ff8b86395215))
* **popover:** default alignment to 'center' for ios mode ([#24815](https://github.com/ionic-team/ionic/issues/24815)) ([243f673](https://github.com/ionic-team/ionic/commit/243f67362f25699bdb373be6b72cb9c14dc95a32))
* **popover:** dismissing nested popover via backdrop now works ([#24957](https://github.com/ionic-team/ionic/issues/24957)) ([9e84ef7](https://github.com/ionic-team/ionic/commit/9e84ef7f91d76ca5a1ecaffc7592287267d5368b)), closes [#24954](https://github.com/ionic-team/ionic/issues/24954)
* **popover:** fix keyboard arrow navigation ([#23709](https://github.com/ionic-team/ionic/issues/23709)) ([f2e7a26](https://github.com/ionic-team/ionic/commit/f2e7a267973a06b50a0f6dcbba0a204930bccf69)), closes [#23512](https://github.com/ionic-team/ionic/issues/23512)
* **popover:** handle scrolling in content so header can be sticky ([#24294](https://github.com/ionic-team/ionic/issues/24294)) ([f6a00ea](https://github.com/ionic-team/ionic/commit/f6a00ea9544aa70620b5f8f65a7702fa3bedd974))
* **popover:** only focus trap ion-item children ([#24990](https://github.com/ionic-team/ionic/issues/24990)) ([0cd06a6](https://github.com/ionic-team/ionic/commit/0cd06a675474e1893b4c0801fab8ab79813537c8)), closes [#24633](https://github.com/ionic-team/ionic/issues/24633)
* **popover:** shadow parts now correctly added ([#23446](https://github.com/ionic-team/ionic/issues/23446)) ([e1a9613](https://github.com/ionic-team/ionic/commit/e1a96130ebab1e481e880f0f3876f421976f08d5))
* **popover:** size property now works when providing only event ([#23532](https://github.com/ionic-team/ionic/issues/23532)) ([bdc1f23](https://github.com/ionic-team/ionic/commit/bdc1f2360d7795472cc242a86eb4376d05fa0bb7)), closes [#23528](https://github.com/ionic-team/ionic/issues/23528)
* **popover:** update animation to better match MD spec ([#23541](https://github.com/ionic-team/ionic/issues/23541)) ([bdb95b7](https://github.com/ionic-team/ionic/commit/bdb95b7b6dd798cbc6d1786ae54fa95ac1dfd096))
* **popover:** update prop defaults, use correct delegate ([#23340](https://github.com/ionic-team/ionic/issues/23340)) ([960778a](https://github.com/ionic-team/ionic/commit/960778a36f6eb6318cc740c4f7a255107723b8fd))
* **popover:** use alignment with popover options ([#24711](https://github.com/ionic-team/ionic/issues/24711)) ([f5c5c3c](https://github.com/ionic-team/ionic/commit/f5c5c3cffa4f34046b0e9471a9f193db3772180e)), closes [#24709](https://github.com/ionic-team/ionic/issues/24709)
* **progress-bar:** add width transition ([#22964](https://github.com/ionic-team/ionic/issues/22964)) ([8c1646a](https://github.com/ionic-team/ionic/commit/8c1646a105aba24c426954103037bc51f4d0d430))
* **progress-bar:** use correct theme colors in dark mode ([#22957](https://github.com/ionic-team/ionic/issues/22957)) ([26285bb](https://github.com/ionic-team/ionic/commit/26285bbc9150cf618386dec3915f37b392ed8d53)), closes [#20098](https://github.com/ionic-team/ionic/issues/20098)
* **progress-bar:** use correct theme colors in dark mode ([#22965](https://github.com/ionic-team/ionic/issues/22965)) ([b6b2714](https://github.com/ionic-team/ionic/commit/b6b2714d70f71255315510c5e49708944875db72)), closes [#20098](https://github.com/ionic-team/ionic/issues/20098)
* properly scroll to input with scroll assist ([#20742](https://github.com/ionic-team/ionic/issues/20742)) ([e24060e](https://github.com/ionic-team/ionic/commit/e24060ecd9d803ece4bbb9c6beae23e761d7fb5e)), closes [#19589](https://github.com/ionic-team/ionic/issues/19589)
* **radio-group:** pressing space no longer jumps screen to bottom of page ([#22892](https://github.com/ionic-team/ionic/issues/22892)) ([3a0465e](https://github.com/ionic-team/ionic/commit/3a0465e7d6f9e3cb01336a8bdbd7001e4ec34559)), closes [#22716](https://github.com/ionic-team/ionic/issues/22716)
* **radio-group:** pressing spacebar correctly unselects radio with allow-empty-selection ([#23194](https://github.com/ionic-team/ionic/issues/23194)) ([7139b3f](https://github.com/ionic-team/ionic/commit/7139b3f39e8eeef07ff7c595940fc5dafe062956)), closes [#22734](https://github.com/ionic-team/ionic/issues/22734)
* **radio:** do not clear value of radio group from radio ([#20343](https://github.com/ionic-team/ionic/issues/20343)) ([ff78e6e](https://github.com/ionic-team/ionic/commit/ff78e6e8ca8ae4dc2a6d401b377dd3977c48824a)), closes [#20323](https://github.com/ionic-team/ionic/issues/20323)
* **radio:** fix radio not showing checked state when not in a group ([#24423](https://github.com/ionic-team/ionic/issues/24423)) ([94a781c](https://github.com/ionic-team/ionic/commit/94a781cb6a3d92c5e6cab1a7603bfe25826a753c))
* **radio:** properly announce radios on screen readers and resolve axe errors ([#22507](https://github.com/ionic-team/ionic/issues/22507)) ([afcc46e](https://github.com/ionic-team/ionic/commit/afcc46e1cc4d7f6e9d1a50f8b367da4b1d0c3143))
* **radio:** set default radio value if undefined ([#20329](https://github.com/ionic-team/ionic/issues/20329)) ([eb57723](https://github.com/ionic-team/ionic/commit/eb57723785ce5b05585bf48bf9c8ae1b62235ba2))
* **radio:** update to follow accessibility guidelines outlined by wai-aria ([#22113](https://github.com/ionic-team/ionic/issues/22113)) ([ea0e049](https://github.com/ionic-team/ionic/commit/ea0e0499e24865faad3d11f50f7037645f6cdcc8)), closes [#21743](https://github.com/ionic-team/ionic/issues/21743)
* **range:** dragging knob no longer scrolls page ([#25343](https://github.com/ionic-team/ionic/issues/25343)) ([0b92dff](https://github.com/ionic-team/ionic/commit/0b92dffa92c05705ff83518c10608e3dc3651d51)), closes [#19004](https://github.com/ionic-team/ionic/issues/19004)
* **range:** gesture is now properly re-created on connectedCallback ([#22407](https://github.com/ionic-team/ionic/issues/22407)) ([2fea36f](https://github.com/ionic-team/ionic/commit/2fea36fc98f772443a6560a9491f2f0e574366d1)), closes [#22335](https://github.com/ionic-team/ionic/issues/22335)
* **range:** knob can now have an accessible name ([#23338](https://github.com/ionic-team/ionic/issues/23338)) ([881dcff](https://github.com/ionic-team/ionic/commit/881dcff40b8bdcb07b27d4ee812ce4ee64b6ea9a)), closes [#23295](https://github.com/ionic-team/ionic/issues/23295)
* **range:** properly display stacked labels in an item with a range ([#21944](https://github.com/ionic-team/ionic/issues/21944)) ([9f4b01e](https://github.com/ionic-team/ionic/commit/9f4b01e17fd2f5e742d32bc9e080b6b394c43d37)), closes [#21625](https://github.com/ionic-team/ionic/issues/21625)
* **range:** setting dir on ion-range to enable rtl mode now supported ([#24597](https://github.com/ionic-team/ionic/issues/24597)) ([5dba4e5](https://github.com/ionic-team/ionic/commit/5dba4e5ce0a07f69a08f2b427e8010b311910f88)), closes [#20201](https://github.com/ionic-team/ionic/issues/20201)
* **react, vue:** remove sideeffects to improve treeshaking ([#24313](https://github.com/ionic-team/ionic/issues/24313)) ([13d4418](https://github.com/ionic-team/ionic/commit/13d4418588b98d301b05ebd94e0eac670163a553))
* **react, vue:** scroll is no longer interrupted on ios ([#24791](https://github.com/ionic-team/ionic/issues/24791)) ([99c91ef](https://github.com/ionic-team/ionic/commit/99c91eff8764c9a1630adedab6a9765dd9754f7d)), closes [#24435](https://github.com/ionic-team/ionic/issues/24435)
* **react,vue:** backdrop for inline modal/popover overlay ([#24453](https://github.com/ionic-team/ionic/issues/24453)) ([77f8412](https://github.com/ionic-team/ionic/commit/77f8412b746222793cd9d17f12f50d512ab5e886)), closes [#24449](https://github.com/ionic-team/ionic/issues/24449)
* **react:** building app for production now works correctly with vite ([#24515](https://github.com/ionic-team/ionic/issues/24515)) ([32fad3d](https://github.com/ionic-team/ionic/commit/32fad3d02cb6b012a772de03eafe3e3a6b1300e0)), closes [#24229](https://github.com/ionic-team/ionic/issues/24229)
* **react:** fixing type of icon in ToastOptions, ActionSheetOptions, fixes [#20100](https://github.com/ionic-team/ionic/issues/20100) ([432887b](https://github.com/ionic-team/ionic/commit/432887b410b1e209e7fcdf93f4ff9d661b2c21a9))
* **react:** improve component compatibility with preact ([#24132](https://github.com/ionic-team/ionic/issues/24132)) ([15fc293](https://github.com/ionic-team/ionic/commit/15fc293d75aa21426616459c2596b46e2d460f49)), closes [#23516](https://github.com/ionic-team/ionic/issues/23516)
* **react:** overlays shown with useIonModal and useIonPopover no longer render outside of main react tree ([f3e492c](https://github.com/ionic-team/ionic/commit/f3e492c897c8cda2b98050156f130654f4d7014a)), closes [#23516](https://github.com/ionic-team/ionic/issues/23516) [#23516](https://github.com/ionic-team/ionic/issues/23516)
* **refresher:** add correct dark mode styles ([#22639](https://github.com/ionic-team/ionic/issues/22639)) ([c05476b](https://github.com/ionic-team/ionic/commit/c05476b88e3e6884b4c490461c9c67dee3dca83d)), closes [#22637](https://github.com/ionic-team/ionic/issues/22637)
* **refresher:** add correct fallbacks for native refreshers ([#20333](https://github.com/ionic-team/ionic/issues/20333)) ([fd55427](https://github.com/ionic-team/ionic/commit/fd55427991e94488d86971aaa10acb13d7fa1c23))
* **refresher:** attach scroll listener to custom scroll target ([#25335](https://github.com/ionic-team/ionic/issues/25335)) ([8f5e4cd](https://github.com/ionic-team/ionic/commit/8f5e4cd9350b10a98afb7c98353c6719eee918bb)), closes [#25318](https://github.com/ionic-team/ionic/issues/25318)
* **refresher:** clean up old css if calling refresh method before native refresher is setup ([#22640](https://github.com/ionic-team/ionic/issues/22640)) ([8d5ed47](https://github.com/ionic-team/ionic/commit/8d5ed47a282f92a60a2c4126a673cc2a5733067e)), closes [#22636](https://github.com/ionic-team/ionic/issues/22636)
* **refresher:** correctly detect spinner when using native refresher ([#22800](https://github.com/ionic-team/ionic/issues/22800)) ([e2d8e5c](https://github.com/ionic-team/ionic/commit/e2d8e5c4dcf893ddd8aaa556c1dd8fcaf52411c9)), closes [#22706](https://github.com/ionic-team/ionic/issues/22706)
* **refresher:** correctly select shadow root on older browsers ([#21237](https://github.com/ionic-team/ionic/issues/21237)) ([f23f1cb](https://github.com/ionic-team/ionic/commit/f23f1cb37eef02307c357fbb48c0db729974cdc4))
* **refresher:** ensure gesture does not interfere with item-sliding ([#20380](https://github.com/ionic-team/ionic/issues/20380)) ([8983c70](https://github.com/ionic-team/ionic/commit/8983c7006e54743873cd45ae1acdfa974d74547a)), closes [#20379](https://github.com/ionic-team/ionic/issues/20379)
* **refresher:** ensure that translate is cleaned up to avoid stacking context ([#20621](https://github.com/ionic-team/ionic/issues/20621)) ([e3e5c69](https://github.com/ionic-team/ionic/commit/e3e5c69681f376cbc4b1305f719fc6895b21a9b7)), closes [#17949](https://github.com/ionic-team/ionic/issues/17949)
* **refresher:** import icons to avoid errors in react and vue ([#24525](https://github.com/ionic-team/ionic/issues/24525)) ([388622f](https://github.com/ionic-team/ionic/commit/388622f9734b7b832bca3ede99820a7124faa618)), closes [#24480](https://github.com/ionic-team/ionic/issues/24480)
* **refresher:** ios native refresher now works in side menu ([#22449](https://github.com/ionic-team/ionic/issues/22449)) ([a4a6453](https://github.com/ionic-team/ionic/commit/a4a64530ff083b83187b293dfdacb0fa45ad9f51))
* **refresher:** progressEnd no longer errors when pulling quickly in MD native refresher ([#23056](https://github.com/ionic-team/ionic/issues/23056)) ([67617fb](https://github.com/ionic-team/ionic/commit/67617fbc0f7ec825f1fa4c6e7e2da70e3fcd2d66))
* **refresher:** properly calculate content dimensions in native ion-refresher ([#21157](https://github.com/ionic-team/ionic/issues/21157)) ([83dcc71](https://github.com/ionic-team/ionic/commit/83dcc7168a48bc5b05583fb7c01b5eff9d1a67f8))
* **refresher:** properly dismiss refresher when completed synchronously ([#20815](https://github.com/ionic-team/ionic/issues/20815)) ([b1a87c8](https://github.com/ionic-team/ionic/commit/b1a87c88923201fd0b31bf55d81b97acc09ddf1c)), closes [#20803](https://github.com/ionic-team/ionic/issues/20803)
* **refresher:** refresher completes even after switching to a new tab ([#21236](https://github.com/ionic-team/ionic/issues/21236)) ([1e6f923](https://github.com/ionic-team/ionic/commit/1e6f92377aaf0804cfd0ddb9b06da7b4c9dc355f))
* **refresher:** refresher correctly detects native refresher when shown asynchronously ([#22623](https://github.com/ionic-team/ionic/issues/22623)) ([5ed73cd](https://github.com/ionic-team/ionic/commit/5ed73cdf4d63eeee25ef28d9676fcaa4f8e07b47)), closes [#22616](https://github.com/ionic-team/ionic/issues/22616)
* **refresher:** refresher gesture now works in side menu ([#22446](https://github.com/ionic-team/ionic/issues/22446)) ([6b817f2](https://github.com/ionic-team/ionic/commit/6b817f26b08d01d8367d16308db775b6192e7628)), closes [#20832](https://github.com/ionic-team/ionic/issues/20832)
* **refresher:** refresher now only activates when pulling down on MD ([#23283](https://github.com/ionic-team/ionic/issues/23283)) ([1e1596f](https://github.com/ionic-team/ionic/commit/1e1596f471e440085bf2d90e473f0cb0c0dcf6e2)), closes [#23245](https://github.com/ionic-team/ionic/issues/23245)
* **refresher:** resolve undefined issues when updating component ([#20322](https://github.com/ionic-team/ionic/issues/20322)) ([59d8687](https://github.com/ionic-team/ionic/commit/59d86873a2ab913358b084bb05180ba176893a8f)), closes [#20320](https://github.com/ionic-team/ionic/issues/20320)
* **refresher:** translate background content when refreshing ([#20378](https://github.com/ionic-team/ionic/issues/20378)) ([cf70916](https://github.com/ionic-team/ionic/commit/cf7091625ecb46c3f9882ae9eff5c946523fab75)), closes [#20377](https://github.com/ionic-team/ionic/issues/20377)
* **refresher:** update animation for dashed property values ([#20310](https://github.com/ionic-team/ionic/issues/20310)) ([44211c1](https://github.com/ionic-team/ionic/commit/44211c11ee929b9966d5e67e99fb6a495380432c))
* **refresher:** work properly in modal by waiting for content to be ready ([#22390](https://github.com/ionic-team/ionic/issues/22390)) ([91d0414](https://github.com/ionic-team/ionic/commit/91d041485cb3565fa81fea24c1811e48108f277a)), closes [#22256](https://github.com/ionic-team/ionic/issues/22256)
* **reorder-group:** dragging reorder item to bottom no longer gives out of bounds index ([#23797](https://github.com/ionic-team/ionic/issues/23797)) ([02409f2](https://github.com/ionic-team/ionic/commit/02409f2abfa8acbab05d0f1217b9d1c13721746e)), closes [#23796](https://github.com/ionic-team/ionic/issues/23796)
* **reorder-group:** revert item to original position when passing false to complete ([#21396](https://github.com/ionic-team/ionic/issues/21396)) ([5f2001c](https://github.com/ionic-team/ionic/commit/5f2001c43c0846ec8973cbb8eb5662976ba7e31a)), closes [#19128](https://github.com/ionic-team/ionic/issues/19128)
* **reorder-group:** wait for content to render before getting scroll position ([#24007](https://github.com/ionic-team/ionic/issues/24007)) ([225a278](https://github.com/ionic-team/ionic/commit/225a2787407c5ce68a953ee3448647d00af26517)), closes [#23875](https://github.com/ionic-team/ionic/issues/23875)
* **reorder:** allow click event propagation when reorder group is disabled ([#21947](https://github.com/ionic-team/ionic/issues/21947)) ([baafe08](https://github.com/ionic-team/ionic/commit/baafe08927b7b858170496605781e6fa682e0147)), closes [#21017](https://github.com/ionic-team/ionic/issues/21017)
* **ripple-effect:** ripple displays on click or touch ([#25102](https://github.com/ionic-team/ionic/issues/25102)) ([2a313e9](https://github.com/ionic-team/ionic/commit/2a313e91179e19660a758470ed2218bbcf03e0bb)), closes [#25094](https://github.com/ionic-team/ionic/issues/25094)
* **router-outlet:** getRouteId() returns the params set in setRouteId(). ([#24656](https://github.com/ionic-team/ionic/issues/24656)) ([be2205e](https://github.com/ionic-team/ionic/commit/be2205e5a2b2f8778bd1f7b4ea5cae0bf96f9ef3)), closes [#24652](https://github.com/ionic-team/ionic/issues/24652)
* **router-outlet:** improve reliability of swipe back gesture when quickly swiping back ([#23527](https://github.com/ionic-team/ionic/issues/23527)) ([fa06942](https://github.com/ionic-team/ionic/commit/fa069424b265891852a07869b6d086a1cb041e93)), closes [#22895](https://github.com/ionic-team/ionic/issues/22895)
* **router-outlet:** navigating to same route with different params now activates component ([#24760](https://github.com/ionic-team/ionic/issues/24760)) ([abc36ae](https://github.com/ionic-team/ionic/commit/abc36ae80b060a659f7557ad90efe98b78f5ead9)), closes [#24653](https://github.com/ionic-team/ionic/issues/24653)
* **router:** account for query string when pushing page ([#21071](https://github.com/ionic-team/ionic/issues/21071)) ([eab3373](https://github.com/ionic-team/ionic/commit/eab33732133bd43ca6788bba6e93a9b545ee058a))
* **router:** going back uses correct nav transition ([#21301](https://github.com/ionic-team/ionic/issues/21301)) ([c8db0d5](https://github.com/ionic-team/ionic/commit/c8db0d5eeba6f10d1492e95e6df6b4d871d43400))
* **router:** guards are now triggered on initial navigation ([#23123](https://github.com/ionic-team/ionic/issues/23123)) ([56f6f56](https://github.com/ionic-team/ionic/commit/56f6f56c6665f40ea6bf41be463cd416883359f7)), closes [#22936](https://github.com/ionic-team/ionic/issues/22936)
* **router:** navigation guards now fire when navigating to a page with params ([#22521](https://github.com/ionic-team/ionic/issues/22521)) ([1956f98](https://github.com/ionic-team/ionic/commit/1956f9896883dc4687488e5418e50ce0f6cbe6c9)), closes [#22516](https://github.com/ionic-team/ionic/issues/22516)
* **router:** popping route now accounts for route params ([#24315](https://github.com/ionic-team/ionic/issues/24315)) ([5e5054d](https://github.com/ionic-team/ionic/commit/5e5054d369ad68c9ac43e12439d71fb42d6ca26b))
* **router:** redirects now account for query string ([#23337](https://github.com/ionic-team/ionic/issues/23337)) ([08a9f3a](https://github.com/ionic-team/ionic/commit/08a9f3ac94685c5782dd2fa6b56bf3448729a768)), closes [#23136](https://github.com/ionic-team/ionic/issues/23136)
* **router:** router push with relative path ([#24719](https://github.com/ionic-team/ionic/issues/24719)) ([d40c0c3](https://github.com/ionic-team/ionic/commit/d40c0c3a0993eaefbe5107e98958c6b0699a62c2)), closes [#24718](https://github.com/ionic-team/ionic/issues/24718)
* **router:** simplify param merging ([#22999](https://github.com/ionic-team/ionic/issues/22999)) ([4ce62b2](https://github.com/ionic-team/ionic/commit/4ce62b26a8bb7fad0f704c3c4c4b8e4b03b110b5))
* scroll assist no longer prevents first click event from firing ([#22845](https://github.com/ionic-team/ionic/issues/22845)) ([f7d4c21](https://github.com/ionic-team/ionic/commit/f7d4c21b64e27f9b655bc1ab2522d6357dc6010f)), closes [#21871](https://github.com/ionic-team/ionic/issues/21871)
* scroll assists now recognizes inputs on inner pages and modals ([#20864](https://github.com/ionic-team/ionic/issues/20864)) ([d3d7de1](https://github.com/ionic-team/ionic/commit/d3d7de121be7bc69e5bbf4667158e5c5f945a925)), closes [#20843](https://github.com/ionic-team/ionic/issues/20843)
* **scroll-assist:** improve scroll detection accuracy ([#21416](https://github.com/ionic-team/ionic/issues/21416)) ([137c49d](https://github.com/ionic-team/ionic/commit/137c49d70be45e1b0ee73d41fed6e9d69a2caa32))
* **scroll-assist:** touch end events continue to bubble on inputs ([#25282](https://github.com/ionic-team/ionic/issues/25282)) ([780f16d](https://github.com/ionic-team/ionic/commit/780f16d9e04ee5aaaf91bb7c6ef15c72cc8aeb45)), closes [#25229](https://github.com/ionic-team/ionic/issues/25229)
* **searchbar:** properly align placeholder ([#20460](https://github.com/ionic-team/ionic/issues/20460)) ([4d6e15a](https://github.com/ionic-team/ionic/commit/4d6e15ab18fc894c3826b89362163256adc227f4)), closes [#20456](https://github.com/ionic-team/ionic/issues/20456)
* **searchbar:** screen readers correctly announce the cancel button text ([#21049](https://github.com/ionic-team/ionic/issues/21049)) ([15a603b](https://github.com/ionic-team/ionic/commit/15a603b39797dee6baf7e33d58907f98ced7e86d)), closes [#21013](https://github.com/ionic-team/ionic/issues/21013)
* **searchbar:** setting dir on ion-searchbar to enable rtl mode now supported ([#24602](https://github.com/ionic-team/ionic/issues/24602)) ([35e5235](https://github.com/ionic-team/ionic/commit/35e523564561c0f3323efa761c4654016b97ef69))
* **searchbar:** showClearButton now defaults to 'always' for improved usability with screen readers ([#23475](https://github.com/ionic-team/ionic/issues/23475)) ([80f181d](https://github.com/ionic-team/ionic/commit/80f181d4846507ee6bd4150bb568fca9b6660428))
* **segment-button:** allow min-width to be overridden ([#21722](https://github.com/ionic-team/ionic/issues/21722)) ([88f1828](https://github.com/ionic-team/ionic/commit/88f1828bd8f6b9a1c1f3dcb220d93067bed7f404)), closes [#21105](https://github.com/ionic-team/ionic/issues/21105)
* **segment-button:** color property is now reactive if previously undefined ([#22405](https://github.com/ionic-team/ionic/issues/22405)) ([04161c9](https://github.com/ionic-team/ionic/commit/04161c9512ed8e965c93698d7f5501a21485052f)), closes [#20831](https://github.com/ionic-team/ionic/issues/20831)
* **segment-button:** screen readers now announce selected state properly ([#21273](https://github.com/ionic-team/ionic/issues/21273)) ([85cc35e](https://github.com/ionic-team/ionic/commit/85cc35ee9163a38c48c6df466a3c036906437804))
* **segment, segment-button:** use correct tablist and tab roles for screen readers ([#23145](https://github.com/ionic-team/ionic/issues/23145)) ([91ac340](https://github.com/ionic-team/ionic/commit/91ac340ae7e8928f7b0972a093dd9dd7fa727671))
* **segment:** add activated class directly to segment button ([#20400](https://github.com/ionic-team/ionic/issues/20400)) ([e8886e9](https://github.com/ionic-team/ionic/commit/e8886e98f188044227bf5757892341cb598fdd27))
* **segment:** allow background to be set on iOS segment in a toolbar ([#20350](https://github.com/ionic-team/ionic/issues/20350)) ([0f31624](https://github.com/ionic-team/ionic/commit/0f31624104d195367df197eda9b8d6c5bda4cf75))
* **segment:** allow routerLink to work on segment buttons ([#20682](https://github.com/ionic-team/ionic/issues/20682)) ([314dbb1](https://github.com/ionic-team/ionic/commit/314dbb1a4d970327fcbb2f3fbdec0627c626fe4d)), closes [#20678](https://github.com/ionic-team/ionic/issues/20678)
* **segment:** automatically expand width for scrollable segment buttons ([#20763](https://github.com/ionic-team/ionic/issues/20763)) ([cdfd50b](https://github.com/ionic-team/ionic/commit/cdfd50b554d1d8f89c3d9948c7613ce75ede1e52)), closes [#20566](https://github.com/ionic-team/ionic/issues/20566)
* **segment:** border radius applies to indicator on ios ([#20541](https://github.com/ionic-team/ionic/issues/20541)) ([9b5854d](https://github.com/ionic-team/ionic/commit/9b5854d79712356f8a3772442c0cc412db09d5e0)), closes [#20539](https://github.com/ionic-team/ionic/issues/20539)
* **segment:** clicking disabled button no longer adds ripple to active button ([#20254](https://github.com/ionic-team/ionic/issues/20254)) ([f896821](https://github.com/ionic-team/ionic/commit/f8968217533ff60948047510064d2f15d01c249c)), closes [#20253](https://github.com/ionic-team/ionic/issues/20253)
* **segment:** do not allow text selection on desktop ([#22158](https://github.com/ionic-team/ionic/issues/22158)) ([1526bdf](https://github.com/ionic-team/ionic/commit/1526bdfb492c1fa8d71f8a1af8cd97abd9e62642))
* **segment:** do not show ripple effect if disabled via config ([#20542](https://github.com/ionic-team/ionic/issues/20542)) ([7a461c5](https://github.com/ionic-team/ionic/commit/7a461c59c5d9a23de0bcdd53397f452d17251fd6)), closes [#20533](https://github.com/ionic-team/ionic/issues/20533)
* **segment:** ensure checked classes get set after not having a value ([#21547](https://github.com/ionic-team/ionic/issues/21547)) ([17308f2](https://github.com/ionic-team/ionic/commit/17308f247f8750029ece39548c9f457e15326189))
* **segment:** inner div no longer interferes with click events ([#20522](https://github.com/ionic-team/ionic/issues/20522)) ([06b828b](https://github.com/ionic-team/ionic/commit/06b828b4ffb12b076b0805274f53fa158ee65c5a)), closes [#20381](https://github.com/ionic-team/ionic/issues/20381)
* **segment:** iOS mode segment now works on older Android devices ([#20673](https://github.com/ionic-team/ionic/issues/20673)) ([44993b7](https://github.com/ionic-team/ionic/commit/44993b7987031b6618409675fdbb1f15ec4ea343)), closes [#20648](https://github.com/ionic-team/ionic/issues/20648)
* **segment:** only emit ionChange when user releases pointer from screen ([#20495](https://github.com/ionic-team/ionic/issues/20495)) ([4d50064](https://github.com/ionic-team/ionic/commit/4d5006476479bc376d3bb4edad6db0b3ce806ef7)), closes [#20500](https://github.com/ionic-team/ionic/issues/20500) [#20257](https://github.com/ionic-team/ionic/issues/20257)
* **segment:** scrollable segments only show scrollbar if they overflow ([#20760](https://github.com/ionic-team/ionic/issues/20760)) ([ab146c9](https://github.com/ionic-team/ionic/commit/ab146c96ec5cbc962eed629c30b2c5c446f3098d)), closes [#20758](https://github.com/ionic-team/ionic/issues/20758)
* **segment:** segment functions properly on android 5 ([#20554](https://github.com/ionic-team/ionic/issues/20554)) ([0224bed](https://github.com/ionic-team/ionic/commit/0224bed0c9f91bcb54bb4b3064df56928cf5ed8a)), closes [#20466](https://github.com/ionic-team/ionic/issues/20466)
* **segment:** setting dir on ion-segment to enable rtl mode now supported ([#24601](https://github.com/ionic-team/ionic/issues/24601)) ([2940e73](https://github.com/ionic-team/ionic/commit/2940e73a4504247eecb0de6c433104f529530850)), closes [#23978](https://github.com/ionic-team/ionic/issues/23978)
* **select-popover:** non-scrollable popovers no longer have forced overscroll ([#23972](https://github.com/ionic-team/ionic/issues/23972)) ([aa4ba89](https://github.com/ionic-team/ionic/commit/aa4ba890e9c18e8a911c5188b3e2e85433658be9)), closes [#23971](https://github.com/ionic-team/ionic/issues/23971)
* **select:** account for MutationObserver when performing SSR ([#21068](https://github.com/ionic-team/ionic/issues/21068)) ([66e8e64](https://github.com/ionic-team/ionic/commit/66e8e6404d87a2767e71b13bed19706b29ad1b9c)), closes [#21063](https://github.com/ionic-team/ionic/issues/21063)
* **select:** add icon-inner & placeholder part ([#20605](https://github.com/ionic-team/ionic/issues/20605)) ([926ac3f](https://github.com/ionic-team/ionic/commit/926ac3fb47228be19146ccdfab92a05cf6677ff4))
* **select:** avoid duplicate dialogs and backdrops when clicking ([#25175](https://github.com/ionic-team/ionic/issues/25175)) ([70d2784](https://github.com/ionic-team/ionic/commit/70d278414eb5124d17c5ffaba5231c6bfd285656)), closes [#25126](https://github.com/ionic-team/ionic/issues/25126)
* **select:** change role to listbox ([#21609](https://github.com/ionic-team/ionic/issues/21609)) ([8c79e2c](https://github.com/ionic-team/ionic/commit/8c79e2c5b58ad562967f2d559c6b548e57536936))
* **select:** class on component now indicates when select is open ([#22846](https://github.com/ionic-team/ionic/issues/22846)) ([1a5accc](https://github.com/ionic-team/ionic/commit/1a5accc5f707f84063469c0bd3e5e153489f1e5d)), closes [#22801](https://github.com/ionic-team/ionic/issues/22801)
* **select:** do not close popover or set value when switching with arrow keys ([#22210](https://github.com/ionic-team/ionic/issues/22210)) ([1878c8e](https://github.com/ionic-team/ionic/commit/1878c8e7e01c02f06bdc5f1562af0d45531539cf)), closes [#22179](https://github.com/ionic-team/ionic/issues/22179)
* **select:** ensure popover options with number values are searched for correctly ([#23998](https://github.com/ionic-team/ionic/issues/23998)) ([c204083](https://github.com/ionic-team/ionic/commit/c20408369bd332b5e225a3d50ec94978f6f5ec97))
* **select:** fix a11y issues with axe and screen readers ([#22494](https://github.com/ionic-team/ionic/issues/22494)) ([04b874e](https://github.com/ionic-team/ionic/commit/04b874e32a65588ca79eda9399ab7e9d86a3cb77)), closes [#21552](https://github.com/ionic-team/ionic/issues/21552) [#21548](https://github.com/ionic-team/ionic/issues/21548)
* **select:** focus selected item in popovers ([#23991](https://github.com/ionic-team/ionic/issues/23991)) ([2497a53](https://github.com/ionic-team/ionic/commit/2497a53255dc43052755bba842dfcf556d930dcd))
* **select:** improvements for announcing placeholder and value on screenreaders ([#22556](https://github.com/ionic-team/ionic/issues/22556)) ([ea52db6](https://github.com/ionic-team/ionic/commit/ea52db66f05a185fed6b2e849734a7ffa1c6c6ea))
* **select:** interface components now show correctly ([#24810](https://github.com/ionic-team/ionic/issues/24810)) ([2fc2de5](https://github.com/ionic-team/ionic/commit/2fc2de51771f4a5c3f20c6071284096e5bf31ec8)), closes [#24807](https://github.com/ionic-team/ionic/issues/24807)
* **select:** properly align label with select in item in md ([#22330](https://github.com/ionic-team/ionic/issues/22330)) ([1a2e532](https://github.com/ionic-team/ionic/commit/1a2e5322fb7ac0dd6bd3d0705b8e32f9d3649bfc)), closes [#19887](https://github.com/ionic-team/ionic/issues/19887)
* **select:** value is selected when given array ([#24687](https://github.com/ionic-team/ionic/issues/24687)) ([6ee7d15](https://github.com/ionic-team/ionic/commit/6ee7d159ecfff3382fadb524c5c430172d40c267)), closes [#24742](https://github.com/ionic-team/ionic/issues/24742)
* **skeleton-text:** animation no longer jumps on large skeleton text elements ([#22697](https://github.com/ionic-team/ionic/issues/22697)) ([1a36922](https://github.com/ionic-team/ionic/commit/1a36922f41f2890c778feedbad9c5b74a72a3907)), closes [#22694](https://github.com/ionic-team/ionic/issues/22694)
* **slides:** check that mutation observer is defined for ssr ([#20791](https://github.com/ionic-team/ionic/issues/20791)) ([2d5d251](https://github.com/ionic-team/ionic/commit/2d5d2515be86496a280d93847185ab332e5d47a2))
* **slides:** enable keyboard integration ([#21608](https://github.com/ionic-team/ionic/issues/21608)) ([26674f1](https://github.com/ionic-team/ionic/commit/26674f1dfa8c9a28f5525f1b16070e8ec494c232)), closes [#21554](https://github.com/ionic-team/ionic/issues/21554)
* **slides:** resolve prototype pollution in swiper v5 ([#23344](https://github.com/ionic-team/ionic/issues/23344)) ([a708c41](https://github.com/ionic-team/ionic/commit/a708c412625cba475ec7863468dcc2146b8feb7a)), closes [#23342](https://github.com/ionic-team/ionic/issues/23342)
* **slides:** set height to 100% for vertical slides ([#20603](https://github.com/ionic-team/ionic/issues/20603)) ([20af652](https://github.com/ionic-team/ionic/commit/20af652a1be5e1aff2836422489642c8baed6939)), closes [#17341](https://github.com/ionic-team/ionic/issues/17341)
* **slides:** slides no longer breaks when Angular Ivy enabled ([#20899](https://github.com/ionic-team/ionic/issues/20899)) ([3123a31](https://github.com/ionic-team/ionic/commit/3123a318b6755dbf8fde8476f81c37e6ffa9b70e)), closes [#20356](https://github.com/ionic-team/ionic/issues/20356)
* **slides:** undefined error is no longer thrown after destroying and quickly re-creating ion-slides ([#23239](https://github.com/ionic-team/ionic/issues/23239)) ([2ccaabb](https://github.com/ionic-team/ionic/commit/2ccaabb5b4d67ec4b1318e3ccb3edc1bd853ab3e)), closes [#22289](https://github.com/ionic-team/ionic/issues/22289)
* **slides:** update Swiper dependency to resolve error when doing SSR ([#21350](https://github.com/ionic-team/ionic/issues/21350)) ([3290604](https://github.com/ionic-team/ionic/commit/32906048a491961ec7340ba2e085807ea8a9c118))
* **slides:** update swiper instance after initialization ([#24257](https://github.com/ionic-team/ionic/issues/24257)) ([89e4bc5](https://github.com/ionic-team/ionic/commit/89e4bc56a1c3cd4fb26fc5514f38c6a01f047297))
* **spinner:** alignment is now correct in rtl ([#25260](https://github.com/ionic-team/ionic/issues/25260)) ([e3c996d](https://github.com/ionic-team/ionic/commit/e3c996dea878a8dd276a0ca99f59b330125f9b75))
* **spinner:** ensure transform doesn't overwrite circular animation ([#24643](https://github.com/ionic-team/ionic/issues/24643)) ([88ce010](https://github.com/ionic-team/ionic/commit/88ce010418eaca38786b51720c696860b417ab6d))
* **split-pane:** properly show border in rtl mode ([#20995](https://github.com/ionic-team/ionic/issues/20995)) ([7a21708](https://github.com/ionic-team/ionic/commit/7a21708d24bab6a388e1b55c88337e3d0f7922eb)), closes [#20994](https://github.com/ionic-team/ionic/issues/20994)
* **ssr:** reflect content-id attribute ([#20169](https://github.com/ionic-team/ionic/issues/20169)) ([3aa47e6](https://github.com/ionic-team/ionic/commit/3aa47e6e2f18c3a07f2c0560a0946571e8e6815d))
* **status-bar:** tapping status bar correctly scrolls content to top ([#24001](https://github.com/ionic-team/ionic/issues/24001)) ([25eb8cd](https://github.com/ionic-team/ionic/commit/25eb8cdf98fe455433ca6185e89d9e1223a6d3ae)), closes [#20423](https://github.com/ionic-team/ionic/issues/20423)
* **tab-bar:** safe area padding now added when slot="top" ([#23895](https://github.com/ionic-team/ionic/issues/23895)) ([4782969](https://github.com/ionic-team/ionic/commit/47829690b538903b70ad4fe77657404013270263)), closes [#23893](https://github.com/ionic-team/ionic/issues/23893)
* **tab-bar:** update ios icon and label design to match native ([#20548](https://github.com/ionic-team/ionic/issues/20548)) ([34f8576](https://github.com/ionic-team/ionic/commit/34f8576b959d41896502e4f7b0c4240156e001eb))
* **textarea:** add aria-labelledby to native textarea ([#21606](https://github.com/ionic-team/ionic/issues/21606)) ([88f23b1](https://github.com/ionic-team/ionic/commit/88f23b1626eb400336f2f52a3e0d34ac3c161e64)), closes [#21600](https://github.com/ionic-team/ionic/issues/21600)
* **textarea:** do not generate duplicate IDs between ion-input and ion-textarea ([#22074](https://github.com/ionic-team/ionic/issues/22074)) ([c72c7ff](https://github.com/ionic-team/ionic/commit/c72c7ffa983af8885dd93f9adfcb3f2af232d2d9)), closes [#21542](https://github.com/ionic-team/ionic/issues/21542)
* **textarea:** floating label with autogrow textareas ([#24202](https://github.com/ionic-team/ionic/issues/24202)) ([713f0f5](https://github.com/ionic-team/ionic/commit/713f0f55261205d3f7e25874939cb1f998f38d4a))
* **textarea:** height is set correctly when using autoGrow in modals ([#20971](https://github.com/ionic-team/ionic/issues/20971)) ([32ee040](https://github.com/ionic-team/ionic/commit/32ee040e3f0d7012790f190856097d0c6fa0eaa2)), closes [#18993](https://github.com/ionic-team/ionic/issues/18993)
* **textarea:** native textarea inherits max/min width and heights ([#21333](https://github.com/ionic-team/ionic/issues/21333)) ([2377480](https://github.com/ionic-team/ionic/commit/237748049c7644ae8a7a74101ece5cfd7a160470))
* **textarea:** properly adjust auto-grow textarea in scrolled content ([#19776](https://github.com/ionic-team/ionic/issues/19776)) ([8bd5bac](https://github.com/ionic-team/ionic/commit/8bd5bace73670dfe351b3734b51cbf3aa87517dc)), closes [#19193](https://github.com/ionic-team/ionic/issues/19193)
* **title:** allow overriding of large title transform origin ([#21770](https://github.com/ionic-team/ionic/issues/21770)) ([dbe6853](https://github.com/ionic-team/ionic/commit/dbe6853884bd76c3d8e229cd58e1571d9b3a7249)), closes [#21761](https://github.com/ionic-team/ionic/issues/21761)
* **title:** improve reliability of large title ios nav transition ([#20861](https://github.com/ionic-team/ionic/issues/20861)) ([3bd6b5d](https://github.com/ionic-team/ionic/commit/3bd6b5def2877f6a918c587de25a10ccc82f88f1))
* **title:** inherit padding for iOS title in a toolbar ([#23343](https://github.com/ionic-team/ionic/issues/23343)) ([82cfa55](https://github.com/ionic-team/ionic/commit/82cfa5565347704b0e9f7dac792ed2aa6dd30505)), closes [#23072](https://github.com/ionic-team/ionic/issues/23072)
* **title:** large title now inherits global color styling during nav transition ([#20862](https://github.com/ionic-team/ionic/issues/20862)) ([321140f](https://github.com/ionic-team/ionic/commit/321140ff736b46d2631a9e87a7b070009c5e1b2c))
* **title:** large title scale animation is now correct in rtl mode ([#23372](https://github.com/ionic-team/ionic/issues/23372)) ([3d474ec](https://github.com/ionic-team/ionic/commit/3d474ec67ff4192fa3d08e370e20fecbee99a6aa)), closes [#23371](https://github.com/ionic-team/ionic/issues/23371)
* **title:** only add large title transition when using collapsible header ([#22762](https://github.com/ionic-team/ionic/issues/22762)) ([348c50b](https://github.com/ionic-team/ionic/commit/348c50b7ea5d4c74498c5d26e40c1c4fe923ee55)), closes [#22760](https://github.com/ionic-team/ionic/issues/22760)
* **toast, action-sheet:** allow button handler to return `Promise<void>` ([#21259](https://github.com/ionic-team/ionic/issues/21259)) ([7703da2](https://github.com/ionic-team/ionic/commit/7703da28f8181b02390b97a7d4d02df99b2ad34c))
* **toast:** allow input focus while toast is visible ([#24572](https://github.com/ionic-team/ionic/issues/24572)) ([29f1140](https://github.com/ionic-team/ionic/commit/29f1140384ae7e1402b09c3760e168cf79833619)), closes [#24571](https://github.com/ionic-team/ionic/issues/24571)
* **toast:** inherit color in cancel button for a toast with color ([#20299](https://github.com/ionic-team/ionic/issues/20299)) ([7b44ae2](https://github.com/ionic-team/ionic/commit/7b44ae2a400bb0c0616012e9c42bfc67edbfc793)), closes [#20139](https://github.com/ionic-team/ionic/issues/20139)
* **toast:** screen readers now announce toasts when presented ([#24937](https://github.com/ionic-team/ionic/issues/24937)) ([8a97f6b](https://github.com/ionic-team/ionic/commit/8a97f6b5c9ca1e77c1790abd1e924955b6b6ea27)), closes [#22333](https://github.com/ionic-team/ionic/issues/22333)
* **toast:** toast is now correctly excluded from focus trapping ([#24816](https://github.com/ionic-team/ionic/issues/24816)) ([8246112](https://github.com/ionic-team/ionic/commit/8246112ca12f90edb98629ab82e27a792a1fafad)), closes [#24733](https://github.com/ionic-team/ionic/issues/24733)
* **toast:** ToastOptions interface now contains icon prop ([#23737](https://github.com/ionic-team/ionic/issues/23737)) ([fbd32ff](https://github.com/ionic-team/ionic/commit/fbd32ffb2633b17d71a34a8760386a319f2e2bca)), closes [#23736](https://github.com/ionic-team/ionic/issues/23736)
* **toggle:** prevent click event from firing twice ([#23146](https://github.com/ionic-team/ionic/issues/23146)) ([42e6c90](https://github.com/ionic-team/ionic/commit/42e6c90c4632423386b165dddc4b94a55c075e2e)), closes [#23041](https://github.com/ionic-team/ionic/issues/23041)
* **toggle:** screen readers now announce toggle properly ([#21168](https://github.com/ionic-team/ionic/issues/21168)) ([1fbdb22](https://github.com/ionic-team/ionic/commit/1fbdb2255e4ff7fccf22d9ccc12b7f9bb4c3a064))
* **toggle:** setting dir on ion-toggle to enable rtl mode now supported ([#24600](https://github.com/ionic-team/ionic/issues/24600)) ([353dbc0](https://github.com/ionic-team/ionic/commit/353dbc0537ef3b46b9ba13a365ebc5da269de4c7))
* **toggle:** use a native input to fix a11y issues with axe and screen readers ([#22477](https://github.com/ionic-team/ionic/issues/22477)) ([813611a](https://github.com/ionic-team/ionic/commit/813611a61b664c9827760ccaa889d0e2fcae7d94)), closes [#22011](https://github.com/ionic-team/ionic/issues/22011) [#21552](https://github.com/ionic-team/ionic/issues/21552)
* **toolbar:** properly apply safe area and border ([#20375](https://github.com/ionic-team/ionic/issues/20375)) ([4971499](https://github.com/ionic-team/ionic/commit/4971499026fcee70a32cc9480302bb14a1bebcb7)), closes [#20354](https://github.com/ionic-team/ionic/issues/20354)
* **types:** improve intellisense with colors ([#25347](https://github.com/ionic-team/ionic/issues/25347)) ([97cfbbb](https://github.com/ionic-team/ionic/commit/97cfbbb65d3e63c32d720e01c7368c68616bb531))
* **virtual-scroll:** properly calculate top offset when nested ([#21581](https://github.com/ionic-team/ionic/issues/21581)) ([d297ecb](https://github.com/ionic-team/ionic/commit/d297ecb87ad3e1c8f0988f0571a475081ce368f8))
* **vue:** account for event name changes in vue 3.0.6+ ([06d4c8e](https://github.com/ionic-team/ionic/commit/06d4c8e6f1897759b9edc921e453944c4c1d1dbf))
* **vue:** all ionic vue components can now use router link ([#22743](https://github.com/ionic-team/ionic/issues/22743)) ([3d6ac13](https://github.com/ionic-team/ionic/commit/3d6ac1382e23663a3d010fd253d3c6017d3923e4))
* **vue:** components now integrate properly with vee-validate ([#23114](https://github.com/ionic-team/ionic/issues/23114)) ([ba51daf](https://github.com/ionic-team/ionic/commit/ba51daf17c4438aea6826882f82a04ebf8d6a5d8)), closes [#22886](https://github.com/ionic-team/ionic/issues/22886)
* **vue:** correctly handle platform specific icons ([#22200](https://github.com/ionic-team/ionic/issues/22200)) ([25d3ea6](https://github.com/ionic-team/ionic/commit/25d3ea6b8d78016e9122c4ec02016af33a2041e8)), closes [#19078](https://github.com/ionic-team/ionic/issues/19078)
* **vue:** correctly update property values ([#22218](https://github.com/ionic-team/ionic/issues/22218)) ([2527189](https://github.com/ionic-team/ionic/commit/25271897e2a5acd216f4076ab0284bb91023d424)), closes [#22079](https://github.com/ionic-team/ionic/issues/22079)
* **vue:** custom element internal properties are no longer overridden in vue 3.1.0 ([#23738](https://github.com/ionic-team/ionic/issues/23738)) ([ea39c70](https://github.com/ionic-team/ionic/commit/ea39c70b3ec78b2ea5ef64263e8528b543378784)), closes [#23539](https://github.com/ionic-team/ionic/issues/23539)
* **vue:** ensure dynamic classes are synced with internal Ionic component classes ([#22096](https://github.com/ionic-team/ionic/issues/22096)) ([9cb22be](https://github.com/ionic-team/ionic/commit/9cb22be91a232c395780f7ceb50c3e9ae28e7dc2)), closes [#22051](https://github.com/ionic-team/ionic/issues/22051)
* **vue:** ensure v-model value is properly synced before ionChange event ([#22749](https://github.com/ionic-team/ionic/issues/22749)) ([e1d6627](https://github.com/ionic-team/ionic/commit/e1d6627bf0ef1f47f980db1573c6b2a3d16d7677)), closes [#22610](https://github.com/ionic-team/ionic/issues/22610)
* **vue:** improve v-model binding sync between vue wrappers and web components ([#22745](https://github.com/ionic-team/ionic/issues/22745)) ([64719f4](https://github.com/ionic-team/ionic/commit/64719f49f979c0296a01827d3c02599a48ba93a6)), closes [#22731](https://github.com/ionic-team/ionic/issues/22731)
* **vue:** improve v-model integration for Vue 3.1.0+ ([#23420](https://github.com/ionic-team/ionic/issues/23420)) ([f008628](https://github.com/ionic-team/ionic/commit/f0086288512bd7f7d1929d79bfd8bf702efc732e))
* **vue:** ionChange events now propagate correctly ([#22872](https://github.com/ionic-team/ionic/issues/22872)) ([ff0f1da](https://github.com/ionic-team/ionic/commit/ff0f1da9f11915b48c4258af7c48c4513785f3fc)), closes [#22870](https://github.com/ionic-team/ionic/issues/22870)
* **vue:** modal, popover, and nav are now created within application context ([#22282](https://github.com/ionic-team/ionic/issues/22282)) ([6026c65](https://github.com/ionic-team/ionic/commit/6026c65b1ae80af0f8604e7a3bcb220153267955)), closes [#22079](https://github.com/ionic-team/ionic/issues/22079)
* **vue:** overlay events can now be listened for without the "on" prefix, deprecated "on" prefix event listeners ([#23227](https://github.com/ionic-team/ionic/issues/23227)) ([dab927d](https://github.com/ionic-team/ionic/commit/dab927d2901658f4040c1d1aa6c777497d8714c8))
* **vue:** overlays function properly when used via controller or template ([#22155](https://github.com/ionic-team/ionic/issues/22155)) ([fe5fadf](https://github.com/ionic-team/ionic/commit/fe5fadf19cd63087311959c549e7e7c55261b459)), closes [#22090](https://github.com/ionic-team/ionic/issues/22090)
* **vue:** popover positioning is now correct with custom elements build ([#23680](https://github.com/ionic-team/ionic/issues/23680)) ([3a1a9cb](https://github.com/ionic-team/ionic/commit/3a1a9cbce45ad128c9ba87940535dabfa167fb9e))
* **vue:** prevent error from being thrown when testing on certain jest runners ([#23421](https://github.com/ionic-team/ionic/issues/23421)) ([60bedb5](https://github.com/ionic-team/ionic/commit/60bedb5599b286bffccfc54c4861a269d9b8df73)), closes [#23397](https://github.com/ionic-team/ionic/issues/23397)
* **vue:** tab bar is now correctly hidden when keyboard is open ([#22687](https://github.com/ionic-team/ionic/issues/22687)) ([5c27dd8](https://github.com/ionic-team/ionic/commit/5c27dd8032d32ebb57c31e1f6c112dc513344b93))
* **vue:** testing a routerLink-capable component no longer warns of missing router dependency ([#22532](https://github.com/ionic-team/ionic/issues/22532)) ([4e23aad](https://github.com/ionic-team/ionic/commit/4e23aad3d911188e4a2706545463a81332c00ce9)), closes [#22506](https://github.com/ionic-team/ionic/issues/22506)
* **vue:** using refs with v-model now works properly ([#22092](https://github.com/ionic-team/ionic/issues/22092)) ([67fbb3b](https://github.com/ionic-team/ionic/commit/67fbb3b963e2e75284b578777057c0822720fb1e)), closes [#22076](https://github.com/ionic-team/ionic/issues/22076)


### Code Refactoring

* **header:** removed border from last toolbar when using collapsible large title ([#22891](https://github.com/ionic-team/ionic/issues/22891)) ([c72bc5d](https://github.com/ionic-team/ionic/commit/c72bc5dbd76cd3ce622a4b3cedcb7446a2819384)), closes [#22777](https://github.com/ionic-team/ionic/issues/22777)
* **ios:** update toolbar and tabbar default background colors ([#22852](https://github.com/ionic-team/ionic/issues/22852)) ([3d615cb](https://github.com/ionic-team/ionic/commit/3d615cb3c7b233b08b9da6ac04096e16bbb60bfc)), closes [#22780](https://github.com/ionic-team/ionic/issues/22780)
* remove checked property in favor of parent value ([#19449](https://github.com/ionic-team/ionic/issues/19449)) ([a5229d9](https://github.com/ionic-team/ionic/commit/a5229d90ca2a608e8bf4db0c8f71c86d481dd649))
* **toast:** whitespace variable now defaults to normal ([#22866](https://github.com/ionic-team/ionic/issues/22866)) ([9b78689](https://github.com/ionic-team/ionic/commit/9b786899e550c391b9395c669f9bba8f39ac98aa))


### Features

* **accordion-group:** add animated property to disable animations ([#23530](https://github.com/ionic-team/ionic/issues/23530)) ([9a60dd0](https://github.com/ionic-team/ionic/commit/9a60dd0ea7c55acf0fdd1161433e5b4ed40778f2))
* **accordion:** add accordion and accordion-group components ([#22865](https://github.com/ionic-team/ionic/issues/22865)) ([073883a](https://github.com/ionic-team/ionic/commit/073883a0987149e9f6258ca43c46f5ed4bce0dc5)), closes [#17094](https://github.com/ionic-team/ionic/issues/17094)
* **action-sheet, alert:** add id to AlertButton and ActionSheetButton ([#18992](https://github.com/ionic-team/ionic/issues/18992)) ([9e24a0b](https://github.com/ionic-team/ionic/commit/9e24a0b49357a3a39ca89f026ff23271a365d935)), closes [#22959](https://github.com/ionic-team/ionic/issues/22959)
* **action-sheet, loading, modal, picker, popover:** pass HTML attributes to host element ([#23929](https://github.com/ionic-team/ionic/issues/23929)) ([bd96a81](https://github.com/ionic-team/ionic/commit/bd96a81ff80ffe32914804ba9b6234c0286a33db))
* **action-sheet:** add data property to ActionSheetButton ([#23744](https://github.com/ionic-team/ionic/issues/23744)) ([30f8508](https://github.com/ionic-team/ionic/commit/30f8508296cfc8f8b1c03d04b24abfa184624200)), closes [#23700](https://github.com/ionic-team/ionic/issues/23700)
* add ability to continue processing hardware back button events ([#20613](https://github.com/ionic-team/ionic/issues/20613)) ([3821c04](https://github.com/ionic-team/ionic/commit/3821c0463ae9a02e67c835a221c4ea01fab306d1)), closes [#17824](https://github.com/ionic-team/ionic/issues/17824)
* **alert, toast:** pass arbitrary HTML attributes to host element ([#23891](https://github.com/ionic-team/ionic/issues/23891)) ([73a1daf](https://github.com/ionic-team/ionic/commit/73a1daf0aaf6ffe8c7871619f2aec5f6fca1321a)), closes [#23825](https://github.com/ionic-team/ionic/issues/23825)
* **alert:** add destructive role to alert buttons ([#21269](https://github.com/ionic-team/ionic/issues/21269)) ([e53f024](https://github.com/ionic-team/ionic/commit/e53f0241e2bf91461c55097fde271ae85ca644ea))
* **alert:** add support for custom input attributes ([#21365](https://github.com/ionic-team/ionic/issues/21365)) ([1ed8169](https://github.com/ionic-team/ionic/commit/1ed81693f225b6801a0897ef1a8314999c122484))
* **all:** add ability to eject from Ionic sanitizer ([#20457](https://github.com/ionic-team/ionic/issues/20457)) ([fa9ddc9](https://github.com/ionic-team/ionic/commit/fa9ddc91bc9fefc2bb247cfe7511384f77335476)), closes [#18277](https://github.com/ionic-team/ionic/issues/18277)
* **all:** add all autocomplete values to input and searchbar ([#21297](https://github.com/ionic-team/ionic/issues/21297)) ([4fd7c0c](https://github.com/ionic-team/ionic/commit/4fd7c0cc5a6c97100fa380e4ff1be0bb84c7006b))
* **all:** add CustomEvents types to components that emit events ([#23956](https://github.com/ionic-team/ionic/issues/23956)) ([8708095](https://github.com/ionic-team/ionic/commit/87080951112a409893a4bac2def1deca06642b16)), closes [#22925](https://github.com/ionic-team/ionic/issues/22925)
* **all:** add optional generics typings for overlay component methods ([#21393](https://github.com/ionic-team/ionic/issues/21393)) ([5bf83b8](https://github.com/ionic-team/ionic/commit/5bf83b80d7d2749719dd1a280ae8e205fbc4b2a9))
* **all:** add shadow parts to missing components ([#21436](https://github.com/ionic-team/ionic/issues/21436)) ([17375d2](https://github.com/ionic-team/ionic/commit/17375d232500b47ef1cacd7c028c38990d307984))
* **all:** add support for configuring animations on a per-page basis  ([#21433](https://github.com/ionic-team/ionic/issues/21433)) ([f34d375](https://github.com/ionic-team/ionic/commit/f34d3752e3462c9d81487fc86af5ec185cc3d1e3))
* **angular:** build for angular 12.0 ([#23970](https://github.com/ionic-team/ionic/issues/23970)) ([3451a34](https://github.com/ionic-team/ionic/commit/3451a34ad0c893be0b6c17dc91ac9a75d2b9b52c))
* **angular:** expose getPlatforms and isPlatform ([#21308](https://github.com/ionic-team/ionic/issues/21308)) ([4af54a2](https://github.com/ionic-team/ionic/commit/4af54a2fea5d9cef843b1ebce849fb4a5c206f0b))
* **angular:** strongly type Ionic lifecycle hooks ([#18044](https://github.com/ionic-team/ionic/issues/18044)) ([53fc8e3](https://github.com/ionic-team/ionic/commit/53fc8e37c89cea793d0e00246d52805166730108)), closes [#18043](https://github.com/ionic-team/ionic/issues/18043)
* **animation:** add option to clean up old animation stylesheets ([#20940](https://github.com/ionic-team/ionic/issues/20940)) ([5b98405](https://github.com/ionic-team/ionic/commit/5b9840508faf6a2c985726be889c1f2fca0e0733)), closes [#20610](https://github.com/ionic-team/ionic/issues/20610)
* **app:** keyboard open and close events ([#18478](https://github.com/ionic-team/ionic/issues/18478)) ([ae5f1dd](https://github.com/ionic-team/ionic/commit/ae5f1ddff0c0799167a154abbb418b2ad3434d47))
* **back-button:** add 'backButtonDefaultHref' property to Ionic Config ([#20491](https://github.com/ionic-team/ionic/issues/20491)) ([1b11ff7](https://github.com/ionic-team/ionic/commit/1b11ff7fb92b75f5c869c79d5e0d5dfd8889597f)), closes [#19305](https://github.com/ionic-team/ionic/issues/19305)
* **breadcrumbs:** add breadcrumbs component ([#22701](https://github.com/ionic-team/ionic/issues/22701)) ([2f6b1e4](https://github.com/ionic-team/ionic/commit/2f6b1e4eea307c6f14345704e5824378ef079acb)), closes [#22770](https://github.com/ionic-team/ionic/issues/22770)
* **breadcrumbs:** ionCollapsedClick event payload now contains references to collapsed breadcrumb elements ([#23611](https://github.com/ionic-team/ionic/issues/23611)) ([9ce57d2](https://github.com/ionic-team/ionic/commit/9ce57d2efb84130895a37e22e0fd7e5d713a9fa5)), closes [#23552](https://github.com/ionic-team/ionic/issues/23552)
* **card:** expose global card css variable ([#21756](https://github.com/ionic-team/ionic/issues/21756)) ([096eef4](https://github.com/ionic-team/ionic/commit/096eef4a79c2d05c37eb224466c6d7d512d2be20)), closes [#21694](https://github.com/ionic-team/ionic/issues/21694)
* **checkbox:** add parts support for container, mark ([#20950](https://github.com/ionic-team/ionic/issues/20950)) ([d4b9151](https://github.com/ionic-team/ionic/commit/d4b9151396aed6d7a29d8f40d6e607bf6258b4ef))
* **chip:** add disabled property ([#20658](https://github.com/ionic-team/ionic/issues/20658)) ([0a0cbd8](https://github.com/ionic-team/ionic/commit/0a0cbd8f2a505ad2b3d8afb60cb1e940ced52e0d)), closes [#19510](https://github.com/ionic-team/ionic/issues/19510)
* **components:** improve button states and add new css properties ([#19440](https://github.com/ionic-team/ionic/issues/19440)) ([9415929](https://github.com/ionic-team/ionic/commit/94159291b27ddf1a859c8f3f87a0d6e54a8b5f13)), closes [#20213](https://github.com/ionic-team/ionic/issues/20213) [#19965](https://github.com/ionic-team/ionic/issues/19965)
* **content, reorder-group, header, footer, infinite-scroll, refresher:** add custom scroll target to improve compatibility with virtual scroll ([#24883](https://github.com/ionic-team/ionic/issues/24883)) ([2a438da](https://github.com/ionic-team/ionic/commit/2a438da010ddd4d4211e1879e27d7b28409daaa2)), closes [#23437](https://github.com/ionic-team/ionic/issues/23437)
* **content:** add parts support for background, scroll ([#20929](https://github.com/ionic-team/ionic/issues/20929)) ([578ab93](https://github.com/ionic-team/ionic/commit/578ab93d297f101ac899b6b6b099445ac679c71f))
* **custom-elements:** add experimental custom elements build  ([#22863](https://github.com/ionic-team/ionic/issues/22863)) ([0de75af](https://github.com/ionic-team/ionic/commit/0de75afbefc521c1d76adcd587f77ba19c285a95))
* **datetime:** add ability to select only month, year, or month and year ([#23913](https://github.com/ionic-team/ionic/issues/23913)) ([4ae44b7](https://github.com/ionic-team/ionic/commit/4ae44b7a236004738d593406d7b1236600bc6d95))
* **datetime:** add calendar picker ([#23416](https://github.com/ionic-team/ionic/issues/23416)) ([932d3ca](https://github.com/ionic-team/ionic/commit/932d3ca62f3e3ef08acb065ce6ec46faa3811f96)), closes [#19423](https://github.com/ionic-team/ionic/issues/19423)
* **datetime:** add clear button ([#23920](https://github.com/ionic-team/ionic/issues/23920)) ([18765e7](https://github.com/ionic-team/ionic/commit/18765e7e39b9f205f47f394d26d6ecc4b53e17ef)), closes [#17482](https://github.com/ionic-team/ionic/issues/17482)
* **datetime:** add custom timezone display property ([#19519](https://github.com/ionic-team/ionic/issues/19519)) ([7b032c5](https://github.com/ionic-team/ionic/commit/7b032c5e9b396fcfb0b0e313aff1bebcbc43305e)), closes [#19401](https://github.com/ionic-team/ionic/issues/19401)
* **datetime:** add firstDayOfWeek property ([#23692](https://github.com/ionic-team/ionic/issues/23692)) ([ea348f0](https://github.com/ionic-team/ionic/commit/ea348f005aef7b2fda581a99338139f6fefcda63)), closes [#23556](https://github.com/ionic-team/ionic/issues/23556)
* **datetime:** add hourCycle property ([#23686](https://github.com/ionic-team/ionic/issues/23686)) ([6342fde](https://github.com/ionic-team/ionic/commit/6342fde56c7687703edd212b8383536c8b9a6400)), closes [#23661](https://github.com/ionic-team/ionic/issues/23661)
* **datetime:** add parts support for placeholder, text ([#20930](https://github.com/ionic-team/ionic/issues/20930)) ([76ca475](https://github.com/ionic-team/ionic/commit/76ca475734e13404886bdf70117c0c39bbd7ce70))
* **datetime:** add showDefaultTimeLabel property and time-label slot ([#23577](https://github.com/ionic-team/ionic/issues/23577)) ([7ac0109](https://github.com/ionic-team/ionic/commit/7ac010943b2c9ad42a1833153ea16ccffd169b91)), closes [#23555](https://github.com/ionic-team/ionic/issues/23555)
* **datetime:** add size property ([#23649](https://github.com/ionic-team/ionic/issues/23649)) ([321341d](https://github.com/ionic-team/ionic/commit/321341d97dff98b76b69a1efce58923a80e92bc4)), closes [#23518](https://github.com/ionic-team/ionic/issues/23518)
* **datetime:** isDateEnabled to enable/disable specific days  ([#24898](https://github.com/ionic-team/ionic/issues/24898)) ([e932a04](https://github.com/ionic-team/ionic/commit/e932a042237e6f44bf278bcbd895d8569fc17348)), closes [#24209](https://github.com/ionic-team/ionic/issues/24209)
* **fab-button:** add close icon font size css variable ([#19628](https://github.com/ionic-team/ionic/issues/19628)) ([df408f9](https://github.com/ionic-team/ionic/commit/df408f91f1aef903adaa5e635fef9bc7542e8739))
* **fab-button:** add closeIcon property ([#19626](https://github.com/ionic-team/ionic/issues/19626)) ([698e526](https://github.com/ionic-team/ionic/commit/698e526b9f882e98efc4bf160999182c645b772c))
* **gesture:** add support for blurring active inputs on gesture start ([#20638](https://github.com/ionic-team/ionic/issues/20638)) ([32ecdd6](https://github.com/ionic-team/ionic/commit/32ecdd67536f07f9d95e331e44661afb2cf7b470)), closes [#20588](https://github.com/ionic-team/ionic/issues/20588)
* **header, footer:** add ios fading header style ([#24011](https://github.com/ionic-team/ionic/issues/24011)) ([7ce3959](https://github.com/ionic-team/ionic/commit/7ce3959b66a08e980c7dac3bb7d7df6bf0ae874e))
* **img:** add parts support for image ([#20943](https://github.com/ionic-team/ionic/issues/20943)) ([63c75ed](https://github.com/ionic-team/ionic/commit/63c75edd21387f28387c8a8529ba638317a9d9b8))
* **input, textarea:** expose native events for ionBlur and ionFocus ([#21777](https://github.com/ionic-team/ionic/issues/21777)) ([a625c83](https://github.com/ionic-team/ionic/commit/a625c837a60abc07ad71c696196a89f1a25a4c27)), closes [#17363](https://github.com/ionic-team/ionic/issues/17363)
* **input:** accept datetime-local, month, and week type values ([#21758](https://github.com/ionic-team/ionic/issues/21758)) ([fa93dff](https://github.com/ionic-team/ionic/commit/fa93dffdb4f350e8db8acc7f06b06761974eea8e)), closes [#21757](https://github.com/ionic-team/ionic/issues/21757)
* **input:** add support for enterkeyhint ([#21035](https://github.com/ionic-team/ionic/issues/21035)) ([3efaf43](https://github.com/ionic-team/ionic/commit/3efaf4382175d40902968cabb7edd672ffc7cc2b)), closes [#21034](https://github.com/ionic-team/ionic/issues/21034)
* **item:** add helper text, error text, counter, shape, and fill mode ([#23354](https://github.com/ionic-team/ionic/issues/23354)) ([faefe97](https://github.com/ionic-team/ionic/commit/faefe97da6a9d5beff1183d10efd0df9c4e3ebd7)), closes [#19619](https://github.com/ionic-team/ionic/issues/19619)
* **item:** add parts support for detail-icon ([#20979](https://github.com/ionic-team/ionic/issues/20979)) ([6414496](https://github.com/ionic-team/ionic/commit/64144960b06e056a99aa3d352486a495b6bb43ed))
* **item:** counter formatter to customize counter text display ([#24336](https://github.com/ionic-team/ionic/issues/24336)) ([171020e](https://github.com/ionic-team/ionic/commit/171020e9d200ccfdef0f01c427b295bb50dd1fef)), closes [#24327](https://github.com/ionic-team/ionic/issues/24327)
* **menu:** add console error for incorrect usage of contentId ([#23871](https://github.com/ionic-team/ionic/issues/23871)) ([879ab8e](https://github.com/ionic-team/ionic/commit/879ab8ebdacc1468ed206701c00b60100dbab9e4)), closes [#23810](https://github.com/ionic-team/ionic/issues/23810)
* **menu:** add parts support for backdrop, container ([#20978](https://github.com/ionic-team/ionic/issues/20978)) ([50bc212](https://github.com/ionic-team/ionic/commit/50bc212d0b30919c136d6be60a9d458ec7d50dde))
* **modal:** ability to programmatically set current sheet breakpoint ([#24648](https://github.com/ionic-team/ionic/issues/24648)) ([3145c76](https://github.com/ionic-team/ionic/commit/3145c76934ac711038f9dcba98a385dfbe754953)), closes [#23917](https://github.com/ionic-team/ionic/issues/23917)
* **modal:** add bottom sheet functionality ([#23828](https://github.com/ionic-team/ionic/issues/23828)) ([12216d3](https://github.com/ionic-team/ionic/commit/12216d378df091e16fd77d271b107e819278481c)), closes [#21039](https://github.com/ionic-team/ionic/issues/21039)
* **modal:** add canDismiss property to manage modal dismissing ([#24928](https://github.com/ionic-team/ionic/issues/24928)) ([4b21958](https://github.com/ionic-team/ionic/commit/4b21958ec57019afcde786598880e1f8edada2b1)), closes [#22297](https://github.com/ionic-team/ionic/issues/22297)
* **modal:** modals can now be used inline ([#23341](https://github.com/ionic-team/ionic/issues/23341)) ([3be1c3d](https://github.com/ionic-team/ionic/commit/3be1c3dcd73e6039a89b19b409e63877cda37f6e)), closes [#20117](https://github.com/ionic-team/ionic/issues/20117) [#20263](https://github.com/ionic-team/ionic/issues/20263)
* **platform:** add ability to override platform detection methods ([#23915](https://github.com/ionic-team/ionic/issues/23915)) ([45cabae](https://github.com/ionic-team/ionic/commit/45cabae04bf9236cd069793fbf2ac8f68c372cc3)), closes [#19737](https://github.com/ionic-team/ionic/issues/19737)
* **popover:** account for ionShadowTarget elements ([#23436](https://github.com/ionic-team/ionic/issues/23436)) ([0e38d42](https://github.com/ionic-team/ionic/commit/0e38d4276110dcd94db5adc3b6aee3b5b0befc5c))
* **popover:** add ability to pass event to present method ([#23827](https://github.com/ionic-team/ionic/issues/23827)) ([1d2ee92](https://github.com/ionic-team/ionic/commit/1d2ee92ca01b77bcf87c7783b50d59efcf0a402a)), closes [#23813](https://github.com/ionic-team/ionic/issues/23813)
* **popover:** add desktop support ([#23258](https://github.com/ionic-team/ionic/issues/23258)) ([a67a0fa](https://github.com/ionic-team/ionic/commit/a67a0fabb8249685bbe93ed862839e2b2e76cd5a)), closes [#21599](https://github.com/ionic-team/ionic/issues/21599)
* **popover:** popover can now be used inline ([#23231](https://github.com/ionic-team/ionic/issues/23231)) ([308fa1c](https://github.com/ionic-team/ionic/commit/308fa1c0dd054cfc2ea54d2edc99e7a4b549f6f0))
* **progress:** add parts for more design customization ([#22938](https://github.com/ionic-team/ionic/issues/22938)) ([e256d3f](https://github.com/ionic-team/ionic/commit/e256d3f09fd6f231c4d9e1d0f0927612a591466b)), closes [#20062](https://github.com/ionic-team/ionic/issues/20062) [#21820](https://github.com/ionic-team/ionic/issues/21820)
* **radio:** add parts support for container, mark ([#20952](https://github.com/ionic-team/ionic/issues/20952)) ([228ca2b](https://github.com/ionic-team/ionic/commit/228ca2b093215aba91fe925b301049471ffaa169))
* **range:** add knobMoveStart and knobMoveEnd events ([#25011](https://github.com/ionic-team/ionic/issues/25011)) ([f5cb1f8](https://github.com/ionic-team/ionic/commit/f5cb1f8444ba050042e788f9f9ec7b6309bf1b60))
* **range:** add parts support for bar, bar-active, knob, pin, tick, tick-active ([#20961](https://github.com/ionic-team/ionic/issues/20961)) ([619f67a](https://github.com/ionic-team/ionic/commit/619f67a00baa387d0f2bf3f6219e21bc87c03313))
* **range:** add support for customizing pin format ([#22972](https://github.com/ionic-team/ionic/issues/22972)) ([8f2c4f7](https://github.com/ionic-team/ionic/commit/8f2c4f73db167503cdf60222f42bcaadf905b401))
* **react:** add custom elements bundle ([#23896](https://github.com/ionic-team/ionic/issues/23896)) ([c50d895](https://github.com/ionic-team/ionic/commit/c50d895370a56d0809019dc59fe32ec840b72f03))
* **react:** add Ionic Animations wrapper (experimental) ([#20273](https://github.com/ionic-team/ionic/issues/20273)) ([b59d764](https://github.com/ionic-team/ionic/commit/b59d7647fd6f9a645a4ec0fe9aca526ea5eda4e0))
* **react:** add react hooks to control overlay components ([#22484](https://github.com/ionic-team/ionic/issues/22484)) ([b83e009](https://github.com/ionic-team/ionic/commit/b83e00934e794a936c9d3d23d7f94bbe89cedcd5))
* **reorder:** add parts support for icon ([#20960](https://github.com/ionic-team/ionic/issues/20960)) ([ba20209](https://github.com/ionic-team/ionic/commit/ba20209604666048619ae5f4358be0e65ef36e4f))
* **router:** add navigation hooks ([#21709](https://github.com/ionic-team/ionic/issues/21709)) ([77464ef](https://github.com/ionic-team/ionic/commit/77464ef21aaaa5afa7a02e5417f3ec295b240601))
* **searchbar:** add border-radius css variable ([#20662](https://github.com/ionic-team/ionic/issues/20662)) ([acaa1d9](https://github.com/ionic-team/ionic/commit/acaa1d9ef7e4037913159c0d32829183ddc1860b)), closes [#17426](https://github.com/ionic-team/ionic/issues/17426) [#18247](https://github.com/ionic-team/ionic/issues/18247)
* **searchbar:** add showClearIcon property ([#22759](https://github.com/ionic-team/ionic/issues/22759)) ([215eb5d](https://github.com/ionic-team/ionic/commit/215eb5d4efbb9ade942dba1687469caf61da21e7)), closes [#22738](https://github.com/ionic-team/ionic/issues/22738)
* **searchbar:** add support for enterkeyhint ([#21036](https://github.com/ionic-team/ionic/issues/21036)) ([e90683a](https://github.com/ionic-team/ionic/commit/e90683a713cb45d1e1283dd41343ea6b672a9e3a)), closes [#21034](https://github.com/ionic-team/ionic/issues/21034)
* **segment-button, toast:** add additional parts docs ([#21532](https://github.com/ionic-team/ionic/issues/21532)) ([a5e4669](https://github.com/ionic-team/ionic/commit/a5e4669c4bcbcb2cdd605ed17c35e42438bd5596))
* **segment-button:** add --indicator-height property to segment button ([#19653](https://github.com/ionic-team/ionic/issues/19653)) ([d76a503](https://github.com/ionic-team/ionic/commit/d76a5031c4c96b5fdf691a56ed61d3dcc4e4dafb))
* **segment:** add keyboard navigation, add selectOnFocus property to control selection follow focus behavior ([#23590](https://github.com/ionic-team/ionic/issues/23590)) ([b6c53e5](https://github.com/ionic-team/ionic/commit/b6c53e539b0855fa95b0fe02e5fa74ce403b68b8)), closes [#23520](https://github.com/ionic-team/ionic/issues/23520)
* **segment:** add swipeGesture property to allow for disabling of the swipe gesture ([#22087](https://github.com/ionic-team/ionic/issues/22087)) ([65bc995](https://github.com/ionic-team/ionic/commit/65bc99577c44cce653dafd9937c4d8f9c45fff61)), closes [#22048](https://github.com/ionic-team/ionic/issues/22048)
* **segment:** implement iOS 13 segment with animation ([#19036](https://github.com/ionic-team/ionic/issues/19036)) ([dc66ce4](https://github.com/ionic-team/ionic/commit/dc66ce48e1f210ca57cecae5c89e5dc3b7e95de5)), closes [#18663](https://github.com/ionic-team/ionic/issues/18663)
* **select-option:** pass class from the option to the interface for individual styling  ([#21304](https://github.com/ionic-team/ionic/issues/21304)) ([5285824](https://github.com/ionic-team/ionic/commit/5285824da5258ea638420fc60c50e0a19952f89c))
* **select:** add event for when overlay is dismissed ([#24099](https://github.com/ionic-team/ionic/issues/24099)) ([c1ecf94](https://github.com/ionic-team/ionic/commit/c1ecf94e4e6e320b61606da3c889926f7372ced7))
* **select:** add event for when overlay is dismissed ([#24400](https://github.com/ionic-team/ionic/issues/24400)) ([b835b7c](https://github.com/ionic-team/ionic/commit/b835b7c0c7840f41c54f96743cc0a779ff474ab6))
* **select:** add optional generic typings ([#21514](https://github.com/ionic-team/ionic/issues/21514)) ([7c2d0c9](https://github.com/ionic-team/ionic/commit/7c2d0c981ab91930478c4b76220ce4ec4ed4e471))
* **select:** add parts support for placeholder, icon, text ([#21108](https://github.com/ionic-team/ionic/issues/21108)) ([30a1c89](https://github.com/ionic-team/ionic/commit/30a1c896883e971ab87ef7d5d8790e9a60632fc2))
* **select:** update popover interface to match MD spec on desktop, allow multiple values in popover interface ([#23474](https://github.com/ionic-team/ionic/issues/23474)) ([2c07a15](https://github.com/ionic-team/ionic/commit/2c07a1566b6f8570f7e12a55ca8f86d8fb8a968e)), closes [#23657](https://github.com/ionic-team/ionic/issues/23657) [#15500](https://github.com/ionic-team/ionic/issues/15500) [#12310](https://github.com/ionic-team/ionic/issues/12310)
* **slides:** add IonicSlides module for Swiper migration, deprecate ion-slides ([#23844](https://github.com/ionic-team/ionic/issues/23844)) ([11fda41](https://github.com/ionic-team/ionic/commit/11fda41420343886dabd97096690be38f1c40524)), closes [#23447](https://github.com/ionic-team/ionic/issues/23447)
* **slides:** add IonicSwiper modules, deprecate ion-slides, and add link to migration ([#23447](https://github.com/ionic-team/ionic/issues/23447)) ([623c84a](https://github.com/ionic-team/ionic/commit/623c84ab082668a996c654e18ffc9768f68b85dd))
* **slides:** add support for Swiper 7 ([#24190](https://github.com/ionic-team/ionic/issues/24190)) ([d0b6130](https://github.com/ionic-team/ionic/commit/d0b61307c6b7ff1589646c43f989260b59db1473))
* **slides:** update to swiper 5 ([#20917](https://github.com/ionic-team/ionic/issues/20917)) ([4e28445](https://github.com/ionic-team/ionic/commit/4e28445ecb029f8d225acf9313209e5f61114dc4)), closes [#20033](https://github.com/ionic-team/ionic/issues/20033)
* **spinner:** add lines-sharp, lines-sharp-small, update styles for ios 14 ([#22397](https://github.com/ionic-team/ionic/issues/22397)) ([2a5b272](https://github.com/ionic-team/ionic/commit/2a5b272a329bbad1ca07705f84f0fd06e3ef32ad))
* **textarea:** add support for inputmode and enterkeyhint ([#21106](https://github.com/ionic-team/ionic/issues/21106)) ([1622d9b](https://github.com/ionic-team/ionic/commit/1622d9bb3c7f2aeed7dc823620204737619a5b0d))
* **toast:** add icon property to show icon at start of toast content ([#23596](https://github.com/ionic-team/ionic/issues/23596)) ([df24c8c](https://github.com/ionic-team/ionic/commit/df24c8c5ae0b493841c07c05e0d620fa4a90c05a)), closes [#23524](https://github.com/ionic-team/ionic/issues/23524)
* **toast:** add white-space variable for toast message ([#20729](https://github.com/ionic-team/ionic/issues/20729)) ([e5e02d4](https://github.com/ionic-team/ionic/commit/e5e02d4f88abbcc7dbc626db6d5adf4292d8e776)), closes [#20727](https://github.com/ionic-team/ionic/issues/20727)
* **toast:** expose shadow parts ([#20146](https://github.com/ionic-team/ionic/issues/20146)) ([3b4988a](https://github.com/ionic-team/ionic/commit/3b4988aa60dc6d31e1bc3367cb8f5e8d85710ac6)), closes [#19722](https://github.com/ionic-team/ionic/issues/19722)
* **toggle:** add parts support for handle, track ([#20962](https://github.com/ionic-team/ionic/issues/20962)) ([d2b772f](https://github.com/ionic-team/ionic/commit/d2b772f19fde71bcec72300cb4cf8234321b35bc))
* **toggle:** improve customization with css vars and auto-adjust handle width and height ([#21050](https://github.com/ionic-team/ionic/issues/21050)) ([04ace4c](https://github.com/ionic-team/ionic/commit/04ace4c98346fde5bad343224657f049beb3e868)), closes [#19868](https://github.com/ionic-team/ionic/issues/19868) [#20474](https://github.com/ionic-team/ionic/issues/20474)
* **vue:** add custom elements bundle ([#23458](https://github.com/ionic-team/ionic/issues/23458)) ([dc48a9f](https://github.com/ionic-team/ionic/commit/dc48a9f1a2dff8a2d644112bbe1df8b0b6811848))
* **vue:** add hardware back button hook ([#22069](https://github.com/ionic-team/ionic/issues/22069)) ([a7f564b](https://github.com/ionic-team/ionic/commit/a7f564b818a6ce5f97d999934d5cca77da1b2c83))
* **vue:** add ionic vue beta ([#22062](https://github.com/ionic-team/ionic/issues/22062)) ([5ffa65f](https://github.com/ionic-team/ionic/commit/5ffa65f84a037f265a89f0b3310552d73125b8cd))


### Performance Improvements

* **all:** improve scroll assist responsiveness ([#20987](https://github.com/ionic-team/ionic/issues/20987)) ([6f13b8c](https://github.com/ionic-team/ionic/commit/6f13b8c7922f638cac4eb3b111ff9643e6995491)), closes [#20922](https://github.com/ionic-team/ionic/issues/20922)
* **content:** remove global click listener to improve interaction performance ([#24360](https://github.com/ionic-team/ionic/issues/24360)) ([1bfac52](https://github.com/ionic-team/ionic/commit/1bfac52331d3f296e5721b2a6c3fd94a97450a1d)), closes [#24359](https://github.com/ionic-team/ionic/issues/24359)
* improve treeshaking functionality ([#24895](https://github.com/ionic-team/ionic/issues/24895)) ([805907a](https://github.com/ionic-team/ionic/commit/805907af4e78179f1acc9cb02263b1ea10d4e3df)), closes [#24280](https://github.com/ionic-team/ionic/issues/24280)
* **ios:** move content to stacking context to improve scrolling performance on iOS devices ([#22180](https://github.com/ionic-team/ionic/issues/22180)) ([9f44966](https://github.com/ionic-team/ionic/commit/9f44966d8572a27d8296b38ae4f3e689c76c2e44))
* **ios:** move content to stacking context while preserving position: fixed behavior ([#22489](https://github.com/ionic-team/ionic/issues/22489)) ([d77a9d5](https://github.com/ionic-team/ionic/commit/d77a9d57ec02c69df43ec2a286eea674a85cae36)), closes [#22473](https://github.com/ionic-team/ionic/issues/22473)
* remove shims for legacy browsers no longer supported in v6 ([#23592](https://github.com/ionic-team/ionic/issues/23592)) ([259b135](https://github.com/ionic-team/ionic/commit/259b1359dbd20d4f85036ae46901a051cd8fc98b))
* **segment:** improve scrolling performance on ios when using segment ([#22110](https://github.com/ionic-team/ionic/issues/22110)) ([68afc49](https://github.com/ionic-team/ionic/commit/68afc49e9ed27acffb0b765b7be6b03e8574850d)), closes [#22095](https://github.com/ionic-team/ionic/issues/22095)
* **various:** don't use lazy-loaded icon names in components ([#24671](https://github.com/ionic-team/ionic/issues/24671)) ([484de50](https://github.com/ionic-team/ionic/commit/484de5074de212dffb4bf4f73bade7acec103fe8))


### BREAKING CHANGES

* **all:** The `RadioChangeEventDetail` interface has been removed in favor of `RadioGroupChangeEventDetail`.
* **input, select, textarea:** Updated the `placeholder` property on `ion-input`, `ion-textarea`, and `ion-select` to have a type of `string | undefined`.
* **searchbar:** The `showClearButton` property on `ion-searchbar` now defaults to `'always'`.
* **datetime:** The `ion-datetime` component has been revamped to use a new calendar style. As a result, some APIs have been removed. See https://github.com/ionic-team/ionic-framework/blob/master/BREAKING.md for more details.
* **popover:** Converted `ion-popover` to use the Shadow DOM.
* **ios:** The tab bar and toolbar default background colors have been updated to better reflect the latest iOS styles.
* **header:** The last toolbar in the header with a collapsible large title no longer has a border.
* **toast:** The `--white-space` CSS Variable now defaults to `normal`.
* **components:** *Activated Class*

The `activated` class that is automatically added to buttons on press has been renamed to `ion-activated`. This will be more consistent with our `ion-focused` class we add and also will reduce conflicts with user's CSS.

*CSS Variables*

The `--background-hover`, `--background-focused` and `--background-activated` CSS variables on components that render native buttons will now have an opacity automatically set. If you are setting any of these like the following:

```
--background-hover: rgba(44, 44, 44, 0.08);
```

You will likely not see a hover state anymore. It should be updated to only set the desired color:

```
--background-hover: rgba(44, 44, 44);
```

If the opacity desired is something other than what the spec asks for, use:

```
--background-hover: rgba(44, 44, 44);
--background-hover-opacity: 1;
```
* The following components have been updated to remove the checked or selected properties:

- Radio
- Segment Button
- Select

Developers should set the value property on the respective parent components in order to managed checked/selected status.

Co-authored-by: Liam DeBeasi <liamdebeasi@users.noreply.github.com>





## [6.1.8](https://github.com/ionic-team/ionic/compare/v6.1.7...v6.1.8) (2022-06-01)


### Bug Fixes

* **all:** improve compatibility with vite ([#25381](https://github.com/ionic-team/ionic/issues/25381)) ([d83bcd2](https://github.com/ionic-team/ionic/commit/d83bcd2b7f9937550008f995ff91517777584373)), closes [#23823](https://github.com/ionic-team/ionic/issues/23823)
* **item-sliding:** swiping inside of virtual scroller now prevents scrolling ([#25345](https://github.com/ionic-team/ionic/issues/25345)) ([5a1a5f6](https://github.com/ionic-team/ionic/commit/5a1a5f6b4c2ab4059158986e907fff45d03be753))
* **range:** dragging knob no longer scrolls page ([#25343](https://github.com/ionic-team/ionic/issues/25343)) ([0b92dff](https://github.com/ionic-team/ionic/commit/0b92dffa92c05705ff83518c10608e3dc3651d51)), closes [#19004](https://github.com/ionic-team/ionic/issues/19004)





## [6.1.7](https://github.com/ionic-team/ionic/compare/v6.1.6...v6.1.7) (2022-05-26)


### Bug Fixes

* **accordion:** accordions expand when using binding ([#25322](https://github.com/ionic-team/ionic/issues/25322)) ([61e571e](https://github.com/ionic-team/ionic/commit/61e571e585ed8ad9b0ca2f98f57bb16616413ba6)), closes [#25307](https://github.com/ionic-team/ionic/issues/25307)
* **datetime:** don't update value on confirm call if no date was selected ([#25338](https://github.com/ionic-team/ionic/issues/25338)) ([9e5b10a](https://github.com/ionic-team/ionic/commit/9e5b10a2155c6b9de565931da384e0e49aeca7b7))
* **item, list:** list aria roles are added ([#25336](https://github.com/ionic-team/ionic/issues/25336)) ([311c634](https://github.com/ionic-team/ionic/commit/311c634d20e9e597db676d6f54e4b79cfe742a61)), closes [#19939](https://github.com/ionic-team/ionic/issues/19939)
* **menu:** rtl menu no longer disappears on ios 15 ([#25309](https://github.com/ionic-team/ionic/issues/25309)) ([6005431](https://github.com/ionic-team/ionic/commit/60054310afbab6151f6c29ff6e74666acd181a41)), closes [#25192](https://github.com/ionic-team/ionic/issues/25192)
* **modal:** swipe to close on content blocks scroll in ion-nav ([#25300](https://github.com/ionic-team/ionic/issues/25300)) ([fdc55c0](https://github.com/ionic-team/ionic/commit/fdc55c072765c87ad7c783e6d8a238b007f5f3ff)), closes [#25298](https://github.com/ionic-team/ionic/issues/25298)
* **nav:** swipe to go back works inside card modal ([#25333](https://github.com/ionic-team/ionic/issues/25333)) ([0156be6](https://github.com/ionic-team/ionic/commit/0156be61cbf73b25cb3c2cba1bd20adebbb3db4f)), closes [#25327](https://github.com/ionic-team/ionic/issues/25327)
* **refresher:** attach scroll listener to custom scroll target ([#25335](https://github.com/ionic-team/ionic/issues/25335)) ([8f5e4cd](https://github.com/ionic-team/ionic/commit/8f5e4cd9350b10a98afb7c98353c6719eee918bb)), closes [#25318](https://github.com/ionic-team/ionic/issues/25318)
* **types:** improve intellisense with colors ([#25347](https://github.com/ionic-team/ionic/issues/25347)) ([97cfbbb](https://github.com/ionic-team/ionic/commit/97cfbbb65d3e63c32d720e01c7368c68616bb531))





## [6.1.6](https://github.com/ionic-team/ionic/compare/v6.1.5...v6.1.6) (2022-05-18)


### Bug Fixes

* **loading:** spinner now respects —spinner-color ([#25261](https://github.com/ionic-team/ionic/issues/25261)) ([65f4c74](https://github.com/ionic-team/ionic/commit/65f4c742e7a5e5756f6f72dd853e38e885f90385)), closes [#25180](https://github.com/ionic-team/ionic/issues/25180)
* **modal:** reset breakpoint to initial breakpoint on present ([#25246](https://github.com/ionic-team/ionic/issues/25246)) ([2557bf3](https://github.com/ionic-team/ionic/commit/2557bf3c3eed9e33e89e07a8d73489da8d81bee3)), closes [#25245](https://github.com/ionic-team/ionic/issues/25245)
* **scroll-assist:** touch end events continue to bubble on inputs ([#25282](https://github.com/ionic-team/ionic/issues/25282)) ([780f16d](https://github.com/ionic-team/ionic/commit/780f16d9e04ee5aaaf91bb7c6ef15c72cc8aeb45)), closes [#25229](https://github.com/ionic-team/ionic/issues/25229)





## [6.1.5](https://github.com/ionic-team/ionic/compare/v6.1.4...v6.1.5) (2022-05-11)


### Bug Fixes

* **core:** @axe-core/playwright should be a devDependency ([#25244](https://github.com/ionic-team/ionic/issues/25244)) ([617ec48](https://github.com/ionic-team/ionic/commit/617ec48265157d1502c443395472c21ebdb2989e)), closes [#25242](https://github.com/ionic-team/ionic/issues/25242)
* **item:** counter has appropriate contrast ([#25266](https://github.com/ionic-team/ionic/issues/25266)) ([750be33](https://github.com/ionic-team/ionic/commit/750be33772e9ba71a3cda35709d17b7912aa68e2)), closes [#25262](https://github.com/ionic-team/ionic/issues/25262)
* **spinner:** alignment is now correct in rtl ([#25260](https://github.com/ionic-team/ionic/issues/25260)) ([e3c996d](https://github.com/ionic-team/ionic/commit/e3c996dea878a8dd276a0ca99f59b330125f9b75))





## [6.1.4](https://github.com/ionic-team/ionic/compare/v6.1.3...v6.1.4) (2022-05-04)


### Bug Fixes

* **datetime:** arrow navigation respects min/max values ([#25182](https://github.com/ionic-team/ionic/issues/25182)) ([6946e09](https://github.com/ionic-team/ionic/commit/6946e09815da605e37ff8e4d613a14288ea35fb0)), closes [#25073](https://github.com/ionic-team/ionic/issues/25073)
* **datetime:** hide footer when month-year picker is open ([#25205](https://github.com/ionic-team/ionic/issues/25205)) ([aa5e1b9](https://github.com/ionic-team/ionic/commit/aa5e1b962150b9ed9629812ec566873784526c83))
* **modal:** card modal can now be swiped to close on the content ([#25185](https://github.com/ionic-team/ionic/issues/25185)) ([7633ddb](https://github.com/ionic-team/ionic/commit/7633ddbc845745dfe36b5c8025c54c22c083c2f4)), closes [#22046](https://github.com/ionic-team/ionic/issues/22046)
* **modal:** card modal no longer dismisses from content with refresher ([#25227](https://github.com/ionic-team/ionic/issues/25227)) ([c4f811f](https://github.com/ionic-team/ionic/commit/c4f811f1dde0dcbcdaebaa3a4f5ef87e192b5cc5))





## [6.1.3](https://github.com/ionic-team/ionic/compare/v6.1.2...v6.1.3) (2022-04-27)


### Bug Fixes

* **core:** inherit aria attributes on host elements ([#25156](https://github.com/ionic-team/ionic/issues/25156)) ([611832b](https://github.com/ionic-team/ionic/commit/611832b0d51da295c1bf2897972c4e8baf6e23a3)), closes [#20127](https://github.com/ionic-team/ionic/issues/20127)
* **datetime:** if no default value, don't highlight active day until one is selected ([#25151](https://github.com/ionic-team/ionic/issues/25151)) ([9896939](https://github.com/ionic-team/ionic/commit/98969395abd400cc44d2d3825581a63eb64a56e0))
* **picker-column-internal:** center active item when rapidly opened ([#25155](https://github.com/ionic-team/ionic/issues/25155)) ([8e17fa9](https://github.com/ionic-team/ionic/commit/8e17fa9d5f9b00139693e34bc93b1f9c718ea3cf)), closes [#25154](https://github.com/ionic-team/ionic/issues/25154)
* **select:** avoid duplicate dialogs and backdrops when clicking ([#25175](https://github.com/ionic-team/ionic/issues/25175)) ([70d2784](https://github.com/ionic-team/ionic/commit/70d278414eb5124d17c5ffaba5231c6bfd285656)), closes [#25126](https://github.com/ionic-team/ionic/issues/25126)





## [6.1.2](https://github.com/ionic-team/ionic/compare/v6.1.1...v6.1.2) (2022-04-20)


### Bug Fixes

* **datetime:** time picker display matches dynamically set value ([#25010](https://github.com/ionic-team/ionic/issues/25010)) ([11493a0](https://github.com/ionic-team/ionic/commit/11493a086a4e3f2a4e9d3acdf5a9d49e810a5ef0)), closes [#24967](https://github.com/ionic-team/ionic/issues/24967)
* **modal:** add canDismiss option to modal options ([#25144](https://github.com/ionic-team/ionic/issues/25144)) ([2984ddf](https://github.com/ionic-team/ionic/commit/2984ddf111b6acbd9e47ed90830b6522179b6cee)), closes [#25143](https://github.com/ionic-team/ionic/issues/25143)





## [6.1.1](https://github.com/ionic-team/ionic/compare/v6.1.0...v6.1.1) (2022-04-15)


### Bug Fixes

* **all:** import path is now correct when using ionic in a stencil app ([#25123](https://github.com/ionic-team/ionic/issues/25123)) ([1b407ab](https://github.com/ionic-team/ionic/commit/1b407abdf5d8a2a18b6a2b9daca2d58b7b0f782b)), closes [#25122](https://github.com/ionic-team/ionic/issues/25122)
* **datetime:** account for 30 and 45 minute timezones when getting current date ([#25120](https://github.com/ionic-team/ionic/issues/25120)) ([96b2003](https://github.com/ionic-team/ionic/commit/96b2003b2bd5089d1faafe262e96c7445c5c3349)), closes [#25112](https://github.com/ionic-team/ionic/issues/25112)
* **modal, popover:** do not dismiss when ionDismiss is emitted from select ([#25125](https://github.com/ionic-team/ionic/issues/25125)) ([90115db](https://github.com/ionic-team/ionic/commit/90115db98540a5fc67b611ac2742d1221b8e96ff)), closes [#25124](https://github.com/ionic-team/ionic/issues/25124)





# [6.1.0](https://github.com/ionic-team/ionic/compare/v6.0.14...v6.1.0) (2022-04-13)


### Bug Fixes

* **accordion-group:** only allow keyboard interaction if header is focused ([#25091](https://github.com/ionic-team/ionic/issues/25091)) ([e1b555f](https://github.com/ionic-team/ionic/commit/e1b555f286956574876924068304fc44a78c027c))
* **datetime:** resolve warnings when importing into Stencil app ([#25106](https://github.com/ionic-team/ionic/issues/25106)) ([a61c004](https://github.com/ionic-team/ionic/commit/a61c004fb0c10d9fb0eca0987edf798386251ec2))
* **datetime:** warn when parsing an invalid date value ([#25049](https://github.com/ionic-team/ionic/issues/25049)) ([982dc85](https://github.com/ionic-team/ionic/commit/982dc853befe8ccf54163a0b145e563da06f5dc1))
* **menu:** preserve scroll position when focusing on open ([#25044](https://github.com/ionic-team/ionic/issues/25044)) ([da89684](https://github.com/ionic-team/ionic/commit/da896848776105ba1f7035c4412495786199bade))
* **picker-column:** column renders correctly with selected value ([#24988](https://github.com/ionic-team/ionic/issues/24988)) ([8318659](https://github.com/ionic-team/ionic/commit/83186598ed6cf08b0f0421076c4afb3ab53e1e57)), closes [#17664](https://github.com/ionic-team/ionic/issues/17664)
* **popover:** allow arrow on desktop ([#25056](https://github.com/ionic-team/ionic/issues/25056)) ([bcd00c7](https://github.com/ionic-team/ionic/commit/bcd00c7a6ebb6a00193f04458976ff8b86395215))
* **popover:** only focus trap ion-item children ([#24990](https://github.com/ionic-team/ionic/issues/24990)) ([0cd06a6](https://github.com/ionic-team/ionic/commit/0cd06a675474e1893b4c0801fab8ab79813537c8)), closes [#24633](https://github.com/ionic-team/ionic/issues/24633)
* **ripple-effect:** ripple displays on click or touch ([#25102](https://github.com/ionic-team/ionic/issues/25102)) ([2a313e9](https://github.com/ionic-team/ionic/commit/2a313e91179e19660a758470ed2218bbcf03e0bb)), closes [#25094](https://github.com/ionic-team/ionic/issues/25094)


### Features

* **content, reorder-group, header, footer, infinite-scroll, refresher:** add custom scroll target to improve compatibility with virtual scroll ([#24883](https://github.com/ionic-team/ionic/issues/24883)) ([2a438da](https://github.com/ionic-team/ionic/commit/2a438da010ddd4d4211e1879e27d7b28409daaa2)), closes [#23437](https://github.com/ionic-team/ionic/issues/23437)
* **datetime:** isDateEnabled to enable/disable specific days  ([#24898](https://github.com/ionic-team/ionic/issues/24898)) ([e932a04](https://github.com/ionic-team/ionic/commit/e932a042237e6f44bf278bcbd895d8569fc17348)), closes [#24209](https://github.com/ionic-team/ionic/issues/24209)
* **item:** counter formatter to customize counter text display ([#24336](https://github.com/ionic-team/ionic/issues/24336)) ([171020e](https://github.com/ionic-team/ionic/commit/171020e9d200ccfdef0f01c427b295bb50dd1fef)), closes [#24327](https://github.com/ionic-team/ionic/issues/24327)
* **modal:** ability to programmatically set current sheet breakpoint ([#24648](https://github.com/ionic-team/ionic/issues/24648)) ([3145c76](https://github.com/ionic-team/ionic/commit/3145c76934ac711038f9dcba98a385dfbe754953)), closes [#23917](https://github.com/ionic-team/ionic/issues/23917)
* **modal:** add canDismiss property to manage modal dismissing ([#24928](https://github.com/ionic-team/ionic/issues/24928)) ([4b21958](https://github.com/ionic-team/ionic/commit/4b21958ec57019afcde786598880e1f8edada2b1)), closes [#22297](https://github.com/ionic-team/ionic/issues/22297)
* **range:** add knobMoveStart and knobMoveEnd events ([#25011](https://github.com/ionic-team/ionic/issues/25011)) ([f5cb1f8](https://github.com/ionic-team/ionic/commit/f5cb1f8444ba050042e788f9f9ec7b6309bf1b60))
* **select:** add event for when overlay is dismissed ([#24400](https://github.com/ionic-team/ionic/issues/24400)) ([b835b7c](https://github.com/ionic-team/ionic/commit/b835b7c0c7840f41c54f96743cc0a779ff474ab6))





## [6.0.16](https://github.com/ionic-team/ionic/compare/v6.0.15...v6.0.16) (2022-04-08)

**Note:** Version bump only for package @ionic/core





## [6.0.15](https://github.com/ionic-team/ionic/compare/v6.0.14...v6.0.15) (2022-04-06)


### Bug Fixes

* **datetime:** warn when parsing an invalid date value ([#25049](https://github.com/ionic-team/ionic/issues/25049)) ([982dc85](https://github.com/ionic-team/ionic/commit/982dc853befe8ccf54163a0b145e563da06f5dc1))
* **picker-column:** column renders correctly with selected value ([#24988](https://github.com/ionic-team/ionic/issues/24988)) ([8318659](https://github.com/ionic-team/ionic/commit/83186598ed6cf08b0f0421076c4afb3ab53e1e57)), closes [#17664](https://github.com/ionic-team/ionic/issues/17664)
* **popover:** allow arrow on desktop ([#25056](https://github.com/ionic-team/ionic/issues/25056)) ([bcd00c7](https://github.com/ionic-team/ionic/commit/bcd00c7a6ebb6a00193f04458976ff8b86395215))





## [6.0.14](https://github.com/ionic-team/ionic/compare/v6.0.13...v6.0.14) (2022-03-30)

**Note:** Version bump only for package @ionic/core





## [6.0.13](https://github.com/ionic-team/ionic/compare/v6.0.12...v6.0.13) (2022-03-23)


### Bug Fixes

* **datetime:** presentation time emits ionChange once  ([#24968](https://github.com/ionic-team/ionic/issues/24968)) ([2909b08](https://github.com/ionic-team/ionic/commit/2909b080b7020299a4554c1459b4b190ff739085)), closes [#24967](https://github.com/ionic-team/ionic/issues/24967)
* **popover:** dismissing nested popover via backdrop now works ([#24957](https://github.com/ionic-team/ionic/issues/24957)) ([9e84ef7](https://github.com/ionic-team/ionic/commit/9e84ef7f91d76ca5a1ecaffc7592287267d5368b)), closes [#24954](https://github.com/ionic-team/ionic/issues/24954)





## [6.0.12](https://github.com/ionic-team/ionic/compare/v6.0.11...v6.0.12) (2022-03-16)


### Bug Fixes

* **datetime:** reinit behavior on presentation change ([#24828](https://github.com/ionic-team/ionic/issues/24828)) ([d46e1e8](https://github.com/ionic-team/ionic/commit/d46e1e8506ca5095817b421e9edb37d41451e885))
* **toast:** screen readers now announce toasts when presented ([#24937](https://github.com/ionic-team/ionic/issues/24937)) ([8a97f6b](https://github.com/ionic-team/ionic/commit/8a97f6b5c9ca1e77c1790abd1e924955b6b6ea27)), closes [#22333](https://github.com/ionic-team/ionic/issues/22333)





## [6.0.11](https://github.com/ionic-team/ionic/compare/v6.0.10...v6.0.11) (2022-03-09)


### Bug Fixes

* **datetime:** time picker now scrolls to correct value ([#24879](https://github.com/ionic-team/ionic/issues/24879)) ([331ce6d](https://github.com/ionic-team/ionic/commit/331ce6d6769900e2aec9e30d35b52cfd40cbb889)), closes [#24878](https://github.com/ionic-team/ionic/issues/24878)
* **ios:** swipe to go back now works in rtl mode ([#24866](https://github.com/ionic-team/ionic/issues/24866)) ([2ac9105](https://github.com/ionic-team/ionic/commit/2ac9105796a0765fabc48592b5b44ac58c568579)), closes [#19488](https://github.com/ionic-team/ionic/issues/19488)


### Performance Improvements

* improve treeshaking functionality ([#24895](https://github.com/ionic-team/ionic/issues/24895)) ([805907a](https://github.com/ionic-team/ionic/commit/805907af4e78179f1acc9cb02263b1ea10d4e3df)), closes [#24280](https://github.com/ionic-team/ionic/issues/24280)





## [6.0.10](https://github.com/ionic-team/ionic/compare/v6.0.9...v6.0.10) (2022-03-02)


### Bug Fixes

* **datetime:** confirm method now uses selected date ([#24827](https://github.com/ionic-team/ionic/issues/24827)) ([c35b898](https://github.com/ionic-team/ionic/commit/c35b898f1dc0fb706446b6971982df48fd72fe6d)), closes [#24823](https://github.com/ionic-team/ionic/issues/24823)
* **datetime:** persist minutes column on hour change ([#24829](https://github.com/ionic-team/ionic/issues/24829)) ([aacb58a](https://github.com/ionic-team/ionic/commit/aacb58a3224e3cc51c731d0c9aa52f52c9276692)), closes [#24821](https://github.com/ionic-team/ionic/issues/24821)
* **item-sliding:** close() will maintain disabled state ([#24847](https://github.com/ionic-team/ionic/issues/24847)) ([ea4a9bb](https://github.com/ionic-team/ionic/commit/ea4a9bb69465f8e97746b36638f0b3a26e45da18)), closes [#24747](https://github.com/ionic-team/ionic/issues/24747)
* **modal:** re-enable swipe gestures when modal is dismissed ([#24846](https://github.com/ionic-team/ionic/issues/24846)) ([836c01c](https://github.com/ionic-team/ionic/commit/836c01c73e42caab0101ac4988f0a9b27cf96a5b)), closes [#24817](https://github.com/ionic-team/ionic/issues/24817)
* **modal:** sheet modal now allows input focusing when backdrop disabled ([#24840](https://github.com/ionic-team/ionic/issues/24840)) ([e4ec572](https://github.com/ionic-team/ionic/commit/e4ec572043e22bd2626dbcfd204fc22a7335282c)), closes [#24581](https://github.com/ionic-team/ionic/issues/24581)





## [6.0.9](https://github.com/ionic-team/ionic/compare/v6.0.8...v6.0.9) (2022-02-23)


### Bug Fixes

* **datetime:** improve datetime sizing in modals ([#24762](https://github.com/ionic-team/ionic/issues/24762)) ([b0ac7de](https://github.com/ionic-team/ionic/commit/b0ac7de168c353ba4899cb74a2b38e25fd0cc0f1)), closes [#23992](https://github.com/ionic-team/ionic/issues/23992)
* **datetime:** month and year column order is now locale aware ([#24802](https://github.com/ionic-team/ionic/issues/24802)) ([16647b2](https://github.com/ionic-team/ionic/commit/16647b2c7290389755a4093145788f281c84b7e2)), closes [#24548](https://github.com/ionic-team/ionic/issues/24548)
* **datetime:** month picker no longer gives duplicate months on ios 14 and older ([#24792](https://github.com/ionic-team/ionic/issues/24792)) ([b6d7e1c](https://github.com/ionic-team/ionic/commit/b6d7e1c75740a61dcd02c21692e4d4632fb8df5c)), closes [#24663](https://github.com/ionic-team/ionic/issues/24663)
* **img:** draggable attribute is now inherited to inner img element ([#24781](https://github.com/ionic-team/ionic/issues/24781)) ([19ac238](https://github.com/ionic-team/ionic/commit/19ac2389eb0843173f51a12de41ac808cd8f0569)), closes [#21325](https://github.com/ionic-team/ionic/issues/21325)
* **modal:** backdropBreakpoint allows interactivity behind sheet ([#24798](https://github.com/ionic-team/ionic/issues/24798)) ([fca3f56](https://github.com/ionic-team/ionic/commit/fca3f56ca4568e63fd493debda088263caa86c64)), closes [#24797](https://github.com/ionic-team/ionic/issues/24797)
* **popover:** default alignment to 'center' for ios mode ([#24815](https://github.com/ionic-team/ionic/issues/24815)) ([243f673](https://github.com/ionic-team/ionic/commit/243f67362f25699bdb373be6b72cb9c14dc95a32))
* **react, vue:** scroll is no longer interrupted on ios ([#24791](https://github.com/ionic-team/ionic/issues/24791)) ([99c91ef](https://github.com/ionic-team/ionic/commit/99c91eff8764c9a1630adedab6a9765dd9754f7d)), closes [#24435](https://github.com/ionic-team/ionic/issues/24435)
* **select:** interface components now show correctly ([#24810](https://github.com/ionic-team/ionic/issues/24810)) ([2fc2de5](https://github.com/ionic-team/ionic/commit/2fc2de51771f4a5c3f20c6071284096e5bf31ec8)), closes [#24807](https://github.com/ionic-team/ionic/issues/24807)
* **toast:** toast is now correctly excluded from focus trapping ([#24816](https://github.com/ionic-team/ionic/issues/24816)) ([8246112](https://github.com/ionic-team/ionic/commit/8246112ca12f90edb98629ab82e27a792a1fafad)), closes [#24733](https://github.com/ionic-team/ionic/issues/24733)





## [6.0.8](https://github.com/ionic-team/ionic/compare/v6.0.7...v6.0.8) (2022-02-15)


### Bug Fixes

* **back-button, breadcrumb, item:** flip chevron icons on RTL ([#24705](https://github.com/ionic-team/ionic/issues/24705)) ([a093544](https://github.com/ionic-team/ionic/commit/a093544fdfc438ed03024285b2a35c5f645ea011))
* **datetime:** navigate to month within min range ([#24759](https://github.com/ionic-team/ionic/issues/24759)) ([7b3838c](https://github.com/ionic-team/ionic/commit/7b3838cc670de7845bb5937d204e86cdba93b6e6)), closes [#24757](https://github.com/ionic-team/ionic/issues/24757)
* **input:** only set native input value if different ([#24758](https://github.com/ionic-team/ionic/issues/24758)) ([fd031aa](https://github.com/ionic-team/ionic/commit/fd031aa1c3f05b7bfa3e0a0ee2a4793e29e22df5)), closes [#24753](https://github.com/ionic-team/ionic/issues/24753)
* **router-outlet:** getRouteId() returns the params set in setRouteId(). ([#24656](https://github.com/ionic-team/ionic/issues/24656)) ([be2205e](https://github.com/ionic-team/ionic/commit/be2205e5a2b2f8778bd1f7b4ea5cae0bf96f9ef3)), closes [#24652](https://github.com/ionic-team/ionic/issues/24652)
* **router-outlet:** navigating to same route with different params now activates component ([#24760](https://github.com/ionic-team/ionic/issues/24760)) ([abc36ae](https://github.com/ionic-team/ionic/commit/abc36ae80b060a659f7557ad90efe98b78f5ead9)), closes [#24653](https://github.com/ionic-team/ionic/issues/24653)





## [6.0.7](https://github.com/ionic-team/ionic/compare/v6.0.6...v6.0.7) (2022-02-09)


### Bug Fixes

* **angular:** inline modals now add .ion-page class correctly ([#24751](https://github.com/ionic-team/ionic/issues/24751)) ([ef46eaf](https://github.com/ionic-team/ionic/commit/ef46eafc9476a85ea3369e542f528d01d3cca0a8)), closes [#24750](https://github.com/ionic-team/ionic/issues/24750)





## [6.0.6](https://github.com/ionic-team/ionic/compare/v6.0.5...v6.0.6) (2022-02-09)


### Bug Fixes

* **action-sheet:** background includes safe area margin ([#24700](https://github.com/ionic-team/ionic/issues/24700)) ([8c22646](https://github.com/ionic-team/ionic/commit/8c22646d66e2077fc88aaacf350330097733bb9b)), closes [#24699](https://github.com/ionic-team/ionic/issues/24699)
* **angular, react,  vue:** overlays no longer throw errors when used inside tests ([#24681](https://github.com/ionic-team/ionic/issues/24681)) ([897ae4a](https://github.com/ionic-team/ionic/commit/897ae4a4546ac0dd811125d5513ef23d133a1589)), closes [#24549](https://github.com/ionic-team/ionic/issues/24549) [#24590](https://github.com/ionic-team/ionic/issues/24590)
* **datetime:** disable intersection observer during month update ([#24713](https://github.com/ionic-team/ionic/issues/24713)) ([aab4d30](https://github.com/ionic-team/ionic/commit/aab4d306f80851bfd8a02a6361e26d60faeaadb4)), closes [#24712](https://github.com/ionic-team/ionic/issues/24712)
* **datetime:** minutes only filtered when max hour matches current hour ([#24710](https://github.com/ionic-team/ionic/issues/24710)) ([231d6df](https://github.com/ionic-team/ionic/commit/231d6df622c1f5dd9ecdff6fed8f61a4bff332df)), closes [#24702](https://github.com/ionic-team/ionic/issues/24702)
* **input:** cursor position does not jump to end ([#24736](https://github.com/ionic-team/ionic/issues/24736)) ([4ff9524](https://github.com/ionic-team/ionic/commit/4ff9524e1057aa487069b5982c5f1ecdf51d982b)), closes [#24727](https://github.com/ionic-team/ionic/issues/24727)
* **input:** IME composition mode ([#24735](https://github.com/ionic-team/ionic/issues/24735)) ([c6381ce](https://github.com/ionic-team/ionic/commit/c6381ce4f90707774d1c8662bba874f7b306bd1c)), closes [#24669](https://github.com/ionic-team/ionic/issues/24669)
* **modal, popover:** quickly opening modal/popover no longer presents duplicates ([#24697](https://github.com/ionic-team/ionic/issues/24697)) ([928c5fb](https://github.com/ionic-team/ionic/commit/928c5fbfcbf3ef1b2c3074464fc20dcf1fe143ae))
* **modal:** inline modals inherit ion-page styling ([#24723](https://github.com/ionic-team/ionic/issues/24723)) ([596aad4](https://github.com/ionic-team/ionic/commit/596aad435b5102307da89dd626ca4682b78db452)), closes [#24706](https://github.com/ionic-team/ionic/issues/24706)
* **popover:** use alignment with popover options ([#24711](https://github.com/ionic-team/ionic/issues/24711)) ([f5c5c3c](https://github.com/ionic-team/ionic/commit/f5c5c3cffa4f34046b0e9471a9f193db3772180e)), closes [#24709](https://github.com/ionic-team/ionic/issues/24709)
* **router:** router push with relative path ([#24719](https://github.com/ionic-team/ionic/issues/24719)) ([d40c0c3](https://github.com/ionic-team/ionic/commit/d40c0c3a0993eaefbe5107e98958c6b0699a62c2)), closes [#24718](https://github.com/ionic-team/ionic/issues/24718)
* **select:** value is selected when given array ([#24687](https://github.com/ionic-team/ionic/issues/24687)) ([6ee7d15](https://github.com/ionic-team/ionic/commit/6ee7d159ecfff3382fadb524c5c430172d40c267)), closes [#24742](https://github.com/ionic-team/ionic/issues/24742)





## [6.0.5](https://github.com/ionic-team/ionic/compare/v6.0.4...v6.0.5) (2022-02-02)


### Bug Fixes

* **datetime:** prevent navigating to disabled months ([#24421](https://github.com/ionic-team/ionic/issues/24421)) ([b40fc46](https://github.com/ionic-team/ionic/commit/b40fc4632efcdc01f1062d9bcec826afff5cf4ea)), closes [#24208](https://github.com/ionic-team/ionic/issues/24208) [#24482](https://github.com/ionic-team/ionic/issues/24482)
* **input:** min/max compatibility with react-hook-form ([#24657](https://github.com/ionic-team/ionic/issues/24657)) ([1f91883](https://github.com/ionic-team/ionic/commit/1f918835f437a59f7a70fc59d9305647aa9c298d)), closes [#24489](https://github.com/ionic-team/ionic/issues/24489)


### Performance Improvements

* **various:** don't use lazy-loaded icon names in components ([#24671](https://github.com/ionic-team/ionic/issues/24671)) ([484de50](https://github.com/ionic-team/ionic/commit/484de5074de212dffb4bf4f73bade7acec103fe8))





## [6.0.4](https://github.com/ionic-team/ionic/compare/v6.0.3...v6.0.4) (2022-01-26)


### Bug Fixes

* **accordion:** items inside of the content now correct display borders ([#24618](https://github.com/ionic-team/ionic/issues/24618)) ([d3311df](https://github.com/ionic-team/ionic/commit/d3311df96765948d0a395e4ba99fb9117b44adcb)), closes [#24613](https://github.com/ionic-team/ionic/issues/24613)
* **col:** col no longer errors when running in non-browser environment ([#24603](https://github.com/ionic-team/ionic/issues/24603)) ([af0135c](https://github.com/ionic-team/ionic/commit/af0135ce7dbe737b2df46094fd3dc8a41bdb60ae)), closes [#24446](https://github.com/ionic-team/ionic/issues/24446)
* **datetime:** datetime locale with h23 will respect max time range ([#24610](https://github.com/ionic-team/ionic/issues/24610)) ([5925e76](https://github.com/ionic-team/ionic/commit/5925e7608ef04f8877e4dd8a80b2c8bdc1cfd4bd)), closes [#24588](https://github.com/ionic-team/ionic/issues/24588)
* **datetime:** timepicker popover will position relative to click target ([#24616](https://github.com/ionic-team/ionic/issues/24616)) ([378c632](https://github.com/ionic-team/ionic/commit/378c63264366964e6ea11e1a2ff8791a40f182d4)), closes [#24531](https://github.com/ionic-team/ionic/issues/24531) [#24415](https://github.com/ionic-team/ionic/issues/24415)
* **input:** ion-input accepts any string value ([#24606](https://github.com/ionic-team/ionic/issues/24606)) ([43c5977](https://github.com/ionic-team/ionic/commit/43c5977d48cb12331c1d3107eb73f29b92c5e049)), closes [#19884](https://github.com/ionic-team/ionic/issues/19884)
* **item:** label text aligns with input text ([#24620](https://github.com/ionic-team/ionic/issues/24620)) ([94d033c](https://github.com/ionic-team/ionic/commit/94d033c4216ae9978aed6346c1c0ea2aec4d375b)), closes [#24404](https://github.com/ionic-team/ionic/issues/24404)
* **item:** match material design character counter ([#24335](https://github.com/ionic-team/ionic/issues/24335)) ([54db1a1](https://github.com/ionic-team/ionic/commit/54db1a1e7c71c78e843370848fc768582768333e)), closes [#24334](https://github.com/ionic-team/ionic/issues/24334)
* **menu:** focus trapping with menu and overlays no longer results in errors ([#24611](https://github.com/ionic-team/ionic/issues/24611)) ([632dafc](https://github.com/ionic-team/ionic/commit/632dafcd57de5086deebdc7d586b01710aa1a3ce)), closes [#24361](https://github.com/ionic-team/ionic/issues/24361) [#24481](https://github.com/ionic-team/ionic/issues/24481)
* **modal:** native keyboard will dismiss when bottom sheet is dragged ([#24642](https://github.com/ionic-team/ionic/issues/24642)) ([525f01f](https://github.com/ionic-team/ionic/commit/525f01f086ebf95ab62af0162b876a25f50a3d4b)), closes [#23878](https://github.com/ionic-team/ionic/issues/23878)
* **range:** setting dir on ion-range to enable rtl mode now supported ([#24597](https://github.com/ionic-team/ionic/issues/24597)) ([5dba4e5](https://github.com/ionic-team/ionic/commit/5dba4e5ce0a07f69a08f2b427e8010b311910f88)), closes [#20201](https://github.com/ionic-team/ionic/issues/20201)
* **searchbar:** setting dir on ion-searchbar to enable rtl mode now supported ([#24602](https://github.com/ionic-team/ionic/issues/24602)) ([35e5235](https://github.com/ionic-team/ionic/commit/35e523564561c0f3323efa761c4654016b97ef69))
* **segment:** setting dir on ion-segment to enable rtl mode now supported ([#24601](https://github.com/ionic-team/ionic/issues/24601)) ([2940e73](https://github.com/ionic-team/ionic/commit/2940e73a4504247eecb0de6c433104f529530850)), closes [#23978](https://github.com/ionic-team/ionic/issues/23978)
* **spinner:** ensure transform doesn't overwrite circular animation ([#24643](https://github.com/ionic-team/ionic/issues/24643)) ([88ce010](https://github.com/ionic-team/ionic/commit/88ce010418eaca38786b51720c696860b417ab6d))
* **toast:** allow input focus while toast is visible ([#24572](https://github.com/ionic-team/ionic/issues/24572)) ([29f1140](https://github.com/ionic-team/ionic/commit/29f1140384ae7e1402b09c3760e168cf79833619)), closes [#24571](https://github.com/ionic-team/ionic/issues/24571)
* **toggle:** setting dir on ion-toggle to enable rtl mode now supported ([#24600](https://github.com/ionic-team/ionic/issues/24600)) ([353dbc0](https://github.com/ionic-team/ionic/commit/353dbc0537ef3b46b9ba13a365ebc5da269de4c7))





## [6.0.3](https://github.com/ionic-team/ionic/compare/v6.0.2...v6.0.3) (2022-01-19)


### Bug Fixes

* **datetime:** showing calendar grid no longer causes month to switch on ios 15 ([#24554](https://github.com/ionic-team/ionic/issues/24554)) ([3d20959](https://github.com/ionic-team/ionic/commit/3d2095922147ea3763e977412977edd9586fec5d)), closes [#24405](https://github.com/ionic-team/ionic/issues/24405)
* **item:** error slot visible in Safari ([#24579](https://github.com/ionic-team/ionic/issues/24579)) ([af01a8b](https://github.com/ionic-team/ionic/commit/af01a8b3073dce784cc042923d712b9492638d32)), closes [#24575](https://github.com/ionic-team/ionic/issues/24575)
* **menu:** remove main attribute that was supposed to removed in v5 ([#24565](https://github.com/ionic-team/ionic/issues/24565)) ([7704ac3](https://github.com/ionic-team/ionic/commit/7704ac3a3710396248590daecb945b76825a0539)), closes [#24563](https://github.com/ionic-team/ionic/issues/24563)
* **modal:** life cycle events for controller modals ([#24508](https://github.com/ionic-team/ionic/issues/24508)) ([9a15753](https://github.com/ionic-team/ionic/commit/9a15753fd95e32155abdeb490ec57cb72385ad1a)), closes [#24460](https://github.com/ionic-team/ionic/issues/24460)
* **overlays:** getTop now returns the top-most presented overlay ([#24547](https://github.com/ionic-team/ionic/issues/24547)) ([f5b4382](https://github.com/ionic-team/ionic/commit/f5b4382fd5728365e4badf39bc1dd0c149b45c2c)), closes [#19111](https://github.com/ionic-team/ionic/issues/19111)





## [6.0.2](https://github.com/ionic-team/ionic/compare/v6.0.1...v6.0.2) (2022-01-11)


### Bug Fixes

* **breadcrumb:** support routerLink on breadcrumb ([#24509](https://github.com/ionic-team/ionic/issues/24509)) ([5bb1414](https://github.com/ionic-team/ionic/commit/5bb1414f7fa04ea07954cb3f68883ee2f162586a)), closes [#24493](https://github.com/ionic-team/ionic/issues/24493)
* **css:** inline css source in source maps ([#24514](https://github.com/ionic-team/ionic/issues/24514)) ([987d46c](https://github.com/ionic-team/ionic/commit/987d46cfa6e48a932330f04f2e8eb7054b11baf8)), closes [#24441](https://github.com/ionic-team/ionic/issues/24441)
* **datetime:** add top padding to MD calendar month grid ([#24522](https://github.com/ionic-team/ionic/issues/24522)) ([bd82b5d](https://github.com/ionic-team/ionic/commit/bd82b5dc1d06ba22a5410858802d57735fdcf450)), closes [#24408](https://github.com/ionic-team/ionic/issues/24408)
* **datetime:** RTL will no longer infinitely scroll ([#24475](https://github.com/ionic-team/ionic/issues/24475)) ([8f00008](https://github.com/ionic-team/ionic/commit/8f000089c2986f292147c7f501f23c8c7d1df457)), closes [#24472](https://github.com/ionic-team/ionic/issues/24472)
* **datetime:** time picker format with hourCycle h23 ([#24476](https://github.com/ionic-team/ionic/issues/24476)) ([a3724e6](https://github.com/ionic-team/ionic/commit/a3724e6a5662c5bc1b724d80540530472827506e)), closes [#24474](https://github.com/ionic-team/ionic/issues/24474)
* **datetime:** update active day styling when day is selected ([#24454](https://github.com/ionic-team/ionic/issues/24454)) ([4304391](https://github.com/ionic-team/ionic/commit/430439191dba824c11290d7f8622fea10ced6c40)), closes [#24414](https://github.com/ionic-team/ionic/issues/24414) [#24451](https://github.com/ionic-team/ionic/issues/24451)
* **datetime:** wheel picker shows correct column order in rtl ([#24546](https://github.com/ionic-team/ionic/issues/24546)) ([c90ce31](https://github.com/ionic-team/ionic/commit/c90ce311a86ccb7c06b1cde91a4659f6682df04d)), closes [#24378](https://github.com/ionic-team/ionic/issues/24378)
* **overlays:** define custom element children ([#24439](https://github.com/ionic-team/ionic/issues/24439)) ([4715b83](https://github.com/ionic-team/ionic/commit/4715b83abb30ec5930710d16e5bfe8fc88a940ce)), closes [#24393](https://github.com/ionic-team/ionic/issues/24393)
* **popover:** allow arrow configuration with controller approach ([#24512](https://github.com/ionic-team/ionic/issues/24512)) ([b39003a](https://github.com/ionic-team/ionic/commit/b39003a4c67cd7e01d09be012c9e12d99ca1730a)), closes [#24487](https://github.com/ionic-team/ionic/issues/24487)
* **radio:** fix radio not showing checked state when not in a group ([#24423](https://github.com/ionic-team/ionic/issues/24423)) ([94a781c](https://github.com/ionic-team/ionic/commit/94a781cb6a3d92c5e6cab1a7603bfe25826a753c))
* **react,vue:** backdrop for inline modal/popover overlay ([#24453](https://github.com/ionic-team/ionic/issues/24453)) ([77f8412](https://github.com/ionic-team/ionic/commit/77f8412b746222793cd9d17f12f50d512ab5e886)), closes [#24449](https://github.com/ionic-team/ionic/issues/24449)
* **react:** building app for production now works correctly with vite ([#24515](https://github.com/ionic-team/ionic/issues/24515)) ([32fad3d](https://github.com/ionic-team/ionic/commit/32fad3d02cb6b012a772de03eafe3e3a6b1300e0)), closes [#24229](https://github.com/ionic-team/ionic/issues/24229)
* **refresher:** import icons to avoid errors in react and vue ([#24525](https://github.com/ionic-team/ionic/issues/24525)) ([388622f](https://github.com/ionic-team/ionic/commit/388622f9734b7b832bca3ede99820a7124faa618)), closes [#24480](https://github.com/ionic-team/ionic/issues/24480)
