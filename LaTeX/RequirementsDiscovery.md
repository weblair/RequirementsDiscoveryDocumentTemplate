# Definition of Done (DOD)

## Project Objectives

### Purpose
I want to separate service configuration from service code in a central,
dynamic, and secure way.

I have considered these existing products:
    - Git
    - Ansible
    - Terraform

With these products, however, I am unable to:
    - Maintain separation of concerns between code, infrastructure, and
      configuration,
    - Centrally change and track configuration without a complete
      rebuild/redeploy of the service, or
    - Keep somewhat sensitive configuration settings separate from code or
      infrastructure repositories (NOTE: highly sensitive settings should be
      stored in AWS Secrets Manager anyway and *not* in the config).

In order to achieve my objective(s), I need the following solution(s):
    - A central server that services can query on startup to receive their
      configurations,
    - A tool for easily versioning and updating service configurations

### Principles
I want this project to add value by:
    - Giving developers and system administrators a simple and elegant way to
      configure their deployed services,
    - 

I do *not* want this project to become:
    - A secrets manager,
    - An excessive burden on developers or systems administrators,

## Victory Conditions
When this project is finished, it will be possible to:
    - <goal>

# User Stories
1. As a <type of user>, I want <some goal> so that <some reason>.
