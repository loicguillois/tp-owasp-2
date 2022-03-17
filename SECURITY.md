# Security Policy

## Supported Versions

Use this section to tell people about which versions of your project are
currently being supported with security updates.

| Version | Supported          |
| ------- | ------------------ |
| 2.0.x   | secure             |
| < 2.0   | not secure         |

## Reporting a Vulnerability

To report a vulnerability you should audit packages used in the package.json file

There are many way to report a vulnerability. 

You could use `npm audit` or `yarn audit` to get an exausted list of vulnerabilities.

To ensure that the packages used doesn't have any vulnerabilities, the best way is to set up a GitHub action or GitLab job to trigger a pipeline every time a commit is pushed.
You could also use a third party option with for example : `Snyk`
