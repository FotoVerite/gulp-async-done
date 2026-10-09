# Changelog

## 1.0.0 (2026-10-09)


### ⚠ BREAKING CHANGES

* Allow end-of-stream to handle the stream error states
* Normalize repository, dropping node <10.13 support ([#54](https://github.com/FotoVerite/gulp-async-done/issues/54))

### Bug Fixes

* Actually publish types ([51c5ec5](https://github.com/FotoVerite/gulp-async-done/commit/51c5ec5686e8ee2d685283a694cfeba7e96269bd))
* Allow end-of-stream to handle the stream error states ([7b37da4](https://github.com/FotoVerite/gulp-async-done/commit/7b37da45e8344e78a5d40a8c277cc57d796c1257))
* Avoid swallowing thrown errors in callback argument (closes [#43](https://github.com/FotoVerite/gulp-async-done/issues/43)) ([204de69](https://github.com/FotoVerite/gulp-async-done/commit/204de69e0e62d4d8b1f6b61c54affe0d52859590))
* Callback with an error even if Promise is rejected with nothing (closes [#42](https://github.com/FotoVerite/gulp-async-done/issues/42)) ([77d00f9](https://github.com/FotoVerite/gulp-async-done/commit/77d00f9fe66706a390cb58c879b308c78b7cc9c2))
* Change & tests for failing child processes (fixes [#24](https://github.com/FotoVerite/gulp-async-done/issues/24)) ([0224d42](https://github.com/FotoVerite/gulp-async-done/commit/0224d42dd050a009a52fec01f3cfe9ffadea7c08))
* Ensure stream is flowing using stream-exhaust module (fixes [#11](https://github.com/FotoVerite/gulp-async-done/issues/11)) ([b6b297f](https://github.com/FotoVerite/gulp-async-done/commit/b6b297fa0dca9482318db8ff6315cf7845cbe32d))
* Ensure the Observable failure test works ([#59](https://github.com/FotoVerite/gulp-async-done/issues/59)) ([dfa4f0b](https://github.com/FotoVerite/gulp-async-done/commit/dfa4f0b30b1c4666dbf6c930aac62434cf6a0c1c))
* Use .once instead of .on to fix memory leak (fixes [#1](https://github.com/FotoVerite/gulp-async-done/issues/1)) ([aa0ffca](https://github.com/FotoVerite/gulp-async-done/commit/aa0ffca835b97b67ed78cf79931c4fb334460dcb))
* Wrap callback call in try/catch and rethrow async (fixes [#45](https://github.com/FotoVerite/gulp-async-done/issues/45)) ([#46](https://github.com/FotoVerite/gulp-async-done/issues/46)) ([11fffe0](https://github.com/FotoVerite/gulp-async-done/commit/11fffe0d06202c8e7b5af6ce1b8972282e5111f6))


### Miscellaneous Chores

* Normalize repository, dropping node &lt;10.13 support ([#54](https://github.com/FotoVerite/gulp-async-done/issues/54)) ([66f987f](https://github.com/FotoVerite/gulp-async-done/commit/66f987f36d2cbd07d5b96f487ea327caa44acb10))

## [2.0.0](https://www.github.com/gulpjs/async-done/compare/v1.3.2...v2.0.0) (2022-06-25)


### ⚠ BREAKING CHANGES

* Allow end-of-stream to handle the stream error states
* Normalize repository, dropping node <10.13 support (#54)

### Bug Fixes

* Allow end-of-stream to handle the stream error states ([7b37da4](https://www.github.com/gulpjs/async-done/commit/7b37da45e8344e78a5d40a8c277cc57d796c1257))
* Ensure the Observable failure test works ([#59](https://www.github.com/gulpjs/async-done/issues/59)) ([dfa4f0b](https://www.github.com/gulpjs/async-done/commit/dfa4f0b30b1c4666dbf6c930aac62434cf6a0c1c))


### Miscellaneous Chores

* Normalize repository, dropping node <10.13 support ([#54](https://www.github.com/gulpjs/async-done/issues/54)) ([66f987f](https://www.github.com/gulpjs/async-done/commit/66f987f36d2cbd07d5b96f487ea327caa44acb10))
