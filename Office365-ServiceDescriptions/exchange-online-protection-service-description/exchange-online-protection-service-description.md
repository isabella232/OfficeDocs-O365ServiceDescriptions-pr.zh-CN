---
title: Exchange Online Protection 服务说明
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: 获取有关 Exchange Online Protection 的功能和要求的信息。 包含的计划列表可提供Exchange Online Protection，以及跨这些计划的功能比较。
ms.openlocfilehash: fbfbe39931e6037b358bb76c124937904a408783
ms.sourcegitcommit: 427dbb27426a12e8c5dba7d8b4cbaf2bedb3aaba
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/30/2021
ms.locfileid: "53222479"
---
# <a name="exchange-online-protection-service-description"></a>Exchange Online Protection 服务说明

获取有关 Exchange Online Protection 的功能和要求的信息。 包含的计划列表可提供Exchange Online Protection，以及跨这些计划的功能比较。

Microsoft Exchange Online保护 (EOP) 是一种基于云的电子邮件筛选服务，可帮助保护组织免受垃圾邮件和恶意软件的攻击，并包括用于保护您的组织避免违反邮件策略的功能。 EOP 可以简化对邮件环境的管理，缓解由于维护内部部署硬件和软件而产生的许多负担。

以下列表介绍了可以使用 EOP 进行邮件保护的主要方法：

- **在独立方案中**：EOP 为本地电子邮件环境或其他本地 SMTP 电子邮件解决方案 (Exchange Server基于云的电子邮件) 。

- **作为托管邮箱Microsoft Exchange Online：** 默认情况下，EOP Exchange Online云托管的邮箱。 若要了解有关服务Exchange Online，请参阅Exchange Online[服务说明](../exchange-online-service-description/exchange-online-service-description.md)。

- **在混合部署** 中：当您混合使用本地邮箱和云邮箱时，EOP 可以配置为保护您的邮件环境和控制邮件路由。

## <a name="available-plans"></a>可用计划

下表显示了包含Exchange Online Protection，以便您可以选择最符合组织需求的解决方案。 有关详细的计划信息[，请参阅](https://products.office.com/exchange/exchange-email-security-spam-protection)Exchange Online Protection。

有关允许用户进行订阅的详细信息，Exchange Online Protection完整[订阅比较表](https://www.microsoft.com/microsoft-365/compare-microsoft-365-enterprise-plans)。

### <a name="exchange-enterprise-cal-with-services-features"></a>Exchange Enterprise CAL with Services 功能

Microsoft Exchange Enterprise CAL with Services 提供 EOP 的电子邮件保护功能以及以下基于云的其他功能：

- [数据丢失防护](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)

- [Reporting using web services](reporting-and-message-trace.md#reporting-using-web-services)

有关 CAL with Services Exchange Enterprise，请参阅Exchange[常见问题解答](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)。

如果你拥有EXCHANGE ENTERPRISE CAL with Services 许可证，并且想要预配 EOP，请按照设置 EOP 服务[中的说明操作](/microsoft-365/security/office-365-security/set-up-your-eop-service)。 设置步骤与设置 EOP 独立的步骤相同。

> [!NOTE]
> Exchange Enterprise CAL with Services 的新功能同时部署为 Exchange Online，而不是独立 EOP。请注意，独立 EOP 与 Exchange Online/Exchange Enterprise CAL with Services 的部署计划可能略有不同。

## <a name="requirements-for-exchange-online-protection-eop"></a>Exchange Online Protection (EOP) 的要求

EOP 可以与任意 SMTP 邮件传输代理（如 Microsoft Exchange Server） 一Microsoft Exchange Server。 有关 EOP 支持的操作系统、Web 浏览器和语言的信息，请参阅 Exchange Online Protection 中 Exchange 管理中心中的"支持的浏览器"和"支持的语言["部分](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop)。

## <a name="limits"></a>限制

有关 EOP 中的限制，请参阅Exchange Online Protection[限制](exchange-online-protection-limits.md)。

## <a name="feature-availability"></a>功能可用性

下表列出了跨计划Exchange Online Protection的主要可用功能。 某些注意事项适用。 有关详细信息，请参阅脚注。 此表可能发生更改，恕不另行通知。 有关最新、完整的功能列表，请参阅 [支持企业的强大工具](https://products.office.com/business/compare-more-office-365-for-business-plans)。

| 功能 | 独立 EOP | CAL w/ 服务企业版 EOP | Exchange Online 中的 EOP 功能 |
|:-----|:-----|:-----|:-----|
|**Protection**||||
|反恶意软件策略 (内置和自定义) |是|是|是|
|入站反垃圾邮件策略 (内置和自定义) |是|是|是|
|出站反垃圾邮件策略 (内置和自定义) |是|是|是|
|连接筛选 (IP 允许列表和 IP 阻止列表) |是|是|是|
|反网络钓鱼策略 (内置和自定义) |是|是|是|
|反欺骗保护 (内置和自定义) |是|是|是|
|零时差自动清除 (恶意软件) 垃圾邮件和网络钓鱼邮件的 ZAP 策略<sup>10</sup>|否|否|是|
|预设安全策略|是|是|是|
|保护策略的配置分析器|是|是|是|
|租户允许/阻止列表|是|是|是|
|阻止邮件发件人列表|是|是|是|
|允许邮件发件人列表|是|是|是|
|边缘阻止|是|是|是|
|基于目录的边缘阻止 (不存在) 的 DBEB 策略|是|是|是|
|**隔离和提交**||||
|管理员提交<sup>10</sup>|否|否|是|
|自定义邮箱 (提交) <sup>10</sup>|否|否|是|
|管理员隔离|是|是|是|
|最终用户隔离|是|是|是|
|报告邮件外接程序和报告网页仿冒Outlook|是|是|是|
|**邮件流**||||
|邮件流规则 (传输规则) <sup>4</sup>|是|是<sup>6</sup>|是|
|接受域<sup>3</sup> |是|是|是|
|连接器|是|是|是|
|增强的连接器筛选 (跳过列表) |是|是|是|
|**监视**||||
|邮件跟踪|是|是|是|
|电子邮件和安全报告中Microsoft 365 管理中心|是<sup>7</sup>|是<sup>7、8</sup>|是<sup>8</sup>|
|安全中心Microsoft 365报告|是<sup>7</sup>|是<sup>7、8</sup>|是<sup>8</sup>|
|EAC 中的电子邮件报告|是<sup>7</sup>|是<sup>7、8</sup>|是<sup>8</sup>|
|管理员审核日志记录<sup>5</sup>|是|是|是|
|**Users**||||
|邮件用户和邮件联系人<sup>1</sup>|是|是|是|
|邮箱|否|否|是<sup>1a</sup>|
|基于角色的访问控制 (RBAC) <sup>2</sup>|是|是|是|
|**合规性**||||
|电子邮件的数据丢失防护|否|是|是|
|Office 365 邮件加密|否<sup>9</sup>|否<sup>9</sup>|是|
|**管理**||||
|Microsoft 365 管理中心|是|是|是|
|Exchange 管理中心|是|是|是|
|Microsoft 365 安全中心|是|是|是|
|独立Exchange Online Protection PowerShell|是|否|否|
|Exchange Online PowerShell|否|是|是|

<sup>1</sup> 在 EAC 中创建、删除和编辑邮件用户和邮件联系人。 <br/>
<sup>1a</sup>在邮件中删除邮箱Microsoft 365 管理中心。 可以在 EAC 中编辑现有邮箱。 <br/>
<sup>2</sup>在独立 EOP 企业版 CAL with Services 中，没有最终用户角色或角色分配策略。<br/>
<sup>3</sup>在域中添加和删除Microsoft 365 管理中心。  在 EAC 中，您将域配置为"权威"或"非权威"。<br/>
<sup>4</sup>一些规则条件、例外和操作在独立 EOP 或 企业版 CAL with Services 中的 EOP 中不可用。 邮件流规则内容中Exchange Online这些差异。 <br/>
<sup>5</sup>在独立 EOP 和 企业版 CAL with Services 中：

- 邮箱审核报告不可用。
- 管理员角色组报告和管理员审核日志报告是 EAC 中唯一的管理员审核报告。
- 审核日志导出仅适用于 PowerShell。 <br/>

<sup>6</sup> DLP 策略提示在 企业版 CAL with Services 中不可用。 <br/>
<sup>7</sup>独立 EOP 和 企业版 CAL with Services 中的报告是 Exchange Online 报告 (报告（用于处理邮箱) ）。<br/>
<sup>8</sup> 包括 DLP 报告。 <br/>
<sup>9</sup> 如果配置本地电子邮件环境以通过 EOP 将电子邮件路由到 Internet 和从 Internet 路由，你可以购买 Azure 信息保护作为附加订阅并使用 OME。 <br/>
<sup>10</sup>此功能要求Exchange Online邮箱。 <br/>

## <a name="learn-more"></a>了解详细信息

有关此Exchange Online Protection的信息，请查看以下资源：

此[Microsoft 365路线图](https://office.microsoft.com/products/office-365-roadmap-FX104343353.aspx)是一个很好的资源，用于查找有关即将推出的新功能的信息。

### <a name="licensing-terms"></a>许可条款

有关通过 Microsoft 商业批量许可计划购买的产品和服务的许可条款和条件，请参阅[产品条款网站](https://www.microsoft.com/licensing/terms/)。

### <a name="messaging"></a>消息传递

若要跟踪即将发生的更改，包括新功能和已更改的功能、计划的维护或其他重要公告，请访问“消息中心”。 有关详细信息，请参阅[消息中心](/microsoft-365/admin/manage/message-center)。

### <a name="accessibility"></a>辅助功能

Microsoft 始终致力于确保数据的安全性以及服务的[辅助功能](https://www.microsoft.com/trust-center/compliance/accessibility)。 有关详细信息，请参阅 [Microsoft 信任中心](https://www.microsoft.com/trust-center)和 [Office 辅助功能中心](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)。
