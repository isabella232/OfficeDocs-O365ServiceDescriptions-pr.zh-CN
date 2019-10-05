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
description: Microsoft Office 365 高级威胁防护（ATP）是一项基于云的电子邮件筛选服务，通过提供强大的零天保护功能，帮助您的组织抵御未知恶意软件和病毒，并提供保护实时来自有害链接的组织。 ATP 具有丰富的报告功能和 URL 跟踪功能，可让管理员了解组织中发生的攻击种类。
ms.openlocfilehash: ffb08bc3104e1c41ebf6441a68fd3d22b367f5c4
ms.sourcegitcommit: 3976036fdf009ec5f6424495251c830c0b379b6a
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/05/2019
ms.locfileid: "37401738"
---
# <a name="office-365-advanced-threat-protection-service-description"></a><span data-ttu-id="3d5bd-104">Office 365 高级威胁防护服务说明</span><span class="sxs-lookup"><span data-stu-id="3d5bd-104">Office 365 Advanced Threat Protection Service Description</span></span>

<span data-ttu-id="3d5bd-105">Microsoft Office 365 高级威胁防护（ATP）是一项基于云的电子邮件筛选服务，通过提供强大的零天保护功能，帮助您的组织抵御未知恶意软件和病毒，并提供保护实时来自有害链接的组织。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-105">Microsoft Office 365 Advanced Threat Protection (ATP) is a cloud-based email filtering service that helps protect your organization against unknown malware and viruses by providing robust zero-day protection, and includes features to safeguard your organization from harmful links in real time.</span></span> <span data-ttu-id="3d5bd-106">ATP 具有丰富的报告功能和 URL 跟踪功能，可让管理员了解组织中发生的攻击种类。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-106">ATP has rich reporting and URL trace capabilities that give administrators insight into the kind of attacks happening in your organization.</span></span>

<span data-ttu-id="3d5bd-107">以下是您可以使用 ATP 进行邮件保护的主要方式：</span><span class="sxs-lookup"><span data-stu-id="3d5bd-107">The following are the primary ways you can use ATP for message protection:</span></span>

- <span data-ttu-id="3d5bd-108">在 Office 365 ATP 仅筛选方案中，ATP 为本地 Exchange Server 环境或任何其他本地 SMTP 电子邮件解决方案提供基于云的电子邮件保护。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-108">In an Office 365 ATP filtering-only scenario, ATP provides cloud-based email protection for your on-premises Exchange Server environment or any other on-premises SMTP email solution.</span></span>

- <span data-ttu-id="3d5bd-109">可以启用 Office 365 ATP 来保护 Exchange Online 云托管的邮箱。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-109">Office 365 ATP can be enabled to protect Exchange Online cloud-hosted mailboxes.</span></span> <span data-ttu-id="3d5bd-110">若要了解有关 Exchange Online 的详细信息，请参阅 [Exchange Online 服务说明](exchange-online-service-description/exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-110">To learn more about Exchange Online, see the [Exchange Online Service Description](exchange-online-service-description/exchange-online-service-description.md).</span></span>

- <span data-ttu-id="3d5bd-111">在混合部署中，如果您将本地和云邮箱与入站电子邮件筛选的 Exchange Online 保护结合在一起，则可以将 ATP 配置为保护您的邮件环境并控制邮件路由。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-111">In a hybrid deployment, ATP can be configured to protect your messaging environment and control mail routing when you have a mix of on-premises and cloud mailboxes with Exchange Online Protection for inbound email filtering.</span></span>

## <a name="office-365-advanced-threat-protection-atp-availability"></a><span data-ttu-id="3d5bd-112">Office 365 高级威胁防护（ATP）可用性</span><span class="sxs-lookup"><span data-stu-id="3d5bd-112">Office 365 Advanced Threat Protection (ATP) availability</span></span>

<span data-ttu-id="3d5bd-113">ATP 包含在 Office 365 企业版 E5、Office 365 教育版 A5 和 Microsoft 365 商业版中。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-113">ATP is included in Office 365 Enterprise E5, Office 365 Education A5, and Microsoft 365 Business.</span></span>

<span data-ttu-id="3d5bd-114">可以将 ATP 添加到以下 Exchange 和 Office 365 订阅计划中：</span><span class="sxs-lookup"><span data-stu-id="3d5bd-114">You can add ATP to the following Exchange and Office 365 subscription plans:</span></span>

- <span data-ttu-id="3d5bd-115">Exchange Online 计划 1</span><span class="sxs-lookup"><span data-stu-id="3d5bd-115">Exchange Online Plan 1</span></span>

- <span data-ttu-id="3d5bd-116">Exchange Online 计划 2</span><span class="sxs-lookup"><span data-stu-id="3d5bd-116">Exchange Online Plan 2</span></span>

- <span data-ttu-id="3d5bd-117">Exchange Online Kiosk</span><span class="sxs-lookup"><span data-stu-id="3d5bd-117">Exchange Online Kiosk</span></span>

- <span data-ttu-id="3d5bd-118">Exchange Online Protection</span><span class="sxs-lookup"><span data-stu-id="3d5bd-118">Exchange Online Protection</span></span>

- <span data-ttu-id="3d5bd-119">Office 365 商业协作版</span><span class="sxs-lookup"><span data-stu-id="3d5bd-119">Office 365 Business Essentials</span></span>

- <span data-ttu-id="3d5bd-120">Office 365 商业高级版</span><span class="sxs-lookup"><span data-stu-id="3d5bd-120">Office 365 Business Premium</span></span>

- <span data-ttu-id="3d5bd-121">Office 365 企业版 E1</span><span class="sxs-lookup"><span data-stu-id="3d5bd-121">Office 365 Enterprise E1</span></span>

- <span data-ttu-id="3d5bd-122">Office 365 企业版 E3</span><span class="sxs-lookup"><span data-stu-id="3d5bd-122">Office 365 Enterprise E3</span></span>

- <span data-ttu-id="3d5bd-123">Office 365 企业版 F1</span><span class="sxs-lookup"><span data-stu-id="3d5bd-123">Office 365 Enterprise F1</span></span>

- <span data-ttu-id="3d5bd-124">Office 365 A1</span><span class="sxs-lookup"><span data-stu-id="3d5bd-124">Office 365 A1</span></span>

- <span data-ttu-id="3d5bd-125">Office 365 A3</span><span class="sxs-lookup"><span data-stu-id="3d5bd-125">Office 365 A3</span></span>

<span data-ttu-id="3d5bd-126">若要购买 Office 365 高级威胁防护，请参阅[office 365 高级威胁防护](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-126">To buy Office 365 Advanced Threat Protection, see [Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).</span></span>

<span data-ttu-id="3d5bd-127">若要跨计划比较功能，请参阅[比较 Office 365 For Business 计划](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409)和[发现适合你的 Microsoft 365 企业解决方案](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans)。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-127">To compare features across plans, see [Compare Office 365 for Business plans](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) and [Discover the Microsoft 365 Enterprise solution that's right for you](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans).</span></span>

## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a><span data-ttu-id="3d5bd-128">Office 365 高级威胁防护（ATP）的新增功能</span><span class="sxs-lookup"><span data-stu-id="3d5bd-128">What's new in Office 365 Advanced Threat Protection (ATP)</span></span>

<span data-ttu-id="3d5bd-129">我们正在继续向 Office 365 ATP 添加新功能。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-129">We are continuing to add new features to Office 365 ATP.</span></span> <span data-ttu-id="3d5bd-130">若要了解有关即将 ATP （或常规 Microsoft 365）的新功能的详细信息，请参阅以下资源：</span><span class="sxs-lookup"><span data-stu-id="3d5bd-130">To learn more about new features coming to ATP (or Microsoft 365 in general), see the following resources:</span></span>
- [<span data-ttu-id="3d5bd-131">Microsoft 365 路线图</span><span class="sxs-lookup"><span data-stu-id="3d5bd-131">Microsoft 365 Roadmap</span></span>](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)
- [<span data-ttu-id="3d5bd-132">Office 365 ATP 中的新增功能</span><span class="sxs-lookup"><span data-stu-id="3d5bd-132">What's new in Office 365 ATP</span></span>](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a><span data-ttu-id="3d5bd-133">Office 365 高级威胁防护（ATP）的要求</span><span class="sxs-lookup"><span data-stu-id="3d5bd-133">Requirements for Office 365 Advanced Threat Protection (ATP)</span></span>

<span data-ttu-id="3d5bd-134">ATP 可以与任何 SMTP 邮件传输代理（如 Microsoft Exchange Server）一起使用。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-134">ATP can be used with any SMTP mail transfer agent, such as Microsoft Exchange Server.</span></span> <span data-ttu-id="3d5bd-135">若要了解 ATP 支持的操作系统、Web 浏览器和语言，请参阅 [Exchange Online Protection 中的 Exchange 管理中心](https://go.microsoft.com/fwlink/p/?LinkId=282381)的"支持的浏览器"和"支持的语言"部分。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-135">For information about the operating systems, web browsers, and languages that are supported by ATP, see the "Supported browsers" and "Supported languages" sections in [Exchange Admin Center in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).</span></span>

## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a><span data-ttu-id="3d5bd-136">跨高级威胁防护（ATP）计划的功能可用性</span><span class="sxs-lookup"><span data-stu-id="3d5bd-136">Feature availability across Advanced Threat Protection (ATP) plans</span></span>

<span data-ttu-id="3d5bd-p106">下面列出了每个功能。当提到 Exchange Online 时，通常指的是 Office 365 企业版服务系列。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-p106">Each feature is listed below. When Exchange Online is mentioned, it typically refers to the Office 365 Enterprise service family.</span></span>

|<span data-ttu-id="3d5bd-139">**功能**</span><span class="sxs-lookup"><span data-stu-id="3d5bd-139">**Feature**</span></span>|<span data-ttu-id="3d5bd-140">**ATP 计划1**</span><span class="sxs-lookup"><span data-stu-id="3d5bd-140">**ATP Plan 1**</span></span><br><span data-ttu-id="3d5bd-141">（以前的 ATP 独立）</span><span class="sxs-lookup"><span data-stu-id="3d5bd-141">(formerly ATP standalone)</span></span>|<span data-ttu-id="3d5bd-142">**ATP 计划2**</span><span class="sxs-lookup"><span data-stu-id="3d5bd-142">**ATP Plan 2**</span></span><br><span data-ttu-id="3d5bd-143">（以前称为威胁智能</span><span class="sxs-lookup"><span data-stu-id="3d5bd-143">(formerly Threat Intelligence</span></span> <br><span data-ttu-id="3d5bd-144">独立主机</span><span class="sxs-lookup"><span data-stu-id="3d5bd-144">standalone)</span></span>| <span data-ttu-id="3d5bd-145">Office 365 企业版 E5</span><span class="sxs-lookup"><span data-stu-id="3d5bd-145">Office 365 Enterprise E5</span></span>|
|:-----|:-----|:-----|:-----|
|<span data-ttu-id="3d5bd-146">*配置、保护和检测*</span><span class="sxs-lookup"><span data-stu-id="3d5bd-146">*Configuration, Protection, and Detection*</span></span>|
|<span data-ttu-id="3d5bd-147">安全附件</span><span class="sxs-lookup"><span data-stu-id="3d5bd-147">Safe Attachments</span></span>|<span data-ttu-id="3d5bd-148">是</span><span class="sxs-lookup"><span data-stu-id="3d5bd-148">Yes</span></span>|<span data-ttu-id="3d5bd-149">是</span><span class="sxs-lookup"><span data-stu-id="3d5bd-149">Yes</span></span>|<span data-ttu-id="3d5bd-150">是</span><span class="sxs-lookup"><span data-stu-id="3d5bd-150">Yes</span></span>|
|<span data-ttu-id="3d5bd-151">安全链接</span><span class="sxs-lookup"><span data-stu-id="3d5bd-151">Safe Links</span></span>|<span data-ttu-id="3d5bd-152">是</span><span class="sxs-lookup"><span data-stu-id="3d5bd-152">Yes</span></span>|<span data-ttu-id="3d5bd-153">是</span><span class="sxs-lookup"><span data-stu-id="3d5bd-153">Yes</span></span>|<span data-ttu-id="3d5bd-154">是</span><span class="sxs-lookup"><span data-stu-id="3d5bd-154">Yes</span></span>|
|<span data-ttu-id="3d5bd-155">反网络钓鱼策略</span><span class="sxs-lookup"><span data-stu-id="3d5bd-155">Anti-Phishing Policies</span></span>|<span data-ttu-id="3d5bd-156">是</span><span class="sxs-lookup"><span data-stu-id="3d5bd-156">Yes</span></span>|<span data-ttu-id="3d5bd-157">是</span><span class="sxs-lookup"><span data-stu-id="3d5bd-157">Yes</span></span>|<span data-ttu-id="3d5bd-158">是</span><span class="sxs-lookup"><span data-stu-id="3d5bd-158">Yes</span></span>|
|<span data-ttu-id="3d5bd-159">SharePoint、OneDrive 和 Microsoft 团队的 ATP</span><span class="sxs-lookup"><span data-stu-id="3d5bd-159">ATP for SharePoint, OneDrive and Microsoft Teams</span></span>|<span data-ttu-id="3d5bd-160">是</span><span class="sxs-lookup"><span data-stu-id="3d5bd-160">Yes</span></span>|<span data-ttu-id="3d5bd-161">是</span><span class="sxs-lookup"><span data-stu-id="3d5bd-161">Yes</span></span>|<span data-ttu-id="3d5bd-162">是</span><span class="sxs-lookup"><span data-stu-id="3d5bd-162">Yes</span></span>|
|<span data-ttu-id="3d5bd-163">团队中的安全附件</span><span class="sxs-lookup"><span data-stu-id="3d5bd-163">Safe Attachments in Teams</span></span>|<span data-ttu-id="3d5bd-164">是</span><span class="sxs-lookup"><span data-stu-id="3d5bd-164">Yes</span></span>|<span data-ttu-id="3d5bd-165">是</span><span class="sxs-lookup"><span data-stu-id="3d5bd-165">Yes</span></span>|<span data-ttu-id="3d5bd-166">是</span><span class="sxs-lookup"><span data-stu-id="3d5bd-166">Yes</span></span>|
|<span data-ttu-id="3d5bd-167">团队中的安全链接</span><span class="sxs-lookup"><span data-stu-id="3d5bd-167">Safe Links in Teams</span></span>|<span data-ttu-id="3d5bd-168">否</span><span class="sxs-lookup"><span data-stu-id="3d5bd-168">No</span></span>|<span data-ttu-id="3d5bd-169">否</span><span class="sxs-lookup"><span data-stu-id="3d5bd-169">No</span></span>|<span data-ttu-id="3d5bd-170">否</span><span class="sxs-lookup"><span data-stu-id="3d5bd-170">No</span></span>|
|<span data-ttu-id="3d5bd-171">实时报告</span><span class="sxs-lookup"><span data-stu-id="3d5bd-171">Real-time reports</span></span>|<span data-ttu-id="3d5bd-172">是</span><span class="sxs-lookup"><span data-stu-id="3d5bd-172">Yes</span></span>|<span data-ttu-id="3d5bd-173">是</span><span class="sxs-lookup"><span data-stu-id="3d5bd-173">Yes</span></span>|<span data-ttu-id="3d5bd-174">是</span><span class="sxs-lookup"><span data-stu-id="3d5bd-174">Yes</span></span>|
|<span data-ttu-id="3d5bd-175">*自动化、调查、修正和教育*</span><span class="sxs-lookup"><span data-stu-id="3d5bd-175">*Automation, Investigation, Remediation and Education*</span></span>|
|<span data-ttu-id="3d5bd-176">威胁跟踪器</span><span class="sxs-lookup"><span data-stu-id="3d5bd-176">Threat Trackers</span></span>|<span data-ttu-id="3d5bd-177">否</span><span class="sxs-lookup"><span data-stu-id="3d5bd-177">No</span></span>|<span data-ttu-id="3d5bd-178">可访问</span><span class="sxs-lookup"><span data-stu-id="3d5bd-178">Yes</span></span>|<span data-ttu-id="3d5bd-179">是</span><span class="sxs-lookup"><span data-stu-id="3d5bd-179">Yes</span></span>|
|<span data-ttu-id="3d5bd-180">资源管理器（高级威胁调查）</span><span class="sxs-lookup"><span data-stu-id="3d5bd-180">Explorer (advanced threat investigation)</span></span>|<span data-ttu-id="3d5bd-181">否</span><span class="sxs-lookup"><span data-stu-id="3d5bd-181">No</span></span>|<span data-ttu-id="3d5bd-182">可访问</span><span class="sxs-lookup"><span data-stu-id="3d5bd-182">Yes</span></span>|<span data-ttu-id="3d5bd-183">是</span><span class="sxs-lookup"><span data-stu-id="3d5bd-183">Yes</span></span>|
|<span data-ttu-id="3d5bd-184">自动化事件响应</span><span class="sxs-lookup"><span data-stu-id="3d5bd-184">Automated incident response</span></span>|<span data-ttu-id="3d5bd-185">否</span><span class="sxs-lookup"><span data-stu-id="3d5bd-185">No</span></span>|<span data-ttu-id="3d5bd-186">可访问</span><span class="sxs-lookup"><span data-stu-id="3d5bd-186">Yes</span></span>|<span data-ttu-id="3d5bd-187">是</span><span class="sxs-lookup"><span data-stu-id="3d5bd-187">Yes</span></span>|
|<span data-ttu-id="3d5bd-188">攻击模拟器</span><span class="sxs-lookup"><span data-stu-id="3d5bd-188">Attack Simulator</span></span>|<span data-ttu-id="3d5bd-189">否</span><span class="sxs-lookup"><span data-stu-id="3d5bd-189">No</span></span>|<span data-ttu-id="3d5bd-190">可访问</span><span class="sxs-lookup"><span data-stu-id="3d5bd-190">Yes</span></span>|<span data-ttu-id="3d5bd-191">是</span><span class="sxs-lookup"><span data-stu-id="3d5bd-191">Yes</span></span>|

## <a name="advanced-threat-protection-atp-capabilities"></a><span data-ttu-id="3d5bd-192">高级威胁防护（ATP）功能</span><span class="sxs-lookup"><span data-stu-id="3d5bd-192">Advanced Threat Protection (ATP) Capabilities</span></span>

### <a name="safe-attachments"></a><span data-ttu-id="3d5bd-193">安全附件</span><span class="sxs-lookup"><span data-stu-id="3d5bd-193">Safe Attachments</span></span>

<span data-ttu-id="3d5bd-194">[ATP 安全附件](https://docs.microsoft.com/office365/securitycompliance/atp-safe-attachments)针对未知恶意软件和病毒提供保护，并提供为期零天的保护，以保护您的邮件系统。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-194">[ATP Safe Attachments](https://docs.microsoft.com/office365/securitycompliance/atp-safe-attachments) protects against unknown malware and viruses, and provides zero-day protection to safeguard your messaging system.</span></span> <span data-ttu-id="3d5bd-195">所有不带有已知的病毒/恶意软件签名的邮件和附件都被路由到一个特殊的环境中，ATP 将在其中使用多种机器学习和分析技术来检测恶意企图。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-195">All messages and attachments that don't have a known virus/malware signature are routed to a special environment where ATP uses a variety of machine learning and analysis techniques to detect malicious intent.</span></span> <span data-ttu-id="3d5bd-196">如果没有检测到可疑的活动，会发布邮件并传递到邮箱中。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-196">If no suspicious activity is detected, the message is released for delivery to the mailbox.</span></span>

> [!NOTE]
> <span data-ttu-id="3d5bd-197">ATP 安全附件扫描发生在 Office 365 数据所在的同一个区域中。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-197">ATP Safe Attachments scanning takes place in the same region where your Office 365 data resides.</span></span> <span data-ttu-id="3d5bd-198">有关数据中心地理位置的详细信息，请参阅[您的数据位于何处？](https://products.office.com/where-is-your-data-located?geo=All)</span><span class="sxs-lookup"><span data-stu-id="3d5bd-198">For more information about data center geography, see [Where is your data located?](https://products.office.com/where-is-your-data-located?geo=All)</span></span>

### <a name="safe-links"></a><span data-ttu-id="3d5bd-199">安全链接</span><span class="sxs-lookup"><span data-stu-id="3d5bd-199">Safe Links</span></span>

<span data-ttu-id="3d5bd-200">[ATP 安全链接](https://docs.microsoft.com/Office365/SecurityCompliance/atp-safe-links)功能主动保护您的用户免受邮件中或 Office 文档中的恶意 url 的攻击。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-200">The [ATP Safe Links](https://docs.microsoft.com/Office365/SecurityCompliance/atp-safe-links) feature proactively protects your users from malicious URLs in a message or in an Office document.</span></span> <span data-ttu-id="3d5bd-201">每次单击链接时，将继续提供保护，因为会在访问良好的链接时动态地阻挡恶意链接。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-201">The protection remains every time they click the link, as malicious links are dynamically blocked while good links can be accessed.</span></span>

<span data-ttu-id="3d5bd-202">安全链接可用于以下应用程序中的 Url：</span><span class="sxs-lookup"><span data-stu-id="3d5bd-202">Safe Links is available for URLs in the following apps:</span></span>

- <span data-ttu-id="3d5bd-203">Windows 或 Mac 上的 Office 365 专业增强版。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-203">Office 365 ProPlus on Windows or Mac.</span></span>

- <span data-ttu-id="3d5bd-204">Office for web （适用于 web 的 Word、适用于 web 的 Excel、PowerPoint for web 以及适用于 web 的 OneNote）。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-204">Office for the web (Word for the web, Excel for the web, PowerPoint for the web, and OneNote for the web).</span></span>

- <span data-ttu-id="3d5bd-205">Windows 上的 Word、Excel、PowerPoint 和 Visio，以及 iOS 和 Android 设备上的 Office 应用程序。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-205">Word, Excel, PowerPoint, and Visio on Windows, as well as Office apps on iOS and Android devices.</span></span>

> [!NOTE]
> <span data-ttu-id="3d5bd-206">用户必须获得 ATP<sup>\*</sup>许可，必须包含在 Atp 安全链接策略中，并且必须在其设备上登录，才能就地保护。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-206">Users must be licensed for ATP<sup>\*</sup>, must be included in ATP Safe Links policies, and must be signed in on their devices for protection to be in place.</span></span>

<span data-ttu-id="3d5bd-207"><sup>\*</sup>对于组织范围的 ATP 许可证（例如，ATP_ENTERPRISE_FACULTY），您无需向单个用户分配 ATP 许可证。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-207"><sup>\*</sup> For organization-wide ATP licenses (for example, ATP_ENTERPRISE_FACULTY), you don't need to assign ATP licenses to individual users.</span></span>

### <a name="anti-phishing-policies"></a><span data-ttu-id="3d5bd-208">反网络钓鱼策略</span><span class="sxs-lookup"><span data-stu-id="3d5bd-208">Anti-phishing policies</span></span>

<span data-ttu-id="3d5bd-209">[ATP 反网络钓鱼](https://docs.microsoft.com/office365/securitycompliance/atp-anti-phishing)检查传入的邮件，以指示邮件可能是网络钓鱼尝试。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-209">[ATP anti-phishing](https://docs.microsoft.com/office365/securitycompliance/atp-anti-phishing) checks incoming messages for indicators that a message might be a phishing attempt.</span></span> <span data-ttu-id="3d5bd-210">当 ATP 策略（安全附件、安全链接或反网络钓鱼）覆盖了用户时，将通过分析邮件的多个机器学习模型来评估传入的邮件，并根据配置的策略采取相应的操作。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-210">When users are covered by ATP policies (safe attachments, safe links or anti-phishing), incoming messages are evaluated by multiple machine learning models that analyze messages and the appropriate action is taken, based on the configured policies.</span></span>

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a><span data-ttu-id="3d5bd-211">适用于 SharePoint、OneDrive 和 Microsoft Teams 的 ATP</span><span class="sxs-lookup"><span data-stu-id="3d5bd-211">ATP for SharePoint, OneDrive, and Microsoft Teams</span></span>

<span data-ttu-id="3d5bd-212">[SharePoint、OneDrive 和 Microsoft 团队的 ATP](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams)可帮助检测和阻止在工作组网站和文档库中被标识为恶意的文件。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-212">[ATP for SharePoint, OneDrive, and Microsoft Teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams)  helps detect and block files that are identified as malicious in team sites and document libraries.</span></span>

### <a name="real-time-reports"></a><span data-ttu-id="3d5bd-213">实时报告</span><span class="sxs-lookup"><span data-stu-id="3d5bd-213">Real-time reports</span></span>

<span data-ttu-id="3d5bd-214">Office 365 安全 & 合规中心中提供的监视功能包括[实时报告和见解](https://docs.microsoft.com/office365/securitycompliance/view-reports-for-atp)，使您的安全和合规性管理员能够重点关注高优先级问题，如安全攻击或提高可疑活动。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-214">Monitoring capabilities available in the Office 365 Security & Compliance Center include [real-time reports and insights](https://docs.microsoft.com/office365/securitycompliance/view-reports-for-atp) that enable your security and compliance administrators to focus on high-priority issues, such as security attacks or increased suspicious activity.</span></span> <span data-ttu-id="3d5bd-215">除了突出显示问题区域之外，智能报告和见解还包括用于查看和浏览数据的建议和链接，同时还采取快速操作。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-215">In addition to highlighting problem areas, smart reports and insights include recommendations and links to view and explore data and also take quick actions.</span></span>

### <a name="threat-trackers"></a><span data-ttu-id="3d5bd-216">威胁跟踪器</span><span class="sxs-lookup"><span data-stu-id="3d5bd-216">Threat Trackers</span></span>

<span data-ttu-id="3d5bd-217">[威胁跟踪](https://docs.microsoft.com/office365/securitycompliance/threat-trackers)程序是信息小组件和视图，为授权用户提供了可能会影响您的组织的 cybersecurity 问题的智能。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-217">[Threat Trackers](https://docs.microsoft.com/office365/securitycompliance/threat-trackers) are informative widgets and views that provide authorized users with intelligence on cybersecurity issues that might impact your organization.</span></span>

### <a name="explorer"></a><span data-ttu-id="3d5bd-218">Explorer</span><span class="sxs-lookup"><span data-stu-id="3d5bd-218">Explorer</span></span>

<span data-ttu-id="3d5bd-219">资源管理器（也称为威胁浏览器）是一种实时报告，它使授权用户能够识别和分析最新的威胁。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-219">Explorer (also referred to as Threat Explorer) is a real-time report that enables authorized users to identify and analyze recent threats.</span></span> <span data-ttu-id="3d5bd-220">默认情况下，此报告显示过去7天的数据;但是，可以对视图进行修改，以显示过去30天的数据。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-220">By default, this report shows data for the past 7 days; however, views can be modified to show data for the past 30 days.</span></span>

<span data-ttu-id="3d5bd-221">有关浏览器（在 Office 365 高级威胁防护计划2中）和实时检测（在 Office 365 高级威胁防护计划1中）的详细信息，请参阅[威胁 Explorer （和实时检测）](https://docs.microsoft.com/office365/securitycompliance/threat-explorer)。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-221">For more information about Explorer (in Office 365 Advanced Threat Protection Plan 2) and real-time detections (in Office 365 Advanced Threat Protection Plan 1), see [Threat Explorer (and real-time detections)](https://docs.microsoft.com/office365/securitycompliance/threat-explorer).</span></span>

### <a name="attack-simulator"></a><span data-ttu-id="3d5bd-222">攻击模拟器</span><span class="sxs-lookup"><span data-stu-id="3d5bd-222">Attack Simulator</span></span>

<span data-ttu-id="3d5bd-223">利用[攻击模拟器](https://docs.microsoft.com/office365/SecurityCompliance/attack-simulator)，授权用户可以在您的组织中运行实际的攻击方案。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-223">[Attack Simulator](https://docs.microsoft.com/office365/SecurityCompliance/attack-simulator) enables authorized users to run realistic attack scenarios in your organization.</span></span> <span data-ttu-id="3d5bd-224">有几种不同类型的攻击可供使用，其中包括显示名称 spear 网络钓鱼攻击、密码喷涂攻击和强力密码攻击。</span><span class="sxs-lookup"><span data-stu-id="3d5bd-224">Several different kinds of attacks are available, including a display name spear-phishing attack, a password-spray attack, and a brute-force password attack.</span></span>
