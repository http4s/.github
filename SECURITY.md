# Security Policy

## Supported Versions

We are currently providing security updates to the following http4s core versions: 

| Version | Supported          |
|---------|--------------------|
| 1.x     | :white_check_mark: |
| 0.23.x  | :white_check_mark: |
| 0.22.x  | :x:                |
| 0.21.x  | :x:                |
| 0.20.x  | :x:                |
| 0.19.x  | :x:                |
| 0.18.x  | :x:                |
| < 0.18  | :x:                |

For other repos in the http4s org on different release cycles, see their documentation.

## Reporting a Security Issue

To report a security issue, please use one of the following methods:

1. Navigate to the "Security and quality" tab at the top of the relevant repository, click the "Report a vulnerability" button, and complete the form as much as possible.
2. Email the [Security Team](#security-team) with a description of the issue, the steps you took to create the issue, affected versions, and, if known, mitigations for the issue.

The Security Team will attempt to respond within 3 working days of your report.  If the issue is confirmed as a vulnerability, we will open a Security Advisory.  This project follows a 90 day disclosure timeline.

## Procedure

1. A GitHub Security Advisory will be created in the appropriate repository.
2. A project member works privately with the reporter to resolve the vulnerability.
3. The project creates a new release of the package the vulnerabilty affects to deliver its fix.
4. The project publicly announces the vulnerability and describes how to apply the fix.

## Scala Steward

We strongly recommend users of our libraries to use [Scala Steward](https://github.com/scala-steward-org/scala-steward) or something similar to 
automatically receive updates.

### Security Maintainer list:

| name                                           | email               | PGP public key                                                                                                         |
|------------------------------------------------|---------------------|------------------------------------------------------------------------------------------------------------------------|
| [Ross A. Baker](https://github.com/rossabaker) | ross@rossabaker.com | [0x975BE5BC29D92CA5](https://keyserver.ubuntu.com/pks/lookup?op=get&search=0x904c153733dbb0106915c0bd975be5bc29d92ca5) |
| [Arman Bilge](https://github.com/armanbilge)   | arman@typelevel.org | [0xA335B107E9282548](https://keyserver.ubuntu.com/pks/lookup?op=get&search=0x1CAE49948EE0A2D7154A2B62A335B107E9282548) |
| [Erlend Hamnaberg](https://github.com/hamnis)  |                     |
||
