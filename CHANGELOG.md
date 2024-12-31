# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

<!-- Format restrictions - see https://common-changelog.org and https://keepachangelog.com/ for details -->
<!-- Each Release must start with a line for the release version of exactly this format: ## [version] -->
<!-- The subsequent comment lines start with a space - not to irritate the release scripts parser!
 ## [major.minor.micro]
 <empty line> - optional sub sections may follow like:
 ### Added:
 - This feature was added
 <empty line>
 ### Changed:
 - This feature was changed
 <empty line>
 ### Removed:
 - This feature was removed
 <empty line>
 ### Fixed:
 - This issue was fixed
 <empty line>
 <empty line> - next line is the starting of the previous release
 ## [major.minor.micro]
 <empty line>
 <...>
 !!! In addition the compare URL links are to be maintained at the end of this CHANGELOG.md as follows.
     These links provide direct access to the GitHub compare vs. the previous release.
     The particular link of a released version will be copied to the release notes of a release accordingly.
     At the end of this file appropriate compare links have to be maintained for each release version in format:
 
  +-current release version
  |
  |                   +-URL to this repo                   previous release version tag-+       +-current release version tag
  |                   |                                                                 |       |
 [major.minor.micro]: https://github.com/mavenplugins/parent-base-maven-plugins/compare/vM.N.u..vM.N.u
-->
<!--
## [Unreleased]

### 🚨 Removed
- TBD

### 💥 Breaking
- TBD

### 📢 Deprecated
- TBD

### 🚀 New Features
- TBD

### 🐛 Fixes
- TBD

### ✨ Improvements
- TBD

### 🔧 Internal Changes
- TBD

### 🚦 Tests
- TBD

### 📦 Updates
- TBD

### 🔒 Security
- TBD

### 📝 Documentation Updates
- TBD
-->

## [Unreleased]
<!-- !!! Align version in badge URLs as well !!! -->
[![4 Badge](https://img.shields.io/nexus/r/io.github.mavenplugins/parent-base-maven-plugins?server=https://s01.oss.sonatype.org&label=Maven%20Central&queryOpt=:v=4)](https://central.sonatype.com/artifact/io.github.mavenplugins/parent-base-maven-plugins/4)

### Summary
- TBD

### 📦 Updates
- TBD

### 📝 Usage
- For details on usage please have a look to the comments in [pom.xml](pom.xml)
- Use as parent pom:
  ```
  <parent>
    <groupId>io.github.mavenplugins</groupId>
    <artifactId>parent-base-maven-plugins</artifactId>
    <version>4</version>
  </parent>
  ```


## [3]
<!-- !!! Align version in badge URLs as well !!! -->
[![3 Badge](https://img.shields.io/nexus/r/io.github.mavenplugins/parent-base-maven-plugins?server=https://s01.oss.sonatype.org&label=Maven%20Central&queryOpt=:v=3)](https://central.sonatype.com/artifact/io.github.mavenplugins/parent-base-maven-plugins/3)

### Summary
- Refer to parent pom version `io.github.mavenplugins:org-parent:10`

### 🔒 Security
- Update reference to parent pom version `io.github.mavenplugins:org-parent:10`

### 📝 Usage
- For details on usage please have a look to the comments in [pom.xml](pom.xml)
- Use as parent pom:
  ```
  <parent>
    <groupId>io.github.mavenplugins</groupId>
    <artifactId>parent-base-maven-plugins</artifactId>
    <version>3</version>
  </parent>
  ```


## [2]
<!-- !!! Align version in badge URLs as well !!! -->
[![2 Badge](https://img.shields.io/nexus/r/io.github.mavenplugins/parent-base-maven-plugins?server=https://s01.oss.sonatype.org&label=Maven%20Central&queryOpt=:v=2)](https://central.sonatype.com/artifact/io.github.mavenplugins/parent-base-maven-plugins/2)

### Summary
- Initial release maintained within GitHub mavenplugins organization
- Moved and updated from `de.mhoffrogge.maven:parent-base-maven-plugins:1` at [parent-base-maven-plugins on GitLab](https://gitlab.com/mhopen/maven-plugins/-/tree/master/parent-base-maven-plugins?ref_type=heads)

### 📦 Updates
- Inherit from `io.github.mavenplugins:org-parent`
- Maven groupId changed to `io.github.mavenplugins`
- Bump `<version.maven>3.8.1</version.maven>`
- Bump `<version.maven-invoker>3.1.0</version.maven-invoker>`
- Bump `<version.maven-plugin-plugin>3.13.1</version.maven-plugin-plugin>`
- Bump `<version.plexus-component-metadata>2.2.0</version.plexus-component-metadata>`
- Bump `<version.versions-maven-plugin>2.15.0</version.versions-maven-plugin>`
- Bump `<version.plexus-interactivity-api>1.3</version.plexus-interactivity-api>`
- Bump `<version.commons-text>1.11.0</version.commons-text>`
- Bump `<version.commons-lang3>3.14.0</version.commons-lang3>`
- Bump `<version.commons-io>2.16.1</version.commons-io>`
- Bump `<version.junit>4.13.2</version.junit>`

### 📝 Usage
- For details on usage please have a look to the comments in [pom.xml](pom.xml)
- Use as parent pom:
  ```
  <parent>
    <groupId>io.github.mavenplugins</groupId>
    <artifactId>parent-base-maven-plugins</artifactId>
    <version>2</version>
  </parent>
  ```


<!--
## []

### NeverReleased
- This is just a dummy placeholder to make the parser of GHCICD/release-notes-from-changelog@v1 happy!
-->

[Unreleased]: https://github.com/mavenplugins/parent-base-maven-plugins/compare/v3..HEAD
[3]: https://github.com/mavenplugins/parent-base-maven-plugins/compare/v2..v3
[2]: https://github.com/mavenplugins/parent-base-maven-plugins/releases/tag/v2
