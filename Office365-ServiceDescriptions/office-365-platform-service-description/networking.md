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
# <a name="networking"></a>网络

Microsoft 支持以下网络功能。
  
## <a name="ports-protocols-and-ip-addresses"></a>端口、协议和 IP 地址

Microsoft 使用 IPv4 和 IPv6 地址。 可选择使用 IPv6 寻址，并且不需要与 Office 365 之间进行连接。 并非所有 Microsoft 365 功能都使用 IPv6 完全启用。 有关 Ipv6 支持的详细信息，请参阅[Microsoft 服务中的 Ipv6 支持](https://docs.microsoft.com/office365/enterprise/ipv6-support)。
  
Microsoft 在 Microsoft 帮助中维护允许的 IP 地址的列表。 有关详细信息，请参阅[url 和 IP 地址范围](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)。 有关由世纪互联运营的 Office 365 的信息，请参阅[由世纪互联运营的 Office 365 的 URL 和 IP 地址](https://docs.microsoft.com/office365/enterprise/managing-office-365-endpoints)。 有关 Office 365 Germany，请参阅 [Office 365 Germany 终结点](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8)。
  
> [!IMPORTANT]
> We strongly recommend that you enable routing to the root domain names listed in the articles above (such as \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com) instead of routing to specific IP address subnets. Relying on IP address subnets runs the risk of outages for your users as changes are made. 
  
## <a name="bandwidth-requirements"></a>带宽要求

有关带宽要求的信息，请参阅 [Internet 带宽规划](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance)。
  
## <a name="connecting-to-microsoft"></a>连接到 Microsoft

与 Microsoft 的所有连接都通过公共 internet 或专用 Azure ExpressRoute 连接完成，并根据需要由 SSL 进行保护。 通过 Azure ExpressRoute，可以绕过 internet 直接连接到全局 Microsoft 网络。 Microsoft 网络合作伙伴提供了到 Microsoft 全球网络的连接。
  
有关 Azure ExpressRoute 的详细信息，请参阅[适用于 Office 365 的 Azure ExpressRoute](https://aka.ms/expressrouteoffice365)。
  
### <a name="wan-accelerators"></a>WAN 加速器

Microsoft does not provide support for customer-owned WAN acceleration and caching devices with Office 365. If you decide to use a WAN optimization controller to improve performance under conditions of high latency or low bandwidth, you'll need to disable it while troubleshooting service requests with Microsoft, and work with your device vendor for device support. For more information, see [WAN Acceleration and caching devices with Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).
  
## <a name="the-global-microsoft-network"></a>Microsoft 全球网络

Microsoft 网络基础结构由一系列大型的数据中心、服务器、内容分发网络、边缘计算节点以及光纤网络组成，以提供服务的全局分发。 尖端服务检测和监控在最深层级与每个组件集成，提供了数据中心、网络主干、Internet Exchange 和 Beyond 的可见性，以帮助发现、诊断和管理出现的中断原因。 此网络致力于维持足够的功能，即使出现大规模网络中断，也不会降低性能。 有关详细信息，请参阅[Microsoft 全球网络](https://docs.microsoft.com/azure/networking/microsoft-global-network)。 
  
为了维护客户数据的机密性和完整性，Microsoft 保留了独立于 Microsoft 网络的消费者服务网络。 使用多种技术控制信息流，包括但不限于：
  
- Physical separation. Network segments are physically separated by routers that are configured to prevent specific communication patterns.
    
- Logical separation. Virtual LAN (VLAN) technology is used to further separate communications.
    
- 防火墙。 防火墙和其他网络安全强制点用于限制与向 internet 公开的系统进行的数据交换，并将系统与 Microsoft 托管的后端系统隔离。 
    
- 协议限制。
    
有关详细信息，请参阅 [Office 365 信任中心](https://www.microsoft.com/trust-center)。 
  
## <a name="feature-availability"></a>功能可用性

若要查看各个计划的功能可用性，请参阅[Microsoft 365 And Office 365 platform service description](office-365-platform-service-description.md)。
  

