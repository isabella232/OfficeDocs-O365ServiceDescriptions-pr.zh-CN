---
title: 报告功能和疑难解答工具
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft exchange Online 提供了 Exchange 管理中心 (EAC) 的各种报告功能。
ms.openlocfilehash: 1fb9a0fe62fb94c0ace7388613ca26f65fc4698f
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/07/2019
ms.locfileid: "30466979"
---
# <a name="reporting-features-and-troubleshooting-tools"></a><span data-ttu-id="391e4-103">报告功能和疑难解答工具</span><span class="sxs-lookup"><span data-stu-id="391e4-103">Reporting Features and Troubleshooting Tools</span></span>

<span data-ttu-id="391e4-104">Microsoft exchange Online 提供了 Exchange 管理中心 (EAC) 的各种报告功能。</span><span class="sxs-lookup"><span data-stu-id="391e4-104">Microsoft Exchange Online offers a variety of reporting features both in and out of the Exchange admin center (EAC).</span></span>
  
## <a name="reporting-features"></a><span data-ttu-id="391e4-105">报告功能</span><span class="sxs-lookup"><span data-stu-id="391e4-105">Reporting features</span></span>

<span data-ttu-id="391e4-106">Exchange Online 客户可以通过下载 Excel 报告工作簿或使用 Web 服务来访问 Microsoft 365 管理中心中的报告。</span><span class="sxs-lookup"><span data-stu-id="391e4-106">Exchange Online customers can access reports in the Microsoft 365 admin center, by downloading an Excel reporting workbook, or by using Web services.</span></span>
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a><span data-ttu-id="391e4-107">Microsoft 365 管理中心中的报告</span><span class="sxs-lookup"><span data-stu-id="391e4-107">Reporting in the Microsoft 365 admin center</span></span>

<span data-ttu-id="391e4-108">Microsoft 365 管理中心中的 "报告" 页面上有报告, 其中提供了有关邮箱和组的摘要信息。</span><span class="sxs-lookup"><span data-stu-id="391e4-108">There are reports on the Reports page in the Microsoft 365 admin center that provide summary information about mailboxes and groups.</span></span> <span data-ttu-id="391e4-109">例如，其中有一项报告将列出按天、星期、月份或年份创建和删除的组的数量。</span><span class="sxs-lookup"><span data-stu-id="391e4-109">For example, one report lists the number of groups created and deleted by day, week, month, or year.</span></span> <span data-ttu-id="391e4-110">它还有许多有关新邮箱和已删除邮箱的摘要报告，以及活动和不活动邮箱的摘要报告。</span><span class="sxs-lookup"><span data-stu-id="391e4-110">There are also summary reports for new and deleted mailboxes, and active and inactive mailboxes.</span></span> 
  
<span data-ttu-id="391e4-111">此外, Microsoft 365 管理中心中的 "报告" 页面包含邮件数据报告, 其中提供了有关邮件流量、垃圾邮件和恶意软件检测以及受 Exchange 传输规则或数据丢失防护 (DLP) 影响的邮件的信息。策略.</span><span class="sxs-lookup"><span data-stu-id="391e4-111">Additionally, the Reports page in the Microsoft 365 admin center contains messaging data reports, which provide information about message traffic, spam and malware detections, and messages affected by Exchange Transport Rules or Data Loss Prevention (DLP) policies.</span></span> <span data-ttu-id="391e4-112">有关保护、规则和 DLP 的增强报告为 Exchange Online 管理员提供了交互式报告体验。</span><span class="sxs-lookup"><span data-stu-id="391e4-112">The enhanced reports for protection, rules, and DLP offer an interactive reporting experience for Exchange Online admins.</span></span> <span data-ttu-id="391e4-113">这些报告提供了摘要数据，以及深入了解各个邮件详细信息的功能。</span><span class="sxs-lookup"><span data-stu-id="391e4-113">These reports provide summary data and the ability to drill down into details about individual messages.</span></span>
  
<span data-ttu-id="391e4-114">若要详细了解每个 Office 365 订阅的可用报告，请参阅[报告](../office-365-platform-service-description/reports.md)。</span><span class="sxs-lookup"><span data-stu-id="391e4-114">For more information about which reports are available with each Office 365 subscription, see [Reports](../office-365-platform-service-description/reports.md).</span></span> <span data-ttu-id="391e4-115">有关 Microsoft 365 管理中心中的 "报告" 页面的更多详细信息, 请参阅[查看和下载有关 office 365 中服务使用情况的报告](https://go.microsoft.com/fwlink/p/?LinkId=401187)和[使用 office 365 中的邮件保护报告查看有关恶意软件、垃圾邮件和规则检测的数据](https://go.microsoft.com/fwlink/p/?LinkID=401102).</span><span class="sxs-lookup"><span data-stu-id="391e4-115">For more detailed information about the Reports page in the Microsoft 365 admin center, see [View and download reports about service usage in Office 365](https://go.microsoft.com/fwlink/p/?LinkId=401187) and [Use mail protection reports in Office 365 to view data about malware, spam, and rule detections](https://go.microsoft.com/fwlink/p/?LinkID=401102).</span></span>
  
### <a name="reporting-using-the-excel-reporting-workbook"></a><span data-ttu-id="391e4-116">使用 Excel 报告工作簿进行报告</span><span class="sxs-lookup"><span data-stu-id="391e4-116">Reporting using the Excel reporting workbook</span></span>

<span data-ttu-id="391e4-117">还可以使用 Excel 2013 报告工作簿来查看具有细分功能的摘要报告。</span><span class="sxs-lookup"><span data-stu-id="391e4-117">You can also use the Excel 2013 reporting workbook to view summary reports with drill-down capabilities.</span></span> <span data-ttu-id="391e4-118">但是, 我们建议改为使用增强型 Microsoft 365 管理中心报告。</span><span class="sxs-lookup"><span data-stu-id="391e4-118">However, we recommend using the enhanced Microsoft 365 admin center reports instead.</span></span> <span data-ttu-id="391e4-119">Excel 2013 报告工作簿计划将在未来弃用。</span><span class="sxs-lookup"><span data-stu-id="391e4-119">The Excel 2013 reporting workbook is planned to be deprecated in the future.</span></span> <span data-ttu-id="391e4-120">有关下载并安装此工作簿的更多概述信息和链接，请访问以下[下载页](https://go.microsoft.com/fwlink/p/?LinkId=271776)。</span><span class="sxs-lookup"><span data-stu-id="391e4-120">For more overview information and links to download and install the workbook, see the following [download page](https://go.microsoft.com/fwlink/p/?LinkId=271776).</span></span> <span data-ttu-id="391e4-121">若要了解如何使用工作簿，请参阅 [Mail Protection Reports Using the Excel Reporting Workbook](https://go.microsoft.com/fwlink/p/?LinkId=285211)（使用 Excel 报告工作簿的邮件保护报告）。</span><span class="sxs-lookup"><span data-stu-id="391e4-121">For information about how to use the workbook, see [Mail Protection Reports Using the Excel Reporting Workbook](https://go.microsoft.com/fwlink/p/?LinkId=285211).</span></span> 
  
### <a name="reporting-using-web-services"></a><span data-ttu-id="391e4-122">使用 Web 服务的报告</span><span class="sxs-lookup"><span data-stu-id="391e4-122">Reporting using Web services</span></span>

<span data-ttu-id="391e4-p105">使用 REST/OData Tenant Reporting Web 服务（一款支持创建自定义报告的编程界面），可以访问邮箱、组和邮件数据的摘要报告和详细报告。有关详细信息，请参阅 [Office 365 报告 Web 服务](https://go.microsoft.com/fwlink/p/?LinkId=287041)。</span><span class="sxs-lookup"><span data-stu-id="391e4-p105">Access to both summary and detailed reports about mailboxes, groups, and messaging data is available by using the REST/OData Tenant Reporting Web service, which is a programmatic interface that enables you to create custom reports. For more information, see [Office 365 Reporting Web Services](https://go.microsoft.com/fwlink/p/?LinkId=287041).</span></span>
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a><span data-ttu-id="391e4-125">EAC 中的报告功能和疑难解答工具</span><span class="sxs-lookup"><span data-stu-id="391e4-125">Reporting features and troubleshooting tools in the EAC</span></span>

<span data-ttu-id="391e4-126">Exchange 管理中心将提供下列报告功能和疑难解答工具。</span><span class="sxs-lookup"><span data-stu-id="391e4-126">The following reporting features and troubleshooting tools are available in the Exchange admin center.</span></span>
  
### <a name="trace-an-email-message"></a><span data-ttu-id="391e4-127">跟踪电子邮件</span><span class="sxs-lookup"><span data-stu-id="391e4-127">Trace an email message</span></span>

<span data-ttu-id="391e4-p106">邮件跟踪功能使您可以作为管理员在邮件经过 Exchange Online 服务时对邮件进行跟踪。该功能有助于您确定目标邮件是否被接收、拒绝、推迟或由 Exchange 服务进行了传递。这使得您可以有效回答用户的问题，解决邮件流问题，并减少联系技术支持寻求帮助的需要。</span><span class="sxs-lookup"><span data-stu-id="391e4-p106">The message trace feature enables you as an administrator to follow email messages as they pass through your Exchange Online service. It helps you determine whether a targeted email message was received, rejected, deferred, or delivered by the service. This lets you efficiently answer your users' questions and troubleshoot mail flow issues, and alleviates the need to contact technical support for assistance.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="391e4-p107">对于一般问题与走向的疑难解答，使用报告工具获取相关数据。使用邮件跟踪工具获取需要邮件详细信息的单点信息。</span><span class="sxs-lookup"><span data-stu-id="391e4-p107">For troubleshooting general issues and trends, use the reporting tools to obtain such data. For single point specifics where details are needed about a message, use the message trace tool.</span></span> 
  
<span data-ttu-id="391e4-133">有关邮件跟踪功能的详细信息，请参阅[跟踪电子邮件](https://go.microsoft.com/fwlink/p/?LinkId=271777)。</span><span class="sxs-lookup"><span data-stu-id="391e4-133">For more information about the message trace feature, see [Trace an Email Message](https://go.microsoft.com/fwlink/p/?LinkId=271777).</span></span>
  
### <a name="auditing-reports"></a><span data-ttu-id="391e4-134">审核报告</span><span class="sxs-lookup"><span data-stu-id="391e4-134">Auditing reports</span></span>

<span data-ttu-id="391e4-p108">您可以使用审核日志记录通过跟踪管理员所做的特定更改来解决配置问题，并帮助您满足法规、遵从性以及诉讼等要求。Exchange Online 提供两种类型的审核日志记录：</span><span class="sxs-lookup"><span data-stu-id="391e4-p108">You can use audit logging to troubleshoot configuration issues by tracking specific changes made by administrators and to help you meet regulatory, compliance, and litigation requirements. Exchange Online provides two types of audit logging:</span></span>
  
- <span data-ttu-id="391e4-p109">管理员审核日志记录。它将记录由管理员执行的任何操作。这可以帮助您解决配置问题，或找出与安全或合规性相关的问题的原因。</span><span class="sxs-lookup"><span data-stu-id="391e4-p109">Administrator audit logging records any action performed by an administrator. This can help you troubleshoot configuration issues or identify the cause of security-related or compliance-related problems.</span></span> 
    
- <span data-ttu-id="391e4-p110">邮箱审核日志记录会在邮箱所有者之外的其他人每次访问邮箱时进行记录。这可以帮助您确定谁访问了邮箱以及访问者完成了哪些操作。</span><span class="sxs-lookup"><span data-stu-id="391e4-p110">Mailbox audit logging records whenever a mailbox is accessed by someone other than the person who owns the mailbox. This can help you determine who has accessed a mailbox and what they've done.</span></span> 
    
<span data-ttu-id="391e4-141">有关审核日志记录的详细信息，请参阅[审核报告](https://go.microsoft.com/fwlink/p/?LinkId=271779)。</span><span class="sxs-lookup"><span data-stu-id="391e4-141">For more information about audit logging, see [Auditing Reports](https://go.microsoft.com/fwlink/p/?LinkId=271779).</span></span>
  
### <a name="unified-messaging-reports"></a><span data-ttu-id="391e4-142">统一消息报告</span><span class="sxs-lookup"><span data-stu-id="391e4-142">Unified Messaging reports</span></span>

<span data-ttu-id="391e4-p111">可使用这些报告监视并排查 Exchange Online 组织中的统一消息 (UM) 问题。有关详细信息，请参阅 [Run Reports for Voice Mail Calls](https://go.microsoft.com/fwlink/p/?LinkId=287042)（生成语音邮件呼叫报告）。</span><span class="sxs-lookup"><span data-stu-id="391e4-p111">You can use these reports to monitor and troubleshoot Unified Messaging (UM) in your Exchange Online organization. For more information, see [Run Reports for Voice Mail Calls](https://go.microsoft.com/fwlink/p/?LinkId=287042).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="391e4-145">功能可用性</span><span class="sxs-lookup"><span data-stu-id="391e4-145">Feature Availability</span></span>

<span data-ttu-id="391e4-146">若要查看在各个 Office 365 计划、独立选项和内部部署解决方案之间的功能可用性，请参阅 [Exchange Online 服务说明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="391e4-146">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

