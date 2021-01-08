---
title: Microsoft Defender for Office 365 服务说明
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
description: Microsoft Defender for Office 365 是一种基于云的电子邮件筛选服务，它通过提供强大的零日保护来帮助组织抵御未知恶意软件和病毒，并包括实时保护组织免受恶意链接危害的功能。
ms.openlocfilehash: fd2869eb98b64fca4f241339497486a392815402
ms.sourcegitcommit: bab0eaae59d5c801f88eadbd29fd0d16de387c82
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 01/07/2021
ms.locfileid: "49780006"
---
# <a name="microsoft-defender-for-office-365-service-description"></a><span data-ttu-id="fe030-103">Microsoft Defender for Office 365 服务说明</span><span class="sxs-lookup"><span data-stu-id="fe030-103">Microsoft Defender for Office 365 service description</span></span>

<span data-ttu-id="fe030-104">Microsoft Defender for Office 365 是一种基于云的电子邮件筛选服务，它通过提供强大的零日保护来帮助组织抵御未知恶意软件和病毒，并包括实时保护组织免受恶意链接危害的功能。</span><span class="sxs-lookup"><span data-stu-id="fe030-104">Microsoft Defender for Office 365 is a cloud-based email filtering service that helps protect your organization against unknown malware and viruses by providing robust zero-day protection, and includes features to safeguard your organization from harmful links in real time.</span></span> <span data-ttu-id="fe030-105">Defender for Office 365 具有丰富的报告和 URL 跟踪功能，使管理员能够深入了解组织中发生的攻击类型。</span><span class="sxs-lookup"><span data-stu-id="fe030-105">Defender for Office 365 has rich reporting and URL trace capabilities that give administrators insight into the kind of attacks happening in your organization.</span></span>

<span data-ttu-id="fe030-106">以下是可以使用适用于 Office 365 的 Defender 进行邮件保护的主要方法：</span><span class="sxs-lookup"><span data-stu-id="fe030-106">The following are the primary ways you can use Defender for Office 365 for message protection:</span></span>

- <span data-ttu-id="fe030-107">在 Defender for Office 365 仅筛选方案中，Defender for Office 365 为本地 Exchange Server 环境或其他任何本地 SMTP 电子邮件解决方案提供基于云的电子邮件保护。</span><span class="sxs-lookup"><span data-stu-id="fe030-107">In a Defender for Office 365 filtering-only scenario, Defender for Office 365 provides cloud-based email protection for your on-premises Exchange Server environment or any other on-premises SMTP email solution.</span></span>

- <span data-ttu-id="fe030-108">可以启用 Defender for Office 365 来保护 Exchange Online 云托管的邮箱。</span><span class="sxs-lookup"><span data-stu-id="fe030-108">Defender for Office 365 can be enabled to protect Exchange Online cloud-hosted mailboxes.</span></span> <span data-ttu-id="fe030-109">若要了解有关 Exchange Online 的更多信息，请参阅 [Exchange Online 服务说明](exchange-online-service-description/exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="fe030-109">To learn more about Exchange Online, see the [Exchange Online service description](exchange-online-service-description/exchange-online-service-description.md).</span></span>

- <span data-ttu-id="fe030-110">在混合部署中，可以将 Defender for Office 365 配置为在将本地邮箱和云邮箱与 Exchange Online Protection 混合用于入站电子邮件筛选时保护邮件环境和控制邮件路由。</span><span class="sxs-lookup"><span data-stu-id="fe030-110">In a hybrid deployment, Defender for Office 365 can be configured to protect your messaging environment and control mail routing when you have a mix of on-premises and cloud mailboxes with Exchange Online Protection for inbound email filtering.</span></span>

## <a name="microsoft-defender-for-office-365-availability"></a><span data-ttu-id="fe030-111">Microsoft Defender for Office 365 可用性</span><span class="sxs-lookup"><span data-stu-id="fe030-111">Microsoft Defender for Office 365 availability</span></span>

<span data-ttu-id="fe030-112">Defender for Office 365 计划 2 包含在 Office 365 E5、Office 365 A5 和 Microsoft 365 E5 中。</span><span class="sxs-lookup"><span data-stu-id="fe030-112">Defender for Office 365 Plan 2 is included in Office 365 E5, Office 365 A5, and Microsoft 365 E5.</span></span> <span data-ttu-id="fe030-113">Microsoft 365 商业高级版中包含 Defender for Office 365 计划 1。</span><span class="sxs-lookup"><span data-stu-id="fe030-113">Defender for Office 365 Plan 1 is included in Microsoft 365 Business Premium.</span></span>

<span data-ttu-id="fe030-114">你可以将 Defender for Office 365 添加到以下 Exchange 和 Microsoft 365 订阅计划：</span><span class="sxs-lookup"><span data-stu-id="fe030-114">You can add Defender for Office 365 to the following Exchange and Microsoft 365 subscription plans:</span></span>

- <span data-ttu-id="fe030-115">Exchange Online 计划 1</span><span class="sxs-lookup"><span data-stu-id="fe030-115">Exchange Online Plan 1</span></span>

- <span data-ttu-id="fe030-116">Exchange Online 计划 2</span><span class="sxs-lookup"><span data-stu-id="fe030-116">Exchange Online Plan 2</span></span>

- <span data-ttu-id="fe030-117">Exchange Online Kiosk</span><span class="sxs-lookup"><span data-stu-id="fe030-117">Exchange Online Kiosk</span></span>

- <span data-ttu-id="fe030-118">Exchange Online Protection</span><span class="sxs-lookup"><span data-stu-id="fe030-118">Exchange Online Protection</span></span>

- <span data-ttu-id="fe030-119">Microsoft 365 商业基础版</span><span class="sxs-lookup"><span data-stu-id="fe030-119">Microsoft 365 Business Basic</span></span>

- <span data-ttu-id="fe030-120">Microsoft 365 商业标准版</span><span class="sxs-lookup"><span data-stu-id="fe030-120">Microsoft 365 Business Standard</span></span>

- <span data-ttu-id="fe030-121">Office 365 企业版 E1</span><span class="sxs-lookup"><span data-stu-id="fe030-121">Office 365 Enterprise E1</span></span>

- <span data-ttu-id="fe030-122">Office 365 企业版 E3</span><span class="sxs-lookup"><span data-stu-id="fe030-122">Office 365 Enterprise E3</span></span>

- <span data-ttu-id="fe030-123">Office 365 企业版 F3</span><span class="sxs-lookup"><span data-stu-id="fe030-123">Office 365 Enterprise F3</span></span>

- <span data-ttu-id="fe030-124">Office 365 A1</span><span class="sxs-lookup"><span data-stu-id="fe030-124">Office 365 A1</span></span>

- <span data-ttu-id="fe030-125">Office 365 A3</span><span class="sxs-lookup"><span data-stu-id="fe030-125">Office 365 A3</span></span>

<span data-ttu-id="fe030-126">若要购买 Microsoft Defender for Office 365，请参阅[Microsoft Defender for Office 365。](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)</span><span class="sxs-lookup"><span data-stu-id="fe030-126">To buy Microsoft Defender for Office 365, see [Microsoft Defender for Office 365](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).</span></span>

<span data-ttu-id="fe030-127">若要跨计划比较功能，请参阅[](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409)用于支持企业以及使用[Microsoft 365](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans)转换企业的强大工具。</span><span class="sxs-lookup"><span data-stu-id="fe030-127">To compare features across plans, see [Powerful tools to support your enterprise](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) and [Transform your enterprise with Microsoft 365](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans).</span></span>

## <a name="whats-new-in-microsoft-defender-for-office-365"></a><span data-ttu-id="fe030-128">Microsoft Defender for Office 365 的新增功能</span><span class="sxs-lookup"><span data-stu-id="fe030-128">What's new in Microsoft Defender for Office 365</span></span>

<span data-ttu-id="fe030-129">我们将继续向 Defender for Office 365 添加新功能。</span><span class="sxs-lookup"><span data-stu-id="fe030-129">We are continuing to add new features to Defender for Office 365.</span></span> <span data-ttu-id="fe030-130">若要了解有关适用于 Office 365 (Defender 或 Microsoft 365 的新功能) ，请参阅以下资源：</span><span class="sxs-lookup"><span data-stu-id="fe030-130">To learn more about new features coming to Defender for Office 365 (or Microsoft 365 in general), see the following resources:</span></span>

- [<span data-ttu-id="fe030-131">Microsoft 365 路线图</span><span class="sxs-lookup"><span data-stu-id="fe030-131">Microsoft 365 Roadmap</span></span>](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [<span data-ttu-id="fe030-132">Microsoft Defender for Office 365 的新增功能</span><span class="sxs-lookup"><span data-stu-id="fe030-132">What's new in Microsoft Defender for Office 365</span></span>](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a><span data-ttu-id="fe030-133">Microsoft Defender for Office 365 的要求</span><span class="sxs-lookup"><span data-stu-id="fe030-133">Requirements for Microsoft Defender for Office 365</span></span>

<span data-ttu-id="fe030-134">Defender for Office 365 可以与任意 SMTP 邮件传输代理（如 Microsoft Exchange Server） 一Microsoft Exchange Server。</span><span class="sxs-lookup"><span data-stu-id="fe030-134">Defender for Office 365 can be used with any SMTP mail transfer agent, such as Microsoft Exchange Server.</span></span> <span data-ttu-id="fe030-135">有关适用于 Office 365 的 Defender 支持的操作系统、Web 浏览器和语言的信息，请参阅 [Exchange Online Protection 中 Exchange](https://go.microsoft.com/fwlink/p/?LinkId=282381)管理中心中的"支持的浏览器"和"支持的语言"部分。</span><span class="sxs-lookup"><span data-stu-id="fe030-135">For information about the operating systems, web browsers, and languages that are supported by Defender for Office 365, see the "Supported browsers" and "Supported languages" sections in [Exchange admin center in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).</span></span>

## <a name="feature-availability-across-defender-for-office-365-plans"></a><span data-ttu-id="fe030-136">跨 Defender for Office 365 计划的功能可用性</span><span class="sxs-lookup"><span data-stu-id="fe030-136">Feature availability across Defender for Office 365 plans</span></span>

<span data-ttu-id="fe030-137">下面列出了每个功能。</span><span class="sxs-lookup"><span data-stu-id="fe030-137">Each feature is listed below.</span></span> <span data-ttu-id="fe030-138">当提到 Exchange Online 时，通常指的是 Office 365 企业版服务系列。</span><span class="sxs-lookup"><span data-stu-id="fe030-138">When Exchange Online is mentioned, it typically refers to the Office 365 Enterprise service family.</span></span><br><br>

| <span data-ttu-id="fe030-139">功能</span><span class="sxs-lookup"><span data-stu-id="fe030-139">Feature</span></span> | <span data-ttu-id="fe030-140">Defender for Office 365 计划 1</span><span class="sxs-lookup"><span data-stu-id="fe030-140">Defender for Office 365 Plan 1</span></span> | <span data-ttu-id="fe030-141">Defender for Office 365 计划 2</span><span class="sxs-lookup"><span data-stu-id="fe030-141">Defender for Office 365 Plan 2</span></span> | <span data-ttu-id="fe030-142">Microsoft 365 E5 /E5 安全</span><span class="sxs-lookup"><span data-stu-id="fe030-142">Microsoft 365 E5 / E5 Security</span></span>|
|:-----|:-----|:-----|:-----|
|<span data-ttu-id="fe030-143">*配置、保护和检测*</span><span class="sxs-lookup"><span data-stu-id="fe030-143">*Configuration, protection, and detection*</span></span>|
|[<span data-ttu-id="fe030-144">安全附件</span><span class="sxs-lookup"><span data-stu-id="fe030-144">Safe Attachments</span></span>](#safe-attachments)|<span data-ttu-id="fe030-145">是</span><span class="sxs-lookup"><span data-stu-id="fe030-145">Yes</span></span>|<span data-ttu-id="fe030-146">是</span><span class="sxs-lookup"><span data-stu-id="fe030-146">Yes</span></span>|<span data-ttu-id="fe030-147">是</span><span class="sxs-lookup"><span data-stu-id="fe030-147">Yes</span></span>|
|<span data-ttu-id="fe030-148">Teams 中的安全附件</span><span class="sxs-lookup"><span data-stu-id="fe030-148">Safe Attachments in Teams</span></span>|<span data-ttu-id="fe030-149">是</span><span class="sxs-lookup"><span data-stu-id="fe030-149">Yes</span></span>|<span data-ttu-id="fe030-150">是</span><span class="sxs-lookup"><span data-stu-id="fe030-150">Yes</span></span>|<span data-ttu-id="fe030-151">是</span><span class="sxs-lookup"><span data-stu-id="fe030-151">Yes</span></span>|
|[<span data-ttu-id="fe030-152">安全链接</span><span class="sxs-lookup"><span data-stu-id="fe030-152">Safe Links</span></span>](#safe-links)|<span data-ttu-id="fe030-153">是</span><span class="sxs-lookup"><span data-stu-id="fe030-153">Yes</span></span>|<span data-ttu-id="fe030-154">是</span><span class="sxs-lookup"><span data-stu-id="fe030-154">Yes</span></span>|<span data-ttu-id="fe030-155">是</span><span class="sxs-lookup"><span data-stu-id="fe030-155">Yes</span></span>|
|[<span data-ttu-id="fe030-156">安全文档</span><span class="sxs-lookup"><span data-stu-id="fe030-156">Safe Documents</span></span>](#safe-documents)|<span data-ttu-id="fe030-157">否</span><span class="sxs-lookup"><span data-stu-id="fe030-157">No</span></span>|<span data-ttu-id="fe030-158">否</span><span class="sxs-lookup"><span data-stu-id="fe030-158">No</span></span>|<span data-ttu-id="fe030-159">是</span><span class="sxs-lookup"><span data-stu-id="fe030-159">Yes</span></span>|
|<span data-ttu-id="fe030-160">Teams 中安全链接</span><span class="sxs-lookup"><span data-stu-id="fe030-160">Safe Links in Teams</span></span>|<span data-ttu-id="fe030-161">是</span><span class="sxs-lookup"><span data-stu-id="fe030-161">Yes</span></span>|<span data-ttu-id="fe030-162">是</span><span class="sxs-lookup"><span data-stu-id="fe030-162">Yes</span></span>|<span data-ttu-id="fe030-163">是</span><span class="sxs-lookup"><span data-stu-id="fe030-163">Yes</span></span>|
|[<span data-ttu-id="fe030-164">适用于 SharePoint、OneDrive 和 Microsoft Teams 的 ATP</span><span class="sxs-lookup"><span data-stu-id="fe030-164">ATP for SharePoint, OneDrive, and Microsoft Teams</span></span>](#atp-for-sharepoint-onedrive-and-microsoft-teams)|<span data-ttu-id="fe030-165">是</span><span class="sxs-lookup"><span data-stu-id="fe030-165">Yes</span></span>|<span data-ttu-id="fe030-166">是</span><span class="sxs-lookup"><span data-stu-id="fe030-166">Yes</span></span>|<span data-ttu-id="fe030-167">是</span><span class="sxs-lookup"><span data-stu-id="fe030-167">Yes</span></span>|
|[<span data-ttu-id="fe030-168">防钓鱼策略</span><span class="sxs-lookup"><span data-stu-id="fe030-168">Anti-phishing policies</span></span>](#anti-phishing-policies)|<span data-ttu-id="fe030-169">是</span><span class="sxs-lookup"><span data-stu-id="fe030-169">Yes</span></span>|<span data-ttu-id="fe030-170">是</span><span class="sxs-lookup"><span data-stu-id="fe030-170">Yes</span></span>|<span data-ttu-id="fe030-171">是</span><span class="sxs-lookup"><span data-stu-id="fe030-171">Yes</span></span>|
|[<span data-ttu-id="fe030-172">实时报告</span><span class="sxs-lookup"><span data-stu-id="fe030-172">Real-time reports</span></span>](#real-time-reports)|<span data-ttu-id="fe030-173">是</span><span class="sxs-lookup"><span data-stu-id="fe030-173">Yes</span></span>|<span data-ttu-id="fe030-174">是</span><span class="sxs-lookup"><span data-stu-id="fe030-174">Yes</span></span>|<span data-ttu-id="fe030-175">是</span><span class="sxs-lookup"><span data-stu-id="fe030-175">Yes</span></span>|
|<span data-ttu-id="fe030-176">*自动化、调查、修正和教育*</span><span class="sxs-lookup"><span data-stu-id="fe030-176">*Automation, investigation, remediation, and education*</span></span>|
|[<span data-ttu-id="fe030-177">威胁跟踪器</span><span class="sxs-lookup"><span data-stu-id="fe030-177">Threat Trackers</span></span>](#threat-trackers)|<span data-ttu-id="fe030-178">否</span><span class="sxs-lookup"><span data-stu-id="fe030-178">No</span></span>|<span data-ttu-id="fe030-179">是</span><span class="sxs-lookup"><span data-stu-id="fe030-179">Yes</span></span>|<span data-ttu-id="fe030-180">是</span><span class="sxs-lookup"><span data-stu-id="fe030-180">Yes</span></span>|
|<span data-ttu-id="fe030-181">威胁调查 (高级威胁调查) </span><span class="sxs-lookup"><span data-stu-id="fe030-181">Threat investigation  (advanced threat investigation)</span></span>|[<span data-ttu-id="fe030-182">实时检测</span><span class="sxs-lookup"><span data-stu-id="fe030-182">Real-time detections</span></span>](#real-time-detections)|[<span data-ttu-id="fe030-183">资源管理器</span><span class="sxs-lookup"><span data-stu-id="fe030-183">Explorer</span></span>](#explorer)|[<span data-ttu-id="fe030-184">资源管理器</span><span class="sxs-lookup"><span data-stu-id="fe030-184">Explorer</span></span>](#explorer)|
|[<span data-ttu-id="fe030-185">自动事件响应</span><span class="sxs-lookup"><span data-stu-id="fe030-185">Automated incident response</span></span>](#automated-incident-response)|<span data-ttu-id="fe030-186">否</span><span class="sxs-lookup"><span data-stu-id="fe030-186">No</span></span>|<span data-ttu-id="fe030-187">是</span><span class="sxs-lookup"><span data-stu-id="fe030-187">Yes</span></span>|<span data-ttu-id="fe030-188">是</span><span class="sxs-lookup"><span data-stu-id="fe030-188">Yes</span></span>|
|[<span data-ttu-id="fe030-189">攻击模拟器</span><span class="sxs-lookup"><span data-stu-id="fe030-189">Attack Simulator</span></span>](#attack-simulator)|<span data-ttu-id="fe030-190">否</span><span class="sxs-lookup"><span data-stu-id="fe030-190">No</span></span>|<span data-ttu-id="fe030-191">是</span><span class="sxs-lookup"><span data-stu-id="fe030-191">Yes</span></span>|<span data-ttu-id="fe030-192">是</span><span class="sxs-lookup"><span data-stu-id="fe030-192">Yes</span></span>|
|<span data-ttu-id="fe030-193">*与 Microsoft 365 Defender 集成*</span><span class="sxs-lookup"><span data-stu-id="fe030-193">*Integration with Microsoft 365 Defender*</span></span>|<span data-ttu-id="fe030-194">否</span><span class="sxs-lookup"><span data-stu-id="fe030-194">No</span></span>|<span data-ttu-id="fe030-195">是</span><span class="sxs-lookup"><span data-stu-id="fe030-195">Yes</span></span>|<span data-ttu-id="fe030-196">是</span><span class="sxs-lookup"><span data-stu-id="fe030-196">Yes</span></span>|

> [!TIP]
> <span data-ttu-id="fe030-197">想要下载 Office 365 计划 1 和计划 2 之间差异的可下载列表？</span><span class="sxs-lookup"><span data-stu-id="fe030-197">Want a downloadable list of differences between Defender for Office 365 Plan 1 and Plan 2?</span></span> <span data-ttu-id="fe030-198">[获取 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。</span><span class="sxs-lookup"><span data-stu-id="fe030-198">[Get the PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).</span></span>

> [!NOTE]
> <span data-ttu-id="fe030-199">如果你的租户只有 Office ATP P2 试用许可证或 Office 365 E5 试用许可证，而 Microsoft 威胁防护没有其他符合条件的许可证，你将无法访问 Microsoft 威胁防护。</span><span class="sxs-lookup"><span data-stu-id="fe030-199">If your tenant has only Office ATP P2 trial license or Office 365 E5 trial license, with no other eligible license for Microsoft Threat Protection, you will not be able to access Microsoft Threat Protection.</span></span> <span data-ttu-id="fe030-200">若要了解有关 MTP 许可证的更多信息，请参阅 <https://docs.microsoft.com/microsoft-365/security/mtp/prerequisites></span><span class="sxs-lookup"><span data-stu-id="fe030-200">To learn more about MTP license, see <https://docs.microsoft.com/microsoft-365/security/mtp/prerequisites></span></span>

## <a name="defender-for-office-365-capabilities"></a><span data-ttu-id="fe030-201">Defender for Office 365 功能</span><span class="sxs-lookup"><span data-stu-id="fe030-201">Defender for Office 365 capabilities</span></span>

### <a name="safe-attachments"></a><span data-ttu-id="fe030-202">安全附件</span><span class="sxs-lookup"><span data-stu-id="fe030-202">Safe Attachments</span></span>

<span data-ttu-id="fe030-203">[安全附件](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) 可抵御未知恶意软件和病毒，并提供零日保护来保护邮件系统。</span><span class="sxs-lookup"><span data-stu-id="fe030-203">[Safe Attachments](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) protects against unknown malware and viruses, and provides zero-day protection to safeguard your messaging system.</span></span> <span data-ttu-id="fe030-204">所有没有已知病毒/恶意软件签名的邮件和附件将路由到 Defender for Office 365 使用各种机器学习和分析技术检测恶意意图的特殊环境。</span><span class="sxs-lookup"><span data-stu-id="fe030-204">All messages and attachments that don't have a known virus/malware signature are routed to a special environment where Defender for Office 365 uses a variety of machine learning and analysis techniques to detect malicious intent.</span></span> <span data-ttu-id="fe030-205">如果没有检测到可疑的活动，会发布邮件并传递到邮箱中。</span><span class="sxs-lookup"><span data-stu-id="fe030-205">If no suspicious activity is detected, the message is released for delivery to the mailbox.</span></span>

> [!NOTE]
> <span data-ttu-id="fe030-206">安全附件扫描发生在 Office 365 数据所在的同一区域。</span><span class="sxs-lookup"><span data-stu-id="fe030-206">Safe Attachments scanning takes place in the same region where your Office 365 data resides.</span></span> <span data-ttu-id="fe030-207">有关数据中心地理位置的信息，请参阅 [数据所在的位置？](https://products.office.com/where-is-your-data-located?geo=All)</span><span class="sxs-lookup"><span data-stu-id="fe030-207">For more information about data center geography, see [Where is your data located?](https://products.office.com/where-is-your-data-located?geo=All)</span></span>

### <a name="safe-links"></a><span data-ttu-id="fe030-208">安全链接</span><span class="sxs-lookup"><span data-stu-id="fe030-208">Safe Links</span></span>

<span data-ttu-id="fe030-209">安全 [链接](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) 功能可主动保护用户免受邮件或 Office 文档中的恶意 URL 的攻击。</span><span class="sxs-lookup"><span data-stu-id="fe030-209">The [Safe Links](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) feature proactively protects your users from malicious URLs in a message or in an Office document.</span></span> <span data-ttu-id="fe030-210">每次选择链接时，将继续提供保护，因为会在访问良好的链接时动态地阻挡恶意链接。</span><span class="sxs-lookup"><span data-stu-id="fe030-210">The protection remains every time they select the link, as malicious links are dynamically blocked while good links can be accessed.</span></span>

<span data-ttu-id="fe030-211">安全链接可用于以下应用中的 URL：</span><span class="sxs-lookup"><span data-stu-id="fe030-211">Safe Links is available for URLs in the following apps:</span></span>

- <span data-ttu-id="fe030-212">Windows 或 Mac 上的 Microsoft 365 企业应用版</span><span class="sxs-lookup"><span data-stu-id="fe030-212">Microsoft 365 Apps for enterprise on Windows or Mac</span></span>

- <span data-ttu-id="fe030-213">Office web 版（Word 网页版、Excel 网页版、PowerPoint 网页版、OneNote 网页版）</span><span class="sxs-lookup"><span data-stu-id="fe030-213">Office for the web (Word for the web, Excel for the web, PowerPoint for the web, and OneNote for the web)</span></span>

- <span data-ttu-id="fe030-214">Windows 上的 Word、Excel 和 PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe030-214">Word, Excel, and PowerPoint on Windows</span></span>

- <span data-ttu-id="fe030-215">Microsoft Teams 频道和聊天</span><span class="sxs-lookup"><span data-stu-id="fe030-215">Microsoft Teams channels and chats</span></span>

> [!NOTE]
> <span data-ttu-id="fe030-216">用户必须获得 Office 365 Defender 许可，必须包含在安全链接策略中，并且必须登录其设备，保护 <sup>\*</sup> 就位。</span><span class="sxs-lookup"><span data-stu-id="fe030-216">Users must be licensed for Defender for Office 365<sup>\*</sup>, must be included in Safe Links policies, and must be signed in on their devices for protection to be in place.</span></span>
>
> <span data-ttu-id="fe030-217"><sup>\*</sup> 对于组织范围内的 Defender for Office 365 许可证 (例如 ATP_ENTERPRISE_FACULTY) ，无需向单个用户分配 Defender for Office 365 许可证。</span><span class="sxs-lookup"><span data-stu-id="fe030-217"><sup>\*</sup> For organization-wide Defender for Office 365 licenses (for example, ATP_ENTERPRISE_FACULTY), you don't need to assign Defender for Office 365 licenses to individual users.</span></span>
>
> <span data-ttu-id="fe030-218">有关安全链接保护详细信息，请参阅 [Microsoft Defender for Office 365 中的安全链接](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)。</span><span class="sxs-lookup"><span data-stu-id="fe030-218">For more information about Safe Links protection, see [Safe Links in Microsoft Defender for Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links).</span></span>

### <a name="safe-documents"></a><span data-ttu-id="fe030-219">安全文档</span><span class="sxs-lookup"><span data-stu-id="fe030-219">Safe Documents</span></span>

<span data-ttu-id="fe030-220">安全 [文档](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs) 功能使用 [Microsoft Defender for Endpoint](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) 扫描在受保护视图中打开 [的文档和文件](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)。</span><span class="sxs-lookup"><span data-stu-id="fe030-220">The [Safe Documents](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs) feature uses [Microsoft Defender for Endpoint](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) to scan documents and files that are opened in [Protected View](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653).</span></span>

<span data-ttu-id="fe030-221">在开始之前，您需要知道什么？</span><span class="sxs-lookup"><span data-stu-id="fe030-221">What do you need to know before you begin?</span></span>

- <span data-ttu-id="fe030-222">安全文档现在通常可供 Office 版本 2004 (12730.x) 或更高！</span><span class="sxs-lookup"><span data-stu-id="fe030-222">Safe Documents is now generally available to users with Office Version 2004 (12730.x) or greater!</span></span> <span data-ttu-id="fe030-223">默认情况下，此功能已关闭，并且需要由安全管理员启用。</span><span class="sxs-lookup"><span data-stu-id="fe030-223">This feature is off by default and will need to be enabled by the Security Administrator.</span></span>

- <span data-ttu-id="fe030-224">此功能仅适用于拥有 Microsoft 365 E5 或 Microsoft 365 E5 安全许可证的用户 (Defender for Office 365 计划未) 。</span><span class="sxs-lookup"><span data-stu-id="fe030-224">This feature is only available to users with the Microsoft 365 E5 or Microsoft 365 E5 Security license (not included in Defender for Office 365 plans).</span></span>

- <span data-ttu-id="fe030-225">Windows 上的 Word、Excel 和 PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe030-225">Word, Excel, and PowerPoint on Windows</span></span>

- <span data-ttu-id="fe030-226">Microsoft Teams 频道和聊天</span><span class="sxs-lookup"><span data-stu-id="fe030-226">Microsoft Teams channels and chats</span></span>

> [!NOTE]
> <span data-ttu-id="fe030-227">用户必须获得 Microsoft 365 E5 或 Microsoft 365 E5 安全许可，必须包含在安全文档策略中，并且必须在其设备上登录，保护就位 <sup>\*</sup> 。</span><span class="sxs-lookup"><span data-stu-id="fe030-227">Users must be licensed for Microsoft 365 E5 or Microsoft 365 E5 Security<sup>\*</sup>, must be included in Safe Documents policies, and must be signed in on their devices for protection to be in place.</span></span>
>
> <span data-ttu-id="fe030-228">有关安全文档保护详细信息，请参阅 [Microsoft 365 E5 中的安全文档](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs)。</span><span class="sxs-lookup"><span data-stu-id="fe030-228">For more information about Safe Documents protection, see [Safe Documents in Microsoft 365 E5](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs).</span></span>

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a><span data-ttu-id="fe030-229">适用于 SharePoint、OneDrive 和 Microsoft Teams 的 ATP</span><span class="sxs-lookup"><span data-stu-id="fe030-229">ATP for SharePoint, OneDrive, and Microsoft Teams</span></span>

<span data-ttu-id="fe030-230">[适用于 SharePoint、OneDrive](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  和 Microsoft Teams 的 ATP 可帮助检测和阻止团队网站和文档库中标识为恶意的文件。</span><span class="sxs-lookup"><span data-stu-id="fe030-230">[ATP for SharePoint, OneDrive, and Microsoft Teams](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  helps detect and block files that are identified as malicious in team sites and document libraries.</span></span> <span data-ttu-id="fe030-231">此外，Microsoft Teams 频道和聊天中现在提供安全链接保护。</span><span class="sxs-lookup"><span data-stu-id="fe030-231">In addition, Safe Links protection is now available in Microsoft Teams channels and chats.</span></span>

### <a name="anti-phishing-policies"></a><span data-ttu-id="fe030-232">防钓鱼策略</span><span class="sxs-lookup"><span data-stu-id="fe030-232">Anti-phishing policies</span></span>

<span data-ttu-id="fe030-233">[防钓鱼功能](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) 检查传入邮件，以识别邮件可能是网络钓鱼尝试的指示器。</span><span class="sxs-lookup"><span data-stu-id="fe030-233">[Anti-phishing](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) checks incoming messages for indicators that a message might be a phishing attempt.</span></span> <span data-ttu-id="fe030-234">当 Defender for Office 365 策略 (安全附件、安全链接或防钓鱼) 涵盖用户时，传入邮件会由多个机器学习模型进行评估，这些模型可分析邮件，并基于配置的策略采取适当的操作。</span><span class="sxs-lookup"><span data-stu-id="fe030-234">When users are covered by Defender for Office 365 policies (Safe Attachments, Safe Links, or anti-phishing), incoming messages are evaluated by multiple machine learning models that analyze messages and the appropriate action is taken, based on the configured policies.</span></span>

### <a name="real-time-reports"></a><span data-ttu-id="fe030-235">实时报告</span><span class="sxs-lookup"><span data-stu-id="fe030-235">Real-time reports</span></span>

<span data-ttu-id="fe030-236">安全与合规中心提供的监视功能包括实时报告和见解，让安全[](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp)与合规管理员专注于高优先级问题，例如安全攻击或可疑活动增加。 &</span><span class="sxs-lookup"><span data-stu-id="fe030-236">Monitoring capabilities available in the Security & Compliance Center include [real-time reports and insights](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) that let your security and compliance administrators focus on high-priority issues, such as security attacks or increased suspicious activity.</span></span> <span data-ttu-id="fe030-237">除了突出显示问题区域外，智能报告和见解还包括查看和浏览数据以及快速操作的建议和链接。</span><span class="sxs-lookup"><span data-stu-id="fe030-237">In addition to highlighting problem areas, smart reports and insights include recommendations and links to view and explore data and also take quick actions.</span></span>

### <a name="explorer"></a><span data-ttu-id="fe030-238">资源管理器</span><span class="sxs-lookup"><span data-stu-id="fe030-238">Explorer</span></span>

<span data-ttu-id="fe030-239">资源管理器（也称为威胁资源管理器）是一种实时报告，可让授权用户能够识别和分析最近的威胁。</span><span class="sxs-lookup"><span data-stu-id="fe030-239">Explorer (also referred to as Threat Explorer) is a real-time report that lets authorized users identify and analyze recent threats.</span></span> <span data-ttu-id="fe030-240">默认情况下，此报告显示过去 7 天的数据；但是，可以修改视图以显示过去 30 天的数据。</span><span class="sxs-lookup"><span data-stu-id="fe030-240">By default, this report shows data for the past 7 days; however, views can be modified to show data for the past 30 days.</span></span>

<span data-ttu-id="fe030-241">资源管理器包含一些视图，如 (电子邮件和内容) 、提交、网络钓鱼以及所有电子邮件。</span><span class="sxs-lookup"><span data-stu-id="fe030-241">Explorer contains views, such as Malware (for email and content), Submissions, Phish, and All Email.</span></span> <span data-ttu-id="fe030-242">若要了解资源管理器与实时检测的比较，[请下载此 PDF。](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)</span><span class="sxs-lookup"><span data-stu-id="fe030-242">To see how Explorer compares with real-time detections, [download this PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).</span></span>

<span data-ttu-id="fe030-243">有关适用于 Office 365 计划 2) 的 Microsoft Defender 中的资源管理器 (和 Microsoft Defender for Office 365 计划 1 (中的实时检测) ，请参阅威胁资源管理器和实时[检测。](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)</span><span class="sxs-lookup"><span data-stu-id="fe030-243">For more information about Explorer (in Microsoft Defender for Office 365 Plan 2) and real-time detections (in Microsoft Defender for Office 365 Plan 1), see [Threat Explorer and real-time detections](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).</span></span>

### <a name="real-time-detections"></a><span data-ttu-id="fe030-244">实时检测</span><span class="sxs-lookup"><span data-stu-id="fe030-244">Real-time detections</span></span>

<span data-ttu-id="fe030-245">实时检测是一种实时报告，可让授权用户能够识别和分析最近的威胁。</span><span class="sxs-lookup"><span data-stu-id="fe030-245">Real-time detections is a real-time report that lets authorized users identify and analyze recent threats.</span></span> <span data-ttu-id="fe030-246">此报告与资源管理器类似，默认情况下显示过去 7 天的数据。</span><span class="sxs-lookup"><span data-stu-id="fe030-246">Similar to Explorer, by default, this report shows data for the past 7 days.</span></span>

<span data-ttu-id="fe030-247">实时检测包含视图，如电子邮件 (、提交和网络钓鱼) 恶意软件。</span><span class="sxs-lookup"><span data-stu-id="fe030-247">Real-time detections contain views, such as Malware (for email and content), Submissions, and Phish.</span></span> <span data-ttu-id="fe030-248">若要了解实时检测与资源管理器的比较，[请下载此 PDF。](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)</span><span class="sxs-lookup"><span data-stu-id="fe030-248">To see how real-time detections compare with Explorer, [download this PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).</span></span>

<span data-ttu-id="fe030-249">有关适用于 Office 365 计划 2) 的 Microsoft Defender 中的资源管理器 (和 Microsoft Defender for Office 365 计划 1 (中的实时检测) ，请参阅威胁资源管理器 (和实时检测[) 。 ](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)</span><span class="sxs-lookup"><span data-stu-id="fe030-249">For more information about Explorer (in Microsoft Defender for Office 365 Plan 2) and real-time detections (in Microsoft Defender for Office 365 Plan 1), see [Threat Explorer (and real-time detections)](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).</span></span>

### <a name="threat-trackers"></a><span data-ttu-id="fe030-250">威胁跟踪器</span><span class="sxs-lookup"><span data-stu-id="fe030-250">Threat Trackers</span></span>

<span data-ttu-id="fe030-251">[威胁跟踪](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) 器是信息小组件和视图，可为授权用户提供可能会影响组织的网络安全问题情报。</span><span class="sxs-lookup"><span data-stu-id="fe030-251">[Threat Trackers](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) are informative widgets and views that provide authorized users with intelligence on cybersecurity issues that might impact your organization.</span></span>

### <a name="automated-incident-response"></a><span data-ttu-id="fe030-252">自动事件响应</span><span class="sxs-lookup"><span data-stu-id="fe030-252">Automated incident response</span></span>

<span data-ttu-id="fe030-253">[通过](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) Defender for Office 365 计划 2 (AIR) 功能提供的自动事件响应，可以运行自动调查流程，以响应当今存在的已知威胁。</span><span class="sxs-lookup"><span data-stu-id="fe030-253">[Automated incident response](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) (AIR) capabilities available in Defender for Office 365 Plan 2 let you run automated investigation processes in response to well known threats that exist today.</span></span> <span data-ttu-id="fe030-254">通过自动执行某些调查任务，安全运营团队可以更高效地运行。</span><span class="sxs-lookup"><span data-stu-id="fe030-254">By automated certain investigation tasks, your security operations team can operate more efficiently and effectively.</span></span> <span data-ttu-id="fe030-255">安全运营团队批准后，将执行修正操作，如删除恶意电子邮件。</span><span class="sxs-lookup"><span data-stu-id="fe030-255">Remediation actions, such as deleting malicious email messages, are taken upon approval by your security operations team.</span></span> <span data-ttu-id="fe030-256">若要了解更多信息，请参阅 [AIR 在 Office 365 中的工作原理](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office)。</span><span class="sxs-lookup"><span data-stu-id="fe030-256">To learn more, see [How AIR works in Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office).</span></span>

### <a name="attack-simulator"></a><span data-ttu-id="fe030-257">攻击模拟器</span><span class="sxs-lookup"><span data-stu-id="fe030-257">Attack Simulator</span></span>

<span data-ttu-id="fe030-258">[攻击模拟器](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) 允许授权用户在组织中运行真实的攻击方案。</span><span class="sxs-lookup"><span data-stu-id="fe030-258">[Attack Simulator](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) lets authorized users run realistic attack scenarios in your organization.</span></span> <span data-ttu-id="fe030-259">提供了几种不同类型的攻击，包括显示名称钓鱼攻击、密码攻击和暴力密码攻击。</span><span class="sxs-lookup"><span data-stu-id="fe030-259">Several different kinds of attacks are available, including a display name spear-phishing attack, a password-spray attack, and a brute-force password attack.</span></span>
