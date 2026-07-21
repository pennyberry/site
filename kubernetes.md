---
title: Kubernetes
layout: default
nav_order: 3
---

[Kubectl](https://github.com/pennyberry/Public/tree/main/kubectl){: .btn }
[Helm](https://github.com/pennyberry/Public/tree/main/helm){: .btn }

The links above showcase the multitude of applications you can run using kubernetes. I host a 3-VM k3s cluster via my 3-node proxmox cluster at home. This architecture allows for high-availability and fault tollerance across NICs, Disks, RAM, CPU, etc..
To view live stats, head over to my Grafana Dashboards:

[Grafana Dashboard - Pods](https://grafana.joeberry.org/d/85a562078cdf77779eaa1add43ccec1e/kubernetes-compute-resources-namespace-pods?orgId=1&from=now-1h&to=now&timezone=UTC&var-datasource=edvca7b2zijuod&var-cluster=&var-namespace=default&refresh=10s)

[Grafana Dashboard - Networking](https://grafana.joeberry.org/d/8b7a8b326d7a6f1f04244066368c67af/kubernetes-networking-namespace-pods?orgId=1&from=now-1h&to=now&timezone=UTC&var-datasource=edvca7b2zijuod&var-cluster=&var-namespace=$__all&refresh=10s)