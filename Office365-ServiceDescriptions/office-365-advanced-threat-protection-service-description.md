---
title: Microsoft Defender for Office 365 服务说明
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Defender for Office 365 是一种基于云的电子邮件筛选服务，它通过提供强大的零日保护来帮助组织抵御未知恶意软件和病毒，并包括实时保护组织免受恶意链接危害的功能。
ms.openlocfilehash: b3eb9d94fdd96899a0d08e591715a07354104c25
ms.sourcegitcommit: 29db3ccfdd875fc8968e11c040c6db46c2720134
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 01/12/2021
ms.locfileid: "49799401"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Microsoft Defender for Office 365 服务说明

Microsoft Defender for Office 365 是一种基于云的电子邮件筛选服务，它通过提供强大的零日保护来帮助组织抵御未知恶意软件和病毒，并包括实时保护组织免受恶意链接危害的功能。 Defender for Office 365 具有丰富的报告和 URL 跟踪功能，使管理员能够深入了解组织中发生的攻击类型。

以下是可以使用适用于 Office 365 的 Defender 进行邮件保护的主要方法：

- 在 Defender for Office 365 仅筛选方案中，Defender for Office 365 为本地 Exchange Server 环境或其他任何本地 SMTP 电子邮件解决方案提供基于云的电子邮件保护。

- 可以启用 Defender for Office 365 来保护 Exchange Online 云托管的邮箱。 若要详细了解 Exchange Online，请参阅 [Exchange Online 服务说明](exchange-online-service-description/exchange-online-service-description.md)。

- 在混合部署中，可以将 Defender for Office 365 配置为在将本地邮箱和云邮箱与 Exchange Online Protection 混合用于入站电子邮件筛选时保护邮件环境和控制邮件路由。

## <a name="microsoft-defender-for-office-365-availability"></a>Microsoft Defender for Office 365 可用性

Microsoft Defender for Office 365 计划 2 包含在 Office 365 E5、Office 365 A5、Microsoft 365 E5 安全与 Microsoft 365 E5 中，如此处所 [https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp) 指定： Microsoft 365 商业高级版中包含 Defender for Office 365 计划 1。

你可以将 Defender for Office 365 添加到以下 Exchange 和 Microsoft 365 订阅计划：

- Exchange Online 计划 1

- Exchange Online 计划 2

- Exchange Online Kiosk

- Exchange Online Protection

- Microsoft 365 商业基础版

- Microsoft 365 商业标准版

- Office 365 企业版 E1

- Office 365 企业版 E3

- Office 365 企业版 F3

- Office 365 A1

- Office 365 A3

若要购买 Microsoft Defender for Office 365，请参阅[Microsoft Defender for Office 365。](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)

若要跨计划比较功能，请参阅[](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409)用于支持企业以及使用[Microsoft 365](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans)转换企业的强大工具。

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Microsoft Defender for Office 365 的新增功能

我们将继续向 Defender for Office 365 添加新功能。 若要了解有关适用于 Office 365 (Defender 或 Microsoft 365 的新功能) ，请参阅以下资源：

- [Microsoft 365 路线图](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Microsoft Defender for Office 365 的新增功能](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Microsoft Defender for Office 365 的要求

Defender for Office 365 可以与任意 SMTP 邮件传输代理（如 Microsoft Exchange Server） 一Microsoft Exchange Server。 有关适用于 Office 365 的 Defender 支持的操作系统、Web 浏览器和语言的信息，请参阅 [Exchange Online Protection 中 Exchange](https://go.microsoft.com/fwlink/p/?LinkId=282381)管理中心中的"支持的浏览器"和"支持的语言"部分。

## <a name="feature-availability-across-defender-for-office-365-plans"></a>跨 Defender for Office 365 计划的功能可用性

下面列出了每个功能。 当提到 Exchange Online 时，通常指的是 Office 365 企业版服务系列。<br><br>

| 功能 | Defender for Office 365 计划 1 | Defender for Office 365 计划 2 | Microsoft 365 E5 /E5 安全|
|:-----|:-----|:-----|:-----|
|*配置、保护和检测*|
|[安全附件](#safe-attachments)|是|是|是|
|Teams 中的安全附件|是|是|是|
|[安全链接](#safe-links)|是|是|是|
|[安全文档](#safe-documents)|否|否|是|
|Teams 中安全链接|是|是|是|
|[适用于 SharePoint、OneDrive 和 Microsoft Teams 的 ATP](#atp-for-sharepoint-onedrive-and-microsoft-teams)|是|是|是|
|[防钓鱼策略](#anti-phishing-policies)|是|是|是|
|[实时报告](#real-time-reports)|是|是|是|
|*自动化、调查、修正和教育*|
|[威胁跟踪器](#threat-trackers)|否|是|是|
|威胁调查 (高级威胁调查) |[实时检测](#real-time-detections)|[资源管理器](#explorer)|[资源管理器](#explorer)|
|[自动事件响应](#automated-incident-response)|否|是|是|
|[攻击模拟器](#attack-simulator)|否|是|是|
|*与 [Microsoft 365 Defender 集成](https://docs.microsoft.com/microsoft-365/security/mtp/microsoft-threat-protection)*|否|是|是|

> [!NOTE]
> 如果你的租户只有 Microsoft Defender for Office 计划 P2 试用许可证或 Office 365 E5 试用许可证，而 Microsoft 365 Defender 没有其他符合条件的许可证，你将无法访问 Microsoft 365 Defender。 若要了解有关 MTP 许可证的更多信息，请参阅 [Microsoft 365 Defender 要求](https://docs.microsoft.com/microsoft-365/security/mtp/prerequisites)。

## <a name="defender-for-office-365-capabilities"></a>Defender for Office 365 功能

### <a name="safe-attachments"></a>安全附件

[安全附件](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) 可抵御未知恶意软件和病毒，并提供零日保护来保护邮件系统。 所有没有已知病毒/恶意软件签名的邮件和附件将路由到 Defender for Office 365 使用各种机器学习和分析技术检测恶意意图的特殊环境。 如果没有检测到可疑的活动，会发布邮件并传递到邮箱中。

> [!NOTE]
> 安全附件扫描发生在 Office 365 数据所在的同一区域。 有关数据中心地理位置的信息，请参阅 [数据所在的位置？](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>安全链接

安全 [链接](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) 功能可主动保护用户免受邮件或 Office 文档中的恶意 URL 的攻击。 每次选择链接时，将继续提供保护，因为会在访问良好的链接时动态地阻挡恶意链接。

安全链接可用于以下应用中的 URL：

- Windows 或 Mac 上的 Microsoft 365 企业应用版

- Office web 版（Word 网页版、Excel 网页版、PowerPoint 网页版、OneNote 网页版）

- Windows 上的 Word、Excel 和 PowerPoint

- Microsoft Teams 频道和聊天

> [!NOTE]
> 用户必须获得适用于 Office 365 的 Defender 的许可，必须包含在安全链接策略中，并且必须登录其设备，保护 <sup>\*</sup> 就位。
>
> <sup>\*</sup> 对于组织范围内的 Defender for Office 365 许可证 (例如 ATP_ENTERPRISE_FACULTY) ，无需向单个用户分配 Defender for Office 365 许可证。
>
> 有关安全链接保护详细信息，请参阅适用于 [Office 365 的 Microsoft Defender 中的安全链接](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)。

### <a name="safe-documents"></a>安全文档

安全 [文档](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs) 功能使用 [Microsoft Defender for Endpoint](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) 扫描在受保护的视图中打开 [的文档和文件](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)。

在开始之前，您需要知道什么？

- 安全文档现在通常可供 Office 版本 2004 (12730.x) 或更高！ 默认情况下，此功能已关闭，并且需要由安全管理员启用。

- 此功能仅适用于拥有 Microsoft 365 E5 或 Microsoft 365 E5 安全许可证的用户 (Defender for Office 365 计划未) 。

- Windows 上的 Word、Excel 和 PowerPoint

- Microsoft Teams 频道和聊天

> [!NOTE]
> 用户必须获得 Microsoft 365 E5 或 Microsoft 365 E5 安全许可，必须包含在安全文档策略中，并且必须在其设备上登录，保护就位。 <sup>\*</sup>
>
> 有关安全文档保护详细信息，请参阅 [Microsoft 365 E5 中的安全文档](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs)。

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>适用于 SharePoint、OneDrive 和 Microsoft Teams 的 ATP

[适用于 SharePoint、OneDrive](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  和 Microsoft Teams 的 ATP 可帮助检测和阻止团队网站和文档库中标识为恶意的文件。 此外，Microsoft Teams 频道和聊天中现在提供安全链接保护。

### <a name="anti-phishing-policies"></a>防钓鱼策略

[防钓鱼功能](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) 检查传入邮件，以识别邮件可能是网络钓鱼尝试的指示器。 当 Defender for Office 365 策略 (安全附件、安全链接或防钓鱼) 涵盖用户时，传入邮件会由多个机器学习模型进行评估，这些模型可分析邮件，并基于配置的策略采取适当的操作。

### <a name="real-time-reports"></a>实时报告

安全与合规中心 () 中提供的监视功能包括实时报告和见解，让安全与合规管理员专注于高优先级问题，例如安全攻击或可疑活动增加。 & [https://protection.office.com](https://protection.office.com) [](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) 除了突出显示问题区域外，智能报告和见解还包括用于查看和浏览数据以及快速操作的建议和链接。

### <a name="explorer"></a>资源管理器

资源管理器（也称为威胁资源管理器）是一种实时报告，可让授权用户能够识别和分析最近的威胁。 默认情况下，此报告显示过去七天的数据;但是，可以修改视图以显示过去 30 天的数据。

资源管理器包含一些视图，例如 (电子邮件和内容) 、提交、网络钓鱼以及所有电子邮件的恶意软件。 若要了解资源管理器与实时检测的比较，[请下载此 PDF。](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

有关适用于 Office 365 计划 2) 的 Microsoft Defender 中的资源管理器 (和 Microsoft Defender for Office 365 计划 1 (中的实时检测) ，请参阅威胁资源管理器和实时[检测。](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)

### <a name="real-time-detections"></a>实时检测

实时检测是一种实时报告，可让授权用户能够识别和分析最近的威胁。 与资源管理器类似，默认情况下，此报告显示过去七天的数据。

实时检测包含视图，例如电子邮件 (、提交和网络钓鱼) 恶意软件。 若要了解实时检测与资源管理器的比较，[请下载此 PDF。](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

有关适用于 Office 365 计划 2) 的 Microsoft Defender 中的资源管理器 (和 Microsoft Defender for Office 365 计划 1 (中的实时检测) ，请参阅威胁资源管理器 (和实时检测[) 。 ](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)

### <a name="threat-trackers"></a>威胁跟踪器

[威胁跟踪](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) 器是信息小组件和视图，可为授权用户提供可能会影响组织的网络安全问题情报。

### <a name="automated-incident-response"></a>自动事件响应

[通过](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) Defender for Office 365 计划 2 (AIR) 功能提供的自动事件响应，可以运行自动调查流程，以响应当今存在的已知威胁。 通过自动执行某些调查任务，安全运营团队可以更高效地运行。 安全运营团队批准后，将执行修正操作，如删除恶意电子邮件。 若要了解更多信息，请参阅 [AIR 在 Office 365 中的工作原理](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office)。

### <a name="attack-simulator"></a>攻击模拟器

[攻击模拟器](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) 允许授权用户在组织中运行真实的攻击方案。 提供了几种不同类型的攻击，包括显示名称钓鱼攻击、密码攻击和暴力密码攻击。
