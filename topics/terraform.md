# Terraform

[Home](../README.md) > [Topics](./README.md) > **Terraform**

**60** real interview questions. Study this page end-to-end — open a detail page only when an answer is enriched.

## Table of contents

- [Overview](#overview)
- [Most asked](#most-asked)
- [Beginner](#beginner)
- [Intermediate](#intermediate)
- [Advanced](#advanced)
- [By interview round](#by-interview-round)
- [Companies asking](#companies-asking)
- [Recently added](#recently-added)
- [Related topics](#related-topics)
- [All questions](#all-questions)

## Overview

| | |
| --- | ---: |
| Questions | 60 |
| Easy / Medium / Hard | 5 / 50 / 5 |
| Companies | 5 |

## Most asked

- [What is Terraform?](../topics/terraform.md#what-is-terraform) — **6×** · Medium
  <a id="what-is-terraform"></a>
- [What is a Terraform State File, and why is it important?](../topics/terraform.md#what-is-a-terraform-state-file-and-why-is-it-important) — **3×** · Medium
  <a id="what-is-a-terraform-state-file-and-why-is-it-important"></a>
- [CI/CD Pipeline Automation (YAML Templates)](../topics/terraform.md#ci-cd-pipeline-automation-yaml-templates) — **2×** · Easy
  <a id="ci-cd-pipeline-automation-yaml-templates"></a>
- [Explain the Terraform workflow.](../topics/terraform.md#explain-the-terraform-workflow) — **2×** · Medium
  <a id="explain-the-terraform-workflow"></a>
- [How do you import an existing AWS resource into Terraform?](../topics/terraform.md#how-do-you-import-an-existing-aws-resource-into-terraform) — **2×** · Medium
  <a id="how-do-you-import-an-existing-aws-resource-into-terraform"></a>
- [How would you create the same infrastructure for Development, QA, UAT, and Production without duplicating code using Terraform?](../topics/terraform.md#how-would-you-create-the-same-infrastructure-for-development-qa-uat-and-producti) — **2×** · Easy
  <a id="how-would-you-create-the-same-infrastructure-for-development-qa-uat-and-producti"></a>
- [Terraform changes accidentally modify production resources. How would you recover?](../topics/terraform.md#terraform-changes-accidentally-modify-production-resources-how-would-you-recover) — **2×** · Medium
  <a id="terraform-changes-accidentally-modify-production-resources-how-would-you-recover"></a>
- [Terraform partially created infrastructure before failing. How would you recover safely?](../topics/terraform.md#terraform-partially-created-infrastructure-before-failing-how-would-you-recover-) — **2×** · Medium
  <a id="terraform-partially-created-infrastructure-before-failing-how-would-you-recover-"></a>
- [Terraform state is 300MB and planning takes 15 minutes. How would you optimize it?](../topics/terraform.md#terraform-state-is-300mb-and-planning-takes-15-minutes-how-would-you-optimize-it) — **2×** · Medium
  <a id="terraform-state-is-300mb-and-planning-takes-15-minutes-how-would-you-optimize-it"></a>
- [What are Terraform modules?](../topics/terraform.md#what-are-terraform-modules) — **2×** · Medium
  <a id="what-are-terraform-modules"></a>
- [What are variables and outputs in Terraform?](../topics/terraform.md#what-are-variables-and-outputs-in-terraform) — **2×** · Medium
  <a id="what-are-variables-and-outputs-in-terraform"></a>
- [What is a Terraform provider?](../topics/terraform.md#what-is-a-terraform-provider) — **2×** · Medium
  <a id="what-is-a-terraform-provider"></a>
- [What is a Terraform resource?](../topics/terraform.md#what-is-a-terraform-resource) — **2×** · Medium
  <a id="what-is-a-terraform-resource"></a>
- [What is remote state?](../topics/terraform.md#what-is-remote-state) — **2×** · Medium
  <a id="what-is-remote-state"></a>
- [What is state locking in Terraform?](../topics/terraform.md#what-is-state-locking-in-terraform) — **2×** · Medium
  <a id="what-is-state-locking-in-terraform"></a>
- [What is the difference between terraform plan and terraform apply?](../topics/terraform.md#what-is-the-difference-between-terraform-plan-and-terraform-apply) — **2×** · Medium
  <a id="what-is-the-difference-between-terraform-plan-and-terraform-apply"></a>
- [Why do we use an S3 bucket and DynamoDB for Terraform state?](../topics/terraform.md#why-do-we-use-an-s3-bucket-and-dynamodb-for-terraform-state) — **2×** · Medium
  <a id="why-do-we-use-an-s3-bucket-and-dynamodb-for-terraform-state"></a>
- [Why do we use Terraform?](../topics/terraform.md#why-do-we-use-terraform) — **2×** · Medium
  <a id="why-do-we-use-terraform"></a>
- [You need to provision 100 EC2 instances with different configurations across Development, QA, UAT, and Production environments using Terraform. What would you use, and why?](../topics/terraform.md#you-need-to-provision-100-ec2-instances-with-different-configurations-across-dev) — **2×** · Easy
  <a id="you-need-to-provision-100-ec2-instances-with-different-configurations-across-dev"></a>
- [Can you explain Terraform state files and how you manage/organize them?](../topics/terraform.md#can-you-explain-terraform-state-files-and-how-you-manage-organize-them) — **1×** · Medium
  <a id="can-you-explain-terraform-state-files-and-how-you-manage-organize-them"></a>
- [Can you walk through a real example of importing resources into Terraform?](../topics/terraform.md#can-you-walk-through-a-real-example-of-importing-resources-into-terraform) — **1×** · Medium
  <a id="can-you-walk-through-a-real-example-of-importing-resources-into-terraform"></a>
- [Could you provide a detailed example of structuring variables/maps for dynamic resource creation?](../topics/terraform.md#could-you-provide-a-detailed-example-of-structuring-variables-maps-for-dynamic-r) — **1×** · Hard
  <a id="could-you-provide-a-detailed-example-of-structuring-variables-maps-for-dynamic-r"></a>
- [Design and implement modern DevOps, CI/CD, Infrastructure as Code (IaC), and Kubernetes solutions.](../topics/terraform.md#design-and-implement-modern-devops-ci-cd-infrastructure-as-code-iac-and-kubernet) — **1×** · Medium
  <a id="design-and-implement-modern-devops-ci-cd-infrastructure-as-code-iac-and-kubernet"></a>
- [Difference between count and for_each.](../topics/terraform.md#difference-between-count-and-for-each) — **1×** · Easy
  <a id="difference-between-count-and-for-each"></a>
- [Explain Terraform Workspaces and their use cases.](../topics/terraform.md#explain-terraform-workspaces-and-their-use-cases) — **1×** · Medium
  <a id="explain-terraform-workspaces-and-their-use-cases"></a>

## Beginner

- [CI/CD Pipeline Automation (YAML Templates)](../topics/terraform.md#ci-cd-pipeline-automation-yaml-templates) — 2×
  <a id="ci-cd-pipeline-automation-yaml-templates"></a>
- [How would you create the same infrastructure for Development, QA, UAT, and Production without duplicating code using Terraform?](../topics/terraform.md#how-would-you-create-the-same-infrastructure-for-development-qa-uat-and-producti) — 2×
  <a id="how-would-you-create-the-same-infrastructure-for-development-qa-uat-and-producti"></a>
- [You need to provision 100 EC2 instances with different configurations across Development, QA, UAT, and Production environments using Terraform. What would you use, and why?](../topics/terraform.md#you-need-to-provision-100-ec2-instances-with-different-configurations-across-dev) — 2×
  <a id="you-need-to-provision-100-ec2-instances-with-different-configurations-across-dev"></a>
- [Difference between count and for_each.](../topics/terraform.md#difference-between-count-and-for-each) — 1×
  <a id="difference-between-count-and-for-each"></a>
- [How would you rate your Terraform proficiency on a scale of 1–5?](../topics/terraform.md#how-would-you-rate-your-terraform-proficiency-on-a-scale-of-1-5) — 1×
  <a id="how-would-you-rate-your-terraform-proficiency-on-a-scale-of-1-5"></a>

## Intermediate

- [What is Terraform?](../topics/terraform.md#what-is-terraform) — 6×
  <a id="what-is-terraform"></a>
- [What is a Terraform State File, and why is it important?](../topics/terraform.md#what-is-a-terraform-state-file-and-why-is-it-important) — 3×
  <a id="what-is-a-terraform-state-file-and-why-is-it-important"></a>
- [Explain the Terraform workflow.](../topics/terraform.md#explain-the-terraform-workflow) — 2×
  <a id="explain-the-terraform-workflow"></a>
- [How do you import an existing AWS resource into Terraform?](../topics/terraform.md#how-do-you-import-an-existing-aws-resource-into-terraform) — 2×
  <a id="how-do-you-import-an-existing-aws-resource-into-terraform"></a>
- [Terraform changes accidentally modify production resources. How would you recover?](../topics/terraform.md#terraform-changes-accidentally-modify-production-resources-how-would-you-recover) — 2×
  <a id="terraform-changes-accidentally-modify-production-resources-how-would-you-recover"></a>
- [Terraform partially created infrastructure before failing. How would you recover safely?](../topics/terraform.md#terraform-partially-created-infrastructure-before-failing-how-would-you-recover-) — 2×
  <a id="terraform-partially-created-infrastructure-before-failing-how-would-you-recover-"></a>
- [Terraform state is 300MB and planning takes 15 minutes. How would you optimize it?](../topics/terraform.md#terraform-state-is-300mb-and-planning-takes-15-minutes-how-would-you-optimize-it) — 2×
  <a id="terraform-state-is-300mb-and-planning-takes-15-minutes-how-would-you-optimize-it"></a>
- [What are Terraform modules?](../topics/terraform.md#what-are-terraform-modules) — 2×
  <a id="what-are-terraform-modules"></a>
- [What are variables and outputs in Terraform?](../topics/terraform.md#what-are-variables-and-outputs-in-terraform) — 2×
  <a id="what-are-variables-and-outputs-in-terraform"></a>
- [What is a Terraform provider?](../topics/terraform.md#what-is-a-terraform-provider) — 2×
  <a id="what-is-a-terraform-provider"></a>
- [What is a Terraform resource?](../topics/terraform.md#what-is-a-terraform-resource) — 2×
  <a id="what-is-a-terraform-resource"></a>
- [What is remote state?](../topics/terraform.md#what-is-remote-state) — 2×
  <a id="what-is-remote-state"></a>
- [What is state locking in Terraform?](../topics/terraform.md#what-is-state-locking-in-terraform) — 2×
  <a id="what-is-state-locking-in-terraform"></a>
- [What is the difference between terraform plan and terraform apply?](../topics/terraform.md#what-is-the-difference-between-terraform-plan-and-terraform-apply) — 2×
  <a id="what-is-the-difference-between-terraform-plan-and-terraform-apply"></a>
- [Why do we use an S3 bucket and DynamoDB for Terraform state?](../topics/terraform.md#why-do-we-use-an-s3-bucket-and-dynamodb-for-terraform-state) — 2×
  <a id="why-do-we-use-an-s3-bucket-and-dynamodb-for-terraform-state"></a>
- [Why do we use Terraform?](../topics/terraform.md#why-do-we-use-terraform) — 2×
  <a id="why-do-we-use-terraform"></a>
- [Can you explain Terraform state files and how you manage/organize them?](../topics/terraform.md#can-you-explain-terraform-state-files-and-how-you-manage-organize-them) — 1×
  <a id="can-you-explain-terraform-state-files-and-how-you-manage-organize-them"></a>
- [Can you walk through a real example of importing resources into Terraform?](../topics/terraform.md#can-you-walk-through-a-real-example-of-importing-resources-into-terraform) — 1×
  <a id="can-you-walk-through-a-real-example-of-importing-resources-into-terraform"></a>
- [Design and implement modern DevOps, CI/CD, Infrastructure as Code (IaC), and Kubernetes solutions.](../topics/terraform.md#design-and-implement-modern-devops-ci-cd-infrastructure-as-code-iac-and-kubernet) — 1×
  <a id="design-and-implement-modern-devops-ci-cd-infrastructure-as-code-iac-and-kubernet"></a>
- [Explain Terraform Workspaces and their use cases.](../topics/terraform.md#explain-terraform-workspaces-and-their-use-cases) — 1×
  <a id="explain-terraform-workspaces-and-their-use-cases"></a>
- [Explain your Terraform module structure for multiple environments.](../topics/terraform.md#explain-your-terraform-module-structure-for-multiple-environments) — 1×
  <a id="explain-your-terraform-module-structure-for-multiple-environments"></a>
- [Have you worked on Terraform recently, and which version(s)?](../topics/terraform.md#have-you-worked-on-terraform-recently-and-which-version-s) — 1×
  <a id="have-you-worked-on-terraform-recently-and-which-version-s"></a>
- [How did you deploy components like HPA, Karpenter, Metrics Server, and CoreDNS? Did you use Terraform?](../topics/terraform.md#how-did-you-deploy-components-like-hpa-karpenter-metrics-server-and-coredns-did-) — 1×
  <a id="how-did-you-deploy-components-like-hpa-karpenter-metrics-server-and-coredns-did-"></a>
- [How do you migrate Terraform state without recreating resources?](../topics/terraform.md#how-do-you-migrate-terraform-state-without-recreating-resources) — 1×
  <a id="how-do-you-migrate-terraform-state-without-recreating-resources"></a>
- [How does Terraform state locking work?](../topics/terraform.md#how-does-terraform-state-locking-work) — 1×
  <a id="how-does-terraform-state-locking-work"></a>
- [How will you manage environments like Dev, QA, Prod in Terraform?](../topics/terraform.md#how-will-you-manage-environments-like-dev-qa-prod-in-terraform) — 1×
  <a id="how-will-you-manage-environments-like-dev-qa-prod-in-terraform"></a>
- [How will you use Terraform modules in a real project?](../topics/terraform.md#how-will-you-use-terraform-modules-in-a-real-project) — 1×
  <a id="how-will-you-use-terraform-modules-in-a-real-project"></a>
- [How would you bring existing AWS resources (created outside Terraform) under Terraform management?](../topics/terraform.md#how-would-you-bring-existing-aws-resources-created-outside-terraform-under-terra) — 1×
  <a id="how-would-you-bring-existing-aws-resources-created-outside-terraform-under-terra"></a>
- [How would you design a modular Terraform architecture for large-scale AWS environments?](../topics/terraform.md#how-would-you-design-a-modular-terraform-architecture-for-large-scale-aws-enviro) — 1×
  <a id="how-would-you-design-a-modular-terraform-architecture-for-large-scale-aws-enviro"></a>
- [How would you enforce standards, governance, and reusability in Terraform modules?](../topics/terraform.md#how-would-you-enforce-standards-governance-and-reusability-in-terraform-modules) — 1×
  <a id="how-would-you-enforce-standards-governance-and-reusability-in-terraform-modules"></a>
- [How would you manage Infrastructure as Code for 200–300 AWS accounts?](../topics/terraform.md#how-would-you-manage-infrastructure-as-code-for-200-300-aws-accounts) — 1×
  <a id="how-would-you-manage-infrastructure-as-code-for-200-300-aws-accounts"></a>
- [How would you manage Terraform state across multiple accounts and environments?](../topics/terraform.md#how-would-you-manage-terraform-state-across-multiple-accounts-and-environments) — 1×
  <a id="how-would-you-manage-terraform-state-across-multiple-accounts-and-environments"></a>
- [How would you stop Terraform from managing a resource it currently manages?](../topics/terraform.md#how-would-you-stop-terraform-from-managing-a-resource-it-currently-manages) — 1×
  <a id="how-would-you-stop-terraform-from-managing-a-resource-it-currently-manages"></a>
- [Infrastructure as Code (IaC)](../topics/terraform.md#infrastructure-as-code-iac) — 1×
  <a id="infrastructure-as-code-iac"></a>
- [Terraform project architecture](../topics/terraform.md#terraform-project-architecture) — 1×
  <a id="terraform-project-architecture"></a>
- [What is a Terraform Backend? Explain the Backend configuration.](../topics/terraform.md#what-is-a-terraform-backend-explain-the-backend-configuration) — 1×
  <a id="what-is-a-terraform-backend-explain-the-backend-configuration"></a>
- [What is drift detection](../topics/terraform.md#what-is-drift-detection) — 1×
  <a id="what-is-drift-detection"></a>
- [What is Terraform and how do you use it in your cloud infrastructure?](../topics/terraform.md#what-is-terraform-and-how-do-you-use-it-in-your-cloud-infrastructure) — 1×
  <a id="what-is-terraform-and-how-do-you-use-it-in-your-cloud-infrastructure"></a>
- [What is Terraform Drift? How do you detect it?](../topics/terraform.md#what-is-terraform-drift-how-do-you-detect-it) — 1×
  <a id="what-is-terraform-drift-how-do-you-detect-it"></a>
- [What is the difference between a .tf file and variables in Terraform?](../topics/terraform.md#what-is-the-difference-between-a-tf-file-and-variables-in-terraform) — 1×
  <a id="what-is-the-difference-between-a-tf-file-and-variables-in-terraform"></a>
- [What is the purpose of Terraform in infrastructure as code?](../topics/terraform.md#what-is-the-purpose-of-terraform-in-infrastructure-as-code) — 1×
  <a id="what-is-the-purpose-of-terraform-in-infrastructure-as-code"></a>
- [Which IaC tool have you used for provisioning infrastructure?](../topics/terraform.md#which-iac-tool-have-you-used-for-provisioning-infrastructure) — 1×
  <a id="which-iac-tool-have-you-used-for-provisioning-infrastructure"></a>
- [Which meta-arguments have you used in Terraform (e.g., count, for_each, depends_on, lifecycle)?](../topics/terraform.md#which-meta-arguments-have-you-used-in-terraform-e-g-count-for-each-depends-on-li) — 1×
  <a id="which-meta-arguments-have-you-used-in-terraform-e-g-count-for-each-depends-on-li"></a>
- [Write Terraform code to provision an AWS EC2 instance.](../topics/terraform.md#write-terraform-code-to-provision-an-aws-ec2-instance) — 1×
  <a id="write-terraform-code-to-provision-an-aws-ec2-instance"></a>
- [You accidentally deleted a resource from Terraform code but don't want it to be destroyed. What will you do?](../topics/terraform.md#you-accidentally-deleted-a-resource-from-terraform-code-but-don-t-want-it-to-be-) — 1×
  <a id="you-accidentally-deleted-a-resource-from-terraform-code-but-don-t-want-it-to-be-"></a>
- [You need to deploy an EC2 instance and an S3 bucket, and output the instance public IP and bucket name. How will you do it?](../topics/terraform.md#you-need-to-deploy-an-ec2-instance-and-an-s3-bucket-and-output-the-instance-publ) — 1×
  <a id="you-need-to-deploy-an-ec2-instance-and-an-s3-bucket-and-output-the-instance-publ"></a>
- [You need to provision a VPC with 3 public subnets and 2 private subnets across 2 AZs. How will you do it using Terraform?](../topics/terraform.md#you-need-to-provision-a-vpc-with-3-public-subnets-and-2-private-subnets-across-2) — 1×
  <a id="you-need-to-provision-a-vpc-with-3-public-subnets-and-2-private-subnets-across-2"></a>
- [You need to update an AMI ID of an EC2 instance without downtime. How will you achieve this?](../topics/terraform.md#you-need-to-update-an-ami-id-of-an-ec2-instance-without-downtime-how-will-you-ac) — 1×
  <a id="you-need-to-update-an-ami-id-of-an-ec2-instance-without-downtime-how-will-you-ac"></a>
- [Your team is working on the same Terraform code. How will you handle the state file?](../topics/terraform.md#your-team-is-working-on-the-same-terraform-code-how-will-you-handle-the-state-fi) — 1×
  <a id="your-team-is-working-on-the-same-terraform-code-how-will-you-handle-the-state-fi"></a>
- [Your Terraform apply is failing due to a resource already exists error. How will you fix it?](../topics/terraform.md#your-terraform-apply-is-failing-due-to-a-resource-already-exists-error-how-will-) — 1×
  <a id="your-terraform-apply-is-failing-due-to-a-resource-already-exists-error-how-will-"></a>

## Advanced

- [Could you provide a detailed example of structuring variables/maps for dynamic resource creation?](../topics/terraform.md#could-you-provide-a-detailed-example-of-structuring-variables-maps-for-dynamic-r) — 1×
  <a id="could-you-provide-a-detailed-example-of-structuring-variables-maps-for-dynamic-r"></a>
- [How would you design Terraform code to manage a large number of similar resources (e.g., 100 Lambda functions) with varying configurations, without duplicating resource blocks?](../topics/terraform.md#how-would-you-design-terraform-code-to-manage-a-large-number-of-similar-resource) — 1×
  <a id="how-would-you-design-terraform-code-to-manage-a-large-number-of-similar-resource"></a>
- [If the Terraform State File is lost, how can it be recovered?](../topics/terraform.md#if-the-terraform-state-file-is-lost-how-can-it-be-recovered) — 1×
  <a id="if-the-terraform-state-file-is-lost-how-can-it-be-recovered"></a>
- [Is there a safer alternative to directly modifying the Terraform state file in a production environment?](../topics/terraform.md#is-there-a-safer-alternative-to-directly-modifying-the-terraform-state-file-in-a) — 1×
  <a id="is-there-a-safer-alternative-to-directly-modifying-the-terraform-state-file-in-a"></a>
- [What is statefile explain more about it and where to store and why if lost if doesn't have backup how do you regain statefile](../topics/terraform.md#what-is-statefile-explain-more-about-it-and-where-to-store-and-why-if-lost-if-do) — 1×
  <a id="what-is-statefile-explain-more-about-it-and-where-to-store-and-why-if-lost-if-do"></a>

## By interview round

### Other

- [What is the difference between a .tf file and variables in Terraform?](../topics/terraform.md#what-is-the-difference-between-a-tf-file-and-variables-in-terraform)

### Technical

- [Explain Terraform Workspaces and their use cases.](../topics/terraform.md#explain-terraform-workspaces-and-their-use-cases)
- [If the Terraform State File is lost, how can it be recovered?](../topics/terraform.md#if-the-terraform-state-file-is-lost-how-can-it-be-recovered)
- [What is a Terraform Backend? Explain the Backend configuration.](../topics/terraform.md#what-is-a-terraform-backend-explain-the-backend-configuration)
- [What is a Terraform State File, and why is it important?](../topics/terraform.md#what-is-a-terraform-state-file-and-why-is-it-important)
- [Write Terraform code to provision an AWS EC2 instance.](../topics/terraform.md#write-terraform-code-to-provision-an-aws-ec2-instance)

### Technical Round 1

- [Explain the Terraform workflow.](../topics/terraform.md#explain-the-terraform-workflow)
- [How do you import an existing AWS resource into Terraform?](../topics/terraform.md#how-do-you-import-an-existing-aws-resource-into-terraform)
- [How would you design a modular Terraform architecture for large-scale AWS environments?](../topics/terraform.md#how-would-you-design-a-modular-terraform-architecture-for-large-scale-aws-enviro)
- [How would you enforce standards, governance, and reusability in Terraform modules?](../topics/terraform.md#how-would-you-enforce-standards-governance-and-reusability-in-terraform-modules)
- [How would you manage Infrastructure as Code for 200–300 AWS accounts?](../topics/terraform.md#how-would-you-manage-infrastructure-as-code-for-200-300-aws-accounts)
- [How would you manage Terraform state across multiple accounts and environments?](../topics/terraform.md#how-would-you-manage-terraform-state-across-multiple-accounts-and-environments)
- [What are Terraform modules?](../topics/terraform.md#what-are-terraform-modules)
- [What are variables and outputs in Terraform?](../topics/terraform.md#what-are-variables-and-outputs-in-terraform)
- [What is a Terraform provider?](../topics/terraform.md#what-is-a-terraform-provider)
- [What is a Terraform resource?](../topics/terraform.md#what-is-a-terraform-resource)
- [What is remote state?](../topics/terraform.md#what-is-remote-state)
- [What is state locking in Terraform?](../topics/terraform.md#what-is-state-locking-in-terraform)
- [What is Terraform?](../topics/terraform.md#what-is-terraform)
- [What is the difference between terraform plan and terraform apply?](../topics/terraform.md#what-is-the-difference-between-terraform-plan-and-terraform-apply)
- [Why do we use an S3 bucket and DynamoDB for Terraform state?](../topics/terraform.md#why-do-we-use-an-s3-bucket-and-dynamodb-for-terraform-state)
- [Why do we use Terraform?](../topics/terraform.md#why-do-we-use-terraform)

### Unspecified

- [Can you explain Terraform state files and how you manage/organize them?](../topics/terraform.md#can-you-explain-terraform-state-files-and-how-you-manage-organize-them)
- [Can you walk through a real example of importing resources into Terraform?](../topics/terraform.md#can-you-walk-through-a-real-example-of-importing-resources-into-terraform)
- [CI/CD Pipeline Automation (YAML Templates)](../topics/terraform.md#ci-cd-pipeline-automation-yaml-templates)
- [Could you provide a detailed example of structuring variables/maps for dynamic resource creation?](../topics/terraform.md#could-you-provide-a-detailed-example-of-structuring-variables-maps-for-dynamic-r)
- [Design and implement modern DevOps, CI/CD, Infrastructure as Code (IaC), and Kubernetes solutions.](../topics/terraform.md#design-and-implement-modern-devops-ci-cd-infrastructure-as-code-iac-and-kubernet)
- [Difference between count and for_each.](../topics/terraform.md#difference-between-count-and-for-each)
- [Explain your Terraform module structure for multiple environments.](../topics/terraform.md#explain-your-terraform-module-structure-for-multiple-environments)
- [Have you worked on Terraform recently, and which version(s)?](../topics/terraform.md#have-you-worked-on-terraform-recently-and-which-version-s)
- [How did you deploy components like HPA, Karpenter, Metrics Server, and CoreDNS? Did you use Terraform?](../topics/terraform.md#how-did-you-deploy-components-like-hpa-karpenter-metrics-server-and-coredns-did-)
- [How do you migrate Terraform state without recreating resources?](../topics/terraform.md#how-do-you-migrate-terraform-state-without-recreating-resources)
- [How does Terraform state locking work?](../topics/terraform.md#how-does-terraform-state-locking-work)
- [How will you manage environments like Dev, QA, Prod in Terraform?](../topics/terraform.md#how-will-you-manage-environments-like-dev-qa-prod-in-terraform)
- [How will you use Terraform modules in a real project?](../topics/terraform.md#how-will-you-use-terraform-modules-in-a-real-project)
- [How would you bring existing AWS resources (created outside Terraform) under Terraform management?](../topics/terraform.md#how-would-you-bring-existing-aws-resources-created-outside-terraform-under-terra)
- [How would you create the same infrastructure for Development, QA, UAT, and Production without duplicating code using Terraform?](../topics/terraform.md#how-would-you-create-the-same-infrastructure-for-development-qa-uat-and-producti)
- [How would you design Terraform code to manage a large number of similar resources (e.g., 100 Lambda functions) with varying configurations, without duplicating resource blocks?](../topics/terraform.md#how-would-you-design-terraform-code-to-manage-a-large-number-of-similar-resource)
- [How would you rate your Terraform proficiency on a scale of 1–5?](../topics/terraform.md#how-would-you-rate-your-terraform-proficiency-on-a-scale-of-1-5)
- [How would you stop Terraform from managing a resource it currently manages?](../topics/terraform.md#how-would-you-stop-terraform-from-managing-a-resource-it-currently-manages)
- [Infrastructure as Code (IaC)](../topics/terraform.md#infrastructure-as-code-iac)
- [Is there a safer alternative to directly modifying the Terraform state file in a production environment?](../topics/terraform.md#is-there-a-safer-alternative-to-directly-modifying-the-terraform-state-file-in-a)
- [Terraform changes accidentally modify production resources. How would you recover?](../topics/terraform.md#terraform-changes-accidentally-modify-production-resources-how-would-you-recover)
- [Terraform partially created infrastructure before failing. How would you recover safely?](../topics/terraform.md#terraform-partially-created-infrastructure-before-failing-how-would-you-recover-)
- [Terraform project architecture](../topics/terraform.md#terraform-project-architecture)
- [Terraform state is 300MB and planning takes 15 minutes. How would you optimize it?](../topics/terraform.md#terraform-state-is-300mb-and-planning-takes-15-minutes-how-would-you-optimize-it)
- [What is drift detection](../topics/terraform.md#what-is-drift-detection)
- [What is statefile explain more about it and where to store and why if lost if doesn't have backup how do you regain statefile](../topics/terraform.md#what-is-statefile-explain-more-about-it-and-where-to-store-and-why-if-lost-if-do)
- [What is Terraform and how do you use it in your cloud infrastructure?](../topics/terraform.md#what-is-terraform-and-how-do-you-use-it-in-your-cloud-infrastructure)
- [What is Terraform Drift? How do you detect it?](../topics/terraform.md#what-is-terraform-drift-how-do-you-detect-it)
- [What is the purpose of Terraform in infrastructure as code?](../topics/terraform.md#what-is-the-purpose-of-terraform-in-infrastructure-as-code)
- [Which IaC tool have you used for provisioning infrastructure?](../topics/terraform.md#which-iac-tool-have-you-used-for-provisioning-infrastructure)
- [Which meta-arguments have you used in Terraform (e.g., count, for_each, depends_on, lifecycle)?](../topics/terraform.md#which-meta-arguments-have-you-used-in-terraform-e-g-count-for-each-depends-on-li)
- [You accidentally deleted a resource from Terraform code but don't want it to be destroyed. What will you do?](../topics/terraform.md#you-accidentally-deleted-a-resource-from-terraform-code-but-don-t-want-it-to-be-)
- [You need to deploy an EC2 instance and an S3 bucket, and output the instance public IP and bucket name. How will you do it?](../topics/terraform.md#you-need-to-deploy-an-ec2-instance-and-an-s3-bucket-and-output-the-instance-publ)
- [You need to provision 100 EC2 instances with different configurations across Development, QA, UAT, and Production environments using Terraform. What would you use, and why?](../topics/terraform.md#you-need-to-provision-100-ec2-instances-with-different-configurations-across-dev)
- [You need to provision a VPC with 3 public subnets and 2 private subnets across 2 AZs. How will you do it using Terraform?](../topics/terraform.md#you-need-to-provision-a-vpc-with-3-public-subnets-and-2-private-subnets-across-2)
- [You need to update an AMI ID of an EC2 instance without downtime. How will you achieve this?](../topics/terraform.md#you-need-to-update-an-ami-id-of-an-ec2-instance-without-downtime-how-will-you-ac)
- [Your team is working on the same Terraform code. How will you handle the state file?](../topics/terraform.md#your-team-is-working-on-the-same-terraform-code-how-will-you-handle-the-state-fi)
- [Your Terraform apply is failing due to a resource already exists error. How will you fix it?](../topics/terraform.md#your-terraform-apply-is-failing-due-to-a-resource-already-exists-error-how-will-)

## Companies asking

- [Argyll Infotech](../companies/argyll-infotech.md)
- [BNP Paribas](../companies/bnp-paribas.md)
- [Fineshift Software Pvt. Ltd.](../companies/fineshift-software-pvt-ltd.md)
- [Global Payments](../companies/global-payments.md)
- [TCS](../companies/tcs.md)

## Recently added

- [Terraform partially created infrastructure before failing. How would you recover safely?](../topics/terraform.md#terraform-partially-created-infrastructure-before-failing-how-would-you-recover-) — 2026-07-15
- [Terraform state is 300MB and planning takes 15 minutes. How would you optimize it?](../topics/terraform.md#terraform-state-is-300mb-and-planning-takes-15-minutes-how-would-you-optimize-it) — 2026-07-15
- [CI/CD Pipeline Automation (YAML Templates)](../topics/terraform.md#ci-cd-pipeline-automation-yaml-templates) — 2026-07-15
- [How do you import an existing AWS resource into Terraform?](../topics/terraform.md#how-do-you-import-an-existing-aws-resource-into-terraform) — 2026-07-15
- [What is Terraform?](../topics/terraform.md#what-is-terraform) — 2026-07-15
- [What is the difference between terraform plan and terraform apply?](../topics/terraform.md#what-is-the-difference-between-terraform-plan-and-terraform-apply) — 2026-07-15
- [What are Terraform modules?](../topics/terraform.md#what-are-terraform-modules) — 2026-07-15
- [What are variables and outputs in Terraform?](../topics/terraform.md#what-are-variables-and-outputs-in-terraform) — 2026-07-15
- [What is a Terraform resource?](../topics/terraform.md#what-is-a-terraform-resource) — 2026-07-15
- [What is a Terraform provider?](../topics/terraform.md#what-is-a-terraform-provider) — 2026-07-15
- [What is state locking in Terraform?](../topics/terraform.md#what-is-state-locking-in-terraform) — 2026-07-15
- [Why do we use an S3 bucket and DynamoDB for Terraform state?](../topics/terraform.md#why-do-we-use-an-s3-bucket-and-dynamodb-for-terraform-state) — 2026-07-15
- [What is remote state?](../topics/terraform.md#what-is-remote-state) — 2026-07-15
- [What is a Terraform State File, and why is it important?](../topics/terraform.md#what-is-a-terraform-state-file-and-why-is-it-important) — 2026-07-15
- [Explain the Terraform workflow.](../topics/terraform.md#explain-the-terraform-workflow) — 2026-07-15

## Related topics

- [Ansible](./ansible.md)

## All questions

| Question | Diff | Asked |
| --- | --- | ---: |
| [Can you explain Terraform state files and how you manage/organize them?](../topics/terraform.md#can-you-explain-terraform-state-files-and-how-you-manage-organize-them) | Medium | 1 |
| [Can you walk through a real example of importing resources into Terraform?](../topics/terraform.md#can-you-walk-through-a-real-example-of-importing-resources-into-terraform) | Medium | 1 |
| [CI/CD Pipeline Automation (YAML Templates)](../topics/terraform.md#ci-cd-pipeline-automation-yaml-templates) | Easy | 2 |
| [Could you provide a detailed example of structuring variables/maps for dynamic resource creation?](../topics/terraform.md#could-you-provide-a-detailed-example-of-structuring-variables-maps-for-dynamic-r) | Hard | 1 |
| [Design and implement modern DevOps, CI/CD, Infrastructure as Code (IaC), and Kubernetes solutions.](../topics/terraform.md#design-and-implement-modern-devops-ci-cd-infrastructure-as-code-iac-and-kubernet) | Medium | 1 |
| [Difference between count and for_each.](../topics/terraform.md#difference-between-count-and-for-each) | Easy | 1 |
| [Explain Terraform Workspaces and their use cases.](../topics/terraform.md#explain-terraform-workspaces-and-their-use-cases) | Medium | 1 |
| [Explain the Terraform workflow.](../topics/terraform.md#explain-the-terraform-workflow) | Medium | 2 |
| [Explain your Terraform module structure for multiple environments.](../topics/terraform.md#explain-your-terraform-module-structure-for-multiple-environments) | Medium | 1 |
| [Have you worked on Terraform recently, and which version(s)?](../topics/terraform.md#have-you-worked-on-terraform-recently-and-which-version-s) | Medium | 1 |
| [How did you deploy components like HPA, Karpenter, Metrics Server, and CoreDNS? Did you use Terraform?](../topics/terraform.md#how-did-you-deploy-components-like-hpa-karpenter-metrics-server-and-coredns-did-) | Medium | 1 |
| [How do you import an existing AWS resource into Terraform?](../topics/terraform.md#how-do-you-import-an-existing-aws-resource-into-terraform) | Medium | 2 |
| [How do you migrate Terraform state without recreating resources?](../topics/terraform.md#how-do-you-migrate-terraform-state-without-recreating-resources) | Medium | 1 |
| [How does Terraform state locking work?](../topics/terraform.md#how-does-terraform-state-locking-work) | Medium | 1 |
| [How will you manage environments like Dev, QA, Prod in Terraform?](../topics/terraform.md#how-will-you-manage-environments-like-dev-qa-prod-in-terraform) | Medium | 1 |
| [How will you use Terraform modules in a real project?](../topics/terraform.md#how-will-you-use-terraform-modules-in-a-real-project) | Medium | 1 |
| [How would you bring existing AWS resources (created outside Terraform) under Terraform management?](../topics/terraform.md#how-would-you-bring-existing-aws-resources-created-outside-terraform-under-terra) | Medium | 1 |
| [How would you create the same infrastructure for Development, QA, UAT, and Production without duplicating code using Terraform?](../topics/terraform.md#how-would-you-create-the-same-infrastructure-for-development-qa-uat-and-producti) | Easy | 2 |
| [How would you design a modular Terraform architecture for large-scale AWS environments?](../topics/terraform.md#how-would-you-design-a-modular-terraform-architecture-for-large-scale-aws-enviro) | Medium | 1 |
| [How would you design Terraform code to manage a large number of similar resources (e.g., 100 Lambda functions) with varying configurations, without duplicating resource blocks?](../topics/terraform.md#how-would-you-design-terraform-code-to-manage-a-large-number-of-similar-resource) | Hard | 1 |
| [How would you enforce standards, governance, and reusability in Terraform modules?](../topics/terraform.md#how-would-you-enforce-standards-governance-and-reusability-in-terraform-modules) | Medium | 1 |
| [How would you manage Infrastructure as Code for 200–300 AWS accounts?](../topics/terraform.md#how-would-you-manage-infrastructure-as-code-for-200-300-aws-accounts) | Medium | 1 |
| [How would you manage Terraform state across multiple accounts and environments?](../topics/terraform.md#how-would-you-manage-terraform-state-across-multiple-accounts-and-environments) | Medium | 1 |
| [How would you rate your Terraform proficiency on a scale of 1–5?](../topics/terraform.md#how-would-you-rate-your-terraform-proficiency-on-a-scale-of-1-5) | Easy | 1 |
| [How would you stop Terraform from managing a resource it currently manages?](../topics/terraform.md#how-would-you-stop-terraform-from-managing-a-resource-it-currently-manages) | Medium | 1 |
| [If the Terraform State File is lost, how can it be recovered?](../topics/terraform.md#if-the-terraform-state-file-is-lost-how-can-it-be-recovered) | Hard | 1 |
| [Infrastructure as Code (IaC)](../topics/terraform.md#infrastructure-as-code-iac) | Medium | 1 |
| [Is there a safer alternative to directly modifying the Terraform state file in a production environment?](../topics/terraform.md#is-there-a-safer-alternative-to-directly-modifying-the-terraform-state-file-in-a) | Hard | 1 |
| [Terraform changes accidentally modify production resources. How would you recover?](../topics/terraform.md#terraform-changes-accidentally-modify-production-resources-how-would-you-recover) | Medium | 2 |
| [Terraform partially created infrastructure before failing. How would you recover safely?](../topics/terraform.md#terraform-partially-created-infrastructure-before-failing-how-would-you-recover-) | Medium | 2 |
| [Terraform project architecture](../topics/terraform.md#terraform-project-architecture) | Medium | 1 |
| [Terraform state is 300MB and planning takes 15 minutes. How would you optimize it?](../topics/terraform.md#terraform-state-is-300mb-and-planning-takes-15-minutes-how-would-you-optimize-it) | Medium | 2 |
| [What are Terraform modules?](../topics/terraform.md#what-are-terraform-modules) | Medium | 2 |
| [What are variables and outputs in Terraform?](../topics/terraform.md#what-are-variables-and-outputs-in-terraform) | Medium | 2 |
| [What is a Terraform Backend? Explain the Backend configuration.](../topics/terraform.md#what-is-a-terraform-backend-explain-the-backend-configuration) | Medium | 1 |
| [What is a Terraform provider?](../topics/terraform.md#what-is-a-terraform-provider) | Medium | 2 |
| [What is a Terraform resource?](../topics/terraform.md#what-is-a-terraform-resource) | Medium | 2 |
| [What is a Terraform State File, and why is it important?](../topics/terraform.md#what-is-a-terraform-state-file-and-why-is-it-important) | Medium | 3 |
| [What is drift detection](../topics/terraform.md#what-is-drift-detection) | Medium | 1 |
| [What is remote state?](../topics/terraform.md#what-is-remote-state) | Medium | 2 |
| [What is state locking in Terraform?](../topics/terraform.md#what-is-state-locking-in-terraform) | Medium | 2 |
| [What is statefile explain more about it and where to store and why if lost if doesn't have backup how do you regain statefile](../topics/terraform.md#what-is-statefile-explain-more-about-it-and-where-to-store-and-why-if-lost-if-do) | Hard | 1 |
| [What is Terraform and how do you use it in your cloud infrastructure?](../topics/terraform.md#what-is-terraform-and-how-do-you-use-it-in-your-cloud-infrastructure) | Medium | 1 |
| [What is Terraform Drift? How do you detect it?](../topics/terraform.md#what-is-terraform-drift-how-do-you-detect-it) | Medium | 1 |
| [What is Terraform?](../topics/terraform.md#what-is-terraform) | Medium | 6 |
| [What is the difference between a .tf file and variables in Terraform?](../topics/terraform.md#what-is-the-difference-between-a-tf-file-and-variables-in-terraform) | Medium | 1 |
| [What is the difference between terraform plan and terraform apply?](../topics/terraform.md#what-is-the-difference-between-terraform-plan-and-terraform-apply) | Medium | 2 |
| [What is the purpose of Terraform in infrastructure as code?](../topics/terraform.md#what-is-the-purpose-of-terraform-in-infrastructure-as-code) | Medium | 1 |
| [Which IaC tool have you used for provisioning infrastructure?](../topics/terraform.md#which-iac-tool-have-you-used-for-provisioning-infrastructure) | Medium | 1 |
| [Which meta-arguments have you used in Terraform (e.g., count, for_each, depends_on, lifecycle)?](../topics/terraform.md#which-meta-arguments-have-you-used-in-terraform-e-g-count-for-each-depends-on-li) | Medium | 1 |
| [Why do we use an S3 bucket and DynamoDB for Terraform state?](../topics/terraform.md#why-do-we-use-an-s3-bucket-and-dynamodb-for-terraform-state) | Medium | 2 |
| [Why do we use Terraform?](../topics/terraform.md#why-do-we-use-terraform) | Medium | 2 |
| [Write Terraform code to provision an AWS EC2 instance.](../topics/terraform.md#write-terraform-code-to-provision-an-aws-ec2-instance) | Medium | 1 |
| [You accidentally deleted a resource from Terraform code but don't want it to be destroyed. What will you do?](../topics/terraform.md#you-accidentally-deleted-a-resource-from-terraform-code-but-don-t-want-it-to-be-) | Medium | 1 |
| [You need to deploy an EC2 instance and an S3 bucket, and output the instance public IP and bucket name. How will you do it?](../topics/terraform.md#you-need-to-deploy-an-ec2-instance-and-an-s3-bucket-and-output-the-instance-publ) | Medium | 1 |
| [You need to provision 100 EC2 instances with different configurations across Development, QA, UAT, and Production environments using Terraform. What would you use, and why?](../topics/terraform.md#you-need-to-provision-100-ec2-instances-with-different-configurations-across-dev) | Easy | 2 |
| [You need to provision a VPC with 3 public subnets and 2 private subnets across 2 AZs. How will you do it using Terraform?](../topics/terraform.md#you-need-to-provision-a-vpc-with-3-public-subnets-and-2-private-subnets-across-2) | Medium | 1 |
| [You need to update an AMI ID of an EC2 instance without downtime. How will you achieve this?](../topics/terraform.md#you-need-to-update-an-ami-id-of-an-ec2-instance-without-downtime-how-will-you-ac) | Medium | 1 |
| [Your team is working on the same Terraform code. How will you handle the state file?](../topics/terraform.md#your-team-is-working-on-the-same-terraform-code-how-will-you-handle-the-state-fi) | Medium | 1 |
| [Your Terraform apply is failing due to a resource already exists error. How will you fix it?](../topics/terraform.md#your-terraform-apply-is-failing-due-to-a-resource-already-exists-error-how-will-) | Medium | 1 |

## Learning resources

- Practice [most asked overall](../study-guides/most-asked.md)
- Filter by [difficulty](../study-guides/by-difficulty.md)
- Browse [companies](../companies/README.md)

[← All topics](./README.md) · [Home](../README.md)
