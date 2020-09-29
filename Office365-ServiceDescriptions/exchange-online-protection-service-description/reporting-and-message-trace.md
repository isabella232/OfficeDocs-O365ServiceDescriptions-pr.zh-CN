---
title: Exchange Online Protection 中的报告和邮件跟踪
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- reporting-and-message-trace-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9263f99-5921-44fd-bb4c-0d487b59a656
description: 阅读本文以了解 Microsoft Exchange Online Protection (EOP) 中的报告和邮件跟踪。
ms.openlocfilehash: 6690c246620d4324610213b4968367cff0d30cf9
ms.sourcegitcommit: e342174df76128430dfc8c971716da5c4b2942ac
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/28/2020
ms.locfileid: "48293658"
---
# <a name="reporting-and-message-trace-in-exchange-online-protection"></a>Exchange Online Protection 中的报告和邮件跟踪

Microsoft Exchange Online Protection (EOP) 提供许多不同的报告，可帮助您确定组织的总体状态和运行状况。 某些报告在 Microsoft 365 管理中心中可用，而其他报告在 Exchange 管理中心 (EAC) 中可用。

要查找有关 EOP 所有功能的信息吗？ 请参阅 [Exchange Online Protection 服务说明](exchange-online-protection-service-description.md)。

## <a name="microsoft-365-admin-center-reports"></a>Microsoft 365 管理中心报告

Microsoft 365 管理中心中的 "报告" 页提供有关邮件流量、垃圾邮件和恶意软件检测项的信息，以及受邮件流规则影响的邮件 (也称为传输规则) 或数据丢失防护 (DLP) 策略。 有关保护、规则和 DLP 的增强报告为 EOP 管理员提供了交互式报告体验。 这些报告提供了摘要数据，以及深入了解各个邮件详细信息的功能。

有关这些报告的更多详细信息，请参阅 [使用邮件保护报告查看关于恶意软件、垃圾邮件和规则检测的数据](https://docs.microsoft.com/exchange/monitoring/use-mail-protection-reports)。

## <a name="reporting-using-web-services"></a>Reporting using web services

> [!NOTE]
> 许多基于 REST 的报告功能和相关 cmdlet 在2018年1月已弃用。 有关 Office 365 中可用的替换 Microsoft Graph 报告的信息，请参阅 [在 Microsoft graph 中使用使用率报告](https://go.microsoft.com/fwlink/p/?LinkID=865135)主题。

不适用于 EOP 独立客户。 您可以使用 REST/OData 租户报告 web 服务以编程方式收集有关邮件数据的摘要和详细报告，并且您可以在自定义 web 管理门户中的网页上显示数据。

## <a name="message-trace"></a>邮件跟踪

EAC 中的邮件跟踪功能使您可以作为管理员，在电子邮件通过 EOP 时执行这些操作。 该功能有助于你确定目标电子邮件是被接收、拒绝、延迟，还是由服务进行传递。 它还显示邮件在最终状态前其上发生的操作。 获取特定邮件的详细信息后，可以有效回答用户的问题、排查邮件流问题、验证策略更改，并减少需要联系技术支持寻求帮助的情况。 有关详细信息，请参阅 [运行邮件跟踪和在 Exchange 管理中心中查看结果](https://docs.microsoft.com/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results)。

## <a name="feature-availability"></a>功能可用性

若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅 [Exchange Online Protection 服务说明](exchange-online-protection-service-description.md)。
