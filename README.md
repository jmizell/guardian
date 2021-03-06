# Guardian Web Application Firewall
[![CircleCI](https://circleci.com/gh/asalih/guardian.svg?style=shield)](https://circleci.com/gh/asalih/guardian)
[![Go Report Card](https://goreportcard.com/badge/github.com/asalih/guardian)](https://goreportcard.com/report/github.com/asalih/guardian)

Guardian is the open source web application firewall based on ModSecurity SecRule format.

# How it works!
Guardian locates in front of your web server and if incoming traffic valid then the Guardian passes it to the target server.

![Diagram](images/guardian.png)

## Guardian Nameserver
[Guardian Nameserver](https://github.com/asalih/guardian_ns) To route web traffic through the Guardian, update the nameservers at your domain registrar to resolve your domain’s DNS with Guardian's nameservers.

## Guardian Dashboard
[Guardian Dashboard](https://github.com/asalih/GuardianUI) To managing your rules and domains.

## TODO
-   General improvements & better testing
-   Add Dockerfile
-   Usecase