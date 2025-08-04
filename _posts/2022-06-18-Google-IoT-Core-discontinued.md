---
title: "Google IoT Core discontinued in 2023, analyst recommendations for enterprises"
excerpt_separator: "<!--more-->"
date: 2022-08-18
categories:
  - news
tags:
  - IoT
  - MachNation
  - Archive
  - Google
---

{% include figure popup=true image_path="/assets/images/road-block.jpg" %}

On August 18, 2022, Google announced the planned discontinuation of Google IoT Core, Google’s platform for managing IoT devices and their data. This will leave many enterprises without a necessary part of their IoT systems within one year. In this article, we’ll review why Google is doing this and provide MachNation’s recommendations on what enterprises running Google IoT Core should do.

<!--more-->

There are two reasons why Google is discontinuing IoT Core:

1. **Google cancels products.** This is far from the first time Google has canceled a product or discontinued support for it. Google has axed no less than 20 major product releases over the past decade (Google Product Graveyard). While this may come as a blow to enterprises that relied on Google’s infrastructure for their IoT solutions, it is not a shocking turn-of-events for those that are familiar with Google’s history.

2. **Of the three hyperscale cloud providers (Azure, AWS, and GCP), Google’s IoT offering is the worst of the group.** Google has failed to adhere to current IoT security standards, modernize their platform, and add new features. We’ve documented these deficiencies for over 5 years in MachNation’s IoT Application Enablement ScoreCard and our IoT Device Management ScoreCard.

What should affected enterprises do?

This is a tough question to answer. However, MachNation has three thoughts on what enterprises should do to move forward with their IoT solutions.

1. For enterprises with expertise in cloud-native deployments on Amazon AWS or Microsoft Azure solutions, migrate your IoT infrastructure to a different hyperscaler that has a dedicated team and vested interest in maintaining the viability of their solutions. That said, don’t underestimate the effort required to do this. Without a well-recreated IoT system architecture, other parts of your IoT tech stack will cease to function when you move to a new hyperscaler. 

2. For enterprises loath to using another hyperscaler besides Google, move your IoT solution to a best-in-class, 3rd-party data or device management solution. There are many on the market that are designed to operate with specific verticals, and just as many that are more horizontal to fit multiple use cases. Caveat emptor… there are big differences in platforms’ scalability, performance, and features. MachNation learned long ago that only by using and testing dozens of IoT platforms can we truly understand what these platforms are capable of.

3. For enterprises that still want to use a hyperscaler, you could consider a fault-tolerant multi-cloud solution. While it may be more complex to implement and incur additional costs up-front, a multi-cloud solution for things like an IoT data store or device agent support is more reliable, flexible, and less likely to spell disaster should another company “pull a Google”.

Google’s leaving the market will create architecture and solution problems for existing Google IoT Core customers, but there are options available.

MachNation is an IoT platform test lab with years of experience helping enterprises architect their IoT solutions using best-in-class IoT platforms and conduct IoT performance testing. Want more insights into a viable migration strategy? Contact us.

**This article was originally published on MachNation.com.**
{: .notice--info}
