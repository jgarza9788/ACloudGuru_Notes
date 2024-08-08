# Docker Certified Associate

# Study Guide

Version 1.
May 2020


```
Page 2
```
## Introduction

```
This examination is based upon critical job activities a Docker Certified Associate performs. The skills and
knowledge certified by this examination represent a level of expertise where a certified Docker Associate
can:
● Run containerized applications from pre-existing images stored in a centralized registry
● Deploy images across the cluster
● Triage and resolve issue reports from stakeholders and resolve
● Standup up on Enterprise clusters with one UCP manager, one DTR replica, and one worker node
● Migrate traditional applications to containers
● Configure and troubleshoot Docker engine
● Perform general maintenance and configuration
Candidates for this certification should have at least six months to one year of experience with Docker,
including exposure to the Docker Enterprise Edition. The knowledge, skills and experience required at this
level should also include:
● container security
● experience with at least one cloud provider
● configuration management tools
● Linux and/or Windows Server
The skills and knowledge this examination measures are derived from an understanding of the jobs of
current Docker users. A team of highly qualified Docker experts defined the test content and developed the
test items.
Note: This examination blueprint includes weighting, test objectives, and example content. Example
topics and concepts are included to clarify the test objectives; they should not be construed as a
comprehensive listing of all the content of this examination.
The following table lists the domains measured by this examination and the extent to which they are
represented.
```
## Examination Format

```
The examination contains 55 questions consisting of 13 multiple choice items and 42 discrete option
multiple choice (DOMC) items.
```
**Name of Domain % of Exam**

Orchestration 25%

Image Creation, Management, and Registry 20%

Installation and Configuration 15%

Networking 15%

Security 15%

Storage and Volumes 10%


● **Multiple-choice:** Examinees are presented a question with at least four response options and must
select one or more options to best answer the question. Distracters or wrong answers will be
presented as response options. These are response options that examinees with incomplete
knowledge or skill might choose, as they are generally plausible responses fitting into the content
area defined by the test objective.

● **Discrete Option Multiple Choice (DOMC):** DOMC items represent a relatively simple, but useful
change in the delivery of multiple-choice questions. Options are randomly presented, one at a time.
For each presented option, the examinee chooses YES or NO to indicate if the option is correct. To
familiarize yourself with DOMC, try out this practice exam.


## Content Limits

**Domain 1: Orchestration (25% of exam)**

Content may include the following:

```
● Complete the setup of a swarm mode cluster, with managers and worker nodes
● Describe and demonstrate how to extend the instructions to run individual containers into
running services under swarm.
● Describe the importance of quorum in a swarm cluster.
● Describe the difference between running a container and running a service.
● Interpret the output of “docker inspect” commands.
● Convert an application deployment into a stack file using a YAML compose file with "docker
stack deploy"
● Manipulate a running stack of services.
● Describe and demonstrate orchestration activities.
● Increase the number of replicas.
● Add networks, publish ports.
● Mount volumes.
● Describe and demonstrate how to run replicated and global services.
● Apply node labels to demonstrate placement of tasks.
● Describe and demonstrate how to use templates with “docker service create”.
● Identify the steps needed to troubleshoot a service not deploying.
● Describe how a Dockerized application communicates with legacy systems.
● Describe how to deploy containerized workloads as Kubernetes pods and deployments.
● Describe how to provide configuration to Kubernetes pods using configMaps and secrets.
```
**Domain 2: Image Creation, Management, and Registry (20% of exam)**
Content may include the following:

```
● Describe the use of Dockerfile.
● Describe options, such as add, copy, volumes, expose, entry point.
● Identify and display the main parts of a Dockerfile.
● Describe and demonstrate how to create an efficient image via a Dockerfile.
● Describe and demonstrate how to use CLI commands to manage images, such as list,
delete, prune, rmi.
● Describe and demonstrate how to inspect images and report specific attributes using filter
and format
● Describe and demonstrate how to tag an image.
```

```
● Describe and demonstrate how to apply a file to create a Docker image.
● Describe and demonstrate how to display layers of a Docker image
● Describe and demonstrate how to modify an image to a single layer.
● Describe and demonstrate registry functions.
● Deploy a registry.
● Log into a registry.
● Utilize search in a registry.
● Push an image to a registry.
● Sign an image in a registry.
● Pull and delete images from a registry.
```
**Domain 3: Installation and Configuration (15% of exam)**
Content may include the following:

```
● Describe sizing requirements for installation.
● Describe and demonstrate the setup of repo, selection of a storage driver, and installation
of the Docker engine on multiple platforms.
● Describe and demonstrate configuration of logging drivers (splunk, journald, etc.).
● Describe and demonstrate how to set up swarm, configure managers, add nodes, and
setup the backup schedule.
● Describe and demonstrate how to create and manage user and teams.
● Describe and demonstrate how to configure the Docker daemon to start on boot.
● Describe and demonstrate how to use certificate-based client-server authentication to
ensure a Docker daemon has the rights to access images on a registry.
● Describe the use of namespaces, cgroups, and certificate configuration.
● Describe and interpret errors to troubleshoot installation issues without assistance.
● Describe and demonstrate the steps to deploy the Docker engine, UCP, and DTR on AWS
and on-premises in an HA configuration.
● Describe and demonstrate how to configure backups for UCP and DTR.
```

**Domain 4: Networking (15% of exam)**

Content may include the following:

```
● Describe the Container Network Model and how it interfaces with the Docker engine and
network and IPAM drivers.
● Describe the different types and use cases for the built-in network drivers.
● Describe the types of traffic that flow between the Docker engine, registry and UCP
controllers.
● Describe and demonstrate how to create a Docker bridge network for developers to use for
their containers.
● Describe and demonstrate how to publish a port so that an application is accessible
externally.
● Identify which IP and port a container is externally accessible on.
● Compare and contrast “host” and “ingress” publishing modes.
● Describe and demonstrate how to configure Docker to use external DNS.
● Describe and demonstrate how to use Docker to load balance HTTP/HTTPs traffic to an
application (Configure L7 load balancing with Docker EE).
● Understand and describe the types of traffic that flow between the Docker engine, registry,
and UCP controllers
● Describe and demonstrate how to deploy a service on a Docker overlay network.
● Describe and demonstrate how to troubleshoot container and engine logs to resolve
connectivity issues between containers.
● Describe how to route traffic to Kubernetes pods using ClusterIP and NodePort services.
● Describe the Kubertnetes’ container network model.
```
**Domain 5: Security (15% of exam)**
Content may include the following:

```
● Describe security administration and tasks.
● Describe the process of signing an image.
● Describe default engine security.
● Describe swarm default security.
● Describe MTLS.
● Describe identity roles.
● Compare and contrast UCP workers and managers.
● Describe the process to use external certificates with UCP and DTR.
● Describe and demonstrate that an image passes a security scan.
● Describe and demonstrate how to enable Docker Content Trust.
● Describe and demonstrate how to configure RBAC with UCP.
● Describe and demonstrate how to integrate UCP with LDAP/AD.
```

```
● Describe and demonstrate how to create UCP client bundles.
```
**Domain 6: Storage and Volumes (10% of exam)**

Content may include the following:

```
● Identify the correct graph drivers to uses with various operating systems.
● Describe and demonstrate how to configure devicemapper.
● Compare and contrast object and block storage and when they should be used.
● Describe how an application is composed of layers and where these layers reside on the
filesystem.
● Describe the use of volumes are used with Docker for persistent storage.
● Identify the steps to take to clean up unused images on a filesystem and DTR.
● Describe and demonstrate how storage can be used across cluster nodes.
● Describe how to provision persistent storage to a Kubernetes pod using persistentVolumes.
● Describe the relationship between container storage interface drivers, storageClass,
persistentVolumeClaim and volume objects in Kubernetes.
```
## Sample Test Questions

The following supplemental information is displayed above each DOMC item on the live exam:





## Answer Key

Q1 = Option 3
Q2 = Option 1
Q3 = Option 1
Q4 = A
Q5 = B
Q6 = A
Q7 = Option 3
Q8 = C
Q9 = B


## Notes


### success.docker.com/certification

**Questions? Email certification@docker.com**

Copyright © 2017 Docker, Inc. All Rights Reserved. Docker and the Docker logo are
trademarks or registered trademarks of Docker in the United States and other countries.
All brand names, product names, or trademarks belong to their respective holders


