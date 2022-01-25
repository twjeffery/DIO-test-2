---
layout: default
title: Look up information for court personnel
parent: Justice
grand_parent: Shared services
nav_order: 9
---
In development
{: .label .label-yellow .mt-6}

# Look up information for court personnel
{: .no_toc .mt-4 .mb-5}

`court-personnel-api`
{: .mt-2 .mb-5}

Look up meta data or contact information regarding Justice, Judge, Justice Assistants (JA), or Masters at any point in your service.

[Swagger - API documentation](#)      [Health check](https://jdms-platform-api-jdms-dev.os99.gov.ab.ca/health-ui#/healthchecks)

---
## On this page
{: .no_toc .text-delta }

1. TOC
{:toc}
---

## Background
{: mb-3}
Currently, meta data and contact information for Judges, Justices, Judicial assistants, and Masters are collected and updated in a number of different places. Services need to pull this data together to use within their service. The Justice/JA shared service aims to be the source of truth for this information, where Justices and Judicial assistants can come to update information and for all other services and systems to pull from.

---

## Using the shared service

### When to use
{: .no_toc .mb-3}
Use this service when you need any kind of Justice data.

Information on each Justice or Judge, including:
- Name
- Judge code (5-6 letter code, similar to an identification number)
- Email
- Level of court (provincial, QB, CoA)
- Jurisdiction - (surrogate, bankruptcy, commercial list)
- Supernumerary flag & date
- Active (yes/no)
- Retirement date
- Appointment date
- Location
- Bilingual (yes/no)
- Associated JA's (listed)
- Justice training data

Information on each Judicial Assistant, including:
- Name
- Email
- Location, Court House/ Office (similar structure to Justice’s)
- Associated Justice's (listed)

### When not to use
{: .no_toc .mb-3}
This shared service is not relevant for services if they do not need to know anything about a Justice or Judicial assistant.

### How it works
{: .no_toc .mb-3}
The Justice / JA shared service stores all Justice and JA related data and information and puts it in a place where it can be updated and queried. By creating a single source of truth for this information, services will not have to duplicate this information anywhere.

#### Privacy
This information is considered sensitive. As it includes contact information for each Justice, Judge, and JA, the privacy of this information should be considered as a high priority.

This is information is gathered from:

[Judges of the Provincial Court](https://albertacourts.ca/pc/about-the-court/judges_and_justices/judges-list)
[Justices & Masters](https://albertacourts.ca/qb/about/justices-and-masters)

### How to access
{: .no_toc .mb-3}
#### Testing environment
{: .no_toc .mb-2}
Access the dev environment to try out and test this shared service within your context and to determine if it fills your need.

[Try out and explore the API](#) (Link to Swagger page)

[Point to UAT endpoint](#)
<br>

#### Production access
{: .no_toc .mb-2}
To request access to the production environment: email your request to <JSG.PlatformSupport@gov.ab.ca>

---

## Examples

### How it’s used
{: .no_toc .mb-3}

**Court case management digital service**

Derek Osadiuk - Digital architect

Chrissy Parkinson - Product owner

[A description of how the action number generator is used within the Court Case Management digital service.]

[link, video, or images of application]

**QB Filing digital service**

Ronald Garcia - Digital architect

Helen Maze - Product owner

The QB Filing service needs to look up Justice and Master names as part of the clerk review and filing process. The lookup enables a clerk to select an assigned Justice/Master and add it to a request as metadata, which can then be surfaced to other stakeholders involved in the workflow.

For example:
- any Clerk can open a package and see which Justice/Master has been assigned for review or signature.
- the requestor (Lawyer or Legal Assistant) can see which Justice/Master has requested revisions to a draft order, or which Justice/Master has signed their order.

In the future, a Lawyer or Legal Assistant who requests to file an order signed in Court would also use a Justice/Master lookup to identify the signature.



---

### Additional documentation
{: .no_toc }

---

## Support

### Need help? Connect with us on Slack
{: .no_toc }
[#jd-shared-services](https://justicedigital.slack.com/archives/C02UR7LPRDF) General information and discussion related to justice shared services including questions, new shared service proposals, contribution, and other requests.

You can also email the justice platform team at <JSG.PlatformSupport@gov.ab.ca>
