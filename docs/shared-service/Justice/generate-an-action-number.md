---
layout: default
title: Generate an action number
parent: Justice
grand_parent: Shared services
nav_order: 1
---

# Generate an action number
{: .no_toc .mt-8 }
`action-number-api`
{: .mt-2 .mb-3 }
This shared-service generates an action number for your service to associate with a court action. The action number generator allows you to maintain a correct sequence for all action numbers created.

---
  <summary>
    On this page
  </summary>
- TOC
{:toc}
---

## Background
{: mb-3}
An [Action Number](https://twjeffery.github.io/DIO-test-2/docs/shared-service/Justice/glossary/#:~:text=Area-,Action%20number,-An%20Action%20Number) is a business key that is used to identify actions across all tracks in the Courts.

Action numbers are commonly a manual process, using paper and stamps. This service generates Action numbers automatically, automating the manual process and saving time, while eliminating duplicates of action numbers.

---

## Using the shared service

### When to use
{: .no_toc .mb-2}
Use the action number generator if you need to create a new action number for your service.

You would use this micro-service when you need to reliably generate an action number for a certain [jurisdiction](https://twjeffery.github.io/DIO-test-2/docs/get-started/glossary/#:~:text=Justice-,Jurisdiction,-A%20jurisdiction%20is) and district or centre. The action number generator allows you to maintain a correct sequence for all action numbers created.

### When not to use
{: .no_toc .mb-2}
This service only creates action numbers for civil actions in the Court of Queen's Bench. It is not currently available in other levels of Court.

### How it works
{: .no_toc .mb-2}
Based on the jurisdiction and district, it will look up the last generated value in the sequence, and increment that. It then returns that identifier and formats it based on the business rules relevant for that jurisdiction and district.

The generator looks up the last action number, increments it, and returns the next one. Making sure there are no collisions.

### How to access
{: .no_toc .mb-2}
#### Testing environment
{: .no_toc }
Access the dev environment to try out and test this shared service within your context and to determine if it fills your need.

[Try out and explore the API](#) (Link to Swagger page)

[Point to UAT endpoint](#)


#### Production access
{: .no_toc .mt-3}
To request access to the production environment: email your request to <JSG.PlatformSupport@gov.ab.ca>

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

## Support

### Need help?
{: .no_toc }
[Shared service owner?]

For technical help, contact the justice platform team [platform team contact information]

### Want to contribute?
{: .no_toc }
These services are made by community contribution.

[Contribution process]
