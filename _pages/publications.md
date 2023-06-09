---
title: "Allan Lab - Publications"
layout: gridlay
excerpt: "Allan Lab -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

## Group highlights

**At the end of this page, you can find the [full list of publications and patents](#full-list-of-publications). All papers are also available on [arXiv](https://arxiv.org/search/?searchtype=author&query=Allan%2C+M+P).**

## Patents
<p>11663290 - Analyzing time series data for sets of devices using machine learning techniques (2023-05-30)<br>11658920 - System and method for autonomous and dynamic resource allocation in storage systems (2023-05-23)<br>11604611 - Variable sparing of disk drives in storage array (2023-03-14)<br>11604701 - System and method for scheduling backup workloads using a trained job resource mapping model (2023-03-14)<br>11599352 - Method of creating an intelligent upgrade flow for a heterogeneous data center (2023-03-07)<br>11599402 - Method and system for reliably forecasting storage disk failure (2023-03-07)<br>11593014 - System and method for approximating replication completion time (2023-02-28)<br>11586368 - Configuring unused SCM memory space to support namespaces based on IO patterns (2023-02-21)<br>11561777 - System and method for intelligent update flow across inter and intra update dependencies (2023-01-24)<br>11561701 - System and method for survival forecasting of disk drives using semi-parametric transfer learning (2023-01-24)<br>11531592 - Method and system for determining favorability of upgrade window (2022-12-20)<br>11520669 - System and method for efficient backup system aware direct data migration between cloud storages (2022-12-06)<br>11513931 - Anomaly aware log retrieval from disk array enclosures (DAEs) (2022-11-29)<br>11507422 - Method and system for intelligently provisioning resources in storage systems (2022-11-22)<br>11507469 - Method and system for risk score based asset data protection using a conformal framework (2022-11-22)<br>11500560 - Method to suggest best SCM configuration based on resource proportionality in a de-duplication based backup storage (2022-11-15)<br>11500712 - Method and system for intelligent proactive error log activation (2022-11-15)<br>11500815 - Dual relationship-based hash structure for non-volatile memory technology (2022-11-15)<br>11494250 - Method and system for variable level of logging based on (long term steady state) system error equilibrium (2022-11-08)<br>11455577 - Automatically allocating device resources using machine learning techniques (2022-09-27)<br>11436104 - Decreasing data restoration times using advanced configuration and power interface (ACPI) (2022-09-06)<br>11436396 - Estimating replication completion time using machine learning techniques (2022-09-06)<br>11422702 - Managing utilization of storage class memory (SCM) resources (2022-08-23)<br>11403186 - Accelerating backup by writing to performance ranked memory (2022-08-02)<br>11403029 - System and method for managing cleaning policies of storage devices in storage device pools using self-monitored statistics and input/output statistics (2022-08-02)<br>11379145 - Systems and methods for selecting devices for backup and restore operations for virtual machines (2022-07-05)<br>11330078 - Method and system for managing updates of a data manager (2022-05-10)<br>11321000 - System and method for variable sparing in RAID groups based on drive failure probability (2022-05-03)<br>11314600 - Data placement method based on health scores (2022-04-26)<br>11243705 - Method and system for policy class based data migration (2022-02-08)<br>11227222 - System and method for prioritizing and preventing backup failures (2022-01-18)<br>11200132 - Anomaly aware log retrieval from disk array enclosures (DAEs) (2021-12-14)<br>11029864 - Method and system for dynamic backup policy handshaking (2021-06-08)<br>11023332 - System and method for efficient backup system aware direct data migration between cloud storages (2021-06-01)<br>11018991 - System and method for autonomous and dynamic resource allocation in storage systems (2021-05-25)<br>10936464 - Method and system for countering capacity shortages on storage systems (2021-03-02)<br>10509586 - System and method for capacity forecasting in backup systems (2019-12-17)<br>&nbsp;</p>

## Full List of publications

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}
