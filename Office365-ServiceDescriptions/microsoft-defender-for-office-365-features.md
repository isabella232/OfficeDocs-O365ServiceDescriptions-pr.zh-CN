---
title: Microsoft Defender for Office 365 功能服务说明
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: ''
description: 了解 Microsoft Defender for Office 365 中提供Office 365。
ms.openlocfilehash: 620639a2c40d589123ebda33446411533798d2ec
ms.sourcegitcommit: 7ee8775831fd481ab2ef477245d2ae2af98ac2d7
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/30/2021
ms.locfileid: "53204860"
---
# <a name="microsoft-defender-for-office-365-features-service-description"></a><span data-ttu-id="e1ec8-103">Microsoft Defender for Office 365 功能服务说明</span><span class="sxs-lookup"><span data-stu-id="e1ec8-103">Microsoft Defender for Office 365 Features service description</span></span>

## <a name="whats-new-in-microsoft-defender-for-office-365"></a><span data-ttu-id="e1ec8-104">Microsoft Defender for Office 365</span><span class="sxs-lookup"><span data-stu-id="e1ec8-104">What's new in Microsoft Defender for Office 365</span></span>

<span data-ttu-id="e1ec8-105">我们将继续向 Defender for Office 365。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-105">We are continuing to add new features to Defender for Office 365.</span></span> <span data-ttu-id="e1ec8-106">若要了解有关 Defender for Office 365 (或 Microsoft 365 的新功能) ，请参阅以下资源：</span><span class="sxs-lookup"><span data-stu-id="e1ec8-106">To learn more about new features coming to Defender for Office 365 (or Microsoft 365 in general), see the following resources:</span></span>

- [<span data-ttu-id="e1ec8-107">Microsoft 365 路线图</span><span class="sxs-lookup"><span data-stu-id="e1ec8-107">Microsoft 365 Roadmap</span></span>](https://www.microsoft.com/microsoft-365/roadmap)

- [<span data-ttu-id="e1ec8-108">Microsoft Defender for Office 365 中的新增功能 - Office 365 |Microsoft Docs</span><span class="sxs-lookup"><span data-stu-id="e1ec8-108">What's new in Microsoft Defender for Office 365 - Office 365 | Microsoft Docs</span></span>](/microsoft-365/security/office-365-security/whats-new-in-defender-for-office-365)

## <a name="defender-for-office-365-capabilities"></a><span data-ttu-id="e1ec8-109">Defender for Office 365 功能</span><span class="sxs-lookup"><span data-stu-id="e1ec8-109">Defender for Office 365 capabilities</span></span>

### <a name="safe-attachments"></a><span data-ttu-id="e1ec8-110">安全附件</span><span class="sxs-lookup"><span data-stu-id="e1ec8-110">Safe Attachments</span></span>

<span data-ttu-id="e1ec8-111">[保险箱附件](/microsoft-365/security/office-365-security/atp-safe-attachments)可抵御未知恶意软件和病毒的攻击，并提供零日保护来保护邮件系统。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-111">[Safe Attachments](/microsoft-365/security/office-365-security/atp-safe-attachments) protects against unknown malware and viruses, and provides zero-day protection to safeguard your messaging system.</span></span> <span data-ttu-id="e1ec8-112">所有没有已知病毒/恶意软件签名的邮件和附件将路由到 Defender for Office 365 使用各种机器学习和分析技术检测恶意意图的特殊环境。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-112">All messages and attachments that don't have a known virus/malware signature are routed to a special environment where Defender for Office 365 uses a variety of machine learning and analysis techniques to detect malicious intent.</span></span> <span data-ttu-id="e1ec8-113">如果没有检测到可疑的活动，会发布邮件并传递到邮箱中。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-113">If no suspicious activity is detected, the message is released for delivery to the mailbox.</span></span>

> [!NOTE]
> <span data-ttu-id="e1ec8-114">保险箱附件扫描发生在数据所在的同一Office 365区域。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-114">Safe Attachments scanning takes place in the same region where your Office 365 data resides.</span></span> <span data-ttu-id="e1ec8-115">有关数据中心地理位置的信息，请参阅 [数据所在的位置？](/microsoft-365/enterprise/o365-data-locations)</span><span class="sxs-lookup"><span data-stu-id="e1ec8-115">For more information about data center geography, see [Where is your data located?](/microsoft-365/enterprise/o365-data-locations)</span></span>

### <a name="safe-links"></a><span data-ttu-id="e1ec8-116">安全链接</span><span class="sxs-lookup"><span data-stu-id="e1ec8-116">Safe Links</span></span>

<span data-ttu-id="e1ec8-117">["保险箱链接](/microsoft-365/security/office-365-security/atp-safe-links)"功能可主动保护用户免受邮件或电子邮件文档中的恶意OFFICE攻击。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-117">The [Safe Links](/microsoft-365/security/office-365-security/atp-safe-links) feature proactively protects your users from malicious URLs in a message or in an Office document.</span></span> <span data-ttu-id="e1ec8-118">每次选择链接时，将继续提供保护，因为会在访问良好的链接时动态地阻挡恶意链接。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-118">The protection remains every time they select the link, as malicious links are dynamically blocked while good links can be accessed.</span></span>

<span data-ttu-id="e1ec8-119">安全链接可用于以下应用中的 URL：</span><span class="sxs-lookup"><span data-stu-id="e1ec8-119">Safe Links is available for URLs in the following apps:</span></span>

- <span data-ttu-id="e1ec8-120">Microsoft 365 企业应用版或 Mac Windows上</span><span class="sxs-lookup"><span data-stu-id="e1ec8-120">Microsoft 365 Apps for enterprise on Windows or Mac</span></span>

- <span data-ttu-id="e1ec8-121">Office web 版（Word 网页版、Excel 网页版、PowerPoint 网页版、OneNote 网页版）</span><span class="sxs-lookup"><span data-stu-id="e1ec8-121">Office for the web (Word for the web, Excel for the web, PowerPoint for the web, and OneNote for the web)</span></span>

- <span data-ttu-id="e1ec8-122">Word、Excel 和 PowerPoint Windows</span><span class="sxs-lookup"><span data-stu-id="e1ec8-122">Word, Excel, and PowerPoint on Windows</span></span>

- <span data-ttu-id="e1ec8-123">Microsoft Teams 频道和聊天</span><span class="sxs-lookup"><span data-stu-id="e1ec8-123">Microsoft Teams channels and chats</span></span>

> [!NOTE]
> <span data-ttu-id="e1ec8-124">用户必须获得 Defender for Office 365 的许可，必须包含在 保险箱 链接策略中，并且必须登录到其设备，以便保护 <sup>\*</sup> 就位。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-124">Users must be licensed for Defender for Office 365<sup>\*</sup>, must be included in Safe Links policies, and must be signed in on their devices for protection to be in place.</span></span>
>
> <span data-ttu-id="e1ec8-125"><sup>\*</sup>对于组织范围内的 Defender Office 365许可证 (例如，ATP_ENTERPRISE_FACULTY) ，你无需为单个用户分配适用于 Office 365 的 Defender。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-125"><sup>\*</sup> For organization-wide Defender for Office 365 licenses (for example, ATP_ENTERPRISE_FACULTY), you don't need to assign Defender for Office 365 licenses to individual users.</span></span>
>
> <span data-ttu-id="e1ec8-126">有关链接保护保险箱，请参阅 microsoft Defender[保险箱中的链接Office 365。](/microsoft-365/security/office-365-security/atp-safe-links)</span><span class="sxs-lookup"><span data-stu-id="e1ec8-126">For more information about Safe Links protection, see [Safe Links in Microsoft Defender for Office 365](/microsoft-365/security/office-365-security/atp-safe-links).</span></span>

### <a name="safe-documents"></a><span data-ttu-id="e1ec8-127">安全文档</span><span class="sxs-lookup"><span data-stu-id="e1ec8-127">Safe Documents</span></span>

<span data-ttu-id="e1ec8-128">["保险箱文档](/microsoft-365/security/office-365-security/safe-docs)"功能使用[Microsoft Defender for Endpoint](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection)扫描在受保护视图中[打开的文档和文件](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-128">The [Safe Documents](/microsoft-365/security/office-365-security/safe-docs) feature uses [Microsoft Defender for Endpoint](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) to scan documents and files that are opened in [Protected View](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653).</span></span>

<span data-ttu-id="e1ec8-129">开始前，有必要了解什么？</span><span class="sxs-lookup"><span data-stu-id="e1ec8-129">What do you need to know before you begin?</span></span>

- <span data-ttu-id="e1ec8-130">保险箱现在，具有 2004 Office 12730.x (12730.x) 用户可以使用文档！</span><span class="sxs-lookup"><span data-stu-id="e1ec8-130">Safe Documents is now generally available to users with Office Version 2004 (12730.x) or greater!</span></span> <span data-ttu-id="e1ec8-131">默认情况下，此功能已关闭，并且需要由安全管理员启用。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-131">This feature is off by default and will need to be enabled by the Security Administrator.</span></span>

- <span data-ttu-id="e1ec8-132">此功能仅适用于拥有 Microsoft 365 E5 或 Microsoft 365 E5 安全性 许可证 (未包含在 Defender for Office 365 计划) 。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-132">This feature is only available to users with the Microsoft 365 E5 or Microsoft 365 E5 Security license (not included in Defender for Office 365 plans).</span></span>

- <span data-ttu-id="e1ec8-133">Word、Excel 和 PowerPoint Windows</span><span class="sxs-lookup"><span data-stu-id="e1ec8-133">Word, Excel, and PowerPoint on Windows</span></span>

- <span data-ttu-id="e1ec8-134">Microsoft Teams 频道和聊天</span><span class="sxs-lookup"><span data-stu-id="e1ec8-134">Microsoft Teams channels and chats</span></span>

> [!NOTE]
> <span data-ttu-id="e1ec8-135">用户必须获得 Microsoft 365 E5 或 Microsoft 365 E5 安全性 的许可，并且必须包含在 保险箱 文档策略中，并且必须登录其设备，保护 <sup>\*</sup> 就位。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-135">Users must be licensed for Microsoft 365 E5 or Microsoft 365 E5 Security<sup>\*</sup>, must be included in Safe Documents policies, and must be signed in on their devices for protection to be in place.</span></span>
>
> <span data-ttu-id="e1ec8-136">有关文档保护保险箱，请参阅 保险箱 Documents [in Microsoft 365 E5。](/microsoft-365/security/office-365-security/safe-docs)</span><span class="sxs-lookup"><span data-stu-id="e1ec8-136">For more information about Safe Documents protection, see [Safe Documents in Microsoft 365 E5](/microsoft-365/security/office-365-security/safe-docs).</span></span>

### <a name="protection-for-sharepoint-onedrive-and-microsoft-teams"></a><span data-ttu-id="e1ec8-137">保护SharePoint、OneDrive和Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="e1ec8-137">Protection for SharePoint, OneDrive, and Microsoft Teams</span></span>

<span data-ttu-id="e1ec8-138">[对 SharePoint、OneDrive](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)和 Microsoft Teams 的保护可帮助检测和阻止在团队网站和文档库中被标识为恶意的文件。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-138">[Protection for SharePoint, OneDrive, and Microsoft Teams](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) helps detect and block files that are identified as malicious in team sites and document libraries.</span></span> <span data-ttu-id="e1ec8-139">此外，保险箱频道和聊天中现在Microsoft Teams链接保护。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-139">In addition, Safe Links protection is now available in Microsoft Teams channels and chats.</span></span>

### <a name="anti-phishing-policies"></a><span data-ttu-id="e1ec8-140">防钓鱼策略</span><span class="sxs-lookup"><span data-stu-id="e1ec8-140">Anti-phishing policies</span></span>

<span data-ttu-id="e1ec8-141">[防钓鱼功能](/microsoft-365/security/office-365-security/atp-anti-phishing) 检查传入邮件，以指示邮件可能是网络钓鱼尝试。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-141">[Anti-phishing](/microsoft-365/security/office-365-security/atp-anti-phishing) checks incoming messages for indicators that a message might be a phishing attempt.</span></span> <span data-ttu-id="e1ec8-142">当用户被 Office 365 (保险箱 策略（附件、保险箱 链接或防钓鱼) ）的 Defender 覆盖时，传入邮件由分析邮件的多个机器学习模型进行评估，并基于配置的策略执行相应的操作。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-142">When users are covered by Defender for Office 365 policies (Safe Attachments, Safe Links, or anti-phishing), incoming messages are evaluated by multiple machine learning models that analyze messages and the appropriate action is taken, based on the configured policies.</span></span>

### <a name="real-time-reports"></a><span data-ttu-id="e1ec8-143">实时报告</span><span class="sxs-lookup"><span data-stu-id="e1ec8-143">Real-time reports</span></span>

<span data-ttu-id="e1ec8-144">安全与合规中心提供的监视[](https://protection.office.com)功能&实时报告和见解，让安全[](/microsoft-365/security/office-365-security/view-reports-for-atp)与合规管理员专注于高优先级问题，如安全攻击或可疑活动增加。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-144">Monitoring capabilities available in the [Security & Compliance Center](https://protection.office.com) include [real-time reports and insights](/microsoft-365/security/office-365-security/view-reports-for-atp) that let your security and compliance administrators focus on high-priority issues, such as security attacks or increased suspicious activity.</span></span> <span data-ttu-id="e1ec8-145">除了突出显示问题区域外，智能报告和见解还包括用于查看和浏览数据的建议和链接，以及快速操作。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-145">In addition to highlighting problem areas, smart reports and insights include recommendations and links to view and explore data and also take quick actions.</span></span>

### <a name="threat-explorer"></a><span data-ttu-id="e1ec8-146">威胁资源管理器</span><span class="sxs-lookup"><span data-stu-id="e1ec8-146">Threat Explorer</span></span>

<span data-ttu-id="e1ec8-147">威胁 (浏览器也称为资源管理器) 是一个实时报告，可让授权用户识别和分析最近的威胁。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-147">Threat Explorer (also referred to as Explorer) is a real-time report that lets authorized users identify and analyze recent threats.</span></span> <span data-ttu-id="e1ec8-148">默认情况下，此报告显示过去七天的数据;但是，可以修改视图以显示过去 30 天的数据。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-148">By default, this report shows data for the past seven days; however, views can be modified to show data for the past 30 days.</span></span>

<span data-ttu-id="e1ec8-149">资源管理器包含诸如电子邮件和内容 (、提交、网络钓鱼) 所有电子邮件的恶意软件策略等视图。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-149">Explorer contains views, such as Malware (for email and content), Submissions, Phish, and All Email.</span></span> <span data-ttu-id="e1ec8-150">若要了解资源管理器与实时检测的比较， [请下载此 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-150">To see how Explorer compares with real-time detections, [download this PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).</span></span>

<span data-ttu-id="e1ec8-151">有关 Microsoft Defender for Office 365 计划 2) 中的资源管理器 (以及 Microsoft Defender for Office 365 计划 1) 中的实时检测 (，请参阅威胁资源管理器和实时[检测。](/microsoft-365/security/office-365-security/threat-explorer)</span><span class="sxs-lookup"><span data-stu-id="e1ec8-151">For more information about Explorer (in Microsoft Defender for Office 365 Plan 2) and real-time detections (in Microsoft Defender for Office 365 Plan 1), see [Threat Explorer and real-time detections](/microsoft-365/security/office-365-security/threat-explorer).</span></span>

### <a name="real-time-detections"></a><span data-ttu-id="e1ec8-152">实时检测</span><span class="sxs-lookup"><span data-stu-id="e1ec8-152">Real-time detections</span></span>

<span data-ttu-id="e1ec8-153">实时检测是一种实时报告，可让授权用户能够识别和分析最近的威胁。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-153">Real-time detections is a real-time report that lets authorized users identify and analyze recent threats.</span></span> <span data-ttu-id="e1ec8-154">与资源管理器类似，默认情况下，此报告显示过去七天的数据。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-154">Similar to Explorer, by default, this report shows data for the past seven days.</span></span>

<span data-ttu-id="e1ec8-155">实时检测包含视图，如电子邮件 (、提交和网络钓鱼) 恶意软件。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-155">Real-time detections contain views, such as Malware (for email and content), Submissions, and Phish.</span></span> <span data-ttu-id="e1ec8-156">若要了解实时检测与资源管理器的对比， [请下载此 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-156">To see how real-time detections compare with Explorer, [download this PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).</span></span>

<span data-ttu-id="e1ec8-157">有关 Microsoft Defender for Office 365 计划 2) 中的资源管理器 (以及 Microsoft Defender for Office 365 计划 1) 中的实时检测 (，请参阅威胁资源管理器和实时[检测。](/microsoft-365/security/office-365-security/threat-explorer)</span><span class="sxs-lookup"><span data-stu-id="e1ec8-157">For more information about Explorer (in Microsoft Defender for Office 365 Plan 2) and real-time detections (in Microsoft Defender for Office 365 Plan 1), see [Threat Explorer and real-time detections](/microsoft-365/security/office-365-security/threat-explorer).</span></span>

### <a name="threat-trackers"></a><span data-ttu-id="e1ec8-158">威胁跟踪器</span><span class="sxs-lookup"><span data-stu-id="e1ec8-158">Threat Trackers</span></span>

<span data-ttu-id="e1ec8-159">[威胁跟踪](/microsoft-365/security/office-365-security/threat-trackers) 器是信息小组件和视图，可为授权用户提供可能会影响组织的网络安全问题智能。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-159">[Threat Trackers](/microsoft-365/security/office-365-security/threat-trackers) are informative widgets and views that provide authorized users with intelligence on cybersecurity issues that might impact your organization.</span></span>

### <a name="automated-investigation--response"></a><span data-ttu-id="e1ec8-160">自动调查和&响应</span><span class="sxs-lookup"><span data-stu-id="e1ec8-160">Automated investigation & response</span></span>

<span data-ttu-id="e1ec8-161">Office 365 自动调查[&](/microsoft-365/security/office-365-security/office-365-air) () 计划 2 中提供的 AIR) 功能，让你可以运行自动调查流程，以响应当今存在的已知威胁。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-161">[Automated investigation & response](/microsoft-365/security/office-365-security/office-365-air) (AIR) capabilities available in Defender for Office 365 Plan 2 let you run automated investigation processes in response to well-known threats that exist today.</span></span> <span data-ttu-id="e1ec8-162">通过自动执行某些调查任务，安全运营团队可以更高效地操作。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-162">By automating certain investigation tasks, your security operations team can operate more efficiently and effectively.</span></span> <span data-ttu-id="e1ec8-163">安全运营团队批准后，将执行修正操作，如删除恶意电子邮件。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-163">Remediation actions, such as deleting malicious email messages, are taken upon approval by your security operations team.</span></span> <span data-ttu-id="e1ec8-164">若要了解更多信息，请参阅[AIR 在 Office 365 中Office 365。](/microsoft-365/security/office-365-security/automated-investigation-response-office)</span><span class="sxs-lookup"><span data-stu-id="e1ec8-164">To learn more, see [How AIR works in Office 365](/microsoft-365/security/office-365-security/automated-investigation-response-office).</span></span>

### <a name="attack-simulation-training"></a><span data-ttu-id="e1ec8-165">攻击模拟培训</span><span class="sxs-lookup"><span data-stu-id="e1ec8-165">Attack simulation training</span></span>

<span data-ttu-id="e1ec8-166">[攻击模拟培训](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) 是一种智能社交风险管理工具，可自动创建和管理网络钓鱼模拟。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-166">[Attack simulation training](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) is an intelligent social risk management tool that automates the creation and management of phishing simulations.</span></span> <span data-ttu-id="e1ec8-167">模拟通过使用真实的网络钓鱼欺诈和超目标培训来更改员工行为，帮助客户检测、确定钓鱼风险优先级并修正这些风险。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-167">Simulations help customers detect, prioritize, and remediate phishing risks by using real world phish lures and hyper-targeted training to change employee behaviors.</span></span>

- <span data-ttu-id="e1ec8-168">攻击模拟培训现已在 WW 中提供，GCC (将于 GCC年 6 月 21 日) 。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-168">Attack simulation training is now available in WW and GCC (will be in GCC from June 21).</span></span>
- <span data-ttu-id="e1ec8-169">若要详细了解如何开始使用，请参阅使用 [攻击模拟培训入门](/microsoft-365/security/office-365-security/attack-simulation-training-get-started)。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-169">For more information on how to get started, see [Get started using Attack simulation training](/microsoft-365/security/office-365-security/attack-simulation-training-get-started).</span></span>
- <span data-ttu-id="e1ec8-170">应用去武器化的实际网络钓鱼有效负载的各种攻击技术可用于复制实际攻击者行为，使网络钓鱼模拟相关。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-170">Various attack techniques that apply de-weaponized, real-world phish payloads are available that replicate real world attacker behavior to make phishing simulations relevant.</span></span>
- <span data-ttu-id="e1ec8-171">此服务适用于拥有 Microsoft 365 E5、Office 365 E5 或 Microsoft Defender for Office 365 计划[2](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2)许可证的组织。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-171">This service is available to organizations that have either Microsoft 365 E5, Office 365 E5, or [Microsoft Defender for Office 365 Plan 2](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2) licenses.</span></span> <span data-ttu-id="e1ec8-172">一部分功能作为试用版提供给 E3 客户。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-172">A subset of capabilities is offered to E3 customers as a trial.</span></span>
- <span data-ttu-id="e1ec8-173">若要了解更多信息并尝试模拟，请参阅 [模拟网络钓鱼攻击](/microsoft-365/security/office-365-security/attack-simulation-training)。</span><span class="sxs-lookup"><span data-stu-id="e1ec8-173">To learn more and try out a simulation, see [Simulate a phishing attack](/microsoft-365/security/office-365-security/attack-simulation-training).</span></span>