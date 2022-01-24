---
layout: default
title: Generate an action number
parent: Justice
grand_parent: Shared services
nav_order: 1
---

# Generate an action number
{: .no_toc .mt-4 }
This shared-service generates an action number for your service to associate with a court action. The action number generator allows you to maintain a correct sequence for all action numbers created.
<br><br>
{: .fs-6 .fw-300 }


[Create a test account](){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } or [contact the justice platform team for more information](#)

---
<details open markdown="block">
  <summary>
    On this page
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>
---

## Background
An [Action Number](https://twjeffery.github.io/DIO-test-2/docs/get-started/glossary/#:~:text=Area-,Action%20number,-An%20Action%20Number) is a business key that is used to identify actions across all tracks in the Courts.

Action numbers are commonly a manual process, using paper and stamps. This service generates Action numbers automatically, automating the manual process and saving time, while eliminating duplicates of action numbers.

---

## Using the shared service

### When to use
{: .no_toc }
Use the action number generator if you need to create a new action number for your service.

You would use this micro-service when you need to reliably generate an action number for a certain [jurisdiction](https://twjeffery.github.io/DIO-test-2/docs/get-started/glossary/#:~:text=Justice-,Jurisdiction,-A%20jurisdiction%20is) and district or centre. The action number generator allows you to maintain a correct sequence for all action numbers created.

### When not to use
{: .no_toc }
This service only creates action numbers for civil actions in the Court of Queen's Bench. It is not currently available in other levels of Court.

### How it works
{: .no_toc }
Based on the jurisdiction and district, it will look up the last generated value in the sequence, and increment that. It then returns that identifier and formats it based on the business rules relevant for that jurisdiction and district.

The generator looks up the last action number, increments it, and returns the next one. Making sure there are no collisions.

### How to access
{: .no_toc }
#### Sandbox
{: .no_toc }
[access to the dev environment or sandbox to try out and test with, determine if it fills their need]

(Point to UAT endpoint)

Link to Swagger page to try out and explore the API.

#### Production access
{: .no_toc }
After testing out the API, here is how to request to get full access to the shared service:

For production access, [intake process] (contact ______ to request access)

#### Security
{: .no_toc }
Instructions on security (how is security being handled on this?)

[Link to standards if relevant]

---

## Examples
A [civil action](https://twjeffery.github.io/DIO-test-2/docs/get-started/glossary/#:~:text=Justice-,Civil%20action,-A%20civil%20action) number is made up of Year, district, and number.

#### Civil action example:
{: .no_toc }


### How it’s used
{: .no_toc }
#### Who’s currently using it within their service?
{: .no_toc }
**Court case management digital service**

Derek Osadiuk - Digital architect

Chrissy Parkinson - Product owner

**Filing digital service**

Ronald Garcia - Digital architect

Helen Maze - Product owner

#### Examples of use:
{: .no_toc }
**Repo**
Link to repo

**Live app**
[Link to app in test env]

[Link to other relevant things]

[Explanation of how it’s helping within a context of a service]

Images if relevant of interface or UI

---

### Additional documentation
{: .no_toc }
[Action number formatting](https://goa-dio.atlassian.net/wiki/spaces/QFR/pages/1486356612/Architecture+Artifacts#Action-Numbers)

[Any other documentation relevant in creating this service.]

---

### Release notes
{: .no_toc }
[v1]

[v2]

---

## Support and contribution

### Need help?
{: .no_toc }
[Shared service owner?]

For technical help, contact the justice platform team [platform team contact information]

### Want to contribute?
{: .no_toc }
These services are made by community contribution.

[Contribution process]
