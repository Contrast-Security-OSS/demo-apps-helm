# Introduction

Terracotta Bank is an intentionally-vulnerable web application, useful for practicing detection, exploitation, and mitigation of common web application security vulnerabilities.

## Configuration

The Contrast Demo environment makes use of the Kubernetes Agent Operator to automatically instrument this application for vulnerability detection (IAST) or runtime protection (RASP). 
All you need to provide is:

* Name - this is the deployment name so needs to be unique
* Contrast Application Name - this will be used for the application name in the Contrast UI
* Environment - this should be set to Development, QA or Production
* Server Name - this is optional, if not specified the container id will be used