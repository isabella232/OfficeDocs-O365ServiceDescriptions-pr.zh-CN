---
title: 网络
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Microsoft Office 365 支持以下网络功能。
ms.openlocfilehash: 2245e2e60333d0f1eb85e1243c49c0a04a4f62ec
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/07/2019
ms.locfileid: "30467899"
---
# <a name="networking"></a><span data-ttu-id="e841d-103">网络</span><span class="sxs-lookup"><span data-stu-id="e841d-103">Networking</span></span>

<span data-ttu-id="e841d-104">Microsoft Office 365 支持以下网络功能。</span><span class="sxs-lookup"><span data-stu-id="e841d-104">Microsoft Office 365 supports the following networking features.</span></span>
  
## <a name="ports-protocols-and-ip-addresses"></a><span data-ttu-id="e841d-105">端口、协议和 IP 地址</span><span class="sxs-lookup"><span data-stu-id="e841d-105">Ports, protocols, and IP addresses</span></span>

<span data-ttu-id="e841d-p101">Office 365 使用 IPv4 和 IPv6 地址。可选择使用 IPv6 寻址，并且不需要与 Office 365 之间进行连接。使用 IPv6 时未完全启用所有的 Office 365 功能。有关 Office 365 中的 IPv6 支持的详细信息，请参阅 [Office 365 服务中的 IPv6 支持](https://go.microsoft.com/fwlink/?LinkID=785121&amp;clcid=0x409)。</span><span class="sxs-lookup"><span data-stu-id="e841d-p101">Office 365 uses IPv4 and IPv6 addresses. Use of IPv6 addressing is optional and not required for connectivity with Office 365. Not all Office 365 features are fully enabled using IPv6. For more information about Ipv6 support in Office 365, see [IPv6 support in Office 365 services](https://go.microsoft.com/fwlink/?LinkID=785121&amp;clcid=0x409).</span></span>
  
<span data-ttu-id="e841d-p102">Office 365 在 Office 365 帮助中维护允许的 IP 地址的列表。有关详细信息，请参阅 [Office 365 URL 和 IP 地址范围](https://go.microsoft.com/fwlink/p/?LinkID=243567)。有关由世纪互联运营的 Office 365 的信息，请参阅[由世纪互联运营的 Office 365 的 URL 和 IP 地址](https://go.microsoft.com/fwlink/?LinkID=733351&amp;clcid=0x409)。有关 Office 365 Germany，请参阅 [Office 365 Germany 终结点](https://support.office.com/en-us/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8)。</span><span class="sxs-lookup"><span data-stu-id="e841d-p102">Office 365 maintains a list of allowed IP addresses in the Office 365 help. For more information, see [Office 365 URLs and IP address ranges](https://go.microsoft.com/fwlink/p/?LinkID=243567). For Office 365 operated by 21Vianet, see [URLs and IP Addresses for Office 365 operated by 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733351&amp;clcid=0x409). For Office 365 Germany, see [Office 365 Germany endpoints](https://support.office.com/en-us/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="e841d-p103">我们强烈建议您允许路由到上述文章中列出的根域名（如 \*.Outlook.com、\*.MicrosoftOnline.com 和 \*.SharePoint.com），而不是路由到特定的 IP 地址子网。如果依赖 IP 地址子网，则进行更改时您的用户会有中断风险。</span><span class="sxs-lookup"><span data-stu-id="e841d-p103">We strongly recommend that you enable routing to the root domain names listed in the articles above (such as \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com) instead of routing to specific IP address subnets. Relying on IP address subnets runs the risk of outages for your users as changes are made.</span></span> 
  
## <a name="bandwidth-requirements"></a><span data-ttu-id="e841d-116">带宽要求</span><span class="sxs-lookup"><span data-stu-id="e841d-116">Bandwidth requirements</span></span>

<span data-ttu-id="e841d-117">有关带宽要求的信息，请参阅 [Internet 带宽规划](https://go.microsoft.com/fwlink/p/?LinkID=282467)。</span><span class="sxs-lookup"><span data-stu-id="e841d-117">For information on bandwidth requirements, see [Internet bandwidth planning](https://go.microsoft.com/fwlink/p/?LinkID=282467).</span></span>
  
## <a name="connecting-to-office-365"></a><span data-ttu-id="e841d-118">连接到 Office 365</span><span class="sxs-lookup"><span data-stu-id="e841d-118">Connecting to Office 365</span></span>

<span data-ttu-id="e841d-p104">已经通过公共 Internet 或专用的 Azure ExpressRoute 连接完成了与 Office 365 的所有连接，并根据需要采用 SSL 进行保护。Azure ExpressRoute 允许绕过 Internet 直接连接到 Microsoft 全球网络。Microsoft 网络合作伙伴提供了到 Microsoft 全球网络的连接。</span><span class="sxs-lookup"><span data-stu-id="e841d-p104">All Connections to Office 365 are done over the public Internet or over a private Azure ExpressRoute connection, and are secured by SSL as appropriate. Azure ExpressRoute allows connecting directly to the global Microsoft network, bypassing the Internet. A Microsoft networking partner provides the connectivity to the global Microsoft network.</span></span>
  
<span data-ttu-id="e841d-122">有关 Azure ExpressRoute 的详细信息，请参阅[适用于 Office 365 的 Azure ExpressRoute](https://aka.ms/expressrouteoffice365)。</span><span class="sxs-lookup"><span data-stu-id="e841d-122">For more information about Azure ExpressRoute, see [Azure ExpressRoute for Office 365.](https://aka.ms/expressrouteoffice365)</span></span>
  
### <a name="wan-accelerators"></a><span data-ttu-id="e841d-123">WAN 加速器</span><span class="sxs-lookup"><span data-stu-id="e841d-123">WAN accelerators</span></span>

<span data-ttu-id="e841d-p105">Microsoft 不支持对 Office 365 使用客户拥有的 WAN 加速和缓存设备。如果决定使用 WAN 优化控制器在高延迟和低带宽的条件下改善性能，将需要在使用 Microsoft 解决服务请求问题时禁用此控制器，并与设备供应商合作以获取设备支持。有关详细信息，请参阅[对 Office 365 使用 WAN 加速和缓存设备](https://go.microsoft.com/fwlink/p/?LinkID=282468)。</span><span class="sxs-lookup"><span data-stu-id="e841d-p105">Microsoft does not provide support for customer-owned WAN acceleration and caching devices with Office 365. If you decide to use a WAN optimization controller to improve performance under conditions of high latency or low bandwidth, you'll need to disable it while troubleshooting service requests with Microsoft, and work with your device vendor for device support. For more information, see [WAN Acceleration and caching devices with Office 365](https://go.microsoft.com/fwlink/p/?LinkID=282468).</span></span>
  
## <a name="the-global-microsoft-network"></a><span data-ttu-id="e841d-127">Microsoft 全球网络</span><span class="sxs-lookup"><span data-stu-id="e841d-127">The global Microsoft network</span></span>

<span data-ttu-id="e841d-p106">Office 365 网络基础结构由大型的全球组合产品组成，包括数据中心、服务器、内容分发网络、边缘计算节点和光纤网络，从而可以在全球范围内提供服务。尖端服务检测和监控在最深层级与每个组件集成，提供了数据中心、网络主干、Internet Exchange 和 Beyond 的可见性，以帮助发现、诊断和管理出现的中断原因。此网络致力于维持足够的功能，即使出现大规模网络中断，也不会降低性能。有关详细信息，请参阅 [Global Foundation Services](https://go.microsoft.com/fwlink/p/?LinkID=282622)。</span><span class="sxs-lookup"><span data-stu-id="e841d-p106">The Office 365 networking infrastructure is comprised of a large global portfolio of data centers, servers, content distribution networks, edge computing nodes, and fiber optic networks to provide global distribution of services. Sophisticated service instrumentation and monitoring integrates at the deepest levels with each component, giving visibility into the data center, network backbone, internet exchanges and beyond, to help spot, diagnose and manage the cause of disruptions that arise. The network is built to maintain sufficient capacity even for large scale network interruptions without degradation of performance. For more information, see [Global Foundation Services](https://go.microsoft.com/fwlink/p/?LinkID=282622).</span></span> 
  
<span data-ttu-id="e841d-p107">为了维护客户数据的机密性和完整性，Microsoft 将客户服务网络与 Office 365 网络区分开来。使用多种技术控制信息流，包括但不限于：</span><span class="sxs-lookup"><span data-stu-id="e841d-p107">To maintain the confidentiality and integrity of customer data, Microsoft keeps consumer services networks separate from Office 365 networks. Multiple techniques are used to control information flows, including but not limited to:</span></span>
  
- <span data-ttu-id="e841d-p108">物理分离。通过配置为阻止特定通信模式的路由器在物理上分隔网络段。</span><span class="sxs-lookup"><span data-stu-id="e841d-p108">Physical separation. Network segments are physically separated by routers that are configured to prevent specific communication patterns.</span></span>
    
- <span data-ttu-id="e841d-p109">逻辑分离。虚拟 LAN (VLAN) 技术用来进一步分隔通信。</span><span class="sxs-lookup"><span data-stu-id="e841d-p109">Logical separation. Virtual LAN (VLAN) technology is used to further separate communications.</span></span>
    
- <span data-ttu-id="e841d-p110">防火墙。防火墙和其他网络安全实施点用于限制与对 Internet 公开的系统进行数据交换，并将这些系统与 Microsoft 管理的后台系统隔离开来。</span><span class="sxs-lookup"><span data-stu-id="e841d-p110">Firewalls. Firewalls and other network security enforcement points are used to limit data exchanges with systems that are exposed to the Internet, and to isolate systems from back-end systems managed by Microsoft.</span></span> 
    
- <span data-ttu-id="e841d-140">协议限制。</span><span class="sxs-lookup"><span data-stu-id="e841d-140">Protocol restrictions.</span></span>
    
<span data-ttu-id="e841d-141">有关详细信息，请参阅 [Office 365 信任中心](https://go.microsoft.com/fwlink/p/?LinkID=282621)。</span><span class="sxs-lookup"><span data-stu-id="e841d-141">For more information, see the [Office 365 Trust Center](https://go.microsoft.com/fwlink/p/?LinkID=282621).</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="e841d-142">功能可用性</span><span class="sxs-lookup"><span data-stu-id="e841d-142">Feature availability</span></span>

<span data-ttu-id="e841d-143">若要查看各个 Office 365 计划的功能可用性，请参阅 [Office 365 平台服务说明](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx)。</span><span class="sxs-lookup"><span data-stu-id="e841d-143">To view feature availability across Office 365 plans, see [Office 365 Platform Service Description](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx).</span></span>
  

