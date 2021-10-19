---
title: Microsoft 365安全与合规&指南
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.reviewer: v-trscho
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: 本文提供有关实现Microsoft 365指南，以帮助避免由于未授权访问而潜在的服务中断。
ms.openlocfilehash: 23347668f4a065a55e0a556fe7b18aab75d69000
ms.sourcegitcommit: dd0ac3657e87c9149ea92318dc8ed0a1e94905e0
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/19/2021
ms.locfileid: "60478050"
---
# <a name="microsoft-365-guidance-for-security-amp-compliance"></a>Microsoft 365 &amp; 合规性指南

出于本文的目的，租户级服务是一种在线服务，当为租户 (独立版或 Office 365 或 Microsoft 365 计划) 的任何用户购买时，会为租户中的所有用户部分或完整激活该服务。 &mdash; &mdash; 尽管某些未授权的用户可能从技术上能够访问该服务，但任何打算从该服务受益的用户都需要许可证。

> [!NOTE]
> 某些租户服务当前无法将权益限制到特定用户。 应努力将服务权益限制为许可用户。 这可帮助避免目标功能可用后组织的潜在服务中断。

若要查看授权用户从合规性功能Microsoft 365的选项，请下载"比较Microsoft 365[表](https://go.microsoft.com/fwlink/?linkid=2139145)。

## <a name="advanced-audit"></a>高级审核

Microsoft 365 中的高级审核为用户和管理员活动提供了一年审核日志保留期，并提供了创建自定义 审核日志 保留策略来管理其他 审核日志 服务 Microsoft 365 保留的能力。 它还提供对关键事件的访问权限，以进行调查，以及访问 Office 365 活动 API。 有关详细信息，请参阅高级审核[Microsoft 365。](/microsoft-365/compliance/advanced-audit)

您还可以使用附加 SKU 启用保留期 10 年。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中获益？

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合规性、Microsoft 365 F5 安全 & 合规性以及 Microsoft 365 E5/A5/G5 电子数据展示和审核的许可用户可以从高级审核中获益。

具有高级审核和 10 年审核日志保留加载项的许可用户可以从 10 年的审核日志保留中获益。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

用户受益于高级审核，因为与 Microsoft 365 服务中的用户活动相关的审核记录最多可保留一年。 此外，还会记录高价值审核事件，例如访问或读取用户邮箱中的项目时。 有关详细信息，请参阅高级审核[Microsoft 365。](/microsoft-365/compliance/advanced-audit)

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，为从服务受益的所有用户启用租户级高级审核，并自动为 Azure Active Directory、Exchange 和 SharePoint 中具有相应许可证) 的用户执行的活动 (保留一年审核日志。 此外，组织可以使用审核日志策略来管理由其他服务中的活动生成的审核记录的Microsoft 365期。 10 年审核日志保留功能也使用相同的保留策略启用。 有关详细信息，请参阅[管理审核日志保留策略](/microsoft-365/compliance/audit-log-retention-policies)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

一年保留审核日志和重要事件的审核仅适用于具有相应许可证的用户。 此外，管理员可以使用审核日志策略来为特定用户的审核日志指定较短的保留期。

审核日志保留 10 年仅适用于具有相应附加许可证的用户。 从 2021 年初开始，需要加载项 SKU。

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure Active Directory标识保护是 Azure Active Directory Premium P2 计划的一项功能，可让你检测影响组织标识的潜在漏洞，配置对检测到的与组织标识相关的可疑操作自动响应，并调查可疑事件，并采取适当的措施解决这些问题。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

SecOps 分析员和安全专业人员从具有基于机器学习算法的已标记用户和风险事件的合并视图中获益。 最终用户受益于通过基于风险的条件访问提供的自动保护，以及通过对漏洞采取行动所提供的改进的安全性。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

- Azure Active Directory计划 1：Microsoft 365 E3/A3/G3/F1/F3、Enterprise Mobility & Security E3 和 Microsoft 365 商业高级版
- Azure Active Directory计划 2：Microsoft 365 E5/A5/G5、Enterprise Mobility & Security E5、Microsoft 365 E5/F5 Security and Microsoft 365 F5 Security & Compliance

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，Azure AD租户内的所有用户在租户级别启用 Identity Protection 功能。 有关标识保护Azure AD，请参阅[什么是标识保护？](/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

管理员可以通过分配Azure AD密码重置级别并仅允许许可用户访问的风险策略，来界定对 Identity Protection 的访问权限。 有关如何确定 Identity Protection 部署Azure AD的说明，请参阅[如何配置和启用风险策略](/azure/active-directory/identity-protection/howto-sign-in-risk-policy)。

## <a name="azure-active-directory-identity-governance"></a>Azure Active Directory标识治理

Azure Active Directory通过身份管理，您可以平衡组织对安全性和员工工作效率的需要与正确的流程和可见性。 它使用权利管理、访问评审、特权标识管理和使用条款策略，以确保合适的人员能够正确访问适当的资源。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

Azure Active DirectoryIdentity Governance 通过更轻松地请求访问一个访问包中的应用、组Microsoft Teams用户工作效率。 用户还可以配置为审批者，无需管理员参与。 对于访问评审，用户可以使用智能建议查看组的成员身份，以便定期采取措施。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

企业移动性 + 安全性E5/A5、Microsoft 365 E5/A5、Microsoft 365 E5/A5/F5 安全与 F5 安全 & 合规性和 Azure Active Directory Premium 计划 2 为用户提供了从 Azure Active Directory 身份管理中获益的权利。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

Azure AD标识治理功能在租户级别启用，但按用户实现。 有关标识Azure AD的信息，请参阅[什么是标识Azure AD？](/azure/active-directory/governance/identity-governance-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

管理员仅Azure AD访问包、访问评审或特权标识管理，来界定对 Identity Governance 的访问权限。 有关如何确定 Identity Governance 部署Azure AD的说明，请参阅：

- [Azure AD权利管理许可证要求](/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Azure AD访问评审许可证要求](/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [使用证书的许可证Privileged Identity Management](/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="communication-compliance"></a>通信合规性

组织中通信合规性Microsoft 365通过帮助您检测、捕获和采取针对组织中不当邮件的修正操作，帮助最大程度地降低通信风险。 可以定义捕获组织中内部和外部电子邮件、Microsoft Teams或第三方通信的特定策略。 审阅者可以采取适当的修正措施，以确保他们符合组织的邮件标准。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

合规性专家通过让组织通信受通信合规性策略监控，从服务中获益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合规性、Microsoft 365 F5 安全 & 合规性和 Microsoft 365 E5/A5/G5 内部风险管理为用户提供了从通信合规性中获益的权利。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

管理员和合规性专家在安全中心内创建Microsoft 365 合规中心。 这些策略定义哪些通信和用户在组织中需要审阅，定义通信必须满足的自定义条件，并指定应执行审阅的用户。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

管理员选择要包括在通信合规性策略中的特定用户或组。 选择组时，他们还可以选择要从通信合规性策略中排除的组中特定用户。 有关通信合规性策略详细信息，请参阅 Microsoft 365[中的通信合规性入门](/microsoft-365/compliance/communication-compliance-configure)。

## <a name="compliance-manager"></a>合规性管理器

[Microsoft 合规性管理器](https://compliance.microsoft.com/compliancemanager)是 microsoft[](/microsoft-365/compliance/microsoft-365-compliance-center)合规性管理器Microsoft 365 合规中心一项功能，可帮助您更轻松、更方便地管理组织的合规性要求。 合规性管理器可以帮助你完成合规性之旅，从清查数据保护风险到管理实现控制的复杂性、及时了解最新法规和认证、以及向审核员报告。

合规性管理器通过提供：

- 针对常见行业和区域标准和法规的预建或自定义评估，满足独特的合规性要求。
- 工作流功能通过单一工具帮助你有效完成风险评估。
- 有关建议改进操作的详细分步指南，可帮助您遵守与组织最相关的标准和法规。 对于由 Microsoft 管理的操作，你将看到实现详细信息和审核结果。
- 基于风险的合规性分数，通过衡量完成改进操作的进度，帮助你了解合规性状态。

### <a name="who-can-access-compliance-manager"></a>Who合规性管理器？

合规性管理器适用于具有 Office 365 和 Microsoft 365 许可证的组织，以及美国 政府社区云 (GCC) 、GCC High 和国防部 (DoD) 客户。 评估可用性和管理功能取决于您的许可协议。

### <a name="what-are-premium-assessments"></a>什么是高级评估？

高级版评估是合规性管理器的附加价值，有助于：

- 将复杂的法规要求转换为特定控制措施
- 建议改进操作
- 根据法规提供可量化的合规性度量

合规性管理器具有 300 多个高级评估，客户可以使用这些评估评估其是否符合各种全球、区域和行业法规和标准。

任何具有订阅（包括Microsoft Exchange Online）的客户可以购买合规性管理器高级评估。

### <a name="which-premium-assessments-are-available"></a>哪些高级评估可用？

下面是高级 [评估列表](/microsoft-365/compliance/compliance-manager-templates-list#premium-templates)。

### <a name="which-assessments-are-included-by-default-free-of-cost"></a>默认情况下，哪些评估 (免费？) ？

某些评估包含在合规性管理器和客户许可证类型中。 有关详细信息，请参阅下表：

| 许可证类型 | 默认情况下 (评估模板)  |
|:-----|:-----|
|<ul><li>Microsoft 365或 Office 365 A1/E1/F1/G1</li><li>Microsoft 365 或 Office 365 A3/E3/F3/G3</li></ul>|<ul><li>数据保护基线</li></ul>|
|<ul><li>Microsoft 365 或 Office 365 A5/E5/G5</li><li>Microsoft 365 A5/E5/F5/G5 合规性</li><li>Microsoft 365 A5/E5/F5/G5 电子数据展示和审核</li><li>Microsoft 365 A5/E5/F5/G5 内部风险管理</li><li>Microsoft 365 A5/E5/F5/G5 信息保护和管理</li></ul>|<ul><li>数据保护基线</li><li>欧盟 GDPR</li><li>NIST 800-53</li><li>ISO 27001</li><li>CMMC 级别 1-5 (仅适用于 G5) </li><li>自定义评估</li></ul>|

### <a name="what-are-custom-assessments"></a>什么是自定义评估？

自定义评估是合规性管理器功能，它提供创建新模板或自定义现有评估模板（包括添加或更新控制措施和改进操作）的功能。

### <a name="who-can-access-custom-assessments"></a>Who能否访问自定义评估？

具有 E5 订阅的客户可以使用自定义评估功能，如下所示：

- Microsoft 365 或 Office 365 A5/E5/G5
- Microsoft 365 A5/E5/F5/G5 合规性
- Microsoft 365 A5/E5/F5/G5 电子数据展示和审核
- Microsoft 365 A5/E5/F5/G5 内部风险管理
- Microsoft 365 A5/E5/F5/G5 信息保护和管理

## <a name="customer-key-for-microsoft-365"></a>客户密钥Microsoft 365

使用客户密钥，可以控制组织的加密密钥，Microsoft 365以使用它们加密 Microsoft 数据中心中的静态数据。 换句话说，客户密钥允许你使用自己的密钥添加属于你的加密层。 客户密钥通过静态数据加密服务为多个Microsoft 365工作负荷Microsoft 365[](/microsoft-365/compliance/customer-key-overview#about-data-encryption-policies)静态数据加密支持。 此外，客户密钥还提供 SharePoint Online 和 OneDrive for Business 数据的加密，以及Exchange Online级别的加密。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

用户可以通过使用由其自己的组织提供的、控制和管理的加密密钥在应用程序层加密静态数据，从客户密钥中获益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合规性、Microsoft 365 F5 安全 & 合规性、Microsoft 365 E5/A5/G5 信息保护和治理以及 Office 365 E5/A5/G5 为用户提供从客户密钥中获益的权利。 若要充分利用客户密钥，还必须订阅 Azure 密钥保管库。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

设置 [客户密钥](/microsoft-365/compliance/customer-key-set-up) 一文介绍了创建和配置所需的 Azure 资源所需的步骤，然后提供了设置客户密钥的步骤。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

Microsoft 365多工作负荷加密支持的静态数据服务是租户级服务。 尽管某些未授权的用户可能从技术上能够访问该服务，但任何打算从该服务受益的用户都需要许可证。 对于Exchange Online级别加密，用户邮箱需要获得授权，以分配数据加密策略。

## <a name="data-connectors"></a>数据连接器

Microsoft 提供可在数据连接器中配置的第三方数据Microsoft 365 合规中心。 有关 Microsoft 提供的数据连接器的列表，请参阅第三方 [数据连接器](/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) 表。 此表还汇总了在 Microsoft 365 中导入和存档数据后可应用于第三方数据的合规性解决方案，以及指向每个连接器的分步说明的链接。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

使用数据连接器在 Microsoft 365 中导入和存档第三方数据的主要好处是，您可以在导入数据后对数据应用各种 Microsoft 365 合规性解决方案。 这有助于确保组织的非 Microsoft 数据符合影响组织的法规和标准。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

以下许可证为用户提供了从数据连接器中获益的权利：

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 信息保护 &amp; 治理
- Microsoft 365 E5/A5/G5/F5 合规性
- Microsoft 365F5 安全&合规性
- Microsoft 365 E5/A5/G5 内部风险管理
- Microsoft 365 E5/A5/G5 电子数据展示和审核
- Office 365 E5/A5/G5

对于 Microsoft 合作伙伴Microsoft 365安全与合规中心内的数据连接器，贵组织需要与合作伙伴建立业务关系，然后才能部署 &amp; 这些连接器。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

连接器使用安全与合规中心和连接器 &amp; 目录进行配置。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

数据连接器服务是租户级别的值。 每位打算从此服务受益的用户都必须获得许可。

## <a name="data-classification-analytics-overview-content-amp-activity-explorer"></a>数据分类分析：内容活动 &amp; 资源管理器概述

数据分类分析功能在Microsoft 365 合规中心可用。 概述显示数字内容的位置以及最常见的敏感信息类型和标签。 内容资源管理器提供敏感数据量和类型的可见性，并允许用户按标签或敏感度类型进行筛选，获取存储敏感数据的位置的详细视图。 活动资源管理器显示与敏感数据和标签相关的活动，例如标签降级或外部共享，这些活动可能会将内容暴露给风险。

活动资源管理器为管理员提供了一个窗格，以便查看与最终用户使用的敏感信息相关的活动。 这些数据包括标签活动、数据丢失防护 (DLP) 日志、自动标记、终结点 DLP 等。

利用内容资源管理器，管理员可以对存储在受支持 Microsoft 365 中的敏感文档编制索引，并标识要存储的敏感信息。 此外，内容资源管理器还可帮助识别使用敏感度标签和保留标签分类的文档。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

信息保护和合规性管理员可以访问服务，以访问这些日志和索引数据，以了解敏感数据存储的位置以及哪些活动与此数据相关以及由最终用户执行。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合规性、Microsoft 365 F5 安全 & 合规性、Microsoft 365 E5/A5/G5 信息保护治理和 Office 365 E5 的许可用户可以从 Microsoft 365 数据分类分析中获益。 &amp;

Microsoft 365 E3/A3/G3 和 Office 365 E3/A3/G3 仅允许用户从内容资源管理器数据聚合中获益。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，在租户级别为租户内的所有用户启用"概述内容和活动资源管理器"功能。 有关为许可用户配置数据分类分析的信息，请参阅：

- **内容资源管理器**[：内容资源管理器入门 - Microsoft 365合规性|Microsoft Docs](/microsoft-365/compliance/data-classification-content-explorer)。
- **活动资源管理器**[：活动资源管理器入门 - Microsoft 365合规性|Microsoft Docs](/microsoft-365/compliance/data-classification-activity-explorer)。
- **数据分类发行说明**：[数据分类发行说明 - Microsoft 365合规性|Microsoft Docs](/microsoft-365/compliance/data-classification-pub-preview-relnotes)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

此功能需要针对在合规性门户中主动使用Microsoft 365范围。

## <a name="data-loss-prevention-for-teams"></a>数据丢失防护Teams

借助通信 DLP Teams，组织可以阻止包含敏感信息（例如财务信息、个人身份信息、运行状况相关信息或其他机密信息）的聊天和频道消息。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中获益？

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5/F5 合规性和 F5 安全&合规性
- Microsoft 365 E5/A5/G5 信息保护和管理
- Office 365 E5/A5/G5

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

发件人通过检查其传出聊天和频道消息中的敏感信息来查看敏感信息，这一点在组织的 DLP 策略中配置。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，Teams消息和频道消息是租户中所有用户 *(* 启用) DLP 功能的位置和工作负载。 有关使用 DLP 策略的信息，请参阅 [数据丢失防护概述](/office365/securitycompliance/data-loss-prevention-policies)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

管理员可以在"数据丢失防护 ("下) 安全与合规中心中的用户、包括用户和已排除用户等工作负载 &amp;   >  **自定义位置**。

## <a name="data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Exchange Online、SharePoint Online 和 OneDrive for Business 的数据丢失防护

借助 Office 365 数据丢失防护 (DLP) for Exchange Online、SharePoint Online 和 OneDrive for Business，组织可以识别、监视和自动保护电子邮件和文件 (包括存储在 Microsoft Teams 文件存储库中) 中的文件。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

当用户的电子邮件和文件检查敏感信息时，Exchange Online、SharePoint Online 和 OneDrive for Business 从 DLP 中获益，如组织的 DLP 策略中配置。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Microsoft 365 E3/A3/Business 高级版、Office 365 E3/A3 和 Office 365 数据丢失防护、F5 合规性和 F5 安全 & 合规性为用户提供了从 Exchange Online、SharePoint Online 和 OneDrive for Business 的 Office 365 DLP 中获益的权利。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，Exchange Online、SharePoint网站和 OneDrive 帐户 (租户中所有用户) DLP 功能的启用位置。 有关使用 DLP 策略的信息，请参阅 [数据丢失防护概述](/microsoft-365/compliance/data-loss-prevention-policies)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

管理员可以在"数据丢失防护 ("下) 安全与合规中心中的用户、包括用户和已排除用户等工作负载 &amp;   >  **自定义位置**。

## <a name="double-key-encryption-for-microsoft-365"></a>双密钥加密Microsoft 365

双密钥加密Microsoft 365保护高度敏感的数据，以满足特定要求并保持对加密密钥的完全控制。 双密钥加密使用两个密钥来保护你的数据，其中一个密钥在你的控件中，另一个密钥通过密码Microsoft Azure。 若要查看数据，您必须有权访问这两个密钥。 由于 Microsoft 只能访问一个密钥，因此你的密钥和数据对 Microsoft 不可用，从而确保你可以完全控制数据的隐私和安全性。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

用户可以将其加密数据迁移到云，从而受益于双密钥加密，只要密钥仍控制用户，就可以阻止第三方访问。 用户可以保护和使用双密钥加密内容，类似于任何其他敏感度标签受保护的内容。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合规性和 F5 安全 & 合规性、Microsoft 365 E5/A5/G5 信息保护和管理、Office 365 E5/A5/G5 和 EMS E5 为用户提供了从双密钥加密中获益的权利。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

双密钥加密支持桌面版本的 Microsoft Office for Windows。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

若要为授权用户分配Office 365和/或Microsoft 365组内的数据，请按照双密钥加密部署说明操作。

## <a name="ediscovery"></a>电子数据展示

电子数据展示为公司内的 IT 和法律部门提供调查和电子数据展示解决方案，以在从 Microsoft 365 系统导出之前识别、收集、保留、减少和查看与调查或诉讼相关的内容。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

如果用户被选择为Advanced eDiscovery保管人，则用户受益于 (对文档或电子文件具有管理控制权) 案例的用户。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Microsoft 365 E5/A5/G5/E3/A3/G3、Office 365 E5/A5/G5/E3/A3/G3 和 F5 合规性和 F5 安全 & 合规性为用户提供了从核心电子数据展示中获益的权利。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合规性和 F5 安全 & 合规性、Microsoft 365 E5/A5/G5 电子数据展示和审核以及 Office 365 E5/A5/G5 为用户提供从 Advanced eDiscovery 受益的权利。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，Advanced eDiscovery在安全与合规中心内分配电子数据展示权限时，租户内的所有用户在租户级别启用这些功能 &amp; 。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

电子数据展示管理员可以使用 Advanced eDiscovery 中的内置保管人管理工具选择特定用户作为案例的数据保管人，如将保管人添加到 Advanced eDiscovery[案例中所述](/microsoft-365/compliance/add-custodians-to-case)。

## <a name="information-barriers"></a>信息屏障

信息屏障是管理员可以配置以防止个人或组相互通信的策略。 例如，如果一个部门正在处理不应与其他部门共享的信息，或者需要阻止组与外部联系人通信，这将非常有用。 信息屏障策略还会阻止查找和发现。 这意味着，如果你尝试与不应通信的人通信，你将在人员选取器中找不到该用户。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

当用户受限于与其他用户通信时，他们受益于信息屏障的高级合规性功能。 可以定义信息屏障策略，以防止某些用户段与每个用户段通信，或允许特定细分仅与某些其他分段进行通信。 有关定义信息屏障策略的信息，请参阅 [定义信息屏障策略](/microsoft-365/compliance/information-barriers-policies)。 对于两个组无法相互通信的情况，这两个组的用户都需要许可证才能从服务中获益 (请参阅下面的示例) 。<br><br>

| 应用场景 | Who许可证？ |
|:------|:------|
| 组 1 (组 2 和组 2) 无法相互通信的两个组 (即组 1 用户不能与组 2 用户通信，组 2 用户不能与组 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 1 用户通信。 | 组 1 和组 &nbsp; &nbsp; 2 中的用户 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合规性和 F5 安全 & 合规性、Microsoft 365 E5/A5/G5 内部风险管理和 Office 365 E5/A5/G5 为用户提供从信息障碍中获益的权利。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

管理员使用安全与合规中心中的 PowerShell cmdlet 创建和管理信息屏障 &amp; 策略。 管理员必须分配有全局Microsoft 365 企业版管理员、Office 365全局管理员或合规性管理员角色，才能创建信息屏障策略。 默认情况下，这些策略适用于租户中的所有用户。 有关信息屏障的信息障碍，请参阅信息障碍[Microsoft Teams。](/MicrosoftTeams/information-barriers-in-teams)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

管理员可以自定义安全 (中心) 用户和排除用户等工作负载 &amp; 的位置。 例如，如果所有用户都获得 Office 365 E3 许可，但没有为 Office 365 高级合规版/E5 授权，则不需要为组织创建任何信息屏障策略。 有关详细信息，请参阅 [Teams](/MicrosoftTeams/information-barriers-in-teams)中的信息屏障。

## <a name="information-protection"></a>信息保护

信息保护可帮助组织发现、分类、标记和保护敏感文档和电子邮件。 管理员可以定义规则和条件以自动应用标签、用户可以手动应用标签或结合使用这两者，其中会为用户提供有关应用标签的建议。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

用户通过能够手动将敏感度标签应用于其内容或自动对内容进行分类而受益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business 高级版、F5 合规性和 F5 安全 & 合规性、企业移动性 + 安全性 E3/E5、M365 E5/A5/G5、Office 365 E5/A5/E3/A3/F3、AIP 计划 1 和 AIP 计划 2 为用户提供从手动敏感度标签中获益的权利。

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business 高级版 和 企业移动性 + 安全性 E3/E5， AIP 计划 1 和 AIP 计划 2 以及 F5 合规性和 F5 安全 & 合规性为用户提供了从 Power BI 中应用和查看敏感度标签的好处，以及将数据从 Power BI 导出到 Excel、PowerPoint 或 PDF 时保护数据的权利。

Microsoft 365 商业高级版和 Enterprise 移动性提供使用[AIPService](/powershell/azure/aip/overview#aipservice) PowerShell 模块管理 Azure 信息保护的 Azure 权限管理保护服务的权利。

> [!NOTE]
> Power BI包含在 Microsoft 365 E5/A5/G5 中;在所有其他计划中，Power BI必须单独获得许可。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合规性和 F5 安全 & 合规性、Microsoft 365 E5/A5/G5 信息保护和管理、Office 365 E5、企业移动性 + 安全性 E5/A5/G5 和 AIP 计划 2 为用户提供了以下权限：从自动敏感度标签中获益。

信息保护不包括基于可训练分类器机器学习 (自动分类) 。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，在租户级别为租户内的所有用户启用信息保护功能。 有关为许可用户配置策略的信息，请参阅激活 Azure 权限管理。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

除非使用 AIP 扫描程序功能，否则可以将策略的范围划分到特定组或用户，并可以编辑注册表以防止未经授权的用户运行分类或标记功能。

对于 AIP 扫描程序功能，Microsoft 不承诺向未获得许可的用户提供文件分类、标记或保护功能。

有关详细信息，请参阅创建和发布 [敏感度](/microsoft-365/compliance/create-sensitivity-labels#publish-sensitivity-labels-by-creating-a-label-policy) 标签和 [了解 Azure 信息保护统一标签扫描程序](/azure/information-protection/deploy-aip-scanner)。

## <a name="information-governance"></a>信息治理

信息治理通过发现、分类、标记和管理数据来帮助组织管理其风险。 利用信息治理，组织可以满足业务和法规要求，并且通过跨组织数据和第三方数据提供保留和删除功能Microsoft 365攻击面。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

用户受益于能够将数据分类以保留特定策略和法规。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Microsoft 365 F3/Business 高级版、Office 365 E5/A5/G5/E3/A3/G3/E1/A1/G1/F3 和独立 Exchange 计划为用户提供了从手动将非记录保留标签应用于邮箱数据中获益的权限。

Microsoft 365 F3/F1/Business 高级版、Office 365 E5/A5/G5/E3/A3/G3/F3/E1/A1/G1 和独立 SharePoint 计划为用户提供了从手动将非记录保留标签应用于 SharePoint 或 OneDrive 中的文件的好处。

Microsoft 365 E5/A5/G5/E3/A3/Business 高级版、Office 365 E5/A5/G5/E3/A3、Exchange 计划 2 和 Exchange Online Archiving 为用户提供了从组织范围或位置范围的基本邮箱保留策略中获益的权限。

Microsoft 365 E5/A5/G5/E3/A3、Office 365 E5/A5/G5/E3/A3 和 SharePoint 计划 2 为用户提供了从基本 SharePoint 或 OneDrive 保留策略中获益和/或手动将非记录保留标签应用于 SharePoint 或OneDrive。

组织可以使用保留策略根据策略Teams或删除邮件。 这包括管理聊天Teams对话中的消息。

以下许可证为用户提供了从保留策略Teams的权利：

- Microsoft 365 E5/G5/A5/E3/G3/A3/F3/F1、Business Basic、Business Standard 和 Business 高级版
- Office 365 E5/G5/A5/E3/G3/A3/F3/E1/G1

对于具有以下许可证的用户，受支持的最小保留或删除期限为 30 天：

- Microsoft 365 F1/F3、Business Basic、Business Standard 和 Business 高级版
- Office 365 E1/G1 和 F3

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合规性和 F5 安全 & 合规性、Microsoft 365 信息保护和管理 E5/A5/G5 以及 Office 365 E5/A5 为用户提供了从自动应用保留标签或策略、应用默认保留中获益的权利标签或策略，基于自定义事件开始保留标签的保留期，在标签保留期结束时触发手动处置评审，通过本机数据连接器导入第三方数据，声明文件记录，发现标记内容，并监视标签活动。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合规性和 F5 安全 & 合规性、Microsoft 365 E5/A5/G5 信息保护和治理为用户提供了根据可训练分类器自动应用保留标签的好处。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，在租户级别为租户内的所有用户启用信息治理功能。 有关配置信息治理以对许可用户应用自动标签和策略的信息，请参阅 Microsoft [Microsoft 365。](/microsoft-365/compliance/manage-information-governance)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

信息治理功能可应用于特定位置的许可用户 (网站、组网站等) 。 有关配置信息治理以对许可用户应用自动标签和策略的信息，请参阅 Microsoft [Microsoft 365。](/microsoft-365/compliance/manage-information-governance)

## <a name="insider-risk-management"></a>内部风险管理

内部风险管理是一种Microsoft 365，通过让你检测、调查和对组织中存在风险的活动采取行动，有助于将内部风险降至最低。

自定义策略允许你检测组织中恶意和无意间存在风险的活动并采取措施，包括根据需要将Advanced eDiscovery上报给 Microsoft 客户。 您组织的风险分析师可以快速采取相应的措施，以确保用户符合组织的合规性标准。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

用户通过监视其活动的风险而受益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合规性和 F5 安全 & 合规性以及 Microsoft 365 E5/A5/G5 内部风险管理为用户提供从内部风险管理中获益的权利。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

必须在管理中心中创建内部风险管理策略Microsoft 365 合规中心分配给用户。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

在 Microsoft 365 合规中心 中创建策略时，在"选择用户和组"页上，选择"选择用户或组"以仅选择许可用户，或者，如果您的所有用户都获得许可，您可以选择"所有用户和启用邮件的组"复选框。  有关详细信息，请参阅 [内部风险管理入门](/microsoft-365/compliance/insider-risk-management-configure)。

## <a name="microsoft-defender-for-identity"></a>Microsoft Defender for Identity

Microsoft Defender for Identity (以前是 Azure 高级威胁防护) 是一项云服务，可帮助保护企业混合环境免受多种类型的高级目标网络攻击和内部威胁。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

SecOp 分析师和安全专业人员受益于 Microsoft Defender for Identity 检测和调查高级威胁、泄露的身份和恶意预览体验成员操作的能力。 最终用户通过让 Microsoft Defender for Identity 监视其数据而受益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

企业移动性 + 安全性E5/A5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 Security、Microsoft F5 Security & Compliance 和 Microsoft Defender for Identity for Users 提供从 Microsoft Defender for Identity 中获益的权利。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，在租户级别为租户内的所有用户启用 Microsoft Defender for Identity 功能。 有关配置 Azure ATP 的信息，请参阅 [创建 Microsoft Defender for Identity 实例](/defender-for-identity/install-step1)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

Microsoft Defender for Identity 服务当前无法将功能限制到特定用户。 必须对希望受益的每个用户授予许可。

## <a name="microsoft-defender-for-office-365"></a>Microsoft Defender for Office 365

Microsoft Defender for Office 365 (以前Office 365高级威胁防护) 帮助保护组织免受钓鱼和零日恶意软件等复杂攻击。 Microsoft Defender for Office 365还通过关联来自各种数据的信号来提供可操作见解，以帮助识别潜在威胁、确定优先级并提供相关建议。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

Microsoft Defender for Office 365保护用户免受钓鱼和零日恶意软件等复杂攻击。 有关计划 1 和计划 2 中提供的服务的完整列表，请参阅[Microsoft Defender for Office 365。](/microsoft-365/security/office-365-security/office-365-atp)

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？ 

Microsoft Defender for Office 365 Plans 1 and 2， Office 365 E5/A5/G5， Microsoft 365 E5/A5/G5， Microsoft 365 E5/A5/G5/F5 Security，Microsoft 365 F5 Security & Compliance， and Microsoft 365 商业高级版 provide the rights for a user to benefit from Microsoft Defender for Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，租户内的所有用户Office 365启用 Microsoft Defender for Office 365 功能。 有关为许可用户配置 Microsoft Defender Office 365策略的信息，请参阅 Microsoft [Defender for Office 365。](/microsoft-365/security/office-365-security/office-365-atp)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

若要将 Microsoft Defender Office 365范围，请遵循保险箱链接保险箱附件"部署策略：

- 有关为许可用户保险箱链接的信息，请参阅[保险箱 Links in Microsoft Defender for Office 365。](/microsoft-365/security/office-365-security/atp-safe-links)

- 有关为授权用户保险箱附件的信息，请参阅[保险箱 Attachments in Microsoft Defender for Office 365。](/microsoft-365/security/office-365-security/atp-safe-attachments)

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) 是云访问安全代理 (CASB) 解决方案，使组织能够查看其云应用和服务，提供复杂的分析以识别和防御网络威胁，并让他们控制数据在任何云应用中的传输方式。 &mdash;

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

MCAS 发现和评估影子 IT，跨第一方和第三方云应用提供威胁防护，并保护第一方和第三方云应用的信息。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

企业移动性 + 安全性E5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 安全、Microsoft 365 E5/A5/G5/F5 合规性、Microsoft 365 F5 安全 & 合规性和 Microsoft 365 信息保护和管理为用户提供了从 MCAS 中获益的权利。

Azure ADP1 为用户提供了从 MCAS 中的发现功能中获益的权利。

若要从 MCAS 中的条件访问应用控制功能中获益，用户还必须获得 Azure Active Directory P1 的许可，P1 包含在 企业移动性 + 安全性 F1/F3/E3/A3/G3、企业移动性 + 安全性 E5、Microsoft 365 E3/A3/G3、Microsoft 365 E5/A5/G5/F Microsoft 365 E5 5 安全与 Microsoft 365 F5 & 合规性中。

若要从自动客户端标记中获益，用户必须获得 Azure 信息保护 P2 的许可，该 P2 包含在 企业移动性 + 安全性 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合规性、Microsoft 365 F5 安全 & 合规性和 Microsoft 365 信息保护和管理中。

> [!NOTE]
> 自动服务器端标签需要信息保护Office 365 - 高级版许可证 (`MIP_S_CLP2` 或 `efb0351d-3b08-4503-993d-383af8de41e3`) 。 有关参考，请参阅 [许可的产品名称和服务计划标识符](/azure/active-directory/enterprise-users/licensing-service-plan-reference)。

有关详细信息，请参阅Microsoft Cloud App Security[数据表](https://www.aka.ms/mcaslicensing)。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，在租户级别为租户内的所有用户启用 MCAS 功能。

有关为授权用户Microsoft Cloud App Security策略的信息，请参阅Microsoft Cloud App Security[概述](/cloud-app-security/what-is-cloud-app-security)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

管理员可以使用服务中提供的范围部署功能将 MCAS 部署范围缩小到许可用户。 有关详细信息，请参阅作用域 [部署](/cloud-app-security/scoped-deployment)。

## <a name="microsoft-defender-for-endpoint"></a>Microsoft Defender for Endpoint

Microsoft Defender for Endpoint (以前为 Microsoft Defender ATP) 是一种终结点安全解决方案，包括基于风险漏洞管理和评估;攻击面减少功能;基于行为的和由云支持的下一代保护;终结点检测和响应 (EDR) ;自动调查和修正;和托管搜寻服务。 有关详细信息 [，请参阅 Microsoft Defender for Endpoint](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) 页面。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中获益？

Windows 10 企业版 E5、Windows 10 教育版 A5、Microsoft 365 E5/G5 的许可用户，其中包括 Windows 10 企业版 E5、Microsoft 365 E5/A5/G5/F5 安全Microsoft 365 F5 &合规性可以从 Microsoft Defender for Endpoint 受益。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

SecOps 分析员和安全专业人员受益于 Microsoft Defender for Endpoint 的终结点安全性功能，以执行预防性保护、攻破后检测、自动调查和对高级威胁的响应。 最终用户通过 Microsoft Defender for Endpoint 监视恶意事件而受益。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，在租户级别为租户内的所有用户启用 Microsoft Defender for Endpoint 功能。 有关部署的信息，请参阅 [部署阶段](/windows/security/threat-protection/microsoft-defender-atp/deployment-phases)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

Microsoft Defender for Endpoint 管理员可以使用基于角色的访问控制 (RBAC) 在安全操作团队内创建角色和组，以授予对 Microsoft Defender 安全中心 的适当访问权限。 有关详细信息，请参阅使用基于角色 [的访问控制管理门户访问](/windows/security/threat-protection/microsoft-defender-atp/rbac)。

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp-and-for-teams-export"></a>Microsoft Graph DLP Teams (和 Teams 导出的 Microsoft) API

这些 API 使开发人员可以生成安全与合规性应用，这些应用可以"侦听"Microsoft Teams 消息，或以一对一的群聊或 Teams 频道导出团队消息。 这些 API 为客户和 ISV 启用 DLP 和其他信息保护和管理方案。 此外，Microsoft Graph 修补程序 API 允许对邮件应用 DLP Teams操作。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

[数据丢失防护 (DLP) ](/microsoft-365/compliance/dlp-microsoft-teams)功能在组织中广泛使用Microsoft Teams，尤其是在组织转移到远程工作时。 如果组织具有 DLP，现在可以定义防止用户共享频道或聊天会话中Microsoft Teams策略。

信息保护和管理功能在组织中广泛使用Microsoft Teams，尤其是在组织转移到远程工作时。 使用[Teams导出 API，](/microsoftteams/export-teams-content)可以将数据导出到第三方电子数据展示或合规性存档应用程序，以确保符合合规性要求。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

- Microsoft 365 E5/A5
- Microsoft 365 E5/A5 合规
- Microsoft 365 E5/A5 安全性
- Microsoft 365 E5/A5 信息保护和治理

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

API 访问在租户级别配置。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

Microsoft Graph DLP 和Teams导出Teams提供了租户级值。 每位打算从此服务受益的用户都必须获得许可。 作为一个附加值，我们将为每个许可用户添加种子设定容量，每月计算一次，并聚合在租户级别。 对于超出种子容量的使用，将针对 API 使用向应用所有者计费。

有关种子设定容量和消耗费用的信息，请参阅Graph[聊天消息的一些要求](/graph/teams-licenses)。

## <a name="office-365-advanced-message-encryption"></a>Office 365 高级邮件加密

Office 365 高级邮件加密帮助客户履行合规性义务，这些义务要求对外部收件人及其对加密电子邮件的访问进行更灵活的控制。 通过高级邮件加密，管理员可以使用可检测敏感信息类型 (（例如，个人标识信息或财务或运行状况标识) ）的自动策略控制在组织外部共享的敏感电子邮件，或者，他们可以使用关键字通过应用自定义电子邮件模板并通过安全 Web 门户使加密电子邮件的访问权限过期来增强保护。 此外，管理员还随时通过撤销访问权限，进一步控制通过安全 Web 门户从外部访问的加密电子邮件。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

邮件发件人受益于高级邮件加密提供的对敏感电子邮件的附加控制。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/F5 合规性和 F5 安全 & 合规性以及 Microsoft 365 E5/A5/G5 信息保护和管理为用户提供了从高级邮件加密中获益的权利。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

管理员在管理中心的"邮件流规则"Exchange和管理高级 **邮件加密**  >  **策略**。 默认情况下，这些规则适用于租户中的所有用户。 有关设置新邮件加密功能的信息，请参阅设置新的邮件Office 365 邮件加密[功能](/office365/securitycompliance/set-up-new-message-encryption-capabilities)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

管理员应仅将高级邮件加密的邮件流规则应用于许可用户。 有关定义邮件流规则的信息，请参阅在邮件流中定义用于加密电子邮件[Office 365。](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)

## <a name="office-365-cloud-app-security"></a>Office 365 云应用安全

Office 365 云应用安全 (OCAS) 是 Microsoft Cloud App Security 的子集，其功能限制为 Office 365，而第三方云应用和 IaaS 服务没有额外的安全性。

OCAS 使组织能够了解其工作效率的云应用和服务，提供复杂的分析，以识别和防御网络威胁，并让他们控制数据在 &mdash; Office 365。

若要比较功能，请参阅[Differences between Microsoft Cloud App Security and Office 365 云应用安全](/cloud-app-security/editions-cloud-app-security-o365)。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

OCAS 发现卷影 IT，跨 Office 365 提供威胁防护，并可以控制哪些应用有权访问数据。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Office 365 E5/A3/A5/G5 为用户提供从 OCAS 中获益的权利。
有关详细信息，请参阅Microsoft Cloud App Security[数据表](https://www.aka.ms/mcaslicensing)。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，在租户级别为租户内的所有用户启用 OCAS 功能。

有关配置服务的信息，请参阅 Basic [setup for 云应用安全](/cloud-app-security/general-setup)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

管理员可以将 OCAS 部署的范围限定为强制访问某些应用，并限制由管理员监视Office 365 云应用安全。 有关详细信息，请参阅作用域 [部署](/cloud-app-security/scoped-deployment)。

## <a name="office-365-customer-lockbox"></a>Office 365 客户密码箱

客户密码箱通过为客户提供为服务操作提供显式访问授权的能力，提供了一层额外的控制。 通过证明已制定显式数据访问授权过程，客户密码箱还可以帮助组织履行某些合规性义务，如 HIPAA 和 FedRAMP。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

客户密码箱可确保未经客户明确批准，Microsoft 中的任何人无法访问客户内容以执行服务操作。 客户密码箱将客户引入对访问其内容的请求的审批工作流。 有时，Microsoft 工程师会在支持过程中参与排查和修复客户报告的问题。 在大多数情况下，可以通过 Microsoft 已针对其服务提供的广泛遥测和调试工具来修复问题。 但是，在某些情况下，可能要求 Microsoft 工程师访问客户内容以确定根本原因并解决该问题。 作为审批工作流程的最后一步，客户密码箱要求工程师向客户请求访问权限。 这使组织可以选择批准或拒绝这些请求，从而直接控制 Microsoft 工程师能否访问组织的最终用户数据。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合规性和 F5 安全 & 合规性以及 Microsoft 365 E5/A5/G5 内部风险管理为用户提供从客户密码箱中获益的权利。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

管理员可以在密码箱中打开Microsoft 365 管理中心。 有关详细信息，请参阅客户[密码箱Office 365。](/microsoft-365/compliance/customer-lockbox-requests) 当客户密码箱打开时，Microsoft 需要先获得组织的批准，才能访问其任何内容。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

目前，客户密码箱服务不能仅限于特定用户。 虽然租户服务当前无法将权益限制为特定用户，但应努力将服务权益限制为许可用户。 这可帮助避免目标功能可用后潜在的服务中断。

## <a name="office-365-message-encryption"></a>Office 365 邮件加密

Office 365 邮件加密 (OME) 是一项基于 Azure 权限管理 (Azure RMS) 构建的服务，允许您向组织内外发送经加密的电子邮件，而无需考虑目标电子邮件地址（Gmail、Yahoo!Mail、Outlook.com 等）。

若要查看加密邮件，收件人可以使用一次性密码、通过 Microsoft 帐户登录或使用与 Office 365 关联的工作或学校帐户登录。 此外，收件人也可发送加密回复。 他们无需订阅来查看加密邮件或发送加密回复。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

邮件发件人受益于由邮件发件人提供的对敏感Office 365 邮件加密。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Microsoft 365 E3/A3/G3、Office 365 E3/A3/G3 和 Azure 信息保护计划 1 为用户提供从 Office 365 邮件加密 中Office 365 邮件加密。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

管理员在邮件流规则Office 365 邮件加密管理中心Exchange管理 **策略**  >  。 默认情况下，这些规则适用于租户中的所有用户。 有关设置新的邮件加密Office 365 邮件加密，请参阅[设置新的邮件加密功能](/office365/securitycompliance/set-up-new-message-encryption-capabilities)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

管理员应仅对授权用户Office 365 邮件加密邮件流规则。 有关定义邮件流规则的信息，请参阅定义邮件 [流规则以加密电子邮件](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)。

## <a name="privacy-management"></a>隐私管理

[隐私管理 Microsoft 365](https://aka.ms/privacymanagementdocs)是 Microsoft 在隐私管理软件空间中的第一个解决方案。 隐私管理通过主动识别和防范隐私风险（如数据存储、数据传输和数据过度共享）来帮助公司保护个人数据并构建隐私复原工作区，使信息工作者能够做出智能数据处理决策，并大规模自动执行和管理主题请求。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

隐私管理是具有 Office 365 A1/E1/A3/E3/A5/E5 和 Microsoft 365 A3/E3/A5/E5 订阅的组织的新增功能。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

用户可从以下功能中获益：组织能够了解其环境中的私人数据、主动识别和防范隐私风险，以及大规模管理使用者权限请求 (通常称为"数据主体请求) 。

### <a name="how-can-customers-access-the-service"></a>客户如何访问服务？

隐私管理内置在租户Microsoft 365 合规中心租户[](https://compliance.microsoft.com/homepage)级别为租户内的所有用户启用。 我们建议为打算从该服务受益并保护的任何用户获取许可证。

客户可以基于组织需求购买以下许可证：

**隐私管理 – 风险** 允许组织：

- 了解企业环境中个人数据Microsoft 365、 (Microsoft Exchange Online SharePoint、OneDrive业务Teams) 相关的风险。
- 利用默认隐私策略模板（包括数据最小化、数据过度利用和数据传输）或自定义它们以满足您独特的组织需求。
- 接收建议的修正控制措施，以减少隐私风险。
- 与来自生产力套件内的信息工作者互动，并推动行为变更。

**隐私管理 –主体权限请求** 允许组织：

- 自动响应主题权限请求，并大规模管理它们。
- 将 Microsoft Power Automate模板与现有业务流程一 (需要相应的许可证才能进行Power Automate) 。
- 利用对 API 的编程访问。
- 通过安全集成与其他利益干系Microsoft Teams， (需要适当的许可证才能进行Microsoft Teams) 。</br>
    客户将能够购买 1、10 或 100 个块中的主题权限请求。

隐私管理-风险和隐私管理主体权限请求可以相互独立地购买，并可在以下[Microsoft 365 管理中心。](https://admin.microsoft.com/)

请参阅 [产品条款](https://www.microsoft.com/licensing/terms/productoffering/Microsoft365/EAEAS) ，了解获取隐私管理（风险和隐私管理）主体权限请求所需的许可先决条件。

在此处了解有关隐私管理免费试用版 [的更多信息](https://aka.ms/privacymgmt/TrialDocs)。

## <a name="privileged-access-management-in-office-365"></a>Office 365 中的 Privileged Access Management

[PAM (Privileged access management) ](/microsoft-365/compliance/privileged-access-management-configuration)提供对 OFFICE 365 中特权管理任务的细化访问控制。 启用 PAM 后，若要完成提升的特权任务，用户将需要通过范围和时间高度限制的审批工作流请求实时访问。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

启用 PAM 可让组织以零长期特权运行。 用户受益于针对长期管理访问引发的漏洞的附加防护层，该访问提供对数据的不受限制的访问。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？ 

Office 365 E5/A5、Microsoft 365 E5/A5、Microsoft 365 E5/A5/F5 合规性和 F5 安全 & 合规性以及 Microsoft 365 E5/A5 信息保护和治理为用户提供了从 PAM 受益的权利。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，在租户级别为租户内的所有用户启用 PAM 功能。 有关配置 PAM 策略的信息，请参阅特权 [访问管理入门](/microsoft-365/compliance/privileged-access-management-configuration)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

客户可以通过审批者组和访问策略（可应用于许可用户）按用户管理 PAM。 有关详细信息，请参阅[Privileged access management in Office 365](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751)。

## <a name="records-management"></a>记录管理

记录管理通过发现、分类、标记、保留和防止删除 Microsoft 365 和第三方数据，帮助组织履行业务和监管记录保留义务。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合规性和 F5 安全 & 合规性、Microsoft 365 信息保护和管理 E5/A5/G5 以及 Office 365 E5/A5/G5 为用户提供了从记录管理中获益的权利，包括将项目声明为记录或监管记录，自动应用保留或记录标签并执行处置评审 (基于可训练分类器自动应用保留标签) 。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合规性和 F5 安全 & 合规性以及 Microsoft 365 信息保护和治理为用户提供了根据可训练分类器自动应用保留标签或记录标签的权利。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

用户可以通过策略定义和声明（通过防御性处置）将内容声明为记录并管理其完整记录过程，因此用户受益。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，在租户级别为租户内的所有用户启用记录管理功能。 有关配置记录管理以应用于许可用户的信息，请参阅了解记录[Microsoft 365。](/microsoft-365/compliance/records-management)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

记录管理功能可应用于工作组网站、组网站 (特定位置的许可) 。 有关配置记录管理以应用于许可用户的信息，请参阅了解记录[Microsoft 365。](/microsoft-365/compliance/records-management)
