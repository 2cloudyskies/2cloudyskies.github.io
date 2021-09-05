## Viewing pod information using crictl

I recently used containerd instead of Docker for the container runtime in a K8S cluster. I was familiar with the usual <span style="color:blue">docker ps</span>, <span style="color:blue">docker logs <container-id></span> commands but was trying to figure out how to do the same with containerd. [crictl](https://github.com/kubernetes-sigs/cri-tools/blob/master/docs/crictl.md) came to the rescue

**Step 1** - Create a /etc/crictl.yaml file as follows

<pre><code> test </code></pre>

**Step 2** - Run the commands

