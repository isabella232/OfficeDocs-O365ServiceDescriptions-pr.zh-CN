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
ms.openlocfilehash: 099f17c638a2c8c9d6d13004dc19a29862de2555
ms.sourcegitcommit: 19591e97b35c1b2a99e04a496d83af27dc6530d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/18/2019
ms.locfileid: "37582028"
---
# <a name="microsoft-365-tenant-level-services-licensing-guidance"></a><span data-ttu-id="66b96-103">Microsoft 365 租户级服务许可指南</span><span class="sxs-lookup"><span data-stu-id="66b96-103">Microsoft 365 tenant-level services licensing guidance</span></span>

<span data-ttu-id="66b96-104">在本文中，租户级服务是一种在线服务，&mdash;在为租户中的任何用户购买（独立或作为 Office 365 或 Microsoft 365 计划的一部分）&mdash;时，将为租户中的所有用户激活或完全激活。</span><span class="sxs-lookup"><span data-stu-id="66b96-104">For the purposes of this article, a tenant-level service is an online service that&mdash;when purchased for any user in the tenant (standalone or as part of Office 365 or Microsoft 365 plans)&mdash;is activated in part or in full for all users in the tenant.</span></span> <span data-ttu-id="66b96-105">尽管一些未经许可的用户在技术上能够访问该服务，但您希望从该服务获益的任何用户都需要许可证。</span><span class="sxs-lookup"><span data-stu-id="66b96-105">Although some unlicensed users may technically be able to access the service, a license is required for any user that you intend to benefit from the service.</span></span>

> [!NOTE]
> <span data-ttu-id="66b96-106">某些租户服务当前不能限制特定用户的优势。</span><span class="sxs-lookup"><span data-stu-id="66b96-106">Some tenant services are not currently capable of limiting benefits to specific users.</span></span> <span data-ttu-id="66b96-107">应采取措施将服务的好处限制为许可用户。</span><span class="sxs-lookup"><span data-stu-id="66b96-107">Efforts should be taken to limit the service benefits to licensed users.</span></span> <span data-ttu-id="66b96-108">这有助于避免您的组织在获得目标功能后对组织造成潜在的服务中断。</span><span class="sxs-lookup"><span data-stu-id="66b96-108">This will help avoid potential service disruption to your organization once targeting capabilities are available.</span></span>

## <a name="azure-active-directory-identity-protection"></a><span data-ttu-id="66b96-109">Azure Active Directory Identity Protection</span><span class="sxs-lookup"><span data-stu-id="66b96-109">Azure Active Directory Identity Protection</span></span>

<span data-ttu-id="66b96-110">Azure Active Directory 标识保护（AADIP）是 Azure Active Directory 高级 P2 计划的一项功能，可让你检测影响组织标识的潜在漏洞，并将自动响应配置为检测到的可疑与您的组织的标识相关的操作，并调查可疑事件并采取适当的措施来解决这些问题。</span><span class="sxs-lookup"><span data-stu-id="66b96-110">Azure Active Directory Identity Protection (AADIP) is a feature of the Azure Active Directory Premium P2 plan that lets you detect potential vulnerabilities affecting your organization's identities, configure automated responses to detected suspicious actions that are related to your organization's identities, and investigate suspicious incidents and take appropriate action to resolve them.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="66b96-111">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="66b96-111">Which users benefit from the service?</span></span>

<span data-ttu-id="66b96-112">企业移动性 + 安全性 E5/A5/G5 的许可用户、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 和 Azure Active Directory 高级计划2可以从 AADIP 获益。</span><span class="sxs-lookup"><span data-stu-id="66b96-112">Licensed users of Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security, and Azure Active Directory Premium Plan 2 can benefit from AADIP.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="66b96-113">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="66b96-113">How do users benefit from the service?</span></span>

<span data-ttu-id="66b96-114">SecOps 分析师和安全专家将从基于机器学习算法的已标记用户和风险事件的合并视图中获益。</span><span class="sxs-lookup"><span data-stu-id="66b96-114">SecOps analysts and security professionals benefit from having consolidated views of flagged users and risk events based on machine learning algorithms.</span></span> <span data-ttu-id="66b96-115">最终用户可通过基于风险的条件访问提供自动保护，并通过对漏洞的操作提供改进的安全性来获得好处。</span><span class="sxs-lookup"><span data-stu-id="66b96-115">End users benefit from the automatic protection provided through risk-based Conditional Access and the improved security provided by acting on vulnerabilities.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="66b96-116">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="66b96-116">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="66b96-117">默认情况下，AADIP 功能在租户级别为租户中的所有用户启用。</span><span class="sxs-lookup"><span data-stu-id="66b96-117">By default, AADIP features are enabled at the tenant level for all users within the tenant.</span></span> <span data-ttu-id="66b96-118">有关配置 AADIP 的信息，请参阅[启用 Azure Active Directory Identity Protection](https://docs.microsoft.com/azure/active-directory/identity-protection/enable)。</span><span class="sxs-lookup"><span data-stu-id="66b96-118">For information on configuring AADIP, see [Enabling Azure Active Directory Identity Protection](https://docs.microsoft.com/azure/active-directory/identity-protection/enable).</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="66b96-119">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="66b96-119">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="66b96-120">管理员可以通过分配定义密码重置级别的风险策略并仅允许许可用户访问，来对 AADIP 进行作用域。</span><span class="sxs-lookup"><span data-stu-id="66b96-120">Admins can scope AADIP by assigning risk policies that define the level for password resets and allowing access for licensed users only.</span></span> <span data-ttu-id="66b96-121">有关如何对 AADIP 部署进行作用域的说明，请参阅[配置登录风险策略](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy)。</span><span class="sxs-lookup"><span data-stu-id="66b96-121">For instructions on how to scope AADIP deployments, see [Configure the sign-in risk policy](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy).</span></span>

## <a name="azure-advanced-threat-protection"></a><span data-ttu-id="66b96-122">Azure 高级威胁防护</span><span class="sxs-lookup"><span data-stu-id="66b96-122">Azure Advanced Threat Protection</span></span>

<span data-ttu-id="66b96-123">Azure 高级威胁防护（ATP）是一项云服务，可帮助保护企业混合环境，使其免受多种类型的高级目标网络攻击和内幕威胁的侵扰。</span><span class="sxs-lookup"><span data-stu-id="66b96-123">Azure Advanced Threat Protection (ATP) is a cloud service that helps protect enterprise hybrid environments from multiple types of advanced targeted cyber-attacks and insider threats.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="66b96-124">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="66b96-124">Which users benefit from the service?</span></span>

<span data-ttu-id="66b96-125">企业移动性 + 安全性 E5/A5/G5 的许可用户，Microsoft 365 E5/A5/G5，Microsoft 365 E5/A5/G5，以及 Azure 高级威胁防护可从 Azure ATP 获益。</span><span class="sxs-lookup"><span data-stu-id="66b96-125">Licensed users of Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security, and Azure Advanced Threat Protection for Users can benefit from Azure ATP.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="66b96-126">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="66b96-126">How do users benefit from the service?</span></span>

<span data-ttu-id="66b96-127">SecOp 分析师和安全性专家将受益于 Azure ATP 检测和调查高级威胁、已泄露身份和恶意内幕活动的能力。</span><span class="sxs-lookup"><span data-stu-id="66b96-127">SecOp analysts and security professionals benefit from the ability of Azure ATP to detect and investigate advanced threats, compromised identities, and malicious insider actions.</span></span> <span data-ttu-id="66b96-128">最终用户通过 Azure ATP 监视数据来获得好处。</span><span class="sxs-lookup"><span data-stu-id="66b96-128">End users benefit by having their data monitored by Azure ATP.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="66b96-129">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="66b96-129">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="66b96-130">默认情况下，在租户级别为租户中的所有用户启用 Azure ATP 功能。</span><span class="sxs-lookup"><span data-stu-id="66b96-130">By default, Azure ATP features are enabled at the tenant level for all users within the tenant.</span></span> <span data-ttu-id="66b96-131">有关配置 Azure ATP 的信息，请参阅[Create a AZURE atp instance](https://docs.microsoft.com/azure-advanced-threat-protection/install-atp-step1)。</span><span class="sxs-lookup"><span data-stu-id="66b96-131">For information on configuring Azure ATP, see [Create your Azure ATP instance](https://docs.microsoft.com/azure-advanced-threat-protection/install-atp-step1).</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="66b96-132">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="66b96-132">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="66b96-133">Microsoft 为许可用户提供威胁检测功能。</span><span class="sxs-lookup"><span data-stu-id="66b96-133">Microsoft provides threat detection capabilities for licensed users.</span></span>

## <a name="azure-information-protection"></a><span data-ttu-id="66b96-134">Azure 信息保护</span><span class="sxs-lookup"><span data-stu-id="66b96-134">Azure Information Protection</span></span>

<span data-ttu-id="66b96-135">Azure 信息保护（AIP）可帮助组织发现、分类、标记和保护敏感文档和电子邮件。</span><span class="sxs-lookup"><span data-stu-id="66b96-135">Azure Information Protection (AIP) helps organizations discover, classify, label, and protect sensitive documents and emails.</span></span> <span data-ttu-id="66b96-136">管理员可以定义规则和条件以自动应用标签，用户可以手动应用标签，也可以在向用户提供有关应用标签&mdash;的建议时使用二者的组合。</span><span class="sxs-lookup"><span data-stu-id="66b96-136">Admins can define rules and conditions to apply labels automatically, users can apply labels manually, or a combination of the two can be used&mdash;where users are given recommendations on applying labels.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="66b96-137">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="66b96-137">Which users benefit from the service?</span></span>

<span data-ttu-id="66b96-138">Microsoft 365 F1、Microsoft 365 商业版、Microsoft 365 E3/A3/G3 和 AIP Plan 1 的许可用户可从 AIP 计划1获益。</span><span class="sxs-lookup"><span data-stu-id="66b96-138">Licensed users of Microsoft 365 F1, Microsoft 365 Business, Microsoft 365 E3/A3/G3, and AIP Plan 1 can benefit from AIP Plan 1.</span></span> <span data-ttu-id="66b96-139">Microsoft 365 E5/A5/G5 的许可用户、Microsoft 365 E5/A5/G5 合规性和 AIP 计划2可从 AIP 计划2中受益。</span><span class="sxs-lookup"><span data-stu-id="66b96-139">Licensed users of Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, and AIP Plan 2 can benefit from AIP Plan 2.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="66b96-140">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="66b96-140">How do users benefit from the service?</span></span>

<span data-ttu-id="66b96-141">AIP 扫描程序功能会自动分类、标记和保护驻留在本地文件存储库中的文件。</span><span class="sxs-lookup"><span data-stu-id="66b96-141">The AIP scanner feature automatically classifies, labels, and protects files that reside in on-premises file repositories.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="66b96-142">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="66b96-142">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="66b96-143">默认情况下，AIP 功能在租户级别为租户中的所有用户启用。</span><span class="sxs-lookup"><span data-stu-id="66b96-143">By default, AIP features are enabled at the tenant level for all users within the tenant.</span></span> <span data-ttu-id="66b96-144">有关为许可用户配置 AIP 策略的信息，请参阅[激活 Azure 权限管理](https://docs.microsoft.com/azure/information-protection/activate-service)。</span><span class="sxs-lookup"><span data-stu-id="66b96-144">For information on configuring AIP policies for licensed users, see [Activating Azure Rights Management](https://docs.microsoft.com/azure/information-protection/activate-service).</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="66b96-145">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="66b96-145">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="66b96-146">AIP 功能策略（扫描程序功能除外）可以限定为特定的组或用户;可以对注册表进行编辑，以防止未授权的用户运行 AIP 分类或标记功能。</span><span class="sxs-lookup"><span data-stu-id="66b96-146">AIP feature policies (except the scanner feature) can be scoped to specific groups or users; registries can be edited to prevent unlicensed users from running AIP classification or labeling features.</span></span> <span data-ttu-id="66b96-147">有关如何对 AIP 部署进行作用域的说明，请参阅[配置 Azure 信息保护策略](https://docs.microsoft.com/azure/information-protection/configure-policy)。</span><span class="sxs-lookup"><span data-stu-id="66b96-147">For instructions on how to scope AIP deployments, see [Configuring the Azure Information Protection policy](https://docs.microsoft.com/azure/information-protection/configure-policy).</span></span>

<span data-ttu-id="66b96-148">对于 AIP 扫描程序功能，Microsoft 不会承诺向未获得许可的用户提供文件分类、标记或保护功能。</span><span class="sxs-lookup"><span data-stu-id="66b96-148">For the AIP scanner feature, Microsoft does not commit to providing file classification, labeling, or protection capabilities to users who are not licensed.</span></span> <span data-ttu-id="66b96-149">随着时间的推移，将向 AIP 中添加许可证检查或目标工具，以确保将扫描程序功能分配给许可用户。</span><span class="sxs-lookup"><span data-stu-id="66b96-149">Over time, license checks or targeted tooling will be added to AIP to ensure the scanner feature is assignable to licensed users.</span></span>

## <a name="office-365-advanced-threat-protection"></a><span data-ttu-id="66b96-150">Office 365 高级威胁防护</span><span class="sxs-lookup"><span data-stu-id="66b96-150">Office 365 Advanced Threat Protection</span></span>

<span data-ttu-id="66b96-151">高级威胁防护（ATP）可帮助组织防御复杂的攻击，如网络钓鱼和零日恶意软件。</span><span class="sxs-lookup"><span data-stu-id="66b96-151">Advanced Threat Protection (ATP) helps protect organizations against sophisticated attacks such as phishing and zero-day malware.</span></span> <span data-ttu-id="66b96-152">它还通过关联大量数据中的信号来提供可操作的见解，以帮助确定、设置优先级，并提供有关如何解决潜在威胁的建议。</span><span class="sxs-lookup"><span data-stu-id="66b96-152">It also provides actionable insights by correlating signals from a broad range of data to help identify, prioritize, and provide recommendations on how to address potential threats.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="66b96-153">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="66b96-153">Which users benefit from the service?</span></span>

<span data-ttu-id="66b96-154">Office 365 E5/A5/G5 许可用户，Microsoft 365 E5/A5/G5，Microsoft 365 E5/A5/G5 Security，Microsoft 365 Business 和 Office 365 ATP 计划1和2可从 ATP 获益。</span><span class="sxs-lookup"><span data-stu-id="66b96-154">Licensed users of Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security, Microsoft 365 Business, and Office 365 ATP Plans 1 and 2 can benefit from ATP.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="66b96-155">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="66b96-155">How do users benefit from the service?</span></span>

<span data-ttu-id="66b96-156">ATP 可保护用户免受复杂攻击（如网络钓鱼和零天恶意软件）的攻击。</span><span class="sxs-lookup"><span data-stu-id="66b96-156">ATP protects users from sophisticated attacks such as phishing and zero-day malware.</span></span> <span data-ttu-id="66b96-157">有关计划1和计划2中提供的服务的完整列表，请参阅[Office 365 高级威胁防护](https://products.office.com/exchange/advance-threat-protection)。</span><span class="sxs-lookup"><span data-stu-id="66b96-157">For the full list of services provided in Plan 1 and Plan 2, see [Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection).</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="66b96-158">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="66b96-158">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="66b96-159">默认情况下，在租户级别为租户中的所有用户启用 ATP 功能。</span><span class="sxs-lookup"><span data-stu-id="66b96-159">By default, ATP features are enabled at the tenant level for all users within the tenant.</span></span> <span data-ttu-id="66b96-160">有关为许可用户配置 ATP 策略的信息，请参阅[Office 365 高级威胁防护](https://docs.microsoft.com/office365/securitycompliance/office-365-atp)。</span><span class="sxs-lookup"><span data-stu-id="66b96-160">For information on configuring ATP policies for licensed users, see [Office 365 Advanced Threat Protection](https://docs.microsoft.com/office365/securitycompliance/office-365-atp).</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="66b96-161">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="66b96-161">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="66b96-162">若要对 ATP 进行作用域，请遵循安全链接和安全附件部署策略：</span><span class="sxs-lookup"><span data-stu-id="66b96-162">To scope ATP, follow the Safe Links and Safe Attachments deployment policies:</span></span>

  - <span data-ttu-id="66b96-163">有关为许可用户配置安全链接的信息，请参阅[设置 Office 365 ATP 安全链接策略](https://docs.microsoft.com/office365/securitycompliance/set-up-atp-safe-links-policies)。</span><span class="sxs-lookup"><span data-stu-id="66b96-163">For information on configuring Safe Links for licensed users, see [Set up Office 365 ATP Safe Links policies](https://docs.microsoft.com/office365/securitycompliance/set-up-atp-safe-links-policies).</span></span>

  - <span data-ttu-id="66b96-164">有关为许可用户配置安全附件的信息，请参阅[设置 Office 365 ATP 安全附件策略](https://docs.microsoft.com/office365/securitycompliance/set-up-atp-safe-attachments-policies)。</span><span class="sxs-lookup"><span data-stu-id="66b96-164">For information on configuring Safe Attachments for licensed users, see [Set up Office 365 ATP Safe Attachments policies](https://docs.microsoft.com/office365/securitycompliance/set-up-atp-safe-attachments-policies).</span></span>

## <a name="office-365-cloud-app-security"></a><span data-ttu-id="66b96-165">Office 365 云应用安全</span><span class="sxs-lookup"><span data-stu-id="66b96-165">Office 365 Cloud App Security</span></span>

<span data-ttu-id="66b96-166">Office 365 云应用安全（OCAS）是 Microsoft 云应用安全性的子集，其中的功能仅限于 Office 365，而无需对第三方云应用和 IaaS 服务进行额外的安全性。</span><span class="sxs-lookup"><span data-stu-id="66b96-166">Office 365 Cloud App Security (OCAS) is a subset of Microsoft Cloud App Security, with features limited to Office 365 and without additional security for third-party cloud apps and IaaS services.</span></span>

<span data-ttu-id="66b96-167">OCAS 使组织能够深入了解他们的工作效率云应用和服务，提供了完善的分析来识别和防御网络威胁，并使&mdash;他们可以控制数据在 Office 365 之间的传输方式。</span><span class="sxs-lookup"><span data-stu-id="66b96-167">OCAS gives organizations visibility into their productivity cloud apps and services, provides sophisticated analytics to identify and combat cyber threats, and lets them control how data travels&mdash;across Office 365.</span></span>

<span data-ttu-id="66b96-168">若要比较功能，请参阅[Microsoft Cloud App security 与 Office 365 云应用安全性之间的差异](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365)。</span><span class="sxs-lookup"><span data-stu-id="66b96-168">To compare features, see [Differences between Microsoft Cloud App Security and Office 365 Cloud App Security](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365).</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="66b96-169">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="66b96-169">Which users benefit from the service?</span></span>

<span data-ttu-id="66b96-170">Office 365 E5/G5 的许可用户可以从 OCAS 获益。</span><span class="sxs-lookup"><span data-stu-id="66b96-170">Licensed users of Office 365 E5/A5/G5 can benefit from OCAS.</span></span>

<span data-ttu-id="66b96-171">有关详细信息，请参阅[Microsoft Cloud App Security 授权数据表](http://www.aka.ms/mcaslicensing)。</span><span class="sxs-lookup"><span data-stu-id="66b96-171">For more information, see the [Microsoft Cloud App Security Licensing Datasheet](http://www.aka.ms/mcaslicensing).</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="66b96-172">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="66b96-172">How do users benefit from the service?</span></span>

<span data-ttu-id="66b96-173">OCAS 发现影子它，提供了 Office 365 之间的威胁防护，并可以控制哪些应用有权访问 Office 365 数据。</span><span class="sxs-lookup"><span data-stu-id="66b96-173">OCAS discovers Shadow IT, provides threat protection across Office 365, and can control which apps have permission to access Office 365 data.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="66b96-174">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="66b96-174">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="66b96-175">默认情况下，OCAS 功能在租户级别为租户中的所有用户启用。</span><span class="sxs-lookup"><span data-stu-id="66b96-175">By default, OCAS features are enabled at the tenant level for all users within the tenant.</span></span>

<span data-ttu-id="66b96-176">有关配置服务的信息，请参阅[Basic setup For Cloud App Security](https://docs.microsoft.com/cloud-app-security/general-setup)。</span><span class="sxs-lookup"><span data-stu-id="66b96-176">For information on configuring the service, see [Basic setup for Cloud App Security](https://docs.microsoft.com/cloud-app-security/general-setup).</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="66b96-177">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="66b96-177">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="66b96-178">管理员可以对 OCAS 部署进行作用域，以强制实施特定应用程序的访问方式并限制由 Office 365 云应用安全性监控的用户组。</span><span class="sxs-lookup"><span data-stu-id="66b96-178">Admins can scope OCAS deployments to enforce how certain apps are accessed and limit user groups monitored by Office 365 Cloud App Security.</span></span> <span data-ttu-id="66b96-179">有关详细信息，请参阅[作用域部署](https://docs.microsoft.com/cloud-app-security/scoped-deployment)。</span><span class="sxs-lookup"><span data-stu-id="66b96-179">For more information, see [Scoped deployment](https://docs.microsoft.com/cloud-app-security/scoped-deployment).</span></span>

## <a name="microsoft-cloud-app-security"></a><span data-ttu-id="66b96-180">Microsoft Cloud App Security</span><span class="sxs-lookup"><span data-stu-id="66b96-180">Microsoft Cloud App Security</span></span>

<span data-ttu-id="66b96-181">Microsoft Cloud App Security （MCAS）是一个云访问安全代理（CASB）解决方案，它为组织提供了其云应用和服务的可见性，提供了完善的分析来识别和防御网络威胁，并让他们控制数据跨&mdash;任意云应用传播。</span><span class="sxs-lookup"><span data-stu-id="66b96-181">Microsoft Cloud App Security (MCAS) is a Cloud Access Security Broker (CASB) solution that gives organizations visibility into their cloud apps and services, provides sophisticated analytics to identify and combat cyber threats, and lets them control how data travels&mdash;across any cloud app.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="66b96-182">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="66b96-182">Which users benefit from the service?</span></span>

<span data-ttu-id="66b96-183">授权用户的 MCAS，企业移动性 + 安全性 E5/A5/G5，Microsoft 365 E5/A5/G5 和 Microsoft 365 E5/A5/G5 安全性可从 MCAS 获益。</span><span class="sxs-lookup"><span data-stu-id="66b96-183">Licensed users of MCAS, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, and Microsoft 365 E5/A5/G5 Security can benefit from MCAS.</span></span>

<span data-ttu-id="66b96-184">Azure AD P1 的许可用户可以从 MCAS 中的发现功能中受益。</span><span class="sxs-lookup"><span data-stu-id="66b96-184">Licensed users of Azure AD P1 can benefit from the Discovery capabilities in MCAS.</span></span>

<span data-ttu-id="66b96-185">若要从 MCAS 中的[条件访问应用程序控制](https://docs.microsoft.com/cloud-app-security/proxy-intro-aad)功能中受益，还必须授予用户 Azure Active Directory P1 （包含在企业移动性 + 安全 E3/A3/G3、企业移动性 + 安全性 E5/A5/G5、Microsoft 365 E3/A3/G3、Microsoft 365 E5/A5/G5 和 Microsoft 365 E5/A5/G5 安全性。</span><span class="sxs-lookup"><span data-stu-id="66b96-185">To benefit from the [Conditional Access App Control](https://docs.microsoft.com/cloud-app-security/proxy-intro-aad) capabilities in MCAS, users must also be licensed for Azure Active Directory P1, which is included in Enterprise Mobility + Security E3/A3/G3, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E3/A3/G3, Microsoft 365 E5/A5/G5, and Microsoft 365 E5/A5/G5 Security.</span></span>

<span data-ttu-id="66b96-186">若要从[自动标记](https://docs.microsoft.com/cloud-app-security/data-protection-policies)中受益，用户必须获得 Azure 信息保护 P2 的许可，该版本包含在企业移动性 + 安全 E5/A5/g5 中，Microsoft 365 E5/A5/G5 和 Microsoft 365 E5/A5/G5 合规性。</span><span class="sxs-lookup"><span data-stu-id="66b96-186">To benefit from [automatic labeling](https://docs.microsoft.com/cloud-app-security/data-protection-policies), users must be licensed for Azure Information Protection P2, which is included in Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, and Microsoft 365 E5/A5/G5 Compliance.</span></span>

<span data-ttu-id="66b96-187">有关详细信息，请参阅[Microsoft Cloud App Security 授权数据表](http://www.aka.ms/mcaslicensing)。</span><span class="sxs-lookup"><span data-stu-id="66b96-187">For more information, see the [Microsoft Cloud App Security Licensing Datasheet](http://www.aka.ms/mcaslicensing).</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="66b96-188">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="66b96-188">How do users benefit from the service?</span></span>

<span data-ttu-id="66b96-189">MCAS 发现和评估阴影，提供跨第一方云应用程序的威胁保护，并在第一方和第三方云应用中保护信息。</span><span class="sxs-lookup"><span data-stu-id="66b96-189">MCAS discovers and assesses Shadow IT, provides threat protection across first- and third-party cloud apps, and protects information across first- and third-party cloud apps.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="66b96-190">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="66b96-190">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="66b96-191">默认情况下，MCAS 功能在租户级别为租户中的所有用户启用。</span><span class="sxs-lookup"><span data-stu-id="66b96-191">By default, MCAS features are enabled at the tenant level for all users within the tenant.</span></span>

<span data-ttu-id="66b96-192">有关为许可用户配置 Microsoft 云应用安全策略的信息，请参阅[Microsoft Cloud App security 概述](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)。</span><span class="sxs-lookup"><span data-stu-id="66b96-192">For information on configuring Microsoft Cloud App Security policies for licensed users, see [Microsoft Cloud App Security overview](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security).</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="66b96-193">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="66b96-193">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="66b96-194">管理员可以使用服务中提供的作用域部署功能将 MCAS 部署限定为许可用户。</span><span class="sxs-lookup"><span data-stu-id="66b96-194">Admins can scope MCAS deployments to licensed users by using the scoped deployment capabilities available in the service.</span></span> <span data-ttu-id="66b96-195">有关详细信息，请参阅[作用域部署](https://docs.microsoft.com/cloud-app-security/scoped-deployment)。</span><span class="sxs-lookup"><span data-stu-id="66b96-195">For more information, see [Scoped deployment](https://docs.microsoft.com/cloud-app-security/scoped-deployment).</span></span>

## <a name="office-365-advanced-data-governance"></a><span data-ttu-id="66b96-196">Office 365 高级数据管理</span><span class="sxs-lookup"><span data-stu-id="66b96-196">Office 365 Advanced Data Governance</span></span>

<span data-ttu-id="66b96-197">高级数据治理（ADG）可帮助组织通过启用保留和删除的策略满足信息治理要求。</span><span class="sxs-lookup"><span data-stu-id="66b96-197">Advanced Data Governance (ADG) helps organizations meet information governance requirements with policies to enable retention and deletion.</span></span> <span data-ttu-id="66b96-198">ADG 允许组织根据敏感信息类型自动标记内容，并对该内容应用调控策略。</span><span class="sxs-lookup"><span data-stu-id="66b96-198">ADG lets organizations auto-label content based on sensitive information type and apply governance policies to that content.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="66b96-199">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="66b96-199">Which users benefit from the service?</span></span>

<span data-ttu-id="66b96-200">许可用户的 Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 合规性和 Office 365 高级合规性可以从 ADG 获益。</span><span class="sxs-lookup"><span data-stu-id="66b96-200">Licensed users of Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, and Office 365 Advanced Compliance can benefit from ADG.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="66b96-201">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="66b96-201">How do users benefit from the service?</span></span>

<span data-ttu-id="66b96-202">ADG 允许用户将标签应用于特定数据，以对特定的策略进行对齐、自动将内容标记为记录，以及管理从声明到处置的完整记录过程。</span><span class="sxs-lookup"><span data-stu-id="66b96-202">ADG lets users apply labels to specific data to uphold specific policies, automatically label content as a record, and manage the full records process from declaration to disposal.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="66b96-203">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="66b96-203">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="66b96-204">默认情况下，ADG 功能在租户级别为租户中的所有用户启用。</span><span class="sxs-lookup"><span data-stu-id="66b96-204">By default, ADG features are enabled at the tenant level for all users within the tenant.</span></span> <span data-ttu-id="66b96-205">有关配置 ADG 以将自动标记和策略应用于许可用户的信息，请参阅[保留标签概述](https://docs.microsoft.com/office365/securitycompliance/labels)。</span><span class="sxs-lookup"><span data-stu-id="66b96-205">For information on configuring ADG to apply auto-labeling and policies for licensed users, see [Overview of retention labels](https://docs.microsoft.com/office365/securitycompliance/labels).</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="66b96-206">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="66b96-206">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="66b96-207">可以通过自动分类将 ADG 保留策略应用于特定位置（工作组网站、组网站等）的许可用户。</span><span class="sxs-lookup"><span data-stu-id="66b96-207">ADG retention policies can be applied to licensed users in specific locations (team sites, group sites, etc.) through automatic classification.</span></span> <span data-ttu-id="66b96-208">有关应用 ADG 保留策略的说明，请参阅[将保留策略应用于整个组织或特定位置](https://docs.microsoft.com/office365/securitycompliance/retention-policies#applying-a-retention-policy-to-an-entire-organization-or-specific-locations)。</span><span class="sxs-lookup"><span data-stu-id="66b96-208">For instructions on applying ADG retention policies, see [Applying a retention policy to an entire organization or specific locations](https://docs.microsoft.com/office365/securitycompliance/retention-policies#applying-a-retention-policy-to-an-entire-organization-or-specific-locations).</span></span>

## <a name="office-365-advanced-ediscovery"></a><span data-ttu-id="66b96-209">Office 365 高级电子数据展示</span><span class="sxs-lookup"><span data-stu-id="66b96-209">Office 365 Advanced eDiscovery</span></span>

<span data-ttu-id="66b96-210">Office 365 高级电子数据展示为 IT 和公司内部的法律部门提供调查和电子数据展示解决方案，以确定、收集、保留、减少和查看与调查或诉讼相关的内容，然后再导出Office 365 系统。</span><span class="sxs-lookup"><span data-stu-id="66b96-210">Office 365 Advanced eDiscovery provides investigation and eDiscovery solutions for IT and legal departments within corporations to identify, collect, preserve, reduce, and review content related to an investigation or litigation prior to export out of the Office 365 system.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="66b96-211">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="66b96-211">Which users benefit from the service?</span></span>

<span data-ttu-id="66b96-212">许可用户的 Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 合规性和 Office 365 高级合规性可以从高级电子数据展示中受益。</span><span class="sxs-lookup"><span data-stu-id="66b96-212">Licensed users of Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, and Office 365 Advanced Compliance can benefit from Advanced eDiscovery.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="66b96-213">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="66b96-213">How do users benefit from the service?</span></span>

<span data-ttu-id="66b96-214">当用户选择作为数据管理员（具有文档或电子文件的管理控制）时，用户将从高级电子数据展示中受益。</span><span class="sxs-lookup"><span data-stu-id="66b96-214">A user benefits from Advanced eDiscovery when the user is selected as a data custodian (a person having administrative control of a document or electronic file) for a case.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="66b96-215">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="66b96-215">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="66b96-216">默认情况下，当管理员在安全 & 合规中心中分配电子数据展示权限时，将在租户级别为租户中的所有用户启用高级电子数据展示功能。</span><span class="sxs-lookup"><span data-stu-id="66b96-216">By default, Advanced eDiscovery features are enabled at the tenant level for all users within the tenant when admins assign eDiscovery permissions in the Security & Compliance Center.</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="66b96-217">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="66b96-217">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="66b96-218">通过使用高级电子数据展示中的内置保管人管理工具，电子数据展示管理员可以选择特定用户作为事例的数据保管人，如[将保管人添加到高级电子数据展示事例](https://docs.microsoft.com/office365/securitycompliance/compliance20/add-custodians-to-case)中所述。</span><span class="sxs-lookup"><span data-stu-id="66b96-218">eDiscovery administrators can select specific users as data custodians for a case by using the built-in custodian management tool in Advanced eDiscovery as described in [Add custodians to an Advanced eDiscovery case](https://docs.microsoft.com/office365/securitycompliance/compliance20/add-custodians-to-case).</span></span>

## <a name="office-365-customer-key"></a><span data-ttu-id="66b96-219">Office 365 客户密钥</span><span class="sxs-lookup"><span data-stu-id="66b96-219">Office 365 Customer Key</span></span>

<span data-ttu-id="66b96-220">使用 "客户密钥"，可以控制组织的加密密钥，并配置 Office 365 以使用它们在 Microsoft 数据中心中对静态数据进行加密。</span><span class="sxs-lookup"><span data-stu-id="66b96-220">With Customer Key, you control your organization's encryption keys and configure Office 365 to use them to encrypt your data at rest in Microsoft's data centers.</span></span> <span data-ttu-id="66b96-221">换句话说，客户密钥允许您使用自己的密钥添加属于您的加密层。</span><span class="sxs-lookup"><span data-stu-id="66b96-221">In other words, Customer Key allows you to add a layer of encryption that belongs to you, using your own keys.</span></span> <span data-ttu-id="66b96-222">静态数据包含来自 Exchange Online 和 Skype for business 的数据，这些数据存储在 SharePoint Online 和 OneDrive for business 中的邮箱和文件中。</span><span class="sxs-lookup"><span data-stu-id="66b96-222">Data at rest includes data from Exchange Online and Skype for Business that is stored in mailboxes and files within SharePoint Online and OneDrive for Business.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="66b96-223">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="66b96-223">Which users benefit from the service?</span></span>

<span data-ttu-id="66b96-224">许可用户的 Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 合规性，以及 Office 365 高级合规性可从客户密钥获益。</span><span class="sxs-lookup"><span data-stu-id="66b96-224">Licensed users of Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, and Office 365 Advanced Compliance can benefit from Customer Key.</span></span> <span data-ttu-id="66b96-225">若要获得客户密钥的全部好处，您还必须具有 Azure Key Vault 的订阅。</span><span class="sxs-lookup"><span data-stu-id="66b96-225">To get the full benefit of Customer Key, you must also have a subscription for Azure Key Vault.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="66b96-226">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="66b96-226">How do users benefit from the service?</span></span>

<span data-ttu-id="66b96-227">用户可通过在应用程序层使用提供、控制和管理自己的组织的加密密钥在应用程序层对其数据进行加密，从而获得客户密钥的好处。</span><span class="sxs-lookup"><span data-stu-id="66b96-227">Users benefit from Customer Key by having their data at rest encrypted at the application layer using encryption keys that are provided, controlled, and managed by their own organization.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="66b96-228">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="66b96-228">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="66b96-229">可以为存储在 Exchange Online 和 Skype for business 邮箱以及 SharePoint Online 和 OneDrive for business 文件中的所有数据启用 Office 365 客户密钥加密密钥。</span><span class="sxs-lookup"><span data-stu-id="66b96-229">Office 365 Customer Key encryption keys can be enabled for all data stored in Exchange Online and Skype for Business mailboxes, and SharePoint Online and OneDrive for Business files.</span></span> <span data-ttu-id="66b96-230">有关配置 Office 365 客户密钥以加密静态数据的信息，请参阅[使用客户密钥控制 office 365 中的数据](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key)。</span><span class="sxs-lookup"><span data-stu-id="66b96-230">For information on configuring Office 365 Customer Key to encrypt your data at rest, see [Controlling Your Data in Office 365 Using Customer Key](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key).</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="66b96-231">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="66b96-231">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="66b96-232">若要将加密密钥分配给 Office 365 和/或 Microsoft 365 租户中的数据以供许可用户使用，请按照客户密钥加密密钥部署说明进行操作：</span><span class="sxs-lookup"><span data-stu-id="66b96-232">To assign encryption keys to data within an Office 365 and/or Microsoft 365 tenant for licensed users, follow the Customer Key encryption keys deployment instructions:</span></span>

  - <span data-ttu-id="66b96-233">对于 SharePoint Online 和 OneDrive for business，一个或多个网站上的文件可使用客户密钥进行加密，如下所述：为[SharePoint Online 和 OneDrive For Business 设置客户密钥](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key#office-365-setting-up-customer-key-for-sharepoint-online-and-onedrive-for-business)。</span><span class="sxs-lookup"><span data-stu-id="66b96-233">For SharePoint Online and OneDrive for Business, files on one or more sites can be encrypted using Customer Key as described here: [Setting up Customer Key for SharePoint Online and OneDrive for Business](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key#office-365-setting-up-customer-key-for-sharepoint-online-and-onedrive-for-business).</span></span>

  - <span data-ttu-id="66b96-234">对于 Exchange Online 和 Skype for business Online，可以使用以下所述的客户密钥对邮箱进行加密：[设置 Exchange Online 和 Skype for business 的客户密钥](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key#office-365-setting-up-customer-key-for-exchange-online-and-skype-for-business)</span><span class="sxs-lookup"><span data-stu-id="66b96-234">For Exchange Online and Skype for Business Online, mailboxes can be encrypted using Customer Key as described here: [Setting up Customer Key for Exchange Online and Skype for Business](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key#office-365-setting-up-customer-key-for-exchange-online-and-skype-for-business)</span></span>

## <a name="office-365-customer-lockbox"></a><span data-ttu-id="66b96-235">Office 365 客户密码箱</span><span class="sxs-lookup"><span data-stu-id="66b96-235">Office 365 Customer Lockbox</span></span>

<span data-ttu-id="66b96-236">客户密码箱通过让客户能够为服务操作提供显式访问授权，从而提供了一个额外的控制层。</span><span class="sxs-lookup"><span data-stu-id="66b96-236">Customer Lockbox provides an additional layer of control by offering customers the ability to give explicit access authorization for service operations.</span></span> <span data-ttu-id="66b96-237">通过演示如何将过程用于显式数据访问授权，客户密码箱还可以帮助组织满足特定合规性义务，如 HIPAA 和 FEDRAMP。</span><span class="sxs-lookup"><span data-stu-id="66b96-237">By demonstrating that procedures are in place for explicit data access authorization, Customer Lockbox may also help organizations meet certain compliance obligations such as HIPAA and FEDRAMP.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="66b96-238">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="66b96-238">Which users benefit from the service?</span></span>

<span data-ttu-id="66b96-239">许可用户的 Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 合规性，以及 Office 365 高级合规性可从客户密码箱获益。</span><span class="sxs-lookup"><span data-stu-id="66b96-239">Licensed users of Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, and the Office 365 Advanced Compliance can benefit from Customer Lockbox.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="66b96-240">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="66b96-240">How do users benefit from the service?</span></span>

<span data-ttu-id="66b96-241">用户可以从客户密码箱获益，确保 Microsoft 无需在未经客户明确批准的情况下即可在 Microsoft 不能访问其内容的情况下执行服务操作。</span><span class="sxs-lookup"><span data-stu-id="66b96-241">Users benefit from Customer Lockbox ensuring that no one at Microsoft can access their content to perform a service operation without the customer’s explicit approval.</span></span> <span data-ttu-id="66b96-242">客户密码箱将客户引入审批工作流，以获取访问其内容的请求。</span><span class="sxs-lookup"><span data-stu-id="66b96-242">Customer Lockbox brings the customer into the approval workflow for requests to access their content.</span></span> <span data-ttu-id="66b96-243">有时，Microsoft 工程师会在支持流程中参与诊断和修复客户报告的问题。</span><span class="sxs-lookup"><span data-stu-id="66b96-243">Occasionally, Microsoft engineers are involved during the support process to troubleshoot and fix customer-reported issues.</span></span> <span data-ttu-id="66b96-244">在大多数情况下，通过 Microsoft 为其服务提供的大量遥测和调试工具解决了问题。</span><span class="sxs-lookup"><span data-stu-id="66b96-244">In most cases, issues are fixed through extensive telemetry and debugging tools that Microsoft has in place for its services.</span></span> <span data-ttu-id="66b96-245">但是，在某些情况下，可能需要 Microsoft 工程师访问客户内容以确定根本原因并解决问题。</span><span class="sxs-lookup"><span data-stu-id="66b96-245">However, there may be cases that require a Microsoft engineer to access customer content to determine the root cause and fix the issue.</span></span> <span data-ttu-id="66b96-246">客户密码箱要求工程师在审批工作流的最后步骤中请求从客户进行访问。</span><span class="sxs-lookup"><span data-stu-id="66b96-246">Customer Lockbox requires the engineer to request access from the customer as a final step in the approval workflow.</span></span> <span data-ttu-id="66b96-247">这为组织提供了批准或拒绝这些请求的选项，这些请求使他们可以直接控制 Microsoft 工程师是否可以访问组织的最终用户数据。</span><span class="sxs-lookup"><span data-stu-id="66b96-247">This gives organizations the option to approve or deny these requests, which gives them direct control over whether a Microsoft engineer can access the organizations’ end-user data.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="66b96-248">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="66b96-248">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="66b96-249">管理员可以在 Microsoft 365 管理中心启用客户密码箱控件。</span><span class="sxs-lookup"><span data-stu-id="66b96-249">Admins can turn on Customer Lockbox controls in the Microsoft 365 admin center.</span></span> <span data-ttu-id="66b96-250">有关详细信息，请参阅[Office 365 中的客户密码箱](https://docs.microsoft.com/Office365/Admin/manage/customer-lockbox-requests)。</span><span class="sxs-lookup"><span data-stu-id="66b96-250">For more information, see [Customer Lockbox in Office 365](https://docs.microsoft.com/Office365/Admin/manage/customer-lockbox-requests).</span></span> <span data-ttu-id="66b96-251">当客户密码箱打开时，在访问其任何内容之前，需要 Microsoft 获取组织的批准。</span><span class="sxs-lookup"><span data-stu-id="66b96-251">When Customer Lockbox is turned on, Microsoft is required to obtain an organization’s approval prior to accessing any of their content.</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="66b96-252">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="66b96-252">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="66b96-253">Microsoft 为 Office 365 组织中的用户提供客户密码箱访问控制审批请求。</span><span class="sxs-lookup"><span data-stu-id="66b96-253">Microsoft provides Customer Lockbox access control approval requests for users in your Office 365 organization.</span></span>

## <a name="privileged-access-management-in-office-365"></a><span data-ttu-id="66b96-254">Office 365 中的特权访问管理</span><span class="sxs-lookup"><span data-stu-id="66b96-254">Privileged access management in Office 365</span></span>

<span data-ttu-id="66b96-255">特权访问管理（PAM）提供对 Office 365 中的特权管理任务的精细访问控制。</span><span class="sxs-lookup"><span data-stu-id="66b96-255">Privileged access management (PAM) provides granular access control over privileged admin tasks in Office 365.</span></span> <span data-ttu-id="66b96-256">启用 PAM 后，用户将需要通过高度范围和时间限制的审批工作流请求实时访问，以完成提升和特权的任务。</span><span class="sxs-lookup"><span data-stu-id="66b96-256">After enabling PAM, users will need to request just-in-time access through an approval workflow that is highly scoped and time-bound in order to complete elevated and privileged tasks.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="66b96-257">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="66b96-257">Which users benefit from the service?</span></span>

<span data-ttu-id="66b96-258">许可用户的 Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 合规性和 Office 365 高级合规性可以从 PAM 中受益。</span><span class="sxs-lookup"><span data-stu-id="66b96-258">Licensed users of Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, and Office 365 Advanced Compliance can benefit from PAM.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="66b96-259">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="66b96-259">How do users benefit from the service?</span></span>

<span data-ttu-id="66b96-260">启用 PAM 可让组织以零作为自主权限运行。</span><span class="sxs-lookup"><span data-stu-id="66b96-260">Enabling PAM lets organizations operate with zero standing privileges.</span></span> <span data-ttu-id="66b96-261">用户从增加的防御层中受益，以防止因提供对其数据的 unfettered 访问而产生的漏洞。</span><span class="sxs-lookup"><span data-stu-id="66b96-261">Users benefit from the added layer of defense against vulnerabilities arising from standing administrative access that provides unfettered access to their data.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="66b96-262">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="66b96-262">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="66b96-263">默认情况下，在租户级别为租户中的所有用户启用 PAM 功能。</span><span class="sxs-lookup"><span data-stu-id="66b96-263">By default, PAM features are enabled at the tenant level for all users within the tenant.</span></span> <span data-ttu-id="66b96-264">有关配置 PAM 策略的信息，请参阅[在 Office 365 中配置特权访问管理](https://docs.microsoft.com/office365/securitycompliance/privileged-access-management-configuration)。</span><span class="sxs-lookup"><span data-stu-id="66b96-264">For information on configuring PAM policies, see [Configuring privileged access management in Office 365](https://docs.microsoft.com/office365/securitycompliance/privileged-access-management-configuration).</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="66b96-265">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="66b96-265">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="66b96-266">客户可以通过审核人组和访问策略（可应用于许可用户）在每用户的基础上管理 PAM。</span><span class="sxs-lookup"><span data-stu-id="66b96-266">Customers can manage PAM on a per-user basis through approver group and access policies, which can be applied to licensed users.</span></span> <span data-ttu-id="66b96-267">有关详细信息，请参阅[Office 365 中的特权访问管理](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751)。</span><span class="sxs-lookup"><span data-stu-id="66b96-267">For more information, see [Privileged Access Management in Office 365](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751).</span></span>

## <a name="data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a><span data-ttu-id="66b96-268">Exchange Online、SharePoint Online 和 OneDrive for business 的数据丢失防护</span><span class="sxs-lookup"><span data-stu-id="66b96-268">Data loss prevention for Exchange Online, SharePoint Online, and OneDrive for Business</span></span>

<span data-ttu-id="66b96-269">对于 Exchange Online、SharePoint Online 和 OneDrive for Business 的数据丢失防护（DLP），组织可以通过电子邮件和文件（包括存储在 Microsoft 团队文件中的文件）识别、监视和自动保护敏感信息。存储库）。</span><span class="sxs-lookup"><span data-stu-id="66b96-269">With data loss prevention (DLP) for Exchange Online, SharePoint Online, and OneDrive for Business, organizations can identify, monitor, and automatically protect sensitive information across emails and files (including files stored in Microsoft Teams file repositories).</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="66b96-270">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="66b96-270">Which users benefit from the service?</span></span>

<span data-ttu-id="66b96-271">Office 365 E3/A3/G3、Microsoft 365 Business、Microsoft 365 A1/E3/A3/G3 和 Office 365 数据丢失防护的许可用户可受益于 DLP for Exchange Online、SharePoint Online 和 OneDrive for Business。</span><span class="sxs-lookup"><span data-stu-id="66b96-271">Licensed users of Office 365 E3/A3/G3, Microsoft 365 Business, Microsoft 365 A1/E3/A3/G3, and Office 365 data loss prevention can benefit from DLP for Exchange Online, SharePoint Online, and OneDrive for Business.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="66b96-272">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="66b96-272">How do users benefit from the service?</span></span>

<span data-ttu-id="66b96-273">当检查其电子邮件和文件中的敏感信息（如组织的 DLP 策略中配置）时，用户将受益于 DLP for Exchange Online、SharePoint Online 和 OneDrive for business。</span><span class="sxs-lookup"><span data-stu-id="66b96-273">Users benefit from DLP for Exchange Online, SharePoint Online, and OneDrive for Business when their emails and files are being inspected for sensitive information, as configured in the organization’s DLP policy.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="66b96-274">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="66b96-274">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="66b96-275">默认情况下，Exchange Online 电子邮件、SharePoint 网站和 OneDrive 帐户为租户中的所有用户启用这些 DLP 功能的*位置（工作负荷）* 。</span><span class="sxs-lookup"><span data-stu-id="66b96-275">By default, Exchange Online emails, SharePoint sites, and OneDrive accounts are *enabled locations (workloads)* for these DLP features for all users within the tenant.</span></span> <span data-ttu-id="66b96-276">有关使用 DLP 策略的详细信息，请参阅[数据丢失防护概述](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)。</span><span class="sxs-lookup"><span data-stu-id="66b96-276">For more information about using DLP policies, see [Overview of data loss prevention](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies).</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="66b96-277">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="66b96-277">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="66b96-278">管理员可以在 "Office 365 安全 & 合规中心" 中的 "**数据丢失防护** > **位置**" 下自定义位置（工作负荷）、包含的用户和排除的用户。</span><span class="sxs-lookup"><span data-stu-id="66b96-278">Admins can customize locations (workloads), included users, and excluded users in the Office 365 Security & Compliance Center, under **Data loss prevention** > **Locations**.</span></span>

## <a name="data-loss-prevention-for-teams-chat-and-channel-messages"></a><span data-ttu-id="66b96-279">工作组聊天和频道消息的数据丢失防护</span><span class="sxs-lookup"><span data-stu-id="66b96-279">Data loss prevention for Teams chat and channel messages</span></span>

<span data-ttu-id="66b96-280">使用数据丢失防护（DLP）获取团队聊天和频道消息时，组织可以阻止包含敏感信息的聊天和频道消息，如财务信息、个人标识信息、与运行状况相关的信息，或其他机密信息。</span><span class="sxs-lookup"><span data-stu-id="66b96-280">With data loss prevention (DLP) for Teams chat and channel messages, organizations can block chats and channel messages that contain sensitive information, such as financial information, personally identifying information, health-related information, or other confidential information.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="66b96-281">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="66b96-281">Which users benefit from the service?</span></span>

<span data-ttu-id="66b96-282">Office 365 E5/A5/G5 许可用户，Microsoft 365 E5/A5/G5，Microsoft 365 E5/A5/G5 合规性，Office 365 高级合规性可以从 DLP for team chat and 频道消息中获益。</span><span class="sxs-lookup"><span data-stu-id="66b96-282">Licensed users of Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, and Office 365 Advanced Compliance can benefit from DLP for Teams chat and channel messages.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="66b96-283">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="66b96-283">How do users benefit from the service?</span></span>

<span data-ttu-id="66b96-284">通过在组织的 DLP 策略中配置的敏感信息检查其传出聊天和频道消息中的敏感信息，发件人会获得好处。</span><span class="sxs-lookup"><span data-stu-id="66b96-284">Senders benefit by having sensitive information in their outgoing chat and channel messages inspected for sensitive information, as configured in the organization’s DLP policy.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="66b96-285">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="66b96-285">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="66b96-286">默认情况下，团队聊天和频道消息是租户中所有用户的这些 DLP 功能的*已启用位置（工作负荷）* 。</span><span class="sxs-lookup"><span data-stu-id="66b96-286">By default, Teams chat and channel messages are an *enabled Location (workload)* for these DLP features for all users within the tenant.</span></span> <span data-ttu-id="66b96-287">有关使用 DLP 策略的详细信息，请参阅[数据丢失防护概述](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)。</span><span class="sxs-lookup"><span data-stu-id="66b96-287">For more information about using DLP policies, see [Overview of data loss prevention](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies).</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="66b96-288">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="66b96-288">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="66b96-289">管理员可以在 "Office 365 安全 & 合规中心" 中的 "**数据丢失防护** > **位置**" 下自定义位置（工作负荷）、包含的用户和排除的用户。</span><span class="sxs-lookup"><span data-stu-id="66b96-289">Admins can customize locations (workloads), included users, and excluded users in the Office 365 Security & Compliance Center, under **Data loss prevention** > **Locations**.</span></span>

## <a name="information-barriers"></a><span data-ttu-id="66b96-290">信息屏障</span><span class="sxs-lookup"><span data-stu-id="66b96-290">Information barriers</span></span>

<span data-ttu-id="66b96-291">信息障碍是管理员可以配置的用于阻止个人或组相互通信的策略。</span><span class="sxs-lookup"><span data-stu-id="66b96-291">Information barriers are policies that an admin can configure to prevent individuals or groups from communicating with each other.</span></span> <span data-ttu-id="66b96-292">例如，如果一个部门处理的信息不应与其他部门共享，或者必须阻止某个组与外部联系人通信，则这将非常有用。</span><span class="sxs-lookup"><span data-stu-id="66b96-292">This is useful if, for example, one department is handling information that shouldn't be shared with other departments, or a group needs to be prevented from communicating with outside contacts.</span></span> <span data-ttu-id="66b96-293">信息屏障策略也阻止了查找和发现。</span><span class="sxs-lookup"><span data-stu-id="66b96-293">Information barrier policies also prevent lookups and discovery.</span></span> <span data-ttu-id="66b96-294">这意味着，如果您尝试与不应与之通信的人员进行通信，则不会在人员选取器中找到该用户。</span><span class="sxs-lookup"><span data-stu-id="66b96-294">This means that if you attempt to communicate with someone you should not be communicating with, you won't find that user in the people picker.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="66b96-295">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="66b96-295">Which users benefit from the service?</span></span>

<span data-ttu-id="66b96-296">许可用户的 Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 合规性和 Office 365 高级合规性可以从信息障碍中受益。</span><span class="sxs-lookup"><span data-stu-id="66b96-296">Licensed users of Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, and Office 365 Advanced Compliance can benefit from information barriers.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="66b96-297">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="66b96-297">How do users benefit from the service?</span></span>

<span data-ttu-id="66b96-298">当限制用户与其他人通信时，他们将受益于信息障碍的高级合规性功能。</span><span class="sxs-lookup"><span data-stu-id="66b96-298">Users benefit from the advanced compliance capabilities of information barriers when they're restricted from communicating with others.</span></span> <span data-ttu-id="66b96-299">例如：</span><span class="sxs-lookup"><span data-stu-id="66b96-299">For example:</span></span>

| <span data-ttu-id="66b96-300">应用场景</span><span class="sxs-lookup"><span data-stu-id="66b96-300">Scenario</span></span>                                                                                                                                                                                                              | <span data-ttu-id="66b96-301">需要许可证的是谁？</span><span class="sxs-lookup"><span data-stu-id="66b96-301">Who requires a license?</span></span> |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| <span data-ttu-id="66b96-302">两组（组1和组2）无法相互通信（即，限制组1用户与组2用户通信，而组2用户限制与组1用户通信。</span><span class="sxs-lookup"><span data-stu-id="66b96-302">Two groups (Group 1 and Group 2) cannot communicate with each other (that is, Group 1 users are restricted from communicating with Group 2 users, and Group 2 users are restricted from communicating with Group 1 users.</span></span> | <span data-ttu-id="66b96-303">组1和组2中的用户</span><span class="sxs-lookup"><span data-stu-id="66b96-303">Users in both Group 1 and Group 2</span></span>                    |
| <span data-ttu-id="66b96-304">限制组1中的用户与公司的其余用户通信。</span><span class="sxs-lookup"><span data-stu-id="66b96-304">Users in Group 1 are restricted from communicating with the rest of the company.</span></span>                                                                                                                                       | <span data-ttu-id="66b96-305">仅限组1中的用户</span><span class="sxs-lookup"><span data-stu-id="66b96-305">Users in Group 1 only</span></span>                                |
| <span data-ttu-id="66b96-306">公司的其余部分受到限制，无法与组1通信。</span><span class="sxs-lookup"><span data-stu-id="66b96-306">The rest of the company is restricted from communicating with Group 1.</span></span>                                                                                                                                                 | <span data-ttu-id="66b96-307">除组1中的用户之外的所有用户</span><span class="sxs-lookup"><span data-stu-id="66b96-307">All users except those in Group 1</span></span>                    |
| <span data-ttu-id="66b96-308">限制组1用户与组2用户通信，但组2用户可以与组1用户进行通信。</span><span class="sxs-lookup"><span data-stu-id="66b96-308">Group 1 users are restricted from communicating with Group 2 users, but Group 2 users can communicate with Group 1 users.</span></span>                                                                                              | <span data-ttu-id="66b96-309">仅限组1中的用户</span><span class="sxs-lookup"><span data-stu-id="66b96-309">Users in Group 1 only</span></span>                                |

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="66b96-310">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="66b96-310">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="66b96-311">管理员在安全 & 合规中心中使用 PowerShell cmdlet 创建和管理信息障碍策略。</span><span class="sxs-lookup"><span data-stu-id="66b96-311">Admins create and manage information barrier policies by using PowerShell cmdlets in the Security & Compliance Center.</span></span> <span data-ttu-id="66b96-312">必须为管理员分配 Microsoft 365 企业全局管理员、Office 365 全局管理员或合规性管理员角色，以创建信息障碍策略。</span><span class="sxs-lookup"><span data-stu-id="66b96-312">Admins must be assigned the Microsoft 365 Enterprise Global Administrator, Office 365 Global Administrator, or Compliance Administrator role to create an information barrier policy.</span></span> <span data-ttu-id="66b96-313">默认情况下，这些策略适用于租户中的所有用户。</span><span class="sxs-lookup"><span data-stu-id="66b96-313">By default, these policies apply to all users in the tenant.</span></span> <span data-ttu-id="66b96-314">有关信息障碍的详细信息，请参阅[Microsoft 团队中的信息障碍](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)。</span><span class="sxs-lookup"><span data-stu-id="66b96-314">For more information about information barriers, see [Information barriers in Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams).</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="66b96-315">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="66b96-315">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="66b96-316">管理员可以在 Office 365 安全 & 合规中心中自定义位置（工作负荷）、包含的用户以及排除的用户。</span><span class="sxs-lookup"><span data-stu-id="66b96-316">Admins can customize locations (workloads), included users, and excluded users in the Office 365 Security & Compliance Center.</span></span> <span data-ttu-id="66b96-317">例如，如果所有用户均为 Office 365 E3 许可，并且没有许可 Office 365 高级合规性/E5，则无需为组织创建任何信息障碍策略。</span><span class="sxs-lookup"><span data-stu-id="66b96-317">For example, if all users are licensed for Office 365 E3, and none are licensed for Office 365 Advanced Compliance/E5, they wouldn't need to create any information barrier policies for the organization.</span></span> <span data-ttu-id="66b96-318">有关详细信息，请参阅[Microsoft 团队中的信息障碍](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)。</span><span class="sxs-lookup"><span data-stu-id="66b96-318">For more information, see [Information barriers in Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams).</span></span>

## <a name="office-365-message-encryption"></a><span data-ttu-id="66b96-319">Office 365 邮件加密</span><span class="sxs-lookup"><span data-stu-id="66b96-319">Office 365 Message Encryption</span></span>

<span data-ttu-id="66b96-p137">Office 365 邮件加密 (OME) 是一项基于 Azure 权限管理 (Azure RMS) 构建的服务，允许您向组织内外发送经加密的电子邮件，而无需考虑目标电子邮件地址（Gmail、Yahoo!Mail、Outlook.com 等）。</span><span class="sxs-lookup"><span data-stu-id="66b96-p137">Office 365 Message Encryption (OME) is a service built on Azure Rights Management (Azure RMS) that lets you send encrypted email to people inside or outside your organization, regardless of the destination email address (Gmail, Yahoo! Mail, Outlook.com, etc.).</span></span>

<span data-ttu-id="66b96-322">若要查看加密邮件，收件人可以使用一次性密码、通过 Microsoft 帐户登录或使用与 Office 365 关联的工作或学校帐户登录。</span><span class="sxs-lookup"><span data-stu-id="66b96-322">To view encrypted messages, recipients can either get a one-time passcode, sign in with a Microsoft account, or sign in with a work or school account associated with Office 365.</span></span> <span data-ttu-id="66b96-323">此外，收件人也可发送加密回复。</span><span class="sxs-lookup"><span data-stu-id="66b96-323">Recipients can also send encrypted replies.</span></span> <span data-ttu-id="66b96-324">他们不需要 Office 365 订阅即可查看加密邮件或发送加密答复。</span><span class="sxs-lookup"><span data-stu-id="66b96-324">They don't need an Office 365 subscription to view encrypted messages or send encrypted replies.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="66b96-325">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="66b96-325">Which users benefit from the service?</span></span>

<span data-ttu-id="66b96-326">Office 365 E3/A3/G3、Microsoft 365 E3/A3/G3 和 Azure 信息保护计划1的许可用户可受益于 Office 365 邮件加密。</span><span class="sxs-lookup"><span data-stu-id="66b96-326">Licensed users of Office 365 E3/A3/G3, Microsoft 365 E3/A3/G3, and Azure Information Protection Plan 1 can benefit from Office 365 Message Encryption.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="66b96-327">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="66b96-327">How do users benefit from the service?</span></span>

<span data-ttu-id="66b96-328">邮件发件人可受益于对 Office 365 邮件加密提供的敏感电子邮件的新增控制。</span><span class="sxs-lookup"><span data-stu-id="66b96-328">Message senders benefit from the added control over sensitive emails provided by Office 365 Message Encryption.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="66b96-329">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="66b96-329">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="66b96-330">管理员在 "**邮件流** > **规则**" 下的 Exchange 管理中心中创建和管理 Office 365 邮件加密策略。</span><span class="sxs-lookup"><span data-stu-id="66b96-330">Admins create and manage Office 365 Message Encryption policies in the Exchange admin center under **Mail flow** > **Rules**.</span></span> <span data-ttu-id="66b96-331">默认情况下，这些规则适用于租户中的所有用户。</span><span class="sxs-lookup"><span data-stu-id="66b96-331">By default, these rules apply to all users in the tenant.</span></span> <span data-ttu-id="66b96-332">有关设置新的 Office 365 邮件加密功能的详细信息，请参阅[设置新的 office 365 邮件加密功能](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)。</span><span class="sxs-lookup"><span data-stu-id="66b96-332">For more information about setting up new Office 365 Message Encryption capabilities, see [Set up new Office 365 Message Encryption capabilities](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities).</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="66b96-333">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="66b96-333">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="66b96-334">管理员应将仅限 Office 365 邮件加密的邮件流规则应用于许可用户。</span><span class="sxs-lookup"><span data-stu-id="66b96-334">Admins should apply mail flow rules for Office 365 Message Encryption only to licensed users.</span></span> <span data-ttu-id="66b96-335">有关定义邮件流规则的详细信息，请参阅[在 Office 365 中定义用于加密电子邮件的邮件流规则](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)。</span><span class="sxs-lookup"><span data-stu-id="66b96-335">For more information about defining mail flow rules, see [Define mail flow rules to encrypt email messages in Office 365](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).</span></span>


## <a name="office-365-advanced-message-encryption"></a><span data-ttu-id="66b96-336">Office 365 高级邮件加密</span><span class="sxs-lookup"><span data-stu-id="66b96-336">Office 365 Advanced Message Encryption</span></span>

<span data-ttu-id="66b96-337">高级邮件加密帮助客户满足法规遵从性义务，这些要求对外部收件人和对加密电子邮件的访问权限要求更灵活的控制。</span><span class="sxs-lookup"><span data-stu-id="66b96-337">Advanced Message Encryption helps customers meet compliance obligations that require more flexible controls over external recipients and their access to encrypted emails.</span></span> <span data-ttu-id="66b96-338">通过高级邮件加密，管理员可以通过使用可检测敏感信息类型（例如，个人标识信息或财务或运行状况 Id）的自动策略来控制在组织外共享的敏感电子邮件，或者它们可以通过应用自定义电子邮件模板，并通过安全 web 门户终止对加密电子邮件的访问，从而使用关键字增强保护。</span><span class="sxs-lookup"><span data-stu-id="66b96-338">With Advanced Message Encryption, admins can control sensitive emails shared outside the organization by using automatic policies that can detect sensitive information types (for example, personally identifying information, or financial or health IDs), or they can use keywords to enhance protection by applying custom email templates and expiring access to encrypted emails through a secure web portal.</span></span> <span data-ttu-id="66b96-339">此外，管理员可以随时撤销访问权限，从而进一步控制通过安全 web 门户外部访问的加密电子邮件。</span><span class="sxs-lookup"><span data-stu-id="66b96-339">Additionally, admins can further control encrypted emails accessed externally through a secure web portal by revoking access at any time.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="66b96-340">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="66b96-340">Which users benefit from the service?</span></span>

<span data-ttu-id="66b96-341">许可用户的 Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 合规性和 Office 365 高级合规性可以从高级邮件加密中受益。</span><span class="sxs-lookup"><span data-stu-id="66b96-341">Licensed users of Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, and Office 365 Advanced Compliance can benefit from Advanced Message Encryption.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="66b96-342">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="66b96-342">How do users benefit from the service?</span></span>

<span data-ttu-id="66b96-343">邮件发件人可受益于对高级邮件加密提供的敏感电子邮件所添加的控制。</span><span class="sxs-lookup"><span data-stu-id="66b96-343">Message senders benefit from the added control over sensitive emails provided by Advanced Message Encryption.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="66b96-344">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="66b96-344">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="66b96-345">管理员在 "邮件流规则" 下的 Exchange 管理中心中创建和管理高级邮件加密策略。</span><span class="sxs-lookup"><span data-stu-id="66b96-345">Admins create and manage Advanced Message Encryption policies in the Exchange admin center under mail flow rules.</span></span> <span data-ttu-id="66b96-346">默认情况下，这些规则适用于租户上的所有用户。</span><span class="sxs-lookup"><span data-stu-id="66b96-346">By default, these rules apply to all users on the tenant.</span></span> <span data-ttu-id="66b96-347">有关设置新的邮件加密功能的详细信息，请参阅[设置新的 Office 365 邮件加密功能](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)。</span><span class="sxs-lookup"><span data-stu-id="66b96-347">For more information about setting up new Message Encryption capabilities, see [Set up new Office 365 Message Encryption capabilities](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities).</span></span>

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="66b96-348">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="66b96-348">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="66b96-349">管理员应将邮件流规则仅应用于已授权用户的高级邮件加密。</span><span class="sxs-lookup"><span data-stu-id="66b96-349">Admins should apply mail flow rules for Advanced Message Encryption only to licensed users.</span></span> <span data-ttu-id="66b96-350">有关定义邮件流规则的详细信息，请参阅[在 Office 365 中定义用于加密电子邮件的邮件流规则](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)。</span><span class="sxs-lookup"><span data-stu-id="66b96-350">For more information about defining mail flow rules, see [Define mail flow rules to encrypt email messages in Office 365](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).</span></span>

## <a name="supervision-policies"></a><span data-ttu-id="66b96-351">监督策略</span><span class="sxs-lookup"><span data-stu-id="66b96-351">Supervision policies</span></span>

<span data-ttu-id="66b96-352">Office 365 中的监督策略使您可以捕获指定审阅者进行检查的员工通信。</span><span class="sxs-lookup"><span data-stu-id="66b96-352">Supervision policies in Office 365 allow you to capture employee communications for examination by designated reviewers.</span></span> <span data-ttu-id="66b96-353">您可以定义用于捕获组织中的内部和外部电子邮件、Microsoft 团队或第三方通信的特定策略。</span><span class="sxs-lookup"><span data-stu-id="66b96-353">You can define specific policies that capture internal and external email, Microsoft Teams, or third-party communications in your organization.</span></span> <span data-ttu-id="66b96-354">然后，审阅者可以检查这些邮件，以确保它们符合组织的邮件标准，并使用分类类型解决这些问题。</span><span class="sxs-lookup"><span data-stu-id="66b96-354">Reviewers can then examine the messages to make sure that they are compliant with your organization's message standards and resolve them with classification type.</span></span>

### <a name="which-users-benefit-from-the-service"></a><span data-ttu-id="66b96-355">哪些用户从服务中受益？</span><span class="sxs-lookup"><span data-stu-id="66b96-355">Which users benefit from the service?</span></span>

<span data-ttu-id="66b96-356">许可用户的 Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 合规性和 Office 365 高级合规性可以从监督策略中受益。</span><span class="sxs-lookup"><span data-stu-id="66b96-356">Licensed users of Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, and Office 365 Advanced Compliance can benefit from supervision policies.</span></span>

### <a name="how-do-users-benefit-from-the-service"></a><span data-ttu-id="66b96-357">用户如何从服务中获益？</span><span class="sxs-lookup"><span data-stu-id="66b96-357">How do users benefit from the service?</span></span>

<span data-ttu-id="66b96-358">用户通过监督策略监视其通信，从而从服务中获益。</span><span class="sxs-lookup"><span data-stu-id="66b96-358">Users benefit from the service by having their communications monitored by supervision policies.</span></span>

### <a name="how-is-the-service-provisioneddeployed"></a><span data-ttu-id="66b96-359">服务是如何设置/部署的？</span><span class="sxs-lookup"><span data-stu-id="66b96-359">How is the service provisioned/deployed?</span></span>

<span data-ttu-id="66b96-360">管理员在安全 & 合规中心中创建监督策略。</span><span class="sxs-lookup"><span data-stu-id="66b96-360">Admins create supervision policies in the Security & Compliance Center.</span></span> <span data-ttu-id="66b96-361">这些策略定义哪些通信和用户将在组织中进行审阅，定义通信必须满足的自定义条件，并指定应执行审阅的用户。</span><span class="sxs-lookup"><span data-stu-id="66b96-361">These policies define which communications and users are subject to review in the organization, define custom conditions that the communications must meet, and specify who should perform reviews.</span></span>
 
### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a><span data-ttu-id="66b96-362">如何将服务仅应用于受该服务授权的租户中的用户？</span><span class="sxs-lookup"><span data-stu-id="66b96-362">How can the service be applied only to users in the tenant who are licensed for the service?</span></span>

<span data-ttu-id="66b96-363">管理员选择要包含在监督策略中的特定用户或组。</span><span class="sxs-lookup"><span data-stu-id="66b96-363">Admins choose specific users or groups to include in a supervision policy.</span></span> <span data-ttu-id="66b96-364">在选择组时，他们还可以选择组中要从监督策略中排除的特定用户。</span><span class="sxs-lookup"><span data-stu-id="66b96-364">When choosing a group, they can also select specific users in the group to exclude from the supervision policy.</span></span> <span data-ttu-id="66b96-365">有关监督策略的详细信息，请参阅[Office 365 中的监察策略](https://docs.microsoft.com/office365/SecurityCompliance/supervision-policies)。</span><span class="sxs-lookup"><span data-stu-id="66b96-365">For more information about supervision polices, see [Supervision policies in Office 365](https://docs.microsoft.com/office365/SecurityCompliance/supervision-policies).</span></span>
