# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [3.2.3](https://github.com/appium/appium/compare/@appium/fake-driver@3.2.2...@appium/fake-driver@3.2.3) (2022-01-11)

**Note:** Version bump only for package @appium/fake-driver





## [3.2.2](https://github.com/appium/appium/compare/@appium/fake-driver@3.2.1...@appium/fake-driver@3.2.2) (2021-11-23)

**Note:** Version bump only for package @appium/fake-driver





## [3.2.1](https://github.com/appium/appium/compare/@appium/fake-driver@3.2.0...@appium/fake-driver@3.2.1) (2021-11-19)


### Bug Fixes

* **fake-driver:** create cjs wrapper ([a93f37a](https://github.com/appium/appium/commit/a93f37ad060ecfca41895bed49eed60413959421))





# [3.2.0](https://github.com/appium/appium/compare/@appium/fake-driver@3.1.0...@appium/fake-driver@3.2.0) (2021-11-15)


### Features

* **fake-driver:** add a new 'PROXY' context that does 'proxying' for use in testing ([9e6c0a1](https://github.com/appium/appium/commit/9e6c0a13ef197c3a8caa9e18bdf4f8e6960951f1))





# [3.1.0](https://github.com/appium/appium/compare/@appium/fake-driver@3.0.5...@appium/fake-driver@3.1.0) (2021-11-09)


### Features

* **fake-driver:** add a schema ([cf7438a](https://github.com/appium/appium/commit/cf7438a352a8668b6a3efdc2d7abb0252554630f))





## [3.0.5](https://github.com/appium/appium/compare/@appium/fake-driver@3.0.4...@appium/fake-driver@3.0.5) (2021-09-16)

**Note:** Version bump only for package @appium/fake-driver





## [3.0.4](https://github.com/appium/appium/compare/@appium/fake-driver@3.0.3...@appium/fake-driver@3.0.4) (2021-09-16)

**Note:** Version bump only for package @appium/fake-driver





## [3.0.3](https://github.com/appium/appium/compare/@appium/fake-driver@3.0.2...@appium/fake-driver@3.0.3) (2021-09-15)

**Note:** Version bump only for package @appium/fake-driver





## [3.0.2](https://github.com/appium/appium/compare/@appium/fake-driver@3.0.1...@appium/fake-driver@3.0.2) (2021-09-14)

**Note:** Version bump only for package @appium/fake-driver





## [3.0.1](https://github.com/appium/appium/compare/@appium/fake-driver@3.0.0...@appium/fake-driver@3.0.1) (2021-09-14)

**Note:** Version bump only for package @appium/fake-driver





# [3.0.0](https://github.com/appium/appium/compare/@appium/fake-driver@2.2.0...@appium/fake-driver@3.0.0) (2021-08-16)



# 2.0.0-beta (2021-08-13)


### Bug Fixes

* **fake-driver:** copy non-JS files into build dir at transpile time; closes [#15471](https://github.com/appium/appium/issues/15471) ([950372c](https://github.com/appium/appium/commit/950372c1bdf556463eac285999eba482682666db))


### chore

* update @appium/fake-driver to use @appium/base-driver ([#15436](https://github.com/appium/appium/issues/15436)) ([c66144d](https://github.com/appium/appium/commit/c66144d62b23681f91b45c45648dddf51f0ea991)), closes [#15425](https://github.com/appium/appium/issues/15425)


### Features

* **appium:** Add driver and plugin server arg injection feature ([#15388](https://github.com/appium/appium/issues/15388)) ([d3c11e3](https://github.com/appium/appium/commit/d3c11e364dffff87ac38ac8dc3ad65a1e4534a9a))


### BREAKING CHANGES

* `fake-driver` now depends upon `@appium/base-driver@8.x`

## `@appium/fake-driver`

- need to use w3c capabilities only
- fix: find `app.xml` fixture properly when running tests via `mocha --require=@babel/register`

## `@appium/base-driver`

- fixed a dead URL in a comment
- updated the "logging" tests to manually supply w3c capabilities.  `createSession()` does it for you, but `executeCommand('createSession')` does not.
- display the name of the driver under test when executing base driver's test suite with other drivers