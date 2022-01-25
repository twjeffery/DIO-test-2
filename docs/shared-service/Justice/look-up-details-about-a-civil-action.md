---
layout: default
title: Look up details about a civil action
parent: Justice
grand_parent: Shared services
nav_order: 3
---

# Look up details about a civil action
{: .no_toc .mt-8 .mb-5}

`civil-actions-api`
{: .mt-2 .mb-5}

The Civil Actions API is intended to be a hub for retrieving information about actions entered into the Civil and Sheriff Information system (CASES). This includes information about documents, hearings, parties (plaintiffs, defendants, etc), activities and more.

[Swagger - API documentation](https://jdms-law-society-api-jdms-prod.os99.gov.ab.ca/swagger/index.html)      [Health check](https://jdms-platform-api-jdms-dev.os99.gov.ab.ca/health-ui#/healthchecks)

---
## On this page
{: .no_toc .text-delta }

1. TOC
{:toc}
---

## Background
{: mb-3}
CASES is a legacy system used by the court system that contains a list of: all documents filed in an action,  information about parties to the action, hearings, and the results of the hearings.

Each document or hearing has a unique identifier made up of 2-5 character code.

**Examples of unique identifiers:**
- AF = affidavit
- SCDEC = Statement of claim - declaration

[Link to full list](#)

---

## Using the shared service

### When to use
{: .no_toc .mb-3}
Use the Civil Actions service when you need to look up details about a Civil Action including:

#### Plaintiff data
- Related Action
- Names
- Contact information
- Counsel of Record
- Comments

#### Defendant data
- Related Action
- Names
- Contact information
- Counsel of Record
- Comments

#### Other parties or non parties
- Plaintiff
- Defendant
- Applicant - important enough to add.
- Respondent
- Intervenor

#### Hearing data
- Related Action
- Dates
- Durations
- Justice
- Location
- Court Room
- Status of the hearing
- Result
- Comments
- Activity/ History Data

#### Justice's data
- Code
- Name
- Contact Information
- Hearings


### When not to use
{: .no_toc .mb-3}
If you need to write back into CASES. This cannot be done. This API is for validation and for populating fields within your service.

### How it works
- The Civil Action API currently connects to the Justice legacy database system for civil action information, CASES. This API provides a facade for accessing data from that database.
- Access is secured and audited.
- In the future this system will aggregate data from CASES, possibly QBSS and new systems such as Court Case Management and QB Filing into a backing Data Lake.

### How to access
{: .no_toc .mb-3}

#### Testing environment
{: .no_toc .mb-2}
Access the dev environment to try out and test this shared service within your context and to determine if it fills your need.

[Try out and explore the API](#)

[UAT endpoint](#)
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

[A description of how this is used within the Court Case Management digital service.]

[link, video, or images of application]

**QB Filing digital service**

Ronald Garcia - Digital architect

Helen Maze - Product owner

[A description of how this is used within the Filing digital service.]

[link, video, or images of application]


---

### Additional documentation
{: .no_toc }
[More information on CASES](https://goa-dio.atlassian.net/wiki/spaces/CCM/pages/1756332095/CASES)
---

## Support

### Need help? Connect with us on Slack
{: .no_toc }
[#jd-shared-services](https://justicedigital.slack.com/archives/C02UR7LPRDF) General information and discussion related to justice shared services including questions, new shared service proposals, contribution, and other requests.

You can also email the justice platform team at <JSG.PlatformSupport@gov.ab.ca>
