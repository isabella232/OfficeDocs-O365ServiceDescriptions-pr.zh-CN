---
title: Microsoft Defender for Office 365 服务说明
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
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Defender for Office 365 是一种基于云的电子邮件筛选服务，它通过提供强大的零日保护来帮助你的组织抵御未知恶意软件和病毒，并包括实时保护组织免受有害的链接危害的功能。
ms.openlocfilehash: 823527f1ef0fbd0284fb1b703d3c6e9f7dfdad440138b6d724077ad5badb9bca
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/06/2021
ms.locfileid: "54663095"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Microsoft Defender for Office 365 服务说明

Microsoft Defender for Office 365 是一种基于云的电子邮件筛选服务，可帮助保护你的组织免受电子邮件和协作工具的高级威胁，如网络钓鱼、商业电子邮件入侵和恶意软件攻击。 Defender for Office 365还提供调查、搜寻和修正功能，以帮助安全团队高效地识别、确定威胁优先级、调查和响应威胁。

以下是你可以将 Defender 用于邮件保护Office 365的主要方法：

- 在仅Office 365筛选的 Defender 方案中，Office 365 Defender 为本地 Exchange Server 环境或其他任何本地 SMTP 电子邮件解决方案提供基于云的电子邮件保护。

- 可以Office 365 Defender for Exchange Online云托管的邮箱。 若要了解有关服务Exchange Online，请参阅Exchange Online[服务说明](exchange-online-service-description/exchange-online-service-description.md)。

- 在混合部署中，可以将 Defender for Office 365 配置为在将本地邮箱和云邮箱与 Exchange Online Protection 混合用于入站电子邮件筛选时保护邮件环境和控制邮件路由。

## <a name="available-plans"></a>可用计划

有关为 Microsoft Defender for Office 365 启用订阅的详细计划信息，请参阅[完整的订阅比较表](https://go.microsoft.com/fwlink/?linkid=2139145)。

## <a name="feature-availability"></a>功能可用性

下表列出了跨计划提供的主要 Microsoft Defender Office 365功能。 某些注意事项适用。 有关详细信息，请参阅脚注。 此表可能发生更改，恕不另行通知。 有关跨计划更新的 Microsoft Defender Office 365的完整列表，请参阅 Microsoft Defender for Office 365 [Features 服务说明](microsoft-defender-for-office-365-features.md)。

| 功能 | Defender for Office 365 计划 1 | Defender for Office 365 计划 2 | Microsoft 365 E5/A5 安全 |
|---------|--------------------------------|--------------------------------|--------------------------------|
| *配置、保护和检测* | | | |
| 预设安全策略和配置分析器 | 是 | 是 | 是 |
| [安全附件](microsoft-defender-for-office-365-features.md#safe-attachments) | 是 | 是 | 是 |
| 保险箱附件Teams | 是 | 是 | 是 |
| [安全链接](microsoft-defender-for-office-365-features.md#safe-links) | 是 | 是 | 是 |
| [安全文档](microsoft-defender-for-office-365-features.md#safe-documents) | 否 | 否 | 是 |
| Teams 中安全链接 | 是 | 是 | 是 |
| 报告邮件Add-In | 是 | 是 | 是 |
| [保护SharePoint、OneDrive和Microsoft Teams](microsoft-defender-for-office-365-features.md#protection-for-sharepoint-onedrive-and-microsoft-teams) | 是 | 是 | 是 |
| [防网络钓鱼策略](microsoft-defender-for-office-365-features.md#anti-phishing-policies) | 是 | 是 | 是 |
| [实时报告](microsoft-defender-for-office-365-features.md#real-time-reports) | 是 | 是 | 是 |
| 内部邮件的高级保护 | 是 | 是 | 是 |
| *自动化、调查、修正和教育* | | | |
| [威胁跟踪器](microsoft-defender-for-office-365-features.md#threat-trackers) | 否 | 是 | 是 |
| 市场活动视图 | 否 | 是 | 是 |
| 威胁调查 (高级威胁调查)  | [实时检测](microsoft-defender-for-office-365-features.md#real-time-detections) | [资源管理器](microsoft-defender-for-office-365-features.md#threat-explorer) | [资源管理器](microsoft-defender-for-office-365-features.md#threat-explorer) |
| [自动调查和&响应](microsoft-defender-for-office-365-features.md#automated-investigation--response) | 否 | 是 | 是 |
| [攻击模拟培训](microsoft-defender-for-office-365-features.md#attack-simulation-training) | 否 | 是 | 是 |
| *与 [Microsoft 365 Defender](/microsoft-365/security/defender/microsoft-365-defender)* | 否 | 是 | 是 |

> [!NOTE]
> Microsoft Defender for Office 365 是 Microsoft Defender Microsoft 365 Defender。 有关使用自动跨域安全与Microsoft 365 Defender，请参阅Microsoft 365 Defender[要求](/microsoft-365/security/mtp/prerequisites)。

## <a name="learn-more"></a>了解详细信息

有关 Microsoft Defender for Office 365，请查看以下资源：

- [Microsoft Docs Office 365 Microsoft Defender for Office 365](/microsoft-365/security/office-365-security/defender-for-office-365)
- [Microsoft Defender for Office 365 网站](https://www.microsoft.com/security/business/threat-protection/office-365-defender)
- [Microsoft Defender for Office 365 博客](https://techcommunity.microsoft.com/t5/microsoft-defender-for-office/bg-p/MicrosoftDefenderforOffice365Blog)
- [Microsoft Defender for Office 365 论坛](https://techcommunity.microsoft.com/t5/microsoft-defender-for-office/bd-p/MicrosoftDefenderforOffice365)

### <a name="licensing-terms"></a>许可条款

有关通过 Microsoft 商业批量许可计划购买的产品和服务的许可条款和条件，请参阅[产品条款网站](https://www.microsoft.com/licensing/terms/)。

### <a name="messaging"></a>消息传递

若要及时了解即将进行的更改，包括新功能和已更改的功能、计划的维护或其他重要通知，请访问消息中心。 有关详细信息，请参阅[消息中心](/microsoft-365/admin/manage/message-center)。

### <a name="accessibility"></a>辅助功能

Microsoft 始终致力于确保数据的安全性以及服务的[辅助功能](https://www.microsoft.com/trust-center/compliance/accessibility)。 有关详细信息，请参阅 [Microsoft 信任中心](https://www.microsoft.com/trust-center)和 [Office 辅助功能中心](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)。
