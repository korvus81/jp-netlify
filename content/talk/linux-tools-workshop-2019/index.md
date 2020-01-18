---
title: "Troubleshooting tools and discovery techniques for Linux systems"
date: 2020-06-16T09:00:00-08:00
publishDate: 2020-01-01T00:00:00-08:00
draft: false
publication: O'Reilly Infrastructure and Operations Conference, Santa Clara, CA
abstract: |
  If you are responsible for keeping systems running smoothly, there are several skills that are useful to have. The ability to determine how software works, even if you don't have access to the source code or previous experience with it can be invaluable, as is the ability to determine how software is failing. This training will cover several Linux tools to dig into what is really happening.


---
  
Those entrusted to scale and run software systems have a potentially massive job. Often they are asked to run third party tools with no local experts. Or they are running internally-developed software that is poorly documented and may have unknown performance characteristics under load. Sometimes several pieces of software can come together and produce unexpected behavior, and the team in charge of keeping things running smoothly tends to be the first ones on scene. Without the ability to diagnose what is wrong, it may be hard to even get additional help, because it may not be clear who could help. Part of doing the job well is being good at the detective work required.

This training will go through several tools that can be used in Linux environments to understand what software is doing and how it might be breaking. We will look at:
- the /proc filesystem
- basic performance tools like top and uptime
- networking tools like netstat, ss, tcpdump, and tshark
- tools for looking at system calls, including strace and sysdig
- more detailed performance analysis tools such as those in the sysstat package (iostat, mpstat, etc)
- approaches to debugging programs running in Kubernetes and Docker containers
- basic cgroup investigation

The material will be heavily lab-based so everyone involved will get a chance to run these commands and see how they work.
