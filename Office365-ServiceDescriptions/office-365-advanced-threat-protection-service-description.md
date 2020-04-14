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
description: Microsoft Office 365 高级威胁防护（ATP）是一项基于云的电子邮件筛选服务，通过提供强健的零天保护来帮助您的组织抵御未知恶意软件和病毒，并包括实时保护组织免受有害链接的功能。
ms.openlocfilehash: 5c604eac3079946c5b6fc2a02b44f4870a99a69f
ms.sourcegitcommit: 80f7e210831388962a4cc9bfa3892ab1070fb92b
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/14/2020
ms.locfileid: "43285548"
---
# <a name="office-365-advanced-threat-protection-service-description"></a><span data-ttu-id="ef95b-103">Office 365 高级威胁防护服务说明</span><span class="sxs-lookup"><span data-stu-id="ef95b-103">Office 365 Advanced Threat Protection service description</span></span>

<span data-ttu-id="ef95b-104">Microsoft Office 365 高级威胁防护（ATP）是一项基于云的电子邮件筛选服务，通过提供强健的零天保护来帮助您的组织抵御未知恶意软件和病毒，并包括实时保护组织免受有害链接的功能。</span><span class="sxs-lookup"><span data-stu-id="ef95b-104">Microsoft Office 365 Advanced Threat Protection (ATP) is a cloud-based email filtering service that helps protect your organization against unknown malware and viruses by providing robust zero-day protection, and includes features to safeguard your organization from harmful links in real time.</span></span> <span data-ttu-id="ef95b-105">ATP 具有丰富的报告功能和 URL 跟踪功能，可让管理员了解组织中发生的攻击种类。</span><span class="sxs-lookup"><span data-stu-id="ef95b-105">ATP has rich reporting and URL trace capabilities that give administrators insight into the kind of attacks happening in your organization.</span></span>

<span data-ttu-id="ef95b-106">以下是您可以使用 ATP 进行邮件保护的主要方式：</span><span class="sxs-lookup"><span data-stu-id="ef95b-106">The following are the primary ways you can use ATP for message protection:</span></span>

- <span data-ttu-id="ef95b-107">在 Office 365 ATP 仅筛选方案中，ATP 为本地 Exchange Server 环境或任何其他本地 SMTP 电子邮件解决方案提供基于云的电子邮件保护。</span><span class="sxs-lookup"><span data-stu-id="ef95b-107">In an Office 365 ATP filtering-only scenario, ATP provides cloud-based email protection for your on-premises Exchange Server environment or any other on-premises SMTP email solution.</span></span>

- <span data-ttu-id="ef95b-108">可以启用 Office 365 ATP 来保护 Exchange Online 云托管的邮箱。</span><span class="sxs-lookup"><span data-stu-id="ef95b-108">Office 365 ATP can be enabled to protect Exchange Online cloud-hosted mailboxes.</span></span> <span data-ttu-id="ef95b-109">若要了解有关 Exchange Online 的详细信息，请参阅[Exchange online 服务说明](exchange-online-service-description/exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="ef95b-109">To learn more about Exchange Online, see the [Exchange Online service description](exchange-online-service-description/exchange-online-service-description.md).</span></span>

- <span data-ttu-id="ef95b-110">在混合部署中，如果您将本地和云邮箱与入站电子邮件筛选的 Exchange Online 保护结合在一起，则可以将 ATP 配置为保护您的邮件环境并控制邮件路由。</span><span class="sxs-lookup"><span data-stu-id="ef95b-110">In a hybrid deployment, ATP can be configured to protect your messaging environment and control mail routing when you have a mix of on-premises and cloud mailboxes with Exchange Online Protection for inbound email filtering.</span></span>

## <a name="office-365-advanced-threat-protection-atp-availability"></a><span data-ttu-id="ef95b-111">Office 365 高级威胁防护（ATP）可用性</span><span class="sxs-lookup"><span data-stu-id="ef95b-111">Office 365 Advanced Threat Protection (ATP) availability</span></span>

<span data-ttu-id="ef95b-112">ATP 包含在 Office 365 企业版 E5、Office 365 教育版 A5 和 Microsoft 365 商业版中。</span><span class="sxs-lookup"><span data-stu-id="ef95b-112">ATP is included in Office 365 Enterprise E5, Office 365 Education A5, and Microsoft 365 Business.</span></span>

<span data-ttu-id="ef95b-113">可以将 ATP 添加到以下 Exchange 和 Office 365 订阅计划中：</span><span class="sxs-lookup"><span data-stu-id="ef95b-113">You can add ATP to the following Exchange and Office 365 subscription plans:</span></span>

- <span data-ttu-id="ef95b-114">Exchange Online 计划 1</span><span class="sxs-lookup"><span data-stu-id="ef95b-114">Exchange Online Plan 1</span></span>

- <span data-ttu-id="ef95b-115">Exchange Online 计划 2</span><span class="sxs-lookup"><span data-stu-id="ef95b-115">Exchange Online Plan 2</span></span>

- <span data-ttu-id="ef95b-116">Exchange Online Kiosk</span><span class="sxs-lookup"><span data-stu-id="ef95b-116">Exchange Online Kiosk</span></span>

- <span data-ttu-id="ef95b-117">Exchange Online Protection</span><span class="sxs-lookup"><span data-stu-id="ef95b-117">Exchange Online Protection</span></span>

- <span data-ttu-id="ef95b-118">Office 365 商业协作版</span><span class="sxs-lookup"><span data-stu-id="ef95b-118">Office 365 Business Essentials</span></span>

- <span data-ttu-id="ef95b-119"> Office 365 商业高级版</span><span class="sxs-lookup"><span data-stu-id="ef95b-119">Office 365 Business Premium</span></span>

- <span data-ttu-id="ef95b-120">Office 365 企业版 E1</span><span class="sxs-lookup"><span data-stu-id="ef95b-120">Office 365 Enterprise E1</span></span>

- <span data-ttu-id="ef95b-121">Office 365 企业版 E3</span><span class="sxs-lookup"><span data-stu-id="ef95b-121">Office 365 Enterprise E3</span></span>

- <span data-ttu-id="ef95b-122">Office 365 企业版 F3</span><span class="sxs-lookup"><span data-stu-id="ef95b-122">Office 365 Enterprise F3</span></span>

- <span data-ttu-id="ef95b-123">Office 365 A1</span><span class="sxs-lookup"><span data-stu-id="ef95b-123">Office 365 A1</span></span>

- <span data-ttu-id="ef95b-124">Office 365 A3</span><span class="sxs-lookup"><span data-stu-id="ef95b-124">Office 365 A3</span></span>

<span data-ttu-id="ef95b-125">若要购买 Office 365 高级威胁防护，请参阅[office 365 高级威胁防护](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)。</span><span class="sxs-lookup"><span data-stu-id="ef95b-125">To buy Office 365 Advanced Threat Protection, see [Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).</span></span>

<span data-ttu-id="ef95b-126">若要跨计划比较功能，请参阅[比较 Office 365 For Business 计划](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409)和[发现适合你的 Microsoft 365 企业解决方案](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans)。</span><span class="sxs-lookup"><span data-stu-id="ef95b-126">To compare features across plans, see [Compare Office 365 for Business plans](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) and [Discover the Microsoft 365 Enterprise solution that's right for you](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans).</span></span>

## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a><span data-ttu-id="ef95b-127">Office 365 高级威胁防护（ATP）的新增功能</span><span class="sxs-lookup"><span data-stu-id="ef95b-127">What's new in Office 365 Advanced Threat Protection (ATP)</span></span>

<span data-ttu-id="ef95b-128">我们正在继续向 Office 365 ATP 添加新功能。</span><span class="sxs-lookup"><span data-stu-id="ef95b-128">We are continuing to add new features to Office 365 ATP.</span></span> <span data-ttu-id="ef95b-129">若要了解有关即将 ATP （或常规 Microsoft 365）的新功能的详细信息，请参阅以下资源：</span><span class="sxs-lookup"><span data-stu-id="ef95b-129">To learn more about new features coming to ATP (or Microsoft 365 in general), see the following resources:</span></span>

- [<span data-ttu-id="ef95b-130">Microsoft 365 路线图</span><span class="sxs-lookup"><span data-stu-id="ef95b-130">Microsoft 365 Roadmap</span></span>](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [<span data-ttu-id="ef95b-131">Office 365 ATP 的新增功能</span><span class="sxs-lookup"><span data-stu-id="ef95b-131">What's new in Office 365 ATP</span></span>](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a><span data-ttu-id="ef95b-132">Office 365 高级威胁防护（ATP）的要求</span><span class="sxs-lookup"><span data-stu-id="ef95b-132">Requirements for Office 365 Advanced Threat Protection (ATP)</span></span>

<span data-ttu-id="ef95b-133">ATP 可以与任何 SMTP 邮件传输代理（如 Microsoft Exchange Server）一起使用。</span><span class="sxs-lookup"><span data-stu-id="ef95b-133">ATP can be used with any SMTP mail transfer agent, such as Microsoft Exchange Server.</span></span> <span data-ttu-id="ef95b-134">若要了解 ATP 支持的操作系统、Web 浏览器和语言，请参阅 [Exchange Online Protection 中的 Exchange 管理中心](https://go.microsoft.com/fwlink/p/?LinkId=282381)的"支持的浏览器"和"支持的语言"部分。</span><span class="sxs-lookup"><span data-stu-id="ef95b-134">For information about the operating systems, web browsers, and languages that are supported by ATP, see the "Supported browsers" and "Supported languages" sections in [Exchange Admin Center in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).</span></span>

## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a><span data-ttu-id="ef95b-135">跨高级威胁防护（ATP）计划的功能可用性</span><span class="sxs-lookup"><span data-stu-id="ef95b-135">Feature availability across Advanced Threat Protection (ATP) plans</span></span>

<span data-ttu-id="ef95b-p105">下面列出了每个功能。当提到 Exchange Online 时，通常指的是 Office 365 企业版服务系列。</span><span class="sxs-lookup"><span data-stu-id="ef95b-p105">Each feature is listed below. When Exchange Online is mentioned, it typically refers to the Office 365 Enterprise service family.</span></span>

|<span data-ttu-id="ef95b-138">**功能**</span><span class="sxs-lookup"><span data-stu-id="ef95b-138">**Feature**</span></span>|<span data-ttu-id="ef95b-139">**ATP 计划1**</span><span class="sxs-lookup"><span data-stu-id="ef95b-139">**ATP Plan 1**</span></span><br><span data-ttu-id="ef95b-140">（以前的 ATP 独立）</span><span class="sxs-lookup"><span data-stu-id="ef95b-140">(formerly ATP standalone)</span></span>|<span data-ttu-id="ef95b-141">**ATP 计划2**</span><span class="sxs-lookup"><span data-stu-id="ef95b-141">**ATP Plan 2**</span></span><br><span data-ttu-id="ef95b-142">（以前称为威胁智能</span><span class="sxs-lookup"><span data-stu-id="ef95b-142">(formerly Threat Intelligence</span></span> <br><span data-ttu-id="ef95b-143">独立主机</span><span class="sxs-lookup"><span data-stu-id="ef95b-143">standalone)</span></span>| <span data-ttu-id="ef95b-144">Office 365 企业版 E5</span><span class="sxs-lookup"><span data-stu-id="ef95b-144">Office 365 Enterprise E5</span></span>|
|:-----|:-----|:-----|:-----|
|<span data-ttu-id="ef95b-145">*配置、保护和检测*</span><span class="sxs-lookup"><span data-stu-id="ef95b-145">*Configuration, protection, and detection*</span></span>|
|[<span data-ttu-id="ef95b-146">安全附件</span><span class="sxs-lookup"><span data-stu-id="ef95b-146">Safe Attachments</span></span>](#safe-attachments)|<span data-ttu-id="ef95b-147">是</span><span class="sxs-lookup"><span data-stu-id="ef95b-147">Yes</span></span>|<span data-ttu-id="ef95b-148">是</span><span class="sxs-lookup"><span data-stu-id="ef95b-148">Yes</span></span>|<span data-ttu-id="ef95b-149">是</span><span class="sxs-lookup"><span data-stu-id="ef95b-149">Yes</span></span>|
|<span data-ttu-id="ef95b-150">团队中的安全附件</span><span class="sxs-lookup"><span data-stu-id="ef95b-150">Safe Attachments in Teams</span></span>|<span data-ttu-id="ef95b-151">是</span><span class="sxs-lookup"><span data-stu-id="ef95b-151">Yes</span></span>|<span data-ttu-id="ef95b-152">是</span><span class="sxs-lookup"><span data-stu-id="ef95b-152">Yes</span></span>|<span data-ttu-id="ef95b-153">是</span><span class="sxs-lookup"><span data-stu-id="ef95b-153">Yes</span></span>|
|[<span data-ttu-id="ef95b-154">安全链接</span><span class="sxs-lookup"><span data-stu-id="ef95b-154">Safe Links</span></span>](#safe-links)|<span data-ttu-id="ef95b-155">是</span><span class="sxs-lookup"><span data-stu-id="ef95b-155">Yes</span></span>|<span data-ttu-id="ef95b-156">是</span><span class="sxs-lookup"><span data-stu-id="ef95b-156">Yes</span></span>|<span data-ttu-id="ef95b-157">是</span><span class="sxs-lookup"><span data-stu-id="ef95b-157">Yes</span></span>|
|<span data-ttu-id="ef95b-158">Teams 中安全链接</span><span class="sxs-lookup"><span data-stu-id="ef95b-158">Safe Links in Teams</span></span>|<span data-ttu-id="ef95b-159">是</span><span class="sxs-lookup"><span data-stu-id="ef95b-159">Yes</span></span>|<span data-ttu-id="ef95b-160">是</span><span class="sxs-lookup"><span data-stu-id="ef95b-160">Yes</span></span>|<span data-ttu-id="ef95b-161">是</span><span class="sxs-lookup"><span data-stu-id="ef95b-161">Yes</span></span>|
|[<span data-ttu-id="ef95b-162">SharePoint、OneDrive 和 Microsoft 团队的 ATP</span><span class="sxs-lookup"><span data-stu-id="ef95b-162">ATP for SharePoint, OneDrive and Microsoft Teams</span></span>](#atp-for-sharepoint-onedrive-and-microsoft-teams)|<span data-ttu-id="ef95b-163">是</span><span class="sxs-lookup"><span data-stu-id="ef95b-163">Yes</span></span>|<span data-ttu-id="ef95b-164">是</span><span class="sxs-lookup"><span data-stu-id="ef95b-164">Yes</span></span>|<span data-ttu-id="ef95b-165">是</span><span class="sxs-lookup"><span data-stu-id="ef95b-165">Yes</span></span>|
|[<span data-ttu-id="ef95b-166">反网络钓鱼策略</span><span class="sxs-lookup"><span data-stu-id="ef95b-166">Anti-phishing policies</span></span>](#anti-phishing-policies)|<span data-ttu-id="ef95b-167">是</span><span class="sxs-lookup"><span data-stu-id="ef95b-167">Yes</span></span>|<span data-ttu-id="ef95b-168">是</span><span class="sxs-lookup"><span data-stu-id="ef95b-168">Yes</span></span>|<span data-ttu-id="ef95b-169">是</span><span class="sxs-lookup"><span data-stu-id="ef95b-169">Yes</span></span>|
|[<span data-ttu-id="ef95b-170">实时报告</span><span class="sxs-lookup"><span data-stu-id="ef95b-170">Real-time reports</span></span>](#real-time-reports)|<span data-ttu-id="ef95b-171">是</span><span class="sxs-lookup"><span data-stu-id="ef95b-171">Yes</span></span>|<span data-ttu-id="ef95b-172">是</span><span class="sxs-lookup"><span data-stu-id="ef95b-172">Yes</span></span>|<span data-ttu-id="ef95b-173">是</span><span class="sxs-lookup"><span data-stu-id="ef95b-173">Yes</span></span>|
|<span data-ttu-id="ef95b-174">*自动化、调查、修正和教育*</span><span class="sxs-lookup"><span data-stu-id="ef95b-174">*Automation, investigation, remediation, and education*</span></span>|
|[<span data-ttu-id="ef95b-175">威胁跟踪器</span><span class="sxs-lookup"><span data-stu-id="ef95b-175">Threat Trackers</span></span>](#threat-trackers)|<span data-ttu-id="ef95b-176">否</span><span class="sxs-lookup"><span data-stu-id="ef95b-176">No</span></span>|<span data-ttu-id="ef95b-177">可访问</span><span class="sxs-lookup"><span data-stu-id="ef95b-177">Yes</span></span>|<span data-ttu-id="ef95b-178">是</span><span class="sxs-lookup"><span data-stu-id="ef95b-178">Yes</span></span>|
|<span data-ttu-id="ef95b-179">威胁调查（高级威胁调查）</span><span class="sxs-lookup"><span data-stu-id="ef95b-179">Threat investigation  (advanced threat investigation)</span></span>|[<span data-ttu-id="ef95b-180">实时检测</span><span class="sxs-lookup"><span data-stu-id="ef95b-180">Real-time detections</span></span>](#real-time-detections)|[<span data-ttu-id="ef95b-181">Explorer</span><span class="sxs-lookup"><span data-stu-id="ef95b-181">Explorer</span></span>](#explorer)|[<span data-ttu-id="ef95b-182">Explorer</span><span class="sxs-lookup"><span data-stu-id="ef95b-182">Explorer</span></span>](#explorer)|
|[<span data-ttu-id="ef95b-183">自动化事件响应</span><span class="sxs-lookup"><span data-stu-id="ef95b-183">Automated incident response</span></span>](#automated-incident-response)|<span data-ttu-id="ef95b-184">否</span><span class="sxs-lookup"><span data-stu-id="ef95b-184">No</span></span>|<span data-ttu-id="ef95b-185">可访问</span><span class="sxs-lookup"><span data-stu-id="ef95b-185">Yes</span></span>|<span data-ttu-id="ef95b-186">是</span><span class="sxs-lookup"><span data-stu-id="ef95b-186">Yes</span></span>|
|[<span data-ttu-id="ef95b-187">攻击模拟器</span><span class="sxs-lookup"><span data-stu-id="ef95b-187">Attack Simulator</span></span>](#attack-simulator)|<span data-ttu-id="ef95b-188">否</span><span class="sxs-lookup"><span data-stu-id="ef95b-188">No</span></span>|<span data-ttu-id="ef95b-189">可访问</span><span class="sxs-lookup"><span data-stu-id="ef95b-189">Yes</span></span>|<span data-ttu-id="ef95b-190">是</span><span class="sxs-lookup"><span data-stu-id="ef95b-190">Yes</span></span>|

> [!TIP]
> <span data-ttu-id="ef95b-191">想要一个可下载的 Office 365 ATP 计划1与计划2之间的差异列表吗？</span><span class="sxs-lookup"><span data-stu-id="ef95b-191">Want a downloadable list of differences between Office 365 ATP Plan 1 and Plan 2?</span></span> <span data-ttu-id="ef95b-192">[获取 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/Office%20365%20ATP%20Plan%20Comparison%20-%20March%202020.pdf)。</span><span class="sxs-lookup"><span data-stu-id="ef95b-192">[Get the PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/Office%20365%20ATP%20Plan%20Comparison%20-%20March%202020.pdf).</span></span> 

## <a name="advanced-threat-protection-atp-capabilities"></a><span data-ttu-id="ef95b-193">高级威胁防护（ATP）功能</span><span class="sxs-lookup"><span data-stu-id="ef95b-193">Advanced Threat Protection (ATP) capabilities</span></span>

### <a name="safe-attachments"></a><span data-ttu-id="ef95b-194">安全附件</span><span class="sxs-lookup"><span data-stu-id="ef95b-194">Safe Attachments</span></span>

<span data-ttu-id="ef95b-195">[ATP 安全附件](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments)针对未知恶意软件和病毒提供保护，并提供为期零天的保护，以保护您的邮件系统。</span><span class="sxs-lookup"><span data-stu-id="ef95b-195">[ATP Safe Attachments](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) protects against unknown malware and viruses, and provides zero-day protection to safeguard your messaging system.</span></span> <span data-ttu-id="ef95b-196">所有不带有已知的病毒/恶意软件签名的邮件和附件都被路由到一个特殊的环境中，ATP 将在其中使用多种机器学习和分析技术来检测恶意企图。</span><span class="sxs-lookup"><span data-stu-id="ef95b-196">All messages and attachments that don't have a known virus/malware signature are routed to a special environment where ATP uses a variety of machine learning and analysis techniques to detect malicious intent.</span></span> <span data-ttu-id="ef95b-197">如果没有检测到可疑的活动，会发布邮件并传递到邮箱中。</span><span class="sxs-lookup"><span data-stu-id="ef95b-197">If no suspicious activity is detected, the message is released for delivery to the mailbox.</span></span>

> [!NOTE]
> <span data-ttu-id="ef95b-198">ATP 安全附件扫描发生在 Office 365 数据所在的同一个区域中。</span><span class="sxs-lookup"><span data-stu-id="ef95b-198">ATP Safe Attachments scanning takes place in the same region where your Office 365 data resides.</span></span> <span data-ttu-id="ef95b-199">有关数据中心地理位置的详细信息，请参阅[您的数据位于何处？](https://products.office.com/where-is-your-data-located?geo=All)</span><span class="sxs-lookup"><span data-stu-id="ef95b-199">For more information about data center geography, see [Where is your data located?](https://products.office.com/where-is-your-data-located?geo=All)</span></span>

### <a name="safe-links"></a><span data-ttu-id="ef95b-200">安全链接</span><span class="sxs-lookup"><span data-stu-id="ef95b-200">Safe Links</span></span>

<span data-ttu-id="ef95b-201">[ATP 安全链接](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)功能主动保护您的用户免受邮件中或 Office 文档中的恶意 url 的攻击。</span><span class="sxs-lookup"><span data-stu-id="ef95b-201">The [ATP Safe Links](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) feature proactively protects your users from malicious URLs in a message or in an Office document.</span></span> <span data-ttu-id="ef95b-202">每次选择该链接时，都会保持保护，因为在可以访问正确的链接时，会动态阻止恶意链接。</span><span class="sxs-lookup"><span data-stu-id="ef95b-202">The protection remains every time they select the link, as malicious links are dynamically blocked while good links can be accessed.</span></span>

<span data-ttu-id="ef95b-203">安全链接可用于以下应用程序中的 Url：</span><span class="sxs-lookup"><span data-stu-id="ef95b-203">Safe Links is available for URLs in the following apps:</span></span>

- <span data-ttu-id="ef95b-204">Windows 或 Mac 上的 Office 365 专业增强版</span><span class="sxs-lookup"><span data-stu-id="ef95b-204">Office 365 ProPlus on Windows or Mac</span></span>

- <span data-ttu-id="ef95b-205">适用于 web 的 Office （适用于 web 的 Excel、适用于 web 的 Excel、PowerPoint for web 以及适用于 web 的 OneNote）</span><span class="sxs-lookup"><span data-stu-id="ef95b-205">Office for the web (Word for the web, Excel for the web, PowerPoint for the web, and OneNote for the web)</span></span>

- <span data-ttu-id="ef95b-206">Windows 上的 Word、Excel、PowerPoint 和 Visio，以及 iOS 和 Android 设备上的 Office 应用</span><span class="sxs-lookup"><span data-stu-id="ef95b-206">Word, Excel, PowerPoint, and Visio on Windows, as well as Office apps on iOS and Android devices</span></span>

- <span data-ttu-id="ef95b-207">Microsoft Teams 频道和聊天</span><span class="sxs-lookup"><span data-stu-id="ef95b-207">Microsoft Teams channels and chats</span></span>

> [!NOTE]
> <span data-ttu-id="ef95b-208">用户必须获得 ATP<sup>\*</sup>许可，必须包含在 Atp 安全链接策略中，并且必须在其设备上登录，才能就地保护。</span><span class="sxs-lookup"><span data-stu-id="ef95b-208">Users must be licensed for ATP<sup>\*</sup>, must be included in ATP Safe Links policies, and must be signed in on their devices for protection to be in place.</span></span>
>
> <span data-ttu-id="ef95b-209"><sup>\*</sup>对于组织范围的 ATP 许可证（例如，ATP_ENTERPRISE_FACULTY），无需向单个用户分配 ATP 许可证。</span><span class="sxs-lookup"><span data-stu-id="ef95b-209"><sup>\*</sup> For organization-wide ATP licenses (for example, ATP_ENTERPRISE_FACULTY), you don't need to assign ATP licenses to individual users.</span></span>
>
> <span data-ttu-id="ef95b-210">有关 ATP 安全链接保护的详细信息，请参阅[Atp 安全链接如何处理 Office 文档中的 url](https://docs.microsoft.com/microsoft-365/security/office-365-security/how-atp-safe-links-works#how-atp-safe-links-works-with-urls-in-office-documents)。</span><span class="sxs-lookup"><span data-stu-id="ef95b-210">For more information about ATP Safe Links protection, see [How ATP Safe Links works with URLs in Office documents](https://docs.microsoft.com/microsoft-365/security/office-365-security/how-atp-safe-links-works#how-atp-safe-links-works-with-urls-in-office-documents).</span></span>

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a><span data-ttu-id="ef95b-211">适用于 SharePoint、OneDrive 和 Microsoft Teams 的 ATP</span><span class="sxs-lookup"><span data-stu-id="ef95b-211">ATP for SharePoint, OneDrive, and Microsoft Teams</span></span>

<span data-ttu-id="ef95b-212">[SharePoint、OneDrive 和 Microsoft 团队的 ATP](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)可帮助检测和阻止在工作组网站和文档库中被标识为恶意的文件。</span><span class="sxs-lookup"><span data-stu-id="ef95b-212">[ATP for SharePoint, OneDrive, and Microsoft Teams](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  helps detect and block files that are identified as malicious in team sites and document libraries.</span></span> <span data-ttu-id="ef95b-213">此外，ATP 安全链接保护现已在 Microsoft 团队频道和聊天中提供。</span><span class="sxs-lookup"><span data-stu-id="ef95b-213">In addition, ATP Safe Links protection is now available in Microsoft Teams channels and chats.</span></span>

### <a name="anti-phishing-policies"></a><span data-ttu-id="ef95b-214">反网络钓鱼策略</span><span class="sxs-lookup"><span data-stu-id="ef95b-214">Anti-phishing policies</span></span>

<span data-ttu-id="ef95b-215">[ATP 反网络钓鱼](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing)检查传入的邮件，以指示邮件可能是网络钓鱼尝试。</span><span class="sxs-lookup"><span data-stu-id="ef95b-215">[ATP anti-phishing](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) checks incoming messages for indicators that a message might be a phishing attempt.</span></span> <span data-ttu-id="ef95b-216">当 ATP 策略（安全附件、安全链接或反网络钓鱼）覆盖了用户时，将通过分析邮件的多个机器学习模型来评估传入的邮件，并根据配置的策略采取相应的操作。</span><span class="sxs-lookup"><span data-stu-id="ef95b-216">When users are covered by ATP policies (Safe Attachments, Safe Links, or anti-phishing), incoming messages are evaluated by multiple machine learning models that analyze messages and the appropriate action is taken, based on the configured policies.</span></span>

### <a name="real-time-reports"></a><span data-ttu-id="ef95b-217">实时报告</span><span class="sxs-lookup"><span data-stu-id="ef95b-217">Real-time reports</span></span>

<span data-ttu-id="ef95b-218">Office 365 安全 & 合规性中心中提供的监视功能包括[实时报告和见解](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp)，使您的安全和合规性能够重点关注高优先级问题，如安全攻击或更高的可疑活动。</span><span class="sxs-lookup"><span data-stu-id="ef95b-218">Monitoring capabilities available in the Office 365 Security & Compliance Center include [real-time reports and insights](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) that let your security and compliance administrators focus on high-priority issues, such as security attacks or increased suspicious activity.</span></span> <span data-ttu-id="ef95b-219">除了突出显示问题区域之外，智能报告和见解还包括用于查看和浏览数据的建议和链接，同时还采取快速操作。</span><span class="sxs-lookup"><span data-stu-id="ef95b-219">In addition to highlighting problem areas, smart reports and insights include recommendations and links to view and explore data and also take quick actions.</span></span>

### <a name="explorer"></a><span data-ttu-id="ef95b-220">Explorer</span><span class="sxs-lookup"><span data-stu-id="ef95b-220">Explorer</span></span>

<span data-ttu-id="ef95b-221">资源管理器（也称为威胁浏览器）是一个实时报告，它允许授权用户识别和分析最新的威胁。</span><span class="sxs-lookup"><span data-stu-id="ef95b-221">Explorer (also referred to as Threat Explorer) is a real-time report that lets authorized users identify and analyze recent threats.</span></span> <span data-ttu-id="ef95b-222">默认情况下，此报告显示过去7天的数据;但是，可以对视图进行修改，以显示过去30天的数据。</span><span class="sxs-lookup"><span data-stu-id="ef95b-222">By default, this report shows data for the past 7 days; however, views can be modified to show data for the past 30 days.</span></span>

<span data-ttu-id="ef95b-223">资源管理器包含视图，如恶意软件（电子邮件和内容）、提交、网络钓鱼和所有电子邮件。</span><span class="sxs-lookup"><span data-stu-id="ef95b-223">Explorer contains views, such as Malware (for email and content), Submissions, Phish, and All Email.</span></span> <span data-ttu-id="ef95b-224">若要查看浏览器与实时检测的比较情况，请[下载此 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/Office%20365%20ATP%20Plan%20Comparison%20-%20March%202020.pdf)。</span><span class="sxs-lookup"><span data-stu-id="ef95b-224">To see how Explorer compares with real-time detections, [download this PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/Office%20365%20ATP%20Plan%20Comparison%20-%20March%202020.pdf).</span></span>

<span data-ttu-id="ef95b-225">有关浏览器（在 Office 365 高级威胁防护计划2中）和实时检测（在 Office 365 高级威胁防护计划1中）的详细信息，请参阅[威胁 Explorer （和实时检测）](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)。</span><span class="sxs-lookup"><span data-stu-id="ef95b-225">For more information about Explorer (in Office 365 Advanced Threat Protection Plan 2) and real-time detections (in Office 365 Advanced Threat Protection Plan 1), see [Threat Explorer (and real-time detections)](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).</span></span>

### <a name="real-time-detections"></a><span data-ttu-id="ef95b-226">实时检测</span><span class="sxs-lookup"><span data-stu-id="ef95b-226">Real-time detections</span></span>

<span data-ttu-id="ef95b-227">实时检测是一份实时报告，可让授权用户识别和分析最新的威胁。</span><span class="sxs-lookup"><span data-stu-id="ef95b-227">Real-time detections is a real-time report that lets authorized users identify and analyze recent threats.</span></span> <span data-ttu-id="ef95b-228">与资源管理器类似，默认情况下，此报告显示过去7天的数据。</span><span class="sxs-lookup"><span data-stu-id="ef95b-228">Similar to Explorer, by default, this report shows data for the past 7 days.</span></span>

<span data-ttu-id="ef95b-229">实时检测包含视图，如恶意软件（电子邮件和内容）、提交和网络钓鱼。</span><span class="sxs-lookup"><span data-stu-id="ef95b-229">Real-time detections contain views, such as Malware (for email and content), Submissions, and Phish.</span></span> <span data-ttu-id="ef95b-230">若要查看实时检测与资源管理器的比较情况，请[下载此 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/Office%20365%20ATP%20Plan%20Comparison%20-%20March%202020.pdf)。</span><span class="sxs-lookup"><span data-stu-id="ef95b-230">To see how real-time detections compare with Explorer, [download this PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/Office%20365%20ATP%20Plan%20Comparison%20-%20March%202020.pdf).</span></span>

<span data-ttu-id="ef95b-231">有关浏览器（在 Office 365 高级威胁防护计划2中）和实时检测（在 Office 365 高级威胁防护计划1中）的详细信息，请参阅[威胁 Explorer （和实时检测）](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)。</span><span class="sxs-lookup"><span data-stu-id="ef95b-231">For more information about Explorer (in Office 365 Advanced Threat Protection Plan 2) and real-time detections (in Office 365 Advanced Threat Protection Plan 1), see [Threat Explorer (and real-time detections)](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).</span></span>

### <a name="threat-trackers"></a><span data-ttu-id="ef95b-232">威胁跟踪器</span><span class="sxs-lookup"><span data-stu-id="ef95b-232">Threat Trackers</span></span>

<span data-ttu-id="ef95b-233">[威胁跟踪](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers)程序是信息小组件和视图，为授权用户提供了可能会影响您的组织的 cybersecurity 问题的智能。</span><span class="sxs-lookup"><span data-stu-id="ef95b-233">[Threat Trackers](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) are informative widgets and views that provide authorized users with intelligence on cybersecurity issues that might impact your organization.</span></span>

### <a name="automated-incident-response"></a><span data-ttu-id="ef95b-234">自动化事件响应</span><span class="sxs-lookup"><span data-stu-id="ef95b-234">Automated incident response</span></span>

<span data-ttu-id="ef95b-235">Office 365 ATP 计划2中提供的[自动事件响应](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air)（空中）功能使您能够运行自动化的调查过程，以应对目前存在的已知威胁。</span><span class="sxs-lookup"><span data-stu-id="ef95b-235">[Automated incident response](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) (AIR) capabilities available in Office 365 ATP Plan 2 enable you to run automated investigation processes in response to well known threats that exist today.</span></span> <span data-ttu-id="ef95b-236">通过自动执行某些调查任务，安全操作团队可以更高效地运行。</span><span class="sxs-lookup"><span data-stu-id="ef95b-236">By automated certain investigation tasks, your security operations team can operate more efficiently and effectively.</span></span> <span data-ttu-id="ef95b-237">安全操作团队批准执行更正操作，如删除恶意电子邮件。</span><span class="sxs-lookup"><span data-stu-id="ef95b-237">Remediation actions, such as deleting malicious email messages, are taken upon approval by your security operations team.</span></span> <span data-ttu-id="ef95b-238">若要了解详细信息，请参阅[Office 365 中的 AIR 的工作原理](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office)。</span><span class="sxs-lookup"><span data-stu-id="ef95b-238">To learn more, see [How AIR works in Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office).</span></span>

### <a name="attack-simulator"></a><span data-ttu-id="ef95b-239">攻击模拟器</span><span class="sxs-lookup"><span data-stu-id="ef95b-239">Attack Simulator</span></span>

<span data-ttu-id="ef95b-240">[攻击模拟器](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator)允许授权用户在您的组织中运行实际的攻击方案。</span><span class="sxs-lookup"><span data-stu-id="ef95b-240">[Attack Simulator](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) lets authorized users run realistic attack scenarios in your organization.</span></span> <span data-ttu-id="ef95b-241">有几种不同类型的攻击可供使用，其中包括显示名称 spear 网络钓鱼攻击、密码喷涂攻击和强力密码攻击。</span><span class="sxs-lookup"><span data-stu-id="ef95b-241">Several different kinds of attacks are available, including a display name spear-phishing attack, a password-spray attack, and a brute-force password attack.</span></span>
