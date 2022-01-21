# Enabling logging on NSX-T distributed IDPS
In this [post](post1-idps.md), I'll show you how you can enable logging with NSX-T distributed IDPS. Logging IDPS events is useful when it comes to troubleshooting

# Installing Palo Alto Cortex XSOAR
I recently had the chance to install Palo Alto Cortex XSOAR and thought I'll document it [here](post2-xsoar.md) for reference

# Using kubectl proxy
Some notes on using [kubectl proxy](post3-kubectlproxy.md)

# Decoding certificates in K8S
[Notes](post4-k8scert.md) on viewing certificates in K8S

# How to view logs for NSX-T Edge Firewall
[Notes](post5-nsxtedge.md) on viewing logs on NSX-T Edge firewall

# Using KASM behind a reverse proxy
I recently deployed KASM on CentOS behind a Contour reverse proxy. There is a [change](post6kasm.md) to the KASM default zone settings for this to work, otherwise you will not be able to successfully launch applications from KASM workspace

# Using crictl and containerd
I recently used containerd instead of Docker for a K8S environment. As Docker commands are not available anymore, this [post](post7crictl.md) explains how to use crictl commands instead.

# Enabling Carbon Black container image scanning
cbctl is the tool from Carbon Black that can be used to scan container images or K8S manifest files for vulnerabilities or security-related issues. This [post](post8cbctl.md) describes how it can be enabled.

# Useful Antrea commands
[Antrea](https://antrea.io) is an open-source CNI from VMware. This [post](post9antrea.md) describes how Antrea is integrated with NSX-T 3.2 and what are some of the features available.
