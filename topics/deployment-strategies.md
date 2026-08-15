# Deployment Strategies

[Home](../README.md) > [Topics](./README.md) > **Deployment Strategies**

**23** real interview questions. Study this page end-to-end — open a detail page only when an answer is enriched.

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
| Questions | 23 |
| Easy / Medium / Hard | 3 / 10 / 10 |
| Companies | 5 |

## Most asked

- [Design a rollback strategy that works even if the deployment stage fails.](../topics/deployment-strategies.md#design-a-rollback-strategy-that-works-even-if-the-deployment-stage-fails) — **7×** · Hard
  <a id="design-a-rollback-strategy-that-works-even-if-the-deployment-stage-fails"></a>
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
- [Explain your rollback strategy during production deployments.](../topics/deployment-strategies.md#explain-your-rollback-strategy-during-production-deployments) — **2×** · Hard
  <a id="explain-your-rollback-strategy-during-production-deployments"></a>
- [How do you design a rollback strategy if the deployment stage itself fails?](../topics/deployment-strategies.md#how-do-you-design-a-rollback-strategy-if-the-deployment-stage-itself-fails) — **2×** · Hard
  <a id="how-do-you-design-a-rollback-strategy-if-the-deployment-stage-itself-fails"></a>
- [How do you perform a rolling update?](../topics/deployment-strategies.md#how-do-you-perform-a-rolling-update) — **2×** · Medium
  <a id="how-do-you-perform-a-rolling-update"></a>
- [A production deployment failed, and users are impacted. What would your rollback strategy look like?](../topics/deployment-strategies.md#a-production-deployment-failed-and-users-are-impacted-what-would-your-rollback-s) — **1×** · Hard
  <a id="a-production-deployment-failed-and-users-are-impacted-what-would-your-rollback-s"></a>
- [Describe your strategy for zero-downtime data migrations between entirely different storage backends.](../topics/deployment-strategies.md#describe-your-strategy-for-zero-downtime-data-migrations-between-entirely-differ) — **1×** · Medium
  <a id="describe-your-strategy-for-zero-downtime-data-migrations-between-entirely-differ"></a>
- [During a Canary deployment, how would you verify that the 10% deployment is healthy? What metrics would you monitor before proceeding to 100%?](../topics/deployment-strategies.md#during-a-canary-deployment-how-would-you-verify-that-the-10-deployment-is-health) — **1×** · Medium · tags: `Canary`
  <a id="during-a-canary-deployment-how-would-you-verify-that-the-10-deployment-is-health"></a>
- [Explain Blue-Green Deployment and Canary Deployment. How have you implemented them?](../topics/deployment-strategies.md#explain-blue-green-deployment-and-canary-deployment-how-have-you-implemented-the) — **1×** · Medium · tags: `Blue-Green`, `Canary`
  <a id="explain-blue-green-deployment-and-canary-deployment-how-have-you-implemented-the"></a>
- [How do you design a rollback strategy for a failed production deployment?](../topics/deployment-strategies.md#how-do-you-design-a-rollback-strategy-for-a-failed-production-deployment) — **1×** · Hard
  <a id="how-do-you-design-a-rollback-strategy-for-a-failed-production-deployment"></a>
- [How do you implement blue-green and canary deployments?](../topics/deployment-strategies.md#how-do-you-implement-blue-green-and-canary-deployments) — **1×** · Medium · tags: `Blue-Green`, `Canary`
  <a id="how-do-you-implement-blue-green-and-canary-deployments"></a>
- [How would you implement a reliable rollback strategy?](../topics/deployment-strategies.md#how-would-you-implement-a-reliable-rollback-strategy) — **1×** · Hard
  <a id="how-would-you-implement-a-reliable-rollback-strategy"></a>
- [How would you implement a zero-downtime deployment?](../topics/deployment-strategies.md#how-would-you-implement-a-zero-downtime-deployment) — **1×** · Hard
  <a id="how-would-you-implement-a-zero-downtime-deployment"></a>
- [Suppose you are implementing a Canary Deployment where only 10% of users receive the new version. How would you implement it through your CI/CD pipeline?](../topics/deployment-strategies.md#suppose-you-are-implementing-a-canary-deployment-where-only-10-of-users-receive-) — **1×** · Hard · tags: `CI/CD`, `Canary`
  <a id="suppose-you-are-implementing-a-canary-deployment-where-only-10-of-users-receive-"></a>
- [What is Canary Deployment?](../topics/deployment-strategies.md#what-is-canary-deployment) — **1×** · Easy · tags: `Canary`
  <a id="what-is-canary-deployment"></a>
- [What is the difference between blue-green deployment and canary deployment?](../topics/deployment-strategies.md#what-is-the-difference-between-blue-green-deployment-and-canary-deployment) — **1×** · Easy · tags: `Blue-Green`, `Canary`
  <a id="what-is-the-difference-between-blue-green-deployment-and-canary-deployment"></a>
- [You must migrate a business-critical platform across clouds with zero downtime. What is your strategy?](../topics/deployment-strategies.md#you-must-migrate-a-business-critical-platform-across-clouds-with-zero-downtime-w) — **1×** · Medium
  <a id="you-must-migrate-a-business-critical-platform-across-clouds-with-zero-downtime-w"></a>
- [Your organization is migrating a 15 year old monolithic .NET application to a cloud native microservices architecture on Microsoft Azure. How would you manage application decomposition, data migration, API integration, security, and zero downtime deployment?](../topics/deployment-strategies.md#your-organization-is-migrating-a-15-year-old-monolithic-net-application-to-a-clo) — **1×** · Hard · tags: `Azure`, `System Design`
  <a id="your-organization-is-migrating-a-15-year-old-monolithic-net-application-to-a-clo"></a>
- [Zero-downtime deployments](../topics/deployment-strategies.md#zero-downtime-deployments) — **1×** · Medium
  <a id="zero-downtime-deployments"></a>

## Beginner

- [Explain the difference between Rolling, Blue-Green, and Canary deployments.](../topics/deployment-strategies.md#explain-the-difference-between-rolling-blue-green-and-canary-deployments) — 3× · tags: `Blue-Green`, `Canary`
  <a id="explain-the-difference-between-rolling-blue-green-and-canary-deployments"></a>
- [What is Canary Deployment?](../topics/deployment-strategies.md#what-is-canary-deployment) — 1× · tags: `Canary`
  <a id="what-is-canary-deployment"></a>
- [What is the difference between blue-green deployment and canary deployment?](../topics/deployment-strategies.md#what-is-the-difference-between-blue-green-deployment-and-canary-deployment) — 1× · tags: `Blue-Green`, `Canary`
  <a id="what-is-the-difference-between-blue-green-deployment-and-canary-deployment"></a>

## Intermediate

- [Blue-Green & Canary deployments](../topics/deployment-strategies.md#blue-green-canary-deployments) — 3× · tags: `Blue-Green`, `Canary`
  <a id="blue-green-canary-deployments"></a>
- [Difference between blue-green and canary and roll-out deployments ? which is more expensive?](../topics/deployment-strategies.md#difference-between-blue-green-and-canary-and-roll-out-deployments-which-is-more-) — 3× · tags: `Blue-Green`, `Canary`
  <a id="difference-between-blue-green-and-canary-and-roll-out-deployments-which-is-more-"></a>
- [Explain Blue-Green Deployment](../topics/deployment-strategies.md#explain-blue-green-deployment) — 3× · tags: `Blue-Green`
  <a id="explain-blue-green-deployment"></a>
- [How do you perform a rolling update?](../topics/deployment-strategies.md#how-do-you-perform-a-rolling-update) — 2×
  <a id="how-do-you-perform-a-rolling-update"></a>
- [Describe your strategy for zero-downtime data migrations between entirely different storage backends.](../topics/deployment-strategies.md#describe-your-strategy-for-zero-downtime-data-migrations-between-entirely-differ) — 1×
  <a id="describe-your-strategy-for-zero-downtime-data-migrations-between-entirely-differ"></a>
- [During a Canary deployment, how would you verify that the 10% deployment is healthy? What metrics would you monitor before proceeding to 100%?](../topics/deployment-strategies.md#during-a-canary-deployment-how-would-you-verify-that-the-10-deployment-is-health) — 1× · tags: `Canary`
  <a id="during-a-canary-deployment-how-would-you-verify-that-the-10-deployment-is-health"></a>
- [Explain Blue-Green Deployment and Canary Deployment. How have you implemented them?](../topics/deployment-strategies.md#explain-blue-green-deployment-and-canary-deployment-how-have-you-implemented-the) — 1× · tags: `Blue-Green`, `Canary`
  <a id="explain-blue-green-deployment-and-canary-deployment-how-have-you-implemented-the"></a>
- [How do you implement blue-green and canary deployments?](../topics/deployment-strategies.md#how-do-you-implement-blue-green-and-canary-deployments) — 1× · tags: `Blue-Green`, `Canary`
  <a id="how-do-you-implement-blue-green-and-canary-deployments"></a>
- [You must migrate a business-critical platform across clouds with zero downtime. What is your strategy?](../topics/deployment-strategies.md#you-must-migrate-a-business-critical-platform-across-clouds-with-zero-downtime-w) — 1×
  <a id="you-must-migrate-a-business-critical-platform-across-clouds-with-zero-downtime-w"></a>
- [Zero-downtime deployments](../topics/deployment-strategies.md#zero-downtime-deployments) — 1×
  <a id="zero-downtime-deployments"></a>

## Advanced

- [Design a rollback strategy that works even if the deployment stage fails.](../topics/deployment-strategies.md#design-a-rollback-strategy-that-works-even-if-the-deployment-stage-fails) — 7×
  <a id="design-a-rollback-strategy-that-works-even-if-the-deployment-stage-fails"></a>
- [How do you ensure zero-downtime deployments in production?](../topics/deployment-strategies.md#how-do-you-ensure-zero-downtime-deployments-in-production) — 4×
  <a id="how-do-you-ensure-zero-downtime-deployments-in-production"></a>
- [Explain your rollback strategy during production deployments.](../topics/deployment-strategies.md#explain-your-rollback-strategy-during-production-deployments) — 2×
  <a id="explain-your-rollback-strategy-during-production-deployments"></a>
- [How do you design a rollback strategy if the deployment stage itself fails?](../topics/deployment-strategies.md#how-do-you-design-a-rollback-strategy-if-the-deployment-stage-itself-fails) — 2×
  <a id="how-do-you-design-a-rollback-strategy-if-the-deployment-stage-itself-fails"></a>
- [A production deployment failed, and users are impacted. What would your rollback strategy look like?](../topics/deployment-strategies.md#a-production-deployment-failed-and-users-are-impacted-what-would-your-rollback-s) — 1×
  <a id="a-production-deployment-failed-and-users-are-impacted-what-would-your-rollback-s"></a>
- [How do you design a rollback strategy for a failed production deployment?](../topics/deployment-strategies.md#how-do-you-design-a-rollback-strategy-for-a-failed-production-deployment) — 1×
  <a id="how-do-you-design-a-rollback-strategy-for-a-failed-production-deployment"></a>
- [How would you implement a reliable rollback strategy?](../topics/deployment-strategies.md#how-would-you-implement-a-reliable-rollback-strategy) — 1×
  <a id="how-would-you-implement-a-reliable-rollback-strategy"></a>
- [How would you implement a zero-downtime deployment?](../topics/deployment-strategies.md#how-would-you-implement-a-zero-downtime-deployment) — 1×
  <a id="how-would-you-implement-a-zero-downtime-deployment"></a>
- [Suppose you are implementing a Canary Deployment where only 10% of users receive the new version. How would you implement it through your CI/CD pipeline?](../topics/deployment-strategies.md#suppose-you-are-implementing-a-canary-deployment-where-only-10-of-users-receive-) — 1× · tags: `CI/CD`, `Canary`
  <a id="suppose-you-are-implementing-a-canary-deployment-where-only-10-of-users-receive-"></a>
- [Your organization is migrating a 15 year old monolithic .NET application to a cloud native microservices architecture on Microsoft Azure. How would you manage application decomposition, data migration, API integration, security, and zero downtime deployment?](../topics/deployment-strategies.md#your-organization-is-migrating-a-15-year-old-monolithic-net-application-to-a-clo) — 1× · tags: `Azure`, `System Design`
  <a id="your-organization-is-migrating-a-15-year-old-monolithic-net-application-to-a-clo"></a>

## By interview round

### Unspecified

- [A production deployment failed, and users are impacted. What would your rollback strategy look like?](../topics/deployment-strategies.md#a-production-deployment-failed-and-users-are-impacted-what-would-your-rollback-s)
- [Blue-Green & Canary deployments](../topics/deployment-strategies.md#blue-green-canary-deployments) — tags: `Blue-Green`, `Canary`
- [Describe your strategy for zero-downtime data migrations between entirely different storage backends.](../topics/deployment-strategies.md#describe-your-strategy-for-zero-downtime-data-migrations-between-entirely-differ)
- [Design a rollback strategy that works even if the deployment stage fails.](../topics/deployment-strategies.md#design-a-rollback-strategy-that-works-even-if-the-deployment-stage-fails)
- [Difference between blue-green and canary and roll-out deployments ? which is more expensive?](../topics/deployment-strategies.md#difference-between-blue-green-and-canary-and-roll-out-deployments-which-is-more-) — tags: `Blue-Green`, `Canary`
- [During a Canary deployment, how would you verify that the 10% deployment is healthy? What metrics would you monitor before proceeding to 100%?](../topics/deployment-strategies.md#during-a-canary-deployment-how-would-you-verify-that-the-10-deployment-is-health) — tags: `Canary`
- [Explain Blue-Green Deployment](../topics/deployment-strategies.md#explain-blue-green-deployment) — tags: `Blue-Green`
- [Explain Blue-Green Deployment and Canary Deployment. How have you implemented them?](../topics/deployment-strategies.md#explain-blue-green-deployment-and-canary-deployment-how-have-you-implemented-the) — tags: `Blue-Green`, `Canary`
- [Explain the difference between Rolling, Blue-Green, and Canary deployments.](../topics/deployment-strategies.md#explain-the-difference-between-rolling-blue-green-and-canary-deployments) — tags: `Blue-Green`, `Canary`
- [Explain your rollback strategy during production deployments.](../topics/deployment-strategies.md#explain-your-rollback-strategy-during-production-deployments)
- [How do you design a rollback strategy for a failed production deployment?](../topics/deployment-strategies.md#how-do-you-design-a-rollback-strategy-for-a-failed-production-deployment)
- [How do you design a rollback strategy if the deployment stage itself fails?](../topics/deployment-strategies.md#how-do-you-design-a-rollback-strategy-if-the-deployment-stage-itself-fails)
- [How do you ensure zero-downtime deployments in production?](../topics/deployment-strategies.md#how-do-you-ensure-zero-downtime-deployments-in-production)
- [How do you implement blue-green and canary deployments?](../topics/deployment-strategies.md#how-do-you-implement-blue-green-and-canary-deployments) — tags: `Blue-Green`, `Canary`
- [How do you perform a rolling update?](../topics/deployment-strategies.md#how-do-you-perform-a-rolling-update)
- [How would you implement a reliable rollback strategy?](../topics/deployment-strategies.md#how-would-you-implement-a-reliable-rollback-strategy)
- [How would you implement a zero-downtime deployment?](../topics/deployment-strategies.md#how-would-you-implement-a-zero-downtime-deployment)
- [Suppose you are implementing a Canary Deployment where only 10% of users receive the new version. How would you implement it through your CI/CD pipeline?](../topics/deployment-strategies.md#suppose-you-are-implementing-a-canary-deployment-where-only-10-of-users-receive-) — tags: `CI/CD`, `Canary`
- [What is Canary Deployment?](../topics/deployment-strategies.md#what-is-canary-deployment) — tags: `Canary`
- [What is the difference between blue-green deployment and canary deployment?](../topics/deployment-strategies.md#what-is-the-difference-between-blue-green-deployment-and-canary-deployment) — tags: `Blue-Green`, `Canary`
- [You must migrate a business-critical platform across clouds with zero downtime. What is your strategy?](../topics/deployment-strategies.md#you-must-migrate-a-business-critical-platform-across-clouds-with-zero-downtime-w)
- [Your organization is migrating a 15 year old monolithic .NET application to a cloud native microservices architecture on Microsoft Azure. How would you manage application decomposition, data migration, API integration, security, and zero downtime deployment?](../topics/deployment-strategies.md#your-organization-is-migrating-a-15-year-old-monolithic-net-application-to-a-clo) — tags: `Azure`, `System Design`
- [Zero-downtime deployments](../topics/deployment-strategies.md#zero-downtime-deployments)

## Companies asking

- [Amazon](../companies/amazon.md)
- [Elite Code Technologies](../companies/elite-code-technologies.md)
- [Infosys](../companies/infosys.md)
- [Oracle](../companies/oracle.md)
- [TCS](../companies/tcs.md)

## Recently added

- [How do you design a rollback strategy if the deployment stage itself fails?](../topics/deployment-strategies.md#how-do-you-design-a-rollback-strategy-if-the-deployment-stage-itself-fails) — 2026-08-15
- [What is the difference between blue-green deployment and canary deployment?](../topics/deployment-strategies.md#what-is-the-difference-between-blue-green-deployment-and-canary-deployment) — 2026-08-13 · tags: `Blue-Green`, `Canary`
- [How do you ensure zero-downtime deployments in production?](../topics/deployment-strategies.md#how-do-you-ensure-zero-downtime-deployments-in-production) — 2026-08-12
- [Design a rollback strategy that works even if the deployment stage fails.](../topics/deployment-strategies.md#design-a-rollback-strategy-that-works-even-if-the-deployment-stage-fails) — 2026-08-12
- [Blue-Green & Canary deployments](../topics/deployment-strategies.md#blue-green-canary-deployments) — 2026-08-12 · tags: `Blue-Green`, `Canary`
- [How would you implement a zero-downtime deployment?](../topics/deployment-strategies.md#how-would-you-implement-a-zero-downtime-deployment) — 2026-08-10
- [Explain the difference between Rolling, Blue-Green, and Canary deployments.](../topics/deployment-strategies.md#explain-the-difference-between-rolling-blue-green-and-canary-deployments) — 2026-08-10 · tags: `Blue-Green`, `Canary`
- [Explain Blue-Green Deployment](../topics/deployment-strategies.md#explain-blue-green-deployment) — 2026-08-10 · tags: `Blue-Green`
- [Explain Blue-Green Deployment and Canary Deployment. How have you implemented them?](../topics/deployment-strategies.md#explain-blue-green-deployment-and-canary-deployment-how-have-you-implemented-the) — 2026-08-10 · tags: `Blue-Green`, `Canary`
- [Difference between blue-green and canary and roll-out deployments ? which is more expensive?](../topics/deployment-strategies.md#difference-between-blue-green-and-canary-and-roll-out-deployments-which-is-more-) — 2026-08-10 · tags: `Blue-Green`, `Canary`
- [Describe your strategy for zero-downtime data migrations between entirely different storage backends.](../topics/deployment-strategies.md#describe-your-strategy-for-zero-downtime-data-migrations-between-entirely-differ) — 2026-08-02
- [Your organization is migrating a 15 year old monolithic .NET application to a cloud native microservices architecture on Microsoft Azure. How would you manage application decomposition, data migration, API integration, security, and zero downtime deployment?](../topics/deployment-strategies.md#your-organization-is-migrating-a-15-year-old-monolithic-net-application-to-a-clo) — 2026-08-02 · tags: `Azure`, `System Design`
- [During a Canary deployment, how would you verify that the 10% deployment is healthy? What metrics would you monitor before proceeding to 100%?](../topics/deployment-strategies.md#during-a-canary-deployment-how-would-you-verify-that-the-10-deployment-is-health) — 2026-08-02 · tags: `Canary`
- [Suppose you are implementing a Canary Deployment where only 10% of users receive the new version. How would you implement it through your CI/CD pipeline?](../topics/deployment-strategies.md#suppose-you-are-implementing-a-canary-deployment-where-only-10-of-users-receive-) — 2026-08-02 · tags: `CI/CD`, `Canary`
- [How do you implement blue-green and canary deployments?](../topics/deployment-strategies.md#how-do-you-implement-blue-green-and-canary-deployments) — 2026-07-28 · tags: `Blue-Green`, `Canary`

## Related topics

- [CI/CD](./ci-cd.md)
- [Jenkins](./jenkins.md)
- [GitHub Actions](./github-actions.md)
- [Azure DevOps](./azure-devops.md)

## All questions

| Question | Diff | Asked |
| --- | --- | ---: |
| [A production deployment failed, and users are impacted. What would your rollback strategy look like?](../topics/deployment-strategies.md#a-production-deployment-failed-and-users-are-impacted-what-would-your-rollback-s) | Hard | 1 |
| [Blue-Green & Canary deployments](../topics/deployment-strategies.md#blue-green-canary-deployments) | Medium | 3 |
| [Describe your strategy for zero-downtime data migrations between entirely different storage backends.](../topics/deployment-strategies.md#describe-your-strategy-for-zero-downtime-data-migrations-between-entirely-differ) | Medium | 1 |
| [Design a rollback strategy that works even if the deployment stage fails.](../topics/deployment-strategies.md#design-a-rollback-strategy-that-works-even-if-the-deployment-stage-fails) | Hard | 7 |
| [Difference between blue-green and canary and roll-out deployments ? which is more expensive?](../topics/deployment-strategies.md#difference-between-blue-green-and-canary-and-roll-out-deployments-which-is-more-) | Medium | 3 |
| [During a Canary deployment, how would you verify that the 10% deployment is healthy? What metrics would you monitor before proceeding to 100%?](../topics/deployment-strategies.md#during-a-canary-deployment-how-would-you-verify-that-the-10-deployment-is-health) | Medium | 1 |
| [Explain Blue-Green Deployment](../topics/deployment-strategies.md#explain-blue-green-deployment) | Medium | 3 |
| [Explain Blue-Green Deployment and Canary Deployment. How have you implemented them?](../topics/deployment-strategies.md#explain-blue-green-deployment-and-canary-deployment-how-have-you-implemented-the) | Medium | 1 |
| [Explain the difference between Rolling, Blue-Green, and Canary deployments.](../topics/deployment-strategies.md#explain-the-difference-between-rolling-blue-green-and-canary-deployments) | Easy | 3 |
| [Explain your rollback strategy during production deployments.](../topics/deployment-strategies.md#explain-your-rollback-strategy-during-production-deployments) | Hard | 2 |
| [How do you design a rollback strategy for a failed production deployment?](../topics/deployment-strategies.md#how-do-you-design-a-rollback-strategy-for-a-failed-production-deployment) | Hard | 1 |
| [How do you design a rollback strategy if the deployment stage itself fails?](../topics/deployment-strategies.md#how-do-you-design-a-rollback-strategy-if-the-deployment-stage-itself-fails) | Hard | 2 |
| [How do you ensure zero-downtime deployments in production?](../topics/deployment-strategies.md#how-do-you-ensure-zero-downtime-deployments-in-production) | Hard | 4 |
| [How do you implement blue-green and canary deployments?](../topics/deployment-strategies.md#how-do-you-implement-blue-green-and-canary-deployments) | Medium | 1 |
| [How do you perform a rolling update?](../topics/deployment-strategies.md#how-do-you-perform-a-rolling-update) | Medium | 2 |
| [How would you implement a reliable rollback strategy?](../topics/deployment-strategies.md#how-would-you-implement-a-reliable-rollback-strategy) | Hard | 1 |
| [How would you implement a zero-downtime deployment?](../topics/deployment-strategies.md#how-would-you-implement-a-zero-downtime-deployment) | Hard | 1 |
| [Suppose you are implementing a Canary Deployment where only 10% of users receive the new version. How would you implement it through your CI/CD pipeline?](../topics/deployment-strategies.md#suppose-you-are-implementing-a-canary-deployment-where-only-10-of-users-receive-) | Hard | 1 |
| [What is Canary Deployment?](../topics/deployment-strategies.md#what-is-canary-deployment) | Easy | 1 |
| [What is the difference between blue-green deployment and canary deployment?](../topics/deployment-strategies.md#what-is-the-difference-between-blue-green-deployment-and-canary-deployment) | Easy | 1 |
| [You must migrate a business-critical platform across clouds with zero downtime. What is your strategy?](../topics/deployment-strategies.md#you-must-migrate-a-business-critical-platform-across-clouds-with-zero-downtime-w) | Medium | 1 |
| [Your organization is migrating a 15 year old monolithic .NET application to a cloud native microservices architecture on Microsoft Azure. How would you manage application decomposition, data migration, API integration, security, and zero downtime deployment?](../topics/deployment-strategies.md#your-organization-is-migrating-a-15-year-old-monolithic-net-application-to-a-clo) | Hard | 1 |
| [Zero-downtime deployments](../topics/deployment-strategies.md#zero-downtime-deployments) | Medium | 1 |

## Learning resources

- Practice [most asked overall](../study-guides/most-asked.md)
- Filter by [difficulty](../study-guides/by-difficulty.md)
- Browse [companies](../companies/README.md)

[← All topics](./README.md) · [Home](../README.md)
