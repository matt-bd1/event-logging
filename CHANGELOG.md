# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) 
and this project adheres to [Semantic Versioning](http://semver.org/).


## [Unreleased]

~~~
DO NOT ADD CHANGES HERE - ADD THEM USING log_change.sh
~~~


## [v5.0-beta.36_schema-v4.0-beta.10] - 2023-05-10

* No change to event-logging library. Change Maven repository credentials.


## [v5.0-beta.35_schema-v4.0-beta.10] - 2022-06-07

* No change to event-logging library. Fix automated build.


## [v5.0-beta.34_schema-v4.0-beta.10] - 2022-06-07

* No change to event-logging library. Fix automated build.


## [v5.0-beta.33_schema-v4.0-beta.10] - 2022-06-07

* No change to event-logging library. Fix build process.


## [v5.0-beta.32_schema-v4.0-beta.10] - 2022-05-26

* Update schema to schema-v4.0-beta.10 which fixes a number of typos in the schema annotations and thus the event-logging javadoc.


## [v5.0-beta.31_schema-v4.0-beta.3] - 2022-04-29

* Issue **#14** : Change DeviceUtil to strip square brackets from IPv6 addresses to ensure they are valid in the Schema.


## [v5.0-beta.30_schema-v4.0-beta.3] - 2021-11-12

* Make construcotr for MockEventLoggerBuilder public.


## [v5.0-beta.29_schema-v4.0-beta.3] - 2021-11-12

* Fix CI build.


## [v5.0-beta.28_schema-v4.0-beta.3] - 2021-11-12

* Remove `loggedResult()` and `loggedAction()` methods from EventLoggingService. Instead use `loggedWorkBuilder()`.


## [v5.0-beta.27_schema-v4.0-beta.3] - 2021-11-09

* Add loggedWorkBuilder() to EventLoggingService.

* Deprecate loggedXXX methods in EventLoggingService.


## [v5.0-beta.26_schema-v4.0-beta.3] - 2021-11-08

* No changes to event-logging. Fix build process.


## [v5.0-beta.25_schema-v4.0-beta.3] - 2021-11-08

* No changes to event-logging. Fix build process.


## [v5.0-beta.24_schema-v4.0-beta.3] - 2021-11-08

* No changes to event-logging. Fix build process.


## [v5.0-beta.23_schema-v4.0-beta.3] - 2021-11-08

* No changes to event-logging. Fix build process.


## [v5.0-beta.22_schema-v4.0-beta.3] - 2021-11-08

* No changes to event-logging. Fix build process.


## [v5.0-beta.21_schema-v4.0-beta.3] - 2021-11-05

* No changes to event-logging. Fix build process.


## [v5.0-beta.20_schema-v4.0-beta.3] - 2021-11-05

* No changes to event-logging. Fix build process.


## [v5.0-beta.19_schema-v4.0-beta.3] - 2021-11-05

* No changes to event-logging. Fix build process.


## [v5.0-beta.18_schema-v4.0-beta.3] - 2021-11-05

* Fix problem of a failure Outcome not being added when an exception is thrown during `loggedWork` in `log()`.


## [v5.0-beta.17_schema-v4.0-beta.3] - 2021-04-26

* Change filename of Maven artifacts from `event-logging-api...` to `event-logging...`.


## [v5.0-beta.16_schema-v4.0-beta.3] - 2021-04-23

* Change maven coordinates to `uk.gov.gchq.eventlogging:event-logging` and publish on maven central instead of bintray.


## [v5.0-beta.15_schema-v4.0-beta.3] - 2021-04-08

* Fix build number.


## [v5.0-beta.14_schema-v4.0-beta.3] - 2021-04-08

* Issue **gchq/stroom#2170** : Added better logging for FQDN resolution.

* Uplift gradle version.

* Uplift schema to `v4.0-beta.3`.


## [v5.0-beta.13_schema-v4.0-beta.1] - 2021-03-08

* No changes


## [v5.0-beta.12_schema-v4.0-beta.1] - 2021-03-08

* No changes


## [v5.0-beta.11_schema-v4.0-beta.1] - 2021-01-08

* Add additional `createOutcome` methods to `EventLoggingUtil`.


## [v5.0-beta.10_schema-v4.0-beta.1] - 2021-01-08

* Add `Purpose` arg to `loggedXXX` methods.

* Add example application

* Improve README


## [v5.0-beta.9_schema-v4.0-beta.1] - 2021-01-07

* Add missing handling of unsuccessful logged work outcome.


## [v5.0-beta.8_schema-v4.0-beta.1] - 2021-01-07

* Add overloaded `log` and `createEvent` methods to `EventLoggingService`.


## [v5.0-beta.7_schema-v4.0-beta.1] - 2021-01-07

* Add overloaded `log` method to `EventLoggingService`.


## [v5.0-beta.6_schema-v4.0-beta.1] - 2021-01-07

* Improve loggedXXX methods in `EventLoggingService`.


## [v5.0-beta.5_schema-v4.0-beta.1] - 2021-01-05

* Add loggedResult and loggedAction methods.


## [v5.0-beta.4_schema-v4.0-beta.1] - 2021-01-04

* Add `AdvancedQueryOperator` interface.


## [v5.0-beta.3_schema-v4.0-beta.1] - 2020-12-17

* Change `HasOutcome#getOutcome` to return `BaseOutcome`, improve binding for `HasOutcome`.


## [v5.0-beta.2_schema-v4.0-beta.1] - 2020-12-17

* Add `HasOutcome` interface and make all complex types with an Outcome element implement it.


## [v5.0-beta.1_schema-v4.0-beta.1] - 2020-12-17

* Uplifted schema to v4.0-beta.1

* Issue **gchq/event-logging-schema#54** : Remove `Outcome` from `Network`, add new `NetworkOutcome` class.

* Issue **gchq/event-logging-schema#63**: Allow `EventSource/Door` to be combined with `Device`, `Client` and `Server`.

* Issue **gchq/event-logging-schema#64**: Change `Door` sub-element constraints to be consistent with documentation.

* Issue **gchq/event-logging-schema#65**: Add enum values to `AuthenticateActionSimpleType` and `AuthenticateLogonTypeSimpleType` to better describe physical access events

* Issue **gchq/event-logging-schema#10** : Add `SearchResults` to `BaseMultiObjectComplexType` to allow for use cases like `View/SearchResults`. 

* Issue **gchq/event-logging-schema#10** : Add `Id`, `Name` and `Description` to `QueryComplexType` to allow the linking of query to results.

* Issue **gchq/event-logging-schema#39** : Add `TimeZoneName` element to `LocationComplexType` to improve the recording of time zone information.

* Issue **gchq/event-logging-schema#44** : Add `Approval` schema action.

* Issue **gchq/event-logging-schema#47** : Add `CachedInteractive`, `CachedRemoteInteractive`, `Proxy` and `Other` logon types to `AuthenticateLogonTypeSimpleType`.

* Issue **gchq/event-logging-schema#40**: Add `State`, `City` and `Town` elements to provide more Location detail.

* Issue **gchq/event-logging-schema#3** : Add `Type` attribute to `Hash` element in `BaseFileComplexType`.

* Issue **gchq/event-logging-schema#35** : Add `Meta` element to `Event` and `BaseObjectGroup` to allow extension/decoration.

* Issue **gchq/event-logging-schema#31** : Add `Tags` element to `BaseObjectGroup`.

* Issue **gchq/event-logging-schema#37** : Add `Tags` element to `SystemComplexType`.

* Generate javadoc from the schema annotations.

* Issue **5** : Add fluent builder api code.

* Issue **3** : Change xjc bindings to force all top level classes [BREAKING CHANGE].

* Issue **6** : Fix hard coded success value in EventLoggingUtil.createOutcome().

* Revert to java 8


[Unreleased]: https://github.com/gchq/event-logging/compare/v5.0-beta.36_schema-v4.0-beta.10...HEAD
[v5.0-beta.36_schema-v4.0-beta.10]: https://github.com/gchq/event-logging/compare/v5.0-beta.35_schema-v4.0-beta.10...v5.0-beta.36_schema-v4.0-beta.10
[v5.0-beta.35_schema-v4.0-beta.10]: https://github.com/gchq/event-logging/compare/v5.0-beta.34_schema-v4.0-beta.10...v5.0-beta.35_schema-v4.0-beta.10
[v5.0-beta.34_schema-v4.0-beta.10]: https://github.com/gchq/event-logging/compare/v5.0-beta.33_schema-v4.0-beta.10...v5.0-beta.34_schema-v4.0-beta.10
[v5.0-beta.33_schema-v4.0-beta.10]: https://github.com/gchq/event-logging/compare/v5.0-beta.32_schema-v4.0-beta.10...v5.0-beta.33_schema-v4.0-beta.10
[v5.0-beta.32_schema-v4.0-beta.10]: https://github.com/gchq/event-logging/compare/v5.0-beta.31_schema-v4.0-beta.3...v5.0-beta.32_schema-v4.0-beta.10
[v5.0-beta.31_schema-v4.0-beta.3]: https://github.com/gchq/event-logging/compare/v5.0-beta.30_schema-v4.0-beta.3...v5.0-beta.31_schema-v4.0-beta.3
[v5.0-beta.30_schema-v4.0-beta.3]: https://github.com/gchq/event-logging/compare/v5.0-beta.29_schema-v4.0-beta.3...v5.0-beta.30_schema-v4.0-beta.3
[v5.0-beta.29_schema-v4.0-beta.3]: https://github.com/gchq/event-logging/compare/v5.0-beta.28_schema-v4.0-beta.3...v5.0-beta.29_schema-v4.0-beta.3
[v5.0-beta.28_schema-v4.0-beta.3]: https://github.com/gchq/event-logging/compare/v5.0-beta.27_schema-v4.0-beta.3...v5.0-beta.28_schema-v4.0-beta.3
[v5.0-beta.27_schema-v4.0-beta.3]: https://github.com/gchq/event-logging/compare/v5.0-beta.26_schema-v4.0-beta.3...v5.0-beta.27_schema-v4.0-beta.3
[v5.0-beta.26_schema-v4.0-beta.3]: https://github.com/gchq/event-logging/compare/v5.0-beta.25_schema-v4.0-beta.3...v5.0-beta.26_schema-v4.0-beta.3
[v5.0-beta.25_schema-v4.0-beta.3]: https://github.com/gchq/event-logging/compare/v5.0-beta.24_schema-v4.0-beta.3...v5.0-beta.25_schema-v4.0-beta.3
[v5.0-beta.24_schema-v4.0-beta.3]: https://github.com/gchq/event-logging/compare/v5.0-beta.23_schema-v4.0-beta.3...v5.0-beta.24_schema-v4.0-beta.3
[v5.0-beta.23_schema-v4.0-beta.3]: https://github.com/gchq/event-logging/compare/v5.0-beta.22_schema-v4.0-beta.3...v5.0-beta.23_schema-v4.0-beta.3
[v5.0-beta.22_schema-v4.0-beta.3]: https://github.com/gchq/event-logging/compare/v5.0-beta.21_schema-v4.0-beta.3...v5.0-beta.22_schema-v4.0-beta.3
[v5.0-beta.21_schema-v4.0-beta.3]: https://github.com/gchq/event-logging/compare/v5.0-beta.20_schema-v4.0-beta.3...v5.0-beta.21_schema-v4.0-beta.3
[v5.0-beta.20_schema-v4.0-beta.3]: https://github.com/gchq/event-logging/compare/v5.0-beta.19_schema-v4.0-beta.3...v5.0-beta.20_schema-v4.0-beta.3
[v5.0-beta.19_schema-v4.0-beta.3]: https://github.com/gchq/event-logging/compare/v5.0-beta.18_schema-v4.0-beta.3...v5.0-beta.19_schema-v4.0-beta.3
[v5.0-beta.18_schema-v4.0-beta.3]: https://github.com/gchq/event-logging/compare/v5.0-beta.17_schema-v4.0-beta.3...v5.0-beta.18_schema-v4.0-beta.3
[v5.0-beta.17_schema-v4.0-beta.3]: https://github.com/gchq/event-logging/compare/v5.0-beta.16_schema-v4.0-beta.1...v5.0-beta.17_schema-v4.0-beta.3
[v5.0-beta.16_schema-v4.0-beta.3]: https://github.com/gchq/event-logging/compare/v5.0-beta.15_schema-v4.0-beta.1...v5.0-beta.16_schema-v4.0-beta.3
[v5.0-beta.15_schema-v4.0-beta.3]: https://github.com/gchq/event-logging/compare/v5.0-beta.14_schema-v4.0-beta.1...v5.0-beta.15_schema-v4.0-beta.3
[v5.0-beta.14_schema-v4.0-beta.1]: https://github.com/gchq/event-logging/compare/v5.0-beta.13_schema-v4.0-beta.1...v5.0-beta.14_schema-v4.0-beta.1
[v5.0-beta.13_schema-v4.0-beta.1]: https://github.com/gchq/event-logging/compare/v5.0-beta.12_schema-v4.0-beta.1...v5.0-beta.13_schema-v4.0-beta.1
[v5.0-beta.12_schema-v4.0-beta.1]: https://github.com/gchq/event-logging/compare/v5.0-beta.11_schema-v4.0-beta.1...v5.0-beta.12_schema-v4.0-beta.1
[v5.0-beta.11_schema-v4.0-beta.1]: https://github.com/gchq/event-logging/compare/v5.0-beta.10_schema-v4.0-beta.1...v5.0-beta.11_schema-v4.0-beta.1
[v5.0-beta.10_schema-v4.0-beta.1]: https://github.com/gchq/event-logging/compare/v5.0-beta.9_schema-v4.0-beta.1...v5.0-beta.10_schema-v4.0-beta.1
[v5.0-beta.9_schema-v4.0-beta.1]: https://github.com/gchq/event-logging/compare/v5.0-beta.8_schema-v4.0-beta.1...v5.0-beta.9_schema-v4.0-beta.1
[v5.0-beta.8_schema-v4.0-beta.1]: https://github.com/gchq/event-logging/compare/v5.0-beta.7_schema-v4.0-beta.1...v5.0-beta.8_schema-v4.0-beta.1
[v5.0-beta.7_schema-v4.0-beta.1]: https://github.com/gchq/event-logging/compare/v5.0-beta.6_schema-v4.0-beta.1...v5.0-beta.7_schema-v4.0-beta.1
[v5.0-beta.6_schema-v4.0-beta.1]: https://github.com/gchq/event-logging/compare/v5.0-beta.5_schema-v4.0-beta.1...v5.0-beta.6_schema-v4.0-beta.1
[v5.0-beta.5_schema-v4.0-beta.1]: https://github.com/gchq/event-logging/compare/v5.0-beta.4_schema-v4.0-beta.1...v5.0-beta.5_schema-v4.0-beta.1
[v5.0-beta.4_schema-v4.0-beta.1]: https://github.com/gchq/event-logging/compare/v5.0-beta.3_schema-v4.0-beta.1...v5.0-beta.4_schema-v4.0-beta.1
[v5.0-beta.3_schema-v4.0-beta.1]: https://github.com/gchq/event-logging/compare/v5.0-beta.2_schema-v4.0-beta.1...v5.0-beta.3_schema-v4.0-beta.1
[v5.0-beta.2_schema-v4.0-beta.1]: https://github.com/gchq/event-logging/compare/v5.0-beta.1_schema-v4.0-beta.1...v5.0-beta.2_schema-v4.0-beta.1
[v5.0-beta.1_schema-v4.0-beta.1]: https://github.com/gchq/event-logging/compare/v4.0.7_schema-v3.2.4...v5.0-beta.1_schema-v4.0-beta.1
