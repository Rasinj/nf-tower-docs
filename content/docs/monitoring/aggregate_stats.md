---
title: Aggregate stats & load
aliases:
- "/docs/monitoring/stats-load-utilization"
weight: 1
layout: single
publishdate: 2020-10-20 04:00:00 +0000
authors:
  - "Evan Floden"
  - "Alain Coletta"
  - "Seqera Labs"

headline: 'Aggregated stats and resources used by the workflow'
description: 'Monitoring a Nextflow pipeline executed through Tower.nf'

menu:
  docs:
    parent: Monitoring Pipelines
    weight: 5
---

The **aggregate stats** section is a real-time summary of the resources used by the workflow. These include total running time ('wall time'), aggregated CPU, memory usage, i/o data, and cost.
{{% pretty_screenshot img="/uploads/2020/10/monitoring_aggregate_stats.png" %}}
{{% tip %}}
Note the estimated cost is only based on computation usage and does not currently take into account storage or associated network costs.
{{% /tip %}}


### Load and Utilization sections

As processes are being submitted to the compute environment, the **Load** and **Utilization** sections allow the user to monitor how many cores, memory and CPUs are being used as well as how many processes tasks are being computed.

{{% pretty_screenshot img="/uploads/2020/10/monitoring_load.png" %}}