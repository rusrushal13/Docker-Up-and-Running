# [Chapter 1: Introduction](https://github.com/rusrushal13/Docker-Up-and-Running-Notes/blob/master/Chapter1.md#chapter-1-introduction)

The first chapter provides us an high level understanding of [Docker](https://github.com/docker/docker), how it begun, explains what it is and how we can use it.

The Docker project is annouced by Solomon Hykes who started this project in Dotcloud. Docker is a tool that promises to easily encapsulate the process of creating a distributable artifact for any application, deploying it at scale into any environment, and streamlining the workflow and responsiveness of agile software organizations.

* It is viewed as a virtualization platform which can competes with technologies like KVM, OpenStack, Xen, Ansible, Chef etc.

* It's solves one of the pain points of the companies - shipping software very fast and easily.Docker helps to build a layer of isolation in software that reduces burdens on the software teams.

* Docker helps in making the softwares more robust. This leads to applications more scalable and reliable. Container Instances can be rolled down very easily and without or very less down-time.

## [Benefits](https://github.com/rusrushal13/Docker-Up-and-Running-Notes/blob/master/Chapter1.md#Benefits)

* Packaging software in a way that leverages the skills developers already have - Docker wraps up all your requirements together into one package that is defined in a single file.

* Bundling all the libraries and binaries in single standard image format - Docker ensures that everything is there what you needed.

* Utilizing the resources as much as possible - Containers are just the process which talks to kernel and utilizes most of the resources available.

## [What it isn't](https://github.com/rusrushal13/Docker-Up-and-Running-Notes/blob/master/Chapter1.md#What-it-isn't)

* Enterprise Virtualization Platform (VMware, KVM etc) - Container is not a virtual machine, containers share the same host kernel i.e utilizes fewer system resources as compared to VM's.

* Cloud Platforms (OpenStack, CloudStack etc) - It can scales in a similar way the cloud does but it handles only deploying, running and managing containers on hosts.

* Configuration Management (Chef, Puppet etc) - Dockerfile doesn't manages the ongoing state of containers or docker host systems, it just defines how should the container looks at build time.

* Deployment Framework (Capistrano, Fabric etc) - It eases the process but can't be used to automate process.

* Workload Management Tool (Mesos, Fleet etc) - There is no cluster management in Docker server, additional orchestration tools needed for it(It only mentions Docker Swarm)

* Development environment (Vagrant etc) - Vagrant have lot of more features than the current state of Docker.