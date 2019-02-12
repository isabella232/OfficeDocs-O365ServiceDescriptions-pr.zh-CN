---
title: Office 365 高级威胁防护服务说明
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 02/08/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 高级威胁保护 (ATP) 是基于云的电子邮件筛选服务，可帮助保护您的组织免受未知的恶意软件和病毒通过提供强大的零时差保护，并包括功能来保护您从实时有害链接的组织。ATP 具有丰富报告和 URL 跟踪功能，为管理员提供深入的组织中发生的攻击的类型。
ms.openlocfilehash: aeddc27c0275cb21ec257878e0978961356e7a85
ms.sourcegitcommit: 30a452b9b9a0d8fc288e5911235454cc8f1907be
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 02/11/2019
ms.locfileid: "29884193"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Office 365 高级威胁防护服务说明

Microsoft Office 365 高级威胁保护 (ATP) 是基于云的电子邮件筛选服务，可帮助保护您的组织免受未知的恶意软件和病毒通过提供强大的零时差保护，并包括功能来保护您从实时有害链接的组织。ATP 具有丰富报告和 URL 跟踪功能，为管理员提供深入的组织中发生的攻击的类型。
  
您可以使用 ATP 邮件保护的主要方式如下：
  
- 在 Office 365 ATP 仅筛选方案中，ATP 提供对内部部署 Exchange Server 环境或任何其他内部部署 SMTP 电子邮件解决方案的基于云的电子邮件保护。
    
- Office 365 ATP 可以启用保护云承载的 Exchange Online 邮箱。若要了解有关 Exchange Online 的详细信息，请参阅[Exchange Online Service Description](exchange-online-service-description/exchange-online-service-description.md)。
    
- 在混合部署中，可以配置 ATP 为保护您的邮件环境并控制邮件路由时具有的内部部署混合和云邮箱与 Exchange Online Protection 入站电子邮件筛选。
    
## <a name="office-365-advanced-threat-protection-atp-availability"></a>Office 365 高级威胁保护 (ATP) 可用性

ATP 包含在 Office 365 企业 E5、 Office 365 教育版 A5 和 Microsoft 365 企业版。 
  
可以将 ATP 添加到以下 Exchange 和 Office 365 订阅计划中： 
  
- Exchange Online 计划 1
    
- Exchange Online 计划 2
    
- Exchange Online Kiosk
    
- Exchange Online Protection
    
- Office 365 商业协作版
    
- Office 365 商业高级版
    
- Office 365 企业版 E1
    
- Office 365 企业版 E3
    
- Office 365 企业版 F1
    
- Office 365 A1
    
- Office 365 A3
    
若要购买 Office 365 高级威胁保护，请参阅[Office 365 高级威胁保护](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)。
  
若要跨计划比较功能，请参阅[比较 Office 365 商业版计划](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409)。
  
## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>What's new 在 Office 365 高级威胁保护 (ATP)

开始在年 2 月 2019年和推出通过下的几个月，威胁智能功能被添加到 ATP。此外，如果您的组织当前不具有 ATP，您必须考虑，新选项包括 ATP 计划 1 和 ATP 计划 2。有关详细信息，请参阅[Office 365 高级威胁保护计划和定价](https://products.office.com/en-us/exchange/advance-threat-protection#pmg-allup-content)和[跨高级威胁保护 (ATP) 计划功能可用性](#feature-availability-across-advanced-threat-protection-atp-plans)。

有关 ATP 中的新功能的信息，请参阅[ATP 中的新功能](https://docs.microsoft.com/office365/securitycompliance/office-365-atp#new-features-are-continually-being-added-to-atp)。
  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Office 365 的高级的威胁保护 (ATP) 的要求

ATP 可以与任何 SMTP 邮件传输代理（如 Microsoft Exchange Server 2013）结合使用。若要了解 ATP 支持的操作系统、Web 浏览器和语言，请参阅 [Exchange Online Protection 中的 Exchange 管理中心](https://go.microsoft.com/fwlink/p/?LinkId=282381)的"支持的浏览器"和"支持的语言"部分。
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>跨高级威胁保护 (ATP) 计划功能可用性

下面列出了每个功能。当提到 Exchange Online 时，通常指的是 Office 365 企业版服务系列。
  
|**功能**|**ATP 计划 1**<br>（以前称为 ATP 独立）|**ATP 计划 2**<br>（以前称为威胁智能 <br>独立） | Office 365 企业版 E5| 
|:-----|:-----|:-----|:-----|
| *配置、 保护和检测* | 
|安全附件 |是|支持 |可访问|
|安全链接 |是|支持 |可访问 | 
|防钓鱼策略 |是 |支持 |可访问 |
|SharePoint、 OneDrive 和 Microsoft 团队 ATP |是 |支持 |可访问|
|团队中的安全链接 |是|支持 |可访问 |
|实时报告 |是 |支持 |可访问|
|*自动化、 调查、 修复和教育* |
|威胁跟踪器 |否 |是 |可访问 |
|资源管理器 （高级威胁调查） |否 |是 |可访问 |
|自动的调查和响应  |否 |是 |可访问 |
|攻击模拟器 |否 |是 |可访问 |

   
## <a name="advanced-threat-protection-atp-capabilities"></a>高级的威胁保护 (ATP) 功能

### <a name="safe-attachments"></a>安全附件

[ATP 安全附件](https://docs.microsoft.com/office365/securitycompliance/atp-safe-attachments)可防止未知的恶意软件和病毒，并提供零时差保护，以保护邮件系统。所有邮件和附件没有已知的病毒/恶意软件签名的都路由至 ATP 其中使用的各种计算机学习和分析技术来检测恶意特殊环境。如果检测到没有可疑活动时，邮件已发布用于传递到邮箱。 

### <a name="safe-links"></a>安全链接

[ATP 安全链接](https://docs.microsoft.com/Office365/SecurityCompliance/atp-safe-links)功能主动可防止用户在邮件或 Office 文档中的恶意 Url。保护保持每次用户单击此链接，可以访问良好的链接时动态阻止恶意链接。

### <a name="anti-phishing-policies"></a>防钓鱼策略

[ATP 防钓鱼](https://docs.microsoft.com/office365/securitycompliance/atp-anti-phishing)检查可能是一条消息网络钓鱼尝试指标的传入消息。时介绍用户的传入消息计算的多个计算机学习分析消息的模型 ATP 策略 （安全附件、 安全链接或防钓鱼），并执行相应的操作，基于已配置的策略。
  
### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>适用于 SharePoint、OneDrive 和 Microsoft Teams 的 ATP

[SharePoint、 OneDrive 和 Microsoft 团队 ATP](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams)有助于检测和阻止的工作组网站和文档库中标识为恶意文件。

### <a name="real-time-reports"></a>实时报告

监控功能的 Office 365 安全性 & 合规性中心包括[实时报告和见解](https://docs.microsoft.com/office365/securitycompliance/view-reports-for-atp)使安全性和遵从性管理员重点关注高优先级的问题，例如安全攻击或增加可疑活动。除了突出显示问题的区域，智能报告和见解包括建议和链接以查看和分析数据，以及还执行快速操作。 
  
### <a name="threat-trackers"></a>威胁跟踪器

[威胁跟踪器](https://docs.microsoft.com/office365/securitycompliance/threat-trackers)是信息性小部件和授权的用户提供智能网络安全问题，可能会影响您的组织的视图。

### <a name="explorer"></a>资源管理器

[资源管理器](https://docs.microsoft.com/office365/securitycompliance/use-explorer-in-security-and-compliance)（也称为威胁资源管理器） 是允许授权用户标识和分析最近威胁的实时报告。默认情况下，此报告将显示数据的过去 7 天。但是，可以修改视图，以显示过去 30 天的数据。 

### <a name="attack-simulator"></a>攻击模拟器
  
[攻击模拟器](https://docs.microsoft.com/office365/SecurityCompliance/attack-simulator)，授权的用户可以在您的组织中运行实际攻击方案。几种不同的攻击是可用，包括的显示名称矛网络钓鱼攻击、 密码喷涂攻击中和密码强力攻击。