# Pudica Parent POM

![MIT License](https://img.shields.io/github/license/jycchoi/pudica-parent.svg)
![Maven Central](https://img.shields.io/maven-central/v/org.pudica/pudica-parent.svg)

This project is licensed under the terms of the MIT license.

This project configures the versions of the following plugins to allow
reproducible builds.
The plugins are listing according to the usual invoked build phase.

- clean
    - maven-clean-plugin
- validate
    - maven-enforcer-plugin
    - maven-toolchains-plugin
- generate-sources
    - maven-plugin-plugin
    - maven-jxr-plugin
- process-sources
    - maven-dependency-plugin
- process-resources
    - maven-resources-plugin
- compile
    - maven-antrun-plugin
    - maven-compiler-plugin
- test
    - maven-surefire-plugin
- package
    - maven-jar-plugin
    - maven-war-plugin
    - maven-ear-plugin
    - maven-shade-plugin
    - maven-source-plugin
    - maven-javadoc-plugin
    - maven-assembly-plugin
- integration-test
    - maven-failsafe-plugin
- verify
    - maven-checkstyle-plugin
    - maven-pmd-plugin
    - maven-jarsigner-plugin
    - maven-gpg-plugin
- install
    - maven-install-plugin
- deploy
    - maven-deploy-plugin
- release
    - maven-release-plugin
- site
    - maven-site-plugin
    - maven-surefire-report-plugin
    - maven-project-info-reports-plugin
