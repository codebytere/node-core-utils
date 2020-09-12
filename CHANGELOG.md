# Changelog

## [1.17.0](https://www.github.com/codebytere/node-core-utils/compare/v1.16.1...v1.17.0) (2020-09-12)


### Features

* add ncu-ci cigtm <jobid> ([#454](https://www.github.com/codebytere/node-core-utils/issues/454)) ([c1dfbd0](https://www.github.com/codebytere/node-core-utils/commit/c1dfbd0f57feb62c813205e2ff748d7d7db7f048))
* allow citgm job comparison ([#455](https://www.github.com/codebytere/node-core-utils/issues/455)) ([336dc7f](https://www.github.com/codebytere/node-core-utils/commit/336dc7fe399ca082da0f02d6dcec769f7d1cb069))
* allow to fixup everything into first commit with fixupAll ([4ad4a58](https://www.github.com/codebytere/node-core-utils/commit/4ad4a58a9471d3fd4e27e3b19bae979d91916cef))
* check Actions and handle doc-only changes ([855f1d4](https://www.github.com/codebytere/node-core-utils/commit/855f1d46bd70aa54037111138a0d4b7a59f3001b))
* check CI failures before land ([#422](https://www.github.com/codebytere/node-core-utils/issues/422)) ([75abd3a](https://www.github.com/codebytere/node-core-utils/commit/75abd3a22eca92a48ceb28532c7311de5e8ebe67))
* enable parsing citgm-nobuild jobs ([#458](https://www.github.com/codebytere/node-core-utils/issues/458)) ([d4b189b](https://www.github.com/codebytere/node-core-utils/commit/d4b189b167951dd8ca50849b6f4548e8b63cf41a))
* handle unknown commands ([#387](https://www.github.com/codebytere/node-core-utils/issues/387)) ([4ea4dfa](https://www.github.com/codebytere/node-core-utils/commit/4ea4dfad069d7cb6eccdea28f514a2b67e153508))
* implement autorebase for PRs with multiple commits ([17ea885](https://www.github.com/codebytere/node-core-utils/commit/17ea88569ccae245017f9851f5a6e64b1ca6566c))
* make lint check opt-in ([b567c1e](https://www.github.com/codebytere/node-core-utils/commit/b567c1e57acec50abc12c49f51c93837a7ccd5e4))
* **git-node:** add git-node status ([ebc8fb2](https://www.github.com/codebytere/node-core-utils/commit/ebc8fb2652c9eaef5af556b6be0db089e8f29320))
* handle unmarked DEP0XXX tags during landing and release ([#420](https://www.github.com/codebytere/node-core-utils/issues/420)) ([08bc3fc](https://www.github.com/codebytere/node-core-utils/commit/08bc3fc4ea74c879f4791f83a56d73a681351ff2))
* set error code in some failure cases ([#443](https://www.github.com/codebytere/node-core-utils/issues/443)) ([56d4931](https://www.github.com/codebytere/node-core-utils/commit/56d49317787cde0807fb1549c1f190b498e9aa74))
* support system proxy ([#408](https://www.github.com/codebytere/node-core-utils/issues/408)) ([c6697de](https://www.github.com/codebytere/node-core-utils/commit/c6697de07e67b4c3cffbea392003020c772fed4d))


### Bug Fixes

* add missing comma in release commit title ([#403](https://www.github.com/codebytere/node-core-utils/issues/403)) ([78f0b96](https://www.github.com/codebytere/node-core-utils/commit/78f0b9606b5ff715810e7f5ebc96de20f2d4ddd1)), closes [/github.com/nodejs/node/blob/cf888ac105ffd02bbceef02c16d0df548676abd1/doc/guides/releases.md#5](https://www.github.com/codebytere//github.com/nodejs/node/blob/cf888ac105ffd02bbceef02c16d0df548676abd1/doc/guides/releases.md/issues/5)
* allow opt-out of Fixes/Refs metadata ([#474](https://www.github.com/codebytere/node-core-utils/issues/474)) ([df5c572](https://www.github.com/codebytere/node-core-utils/commit/df5c572cded5a1b96da0894d3e3b15019116c594))
* also exclude backport-open label from branch diff ([#440](https://www.github.com/codebytere/node-core-utils/issues/440)) ([af4c72c](https://www.github.com/codebytere/node-core-utils/commit/af4c72c4ed2d9f47e19f1902925973bea8ae10ab))
* check missing config in Session ctor ([#426](https://www.github.com/codebytere/node-core-utils/issues/426)) ([7dc544d](https://www.github.com/codebytere/node-core-utils/commit/7dc544d106098576ddd66c85c733069cfdf3a787))
* correct for new execGitNode syntax ([#433](https://www.github.com/codebytere/node-core-utils/issues/433)) ([6d82a73](https://www.github.com/codebytere/node-core-utils/commit/6d82a730dfc95d8dde2176f002fa89157503b93c))
* default date for release ([#419](https://www.github.com/codebytere/node-core-utils/issues/419)) ([ecc7f0c](https://www.github.com/codebytere/node-core-utils/commit/ecc7f0c233a630da0937d8009afc6c39aa46c29d))
* enforce default for non-confirmation prompts ([#415](https://www.github.com/codebytere/node-core-utils/issues/415)) ([3e0f03d](https://www.github.com/codebytere/node-core-utils/commit/3e0f03d15b377a43f91ed59776477b0aa1a3d8dd))
* ensure node-test-commit job id in daily-master ([#460](https://www.github.com/codebytere/node-core-utils/issues/460)) ([de35935](https://www.github.com/codebytere/node-core-utils/commit/de3593557e19c036b2fdec297dbfe11b580e5399))
* handle citgm failures better ([#497](https://www.github.com/codebytere/node-core-utils/issues/497)) ([a429893](https://www.github.com/codebytere/node-core-utils/commit/a4298938f84382588db3101dcf611d89f6f0f1e9))
* landing when no Jenkins CI has been run for PR ([#451](https://www.github.com/codebytere/node-core-utils/issues/451)) ([d63301e](https://www.github.com/codebytere/node-core-utils/commit/d63301e9ea18543ab1d5d4be7ead09ddae3ce74c))
* lint during the landing process ([#435](https://www.github.com/codebytere/node-core-utils/issues/435)) ([de6d1e2](https://www.github.com/codebytere/node-core-utils/commit/de6d1e22fb11b344ba581b52627c36a3df910294))
* LTS release commit should contain codename ([#401](https://www.github.com/codebytere/node-core-utils/issues/401)) ([37f4cc6](https://www.github.com/codebytere/node-core-utils/commit/37f4cc6a814f4667333fc59563527925d7b03b16))
* prevent duplicate and self-refs ([#478](https://www.github.com/codebytere/node-core-utils/issues/478)) ([95300fd](https://www.github.com/codebytere/node-core-utils/commit/95300fdcd98c1a1f5bd5d1f5dcbc8f96922096f8))
* return value for validateLint ([#482](https://www.github.com/codebytere/node-core-utils/issues/482)) ([e379e9f](https://www.github.com/codebytere/node-core-utils/commit/e379e9f94688e38b7da5367eaadcfb7af74609a0))
* **v8:** support non-relative paths in V8 DEPS ([#471](https://www.github.com/codebytere/node-core-utils/issues/471)) ([746e5e5](https://www.github.com/codebytere/node-core-utils/commit/746e5e593a7af2244877cdee5282b9c3a507d2d5))
* print full command in case of failure ([#456](https://www.github.com/codebytere/node-core-utils/issues/456)) ([5fe936f](https://www.github.com/codebytere/node-core-utils/commit/5fe936ff7239528c67c1ef564c563dca92eec05d))
* properly handle failure to start CI ([48c306b](https://www.github.com/codebytere/node-core-utils/commit/48c306b4d84aacb799b75eaae1fe304eed0639fd))
* repo/path mismatch in v8 update ([#465](https://www.github.com/codebytere/node-core-utils/issues/465)) ([57b7df8](https://www.github.com/codebytere/node-core-utils/commit/57b7df8016a3d1495be4f67fc3cc34db21a2b3a6))
* spacing in warnForWrongBranch() ([#448](https://www.github.com/codebytere/node-core-utils/issues/448)) ([d8c024d](https://www.github.com/codebytere/node-core-utils/commit/d8c024d3fdbd0278cc56f746e527cb43fc8eaa03))
* use 12 characters for commit SHAs ([#372](https://www.github.com/codebytere/node-core-utils/issues/372)) ([a9c0676](https://www.github.com/codebytere/node-core-utils/commit/a9c0676d0f64df5c8e86d7287f69381dc64049f2))
* use git apply not system apply in v8 backport ([#432](https://www.github.com/codebytere/node-core-utils/issues/432)) ([65fb311](https://www.github.com/codebytere/node-core-utils/commit/65fb311a0fac380f4c74012d703a75ebe22f6508))
* use plaintext formatting in release commit ([#417](https://www.github.com/codebytere/node-core-utils/issues/417)) ([8e6ac47](https://www.github.com/codebytere/node-core-utils/commit/8e6ac47e0256f11bdc21262b644285299b8ff18a))
* validate ncu-ci args ([#411](https://www.github.com/codebytere/node-core-utils/issues/411)) ([dfe7adf](https://www.github.com/codebytere/node-core-utils/commit/dfe7adf18e4bbeadb479482c5f36fe344a78292b))
* warn on whitespace during landing ([#438](https://www.github.com/codebytere/node-core-utils/issues/438)) ([ae3aeb9](https://www.github.com/codebytere/node-core-utils/commit/ae3aeb93f8368779b8b3a95cbd82841f7feae2ab))
* write file to the current folder ([#434](https://www.github.com/codebytere/node-core-utils/issues/434)) ([5974797](https://www.github.com/codebytere/node-core-utils/commit/59747973f681cca4dc4eb60d617638b0c194c137))

## [1.24.0](https://www.github.com/nodejs/node-core-utils/compare/v1.23.0...v1.24.0) (2020-08-21)


### Features

* check Actions and handle doc-only changes ([855f1d4](https://www.github.com/nodejs/node-core-utils/commit/855f1d46bd70aa54037111138a0d4b7a59f3001b))
* implement autorebase for PRs with multiple commits ([17ea885](https://www.github.com/nodejs/node-core-utils/commit/17ea88569ccae245017f9851f5a6e64b1ca6566c))
* make lint check opt-in ([b567c1e](https://www.github.com/nodejs/node-core-utils/commit/b567c1e57acec50abc12c49f51c93837a7ccd5e4))
* **git-node:** add git-node status ([ebc8fb2](https://www.github.com/nodejs/node-core-utils/commit/ebc8fb2652c9eaef5af556b6be0db089e8f29320))


### Bug Fixes

* allow opt-out of Fixes/Refs metadata ([#474](https://www.github.com/nodejs/node-core-utils/issues/474)) ([df5c572](https://www.github.com/nodejs/node-core-utils/commit/df5c572cded5a1b96da0894d3e3b15019116c594))
* lint during the landing process ([#435](https://www.github.com/nodejs/node-core-utils/issues/435)) ([de6d1e2](https://www.github.com/nodejs/node-core-utils/commit/de6d1e22fb11b344ba581b52627c36a3df910294))
* prevent duplicate and self-refs ([#478](https://www.github.com/nodejs/node-core-utils/issues/478)) ([95300fd](https://www.github.com/nodejs/node-core-utils/commit/95300fdcd98c1a1f5bd5d1f5dcbc8f96922096f8))
* properly handle failure to start CI ([48c306b](https://www.github.com/nodejs/node-core-utils/commit/48c306b4d84aacb799b75eaae1fe304eed0639fd))
* return value for validateLint ([#482](https://www.github.com/nodejs/node-core-utils/issues/482)) ([e379e9f](https://www.github.com/nodejs/node-core-utils/commit/e379e9f94688e38b7da5367eaadcfb7af74609a0))
* **v8:** support non-relative paths in V8 DEPS ([#471](https://www.github.com/nodejs/node-core-utils/issues/471)) ([746e5e5](https://www.github.com/nodejs/node-core-utils/commit/746e5e593a7af2244877cdee5282b9c3a507d2d5))
* repo/path mismatch in v8 update ([#465](https://www.github.com/nodejs/node-core-utils/issues/465)) ([57b7df8](https://www.github.com/nodejs/node-core-utils/commit/57b7df8016a3d1495be4f67fc3cc34db21a2b3a6))
