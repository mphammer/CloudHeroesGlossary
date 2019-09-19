# The Cloud Glossary
##### *By [Cloud Heroes](https://medium.com/cloud-heroes)*

#### Here is a list of terms, phrases, and other things that we frequently hear as Cloud Engineers. Each item has a small, practical description with just enough to understand what it is and why/how it's used.  
#### THE GOAL of this gloassary is to be a quick, insightful refernece on your journey from noob to Cloud Hero.
---

### Alpine Linux:  
* __Cloud Example:__ Docker provides an image based on Alpine Linux that allows you to have a Docker Container with that Operating System.  
### Amazon Simple Storage Service (S3):  
### Ansible:  
### Apache:   
### Aurora:  
### Borg:  
### Buildah:  
### Busy Box:  
* __Description:__ BusyBox is a software suite that provides several Unix utilities in a single executable file [src](https://en.wikipedia.org/wiki/BusyBox) such as ls, chmod, wget, cat, etc. It's designed to run in an environment with a Linux Kernel. [src](https://www.quora.com/What-is-busybox).  
* __Cloud Relevance:__ Busy Box can be put into an image so that processes in your container have the suite of utilities that it provides. It is also size-optimized which makes it desirable for containers (which you want to be lightweight).  
### CloudFlare SSL (CFSSL):  
* __Description:__ An application by CloudFlare that can provide a SSL Certificate and a Certificate Authority. [src](https://blog.cloudflare.com/introducing-cfssl/)  
* __Cloud Example:__ It's common to have a container with CFSSL in it that other containers/microservices use to generate Certificate Authorities.  
### Cloud Native:  
* __Description:__ "Cloud-native is an approach to building and running applications that exploits the advantages of the cloud computing delivery model". The cloud computing delivery model includes using DevOps, CI/CD, Microservices, and Containers. The main advantages are scalability of applications and rapid development of features.  [src](https://pivotal.io/cloud-native)  
### Cluster: 
* __Description:__ A group of Nodes that are linked together. Where a node is a physical system in a computer network.  
### Cluster Orchestration System:  
### Cloud Native Computing Foundation (CNCF):  
### Consul:  
### Container: 
* __Description:__ A unit of software that includes the program and all its dependencies. It's like a little environment for a process to run that's separate from other processes. They are made with Cgroups, Namespaces, and a File System. [src](https://www.docker.com/resources/what-container)  
### Container Control Groups (Cgroups): 
* __Description:__ (Note: A group is a set of processes). Cgroups are a feature of a kernel that can limit the amount of resources for a group (memory, CPU, etc.), prioritize which groups get resources, record metrics of resource usage, and set conditions by which groups can run. [src](https://www.youtube.com/watch?v=2ZdJ_3sBr6A) [src](https://en.wikipedia.org/wiki/Cgroups) [src](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/6/html/resource_management_guide/ch01)  
### Container Namespaces: 
* __Description:__ Essentially identifiers in a kernel that define what kernel resources (network, filesystem, uts, pid, user) belong together. This allows you to group a set of resources together into little environments. You can then run a different processes in their own isolated environment (aka containers). [src](https://www.youtube.com/watch?v=2ZdJ_3sBr6A) [src](https://en.wikipedia.org/wiki/Linux_namespaces)  
### Container Image: 
* __Description:__ An image that becomes a container when run in a Container Runtime. [src](https://www.docker.com/resources/what-container)  
### Container Runtime: 
* __Description:__ Software that runs on a node to manage containers on that node. It's responsible for running all parts of the container besides the actual program. Examples are Docker, CRI-O, and Containerd. [src](https://kubernetes.io/blog/2017/11/containerd-container-runtime-options-kubernetes/) [src](https://www.ianlewis.org/en/container-runtimes-part-1-introduction-container-r?source=post_page---------------------------)  
### Containerd: 
* __Description:__ A Container Runtime that follows Open Container Initiative (OCI) guidelines. [src](https://kubernetes.io/blog/2017/11/containerd-container-runtime-options-kubernetes/)  
### Continuous Integration (CI):  
* __Description:__ "Continuous integration is a software development practice where developers regularly merge their code changes into a central repository, after which automated builds and tests are run. The key goals of continuous integration are to find and address bugs quicker, improve software quality, and reduce the time it takes to validate and release new software updates." [src](https://aws.amazon.com/devops/what-is-devops/)
### Continuous Integration / Continuous Delivery (CICD or CI/CD):  
### Continuous Integration / Continuous Delivery (CICD or CI/CD) Pipeline:  
### Continuous Delivery (CD):  
* __Description:__ "Continuous delivery is a software development practice where code changes are automatically built, tested, and prepared for a release to production. It expands upon continuous integration by deploying all code changes to a testing environment and/or a production environment after the build stage. When continuous delivery is implemented properly, developers will always have a deployment-ready build artifact that has passed through a standardized test process." [src](https://aws.amazon.com/devops/what-is-devops/)
### CoreOS: 
* __Description:__ A company with various cloud products that was bought by RedHat.  
### CoreOS Operating System (Container Linux): 
* __Description:__ A lightweight Linux Operating System that can be run in containers. [src](https://www.quora.com/What-is-CoreOS)  
### CoreOS Rocket (rkt):  
### CoreOS Tectonic: 
* __Description:__ A platform that provides users with Kuberentes that's running CoreOs technologies.  
### Create Read Update Delete (CRUD):  
### CRI-O: 
* __Description:__ A Container Runtime that can run any container that follows the Open Container Initiative (OCI) guidelines. CRI-O stands for **C**ontainer **R**untime **I**nterface for **O**pen Container Initiative. [src](https://www.redhat.com/en/blog/introducing-cri-o-10)  
### Debian: 
* __Description:__ A Linux Distribution (aka an Operating System that uses the Linux kernel).   
### Declarative:
* __Description:__  [src](https://stackoverflow.com/questions/47369351/kubectl-apply-vs-kubectl-create)  
### Development Operations (DevOps): 
* __Description:__ DevOps is a term that means the Development team (Dev - codes the application) and Information Technology Operations Team (Ops - manages real world instances of the application) work closely together throughout the software development process to increase productivity and performance. They will use techniques such as CI/CD, Microservices, Infrastructure as Code, and Monitoring/Logging. This allows the development team to rapidly implement changes based on Ops Team findings and customer feedback. [src](https://aws.amazon.com/devops/what-is-devops/)  
* __Cloud Example:__ The Dev Team submits a small feature or resolves a bug in an appliation. Using CI/CD and Infrastructure as Code, a cloud is automatically created and the application is deployed/tested. If something goes wrong, the Ops team uses monitoring/logging to determine the issue and quickly tell the Dev Team. The Dev Team will then fix the bug and submit it which causes the process to start over again.  
### Docker: 
* __Description:__ A company.  
### Docker Container: 
* __Description:__ A container that is running in the Docker Engine Container Runtime. [src](https://www.docker.com/resources/what-container)  
### Docker Compose:  
### Docker Daemon:  
### Docker Engine: 
* __Description:__ The Container Runtime for running Docker containers. [src](https://www.docker.com/products/container-runtime)  
### Docker Swarm:   
### DockerHub:  
### Envoy:  
### Ephemeral:  
* __Description:__ Lasting for a very short time.  
* __Cloud Example:__ Kubernetes pods are ephemeral because they can easily be deleted (Ex: If all containers in the pod crash then the pod will be removed from the cluster). [src](https://www.google.com/search?q=define+ephemeral&oq=define+ephemeral&aqs=chrome..69i57j0l5.2535j1j9&sourceid=chrome&ie=UTF-8)  
### Etcd:  
### Eventstore:  
### File System (NAS):  
* __Cloud Relevance:__ As capacity grows (scaling) File Systems lack in performance when compared to other models like Object Storage - you have limited space in your filesystem. 
### Flocker:  
### Git:  
* __Description:__ A Version Control System (VCS).  
### GitHub:   
* __Description:__  A web based Git Repsoitory.  
* __Cloud Example:__ Your team can collaborate together on microservices using a remote GitHub repo.
### GitLab:  
* __Description:__  A web based Git Repsoitory.  
* __Cloud Relevance:__ A key difference between GitLab and GitHub, is that GitLab provides a lot of support for CI/CD.  
* __Cloud Example:__ Your team can collaborate together using a remote GitLab repo. When you push/submit changes to the repo, CI/CD automation can be triggered that tests your software in cloud environments like Kubernetes and Openshift.  
### Golang:  
### Google Cloud Platform (GCP):  
### Google Kubernetes Engine:  
### Hashicorp:  
### Heroku:  
### Heavyweight Operating System: 
* __Description:__ An Operating System that runs processes as opposed to threads. The advantage of processes over threads is that process don't share memory so they don't need to worry about competing for resources and other risks of multithreading. [src](https://stackoverflow.com/questions/6004069/lightweight-vs-heavyweight-processes)  
### Helm:  
### Helm Chart:  
### Heptio:  
### Hypervisor:  
### Iternational Business Machines (IBM):  
* __Description:__ The largest computer company in the world.  
* __Cloud Relevance:__ They are a large force in the Cloud World. They stay competitive by doing things like aqcuiring RedHat.  
### Image:  
### Image Layer:  
### Imperative:
* __Description:__  [src](https://stackoverflow.com/questions/47369351/kubectl-apply-vs-kubectl-create)  
### Infrastructure as Code: 
* __Description:__ "Infrastructure as code is a practice in which infrastructure is provisioned and managed using code and software development techniques, such as version control and continuous integration. The cloud’s API-driven model enables developers and system administrators to interact with infrastructure programmatically, and at scale, instead of needing to manually set up and configure resources. Thus, engineers can interface with infrastructure using code-based tools and treat infrastructure in a manner similar to how they treat application code. Because they are defined by code, infrastructure and servers can quickly be deployed using standardized patterns, updated with the latest patches and versions, or duplicated in repeatable ways." [src](https://aws.amazon.com/devops/what-is-devops/)  
* __Cloud Example:__ A program is run that creates a Kubernetes cluster with X nodes and Y CPUs, and names the cluster Z. X, Y, and Z are variables that are passed into the program. 
### Ingress:  
### Istio:  
* __Description:__ An Open Source Service Mesh provided by Google Cloud. [src](https://cloud.google.com/istio/) It uses the Envoy Proxy.  
### Jenkins:  
### Joe Beda:  
### Kata Container:  
### Kelsie Hightower:  
### Kernel: 
* __Description:__ The Kernel is the interface between applications, CPU/memory, and other hardware I/O devices. It runs behind the scenes when you interact with your computer and its Operating System. The Kernel is responsible for managing processes for applications, interacting with memory, managing memory, allocating memory, managing devices through device drivers, and executing system calls (sort of like commands you enter in the terminal). [src](https://www.techopedia.com/definition/3277/kernel)  
### Kind:  
### Knative: 
* __Description:__ An Open Source suite of tools for Kubernetes that make it easier for developers to use serverless applications in their cluster and simplify management/configuration of Kubernetes. It has three main components: Build - turn source code into containers that can be run in the cluster; Serve - configure and scale your containers, and route networking to a subset of your containers; Event - it can perform functions based on events it observes ([src](https://www.ibm.com/cloud/learn/knative)). Knative runs in your cluster, and uses CRDs and listens to API events.  
* __Cloud Examples:__ Autoscaling workloads; Building containers from source code; Stateless computing; Installing dependencies; Configuring networking rules to route traffic; Generating config files; Setting up logging; and more...  
* __Use Case:__ CI/CD Pipeline. Instead of maintining your own custom CI/CD Pipeline architecture with a tool like Jenkins, you can use the framework provided by Knative. By defining a set of Knative's CRDs (like Pipeline or Tasks) you can configure it to execute your CI/CD workflow.  
### Kops (Kubernetes Operations):  
* __Description:__ The kops tool helps you create, destroy, upgrade and maintain production-grade, highly available, Kubernetes clusters from the command line. They describe the tool as "kubectl" but for clusters. [src](https://github.com/kubernetes/kops)  
### Kubernetes:  
### Kubernetes Cluster Role:  
### Kubernetes Cluster Role Binding:  
### Kubernetes Container Runtime Interface (CRI):  
### Kubernetes Custom Resource Definition (CRD):  
### Kubernetes Endpoint:  
### Kubernetes Liveness Probe:   
* __Description:__ This is a configuration in a Pod's YAML that tells kublet how to check if the Pod is healthy. For example, it can require that every 5 seconds the kublet should execute a command in the container, perform an HTTP request to the server in a containter, or do a TCP request to the container. The kublet will recieve a success or failure response. If it receives a failure response it will then kill the container. [src](https://kubernetes.io/docs/tasks/configure-pod-container/configure-liveness-readiness-probes/)   
### Kubernetes Readiness Probe:  
* __Description:__ This is a configuration in a Pod to tell Kubernetes how to know when a Pod is ready to receive networking traffic from Kubernetes Services. The check can be through executing a command in the containerr, performing an HTTP request to the server in the conatiner, or a TCP request.     
* __Use Cases:__ If your application is currently processing a large amount of data you may not want to keep sending network traffic to it until it's finished. If your application depends on external services you may not want to send it network traffic yet. [src](https://kubernetes.io/docs/tasks/configure-pod-container/configure-liveness-readiness-probes/)  
### Kubernetes Role:  
### Kubernetes Role Binding:  
### Kubernetes Service: 
* __Description:__ A Service is a Kubernetes REST Resource that specifies a policy (or rules) for directing networking data. [src](https://medium.com/cloud-heroes/the-kubernetes-service-basics-2756cb6e455f)  
### Kubernetes Service Accounts:  
### Kubelet:  
### Kube Proxy:  
### Kustomize:  
### Lightweight Operating System: 
* __Description:__ An Operating System that runs threads as opposed to processes. The advantage of threads over processes is that threads share a common memory so an entire set of memory isn't needed for each one. [src](https://stackoverflow.com/questions/6004069/lightweight-vs-heavyweight-processes)  
### Linkerd:  
### Linux: 
* __Description:__ This term can either describe the Linux Operating System (OS) or just the Linux Kernel (the Kernel is a component of the OS).  
* __Cloud Note:__ Linux is so popular in the Cloud World because it was the first Kernel/OS to provide containers. The Linux Kernel is able to manage Cgroups, Namespaces, and File Systems (aka the essential building blocks of a container). 
### Linux Distribution (distro): 
* __Description:__ An operating system made from a collection of software on top of the Linux Kernel. [src](https://en.wikipedia.org/wiki/Linux_distribution)  
### Linux Kernel:  
### Linux Operating System (OS):  
* __Description:__ "The Linux open source operating system, or Linux OS, is a freely distributable, cross-platform operating system based on Unix that can be installed on PCs, laptops, netbooks, mobile and tablet devices, video game consoles, servers, supercomputers and more." [src](https://www.webopedia.com/TERM/L/linux_os.html)  
### List-Watch Pattern:  
* __Description:__ A reconciliation method where you continusously or periodically list a set of resources in order to determine what has changed and what needs to be done to restore the correct state.  [src](https://speakerdeck.com/thockin/kubernetes-what-is-reconciliation?slide=95)
### Mesos:  
### Microservices:  
* __Description:__ "The microservices architecture is a design approach to build a single application as a set of small services. Each service runs in its own process and communicates with other services through a well-defined interface using a lightweight mechanism, typically an HTTP-based application programming interface (API). Microservices are built around business capabilities; each service is scoped to a single purpose. You can use different frameworks or programming languages to write microservices and deploy them independently, as a single service, or as a group of services." [src](https://aws.amazon.com/devops/what-is-devops/)
### Microsoft Azure:  
### Minikube:  
### Minishift:  
### Minio:  
### MongoDB:  
### Monolith:  
### Multi Tenant:  
### Network File System (NFS):  
* __Cloud Example:__ Amazon Elastic File System (EFS), Google Cloud Filestore
### Nginx:  
### Node:  
* __Description:__ A physical system in a computer network.  
### NoSQL:  
### Object Store: 
* __Description:__ Object storage (also known as object-based storage) is a computer data storage architecture that manages data as objects, as opposed to other storage architectures like file systems which manages data as a file hierarchy, and block storage which manages data as blocks within sectors and tracks. Each object typically includes the data itself, a variable amount of metadata, and a globally unique identifier. [src](https://en.wikipedia.org/wiki/Object_storage)  
* __Cloud Relevance:__ This storage is beneficial for scalability - since the objects are stored in a flat address space, you can simply add more nodes to get more room.  
### Open Container Initiative (OCI):  
### Openshift Route:  
### Openstack:  
### Operating System: 
* __Description:__ The Operating System is the primary software on your computer that manages all the software and hardware. It is the glue that connects everything in your computer together and allows them to interact. It handles things like receiving mouse clicks, handling Wi-Fi radio, displaying things on the monitor, managing memory, running programs/commands, etc. [src](https://www.howtogeek.com/361572/what-is-an-operating-system/) They are commonly talked about in the Cloud because containers can each have their own Lightweight Operating Systems.  
### Operator:  
### Operator SDK:  
### Peleton:  
### Pivotal:  
### Pivotal's Cloud Foundry:  
### Podman:  
### Prometheus:  
### Prow:  
### Publish Subscribe (Pub/Sub) Patter:  
### Puppet:  
### RabbitMQ:  
### Reconciliation:  
* __Description:__ The process of ensuring that two sets of records are in agreement.  
* __Cloud Relevance:__ Controllers in Kubernetes have a reconciliation process. You tell it what you want in the cluster and it ensures that is what is acutally running in the cluster.  
### RedHat: 
* __Description:__ A company with various cloud products that was bought by IBM.  
### RedHat's Openshift: 
* __Description:__ RedHat's container platform that runs Kubernetes. Essentially it's Kubernetes with extra features. [src](https://www.openshift.com/learn/what-is-openshift)  
### Relational Database:  
### REpresentational State Transfer API (REST API):  
* __Description:__ An API is a set of rules that allow applications to interact with each other. REST is a set of rules to follow when creating the API. Two key principles are that there are clients (a person or software that uses the API) and there are resources (any object the API can provide information about).     
* __The Six Constraints:__ In order to make the API RESTful it must satisfy 6 constraints: 
  * (1) Uniform Interface - The request must have all the information required to perform the request. The response must provide enough information for the user to modify a resource. Hypermedia must be used as the engine of application state (aka the server must be able to tell the user how to change the state)
  * (2) Client-Server Separation - The client and the server are independent, and only interact through requests and responses. 
  * (3) Sateless - the server doesn't remember anything (like the users of the api or if a resource was requested before)
  * (4) Layered System - Layers between the client and server (security, caching, loadbalancing, etc) should not affect requests/responses
  * (5) Cacheable - Responses should be labeled as cacheable or non-cacheable (like with a version number). If a resource is cacheable, the client can use the data for future requests. This can help prevent the client for requesting data over and over. 
  * (6) Code-on-demand (optional) - The client can request code from the server (like a script) that the client can then execute.  
* __Cloud Usage:__ An applications exposes information about itself by providing information about its resources through a REST API. A user or another application can view the state of the application and then create/update/delete resources through the REST API.  The Kubernetes API is an example of this - for example, it allows you to create/delete Pods by sending requests to the API Server.  [src](https://medium.com/extend/what-is-rest-a-simple-explanation-for-beginners-part-1-introduction-b4a072f8740f) [src](https://restfulapi.net/) [src](https://www.smashingmagazine.com/2018/01/understanding-using-rest-api/)
### Role Based Access Control (RBAC): 
* __Description:__ A security protocol that restricts access to resources by giving Roles to users. A Role is allowed to do certain things. Thus, what a user can do is based on what role it has ([src](https://digitalguardian.com/blog/what-role-based-access-control-rbac-examples-benefits-and-more)).    
### Serverless Computing:  
* __Desription:__ A cloud-computing execution model in which the cloud provider runs the server, and dynamically manages the allocation of machine resources. [src](https://en.wikipedia.org/wiki/Serverless_computing)  
* __Cloud Example:__ You give the cloud provider your code. When the cloud provider sees a request to access your code it will then allocate resources to run your code. When nobody is accessing your code anymore it will remove the resources. 
### Service Mesh: 
* __Description:__ An Infrastructure Layer for microservices. [src](https://medium.com/cloud-heroes/cloud-simplified-service-mesh-basics-542fef25024d)  
### Service Mesh Side Car: 
* __Description:__ An implementation of a Service Mesh where every unit gets a "Side Car" that handles networking for the unit that it's paired with.  
### Source of Truth:  
### SSL Certificates: 
* __Description:__ "SSL certificates form the core of trust on the web by assuring the identity of websites. This trust is built by digitally binding a cryptographic key to an organization’s identity. An SSL certificate will bind domain names to server names, and company names to locations. This ensures that if you go to your bank’s web site, for example, you know for sure it is your bank, and you are not giving out your information to a phishing scam." (where a certificate is a file that contains a Public Key) [src](https://blog.cloudflare.com/introducing-cfssl/)  
* __Cloud Example:__ These are commonly used in the Cloud when networking between components. You could have a container that generates certificates for you application to use.  
### SQL:  
### Stateless:  
### Systemd:  
### S3 Bucket:  
### Terraform:  
### Travis:  
### Tupperware:  
### Quay.io:  
* __Description:__ A private hosted docker registry. [src](https://quay.io/)  
### Ubuntu: 
* __Description:__ A Linux Distribution (aka an Operating System that uses the Linux kernel).   
### Vault:  
### Virtual Machine:  
### VMWare:  
### WeaveWorks:  
### Yaml:  
