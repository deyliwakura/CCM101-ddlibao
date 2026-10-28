# Laboratory Activity 2 — Build the Cloud Infrastructure Blueprint

## Mission Overview

Congratulations,
Your onboarding has been successfully completed, and your Cloud Computing Portfolio has been approved by
your supervisor.
CloudNova Technologies has now assigned you to your first official project.
Before deploying cloud services, every cloud engineer must understand the infrastructure that powers modern
cloud computing. Your mission is to investigate the components of cloud infrastructure, identify how compute,
storage, networking, and identity services work together, and document your findings as if you were preparing
technical documentation for a client.
Using the KillerCoda Playground, Linux tools, official cloud documentation, and your GitHub Cloud Computing
Portfolio, you will complete a series of engineering tasks that simulate the planning phase of a cloud deployment.
Remember: Great cloud engineers build systems—but exceptional cloud engineers document and justify
every design decision.

## Objectives

At the end of this laboratory activity, I should be able to:

* Explain the major components of cloud infrastructure.
* Investigate hardware and software resources available in a Linux environment.
* Differentiate compute, storage, networking, and identity resources.
* Interpret the relationship between cloud infrastructure components.
* Create professional technical documentation using Markdown.
* Continue building a structured GitHub Cloud Computing Portfolio.

## Cloud Infrastructure Components

### 1. Compute

Compute resources provide the processing power required to run applications and services. Examples include virtual machines, containers, and cloud-based compute instances.

### 2. Storage

Storage resources are used to save operating system files, application data, databases, backups, and other information. Cloud storage can include block, file, and object storage.

### 3. Networking

Networking connects cloud resources and allows systems to communicate with each other and with users. Important components include IP addresses, network interfaces, routers, subnets, firewalls, and DNS.

### 4. Identity and Access Management

Identity services control who can access cloud resources and what actions they are allowed to perform. Authentication verifies an identity, while authorization determines the permissions associated with that identity.

### Relationship Between Components

Cloud infrastructure components work together to provide a complete service. For example, a compute instance can run an application, storage can hold its data, networking allows users to access the application, and identity services control access to the resources.

## Tools Used

* **KillerCoda Playground** — Used to perform Linux-based laboratory activities.
* **Linux Terminal** — Used to investigate system resources and execute commands.
* **GitHub** — Used to maintain and document the Cloud Computing Portfolio.
* **Official Cloud Documentation** — Used as a reference for understanding cloud infrastructure concepts.
* **Markdown** — Used to create professional technical documentation.

## Linux Commands Executed

The following Linux commands were used to investigate the available system resources:

```bash
uname -a
```

Displays information about the Linux kernel and operating system.

```bash
lscpu
```

Displays information about the CPU and processor configuration.

```bash
free -h
```

Displays the system's memory and RAM usage in a human-readable format.

```bash
lsblk
```

Lists available block storage devices and partitions.

```bash
df -h
```

Displays disk space usage for mounted filesystems.

```bash
ip addr
```

Displays network interfaces and IP address information.

```bash
hostname
```

Displays the hostname of the Linux system.

```bash
whoami
```

Displays the username of the currently logged-in user.

```bash
ps aux
```

Displays currently running processes.

```bash
ls
```

Lists files and directories in the current location.

```bash
pwd
```

Displays the current working directory.

## Skills Learned

Through this laboratory activity, I learned how to:

* Identify the major components of cloud infrastructure.
* Examine CPU, memory, storage, and networking resources in Linux.
* Use basic Linux commands to gather system information.
* Understand the roles of compute, storage, networking, and identity services.
* Analyze how different infrastructure components interact.
* Document technical information using Markdown.
* Organize cloud engineering work in a GitHub portfolio.
* Use technical documentation as part of the cloud engineering process.

## Challenges Encountered

During the laboratory activity, I encountered challenges while working with the Linux environment and understanding the different cloud infrastructure components.

Some of the challenges included:

* Understanding the purpose of different Linux system-information commands.
* Interpreting CPU, memory, storage, and network information returned by the terminal.
* Differentiating between the roles of compute, storage, networking, and identity services.
* Connecting Linux resources to their equivalent concepts in cloud environments.
* Organizing technical findings into a clear and professional Markdown document.
* Ensuring that the laboratory documentation was properly structured for the GitHub Cloud Computing Portfolio.

These challenges helped improve my Linux command-line skills, cloud infrastructure knowledge, and technical documentation abilities.

## Conclusion

Laboratory Activity 2 provided practical experience in investigating and documenting the fundamental components of cloud infrastructure. By using Linux tools and researching cloud concepts, I gained a better understanding of how compute, storage, networking, and identity services work together. The activity also reinforced the importance of professional documentation when designing and planning cloud infrastructure.
