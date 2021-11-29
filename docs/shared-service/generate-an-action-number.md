---
layout: default
title: Generate an action number
parent: Shared services
nav_order: 2
---
# Generate an action number
{: .no_toc }
This shared-service generates an action number for your service to associate with a court action. The action number generator allows you to maintain a correct sequence for all action numbers created.
<br><br>
{: .fs-6 .fw-300 }




---
**Tags:** Justice Digital | Action number | API | Civil action
{: .text-grey-lt-300 }

<br><br>

## On this page
{: .no_toc .text-delta }

- TOC
{:toc}
---

## Background
An Action Number is a business key that is used to identify actions across all tracks in the Courts.

Action numbers are commonly a manual process, using paper and stamps. This service generates Action numbers automatically, automating the manual process and saving time, while eliminating duplicates of action numbers.

---

## Using the shared services

### When to use
Use the action number generator if you need to create a new action number for your service.

You would use this micro-service when you need to reliably generate an action number for a certain jurisdiction and district or centre. The action number generator allows you to maintain a correct sequence for all action numbers created.

### When not to use
This service only creates action numbers for civil actions in the Court of Queen's Bench. It is not currently available in other levels of Court.

### How it works
Based on the jurisdiction and district, it will look up the last generated value in the sequence, and increment that. It then returns that identifier and formats it based on the business rules relevant for that jurisdiction and district.

The generator looks up the last action number, increments it, and returns the next one. Making sure there are no collisions.

### How to access
#### Sandbox
[access to the dev environment or sandbox to try out and test with, determine if it fills their need]

(Point to UAT endpoint)

Link to Swagger page to try out and explore the API.

#### Production access
After testing out the API, here is how to request to get full access to the shared service:

For production access, [intake process] (contact ______ to request access)

#### Security
Instructions on security (how is security being handled on this?)

[Link to standards if relevant]

---

## Examples
A civil action number is made up of Year, district, and number.
