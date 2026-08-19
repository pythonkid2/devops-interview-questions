# Incident Response

[Home](../README.md) > [Topics](./README.md) > **Incident Response**

**69** real interview questions. Study this page end-to-end — open a detail page only when an answer is enriched.

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
| Questions | 69 |
| Easy / Medium / Hard | 0 / 37 / 32 |
| Companies | 8 |

## Most asked

- [How do you correlate logs, metrics, and traces during a production incident?](../topics/incident-response.md#how-do-you-correlate-logs-metrics-and-traces-during-a-production-incident) — **9×** · Hard
  <a id="how-do-you-correlate-logs-metrics-and-traces-during-a-production-incident"></a>
- [Explain the most challenging production incident you've handled and the architectural improvements you made afterward.](../topics/incident-response.md#explain-the-most-challenging-production-incident-you-ve-handled-and-the-architec) — **7×** · Hard
  <a id="explain-the-most-challenging-production-incident-you-ve-handled-and-the-architec"></a>
- [Your Kubernetes cluster is healthy but requests intermittently return 503. How do you troubleshoot it?](../topics/incident-response.md#your-kubernetes-cluster-is-healthy-but-requests-intermittently-return-503-how-do) — **7×** · Medium · tags: `Kubernetes`
  <a id="your-kubernetes-cluster-is-healthy-but-requests-intermittently-return-503-how-do"></a>
- [After deployment, application latency suddenly doubles while CPU and memory remain normal. How would you approach the investigation?](../topics/incident-response.md#after-deployment-application-latency-suddenly-doubles-while-cpu-and-memory-remai) — **5×** · Medium
  <a id="after-deployment-application-latency-suddenly-doubles-while-cpu-and-memory-remai"></a>
- [How would you troubleshoot a deployment that succeeded but users are receiving 503 errors?](../topics/incident-response.md#how-would-you-troubleshoot-a-deployment-that-succeeded-but-users-are-receiving-5) — **4×** · Medium
  <a id="how-would-you-troubleshoot-a-deployment-that-succeeded-but-users-are-receiving-5"></a>
- [Production is down. Users are impacted. What will you do?](../topics/incident-response.md#production-is-down-users-are-impacted-what-will-you-do) — **4×** · Hard
  <a id="production-is-down-users-are-impacted-what-will-you-do"></a>
- [Tell me about a major incident or outage you handled. How did you respond, and what improvements were implemented afterward?](../topics/incident-response.md#tell-me-about-a-major-incident-or-outage-you-handled-how-did-you-respond-and-wha) — **3×** · Medium
  <a id="tell-me-about-a-major-incident-or-outage-you-handled-how-did-you-respond-and-wha"></a>
- [An Amazon EKS application starts returning intermittent 502/503 errors immediately after deployment. How would you identify whether the issue is related to Kubernetes, the Load Balancer, or the application?](../topics/incident-response.md#an-amazon-eks-application-starts-returning-intermittent-502-503-errors-immediate) — **2×** · Medium · tags: `EKS`, `Kubernetes`, `Load Balancing`
  <a id="an-amazon-eks-application-starts-returning-intermittent-502-503-errors-immediate"></a>
- [Application latency suddenly increased. How would you troubleshoot?](../topics/incident-response.md#application-latency-suddenly-increased-how-would-you-troubleshoot) — **2×** · Medium
  <a id="application-latency-suddenly-increased-how-would-you-troubleshoot"></a>
- [Describe a production incident you handled. What was the root cause, how did you resolve it, and what did you learn from the experience?](../topics/incident-response.md#describe-a-production-incident-you-handled-what-was-the-root-cause-how-did-you-r) — **2×** · Hard
  <a id="describe-a-production-incident-you-handled-what-was-the-root-cause-how-did-you-r"></a>
- [Explain one challenging production incident and how you resolved it.](../topics/incident-response.md#explain-one-challenging-production-incident-and-how-you-resolved-it) — **2×** · Hard
  <a id="explain-one-challenging-production-incident-and-how-you-resolved-it"></a>
- [Have you worked on incident management / production incidents?](../topics/incident-response.md#have-you-worked-on-incident-management-production-incidents) — **2×** · Hard
  <a id="have-you-worked-on-incident-management-production-incidents"></a>
- [How do you perform a Root Cause Analysis (RCA) after a major production incident?](../topics/incident-response.md#how-do-you-perform-a-root-cause-analysis-rca-after-a-major-production-incident) — **2×** · Hard
  <a id="how-do-you-perform-a-root-cause-analysis-rca-after-a-major-production-incident"></a>
- [How would you troubleshoot intermittent 503 errors in Kubernetes?](../topics/incident-response.md#how-would-you-troubleshoot-intermittent-503-errors-in-kubernetes) — **2×** · Medium · tags: `Kubernetes`
  <a id="how-would-you-troubleshoot-intermittent-503-errors-in-kubernetes"></a>
- [Incident Response](../topics/incident-response.md#incident-response) — **2×** · Medium
  <a id="incident-response"></a>
- [Kubernetes pods are Running but users receive 503 errors. What will you check?](../topics/incident-response.md#kubernetes-pods-are-running-but-users-receive-503-errors-what-will-you-check) — **2×** · Medium · tags: `Kubernetes`
  <a id="kubernetes-pods-are-running-but-users-receive-503-errors-what-will-you-check"></a>
- [Production error crashloopback of how do you troubleshoot.](../topics/incident-response.md#production-error-crashloopback-of-how-do-you-troubleshoot) — **2×** · Hard
  <a id="production-error-crashloopback-of-how-do-you-troubleshoot"></a>
- [Production is down, and multiple teams join the incident bridge. How would you handle the situation?](../topics/incident-response.md#production-is-down-and-multiple-teams-join-the-incident-bridge-how-would-you-han) — **2×** · Hard
  <a id="production-is-down-and-multiple-teams-join-the-incident-bridge-how-would-you-han"></a>
- [Read real outage RCAs.](../topics/incident-response.md#read-real-outage-rcas) — **2×** · Medium
  <a id="read-real-outage-rcas"></a>
- [Tell us about a production incident and how you resolved it.](../topics/incident-response.md#tell-us-about-a-production-incident-and-how-you-resolved-it) — **2×** · Hard
  <a id="tell-us-about-a-production-incident-and-how-you-resolved-it"></a>
- [Users are getting 503 errors, but all Pods are running. Where do you start?](../topics/incident-response.md#users-are-getting-503-errors-but-all-pods-are-running-where-do-you-start) — **2×** · Medium · tags: `Kubernetes`
  <a id="users-are-getting-503-errors-but-all-pods-are-running-where-do-you-start"></a>
- [Users are getting 503 Service Unavailable, but all Pods are running. What would you check?](../topics/incident-response.md#users-are-getting-503-service-unavailable-but-all-pods-are-running-what-would-yo) — **2×** · Medium · tags: `Kubernetes`
  <a id="users-are-getting-503-service-unavailable-but-all-pods-are-running-what-would-yo"></a>
- [Users report a slow application, but the servers look healthy. How would you troubleshoot?](../topics/incident-response.md#users-report-a-slow-application-but-the-servers-look-healthy-how-would-you-troub) — **2×** · Medium
  <a id="users-report-a-slow-application-but-the-servers-look-healthy-how-would-you-troub"></a>
- [Walk me through a production incident you personally handled — what was your role?](../topics/incident-response.md#walk-me-through-a-production-incident-you-personally-handled-what-was-your-role) — **2×** · Hard
  <a id="walk-me-through-a-production-incident-you-personally-handled-what-was-your-role"></a>
- [Walk me through your worst production incident. What was it about? What did you do? What would you have done differently?](../topics/incident-response.md#walk-me-through-your-worst-production-incident-what-was-it-about-what-did-you-do) — **2×** · Hard
  <a id="walk-me-through-your-worst-production-incident-what-was-it-about-what-did-you-do"></a>

## Beginner

_None in this band yet._

## Intermediate

- [Your Kubernetes cluster is healthy but requests intermittently return 503. How do you troubleshoot it?](../topics/incident-response.md#your-kubernetes-cluster-is-healthy-but-requests-intermittently-return-503-how-do) — 7× · tags: `Kubernetes`
  <a id="your-kubernetes-cluster-is-healthy-but-requests-intermittently-return-503-how-do"></a>
- [After deployment, application latency suddenly doubles while CPU and memory remain normal. How would you approach the investigation?](../topics/incident-response.md#after-deployment-application-latency-suddenly-doubles-while-cpu-and-memory-remai) — 5×
  <a id="after-deployment-application-latency-suddenly-doubles-while-cpu-and-memory-remai"></a>
- [How would you troubleshoot a deployment that succeeded but users are receiving 503 errors?](../topics/incident-response.md#how-would-you-troubleshoot-a-deployment-that-succeeded-but-users-are-receiving-5) — 4×
  <a id="how-would-you-troubleshoot-a-deployment-that-succeeded-but-users-are-receiving-5"></a>
- [Tell me about a major incident or outage you handled. How did you respond, and what improvements were implemented afterward?](../topics/incident-response.md#tell-me-about-a-major-incident-or-outage-you-handled-how-did-you-respond-and-wha) — 3×
  <a id="tell-me-about-a-major-incident-or-outage-you-handled-how-did-you-respond-and-wha"></a>
- [An Amazon EKS application starts returning intermittent 502/503 errors immediately after deployment. How would you identify whether the issue is related to Kubernetes, the Load Balancer, or the application?](../topics/incident-response.md#an-amazon-eks-application-starts-returning-intermittent-502-503-errors-immediate) — 2× · tags: `EKS`, `Kubernetes`, `Load Balancing`
  <a id="an-amazon-eks-application-starts-returning-intermittent-502-503-errors-immediate"></a>
- [Application latency suddenly increased. How would you troubleshoot?](../topics/incident-response.md#application-latency-suddenly-increased-how-would-you-troubleshoot) — 2×
  <a id="application-latency-suddenly-increased-how-would-you-troubleshoot"></a>
- [How would you troubleshoot intermittent 503 errors in Kubernetes?](../topics/incident-response.md#how-would-you-troubleshoot-intermittent-503-errors-in-kubernetes) — 2× · tags: `Kubernetes`
  <a id="how-would-you-troubleshoot-intermittent-503-errors-in-kubernetes"></a>
- [Incident Response](../topics/incident-response.md#incident-response) — 2×
  <a id="incident-response"></a>
- [Kubernetes pods are Running but users receive 503 errors. What will you check?](../topics/incident-response.md#kubernetes-pods-are-running-but-users-receive-503-errors-what-will-you-check) — 2× · tags: `Kubernetes`
  <a id="kubernetes-pods-are-running-but-users-receive-503-errors-what-will-you-check"></a>
- [Read real outage RCAs.](../topics/incident-response.md#read-real-outage-rcas) — 2×
  <a id="read-real-outage-rcas"></a>
- [Users are getting 503 errors, but all Pods are running. Where do you start?](../topics/incident-response.md#users-are-getting-503-errors-but-all-pods-are-running-where-do-you-start) — 2× · tags: `Kubernetes`
  <a id="users-are-getting-503-errors-but-all-pods-are-running-where-do-you-start"></a>
- [Users are getting 503 Service Unavailable, but all Pods are running. What would you check?](../topics/incident-response.md#users-are-getting-503-service-unavailable-but-all-pods-are-running-what-would-yo) — 2× · tags: `Kubernetes`
  <a id="users-are-getting-503-service-unavailable-but-all-pods-are-running-what-would-yo"></a>
- [Users report a slow application, but the servers look healthy. How would you troubleshoot?](../topics/incident-response.md#users-report-a-slow-application-but-the-servers-look-healthy-how-would-you-troub) — 2×
  <a id="users-report-a-slow-application-but-the-servers-look-healthy-how-would-you-troub"></a>
- [You had HA. Still had 9 minutes of outage. Walk me through what your team missed.](../topics/incident-response.md#you-had-ha-still-had-9-minutes-of-outage-walk-me-through-what-your-team-missed) — 2×
  <a id="you-had-ha-still-had-9-minutes-of-outage-walk-me-through-what-your-team-missed"></a>
- [Your application latency increased by 40% overnight. How would you investigate it?](../topics/incident-response.md#your-application-latency-increased-by-40-overnight-how-would-you-investigate-it) — 2×
  <a id="your-application-latency-increased-by-40-overnight-how-would-you-investigate-it"></a>
- [Your application latency suddenly increased after a release. Walk me through your debugging approach.](../topics/incident-response.md#your-application-latency-suddenly-increased-after-a-release-walk-me-through-your) — 2×
  <a id="your-application-latency-suddenly-increased-after-a-release-walk-me-through-your"></a>
- [504 errors on the playback service. Cloud LB shows healthy, mesh sidecars pass, but users can’t stream. Triage?](../topics/incident-response.md#504-errors-on-the-playback-service-cloud-lb-shows-healthy-mesh-sidecars-pass-but) — 1×
  <a id="504-errors-on-the-playback-service-cloud-lb-shows-healthy-mesh-sidecars-pass-but"></a>
- [504 Gateway Timeout troubleshooting](../topics/incident-response.md#504-gateway-timeout-troubleshooting) — 1×
  <a id="504-gateway-timeout-troubleshooting"></a>
- [A deployment completed successfully. All Kubernetes pods are Running. But users are getting 503 Service Unavailable. How would you troubleshoot it?](../topics/incident-response.md#a-deployment-completed-successfully-all-kubernetes-pods-are-running-but-users-ar) — 1× · tags: `Kubernetes`
  <a id="a-deployment-completed-successfully-all-kubernetes-pods-are-running-but-users-ar"></a>
- [A developer accidentally commits AWS credentials to Git. What is your complete incident response process?](../topics/incident-response.md#a-developer-accidentally-commits-aws-credentials-to-git-what-is-your-complete-in) — 1× · tags: `Git`, `AWS`
  <a id="a-developer-accidentally-commits-aws-credentials-to-git-what-is-your-complete-in"></a>
- [AI-assisted incident management](../topics/incident-response.md#ai-assisted-incident-management) — 1×
  <a id="ai-assisted-incident-management"></a>
- [Any critical incident that happened within your system related to kubernetes, And how you were able to fix it?](../topics/incident-response.md#any-critical-incident-that-happened-within-your-system-related-to-kubernetes-and) — 1× · tags: `Kubernetes`
  <a id="any-critical-incident-that-happened-within-your-system-related-to-kubernetes-and"></a>
- [etcd latency spikes and your API server slows to a crawl](../topics/incident-response.md#etcd-latency-spikes-and-your-api-server-slows-to-a-crawl) — 1×
  <a id="etcd-latency-spikes-and-your-api-server-slows-to-a-crawl"></a>
- [How do you communicate outage impact and recovery to executives who only care about revenue metrics?](../topics/incident-response.md#how-do-you-communicate-outage-impact-and-recovery-to-executives-who-only-care-ab) — 1×
  <a id="how-do-you-communicate-outage-impact-and-recovery-to-executives-who-only-care-ab"></a>
- [How do you debug a website returning 503?](../topics/incident-response.md#how-do-you-debug-a-website-returning-503) — 1×
  <a id="how-do-you-debug-a-website-returning-503"></a>
- [How do you handle on-call support and incident management?](../topics/incident-response.md#how-do-you-handle-on-call-support-and-incident-management) — 1× · tags: `On-Call`
  <a id="how-do-you-handle-on-call-support-and-incident-management"></a>
- [How do you optimize the performance of a slow application? Describe your approach to identifying bottlenecks in the frontend, backend, database, and network.](../topics/incident-response.md#how-do-you-optimize-the-performance-of-a-slow-application-describe-your-approach) — 1× · tags: `Databases`
  <a id="how-do-you-optimize-the-performance-of-a-slow-application-describe-your-approach"></a>
- [Incident Management](../topics/incident-response.md#incident-management) — 1×
  <a id="incident-management"></a>
- [Pod is Running but returning 503 - how do you debug at network, service, and ingress level?](../topics/incident-response.md#pod-is-running-but-returning-503-how-do-you-debug-at-network-service-and-ingress) — 1× · tags: `Ingress`, `Kubernetes`
  <a id="pod-is-running-but-returning-503-how-do-you-debug-at-network-service-and-ingress"></a>
- [Real incident-based thinking](../topics/incident-response.md#real-incident-based-thinking) — 1×
  <a id="real-incident-based-thinking"></a>
- [Storage latency suddenly increases. How would you investigate?](../topics/incident-response.md#storage-latency-suddenly-increases-how-would-you-investigate) — 1×
  <a id="storage-latency-suddenly-increases-how-would-you-investigate"></a>
- [The Board approves a ₹600 Crore Cloud, AI, and Platform Engineering Transformation with an expectation of 50% faster deployments and 70% reduction in MTTR within 18 months. What execution strategy would you recommend?](../topics/incident-response.md#the-board-approves-a-600-crore-cloud-ai-and-platform-engineering-transformation-) — 1×
  <a id="the-board-approves-a-600-crore-cloud-ai-and-platform-engineering-transformation-"></a>
- [Which 10 executive KPIs would you present monthly to measure platform reliability, deployment frequency, MTTR, change failure rate, cloud cost efficiency, infrastructure utilization, developer productivity, and SLA compliance?](../topics/incident-response.md#which-10-executive-kpis-would-you-present-monthly-to-measure-platform-reliabilit) — 1×
  <a id="which-10-executive-kpis-would-you-present-monthly-to-measure-platform-reliabilit"></a>
- [You introduced a sidecar-based caching layer. Suddenly, tail latency spikes. What’s your debug path?](../topics/incident-response.md#you-introduced-a-sidecar-based-caching-layer-suddenly-tail-latency-spikes-whats-) — 1×
  <a id="you-introduced-a-sidecar-based-caching-layer-suddenly-tail-latency-spikes-whats-"></a>
- [You mentioned reducing incident response time significantly—what exactly did you implement to achieve that?](../topics/incident-response.md#you-mentioned-reducing-incident-response-time-significantly-what-exactly-did-you) — 1×
  <a id="you-mentioned-reducing-incident-response-time-significantly-what-exactly-did-you"></a>
- [Your application's response time has suddenly increased. How would you determine whether the issue is related to infrastructure, networking, or the application itself?](../topics/incident-response.md#your-application-s-response-time-has-suddenly-increased-how-would-you-determine-) — 1×
  <a id="your-application-s-response-time-has-suddenly-increased-how-would-you-determine-"></a>
- [Your organization performs 250,000 deployments annually, but the change failure rate has increased to 18% and MTTR exceeds 3 hours. How would you redesign the CI/CD pipeline, release strategy, and platform engineering practices?](../topics/incident-response.md#your-organization-performs-250000-deployments-annually-but-the-change-failure-ra) — 1× · tags: `CI/CD`
  <a id="your-organization-performs-250000-deployments-annually-but-the-change-failure-ra"></a>

## Advanced

- [How do you correlate logs, metrics, and traces during a production incident?](../topics/incident-response.md#how-do-you-correlate-logs-metrics-and-traces-during-a-production-incident) — 9×
  <a id="how-do-you-correlate-logs-metrics-and-traces-during-a-production-incident"></a>
- [Explain the most challenging production incident you've handled and the architectural improvements you made afterward.](../topics/incident-response.md#explain-the-most-challenging-production-incident-you-ve-handled-and-the-architec) — 7×
  <a id="explain-the-most-challenging-production-incident-you-ve-handled-and-the-architec"></a>
- [Production is down. Users are impacted. What will you do?](../topics/incident-response.md#production-is-down-users-are-impacted-what-will-you-do) — 4×
  <a id="production-is-down-users-are-impacted-what-will-you-do"></a>
- [Describe a production incident you handled. What was the root cause, how did you resolve it, and what did you learn from the experience?](../topics/incident-response.md#describe-a-production-incident-you-handled-what-was-the-root-cause-how-did-you-r) — 2×
  <a id="describe-a-production-incident-you-handled-what-was-the-root-cause-how-did-you-r"></a>
- [Explain one challenging production incident and how you resolved it.](../topics/incident-response.md#explain-one-challenging-production-incident-and-how-you-resolved-it) — 2×
  <a id="explain-one-challenging-production-incident-and-how-you-resolved-it"></a>
- [Have you worked on incident management / production incidents?](../topics/incident-response.md#have-you-worked-on-incident-management-production-incidents) — 2×
  <a id="have-you-worked-on-incident-management-production-incidents"></a>
- [How do you perform a Root Cause Analysis (RCA) after a major production incident?](../topics/incident-response.md#how-do-you-perform-a-root-cause-analysis-rca-after-a-major-production-incident) — 2×
  <a id="how-do-you-perform-a-root-cause-analysis-rca-after-a-major-production-incident"></a>
- [Production error crashloopback of how do you troubleshoot.](../topics/incident-response.md#production-error-crashloopback-of-how-do-you-troubleshoot) — 2×
  <a id="production-error-crashloopback-of-how-do-you-troubleshoot"></a>
- [Production is down, and multiple teams join the incident bridge. How would you handle the situation?](../topics/incident-response.md#production-is-down-and-multiple-teams-join-the-incident-bridge-how-would-you-han) — 2×
  <a id="production-is-down-and-multiple-teams-join-the-incident-bridge-how-would-you-han"></a>
- [Tell us about a production incident and how you resolved it.](../topics/incident-response.md#tell-us-about-a-production-incident-and-how-you-resolved-it) — 2×
  <a id="tell-us-about-a-production-incident-and-how-you-resolved-it"></a>
- [Walk me through a production incident you personally handled — what was your role?](../topics/incident-response.md#walk-me-through-a-production-incident-you-personally-handled-what-was-your-role) — 2×
  <a id="walk-me-through-a-production-incident-you-personally-handled-what-was-your-role"></a>
- [Walk me through your worst production incident. What was it about? What did you do? What would you have done differently?](../topics/incident-response.md#walk-me-through-your-worst-production-incident-what-was-it-about-what-did-you-do) — 2×
  <a id="walk-me-through-your-worst-production-incident-what-was-it-about-what-did-you-do"></a>
- [What's one production incident that taught you more than any certification ever could?](../topics/incident-response.md#what-s-one-production-incident-that-taught-you-more-than-any-certification-ever-) — 2×
  <a id="what-s-one-production-incident-that-taught-you-more-than-any-certification-ever-"></a>
- [Which production issues have you faced, and how did you troubleshoot them?](../topics/incident-response.md#which-production-issues-have-you-faced-and-how-did-you-troubleshoot-them) — 2×
  <a id="which-production-issues-have-you-faced-and-how-did-you-troubleshoot-them"></a>
- [Why does a Canvas App work perfectly in Dev but fail in Production, and how do you troubleshoot it?](../topics/incident-response.md#why-does-a-canvas-app-work-perfectly-in-dev-but-fail-in-production-and-how-do-yo) — 2×
  <a id="why-does-a-canvas-app-work-perfectly-in-dev-but-fail-in-production-and-how-do-yo"></a>
- [Your production server suddenly goes down. What do you do first?](../topics/incident-response.md#your-production-server-suddenly-goes-down-what-do-you-do-first) — 2×
  <a id="your-production-server-suddenly-goes-down-what-do-you-do-first"></a>
- [A production issue causes $250 million in business impact, affecting 100 million customers worldwide. How would you troubleshoot the issue, perform root cause analysis, optimize application performance, and prevent future incidents?](../topics/incident-response.md#a-production-issue-causes-250-million-in-business-impact-affecting-100-million-c) — 1×
  <a id="a-production-issue-causes-250-million-in-business-impact-affecting-100-million-c"></a>
- [A trigger is causing CPU timeout exceptions in production. How would you troubleshoot it?](../topics/incident-response.md#a-trigger-is-causing-cpu-timeout-exceptions-in-production-how-would-you-troubles) — 1×
  <a id="a-trigger-is-causing-cpu-timeout-exceptions-in-production-how-would-you-troubles"></a>
- [Describe a challenging production incident you resolved and what you learned from it.](../topics/incident-response.md#describe-a-challenging-production-incident-you-resolved-and-what-you-learned-fro) — 1×
  <a id="describe-a-challenging-production-incident-you-resolved-and-what-you-learned-fro"></a>
- [Describe a production incident you handled from detection to resolution.](../topics/incident-response.md#describe-a-production-incident-you-handled-from-detection-to-resolution) — 1×
  <a id="describe-a-production-incident-you-handled-from-detection-to-resolution"></a>
- [Design a multi-region observability and incident platform that can survive the loss of two availability zones at once.](../topics/incident-response.md#design-a-multi-region-observability-and-incident-platform-that-can-survive-the-l) — 1× · tags: `Observability`, `System Design`
  <a id="design-a-multi-region-observability-and-incident-platform-that-can-survive-the-l"></a>
- [Explain a production incident you resolved and your RCA approach.](../topics/incident-response.md#explain-a-production-incident-you-resolved-and-your-rca-approach) — 1×
  <a id="explain-a-production-incident-you-resolved-and-your-rca-approach"></a>
- [Explain your production incident management process.](../topics/incident-response.md#explain-your-production-incident-management-process) — 1×
  <a id="explain-your-production-incident-management-process"></a>
- [How do you respond to a production incident?](../topics/incident-response.md#how-do-you-respond-to-a-production-incident) — 1×
  <a id="how-do-you-respond-to-a-production-incident"></a>
- [Leadership wants to implement AI-powered Platform Engineering using GitOps, AI Agents, Observability, Prometheus, Grafana, OpenTelemetry, Microsoft Fabric, and predictive incident management. How would you design the enterprise platform architecture?](../topics/incident-response.md#leadership-wants-to-implement-ai-powered-platform-engineering-using-gitops-ai-ag) — 1× · tags: `OpenTelemetry`, `Prometheus`, `Grafana`, `Observability`
  <a id="leadership-wants-to-implement-ai-powered-platform-engineering-using-gitops-ai-ag"></a>
- [Monitoring, Troubleshooting & Production Support](../topics/incident-response.md#monitoring-troubleshooting-production-support) — 1× · tags: `Monitoring`
  <a id="monitoring-troubleshooting-production-support"></a>
- [Production incident response](../topics/incident-response.md#production-incident-response) — 1×
  <a id="production-incident-response"></a>
- [Tell me about a production incident you caused.](../topics/incident-response.md#tell-me-about-a-production-incident-you-caused) — 1×
  <a id="tell-me-about-a-production-incident-you-caused"></a>
- [You are responsible for a global cloud platform supporting 500 million users, 8,000 microservices, and 99.99% availability across AWS, Azure, and Kubernetes. A production outage impacts $300 million in business transactions. How would you restore services, conduct root cause analysis, and prevent future incidents?](../topics/incident-response.md#you-are-responsible-for-a-global-cloud-platform-supporting-500-million-users-800) — 1× · tags: `Kubernetes`, `AWS`, `Azure`
  <a id="you-are-responsible-for-a-global-cloud-platform-supporting-500-million-users-800"></a>
- [You're on-call and production is down. What's the FIRST command you run?](../topics/incident-response.md#you-re-on-call-and-production-is-down-what-s-the-first-command-you-run) — 1× · tags: `On-Call`
  <a id="you-re-on-call-and-production-is-down-what-s-the-first-command-you-run"></a>
- [Your API response time increased from 200 ms to 8 seconds in production. Where do you start debugging?](../topics/incident-response.md#your-api-response-time-increased-from-200-ms-to-8-seconds-in-production-where-do) — 1×
  <a id="your-api-response-time-increased-from-200-ms-to-8-seconds-in-production-where-do"></a>
- [Your organization wants to implement end-to-end observability across microservices, Kubernetes clusters, cloud infrastructure, APIs, and databases using Prometheus, Grafana, ELK Stack, Splunk, OpenTelemetry, and Azure Monitor, aiming to reduce MTTR by 65% and improve platform reliability. How would you design the monitoring, alerting, logging, and incident management architecture?](../topics/incident-response.md#your-organization-wants-to-implement-end-to-end-observability-across-microservic) — 1× · tags: `OpenTelemetry`, `Prometheus`, `Grafana`, `Alerting`
  <a id="your-organization-wants-to-implement-end-to-end-observability-across-microservic"></a>

## By interview round

### Technical

- [After deployment, application latency suddenly doubles while CPU and memory remain normal. How would you approach the investigation?](../topics/incident-response.md#after-deployment-application-latency-suddenly-doubles-while-cpu-and-memory-remai)
- [Production is down. Users are impacted. What will you do?](../topics/incident-response.md#production-is-down-users-are-impacted-what-will-you-do)

### Unspecified

- [504 errors on the playback service. Cloud LB shows healthy, mesh sidecars pass, but users can’t stream. Triage?](../topics/incident-response.md#504-errors-on-the-playback-service-cloud-lb-shows-healthy-mesh-sidecars-pass-but)
- [504 Gateway Timeout troubleshooting](../topics/incident-response.md#504-gateway-timeout-troubleshooting)
- [A deployment completed successfully. All Kubernetes pods are Running. But users are getting 503 Service Unavailable. How would you troubleshoot it?](../topics/incident-response.md#a-deployment-completed-successfully-all-kubernetes-pods-are-running-but-users-ar) — tags: `Kubernetes`
- [A developer accidentally commits AWS credentials to Git. What is your complete incident response process?](../topics/incident-response.md#a-developer-accidentally-commits-aws-credentials-to-git-what-is-your-complete-in) — tags: `Git`, `AWS`
- [A production issue causes $250 million in business impact, affecting 100 million customers worldwide. How would you troubleshoot the issue, perform root cause analysis, optimize application performance, and prevent future incidents?](../topics/incident-response.md#a-production-issue-causes-250-million-in-business-impact-affecting-100-million-c)
- [A trigger is causing CPU timeout exceptions in production. How would you troubleshoot it?](../topics/incident-response.md#a-trigger-is-causing-cpu-timeout-exceptions-in-production-how-would-you-troubles)
- [AI-assisted incident management](../topics/incident-response.md#ai-assisted-incident-management)
- [An Amazon EKS application starts returning intermittent 502/503 errors immediately after deployment. How would you identify whether the issue is related to Kubernetes, the Load Balancer, or the application?](../topics/incident-response.md#an-amazon-eks-application-starts-returning-intermittent-502-503-errors-immediate) — tags: `EKS`, `Kubernetes`, `Load Balancing`
- [Any critical incident that happened within your system related to kubernetes, And how you were able to fix it?](../topics/incident-response.md#any-critical-incident-that-happened-within-your-system-related-to-kubernetes-and) — tags: `Kubernetes`
- [Application latency suddenly increased. How would you troubleshoot?](../topics/incident-response.md#application-latency-suddenly-increased-how-would-you-troubleshoot)
- [Describe a challenging production incident you resolved and what you learned from it.](../topics/incident-response.md#describe-a-challenging-production-incident-you-resolved-and-what-you-learned-fro)
- [Describe a production incident you handled from detection to resolution.](../topics/incident-response.md#describe-a-production-incident-you-handled-from-detection-to-resolution)
- [Describe a production incident you handled. What was the root cause, how did you resolve it, and what did you learn from the experience?](../topics/incident-response.md#describe-a-production-incident-you-handled-what-was-the-root-cause-how-did-you-r)
- [Design a multi-region observability and incident platform that can survive the loss of two availability zones at once.](../topics/incident-response.md#design-a-multi-region-observability-and-incident-platform-that-can-survive-the-l) — tags: `Observability`, `System Design`
- [etcd latency spikes and your API server slows to a crawl](../topics/incident-response.md#etcd-latency-spikes-and-your-api-server-slows-to-a-crawl)
- [Explain a production incident you resolved and your RCA approach.](../topics/incident-response.md#explain-a-production-incident-you-resolved-and-your-rca-approach)
- [Explain one challenging production incident and how you resolved it.](../topics/incident-response.md#explain-one-challenging-production-incident-and-how-you-resolved-it)
- [Explain the most challenging production incident you've handled and the architectural improvements you made afterward.](../topics/incident-response.md#explain-the-most-challenging-production-incident-you-ve-handled-and-the-architec)
- [Explain your production incident management process.](../topics/incident-response.md#explain-your-production-incident-management-process)
- [Have you worked on incident management / production incidents?](../topics/incident-response.md#have-you-worked-on-incident-management-production-incidents)
- [How do you communicate outage impact and recovery to executives who only care about revenue metrics?](../topics/incident-response.md#how-do-you-communicate-outage-impact-and-recovery-to-executives-who-only-care-ab)
- [How do you correlate logs, metrics, and traces during a production incident?](../topics/incident-response.md#how-do-you-correlate-logs-metrics-and-traces-during-a-production-incident)
- [How do you debug a website returning 503?](../topics/incident-response.md#how-do-you-debug-a-website-returning-503)
- [How do you handle on-call support and incident management?](../topics/incident-response.md#how-do-you-handle-on-call-support-and-incident-management) — tags: `On-Call`
- [How do you optimize the performance of a slow application? Describe your approach to identifying bottlenecks in the frontend, backend, database, and network.](../topics/incident-response.md#how-do-you-optimize-the-performance-of-a-slow-application-describe-your-approach) — tags: `Databases`
- [How do you perform a Root Cause Analysis (RCA) after a major production incident?](../topics/incident-response.md#how-do-you-perform-a-root-cause-analysis-rca-after-a-major-production-incident)
- [How do you respond to a production incident?](../topics/incident-response.md#how-do-you-respond-to-a-production-incident)
- [How would you troubleshoot a deployment that succeeded but users are receiving 503 errors?](../topics/incident-response.md#how-would-you-troubleshoot-a-deployment-that-succeeded-but-users-are-receiving-5)
- [How would you troubleshoot intermittent 503 errors in Kubernetes?](../topics/incident-response.md#how-would-you-troubleshoot-intermittent-503-errors-in-kubernetes) — tags: `Kubernetes`
- [Incident Management](../topics/incident-response.md#incident-management)
- [Incident Response](../topics/incident-response.md#incident-response)
- [Kubernetes pods are Running but users receive 503 errors. What will you check?](../topics/incident-response.md#kubernetes-pods-are-running-but-users-receive-503-errors-what-will-you-check) — tags: `Kubernetes`
- [Leadership wants to implement AI-powered Platform Engineering using GitOps, AI Agents, Observability, Prometheus, Grafana, OpenTelemetry, Microsoft Fabric, and predictive incident management. How would you design the enterprise platform architecture?](../topics/incident-response.md#leadership-wants-to-implement-ai-powered-platform-engineering-using-gitops-ai-ag) — tags: `OpenTelemetry`, `Prometheus`, `Grafana`, `Observability`
- [Monitoring, Troubleshooting & Production Support](../topics/incident-response.md#monitoring-troubleshooting-production-support) — tags: `Monitoring`
- [Pod is Running but returning 503 - how do you debug at network, service, and ingress level?](../topics/incident-response.md#pod-is-running-but-returning-503-how-do-you-debug-at-network-service-and-ingress) — tags: `Ingress`, `Kubernetes`
- [Production error crashloopback of how do you troubleshoot.](../topics/incident-response.md#production-error-crashloopback-of-how-do-you-troubleshoot)
- [Production incident response](../topics/incident-response.md#production-incident-response)
- [Production is down, and multiple teams join the incident bridge. How would you handle the situation?](../topics/incident-response.md#production-is-down-and-multiple-teams-join-the-incident-bridge-how-would-you-han)
- [Read real outage RCAs.](../topics/incident-response.md#read-real-outage-rcas)
- [Real incident-based thinking](../topics/incident-response.md#real-incident-based-thinking)
- [Storage latency suddenly increases. How would you investigate?](../topics/incident-response.md#storage-latency-suddenly-increases-how-would-you-investigate)
- [Tell me about a major incident or outage you handled. How did you respond, and what improvements were implemented afterward?](../topics/incident-response.md#tell-me-about-a-major-incident-or-outage-you-handled-how-did-you-respond-and-wha)
- [Tell me about a production incident you caused.](../topics/incident-response.md#tell-me-about-a-production-incident-you-caused)
- [Tell us about a production incident and how you resolved it.](../topics/incident-response.md#tell-us-about-a-production-incident-and-how-you-resolved-it)
- [The Board approves a ₹600 Crore Cloud, AI, and Platform Engineering Transformation with an expectation of 50% faster deployments and 70% reduction in MTTR within 18 months. What execution strategy would you recommend?](../topics/incident-response.md#the-board-approves-a-600-crore-cloud-ai-and-platform-engineering-transformation-)
- [Users are getting 503 errors, but all Pods are running. Where do you start?](../topics/incident-response.md#users-are-getting-503-errors-but-all-pods-are-running-where-do-you-start) — tags: `Kubernetes`
- [Users are getting 503 Service Unavailable, but all Pods are running. What would you check?](../topics/incident-response.md#users-are-getting-503-service-unavailable-but-all-pods-are-running-what-would-yo) — tags: `Kubernetes`
- [Users report a slow application, but the servers look healthy. How would you troubleshoot?](../topics/incident-response.md#users-report-a-slow-application-but-the-servers-look-healthy-how-would-you-troub)
- [Walk me through a production incident you personally handled — what was your role?](../topics/incident-response.md#walk-me-through-a-production-incident-you-personally-handled-what-was-your-role)
- [Walk me through your worst production incident. What was it about? What did you do? What would you have done differently?](../topics/incident-response.md#walk-me-through-your-worst-production-incident-what-was-it-about-what-did-you-do)
- [What's one production incident that taught you more than any certification ever could?](../topics/incident-response.md#what-s-one-production-incident-that-taught-you-more-than-any-certification-ever-)
- [Which 10 executive KPIs would you present monthly to measure platform reliability, deployment frequency, MTTR, change failure rate, cloud cost efficiency, infrastructure utilization, developer productivity, and SLA compliance?](../topics/incident-response.md#which-10-executive-kpis-would-you-present-monthly-to-measure-platform-reliabilit)
- [Which production issues have you faced, and how did you troubleshoot them?](../topics/incident-response.md#which-production-issues-have-you-faced-and-how-did-you-troubleshoot-them)
- [Why does a Canvas App work perfectly in Dev but fail in Production, and how do you troubleshoot it?](../topics/incident-response.md#why-does-a-canvas-app-work-perfectly-in-dev-but-fail-in-production-and-how-do-yo)
- [You are responsible for a global cloud platform supporting 500 million users, 8,000 microservices, and 99.99% availability across AWS, Azure, and Kubernetes. A production outage impacts $300 million in business transactions. How would you restore services, conduct root cause analysis, and prevent future incidents?](../topics/incident-response.md#you-are-responsible-for-a-global-cloud-platform-supporting-500-million-users-800) — tags: `Kubernetes`, `AWS`, `Azure`
- [You had HA. Still had 9 minutes of outage. Walk me through what your team missed.](../topics/incident-response.md#you-had-ha-still-had-9-minutes-of-outage-walk-me-through-what-your-team-missed)
- [You introduced a sidecar-based caching layer. Suddenly, tail latency spikes. What’s your debug path?](../topics/incident-response.md#you-introduced-a-sidecar-based-caching-layer-suddenly-tail-latency-spikes-whats-)
- [You mentioned reducing incident response time significantly—what exactly did you implement to achieve that?](../topics/incident-response.md#you-mentioned-reducing-incident-response-time-significantly-what-exactly-did-you)
- [You're on-call and production is down. What's the FIRST command you run?](../topics/incident-response.md#you-re-on-call-and-production-is-down-what-s-the-first-command-you-run) — tags: `On-Call`
- [Your API response time increased from 200 ms to 8 seconds in production. Where do you start debugging?](../topics/incident-response.md#your-api-response-time-increased-from-200-ms-to-8-seconds-in-production-where-do)
- [Your application latency increased by 40% overnight. How would you investigate it?](../topics/incident-response.md#your-application-latency-increased-by-40-overnight-how-would-you-investigate-it)
- [Your application latency suddenly increased after a release. Walk me through your debugging approach.](../topics/incident-response.md#your-application-latency-suddenly-increased-after-a-release-walk-me-through-your)
- [Your application's response time has suddenly increased. How would you determine whether the issue is related to infrastructure, networking, or the application itself?](../topics/incident-response.md#your-application-s-response-time-has-suddenly-increased-how-would-you-determine-)
- [Your Kubernetes cluster is healthy but requests intermittently return 503. How do you troubleshoot it?](../topics/incident-response.md#your-kubernetes-cluster-is-healthy-but-requests-intermittently-return-503-how-do) — tags: `Kubernetes`
- [Your organization performs 250,000 deployments annually, but the change failure rate has increased to 18% and MTTR exceeds 3 hours. How would you redesign the CI/CD pipeline, release strategy, and platform engineering practices?](../topics/incident-response.md#your-organization-performs-250000-deployments-annually-but-the-change-failure-ra) — tags: `CI/CD`
- [Your organization wants to implement end-to-end observability across microservices, Kubernetes clusters, cloud infrastructure, APIs, and databases using Prometheus, Grafana, ELK Stack, Splunk, OpenTelemetry, and Azure Monitor, aiming to reduce MTTR by 65% and improve platform reliability. How would you design the monitoring, alerting, logging, and incident management architecture?](../topics/incident-response.md#your-organization-wants-to-implement-end-to-end-observability-across-microservic) — tags: `OpenTelemetry`, `Prometheus`, `Grafana`, `Alerting`
- [Your production server suddenly goes down. What do you do first?](../topics/incident-response.md#your-production-server-suddenly-goes-down-what-do-you-do-first)

## Companies asking

- [Amazon](../companies/amazon.md)
- [Argyll Infotech](../companies/argyll-infotech.md)
- [DBS Bank](../companies/dbs-bank.md)
- [Elite Code Technologies](../companies/elite-code-technologies.md)
- [EY](../companies/ey.md)
- [Infosys](../companies/infosys.md)
- [PwC](../companies/pwc.md)
- [TCS](../companies/tcs.md)

## Recently added

- [Explain the most challenging production incident you've handled and the architectural improvements you made afterward.](../topics/incident-response.md#explain-the-most-challenging-production-incident-you-ve-handled-and-the-architec) — 2026-08-15
- [Your application latency suddenly increased after a release. Walk me through your debugging approach.](../topics/incident-response.md#your-application-latency-suddenly-increased-after-a-release-walk-me-through-your) — 2026-08-15
- [How would you troubleshoot a deployment that succeeded but users are receiving 503 errors?](../topics/incident-response.md#how-would-you-troubleshoot-a-deployment-that-succeeded-but-users-are-receiving-5) — 2026-08-15
- [Have you worked on incident management / production incidents?](../topics/incident-response.md#have-you-worked-on-incident-management-production-incidents) — 2026-08-13
- [How do you correlate logs, metrics, and traces during a production incident?](../topics/incident-response.md#how-do-you-correlate-logs-metrics-and-traces-during-a-production-incident) — 2026-08-12
- [Your Kubernetes cluster is healthy but requests intermittently return 503. How do you troubleshoot it?](../topics/incident-response.md#your-kubernetes-cluster-is-healthy-but-requests-intermittently-return-503-how-do) — 2026-08-12 · tags: `Kubernetes`
- [You had HA. Still had 9 minutes of outage. Walk me through what your team missed.](../topics/incident-response.md#you-had-ha-still-had-9-minutes-of-outage-walk-me-through-what-your-team-missed) — 2026-08-12
- [Production is down. Users are impacted. What will you do?](../topics/incident-response.md#production-is-down-users-are-impacted-what-will-you-do) — 2026-08-12
- [Incident Response](../topics/incident-response.md#incident-response) — 2026-08-12
- [AI-assisted incident management](../topics/incident-response.md#ai-assisted-incident-management) — 2026-08-10
- [You're on-call and production is down. What's the FIRST command you run?](../topics/incident-response.md#you-re-on-call-and-production-is-down-what-s-the-first-command-you-run) — 2026-08-10 · tags: `On-Call`
- [Explain a production incident you resolved and your RCA approach.](../topics/incident-response.md#explain-a-production-incident-you-resolved-and-your-rca-approach) — 2026-08-10
- [How would you troubleshoot intermittent 503 errors in Kubernetes?](../topics/incident-response.md#how-would-you-troubleshoot-intermittent-503-errors-in-kubernetes) — 2026-08-10 · tags: `Kubernetes`
- [Describe a production incident you handled. What was the root cause, how did you resolve it, and what did you learn from the experience?](../topics/incident-response.md#describe-a-production-incident-you-handled-what-was-the-root-cause-how-did-you-r) — 2026-08-10
- [How do you perform a Root Cause Analysis (RCA) after a major production incident?](../topics/incident-response.md#how-do-you-perform-a-root-cause-analysis-rca-after-a-major-production-incident) — 2026-08-10

## Related topics

- [SRE](./sre.md)
- [Disaster Recovery](./disaster-recovery.md)
- [High Availability](./high-availability.md)
- [Chaos Engineering](./chaos-engineering.md)
- [Capacity Planning](./capacity-planning.md)
- [On-Call](./on-call.md)
- [SLOs](./slos.md)

## All questions

| Question | Diff | Asked |
| --- | --- | ---: |
| [504 errors on the playback service. Cloud LB shows healthy, mesh sidecars pass, but users can’t stream. Triage?](../topics/incident-response.md#504-errors-on-the-playback-service-cloud-lb-shows-healthy-mesh-sidecars-pass-but) | Medium | 1 |
| [504 Gateway Timeout troubleshooting](../topics/incident-response.md#504-gateway-timeout-troubleshooting) | Medium | 1 |
| [A deployment completed successfully. All Kubernetes pods are Running. But users are getting 503 Service Unavailable. How would you troubleshoot it?](../topics/incident-response.md#a-deployment-completed-successfully-all-kubernetes-pods-are-running-but-users-ar) | Medium | 1 |
| [A developer accidentally commits AWS credentials to Git. What is your complete incident response process?](../topics/incident-response.md#a-developer-accidentally-commits-aws-credentials-to-git-what-is-your-complete-in) | Medium | 1 |
| [A production issue causes $250 million in business impact, affecting 100 million customers worldwide. How would you troubleshoot the issue, perform root cause analysis, optimize application performance, and prevent future incidents?](../topics/incident-response.md#a-production-issue-causes-250-million-in-business-impact-affecting-100-million-c) | Hard | 1 |
| [A trigger is causing CPU timeout exceptions in production. How would you troubleshoot it?](../topics/incident-response.md#a-trigger-is-causing-cpu-timeout-exceptions-in-production-how-would-you-troubles) | Hard | 1 |
| [After deployment, application latency suddenly doubles while CPU and memory remain normal. How would you approach the investigation?](../topics/incident-response.md#after-deployment-application-latency-suddenly-doubles-while-cpu-and-memory-remai) | Medium | 5 |
| [AI-assisted incident management](../topics/incident-response.md#ai-assisted-incident-management) | Medium | 1 |
| [An Amazon EKS application starts returning intermittent 502/503 errors immediately after deployment. How would you identify whether the issue is related to Kubernetes, the Load Balancer, or the application?](../topics/incident-response.md#an-amazon-eks-application-starts-returning-intermittent-502-503-errors-immediate) | Medium | 2 |
| [Any critical incident that happened within your system related to kubernetes, And how you were able to fix it?](../topics/incident-response.md#any-critical-incident-that-happened-within-your-system-related-to-kubernetes-and) | Medium | 1 |
| [Application latency suddenly increased. How would you troubleshoot?](../topics/incident-response.md#application-latency-suddenly-increased-how-would-you-troubleshoot) | Medium | 2 |
| [Describe a challenging production incident you resolved and what you learned from it.](../topics/incident-response.md#describe-a-challenging-production-incident-you-resolved-and-what-you-learned-fro) | Hard | 1 |
| [Describe a production incident you handled from detection to resolution.](../topics/incident-response.md#describe-a-production-incident-you-handled-from-detection-to-resolution) | Hard | 1 |
| [Describe a production incident you handled. What was the root cause, how did you resolve it, and what did you learn from the experience?](../topics/incident-response.md#describe-a-production-incident-you-handled-what-was-the-root-cause-how-did-you-r) | Hard | 2 |
| [Design a multi-region observability and incident platform that can survive the loss of two availability zones at once.](../topics/incident-response.md#design-a-multi-region-observability-and-incident-platform-that-can-survive-the-l) | Hard | 1 |
| [etcd latency spikes and your API server slows to a crawl](../topics/incident-response.md#etcd-latency-spikes-and-your-api-server-slows-to-a-crawl) | Medium | 1 |
| [Explain a production incident you resolved and your RCA approach.](../topics/incident-response.md#explain-a-production-incident-you-resolved-and-your-rca-approach) | Hard | 1 |
| [Explain one challenging production incident and how you resolved it.](../topics/incident-response.md#explain-one-challenging-production-incident-and-how-you-resolved-it) | Hard | 2 |
| [Explain the most challenging production incident you've handled and the architectural improvements you made afterward.](../topics/incident-response.md#explain-the-most-challenging-production-incident-you-ve-handled-and-the-architec) | Hard | 7 |
| [Explain your production incident management process.](../topics/incident-response.md#explain-your-production-incident-management-process) | Hard | 1 |
| [Have you worked on incident management / production incidents?](../topics/incident-response.md#have-you-worked-on-incident-management-production-incidents) | Hard | 2 |
| [How do you communicate outage impact and recovery to executives who only care about revenue metrics?](../topics/incident-response.md#how-do-you-communicate-outage-impact-and-recovery-to-executives-who-only-care-ab) | Medium | 1 |
| [How do you correlate logs, metrics, and traces during a production incident?](../topics/incident-response.md#how-do-you-correlate-logs-metrics-and-traces-during-a-production-incident) | Hard | 9 |
| [How do you debug a website returning 503?](../topics/incident-response.md#how-do-you-debug-a-website-returning-503) | Medium | 1 |
| [How do you handle on-call support and incident management?](../topics/incident-response.md#how-do-you-handle-on-call-support-and-incident-management) | Medium | 1 |
| [How do you optimize the performance of a slow application? Describe your approach to identifying bottlenecks in the frontend, backend, database, and network.](../topics/incident-response.md#how-do-you-optimize-the-performance-of-a-slow-application-describe-your-approach) | Medium | 1 |
| [How do you perform a Root Cause Analysis (RCA) after a major production incident?](../topics/incident-response.md#how-do-you-perform-a-root-cause-analysis-rca-after-a-major-production-incident) | Hard | 2 |
| [How do you respond to a production incident?](../topics/incident-response.md#how-do-you-respond-to-a-production-incident) | Hard | 1 |
| [How would you troubleshoot a deployment that succeeded but users are receiving 503 errors?](../topics/incident-response.md#how-would-you-troubleshoot-a-deployment-that-succeeded-but-users-are-receiving-5) | Medium | 4 |
| [How would you troubleshoot intermittent 503 errors in Kubernetes?](../topics/incident-response.md#how-would-you-troubleshoot-intermittent-503-errors-in-kubernetes) | Medium | 2 |
| [Incident Management](../topics/incident-response.md#incident-management) | Medium | 1 |
| [Incident Response](../topics/incident-response.md#incident-response) | Medium | 2 |
| [Kubernetes pods are Running but users receive 503 errors. What will you check?](../topics/incident-response.md#kubernetes-pods-are-running-but-users-receive-503-errors-what-will-you-check) | Medium | 2 |
| [Leadership wants to implement AI-powered Platform Engineering using GitOps, AI Agents, Observability, Prometheus, Grafana, OpenTelemetry, Microsoft Fabric, and predictive incident management. How would you design the enterprise platform architecture?](../topics/incident-response.md#leadership-wants-to-implement-ai-powered-platform-engineering-using-gitops-ai-ag) | Hard | 1 |
| [Monitoring, Troubleshooting & Production Support](../topics/incident-response.md#monitoring-troubleshooting-production-support) | Hard | 1 |
| [Pod is Running but returning 503 - how do you debug at network, service, and ingress level?](../topics/incident-response.md#pod-is-running-but-returning-503-how-do-you-debug-at-network-service-and-ingress) | Medium | 1 |
| [Production error crashloopback of how do you troubleshoot.](../topics/incident-response.md#production-error-crashloopback-of-how-do-you-troubleshoot) | Hard | 2 |
| [Production incident response](../topics/incident-response.md#production-incident-response) | Hard | 1 |
| [Production is down, and multiple teams join the incident bridge. How would you handle the situation?](../topics/incident-response.md#production-is-down-and-multiple-teams-join-the-incident-bridge-how-would-you-han) | Hard | 2 |
| [Production is down. Users are impacted. What will you do?](../topics/incident-response.md#production-is-down-users-are-impacted-what-will-you-do) | Hard | 4 |
| [Read real outage RCAs.](../topics/incident-response.md#read-real-outage-rcas) | Medium | 2 |
| [Real incident-based thinking](../topics/incident-response.md#real-incident-based-thinking) | Medium | 1 |
| [Storage latency suddenly increases. How would you investigate?](../topics/incident-response.md#storage-latency-suddenly-increases-how-would-you-investigate) | Medium | 1 |
| [Tell me about a major incident or outage you handled. How did you respond, and what improvements were implemented afterward?](../topics/incident-response.md#tell-me-about-a-major-incident-or-outage-you-handled-how-did-you-respond-and-wha) | Medium | 3 |
| [Tell me about a production incident you caused.](../topics/incident-response.md#tell-me-about-a-production-incident-you-caused) | Hard | 1 |
| [Tell us about a production incident and how you resolved it.](../topics/incident-response.md#tell-us-about-a-production-incident-and-how-you-resolved-it) | Hard | 2 |
| [The Board approves a ₹600 Crore Cloud, AI, and Platform Engineering Transformation with an expectation of 50% faster deployments and 70% reduction in MTTR within 18 months. What execution strategy would you recommend?](../topics/incident-response.md#the-board-approves-a-600-crore-cloud-ai-and-platform-engineering-transformation-) | Medium | 1 |
| [Users are getting 503 errors, but all Pods are running. Where do you start?](../topics/incident-response.md#users-are-getting-503-errors-but-all-pods-are-running-where-do-you-start) | Medium | 2 |
| [Users are getting 503 Service Unavailable, but all Pods are running. What would you check?](../topics/incident-response.md#users-are-getting-503-service-unavailable-but-all-pods-are-running-what-would-yo) | Medium | 2 |
| [Users report a slow application, but the servers look healthy. How would you troubleshoot?](../topics/incident-response.md#users-report-a-slow-application-but-the-servers-look-healthy-how-would-you-troub) | Medium | 2 |
| [Walk me through a production incident you personally handled — what was your role?](../topics/incident-response.md#walk-me-through-a-production-incident-you-personally-handled-what-was-your-role) | Hard | 2 |
| [Walk me through your worst production incident. What was it about? What did you do? What would you have done differently?](../topics/incident-response.md#walk-me-through-your-worst-production-incident-what-was-it-about-what-did-you-do) | Hard | 2 |
| [What's one production incident that taught you more than any certification ever could?](../topics/incident-response.md#what-s-one-production-incident-that-taught-you-more-than-any-certification-ever-) | Hard | 2 |
| [Which 10 executive KPIs would you present monthly to measure platform reliability, deployment frequency, MTTR, change failure rate, cloud cost efficiency, infrastructure utilization, developer productivity, and SLA compliance?](../topics/incident-response.md#which-10-executive-kpis-would-you-present-monthly-to-measure-platform-reliabilit) | Medium | 1 |
| [Which production issues have you faced, and how did you troubleshoot them?](../topics/incident-response.md#which-production-issues-have-you-faced-and-how-did-you-troubleshoot-them) | Hard | 2 |
| [Why does a Canvas App work perfectly in Dev but fail in Production, and how do you troubleshoot it?](../topics/incident-response.md#why-does-a-canvas-app-work-perfectly-in-dev-but-fail-in-production-and-how-do-yo) | Hard | 2 |
| [You are responsible for a global cloud platform supporting 500 million users, 8,000 microservices, and 99.99% availability across AWS, Azure, and Kubernetes. A production outage impacts $300 million in business transactions. How would you restore services, conduct root cause analysis, and prevent future incidents?](../topics/incident-response.md#you-are-responsible-for-a-global-cloud-platform-supporting-500-million-users-800) | Hard | 1 |
| [You had HA. Still had 9 minutes of outage. Walk me through what your team missed.](../topics/incident-response.md#you-had-ha-still-had-9-minutes-of-outage-walk-me-through-what-your-team-missed) | Medium | 2 |
| [You introduced a sidecar-based caching layer. Suddenly, tail latency spikes. What’s your debug path?](../topics/incident-response.md#you-introduced-a-sidecar-based-caching-layer-suddenly-tail-latency-spikes-whats-) | Medium | 1 |
| [You mentioned reducing incident response time significantly—what exactly did you implement to achieve that?](../topics/incident-response.md#you-mentioned-reducing-incident-response-time-significantly-what-exactly-did-you) | Medium | 1 |
| [You're on-call and production is down. What's the FIRST command you run?](../topics/incident-response.md#you-re-on-call-and-production-is-down-what-s-the-first-command-you-run) | Hard | 1 |
| [Your API response time increased from 200 ms to 8 seconds in production. Where do you start debugging?](../topics/incident-response.md#your-api-response-time-increased-from-200-ms-to-8-seconds-in-production-where-do) | Hard | 1 |
| [Your application latency increased by 40% overnight. How would you investigate it?](../topics/incident-response.md#your-application-latency-increased-by-40-overnight-how-would-you-investigate-it) | Medium | 2 |
| [Your application latency suddenly increased after a release. Walk me through your debugging approach.](../topics/incident-response.md#your-application-latency-suddenly-increased-after-a-release-walk-me-through-your) | Medium | 2 |
| [Your application's response time has suddenly increased. How would you determine whether the issue is related to infrastructure, networking, or the application itself?](../topics/incident-response.md#your-application-s-response-time-has-suddenly-increased-how-would-you-determine-) | Medium | 1 |
| [Your Kubernetes cluster is healthy but requests intermittently return 503. How do you troubleshoot it?](../topics/incident-response.md#your-kubernetes-cluster-is-healthy-but-requests-intermittently-return-503-how-do) | Medium | 7 |
| [Your organization performs 250,000 deployments annually, but the change failure rate has increased to 18% and MTTR exceeds 3 hours. How would you redesign the CI/CD pipeline, release strategy, and platform engineering practices?](../topics/incident-response.md#your-organization-performs-250000-deployments-annually-but-the-change-failure-ra) | Medium | 1 |
| [Your organization wants to implement end-to-end observability across microservices, Kubernetes clusters, cloud infrastructure, APIs, and databases using Prometheus, Grafana, ELK Stack, Splunk, OpenTelemetry, and Azure Monitor, aiming to reduce MTTR by 65% and improve platform reliability. How would you design the monitoring, alerting, logging, and incident management architecture?](../topics/incident-response.md#your-organization-wants-to-implement-end-to-end-observability-across-microservic) | Hard | 1 |
| [Your production server suddenly goes down. What do you do first?](../topics/incident-response.md#your-production-server-suddenly-goes-down-what-do-you-do-first) | Hard | 2 |

## Learning resources

- Practice [most asked overall](../study-guides/most-asked.md)
- Filter by [difficulty](../study-guides/by-difficulty.md)
- Browse [companies](../companies/README.md)

[← All topics](./README.md) · [Home](../README.md)
