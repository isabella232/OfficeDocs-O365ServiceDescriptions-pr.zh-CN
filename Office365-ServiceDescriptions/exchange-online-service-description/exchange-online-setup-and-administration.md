---
title: Exchange Online 设置和管理
ms.author: office365servicedesc
author: pamelaar
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
ms.openlocfilehash: 19ec50b3f502ee111de05e1a115d17f16fec3569
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132997"
---
# <a name="exchange-online-setup-and-administration"></a>Exchange Online 设置和管理

本文介绍可用于自定义 Exchange Online 设置并将组织的 Exchange Online 环境保持启动、运行和当前状态的管理控件和支持。 它包括有关组织可以使用的自助式管理工具和功能、Microsoft 管理责任和性能承诺以及服务与产品升级的信息。
  
## <a name="self-service-administration-tools"></a>自助服务管理工具

尽管 Microsoft 直接控制所有 Exchange Online 数据中心并负责整体系统性能，但它只能控制组合在一起以提供用户的总体体验的部分元素。 组织本身负责到数据中心、客户广域网 (WAN) 和客户局域网 (LAN) 的网络连接。 此外，还负责用户设备及其配置。它们也负责维护每个用户的任何所需功能需要的授权，包括但不限于管理这些功能的能力，前提是用户需要访问此功能。
  
因此，Exchange Online 为客户管理员提供了以下工具（如下所述），帮助他们管理消息传递相关的任务：
  
- [Microsoft Office 365 门户](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [Microsoft 365 管理中心](#microsoft-365-admin-center)
    
- [Exchange 管理中心](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [Exchange Online 的远程 Windows PowerShell](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a>Microsoft Office 365 门户

Microsoft Office 365 门户 ([https://portal.office.com](https://portal.office.com)) 门户是一个网站，管理员与合作伙伴可通过其购买和管理 Office 365 服务，而用户则可在其中访问和使用 Office 365 协作工具。
  
### <a name="microsoft-365-admin-center"></a>Microsoft 365 管理中心

Microsoft 365 管理中心是一个 web 门户，其中每个公司的服务管理员都可以管理他们订阅的每个 Microsoft 服务的用户帐户和设置。 在 Microsoft 365 管理中心内，管理员可以访问 Exchange 管理中心（EAC）的链接，在其中可以管理特定于 Exchange Online 的设置。 若要详细了解如何使用 Microsoft 365 管理中心启动和运行，请参阅以下视频： [Office 365 企业版简介](https://go.microsoft.com/fwlink/p/?LinkId=271806)。
  
### <a name="exchange-admin-center"></a>Exchange 管理中心

Exchange Online provides a single unified management console that allows for ease of use and is optimized for management of on-premises, online, or hybrid deployments. The Exchange admin center (EAC) is where administrators can manage Exchange-specific settings.
  
若要详细了解如何使用 EAC 管理 Exchange Online，请参阅 [Exchange 管理中心](https://go.microsoft.com/fwlink/p/?LinkId=271807)。
  
### <a name="remote-windows-powershell-for-exchange-online"></a>Exchange Online 的远程 Windows PowerShell

Using remote Windows PowerShell, administrators can connect to Exchange Online to perform management tasks that are not available or practical using the EAC. These include the ability to automate repetitive tasks, extract data for custom reports, customize policies, and connect Exchange Online to existing infrastructure and processes. For more information, see [Connect to Exchange Online Using Remote PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).
  
Exchange Online uses the same Windows PowerShell cmdlets as Exchange Server 2013, with certain commands and parameters unavailable because these features do not apply in Exchange Online. For a list of cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).
  
Administrators do not need to install any Exchange Server management or migration tools to use remote Windows PowerShell. However, administrators' computers must be running the Windows Management Framework 3.0, which contains Windows PowerShell v3 and WinRM 3.0; and Windows .NET Framework 4.5. These components are already installed on computers running Windows 8 or Windows Server 2012. Administrators can manually download these components for computers that are running Windows 7 or Windows Server 2008 R2.
  
> [!IMPORTANT]
> 为了帮助防止受到拒绝服务 (DoS) 攻击，您最多只能打开三次与 Exchange Online 组织的 Windows PowerShell 连接。 
  
## <a name="self-service-capabilities-for-exchange-online"></a>Exchange Online 的自助服务功能

Below are important capabilities that are available for managing Exchange Online by using the EAC, remote Windows PowerShell, and other tools. Many other settings can also be controlled with these tools, as described throughout this document.
  
### <a name="mobile-device-security-policies-for-exchange-online"></a>Exchange Online 的移动设备安全策略

Exchange Online supports the same ActiveSync policies for mobile devices as Exchange Server 2013. Administrators can enforce and customize these security policies for specific users and groups by using the EAC or remote Windows PowerShell.
  
### <a name="message-tracking-for-exchange-online"></a>Exchange Online 的邮件跟踪功能

通过送达报告功能进行邮件跟踪在以下主题中进行了介绍：[报告功能和疑难解答工具](reporting-features-and-troubleshooting-tools.md)。
  
### <a name="usage-reporting-for-exchange-online"></a>Exchange Online 的使用情况报告功能

Administrators can use remote Windows PowerShell to retrieve information about how people in their organizations use the Exchange Online service. Available information includes:
  
- 显示组织中每个用户的邮箱大小。
    
- 显示邮箱中设置的自定义权限（例如，委派访问权限）。
    
- 提取有关移动设备访问的数据，例如：哪些用户正在通过 Exchange ActiveSync 实现连接、用户正在使用哪些设备、他们上次何时连接。
    
Remote Windows PowerShell cmdlets that start with "get-" can fetch data from the Exchange Online system. Administrators can export this information from Windows PowerShell in .csv format for advanced analysis or reporting.
  
若要详细了解可与 Exchange Online 结合使用的 Windows PowerShell cmdlet，请参阅 [Exchange Online cmdlet](https://go.microsoft.com/fwlink/p/?LinkId=271808)。
  
### <a name="auditing-for-exchange-online"></a>Exchange Online 的审核功能

以下主题中介绍了审核日志记录功能：[报告功能和疑难解答工具](reporting-features-and-troubleshooting-tools.md)。
  
## <a name="service-and-product-upgrades-for-exchange-online"></a>Exchange Online 的服务和产品升级

Exchange Online customers benefit from periodic upgrades to the latest Exchange technology, including new releases of Exchange Server. These upgrades are made available at no additional charge, and ensure that customers are always using the latest Exchange software.
  
Microsoft 发行 Exchange 主版本后，客户最长可在 12 个月内将服务升级到新版本。
  
## <a name="feature-availability"></a>功能可用性

若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅[Exchange Online 服务说明](exchange-online-service-description.md)。
  