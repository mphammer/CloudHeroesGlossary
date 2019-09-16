# The Cloud Glossary
##### *By [Cloud Heroes](https://medium.com/cloud-heroes)*

#### Here is a list of terms, phrases, and other things that we frequently hear as Cloud Engineers. Each item has a small, practical description with just enough to understand what it is and why/how it's used.  
#### THE GOAL of this gloassary is to be a quick, insightful refernece on your journey from noob to Cloud Hero.
---

### Alpine Linux:  
__Cloud Example:__ Docker provides an image based on Alpine Linux that allows you to have a Docker Container with that Operating System.  
### Ansible:  
### Apache:   
### Aurora:  
### Borg:  
### Buildah:  
### Busy Box:  
__Description:__ BusyBox is a software suite that provides several Unix utilities in a single executable file [src](https://en.wikipedia.org/wiki/BusyBox) such as ls, chmod, wget, cat, etc. It's designed to run in an environment with a Linux Kernel. [src](https://www.quora.com/What-is-busybox).  
__Cloud Relevance:__ Busy Box can be put into an image so that processes in your container have the suite of utilities that it provides. It is also size-optimized which makes it desirable for containers (which you want to be lightweight).  
### CloudFlare SSL (CFSSL):  
__Description:__ An application by CloudFlare that can provide a SSL Certificate and a Certificate Authority. [src](https://blog.cloudflare.com/introducing-cfssl/)  
__Cloud Example:__ It's common to have a container with CFSSL in it that other containers/microservices use to generate Certificate Authorities.  
### Cloud Native:  
__Description:__ "Cloud-native is an approach to building and running applications that exploits the advantages of the cloud computing delivery model". The cloud computing delivery model includes using DevOps, CI/CD, Microservices, and Containers. The main advantages are scalability of applications and rapid development of features.  [src](https://pivotal.io/cloud-native)  
### Cluster: 
__Description:__ A group of Nodes that are linked together. Where a node is a physical system in a computer network.  
### Cluster Orchestration System:  
### Cloud Native Computing Foundation (CNCF):  
### Container: 
__Description:__ A unit of software that includes the program and all its dependencies. It's like a little environment for a process to run that's separate from other processes. They are made with Cgroups, Namespaces, and a File System. [src](https://www.docker.com/resources/what-container)  
### Container Control Groups (Cgroups): 
__Description:__ (Note: A group is a set of processes). Cgroups are a feature of a kernel that can limit the amount of resources for a group (memory, CPU, etc.), prioritize which groups get resources, record metrics of resource usage, and set conditions by which groups can run. [src](https://www.youtube.com/watch?v=2ZdJ_3sBr6A) [src](https://en.wikipedia.org/wiki/Cgroups) [src](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/6/html/resource_management_guide/ch01)  
### Container Namespaces: 
__Description:__ Essentially identifiers in a kernel that define what kernel resources (network, filesystem, uts, pid, user) belong together. This allows you to group a set of resources together into little environments. You can then run a different processes in their own isolated environment (aka containers). [src](https://www.youtube.com/watch?v=2ZdJ_3sBr6A) [src](https://en.wikipedia.org/wiki/Linux_namespaces)  
### Container Image: 
__Description:__ An image that becomes a container when run in a Container Runtime. [src](https://www.docker.com/resources/what-container)  
### Container Runtime: 
__Description:__ Software that runs on a node to manage containers on that node. It's responsible for running all parts of the container besides the actual program. Examples are Docker, CRI-O, and Containerd. [src](https://kubernetes.io/blog/2017/11/containerd-container-runtime-options-kubernetes/) [src](https://www.ianlewis.org/en/container-runtimes-part-1-introduction-container-r?source=post_page---------------------------)  
### Containerd: 
__Description:__ A Container Runtime that follows Open Container Initiative (OCI) guidelines. [src](https://kubernetes.io/blog/2017/11/containerd-container-runtime-options-kubernetes/)  
### Continuous Integration (CI):  
__Description:__ "Continuous integration is a software development practice where developers regularly merge their code changes into a central repository, after which automated builds and tests are run. The key goals of continuous integration are to find and address bugs quicker, improve software quality, and reduce the time it takes to validate and release new software updates." [src](https://aws.amazon.com/devops/what-is-devops/)
### Continuous Integration / Continuous Delivery (CICD or CI/CD):  
### Continuous Integration / Continuous Delivery (CICD or CI/CD) Pipeline:  
### Continuous Delivery (CD):  
__Description:__ "Continuous delivery is a software development practice where code changes are automatically built, tested, and prepared for a release to production. It expands upon continuous integration by deploying all code changes to a testing environment and/or a production environment after the build stage. When continuous delivery is implemented properly, developers will always have a deployment-ready build artifact that has passed through a standardized test process." [src](https://aws.amazon.com/devops/what-is-devops/)
### CoreOS: 
__Description:__ A company with various cloud products that was bought by RedHat.  
### CoreOS Operating System (Container Linux): 
__Description:__ A lightweight Linux Operating System that can be run in containers. [src](https://www.quora.com/What-is-CoreOS)  
### CoreOS Rocket (rkt):  
### CoreOS Tectonic: 
__Description:__ A platform that provides users with Kuberentes that's running CoreOs technologies.  
### CRI-O: 
__Description:__ A Container Runtime that can run any container that follows the Open Container Initiative (OCI) guidelines. CRI-O stands for **C**ontainer **R**untime **I**nterface for **O**pen Container Initiative. [src](https://www.redhat.com/en/blog/introducing-cri-o-10)  
### Debian: 
__Description:__ A Linux Distribution (aka an Operating System that uses the Linux kernel).   
### Declarative:
__Description:__  [src](https://stackoverflow.com/questions/47369351/kubectl-apply-vs-kubectl-create)  
### Development Operations (DevOps): 
__Description:__ DevOps is a term that means the Development team (Dev - codes the application) and Information Technology Operations Team (Ops - manages real world instances of the application) work closely together throughout the software development process to increase productivity and performance. They will use techniques such as CI/CD, Microservices, Infrastructure as Code, and Monitoring/Logging. This allows the development team to rapidly implement changes based on Ops Team findings and customer feedback. [src](https://aws.amazon.com/devops/what-is-devops/)  
__Cloud Example:__ The Dev Team submits a small feature or resolves a bug in an appliation. Using CI/CD and Infrastructure as Code, a cloud is automatically created and the application is deployed/tested. If something goes wrong, the Ops team uses monitoring/logging to determine the issue and quickly tell the Dev Team. The Dev Team will then fix the bug and submit it which causes the process to start over again.  
### Docker: 
__Description:__ A company.  
### Docker Container: 
__Description:__ A container that is running in the Docker Engine Container Runtime. [src](https://www.docker.com/resources/what-container)  
### Docker Compose:  
### Docker Daemon:  
### Docker Engine: 
__Description:__ The Container Runtime for running Docker containers. [src](https://www.docker.com/products/container-runtime)  
### Docker Swarm:   
### DockerHub:  
### Envoy:  
### Ephemeral: 
__Description:__ Lasting for a very short time.  
__Cloud Example:__ Kubernetes pods are ephemeral because they can easily be deleted (Ex: If all containers in the pod crash then the pod will be removed from the cluster). [src](https://www.google.com/search?q=define+ephemeral&oq=define+ephemeral&aqs=chrome..69i57j0l5.2535j1j9&sourceid=chrome&ie=UTF-8)  
### Etcd:  
### Eventstore:  
### Flocker:  
### Git:  
__Description:__ A Version Control System (VCS).  
### GitHub:   
__Description:__  A web based Git Repsoitory.  
__Cloud Example:__ Your team can collaborate together on microservices using a remote GitHub repo.
### GitLab:  
__Description:__  A web based Git Repsoitory.  
__Cloud Relevance:__ A key difference between GitLab and GitHub, is that GitLab provides a lot of support for CI/CD.  
__Cloud Example:__ Your team can collaborate together using a remote GitLab repo. When you push/submit changes to the repo, CI/CD automation can be triggered that tests your software in cloud environments like Kubernetes and Openshift.  
### Golang:  
### Google Cloud Platform (GCP):  
### Google Kubernetes Engine:  
### Hashicorp:  
### Heroku:  
### Heavyweight Operating System: 
__Description:__ An Operating System that runs processes as opposed to threads. The advantage of processes over threads is that process don't share memory so they don't need to worry about competing for resources and other risks of multithreading. [src](https://stackoverflow.com/questions/6004069/lightweight-vs-heavyweight-processes)  
### Helm:  
### Helm Chart:  
### Heptio:  
### Hypervisor:  
### Iternational Business Machines (IBM):  
__Description:__ The largest computer company in the world.  
__Cloud Relevance:__ They are a large force in the Cloud World. They stay competitive by doing things like aqcuiring RedHat.  
### Image:  
### Image Layer:  
### Imperative:
__Description:__  [src](https://stackoverflow.com/questions/47369351/kubectl-apply-vs-kubectl-create)  
### Infrastructure as Code: 
__Description:__ "Infrastructure as code is a practice in which infrastructure is provisioned and managed using code and software development techniques, such as version control and continuous integration. The cloud’s API-driven model enables developers and system administrators to interact with infrastructure programmatically, and at scale, instead of needing to manually set up and configure resources. Thus, engineers can interface with infrastructure using code-based tools and treat infrastructure in a manner similar to how they treat application code. Because they are defined by code, infrastructure and servers can quickly be deployed using standardized patterns, updated with the latest patches and versions, or duplicated in repeatable ways." [src](https://aws.amazon.com/devops/what-is-devops/)  
__Cloud Example:__ A program is run that creates a Kubernetes cluster with X nodes and Y CPUs, and names the cluster Z. X, Y, and Z are variables that are passed into the program. 
### Ingress:  
### Istio:  
__Description:__ An Open Source Service Mesh provided by Google Cloud. [src](https://cloud.google.com/istio/) It uses the Envoy Proxy.  
### Jenkins:  
### Joe Beda:  
### Kata Container:  
### Kelsie Hightower:  
### Kernel: 
__Description:__ The Kernel is the interface between applications, CPU/memory, and other hardware I/O devices. It runs behind the scenes when you interact with your computer and its Operating System. The Kernel is responsible for managing processes for applications, interacting with memory, managing memory, allocating memory, managing devices through device drivers, and executing system calls (sort of like commands you enter in the terminal). [src](https://www.techopedia.com/definition/3277/kernel)  
### Kind:  
### Knative:  
### Kubernetes:  
### Kubernetes Cluster Role:  
### Kubernetes Cluster Role Binding:  
### Kubernetes Container Runtime Interface (CRI):  
### Kubernetes Endpoint:  
### Kubernetes Service: 
__Description:__ A Service is a Kubernetes REST Resource that specifies a policy (or rules) for directing networking data. [src](https://medium.com/cloud-heroes/the-kubernetes-service-basics-2756cb6e455f)  
### Kubernetes Role:  
### Kubernetes Role Binding:  
### Kubernetes Service Accounts:  
### Kubelet:  
### Kube Proxy:  
### Kustomize:  
### Lightweight Operating System: 
__Description:__ An Operating System that runs threads as opposed to processes. The advantage of threads over processes is that threads share a common memory so an entire set of memory isn't needed for each one. [src](https://stackoverflow.com/questions/6004069/lightweight-vs-heavyweight-processes)  
### Linkerd:  
### Linux: 
__Description:__ This term can either describe the Linux Operating System (OS) or just the Linux Kernel (the Kernel is a component of the OS).  
__Cloud Note:__ Linux is so popular in the Cloud World because it was the first Kernel/OS to provide containers. The Linux Kernel is able to manage Cgroups, Namespaces, and File Systems (aka the essential building blocks of a container). 
### Linux Distribution (distro): 
__Description:__ An operating system made from a collection of software on top of the Linux Kernel. [src](https://en.wikipedia.org/wiki/Linux_distribution)  
### Linux Kernel:  
### Linux Operating System (OS):  
__Description:__ "The Linux open source operating system, or Linux OS, is a freely distributable, cross-platform operating system based on Unix that can be installed on PCs, laptops, netbooks, mobile and tablet devices, video game consoles, servers, supercomputers and more." [src](https://www.webopedia.com/TERM/L/linux_os.html)
### Mesos:  
### Microservices:  
__Description:__ "The microservices architecture is a design approach to build a single application as a set of small services. Each service runs in its own process and communicates with other services through a well-defined interface using a lightweight mechanism, typically an HTTP-based application programming interface (API). Microservices are built around business capabilities; each service is scoped to a single purpose. You can use different frameworks or programming languages to write microservices and deploy them independently, as a single service, or as a group of services." [src](https://aws.amazon.com/devops/what-is-devops/)
### Microsoft Azure:  
### Minikube:  
### Minishift:  
### Minio:  
### Monolith:  
### Multi Tenant:  
### Network File System (NFS):  
__Cloud Example:__ Amazon Elastic File System (EFS), Google Cloud Filestore
### Nginx:  
### Node: 
__Description:__ A physical system in a computer network.  
### Open Container Initiative (OCI):  
### Openshift Route:  
### Openstack:  
### Operating System: 
__Description:__ The Operating System is the primary software on your computer that manages all the software and hardware. It is the glue that connects everything in your computer together and allows them to interact. It handles things like receiving mouse clicks, handling Wi-Fi radio, displaying things on the monitor, managing memory, running programs/commands, etc. [src](https://www.howtogeek.com/361572/what-is-an-operating-system/) They are commonly talked about in the Cloud because containers can each have their own Lightweight Operating Systems.  
### Operator:  
### Operator SDK:  
### Peleton:  
### Pivotal:  
### Pivotal's Cloud Foundry:  
### Prometheus:  
### Prow:  
### Publish Subscribe (Pub/Sub) Patter:  
### Puppet:  
### RabbitMQ:  
### RedHat: 
__Description:__ A company with various cloud products that was bought by IBM.  
### RedHat's Openshift: 
__Description:__ RedHat's container platform that runs Kubernetes. Essentially it's Kubernetes with extra features. [src](https://www.openshift.com/learn/what-is-openshift)  
### Role Based Access Control (RBAC): 
__Description:__ A security protocol that restricts access to resources by giving Roles to users. A Role is allowed to do certain things. Thus, what a user can do is based on what role it has. [src](https://digitalguardian.com/blog/what-role-based-access-control-rbac-examples-benefits-and-more)  
### Service Mesh: 
__Description:__ An Infrastructure Layer for microservices. [src](https://medium.com/cloud-heroes/cloud-simplified-service-mesh-basics-542fef25024d)  
### Service Mesh Side Car: 
__Description:__ An implementation of a Service Mesh where every unit gets a "Side Car" that handles networking for the unit that it's paired with.  
### SSL Certificates: 
__Description:__ "SSL certificates form the core of trust on the web by assuring the identity of websites. This trust is built by digitally binding a cryptographic key to an organization’s identity. An SSL certificate will bind domain names to server names, and company names to locations. This ensures that if you go to your bank’s web site, for example, you know for sure it is your bank, and you are not giving out your information to a phishing scam." (where a certificate is a file that contains a Public Key) [src](https://blog.cloudflare.com/introducing-cfssl/)  
__Cloud Example:__ These are commonly used in the Cloud when networking between components. You could have a container that generates certificates for you application to use.  
### Stateless:  
### Systemd:  
### S3 Bucket:  
### Terraform:  
### Travis:  
### Tupperware:  
### Ubuntu: 
__Description:__ A Linux Distribution (aka an Operating System that uses the Linux kernel).   
### Vault:  
### Virtual Machine:  
### VMWare:  
### WeaveWorks:  
### Yaml:  