# Deployment Strategies

[Home](../README.md) > [Topics](./README.md) > **Deployment Strategies**

**56** real interview questions. Study this page end-to-end — open a detail page only when an answer is enriched.

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
| Questions | 56 |
| Easy / Medium / Hard | 5 / 28 / 23 |
| Companies | 8 |

## Most asked

- [Design a rollback strategy that works even if the deployment stage fails.](../topics/deployment-strategies.md#design-a-rollback-strategy-that-works-even-if-the-deployment-stage-fails) — **7×** · Hard
  <a id="design-a-rollback-strategy-that-works-even-if-the-deployment-stage-fails"></a>
- [A deployment succeeds, but latency increases from 80 ms to 2 seconds. Walk me through your debugging approach.](../topics/deployment-strategies.md#a-deployment-succeeds-but-latency-increases-from-80-ms-to-2-seconds-walk-me-thro) — **5×** · Medium
  <a id="a-deployment-succeeds-but-latency-increases-from-80-ms-to-2-seconds-walk-me-thro"></a>
- [What is Blue-Green Deployment?](../topics/deployment-strategies.md#what-is-blue-green-deployment) — **5×** · Easy · tags: `Blue-Green`
  <a id="what-is-blue-green-deployment"></a>
- [How do you ensure zero-downtime deployments in production?](../topics/deployment-strategies.md#how-do-you-ensure-zero-downtime-deployments-in-production) — **4×** · Hard
  <a id="how-do-you-ensure-zero-downtime-deployments-in-production"></a>
- [Blue-Green & Canary deployments](../topics/deployment-strategies.md#blue-green-canary-deployments) — **3×** · Medium · tags: `Blue-Green`, `Canary`
  <a id="blue-green-canary-deployments"></a>
- [Difference between blue-green and canary and roll-out deployments ? which is more expensive?](../topics/deployment-strategies.md#difference-between-blue-green-and-canary-and-roll-out-deployments-which-is-more-) — **3×** · Medium · tags: `Blue-Green`, `Canary`
  <a id="difference-between-blue-green-and-canary-and-roll-out-deployments-which-is-more-"></a>
- [Explain Blue-Green Deployment](../topics/deployment-strategies.md#explain-blue-green-deployment) — **3×** · Medium · tags: `Blue-Green`
  <a id="explain-blue-green-deployment"></a>
- [Explain the difference between Rolling, Blue-Green, and Canary deployments.](../topics/deployment-strategies.md#explain-the-difference-between-rolling-blue-green-and-canary-deployments) — **3×** · Easy · tags: `Blue-Green`, `Canary`
  <a id="explain-the-difference-between-rolling-blue-green-and-canary-deployments"></a>
- [How do you implement rollback if deployment fails?](../topics/deployment-strategies.md#how-do-you-implement-rollback-if-deployment-fails) — **3×** · Medium
  <a id="how-do-you-implement-rollback-if-deployment-fails"></a>
- [How do you implement zero-downtime deployments?](../topics/deployment-strategies.md#how-do-you-implement-zero-downtime-deployments) — **3×** · Medium
  <a id="how-do-you-implement-zero-downtime-deployments"></a>
- [A deployment failed in Production. How would you troubleshoot?](../topics/deployment-strategies.md#a-deployment-failed-in-production-how-would-you-troubleshoot) — **2×** · Hard · tags: `Incident Response`
  <a id="a-deployment-failed-in-production-how-would-you-troubleshoot"></a>
- [A Jenkins pipeline completed successfully, but the latest changes are not visible in production. What components would you verify before concluding the deployment failed?](../topics/deployment-strategies.md#a-jenkins-pipeline-completed-successfully-but-the-latest-changes-are-not-visible) — **2×** · Hard · tags: `Jenkins`, `CI/CD`
  <a id="a-jenkins-pipeline-completed-successfully-but-the-latest-changes-are-not-visible"></a>
- [A new deployment caused production issues. How would you safely roll back to the previous version?](../topics/deployment-strategies.md#a-new-deployment-caused-production-issues-how-would-you-safely-roll-back-to-the-) — **2×** · Hard
  <a id="a-new-deployment-caused-production-issues-how-would-you-safely-roll-back-to-the-"></a>
- [Explain your rollback strategy during production deployments.](../topics/deployment-strategies.md#explain-your-rollback-strategy-during-production-deployments) — **2×** · Hard
  <a id="explain-your-rollback-strategy-during-production-deployments"></a>
- [For a production e-commerce application, which deployment strategy would you recommend—Rolling Update, Blue-Green, or Canary Deployment? What factors would influence your decision?](../topics/deployment-strategies.md#for-a-production-e-commerce-application-which-deployment-strategy-would-you-reco) — **2×** · Hard · tags: `Blue-Green`, `Canary`
  <a id="for-a-production-e-commerce-application-which-deployment-strategy-would-you-reco"></a>
- [Helm rollback worked. App still broken. Logs silent. What now?](../topics/deployment-strategies.md#helm-rollback-worked-app-still-broken-logs-silent-what-now) — **2×** · Medium · tags: `Helm`
  <a id="helm-rollback-worked-app-still-broken-logs-silent-what-now"></a>
- [How do you design a rollback strategy if the deployment stage itself fails?](../topics/deployment-strategies.md#how-do-you-design-a-rollback-strategy-if-the-deployment-stage-itself-fails) — **2×** · Hard
  <a id="how-do-you-design-a-rollback-strategy-if-the-deployment-stage-itself-fails"></a>
- [How do you handle a failed deployment in production?](../topics/deployment-strategies.md#how-do-you-handle-a-failed-deployment-in-production) — **2×** · Hard
  <a id="how-do-you-handle-a-failed-deployment-in-production"></a>
- [How do you perform a rolling update?](../topics/deployment-strategies.md#how-do-you-perform-a-rolling-update) — **2×** · Medium
  <a id="how-do-you-perform-a-rolling-update"></a>
- [How do you roll back a failed Kubernetes deployment?](../topics/deployment-strategies.md#how-do-you-roll-back-a-failed-kubernetes-deployment) — **2×** · Medium · tags: `Kubernetes`
  <a id="how-do-you-roll-back-a-failed-kubernetes-deployment"></a>
- [How would you design a CI/CD pipeline with an automatic rollback strategy?](../topics/deployment-strategies.md#how-would-you-design-a-ci-cd-pipeline-with-an-automatic-rollback-strategy) — **2×** · Hard · tags: `CI/CD`
  <a id="how-would-you-design-a-ci-cd-pipeline-with-an-automatic-rollback-strategy"></a>
- [Production deployment failed. What steps would you take?](../topics/deployment-strategies.md#production-deployment-failed-what-steps-would-you-take) — **2×** · Hard
  <a id="production-deployment-failed-what-steps-would-you-take"></a>
- [What is a rolling rollback?](../topics/deployment-strategies.md#what-is-a-rolling-rollback) — **2×** · Easy
  <a id="what-is-a-rolling-rollback"></a>
- [What rollback strategies do you follow?](../topics/deployment-strategies.md#what-rollback-strategies-do-you-follow) — **2×** · Medium
  <a id="what-rollback-strategies-do-you-follow"></a>
- [A critical production deployment fails during a global release, affecting 80 million users and resulting in an estimated ₹350 Crore business impact. How would you investigate the root cause, coordinate incident response, perform rollback or recovery, and implement preventive controls to eliminate similar failures in future releases?](../topics/deployment-strategies.md#a-critical-production-deployment-fails-during-a-global-release-affecting-80-mill) — **1×** · Hard · tags: `Incident Response`
  <a id="a-critical-production-deployment-fails-during-a-global-release-affecting-80-mill"></a>

## Beginner

- [What is Blue-Green Deployment?](../topics/deployment-strategies.md#what-is-blue-green-deployment) — 5× · tags: `Blue-Green`
  <a id="what-is-blue-green-deployment"></a>
- [Explain the difference between Rolling, Blue-Green, and Canary deployments.](../topics/deployment-strategies.md#explain-the-difference-between-rolling-blue-green-and-canary-deployments) — 3× · tags: `Blue-Green`, `Canary`
  <a id="explain-the-difference-between-rolling-blue-green-and-canary-deployments"></a>
- [What is a rolling rollback?](../topics/deployment-strategies.md#what-is-a-rolling-rollback) — 2×
  <a id="what-is-a-rolling-rollback"></a>
- [What is Canary Deployment?](../topics/deployment-strategies.md#what-is-canary-deployment) — 1× · tags: `Canary`
  <a id="what-is-canary-deployment"></a>
- [What is the difference between blue-green deployment and canary deployment?](../topics/deployment-strategies.md#what-is-the-difference-between-blue-green-deployment-and-canary-deployment) — 1× · tags: `Blue-Green`, `Canary`
  <a id="what-is-the-difference-between-blue-green-deployment-and-canary-deployment"></a>

## Intermediate

- [A deployment succeeds, but latency increases from 80 ms to 2 seconds. Walk me through your debugging approach.](../topics/deployment-strategies.md#a-deployment-succeeds-but-latency-increases-from-80-ms-to-2-seconds-walk-me-thro) — 5×
  <a id="a-deployment-succeeds-but-latency-increases-from-80-ms-to-2-seconds-walk-me-thro"></a>
- [Blue-Green & Canary deployments](../topics/deployment-strategies.md#blue-green-canary-deployments) — 3× · tags: `Blue-Green`, `Canary`
  <a id="blue-green-canary-deployments"></a>
- [Difference between blue-green and canary and roll-out deployments ? which is more expensive?](../topics/deployment-strategies.md#difference-between-blue-green-and-canary-and-roll-out-deployments-which-is-more-) — 3× · tags: `Blue-Green`, `Canary`
  <a id="difference-between-blue-green-and-canary-and-roll-out-deployments-which-is-more-"></a>
- [Explain Blue-Green Deployment](../topics/deployment-strategies.md#explain-blue-green-deployment) — 3× · tags: `Blue-Green`
  <a id="explain-blue-green-deployment"></a>
- [How do you implement rollback if deployment fails?](../topics/deployment-strategies.md#how-do-you-implement-rollback-if-deployment-fails) — 3×
  <a id="how-do-you-implement-rollback-if-deployment-fails"></a>
- [How do you implement zero-downtime deployments?](../topics/deployment-strategies.md#how-do-you-implement-zero-downtime-deployments) — 3×
  <a id="how-do-you-implement-zero-downtime-deployments"></a>
- [Helm rollback worked. App still broken. Logs silent. What now?](../topics/deployment-strategies.md#helm-rollback-worked-app-still-broken-logs-silent-what-now) — 2× · tags: `Helm`
  <a id="helm-rollback-worked-app-still-broken-logs-silent-what-now"></a>
- [How do you perform a rolling update?](../topics/deployment-strategies.md#how-do-you-perform-a-rolling-update) — 2×
  <a id="how-do-you-perform-a-rolling-update"></a>
- [How do you roll back a failed Kubernetes deployment?](../topics/deployment-strategies.md#how-do-you-roll-back-a-failed-kubernetes-deployment) — 2× · tags: `Kubernetes`
  <a id="how-do-you-roll-back-a-failed-kubernetes-deployment"></a>
- [What rollback strategies do you follow?](../topics/deployment-strategies.md#what-rollback-strategies-do-you-follow) — 2×
  <a id="what-rollback-strategies-do-you-follow"></a>
- [A deployment succeeds, but the application becomes unavailable immediately afterward. What would be your step-by-step troubleshooting process?](../topics/deployment-strategies.md#a-deployment-succeeds-but-the-application-becomes-unavailable-immediately-afterw) — 1×
  <a id="a-deployment-succeeds-but-the-application-becomes-unavailable-immediately-afterw"></a>
- [A failed deployment brings a mission-critical platform down globally. What are your first 30-minute actions?](../topics/deployment-strategies.md#a-failed-deployment-brings-a-mission-critical-platform-down-globally-what-are-yo) — 1×
  <a id="a-failed-deployment-brings-a-mission-critical-platform-down-globally-what-are-yo"></a>
- [CI/CD, rollback and security best practices](../topics/deployment-strategies.md#ci-cd-rollback-and-security-best-practices) — 1× · tags: `CI/CD`
  <a id="ci-cd-rollback-and-security-best-practices"></a>
- [Describe your strategy for zero-downtime data migrations between entirely different storage backends.](../topics/deployment-strategies.md#describe-your-strategy-for-zero-downtime-data-migrations-between-entirely-differ) — 1×
  <a id="describe-your-strategy-for-zero-downtime-data-migrations-between-entirely-differ"></a>
- [During a Canary deployment, how would you verify that the 10% deployment is healthy? What metrics would you monitor before proceeding to 100%?](../topics/deployment-strategies.md#during-a-canary-deployment-how-would-you-verify-that-the-10-deployment-is-health) — 1× · tags: `Canary`
  <a id="during-a-canary-deployment-how-would-you-verify-that-the-10-deployment-is-health"></a>
- [Explain Blue-Green Deployment and Canary Deployment. How have you implemented them?](../topics/deployment-strategies.md#explain-blue-green-deployment-and-canary-deployment-how-have-you-implemented-the) — 1× · tags: `Blue-Green`, `Canary`
  <a id="explain-blue-green-deployment-and-canary-deployment-how-have-you-implemented-the"></a>
- [How do you handle rollback if a deployment fails?](../topics/deployment-strategies.md#how-do-you-handle-rollback-if-a-deployment-fails) — 1×
  <a id="how-do-you-handle-rollback-if-a-deployment-fails"></a>
- [How do you implement blue-green and canary deployments?](../topics/deployment-strategies.md#how-do-you-implement-blue-green-and-canary-deployments) — 1× · tags: `Blue-Green`, `Canary`
  <a id="how-do-you-implement-blue-green-and-canary-deployments"></a>
- [How do you implement rollback strategy in Jenkins pipeline?](../topics/deployment-strategies.md#how-do-you-implement-rollback-strategy-in-jenkins-pipeline) — 1× · tags: `Jenkins`, `CI/CD`
  <a id="how-do-you-implement-rollback-strategy-in-jenkins-pipeline"></a>
- [How do you roll back a failed deployment in Jenkins?](../topics/deployment-strategies.md#how-do-you-roll-back-a-failed-deployment-in-jenkins) — 1× · tags: `Jenkins`
  <a id="how-do-you-roll-back-a-failed-deployment-in-jenkins"></a>
- [How do you safely roll back infrastructure changes after a failed deployment?](../topics/deployment-strategies.md#how-do-you-safely-roll-back-infrastructure-changes-after-a-failed-deployment) — 1×
  <a id="how-do-you-safely-roll-back-infrastructure-changes-after-a-failed-deployment"></a>
- [How do you troubleshoot a failed deployment?](../topics/deployment-strategies.md#how-do-you-troubleshoot-a-failed-deployment) — 1×
  <a id="how-do-you-troubleshoot-a-failed-deployment"></a>
- [Rollback strategies](../topics/deployment-strategies.md#rollback-strategies) — 1×
  <a id="rollback-strategies"></a>
- [Tell me about a failed deployment you handled. How did you troubleshoot the issue, restore services, and prevent similar failures in the future?](../topics/deployment-strategies.md#tell-me-about-a-failed-deployment-you-handled-how-did-you-troubleshoot-the-issue) — 1×
  <a id="tell-me-about-a-failed-deployment-you-handled-how-did-you-troubleshoot-the-issue"></a>
- [What CI/CD practices have you implemented? Explain your experience with automated testing, deployment pipelines, rollback strategies, and monitoring.](../topics/deployment-strategies.md#what-ci-cd-practices-have-you-implemented-explain-your-experience-with-automated) — 1× · tags: `Monitoring`, `CI/CD`
  <a id="what-ci-cd-practices-have-you-implemented-explain-your-experience-with-automated"></a>
- [You must migrate a business-critical platform across clouds with zero downtime. What is your strategy?](../topics/deployment-strategies.md#you-must-migrate-a-business-critical-platform-across-clouds-with-zero-downtime-w) — 1×
  <a id="you-must-migrate-a-business-critical-platform-across-clouds-with-zero-downtime-w"></a>
- [Your CI/CD deployment failed. The rollback pipeline also failed because it depends on the deployment stage. How would you redesign the pipeline to avoid this situation?](../topics/deployment-strategies.md#your-ci-cd-deployment-failed-the-rollback-pipeline-also-failed-because-it-depend) — 1× · tags: `CI/CD`
  <a id="your-ci-cd-deployment-failed-the-rollback-pipeline-also-failed-because-it-depend"></a>
- [Zero-downtime deployments](../topics/deployment-strategies.md#zero-downtime-deployments) — 1×
  <a id="zero-downtime-deployments"></a>

## Advanced

- [Design a rollback strategy that works even if the deployment stage fails.](../topics/deployment-strategies.md#design-a-rollback-strategy-that-works-even-if-the-deployment-stage-fails) — 7×
  <a id="design-a-rollback-strategy-that-works-even-if-the-deployment-stage-fails"></a>
- [How do you ensure zero-downtime deployments in production?](../topics/deployment-strategies.md#how-do-you-ensure-zero-downtime-deployments-in-production) — 4×
  <a id="how-do-you-ensure-zero-downtime-deployments-in-production"></a>
- [A deployment failed in Production. How would you troubleshoot?](../topics/deployment-strategies.md#a-deployment-failed-in-production-how-would-you-troubleshoot) — 2× · tags: `Incident Response`
  <a id="a-deployment-failed-in-production-how-would-you-troubleshoot"></a>
- [A Jenkins pipeline completed successfully, but the latest changes are not visible in production. What components would you verify before concluding the deployment failed?](../topics/deployment-strategies.md#a-jenkins-pipeline-completed-successfully-but-the-latest-changes-are-not-visible) — 2× · tags: `Jenkins`, `CI/CD`
  <a id="a-jenkins-pipeline-completed-successfully-but-the-latest-changes-are-not-visible"></a>
- [A new deployment caused production issues. How would you safely roll back to the previous version?](../topics/deployment-strategies.md#a-new-deployment-caused-production-issues-how-would-you-safely-roll-back-to-the-) — 2×
  <a id="a-new-deployment-caused-production-issues-how-would-you-safely-roll-back-to-the-"></a>
- [Explain your rollback strategy during production deployments.](../topics/deployment-strategies.md#explain-your-rollback-strategy-during-production-deployments) — 2×
  <a id="explain-your-rollback-strategy-during-production-deployments"></a>
- [For a production e-commerce application, which deployment strategy would you recommend—Rolling Update, Blue-Green, or Canary Deployment? What factors would influence your decision?](../topics/deployment-strategies.md#for-a-production-e-commerce-application-which-deployment-strategy-would-you-reco) — 2× · tags: `Blue-Green`, `Canary`
  <a id="for-a-production-e-commerce-application-which-deployment-strategy-would-you-reco"></a>
- [How do you design a rollback strategy if the deployment stage itself fails?](../topics/deployment-strategies.md#how-do-you-design-a-rollback-strategy-if-the-deployment-stage-itself-fails) — 2×
  <a id="how-do-you-design-a-rollback-strategy-if-the-deployment-stage-itself-fails"></a>
- [How do you handle a failed deployment in production?](../topics/deployment-strategies.md#how-do-you-handle-a-failed-deployment-in-production) — 2×
  <a id="how-do-you-handle-a-failed-deployment-in-production"></a>
- [How would you design a CI/CD pipeline with an automatic rollback strategy?](../topics/deployment-strategies.md#how-would-you-design-a-ci-cd-pipeline-with-an-automatic-rollback-strategy) — 2× · tags: `CI/CD`
  <a id="how-would-you-design-a-ci-cd-pipeline-with-an-automatic-rollback-strategy"></a>
- [Production deployment failed. What steps would you take?](../topics/deployment-strategies.md#production-deployment-failed-what-steps-would-you-take) — 2×
  <a id="production-deployment-failed-what-steps-would-you-take"></a>
- [A critical production deployment fails during a global release, affecting 80 million users and resulting in an estimated ₹350 Crore business impact. How would you investigate the root cause, coordinate incident response, perform rollback or recovery, and implement preventive controls to eliminate similar failures in future releases?](../topics/deployment-strategies.md#a-critical-production-deployment-fails-during-a-global-release-affecting-80-mill) — 1× · tags: `Incident Response`
  <a id="a-critical-production-deployment-fails-during-a-global-release-affecting-80-mill"></a>
- [A failed production deployment across 1,200 microservices impacts 35 million customers within 30 minutes. What would be your incident response, rollback, and recovery strategy?](../topics/deployment-strategies.md#a-failed-production-deployment-across-1200-microservices-impacts-35-million-cust) — 1× · tags: `Incident Response`
  <a id="a-failed-production-deployment-across-1200-microservices-impacts-35-million-cust"></a>
- [A production deployment failed, and users are impacted. What would your rollback strategy look like?](../topics/deployment-strategies.md#a-production-deployment-failed-and-users-are-impacted-what-would-your-rollback-s) — 1× · tags: `Incident Response`
  <a id="a-production-deployment-failed-and-users-are-impacted-what-would-your-rollback-s"></a>
- [A production deployment failed. What steps would you take to troubleshoot and recover?](../topics/deployment-strategies.md#a-production-deployment-failed-what-steps-would-you-take-to-troubleshoot-and-rec) — 1× · tags: `Incident Response`
  <a id="a-production-deployment-failed-what-steps-would-you-take-to-troubleshoot-and-rec"></a>
- [CI/CD pipeline failures & production rollback](../topics/deployment-strategies.md#ci-cd-pipeline-failures-production-rollback) — 1× · tags: `CI/CD`
  <a id="ci-cd-pipeline-failures-production-rollback"></a>
- [How do you design a rollback strategy for a failed production deployment?](../topics/deployment-strategies.md#how-do-you-design-a-rollback-strategy-for-a-failed-production-deployment) — 1×
  <a id="how-do-you-design-a-rollback-strategy-for-a-failed-production-deployment"></a>
- [How would you implement a reliable rollback strategy?](../topics/deployment-strategies.md#how-would-you-implement-a-reliable-rollback-strategy) — 1×
  <a id="how-would-you-implement-a-reliable-rollback-strategy"></a>
- [How would you implement a zero-downtime deployment?](../topics/deployment-strategies.md#how-would-you-implement-a-zero-downtime-deployment) — 1×
  <a id="how-would-you-implement-a-zero-downtime-deployment"></a>
- [Rollback techniques in production](../topics/deployment-strategies.md#rollback-techniques-in-production) — 1×
  <a id="rollback-techniques-in-production"></a>
- [Suppose a production deployment fails and Jenkins catches it. How do you perform rollback and what responsibilities did you handle?](../topics/deployment-strategies.md#suppose-a-production-deployment-fails-and-jenkins-catches-it-how-do-you-perform-) — 1× · tags: `Jenkins`
  <a id="suppose-a-production-deployment-fails-and-jenkins-catches-it-how-do-you-perform-"></a>
- [Suppose you are implementing a Canary Deployment where only 10% of users receive the new version. How would you implement it through your CI/CD pipeline?](../topics/deployment-strategies.md#suppose-you-are-implementing-a-canary-deployment-where-only-10-of-users-receive-) — 1× · tags: `CI/CD`, `Canary`
  <a id="suppose-you-are-implementing-a-canary-deployment-where-only-10-of-users-receive-"></a>
- [Your organization is migrating a 15 year old monolithic .NET application to a cloud native microservices architecture on Microsoft Azure. How would you manage application decomposition, data migration, API integration, security, and zero downtime deployment?](../topics/deployment-strategies.md#your-organization-is-migrating-a-15-year-old-monolithic-net-application-to-a-clo) — 1× · tags: `Azure`, `System Design`
  <a id="your-organization-is-migrating-a-15-year-old-monolithic-net-application-to-a-clo"></a>

## By interview round

### Unspecified

- [A critical production deployment fails during a global release, affecting 80 million users and resulting in an estimated ₹350 Crore business impact. How would you investigate the root cause, coordinate incident response, perform rollback or recovery, and implement preventive controls to eliminate similar failures in future releases?](../topics/deployment-strategies.md#a-critical-production-deployment-fails-during-a-global-release-affecting-80-mill) — tags: `Incident Response`
- [A deployment failed in Production. How would you troubleshoot?](../topics/deployment-strategies.md#a-deployment-failed-in-production-how-would-you-troubleshoot) — tags: `Incident Response`
- [A deployment succeeds, but latency increases from 80 ms to 2 seconds. Walk me through your debugging approach.](../topics/deployment-strategies.md#a-deployment-succeeds-but-latency-increases-from-80-ms-to-2-seconds-walk-me-thro)
- [A deployment succeeds, but the application becomes unavailable immediately afterward. What would be your step-by-step troubleshooting process?](../topics/deployment-strategies.md#a-deployment-succeeds-but-the-application-becomes-unavailable-immediately-afterw)
- [A failed deployment brings a mission-critical platform down globally. What are your first 30-minute actions?](../topics/deployment-strategies.md#a-failed-deployment-brings-a-mission-critical-platform-down-globally-what-are-yo)
- [A failed production deployment across 1,200 microservices impacts 35 million customers within 30 minutes. What would be your incident response, rollback, and recovery strategy?](../topics/deployment-strategies.md#a-failed-production-deployment-across-1200-microservices-impacts-35-million-cust) — tags: `Incident Response`
- [A Jenkins pipeline completed successfully, but the latest changes are not visible in production. What components would you verify before concluding the deployment failed?](../topics/deployment-strategies.md#a-jenkins-pipeline-completed-successfully-but-the-latest-changes-are-not-visible) — tags: `Jenkins`, `CI/CD`
- [A new deployment caused production issues. How would you safely roll back to the previous version?](../topics/deployment-strategies.md#a-new-deployment-caused-production-issues-how-would-you-safely-roll-back-to-the-)
- [A production deployment failed, and users are impacted. What would your rollback strategy look like?](../topics/deployment-strategies.md#a-production-deployment-failed-and-users-are-impacted-what-would-your-rollback-s) — tags: `Incident Response`
- [A production deployment failed. What steps would you take to troubleshoot and recover?](../topics/deployment-strategies.md#a-production-deployment-failed-what-steps-would-you-take-to-troubleshoot-and-rec) — tags: `Incident Response`
- [Blue-Green & Canary deployments](../topics/deployment-strategies.md#blue-green-canary-deployments) — tags: `Blue-Green`, `Canary`
- [CI/CD pipeline failures & production rollback](../topics/deployment-strategies.md#ci-cd-pipeline-failures-production-rollback) — tags: `CI/CD`
- [CI/CD, rollback and security best practices](../topics/deployment-strategies.md#ci-cd-rollback-and-security-best-practices) — tags: `CI/CD`
- [Describe your strategy for zero-downtime data migrations between entirely different storage backends.](../topics/deployment-strategies.md#describe-your-strategy-for-zero-downtime-data-migrations-between-entirely-differ)
- [Design a rollback strategy that works even if the deployment stage fails.](../topics/deployment-strategies.md#design-a-rollback-strategy-that-works-even-if-the-deployment-stage-fails)
- [Difference between blue-green and canary and roll-out deployments ? which is more expensive?](../topics/deployment-strategies.md#difference-between-blue-green-and-canary-and-roll-out-deployments-which-is-more-) — tags: `Blue-Green`, `Canary`
- [During a Canary deployment, how would you verify that the 10% deployment is healthy? What metrics would you monitor before proceeding to 100%?](../topics/deployment-strategies.md#during-a-canary-deployment-how-would-you-verify-that-the-10-deployment-is-health) — tags: `Canary`
- [Explain Blue-Green Deployment](../topics/deployment-strategies.md#explain-blue-green-deployment) — tags: `Blue-Green`
- [Explain Blue-Green Deployment and Canary Deployment. How have you implemented them?](../topics/deployment-strategies.md#explain-blue-green-deployment-and-canary-deployment-how-have-you-implemented-the) — tags: `Blue-Green`, `Canary`
- [Explain the difference between Rolling, Blue-Green, and Canary deployments.](../topics/deployment-strategies.md#explain-the-difference-between-rolling-blue-green-and-canary-deployments) — tags: `Blue-Green`, `Canary`
- [Explain your rollback strategy during production deployments.](../topics/deployment-strategies.md#explain-your-rollback-strategy-during-production-deployments)
- [For a production e-commerce application, which deployment strategy would you recommend—Rolling Update, Blue-Green, or Canary Deployment? What factors would influence your decision?](../topics/deployment-strategies.md#for-a-production-e-commerce-application-which-deployment-strategy-would-you-reco) — tags: `Blue-Green`, `Canary`
- [Helm rollback worked. App still broken. Logs silent. What now?](../topics/deployment-strategies.md#helm-rollback-worked-app-still-broken-logs-silent-what-now) — tags: `Helm`
- [How do you design a rollback strategy for a failed production deployment?](../topics/deployment-strategies.md#how-do-you-design-a-rollback-strategy-for-a-failed-production-deployment)
- [How do you design a rollback strategy if the deployment stage itself fails?](../topics/deployment-strategies.md#how-do-you-design-a-rollback-strategy-if-the-deployment-stage-itself-fails)
- [How do you ensure zero-downtime deployments in production?](../topics/deployment-strategies.md#how-do-you-ensure-zero-downtime-deployments-in-production)
- [How do you handle a failed deployment in production?](../topics/deployment-strategies.md#how-do-you-handle-a-failed-deployment-in-production)
- [How do you handle rollback if a deployment fails?](../topics/deployment-strategies.md#how-do-you-handle-rollback-if-a-deployment-fails)
- [How do you implement blue-green and canary deployments?](../topics/deployment-strategies.md#how-do-you-implement-blue-green-and-canary-deployments) — tags: `Blue-Green`, `Canary`
- [How do you implement rollback if deployment fails?](../topics/deployment-strategies.md#how-do-you-implement-rollback-if-deployment-fails)
- [How do you implement rollback strategy in Jenkins pipeline?](../topics/deployment-strategies.md#how-do-you-implement-rollback-strategy-in-jenkins-pipeline) — tags: `Jenkins`, `CI/CD`
- [How do you implement zero-downtime deployments?](../topics/deployment-strategies.md#how-do-you-implement-zero-downtime-deployments)
- [How do you perform a rolling update?](../topics/deployment-strategies.md#how-do-you-perform-a-rolling-update)
- [How do you roll back a failed deployment in Jenkins?](../topics/deployment-strategies.md#how-do-you-roll-back-a-failed-deployment-in-jenkins) — tags: `Jenkins`
- [How do you roll back a failed Kubernetes deployment?](../topics/deployment-strategies.md#how-do-you-roll-back-a-failed-kubernetes-deployment) — tags: `Kubernetes`
- [How do you safely roll back infrastructure changes after a failed deployment?](../topics/deployment-strategies.md#how-do-you-safely-roll-back-infrastructure-changes-after-a-failed-deployment)
- [How do you troubleshoot a failed deployment?](../topics/deployment-strategies.md#how-do-you-troubleshoot-a-failed-deployment)
- [How would you design a CI/CD pipeline with an automatic rollback strategy?](../topics/deployment-strategies.md#how-would-you-design-a-ci-cd-pipeline-with-an-automatic-rollback-strategy) — tags: `CI/CD`
- [How would you implement a reliable rollback strategy?](../topics/deployment-strategies.md#how-would-you-implement-a-reliable-rollback-strategy)
- [How would you implement a zero-downtime deployment?](../topics/deployment-strategies.md#how-would-you-implement-a-zero-downtime-deployment)
- [Production deployment failed. What steps would you take?](../topics/deployment-strategies.md#production-deployment-failed-what-steps-would-you-take)
- [Rollback strategies](../topics/deployment-strategies.md#rollback-strategies)
- [Rollback techniques in production](../topics/deployment-strategies.md#rollback-techniques-in-production)
- [Suppose a production deployment fails and Jenkins catches it. How do you perform rollback and what responsibilities did you handle?](../topics/deployment-strategies.md#suppose-a-production-deployment-fails-and-jenkins-catches-it-how-do-you-perform-) — tags: `Jenkins`
- [Suppose you are implementing a Canary Deployment where only 10% of users receive the new version. How would you implement it through your CI/CD pipeline?](../topics/deployment-strategies.md#suppose-you-are-implementing-a-canary-deployment-where-only-10-of-users-receive-) — tags: `CI/CD`, `Canary`
- [Tell me about a failed deployment you handled. How did you troubleshoot the issue, restore services, and prevent similar failures in the future?](../topics/deployment-strategies.md#tell-me-about-a-failed-deployment-you-handled-how-did-you-troubleshoot-the-issue)
- [What CI/CD practices have you implemented? Explain your experience with automated testing, deployment pipelines, rollback strategies, and monitoring.](../topics/deployment-strategies.md#what-ci-cd-practices-have-you-implemented-explain-your-experience-with-automated) — tags: `Monitoring`, `CI/CD`
- [What is a rolling rollback?](../topics/deployment-strategies.md#what-is-a-rolling-rollback)
- [What is Blue-Green Deployment?](../topics/deployment-strategies.md#what-is-blue-green-deployment) — tags: `Blue-Green`
- [What is Canary Deployment?](../topics/deployment-strategies.md#what-is-canary-deployment) — tags: `Canary`
- [What is the difference between blue-green deployment and canary deployment?](../topics/deployment-strategies.md#what-is-the-difference-between-blue-green-deployment-and-canary-deployment) — tags: `Blue-Green`, `Canary`
- [What rollback strategies do you follow?](../topics/deployment-strategies.md#what-rollback-strategies-do-you-follow)
- [You must migrate a business-critical platform across clouds with zero downtime. What is your strategy?](../topics/deployment-strategies.md#you-must-migrate-a-business-critical-platform-across-clouds-with-zero-downtime-w)
- [Your CI/CD deployment failed. The rollback pipeline also failed because it depends on the deployment stage. How would you redesign the pipeline to avoid this situation?](../topics/deployment-strategies.md#your-ci-cd-deployment-failed-the-rollback-pipeline-also-failed-because-it-depend) — tags: `CI/CD`
- [Your organization is migrating a 15 year old monolithic .NET application to a cloud native microservices architecture on Microsoft Azure. How would you manage application decomposition, data migration, API integration, security, and zero downtime deployment?](../topics/deployment-strategies.md#your-organization-is-migrating-a-15-year-old-monolithic-net-application-to-a-clo) — tags: `Azure`, `System Design`
- [Zero-downtime deployments](../topics/deployment-strategies.md#zero-downtime-deployments)

## Companies asking

- [Accenture](../companies/accenture.md)
- [Amazon](../companies/amazon.md)
- [Elite Code Technologies](../companies/elite-code-technologies.md)
- [Global Payments](../companies/global-payments.md)
- [Infosys](../companies/infosys.md)
- [Kotraya Technologies](../companies/kotraya-technologies.md)
- [Oracle](../companies/oracle.md)
- [TCS](../companies/tcs.md)

## Recently added

- [How do you implement rollback if deployment fails?](../topics/deployment-strategies.md#how-do-you-implement-rollback-if-deployment-fails) — 2026-08-19
- [How do you implement zero-downtime deployments?](../topics/deployment-strategies.md#how-do-you-implement-zero-downtime-deployments) — 2026-08-19
- [How do you design a rollback strategy if the deployment stage itself fails?](../topics/deployment-strategies.md#how-do-you-design-a-rollback-strategy-if-the-deployment-stage-itself-fails) — 2026-08-15
- [What is the difference between blue-green deployment and canary deployment?](../topics/deployment-strategies.md#what-is-the-difference-between-blue-green-deployment-and-canary-deployment) — 2026-08-13 · tags: `Blue-Green`, `Canary`
- [How do you ensure zero-downtime deployments in production?](../topics/deployment-strategies.md#how-do-you-ensure-zero-downtime-deployments-in-production) — 2026-08-12
- [A deployment succeeds, but latency increases from 80 ms to 2 seconds. Walk me through your debugging approach.](../topics/deployment-strategies.md#a-deployment-succeeds-but-latency-increases-from-80-ms-to-2-seconds-walk-me-thro) — 2026-08-12
- [Design a rollback strategy that works even if the deployment stage fails.](../topics/deployment-strategies.md#design-a-rollback-strategy-that-works-even-if-the-deployment-stage-fails) — 2026-08-12
- [Helm rollback worked. App still broken. Logs silent. What now?](../topics/deployment-strategies.md#helm-rollback-worked-app-still-broken-logs-silent-what-now) — 2026-08-12 · tags: `Helm`
- [Blue-Green & Canary deployments](../topics/deployment-strategies.md#blue-green-canary-deployments) — 2026-08-12 · tags: `Blue-Green`, `Canary`
- [How do you roll back a failed Kubernetes deployment?](../topics/deployment-strategies.md#how-do-you-roll-back-a-failed-kubernetes-deployment) — 2026-08-10 · tags: `Kubernetes`
- [How would you implement a zero-downtime deployment?](../topics/deployment-strategies.md#how-would-you-implement-a-zero-downtime-deployment) — 2026-08-10
- [Explain the difference between Rolling, Blue-Green, and Canary deployments.](../topics/deployment-strategies.md#explain-the-difference-between-rolling-blue-green-and-canary-deployments) — 2026-08-10 · tags: `Blue-Green`, `Canary`
- [Explain Blue-Green Deployment](../topics/deployment-strategies.md#explain-blue-green-deployment) — 2026-08-10 · tags: `Blue-Green`
- [How do you handle a failed deployment in production?](../topics/deployment-strategies.md#how-do-you-handle-a-failed-deployment-in-production) — 2026-08-10
- [Explain Blue-Green Deployment and Canary Deployment. How have you implemented them?](../topics/deployment-strategies.md#explain-blue-green-deployment-and-canary-deployment-how-have-you-implemented-the) — 2026-08-10 · tags: `Blue-Green`, `Canary`

## Related topics

- [CI/CD](./ci-cd.md)
- [Jenkins](./jenkins.md)
- [GitHub Actions](./github-actions.md)
- [Azure DevOps](./azure-devops.md)

## All questions

| Question | Diff | Asked |
| --- | --- | ---: |
| [A critical production deployment fails during a global release, affecting 80 million users and resulting in an estimated ₹350 Crore business impact. How would you investigate the root cause, coordinate incident response, perform rollback or recovery, and implement preventive controls to eliminate similar failures in future releases?](../topics/deployment-strategies.md#a-critical-production-deployment-fails-during-a-global-release-affecting-80-mill) | Hard | 1 |
| [A deployment failed in Production. How would you troubleshoot?](../topics/deployment-strategies.md#a-deployment-failed-in-production-how-would-you-troubleshoot) | Hard | 2 |
| [A deployment succeeds, but latency increases from 80 ms to 2 seconds. Walk me through your debugging approach.](../topics/deployment-strategies.md#a-deployment-succeeds-but-latency-increases-from-80-ms-to-2-seconds-walk-me-thro) | Medium | 5 |
| [A deployment succeeds, but the application becomes unavailable immediately afterward. What would be your step-by-step troubleshooting process?](../topics/deployment-strategies.md#a-deployment-succeeds-but-the-application-becomes-unavailable-immediately-afterw) | Medium | 1 |
| [A failed deployment brings a mission-critical platform down globally. What are your first 30-minute actions?](../topics/deployment-strategies.md#a-failed-deployment-brings-a-mission-critical-platform-down-globally-what-are-yo) | Medium | 1 |
| [A failed production deployment across 1,200 microservices impacts 35 million customers within 30 minutes. What would be your incident response, rollback, and recovery strategy?](../topics/deployment-strategies.md#a-failed-production-deployment-across-1200-microservices-impacts-35-million-cust) | Hard | 1 |
| [A Jenkins pipeline completed successfully, but the latest changes are not visible in production. What components would you verify before concluding the deployment failed?](../topics/deployment-strategies.md#a-jenkins-pipeline-completed-successfully-but-the-latest-changes-are-not-visible) | Hard | 2 |
| [A new deployment caused production issues. How would you safely roll back to the previous version?](../topics/deployment-strategies.md#a-new-deployment-caused-production-issues-how-would-you-safely-roll-back-to-the-) | Hard | 2 |
| [A production deployment failed, and users are impacted. What would your rollback strategy look like?](../topics/deployment-strategies.md#a-production-deployment-failed-and-users-are-impacted-what-would-your-rollback-s) | Hard | 1 |
| [A production deployment failed. What steps would you take to troubleshoot and recover?](../topics/deployment-strategies.md#a-production-deployment-failed-what-steps-would-you-take-to-troubleshoot-and-rec) | Hard | 1 |
| [Blue-Green & Canary deployments](../topics/deployment-strategies.md#blue-green-canary-deployments) | Medium | 3 |
| [CI/CD pipeline failures & production rollback](../topics/deployment-strategies.md#ci-cd-pipeline-failures-production-rollback) | Hard | 1 |
| [CI/CD, rollback and security best practices](../topics/deployment-strategies.md#ci-cd-rollback-and-security-best-practices) | Medium | 1 |
| [Describe your strategy for zero-downtime data migrations between entirely different storage backends.](../topics/deployment-strategies.md#describe-your-strategy-for-zero-downtime-data-migrations-between-entirely-differ) | Medium | 1 |
| [Design a rollback strategy that works even if the deployment stage fails.](../topics/deployment-strategies.md#design-a-rollback-strategy-that-works-even-if-the-deployment-stage-fails) | Hard | 7 |
| [Difference between blue-green and canary and roll-out deployments ? which is more expensive?](../topics/deployment-strategies.md#difference-between-blue-green-and-canary-and-roll-out-deployments-which-is-more-) | Medium | 3 |
| [During a Canary deployment, how would you verify that the 10% deployment is healthy? What metrics would you monitor before proceeding to 100%?](../topics/deployment-strategies.md#during-a-canary-deployment-how-would-you-verify-that-the-10-deployment-is-health) | Medium | 1 |
| [Explain Blue-Green Deployment](../topics/deployment-strategies.md#explain-blue-green-deployment) | Medium | 3 |
| [Explain Blue-Green Deployment and Canary Deployment. How have you implemented them?](../topics/deployment-strategies.md#explain-blue-green-deployment-and-canary-deployment-how-have-you-implemented-the) | Medium | 1 |
| [Explain the difference between Rolling, Blue-Green, and Canary deployments.](../topics/deployment-strategies.md#explain-the-difference-between-rolling-blue-green-and-canary-deployments) | Easy | 3 |
| [Explain your rollback strategy during production deployments.](../topics/deployment-strategies.md#explain-your-rollback-strategy-during-production-deployments) | Hard | 2 |
| [For a production e-commerce application, which deployment strategy would you recommend—Rolling Update, Blue-Green, or Canary Deployment? What factors would influence your decision?](../topics/deployment-strategies.md#for-a-production-e-commerce-application-which-deployment-strategy-would-you-reco) | Hard | 2 |
| [Helm rollback worked. App still broken. Logs silent. What now?](../topics/deployment-strategies.md#helm-rollback-worked-app-still-broken-logs-silent-what-now) | Medium | 2 |
| [How do you design a rollback strategy for a failed production deployment?](../topics/deployment-strategies.md#how-do-you-design-a-rollback-strategy-for-a-failed-production-deployment) | Hard | 1 |
| [How do you design a rollback strategy if the deployment stage itself fails?](../topics/deployment-strategies.md#how-do-you-design-a-rollback-strategy-if-the-deployment-stage-itself-fails) | Hard | 2 |
| [How do you ensure zero-downtime deployments in production?](../topics/deployment-strategies.md#how-do-you-ensure-zero-downtime-deployments-in-production) | Hard | 4 |
| [How do you handle a failed deployment in production?](../topics/deployment-strategies.md#how-do-you-handle-a-failed-deployment-in-production) | Hard | 2 |
| [How do you handle rollback if a deployment fails?](../topics/deployment-strategies.md#how-do-you-handle-rollback-if-a-deployment-fails) | Medium | 1 |
| [How do you implement blue-green and canary deployments?](../topics/deployment-strategies.md#how-do-you-implement-blue-green-and-canary-deployments) | Medium | 1 |
| [How do you implement rollback if deployment fails?](../topics/deployment-strategies.md#how-do-you-implement-rollback-if-deployment-fails) | Medium | 3 |
| [How do you implement rollback strategy in Jenkins pipeline?](../topics/deployment-strategies.md#how-do-you-implement-rollback-strategy-in-jenkins-pipeline) | Medium | 1 |
| [How do you implement zero-downtime deployments?](../topics/deployment-strategies.md#how-do-you-implement-zero-downtime-deployments) | Medium | 3 |
| [How do you perform a rolling update?](../topics/deployment-strategies.md#how-do-you-perform-a-rolling-update) | Medium | 2 |
| [How do you roll back a failed deployment in Jenkins?](../topics/deployment-strategies.md#how-do-you-roll-back-a-failed-deployment-in-jenkins) | Medium | 1 |
| [How do you roll back a failed Kubernetes deployment?](../topics/deployment-strategies.md#how-do-you-roll-back-a-failed-kubernetes-deployment) | Medium | 2 |
| [How do you safely roll back infrastructure changes after a failed deployment?](../topics/deployment-strategies.md#how-do-you-safely-roll-back-infrastructure-changes-after-a-failed-deployment) | Medium | 1 |
| [How do you troubleshoot a failed deployment?](../topics/deployment-strategies.md#how-do-you-troubleshoot-a-failed-deployment) | Medium | 1 |
| [How would you design a CI/CD pipeline with an automatic rollback strategy?](../topics/deployment-strategies.md#how-would-you-design-a-ci-cd-pipeline-with-an-automatic-rollback-strategy) | Hard | 2 |
| [How would you implement a reliable rollback strategy?](../topics/deployment-strategies.md#how-would-you-implement-a-reliable-rollback-strategy) | Hard | 1 |
| [How would you implement a zero-downtime deployment?](../topics/deployment-strategies.md#how-would-you-implement-a-zero-downtime-deployment) | Hard | 1 |
| [Production deployment failed. What steps would you take?](../topics/deployment-strategies.md#production-deployment-failed-what-steps-would-you-take) | Hard | 2 |
| [Rollback strategies](../topics/deployment-strategies.md#rollback-strategies) | Medium | 1 |
| [Rollback techniques in production](../topics/deployment-strategies.md#rollback-techniques-in-production) | Hard | 1 |
| [Suppose a production deployment fails and Jenkins catches it. How do you perform rollback and what responsibilities did you handle?](../topics/deployment-strategies.md#suppose-a-production-deployment-fails-and-jenkins-catches-it-how-do-you-perform-) | Hard | 1 |
| [Suppose you are implementing a Canary Deployment where only 10% of users receive the new version. How would you implement it through your CI/CD pipeline?](../topics/deployment-strategies.md#suppose-you-are-implementing-a-canary-deployment-where-only-10-of-users-receive-) | Hard | 1 |
| [Tell me about a failed deployment you handled. How did you troubleshoot the issue, restore services, and prevent similar failures in the future?](../topics/deployment-strategies.md#tell-me-about-a-failed-deployment-you-handled-how-did-you-troubleshoot-the-issue) | Medium | 1 |
| [What CI/CD practices have you implemented? Explain your experience with automated testing, deployment pipelines, rollback strategies, and monitoring.](../topics/deployment-strategies.md#what-ci-cd-practices-have-you-implemented-explain-your-experience-with-automated) | Medium | 1 |
| [What is a rolling rollback?](../topics/deployment-strategies.md#what-is-a-rolling-rollback) | Easy | 2 |
| [What is Blue-Green Deployment?](../topics/deployment-strategies.md#what-is-blue-green-deployment) | Easy | 5 |
| [What is Canary Deployment?](../topics/deployment-strategies.md#what-is-canary-deployment) | Easy | 1 |
| [What is the difference between blue-green deployment and canary deployment?](../topics/deployment-strategies.md#what-is-the-difference-between-blue-green-deployment-and-canary-deployment) | Easy | 1 |
| [What rollback strategies do you follow?](../topics/deployment-strategies.md#what-rollback-strategies-do-you-follow) | Medium | 2 |
| [You must migrate a business-critical platform across clouds with zero downtime. What is your strategy?](../topics/deployment-strategies.md#you-must-migrate-a-business-critical-platform-across-clouds-with-zero-downtime-w) | Medium | 1 |
| [Your CI/CD deployment failed. The rollback pipeline also failed because it depends on the deployment stage. How would you redesign the pipeline to avoid this situation?](../topics/deployment-strategies.md#your-ci-cd-deployment-failed-the-rollback-pipeline-also-failed-because-it-depend) | Medium | 1 |
| [Your organization is migrating a 15 year old monolithic .NET application to a cloud native microservices architecture on Microsoft Azure. How would you manage application decomposition, data migration, API integration, security, and zero downtime deployment?](../topics/deployment-strategies.md#your-organization-is-migrating-a-15-year-old-monolithic-net-application-to-a-clo) | Hard | 1 |
| [Zero-downtime deployments](../topics/deployment-strategies.md#zero-downtime-deployments) | Medium | 1 |

## Learning resources

- Practice [most asked overall](../study-guides/most-asked.md)
- Filter by [difficulty](../study-guides/by-difficulty.md)
- Browse [companies](../companies/README.md)

[← All topics](./README.md) · [Home](../README.md)
