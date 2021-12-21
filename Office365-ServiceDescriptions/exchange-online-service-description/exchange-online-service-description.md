---
title: Exchange Online 服务说明
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-service-description
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 7a83da3c-3b6d-4f86-ad4d-6104707cd0ec
description: 您是否正在查找包含新订阅的订阅Exchange Online？ 如果是这样，Exchange Online 服务说明文章就是您需要的内容。 您还可以了解到系统要求以及存储和收件人要求。
ms.openlocfilehash: 3b683c01f5348a4a50b15fe11df3828bbfaa3f0b
ms.sourcegitcommit: 486c7c8d1a6f8992ef174dfd0ef6137a93046b83
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 12/21/2021
ms.locfileid: "61574989"
---
# <a name="exchange-online-service-description"></a>Exchange Online 服务说明

Microsoft Exchange Online是一种托管邮件解决方案，它从电脑、Web 和移动设备传送电子邮件、日历、联系人和任务。 它与Azure Active Directory集成，使管理员能够使用组策略以及其他管理工具来管理Exchange Online功能。

订阅邮件服务的Exchange Online保留对它们为用户提供的邮件服务的控制权。 利用本文档中描述的 Exchange Online 托管计划，电子邮件将托管在同时支持多个客户的服务器上。 这些服务器位于 Microsoft 数据中心内，可供各种设备（从企业网络内部或 Internet）访问。

## <a name="available-plans-for-exchange-online"></a>可用的Exchange Online

Microsoft 365有多种计划提供，以最好地满足组织的需求。 有关允许用户进行订阅订阅的详细计划Exchange Online，请参阅[完整的订阅比较表](https://go.microsoft.com/fwlink/?linkid=2139145)。

> [!NOTE]
> 每位访问 Exchange Online 服务的用户均必须分配一个订阅计划，且每个用户订阅均具有自身的邮箱。 这些邮箱中的文件夹和邮件驻留在 Microsoft 数据中心。 会议室和共享邮箱不需要用户订阅。 这些特殊邮箱类型没有登录凭据，而是具有适当权限的许可用户通过委派管理和访问它们。 Microsoft 365 F1不包括对邮箱Exchange权限。 若要启用完整的Teams体验，Microsoft 365 F1 K1 服务计划Exchange Online许可证。 尽管 Exchange Online K1 服务计划将为用户设置邮箱，Microsoft 365 F1用户无权使用该邮箱。 建议通过这些步骤Outlook 网页版邮箱，并要求用户不要通过[](/exchange/recipients-in-exchange-online/manage-user-mailboxes/enable-or-disable-outlook-web-app)任何其他Exchange访问邮箱。

## <a name="feature-availability-including-standalone-plans"></a>功能可用性 (包括独立计划) 

下表列出了跨计划Exchange Online的主要可用功能 (一些注意事项（请参阅脚注了解详细信息）此表可能会更改，) 。 有关跨计划功能的最最新完整列表，请参阅支持 [企业的强大工具](https://products.office.com/business/compare-more-office-365-for-business-plans)。 有关 Microsoft 365 商业版计划 (基本、标准和高级) 中的功能可用性，请参阅[Microsoft 365 商业](https://aka.ms/M365BusinessPlans)版计划，或访问 Microsoft 365 管理中心 中的消息中心或与提供商联系，了解有关新的 Microsoft 365 应用版 计划如何影响您的更多详细信息。

### <a name="features-available-to-all-plans"></a>所有计划可用的功能

这些功能适用于所有商业版 (基本、标准和高级) 、Enterprise (E1、E3、E5 和 F3) 以及 Exchange Online 计划 (1、2 和展台) – 有关详细信息，请参阅脚注。

- 反垃圾邮件和反恶意软件保护 [**(**](/exchange/antispam-and-antimalware/antispam-and-antimalware)通过直接访问 Exchange 管理中心管理界面) ：内置反垃圾邮件和反恶意软件保护 (使用多个反恶意软件引擎扫描入站、出站和内部邮件中恶意软件) 、自定义的反垃圾邮件和反恶意软件策略、隔离 - 管理员管理和隔离 - 最终用户自我管理。
- [**Exchange Online和管理**](/exchange/architecture/client-access/exchange-admin-center)**：** Microsoft 365门户和管理中心访问权限， Exchange 管理中心访问， 远程 Windows PowerShell 访问， 移动设备的 ActiveSync 策略，[使用情况报告](/exchange/monitoring/monitoring)。
- [**高可用性和业务连续性**](/exchange/high-availability/high-availability)：数据中心的邮箱复制、单个项目 (不适用于 F3 和 Kiosk 计划) 已删除的邮箱和已删除的项目 [恢复](/exchange/recipients/disconnected-mailboxes/restore-deleted-mailboxes)。
- 互操作性、连接性和 [**兼容性**](/exchange/security-and-compliance/interoperability-connectivity-and-compatiblity)**：OWA** 中的 Skype for Business 状态和 Outlook、SharePoint 互操作性、EWS 连接支持 (EWS 应用支持（应用于模拟) 、SMTP 中继支持）。
- [](/exchange/security-and-compliance/mail-flow-rules/mail-flow-rules)邮件流：出站邮件的自定义路由、与受信任合作伙伴的安全邮件传递、将合作伙伴添加到入站安全列表、条件邮件和混合电子邮件路由 (CAL 或升级到 Enterprise SKU 提供访问权限) 。
- [](/exchange/plan-and-deploy/plan-and-deploy)[](/exchange/hybrid-deployment/hybrid-deployment)规划和部署：支持 (CAL 或升级到 Enterprise SKU 的混合部署为企业版和 F3 计划提供访问权限[) 、IMAP、](/exchange/mailbox-migration/migrating-imap-mailboxes/migrating-imap-mailboxes)转换和分[步迁移支持](/exchange/mailbox-migration/what-to-know-about-a-staged-migration)。
- 报告 [**功能和**](/office365/servicedescriptions/exchange-online-service-description/reporting-features-and-troubleshooting-tools)疑难解答工具 **：Microsoft 365 管理中心报告**、Excel报告工作簿、Web 服务报告、统一消息报告 (E3/E5 和计划 2) 。 邮件跟踪和[审核报告](/exchange/exchange-auditing-reports-exchange-2013-help)可通过直接访问 EAC Exchange管理中心 (EAC) 访问。
- [](/exchange/recipients-in-exchange-online/recipients-in-exchange-online)收件人：容量警报、待筛选邮件、邮件提示、收件箱规则、脱机通讯簿、通讯簿策略、通讯组、外部联系人 (全局) 、通用联系人卡片、社交网络的联系人链接、资源邮箱、会议室管理、外出答复、日历共享 (Kiosk 日历只能通过 OWA) 访问或共享。
- 共享 [**和**](/exchange/sharing/sharing)协作：必须包含和部署联合共享 (包括日历发布) 、网站邮箱 (SharePoint Online) 以及公用文件夹 (不适用于 F3 和网亭计划) 。
- [**语音邮件服务**](/exchange/plan-and-deploy/integration-with-sharepoint-and-skype/integration-with-sharepoint-and-skype)**：Skype for Business** 集成。 第三方语音邮件互操作性。 仅 E3/E5 和计划 2 提供语音邮件和第三方语音邮件/传真集成。 有关通过直接连接的第三方 PBX 系统，请参阅[Cingation of support for Session Border Controllers in Exchange Online Unified Messaging](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/New-date-for-discontinuation-of-support-for-Session-Border/ba-p/607853)。

## <a name="features-available-to-some-plans"></a>某些计划可用的功能

这些功能可用于某些计划 - 有关进一步的信息，请参阅脚注， (此表可能会更改，) 。

| 功能 | 说明 | Microsoft 365 商业基础版、Standard 和 高级版 | Office 365 企业版 E1 | Office 365 企业版 E3/E5 | Office 365 企业版 F3 | Exchange Online计划 1/2 | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**[客户端和移动设备](/exchange/clients-and-mobile-in-exchange-online/clients-and-mobile-in-exchange-online)**|Outlook 网页版<sup>1</sup>、Outlook for iOS 和 Android<sup>1、Exchange ActiveSync</sup>和 SMTP|是|是|是|是|是|是|
||POP 和 IMAP|是|是|是|是<sup>2</sup>|是|是<sup>3</sup>|
||EWS 应用程序支持，Outlook 1 Windows<sup>1，Outlook for Mac</sup><sup>1</sup>|是|是|是|否|是|否|
||基本移动性和安全性Microsoft 365|是|是|是|是|||
|**[邮件策略和合规性](/exchange/policy-and-compliance/policy-and-compliance)**|[存档基于 Exchange Online 的邮箱](/exchange/policy-and-compliance/in-place-archiving/in-place-archiving)|是<sup>4</sup>|是<sup>4</sup>|是<sup>4</sup>|否|是|是|
||内部部署邮箱的基于云的存档|否|是|是|否|是<sup>5</sup>|是|
||[手动保留策略、标签和标记](/exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies)|否|是|是|是|是|是|
||[使用 Azure 信息保护<sup>6、Office 365 邮件加密</sup>](/exchange/policy-and-compliance/in-place-archiving/in-place-archiving)<sup>7</sup>和客户密钥<sup>8</sup>的 IRM|否|否|是|否|否|否|
||In-Place保留、诉讼保留和数据丢失防护|否|否|是|否|是<sup>5</sup>|是|
||静态数据的加密 (BitLocker) 、邮件记录管理 (MRM) 、S/MIME、日记、In-Place 电子数据展示<sup>9、</sup>传输规则<sup>10、</sup>使用 Windows Server AD RMS<sup>11</sup>的 IRM|是|是|是|是|是|是|
|**[权限](/exchange/permissions-exo/permissions-exo)**|基于角色的权限、角色组和角色分配策略|是|是|是|否|是|否|
|**[收件人](/exchange/recipients-in-exchange-online/recipients-in-exchange-online)**|委派访问和分层通讯簿|是|是|是|否|是|否|
||已连接帐户<sup>12、</sup>地址列表和全局地址列表<sup>13</sup>|是|是|是|是|是|是|
||非活动邮箱|否|否|是|否|是<sup>5</sup>|否|
||Microsoft 365 组|是|是|是|是|是<sup>14</sup>|否|

<sup>1</sup>某些第三方 Web 部件和外接程序可能不可用。 <br/>
<sup>2 Windows Server AD</sup> RMS 是必须单独购买和管理才能启用受支持的 IRM 功能本地服务器。 <br/>
<sup>3</sup> 不支持 IMAP。 <br/>
<sup>4</sup> 可以单独为需要非活动邮箱或存档功能的每个邮箱购买 EOA 订阅。 <br/>
<sup>5</sup> 仅计划 2。 <br/>
<sup>6</sup> 单独购买的 AIP 以启用 IRM 功能。 某些 AIP 功能还要求 M365 企业应用版 (E1/F3 或商业版计划不包含在内。 <br/>
<sup>7</sup> Office 365 邮件加密取决于 AIP。 <br/>
<sup>8</sup> 仅适用于 E5 的客户密钥。 <br/>
<sup>9</sup> 对于电子数据展示，需要针对本地与云的单独查询。<br/>
<sup>10</sup> 传输规则由灵活条件（允许您定义条件和例外）以及基于条件采取的操作（这些条件）所决定。 有关可用条件和操作的列表，请参阅每款产品的相应条件和操作主题。 <br/>
<sup>11</sup> Windows Server AD RMS 是本地服务器，必须单独购买和管理才能启用支持的 IRM 功能。 <br/>
<sup>12</sup>已连接帐户受 POP & IMAP 帐户支持，但对于 Outlook.com (Hotmail) 。 <br/>
<sup>13</sup>不支持在 Exchange Online PowerShell 中使用 cmdlet 自定义默认地址列表和 GAL (默认) 全局地址列表。 <br/>
<sup>14</sup> Microsoft 365组具有缩减功能。 <br/>

## <a name="additional-services"></a>其他服务

### <a name="scheduler-for-microsoft-365"></a>Microsoft 365 专属计划员

Microsoft 365计划程序是一个Exchange Online加载项，它使用户能够将其日程安排需求委派给数字个人助理。 助理可以安排和重新安排与组织内外人员之间的约会和会议。 助理邮箱由租户设置和控制。 若要启用计划程序，管理员需要通过 PowerShell cmdlet 设置助理的邮箱，并购买会议组织者的许可证。 若要详细了解计划程序及其工作方式，请参阅欢迎[使用计划程序Microsoft 365。](/microsoft-365/scheduler/scheduler-overview#how-does-scheduler-for-microsoft-365-work) 有关计划程序定价和许可，请参阅[计划程序Microsoft 365许可](https://www.microsoft.com/microsoft-365/meeting-scheduler-pricing)。

## <a name="learn-more"></a>了解详细信息

有关此Exchange Online，请查看以下资源：

- **Exchange Server：** 若要详细了解Exchange Server，请转到Exchange Server [可用性](/Exchange/new-features/feature-availability)表。
- [**电子邮件**](https://support.office.com/article/Email-94275804-7147-4332-9ccd-5d421760a9ed) ，帮助创建和发送电子邮件。
- [**管理电子邮件和日历**](/office365/admin/email/email)
- [**关于 Microsoft 支持和恢复助手**](https://diagnostics.office.com/)
- [**Exchange Online 中的电子邮件未送达报告**](/Exchange/mail-flow-best-practices/non-delivery-reports-in-exchange-online/non-delivery-reports-in-exchange-online)
- [**Exchange Online 帮助**](/exchange/exchange-online)
- 有关跨计划的功能详细信息，请参阅 [用于支持企业的强大工具](https://products.office.com/business/compare-more-office-365-for-business-plans)。
- 可以在 Microsoft 服务说明中导出、保存和打印页面。 了解如何导出 [**内容搜索结果**](/office365/securitycompliance/export-search-results)。
- **Exchange中心** 中的新增功能：有关 Exchange 管理中心中的新功能的信息，请参阅 Exchange [管理中心的新增功能](/exchange/whats-new)。
- **Exchange Online的系统要求：有关** 系统要求，适用于企业、教育以及政府组织的基于每月订阅的服务，请参阅 Microsoft 365 [and Office Resources](https://products.office.com/office-system-requirements/#Office365forBEG)。
- 存储和收件人Exchange Online：有关 Exchange Online 订阅计划中提供的存储和收件人限制的信息，请参阅Exchange Online[限制](/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits)。
- **消息传递：** 若要及时了解即将进行的更改，包括新功能和已更改的功能、计划的维护或其他重要通知，请访问消息中心。 有关详细信息，请参阅[消息中心](/microsoft-365/admin/manage/message-center)。
- 许可条款：有关通过 Microsoft 商业批量许可计划购买的产品和服务的许可条款和条件，请参阅产品 [条款网站](https://www.microsoft.com/licensing/terms/)。
- **辅助功能：** Microsoft 始终致力于确保数据的安全性 [以及服务的](https://www.microsoft.com/trust-center/compliance/accessibility) 辅助功能。 有关详细信息，请参阅 [Microsoft 信任中心](https://www.microsoft.com/trust-center)和 [Office 辅助功能中心](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)。
