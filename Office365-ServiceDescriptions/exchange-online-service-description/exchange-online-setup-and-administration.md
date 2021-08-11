---
title: Exchange Online 设置和管理
ms.author: office365servicedesc
author: pamelaar
manager: gailw
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
description: 本文介绍可用于自定义组织设置Exchange Online保持组织环境运行、运行Exchange Online更新的管理控件和支持。 它包括有关组织可以使用的自助式管理工具和功能、Microsoft 管理责任和性能承诺以及服务与产品升级的信息。
ms.openlocfilehash: 24edb5a4c1855acd990ddc427e218cb601dc45aab34a5f6a83cf76cb561dbffe
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/06/2021
ms.locfileid: "54663945"
---
# <a name="exchange-online-setup-and-administration"></a>Exchange Online 设置和管理

本文介绍可用于自定义组织设置Exchange Online保持组织环境运行、运行Exchange Online更新的管理控件和支持。 它包括有关组织可以使用的自助式管理工具和功能、Microsoft 管理责任和性能承诺以及服务与产品升级的信息。
  
## <a name="self-service-administration-tools"></a>自助服务管理工具

尽管 Microsoft 直接控制所有Exchange Online，并负责整体系统性能，但它只能控制组合在一起以为用户提供总体验的部分元素。 组织本身负责到数据中心、客户广域网 (WAN) 和客户局域网 (LAN) 的网络连接。 此外，还负责用户设备及其配置。它们也负责维护每个用户的任何所需功能需要的授权，包括但不限于管理这些功能的能力，前提是用户需要访问此功能。
  
因此，Exchange Online 为客户管理员提供了以下工具（如下所述），帮助他们管理消息传递相关的任务：
  
- [Microsoft Office 365 门户](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [ Microsoft 365 管理中心](#microsoft-365-admin-center)
    
- [Exchange 管理中心](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [Exchange Online 的远程 Windows PowerShell](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a>Microsoft Office 365 门户

Microsoft Office 365 门户 ([https://portal.office.com](https://portal.office.com)) 门户是一个网站，管理员与合作伙伴可通过其购买和管理 Office 365 服务，而用户则可在其中访问和使用 Office 365 协作工具。
  
### <a name="microsoft-365-admin-center"></a>Microsoft 365 管理中心

Microsoft 365 管理中心是一个 Web 门户，每个公司的服务管理员可以从该门户管理他们订阅的每个 Microsoft 服务用户帐户和设置。 管理员可以从Microsoft 365 管理中心 EAC Exchange管理中心 (EAC) ，在此链接中可以管理特定于 Exchange Online 的设置。 有关开始使用和运行 Microsoft 365 管理中心，请参阅以下视频[：Office 365 企业版。](https://go.microsoft.com/fwlink/p/?LinkId=271806)
  
### <a name="exchange-admin-center"></a>Exchange 管理中心

Exchange Online 提供单一的统一管理控制台，该控制台易于使用，并针对内部部署、联机部署或混合部署进行了管理优化。在 Exchange 管理中心 (EAC) 内，管理员可以管理特定于 Exchange 的相关设置。
  
若要详细了解如何使用 EAC 管理 Exchange Online，请参阅 [Exchange 管理中心](/exchange/exchange-admin-center)。
  
### <a name="remote-windows-powershell-for-exchange-online"></a>Exchange Online 的远程 Windows PowerShell

使用远程 Windows PowerShell，管理员可以连接到 Exchange Online，执行使用 EAC 无法执行的管理任务。这些任务包括：自动运行重复任务、从自定义报告中提取数据、自定义策略，以及将 Exchange Online 连接到现有基础结构和流程。有关详细信息，请参阅[使用远程 PowerShell 连接到 Exchange Online](/powershell/exchange/connect-to-exchange-online-powershell)。
  
Exchange Online 使用与 Exchange Server 2013 相同的 Windows PowerShell cmdlet，但某些特定的命令和参数不可用，其原因在于这些功能在 Exchange Online 中不适用。有关可与 Exchange Online 结合使用的 cmdlet 列表，请参阅 [Exchange Online cmdlet](/powershell/exchange/exchange-online-powershell)。
  
管理员无需安装任何 Exchange Server 管理或迁移工具，即可使用远程 Windows PowerShell。但是，管理员的计算机必须运行 Windows Management Framework 3.0，它包含 Windows PowerShell v3、WinRM 3.0 和 Windows .NET Framework 4.5。这些组件已安装在运行 Windows 8 或 Windows Server 2012 的计算机上。管理员可针对运行 Windows 7 或 Windows Server 2008 R2 的计算机手动下载这些组件。
  
> [!IMPORTANT]
> 为了帮助防止受到拒绝服务 (DoS) 攻击，您最多只能打开三次与 Exchange Online 组织的 Windows PowerShell 连接。 
  
## <a name="self-service-capabilities-for-exchange-online"></a>Exchange Online 的自助服务功能

以下是通过使用 EAC、远程 Windows PowerShell 和其他工具管理 Exchange Online 时可以使用的重要功能。正如本文档所述，使用这些工具还可以控制其他许多设置。
  
### <a name="mobile-device-security-policies-for-exchange-online"></a>Exchange Online 的移动设备安全策略

Exchange Online 支持与 Exchange Server 2013 相同的 ActiveSync 移动设备策略。管理员可以通过使用 EAC 或远程 Windows PowerShell 为特定用户和组实施和自定义这些安全策略。
  
### <a name="message-tracking-for-exchange-online"></a>Exchange Online 的邮件跟踪功能

以下主题介绍了通过送达报告功能的邮件跟踪： [报告功能和疑难解答工具](reporting-features-and-troubleshooting-tools.md)。
  
### <a name="usage-reporting-for-exchange-online"></a>Exchange Online 的使用情况报告功能

管理员可以使用远程 Windows PowerShell 检索组织中的人员如何使用 Exchange Online 服务的详细信息。可用信息包括：
  
- 显示组织中每个用户的邮箱大小。
    
- 显示邮箱中设置的自定义权限（例如，委派访问权限）。
    
- 提取有关移动设备访问的数据，例如：哪些用户正在通过 Exchange ActiveSync 实现连接、用户正在使用哪些设备、他们上次何时连接。
    
以 "get-" 开头的远程 Windows PowerShell cmdlet 可从 Exchange Online 系统中提取数据。管理员可从 Windows PowerShell 中以 .csv 格式导出这些信息，以便进行高级分析或报告。
  
若要详细了解可与 Exchange Online 结合使用的 Windows PowerShell cmdlet，请参阅 [Exchange Online cmdlet](/powershell/exchange/exchange-online-powershell)。
  
### <a name="auditing-for-exchange-online"></a>Exchange Online 的审核功能

以下主题介绍了审核日志记录功能： [报告功能和疑难解答工具](reporting-features-and-troubleshooting-tools.md)。
  
## <a name="service-and-product-upgrades-for-exchange-online"></a>Exchange Online 的服务和产品升级

Exchange Online 客户可从定期升级至最新 Exchange 技术（其中包括新版本的 Exchange Server）中获益良多。这些升级无需另行收费，且可确保用户始终能够使用最新的 Exchange 软件。
  
Microsoft 发行 Exchange 主版本后，客户最长可在 12 个月内将服务升级到新版本。
  
## <a name="feature-availability"></a>功能可用性

若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅Exchange Online[说明](exchange-online-service-description.md)。
