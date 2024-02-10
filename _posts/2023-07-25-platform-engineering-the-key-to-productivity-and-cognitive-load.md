---
layout: post
title:  "Platform Engineering: The Key to Productivity and Cognitive Load"
date:   2023-07-25 17:00:00 +0000
categories: [Platform Engineering, Internal Developer Platform, Data Engineering, Data Governance]
---

In the fast-paced world of data falling behind the speed of business and cloud native platform operations, data engineers must use mountains of processes and tools that are simply overbearing. These issues are also raised by multiple engineering teams, calling for platform engineering infrastructure solutions.

Successful platform engineering teams leverage common technologies and processes to build robust internal developer platform capabilities. Read on to learn more about platform engineering and its benefits, including how cognitive load can be significantly reduced with it.

![](https://cdn-images-1.medium.com/max/2912/0*TFBg_0Ix_Hq3beZu.png)

## Constant And High Cognitive Load Reduces the Productivity of Data Engineers

Have you ever felt overwhelmed by the number of details you need to keep in mind when crafting and shipping even the simplest data pipeline or software module? What about a more complex project like a cloud native platform operation?

If so, bad news… your brain shouldn’t have to replace a platform engineering infrastructure.

Data engineers often must remember many details: business requirements, integrating data from other domains, configuration options, dependencies, and scaling requirements. On top of that, they still need to ship high-quality data pipelines compliant with governance rules, security standards, and data quality checks.

You soon start to feel that you need more RAM than your computer, and this is an increasingly shared feeling among engineers due to the complexity of the development process that keeps growing.

## What is Cognitive Load and How Does it Impact Data Engineers?

In theory, [cognitive load](https://my.chartered.college/impact_article/%20cognitive-load-theory-and-its-application-in-the-classroom/) can be defined as:
> # The cognitive effort (or amount of information processing) required by a person to perform this task.

It has started gaining popularity only recently in the software industry. The book “Team Topologies” describes the effects of cognitive overload on high-performing software engineering teams, contributing to this trend.

**Matthew Skelton** and **Manuel Pais** suggest that cognitive load can be utilized as a [key aspect of architectural and organizational design](https://techbeacon.com/app-dev-testing/how-reduce-cognitive-load-increase-flow-5-real-world-examples), to improve team efficiency and speed up time to value. In our case, that’s a modern platform engineering solution that reduces the cognitive load of data engineers.

Having too much cognitive load can limit the amount of information retained and processed, making it difficult to complete tasks. This is a recurring struggle for anyone trying to navigate a complex technical landscape. New tools are released daily so keeping up with their features, evaluating them, selecting the right ones for the job, and understanding how they interact with each other and fit into your tech stack can be overwhelming.

## How do data engineering projects differ from software engineering projects?

As more and more companies become data-driven, an increasing number of new tools and data management practices will become available. For this reason, data engineering projects require a higher level of cognitive effort.

Let’s consider some key aspects to better explain the idea:

### Data Engineering is more than business, code, and infrastructure.

Software engineering involves code, business, and infrastructure, whereas data engineering involves all that, plus the data lifecycle and data infrastructure. Data engineering projects require a higher level of cognitive effort because data engineers also need to consider the business context and data lifecycle they are working with.

This complexity can lead to cognitive overload, which impairs their ability to make good decisions and solve complex problems.

### Testing

A good data engineer must test software but also makes sure that data is tested and continues to be tested during runtime. While testing is mainly done at deploy-time in software engineering, data needs to be assessed and measured at runtime as well to check that quality standards are met, in the case of data engineering.

### Ensuring that software and data work properly is key along with data consistency in time

Once the software development process is completed, the main concern is ensuring that the software continues to work properly. In data engineering, however, it is necessary to ensure that data also remains consistent and compliant with expectations.

Additionally, while software engineering is not influenced by time, data accumulates and it is necessary to manage its entire history, at every point in time. For example, if a breaking change is made to data, simply updating the software is not enough. The historical data must also be corrected and aligned to ensure that it is consistent (think about schema migrations).

### Data engineering tools and best practices are still evolving

The available tools for data engineering are still very diverse and require engineers to try to configure and understand them. Unlike enterprise software engineering, where there are established best practices and standard tools, data engineering tools are still evolving rapidly.

Data engineers need to keep up with the latest developments and be able to understand and configure a wide range of tools to design and optimize data operations effectively. Also, while software engineering has brought well-established tools during the DevOps boom, data engineering has a wider range of tools that involve both DevOps and DataOps.

Having to deal with a wide range of tools in the day-to-day job highly increases the cognitive load due to different UIs, logins, commands, and know-how.

### Project templates, scaffolding tools, and computational governance for data engineering are still in the early stages of development

Most people create pipelines from scratch however they want. This means that data engineering projects often lack standardization and engineers need to create custom solutions that fit the specific requirements of each project.

This can be time-consuming and requires a high level of cognitive effort, especially when requirements change. Domain knowledge is crucial for data engineers to understand the data being processed and to troubleshoot any issues that may arise. This knowledge includes an understanding of the business domain to which the data belongs, including jargon, industry trends, and other relevant knowledge necessary to comprehend the nuances of the data.

### Collaboration patterns for data engineering haven’t been standardized yet

Unlike enterprise software where collaboration patterns are well-established, data engineering collaboration patterns are still evolving. Engineers need to be able to adapt to different collaboration patterns and work effectively in a variety of team structures.

These factors can worsen the overall experience of a data engineer. This is why cognitive load is rapidly becoming a crucial aspect to consider when planning and executing data engineering projects. Ensuring that data application development teams are adequately supported can help them deliver value effectively.

How can we address the increasing complexity of data engineering projects? With an owned platform engineering infrastructure.

## What is Platform Engineering?
>  Platform engineering is a practice to enable self-service capabilities to engineering teams in response to the growing complexity of modern cloud-native architectures and the modern data stack.

It is the discipline of designing and building reusable tools and self-service capabilities with automated infrastructure operations for multiple engineering teams, leaving users to focus on value delivery as much as possible.

The goal of the platform engineering team is to build an internal developer platform. This platform becomes the central access point for developers in the day-by-day job. Realizing its practicality, many organizations are starting to create their own platform engineering practice.

Platform engineers facilitate interactions between data engineers and the underlying infrastructure, collect feedback, and iterate. Therefore, the platform engineering team:

* Follows a product approach to ensure that the internal developer platform is meeting the needs of its users and is adopted across the organization.

* Conducts user research, creates a product roadmap, solicits regular feedback, iterates, and markets the platform to its customers and the developers within the organization.

* Solicits regular feedback from the developers allowing the team to iterate and improve the platform continually. Your engineers must love the platform in the end.

* Markets the platform effectively to its customers, the data engineers, which is crucial to its success. Developers need to understand the value of the platform and how it can benefit them.

## Unlock productivity with Platform Engineering

The advantages of effective internal developer platforms should be clear at this point:

**1. Alignment**

By defining the infrastructures, technologies, and best practices supported by an internal developer platform, engineering teams will be aligned on the practices established within the organization. This will give you an overview of the tech ecosystem, reduce fragmentation across tech stacks, and streamline the platform engineering journey.

**2. Self-service**

An Internal Developer Platform provides development teams with the necessary tools to complete their tasks without having to contact the operations team.

**3. Composable**

By simplifying interaction with the infrastructure, the underlying internal developer platform allows developers to deploy modular software without worrying about orchestration and the complexities of data architectures.

**4. Reuse**

Modules can be easily reused in other products, accelerating the creation of new use cases. A software catalogue can be created which together with the internal developer platform facilitates the discovery of existing components.

**5. Data Governance and compliance**

Defining a build process phase [allows policies to become automatically applied](https://www.agilelab.it/white-paper-lifecycle-computational-policy) at deploy-time. No more manual checks. Enabling automated governance means building trust between teams.

But we have seen how data engineering projects can require a higher cognitive load than software engineering projects. How are these differences reflected in implementing an internal developer platform for elite data engineers?

An internal developer platform enables a successful platform engineering practice. To do this, it must:

* Enforce best data management practices through standardization and embedded workflows. Computational policies can also help in this direction: all entities built through the platform must have fundamental elements in place (e.g., documentation, versioning, data contracts, compliance, SLA).

* Provide a set of reusable building blocks that enable data engineers to build, deploy and orchestrate data pipelines quickly and easily. Building blocks also include DataOps tools for data quality, monitoring, application development, etc.

* [Automate infrastructure tasks such as provisioning](https://www.agilelab.it/white-paper-automating-complex-provisioning) and monitoring. No more configuration hell.

* Breaking change detection mechanisms. Data that is tracked by the platform should be constantly monitored and the platform should inform consumers whenever there is a breaking change in the data contract.

* Implement internal developer platform capabilities that provide observability and monitoring for developers to quickly identify and remediate issues. This reduces the time required to debug and troubleshoot applications and data pipelines.

* A successful platform engineering practice requires the platform to be built with a product approach, prioritizing usability, and developer experience. This includes conducting user research, creating a product roadmap, soliciting feedback, and iterating on the platform to improve its effectiveness and usability.

* Foster a culture of collaboration and knowledge sharing within the platform engineering team and across the organization. This includes creating a community of practice around the platform, providing documentation, and training resources, and encouraging engineers to share their knowledge and experiences.

By implementing these key aspects, an effective modern platform engineering practice can significantly reduce the cognitive load of engineers and improve their productivity.
>  The advantages of Internal Developer Platforms include: alignment, self-service capability, composability, reusability, and data governance and compliance.

## Wrap up

We have seen how Platform Engineering can reduce the amount of cognitive load for data engineers. In the end, everyone can benefit from internal developer platforms:

* **For engineering managers**

It increases quality standards and best practices across the organization and several technologies and can help you manage your whole tech ecosystem, from migrations to policy compliance. It also reduces time to market and costs to build a data-driven use case with high-quality standards.

* **For end users (data engineers)**

The platform engineering infrastructure makes it fast and simple to build software components in a standardized way, and it provides a central place to manage all artefacts (software, metadata, documentation, data).

* **For architects and CTOs**

It increases the ability to innovate, because of the low friction between practices, processes, and technology. It opens up the possibility to replace and modify the technology landscape without touching the implementation.

* **For governance teams**

It increases the quantity, quality, and completeness of metadata and governance artefacts, reducing the human bottleneck and related costs.

* **For everyone**

It’s a consistent experience that ties all your infrastructure tooling, resources, standards, owners, contributors, and administrators together in one place.

Platform engineers should focus on the internal developer platform’s extensibility and scalability so that it is easy to integrate new tools and services, as well as extend the functionality of existing ones. This scaling will increase the productivity of multiple engineering teams.

In conclusion, modern platform engineering plays a vital role in reducing the cognitive load for data engineers and improving their productivity. Internal developer platforms enable focus on value delivery by streamlining processes, enforcing best practices, and automating tasks. Successful platform engineering teams build reusable common technologies and tools to prioritize usability, collaboration, and knowledge sharing. They thus set up their organizations for long-term success.


