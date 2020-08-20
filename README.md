# CI/CD as Code Demo

Shows a few examples of running the same basic workflow through multiple different CI/CD tools.

* AppVeyor - appveyor.yml
* Gitlab CI - .gitlab-ci.yml
* Github Actions - .github/workflows/main.yml
* Jenkins (scripted) - deploy.jenkinsfile
* Jenkins (declarative) - multibranch.jenkinsfile

## Basic Automation Pipeline

* Install npm dependencies
* Run linter
* Run test suite
* Run application build
* Deploy application (mocked)