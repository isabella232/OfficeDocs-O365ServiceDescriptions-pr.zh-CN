---
title: Microsoft Defender for Office 365 功能服务说明
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: ''
description: 了解 Microsoft Defender for Office 365 中提供Office 365。
ms.openlocfilehash: a4f7fe00162dc15d7f01be831842066ef448546ad36197fb0551d85dbfba73ef
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/06/2021
ms.locfileid: "54663045"
---
# <a name="microsoft-defender-for-office-365-features-service-description"></a>Microsoft Defender for Office 365 功能服务说明

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Microsoft Defender for Office 365

我们将继续向 Defender for Office 365。 若要了解有关 Defender for Office 365 (或 Microsoft 365 的新功能) ，请参阅以下资源：

- [Microsoft 365 路线图](https://www.microsoft.com/microsoft-365/roadmap)

- [Microsoft Defender for Office 365 中的新增功能 - Office 365 |Microsoft Docs](/microsoft-365/security/office-365-security/whats-new-in-defender-for-office-365)

## <a name="defender-for-office-365-capabilities"></a>Defender for Office 365 功能

### <a name="safe-attachments"></a>安全附件

[保险箱附件](/microsoft-365/security/office-365-security/atp-safe-attachments)可抵御未知恶意软件和病毒的攻击，并提供零日保护来保护邮件系统。 所有没有已知病毒/恶意软件签名的邮件和附件将路由到 Defender for Office 365 使用各种机器学习和分析技术检测恶意意图的特殊环境。 如果没有检测到可疑的活动，会发布邮件并传递到邮箱中。

> [!NOTE]
> 保险箱附件扫描发生在数据所在的同一Office 365区域。 有关数据中心地理位置的信息，请参阅 [数据所在的位置？](/microsoft-365/enterprise/o365-data-locations)

### <a name="safe-links"></a>安全链接

["保险箱链接](/microsoft-365/security/office-365-security/atp-safe-links)"功能可主动保护用户免受邮件或电子邮件文档中的恶意OFFICE攻击。 每次选择链接时，将继续提供保护，因为会在访问良好的链接时动态地阻挡恶意链接。

安全链接可用于以下应用中的 URL：

- Microsoft 365 企业应用版或 Mac Windows上

- Office web 版（Word 网页版、Excel 网页版、PowerPoint 网页版、OneNote 网页版）

- Word、Excel 和 PowerPoint Windows

- Microsoft Teams 频道和聊天

> [!NOTE]
> 用户必须获得 Defender for Office 365 的许可，必须包含在 保险箱 链接策略中，并且必须登录到其设备，以便保护 <sup>\*</sup> 就位。
>
> <sup>\*</sup>对于组织范围内的 Defender Office 365许可证 (例如，ATP_ENTERPRISE_FACULTY) ，你无需为单个用户分配适用于 Office 365 的 Defender。
>
> 有关链接保护保险箱，请参阅 microsoft Defender[保险箱中的链接Office 365。](/microsoft-365/security/office-365-security/atp-safe-links)

### <a name="safe-documents"></a>安全文档

["保险箱文档](/microsoft-365/security/office-365-security/safe-docs)"功能使用[Microsoft Defender for Endpoint](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection)扫描在受保护视图中[打开的文档和文件](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)。

开始前，有必要了解什么？

- 保险箱现在，具有 2004 Office 12730.x (12730.x) 用户可以使用文档！ 默认情况下，此功能已关闭，并且需要由安全管理员启用。

- 此功能仅适用于拥有 Microsoft 365 E5 或 Microsoft 365 E5 安全性 许可证 (未包含在 Defender for Office 365 计划) 。

- Word、Excel 和 PowerPoint Windows

- Microsoft Teams 频道和聊天

> [!NOTE]
> 用户必须获得 Microsoft 365 E5 或 Microsoft 365 E5 安全性 的许可，并且必须包含在 保险箱 文档策略中，并且必须登录其设备，保护 <sup>\*</sup> 就位。
>
> 有关文档保护保险箱，请参阅 保险箱 Documents [in Microsoft 365 E5。](/microsoft-365/security/office-365-security/safe-docs)

### <a name="protection-for-sharepoint-onedrive-and-microsoft-teams"></a>保护SharePoint、OneDrive和Microsoft Teams

[对 SharePoint、OneDrive](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)和 Microsoft Teams 的保护可帮助检测和阻止在团队网站和文档库中被标识为恶意的文件。 此外，保险箱频道和聊天中现在Microsoft Teams链接保护。

### <a name="anti-phishing-policies"></a>防钓鱼策略

[防钓鱼功能](/microsoft-365/security/office-365-security/atp-anti-phishing) 检查传入邮件，以指示邮件可能是网络钓鱼尝试。 当用户被 Office 365 (保险箱 策略（附件、保险箱 链接或防钓鱼) ）的 Defender 覆盖时，传入邮件由分析邮件的多个机器学习模型进行评估，并基于配置的策略执行相应的操作。

### <a name="real-time-reports"></a>实时报告

安全与合规中心提供的监视[](https://protection.office.com)功能&实时报告和见解，让安全[](/microsoft-365/security/office-365-security/view-reports-for-atp)与合规管理员专注于高优先级问题，如安全攻击或可疑活动增加。 除了突出显示问题区域外，智能报告和见解还包括用于查看和浏览数据的建议和链接，以及快速操作。

### <a name="threat-explorer"></a>威胁资源管理器

威胁 (浏览器也称为资源管理器) 是一个实时报告，可让授权用户识别和分析最近的威胁。 默认情况下，此报告显示过去七天的数据;但是，可以修改视图以显示过去 30 天的数据。

资源管理器包含诸如电子邮件和内容 (、提交、网络钓鱼) 所有电子邮件的恶意软件策略等视图。 若要了解资源管理器与实时检测的比较， [请下载此 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。

有关 Microsoft Defender for Office 365 计划 2) 中的资源管理器 (以及 Microsoft Defender for Office 365 计划 1) 中的实时检测 (，请参阅威胁资源管理器和实时[检测。](/microsoft-365/security/office-365-security/threat-explorer)

### <a name="real-time-detections"></a>实时检测

实时检测是一种实时报告，可让授权用户能够识别和分析最近的威胁。 与资源管理器类似，默认情况下，此报告显示过去七天的数据。

实时检测包含视图，如电子邮件 (、提交和网络钓鱼) 恶意软件。 若要了解实时检测与资源管理器的对比， [请下载此 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。

有关 Microsoft Defender for Office 365 计划 2) 中的资源管理器 (以及 Microsoft Defender for Office 365 计划 1) 中的实时检测 (，请参阅威胁资源管理器和实时[检测。](/microsoft-365/security/office-365-security/threat-explorer)

### <a name="threat-trackers"></a>威胁跟踪器

[威胁跟踪](/microsoft-365/security/office-365-security/threat-trackers) 器是信息小组件和视图，可为授权用户提供可能会影响组织的网络安全问题智能。

### <a name="automated-investigation--response"></a>自动调查和&响应

Office 365 自动调查[&](/microsoft-365/security/office-365-security/office-365-air) () 计划 2 中提供的 AIR) 功能，让你可以运行自动调查流程，以响应当今存在的已知威胁。 通过自动执行某些调查任务，安全运营团队可以更高效地操作。 安全运营团队批准后，将执行修正操作，如删除恶意电子邮件。 若要了解更多信息，请参阅[AIR 在 Office 365 中Office 365。](/microsoft-365/security/office-365-security/automated-investigation-response-office)

### <a name="attack-simulation-training"></a>攻击模拟培训

[攻击模拟培训](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) 是一种智能社交风险管理工具，可自动创建和管理网络钓鱼模拟。 模拟通过使用真实的网络钓鱼欺诈和超目标培训来更改员工行为，帮助客户检测、确定钓鱼风险优先级并修正这些风险。

- 攻击模拟培训现已在 WW 中提供，GCC (将于 GCC年 6 月 21 日) 。
- 若要详细了解如何开始使用，请参阅使用 [攻击模拟培训入门](/microsoft-365/security/office-365-security/attack-simulation-training-get-started)。
- 应用去武器化的实际网络钓鱼有效负载的各种攻击技术可用于复制实际攻击者行为，使网络钓鱼模拟相关。
- 此服务适用于拥有 Microsoft 365 E5、Office 365 E5 或 Microsoft Defender for Office 365 计划[2](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2)许可证的组织。 一部分功能作为试用版提供给 E3 客户。
- 若要了解更多信息并尝试模拟，请参阅 [模拟网络钓鱼攻击](/microsoft-365/security/office-365-security/attack-simulation-training)。