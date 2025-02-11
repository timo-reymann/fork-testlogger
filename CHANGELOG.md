# Changelog

Starting with v4.0.x, all the testloggers use a unified changelog for
simplicity. For v3.x changelogs, refer to the end of this document.

## [6.0.0](https://github.com/timo-reymann/fork-testlogger/compare/v5.0.0...v6.0.0) (2025-02-11)


### ⚠ BREAKING CHANGES

* [junit] #153 Add properties support on test case level for test logger ([#154](https://github.com/timo-reymann/fork-testlogger/issues/154))
* [junit] add testcase system-out and system-err along with attachment support. ([#136](https://github.com/timo-reymann/fork-testlogger/issues/136))

### Features

* [junit] [#153](https://github.com/timo-reymann/fork-testlogger/issues/153) Add properties support on test case level for test logger ([#154](https://github.com/timo-reymann/fork-testlogger/issues/154)) ([f555322](https://github.com/timo-reymann/fork-testlogger/commit/f555322cdb8c593a633b9707c289957b80110fab))
* [junit] add testcase system-out and system-err along with attachment support. ([#136](https://github.com/timo-reymann/fork-testlogger/issues/136)) ([dff18d6](https://github.com/timo-reymann/fork-testlogger/commit/dff18d6379009656fc622fe15e9a5f2708e72f33))
* [JUnit] added StoreConsoleOutput option ([#115](https://github.com/timo-reymann/fork-testlogger/issues/115)) ([63fc58f](https://github.com/timo-reymann/fork-testlogger/commit/63fc58fecb2f48d60335b85b190e30fb7450e443))
* add nunit test adapter to transform tests marked with Explicit attribute to Skipped instead of Inconclusive outcome. ([#26](https://github.com/timo-reymann/fork-testlogger/issues/26)) ([ebe101b](https://github.com/timo-reymann/fork-testlogger/commit/ebe101baf902ce3ab74ccf08ca553701705b332d))
* add skeleton workflows for the core logger. ([4623234](https://github.com/timo-reymann/fork-testlogger/commit/462323430268d16eac836a399fa933d11177d160))
* add string extensions for sanitizing xml chars. ([#15](https://github.com/timo-reymann/fork-testlogger/issues/15)) ([a6a7a5e](https://github.com/timo-reymann/fork-testlogger/commit/a6a7a5e472b41edd8bcaf5a495bbe92a095c7739)), closes [#1](https://github.com/timo-reymann/fork-testlogger/issues/1)
* Add support for test and run level attachments. ([#40](https://github.com/timo-reymann/fork-testlogger/issues/40)) ([0a35c55](https://github.com/timo-reymann/fork-testlogger/commit/0a35c55a4249567213423c82903c1a8590f9807a))
* add testproperty to TestResultInfo for Nunit scenarios. ([#38](https://github.com/timo-reymann/fork-testlogger/issues/38)) ([019c976](https://github.com/timo-reymann/fork-testlogger/commit/019c976c2bab45ae430a51469bb6c8081c92f877))
* embed symbols and source code for test logger for debuggability. ([#23](https://github.com/timo-reymann/fork-testlogger/issues/23)) ([65d52da](https://github.com/timo-reymann/fork-testlogger/commit/65d52da61f9a8ea61af0182da1e0efc7f6628911))
* enable end to end log workflow. ([#10](https://github.com/timo-reymann/fork-testlogger/issues/10)) ([c2cdd59](https://github.com/timo-reymann/fork-testlogger/commit/c2cdd595b384358b8662663804256d8f24f8253d))
* handle illegal xml characters in test data ([#37](https://github.com/timo-reymann/fork-testlogger/issues/37)) ([ea8357f](https://github.com/timo-reymann/fork-testlogger/commit/ea8357fa40964eb7aa1f91f69e2cf3355dd62ce1))
* implement filesystem abstraction, add platform tests and fix integration test. ([03951a6](https://github.com/timo-reymann/fork-testlogger/commit/03951a653d2f0f68840e25d6869d782a97cc43e5))
* mstest adapter to include result displayname ([86d5ab9](https://github.com/timo-reymann/fork-testlogger/commit/86d5ab98a8b61022ba010922cc66423513b828e8))
* overhaul parser & Test all supported test frameworks ([#30](https://github.com/timo-reymann/fork-testlogger/issues/30)) ([267b36c](https://github.com/timo-reymann/fork-testlogger/commit/267b36c1b956a720d5962c47f67029e9486bb89a))
* port junit logger. ([#70](https://github.com/timo-reymann/fork-testlogger/issues/70)) ([1f57003](https://github.com/timo-reymann/fork-testlogger/commit/1f570030082d7994429fb5317636bc8df1112d5d))
* port xunit and nunit loggers into testlogger repo. ([#68](https://github.com/timo-reymann/fork-testlogger/issues/68)) ([677c53f](https://github.com/timo-reymann/fork-testlogger/commit/677c53ffc19e071477fab79c585e4e752ba2546b))
* transform results to include skip reason for xunit. ([#14](https://github.com/timo-reymann/fork-testlogger/issues/14)) ([8068672](https://github.com/timo-reymann/fork-testlogger/commit/80686725d477bb1326e0a61857fc522eb9f7587a))
* Update ITestResultSeralizer to accept messages. ([#19](https://github.com/timo-reymann/fork-testlogger/issues/19)) ([365fc23](https://github.com/timo-reymann/fork-testlogger/commit/365fc23a7091196c4c6ad61fc1f5cf0094de3100))
* update junit xsd to allow test case level outputs. ([#134](https://github.com/timo-reymann/fork-testlogger/issues/134)) ([1a37110](https://github.com/timo-reymann/fork-testlogger/commit/1a37110a8be5e4e20896826b2ed5db28b5dd4a06))


### Bug Fixes

* add business logic for json logger. ([#13](https://github.com/timo-reymann/fork-testlogger/issues/13)) ([0b39fb0](https://github.com/timo-reymann/fork-testlogger/commit/0b39fb0ed4b35a6d6e8bd45902df35ceba076c56))
* Add DisplayName property in TestResultInfo ([#39](https://github.com/timo-reymann/fork-testlogger/issues/39)) ([11c79e7](https://github.com/timo-reymann/fork-testlogger/commit/11c79e775bcc5eb0e8fdb01864b1ad1068c70405))
* appveyor build with correct project references. Add codecov support in travis. ([9e59ebf](https://github.com/timo-reymann/fork-testlogger/commit/9e59ebf0afa0f4b6b3636a7fea6d294b39bb21dc))
* build and run tests when repo path contains whitespace. Fix test flakiness. ([#42](https://github.com/timo-reymann/fork-testlogger/issues/42)) ([6eb1221](https://github.com/timo-reymann/fork-testlogger/commit/6eb122170ce7bd56808caea1371ef420091e98bc))
* build package test with restore config ([#72](https://github.com/timo-reymann/fork-testlogger/issues/72)) ([443ea96](https://github.com/timo-reymann/fork-testlogger/commit/443ea96c520b173a0fd35de33236ad60593d1721))
* exclude assembly from code coverage. ([#44](https://github.com/timo-reymann/fork-testlogger/issues/44)) ([bf2d130](https://github.com/timo-reymann/fork-testlogger/commit/bf2d130d226dbea7aea503f0098e31c39e27fb59))
* Fix issue parsing methods with char args ([#27](https://github.com/timo-reymann/fork-testlogger/issues/27)) ([b5078d1](https://github.com/timo-reymann/fork-testlogger/commit/b5078d16346a132cd31bd5cdee752e19019fcca3))
* make attachment description optional for nunit test logger. ([#87](https://github.com/timo-reymann/fork-testlogger/issues/87)) ([73e23a0](https://github.com/timo-reymann/fork-testlogger/commit/73e23a0ac1bda8153deba8a4127c642d60a47ea4))
* nested classes report UnknownNamespace.UnknownMethod ([#41](https://github.com/timo-reymann/fork-testlogger/issues/41)) ([c26414c](https://github.com/timo-reymann/fork-testlogger/commit/c26414c344d8ec93021309c56472fff6cea23d5a))
* publish package to github ([#12](https://github.com/timo-reymann/fork-testlogger/issues/12)) ([2732771](https://github.com/timo-reymann/fork-testlogger/commit/2732771c11731c59975865a07f676fb60ddf692c))
* remove TestResultInfo.Name from public API. ([#24](https://github.com/timo-reymann/fork-testlogger/issues/24)) ([8c0973b](https://github.com/timo-reymann/fork-testlogger/commit/8c0973b07efe6f4038f4c42bc1306e577333da02))
* standardize the start and end time formats in nunit report. ([#88](https://github.com/timo-reymann/fork-testlogger/issues/88)) ([6faaacd](https://github.com/timo-reymann/fork-testlogger/commit/6faaacd328b6fa562a718720f2846faa45db073a))
* test results must overwrite an existing file. ([#18](https://github.com/timo-reymann/fork-testlogger/issues/18)) ([f5704c0](https://github.com/timo-reymann/fork-testlogger/commit/f5704c09657c020278c25f7d344f6648274530c8))
* update stylecop version to a stable build. ([b344cda](https://github.com/timo-reymann/fork-testlogger/commit/b344cda24607026df5bbb9c7c2176b5fbb956696))
* use system drive for windows. ([f697837](https://github.com/timo-reymann/fork-testlogger/commit/f6978370151d2b529618a78599e063e15fc1d441))

## [5.0.0](https://github.com/spekt/testlogger/compare/v4.1.0...v5.0.0) (2024-12-19)


### ⚠ BREAKING CHANGES

* [junit] add testcase system-out and system-err along with attachment support. ([#136](https://github.com/spekt/testlogger/issues/136))

### Features

* [junit] add testcase system-out and system-err along with attachment support. ([#136](https://github.com/spekt/testlogger/issues/136)) ([dff18d6](https://github.com/spekt/testlogger/commit/dff18d6379009656fc622fe15e9a5f2708e72f33))
* update junit xsd to allow test case level outputs. ([#134](https://github.com/spekt/testlogger/issues/134)) ([1a37110](https://github.com/spekt/testlogger/commit/1a37110a8be5e4e20896826b2ed5db28b5dd4a06))

## [4.1.0](https://github.com/spekt/testlogger/compare/v4.0.254...v4.1.0) (2024-10-12)


### Features

* [JUnit] added StoreConsoleOutput option ([#115](https://github.com/spekt/testlogger/issues/115)) ([63fc58f](https://github.com/spekt/testlogger/commit/63fc58fecb2f48d60335b85b190e30fb7450e443))

## v4.0.254 - 2024/07/28

- Fix: [nunit logger]: standardize start and end times. See #88 and https://github.com/spekt/nunit.testlogger/issues/105.
- Fix: [nunit logger]: make attachment description optional. See #87 and https://github.com/spekt/nunit.testlogger/issues/106.
- Infra: [all loggers]: remove dependency on System.ValueTuple. See #82.
- Infra: [all loggers]: consolidate build infra, test infra and make E2E tests now run on library dependencies. Makes running tests faster and possible from the test explorers.
- Infra: [all loggers]: port various loggers to testlogger repo, add sample gitlab and circle CIs for junit.

## v3.x and earlier

- **JUnitXml.TestLogger**: See changelog on the releases page of the [JUnit Test Logger GitHub repository](https://github.com/spekt/junit.testlogger/).
- **NUnitXml.TestLogger**: See
  [CHANGELOG](https://github.com/spekt/nunit.testlogger/blob/master/CHANGELOG.md).
- **XunitXml.TestLogger**: See
  [CHANGELOG](https://github.com/spekt/xunit.testlogger/blob/master/CHANGELOG.md).
