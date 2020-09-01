---
title: Office 365 高级威胁防护服务说明
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 高级威胁防护 (ATP) 是一种基于云的电子邮件筛选服务，通过提供强健的零天保护来帮助您的组织抵御未知恶意软件和病毒，并包括实时保护组织免受有害链接的功能。
ms.openlocfilehash: 0e9c7e76cabd9f39a13c16689a4255732617b09d
ms.sourcegitcommit: 0f2d249dfc93432e17344f70b8317a455204f018
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/01/2020
ms.locfileid: "47318939"
---
# <a name="office-365-advanced-threat-protection-service-description"></a><span data-ttu-id="177db-103">Office 365 高级威胁防护服务说明</span><span class="sxs-lookup"><span data-stu-id="177db-103">Office 365 Advanced Threat Protection service description</span></span>

<span data-ttu-id="177db-104">Microsoft Office 365 高级威胁防护 (ATP) 是一种基于云的电子邮件筛选服务，通过提供强健的零天保护来帮助您的组织抵御未知恶意软件和病毒，并包括实时保护组织免受有害链接的功能。</span><span class="sxs-lookup"><span data-stu-id="177db-104">Microsoft Office 365 Advanced Threat Protection (ATP) is a cloud-based email filtering service that helps protect your organization against unknown malware and viruses by providing robust zero-day protection, and includes features to safeguard your organization from harmful links in real time.</span></span> <span data-ttu-id="177db-105">ATP 具有丰富的报告功能和 URL 跟踪功能，可让管理员了解组织中发生的攻击种类。</span><span class="sxs-lookup"><span data-stu-id="177db-105">ATP has rich reporting and URL trace capabilities that give administrators insight into the kind of attacks happening in your organization.</span></span>

<span data-ttu-id="177db-106">以下是你可以使用 ATP 进行邮件保护的主要方式：</span><span class="sxs-lookup"><span data-stu-id="177db-106">The following are the primary ways you can use ATP for message protection:</span></span>

- <span data-ttu-id="177db-107">在 Office 365 ATP 仅筛选方案中，ATP 将为你的本地 Exchange Server 环境或任何其他本地 SMTP 电子邮件解决方案提供基于云的电子邮件保护。</span><span class="sxs-lookup"><span data-stu-id="177db-107">In an Office 365 ATP filtering-only scenario, ATP provides cloud-based email protection for your on-premises Exchange Server environment or any other on-premises SMTP email solution.</span></span>

- <span data-ttu-id="177db-108">可以启用 Office 365 ATP 来保护 Exchange Online 的云托管邮箱。</span><span class="sxs-lookup"><span data-stu-id="177db-108">Office 365 ATP can be enabled to protect Exchange Online cloud-hosted mailboxes.</span></span> <span data-ttu-id="177db-109">若要了解有关 Exchange Online 的详细信息，请参阅 [Exchange online 服务说明](exchange-online-service-description/exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="177db-109">To learn more about Exchange Online, see the [Exchange Online service description](exchange-online-service-description/exchange-online-service-description.md).</span></span>

- <span data-ttu-id="177db-110">在混合部署中，当邮箱中混合了本地邮箱和云邮箱并且使用 Exchange Online Protection 筛选入站电子邮件时，可配置 ATP 以保护邮件环境和控制邮件路由。</span><span class="sxs-lookup"><span data-stu-id="177db-110">In a hybrid deployment, ATP can be configured to protect your messaging environment and control mail routing when you have a mix of on-premises and cloud mailboxes with Exchange Online Protection for inbound email filtering.</span></span>

## <a name="office-365-advanced-threat-protection-atp-availability"></a><span data-ttu-id="177db-111">Office 365 高级威胁防护 (ATP) 可用性</span><span class="sxs-lookup"><span data-stu-id="177db-111">Office 365 Advanced Threat Protection (ATP) availability</span></span>

<span data-ttu-id="177db-112">Office 365 E5、Office 365 A5 和 Microsoft 365 E5 中包含 Office 365 ATP 计划 2。</span><span class="sxs-lookup"><span data-stu-id="177db-112">Office 365 ATP Plan 2 is included in Office 365 E5, Office 365 A5, and Microsoft 365 E5.</span></span> <span data-ttu-id="177db-113">Office 365 ATP 计划 1 包含在 Microsoft 365 商业高级版中。</span><span class="sxs-lookup"><span data-stu-id="177db-113">Office 365 ATP Plan 1 is included in Microsoft 365 Business Premium.</span></span>

<span data-ttu-id="177db-114">您可以向以下 Exchange 和 Microsoft 365 订阅计划中添加 ATP：</span><span class="sxs-lookup"><span data-stu-id="177db-114">You can add ATP to the following Exchange and Microsoft 365 subscription plans:</span></span>

- <span data-ttu-id="177db-115">Exchange Online 计划 1</span><span class="sxs-lookup"><span data-stu-id="177db-115">Exchange Online Plan 1</span></span>

- <span data-ttu-id="177db-116">Exchange Online 计划 2</span><span class="sxs-lookup"><span data-stu-id="177db-116">Exchange Online Plan 2</span></span>

- <span data-ttu-id="177db-117">Exchange Online Kiosk</span><span class="sxs-lookup"><span data-stu-id="177db-117">Exchange Online Kiosk</span></span>

- <span data-ttu-id="177db-118">Exchange Online Protection</span><span class="sxs-lookup"><span data-stu-id="177db-118">Exchange Online Protection</span></span>

- <span data-ttu-id="177db-119">Microsoft 365 商业基础版</span><span class="sxs-lookup"><span data-stu-id="177db-119">Microsoft 365 Business Basic</span></span>

- <span data-ttu-id="177db-120">Microsoft 365 商业标准版</span><span class="sxs-lookup"><span data-stu-id="177db-120">Microsoft 365 Business Standard</span></span>

- <span data-ttu-id="177db-121">Office 365 企业版 E1</span><span class="sxs-lookup"><span data-stu-id="177db-121">Office 365 Enterprise E1</span></span>

- <span data-ttu-id="177db-122">Office 365 企业版 E3</span><span class="sxs-lookup"><span data-stu-id="177db-122">Office 365 Enterprise E3</span></span>

- <span data-ttu-id="177db-123">Office 365 企业版 F3</span><span class="sxs-lookup"><span data-stu-id="177db-123">Office 365 Enterprise F3</span></span>

- <span data-ttu-id="177db-124">Office 365 A1</span><span class="sxs-lookup"><span data-stu-id="177db-124">Office 365 A1</span></span>

- <span data-ttu-id="177db-125">Office 365 A3</span><span class="sxs-lookup"><span data-stu-id="177db-125">Office 365 A3</span></span>

<span data-ttu-id="177db-126">若要购买 Office 365 高级威胁防护，请参阅 [office 365 高级威胁防护](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)。</span><span class="sxs-lookup"><span data-stu-id="177db-126">To buy Office 365 Advanced Threat Protection, see [Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).</span></span>

<span data-ttu-id="177db-127">若要跨计划比较功能，请参阅 [强大的工具来支持您的企业](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) 并 [使用 Microsoft 365 转换企业](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans)。</span><span class="sxs-lookup"><span data-stu-id="177db-127">To compare features across plans, see [Powerful tools to support your enterprise](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) and [Transform your enterprise with Microsoft 365](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans).</span></span>

## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a><span data-ttu-id="177db-128">Office 365 高级威胁防护中的新增功能 (ATP) </span><span class="sxs-lookup"><span data-stu-id="177db-128">What's new in Office 365 Advanced Threat Protection (ATP)</span></span>

<span data-ttu-id="177db-129">我们正在继续向 Office 365 ATP 添加新功能。</span><span class="sxs-lookup"><span data-stu-id="177db-129">We are continuing to add new features to Office 365 ATP.</span></span> <span data-ttu-id="177db-130">若要了解有关即将 ATP (或 Microsoft 365 常规) 的新功能的详细信息，请参阅以下资源：</span><span class="sxs-lookup"><span data-stu-id="177db-130">To learn more about new features coming to ATP (or Microsoft 365 in general), see the following resources:</span></span>

- [<span data-ttu-id="177db-131">Microsoft 365 路线图</span><span class="sxs-lookup"><span data-stu-id="177db-131">Microsoft 365 Roadmap</span></span>](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [<span data-ttu-id="177db-132">Office 365 ATP 的新增功能</span><span class="sxs-lookup"><span data-stu-id="177db-132">What's new in Office 365 ATP</span></span>](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a><span data-ttu-id="177db-133">Office 365 高级威胁防护的要求 (ATP) </span><span class="sxs-lookup"><span data-stu-id="177db-133">Requirements for Office 365 Advanced Threat Protection (ATP)</span></span>

<span data-ttu-id="177db-134">ATP 可以与任何 SMTP 邮件传输代理（如 Microsoft Exchange Server）一起使用。</span><span class="sxs-lookup"><span data-stu-id="177db-134">ATP can be used with any SMTP mail transfer agent, such as Microsoft Exchange Server.</span></span> <span data-ttu-id="177db-135">有关 ATP 支持的操作系统、web 浏览器和语言的信息，请参阅 exchange [Online Protection 中 exchange 管理中心](https://go.microsoft.com/fwlink/p/?LinkId=282381)的 "支持的浏览器" 和 "支持的语言" 部分。</span><span class="sxs-lookup"><span data-stu-id="177db-135">For information about the operating systems, web browsers, and languages that are supported by ATP, see the "Supported browsers" and "Supported languages" sections in [Exchange admin center in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).</span></span>

## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a><span data-ttu-id="177db-136">跨高级威胁防护的功能可用性 (ATP) 计划</span><span class="sxs-lookup"><span data-stu-id="177db-136">Feature availability across Advanced Threat Protection (ATP) plans</span></span>

<span data-ttu-id="177db-p106">下面列出了每个功能。当提到 Exchange Online 时，通常指的是 Office 365 企业版服务系列。</span><span class="sxs-lookup"><span data-stu-id="177db-p106">Each feature is listed below. When Exchange Online is mentioned, it typically refers to the Office 365 Enterprise service family.</span></span>

|<span data-ttu-id="177db-139">**功能**</span><span class="sxs-lookup"><span data-stu-id="177db-139">**Feature**</span></span>|<span data-ttu-id="177db-140">**ATP 计划1**</span><span class="sxs-lookup"><span data-stu-id="177db-140">**ATP Plan 1**</span></span><br><span data-ttu-id="177db-141"> (以前的 ATP 独立) </span><span class="sxs-lookup"><span data-stu-id="177db-141">(formerly ATP standalone)</span></span>|<span data-ttu-id="177db-142">**ATP 计划2**</span><span class="sxs-lookup"><span data-stu-id="177db-142">**ATP Plan 2**</span></span><br><span data-ttu-id="177db-143"> (以前的威胁情报</span><span class="sxs-lookup"><span data-stu-id="177db-143">(formerly Threat Intelligence</span></span> <br><span data-ttu-id="177db-144">独立) </span><span class="sxs-lookup"><span data-stu-id="177db-144">standalone)</span></span>| <span data-ttu-id="177db-145">Microsoft 365 E5/E5 安全</span><span class="sxs-lookup"><span data-stu-id="177db-145">Microsoft 365 E5 / E5 Security</span></span>|
|:-----|:-----|:-----|:-----|
|<span data-ttu-id="177db-146">*配置、保护和检测*</span><span class="sxs-lookup"><span data-stu-id="177db-146">*Configuration, protection, and detection*</span></span>|
|[<span data-ttu-id="177db-147">安全附件</span><span class="sxs-lookup"><span data-stu-id="177db-147">Safe Attachments</span></span>](#safe-attachments)|<span data-ttu-id="177db-148">是</span><span class="sxs-lookup"><span data-stu-id="177db-148">Yes</span></span>|<span data-ttu-id="177db-149">是</span><span class="sxs-lookup"><span data-stu-id="177db-149">Yes</span></span>|<span data-ttu-id="177db-150">是</span><span class="sxs-lookup"><span data-stu-id="177db-150">Yes</span></span>|
|<span data-ttu-id="177db-151">团队中的安全附件</span><span class="sxs-lookup"><span data-stu-id="177db-151">Safe Attachments in Teams</span></span>|<span data-ttu-id="177db-152">是</span><span class="sxs-lookup"><span data-stu-id="177db-152">Yes</span></span>|<span data-ttu-id="177db-153">是</span><span class="sxs-lookup"><span data-stu-id="177db-153">Yes</span></span>|<span data-ttu-id="177db-154">是</span><span class="sxs-lookup"><span data-stu-id="177db-154">Yes</span></span>|
|[<span data-ttu-id="177db-155">安全链接</span><span class="sxs-lookup"><span data-stu-id="177db-155">Safe Links</span></span>](#safe-links)|<span data-ttu-id="177db-156">是</span><span class="sxs-lookup"><span data-stu-id="177db-156">Yes</span></span>|<span data-ttu-id="177db-157">是</span><span class="sxs-lookup"><span data-stu-id="177db-157">Yes</span></span>|<span data-ttu-id="177db-158">是</span><span class="sxs-lookup"><span data-stu-id="177db-158">Yes</span></span>|
|[<span data-ttu-id="177db-159">安全文档</span><span class="sxs-lookup"><span data-stu-id="177db-159">Safe Documents</span></span>](#safe-documents)|<span data-ttu-id="177db-160">否</span><span class="sxs-lookup"><span data-stu-id="177db-160">No</span></span>|<span data-ttu-id="177db-161">否</span><span class="sxs-lookup"><span data-stu-id="177db-161">No</span></span>|<span data-ttu-id="177db-162">是</span><span class="sxs-lookup"><span data-stu-id="177db-162">Yes</span></span>|
|<span data-ttu-id="177db-163">Teams 中安全链接</span><span class="sxs-lookup"><span data-stu-id="177db-163">Safe Links in Teams</span></span>|<span data-ttu-id="177db-164">是</span><span class="sxs-lookup"><span data-stu-id="177db-164">Yes</span></span>|<span data-ttu-id="177db-165">是</span><span class="sxs-lookup"><span data-stu-id="177db-165">Yes</span></span>|<span data-ttu-id="177db-166">是</span><span class="sxs-lookup"><span data-stu-id="177db-166">Yes</span></span>|
|[<span data-ttu-id="177db-167">SharePoint、OneDrive 和 Microsoft 团队的 ATP</span><span class="sxs-lookup"><span data-stu-id="177db-167">ATP for SharePoint, OneDrive and Microsoft Teams</span></span>](#atp-for-sharepoint-onedrive-and-microsoft-teams)|<span data-ttu-id="177db-168">是</span><span class="sxs-lookup"><span data-stu-id="177db-168">Yes</span></span>|<span data-ttu-id="177db-169">是</span><span class="sxs-lookup"><span data-stu-id="177db-169">Yes</span></span>|<span data-ttu-id="177db-170">是</span><span class="sxs-lookup"><span data-stu-id="177db-170">Yes</span></span>|
|[<span data-ttu-id="177db-171">防钓鱼策略</span><span class="sxs-lookup"><span data-stu-id="177db-171">Anti-phishing policies</span></span>](#anti-phishing-policies)|<span data-ttu-id="177db-172">是</span><span class="sxs-lookup"><span data-stu-id="177db-172">Yes</span></span>|<span data-ttu-id="177db-173">是</span><span class="sxs-lookup"><span data-stu-id="177db-173">Yes</span></span>|<span data-ttu-id="177db-174">是</span><span class="sxs-lookup"><span data-stu-id="177db-174">Yes</span></span>|
|[<span data-ttu-id="177db-175">实时报告</span><span class="sxs-lookup"><span data-stu-id="177db-175">Real-time reports</span></span>](#real-time-reports)|<span data-ttu-id="177db-176">是</span><span class="sxs-lookup"><span data-stu-id="177db-176">Yes</span></span>|<span data-ttu-id="177db-177">是</span><span class="sxs-lookup"><span data-stu-id="177db-177">Yes</span></span>|<span data-ttu-id="177db-178">是</span><span class="sxs-lookup"><span data-stu-id="177db-178">Yes</span></span>|
|<span data-ttu-id="177db-179">*自动化、调查、修正和教育*</span><span class="sxs-lookup"><span data-stu-id="177db-179">*Automation, investigation, remediation, and education*</span></span>|
|[<span data-ttu-id="177db-180">威胁跟踪器</span><span class="sxs-lookup"><span data-stu-id="177db-180">Threat Trackers</span></span>](#threat-trackers)|<span data-ttu-id="177db-181">否</span><span class="sxs-lookup"><span data-stu-id="177db-181">No</span></span>|<span data-ttu-id="177db-182">是</span><span class="sxs-lookup"><span data-stu-id="177db-182">Yes</span></span>|<span data-ttu-id="177db-183">是</span><span class="sxs-lookup"><span data-stu-id="177db-183">Yes</span></span>|
|<span data-ttu-id="177db-184">威胁调查 (高级威胁调查) </span><span class="sxs-lookup"><span data-stu-id="177db-184">Threat investigation  (advanced threat investigation)</span></span>|[<span data-ttu-id="177db-185">实时检测</span><span class="sxs-lookup"><span data-stu-id="177db-185">Real-time detections</span></span>](#real-time-detections)|[<span data-ttu-id="177db-186">资源管理器</span><span class="sxs-lookup"><span data-stu-id="177db-186">Explorer</span></span>](#explorer)|[<span data-ttu-id="177db-187">资源管理器</span><span class="sxs-lookup"><span data-stu-id="177db-187">Explorer</span></span>](#explorer)|
|[<span data-ttu-id="177db-188">自动化事件响应</span><span class="sxs-lookup"><span data-stu-id="177db-188">Automated incident response</span></span>](#automated-incident-response)|<span data-ttu-id="177db-189">否</span><span class="sxs-lookup"><span data-stu-id="177db-189">No</span></span>|<span data-ttu-id="177db-190">是</span><span class="sxs-lookup"><span data-stu-id="177db-190">Yes</span></span>|<span data-ttu-id="177db-191">是</span><span class="sxs-lookup"><span data-stu-id="177db-191">Yes</span></span>|
|[<span data-ttu-id="177db-192">攻击模拟器</span><span class="sxs-lookup"><span data-stu-id="177db-192">Attack Simulator</span></span>](#attack-simulator)|<span data-ttu-id="177db-193">否</span><span class="sxs-lookup"><span data-stu-id="177db-193">No</span></span>|<span data-ttu-id="177db-194">是</span><span class="sxs-lookup"><span data-stu-id="177db-194">Yes</span></span>|<span data-ttu-id="177db-195">是</span><span class="sxs-lookup"><span data-stu-id="177db-195">Yes</span></span>|

> [!TIP]
> <span data-ttu-id="177db-196">想要一个可下载的 Office 365 ATP 计划1与计划2之间的差异列表吗？</span><span class="sxs-lookup"><span data-stu-id="177db-196">Want a downloadable list of differences between Office 365 ATP Plan 1 and Plan 2?</span></span> <span data-ttu-id="177db-197">[获取 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。</span><span class="sxs-lookup"><span data-stu-id="177db-197">[Get the PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).</span></span> 

## <a name="advanced-threat-protection-atp-capabilities"></a><span data-ttu-id="177db-198">高级威胁防护 (ATP) 功能</span><span class="sxs-lookup"><span data-stu-id="177db-198">Advanced Threat Protection (ATP) capabilities</span></span>

### <a name="safe-attachments"></a><span data-ttu-id="177db-199">安全附件</span><span class="sxs-lookup"><span data-stu-id="177db-199">Safe Attachments</span></span>

<span data-ttu-id="177db-200">[ATP 安全附件](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) 针对未知恶意软件和病毒提供保护，并提供为期零天的保护，以保护您的邮件系统。</span><span class="sxs-lookup"><span data-stu-id="177db-200">[ATP Safe Attachments](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) protects against unknown malware and viruses, and provides zero-day protection to safeguard your messaging system.</span></span> <span data-ttu-id="177db-201">所有不带有已知的病毒/恶意软件签名的邮件和附件都被路由到一个特殊的环境中，ATP 将在其中使用多种机器学习和分析技术来检测恶意企图。</span><span class="sxs-lookup"><span data-stu-id="177db-201">All messages and attachments that don't have a known virus/malware signature are routed to a special environment where ATP uses a variety of machine learning and analysis techniques to detect malicious intent.</span></span> <span data-ttu-id="177db-202">如果没有检测到可疑的活动，会发布邮件并传递到邮箱中。</span><span class="sxs-lookup"><span data-stu-id="177db-202">If no suspicious activity is detected, the message is released for delivery to the mailbox.</span></span>

> [!NOTE]
> <span data-ttu-id="177db-203">ATP 安全附件扫描发生在 Office 365 数据所在的同一个区域中。</span><span class="sxs-lookup"><span data-stu-id="177db-203">ATP Safe Attachments scanning takes place in the same region where your Office 365 data resides.</span></span> <span data-ttu-id="177db-204">有关数据中心地理位置的详细信息，请参阅 [您的数据位于何处？](https://products.office.com/where-is-your-data-located?geo=All)</span><span class="sxs-lookup"><span data-stu-id="177db-204">For more information about data center geography, see [Where is your data located?](https://products.office.com/where-is-your-data-located?geo=All)</span></span>

### <a name="safe-links"></a><span data-ttu-id="177db-205">安全链接</span><span class="sxs-lookup"><span data-stu-id="177db-205">Safe Links</span></span>

<span data-ttu-id="177db-206">[ATP 安全链接](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)功能主动保护您的用户免受邮件中或 Office 文档中的恶意 url 的攻击。</span><span class="sxs-lookup"><span data-stu-id="177db-206">The [ATP Safe Links](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) feature proactively protects your users from malicious URLs in a message or in an Office document.</span></span> <span data-ttu-id="177db-207">每次选择链接时，将继续提供保护，因为会在访问良好的链接时动态地阻挡恶意链接。</span><span class="sxs-lookup"><span data-stu-id="177db-207">The protection remains every time they select the link, as malicious links are dynamically blocked while good links can be accessed.</span></span>

<span data-ttu-id="177db-208">安全链接可用于以下应用程序中的 Url：</span><span class="sxs-lookup"><span data-stu-id="177db-208">Safe Links is available for URLs in the following apps:</span></span>

- <span data-ttu-id="177db-209">适用于 Windows 或 Mac 的 Microsoft 365 企业版应用程序</span><span class="sxs-lookup"><span data-stu-id="177db-209">Microsoft 365 Apps for enterprise on Windows or Mac</span></span>

- <span data-ttu-id="177db-210">Office for web (Word for web、适用于 web 的 Excel、PowerPoint for web 以及适用于 web 的 OneNote) </span><span class="sxs-lookup"><span data-stu-id="177db-210">Office for the web (Word for the web, Excel for the web, PowerPoint for the web, and OneNote for the web)</span></span>

- <span data-ttu-id="177db-211">Windows 上的 Word、Excel、PowerPoint 和 Visio，以及 iOS 和 Android 设备上的 Office 应用</span><span class="sxs-lookup"><span data-stu-id="177db-211">Word, Excel, PowerPoint, and Visio on Windows, as well as Office apps on iOS and Android devices</span></span>

- <span data-ttu-id="177db-212">Microsoft Teams 频道和聊天</span><span class="sxs-lookup"><span data-stu-id="177db-212">Microsoft Teams channels and chats</span></span>

> [!NOTE]
> <span data-ttu-id="177db-213">用户必须获得 ATP 许可 <sup>\*</sup> ，必须包含在 Atp 安全链接策略中，并且必须在其设备上登录，才能就地保护。</span><span class="sxs-lookup"><span data-stu-id="177db-213">Users must be licensed for ATP<sup>\*</sup>, must be included in ATP Safe Links policies, and must be signed in on their devices for protection to be in place.</span></span>
>
> <span data-ttu-id="177db-214"><sup>\*</sup> 对于组织范围的 ATP 许可证 (例如，ATP_ENTERPRISE_FACULTY) ，无需向单个用户分配 ATP 许可证。</span><span class="sxs-lookup"><span data-stu-id="177db-214"><sup>\*</sup> For organization-wide ATP licenses (for example, ATP_ENTERPRISE_FACULTY), you don't need to assign ATP licenses to individual users.</span></span>
>
> <span data-ttu-id="177db-215">有关 ATP 安全链接保护的详细信息，请参阅 [Atp 安全链接如何处理 Office 文档中的 url](https://docs.microsoft.com/microsoft-365/security/office-365-security/how-atp-safe-links-works#how-atp-safe-links-works-with-urls-in-office-documents)。</span><span class="sxs-lookup"><span data-stu-id="177db-215">For more information about ATP Safe Links protection, see [How ATP Safe Links works with URLs in Office documents](https://docs.microsoft.com/microsoft-365/security/office-365-security/how-atp-safe-links-works#how-atp-safe-links-works-with-urls-in-office-documents).</span></span>

### <a name="safe-documents"></a><span data-ttu-id="177db-216">安全文档</span><span class="sxs-lookup"><span data-stu-id="177db-216">Safe Documents</span></span>

<span data-ttu-id="177db-217">[ATP 安全文档](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs)功能使用[Microsoft Defender 高级威胁防护](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection)来扫描在[受保护视图](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)中打开的文档和文件。</span><span class="sxs-lookup"><span data-stu-id="177db-217">The [ATP Safe Documents](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs) feature uses [Microsoft Defender Advanced Threat Protection](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) to scan documents and files that are opened in [Protected View](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653).</span></span>

<span data-ttu-id="177db-218">开始前，有必要了解什么？</span><span class="sxs-lookup"><span data-stu-id="177db-218">What do you need to know before you begin?</span></span>

- <span data-ttu-id="177db-219">安全文档现在对 Office 版本 2004 () 或更高版本的用户通常可用！</span><span class="sxs-lookup"><span data-stu-id="177db-219">Safe Documents is now generally available to users with Office Version 2004 (12730.x) or greater!</span></span> <span data-ttu-id="177db-220">此功能在默认情况下处于禁用状态，将需要由安全管理员启用。</span><span class="sxs-lookup"><span data-stu-id="177db-220">This feature is off by default and will need to be enabled by the Security Administrator.</span></span>

- <span data-ttu-id="177db-221">此功能仅适用于使用 Microsoft 365 E5 或 Microsoft 365 E5 安全许可证的用户 (不包含在 Office 365 ATP 计划) 中。</span><span class="sxs-lookup"><span data-stu-id="177db-221">This feature is only available to users with the Microsoft 365 E5 or Microsoft 365 E5 Security license (not included in Office 365 ATP plans).</span></span>

- <span data-ttu-id="177db-222">Windows 上的 Word、Excel、PowerPoint 和 Visio，以及 iOS 和 Android 设备上的 Office 应用</span><span class="sxs-lookup"><span data-stu-id="177db-222">Word, Excel, PowerPoint, and Visio on Windows, as well as Office apps on iOS and Android devices</span></span>

- <span data-ttu-id="177db-223">Microsoft Teams 频道和聊天</span><span class="sxs-lookup"><span data-stu-id="177db-223">Microsoft Teams channels and chats</span></span>

> [!NOTE]
> <span data-ttu-id="177db-224">用户必须获得 Microsoft 365 E5 或 Microsoft 365 E5 安全性 <sup>\*</sup> ，必须包含在 ATP 安全文档策略中，并且必须在其设备上登录，才能就地保护。</span><span class="sxs-lookup"><span data-stu-id="177db-224">Users must be licensed for Microsoft 365 E5 or Microsoft 365 E5 Security<sup>\*</sup>, must be included in ATP Safe Documents policies, and must be signed in on their devices for protection to be in place.</span></span>
>
> <span data-ttu-id="177db-225">有关 ATP 安全文档保护的详细信息，请参阅 [Microsoft 365 E5 中的安全文档](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs)。</span><span class="sxs-lookup"><span data-stu-id="177db-225">For more information about ATP Safe Documents protection, see [Safe Documents in Microsoft 365 E5](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs).</span></span>

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a><span data-ttu-id="177db-226">适用于 SharePoint、OneDrive 和 Microsoft Teams 的 ATP</span><span class="sxs-lookup"><span data-stu-id="177db-226">ATP for SharePoint, OneDrive, and Microsoft Teams</span></span>

<span data-ttu-id="177db-227">[SharePoint、OneDrive 和 Microsoft 团队的 ATP](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  可帮助检测和阻止在工作组网站和文档库中被标识为恶意的文件。</span><span class="sxs-lookup"><span data-stu-id="177db-227">[ATP for SharePoint, OneDrive, and Microsoft Teams](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  helps detect and block files that are identified as malicious in team sites and document libraries.</span></span> <span data-ttu-id="177db-228">此外，ATP 安全链接保护现已在 Microsoft 团队频道和聊天中提供。</span><span class="sxs-lookup"><span data-stu-id="177db-228">In addition, ATP Safe Links protection is now available in Microsoft Teams channels and chats.</span></span>

### <a name="anti-phishing-policies"></a><span data-ttu-id="177db-229">防钓鱼策略</span><span class="sxs-lookup"><span data-stu-id="177db-229">Anti-phishing policies</span></span>

<span data-ttu-id="177db-230">[ATP 反网络钓鱼](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) 检查传入的邮件，以指示邮件可能是网络钓鱼尝试。</span><span class="sxs-lookup"><span data-stu-id="177db-230">[ATP anti-phishing](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) checks incoming messages for indicators that a message might be a phishing attempt.</span></span> <span data-ttu-id="177db-231">当用户在 ATP 策略（安全附件、安全链接或防钓鱼）涵盖范围内时，将通过多个可分析邮件的机器学习模型来评估传入的邮件，然后根据配置的策略采取相应操作。</span><span class="sxs-lookup"><span data-stu-id="177db-231">When users are covered by ATP policies (Safe Attachments, Safe Links, or anti-phishing), incoming messages are evaluated by multiple machine learning models that analyze messages and the appropriate action is taken, based on the configured policies.</span></span>

### <a name="real-time-reports"></a><span data-ttu-id="177db-232">实时报告</span><span class="sxs-lookup"><span data-stu-id="177db-232">Real-time reports</span></span>

<span data-ttu-id="177db-233">安全 & 合规性中心中提供的监视功能包括 [实时报告和见解](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) ，使您的安全和合规性能够重点关注高优先级问题，如安全攻击或更高的可疑活动。</span><span class="sxs-lookup"><span data-stu-id="177db-233">Monitoring capabilities available in the Security & Compliance Center include [real-time reports and insights](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) that let your security and compliance administrators focus on high-priority issues, such as security attacks or increased suspicious activity.</span></span> <span data-ttu-id="177db-234">除了突出显示问题区域之外，智能报告和见解还包括用于查看和浏览数据的建议和链接，同时还采取快速操作。</span><span class="sxs-lookup"><span data-stu-id="177db-234">In addition to highlighting problem areas, smart reports and insights include recommendations and links to view and explore data and also take quick actions.</span></span>

### <a name="explorer"></a><span data-ttu-id="177db-235">资源管理器</span><span class="sxs-lookup"><span data-stu-id="177db-235">Explorer</span></span>

<span data-ttu-id="177db-236">资源管理器（也称为威胁资源管理器）是一种实时报告，可让授权用户能够识别和分析最近的威胁。</span><span class="sxs-lookup"><span data-stu-id="177db-236">Explorer (also referred to as Threat Explorer) is a real-time report that lets authorized users identify and analyze recent threats.</span></span> <span data-ttu-id="177db-237">默认情况下，此报告显示过去 7 天的数据；但是，可以修改视图以显示过去 30 天的数据。</span><span class="sxs-lookup"><span data-stu-id="177db-237">By default, this report shows data for the past 7 days; however, views can be modified to show data for the past 30 days.</span></span>

<span data-ttu-id="177db-238">资源管理器包含用于电子邮件和内容) 、提交、网络钓鱼和所有电子邮件的恶意软件 (的视图。</span><span class="sxs-lookup"><span data-stu-id="177db-238">Explorer contains views, such as Malware (for email and content), Submissions, Phish, and All Email.</span></span> <span data-ttu-id="177db-239">若要查看浏览器与实时检测的比较情况，请 [下载此 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。</span><span class="sxs-lookup"><span data-stu-id="177db-239">To see how Explorer compares with real-time detections, [download this PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).</span></span>

<span data-ttu-id="177db-240">有关浏览器 (Office 365 高级威胁防护计划 2) 和实时检测 (在 Office 365 高级威胁防护计划 1) 中的详细信息，请参阅 [威胁资源管理器和实时检测](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)。</span><span class="sxs-lookup"><span data-stu-id="177db-240">For more information about Explorer (in Office 365 Advanced Threat Protection Plan 2) and real-time detections (in Office 365 Advanced Threat Protection Plan 1), see [Threat Explorer and real-time detections](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).</span></span>

### <a name="real-time-detections"></a><span data-ttu-id="177db-241">实时检测</span><span class="sxs-lookup"><span data-stu-id="177db-241">Real-time detections</span></span>

<span data-ttu-id="177db-242">实时检测是一种实时报告，可让授权用户能够识别和分析最近的威胁。</span><span class="sxs-lookup"><span data-stu-id="177db-242">Real-time detections is a real-time report that lets authorized users identify and analyze recent threats.</span></span> <span data-ttu-id="177db-243">此报告与资源管理器类似，默认情况下显示过去 7 天的数据。</span><span class="sxs-lookup"><span data-stu-id="177db-243">Similar to Explorer, by default, this report shows data for the past 7 days.</span></span>

<span data-ttu-id="177db-244">实时检测包含用于电子邮件和内容) 、提交和网络钓鱼的恶意软件 (的视图。</span><span class="sxs-lookup"><span data-stu-id="177db-244">Real-time detections contain views, such as Malware (for email and content), Submissions, and Phish.</span></span> <span data-ttu-id="177db-245">若要查看实时检测与资源管理器的比较情况，请 [下载此 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。</span><span class="sxs-lookup"><span data-stu-id="177db-245">To see how real-time detections compare with Explorer, [download this PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).</span></span>

<span data-ttu-id="177db-246">有关浏览器 (Office 365 高级威胁防护计划 2) 和实时检测 (在 Office 365 高级威胁防护计划 1) 中的详细信息，请参阅 [威胁资源管理器 (和实时检测) ](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)。</span><span class="sxs-lookup"><span data-stu-id="177db-246">For more information about Explorer (in Office 365 Advanced Threat Protection Plan 2) and real-time detections (in Office 365 Advanced Threat Protection Plan 1), see [Threat Explorer (and real-time detections)](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).</span></span>

### <a name="threat-trackers"></a><span data-ttu-id="177db-247">威胁跟踪器</span><span class="sxs-lookup"><span data-stu-id="177db-247">Threat Trackers</span></span>

<span data-ttu-id="177db-248">[威胁跟踪](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) 程序是信息小组件和视图，为授权用户提供了可能会影响您的组织的 cybersecurity 问题的智能。</span><span class="sxs-lookup"><span data-stu-id="177db-248">[Threat Trackers](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) are informative widgets and views that provide authorized users with intelligence on cybersecurity issues that might impact your organization.</span></span>

### <a name="automated-incident-response"></a><span data-ttu-id="177db-249">自动化事件响应</span><span class="sxs-lookup"><span data-stu-id="177db-249">Automated incident response</span></span>

<span data-ttu-id="177db-250">Office 365 ATP 计划2中提供的[自动事件响应](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) (空中) 功能使您能够运行自动调查过程，以应对目前存在的已知威胁。</span><span class="sxs-lookup"><span data-stu-id="177db-250">[Automated incident response](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) (AIR) capabilities available in Office 365 ATP Plan 2 enable you to run automated investigation processes in response to well known threats that exist today.</span></span> <span data-ttu-id="177db-251">通过自动执行某些调查任务，安全操作团队可以更高效地运行。</span><span class="sxs-lookup"><span data-stu-id="177db-251">By automated certain investigation tasks, your security operations team can operate more efficiently and effectively.</span></span> <span data-ttu-id="177db-252">安全操作团队批准执行更正操作，如删除恶意电子邮件。</span><span class="sxs-lookup"><span data-stu-id="177db-252">Remediation actions, such as deleting malicious email messages, are taken upon approval by your security operations team.</span></span> <span data-ttu-id="177db-253">若要了解详细信息，请参阅 [Office 365 中的 AIR 的工作原理](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office)。</span><span class="sxs-lookup"><span data-stu-id="177db-253">To learn more, see [How AIR works in Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office).</span></span>

### <a name="attack-simulator"></a><span data-ttu-id="177db-254">攻击模拟器</span><span class="sxs-lookup"><span data-stu-id="177db-254">Attack Simulator</span></span>

<span data-ttu-id="177db-255">[攻击模拟器](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) 允许授权用户在您的组织中运行实际的攻击方案。</span><span class="sxs-lookup"><span data-stu-id="177db-255">[Attack Simulator](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) lets authorized users run realistic attack scenarios in your organization.</span></span> <span data-ttu-id="177db-256">有几种不同类型的攻击可供使用，其中包括显示名称 spear 网络钓鱼攻击、密码喷涂攻击和强力密码攻击。</span><span class="sxs-lookup"><span data-stu-id="177db-256">Several different kinds of attacks are available, including a display name spear-phishing attack, a password-spray attack, and a brute-force password attack.</span></span>
