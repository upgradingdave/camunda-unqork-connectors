# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### TODO

#### Project Management
- [x] Discuss ownership and maintenance (Will move github over to unqork team as discussed on April 5)
- [x] Documentation? (Dave will create a first draft )
- [x] End-to-end demo? (We will focus technical and functional and webinar style later)
- [x] How to track project? Private Github issues? private gh issues (github issues should work for now)
- [x] Implement Unqork Workflow API for first version? Let's stick with modules submissions for first release. Workflow api will need some more thoughts around best practices 
- [x] What is Unqork release schedule? How often does the Module Submission API change? Doesn't change very frequently

#### Technical Tasks
- [x] Outbound connector - create module submission
- [x] Outbound connector - update module submission
- [x] Outbound connector - delete module submission
- [x] Outbound connector - get module submissions
- [x] Outbound connector - get module submission
- [x] Outbound connector - getBearerToken
- [x] Submit PR so backend supports `Content-Type: application/x-www-form-urlencoded` and grant_type=password&username=xxx&password=xxx
- [x] First version of Inbound webhook start connector
- [x] First version of Inbound webhook intermediate connector
- [ ] Better Unqork Logo?
- [ ] Switch to from using `local` to camunda version when PR is applied
- [ ] fix issue with create and update where data is not showing up in unqork
- [ ] create first version of user guide document
- [ ] (longer term) Polling intermediate connector
- [ ] (longer term) Add new authentication type to backend to accept username,password,grant_type
- [ ] (longer term) Update template generator to replace openapi syntax of `{moduleId}` with feel expression and corresponding input binding

## [1.0.0] - April 2024
### Added

- Updated HTTP Rest backend to support POSTing form data (application/x-www-form-urlencoded)
- Able to authenticate and get bearer token
- Able to get submissions
- Able to get submission
- Able to create module submission
- Able to update existing module submissions
- Able to delete module submissions
- First basic Inbound Webhook connector

### Fixed

- none

### Changed

- none

### Removed

- none