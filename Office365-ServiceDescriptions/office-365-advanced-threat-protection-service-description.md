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
description: Microsoft Office 365 高级威胁防护（ATP）是一项基于云的电子邮件筛选服务，通过提供强健的零天保护来帮助您的组织抵御未知恶意软件和病毒，并包括实时保护组织免受有害链接的功能。
ms.openlocfilehash: edcf7b7207be27e406f9c6876c1d7d50d3d12dd5
ms.sourcegitcommit: 0ed2137e41e29de9afcaefbff7583da8cfcd55d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/16/2020
ms.locfileid: "43529215"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Office 365 高级威胁防护服务说明

Microsoft Office 365 高级威胁防护（ATP）是一项基于云的电子邮件筛选服务，通过提供强健的零天保护来帮助您的组织抵御未知恶意软件和病毒，并包括实时保护组织免受有害链接的功能。 ATP 具有丰富的报告功能和 URL 跟踪功能，可让管理员了解组织中发生的攻击种类。

以下是您可以使用 ATP 进行邮件保护的主要方式：

- 在 Office 365 ATP 仅筛选方案中，ATP 为本地 Exchange Server 环境或任何其他本地 SMTP 电子邮件解决方案提供基于云的电子邮件保护。

- 可以启用 Office 365 ATP 来保护 Exchange Online 云托管的邮箱。 若要了解有关 Exchange Online 的详细信息，请参阅[Exchange online 服务说明](exchange-online-service-description/exchange-online-service-description.md)。

- 在混合部署中，如果您将本地和云邮箱与入站电子邮件筛选的 Exchange Online 保护结合在一起，则可以将 ATP 配置为保护您的邮件环境并控制邮件路由。

## <a name="office-365-advanced-threat-protection-atp-availability"></a>Office 365 高级威胁防护（ATP）可用性

ATP 包含在 Office 365 企业版 E5、Office 365 教育版 A5 和 Microsoft 365 商业版中。

可以将 ATP 添加到以下 Exchange 和 Office 365 订阅计划中：

- Exchange Online 计划 1

- Exchange Online 计划 2

- Exchange Online Kiosk

- Exchange Online Protection

- Office 365 商业协作版

-  Office 365 商业高级版

- Office 365 企业版 E1

- Office 365 企业版 E3

- Office 365 企业版 F3

- Office 365 A1

- Office 365 A3

若要购买 Office 365 高级威胁防护，请参阅[office 365 高级威胁防护](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)。

若要跨计划比较功能，请参阅[比较 Office 365 For Business 计划](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409)和[发现适合你的 Microsoft 365 企业解决方案](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans)。

## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Office 365 高级威胁防护（ATP）的新增功能

我们正在继续向 Office 365 ATP 添加新功能。 若要了解有关即将 ATP （或常规 Microsoft 365）的新功能的详细信息，请参阅以下资源：

- [Microsoft 365 路线图](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Office 365 ATP 的新增功能](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Office 365 高级威胁防护（ATP）的要求

ATP 可以与任何 SMTP 邮件传输代理（如 Microsoft Exchange Server）一起使用。 若要了解 ATP 支持的操作系统、Web 浏览器和语言，请参阅 [Exchange Online Protection 中的 Exchange 管理中心](https://go.microsoft.com/fwlink/p/?LinkId=282381)的"支持的浏览器"和"支持的语言"部分。

## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>跨高级威胁防护（ATP）计划的功能可用性

下面列出了每个功能。当提到 Exchange Online 时，通常指的是 Office 365 企业版服务系列。

|**功能**|**ATP 计划1**<br>（以前的 ATP 独立）|**ATP 计划2**<br>（以前称为威胁智能 <br>独立主机| Office 365 企业版 E5|
|:-----|:-----|:-----|:-----|
|*配置、保护和检测*|
|[安全附件](#safe-attachments)|是|是|是|
|团队中的安全附件|是|是|是|
|[安全链接](#safe-links)|是|是|是|
|Teams 中安全链接|是|是|是|
|[SharePoint、OneDrive 和 Microsoft 团队的 ATP](#atp-for-sharepoint-onedrive-and-microsoft-teams)|是|是|是|
|[防钓鱼策略](#anti-phishing-policies)|是|是|是|
|[实时报告](#real-time-reports)|是|是|是|
|*自动化、调查、修正和教育*|
|[威胁跟踪器](#threat-trackers)|否|可访问|是|
|威胁调查（高级威胁调查）|[实时检测](#real-time-detections)|[Explorer](#explorer)|[Explorer](#explorer)|
|[自动化事件响应](#automated-incident-response)|否|可访问|是|
|[攻击模拟器](#attack-simulator)|否|可访问|是|

> [!TIP]
> 想要一个可下载的 Office 365 ATP 计划1与计划2之间的差异列表吗？ [获取 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。 

## <a name="advanced-threat-protection-atp-capabilities"></a>高级威胁防护（ATP）功能

### <a name="safe-attachments"></a>安全附件

[ATP 安全附件](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments)针对未知恶意软件和病毒提供保护，并提供为期零天的保护，以保护您的邮件系统。 所有不带有已知的病毒/恶意软件签名的邮件和附件都被路由到一个特殊的环境中，ATP 将在其中使用多种机器学习和分析技术来检测恶意企图。 如果没有检测到可疑的活动，会发布邮件并传递到邮箱中。

> [!NOTE]
> ATP 安全附件扫描发生在 Office 365 数据所在的同一个区域中。 有关数据中心地理位置的详细信息，请参阅[您的数据位于何处？](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>安全链接

[ATP 安全链接](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)功能主动保护您的用户免受邮件中或 Office 文档中的恶意 url 的攻击。 每次选择该链接时，都会保持保护，因为在可以访问正确的链接时，会动态阻止恶意链接。

安全链接可用于以下应用程序中的 Url：

- Windows 或 Mac 上的 Office 365 专业增强版

- 适用于 web 的 Office （适用于 web 的 Excel、适用于 web 的 Excel、PowerPoint for web 以及适用于 web 的 OneNote）

- Windows 上的 Word、Excel、PowerPoint 和 Visio，以及 iOS 和 Android 设备上的 Office 应用

- Microsoft Teams 频道和聊天

> [!NOTE]
> 用户必须获得 ATP<sup>\*</sup>许可，必须包含在 Atp 安全链接策略中，并且必须在其设备上登录，才能就地保护。
>
> <sup>\*</sup>对于组织范围的 ATP 许可证（例如，ATP_ENTERPRISE_FACULTY），无需向单个用户分配 ATP 许可证。
>
> 有关 ATP 安全链接保护的详细信息，请参阅[Atp 安全链接如何处理 Office 文档中的 url](https://docs.microsoft.com/microsoft-365/security/office-365-security/how-atp-safe-links-works#how-atp-safe-links-works-with-urls-in-office-documents)。

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>适用于 SharePoint、OneDrive 和 Microsoft Teams 的 ATP

[SharePoint、OneDrive 和 Microsoft 团队的 ATP](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)可帮助检测和阻止在工作组网站和文档库中被标识为恶意的文件。 此外，ATP 安全链接保护现已在 Microsoft 团队频道和聊天中提供。

### <a name="anti-phishing-policies"></a>防钓鱼策略

[ATP 反网络钓鱼](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing)检查传入的邮件，以指示邮件可能是网络钓鱼尝试。 当 ATP 策略（安全附件、安全链接或反网络钓鱼）覆盖了用户时，将通过分析邮件的多个机器学习模型来评估传入的邮件，并根据配置的策略采取相应的操作。

### <a name="real-time-reports"></a>实时报告

Office 365 安全 & 合规性中心中提供的监视功能包括[实时报告和见解](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp)，使您的安全和合规性能够重点关注高优先级问题，如安全攻击或更高的可疑活动。 除了突出显示问题区域之外，智能报告和见解还包括用于查看和浏览数据的建议和链接，同时还采取快速操作。

### <a name="explorer"></a>Explorer

资源管理器（也称为威胁浏览器）是一个实时报告，它允许授权用户识别和分析最新的威胁。 默认情况下，此报告显示过去7天的数据;但是，可以对视图进行修改，以显示过去30天的数据。

资源管理器包含视图，如恶意软件（电子邮件和内容）、提交、网络钓鱼和所有电子邮件。 若要查看浏览器与实时检测的比较情况，请[下载此 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。

有关浏览器（在 Office 365 高级威胁防护计划2中）和实时检测（在 Office 365 高级威胁防护计划1中）的详细信息，请参阅[威胁 Explorer （和实时检测）](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)。

### <a name="real-time-detections"></a>实时检测

实时检测是一份实时报告，可让授权用户识别和分析最新的威胁。 与资源管理器类似，默认情况下，此报告显示过去7天的数据。

实时检测包含视图，如恶意软件（电子邮件和内容）、提交和网络钓鱼。 若要查看实时检测与资源管理器的比较情况，请[下载此 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。

有关浏览器（在 Office 365 高级威胁防护计划2中）和实时检测（在 Office 365 高级威胁防护计划1中）的详细信息，请参阅[威胁 Explorer （和实时检测）](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)。

### <a name="threat-trackers"></a>威胁跟踪器

[威胁跟踪](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers)程序是信息小组件和视图，为授权用户提供了可能会影响您的组织的 cybersecurity 问题的智能。

### <a name="automated-incident-response"></a>自动化事件响应

Office 365 ATP 计划2中提供的[自动事件响应](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air)（空中）功能使您能够运行自动化的调查过程，以应对目前存在的已知威胁。 通过自动执行某些调查任务，安全操作团队可以更高效地运行。 安全操作团队批准执行更正操作，如删除恶意电子邮件。 若要了解详细信息，请参阅[Office 365 中的 AIR 的工作原理](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office)。

### <a name="attack-simulator"></a>攻击模拟器

[攻击模拟器](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator)允许授权用户在您的组织中运行实际的攻击方案。 有几种不同类型的攻击可供使用，其中包括显示名称 spear 网络钓鱼攻击、密码喷涂攻击和强力密码攻击。
