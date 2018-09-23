---
title: Exchange Online 设置和管理
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-administration-and-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 80c07748-ac57-4b90-97dd-a2d1115009a6
description: 本节介绍管理控件和可用于自定义 Exchange Online 设置并保留组织的 Exchange Online 环境，运行，并且当前的支持。它包括有关自助服务管理工具和可用的组织; 功能信息Microsoft 管理责任和性能承诺;和服务和产品的升级。
ms.openlocfilehash: 6b7bb1d68e6d676c39e9ebb254305b2799cc0931
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035016"
---
# <a name="exchange-online-setup-and-administration"></a><span data-ttu-id="ff088-104">Exchange Online 设置和管理</span><span class="sxs-lookup"><span data-stu-id="ff088-104">Exchange Online Setup and Administration</span></span>

<span data-ttu-id="ff088-p102">本节介绍管理控件和可用于自定义 Exchange Online 设置并保留组织的 Exchange Online 环境，运行，并且当前的支持。它包括有关自助服务管理工具和可用的组织; 功能信息Microsoft 管理责任和性能承诺;和服务和产品的升级。</span><span class="sxs-lookup"><span data-stu-id="ff088-p102">This section describes the administration controls and support that are available to customize Exchange Online settings and keep an organization's Exchange Online environment up, running, and current. It includes information about self-service administration tools and capabilities available to organizations; Microsoft administration responsibilities and performance commitments; and service and product upgrades.</span></span>
  
## <a name="self-service-administration-tools"></a><span data-ttu-id="ff088-107">自助服务管理工具</span><span class="sxs-lookup"><span data-stu-id="ff088-107">Self-service administration tools</span></span>

<span data-ttu-id="ff088-p103">尽管 Microsoft 直接控制所有的 Exchange Online 数据中心，并负责整体系统性能，但它仅控制一部分组合在一起可为 Office 365 用户提供全面体验的元素。组织本身负责到数据中心、客户广域网 (WAN) 和客户局域网 (LAN) 的网络连接。此外，还负责用户设备及其配置。它们也负责维护每个用户的任何所需功能需要的授权，包括但不限于管理这些功能的能力，前提是用户需要访问此功能。</span><span class="sxs-lookup"><span data-stu-id="ff088-p103">Although Microsoft directly controls all Exchange Online data centers and is responsible for overall system performance, it can control only a portion of the elements that combine to provide the total experience for Office 365 users. Organizations themselves are responsible for the network connections to the data centers, the customer's wide area network (WAN), and the customer's local area networks (LANs). Additionally, they are in charge of user devices and their configuration.  They are also responsible for maintaining the required licensing per user for any desired feature, including, but not limited to, the ability to manage these features, for as long as the user needs access to the feature.</span></span>
  
<span data-ttu-id="ff088-112">因此，Exchange Online 为客户管理员提供了以下工具（如下所述），帮助他们管理消息传递相关的任务：</span><span class="sxs-lookup"><span data-stu-id="ff088-112">Exchange Online therefore provides customer administrators with the following tools, described below, to manage a variety of messaging-related tasks:</span></span>
  
- [<span data-ttu-id="ff088-113">Microsoft Office 365 门户</span><span class="sxs-lookup"><span data-stu-id="ff088-113">Microsoft Office 365 portal</span></span>](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [<span data-ttu-id="ff088-114">Microsoft Office 365 管理中心</span><span class="sxs-lookup"><span data-stu-id="ff088-114">Microsoft Office 365 admin center</span></span>](exchange-online-setup-and-administration.md#microsoft-office-365-admin-center)
    
- [<span data-ttu-id="ff088-115">Exchange 管理中心</span><span class="sxs-lookup"><span data-stu-id="ff088-115">Exchange admin center</span></span>](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [<span data-ttu-id="ff088-116">Exchange Online 的远程 Windows PowerShell</span><span class="sxs-lookup"><span data-stu-id="ff088-116">Remote Windows PowerShell for Exchange Online</span></span>](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a><span data-ttu-id="ff088-117">Microsoft Office 365 门户</span><span class="sxs-lookup"><span data-stu-id="ff088-117">Microsoft Office 365 portal</span></span>
<span data-ttu-id="ff088-118"><a name="BKMK_MicrosoftOnlineServicesPortal"> </a></span><span class="sxs-lookup"><span data-stu-id="ff088-118"></span></span>

<span data-ttu-id="ff088-119">Microsoft Office 365 门户 ([https://portal.office.com](https://portal.office.com)) 门户是一个网站，管理员与合作伙伴可通过其购买和管理 Office 365 服务，而用户则可在其中访问和使用 Office 365 协作工具。</span><span class="sxs-lookup"><span data-stu-id="ff088-119">The Microsoft Office 365 portal, at [https://portal.office.com](https://portal.office.com), is the website through which administrators and partners purchase and manage Office 365 services and where users access and use Office 365 collaborative tools.</span></span>
  
### <a name="microsoft-office-365-admin-center"></a><span data-ttu-id="ff088-120">Microsoft Office 365 管理中心</span><span class="sxs-lookup"><span data-stu-id="ff088-120">Microsoft Office 365 admin center</span></span>
<span data-ttu-id="ff088-121"><a name="BKMK_Office365admincenterl"> </a></span><span class="sxs-lookup"><span data-stu-id="ff088-121"></span></span>

<span data-ttu-id="ff088-p104">Microsoft Office 365 管理中心是一个 Web 门户；通过它，每个公司的服务管理员都可以管理他们订阅的每项 Office 365 服务的用户帐户和设置。管理员可以在 Office 365 管理中心内单击指向 Exchange 管理中心 (EAC) 的链接。在此管理中心内，他们可以管理特定于 Exchange Online 的相关设置。若要详细了解如何使用 Office 365 管理中心，请观看以下视频：[Introducing Office 365 Enterprise](https://go.microsoft.com/fwlink/p/?LinkId=271806)（Office 365 企业版简介）。</span><span class="sxs-lookup"><span data-stu-id="ff088-p104">The Microsoft Office 365 admin center is the web portal from which each company's service administrator can manage user accounts and settings for each of the Office 365 services to which they subscribe. From within the Office 365 admin center, administrators can follow links to the Exchange admin center (EAC), where they can manage settings specific to Exchange Online. For more information about getting up and running using the Office 365 admin center, see the following video: [Introducing Office 365 Enterprise](https://go.microsoft.com/fwlink/p/?LinkId=271806).</span></span>
  
### <a name="exchange-admin-center"></a><span data-ttu-id="ff088-125">Exchange 管理中心</span><span class="sxs-lookup"><span data-stu-id="ff088-125">Exchange admin center</span></span>
<span data-ttu-id="ff088-126"><a name="BKMK_ExchangeAdministrationCenter"> </a></span><span class="sxs-lookup"><span data-stu-id="ff088-126"></span></span>

<span data-ttu-id="ff088-p105">Exchange Online 提供单一的统一管理控制台，该控制台易于使用，并针对内部部署、联机部署或混合部署进行了管理优化。在 Exchange 管理中心 (EAC) 内，管理员可以管理特定于 Exchange 的相关设置。</span><span class="sxs-lookup"><span data-stu-id="ff088-p105">Exchange Online provides a single unified management console that allows for ease of use and is optimized for management of on-premises, online, or hybrid deployments. The Exchange admin center (EAC) is where administrators can manage Exchange-specific settings.</span></span>
  
<span data-ttu-id="ff088-129">若要详细了解如何使用 EAC 管理 Exchange Online，请参阅 [Exchange 管理中心](https://go.microsoft.com/fwlink/p/?LinkId=271807)。</span><span class="sxs-lookup"><span data-stu-id="ff088-129">For more information about how to use the EAC to manage Exchange Online, see [Exchange admin center](https://go.microsoft.com/fwlink/p/?LinkId=271807).</span></span>
  
### <a name="remote-windows-powershell-for-exchange-online"></a><span data-ttu-id="ff088-130">Exchange Online 的远程 Windows PowerShell</span><span class="sxs-lookup"><span data-stu-id="ff088-130">Remote Windows PowerShell for Exchange Online</span></span>
<span data-ttu-id="ff088-131"><a name="BKMK_RemoteWindowsPowerShell"> </a></span><span class="sxs-lookup"><span data-stu-id="ff088-131"></span></span>

<span data-ttu-id="ff088-p106">使用远程 Windows PowerShell，管理员可以连接到 Exchange Online，执行使用 EAC 无法执行的管理任务。这些任务包括：自动运行重复任务、从自定义报告中提取数据、自定义策略，以及将 Exchange Online 连接到现有基础结构和流程。有关详细信息，请参阅[使用远程 PowerShell 连接到 Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=308994)。</span><span class="sxs-lookup"><span data-stu-id="ff088-p106">Using remote Windows PowerShell, administrators can connect to Exchange Online to perform management tasks that are not available or practical using the EAC. These include the ability to automate repetitive tasks, extract data for custom reports, customize policies, and connect Exchange Online to existing infrastructure and processes. For more information, see [Connect to Exchange Online Using Remote PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).</span></span>
  
<span data-ttu-id="ff088-p107">Exchange Online 使用与 Exchange Server 2013 相同的 Windows PowerShell cmdlet，但某些特定的命令和参数不可用，其原因在于这些功能在 Exchange Online 中不适用。有关可与 Exchange Online 结合使用的 cmdlet 列表，请参阅 [Exchange Online cmdlet](https://go.microsoft.com/fwlink/p/?LinkId=271808)。</span><span class="sxs-lookup"><span data-stu-id="ff088-p107">Exchange Online uses the same Windows PowerShell cmdlets as Exchange Server 2013, with certain commands and parameters unavailable because these features do not apply in Exchange Online. For a list of cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span></span>
  
<span data-ttu-id="ff088-p108">管理员无需安装任何 Exchange Server 管理或迁移工具，即可使用远程 Windows PowerShell。但是，管理员的计算机必须运行 Windows Management Framework 3.0，它包含 Windows PowerShell v3、WinRM 3.0 和 Windows .NET Framework 4.5。这些组件已安装在运行 Windows 8 或 Windows Server 2012 的计算机上。管理员可针对运行 Windows 7 或 Windows Server 2008 R2 的计算机手动下载这些组件。</span><span class="sxs-lookup"><span data-stu-id="ff088-p108">Administrators do not need to install any Exchange Server management or migration tools to use remote Windows PowerShell. However, administrators' computers must be running the Windows Management Framework 3.0, which contains Windows PowerShell v3 and WinRM 3.0; and Windows .NET Framework 4.5. These components are already installed on computers running Windows 8 or Windows Server 2012. Administrators can manually download these components for computers that are running Windows 7 or Windows Server 2008 R2.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="ff088-141">为了帮助防止受到拒绝服务 (DoS) 攻击，您最多只能打开三次与 Exchange Online 组织的 Windows PowerShell 连接。</span><span class="sxs-lookup"><span data-stu-id="ff088-141">To help prevent denial of service (DoS) attacks, you're limited to three open Windows PowerShell connections to your Exchange Online organization.</span></span> 
  
## <a name="self-service-capabilities-for-exchange-online"></a><span data-ttu-id="ff088-142">Exchange Online 的自助服务功能</span><span class="sxs-lookup"><span data-stu-id="ff088-142">Self-service capabilities for Exchange Online</span></span>

<span data-ttu-id="ff088-p109">以下是通过使用 EAC、远程 Windows PowerShell 和其他工具管理 Exchange Online 时可以使用的重要功能。正如本文档所述，使用这些工具还可以控制其他许多设置。</span><span class="sxs-lookup"><span data-stu-id="ff088-p109">Below are important capabilities that are available for managing Exchange Online by using the EAC, remote Windows PowerShell, and other tools. Many other settings can also be controlled with these tools, as described throughout this document.</span></span>
  
### <a name="mobile-device-security-policies-for-exchange-online"></a><span data-ttu-id="ff088-145">Exchange Online 的移动设备安全策略</span><span class="sxs-lookup"><span data-stu-id="ff088-145">Mobile device security policies for Exchange Online</span></span>

<span data-ttu-id="ff088-p110">Exchange Online 支持与 Exchange Server 2013 相同的 ActiveSync 移动设备策略。管理员可以通过使用 EAC 或远程 Windows PowerShell 为特定用户和组实施和自定义这些安全策略。</span><span class="sxs-lookup"><span data-stu-id="ff088-p110">Exchange Online supports the same ActiveSync policies for mobile devices as Exchange Server 2013. Administrators can enforce and customize these security policies for specific users and groups by using the EAC or remote Windows PowerShell.</span></span>
  
### <a name="message-tracking-for-exchange-online"></a><span data-ttu-id="ff088-148">Exchange Online 的邮件跟踪功能</span><span class="sxs-lookup"><span data-stu-id="ff088-148">Message tracking for Exchange Online</span></span>

<span data-ttu-id="ff088-149">以下主题描述了通过"送达报告"功能跟踪的邮件：[报告功能和疑难解答工具](reporting-features-and-troubleshooting-tools.md).</span><span class="sxs-lookup"><span data-stu-id="ff088-149">Message tracking via the Delivery Reports feature is described in the following topic: [Reporting Features and Troubleshooting Tools](reporting-features-and-troubleshooting-tools.md).</span></span>
  
### <a name="usage-reporting-for-exchange-online"></a><span data-ttu-id="ff088-150">Exchange Online 的使用情况报告功能</span><span class="sxs-lookup"><span data-stu-id="ff088-150">Usage reporting for Exchange Online</span></span>

<span data-ttu-id="ff088-p111">管理员可以使用远程 Windows PowerShell 检索组织中的人员如何使用 Exchange Online 服务的详细信息。可用信息包括：</span><span class="sxs-lookup"><span data-stu-id="ff088-p111">Administrators can use remote Windows PowerShell to retrieve information about how people in their organizations use the Exchange Online service. Available information includes:</span></span>
  
- <span data-ttu-id="ff088-153">显示组织中每个用户的邮箱大小。</span><span class="sxs-lookup"><span data-stu-id="ff088-153">Showing the mailbox size for each user in the organization.</span></span>
    
- <span data-ttu-id="ff088-154">显示邮箱中设置的自定义权限（例如，委派访问权限）。</span><span class="sxs-lookup"><span data-stu-id="ff088-154">Displaying custom permissions that are set on mailboxes, such as delegate access.</span></span>
    
- <span data-ttu-id="ff088-155">提取有关移动设备访问的数据，例如：哪些用户正在通过 Exchange ActiveSync 实现连接、用户正在使用哪些设备、他们上次何时连接。</span><span class="sxs-lookup"><span data-stu-id="ff088-155">Extracting data about mobile device access, such as which users are connecting through Exchange ActiveSync, what devices they are using, and when they last connected.</span></span>
    
<span data-ttu-id="ff088-p112">以 "get-" 开头的远程 Windows PowerShell cmdlet 可从 Exchange Online 系统中提取数据。管理员可从 Windows PowerShell 中以 .csv 格式导出这些信息，以便进行高级分析或报告。</span><span class="sxs-lookup"><span data-stu-id="ff088-p112">Remote Windows PowerShell cmdlets that start with "get-" can fetch data from the Exchange Online system. Administrators can export this information from Windows PowerShell in .csv format for advanced analysis or reporting.</span></span>
  
<span data-ttu-id="ff088-158">若要详细了解可与 Exchange Online 结合使用的 Windows PowerShell cmdlet，请参阅 [Exchange Online cmdlet](https://go.microsoft.com/fwlink/p/?LinkId=271808)。</span><span class="sxs-lookup"><span data-stu-id="ff088-158">For more information about Windows PowerShell cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span></span>
  
### <a name="auditing-for-exchange-online"></a><span data-ttu-id="ff088-159">Exchange Online 的审核功能</span><span class="sxs-lookup"><span data-stu-id="ff088-159">Auditing for Exchange Online</span></span>

<span data-ttu-id="ff088-160">以下主题介绍了审核日志记录功能：[报告功能和疑难解答工具](reporting-features-and-troubleshooting-tools.md).</span><span class="sxs-lookup"><span data-stu-id="ff088-160">The audit logging feature is described in the following topic: [Reporting Features and Troubleshooting Tools](reporting-features-and-troubleshooting-tools.md).</span></span>
  
## <a name="service-and-product-upgrades-for-exchange-online"></a><span data-ttu-id="ff088-161">Exchange Online 的服务和产品升级</span><span class="sxs-lookup"><span data-stu-id="ff088-161">Service and product upgrades for Exchange Online</span></span>

<span data-ttu-id="ff088-p113">Exchange Online 客户可从定期升级至最新 Exchange 技术（其中包括新版本的 Exchange Server）中获益良多。这些升级无需另行收费，且可确保用户始终能够使用最新的 Exchange 软件。</span><span class="sxs-lookup"><span data-stu-id="ff088-p113">Exchange Online customers benefit from periodic upgrades to the latest Exchange technology, including new releases of Exchange Server. These upgrades are made available at no additional charge, and ensure that customers are always using the latest Exchange software.</span></span>
  
<span data-ttu-id="ff088-164">Microsoft 发行 Exchange 主版本后，客户最长可在 12 个月内将服务升级到新版本。</span><span class="sxs-lookup"><span data-stu-id="ff088-164">After a major version of Exchange is released by Microsoft, customers have up to 12 months to upgrade their service to the new release.</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="ff088-165">功能可用性</span><span class="sxs-lookup"><span data-stu-id="ff088-165">Feature Availability</span></span>

<span data-ttu-id="ff088-166">若要查看在各个 Office 365 计划、独立选项和内部部署解决方案之间的功能可用性，请参阅 [Exchange Online 服务说明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="ff088-166">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

