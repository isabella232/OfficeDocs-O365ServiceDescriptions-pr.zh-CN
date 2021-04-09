---
title: 网络
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Microsoft 支持以下网络功能。
ms.openlocfilehash: df2fb9343529a7722fc434a79bf74621b78b787e
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652536"
---
# <a name="networking"></a>网络

Microsoft 支持以下网络功能。
  
## <a name="ports-protocols-and-ip-addresses"></a>端口、协议和 IP 地址

Microsoft 使用 IPv4 和 IPv6 地址。 可选择使用 IPv6 寻址，并且不需要与 Office 365 之间进行连接。 并非所有 Microsoft 365 功能都使用 IPv6 完全启用。 有关 Ipv6 支持的信息，请参阅 [Microsoft 服务中的 IPv6 支持](/office365/enterprise/ipv6-support)。
  
Microsoft 在 Microsoft 帮助中维护允许的 IP 地址列表。 有关详细信息，请参阅 [URL 和 IP 地址范围](/office365/enterprise/urls-and-ip-address-ranges)。 有关由世纪互联运营的 Office 365 的信息，请参阅[由世纪互联运营的 Office 365 的 URL 和 IP 地址](/office365/enterprise/managing-office-365-endpoints)。 有关 Office 365 Germany，请参阅 [Office 365 Germany 终结点](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8)。
  
> [!IMPORTANT]
> 我们强烈建议您允许路由到上述文章中列出的根域名（如 \*.Outlook.com、\*.MicrosoftOnline.com 和 \*.SharePoint.com），而不是路由到特定的 IP 地址子网。如果依赖 IP 地址子网，则进行更改时您的用户会有中断风险。 
  
## <a name="bandwidth-requirements"></a>带宽要求

有关带宽要求的信息，请参阅 [Internet 带宽规划](/office365/enterprise/network-planning-and-performance)。
  
## <a name="connecting-to-microsoft"></a>连接到 Microsoft

所有与 Microsoft 的连接都通过公共 Internet 或专用 Azure ExpressRoute 连接完成，并在适当时受 SSL 保护。 Azure ExpressRoute 允许直接连接到全局 Microsoft 网络，绕过 Internet。 Microsoft 网络合作伙伴提供了到 Microsoft 全球网络的连接。
  
有关 Azure ExpressRoute 的详细信息，请参阅[适用于 Office 365 的 Azure ExpressRoute](/microsoft-365/enterprise/azure-expressroute)。
  
### <a name="wan-accelerators"></a>WAN 加速器

Microsoft 不支持对 Office 365 使用客户拥有的 WAN 加速和缓存设备。如果决定使用 WAN 优化控制器在高延迟和低带宽的条件下改善性能，将需要在使用 Microsoft 解决服务请求问题时禁用此控制器，并与设备供应商合作以获取设备支持。有关详细信息，请参阅[对 Office 365 使用 WAN 加速和缓存设备](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365)。
  
## <a name="the-global-microsoft-network"></a>Microsoft 全球网络

Microsoft 网络基础结构由一个大型的全球项目组合组成，包括数据中心、服务器、内容分发网络、边缘计算节点和光纤网络，以提供服务的全局分布。 尖端服务检测和监控在最深层级与每个组件集成，提供了数据中心、网络主干、Internet Exchange 和 Beyond 的可见性，以帮助发现、诊断和管理出现的中断原因。 此网络致力于维持足够的功能，即使出现大规模网络中断，也不会降低性能。 有关详细信息，请参阅 [Microsoft 全球网络](/azure/networking/microsoft-global-network)。 
  
为了维护客户数据的机密性和完整性，Microsoft 将客户服务网络与 Microsoft 网络分开。 使用多种技术控制信息流，包括但不限于：
  
- 物理分离。通过配置为阻止特定通信模式的路由器在物理上分隔网络段。
    
- 逻辑分离。虚拟 LAN (VLAN) 技术用来进一步分隔通信。
    
- 防火墙。 防火墙和其他网络安全实施点用于限制与向 Internet 公开的系统的数据交换，以及将系统与 Microsoft 管理的后端系统隔离开。 
    
- 协议限制。
    
有关详细信息，请参阅 [Office 365 信任中心](https://www.microsoft.com/trust-center)。 
  
## <a name="feature-availability"></a>功能可用性

若要查看各个计划的功能可用性，请参阅 [Microsoft 365 和 Office 365 平台服务](office-365-platform-service-description.md)说明。
