## How to install and use cbctl for container image/K8S manifest scanning

The official documentation describing how to install and use cbctl is [here](https://docs.vmware.com/en/VMware-Carbon-Black-Cloud/services/carbon-black-cloud-user-guide/GUID-EF1FEFFE-AAEB-418E-80AC-CCE4494E99B7.html). This post aims to provide a more pictorial view of the installation process with some screenshots. 


**Step 1** - Login into CB cloud and create a CLI configuration
Go to Inventory > Kubernetes > K8S Clusters > CLI config . Give your CLI config a name that you can identify and a built step, for e.g. development

![cbctl1](https://2cloudyskies.github.io/cbct1.png)



**Step 3** - You can see firewall logs using the command below

<pre><code>edge01>edge01> <span style="color:blue">get log-file syslog follow</span>
 
2021-08-19T02:37:29.031Z edge01.lab01.one NSX 5055 FIREWALL [nsx@6876 comp="nsx-edge" subcomp="datapathd" s2comp="firewallpkt" level="INFO"] <3 a91a35d4acea4843:8b0fb4b8b5fe50a4> INET reason-match DROP 1001 OUT 84 PROTO 1 172.16.20.10->172.16.5.1</code></pre>
