---
title: Exchange Online Protection 中的报告和邮件跟踪
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- reporting-and-message-trace-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9263f99-5921-44fd-bb4c-0d487b59a656
description: 阅读本文，了解 Microsoft Exchange Online Protection (EOP) 中的报告和邮件) 。
ms.openlocfilehash: 383c222563e76d4a5613c9faac5b68417fa64b8a
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653124"
---
# <a name="reporting-and-message-trace-in-exchange-online-protection"></a><span data-ttu-id="2eb85-103">Exchange Online Protection 中的报告和邮件跟踪</span><span class="sxs-lookup"><span data-stu-id="2eb85-103">Reporting and message trace in Exchange Online Protection</span></span>

<span data-ttu-id="2eb85-104">Microsoft Exchange Online Protection (EOP) 提供许多不同的报告，可帮助您确定组织的总体状态和运行状况。</span><span class="sxs-lookup"><span data-stu-id="2eb85-104">Microsoft Exchange Online Protection (EOP) offers many different reports that can help you determine the overall status and health of your organization.</span></span> <span data-ttu-id="2eb85-105">某些报告在管理中心Microsoft 365，而其他报告在 EAC Exchange管理中心 () 。</span><span class="sxs-lookup"><span data-stu-id="2eb85-105">Some reports are available in the Microsoft 365 admin center, while others are available in the Exchange admin center (EAC).</span></span>

<span data-ttu-id="2eb85-106">要查找有关 EOP 所有功能的信息吗？</span><span class="sxs-lookup"><span data-stu-id="2eb85-106">Looking for information about all EOP features?</span></span> <span data-ttu-id="2eb85-107">请参阅Exchange Online Protection[服务说明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="2eb85-107">See the [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>

## <a name="microsoft-365-admin-center-reports"></a><span data-ttu-id="2eb85-108">Microsoft 365 管理中心报告</span><span class="sxs-lookup"><span data-stu-id="2eb85-108">Microsoft 365 admin center reports</span></span>

<span data-ttu-id="2eb85-109">Microsoft 365 管理中心中的"报告"页提供了有关邮件通信、垃圾邮件和恶意软件检测以及受邮件流规则影响的邮件的信息 (也称为传输规则) 或数据丢失防护 (DLP) 策略。</span><span class="sxs-lookup"><span data-stu-id="2eb85-109">The Reports page in the Microsoft 365 admin center provides information about message traffic, spam and malware detections, and messages affected by mail flow rules (also known as transport rules) or data loss prevention (DLP) policies.</span></span> <span data-ttu-id="2eb85-110">有关保护、规则和 DLP 的增强报告为 EOP 管理员提供了交互式报告体验。</span><span class="sxs-lookup"><span data-stu-id="2eb85-110">The enhanced reports for protection, rules, and DLP offer an interactive reporting experience for EOP admins.</span></span> <span data-ttu-id="2eb85-111">这些报告提供了摘要数据，以及深入了解各个邮件详细信息的功能。</span><span class="sxs-lookup"><span data-stu-id="2eb85-111">These reports provide summary data and the ability to drill down into details about individual messages.</span></span>

<span data-ttu-id="2eb85-112">有关这些报告的更多详细信息，请参阅使用邮件 [保护报告查看有关恶意软件、垃圾邮件和规则检测的数据](/exchange/monitoring/use-mail-protection-reports)。</span><span class="sxs-lookup"><span data-stu-id="2eb85-112">For more detailed information about these reports, see [Use mail protection reports to view data about malware, spam, and rule detections](/exchange/monitoring/use-mail-protection-reports).</span></span>

## <a name="reporting-using-web-services"></a><span data-ttu-id="2eb85-113">Reporting using web services</span><span class="sxs-lookup"><span data-stu-id="2eb85-113">Reporting using web services</span></span>

> [!NOTE]
> <span data-ttu-id="2eb85-114">许多基于 REST 的报告功能和相关 cmdlet 在 2018 年 1 月已弃用。</span><span class="sxs-lookup"><span data-stu-id="2eb85-114">Many of the REST-based reporting features and related cmdlets were deprecated in January, 2018.</span></span> <span data-ttu-id="2eb85-115">有关可用替换 Microsoft Graph报告Office 365，请参阅在 Microsoft Graph 中处理[使用情况报表的子Graph。](/graph/api/resources/report)</span><span class="sxs-lookup"><span data-stu-id="2eb85-115">For information about the available replacement Microsoft Graph reports in Office 365, see the subtopics of [Working with usage reports in Microsoft Graph](/graph/api/resources/report).</span></span>

<span data-ttu-id="2eb85-116">不适用于 EOP 独立客户。</span><span class="sxs-lookup"><span data-stu-id="2eb85-116">Not available to EOP standalone customers.</span></span> <span data-ttu-id="2eb85-117">您可以使用 REST/OData 租户报告 Web 服务以编程方式收集有关邮件数据的摘要和详细报告，还可以在自定义 Web 管理门户的网页上显示数据。</span><span class="sxs-lookup"><span data-stu-id="2eb85-117">You can use the REST/OData Tenant Reporting web service to programmatically collect summary and detailed reports about messaging data, and you can display the data on a web page in a custom web management portal.</span></span>

## <a name="message-trace"></a><span data-ttu-id="2eb85-118">邮件跟踪</span><span class="sxs-lookup"><span data-stu-id="2eb85-118">Message trace</span></span>

<span data-ttu-id="2eb85-119">通过 EAC 中的邮件跟踪功能，您可以作为管理员跟踪通过 EOP 传递的电子邮件。</span><span class="sxs-lookup"><span data-stu-id="2eb85-119">The message trace feature in the EAC lets you, as an administrator, follow email messages as they pass through the EOP.</span></span> <span data-ttu-id="2eb85-120">该功能有助于你确定目标电子邮件是被接收、拒绝、延迟，还是由服务进行传递。</span><span class="sxs-lookup"><span data-stu-id="2eb85-120">It helps you determine whether a targeted email message was received, rejected, deferred, or delivered by the service.</span></span> <span data-ttu-id="2eb85-121">它还显示邮件在最终状态前其上发生的操作。</span><span class="sxs-lookup"><span data-stu-id="2eb85-121">It also shows what actions have occurred to the message before reaching its final status.</span></span> <span data-ttu-id="2eb85-122">获取特定邮件的详细信息后，可以有效回答用户的问题、排查邮件流问题、验证策略更改，并减少需要联系技术支持寻求帮助的情况。</span><span class="sxs-lookup"><span data-stu-id="2eb85-122">Obtaining detailed information about a specific message lets you efficiently answer your user's questions, troubleshoot mail flow issues, validate policy changes, and alleviates the need to contact technical support for assistance.</span></span> <span data-ttu-id="2eb85-123">有关详细信息，请参阅运行[邮件跟踪，并查看](/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results)管理中心Exchange结果。</span><span class="sxs-lookup"><span data-stu-id="2eb85-123">For more information, see [Run a message trace and view the results in the Exchange admin center](/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results).</span></span>

## <a name="feature-availability"></a><span data-ttu-id="2eb85-124">功能可用性</span><span class="sxs-lookup"><span data-stu-id="2eb85-124">Feature availability</span></span>

<span data-ttu-id="2eb85-125">若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅Exchange Online Protection[说明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="2eb85-125">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>