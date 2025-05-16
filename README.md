## open-source-parent

A POM with some common settings for Babel Street Rosette open source
components.

## Release Instructions

#### Maven Central
```
mvn --batch-mode \
    --activate-profiles release \
    release:prepare \
    release:perform \
    -Darguments=-Dgpg.passphrase=MY_PASSPHRASE
```

#### Internal Only
TBD
