---
title: "Whitepaper - Security Best Practices for SC//HyperCore Customers"
excerpt_separator: "<!--more-->"
date: 2025-06-14
toc: true
toc_sticky: true
categories:
  - whitepapers
tags:
  - Security
  - Best-Practices
---

![image-center](/assets/images/sc-whitepaper.png){: .align-center}

Executive summary of a whitepaper I authored at Scale Computing as the Technical Writer for the Engineering and Product teams. The report outlines best practices for customers to secure their infrastructure. The full version is available online [here](https://www.scalecomputing.com/documents/White-Papers/Security-Best-Practices-White-Paper.pdf).
{: .notice--info}

<!--more-->

# Executive Summary

As organizations increasingly rely on hyperconverged infrastructure, cybersecurity has become a fundamental business priority. This white paper from Scale Computing outlines actionable security best practices to help SC//HyperCore customers protect their infrastructure, data, and operations from evolving cyber threats.
Key Insights

-  Hyperconverged Advantage: SC//HyperCore reduces attack surfaces through centralized management and built-in security, but a layered, proactive approach is still essential.

-  Holistic Security Approach: Security must encompass not just data, but also network integrity, hardware protection, access controls, and user behavior monitoring.

## Recommended Best Practices

### Network Security

1. Keep SC//HyperCore systems updated to mitigate known vulnerabilities.

1. Isolate sensitive traffic (e.g., backplane) using VLANs and dedicated NICs.

1. Apply a defense-in-depth strategy with firewalls, segmentation, and endpoint protections.

### Authentication & Authorization

1. Enforce strong, regularly updated password policies.

1. Use OpenID Connect (OIDC) providers like Okta or EntraID for SSO and MFA.

1. Grant access based on roles to minimize privilege exposure.

### Logging & Monitoring

1. Centralize logs using syslog servers (e.g., Splunk, Rsyslog).

1. Filter and restrict access to sensitive logs (e.g., those with PII).

1. Use logs for auditing, compliance, and rapid incident response.

### Physical Hardware Security

1. Secure Out-of-Band Management (e.g., iDRAC, IPMI) with strong credentials and isolation.

1. Protect BIOS/UEFI configurations with password controls and firmware updates.

1. Disable unused ports and use tamper-evident labeling to detect physical tampering.

1. Procure hardware and components only through trusted, verifiable channels.

### Data Encryption

1. At Rest: Use third-party encryption tools like BitLocker (SC//HyperCore lacks native support).

1. In Transit: Secure data movement using TLS 1.2+ and network segmentation.

1. In Use: Isolate and physically secure systems while processing sensitive data.

## Conclusion

Security is not a one-time configuration but a continuous, shared effort. By applying the best practices in this guide, SC//HyperCore customers can strengthen their resilience, safeguard business continuity, and confidently navigate modern cyber risks.
