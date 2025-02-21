# Changelog

This file was generated using [@jscutlery/semver](https://github.com/jscutlery/semver).

## [0.1.13](https://github.com/qwikifiers/qwik-ui/compare/headless-0.1.12...headless-0.1.13) (2023-08-01)


### Features

* **accordion:** dynamic tests, docs, refactor, accordion ready state :) ([b21617b](https://github.com/qwikifiers/qwik-ui/commit/b21617bac8aa3e2fb009126555461830125b7ba4))



## [0.1.12](https://github.com/qwikifiers/qwik-ui/compare/headless-0.1.11...headless-0.1.12) (2023-07-28)


### Bug Fixes

* **accordion:** proper generic type annotation ([598a22c](https://github.com/qwikifiers/qwik-ui/commit/598a22c0d5cf78cf455e8a4de531cd447519f7b1))



## [0.1.11](https://github.com/qwikifiers/qwik-ui/compare/headless-0.1.10...headless-0.1.11) (2023-07-28)


### Bug Fixes

* **accordion:** add propfunction type ([66e89b6](https://github.com/qwikifiers/qwik-ui/commit/66e89b670ca3386e6b4e8cb068a0f348d51d5c01))
* **accordion:** ci / lint warning fixes ([f7de15d](https://github.com/qwikifiers/qwik-ui/commit/f7de15d9744bca65d5fe3587b77457c449beb28d))
* **accordion:** defaultValue flicker fix ([f8a7bd0](https://github.com/qwikifiers/qwik-ui/commit/f8a7bd0f5439c255f59a2f341cf789a683bf6cc8))
* **accordion:** docs typo, cleanup comments, comment out dynamic tests for now ([049d788](https://github.com/qwikifiers/qwik-ui/commit/049d7885a51ac273ec1bb7781d6db6c07969195d))
* **accordion:** fixed animated height calculation for keyframes ([bb320ef](https://github.com/qwikifiers/qwik-ui/commit/bb320ef3dd6ef6b6ec9e1ab1d0063ee8c274294f))
* **accordion:** proper naming of QRL ([669863e](https://github.com/qwikifiers/qwik-ui/commit/669863ed88bd2d8b9f4056ae9bcb528c69e25fe9))
* **eslint props task error:** eslint props task error fix ([048d9ce](https://github.com/qwikifiers/qwik-ui/commit/048d9cee18ba013e4e9ee88ab93c485ede8e2313))


### Code Refactoring

* **select:** update event handlers ([bc08c54](https://github.com/qwikifiers/qwik-ui/commit/bc08c54872275ba8dfd1d0cf81733ae8cd3e70eb))


### Features

* **accordion & website:** accordion examples, feats, critical fix, website font build fix ([a6a213b](https://github.com/qwikifiers/qwik-ui/commit/a6a213beb61fab01a123b46e67be0fa5fe10deaf))
* **accordion:** possible ready state, major refactor, major docs additions ([fffbb87](https://github.com/qwikifiers/qwik-ui/commit/fffbb8703b52af7d12cac53cb37dbd8b460c1756))
* **accordion:** small code refactor, and props array for consumers ([1e37d53](https://github.com/qwikifiers/qwik-ui/commit/1e37d5349a66fc5334e29c778130bb6363ab9baa))
* **Select:** add preliminary required behaviour ([009be72](https://github.com/qwikifiers/qwik-ui/commit/009be72d8b6c43a9b3bad9331eb20e459dfdb11e))


### BREAKING CHANGES

* **select:** Previously, optionValue automatically emits as a text node to the <li> element for
SelectOption which was potentially problematic if the user has different values for what should be
displayed instead of what is stored in state for form submission



## [0.1.10](https://github.com/qwikifiers/qwik-ui/compare/headless-0.1.9...headless-0.1.10) (2023-07-13)


### Bug Fixes

* **headless/tabs:** disabled edges working now ([92ae8c8](https://github.com/qwikifiers/qwik-ui/commit/92ae8c877622429dffc24a3d9fdc2a957ffbedac))


### Features

* **accordion & banner:** major accordion refactor and banner component for docs ([c5d4017](https://github.com/qwikifiers/qwik-ui/commit/c5d40172243ac9fa71917fea1f44c2dc96ccc340))
* **headless/tabs:** add custom selected class ([0590bf4](https://github.com/qwikifiers/qwik-ui/commit/0590bf424b76f773be60f0e2ead52ea8861a96ca))



## [0.1.9](https://github.com/qwikifiers/qwik-ui/compare/headless-0.1.8...headless-0.1.9) (2023-07-08)


### Bug Fixes

* types path in all packages ([d1baf5e](https://github.com/qwikifiers/qwik-ui/commit/d1baf5ea69a23d5f8f9700c0e6d5bb006c642cf9))



## [0.1.8](https://github.com/qwikifiers/qwik-ui/compare/headless-0.1.7...headless-0.1.8) (2023-07-04)


### Bug Fixes

* **attempted build fix:** n ([3d3158a](https://github.com/qwikifiers/qwik-ui/commit/3d3158a1bda10ab3f182d127e75f9d9f81bdc3d7))
* **autocomplete & website deploy fixes:** autocomplete dropdown fix & deploy fix ([6a1710e](https://github.com/qwikifiers/qwik-ui/commit/6a1710e65e9aa038f70a12a444e4747d3450c062))
* **autocomplete file issue:** n ([f44779d](https://github.com/qwikifiers/qwik-ui/commit/f44779d951771b1f513d70c7366725d7da53f2f3))
* **autocomplete issue:** n ([81c1acb](https://github.com/qwikifiers/qwik-ui/commit/81c1acb300caedc02546dbd44f2a0f4dbc160105))
* content blocking aria-expanded and select visible after computed ([0e97e1b](https://github.com/qwikifiers/qwik-ui/commit/0e97e1b7c8722638f00513dae522781bd0b0463b))
* **cypress:** attempt to fix async error in cypress ([8240870](https://github.com/qwikifiers/qwik-ui/commit/82408705e337d638e31f7d6ce385cc993ff2401b))
* **fixed enter key not properly hiding listbox:** enter key now hides the listbow ([899a56d](https://github.com/qwikifiers/qwik-ui/commit/899a56dcaeaea3f1e32f244e5fe07c7c65d2935b))
* **headless/tabs:** removed empty if ([1e8be6b](https://github.com/qwikifiers/qwik-ui/commit/1e8be6b15dc1244d32ec00960250baf72b6464de))
* **headless/tabs:** render on server ([8309d7b](https://github.com/qwikifiers/qwik-ui/commit/8309d7b4e5c93058e4fbb5f7951e8f198f895a36))
* **headless/tabs:** restored dynamic handling ([c5621a5](https://github.com/qwikifiers/qwik-ui/commit/c5621a53c0258fb4c1ad1f30a142367d74009ade))
* **headless/tabs:** specific preventDefault ([a7bd27b](https://github.com/qwikifiers/qwik-ui/commit/a7bd27b9ecf841386afc571f9bfee8dceccec6c8))
* **headless:** added tests to ts exclude ([8bc36a0](https://github.com/qwikifiers/qwik-ui/commit/8bc36a0c5cc4ba86a14a78742388ed89f3d595f4))
* **hopeful fix for autocomplete directory:** n ([f6368ae](https://github.com/qwikifiers/qwik-ui/commit/f6368ae4894b8c5ee96a4f4fc488ee18901d9a6b))
* moved useId outside fo template ([ce2799f](https://github.com/qwikifiers/qwik-ui/commit/ce2799f1181ff5b970dab0b867e9bd12c878b5d3))
* **popover-content:** add aria-label attr to pass a11y cypress assertion ([dd06273](https://github.com/qwikifiers/qwik-ui/commit/dd06273facf460462e1e1d1868f05627ef93425c))
* **previous commit:** overwrite previous commit ([3767c44](https://github.com/qwikifiers/qwik-ui/commit/3767c4405990c72edee776963bf3a9d339bfb081))
* tabs flicker ([e2227c2](https://github.com/qwikifiers/qwik-ui/commit/e2227c21f9d1dd89d1074f223e94753aa8530a4c))
* tabs, finally 😅 ([9d579b6](https://github.com/qwikifiers/qwik-ui/commit/9d579b68c91baaaa03b0872deb91c46a4df44fae))
* **tabs:** wrong labelledBy value ([8cb43c9](https://github.com/qwikifiers/qwik-ui/commit/8cb43c97fa2d8b359ede08121f1a01b6504f6780))


### Features

* **accessibility:** axe accessibility recommendation changes ([ef1e1f2](https://github.com/qwikifiers/qwik-ui/commit/ef1e1f295c833fd5acfb59db61e33b4cb5554e51))
* add carousel component ([#280](https://github.com/qwikifiers/qwik-ui/issues/280)) ([396aeb1](https://github.com/qwikifiers/qwik-ui/commit/396aeb1843740c3cf7f50520dc2ebb3882692e77))
* **component:** add support for button custom labels ([b71af63](https://github.com/qwikifiers/qwik-ui/commit/b71af63ad2032fcf23942d8d2c8156d355cd359d))
* **component:** add support to customize the default and active classes in button ([8ad71bf](https://github.com/qwikifiers/qwik-ui/commit/8ad71bf66059582f7818d113c5a8e5c3c2d89e54))
* **cypress select tests:** added tests for select component using cypress ([515e77d](https://github.com/qwikifiers/qwik-ui/commit/515e77ddc76e69ea5ed2c51a2a49097541059c19))
* **disabled options for autocomplete:** disabled options for autocomplete ([f9c01b3](https://github.com/qwikifiers/qwik-ui/commit/f9c01b3da86bac96b41921f78c3b23b331c4d84d))
* **docs:** add preview/code switching to examples ([05862dc](https://github.com/qwikifiers/qwik-ui/commit/05862dc73123b46b4f1153726af09a21aa6c62db))
* **filtering, autocomplete functionality , along with selecting an object:** autocomplete works ([f3cd73c](https://github.com/qwikifiers/qwik-ui/commit/f3cd73c179ba902c58d3ac522bf6b4bbadb1ed3e))
* **headless/tabs:** add right arrow support ([1284b1e](https://github.com/qwikifiers/qwik-ui/commit/1284b1e1b48747de42993368aaab21a019e22746))
* **headless/tabs:** end,home,pagedn,pageup ([745c8bd](https://github.com/qwikifiers/qwik-ui/commit/745c8bd44fdb50c8a550d2655830b9f6414b2ec2))
* **headless/tabs:** handle left arrow, home, end ([487de0e](https://github.com/qwikifiers/qwik-ui/commit/487de0efc2587392d3bad2a49a40b98551c36541))
* **headless/tabs:** handle vertical tabs ([1a6ae5a](https://github.com/qwikifiers/qwik-ui/commit/1a6ae5af7417640b0ed624f25e35bbd28c2a43b1))
* **headless/tabs:** onSelectedIndexChange ([a43c87a](https://github.com/qwikifiers/qwik-ui/commit/a43c87aba2d778deafdfc206935b233b0ebf089f))
* **headless:** tabs  selectedIndex impl & tests ([74fb635](https://github.com/qwikifiers/qwik-ui/commit/74fb635e6887cc58d8eb7e80826bfad42aa1e2e1))
* **initial api additions & scaffolding:** initial API, Setting up types & props ([99e31e6](https://github.com/qwikifiers/qwik-ui/commit/99e31e6ecd1f2b2df5b680a11017e353cfb40786))
* **keyboard navigation & aria:** added keyboard navigation ([09689c0](https://github.com/qwikifiers/qwik-ui/commit/09689c053429c6ec0744ae7d320e11b5d54b8eea))
* **listbox toggle, floating ui anchor additiongs, listbox wrapper:** part of the autocomplete added ([593aa80](https://github.com/qwikifiers/qwik-ui/commit/593aa80af6c8df565001a4209d9cd358cb9ecc37))
* **popover-content:** add aria-modal attr ([4b8aa11](https://github.com/qwikifiers/qwik-ui/commit/4b8aa11398d0f05d79f2986e6db46f1d8d8d0c71))
* **popover:** add roles to popover trigger and content ([4d8c94a](https://github.com/qwikifiers/qwik-ui/commit/4d8c94a72023ebb6cc5614bbf5c6e617d4fa1322))



## [0.1.7](https://github.com/qwikifiers/qwik-ui/compare/headless-0.1.6...headless-0.1.7) (2023-04-29)

### Bug Fixes

- types on published kits ([a05f758](https://github.com/qwikifiers/qwik-ui/commit/a05f7586fa04abc676d145f48c38950327022468))

## [0.1.6](https://github.com/qwikifiers/qwik-ui/compare/headless-0.1.5...headless-0.1.6) (2023-04-29)

### Bug Fixes

- build paths ([aabbd0f](https://github.com/qwikifiers/qwik-ui/commit/aabbd0f760d0bee56451433070cc8d1b31df7c53))

## [0.1.5](https://github.com/qwikifiers/qwik-ui/compare/headless-0.1.4...headless-0.1.5) (2023-04-29)

## [0.1.4](https://github.com/qwikifiers/qwik-ui/compare/headless-0.1.3...headless-0.1.4) (2023-04-28)

### Bug Fixes

- add css inline definitions ([#276](https://github.com/qwikifiers/qwik-ui/issues/276)) ([0ed7d96](https://github.com/qwikifiers/qwik-ui/commit/0ed7d961ee0d4249afbb569bedc9bc3e18fa5807))
- project folders and linter ([#205](https://github.com/qwikifiers/qwik-ui/issues/205)) ([198f729](https://github.com/qwikifiers/qwik-ui/commit/198f729b1263797941ee21f82a2c71b20727c45e))
- remove any to satisfy the picky linter ✅ ([737860b](https://github.com/qwikifiers/qwik-ui/commit/737860bc6f06d523e813c0088dc1265dd36ed0f3))
- solve headless linter warnings ([a97d826](https://github.com/qwikifiers/qwik-ui/commit/a97d826eff4fb16f51b027c87829e9c3b31f7f1e))
- solve linter errors ([100ed43](https://github.com/qwikifiers/qwik-ui/commit/100ed4376b7cbfe454cef9ca7b1743c6335bf069))
- **toggle component:** renamed prop & change funcionality in Toggle ([#210](https://github.com/qwikifiers/qwik-ui/issues/210)) ([d96c401](https://github.com/qwikifiers/qwik-ui/commit/d96c40130fc8bf38036d837c478de5ed503f24b1)), closes [#209](https://github.com/qwikifiers/qwik-ui/issues/209)
- tooltip works only the first time ([#269](https://github.com/qwikifiers/qwik-ui/issues/269)) ([29b14ff](https://github.com/qwikifiers/qwik-ui/commit/29b14ff91981d6782885993422f1e7ea6bb9f2dc))
- update config to enable cypress component testing ([ff170b8](https://github.com/qwikifiers/qwik-ui/commit/ff170b8491a58f2fd300a62745f5e7be8e2d45fd))

### Features

- add checkbox ([#154](https://github.com/qwikifiers/qwik-ui/issues/154)) ([b8d9a73](https://github.com/qwikifiers/qwik-ui/commit/b8d9a7312a276dfa0c96a4f0b0592e08b134f9fe)), closes [#128](https://github.com/qwikifiers/qwik-ui/issues/128)
- add daisy slider component ([#199](https://github.com/qwikifiers/qwik-ui/issues/199)) ([f9b997d](https://github.com/qwikifiers/qwik-ui/commit/f9b997dcbcc2edc1c23948c93f4dc783e7b620d6))
- add input phone ([#243](https://github.com/qwikifiers/qwik-ui/issues/243)) ([8c8b1aa](https://github.com/qwikifiers/qwik-ui/commit/8c8b1aa6a825852ed3bde0695514b9f7d676ecaf))
- added a11y to storybook ([2310d71](https://github.com/qwikifiers/qwik-ui/commit/2310d71ef378c8852704a472da903b1a82ec6f48))
- auto country code ([#249](https://github.com/qwikifiers/qwik-ui/issues/249)) ([91af379](https://github.com/qwikifiers/qwik-ui/commit/91af3798fe9c6e298c4747208b8db64cfd1bd3c6))
- base pagination ([#151](https://github.com/qwikifiers/qwik-ui/issues/151)) ([76aed0e](https://github.com/qwikifiers/qwik-ui/commit/76aed0e6ae2e9c67051ab574f0d1e3c9313904e6)), closes [#130](https://github.com/qwikifiers/qwik-ui/issues/130) [#15](https://github.com/qwikifiers/qwik-ui/issues/15)
- **component:** Add Badge Component ([#222](https://github.com/qwikifiers/qwik-ui/issues/222)) ([fe15e6c](https://github.com/qwikifiers/qwik-ui/commit/fe15e6ce8a96941f295887739f5dff4cbc296c21)), closes [#219](https://github.com/qwikifiers/qwik-ui/issues/219)
- **component:** add carousel component ([#258](https://github.com/qwikifiers/qwik-ui/issues/258)) ([d258189](https://github.com/qwikifiers/qwik-ui/commit/d2581896653b6291f5b1ed97a6802069f2b7ddc3))
- **component:** Add loading indicator ([#207](https://github.com/qwikifiers/qwik-ui/issues/207)) ([923fd4e](https://github.com/qwikifiers/qwik-ui/commit/923fd4e356f4855fa1be0e6ce449ed3146683231))
- **component:** add navigation bar ([#213](https://github.com/qwikifiers/qwik-ui/issues/213)) ([dfd89e0](https://github.com/qwikifiers/qwik-ui/commit/dfd89e04b2b765476d3f31ea066af56050318ff8)), closes [#200](https://github.com/qwikifiers/qwik-ui/issues/200)
- **component:** add new Breadcrumb component ([#212](https://github.com/qwikifiers/qwik-ui/issues/212)) ([5b526cc](https://github.com/qwikifiers/qwik-ui/commit/5b526cc2cc23acc9fecd3aefefa881af0deb33c4))
- **component:** an alert component ([#218](https://github.com/qwikifiers/qwik-ui/issues/218)) ([d3daf68](https://github.com/qwikifiers/qwik-ui/commit/d3daf68e2f1a64cc9f267c4ca41262942bd92e0d)), closes [#217](https://github.com/qwikifiers/qwik-ui/issues/217)
- **component:** improve pagination ([#208](https://github.com/qwikifiers/qwik-ui/issues/208)) ([5d86b51](https://github.com/qwikifiers/qwik-ui/commit/5d86b510809276e748ad990cd0310bd88155c391))
- **input:** add input component ([#257](https://github.com/qwikifiers/qwik-ui/issues/257)) ([43c5f53](https://github.com/qwikifiers/qwik-ui/commit/43c5f53cbcd5ca5d08f522fa0707a251026a046e))

### BREAKING CHANGES

- **toggle component:** any component who uses daisy-toggle, will have to rename `checked` to `pressed`

## [0.1.3](https://github.com/qwikifiers/qwik-ui/compare/headless-0.1.2...headless-0.1.3) (2023-02-23)

## [0.1.2](https://github.com/qwikifiers/qwik-ui/compare/headless-0.1.1...headless-0.1.2) (2023-02-23)

### Bug Fixes

- debounce showing/hiding the tooltip ([#159](https://github.com/qwikifiers/qwik-ui/issues/159)) ([f889444](https://github.com/qwikifiers/qwik-ui/commit/f889444da72e7c1f7f9ba3bb05fb470ad057a017))
- deprecated useClientEffect$ and createContext hooks ([#187](https://github.com/qwikifiers/qwik-ui/issues/187)) ([ff6016f](https://github.com/qwikifiers/qwik-ui/commit/ff6016f88f19a6a0f915afe5f70f5576e3c3be1a))
- **rating:** add useId as key for each RatingIcon ([#162](https://github.com/qwikifiers/qwik-ui/issues/162)) ([b9f47b1](https://github.com/qwikifiers/qwik-ui/commit/b9f47b1bed4898db9056a397b725fa07e2ab03a3))
- remove any from Component<any> ([#190](https://github.com/qwikifiers/qwik-ui/issues/190)) ([35bc6fa](https://github.com/qwikifiers/qwik-ui/commit/35bc6faac9717a29c8162486c08d0ef21a809641))
- remove double await ([97c9f0e](https://github.com/qwikifiers/qwik-ui/commit/97c9f0eb9a971e1d793add29fd7accec48c8d835)), closes [#75](https://github.com/qwikifiers/qwik-ui/issues/75)
- remove warnings ([#182](https://github.com/qwikifiers/qwik-ui/issues/182)) ([befcbc5](https://github.com/qwikifiers/qwik-ui/commit/befcbc5509708a3c222a6a634cce4dc5bf93dfb4))
- rub up tests ([0f2adf9](https://github.com/qwikifiers/qwik-ui/commit/0f2adf91822a3c40072f72c07463024849cd79d1))

### Features

- **component:** add draft Popover component ([#140](https://github.com/qwikifiers/qwik-ui/issues/140)) ([15950fe](https://github.com/qwikifiers/qwik-ui/commit/15950fe87a23a35ce8d6a5d61a2599a2687abf7d))
- **component:** add new Progress Bar component ([#174](https://github.com/qwikifiers/qwik-ui/issues/174)) ([5bf8262](https://github.com/qwikifiers/qwik-ui/commit/5bf8262e86abd20590baa81cc69988dd5daf307b)), closes [#129](https://github.com/qwikifiers/qwik-ui/issues/129)
- **component:** add radio component ([#178](https://github.com/qwikifiers/qwik-ui/issues/178)) ([35b7a60](https://github.com/qwikifiers/qwik-ui/commit/35b7a60ceda6233587fe4f6ffe2b187e7ef5757e)), closes [#128](https://github.com/qwikifiers/qwik-ui/issues/128)
- **component:** add the Accordion Component ([#176](https://github.com/qwikifiers/qwik-ui/issues/176)) ([523d19d](https://github.com/qwikifiers/qwik-ui/commit/523d19d124c245f3973b3b6ac0adbb82a6820e60)), closes [#126](https://github.com/qwikifiers/qwik-ui/issues/126)
- **component:** add the rating component ([#149](https://github.com/qwikifiers/qwik-ui/issues/149)) ([0c07dd9](https://github.com/qwikifiers/qwik-ui/commit/0c07dd993f7ea46dc93420625ca8bbb8c3dc2e69))
- **component:** added a new headless slider component ([#169](https://github.com/qwikifiers/qwik-ui/issues/169)) ([80f860f](https://github.com/qwikifiers/qwik-ui/commit/80f860f1536e2364eddd6295a4375639bbcc6b4e))
- **component:** added a Toast component that reads the label, the po… ([#157](https://github.com/qwikifiers/qwik-ui/issues/157)) ([019f7fa](https://github.com/qwikifiers/qwik-ui/commit/019f7fa1e72ef7bd85c19adec3184add33e55010))
- headless menu ([#158](https://github.com/qwikifiers/qwik-ui/issues/158)) ([1ec959e](https://github.com/qwikifiers/qwik-ui/commit/1ec959eb81c127161db52ab8ab0d6e27ac34e7a1))

## [0.1.1](https://github.com/qwikifiers/qwik-ui/compare/headless-0.1.0...headless-0.1.1) (2023-02-09)

### Bug Fixes

- actions/test ([#107](https://github.com/qwikifiers/qwik-ui/issues/107)) ([816fa37](https://github.com/qwikifiers/qwik-ui/commit/816fa377cc7996ffb0cf5985068a205d7df9d197))
- **component:** add TS support for HTMLButton properties ([b3fca21](https://github.com/qwikifiers/qwik-ui/commit/b3fca210dbe026c653e0f4a7518ed7621bd1aeda))

- add select implementation (#88) ([ba67163](https://github.com/qwikifiers/qwik-ui/commit/ba671637546cd2211960f05fb3187fd173517958)), closes [#88](https://github.com/qwikifiers/qwik-ui/issues/88) [#76](https://github.com/qwikifiers/qwik-ui/issues/76) [#76](https://github.com/qwikifiers/qwik-ui/issues/76) [#76](https://github.com/qwikifiers/qwik-ui/issues/76) [#88](https://github.com/qwikifiers/qwik-ui/issues/88) [#88](https://github.com/qwikifiers/qwik-ui/issues/88) [#88](https://github.com/qwikifiers/qwik-ui/issues/88) [#97](https://github.com/qwikifiers/qwik-ui/issues/97) [#88](https://github.com/qwikifiers/qwik-ui/issues/88) [#88](https://github.com/qwikifiers/qwik-ui/issues/88)

### Features

- add Button component ([#98](https://github.com/qwikifiers/qwik-ui/issues/98)) ([58f1ff1](https://github.com/qwikifiers/qwik-ui/commit/58f1ff1fcabbe9f0cfb66203000e84d76096d5b4))
- **component:** add ButtonGroup component ([#103](https://github.com/qwikifiers/qwik-ui/issues/103)) ([30d9f69](https://github.com/qwikifiers/qwik-ui/commit/30d9f697e9cda54d9aa7ee452fe870d555ad0ce5))

### BREAKING CHANGES

- Value on option elements are set to 0 despite value prop being successfully passed
