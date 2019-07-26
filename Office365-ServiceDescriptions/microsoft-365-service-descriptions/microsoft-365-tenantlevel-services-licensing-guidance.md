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
description: 本文提供适用于 Microsoft 365 租户级服务的许可指南, 以帮助避免由于未经许可访问而导致的潜在服务中断。
ms.openlocfilehash: a3a3c969b7857764610694698f877b4e05231e01
ms.sourcegitcommit: d748b75a186faf3d303437cbb78d6ad6b3f31baf
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/26/2019
ms.locfileid: "35908719"
---
# <a name="microsoft-365-tenant-level-services-licensing-guidance"></a><span data-ttu-id="f4629-103">Microsoft 365 租户级服务许可指南</span><span class="sxs-lookup"><span data-stu-id="f4629-103">Microsoft 365 Tenant-Level Services Licensing Guidance</span></span>

<span data-ttu-id="f4629-104">在本文中, 租户级服务是一种在线服务,&mdash;在为租户中的任何用户购买 (独立或作为 Office 365 或 Microsoft 365 计划的一部分)&mdash;时, 将为租户中的所有用户激活或完全激活。</span><span class="sxs-lookup"><span data-stu-id="f4629-104">For the purposes of this article, a tenant-level service is an online service that&mdash;when purchased for any user in the tenant (standalone or as part of Office 365 or Microsoft 365 plans)&mdash;is activated in part or in full for all users in the tenant.</span></span> <span data-ttu-id="f4629-105">尽管一些未经许可的用户在技术上能够访问该服务, 但您希望从该服务获益的任何用户都需要许可证。</span><span class="sxs-lookup"><span data-stu-id="f4629-105">Although some unlicensed users may technically be able to access the service, a license is required for any user that you intend to benefit from the service.</span></span>

> [!NOTE]
> <span data-ttu-id="f4629-106">某些租户服务当前不能限制特定用户的优势。</span><span class="sxs-lookup"><span data-stu-id="f4629-106">Some tenant services are not currently capable of limiting benefits to specific users.</span></span> <span data-ttu-id="f4629-107">应采取措施将服务的好处限制为许可用户。</span><span class="sxs-lookup"><span data-stu-id="f4629-107">Efforts should be taken to limit the service benefits to licensed users.</span></span> <span data-ttu-id="f4629-108">这有助于避免您的组织在获得目标功能后对组织造成潜在的服务中断。</span><span class="sxs-lookup"><span data-stu-id="f4629-108">This will help avoid potential service disruption to your organization once targeting capabilities are available.</span></span>

## <a name="azure-active-directory-identity-protection"></a><span data-ttu-id="f4629-109">Azure Active Directory Identity Protection</span><span class="sxs-lookup"><span data-stu-id="f4629-109">Azure Active Directory Identity Protection</span></span>

<span data-ttu-id="f4629-110">Azure Active Directory 标识保护 (AADIP) 是 Azure Active Directory 高级 P2 计划的一项功能, 可让你检测影响组织标识的潜在漏洞, 并将自动响应配置为检测到的可疑与您的组织的标识相关的操作, 并调查可疑事件并采取适当的措施来解决这些问题。</span><span class="sxs-lookup"><span data-stu-id="f4629-110">Azure Active Directory Identity Protection (AADIP) is a feature of the Azure Active Directory Premium P2 plan that enables you to detect potential vulnerabilities affecting your organization's identities, configure automated responses to detected suspicious actions that are related to your organization's identities, and investigate suspicious incidents and take appropriate action to resolve them.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="f4629-111">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="f4629-111">Which users benefit from the service?</span></span>

<span data-ttu-id="f4629-112">企业移动性 + 安全性 E5、Microsoft 365 E5、Microsoft 365 E5 Security 和 Azure Active Directory 高级计划2的许可用户可从 AADIP 获益。</span><span class="sxs-lookup"><span data-stu-id="f4629-112">Licensed users of Enterprise Mobility + Security E5, Microsoft 365 E5, Microsoft 365 E5 Security, and Azure Active Directory Premium Plan 2 can benefit from AADIP.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="f4629-113">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="f4629-113">How do users benefit from the service?</span></span>

<span data-ttu-id="f4629-114">SecOps 分析师和安全专家将从基于机器学习算法的已标记用户和风险事件的合并视图中获益。</span><span class="sxs-lookup"><span data-stu-id="f4629-114">SecOps analysts and security professionals benefit from having consolidated views of flagged users and risk events based on machine learning algorithms.</span></span> <span data-ttu-id="f4629-115">最终用户可通过基于风险的条件访问提供自动保护, 并通过对漏洞的操作提供改进的安全性来获得好处。</span><span class="sxs-lookup"><span data-stu-id="f4629-115">End users benefit from the automatic protection provided through risk-based Conditional Access and the improved security provided by acting on vulnerabilities.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="f4629-116">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="f4629-116">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="f4629-117">默认情况下, AADIP 功能在租户级别为租户中的所有用户启用。</span><span class="sxs-lookup"><span data-stu-id="f4629-117">By default, AADIP features are enabled at the tenant level for all users within the tenant.</span></span> <span data-ttu-id="f4629-118">有关配置 AADIP 的信息, 请参阅[启用 Azure Active Directory Identity Protection](https://docs.microsoft.com/azure/active-directory/identity-protection/enable)。</span><span class="sxs-lookup"><span data-stu-id="f4629-118">For information on configuring AADIP, see [Enabling Azure Active Directory Identity Protection](https://docs.microsoft.com/azure/active-directory/identity-protection/enable).</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="f4629-119">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="f4629-119">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="f4629-120">管理员可以通过分配定义密码重置级别的风险策略并仅允许许可用户访问, 来对 AADIP 进行作用域。</span><span class="sxs-lookup"><span data-stu-id="f4629-120">Admins can scope AADIP by assigning risk policies that define the level for password resets and allowing access for licensed users only.</span></span> <span data-ttu-id="f4629-121">有关如何对 AADIP 部署进行作用域的说明, 请参阅[配置登录风险策略](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy)。</span><span class="sxs-lookup"><span data-stu-id="f4629-121">For instructions on how to scope AADIP deployments, see [Configure the sign-in risk policy](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy).</span></span>

## <a name="azure-advanced-threat-protection"></a><span data-ttu-id="f4629-122">Azure 高级威胁防护</span><span class="sxs-lookup"><span data-stu-id="f4629-122">Azure Advanced Threat Protection</span></span>

<span data-ttu-id="f4629-123">Azure 高级威胁防护 (ATP) 是一项云服务, 可帮助保护企业混合环境, 使其免受多种类型的高级目标网络攻击和内幕威胁的侵扰。</span><span class="sxs-lookup"><span data-stu-id="f4629-123">Azure Advanced Threat Protection (ATP) is a cloud service that helps protect enterprise hybrid environments from multiple types of advanced targeted cyber-attacks and insider threats.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="f4629-124">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="f4629-124">Which users benefit from the service?</span></span>

<span data-ttu-id="f4629-125">企业移动性 + 安全性 E5、Microsoft 365 E5、Microsoft 365 E5 Security 和 Azure 高级威胁防护的许可用户可以从 Azure ATP 获益。</span><span class="sxs-lookup"><span data-stu-id="f4629-125">Licensed users of Enterprise Mobility + Security E5, Microsoft 365 E5, Microsoft 365 E5 Security, and Azure Advanced Threat Protection for Users can benefit from Azure ATP.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="f4629-126">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="f4629-126">How do users benefit from the service?</span></span>

<span data-ttu-id="f4629-127">SecOp 分析师和安全性专家将受益于 Azure ATP 检测和调查高级威胁、已泄露身份和恶意内幕活动的能力。</span><span class="sxs-lookup"><span data-stu-id="f4629-127">SecOp analysts and security professionals benefit from the ability of Azure ATP to detect and investigate advanced threats, compromised identities, and malicious insider actions.</span></span> <span data-ttu-id="f4629-128">最终用户通过 Azure ATP 监视数据来获得好处。</span><span class="sxs-lookup"><span data-stu-id="f4629-128">End users benefit by having their data monitored by Azure ATP.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="f4629-129">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="f4629-129">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="f4629-130">默认情况下, 在租户级别为租户中的所有用户启用 Azure ATP 功能。</span><span class="sxs-lookup"><span data-stu-id="f4629-130">By default, Azure ATP features are enabled at the tenant level for all users within the tenant.</span></span> <span data-ttu-id="f4629-131">有关配置 Azure ATP 的信息, 请参阅[Create a AZURE atp instance](https://docs.microsoft.com/azure-advanced-threat-protection/install-atp-step1)。</span><span class="sxs-lookup"><span data-stu-id="f4629-131">For information on configuring Azure ATP, see [Create your Azure ATP instance](https://docs.microsoft.com/azure-advanced-threat-protection/install-atp-step1).</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="f4629-132">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="f4629-132">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="f4629-133">Microsoft 不会承诺向未获得许可的用户提供威胁检测功能。</span><span class="sxs-lookup"><span data-stu-id="f4629-133">Microsoft does not commit to providing threat detection capabilities to users who are not licensed.</span></span> <span data-ttu-id="f4629-134">随着时间的推移, 许可证检查或目标工具将添加到 Azure ATP, 以确保 Azure ATP 功能仅适用于许可用户。</span><span class="sxs-lookup"><span data-stu-id="f4629-134">Over time, license checks or targeted tooling will be added to Azure ATP to ensure Azure ATP functionality is applicable to licensed users only.</span></span>

## <a name="azure-information-protection"></a><span data-ttu-id="f4629-135">Azure 信息保护</span><span class="sxs-lookup"><span data-stu-id="f4629-135">Azure Information Protection</span></span>

<span data-ttu-id="f4629-136">Azure 信息保护 (AIP) 可帮助组织发现、分类、标记和保护敏感文档和电子邮件。</span><span class="sxs-lookup"><span data-stu-id="f4629-136">Azure Information Protection (AIP) helps organizations discover, classify, label, and protect sensitive documents and emails.</span></span> <span data-ttu-id="f4629-137">管理员可以定义规则和条件以自动应用标签, 用户可以手动应用标签, 也可以在向用户提供有关应用标签&mdash;的建议时使用二者的组合。</span><span class="sxs-lookup"><span data-stu-id="f4629-137">Admins can define rules and conditions to apply labels automatically, users can apply labels manually, or a combination of the two can be used&mdash;where users are given recommendations on applying labels.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="f4629-138">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="f4629-138">Which users benefit from the service?</span></span>

<span data-ttu-id="f4629-139">Microsoft 365 F1、Microsoft 365 E3 和 AIP Plan 1 的许可用户可以从 AIP 计划1中受益。</span><span class="sxs-lookup"><span data-stu-id="f4629-139">Licensed users of Microsoft 365 F1, Microsoft 365 E3, and AIP Plan 1 can benefit from AIP Plan 1.</span></span> <span data-ttu-id="f4629-140">Microsoft 365 E5、Microsoft 365 E5 合规性和 AIP 计划2的授权用户可以从 AIP 计划2中受益。</span><span class="sxs-lookup"><span data-stu-id="f4629-140">Licensed users of Microsoft 365 E5, Microsoft 365 E5 Compliance, and AIP Plan 2 can benefit from AIP Plan 2.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="f4629-141">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="f4629-141">How do users benefit from the service?</span></span>

<span data-ttu-id="f4629-142">AIP 扫描程序功能会自动分类、标记和保护驻留在本地文件存储库中的文件。</span><span class="sxs-lookup"><span data-stu-id="f4629-142">The AIP scanner feature automatically classifies, labels, and protects files that reside in on-premises file repositories.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="f4629-143">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="f4629-143">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="f4629-144">默认情况下, AIP 功能在租户级别为租户中的所有用户启用。</span><span class="sxs-lookup"><span data-stu-id="f4629-144">By default, AIP features are enabled at the tenant level for all users within the tenant.</span></span> <span data-ttu-id="f4629-145">有关为许可用户配置 AIP 策略的信息, 请参阅[激活 Azure 权限管理](https://docs.microsoft.com/azure/information-protection/activate-service)。</span><span class="sxs-lookup"><span data-stu-id="f4629-145">For information on configuring AIP policies for licensed users, see [Activating Azure Rights Management](https://docs.microsoft.com/azure/information-protection/activate-service).</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="f4629-146">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="f4629-146">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="f4629-147">AIP 功能策略 (扫描程序功能除外) 可以限定为特定的组或用户;可以对注册表进行编辑, 以防止未授权的用户运行 AIP 分类或标记功能。</span><span class="sxs-lookup"><span data-stu-id="f4629-147">AIP feature policies (except the scanner feature) can be scoped to specific groups or users; registries can be edited to prevent unlicensed users from running AIP classification or labeling features.</span></span> <span data-ttu-id="f4629-148">有关如何对 AIP 部署进行作用域的说明, 请参阅[配置 Azure 信息保护策略](https://docs.microsoft.com/azure/information-protection/configure-policy)。</span><span class="sxs-lookup"><span data-stu-id="f4629-148">For instructions on how to scope AIP deployments, see [Configuring the Azure Information Protection policy](https://docs.microsoft.com/azure/information-protection/configure-policy).</span></span>

<span data-ttu-id="f4629-149">对于 AIP 扫描程序功能, Microsoft 不会承诺向未获得许可的用户提供文件分类、标记或保护功能。</span><span class="sxs-lookup"><span data-stu-id="f4629-149">For the AIP scanner feature, Microsoft does not commit to providing file classification, labeling, or protection capabilities to users who are not licensed.</span></span> <span data-ttu-id="f4629-150">随着时间的推移, 将向 AIP 中添加许可证检查或目标工具, 以确保将扫描程序功能分配给许可用户。</span><span class="sxs-lookup"><span data-stu-id="f4629-150">Over time, license checks or targeted tooling will be added to AIP to ensure the scanner feature is assignable to licensed users.</span></span>

## <a name="office-365-advanced-threat-protection"></a><span data-ttu-id="f4629-151">Office 365 高级威胁防护</span><span class="sxs-lookup"><span data-stu-id="f4629-151">Office 365 Advanced Threat Protection</span></span>

<span data-ttu-id="f4629-152">高级威胁防护 (ATP) 可帮助组织防御复杂的攻击, 如网络钓鱼和零日恶意软件。</span><span class="sxs-lookup"><span data-stu-id="f4629-152">Advanced Threat Protection (ATP) helps protect organizations against sophisticated attacks such as phishing and zero-day malware.</span></span> <span data-ttu-id="f4629-153">它还通过关联大量数据中的信号来提供可操作的见解, 以帮助确定、设置优先级, 并提供有关如何解决潜在威胁的建议。</span><span class="sxs-lookup"><span data-stu-id="f4629-153">It also provides actionable insights by correlating signals from a broad range of data to help identify, prioritize, and provide recommendations on how to address potential threats.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="f4629-154">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="f4629-154">Which users benefit from the service?</span></span>

<span data-ttu-id="f4629-155">Office 365 E5 许可用户: Microsoft 365 E5、microsoft 365 E5 Security、Microsoft 365 Business 和 Office 365 ATP 计划1和2可从 ATP 获益。</span><span class="sxs-lookup"><span data-stu-id="f4629-155">Licensed users of Office 365 E5, Microsoft 365 E5, Microsoft 365 E5 Security, Microsoft 365 Business, and Office 365 ATP Plans 1 and 2 can benefit from ATP.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="f4629-156">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="f4629-156">How do users benefit from the service?</span></span>

<span data-ttu-id="f4629-157">ATP 可保护用户免受复杂攻击 (如网络钓鱼和零天恶意软件) 的攻击。</span><span class="sxs-lookup"><span data-stu-id="f4629-157">ATP protects users from sophisticated attacks such as phishing and zero-day malware.</span></span> <span data-ttu-id="f4629-158">有关计划1和计划2中提供的服务的完整列表, 请参阅[Office 365 高级威胁防护](https://products.office.com/exchange/advance-threat-protection)。</span><span class="sxs-lookup"><span data-stu-id="f4629-158">For the full list of services provided in Plan 1 and Plan 2, see [Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection).</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="f4629-159">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="f4629-159">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="f4629-160">默认情况下, 在租户级别为租户中的所有用户启用 ATP 功能。</span><span class="sxs-lookup"><span data-stu-id="f4629-160">By default, ATP features are enabled at the tenant level for all users within the tenant.</span></span> <span data-ttu-id="f4629-161">有关为许可用户配置 ATP 策略的信息, 请参阅[Office 365 高级威胁防护](https://docs.microsoft.com/office365/securitycompliance/office-365-atp)。</span><span class="sxs-lookup"><span data-stu-id="f4629-161">For information on configuring ATP policies for licensed users, see [Office 365 Advanced Threat Protection](https://docs.microsoft.com/office365/securitycompliance/office-365-atp).</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="f4629-162">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="f4629-162">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="f4629-163">若要对 ATP 进行作用域, 请遵循安全链接和安全附件部署策略:</span><span class="sxs-lookup"><span data-stu-id="f4629-163">To scope ATP, follow the Safe Links and Safe Attachments deployment policies:</span></span>

  - <span data-ttu-id="f4629-164">有关为许可用户配置安全链接的信息, 请参阅[设置 Office 365 ATP 安全链接策略](https://docs.microsoft.com/office365/securitycompliance/set-up-atp-safe-links-policies)。</span><span class="sxs-lookup"><span data-stu-id="f4629-164">For information on configuring Safe Links for licensed users, see [Set up Office 365 ATP Safe Links policies](https://docs.microsoft.com/office365/securitycompliance/set-up-atp-safe-links-policies).</span></span>

  - <span data-ttu-id="f4629-165">有关为许可用户配置安全附件的信息, 请参阅[设置 Office 365 ATP 安全附件策略](https://docs.microsoft.com/office365/securitycompliance/set-up-atp-safe-attachments-policies)。</span><span class="sxs-lookup"><span data-stu-id="f4629-165">For information on configuring Safe Attachments for licensed users, see [Set up Office 365 ATP Safe Attachments policies](https://docs.microsoft.com/office365/securitycompliance/set-up-atp-safe-attachments-policies).</span></span>

## <a name="office-365-cloud-app-security"></a><span data-ttu-id="f4629-166">Office 365 云应用安全</span><span class="sxs-lookup"><span data-stu-id="f4629-166">Office 365 Cloud App Security</span></span>

<span data-ttu-id="f4629-167">Office 365 云应用安全 (OCAS) 是 Microsoft 云应用安全性的子集, 其中的功能仅限于 Office 365, 而无需对第三方云应用和 IaaS 服务进行额外的安全性。</span><span class="sxs-lookup"><span data-stu-id="f4629-167">Office 365 Cloud App Security (OCAS) is a subset of Microsoft Cloud App Security, with features limited to Office 365 and without additional security for third-party cloud apps and IaaS services.</span></span>

<span data-ttu-id="f4629-168">OCAS 使组织能够深入了解他们的工作效率云应用和服务, 提供了完善的分析来识别和防御网络威胁, 并使&mdash;他们可以控制数据在 Office 365 之间的传输方式。</span><span class="sxs-lookup"><span data-stu-id="f4629-168">OCAS gives organizations visibility into their productivity cloud apps and services, provides sophisticated analytics to identify and combat cyber threats, and lets them control how data travels&mdash;across Office 365.</span></span>

<span data-ttu-id="f4629-169">若要比较功能, 请参阅[Microsoft Cloud App security 与 Office 365 云应用安全性之间的差异](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365)。</span><span class="sxs-lookup"><span data-stu-id="f4629-169">To compare features, see [Differences between Microsoft Cloud App Security and Office 365 Cloud App Security](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365).</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="f4629-170">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="f4629-170">Which users benefit from the service?</span></span>

<span data-ttu-id="f4629-171">Office 365 E5 的许可用户可以从 OCAS 获益。</span><span class="sxs-lookup"><span data-stu-id="f4629-171">Licensed users of Office 365 E5 can benefit from OCAS.</span></span>

<span data-ttu-id="f4629-172">有关详细信息, 请参阅[Microsoft Cloud App Security 授权数据表](http://www.aka.ms/mcaslicensing)。</span><span class="sxs-lookup"><span data-stu-id="f4629-172">For more information, see the [Microsoft Cloud App Security Licensing Datasheet](http://www.aka.ms/mcaslicensing).</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="f4629-173">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="f4629-173">How do users benefit from the service?</span></span>

<span data-ttu-id="f4629-174">OCAS 发现影子它, 提供了 Office 365 之间的威胁防护, 并可以控制哪些应用有权访问 Office 365 数据。</span><span class="sxs-lookup"><span data-stu-id="f4629-174">OCAS discovers Shadow IT, provides threat protection across Office 365, and can control which apps have permission to access Office 365 data.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="f4629-175">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="f4629-175">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="f4629-176">默认情况下, OCAS 功能在租户级别为租户中的所有用户启用。</span><span class="sxs-lookup"><span data-stu-id="f4629-176">By default, OCAS features are enabled at the tenant level for all users within the tenant.</span></span>

<span data-ttu-id="f4629-177">有关配置服务的信息, 请参阅[Basic setup For Cloud App Security](https://docs.microsoft.com/cloud-app-security/general-setup)。</span><span class="sxs-lookup"><span data-stu-id="f4629-177">For information on configuring the service, see [Basic setup for Cloud App Security](https://docs.microsoft.com/cloud-app-security/general-setup).</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="f4629-178">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="f4629-178">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="f4629-179">管理员可以对 OCAS 部署进行作用域, 以强制实施特定应用程序的访问方式并限制由 Office 365 云应用安全性监控的用户组。</span><span class="sxs-lookup"><span data-stu-id="f4629-179">Admins can scope OCAS deployments to enforce how certain apps are accessed and limit user groups monitored by Office 365 Cloud App Security.</span></span> <span data-ttu-id="f4629-180">有关详细信息, 请参阅[作用域部署](https://docs.microsoft.com/cloud-app-security/scoped-deployment)。</span><span class="sxs-lookup"><span data-stu-id="f4629-180">For more information, see [Scoped deployment](https://docs.microsoft.com/cloud-app-security/scoped-deployment).</span></span>

## <a name="microsoft-cloud-app-security"></a><span data-ttu-id="f4629-181">Microsoft Cloud App Security</span><span class="sxs-lookup"><span data-stu-id="f4629-181">Microsoft Cloud App Security</span></span>

<span data-ttu-id="f4629-182">Microsoft Cloud App Security (MCAS) 是一个云访问安全代理 (CASB) 解决方案, 它为组织提供了其云应用和服务的可见性, 提供了完善的分析来识别和防御网络威胁, 并让他们控制数据跨&mdash;任意云应用传播。</span><span class="sxs-lookup"><span data-stu-id="f4629-182">Microsoft Cloud App Security (MCAS) is a Cloud Access Security Broker (CASB) solution that gives organizations visibility into their cloud apps and services, provides sophisticated analytics to identify and combat cyber threats, and lets them control how data travels&mdash;across any cloud app.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="f4629-183">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="f4629-183">Which users benefit from the service?</span></span>

<span data-ttu-id="f4629-184">MCAS 的许可用户 (企业移动性 + 安全性 E5、Microsoft 365 E5 和 Microsoft 365 E5 安全性) 可以从 MCAS 获益。</span><span class="sxs-lookup"><span data-stu-id="f4629-184">Licensed users of MCAS, Enterprise Mobility + Security E5, Microsoft 365 E5, and Microsoft 365 E5 Security can benefit from MCAS.</span></span>

<span data-ttu-id="f4629-185">Azure AD P1 的许可用户可以从 MCAS 中的发现功能中受益。</span><span class="sxs-lookup"><span data-stu-id="f4629-185">Licensed users of Azure AD P1 can benefit from the Discovery capabilities in MCAS.</span></span>

<span data-ttu-id="f4629-186">若要从 MCAS 中的[条件访问应用程序控制](https://docs.microsoft.com/cloud-app-security/proxy-intro-aad)功能中受益, 还必须为用户授予 Azure Active Directory P1 (包括在企业移动性 + 安全 E3、企业移动性 + 安全 E5、Microsoft 365 E3、microsoft 365E5 和 Microsoft 365 E5 Security。</span><span class="sxs-lookup"><span data-stu-id="f4629-186">To benefit from the [Conditional Access App Control](https://docs.microsoft.com/cloud-app-security/proxy-intro-aad) capabilities in MCAS, users must also be licensed for Azure Active Directory P1, which is included in Enterprise Mobility + Security E3, Enterprise Mobility + Security E5, Microsoft 365 E3, Microsoft 365 E5, and Microsoft 365 E5 Security.</span></span>

<span data-ttu-id="f4629-187">若要从[自动标记](https://docs.microsoft.com/cloud-app-security/data-protection-policies)中受益, 用户必须获得 Azure 信息保护 P2 (包含在企业移动性 + 安全 E5、Microsoft 365 E5 和 Microsoft 365 e5) 的许可。</span><span class="sxs-lookup"><span data-stu-id="f4629-187">To benefit from [automatic labeling](https://docs.microsoft.com/cloud-app-security/data-protection-policies), users must be licensed for Azure Information Protection P2, which is included in Enterprise Mobility + Security E5, Microsoft 365 E5, and Microsoft 365 E5 Compliance.</span></span>

<span data-ttu-id="f4629-188">有关详细信息, 请参阅[Microsoft Cloud App Security 授权数据表](http://www.aka.ms/mcaslicensing)。</span><span class="sxs-lookup"><span data-stu-id="f4629-188">For more information, see the [Microsoft Cloud App Security Licensing Datasheet](http://www.aka.ms/mcaslicensing).</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="f4629-189">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="f4629-189">How do users benefit from the service?</span></span>

<span data-ttu-id="f4629-190">MCAS 发现和评估阴影, 提供跨第一方云应用程序的威胁保护, 并在第一方和第三方云应用中保护信息。</span><span class="sxs-lookup"><span data-stu-id="f4629-190">MCAS discovers and assesses Shadow IT, provides threat protection across first- and third-party cloud apps, and protects information across first- and third-party cloud apps.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="f4629-191">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="f4629-191">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="f4629-192">默认情况下, MCAS 功能在租户级别为租户中的所有用户启用。</span><span class="sxs-lookup"><span data-stu-id="f4629-192">By default, MCAS features are enabled at the tenant level for all users within the tenant.</span></span>

<span data-ttu-id="f4629-193">有关为许可用户配置 Microsoft 云应用安全策略的信息, 请参阅[Microsoft Cloud App security 概述](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)。</span><span class="sxs-lookup"><span data-stu-id="f4629-193">For information on configuring Microsoft Cloud App Security policies for licensed users, see [Microsoft Cloud App Security overview](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security).</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="f4629-194">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="f4629-194">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="f4629-195">管理员可以使用服务中提供的作用域部署功能将 MCAS 部署限定为许可用户。</span><span class="sxs-lookup"><span data-stu-id="f4629-195">Admins can scope MCAS deployments to licensed users by using the scoped deployment capabilities available in the service.</span></span> <span data-ttu-id="f4629-196">有关详细信息, 请参阅[作用域部署](https://docs.microsoft.com/cloud-app-security/scoped-deployment)。</span><span class="sxs-lookup"><span data-stu-id="f4629-196">For more information, see [Scoped deployment](https://docs.microsoft.com/cloud-app-security/scoped-deployment).</span></span>

## <a name="office-365-advanced-data-governance"></a><span data-ttu-id="f4629-197">Office 365 高级数据管理</span><span class="sxs-lookup"><span data-stu-id="f4629-197">Office 365 Advanced Data Governance</span></span>

<span data-ttu-id="f4629-198">高级数据治理 (ADG) 可帮助组织通过启用保留和删除的策略满足信息治理要求。</span><span class="sxs-lookup"><span data-stu-id="f4629-198">Advanced Data Governance (ADG) helps organizations meet information governance requirements with policies to enable retention and deletion.</span></span> <span data-ttu-id="f4629-199">ADG 允许组织根据敏感信息类型自动标记内容, 并对该内容应用调控策略。</span><span class="sxs-lookup"><span data-stu-id="f4629-199">ADG lets organizations auto-label content based on sensitive information type and apply governance policies to that content.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="f4629-200">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="f4629-200">Which users benefit from the service?</span></span>

<span data-ttu-id="f4629-201">Office 365 E5 的许可用户、Microsoft 365 E5、Microsoft 365 E5 和 Office 365 高级合规性可以从 ADG 获益。</span><span class="sxs-lookup"><span data-stu-id="f4629-201">Licensed users of Office 365 E5, Microsoft 365 E5, Microsoft 365 E5 Compliance, and Office 365 Advanced Compliance can benefit from ADG.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="f4629-202">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="f4629-202">How do users benefit from the service?</span></span>

<span data-ttu-id="f4629-203">ADG 允许用户将标签应用于特定数据, 以对特定的策略进行对齐、自动将内容标记为记录, 以及管理从声明到处置的完整记录过程。</span><span class="sxs-lookup"><span data-stu-id="f4629-203">ADG lets users apply labels to specific data to uphold specific policies, automatically label content as a record, and manage the full records process from declaration to disposal.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="f4629-204">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="f4629-204">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="f4629-205">默认情况下, ADG 功能在租户级别为租户中的所有用户启用。</span><span class="sxs-lookup"><span data-stu-id="f4629-205">By default, ADG features are enabled at the tenant level for all users within the tenant.</span></span> <span data-ttu-id="f4629-206">有关配置 ADG 以将自动标记和策略应用于许可用户的信息, 请参阅[保留标签概述](https://docs.microsoft.com/office365/securitycompliance/labels)。</span><span class="sxs-lookup"><span data-stu-id="f4629-206">For information on configuring ADG to apply auto-labeling and policies for licensed users, see [Overview of retention labels](https://docs.microsoft.com/office365/securitycompliance/labels).</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="f4629-207">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="f4629-207">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="f4629-208">可以通过自动分类将 ADG 保留策略应用于特定位置 (工作组网站、组网站等) 的许可用户。</span><span class="sxs-lookup"><span data-stu-id="f4629-208">ADG retention policies can be applied to licensed users in specific locations (team sites, group sites, etc.) through automatic classification.</span></span> <span data-ttu-id="f4629-209">有关应用 ADG 保留策略的说明, 请参阅[将保留策略应用于整个组织或特定位置](https://docs.microsoft.com/office365/securitycompliance/retention-policies#applying-a-retention-policy-to-an-entire-organization-or-specific-locations)。</span><span class="sxs-lookup"><span data-stu-id="f4629-209">For instructions on applying ADG retention policies, see [Applying a retention policy to an entire organization or specific locations](https://docs.microsoft.com/office365/securitycompliance/retention-policies#applying-a-retention-policy-to-an-entire-organization-or-specific-locations).</span></span>

## <a name="office-365-advanced-ediscovery"></a><span data-ttu-id="f4629-210">Office 365 高级电子数据展示</span><span class="sxs-lookup"><span data-stu-id="f4629-210">Office 365 Advanced eDiscovery</span></span>

<span data-ttu-id="f4629-211">Office 365 高级电子数据展示为 IT 和公司内部的法律部门提供调查和电子数据展示解决方案, 以确定、收集、保留、减少和查看与调查或诉讼相关的内容, 然后再导出Office 365 系统。</span><span class="sxs-lookup"><span data-stu-id="f4629-211">Office 365 Advanced eDiscovery provides investigation and eDiscovery solutions for IT and legal departments within corporations to identify, collect, preserve, reduce, and review content related to an investigation or litigation prior to export out of the Office 365 system.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="f4629-212">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="f4629-212">Which users benefit from the service?</span></span>

<span data-ttu-id="f4629-213">Office 365 E5 的许可用户、Microsoft 365 E5、Microsoft 365 E5 和 Office 365 高级合规性可以从高级电子数据展示中受益。</span><span class="sxs-lookup"><span data-stu-id="f4629-213">Licensed users of Office 365 E5, Microsoft 365 E5, Microsoft 365 E5 Compliance, and Office 365 Advanced Compliance can benefit from Advanced eDiscovery.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="f4629-214">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="f4629-214">How do users benefit from the service?</span></span>

<span data-ttu-id="f4629-215">当用户选择作为数据管理员 (具有文档或电子文件的管理控制) 时, 用户将从高级电子数据展示中受益。</span><span class="sxs-lookup"><span data-stu-id="f4629-215">A user benefits from Advanced eDiscovery when the user is selected as a data custodian (a person having administrative control of a document or electronic file) for a case.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="f4629-216">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="f4629-216">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="f4629-217">默认情况下, 当管理员在安全 & 合规中心中分配电子数据展示权限时, 将在租户级别为租户中的所有用户启用高级电子数据展示功能。</span><span class="sxs-lookup"><span data-stu-id="f4629-217">By default, Advanced eDiscovery features are enabled at the tenant level for all users within the tenant when admins assign eDiscovery permissions in the Security & Compliance Center.</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="f4629-218">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="f4629-218">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="f4629-219">通过使用高级电子数据展示中的内置保管人管理工具, 电子数据展示管理员可以选择特定用户作为事例的数据保管人, 如[将保管人添加到高级电子数据展示事例](https://docs.microsoft.com/office365/securitycompliance/compliance20/add-custodians-to-case)中所述。</span><span class="sxs-lookup"><span data-stu-id="f4629-219">eDiscovery administrators can select specific users as data custodians for a case by using the built-in custodian management tool in Advanced eDiscovery as described in [Add custodians to an Advanced eDiscovery case](https://docs.microsoft.com/office365/securitycompliance/compliance20/add-custodians-to-case).</span></span>

## <a name="office-365-customer-key"></a><span data-ttu-id="f4629-220">Office 365 客户密钥</span><span class="sxs-lookup"><span data-stu-id="f4629-220">Office 365 Customer Key</span></span>

<span data-ttu-id="f4629-221">使用 "客户密钥", 可以控制组织的加密密钥, 并配置 Office 365 以使用它们在 Microsoft 数据中心中对静态数据进行加密。</span><span class="sxs-lookup"><span data-stu-id="f4629-221">With Customer Key, you control your organization's encryption keys and configure Office 365 to use them to encrypt your data at rest in Microsoft's data centers.</span></span> <span data-ttu-id="f4629-222">换句话说, 客户密钥允许您使用自己的密钥添加属于您的加密层。</span><span class="sxs-lookup"><span data-stu-id="f4629-222">In other words, Customer Key allows you to add a layer of encryption that belongs to you, using your own keys.</span></span> <span data-ttu-id="f4629-223">静态数据包含来自 Exchange Online 和 Skype for business 的数据, 这些数据存储在 SharePoint Online 和 OneDrive for business 中的邮箱和文件中。</span><span class="sxs-lookup"><span data-stu-id="f4629-223">Data at rest includes data from Exchange Online and Skype for Business that is stored in mailboxes and files within SharePoint Online and OneDrive for Business.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="f4629-224">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="f4629-224">Which users benefit from the service?</span></span>

<span data-ttu-id="f4629-225">Office 365 E5 的许可用户、Microsoft 365 E5、Microsoft 365 E5 和 Office 365 高级合规性可以从客户密钥获益。</span><span class="sxs-lookup"><span data-stu-id="f4629-225">Licensed users of Office 365 E5, Microsoft 365 E5, Microsoft 365 E5 Compliance, and Office 365 Advanced Compliance can benefit from Customer Key.</span></span> <span data-ttu-id="f4629-226">若要获得客户密钥的全部好处, 您还必须具有 Azure Key Vault 的订阅。</span><span class="sxs-lookup"><span data-stu-id="f4629-226">To get the full benefit of Customer Key, you must also have a subscription for Azure Key Vault.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="f4629-227">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="f4629-227">How do users benefit from the service?</span></span>

<span data-ttu-id="f4629-228">用户可通过在应用程序层使用提供、控制和管理自己的组织的加密密钥在应用程序层对其数据进行加密, 从而获得客户密钥的好处。</span><span class="sxs-lookup"><span data-stu-id="f4629-228">Users benefit from Customer Key by having their data at rest encrypted at the application layer using encryption keys that are provided, controlled, and managed by their own organization.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="f4629-229">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="f4629-229">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="f4629-230">可以为存储在 Exchange Online 和 Skype for business 邮箱以及 SharePoint Online 和 OneDrive for business 文件中的所有数据启用 Office 365 客户密钥加密密钥。</span><span class="sxs-lookup"><span data-stu-id="f4629-230">Office 365 Customer Key encryption keys can be enabled for all data stored in Exchange Online and Skype for Business mailboxes, and SharePoint Online and OneDrive for Business files.</span></span> <span data-ttu-id="f4629-231">有关配置 Office 365 客户密钥以加密静态数据的信息, 请参阅[使用客户密钥控制 office 365 中的数据](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key)。</span><span class="sxs-lookup"><span data-stu-id="f4629-231">For information on configuring Office 365 Customer Key to encrypt your data at rest, see [Controlling Your Data in Office 365 Using Customer Key](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key).</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="f4629-232">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="f4629-232">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="f4629-233">若要将加密密钥分配给 Office 365 和/或 Microsoft 365 租户中的数据以供许可用户使用, 请按照客户密钥加密密钥部署策略操作:</span><span class="sxs-lookup"><span data-stu-id="f4629-233">To assign encryption keys to data within an Office 365 and/or Microsoft 365 tenant for licensed users, follow the Customer Key encryption keys deployment policies:</span></span>

  - <span data-ttu-id="f4629-234">对于 SharePoint Online, 可以使用以下所述的客户密钥对一个或多个网站上的文件进行加密:[设置 SharePoint Online 和 OneDrive for business 的客户密钥](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key#office-365-setting-up-customer-key-for-sharepoint-online-and-onedrive-for-business)。</span><span class="sxs-lookup"><span data-stu-id="f4629-234">For SharePoint Online, files on one or more sites can be encrypted using Customer Key as described here: [Setting up Customer Key for SharePoint Online and OneDrive for Business](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key#office-365-setting-up-customer-key-for-sharepoint-online-and-onedrive-for-business).</span></span>

  - <span data-ttu-id="f4629-235">对于 Exchange Online 和 Skype for business Online, 可以使用以下所述的客户密钥对邮箱进行加密:[设置 Exchange Online 和 Skype for business 的客户密钥](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key#office-365-setting-up-customer-key-for-exchange-online-and-skype-for-business)</span><span class="sxs-lookup"><span data-stu-id="f4629-235">For Exchange Online and Skype for Business Online, mailboxes can be encrypted using Customer Key as described here: [Setting up Customer Key for Exchange Online and Skype for Business](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key#office-365-setting-up-customer-key-for-exchange-online-and-skype-for-business)</span></span>

## <a name="office-365-customer-lockbox"></a><span data-ttu-id="f4629-236">Office 365 客户密码箱</span><span class="sxs-lookup"><span data-stu-id="f4629-236">Office 365 Customer Lockbox</span></span>

<span data-ttu-id="f4629-237">客户密码箱通过让客户能够为服务操作提供显式访问授权, 从而提供了一个额外的控制层。</span><span class="sxs-lookup"><span data-stu-id="f4629-237">Customer Lockbox provides an additional layer of control by offering customers the ability to give explicit access authorization for service operations.</span></span> <span data-ttu-id="f4629-238">通过演示如何将过程用于显式数据访问授权, 客户密码箱还可以帮助组织满足特定合规性义务, 如 HIPAA 和 FEDRAMP。</span><span class="sxs-lookup"><span data-stu-id="f4629-238">By demonstrating that procedures are in place for explicit data access authorization, Customer Lockbox may also help organizations meet certain compliance obligations such as HIPAA and FEDRAMP.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="f4629-239">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="f4629-239">Which users benefit from the service?</span></span>

<span data-ttu-id="f4629-240">Office 365 E5、Microsoft 365 E5、Microsoft 365 E5 合规性和 Office 365 高级合规性的许可用户可从客户密码箱获益。</span><span class="sxs-lookup"><span data-stu-id="f4629-240">Licensed users of Office 365 E5, Microsoft 365 E5, Microsoft 365 E5 Compliance, and the Office 365 Advanced Compliance can benefit from Customer Lockbox.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="f4629-241">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="f4629-241">How do users benefit from the service?</span></span>

<span data-ttu-id="f4629-242">用户可以从客户密码箱获益, 确保 Microsoft 无需在未经客户明确批准的情况下即可在 Microsoft 不能访问其内容的情况下执行服务操作。</span><span class="sxs-lookup"><span data-stu-id="f4629-242">Users benefit from Customer Lockbox ensuring that no one at Microsoft can access their content to perform a service operation without the customer’s explicit approval.</span></span> <span data-ttu-id="f4629-243">客户密码箱将客户引入审批工作流, 以获取访问其内容的请求。</span><span class="sxs-lookup"><span data-stu-id="f4629-243">Customer Lockbox brings the customer into the approval workflow for requests to access their content.</span></span> <span data-ttu-id="f4629-244">有时, Microsoft 工程师会在支持流程中参与诊断和修复客户报告的问题。</span><span class="sxs-lookup"><span data-stu-id="f4629-244">Occasionally, Microsoft engineers are involved during the support process to troubleshoot and fix customer-reported issues.</span></span> <span data-ttu-id="f4629-245">在大多数情况下, 通过 Microsoft 为其服务提供的大量遥测和调试工具解决了问题。</span><span class="sxs-lookup"><span data-stu-id="f4629-245">In most cases, issues are fixed through extensive telemetry and debugging tools that Microsoft has in place for its services.</span></span> <span data-ttu-id="f4629-246">但是, 在某些情况下, 可能需要 Microsoft 工程师访问客户内容以确定根本原因并解决问题。</span><span class="sxs-lookup"><span data-stu-id="f4629-246">However, there may be cases that require a Microsoft engineer to access customer content to determine the root cause and fix the issue.</span></span> <span data-ttu-id="f4629-247">客户密码箱要求工程师在审批工作流的最后步骤中请求从客户进行访问。</span><span class="sxs-lookup"><span data-stu-id="f4629-247">Customer Lockbox requires the engineer to request access from the customer as a final step in the approval workflow.</span></span> <span data-ttu-id="f4629-248">这为组织提供了批准或拒绝这些请求的选项, 这些请求使他们可以直接控制 Microsoft 工程师是否可以访问组织的最终用户数据。</span><span class="sxs-lookup"><span data-stu-id="f4629-248">This gives organizations the option to approve or deny these requests, which gives them direct control over whether a Microsoft engineer can access the organizations’ end-user data.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="f4629-249">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="f4629-249">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="f4629-250">管理员可以在 Microsoft 365 管理中心启用客户密码箱控件。</span><span class="sxs-lookup"><span data-stu-id="f4629-250">Admins can turn on Customer Lockbox controls in the Microsoft 365 admin center.</span></span> <span data-ttu-id="f4629-251">有关详细信息, 请参阅[Office 365 中的客户密码箱](https://docs.microsoft.com/Office365/Admin/manage/customer-lockbox-requests)。</span><span class="sxs-lookup"><span data-stu-id="f4629-251">For more information, see [Customer Lockbox in Office 365](https://docs.microsoft.com/Office365/Admin/manage/customer-lockbox-requests).</span></span> <span data-ttu-id="f4629-252">当客户密码箱打开时, 在访问其任何内容之前, 需要 Microsoft 获取组织的批准。</span><span class="sxs-lookup"><span data-stu-id="f4629-252">When Customer Lockbox is turned on, Microsoft is required to obtain an organization’s approval prior to accessing any of their content.</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="f4629-253">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="f4629-253">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="f4629-254">Microsoft 不会承诺向未获得许可的用户提供客户密码箱访问控制审批请求。</span><span class="sxs-lookup"><span data-stu-id="f4629-254">Microsoft does not commit to providing Customer Lockbox access-control approval requests for users who are not licensed.</span></span> <span data-ttu-id="f4629-255">随着时间的推移, 许可证检查或目标工具将添加到客户密码箱中, 以确保客户密码箱可分配给许可用户。</span><span class="sxs-lookup"><span data-stu-id="f4629-255">Over time, license checks or targeted tooling will be added to Customer Lockbox to ensure Customer Lockbox is assignable to licensed users.</span></span>

## <a name="privileged-access-management-in-office-365"></a><span data-ttu-id="f4629-256">Office 365 中的特权访问管理</span><span class="sxs-lookup"><span data-stu-id="f4629-256">Privileged access management in Office 365</span></span>

<span data-ttu-id="f4629-257">特权访问管理 (PAM) 提供对 Office 365 中的特权管理任务的精细访问控制。</span><span class="sxs-lookup"><span data-stu-id="f4629-257">Privileged access management (PAM) provides granular access control over privileged admin tasks in Office 365.</span></span> <span data-ttu-id="f4629-258">启用 PAM 后, 用户将需要通过高度范围和时间限制的审批工作流请求实时访问, 以完成提升和特权的任务。</span><span class="sxs-lookup"><span data-stu-id="f4629-258">After enabling PAM, users will need to request just-in-time access through an approval workflow that is highly scoped and time-bound in order to complete elevated and privileged tasks.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="f4629-259">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="f4629-259">Which users benefit from the service?</span></span>

<span data-ttu-id="f4629-260">Office 365 E5 的许可用户、Microsoft 365 E5、Microsoft 365 E5 和 Office 365 高级合规性可以从 PAM 中受益。</span><span class="sxs-lookup"><span data-stu-id="f4629-260">Licensed users of Office 365 E5, Microsoft 365 E5, Microsoft 365 E5 Compliance, and Office 365 Advanced Compliance can benefit from PAM.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="f4629-261">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="f4629-261">How do users benefit from the service?</span></span>

<span data-ttu-id="f4629-262">启用 PAM 可让组织以零作为自主权限运行。</span><span class="sxs-lookup"><span data-stu-id="f4629-262">Enabling PAM lets organizations operate with zero standing privileges.</span></span> <span data-ttu-id="f4629-263">用户从增加的防御层中受益, 以防止因提供对其数据的 unfettered 访问而产生的漏洞。</span><span class="sxs-lookup"><span data-stu-id="f4629-263">Users benefit from the added layer of defense against vulnerabilities arising from standing administrative access that provides unfettered access to their data.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="f4629-264">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="f4629-264">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="f4629-265">默认情况下, 在租户级别为租户中的所有用户启用 PAM 功能。</span><span class="sxs-lookup"><span data-stu-id="f4629-265">By default, PAM features are enabled at the tenant level for all users within the tenant.</span></span> <span data-ttu-id="f4629-266">有关配置 PAM 策略的信息, 请参阅[在 Office 365 中配置特权访问管理](https://docs.microsoft.com/office365/securitycompliance/privileged-access-management-configuration)。</span><span class="sxs-lookup"><span data-stu-id="f4629-266">For information on configuring PAM policies, see [Configuring privileged access management in Office 365](https://docs.microsoft.com/office365/securitycompliance/privileged-access-management-configuration).</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="f4629-267">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="f4629-267">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="f4629-268">客户可以通过审核人组和访问策略 (可应用于许可用户) 在每用户的基础上管理 PAM。</span><span class="sxs-lookup"><span data-stu-id="f4629-268">Customers can manage PAM on a per-user basis through approver group and access policies, which can be applied to licensed users.</span></span> <span data-ttu-id="f4629-269">有关详细信息, 请参阅[Office 365 中的特权访问管理](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751)。</span><span class="sxs-lookup"><span data-stu-id="f4629-269">For more information, see [Privileged Access Management in Office 365](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751).</span></span>

## <a name="data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a><span data-ttu-id="f4629-270">Exchange Online、SharePoint Online 和 OneDrive for business 的数据丢失防护</span><span class="sxs-lookup"><span data-stu-id="f4629-270">Data Loss Prevention for Exchange Online, SharePoint Online, and OneDrive for Business</span></span>

<span data-ttu-id="f4629-271">对于 Exchange Online、SharePoint Online 和 OneDrive for Business 的数据丢失防护 (DLP), 组织可以通过电子邮件和文件 (包括存储在 Microsoft 团队文件中的文件) 识别、监视和自动保护敏感信息。存储库)。</span><span class="sxs-lookup"><span data-stu-id="f4629-271">With Data Loss Prevention (DLP) for Exchange Online, SharePoint Online, and OneDrive for Business, organizations can identify, monitor, and automatically protect sensitive information across emails and files (including files stored in Microsoft Teams file repositories).</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="f4629-272">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="f4629-272">Which users benefit from the service?</span></span>

<span data-ttu-id="f4629-273">Office 365 E3、Microsoft 365 E3 和 Office 365 数据丢失防护的许可用户可受益于 DLP for Exchange Online、SharePoint Online 和 OneDrive for Business。</span><span class="sxs-lookup"><span data-stu-id="f4629-273">Licensed users of Office 365 E3, Microsoft 365 E3, and Office 365 Data Loss Prevention can benefit from DLP for Exchange Online, SharePoint Online, and OneDrive for Business.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="f4629-274">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="f4629-274">How do users benefit from the service?</span></span>

<span data-ttu-id="f4629-275">当检查其电子邮件和文件中的敏感信息 (如组织的 DLP 策略中配置) 时, 用户将受益于 DLP for Exchange Online、SharePoint Online 和 OneDrive for business。</span><span class="sxs-lookup"><span data-stu-id="f4629-275">Users benefit from DLP for Exchange Online, SharePoint Online, and OneDrive for Business when their emails and files are being inspected for sensitive information, as configured in the organization’s DLP policy.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="f4629-276">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="f4629-276">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="f4629-277">默认情况下, Exchange Online 电子邮件、SharePoint 网站和 OneDrive 帐户为租户中的所有用户启用这些 DLP 功能的*位置 (工作负荷)* 。</span><span class="sxs-lookup"><span data-stu-id="f4629-277">By default, Exchange Online emails, SharePoint sites, and OneDrive accounts are *enabled locations (workloads)* for these DLP features for all users within the tenant.</span></span> <span data-ttu-id="f4629-278">有关使用 DLP 策略的详细信息, 请参阅[数据丢失防护概述](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)。</span><span class="sxs-lookup"><span data-stu-id="f4629-278">For more information about using DLP policies, see [Overview of data loss prevention](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies).</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="f4629-279">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="f4629-279">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="f4629-280">管理员可以在 "Office 365 安全 & 合规中心" 中的 "**数据丢失防护** > **位置**" 下自定义位置 (工作负荷)、包含的用户和排除的用户。</span><span class="sxs-lookup"><span data-stu-id="f4629-280">Admins can customize locations (workloads), included users, and excluded users in the Office 365 Security & Compliance Center, under **Data loss prevention** > **Locations**.</span></span>

## <a name="data-loss-prevention-for-teams-chat-and-channel-messages"></a><span data-ttu-id="f4629-281">工作组聊天和频道消息的数据丢失防护</span><span class="sxs-lookup"><span data-stu-id="f4629-281">Data Loss Prevention for Teams chat and channel messages</span></span>

<span data-ttu-id="f4629-282">使用数据丢失防护 (DLP) 获取团队聊天和频道消息时, 组织可以阻止包含敏感信息的聊天和频道消息, 如财务信息、个人标识信息、与运行状况相关的信息, 或其他机密信息。</span><span class="sxs-lookup"><span data-stu-id="f4629-282">With Data Loss Prevention (DLP) for Teams chat and channel messages, organizations can block chats and channel messages that contain sensitive information, such as financial information, personally identifying information, health-related information, or other confidential information.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="f4629-283">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="f4629-283">Which users benefit from the service?</span></span>

<span data-ttu-id="f4629-284">Office 365 E5 的许可用户、Microsoft 365 E5、Microsoft 365 E5 和 Office 365 高级合规性可受益于 DLP for 团队聊天和频道消息。</span><span class="sxs-lookup"><span data-stu-id="f4629-284">Licensed users of Office 365 E5, Microsoft 365 E5, Microsoft 365 E5 Compliance, and Office 365 Advanced Compliance can benefit from DLP for Teams chat and channel messages.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="f4629-285">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="f4629-285">How do users benefit from the service?</span></span>

<span data-ttu-id="f4629-286">通过在组织的 DLP 策略中配置的敏感信息检查其传出聊天和频道消息中的敏感信息, 发件人会获得好处。</span><span class="sxs-lookup"><span data-stu-id="f4629-286">Senders benefit by having sensitive information in their outgoing chat and channel messages inspected for sensitive information, as configured in the organization’s DLP policy.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="f4629-287">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="f4629-287">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="f4629-288">默认情况下, 团队聊天和频道消息是租户中所有用户的这些 DLP 功能的*已启用位置 (工作负荷)* 。</span><span class="sxs-lookup"><span data-stu-id="f4629-288">By default, Teams chat and channel messages are an *enabled Location (workload)* for these DLP features for all users within the tenant.</span></span> <span data-ttu-id="f4629-289">有关使用 DLP 策略的详细信息, 请参阅[数据丢失防护概述](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)。</span><span class="sxs-lookup"><span data-stu-id="f4629-289">For more information about using DLP policies, see [Overview of data loss prevention](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies).</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="f4629-290">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="f4629-290">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="f4629-291">管理员可以在 "Office 365 安全 & 合规中心" 中的 "**数据丢失防护** > **位置**" 下自定义位置 (工作负荷)、包含的用户和排除的用户。</span><span class="sxs-lookup"><span data-stu-id="f4629-291">Admins can customize locations (workloads), included users, and excluded users in the Office 365 Security & Compliance Center, under **Data loss prevention** > **Locations**.</span></span>

## <a name="information-barriers"></a><span data-ttu-id="f4629-292">信息障碍</span><span class="sxs-lookup"><span data-stu-id="f4629-292">Information barriers</span></span>

<span data-ttu-id="f4629-293">信息障碍是管理员可以配置的用于阻止个人或组相互通信的策略。</span><span class="sxs-lookup"><span data-stu-id="f4629-293">Information barriers are policies that an admin can configure to prevent individuals or groups from communicating with each other.</span></span> <span data-ttu-id="f4629-294">例如, 如果一个部门处理的信息不应与其他部门共享, 或者必须阻止某个组与外部联系人通信, 则这将非常有用。</span><span class="sxs-lookup"><span data-stu-id="f4629-294">This is useful if, for example, one department is handling information that shouldn't be shared with other departments, or a group needs to be prevented from communicating with outside contacts.</span></span> <span data-ttu-id="f4629-295">信息屏障策略也阻止了查找和发现。</span><span class="sxs-lookup"><span data-stu-id="f4629-295">Information barrier policies also prevent lookups and discovery.</span></span> <span data-ttu-id="f4629-296">这意味着, 如果您尝试与不应与之通信的人员进行通信, 则不会在人员选取器中找到该用户。</span><span class="sxs-lookup"><span data-stu-id="f4629-296">This means that if you attempt to communicate with someone you should not be communicating with, you won't find that user in the people picker.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="f4629-297">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="f4629-297">Which users benefit from the service?</span></span>

<span data-ttu-id="f4629-298">Office 365 E5 的许可用户、Microsoft 365 E5、Microsoft 365 E5 和 Office 365 高级合规性可以从信息障碍中受益。</span><span class="sxs-lookup"><span data-stu-id="f4629-298">Licensed users of Office 365 E5, Microsoft 365 E5, Microsoft 365 E5 Compliance, and Office 365 Advanced Compliance can benefit from information barriers.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="f4629-299">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="f4629-299">How do users benefit from the service?</span></span>

<span data-ttu-id="f4629-300">当限制用户与其他人通信时, 他们将受益于信息障碍的高级合规性功能。</span><span class="sxs-lookup"><span data-stu-id="f4629-300">Users benefit from the advanced compliance capabilities of information barriers when they're restricted from communicating with others.</span></span> <span data-ttu-id="f4629-301">例如：</span><span class="sxs-lookup"><span data-stu-id="f4629-301">For example:</span></span>

| <span data-ttu-id="f4629-302">应用场景</span><span class="sxs-lookup"><span data-stu-id="f4629-302">Scenario</span></span>                                                                                                                                                                                                              | <span data-ttu-id="f4629-303">需要许可证的是谁？</span><span class="sxs-lookup"><span data-stu-id="f4629-303">Who requires a license?</span></span> |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| <span data-ttu-id="f4629-304">两组 (组1和组 2) 无法相互通信 (即, 限制组1用户与组2用户通信, 而组2用户限制与组1用户通信。</span><span class="sxs-lookup"><span data-stu-id="f4629-304">Two groups (Group 1 and Group 2) cannot communicate with each other (that is, Group 1 users are restricted from communicating with Group 2 users, and Group 2 users are restricted from communicating with Group 1 users.</span></span> | <span data-ttu-id="f4629-305">组1和组2中的用户</span><span class="sxs-lookup"><span data-stu-id="f4629-305">Users in both Group 1 and Group 2</span></span>                    |
| <span data-ttu-id="f4629-306">限制组1中的用户与公司的其余用户通信。</span><span class="sxs-lookup"><span data-stu-id="f4629-306">Users in Group 1 are restricted from communicating with the rest of the company.</span></span>                                                                                                                                       | <span data-ttu-id="f4629-307">仅限组1中的用户</span><span class="sxs-lookup"><span data-stu-id="f4629-307">Users in Group 1 only</span></span>                                |
| <span data-ttu-id="f4629-308">公司的其余部分受到限制, 无法与组1通信。</span><span class="sxs-lookup"><span data-stu-id="f4629-308">The rest of the company is restricted from communicating with Group 1.</span></span>                                                                                                                                                 | <span data-ttu-id="f4629-309">除组1中的用户之外的所有用户</span><span class="sxs-lookup"><span data-stu-id="f4629-309">All users except those in Group 1</span></span>                    |
| <span data-ttu-id="f4629-310">限制组1用户与组2用户通信, 但组2用户可以与组1用户进行通信。</span><span class="sxs-lookup"><span data-stu-id="f4629-310">Group 1 users are restricted from communicating with Group 2 users, but Group 2 users can communicate with Group 1 users.</span></span>                                                                                              | <span data-ttu-id="f4629-311">仅限组1中的用户</span><span class="sxs-lookup"><span data-stu-id="f4629-311">Users in Group 1 only</span></span>                                |

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="f4629-312">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="f4629-312">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="f4629-313">管理员在安全 & 合规中心中使用 PowerShell cmdlet 创建和管理信息障碍策略。</span><span class="sxs-lookup"><span data-stu-id="f4629-313">Admins create and manage information barrier policies by using PowerShell cmdlets in the Security & Compliance Center.</span></span> <span data-ttu-id="f4629-314">必须为管理员分配 Microsoft 365 企业全局管理员、Office 365 全局管理员或合规性管理员角色, 以创建信息障碍策略。</span><span class="sxs-lookup"><span data-stu-id="f4629-314">Admins must be assigned the Microsoft 365 Enterprise Global Administrator, Office 365 Global Administrator, or Compliance Administrator role to create an information barrier policy.</span></span> <span data-ttu-id="f4629-315">默认情况下, 这些策略适用于租户中的所有用户。</span><span class="sxs-lookup"><span data-stu-id="f4629-315">By default, these policies apply to all users in the tenant.</span></span> <span data-ttu-id="f4629-316">有关信息障碍的详细信息, 请参阅[Microsoft 团队中的信息障碍](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)。</span><span class="sxs-lookup"><span data-stu-id="f4629-316">For more information about information barriers, see [Information barriers in Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams).</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="f4629-317">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="f4629-317">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="f4629-318">管理员可以在 Office 365 安全 & 合规中心中自定义位置 (工作负荷)、包含的用户以及排除的用户。</span><span class="sxs-lookup"><span data-stu-id="f4629-318">Admins can customize locations (workloads), included users, and excluded users in the Office 365 Security & Compliance Center.</span></span> <span data-ttu-id="f4629-319">例如, 如果所有用户均为 Office 365 E3 许可, 并且没有许可 Office 365 高级合规性/E5, 则无需为组织创建任何信息障碍策略。</span><span class="sxs-lookup"><span data-stu-id="f4629-319">For example, if all users are licensed for Office 365 E3, and none are licensed for Office 365 Advanced Compliance/E5, they wouldn't need to create any information barrier policies for the organization.</span></span> <span data-ttu-id="f4629-320">有关详细信息, 请参阅[Microsoft 团队中的信息障碍](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)。</span><span class="sxs-lookup"><span data-stu-id="f4629-320">For more information, see [Information barriers in Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams).</span></span>

## <a name="office-365-advanced-message-encryption"></a><span data-ttu-id="f4629-321">Office 365 高级邮件加密</span><span class="sxs-lookup"><span data-stu-id="f4629-321">Office 365 Advanced Message Encryption</span></span>

<span data-ttu-id="f4629-322">高级邮件加密帮助客户满足法规遵从性义务, 这些要求对外部收件人和对加密电子邮件的访问权限要求更灵活的控制。</span><span class="sxs-lookup"><span data-stu-id="f4629-322">Advanced Message Encryption helps customers meet compliance obligations that require more flexible controls over external recipients and their access to encrypted emails.</span></span> <span data-ttu-id="f4629-323">通过高级邮件加密, 管理员可以通过使用可检测敏感信息类型 (例如, 个人标识信息或财务或运行状况 Id) 的自动策略来控制在组织外共享的敏感电子邮件, 或者它们可以通过应用自定义电子邮件模板, 并通过安全 web 门户终止对加密电子邮件的访问, 从而使用关键字增强保护。</span><span class="sxs-lookup"><span data-stu-id="f4629-323">With Advanced Message Encryption, admins can control sensitive emails shared outside the organization by using automatic policies that can detect sensitive information types (for example, personally identifying information, or financial or health IDs), or they can use keywords to enhance protection by applying custom email templates and expiring access to encrypted emails through a secure web portal.</span></span> <span data-ttu-id="f4629-324">此外, 管理员可以随时撤销访问权限, 从而进一步控制通过安全 web 门户外部访问的加密电子邮件。</span><span class="sxs-lookup"><span data-stu-id="f4629-324">Additionally, admins can further control encrypted emails accessed externally through a secure web portal by revoking access at any time.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="f4629-325">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="f4629-325">Which users benefit from the service?</span></span>

<span data-ttu-id="f4629-326">Office 365 E5 的许可用户、Microsoft 365 E5、Microsoft 365 E5 和 Office 365 高级合规性可以从高级邮件加密中受益。</span><span class="sxs-lookup"><span data-stu-id="f4629-326">Licensed users of Office 365 E5, Microsoft 365 E5, Microsoft 365 E5 Compliance, and Office 365 Advanced Compliance can benefit from Advanced Message Encryption.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="f4629-327">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="f4629-327">How do users benefit from the service?</span></span>

<span data-ttu-id="f4629-328">邮件发件人可受益于对高级邮件加密提供的敏感电子邮件所添加的控制。</span><span class="sxs-lookup"><span data-stu-id="f4629-328">Message senders benefit from the added control over sensitive emails provided by Advanced Message Encryption.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="f4629-329">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="f4629-329">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="f4629-330">管理员在 "邮件流规则" 下的 Exchange 管理中心中创建和管理高级邮件加密策略。</span><span class="sxs-lookup"><span data-stu-id="f4629-330">Admins create and manage Advanced Message Encryption policies in the Exchange admin center under mail flow rules.</span></span> <span data-ttu-id="f4629-331">默认情况下, 这些规则适用于租户上的所有用户。</span><span class="sxs-lookup"><span data-stu-id="f4629-331">By default, these rules apply to all users on the tenant.</span></span> <span data-ttu-id="f4629-332">有关设置新的邮件加密功能的详细信息, 请参阅[设置新的 Office 365 邮件加密功能](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)。</span><span class="sxs-lookup"><span data-stu-id="f4629-332">For more information about setting up new Message Encryption capabilities, see [Set up new Office 365 Message Encryption capabilities](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities).</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="f4629-333">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="f4629-333">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="f4629-334">管理员应将邮件流规则仅应用于已授权用户的高级邮件加密。</span><span class="sxs-lookup"><span data-stu-id="f4629-334">Admins should apply mail flow rules for Advanced Message Encryption only to licensed users.</span></span> <span data-ttu-id="f4629-335">有关定义邮件流规则的详细信息, 请参阅[在 Office 365 中定义用于加密电子邮件的邮件流规则](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)。</span><span class="sxs-lookup"><span data-stu-id="f4629-335">For more information about defining mail flow rules, see [Define mail flow rules to encrypt email messages in Office 365](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).</span></span>

## <a name="supervision-policies"></a><span data-ttu-id="f4629-336">监督策略</span><span class="sxs-lookup"><span data-stu-id="f4629-336">Supervision policies</span></span>

<span data-ttu-id="f4629-337">Office 365 中的监督策略使您可以捕获指定审阅者进行检查的员工通信。</span><span class="sxs-lookup"><span data-stu-id="f4629-337">Supervision policies in Office 365 allow you to capture employee communications for examination by designated reviewers.</span></span> <span data-ttu-id="f4629-338">您可以定义用于捕获组织中的内部和外部电子邮件、Microsoft 团队或第三方通信的特定策略。</span><span class="sxs-lookup"><span data-stu-id="f4629-338">You can define specific policies that capture internal and external email, Microsoft Teams, or third-party communications in your organization.</span></span> <span data-ttu-id="f4629-339">然后, 审阅者可以检查这些邮件, 以确保它们符合组织的邮件标准, 并使用分类类型解决这些问题。</span><span class="sxs-lookup"><span data-stu-id="f4629-339">Reviewers can then examine the messages to make sure that they are compliant with your organization's message standards and resolve them with classification type.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="f4629-340">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="f4629-340">Which users benefit from the service?</span></span>

<span data-ttu-id="f4629-341">Office 365 E5 的许可用户、Microsoft 365 E5、Microsoft 365 E5 和 Office 365 高级合规性可以从监督策略中受益。</span><span class="sxs-lookup"><span data-stu-id="f4629-341">Licensed users of Office 365 E5, Microsoft 365 E5, Microsoft 365 E5 Compliance, and Office 365 Advanced Compliance can benefit from supervision policies.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="f4629-342">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="f4629-342">How do users benefit from the service?</span></span>

<span data-ttu-id="f4629-343">用户通过监督策略监视其通信, 从而从服务中获益。</span><span class="sxs-lookup"><span data-stu-id="f4629-343">Users benefit from the service by having their communications monitored by supervision policies.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="f4629-344">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="f4629-344">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="f4629-345">管理员在安全 & 合规中心中创建监督策略。</span><span class="sxs-lookup"><span data-stu-id="f4629-345">Admins create supervision policies in the Security & Compliance Center.</span></span> <span data-ttu-id="f4629-346">这些策略定义哪些通信和用户将在组织中进行审阅, 定义通信必须满足的自定义条件, 并指定应执行审阅的用户。</span><span class="sxs-lookup"><span data-stu-id="f4629-346">These policies define which communications and users are subject to review in the organization, define custom conditions that the communications must meet, and specify who should perform reviews.</span></span>
 
### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="f4629-347">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="f4629-347">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="f4629-348">管理员选择要包含在监督策略中的特定用户或组。</span><span class="sxs-lookup"><span data-stu-id="f4629-348">Admins choose specific users or groups to include in a supervision policy.</span></span> <span data-ttu-id="f4629-349">在选择组时, 他们还可以选择组中要从监督策略中排除的特定用户。</span><span class="sxs-lookup"><span data-stu-id="f4629-349">When choosing a group, they can also select specific users in the group to exclude from the supervision policy.</span></span> <span data-ttu-id="f4629-350">有关监督策略的详细信息, 请参阅[Office 365 中的监察策略](https://docs.microsoft.com/office365/SecurityCompliance/supervision-policies)。</span><span class="sxs-lookup"><span data-stu-id="f4629-350">For more information about supervision polices, see [Supervision policies in Office 365](https://docs.microsoft.com/office365/SecurityCompliance/supervision-policies).</span></span>
