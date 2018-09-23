---
title: 报告和邮件跟踪
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- reporting-and-message-trace-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9263f99-5921-44fd-bb4c-0d487b59a656
description: Microsoft Exchange Online Protection (EOP) 提供了许多不同的报表，可帮助您确定的总体状态和组织的运行状况。某些报告可在 Microsoft Office 365 管理中心时其他人可在 Exchange 管理中心 (EAC)。
ms.openlocfilehash: ead40ff8932d6f10ca91bd871e34ef9070c6b2db
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035160"
---
# <a name="reporting-and-message-trace"></a><span data-ttu-id="683a0-104">报告和邮件跟踪</span><span class="sxs-lookup"><span data-stu-id="683a0-104">Reporting and Message Trace</span></span>

<span data-ttu-id="683a0-p102">Microsoft Exchange Online Protection (EOP) 提供了许多不同的报表，可帮助您确定的总体状态和组织的运行状况。某些报告可在 Microsoft Office 365 管理中心时其他人可在 Exchange 管理中心 (EAC)。</span><span class="sxs-lookup"><span data-stu-id="683a0-p102">Microsoft Exchange Online Protection (EOP) offers many different reports that can help you determine the overall status and health of your organization. Some reports are available in the Microsoft Office 365 admin center, while others are available in the Exchange admin center (EAC).</span></span>
  
<span data-ttu-id="683a0-p103">想了解 EOP 的所有功能？请参阅 [Exchange Online Protection 服务说明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="683a0-p103">Looking for information about all EOP features? See the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="office-365-admin-center-reports"></a><span data-ttu-id="683a0-109">Office 365 管理中心报告</span><span class="sxs-lookup"><span data-stu-id="683a0-109">Office 365 admin center reports</span></span>
<span data-ttu-id="683a0-110"><a name="BKMK_office365admincenterreports"> </a></span><span class="sxs-lookup"><span data-stu-id="683a0-110"></span></span>

<span data-ttu-id="683a0-p104">Office 365 管理中心中的"报告"页面提供受 Exchange 传输规则或数据丢失保护 (DLP) 策略影响的有关邮件通信、垃圾邮件和恶意软件检测以及邮件的信息。有关保护、规则和 DLP 的增强报告为 EOP 管理员提供了交互式报告体验。这些报告提供了摘要数据，以及深入了解各个邮件详细信息的功能。</span><span class="sxs-lookup"><span data-stu-id="683a0-p104">The Reports page in the Office 365 admin center provides information about message traffic, spam and malware detections, and messages affected by Exchange Transport Rules or Data Loss Prevention (DLP) policies. The enhanced reports for protection, rules, and DLP offer an interactive reporting experience for EOP admins. These reports provide summary data and the ability to drill down into details about individual messages.</span></span>
  
<span data-ttu-id="683a0-114">有关这些报告的详细信息，请参阅[使用 Office 365 中的邮件保护报告查看关于恶意软件、垃圾邮件和规则检测的数据](https://go.microsoft.com/fwlink/p/?LinkID=401102)。</span><span class="sxs-lookup"><span data-stu-id="683a0-114">For more detailed information about these reports, see [Use mail protection reports in Office 365 to view data about malware, spam and rule detections](https://go.microsoft.com/fwlink/p/?LinkID=401102).</span></span>
  
## <a name="excel-download-application-reports"></a><span data-ttu-id="683a0-115">Excel 下载应用程序报告</span><span class="sxs-lookup"><span data-stu-id="683a0-115">Excel download application reports</span></span>
<span data-ttu-id="683a0-116"><a name="BKMK_exceldownloadapplicationreports"> </a></span><span class="sxs-lookup"><span data-stu-id="683a0-116"></span></span>

<span data-ttu-id="683a0-p105">Excel 2013 报告工作簿中还提供邮件保护报告，为摘要报告提供了深入了解功能。但是，我们建议改用增强的 Office 365 管理中心报告。Excel 2013 报告工作簿计划将在未来弃用。</span><span class="sxs-lookup"><span data-stu-id="683a0-p105">Email protection reports are also available in the Excel 2013 reporting workbook, which provides summary reports with drill-down capabilities. However, we recommend using the enhanced Office 365 admin center reports instead. The Excel 2013 reporting workbook is planned to be deprecated in the future.</span></span> 
  
<span data-ttu-id="683a0-p106">有关下载并安装工作簿的更多概述信息和链接，请参阅 [Mail Protection Reports for Office 365](https://go.microsoft.com/fwlink/p/?LinkId=271776)。若要了解如何使用工作簿，请参阅 [Mail Protection Reports Using the Excel Reporting Workbook](https://go.microsoft.com/fwlink/p/?LinkId=285211)（使用 Excel 报告工作簿的邮件保护报告）。</span><span class="sxs-lookup"><span data-stu-id="683a0-p106">For more overview information and links to download and install the workbook, see [Mail Protection Reports for Office 365](https://go.microsoft.com/fwlink/p/?LinkId=271776). For information about how to use the workbook, see [Mail Protection Reports Using the Excel Reporting Workbook](https://go.microsoft.com/fwlink/p/?LinkId=285211).</span></span>
  
## <a name="reporting-using-web-services"></a><span data-ttu-id="683a0-122">使用 Web 服务的报告</span><span class="sxs-lookup"><span data-stu-id="683a0-122">Reporting using web services</span></span>
<span data-ttu-id="683a0-123"><a name="BKMK_reportingusingwebservices"> </a></span><span class="sxs-lookup"><span data-stu-id="683a0-123"></span></span>

<span data-ttu-id="683a0-p107">不适用于 EOP 独立客户。可以使用 REST/OData 租户报告 Web 服务以编程方式收集有关邮件数据的摘要和详细报告，也可以在自定义管理 Web 门户网页上显示数据。有关详细信息，请参阅 [Office 365 报告 Web 服务](https://go.microsoft.com/fwlink/?LinkId=279926)。</span><span class="sxs-lookup"><span data-stu-id="683a0-p107">Not available to EOP standalone customers. You can use the REST/OData Tenant Reporting Web service to programmatically collect summary and detailed reports about messaging data, and you can display the data on a web page in a custom management Web portal. For more information, see [Office 365 Reporting Web Services](https://go.microsoft.com/fwlink/?LinkId=279926).</span></span>
  
## <a name="message-trace"></a><span data-ttu-id="683a0-127">邮件跟踪</span><span class="sxs-lookup"><span data-stu-id="683a0-127">Message trace</span></span>
<span data-ttu-id="683a0-128"><a name="BKMK_messagetrace"> </a></span><span class="sxs-lookup"><span data-stu-id="683a0-128"></span></span>

<span data-ttu-id="683a0-p108">通过 EAC 中的邮件跟踪功能，可以管理员身份在电子邮件经过 EOP 时对其进行跟踪。该功能有助于你确定目标电子邮件是被接收、拒绝、延迟，还是由服务进行传递。它还显示邮件在最终状态前其上发生的操作。获取特定邮件的详细信息后，可以有效回答用户的问题、排查邮件流问题、验证策略更改，并减少需要联系技术支持寻求帮助的情况。有关详细信息，请参阅[跟踪电子邮件](https://go.microsoft.com/fwlink/p/?LinkID=282262)。</span><span class="sxs-lookup"><span data-stu-id="683a0-p108">The message trace feature in the EAC enables you as an administrator to follow email messages as they pass through the EOP. It helps you determine whether a targeted email message was received, rejected, deferred, or delivered by the service. It also shows what actions have occurred to the message before reaching its final status. Obtaining detailed information about a specific message lets you efficiently answer your user's questions, troubleshoot mail flow issues, validate policy changes, and alleviates the need to contact technical support for assistance. For more information, see [Trace an Email Message](https://go.microsoft.com/fwlink/p/?LinkID=282262).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="683a0-134">功能可用性</span><span class="sxs-lookup"><span data-stu-id="683a0-134">Feature Availability</span></span>
<span data-ttu-id="683a0-135"><a name="BKMK_messagetrace"> </a></span><span class="sxs-lookup"><span data-stu-id="683a0-135"></span></span>

<span data-ttu-id="683a0-136">若要查看在各个 Office 365 计划、独立选项和内部部署解决方案之间的功能可用性，请参阅 [Exchange Online Protection 服务说明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="683a0-136">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  

