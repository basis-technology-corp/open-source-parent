# Release Notes for com.basistech:open-source-parent #

# 15.0.0
- Upgrade many dependency versions
- Upgrade many plugin versions; including `maven-release-plugin`.
- Upgrade to 7.0.0 of `com.basistech:open-source-buildtools` to pick up PMD deprecation fixes.
- Fix checkstyle plugin configuration:  Use `inputEncoding` instead of `encoding`.
- Fix checkstyle plugin configuration:  `linkXRef` not applicable for `check` goal.
- Fix pmd plugin configuration:  Use `inputEncoding` instead of `sourceEncoding`.
- Change organization url to rosette.com

# 14.0.0

## [WS-2698](https://basistech.atlassian.net/browse/WS-2698)
- Add dependency on custom `com.basistech.org.apache.httpcomponents`
- Add new property `bt-custom-httpclient-osgi-version` for the custom artifact

# 13.0.0

## [COMN-297](https://basistech.atlassian.net/browse/COMN-297)
- Add dependency on `org.cyclonedx:cyclonedx-maven-plugin` version 2.7.4
- Add dependency on `io.github.pmckeown:dependency-track-maven-plugin` version 1.4.0
- Update `bt-guava-version` to 31.1-jre from 26.0-jre
- Update `bt-protobuf-version` to 3.21.7 from 3.12.2

# 12.0.0

## [COMN-286](https://basistech.atlassian.net/browse/COMN-286)
- Update `bt-snakeyaml-version` to 1.33 from 1.30

## [COMN-287](https://basistech.atlassian.net/browse/COMN-287)
- Update lots of plugins and dependencies

# 11.0.0

## [COMN-284](https://basistech.atlassian.net/browse/COMN-284)
- Update `nexus-staging-plugin-version` to 1.6.12 from 1.6.8
- Update `bt-common-api-version` to 37.5.0 from 37.4.0

## [COMN-282](https://basistech.atlassian.net/browse/COMN-282)
- Update `maven-enforcer-plugin` to require Java version 17
- Add new property `bt.compile.release` to target Java version 11
- Remove redundant properties `bt.compile.source`, `bt.compile.target`, `bt.java.source`, and `bt.java.target`

# 10.0.0

## [COMN-279](https://basistech.atlassian.net/browse/COMN-279)
- Update `bt-log4j-version` to 2.17.1 from 1.2.17
- Change Log4j dependencies from `log4j:log4j` to
  `org.apache.logging.log4j:log4j-api`,
  `org.apache.logging.log4j:log4j-core`, and
  `org.apache.logging.log4j:log4j-slf4j-impl`
- Remove `org.slf4j:slf4j-log4j12` dependency

## [COMN-280](https://basistech.atlassian.net/browse/COMN-280)
- Update lots of plugins and dependencies
- Change Apache Commons Lang dependency from `commons-lang:commons-lang` to
  `org.apache.commons:commons-lang3`
- Add dependency on `org.slf4j:log4j-over-slf4j` version 1.7.32

## [ROS-327](https://basistech.atlassian.net/browse/ROS-327)
- Add a dependency on `org.apache.commons:commons-compress` version 1.21

# 9.0.0

## [COMN-274](https://basistech.atlassian.net/browse/COMN-274):
- Update `dependency-check-maven.version` to 6.1.6 from 6.0.5

## [COMN-276](https://basistech.atlassian.net/browse/COMN-276):
- Update `bt-common-api-version` to 37.3.0 from 37.2.0

# 8.1.0 #

## [COMN-273](https://basistech.atlassian.net/browse/COMN-273):
- Update `bt-common-api-version` to 37.2.0 from 37.1.0

# 8.0.0 #

## [COMN-271](https://basistech.atlassian.net/browse/COMN-271):
- Update `bt-common-api-version` to 37.1.0 from 37.0.1

# 7.0.1 #
## [COMN-268](https://basistech.atlassian.net/browse/COMN-268):
- downgrade maven-release-plugin to 2.5.3 for MRELEASE-1042

# 7.0.0 #
## [COMN-268](https://basistech.atlassian.net/browse/COMN-268):
- update dependency-check; remove execution

# 5.3.0 #
## [ROS-321](https://basistech.atlassian.net/browse/ROS-321):
- integrate Sonarqube
