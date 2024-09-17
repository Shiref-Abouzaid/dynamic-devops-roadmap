# Module 5: Transform - Finishing the Structure

[🗂 Back to the Roadmap Index](../../README.md#roadmap-index)

## Table of Content

- [Table of Content](#table-of-content)
- [5.1 Planning - Refine the Goals and Requirements](#51-planning---refine-the-goals-and-requirements)
- [5.2 Code - Working with External Systems](#52-code---working-with-external-systems)
- [5.3 Code - Writing Integration Tests](#53-code---writing-integration-tests)
- [5.4 Infrastructure - Infrastructure as Code and Configuration Management](#54-infrastructure---infrastructure-as-code-and-configuration-management)
- [5.5 Infrastructure - Terraform Essentials](#55-infrastructure---terraform-essentials)
- [5.6 Containers - Kubernetes Configuration Management](#56-containers---kubernetes-configuration-management)
- [5.7 Observability - Log Aggregation Systems](#57-observability---log-aggregation-systems)
- [5.8 Continuous Delivery - CD Best Practices](#58-continuous-delivery---cd-best-practices)
- [5.9 Project - HiveBox Phase 5](#59-project---hivebox-phase-5)

## 5.1 Planning - Refine the Goals and Requirements

### What you need to know

- At this point, you should have a working [project](../../projects/hivebox). It might not be perfect but good enough as start. Now it's time to start polishing it.
- First of all, you need to align with the business objectives. Is the project still relevant? Has the business changed direction, which requires changes in the tech side? Ensuring that the goals and requirements are aligned with the business means understanding the business context, market demands, and how you, as a DevOps engineer, can drive value to the company.
- OK, let's assume there have been no changes in the business directions. Now, it's essential to review the goals according to user feedback. You need to gather user feedback after using the first version of the solution you developed.
- Mostly, DevOps Engineers' users are other teams in the organization, but it could also be useful to get the end-users feedback via Product Owners/Managers.- You will refine your solution based on the business directions and user feedback. Establishing cross-functional collaboration with other teams (especially with the QA team) is also vital to ensure smooth end-to-end deliverability.
- From now on, you need to start building continuous feedback loops. They could have a simple structure, such as recutting meetings with different teams. We will cover this topic in detail in the next module.
- In general, planning should be considered a moving target. Goals should always be iterated to ensure they meet the requirements.

### Resources

- [Backlog Refinement Guide: How to & tips to be successful - Atlassian](https://www.atlassian.com/agile/scrum/backlog-refinement)
- [5 Strategies for Product Backlog Refinement - Scrum.org](https://www.scrum.org/resources/blog/5-strategies-product-backlog-refinement)

## 5.2 Code - Working with External Systems

### What you need to know

- As a DevOps Engineer, you will work or integrate with external systems using code or tools. Those external systems could be third-party APIs, databases, cloud services, or microservices.
- You will mostly use REST APIs to interact with those services, but there are many ways to communicate with those systems according to each use case.
- Here, we will cover some essential points when working with external systems programmatically.
  - If it's a known system, it's usually better to use a library or SDK for that system. Don't write everything from scratch.
  - Ensure to handle errors and rate limits. Know how to implement rate-limiting strategies (e.g., exponential backoff).
  - Ensure you handle paginated responses (e.g., retrieving data in chunks), especially if you expect a big load of data.
  - Use caching whenever possible. Don't hummer the systems with unnecessary calls.
  - Always use secure connection with external systems even if the use case is trivial.
  - Not every connection should be synced; you could use async communication by using message queues to deal with lagging and latency under pressure.

### Resources

- [System Integration: Types, Approaches, and Implementation Steps - AltexSoft](https://www.altexsoft.com/blog/system-integration/)
- [System Integration vs Software Development - Budibase](https://budibase.com/blog/app-building/system-integration-vs-software-development/)

## 5.3 Code - Writing Integration Tests

### What you need to know

- 

### Resources

- 

## 5.4 Infrastructure - Infrastructure as Code and Configuration Management

### What you need to know

- 

### Resources

- 

## 5.5 Infrastructure - Terraform Essentials

### What you need to know

- 

### Resources

- 

## 5.6 Containers - Kubernetes Configuration Management

### What you need to know

- 

### Resources

- 

## 5.7 Observability - Log Aggregation Systems

### What you need to know

- 

### Resources

- 

## 5.8 Continuous Delivery - CD Best Practices

### What you need to know

- 

### Resources

- 

## 5.9 Project - HiveBox Phase 5

Follow the instructions in the [HiveBox project phase 5](../../projects/hivebox/README.md#phase-5).

---

If you are done, [🗂 Back to the Roadmap Index](../../README.md#roadmap-index)