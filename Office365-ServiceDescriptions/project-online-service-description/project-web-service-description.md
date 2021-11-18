---
title: Microsoft Project 网页版服务说明
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: End User
ms.topic: reference
f1_keywords:
- project-web-service-description
ms.prod: office-online-server
ms.localizationpriority: medium
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: ''
description: Project是 Microsoft 最新的基于云的工作和项目管理产品/服务。 Project Web 服务提供了简单、强大的工作管理功能，以满足大多数需求和角色。
ms.openlocfilehash: 817656fb2e9a24fa8392959f6f22dfdbd9e67eec
ms.sourcegitcommit: ad4c082362428dbd29a0347058abed9e51685916
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/18/2021
ms.locfileid: "61070136"
---
# <a name="microsoft-project-for-the-web-service-description"></a>Microsoft Project 网页版服务说明

Project是 Microsoft 最新的基于云的工作和项目管理产品/服务。 Project Web 服务提供了简单、强大的工作管理功能，以满足大多数需求和角色。 Project管理员和团队成员可以使用 web Project来规划和管理任何规模的工作。

Project构建于 Microsoft Power Platform 上。 Power Platform 由 PowerApps、Power Automate、Power BI 和 Microsoft Dataverse 组成。 Project的数据存储在 Microsoft Dataverse 中。

## <a name="available-plans"></a>可用计划

Project订阅提供适用于 Web 的订阅：Project 计划 1、Project 计划 3 和 Project 计划 5。 Web 功能[Project中列出的功能](/office365/servicedescriptions/project-online-service-description/project-online-service-description#project-for-the-web-features)仅与 Web Project数据存储区的数据进行交互。 有关允许用户使用 Web Microsoft Project订阅的更多信息，请参阅[比较项目管理解决方案和成本](https://www.microsoft.com/microsoft-365/project/compare-microsoft-project-management-software)。

## <a name="feature-availability"></a>功能可用性

下表列出了跨计划Microsoft Project Web 功能的主要功能。 某些注意事项适用。 有关详细信息，请参阅脚注。 此表可能发生更改，恕不另行通知。 <br/><br/>

| 功能 | 说明 | Office 365许可证 | 计划 1 | 计划 3 | 计划 5 |
|---------|---------|---------------------|--------|--------|--------|
| **Project、任务和时间管理** |板视图 | 仅查看 | 是 | 是 | 是 |
| | 相关性 | 仅查看 | 是 | 是 | 是 |
| | 网格视图 | 仅查看 | 是 | 是 | 是 |
| | 里程碑 | 仅查看 | 是 | 是 | 是 |
| | Project 主页 | 是 | 是 | 是 | 是 |
| | 任务计划 | 仅查看 | 是 | 是 | 是 |
| | 日程表视图 (甘特图)  | 仅查看 | 是 | 是 | 是 |
| | 关键路径 | 否 | 否 | 是 | 是 |
| | 摘要任务 | 仅查看 | 是 | 是 | 是 |
| | 创建和使用任务自定义域 | 仅查看 | 是 | 是 | 是 |
| **协作** | Microsoft Teams集成 | 是 | 是 | 是 | 是 |
| | 任务对话 | 是<sup>1</sup> | 是<sup>1</sup> | 是<sup>1</sup> | 是<sup>1</sup> |
| **资源和计划管理** | Project团队设置 | 否 | 是 | 是 | 是 |
| | 创建资源请求<sup>2</sup> | 仅查看 | 仅查看 | 是 | 是 |
| | 接受预订建议<sup>2</sup> | 仅查看 | 仅查看 | 是 | 是 |
| | 创建和更新预订以满足资源请求<sup>2</sup> | 仅查看 | 仅查看 | 仅查看 | 是 |
| | 管理资源的技能/熟练程度 | 仅查看 | 仅查看 | 仅查看 | 是 |
| | 路线图 | 仅查看 | 仅查看 | 是 | 是 |
| **报告**<sup>3</sup> | 从 Web Project读取报告 | 是 | 是 | 是 | 是 |
| | 使用 Web Project创建报告 | 否 | 是 | 是 | 是 |
| **可用性** | 共同创作 | 仅查看 | 是 | 是 | 是 |
| | 图形指示器 | 仅查看 | 是 | 是 | 是 |
| **自定义和集成** | 使用开箱Project应用程序 | 仅查看 | 是 | 是 | 是 |
| | 自定义视图和表单<sup>4</sup> | 仅查看 | 是 | 是 | 是 |
| | 使用自定义列 | 仅查看 | 是 | 是 | 是 |
| | 使用自定义表<sup>5</sup> | 仅查看 | 是 | 是 | 是 |
| **Power Automate工作流和业务流程流**<sup>6</sup> | 定义和使用Power Automate数据（包括自定义表Project列）的云流 | 否 | 是 | 是 | 是 |
| | 定义Power Automate数据（包括自定义表Project列）的业务流程流。 | 否 | 否 | 是 | 是 |
| | 使用Power Automate数据的业务流程流Project流 | 否 | 是 | 是 | 是 |
| **安全性和用户管理** | Office新式组 | 是 | 是 | 是 | 是 |
| | 第三方应用 | 否 | 是 | 是 | 是 |
| | *连接Project第三方* 应用访问 Web <sup>4</sup> | 仅查看<sup>7</sup> | 是 | 是 | 是 |

<sup>1</sup>需要Microsoft Teams许可证。 <br/>
<sup>2</sup>  具有 Microsoft Project 计划 3/5 许可证 () 仅允许使用通用资源计划在项目上下文中安排 Project 表和任务表。 <br/>
<sup>3</sup>  使用 Project 报告 Web Power BI需要一个Power BI许可证。 <br/>
<sup>4</sup>  构建和使用Power Apps访问 Web 或 Project Online 客户数据的 Project 的开箱即用 Project 应用程序之外的单独 Power Apps 订阅。 <br/>
<sup>5</sup>  限制为 5 个自定义表。 <br/>
<sup>6</sup>  Power Automate内部Project仅限于应用程序Project上下文。 这意味着，对于触发器和操作，包含在流Project可以：
   - 连接应用程序使用权限内的任何Project数据源：
       - 可通过标准连接器获取的数据源。
       - Project Microsoft Dataverse 连接器访问数据。
   - 通过内置触发器/操作 (直接在 Project 应用程序内触发) 。

<sup>7</sup> 仅从 Power App 内授予仅查看权利。

## <a name="messaging"></a>消息传递

若要及时了解即将进行的更改，包括新功能和已更改的功能、计划的维护或其他重要通知，请访问消息中心。 有关详细信息，请参阅[消息中心](/microsoft-365/admin/manage/message-center)。

## <a name="licensing-terms"></a>许可条款

有关通过 Microsoft 商业批量许可计划购买的产品和服务的许可条款和条件，请参阅[产品条款网站](https://www.microsoft.com/licensing/terms/)。

### <a name="licensing-considerations"></a>许可注意事项

当你的最后一个 Project 计划 1、Project 计划 3 或 Project 计划 5 订阅过期时，Web 实例的 Project 将不会自动删除，直到你没有依赖于 Microsoft Dataverse 的活动订阅。 For Project for the web trial subscriptions， your trial instances will not be deleted until you have no active subscriptions that depend on Microsoft Dataverse.

## <a name="accessibility"></a>辅助功能

Microsoft 始终致力于确保数据的安全性以及服务的[辅助功能](https://www.microsoft.com/trust-center/compliance/accessibility)。 有关详细信息，请参阅 [Microsoft 信任中心](https://www.microsoft.com/trust-center)和 [Office 辅助功能中心](https://support.microsoft.com/office/office-accessibility-center-resources-for-people-with-disabilities-ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)。

## <a name="learn-more"></a>了解详细信息

### <a name="architecture"></a>体系结构

[Project体系结构图](/project-for-the-web/project-architecture-overview)Project适用于 Web 的服务如何与 Power Platform、Power BI 和第三方服务一起运行。 虽然" (项目组合服务) 仅在默认环境中安装，但该路线图可以显示任何支持 Project 应用的环境的项目。 the Project solution can be installed on the default， production， and sandbox Dataverse environments.

### <a name="service-considerations"></a>服务注意事项

Project当前无法用于 GCC、GCC High 和 DoD。 We're working on delivering Project for the web to you but are unable to share a firm time at this time.

### <a name="project-roadmap-and-power-automate"></a>Project路线图和Power Automate

Project路线图要求使用 Power Automate，该指南作为你的 Project 订阅的一部分进行预配。 Power Automate Web Project随附的 web 服务功能Flow应用程序部分中的 Project **** 服务计划    ****   Microsoft 365 管理中心。

### <a name="project-for-the-web-and-microsoft-dataverse"></a>Project和 Microsoft Dataverse

Project需要使用 Microsoft Dataverse 来存储其数据。 Microsoft Dataverse 数据库将预配为订阅的Project一部分。 对 Microsoft Dataverse 功能的访问权限仅限于存储和访问数据，以支持Project Web 服务。 Project所需的 Microsoft Dataverse 功能Project应用程序的"应用程序"部分中的 Common **Data Service for**    ****   Microsoft 365 管理中心。

For Project Customers with five (5) or more Project for the web licenses， you may deploy Project for the web to Power Platform Production and Sandbox environments. 点击[此处](/project-for-the-web/deploying-project)了解详细信息。

| 包含/累算的容量 | Project P1 | Project P3 | Project P5 |
|---------------------------|------------|------------|------------|
| Dataverse (Common Data Service) 数据库：包含/租户 | 3 GB | 5 GB | 5 GB |
| Dataverse 数据库：USL 数据库的累计/ (许可证)  | 50 MB | 250 MB | 250 MB |
| Dataverse 日志：包含/租户 | 2 GB | 2 GB | 2 GB |
| Dataverse 文件：包含/租户 | 20 GB | 20 GB | 20 GB |
| Dataverse 文件：Accrued/USL | 400 MB | 2 GB | 2 GB |

除了授权 Dataverse 存储容量Project还有额外的 Microsoft 订阅。 有关其他 Dataverse 存储容量权利，请参阅 [Dynamics 365](https://go.microsoft.com/fwlink/?LinkId=866544&clcid=0x409)许可指南和    [Power Apps、Power Automate 和](https://go.microsoft.com/fwlink/?LinkId=2085130&clcid=0x409)Power Virtual Agents 许可指南。

### <a name="data-backup-and-retention"></a>数据备份和保留

Project Web 服务器的数据备份和保留策略与网站Office 365。 有关详细信息，请参阅数据保留[、删除和销毁Microsoft 365。](/office365/Enterprise/office-365-data-retention-deletion-and-destruction-overview) 若要详细了解如何管理备份和还原，请参阅 [备份和还原环境](/power-platform/admin/backup-restore-environments)。 无法删除默认环境，并且不支持备份和还原。 有关环境详细信息，请参阅 [默认环境](/power-platform/admin/environments-overview#the-default-environment)。

### <a name="data-encryption"></a>数据加密

若要了解有关 Web Project中数据加密的信息，请参阅 Microsoft [Dynamics 365 中的加密](/microsoft-365/compliance/office-365-encryption-in-microsoft-dynamics-365)。

### <a name="project-for-the-web-boundaries-and-limitations"></a>Project Web 边界和限制

下表介绍了针对 Web Project的限制。

| 实体/字段 | 限制 |
|--------------|-------|
| **任务** | |
| 最大 任务的层次结构级别 | 10 个级别 |
| 最大 任务 (后续任务 + 前置) 的链接 | 20 |
| 最大 叶任务的工期 | 1250 天 |
| 最大 摘要任务的工期 | 3650 天 (10 年)  |
| 最大 可分配给任务的资源 | 20 个资源 |
| 任务支持的日期范围 | 1/1/2000 – 12/31/2149 |
| **项目** | |
| 最大 项目的总任务 | 500 |
| 最大 项目的总工期 | 3650 天 (10 年)  |
| 最大 项目的总资源 | 150 |
| 最大 项目 (后续) 的链接总数 | 600 |

## <a name="additional-resources"></a>其他资源

- [Project Web 入门指南 - Project Web |Microsoft Docs](/project-for-the-web/project-for-the-web-get-started-guide-for-admins)
- 有关最佳做法、新闻和趋势，请转到Project[博客](https://techcommunity.microsoft.com/t5/project-blog/bg-p/ProjectBlog)
