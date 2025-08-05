---
title: "Thin vs. Thick Edge IoT Deployments"
excerpt_separator: "<!--more-->"
toc: true
toc_sticky: true
date: 2024-12-02
categories:
  - thought_leadership
tags:
  - IoT
  - Edge Computing
  - Hardware
  - MachNation
  - Archive
---

**This article originally appeared on [iotforall.com](https://www.iotforall.com/thin-vs-thick-edge-in-enterprise-iot-deployments).**
{: .notice--info}

{% include figure popup=true image_path="/assets/images/iotForAll-header.jpg" %}

Industry experts agree that critical infrastructure for Internet-of-Things (IoT) deployments will continue to shift towards the edge. As new use cases emerge across industries investing in their digital transformation journeys, the diversification of edge-enabled physical hardware will continue to expand with technology and business requirements. Edge deployments in IoT are highly diverse and exist within a spectrum between "thin" and "thick". Lets take a look at thin vs. thick edge IoT, compare and contrast both ends of that spectrum, and then take a look at some of the technical requirements for enterprise IoT deployments for each.

<!--more-->

> 'Edge deployments in IoT are highly diverse and exist within a spectrum between 'thin' and 'thick'.' - MachNation

## Thin vs. Thick Edge: Which Is Better?

The short answer: It depends. An enterprise’s use-case and software capabilities are the primary factors in determining which edge hardware best suits its needs. According to MachNation research of enterprise IoT buyers, roughly 90 percent of the complexity at the edge is software-related. Thus, while many hardware vendors already provide hardware that adequately supports most IoT solutions, the quality, sophistication, usability, and scalability of vendors’ software and platform for both thin and thick edge deployments remain a differentiator. While having the right software to suit enterprise needs is critical, choosing the right edge hardware can often be the key differentiator between an overly-complex, costly edge deployment and an effective one.

## Thin Edge Hardware & Use Cases

A thin edge is an IoT solution that supports and manages decentralized deployments of low-powered, memory and power constrained devices. Some examples include Arm Cortex-M devices, low-power Texas Instruments (TI) devices, Marvell Technology devices, and others.

These devices transmit data northbound with minimal execution of workloads (e.g., filtering, aggregation, or normalization) or with analytics being performed at the site of data origin. Enterprises install thin edge nodes to connect legacy equipment to their cloud solutions, taking advantage of cost savings on equipment.

### Use Cases:

- Track and trace; battery-powered sensors, continuous transmission of small geo-data packets to the cloud.

- Agricultural monitoring; low-powered, transmitting selective low-volume data points to a gateway device.

- Smart building; battery-powered sensors that only “wake up” when an action is triggered or when transmitting low-volume data to the centralized monitoring and management platform.

## Thick Edge Hardware

A thick edge is an IoT solution that supports and manages high-powered, high-capability edge hardware. Some examples include high-powered IoT gateway devices from companies like Dell and Cisco, Arm Cortex-A devices, x.86-based devices, and others. These devices can run advanced on-device inference, event processing rules, business logic, analytics, and machine learning algorithms.

### Use Cases:

- Smart factory; high-memory capacity devices that can store and analyze historical machine-performance data on-device.

- Cloud optimization; gateway devices that actively filter out “junk” sensor data before transmitting to the cloud.

- Latency-critical operations; high-powered devices capable of running on-device inference in near real-time and executing automatic actions (i.e. powering down a wind-turbine automatically when its rotations-per-minute (RPMs) fall outside acceptable parameters).

## Key Decision Factors

Every IoT edge deployment should be purpose-built to fit the use case. Restrictions on available hardware and software can also be determining factors. It is recommended to have a well-defined hardware and software strategy in place before embarking on an IoT edge journey. Consider these factors when choosing and IoT edge hardware vendor:

- Use-case
- Hardware availability
- Cloud infrastructure to support your edge deployment
- Data requirements around latency and on-device compute resources

Whether you decide to implement thin vs. thick edge IoT will depend on your specific use case, and these factors should also be weighed carefully.
