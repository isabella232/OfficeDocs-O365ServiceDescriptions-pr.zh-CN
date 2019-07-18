---
title: Office 365 高级威胁防护服务说明
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 高级威胁防护 (ATP) 是一项基于云的电子邮件筛选服务, 通过提供强大的零天保护功能, 帮助您的组织抵御未知恶意软件和病毒, 并提供保护实时来自有害链接的组织。 ATP 具有丰富的报告功能和 URL 跟踪功能, 可让管理员了解组织中发生的攻击种类。
ms.openlocfilehash: a54d0fddae4430b450b944781cbeca1cbb1e414f
ms.sourcegitcommit: 96dc758c790ddaf05f5c2b836451b417729cf119
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/18/2019
ms.locfileid: "35776413"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Office 365 高级威胁防护服务说明

Microsoft Office 365 高级威胁防护 (ATP) 是一项基于云的电子邮件筛选服务, 通过提供强大的零天保护功能, 帮助您的组织抵御未知恶意软件和病毒, 并提供保护实时来自有害链接的组织。 ATP 具有丰富的报告功能和 URL 跟踪功能, 可让管理员了解组织中发生的攻击种类。
  
以下是您可以使用 ATP 进行邮件保护的主要方式:
  
- 在 Office 365 ATP 仅筛选方案中, ATP 为本地 Exchange Server 环境或任何其他本地 SMTP 电子邮件解决方案提供基于云的电子邮件保护。
    
- 可以启用 Office 365 ATP 来保护 Exchange Online 云托管的邮箱。 若要了解有关 Exchange Online 的详细信息，请参阅 [Exchange Online 服务说明](exchange-online-service-description/exchange-online-service-description.md)。
    
- 在混合部署中, 如果您将本地和云邮箱与入站电子邮件筛选的 Exchange Online 保护结合在一起, 则可以将 ATP 配置为保护您的邮件环境并控制邮件路由。
    
## <a name="office-365-advanced-threat-protection-atp-availability"></a>Office 365 高级威胁防护 (ATP) 可用性

ATP 包含在 Office 365 企业版 E5、Office 365 教育版 A5 和 Microsoft 365 商业版中。 
  
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
    
若要购买 Office 365 高级威胁防护, 请参阅[office 365 高级威胁防护](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)。
  
若要跨计划比较功能, 请参阅[比较 Office 365 For Business 计划](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409)和[发现适合你的 Microsoft 365 企业解决方案](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans)。
  
## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Office 365 高级威胁防护 (ATP) 的新增功能

我们正在继续向 Office 365 ATP 添加新功能。 下面列出了几个新功能, 其中一些是用于检查和更新 ATP 策略的。 若要了解有关即将 ATP (或常规 Microsoft 365) 的新功能的详细信息, 请访问[Microsoft 365 路线图](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)。

|功能更新  |交办事项  |
|---------|---------|
|[Office 365 威胁智能](https://docs.microsoft.com/office365/securitycompliance/office-365-ti)(TI) 功能现已成为 ATP 计划2的一部分的威胁调查和响应功能。 推出了新功能, 如[自动调查和响应](https://docs.microsoft.com/office365/securitycompliance/automated-investigation-response-office), 以及[威胁 Explorer](https://docs.microsoft.com/office365/securitycompliance/use-explorer-in-security-and-compliance)的增强功能。<br/><br/>如果你的组织当前没有 ATP, 或者如果你有 ATP 而不是 TI, 则你现在有几个选项需要考虑, 并且 ATP 计划1和 ATP 计划2的可用性。 若要了解详细信息, 请参阅[跨高级威胁防护 (ATP) 计划](#feature-availability-across-advanced-threat-protection-atp-plans)(本文中) 和[Office 365 高级威胁防护计划和定价](https://products.office.com/exchange/advance-threat-protection)的功能可用性。 |查看组织的订阅, 如果需要, 请[购买或编辑加载](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/buy-or-edit-an-add-on)项。  |
|当用户使用 Outlook 或 Outlook Web 应用程序 (OWA) 时, [ATP 安全链接](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links)将呈现原始 url, 而不是重写的 url。 (我们称之为本机链接呈现。)<br>当您的组织提供本机链接呈现时, 此功能将在 Outlook 365 (即点即用)、OWA 以及 Windows 和 Mac OS 中运行。 |无         |
|[Office 365 ATP 警告页面](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links-warning-pages)功能提供了新的配色方案、更多详细信息和继续转到网站的功能, 尽管有警告和建议。 |无         |
|[ATP 安全链接](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links)保护扩展到适用于 Office 中的 url 的 Web (Word for Web、Excel for Web、PowerPoint for Web 和 OneNote for web) 和 Mac 上的 Office 365 专业增强版。   |[查看和编辑 ATP 安全链接策略](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-links-policies)  |
|安全&amp;合规中心中的隔离功能扩展到[SharePoint Online、OneDrive For Business 和 Microsoft 团队的 ATP](https://docs.microsoft.com/office365/SecurityCompliance/atp-for-spo-odb-and-teams)。 |[查看和编辑 ATP 安全附件策略](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-attachments-policies) |
|[ATP 安全链接](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links)保护扩展为适用于在组织内的人员之间发送的电子邮件。 |[查看和编辑 ATP 安全链接策略](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-links-policies) |
|[ATP 安全链接](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links)保护扩展为应用于电子邮件中的 Url 以及 Office 365 专业增强版文档中的 url, 如 Word、Excel、PowerPoint 和 Visio on Windows, 以及 IOS 和 Android 设备上的 Office 应用程序。  |确保您正在使用[Office 的新式验证](https://docs.microsoft.com/office365/enterprise/modern-auth-for-office-2013-and-2016) |

  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Office 365 高级威胁防护 (ATP) 的要求

ATP 可以与任何 SMTP 邮件传输代理 (如 Microsoft Exchange Server) 一起使用。 若要了解 ATP 支持的操作系统、Web 浏览器和语言，请参阅 [Exchange Online Protection 中的 Exchange 管理中心](https://go.microsoft.com/fwlink/p/?LinkId=282381)的"支持的浏览器"和"支持的语言"部分。
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>跨高级威胁防护 (ATP) 计划的功能可用性

下面列出了每个功能。当提到 Exchange Online 时，通常指的是 Office 365 企业版服务系列。
  
|**功能**|**ATP 计划1**<br>(以前的 ATP 独立)|**ATP 计划2**<br>(以前称为威胁智能 <br>独立主机 | Office 365 企业版 E5| 
|:-----|:-----|:-----|:-----|
| *配置、保护和检测* | 
|安全附件 |是|是 |是|
|安全链接 |是|是 |是 | 
|反网络钓鱼策略 |是 |是 |是 |
|SharePoint、OneDrive 和 Microsoft 团队的 ATP |是 |是 |是|
|团队中的安全链接 |是|是 |是 |
|实时报告 |是 |是 |是|
|*自动化、调查、修正和教育* |
|威胁跟踪器 |否 |可访问 |是 |
|资源管理器 (高级威胁调查) |否 |可访问 |是 |
|自动调查和响应  |否 |可访问 |是 |
|攻击模拟器 |否 |可访问 |是 |

   
## <a name="advanced-threat-protection-atp-capabilities"></a>高级威胁防护 (ATP) 功能

### <a name="safe-attachments"></a>安全附件

[ATP 安全附件](https://docs.microsoft.com/office365/securitycompliance/atp-safe-attachments)针对未知恶意软件和病毒提供保护, 并提供为期零天的保护, 以保护您的邮件系统。 所有不带有已知的病毒/恶意软件签名的邮件和附件都被路由到一个特殊的环境中，ATP 将在其中使用多种机器学习和分析技术来检测恶意企图。 如果没有检测到可疑的活动，会发布邮件并传递到邮箱中。 

> [!NOTE]
> ATP 安全附件扫描发生在 Office 365 数据所在的同一个区域中。 有关数据中心地理位置的详细信息, 请参阅[您的数据位于何处？](https://products.office.com/where-is-your-data-located?geo=All) 

### <a name="safe-links"></a>安全链接

[ATP 安全链接](https://docs.microsoft.com/Office365/SecurityCompliance/atp-safe-links)功能主动保护您的用户免受邮件中或 Office 文档中的恶意 url 的攻击。 每次单击链接时，将继续提供保护，因为会在访问良好的链接时动态地阻挡恶意链接。

### <a name="anti-phishing-policies"></a>反网络钓鱼策略

[ATP 反网络钓鱼](https://docs.microsoft.com/office365/securitycompliance/atp-anti-phishing)检查传入的邮件, 以指示邮件可能是网络钓鱼尝试。 当 ATP 策略 (安全附件、安全链接或反网络钓鱼) 覆盖了用户时, 将通过分析邮件的多个机器学习模型来评估传入的邮件, 并根据配置的策略采取相应的操作。
  
### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>适用于 SharePoint、OneDrive 和 Microsoft Teams 的 ATP

[SharePoint、OneDrive 和 Microsoft 团队的 ATP](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams)可帮助检测和阻止在工作组网站和文档库中被标识为恶意的文件。

### <a name="real-time-reports"></a>实时报告

Office 365 安全 & 合规中心中提供的监视功能包括[实时报告和见解](https://docs.microsoft.com/office365/securitycompliance/view-reports-for-atp), 使您的安全和合规性管理员能够重点关注高优先级问题, 如安全攻击或提高可疑活动。 除了突出显示问题区域之外, 智能报告和见解还包括用于查看和浏览数据的建议和链接, 同时还采取快速操作。 
  
### <a name="threat-trackers"></a>威胁跟踪器

[威胁跟踪](https://docs.microsoft.com/office365/securitycompliance/threat-trackers)程序是信息小组件和视图, 为授权用户提供了可能会影响您的组织的 cybersecurity 问题的智能。

### <a name="explorer"></a>Explorer

[浏览器](https://docs.microsoft.com/office365/securitycompliance/use-explorer-in-security-and-compliance)(也称为 "威胁资源管理器") 是一种实时报告, 它使授权用户能够识别和分析最新的威胁。 默认情况下, 此报告显示过去7天的数据;但是, 可以对视图进行修改, 以显示过去30天的数据。 

### <a name="attack-simulator"></a>攻击模拟器
  
利用[攻击模拟器](https://docs.microsoft.com/office365/SecurityCompliance/attack-simulator), 授权用户可以在您的组织中运行实际的攻击方案。 有几种不同类型的攻击可供使用, 其中包括显示名称 spear 网络钓鱼攻击、密码喷涂攻击和强力密码攻击。