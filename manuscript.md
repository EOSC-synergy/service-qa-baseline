---
author-meta: []
bibliography:
- content/manual-references.json
date-meta: '2020-05-05'
header-includes: '<!--

  Manubot generated metadata rendered from header-includes-template.html.

  Suggest improvements at https://github.com/manubot/manubot/blob/master/manubot/process/header-includes-template.html

  -->

  <meta name="dc.format" content="text/html" />

  <meta name="dc.title" content="A set of Common Service Quality Assurance Baseline Criteria for Research Projects" />

  <meta name="citation_title" content="A set of Common Service Quality Assurance Baseline Criteria for Research Projects" />

  <meta property="og:title" content="A set of Common Service Quality Assurance Baseline Criteria for Research Projects" />

  <meta property="twitter:title" content="A set of Common Service Quality Assurance Baseline Criteria for Research Projects" />

  <meta name="dc.date" content="2020-05-05" />

  <meta name="citation_publication_date" content="2020-05-05" />

  <meta name="dc.language" content="en-US" />

  <meta name="citation_language" content="en-US" />

  <meta name="dc.relation.ispartof" content="Manubot" />

  <meta name="dc.publisher" content="Manubot" />

  <meta name="citation_journal_title" content="Manubot" />

  <meta name="citation_technical_report_institution" content="Manubot" />

  <link rel="canonical" href="https://EOSC-synergy.github.io/service-qa-baseline/" />

  <meta property="og:url" content="https://EOSC-synergy.github.io/service-qa-baseline/" />

  <meta property="twitter:url" content="https://EOSC-synergy.github.io/service-qa-baseline/" />

  <meta name="citation_fulltext_html_url" content="https://EOSC-synergy.github.io/service-qa-baseline/" />

  <meta name="citation_pdf_url" content="https://EOSC-synergy.github.io/service-qa-baseline/manuscript.pdf" />

  <link rel="alternate" type="application/pdf" href="https://EOSC-synergy.github.io/service-qa-baseline/manuscript.pdf" />

  <link rel="alternate" type="text/html" href="https://EOSC-synergy.github.io/service-qa-baseline/v/89256752feaaf66efcdfa492c171241b122aeace/" />

  <meta name="manubot_html_url_versioned" content="https://EOSC-synergy.github.io/service-qa-baseline/v/89256752feaaf66efcdfa492c171241b122aeace/" />

  <meta name="manubot_pdf_url_versioned" content="https://EOSC-synergy.github.io/service-qa-baseline/v/89256752feaaf66efcdfa492c171241b122aeace/manuscript.pdf" />

  <meta property="og:type" content="article" />

  <meta property="twitter:card" content="summary_large_image" />

  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />

  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />

  <meta name="theme-color" content="#ad1457" />

  <!-- end Manubot generated metadata -->'
keywords:
- service quality assurance
- devops
- service quality baseline
- service testing
- service deployment
- agile development
lang: en-US
manubot-clear-requests-cache: false
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
title: A set of Common Service Quality Assurance Baseline Criteria for Research Projects
...



<br>
![](images/logo-SYNERGY.png){height="50px"}&nbsp;&nbsp;&nbsp;&nbsp;

_A DOI-citable version of this manuscript is available at <http://hdl.handle.net/>_.


<small><em>
This manuscript
was automatically generated
on 29-04-2020.
</em></small>

## Authors



+ **Pablo Orviz**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0002-2473-6405](https://orcid.org/0000-0002-2473-6405)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [orviz](https://github.com/orviz)<br>
  <small>
     Spanish National Research Council (CSIC); Institute of Physics of Cantabria (IFCA)
  </small>

+ **Mario David**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0003-1802-5356](https://orcid.org/0000-0003-1802-5356)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [mariojmdavid](https://github.com/mariojmdavid)<br>
  <small>
  </small>

+ **Jorge Gomes**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0002-9142-2596](https://orcid.org/0000-0002-9142-2596)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [jorge-lip](https://github.com/jorge-lip)<br>
  <small>
  </small>

+ **Joao Pina**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0001-8959-5044](https://orcid.org/0000-0001-8959-5044)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [jopina](https://github.com/jopina)<br>
  <small>
  </small>

+ **Samuel Bernardo**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0002-6175-4012](https://orcid.org/0000-0002-6175-4012)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [samuelbernardolip](https://github.com/samuelbernardolip)<br>
  <small>
  </small>

+ **Isabel Campos**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0002-9350-0383](https://orcid.org/0000-0002-9350-0383)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [isabel-campos-plasencia](https://github.com/isabel-campos-plasencia)<br>
  <small>
     Spanish National Research Council (CSIC); Institute of Physics of Cantabria (IFCA)
  </small>



## Abstract {.page_break_before}

The purpose of this document is to define a set of quality standards,
procedures and best practices to conform a Service Quality Assurance
plan to serve as a reference within the European research ecosystem 
elated projects for the adequate development, deployment, operation
and integration of services into production research infrastructures.


## Copyright Notice

Copyright © Members of the EOSC-Synergy collaborations, 2019-2020.

## Acknowledgements

The EOSC-Synergy project received funding from the European Union’s 
Horizon 2020 research and innovation programme under grant agreement 
number 857647.

<p align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT1WF4g5KH3PnQE_Ve10QFRS-gZ0NpCQ7Qr-_km1RqnOCEF1fQt">
</p>


## Document Log

| Issue | Date       | Comment              |
|-------|------------|----------------------|
| v0.1  | 27/04/2020 | First draft version  |
| v0.2  | 28/02/2020 | Second draft version |


## Introduction

The Open Science realization in Europe is already taking its first steps by
means of the implementation of the European Open Science Cloud (EOSC). The
EOSC aims at providing researchers with a unique, federated and inclusive
view of fit-for-purpose services, developed and operated by the diverse European
research infrastructures, including the underlying e-Infrastructures. Consequently,
the ultimate success of the EOSC heavily relies on the quality aspects of those
services, such as their stability or functional suitability.

The meaning of **Service** can be regarded from different perspectives.
From an IT Service Management (ITSM) standpoint, such as the EOSC Service Management
System (SMS) process model, a service is devised as a means to "provide value
to the customer". The same goal is shared by the DevOps paradigm, but in this
case there is a more pragmatic vision the customer satisfaction is achieved
through the continuous delivery of quality-assured services, with a shorter
life cycle, as the final outcome of a comprehensive software development process.

The ITSM model has a broader focus. A service is an "intangible asset" that
also includes additional activities such as customer engagement and support.
Consequently, it is a much heavier process that might not be appropriate to
be applicable for all types of services. The DevOps model, on the other hand,
narrows down the scope to meet the user expectations by acting exclusively on
the quality features of the service, which is seen as an aggregate of software
components in operation.

## Purpose

This document provides an initial approach to Service Quality Assurance,
meant to be applied in the integration process of the services existing
under the EOSC-Synergy project, which eventually will be accessible as part
of the EOSC offerings.

The criteria compiled in this document favours a pragmatic and systematic
approach that puts emphasis on the programmatic assessment of the quality
conventions. To this end, the criteria herein compiled builds on the DevOps
culture already established in the preceding Software Quality Assurance baseline
document [@url:https://digital.csic.es/handle/10261/160086] to outline the set
of good practices that seek the usability and
reliability of services, and meet the user expectations in terms of functional
requirements.

## Contextualization of a Service

As a result, a **Service**, as conceived in this document, represent the following:

* Web service [WS] [@url:https://techterms.com/definition/web_service]:
    * A web service is an application or data source that is accessible via
    a standard web protocol (HTTP or HTTPS).
    * Web services are designed to communicate with other programs,
    rather than directly with users.
    * Most web services provide an API, or a set of functions and commands,
    that can be used to access the data.

* Web application [WApp] [@url:https://techterms.com/definition/web_application]:
    * A web application or "web app" is a software program that runs on a web server.
    * Web apps must be accessed through a web browser.

* Platform or Service Composition [Plat]
[@url:https://csrc.nist.gov/glossary/term/Service_Composition]:
    * Aggregation of multiple small services into larger services.
    * An integrated set of Web services, Web applications and software components.

Examples are: Web portals, Scientific portals and gateways, data repositories.



## Goals

The herein proposed baseline harnesses the capabilities of the quality factors
in the underlying software to lay out the principles for attaining quality in
the enabled services within the EOSC context. According to this view, service
quality is the foundation to shape user-centric, reliable and fit-for-purpose
services. 

The Service Quality baseline aims at fulfilling the following goals:

* Complement with a DevOps approach the existing approaches to assess and
assure the quality and maturity of services within the EOSC, i.e. Technology
Readiness Levels (TRLs) and EOSC Service Management System (SMS).

* Build trust on the users by strengthening the reliability and stability of
the services, with a focus on the underlying software, thus ensuring a proper
realization of the verification and validation processes.

* Ensure the functional suitability of the service by promoting testing
techniques that check the compliance of the user requirements.

* Improve the usability by identifying the set of criteria that fosters the
service adoption.

* Promote the automated validation of the service quality criteria.


## Notational Conventions

The keywords “MUST”, “MUST NOT”, “REQUIRED”, “SHALL”, “SHALL NOT”, “SHOULD”,
“SHOULD NOT”, “RECOMMENDED”, “MAY”, and “OPTIONAL” in this document are to be
interpreted as described in RFC 2119 [@url:https://www.ietf.org/rfc/rfc2119.txt].


## Quality Criteria

The following sections describe the quality conventions and best
practices that apply to the development, operation and integration
phases of a **Service** with a production infrastructure for research,
such as the EOSC ecosystem. These guidelines rule the **Service** development
and operation process within the framework of the EOSC-Synergy project.

Some of the criteria in this document is similar or based on the
document "Software Quality Assurance baseline"
[@url:https://digital.csic.es/handle/10261/160086], for such cases the
following tag is added to the criteria: [SQA-QC.XyNN] where QC.XyNN is
the codename of the criteria in that document.

### Integration Testing [SvcQC.Int]

Integration testing refers to the evaluation of the interactions among
coupled **Service** or parts of a system that cooperate to achieve a given
functionality.

* **[SvcQC.Int01]** Integration testing outcome MUST guarantee the overall
operation of the  **Service** whenever new functionality is involved. [SQA-QC.Int01].

* **[SvcQC.Int02]** Integration testing SHOULD be automated.

* **[SvcQC.Int03]** Ad-hoc pilot **Service** infrastructures and/or local
testbeds MAY be used to cope with the integration testing requirements. [SQA-QC.Int04].

### Scalability tests [SvcQC.Sca]

Scalability Testing is a non-functional test methodology in which an
application’s performance is measured in terms of its ability to scale
up or scale down the number of user requests or other such performance
measure attributes [@url:https://www.softwaretestinghelp.com/what-is-scalability-testing/].

* **[SvcQC.Sca01]**

### Elasticity tests [SvcQC.Ela]

Elasticity is the level of autonomous adaptation provided by the
cloud layer in response to variable demand for the software
service [@doi:10.1186/s13677-019-0134-y].

* **[SvcQC.Ela01]**

### Acceptance and System tests [SvcQC.Acc]

Test of functionality of the **Service**, tests done before the **Service**
enters into production. Tests for the public API.

* **[SvcQC.Acc01]**

### Documentation [SvcQC.Doc]

* **[SvcQC.Doc01]** Documentation MUST be available online, easily
findable and accessible. [SQA-QC.Doc03].

* **[SvcQC.Doc02]** Documentation SHOULD have a Persistent Identifier (PID).

* **[SvcQC.Doc03]** Documentation MUST be version controlled. [SQA-QC.Doc01.1].

* **[SvcQC.Doc04]** Documentation MUST be updated on new **Service** versions
involving any change in the installation, configuration or behaviour of
the **Service**. [SQA-QC.Doc04].

* **[SvcQC.Doc05]** Documentation MUST be updated whenever reported
as inaccurate or unclear. [SQA-QC.Doc05].

* **[SvcQC.Doc06]** Documentation MUST have a non-software license.

* **[SvcQC.Doc07]** Documentation MUST be produced according to the
target audience, varying according to the **Service** specification.
The identified types of documentation and their RECOMMENDED content are:

  * **[SvcQC.Doc07.2]** Deployment and Administration. [SQA-QC.Doc06.3]:
    * Installation and configuration guides.
    * Service Reference Card, with the following RECOMMENDED content:
      * Brief functional description.
      * List of processes or daemons.
      * Init scripts and options.
      * List of configuration files, location and example or template.
      * Log files location and other useful audit information.
      * List of ports.
      * Service state information.
      * List of cron jobs.
      * Security information.
      * FAQs and troubleshooting.
  * **[SvcQC.Doc07.3]** User. [SQA-QC.Doc06.4]:
    * Detailed User Guide for the **Service**.
    * Public API documentation (if applicable).
    * Command-line (CLI) reference (if applicable).

### Policies [SvcQC.Pol]

* **[SvcQC.Pol01]** The **Service** MUST include the following policy documents:
  * **[SvcQC.Pol01.1]** Acceptable Usage Policy (AUP).
  * **[SvcQC.Pol01.2]** Access policy.
  * **[SvcQC.Pol01.3]** Privacy policy.

### Security [SvcQC.Sec]

* **[SvcQC.Sec01]** The **Service** public endpoints and APIs MUST be secured
with encryption.

* **[SvcQC.Sec02]** Dynamic application security testing (DAST)
[@url:https://www.techopedia.com/definition/30958/dynamic-application-security-testing-dast]
SHALL be performed from the outside, to the **Service** in an operation
state, to look for security vulnerabilities (e.g. SQL injection,
cross-site scripting, DDOS). [SQA-QC.Sec03].

* **[SvcQC.Sec03]** Manual penetration testing MAY be part of the
application security  verification effort. [SQA-QC.Sec04].

* **[SvcQC.Sec04]** The **Service** SHOULD have an Authentication mechanism.

* **[SvcQC.Sec05]** The **Service** MUST use strong ciphers for encryption.

* **[SvcQC.Sec06]** Credentials used in the **Service** MUST be signed by
a recognized certification authority.

* **[SvcQC.Sec07]** The **Service** MUST validate the credentials and signatures.

### Automated Deployment [SvcQC.Aud]

* **[SvcQC.Aud01]** Production-ready **Service** SHALL be deployed as
a workable system with the minimal user or system administrator interaction
leveraging Infrastructure as Code (IaC) tools.

### Support [SvcQC.Sup]

* **[SvcQC.Sup01]** The **Service** MUST have a tracker or helpdesk
for operational and users issues.

* **[SvcQC.Sup02]** The **Service** SHOULD have a tracker for the
underlying software issues. [SQA-QC.Man01].

* **[SvcQC.Sup03]** The **Service** SHOULD include an Operational
Level Agreement (OLA) with the infrastructure where it is integrated.

* **[SvcQC.Sup04]** The **Service** MAY include Service Level
Agreement (SLA) with user communities.

### Monitoring, Alerts, Metrics [SvcQC.MAM]

* **[SvcQC.MAM01]** The **Service** in an operational production state SHOULD be monitored.
  * **[SvcQC.MAM01.1]** The **Service** public endpoints SHOULD be monitored.
  * **[SvcQC.MAM01.2]** The **Service** public APIs SHOULD be monitored.
  * **[SvcQC.MAM01.3]** The **Service** SHOULD for security related criteria (DAST).

* **[SvcQC.MAM02]** The **Service** SHOULD have alerts.

* **[SvcQC.MAM03]** The **Service** SHOULD have metrics.


## Glossary

__API__
: Application Programming Interface

__CLI__
: Command Line Interface

__DAST__
: Dynamic Application Security Testing

__EOSC__
: European Open Science Cloud

__VCS__
: Version Control System


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
