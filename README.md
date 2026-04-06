**What is a container and Docker Container?**

Container is a bundle of Application, Application libraries that required to run your business application, It packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another. Containers are lightweight which share the host operating system's kernel and libraries, while providing isolation for the application code's and its dependencies.

A Docker container image is a lightweight, standalone, executable package of software which includes everything needed to run an application: code, runtime, system tools, system libraries and settings. This results in a smaller footprint compared to traditional VM's (virtual machines), as the containers do not need to include a full operating system. Docker containers are designed to be minimal, only including what is necessary for the application to run, further reducing their size.

**Containers VS Virtual Machine** 

Containers share the host operating system kernel, making them lighter and faster than VMs. Containers are designed to be portable and can run on any system with a compatible host operating system.
VMs have a full-fledged OS and hypervisor, making them more resource-intensive.VMs are less portable as they need a compatible hypervisor to run.

**Management** 

Containers is typically easier than managing VMs, as containers are designed to be lightweight and fast-moving.
