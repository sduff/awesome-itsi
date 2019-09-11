# Awesome ITSI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome resourcesi for Splunk IT Service Intelligence.

## Contents

- [Basics](#basics)
- [Education and Training](#education-and-training)
- [Modules](#modules)
- [3rd Party Modules](#3rd-party-modules)
- [Notable Event Aggregation Policy](#notable-event-aggregation-policy)
- [Integrations](#integrations)
- [.Conf Presentations](#conf-presentations)

## Basics

Basic resources for getting started with Splunk IT Service Intelligence.

- [Splunk Website](https://splunk.com)
  - [Downloads](https://www.splunk.com/download)
- [Splunk ITSI](https://www.splunk.com/en_us/software/it-service-intelligence.html)
  - [Splunkbase Entry](https://splunkbase.splunk.com/app/1841/) - Download page for licensed users.
  - [Documentation](https://docs.splunk.com/Documentation/ITSI/latest)
  - [Splunk Blog ITSI Posts](https://www.splunk.com/blog/tag/splunk-itsi.html)

## Education and Training
- Training Classes
  - [Using IT Service Intelligence](https://www.splunk.com/en_us/training/courses/using-splunk-it-service-intelligence.html)
  - [Implementing IT Service Intelligence](https://www.splunk.com/en_us/training/courses/implementing-splunk-it-service-intelligence.html)
- Certifications
  - [Splunk ITSI Certified Admin](https://www.splunk.com/en_us/training/certification-track/splunk-itsi-certified-admin.html)
  - [Splunk ITSI Admin Blueprint](https://www.splunk.com/content/dam/splunk2/pdfs/training/Splunk-Test-Blueprint-ITSI-Admin-v1.1.pdf) - A guide to the examinable material in the ITSI Admin certification.

## Modules

### ITSI Module for Application Performance Monitoring

The Module for Application Performance Monitoring (APM) does not ship with ITSI
by default. It can be [downloaded from
Splunkbase](https://splunkbase.splunk.com/app/3664/). If you are using ITSI on
Splunk Cloud, request it to be installed from Splunk Cloud Ops.

#### Support Add-Ons
- [Splunk Add-on for New Relic](https://splunkbase.splunk.com/app/3465)
- [Splunk Add-on for AppDynamics](https://splunkbase.splunk.com/app/3471)

### Application Server Module
#### Support Add-Ons
- [Splunk Add-on for Tomcat](https://splunkbase.splunk.com/app/2911/)
- [Splunk Add-on for IBM WebSphere Application Server](https://splunkbase.splunk.com/app/2789/)

### Splunk ITSI Module for Continuous Delivery The Module for Continuous

Delivery does not shop with ITSI by default. It can be [downloaded from
Splunkbase](https://splunkbase.splunk.com/app/3439/). If you are using ITSI on
Splunk Cloud, request it to be installed from Splunk Cloud Ops.

#### Support Add-Ons
- [Splunk Add-on for Bamboo](https://splunkbase.splunk.com/app/3440/)
- [Splunk Add-on for JIRA](https://splunkbase.splunk.com/app/1438/)
- [Splunk App for Jenkins](https://splunkbase.splunk.com/app/3332/)
- [Splunk Plugin for Jenkins](https://wiki.jenkins-ci.org/display/JENKINS/Splunk+Plugin+for+Jenkins)

### Database Module
#### Support Add-Ons
- [Splunk Add-on for Microsoft SQL Server](https://splunkbase.splunk.com/app/2648/)
- [Splunk Add-on for Oracle Database](https://splunkbase.splunk.com/app/1910/)

### End User Experience Monitoring Module
#### Support Add-Ons
- [Splunk Add-on for MINT](https://splunkbase.splunk.com/app/3309/)

### Load Balancer Module
#### Support Add-Ons
- [Splunk Add-on for F5 Big-IP](https://splunkbase.splunk.com/app/2680/)
- [Splunk Add-on for Citrix Netscaler](https://splunkbase.splunk.com/app/2770/)

### Operating System Module
#### Support Add-Ons
- [Splunk Add-on for Unix and Linux](https://splunkbase.splunk.com/app/833/)
- [Splunk Add-on for Microsoft Window](https://splunkbase.splunk.com/app/742/)

### Storage Module
#### Support Add-Ons
- [Splunk Add-on for NetApp Data ONTAP](https://splunkbase.splunk.com/app/3418/)
- [Splunk Add-on for EMC VNX](https://splunkbase.splunk.com/app/1836/)

### Virtualization Module
#### Support Add-Ons
- [Splunk Add-on for Microsoft Hyper-V](https://splunkbase.splunk.com/app/1253/)
- [Splunk Add-on for VMware](https://splunkbase.splunk.com/app/3215/)

### Web Server Module
#### Support Add-Ons
- [Splunk Add-on for Apache Web Server](https://splunkbase.splunk.com/app/3186/)
- [Splunk Add-on for Microsoft IIS](https://splunkbase.splunk.com/app/3185/)

## 3rd Party Modules

### ITSI Module for Open Banking

*This Module is a framework, and requires significant customization by the Developer for use.*

The [ITSI Module for Open Banking](https://splunkbase.splunk.com/app/4485/)
provides an ITSI Service Hierarchy and KPIs to monitor Open
Banking APIs.

### ITSI module for Nmon Metricator

The [ITSI Module for Nmon Metricator](https://splunkbase.splunk.com/app/4123/)
packages the [`nmon`](http://nmon.sourceforge.net/pmwiki.php) utility to
generate performance and inventory data for AIX, Linux and Solaris servers.

#### Support Add-Ons
- [Nmon Technology Add-On](https://splunkbase.splunk.com/app/3948/)
- [Nmon Technology Add-On - HEC Version](https://splunkbase.splunk.com/app/4022/)

### Splunk ITSI Module for Puppet Enterprise

The [Splunk ITSI Module for Puppet
Enterprise](https://splunkbase.splunk.com/app/3716)/ utilizes the Notable
Events and Action Framework, to trigger Puppet Orchestrator to perform
pre-defined tasks on select services.

## Notable Event Aggregation Policy
- A Blueprint for Splunk ITSI Alerting
  - [Overview](https://www.splunk.com/blog/2019/01/10/a-blueprint-for-splunk-itsi-alerting-overview.html)
  - [Part 1](https://www.splunk.com/blog/2019/01/18/a-blueprint-for-splunk-itsi-alerting-step-1.html)
  - [Part 2](https://www.splunk.com/blog/2019/02/01/a-blueprint-for-splunk-itsi-alerting-step-2.html)
  - [Part 3](https://www.splunk.com/blog/2019/02/08/a-blueprint-for-splunk-itsi-alerting-step-3.html) 
  - [Part 4](https://www.splunk.com/blog/2019/02/14/a-blueprint-for-splunk-itsi-alerting-step-4.html)
  - [Part 5](https://www.splunk.com/blog/2019/02/22/a-blueprint-for-splunk-itsi-alerting-step-5.html)

## Integrations
- Phantom
  - [Awesome Phantom](https://github.com/ryanplasma/awesome-splunk-phantom)
- VictorOps

## .Conf Presentations
- [ITSI .Conf Presentations](https://conf.splunk.com/watch/conf-online.html?search=ITSI#/)

## Contribute
Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License
[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Simon Duff has waived all copyright and
related or neighboring rights to this work.
