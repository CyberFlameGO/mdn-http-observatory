# Changelog

## [1.2.0](https://github.com/mdn/mdn-http-observatory/compare/v1.1.0...v1.2.0) (2024-07-26)


### Features

* **db:** cleanup ([ee1942e](https://github.com/mdn/mdn-http-observatory/commit/ee1942e99938ccfc8e0e1f9545d43ae7a2d80940))
* **db:** remove auto-migrate from server startup ([#52](https://github.com/mdn/mdn-http-observatory/issues/52)) ([d43d626](https://github.com/mdn/mdn-http-observatory/commit/d43d6262c93217f9a87fa23f7eea18090e47ea9d))


### Bug Fixes

* **hsts:** resolve path for hsts-preload.json file ([0ea5178](https://github.com/mdn/mdn-http-observatory/commit/0ea51787d06094eeab5ba4a49f12fe4f6830cff9))
* **hsts:** rework file path resolution ([#50](https://github.com/mdn/mdn-http-observatory/issues/50)) ([1b2e9ed](https://github.com/mdn/mdn-http-observatory/commit/1b2e9edfa107192327d632e41c638d4bff3c2354))

## [1.1.0](https://github.com/mdn/mdn-http-observatory/compare/v1.0.0...v1.1.0) (2024-07-22)


### Features

* **api:** add Sentry ([#24](https://github.com/mdn/mdn-http-observatory/issues/24)) ([f20f546](https://github.com/mdn/mdn-http-observatory/commit/f20f546c2485e848bf3839b3d64d32c542c050cc))
* **workflows:** setup release-please ([#35](https://github.com/mdn/mdn-http-observatory/issues/35)) ([9c945ca](https://github.com/mdn/mdn-http-observatory/commit/9c945ca7e39fd8dcda1fed27a2d855bec81ae4df))


### Bug Fixes

* **api:** properly refuse hostnames in special TLDs (MP-1287) ([ea315ba](https://github.com/mdn/mdn-http-observatory/commit/ea315baf7415004417d5d9ffae91aa7bea4cd9e0))
* **api:** typos in policy copy ([e1d710d](https://github.com/mdn/mdn-http-observatory/commit/e1d710d63e4a227cb972f5646e68fc61504d987c))
* **auto-merge:** approve before comment ([#22](https://github.com/mdn/mdn-http-observatory/issues/22)) ([c2519a1](https://github.com/mdn/mdn-http-observatory/commit/c2519a1321b686dc8d512f7974fdc869939afd24))
* **auto-merge:** remove accidental quote ([#23](https://github.com/mdn/mdn-http-observatory/issues/23)) ([561b2dd](https://github.com/mdn/mdn-http-observatory/commit/561b2dd4c8692094dbcf406df57b5d38b56292d2))
* **csp:** make sure a single `frame-ancestors` in meta equiv tags gets ignored correctly ([5080718](https://github.com/mdn/mdn-http-observatory/commit/5080718fcbb89837e71085da8e11c338a98bc203))
* **xframeoptions:** added a test that ensures meta equiv tags with `x-frame-options` are ignored ([39cf38c](https://github.com/mdn/mdn-http-observatory/commit/39cf38cf1c2e6d382d4bac5714fb2b9573e87848))


### Miscellaneous

* **auto-merge:** replace workflow ([#11](https://github.com/mdn/mdn-http-observatory/issues/11)) ([3ad31e3](https://github.com/mdn/mdn-http-observatory/commit/3ad31e3572c0c2cb22e43b7175960b91c1fbddf6))
* **github:** add CODEOWNERS ([#10](https://github.com/mdn/mdn-http-observatory/issues/10)) ([8f64852](https://github.com/mdn/mdn-http-observatory/commit/8f64852023a3e2d7a8b7e8892aef659291eaedae))
* **github:** add Dependabot config ([#12](https://github.com/mdn/mdn-http-observatory/issues/12)) ([5b9384a](https://github.com/mdn/mdn-http-observatory/commit/5b9384a704e1ff56016ddf63a196eddbc3d4f3de))
* **node:** use Node.js v20 via .nvmrc file ([#9](https://github.com/mdn/mdn-http-observatory/issues/9)) ([a9992a8](https://github.com/mdn/mdn-http-observatory/commit/a9992a82368068fca635859885816589738e8fb6))
