---
title: 服务运行状况和连续性
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-service-health
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: 0483499d-8972-4a8f-97bd-b82f5b138991
description: Microsoft 管理员可以查看服务的状态，并了解何时计划维护。 服务运行状况信息随时可通过登录获得。
ms.openlocfilehash: 9a00f72b4cede8b9ac2b0690f194d36d32dd1906
ms.sourcegitcommit: c2d2064d8fbebbe9843a4e824860e214b0b54c58
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/04/2022
ms.locfileid: "65187493"
---
# <a name="service-health-and-continuity"></a>服务运行状况和连续性

Microsoft 管理员可以查看服务的状态，并了解何时计划维护。 服务运行状况信息随时可通过登录获得。
  
> [!NOTE]
> 如果正在使用由世纪互联运营的 Office 365，则下面的某些信息可能不适用。请转为参阅[世纪互联服务级别协议](https://www.21vbluecloud.com/office365/O365-SLA/)。 
  
## <a name="view-status-of-services"></a>查看服务状态

服务运行状况部分显示服务的当前状态以及有关服务中断和中断的详细信息。 消息中心提供计划内维护信息。 有关详细信息，请参阅[查看服务状态](/office365/enterprise/view-service-health)。 
  
## <a name="service-incidents"></a>服务事件

服务事件是影响服务交付的事件。 服务事件可能是由 Microsoft 数据中心中的硬件或软件故障、由于 Microsoft 所做的更改导致的网络连接故障，或重大数据中心挑战（如火灾、洪水或区域灾难）造成的。 由第三方服务提供商导致的中断或在客户托管环境中所做的更改不被视为服务事件。 可以使用 Microsoft 技术和流程解决方案，在很短时间内解决大部分服务事件。 然而，一些服务事件更加严重，并会导致长期中断。
  
关于服务可能不可用的时间，有两种类型的通知：
  
- **计划内维护事件：** 计划内维护是 Microsoft 对基础结构和软件应用程序的常规服务更新。 计划内维护通知告知客户可能影响 Microsoft 服务功能的服务工作。 客户在Microsoft 365 管理中心上通过消息中心提前五天收到所有计划内维护的通知。 Microsoft 通常根据区域时区规划服务使用率在历史最低时段的维护时间。

- **计划外停机时间：** 如果其中一个服务因 Microsoft 托管环境中的故障而不可用或无响应，则会发生计划外服务事件。 客户通过Microsoft 365 管理中心上的服务运行状况收到已知服务事件通知。

### <a name="recent-worldwide-uptimes"></a>最近全球运行时间

迁移到云服务并不意味着失去知道发生了什么事情的能力。 使用Microsoft 365，则不会。 我们的目标是在操作中保持透明，以便你可以监视服务状态、跟踪问题，并具有历史可用性视图。 下表显示了最近全球运行时间数据。

**2022**

| 第 1 季度 | 第 2 季度 | 第 3 季度 | Q4 |
|:-----|:-----|:-----|:-----|
| 99.97%  | - | - | -|

<br>

**2021**

| 第 1 季度 | 第 2 季度 | 第 3 季度 | Q4 |
|:-----|:-----|:-----|:-----|
| 99.97%  | 99.98% | 99.985% | 99.976%|

<br>

**2020**

| 第 1 季度 | 第 2 季度 | 第 3 季度 | Q4 |
|:-----|:-----|:-----|:-----|
| 99.98% | 99.99% | 99.97% | 99.97% |

<br>

**2019**

| 第 1 季度 | 第 2 季度 | 第 3 季度 | Q4 |
|:-----|:-----|:-----|:-----|
| 99.97% | 99.97% | 99.98% | 99.98% |

<br>

**2018**

| 第 1 季度 | 第 2 季度 | 第 3 季度 | Q4 |
|:-----|:-----|:-----|:-----|
| 99.99% | 99.98% | 99.97% | 99.98% |

<br>

**2017**

| 第 1 季度 | 第 2 季度 | 第 3 季度 | Q4 |
|:-----|:-----|:-----|:-----|
| 99.99% | 99.97% | 99.98% | 99.99% |

## <a name="notification-policy"></a>通知策略

当服务事件发生时，Microsoft 意识到及时、定向和准确的通信对客户非常重要。 Microsoft 通过Microsoft 365 管理中心上的服务运行状况直接与受影响的客户通信来通知管理员。 服务事件更新按小时节奏提供，如果需要不同的节奏，则会在 SHD 通信发布中说明。
  
## <a name="service-health-communication-channels"></a>服务运行状况通信通道

### <a name="admin-app"></a>管理应用

组织管理员的管理员应用使你能够随地连接到组织的 Microsoft 服务状态。 Microsoft 管理员将能够从其移动设备查看服务运行状况信息和维护状态更新。 有关详细信息，请访问[管理应用常见问题解答](/office365/admin/admin-overview/admin-mobile-app)。
  
### <a name="microsoft-365-management-pack-for-microsoft-system-center-operations-manager"></a>Microsoft 365 Microsoft System Center Operations Manager 的管理包

Microsoft System Center Operations Manager (SCOM) 是一个集成管理平台，可帮助你管理数据中心、客户端设备和混合云 IT 环境。 使用 SCOM 的 Microsoft 管理员可以选择导入 Microsoft 365 管理包，这使他们能够在 System Center 中查看 Operations Manager 中的所有服务通信。 使用此工具可以访问订阅服务的状态、活动和已解决的服务事件以及消息中心通信。 有关详细信息，请在 Microsoft 下载中心获取[适用于Microsoft 365的 Microsoft System Center 管理包](https://www.microsoft.com/download/details.aspx?id=103379)。
  
### <a name="microsoft-365-service-communications-api-in-graph"></a>Graph中的Microsoft 365服务通信 API

使用Microsoft 365服务通信 API 可以按所需方式访问服务通信。 使用此 API，可以创建工具或将工具连接到服务通信，从而可以简化环境的监视方式。 使用服务通信 API 可以监视环境的以下项：

- 实时服务运行状况

- 消息中心通信

有关详细信息，请参阅[Microsoft 365服务通信 API 参考](/graph/api/resources/service-communications-api-overview)。

## <a name="post-incident-reviews"></a>事后评审

Microsoft 致力于持续改进，包括分析影响客户的计划外服务事件，以最大限度地减少此类事件的再发生次数。
  
计划外服务事件定义为多租户服务中断，影响服务级别协议 (SLA) 定义的服务使用情况，并通过Microsoft 365 管理中心上的服务运行状况进行声明。
  
对于对大量组织产生广泛和明显影响的非计划客户影响服务事件，将在事件解决后的 48 小时内通过服务运行状况提供初步的事后审查 (PIR) ，然后在五个工作日内进行最终 PIR。 详细的 PIR 报表包括：
  
- 用户体验和客户影响

- 事件开始日期和结束日期/时间

- 影响和解决措施的详细时间线

- 根本原因分析以及为持续改进采取的操作

对于所有其他服务事件，Microsoft 365 管理中心上的服务运行状况页将提供事件关闭摘要，包括事件的最终摘要、根本原因、开始时间和结束时间，以及详细说明后续步骤的信息。 对于此类服务事件，不会生成 PIR。
  
## <a name="service-continuity"></a>服务连续性

Microsoft 产品/服务由高度复原的系统提供，这些系统有助于保持峰值服务性能。 服务连续性预配是系统设计的一部分。 这些规定使 Microsoft 能够从意外事件（如硬件或应用程序故障、数据损坏或其他影响用户的事件）中快速恢复。 这些服务连续性解决方案还适用于灾难性中断（例如，自然灾害或 Microsoft 数据中心内的事件导致整个数据中心无法运营）。
  
请注意，从灾难性故障恢复后，可能需要经过一段时间才能还原服务的完整数据中心冗余。 例如，如果数据中心 1 出现故障，则服务通过数据中心 2 的资源进行还原。 不过，可能需要经过一段时间，数据中心 2 中的服务才会获得服务连续性支持（要么通过数据中心 1 中已还原的资源获得，要么通过数据中心 3 中的新资源获得）。 在此期间，Microsoft [服务级别协议](service-level-agreement.md) (SLA) 适用。 由世纪互联运营的 Office 365 具有不同的 SLA。 有关详细信息，请参阅 [21Vianet 网站](https://www.21vbluecloud.com/office365/O365-SLA/)。 
  
## <a name="ensuring-data-availability"></a>确保数据可用性

Microsoft 可以通过以下功能确保客户数据随时可用：
  
- **数据存储和冗余：** 客户数据存储在具有强大数据保护功能的冗余环境中，以支持可用性、业务连续性和快速恢复。实施了多级数据冗余，从冗余磁盘到防止本地磁盘故障，从完整的持续数据复制到地理分散的数据中心。 

- **数据监视：** Microsoft 服务通过监视来保持高性能： 

  - Databases

  - 阻塞的进程

  - 数据包丢失

  - 进程排队

  - 查询延迟

- **完成预防性维护：** 预防性维护包括数据库一致性检查、定期数据压缩和错误日志检查。 

## <a name="support"></a>支持

Microsoft 开发和运营团队由专门的支持组织提供补充，在为客户提供业务连续性方面发挥着重要作用。 支持员工拥有深厚的服务及其相关应用程序的知识，并可直接接触架构、开发和测试方面的 Microsoft 专家。
  
支持组织与运营和产品团队紧密合作，提供快速的解决时间，并提供倾听客户意见的渠道。来自客户的反馈为计划、开发和运营流程提供输入。
  
- **在线问题跟踪：** 客户需要知道他们的问题正在得到解决，同时需要能够跟踪及时解决。 Microsoft 365 管理中心提供单个基于 Web 的接口以获得支持。 Customers can use the portal to add and monitor service requests and receive feedback from Microsoft support teams. 

- **自助，由持续员工支持提供支持：** Microsoft 提供了各种自助资源和工具，可帮助客户解决与服务相关的问题，而无需 Microsoft 支持。 

在客户输入服务请求之前，他们可以访问知识库文章和常见问题，其中提供了最常见问题的立即帮助。我们以最新信息持续更新这些资源，通过提供已知问题的解决方案帮助避免延迟。然而，当出现的问题需要支持专业人员帮助时，员工成员可以通过电话和管理门户每周 7 天、每天 24 小时提供立即帮助。
  
有关支持的详细信息，请参阅 [支持](support.md) 文章。 
  
## <a name="feature-availability"></a>功能可用性

若要查看各个计划的功能可用性，请参阅 [Microsoft 365 和 Office 365 平台服务](office-365-platform-service-description.md)说明。
