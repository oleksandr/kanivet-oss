# Changelog

## [0.5.0](https://github.com/oleksandr/kanivet-oss/compare/v0.4.0...v0.5.0) (2026-10-02)


### Features

* add GitHub star prompt and bug reporting with persistent opt-out ([9c08c20](https://github.com/oleksandr/kanivet-oss/commit/9c08c20a2a8dbfe9b60aabdd130dcaedd4af4b93))
* **cloud:** reach EKS contexts through AWS SSO with a chosen role ([7da0065](https://github.com/oleksandr/kanivet-oss/commit/7da0065c08324b27c1a596c2e607381a8e911ca1))
* **frontend:** adopt the macOS-native design system ([158069e](https://github.com/oleksandr/kanivet-oss/commit/158069e849bc7a5d5017523dde0873fd8c2ec6e9))
* **frontend:** layered Kanivet mark and regenerated app icons ([fe95db4](https://github.com/oleksandr/kanivet-oss/commit/fe95db42209874003bb7b4254a94ce72ee7c4097))
* **frontend:** Perf/fast tab switching ([#30](https://github.com/oleksandr/kanivet-oss/issues/30)) ([c68224e](https://github.com/oleksandr/kanivet-oss/commit/c68224e70dbb986ce4177b4db61c60685d60a360))
* **frontend:** purpose-built Kubernetes resource icon pack ([6f030ed](https://github.com/oleksandr/kanivet-oss/commit/6f030eddc38163f51e24463f69a8b6b66634b770))
* **frontend:** refresh resource icon pack and Kanivet mark ([3996cef](https://github.com/oleksandr/kanivet-oss/commit/3996ceff76aea5eb660b9c308211537cff6eef1b))
* **pods:** link a pod to its node and match node names in list search ([48949cb](https://github.com/oleksandr/kanivet-oss/commit/48949cbcf3e96532f89f519aaa094175dde3195c))
* show CRD printer columns on custom resource lists ([9d3212c](https://github.com/oleksandr/kanivet-oss/commit/9d3212c8372fe148c4210a0d9c95bd2e7e410a36))
* show CRD printer columns on custom resource lists ([03b572e](https://github.com/oleksandr/kanivet-oss/commit/03b572e8e16da4869b5ff4469e696b478348962c))


### Bug Fixes

* bounded startup index load, DB retention, vcluster health recovery ([e7d9ed8](https://github.com/oleksandr/kanivet-oss/commit/e7d9ed801b9d5ca6d40fddda249c8557a744b887))
* **cloud:** read sso_region from legacy AWS profiles ([032141f](https://github.com/oleksandr/kanivet-oss/commit/032141faaaa4f88d442ab80e6c91da44072be0a0))
* **cloud:** read sso_region from legacy AWS profiles ([dab641e](https://github.com/oleksandr/kanivet-oss/commit/dab641e5a1fe97fe4841594c160ba38c7057ef17))
* **cloud:** rework AWS SSO, GCP and Azure sign-in around the shared CLI caches ([b98dc6a](https://github.com/oleksandr/kanivet-oss/commit/b98dc6ae8106b8c418746c60e60f496ee4ca6ace))
* **cloud:** rework AWS SSO, GCP and Azure sign-in; make the title bar draggable ([c27d2cb](https://github.com/oleksandr/kanivet-oss/commit/c27d2cbea394677b256351ba055fd9e9f20e9c8b))
* **cloud:** stop counting down the hourly AWS access token ([983bc83](https://github.com/oleksandr/kanivet-oss/commit/983bc831c46731c0e10798c2fc84eb7110d71104))
* consistent kind and resource naming in search, single sidebar selection, detail pane styling ([f434c63](https://github.com/oleksandr/kanivet-oss/commit/f434c63a5017f19a3be0b902690559a9c0c7e8b5))
* **db:** purge search rows written before kind normalization ([0b4ebc9](https://github.com/oleksandr/kanivet-oss/commit/0b4ebc9829494362f857250ce18d09429e7e9411))
* **db:** version the schema, purge stale and orphaned rows, reclaim space ([1122727](https://github.com/oleksandr/kanivet-oss/commit/1122727db947f832d68a4710d8a60a54e77c2875))
* **details:** keep a detail load that finishes after a cluster tab switch ([e9b3b91](https://github.com/oleksandr/kanivet-oss/commit/e9b3b91c7eaff67d2e5664a03b57fedfd4ce7cf0))
* **edit:** never recreate a deleted resource when saving from the YAML editor ([78e0a8f](https://github.com/oleksandr/kanivet-oss/commit/78e0a8fda4ed7685f0fc9aee8e2febd9b724047d))
* enable automated releases and resolve platform failures ([#2](https://github.com/oleksandr/kanivet-oss/issues/2)) ([4bcea66](https://github.com/oleksandr/kanivet-oss/commit/4bcea669a47a2a6209379d2833f120601d855a30))
* **events:** scope resource events by kind, not just name and namespace ([2db4412](https://github.com/oleksandr/kanivet-oss/commit/2db441269d4bb6246043c8cab1792eadf40d35b6))
* extended fonts family to include more developer friendly fonts so the terminal is rendering proper prompts/symbols ([570b1c3](https://github.com/oleksandr/kanivet-oss/commit/570b1c3344e92110ce73cc0c4983bf8ac5e60d07))
* **frontend:** give discovered kinds a fitting icon instead of a document ([e18ca88](https://github.com/oleksandr/kanivet-oss/commit/e18ca881be9d52991f53df4ff656da32ada3d372))
* **frontend:** open search results through the tree's resource node ([e883448](https://github.com/oleksandr/kanivet-oss/commit/e8834482f32b3fff48e1a82f50c355a4881cfd4b))
* **frontend:** preserve conflict protection when saving YAML ([4fe7ad8](https://github.com/oleksandr/kanivet-oss/commit/4fe7ad838e8ef4c1956c3d021124c20a83213ab0))
* **frontend:** preserve conflict protection when saving YAML ([af33937](https://github.com/oleksandr/kanivet-oss/commit/af33937c42c0ed7b09a9c25b088de42430934e05))
* **frontend:** report failed resource actions accurately ([54a3af2](https://github.com/oleksandr/kanivet-oss/commit/54a3af27baeaf7da23ed36b0d7fed1f1ef9a25ff))
* **frontend:** report failed resource actions accurately ([65ad270](https://github.com/oleksandr/kanivet-oss/commit/65ad2701231863dec6d22efe7e7e9c2399765254))
* **frontend:** resume log streams after reconnecting ([1ac561d](https://github.com/oleksandr/kanivet-oss/commit/1ac561df026dc8da6f81de8d51ef074c55924e18))
* **frontend:** resume log streams after reconnecting ([aa7bb88](https://github.com/oleksandr/kanivet-oss/commit/aa7bb88110dcf9aa4c8ac0d7edaec054c7f4ebea))
* **k8s:** count resources without downloading the whole list ([702ab2d](https://github.com/oleksandr/kanivet-oss/commit/702ab2d10cee69cba6e9a40496f7cadaa51e704b))
* **logs:** stop log streams from outliving their handler ([33b949a](https://github.com/oleksandr/kanivet-oss/commit/33b949ab16d787081b08e76a18dd4c3c3ab02cd6))
* **logs:** stop log streams from outliving their handler ([75acef1](https://github.com/oleksandr/kanivet-oss/commit/75acef1f220f604dd1fe6abb59006845c3b78fc7))
* **metrics:** show Mimir discovery failures instead of an empty list ([430b67e](https://github.com/oleksandr/kanivet-oss/commit/430b67ea23eacbea19161be402f72336023f8448))
* normalize CRLF when testing workflow files on Windows ([#28](https://github.com/oleksandr/kanivet-oss/issues/28)) ([7942edc](https://github.com/oleksandr/kanivet-oss/commit/7942edc7bf976da730d84f98b59b089b5696d831))
* **panes:** give each cluster tab its own pane layout ([6df842d](https://github.com/oleksandr/kanivet-oss/commit/6df842dc602c483d199be7ca6fb5995b077dde52))
* **panes:** give each cluster tab its own pane layout ([0e60732](https://github.com/oleksandr/kanivet-oss/commit/0e6073250f23ed519f71c1d134808fb4e662ea41))
* resolve Windows release-candidate AWS config test failure ([#31](https://github.com/oleksandr/kanivet-oss/issues/31)) ([fe88541](https://github.com/oleksandr/kanivet-oss/commit/fe88541745f994d6df71a9adb21253cced4f074a))
* **search:** index one document per object, with the discovery kind and resource name ([b5ff5f7](https://github.com/oleksandr/kanivet-oss/commit/b5ff5f7c3e5c2c77e3b95d874296ea51d4775406))
* **search:** search every selected cluster instead of only the first ([37d9381](https://github.com/oleksandr/kanivet-oss/commit/37d93815e0ffe052dfafa852fd760d1a232193ef))
* **sidebar,metrics:** keep the outline indented and the metric controls compact ([94d4ef9](https://github.com/oleksandr/kanivet-oss/commit/94d4ef99b384154f07d8f6dc74cda70b5d9815e0))
* **sidebar:** drop the kanivetIDE root node and highlight a single selected row ([e813c9a](https://github.com/oleksandr/kanivet-oss/commit/e813c9acfd02ce75b729abb44b2bfe7c6c4eee9f))
* **sidebar:** keep resource counts on screen while a category refreshes ([d8f7ce2](https://github.com/oleksandr/kanivet-oss/commit/d8f7ce2fe2ccd91f921c2e7404f7f2c5dac0ff2a))
* six behaviour fixes — terminal reconnect, kind-scoped events, action error toasts, no recreate on edit, multi-cluster search, Mimir discovery errors ([a59cc01](https://github.com/oleksandr/kanivet-oss/commit/a59cc0126af3e160a117613a2fe36bbf5f29f99c))
* **tabbar:** make the title bar draggable and zoomable again ([fedd992](https://github.com/oleksandr/kanivet-oss/commit/fedd992a21018e3ed852cac1a3e95d6f7ce98b68))
* **tabs:** start keyboard focus in the sidebar for a newly opened cluster ([8a24272](https://github.com/oleksandr/kanivet-oss/commit/8a2427211905fd7ee0f5701494f9e292ec8a1f6f))
* **terminal:** recreate the shell session after a WebSocket reconnect ([a2a03c3](https://github.com/oleksandr/kanivet-oss/commit/a2a03c3fba5627e4dab6131592953ea6e181220e))
* **themes:** tolerate duplicate JSON keys in theme/VSIX parsing ([4dd3c09](https://github.com/oleksandr/kanivet-oss/commit/4dd3c095bda2f9b10a1d2d944c70f4dda47f82a1))
* **ui:** surface failed operational actions as error toasts ([03d25f3](https://github.com/oleksandr/kanivet-oss/commit/03d25f3546c8e28986270c00a74ce692362951a8))
* **vcluster:** return the supervisor to healthy after a transient probe failure ([dd25b7f](https://github.com/oleksandr/kanivet-oss/commit/dd25b7f4484302c74c70ca910cc3b40da17bbc08))


### Performance

* port upstream PR [#121](https://github.com/oleksandr/kanivet-oss/issues/121) efficiency improvements ([33bf576](https://github.com/oleksandr/kanivet-oss/commit/33bf5760ec3af6626b92f017ab575121d459b8de))
* reduce idle CPU, network and re-render churn ([3d7681f](https://github.com/oleksandr/kanivet-oss/commit/3d7681fd56112038d043e3f81b0ef5fd94c6c1ed))
* **search:** load the persisted index once, into shards, within a budget ([bcbf17b](https://github.com/oleksandr/kanivet-oss/commit/bcbf17bcdd79ed514ed883ff295e739d16d93787))
* **websocket:** assemble batch envelopes without re-encoding raw events ([1301edb](https://github.com/oleksandr/kanivet-oss/commit/1301edb40165ed6c68b6195d803b78920f0121df))


### Documentation

* add project governance and adopt Apache-2.0 ([#4](https://github.com/oleksandr/kanivet-oss/issues/4)) ([2ec6cb8](https://github.com/oleksandr/kanivet-oss/commit/2ec6cb8c7e4476667e58814de3a9fb24a9b6270f))
* **readme:** center the new Kanivet logo above the title ([5763a7c](https://github.com/oleksandr/kanivet-oss/commit/5763a7c24ebb3908b9ef3a1382ac0275eb4cd9ad))
* **readme:** improve Kubernetes feature discovery and getting started ([f1d6a27](https://github.com/oleksandr/kanivet-oss/commit/f1d6a273b3cb910f3106d01cbbed60f39814d56f))


### Refactoring

* migrated Go code for latest Go 1.27 and replaced Sonic with standard library's v2 json package (brand new in the latest Go). ([fe94e1f](https://github.com/oleksandr/kanivet-oss/commit/fe94e1f24e8465f70c5e4377feb711d2d8d8b115))


### CI

* validate release eligibility and test app before publishing ([#26](https://github.com/oleksandr/kanivet-oss/issues/26)) ([a0657a3](https://github.com/oleksandr/kanivet-oss/commit/a0657a3a8ab64e28d863f4eeec3e5305f61cd92b))


### Maintenance

* added optional devbox support to have easily reproducible local dev env ([b08747d](https://github.com/oleksandr/kanivet-oss/commit/b08747d1ad137816e4c4edc0c56c23075e017724))
* create clean Kanivet source export ([179a87c](https://github.com/oleksandr/kanivet-oss/commit/179a87cb1c92add10599788c6a2f7d3384c1ae6e))
* ignore per-platform backend binaries ([d6b014d](https://github.com/oleksandr/kanivet-oss/commit/d6b014d148d99d8c1d235da59b45dcb9554d1c17))
* initial NATS implementation ([128aabd](https://github.com/oleksandr/kanivet-oss/commit/128aabd9af4b4b27909f5dd393f6f98ae0aa7341))
* initial NATS implementation ([c4c57b7](https://github.com/oleksandr/kanivet-oss/commit/c4c57b7a22a63014016a7008e3ae8a3b56b8f85b))
* **main:** release 0.1.1 ([#3](https://github.com/oleksandr/kanivet-oss/issues/3)) ([60302ac](https://github.com/oleksandr/kanivet-oss/commit/60302acf6cd769b7e2b0d125d97f1b259b3b80c2))
* **main:** release 0.1.2 ([#5](https://github.com/oleksandr/kanivet-oss/issues/5)) ([46f6a22](https://github.com/oleksandr/kanivet-oss/commit/46f6a22ca7fa16ebb4d6b5d07a4c2f06be1db695))
* **main:** release 0.2.0 ([e007587](https://github.com/oleksandr/kanivet-oss/commit/e007587262c5385175bc98a720f513e0152466df))
* **main:** release 0.2.0 ([75022bd](https://github.com/oleksandr/kanivet-oss/commit/75022bd474d2e718ac21165e43143a04613a2acb))
* **main:** release 0.3.0 ([d7ce4c9](https://github.com/oleksandr/kanivet-oss/commit/d7ce4c9f5929b34b02076b79764c017afd10c530))
* **main:** release 0.3.0 ([8b232dd](https://github.com/oleksandr/kanivet-oss/commit/8b232dd36cda028ab31eb7631161be5b664735f3))
* **main:** release 0.4.0 ([#27](https://github.com/oleksandr/kanivet-oss/issues/27)) ([9b56a18](https://github.com/oleksandr/kanivet-oss/commit/9b56a18c0f78da437e3fceac8e5a3d8edc04bf8b))
* updated devbox plugin version ([b68fd11](https://github.com/oleksandr/kanivet-oss/commit/b68fd119b5b0a741a78fe86e08e460c2a4baad55))
* Upgrade backend to latest Go version (1.27), replace json library with recent builtin JSON v2, added optional devbox ([#6](https://github.com/oleksandr/kanivet-oss/issues/6)) ([e0164a2](https://github.com/oleksandr/kanivet-oss/commit/e0164a2f2132fe891efddcfa723340525db686a4))

## [0.4.0](https://github.com/kanivet-ai/kanivet-oss/compare/v0.3.0...v0.4.0) (2026-09-22)


### Features

* add GitHub star prompt and bug reporting with persistent opt-out ([9c08c20](https://github.com/kanivet-ai/kanivet-oss/commit/9c08c20a2a8dbfe9b60aabdd130dcaedd4af4b93))


### CI

* validate release eligibility and test app before publishing ([#26](https://github.com/kanivet-ai/kanivet-oss/issues/26)) ([a0657a3](https://github.com/kanivet-ai/kanivet-oss/commit/a0657a3a8ab64e28d863f4eeec3e5305f61cd92b))

## [0.3.0](https://github.com/kanivet-ai/kanivet-oss/compare/v0.2.0...v0.3.0) (2026-09-21)


### Features

* **cloud:** reach EKS contexts through AWS SSO with a chosen role ([7da0065](https://github.com/kanivet-ai/kanivet-oss/commit/7da0065c08324b27c1a596c2e607381a8e911ca1))
* **frontend:** adopt the macOS-native design system ([158069e](https://github.com/kanivet-ai/kanivet-oss/commit/158069e849bc7a5d5017523dde0873fd8c2ec6e9))
* **frontend:** layered Kanivet mark and regenerated app icons ([fe95db4](https://github.com/kanivet-ai/kanivet-oss/commit/fe95db42209874003bb7b4254a94ce72ee7c4097))
* **frontend:** purpose-built Kubernetes resource icon pack ([6f030ed](https://github.com/kanivet-ai/kanivet-oss/commit/6f030eddc38163f51e24463f69a8b6b66634b770))
* **frontend:** refresh resource icon pack and Kanivet mark ([3996cef](https://github.com/kanivet-ai/kanivet-oss/commit/3996ceff76aea5eb660b9c308211537cff6eef1b))
* **pods:** link a pod to its node and match node names in list search ([48949cb](https://github.com/kanivet-ai/kanivet-oss/commit/48949cbcf3e96532f89f519aaa094175dde3195c))


### Bug Fixes

* bounded startup index load, DB retention, vcluster health recovery ([e7d9ed8](https://github.com/kanivet-ai/kanivet-oss/commit/e7d9ed801b9d5ca6d40fddda249c8557a744b887))
* **cloud:** read sso_region from legacy AWS profiles ([032141f](https://github.com/kanivet-ai/kanivet-oss/commit/032141faaaa4f88d442ab80e6c91da44072be0a0))
* **cloud:** read sso_region from legacy AWS profiles ([dab641e](https://github.com/kanivet-ai/kanivet-oss/commit/dab641e5a1fe97fe4841594c160ba38c7057ef17))
* **cloud:** rework AWS SSO, GCP and Azure sign-in around the shared CLI caches ([b98dc6a](https://github.com/kanivet-ai/kanivet-oss/commit/b98dc6ae8106b8c418746c60e60f496ee4ca6ace))
* **cloud:** rework AWS SSO, GCP and Azure sign-in; make the title bar draggable ([c27d2cb](https://github.com/kanivet-ai/kanivet-oss/commit/c27d2cbea394677b256351ba055fd9e9f20e9c8b))
* **cloud:** stop counting down the hourly AWS access token ([983bc83](https://github.com/kanivet-ai/kanivet-oss/commit/983bc831c46731c0e10798c2fc84eb7110d71104))
* consistent kind and resource naming in search, single sidebar selection, detail pane styling ([f434c63](https://github.com/kanivet-ai/kanivet-oss/commit/f434c63a5017f19a3be0b902690559a9c0c7e8b5))
* **db:** purge search rows written before kind normalization ([0b4ebc9](https://github.com/kanivet-ai/kanivet-oss/commit/0b4ebc9829494362f857250ce18d09429e7e9411))
* **db:** version the schema, purge stale and orphaned rows, reclaim space ([1122727](https://github.com/kanivet-ai/kanivet-oss/commit/1122727db947f832d68a4710d8a60a54e77c2875))
* **details:** keep a detail load that finishes after a cluster tab switch ([e9b3b91](https://github.com/kanivet-ai/kanivet-oss/commit/e9b3b91c7eaff67d2e5664a03b57fedfd4ce7cf0))
* **edit:** never recreate a deleted resource when saving from the YAML editor ([78e0a8f](https://github.com/kanivet-ai/kanivet-oss/commit/78e0a8fda4ed7685f0fc9aee8e2febd9b724047d))
* **events:** scope resource events by kind, not just name and namespace ([2db4412](https://github.com/kanivet-ai/kanivet-oss/commit/2db441269d4bb6246043c8cab1792eadf40d35b6))
* **frontend:** give discovered kinds a fitting icon instead of a document ([e18ca88](https://github.com/kanivet-ai/kanivet-oss/commit/e18ca881be9d52991f53df4ff656da32ada3d372))
* **frontend:** open search results through the tree's resource node ([e883448](https://github.com/kanivet-ai/kanivet-oss/commit/e8834482f32b3fff48e1a82f50c355a4881cfd4b))
* **frontend:** preserve conflict protection when saving YAML ([4fe7ad8](https://github.com/kanivet-ai/kanivet-oss/commit/4fe7ad838e8ef4c1956c3d021124c20a83213ab0))
* **frontend:** preserve conflict protection when saving YAML ([af33937](https://github.com/kanivet-ai/kanivet-oss/commit/af33937c42c0ed7b09a9c25b088de42430934e05))
* **frontend:** report failed resource actions accurately ([54a3af2](https://github.com/kanivet-ai/kanivet-oss/commit/54a3af27baeaf7da23ed36b0d7fed1f1ef9a25ff))
* **frontend:** report failed resource actions accurately ([65ad270](https://github.com/kanivet-ai/kanivet-oss/commit/65ad2701231863dec6d22efe7e7e9c2399765254))
* **frontend:** resume log streams after reconnecting ([1ac561d](https://github.com/kanivet-ai/kanivet-oss/commit/1ac561df026dc8da6f81de8d51ef074c55924e18))
* **frontend:** resume log streams after reconnecting ([aa7bb88](https://github.com/kanivet-ai/kanivet-oss/commit/aa7bb88110dcf9aa4c8ac0d7edaec054c7f4ebea))
* **k8s:** count resources without downloading the whole list ([702ab2d](https://github.com/kanivet-ai/kanivet-oss/commit/702ab2d10cee69cba6e9a40496f7cadaa51e704b))
* **logs:** stop log streams from outliving their handler ([33b949a](https://github.com/kanivet-ai/kanivet-oss/commit/33b949ab16d787081b08e76a18dd4c3c3ab02cd6))
* **logs:** stop log streams from outliving their handler ([75acef1](https://github.com/kanivet-ai/kanivet-oss/commit/75acef1f220f604dd1fe6abb59006845c3b78fc7))
* **metrics:** show Mimir discovery failures instead of an empty list ([430b67e](https://github.com/kanivet-ai/kanivet-oss/commit/430b67ea23eacbea19161be402f72336023f8448))
* **panes:** give each cluster tab its own pane layout ([6df842d](https://github.com/kanivet-ai/kanivet-oss/commit/6df842dc602c483d199be7ca6fb5995b077dde52))
* **panes:** give each cluster tab its own pane layout ([0e60732](https://github.com/kanivet-ai/kanivet-oss/commit/0e6073250f23ed519f71c1d134808fb4e662ea41))
* **search:** index one document per object, with the discovery kind and resource name ([b5ff5f7](https://github.com/kanivet-ai/kanivet-oss/commit/b5ff5f7c3e5c2c77e3b95d874296ea51d4775406))
* **search:** search every selected cluster instead of only the first ([37d9381](https://github.com/kanivet-ai/kanivet-oss/commit/37d93815e0ffe052dfafa852fd760d1a232193ef))
* **sidebar,metrics:** keep the outline indented and the metric controls compact ([94d4ef9](https://github.com/kanivet-ai/kanivet-oss/commit/94d4ef99b384154f07d8f6dc74cda70b5d9815e0))
* **sidebar:** drop the kanivetIDE root node and highlight a single selected row ([e813c9a](https://github.com/kanivet-ai/kanivet-oss/commit/e813c9acfd02ce75b729abb44b2bfe7c6c4eee9f))
* **sidebar:** keep resource counts on screen while a category refreshes ([d8f7ce2](https://github.com/kanivet-ai/kanivet-oss/commit/d8f7ce2fe2ccd91f921c2e7404f7f2c5dac0ff2a))
* six behaviour fixes — terminal reconnect, kind-scoped events, action error toasts, no recreate on edit, multi-cluster search, Mimir discovery errors ([a59cc01](https://github.com/kanivet-ai/kanivet-oss/commit/a59cc0126af3e160a117613a2fe36bbf5f29f99c))
* **tabbar:** make the title bar draggable and zoomable again ([fedd992](https://github.com/kanivet-ai/kanivet-oss/commit/fedd992a21018e3ed852cac1a3e95d6f7ce98b68))
* **tabs:** start keyboard focus in the sidebar for a newly opened cluster ([8a24272](https://github.com/kanivet-ai/kanivet-oss/commit/8a2427211905fd7ee0f5701494f9e292ec8a1f6f))
* **terminal:** recreate the shell session after a WebSocket reconnect ([a2a03c3](https://github.com/kanivet-ai/kanivet-oss/commit/a2a03c3fba5627e4dab6131592953ea6e181220e))
* **ui:** surface failed operational actions as error toasts ([03d25f3](https://github.com/kanivet-ai/kanivet-oss/commit/03d25f3546c8e28986270c00a74ce692362951a8))
* **vcluster:** return the supervisor to healthy after a transient probe failure ([dd25b7f](https://github.com/kanivet-ai/kanivet-oss/commit/dd25b7f4484302c74c70ca910cc3b40da17bbc08))


### Performance

* **search:** load the persisted index once, into shards, within a budget ([bcbf17b](https://github.com/kanivet-ai/kanivet-oss/commit/bcbf17bcdd79ed514ed883ff295e739d16d93787))
* **websocket:** assemble batch envelopes without re-encoding raw events ([1301edb](https://github.com/kanivet-ai/kanivet-oss/commit/1301edb40165ed6c68b6195d803b78920f0121df))


### Documentation

* **readme:** center the new Kanivet logo above the title ([5763a7c](https://github.com/kanivet-ai/kanivet-oss/commit/5763a7c24ebb3908b9ef3a1382ac0275eb4cd9ad))
* **readme:** improve Kubernetes feature discovery and getting started ([f1d6a27](https://github.com/kanivet-ai/kanivet-oss/commit/f1d6a273b3cb910f3106d01cbbed60f39814d56f))


### Maintenance

* Upgrade backend to latest Go version (1.27), replace json library with recent builtin JSON v2, added optional devbox ([#6](https://github.com/kanivet-ai/kanivet-oss/issues/6)) ([e0164a2](https://github.com/kanivet-ai/kanivet-oss/commit/e0164a2f2132fe891efddcfa723340525db686a4))

## [0.2.0](https://github.com/kanivet-ai/kanivet-oss/compare/v0.1.2...v0.2.0) (2026-09-11)


### Features

* show CRD printer columns on custom resource lists ([9d3212c](https://github.com/kanivet-ai/kanivet-oss/commit/9d3212c8372fe148c4210a0d9c95bd2e7e410a36))
* show CRD printer columns on custom resource lists ([03b572e](https://github.com/kanivet-ai/kanivet-oss/commit/03b572e8e16da4869b5ff4469e696b478348962c))

## [0.1.2](https://github.com/kanivet-ai/kanivet-oss/compare/v0.1.1...v0.1.2) (2026-09-10)


### Documentation

* add project governance and adopt Apache-2.0 ([#4](https://github.com/kanivet-ai/kanivet-oss/issues/4)) ([2ec6cb8](https://github.com/kanivet-ai/kanivet-oss/commit/2ec6cb8c7e4476667e58814de3a9fb24a9b6270f))

## [0.1.1](https://github.com/kanivet-ai/kanivet-oss/compare/v0.1.0...v0.1.1) (2026-09-08)


### Bug Fixes

* enable automated releases and resolve platform failures ([#2](https://github.com/kanivet-ai/kanivet-oss/issues/2)) ([4bcea66](https://github.com/kanivet-ai/kanivet-oss/commit/4bcea669a47a2a6209379d2833f120601d855a30))


### Performance

* port upstream PR [#121](https://github.com/kanivet-ai/kanivet-oss/issues/121) efficiency improvements ([33bf576](https://github.com/kanivet-ai/kanivet-oss/commit/33bf5760ec3af6626b92f017ab575121d459b8de))
* reduce idle CPU, network and re-render churn ([3d7681f](https://github.com/kanivet-ai/kanivet-oss/commit/3d7681fd56112038d043e3f81b0ef5fd94c6c1ed))


### Maintenance

* create clean Kanivet source export ([179a87c](https://github.com/kanivet-ai/kanivet-oss/commit/179a87cb1c92add10599788c6a2f7d3384c1ae6e))
