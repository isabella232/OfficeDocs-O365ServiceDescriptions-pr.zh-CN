---
title: 报告功能和疑难解答工具
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Online EAC 管理中心管理中心内和场外Exchange各种 (功能) 。
ms.openlocfilehash: fa80cd6c7d8e9e5f0527c478474cffe17e9204af
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652686"
---
# <a name="reporting-features-and-troubleshooting-tools"></a>报告功能和疑难解答工具

Microsoft Exchange Online EAC 管理中心管理中心内和场外Exchange各种 (功能) 。
  
## <a name="reporting-features"></a>报告功能

Exchange Online客户可以通过下载报告工作簿Microsoft 365 Web 服务来访问 Excel 报告中心中的报告。
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a>管理中心Microsoft 365报告

管理中心中的"报告"Microsoft 365报告提供有关邮箱和组的摘要信息。 例如，其中有一项报告将列出按天、星期、月份或年份创建和删除的组的数量。 它还有许多有关新邮箱和已删除邮箱的摘要报告，以及活动和不活动邮箱的摘要报告。 
  
此外，Microsoft 365 管理中心中的"报告"页包含邮件数据报告，其中提供有关受 Exchange 传输规则或数据丢失防护 (DLP) 策略影响的邮件通信、垃圾邮件和恶意软件检测以及邮件的信息。 有关保护、规则和 DLP 的增强报告为 Exchange Online 管理员提供了交互式报告体验。 这些报告提供了摘要数据，以及深入了解各个邮件详细信息的功能。
  
有关每个订阅中可用的报告详细信息， [请参阅报告](../office-365-platform-service-description/reports.md)。 有关 Microsoft 365 管理中心中的"报告"页面的更多详细信息，请参阅查看和下载[有关 Office 365](/microsoft-365/admin/activity-reports/activity-reports)中的服务使用情况的报告和使用邮件保护报告查看有关恶意软件、垃圾邮件和规则检测[的数据](/exchange/monitoring/use-mail-protection-reports)。
  
### <a name="reporting-using-the-excel-reporting-workbook"></a>使用 Excel 报告工作簿进行报告

还可以使用 Excel 2013 报告工作簿来查看具有细分功能的摘要报告。 但是，我们建议改为使用增强Microsoft 365管理中心报告。 Excel 2013 报告工作簿计划将在未来弃用。 有关下载并安装此工作簿的更多概述信息和链接，请访问以下[下载页](https://go.microsoft.com/fwlink/p/?LinkId=271776)。 若要了解如何使用工作簿，请参阅 [Mail Protection Reports Using the Excel Reporting Workbook](/previous-versions/exchange-server/exchange-150/jj945734(v=exchg.150))（使用 Excel 报告工作簿的邮件保护报告）。 
  
### <a name="reporting-using-web-services"></a>Reporting using web services

REST/OData 租户报告 Web 服务是允许您创建自定义报告的编程界面，可以访问有关邮箱、组和邮件数据的摘要报告和详细报告。 有关详细信息，请参阅报告[Office 365服务](/previous-versions/office/developer/o365-enterprise-developers/jj984325(v=office.15))。
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a>EAC 中的报告功能和疑难解答工具

Exchange 管理中心将提供下列报告功能和疑难解答工具。
  
### <a name="trace-an-email-message"></a>跟踪电子邮件

通过邮件跟踪功能，您可以作为管理员跟踪电子邮件，因为它们通过您的 Exchange Online 服务。 该功能有助于您确定目标邮件是否被接收、拒绝、推迟或由 Exchange 服务进行了传递。 这使得您可以有效回答用户的问题，解决邮件流问题，并减少联系技术支持寻求帮助的需要。
  
> [!IMPORTANT]
> 对于一般问题与走向的疑难解答，使用报告工具获取相关数据。使用邮件跟踪工具获取需要邮件详细信息的单点信息。 
  
有关邮件跟踪功能的详细信息，请参阅[跟踪电子邮件](/exchange/monitoring/trace-an-email-message/trace-an-email-message)。
  
### <a name="auditing-reports"></a>审核报告

您可以使用审核日志记录通过跟踪管理员所做的特定更改来解决配置问题，并帮助您满足法规、遵从性以及诉讼等要求。Exchange Online 提供两种类型的审核日志记录：
  
- 管理员审核日志记录。它将记录由管理员执行的任何操作。这可以帮助您解决配置问题，或找出与安全或合规性相关的问题的原因。 
    
- 邮箱审核日志记录会在邮箱所有者之外的其他人每次访问邮箱时进行记录。这可以帮助您确定谁访问了邮箱以及访问者完成了哪些操作。 
    
有关审核日志记录的详细信息，请参阅[审核报告](/exchange/security-and-compliance/exchange-auditing-reports/exchange-auditing-reports)。
  
### <a name="unified-messaging-reports"></a>统一消息报告

可使用这些报告监视并排查 Exchange Online 组织中的统一消息 (UM) 问题。有关详细信息，请参阅 [Run Reports for Voice Mail Calls](/exchange/voice-mail-unified-messaging/run-voice-mail-call-reports/run-voice-mail-call-reports)（生成语音邮件呼叫报告）。
  
## <a name="feature-availability"></a>功能可用性

若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅Exchange Online[说明](exchange-online-service-description.md)。
