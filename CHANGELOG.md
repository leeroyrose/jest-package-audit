## [1.0.3](https://github.com/xeroxinteractive/jest-package-audit/compare/v1.0.2...v1.0.3) (2019-05-24)


### Bug Fixes

* allow filtering + better exit code handling ([85406d7](https://github.com/xeroxinteractive/jest-package-audit/commit/85406d7))

## [1.0.2](https://github.com/xeroxinteractive/jest-package-audit/compare/v1.0.1...v1.0.2) (2019-05-23)


### Code Refactoring

* single file exports matcher ([5ac17da](https://github.com/xeroxinteractive/jest-package-audit/commit/5ac17da))


### BREAKING CHANGES

* toPassPackageAudit is no longer automatically extended onto jest, using setupFilesAfterEnv will no longer work.

## [1.0.1](https://github.com/xeroxinteractive/jest-package-audit/compare/v1.0.0...v1.0.1) (2019-05-22)


### Bug Fixes

* use cross-spawn for windows compat ([0cf82c3](https://github.com/xeroxinteractive/jest-package-audit/commit/0cf82c3))
* windows cross-spawn mocking ([219c576](https://github.com/xeroxinteractive/jest-package-audit/commit/219c576))

# 1.0.0 (2019-05-21)


### Bug Fixes

* exit code 8 ([3817c9d](https://github.com/xeroxinteractive/jest-package-audit/commit/3817c9d))
* **audit:** more timeout I guess ([4d4ec6e](https://github.com/xeroxinteractive/jest-package-audit/commit/4d4ec6e))
* **matcher:** output error in message ([464a5aa](https://github.com/xeroxinteractive/jest-package-audit/commit/464a5aa))
* **package:** v0.0.0 ([0fa7df3](https://github.com/xeroxinteractive/jest-package-audit/commit/0fa7df3))


### Features

* initial implementation ([7de24fc](https://github.com/xeroxinteractive/jest-package-audit/commit/7de24fc))
* log error if jest can’t be extended ([9e2503d](https://github.com/xeroxinteractive/jest-package-audit/commit/9e2503d))
