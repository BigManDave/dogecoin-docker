# DogecoinD Docker Image
  This is an x86 Docker image for running a DogecoinD 1.14.4 FullNode based on Ubuntu.

  Requirements:
  - Port 22556 added to the container and forwarded by your router. (uPnP is untested but may be a possible alternative to port forwarding. See dogecoin.conf https://bit.ly/3gNQrCr)
  - Container path /etc/doge/ mapped to host where blockchain data will be stored.
  - In the same path dogecoin.conf file should be created. See this repository for template.