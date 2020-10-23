---
title: 服务运行状况和连续性
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-service-health
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0483499d-8972-4a8f-97bd-b82f5b138991
description: Microsoft 管理员可以查看服务的状态，并了解何时安排了维护。 服务运行状况信息随时通过登录提供。
ms.openlocfilehash: 3a5c2680a68a437e69cc7994a1e519fae957dc2a
ms.sourcegitcommit: 9610e71d9e64a2bb0ffdfed8cc7ad51f8829905a
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/22/2020
ms.locfileid: "48661250"
---
# <a name="service-health-and-continuity"></a>服务运行状况和连续性

Microsoft 管理员可以查看服务的状态，并了解何时安排了维护。 服务运行状况信息随时通过登录提供。
  
> [!NOTE]
> 如果正在使用由世纪互联运营的 Office 365，则下面的某些信息可能不适用。 请转为参阅[世纪互联服务级别协议](https://www.21vbluecloud.com/office365/O365-SLA/)。 
  
## <a name="view-status-of-services"></a>查看服务的状态

"服务运行状况" 部分显示服务的当前状态以及服务中断和中断的详细信息。 计划的维护信息在邮件中心提供。 有关详细信息，请参阅[查看服务状态](https://docs.microsoft.com/office365/enterprise/view-service-health)。 
  
## <a name="service-incidents"></a>服务事件

服务事件是影响服务交付的事件。 服务事件可能是由 Microsoft 数据中心中的硬件或软件故障、客户与 Microsoft 之间的故障网络连接或主要的数据中心挑战（如火灾、洪水或区域灾难）引起的。 可以使用 Microsoft 技术和流程解决方案，在很短时间内解决大部分服务事件。 然而，一些服务事件更加严重，并会导致长期中断。
  
有两种类型的通知关于服务可能不可用的次数：
  
- **计划的维护事件：** 计划内维护是对基础结构和软件应用程序的定期 Microsoft 启动的服务更新。 计划内维护通知通知客户可能会影响 Microsoft 服务功能的服务工作。 通过 Microsoft 365 管理中心上的消息中心，在所有计划维护之前，客户收到的通知不会超过五天。 Microsoft 通常会在服务使用情况在其基于区域时间区域的最低阶段时规划维护时间。 
    
- **计划外停机时间：** 当其中一个服务不可用或未响应时，将发生计划外服务事件。 

### <a name="recent-worldwide-uptimes"></a>最近的全球保障

移动到云服务并不意味着能够知道即将发生的情况。 在 Office 365 中，它不会。 我们在操作中的目标是透明的，因此您可以监视服务的状态，跟踪问题，并提供可用性的历史视图。 下表显示了最近的全球正常运行时间数据。

**2020**

| Q1 | 季 | 3 | 起 |
|:-----|:-----|:-----|:-----|
| 99.98% <br/> | 99.99%<br/> | 99.97%<br/> |<br/> |

<br>

**2019**

| Q1 | 季 | 3 | 起 |
|:-----|:-----|:-----|:-----|
| 99.97% <br/> | 99.97% <br/> | 99.98% <br/> | 99.98% <br/> |

<br>

**2018**

| Q1 | 季 | 3 | 起 |
|:-----|:-----|:-----|:-----|
| 99.99% <br/> | 99.98% <br/> | 99.97% <br/> | 99.98% <br/> |

<br>

**2017**

| Q1 | 季 | 3 | 起 |
|:-----|:-----|:-----|:-----|
| 99.99% <br/> | 99.97% <br/> | 99.98% <br/> | 99.99% <br/> |

## <a name="notification-policy"></a>通知策略

当服务事件发生时，Microsoft 意识到及时、定向和准确的通信对客户非常重要。 Microsoft 在 Microsoft 365 管理中心 (SHD) 更新租户特定的服务运行状况仪表板，从而通知管理员。 服务事件更新在每小时节奏上提供，如果需要不同的节奏，则会在 SHD 通信发布中进行说明。 
  
## <a name="service-health-communication-channels"></a>服务运行状况通信通道

### <a name="admin-app"></a>管理应用程序

组织管理员的管理员应用程序让你能够在旅途中连接到你的组织的 Microsoft 服务状态。 Microsoft 管理员能够从其移动设备查看服务运行状况信息和维护状态更新。 有关详细信息，请访问[管理应用常见问题解答](https://docs.microsoft.com/office365/admin/admin-overview/admin-mobile-app)。
  
### <a name="office-365-management-pack-for-microsoft-system-center-2012-r2"></a>Office 365 Management Pack for Microsoft System Center 2012 R2

Microsoft System Center 是一个集成管理平台，可以帮助你管理数据中心、客户端设备和混合云 IT 环境。 使用 System Center 的 Microsoft 管理员现在可以选择导入 Office 365 管理包，这样他们就可以在 System Center 中查看 Operations Manager 中的所有服务通信。 使用此工具，可以访问已订阅服务的状态、未解决和已解决的服务事件以及消息中心通信。 有关详细信息，请在 Microsoft 下载中心获取 [适用于 Office 365 的 Microsoft System Center 管理包](https://www.microsoft.com/download/details.aspx?id=43708) 。 
  
### <a name="office-365-service-communications-api"></a>Office 365 服务通信 API

Office 365 服务通信 API 允许您按所需的方式访问服务通信。 使用此 API，您可以创建或连接工具以实现服务通信，从而可能简化您监视环境的方式。 服务通信 API 允许您监视环境中的以下项：
  
- 实时服务运行状况
    
- 消息中心通信
    
有关详细信息，请参阅 [Office 365 服务通信 API 参考](https://docs.microsoft.com/office/office-365-management-api/office-365-service-communications-api-reference)。 
  
## <a name="post-incident-reviews"></a>事后评审

Microsoft 致力于持续改进，包括分析影响客户的计划外服务事件，以最大限度地减少此类事件的再发生次数。 
  
计划外服务事件定义为影响服务使用情况的多租户服务中断（由我们的服务级别协议 (Sla) 定义），并在服务运行状况仪表板中声明为这样。
  
 对于在大量组织中有广泛且显著影响的未计划客户影响的服务事件，在事件解决的48小时内，将通过您的服务运行状况仪表板 (PIR) 提供初步的后续审核，并在五个工作日内完成最终 PIR。 详细的 PIR 报告包括： 
  
- 用户体验和客户影响
    
- 事件开始日期和结束日期/时间
    
- 影响和解决方法的详细日程表
    
- 根本原因分析以及为持续改进采取的操作
    
对于所有其他服务事件，服务运行状况仪表板将提供事件结束摘要，包括事件的最终摘要、初步根源、开始和结束时间以及详细介绍后续步骤的信息。 对于此类服务事件，不会生成 PIR。 
  
## <a name="service-continuity"></a>服务连续性

Microsoft 产品通过高度强健的系统提供，可帮助保持最佳服务性能。 服务连续性设置是系统设计的一部分。 这些设置使 Microsoft 能够快速从意外事件（如硬件或应用程序故障、数据损坏或其他影响用户的事件）进行恢复。 这些服务连续性解决方案还适用于灾难性中断（例如，自然灾害或 Microsoft 数据中心内的事件导致整个数据中心无法运营）。
  
请注意，从灾难性故障恢复后，可能需要经过一段时间才能还原服务的完整数据中心冗余。 例如，如果数据中心 1 出现故障，则服务通过数据中心 2 的资源进行还原。 不过，可能需要经过一段时间，数据中心 2 中的服务才会获得服务连续性支持（要么通过数据中心 1 中已还原的资源获得，要么通过数据中心 3 中的新资源获得）。 在这段时间，Microsoft [服务级别协议](service-level-agreement.md) (SLA) 适用。 由世纪互联运营的 Office 365 具有不同的 SLA。 有关详细信息，请参阅 [世纪互联网站](https://www.21vbluecloud.com/office365/O365-SLA/)。 
  
## <a name="ensuring-data-availability"></a>确保数据可用性

Microsoft 可以通过以下功能确保客户数据随时可用：
  
- **数据存储和冗余：** 客户数据存储在具有强大数据保护功能的冗余环境中，以支持可用性、业务连续性和快速恢复。实施了多级数据冗余，从冗余磁盘到防止本地磁盘故障，从完整的持续数据复制到地理分散的数据中心。 
    
- **数据监控：** Microsoft 服务通过监视维护高级别的性能： 
    
  - Databases
    
  - 阻塞的进程
    
  - 数据包丢失
    
  - 进程排队
    
  - 查询延迟
    
- **完成预防性维护：** 预防性维护包括数据库一致性检查、定期数据压缩和错误日志检查。 
    
## <a name="support"></a>支持

Microsoft 开发和运营团队通过专用的支持组织进行补充，这在为客户提供业务连续性方面起着重要作用。 支持员工拥有深厚的服务及其相关应用程序的知识，并可直接接触架构、开发和测试方面的 Microsoft 专家。
  
支持组织与运营和产品团队紧密合作，提供快速的解决时间，并提供倾听客户意见的渠道。来自客户的反馈为计划、开发和运营流程提供输入。
  
- **在线问题跟踪：** 客户需要知道他们的问题正在得到解决，同时需要能够跟踪及时解决。 Microsoft 365 管理中心提供了用于支持的单个基于 web 的界面。 Customers can use the portal to add and monitor service requests and receive feedback from Microsoft support teams. 
    
- **自助，由持续员工支持提供支持：** Microsoft 提供了范围广泛的自助资源和工具，可帮助客户解决服务相关问题，而无需 Microsoft 支持。 
    
在客户输入服务请求之前，他们可以访问知识库文章和常见问题，其中提供了最常见问题的立即帮助。我们以最新信息持续更新这些资源，通过提供已知问题的解决方案帮助避免延迟。然而，当出现的问题需要支持专业人员帮助时，员工成员可以通过电话和管理门户每周 7 天、每天 24 小时提供立即帮助。
  
有关支持的详细信息，请参阅 [支持](support.md) 文章。 
  
## <a name="feature-availability"></a>功能可用性

若要查看各个计划的功能可用性，请参阅 [Microsoft 365 And Office 365 platform service description](office-365-platform-service-description.md)。
  