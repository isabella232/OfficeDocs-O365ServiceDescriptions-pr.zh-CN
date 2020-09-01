---
title: Office 365 高级威胁防护服务说明
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
description: Microsoft Office 365 高级威胁防护 (ATP) 是一种基于云的电子邮件筛选服务，通过提供强健的零天保护来帮助您的组织抵御未知恶意软件和病毒，并包括实时保护组织免受有害链接的功能。
ms.openlocfilehash: 0e9c7e76cabd9f39a13c16689a4255732617b09d
ms.sourcegitcommit: 0f2d249dfc93432e17344f70b8317a455204f018
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/01/2020
ms.locfileid: "47318939"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Office 365 高级威胁防护服务说明

Microsoft Office 365 高级威胁防护 (ATP) 是一种基于云的电子邮件筛选服务，通过提供强健的零天保护来帮助您的组织抵御未知恶意软件和病毒，并包括实时保护组织免受有害链接的功能。 ATP 具有丰富的报告功能和 URL 跟踪功能，可让管理员了解组织中发生的攻击种类。

以下是你可以使用 ATP 进行邮件保护的主要方式：

- 在 Office 365 ATP 仅筛选方案中，ATP 将为你的本地 Exchange Server 环境或任何其他本地 SMTP 电子邮件解决方案提供基于云的电子邮件保护。

- 可以启用 Office 365 ATP 来保护 Exchange Online 的云托管邮箱。 若要了解有关 Exchange Online 的详细信息，请参阅 [Exchange online 服务说明](exchange-online-service-description/exchange-online-service-description.md)。

- 在混合部署中，当邮箱中混合了本地邮箱和云邮箱并且使用 Exchange Online Protection 筛选入站电子邮件时，可配置 ATP 以保护邮件环境和控制邮件路由。

## <a name="office-365-advanced-threat-protection-atp-availability"></a>Office 365 高级威胁防护 (ATP) 可用性

Office 365 E5、Office 365 A5 和 Microsoft 365 E5 中包含 Office 365 ATP 计划 2。 Office 365 ATP 计划 1 包含在 Microsoft 365 商业高级版中。

您可以向以下 Exchange 和 Microsoft 365 订阅计划中添加 ATP：

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

若要购买 Office 365 高级威胁防护，请参阅 [office 365 高级威胁防护](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)。

若要跨计划比较功能，请参阅 [强大的工具来支持您的企业](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) 并 [使用 Microsoft 365 转换企业](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans)。

## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Office 365 高级威胁防护中的新增功能 (ATP) 

我们正在继续向 Office 365 ATP 添加新功能。 若要了解有关即将 ATP (或 Microsoft 365 常规) 的新功能的详细信息，请参阅以下资源：

- [Microsoft 365 路线图](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Office 365 ATP 的新增功能](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Office 365 高级威胁防护的要求 (ATP) 

ATP 可以与任何 SMTP 邮件传输代理（如 Microsoft Exchange Server）一起使用。 有关 ATP 支持的操作系统、web 浏览器和语言的信息，请参阅 exchange [Online Protection 中 exchange 管理中心](https://go.microsoft.com/fwlink/p/?LinkId=282381)的 "支持的浏览器" 和 "支持的语言" 部分。

## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>跨高级威胁防护的功能可用性 (ATP) 计划

下面列出了每个功能。当提到 Exchange Online 时，通常指的是 Office 365 企业版服务系列。

|**功能**|**ATP 计划1**<br> (以前的 ATP 独立) |**ATP 计划2**<br> (以前的威胁情报 <br>独立) | Microsoft 365 E5/E5 安全|
|:-----|:-----|:-----|:-----|
|*配置、保护和检测*|
|[安全附件](#safe-attachments)|是|是|是|
|团队中的安全附件|是|是|是|
|[安全链接](#safe-links)|是|是|是|
|[安全文档](#safe-documents)|否|否|是|
|Teams 中安全链接|是|是|是|
|[SharePoint、OneDrive 和 Microsoft 团队的 ATP](#atp-for-sharepoint-onedrive-and-microsoft-teams)|是|是|是|
|[防钓鱼策略](#anti-phishing-policies)|是|是|是|
|[实时报告](#real-time-reports)|是|是|是|
|*自动化、调查、修正和教育*|
|[威胁跟踪器](#threat-trackers)|否|是|是|
|威胁调查 (高级威胁调查) |[实时检测](#real-time-detections)|[资源管理器](#explorer)|[资源管理器](#explorer)|
|[自动化事件响应](#automated-incident-response)|否|是|是|
|[攻击模拟器](#attack-simulator)|否|是|是|

> [!TIP]
> 想要一个可下载的 Office 365 ATP 计划1与计划2之间的差异列表吗？ [获取 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。 

## <a name="advanced-threat-protection-atp-capabilities"></a>高级威胁防护 (ATP) 功能

### <a name="safe-attachments"></a>安全附件

[ATP 安全附件](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) 针对未知恶意软件和病毒提供保护，并提供为期零天的保护，以保护您的邮件系统。 所有不带有已知的病毒/恶意软件签名的邮件和附件都被路由到一个特殊的环境中，ATP 将在其中使用多种机器学习和分析技术来检测恶意企图。 如果没有检测到可疑的活动，会发布邮件并传递到邮箱中。

> [!NOTE]
> ATP 安全附件扫描发生在 Office 365 数据所在的同一个区域中。 有关数据中心地理位置的详细信息，请参阅 [您的数据位于何处？](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>安全链接

[ATP 安全链接](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)功能主动保护您的用户免受邮件中或 Office 文档中的恶意 url 的攻击。 每次选择链接时，将继续提供保护，因为会在访问良好的链接时动态地阻挡恶意链接。

安全链接可用于以下应用程序中的 Url：

- 适用于 Windows 或 Mac 的 Microsoft 365 企业版应用程序

- Office for web (Word for web、适用于 web 的 Excel、PowerPoint for web 以及适用于 web 的 OneNote) 

- Windows 上的 Word、Excel、PowerPoint 和 Visio，以及 iOS 和 Android 设备上的 Office 应用

- Microsoft Teams 频道和聊天

> [!NOTE]
> 用户必须获得 ATP 许可 <sup>\*</sup> ，必须包含在 Atp 安全链接策略中，并且必须在其设备上登录，才能就地保护。
>
> <sup>\*</sup> 对于组织范围的 ATP 许可证 (例如，ATP_ENTERPRISE_FACULTY) ，无需向单个用户分配 ATP 许可证。
>
> 有关 ATP 安全链接保护的详细信息，请参阅 [Atp 安全链接如何处理 Office 文档中的 url](https://docs.microsoft.com/microsoft-365/security/office-365-security/how-atp-safe-links-works#how-atp-safe-links-works-with-urls-in-office-documents)。

### <a name="safe-documents"></a>安全文档

[ATP 安全文档](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs)功能使用[Microsoft Defender 高级威胁防护](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection)来扫描在[受保护视图](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)中打开的文档和文件。

开始前，有必要了解什么？

- 安全文档现在对 Office 版本 2004 () 或更高版本的用户通常可用！ 此功能在默认情况下处于禁用状态，将需要由安全管理员启用。

- 此功能仅适用于使用 Microsoft 365 E5 或 Microsoft 365 E5 安全许可证的用户 (不包含在 Office 365 ATP 计划) 中。

- Windows 上的 Word、Excel、PowerPoint 和 Visio，以及 iOS 和 Android 设备上的 Office 应用

- Microsoft Teams 频道和聊天

> [!NOTE]
> 用户必须获得 Microsoft 365 E5 或 Microsoft 365 E5 安全性 <sup>\*</sup> ，必须包含在 ATP 安全文档策略中，并且必须在其设备上登录，才能就地保护。
>
> 有关 ATP 安全文档保护的详细信息，请参阅 [Microsoft 365 E5 中的安全文档](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs)。

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>适用于 SharePoint、OneDrive 和 Microsoft Teams 的 ATP

[SharePoint、OneDrive 和 Microsoft 团队的 ATP](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  可帮助检测和阻止在工作组网站和文档库中被标识为恶意的文件。 此外，ATP 安全链接保护现已在 Microsoft 团队频道和聊天中提供。

### <a name="anti-phishing-policies"></a>防钓鱼策略

[ATP 反网络钓鱼](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) 检查传入的邮件，以指示邮件可能是网络钓鱼尝试。 当用户在 ATP 策略（安全附件、安全链接或防钓鱼）涵盖范围内时，将通过多个可分析邮件的机器学习模型来评估传入的邮件，然后根据配置的策略采取相应操作。

### <a name="real-time-reports"></a>实时报告

安全 & 合规性中心中提供的监视功能包括 [实时报告和见解](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) ，使您的安全和合规性能够重点关注高优先级问题，如安全攻击或更高的可疑活动。 除了突出显示问题区域之外，智能报告和见解还包括用于查看和浏览数据的建议和链接，同时还采取快速操作。

### <a name="explorer"></a>资源管理器

资源管理器（也称为威胁资源管理器）是一种实时报告，可让授权用户能够识别和分析最近的威胁。 默认情况下，此报告显示过去 7 天的数据；但是，可以修改视图以显示过去 30 天的数据。

资源管理器包含用于电子邮件和内容) 、提交、网络钓鱼和所有电子邮件的恶意软件 (的视图。 若要查看浏览器与实时检测的比较情况，请 [下载此 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。

有关浏览器 (Office 365 高级威胁防护计划 2) 和实时检测 (在 Office 365 高级威胁防护计划 1) 中的详细信息，请参阅 [威胁资源管理器和实时检测](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)。

### <a name="real-time-detections"></a>实时检测

实时检测是一种实时报告，可让授权用户能够识别和分析最近的威胁。 此报告与资源管理器类似，默认情况下显示过去 7 天的数据。

实时检测包含用于电子邮件和内容) 、提交和网络钓鱼的恶意软件 (的视图。 若要查看实时检测与资源管理器的比较情况，请 [下载此 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。

有关浏览器 (Office 365 高级威胁防护计划 2) 和实时检测 (在 Office 365 高级威胁防护计划 1) 中的详细信息，请参阅 [威胁资源管理器 (和实时检测) ](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)。

### <a name="threat-trackers"></a>威胁跟踪器

[威胁跟踪](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) 程序是信息小组件和视图，为授权用户提供了可能会影响您的组织的 cybersecurity 问题的智能。

### <a name="automated-incident-response"></a>自动化事件响应

Office 365 ATP 计划2中提供的[自动事件响应](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) (空中) 功能使您能够运行自动调查过程，以应对目前存在的已知威胁。 通过自动执行某些调查任务，安全操作团队可以更高效地运行。 安全操作团队批准执行更正操作，如删除恶意电子邮件。 若要了解详细信息，请参阅 [Office 365 中的 AIR 的工作原理](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office)。

### <a name="attack-simulator"></a>攻击模拟器

[攻击模拟器](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) 允许授权用户在您的组织中运行实际的攻击方案。 有几种不同类型的攻击可供使用，其中包括显示名称 spear 网络钓鱼攻击、密码喷涂攻击和强力密码攻击。
