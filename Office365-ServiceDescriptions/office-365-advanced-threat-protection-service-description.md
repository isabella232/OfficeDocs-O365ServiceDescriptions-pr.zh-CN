---
title: Office 365 高级威胁防护服务说明
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 01/02/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 高级威胁保护 (ATP) 是基于云的电子邮件筛选服务，可帮助保护您的组织免受未知的恶意软件和病毒通过提供强大的零时差保护，并包括功能来保护您从实时有害链接的组织。ATP 具有丰富报告和 URL 跟踪功能，为管理员提供深入的组织中发生的攻击的类型。
ms.openlocfilehash: f8a44cdebebafe575f5c22a3a491671f57b05d49
ms.sourcegitcommit: d1d7309e864398e7d029956231cbaee054a2a0cf
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 01/09/2019
ms.locfileid: "27784864"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Office 365 高级威胁防护服务说明

Microsoft Office 365 高级威胁保护 (ATP) 是基于云的电子邮件筛选服务，可帮助保护您的组织免受未知的恶意软件和病毒通过提供强大的零时差保护，并包括功能来保护您从实时有害链接的组织。ATP 具有丰富报告和 URL 跟踪功能，为管理员提供深入的组织中发生的攻击的类型。
  
您可以使用 ATP 邮件保护的主要方式如下：
  
- 在 Office 365 ATP 仅筛选方案中，ATP 提供的基于云的电子邮件保护您的内部部署 Exchange Server 2013 环境、 旧版 Exchange Server 或其他任何本地 SMTP 电子邮件解决方案。
    
- Office 365 ATP 可以启用保护云承载的 Exchange Online 邮箱。若要了解有关 Exchange Online 的详细信息，请参阅[Exchange Online Service Description](exchange-online-service-description/exchange-online-service-description.md)。
    
- 在混合部署中，可以配置 ATP 为保护您的邮件环境并控制邮件路由时具有的内部部署混合和云邮箱与 Exchange Online Protection 入站电子邮件筛选。
    
## <a name="office-365-advanced-threat-protection-atp-availability"></a>Office 365 高级威胁保护 (ATP) 可用性

ATP 包含在 Office 365 企业 E5、 Office 365 教育版 A5 和 Microsoft 365 企业版。 
  
> [!NOTE]
> Microsoft 365 企业版中的客户端依赖于 ATP 功能将可用夏季完成 2018年。 
  
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
    
若要购买 Office 365 高级威胁保护，请参阅[Office 365 高级威胁保护](https://go.microsoft.com/fwlink/p/?LinkId=294201)。
  
若要跨计划比较功能，请参阅[比较 Office 365 商业版计划](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409)。
  
## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>What's new 在 Office 365 高级威胁保护 (ATP)

有关 ATP 中的新功能的信息，请参阅[ATP 中的新功能](https://docs.microsoft.com/office365/securitycompliance/office-365-atp#new-features-are-continually-being-added-to-atp)。
  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Office 365 的高级的威胁保护 (ATP) 的要求

ATP 可以与任何 SMTP 邮件传输代理（如 Microsoft Exchange Server 2013）结合使用。若要了解 ATP 支持的操作系统、Web 浏览器和语言，请参阅 [Exchange Online Protection 中的 Exchange 管理中心](https://go.microsoft.com/fwlink/p/?LinkId=282381)的"支持的浏览器"和"支持的语言"部分。
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>跨高级威胁保护 (ATP) 计划功能可用性

下面列出了每个功能。当提到 Exchange Online 时，通常指的是 Office 365 企业版服务系列。
  
|**功能**|**独立 ATP**|**Exchange Online Protection**|
|:-----|:-----|:-----|
|安全链接  <br/> |是  <br/> |否  <br/> |
|安全附件  <br/> |是  <br/> |否  <br/> |
|欺骗智能  <br/> |是  <br/> |否  <br/> |
|隔离  <br/> |是  <br/> |是  <br/> |
|高级的防钓鱼功能  <br/> |是  <br/> |否  <br/> |
   
## <a name="advanced-threat-protection-atp-capabilities"></a>高级的威胁保护 (ATP) 功能

### <a name="safe-links"></a>安全链接

ATP 安全链接功能主动保护您的用户从邮件中的恶意超链接。保护保持每次用户单击此链接，可以访问良好的链接时动态阻止恶意链接。
  
### <a name="safe-attachments"></a>安全附件

安全附件可防御未知恶意软件和病毒的攻击，并提供了零日保护，以保护您的邮件系统。所有不带有已知的病毒/恶意软件签名的邮件和附件都被路由到一个特殊的环境中，ATP 将在其中使用多种机器学习和分析技术来检测恶意企图。如果没有检测到可疑的活动，会发布邮件并传递到邮箱中。 
  
### <a name="spoof-intelligence"></a>欺骗智能

欺骗智能检测何时发件人出现在一个组织的域发送邮件代表一个或多个用户帐户。使您可以查看所有发件人在伪造您的域，然后选择要允许发件人继续，或阻止发件人。欺骗智能安全中位于&amp;反垃圾邮件设置页上的合规性中心。
  
### <a name="quarantine"></a>隔离

邮件由 Office 365 服务标识为垃圾邮件，批量邮件、 网络钓鱼邮件，包含恶意软件，或因为它们匹配的邮件流规则可以发送到隔离。默认情况下，Office 365 发送网络钓鱼邮件和邮件包含恶意软件直接到隔离。授权的用户可以查看、 删除或管理电子邮件发送到隔离。
  
### <a name="advanced-anti-phishing-capabilities"></a>高级的防钓鱼功能

此功能使用计算机学习模型来检测网络钓鱼邮件。 
  
