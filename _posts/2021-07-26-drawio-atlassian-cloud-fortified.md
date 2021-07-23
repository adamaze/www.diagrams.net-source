---
layout: post
author: diagrams.net
slug: drawio-atlassian-cloud-fortified
date: 2021-07-26 12:07:00
title: draw.io is now an Atlassian Cloud Fortified app
tags: [features, Atlassian]
categories: [features,atlassian,trust]
---

The draw.io apps for Confluence and Jira are built, delivered and maintained by JGraph alongside the online diagrams.net and desktop tools. JGraph is pleased to announce that draw.io is the only secure diagramming application to meet Atlassian's new **Cloud Fortified** standard. 

## What is Atlassian Cloud Fortified?

Atlassian developed the more [rigorous Cloud Fortified standard](https://marketplace.atlassian.com/categories/cloud-fortified-apps) to highlight enterprise-grade apps with a particular focus on reliability and service, in addition to increased security requirements. 

By including strict reliability and support requirements, the new standard goes above and beyond the older Atlassian Cloud Security program. 

As a security-first diagramming app for Atlassian Cloud products, the draw.io developer JGraph has continued to work closely with Atlassian over the years, participating in security initiatives as they are made available to app developers.

### draw.io is Atlassian Cloud Fortified

As a Cloud Fortified app, draw.io and JGraph meets the following requirements:

* Participate in all of Atlassian's cloud app security programs, including the automated [Ecoscanner](https://developer.atlassian.com/platform/marketplace/ecoscanner/), as well as the [VDP](https://developer.atlassian.com/platform/marketplace/vdp/), [AMS](https://developer.atlassian.com/platform/marketplace/vulnerability-tracking-more-info/), [Marketplace Bug Bounty](https://developer.atlassian.com/platform/marketplace/marketplace-security-bug-bounty-program/), and the [security self-assessment](https://developer.atlassian.com/platform/marketplace/security-self-assessment-program/)  programs.
* Meet all of the [security requirements for Marketplace cloud apps](https://developer.atlassian.com/platform/marketplace/security-requirements/).
* Pass strict checks for [service reliability and performance at scale](https://developer.atlassian.com/platform/marketplace/cloud-fortified-apps-program-reliability-requirements/), including automated checks to ensure a 99.9% or higher app availability. 
* Proactively [review compatibility with upcoming host product updates](https://community.atlassian.com/t5/Marketplace-Apps-Integrations/Introducing-Cloud-Fortified-meet-the-first-Cloud-Fortified-apps/ba-p/1749111).
* Abide by the [Atlassian-defined app support SLAs](https://developer.atlassian.com/platform/marketplace/sla-management/) and integrate with Atlassian's process to ensure fast incident response and resolution times.

### Secure diagramming with draw.io and Atlassian

JGraph and draw.io are fully committed to your data security and privacy. 

Because your sensitive diagram data doesn't leave your infrastructure and is never stored on the draw.io servers, draw.io is an app for Confluence and Jira that lets you comply with a number of data protection certifications (``ISO 27000``, ``27001`` and ``27002``) and the GDPR.

[Learn more about our commitment to data security and privacy](/blog/data-protection.html)

If you are using the draw.io apps for Confluence or Jira Cloud, Atlassian lets you set strict data governance rules, including your [**data residency** region](https://confluence.atlassian.com/cloud/manage-data-residency-976763149.html) to choose where your data or _in-scope product content_ resides. 

Set the draw.io **lockdown** option as a JSON string in the app configuration to additionally restrict data transmission to _only_ between a user's browser and their Confluence Cloud instance: 
<br />``"lockdown": true"``

If you use one of the draw.io features that are not provided within the scope of the Atlassian platform (PDF generation; ``.vdsx``, ``.vsd``, ``.vssx`` and ``.gliffy`` import; and generated PlantUML images), use the draw.io **datagovernance** option to set a server endpoint region in a JSON string in the app configuration: 
<br />``"dataGovernance": "EU"`` or ``"dataGovernance": "US"``
<br /><img src="/assets/img/blog/confluence-cloud-data-governance-lockdown-configuration.png" style="width=100%;max-width:600px;height:auto;" alt="Set which draw.io server endppoint region to use and restrict data transmission to between browser and Confluence Cloud in the draw.io app configuration JSON code">

[See how to configure draw.io in Confluence Cloud](/doc/drawio-confluence-cloud.html)



