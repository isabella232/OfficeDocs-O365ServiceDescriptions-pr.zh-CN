---
title: 有关安全&合规性的Microsoft 365指南
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
description: 本文提供有关Microsoft 365合规性的指导，以帮助避免因未经许可的访问而导致的潜在服务中断。
ms.openlocfilehash: cce6e34112bbb1a6b422f53891a8ccd24562c3e1
ms.sourcegitcommit: cee14aa16defb331bd4c610e6c3549269a5e4841
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/13/2022
ms.locfileid: "64828734"
---
# <a name="microsoft-365-guidance-for-security-amp-compliance"></a>Microsoft 365安全&amp;合规性指南

在本文中，租户级服务是一项联机服务，它为租户中的所有用户部分或完整激活， (独立许可证和/或作为Microsoft 365或Office 365计划) 的一部分。 客户使用联机服务需要适当的订阅许可证。 若要查看允许用户从Microsoft 365合规性功能中受益的选项，请下载 [Microsoft 365比较表](https://go.microsoft.com/fwlink/?linkid=2139145)。

某些租户服务当前无法限制特定用户的权益。 应努力限制许可用户的服务权益。 若要查看有关使用 Microsoft 产品和Professional通过 Microsoft 许可计划获取的服务的条款和条件，请参阅 [产品条款](https://www.microsoft.com/Licensing/product-licensing/products)。

## <a name="advanced-audit"></a>高级审核

Microsoft 365中的高级审核为用户和管理员活动提供一年的审核日志保留期，并提供创建自定义审核日志保留策略以管理其他Microsoft 365服务的审核日志保留的功能。 它还提供对关键事件的访问权限，以便调查和高带宽访问Office 365管理活动 API。 有关详细信息，请参阅[Microsoft 365中的高级审核](/microsoft-365/compliance/advanced-audit)。

还可以使用加载项 SKU 启用 10 年的保留期。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中受益？

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合规性、Microsoft 365 F5 安全&合规性和Microsoft 365 E5/A5/G5 电子数据展示和审核的许可用户可从高级审核中受益。

具有高级审核和 10 年审核日志保留加载项的许可用户可以受益于 10 年的审核日志保留期。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中受益？

用户受益于高级审核，因为与Microsoft 365服务中的用户活动相关的审核记录最多可以保留一年。 此外，还会记录高价值审核事件，例如访问或读取用户邮箱中的项目时。 有关详细信息，请参阅[Microsoft 365中的高级审核](/microsoft-365/compliance/advanced-audit)。

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？

默认情况下，在租户级别为从服务中受益的所有用户启用高级审核，并自动为Azure Active Directory、Exchange和SharePoint中具有适当许可证) 的用户 (执行的活动提供一年的审核日志保留期。 此外，组织可以使用审核日志保留策略来管理其他Microsoft 365服务中活动生成的审核记录的保留期。 还使用相同的保留策略启用了 10 年审核日志保留功能。 有关详细信息，请参阅[管理审核日志保留策略](/microsoft-365/compliance/audit-log-retention-policies)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用到获得服务许可的租户中的用户？

审核日志的一年保留期和对关键事件的审核仅适用于具有相应许可证的用户。 此外，管理员可以使用审核日志保留策略为特定用户的审核日志指定更短的保留期。

审核日志的 10 年保留期仅适用于具有相应加载项许可证的用户。 从 2021 年初开始，需要加载项 SKU。

## <a name="azure-active-directory-identity-governance"></a>Azure Active Directory标识治理

Azure Active Directory标识治理使你能够平衡组织对安全和员工工作效率的需求与正确的流程和可见性。 它使用权利管理、访问评审、特权标识管理和使用条款策略来确保合适的人有权访问正确的资源。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中受益？

Azure Active Directory标识治理使用户更轻松地请求访问一个访问包中的应用、组和Microsoft Teams，从而提高了用户的工作效率。 也可以将用户配置为审批者，而不涉及管理员。 对于访问评审，用户可以使用智能建议查看组的成员身份，以便定期采取措施。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中受益的权限？

企业移动性 + 安全性 E5/A5、Microsoft 365 E5/A5、Microsoft 365 E5/A5/F5 安全性和 F5 安全&符合性，Azure Active Directory Premium计划 2 为用户提供从中受益的权限Azure Active Directory标识治理。

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？

Azure AD标识治理功能在租户级别启用，但每个用户实现。 有关Azure AD标识治理的信息，[请参阅什么是Azure AD标识治理？](/azure/active-directory/governance/identity-governance-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用到获得服务许可的租户中的用户？

管理员只能为许可用户分配访问包、访问评审或特权标识管理，从而Azure AD标识治理的范围。 有关如何作用域Azure AD标识治理部署的说明，请参阅：

- [Azure AD权利管理许可证要求](/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Azure AD访问评审许可证要求](/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [使用Privileged Identity Management的许可证要求](/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory 标识保护

Azure Active Directory标识保护是Azure Active Directory Premium P2计划的一项功能，可用于检测影响组织标识的潜在漏洞、配置对检测到的与组织标识相关的可疑操作的自动响应，以及调查可疑事件和采取适当的操作来解决这些问题。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中受益？

SecOps 分析师和安全专业人员受益于基于机器学习算法对已标记用户和风险事件的合并视图。 最终用户受益于通过基于风险的条件访问提供的自动保护以及通过处理漏洞提供的改进的安全性。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中受益的权限？

- Azure Active Directory计划 1：Microsoft 365 E3/A3/G3/F1/F3、Enterprise移动性&安全 E3 和Microsoft 365 商业高级版
- Azure Active Directory计划 2：Microsoft 365 E5/a5/G5、Enterprise移动性&安全 E5、Microsoft 365 E5/F5 安全性和Microsoft 365 F5 安全&合规性

有关可用的不同计划中包含的功能的详细信息，[请参阅什么是Azure Active Directory标识保护？](https://www.microsoft.com/en-us/security/business/identity-access-management/azure-ad-pricing)

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？

默认情况下，租户级别为租户中的所有用户启用Azure AD标识保护功能。 有关Azure AD标识保护的信息，[请参阅什么是标识保护？](/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用到获得服务许可的租户中的用户？

管理员可以通过分配风险策略来限制Azure AD标识保护，这些策略定义密码重置级别，并仅允许许可用户访问。 有关如何Azure AD标识保护部署的范围的说明，请参阅[如何配置和启用风险策略](/azure/active-directory/identity-protection/howto-sign-in-risk-policy)。

## <a name="communication-compliance"></a>通信合规性

Microsoft 365中的通信符合性可帮助你检测、捕获和采取针对组织中不当消息的修正操作，从而最大程度地降低通信风险。 可以定义特定策略，用于捕获组织中的内部和外部电子邮件、Microsoft Teams或第三方通信。 审阅者可以采取适当的修正措施，以确保它们符合组织的消息标准。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中受益？

合规性专家通过让组织通信受到通信合规性策略的监视，从服务中受益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中受益的权限？

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合规性、Microsoft 365 F5 安全&合规性和Microsoft 365 E5/A5/G5 预览体验成员风险管理为用户提供从通信中获益的权限合 规。

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？

管理员和合规性专家在Microsoft 365 合规中心中创建通信合规性策略。 这些策略定义哪些通信和用户在组织中需要审阅，定义通信必须满足的自定义条件，并指定谁应执行评审。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用到获得服务许可的租户中的用户？

管理员选择要包含在通信合规性策略中的特定用户或组。 选择组时，他们还可以在组中选择要从通信合规性策略中排除的特定用户。 有关通信符合性策略的详细信息，请参阅[Microsoft 365中的通信合规性开始](/microsoft-365/compliance/communication-compliance-configure)。

## <a name="compliance-manager"></a>合规性管理器

[Microsoft 合规性管理器](https://compliance.microsoft.com/compliancemanager)是[Microsoft 365 合规中心](/microsoft-365/compliance/microsoft-365-compliance-center)中的一项功能，可帮助你更轻松、更方便地管理组织的合规性要求。 合规性管理器可以帮助你完成合规性之旅，从清查数据保护风险到管理实现控制的复杂性、及时了解最新法规和认证、以及向审核员报告。

合规性管理器通过提供以下内容来帮助简化合规性和降低风险：

- 针对常见行业和区域标准和法规的预建或自定义评估，满足独特的合规性要求。
- 工作流功能通过单一工具帮助你有效完成风险评估。
- 有关建议的改进措施的详细分步指南，以帮助你遵守与组织最相关的标准和法规。 对于由 Microsoft 管理的操作，你将看到实现详细信息和审核结果。
- 基于风险的合规性分数，可通过衡量完成改进操作的进度来帮助你了解合规性状况。

### <a name="who-can-access-compliance-manager"></a>Who可以访问合规性管理器？

合规性管理器适用于拥有Office 365和Microsoft 365许可证的组织，以及美国政府社区云 (GCC) 、GCC高和国防部 (DoD) 客户。 评估可用性和管理功能取决于许可协议。

### <a name="what-are-premium-assessments"></a>什么是高级评估？

高级版评估是合规性管理器和帮助的附加值：

- 将复杂的法规要求转换为特定控件
- 建议建议的改进操作
- 根据法规提供可量化的合规度量值

合规性管理器有 300 多个高级评估，客户可以使用这些评估来评估其符合各种全球、区域和行业法规和标准。

拥有包含Microsoft Exchange Online许可证的订阅的任何客户都可购买合规性管理器高级评估。

### <a name="which-premium-assessments-are-available"></a>哪些高级评估可用？

下面是 [高级评估列表](/microsoft-365/compliance/compliance-manager-templates-list#premium-templates)。

### <a name="which-assessments-are-included-by-default-free-of-cost"></a>默认情况下包含哪些评估 (免费) ？

某些评估包含在合规性管理器和客户许可证类型中。 有关详细信息，请参阅下表：

| 许可证类型 | 默认情况下 (包含的评估模板)  |
|:-----|:-----|
|<ul><li>Microsoft 365或Office 365 A1/E1/F1/G1</li><li>Microsoft 365或Office 365 A3/E3/F3/G3</li></ul>|<ul><li>数据保护基线</li></ul>|
|<ul><li>Microsoft 365或Office 365 A5/E5/G5</li><li>Microsoft 365 A5/E5/F5/G5 符合性</li><li>Microsoft 365 A5/E5/F5/G5 电子数据展示和审核</li><li>Microsoft 365 A5/E5/F5/G5 预览体验成员风险管理</li><li>Microsoft 365 A5/E5/F5/G5 信息保护和治理</li></ul>|<ul><li>数据保护基线</li><li>欧盟 GDPR</li><li>NIST 800-53</li><li>ISO 27001</li><li>CMMC 级别 1-5 (仅适用于 G5) </li><li>自定义评估</li></ul>|

### <a name="what-are-custom-assessments"></a>什么是自定义评估？

自定义评估是一项合规性管理器功能，可提供创建新模板或自定义现有评估模板（包括添加或更新控件和改进操作）的功能。

### <a name="who-can-access-custom-assessments"></a>Who可以访问自定义评估？

具有 E5 订阅的客户可使用自定义评估功能，如下所示：

- Microsoft 365或Office 365 A5/E5/G5
- Microsoft 365 A5/E5/F5/G5 符合性
- Microsoft 365 A5/E5/F5/G5 电子数据展示和审核
- Microsoft 365 A5/E5/F5/G5 预览体验成员风险管理
- Microsoft 365 A5/E5/F5/G5 信息保护和治理

## <a name="compliance-program-for-microsoft-cloud"></a>Microsoft 云符合性计划

[Microsoft 云合规性计划](https://aka.ms/cpmc) 旨在提供个性化的客户支持、教育和网络机会。 通过加入该计划，客户将获得与监管机构、行业同行和 Microsoft 专家直接就安全、合规性和隐私领域进行直接接触的独特机会。 此计划取代了 2013 年创建的现有金融服务行业 (FSI) 合规性计划。

### <a name="who-can-access-the-compliance-program-for-microsoft-cloud"></a>Who可以访问 Microsoft 云的合规性计划？

Microsoft 云符合性计划适用于具有Microsoft 365和Office 365许可证的组织。

当前已注册 FSI 符合性计划的客户需要为 Microsoft 云的新合规性计划购买订阅。 有关详细信息，请参阅 [Microsoft Cloud 的合规性计划](https://aka.ms/cpmc)。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中受益？

Enterprise希望 Microsoft 协助其云旅程的组织，例如风险评估员、合规官、内部审核员、隐私官员、法规事务/法律人员，CISO 将从此服务中受益。 下面是客户可以获得的可用权益的示例方案：

- 用于加入和使用 Microsoft 云服务的风险评估的持续风险和合规性帮助。
- 支持 Microsoft 云服务的 Microsoft 和客户管理的控件。
- 协助内部审核、监管机构或董事会批准使用第三方云服务。
- 支持与使用云服务中的复杂风险和合规性要求相关的持续技术问题。
- 直接协助填写固定数量的客户风险和合规性问卷。
- 与监管机构和行业专家建立联系，帮助解决合规性过程中的问题。

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？

默认情况下，Microsoft 云符合性计划在租户级别为从服务中受益的所有用户启用。 有关详细信息，请参阅 [Microsoft Cloud 的合规性计划](https://aka.ms/cpmc)。

## <a name="data-connectors"></a>数据连接器

Microsoft 提供可在Microsoft 365 合规中心中配置的第三方数据连接器。 有关 Microsoft 提供的数据连接器列表，请参阅 [第三方数据连接器](/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) 表。 下表还汇总了在Microsoft 365中导入和存档数据后可应用于第三方数据的符合性解决方案，以及指向每个连接器的分步说明的链接。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中受益？

使用数据连接器在Microsoft 365中导入和存档第三方数据的主要优点是，在导入数据后，可以对数据应用各种Microsoft 365合规性解决方案。 这有助于确保组织的非 Microsoft 数据符合影响组织的法规和标准。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中受益的权限？

以下许可证为用户提供从数据连接器中受益的权限：

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/a5/g5 信息保护&amp;治理
- Microsoft 365 E5/a5/G5/F5 符合性
- Microsoft 365 F5 安全&合规性
- Microsoft 365 E5/a5/g5 预览体验成员风险管理
- Microsoft 365 E5/A5/G5 电子数据展示和审核
- Office 365 E5/A5/G5

对于 Microsoft 合作伙伴提供的Microsoft 365安全&amp;合规中心中的数据连接器，组织需要与合作伙伴建立业务关系，然后才能部署这些连接器。

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？

连接器是使用安全 &amp; 合规中心和连接器目录配置的。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用到获得服务许可的租户中的用户？

数据连接器服务是租户级值。 每个打算从此服务中受益的用户都必须获得许可。

## <a name="ediscovery"></a>电子数据展示

电子数据展示为公司内部的 IT 和法律部门提供了调查和电子数据展示解决方案，用于在将调查或诉讼导出Microsoft 365系统之前识别、收集、保存、减少和审查与调查或诉讼相关的内容。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中受益？

当用户被选为数据保管人时，用户将受益于Advanced eDiscovery (具有文档或电子文件管理控制权的人) 事例。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中受益的权限？

Exchange Online计划 2、Exchange Online Archiving、SharePoint联机计划 2、Microsoft 365 E5/A5/G5/E3/A3/G3、Office 365 E5/A5/G5/E3/A3/G3 和 F5 合规性和 F5 安全&符合性为用户提供从中受益的权限核心电子数据展示。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合规性和 F5 安全&合规性、Microsoft 365 E5/A5/G5 电子数据展示和审核以及Office 365 E5/A5/G5 为用户提供从Advanced eDiscovery中受益的权限。

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？

默认情况下，当管理员在安全&amp;合规中心分配电子数据展示权限时，租户级别会为租户中的所有用户启用Advanced eDiscovery功能。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用到获得服务许可的租户中的用户？

电子数据展示管理员可以通过使用Advanced eDiscovery中的内置保管人管理工具选择特定用户作为案例的数据保管人，如将[保管人添加到Advanced eDiscovery案例](/microsoft-365/compliance/add-custodians-to-case)中所述。

## <a name="information-barriers"></a>信息屏障

信息屏障是管理员可以配置的策略，以防止个人或组相互通信。 例如，如果一个部门正在处理不应与其他部门共享的信息，或者需要阻止一个组与外部联系人通信，则此操作非常有用。 信息屏障策略还可防止查找和发现。 这意味着，如果尝试与不应与之通信的人员通信，则不会在人员选取器中找到该用户。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中受益？

当用户被限制与他人通信时，他们可从信息屏障的高级符合性功能中受益。 可以定义信息屏障策略，以防止某些用户段与每个段通信，或允许特定段仅与某些其他段通信。 有关定义信息屏障策略的详细信息，请参阅 [“定义信息屏障策略](/microsoft-365/compliance/information-barriers-policies)”。 对于两个组无法相互通信的情况，这两个组中的用户都需要许可证才能从服务中受益 (请参阅下面的示例) 。<br><br>

| 应用场景 | Who需要许可证？ |
|:------|:------|
| Group1 和 Group2&nbsp;&nbsp; (两个组) 无法相互通信， (即，Group1&nbsp; 用户受限于与 Group2&nbsp; 用户通信，并且组&nbsp; 2 用户被禁止与 Group1&nbsp; 用户通信。 | Group1 和 Group2&nbsp;&nbsp; 中的用户 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中受益的权限？

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合规性和 F5 安全&合规性、Microsoft 365 E5/A5/G5 预览体验成员风险管理以及Office 365 E5/A5/G5，为用户提供从信息屏障中获益的权限。

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？

管理员在安全 &amp; 合规中心使用 PowerShell cmdlet 创建和管理信息屏障策略。 必须为管理员分配Microsoft 365 企业版全局管理员、Office 365全局管理员或合规性管理员角色才能创建信息屏障策略。 默认情况下，这些策略适用于租户中的所有用户。 有关信息屏障的详细信息，请参阅[Microsoft Teams中的信息屏障](/MicrosoftTeams/information-barriers-in-teams)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用到获得服务许可的租户中的用户？

管理员可以自定义工作负载)  (位置、包含的用户以及安全 &amp; 合规中心中排除的用户。 例如，如果所有用户都获得Office 365 E3许可，并且没有一个用户获得Office 365 高级合规版/E5 许可，则他们不需要为组织创建任何信息屏障策略。 有关详细信息，请参阅 [Teams](/MicrosoftTeams/information-barriers-in-teams)中的信息屏障。

## <a name="information-governance"></a>信息治理

信息治理通过发现、分类、标记和管理其数据来帮助组织管理其风险。 信息治理使组织能够满足业务和法规要求，并通过在其Microsoft 365和第三方数据中提供保留和删除功能来减少攻击面。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中受益？

用户能够将数据分类以用于保留，以维护特定的策略和法规，从而受益匪浅。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中受益的权限？

Microsoft 365 F3/业务高级版、Office 365 E5/A5/G5/E3/A3/G3/E1/A1/G1/G1/F3 和独立Exchange计划为用户提供了从手动将非记录保留标签应用于邮箱数据中获益的权限。

Microsoft 365 F3/F1/业务高级版、Office 365 E5/A5/G5/E3/A3/G3/F3/F3/E1/A1/G1 和独立SharePoint计划为用户提供了从手动将非记录保留标签应用于SharePoint或OneDrive中的文件中受益的权限。

Microsoft 365 E5/A5/G5/E3/A3/G3/业务高级版、Office 365 E5/A5/G5/G5/E3/A3/G3、Exchange计划 2，Exchange Online Archiving为用户提供从组织范围或位置范围的基本邮箱保留策略中受益的权限。

Microsoft 365 E5/A5/G5/E3/A3/G3、Office 365 E5/A5/G5/E3/A3/G3 和SharePoint计划 2 为用户提供从基本SharePoint或OneDrive保留策略中获益以及/或手动将非记录保留标签应用于文件的权限SharePoint或OneDrive。

组织可以使用保留策略根据其策略保留或删除Teams消息。 这包括管理Teams聊天和对话中的消息。

以下许可证为用户提供从Teams保留策略中受益的权限：

- Microsoft 365 E5/G5/a5/E3/G3/a3/F3/F1、商业基础、业务标准和业务高级版
- Office 365 E5/G5/A5/E3/G3/A3/F3/E1/G1

对于具有以下许可证的用户，支持的最低保留期或删除期为 30 天：

- Microsoft 365 F1/F3、Business Basic、Business Standard 和 Business 高级版
- Office 365 E1/G1 和 F3

Microsoft 365 E5/a5/G5、Microsoft 365 E5/a5/G5/F5 合规性和 F5 安全&合规性、Microsoft 365 信息保护和治理 E5/a5/G5 和Office 365 E5/A5 为用户提供从自动应用保留标签或策略、应用默认保留标签或策略、基于自定义事件开始保留标签的保留期、在标签的保留期结束时触发手动处置评审、通过本机数据连接器导入第三方数据、将文件声明为记录的权限， 发现已标记的内容，并监视标记活动。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合规性和 F5 安全&合规性、Microsoft 365 E5/A5/G5 信息保护和治理为用户提供基于可训练分类器自动应用保留标签的权限。

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？

默认情况下，在租户级别为租户中的所有用户启用信息治理功能。 有关配置信息治理以为许可用户应用自动标签和策略的信息，请参阅 [Microsoft 365 中的 Microsoft 信息治理](/microsoft-365/compliance/manage-information-governance)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用到获得服务许可的租户中的用户？

信息治理功能可应用于特定位置的许可用户 (团队网站、组网站等) 。 有关配置信息治理以为许可用户应用自动标签和策略的信息，请参阅 [Microsoft 365 中的 Microsoft 信息治理](/microsoft-365/compliance/manage-information-governance)。

## <a name="information-protection-customer-key-for-microsoft-365"></a>信息保护：用于Microsoft 365的客户密钥

借助客户密钥，可以控制组织的加密密钥，并将Microsoft 365配置为使用它们在 Microsoft 数据中心加密静态数据。 换句话说，客户密钥允许你使用自己的密钥添加属于你的加密层。 客户密钥通过Microsoft 365静态数据加密服务为多个[Microsoft 365工作负荷](/microsoft-365/compliance/customer-key-overview#about-data-encryption-policies)提供静态数据加密支持。 此外，客户密钥还提供SharePoint联机和OneDrive for Business数据的加密，以及Exchange Online邮箱级别的加密。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中受益？

用户通过使用自己的组织提供的、控制和管理的加密密钥在应用程序层加密其静态数据，从而从客户密钥中获益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中受益的权限？

Microsoft 365 E5/a5/G5、Microsoft 365 E5/a5/G5/F5 合规性、Microsoft 365 F5 安全&合规性、Microsoft 365 E5/a5/G5 信息保护和治理以及Office 365 E5/A5/G5 为用户提供从客户密钥中受益的权限。 若要获得客户密钥的全部权益，还必须拥有 Azure 密钥保管库订阅。

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？

[“设置客户密钥](/microsoft-365/compliance/customer-key-set-up)”一文介绍了创建和配置所需 Azure 资源所需的步骤，并提供了设置客户密钥的步骤。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用到获得服务许可的租户中的用户？

Microsoft 365提供多工作负荷加密支持的静态数据服务是租户级服务。 尽管某些未经许可的用户在技术上可能能够访问该服务，但任何你打算从服务中受益的用户都需要许可证。 若要Exchange Online邮箱级别加密，需要授权用户邮箱分配数据加密策略。

## <a name="information-protection-data-classification-analytics-overview-content-amp-activity-explorer"></a>信息保护：数据分类分析：概述内容&amp;活动资源管理器

数据分类分析功能在Microsoft 365 合规中心体验中可用。 概述显示了数字内容的位置以及最常见的敏感信息类型和标签。 内容资源管理器提供敏感数据的数量和类型的可见性，并允许用户按标签或敏感度类型进行筛选，以获取敏感数据存储位置的详细视图。 活动资源管理器显示与敏感数据和标签相关的活动，例如标签降级或外部共享，可能会使内容面临风险。

活动资源管理器提供了一个玻璃窗格，供管理员查看与最终用户正在使用的敏感信息相关的活动。 这些数据包括标签活动、数据丢失防护 (DLP) 日志、自动标记、终结点 DLP 等。

内容资源管理器使管理员能够为存储在受支持Microsoft 365工作负荷中的敏感文档编制索引，并识别它们存储的敏感信息。 此外，内容资源管理器还可帮助识别使用敏感度和保留标签分类的文档。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中受益？

信息保护和符合性管理员可以访问该服务，以获取对这些日志和索引数据的访问权限，以了解敏感数据的存储位置，以及哪些活动与此数据相关以及最终用户执行。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中受益的权限？

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合规性、Microsoft 365 F5 安全&合规性、Microsoft 365 E5/A5/G5 信息保护&amp;治理和Office 365 E5的许可用户可以受益于Microsoft 365数据分类分析。

Microsoft 365 E3/A3/G3 和 Office 365 E3/A3/G3 允许用户仅从内容资源管理器数据聚合中获益。

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？

默认情况下，租户级别为租户中的所有用户启用概述内容和活动资源管理器功能。 有关为许可用户配置数据分类分析的信息，请参阅：

- **内容资源管理器**：[使用内容资源管理器开始](/microsoft-365/compliance/data-classification-content-explorer)。
- **活动资源管理器**：[使用活动资源管理器开始](/microsoft-365/compliance/data-classification-activity-explorer)。
- **数据分类发行说明**： [数据分类发行说明](/microsoft-365/compliance/data-classification-overview#public-preview-release-notes)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用到获得服务许可的租户中的用户？

此功能需要适用于在符合性门户Microsoft 365积极使用解决方案的用户。

## <a name="information-protection-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>信息保护：针对Exchange Online、SharePoint联机和OneDrive for Business的数据丢失防护

通过Office 365数据丢失防护 (用于Exchange Online、SharePoint联机和OneDrive for Business的 DLP) ，组织可以识别、监视和自动保护电子邮件和文件 (（包括存储在Microsoft Teams中的文件）的敏感信息Microsoft Teams 文件存储库) 。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中受益？

当检查用户的电子邮件和文件是否存在敏感信息时，用户可从 DLP 中获得Exchange Online、SharePoint联机和OneDrive for Business，如组织 DLP 策略中配置的那样。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中受益的权限？

Microsoft 365 E3/A3/业务高级版、Office 365 E3/A3 以及Office 365数据丢失防护和 F5 合规性和 F5 安全&符合性为用户提供从Exchange Online的 Office 365 DLP 中受益的权限，SharePoint联机和OneDrive for Business。

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？

默认情况下，Exchange Online电子邮件、SharePoint站点和OneDrive帐户为租户中所有用户启用) 这些 DLP 功能 *(工作负荷的位置*。 有关使用 DLP 策略的详细信息，请参阅 [数据丢失防护概述](/microsoft-365/compliance/data-loss-prevention-policies)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用到获得服务许可的租户中的用户？

管理员可以自定义工作负载)  (位置，在 **“数据丢失防护** > **定位**”下将用户包括在安全&amp;合规中心，并排除用户。

## <a name="information-protection-data-loss-prevention-for-teams"></a>信息保护：针对Teams的数据丢失防护

使用用于Teams的通信 DLP，组织可以阻止包含敏感信息的聊天和频道消息，例如财务信息、个人身份信息、与健康相关的信息或其他机密信息。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中受益？

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/a5/G5/F5 合规性和 F5 安全&合规性
- Microsoft 365 E5/a5/g5 信息保护和治理
- Office 365 E5/A5/G5

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中受益？

发件人可从其传出聊天中的敏感信息和检查敏感信息的频道消息中受益，如组织 DLP 策略中配置的那样。

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？

默认情况下，Teams聊天和频道消息是针对租户中所有用户的这些 DLP 功能 *启用的位置 (工作负载)*。 有关使用 DLP 策略的详细信息，请参阅 [数据丢失防护概述](/office365/securitycompliance/data-loss-prevention-policies)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用到获得服务许可的租户中的用户？

管理员可以在 **“数据丢失防护** > **”** 下自定义工作负荷 (位置) 、包括用户以及安全&amp;合规中心内排除的用户。

## <a name="information-protection-double-key-encryption-for-microsoft-365"></a>信息保护：用于Microsoft 365的双键加密

用于Microsoft 365的双重密钥加密使你能够保护高度敏感的数据以满足专门的要求，并保持对加密密钥的完全控制。 双密钥加密使用两个密钥来保护数据，其中一个密钥在控件中，第二个密钥通过Microsoft Azure安全存储。 若要查看数据，必须有权访问这两个密钥。 由于 Microsoft 只能访问一个密钥，因此 Microsoft 无法访问密钥和数据，因此可确保你完全控制数据的隐私和安全性。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中受益？

用户能够将其加密的数据迁移到云，从而从双重密钥加密中受益，这会阻止第三方访问，前提是密钥仍由用户控制。 用户可以保护和使用双键加密的内容，类似于任何其他敏感度标签保护的内容。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中受益的权限？

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合规性和 F5 安全&合规性、Microsoft 365 E5/A5/G5 信息保护和治理、Office 365 E5/A5/G5 和 EMS E5 为用户提供从双重密钥加密中获益的权限。

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？

Double Key Encryption 支持桌面版本的 Windows Microsoft Office。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用到获得服务许可的租户中的用户？

若要将加密密钥分配给Office 365和/或Microsoft 365组织中的数据，请按照“双密钥加密”部署说明操作。

## <a name="information-protection-office-365-advanced-message-encryption"></a>信息保护：Office 365 高级邮件加密

Office 365 高级邮件加密可帮助客户履行合规性义务，这些义务要求对外部收件人进行更灵活的控制，以及对加密电子邮件的访问权限。 使用高级邮件加密，管理员可以通过使用自动策略来控制组织外部共享的敏感电子邮件，这些策略可以检测敏感信息类型 (例如个人标识信息或财务或运行状况 ID) ，或者他们可以通过应用自定义电子邮件模板并通过安全 Web 门户对加密电子邮件进行过期访问来使用关键字来增强保护。 此外，管理员可以通过随时撤消访问权限，进一步控制通过安全 Web 门户从外部访问的加密电子邮件。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中受益？

邮件发件人受益于对高级邮件加密提供的敏感电子邮件的额外控制。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中受益的权限？

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合规性和 F5 安全&合规性以及Microsoft 365 E5/A5/G5 信息保护和治理为用户提供从高级消息加密中受益的权限。

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？

管理员在 **Mail flowRules** >  下Exchange管理中心创建和管理高级邮件加密 **策略**。 默认情况下，这些规则适用于租户中的所有用户。 有关设置新的消息加密功能的详细信息，请参阅[设置新的Office 365消息加密功能](/office365/securitycompliance/set-up-new-message-encryption-capabilities)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用到获得服务许可的租户中的用户？

管理员应仅向许可用户应用高级邮件加密的邮件流规则。 有关定义邮件流规则的详细信息，请参阅[“定义邮件流规则”以加密Office 365中的电子邮件](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)。

## <a name="information-protection-office-365-message-encryption"></a>信息保护：Office 365消息加密

Office 365 邮件加密 (OME) 是一项基于 Azure 权限管理 (Azure RMS) 构建的服务，允许您向组织内外发送经加密的电子邮件，而无需考虑目标电子邮件地址（Gmail、Yahoo!Mail、Outlook.com 等）。

若要查看加密邮件，收件人可以使用一次性密码、通过 Microsoft 帐户登录或使用与 Office 365 关联的工作或学校帐户登录。 此外，收件人也可发送加密回复。 无需订阅即可查看加密邮件或发送加密答复。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中受益？

邮件发件人受益于对Office 365邮件加密提供的敏感电子邮件的额外控制。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中受益的权限？

- Microsoft 365 F3/E3/A3/G3/E5/A5/G5 和 Microsoft Business 高级版
- Office 365 A1/E3/A3/G3/E5/A5/G5
- Azure 信息保护计划 1 还提供组织在添加到以下计划时从Office 365消息加密中获益的权利：Exchange Online Kiosk、Exchange Online计划 1、Exchange Online计划 2、Office 365 F3、Microsoft 365 商业基础版、Microsoft 365 商业标准版 或 Office 365 企业版 E1

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？

管理员在 **Mail flowRules** >  下Exchange管理中心创建和管理Office 365邮件加密 **策略**。 默认情况下，这些规则适用于租户中的所有用户。 有关设置新的Office 365消息加密功能的详细信息，请参阅[设置新的消息加密功能](/office365/securitycompliance/set-up-new-message-encryption-capabilities)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用到获得服务许可的租户中的用户？

管理员应仅向许可用户应用邮件流规则以Office 365消息加密。 有关定义邮件流规则的详细信息，请参阅 [“定义邮件流规则”来加密电子邮件](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)。

## <a name="information-protection-sensitivity-labeling"></a>信息保护：敏感度标签

信息保护可帮助组织发现、分类、标记和保护敏感文档和电子邮件。 管理员可以定义规则和条件以自动应用标签，用户可以手动应用标签，或者可以使用这两个标签的组合，在其中向用户提供有关应用标签的建议。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中受益？

用户能够手动将敏感度标签应用于其内容或自动分类其内容，从而受益匪浅。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中受益的权限？

对于 **手动敏感度标签**，以下许可证提供用户权限：

- Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/商业高级版 (信息保护Office 365 - 如果仅分配了 E5 许可证，则应启用标准) 
- 企业移动性 + 安全性 E3/E5
- Office 365 E5/A5/E3/A3
- AIP 计划 1
- AIP 计划 2

对于 **客户端和服务端自动敏感度标记**，以下许可证提供用户权限：

- Microsoft 365 E5/A5/G5
- F5 和 E5 符合性
- F5 安全&合规性
- Microsoft 365 E5/a5/g5 信息保护和治理
- Office 365 E5

**对于仅限客户端自动敏感度标记**，以下许可证提供用户权限：

- 企业移动性 + 安全性 E5/A5/G5
- AIP 计划 2

若 **要在Power BI中应用和查看敏感度标签，并在数据从Power BI导出到Excel、PowerPoint或 PDF 时保护数据，** 以下许可证提供用户权限：

- Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business 高级版
- 企业移动性 + 安全性 E3/E5
- AIP 计划 1
- AIP 计划 2

有关用户如何从 [AIPService](/powershell/azure/aip/overview) PowerShell 模块中受益以管理 Azure 信息保护的 Azure Rights Management 保护服务的信息，请参阅 [Azure 信息保护](/powershell/azure/aip/overview)。

> [!NOTE]
>
> - Power BI包含在Microsoft 365 E5/A5/G5;在所有其他计划中，Power BI必须单独获得许可。
> - 有关基于机器学习的自动分类的用户权益信息， (可训练分类器) ，请参阅[信息治理](/office365/servicedescriptions/microsoft-365-service-descriptions/microsoft-365-tenantlevel-services-licensing-guidance/microsoft-365-security-compliance-licensing-guidance#information-governance)和/或[记录管理](/office365/servicedescriptions/microsoft-365-service-descriptions/microsoft-365-tenantlevel-services-licensing-guidance/microsoft-365-security-compliance-licensing-guidance#records-management)。

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？

默认情况下，在租户级别为租户中的所有用户启用信息保护功能。 有关为许可用户配置策略的信息，请参阅激活 Azure Rights Management。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用到获得服务许可的租户中的用户？

除了使用 AIP 扫描程序功能时，策略可以限于特定组或用户，并且可以编辑注册表以防止未经许可的用户运行分类或标记功能。

对于 AIP 扫描程序功能，Microsoft 不承诺向未获得许可的用户提供文件分类、标记或保护功能。

有关详细信息，请参阅[创建和发布敏感度标签](/microsoft-365/compliance/create-sensitivity-labels#publish-sensitivity-labels-by-creating-a-label-policy)并[了解 Azure 信息保护统一标记扫描程序](/azure/information-protection/deploy-aip-scanner)。

## <a name="insider-risk-management"></a>内部风险管理

预览体验成员风险管理是Microsoft 365中的一种解决方案，可让你检测、调查组织中的风险活动并采取措施，从而最大限度地降低内部风险。

自定义策略允许检测组织中的恶意和无意中风险活动并采取措施，包括根据需要将事例升级到 Microsoft Advanced eDiscovery。 组织中的风险分析师可以快速采取适当措施，确保用户符合组织的合规性标准。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中受益？

用户通过监视其活动以应对风险而受益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中受益的权限？

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合规性和 F5 安全&合规性以及Microsoft 365 E5/A5/G5 预览体验成员风险管理为用户提供从预览体验成员风险管理中受益的权限。

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？

必须在Microsoft 365 合规中心中创建预览体验成员风险管理策略并将其分配给用户。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用到获得服务许可的租户中的用户？

在Microsoft 365 合规中心中创建策略时，在 **“选择用户和组**”页上，**选择“选择用户或组**”以仅选择许可用户，或者，如果所有用户都获得许可，则可以选择 **“所有用户和启用邮件的组”** 复选框。 有关详细信息，请参阅[开始内部风险管理](/microsoft-365/compliance/insider-risk-management-configure)。

## <a name="microsoft-defender-for-business"></a>Microsoft Defender 商业版

Microsoft Defender 商业版是一种新的终结点安全解决方案，专为中小型企业设计， (多达 300 名员工) 。 借助此终结点安全解决方案，中小型企业 (SMB) 组织设备可以更好地抵御勒索软件、恶意软件、网络钓鱼和其他威胁。

有关详细信息，请参阅[Microsoft Defender 商业版](/microsoft-365/security/defender-business)。

### <a name="which-licenses-provide-the-rights-for-users-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中受益的权限？ 

Microsoft Defender 商业版包含在Microsoft 365 商业高级版许可证中。  

Defender for Business 的独立版本为预览版，将于今年晚些时候正式发布。 若要了解详细信息， [请参阅如何获取Microsoft Defender 商业版](/microsoft-365/security/defender-business/get-defender-business)。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中受益？

将Microsoft Defender 商业版添加到[Microsoft 365 商业高级版](https://techcommunity.microsoft.com/t5/small-and-medium-business-blog/new-security-solutions-to-help-secure-small-and-medium/ba-p/3207043)通过使用终结点检测和响应等技术添加跨平台终结点保护和复杂的勒索软件防御，增强了业务高级版现有的生产力和安全性产品/ 和自动调查和修正。

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？ 

默认情况下，租户级别为租户中的所有用户启用Microsoft Defender 商业版功能。 如果有Microsoft 365 商业高级版，可以通过[Microsoft 365 Defender门户](https://sip.security.microsoft.com/homepage)访问 Defender for Business。 

有关详细信息和指向更多资源的链接，请查看[Microsoft Defender 商业版常见问题解答](/microsoft-365/security/defender-business/get-defender-business)。

## <a name="microsoft-defender-for-cloud-apps"></a>Microsoft Defender for Cloud Apps

Microsoft Defender for Cloud Apps是一种云访问安全代理 (CASB) 解决方案，使客户能够灵活地实现核心功能和支持多种类型的部署。 Microsoft Defender for Cloud Apps是基于用户的订阅服务。 每个许可证是每个用户的每月许可证，可以作为独立产品或作为多个许可计划的一部分获得许可，如下所示。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中受益的权限？

Microsoft Defender for Cloud Apps作为独立许可证提供，也可作为以下计划的一部分使用：

- 企业移动性 + 安全性 E5
- Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 安全性
- Microsoft 365 E5/a5/G5/F5 符合性
- Microsoft 365 F5 安全性&amp;合 规
- Microsoft 365 信息保护和治理

Azure AD P1/P2 为用户提供从作为Defender for Cloud应用的一部分包含的发现功能中受益的权限。

若要受益于Defender for Cloud应用中的条件访问应用控制功能，用户还必须获得 Azure Active Directory P1 的许可，该功能包含在 企业移动性 + 安全性 F1/F3/E3/A3/G3 企业移动性 + 安全性 E5 中，Microsoft 365 E3/A3/G3、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 安全性和Microsoft 365 F5 安全&amp;合规性。

若要受益于自动客户端标签，必须为 Azure 信息保护 P2 授予许可，该 P2 包含在 企业移动性 + 安全性 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合规性、Microsoft 365 F5 安全&amp;性中符合性以及Microsoft 365 信息保护和治理。

> [!NOTE]
> 自动服务器端标记需要信息保护Office 365 - 高级版许可证 (`MIP_S_CLP2` 或 `efb0351d-3b08-4503-993d-383af8de41e3`) 。 有关参考，请参阅 [许可的Product 名称和服务计划标识符](/azure/active-directory/enterprise-users/licensing-service-plan-reference)。

有关详细信息，请参阅 [此处](https://aka.ms/defender-for-cloud-apps)。

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？

默认情况下，租户级别为租户中的所有用户启用Microsoft Defender for Cloud Apps功能。

有关为许可用户配置Defender for Cloud应用策略的信息，请参阅[此处](https://aka.ms/defender-for-cloud-apps)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用到获得服务许可的租户中的用户？

管理员可以使用服务中提供的范围内部署功能，将Microsoft Defender for Cloud Apps部署范围限定到许可用户。 有关详细信息，请参 [阅Scoped 部署](/cloud-app-security/scoped-deployment)。

### <a name="what-is-the-app-governance-add-on-feature-for-microsoft-defender-for-cloud-apps"></a>Microsoft Defender for Cloud Apps的应用治理加载项功能是什么？

应用治理是一种安全性和策略管理功能，可用作Microsoft Defender for Cloud Apps的附加功能。

通过应用治理，客户可以在Microsoft 365平台上监视和管理第三方和内部开发的应用，以帮助识别、发出警报，并防止有风险或未经批准的访问、权利或特权数据使用。 应用治理专为通过 [Microsoft 图形 API](/graph/use-the-api) 访问Microsoft 365数据的已启用 OAuth 的应用而设计。

应用治理为客户提供以下功能优势：

- **深度可见性和见解：**[更深入地了解](/microsoft-365/compliance/app-governance-visibility-insights-overview)可访问Microsoft 365数据的应用，以及有关如何在环境中配置和运行应用的可操作见解。
- **策略驱动的治理：** 根据组织对数据访问的安全性和合规性状况，对数据、用户和其他应用  [主动定义和强制实施适当的应用行为](/microsoft-365/compliance/app-governance-app-policies-overview)。
- **综合：**[检测和修正](/microsoft-365/compliance/app-governance-detect-remediate-overview)：使用机器学习模型检测异常应用行为，解决自动化和手动修正操作的问题。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中受益的权限？

应用治理可作为组织的加载项使用：

- Microsoft Defender for Cloud Apps (独立) 
- 企业移动性 + 安全性 E5/A5
- Microsoft 365 E5/A5
- Microsoft 365 安全中心
- Microsoft 365 合规 E5/A5 
- Microsoft 365 E5/A5 信息保护和治理
- Microsoft 365 F5 安全加载项
- Microsoft 365 F5 合规加载项
- Microsoft 365 F5 安全性 + 合规加载项

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？

默认情况下，在租户级别为租户中的所有用户启用应用治理。 有关详细信息，请参阅[应用治理Microsoft 365](/microsoft-365/compliance/app-governance-manage-app-governance)和[应用治理入门中的应用治理](/microsoft-365/compliance/app-governance-get-started)。

### <a name="is-it-a-requirement-for-the-apps-in-the-tenant-to-be-registered-with-azure-active-director-to-be-viewable-by-app-governance"></a>是否要求租户中的应用注册到 Azure Active Director 才能通过应用治理查看？

能。 应用必须注册到Azure AD，并且必须启用 OAuth 2.0。 目前不支持其他标识管理系统。 应用治理加载项功能监视使用 Microsoft 图形 API 的 Microsoft 365 OAuth 应用的行为和状态。 所有Microsoft 365 E5/A5 许可证都有Azure AD。

## <a name="microsoft-defender-for-endpoint"></a>Microsoft Defender for Endpoint

Microsoft Defender for Endpoint是一种终结点安全解决方案，其中包括：

- 基于风险的漏洞管理和评估
- 攻击面减少功能
- 基于行为和云支持的下一代保护
- 终结点检测和响应 (EDR) 
- 自动调查和修正
- 托管搜寻服务

有关详细信息，请参阅[Microsoft Defender for Endpoint](/microsoft-365/security/defender-endpoint/microsoft-defender-endpoint)。

### <a name="which-licenses-provide-the-rights-for-users-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中受益的权限？

**Microsoft Defender for Endpoint计划 1 (P1)**

Microsoft Defender for Endpoint P1 作为商业和教育客户的独立用户订阅许可证提供。 它还作为Microsoft 365 E3/A3 的一部分包含在内。

**Microsoft Defender for Endpoint计划 2 (P2)**

Microsoft Defender for Endpoint P2（以前称为Microsoft Defender for Endpoint）作为独立许可证和以下计划的一部分提供：

- Windows 11 企业版 E5/A5
- Windows 10 企业版 E5/A5
- Microsoft 365 E5/A5/G5 (，其中包括Windows 10或Windows 11 企业版 E5) 
- Microsoft 365 E5/A5/G5/F5 安全性
- Microsoft 365 F5 安全性&amp;合 规

**Microsoft Defender for Endpoint服务器**

对于服务器安全性，我们的英雄产品/服务Defender for Cloud。 它具有最佳和最合适的服务器和云保护功能，截至 2022 年 4 月，我们引入了 Microsoft Defender for Servers 计划 1，除了 Microsoft Defender for Servers 计划 2 (计划 2 最初是 Microsoft Defender for Servers) 。 有关详细信息，请阅读 [Microsoft Defender for Servers - 优势和功能|Microsoft Docs](/azure/defender-for-cloud/defender-for-servers-introduction)。

有关Microsoft Defender for Endpoint服务器条款和条件，请查看[产品条款](https://www.microsoft.com/licensing/terms/en-US/productoffering/MicrosoftDefenderforEndpointServer/EAEAS)中的信息。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中受益？

**Microsoft Defender for Endpoint 计划 1**

Microsoft Defender for Endpoint P1 提供核心终结点保护功能，例如下一代反恶意软件、攻击面减少规则、设备控制、终结点防火墙、网络保护等。 有关详细信息，请参阅[Microsoft Defender for Endpoint计划 1 和计划 2](/microsoft-365/security/defender-endpoint/defender-endpoint-plan-1-2)。

**Microsoft Defender for Endpoint 计划 2**

Microsoft Defender for Endpoint P2 提供全面的终结点保护功能，包括 Microsoft Defender for Endpoint P1 的所有功能，并提供其他功能，例如终结点检测和响应、自动调查和修正、危险和漏洞管理、威胁情报、沙盒和 Microsoft 威胁专家。 有关详细信息，请参阅[Microsoft Defender for Endpoint文档](/microsoft-365/security/defender-endpoint)。

**Microsoft Defender for Endpoint服务器**

Microsoft Defender for server 使用与 P2 Microsoft Defender for Endpoint一样的功能保护Windows和 Linux 服务器。

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？

默认情况下，租户级别为租户中的所有用户启用Microsoft Defender for Endpoint功能。 有关部署的信息，请参阅 [“部署”阶段](/microsoft-365/security/defender-endpoint/deployment-phases)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用到获得服务许可的租户中的用户？

Microsoft Defender for Endpoint管理员可以使用基于角色的访问控制 (RBAC) 在安全操作团队中创建角色和组，以授予对Microsoft Defender 安全中心的适当访问权限。 有关详细信息，请 [参阅使用基于角色的访问控制进行门户访问](/microsoft-365/security/defender-endpoint/rbac)。

## <a name="microsoft-defender-for-identity"></a>Microsoft Defender for Identity

Microsoft Defender for Identity (以前 Azure 高级威胁防护) 是一种云服务，可帮助保护企业混合环境免受多种类型的高级目标网络攻击和内部威胁。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中受益？

SecOp 分析师和安全专业人员受益于Microsoft Defender for Identity检测和调查高级威胁、泄露标识和恶意内部操作的能力。 最终用户通过Microsoft Defender for Identity监视其数据而受益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中受益的权限？

企业移动性 + 安全性 E5/A5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 安全、Microsoft F5 安全&合规性和用户Microsoft Defender for Identity提供从中受益的权限Microsoft Defender for Identity。

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？

默认情况下，租户级别为租户中的所有用户启用Microsoft Defender for Identity功能。  有关配置Microsoft Defender for Identity的信息，请参阅[“创建Microsoft Defender for Identity实例](/defender-for-identity/install-step1)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用到获得服务许可的租户中的用户？

Microsoft Defender for Identity服务当前无法将功能限制为特定用户。 必须为你打算受益的每个用户授予许可证。 请注意，如果一个用户在 Active Directory 中可能有多个帐户，例如不同域/林的不同管理帐户，则要求只有一个许可证。

同样，不需要许可服务帐户，也不要求使用任何有助于自动化的帐户。 只有人工用户才需要获得许可。

## <a name="microsoft-defender-for-office-365"></a>Microsoft Defender for Office 365

Microsoft Defender for Office 365 (以前Office 365高级威胁防护) 有助于保护组织免受网络钓鱼和零天恶意软件等复杂攻击。 Microsoft Defender for Office 365还通过关联来自各种数据的信号来提供可操作的见解，以帮助确定、确定优先级，并提供有关如何应对潜在威胁的建议。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中受益？

Microsoft Defender for Office 365可保护用户免受网络钓鱼和零天恶意软件等复杂攻击。 有关计划 1 和计划 2 中提供的服务的完整列表，请[参阅Microsoft Defender for Office 365](/microsoft-365/security/office-365-security/office-365-atp)。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中受益的权限？ 

Microsoft Defender for Office 365计划 1 和 2、Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 安全性、Microsoft 365 F5 安全&合规性以及Microsoft 365 商业高级版为用户提供从Microsoft Defender for Office 365中受益的权限。

此快速参考将帮助你了解每个Microsoft Defender for Office 365订阅附带的功能。 结合对 EOP 功能的了解，可以帮助业务决策者确定最适合需要的 Microsoft Defender for Office 365。

#### <a name="microsoft-defender-for-office-365-plan-1-vs-plan-2-cheat-sheet"></a>Microsoft Defender for Office 365计划 1 与计划 2 速查表

| Defender for Office 365 计划 1 | Defender for Office 365 计划 2 |
|---------|---------|
| 配置、保护和检测功能： <ul><li> 安全附件 </li><li> 安全链接 </li><li> 用于 SharePoint、OneDrive 和 Microsoft Teams 的安全附件 </li><li> Defender for Office 365 中的防钓鱼保护 </li><li> 实时检测 </li></ul> | Defender for Office 365 计划 1 功能 </br> --- + --- </br> 自动化、调查、补救措施和教育功能： <ul><li> 威胁跟踪器 </li><li> 威胁资源管理器 </li><li> 自动调查和响应 </li><li> 攻击模拟培训 </li></ul> |

有关详细信息，请转到[Office 365安全性，包括Microsoft Defender for Office 365和Exchange Online Protection - Office 365 |Microsoft Docs](/microsoft-365/security/office-365-security/overview)。

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？

默认情况下，租户级别为租户中的所有用户启用Microsoft Defender for Office 365功能。 有关为许可用户配置Microsoft Defender for Office 365策略的信息，请参阅[Microsoft Defender for Office 365](/microsoft-365/security/office-365-security/office-365-atp)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用到获得服务许可的租户中的用户？

若要Microsoft Defender for Office 365范围，请遵循保险箱链接和保险箱附件部署策略：

- 有关为许可用户配置保险箱链接的信息，请参阅[Microsoft Defender for Office 365中的保险箱链接](/microsoft-365/security/office-365-security/atp-safe-links)。

- 有关为许可用户配置保险箱附件的信息，请[参阅Microsoft Defender for Office 365中的保险箱附件](/microsoft-365/security/office-365-security/atp-safe-attachments)。

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp-and-for-teams-export"></a>Microsoft Graph API，用于Teams数据丢失防护 (DLP) 和Teams导出

这些 API 使开发人员能够生成安全性和合规性应用，这些应用可以“侦听”以近实时的方式Microsoft Teams消息，或者在 1：1/组聊天或Teams频道中导出团队消息。 这些 API 为客户和 ISV 启用 DLP 和其他信息保护和治理方案。 此外，Microsoft Graph修补程序 API 允许将 DLP 操作应用于Teams消息。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中受益？

[数据丢失防护 (DLP) ](/microsoft-365/compliance/dlp-microsoft-teams)功能广泛用于Microsoft Teams，尤其是在组织转向远程工作时。 如果你的组织具有 DLP，现在可以定义阻止用户在Microsoft Teams频道或聊天会话中共享敏感信息的策略。

信息保护和治理功能在Microsoft Teams中得到广泛使用，尤其是在组织转向远程工作时。 使用[Teams导出 API](/microsoftteams/export-teams-content)，可以将数据导出到第三方电子数据展示或合规性存档应用程序，以确保符合合规性做法。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中受益的权限？

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/a5/F5/G5 符合性
- Microsoft 365 E5/a5/g5 信息保护和治理
- Microsoft 365 F5 安全&合规性

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？

API 访问是在租户级别配置的。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用到获得服务许可的租户中的用户？

Microsoft Graph API for Teams DLP 和 Teams Export 提供租户级值。 每个打算从此服务中受益的用户都必须获得许可。 作为附加值，我们将添加每个许可用户的种子容量，按月计算，并在租户级别进行聚合。 对于超出种子容量的使用情况，将向应用所有者收取 API 使用费用。

有关种子容量和消耗费的详细信息，请参阅[访问聊天消息的Graph要求](/graph/teams-licenses)。

## <a name="microsoft-priva"></a>Microsoft Priva

[Microsoft Priva](https://aka.ms/privacymanagementdocs) 通过主动识别和防范隐私风险（如数据囤积、数据传输和数据过度共享、使信息工作者能够做出智能数据处理决策以及大规模自动化和管理主题请求）来帮助公司保护个人数据并构建隐私弹性工作场所。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中受益的权限？

Priva 可作为Office 365 A1/E1/A3/E3/A5/E5 和Microsoft 365 A3/E3/A5/E5 订阅的组织添加。 

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中受益？

用户能够让组织了解其环境中的私有数据，主动识别和防范隐私风险，以及管理 (通常称为“数据主体请求”) 的主题权利请求。

### <a name="how-can-customers-access-the-service"></a>客户如何访问该服务？

Priva 解决方案内置于[Microsoft 365 合规中心](https://compliance.microsoft.com/homepage)中，并在租户级别为租户中的所有用户启用。 我们建议为你打算从服务中受益和保护的任何用户获取许可证。

客户可以根据组织需求购买以下许可证：

**隐私管理 - 风险是 Priva 隐私风险管理的许可证名称。** 该服务允许组织：

- 了解Microsoft 365环境中的个人数据 (Microsoft Exchange Online、SharePoint、OneDrive for Business和Teams) 以及关联的风险。
- 利用默认隐私策略模板，包括数据最小化、数据过度呈现和数据传输，或自定义它们以满足你独特的组织需求。
- 接收建议的补救措施，以缓解隐私风险。
- 从生产力套件中与信息工作者互动，并推动行为更改。

**隐私管理 - 使用者权利请求是 Priva 使用者权利请求的许可证名称。** 该服务允许组织：

- 自动响应受限权限请求，并大规模管理它们。
- 将 Microsoft Power Automate 模板与现有业务流程配合使用 (需要适当的许可证才能Power Automate) 。
- 利用对 API 的编程访问。
- 通过Microsoft Teams集成与其他利益干系人安全协作 (需要适当的Microsoft Teams) 许可证。</br>

客户将能够在 1，10 或 100 个块中购买 Priva 主题权限请求。

隐私风险管理和 Priva 使用者权利请求可以独立购买。

请参阅获取隐私风险管理和 Priva 使用者权利请求所需的许可先决条件 [的产品条款](https://www.microsoft.com/licensing/terms/productoffering/Microsoft365/EAEAS) 。

## <a name="office-365-cloud-app-security"></a>Office 365 云应用安全

Office 365 云应用安全 (OCAS) 是Microsoft Defender for Cloud Apps的子集，其功能仅限于Office 365，对第三方云应用和 IaaS 服务没有额外的安全性。

OCAS 使组织能够了解其工作效率云应用和服务，提供复杂的分析来识别和应对网络威胁，并使他们能够控制数据&mdash;如何遍历Office 365。

若要比较功能，请参阅[Microsoft Defender for Cloud Apps和Office 365 云应用安全之间的差异](/cloud-app-security/editions-cloud-app-security-o365)。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中受益？

OCAS 发现影子 IT，提供跨Office 365的威胁防护，并可以控制哪些应用有权访问数据。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中受益的权限？

Office 365 E5/A3/A5/G5 为用户提供从 OCAS 中受益的权限。

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？

默认情况下，在租户级别为租户中的所有用户启用 OCAS 功能。

有关配置服务的信息，请参阅[Defender for Cloud应用的基本设置](/cloud-app-security/general-setup)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用到获得服务许可的租户中的用户？

管理员可以限制 OCAS 部署的范围，以强制执行某些应用的访问方式，并限制Office 365 云应用安全监视的用户组。 有关详细信息，请参阅 [作用域部署](/cloud-app-security/scoped-deployment)。

## <a name="office-365-customer-lockbox"></a>Office 365 客户密码箱

客户密码箱通过为客户提供为服务操作提供显式访问授权的能力，从而提供额外的控制层。 通过演示显式数据访问授权的过程已就绪，客户密码箱还可以帮助组织履行某些合规性义务，例如 HIPAA 和 FedRAMP。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中受益？

客户密码箱确保在未经客户明确批准的情况下，Microsoft 上的任何人都无法访问客户内容来执行服务操作。 客户密码箱将客户引入审批工作流，以便请求访问其内容。 有时，Microsoft 工程师会在支持过程中参与，以排查和解决客户报告的问题。 在大多数情况下，问题通过 Microsoft 为其服务提供的大量遥测和调试工具来解决。 但是，在某些情况下，可能需要 Microsoft 工程师访问客户内容，以确定根本原因并解决问题。 作为审批工作流程的最后一步，客户密码箱要求工程师向客户请求访问权限。 这为组织提供了批准或拒绝这些请求的选项，这使他们能够直接控制 Microsoft 工程师是否可以访问组织的最终用户数据。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中受益的权限？

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合规性和 F5 安全&合规性，Microsoft 365 E5/A5/G5 预览体验成员风险管理为用户提供从客户密码箱中受益的权限。

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？

管理员可以在Microsoft 365 管理中心中打开客户密码箱。 有关详细信息，请参阅[Office 365中的客户密码箱](/microsoft-365/compliance/customer-lockbox-requests)。 当客户密码箱处于打开状态时，Microsoft 需要在访问其任何内容之前获得组织的批准。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用到获得服务许可的租户中的用户？

目前，客户密码箱服务不能仅限于特定用户。 尽管租户服务目前无法限制特定用户的权益，但应努力限制许可用户的服务权益。 这将有助于避免目标功能可用后可能出现的服务中断。

## <a name="privileged-access-management-in-office-365"></a>Office 365 中的 Privileged Access Management

[特权访问管理 (PAM) ](/microsoft-365/compliance/privileged-access-management-configuration)为Office 365中的特权管理员任务提供精细的访问控制。 启用 PAM 后，若要完成提升的任务和特权任务，用户需要通过具有高度范围和时间限制的审批工作流请求实时访问权限。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中受益？

启用 PAM 可让组织以零常用权限运行。 用户可从增加的防御层中受益，以防范通过提供对其数据的不受约束访问的常设管理访问所产生的漏洞。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中受益的权限？ 

Office 365 E5/A5、Microsoft 365 E5/A5、Microsoft 365 E5/A5/F5 合规性和 F5 安全&合规性以及Microsoft 365 E5/A5 信息保护和治理为用户提供从 PAM 中受益的权限。

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？

默认情况下，在租户级别为租户中的所有用户启用 PAM 功能。 有关配置 PAM 策略的信息，请参阅[具有特权访问管理的开始](/microsoft-365/compliance/privileged-access-management-configuration)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用到获得服务许可的租户中的用户？

客户可以通过审批者组和访问策略（可应用于许可用户）按用户管理 PAM。 有关详细信息，请参阅 [Office 365 中的 Privileged 访问管理](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751)。

## <a name="records-management"></a>记录管理

记录管理通过在其Microsoft 365和第三方数据中发现、分类、标记、保留和可防御的删除功能，帮助组织履行业务和法规记录保存义务。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中受益的权限？

Microsoft 365 E5/a5/G5、Microsoft 365 E5/a5/G5/F5 合规性和 F5 安全&合规性、Microsoft 365 信息保护和治理 E5/a5/G5 和Office 365 E5/A5/G5 为用户提供从记录管理中受益的权利，包括将项目声明为记录或法规记录、自动应用保留或记录标签以及执行处置评审过程 (不包括基于可训练分类器自动应用保留标签) 。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5/F5 合规性和 F5 安全&符合性，Microsoft 365 信息保护和治理为用户提供基于可训练分类器自动应用保留或记录标签的权限。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中受益？

用户能够将内容声明为记录，并通过可防御的处置从策略定义和声明管理其完整记录过程，从而受益匪浅。

### <a name="how-is-the-service-provisioneddeployed"></a>如何预配/部署服务？

默认情况下，在租户级别为租户中的所有用户启用记录管理功能。 有关将记录管理配置为适用于许可用户的信息，[请参阅Microsoft 365中的记录管理。](/microsoft-365/compliance/records-management)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用到获得服务许可的租户中的用户？

记录管理功能可以应用于特定位置的许可用户 (团队网站、组网站等) 。 有关将记录管理配置为适用于许可用户的信息，[请参阅Microsoft 365中的记录管理。](/microsoft-365/compliance/records-management)
