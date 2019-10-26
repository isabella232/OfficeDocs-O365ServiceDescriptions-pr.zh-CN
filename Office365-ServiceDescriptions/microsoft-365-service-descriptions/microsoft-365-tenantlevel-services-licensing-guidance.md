---
title: Microsoft 365 租户级服务许可指南
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 本文提供适用于 Microsoft 365 租户级服务的许可指南，以帮助避免由于未经许可访问而导致的潜在服务中断。
ms.openlocfilehash: b0ff01a92ed1d3c3a5284fd3eba45241a65c0a6a
ms.sourcegitcommit: fb245074a57da585566096f6956d37325f451262
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/26/2019
ms.locfileid: "37734190"
---
# <a name="microsoft-365-tenant-level-services-licensing-guidance"></a>Microsoft 365 租户级服务许可指南

在本文中，租户级服务是一种在线服务，&mdash;在为租户中的任何用户购买（独立或作为 Office 365 或 Microsoft 365 计划的一部分）&mdash;时，将为租户中的所有用户激活或完全激活。 尽管一些未经许可的用户在技术上能够访问该服务，但您希望从该服务获益的任何用户都需要许可证。

> [!NOTE]
> 某些租户服务当前不能限制特定用户的优势。 应采取措施将服务的好处限制为许可用户。 这有助于避免您的组织在获得目标功能后对组织造成潜在的服务中断。

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure Active Directory 标识保护（AADIP）是 Azure Active Directory 高级 P2 计划的一项功能，可让你检测影响组织标识的潜在漏洞，并将自动响应配置为检测到的可疑与您的组织的标识相关的操作，并调查可疑事件并采取适当的措施来解决这些问题。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中受益？

企业移动性 + 安全性 E5/A5/G5 的许可用户、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 和 Azure Active Directory 高级计划2可以从 AADIP 获益。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

SecOps 分析师和安全专家将从基于机器学习算法的已标记用户和风险事件的合并视图中获益。 最终用户可通过基于风险的条件访问提供自动保护，并通过对漏洞的操作提供改进的安全性来获得好处。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

默认情况下，AADIP 功能在租户级别为租户中的所有用户启用。 有关配置 AADIP 的信息，请参阅[启用 Azure Active Directory Identity Protection](https://docs.microsoft.com/azure/active-directory/identity-protection/enable)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

管理员可以通过分配定义密码重置级别的风险策略并仅允许许可用户访问，来对 AADIP 进行作用域。 有关如何对 AADIP 部署进行作用域的说明，请参阅[配置登录风险策略](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy)。

## <a name="azure-advanced-threat-protection"></a>Azure 高级威胁防护

Azure 高级威胁防护（ATP）是一项云服务，可帮助保护企业混合环境，使其免受多种类型的高级目标网络攻击和内幕威胁的侵扰。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中受益？

企业移动性 + 安全性 E5/A5/G5 的许可用户，Microsoft 365 E5/A5/G5，Microsoft 365 E5/A5/G5，以及 Azure 高级威胁防护可从 Azure ATP 获益。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

SecOp 分析师和安全性专家将受益于 Azure ATP 检测和调查高级威胁、已泄露身份和恶意内幕活动的能力。 最终用户通过 Azure ATP 监视数据来获得好处。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

默认情况下，在租户级别为租户中的所有用户启用 Azure ATP 功能。 有关配置 Azure ATP 的信息，请参阅[Create a AZURE atp instance](https://docs.microsoft.com/azure-advanced-threat-protection/install-atp-step1)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

Microsoft 为许可用户提供威胁检测功能。

## <a name="azure-information-protection"></a>Azure 信息保护

Azure 信息保护（AIP）可帮助组织发现、分类、标记和保护敏感文档和电子邮件。 管理员可以定义规则和条件以自动应用标签，用户可以手动应用标签，也可以在向用户提供有关应用标签&mdash;的建议时使用二者的组合。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中受益？

Microsoft 365 F1、Microsoft 365 商业版、Microsoft 365 E3/A3/G3 和 AIP Plan 1 的许可用户可从 AIP 计划1获益。 Microsoft 365 E5/A5/G5 的许可用户、Microsoft 365 E5/A5/G5 合规性和 AIP 计划2可从 AIP 计划2中受益。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

AIP 扫描程序功能会自动分类、标记和保护驻留在本地文件存储库中的文件。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

默认情况下，AIP 功能在租户级别为租户中的所有用户启用。 有关为许可用户配置 AIP 策略的信息，请参阅[激活 Azure 权限管理](https://docs.microsoft.com/azure/information-protection/activate-service)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

AIP 功能策略（扫描程序功能除外）可以限定为特定的组或用户;可以对注册表进行编辑，以防止未授权的用户运行 AIP 分类或标记功能。 有关如何对 AIP 部署进行作用域的说明，请参阅[配置 Azure 信息保护策略](https://docs.microsoft.com/azure/information-protection/configure-policy)。

对于 AIP 扫描程序功能，Microsoft 不会承诺向未获得许可的用户提供文件分类、标记或保护功能。 随着时间的推移，将向 AIP 中添加许可证检查或目标工具，以确保将扫描程序功能分配给许可用户。

## <a name="office-365-advanced-threat-protection"></a>Office 365 高级威胁防护

高级威胁防护（ATP）可帮助组织防御复杂的攻击，如网络钓鱼和零日恶意软件。 它还通过关联大量数据中的信号来提供可操作的见解，以帮助确定、设置优先级，并提供有关如何解决潜在威胁的建议。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中受益？

Office 365 E5/A5/G5 许可用户，Microsoft 365 E5/A5/G5，Microsoft 365 E5/A5/G5 Security，Microsoft 365 Business 和 Office 365 ATP 计划1和2可从 ATP 获益。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

ATP 可保护用户免受复杂攻击（如网络钓鱼和零天恶意软件）的攻击。 有关计划1和计划2中提供的服务的完整列表，请参阅[Office 365 高级威胁防护](https://products.office.com/exchange/advance-threat-protection)。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

默认情况下，在租户级别为租户中的所有用户启用 ATP 功能。 有关为许可用户配置 ATP 策略的信息，请参阅[Office 365 高级威胁防护](https://docs.microsoft.com/office365/securitycompliance/office-365-atp)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

若要对 ATP 进行作用域，请遵循安全链接和安全附件部署策略：

  - 有关为许可用户配置安全链接的信息，请参阅[设置 Office 365 ATP 安全链接策略](https://docs.microsoft.com/office365/securitycompliance/set-up-atp-safe-links-policies)。

  - 有关为许可用户配置安全附件的信息，请参阅[设置 Office 365 ATP 安全附件策略](https://docs.microsoft.com/office365/securitycompliance/set-up-atp-safe-attachments-policies)。

## <a name="office-365-cloud-app-security"></a>Office 365 云应用安全

Office 365 云应用安全（OCAS）是 Microsoft 云应用安全性的子集，其中的功能仅限于 Office 365，而无需对第三方云应用和 IaaS 服务进行额外的安全性。

OCAS 使组织能够深入了解他们的工作效率云应用和服务，提供了完善的分析来识别和防御网络威胁，并使&mdash;他们可以控制数据在 Office 365 之间的传输方式。

若要比较功能，请参阅[Microsoft Cloud App security 与 Office 365 云应用安全性之间的差异](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365)。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中受益？

Office 365 E5/G5 的许可用户可以从 OCAS 获益。

有关详细信息，请参阅[Microsoft Cloud App Security 授权数据表](https://www.aka.ms/mcaslicensing)。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

OCAS 发现影子它，提供了 Office 365 之间的威胁防护，并可以控制哪些应用有权访问 Office 365 数据。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

默认情况下，OCAS 功能在租户级别为租户中的所有用户启用。

有关配置服务的信息，请参阅[Basic setup For Cloud App Security](https://docs.microsoft.com/cloud-app-security/general-setup)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

管理员可以对 OCAS 部署进行作用域，以强制实施特定应用程序的访问方式并限制由 Office 365 云应用安全性监控的用户组。 有关详细信息，请参阅[作用域部署](https://docs.microsoft.com/cloud-app-security/scoped-deployment)。

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security （MCAS）是一个云访问安全代理（CASB）解决方案，它为组织提供了其云应用和服务的可见性，提供了完善的分析来识别和防御网络威胁，并让他们控制数据跨&mdash;任意云应用传播。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中受益？

授权用户的 MCAS，企业移动性 + 安全性 E5/A5/G5，Microsoft 365 E5/A5/G5 和 Microsoft 365 E5/A5/G5 安全性可从 MCAS 获益。

Azure AD P1 的许可用户可以从 MCAS 中的发现功能中受益。

若要从 MCAS 中的[条件访问应用程序控制](https://docs.microsoft.com/cloud-app-security/proxy-intro-aad)功能中受益，还必须授予用户 Azure Active Directory P1 （包含在企业移动性 + 安全 E3/A3/G3、企业移动性 + 安全性 E5/A5/G5、Microsoft 365 E3/A3/G3、Microsoft 365 E5/A5/G5 和 Microsoft 365 E5/A5/G5 安全性。

若要从[自动标记](https://docs.microsoft.com/cloud-app-security/data-protection-policies)中受益，用户必须获得 Azure 信息保护 P2 的许可，该版本包含在企业移动性 + 安全 E5/A5/g5 中，Microsoft 365 E5/A5/G5 和 Microsoft 365 E5/A5/G5 合规性。

有关详细信息，请参阅[Microsoft Cloud App Security 授权数据表](https://www.aka.ms/mcaslicensing)。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

MCAS 发现和评估阴影，提供跨第一方云应用程序的威胁保护，并在第一方和第三方云应用中保护信息。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

默认情况下，MCAS 功能在租户级别为租户中的所有用户启用。

有关为许可用户配置 Microsoft 云应用安全策略的信息，请参阅[Microsoft Cloud App security 概述](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

管理员可以使用服务中提供的作用域部署功能将 MCAS 部署限定为许可用户。 有关详细信息，请参阅[作用域部署](https://docs.microsoft.com/cloud-app-security/scoped-deployment)。

## <a name="office-365-advanced-data-governance"></a>Office 365 高级数据管理

高级数据治理（ADG）可帮助组织通过启用保留和删除的策略满足信息治理要求。 ADG 允许组织根据敏感信息类型自动标记内容，并对该内容应用调控策略。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中受益？

许可用户的 Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 合规性和 Office 365 高级合规性可以从 ADG 获益。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

ADG 允许用户将标签应用于特定数据，以对特定的策略进行对齐、自动将内容标记为记录，以及管理从声明到处置的完整记录过程。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

默认情况下，ADG 功能在租户级别为租户中的所有用户启用。 有关配置 ADG 以将自动标记和策略应用于许可用户的信息，请参阅[保留标签概述](https://docs.microsoft.com/office365/securitycompliance/labels)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

可以通过自动分类将 ADG 保留策略应用于特定位置（工作组网站、组网站等）的许可用户。 有关应用 ADG 保留策略的说明，请参阅[将保留策略应用于整个组织或特定位置](https://docs.microsoft.com/office365/securitycompliance/retention-policies#applying-a-retention-policy-to-an-entire-organization-or-specific-locations)。

## <a name="office-365-advanced-ediscovery"></a>Office 365 高级电子数据展示

Office 365 高级电子数据展示为 IT 和公司内部的法律部门提供调查和电子数据展示解决方案，以确定、收集、保留、减少和查看与调查或诉讼相关的内容，然后再导出Office 365 系统。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中受益？

许可用户的 Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 合规性和 Office 365 高级合规性可以从高级电子数据展示中受益。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

当用户选择作为数据管理员（具有文档或电子文件的管理控制）时，用户将从高级电子数据展示中受益。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

默认情况下，当管理员在安全 & 合规中心中分配电子数据展示权限时，将在租户级别为租户中的所有用户启用高级电子数据展示功能。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

通过使用高级电子数据展示中的内置保管人管理工具，电子数据展示管理员可以选择特定用户作为事例的数据保管人，如[将保管人添加到高级电子数据展示事例](https://docs.microsoft.com/office365/securitycompliance/compliance20/add-custodians-to-case)中所述。

## <a name="office-365-customer-key"></a>Office 365 客户密钥

使用 "客户密钥"，可以控制组织的加密密钥，并配置 Office 365 以使用它们在 Microsoft 数据中心中对静态数据进行加密。 换句话说，客户密钥允许您使用自己的密钥添加属于您的加密层。 静态数据包含来自 Exchange Online 和 Skype for business 的数据，这些数据存储在 SharePoint Online 和 OneDrive for business 中的邮箱和文件中。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中受益？

许可用户的 Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 合规性，以及 Office 365 高级合规性可从客户密钥获益。 若要获得客户密钥的全部好处，您还必须具有 Azure Key Vault 的订阅。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

用户可通过在应用程序层使用提供、控制和管理自己的组织的加密密钥在应用程序层对其数据进行加密，从而获得客户密钥的好处。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

可以为存储在 Exchange Online 和 Skype for business 邮箱以及 SharePoint Online 和 OneDrive for business 文件中的所有数据启用 Office 365 客户密钥加密密钥。 有关配置 Office 365 客户密钥以加密静态数据的信息，请参阅[使用客户密钥控制 office 365 中的数据](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

若要将加密密钥分配给 Office 365 和/或 Microsoft 365 租户中的数据以供许可用户使用，请按照客户密钥加密密钥部署说明进行操作：

  - 对于 SharePoint Online 和 OneDrive for business，一个或多个网站上的文件可使用客户密钥进行加密，如下所述：为[SharePoint Online 和 OneDrive For Business 设置客户密钥](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key#office-365-setting-up-customer-key-for-sharepoint-online-and-onedrive-for-business)。

  - 对于 Exchange Online 和 Skype for business Online，可以使用以下所述的客户密钥对邮箱进行加密：[设置 Exchange Online 和 Skype for business 的客户密钥](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key#office-365-setting-up-customer-key-for-exchange-online-and-skype-for-business)

## <a name="office-365-customer-lockbox"></a>Office 365 客户密码箱

客户密码箱通过让客户能够为服务操作提供显式访问授权，从而提供了一个额外的控制层。 通过演示如何将过程用于显式数据访问授权，客户密码箱还可以帮助组织满足特定合规性义务，如 HIPAA 和 FEDRAMP。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中受益？

许可用户的 Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 合规性，以及 Office 365 高级合规性可从客户密码箱获益。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

用户可以从客户密码箱获益，确保 Microsoft 无需在未经客户明确批准的情况下即可在 Microsoft 不能访问其内容的情况下执行服务操作。 客户密码箱将客户引入审批工作流，以获取访问其内容的请求。 有时，Microsoft 工程师会在支持流程中参与诊断和修复客户报告的问题。 在大多数情况下，通过 Microsoft 为其服务提供的大量遥测和调试工具解决了问题。 但是，在某些情况下，可能需要 Microsoft 工程师访问客户内容以确定根本原因并解决问题。 客户密码箱要求工程师在审批工作流的最后步骤中请求从客户进行访问。 这为组织提供了批准或拒绝这些请求的选项，这些请求使他们可以直接控制 Microsoft 工程师是否可以访问组织的最终用户数据。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

管理员可以在 Microsoft 365 管理中心启用客户密码箱控件。 有关详细信息，请参阅[Office 365 中的客户密码箱](https://docs.microsoft.com/Office365/Admin/manage/customer-lockbox-requests)。 当客户密码箱打开时，在访问其任何内容之前，需要 Microsoft 获取组织的批准。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

Microsoft 为 Office 365 组织中的用户提供客户密码箱访问控制审批请求。

## <a name="privileged-access-management-in-office-365"></a>Office 365 中的特权访问管理

特权访问管理（PAM）提供对 Office 365 中的特权管理任务的精细访问控制。 启用 PAM 后，用户将需要通过高度范围和时间限制的审批工作流请求实时访问，以完成提升和特权的任务。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中受益？

许可用户的 Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 合规性和 Office 365 高级合规性可以从 PAM 中受益。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

启用 PAM 可让组织以零作为自主权限运行。 用户从增加的防御层中受益，以防止因提供对其数据的 unfettered 访问而产生的漏洞。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

默认情况下，在租户级别为租户中的所有用户启用 PAM 功能。 有关配置 PAM 策略的信息，请参阅[在 Office 365 中配置特权访问管理](https://docs.microsoft.com/office365/securitycompliance/privileged-access-management-configuration)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

客户可以通过审核人组和访问策略（可应用于许可用户）在每用户的基础上管理 PAM。 有关详细信息，请参阅[Office 365 中的特权访问管理](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751)。

## <a name="data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Exchange Online、SharePoint Online 和 OneDrive for business 的数据丢失防护

对于 Exchange Online、SharePoint Online 和 OneDrive for Business 的数据丢失防护（DLP），组织可以通过电子邮件和文件（包括存储在 Microsoft 团队文件中的文件）识别、监视和自动保护敏感信息。存储库）。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中受益？

Office 365 E3/A3/G3、Microsoft 365 Business、Microsoft 365 A1/E3/A3/G3 和 Office 365 数据丢失防护的许可用户可受益于 DLP for Exchange Online、SharePoint Online 和 OneDrive for Business。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

当检查其电子邮件和文件中的敏感信息（如组织的 DLP 策略中配置）时，用户将受益于 DLP for Exchange Online、SharePoint Online 和 OneDrive for business。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

默认情况下，Exchange Online 电子邮件、SharePoint 网站和 OneDrive 帐户为租户中的所有用户启用这些 DLP 功能的*位置（工作负荷）* 。 有关使用 DLP 策略的详细信息，请参阅[数据丢失防护概述](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

管理员可以在 "Office 365 安全 & 合规中心" 中的 "**数据丢失防护** > **位置**" 下自定义位置（工作负荷）、包含的用户和排除的用户。

## <a name="data-loss-prevention-for-teams-chat-and-channel-messages"></a>工作组聊天和频道消息的数据丢失防护

使用数据丢失防护（DLP）获取团队聊天和频道消息时，组织可以阻止包含敏感信息的聊天和频道消息，如财务信息、个人标识信息、与运行状况相关的信息，或其他机密信息。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中受益？

Office 365 E5/A5/G5 许可用户，Microsoft 365 E5/A5/G5，Microsoft 365 E5/A5/G5 合规性，Office 365 高级合规性可以从 DLP for team chat and 频道消息中获益。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

通过在组织的 DLP 策略中配置的敏感信息检查其传出聊天和频道消息中的敏感信息，发件人会获得好处。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

默认情况下，团队聊天和频道消息是租户中所有用户的这些 DLP 功能的*已启用位置（工作负荷）* 。 有关使用 DLP 策略的详细信息，请参阅[数据丢失防护概述](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

管理员可以在 "Office 365 安全 & 合规中心" 中的 "**数据丢失防护** > **位置**" 下自定义位置（工作负荷）、包含的用户和排除的用户。

## <a name="information-barriers"></a>信息屏障

信息障碍是管理员可以配置的用于阻止个人或组相互通信的策略。 例如，如果一个部门处理的信息不应与其他部门共享，或者必须阻止某个组与外部联系人通信，则这将非常有用。 信息屏障策略也阻止了查找和发现。 这意味着，如果您尝试与不应与之通信的人员进行通信，则不会在人员选取器中找到该用户。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中受益？

许可用户的 Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 合规性和 Office 365 高级合规性可以从信息障碍中受益。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

当限制用户与其他人通信时，他们将受益于信息障碍的高级合规性功能。 例如：

| 应用场景                                                                                                                                                                                                              | 需要许可证的是谁？ |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| 两组（组1和组2）无法相互通信（即，限制组1用户与组2用户通信，而组2用户限制与组1用户通信。 | 组1和组2中的用户                    |
| 限制组1中的用户与公司的其余用户通信。                                                                                                                                       | 仅限组1中的用户                                |
| 公司的其余部分受到限制，无法与组1通信。                                                                                                                                                 | 除组1中的用户之外的所有用户                    |
| 限制组1用户与组2用户通信，但组2用户可以与组1用户进行通信。                                                                                              | 仅限组1中的用户                                |

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

管理员在安全 & 合规中心中使用 PowerShell cmdlet 创建和管理信息障碍策略。 必须为管理员分配 Microsoft 365 企业全局管理员、Office 365 全局管理员或合规性管理员角色，以创建信息障碍策略。 默认情况下，这些策略适用于租户中的所有用户。 有关信息障碍的详细信息，请参阅[Microsoft 团队中的信息障碍](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

管理员可以在 Office 365 安全 & 合规中心中自定义位置（工作负荷）、包含的用户以及排除的用户。 例如，如果所有用户均为 Office 365 E3 许可，并且没有许可 Office 365 高级合规性/E5，则无需为组织创建任何信息障碍策略。 有关详细信息，请参阅[Microsoft 团队中的信息障碍](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)。

## <a name="office-365-message-encryption"></a>Office 365 邮件加密

Office 365 邮件加密 (OME) 是一项基于 Azure 权限管理 (Azure RMS) 构建的服务，允许您向组织内外发送经加密的电子邮件，而无需考虑目标电子邮件地址（Gmail、Yahoo!Mail、Outlook.com 等）。

若要查看加密邮件，收件人可以使用一次性密码、通过 Microsoft 帐户登录或使用与 Office 365 关联的工作或学校帐户登录。 此外，收件人也可发送加密回复。 他们不需要 Office 365 订阅即可查看加密邮件或发送加密答复。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中受益？

Office 365 E3/A3/G3、Microsoft 365 E3/A3/G3 和 Azure 信息保护计划1的许可用户可受益于 Office 365 邮件加密。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

邮件发件人可受益于对 Office 365 邮件加密提供的敏感电子邮件的新增控制。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

管理员在 "**邮件流** > **规则**" 下的 Exchange 管理中心中创建和管理 Office 365 邮件加密策略。 默认情况下，这些规则适用于租户中的所有用户。 有关设置新的 Office 365 邮件加密功能的详细信息，请参阅[设置新的 office 365 邮件加密功能](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

管理员应将仅限 Office 365 邮件加密的邮件流规则应用于许可用户。 有关定义邮件流规则的详细信息，请参阅[在 Office 365 中定义用于加密电子邮件的邮件流规则](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)。


## <a name="office-365-advanced-message-encryption"></a>Office 365 高级邮件加密

高级邮件加密帮助客户满足法规遵从性义务，这些要求对外部收件人和对加密电子邮件的访问权限要求更灵活的控制。 通过高级邮件加密，管理员可以通过使用可检测敏感信息类型（例如，个人标识信息或财务或运行状况 Id）的自动策略来控制在组织外共享的敏感电子邮件，或者它们可以通过应用自定义电子邮件模板，并通过安全 web 门户终止对加密电子邮件的访问，从而使用关键字增强保护。 此外，管理员可以随时撤销访问权限，从而进一步控制通过安全 web 门户外部访问的加密电子邮件。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中受益？

许可用户的 Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 合规性和 Office 365 高级合规性可以从高级邮件加密中受益。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

邮件发件人可受益于对高级邮件加密提供的敏感电子邮件所添加的控制。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

管理员在 "邮件流规则" 下的 Exchange 管理中心中创建和管理高级邮件加密策略。 默认情况下，这些规则适用于租户上的所有用户。 有关设置新的邮件加密功能的详细信息，请参阅[设置新的 Office 365 邮件加密功能](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

管理员应将邮件流规则仅应用于已授权用户的高级邮件加密。 有关定义邮件流规则的详细信息，请参阅[在 Office 365 中定义用于加密电子邮件的邮件流规则](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)。

## <a name="supervision-policies"></a>监督策略

Office 365 中的监督策略使您可以捕获指定审阅者进行检查的员工通信。 您可以定义用于捕获组织中的内部和外部电子邮件、Microsoft 团队或第三方通信的特定策略。 然后，审阅者可以检查这些邮件，以确保它们符合组织的邮件标准，并使用分类类型解决这些问题。

### <a name="which-users-benefit-from-the-service"></a>哪些用户从服务中受益？

许可用户的 Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 合规性和 Office 365 高级合规性可以从监督策略中受益。

### <a name="how-do-users-benefit-from-the-service"></a>用户如何从服务中获益？

用户通过监督策略监视其通信，从而从服务中获益。

### <a name="how-is-the-service-provisioneddeployed"></a>服务是如何设置/部署的？

管理员在安全 & 合规中心中创建监督策略。 这些策略定义哪些通信和用户将在组织中进行审阅，定义通信必须满足的自定义条件，并指定应执行审阅的用户。
 
### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>如何将服务仅应用于受该服务授权的租户中的用户？

管理员选择要包含在监督策略中的特定用户或组。 在选择组时，他们还可以选择组中要从监督策略中排除的特定用户。 有关监督策略的详细信息，请参阅[Office 365 中的监察策略](https://docs.microsoft.com/office365/SecurityCompliance/supervision-policies)。
