## How to view gateway firewall logs in NSX-T Edge

NSX-T Edge nodes are capable of performing stateful firewalling for uplink interfaces or centralized service ports, and this can be done on T0 or T1 routers realized on the edge nodes. The main use case is to control zone to zone traffic or to carry out additional functions like NAT. For example, you may have Tenant-A behind T1-A router and Tenant-B behind T1-B router, and using gateway firewall feature on T1-A and T1-B you can control the traffic between the 2 tenants.

In this post, I'll describe how you can view the gateway firewall logs on NSX-T Edge which comes in to be useful for troubleshooting.

**Step 1** - first enable logging for the specific firewall rule in NSX-T manager via NSX-T manager web interface. In this example, the default rule in my t0-core router is configured to drop all traffic with a white-list model and logging is enabled for the rule.

![gfw01](https://2cloudyskies.github.io/gfw01.png)

![gfw02](https://2cloudyskies.github.io/gfw02.png)

**Step 2** - Identify the active T0 instance on the edge node. For stateful firewalling, the T0/T1 routers need to be deployed in active/standby manner on the edge clusters. 







