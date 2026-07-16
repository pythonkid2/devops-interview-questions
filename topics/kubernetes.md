# Kubernetes

[Home](../README.md) > [Topics](./README.md) > **Kubernetes**

**74** real interview questions. Study this page end-to-end — open a detail page only when an answer is enriched.

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
| Questions | 74 |
| Easy / Medium / Hard | 7 / 56 / 11 |
| Companies | 9 |

## Most asked

- [After deployment, application latency suddenly doubles while CPU and memory remain normal. How would you approach the investigation?](../topics/kubernetes.md#after-deployment-application-latency-suddenly-doubles-while-cpu-and-memory-remai) — **4×** · Medium
  <a id="after-deployment-application-latency-suddenly-doubles-while-cpu-and-memory-remai"></a>
- [During a node group upgrade, several workloads become unavailable even though replicas exist. What production checks would you perform?](../topics/kubernetes.md#during-a-node-group-upgrade-several-workloads-become-unavailable-even-though-rep) — **4×** · Medium
  <a id="during-a-node-group-upgrade-several-workloads-become-unavailable-even-though-rep"></a>
- [How do you perform a zero-downtime Kubernetes cluster upgrade in production?](../topics/kubernetes.md#how-do-you-perform-a-zero-downtime-kubernetes-cluster-upgrade-in-production) — **4×** · Hard
  <a id="how-do-you-perform-a-zero-downtime-kubernetes-cluster-upgrade-in-production"></a>
- [How would you determine whether production failures originate from Kubernetes, networking, or the application itself?](../topics/kubernetes.md#how-would-you-determine-whether-production-failures-originate-from-kubernetes-ne) — **4×** · Medium
  <a id="how-would-you-determine-whether-production-failures-originate-from-kubernetes-ne"></a>
- [How would you migrate a stateful application to Kubernetes with minimal downtime?](../topics/kubernetes.md#how-would-you-migrate-a-stateful-application-to-kubernetes-with-minimal-downtime) — **4×** · Medium
  <a id="how-would-you-migrate-a-stateful-application-to-kubernetes-with-minimal-downtime"></a>
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

- [After deployment, application latency suddenly doubles while CPU and memory remain normal. How would you approach the investigation?](../topics/kubernetes.md#after-deployment-application-latency-suddenly-doubles-while-cpu-and-memory-remai) — 4×
  <a id="after-deployment-application-latency-suddenly-doubles-while-cpu-and-memory-remai"></a>
- [During a node group upgrade, several workloads become unavailable even though replicas exist. What production checks would you perform?](../topics/kubernetes.md#during-a-node-group-upgrade-several-workloads-become-unavailable-even-though-rep) — 4×
  <a id="during-a-node-group-upgrade-several-workloads-become-unavailable-even-though-rep"></a>
- [How would you determine whether production failures originate from Kubernetes, networking, or the application itself?](../topics/kubernetes.md#how-would-you-determine-whether-production-failures-originate-from-kubernetes-ne) — 4×
  <a id="how-would-you-determine-whether-production-failures-originate-from-kubernetes-ne"></a>
- [How would you migrate a stateful application to Kubernetes with minimal downtime?](../topics/kubernetes.md#how-would-you-migrate-a-stateful-application-to-kubernetes-with-minimal-downtime) — 4×
  <a id="how-would-you-migrate-a-stateful-application-to-kubernetes-with-minimal-downtime"></a>
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
- [Architecture of kubernetes](../topics/kubernetes.md#architecture-of-kubernetes) — 1×
  <a id="architecture-of-kubernetes"></a>
- [Docker, Kubernetes & Jenkins](../topics/kubernetes.md#docker-kubernetes-jenkins) — 1× · tags: `Docker`, `Jenkins`
  <a id="docker-kubernetes-jenkins"></a>
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
- [How do you provide pod access to S3 bucket](../topics/kubernetes.md#how-do-you-provide-pod-access-to-s3-bucket) — 1×
  <a id="how-do-you-provide-pod-access-to-s3-bucket"></a>
- [How do you use hpa in prod env and what kind of metric target in cluster](../topics/kubernetes.md#how-do-you-use-hpa-in-prod-env-and-what-kind-of-metric-target-in-cluster) — 1×
  <a id="how-do-you-use-hpa-in-prod-env-and-what-kind-of-metric-target-in-cluster"></a>
- [How does Kubernetes Service Discovery work?](../topics/kubernetes.md#how-does-kubernetes-service-discovery-work) — 1×
  <a id="how-does-kubernetes-service-discovery-work"></a>
- [Kubernetes pods are Running but users receive 503 errors. What will you check?](../topics/kubernetes.md#kubernetes-pods-are-running-but-users-receive-503-errors-what-will-you-check) — 1×
  <a id="kubernetes-pods-are-running-but-users-receive-503-errors-what-will-you-check"></a>
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
- [Which Kubernetes topic do you want me to cover next with short answers?](../topics/kubernetes.md#which-kubernetes-topic-do-you-want-me-to-cover-next-with-short-answers) — 1×
  <a id="which-kubernetes-topic-do-you-want-me-to-cover-next-with-short-answers"></a>
- [Why is a pod stuck in CrashLoopBackOff? How would you debug it?](../topics/kubernetes.md#why-is-a-pod-stuck-in-crashloopbackoff-how-would-you-debug-it) — 1×
  <a id="why-is-a-pod-stuck-in-crashloopbackoff-how-would-you-debug-it"></a>

## Advanced

- [How do you perform a zero-downtime Kubernetes cluster upgrade in production?](../topics/kubernetes.md#how-do-you-perform-a-zero-downtime-kubernetes-cluster-upgrade-in-production) — 4×
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
- [A Kubernetes pod keeps crashing. How do you investigate?](../topics/kubernetes.md#a-kubernetes-pod-keeps-crashing-how-do-you-investigate)
- [A Pod is in CrashLoopBackOff. How would you troubleshoot it?](../topics/kubernetes.md#a-pod-is-in-crashloopbackoff-how-would-you-troubleshoot-it)
- [A Pod is running but the application is not accessible. What would you check?](../topics/kubernetes.md#a-pod-is-running-but-the-application-is-not-accessible-what-would-you-check)
- [An Amazon EKS application starts returning intermittent 502/503 errors immediately after deployment. How would you identify whether the issue is related to Kubernetes, the Load Balancer, or the application?](../topics/kubernetes.md#an-amazon-eks-application-starts-returning-intermittent-502-503-errors-immediate)
- [Architecture of kubernetes](../topics/kubernetes.md#architecture-of-kubernetes)
- [Azure Kubernetes Service (AKS) & Docker](../topics/kubernetes.md#azure-kubernetes-service-aks-docker)
- [Can you explain how Kubernetes scheduling works?](../topics/kubernetes.md#can-you-explain-how-kubernetes-scheduling-works)
- [Difference between Deployment, StatefulSet, DaemonSet, and Job.](../topics/kubernetes.md#difference-between-deployment-statefulset-daemonset-and-job)
- [Difference between Pod and Container?](../topics/kubernetes.md#difference-between-pod-and-container) — tags: `Docker`
- [Docker, Kubernetes & Jenkins](../topics/kubernetes.md#docker-kubernetes-jenkins) — tags: `Docker`, `Jenkins`
- [Explain about Kubernetes.](../topics/kubernetes.md#explain-about-kubernetes)
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
- [How do you implement continuous integration and delivery in a Kubernetes cluster?](../topics/kubernetes.md#how-do-you-implement-continuous-integration-and-delivery-in-a-kubernetes-cluster)
- [How do you implement RBAC in Kubernetes?](../topics/kubernetes.md#how-do-you-implement-rbac-in-kubernetes)
- [How do you integrate GitHub or Bitbucket with Kubernetes? Explain the steps.](../topics/kubernetes.md#how-do-you-integrate-github-or-bitbucket-with-kubernetes-explain-the-steps)
- [How do you perform a zero-downtime Kubernetes cluster upgrade in production?](../topics/kubernetes.md#how-do-you-perform-a-zero-downtime-kubernetes-cluster-upgrade-in-production)
- [How do you provide pod access to S3 bucket](../topics/kubernetes.md#how-do-you-provide-pod-access-to-s3-bucket)
- [How do you use hpa in prod env and what kind of metric target in cluster](../topics/kubernetes.md#how-do-you-use-hpa-in-prod-env-and-what-kind-of-metric-target-in-cluster)
- [How does Kubernetes perform self-healing?](../topics/kubernetes.md#how-does-kubernetes-perform-self-healing)
- [How does Kubernetes Service Discovery work?](../topics/kubernetes.md#how-does-kubernetes-service-discovery-work)
- [How does Prometheus work for monitoring in a Kubernetes cluster?](../topics/kubernetes.md#how-does-prometheus-work-for-monitoring-in-a-kubernetes-cluster)
- [How to create pod in Kubernetes.](../topics/kubernetes.md#how-to-create-pod-in-kubernetes)
- [How to resolve storage issue in a pod.](../topics/kubernetes.md#how-to-resolve-storage-issue-in-a-pod)
- [How would you check if a GPU pod in Kubernetes is using the GPU assigned to it?](../topics/kubernetes.md#how-would-you-check-if-a-gpu-pod-in-kubernetes-is-using-the-gpu-assigned-to-it)
- [How would you handle CUDA driver upgrades in Kubernetes without disrupting thousands of running AI pods?](../topics/kubernetes.md#how-would-you-handle-cuda-driver-upgrades-in-kubernetes-without-disrupting-thous)
- [How would you migrate a stateful application to Kubernetes with minimal downtime?](../topics/kubernetes.md#how-would-you-migrate-a-stateful-application-to-kubernetes-with-minimal-downtime)
- [Kubernetes pods are Running but users receive 503 errors. What will you check?](../topics/kubernetes.md#kubernetes-pods-are-running-but-users-receive-503-errors-what-will-you-check)
- [Production error crashloopback of how do you troubleshoot.](../topics/kubernetes.md#production-error-crashloopback-of-how-do-you-troubleshoot)
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
- [Which commands do you use for application deployment in Kubernetes?](../topics/kubernetes.md#which-commands-do-you-use-for-application-deployment-in-kubernetes)
- [Which Kubernetes topic do you want me to cover next with short answers?](../topics/kubernetes.md#which-kubernetes-topic-do-you-want-me-to-cover-next-with-short-answers)
- [Why is a pod stuck in CrashLoopBackOff? How would you debug it?](../topics/kubernetes.md#why-is-a-pod-stuck-in-crashloopbackoff-how-would-you-debug-it)
- [Your Kubernetes cluster is healthy but requests intermittently return 503. How do you troubleshoot it?](../topics/kubernetes.md#your-kubernetes-cluster-is-healthy-but-requests-intermittently-return-503-how-do)

## Companies asking

- [Argyll Infotech](../companies/argyll-infotech.md)
- [Fineshift Software Pvt. Ltd.](../companies/fineshift-software-pvt-ltd.md)
- [Global Payments](../companies/global-payments.md)
- [Infosys](../companies/infosys.md)
- [Mirafra](../companies/mirafra.md)
- [NVIDIA](../companies/nvidia.md)
- [PwC](../companies/pwc.md)
- [TCS](../companies/tcs.md)
- [zemoso technologies](../companies/zemoso-technologies.md)

## Recently added

- [What is Blue-Green Deployment?](../topics/kubernetes.md#what-is-blue-green-deployment) — 2026-07-16
- [What do you mean by RBAC? (IAM/Kubernetes context.)](../topics/kubernetes.md#what-do-you-mean-by-rbac-iam-kubernetes-context) — 2026-07-16
- [How do you automate Kubernetes deployment?](../topics/kubernetes.md#how-do-you-automate-kubernetes-deployment) — 2026-07-16
- [Can you automate Kubernetes deployment?](../topics/kubernetes.md#can-you-automate-kubernetes-deployment) — 2026-07-16
- [What metrics and logs did you monitor after deployment?](../topics/kubernetes.md#what-metrics-and-logs-did-you-monitor-after-deployment) — 2026-07-16
- [How would you determine whether production failures originate from Kubernetes, networking, or the application itself?](../topics/kubernetes.md#how-would-you-determine-whether-production-failures-originate-from-kubernetes-ne) — 2026-07-16
- [After deployment, application latency suddenly doubles while CPU and memory remain normal. How would you approach the investigation?](../topics/kubernetes.md#after-deployment-application-latency-suddenly-doubles-while-cpu-and-memory-remai) — 2026-07-16
- [What indicators tell you that the issue is in the Kubernetes control plane versus the underlying AWS infrastructure?](../topics/kubernetes.md#what-indicators-tell-you-that-the-issue-is-in-the-kubernetes-control-plane-versu) — 2026-07-16
- [During a node group upgrade, several workloads become unavailable even though replicas exist. What production checks would you perform?](../topics/kubernetes.md#during-a-node-group-upgrade-several-workloads-become-unavailable-even-though-rep) — 2026-07-16
- [How would you migrate a stateful application to Kubernetes with minimal downtime?](../topics/kubernetes.md#how-would-you-migrate-a-stateful-application-to-kubernetes-with-minimal-downtime) — 2026-07-16
- [How do you perform a zero-downtime Kubernetes cluster upgrade in production?](../topics/kubernetes.md#how-do-you-perform-a-zero-downtime-kubernetes-cluster-upgrade-in-production) — 2026-07-16
- [Your Kubernetes cluster is healthy but requests intermittently return 503. How do you troubleshoot it?](../topics/kubernetes.md#your-kubernetes-cluster-is-healthy-but-requests-intermittently-return-503-how-do) — 2026-07-16
- [Explain Kubernetes Manifest Files and the specific purposes of different YAML resources (Pods, Deployments, Services).](../topics/kubernetes.md#explain-kubernetes-manifest-files-and-the-specific-purposes-of-different-yaml-re) — 2026-07-16
- [A Kubernetes GPU pod requests 16GB VRAM but only gets 12GB due to fragmentation. How do you detect and fix it in real time?](../topics/kubernetes.md#a-kubernetes-gpu-pod-requests-16gb-vram-but-only-gets-12gb-due-to-fragmentation-) — 2026-07-16
- [How would you check if a GPU pod in Kubernetes is using the GPU assigned to it?](../topics/kubernetes.md#how-would-you-check-if-a-gpu-pod-in-kubernetes-is-using-the-gpu-assigned-to-it) — 2026-07-16

## Related topics

- [Docker](./docker.md)
- [ArgoCD](./argocd.md)

## All questions

| Question | Diff | Asked |
| --- | --- | ---: |
| [A Kubernetes GPU pod requests 16GB VRAM but only gets 12GB due to fragmentation. How do you detect and fix it in real time?](../topics/kubernetes.md#a-kubernetes-gpu-pod-requests-16gb-vram-but-only-gets-12gb-due-to-fragmentation-) | Medium | 2 |
| [A Kubernetes pod keeps crashing. How do you investigate?](../topics/kubernetes.md#a-kubernetes-pod-keeps-crashing-how-do-you-investigate) | Medium | 2 |
| [A Pod is in CrashLoopBackOff. How would you troubleshoot it?](../topics/kubernetes.md#a-pod-is-in-crashloopbackoff-how-would-you-troubleshoot-it) | Medium | 2 |
| [A Pod is running but the application is not accessible. What would you check?](../topics/kubernetes.md#a-pod-is-running-but-the-application-is-not-accessible-what-would-you-check) | Medium | 2 |
| [After deployment, application latency suddenly doubles while CPU and memory remain normal. How would you approach the investigation?](../topics/kubernetes.md#after-deployment-application-latency-suddenly-doubles-while-cpu-and-memory-remai) | Medium | 4 |
| [An Amazon EKS application starts returning intermittent 502/503 errors immediately after deployment. How would you identify whether the issue is related to Kubernetes, the Load Balancer, or the application?](../topics/kubernetes.md#an-amazon-eks-application-starts-returning-intermittent-502-503-errors-immediate) | Medium | 2 |
| [Architecture of kubernetes](../topics/kubernetes.md#architecture-of-kubernetes) | Medium | 1 |
| [Azure Kubernetes Service (AKS) & Docker](../topics/kubernetes.md#azure-kubernetes-service-aks-docker) | Easy | 1 |
| [Can you automate Kubernetes deployment?](../topics/kubernetes.md#can-you-automate-kubernetes-deployment) | Medium | 2 |
| [Can you explain how Kubernetes scheduling works?](../topics/kubernetes.md#can-you-explain-how-kubernetes-scheduling-works) | Medium | 2 |
| [Design an end-to-end automated deployment solution for multiple environments.](../topics/kubernetes.md#design-an-end-to-end-automated-deployment-solution-for-multiple-environments) | Hard | 1 |
| [Difference between Deployment, StatefulSet, DaemonSet, and Job.](../topics/kubernetes.md#difference-between-deployment-statefulset-daemonset-and-job) | Medium | 3 |
| [Difference between Pod and Container?](../topics/kubernetes.md#difference-between-pod-and-container) | Easy | 2 |
| [Docker, Kubernetes & Jenkins](../topics/kubernetes.md#docker-kubernetes-jenkins) | Medium | 1 |
| [During a node group upgrade, several workloads become unavailable even though replicas exist. What production checks would you perform?](../topics/kubernetes.md#during-a-node-group-upgrade-several-workloads-become-unavailable-even-though-rep) | Medium | 4 |
| [Explain about Kubernetes.](../topics/kubernetes.md#explain-about-kubernetes) | Medium | 2 |
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
| [How do you implement continuous integration and delivery in a Kubernetes cluster?](../topics/kubernetes.md#how-do-you-implement-continuous-integration-and-delivery-in-a-kubernetes-cluster) | Hard | 2 |
| [How do you implement RBAC in Kubernetes?](../topics/kubernetes.md#how-do-you-implement-rbac-in-kubernetes) | Medium | 2 |
| [How do you integrate GitHub or Bitbucket with Kubernetes? Explain the steps.](../topics/kubernetes.md#how-do-you-integrate-github-or-bitbucket-with-kubernetes-explain-the-steps) | Hard | 2 |
| [How do you perform a zero-downtime Kubernetes cluster upgrade in production?](../topics/kubernetes.md#how-do-you-perform-a-zero-downtime-kubernetes-cluster-upgrade-in-production) | Hard | 4 |
| [How do you provide pod access to S3 bucket](../topics/kubernetes.md#how-do-you-provide-pod-access-to-s3-bucket) | Medium | 1 |
| [How do you troubleshoot deployment failures?](../topics/kubernetes.md#how-do-you-troubleshoot-deployment-failures) | Medium | 2 |
| [How do you use hpa in prod env and what kind of metric target in cluster](../topics/kubernetes.md#how-do-you-use-hpa-in-prod-env-and-what-kind-of-metric-target-in-cluster) | Medium | 1 |
| [How does Kubernetes perform self-healing?](../topics/kubernetes.md#how-does-kubernetes-perform-self-healing) | Medium | 2 |
| [How does Kubernetes Service Discovery work?](../topics/kubernetes.md#how-does-kubernetes-service-discovery-work) | Medium | 1 |
| [How does Prometheus work for monitoring in a Kubernetes cluster?](../topics/kubernetes.md#how-does-prometheus-work-for-monitoring-in-a-kubernetes-cluster) | Hard | 1 |
| [How to create pod in Kubernetes.](../topics/kubernetes.md#how-to-create-pod-in-kubernetes) | Medium | 2 |
| [How to resolve storage issue in a pod.](../topics/kubernetes.md#how-to-resolve-storage-issue-in-a-pod) | Medium | 2 |
| [How will you set up the Rest Assured framework when APIs are internal to Kubernetes clusters?](../topics/kubernetes.md#how-will-you-set-up-the-rest-assured-framework-when-apis-are-internal-to-kuberne) | Medium | 2 |
| [How would you check if a GPU pod in Kubernetes is using the GPU assigned to it?](../topics/kubernetes.md#how-would-you-check-if-a-gpu-pod-in-kubernetes-is-using-the-gpu-assigned-to-it) | Easy | 2 |
| [How would you determine whether production failures originate from Kubernetes, networking, or the application itself?](../topics/kubernetes.md#how-would-you-determine-whether-production-failures-originate-from-kubernetes-ne) | Medium | 4 |
| [How would you handle CUDA driver upgrades in Kubernetes without disrupting thousands of running AI pods?](../topics/kubernetes.md#how-would-you-handle-cuda-driver-upgrades-in-kubernetes-without-disrupting-thous) | Hard | 2 |
| [How would you migrate a stateful application to Kubernetes with minimal downtime?](../topics/kubernetes.md#how-would-you-migrate-a-stateful-application-to-kubernetes-with-minimal-downtime) | Medium | 4 |
| [Kubernetes pods are Running but users receive 503 errors. What will you check?](../topics/kubernetes.md#kubernetes-pods-are-running-but-users-receive-503-errors-what-will-you-check) | Medium | 1 |
| [Production error crashloopback of how do you troubleshoot.](../topics/kubernetes.md#production-error-crashloopback-of-how-do-you-troubleshoot) | Hard | 1 |
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
| [Which commands do you use for application deployment in Kubernetes?](../topics/kubernetes.md#which-commands-do-you-use-for-application-deployment-in-kubernetes) | Medium | 2 |
| [Which Kubernetes topic do you want me to cover next with short answers?](../topics/kubernetes.md#which-kubernetes-topic-do-you-want-me-to-cover-next-with-short-answers) | Medium | 1 |
| [Why is a pod stuck in CrashLoopBackOff? How would you debug it?](../topics/kubernetes.md#why-is-a-pod-stuck-in-crashloopbackoff-how-would-you-debug-it) | Medium | 1 |
| [Your Kubernetes cluster is healthy but requests intermittently return 503. How do you troubleshoot it?](../topics/kubernetes.md#your-kubernetes-cluster-is-healthy-but-requests-intermittently-return-503-how-do) | Medium | 4 |

## Learning resources

- Practice [most asked overall](../study-guides/most-asked.md)
- Filter by [difficulty](../study-guides/by-difficulty.md)
- Browse [companies](../companies/README.md)

[← All topics](./README.md) · [Home](../README.md)
