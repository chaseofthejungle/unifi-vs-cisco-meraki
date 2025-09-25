# Ubiquiti and Cisco Meraki Overview Guide

**Description/Overview:** Cisco Meraki and Ubiquiti (including UniFi and various other product lines) are two of the most widely-recognized and utilized platforms available in the current hardware market for cloud-managed network management solutions (e.g., access points, routers, switches) intended for organizations of varied sizes. However, their philosophies and emphases are different: while the Meraki platform is based on subscription-model cloud, network security, and automation technologies, Ubiquiti places more focus on on-premises network management solutions that are of a traditional pricing model, with higher expectation of user setup/configuration. This guide will compare and contrast both platforms and their prospective target audiences.

#### Table of Contents

1. [Introducing Meraki and Ubiquiti](#introducing)
2. [Comparison and Contrast](#compare)
3. [Which to Choose](#choose)
4. [Supplemental Resources](#supplemental)

<hr />

## 1. <a name="introducing">Introducing Meraki and Ubiquiti</a>

<hr />

## 2. <a name="compare">Comparison and Contrast</a>

| *Feature* | *Meraki* | *Ubiquiti* |
| :---: | :---: | :----: |
| Management Model | Cloud (dashboard provided via the web), for all monitoring, management, and device configuration services. | Hybrid Cloud (remote dashboard provided via UniFi Site Manager, for multi-site management). UniFi controller software is ran as a private cloud, on-premises, or by using Ubiquiti Cloud Key hybrid hardware. |
| Intended Users | Larger organizations and enterprises that are willing to pay subscription fees for full-scale, simple, automated, and professionally supported service management. | Organizations that are not quite large but do have technically knowledgable networking staff who are willing/desiring to have more managerial control over their networks. |
| Learning Curve | Features a beginner-friendly dashboard and the potential to zero-touch provision devices with automated configurations for quick and easy deployments even when there are many interfaces attached to the network. | Network administrators expected to have advanced knowledge for installations and configurations of platform, especially if needs are complex. |
| Scalability | High, enterprise-caliber scalability that is automated and centralized through a cloud-based dashboard. | Potential for scalability, but likely to need increasing manual configurations and modifications as devices and integrations grow. |
| Security | Features enterprise-level security integrations, including AI-powered threat detection. | Likely to satisfy the needs of small-to-medium sized businesses. |
| Pricing | |
| Support | |

<hr />

## 3. <a name="choose">Which to Choose</a>

**It might be advisable to choose Ubiquiti (and in particular, UniFi) if:**

* Your organization has the expertise and preference for manual/hands-on configuration.
  + UniFi allows significant control and customization, including over network infrastructure.
* A less expensive long-term option is important (no recurring license fees), although enterprise-level performance is necessary.
  + These conditions are common in small and medium sized organizations.

**It might be advisable to choose Meraki if:**

* Easy network management is preferred or necessary (such as if the IT team lacks experience), even if the organization is large and distributed.
  + The UniFi Site Manager dashboard simplifies multi-site remote network management while providing high scalability and security.
* Complex and automated security integrations, as well as 24/7 tech/customer support, are desired or necessary. 
 
<hr />

## 4. <a name="supplemental">Supplemental Resources</a>

* *[Cisco Meraki Official Website](https://meraki.cisco.com/)*
* *[Ubiquiti Official Website](https://ui.com/)*
* *[Serverless Architecture Basics Overview Guide](https://github.com/chaseofthejungle/serverless-architecture-basics)*
