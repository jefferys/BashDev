# BashDev Development RoadMap

Schedule of what might go into the project going forward. Very rough and no commitment is promised!

#### 0.0.0.1 - Minimal bashdev application bootstrap

* Minimal install as manual instructions for Linux-aware developer
* `bashdev --version/-v`
    + hard-coded CLI option - convert to declarative option later
* `bashdev --help/-h/-?`
    + hard-coded CLI option - convert to declarative option later
* validate a directory is a bash-dev project
    + has `.bashdev.proj` file
* `bashdev project <name>`
    + hard-coded argument/command parsing - convert to declarative later
    + creates project (directory) and main script when it does not exist
    + change to project (directory) name when it does exist, verify
    + recognizes when already in a bashdev directory (verify)

#### 0.0.0.2 - Minimal bashdev testing

* Add `test.sh` to run shellspec tests
* Add tests that run with `test.sh` to self-test bashdev
* `bashdev test --self`
    + hard coded command parsed to run self test

#### 0.0.0.3 - Projects with tests

* bashdev add test shellspec
    + hard coded command to add support to a project for testing with shellspec
    + verify shellspec installed
    + add `test.sh` that supports shellspec to a project
    + add dummy test

#### 0.0.0.4 - Minimal module usage by bashdev

#### 0.0.0.5 - Projects with modules

#### 0.0.0.6 - Projects with git

#### 0.0.0.7 - Minimal usage of a settings system by bashdev

#### 0.0.0.8 - Projects with settings

#### 0.0.0.9 - Release testing

### 0.0.1 - Minimal useful tool

### 0.0.2 - Projects with Additional Developer infrastructure

* Roadmap
* Github
* Docker
* DockerHub
* CI
* Bug tracking

### 0.0.3 - Projects use a declarative CLI

### 0.0.4 - Projects with advanced settings

### 0.0.5 - Projects with modular commands

## 0.1 - First advertised version

# Proposed features and changes

## Accepted but not scheduled

## Considering but not accepted

## Rejected
