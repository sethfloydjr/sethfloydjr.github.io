# SethFloydJr

## A Summary Of Me

* Seth Floyd
* McDonough, GA
* Have lived all my life in Georgia

### How did you end up as an SRE?

I went to school at Georgia Southern University, where I studied Hotel and Restaurant Management. After school I worked at a few restaurants and hotels around Atlanta and quickly realized that career and having a family did not mesh well, so I signed up for some classes to study for my MCSE back when Windows NT was still the number one server OS around. I then stumbled into a job working on software and infrastructure for hotels such as the Ritz Carlton and other high-end private hotels, where I was introduced to Unix. I remember my manager set my `.bash_profile` to say "When Seth gets a clue, he will figure out how to change this." I saw that every single day, every single time I logged in, and it pissed me off so much that I went on a mission to figure out how to fix it.

Flash forward a year or so and I was working at Earthlink in dial-up support, reading an O'Reilly book about Linux administration when the light clicked on. I vividly remember where I was and who I stood up and talked to in the cubicle next to me to tell them what I had just figured out. By 2009 I was at a company called Silverpop, where I was introduced to AWS, DevOps, and Chef on the Configuration Management team. I started learning the basic concepts of DevOps and quickly realized that was what I wanted to do.

Since then I have bounced around a few companies — some great, some terrible — and collected all kinds of stories along the way. Now I am at TextNow as a Sr. Security Operations Engineer, where I mentor the more junior people on my team and advise on current architectural concepts around AWS, Terraform, Kubernetes, and security. In the last few years security has become much more important to me; I implement security measures any chance I get and advise on how we can make our infrastructure and code more secure, helping protect our customers and their data.

### Where do you want to go and what do you want to do?

* I am interested in working for companies that give something back. This could be a service that benefits people and they directly see that or it could be a company that supplies a service to other companies that beneits that second companies customers.
* I am especially focused on delevoping my skills around cybersecurity and how they can be implemeted with infrastucture, with CI/CD pipelines, and with application code.
* In 2024 I obtained my CCSP which I feel would be beneficial for all SRE and DevOps engineers to have. There is so much more to being an SRE than just looking at Datadog to respond to alerts or building out a new kubernetes cluster with Terraform. Knowing the "why" of infrastructure and the "why" of providing a high availability system with disaster recovery is important and beneficial to those in my field. The list goes on of how an SRE having his or her CCSP is beneficial but the key is "Can you put it into practice? Can you help make this and that more secure?". Thats what I want to test myself with.

## Resume

Senior Cloud Security Engineer with 20+ years of security-focused engineering experience spanning cloud security, infrastructure security, DevSecOps, and security operations. Deep specialization in AWS cloud security posture management (CSPM), IAM governance, zero trust / least-privilege enforcement, secrets management, and CI/CD security. Throughout my career I have consistently owned the security function — building security automation, implementing compliance frameworks (SOC 2, FedRAMP), securing cloud infrastructure, and establishing incident response programs. Proficient in CrowdStrike, Semgrep, TruffleHog, Terraform (policy as code), and Python-based SOAR automation. CCSP, AWS Solutions Architect, and Terraform certified.

### Core Competencies

* **Cloud Security** — AWS IAM, GuardDuty, Security Hub, CloudTrail, Macie, Config, WAF, CSPM, VPC Security, Network Segmentation
* **Detection & Response** — SIEM, SOAR, Incident Response, Detection Engineering, Threat Hunting, Tabletop Exercises
* **AppSec & CI/CD** — Semgrep (SAST), TruffleHog (Secrets Scanning), Supply Chain Security, CI/CD Security, GitHub Actions, Atlantis
* **Identity & Access** — Zero Trust, Least Privilege, JIT Concepts, IAM Governance, Secrets Management, Policy as Code
* **Infrastructure** — Terraform, Kubernetes/EKS, Docker, ArgoCD, Packer, Container Security Hardening
* **Security Tooling** — CrowdStrike Falcon (EDR/XDR), Qualys, Datadog, AWS Security Hub
* **Frameworks** — SOC 2, FedRAMP, HIPAA-adjacent, Zero Trust Architecture, NIST 800-171

### Relevant Work Experience

#### TextNow - Sr. Security Operations Engineer | Sr. Systems Reliability Engineer - Dec 2021 - Present

*Security-focused throughout tenure; formally titled Sr. Security Operations Engineer from March 2025*

* Lead AWS cloud security posture management (CSPM) across all accounts using GuardDuty, Security Hub, Macie, Config, and CloudTrail — enforcing zero trust / least-privilege IAM governance via Terraform (policy as code).
* Built Python-based security automation tooling and an executive-facing dashboard to audit IAM roles and S3 access, improving visibility, enforcing least-privilege, and reducing storage risk and cost.
* Deployed TruffleHog for automated secrets scanning and Macie for PHI/PII data classification and labeling — closing critical supply chain and data exposure risks.
* Established formal security incident response (IR) and remediation processes from scratch; developed tabletop exercises to build team muscle memory and strengthen incident preparedness.
* Integrated CrowdStrike Falcon across all AWS workloads for EDR/XDR coverage and endpoint security hardening.
* Laid the foundation for SOC 2 compliance through security governance, access control, and monitoring strategy; audited database permissions and enforced IAM-only access policies.
* Drove DevSecOps adoption — migrated CI/CD to GitHub Actions, Terraform execution to Atlantis, Kubernetes deployments to ArgoCD; enforced CI/CD security gates and AWS Config compliance rules.
* Deployed and maintained EKS workloads with hardened container security configurations; enforced least-privilege RBAC and IAM node group policies.
* Conducted security assessments on new tooling prior to adoption; led vulnerability management and remediation planning.

#### Dell Secureworks - Principal Security Infrastructure Engineer - Dec 2020 - Dec 2021

*Security company — built and secured cloud infrastructure for enterprise endpoint security products*

* Built and hardened AWS cloud infrastructure for endpoint security products using Terraform, Packer, Kubernetes, and Rancher — enforcing security hardening standards across all compute and container workloads.
* Partnered with security teams on vulnerability scanning of container images and AWS instances using Qualys; automated security remediation workflows with Python tooling.
* Designed and deployed a GitLab HA cluster hosting 1,500+ repositories with zero-downtime migration — securing the software supply chain across the engineering organization.

#### Valimail - Sr. Security & Reliability Engineer - Feb 2020 - Dec 2020

*Email security company — enforced SOC 2 and FedRAMP compliance across infrastructure processing 500B+ messages daily*

* Secured and managed global cloud infrastructure in AWS and Azure processing nearly 500B messages daily — enforcing SOC 2 and FedRAMP compliance, IAM governance, and security monitoring at massive scale.
* Designed Terraform-based CI/CD pipelines with security controls enforced at every stage; implemented infrastructure rollover policies and strengthened IAM access controls.

#### Terbium Labs - Lead Security & DevOps Engineer - March 2018 - Feb 2020

*Dark web intelligence company — security automation and compliance for sensitive data workloads*

* Directed AWS security automation using Terraform and Python — rebuilt entire security infrastructure from the ground up, implementing vulnerability scanning, IR workflows, and compliance controls for sensitive data workloads.
* Established modern secure CI/CD deployment processes; migrated all source repositories with security controls enforced throughout the pipeline.

#### Earlier Security & Engineering Roles (1999–2018)

Terminus, Dell Secureworks, Purchasing Power, Silverpop — 19 years of progressive security and infrastructure engineering roles spanning secure system design, infrastructure automation, vulnerability management, and high-availability cloud environments.

### Education and Certifications

* CCSP – Certified Cloud Security Professional (ISC²) - 2024
* Hashicorp Terraform Certified Associate - 2022 / 2024
* AWS Certified Solutions Architect - July 2017
* MongoDB Certified Administrator - Dec 2012
* Oracle Database Certified Administrator (OCA) - March 2011
* Georgia Southern University, Statesboro, GA - Bachelor of Science - May 1999
