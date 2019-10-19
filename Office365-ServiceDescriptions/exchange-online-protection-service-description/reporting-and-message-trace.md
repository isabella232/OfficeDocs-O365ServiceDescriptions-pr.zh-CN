---
title: 报告和邮件跟踪
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- reporting-and-message-trace-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9263f99-5921-44fd-bb4c-0d487b59a656
description: Microsoft Exchange Online Protection (EOP) 提供许多不同的报告，可帮助您确定组织的总体状态和运行状况。 Microsoft 365 管理中心提供了一些报告，而其他报告在 Exchange 管理中心（EAC）中可用。
ms.openlocfilehash: b8afb8a404fb322d70ce5d393c5a5e70cc5af6aa
ms.sourcegitcommit: 19591e97b35c1b2a99e04a496d83af27dc6530d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/18/2019
ms.locfileid: "37581898"
---
# <a name="reporting-and-message-trace"></a><span data-ttu-id="715f1-104">报告和邮件跟踪</span><span class="sxs-lookup"><span data-stu-id="715f1-104">Reporting and message trace</span></span>

<span data-ttu-id="715f1-105">Microsoft Exchange Online Protection (EOP) 提供许多不同的报告，可帮助您确定组织的总体状态和运行状况。</span><span class="sxs-lookup"><span data-stu-id="715f1-105">Microsoft Exchange Online Protection (EOP) offers many different reports that can help you determine the overall status and health of your organization.</span></span> <span data-ttu-id="715f1-106">Microsoft 365 管理中心提供了一些报告，而其他报告在 Exchange 管理中心（EAC）中可用。</span><span class="sxs-lookup"><span data-stu-id="715f1-106">Some reports are available in the Microsoft 365 admin center, while others are available in the Exchange admin center (EAC).</span></span>

<span data-ttu-id="715f1-107">要查找有关 EOP 所有功能的信息吗？</span><span class="sxs-lookup"><span data-stu-id="715f1-107">Looking for information about all EOP features?</span></span> <span data-ttu-id="715f1-108">请参阅 [Exchange Online Protection 服务说明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="715f1-108">See the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>

## <a name="microsoft-365-admin-center-reports"></a><span data-ttu-id="715f1-109">Microsoft 365 管理中心报告</span><span class="sxs-lookup"><span data-stu-id="715f1-109">Microsoft 365 admin center reports</span></span>

<span data-ttu-id="715f1-110">Microsoft 365 管理中心中的 "报告" 页提供有关邮件流量、垃圾邮件和恶意软件检测以及受邮件流规则（也称为传输规则）或数据丢失防护（DLP）策略影响的邮件的信息。</span><span class="sxs-lookup"><span data-stu-id="715f1-110">The Reports page in the Microsoft 365 admin center provides information about message traffic, spam and malware detections, and messages affected by mail flow rules (also known as transport rules) or data loss prevention (DLP) policies.</span></span> <span data-ttu-id="715f1-111">有关保护、规则和 DLP 的增强报告为 EOP 管理员提供了交互式报告体验。</span><span class="sxs-lookup"><span data-stu-id="715f1-111">The enhanced reports for protection, rules, and DLP offer an interactive reporting experience for EOP admins.</span></span> <span data-ttu-id="715f1-112">这些报告提供了摘要数据，以及深入了解各个邮件详细信息的功能。</span><span class="sxs-lookup"><span data-stu-id="715f1-112">These reports provide summary data and the ability to drill down into details about individual messages.</span></span>

<span data-ttu-id="715f1-113">有关这些报告的更多详细信息，请参阅[使用 Office 365 中的邮件保护报告查看关于恶意软件、垃圾邮件和规则检测的数据](https://docs.microsoft.com/exchange/monitoring/use-mail-protection-reports)。</span><span class="sxs-lookup"><span data-stu-id="715f1-113">For more detailed information about these reports, see [Use mail protection reports in Office 365 to view data about malware, spam, and rule detections](https://docs.microsoft.com/exchange/monitoring/use-mail-protection-reports).</span></span>

## <a name="reporting-using-web-services"></a><span data-ttu-id="715f1-114">Reporting using web services</span><span class="sxs-lookup"><span data-stu-id="715f1-114">Reporting using web services</span></span>

> [!NOTE]
> <span data-ttu-id="715f1-115">许多基于 REST 的报告功能和相关 cmdlet 在2018年1月已弃用。</span><span class="sxs-lookup"><span data-stu-id="715f1-115">Many of the REST-based reporting features and related cmdlets were deprecated in January, 2018.</span></span> <span data-ttu-id="715f1-116">有关 Office 365 中可用的替换 Microsoft Graph 报告的信息，请参阅[Microsoft Graph 中使用 Office 365 使用率报告](https://go.microsoft.com/fwlink/p/?LinkID=865135)的主题。</span><span class="sxs-lookup"><span data-stu-id="715f1-116">For information about the available replacement Microsoft Graph reports in Office 365, see the subtopics of [Working with Office 365 usage reports in Microsoft Graph](https://go.microsoft.com/fwlink/p/?LinkID=865135).</span></span>

<span data-ttu-id="715f1-117">不适用于 EOP 独立客户。</span><span class="sxs-lookup"><span data-stu-id="715f1-117">Not available to EOP standalone customers.</span></span> <span data-ttu-id="715f1-118">您可以使用 REST/OData 租户报告 web 服务以编程方式收集有关邮件数据的摘要和详细报告，并且您可以在自定义 web 管理门户中的网页上显示数据。</span><span class="sxs-lookup"><span data-stu-id="715f1-118">You can use the REST/OData Tenant Reporting web service to programmatically collect summary and detailed reports about messaging data, and you can display the data on a web page in a custom web management portal.</span></span>

## <a name="message-trace"></a><span data-ttu-id="715f1-119">Message trace</span><span class="sxs-lookup"><span data-stu-id="715f1-119">Message trace</span></span>

<span data-ttu-id="715f1-120">EAC 中的邮件跟踪功能使您可以作为管理员，在电子邮件通过 EOP 时执行这些操作。</span><span class="sxs-lookup"><span data-stu-id="715f1-120">The message trace feature in the EAC lets you, as an administrator, follow email messages as they pass through the EOP.</span></span> <span data-ttu-id="715f1-121">该功能有助于你确定目标电子邮件是被接收、拒绝、延迟，还是由服务进行传递。</span><span class="sxs-lookup"><span data-stu-id="715f1-121">It helps you determine whether a targeted email message was received, rejected, deferred, or delivered by the service.</span></span> <span data-ttu-id="715f1-122">它还显示邮件在最终状态前其上发生的操作。</span><span class="sxs-lookup"><span data-stu-id="715f1-122">It also shows what actions have occurred to the message before reaching its final status.</span></span> <span data-ttu-id="715f1-123">获取特定邮件的详细信息后，可以有效回答用户的问题、排查邮件流问题、验证策略更改，并减少需要联系技术支持寻求帮助的情况。</span><span class="sxs-lookup"><span data-stu-id="715f1-123">Obtaining detailed information about a specific message lets you efficiently answer your user's questions, troubleshoot mail flow issues, validate policy changes, and alleviates the need to contact technical support for assistance.</span></span> <span data-ttu-id="715f1-124">有关详细信息，请参阅[运行邮件跟踪和在 Exchange 管理中心中查看结果](https://docs.microsoft.com/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results)。</span><span class="sxs-lookup"><span data-stu-id="715f1-124">For more information, see [Run a message trace and view the results in the Exchange admin center](https://docs.microsoft.com/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results).</span></span>

## <a name="feature-availability"></a><span data-ttu-id="715f1-125">功能可用性</span><span class="sxs-lookup"><span data-stu-id="715f1-125">Feature availability</span></span>

<span data-ttu-id="715f1-126">若要查看跨 Office 365 计划、独立选项和本地解决方案的功能可用性，请参阅[Exchange Online Protection 服务说明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="715f1-126">To view feature availability across Office 365 plans, standalone options, and on-premises solutions, see [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
