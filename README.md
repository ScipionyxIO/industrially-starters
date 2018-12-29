# Scipionyx Starters

[![Build Status](https://travis-ci.com/ScipionyxIO/industrially-starters.svg?branch=master)](https://travis-ci.com/ScipionyxIO/industrially-starters)
[![CodeFactor](https://www.codefactor.io/repository/github/scipionyxio/industrially-starters/badge)](https://www.codefactor.io/repository/github/scipionyxio/industrially-starters)

![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=scipionyx-io-industrially-starters&metric=vulnerabilities)
![Bugs](https://sonarcloud.io/api/project_badges/measure?project=scipionyx-io-industrially-starters&metric=bugs)
![CodeSmells](https://sonarcloud.io/api/project_badges/measure?project=scipionyx-io-industrially-starters&metric=code_smells)

![Bugs](https://sonarcloud.io/api/project_badges/quality_gate?project=scipionyx-io-industrially-starters)

## Deployment and CI/CD Pipelines

### Projects
#### Node Parent
This parent POM should be utilized by any new project.

### Instructions
#### Phases
The following phases are available from the Gitlab CI/CD menus:
#### Deploy
Automatically triggered whenever a version is committed to GitLab.
The *phase* will run maven's deploy in order to: install, test and deploy the app. 
https://issues.sonatype.org/browse/OSSRH-44915?filter=-2
https://central.sonatype.org/pages/apache-maven.html

#### Release
#### Create Branch
Convenient Phase allowing creating new branches for the development of new version.

