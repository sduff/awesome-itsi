# Awesome ITSI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome resources for Splunk IT Service Intelligence.

## Contents

- [Basics](#basics)
- [Education and Training](#education-and-training)
- [Professional Services](#professional-services)
- [Modules](#modules)
- [Content Packs](#content-packs)
- [Notable Event Aggregation Policy](#notable-event-aggregation-policy)
- [Integrations](#integrations)
- [.Conf Presentations](#conf-presentations)

## Basics

Resources for getting started with Splunk IT Service Intelligence.

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

## Professional Services

Need to get the experts involved in an ITSI implementation, or seeing guidance.

- [Splunk ITOA Professional Service Offerings](https://www.splunk.com/en_us/support-and-services/splunk-services/offerings/itoa-services.html)
- [Splunk Partners for ITSI Implementation](https://partners.splunk.com/locator/search?f0=Professional+Services+Specializations&f0v0=ITSI+Implementation)

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

The Splunk ITSI Module for Continuous Delivery does not shop with ITSI by
default. It can be [downloaded from
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

## Content Packs

ITSI currently still supports modules. Modules were introduced in version 2.0
as a way to deliver out-of-the-box content to customers. 

Like content packs, modules include KPI base searches, KPIs, and entity
auto-discovery searches, but not the other elements that content packs provide.
One key difference is that all module content is immutable, so you can't tailor
KPI base searches for maximum performance.

Due to the limitations of modules, the current best practice is to use the
content packs instead.

Further details on ITSI Content Packs can be found at [https://docs.splunk.com/Documentation/ITSICP/current/Config/About](https://docs.splunk.com/Documentation/ITSICP/current/Config/About) 

### Content Pack for Monitoring Microsoft Windows 

- [Content Pack for Monitoring Microsoft Windows Download](https://docs.splunk.com/Documentation/ITSICP/current/Config/ConfigWin#Install_the_content_pack)
- [Documentation](https://docs.splunk.com/Documentation/ITSICP/current/Config/AboutWin)

#### Support Add-Ons
- [Splunk Add-on for Microsoft Windows](https://splunkbase.splunk.com/app/742/)

### Content Pack for Monitoring Unix and Linux 

- [Content Pack for Monitoring Unix and Linux Download](https://docs.splunk.com/Documentation/ITSICP/current/Config/ConfigNix#Install_the_content_pack)
- [Documentation](https://docs.splunk.com/Documentation/ITSICP/current/Config/AboutNix)

#### Support Add-Ons
- [Splunk Add-on for Unix and Linux](https://splunkbase.splunk.com/app/833/)

### Splunk ITSI Content Pack for Shared IT Infrastructure Components

- [Content Pack for Shared IT Infrastructure Components Download](https://docs.splunk.com/Documentation/ITSICP/current/Config/ConfigShared#Install_the_content_pack)
- [Splunkbase Entry](https://splunkbase.splunk.com/app/4044/) - Alternate download site on Splunkbase.
- [Documentation](https://docs.splunk.com/Documentation/ITSICP/current/Config/AboutShared)

#### Support Add-Ons
- [Splunk Add-on for Microsoft Windows](https://splunkbase.splunk.com/app/742/)
- [Splunk Add-on for Unix and Linux](https://splunkbase.splunk.com/app/833/)

## Notable Event Aggregation Policy
- A Blueprint for Splunk ITSI Alerting - A Splunk blog series by Jeff Wiedemann on developing a blueprint for enterprise-wide alerting.
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
  - [Splunk Integration Guide - VictorOps](https://help.victorops.com/knowledge-base/splunk-integration-guide/) - The VictorOps and Splunk integration allow teams to schedule queries or alerts in Splunk to monitor system health. The VictorOps integration with Splunk can be leveraged to collect data about the overall release tool chain and deployment success to allow teams to collaborate around that information in the timeline.
  - [Create ticket in VictorOps - Splunk](https://docs.splunk.com/Documentation/ITSI/4.3.1/User/Setupandrunnotableeventactions#Create_a_ticket_in_VictorOps) - You can create an incident in a VictorOps incident management system for an (ITSI) episode.

## .Conf Presentations

Selected .conf presentations related to various aspects of ITSI.

- [All .Conf Presentations for 'ITSI'](https://conf.splunk.com/watch/conf-online.html?search.products=1518807815929006Tats#/)
- [Introduction to Splunk IT Service Intelligence](https://conf.splunk.com/files/2016/slides/introduction-to-splunk-it-service-intelligence.pdf) - .conf16.
- [Anatomy of a successful Splunk IT Service Intelligence Deployment](https://conf.splunk.com/files/2017/slides/automation-of-event-correlation-and-clustering-with-built-in-machine-learning-algorithms-in-splunk-it-service-intelligence-itsi.pdf) - .conf17.
- [Ready, Set, Go! Learn from others - The First 30 day Experiences of ITSI Customers](https://conf.splunk.com/files/2017/slides/ready-set-go-learn-from-others-the-first-30-day-experiences-of-itsi-customers.pdf) - .conf17.
- [The Splunk IT Service Intelligence (ITSI) Top 20 KPIs](https://conf.splunk.com/files/2017/slides/ready-set-go-learn-from-others-the-first-30-day-experiences-of-itsi-customers.pdf) - .conf17.
- [Faster Time to Value with ITSI Modules](https://conf.splunk.com/files/2016/slides/faster-time-to-value-with-itsi-modules.pdf) - .conf17.
- [Anatomy of a successful Event Analytics Deployment](https://static.rainfocus.com/splunk/splunkconf18/sess/1523395100233001xpRe/finalPDF/IT1428_AnatomySuccessfulEventAnalytics_Final_1538858366825001rI4i.pdf) - .conf18.


## Contribute
Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License
[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Simon Duff has waived all copyright and
related or neighbouring rights to this work.
