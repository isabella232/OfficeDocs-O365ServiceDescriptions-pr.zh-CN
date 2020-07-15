---
title: Exchange Online Protection 服务说明
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: 获取有关 Exchange Online Protection 的功能和要求的信息。 其中包括提供 Exchange Online Protection 的计划的列表，以及这些计划之间的功能比较。
ms.openlocfilehash: 74a2d3a1af3e369e51e1f9b3b4e1cf5cc981c0d8
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132836"
---
# <a name="exchange-online-protection-service-description"></a>Exchange Online Protection 服务说明

获取有关 Exchange Online Protection 的功能和要求的信息。 其中包括提供 Exchange Online Protection 的计划的列表，以及这些计划之间的功能比较。

Microsoft Exchange Online Protection (EOP) is a cloud-based email filtering service that helps protect your organization against spam and malware, and includes features to safeguard your organization from messaging-policy violations. EOP can simplify the management of your messaging environment and alleviate many of the burdens that come with maintaining on-premises hardware and software.

下面的列表介绍了使用 EOP 进行邮件保护的主要方式：

- **在独立方案中**： EOP 为您的本地电子邮件环境（Exchange Server 或其他内部部署 SMTP 电子邮件解决方案）提供基于云的电子邮件保护。

- **作为 Microsoft Exchange online 的一部分**：默认情况下，EOP 保护 Exchange Online 云托管的邮箱。 若要了解有关 Exchange Online 的详细信息，请参阅[Exchange online 服务说明](../exchange-online-service-description/exchange-online-service-description.md)。

- **在混合部署中**：当您有本地和云邮箱的混合时，可以将 EOP 配置为保护您的邮件环境并控制邮件路由。

若要跨计划比较功能，请参阅[强大的工具来支持您的企业](https://products.office.com/business/compare-more-office-365-for-business-plans)。

若要购买 Exchange Online Protection，请参阅 [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection)。

> [!NOTE]
> EOP 取代了适用于 Exchange 的 Forefront Online Protection （FOPE）。 所有 FOPE 客户都已转换到 EOP。

## <a name="whats-new-in-exchange-online-protection-eop"></a>Exchange Online Protection (EOP) 的新增功能

[Microsoft 365 路线图](https://office.microsoft.com/products/office-365-roadmap-FX104343353.aspx)是找出有关即将推出的新功能的信息的一个很有用的资源。

## <a name="exchange-online-protection-eop-plans"></a>Exchange Online Protection (EOP) 计划

可以通过以下订阅计划使用 EOP：

|**计划**|**说明**|
|:-----|:-----|
|[EOP standalone](https://products.office.com/exchange/exchange-email-security-spam-protection)（EOP 独立）|一种单独的基于云的服务，可保护您的内部部署电子邮件组织。|
|[Exchange Online 中的 EOP 功能](https://products.office.com/exchange/compare-microsoft-exchange-online-plans)|Exchange Online 云托管邮箱的内置保护。|
|[Exchange 企业版 CAL 带服务](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)|为内部部署 Exchange 组织购买的加载项许可证，包括 EOP 和其他基于云的功能（有关详细信息，请参阅下一节）。|

### <a name="exchange-enterprise-cal-with-services-features"></a>Exchange Enterprise CAL with Services 功能

Microsoft Exchange Enterprise CAL with Services 提供 EOP 的电子邮件保护功能以及以下其他基于云的功能：

- [数据丢失防护 (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)

- [使用 Web 服务的报告](reporting-and-message-trace.md#reporting-using-web-services)

有关 Exchange Enterprise CAL with Services 许可的详细信息，请参阅[exchange 许可 faq](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)。

如果您具有具有服务许可证的 Exchange Enterprise CAL，并且您想要设置 EOP，请按照[设置 EOP 服务](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-your-eop-service)中的说明操作。 设置步骤与设置 EOP 独立的步骤相同。

> [!NOTE]
> New features for Exchange Enterprise CAL with Services are deployed at the same time as Exchange Online, not EOP standalone. Be advised that the deployment schedules for EOP standalone and Exchange Online/Exchange Enterprise CAL with Services may be slightly different.

## <a name="requirements-for-exchange-online-protection-eop"></a>Exchange Online Protection (EOP) 的要求

EOP 可与任何 SMTP 邮件传输代理（如 Microsoft Exchange Server）一起使用。 有关 EOP 支持的操作系统、web 浏览器和语言的信息，请参阅 exchange [Online Protection 中 exchange 管理中心](https://docs.microsoft.com/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop)的 "支持的浏览器" 和 "支持的语言" 部分。

## <a name="limits"></a>限制

有关 EOP 中的限制，请参阅[Exchange Online Protection 限制](exchange-online-protection-limits.md)。

## <a name="feature-availability-across-exchange-online-protection-eop-plans"></a>跨 Exchange Online Protection (EOP) 计划的功能可用性

Each feature is listed below. For more detailed information about EOP features, click the links in the table. When Exchange Online is mentioned, it typically refers to the Office 365 Enterprise service family.

|||||
|:-----|:-----|:-----|:-----|
|**功能**|**独立 EOP**|**Exchange Online 中的 EOP 功能 <br/>**|**Exchange Enterprise <br/> CAL With Services**|
|[Mail recipients](recipient-domain-and-company-management.md#mail-recipients)|是<sup>1</sup>|是<sup>1</sup>|是|
|[Admin role group permissions](recipient-domain-and-company-management.md#admin-role-group-permissions)|是<sup>2</sup>|是|是|
|[Domain management](recipient-domain-and-company-management.md#domain-management)|是<sup>3</sup>|是<sup>3</sup>|是<sup>3</sup>|
|[Match subdomains](recipient-domain-and-company-management.md#match-subdomains)|是|可访问|否|
|[基于目录的边缘阻止 (DBEB)](recipient-domain-and-company-management.md#directory-based-edge-blocking-dbeb)|是|是|是|
|[邮件流规则](../exchange-online-service-description/message-policy-and-compliance.md#mail-flow-rules)|是<sup>4</sup>|是<sup>4、6</sup>|是|
|[Audit logging](messaging-policy-and-compliance-servicedesc.md#audit-logging)|是<sup>5</sup>|是|是|
|[Data loss prevention (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)|否|可访问|是<sup>6</sup>|
|[Office 365 邮件加密](messaging-policy-and-compliance-servicedesc.md#office-365-message-encryption)|是<sup>12</sup>|是|是<sup>12</sup>|
|[Anti-spam protection](anti-spam-and-anti-malware-protection-eop.md#anti-spam-protection)（内置）|是|是|是|
|[Customize anti-spam policies](anti-spam-and-anti-malware-protection-eop.md#customize-anti-spam-policies)|是<sup>7</sup>|是|是|
|[Anti-malware protection](anti-spam-and-anti-malware-protection-eop.md#anti-malware-protection)（内置）|是<sup>13</sup>|是|是|
|[Customize anti-malware policies](anti-spam-and-anti-malware-protection-eop.md#customize-anti-malware-policies)|是|是|是|
|[Quarantine](anti-spam-and-anti-malware-protection-eop.md#quarantine)：管理员管理|是|是|是|
|[Quarantine](anti-spam-and-anti-malware-protection-eop.md#quarantine)：最终用户自我管理|是|是|是|
|[提交](anti-spam-and-anti-malware-protection-eop.md#report-messages-to-microsoft-for-analysis)|否|必需|否|
|[Outlook 的报告消息加载项](https://docs.microsoft.com/microsoft-365/security/office-365-security/enable-the-report-message-add-in)|是|是|是|
|[Outlook 网页版中的垃圾邮件报告](https://docs.microsoft.com/microsoft-365/security/office-365-security/report-junk-email-and-phishing-scams-in-outlook-on-the-web-eop)|是|是|是|
|[在 Microsoft 和您自己的电子邮件服务器之间路由电子邮件](mail-flow-eop.md#routing-email-between-microsoft-and-your-own-email-servers)|是|是|是|
|[Secure messaging with a trusted partner](mail-flow-eop.md#secure-messaging-with-a-trusted-partner)|是|是|是|
|[合作伙伴 IP 地址安全列表](mail-flow-eop.md#safe-listing-a-partners-ip-address)|是|是|是|
|[条件邮件路由](mail-flow-eop.md#conditional-mail-routing)|是|是|是|
|[Hybrid mail routing](mail-flow-eop.md#hybrid-mail-routing)|是|是|是|
|[Microsoft 365 管理中心报告](reporting-and-message-trace.md#microsoft-365-admin-center-reports)<br/> |是<sup>9</sup>|是<sup>10</sup>|是<sup>9、10</sup>|
|[Reporting using web services](reporting-and-message-trace.md#reporting-using-web-services)|否|可访问|是|
|[Message trace](reporting-and-message-trace.md#message-trace)|是<sup>15</sup>|是<sup>15</sup>|是|
|[访问 Microsoft 365 管理中心](administration-and-management-eop.md#access-to-the-microsoft-365-admin-center)|是|是|是|
|[对 Exchange 管理中心的访问权限](administration-and-management-eop.md#access-to-the-exchange-admin-center (EAC))|是|是|是|
|[Remote Windows PowerShell access](administration-and-management-eop.md#remote-windows-powershell-access)|是|是|是|

<sup>1</sup> 邮件用户被定义为"邮箱"，并且可以在 Exchange 管理中心 (EAC) 中与外部邮件联系人一起进行添加、删除或直接管理。 <br/>
<sup>2</sup>有 RBAC 自定义项。 只有管理员角色。 <br/>
<sup>3</sup>可在 EAC 中查看托管域和编辑域类型。 其他所有的域管理操作必须在 Microsoft 365 管理中心进行。<br/>
<sup>4</sup>有关 EOP 中的邮件流（也称为传输规则），请参阅 [Exchange Online 保护中的邮件流规则（传输规则）](https://docs.microsoft.com/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0)。 EOP 与 Exchange Online 之间的可用邮件流规则条件、例外和操作有所不同。 有关这些区别，请参阅 [Exchange Online 中的邮件流规则条件和异常（谓词）](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions)和 [Exchange Online 中的邮件流规则](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions)。<br/>
<sup>5</sup>EOP 审核报告是不包括邮箱信息的 Exchange Online 审核报告的子集。 <br/>
<sup>6</sup> DLP 策略提示不适用于 Exchange Enterprise CAL with Services 客户。  <br/>
<sup>7</sup> 默认内容筛选器操作旨在将垃圾邮件移到收件人的"垃圾邮件"文件夹中。 要将此筛选器与本地 Exchange 邮箱结合使用，还需要在本地 Exchange 组织上配置两条传输规则，用于检测 EOP 添加的垃圾邮件头。 有关详细信息，请参阅[Configure 独立 EOP 以将垃圾邮件传递到混合环境中的 "垃圾邮件" 文件夹](https://docs.microsoft.com/microsoft-365/security/office-365-security/ensure-that-spam-is-routed-to-each-user-s-junk-email-folder)。 <br/>
<sup>9</sup> EOP 审核报告是部分不包括邮箱信息的 Exchange Online 审核报告。<br/>
<sup>10</sup> 包括 DLP 报告。 <br/>
<sup>12</sup>支持购买 Azure 信息保护的本地客户，并使用 Exchange online Protection 通过 exchange online 路由电子邮件。 <br/>
<sup>13</sup> 扫描入站和出站邮件，但不扫描从组织中的发件人发送给组织中的收件人的内部邮件。 <br/>
<sup>15</sup> 混合安装程序不能通过混合向导使用，但是，如果你拥有 Exchange SP1，则可以手动进行设置。
