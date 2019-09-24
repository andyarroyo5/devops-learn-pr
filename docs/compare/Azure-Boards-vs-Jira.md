---
title: Azure Boards vs Jira
description: Explanation of Azure Boards and how it compares to Atlassian Jira
ms.prod: devops
ms.technology: devops-learn
ms.topic: conceptual
ms.manager: douge
ms.author: davemcki
ms.date: 3/11/2019
---

# Azure Boards vs Jira Software

Azure DevOps is a cloud-based, open, and integrated platform for enterprise-scale DevOps. Azure Boards is the specific Azure DevOps service focused on agile project management.

To compare to Jira Software, try Azure Boards for free and get:

- Access for up to five users
- Access for an unlimited number of stakeholders
- Dashboards, portfolio management and other Jira add-ons included
- Access to other Azure DevOps services
  (e.g., [Azure Repos](https://azure.microsoft.com/services/devops/repos),
  [Azure Pipelines](https://azure.com/pipelines), etc.)

[Sign-up here](https://azure.microsoft.com/services/devops/boards) and compare for yourself _for FREE_!

## Get the ease and consistency of an integrated system

Azure DevOps provides end-to-end traceability, easy administration, and consistent security and licensing. Whether you host it or
Microsoft does, Azure DevOps provides consistent tools and a common marketplace. Adopt as much or as little of Azure DevOps as
you wish and easily integrate with other development tools across all popular development platforms.

## Compare Azure Boards vs. Jira Software capabilities

| Feature Comparison                   | Azure Boards | Jira Software | Notes                                                                                                                                                                                                                                                                                                                                                                            |
| ------------------------------------ | :----------: | :-----------: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Agile Process                        |      Y       |       Y       | Azure Boards supports basic, agile, scrum, and cmmi with the ability to switch between.                                                                                                                                                                                                                                                                                          |
| Support for enterprise customization |      Y       |       N       | Jira allows for customization at the project level while Azure Boards allows you customize a process that can be used across many projects.                                                                                                                                                                                                                                      |
| Kanban                               |      Y       |       Y       |                                                                                                                                                                                                                                                                                                                                                                                  |
| Backlogs                             |      Y       |       Y       | Jira does not support hierarchical drill-down and drill-up views in the backlog. Jira supports 3 backlog levels while Azure Boards allows 5.                                                                                                                                                                                                                                     |
| Sprints                              |      Y       |       Y       |
| Roadmaps and Portfolio Planning      |      \*      |      \*       | Portfolio for Jira and Jira Align are available as a separate add-on at additional cost. Azure Boards has the [Delivery Plans](https://marketplace.visualstudio.com/items?itemName=ms.vss-plans) and [Portfolio Plans](https://marketplace.visualstudio.com/items?itemName=ms-devlabs.workitem-feature-timeline-extension) extensions available on the marketplace for no costs. |
| Search                               |      Y       |       Y       |                                                                                                                                                                                                                                                                                                                                                                                  |
| Integration with Test                |      Y       |       N       | Azure Boards supports tight integration between work items and test plans.                                                                                                                                                                                                                                                                                                       |
| Enterprise query support             |      Y       |       N       | Azure Boards supports cross project queries. Azure Boards queries can generate charts that can be put on dashboards.                                                                                                                                                                                                                                                             |
| Reporting & Analytics                |      Y       |      \*       | Azure Boards supports both simple and complex reporting using dashboard widgets, queries, and Power BI reporting. Jira requires purchase of third-party solutions through its marketplace for enterprise analytics and reporting.                                                                                                                                                |
| Dashboard support                    |      Y       |      Y\*      | Jira does not support the breadth of ALM/DevOps life cycle widgets (e.g., build, release, monitoring).                                                                                                                                                                                                                                                                           |
| Extensibility & Marketplace          |      Y       |       Y       | Choose from a [library](https://marketplace.visualstudio.com/) of community supported extensions or [create your own](https://docs.microsoft.com/en-us/azure/devops/marketplace-extensibility/index?view=azure-devops).                                                                                                                                                          |

<!--
| Question                                                                             | Azure Boards | Jira Software | Notes                                                                                                                                                         |
| ------------------------------------------------------------------------------------ | :----------: | :-----------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| _DEVOPS TRACEABILITY AND INTEGRATION_                                                |              |               |                                                                                                                                                               |
| Trace work through the entire lifecycle to deployed environments                     |      Y       |      \*       | Jira requires purchase of multiple Atlassian, community, and/or third-party products.                                                                         |
| Trace code changes and reviews to deployment environments                            |      Y       |      \*       | Jira requires purchase of multiple Atlassian, community, and/or third-party products.                                                                         |
| Trace builds into releases and deployment environments                               |      Y       |      \*       | Jira requires purchase of multiple Atlassian, community, and/or third-party products.                                                                         |
| Trace runtime telemetry back into the work stream                                    |      \*      |       N       | Azure DevOps provides this capability by integrating with Azure Application Insights for on-premises or cloud-based apps.                                     |
| Use as much or as little as you need                                                 |      Y       |       Y       |                                                                                                                                                               |
| _PLATFORM SUPPORT_                                                                   |              |               |                                                                                                                                                               |
| Scales to support thousands of users                                                 |      Y       |      \*       | Jira Cloud only supports up to 2000 users. Other Atlassian products scale better.                                                                             |
| Easy to install, configure, and manage                                               |      Y       |      \*       | Atlassian provides a set of tools that each require separate licensing, configuration, and administration.                                                    |
| Cloud-hosted, managed SaaS option                                                    |      Y       |       Y       |                                                                                                                                                               |
| On-premises installation option                                                      |      Y       |      \*       | Jira requires licensing, installation, configuration, and administration of multiple separate Atlassian products.                                             |
| Marketplace provides easy extensibility through community and third-party extensions |      Y       |       Y       |                                                                                                                                                               |
| Completely free for various user profiles, regardless of user count                  |      Y       |      \*       | Free for some Atlassian products but not for others.                                                                                                          |
| Supports custom work item types and fields                                           |      Y       |       Y       |                                                                                                                                                               |
| Supports custom project-scoped link types between work items                         |      Y       |      \*       | Jira provides custom link types which must be globally scoped and cannot be filtered to individuall projects.                                                 |
| _IDE INTEGRATION_                                                                    |              |               | All IDEs support Git repositories. Items listed cover additional platform integration (i.e., work items, pull requests, 2FA).                                 |
| Visual Studio                                                                        |      Y       |      \*       | Jira and Bitbucket plugins are provided by a third party.                                                                                                     |
| Visual Studio Code                                                                   |      Y       |      \*       | Jira plugin in provided by a third party.                                                                                                                     |
| Eclipse                                                                              |      Y       |       N       |                                                                                                                                                               |
| JetBrains IDE Family (IntelliJ IDEA, Android Studio, etc.)                           |      Y       |      \*       | Jira plugin is provided by a third party. Bitbucket plugin is provided by Atlassian Labs.                                                                     |
| XCode                                                                                |      \*      |      \*       | Apple doesn't allow IDE extensions. Version control integration is supported with Git repositories.                                                           |
| _PORTFOLIO MANAGEMENT_                                                               |              |               |                                                                                                                                                               |
| Create a roadmap across teams                                                        |      Y       |      \*       | Portfolio for Jira is available as a separate add-on at additional cost.                                                                                      |
| Multiple backlog levels (e.g., epics, features, stories)                             |      Y       |       Y       | Jira supports up to 3 backlog levels; Azure Boards supports up to 5 backlog levels.                                                                           |
| _BACKLOG MANAGEMENT_                                                                 |              |               |                                                                                                                                                               |
| Modern, efficient, browser-based backlog management                                  |      Y       |       Y       |                                                                                                                                                               |
| Supports both requirement (e.g., stories) and bugs in the product backlog            |      Y       |       Y       |                                                                                                                                                               |
| Customizable backlog columns                                                         |      Y       |       Y       |                                                                                                                                                               |
| Hierarchical drill-down and drill-up available in the backlog                        |      Y       |       N       |                                                                                                                                                               |
| _SCRUM AND AGILE_                                                                    |              |               |                                                                                                                                                               |
| Sprint-level backlog                                                                 |      Y       |       Y       |                                                                                                                                                               |
| Sprint capacity planning tools                                                       |      Y       |       Y       |                                                                                                                                                               |
| Forecasting tools based on velocity and effort to help plan sprint releases          |      Y       |       Y       |                                                                                                                                                               |
| Support for scaled agile capabilities such as SAFe                                   |      Y       |      \*       | The Jira whiteaper on the topic indicates additional purchases are required for SAFe (Portfolio for Jira, Confluence, HipChat) are required for SAFe support. |  |
| Burndown to show progress within a sprint                                            |      Y       |       Y       |                                                                                                                                                               |
| Velocity chart to measure team velocity per sprint                                   |      Y       |       Y       |                                                                                                                                                               |
| _KANBAN AND LEAN_                                                                    |              |               |                                                                                                                                                               |
| Customizable Kanban board states and swim lanes                                      |      Y       |       Y       |                                                                                                                                                               |
| Shows children on card                                                               |      Y       |      \*       | Jira allows “subtasks” on cards but doesn’t understand a formal hierarchy of children.                                                                        |
| Shows test cases on card                                                             |      Y       |      \*       | Jira requires purchase of third-party solutions through its marketplace.                                                                                      |
| Conditional styling for cards on the Kanban board                                    |      Y       |       Y       |                                                                                                                                                               |
| Cumulative flow diagram                                                              |      Y       |       Y       |                                                                                                                                                               |
| Cycle time and lead time graphs                                                      |      Y       |       Y       |                                                                                                                                                               |
| _DASHBOARDS AND REPORTING_                                                           |              |               |                                                                                                                                                               |
| Customizable dashboards                                                              |      Y       |       Y       |                                                                                                                                                               |
| Multiple dashboards per team                                                         |      Y       |       Y       |                                                                                                                                                               |
| Additional dashboard widgets available from a marketplace                            |      Y       |       Y       |                                                                                                                                                               |
| Create custom dashboard widgets                                                      |      Y       |       Y       |                                                                                                                                                               |
| Dashboard breadth of ALM/DevOps lifecycle widgets (e.g., build, release, monitoring) |      Y       |       N       |                                                                                                                                                               |
| Custom reporting available through Power BI or other OData-compatible analysis tools |      Y       |      \*       | Jira requires purchase of third-party solutions through its marketplace.                                                                                      |
-->

## Align across the enterprise while giving teams autonomy

Track at a high level across the enterprise while teams track the details using a multi-level backlog built into Azure DevOps. Different teams can customize their dashboards and Kanban workflows while still enabling roll-ups to the enterprise level.

## Spend less to get more

Access for the first five Azure DevOps users is free, and the
cost for 20 additional users is \$110 per month vs. \$140 for Jira Software. The
price gap grows as you add users and features. Azure DevOps provides more
built-in functionality and requires fewer third-party purchases than Jira
Software. As an integrated suite, Azure DevOps eliminates the
need for separate teams to manage system integrations or different license and
purchase mechanisms, security models, and administrative tools and skillsets.

[This page](https://azure.microsoft.com/pricing/details/devops/azure-devops-services/)
provides prices for unlimited Azure Boards and Azure Repos based on common
user counts. Like Jira, you can ajust to any user count and are billed on a monthly basis.

## Easily migrate from Jira Software

Migrate from Jira Software to Azure DevOps in just a few minutes.
Export from Jira Software to Microsoft Excel and then use the free
[Excel add-in](https://docs.microsoft.com/azure/devops/boards/backlogs/office/track-work)
to import into Azure Boards.

You can also use free community tools such as Solidify's
[Jira to Azure DevOps work item migration tool](https://marketplace.visualstudio.com/items?itemName=solidify-labs.jira-devops-migration)
or perform high-fidelity migrations and even _synchronization_ using partner tools such as
[TFS4Jira](https://marketplace.visualstudio.com/items?itemName=vs-publisher-703379.TFS4JIRA).
