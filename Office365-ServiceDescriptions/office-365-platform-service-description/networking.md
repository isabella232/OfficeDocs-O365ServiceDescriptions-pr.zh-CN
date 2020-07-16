---
title: 网络
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Microsoft 支持以下网络功能。
ms.openlocfilehash: 0f0554bdd907a6f0a37299dc3e38e5f778e7187e
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132326"
---
# <a name="networking"></a><span data-ttu-id="fad43-103">网络</span><span class="sxs-lookup"><span data-stu-id="fad43-103">Networking</span></span>

<span data-ttu-id="fad43-104">Microsoft 支持以下网络功能。</span><span class="sxs-lookup"><span data-stu-id="fad43-104">Microsoft supports the following networking features.</span></span>
  
## <a name="ports-protocols-and-ip-addresses"></a><span data-ttu-id="fad43-105">端口、协议和 IP 地址</span><span class="sxs-lookup"><span data-stu-id="fad43-105">Ports, protocols, and IP addresses</span></span>

<span data-ttu-id="fad43-106">Microsoft 使用 IPv4 和 IPv6 地址。</span><span class="sxs-lookup"><span data-stu-id="fad43-106">Microsoft uses IPv4 and IPv6 addresses.</span></span> <span data-ttu-id="fad43-107">可选择使用 IPv6 寻址，并且不需要与 Office 365 之间进行连接。</span><span class="sxs-lookup"><span data-stu-id="fad43-107">Use of IPv6 addressing is optional and not required for connectivity with Office 365.</span></span> <span data-ttu-id="fad43-108">并非所有 Microsoft 365 功能都使用 IPv6 完全启用。</span><span class="sxs-lookup"><span data-stu-id="fad43-108">Not all Microsoft 365 features are fully enabled using IPv6.</span></span> <span data-ttu-id="fad43-109">有关 Ipv6 支持的详细信息，请参阅[Microsoft 服务中的 Ipv6 支持](https://docs.microsoft.com/office365/enterprise/ipv6-support)。</span><span class="sxs-lookup"><span data-stu-id="fad43-109">For more information about Ipv6 support, see [IPv6 support in Microsoft services](https://docs.microsoft.com/office365/enterprise/ipv6-support).</span></span>
  
<span data-ttu-id="fad43-110">Microsoft 在 Microsoft 帮助中维护允许的 IP 地址的列表。</span><span class="sxs-lookup"><span data-stu-id="fad43-110">Microsoft maintains a list of allowed IP addresses in the Microsoft help.</span></span> <span data-ttu-id="fad43-111">有关详细信息，请参阅[url 和 IP 地址范围](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)。</span><span class="sxs-lookup"><span data-stu-id="fad43-111">For more information, see [URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).</span></span> <span data-ttu-id="fad43-112">有关由世纪互联运营的 Office 365 的信息，请参阅[由世纪互联运营的 Office 365 的 URL 和 IP 地址](https://docs.microsoft.com/office365/enterprise/managing-office-365-endpoints)。</span><span class="sxs-lookup"><span data-stu-id="fad43-112">For Office 365 operated by 21Vianet, see [URLs and IP Addresses for Office 365 operated by 21Vianet](https://docs.microsoft.com/office365/enterprise/managing-office-365-endpoints).</span></span> <span data-ttu-id="fad43-113">有关 Office 365 Germany，请参阅 [Office 365 Germany 终结点](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8)。</span><span class="sxs-lookup"><span data-stu-id="fad43-113">For Office 365 Germany, see [Office 365 Germany endpoints](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="fad43-p103">我们强烈建议您允许路由到上述文章中列出的根域名（如 \*.Outlook.com、\*.MicrosoftOnline.com 和 \*.SharePoint.com），而不是路由到特定的 IP 地址子网。如果依赖 IP 地址子网，则进行更改时您的用户会有中断风险。</span><span class="sxs-lookup"><span data-stu-id="fad43-p103">We strongly recommend that you enable routing to the root domain names listed in the articles above (such as \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com) instead of routing to specific IP address subnets. Relying on IP address subnets runs the risk of outages for your users as changes are made.</span></span> 
  
## <a name="bandwidth-requirements"></a><span data-ttu-id="fad43-116">带宽要求</span><span class="sxs-lookup"><span data-stu-id="fad43-116">Bandwidth requirements</span></span>

<span data-ttu-id="fad43-117">有关带宽要求的信息，请参阅 [Internet 带宽规划](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance)。</span><span class="sxs-lookup"><span data-stu-id="fad43-117">For information on bandwidth requirements, see [Internet bandwidth planning](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance).</span></span>
  
## <a name="connecting-to-microsoft"></a><span data-ttu-id="fad43-118">连接到 Microsoft</span><span class="sxs-lookup"><span data-stu-id="fad43-118">Connecting to Microsoft</span></span>

<span data-ttu-id="fad43-119">与 Microsoft 的所有连接都通过公共 internet 或专用 Azure ExpressRoute 连接完成，并根据需要由 SSL 进行保护。</span><span class="sxs-lookup"><span data-stu-id="fad43-119">All Connections to Microsoft are done over the public internet or over a private Azure ExpressRoute connection, and are secured by SSL as appropriate.</span></span> <span data-ttu-id="fad43-120">通过 Azure ExpressRoute，可以绕过 internet 直接连接到全局 Microsoft 网络。</span><span class="sxs-lookup"><span data-stu-id="fad43-120">Azure ExpressRoute allows connecting directly to the global Microsoft network, bypassing the internet.</span></span> <span data-ttu-id="fad43-121">Microsoft 网络合作伙伴提供了到 Microsoft 全球网络的连接。</span><span class="sxs-lookup"><span data-stu-id="fad43-121">A Microsoft networking partner provides the connectivity to the global Microsoft network.</span></span>
  
<span data-ttu-id="fad43-122">有关 Azure ExpressRoute 的详细信息，请参阅[适用于 Office 365 的 Azure ExpressRoute](https://aka.ms/expressrouteoffice365)。</span><span class="sxs-lookup"><span data-stu-id="fad43-122">For more information about Azure ExpressRoute, see [Azure ExpressRoute for Office 365.](https://aka.ms/expressrouteoffice365)</span></span>
  
### <a name="wan-accelerators"></a><span data-ttu-id="fad43-123">WAN 加速器</span><span class="sxs-lookup"><span data-stu-id="fad43-123">WAN accelerators</span></span>

<span data-ttu-id="fad43-p105">Microsoft 不支持对 Office 365 使用客户拥有的 WAN 加速和缓存设备。如果决定使用 WAN 优化控制器在高延迟和低带宽的条件下改善性能，将需要在使用 Microsoft 解决服务请求问题时禁用此控制器，并与设备供应商合作以获取设备支持。有关详细信息，请参阅[对 Office 365 使用 WAN 加速和缓存设备](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365)。</span><span class="sxs-lookup"><span data-stu-id="fad43-p105">Microsoft does not provide support for customer-owned WAN acceleration and caching devices with Office 365. If you decide to use a WAN optimization controller to improve performance under conditions of high latency or low bandwidth, you'll need to disable it while troubleshooting service requests with Microsoft, and work with your device vendor for device support. For more information, see [WAN Acceleration and caching devices with Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).</span></span>
  
## <a name="the-global-microsoft-network"></a><span data-ttu-id="fad43-127">Microsoft 全球网络</span><span class="sxs-lookup"><span data-stu-id="fad43-127">The global Microsoft network</span></span>

<span data-ttu-id="fad43-128">Microsoft 网络基础结构由一系列大型的数据中心、服务器、内容分发网络、边缘计算节点以及光纤网络组成，以提供服务的全局分发。</span><span class="sxs-lookup"><span data-stu-id="fad43-128">The Microsoft networking infrastructure is comprised of a large global portfolio of data centers, servers, content distribution networks, edge computing nodes, and fiber optic networks to provide global distribution of services.</span></span> <span data-ttu-id="fad43-129">尖端服务检测和监控在最深层级与每个组件集成，提供了数据中心、网络主干、Internet Exchange 和 Beyond 的可见性，以帮助发现、诊断和管理出现的中断原因。</span><span class="sxs-lookup"><span data-stu-id="fad43-129">Sophisticated service instrumentation and monitoring integrates at the deepest levels with each component, giving visibility into the data center, network backbone, internet exchanges and beyond, to help spot, diagnose and manage the cause of disruptions that arise.</span></span> <span data-ttu-id="fad43-130">此网络致力于维持足够的功能，即使出现大规模网络中断，也不会降低性能。</span><span class="sxs-lookup"><span data-stu-id="fad43-130">The network is built to maintain sufficient capacity even for large scale network interruptions without degradation of performance.</span></span> <span data-ttu-id="fad43-131">有关详细信息，请参阅[Microsoft 全球网络](https://docs.microsoft.com/azure/networking/microsoft-global-network)。</span><span class="sxs-lookup"><span data-stu-id="fad43-131">For more information, see [Microsoft Global Network](https://docs.microsoft.com/azure/networking/microsoft-global-network).</span></span> 
  
<span data-ttu-id="fad43-132">为了维护客户数据的机密性和完整性，Microsoft 保留了独立于 Microsoft 网络的消费者服务网络。</span><span class="sxs-lookup"><span data-stu-id="fad43-132">To maintain the confidentiality and integrity of customer data, Microsoft keeps consumer services networks separate from Microsoft networks.</span></span> <span data-ttu-id="fad43-133">使用多种技术控制信息流，包括但不限于：</span><span class="sxs-lookup"><span data-stu-id="fad43-133">Multiple techniques are used to control information flows, including but not limited to:</span></span>
  
- <span data-ttu-id="fad43-p108">物理分离。通过配置为阻止特定通信模式的路由器在物理上分隔网络段。</span><span class="sxs-lookup"><span data-stu-id="fad43-p108">Physical separation. Network segments are physically separated by routers that are configured to prevent specific communication patterns.</span></span>
    
- <span data-ttu-id="fad43-p109">逻辑分离。虚拟 LAN (VLAN) 技术用来进一步分隔通信。</span><span class="sxs-lookup"><span data-stu-id="fad43-p109">Logical separation. Virtual LAN (VLAN) technology is used to further separate communications.</span></span>
    
- <span data-ttu-id="fad43-138">防火墙。</span><span class="sxs-lookup"><span data-stu-id="fad43-138">Firewalls.</span></span> <span data-ttu-id="fad43-139">防火墙和其他网络安全强制点用于限制与向 internet 公开的系统进行的数据交换，并将系统与 Microsoft 托管的后端系统隔离。</span><span class="sxs-lookup"><span data-stu-id="fad43-139">Firewalls and other network security enforcement points are used to limit data exchanges with systems that are exposed to the internet, and to isolate systems from back-end systems managed by Microsoft.</span></span> 
    
- <span data-ttu-id="fad43-140">协议限制。</span><span class="sxs-lookup"><span data-stu-id="fad43-140">Protocol restrictions.</span></span>
    
<span data-ttu-id="fad43-141">有关详细信息，请参阅 [Office 365 信任中心](https://www.microsoft.com/trust-center)。</span><span class="sxs-lookup"><span data-stu-id="fad43-141">For more information, see the [Office 365 Trust Center](https://www.microsoft.com/trust-center).</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="fad43-142">功能可用性</span><span class="sxs-lookup"><span data-stu-id="fad43-142">Feature availability</span></span>

<span data-ttu-id="fad43-143">若要查看各个计划的功能可用性，请参阅[Microsoft 365 And Office 365 platform service description](office-365-platform-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="fad43-143">To view feature availability across plans, see [Microsoft 365 and Office 365 platform service description](office-365-platform-service-description.md).</span></span>
  

