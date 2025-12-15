# Changelog

## [0.1.3](https://github.com/PenguinDan/kotlin-sdk/compare/v0.1.2...v0.1.3) (2025-12-15)


### 🐛 Bug Fixes

* add packageGroup to nexusPublishing for Sonatype staging profile discovery ([e1f75cd](https://github.com/PenguinDan/kotlin-sdk/commit/e1f75cdd3dbedba58f98efdfca8d6883d2aa820d))
* simplify group/version assignment to match upstream ([1ff0aa7](https://github.com/PenguinDan/kotlin-sdk/commit/1ff0aa7c5fc17770496c7f004a5257f7445c46db))

## [0.1.2](https://github.com/PenguinDan/kotlin-sdk/compare/v0.1.1...v0.1.2) (2025-12-15)


### 🐛 Bug Fixes

* simplify GPG config - dismiss overly cautious suggestions ([177fa54](https://github.com/PenguinDan/kotlin-sdk/commit/177fa540bd9d58907fe2fbf5da0785fa5d80ffb0))

## [0.1.1](https://github.com/PenguinDan/kotlin-sdk/compare/v0.1.0...v0.1.1) (2025-12-15)


### ✨ New Features

* reset version for fresh 0.1.0 release ([952176d](https://github.com/PenguinDan/kotlin-sdk/commit/952176dbbe321e1e6192af1f221bb879bfec4dc9))


### 🧹 Chore

* create v0.1.0 tag ([80b5955](https://github.com/PenguinDan/kotlin-sdk/commit/80b5955c0ef3fcdf51cc181f8546bfb4ad66eb13))
* set version to 0.1.0 for initial release ([6ea527a](https://github.com/PenguinDan/kotlin-sdk/commit/6ea527a1d5fc095ad4862175bb21d6dc36b604c2))

## [0.1.0](https://github.com/PenguinDan/kotlin-sdk/releases/tag/v0.1.0) (2025-12-15)

### ✨ Initial Release

This is the first release of the forked OpenFeature Kotlin SDK, published under `io.github.penguindan:kotlin-sdk`.

#### Features

- Full Kotlin Multiplatform support (Android, JVM, iOS, JS, Linux)
- OpenFeature specification v0.8.0 compliance
- Provider abstraction for feature flag management
- Evaluation context for targeting
- Hooks for flag evaluation lifecycle
- Tracking API for experimentation
- Event-driven provider state management

#### Acknowledgments

This project is a fork of the [OpenFeature Kotlin SDK](https://github.com/open-feature/kotlin-sdk), originally developed by the OpenFeature community.
