---
title: 服务运行状况和连续性
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-service-health
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0483499d-8972-4a8f-97bd-b82f5b138991
description: Microsoft Office 365 管理员可以查看服务的状态，并确定何时安排了维护。 服务运行状况信息可随时登录 Office 365。
ms.openlocfilehash: 6265dd28d03099281a9ee2540c5a775daa32108f
ms.sourcegitcommit: 637906376f304e76a32ecf889394687cb6714493
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/31/2019
ms.locfileid: "37911788"
---
# <a name="service-health-and-continuity"></a>服务运行状况和连续性

Microsoft Office 365 管理员可以查看服务的状态，并确定何时安排了维护。 服务运行状况信息可随时登录 Office 365。
  
> [!NOTE]
> 如果正在使用由世纪互联运营的 Office 365，则下面的某些信息可能不适用。 请转为参阅[世纪互联服务级别协议](https://www.21vbluecloud.com/office365/O365-SLA/)。 
  
## <a name="view-status-of-services"></a>查看服务状态

Office 365 的 "服务运行状况" 部分显示了服务的当前状态以及有关服务中断和中断的详细信息。 计划的维护信息在邮件中心提供。 有关详细信息，请参阅[查看服务状态](https://docs.microsoft.com/office365/enterprise/view-service-health)。 
  
## <a name="service-incidents"></a>服务事件

服务事件是影响服务交付的事件。 服务事件可能是由 Microsoft 数据中心中的硬件或软件故障、客户与 Microsoft 之间的故障网络连接或主要的数据中心挑战（如火灾、洪水或区域灾难）引起的。 可以使用 Microsoft 技术和流程解决方案，在很短时间内解决大部分服务事件。 然而，一些服务事件更加严重，并会导致长期中断。
  
有两种类型的通知关于服务可能不可用的次数：
  
- **计划的维护事件：** 计划内维护是对基础结构和软件应用程序的定期 Microsoft 启动的服务更新。 计划内维护通知通知客户可能会影响 Office 365 服务功能的服务工作。 通过 Office 365 管理门户上的消息中心在所有计划维护之前的时间内，客户收到的通知不会超过五天。 Microsoft 通常会在服务使用情况在其基于区域时间区域的最低阶段时规划维护时间。 
    
- **非计划的停机时间：** 当 Office 365 套件中的一项服务不可用或不响应时，发生非计划的服务事件。 

### <a name="recent-worldwide-uptimes"></a>最近的全球保障

移动到云服务并不意味着能够知道即将发生的情况。 在 Office 365 中，它不会。 我们在操作中的目标是透明的，因此您可以监视服务的状态，跟踪问题，并提供可用性的历史视图。 下表显示了最近的全球正常运行时间数据。

<br/>

|**2019 年** <br/> ||||
|:-----|:-----|:-----|:-----|
| **Q1** <br/> | **季** <br/> |**3** <br/> |**起** <br/> |
| 99.97% <br/> | 99.97% <br/> |  <br/> |  <br/> |

<br/>

|**2018 年** <br/>||||
|:-----|:-----|:-----|:-----|
| **Q1** <br/> | **季** <br/> |**3** <br/> |**起** <br/> |
| 99.99% <br/> | 99.98% <br/> | 99.97% <br/> | 99.98% <br/> |

<br/>

|**2017 年** <br/> ||||
|:-----|:-----|:-----|:-----|
| **Q1** <br/> | **季** <br/> |**3** <br/> |**起** <br/> |
| 99.99% <br/> | 99.97% <br/> | 99.98% <br/> | 99.99% <br/> |

<br/>

## <a name="notification-policy"></a>通知策略

当服务事件发生时，Microsoft 意识到及时、定向和准确的通信对客户非常重要。 Microsoft 通过更新 Office 365 管理门户上特定于租户的服务运行状况仪表板（SHD）来通知 Office 365 管理员。 服务事件更新在每小时节奏上提供，如果需要不同的节奏，则会在 SHD 通信发布中进行说明。 
  
## <a name="service-health-communication-channels"></a>服务运行状况的通信通道

### <a name="office-365-admin-app"></a>Office 365 Admin App

Office 365 租户管理员的管理员应用程序使你能够在旅途中与组织的 Office 365 服务状态进行连接。 Office 365 租户管理员将能够从其移动设备查看服务运行状况信息和维护状态更新。 有关详细信息，请参阅 [Admin App FAQ](https://docs.microsoft.com/office365/admin/admin-overview/admin-mobile-app?view=o365-worldwide)（管理应用程序 FAQ）。
  
### <a name="office-365-management-pack-for-microsoft-system-center-2012-r2"></a>Office 365 Management Pack for Microsoft System Center 2012 R2

Microsoft System Center 是一个集成管理平台，可以帮助你管理数据中心、客户端设备和混合云 IT 环境。 使用 System Center 的 Office 365 管理员现在可以选择导入 Office 365 管理包，这样他们就可以在 System Center 中查看 Operations Manager 中的所有服务通信。 使用此工具，可以访问已订阅服务的状态、未解决和已解决的服务事件以及消息中心通信。 有关详细信息，请参阅 [New Office 365 admin tools](https://www.microsoft.com/en-us/microsoft-365/blog/2014/07/29/new-office-365-admin-tools/)（新增的 Office 365 管理工具）博文。 
  
### <a name="office-365-service-communications-api"></a>Office 365 服务通信 API

使用 Office 365 服务通信 API，您可以按所需方式访问 Office 365 服务通信。 通过这一新的管理工具，您现在可以创建或将您的工具连接到 Office 365 服务通信，潜在地简化了环境的监视方式。 服务通信 API 允许您在环境中监视以下内容：
  
- 实时服务运行状况
    
- 消息中心通信
    
- 计划的维护通知
    
有关详细信息，请参阅 [New Office 365 admin tools](https://www.microsoft.com/en-us/microsoft-365/blog/2014/07/29/new-office-365-admin-tools/)（新增的 Office 365 管理工具）博文。 
  
## <a name="post-incident-reviews"></a>事后评审

Microsoft 致力于持续改进，包括分析影响客户的计划外服务事件，以最大限度地减少此类事件的再发生次数。 
  
计划外服务事件定义为影响服务使用者定义的服务使用情况的多租户服务中断，并已在服务运行状况仪表板中声明为这样。
  
 对于在大量组织中有广泛且显著影响的未计划客户影响的服务事件，在事件的48小时内，将通过您的服务运行状况仪表板提供初步的后期事件检查（PIR）。解决办法，后跟最终 PIR 在五个工作日内。 详细的 PIR 报告包括： 
  
- 用户体验和客户影响
    
- 事件开始日期和结束日期/时间
    
- 影响和解决方法的详细日程表
    
- 根本原因分析以及为持续改进采取的操作
    
对于所有其他服务事件，服务运行状况仪表板将提供事件结束摘要，包括事件的最终摘要、初步根源、开始和结束时间以及详细介绍后续步骤的信息。 对于此类服务事件，不会生成 PIR。 
  
## <a name="service-continuity"></a>服务连续性

Microsoft Office 365 产品由恢复能力很强的系统交付，帮助确保高水平服务性能。服务连续性设置是 Office 365 系统设计的一部分。这些设置允许 Office 365 从意外事件中快速恢复，如硬件或应用程序故障、数据损坏或其他影响用户的事件。这些服务连续性解决方案还适用于灾难性中断（例如，自然灾害或 Microsoft 数据中心内的事件导致整个数据中心无法运营）。
  
请注意，从灾难性故障恢复后，可能需要经过一段时间才能还原服务的完整数据中心冗余。例如，如果数据中心 1 出现故障，则服务通过数据中心 2 的资源进行还原。不过，可能需要经过一段时间，数据中心 2 中的服务才会获得服务连续性支持（要么通过数据中心 1 中已还原的资源获得，要么通过数据中心 3 中的新资源获得）。在此期间应用的是 Office 365 [服务级别协议](service-level-agreement.md) (SLA)。由世纪互联运营的 Office 365 具有不同的 SLA。有关详细信息，请访问 [世纪互联网站](https://www.21vbluecloud.com/office365/O365-SLA/)。 
  
## <a name="ensuring-data-availability"></a>确保数据可用性

Microsoft 可以通过以下功能确保客户数据随时可用：
  
- **数据存储和冗余：** 客户数据存储在具有强大数据保护功能的冗余环境中，以支持可用性、业务连续性和快速恢复。实施了多级数据冗余，从冗余磁盘到防止本地磁盘故障，从完整的持续数据复制到地理分散的数据中心。 
    
- **数据监控：** Office 365 服务通过以下方式维护较高级别的性能： 
    
  - **监视数据库：**
    
  - 阻塞的进程
    
  - 数据包丢失
    
  - 进程排队
    
  - 查询延迟
    
- **完成预防性维护：** 预防性维护包括数据库一致性检查、定期数据压缩和错误日志检查。 
    
## <a name="support"></a>支持

Office 365 开发和运营团队由专门的 Office 365 支持组织提供补充，这在为客户提供业务连续性中扮演了重要角色。支持员工拥有深厚的服务及其相关应用程序的知识，并可直接接触架构、开发和测试方面的 Microsoft 专家。
  
支持组织与运营和产品团队紧密合作，提供快速的解决时间，并提供倾听客户意见的渠道。来自客户的反馈为计划、开发和运营流程提供输入。
  
- **在线问题跟踪：** 客户需要知道他们的问题正在得到解决，同时需要能够跟踪及时解决。Office 365 门户提供基于 Web 的单个界面，用于获取支持。客户可以使用该门户添加和监控服务请求，并收到来自 Microsoft 支持团队的反馈。 
    
- **自助，由持续员工支持提供支持：** Office 365 提供范围广泛的自助资源和工具，帮助客户解决服务相关问题而无需 Microsoft 支持。 
    
在客户输入服务请求之前，他们可以访问知识库文章和常见问题，其中提供了最常见问题的立即帮助。我们以最新信息持续更新这些资源，通过提供已知问题的解决方案帮助避免延迟。然而，当出现的问题需要支持专业人员帮助时，员工成员可以通过电话和管理门户全天候提供立即帮助。
  
若要详细了解支持，请参阅[支持](support.md)主题。 
  
## <a name="feature-availability"></a>功能可用性

若要查看跨 Office 365 计划的功能可用性，请参阅[office 365 Platform 服务说明](office-365-platform-service-description.md)。
  