# Release Notes for com.basistech:open-source-parent #

# 24.0.1

## [COMN-415](https://babelstreet.atlassian.net/browse/COMN-415)

- Automatically publish to Maven Central Publisher Portal
- Update properties:
    - `bt-adm-version` to 3.0.7
    - `bt-checkstyle-version` to 11.0.0
    - `bt-common-api-version` to 38.0.7

# 24.0.0

## [COMN-415](https://babelstreet.atlassian.net/browse/COMN-415)

- Add `central-publishing-maven-plugin` plugin
- Add `central-publishing-maven-plugin.version` property at 0.8.0
- Remove `org.sonatype.plugins:nexus-staging-maven-plugin` plugin
- Remove properties:
    - `nexus-staging-maven-plugin.version`
    - `nexus-staging-plugin-nexus-url`
    - `nexus-staging-plugin-ossrh-nexus-url`
    - `nexus-staging-plugin-ossrh-server-id`
    - `nexus-staging-plugin-server-id`
    - `nexus-staging-plugin-skip-staging`
- Update properties:
    - `bt-checkstyle-version` to 11.0.0
    - `bt-commons-cli-version` to 1.10.0
    - `bt-commons-compress-version` to 1.28.0
    - `bt-commons-io-version` to 2.20.0
    - `bt-commons-lang3-version` to 3.18.0
    - `bt-fastutil-version` to 8.5.16
    - `bt-jackson-version` to 2.19.2
    - `bt-log4j-version` to 2.25.1
    - `bt-opencsv-version` to 5.12.0
    - `bt-protobuf-version` to 4.31.1
    - `bt-woodstox-version` to 7.1.1
    - `dependency-track-maven.version` to 1.10.2
    - `exec-maven-plugin.version` to 3.5.1
    - `maven-clean-plugin.version` to 3.5.0
    - `maven-enforcer-plugin.version` to 3.6.1
    - `maven-gpg-plugin.version` to 3.2.8
    - `maven-pmd-plugin.version` to 3.27.0

# 23.0.1

## [COMN-396](https://babelstreet.atlassian.net/browse/COMN-396)

- Update properties:
    - `bt-adm-version` to 3.0.6
    - `bt-common-api-version` to 38.0.6

# 23.0.0

## [COMN-363](https://babelstreet.atlassian.net/browse/COMN-363)

- Remove `internal-release` profile
- Remove properties:
    - `nexus-staging-plugin-internal-nexus-url`
    - `nexus-staging-plugin-internal-server-id`

## [COMN-381](https://babelstreet.atlassian.net/browse/COMN-381)

- Remove `org.owasp:dependency-check-maven` plugin

## [COMN-396](https://babelstreet.atlassian.net/browse/COMN-396)

- Update properties:
    - `bt-adm-version` to 3.0.4
    - `bt-common-api-version` to 38.0.4
    - `bt-checkstyle-version` to 10.23.1
    - `bt-commons-io-version` to 2.19.0
    - `bt-guava-version` to 33.4.8-jre
    - `bt-jackson-version` to 2.19.0
    - `bt-opencsv-version` to 5.11
    - `bt-protobuf-version` to 4.30.2
    - `bt-snakeyaml-version` to 2.4
    - `dependency-track-maven.version` to 1.10.0
    - `jacoco-maven-plugin.version` to 0.8.13
    - `maven-clean-plugin.version` to 3.4.1
    - `maven-compiler-plugin.version` to 3.14.0
    - `maven-deploy-plugin.version` to 3.1.4
    - `maven-install-plugin.version` to 3.1.4
    - `maven-project-info-reports-plugin.version` to 3.9.0
    - `maven-surefire-plugin.version` to 3.5.3
- Update references of Basis Technology to Babel Street Rosette

# 22.0.0

## [COMN-363](https://babelstreet.atlassian.net/browse/COMN-363)

- Update properties:
    - `bt-checkstyle-version` to 10.21.2
    - `bt-commons-io-version` to 2.18.0
    - `bt-guava-version` to 33.4.0-jre
    - `bt-jackson-version` to 2.18.2
    - `bt-log4j-version` to 2.24.3
    - `bt-opencsv-version` to 5.10
    - `bt-protobuf-version` to 4.29.3
    - `buildtools.version` to 7.0.1
    - `cyclonedx-maven-plugin.version` to 2.9.1
    - `dependency-check-maven.version` to 12.0.2
    - `dependency-track-maven.version` to 1.9.1
    - `maven-javadoc-plugin.version` to 3.11.2
    - `maven-pmd-plugin.version` to 3.26.0
    - `maven-surefire-plugin.version` to 3.5.2

# 21.0.0

## [COMN-341](https://babelstreet.atlassian.net/browse/COMN-341)

- Update properties:
    - `bt-adm-version` to 3.0.3
    - `bt-common-api-version` to 38.0.3

## [COMN-342](https://babelstreet.atlassian.net/browse/COMN-342)

- Rename property `bt.compile.release` to `bt.compile.target`
- Reintroduce property `bt.compile.source` at 21
- Update `maven-enforcer-plugin` to require Java version 21

# 20.0.0

## [COMN-318](https://babelstreet.atlassian.net/browse/COMN-318)

- Add property:
    - `bt-tensorflow-version` at 1.0.0-rc.1
- Update many properties, including:
    - `bt-adm-version` to 3.0.2
    - `bt-common-api-version` to 38.0.2

# 19.0.0

## [COMN-314](https://babelstreet.atlassian.net/browse/COMN-314)

- Remove dependency:
    - `org.rauschig:jarchivelib`
- Remove properties:
    - `bt-jarchivelib-version`
    - `bt-metrics-version`
    - `bt-wagon-ssh-version`
- Replace dependency:
    - `org.codehaus.woodstox:woodstox-core-asl` with `com.fasterxml.woodstox:woodstox-core`
- Update properties:
    - `bt-adm-version` to 3.0.1
    - `bt-args4j-version` to 2.37
    - `bt-checkstyle-version` to 10.16.0
    - `bt-common-api-version` to 38.0.1
    - `bt-commons-cli-version` to 1.7.0
    - `bt-commons-compress-version` to 1.26.1
    - `bt-commons-io-version` to 2.16.1
    - `bt-guava-version` to 33.2.0-jre
    - `bt-jackson-version` to 2.17.1
    - `bt-log4j-version` to 2.23.1
    - `bt-protobuf-version` to 3.25.3
    - `bt-spotbugs-version` to 4.8.5
    - `bt-woodstox-version` to 6.6.2
    - `cyclonedx-maven-plugin.version` to 2.8.0
    - `dependency-check-maven.version` to 9.1.0
    - `jacoco-maven-plugin.version` to 0.8.12
    - `maven-assembly-plugin.version` to 3.7.1
    - `maven-compiler-plugin.version` to 3.13.0
    - `maven-deploy-plugin.version` to 3.1.2
    - `maven-gpg-plugin.version` to 3.2.4
    - `maven-install-plugin.version` to 3.1.2
    - `maven-invoker-plugin.version` to 3.6.1
    - `maven-jar-plugin.version` to 3.4.1
    - `maven-pmd-plugin.version` to 3.22.0
    - `maven-scm-plugin.version` to 2.1.0
    - `maven-shade-plugin.version` to 3.5.3
    - `maven-source-plugin.version` to 3.3.1
    - `spotbugs-maven-plugin.version` to 4.8.5.0

# 18.0.0

## [COMN-303](https://babelstreet.atlassian.net/browse/COMN-303)

- Update properties:
    - `bt-adm-version` to 3.0.0
    - `bt-common-api-version` to 38.0.0
    - `bt-commons-compress-version` to 1.26.0
    - `bt-commons-io-version` to 2.15.1
    - `bt-commons-lang3-version` to 3.14.0
    - `bt-fastutil-version` to 8.5.13
    - `bt-guava-version` to 33.0.0-jre
    - `bt-icu4j-version` to 74.2
    - `bt-jackson-version` to 2.16.1
    - `bt-opencsv-version` to 5.9
    - `bt-spotbugs-version` to 4.8.3
    - `cyclonedx-maven-plugin.version` to 2.7.11
    - `exec-maven-plugin.version` to 3.2.0
    - `maven-compiler-plugin.version` to 3.12.1
    - `maven-javadoc-plugin.version` to 3.6.3
    - `maven-pmd-plugin.version` to 3.21.2
    - `maven-project-info-reports-plugin.version` to 3.5.0
    - `maven-shade-plugin.version` to 3.5.2
    - `maven-site-plugin.version` to 4.0.0-M13
    - `maven-surefire-plugin.version` to 3.2.5
    - `spotbugs-maven-plugin.version` to 4.8.3.1
    - `versions-maven-plugin.version` to 2.16.2


## [COMN-305](https://babelstreet.atlassian.net/browse/COMN-305)

- Add property:
    - `bt-commons-cli-version` at 1.6.0
- Add dependency:
    - `commons-cli:commons-cli`

## [COMN-311](https://babelstreet.atlassian.net/browse/COMN-311)

- Remove properties:
    - `bnd-maven-plugin.version`
    - `bt-custom-httpclient-osgi-version`
    - `maven-bundle-plugin.version`
- Remove plugin configurations:
    - `biz.aQute.bnd:bnd-maven-plugin`
    - `org.apache.felix:maven-bundle-plugin`
- Remove dependencies:
    - `com.basistech.org.apache.httpcomponents:httpclient-osgi`
    - `org.apache.httpcomponents:httpasyncclient-osgi`
    - `org.apache.httpcomponents:httpcore-osgi`

# 17.0.0

## [COMN-302](https://babelstreet.atlassian.net/browse/COMN-302)

- Add properties:
    - `bt-spotbugs-version` at 4.8.1
    - `maven-invoker-plugin.version` at 3.6.0
    - `spotbugs-maven-plugin.version` at 4.8.1.0
    - `versions-maven-plugin.version` at 2.16.1
- Rename properties:
    - `maven-enforcer-plugin-version` to `maven-enforcer-plugin.version`
    - `maven-scm-plugin.version` to `maven-scm-publish-plugin.version`
    - `maven.scm.version` to `maven-scm-plugin.version`
    - `nexus-staging-plugin-version` to `nexus-staging-maven-plugin.version`
    - `wagon-ssh.version` to `bt-wagon-ssh-version`
- Update plugins:
    - `bnd-maven-plugin` to 7.0.0 from 6.4.0
    - `cyclonedx-maven-plugin` to 2.7.10 from 2.7.9
    - `dependency-check-maven` to 8.4.2 from 8.3.1
    - `dependency-track-maven-plugin` to 1.7.0 from 1.6.0
    - `jacoco-maven-plugin` to 0.8.11 from 0.8.10
    - `maven-checkstyle-plugin` to 3.3.1 from 3.3.0
    - `maven-clean-plugin` to 3.3.2 from 3.3.1
    - `maven-dependency-plugin` to 3.6.1 from 3.6.0
    - `maven-enforcer-plugin` to 3.4.1 from 3.3.0
    - `maven-javadoc-plugin` to 3.6.0 from 3.5.0
    - `maven-shade-plugin` to 3.5.1 from 3.5.0
    - `maven-site-plugin` to 4.0.0-M11 from 4.0.0-M9
    - `maven-surefire-plugin` to 3.2.1 from 3.1.2
- Update internal dependencies:
    - `bt-adm-version` to 2.10.0 from 2.9.0
    - `bt-common-api-version` to 37.5.5 from 37.5.4
- Update external dependencies:
    - `bt-checkstyle-version` to 10.12.4 from 10.12.2
    - `bt-commons-compress-version` to 1.24.0 from 1.23.0
    - `bt-commons-io-version` to 2.15.0 from 2.11.0
    - `bt-guava-version` to 32.1.3-jre from 32.1.2-jre
    - `bt-jackson-version` to 2.15.3 from 2.15.2
    - `bt-liblinear-version` to 2.44 from 2.30
    - `bt-log4j-version` to 2.21.1 from 2.20.0
    - `bt-metrics-version` to 4.2.21 from 4.2.19
    - `bt-protobuf-version` to 3.25.0 from 3.23.4
    - `bt-snakeyaml-version` to 2.2 from 2.0
    - `bt-stax2-api-version` to 4.2.2 from 4.2.1

# 16.0.0

- Upgrade many dependency versions
- Upgrade many plugin versions
- Add a new property (`bt-checkstyle-version`) to specify the version of
  Checkstyle `maven-checkstyle-plugin` uses

# 15.0.0
- Upgrade many dependency versions
- Upgrade many plugin versions; including `maven-release-plugin`.
- Upgrade to 7.0.0 of `com.basistech:open-source-buildtools` to pick up PMD deprecation fixes.
- Fix checkstyle plugin configuration:  Use `inputEncoding` instead of `encoding`.
- Fix checkstyle plugin configuration:  `linkXRef` not applicable for `check` goal.
- Fix pmd plugin configuration:  Use `inputEncoding` instead of `sourceEncoding`.
- Change organization url to rosette.com

# 14.0.0

## [WS-2698](https://babelstreet.atlassian.net/browse/WS-2698)
- Add dependency on custom `com.basistech.org.apache.httpcomponents`
- Add new property `bt-custom-httpclient-osgi-version` for the custom artifact

# 13.0.0

## [COMN-297](https://babelstreet.atlassian.net/browse/COMN-297)
- Add dependency on `org.cyclonedx:cyclonedx-maven-plugin` version 2.7.4
- Add dependency on `io.github.pmckeown:dependency-track-maven-plugin` version 1.4.0
- Update `bt-guava-version` to 31.1-jre from 26.0-jre
- Update `bt-protobuf-version` to 3.21.7 from 3.12.2

# 12.0.0

## [COMN-286](https://babelstreet.atlassian.net/browse/COMN-286)
- Update `bt-snakeyaml-version` to 1.33 from 1.30

## [COMN-287](https://babelstreet.atlassian.net/browse/COMN-287)
- Update lots of plugins and dependencies

# 11.0.0

## [COMN-284](https://babelstreet.atlassian.net/browse/COMN-284)
- Update `nexus-staging-plugin-version` to 1.6.12 from 1.6.8
- Update `bt-common-api-version` to 37.5.0 from 37.4.0

## [COMN-282](https://babelstreet.atlassian.net/browse/COMN-282)
- Update `maven-enforcer-plugin` to require Java version 17
- Add new property `bt.compile.release` to target Java version 11
- Remove redundant properties `bt.compile.source`, `bt.compile.target`, `bt.java.source`, and `bt.java.target`

# 10.0.0

## [COMN-279](https://babelstreet.atlassian.net/browse/COMN-279)
- Update `bt-log4j-version` to 2.17.1 from 1.2.17
- Change Log4j dependencies from `log4j:log4j` to
  `org.apache.logging.log4j:log4j-api`,
  `org.apache.logging.log4j:log4j-core`, and
  `org.apache.logging.log4j:log4j-slf4j-impl`
- Remove `org.slf4j:slf4j-log4j12` dependency

## [COMN-280](https://babelstreet.atlassian.net/browse/COMN-280)
- Update lots of plugins and dependencies
- Change Apache Commons Lang dependency from `commons-lang:commons-lang` to
  `org.apache.commons:commons-lang3`
- Add dependency on `org.slf4j:log4j-over-slf4j` version 1.7.32

## [ROS-327](https://babelstreet.atlassian.net/browse/ROS-327)
- Add a dependency on `org.apache.commons:commons-compress` version 1.21

# 9.0.0

## [COMN-274](https://babelstreet.atlassian.net/browse/COMN-274):
- Update `dependency-check-maven.version` to 6.1.6 from 6.0.5

## [COMN-276](https://babelstreet.atlassian.net/browse/COMN-276):
- Update `bt-common-api-version` to 37.3.0 from 37.2.0

# 8.1.0 #

## [COMN-273](https://babelstreet.atlassian.net/browse/COMN-273):
- Update `bt-common-api-version` to 37.2.0 from 37.1.0

# 8.0.0 #

## [COMN-271](https://babelstreet.atlassian.net/browse/COMN-271):
- Update `bt-common-api-version` to 37.1.0 from 37.0.1

# 7.0.1 #
## [COMN-268](https://babelstreet.atlassian.net/browse/COMN-268):
- downgrade maven-release-plugin to 2.5.3 for MRELEASE-1042

# 7.0.0 #
## [COMN-268](https://babelstreet.atlassian.net/browse/COMN-268):
- update dependency-check; remove execution

# 5.3.0 #
## [ROS-321](https://babelstreet.atlassian.net/browse/ROS-321):
- integrate Sonarqube
