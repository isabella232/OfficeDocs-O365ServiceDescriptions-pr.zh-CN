---
title: Exchange Online 设置和管理
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-administration-and-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 80c07748-ac57-4b90-97dd-a2d1115009a6
description: 本文介绍可用于自定义 Exchange Online 设置并将组织的 Exchange Online 环境保持启动、运行和当前状态的管理控件和支持。 它包括有关组织可以使用的自助式管理工具和功能、Microsoft 管理责任和性能承诺以及服务与产品升级的信息。
ms.openlocfilehash: 53179b3526a53333583c8265a501c743658348cd
ms.sourcegitcommit: 7a68dc894dde0d06fab014c56914a78aa8cda847
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/21/2020
ms.locfileid: "43640330"
---
# <a name="exchange-online-setup-and-administration"></a><span data-ttu-id="8d879-104">Exchange Online 设置和管理</span><span class="sxs-lookup"><span data-stu-id="8d879-104">Exchange Online setup and administration</span></span>

<span data-ttu-id="8d879-105">本文介绍可用于自定义 Exchange Online 设置并将组织的 Exchange Online 环境保持启动、运行和当前状态的管理控件和支持。</span><span class="sxs-lookup"><span data-stu-id="8d879-105">This article describes the administration controls and support that are available to customize Exchange Online settings and keep an organization's Exchange Online environment up, running, and current.</span></span> <span data-ttu-id="8d879-106">它包括有关组织可以使用的自助式管理工具和功能、Microsoft 管理责任和性能承诺以及服务与产品升级的信息。</span><span class="sxs-lookup"><span data-stu-id="8d879-106">It includes information about self-service administration tools and capabilities available to organizations; Microsoft administration responsibilities and performance commitments; and service and product upgrades.</span></span>
  
## <a name="self-service-administration-tools"></a><span data-ttu-id="8d879-107">自助服务管理工具</span><span class="sxs-lookup"><span data-stu-id="8d879-107">Self-service administration tools</span></span>

<span data-ttu-id="8d879-108">尽管 Microsoft 直接控制所有 Exchange Online 数据中心并负责整体系统性能，但它只能控制组合在一起以提供用户的总体体验的部分元素。</span><span class="sxs-lookup"><span data-stu-id="8d879-108">Although Microsoft directly controls all Exchange Online data centers and is responsible for overall system performance, it can control only a portion of the elements that combine to provide the total experience for users.</span></span> <span data-ttu-id="8d879-109">组织本身负责到数据中心、客户广域网 (WAN) 和客户局域网 (LAN) 的网络连接。</span><span class="sxs-lookup"><span data-stu-id="8d879-109">Organizations themselves are responsible for the network connections to the data centers, the customer's wide area network (WAN), and the customer's local area networks (LANs).</span></span> <span data-ttu-id="8d879-110">此外，还负责用户设备及其配置。</span><span class="sxs-lookup"><span data-stu-id="8d879-110">Additionally, they are in charge of user devices and their configuration.</span></span><span data-ttu-id="8d879-111">它们也负责维护每个用户的任何所需功能需要的授权，包括但不限于管理这些功能的能力，前提是用户需要访问此功能。</span><span class="sxs-lookup"><span data-stu-id="8d879-111">  They are also responsible for maintaining the required licensing per user for any desired feature, including, but not limited to, the ability to manage these features, for as long as the user needs access to the feature.</span></span>
  
<span data-ttu-id="8d879-112">因此，Exchange Online 为客户管理员提供了以下工具（如下所述），帮助他们管理消息传递相关的任务：</span><span class="sxs-lookup"><span data-stu-id="8d879-112">Exchange Online therefore provides customer administrators with the following tools, described below, to manage a variety of messaging-related tasks:</span></span>
  
- [<span data-ttu-id="8d879-113">Microsoft Office 365 门户</span><span class="sxs-lookup"><span data-stu-id="8d879-113">Microsoft Office 365 portal</span></span>](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [<span data-ttu-id="8d879-114">Microsoft 365 管理中心</span><span class="sxs-lookup"><span data-stu-id="8d879-114">Microsoft 365 admin center</span></span>](#microsoft-365-admin-center)
    
- [<span data-ttu-id="8d879-115">Exchange 管理中心</span><span class="sxs-lookup"><span data-stu-id="8d879-115">Exchange admin center</span></span>](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [<span data-ttu-id="8d879-116">Exchange Online 的远程 Windows PowerShell</span><span class="sxs-lookup"><span data-stu-id="8d879-116">Remote Windows PowerShell for Exchange Online</span></span>](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a><span data-ttu-id="8d879-117">Microsoft Office 365 门户</span><span class="sxs-lookup"><span data-stu-id="8d879-117">Microsoft Office 365 portal</span></span>

<span data-ttu-id="8d879-118">Microsoft Office 365 门户 ([https://portal.office.com](https://portal.office.com)) 门户是一个网站，管理员与合作伙伴可通过其购买和管理 Office 365 服务，而用户则可在其中访问和使用 Office 365 协作工具。</span><span class="sxs-lookup"><span data-stu-id="8d879-118">The Microsoft Office 365 portal, at [https://portal.office.com](https://portal.office.com), is the website through which administrators and partners purchase and manage Office 365 services and where users access and use Office 365 collaborative tools.</span></span>
  
### <a name="microsoft-365-admin-center"></a><span data-ttu-id="8d879-119">Microsoft 365 管理中心</span><span class="sxs-lookup"><span data-stu-id="8d879-119">Microsoft 365 admin center</span></span>

<span data-ttu-id="8d879-120">Microsoft 365 管理中心是一个 web 门户，其中每个公司的服务管理员都可以管理他们订阅的每个 Microsoft 服务的用户帐户和设置。</span><span class="sxs-lookup"><span data-stu-id="8d879-120">The Microsoft 365 admin center is the web portal from which each company's service administrator can manage user accounts and settings for each of the Microsoft services to which they subscribe.</span></span> <span data-ttu-id="8d879-121">在 Microsoft 365 管理中心内，管理员可以访问 Exchange 管理中心（EAC）的链接，在其中可以管理特定于 Exchange Online 的设置。</span><span class="sxs-lookup"><span data-stu-id="8d879-121">From within the Microsoft 365 admin center, administrators can follow links to the Exchange admin center (EAC), where they can manage settings specific to Exchange Online.</span></span> <span data-ttu-id="8d879-122">若要详细了解如何使用 Microsoft 365 管理中心启动和运行，请参阅以下视频： [Office 365 企业版简介](https://go.microsoft.com/fwlink/p/?LinkId=271806)。</span><span class="sxs-lookup"><span data-stu-id="8d879-122">For more information about getting up and running using the Microsoft 365 admin center, see the following video: [Introducing Office 365 Enterprise](https://go.microsoft.com/fwlink/p/?LinkId=271806).</span></span>
  
### <a name="exchange-admin-center"></a><span data-ttu-id="8d879-123">Exchange 管理中心</span><span class="sxs-lookup"><span data-stu-id="8d879-123">Exchange admin center</span></span>

<span data-ttu-id="8d879-p105">Exchange Online 提供单一的统一管理控制台，该控制台易于使用，并针对内部部署、联机部署或混合部署进行了管理优化。在 Exchange 管理中心 (EAC) 内，管理员可以管理特定于 Exchange 的相关设置。</span><span class="sxs-lookup"><span data-stu-id="8d879-p105">Exchange Online provides a single unified management console that allows for ease of use and is optimized for management of on-premises, online, or hybrid deployments. The Exchange admin center (EAC) is where administrators can manage Exchange-specific settings.</span></span>
  
<span data-ttu-id="8d879-126">若要详细了解如何使用 EAC 管理 Exchange Online，请参阅 [Exchange 管理中心](https://go.microsoft.com/fwlink/p/?LinkId=271807)。</span><span class="sxs-lookup"><span data-stu-id="8d879-126">For more information about how to use the EAC to manage Exchange Online, see [Exchange admin center](https://go.microsoft.com/fwlink/p/?LinkId=271807).</span></span>
  
### <a name="remote-windows-powershell-for-exchange-online"></a><span data-ttu-id="8d879-127">Exchange Online 的远程 Windows PowerShell</span><span class="sxs-lookup"><span data-stu-id="8d879-127">Remote Windows PowerShell for Exchange Online</span></span>

<span data-ttu-id="8d879-p106">使用远程 Windows PowerShell，管理员可以连接到 Exchange Online，执行使用 EAC 无法执行的管理任务。这些任务包括：自动运行重复任务、从自定义报告中提取数据、自定义策略，以及将 Exchange Online 连接到现有基础结构和流程。有关详细信息，请参阅[使用远程 PowerShell 连接到 Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=308994)。</span><span class="sxs-lookup"><span data-stu-id="8d879-p106">Using remote Windows PowerShell, administrators can connect to Exchange Online to perform management tasks that are not available or practical using the EAC. These include the ability to automate repetitive tasks, extract data for custom reports, customize policies, and connect Exchange Online to existing infrastructure and processes. For more information, see [Connect to Exchange Online Using Remote PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).</span></span>
  
<span data-ttu-id="8d879-p107">Exchange Online 使用与 Exchange Server 2013 相同的 Windows PowerShell cmdlet，但某些特定的命令和参数不可用，其原因在于这些功能在 Exchange Online 中不适用。有关可与 Exchange Online 结合使用的 cmdlet 列表，请参阅 [Exchange Online cmdlet](https://go.microsoft.com/fwlink/p/?LinkId=271808)。</span><span class="sxs-lookup"><span data-stu-id="8d879-p107">Exchange Online uses the same Windows PowerShell cmdlets as Exchange Server 2013, with certain commands and parameters unavailable because these features do not apply in Exchange Online. For a list of cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span></span>
  
<span data-ttu-id="8d879-p108">管理员无需安装任何 Exchange Server 管理或迁移工具，即可使用远程 Windows PowerShell。但是，管理员的计算机必须运行 Windows Management Framework 3.0，它包含 Windows PowerShell v3、WinRM 3.0 和 Windows .NET Framework 4.5。这些组件已安装在运行 Windows 8 或 Windows Server 2012 的计算机上。管理员可针对运行 Windows 7 或 Windows Server 2008 R2 的计算机手动下载这些组件。</span><span class="sxs-lookup"><span data-stu-id="8d879-p108">Administrators do not need to install any Exchange Server management or migration tools to use remote Windows PowerShell. However, administrators' computers must be running the Windows Management Framework 3.0, which contains Windows PowerShell v3 and WinRM 3.0; and Windows .NET Framework 4.5. These components are already installed on computers running Windows 8 or Windows Server 2012. Administrators can manually download these components for computers that are running Windows 7 or Windows Server 2008 R2.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="8d879-137">为了帮助防止受到拒绝服务 (DoS) 攻击，您最多只能打开三次与 Exchange Online 组织的 Windows PowerShell 连接。</span><span class="sxs-lookup"><span data-stu-id="8d879-137">To help prevent denial of service (DoS) attacks, you're limited to three open Windows PowerShell connections to your Exchange Online organization.</span></span> 
  
## <a name="self-service-capabilities-for-exchange-online"></a><span data-ttu-id="8d879-138">Exchange Online 的自助服务功能</span><span class="sxs-lookup"><span data-stu-id="8d879-138">Self-service capabilities for Exchange Online</span></span>

<span data-ttu-id="8d879-p109">以下是通过使用 EAC、远程 Windows PowerShell 和其他工具管理 Exchange Online 时可以使用的重要功能。正如本文档所述，使用这些工具还可以控制其他许多设置。</span><span class="sxs-lookup"><span data-stu-id="8d879-p109">Below are important capabilities that are available for managing Exchange Online by using the EAC, remote Windows PowerShell, and other tools. Many other settings can also be controlled with these tools, as described throughout this document.</span></span>
  
### <a name="mobile-device-security-policies-for-exchange-online"></a><span data-ttu-id="8d879-141">Exchange Online 的移动设备安全策略</span><span class="sxs-lookup"><span data-stu-id="8d879-141">Mobile device security policies for Exchange Online</span></span>

<span data-ttu-id="8d879-p110">Exchange Online 支持与 Exchange Server 2013 相同的 ActiveSync 移动设备策略。管理员可以通过使用 EAC 或远程 Windows PowerShell 为特定用户和组实施和自定义这些安全策略。</span><span class="sxs-lookup"><span data-stu-id="8d879-p110">Exchange Online supports the same ActiveSync policies for mobile devices as Exchange Server 2013. Administrators can enforce and customize these security policies for specific users and groups by using the EAC or remote Windows PowerShell.</span></span>
  
### <a name="message-tracking-for-exchange-online"></a><span data-ttu-id="8d879-144">Exchange Online 的邮件跟踪功能</span><span class="sxs-lookup"><span data-stu-id="8d879-144">Message tracking for Exchange Online</span></span>

<span data-ttu-id="8d879-145">通过送达报告功能进行邮件跟踪在以下主题中进行了介绍：[报告功能和疑难解答工具](reporting-features-and-troubleshooting-tools.md)。</span><span class="sxs-lookup"><span data-stu-id="8d879-145">Message tracking via the Delivery Reports feature is described in the following topic: [Reporting features and troubleshooting tools](reporting-features-and-troubleshooting-tools.md).</span></span>
  
### <a name="usage-reporting-for-exchange-online"></a><span data-ttu-id="8d879-146">Exchange Online 的使用情况报告功能</span><span class="sxs-lookup"><span data-stu-id="8d879-146">Usage reporting for Exchange Online</span></span>

<span data-ttu-id="8d879-p111">管理员可以使用远程 Windows PowerShell 检索组织中的人员如何使用 Exchange Online 服务的详细信息。可用信息包括：</span><span class="sxs-lookup"><span data-stu-id="8d879-p111">Administrators can use remote Windows PowerShell to retrieve information about how people in their organizations use the Exchange Online service. Available information includes:</span></span>
  
- <span data-ttu-id="8d879-149">显示组织中每个用户的邮箱大小。</span><span class="sxs-lookup"><span data-stu-id="8d879-149">Showing the mailbox size for each user in the organization.</span></span>
    
- <span data-ttu-id="8d879-150">显示邮箱中设置的自定义权限（例如，委派访问权限）。</span><span class="sxs-lookup"><span data-stu-id="8d879-150">Displaying custom permissions that are set on mailboxes, such as delegate access.</span></span>
    
- <span data-ttu-id="8d879-151">提取有关移动设备访问的数据，例如：哪些用户正在通过 Exchange ActiveSync 实现连接、用户正在使用哪些设备、他们上次何时连接。</span><span class="sxs-lookup"><span data-stu-id="8d879-151">Extracting data about mobile device access, such as which users are connecting through Exchange ActiveSync, what devices they are using, and when they last connected.</span></span>
    
<span data-ttu-id="8d879-p112">以 "get-" 开头的远程 Windows PowerShell cmdlet 可从 Exchange Online 系统中提取数据。管理员可从 Windows PowerShell 中以 .csv 格式导出这些信息，以便进行高级分析或报告。</span><span class="sxs-lookup"><span data-stu-id="8d879-p112">Remote Windows PowerShell cmdlets that start with "get-" can fetch data from the Exchange Online system. Administrators can export this information from Windows PowerShell in .csv format for advanced analysis or reporting.</span></span>
  
<span data-ttu-id="8d879-154">若要详细了解可与 Exchange Online 结合使用的 Windows PowerShell cmdlet，请参阅 [Exchange Online cmdlet](https://go.microsoft.com/fwlink/p/?LinkId=271808)。</span><span class="sxs-lookup"><span data-stu-id="8d879-154">For more information about Windows PowerShell cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span></span>
  
### <a name="auditing-for-exchange-online"></a><span data-ttu-id="8d879-155">Exchange Online 的审核功能</span><span class="sxs-lookup"><span data-stu-id="8d879-155">Auditing for Exchange Online</span></span>

<span data-ttu-id="8d879-156">以下主题中介绍了审核日志记录功能：[报告功能和疑难解答工具](reporting-features-and-troubleshooting-tools.md)。</span><span class="sxs-lookup"><span data-stu-id="8d879-156">The audit logging feature is described in the following topic: [Reporting features and troubleshooting tools](reporting-features-and-troubleshooting-tools.md).</span></span>
  
## <a name="service-and-product-upgrades-for-exchange-online"></a><span data-ttu-id="8d879-157">Exchange Online 的服务和产品升级</span><span class="sxs-lookup"><span data-stu-id="8d879-157">Service and product upgrades for Exchange Online</span></span>

<span data-ttu-id="8d879-p113">Exchange Online 客户可从定期升级至最新 Exchange 技术（其中包括新版本的 Exchange Server）中获益良多。这些升级无需另行收费，且可确保用户始终能够使用最新的 Exchange 软件。</span><span class="sxs-lookup"><span data-stu-id="8d879-p113">Exchange Online customers benefit from periodic upgrades to the latest Exchange technology, including new releases of Exchange Server. These upgrades are made available at no additional charge, and ensure that customers are always using the latest Exchange software.</span></span>
  
<span data-ttu-id="8d879-160">Microsoft 发行 Exchange 主版本后，客户最长可在 12 个月内将服务升级到新版本。</span><span class="sxs-lookup"><span data-stu-id="8d879-160">After a major version of Exchange is released by Microsoft, customers have up to 12 months to upgrade their service to the new release.</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="8d879-161">功能可用性</span><span class="sxs-lookup"><span data-stu-id="8d879-161">Feature availability</span></span>

<span data-ttu-id="8d879-162">若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅[Exchange Online 服务说明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="8d879-162">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online service description](exchange-online-service-description.md).</span></span>
  