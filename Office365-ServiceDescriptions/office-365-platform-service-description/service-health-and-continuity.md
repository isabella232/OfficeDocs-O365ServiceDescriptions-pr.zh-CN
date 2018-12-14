---
title: 服务运行状况和连续性
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-service-health
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0483499d-8972-4a8f-97bd-b82f5b138991
description: Microsoft Office 365 管理员可以查看的服务的状态，并了解维护计划。服务运行状况的信息可以在任何时候通过登录到 Office 365。
ms.openlocfilehash: 5744d0f0390aee046c63309c2395e2225c4d9342
ms.sourcegitcommit: ac81ba091876af9c42828faf9f5eb989a3a2cc58
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 12/13/2018
ms.locfileid: "27258734"
---
# <a name="service-health-and-continuity"></a>服务运行状况和连续性

Microsoft Office 365 管理员可以查看的服务的状态，并了解维护计划。服务运行状况的信息可以在任何时候通过登录到 Office 365。
  
> [!NOTE]
> 如果正在使用由世纪互联运营的 Office 365，则下面的某些信息可能不适用。请转为参阅[世纪互联服务级别协议](http://www.21vbluecloud.com/office365/O365-SLA/)。 
  
## <a name="view-status-of-services"></a>查看服务状态

Office 365 服务运行状况部分显示的服务和服务中断和中断的详细信息的当前状态。消息中心上提供了计划内的维护信息。有关详细信息，请参阅[查看您的服务的状态](https://docs.microsoft.com/office365/enterprise/view-service-health)。 
  
## <a name="service-incidents"></a>服务事件

服务事件是一个影响服务的传送的事件。服务事件可能是由在 Microsoft 数据中心中，出错的网络连接客户与 Microsoft 或主要数据中心挑战，如火灾、 淹没或地区灾难之间的硬件或软件故障导致的。大多数服务事件可以用 Microsoft 技术和流程解决方案寻址和短时间内解析。但是，某些服务事件是更严重，并且可能会导致更长时间术语中断。
  
有两种类型的通知有关时服务可能不可用的时间：
  
- **计划维护事件：** 计划内的维护是常规 Microsoft 启动的服务基础结构和软件应用程序更新。计划内的维护通知告知可能会影响 Office 365 服务的功能的服务工作的客户。通过在 Office 365 管理门户上的邮件中心的所有计划内维护前五天内通知客户。通常，Microsoft 在当服务使用情况过去最低的基于区域时区的时间计划维护。 
    
- **非计划的停机时间：** 当 Office 365 套件中的一项服务不可用或不响应时，发生非计划的服务事件。 
    
## <a name="notification-policy"></a>通知策略

服务事件发生时，Microsoft 识别及时、 目标，且准确通信很重要的客户。Microsoft 通知通过更新租户特定服务运行状况仪表板 (SHD) 在 Office 365 管理门户上的 Office 365 管理员。每小时节奏上提供了事件的服务更新，或者，如果不同步调是必需的它将为所述 SHD 通信发布。 
  
## <a name="service-health-communication-channels"></a>服务运行状况的通信通道

### <a name="office-365-admin-app"></a>Office 365 Admin App

管理应用程序的 Office 365 租户管理员为您提供了连接与在贵组织的 Office 365 服务状态的能力。Office 365 租户管理员将能够查看服务运行状况信息和维护从其移动设备的状态更新。有关详细信息，请访问[管理应用程序的常见问题](https://docs.microsoft.com/en-us/office365/admin/admin-overview/admin-mobile-app?view=o365-worldwide)。
  
### <a name="office-365-management-pack-for-microsoft-system-center-2012-r2"></a>Office 365 Management Pack for Microsoft System Center 2012 R2

Microsoft System Center 是帮助您管理数据中心、 客户端设备和混合云 IT 环境集成的管理平台。现在使用 System Center office 365 管理员可以选择要导入 Office 365 管理包，这就使用户可以查看在 System Center Operations Manager 中的所有服务通信。使用此工具可以访问您的订阅的服务、 活动和解决服务事件和消息中心通信的状态。有关详细信息，请访问[新的 Office 365 管理员工具](https://blogs.office.com/2014/07/29/new-office-365-admin-tools/)博客文章。 
  
### <a name="office-365-service-communications-api"></a>Office 365 服务通信 API

通过 Office 365 服务通信 API，您可以根据您的喜好访问 Office 365 服务通信。通过这一新的管理工具，您现在可以创建或将您的工具连接到 Office 365 服务通信，潜在地简化了环境的监视方式。服务通信 API 可让您监视环境中的以下内容：
  
- 实时服务运行状况
    
- 消息中心通信
    
- 计划的维护通知
    
有关详细信息，请参阅 [New Office 365 admin tools](https://blogs.office.com/2014/07/29/new-office-365-admin-tools/)（新增的 Office 365 管理工具）博文。 
  
## <a name="post-incident-reviews"></a>事后评审

Microsoft 致力于持续改进，包括分析影响客户的计划外服务事件，以最大限度地减少此类事件的再发生次数。 
  
计划外的服务事件被指我们服务的 Sla，由定义影响服务使用情况并在服务运行状况主控板上的此类声明的多租户服务中断。
  
 计划外影响客户的服务事件顺序出现广泛和显著影响整个组织的大量的初步后事件审阅 (PIR) 将传递通过服务运行状况主控板的事件的 48 小时内五业务天内跟最终 PIR 分辨率。详细的 PIR 报告包括： 
  
- 用户体验和客户影响
    
- 事件开始日期和结束日期/时间
    
- 详细的时间线的影响和解决方案的度量值
    
- 根本原因分析以及为持续改进采取的操作
    
对于所有其他服务事件，服务运行状况主控板将提供事件关闭摘要包括最后一个摘要事件、 初步根本原因、 开始和结束时间和伴随后续步骤的信息。服务事件此类别，将不会生成 PIR。 
  
## <a name="service-continuity"></a>服务连续性

Microsoft Office 365 产品由恢复能力很强的系统交付，帮助确保高水平服务性能。服务连续性设置是 Office 365 系统设计的一部分。这些设置允许 Office 365 从意外事件中快速恢复，如硬件或应用程序故障、数据损坏或其他影响用户的事件。这些服务连续性解决方案还适用于灾难性中断（例如，自然灾害或 Microsoft 数据中心内的事件导致整个数据中心无法运营）。
  
请注意，从灾难性故障恢复后，可能需要经过一段时间才能还原服务的完整数据中心冗余。例如，如果数据中心 1 出现故障，则服务通过数据中心 2 的资源进行还原。不过，可能需要经过一段时间，数据中心 2 中的服务才会获得服务连续性支持（要么通过数据中心 1 中已还原的资源获得，要么通过数据中心 3 中的新资源获得）。在此期间应用的是 Office 365 [服务级别协议](https://technet.microsoft.com/en-us/library/office-365-service-level-agreement.aspx) (SLA)。由世纪互联运营的 Office 365 具有不同的 SLA。有关详细信息，请访问 [世纪互联网站](http://www.21vbluecloud.com/office365/O365-SLA/)。 
  
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
  
若要详细了解支持，请参阅[支持](https://technet.microsoft.com/en-us/library/office-365-support.aspx)主题。 
  
## <a name="feature-availability"></a>功能可用性

若要查看各个 Office 365 计划的功能可用性，请参阅 [Office 365 平台服务说明](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx)。
  

