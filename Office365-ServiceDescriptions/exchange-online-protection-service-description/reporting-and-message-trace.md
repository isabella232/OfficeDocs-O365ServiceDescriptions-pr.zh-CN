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
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: b9263f99-5921-44fd-bb4c-0d487b59a656
description: 阅读本文，了解 Microsoft Exchange Online Protection (EOP) 中的报告和邮件) 。
ms.openlocfilehash: 2a920ba65c98a612d4343b893458b5bb34a4959e
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/24/2021
ms.locfileid: "59672201"
---
# <a name="reporting-and-message-trace-in-exchange-online-protection"></a>Exchange Online Protection 中的报告和邮件跟踪

Microsoft Exchange Online Protection (EOP) 提供许多不同的报告，可帮助您确定组织的总体状态和运行状况。 某些报告在 EAC Microsoft 365 管理中心中提供，而其他报告Exchange管理中心 (EAC) 。

要查找有关 EOP 所有功能的信息吗？ 请参阅 Exchange Online Protection[服务说明](exchange-online-protection-service-description.md)。

## <a name="microsoft-365-admin-center-reports"></a>Microsoft 365 管理中心报告

Microsoft 365 管理中心 中的"报告"页提供了有关邮件通信、垃圾邮件和恶意软件检测以及受邮件流规则影响的邮件的信息 (也称为传输规则) 或数据丢失防护 (DLP) 策略。 有关保护、规则和 DLP 的增强报告为 EOP 管理员提供了交互式报告体验。 这些报告提供了摘要数据，以及深入了解各个邮件详细信息的功能。

有关这些报告的更多详细信息，请参阅使用邮件 [保护报告查看有关恶意软件、垃圾邮件和规则检测的数据](/exchange/monitoring/use-mail-protection-reports)。

## <a name="reporting-using-web-services"></a>Reporting using web services

> [!NOTE]
> 许多基于 REST 的报告功能和相关 cmdlet 在 2018 年 1 月已弃用。 有关 Microsoft Graph 中的可用替换Office 365，请参阅在 Microsoft Graph 中处理[使用情况报表的Graph。](/graph/api/resources/report)

不适用于 EOP 独立客户。 您可以使用 REST/OData 租户报告 Web 服务以编程方式收集有关邮件数据的摘要和详细报告，还可以在自定义 Web 管理门户的网页上显示数据。

## <a name="message-trace"></a>邮件跟踪

通过 EAC 中的邮件跟踪功能，您可以作为管理员跟踪通过 EOP 传递的电子邮件。 该功能有助于你确定目标电子邮件是被接收、拒绝、延迟，还是由服务进行传递。 它还显示邮件在最终状态前其上发生的操作。 获取特定邮件的详细信息后，可以有效回答用户的问题、排查邮件流问题、验证策略更改，并减少需要联系技术支持寻求帮助的情况。 有关详细信息，请参阅[运行邮件跟踪，并查看](/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results)管理中心Exchange结果。

## <a name="feature-availability"></a>功能可用性

若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅Exchange Online Protection[说明](exchange-online-protection-service-description.md)。