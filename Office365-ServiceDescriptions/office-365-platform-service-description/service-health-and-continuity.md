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
ms.openlocfilehash: cc19a26f7bef070837b1dfa53df927373fd35d3e
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035176"
---
# <a name="service-health-and-continuity"></a><span data-ttu-id="fcbd7-104">服务运行状况和连续性</span><span class="sxs-lookup"><span data-stu-id="fcbd7-104">Service Health and Continuity</span></span>

<span data-ttu-id="fcbd7-p102">Microsoft Office 365 管理员可以查看的服务的状态，并了解维护计划。服务运行状况的信息可以在任何时候通过登录到 Office 365。</span><span class="sxs-lookup"><span data-stu-id="fcbd7-p102">Microsoft Office 365 admins can view the status of services and find out when maintenance is scheduled. Service health information is available at any time by signing in to Office 365.</span></span>
  
> [!NOTE]
> <span data-ttu-id="fcbd7-p103">如果正在使用由世纪互联运营的 Office 365，则下面的某些信息可能不适用。请转为参阅[世纪互联服务级别协议](http://www.21vbluecloud.com/office365/O365-SLA/)。</span><span class="sxs-lookup"><span data-stu-id="fcbd7-p103">If you are using Office 365 operated by 21Vianet, some of the information below might not apply. Instead, see the [21Vianet service level agreement](http://www.21vbluecloud.com/office365/O365-SLA/).</span></span> 
  
## <a name="view-status-of-services"></a><span data-ttu-id="fcbd7-109">查看服务状态</span><span class="sxs-lookup"><span data-stu-id="fcbd7-109">View Status of Services</span></span>

<span data-ttu-id="fcbd7-p104">Office 365 服务运行状况部分显示的服务和服务中断和中断的详细信息的当前状态。消息中心上提供了计划内的维护信息。有关详细信息，请参阅[查看您的服务的状态](https://go.microsoft.com/fwlink/p/?LinkID=270178)。</span><span class="sxs-lookup"><span data-stu-id="fcbd7-p104">The Service health section of Office 365 shows the current status of the service and details about service disruptions and outages. Planned maintenance information is available on the Message Center. For more information, see [View the status of your services](https://go.microsoft.com/fwlink/p/?LinkID=270178).</span></span> 
  
## <a name="service-incidents"></a><span data-ttu-id="fcbd7-113">服务事件</span><span class="sxs-lookup"><span data-stu-id="fcbd7-113">Service incidents</span></span>

<span data-ttu-id="fcbd7-p105">服务事件是一个影响服务的传送的事件。服务事件可能是由在 Microsoft 数据中心中，出错的网络连接客户与 Microsoft 或主要数据中心挑战，如火灾、 淹没或地区灾难之间的硬件或软件故障导致的。大多数服务事件可以用 Microsoft 技术和流程解决方案寻址和短时间内解析。但是，某些服务事件是更严重，并且可能会导致更长时间术语中断。</span><span class="sxs-lookup"><span data-stu-id="fcbd7-p105">A service incident is an event that affects the delivery of a service. Service incidents may be caused by hardware or software failure in the Microsoft data center, a faulty network connection between the customer and Microsoft, or a major data center challenge such as fire, flood, or regional catastrophe. Most service incidents can be addressed using Microsoft technology and process solutions and are resolved within a short time. However, some service incidents are more serious and can lead to longer term outages.</span></span>
  
<span data-ttu-id="fcbd7-118">有两种类型的通知有关时服务可能不可用的时间：</span><span class="sxs-lookup"><span data-stu-id="fcbd7-118">There are two types of notifications about times when services may not be available:</span></span>
  
- <span data-ttu-id="fcbd7-p106">**计划维护事件：** 计划内的维护是常规 Microsoft 启动的服务基础结构和软件应用程序更新。计划内的维护通知告知可能会影响 Office 365 服务的功能的服务工作的客户。通过在 Office 365 管理门户上的邮件中心的所有计划内维护前五天内通知客户。通常，Microsoft 在当服务使用情况过去最低的基于区域时区的时间计划维护。</span><span class="sxs-lookup"><span data-stu-id="fcbd7-p106">**Planned maintenance events:** Planned maintenance is regular Microsoft-initiated service updates to the infrastructure and software applications. Planned maintenance notifications inform customers about service work that might affect the functionality of an Office 365 service. Customers are notified no later than five days in advance of all planned maintenance through Message Center on the Office 365 Admin Portal. Microsoft typically plans maintenance for times when service usage is historically at its lowest based on regional time zones.</span></span> 
    
- <span data-ttu-id="fcbd7-123">**非计划的停机时间：** 当 Office 365 套件中的一项服务不可用或不响应时，发生非计划的服务事件。</span><span class="sxs-lookup"><span data-stu-id="fcbd7-123">**Unplanned downtime:** Unplanned service incidents occur when one of the services in the Office 365 suite is unavailable or unresponsive.</span></span> 
    
## <a name="notification-policy"></a><span data-ttu-id="fcbd7-124">通知策略</span><span class="sxs-lookup"><span data-stu-id="fcbd7-124">Notification policy</span></span>

<span data-ttu-id="fcbd7-p107">服务事件发生时，Microsoft 识别及时、 目标，且准确通信很重要的客户。Microsoft 通知通过更新租户特定服务运行状况仪表板 (SHD) 在 Office 365 管理门户上的 Office 365 管理员。每小时节奏上提供了事件的服务更新，或者，如果不同步调是必需的它将为所述 SHD 通信发布。</span><span class="sxs-lookup"><span data-stu-id="fcbd7-p107">When a service incident occurs, Microsoft recognizes that timely, targeted, and accurate communications are critical for customers. Microsoft notifies Office 365 administrators by updating the tenant-specific Service Health Dashboard (SHD) on the Office 365 Admin Portal. Service incident updates are provided on an hourly cadence or, if a different cadence is required, it will be stated in the SHD communication posting.</span></span> 
  
## <a name="service-health-communication-channels"></a><span data-ttu-id="fcbd7-128">服务运行状况的通信通道</span><span class="sxs-lookup"><span data-stu-id="fcbd7-128">Service Health Communication Channels</span></span>

### <a name="office-365-admin-app"></a><span data-ttu-id="fcbd7-129">Office 365 Admin App</span><span class="sxs-lookup"><span data-stu-id="fcbd7-129">Office 365 Admin App</span></span>

<span data-ttu-id="fcbd7-p108">管理应用程序的 Office 365 租户管理员为您提供了连接与在贵组织的 Office 365 服务状态的能力。Office 365 租户管理员将能够查看服务运行状况信息和维护从其移动设备的状态更新。有关详细信息，请访问[管理应用程序的常见问题](https://community.office365.com/en-us/w/manage/office-365-admin-app-faq.aspx)。</span><span class="sxs-lookup"><span data-stu-id="fcbd7-p108">The Admin App for Office 365 tenant administrators gives you the ability to connect with your organization's Office 365 service status on the go. Office 365 tenant administrators will have the ability to view service health information and maintenance status updates from their mobile devices. For more information, visit the [Admin App FAQ](https://community.office365.com/en-us/w/manage/office-365-admin-app-faq.aspx).</span></span>
  
### <a name="office-365-management-pack-for-microsoft-system-center-2012-r2"></a><span data-ttu-id="fcbd7-133">Office 365 Management Pack for Microsoft System Center 2012 R2</span><span class="sxs-lookup"><span data-stu-id="fcbd7-133">Office 365 Management Pack for Microsoft System Center 2012 R2</span></span>

<span data-ttu-id="fcbd7-p109">Microsoft System Center 是帮助您管理数据中心、 客户端设备和混合云 IT 环境集成的管理平台。现在使用 System Center office 365 管理员可以选择要导入 Office 365 管理包，这就使用户可以查看在 System Center Operations Manager 中的所有服务通信。使用此工具可以访问您的订阅的服务、 活动和解决服务事件和消息中心通信的状态。有关详细信息，请访问[新的 Office 365 管理员工具](https://blogs.office.com/2014/07/29/new-office-365-admin-tools/)博客文章。</span><span class="sxs-lookup"><span data-stu-id="fcbd7-p109">Microsoft System Center is an integrated management platform that helps you manage data center, client devices, and hybrid cloud IT environments. Office 365 administrators who use System Center now have the option to import the Office 365 Management Pack, which enables them to view all service communications within Operations Manager in System Center. Using this tool gives you access to the status of your subscribed services, active and resolved service incidents, and your Message Center communications. For more information, visit the [New Office 365 admin tools](https://blogs.office.com/2014/07/29/new-office-365-admin-tools/) blog post.</span></span> 
  
### <a name="office-365-service-communications-api"></a><span data-ttu-id="fcbd7-138">Office 365 服务通信 API</span><span class="sxs-lookup"><span data-stu-id="fcbd7-138">Office 365 Service Communications API</span></span>

<span data-ttu-id="fcbd7-p110">通过 Office 365 服务通信 API，您可以根据您的喜好访问 Office 365 服务通信。通过这一新的管理工具，您现在可以创建或将您的工具连接到 Office 365 服务通信，潜在地简化了环境的监视方式。服务通信 API 可让您监视环境中的以下内容：</span><span class="sxs-lookup"><span data-stu-id="fcbd7-p110">The Office 365 Service Communications API enables you to access Office 365 service communications the way you want. With this new admin tool, you now have the ability to create or connect your tools to Office 365 service communications, potentially simplifying how you monitor your environment. The Service Communications API enables you to monitor the following in your environment:</span></span>
  
- <span data-ttu-id="fcbd7-142">实时服务运行状况</span><span class="sxs-lookup"><span data-stu-id="fcbd7-142">Real-time service health</span></span>
    
- <span data-ttu-id="fcbd7-143">消息中心通信</span><span class="sxs-lookup"><span data-stu-id="fcbd7-143">Message Center communications</span></span>
    
- <span data-ttu-id="fcbd7-144">计划的维护通知</span><span class="sxs-lookup"><span data-stu-id="fcbd7-144">Planned maintenance notifications</span></span>
    
<span data-ttu-id="fcbd7-145">有关详细信息，请参阅 [New Office 365 admin tools](https://blogs.office.com/2014/07/29/new-office-365-admin-tools/)（新增的 Office 365 管理工具）博文。</span><span class="sxs-lookup"><span data-stu-id="fcbd7-145">For more information, visit the [New Office 365 admin tools](https://blogs.office.com/2014/07/29/new-office-365-admin-tools/) blog post.</span></span> 
  
## <a name="post-incident-reviews"></a><span data-ttu-id="fcbd7-146">事后评审</span><span class="sxs-lookup"><span data-stu-id="fcbd7-146">Post-incident reviews</span></span>

<span data-ttu-id="fcbd7-147">Microsoft 致力于持续改进，包括分析影响客户的计划外服务事件，以最大限度地减少此类事件的再发生次数。</span><span class="sxs-lookup"><span data-stu-id="fcbd7-147">Microsoft's commitment to continuous improvement involves analysis of unplanned customer-impacting service incidents to minimize future recurrence.</span></span> 
  
<span data-ttu-id="fcbd7-148">计划外的服务事件被指我们服务的 Sla，由定义影响服务使用情况并在服务运行状况主控板上的此类声明的多租户服务中断。</span><span class="sxs-lookup"><span data-stu-id="fcbd7-148">Unplanned service incidents are defined as multi-tenant service disruptions that impact service usage as defined by our service SLAs, and have been declared as such on the Service Health Dashboard.</span></span>
  
 <span data-ttu-id="fcbd7-p111">计划外影响客户的服务事件顺序出现广泛和显著影响整个组织的大量的初步后事件审阅 (PIR) 将传递通过服务运行状况主控板的事件的 48 小时内五业务天内跟最终 PIR 分辨率。详细的 PIR 报告包括：</span><span class="sxs-lookup"><span data-stu-id="fcbd7-p111">For unplanned customer-impacting service incidents in which there was broad and noticeable impact across a large number of organizations, a preliminary Post-Incident Review (PIR) will be delivered via your Service Health Dashboard within 48 hours of incident resolution, followed by a final PIR within five business days. The detailed PIR report includes:</span></span> 
  
- <span data-ttu-id="fcbd7-151">用户体验和客户影响</span><span class="sxs-lookup"><span data-stu-id="fcbd7-151">User experience and customer impact</span></span>
    
- <span data-ttu-id="fcbd7-152">事件开始日期和结束日期/时间</span><span class="sxs-lookup"><span data-stu-id="fcbd7-152">Incident start and end date/time</span></span>
    
- <span data-ttu-id="fcbd7-153">详细的时间线的影响和解决方案的度量值</span><span class="sxs-lookup"><span data-stu-id="fcbd7-153">Detailed timeline of impact and resolution measures</span></span>
    
- <span data-ttu-id="fcbd7-154">根本原因分析以及为持续改进采取的操作</span><span class="sxs-lookup"><span data-stu-id="fcbd7-154">Root cause analysis and actions being taken for continuous improvement</span></span>
    
<span data-ttu-id="fcbd7-p112">对于所有其他服务事件，服务运行状况主控板将提供事件关闭摘要包括最后一个摘要事件、 初步根本原因、 开始和结束时间和伴随后续步骤的信息。服务事件此类别，将不会生成 PIR。</span><span class="sxs-lookup"><span data-stu-id="fcbd7-p112">For all other service incidents, the Service Health Dashboard will provide an incident closure summary including a final summary of the event, preliminary root cause, start and end times, and information detailing next steps. For this category of service incident, a PIR will not be generated.</span></span> 
  
## <a name="service-continuity"></a><span data-ttu-id="fcbd7-157">服务连续性</span><span class="sxs-lookup"><span data-stu-id="fcbd7-157">Service Continuity</span></span>

<span data-ttu-id="fcbd7-p113">Microsoft Office 365 产品由恢复能力很强的系统交付，帮助确保高水平服务性能。服务连续性设置是 Office 365 系统设计的一部分。这些设置允许 Office 365 从意外事件中快速恢复，如硬件或应用程序故障、数据损坏或其他影响用户的事件。这些服务连续性解决方案还适用于灾难性中断（例如，自然灾害或 Microsoft 数据中心内的事件导致整个数据中心无法运营）。</span><span class="sxs-lookup"><span data-stu-id="fcbd7-p113">Microsoft Office 365 offerings are delivered by highly resilient systems that help to maintain peak service performance. Service continuity provisions are part of the Office 365 system design. These provisions enable Office 365 to recover quickly from unexpected events such as hardware or application failure, data corruption, or other incidents that affect users. These service continuity solutions also apply during catastrophic outages (for example, natural disasters or an incident within a Microsoft data center that renders the entire data center inoperable).</span></span>
  
<span data-ttu-id="fcbd7-p114">请注意，从灾难性故障恢复后，可能需要经过一段时间才能还原服务的完整数据中心冗余。例如，如果数据中心 1 出现故障，则服务通过数据中心 2 的资源进行还原。不过，可能需要经过一段时间，数据中心 2 中的服务才会获得服务连续性支持（要么通过数据中心 1 中已还原的资源获得，要么通过数据中心 3 中的新资源获得）。在此期间应用的是 Office 365 [服务级别协议](https://technet.microsoft.com/en-us/library/office-365-service-level-agreement.aspx) (SLA)。由世纪互联运营的 Office 365 具有不同的 SLA。有关详细信息，请访问 [世纪互联网站](http://www.21vbluecloud.com/office365/O365-SLA/)。</span><span class="sxs-lookup"><span data-stu-id="fcbd7-p114">Note that after recovery from catastrophic outages, there may be a period of time before full data center redundancy is restored for the service. For example, if Data Center 1 fails, services are restored by resources in Data Center 2. However, there may be a period of time until services in Data Center 2 have service continuity support either by restored resources in Data Center 1, or new resources in Data Center 3. The Office 365 [Service Level Agreement](https://technet.microsoft.com/en-us/library/office-365-service-level-agreement.aspx) (SLA) applies during this time. Office 365 operated by 21Vianet has a different SLA. See the [21Vianet site](http://www.21vbluecloud.com/office365/O365-SLA/) for more information.</span></span> 
  
## <a name="ensuring-data-availability"></a><span data-ttu-id="fcbd7-168">确保数据可用性</span><span class="sxs-lookup"><span data-stu-id="fcbd7-168">Ensuring data availability</span></span>

<span data-ttu-id="fcbd7-169">Microsoft 可以通过以下功能确保客户数据随时可用：</span><span class="sxs-lookup"><span data-stu-id="fcbd7-169">Microsoft ensures that customer data is available whenever it is needed through the following features:</span></span>
  
- <span data-ttu-id="fcbd7-p115">**数据存储和冗余：** 客户数据存储在具有强大数据保护功能的冗余环境中，以支持可用性、业务连续性和快速恢复。实施了多级数据冗余，从冗余磁盘到防止本地磁盘故障，从完整的持续数据复制到地理分散的数据中心。</span><span class="sxs-lookup"><span data-stu-id="fcbd7-p115">**Data storage and redundancy:** Customer data is stored in a redundant environment with robust data protection capabilities to enable availability, business continuity, and rapid recovery. Multiple levels of data redundancy are implemented, ranging from redundant disks to guard against local disk failure to continuous, full data replication to a geographically diverse data center.</span></span> 
    
- <span data-ttu-id="fcbd7-172">**数据监控：** Office 365 服务通过以下方式维护较高级别的性能：</span><span class="sxs-lookup"><span data-stu-id="fcbd7-172">**Data monitoring:** Office 365 services maintain high levels of performance by:</span></span> 
    
  - <span data-ttu-id="fcbd7-173">**监视数据库：**</span><span class="sxs-lookup"><span data-stu-id="fcbd7-173">**Monitoring databases:**</span></span>
    
  - <span data-ttu-id="fcbd7-174">阻塞的进程</span><span class="sxs-lookup"><span data-stu-id="fcbd7-174">Blocked processes</span></span>
    
  - <span data-ttu-id="fcbd7-175">数据包丢失</span><span class="sxs-lookup"><span data-stu-id="fcbd7-175">Packet loss</span></span>
    
  - <span data-ttu-id="fcbd7-176">进程排队</span><span class="sxs-lookup"><span data-stu-id="fcbd7-176">Queued processes</span></span>
    
  - <span data-ttu-id="fcbd7-177">查询延迟</span><span class="sxs-lookup"><span data-stu-id="fcbd7-177">Query latency</span></span>
    
- <span data-ttu-id="fcbd7-178">**完成预防性维护：** 预防性维护包括数据库一致性检查、定期数据压缩和错误日志检查。</span><span class="sxs-lookup"><span data-stu-id="fcbd7-178">**Completing preventative maintenance:** Preventative maintenance includes database consistency checks, periodic data compression, and error log reviews.</span></span> 
    
## <a name="support"></a><span data-ttu-id="fcbd7-179">支持</span><span class="sxs-lookup"><span data-stu-id="fcbd7-179">Support</span></span>

<span data-ttu-id="fcbd7-p116">Office 365 开发和运营团队由专门的 Office 365 支持组织提供补充，这在为客户提供业务连续性中扮演了重要角色。支持员工拥有深厚的服务及其相关应用程序的知识，并可直接接触架构、开发和测试方面的 Microsoft 专家。</span><span class="sxs-lookup"><span data-stu-id="fcbd7-p116">The Office 365 development and operations teams are complemented by a dedicated Office 365 support organization, which plays an important role in providing customers with business continuity. Support staff has a deep knowledge of the service and its associated applications as well as direct access to Microsoft experts in architecture, development, and testing.</span></span>
  
<span data-ttu-id="fcbd7-p117">支持组织与运营和产品团队紧密合作，提供快速的解决时间，并提供倾听客户意见的渠道。来自客户的反馈为计划、开发和运营流程提供输入。</span><span class="sxs-lookup"><span data-stu-id="fcbd7-p117">The support organization closely aligns with operations and product development, offers fast resolution times and provides a channel for customers' voices to be heard. Feedback from customers provides input to the planning, development, and operations processes.</span></span>
  
- <span data-ttu-id="fcbd7-p118">**在线问题跟踪：** 客户需要知道他们的问题正在得到解决，同时需要能够跟踪及时解决。Office 365 门户提供基于 Web 的单个界面，用于获取支持。客户可以使用该门户添加和监控服务请求，并收到来自 Microsoft 支持团队的反馈。</span><span class="sxs-lookup"><span data-stu-id="fcbd7-p118">**Online issue tracking:** Customers need to know that their issues are being addressed, and they need to be able to track timely resolution. The Office 365 portal provides a single web-based interface for support. Customers can use the portal to add and monitor service requests and receive feedback from Microsoft support teams.</span></span> 
    
- <span data-ttu-id="fcbd7-187">**自助，由持续员工支持提供支持：** Office 365 提供范围广泛的自助资源和工具，帮助客户解决服务相关问题而无需 Microsoft 支持。</span><span class="sxs-lookup"><span data-stu-id="fcbd7-187">**Self-help, backed by continuous staff support:** Office 365 offers a wide range of self-help resources and tools that can help customers to resolve service-related issues without requiring Microsoft support.</span></span> 
    
<span data-ttu-id="fcbd7-p119">在客户输入服务请求之前，他们可以访问知识库文章和常见问题，其中提供了最常见问题的立即帮助。我们以最新信息持续更新这些资源，通过提供已知问题的解决方案帮助避免延迟。然而，当出现的问题需要支持专业人员帮助时，员工成员可以通过电话和管理门户全天候提供立即帮助。</span><span class="sxs-lookup"><span data-stu-id="fcbd7-p119">Before customers enter service requests, they can access knowledge base articles and FAQs that provide immediate help with the most common problems. These resources are continually updated with the latest information, which helps avoid delays by providing solutions to known issues. However, when an issue arises that needs the help of a support professional; staff members are available for immediate assistance by telephone and through the administration portal 24 hours a day, 7 days a week.</span></span>
  
<span data-ttu-id="fcbd7-191">若要详细了解支持，请参阅[支持](https://technet.microsoft.com/en-us/library/office-365-support.aspx)主题。</span><span class="sxs-lookup"><span data-stu-id="fcbd7-191">For more information about support, see the [Support](https://technet.microsoft.com/en-us/library/office-365-support.aspx) topic.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="fcbd7-192">功能可用性</span><span class="sxs-lookup"><span data-stu-id="fcbd7-192">Feature availability</span></span>

<span data-ttu-id="fcbd7-193">若要查看各个 Office 365 计划的功能可用性，请参阅 [Office 365 平台服务说明](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx)。</span><span class="sxs-lookup"><span data-stu-id="fcbd7-193">To view feature availability across Office 365 plans, see [Office 365 Platform Service Description](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx).</span></span>
  

