## [v4.9.1](https://github.com/algolia/algoliasearch-client-javascript/compare/4.9.0...4.9.1)

* fix(types): support `facetQuery` in `MultipleQueriesQuery` (#1267) ([84355a9](https://github.com/algolia/algoliasearch-client-javascript/commit/84355a9)), closes [#1267](https://github.com/algolia/algoliasearch-client-javascript/issues/1267)



## [v4.9.0](https://github.com/algolia/algoliasearch-client-javascript/compare/4.8.6...4.9.0)

* feat(dictionaries): adds methods and tests (#1253) ([aed6554](https://github.com/algolia/algoliasearch-client-javascript/commit/aed6554)), closes [#1253](https://github.com/algolia/algoliasearch-client-javascript/issues/1253)
* feat(types): support `type` and `facet` in search methods (#1263) ([54c1cb7](https://github.com/algolia/algoliasearch-client-javascript/commit/54c1cb7)), closes [#1263](https://github.com/algolia/algoliasearch-client-javascript/issues/1263)
* fix(findAnswers): omit removeWordsIfNoResults correctly ([3aec216](https://github.com/algolia/algoliasearch-client-javascript/commit/3aec216))



## [v4.8.6](https://github.com/algolia/algoliasearch-client-javascript/compare/4.8.5...4.8.6)

* fix(answers): rename params to searchParameters (#1256) ([0229a12](https://github.com/algolia/algoliasearch-client-javascript/commit/0229a12)), closes [#1256](https://github.com/algolia/algoliasearch-client-javascript/issues/1256)
* fix(onSucess): correctly deprecate ([c7d04ca](https://github.com/algolia/algoliasearch-client-javascript/commit/c7d04ca))
* fix(types): update FindAnswersOptions (#1258) ([bdf67a5](https://github.com/algolia/algoliasearch-client-javascript/commit/bdf67a5)), closes [#1258](https://github.com/algolia/algoliasearch-client-javascript/issues/1258)
* refactor(retry): Spell success properly (#1254) ([173f5f1](https://github.com/algolia/algoliasearch-client-javascript/commit/173f5f1)), closes [#1254](https://github.com/algolia/algoliasearch-client-javascript/issues/1254)



## [v4.8.5](https://github.com/algolia/algoliasearch-client-javascript/compare/4.8.4...4.8.5)

* feat(ts): add virtual index parameters (#1251) ([cffd8f0](https://github.com/algolia/algoliasearch-client-javascript/commit/cffd8f0)), closes [#1251](https://github.com/algolia/algoliasearch-client-javascript/issues/1251) [#1249](https://github.com/algolia/algoliasearch-client-javascript/issues/1249)
* feat(ts): allow filters in rule condition (#1247) ([5032d6f](https://github.com/algolia/algoliasearch-client-javascript/commit/5032d6f)), closes [#1247](https://github.com/algolia/algoliasearch-client-javascript/issues/1247) [#1246](https://github.com/algolia/algoliasearch-client-javascript/issues/1246)



## [v4.8.4](https://github.com/algolia/algoliasearch-client-javascript/compare/4.8.3...4.8.4)

* feat(ts): add decompoundQuery (#1240) ([446c9a0](https://github.com/algolia/algoliasearch-client-javascript/commit/446c9a0)), closes [#1240](https://github.com/algolia/algoliasearch-client-javascript/issues/1240)
* feat(ts): add the attributesToTransliterate setting (#1244) ([b91c035](https://github.com/algolia/algoliasearch-client-javascript/commit/b91c035)), closes [#1244](https://github.com/algolia/algoliasearch-client-javascript/issues/1244)



## [v4.8.3](https://github.com/algolia/algoliasearch-client-javascript/compare/4.8.2...4.8.3)

* fix(ts): correct type for listIndices response (#1236) ([0bb6bba](https://github.com/algolia/algoliasearch-client-javascript/commit/0bb6bba)), closes [#1236](https://github.com/algolia/algoliasearch-client-javascript/issues/1236)



## [v4.8.2](https://github.com/algolia/algoliasearch-client-javascript/compare/4.8.1...4.8.2)

* fix(findAnswers): fix typing (#1233) ([a935d88](https://github.com/algolia/algoliasearch-client-javascript/commit/a935d88)), closes [#1233](https://github.com/algolia/algoliasearch-client-javascript/issues/1233)
* fix(ts): don't require every attribute to be highlighted (#1234) ([4591d0e](https://github.com/algolia/algoliasearch-client-javascript/commit/4591d0e)), closes [#1234](https://github.com/algolia/algoliasearch-client-javascript/issues/1234)



## [v4.8.1](https://github.com/algolia/algoliasearch-client-javascript/compare/4.8.0...4.8.1)

* fix(ts): correct search response for facets_stats (#1229) ([ac732d1](https://github.com/algolia/algoliasearch-client-javascript/commit/ac732d1)), closes [#1229](https://github.com/algolia/algoliasearch-client-javascript/issues/1229)



## [v4.8.0](https://github.com/algolia/algoliasearch-client-javascript/compare/4.7.0...4.8.0)

* feat(saveSynonyms): replaceExistingSynonyms -> clearExistingSynonyms (#1226) ([2fcf485](https://github.com/algolia/algoliasearch-client-javascript/commit/2fcf485)), closes [#1226](https://github.com/algolia/algoliasearch-client-javascript/issues/1226) [#1224](https://github.com/algolia/algoliasearch-client-javascript/issues/1224)
* fix(findAnswers): expose in lite version (#1227) ([6cb1d0a](https://github.com/algolia/algoliasearch-client-javascript/commit/6cb1d0a)), closes [#1227](https://github.com/algolia/algoliasearch-client-javascript/issues/1227)



## [v4.7.0](https://github.com/algolia/algoliasearch-client-javascript/compare/4.6.0...4.7.0)

* feat(findAnswers): implement the new method (experimental) (#1219) ([8d962ea](https://github.com/algolia/algoliasearch-client-javascript/commit/8d962ea)), closes [#1219](https://github.com/algolia/algoliasearch-client-javascript/issues/1219)
* feat(analytics & recommendation): allow creation of clients (initAnalytics, initRecommendation) with their own credentials (#1223) ([a7938b0](https://github.com/algolia/algoliasearch-client-javascript/commit/a7938b0))



## [v4.6.0](https://github.com/algolia/algoliasearch-client-javascript/compare/4.5.1...4.6.0)

* fix(node): allow passing requesterOptions (#1215) ([4348b38](https://github.com/algolia/algoliasearch-client-javascript/commit/4348b38)), closes [#1215](https://github.com/algolia/algoliasearch-client-javascript/issues/1215)
* fix(node): reuse http agent across client (#1216) ([f6e9e56](https://github.com/algolia/algoliasearch-client-javascript/commit/f6e9e56)), closes [#1216](https://github.com/algolia/algoliasearch-client-javascript/issues/1216)
* feat(client-search): add personalization field to RankingInfo (#1213) ([50b78a3](https://github.com/algolia/algoliasearch-client-javascript/commit/50b78a3)), closes [#1213](https://github.com/algolia/algoliasearch-client-javascript/issues/1213)



## [v4.5.1](https://github.com/algolia/algoliasearch-client-javascript/compare/4.5.0...4.5.1)

### Fixed

- avoid bundle-size increase by using a slightly older version of babel

## [v4.5.0](https://github.com/algolia/algoliasearch-client-javascript/compare/4.4.0...4.5.0)

### Added

- introduce a new `Hit` type, returned from search operations ([#1191](https://github.com/algolia/algoliasearch-client-javascript/pull/1191))
- Allow `hosts` array to also accept strings ([#1189](https://github.com/algolia/algoliasearch-client-javascript/pull/1189))

### Fixed

- add missing updatedAt attribute to client-analytics ([#1186](https://github.com/algolia/algoliasearch-client-javascript/pull/1186))
- a/b test VariantResponse typing ([#1185](https://github.com/algolia/algoliasearch-client-javascript/pull/1185))
- getObjects can also return `null` if an object is not existing ([#1183](https://github.com/algolia/algoliasearch-client-javascript/pull/1183))

## [v4.4.0](https://github.com/algolia/algoliasearch-client-javascript/compare/4.3.1...4.4.0)

### Added

- Accept multiple objectIDs in a Rule promotion ([#1156](https://github.com/algolia/algoliasearch-client-javascript/pull/1156), [#1155](https://github.com/algolia/algoliasearch-client-javascript/pull/1155))
- Accept a custom http(s) agent in `createNodeHttpRequester` ([#1180](https://github.com/algolia/algoliasearch-client-javascript/pull/1180))

## [v4.3.1](https://github.com/algolia/algoliasearch-client-javascript/compare/4.3.0...4.3.1)

### Added

- Support to multiple `conditions` on query rules ([#1171](https://github.com/algolia/algoliasearch-client-javascript/pull/1171), [#1174](https://github.com/algolia/algoliasearch-client-javascript/pull/1174))

## [v4.3.0](https://github.com/algolia/algoliasearch-client-javascript/compare/4.2.0...4.3.0)

### Added

- `naturalLanguages` option type ([#1147](https://github.com/algolia/algoliasearch-client-javascript/pull/1147))
- `shouldStop` option to stop browse ([#1029](https://github.com/algolia/algoliasearch-client-javascript/pull/1029))
- `inner_queries` property to `getLogs` response ([#1109](https://github.com/algolia/algoliasearch-client-javascript/pull/1109), [#1166](https://github.com/algolia/algoliasearch-client-javascript/pull/1166))
- `enablePersonalization` option to type `Settings` ([#1151](https://github.com/algolia/algoliasearch-client-javascript/pull/1151))

### Fixed

- additional `clear`, `delete` & `deleteObject` types for the `.batch` method ([#1149](https://github.com/algolia/algoliasearch-client-javascript/pull/1149))
- unhandled promise issue while using while using `accountCopyIndex` ([#1154](https://github.com/algolia/algoliasearch-client-javascript/pull/1154))
- node requester unicode characters being corrupted on large responses ([#1164](https://github.com/algolia/algoliasearch-client-javascript/pull/1164))

## [v4.2.0](https://github.com/algolia/algoliasearch-client-javascript/compare/4.1.0...4.2.0)

### Added
- Improved `acl` property type in `GetApiKeyResponse` and `addApiKey` function param ([#1126](https://github.com/algolia/algoliasearch-client-javascript/pull/1126))
- Improved `AnalyticsClientOptions` property type region ([#1085](https://github.com/algolia/algoliasearch-client-javascript/pull/1085))
- Responses types can now be mutated ([#1068](https://github.com/algolia/algoliasearch-client-javascript/pull/1068))

### Fixed
- Type `Log` ([#1139](https://github.com/algolia/algoliasearch-client-javascript/pull/1139))

## [v4.1.0](https://github.com/algolia/algoliasearch-client-javascript/compare/4.0.3...4.1.0)

### Added
- Field `filterPromotes` in Rule type ([#1013](https://github.com/algolia/algoliasearch-client-javascript/pull/1013))
- Method `hasPendingMappings` ([#1024](https://github.com/algolia/algoliasearch-client-javascript/pull/1024))

### Fixed
- Field `abtests` in GetAbTestsResponse type ([#1012](https://github.com/algolia/algoliasearch-client-javascript/pull/1012))
- `browse` related methods not bubbling up errors as expected ([#1042](https://github.com/algolia/algoliasearch-client-javascript/pull/1042))
- Header `x-algolia-user-id` is not allowed on browser env ([#1023](https://github.com/algolia/algoliasearch-client-javascript/pull/1023))

## [v4.0.3](https://github.com/algolia/algoliasearch-client-javascript/compare/4.0.2...4.0.3)

### Fixed
- `browseObjects` missing cursor error ([#1011](https://github.com/algolia/algoliasearch-client-javascript/pull/1011))
- `browseSynonyms|browseRules` giving just a maximum of 20 hits ([#1011](https://github.com/algolia/algoliasearch-client-javascript/pull/1011))
- Node entry point not es6 compliant ([#1005](https://github.com/algolia/algoliasearch-client-javascript/pull/1005))

## [v4.0.2](https://github.com/algolia/algoliasearch-client-javascript/compare/4.0.1...4.0.2)

### Fixed
- DOMException being thrown while instantiating browser local storage cache driver ([#999](https://github.com/algolia/algoliasearch-client-javascript/pull/999))

## [v4.0.1](https://github.com/algolia/algoliasearch-client-javascript/compare/4.0.0...4.0.1)

### Fixed
- Missing `repository` entry on `package.json` ([#989](https://github.com/algolia/algoliasearch-client-javascript/pull/989))

## [v4.0.0](https://github.com/algolia/algoliasearch-client-javascript/compare/3.35.1...4.0.0)

- Major version: [Upgrade Guide](https://www.algolia.com/doc/api-client/getting-started/upgrade-guides/javascript/)
