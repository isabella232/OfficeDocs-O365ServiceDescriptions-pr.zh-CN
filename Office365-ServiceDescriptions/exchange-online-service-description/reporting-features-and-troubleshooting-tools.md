---
title: 报告功能和疑难解答工具
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Online 提供了 Exchange 管理中心（EAC）的各种报告功能。
ms.openlocfilehash: f2cc51c9923be8d399fa2837e5b5fabe3117d5ba
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132596"
---
# <a name="reporting-features-and-troubleshooting-tools"></a><span data-ttu-id="7f265-103">报告功能和疑难解答工具</span><span class="sxs-lookup"><span data-stu-id="7f265-103">Reporting features and troubleshooting tools</span></span>

<span data-ttu-id="7f265-104">Microsoft Exchange Online 提供了 Exchange 管理中心（EAC）的各种报告功能。</span><span class="sxs-lookup"><span data-stu-id="7f265-104">Microsoft Exchange Online offers a variety of reporting features both in and out of the Exchange admin center (EAC).</span></span>
  
## <a name="reporting-features"></a><span data-ttu-id="7f265-105">报告功能</span><span class="sxs-lookup"><span data-stu-id="7f265-105">Reporting features</span></span>

<span data-ttu-id="7f265-106">Exchange Online 客户可以通过下载 Excel 报告工作簿或使用 web 服务来访问 Microsoft 365 管理中心中的报告。</span><span class="sxs-lookup"><span data-stu-id="7f265-106">Exchange Online customers can access reports in the Microsoft 365 admin center, by downloading an Excel reporting workbook, or by using web services.</span></span>
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a><span data-ttu-id="7f265-107">Microsoft 365 管理中心中的报告</span><span class="sxs-lookup"><span data-stu-id="7f265-107">Reporting in the Microsoft 365 admin center</span></span>

<span data-ttu-id="7f265-108">Microsoft 365 管理中心中的 "报告" 页面上有报告，其中提供了有关邮箱和组的摘要信息。</span><span class="sxs-lookup"><span data-stu-id="7f265-108">There are reports on the Reports page in the Microsoft 365 admin center that provide summary information about mailboxes and groups.</span></span> <span data-ttu-id="7f265-109">例如，其中有一项报告将列出按天、星期、月份或年份创建和删除的组的数量。</span><span class="sxs-lookup"><span data-stu-id="7f265-109">For example, one report lists the number of groups created and deleted by day, week, month, or year.</span></span> <span data-ttu-id="7f265-110">它还有许多有关新邮箱和已删除邮箱的摘要报告，以及活动和不活动邮箱的摘要报告。</span><span class="sxs-lookup"><span data-stu-id="7f265-110">There are also summary reports for new and deleted mailboxes, and active and inactive mailboxes.</span></span> 
  
<span data-ttu-id="7f265-111">此外，Microsoft 365 管理中心中的 "报告" 页面包含邮件数据报告，其中提供了有关邮件流量、垃圾邮件和恶意软件检测以及受 Exchange 传输规则或数据丢失防护（DLP）策略影响的邮件的信息。</span><span class="sxs-lookup"><span data-stu-id="7f265-111">Additionally, the Reports page in the Microsoft 365 admin center contains messaging data reports, which provide information about message traffic, spam and malware detections, and messages affected by Exchange Transport Rules or Data Loss Prevention (DLP) policies.</span></span> <span data-ttu-id="7f265-112">有关保护、规则和 DLP 的增强报告为 Exchange Online 管理员提供了交互式报告体验。</span><span class="sxs-lookup"><span data-stu-id="7f265-112">The enhanced reports for protection, rules, and DLP offer an interactive reporting experience for Exchange Online admins.</span></span> <span data-ttu-id="7f265-113">这些报告提供了摘要数据，以及深入了解各个邮件详细信息的功能。</span><span class="sxs-lookup"><span data-stu-id="7f265-113">These reports provide summary data and the ability to drill down into details about individual messages.</span></span>
  
<span data-ttu-id="7f265-114">有关每个订阅可用的报告的详细信息，请参阅[报告](../office-365-platform-service-description/reports.md)。</span><span class="sxs-lookup"><span data-stu-id="7f265-114">For more information about which reports are available with each subscription, see [Reports](../office-365-platform-service-description/reports.md).</span></span> <span data-ttu-id="7f265-115">有关 Microsoft 365 管理中心中的 "报告" 页面的更多详细信息，请参阅[查看和下载有关 Office 365 中服务使用情况的报告](https://go.microsoft.com/fwlink/p/?LinkId=401187)和[使用邮件保护报告查看有关恶意软件、垃圾邮件和规则检测的数据](https://go.microsoft.com/fwlink/p/?LinkID=401102)。</span><span class="sxs-lookup"><span data-stu-id="7f265-115">For more detailed information about the Reports page in the Microsoft 365 admin center, see [View and download reports about service usage in Office 365](https://go.microsoft.com/fwlink/p/?LinkId=401187) and [Use mail protection reports to view data about malware, spam, and rule detections](https://go.microsoft.com/fwlink/p/?LinkID=401102).</span></span>
  
### <a name="reporting-using-the-excel-reporting-workbook"></a><span data-ttu-id="7f265-116">使用 Excel 报告工作簿进行报告</span><span class="sxs-lookup"><span data-stu-id="7f265-116">Reporting using the Excel reporting workbook</span></span>

<span data-ttu-id="7f265-117">还可以使用 Excel 2013 报告工作簿来查看具有细分功能的摘要报告。</span><span class="sxs-lookup"><span data-stu-id="7f265-117">You can also use the Excel 2013 reporting workbook to view summary reports with drill-down capabilities.</span></span> <span data-ttu-id="7f265-118">但是，我们建议改为使用增强型 Microsoft 365 管理中心报告。</span><span class="sxs-lookup"><span data-stu-id="7f265-118">However, we recommend using the enhanced Microsoft 365 admin center reports instead.</span></span> <span data-ttu-id="7f265-119">Excel 2013 报告工作簿计划将在未来弃用。</span><span class="sxs-lookup"><span data-stu-id="7f265-119">The Excel 2013 reporting workbook is planned to be deprecated in the future.</span></span> <span data-ttu-id="7f265-120">有关下载并安装此工作簿的更多概述信息和链接，请访问以下[下载页](https://go.microsoft.com/fwlink/p/?LinkId=271776)。</span><span class="sxs-lookup"><span data-stu-id="7f265-120">For more overview information and links to download and install the workbook, see the following [download page](https://go.microsoft.com/fwlink/p/?LinkId=271776).</span></span> <span data-ttu-id="7f265-121">若要了解如何使用工作簿，请参阅 [Mail Protection Reports Using the Excel Reporting Workbook](https://go.microsoft.com/fwlink/p/?LinkId=285211)（使用 Excel 报告工作簿的邮件保护报告）。</span><span class="sxs-lookup"><span data-stu-id="7f265-121">For information about how to use the workbook, see [Mail Protection Reports Using the Excel Reporting Workbook](https://go.microsoft.com/fwlink/p/?LinkId=285211).</span></span> 
  
### <a name="reporting-using-web-services"></a><span data-ttu-id="7f265-122">Reporting using web services</span><span class="sxs-lookup"><span data-stu-id="7f265-122">Reporting using web services</span></span>

<span data-ttu-id="7f265-123">通过使用 REST/OData 租户报告 web 服务，可以访问有关邮箱、组和邮件数据的摘要和详细报告，它是一个可用于创建自定义报告的编程界面。</span><span class="sxs-lookup"><span data-stu-id="7f265-123">Access to both summary and detailed reports about mailboxes, groups, and messaging data is available by using the REST/OData Tenant Reporting web service, which is a programmatic interface that lets you create custom reports.</span></span> <span data-ttu-id="7f265-124">有关详细信息，请参阅[Office 365 Reporting web services](https://go.microsoft.com/fwlink/p/?LinkId=287041)。</span><span class="sxs-lookup"><span data-stu-id="7f265-124">For more information, see [Office 365 Reporting web services](https://go.microsoft.com/fwlink/p/?LinkId=287041).</span></span>
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a><span data-ttu-id="7f265-125">EAC 中的报告功能和疑难解答工具</span><span class="sxs-lookup"><span data-stu-id="7f265-125">Reporting features and troubleshooting tools in the EAC</span></span>

<span data-ttu-id="7f265-126">Exchange 管理中心将提供下列报告功能和疑难解答工具。</span><span class="sxs-lookup"><span data-stu-id="7f265-126">The following reporting features and troubleshooting tools are available in the Exchange admin center.</span></span>
  
### <a name="trace-an-email-message"></a><span data-ttu-id="7f265-127">跟踪电子邮件</span><span class="sxs-lookup"><span data-stu-id="7f265-127">Trace an email message</span></span>

<span data-ttu-id="7f265-128">邮件跟踪功能使您可以作为管理员，在电子邮件通过 Exchange Online 服务时对其进行跟踪。</span><span class="sxs-lookup"><span data-stu-id="7f265-128">The message trace feature lets you, as an administrator, follow email messages as they pass through your Exchange Online service.</span></span> <span data-ttu-id="7f265-129">该功能有助于您确定目标邮件是否被接收、拒绝、推迟或由 Exchange 服务进行了传递。</span><span class="sxs-lookup"><span data-stu-id="7f265-129">It helps you determine whether a targeted email message was received, rejected, deferred, or delivered by the service.</span></span> <span data-ttu-id="7f265-130">这使得您可以有效回答用户的问题，解决邮件流问题，并减少联系技术支持寻求帮助的需要。</span><span class="sxs-lookup"><span data-stu-id="7f265-130">This lets you efficiently answer your users' questions and troubleshoot mail flow issues, and alleviates the need to contact technical support for assistance.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="7f265-131">For troubleshooting general issues and trends, use the reporting tools to obtain such data.</span><span class="sxs-lookup"><span data-stu-id="7f265-131">For troubleshooting general issues and trends, use the reporting tools to obtain such data.</span></span> <span data-ttu-id="7f265-132">For single point specifics where details are needed about a message, use the message trace tool.</span><span class="sxs-lookup"><span data-stu-id="7f265-132">For single point specifics where details are needed about a message, use the message trace tool.</span></span> 
  
<span data-ttu-id="7f265-133">有关邮件跟踪功能的详细信息，请参阅[跟踪电子邮件](https://go.microsoft.com/fwlink/p/?LinkId=271777)。</span><span class="sxs-lookup"><span data-stu-id="7f265-133">For more information about the message trace feature, see [Trace an Email Message](https://go.microsoft.com/fwlink/p/?LinkId=271777).</span></span>
  
### <a name="auditing-reports"></a><span data-ttu-id="7f265-134">审核报告</span><span class="sxs-lookup"><span data-stu-id="7f265-134">Auditing reports</span></span>

<span data-ttu-id="7f265-135">You can use audit logging to troubleshoot configuration issues by tracking specific changes made by administrators and to help you meet regulatory, compliance, and litigation requirements.</span><span class="sxs-lookup"><span data-stu-id="7f265-135">You can use audit logging to troubleshoot configuration issues by tracking specific changes made by administrators and to help you meet regulatory, compliance, and litigation requirements.</span></span> <span data-ttu-id="7f265-136">Exchange Online provides two types of audit logging:</span><span class="sxs-lookup"><span data-stu-id="7f265-136">Exchange Online provides two types of audit logging:</span></span>
  
- <span data-ttu-id="7f265-137">Administrator audit logging records any action performed by an administrator.</span><span class="sxs-lookup"><span data-stu-id="7f265-137">Administrator audit logging records any action performed by an administrator.</span></span> <span data-ttu-id="7f265-138">This can help you troubleshoot configuration issues or identify the cause of security-related or compliance-related problems.</span><span class="sxs-lookup"><span data-stu-id="7f265-138">This can help you troubleshoot configuration issues or identify the cause of security-related or compliance-related problems.</span></span> 
    
- <span data-ttu-id="7f265-139">Mailbox audit logging records whenever a mailbox is accessed by someone other than the person who owns the mailbox.</span><span class="sxs-lookup"><span data-stu-id="7f265-139">Mailbox audit logging records whenever a mailbox is accessed by someone other than the person who owns the mailbox.</span></span> <span data-ttu-id="7f265-140">This can help you determine who has accessed a mailbox and what they've done.</span><span class="sxs-lookup"><span data-stu-id="7f265-140">This can help you determine who has accessed a mailbox and what they've done.</span></span> 
    
<span data-ttu-id="7f265-141">有关审核日志记录的详细信息，请参阅[审核报告](https://go.microsoft.com/fwlink/p/?LinkId=271779)。</span><span class="sxs-lookup"><span data-stu-id="7f265-141">For more information about audit logging, see [Auditing Reports](https://go.microsoft.com/fwlink/p/?LinkId=271779).</span></span>
  
### <a name="unified-messaging-reports"></a><span data-ttu-id="7f265-142">统一消息报告</span><span class="sxs-lookup"><span data-stu-id="7f265-142">Unified Messaging reports</span></span>

<span data-ttu-id="7f265-143">You can use these reports to monitor and troubleshoot Unified Messaging (UM) in your Exchange Online organization.</span><span class="sxs-lookup"><span data-stu-id="7f265-143">You can use these reports to monitor and troubleshoot Unified Messaging (UM) in your Exchange Online organization.</span></span> <span data-ttu-id="7f265-144">For more information, see [Run Reports for Voice Mail Calls](https://go.microsoft.com/fwlink/p/?LinkId=287042).</span><span class="sxs-lookup"><span data-stu-id="7f265-144">For more information, see [Run Reports for Voice Mail Calls](https://go.microsoft.com/fwlink/p/?LinkId=287042).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="7f265-145">功能可用性</span><span class="sxs-lookup"><span data-stu-id="7f265-145">Feature availability</span></span>

<span data-ttu-id="7f265-146">若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅[Exchange Online 服务说明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="7f265-146">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online service description](exchange-online-service-description.md).</span></span>
  

