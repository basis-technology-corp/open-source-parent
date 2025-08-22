# Open-Source Parent POM

A POM with some common settings for Babel Street Rosette open source
components.

## Release Instructions

1. [Generate a user token](https://central.sonatype.org/publish/generate-portal-token/)
2. Add that token to your Maven `settings.xml`
3. Run `mvn release:prepare && mvn release:perform`

