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
description: Microsoft 管理员可以查看服务的状态，并查明何时安排维护。 服务运行状况信息随时可供登录使用。
ms.openlocfilehash: 497568f54fc5a761278902eb26e92bc52789c9b5
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/24/2021
ms.locfileid: "59672963"
---
# <a name="service-health-and-continuity"></a>服务运行状况和连续性

Microsoft 管理员可以查看服务的状态，并查明何时安排维护。 服务运行状况信息随时可供登录使用。
  
> [!NOTE]
> 如果正在使用由世纪互联运营的 Office 365，则下面的某些信息可能不适用。请转为参阅[世纪互联服务级别协议](https://www.21vbluecloud.com/office365/O365-SLA/)。 
  
## <a name="view-status-of-services"></a>查看服务状态

"服务运行状况"部分显示服务的当前状态，以及有关服务中断和中断的详细信息。 消息中心提供计划的维护信息。 有关详细信息，请参阅[查看服务状态](/office365/enterprise/view-service-health)。 
  
## <a name="service-incidents"></a>服务事件

服务事件是影响服务交付的事件。 服务事件可能是由 Microsoft 数据中心中的硬件或软件故障、客户与 Microsoft 之间的网络连接错误或主要数据中心挑战（如火灾、淹没或区域灾难）导致的。 可以使用 Microsoft 技术和流程解决方案，在很短时间内解决大部分服务事件。 然而，一些服务事件更加严重，并会导致长期中断。
  
有两种类型的有关服务不可用时间的通知：
  
- **计划的维护事件：** 计划维护是 Microsoft 启动的对基础结构和软件应用程序的常规服务更新。 计划维护通知会告知客户可能影响 Microsoft 服务功能的服务工作。 客户将提前 5 天通过邮件中心通知所有计划维护Microsoft 365 管理中心。 Microsoft 通常会针对服务使用率在基于区域时区时最低的时间规划维护。 

- **计划外停机：** 当其中一个服务不可用或无响应时，将发生计划外服务事件。 

### <a name="recent-worldwide-uptimes"></a>最近的全球运行时间

迁移到云服务不应意味着失去了解所运行功能的能力。 使用 Office 365，则不能。 我们的目标是在操作中保持透明，以便你可以监视服务状态、跟踪问题，并拥有可用性的历史视图。 下表显示了最近的全球正常运行时间数据。

**2021**

| 问题 1 | 问题 2 | 问题 3 | 问题 4 |
|:-----|:-----|:-----|:-----|
| 99.97%  | 99.98% | | |

<br>

**2020**

| 问题 1 | 问题 2 | 问题 3 | 问题 4 |
|:-----|:-----|:-----|:-----|
| 99.98% | 99.99% | 99.97% | 99.97% |

<br>

**2019**

| 问题 1 | 问题 2 | 问题 3 | 问题 4 |
|:-----|:-----|:-----|:-----|
| 99.97% | 99.97% | 99.98% | 99.98% |

<br>

**2018**

| 问题 1 | 问题 2 | 问题 3 | 问题 4 |
|:-----|:-----|:-----|:-----|
| 99.99% | 99.98% | 99.97% | 99.98% |

<br>

**2017**

| 问题 1 | 问题 2 | 问题 3 | 问题 4 |
|:-----|:-----|:-----|:-----|
| 99.99% | 99.97% | 99.98% | 99.99% |

## <a name="notification-policy"></a>通知策略

当服务事件发生时，Microsoft 意识到及时、定向和准确的通信对客户非常重要。 Microsoft 通知管理员，具体操作是更新租户特定的服务运行状况仪表板 (SHD) SHD Microsoft 365 管理中心。 服务事件更新按每小时提供一次，或者如果需要其他节奏，将在 SHD 通信发布中说明。 
  
## <a name="service-health-communication-channels"></a>服务运行状况通信通道

### <a name="admin-app"></a>管理员应用

组织管理员管理应用使你可以随处连接到组织的 Microsoft 服务状态。 Microsoft 管理员将能够在其移动设备上查看服务运行状况信息和维护状态更新。 有关详细信息，请访问[管理应用常见问题解答](/office365/admin/admin-overview/admin-mobile-app)。
  
### <a name="office-365-management-pack-for-microsoft-system-center-2012-r2"></a>Office 365 Management Pack for Microsoft System Center 2012 R2

Microsoft System Center 是一个集成管理平台，可以帮助你管理数据中心、客户端设备和混合云 IT 环境。 现在，使用 System Center 的 Microsoft 管理员可以选择导入 Office 365 管理包，这样他们可以查看 System Center 中 Operations Manager 内的所有服务通信。 使用此工具，可以访问已订阅服务的状态、未解决和已解决的服务事件以及消息中心通信。 有关详细信息，请从[Microsoft 下载System Center Microsoft Office 365](https://www.microsoft.com/download/details.aspx?id=43708) Microsoft 管理包。 
  
### <a name="office-365-service-communications-api"></a>Office 365 服务通信 API

the Office 365 Service Communications API lets you access service communications the way you want. 通过此 API，你可以创建工具或将其连接到服务通信，从而可能简化你的环境监视方式。 服务通信 API 允许你监视你的环境的以下项目：
  
- 实时服务运行状况

- 消息中心通信

有关详细信息，请参阅 Office 365[服务通信 API 参考](/office/office-365-management-api/office-365-service-communications-api-reference)。 
  
## <a name="post-incident-reviews"></a>事后评审

Microsoft 致力于持续改进，包括分析影响客户的计划外服务事件，以最大限度地减少此类事件的再发生次数。 
  
计划外服务事件定义为多租户服务中断，这些中断会影响服务使用情况，如我们的服务级别协议 (SLA) 所定义，并且已在服务运行状况仪表板上声明为此类。
  
 对于影响客户的计划外服务事件（这些事件对大量组织产生广泛且显著的影响）来说，在事件解决后的 48 小时内，通过服务运行状况仪表板提供初步事件后评审 (PIR) ，在 5 个工作日内通过最终 PIR。 详细 PIR 报告包括： 
  
- 用户体验和客户影响

- 事件开始日期和结束日期/时间

- 影响和解决方案措施的详细日程表

- 根本原因分析以及为持续改进采取的操作

对于所有其他服务事件，服务运行状况仪表板将提供事件关闭摘要，包括事件的最终摘要、初步的根本原因、开始时间和结束时间，以及详细说明下一步的信息。 对于此类服务事件，不会生成 PIR。 
  
## <a name="service-continuity"></a>服务连续性

Microsoft 产品由具有高可用性的系统提供，有助于保持服务性能的峰值。 服务连续性设置是系统设计的一部分。 通过这些设置，Microsoft 可以快速从意外事件（如硬件或应用程序故障、数据损坏或其他影响用户的事件）中恢复。 这些服务连续性解决方案还适用于灾难性中断（例如，自然灾害或 Microsoft 数据中心内的事件导致整个数据中心无法运营）。
  
请注意，从灾难性故障恢复后，可能需要经过一段时间才能还原服务的完整数据中心冗余。 例如，如果数据中心 1 出现故障，则服务通过数据中心 2 的资源进行还原。 不过，可能需要经过一段时间，数据中心 2 中的服务才会获得服务连续性支持（要么通过数据中心 1 中已还原的资源获得，要么通过数据中心 3 中的新资源获得）。 Microsoft [服务级别协议](service-level-agreement.md) (SLA) 在此期间适用。 由世纪互联运营的 Office 365 具有不同的 SLA。 有关详细信息，请参阅世纪互联网 [网站](https://www.21vbluecloud.com/office365/O365-SLA/)。 
  
## <a name="ensuring-data-availability"></a>确保数据可用性

Microsoft 可以通过以下功能确保客户数据随时可用：
  
- **数据存储和冗余：** 客户数据存储在具有强大数据保护功能的冗余环境中，以支持可用性、业务连续性和快速恢复。实施了多级数据冗余，从冗余磁盘到防止本地磁盘故障，从完整的持续数据复制到地理分散的数据中心。 

- **数据监视：Microsoft 服务** 监视来保持高级别的性能： 

  - Databases

  - 阻塞的进程

  - 数据包丢失

  - 进程排队

  - 查询延迟

- **完成预防性维护：** 预防性维护包括数据库一致性检查、定期数据压缩和错误日志检查。 

## <a name="support"></a>支持

Microsoft 开发和运营团队由专门的支持组织提供补充，它在为客户提供业务连续性方面起到重要作用。 支持员工拥有深厚的服务及其相关应用程序的知识，并可直接接触架构、开发和测试方面的 Microsoft 专家。
  
支持组织与运营和产品团队紧密合作，提供快速的解决时间，并提供倾听客户意见的渠道。来自客户的反馈为计划、开发和运营流程提供输入。
  
- **在线问题跟踪：** 客户需要知道他们的问题正在得到解决，同时需要能够跟踪及时解决。 The Microsoft 365 管理中心 provides a single web-based interface for support. Customers can use the portal to add and monitor service requests and receive feedback from Microsoft support teams. 

- **自助，由持续员工支持提供支持：** Microsoft 提供各种自助资源和工具，帮助客户解决与服务相关的问题，而无需 Microsoft 支持。 

在客户输入服务请求之前，他们可以访问知识库文章和常见问题，其中提供了最常见问题的立即帮助。我们以最新信息持续更新这些资源，通过提供已知问题的解决方案帮助避免延迟。然而，当出现的问题需要支持专业人员帮助时，员工成员可以通过电话和管理门户每周 7 天、每天 24 小时提供立即帮助。
  
有关支持详细信息， [请参阅支持文章](support.md) 。 
  
## <a name="feature-availability"></a>功能可用性

若要查看各个计划的功能可用性，请参阅 [Microsoft 365 和 Office 365 平台服务](office-365-platform-service-description.md)说明。
