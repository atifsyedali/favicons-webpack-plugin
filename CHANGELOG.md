# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [1.0.6](https://github.com/jantimon/favicons-webpack-plugin/compare/v1.0.4...v1.0.6) (2021-12-13)

### [1.0.4](https://github.com/jantimon/favicons-webpack-plugin/compare/v1.0.3...v1.0.4) (2019-10-28)

### [1.0.3](https://github.com/jantimon/favicons-webpack-plugin/compare/v1.0.2...v1.0.3) (2019-10-28)

### [1.0.2](https://github.com/jantimon/favicons-webpack-plugin/compare/v1.0.1...v1.0.2) (2019-09-06)


### Bug Fixes

* fix output path of dev favicon ([b2b8fc7](https://github.com/jantimon/favicons-webpack-plugin/commit/b2b8fc7)), closes [#164](https://github.com/jantimon/favicons-webpack-plugin/issues/164)

### [1.0.1](https://github.com/jantimon/favicons-webpack-plugin/compare/v1.0.0...v1.0.1) (2019-08-16)


### Bug Fixes

* fix hash generation for light-mode ([67a8850](https://github.com/jantimon/favicons-webpack-plugin/commit/67a8850)), closes [#159](https://github.com/jantimon/favicons-webpack-plugin/issues/159)

## [1.0.0](https://github.com/jantimon/favicons-webpack-plugin/compare/v0.0.4...v1.0.0) (2019-08-14)


### ⚠ BREAKING CHANGES

* Require Node 6 is or newer
* align with webpack 4 and drop support for node < 6 ([e41a990](https://github.com/jantimon/favicons-webpack-plugin/commit/e41a990))
* prefixes are always treated as a directory path
* remove -[hash] from default prefix
* by default only a subset of icons is generated in development 

### Bug Fixes

* always treat prefix as a directory path ([17aabba](https://github.com/jantimon/favicons-webpack-plugin/commit/17aabba))
* avoid failing if html-webpack-plugin isn't installed ([1c0ee82](https://github.com/jantimon/favicons-webpack-plugin/commit/1c0ee82))
* broken links in content meta tags and browserconfig.xml ([51bd1f8](https://github.com/jantimon/favicons-webpack-plugin/commit/51bd1f8))
* do not interpolate empty prefix ([9e197f1](https://github.com/jantimon/favicons-webpack-plugin/commit/9e197f1))
* do not rely on html-webpack-plugin's internals ([9f166a7](https://github.com/jantimon/favicons-webpack-plugin/commit/9f166a7))
* handle author as object in package.json ([06da1f8](https://github.com/jantimon/favicons-webpack-plugin/commit/06da1f8))
* invalidate cache when changing publicPath ([29c9902](https://github.com/jantimon/favicons-webpack-plugin/commit/29c9902))
* set SingleEntryPlugin name ([15c4a1a](https://github.com/jantimon/favicons-webpack-plugin/commit/15c4a1a))
* workaround issues with libxml ([d23aea5](https://github.com/jantimon/favicons-webpack-plugin/commit/d23aea5))
* update favicons to version 5.0.0 ([3737fa3](https://github.com/jantimon/favicons-webpack-plugin/commit/3737fa3))


### Features

* add inject force option to overrule the html-webpack-plugin favicon option ([73b51a1](https://github.com/jantimon/favicons-webpack-plugin/commit/73b51a1))
* add light mode during development ([47986be](https://github.com/jantimon/favicons-webpack-plugin/commit/47986be))
* add support for html-webpack-plugin 4.x ([94ead15](https://github.com/jantimon/favicons-webpack-plugin/commit/94ead15))
* add support for Webpack 4 ([9db88ee](https://github.com/jantimon/favicons-webpack-plugin/commit/9db88ee))
* add zero-config mode ([793a840](https://github.com/jantimon/favicons-webpack-plugin/commit/793a840))
* added compatibility for new webpack 4 .hooks mode ([5ab0bb8](https://github.com/jantimon/favicons-webpack-plugin/commit/5ab0bb8))
* allow skipping specific instances of html-webpack-plugin ([d554946](https://github.com/jantimon/favicons-webpack-plugin/commit/d554946))
* allow to specify a custom output paths ([0755161](https://github.com/jantimon/favicons-webpack-plugin/commit/0755161))
* cache assets using cache-loader ([f2758ca](https://github.com/jantimon/favicons-webpack-plugin/commit/f2758ca))
* change the default output prefix to assets ([99a7310](https://github.com/jantimon/favicons-webpack-plugin/commit/99a7310))
* expose all options of the favicons npm package ([ca4b6e9](https://github.com/jantimon/favicons-webpack-plugin/commit/ca4b6e9))
* give the user more options to specifiy where to inject html ([c8a4767](https://github.com/jantimon/favicons-webpack-plugin/commit/c8a4767))
* make cache directory configurable ([43a5aef](https://github.com/jantimon/favicons-webpack-plugin/commit/43a5aef))
* remove -[hash] from default prefix ([fc0eb3e](https://github.com/jantimon/favicons-webpack-plugin/commit/fc0eb3e))
* the generated [hash] now is based on the current favicon-webpack-plugin version ([ccfea37](https://github.com/jantimon/favicons-webpack-plugin/commit/ccfea37))

# 0.0.9

+ Improve support for Webpack 4

# 0.0.8

+ Add support for Webpack 4

# 0.0.7

+ Inject generated HTML to end of head

# 0.0.6

+ Add support for `devtool: 'eval'`

# 0.0.5

+ Invalidate cache on plugin version change

# 0.0.4

+ Add persistent caching to generate the favicons only once

# 0.0.3

+ Rename filename option to statsFilename
+ Add emitStats option (set to false by default)

## BREAKING CHANGE

+ the stats file isn't generated by default anymore

# 0.0.2

+ Fix typos


# 0.0.1

+ Initial release
