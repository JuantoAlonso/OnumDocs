---
description: Falcon Onum installation process
---

# 3-Deployment

## Overview

Once you’ve obtained an Onum account, just a few steps are needed to complete the installation, depending on the type of deployment you require. Onum supports flexible deployment options, including both on-premises and cloud environments.&#x20;

In case you have any question regarding the deployment and installation process, please [contact us](https://app.gitbook.com/s/cSjT21I4EUhzghjc1rER/).

{% hint style="warning" %}
**Supported browsers**

Onum supports the following browsers:

* Google Chrome
{% endhint %}

### Cloud deployment

For cloud-based installations, either our Customer Success team or a partner will access Onum's internal tenant manager and create the new account. All the necessary infrastructure will be set up based on estimated usage metrics.&#x20;

The deployment process is fully automated, ensuring quick and streamlined provisioning and configuration.

{% hint style="warning" %}
**Cloud Listeners**

Note that the Listener configuration process is slightly different if you are using a Cloud deployment. Learn more about Cloud Listeners [in this article](/broken/pages/ZBvczE2SSU071bnFXVaH).
{% endhint %}

### On-premises deployment

In on-premises deployments, either our Customer Success team or a partner will set up the new account. Appropriate access permissions are granted to allow Onum to perform the installation.

A validation script is run to confirm all prerequisites are met and connectivity is established, ensuring a smooth installation process. Once installed, you can access your tenant, start ingesting data, invite users, and take full advantage of Onum’s capabilities.

You must allocate the disk space to `/opt` on the installation machine.

{% hint style="info" %}
**Dependencies:**

* Docker
* Packages:
  * `gpg`
  * `curl`
  * `ipvsadm`
  * `ca-certificates`
* SIEM access
* Access to sources
{% endhint %}

## Hardware requirements

Hardware (per Virtual Machine):

* Distribution: Linux (Debian or Red Hat)
* Server Hardware: 16GB RAM and 8 CPU
* Disk Storage: At least 500GB

## Access

In case of upcoming system maintenance, we kindly seek permission to access the customer infrastructure. We aim to ensure seamless operations and address any potential issues promptly.
