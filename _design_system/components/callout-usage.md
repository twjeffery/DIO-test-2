---
layout: default
title: Callout
parent: Components
has_toc: false
---


---
# Callout
{: .no_toc }

Callouts communicate important changes or facts within the body layout through a strong visual emphasis, so that users take notice and read the information.
<br><br>
**Usage** | [**Code**](https://twjeffery.github.io/DIO-test-2/design_system/components/callout-code/) | [**Related**](https://twjeffery.github.io/DIO-test-2/design_system/components/callout-related/)


<br><br>
{: .fs-6 .fw-300 }

## On this page
{: .no_toc .text-delta }

- TOC
{:toc}


## Live Demo
---
<div>
<iframe
  width="100%"
  height="250"
src="https://ui-components.alpha.alberta.ca/react/iframe.html?id=react-components-callout--variants" markdown="block" />
</div>


<div class="code-example" markdown="1">

<div>
<iframe
  width="100%"
  height="250"
src="https://ui-components.alpha.alberta.ca/react/iframe.html?id=react-components-callout--variants" markdown="block" />
</div>

</div>


```
<GoACallout
  type="'important || 'information' || 'event' || 'emergency' || 'success'"
  title="Callout Title"
  content="Information to the user goes in the content"
/>
```



[**Angular**]() | [**React**]() | [**Vue**]() | [**Web components**]()
<br><br>


<br>

## Content
---
Callout banners should communicate one piece of crucial information pertaining to the topic.

A callout banner must be relevant to the header or section to which it corresponds. In terms of importance within the section, it takes priority over any other paragraph under the header. If there is additional information that is not in the corresponding section, or is on another page, do use a link.

### Container Text
{: .no_toc }
At minimum, body text is required. There may be an optional header.
<br><br>

![image infos](../../../assets/images/callout-do-1.png)
![image infos](../../../assets/images/callout-dont-1.png)
![image infos](../../../assets/images/callout-dont-2.png)
![image infos](../../../assets/images/callout-dont-3.png)

<br><br>
## Variants
---
Each calllout variant has a particular use case and its design communicates it's function to the user. It is therefore very important that the different variants are implemented consistently across products, so that they communicate consistently.
<br><br>

![image infos](../../../assets/images/callout-variants.png)


| Variant      | Purpose           |
|:-------------|:------------------|
| Information           | Information callouts are used to communicate non-urgent information. |
| Event | Event callouts are used to communicate information about upcoming and scheduled events.   |
| Important          | Important callouts are used to communicate non-emergency but still important messages to a user.      |
| Emergency           | Emergency callouts are used to alert the user to only the most important pieces of information. They can also be used to alert the user to system errors. |
| Success          | Success callouts are used to inform the user of a positive status change to a performed action. |

<br>
<br>

## Positioning
---
Callout banners should be the full width of the content space they are placed in, with a maximum width of 700px.

Callouts banners have a bottom margin of 28px.
<br><br>

![image infos](../../../assets/images/callout-dont-4.png)

<br>
<br>
## Anatomy
---
![image infos](../../../assets/images/callout-anatomy.png)

<br>
<br>

## Feedback
---
Help improve this page. To help make sure that this page is useful, relevant and up to date, you can share your research or feedback on [Github](https://github.com/GovAlta/ui-components/issues/158) or propose a change below using _Edit this page on Github._
