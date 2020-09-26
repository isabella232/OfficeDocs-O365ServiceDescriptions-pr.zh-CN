---
title: 适用于安全性的 Microsoft 365 许可指南 & 合规性
ms.author: v-trscho
author: vtrscho
audience: ITPro
ms.topic: reference
ms.date: 7/13/2020
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 本文提供适用于 Microsoft 365 合规性的许可指南，以帮助避免由于未经许可访问而导致的潜在服务中断。
ms.openlocfilehash: fc3385774a01e76b7297aa77a490acf6153b555c
ms.sourcegitcommit: 57f06932a94f09990c0e02a2da491923ca2c1a2f
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/26/2020
ms.locfileid: "48284984"
---
# <a name="microsoft-365-licensing-guidance-for-security--compliance"></a>适用于安全性的 Microsoft 365 许可指南 & 合规性

出于本文的目的，租户级服务是一种在线服务， &mdash; 在为租户中的任何用户购买或作为 Office 365 或 Microsoft 365 计划的一部分购买时，将为租户中的 &mdash; 所有用户激活或完全激活) 的 (。 尽管一些未经许可的用户在技术上能够访问该服务，但您希望从该服务获益的任何用户都需要许可证。

> [!NOTE]
> 某些租户服务当前不能限制特定用户的优势。 应采取措施将服务的好处限制为许可用户。 这有助于避免您的组织在获得目标功能后对组织造成潜在的服务中断。

若要查看授权你的用户在2020年4月1日的 Microsoft 365 合规性功能中受益的选项，请下载详细的 Microsoft 365 合规性许可比较。 [ (PDF) ](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [ (Excel) ](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory 标识保护

Azure Active Directory 标识保护是 Azure Active Directory 高级 P2 认证计划的一项功能，可让您检测到影响组织标识的潜在漏洞，并将自动响应配置为检测到的与您的组织的身份相关的可疑操作，并调查可疑事件并采取适当的措施来解决这些问题。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

SecOps 分析师和安全专家将从基于机器学习算法的已标记用户和风险事件的合并视图中获益。 最终用户可通过基于风险的条件访问提供自动保护，并通过对漏洞的操作提供改进的安全性来获得好处。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供了从服务中获益的权限？

企业移动性 + 安全性 E5/A5，Microsoft 365 E5/A5，Microsoft 365 E5/A5 安全性，以及 Azure Active Directory 高级计划2为用户提供了从 Azure Active Directory 标识保护中获益的权限。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

默认情况下，Azure AD Identity Protection 功能在租户级别为租户中的所有用户启用。 有关 Azure AD Identity Protection 的信息，请参阅 [什么是 Azure Active Directory 身份保护？](https://docs.microsoft.com/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

管理员可以通过分配定义密码重置级别的风险策略并仅允许许可用户访问，来对 Azure AD 标识保护进行作用域。 有关如何对 Azure AD 标识保护部署进行作用域的说明，请参阅 [配置登录风险策略](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy)。

## <a name="azure-advanced-threat-protection"></a>Azure 高级威胁防护

Azure 高级威胁防护 (ATP) 是一项云服务，可帮助从多种类型的高级目标网络攻击和内幕威胁中保护企业混合环境。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

SecOp 分析师和安全性专家将受益于 Azure ATP 检测和调查高级威胁、已泄露身份和恶意内幕活动的能力。 最终用户通过 Azure ATP 监视数据来获得好处。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供了从服务中获益的权限？

企业移动性 + 安全性 E5/A5，Microsoft 365 E5/A5，Microsoft 365 E5/A5 Security，以及适用于 Azure 的用户的 Azure 高级威胁防护提供从 Azure ATP 获益的权限。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

默认情况下，在租户级别为租户中的所有用户启用 Azure ATP 功能。 有关配置 Azure ATP 的信息，请参阅 [Create a AZURE atp instance](https://docs.microsoft.com/azure-advanced-threat-protection/install-atp-step1)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

Azure ATP 服务当前不能限制特定用户的功能。 您必须为您想要受益的每个用户授予许可证。

## <a name="office-365-advanced-threat-protection"></a>Office 365 高级威胁防护

 (ATP) 的高级威胁防护可帮助组织防御复杂的攻击，如网络钓鱼和零日恶意软件。 ATP 还通过关联大量数据中的信号来提供可操作的见解，以帮助确定、设置优先级，并提供有关如何解决潜在威胁的建议。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

ATP 可保护用户免受复杂攻击（如网络钓鱼和零天恶意软件）的攻击。 有关计划1和计划2中提供的服务的完整列表，请参阅 [Office 365 高级威胁防护](https://products.office.com/exchange/advance-threat-protection)。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供了从服务中获益的权限？ 

Office 365 高级威胁防护，Office 365 E5/A5/G5，Microsoft 365 E5/A5/G5，Microsoft 365 E5/A5/G5 Security，Microsoft 365 商业高级版和 Office 365 ATP 计划1和2为用户提供了从高级威胁防护中获益的权限。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

默认情况下，在租户级别为租户中的所有用户启用 ATP 功能。 有关为许可用户配置 ATP 策略的信息，请参阅 [Office 365 高级威胁防护](https://docs.microsoft.com/office365/securitycompliance/office-365-atp)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

若要对 ATP 进行作用域，请遵循安全链接和安全附件部署策略：

- 有关为许可用户配置安全链接的信息，请参阅 [设置 Office 365 ATP 安全链接策略](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-atp-safe-links-policies)。

- 有关为许可用户配置安全附件的信息，请参阅 [设置 Office 365 ATP 安全附件策略](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-atp-safe-attachments-policies)。

## <a name="office-365-cloud-app-security"></a>Office 365 云应用安全

Office 365 云应用安全 (OCAS) 是 Microsoft 云应用安全性的子集，其中的功能限于 Office 365，无需为第三方云应用程序和 IaaS 服务提供额外的安全性。

OCAS 使组织能够深入了解他们的工作效率云应用和服务，提供了完善的分析来识别和防御网络威胁，并使他们可以控制数据 &mdash; 在 Office 365 之间的传输方式。

若要比较功能，请参阅 [Microsoft Cloud App security 与 Office 365 云应用安全性之间的差异](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365)。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

OCAS 发现影子它，提供跨 Office 365 的威胁防护，并可以控制哪些应用有权访问数据。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供了从服务中获益的权限？

Office 365 E5/A5/G5 为用户提供了从 OCAS 获益的权限。
有关详细信息，请参阅 [Microsoft Cloud App Security 授权数据表](https://www.aka.ms/mcaslicensing)。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

默认情况下，OCAS 功能在租户级别为租户中的所有用户启用。

有关配置服务的信息，请参阅 [Basic setup For Cloud App Security](https://docs.microsoft.com/cloud-app-security/general-setup)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

管理员可以对 OCAS 部署进行作用域，以强制实施特定应用程序的访问方式并限制由 Office 365 云应用安全性监控的用户组。 有关详细信息，请参阅 [作用域部署](https://docs.microsoft.com/cloud-app-security/scoped-deployment)。

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) 是一个云访问安全代理 (CASB) 解决方案，可向组织提供云应用程序和服务的可见性，提供了用于识别和防御网络威胁的高级分析，并允许他们控制数据 &mdash; 在任何云应用中的传输方式。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

MCAS 发现和评估阴影，提供跨第一方云应用程序的威胁保护，并在第一方和第三方云应用中保护信息。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供了从服务中获益的权限？

MCAS，企业移动性 + 安全 E5/A5/G5，Microsoft 365 E5/A5/G5，Microsoft 365 E5/A5/G5 Security，Microsoft 365 E5/A5/G5 合规性，Microsoft 365 信息保护和治理为用户提供了从 MCAS 获益的权限。

Azure AD P1 为用户提供了从 MCAS 中的发现功能中获益的权限。

若要从 MCAS 中的条件访问应用程序控制功能中受益，还必须为 Azure Active Directory P1 （包括在企业移动性 + 安全 E3/A3/G3、企业移动性 + 安全 E5/A5/G5、Microsoft 365 E3/A3/G3、Microsoft 365 E5/A5/G5 和 Microsoft 365 E5/A5/g5 安全性）授予许可证。

若要从自动标记中受益，用户必须获得 Azure 信息保护 P2 的许可，这些 P2 包含在企业移动性 + 安全 E5/A5/G5 中，Microsoft 365 E5/A5/G5，Microsoft 365 E5/A5/G5 合规性，Microsoft 365 信息保护和治理。

有关详细信息，请参阅 [Microsoft Cloud App Security 授权数据表](https://www.aka.ms/mcaslicensing)。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

默认情况下，MCAS 功能在租户级别为租户中的所有用户启用。

有关为许可用户配置 Microsoft 云应用安全策略的信息，请参阅 [Microsoft Cloud App security 概述](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

管理员可以使用服务中提供的作用域部署功能将 MCAS 部署限定为许可用户。 有关详细信息，请参阅 [作用域部署](https://docs.microsoft.com/cloud-app-security/scoped-deployment)。

## <a name="compliance-manager"></a>合规性管理器

通过合规性管理器简化合规性并降低风险。 合规性管理器可帮助组织满足法规、标准、公司策略或其他所需控制框架的要求。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

以下是用户对合规性管理器服务的好处：

- 将复杂的法规、标准、公司策略或其他所需的控制框架转换为简单语言
- 提供对广泛的现成评估和自定义评估库的访问权限，以满足独特的合规性需求
- 将规章控制映射到建议的改进操作
- 提供有关如何实施解决方案以满足管理法规要求的分步指南
- 帮助用户通过将分数与每个操作相关联来确定对组织合规性影响最大的操作。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供了从服务中获益的权限？

具有 Office 365 E1/A1/E3/A3 和 Microsoft 365 E3/A3 许可证的客户将能够访问数据保护基准评估。 拥有 Office 365 E5/A5 和 Microsoft 365 E5/A5 许可证的客户将能够访问数据保护基准、GDPR、NIST 800-53 和 ISO 22701 开箱即用评估。 客户需要至少有一个 Office 365 E5/A5 或 Microsoft 365 E5/A5 许可证，才能使用自定义评估功能。 高级评估版将适用于购买到 Office 365 E5/A5 和 Microsoft 365 E5/A5 客户。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

默认情况下，合规性管理器是为你的租户设置的。 管理员设置用户权限并分配角色，以便组织中的非管理员用户可以开始使用合规性管理器。 有关详细信息，请参阅 [合规性管理器入门：设置用户权限和分配角色](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

对合规性管理器的访问权限是通过设置用户权限和分配角色来控制的。 有关详细信息，请参阅 [合规性管理器入门：设置用户权限和分配角色](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles)。

## <a name="microsoft-defender-atp"></a>每个租户

Microsoft Defender ATP 是一个包含基于风险的漏洞管理和评估的终结点安全解决方案;攻击面减少功能;基于行为和云驱动的下一代保护; (EDR) 的终结点检测和响应自动调查和修正;和托管的搜寻服务。 若要了解详细信息，请参阅 [Microsoft DEFENDER ATP](https://www.microsoft.com/microsoft-365/windows/microsoft-defender-atp?rtc=1) 页面。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中受益？

Windows 10 企业版 E5 的许可用户（Windows 10 教育版 A5） Microsoft 365 E5 (M365 E5) 包括 Windows 10 企业版 E5、Microsoft 365 E5 Security、Microsoft 365 A5 (M365 A5) 可以从 Microsoft Defender ATP 获益。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

SecOps 分析师和安全性专家可受益于 Microsoft Defender ATP 的终结点安全功能，以执行预防性保护、入侵后检测、自动调查以及对高级威胁的响应。 最终用户通过使用 Microsoft Defender ATP 进行监视的恶意事件来获得好处。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

默认情况下，在租户级别为租户中的所有用户启用 Microsoft Defender ATP 功能。 有关部署的信息，请参阅 [部署指南](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/deployment-phases)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

Microsoft Defender ATP 管理员可以利用 [基于角色的访问控制 (RBAC) ](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/rbac) 在安全操作团队中创建角色和组，以向 Microsoft Defender 安全中心授予适当的访问权限。

## <a name="information-protection"></a>信息保护

信息保护可帮助组织发现、分类、标记和保护敏感文档和电子邮件。 管理员可以定义规则和条件以自动应用标签，用户可以手动应用标签，也可以使用二者的组合，即向用户提供有关应用标签的建议。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

用户可以通过将灵敏度标签手动应用于其内容或通过将其内容自动分类来获得好处。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供了从服务中获益的权限？

Microsoft 365 E5/A5/G5/AIP/AIP///A3/A3/G3/F1/F3/Business Premium、企业移动性 + 安全 F3/E3/E5、Office 365 E5/A5/E3/A3/F3、Plan 1 和 Plan 2 为用户提供了从手动敏感度标记中受益的权限。

Microsoft 365 E5/A5/G5/AIP/AIP//？//A3/A3/G3/F1/F3/Business Premium、Enterprise 可移动性 + Security F3/E3/E5、Plan 1 和 Plan 2 为用户提供了一些权限，以便用户能够在 Power bi 中应用和查看敏感度标签并在将数据从 Power BI 导出到 

> [!NOTE]
> Power BI 包含在 Microsoft 365 E5/A5/G5 中;在所有其他计划中，Power BI 必须单独获得许可。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 合规性、Microsoft 365 信息保护和治理、Office 365 E5、Office 365 高级合规性、企业移动性 + 安全 E5 和 AIP Plan 2 为用户提供了从自动敏感度标记中受益的权限。

有关许可证的具体权限，请参阅详细的 Microsoft 365 合规性许可比较。 [ (PDF) ](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [ (Excel) ](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)不包括基于机器学习 (trainable 类元) 自动分类的权限。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

默认情况下，在租户级别为租户中的所有用户启用信息保护功能。 有关为许可用户配置策略的信息，请参阅激活 Azure 权限管理。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

除了使用 AIP 扫描程序功能时，可以对特定组或用户和注册表进行编辑，以防止未经授权的用户运行分类或标记功能。 有关如何对 AIP 部署进行作用域的说明，请参阅 [配置 Azure 信息保护策略](https://docs.microsoft.com/azure/information-protection/configure-policy)。

对于 AIP 扫描程序功能，Microsoft 不会承诺向未获得许可的用户提供文件分类、标记或保护功能。

## <a name="information-governance"></a>信息治理

信息管理通过发现、分类、标记和管理数据来帮助组织管理其风险。 信息管理让组织能够满足业务和管理法规要求，并通过在其 Microsoft 365 和第三方数据中提供保留和删除功能来减少攻击面。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

用户可通过对数据进行分类以进行保留以遵守特定策略和法规，从而获得好处。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供了从服务中获益的权限？

Microsoft 365 F3/Business 高级版、Office 365 E1/A1/F3 和独立 Exchange 计划为用户提供了从手动对邮箱数据应用非记录保留标签的好处。

Microsoft 365 F3/F1/Business Premium、Office 365 E1/A1/F3 和独立 SharePoint 计划为用户提供了从手动将非记录保留标签应用于 SharePoint 或 OneDrive 中的文件的权限。 

Microsoft 365 E5/A5/E3/A5/A3/A3/？ Premium、Office 365 E5/A5/E3/A3、Exchange Plan 2 和 Exchange Online 存档为用户提供了从基本组织范围或位置范围内的邮箱保留策略中获益的权限，并/或将非记录保留标记手动应用于邮箱数据。

Microsoft 365 E5/A5/E3/A5/A3、Office 365 E5/A5/a5/A3 和 SharePoint 计划2为用户提供了从基本 SharePoint 或 OneDrive 保留策略中获益的权限，以及/或手动将非记录保留标签应用于 SharePoint 或 OneDrive 中的文件。

Microsoft 365 E5/A5/E3/A3 和 Office 365 E5/A5/E3/A3 为用户提供了从团队保留策略中获益的权限。

Microsoft 365 E5/A5，Microsoft 365 E5/A5 合规性，Microsoft 365 信息保护和治理、Office 365 E5/A5 和 Office 365 高级合规性为用户提供了从自动应用保留标签或策略中获益的权限。应用默认保留标签或策略，基于自定义事件启动保留期的保留期，在标签保留期结束时触发手动处置评审，通过本机数据连接器导入第三方数据，将文件声明为记录，发现已标记的内容，并监视标记活动。

Microsoft 365 E5/A5、Microsoft 365 E5/A5 合规性、Microsoft 365 信息保护和治理为用户提供了从基于 trainable 分类程序自动应用保留标签中获益的权限。

有关许可证的具体权限，请参阅详细的 Microsoft 365 合规性许可比较。 [ (PDF) ](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [ (Excel) ](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

默认情况下，在租户级别为租户中的所有用户启用信息管理功能。 有关配置信息管理以将 autolabeling 和策略应用于许可用户的信息，请参阅 [管理信息治理](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

信息治理功能可应用于特定位置 (工作组网站、组网站等等 ) 的许可用户。 有关配置信息管理以将 autolabeling 和策略应用于许可用户的信息，请参阅 [管理信息治理](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance)。

## <a name="records-management"></a>记录管理

记录管理通过跨 Microsoft 365 和第三方数据发现、分类、标记、保留和 defensible 删除功能，帮助组织满足其业务和法规记录的要求。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供了从服务中获益的权限？

Microsoft 365 E5/A5，Microsoft 365 E5/A5 合规性，Microsoft 365 信息保护和治理，Office 365 E5/A5，Office 365 高级合规性为用户提供了从记录管理中受益的权限，包括将项目声明为记录、自动应用保留或记录标签和执行处置审核流程 (排除基于 trainable 的分类程序) 自动应用保留标签。

Microsoft 365 E5/A5、Microsoft 365 E5/A5 合规性、Microsoft 365 信息保护和治理为用户提供了从基于 trainable 分类程序自动应用保留或记录标签方面的好处的权限。

有关许可证的具体权限，请参阅详细的 Microsoft 365 合规性许可比较。 [ (PDF) ](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [ (Excel) ](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

用户可以通过将内容声明为记录并通过 defensible 处置来管理其完整的记录流程，从而获得好处。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

默认情况下，在租户级别为租户中的所有用户启用记录管理功能。 有关配置要应用于许可用户的记录管理的信息，请参阅 [Microsoft 365 中的记录管理](https://docs.microsoft.com/microsoft-365/compliance/records-management)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

记录管理功能可应用于特定位置 (工作组网站、组网站等等 ) 的许可用户。 有关配置要应用于许可用户的记录管理的信息，请参阅 [Microsoft 365 中的记录管理](https://docs.microsoft.com/microsoft-365/compliance/records-management)。

## <a name="data-connectors"></a>数据连接器 

Microsoft 提供可在 Microsoft 365 合规性中心中配置的第三方数据连接器。 有关由 Microsoft 提供的数据连接器的列表，请参阅 [第三方数据连接器](https://docs.microsoft.com/microsoft-365/compliance/archiving-third-party-data) 表。 此表还概述了在 Microsoft 365 中导入和存档数据后，您可以应用于第三方数据的合规性解决方案，并提供了有关每个连接器的分步说明的链接。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

使用数据连接器在 Microsoft 365 中导入和存档第三方数据的主要好处在于，在导入后，可以将各种 Microsoft 365 合规性解决方案应用于该解决方案。 这有助于确保贵组织的非 Microsoft 数据符合影响组织的法规和标准。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供了从服务中获益的权限？

以下许可证为用户提供了从数据连接器获益的权限：

- Microsoft 365 E5/A5
- Microsoft 365 E5/A5 Info Protection & 调控
- Microsoft 365 E5/A5 合规性
- Microsoft 365 E5/A5 内幕人士风险管理 
- Microsoft 365 E5/A5 电子数据展示和审核 
- Office 365 E5/A5
- Office 365 高级合规版

对于由 Microsoft 合作伙伴提供的 M365 Security & 合规中心中的数据连接器，贵组织将需要与合作伙伴建立业务关系，然后才能部署这些连接器。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

连接器是使用安全 & 合规中心和连接器目录配置的。

### <a name="how-can-the-service-be-applied-only---to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

数据连接器服务是租户级别的值。 每个旨在受益于此服务的用户都必须获得许可。

## <a name="microsoft-graph-apis-for-teams-dlp"></a>适用于团队 DLP 的 Microsoft Graph Api

在今年早些时候 [，我们宣布了 Microsoft Graph 更改通知 API 的公共预览，用于团队中的邮件](https://developer.microsoft.com/en-us/graph/blogs/announcing-change-notifications-for-microsoft-teams-messages)。 通过此 API，开发人员可以生成可实时收听 Microsoft 团队邮件的应用程序，并为客户和 Isv 启用 DLP 方案实现。 此外，Microsoft Graph 修补程序 API 还允许对工作组邮件应用 DLP 操作。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

[数据丢失防护 (DLP) ](https://docs.microsoft.com/microsoft-365/compliance/dlp-microsoft-teams?view=o365-worldwide) 功能在 Microsoft 团队中广泛使用，尤其是在组织已移动到远程工作时。 如果你的组织拥有 DLP，你现在可以定义策略，以防止用户在 Microsoft 团队频道或聊天会话中共享敏感信息。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供了从服务中获益的权限？

你将需要以下 E5 许可证之一，以支持数据丢失防护 (DLP) protection 在团队聊天中：

- Microsoft 365 E5/A5
- Microsoft 365 E5/A5 合规性
- Microsoft 365 E5/A5 信息保护和治理
- Office 365 E5/A5 

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

API 访问是在租户级别配置的。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

适用于团队 DLP 的 Microsoft Graph API 是租户级别值。 每个旨在受益于此服务的用户都必须获得许可。

## <a name="ediscovery"></a>电子数据展示

电子数据展示为 IT 和公司内部的法律部门提供调查和电子数据展示解决方案，以在从 Microsoft 365 系统中出口之前识别、收集、保留、减少和检查与调查或诉讼相关的内容。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

当用户被选作数据保管人时，用户将从高级电子数据展示中受益 (在对文档或电子文件) 进行管理控制的人的情况下。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供了从服务中获益的权限？

Microsoft 365 E5/A5/？//？/G5/G5/E3/A3/G3、Office 365 E5/A5/G5/E3/A3/G3 和 Office 365 高级合规性为用户提供了从核心电子数据展示中获益的权限。
Microsoft 365 E5/A5/G5，Microsoft 365 E5/A5/G5 合规性，Microsoft 365 E5/A5 电子数据展示和审核，Office 365 E5/A5/G5 和 Office 365 高级合规性为用户提供了从高级电子数据展示中获益的权限。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

默认情况下，当管理员在安全 & 合规中心中分配电子数据展示权限时，将在租户级别为租户中的所有用户启用高级电子数据展示功能。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

通过使用高级电子数据展示中的内置保管人管理工具，电子数据展示管理员可以选择特定用户作为事例的数据保管人，如 [将保管人添加到高级电子数据展示事例](https://docs.microsoft.com/microsoft-365/compliance/add-custodians-to-case)中所述。

## <a name="office-365-customer-key"></a>Office 365 客户密钥

使用 "客户密钥"，可以控制组织的加密密钥，并配置 Office 365 以使用它们在 Microsoft 数据中心中对静态数据进行加密。 换句话说，客户密钥允许您使用自己的密钥添加属于您的加密层。 静态数据包含来自 Exchange Online 和 Skype for business 的数据，这些数据存储在 SharePoint Online 和 OneDrive for business 中的邮箱和文件中。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

用户可通过在应用程序层使用提供、控制和管理自己的组织的加密密钥在应用程序层对其数据进行加密，从而获得客户密钥的好处。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供了从服务中获益的权限？

Microsoft 365 E5/A5、Microsoft 365 E5/A5 合规性、Microsoft 365 信息保护和治理、Office 365 E5/A5 和 Office 365 高级合规性为用户提供了从客户密钥获益的权限。 若要获得客户密钥的全部好处，您还必须具有 Azure Key Vault 的订阅。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

可以为存储在 Exchange Online 和 Skype for business 邮箱、SharePoint Online、OneDrive for Business 和团队文件中的所有数据启用 Office 365 客户密钥加密密钥。 有关 Office 365 客户密钥的详细信息（包括如何开始），请参阅 [Office 365 中的使用客户密钥的服务加密](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

若要将加密密钥分配给 Office 365 和/或 Microsoft 365 组织中的数据以供许可用户使用，请按照客户密钥加密密钥的部署说明进行操作。

- 对于 SharePoint Online、OneDrive for Business 和团队文件，可以使用客户密钥对一个或多个网站上的文件进行加密。

- 对于 Exchange Online 和 Skype for business，可以使用客户密钥加密邮箱。

## <a name="office-365-customer-lockbox"></a>Office 365 客户密码箱

客户密码箱通过让客户能够为服务操作提供显式访问授权，从而提供了一个额外的控制层。 通过演示如何将过程用于显式数据访问授权，客户密码箱还可以帮助组织满足特定合规性义务，如 HIPAA 和 FEDRAMP。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

用户可以从客户密码箱获益，确保 Microsoft 无需在未经客户明确批准的情况下即可在 Microsoft 不能访问其内容的情况下执行服务操作。 客户密码箱将客户引入审批工作流，以获取访问其内容的请求。 有时，Microsoft 工程师会在支持流程中参与诊断和修复客户报告的问题。 在大多数情况下，通过 Microsoft 为其服务提供的大量遥测和调试工具解决了问题。 但是，在某些情况下，可能需要 Microsoft 工程师访问客户内容以确定根本原因并解决问题。 客户密码箱要求工程师在审批工作流的最后步骤中请求从客户进行访问。 这为组织提供了批准或拒绝这些请求的选项，这些请求使他们可以直接控制 Microsoft 工程师是否可以访问组织的最终用户数据。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供了从服务中获益的权限？

Office 365 E5/A5/G5，Microsoft 365 E5/A5/G5，Microsoft 365 E5/A5/G5 合规性，Microsoft 365 内幕风险管理和 Office 365 高级合规性为用户提供了从客户密码箱中获益的权限。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

管理员可以在 Microsoft 365 管理中心启用客户密码箱控件。 有关详细信息，请参阅 [Office 365 中的客户密码箱](https://docs.microsoft.com/microsoft-365/compliance/customer-lockbox-requests)。 当客户密码箱打开时，在访问其任何内容之前，需要 Microsoft 获取组织的批准。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

客户密码箱服务当前不能限制为特定用户。 您必须为您想要受益的每个用户授予许可证。

## <a name="privileged-access-management-in-office-365"></a>Office 365 中的 Privileged Access Management

[ (PAM) 的 "特权访问管理 ](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration) " 提供对 Office 365 中的特权管理任务的精细访问控制。 启用 PAM 后，用户将需要通过高度范围和时间限制的审批工作流请求实时访问，以完成提升和特权的任务。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

启用 PAM 可让组织以零作为自主权限运行。 用户从增加的防御层中受益，以防止因提供对其数据的 unfettered 访问而产生的漏洞。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供了从服务中获益的权限？ 

Office 365 E5/A5，Microsoft 365 E5/A5，Microsoft 365 E5/A5 合规性，Microsoft 365 E5/A5 信息保护和治理为用户提供了从 PAM 中获益的权限。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

默认情况下，在租户级别为租户中的所有用户启用 PAM 功能。 有关配置 PAM 策略的信息，请参阅 [特权访问管理入门](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

客户可以通过审核人组和访问策略（可应用于许可用户）在每用户的基础上管理 PAM。 有关详细信息，请参阅 [Office 365 中的特权访问管理](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751)。

## <a name="double-key-encryption-for-microsoft-365"></a>适用于 Microsoft 365 的双重密钥加密 

对 Microsoft 365 的双重密钥加密允许您保护高度敏感的数据，以满足特殊要求并保持对加密密钥的完全控制。 双密钥加密使用两个密钥来保护你的数据，并在你的控制中使用一个密钥，并将第二个密钥安全地存储在 Microsoft Azure 中。 若要查看数据，您必须具有对这两个键的访问权限。 由于 Microsoft 只能访问一个密钥，因此你的密钥和你的数据在 Microsoft 中不可用，从而确保你能够完全控制你的数据的隐私和安全。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

用户可以将加密的数据迁移到云中，并防止第三方访问，前提是用户可以将其加密数据迁移到云中，从而使用户受益于双密钥加密。 最终用户可以保护和使用与任何其他敏感度标签保护的内容类似的双密钥加密内容。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供了从服务中获益的权限？

Microsoft 365 E5/A5、Microsoft 365 E5/A5 合规性、Microsoft 365 信息保护和治理、Office 365 E5/A5 和 Office 365 高级合规性为用户提供了从双密钥加密中获益的权限。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

双密钥加密支持 Microsoft Office for Windows 的桌面版本。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

若要将加密密钥分配给 Office 365 和/或 Microsoft 365 组织中的数据以供许可用户使用，请按照双重密钥加密部署说明进行操作。

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>适用于 Exchange Online、SharePoint Online 和 OneDrive for business 的 Office 365 数据丢失防护

使用 Office 365 数据丢失防护 (DLP) for Exchange Online、SharePoint Online 和 OneDrive for Business，组织可以在电子邮件和 (文件中识别、监视和自动保护敏感信息，其中包括存储在 Microsoft 团队文件存储库) 中的文件。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

当检查其电子邮件和文件中的敏感信息（如组织的 DLP 策略中配置）时，用户将受益于 DLP for Exchange Online、SharePoint Online 和 OneDrive for business。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供了从服务中获益的权限？

Microsoft 365 A1/E3/A3/a/Business、Office 365 E3/A3 和 Office 365 数据丢失防护为用户提供了从 Office 365 DLP for Exchange Online、SharePoint Online 和 OneDrive for business 中获益的权限。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

默认情况下，Exchange Online 电子邮件、SharePoint 网站和 OneDrive 帐户为租户中所有用户的这些 DLP 功能 *启用了 (工作负荷) 的位置 * 。 有关使用 DLP 策略的详细信息，请参阅 [数据丢失防护概述](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

管理员可以在 "**数据丢失防护**位置" 下的 "安全 & 合规中心" 中自定义位置 (工作负载) 、包含的用户和排除的用户）  >  **Locations**。

## <a name="communication-data-loss-prevention-for-teams"></a>工作组的通信数据丢失防护

使用针对团队的通信 DLP，组织可以阻止包含敏感信息（如财务信息）的聊天和频道消息，以及个人身份信息、与运行状况相关的信息或其他机密信息。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中受益？

Office 365 E5/A5 的许可用户、Microsoft 365 E5/A5、Microsoft 365 信息保护和治理以及 Office 365 高级合规性可以从适用于团队的通信 DLP 中受益。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

通过在组织的 DLP 策略中配置的敏感信息检查其传出聊天和频道消息中的敏感信息，发件人会获得好处。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

默认情况下，团队聊天和频道邮件是为租户中的所有用户启用这些 DLP 功能 * (工作负荷) 的已启用位置 * 。 有关使用 DLP 策略的详细信息，请参阅 [数据丢失防护概述](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

管理员可以在 "**数据丢失防护**位置" 下的 "安全 & 合规中心" 中自定义位置 (工作负载) 、包含的用户和排除的用户）  >  **Locations**。

## <a name="information-barriers"></a>信息屏障

信息障碍是管理员可以配置的用于阻止个人或组相互通信的策略。 例如，如果一个部门处理的信息不应与其他部门共享，或者必须阻止某个组与外部联系人通信，则这将非常有用。 信息屏障策略也阻止了查找和发现。 这意味着，如果您尝试与不应与之通信的人员进行通信，则不会在人员选取器中找到该用户。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

当限制用户与其他人通信时，他们将受益于信息障碍的高级合规性功能。 例如：<br><br>

| 方案 | 需要许可证的是谁？ |
|:------|:------|:------|
|  (组 &nbsp; 1 和组 &nbsp; 2) 的两个组无法相互通信 (也就是说，组 &nbsp; 1 用户限制为与组 &nbsp; 2 用户通信，而组 &nbsp; 2 用户限制与组 &nbsp; 1 用户通信。 | 组 &nbsp; 1 和组2中的 &nbsp; 用户 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供了从服务中获益的权限？

Microsoft 365 E5/A5、Microsoft 365 E5/A5 合规性、Microsoft 365 内幕风险管理、Office 365 E5/A5 和 Office 365 高级合规性为用户提供了从信息障碍中获益的权限。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

管理员在安全 & 合规中心中使用 PowerShell cmdlet 创建和管理信息障碍策略。 必须为管理员分配 Microsoft 365 企业全局管理员、Office 365 全局管理员或合规性管理员角色，以创建信息障碍策略。 默认情况下，这些策略适用于租户中的所有用户。 有关信息障碍的详细信息，请参阅 [Microsoft 团队中的信息障碍](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

管理员可以在安全 & 合规中心中自定义 (工作负荷) 、包含的用户和排除的用户的位置。 例如，如果所有用户均为 Office 365 E3 许可，并且没有许可 Office 365 高级合规性/E5，则无需为组织创建任何信息障碍策略。 有关详细信息，请参阅 [Microsoft 团队中的信息障碍](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)。

## <a name="office-365-message-encryption"></a>Office 365 邮件加密

Office 365 邮件加密 (OME) 是一项基于 Azure 权限管理 (Azure RMS) 构建的服务，允许您向组织内外发送经加密的电子邮件，而无需考虑目标电子邮件地址（Gmail、Yahoo!Mail、Outlook.com 等）。

若要查看加密邮件，收件人可以使用一次性密码、通过 Microsoft 帐户登录或使用与 Office 365 关联的工作或学校帐户登录。 此外，收件人也可发送加密回复。 他们不需要订阅即可查看加密邮件或发送加密回复。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

邮件发件人可受益于对 Office 365 邮件加密提供的敏感电子邮件的新增控制。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供了从服务中获益的权限？

Microsoft 365 E3/A3、Office 365 E3/A3 和 Azure Information Protection Plan 1 为用户提供了从 Office 365 邮件加密中获益的权限。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

管理员在 "**邮件流**规则" 下的 Exchange 管理中心中创建和管理 Office 365 邮件加密策略  >  **Rules**。 默认情况下，这些规则适用于租户中的所有用户。 有关设置新的 Office 365 邮件加密功能的详细信息，请参阅 [设置新的 office 365 邮件加密功能](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

管理员应将仅限 Office 365 邮件加密的邮件流规则应用于许可用户。 有关定义邮件流规则的详细信息，请参阅 [在 Office 365 中定义用于加密电子邮件的邮件流规则](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)。

## <a name="office-365-advanced-message-encryption"></a>Office 365 高级邮件加密

Office 365 高级邮件加密帮助客户满足合规性义务，这些要求对外部收件人和对加密电子邮件的访问权限要求更灵活的控制。 通过高级邮件加密，管理员可以通过使用可检测敏感信息类型的自动策略来控制在组织外共享的敏感电子邮件 (例如，个人标识信息或财务或运行状况 Id) ，也可以通过应用自定义电子邮件模板，并通过安全 web 门户终止对加密电子邮件的访问，从而使用关键字增强保护。 此外，管理员可以随时撤销访问权限，从而进一步控制通过安全 web 门户外部访问的加密电子邮件。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

邮件发件人可受益于对高级邮件加密提供的敏感电子邮件所添加的控制。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供了从服务中获益的权限？

Office 365 E5/A5、Microsoft 365 E5/A5、Microsoft 365 E5/A5 合规性、Microsoft 365 信息保护和治理以及 Office 365 高级合规性为用户提供了从高级邮件加密中获益的权限。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

管理员在 "邮件流规则" 下的 Exchange 管理中心中创建和管理高级邮件加密策略。 默认情况下，这些规则适用于租户上的所有用户。 有关设置新的邮件加密功能的详细信息，请参阅 [设置新的 Office 365 邮件加密功能](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

管理员应将邮件流规则仅应用于已授权用户的高级邮件加密。 有关定义邮件流规则的详细信息，请参阅 [在 Office 365 中定义用于加密电子邮件的邮件流规则](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)。

## <a name="communication-compliance"></a>通信合规性

Microsoft 365 中的通信合规性通过帮助您检测、捕获和采取补救措施对组织中不适当的邮件进行补救，来帮助最大限度地减少通信风险。 您可以定义用于捕获组织中的内部和外部电子邮件、Microsoft 团队或第三方通信的特定策略。 审阅者可以采取相应的更正措施，以确保它们符合组织的邮件标准。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

合规性专家通过通信合规性策略监视组织通信，从而从服务中受益。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供了从服务中获益的权限？

Office 365 E5/A5、Microsoft 365 E5/A5、Microsoft 365 E5/A5 合规性以及 Microsoft 365 内幕风险管理为用户提供了从通信合规性中受益的权限。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

管理员和合规性专家在 Microsoft 365 合规性中心创建通信合规性策略。 这些策略定义哪些通信和用户将在组织中进行审阅，定义通信必须满足的自定义条件，并指定应执行审阅的用户。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

管理员选择要包含在通信合规性策略中的特定用户或组。 选择组时，他们还可以选择组中要从通信合规性策略中排除的特定用户。 有关通信合规性策略的详细信息，请参阅 [Microsoft 365 中的通信合规性](https://docs.microsoft.com/microsoft-365/compliance/communication-compliance-configure)。

## <a name="insider-risk-management"></a>内部风险管理

内幕风险管理是 Microsoft 365 中的一种解决方案，可帮助您检测、调查并对组织中的危险活动采取措施，从而帮助最大限度地减少内部风险。
自定义策略允许您检测组织中的恶意和无意风险的活动并采取措施，包括在需要时向 Microsoft 高级电子数据展示上报案例。 组织中的风险分析师可以快速采取适当的措施，以确保用户符合组织的合规性标准。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

用户通过让其活动受到风险监控来获得好处。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>哪些许可证为用户提供了从服务中获益的权限？

Microsoft 365 E5/A5、Microsoft 365 E5/A5 合规性和 Microsoft 365 内幕风险管理为用户提供了从内幕风险管理中受益的权限。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

必须在 Microsoft 365 合规性中心中创建内幕风险管理策略，并将其分配给用户。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

在 Microsoft 365 合规性中心创建策略时，在 " **选择用户和组** " 页上，选择 " **选择用户或组** " 以仅选择许可用户，或者，如果所有用户都获得许可，则可以选中 " **所有用户和已启用邮件的组** " 复选框。 有关详细信息，请参阅 [内幕风险管理入门](https://docs.microsoft.com/microsoft-365/compliance/insider-risk-management-configure)。

## <a name="conditional-access-policies"></a>条件访问策略

条件访问是 Azure Active Directory 用来将信号放在一起以做出决定以及强制实施组织策略的工具。 条件访问是恒等驱动控制平面的核心。 条件访问策略的最简单之处是 if 语句。 如果用户想要访问某个资源，则必须完成某一操作。 示例：工资经理想要访问工资应用程序，并需要执行多重身份验证以对其进行访问。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中受益？

企业移动性 + 安全 E3/A3、Microsoft 365 F3/E3/A3/商业高级版和 Azure Active Directory 高级计划1的许可用户可从条件访问策略中受益。 企业移动性 + 安全性 E5/A5/G5 的许可用户： Microsoft 365 E5/A5、Microsoft E5 Security 和 Azure Active Directory 高级计划2可从身份保护 (基于风险的条件访问策略) 中受益。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

安全操作分析师和安全性专家通过具备对用户实施组织策略的能力，要求他们在授予对公司内容的访问权限之前满足特定的条件，从而获益。 最终用户可以随时随地访问他们的工作，同时还能在保护组织资产时随时访问他们的工作。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

默认情况下，在租户级别为租户中的所有用户启用条件访问功能。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

若要明确标识保护和条件访问，用户必须包含在组中或添加到条件访问策略中。 在条件访问策略中，users 和 groups 条件是必需的。 在策略中，您可以选择 " **所有用户** " 或 "特定用户和组"。 您应仅选择经过适当授权的用户和组。 有关详细信息，请参阅 [在 Azure Active Directory 条件访问中有哪些条件？](https://docs.microsoft.com/azure/active-directory/conditional-access/conditions)。

## <a name="advanced-audit"></a>高级审核

Microsoft 365 中的高级审核为用户和管理员活动提供了为期一年的审核日志保留，并提供了创建自定义审核日志保留策略以管理其他 Microsoft 365 服务的审核日志保留的功能。 此外，它还提供对 Office 365 管理活动 API 的调查和高带宽访问的关键事件的访问。 有关详细信息，请参阅 [Microsoft 365 中的高级审核](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit)。

您还可以使用附加 SKU 为10年启用保留期。 将需要在2021早些时候启动附加 SKU。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中受益？

Office 365 E5、Microsoft 365 E5、Microsoft 365 E5 合规性和 Microsoft 365 电子数据展示和审核的许可用户可从高级审核中受益。

具有高级审核的许可用户和为期10年的审核日志保留加载项可以从10年审核日志保留中受益。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

由于 Microsoft 365 服务中与用户活动相关的审核记录可保留最多一年，因此用户从高级审核中受益。 此外，还记录了高值审核事件，如访问或读取用户邮箱中的项目的时间。 有关详细信息，请参阅 [Microsoft 365 中的高级审核](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit)。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

默认情况下，在租户级别为拥有 Office 365 或 Microsoft 365 E5 订阅的所有组织启用高级审核，并自动为用户在 Azure Active Directory、Exchange 和 SharePoint 中具有相应许可证) 的用户执行的 (活动提供一年审核日志保留。 此外，组织可以使用审核日志保留策略来管理其他 Microsoft 365 服务中的活动生成的审核记录的保留期。 还可以使用相同的保留策略启用10年审核日志保留功能。 有关详细信息，请参阅[管理审核日志保留策略](https://docs.microsoft.com/microsoft-365/compliance/audit-log-retention-policies)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

审核日志的一年保留时间和关键事件的审核仅适用于具有相应许可证的用户。 此外，管理员还可以使用审核日志保留策略为特定用户的审核日志指定较短的保留期限。

10年的审核日志保留仅适用于具有相应加载项许可证的用户。 将需要在2021早些时候启动附加 SKU。
