# SethFloydJr

## A Summary Of Me

* Seth Floyd
* McDonough, GA
* Have lived all my life in Georgia

### How did you end up as and SRE?

* I went to school at Georgia Southern University where I studied Hotel and Restaurant Management
* After school I worked at a few restaurants and hotels around Atlanta and quickly realized that career and having a family did not mesh well.
* I signed up for some classes to study for my MCSE when Windows NT was still the number one server OS around. 
* I then stumbled into a job where I worked on software and infrastructure for hotels such has Ritz Carlton and other high end private hotels. Here i was introduced to Unix. I remember that my manager set my .bash_profile to say "When Seth gets a clue, he will figure out how to change this." I saw that every single day every single time I logged in. That pissed me off so much that I went on a misssion to figure out how to fix that.
* Flash forward a year or so and I was working at Earthlink in dial up support and reading an O'Reilly book about Linux Administration and the light clicked on. I vividly remember where I was and who I stood up and talked to in the cuble next to me. Oddly enough her name was Sara Hacker.
* Flash forward to 2009 and I was working at a company called Silverpop. There I was introduced to AWS, DevOps, and Chef all while on the Configuration Management team. I started learning the basic concepts of DevOps and I quickly realized that was what I wanted to do.
* Since then I have bounced around to a few companies, some great some terrible. I have all kinds of stories. Now I am at TextNow where I am a Sr SRE. I help mentor the more junior people on my team. I advise on current architechtual concepts around AWS, Terraform, Kuberntes, and Security. 
* In the last few years security has become much more important to me. I implement security measures any chance I get and advise on how we can make our infrastructure more secure, our code more secure, and thus helping protect our customers and their data.

### Where do you wan to go and what do you want to do?

* I am interested in working for companies that give something back. This could be a service that benefits people and they directly see that or it could be a company that supplies a service to other companies that beneits that second companies customers.
* I am especially focused on delevoping my skills around cybersecurity and how they can be implemeted with infrastucture, with CI/CD pipelines, and with application code.
* Currently I am studying for my CCSP which I feel would be beneficial for all SRE and DevOps engineers to have. There is so much more to being and SRE than just looking at Datadog to respond to alerts or building out a new kubernetes cluster with Terraform. Knowing the "why" of infrastructure and the "why" of providing a high availability system with disaster recovery is im portant and beneficial to those in my field. The list goes on of how an SRE having his or her CCSP is beneficial but the key is "can you put it into practice?". Can you help make this and that more secure? Thats what I want to test myself with.

## Resume

DevOps/SRE Engineer with 20+ years experience dedicated to automation, optimization, and security. Understands and manages the space between operations and development to quickly deliver code to customers. Brings maturity, enthusiasm, and a drive to learn new technologies along with real world experience. Believes in and practices the theory of “Cattle not Pets”.

### Core Skills

#### SRE/DevOps Tools

* Full AWS Suite (EC2, VPC, IAM, S3, ECS, RDS (MySQL, PSQL, Cassandra), Lambda, SNS, EKS, MKS, Guardrail, Config, Cloudtrail, Cloudwatch, etc.)
* Python
* Bash
* GIT
* Terraform
* Packer
* Docker
* Gitlab Administration
* GitHub Actions
* CircleCI
* Kubernetes
* ArgoCD
* Atlantis

#### Other Skills: 

* ELK
* MongoDB
* Agile methodologies 
* CI/CD
* Confluence and Jira Administration
* Datadog - Monitor and Dashboard creation
* PagerDuty
* Prometheus 
* Grafana
* Rancher
* GCP

### Relevant Work Experience:

#### TextNow - Sr. Systems Reliability Engineer - Dec 2021 - Present

As a senior member of the SRE team I mentored new and less experienced SREs as they joined the team. I championed DevOps processes and procedures among our team and helped spread these processes through the company. Other duties involved building infrastructure such as MKS Kafka clusters, Elasticsearch clusters, and RDS databases that served applications using Terraform, deploying applications to EKS Kubernetes clusters using ArgoCD, and implementing security practices and securing existing AWS accounts and resources within using Guardrail, Config, and Cloudtrail. Being on call and maintaining monitors, alerts, and dashboards in Datadog and Pager Duty, attending blameless post-mortems after incidents and implementing repair items were also normal activities for me. 
A very large project that I was highly involved with was moving all of our CI/CD pipelines from Jenkins to GitHub Actions. Part of this involved moving our Kubernetes deployments from kube-deploy to ArgoCD and moving our Terraform deployments from Jenkins to Atlantis. Another portion of this involved upgrading all of our EKS clusters, switching from self managed to AWS managed nodes, and maintaining upgrades for other tools such as Terraform using workspaces in a mono-repo.

#### Dell Secureworks - Principal DevOps Engineer - Dec 2020 - Dec 2021

In this role I helped deliver production code at a regular cadence using Agile techniques, tools and methodologies using Terraform, Packer, Gitlab, Rancher and Kubernetes. I was responsible for performing rolling updates of various tools and components of our infrastructure using custom tooling and various procedures that might have required some python scripting to aid in the updates. Working with multiple teams and multiple products I helped troubleshoot and remedy deployment issues, answer technical infrastructure related questions, and provide needed infrastructure guidance in relation to monitoring, logs, and running in Docker containers. This sometimes might include building a new kubernetes cluster and helping populate and manage it with various pipelines in Gitlab. Participating in the on-call rotation which handled all production related outages across all products, I used Datadog and PagerDuty to actively monitor and ensure uptime and effective performance of applications and platforms.
A major project that I was responsible for, was converting our stand-alone Gitlab instance into a multi-instance Gitlab High Availability cluster. This cluster housed nearly 1500 repositories and was accessed by upwards of 300 people per day and the project also included migration of all users, data, and repositories from our original single instance implementation.


#### Valimail - Sr System Reliability Engineer - Feb 2020 - Dec 2020

In this role I managed code and contributed to maintain and build out our infrastructure and servers that service a globally distributed system that people use daily sending almost a half trillion messages across this network per day. Some of my responsibilities include leading and managing the writing of infrastructure and automation, leading capacity planning, provisioning and scaling of the application infrastructure including cost benefit analysis of vendor offerings, managing uniform best practices for Operations across our applications in order to improve availability, security, transparency and incident response. Measure and report progress against targets for improvement in cited areas. The main project I was involved in was the creation and implementation of a CI/CD pipeline using Terraform, Packer, CircleCI, and Docker. This also included deployment strategies and testing to support our goal of 100% up time and quick turnaround of deployments for the engineering organization in both AWS and Azure cloud deployments. Finally, I was in charge of the monthly tasks of rolling over stale infrastructure that helped us maintain SOC2 and FedRAMP compliance.

#### Terbium Labs - Lead DevOps Engineer/Security Engineer - March 2018 - Feb 2020

Serving as DevOps Lead, I redesigned legacy systems, deployed, and maintained our backend in a new cloud infrastructure. This included tasks such as communicating with developers to find what their needs were and the needs for our applications. I developed a full end to end CI/CD system utilizing Packer, Terraform, and Docker all based in Gitlab. As a result I also developed an open source version of our Gitlab system that others could use and implement to aid with their own SDLC. All of this was done in AWS while following strict security guidelines and maintaining PCI compliance. Many AWS services that were used are EC2, ECS, S3, RDS, Lambda, VPC, DynamoDB, and Systems Manager.
In addition to creating a whole new system from scratch I also maintained our legacy systems until we were able to fully migrate them to the new infrastructure. This included managing several large 100 plus TB EBS volumes, large RDS instances, managing backups, and documentation that aided in the migration. I also served as a mentor for new DevOps hires.

* Terminus - Dev/Cloud/Operations/Security Engineer - July 2016 - March 2018
* Dell Secureworks - Cloud Services/DevOps Engineer - April 2015 - July 2016
* Purchasing Power - DevOps Engineer - Feb 2014 - Jan - 2015
* Silverpop - Configuration Management Engineer - Aug. 2010 – Feb 2014
* Silverpop - Senior Support Specialist - May 2008 – Aug. 2010
* Silverpop - Client Support Specialist - Sept. 2007 – May – 2008
* AIS Computers - Technical Consultant - April 2007 – July 2007
* United Realty Group	Information Systems Manager - Feb 2003 – Feb 2006
* Omni Tech Solutions - Owner - Technology Consultant - Dec 2001 – April 2007
* Transdevelopment - Technology Contract Consultant - March 2000 - April 2000
* Mindspring / Earthlink 	Senior Web Hosting Technician - July 2000 - Oct 2002
* Mindspring / Earthlink 	Dial-Up Technician - Dec 1999 - July 2000 
* Eltrax - Support Technician - March 1999 - Dec 1999 

### Education and Certifications

* Hashicorp Terraform Certified Associate - August 2022
* AWS Certified Solutions Architect - July 2017
* MongoDB Certified Administrator - Dec 2012
* Oracle Database Certified Administrator (OCA) - March 2011
* Georgia Southern University, Statesboro, GA - Bachelor of Science - May 1999
