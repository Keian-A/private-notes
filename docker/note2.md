# What is a container?

A container is simply an isolated environment for running an application. You can have multiple containers up at once to run multiple applications with differing versions of packages with no issues with docker.

What is the difference between a container and a Virtual Machine?
- Container: an isolated environment for running an application.
- VM: An abstraction of a machine (physical hardware).

Hypervisor: A tool used to run multiple VMs. In other words, software we use to create and manage VMs.

Cons of VMS:
- Each version of a VM needs a copy of its own OS 
- Resource intensive
    - Your physical hardware needs to be divided between each VM
- Slow to start

Pros of Containers:
- Allow running multiple apps in isolation
- Are lightweight
- Use OS of the host
- Start quickly
- Need less hardware resources
    - You can run tens to hundreds of containers on a single host

[<-- Docker TOC](./DockerTOC.md)