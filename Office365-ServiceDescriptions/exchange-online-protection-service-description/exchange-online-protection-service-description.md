---
title: Exchange Online Protection 服务说明
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: 获取有关 Exchange Online Protection 的功能和要求的信息。其中包括提供 Exchange Online Protection 的计划列表以及所有计划的功能比较。
ms.openlocfilehash: 22116d6771ccafe421cf1a3fc1abc87ab4af1d43
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/22/2019
ms.locfileid: "34342081"
---
# <a name="exchange-online-protection-service-description"></a>Exchange Online Protection 服务说明

获取有关 Exchange Online Protection 的功能和要求的信息。其中包括提供 Exchange Online Protection 的计划列表以及所有计划的功能比较。
  
Microsoft Exchange Online Protection (EOP) 是基于云的电子邮件筛选服务，可帮助您的组织防御垃圾邮件和恶意邮件，并包括用于保护您的组织避免违反邮件策略的功能。EOP 可以简化对邮件环境的管理，缓解由于维护内部部署硬件和软件而产生的许多负担。
  
以下是您可以使用 EOP 进行邮件保护的主要方式：
  
- **在独立方案中**EOP 为您的内部部署 Exchange Server 2013 环境、旧版 Exchange Server 版本或任何其他本地 SMTP 电子邮件解决方案提供基于云的电子邮件保护。 
    
- **作为 Microsoft Exchange Online 的一部分** 默认情况下，EOP 保护 Exchange Online 云托管的邮箱。若要了解有关 Exchange Online 的详细信息，请参阅 [Exchange Online 服务说明](../exchange-online-service-description/exchange-online-service-description.md)。
    
- **在混合部署中** 如果您既有本地邮箱，也有云邮箱，则可以将 EOP 配置为保护您的邮件环境并控制邮件路由。 
    
若要跨计划比较功能，请参阅[比较 Office 365 商业版计划](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409)。
  
若要购买 Exchange Online Protection，请参阅 [Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=294201)。
  
您可以导出、保存以及打印 Office 365 服务说明中的页面。了解如何[导出多个页面](https://go.microsoft.com/fwlink/?LinkId=403349)。
  
> [!IMPORTANT]
> EOP 替换 Forefront Online Protection for Exchange (FOPE)。所有 FOPE 客户将转换到 EOP。EOP 提供 FOPE 所提供的保护和控制，并且包括额外功能。有关从 FOPE 转换到 EOP 的详细信息，请参阅 [Forefront Online Protection for Exchange (FOPE) 转换中心](http://www.movetoeop.com)。 
  
## <a name="whats-new-in-exchange-online-protection-eop"></a>Exchange Online Protection (EOP) 的新增功能

若要了解 EOP 新增功能，请参阅 [What's New in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=320390)（Exchange Online Protection 中的新增功能）。有关 FOPE 与 EOP 功能比较，请参阅 [FOPE vs. EOP Feature Comparison](https://go.microsoft.com/fwlink/p/?LinkId=320391)（FOPE 与 EOP 功能比较）。
  
## <a name="exchange-online-protection-eop-plans"></a>Exchange Online Protection (EOP) 计划

可以通过以下订阅计划使用 EOP：
  
|**计划**|**说明**|
|:-----|:-----|
|[EOP standalone](https://go.microsoft.com/fwlink/p/?LinkId=294201)（EOP 独立） <br/> |其中 EOP 保护本地邮箱。  <br/> |
|[EOP features in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=294197)（Exchange Online 中的 EOP 功能） <br/> |其中 EOP 保护 Exchange Online 云托管的邮箱。  <br/> |
|[Exchange Enterprise CAL with Services](https://go.microsoft.com/fwlink/p/?LinkId=293699) <br/> |其中 EOP 保护您的本地邮箱（如同独立 EOP 一样），并包含数据丢失防护 (DLP) 和使用 Web 服务的报告。  <br/> |
   
### <a name="exchange-enterprise-cal-with-services-features"></a>Exchange Enterprise CAL with Services 功能

Microsoft Exchange Enterprise CAL with Services 为您的本地邮件环境提供 EOP 电子邮件保护功能，除此之外还提供以下功能：
  
- [Data loss prevention (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)
    
- [Reporting using web services](reporting-and-message-trace.md#reporting-using-web-services)
    
有关 Exchange Enterprise CAL with Services 许可的详细信息，请参阅 [Exchange Server 2013 licensing](https://go.microsoft.com/fwlink/p/?LinkId=293699)（Exchange Server 2013 许可）。
  
如果你拥有 Exchange Enterprise CAL with Services 许可证，并且想要预配服务，请按[设置 EOP 服务](https://go.microsoft.com/fwlink/p/?LinkId=320397)中的说明操作。设置步骤与设置 EOP 独立的步骤相同。
  
> [!NOTE]
> Exchange Enterprise CAL with Services 的新功能同时部署为 Exchange Online，而不是独立 EOP。请注意，独立 EOP 与 Exchange Online/Exchange Enterprise CAL with Services 的部署计划可能略有不同。 
  
## <a name="requirements-for-exchange-online-protection-eop"></a>Exchange Online Protection (EOP) 的要求

EOP 可与任意 SMTP 邮件传输代理（如 Microsoft Exchange Server 2013）结合使用。若要了解 EOP 支持的操作系统、Web 浏览器和语言，请参阅 [Exchange Online Protection [EOP] 中的 Exchange 管理中心](https://go.microsoft.com/fwlink/p/?LinkId=282381)中的"支持的浏览器"和"支持的语言"部分。
  
## <a name="limits"></a>限制

有关 EOP 中的限制，请参阅 [Exchange Online Protection 限制](exchange-online-protection-limits.md)。
  
## <a name="feature-availability-across-exchange-online-protection-eop-plans"></a>跨 Exchange Online Protection (EOP) 计划的功能可用性

下面列出了每个功能。有关 EOP 功能的更多详细信息，请单击下表中的链接。提到 Exchange Online 时，通常指的是 Office 365 企业版 服务系列。
  
|||||
|:-----|:-----|:-----|:-----|
|**功能** <br/> |**独立 EOP** <br/> |**Exchange Online 中的 EOP 功能** <br/> |**Exchange 企业版 CAL 带服务** <br/> |
|[邮件收件人](recipient-domain-and-company-management.md#mail-recipients) <br/> |是<sup>1</sup> <br/> |是<sup>1</sup> <br/> |是  <br/> |
|[管理员角色组权限](recipient-domain-and-company-management.md#admin-role-group-permissions) <br/> |是<sup>2</sup> <br/> |是  <br/> |是  <br/> |
|[域管理](recipient-domain-and-company-management.md#domain-management) <br/> |是<sup>3</sup> <br/> |是<sup>3</sup> <br/> |是<sup>3</sup> <br/> |
|[匹配子域](recipient-domain-and-company-management.md#match-subdomains) <br/> |是  <br/> |是  <br/> |否  <br/> |
|[基于目录的边缘阻止 (DBEB)](recipient-domain-and-company-management.md#directory-based-edge-blocking-dbeb) <br/> |是  <br/> |是  <br/> |是  <br/> |
|[传输规则](messaging-policy-and-compliance-servicedesc.md#transport-rules) <br/> |是<sup>3、4、14</sup> <br/> |是<sup>3、4、14</sup> <br/> |是  <br/> |
|[审核日志记录](messaging-policy-and-compliance-servicedesc.md#audit-logging) <br/> |是<sup>5</sup> <br/> |是  <br/> |是  <br/> |
|[数据丢失防护 (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp) <br/> |否  <br/> |可访问  <br/> |是<sup>6</sup> <br/> |
|[Office 365 邮件加密](messaging-policy-and-compliance-servicedesc.md#office-365-message-encryption) <br/> |是<sup>12</sup> <br/> |是  <br/> |是<sup>12</sup> <br/> |
|[反垃圾邮件保护](anti-spam-and-anti-malware-protection-eop.md#anti-spam-protection)（内置）  <br/> |是  <br/> |是  <br/> |是  <br/> |
|[自定义反垃圾邮件策略](anti-spam-and-anti-malware-protection-eop.md#customize-anti-spam-policies) <br/> |是<sup>7</sup> <br/> |是  <br/> |是  <br/> |
|[反恶意软件保护](anti-spam-and-anti-malware-protection-eop.md#anti-malware-protection)（内置）  <br/> |是<sup>13</sup> <br/> |是  <br/> |是  <br/> |
|[自定义反恶意软件策略](anti-spam-and-anti-malware-protection-eop.md#customize-anti-malware-policies) <br/> |是  <br/> |是  <br/> |是  <br/> |
|[隔离](anti-spam-and-anti-malware-protection-eop.md#quarantine)：管理员管理  <br/> |是  <br/> |是  <br/> |是  <br/> |
|[隔离](anti-spam-and-anti-malware-protection-eop.md#quarantine)：最终用户自我管理  <br/> |是  <br/> |是  <br/> |是  <br/> |
|[Microsoft Office Outlook 的垃圾邮件报告加载项](anti-spam-and-anti-malware-protection-eop.md#junk-email-reporting-add-in-for-microsoft-office-outlook) <br/> |是  <br/> |是  <br/> |是  <br/> |
|[Outlook Web App 中的垃圾电子邮件报告](anti-spam-and-anti-malware-protection-eop.md#junk-email-reporting-in-outlook-web-app) <br/> |是<sup>8</sup> <br/> |无<sup>8</sup> <br/> |无<sup>8</sup> <br/> |
|[在 Office 365 和自己的电子邮件服务器之间路由电子邮件](mail-flow-eop.md#routing-email-between-office-365-and-your-own-email-servers) <br/> |是  <br/> |是  <br/> |是  <br/> |
|[与受信任合作伙伴的安全邮件](mail-flow-eop.md#secure-messaging-with-a-trusted-partner) <br/> |是  <br/> |是  <br/> |是  <br/> |
|[合作伙伴 IP 地址安全列表](mail-flow-eop.md#safe-listing-a-partners-ip-address) <br/> |是  <br/> |是  <br/> |是  <br/> |
|[有条件的邮件路由](mail-flow-eop.md#conditional-mail-routing) <br/> |是  <br/> |是  <br/> |是  <br/> |
|[混合邮件路由](mail-flow-eop.md#hybrid-mail-routing) <br/> |是  <br/> |是  <br/> |是  <br/> |
|[Microsoft 365 管理中心报告](reporting-and-message-trace.md#microsoft-365-admin-center-reports)<br/> |是<sup>9</sup> <br/> |是<sup>10</sup> <br/> |是<sup>9、10</sup> <br/> |
|[Excel 下载应用程序报告](reporting-and-message-trace.md#excel-download-application-reports) <br/> |是  <br/> |是  <br/> |是<sup>11</sup> <br/> |
|[使用 Web 服务的报告](reporting-and-message-trace.md#reporting-using-web-services) <br/> |否  <br/> |可访问  <br/> |是  <br/> |
|[邮件跟踪](reporting-and-message-trace.md#message-trace) <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是  <br/> |
|[访问 Microsoft 365 管理中心](administration-and-management-eop.md#access-to-the-microsoft-365-admin-center) <br/> |是  <br/> |是  <br/> |是  <br/> |
|[对 Exchange 管理中心的访问权限](administration-and-management-eop.md#access-to-the-exchange-admin-center) (EAC)  <br/> |是  <br/> |是  <br/> |是  <br/> |
|[远程 Windows PowerShell 访问](administration-and-management-eop.md#remote-windows-powershell-access) <br/> |是<sup>2</sup> <br/> |是  <br/> |是  <br/> |
   
> [!NOTE]
> <sup>1</sup> 邮件用户被定义为"邮箱"，并且可以在 Exchange 管理中心 (EAC) 中与外部邮件联系人一起进行添加、删除或直接管理。 
 <br/><sup>2</sup> 没有 RBAC 自定义项。 只有管理员角色。 
 <br/> <sup>3</sup> 可以在 EAC 中查看托管域和编辑域类型。 所有其他域管理都必须在 Microsoft 365 管理中心完成。 
 <br/><sup>4</sup> EOP 和 Exchange Online 的可用灵活条件和操作不同。 若要获取 EOP 中可用条件和操作的列表，请参阅 [传输规则条件](https://go.microsoft.com/fwlink/p/?LinkId=320392)和[传输规则操作](https://go.microsoft.com/fwlink/p/?LinkId=320393)。 若要获取 Exchange Online 中可用条件和操作的列表，请参阅[传输规则条件](https://go.microsoft.com/fwlink/p/?LinkId=320394)和[传输规则操作](https://go.microsoft.com/fwlink/p/?LinkId=320395)。 
 <br/><sup>5</sup> EOP 审核报告是部分不包括邮箱信息的 Exchange Online 审核报告。 
 <br/> <sup>6</sup> DLP 策略提示不适用于 Exchange Enterprise CAL with Services 客户。  <br/><sup>7</sup> 默认内容筛选器操作旨在将垃圾邮件移到收件人的"垃圾邮件"文件夹中。 若要将此筛选器与本地邮箱结合使用，还必须在本地服务器上配置两个 Exchange 传输规则，用于检测 EOP 添加的垃圾邮件头。 有关详细信息，请参阅 [确保垃圾邮件已路由到每个用户的"垃圾邮件"文件夹](https://go.microsoft.com/fwlink/p/?LinkId=320396)。 
 <br/><sup>8</sup> 此功能适用于将通过 EOP 筛选其邮箱的 Exchange Server 2013 Service Pack 1 (SP1) 客户，并且很快将提供给 Exchange Online 客户。 
 <br/><sup>9</sup> EOP 审核报告是部分不包括邮箱信息的 Exchange Online 审核报告。
 <br/><sup>10</sup> 包括 DLP 报告。 
 <br/><sup>11</sup> Exchange Enterprise CAL with Services 客户应该通过选择 **Exchange Online** 服务（而不是 **Exchange Online Protection** 服务）来安装工作簿。 
 <br/><sup>12</sup>支持购买 Azure 信息保护的本地客户, 并使用 Exchange online Protection 通过 exchange online 路由电子邮件。 
 <br/> <sup>13</sup> 扫描入站和出站邮件，但不扫描从组织中的发件人发送给组织中的收件人的内部邮件。 
 <br/><sup>14</sup> EOP 和 Exchange Online 的可用谓词和操作不同。 
 <br/> <sup>15</sup> 混合安装程序不能通过混合向导使用，但是，如果你拥有 Exchange SP1，则可以手动进行设置。 