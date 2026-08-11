# spring-boot-maven-example

## Quality

<div align="center">

[![SonarQube Cloud](https://sonarcloud.io/images/project_badges/sonarcloud-light.svg)](https://sonarcloud.io/summary/new_code?id=io.github.pgatzka%3Aexample)

[![Quality gate status](https://sonarcloud.io/api/project_badges/measure?project=io.github.pgatzka%3Aexample&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=io.github.pgatzka%3Aexample)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=io.github.pgatzka%3Aexample&metric=bugs)](https://sonarcloud.io/summary/new_code?id=io.github.pgatzka%3Aexample)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=io.github.pgatzka%3Aexample&metric=code_smells)](https://sonarcloud.io/summary/new_code?id=io.github.pgatzka%3Aexample)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=io.github.pgatzka%3Aexample&metric=coverage)](https://sonarcloud.io/summary/new_code?id=io.github.pgatzka%3Aexample)
[![Duplicated Lines (%)](https://sonarcloud.io/api/project_badges/measure?project=io.github.pgatzka%3Aexample&metric=duplicated_lines_density)](https://sonarcloud.io/summary/new_code?id=io.github.pgatzka%3Aexample)
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=io.github.pgatzka%3Aexample&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=io.github.pgatzka%3Aexample)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=io.github.pgatzka%3Aexample&metric=reliability_rating)](https://sonarcloud.io/summary/new_code?id=io.github.pgatzka%3Aexample)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=io.github.pgatzka%3Aexample&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=io.github.pgatzka%3Aexample)
[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=io.github.pgatzka%3Aexample&metric=sqale_index)](https://sonarcloud.io/summary/new_code?id=io.github.pgatzka%3Aexample)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=io.github.pgatzka%3Aexample&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=io.github.pgatzka%3Aexample)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=io.github.pgatzka%3Aexample&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=io.github.pgatzka%3Aexample)
</div>

## Development

### Requirements

* Java 25 JDK
* Docker

### Setup

#### Spotless git hook for convenience

```shell
git config core.hooksPath .gitignore
```

## Using this template

### Update name

Find and replace `spring-boot-maven-example`

```shell
grep -R spring-boot-maven-example --exclude-dir=.git
```

### Update package

Find and replace `io.github.pgatzka.example`

```shell
grep -R io.github.pgatzka --exclude-dir=.git
```

### Update groupId

Find and replace `io.github.pgatzka`

```shell
grep -R io.github.pgatzka --exclude-dir=.git
```

### Update artifactId

Find and replace `example`

```shell
grep -R example --exclude-dir=.git
```

### Sonar scan

This repository uses sonar, if you don't want to use sonar for the project, remove the sonar part from ci.yaml or else
set the `SONAR_TOKEN` secret in GitHub

### Setup release

Create a GitHub application and set the repository action secrets

```
CLIENT_ID
APP_PRIVATE_KEY
```
