# Enabling logging on NSX-T distributed IDPS - Sept 2021
In this [post](post1-idps.md), I'll show you how you can enable logging with NSX-T distributed IDPS. Logging IDPS events is useful when it comes to troubleshooting

# Installing Palo Alto Cortex XSOAR - Sept 2021
I recently had the chance to install Palo Alto Cortex XSOAR and thought I'll document it [here](post2-xsoar.md) for reference

# Using kubectl proxy - Oct 2021
Some notes on using [kubectl proxy](post3-kubectlproxy.md)

# Decoding certificates in K8S - Oct 2021
[Notes](post4-k8scert.md) on viewing certificates in K8S

# How to view logs for NSX-T Edge Firewall - Nov 2021
[Notes](post5-nsxtedge.md) on viewing logs on NSX-T Edge firewall

# Using KASM behind a reverse proxy - Nov 2021
I recently deployed KASM on CentOS behind a Contour reverse proxy. There is a [change](post6kasm.md) to the KASM default zone settings for this to work, otherwise you will not be able to successfully launch applications from KASM workspace

# Using crictl and containerd - Dec 2021
I recently used containerd instead of Docker for a K8S environment. As Docker commands are not available anymore, this [post](post7crictl.md) explains how to use crictl commands instead.

# Enabling Carbon Black container image scanning - Dec 2021
cbctl is the tool from Carbon Black that can be used to scan container images or K8S manifest files for vulnerabilities or security-related issues. This [post](post8cbctl.md) describes how it can be enabled.

# Useful Antrea commands - Jan 2022
[Antrea](https://antrea.io) is an open-source CNI from VMware. This [post](post9antrea.md) describes some of the useful K8S commands to view Antrea objects

## [Archives](archive.md)
