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
description: 是否在查找包含 Exchange Online 的订阅的功能比较？ 如果是这样，Exchange Online 服务说明文章就是您需要的内容。 您还可以了解到系统要求以及存储和收件人要求。
ms.openlocfilehash: 9bd7516e126af8b656ef8af1c6386adaaaa2a4eb
ms.sourcegitcommit: 97f6183334bb103e7b0171cb0ceebcddac25e24f
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/21/2022
ms.locfileid: "65019304"
---
# <a name="exchange-online-service-description"></a>Exchange Online 服务说明

Microsoft Exchange Online是一种托管消息传送解决方案，可从电脑、Web 和移动设备传送电子邮件、日历、联系人和任务。 它与 Azure Active Directory 完全集成，使管理员能够使用组策略和其他管理工具来管理整个环境中Exchange联机功能。

订阅 Exchange Online 的组织保留对他们提供给用户的消息服务的控制权。 利用本文档中描述的 Exchange Online 托管计划，电子邮件将托管在同时支持多个客户的服务器上。 这些服务器位于 Microsoft 数据中心，用户可从公司网络内部或 Internet 上访问各种设备。

## <a name="available-plans-for-exchange-online"></a>Exchange Online 的可用计划

Microsoft 365可在各种计划中提供，以满足组织的需求。 有关为用户启用 Exchange Online 的订阅的详细计划信息，请参阅[完整的订阅比较表](https://go.microsoft.com/fwlink/?linkid=2139145)。

> [!NOTE]
> 每位访问 Exchange Online 服务的用户均必须分配一个订阅计划，且每个用户订阅均具有自身的邮箱。 这些邮箱中的文件夹和邮件位于 Microsoft 数据中心。 会议室和共享邮箱不需要用户订阅。 这些特殊邮箱类型没有登录凭据，而是拥有相应权限的许可用户通过委派管理和访问这些凭据。 Microsoft 365 F1 不包括对Exchange邮箱的权限。 若要启用完整的Teams体验，Microsoft 365 F1 许可证可能附带启用了 Exchange Online K1 服务计划。 虽然 Exchange Online K1 服务计划将为用户预配邮箱，但Microsoft 365 F1 用户无权使用邮箱。 建议通过[这些步骤](/exchange/recipients-in-exchange-online/manage-user-mailboxes/enable-or-disable-outlook-web-app)禁用Outlook 网页版，并要求用户不要通过任何其他方法访问Exchange邮箱。

## <a name="feature-availability-including-standalone-plans"></a>功能可用性 (包括独立计划) 

下表列出了所有计划中可用的主要Exchange联机功能， (某些注意事项适用 - 请参阅脚注以获取更多信息 -- 此表可能会在不通知) 的情况下更改。 有关计划中最新的功能完整列表，请参阅 [支持企业功能的强大工具](https://products.office.com/business/compare-more-office-365-for-business-plans)。 有关Microsoft 365业务计划 (基本、标准和高级) 中的功能可用性，请[参阅Microsoft 365业务计划](https://aka.ms/M365BusinessPlans)，或访问Microsoft 365 管理中心中的邮件中心，或与提供商联系，了解有关新Microsoft 365 应用版计划对你的影响的更多详细信息。

### <a name="features-available-to-all-plans"></a>所有计划都可用的功能

这些功能适用于所有业务 (基本、标准和高级) 、企业 (E1、E3、E5 和 F3) 以及 Exchange Online 计划 (1、2 和展台) – 注意事项适用于详细信息的脚注。

- [**反垃圾邮件和反恶意软件保护**](/exchange/antispam-and-antimalware/antispam-and-antimalware) (通过直接访问Exchange管理中心管理界面) **：** 内置的反垃圾邮件和反恶意软件保护 (使用多个反恶意软件引擎来扫描恶意软件) 的入站、出站和内部消息、自定义的反垃圾邮件和反恶意软件策略、隔离 - 管理员管理和隔离 - 最终用户自我管理。
- [**Exchange联机设置和管理**](/exchange/architecture/client-access/exchange-admin-center)**：** Microsoft 365门户和管理中心访问、Exchange管理中心访问、远程 Windows PowerShell 访问、移动设备的 ActiveSync 策略、[使用情况报告](/exchange/monitoring/monitoring)。
- [**高可用性和业务连续性**](/exchange/high-availability/high-availability)**：** 数据中心的邮箱复制、单项恢复 (不适用于 F3 和展台计划) [已删除的邮箱和已删除的项目恢复](/exchange/recipients/disconnected-mailboxes/restore-deleted-mailboxes)。
- [**互操作性、连接性和兼容性**](/exchange/security-and-compliance/interoperability-connectivity-and-compatiblity)**：** Skype for Business OWA 和Outlook中的状态、SharePoint互操作性、EWS 连接支持 (应用于模拟) 的 EWS 应用支持、SMTP 中继支持。
- [**邮件流**](/exchange/security-and-compliance/mail-flow-rules/mail-flow-rules)**：** 自定义出站邮件路由、与受信任的合作伙伴一起进行安全邮件传递、将合作伙伴添加到入站安全列表，以及条件邮件和混合电子邮件路由 (CAL 或升级到企业 SKU 提供访问权限) 。
- [**规划和部署**](/exchange/plan-and-deploy/plan-and-deploy)**：**[支持混合部署](/exchange/hybrid-deployment/hybrid-deployment) (CAL 或升级到企业 SKU，为业务和 F3 计划提供访问权限，) 、[IMAP](/exchange/mailbox-migration/migrating-imap-mailboxes/migrating-imap-mailboxes)、直接转换和 [分阶段迁移](/exchange/mailbox-migration/what-to-know-about-a-staged-migration)支持。
- [**报告功能和故障排除工具**](/office365/servicedescriptions/exchange-online-service-description/reporting-features-and-troubleshooting-tools)**：** Microsoft 365 管理中心报表、Excel报告工作簿、Web 服务报表、统一消息报表 (E3/E5 和计划 2 仅) 。 消息跟踪和[审核报告](/exchange/exchange-auditing-reports-exchange-2013-help)可通过直接访问 Exchange 管理中心 (EAC) 管理接口进行访问。
- [**收件人**](/exchange/recipients-in-exchange-online/recipients-in-exchange-online)**：** 容量警报、混乱、邮件提示、收件箱规则、脱机通讯簿、通讯簿策略、通讯组、通讯组、全球)  (外部联系人、通用联系人卡片、与社交网络的联系人链接、资源邮箱、会议室管理、外出答复、日历共享 (展台日历只能通过 OWA) 访问或共享。
- [**共享和协作**](/exchange/sharing/sharing)**：** 联合共享 (包括日历发布) 、网站邮箱 (SharePoint联机必须包括和部署) ，公共文件夹 (不适用于 F3 和展台计划) 。
- [**语音消息服务**](/exchange/plan-and-deploy/integration-with-sharepoint-and-skype/integration-with-sharepoint-and-skype)**：** Skype for Business集成。 第三方语音邮件互操作性。 只有 E3/E5 和计划 2 提供语音邮件和第三方语音邮件/传真集成。 对于通过直接连接的第三方 PBX 系统，请参阅[停止对Exchange联机统一消息传送中的会话边界控制器的支持](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/New-date-for-discontinuation-of-support-for-Session-Border/ba-p/607853)。

## <a name="features-available-to-some-plans"></a>某些计划可用的功能

这些功能可用于某些计划 - 请注意，请参阅脚注以获取详细信息 (此表可能会更改，而无需通知) 。

| 功能 | 说明 | Microsoft 365 商业基础版、业务标准 | Microsoft 365 商业高级版 | Office 365 E1 | Microsoft 365 E3/E5 & Office 365 E3/E5 | Microsoft 365 F3 & Office 365 F3 | Exchange Online 计划 2 | Exchange Online 计划 1 | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**[客户端和移动设备](/exchange/clients-and-mobile-in-exchange-online/clients-and-mobile-in-exchange-online)**|Outlook 网页版<sup>1</sup>，适用于 iOS 和 <sup>Android1</sup>、Exchange ActiveSync 和 SMTP 的Outlook|是|是|是|是|是|是|是|是|
||POP 和 IMAP|是|是|是|是|是<sup>2</sup>|是|是|是<sup>2</sup>|
||适用于 <sup>Windows1</sup> 的 EWS 应用程序支持Outlook，Outlook for Mac <sup>1</sup>|是|是|是|是|否|是|是|否|
||Microsoft 365的基本移动性和安全性|是|是|是|是|是||||
|**[邮件策略和合规性](/exchange/policy-and-compliance/policy-and-compliance)**|[Exchange联机Exchange存档](/office365/servicedescriptions/exchange-online-archiving-service-description/archive-features)|否|否|否|是|否|是|否|否|
||[适用于 Exchange Server 的 Exchange Online Archiving](/office365/servicedescriptions/exchange-online-archiving-service-description/archive-features)|否|否|否|是|否|是|否|否|
||[手动保留策略、标签和标记](/exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies)|否|是|是|是|是|是|是|是|
||[使用 Azure 信息保护的 IRM](/exchange/policy-and-compliance/in-place-archiving/in-place-archiving)|否|否|否|是|否|否|否|否|
||基本消息加密|是|是|是|是|是|是|是|是|
||高级消息加密|否|否|否|是|否|否|否|否|
||客户密钥|否|否|否|是|否|否|否|否|
||In-Place保留、诉讼保留|否|是|否|是|否|是|否|否|
||数据丢失防护|否|是|否|是|否|否|否|否|
||将静态数据加密 (BitLocker) 、消息记录管理 (MRM) 、S/MIME、日记、电子数据展示内容搜索<sup>3</sup>、传输规则 <sup>4</sup>|是|是|是|是|是|是|是|是|
||使用 Windows Server AD <sup>RMS5</sup> 支持 IRM|是|是|是|是|是|是|是|是|
|**[权限](/exchange/permissions-exo/permissions-exo)**|基于角色的权限、角色组和角色分配策略|是|是|是|是|否|是|是|否|
|**[收件人](/exchange/recipients-in-exchange-online/recipients-in-exchange-online)**|委托访问和分层通讯簿|是|是|是|是|否|是|是|否|
||非活动邮箱|否|否|否|是|否|是|否|否|
||Microsoft 365 组|是|是|是|是|是|是<sup>6</sup>|是<sup>6</sup>|否|

<sup>1</sup>某些第三方 Web 部件和外接程序可能不可用。<br/>
<sup>支持 2</sup> POP，但 IMAP 不支持。<br/>
<sup>3</sup> 对于电子数据展示，需要本地与云的单独查询。<br/>
<sup>4</sup> 传输规则由灵活条件组成，允许定义条件和异常，以及根据条件执行的操作。 有关可用条件和操作的列表，请参阅每款产品的相应条件和操作主题。 <br/>
<sup>5</sup> Windows Server AD RMS 是本地服务器，必须单独购买和管理才能启用支持的 IRM 功能。<br/>
<sup>有 6</sup> 个Microsoft 365 组可用，但功能已减少。<br/>

## <a name="additional-services"></a>其他服务

### <a name="scheduler-for-microsoft-365"></a>Microsoft 365 专属计划员

Microsoft 365计划程序是Exchange Online 的加载项，使用户能够将其计划需求委托给数字个人助理。 助理可以安排和重新安排与组织内外人员的约会和会议。 助理邮箱由租户设置和控制。 若要启用计划程序，管理员需要通过 PowerShell cmdlet 设置助理的邮箱，并为会议组织者购买许可证。 若要了解有关计划程序及其工作原理的详细信息，请[参阅“欢迎使用计划程序Microsoft 365](/microsoft-365/scheduler/scheduler-overview#how-does-scheduler-for-microsoft-365-work)。 有关计划程序定价和许可，请参阅[计划程序Microsoft 365许可](https://www.microsoft.com/microsoft-365/meeting-scheduler-pricing)。

## <a name="learn-more"></a>了解详细信息

有关联机Exchange的详细信息，请查看以下资源：

- **Exchange服务器：** 有关Exchange服务器的详细信息，请转到 [Exchange服务器功能可用性](/Exchange/new-features/feature-availability)表。
- [**电子邮件**](https://support.office.com/article/Email-94275804-7147-4332-9ccd-5d421760a9ed) 以获取有关创建和发送电子邮件的帮助。
- [**管理电子邮件和日历**](/office365/admin/email/email)
- [**关于Microsoft 支持部门和恢复助手**](https://diagnostics.office.com/)
- [**Exchange Online 中的电子邮件未送达报告**](/Exchange/mail-flow-best-practices/non-delivery-reports-in-exchange-online/non-delivery-reports-in-exchange-online)
- [**Exchange Online 帮助**](/exchange/exchange-online)
- 有关跨计划的功能的详细信息，请参阅 [功能强大的工具来支持你的企业](https://products.office.com/business/compare-more-office-365-for-business-plans)。
- 可以在 Microsoft 服务说明中导出、保存和打印页面。 了解如何 [**导出内容搜索结果**](/office365/securitycompliance/export-search-results)。
- **Exchange管理中心的新增功能：** 有关管理中心Exchange新功能的信息，请参阅 [Exchange管理中心的新增功能](/exchange/whats-new)。
- **Exchange联机的系统要求：** 有关系统要求，请参阅 [Microsoft 365和 Office 资源](https://products.office.com/office-system-requirements/#Office365forBEG)，了解企业、教育和政府组织每月可用的基于订阅的服务。
- Exchange联机的存储和收件人限制：有关Exchange联机订阅计划中可用的存储和收件人限制的信息，[请参阅Exchange联机限制](/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits)。
- **消息：** 若要随时了解即将发生的更改，包括新功能和更改的功能、计划内维护或其他重要公告，请访问消息中心。 有关详细信息，请参阅[消息中心](/microsoft-365/admin/manage/message-center)。
- 许可条款：有关通过 Microsoft 商业批量许可计划购买的产品和服务的许可条款和条件，请参阅 [产品条款网站](https://www.microsoft.com/licensing/terms/)。
- **辅助功能：** Microsoft 仍致力于数据的安全性和服务的 [辅助功能](https://www.microsoft.com/trust-center/compliance/accessibility) 。 有关详细信息，请参阅 [Microsoft 信任中心](https://www.microsoft.com/trust-center)和 [Office 辅助功能中心](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)。
