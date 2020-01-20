---
title: "More than a series of tubes: Networking in Kubernetes"
date: 2018-06-13T13:15:00-05:00
draft: false
publication: O'Reilly Velocity Conference, San Jose
abstract: |
  Networking with Docker and Kubernetes is a lot more complex than with traditional servers and virtual machines. Docker uses network namespaces and virtual interfaces to isolate container networks, while Kubernetes may use iptables rules to provide service routing and is commonly deployed with an overlay network (such as Flannel) in order to support a large IP space without having to reconfigure the existing physical network. Beyond that, you can add in network policies if that isn’t confusing enough.
---

{{< youtube bpjfu5MBhgw >}}
  
Networking with Docker and Kubernetes is a lot more complex than with traditional servers and virtual machines. Docker uses network namespaces and virtual interfaces to isolate container networks, while Kubernetes may use iptables rules to provide service routing and is commonly deployed with an overlay network (such as Flannel) in order to support a large IP space without having to reconfigure the existing physical network. Beyond that, you can add in network policies if that isn’t confusing enough.

Jeff Poole offers an overview of the concepts involved and explains what tuning may be required to use Kubernetes successfully. Jeff also covers examples of tracing network traffic through the system and explores special considerations, such as how to determine if you need to adjust the ARP table size on your hosts.


https://conferences.oreilly.com/velocity/vl-ca-2018/public/schedule/detail/66854
