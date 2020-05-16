## Validate the ns-3 implementation of TCP Veno using ns-3 DCE
## Course Code: CO365

## Assignment: #14

### Overview
TCP Veno is also targeted to improve the performance of TCP in wireless
environments. It is a combination of Vegas and Reno, and hence, named Veno. In this
project, the aim is to validate ns-3 TCP Veno by implementing it using ns-3-dce-Docker and comparing the results
obtained from it to those obtained by simulating Linux TCP Veno.

### Prerequisites
* Install docker (Link: https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-18-04)
* Pull the docker container (Link: https://hub.docker.com/r/thehajime/ns-3-dce)
* Install gnuplot (Link: https://zoomadmin.com/HowToInstall/UbuntuPackage/gnuplot)

### Recommended Reading:
* Direct Code Execution (Link:
https://www.nsnam.org/overview/projects/direct-code-execution/)
* Linux kernel code (Link:
https://elixir.bootlin.com/linux/v4.4/source/net/ipv4/tcp_veno.c)
* TCP Veno Paper (Link:
https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1177186)
* ns-3 code for TCP Veno (Path: ns-3.xx/src/internet/model/tcp-veno.{h, cc})
* Gnuplot in ns-3 (Link: https://www.nsnam.org/docs/manual/html/gnuplot.html)
