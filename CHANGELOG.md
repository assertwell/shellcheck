# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Version 1.0.2] — 2022-02-09

### Fixed

* Look for `COMPOSER_RUNTIME_BIN_DIR`, not `COMPOSER_BIN_DIR` when altering the user's `$PATH` to prevent recursion in Composer scripts ([#5]).

## [Version 1.0.1] — 2022-02-08

### Fixed

* Prevent recursion when calling the bundled ShellCheck script via Composer script ([#3]).

## [Version 1.0.0] — 2022-02-08

Initial release.

[Unreleased]: https://github.com/assertwell/shellcheck/compare/main...develop
[Version 1.0.0]: https://github.com/assertwell/shellcheck/releases/tag/v1.0.0
[Version 1.0.1]: https://github.com/assertwell/shellcheck/releases/tag/v1.0.1
[Version 1.0.2]: https://github.com/assertwell/shellcheck/releases/tag/v1.0.2
[#3]: https://github.com/assertwell/shellcheck/pull/3
[#5]: https://github.com/assertwell/shellcheck/pull/5
