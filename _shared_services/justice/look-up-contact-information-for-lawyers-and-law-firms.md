---
layout: default
title: Look up contact information for lawyers and law firms
parent: Justice Shared Services
nav_order: 2
---

# Look up contact information for lawyers and law firms
{: .no_toc .mt-8 .mb-5}

`law-society-api`
{: .mt-2 .mb-5}

The law society database is a directory to look up information on lawyers and law firms to use within your service.

[Swagger - API documentation](https://jdms-law-society-api-jdms-prod.os99.gov.ab.ca/swagger/index.html)      [Health check](https://jdms-platform-api-jdms-dev.os99.gov.ab.ca/health-ui#/healthchecks)

---
## On this page
{: .no_toc .text-delta }

1. TOC
{:toc}
---

## Background
{: mb-3}
There is an existing Information Sharing Agreement between the Provincial Court, the Court of Queen’s Bench, the Ministry of Justice and Solicitor General, and the Law Society of Alberta for sharing for:
- Providing access to court administration services
- Scheduling court proceedings
- Communicating information regarding court administration, judicial administration, and other matters of general importance to the legal profession.

This micro-service provides an authority for this information to ensure that it is the same for all systems that need to use it.

---

## Using the shared service

### When to use
{: .no_toc .mb-3}
Use this service to verify the identity of lawyers and delegate access to legal assistants and law students. Also used to associate law firm to specific lawyers.

Any application that uses lawyers and or legal assistants would benefit from this shared service.

### When not to use
{: .no_toc .mb-3}
This service would not be relevant if you do not fall within the following:
- Providing access to court administration services
- Scheduling court proceedings
- Communicating information regarding court administration, judicial administration, and other matters of general importance to the legal profession.

#### Privacy
{: .no_toc}
The Bar ID is information that is sensitive, and should not be public.

### How to access
{: .no_toc .mb-3}

#### Testing environment
{: .no_toc .mb-2}
Access the dev environment to try out and test this shared service within your context and to determine if it fills your need.

[Try out and explore the API](https://jdms-law-society-api-jdms-prod.os99.gov.ab.ca/swagger/index.html)

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

**Filing digital service**

Ronald Garcia - Digital architect

Helen Maze - Product owner

[A description of how the action number generator is used within the Filing digital service.]

[link, video, or images of application]


---

### Additional documentation
{: .no_toc }

---

## Support

### Need help? Connect with us on Slack
{: .no_toc }
[#jd-shared-services](https://justicedigital.slack.com/archives/C02UR7LPRDF) General information and discussion related to justice shared services including questions, new shared service proposals, contribution, and other requests.

You can also email the justice platform team at <JSG.PlatformSupport@gov.ab.ca>
