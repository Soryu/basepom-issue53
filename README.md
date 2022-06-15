# basepom-issue53

Demo project for https://github.com/basepom/basepom/issues/53

It's a multi-stage parent pom setup.

1. `base/` contains main-pom which uses basepom-minimal as parent
2. `service/` contains service-pom which uses main-pom as parent
3. finally, `demo/` contains a generated spring starter app that does nothing, based on service-pom

When using IntelliJ Idea to open the demo project and trying to execute the test or tests, it fails on my machine as described in the linked issue.
