# Kubernetes

[Home](../README.md) > [Topics](./README.md) > **Kubernetes**

**98** real interview questions. Study this page end-to-end — open a detail page only when an answer is enriched.

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
| Questions | 98 |
| Easy / Medium / Hard | 7 / 79 / 12 |
| Companies | 10 |

## Most asked

- [How do you perform a zero-downtime Kubernetes cluster upgrade in production?](../topics/kubernetes.md#how-do-you-perform-a-zero-downtime-kubernetes-cluster-upgrade-in-production) — **5×** · Hard
  <a id="how-do-you-perform-a-zero-downtime-kubernetes-cluster-upgrade-in-production"></a>
- [How would you migrate a stateful application to Kubernetes with minimal downtime?](../topics/kubernetes.md#how-would-you-migrate-a-stateful-application-to-kubernetes-with-minimal-downtime) — **5×** · Medium
  <a id="how-would-you-migrate-a-stateful-application-to-kubernetes-with-minimal-downtime"></a>
- [After deployment, application latency suddenly doubles while CPU and memory remain normal. How would you approach the investigation?](../topics/kubernetes.md#after-deployment-application-latency-suddenly-doubles-while-cpu-and-memory-remai) — **4×** · Medium
  <a id="after-deployment-application-latency-suddenly-doubles-while-cpu-and-memory-remai"></a>
- [During a node group upgrade, several workloads become unavailable even though replicas exist. What production checks would you perform?](../topics/kubernetes.md#during-a-node-group-upgrade-several-workloads-become-unavailable-even-though-rep) — **4×** · Medium
  <a id="during-a-node-group-upgrade-several-workloads-become-unavailable-even-though-rep"></a>
- [How would you determine whether production failures originate from Kubernetes, networking, or the application itself?](../topics/kubernetes.md#how-would-you-determine-whether-production-failures-originate-from-kubernetes-ne) — **4×** · Medium
  <a id="how-would-you-determine-whether-production-failures-originate-from-kubernetes-ne"></a>
- [What indicators tell you that the issue is in the Kubernetes control plane versus the underlying AWS infrastructure?](../topics/kubernetes.md#what-indicators-tell-you-that-the-issue-is-in-the-kubernetes-control-plane-versu) — **4×** · Medium
  <a id="what-indicators-tell-you-that-the-issue-is-in-the-kubernetes-control-plane-versu"></a>
- [What is Exit Status 2 in Kubernetes?](../topics/kubernetes.md#what-is-exit-status-2-in-kubernetes) — **4×** · Medium
  <a id="what-is-exit-status-2-in-kubernetes"></a>
- [Your Kubernetes cluster is healthy but requests intermittently return 503. How do you troubleshoot it?](../topics/kubernetes.md#your-kubernetes-cluster-is-healthy-but-requests-intermittently-return-503-how-do) — **4×** · Medium
  <a id="your-kubernetes-cluster-is-healthy-but-requests-intermittently-return-503-how-do"></a>
- [Difference between Deployment, StatefulSet, DaemonSet, and Job.](../topics/kubernetes.md#difference-between-deployment-statefulset-daemonset-and-job) — **3×** · Medium
  <a id="difference-between-deployment-statefulset-daemonset-and-job"></a>
- [What is Blue-Green Deployment?](../topics/kubernetes.md#what-is-blue-green-deployment) — **3×** · Medium
  <a id="what-is-blue-green-deployment"></a>
- [A Kubernetes GPU pod requests 16GB VRAM but only gets 12GB due to fragmentation. How do you detect and fix it in real time?](../topics/kubernetes.md#a-kubernetes-gpu-pod-requests-16gb-vram-but-only-gets-12gb-due-to-fragmentation-) — **2×** · Medium
  <a id="a-kubernetes-gpu-pod-requests-16gb-vram-but-only-gets-12gb-due-to-fragmentation-"></a>
- [A Kubernetes pod keeps crashing. How do you investigate?](../topics/kubernetes.md#a-kubernetes-pod-keeps-crashing-how-do-you-investigate) — **2×** · Medium
  <a id="a-kubernetes-pod-keeps-crashing-how-do-you-investigate"></a>
- [A Pod is in CrashLoopBackOff. How would you troubleshoot it?](../topics/kubernetes.md#a-pod-is-in-crashloopbackoff-how-would-you-troubleshoot-it) — **2×** · Medium
  <a id="a-pod-is-in-crashloopbackoff-how-would-you-troubleshoot-it"></a>
- [A Pod is running but the application is not accessible. What would you check?](../topics/kubernetes.md#a-pod-is-running-but-the-application-is-not-accessible-what-would-you-check) — **2×** · Medium
  <a id="a-pod-is-running-but-the-application-is-not-accessible-what-would-you-check"></a>
- [An Amazon EKS application starts returning intermittent 502/503 errors immediately after deployment. How would you identify whether the issue is related to Kubernetes, the Load Balancer, or the application?](../topics/kubernetes.md#an-amazon-eks-application-starts-returning-intermittent-502-503-errors-immediate) — **2×** · Medium
  <a id="an-amazon-eks-application-starts-returning-intermittent-502-503-errors-immediate"></a>
- [Can you automate Kubernetes deployment?](../topics/kubernetes.md#can-you-automate-kubernetes-deployment) — **2×** · Medium
  <a id="can-you-automate-kubernetes-deployment"></a>
- [Can you explain how Kubernetes scheduling works?](../topics/kubernetes.md#can-you-explain-how-kubernetes-scheduling-works) — **2×** · Medium
  <a id="can-you-explain-how-kubernetes-scheduling-works"></a>
- [Difference between Pod and Container?](../topics/kubernetes.md#difference-between-pod-and-container) — **2×** · Easy · tags: `Docker`
  <a id="difference-between-pod-and-container"></a>
- [Explain about Kubernetes.](../topics/kubernetes.md#explain-about-kubernetes) — **2×** · Medium
  <a id="explain-about-kubernetes"></a>
- [Explain ClusterIP and NodePort. What is the difference between them?](../topics/kubernetes.md#explain-clusterip-and-nodeport-what-is-the-difference-between-them) — **2×** · Medium
  <a id="explain-clusterip-and-nodeport-what-is-the-difference-between-them"></a>
- [Explain Kubernetes RBAC and how it controls access to cluster resources.](../topics/kubernetes.md#explain-kubernetes-rbac-and-how-it-controls-access-to-cluster-resources) — **2×** · Medium
  <a id="explain-kubernetes-rbac-and-how-it-controls-access-to-cluster-resources"></a>
- [Explain PersistentVolume (PV) and PersistentVolumeClaim (PVC).](../topics/kubernetes.md#explain-persistentvolume-pv-and-persistentvolumeclaim-pvc) — **2×** · Medium
  <a id="explain-persistentvolume-pv-and-persistentvolumeclaim-pvc"></a>
- [Explain the end-to-end request flow in Kubernetes?](../topics/kubernetes.md#explain-the-end-to-end-request-flow-in-kubernetes) — **2×** · Medium
  <a id="explain-the-end-to-end-request-flow-in-kubernetes"></a>
- [Explain the Kubernetes architecture.](../topics/kubernetes.md#explain-the-kubernetes-architecture) — **2×** · Hard · tags: `System Design`
  <a id="explain-the-kubernetes-architecture"></a>
- [Explain the Kubernetes scheduling process.](../topics/kubernetes.md#explain-the-kubernetes-scheduling-process) — **2×** · Medium
  <a id="explain-the-kubernetes-scheduling-process"></a>

## Beginner

- [Difference between Pod and Container?](../topics/kubernetes.md#difference-between-pod-and-container) — 2× · tags: `Docker`
  <a id="difference-between-pod-and-container"></a>
- [How would you check if a GPU pod in Kubernetes is using the GPU assigned to it?](../topics/kubernetes.md#how-would-you-check-if-a-gpu-pod-in-kubernetes-is-using-the-gpu-assigned-to-it) — 2×
  <a id="how-would-you-check-if-a-gpu-pod-in-kubernetes-is-using-the-gpu-assigned-to-it"></a>
- [What is a Deployment in Kubernetes?](../topics/kubernetes.md#what-is-a-deployment-in-kubernetes) — 2×
  <a id="what-is-a-deployment-in-kubernetes"></a>
- [What is a Pod?](../topics/kubernetes.md#what-is-a-pod) — 2×
  <a id="what-is-a-pod"></a>
- [What is a Service in Kubernetes?](../topics/kubernetes.md#what-is-a-service-in-kubernetes) — 2×
  <a id="what-is-a-service-in-kubernetes"></a>
- [What is Kubernetes, and why is it used?](../topics/kubernetes.md#what-is-kubernetes-and-why-is-it-used) — 2×
  <a id="what-is-kubernetes-and-why-is-it-used"></a>
- [Azure Kubernetes Service (AKS) & Docker](../topics/kubernetes.md#azure-kubernetes-service-aks-docker) — 1×
  <a id="azure-kubernetes-service-aks-docker"></a>

## Intermediate

- [How would you migrate a stateful application to Kubernetes with minimal downtime?](../topics/kubernetes.md#how-would-you-migrate-a-stateful-application-to-kubernetes-with-minimal-downtime) — 5×
  <a id="how-would-you-migrate-a-stateful-application-to-kubernetes-with-minimal-downtime"></a>
- [After deployment, application latency suddenly doubles while CPU and memory remain normal. How would you approach the investigation?](../topics/kubernetes.md#after-deployment-application-latency-suddenly-doubles-while-cpu-and-memory-remai) — 4×
  <a id="after-deployment-application-latency-suddenly-doubles-while-cpu-and-memory-remai"></a>
- [During a node group upgrade, several workloads become unavailable even though replicas exist. What production checks would you perform?](../topics/kubernetes.md#during-a-node-group-upgrade-several-workloads-become-unavailable-even-though-rep) — 4×
  <a id="during-a-node-group-upgrade-several-workloads-become-unavailable-even-though-rep"></a>
- [How would you determine whether production failures originate from Kubernetes, networking, or the application itself?](../topics/kubernetes.md#how-would-you-determine-whether-production-failures-originate-from-kubernetes-ne) — 4×
  <a id="how-would-you-determine-whether-production-failures-originate-from-kubernetes-ne"></a>
- [What indicators tell you that the issue is in the Kubernetes control plane versus the underlying AWS infrastructure?](../topics/kubernetes.md#what-indicators-tell-you-that-the-issue-is-in-the-kubernetes-control-plane-versu) — 4×
  <a id="what-indicators-tell-you-that-the-issue-is-in-the-kubernetes-control-plane-versu"></a>
- [What is Exit Status 2 in Kubernetes?](../topics/kubernetes.md#what-is-exit-status-2-in-kubernetes) — 4×
  <a id="what-is-exit-status-2-in-kubernetes"></a>
- [Your Kubernetes cluster is healthy but requests intermittently return 503. How do you troubleshoot it?](../topics/kubernetes.md#your-kubernetes-cluster-is-healthy-but-requests-intermittently-return-503-how-do) — 4×
  <a id="your-kubernetes-cluster-is-healthy-but-requests-intermittently-return-503-how-do"></a>
- [Difference between Deployment, StatefulSet, DaemonSet, and Job.](../topics/kubernetes.md#difference-between-deployment-statefulset-daemonset-and-job) — 3×
  <a id="difference-between-deployment-statefulset-daemonset-and-job"></a>
- [What is Blue-Green Deployment?](../topics/kubernetes.md#what-is-blue-green-deployment) — 3×
  <a id="what-is-blue-green-deployment"></a>
- [A Kubernetes GPU pod requests 16GB VRAM but only gets 12GB due to fragmentation. How do you detect and fix it in real time?](../topics/kubernetes.md#a-kubernetes-gpu-pod-requests-16gb-vram-but-only-gets-12gb-due-to-fragmentation-) — 2×
  <a id="a-kubernetes-gpu-pod-requests-16gb-vram-but-only-gets-12gb-due-to-fragmentation-"></a>
- [A Kubernetes pod keeps crashing. How do you investigate?](../topics/kubernetes.md#a-kubernetes-pod-keeps-crashing-how-do-you-investigate) — 2×
  <a id="a-kubernetes-pod-keeps-crashing-how-do-you-investigate"></a>
- [A Pod is in CrashLoopBackOff. How would you troubleshoot it?](../topics/kubernetes.md#a-pod-is-in-crashloopbackoff-how-would-you-troubleshoot-it) — 2×
  <a id="a-pod-is-in-crashloopbackoff-how-would-you-troubleshoot-it"></a>
- [A Pod is running but the application is not accessible. What would you check?](../topics/kubernetes.md#a-pod-is-running-but-the-application-is-not-accessible-what-would-you-check) — 2×
  <a id="a-pod-is-running-but-the-application-is-not-accessible-what-would-you-check"></a>
- [An Amazon EKS application starts returning intermittent 502/503 errors immediately after deployment. How would you identify whether the issue is related to Kubernetes, the Load Balancer, or the application?](../topics/kubernetes.md#an-amazon-eks-application-starts-returning-intermittent-502-503-errors-immediate) — 2×
  <a id="an-amazon-eks-application-starts-returning-intermittent-502-503-errors-immediate"></a>
- [Can you automate Kubernetes deployment?](../topics/kubernetes.md#can-you-automate-kubernetes-deployment) — 2×
  <a id="can-you-automate-kubernetes-deployment"></a>
- [Can you explain how Kubernetes scheduling works?](../topics/kubernetes.md#can-you-explain-how-kubernetes-scheduling-works) — 2×
  <a id="can-you-explain-how-kubernetes-scheduling-works"></a>
- [Explain about Kubernetes.](../topics/kubernetes.md#explain-about-kubernetes) — 2×
  <a id="explain-about-kubernetes"></a>
- [Explain ClusterIP and NodePort. What is the difference between them?](../topics/kubernetes.md#explain-clusterip-and-nodeport-what-is-the-difference-between-them) — 2×
  <a id="explain-clusterip-and-nodeport-what-is-the-difference-between-them"></a>
- [Explain Kubernetes RBAC and how it controls access to cluster resources.](../topics/kubernetes.md#explain-kubernetes-rbac-and-how-it-controls-access-to-cluster-resources) — 2×
  <a id="explain-kubernetes-rbac-and-how-it-controls-access-to-cluster-resources"></a>
- [Explain PersistentVolume (PV) and PersistentVolumeClaim (PVC).](../topics/kubernetes.md#explain-persistentvolume-pv-and-persistentvolumeclaim-pvc) — 2×
  <a id="explain-persistentvolume-pv-and-persistentvolumeclaim-pvc"></a>
- [Explain the end-to-end request flow in Kubernetes?](../topics/kubernetes.md#explain-the-end-to-end-request-flow-in-kubernetes) — 2×
  <a id="explain-the-end-to-end-request-flow-in-kubernetes"></a>
- [Explain the Kubernetes scheduling process.](../topics/kubernetes.md#explain-the-kubernetes-scheduling-process) — 2×
  <a id="explain-the-kubernetes-scheduling-process"></a>
- [How do you automate Kubernetes deployment?](../topics/kubernetes.md#how-do-you-automate-kubernetes-deployment) — 2×
  <a id="how-do-you-automate-kubernetes-deployment"></a>
- [How do you configure Kubernetes taints and tolerations for GPU workloads?](../topics/kubernetes.md#how-do-you-configure-kubernetes-taints-and-tolerations-for-gpu-workloads) — 2×
  <a id="how-do-you-configure-kubernetes-taints-and-tolerations-for-gpu-workloads"></a>
- [How do you implement RBAC in Kubernetes?](../topics/kubernetes.md#how-do-you-implement-rbac-in-kubernetes) — 2×
  <a id="how-do-you-implement-rbac-in-kubernetes"></a>
- [How do you troubleshoot deployment failures?](../topics/kubernetes.md#how-do-you-troubleshoot-deployment-failures) — 2×
  <a id="how-do-you-troubleshoot-deployment-failures"></a>
- [How does Kubernetes perform self-healing?](../topics/kubernetes.md#how-does-kubernetes-perform-self-healing) — 2×
  <a id="how-does-kubernetes-perform-self-healing"></a>
- [How to create pod in Kubernetes.](../topics/kubernetes.md#how-to-create-pod-in-kubernetes) — 2×
  <a id="how-to-create-pod-in-kubernetes"></a>
- [How to resolve storage issue in a pod.](../topics/kubernetes.md#how-to-resolve-storage-issue-in-a-pod) — 2×
  <a id="how-to-resolve-storage-issue-in-a-pod"></a>
- [How will you set up the Rest Assured framework when APIs are internal to Kubernetes clusters?](../topics/kubernetes.md#how-will-you-set-up-the-rest-assured-framework-when-apis-are-internal-to-kuberne) — 2×
  <a id="how-will-you-set-up-the-rest-assured-framework-when-apis-are-internal-to-kuberne"></a>
- [What do you mean by RBAC? (IAM/Kubernetes context.)](../topics/kubernetes.md#what-do-you-mean-by-rbac-iam-kubernetes-context) — 2×
  <a id="what-do-you-mean-by-rbac-iam-kubernetes-context"></a>
- [What happens when a Pod crashes?](../topics/kubernetes.md#what-happens-when-a-pod-crashes) — 2×
  <a id="what-happens-when-a-pod-crashes"></a>
- [What is a Pod Disruption Budget (PDB), and why is it important for production workloads?](../topics/kubernetes.md#what-is-a-pod-disruption-budget-pdb-and-why-is-it-important-for-production-workl) — 2×
  <a id="what-is-a-pod-disruption-budget-pdb-and-why-is-it-important-for-production-workl"></a>
- [What is the difference between a pod and a service in Kubernetes?](../topics/kubernetes.md#what-is-the-difference-between-a-pod-and-a-service-in-kubernetes) — 2×
  <a id="what-is-the-difference-between-a-pod-and-a-service-in-kubernetes"></a>
- [What metrics and logs did you monitor after deployment?](../topics/kubernetes.md#what-metrics-and-logs-did-you-monitor-after-deployment) — 2×
  <a id="what-metrics-and-logs-did-you-monitor-after-deployment"></a>
- [Which commands do you use for application deployment in Kubernetes?](../topics/kubernetes.md#which-commands-do-you-use-for-application-deployment-in-kubernetes) — 2×
  <a id="which-commands-do-you-use-for-application-deployment-in-kubernetes"></a>
- [A Kubernetes Pod is in CrashLoopBackOff. Walk me through your troubleshooting approach from start to finish.](../topics/kubernetes.md#a-kubernetes-pod-is-in-crashloopbackoff-walk-me-through-your-troubleshooting-app) — 1×
  <a id="a-kubernetes-pod-is-in-crashloopbackoff-walk-me-through-your-troubleshooting-app"></a>
- [Architecture of kubernetes](../topics/kubernetes.md#architecture-of-kubernetes) — 1×
  <a id="architecture-of-kubernetes"></a>
- [CrashLoopBackOff, ImagePullError—name the Kubernetes errors you’ve fixed and how.](../topics/kubernetes.md#crashloopbackoff-imagepullerror-name-the-kubernetes-errors-youve-fixed-and-how) — 1×
  <a id="crashloopbackoff-imagepullerror-name-the-kubernetes-errors-youve-fixed-and-how"></a>
- [Docker, Kubernetes & Jenkins](../topics/kubernetes.md#docker-kubernetes-jenkins) — 1× · tags: `Docker`, `Jenkins`
  <a id="docker-kubernetes-jenkins"></a>
- [Explain any kubernetes troubleshooting scenarios](../topics/kubernetes.md#explain-any-kubernetes-troubleshooting-scenarios) — 1×
  <a id="explain-any-kubernetes-troubleshooting-scenarios"></a>
- [Explain ConfigMaps and Secrets. How do you manage them across environments?](../topics/kubernetes.md#explain-configmaps-and-secrets-how-do-you-manage-them-across-environments) — 1×
  <a id="explain-configmaps-and-secrets-how-do-you-manage-them-across-environments"></a>
- [Explain Kubernetes Manifest Files and the purpose of different YAML resources.](../topics/kubernetes.md#explain-kubernetes-manifest-files-and-the-purpose-of-different-yaml-resources) — 1×
  <a id="explain-kubernetes-manifest-files-and-the-purpose-of-different-yaml-resources"></a>
- [Explain Kubernetes Manifest Files and the specific purposes of different YAML resources (Pods, Deployments, Services).](../topics/kubernetes.md#explain-kubernetes-manifest-files-and-the-specific-purposes-of-different-yaml-re) — 1×
  <a id="explain-kubernetes-manifest-files-and-the-specific-purposes-of-different-yaml-re"></a>
- [Explain the complete request flow from a browser to a Kubernetes pod.](../topics/kubernetes.md#explain-the-complete-request-flow-from-a-browser-to-a-kubernetes-pod) — 1×
  <a id="explain-the-complete-request-flow-from-a-browser-to-a-kubernetes-pod"></a>
- [How did you design your Kubernetes (EKS) architecture, and what were the key design decisions?](../topics/kubernetes.md#how-did-you-design-your-kubernetes-eks-architecture-and-what-were-the-key-design) — 1×
  <a id="how-did-you-design-your-kubernetes-eks-architecture-and-what-were-the-key-design"></a>
- [How do multiple applications share a single Load Balancer and domain name in Kubernetes?](../topics/kubernetes.md#how-do-multiple-applications-share-a-single-load-balancer-and-domain-name-in-kub) — 1×
  <a id="how-do-multiple-applications-share-a-single-load-balancer-and-domain-name-in-kub"></a>
- [How do you exec into a pod and what’s the right way to define objects?](../topics/kubernetes.md#how-do-you-exec-into-a-pod-and-whats-the-right-way-to-define-objects) — 1×
  <a id="how-do-you-exec-into-a-pod-and-whats-the-right-way-to-define-objects"></a>
- [How do you monitor AWS infrastructure and Kubernetes?](../topics/kubernetes.md#how-do-you-monitor-aws-infrastructure-and-kubernetes) — 1× · tags: `AWS`
  <a id="how-do-you-monitor-aws-infrastructure-and-kubernetes"></a>
- [How do you provide pod access to S3 bucket](../topics/kubernetes.md#how-do-you-provide-pod-access-to-s3-bucket) — 1×
  <a id="how-do-you-provide-pod-access-to-s3-bucket"></a>
- [How do you restrict pod‑to‑pod communication in Kubernetes inside a cluster?](../topics/kubernetes.md#how-do-you-restrict-pod-to-pod-communication-in-kubernetes-inside-a-cluster) — 1×
  <a id="how-do-you-restrict-pod-to-pod-communication-in-kubernetes-inside-a-cluster"></a>
- [How do you securely store and manage secrets in Kubernetes or cloud environments?](../topics/kubernetes.md#how-do-you-securely-store-and-manage-secrets-in-kubernetes-or-cloud-environments) — 1×
  <a id="how-do-you-securely-store-and-manage-secrets-in-kubernetes-or-cloud-environments"></a>
- [How do you spin up Kubernetes clusters with Terraform and what do the master and worker nodes actually do?](../topics/kubernetes.md#how-do-you-spin-up-kubernetes-clusters-with-terraform-and-what-do-the-master-and) — 1× · tags: `Terraform`
  <a id="how-do-you-spin-up-kubernetes-clusters-with-terraform-and-what-do-the-master-and"></a>
- [How do you use hpa in prod env and what kind of metric target in cluster](../topics/kubernetes.md#how-do-you-use-hpa-in-prod-env-and-what-kind-of-metric-target-in-cluster) — 1×
  <a id="how-do-you-use-hpa-in-prod-env-and-what-kind-of-metric-target-in-cluster"></a>
- [How does Kubernetes Service Discovery work?](../topics/kubernetes.md#how-does-kubernetes-service-discovery-work) — 1×
  <a id="how-does-kubernetes-service-discovery-work"></a>
- [How does Kubernetes work?](../topics/kubernetes.md#how-does-kubernetes-work) — 1×
  <a id="how-does-kubernetes-work"></a>
- [How the setup is done for kubernetes cluster?](../topics/kubernetes.md#how-the-setup-is-done-for-kubernetes-cluster) — 1×
  <a id="how-the-setup-is-done-for-kubernetes-cluster"></a>
- [How would you perform a zero-downtime deployment for a microservices application running on Kubernetes?](../topics/kubernetes.md#how-would-you-perform-a-zero-downtime-deployment-for-a-microservices-application) — 1×
  <a id="how-would-you-perform-a-zero-downtime-deployment-for-a-microservices-application"></a>
- [How would you securely manage secrets in a Kubernetes environment without storing them in Git?](../topics/kubernetes.md#how-would-you-securely-manage-secrets-in-a-kubernetes-environment-without-storin) — 1× · tags: `Git`
  <a id="how-would-you-securely-manage-secrets-in-a-kubernetes-environment-without-storin"></a>
- [How would you troubleshoot intermittent 503 errors in Kubernetes?](../topics/kubernetes.md#how-would-you-troubleshoot-intermittent-503-errors-in-kubernetes) — 1×
  <a id="how-would-you-troubleshoot-intermittent-503-errors-in-kubernetes"></a>
- [Kubernetes Migration / Cost Optimization how have you done?](../topics/kubernetes.md#kubernetes-migration-cost-optimization-how-have-you-done) — 1× · tags: `FinOps`
  <a id="kubernetes-migration-cost-optimization-how-have-you-done"></a>
- [Kubernetes pods are Running but users receive 503 errors. What will you check?](../topics/kubernetes.md#kubernetes-pods-are-running-but-users-receive-503-errors-what-will-you-check) — 1×
  <a id="kubernetes-pods-are-running-but-users-receive-503-errors-what-will-you-check"></a>
- [Q: Your Kubernetes deployment is successful, but the application is not accessible. How would you troubleshoot it?](../topics/kubernetes.md#q-your-kubernetes-deployment-is-successful-but-the-application-is-not-accessible) — 1×
  <a id="q-your-kubernetes-deployment-is-successful-but-the-application-is-not-accessible"></a>
- [Readiness Probe vs Liveness Probe.](../topics/kubernetes.md#readiness-probe-vs-liveness-probe) — 1×
  <a id="readiness-probe-vs-liveness-probe"></a>
- [Tell more about headless service](../topics/kubernetes.md#tell-more-about-headless-service) — 1×
  <a id="tell-more-about-headless-service"></a>
- [Types of service and difference between service and ingress](../topics/kubernetes.md#types-of-service-and-difference-between-service-and-ingress) — 1×
  <a id="types-of-service-and-difference-between-service-and-ingress"></a>
- [What are the biggest Kubernetes challenges you've faced in production, and how did you solve them?](../topics/kubernetes.md#what-are-the-biggest-kubernetes-challenges-you-ve-faced-in-production-and-how-di) — 1×
  <a id="what-are-the-biggest-kubernetes-challenges-you-ve-faced-in-production-and-how-di"></a>
- [What is daemonset and replicaset](../topics/kubernetes.md#what-is-daemonset-and-replicaset) — 1×
  <a id="what-is-daemonset-and-replicaset"></a>
- [What is RBAC and its components](../topics/kubernetes.md#what-is-rbac-and-its-components) — 1×
  <a id="what-is-rbac-and-its-components"></a>
- [What steps would you take if a Kubernetes pod is stuck in CrashLoopBackOff?](../topics/kubernetes.md#what-steps-would-you-take-if-a-kubernetes-pod-is-stuck-in-crashloopbackoff) — 1×
  <a id="what-steps-would-you-take-if-a-kubernetes-pod-is-stuck-in-crashloopbackoff"></a>
- [What type of Instances used for worker nodes in kubernetes?](../topics/kubernetes.md#what-type-of-instances-used-for-worker-nodes-in-kubernetes) — 1×
  <a id="what-type-of-instances-used-for-worker-nodes-in-kubernetes"></a>
- [What's the most difficult Kubernetes interview question you've been asked?](../topics/kubernetes.md#what-s-the-most-difficult-kubernetes-interview-question-you-ve-been-asked) — 1×
  <a id="what-s-the-most-difficult-kubernetes-interview-question-you-ve-been-asked"></a>
- [Which Kubernetes topic do you want me to cover next with short answers?](../topics/kubernetes.md#which-kubernetes-topic-do-you-want-me-to-cover-next-with-short-answers) — 1×
  <a id="which-kubernetes-topic-do-you-want-me-to-cover-next-with-short-answers"></a>
- [Why did your team choose Kubernetes instead of another managed service?](../topics/kubernetes.md#why-did-your-team-choose-kubernetes-instead-of-another-managed-service) — 1×
  <a id="why-did-your-team-choose-kubernetes-instead-of-another-managed-service"></a>
- [Why is a pod stuck in CrashLoopBackOff? How would you debug it?](../topics/kubernetes.md#why-is-a-pod-stuck-in-crashloopbackoff-how-would-you-debug-it) — 1×
  <a id="why-is-a-pod-stuck-in-crashloopbackoff-how-would-you-debug-it"></a>
- [Why you have choose M type to R type instance for your kubernetes cluster?](../topics/kubernetes.md#why-you-have-choose-m-type-to-r-type-instance-for-your-kubernetes-cluster) — 1×
  <a id="why-you-have-choose-m-type-to-r-type-instance-for-your-kubernetes-cluster"></a>
- [Will Kubernetes immediately reschedule them to another node?](../topics/kubernetes.md#will-kubernetes-immediately-reschedule-them-to-another-node) — 1×
  <a id="will-kubernetes-immediately-reschedule-them-to-another-node"></a>
- [Write the Kubernetes manifest file to deploy the new replica agent as a DaemonSet in kubernetes cluster](../topics/kubernetes.md#write-the-kubernetes-manifest-file-to-deploy-the-new-replica-agent-as-a-daemonse) — 1×
  <a id="write-the-kubernetes-manifest-file-to-deploy-the-new-replica-agent-as-a-daemonse"></a>
- [Your Pod is stuck in CrashLoopBackOff. Walk me through your investigation.](../topics/kubernetes.md#your-pod-is-stuck-in-crashloopbackoff-walk-me-through-your-investigation) — 1×
  <a id="your-pod-is-stuck-in-crashloopbackoff-walk-me-through-your-investigation"></a>

## Advanced

- [How do you perform a zero-downtime Kubernetes cluster upgrade in production?](../topics/kubernetes.md#how-do-you-perform-a-zero-downtime-kubernetes-cluster-upgrade-in-production) — 5×
  <a id="how-do-you-perform-a-zero-downtime-kubernetes-cluster-upgrade-in-production"></a>
- [Explain the Kubernetes architecture.](../topics/kubernetes.md#explain-the-kubernetes-architecture) — 2× · tags: `System Design`
  <a id="explain-the-kubernetes-architecture"></a>
- [Explain your Kubernetes project end-to-end.](../topics/kubernetes.md#explain-your-kubernetes-project-end-to-end) — 2×
  <a id="explain-your-kubernetes-project-end-to-end"></a>
- [How do you implement continuous integration and delivery in a Kubernetes cluster?](../topics/kubernetes.md#how-do-you-implement-continuous-integration-and-delivery-in-a-kubernetes-cluster) — 2×
  <a id="how-do-you-implement-continuous-integration-and-delivery-in-a-kubernetes-cluster"></a>
- [How do you integrate GitHub or Bitbucket with Kubernetes? Explain the steps.](../topics/kubernetes.md#how-do-you-integrate-github-or-bitbucket-with-kubernetes-explain-the-steps) — 2×
  <a id="how-do-you-integrate-github-or-bitbucket-with-kubernetes-explain-the-steps"></a>
- [How would you handle CUDA driver upgrades in Kubernetes without disrupting thousands of running AI pods?](../topics/kubernetes.md#how-would-you-handle-cuda-driver-upgrades-in-kubernetes-without-disrupting-thous) — 2×
  <a id="how-would-you-handle-cuda-driver-upgrades-in-kubernetes-without-disrupting-thous"></a>
- [Design an end-to-end automated deployment solution for multiple environments.](../topics/kubernetes.md#design-an-end-to-end-automated-deployment-solution-for-multiple-environments) — 1×
  <a id="design-an-end-to-end-automated-deployment-solution-for-multiple-environments"></a>
- [How does Prometheus work for monitoring in a Kubernetes cluster?](../topics/kubernetes.md#how-does-prometheus-work-for-monitoring-in-a-kubernetes-cluster) — 1×
  <a id="how-does-prometheus-work-for-monitoring-in-a-kubernetes-cluster"></a>
- [Production error crashloopback of how do you troubleshoot.](../topics/kubernetes.md#production-error-crashloopback-of-how-do-you-troubleshoot) — 1×
  <a id="production-error-crashloopback-of-how-do-you-troubleshoot"></a>
- [What are all your followed deployment strategy and when to use those and how to switch traffic and how do you decide traffic percentage](../topics/kubernetes.md#what-are-all-your-followed-deployment-strategy-and-when-to-use-those-and-how-to-) — 1×
  <a id="what-are-all-your-followed-deployment-strategy-and-when-to-use-those-and-how-to-"></a>
- [What is Kubernetes and how do you use it in your projects?](../topics/kubernetes.md#what-is-kubernetes-and-how-do-you-use-it-in-your-projects) — 1×
  <a id="what-is-kubernetes-and-how-do-you-use-it-in-your-projects"></a>
- [What's the most challenging Kubernetes production issue you've faced? Share it in the comments your experience might help someone else.](../topics/kubernetes.md#what-s-the-most-challenging-kubernetes-production-issue-you-ve-faced-share-it-in) — 1×
  <a id="what-s-the-most-challenging-kubernetes-production-issue-you-ve-faced-share-it-in"></a>

## By interview round

### Final

- [How do you troubleshoot deployment failures?](../topics/kubernetes.md#how-do-you-troubleshoot-deployment-failures)

### Managerial

- [How will you set up the Rest Assured framework when APIs are internal to Kubernetes clusters?](../topics/kubernetes.md#how-will-you-set-up-the-rest-assured-framework-when-apis-are-internal-to-kuberne)

### Other

- [Can you automate Kubernetes deployment?](../topics/kubernetes.md#can-you-automate-kubernetes-deployment)
- [How do you automate Kubernetes deployment?](../topics/kubernetes.md#how-do-you-automate-kubernetes-deployment)
- [What do you mean by RBAC? (IAM/Kubernetes context.)](../topics/kubernetes.md#what-do-you-mean-by-rbac-iam-kubernetes-context)

### Technical

- [After deployment, application latency suddenly doubles while CPU and memory remain normal. How would you approach the investigation?](../topics/kubernetes.md#after-deployment-application-latency-suddenly-doubles-while-cpu-and-memory-remai)
- [During a node group upgrade, several workloads become unavailable even though replicas exist. What production checks would you perform?](../topics/kubernetes.md#during-a-node-group-upgrade-several-workloads-become-unavailable-even-though-rep)
- [Explain Kubernetes Manifest Files and the purpose of different YAML resources.](../topics/kubernetes.md#explain-kubernetes-manifest-files-and-the-purpose-of-different-yaml-resources)
- [How would you determine whether production failures originate from Kubernetes, networking, or the application itself?](../topics/kubernetes.md#how-would-you-determine-whether-production-failures-originate-from-kubernetes-ne)
- [What indicators tell you that the issue is in the Kubernetes control plane versus the underlying AWS infrastructure?](../topics/kubernetes.md#what-indicators-tell-you-that-the-issue-is-in-the-kubernetes-control-plane-versu)

### Technical Round 1

- [Design an end-to-end automated deployment solution for multiple environments.](../topics/kubernetes.md#design-an-end-to-end-automated-deployment-solution-for-multiple-environments)

### Unspecified

- [A Kubernetes GPU pod requests 16GB VRAM but only gets 12GB due to fragmentation. How do you detect and fix it in real time?](../topics/kubernetes.md#a-kubernetes-gpu-pod-requests-16gb-vram-but-only-gets-12gb-due-to-fragmentation-)
- [A Kubernetes Pod is in CrashLoopBackOff. Walk me through your troubleshooting approach from start to finish.](../topics/kubernetes.md#a-kubernetes-pod-is-in-crashloopbackoff-walk-me-through-your-troubleshooting-app)
- [A Kubernetes pod keeps crashing. How do you investigate?](../topics/kubernetes.md#a-kubernetes-pod-keeps-crashing-how-do-you-investigate)
- [A Pod is in CrashLoopBackOff. How would you troubleshoot it?](../topics/kubernetes.md#a-pod-is-in-crashloopbackoff-how-would-you-troubleshoot-it)
- [A Pod is running but the application is not accessible. What would you check?](../topics/kubernetes.md#a-pod-is-running-but-the-application-is-not-accessible-what-would-you-check)
- [An Amazon EKS application starts returning intermittent 502/503 errors immediately after deployment. How would you identify whether the issue is related to Kubernetes, the Load Balancer, or the application?](../topics/kubernetes.md#an-amazon-eks-application-starts-returning-intermittent-502-503-errors-immediate)
- [Architecture of kubernetes](../topics/kubernetes.md#architecture-of-kubernetes)
- [Azure Kubernetes Service (AKS) & Docker](../topics/kubernetes.md#azure-kubernetes-service-aks-docker)
- [Can you explain how Kubernetes scheduling works?](../topics/kubernetes.md#can-you-explain-how-kubernetes-scheduling-works)
- [CrashLoopBackOff, ImagePullError—name the Kubernetes errors you’ve fixed and how.](../topics/kubernetes.md#crashloopbackoff-imagepullerror-name-the-kubernetes-errors-youve-fixed-and-how)
- [Difference between Deployment, StatefulSet, DaemonSet, and Job.](../topics/kubernetes.md#difference-between-deployment-statefulset-daemonset-and-job)
- [Difference between Pod and Container?](../topics/kubernetes.md#difference-between-pod-and-container) — tags: `Docker`
- [Docker, Kubernetes & Jenkins](../topics/kubernetes.md#docker-kubernetes-jenkins) — tags: `Docker`, `Jenkins`
- [Explain about Kubernetes.](../topics/kubernetes.md#explain-about-kubernetes)
- [Explain any kubernetes troubleshooting scenarios](../topics/kubernetes.md#explain-any-kubernetes-troubleshooting-scenarios)
- [Explain ClusterIP and NodePort. What is the difference between them?](../topics/kubernetes.md#explain-clusterip-and-nodeport-what-is-the-difference-between-them)
- [Explain ConfigMaps and Secrets. How do you manage them across environments?](../topics/kubernetes.md#explain-configmaps-and-secrets-how-do-you-manage-them-across-environments)
- [Explain Kubernetes Manifest Files and the specific purposes of different YAML resources (Pods, Deployments, Services).](../topics/kubernetes.md#explain-kubernetes-manifest-files-and-the-specific-purposes-of-different-yaml-re)
- [Explain Kubernetes RBAC and how it controls access to cluster resources.](../topics/kubernetes.md#explain-kubernetes-rbac-and-how-it-controls-access-to-cluster-resources)
- [Explain PersistentVolume (PV) and PersistentVolumeClaim (PVC).](../topics/kubernetes.md#explain-persistentvolume-pv-and-persistentvolumeclaim-pvc)
- [Explain the complete request flow from a browser to a Kubernetes pod.](../topics/kubernetes.md#explain-the-complete-request-flow-from-a-browser-to-a-kubernetes-pod)
- [Explain the end-to-end request flow in Kubernetes?](../topics/kubernetes.md#explain-the-end-to-end-request-flow-in-kubernetes)
- [Explain the Kubernetes architecture.](../topics/kubernetes.md#explain-the-kubernetes-architecture) — tags: `System Design`
- [Explain the Kubernetes scheduling process.](../topics/kubernetes.md#explain-the-kubernetes-scheduling-process)
- [Explain your Kubernetes project end-to-end.](../topics/kubernetes.md#explain-your-kubernetes-project-end-to-end)
- [How did you design your Kubernetes (EKS) architecture, and what were the key design decisions?](../topics/kubernetes.md#how-did-you-design-your-kubernetes-eks-architecture-and-what-were-the-key-design)
- [How do multiple applications share a single Load Balancer and domain name in Kubernetes?](../topics/kubernetes.md#how-do-multiple-applications-share-a-single-load-balancer-and-domain-name-in-kub)
- [How do you configure Kubernetes taints and tolerations for GPU workloads?](../topics/kubernetes.md#how-do-you-configure-kubernetes-taints-and-tolerations-for-gpu-workloads)
- [How do you exec into a pod and what’s the right way to define objects?](../topics/kubernetes.md#how-do-you-exec-into-a-pod-and-whats-the-right-way-to-define-objects)
- [How do you implement continuous integration and delivery in a Kubernetes cluster?](../topics/kubernetes.md#how-do-you-implement-continuous-integration-and-delivery-in-a-kubernetes-cluster)
- [How do you implement RBAC in Kubernetes?](../topics/kubernetes.md#how-do-you-implement-rbac-in-kubernetes)
- [How do you integrate GitHub or Bitbucket with Kubernetes? Explain the steps.](../topics/kubernetes.md#how-do-you-integrate-github-or-bitbucket-with-kubernetes-explain-the-steps)
- [How do you monitor AWS infrastructure and Kubernetes?](../topics/kubernetes.md#how-do-you-monitor-aws-infrastructure-and-kubernetes) — tags: `AWS`
- [How do you perform a zero-downtime Kubernetes cluster upgrade in production?](../topics/kubernetes.md#how-do-you-perform-a-zero-downtime-kubernetes-cluster-upgrade-in-production)
- [How do you provide pod access to S3 bucket](../topics/kubernetes.md#how-do-you-provide-pod-access-to-s3-bucket)
- [How do you restrict pod‑to‑pod communication in Kubernetes inside a cluster?](../topics/kubernetes.md#how-do-you-restrict-pod-to-pod-communication-in-kubernetes-inside-a-cluster)
- [How do you securely store and manage secrets in Kubernetes or cloud environments?](../topics/kubernetes.md#how-do-you-securely-store-and-manage-secrets-in-kubernetes-or-cloud-environments)
- [How do you spin up Kubernetes clusters with Terraform and what do the master and worker nodes actually do?](../topics/kubernetes.md#how-do-you-spin-up-kubernetes-clusters-with-terraform-and-what-do-the-master-and) — tags: `Terraform`
- [How do you use hpa in prod env and what kind of metric target in cluster](../topics/kubernetes.md#how-do-you-use-hpa-in-prod-env-and-what-kind-of-metric-target-in-cluster)
- [How does Kubernetes perform self-healing?](../topics/kubernetes.md#how-does-kubernetes-perform-self-healing)
- [How does Kubernetes Service Discovery work?](../topics/kubernetes.md#how-does-kubernetes-service-discovery-work)
- [How does Kubernetes work?](../topics/kubernetes.md#how-does-kubernetes-work)
- [How does Prometheus work for monitoring in a Kubernetes cluster?](../topics/kubernetes.md#how-does-prometheus-work-for-monitoring-in-a-kubernetes-cluster)
- [How the setup is done for kubernetes cluster?](../topics/kubernetes.md#how-the-setup-is-done-for-kubernetes-cluster)
- [How to create pod in Kubernetes.](../topics/kubernetes.md#how-to-create-pod-in-kubernetes)
- [How to resolve storage issue in a pod.](../topics/kubernetes.md#how-to-resolve-storage-issue-in-a-pod)
- [How would you check if a GPU pod in Kubernetes is using the GPU assigned to it?](../topics/kubernetes.md#how-would-you-check-if-a-gpu-pod-in-kubernetes-is-using-the-gpu-assigned-to-it)
- [How would you handle CUDA driver upgrades in Kubernetes without disrupting thousands of running AI pods?](../topics/kubernetes.md#how-would-you-handle-cuda-driver-upgrades-in-kubernetes-without-disrupting-thous)
- [How would you migrate a stateful application to Kubernetes with minimal downtime?](../topics/kubernetes.md#how-would-you-migrate-a-stateful-application-to-kubernetes-with-minimal-downtime)
- [How would you perform a zero-downtime deployment for a microservices application running on Kubernetes?](../topics/kubernetes.md#how-would-you-perform-a-zero-downtime-deployment-for-a-microservices-application)
- [How would you securely manage secrets in a Kubernetes environment without storing them in Git?](../topics/kubernetes.md#how-would-you-securely-manage-secrets-in-a-kubernetes-environment-without-storin) — tags: `Git`
- [How would you troubleshoot intermittent 503 errors in Kubernetes?](../topics/kubernetes.md#how-would-you-troubleshoot-intermittent-503-errors-in-kubernetes)
- [Kubernetes Migration / Cost Optimization how have you done?](../topics/kubernetes.md#kubernetes-migration-cost-optimization-how-have-you-done) — tags: `FinOps`
- [Kubernetes pods are Running but users receive 503 errors. What will you check?](../topics/kubernetes.md#kubernetes-pods-are-running-but-users-receive-503-errors-what-will-you-check)
- [Production error crashloopback of how do you troubleshoot.](../topics/kubernetes.md#production-error-crashloopback-of-how-do-you-troubleshoot)
- [Q: Your Kubernetes deployment is successful, but the application is not accessible. How would you troubleshoot it?](../topics/kubernetes.md#q-your-kubernetes-deployment-is-successful-but-the-application-is-not-accessible)
- [Readiness Probe vs Liveness Probe.](../topics/kubernetes.md#readiness-probe-vs-liveness-probe)
- [Tell more about headless service](../topics/kubernetes.md#tell-more-about-headless-service)
- [Types of service and difference between service and ingress](../topics/kubernetes.md#types-of-service-and-difference-between-service-and-ingress)
- [What are all your followed deployment strategy and when to use those and how to switch traffic and how do you decide traffic percentage](../topics/kubernetes.md#what-are-all-your-followed-deployment-strategy-and-when-to-use-those-and-how-to-)
- [What are the biggest Kubernetes challenges you've faced in production, and how did you solve them?](../topics/kubernetes.md#what-are-the-biggest-kubernetes-challenges-you-ve-faced-in-production-and-how-di)
- [What happens when a Pod crashes?](../topics/kubernetes.md#what-happens-when-a-pod-crashes)
- [What is a Deployment in Kubernetes?](../topics/kubernetes.md#what-is-a-deployment-in-kubernetes)
- [What is a Pod Disruption Budget (PDB), and why is it important for production workloads?](../topics/kubernetes.md#what-is-a-pod-disruption-budget-pdb-and-why-is-it-important-for-production-workl)
- [What is a Pod?](../topics/kubernetes.md#what-is-a-pod)
- [What is a Service in Kubernetes?](../topics/kubernetes.md#what-is-a-service-in-kubernetes)
- [What is Blue-Green Deployment?](../topics/kubernetes.md#what-is-blue-green-deployment)
- [What is daemonset and replicaset](../topics/kubernetes.md#what-is-daemonset-and-replicaset)
- [What is Exit Status 2 in Kubernetes?](../topics/kubernetes.md#what-is-exit-status-2-in-kubernetes)
- [What is Kubernetes and how do you use it in your projects?](../topics/kubernetes.md#what-is-kubernetes-and-how-do-you-use-it-in-your-projects)
- [What is Kubernetes, and why is it used?](../topics/kubernetes.md#what-is-kubernetes-and-why-is-it-used)
- [What is RBAC and its components](../topics/kubernetes.md#what-is-rbac-and-its-components)
- [What is the difference between a pod and a service in Kubernetes?](../topics/kubernetes.md#what-is-the-difference-between-a-pod-and-a-service-in-kubernetes)
- [What metrics and logs did you monitor after deployment?](../topics/kubernetes.md#what-metrics-and-logs-did-you-monitor-after-deployment)
- [What steps would you take if a Kubernetes pod is stuck in CrashLoopBackOff?](../topics/kubernetes.md#what-steps-would-you-take-if-a-kubernetes-pod-is-stuck-in-crashloopbackoff)
- [What type of Instances used for worker nodes in kubernetes?](../topics/kubernetes.md#what-type-of-instances-used-for-worker-nodes-in-kubernetes)
- [What's the most challenging Kubernetes production issue you've faced? Share it in the comments your experience might help someone else.](../topics/kubernetes.md#what-s-the-most-challenging-kubernetes-production-issue-you-ve-faced-share-it-in)
- [What's the most difficult Kubernetes interview question you've been asked?](../topics/kubernetes.md#what-s-the-most-difficult-kubernetes-interview-question-you-ve-been-asked)
- [Which commands do you use for application deployment in Kubernetes?](../topics/kubernetes.md#which-commands-do-you-use-for-application-deployment-in-kubernetes)
- [Which Kubernetes topic do you want me to cover next with short answers?](../topics/kubernetes.md#which-kubernetes-topic-do-you-want-me-to-cover-next-with-short-answers)
- [Why did your team choose Kubernetes instead of another managed service?](../topics/kubernetes.md#why-did-your-team-choose-kubernetes-instead-of-another-managed-service)
- [Why is a pod stuck in CrashLoopBackOff? How would you debug it?](../topics/kubernetes.md#why-is-a-pod-stuck-in-crashloopbackoff-how-would-you-debug-it)
- [Why you have choose M type to R type instance for your kubernetes cluster?](../topics/kubernetes.md#why-you-have-choose-m-type-to-r-type-instance-for-your-kubernetes-cluster)
- [Will Kubernetes immediately reschedule them to another node?](../topics/kubernetes.md#will-kubernetes-immediately-reschedule-them-to-another-node)
- [Write the Kubernetes manifest file to deploy the new replica agent as a DaemonSet in kubernetes cluster](../topics/kubernetes.md#write-the-kubernetes-manifest-file-to-deploy-the-new-replica-agent-as-a-daemonse)
- [Your Kubernetes cluster is healthy but requests intermittently return 503. How do you troubleshoot it?](../topics/kubernetes.md#your-kubernetes-cluster-is-healthy-but-requests-intermittently-return-503-how-do)
- [Your Pod is stuck in CrashLoopBackOff. Walk me through your investigation.](../topics/kubernetes.md#your-pod-is-stuck-in-crashloopbackoff-walk-me-through-your-investigation)

## Companies asking

- [Argyll Infotech](../companies/argyll-infotech.md)
- [Deloitte](../companies/deloitte.md)
- [Fineshift Software Pvt. Ltd.](../companies/fineshift-software-pvt-ltd.md)
- [Global Payments](../companies/global-payments.md)
- [Infosys](../companies/infosys.md)
- [Mirafra](../companies/mirafra.md)
- [NVIDIA](../companies/nvidia.md)
- [PwC](../companies/pwc.md)
- [TCS](../companies/tcs.md)
- [zemoso technologies](../companies/zemoso-technologies.md)

## Recently added

- [How do you monitor AWS infrastructure and Kubernetes?](../topics/kubernetes.md#how-do-you-monitor-aws-infrastructure-and-kubernetes) — 2026-07-17 · tags: `AWS`
- [How would you migrate a stateful application to Kubernetes with minimal downtime?](../topics/kubernetes.md#how-would-you-migrate-a-stateful-application-to-kubernetes-with-minimal-downtime) — 2026-07-17
- [How do you perform a zero-downtime Kubernetes cluster upgrade in production?](../topics/kubernetes.md#how-do-you-perform-a-zero-downtime-kubernetes-cluster-upgrade-in-production) — 2026-07-17
- [How would you troubleshoot intermittent 503 errors in Kubernetes?](../topics/kubernetes.md#how-would-you-troubleshoot-intermittent-503-errors-in-kubernetes) — 2026-07-17
- [How would you securely manage secrets in a Kubernetes environment without storing them in Git?](../topics/kubernetes.md#how-would-you-securely-manage-secrets-in-a-kubernetes-environment-without-storin) — 2026-07-17 · tags: `Git`
- [How would you perform a zero-downtime deployment for a microservices application running on Kubernetes?](../topics/kubernetes.md#how-would-you-perform-a-zero-downtime-deployment-for-a-microservices-application) — 2026-07-17
- [A Kubernetes Pod is in CrashLoopBackOff. Walk me through your troubleshooting approach from start to finish.](../topics/kubernetes.md#a-kubernetes-pod-is-in-crashloopbackoff-walk-me-through-your-troubleshooting-app) — 2026-07-17
- [How do you exec into a pod and what’s the right way to define objects?](../topics/kubernetes.md#how-do-you-exec-into-a-pod-and-whats-the-right-way-to-define-objects) — 2026-07-17
- [CrashLoopBackOff, ImagePullError—name the Kubernetes errors you’ve fixed and how.](../topics/kubernetes.md#crashloopbackoff-imagepullerror-name-the-kubernetes-errors-youve-fixed-and-how) — 2026-07-17
- [How do you spin up Kubernetes clusters with Terraform and what do the master and worker nodes actually do?](../topics/kubernetes.md#how-do-you-spin-up-kubernetes-clusters-with-terraform-and-what-do-the-master-and) — 2026-07-17 · tags: `Terraform`
- [Q: Your Kubernetes deployment is successful, but the application is not accessible. How would you troubleshoot it?](../topics/kubernetes.md#q-your-kubernetes-deployment-is-successful-but-the-application-is-not-accessible) — 2026-07-17
- [Why did your team choose Kubernetes instead of another managed service?](../topics/kubernetes.md#why-did-your-team-choose-kubernetes-instead-of-another-managed-service) — 2026-07-17
- [How does Kubernetes work?](../topics/kubernetes.md#how-does-kubernetes-work) — 2026-07-17
- [Explain any kubernetes troubleshooting scenarios](../topics/kubernetes.md#explain-any-kubernetes-troubleshooting-scenarios) — 2026-07-17
- [Why you have choose M type to R type instance for your kubernetes cluster?](../topics/kubernetes.md#why-you-have-choose-m-type-to-r-type-instance-for-your-kubernetes-cluster) — 2026-07-17

## Related topics

- [Docker](./docker.md)
- [EKS](./eks.md)
- [Helm](./helm.md)
- [ArgoCD](./argocd.md)

## All questions

| Question | Diff | Asked |
| --- | --- | ---: |
| [A Kubernetes GPU pod requests 16GB VRAM but only gets 12GB due to fragmentation. How do you detect and fix it in real time?](../topics/kubernetes.md#a-kubernetes-gpu-pod-requests-16gb-vram-but-only-gets-12gb-due-to-fragmentation-) | Medium | 2 |
| [A Kubernetes Pod is in CrashLoopBackOff. Walk me through your troubleshooting approach from start to finish.](../topics/kubernetes.md#a-kubernetes-pod-is-in-crashloopbackoff-walk-me-through-your-troubleshooting-app) | Medium | 1 |
| [A Kubernetes pod keeps crashing. How do you investigate?](../topics/kubernetes.md#a-kubernetes-pod-keeps-crashing-how-do-you-investigate) | Medium | 2 |
| [A Pod is in CrashLoopBackOff. How would you troubleshoot it?](../topics/kubernetes.md#a-pod-is-in-crashloopbackoff-how-would-you-troubleshoot-it) | Medium | 2 |
| [A Pod is running but the application is not accessible. What would you check?](../topics/kubernetes.md#a-pod-is-running-but-the-application-is-not-accessible-what-would-you-check) | Medium | 2 |
| [After deployment, application latency suddenly doubles while CPU and memory remain normal. How would you approach the investigation?](../topics/kubernetes.md#after-deployment-application-latency-suddenly-doubles-while-cpu-and-memory-remai) | Medium | 4 |
| [An Amazon EKS application starts returning intermittent 502/503 errors immediately after deployment. How would you identify whether the issue is related to Kubernetes, the Load Balancer, or the application?](../topics/kubernetes.md#an-amazon-eks-application-starts-returning-intermittent-502-503-errors-immediate) | Medium | 2 |
| [Architecture of kubernetes](../topics/kubernetes.md#architecture-of-kubernetes) | Medium | 1 |
| [Azure Kubernetes Service (AKS) & Docker](../topics/kubernetes.md#azure-kubernetes-service-aks-docker) | Easy | 1 |
| [Can you automate Kubernetes deployment?](../topics/kubernetes.md#can-you-automate-kubernetes-deployment) | Medium | 2 |
| [Can you explain how Kubernetes scheduling works?](../topics/kubernetes.md#can-you-explain-how-kubernetes-scheduling-works) | Medium | 2 |
| [CrashLoopBackOff, ImagePullError—name the Kubernetes errors you’ve fixed and how.](../topics/kubernetes.md#crashloopbackoff-imagepullerror-name-the-kubernetes-errors-youve-fixed-and-how) | Medium | 1 |
| [Design an end-to-end automated deployment solution for multiple environments.](../topics/kubernetes.md#design-an-end-to-end-automated-deployment-solution-for-multiple-environments) | Hard | 1 |
| [Difference between Deployment, StatefulSet, DaemonSet, and Job.](../topics/kubernetes.md#difference-between-deployment-statefulset-daemonset-and-job) | Medium | 3 |
| [Difference between Pod and Container?](../topics/kubernetes.md#difference-between-pod-and-container) | Easy | 2 |
| [Docker, Kubernetes & Jenkins](../topics/kubernetes.md#docker-kubernetes-jenkins) | Medium | 1 |
| [During a node group upgrade, several workloads become unavailable even though replicas exist. What production checks would you perform?](../topics/kubernetes.md#during-a-node-group-upgrade-several-workloads-become-unavailable-even-though-rep) | Medium | 4 |
| [Explain about Kubernetes.](../topics/kubernetes.md#explain-about-kubernetes) | Medium | 2 |
| [Explain any kubernetes troubleshooting scenarios](../topics/kubernetes.md#explain-any-kubernetes-troubleshooting-scenarios) | Medium | 1 |
| [Explain ClusterIP and NodePort. What is the difference between them?](../topics/kubernetes.md#explain-clusterip-and-nodeport-what-is-the-difference-between-them) | Medium | 2 |
| [Explain ConfigMaps and Secrets. How do you manage them across environments?](../topics/kubernetes.md#explain-configmaps-and-secrets-how-do-you-manage-them-across-environments) | Medium | 1 |
| [Explain Kubernetes Manifest Files and the purpose of different YAML resources.](../topics/kubernetes.md#explain-kubernetes-manifest-files-and-the-purpose-of-different-yaml-resources) | Medium | 1 |
| [Explain Kubernetes Manifest Files and the specific purposes of different YAML resources (Pods, Deployments, Services).](../topics/kubernetes.md#explain-kubernetes-manifest-files-and-the-specific-purposes-of-different-yaml-re) | Medium | 1 |
| [Explain Kubernetes RBAC and how it controls access to cluster resources.](../topics/kubernetes.md#explain-kubernetes-rbac-and-how-it-controls-access-to-cluster-resources) | Medium | 2 |
| [Explain PersistentVolume (PV) and PersistentVolumeClaim (PVC).](../topics/kubernetes.md#explain-persistentvolume-pv-and-persistentvolumeclaim-pvc) | Medium | 2 |
| [Explain the complete request flow from a browser to a Kubernetes pod.](../topics/kubernetes.md#explain-the-complete-request-flow-from-a-browser-to-a-kubernetes-pod) | Medium | 1 |
| [Explain the end-to-end request flow in Kubernetes?](../topics/kubernetes.md#explain-the-end-to-end-request-flow-in-kubernetes) | Medium | 2 |
| [Explain the Kubernetes architecture.](../topics/kubernetes.md#explain-the-kubernetes-architecture) | Hard | 2 |
| [Explain the Kubernetes scheduling process.](../topics/kubernetes.md#explain-the-kubernetes-scheduling-process) | Medium | 2 |
| [Explain your Kubernetes project end-to-end.](../topics/kubernetes.md#explain-your-kubernetes-project-end-to-end) | Hard | 2 |
| [How did you design your Kubernetes (EKS) architecture, and what were the key design decisions?](../topics/kubernetes.md#how-did-you-design-your-kubernetes-eks-architecture-and-what-were-the-key-design) | Medium | 1 |
| [How do multiple applications share a single Load Balancer and domain name in Kubernetes?](../topics/kubernetes.md#how-do-multiple-applications-share-a-single-load-balancer-and-domain-name-in-kub) | Medium | 1 |
| [How do you automate Kubernetes deployment?](../topics/kubernetes.md#how-do-you-automate-kubernetes-deployment) | Medium | 2 |
| [How do you configure Kubernetes taints and tolerations for GPU workloads?](../topics/kubernetes.md#how-do-you-configure-kubernetes-taints-and-tolerations-for-gpu-workloads) | Medium | 2 |
| [How do you exec into a pod and what’s the right way to define objects?](../topics/kubernetes.md#how-do-you-exec-into-a-pod-and-whats-the-right-way-to-define-objects) | Medium | 1 |
| [How do you implement continuous integration and delivery in a Kubernetes cluster?](../topics/kubernetes.md#how-do-you-implement-continuous-integration-and-delivery-in-a-kubernetes-cluster) | Hard | 2 |
| [How do you implement RBAC in Kubernetes?](../topics/kubernetes.md#how-do-you-implement-rbac-in-kubernetes) | Medium | 2 |
| [How do you integrate GitHub or Bitbucket with Kubernetes? Explain the steps.](../topics/kubernetes.md#how-do-you-integrate-github-or-bitbucket-with-kubernetes-explain-the-steps) | Hard | 2 |
| [How do you monitor AWS infrastructure and Kubernetes?](../topics/kubernetes.md#how-do-you-monitor-aws-infrastructure-and-kubernetes) | Medium | 1 |
| [How do you perform a zero-downtime Kubernetes cluster upgrade in production?](../topics/kubernetes.md#how-do-you-perform-a-zero-downtime-kubernetes-cluster-upgrade-in-production) | Hard | 5 |
| [How do you provide pod access to S3 bucket](../topics/kubernetes.md#how-do-you-provide-pod-access-to-s3-bucket) | Medium | 1 |
| [How do you restrict pod‑to‑pod communication in Kubernetes inside a cluster?](../topics/kubernetes.md#how-do-you-restrict-pod-to-pod-communication-in-kubernetes-inside-a-cluster) | Medium | 1 |
| [How do you securely store and manage secrets in Kubernetes or cloud environments?](../topics/kubernetes.md#how-do-you-securely-store-and-manage-secrets-in-kubernetes-or-cloud-environments) | Medium | 1 |
| [How do you spin up Kubernetes clusters with Terraform and what do the master and worker nodes actually do?](../topics/kubernetes.md#how-do-you-spin-up-kubernetes-clusters-with-terraform-and-what-do-the-master-and) | Medium | 1 |
| [How do you troubleshoot deployment failures?](../topics/kubernetes.md#how-do-you-troubleshoot-deployment-failures) | Medium | 2 |
| [How do you use hpa in prod env and what kind of metric target in cluster](../topics/kubernetes.md#how-do-you-use-hpa-in-prod-env-and-what-kind-of-metric-target-in-cluster) | Medium | 1 |
| [How does Kubernetes perform self-healing?](../topics/kubernetes.md#how-does-kubernetes-perform-self-healing) | Medium | 2 |
| [How does Kubernetes Service Discovery work?](../topics/kubernetes.md#how-does-kubernetes-service-discovery-work) | Medium | 1 |
| [How does Kubernetes work?](../topics/kubernetes.md#how-does-kubernetes-work) | Medium | 1 |
| [How does Prometheus work for monitoring in a Kubernetes cluster?](../topics/kubernetes.md#how-does-prometheus-work-for-monitoring-in-a-kubernetes-cluster) | Hard | 1 |
| [How the setup is done for kubernetes cluster?](../topics/kubernetes.md#how-the-setup-is-done-for-kubernetes-cluster) | Medium | 1 |
| [How to create pod in Kubernetes.](../topics/kubernetes.md#how-to-create-pod-in-kubernetes) | Medium | 2 |
| [How to resolve storage issue in a pod.](../topics/kubernetes.md#how-to-resolve-storage-issue-in-a-pod) | Medium | 2 |
| [How will you set up the Rest Assured framework when APIs are internal to Kubernetes clusters?](../topics/kubernetes.md#how-will-you-set-up-the-rest-assured-framework-when-apis-are-internal-to-kuberne) | Medium | 2 |
| [How would you check if a GPU pod in Kubernetes is using the GPU assigned to it?](../topics/kubernetes.md#how-would-you-check-if-a-gpu-pod-in-kubernetes-is-using-the-gpu-assigned-to-it) | Easy | 2 |
| [How would you determine whether production failures originate from Kubernetes, networking, or the application itself?](../topics/kubernetes.md#how-would-you-determine-whether-production-failures-originate-from-kubernetes-ne) | Medium | 4 |
| [How would you handle CUDA driver upgrades in Kubernetes without disrupting thousands of running AI pods?](../topics/kubernetes.md#how-would-you-handle-cuda-driver-upgrades-in-kubernetes-without-disrupting-thous) | Hard | 2 |
| [How would you migrate a stateful application to Kubernetes with minimal downtime?](../topics/kubernetes.md#how-would-you-migrate-a-stateful-application-to-kubernetes-with-minimal-downtime) | Medium | 5 |
| [How would you perform a zero-downtime deployment for a microservices application running on Kubernetes?](../topics/kubernetes.md#how-would-you-perform-a-zero-downtime-deployment-for-a-microservices-application) | Medium | 1 |
| [How would you securely manage secrets in a Kubernetes environment without storing them in Git?](../topics/kubernetes.md#how-would-you-securely-manage-secrets-in-a-kubernetes-environment-without-storin) | Medium | 1 |
| [How would you troubleshoot intermittent 503 errors in Kubernetes?](../topics/kubernetes.md#how-would-you-troubleshoot-intermittent-503-errors-in-kubernetes) | Medium | 1 |
| [Kubernetes Migration / Cost Optimization how have you done?](../topics/kubernetes.md#kubernetes-migration-cost-optimization-how-have-you-done) | Medium | 1 |
| [Kubernetes pods are Running but users receive 503 errors. What will you check?](../topics/kubernetes.md#kubernetes-pods-are-running-but-users-receive-503-errors-what-will-you-check) | Medium | 1 |
| [Production error crashloopback of how do you troubleshoot.](../topics/kubernetes.md#production-error-crashloopback-of-how-do-you-troubleshoot) | Hard | 1 |
| [Q: Your Kubernetes deployment is successful, but the application is not accessible. How would you troubleshoot it?](../topics/kubernetes.md#q-your-kubernetes-deployment-is-successful-but-the-application-is-not-accessible) | Medium | 1 |
| [Readiness Probe vs Liveness Probe.](../topics/kubernetes.md#readiness-probe-vs-liveness-probe) | Medium | 1 |
| [Tell more about headless service](../topics/kubernetes.md#tell-more-about-headless-service) | Medium | 1 |
| [Types of service and difference between service and ingress](../topics/kubernetes.md#types-of-service-and-difference-between-service-and-ingress) | Medium | 1 |
| [What are all your followed deployment strategy and when to use those and how to switch traffic and how do you decide traffic percentage](../topics/kubernetes.md#what-are-all-your-followed-deployment-strategy-and-when-to-use-those-and-how-to-) | Hard | 1 |
| [What are the biggest Kubernetes challenges you've faced in production, and how did you solve them?](../topics/kubernetes.md#what-are-the-biggest-kubernetes-challenges-you-ve-faced-in-production-and-how-di) | Medium | 1 |
| [What do you mean by RBAC? (IAM/Kubernetes context.)](../topics/kubernetes.md#what-do-you-mean-by-rbac-iam-kubernetes-context) | Medium | 2 |
| [What happens when a Pod crashes?](../topics/kubernetes.md#what-happens-when-a-pod-crashes) | Medium | 2 |
| [What indicators tell you that the issue is in the Kubernetes control plane versus the underlying AWS infrastructure?](../topics/kubernetes.md#what-indicators-tell-you-that-the-issue-is-in-the-kubernetes-control-plane-versu) | Medium | 4 |
| [What is a Deployment in Kubernetes?](../topics/kubernetes.md#what-is-a-deployment-in-kubernetes) | Easy | 2 |
| [What is a Pod Disruption Budget (PDB), and why is it important for production workloads?](../topics/kubernetes.md#what-is-a-pod-disruption-budget-pdb-and-why-is-it-important-for-production-workl) | Medium | 2 |
| [What is a Pod?](../topics/kubernetes.md#what-is-a-pod) | Easy | 2 |
| [What is a Service in Kubernetes?](../topics/kubernetes.md#what-is-a-service-in-kubernetes) | Easy | 2 |
| [What is Blue-Green Deployment?](../topics/kubernetes.md#what-is-blue-green-deployment) | Medium | 3 |
| [What is daemonset and replicaset](../topics/kubernetes.md#what-is-daemonset-and-replicaset) | Medium | 1 |
| [What is Exit Status 2 in Kubernetes?](../topics/kubernetes.md#what-is-exit-status-2-in-kubernetes) | Medium | 4 |
| [What is Kubernetes and how do you use it in your projects?](../topics/kubernetes.md#what-is-kubernetes-and-how-do-you-use-it-in-your-projects) | Hard | 1 |
| [What is Kubernetes, and why is it used?](../topics/kubernetes.md#what-is-kubernetes-and-why-is-it-used) | Easy | 2 |
| [What is RBAC and its components](../topics/kubernetes.md#what-is-rbac-and-its-components) | Medium | 1 |
| [What is the difference between a pod and a service in Kubernetes?](../topics/kubernetes.md#what-is-the-difference-between-a-pod-and-a-service-in-kubernetes) | Medium | 2 |
| [What metrics and logs did you monitor after deployment?](../topics/kubernetes.md#what-metrics-and-logs-did-you-monitor-after-deployment) | Medium | 2 |
| [What steps would you take if a Kubernetes pod is stuck in CrashLoopBackOff?](../topics/kubernetes.md#what-steps-would-you-take-if-a-kubernetes-pod-is-stuck-in-crashloopbackoff) | Medium | 1 |
| [What type of Instances used for worker nodes in kubernetes?](../topics/kubernetes.md#what-type-of-instances-used-for-worker-nodes-in-kubernetes) | Medium | 1 |
| [What's the most challenging Kubernetes production issue you've faced? Share it in the comments your experience might help someone else.](../topics/kubernetes.md#what-s-the-most-challenging-kubernetes-production-issue-you-ve-faced-share-it-in) | Hard | 1 |
| [What's the most difficult Kubernetes interview question you've been asked?](../topics/kubernetes.md#what-s-the-most-difficult-kubernetes-interview-question-you-ve-been-asked) | Medium | 1 |
| [Which commands do you use for application deployment in Kubernetes?](../topics/kubernetes.md#which-commands-do-you-use-for-application-deployment-in-kubernetes) | Medium | 2 |
| [Which Kubernetes topic do you want me to cover next with short answers?](../topics/kubernetes.md#which-kubernetes-topic-do-you-want-me-to-cover-next-with-short-answers) | Medium | 1 |
| [Why did your team choose Kubernetes instead of another managed service?](../topics/kubernetes.md#why-did-your-team-choose-kubernetes-instead-of-another-managed-service) | Medium | 1 |
| [Why is a pod stuck in CrashLoopBackOff? How would you debug it?](../topics/kubernetes.md#why-is-a-pod-stuck-in-crashloopbackoff-how-would-you-debug-it) | Medium | 1 |
| [Why you have choose M type to R type instance for your kubernetes cluster?](../topics/kubernetes.md#why-you-have-choose-m-type-to-r-type-instance-for-your-kubernetes-cluster) | Medium | 1 |
| [Will Kubernetes immediately reschedule them to another node?](../topics/kubernetes.md#will-kubernetes-immediately-reschedule-them-to-another-node) | Medium | 1 |
| [Write the Kubernetes manifest file to deploy the new replica agent as a DaemonSet in kubernetes cluster](../topics/kubernetes.md#write-the-kubernetes-manifest-file-to-deploy-the-new-replica-agent-as-a-daemonse) | Medium | 1 |
| [Your Kubernetes cluster is healthy but requests intermittently return 503. How do you troubleshoot it?](../topics/kubernetes.md#your-kubernetes-cluster-is-healthy-but-requests-intermittently-return-503-how-do) | Medium | 4 |
| [Your Pod is stuck in CrashLoopBackOff. Walk me through your investigation.](../topics/kubernetes.md#your-pod-is-stuck-in-crashloopbackoff-walk-me-through-your-investigation) | Medium | 1 |

## Learning resources

- Practice [most asked overall](../study-guides/most-asked.md)
- Filter by [difficulty](../study-guides/by-difficulty.md)
- Browse [companies](../companies/README.md)

[← All topics](./README.md) · [Home](../README.md)
