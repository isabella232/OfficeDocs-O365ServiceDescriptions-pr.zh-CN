---
title: Microsoft 365 安全与合规&指南
ms.author: office365servicedesc
author: pamelaar
ms.reviewer: v-trscho
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 本文提供 Microsoft 365 合规性的许可指南，以帮助避免由于未授权访问而潜在的服务中断。
ms.openlocfilehash: 3e887ef28db0d6c806984170815c432d82573921
ms.sourcegitcommit: d45565d6573db8368c5fcff70c585559c77f3485
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 12/11/2020
ms.locfileid: "49654966"
---
# <a name="microsoft-365-licensing-guidance-for-security--compliance"></a>Microsoft 365 安全与合规&指南

出于本文的目的，租户级服务是一种联机服务，当为租户 (中任何用户单独购买或作为 &mdash; Office 365 或 Microsoft 365 计划的一部分时，) 会部分激活或完全激活租户中的 &mdash; 所有用户。 尽管某些未授权用户可能从技术上能够访问该服务，但任何打算从该服务中获益的用户都需要许可证。

> [!NOTE]
> 某些租户服务当前无法将权益限制到特定用户。 应努力将服务权益限制为许可用户。 这可帮助避免目标功能可用后组织的潜在服务中断。

若要查看自 2020 年 4 月 1 日起授权用户从 Microsoft 365 合规性功能中获益的选项，请下载详细的 Microsoft 365 合规性许可比较。 [ (PDF) ](https://www.microsoft.com/download/details.aspx?id=102403)  | [ (Excel) ](https://www.microsoft.com/download/details.aspx?id=102427)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory 标识保护

Azure Active Directory Identity Protection 是 Azure Active Directory Premium P2 计划的一项功能，可让你检测影响组织标识的潜在漏洞，配置对检测到的与组织标识相关的可疑操作自动响应，并调查可疑事件，并采取适当的措施解决这些问题。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

SecOps 分析员和安全专业人员从具有基于机器学习算法的已标记用户和风险事件的合并视图中获益。 最终用户受益于通过基于风险的条件访问提供的自动保护，以及通过对漏洞采取行动所提供的改进的安全性。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

拥有 E1 和 E3 许可证的客户只能访问默认的数据保护基线评估。 拥有 Office 365 E5/A5 和 Microsoft 365 E5/A5 许可证 (合规性、信息保护 & 治理以及电子数据展示和审核 SUS（包括) ）的客户将能够访问数据保护基线、GDPR、NIST 800-53 和 ISO 27001 开箱即用评估。 自定义评估功能及高级评估为 Office 365 E5/A5 和 Microsoft 365 E5/A5 客户保留。 高级评估将在 2021 上半年通过 VL、CSP 和 WebDirect 进行购买。 

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，在租户级别为租户内的所有用户启用 Azure AD Identity Protection 功能。 有关 Azure AD Identity Protection 的信息，请参阅 [什么是标识保护？](https://docs.microsoft.com/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

管理员可以分配定义密码重置级别的风险策略，并仅允许许可用户访问 Azure AD Identity Protection。 有关如何确定 Azure AD Identity Protection 部署范围的说明，请参阅如何 [配置和启用风险策略](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy)。

## <a name="azure-active-directory-identity-governance"></a>Azure Active Directory 标识治理

Azure Active Directory 身份治理允许你在组织对安全性和员工工作效率需求与正确的流程和可见性之间取得平衡。 它使用权利管理、访问评审、特权标识管理和使用条款策略，以确保合适的人员能够正确访问适当的资源。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

Azure Active Directory Identity Governance 通过更轻松地请求访问一个访问包中的应用、组和 Microsoft Teams，提高了用户的工作效率。 还可以将用户配置为审批者，无需管理员参与。 对于访问评审，用户可以使用智能建议查看组的成员身份，以便定期采取措施。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

企业移动性 + 安全性 E5/A5、Microsoft 365 E5/A5、Microsoft 365 E5/A5 安全和 Azure Active Directory Premium 计划 2 为用户提供了从 Azure Active Directory 标识治理中获益的权利。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

Azure AD Identity Governance 功能在租户级别启用，但按用户实现。 有关 Azure AD Identity Governance 的信息，请参阅 [什么是 Azure AD Identity Governance？](https://docs.microsoft.com/azure/active-directory/governance/identity-governance-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

管理员可通过仅向许可用户分配访问包、访问评审或特权标识管理，来界定 Azure AD 标识治理的范围。 有关如何确定 Azure AD 标识治理部署范围的说明，请参阅：

- [Azure AD 权利管理许可证要求](https://docs.microsoft.com/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Azure AD 访问评审许可证要求](https://docs.microsoft.com/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [使用 Privileged Identity Management 的许可证要求](https://docs.microsoft.com/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="microsoft-defender-for-identity"></a>Microsoft Defender for Identity

Microsoft Defender for Identity (以前是 Azure 高级威胁防护) 是一项云服务，可帮助保护企业混合环境免受多种类型的高级目标网络攻击和内部威胁。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

SecOp 分析师和安全专业人员受益于 Microsoft Defender for Identity 检测和调查高级威胁、泄露的身份和恶意内部操作的能力。 最终用户通过让 Microsoft Defender for Identity 监视其数据而受益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

企业移动性 + 安全性 E5/A5、Microsoft 365 E5/A5、Microsoft 365 E5/A5 安全性和适用于用户的 Microsoft Defender 提供从 Microsoft Defender for Identity 中获益的权利。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，在租户级别为租户内的所有用户启用 Microsoft Defender for Identity 功能。 有关配置 Azure ATP 的信息，请参阅 [创建 Microsoft Defender for Identity 实例](https://docs.microsoft.com/defender-for-identity/install-step1)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

Microsoft Defender for Identity 服务当前无法将功能限制到特定用户。 您必须许可希望受益的每个用户。

## <a name="microsoft-defender-for-office-365"></a>Microsoft Defender for Office 365

Microsoft Defender for Office 365 (以前称为 Office 365 高级威胁防护) 可帮助保护组织免受钓鱼和零日恶意软件等复杂攻击。 Microsoft Defender for Office 365 还通过关联来自各种数据的信号来提供可操作见解，以帮助确定潜在威胁，并确定其优先级并提供相关建议。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

Microsoft Defender for Office 365 可保护用户免受钓鱼和零日恶意软件等复杂攻击的攻击。 有关计划 1 和计划 2 中提供的服务的完整列表，请参阅[Microsoft Defender for Office 365。](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp)

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？ 

Microsoft Defender for Office 365 计划 1 和 2、Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 安全以及 Microsoft 365 商业高级版为用户提供从 Microsoft Defender for Office 365 中获益的权利。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，在租户级别为租户内的所有用户启用 Microsoft Defender for Office 365 功能。 有关为许可用户配置 Microsoft Defender for Office 365 策略的信息，请参阅[Microsoft Defender for Office 365。](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp)


### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

若要确定 Microsoft Defender for Office 365 的范围，请遵循安全链接和安全附件部署策略：

- 有关为许可用户配置安全链接的信息，请参阅 [Microsoft Defender for Office 365 中的安全链接](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)。

- 有关为许可用户配置安全附件的信息，请参阅 [Microsoft Defender for Office 365 中的安全附件](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments)。

## <a name="office-365-cloud-app-security"></a>Office 365 云应用安全

Office 365 Cloud App Security (OCAS) 是 Microsoft Cloud App Security 的子集，功能仅限于 Office 365，并且没有第三方云应用和 IaaS 服务的额外安全性。

OCAS 使组织能够了解其工作效率云应用和服务，提供复杂的分析，以识别和防御网络威胁，并让他们控制数据在 &mdash; Office 365 中的传输方式。

若要比较功能，请参阅 [Microsoft Cloud App Security 和 Office 365 Cloud App Security 之间的差异](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365)。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

OCAS 发现卷影 IT，跨 Office 365 提供威胁防护，并可以控制哪些应用有权访问数据。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Office 365 E5/A3/A5/G5 为用户提供从 OCAS 中获益的权利。
有关详细信息，请参阅 Microsoft [Cloud App Security 许可数据表](https://www.aka.ms/mcaslicensing)。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，在租户级别为租户内的所有用户启用 OCAS 功能。

有关配置服务的信息，请参阅 [云应用安全的基本设置](https://docs.microsoft.com/cloud-app-security/general-setup)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

管理员可以将 OCAS 部署的范围限定为强制访问某些应用，并限制由 Office 365 云应用安全监视的用户组。 有关详细信息，请参阅作用域 [部署](https://docs.microsoft.com/cloud-app-security/scoped-deployment)。

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) 是云访问安全代理 (CASB) 解决方案，让组织能够查看其云应用和服务，提供复杂的分析以识别和防御网络威胁，并让他们控制数据在任何云应用中的传输方式。 &mdash;

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

MCAS 发现和评估影子 IT，跨第一方和第三方云应用提供威胁防护，并保护第一方和第三方云应用的信息。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

MCAS、企业移动性 + 安全性 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 安全、Microsoft 365 E5/A5/G5 合规性和 Microsoft 365 信息保护和管理为用户提供从 MCAS 中获益的权利。

Azure AD P1 为用户提供了从 MCAS 中的发现功能中获益的权利。

若要从 MCAS 中的条件访问应用控制功能中获益，用户还必须获得 Azure Active Directory P1 的许可，该 P1 包含在企业移动性 + 安全性 E3/A3/G3、企业移动性 + 安全性 E5/A5/G5、Microsoft 365 E3/A3/G3、Microsoft 365 E5/A5/G5 和 Microsoft 365 E5/A5/G5 安全中。

若要从自动标记中获益，用户必须获得 Azure 信息保护 P2 的许可，该 P2 包含在企业移动性 + 安全性 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 合规性和 Microsoft 365 信息保护和管理中。

有关详细信息，请参阅 Microsoft [Cloud App Security 许可数据表](https://www.aka.ms/mcaslicensing)。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，在租户级别为租户内的所有用户启用 MCAS 功能。

有关为许可用户配置 Microsoft Cloud App Security 策略的信息，请参阅 [Microsoft Cloud App Security 概述](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

管理员可以使用服务中提供的范围部署功能将 MCAS 部署的范围范围缩小到许可用户。 有关详细信息，请参阅作用域 [部署](https://docs.microsoft.com/cloud-app-security/scoped-deployment)。

## <a name="compliance-manager"></a>合规性管理器

使用合规性管理器简化合规性并降低风险。 合规性管理器可帮助组织满足法规、标准、公司策略或其他所需控制框架的要求。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

以下是合规性管理器服务为用户提供的好处：

- 将复杂的法规、标准、公司策略或其他所需控制框架转换为简单语言
- 提供对大量开箱式评估和自定义评估库的访问权限，以满足独特的合规性需求
- 将监管控制措施映射到建议的改进操作
- 提供有关如何实施解决方案以满足法规要求的分步指南
- 通过将分数与每项操作关联，帮助用户确定对组织合规性影响最大的操作优先级

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

拥有 Office 365 E5/A5 和 Microsoft 365 E5/A5 许可证的客户将能够访问数据保护基线、GDPR、NIST 800-53 和 ISO 27001 开箱即用评估，以及使用自定义评估功能。 高级评估将在 2021 年上半年提供给 Office 365 E5/A5 和 Microsoft 365 E5/A5 客户购买。 它们可以通过 VL、CSP 和 WebDirect 进行购买。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，会为租户预配合规性管理器。 管理员设置用户权限并分配角色，以便组织中非管理员用户可以开始使用合规性管理器。 有关详细信息，请参阅合规性管理器入门 [：设置用户权限和分配角色](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

通过设置用户权限和分配角色控制对合规性管理器的访问。 有关详细信息，请参阅合规性管理器入门 [：设置用户权限和分配角色](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles)。

## <a name="microsoft-defender-for-endpoint"></a>Microsoft Defender for Endpoint

Microsoft Defender for Endpoint (以前是 Microsoft Defender ATP) 是一种终结点安全解决方案，包括基于风险的漏洞管理和评估;攻击面减少功能;基于行为和云的下一代保护;终结点检测和响应 (EDR) ;自动调查和修正;和托管搜寻服务。 有关详细信息 [，请参阅 Microsoft Defender for Endpoint](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) 页面。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中获益？

Windows 10 企业版 E5、Windows 10 教育版 A5、Microsoft 365 E5 (M365 E5) （包括 Windows 10 企业版 E5、Microsoft 365 E5 安全版、Microsoft 365 A5 (M365 A5) ）的许可用户可以从适用于终结点的 Microsoft Defender 中获益。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

SecOps 分析员和安全专业人员受益于 Microsoft Defender for Endpoint 的终结点安全性功能，以执行预防性保护、泄露后检测、自动调查和对高级威胁的响应。 最终用户通过 Microsoft Defender for Endpoint 监视恶意事件而受益。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，在租户级别为租户内的所有用户启用 Microsoft Defender for Endpoint 功能。 有关部署的信息，请参阅 [部署阶段](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/deployment-phases)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

适用于终结点的 Microsoft Defender 管理员可以使用基于角色的访问控制 (RBAC) 在安全操作团队内创建角色和组，以授予对 Microsoft Defender 安全中心的适当访问权限。 有关详细信息，请参阅使用基于角色 [的访问控制管理门户访问](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/rbac)。

## <a name="information-protection"></a>信息保护

信息保护可帮助组织发现、分类、标记和保护敏感文档和电子邮件。 管理员可以定义规则和条件以自动应用标签，用户可以手动应用标签，或结合使用这两者，其中为用户提供了应用标签的建议。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

用户通过能够手动将敏感度标签应用于其内容或自动对内容进行分类而受益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium、企业移动性 + 安全性 F3/E3/E5、Office 365 E5/A5/E3/A3/F3、AIP 计划 1 和 AIP 计划 2 为用户提供了从手动敏感度标签中获益的权利。

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium、企业移动性 + 安全性 F3/E3/E5、AIP 计划 1 和 AIP 计划 2 为用户提供了在 Power BI 中应用和查看敏感度标签的好处，并保护从 Power BI 导出到 Excel、PowerPoint 或 PDF 时的数据。 

> [!NOTE]
> Power BI 包含在 Microsoft 365 E5/A5/G5 中;在所有其他计划中，必须单独许可 Power BI。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 合规性、Microsoft 365 信息保护和治理、Office 365 E5、Office 365 高级合规性、企业移动性 + 安全性 E5 和 AIP 计划 2 为用户提供了从自动敏感度标签中获益的权利。

有关按许可证授予的特定权限，请参阅详细的 Microsoft 365 合规性许可比较。 [ (PDF) ](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [ (Excel) ](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)不包括基于机器学习和可训练分类器 (自动分类) 。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，在租户级别为租户内的所有用户启用信息保护功能。 有关为许可用户配置策略的信息，请参阅"激活 Azure 权限管理"。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

除非使用 AIP 扫描程序功能，否则可以将策略的范围缩小到特定组或用户，并可以编辑注册表以防止未经授权的用户运行分类或标记功能。 有关如何确定 AIP 部署范围的说明，请参阅 [配置 Azure 信息保护策略](https://docs.microsoft.com/azure/information-protection/configure-policy)。

对于 AIP 扫描程序功能，Microsoft 不承诺向未获得许可的用户提供文件分类、标记或保护功能。

## <a name="information-governance"></a>信息治理

信息治理通过发现、分类、标记和管理数据来帮助组织管理其风险。 利用信息治理，组织可以跨 Microsoft 365 和第三方数据提供保留和删除功能，满足业务和法规要求，并减少攻击面。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

用户通过能够对数据进行分类以保留特定策略和法规而受益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Microsoft 365 F3/Business Premium、Office 365 E1/A1/F3 和独立 Exchange 计划为用户提供了从手动将非记录保留标签应用于邮箱数据中获益的权限。

Microsoft 365 F3/F1/Business Premium、Office 365 E1/A1/F3 和独立 SharePoint 计划为用户提供了从手动将非记录保留标签应用于 SharePoint 或 OneDrive 中的文件的好处。 

Microsoft 365 E5/A5/E3/A3/Business Premium、Office 365 E5/A5/E3/A3、Exchange 计划 2 和 Exchange Online Archiving 为用户提供从组织范围或位置范围的基本邮箱保留策略中获益和/或手动将非记录保留标签应用于邮箱数据的权限。

Microsoft 365 E5/A5/E3/A3、Office 365 E5/A5/E3/A3 和 SharePoint 计划 2 为用户提供了从基本 SharePoint 或 OneDrive 保留策略中获益和/或手动将非记录保留标签应用于 SharePoint 或 OneDrive 中的文件的权利。

Microsoft 365 E5/A5/E3/A3 和 Office 365 E5/A5/E3/A3 为用户提供从 Teams 保留策略中获益的权利。

Microsoft 365 E5/A5、Microsoft 365 E5/A5 合规性、Microsoft 365 信息保护和治理、 Office 365 E5/A5 和 Office 365 高级合规性为用户提供了从自动应用保留标签或策略、应用默认保留标签或策略、基于自定义事件开始保留标签的保留期、在标签保留期结束时触发手动处置评审、通过本机数据连接器导入第三方数据、声明文件记录、发现标记内容以及监视标签活动的权利。

Microsoft 365 E5/A5、Microsoft 365 E5/A5 合规性、Microsoft 365 信息保护和治理为用户提供了从基于可训练分类器自动应用保留标签中获益的权利。

有关按许可证授予的特定权限，请参阅详细的 Microsoft 365 合规性许可比较。 [ (PDF) ](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [ (Excel) ](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，在租户级别为租户内的所有用户启用信息治理功能。 有关配置信息治理以对许可用户应用自动标签和策略的信息，请参阅 [Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance)中的 Microsoft 信息治理。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

可以将信息治理功能应用于特定位置的许可用户 (网站、组网站等) 。 有关配置信息治理以对许可用户应用自动标签和策略的信息，请参阅 [Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance)中的 Microsoft 信息治理。

## <a name="records-management"></a>记录管理

记录管理通过跨 Microsoft 365 和第三方数据发现、分类、标记、保留和防御删除功能，帮助组织履行业务和监管记录保留义务。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Microsoft 365 E5/A5、Microsoft 365 E5/A5 合规性、Microsoft 365 信息保护和治理、Office 365 E5/A5、Office 365 高级合规性为用户提供了从记录管理中获益的权利，包括将项目声明为记录、自动应用保留或记录标签和执行处置评审流程 (排除基于可训练分类器) 自动应用保留标签。

Microsoft 365 E5/A5、Microsoft 365 E5/A5 合规性、Microsoft 365 信息保护和治理为用户提供了从基于可训练分类器自动应用保留标签或记录标签中获益的权利。

有关按许可证授予的特定权限，请参阅详细的 Microsoft 365 合规性许可比较。 [ (PDF) ](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [ (Excel) ](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

用户可以通过将内容声明为记录并通过防御性处置从策略定义和声明管理其完整记录过程而受益。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，在租户级别为租户内的所有用户启用记录管理功能。 有关配置记录管理以应用于许可用户的信息，请参阅了解 [Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/records-management)中的记录管理。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

记录管理功能可应用于特定位置的许可用户 (网站、组网站等) 。 有关配置记录管理以应用于许可用户的信息，请参阅了解 [Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/records-management)中的记录管理。

## <a name="data-connectors"></a>数据连接器 

Microsoft 提供可在 Microsoft 365 合规中心配置的第三方数据连接器。 有关 Microsoft 提供的数据连接器列表，请参阅第三方 [数据](https://docs.microsoft.com/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) 连接器表。 此表还汇总了在 Microsoft 365 中导入和存档数据后可应用于第三方数据的合规性解决方案，以及指向每个连接器的分步说明的链接。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

使用数据连接器在 Microsoft 365 中导入和存档第三方数据的主要好处是，可以在导入数据后对数据应用各种 Microsoft 365 合规性解决方案。 这有助于确保组织的非 Microsoft 数据符合影响组织的法规和标准。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

以下许可证为用户提供了从数据连接器中获益的权利：

- Microsoft 365 E5/A5
- Microsoft 365 E5/A5 信息保护&管理
- Microsoft 365 E5/A5 合规性
- Microsoft 365 E5/A5 内部风险管理
- Microsoft 365 E5/A5 电子数据展示和审核
- Office 365 E5/A5
- Office 365 高级合规版

对于 Microsoft 合作伙伴提供的 M365 安全与合规中心&连接器，贵组织需要与合作伙伴建立业务关系，然后才能部署这些连接器。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

连接器使用安全与合规中心&连接器目录进行配置。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

数据连接器服务是租户级别的值。 每位打算从此服务中获益的用户都必须获得许可。

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp"></a>用于 Teams 数据丢失防护和 DLP (Microsoft Graph API) 

今年较早时，我们宣布对 Teams 中的消息公开预览版 Microsoft Graph 更改[通知 API。](https://go.microsoft.com/fwlink/?linkid=2143888) 此 API 允许开发人员构建应用，这些应用可以近实时地收听 Microsoft Teams 消息，并启用客户和 ISV 的 DLP 方案实现。 此外，Microsoft Graph 修补程序 API 允许将 DLP 操作应用于 Teams 消息。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

[数据丢失防护 (DLP) ](https://docs.microsoft.com/microsoft-365/compliance/dlp-microsoft-teams) 功能在 Microsoft Teams 中广泛使用，尤其是在组织转移到远程工作时。 如果你的组织具有 DLP，你现在可以定义防止用户共享 Microsoft Teams 频道或聊天会话中的敏感信息的策略。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

你需要以下 E5 许可证之一，才能在 Teams 聊天中获取 DLP 保护支持：

- Microsoft 365 E5/A5
- Microsoft 365 E5/A5 合规性
- Microsoft 365 E5/A5 信息保护和治理
- Office 365 E5/A5 

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

API 访问在租户级别配置。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

适用于 Teams DLP 的 Microsoft Graph API 是租户级值。 每位打算从此服务中获益的用户都必须获得许可。

## <a name="ediscovery"></a>电子数据展示

电子数据展示为公司内的 IT 和法律部门提供调查和电子数据展示解决方案，以在从 Microsoft 365 系统导出之前识别、收集、保留、减少和查看与调查或诉讼相关的内容。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

如果用户被选择为数据保管人， (对文档或电子文件进行管理控制) 案例时，用户受益于高级电子数据展示。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Microsoft 365 E5/A5/G5/E3/A3/G3、Office 365 E5/A5/G5/E3/A3/G3 和 Office 365 高级合规性为用户提供了从核心电子数据展示中获益的权利。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 合规性、Microsoft 365 E5/A5 电子数据展示和审核、Office 365 E5/A5/G5 和 Office 365 高级合规性为用户提供从高级电子数据展示中获益的权利。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，当管理员在安全与合规中心分配电子数据展示权限时，租户内的所有用户在租户级别&电子数据展示功能。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

电子数据展示管理员可以使用高级电子数据展示中的内置保管人管理工具选择特定用户作为案例的数据保管人，如"向高级电子数据展示案例添加保管人"[中所述。](https://docs.microsoft.com/microsoft-365/compliance/add-custodians-to-case)

## <a name="office-365-customer-key"></a>Office 365 客户密钥

使用客户密钥，可以控制组织的加密密钥，并配置 Office 365 以使用它们加密 Microsoft 数据中心中的静态数据。 换句话说，客户密钥允许你使用你自己的密钥添加属于你的加密层。 其余数据包括存储在邮箱中的 Exchange Online 和 Skype for Business 数据，以及 SharePoint Online 和 OneDrive for Business 中的文件。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

用户可以通过使用由其自己的组织提供的、控制和管理的加密密钥在应用程序层加密静态数据，从客户密钥中获益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Microsoft 365 E5/A5、Microsoft 365 E5/A5 合规性、Microsoft 365 信息保护和治理、Office 365 E5/A5 和 Office 365 高级合规性为用户提供了从客户密钥中获益的权利。 若要充分利用客户密钥，还必须订阅 Azure 密钥保管库。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

可以针对存储在 Exchange Online 和 Skype for Business 邮箱以及 SharePoint Online、OneDrive for Business 和 Teams 文件的所有数据启用 Office 365 客户密钥加密密钥。 有关 Office 365 客户密钥（包括如何开始使用）详细信息，请参阅"使用客户密钥[的服务加密"。](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

对于 Exchange Online 和 Skype for Business，可以使用客户密钥对邮箱进行加密。 必须先设置 Azure，然后才能使用 Office 365 的客户密钥。 请参阅 ["设置客户密钥](https://docs.microsoft.com/microsoft-365/compliance/customer-key-set-up) "，了解创建和配置所需的 Azure 资源所需的步骤，以及设置 Office 365 中的客户密钥的步骤。 完成 Azure 设置后，确定要分配给组织中邮箱和文件的策略以及要分配的密钥。 未为其分配策略的邮箱和文件将使用由 Microsoft 控制和管理的加密策略。 有关客户密钥或一般概述，请参阅使用客户密钥 [的服务加密](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview)。

## <a name="office-365-customer-lockbox"></a>Office 365 客户密码箱

客户密码箱通过为客户提供为服务操作提供显式访问授权的能力，提供了一层额外的控制。 通过证明已制定显式数据访问授权过程，客户密码箱还可以帮助组织履行某些合规性义务，如 HIPAA 和 FEDRAMP。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

客户密码箱可确保未经客户明确批准，Microsoft 中没有人可以访问客户内容以执行服务操作。 客户密码箱将客户引入对访问其内容的请求的审批工作流。 有时，Microsoft 工程师会在支持过程中参与排查和修复客户报告的问题。 在大多数情况下，问题通过 Microsoft 已针对其服务提供的广泛遥测和调试工具来修复。 但是，在某些情况下，可能要求 Microsoft 工程师访问客户内容以确定根本原因并解决该问题。 客户密码箱要求工程师请求客户访问，作为审批工作流的最后一步。 这为组织提供了批准或拒绝这些请求的选项，这使组织可以直接控制 Microsoft 工程师是否可以访问组织的最终用户数据。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 合规性、Microsoft 365 Insider Risk Management 和 Office 365 高级合规性为用户提供从客户密码箱中获益的权利。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

管理员可以在 Microsoft 365 管理中心中打开客户密码箱。 有关详细信息，请参阅 [Office 365 中的客户密码箱](https://docs.microsoft.com/microsoft-365/compliance/customer-lockbox-requests)。 当客户密码箱打开时，Microsoft 需要先获得组织的批准，才能访问其任何内容。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

目前，客户密码箱服务不能限制为特定用户。 您必须许可希望受益的每个用户。

## <a name="privileged-access-management-in-office-365"></a>Office 365 中的 Privileged Access Management

[PAM (Privileged ](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration) access management) 提供对 Office 365 中特权管理员任务的精细访问控制。 启用 PAM 后，若要完成提升和特权任务，用户将需要通过范围和时间高度限制的审批工作流请求实时访问。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

启用 PAM 可让组织以零长期特权运行。 用户受益于针对长期管理访问引发的漏洞的附加防御层，该访问提供对数据不受限制的访问。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？ 

Office 365 E5/A5、Microsoft 365 E5/A5、Microsoft 365 E5/A5 合规性和 Microsoft 365 E5/A5 信息保护和治理为用户提供了从 PAM 受益的权利。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，在租户级别为租户内的所有用户启用 PAM 功能。 有关配置 PAM 策略的信息，请参阅 [特权访问管理入门](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

客户可以通过审批者组和访问策略（可应用于许可用户）按用户管理 PAM。 有关详细信息，请参阅 [Office 365 中的 Privileged 访问管理](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751)。

## <a name="double-key-encryption-for-microsoft-365"></a>Microsoft 365 的双密钥加密 

通过 Microsoft 365 的双密钥加密，你可以保护高度敏感的数据，以满足专门的要求并保持对加密密钥的完全控制。 双密钥加密使用两个密钥来保护数据，其中一个密钥在你的控件中，另一个密钥由 Microsoft Azure 安全存储。 若要查看数据，您必须具有这两个键的访问权限。 由于 Microsoft 只能访问一个密钥，因此你的密钥和数据对 Microsoft 不可用，从而确保你可以完全控制数据的隐私和安全性。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

用户可以将其加密数据迁移到云，从而受益于双密钥加密，只要密钥仍控制用户，就可以阻止第三方访问。 用户可以保护和使用双密钥加密内容，类似于任何其他敏感度标签受保护内容。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Microsoft 365 E5/A5、Microsoft 365 E5/A5 合规性、Microsoft 365 信息保护和治理、Office 365 E5/A5 和 Office 365 高级合规性为用户提供了从双密钥加密中获益的权利。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

双密钥加密支持适用于 Windows 的桌面Microsoft Office版本。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

若要为许可用户向 Office 365 和/或 Microsoft 365 组织内的数据分配加密密钥，请按照双密钥加密部署说明操作。

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Exchange Online、SharePoint Online 和 OneDrive for Business 的 Office 365 数据丢失防护

借助 Office 365 数据丢失防护 (DLP) for Exchange Online、SharePoint Online 和 OneDrive for Business，组织可以识别、监视和自动保护电子邮件和文件之间的敏感信息 (包括存储在 Microsoft Teams 文件存储库中的文件) 。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

当用户的电子邮件和文件被检查是否有敏感信息时（如组织的 DLP 策略中配置）时，用户受益于适用于 Exchange Online、SharePoint Online 和 OneDrive for Business 的 DLP。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Microsoft 365 A1/E3/A3/Business、Office 365 E3/A3 和 Office 365 数据丢失防护为用户提供了从适用于 Exchange Online、SharePoint Online 和 OneDrive for Business 的 Office 365 DLP 中获益的权利。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，Exchange Online 电子邮件、SharePoint 网站和 OneDrive 帐户启用位置 (*租户*) 中所有用户的这些 DLP 功能启用工作负载。 有关使用 DLP 策略的信息，请参阅 [数据丢失防护概述](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

管理员可以自定义安全 (位置下的) 安全与合规中心内&包括的用户和排除  >  **的用户**。

## <a name="communication-data-loss-prevention-for-teams"></a>Teams 的通信数据丢失防护

借助适用于 Teams 的通信 DLP，组织可以阻止包含敏感信息（如财务信息、个人身份信息、运行状况相关信息或其他机密信息）的聊天和频道消息。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中获益？

Office 365 E5/A5、Microsoft 365 E5/A5、Microsoft 365 信息保护和治理以及 Office 365 高级合规性的许可用户可以从 Teams 通信 DLP 中获益。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

发件人通过检查其传出聊天中的敏感信息和频道消息来检查敏感信息，如组织的 DLP 策略中配置。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，Teams 聊天和频道消息是租户 (*所有用户*) DLP 功能的启用位置和工作负载。 有关使用 DLP 策略的信息，请参阅 [数据丢失防护概述](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

管理员可以自定义安全 (位置下的) 安全与合规中心内&包括的用户和排除  >  **的用户**。

## <a name="information-barriers"></a>信息屏障

信息屏障是管理员可以配置以防止个人或组相互通信的策略。 例如，如果一个部门处理不应与其他部门共享的信息，或者需要阻止组与外部联系人通信，这将非常有用。 信息屏障策略还会阻止查找和发现。 这意味着，如果你尝试与不应通信的人通信，你将在人员选取器中找不到该用户。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

当用户受限于与其他用户通信时，他们受益于信息屏障的高级合规性功能。 例如：<br><br>

| 方案 | 谁需要许可证？ |
|:------|:------|:------|
| 组 1 和组 2) 的两个组无法相互通信 (即组 1 用户受限，不能与组 2 用户通信，组 2 用户不能与组 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 1 用户通信。 ( | 组 &nbsp; 1 和组 &nbsp; 2 中的用户 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Microsoft 365 E5/A5、Microsoft 365 E5/A5 合规性、Microsoft 365 Insider Risk Management、Office 365 E5/A5 和 Office 365 高级合规性为用户提供了从信息屏障中获益的权利。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

管理员使用安全与合规中心中的 PowerShell cmdlet 创建和管理&策略。 管理员必须分配有 Microsoft 365 企业版全局管理员、Office 365 全局管理员或合规性管理员角色，才能创建信息屏障策略。 默认情况下，这些策略适用于租户中的所有用户。 有关信息屏障的信息，请参阅 Microsoft [Teams 中的信息屏障](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

管理员可以在安全 () 中自定义&用户和排除&位置。 例如，如果所有用户都获得 Office 365 E3 许可，并且没有获得 Office 365 高级合规性/E5 许可，则他们无需为组织创建任何信息屏障策略。 有关详细信息，请参阅 [Microsoft Teams 中的信息屏障](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)。

## <a name="office-365-message-encryption"></a>Office 365 邮件加密

Office 365 邮件加密 (OME) 是一项基于 Azure 权限管理 (Azure RMS) 构建的服务，允许您向组织内外发送经加密的电子邮件，而无需考虑目标电子邮件地址（Gmail、Yahoo!Mail、Outlook.com 等）。

若要查看加密邮件，收件人可以使用一次性密码、通过 Microsoft 帐户登录或使用与 Office 365 关联的工作或学校帐户登录。 此外，收件人也可发送加密回复。 他们无需订阅来查看加密邮件或发送加密回复。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

邮件发件人受益于对 Office 365 邮件加密提供的敏感电子邮件的新增控制。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Microsoft 365 E3/A3、Office 365 E3/A3 和 Azure 信息保护计划 1 为用户提供了从 Office 365 邮件加密中获益的权利。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

管理员在 Exchange 管理中心的"邮件流规则"下创建和管理 Office 365 **邮件加密**  >  **策略**。 默认情况下，这些规则适用于租户中的所有用户。 有关设置新的 Office 365 邮件加密功能的信息，请参阅["设置新的邮件加密功能"。](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

管理员应仅将 Office 365 邮件加密的邮件流规则应用于许可用户。 有关定义邮件流规则的信息，请参阅 ["定义邮件流规则"以加密电子邮件](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)。

## <a name="office-365-advanced-message-encryption"></a>Office 365 高级邮件加密

Office 365 高级邮件加密帮助客户履行合规性义务，这些义务要求对外部收件人及其对加密电子邮件的访问进行更灵活的控制。 通过高级邮件加密，管理员可以使用可检测敏感信息类型 (（例如，个人标识信息或财务或运行状况标识) ）的自动策略来控制在组织外部共享的敏感电子邮件，或者，他们可以使用关键字通过应用自定义电子邮件模板并通过安全 Web 门户使对加密电子邮件的访问过期来增强保护。 此外，管理员还可随时通过撤销访问权限，进一步控制通过安全 Web 门户在外部访问的加密电子邮件。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

邮件发件人受益于高级邮件加密提供的对敏感电子邮件的新增控制。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Office 365 E5/A5、Microsoft 365 E5/A5、Microsoft 365 E5/A5 合规性、Microsoft 365 信息保护和治理以及 Office 365 高级合规性为用户提供了从高级邮件加密中获益的权利。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

管理员在 Exchange 管理中心的"邮件流规则"下创建 **和管理高级邮件加密**  >  **策略**。 默认情况下，这些规则适用于租户中的所有用户。 有关设置新邮件加密功能的信息，请参阅["设置新的 Office 365 邮件加密功能"。](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

管理员应仅将高级邮件加密的邮件流规则应用于许可用户。 有关定义邮件流规则的信息，请参阅["定义邮件流规则以加密 Office 365 中的电子邮件"。](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)

## <a name="communication-compliance"></a>通信合规性

Microsoft 365 中的通信合规性可帮助你检测、捕获和采取针对组织中不当邮件的修正操作，从而最大限度地降低通信风险。 你可以定义捕获组织中内部和外部电子邮件、Microsoft Teams 或第三方通信的特定策略。 审阅者可以采取适当的修正措施，以确保他们符合组织的邮件标准。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

合规性专家通过让组织通信受通信合规性策略监控，从服务中获益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Office 365 E5/A5、Microsoft 365 E5/A5、Microsoft 365 E5/A5 合规性和 Microsoft 365 内部风险管理为用户提供了从通信合规性中获益的权利。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

管理员和合规性专家在 Microsoft 365 合规中心创建通信合规性策略。 这些策略定义组织中需要审阅的通信和用户，定义通信必须满足的自定义条件，并指定应执行审阅的用户。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

管理员选择要包括在通信合规性策略中的特定用户或组。 选择组时，他们还可以选择要从通信合规性策略中排除的组中特定用户。 有关通信合规性策略详细信息，请参阅 [Microsoft 365 中的通信合规性入门](https://docs.microsoft.com/microsoft-365/compliance/communication-compliance-configure)。

## <a name="insider-risk-management"></a>内部风险管理

内部风险管理是 Microsoft 365 中的一种解决方案，它通过让你检测、调查和对组织中存在风险的活动采取行动，帮助最大限度地降低内部风险。

自定义策略允许你检测组织中恶意和无意间存在风险的活动并采取措施，包括根据需要将事例升级到 Microsoft 高级电子数据展示。 您组织的风险分析员可以快速采取适当的措施，以确保用户符合组织的合规性标准。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

用户通过监视其活动来防范风险而受益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供从服务中获益的权利？

Microsoft 365 E5/A5、Microsoft 365 E5/A5 合规性和 Microsoft 365 内部风险管理为用户提供了从内部风险管理中获益的权利。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

必须在 Microsoft 365 合规中心创建内部风险管理策略并将其分配给用户。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

在 Microsoft 365 合规中心内创建策略时，在"选择用户和组"页上，选择"选择用户或组"以仅选择许可用户，或者，如果所有用户都获得许可，您可以选择"所有用户和启用邮件 **的** 组"复选框。 有关详细信息，请参阅 [内部风险管理入门](https://docs.microsoft.com/microsoft-365/compliance/insider-risk-management-configure)。

## <a name="conditional-access-policies"></a>条件访问策略

条件访问是 Azure Active Directory 用于将信号汇集在一起、做出决策和实施组织策略的工具。 条件访问是标识驱动控制的核心。 条件访问策略最简单的是 if-then 语句。 如果用户希望访问资源，则必须完成一个操作。 示例：工资单经理希望访问工资单应用程序，并且需要执行多重身份验证才能访问它。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中获益？

企业移动性 + 安全性 E3/A3、Microsoft 365 F3/E3/A3/Business Premium 和 Azure Active Directory Premium 计划 1 的许可用户可以从条件访问策略中获益。 企业移动性 + 安全性 E5/A5/G5、Microsoft 365 E5/A5、Microsoft E5 安全与 Azure Active Directory Premium 计划 2 的许可用户可以从 Identity Protection (基于风险的条件访问策略) 。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

安全操作分析师和安全专业人员通过能够对用户强制执行组织策略，要求他们在授予访问公司内容的权限之前满足特定条件而受益。 最终用户通过能够随时随地访问他们的工作，同时保护组织的资产而受益。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，在租户级别为租户内的所有用户启用条件访问功能。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

具体而言，对于标识保护和条件访问，用户必须包含在组中或添加到条件访问策略中。 在条件访问策略中，用户和组条件是必需的。 在策略中，可以选择所有用户 **或** 特定用户和组。 应仅选择经过适当许可的用户和组。 有关详细信息，请参阅条件 [访问：条件](https://docs.microsoft.com/azure/active-directory/conditional-access/conditions)。

## <a name="advanced-audit"></a>高级审核

Microsoft 365 中的高级审核为用户和管理员活动提供一年审核日志保留期，并提供创建自定义 审核日志 保留策略来管理其他 Microsoft 365 服务的 审核日志 保留的能力。 它还提供对关键事件的访问权限，以进行调查以及高带宽访问 Office 365 管理活动 API。 有关详细信息，请参阅 [Microsoft 365 中的高级审核](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit)。

您还可以使用附加 SKU 启用 10 年的保留期。 从 2021 年初开始，需要加载项 SKU。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中获益？

Office 365 E5、Microsoft 365 E5、Microsoft 365 E5 合规性和 Microsoft 365 电子数据展示和审核的许可用户可以从高级审核中获益。

具有高级审核和 10 年审核日志保留加载项的许可用户可以从 10 年审核日志保留中获益。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

用户受益于高级审核，因为与 Microsoft 365 服务中的用户活动相关的审核记录可保留最多一年。 此外，还会记录高价值审核事件，例如访问或读取用户邮箱中的项目时。 有关详细信息，请参阅 [Microsoft 365 中的高级审核](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit)。

### <a name="how-is-the-service-provisioneddeployed"></a>如何设置/部署服务？

默认情况下，对于拥有 Office 365 或 Microsoft 365 E5 订阅的所有组织，在租户级别启用高级审核，并自动为 Azure Active Directory、Exchange 和 SharePoint 中具有相应许可证) 的用户执行的活动 (提供一年审核日志保留期。 此外，组织可以使用审核日志策略来管理其他 Microsoft 365 服务中的活动生成的审核记录的保留期。 10 年审核日志保留功能也使用相同的保留策略启用。 有关详细信息，请参阅[管理审核日志保留策略](https://docs.microsoft.com/microsoft-365/compliance/audit-log-retention-policies)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何仅将服务应用于租户中获得服务许可的用户？

审核日志保留一年以及重要事件的审核仅适用于具有相应许可证的用户。 此外，管理员可以使用审核日志策略为特定用户的审核日志指定较短的保留期。

审核日志保留 10 年仅适用于具有相应加载项许可证的用户。 从 2021 年初开始，需要加载项 SKU。
