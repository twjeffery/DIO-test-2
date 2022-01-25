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
{: .no_toc .mt-2 .mb-5}

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
Use this service when you need any kind of Justice data. This data includes:



### When not to use
{: .no_toc .mb-3}
This service only creates action numbers for civil actions in the Court of Queen's Bench. It is not currently available in other levels of Court.

### How it works
{: .no_toc .mb-3}
Based on the jurisdiction and district, it will look up the last generated value in the sequence, and increment that. It then returns that identifier and formats it based on the business rules relevant for that jurisdiction and district.

The generator looks up the last action number, increments it, and returns the next one. Making sure there are no collisions.

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


#### A Civil Action number explained:
{: .no_toc }

A [civil action](https://twjeffery.github.io/DIO-test-2/docs/shared-service/Justice/glossary/#:~:text=Justice-,Civil%20action,-A%20civil%20action) number is made up of Year, district, and number.

eg. Action Number 2103 123456 = (2021 Edmonton 123456)

![image infos](../../../assets/images/action-number.png)

See more [Action number rules and examples](https://goa-dio.atlassian.net/wiki/spaces/QFR/pages/1486356612/Architecture+Artifacts#Action-Numbers)

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
[Action number formatting](https://goa-dio.atlassian.net/wiki/spaces/QFR/pages/1486356612/Architecture+Artifacts#Action-Numbers)


---

## Support

### Need help? Connect with us on Slack
{: .no_toc }
[#jd-shared-services](https://justicedigital.slack.com/archives/C02UR7LPRDF) General information and discussion related to justice shared services including questions, new shared service proposals, contribution, and other requests.

You can also email the justice platform team at <JSG.PlatformSupport@gov.ab.ca>
