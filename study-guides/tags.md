# Tags (searchable concepts)

[Home](../README.md) > [Study guides](./README.md) > **Tags**

Secondary concepts that are **not** separate topic folders. Canonical topics stay within a curated set of 74.

Use GitHub search: `IRSA`, `OIDC`, `HPA`, etc.

| Tag | Questions |
| --- | ---: |
| `AWS` | 69 |
| `CI/CD` | 63 |
| `Azure` | 55 |
| `Kubernetes` | 50 |
| `System Design` | 47 |
| `Monitoring` | 26 |
| `Docker` | 22 |
| `Jenkins` | 18 |
| `Databases` | 13 |
| `Terraform` | 13 |
| `Grafana` | 11 |
| `Canary` | 10 |
| `Blue-Green` | 9 |
| `Git` | 9 |
| `GitHub Actions` | 9 |
| `HPA` | 9 |
| `RBAC` | 9 |
| `Deployment Strategies` | 8 |
| `DNS` | 8 |
| `GitOps` | 8 |
| `Load Balancing` | 7 |
| `Azure DevOps` | 6 |
| `GCP` | 6 |
| `Incident Response` | 6 |
| `PV` | 6 |
| `PVC` | 6 |
| `Logging` | 5 |
| `VPC` | 5 |
| `Alerting` | 4 |
| `ArgoCD` | 4 |
| `FinOps` | 4 |
| `Linux` | 4 |
| `Networking` | 4 |
| `Observability` | 4 |
| `Redis` | 4 |
| `CNI` | 3 |
| `ELK` | 3 |
| `Prometheus` | 3 |
| `Shell Scripting` | 3 |
| `Ansible` | 2 |
| `Helm` | 2 |
| `Microservices` | 2 |
| `On-Call` | 2 |
| `OpenTelemetry` | 2 |
| `PDB` | 2 |
| `Python` | 2 |
| `Security` | 2 |
| `Storage` | 2 |
| `Bash` | 1 |
| `CloudFormation` | 1 |
| `CUDA` | 1 |
| `DevSecOps` | 1 |
| `EKS` | 1 |
| `GitLab CI` | 1 |
| `High Availability` | 1 |
| `IAM` | 1 |
| `Ingress` | 1 |
| `IRSA` | 1 |
| `NCCL` | 1 |
| `SRE` | 1 |
| `Vault` | 1 |


## Alerting

- [How do you achieve high availability targets like 99% uptime using monitoring and alerting?](../topics/high-availability.md#how-do-you-achieve-high-availability-targets-like-99-uptime-using-monitoring-and) — High Availability · tags: `Alerting`, `Monitoring`
- [How do you design SLO-based alerting that minimizes alert fatigue?](../topics/slos.md#how-do-you-design-slo-based-alerting-that-minimizes-alert-fatigue) — SLOs · tags: `Alerting`
- [How do you implement SLO-based alerting?](../topics/slos.md#how-do-you-implement-slo-based-alerting) — SLOs · tags: `Alerting`
- [Your organization wants to implement end-to-end observability across microservices, Kubernetes clusters, cloud infrastructure, APIs, and databases using Prometheus, Grafana, ELK Stack, Splunk, OpenTelemetry, and Azure Monitor, aiming to reduce MTTR by 65% and improve platform reliability. How would you design the monitoring, alerting, logging, and incident management architecture?](../topics/incident-response.md#your-organization-wants-to-implement-end-to-end-observability-across-microservic) — Incident Response · tags: `OpenTelemetry`, `Prometheus`, `Grafana`, `Alerting`

## Ansible

- [How do you integrate Ansible with the ELK Stack?](../topics/elk.md#how-do-you-integrate-ansible-with-the-elk-stack) — ELK · tags: `Ansible`
- [What is the Troubleshooting Playbook for Kubernetes?](../topics/kubernetes.md#what-is-the-troubleshooting-playbook-for-kubernetes) — Kubernetes · tags: `Ansible`

## ArgoCD

- [Leadership wants to implement AI-powered Platform Engineering using GitOps, AI Agents, Observability, Prometheus, Grafana, OpenTelemetry, Microsoft Fabric, and predictive incident management. How would you design the enterprise platform architecture?](../topics/incident-response.md#leadership-wants-to-implement-ai-powered-platform-engineering-using-gitops-ai-ag) — Incident Response · tags: `OpenTelemetry`, `Prometheus`, `Grafana`, `Observability`
- [Terraform accidentally modifies ArgoCD RBAC, causing ArgoCD to lose access to all applications. How would you recover?](../topics/iam.md#terraform-accidentally-modifies-argocd-rbac-causing-argocd-to-lose-access-to-all) — IAM · tags: `ArgoCD`, `Terraform`, `RBAC`
- [The Board approves a $1 billion Cloud & Platform Modernization Program using Kubernetes, Terraform, GitHub Actions, ArgoCD, Istio, AI Ops, and Azure OpenAI, targeting 99.99% uptime, 70% faster deployments, and 40% lower infrastructure costs. What execution roadmap would you recommend?](../topics/service-mesh.md#the-board-approves-a-1-billion-cloud-platform-modernization-program-using-kubern) — Service Mesh · tags: `ArgoCD`, `Kubernetes`, `Terraform`, `GitHub Actions`
- [The CTO approves a ₹1,400 Crore Enterprise DevOps Transformation Program to modernize software delivery across 400 engineering teams using CI/CD, Infrastructure as Code (Terraform), Kubernetes, GitOps, DevSecOps, and Cloud Automation, targeting 70% faster release cycles and 60% fewer production incidents. What implementation roadmap, governance model, and change management strategy would you recommend?](../topics/devsecops.md#the-cto-approves-a-1400-crore-enterprise-devops-transformation-program-to-modern) — DevSecOps · tags: `ArgoCD`, `Kubernetes`, `Terraform`, `CI/CD`

## AWS

- [A developer accidentally commits AWS credentials to Git. What is your complete incident response process?](../topics/incident-response.md#a-developer-accidentally-commits-aws-credentials-to-git-what-is-your-complete-in) — Incident Response · tags: `Git`, `AWS`
- [A GitHub Actions/Azure DevOps pipeline passes the build and test stages but fails only during deployment. How would you determine whether the problem is in the pipeline or AWS infrastructure?](../topics/github-actions.md#a-github-actions-azure-devops-pipeline-passes-the-build-and-test-stages-but-fail) — GitHub Actions · tags: `Azure DevOps`, `CI/CD`, `AWS`, `Azure`
- [A new team member needs limited access to AWS resources. How would you configure IAM securely?](../topics/iam.md#a-new-team-member-needs-limited-access-to-aws-resources-how-would-you-configure-) — IAM · tags: `AWS`
- [An AWS resource was manually modified outside CloudFormation. How would you detect and handle this configuration drift?](../topics/cloudformation.md#an-aws-resource-was-manually-modified-outside-cloudformation-how-would-you-detec) — CloudFormation · tags: `AWS`
- [An IAM user has admin access, but S3 access is denied. Why?](../topics/iam.md#an-iam-user-has-admin-access-but-s3-access-is-denied-why) — IAM · tags: `AWS`
- [App communication with EC2 in private subnet behind Multi-AZ LB](../topics/high-availability.md#app-communication-with-ec2-in-private-subnet-behind-multi-az-lb) — High Availability · tags: `VPC`, `AWS`
- [Automate EC2 instance tagging based on environment using Terraform.](../topics/terraform.md#automate-ec2-instance-tagging-based-on-environment-using-terraform) — Terraform · tags: `AWS`
- [AWS IAM, EC2, Lambda & Load Balancers](../topics/iam.md#aws-iam-ec2-lambda-load-balancers) — IAM · tags: `AWS`
- [DevOps Engineer (AWS, Azure, Kubernetes, Terraform, Jenkins) – How do you implement continuous deployment in your workflow?](../topics/kubernetes.md#devops-engineer-aws-azure-kubernetes-terraform-jenkins-how-do-you-implement-cont) — Kubernetes · tags: `Terraform`, `Jenkins`, `AWS`, `Azure`
- [Does AWS provide SSL certificates? What is AWS Certificate Manager (ACM)?](../topics/certificate-management.md#does-aws-provide-ssl-certificates-what-is-aws-certificate-manager-acm) — Certificate Management · tags: `AWS`
- [Does AWS WAF logging capture all requests? Explain.](../topics/network-security.md#does-aws-waf-logging-capture-all-requests-explain) — Network Security · tags: `Logging`, `AWS`
- [Explain the CI/CD pipeline you created for CSV validation and S3 upload.](../topics/ci-cd.md#explain-the-ci-cd-pipeline-you-created-for-csv-validation-and-s3-upload) — CI/CD · tags: `AWS`
- [Explain the complete CI/CD pipeline you have implemented using Jenkins, GitHub, and AWS services.](../topics/jenkins.md#explain-the-complete-ci-cd-pipeline-you-have-implemented-using-jenkins-github-an) — Jenkins · tags: `CI/CD`, `AWS`
- [Have you worked with CloudFront, ECR, ECR Lifecycle Policies, and AWS Tags? Explain real-world use cases.](../topics/cdn.md#have-you-worked-with-cloudfront-ecr-ecr-lifecycle-policies-and-aws-tags-explain-) — CDN · tags: `AWS`
- [How do you build and push a Docker image to AWS ECR?](../topics/docker.md#how-do-you-build-and-push-a-docker-image-to-aws-ecr) — Docker · tags: `AWS`
- [How do you connect and manage services such as Databases, EC2, EKS, and ECS?](../topics/eks.md#how-do-you-connect-and-manage-services-such-as-databases-ec2-eks-and-ecs) — EKS · tags: `AWS`
- [How do you ensure high availability and disaster recovery in AWS?](../topics/disaster-recovery.md#how-do-you-ensure-high-availability-and-disaster-recovery-in-aws) — Disaster Recovery · tags: `High Availability`, `AWS`
- [How do you import an existing AWS resource into Terraform?](../topics/terraform.md#how-do-you-import-an-existing-aws-resource-into-terraform) — Terraform · tags: `AWS`
- [How do you monitor AWS infrastructure and Kubernetes?](../topics/kubernetes.md#how-do-you-monitor-aws-infrastructure-and-kubernetes) — Kubernetes · tags: `AWS`
- [How do you monitor AWS infrastructure using CloudWatch? What metrics and alarms do you configure?](../topics/monitoring.md#how-do-you-monitor-aws-infrastructure-using-cloudwatch-what-metrics-and-alarms-d) — Monitoring · tags: `AWS`
- [How do you monitor AWS resources, Kubernetes workloads, SLAs, and production systems?](../topics/kubernetes.md#how-do-you-monitor-aws-resources-kubernetes-workloads-slas-and-production-system) — Kubernetes · tags: `AWS`
- [How do you optimize AWS costs for EC2, EKS, S3, and RDS?](../topics/eks.md#how-do-you-optimize-aws-costs-for-ec2-eks-s3-and-rds) — EKS · tags: `Databases`, `AWS`
- [How do you provide pod access to S3 bucket](../topics/kubernetes.md#how-do-you-provide-pod-access-to-s3-bucket) — Kubernetes · tags: `AWS`
- [How do you securely manage secrets, credentials, and sensitive configuration in AWS and Kubernetes?](../topics/kubernetes.md#how-do-you-securely-manage-secrets-credentials-and-sensitive-configuration-in-aw) — Kubernetes · tags: `AWS`
- [How do you set up a CICD pipeline for an AWS-hosted application?](../topics/ci-cd.md#how-do-you-set-up-a-cicd-pipeline-for-an-aws-hosted-application) — CI/CD · tags: `AWS`
- [How do you wire DBs, EC2, EKS, and ECS together and what’s the command to hit ECS?](../topics/eks.md#how-do-you-wire-dbs-ec2-eks-and-ecs-together-and-whats-the-command-to-hit-ecs) — EKS · tags: `AWS`
- [How do you write Terraform code to provision a standard AWS EC2 instance?](../topics/terraform.md#how-do-you-write-terraform-code-to-provision-a-standard-aws-ec2-instance) — Terraform · tags: `AWS`
- [How do your secure secrets in Kubernetes and AWS?](../topics/kubernetes.md#how-do-your-secure-secrets-in-kubernetes-and-aws) — Kubernetes · tags: `AWS`
- [How does AWS Load Balancer route traffic?](../topics/load-balancing.md#how-does-aws-load-balancer-route-traffic) — Load Balancing · tags: `AWS`
- [How does on-prem Kubernetes connect privately to AWS Redis?](../topics/kubernetes.md#how-does-on-prem-kubernetes-connect-privately-to-aws-redis) — Kubernetes · tags: `Redis`, `AWS`

## Azure

- [A GitHub Actions/Azure DevOps pipeline passes the build and test stages but fails only during deployment. How would you determine whether the problem is in the pipeline or AWS infrastructure?](../topics/github-actions.md#a-github-actions-azure-devops-pipeline-passes-the-build-and-test-stages-but-fail) — GitHub Actions · tags: `Azure DevOps`, `CI/CD`, `AWS`, `Azure`
- [AWS / Azure Cloud Services](../topics/aws.md#aws-azure-cloud-services) — AWS · tags: `Azure`
- [AWS/Azure Cloud Fundamentals](../topics/aws.md#aws-azure-cloud-fundamentals) — AWS · tags: `Azure`
- [AWS/Azure/GCP](../topics/aws.md#aws-azure-gcp) — AWS · tags: `Azure`, `GCP`
- [Azure App Service vs Azure Functions vs AKS — when do you use which?](../topics/aks.md#azure-app-service-vs-azure-functions-vs-aks-when-do-you-use-which) — AKS · tags: `Azure`
- [Azure Cache for Redis](../topics/redis.md#azure-cache-for-redis) — Redis · tags: `Azure`
- [Azure DevOps & CI/CD](../topics/azure-devops.md#azure-devops-ci-cd) — Azure DevOps · tags: `CI/CD`, `Azure`
- [Azure Key Vault Integration](../topics/vault.md#azure-key-vault-integration) — Vault · tags: `Azure`
- [Azure Kubernetes Service (AKS) & Docker](../topics/aks.md#azure-kubernetes-service-aks-docker) — AKS · tags: `Kubernetes`, `Docker`, `Azure`
- [Azure \| Azure DevOps](../topics/azure-devops.md#azure-azure-devops) — Azure DevOps · tags: `Azure`
- [Can you describe your experience with cloud providers like AWS, Azure, or GCP?](../topics/aws.md#can-you-describe-your-experience-with-cloud-providers-like-aws-azure-or-gcp) — AWS · tags: `Azure`, `GCP`
- [Data Engineer (Azure, Snowflake, Databricks, Python, ETL) – What is your experience with data warehousing?](../topics/python.md#data-engineer-azure-snowflake-databricks-python-etl-what-is-your-experience-with) — Python · tags: `Azure`
- [Design, automate, and manage scalable cloud infrastructure using Microsoft Azure, Terraform, Azure DevOps, and Docker.](../topics/docker.md#design-automate-and-manage-scalable-cloud-infrastructure-using-microsoft-azure-t) — Docker · tags: `Terraform`, `Azure DevOps`, `Azure`, `System Design`
- [DevOps Engineer (AWS, Azure, Kubernetes, Terraform, Jenkins) – How do you implement continuous deployment in your workflow?](../topics/kubernetes.md#devops-engineer-aws-azure-kubernetes-terraform-jenkins-how-do-you-implement-cont) — Kubernetes · tags: `Terraform`, `Jenkins`, `AWS`, `Azure`
- [Difference between Azure Load Balancer and Azure Application Gateway.](../topics/load-balancing.md#difference-between-azure-load-balancer-and-azure-application-gateway) — Load Balancing · tags: `Azure`
- [Explain an end-to-end Azure DevOps ALM process.](../topics/azure-devops.md#explain-an-end-to-end-azure-devops-alm-process) — Azure DevOps · tags: `Azure`
- [Explain Azure Active Directory / Microsoft Entra ID authentication.](../topics/azure-ad.md#explain-azure-active-directory-microsoft-entra-id-authentication) — Azure AD · tags: `Azure`
- [Explain NSG and how traffic flows in Azure.](../topics/network-security.md#explain-nsg-and-how-traffic-flows-in-azure) — Network Security · tags: `Azure`
- [High Availability in Azure](../topics/high-availability.md#high-availability-in-azure) — High Availability · tags: `Azure`
- [How do you achieve traceability in Azure DevOps?](../topics/azure-devops.md#how-do-you-achieve-traceability-in-azure-devops) — Azure DevOps · tags: `Azure`
- [How do you implement Agile methodology in Azure DevOps?](../topics/azure-devops.md#how-do-you-implement-agile-methodology-in-azure-devops) — Azure DevOps · tags: `Azure`
- [How do you implement Azure DevOps / CI-CD Pipelines for automated deployments?](../topics/azure-devops.md#how-do-you-implement-azure-devops-ci-cd-pipelines-for-automated-deployments) — Azure DevOps · tags: `Azure`
- [How do you implement CI/CD for a .NET application using Azure DevOps or GitHub Actions?](../topics/github-actions.md#how-do-you-implement-ci-cd-for-a-net-application-using-azure-devops-or-github-ac) — GitHub Actions · tags: `Azure DevOps`, `CI/CD`, `Azure`
- [How do you manage application secrets securely in Azure (e.g., Key Vault)?](../topics/vault.md#how-do-you-manage-application-secrets-securely-in-azure-e-g-key-vault) — Vault · tags: `Azure`
- [How do you manage secrets in Azure? (Key Vault, Managed Identity)](../topics/vault.md#how-do-you-manage-secrets-in-azure-key-vault-managed-identity) — Vault · tags: `Azure`
- [How do you secure Azure DevOps?](../topics/azure-devops.md#how-do-you-secure-azure-devops) — Azure DevOps · tags: `Azure`
- [How do you securely manage secrets in Azure DevOps and AKS?](../topics/aks.md#how-do-you-securely-manage-secrets-in-azure-devops-and-aks) — AKS · tags: `Azure DevOps`, `Azure`
- [How do you store secrets in Azure DevOps?](../topics/azure-devops.md#how-do-you-store-secrets-in-azure-devops) — Azure DevOps · tags: `Azure`
- [How would you configure Microsoft Entra ID and RBAC for an Azure Function accessing Azure AI Search, Key Vault, and Azure OpenAI?](../topics/azure-ad.md#how-would-you-configure-microsoft-entra-id-and-rbac-for-an-azure-function-access) — Azure AD · tags: `Vault`, `IAM`, `Azure`, `RBAC`
- [How would you design a scalable CI/CD pipeline in Azure DevOps?](../topics/azure-devops.md#how-would-you-design-a-scalable-ci-cd-pipeline-in-azure-devops) — Azure DevOps · tags: `CI/CD`, `Azure`, `System Design`

## Azure DevOps

- [A GitHub Actions/Azure DevOps pipeline passes the build and test stages but fails only during deployment. How would you determine whether the problem is in the pipeline or AWS infrastructure?](../topics/github-actions.md#a-github-actions-azure-devops-pipeline-passes-the-build-and-test-stages-but-fail) — GitHub Actions · tags: `Azure DevOps`, `CI/CD`, `AWS`, `Azure`
- [Design, automate, and manage scalable cloud infrastructure using Microsoft Azure, Terraform, Azure DevOps, and Docker.](../topics/docker.md#design-automate-and-manage-scalable-cloud-infrastructure-using-microsoft-azure-t) — Docker · tags: `Terraform`, `Azure DevOps`, `Azure`, `System Design`
- [How do you implement CI/CD for a .NET application using Azure DevOps or GitHub Actions?](../topics/github-actions.md#how-do-you-implement-ci-cd-for-a-net-application-using-azure-devops-or-github-ac) — GitHub Actions · tags: `Azure DevOps`, `CI/CD`, `Azure`
- [How do you securely manage secrets in Azure DevOps and AKS?](../topics/aks.md#how-do-you-securely-manage-secrets-in-azure-devops-and-aks) — AKS · tags: `Azure DevOps`, `Azure`
- [The CTO requests a real time engineering dashboard integrating Azure DevOps, GitHub, SonarQube, Application Insights, Microsoft Fabric, Power BI, and Azure Monitor. How would you define engineering KPIs, code quality metrics, deployment health, and platform governance?](../topics/devsecops.md#the-cto-requests-a-real-time-engineering-dashboard-integrating-azure-devops-gith) — DevSecOps · tags: `Azure DevOps`, `Azure`
- [Your organization supports over 300 million users across 50 countries, deploying applications that process more than 15 billion API requests daily. Frequent deployment failures and infrastructure bottlenecks are impacting customer experience and business revenue. How would you design a highly available DevOps platform using Kubernetes, Docker, Terraform, Jenkins, GitHub Actions, Azure DevOps, and AWS/Azure to achieve 99.99% uptime and 80% deployment automation?](../topics/kubernetes.md#your-organization-supports-over-300-million-users-across-50-countries-deploying-) — Kubernetes · tags: `Docker`, `Terraform`, `Jenkins`, `GitHub Actions`

## Bash

- [Write a Bash script to list pods in a namespace and restart those in CrashLoopBackOff.](../topics/kubernetes.md#write-a-bash-script-to-list-pods-in-a-namespace-and-restart-those-in-crashloopba) — Kubernetes · tags: `Bash`

## Blue-Green

- [Blue-Green & Canary deployments](../topics/deployment-strategies.md#blue-green-canary-deployments) — Deployment Strategies · tags: `Blue-Green`, `Canary`
- [Difference between blue-green and canary and roll-out deployments ? which is more expensive?](../topics/deployment-strategies.md#difference-between-blue-green-and-canary-and-roll-out-deployments-which-is-more-) — Deployment Strategies · tags: `Blue-Green`, `Canary`
- [Explain Blue-Green Deployment](../topics/deployment-strategies.md#explain-blue-green-deployment) — Deployment Strategies · tags: `Blue-Green`
- [Explain Blue-Green Deployment and Canary Deployment. How have you implemented them?](../topics/deployment-strategies.md#explain-blue-green-deployment-and-canary-deployment-how-have-you-implemented-the) — Deployment Strategies · tags: `Blue-Green`, `Canary`
- [Explain the difference between Rolling, Blue-Green, and Canary deployments.](../topics/deployment-strategies.md#explain-the-difference-between-rolling-blue-green-and-canary-deployments) — Deployment Strategies · tags: `Blue-Green`, `Canary`
- [For a production e-commerce application, which deployment strategy would you recommend—Rolling Update, Blue-Green, or Canary Deployment? What factors would influence your decision?](../topics/deployment-strategies.md#for-a-production-e-commerce-application-which-deployment-strategy-would-you-reco) — Deployment Strategies · tags: `Blue-Green`, `Canary`
- [How do you implement blue-green and canary deployments?](../topics/deployment-strategies.md#how-do-you-implement-blue-green-and-canary-deployments) — Deployment Strategies · tags: `Blue-Green`, `Canary`
- [What is Blue-Green Deployment?](../topics/deployment-strategies.md#what-is-blue-green-deployment) — Deployment Strategies · tags: `Blue-Green`
- [What is the difference between blue-green deployment and canary deployment?](../topics/deployment-strategies.md#what-is-the-difference-between-blue-green-deployment-and-canary-deployment) — Deployment Strategies · tags: `Blue-Green`, `Canary`

## Canary

- [Blue-Green & Canary deployments](../topics/deployment-strategies.md#blue-green-canary-deployments) — Deployment Strategies · tags: `Blue-Green`, `Canary`
- [Difference between blue-green and canary and roll-out deployments ? which is more expensive?](../topics/deployment-strategies.md#difference-between-blue-green-and-canary-and-roll-out-deployments-which-is-more-) — Deployment Strategies · tags: `Blue-Green`, `Canary`
- [During a Canary deployment, how would you verify that the 10% deployment is healthy? What metrics would you monitor before proceeding to 100%?](../topics/deployment-strategies.md#during-a-canary-deployment-how-would-you-verify-that-the-10-deployment-is-health) — Deployment Strategies · tags: `Canary`
- [Explain Blue-Green Deployment and Canary Deployment. How have you implemented them?](../topics/deployment-strategies.md#explain-blue-green-deployment-and-canary-deployment-how-have-you-implemented-the) — Deployment Strategies · tags: `Blue-Green`, `Canary`
- [Explain the difference between Rolling, Blue-Green, and Canary deployments.](../topics/deployment-strategies.md#explain-the-difference-between-rolling-blue-green-and-canary-deployments) — Deployment Strategies · tags: `Blue-Green`, `Canary`
- [For a production e-commerce application, which deployment strategy would you recommend—Rolling Update, Blue-Green, or Canary Deployment? What factors would influence your decision?](../topics/deployment-strategies.md#for-a-production-e-commerce-application-which-deployment-strategy-would-you-reco) — Deployment Strategies · tags: `Blue-Green`, `Canary`
- [How do you implement blue-green and canary deployments?](../topics/deployment-strategies.md#how-do-you-implement-blue-green-and-canary-deployments) — Deployment Strategies · tags: `Blue-Green`, `Canary`
- [Suppose you are implementing a Canary Deployment where only 10% of users receive the new version. How would you implement it through your CI/CD pipeline?](../topics/deployment-strategies.md#suppose-you-are-implementing-a-canary-deployment-where-only-10-of-users-receive-) — Deployment Strategies · tags: `CI/CD`, `Canary`
- [What is Canary Deployment?](../topics/deployment-strategies.md#what-is-canary-deployment) — Deployment Strategies · tags: `Canary`
- [What is the difference between blue-green deployment and canary deployment?](../topics/deployment-strategies.md#what-is-the-difference-between-blue-green-deployment-and-canary-deployment) — Deployment Strategies · tags: `Blue-Green`, `Canary`

## CI/CD

- [A GitHub Actions/Azure DevOps pipeline passes the build and test stages but fails only during deployment. How would you determine whether the problem is in the pipeline or AWS infrastructure?](../topics/github-actions.md#a-github-actions-azure-devops-pipeline-passes-the-build-and-test-stages-but-fail) — GitHub Actions · tags: `Azure DevOps`, `CI/CD`, `AWS`, `Azure`
- [A Jenkins pipeline completed successfully, but the latest changes are not visible in production. What components would you verify before concluding the deployment failed?](../topics/deployment-strategies.md#a-jenkins-pipeline-completed-successfully-but-the-latest-changes-are-not-visible) — Deployment Strategies · tags: `Jenkins`, `CI/CD`
- [A Jenkins pipeline completes successfully, but the application is not deployed. How would you identify where the deployment actually failed?](../topics/jenkins.md#a-jenkins-pipeline-completes-successfully-but-the-application-is-not-deployed-ho) — Jenkins · tags: `CI/CD`
- [A Jenkins pipeline fails after deployment. What's your debugging process?](../topics/jenkins.md#a-jenkins-pipeline-fails-after-deployment-what-s-your-debugging-process) — Jenkins · tags: `CI/CD`
- [A Jenkins pipeline has suddenly started failing after yesterday's deployment. What's your troubleshooting approach?](../topics/jenkins.md#a-jenkins-pipeline-has-suddenly-started-failing-after-yesterday-s-deployment-wha) — Jenkins · tags: `CI/CD`
- [A Jenkins pipeline stopped triggering after a Git push. How would you troubleshoot it?](../topics/jenkins.md#a-jenkins-pipeline-stopped-triggering-after-a-git-push-how-would-you-troubleshoo) — Jenkins · tags: `CI/CD`, `Git`
- [A ransomware attack compromises 3,000 production servers, container registries, and CI/CD pipelines across multiple regions. How would you secure the platform, recover operations, and strengthen DevSecOps controls while minimizing business disruption?](../topics/devsecops.md#a-ransomware-attack-compromises-3000-production-servers-container-registries-and) — DevSecOps · tags: `Docker`, `CI/CD`
- [Azure DevOps & CI/CD](../topics/azure-devops.md#azure-devops-ci-cd) — Azure DevOps · tags: `CI/CD`, `Azure`
- [CI/CD pipeline failures & production rollback](../topics/deployment-strategies.md#ci-cd-pipeline-failures-production-rollback) — Deployment Strategies · tags: `CI/CD`
- [CI/CD, rollback and security best practices](../topics/deployment-strategies.md#ci-cd-rollback-and-security-best-practices) — Deployment Strategies · tags: `CI/CD`
- [Deploy a real application using: Git → CI/CD → Docker → Kubernetes → Cloud → Monitoring](../topics/monitoring.md#deploy-a-real-application-using-git-ci-cd-docker-kubernetes-cloud-monitoring) — Monitoring · tags: `Kubernetes`, `Docker`, `CI/CD`, `Git`
- [Design and implement modern DevOps, CI/CD, Infrastructure as Code (IaC), and Kubernetes solutions.](../topics/kubernetes.md#design-and-implement-modern-devops-ci-cd-infrastructure-as-code-iac-and-kubernet) — Kubernetes · tags: `CI/CD`
- [Do you execute Terraform locally or through a CI/CD pipeline? Explain the complete workflow.](../topics/terraform.md#do-you-execute-terraform-locally-or-through-a-ci-cd-pipeline-explain-the-complet) — Terraform · tags: `CI/CD`
- [Explain a Jenkins Pipeline and its stages.](../topics/jenkins.md#explain-a-jenkins-pipeline-and-its-stages) — Jenkins · tags: `CI/CD`
- [Explain a Jenkins Pipeline structure and the purpose of its various stages.](../topics/jenkins.md#explain-a-jenkins-pipeline-structure-and-the-purpose-of-its-various-stages) — Jenkins · tags: `CI/CD`
- [Explain CI/CD and GitHub Actions.](../topics/github-actions.md#explain-ci-cd-and-github-actions) — GitHub Actions · tags: `CI/CD`
- [Explain flow in Jenkins pipeline.](../topics/jenkins.md#explain-flow-in-jenkins-pipeline) — Jenkins · tags: `CI/CD`
- [Explain how Docker fits into your CI/CD pipeline project.](../topics/docker.md#explain-how-docker-fits-into-your-ci-cd-pipeline-project) — Docker · tags: `CI/CD`
- [Explain the complete CI/CD pipeline you have implemented using Jenkins, GitHub, and AWS services.](../topics/jenkins.md#explain-the-complete-ci-cd-pipeline-you-have-implemented-using-jenkins-github-an) — Jenkins · tags: `CI/CD`, `AWS`
- [Explain the Jenkins pipeline you worked on.](../topics/jenkins.md#explain-the-jenkins-pipeline-you-worked-on) — Jenkins · tags: `CI/CD`
- [Explain the stages in a Jenkins Pipeline.](../topics/jenkins.md#explain-the-stages-in-a-jenkins-pipeline) — Jenkins · tags: `CI/CD`
- [Explain your end-to-end CI/CD workflow. Which type of Jenkins pipeline do you use and why?](../topics/jenkins.md#explain-your-end-to-end-ci-cd-workflow-which-type-of-jenkins-pipeline-do-you-use) — Jenkins · tags: `CI/CD`
- [Explain your experience with Jenkins and GitLab CI/CD.](../topics/jenkins.md#explain-your-experience-with-jenkins-and-gitlab-ci-cd) — Jenkins · tags: `GitLab CI`, `CI/CD`
- [How did you tune your Jenkins pipeline?](../topics/jenkins.md#how-did-you-tune-your-jenkins-pipeline) — Jenkins · tags: `CI/CD`
- [How do Jenkins, Docker, Kubernetes, Terraform, Prometheus, and Grafana work together in a complete CI/CD pipeline?](../topics/prometheus.md#how-do-jenkins-docker-kubernetes-terraform-prometheus-and-grafana-work-together-) — Prometheus · tags: `Grafana`, `Kubernetes`, `Docker`, `Terraform`
- [How do you design a CI/CD pipeline for microservices using Jenkins?](../topics/jenkins.md#how-do-you-design-a-ci-cd-pipeline-for-microservices-using-jenkins) — Jenkins · tags: `CI/CD`
- [How do you handle pipeline failures in Jenkins?](../topics/jenkins.md#how-do-you-handle-pipeline-failures-in-jenkins) — Jenkins · tags: `CI/CD`
- [How do you implement CI/CD for a .NET application using Azure DevOps or GitHub Actions?](../topics/github-actions.md#how-do-you-implement-ci-cd-for-a-net-application-using-azure-devops-or-github-ac) — GitHub Actions · tags: `Azure DevOps`, `CI/CD`, `Azure`
- [How do you implement multi-branch CI/CD pipelines in GitLab or Jenkins?](../topics/jenkins.md#how-do-you-implement-multi-branch-ci-cd-pipelines-in-gitlab-or-jenkins) — Jenkins · tags: `CI/CD`
- [How do you implement rollback strategy in Jenkins pipeline?](../topics/deployment-strategies.md#how-do-you-implement-rollback-strategy-in-jenkins-pipeline) — Deployment Strategies · tags: `Jenkins`, `CI/CD`

## CloudFormation

- [Infrastructure as Code (IaC): Terraform, CloudFormation](../topics/terraform.md#infrastructure-as-code-iac-terraform-cloudformation) — Terraform · tags: `CloudFormation`

## CNI

- [Explain how CNI plugins work and how cross-node pod communication happens.](../topics/kubernetes.md#explain-how-cni-plugins-work-and-how-cross-node-pod-communication-happens) — Kubernetes · tags: `CNI`
- [Explain the responsibilities of a CNI plugin beyond just assigning Pod IPs.](../topics/kubernetes.md#explain-the-responsibilities-of-a-cni-plugin-beyond-just-assigning-pod-ips) — Kubernetes · tags: `CNI`
- [Which networking tools do you use to troubleshoot Kubernetes? (tcpdump, ss, conntrack, CNI logs, etc.)](../topics/kubernetes.md#which-networking-tools-do-you-use-to-troubleshoot-kubernetes-tcpdump-ss-conntrac) — Kubernetes · tags: `CNI`

## CUDA

- [How would you handle CUDA driver upgrades in Kubernetes without disrupting thousands of running AI pods?](../topics/kubernetes.md#how-would-you-handle-cuda-driver-upgrades-in-kubernetes-without-disrupting-thous) — Kubernetes · tags: `CUDA`

## Databases

- [ArgoCD shows an application as OutOfSync, but synchronization fails because a PreSync database migration Job is failing. How do you recover without data loss?](../topics/argocd.md#argocd-shows-an-application-as-outofsync-but-synchronization-fails-because-a-pre) — ArgoCD · tags: `Databases`
- [How do you ensure high availability for RDS ?](../topics/high-availability.md#how-do-you-ensure-high-availability-for-rds) — High Availability · tags: `Databases`
- [How do you handle database migrations in a CI/CD pipeline?](../topics/ci-cd.md#how-do-you-handle-database-migrations-in-a-ci-cd-pipeline) — CI/CD · tags: `Databases`
- [How do you optimize AWS costs for EC2, EKS, S3, and RDS?](../topics/eks.md#how-do-you-optimize-aws-costs-for-ec2-eks-s3-and-rds) — EKS · tags: `Databases`, `AWS`
- [How do you optimize the performance of a slow application? Describe your approach to identifying bottlenecks in the frontend, backend, database, and network.](../topics/incident-response.md#how-do-you-optimize-the-performance-of-a-slow-application-describe-your-approach) — Incident Response · tags: `Databases`
- [How does Terraform state locking work with S3 and DynamoDB?](../topics/terraform.md#how-does-terraform-state-locking-work-with-s3-and-dynamodb) — Terraform · tags: `Databases`, `AWS`
- [How would you connect 3 VPCs in one AWS account, 1 VPC in another AWS account, and an on-premises server? Explain the architecture and how they can access an Amazon RDS instance.](../topics/vpc.md#how-would-you-connect-3-vpcs-in-one-aws-account-1-vpc-in-another-aws-account-and) — VPC · tags: `Databases`, `AWS`, `System Design`
- [How would you migrate a 200 GB PostgreSQL database between Kubernetes clusters with less than 10 minutes of downtime?](../topics/kubernetes.md#how-would-you-migrate-a-200-gb-postgresql-database-between-kubernetes-clusters-w) — Kubernetes · tags: `Databases`
- [If the Kubernetes etcd database is lost, what would be your disaster recovery approach?](../topics/disaster-recovery.md#if-the-kubernetes-etcd-database-is-lost-what-would-be-your-disaster-recovery-app) — Disaster Recovery · tags: `Kubernetes`, `Databases`
- [Interview architecture: Design with compute + storage + database + network + identity + security + monitoring.](../topics/monitoring.md#interview-architecture-design-with-compute-storage-database-network-identity-sec) — Monitoring · tags: `Databases`, `System Design`
- [Terraform plan suddenly wants to recreate your production database. What do you do?](../topics/terraform.md#terraform-plan-suddenly-wants-to-recreate-your-production-database-what-do-you-d) — Terraform · tags: `Databases`
- [What is your experience with Lambda, DynamoDB, API Gateway, and the AWS SDKs?](../topics/api-gateway.md#what-is-your-experience-with-lambda-dynamodb-api-gateway-and-the-aws-sdks) — API Gateway · tags: `Databases`, `AWS`
- [Why do we use an S3 bucket and DynamoDB for Terraform state?](../topics/terraform.md#why-do-we-use-an-s3-bucket-and-dynamodb-for-terraform-state) — Terraform · tags: `Databases`, `AWS`

## Deployment Strategies

- [Describe how Kubernetes rolling updates with readiness and liveness probes ensured zero downtime during deployments.](../topics/kubernetes.md#describe-how-kubernetes-rolling-updates-with-readiness-and-liveness-probes-ensur) — Kubernetes · tags: `Deployment Strategies`
- [How do you design zero-downtime deployments for stateful applications in Kubernetes?](../topics/kubernetes.md#how-do-you-design-zero-downtime-deployments-for-stateful-applications-in-kuberne) — Kubernetes · tags: `Deployment Strategies`
- [How do you perform a zero-downtime deployment in Kubernetes?](../topics/kubernetes.md#how-do-you-perform-a-zero-downtime-deployment-in-kubernetes) — Kubernetes · tags: `Deployment Strategies`
- [How do you perform a zero-downtime Kubernetes cluster upgrade in production?](../topics/kubernetes.md#how-do-you-perform-a-zero-downtime-kubernetes-cluster-upgrade-in-production) — Kubernetes · tags: `Deployment Strategies`
- [How would you design a multi-region deployment in terraform, keeping zero downtime in mind ?](../topics/terraform.md#how-would-you-design-a-multi-region-deployment-in-terraform-keeping-zero-downtim) — Terraform · tags: `Deployment Strategies`, `System Design`
- [How would you perform a zero-downtime deployment for a microservices application running on Kubernetes?](../topics/kubernetes.md#how-would-you-perform-a-zero-downtime-deployment-for-a-microservices-application) — Kubernetes · tags: `Deployment Strategies`
- [How would you perform a zero-downtime Kubernetes cluster upgrade?](../topics/kubernetes.md#how-would-you-perform-a-zero-downtime-kubernetes-cluster-upgrade) — Kubernetes · tags: `Deployment Strategies`
- [How would you upgrade a 40-node GKE production cluster running more than 100 microservices with zero downtime?](../topics/gke.md#how-would-you-upgrade-a-40-node-gke-production-cluster-running-more-than-100-mic) — GKE · tags: `Deployment Strategies`

## DevSecOps

- [How do you embed security into the DevOps and SRE lifecycle using DevSecOps practices?](../topics/sre.md#how-do-you-embed-security-into-the-devops-and-sre-lifecycle-using-devsecops-prac) — SRE · tags: `DevSecOps`

## DNS

- [Explain the complete request flow inside Kubernetes—from DNS until the request reaches the container.](../topics/kubernetes.md#explain-the-complete-request-flow-inside-kubernetes-from-dns-until-the-request-r) — Kubernetes · tags: `Docker`, `DNS`
- [How do you handle DNS-level outages inside a service mesh without a full app redeploy?](../topics/service-mesh.md#how-do-you-handle-dns-level-outages-inside-a-service-mesh-without-a-full-app-red) — Service Mesh · tags: `DNS`
- [How does DNS work inside a Kubernetes cluster?](../topics/kubernetes.md#how-does-dns-work-inside-a-kubernetes-cluster) — Kubernetes · tags: `DNS`
- [How does Route 53 perform failover routing?](../topics/disaster-recovery.md#how-does-route-53-perform-failover-routing) — Disaster Recovery · tags: `DNS`
- [Microservice A cannot communicate with Microservice B. Both Pods are Running, DNS resolves correctly, Services and Endpoints exist, but TCP connections time out. How would you troubleshoot?](../topics/kubernetes.md#microservice-a-cannot-communicate-with-microservice-b-both-pods-are-running-dns-) — Kubernetes · tags: `DNS`, `Microservices`
- [Your application is running, but users can't access it. Would you check the Pod, Service, Ingress, DNS, or something else first?](../topics/ingress.md#your-application-is-running-but-users-can-t-access-it-would-you-check-the-pod-se) — Ingress · tags: `Kubernetes`, `DNS`
- [You’re asked to ship a multi-region failover in 3 weeks, no DNS layer allowed. Your plan?](../topics/disaster-recovery.md#youre-asked-to-ship-a-multi-region-failover-in-3-weeks-no-dns-layer-allowed-your) — Disaster Recovery · tags: `DNS`, `System Design`
- [You’re told to implement multi-region AI inference failover without DNS-based routing. What’s your plan?](../topics/disaster-recovery.md#youre-told-to-implement-multi-region-ai-inference-failover-without-dns-based-rou) — Disaster Recovery · tags: `DNS`, `System Design`

## Docker

- [A Pod cannot pull its Docker image. How do you troubleshoot an ImagePullBackOff error?](../topics/kubernetes.md#a-pod-cannot-pull-its-docker-image-how-do-you-troubleshoot-an-imagepullbackoff-e) — Kubernetes · tags: `Docker`
- [A Pod is continuously recreated even though the container itself doesn't report an obvious application error. How would you investigate the complete lifecycle?](../topics/kubernetes.md#a-pod-is-continuously-recreated-even-though-the-container-itself-doesn-t-report-) — Kubernetes · tags: `Docker`
- [A Pod is restarting every 10–15 seconds. How would you troubleshoot and access the container?](../topics/kubernetes.md#a-pod-is-restarting-every-10-15-seconds-how-would-you-troubleshoot-and-access-th) — Kubernetes · tags: `Docker`
- [A production Kubernetes workload needs a configuration change without rebuilding its container image. How would you implement the change safely?](../topics/kubernetes.md#a-production-kubernetes-workload-needs-a-configuration-change-without-rebuilding) — Kubernetes · tags: `Docker`
- [A ransomware attack compromises 3,000 production servers, container registries, and CI/CD pipelines across multiple regions. How would you secure the platform, recover operations, and strengthen DevSecOps controls while minimizing business disruption?](../topics/devsecops.md#a-ransomware-attack-compromises-3000-production-servers-container-registries-and) — DevSecOps · tags: `Docker`, `CI/CD`
- [Azure Kubernetes Service (AKS) & Docker](../topics/aks.md#azure-kubernetes-service-aks-docker) — AKS · tags: `Kubernetes`, `Docker`, `Azure`
- [Deploy a real application using: Git → CI/CD → Docker → Kubernetes → Cloud → Monitoring](../topics/monitoring.md#deploy-a-real-application-using-git-ci-cd-docker-kubernetes-cloud-monitoring) — Monitoring · tags: `Kubernetes`, `Docker`, `CI/CD`, `Git`
- [Difference between Docker Compose and Kubernetes?](../topics/kubernetes.md#difference-between-docker-compose-and-kubernetes) — Kubernetes · tags: `Docker`
- [Difference between Pod and Container?](../topics/kubernetes.md#difference-between-pod-and-container) — Kubernetes · tags: `Docker`
- [Docker, Kubernetes & Jenkins](../topics/kubernetes.md#docker-kubernetes-jenkins) — Kubernetes · tags: `Docker`, `Jenkins`
- [Explain how you solved production problems using Docker, Kubernetes, Terraform, or Jenkins.](../topics/kubernetes.md#explain-how-you-solved-production-problems-using-docker-kubernetes-terraform-or-) — Kubernetes · tags: `Docker`, `Terraform`, `Jenkins`
- [Explain the complete request flow inside Kubernetes—from DNS until the request reaches the container.](../topics/kubernetes.md#explain-the-complete-request-flow-inside-kubernetes-from-dns-until-the-request-r) — Kubernetes · tags: `Docker`, `DNS`
- [Explain the Memory Ladder — Cluster → Namespace → Deployment → ReplicaSet → Pod → Container → Service → Ingress.](../topics/ingress.md#explain-the-memory-ladder-cluster-namespace-deployment-replicaset-pod-container-) — Ingress · tags: `Kubernetes`, `Docker`
- [How do Jenkins, Docker, Kubernetes, Terraform, Prometheus, and Grafana work together in a complete CI/CD pipeline?](../topics/prometheus.md#how-do-jenkins-docker-kubernetes-terraform-prometheus-and-grafana-work-together-) — Prometheus · tags: `Grafana`, `Kubernetes`, `Docker`, `Terraform`
- [How do you integrate Jenkins with Docker and Kubernetes?](../topics/kubernetes.md#how-do-you-integrate-jenkins-with-docker-and-kubernetes) — Kubernetes · tags: `Docker`, `Jenkins`
- [How does docker use namespace and Cgroups?](../topics/kubernetes.md#how-does-docker-use-namespace-and-cgroups) — Kubernetes · tags: `Docker`
- [Security reports that a Pod is making outbound calls to an unauthorized external IP. How would you handle a suspected compromised container?](../topics/kubernetes.md#security-reports-that-a-pod-is-making-outbound-calls-to-an-unauthorized-external) — Kubernetes · tags: `Docker`
- [The Board approves a $800 million Digital Engineering Program using .NET 8, Azure, AI, Azure OpenAI, Microsoft Fabric, Docker, Kubernetes, and DevSecOps, targeting 50% faster releases, 99.99% system availability, and 40% lower infrastructure costs. What implementation roadmap would you recommend?](../topics/devsecops.md#the-board-approves-a-800-million-digital-engineering-program-using-net-8-azure-a) — DevSecOps · tags: `Kubernetes`, `Docker`, `Azure`
- [What is the difference between Docker and Kubernetes?](../topics/kubernetes.md#what-is-the-difference-between-docker-and-kubernetes) — Kubernetes · tags: `Docker`
- [What is your experience with containerization and orchestration technologies such as Docker, Kubernetes, and OpenShift, and how have you used them in production environments?](../topics/kubernetes.md#what-is-your-experience-with-containerization-and-orchestration-technologies-suc) — Kubernetes · tags: `Docker`
- [Which deployment tools have you used (Docker, Kubernetes, Helm, Terraform)?](../topics/helm.md#which-deployment-tools-have-you-used-docker-kubernetes-helm-terraform) — Helm · tags: `Kubernetes`, `Docker`, `Terraform`
- [Your organization supports over 300 million users across 50 countries, deploying applications that process more than 15 billion API requests daily. Frequent deployment failures and infrastructure bottlenecks are impacting customer experience and business revenue. How would you design a highly available DevOps platform using Kubernetes, Docker, Terraform, Jenkins, GitHub Actions, Azure DevOps, and AWS/Azure to achieve 99.99% uptime and 80% deployment automation?](../topics/kubernetes.md#your-organization-supports-over-300-million-users-across-50-countries-deploying-) — Kubernetes · tags: `Docker`, `Terraform`, `Jenkins`, `GitHub Actions`

## EKS

- [An Amazon EKS application starts returning intermittent 502/503 errors immediately after deployment. How would you identify whether the issue is related to Kubernetes, the Load Balancer, or the application?](../topics/incident-response.md#an-amazon-eks-application-starts-returning-intermittent-502-503-errors-immediate) — Incident Response · tags: `EKS`, `Kubernetes`, `Load Balancing`

## ELK

- [Monitoring & Logging: CloudWatch, Prometheus, ELK Stack](../topics/prometheus.md#monitoring-logging-cloudwatch-prometheus-elk-stack) — Prometheus · tags: `ELK`, `Logging`, `Monitoring`
- [What is the difference between Grafana and the ELK Stack?](../topics/grafana.md#what-is-the-difference-between-grafana-and-the-elk-stack) — Grafana · tags: `ELK`
- [Your organization wants to implement end-to-end observability across microservices, Kubernetes clusters, cloud infrastructure, APIs, and databases using Prometheus, Grafana, ELK Stack, Splunk, OpenTelemetry, and Azure Monitor, aiming to reduce MTTR by 65% and improve platform reliability. How would you design the monitoring, alerting, logging, and incident management architecture?](../topics/incident-response.md#your-organization-wants-to-implement-end-to-end-observability-across-microservic) — Incident Response · tags: `OpenTelemetry`, `Prometheus`, `Grafana`, `Alerting`

## FinOps

- [FinOps & AIOps](../topics/observability.md#finops-aiops) — Observability · tags: `FinOps`
- [How do you approach AWS cost optimization and identify underutilized resources?](../topics/aws.md#how-do-you-approach-aws-cost-optimization-and-identify-underutilized-resources) — AWS · tags: `FinOps`
- [Kubernetes Migration / Cost Optimization how have you done?](../topics/kubernetes.md#kubernetes-migration-cost-optimization-how-have-you-done) — Kubernetes · tags: `FinOps`
- [Which AWS tools did you use for cost optimization, and how did you use them?](../topics/aws.md#which-aws-tools-did-you-use-for-cost-optimization-and-how-did-you-use-them) — AWS · tags: `FinOps`

## GCP

- [AWS/Azure/GCP](../topics/aws.md#aws-azure-gcp) — AWS · tags: `Azure`, `GCP`
- [Can you describe your experience with cloud providers like AWS, Azure, or GCP?](../topics/aws.md#can-you-describe-your-experience-with-cloud-providers-like-aws-azure-or-gcp) — AWS · tags: `Azure`, `GCP`
- [Can you design an event-driven pipeline with a Pub/Sub system using GCP?](../topics/ci-cd.md#can-you-design-an-event-driven-pipeline-with-a-pub-sub-system-using-gcp) — CI/CD · tags: `GCP`
- [Which cloud platform are you comfortable with (AWS, Azure, or GCP)?](../topics/aws.md#which-cloud-platform-are-you-comfortable-with-aws-azure-or-gcp) — AWS · tags: `Azure`, `GCP`
- [Which cloud platform do you prefer working with — AWS or GCP — and why?](../topics/aws.md#which-cloud-platform-do-you-prefer-working-with-aws-or-gcp-and-why) — AWS · tags: `GCP`
- [Your organization operates 500 Kubernetes clusters, 50,000 containers, and 2,000 production services across AWS, Azure, and GCP. How would you standardize platform engineering and governance?](../topics/kubernetes.md#your-organization-operates-500-kubernetes-clusters-50000-containers-and-2000-pro) — Kubernetes · tags: `AWS`, `Azure`, `GCP`

## Git

- [A developer accidentally commits AWS credentials to Git. What is your complete incident response process?](../topics/incident-response.md#a-developer-accidentally-commits-aws-credentials-to-git-what-is-your-complete-in) — Incident Response · tags: `Git`, `AWS`
- [A developer asks if they can promote an application from Staging to Production without updating Git. How would you respond in a GitOps environment?](../topics/argocd.md#a-developer-asks-if-they-can-promote-an-application-from-staging-to-production-w) — ArgoCD · tags: `Git`, `GitOps`
- [A Jenkins pipeline stopped triggering after a Git push. How would you troubleshoot it?](../topics/jenkins.md#a-jenkins-pipeline-stopped-triggering-after-a-git-push-how-would-you-troubleshoo) — Jenkins · tags: `CI/CD`, `Git`
- [Deploy a real application using: Git → CI/CD → Docker → Kubernetes → Cloud → Monitoring](../topics/monitoring.md#deploy-a-real-application-using-git-ci-cd-docker-kubernetes-cloud-monitoring) — Monitoring · tags: `Kubernetes`, `Docker`, `CI/CD`, `Git`
- [How do you configure and integrate tools like Jira, GIT/Bitbucket, Jenkins, Artifactory, and Ansible Tower?](../topics/ansible.md#how-do-you-configure-and-integrate-tools-like-jira-git-bitbucket-jenkins-artifac) — Ansible · tags: `Jenkins`, `Git`
- [How would you securely manage secrets in a Kubernetes environment without storing them in Git?](../topics/kubernetes.md#how-would-you-securely-manage-secrets-in-a-kubernetes-environment-without-storin) — Kubernetes · tags: `Git`
- [If Git is already the source of truth, why do we need Argo CD? Why not deploy directly using the CI/CD pipeline with Helm or kubectl?](../topics/argocd.md#if-git-is-already-the-source-of-truth-why-do-we-need-argo-cd-why-not-deploy-dire) — ArgoCD · tags: `Helm`, `CI/CD`, `Git`
- [Memorize this, Jenkins first stage is always git checkout.](../topics/jenkins.md#memorize-this-jenkins-first-stage-is-always-git-checkout) — Jenkins · tags: `Git`
- [Your pipeline suddenly starts executing the same deployment twice for a single Git commit. What would you check in the YAML and repository configuration?](../topics/ci-cd.md#your-pipeline-suddenly-starts-executing-the-same-deployment-twice-for-a-single-g) — CI/CD · tags: `Git`

## GitHub Actions

- [How do you deploy to Kubernetes using GitHub Actions?](../topics/kubernetes.md#how-do-you-deploy-to-kubernetes-using-github-actions) — Kubernetes · tags: `GitHub Actions`
- [How do you troubleshoot a failed Jenkins pipeline or GitHub Actions workflow?](../topics/jenkins.md#how-do-you-troubleshoot-a-failed-jenkins-pipeline-or-github-actions-workflow) — Jenkins · tags: `GitHub Actions`, `CI/CD`
- [How does CI/CD pipeline design work with Jenkins and GitHub Actions?](../topics/jenkins.md#how-does-ci-cd-pipeline-design-work-with-jenkins-and-github-actions) — Jenkins · tags: `GitHub Actions`, `CI/CD`
- [If Docker images are built in Jenkins but security scanning must happen in GitHub Actions, how would you design the workflow?](../topics/docker.md#if-docker-images-are-built-in-jenkins-but-security-scanning-must-happen-in-githu) — Docker · tags: `Jenkins`, `GitHub Actions`
- [Jenkins/GitHub Actions](../topics/jenkins.md#jenkins-github-actions) — Jenkins · tags: `GitHub Actions`
- [Suppose Jenkins currently handles Development, DevOps, and Security pipelines. How would you move security scanning stages from Jenkins to GitHub Actions?](../topics/jenkins.md#suppose-jenkins-currently-handles-development-devops-and-security-pipelines-how-) — Jenkins · tags: `GitHub Actions`
- [The Board approves a $1 billion Cloud & Platform Modernization Program using Kubernetes, Terraform, GitHub Actions, ArgoCD, Istio, AI Ops, and Azure OpenAI, targeting 99.99% uptime, 70% faster deployments, and 40% lower infrastructure costs. What execution roadmap would you recommend?](../topics/service-mesh.md#the-board-approves-a-1-billion-cloud-platform-modernization-program-using-kubern) — Service Mesh · tags: `ArgoCD`, `Kubernetes`, `Terraform`, `GitHub Actions`
- [What is the difference between Jenkins, GitHub Actions, and Bitbucket Pipelines?](../topics/jenkins.md#what-is-the-difference-between-jenkins-github-actions-and-bitbucket-pipelines) — Jenkins · tags: `GitHub Actions`
- [Your organization supports over 300 million users across 50 countries, deploying applications that process more than 15 billion API requests daily. Frequent deployment failures and infrastructure bottlenecks are impacting customer experience and business revenue. How would you design a highly available DevOps platform using Kubernetes, Docker, Terraform, Jenkins, GitHub Actions, Azure DevOps, and AWS/Azure to achieve 99.99% uptime and 80% deployment automation?](../topics/kubernetes.md#your-organization-supports-over-300-million-users-across-50-countries-deploying-) — Kubernetes · tags: `Docker`, `Terraform`, `Jenkins`, `GitHub Actions`

## GitLab CI

- [Explain your experience with Jenkins and GitLab CI/CD.](../topics/jenkins.md#explain-your-experience-with-jenkins-and-gitlab-ci-cd) — Jenkins · tags: `GitLab CI`, `CI/CD`

## GitOps

- [A developer asks if they can promote an application from Staging to Production without updating Git. How would you respond in a GitOps environment?](../topics/argocd.md#a-developer-asks-if-they-can-promote-an-application-from-staging-to-production-w) — ArgoCD · tags: `Git`, `GitOps`
- [ArgoCD & GitOps](../topics/argocd.md#argocd-gitops) — ArgoCD · tags: `GitOps`
- [Design a GitOps workflow for 20+ teams with independent release cycles.](../topics/argocd.md#design-a-gitops-workflow-for-20-teams-with-independent-release-cycles) — ArgoCD · tags: `GitOps`
- [GitOps](../topics/argocd.md#gitops) — ArgoCD · tags: `GitOps`
- [How would you design a GitOps workflow for multiple teams?](../topics/argocd.md#how-would-you-design-a-gitops-workflow-for-multiple-teams) — ArgoCD · tags: `GitOps`
- [Leadership wants to implement AI-powered Platform Engineering using GitOps, AI Agents, Observability, Prometheus, Grafana, OpenTelemetry, Microsoft Fabric, and predictive incident management. How would you design the enterprise platform architecture?](../topics/incident-response.md#leadership-wants-to-implement-ai-powered-platform-engineering-using-gitops-ai-ag) — Incident Response · tags: `OpenTelemetry`, `Prometheus`, `Grafana`, `Observability`
- [The CTO approves a ₹1,400 Crore Enterprise DevOps Transformation Program to modernize software delivery across 400 engineering teams using CI/CD, Infrastructure as Code (Terraform), Kubernetes, GitOps, DevSecOps, and Cloud Automation, targeting 70% faster release cycles and 60% fewer production incidents. What implementation roadmap, governance model, and change management strategy would you recommend?](../topics/devsecops.md#the-cto-approves-a-1400-crore-enterprise-devops-transformation-program-to-modern) — DevSecOps · tags: `ArgoCD`, `Kubernetes`, `Terraform`, `CI/CD`
- [What is the difference between GitOps and traditional DevOps?](../topics/argocd.md#what-is-the-difference-between-gitops-and-traditional-devops) — ArgoCD · tags: `GitOps`

## Grafana

- [are you sure prometheus and grafana do log aggregation?](../topics/prometheus.md#are-you-sure-prometheus-and-grafana-do-log-aggregation) — Prometheus · tags: `Grafana`
- [Compare CloudWatch, Prometheus, Grafana, and Dynatrace.](../topics/prometheus.md#compare-cloudwatch-prometheus-grafana-and-dynatrace) — Prometheus · tags: `Grafana`, `Monitoring`
- [Explain how Prometheus and Grafana helped identify performance bottlenecks before customers noticed them.](../topics/prometheus.md#explain-how-prometheus-and-grafana-helped-identify-performance-bottlenecks-befor) — Prometheus · tags: `Grafana`
- [Have you configured alerts in Prometheus and Grafana? Explain the setup.](../topics/prometheus.md#have-you-configured-alerts-in-prometheus-and-grafana-explain-the-setup) — Prometheus · tags: `Grafana`
- [Have you used Prometheus for monitoring? How was it integrated with Grafana?](../topics/prometheus.md#have-you-used-prometheus-for-monitoring-how-was-it-integrated-with-grafana) — Prometheus · tags: `Grafana`, `Monitoring`
- [How do Jenkins, Docker, Kubernetes, Terraform, Prometheus, and Grafana work together in a complete CI/CD pipeline?](../topics/prometheus.md#how-do-jenkins-docker-kubernetes-terraform-prometheus-and-grafana-work-together-) — Prometheus · tags: `Grafana`, `Kubernetes`, `Docker`, `Terraform`
- [How do you monitor Kubernetes clusters using CloudWatch, Prometheus, and Grafana?](../topics/prometheus.md#how-do-you-monitor-kubernetes-clusters-using-cloudwatch-prometheus-and-grafana) — Prometheus · tags: `Grafana`, `Monitoring`, `Kubernetes`
- [Leadership wants to implement AI-powered Platform Engineering using GitOps, AI Agents, Observability, Prometheus, Grafana, OpenTelemetry, Microsoft Fabric, and predictive incident management. How would you design the enterprise platform architecture?](../topics/incident-response.md#leadership-wants-to-implement-ai-powered-platform-engineering-using-gitops-ai-ag) — Incident Response · tags: `OpenTelemetry`, `Prometheus`, `Grafana`, `Observability`
- [Monitoring with Prometheus & Grafana](../topics/prometheus.md#monitoring-with-prometheus-grafana) — Prometheus · tags: `Grafana`, `Monitoring`
- [What is the purpose of Prometheus and Grafana in monitoring?](../topics/prometheus.md#what-is-the-purpose-of-prometheus-and-grafana-in-monitoring) — Prometheus · tags: `Grafana`, `Monitoring`
- [Your organization wants to implement end-to-end observability across microservices, Kubernetes clusters, cloud infrastructure, APIs, and databases using Prometheus, Grafana, ELK Stack, Splunk, OpenTelemetry, and Azure Monitor, aiming to reduce MTTR by 65% and improve platform reliability. How would you design the monitoring, alerting, logging, and incident management architecture?](../topics/incident-response.md#your-organization-wants-to-implement-end-to-end-observability-across-microservic) — Incident Response · tags: `OpenTelemetry`, `Prometheus`, `Grafana`, `Alerting`

## Helm

- [Helm rollback worked. App still broken. Logs silent. What now?](../topics/deployment-strategies.md#helm-rollback-worked-app-still-broken-logs-silent-what-now) — Deployment Strategies · tags: `Helm`
- [If Git is already the source of truth, why do we need Argo CD? Why not deploy directly using the CI/CD pipeline with Helm or kubectl?](../topics/argocd.md#if-git-is-already-the-source-of-truth-why-do-we-need-argo-cd-why-not-deploy-dire) — ArgoCD · tags: `Helm`, `CI/CD`, `Git`

## High Availability

- [How do you ensure high availability and disaster recovery in AWS?](../topics/disaster-recovery.md#how-do-you-ensure-high-availability-and-disaster-recovery-in-aws) — Disaster Recovery · tags: `High Availability`, `AWS`

## HPA

- [Design an HPA + Cluster Autoscaler solution capable of handling a 5× traffic spike within three minutes.](../topics/capacity-planning.md#design-an-hpa-cluster-autoscaler-solution-capable-of-handling-a-5x-traffic-spike) — Capacity Planning · tags: `HPA`
- [How did you deploy components like HPA, Karpenter, Metrics Server, and CoreDNS? Did you use Terraform?](../topics/capacity-planning.md#how-did-you-deploy-components-like-hpa-karpenter-metrics-server-and-coredns-did-) — Capacity Planning · tags: `Terraform`, `HPA`
- [How do you use hpa in prod env and what kind of metric target in cluster](../topics/capacity-planning.md#how-do-you-use-hpa-in-prod-env-and-what-kind-of-metric-target-in-cluster) — Capacity Planning · tags: `HPA`
- [How does Horizontal Pod Autoscaler (HPA) make scaling decisions?](../topics/capacity-planning.md#how-does-horizontal-pod-autoscaler-hpa-make-scaling-decisions) — Capacity Planning · tags: `Kubernetes`, `HPA`
- [HPA refuses to scale even though CPU is clearly maxed out](../topics/capacity-planning.md#hpa-refuses-to-scale-even-though-cpu-is-clearly-maxed-out) — Capacity Planning · tags: `HPA`
- [HPA refuses to scale even though Prometheus shows CPU > 80%. Diagnose with cloud + K8s metrics.](../topics/capacity-planning.md#hpa-refuses-to-scale-even-though-prometheus-shows-cpu-80-diagnose-with-cloud-k8s) — Capacity Planning · tags: `Prometheus`, `Kubernetes`, `HPA`
- [What is HPA and how does it work?](../topics/capacity-planning.md#what-is-hpa-and-how-does-it-work) — Capacity Planning · tags: `HPA`
- [What is HPA?](../topics/capacity-planning.md#what-is-hpa) — Capacity Planning · tags: `HPA`
- [Why doesn't Horizontal Pod Autoscaler (HPA) solve every performance issue?](../topics/capacity-planning.md#why-doesn-t-horizontal-pod-autoscaler-hpa-solve-every-performance-issue) — Capacity Planning · tags: `Kubernetes`, `HPA`

## IAM

- [How would you configure Microsoft Entra ID and RBAC for an Azure Function accessing Azure AI Search, Key Vault, and Azure OpenAI?](../topics/azure-ad.md#how-would-you-configure-microsoft-entra-id-and-rbac-for-an-azure-function-access) — Azure AD · tags: `Vault`, `IAM`, `Azure`, `RBAC`

## Incident Response

- [A critical production deployment fails during a global release, affecting 80 million users and resulting in an estimated ₹350 Crore business impact. How would you investigate the root cause, coordinate incident response, perform rollback or recovery, and implement preventive controls to eliminate similar failures in future releases?](../topics/deployment-strategies.md#a-critical-production-deployment-fails-during-a-global-release-affecting-80-mill) — Deployment Strategies · tags: `Incident Response`
- [A deployment failed in Production. How would you troubleshoot?](../topics/deployment-strategies.md#a-deployment-failed-in-production-how-would-you-troubleshoot) — Deployment Strategies · tags: `Incident Response`
- [A failed production deployment across 1,200 microservices impacts 35 million customers within 30 minutes. What would be your incident response, rollback, and recovery strategy?](../topics/deployment-strategies.md#a-failed-production-deployment-across-1200-microservices-impacts-35-million-cust) — Deployment Strategies · tags: `Incident Response`
- [A production deployment failed, and users are impacted. What would your rollback strategy look like?](../topics/deployment-strategies.md#a-production-deployment-failed-and-users-are-impacted-what-would-your-rollback-s) — Deployment Strategies · tags: `Incident Response`
- [A production deployment failed. What steps would you take to troubleshoot and recover?](../topics/deployment-strategies.md#a-production-deployment-failed-what-steps-would-you-take-to-troubleshoot-and-rec) — Deployment Strategies · tags: `Incident Response`
- [How would you structure the failover process during a regional outage?](../topics/disaster-recovery.md#how-would-you-structure-the-failover-process-during-a-regional-outage) — Disaster Recovery · tags: `Incident Response`

## Ingress

- [Pod is Running but returning 503 - how do you debug at network, service, and ingress level?](../topics/incident-response.md#pod-is-running-but-returning-503-how-do-you-debug-at-network-service-and-ingress) — Incident Response · tags: `Ingress`, `Kubernetes`

## IRSA

- [What is IRSA and how is it used in Kubernetes?](../topics/iam.md#what-is-irsa-and-how-is-it-used-in-kubernetes) — IAM · tags: `Kubernetes`, `IRSA`

## Jenkins

- [A Jenkins pipeline completed successfully, but the latest changes are not visible in production. What components would you verify before concluding the deployment failed?](../topics/deployment-strategies.md#a-jenkins-pipeline-completed-successfully-but-the-latest-changes-are-not-visible) — Deployment Strategies · tags: `Jenkins`, `CI/CD`
- [DevOps Engineer (AWS, Azure, Kubernetes, Terraform, Jenkins) – How do you implement continuous deployment in your workflow?](../topics/kubernetes.md#devops-engineer-aws-azure-kubernetes-terraform-jenkins-how-do-you-implement-cont) — Kubernetes · tags: `Terraform`, `Jenkins`, `AWS`, `Azure`
- [Docker, Kubernetes & Jenkins](../topics/kubernetes.md#docker-kubernetes-jenkins) — Kubernetes · tags: `Docker`, `Jenkins`
- [Explain how you solved production problems using Docker, Kubernetes, Terraform, or Jenkins.](../topics/kubernetes.md#explain-how-you-solved-production-problems-using-docker-kubernetes-terraform-or-) — Kubernetes · tags: `Docker`, `Terraform`, `Jenkins`
- [How can you ensure high availability in Jenkins ?](../topics/high-availability.md#how-can-you-ensure-high-availability-in-jenkins) — High Availability · tags: `Jenkins`
- [How did you configure SonarQube with Jenkins?](../topics/devsecops.md#how-did-you-configure-sonarqube-with-jenkins) — DevSecOps · tags: `Jenkins`
- [How do Jenkins, Docker, Kubernetes, Terraform, Prometheus, and Grafana work together in a complete CI/CD pipeline?](../topics/prometheus.md#how-do-jenkins-docker-kubernetes-terraform-prometheus-and-grafana-work-together-) — Prometheus · tags: `Grafana`, `Kubernetes`, `Docker`, `Terraform`
- [How do you configure and integrate tools like Jira, GIT/Bitbucket, Jenkins, Artifactory, and Ansible Tower?](../topics/ansible.md#how-do-you-configure-and-integrate-tools-like-jira-git-bitbucket-jenkins-artifac) — Ansible · tags: `Jenkins`, `Git`
- [How do you implement rollback strategy in Jenkins pipeline?](../topics/deployment-strategies.md#how-do-you-implement-rollback-strategy-in-jenkins-pipeline) — Deployment Strategies · tags: `Jenkins`, `CI/CD`
- [How do you integrate Jenkins with Docker and Kubernetes?](../topics/kubernetes.md#how-do-you-integrate-jenkins-with-docker-and-kubernetes) — Kubernetes · tags: `Docker`, `Jenkins`
- [How do you roll back a failed deployment in Jenkins?](../topics/deployment-strategies.md#how-do-you-roll-back-a-failed-deployment-in-jenkins) — Deployment Strategies · tags: `Jenkins`
- [If Docker images are built in Jenkins but security scanning must happen in GitHub Actions, how would you design the workflow?](../topics/docker.md#if-docker-images-are-built-in-jenkins-but-security-scanning-must-happen-in-githu) — Docker · tags: `Jenkins`, `GitHub Actions`
- [Jenkins and Docker troubleshooting](../topics/docker.md#jenkins-and-docker-troubleshooting) — Docker · tags: `Jenkins`
- [Jenkins debugging & Helm deployments](../topics/helm.md#jenkins-debugging-helm-deployments) — Helm · tags: `Jenkins`
- [Jenkins deployed via Helm — how do you update plugins?](../topics/helm.md#jenkins-deployed-via-helm-how-do-you-update-plugins) — Helm · tags: `Jenkins`
- [Suppose a production deployment fails and Jenkins catches it. How do you perform rollback and what responsibilities did you handle?](../topics/deployment-strategies.md#suppose-a-production-deployment-fails-and-jenkins-catches-it-how-do-you-perform-) — Deployment Strategies · tags: `Jenkins`
- [Why do we integrate SonarQube with Jenkins?](../topics/devsecops.md#why-do-we-integrate-sonarqube-with-jenkins) — DevSecOps · tags: `Jenkins`
- [Your organization supports over 300 million users across 50 countries, deploying applications that process more than 15 billion API requests daily. Frequent deployment failures and infrastructure bottlenecks are impacting customer experience and business revenue. How would you design a highly available DevOps platform using Kubernetes, Docker, Terraform, Jenkins, GitHub Actions, Azure DevOps, and AWS/Azure to achieve 99.99% uptime and 80% deployment automation?](../topics/kubernetes.md#your-organization-supports-over-300-million-users-across-50-countries-deploying-) — Kubernetes · tags: `Docker`, `Terraform`, `Jenkins`, `GitHub Actions`

## Kubernetes

- [A deployment completed successfully. All Kubernetes pods are Running. But users are getting 503 Service Unavailable. How would you troubleshoot it?](../topics/incident-response.md#a-deployment-completed-successfully-all-kubernetes-pods-are-running-but-users-ar) — Incident Response · tags: `Kubernetes`
- [An Amazon EKS application starts returning intermittent 502/503 errors immediately after deployment. How would you identify whether the issue is related to Kubernetes, the Load Balancer, or the application?](../topics/incident-response.md#an-amazon-eks-application-starts-returning-intermittent-502-503-errors-immediate) — Incident Response · tags: `EKS`, `Kubernetes`, `Load Balancing`
- [Any critical incident that happened within your system related to kubernetes, And how you were able to fix it?](../topics/incident-response.md#any-critical-incident-that-happened-within-your-system-related-to-kubernetes-and) — Incident Response · tags: `Kubernetes`
- [Azure Kubernetes Service (AKS) & Docker](../topics/aks.md#azure-kubernetes-service-aks-docker) — AKS · tags: `Kubernetes`, `Docker`, `Azure`
- [Deploy a real application using: Git → CI/CD → Docker → Kubernetes → Cloud → Monitoring](../topics/monitoring.md#deploy-a-real-application-using-git-ci-cd-docker-kubernetes-cloud-monitoring) — Monitoring · tags: `Kubernetes`, `Docker`, `CI/CD`, `Git`
- [Design a multi-cluster Kubernetes architecture with an Active cluster in Mumbai and a DR cluster in Singapore (RTO: 15 min, RPO: 1 min).](../topics/disaster-recovery.md#design-a-multi-cluster-kubernetes-architecture-with-an-active-cluster-in-mumbai-) — Disaster Recovery · tags: `Kubernetes`, `System Design`
- [Explain Kubernetes RBAC and how it controls access to cluster resources.](../topics/iam.md#explain-kubernetes-rbac-and-how-it-controls-access-to-cluster-resources) — IAM · tags: `Kubernetes`, `RBAC`
- [Explain the Memory Ladder — Cluster → Namespace → Deployment → ReplicaSet → Pod → Container → Service → Ingress.](../topics/ingress.md#explain-the-memory-ladder-cluster-namespace-deployment-replicaset-pod-container-) — Ingress · tags: `Kubernetes`, `Docker`
- [Explain your experience with Kubernetes or Amazon EKS. What challenges have you faced while managing workloads?](../topics/eks.md#explain-your-experience-with-kubernetes-or-amazon-eks-what-challenges-have-you-f) — EKS · tags: `Kubernetes`
- [Helm & Kubernetes deployments](../topics/helm.md#helm-kubernetes-deployments) — Helm · tags: `Kubernetes`
- [How did you design your Kubernetes (EKS) architecture, and what were the key design decisions?](../topics/eks.md#how-did-you-design-your-kubernetes-eks-architecture-and-what-were-the-key-design) — EKS · tags: `Kubernetes`, `System Design`
- [How do Jenkins, Docker, Kubernetes, Terraform, Prometheus, and Grafana work together in a complete CI/CD pipeline?](../topics/prometheus.md#how-do-jenkins-docker-kubernetes-terraform-prometheus-and-grafana-work-together-) — Prometheus · tags: `Grafana`, `Kubernetes`, `Docker`, `Terraform`
- [How do you deploy and manage applications on Amazon EKS/Kubernetes?](../topics/eks.md#how-do-you-deploy-and-manage-applications-on-amazon-eks-kubernetes) — EKS · tags: `Kubernetes`
- [How do you handle autoscaling in Kubernetes?](../topics/capacity-planning.md#how-do-you-handle-autoscaling-in-kubernetes) — Capacity Planning · tags: `Kubernetes`
- [How do you implement RBAC in Kubernetes?](../topics/iam.md#how-do-you-implement-rbac-in-kubernetes) — IAM · tags: `Kubernetes`, `RBAC`
- [How do you monitor Kubernetes clusters using CloudWatch, Prometheus, and Grafana?](../topics/prometheus.md#how-do-you-monitor-kubernetes-clusters-using-cloudwatch-prometheus-and-grafana) — Prometheus · tags: `Grafana`, `Monitoring`, `Kubernetes`
- [How do you monitor the logs for pods running in an EKS cluster?](../topics/eks.md#how-do-you-monitor-the-logs-for-pods-running-in-an-eks-cluster) — EKS · tags: `Kubernetes`
- [How do you roll back a failed Kubernetes deployment?](../topics/deployment-strategies.md#how-do-you-roll-back-a-failed-kubernetes-deployment) — Deployment Strategies · tags: `Kubernetes`
- [How does Horizontal Pod Autoscaler (HPA) make scaling decisions?](../topics/capacity-planning.md#how-does-horizontal-pod-autoscaler-hpa-make-scaling-decisions) — Capacity Planning · tags: `Kubernetes`, `HPA`
- [How does Prometheus work for monitoring in a Kubernetes cluster?](../topics/prometheus.md#how-does-prometheus-work-for-monitoring-in-a-kubernetes-cluster) — Prometheus · tags: `Monitoring`, `Kubernetes`
- [How does traffic flow from User to Ingress to Service to Pod?](../topics/ingress.md#how-does-traffic-flow-from-user-to-ingress-to-service-to-pod) — Ingress · tags: `Kubernetes`
- [How high availability will be ensured in Kubernetes cluster when running a stateful application ?](../topics/high-availability.md#how-high-availability-will-be-ensured-in-kubernetes-cluster-when-running-a-state) — High Availability · tags: `Kubernetes`
- [How would you design a multi-region Kubernetes architecture for high availability?](../topics/high-availability.md#how-would-you-design-a-multi-region-kubernetes-architecture-for-high-availabilit) — High Availability · tags: `Kubernetes`, `System Design`
- [How would you troubleshoot intermittent 503 errors in Kubernetes?](../topics/incident-response.md#how-would-you-troubleshoot-intermittent-503-errors-in-kubernetes) — Incident Response · tags: `Kubernetes`
- [HPA refuses to scale even though Prometheus shows CPU > 80%. Diagnose with cloud + K8s metrics.](../topics/capacity-planning.md#hpa-refuses-to-scale-even-though-prometheus-shows-cpu-80-diagnose-with-cloud-k8s) — Capacity Planning · tags: `Prometheus`, `Kubernetes`, `HPA`
- [If the Kubernetes etcd database is lost, what would be your disaster recovery approach?](../topics/disaster-recovery.md#if-the-kubernetes-etcd-database-is-lost-what-would-be-your-disaster-recovery-app) — Disaster Recovery · tags: `Kubernetes`, `Databases`
- [Imagine you're the on-call DevOps/SRE engineer for a production Kubernetes cluster. One worker node suddenly becomes NotReady. The cluster is serving live customer traffic. What happens next, and how would you respond?](../topics/on-call.md#imagine-you-re-the-on-call-devops-sre-engineer-for-a-production-kubernetes-clust) — On-Call · tags: `SRE`, `Kubernetes`
- [In Kubernetes, what is RBAC?](../topics/iam.md#in-kubernetes-what-is-rbac) — IAM · tags: `Kubernetes`, `RBAC`
- [It's 2 AM. PagerDuty alerts that 40% of the Pods in your Payments service are in CrashLoopBackOff, while the remaining 60% are still serving traffic. You have 5 minutes before the SLA is breached. Walk me through your response.](../topics/on-call.md#it-s-2-am-pagerduty-alerts-that-40-of-the-pods-in-your-payments-service-are-in-c) — On-Call · tags: `Kubernetes`
- [Kubernetes pods are Running but users receive 503 errors. What will you check?](../topics/incident-response.md#kubernetes-pods-are-running-but-users-receive-503-errors-what-will-you-check) — Incident Response · tags: `Kubernetes`

## Linux

- [How did you use Linux in your CI/CD pipeline?](../topics/ci-cd.md#how-did-you-use-linux-in-your-ci-cd-pipeline) — CI/CD · tags: `Linux`
- [How do you establish connectivity between two Linux servers using Ansible?](../topics/ansible.md#how-do-you-establish-connectivity-between-two-linux-servers-using-ansible) — Ansible · tags: `Linux`
- [What happens when systemd units fail intermittently on EKS nodes? How do you detect and heal?](../topics/eks.md#what-happens-when-systemd-units-fail-intermittently-on-eks-nodes-how-do-you-dete) — EKS · tags: `Linux`
- [What is Cgroups and Namespace in Linux](../topics/kubernetes.md#what-is-cgroups-and-namespace-in-linux) — Kubernetes · tags: `Linux`

## Load Balancing

- [An Amazon EKS application starts returning intermittent 502/503 errors immediately after deployment. How would you identify whether the issue is related to Kubernetes, the Load Balancer, or the application?](../topics/incident-response.md#an-amazon-eks-application-starts-returning-intermittent-502-503-errors-immediate) — Incident Response · tags: `EKS`, `Kubernetes`, `Load Balancing`
- [Difference between Ingress and LoadBalancer?](../topics/ingress.md#difference-between-ingress-and-loadbalancer) — Ingress · tags: `Load Balancing`
- [Difference between Reverse Proxy, Load Balancer, and API Gateway?](../topics/api-gateway.md#difference-between-reverse-proxy-load-balancer-and-api-gateway) — API Gateway · tags: `Load Balancing`
- [Explain Load Balancer, Reverse Proxy, and Ingress with real examples.](../topics/ingress.md#explain-load-balancer-reverse-proxy-and-ingress-with-real-examples) — Ingress · tags: `Load Balancing`
- [Explain the difference between Load Balancer, Reverse Proxy, and API Gateway with a real-world example.](../topics/api-gateway.md#explain-the-difference-between-load-balancer-reverse-proxy-and-api-gateway-with-) — API Gateway · tags: `Load Balancing`
- [How do multiple applications share a single Load Balancer and domain name in Kubernetes?](../topics/kubernetes.md#how-do-multiple-applications-share-a-single-load-balancer-and-domain-name-in-kub) — Kubernetes · tags: `Load Balancing`
- [Trace a request from load balancer to pod — and name what secures every hop.](../topics/kubernetes.md#trace-a-request-from-load-balancer-to-pod-and-name-what-secures-every-hop) — Kubernetes · tags: `Load Balancing`

## Logging

- [Does AWS WAF logging capture all requests? Explain.](../topics/network-security.md#does-aws-waf-logging-capture-all-requests-explain) — Network Security · tags: `Logging`, `AWS`
- [How would you configure cross-account IAM roles for centralized logging?](../topics/iam.md#how-would-you-configure-cross-account-iam-roles-for-centralized-logging) — IAM · tags: `Logging`
- [Logging, Metrics & Distributed Tracing](../topics/tracing.md#logging-metrics-distributed-tracing) — Tracing · tags: `Logging`
- [Monitoring & Logging: CloudWatch, Prometheus, ELK Stack](../topics/prometheus.md#monitoring-logging-cloudwatch-prometheus-elk-stack) — Prometheus · tags: `ELK`, `Logging`, `Monitoring`
- [Your organization wants to implement end-to-end observability across microservices, Kubernetes clusters, cloud infrastructure, APIs, and databases using Prometheus, Grafana, ELK Stack, Splunk, OpenTelemetry, and Azure Monitor, aiming to reduce MTTR by 65% and improve platform reliability. How would you design the monitoring, alerting, logging, and incident management architecture?](../topics/incident-response.md#your-organization-wants-to-implement-end-to-end-observability-across-microservic) — Incident Response · tags: `OpenTelemetry`, `Prometheus`, `Grafana`, `Alerting`

## Microservices

- [How will you design a microservice architecture application in Kubernetes ?](../topics/kubernetes.md#how-will-you-design-a-microservice-architecture-application-in-kubernetes) — Kubernetes · tags: `Microservices`, `System Design`
- [Microservice A cannot communicate with Microservice B. Both Pods are Running, DNS resolves correctly, Services and Endpoints exist, but TCP connections time out. How would you troubleshoot?](../topics/kubernetes.md#microservice-a-cannot-communicate-with-microservice-b-both-pods-are-running-dns-) — Kubernetes · tags: `DNS`, `Microservices`

## Monitoring

- [A monitoring alert fires every few minutes, but there is no real issue. How would you reduce alert fatigue?](../topics/alerting.md#a-monitoring-alert-fires-every-few-minutes-but-there-is-no-real-issue-how-would-) — Alerting · tags: `Monitoring`
- [AIOps and intelligent monitoring](../topics/observability.md#aiops-and-intelligent-monitoring) — Observability · tags: `Monitoring`
- [Compare CloudWatch, Prometheus, Grafana, and Dynatrace.](../topics/prometheus.md#compare-cloudwatch-prometheus-grafana-and-dynatrace) — Prometheus · tags: `Grafana`, `Monitoring`
- [Explain how you implement observability using logging, metrics, tracing, and monitoring across large distributed systems.](../topics/logging.md#explain-how-you-implement-observability-using-logging-metrics-tracing-and-monito) — Logging · tags: `Observability`, `Monitoring`
- [Explain your monitoring and alerting strategy.](../topics/alerting.md#explain-your-monitoring-and-alerting-strategy) — Alerting · tags: `Monitoring`
- [Have you used Prometheus for monitoring? How was it integrated with Grafana?](../topics/prometheus.md#have-you-used-prometheus-for-monitoring-how-was-it-integrated-with-grafana) — Prometheus · tags: `Grafana`, `Monitoring`
- [How do you achieve high availability targets like 99% uptime using monitoring and alerting?](../topics/high-availability.md#how-do-you-achieve-high-availability-targets-like-99-uptime-using-monitoring-and) — High Availability · tags: `Alerting`, `Monitoring`
- [How do you design monitoring and alerting to reduce alert fatigue?](../topics/alerting.md#how-do-you-design-monitoring-and-alerting-to-reduce-alert-fatigue) — Alerting · tags: `Monitoring`
- [How do you implement monitoring using Grafana and CloudWatch?](../topics/grafana.md#how-do-you-implement-monitoring-using-grafana-and-cloudwatch) — Grafana · tags: `Monitoring`
- [How do you monitor a production system — and what's the difference between monitoring and observability?](../topics/observability.md#how-do-you-monitor-a-production-system-and-what-s-the-difference-between-monitor) — Observability · tags: `Monitoring`
- [How do you monitor Kubernetes clusters using CloudWatch, Prometheus, and Grafana?](../topics/prometheus.md#how-do-you-monitor-kubernetes-clusters-using-cloudwatch-prometheus-and-grafana) — Prometheus · tags: `Grafana`, `Monitoring`, `Kubernetes`
- [How do you use CloudWatch Anomaly Detection and Cost Anomaly Detection?](../topics/observability.md#how-do-you-use-cloudwatch-anomaly-detection-and-cost-anomaly-detection) — Observability · tags: `Monitoring`
- [How does Prometheus work for monitoring in a Kubernetes cluster?](../topics/prometheus.md#how-does-prometheus-work-for-monitoring-in-a-kubernetes-cluster) — Prometheus · tags: `Monitoring`, `Kubernetes`
- [How Will you do monitoring and logging if there are multi cloud platforms. What solution will you provide.](../topics/logging.md#how-will-you-do-monitoring-and-logging-if-there-are-multi-cloud-platforms-what-s) — Logging · tags: `Monitoring`
- [How would you centralize AWS WAF monitoring and troubleshooting across 200+ AWS accounts?](../topics/network-security.md#how-would-you-centralize-aws-waf-monitoring-and-troubleshooting-across-200-aws-a) — Network Security · tags: `Monitoring`, `AWS`
- [if cloudwatch do alerting and monitor events, then what about cloudtrail do in AWS?](../topics/alerting.md#if-cloudwatch-do-alerting-and-monitor-events-then-what-about-cloudtrail-do-in-aw) — Alerting · tags: `Monitoring`, `AWS`
- [Monitoring & Logging: CloudWatch, Prometheus, ELK Stack](../topics/prometheus.md#monitoring-logging-cloudwatch-prometheus-elk-stack) — Prometheus · tags: `ELK`, `Logging`, `Monitoring`
- [Monitoring and observability](../topics/observability.md#monitoring-and-observability) — Observability · tags: `Monitoring`
- [Monitoring with Prometheus & Grafana](../topics/prometheus.md#monitoring-with-prometheus-grafana) — Prometheus · tags: `Grafana`, `Monitoring`
- [Monitoring, Troubleshooting & Production Support](../topics/incident-response.md#monitoring-troubleshooting-production-support) — Incident Response · tags: `Monitoring`
- [What are your responsibilities as an SRE beyond monitoring?](../topics/sre.md#what-are-your-responsibilities-as-an-sre-beyond-monitoring) — SRE · tags: `Monitoring`
- [What CI/CD practices have you implemented? Explain your experience with automated testing, deployment pipelines, rollback strategies, and monitoring.](../topics/deployment-strategies.md#what-ci-cd-practices-have-you-implemented-explain-your-experience-with-automated) — Deployment Strategies · tags: `Monitoring`, `CI/CD`
- [What is the purpose of Prometheus and Grafana in monitoring?](../topics/prometheus.md#what-is-the-purpose-of-prometheus-and-grafana-in-monitoring) — Prometheus · tags: `Grafana`, `Monitoring`
- [What tools do you use for logging and monitoring?](../topics/logging.md#what-tools-do-you-use-for-logging-and-monitoring) — Logging · tags: `Monitoring`
- [you said cloudwatch for alerting, let me know what alerting seup its there in project as i know its for metrics.](../topics/alerting.md#you-said-cloudwatch-for-alerting-let-me-know-what-alerting-seup-its-there-in-pro) — Alerting · tags: `Monitoring`
- [Your organization wants to implement end-to-end observability across microservices, Kubernetes clusters, cloud infrastructure, APIs, and databases using Prometheus, Grafana, ELK Stack, Splunk, OpenTelemetry, and Azure Monitor, aiming to reduce MTTR by 65% and improve platform reliability. How would you design the monitoring, alerting, logging, and incident management architecture?](../topics/incident-response.md#your-organization-wants-to-implement-end-to-end-observability-across-microservic) — Incident Response · tags: `OpenTelemetry`, `Prometheus`, `Grafana`, `Alerting`

## NCCL

- [What are NCCL logs, and why are they important in distributed training?](../topics/general.md#what-are-nccl-logs-and-why-are-they-important-in-distributed-training) — General · tags: `NCCL`

## Networking

- [Explain VPC, Subnets, NAT Gateway, and Internet Gateway.](../topics/vpc.md#explain-vpc-subnets-nat-gateway-and-internet-gateway) — VPC · tags: `Networking`
- [How the traffic from private subnet to this NAT Gateway is configured?](../topics/vpc.md#how-the-traffic-from-private-subnet-to-this-nat-gateway-is-configured) — VPC · tags: `Networking`
- [Networking: DNS, Firewall Rules, Virtual Networks](../topics/dns.md#networking-dns-firewall-rules-virtual-networks) — DNS · tags: `Networking`
- [What is the difference between a load balancer and an application firewall?](../topics/load-balancing.md#what-is-the-difference-between-a-load-balancer-and-an-application-firewall) — Load Balancing · tags: `Networking`

## Observability

- [Design a multi-region observability and incident platform that can survive the loss of two availability zones at once.](../topics/incident-response.md#design-a-multi-region-observability-and-incident-platform-that-can-survive-the-l) — Incident Response · tags: `Observability`, `System Design`
- [Explain how you implement observability using logging, metrics, tracing, and monitoring across large distributed systems.](../topics/logging.md#explain-how-you-implement-observability-using-logging-metrics-tracing-and-monito) — Logging · tags: `Observability`, `Monitoring`
- [Leadership wants to implement AI-powered Platform Engineering using GitOps, AI Agents, Observability, Prometheus, Grafana, OpenTelemetry, Microsoft Fabric, and predictive incident management. How would you design the enterprise platform architecture?](../topics/incident-response.md#leadership-wants-to-implement-ai-powered-platform-engineering-using-gitops-ai-ag) — Incident Response · tags: `OpenTelemetry`, `Prometheus`, `Grafana`, `Observability`
- [Your organization wants to implement end-to-end observability across microservices, Kubernetes clusters, cloud infrastructure, APIs, and databases using Prometheus, Grafana, ELK Stack, Splunk, OpenTelemetry, and Azure Monitor, aiming to reduce MTTR by 65% and improve platform reliability. How would you design the monitoring, alerting, logging, and incident management architecture?](../topics/incident-response.md#your-organization-wants-to-implement-end-to-end-observability-across-microservic) — Incident Response · tags: `OpenTelemetry`, `Prometheus`, `Grafana`, `Alerting`

## On-Call

- [How do you handle on-call support and incident management?](../topics/incident-response.md#how-do-you-handle-on-call-support-and-incident-management) — Incident Response · tags: `On-Call`
- [You're on-call and production is down. What's the FIRST command you run?](../topics/incident-response.md#you-re-on-call-and-production-is-down-what-s-the-first-command-you-run) — Incident Response · tags: `On-Call`

## OpenTelemetry

- [Leadership wants to implement AI-powered Platform Engineering using GitOps, AI Agents, Observability, Prometheus, Grafana, OpenTelemetry, Microsoft Fabric, and predictive incident management. How would you design the enterprise platform architecture?](../topics/incident-response.md#leadership-wants-to-implement-ai-powered-platform-engineering-using-gitops-ai-ag) — Incident Response · tags: `OpenTelemetry`, `Prometheus`, `Grafana`, `Observability`
- [Your organization wants to implement end-to-end observability across microservices, Kubernetes clusters, cloud infrastructure, APIs, and databases using Prometheus, Grafana, ELK Stack, Splunk, OpenTelemetry, and Azure Monitor, aiming to reduce MTTR by 65% and improve platform reliability. How would you design the monitoring, alerting, logging, and incident management architecture?](../topics/incident-response.md#your-organization-wants-to-implement-end-to-end-observability-across-microservic) — Incident Response · tags: `OpenTelemetry`, `Prometheus`, `Grafana`, `Alerting`

## PDB

- [What is a Pod Disruption Budget (PDB), and why is it important for production workloads?](../topics/kubernetes.md#what-is-a-pod-disruption-budget-pdb-and-why-is-it-important-for-production-workl) — Kubernetes · tags: `PDB`
- [What Is PDB?](../topics/general.md#what-is-pdb) — General · tags: `PDB`

## Prometheus

- [HPA refuses to scale even though Prometheus shows CPU > 80%. Diagnose with cloud + K8s metrics.](../topics/capacity-planning.md#hpa-refuses-to-scale-even-though-prometheus-shows-cpu-80-diagnose-with-cloud-k8s) — Capacity Planning · tags: `Prometheus`, `Kubernetes`, `HPA`
- [Leadership wants to implement AI-powered Platform Engineering using GitOps, AI Agents, Observability, Prometheus, Grafana, OpenTelemetry, Microsoft Fabric, and predictive incident management. How would you design the enterprise platform architecture?](../topics/incident-response.md#leadership-wants-to-implement-ai-powered-platform-engineering-using-gitops-ai-ag) — Incident Response · tags: `OpenTelemetry`, `Prometheus`, `Grafana`, `Observability`
- [Your organization wants to implement end-to-end observability across microservices, Kubernetes clusters, cloud infrastructure, APIs, and databases using Prometheus, Grafana, ELK Stack, Splunk, OpenTelemetry, and Azure Monitor, aiming to reduce MTTR by 65% and improve platform reliability. How would you design the monitoring, alerting, logging, and incident management architecture?](../topics/incident-response.md#your-organization-wants-to-implement-end-to-end-observability-across-microservic) — Incident Response · tags: `OpenTelemetry`, `Prometheus`, `Grafana`, `Alerting`

## PV

- [A Persistent Volume Claim remains in Pending state. What could be causing it?](../topics/storage.md#a-persistent-volume-claim-remains-in-pending-state-what-could-be-causing-it) — Storage · tags: `PV`
- [Explain PersistentVolume (PV) and PersistentVolumeClaim (PVC).](../topics/storage.md#explain-persistentvolume-pv-and-persistentvolumeclaim-pvc) — Storage · tags: `PVC`, `PV`
- [Explain PV and PVC in Kubernetes.](../topics/kubernetes.md#explain-pv-and-pvc-in-kubernetes) — Kubernetes · tags: `Storage`, `PVC`, `PV`
- [Storage (PV/PVC)](../topics/storage.md#storage-pv-pvc) — Storage · tags: `PVC`, `PV`
- [What is a Persistent Volume (PV) in Kubernetes?](../topics/kubernetes.md#what-is-a-persistent-volume-pv-in-kubernetes) — Kubernetes · tags: `Storage`, `PV`
- [What is the difference between PV and PVC?](../topics/storage.md#what-is-the-difference-between-pv-and-pvc) — Storage · tags: `PVC`, `PV`

## PVC

- [Explain PersistentVolume (PV) and PersistentVolumeClaim (PVC).](../topics/storage.md#explain-persistentvolume-pv-and-persistentvolumeclaim-pvc) — Storage · tags: `PVC`, `PV`
- [Explain PV and PVC in Kubernetes.](../topics/kubernetes.md#explain-pv-and-pvc-in-kubernetes) — Kubernetes · tags: `Storage`, `PVC`, `PV`
- [PVC binding issues](../topics/storage.md#pvc-binding-issues) — Storage · tags: `PVC`
- [Storage (PV/PVC)](../topics/storage.md#storage-pv-pvc) — Storage · tags: `PVC`, `PV`
- [What is PVC?](../topics/storage.md#what-is-pvc) — Storage · tags: `PVC`
- [What is the difference between PV and PVC?](../topics/storage.md#what-is-the-difference-between-pv-and-pvc) — Storage · tags: `PVC`, `PV`

## Python

- [Scripting & Automation: Python, Bash (or equivalent)](../topics/bash.md#scripting-automation-python-bash-or-equivalent) — Bash · tags: `Python`
- [Write a Python script to monitor CPU, Memory, and Disk utilization. If the usage exceeds 90%, generate an alert. You may use any Python packages.](../topics/alerting.md#write-a-python-script-to-monitor-cpu-memory-and-disk-utilization-if-the-usage-ex) — Alerting · tags: `Python`

## RBAC

- [Explain Kubernetes RBAC and how it controls access to cluster resources.](../topics/iam.md#explain-kubernetes-rbac-and-how-it-controls-access-to-cluster-resources) — IAM · tags: `Kubernetes`, `RBAC`
- [How do you implement RBAC in Kubernetes?](../topics/iam.md#how-do-you-implement-rbac-in-kubernetes) — IAM · tags: `Kubernetes`, `RBAC`
- [How would you configure Microsoft Entra ID and RBAC for an Azure Function accessing Azure AI Search, Key Vault, and Azure OpenAI?](../topics/azure-ad.md#how-would-you-configure-microsoft-entra-id-and-rbac-for-an-azure-function-access) — Azure AD · tags: `Vault`, `IAM`, `Azure`, `RBAC`
- [In Kubernetes, what is RBAC?](../topics/iam.md#in-kubernetes-what-is-rbac) — IAM · tags: `Kubernetes`, `RBAC`
- [Interview RBAC: RBAC controls who can perform which actions on which Azure resources.](../topics/iam.md#interview-rbac-rbac-controls-who-can-perform-which-actions-on-which-azure-resour) — IAM · tags: `Azure`, `RBAC`
- [RBAC & Security](../topics/iam.md#rbac-security) — IAM · tags: `RBAC`
- [Terraform accidentally modifies ArgoCD RBAC, causing ArgoCD to lose access to all applications. How would you recover?](../topics/iam.md#terraform-accidentally-modifies-argocd-rbac-causing-argocd-to-lose-access-to-all) — IAM · tags: `ArgoCD`, `Terraform`, `RBAC`
- [What do you mean by RBAC? (IAM/Kubernetes context.)](../topics/iam.md#what-do-you-mean-by-rbac-iam-kubernetes-context) — IAM · tags: `Kubernetes`, `RBAC`
- [What is RBAC and its components](../topics/iam.md#what-is-rbac-and-its-components) — IAM · tags: `RBAC`

## Redis

- [How does on-prem Kubernetes connect privately to AWS Redis?](../topics/kubernetes.md#how-does-on-prem-kubernetes-connect-privately-to-aws-redis) — Kubernetes · tags: `Redis`, `AWS`
- [Security Group vs NACL for Redis access?](../topics/network-security.md#security-group-vs-nacl-for-redis-access) — Network Security · tags: `Redis`
- [Suppose the Spring Boot application is running in Kubernetes, but Redis is an existing AWS ElastiCache cluster. How would you configure the application to access Redis?](../topics/kubernetes.md#suppose-the-spring-boot-application-is-running-in-kubernetes-but-redis-is-an-exi) — Kubernetes · tags: `Redis`, `AWS`
- [What if Kubernetes is running on-premises and Redis is in an AWS VPC?](../topics/kubernetes.md#what-if-kubernetes-is-running-on-premises-and-redis-is-in-an-aws-vpc) — Kubernetes · tags: `VPC`, `Redis`, `AWS`

## Security

- [How do you perform Docker image vulnerability scanning during build time and at the registry level?](../topics/docker.md#how-do-you-perform-docker-image-vulnerability-scanning-during-build-time-and-at-) — Docker · tags: `Security`
- [How would you integrate vulnerability scanning tools such as Trivy or Snyk into GitHub Actions?](../topics/github-actions.md#how-would-you-integrate-vulnerability-scanning-tools-such-as-trivy-or-snyk-into-) — GitHub Actions · tags: `Security`

## Shell Scripting

- [A shell script behaves differently when executed manually versus Jenkins. Why can this happen?](../topics/jenkins.md#a-shell-script-behaves-differently-when-executed-manually-versus-jenkins-why-can) — Jenkins · tags: `Shell Scripting`
- [Write a shell script to monitor disk usage and send an alert if utilization exceeds 85%.](../topics/alerting.md#write-a-shell-script-to-monitor-disk-usage-and-send-an-alert-if-utilization-exce) — Alerting · tags: `Shell Scripting`
- [Write down a script shell script so that it would go and identify the dead or stuck pods in the system?](../topics/kubernetes.md#write-down-a-script-shell-script-so-that-it-would-go-and-identify-the-dead-or-st) — Kubernetes · tags: `Shell Scripting`

## SRE

- [Imagine you're the on-call DevOps/SRE engineer for a production Kubernetes cluster. One worker node suddenly becomes NotReady. The cluster is serving live customer traffic. What happens next, and how would you respond?](../topics/on-call.md#imagine-you-re-the-on-call-devops-sre-engineer-for-a-production-kubernetes-clust) — On-Call · tags: `SRE`, `Kubernetes`

## Storage

- [Explain PV and PVC in Kubernetes.](../topics/kubernetes.md#explain-pv-and-pvc-in-kubernetes) — Kubernetes · tags: `Storage`, `PVC`, `PV`
- [What is a Persistent Volume (PV) in Kubernetes?](../topics/kubernetes.md#what-is-a-persistent-volume-pv-in-kubernetes) — Kubernetes · tags: `Storage`, `PV`

## System Design

- [A mission-critical .NET platform experiences API failures, database bottlenecks, security vulnerabilities, and recurring production incidents. How would you identify root causes, improve performance, and build an enterprise-grade resilient architecture?](../topics/databases.md#a-mission-critical-net-platform-experiences-api-failures-database-bottlenecks-se) — Databases · tags: `System Design`
- [Architecture of kubernetes](../topics/kubernetes.md#architecture-of-kubernetes) — Kubernetes · tags: `System Design`
- [Can you explain AWS architecture?](../topics/aws.md#can-you-explain-aws-architecture) — AWS · tags: `System Design`
- [CI/CD Pipeline Architecture](../topics/ci-cd.md#ci-cd-pipeline-architecture) — CI/CD · tags: `System Design`
- [Design a multi-cluster Kubernetes architecture with an Active cluster in Mumbai and a DR cluster in Singapore (RTO: 15 min, RPO: 1 min).](../topics/disaster-recovery.md#design-a-multi-cluster-kubernetes-architecture-with-an-active-cluster-in-mumbai-) — Disaster Recovery · tags: `Kubernetes`, `System Design`
- [Design a multi-region observability and incident platform that can survive the loss of two availability zones at once.](../topics/incident-response.md#design-a-multi-region-observability-and-incident-platform-that-can-survive-the-l) — Incident Response · tags: `Observability`, `System Design`
- [Design a scalable URL Shortener (like Bitly). Explain the architecture, database design, caching strategy, and how you would handle billions of requests.](../topics/databases.md#design-a-scalable-url-shortener-like-bitly-explain-the-architecture-database-des) — Databases · tags: `System Design`
- [Design, automate, and manage scalable cloud infrastructure using Microsoft Azure, Terraform, Azure DevOps, and Docker.](../topics/docker.md#design-automate-and-manage-scalable-cloud-infrastructure-using-microsoft-azure-t) — Docker · tags: `Terraform`, `Azure DevOps`, `Azure`, `System Design`
- [Expalin a high scalable application in AWS ?](../topics/aws.md#expalin-a-high-scalable-application-in-aws) — AWS · tags: `System Design`
- [Explain EC2, NAT, and NACL together in an AWS architecture.](../topics/aws.md#explain-ec2-nat-and-nacl-together-in-an-aws-architecture) — AWS · tags: `System Design`
- [Explain the Docker architecture.](../topics/docker.md#explain-the-docker-architecture) — Docker · tags: `System Design`
- [Explain the Jenkins architecture.](../topics/jenkins.md#explain-the-jenkins-architecture) — Jenkins · tags: `System Design`
- [Explain the Kubernetes architecture.](../topics/kubernetes.md#explain-the-kubernetes-architecture) — Kubernetes · tags: `System Design`
- [Have you worked on Terraform? How do you manage the state file? What is the Terraform architecture you are using?](../topics/terraform.md#have-you-worked-on-terraform-how-do-you-manage-the-state-file-what-is-the-terraf) — Terraform · tags: `System Design`
- [High availability vs read scalability?](../topics/high-availability.md#high-availability-vs-read-scalability) — High Availability · tags: `System Design`
- [How did you design your Kubernetes (EKS) architecture, and what were the key design decisions?](../topics/eks.md#how-did-you-design-your-kubernetes-eks-architecture-and-what-were-the-key-design) — EKS · tags: `Kubernetes`, `System Design`
- [How do you design a scalable Jenkins architecture?](../topics/jenkins.md#how-do-you-design-a-scalable-jenkins-architecture) — Jenkins · tags: `System Design`
- [How does Kubernetes handle pod failures and self-healing?](../topics/kubernetes.md#how-does-kubernetes-handle-pod-failures-and-self-healing) — Kubernetes · tags: `System Design`
- [How does Kubernetes perform self-healing?](../topics/kubernetes.md#how-does-kubernetes-perform-self-healing) — Kubernetes · tags: `System Design`
- [How will you design a microservice architecture application in Kubernetes ?](../topics/kubernetes.md#how-will-you-design-a-microservice-architecture-application-in-kubernetes) — Kubernetes · tags: `Microservices`, `System Design`
- [How would you connect 3 VPCs in one AWS account, 1 VPC in another AWS account, and an on-premises server? Explain the architecture and how they can access an Amazon RDS instance.](../topics/vpc.md#how-would-you-connect-3-vpcs-in-one-aws-account-1-vpc-in-another-aws-account-and) — VPC · tags: `Databases`, `AWS`, `System Design`
- [How would you design a highly available and fault-tolerant application architecture on AWS?](../topics/aws.md#how-would-you-design-a-highly-available-and-fault-tolerant-application-architect) — AWS · tags: `System Design`
- [How would you design a modular Terraform architecture for large-scale AWS environments?](../topics/terraform.md#how-would-you-design-a-modular-terraform-architecture-for-large-scale-aws-enviro) — Terraform · tags: `AWS`, `System Design`
- [How would you design a multi-region deployment in terraform, keeping zero downtime in mind ?](../topics/terraform.md#how-would-you-design-a-multi-region-deployment-in-terraform-keeping-zero-downtim) — Terraform · tags: `Deployment Strategies`, `System Design`
- [How would you design a multi-region Kubernetes architecture for high availability?](../topics/high-availability.md#how-would-you-design-a-multi-region-kubernetes-architecture-for-high-availabilit) — High Availability · tags: `Kubernetes`, `System Design`
- [How would you design a scalable CI/CD pipeline in Azure DevOps?](../topics/azure-devops.md#how-would-you-design-a-scalable-ci-cd-pipeline-in-azure-devops) — Azure DevOps · tags: `CI/CD`, `Azure`, `System Design`
- [How would you design a VPC architecture that supports multiple application teams without overlapping CIDR ranges?](../topics/vpc.md#how-would-you-design-a-vpc-architecture-that-supports-multiple-application-teams) — VPC · tags: `System Design`
- [Interview architecture: Design with compute + storage + database + network + identity + security + monitoring.](../topics/monitoring.md#interview-architecture-design-with-compute-storage-database-network-identity-sec) — Monitoring · tags: `Databases`, `System Design`
- [Java Full Stack Developer (Java, Spring Boot, Microservices, React, AWS) – Can you explain the differences between microservices and monolithic architecture?](../topics/aws.md#java-full-stack-developer-java-spring-boot-microservices-react-aws-can-you-expla) — AWS · tags: `System Design`
- [Kubernetes architecture and overall cluster structure.](../topics/kubernetes.md#kubernetes-architecture-and-overall-cluster-structure) — Kubernetes · tags: `System Design`

## Terraform

- [Design, automate, and manage scalable cloud infrastructure using Microsoft Azure, Terraform, Azure DevOps, and Docker.](../topics/docker.md#design-automate-and-manage-scalable-cloud-infrastructure-using-microsoft-azure-t) — Docker · tags: `Terraform`, `Azure DevOps`, `Azure`, `System Design`
- [DevOps Engineer (AWS, Azure, Kubernetes, Terraform, Jenkins) – How do you implement continuous deployment in your workflow?](../topics/kubernetes.md#devops-engineer-aws-azure-kubernetes-terraform-jenkins-how-do-you-implement-cont) — Kubernetes · tags: `Terraform`, `Jenkins`, `AWS`, `Azure`
- [Explain how you solved production problems using Docker, Kubernetes, Terraform, or Jenkins.](../topics/kubernetes.md#explain-how-you-solved-production-problems-using-docker-kubernetes-terraform-or-) — Kubernetes · tags: `Docker`, `Terraform`, `Jenkins`
- [How did you deploy components like HPA, Karpenter, Metrics Server, and CoreDNS? Did you use Terraform?](../topics/capacity-planning.md#how-did-you-deploy-components-like-hpa-karpenter-metrics-server-and-coredns-did-) — Capacity Planning · tags: `Terraform`, `HPA`
- [How do Jenkins, Docker, Kubernetes, Terraform, Prometheus, and Grafana work together in a complete CI/CD pipeline?](../topics/prometheus.md#how-do-jenkins-docker-kubernetes-terraform-prometheus-and-grafana-work-together-) — Prometheus · tags: `Grafana`, `Kubernetes`, `Docker`, `Terraform`
- [How do you create and manage Kubernetes clusters using Terraform?](../topics/kubernetes.md#how-do-you-create-and-manage-kubernetes-clusters-using-terraform) — Kubernetes · tags: `Terraform`
- [How do you spin up Kubernetes clusters with Terraform and what do the master and worker nodes actually do?](../topics/kubernetes.md#how-do-you-spin-up-kubernetes-clusters-with-terraform-and-what-do-the-master-and) — Kubernetes · tags: `Terraform`
- [Terraform accidentally modifies ArgoCD RBAC, causing ArgoCD to lose access to all applications. How would you recover?](../topics/iam.md#terraform-accidentally-modifies-argocd-rbac-causing-argocd-to-lose-access-to-all) — IAM · tags: `ArgoCD`, `Terraform`, `RBAC`
- [The Board approves a $1 billion Cloud & Platform Modernization Program using Kubernetes, Terraform, GitHub Actions, ArgoCD, Istio, AI Ops, and Azure OpenAI, targeting 99.99% uptime, 70% faster deployments, and 40% lower infrastructure costs. What execution roadmap would you recommend?](../topics/service-mesh.md#the-board-approves-a-1-billion-cloud-platform-modernization-program-using-kubern) — Service Mesh · tags: `ArgoCD`, `Kubernetes`, `Terraform`, `GitHub Actions`
- [The CTO approves a ₹1,400 Crore Enterprise DevOps Transformation Program to modernize software delivery across 400 engineering teams using CI/CD, Infrastructure as Code (Terraform), Kubernetes, GitOps, DevSecOps, and Cloud Automation, targeting 70% faster release cycles and 60% fewer production incidents. What implementation roadmap, governance model, and change management strategy would you recommend?](../topics/devsecops.md#the-cto-approves-a-1400-crore-enterprise-devops-transformation-program-to-modern) — DevSecOps · tags: `ArgoCD`, `Kubernetes`, `Terraform`, `CI/CD`
- [The CTO launches a large-scale application modernization programme involving .NET 8, Azure, Kubernetes, DevSecOps, Terraform, CI/CD, and Cloud-Native Architecture. What migration roadmap, governance framework, and technical strategy would you recommend?](../topics/devsecops.md#the-cto-launches-a-large-scale-application-modernization-programme-involving-net) — DevSecOps · tags: `Kubernetes`, `Terraform`, `CI/CD`, `Azure`
- [Which deployment tools have you used (Docker, Kubernetes, Helm, Terraform)?](../topics/helm.md#which-deployment-tools-have-you-used-docker-kubernetes-helm-terraform) — Helm · tags: `Kubernetes`, `Docker`, `Terraform`
- [Your organization supports over 300 million users across 50 countries, deploying applications that process more than 15 billion API requests daily. Frequent deployment failures and infrastructure bottlenecks are impacting customer experience and business revenue. How would you design a highly available DevOps platform using Kubernetes, Docker, Terraform, Jenkins, GitHub Actions, Azure DevOps, and AWS/Azure to achieve 99.99% uptime and 80% deployment automation?](../topics/kubernetes.md#your-organization-supports-over-300-million-users-across-50-countries-deploying-) — Kubernetes · tags: `Docker`, `Terraform`, `Jenkins`, `GitHub Actions`

## Vault

- [How would you configure Microsoft Entra ID and RBAC for an Azure Function accessing Azure AI Search, Key Vault, and Azure OpenAI?](../topics/azure-ad.md#how-would-you-configure-microsoft-entra-id-and-rbac-for-an-azure-function-access) — Azure AD · tags: `Vault`, `IAM`, `Azure`, `RBAC`

## VPC

- [App communication with EC2 in private subnet behind Multi-AZ LB](../topics/high-availability.md#app-communication-with-ec2-in-private-subnet-behind-multi-az-lb) — High Availability · tags: `VPC`, `AWS`
- [Import an existing VPC into Terraform](../topics/terraform.md#import-an-existing-vpc-into-terraform) — Terraform · tags: `VPC`
- [What if Kubernetes is running on-premises and Redis is in an AWS VPC?](../topics/kubernetes.md#what-if-kubernetes-is-running-on-premises-and-redis-is-in-an-aws-vpc) — Kubernetes · tags: `VPC`, `Redis`, `AWS`
- [When designing a VPC architecture, should a Load Balancer be placed in a public subnet or private subnet? Why?](../topics/load-balancing.md#when-designing-a-vpc-architecture-should-a-load-balancer-be-placed-in-a-public-s) — Load Balancing · tags: `VPC`, `System Design`
- [You need to provision a VPC with 3 public subnets and 2 private subnets across 2 AZs. How will you do it using Terraform?](../topics/terraform.md#you-need-to-provision-a-vpc-with-3-public-subnets-and-2-private-subnets-across-2) — Terraform · tags: `VPC`

[← Study guides](./README.md) · [Home](../README.md)
