## Installing Cortex XSOAR

Below are some notes I took while installing PANW Cortex XSOAR community edition (version 6.2-1321594) on Ubuntu 18.04 server:
- Do not install docker snap packages while installing Ubuntu. The Demisto installation process will install docker as well
- You need to get the "InRelease" GPG docker public key as follows:

<pre><code>
apt-get update

apt-get install \
    apt-transport-https \
    ca-certificates \
    curl \
    gnupg \
    lsb-release


curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg

echo \
  "deb [arch=amd64 signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu \
  $(lsb_release -cs) InRelease" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
  
apt-get update
</code></pre>


- Note that we use "InRelease" because that is what the Demisto installer uses
- When you run "apt-get update" you may get error messages about some packages missing, just ignore those
