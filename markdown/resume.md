Wes Parish
============
> DFW, TX | wes.parish2024@elastiscale.net |
> github.com/wesparish

----

>  Objective: To leverage my full-stack experience, make significant
>  contributions, and provide innovative solutions to an organization with
>  difficult technical challenges.

----

Professional Summary
--------------------
Experienced System Architect and Developer specializing in DevOps, Cloud, and
K8s, with experience designing, and implementing large-scale resilient IT
infrastructure. Effective collaboration and team leadership skills including
execution of Agile and Scaled Agile Frameworks for managing the development
life-cycle on both small and large programs.

Able to simultaneously work at multiple levels, including high-level system
architecture and low-level detailed design, while maintaining the ability to
“jump in” and perform development during sprints.

Technical Skills
----------------
**Programming / Scripting Languages**: Python, Bash, Ruby, C++, Java \
**Virtualization / Cloud**: AWS/C2S, KVM, Cloudformation, VMware ESXi/vCenter,
OpenStack \
**Deployment Automation**: Ansible, Chef, Terraform/Terragrunt \
**Container Orchestration**:  Kubernetes, Rancher, Docker \
**Database**: MongoDB, RDS, Oracle, PostgreSQL, MySQL, SQLAlchemy, PsycoPG2 \
**Logging / Metrics**: ELK, Splunk, Prometheus/Grafana, Thanos, InfluxDB \
**Pipeline Tooling**: Artifactory/Xray, Jenkins, Atlassian Suite, JIRA,
Gradle/Groovy, Git, GitLab CI, Github, Github Actions \
**Provisioning**: RedHat Satellite Server, MAAS, Kickstart, Preseed, PXE \
**OS/Security**: RHEL, Ubuntu, MacOS, Apache Guacamole, Keycloak, Fedora389,
CA API Gateway \
**Homelab**: Two 42U racks with redundant power supplies, 10Gb interconnect,
running K8s on bare-metal with Ceph storage and Tesla GPUs schedulable to K8s
pods

Professional Experience
----------

**Topgolf | August 2023 - Current**\
*Senior Architect, Platform Engineering*

   - Architected, designed, and helped implement a revolutionary change to the
   way games are delivered to the bay by deploying GPU-accelerated Unity games
   via K8s pods. This resulted in a much simpler, more performant system that
   saves millions of dollars a year in hardware and licenses over the legacy
   design.
   - Designed and implemented a horizontally-scalable, stateless, game launching
   microservice used to launch K8s-based Unity games across 100+ bays
   simultaneously
   - Architected, designed, and helped implement a templatized instantiation of
   the open-source semantic-release project to provide fully-automated releases
   using trunk-based development with automatic semantic versioning, greatly
   simplifying and speeding up the software development lifecycle
   - Identified an inability to effectively update infrastructure (OS, software,
   packages, etc.) at venues and designed a blue/green solution that extended
   the existing Terraform deployments to provision parallel VM baselines. This
   provided the ability to provision a parallel baseline, smoke-test, migrate
   traffic, and cleanup the old baseline, allowing the move
   from "pets to cattle" at the venues and the introduction of truly immutable
   infrastructure.

**Insight Global | June 2016 – August 2023** \
*Raytheon Intelligence and Space | System Architect and Developer |
June 2016 – August 2023*

   - Architected, designed, and helped implement a high-performance,
   large-scale, Kubernetes based, hybrid cloud system with 500+ bare-metal
   hosts and 5000+ AWS EC2 instances
   - Automated bare-metal deployments with Red Hat Satellite Server; hardened
   squashfs images built with Packer and Ansible and delivered through a DevOps
   pipeline
   - Automated AWS deployments with Terraform, auto-scaling groups, and Ansible
   - Deployed mission software with Gitops paradigms using Helm, Kubernetes,
   and Docker
   - Fully automated DevOps pipeline connecting multiple development factories
   to multiple sites
   - Improved baseline release process to increase release cadence from 6
   months to bi-weekly through the use of semantic versioning, trunk-based
   development, and automation tooling
   - Designed and created dynamic deployment tooling to baseline, provision,
   and maintain mission environments across multiple clouds (100+ environments
   deployed, all running baselined versions of factory-delivered artifacts and
   forked configuration templates)

**VMware | March 2013 – June 2016** \
*Senior Consultant*

   - Provided professional services consulting (specialized in VMware
   Integrated OpenStack (VIO) and hybrid-cloud design / implementation)
   - VMware clients ranged from small businesses to large-scale enterprises
   with 20,000+ hypervisors

**Raytheon IIS | May 2007 – March 2013** \
*Senior Software Engineer*

   - Technical lead for a team of engineers tasked with fully automating the
   deployment of a legacy system, estimated $20M savings on first environment
   build after automation implementation
   - Lowered environment build time from 3 weeks to 1.5 hours with Chef
   automation while increasing reliability, scalability, and repeatability
   - Technical lead on an R&D project that provided tooling for dynamic mission
   application deployment and orchestration to multiple private-cloud platforms
   (OpenStack, OpenNebula, vCloud Director, etc.). Developed APIs to
   automatically generate and override application-specific configuration
   (similar to K8s and ConfigMaps, but before Docker or K8s existed)

Education and Certifications
---------

**CompTIA Security+**

**University of Texas at Arlington** \
Bachelor of Science, Computer Science Engineering, 2007

----

> Versioned releases of this resume are controlled at:
> https://github.com/wesparish/pandoc_resume/releases