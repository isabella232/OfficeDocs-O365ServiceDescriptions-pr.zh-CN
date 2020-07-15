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
# <a name="reporting-features-and-troubleshooting-tools"></a>报告功能和疑难解答工具

Microsoft Exchange Online 提供了 Exchange 管理中心（EAC）的各种报告功能。
  
## <a name="reporting-features"></a>报告功能

Exchange Online 客户可以通过下载 Excel 报告工作簿或使用 web 服务来访问 Microsoft 365 管理中心中的报告。
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a>Microsoft 365 管理中心中的报告

Microsoft 365 管理中心中的 "报告" 页面上有报告，其中提供了有关邮箱和组的摘要信息。 例如，其中有一项报告将列出按天、星期、月份或年份创建和删除的组的数量。 它还有许多有关新邮箱和已删除邮箱的摘要报告，以及活动和不活动邮箱的摘要报告。 
  
此外，Microsoft 365 管理中心中的 "报告" 页面包含邮件数据报告，其中提供了有关邮件流量、垃圾邮件和恶意软件检测以及受 Exchange 传输规则或数据丢失防护（DLP）策略影响的邮件的信息。 有关保护、规则和 DLP 的增强报告为 Exchange Online 管理员提供了交互式报告体验。 这些报告提供了摘要数据，以及深入了解各个邮件详细信息的功能。
  
有关每个订阅可用的报告的详细信息，请参阅[报告](../office-365-platform-service-description/reports.md)。 有关 Microsoft 365 管理中心中的 "报告" 页面的更多详细信息，请参阅[查看和下载有关 Office 365 中服务使用情况的报告](https://go.microsoft.com/fwlink/p/?LinkId=401187)和[使用邮件保护报告查看有关恶意软件、垃圾邮件和规则检测的数据](https://go.microsoft.com/fwlink/p/?LinkID=401102)。
  
### <a name="reporting-using-the-excel-reporting-workbook"></a>使用 Excel 报告工作簿进行报告

还可以使用 Excel 2013 报告工作簿来查看具有细分功能的摘要报告。 但是，我们建议改为使用增强型 Microsoft 365 管理中心报告。 Excel 2013 报告工作簿计划将在未来弃用。 有关下载并安装此工作簿的更多概述信息和链接，请访问以下[下载页](https://go.microsoft.com/fwlink/p/?LinkId=271776)。 若要了解如何使用工作簿，请参阅 [Mail Protection Reports Using the Excel Reporting Workbook](https://go.microsoft.com/fwlink/p/?LinkId=285211)（使用 Excel 报告工作簿的邮件保护报告）。 
  
### <a name="reporting-using-web-services"></a>Reporting using web services

通过使用 REST/OData 租户报告 web 服务，可以访问有关邮箱、组和邮件数据的摘要和详细报告，它是一个可用于创建自定义报告的编程界面。 有关详细信息，请参阅[Office 365 Reporting web services](https://go.microsoft.com/fwlink/p/?LinkId=287041)。
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a>EAC 中的报告功能和疑难解答工具

Exchange 管理中心将提供下列报告功能和疑难解答工具。
  
### <a name="trace-an-email-message"></a>跟踪电子邮件

邮件跟踪功能使您可以作为管理员，在电子邮件通过 Exchange Online 服务时对其进行跟踪。 该功能有助于您确定目标邮件是否被接收、拒绝、推迟或由 Exchange 服务进行了传递。 这使得您可以有效回答用户的问题，解决邮件流问题，并减少联系技术支持寻求帮助的需要。
  
> [!IMPORTANT]
> For troubleshooting general issues and trends, use the reporting tools to obtain such data. For single point specifics where details are needed about a message, use the message trace tool. 
  
有关邮件跟踪功能的详细信息，请参阅[跟踪电子邮件](https://go.microsoft.com/fwlink/p/?LinkId=271777)。
  
### <a name="auditing-reports"></a>审核报告

You can use audit logging to troubleshoot configuration issues by tracking specific changes made by administrators and to help you meet regulatory, compliance, and litigation requirements. Exchange Online provides two types of audit logging:
  
- Administrator audit logging records any action performed by an administrator. This can help you troubleshoot configuration issues or identify the cause of security-related or compliance-related problems. 
    
- Mailbox audit logging records whenever a mailbox is accessed by someone other than the person who owns the mailbox. This can help you determine who has accessed a mailbox and what they've done. 
    
有关审核日志记录的详细信息，请参阅[审核报告](https://go.microsoft.com/fwlink/p/?LinkId=271779)。
  
### <a name="unified-messaging-reports"></a>统一消息报告

You can use these reports to monitor and troubleshoot Unified Messaging (UM) in your Exchange Online organization. For more information, see [Run Reports for Voice Mail Calls](https://go.microsoft.com/fwlink/p/?LinkId=287042).
  
## <a name="feature-availability"></a>功能可用性

若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅[Exchange Online 服务说明](exchange-online-service-description.md)。
  

