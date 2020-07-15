---
title: Exchange Online Protection 限制
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: f866fe3b-a183-4e6d-abd9-bbec0a0c7fae
description: Exchange Online Protection 当前存在以下限制。 除非另行指定，否则无法配置这些限制。
ms.openlocfilehash: 3c5a8e0c5f9a19c9cae81b3bc1e39bb153af0137
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/14/2020
ms.locfileid: "45133006"
---
# <a name="exchange-online-protection-limits"></a>Exchange Online Protection 限制

Exchange Online Protection 当前存在以下限制。 除非另行指定，否则无法配置这些限制。 
  
> [!TIP]
> 有关 Exchange Online 中的限制的详细信息，请参阅[Exchange online 限制](../exchange-online-service-description/exchange-online-limits.md)。 传输规则限制也适用于 EOP 独立客户。 Exchange Online 的收件人比率和邮件比率限制不适用于 EOP 独立客户。 
  
- **Domain limit** You can add up to 900 domains per tenant. Subdomains can be included in this 900 limit, or if necessary, as part of a catch-all option, match subdomains. For more information, see [Manage Accepted Domains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).
    
- **邮件大小限制** EOP 独立客户的邮件大小上限（包括附件）为 150 MB。 
    
- **Number of outbound messages sent** The limit for the number of outbound messages sent through EOP is high enough to ensure that normal email communication is not treated as spam. If you want to send commercial bulk email messages, rather than sending outbound messages through EOP, we recommend that you either use a third-party email service provider (ESP) or send them through your on-premises email servers. 
    
- **Recipient limit** As long as the sending host can split the message into "chunks" of fewer than 500 recipients, no explicit limit is defined. However, each "chunk" is effectively treated as a new message. Too many messages in a short period, messages from a host with a poor reputation, or messages with questionable content could be throttled or blocked. 
    
- **IP 允许列表或 IP 阻止列表限制** 在连接筛选器中配置 IP 允许列表或 IP 阻止列表时，您最多可以指定 1273 个条目，每个条目可以是单个 IP 地址或从 /24 到 /32 的 IP 地址的 CIDR 范围。 
    
- **邮件延迟限制**延迟中的邮件将保留在队列中24小时之内。 重试发送邮件的依据为从收件人的邮件系统收到的错误类型。 邮件每 15 分钟重试一次。 
    
- **垃圾邮件隔离保留期**默认情况下，发送到隔离的垃圾邮件将保留30天。 管理员可通过内容筛选器策略降低此值。 
    
- **End-user spam quarantine notifications** By default, if enabled, end-user spam quarantine notifications are sent every 3 days. They can be configured to be sent every 1 to 15 days. 
    
- **报告和邮件跟踪限制**有关报告和邮件跟踪限制，请参阅[Exchange Online Protection 中的报告和邮件跟踪](https://go.microsoft.com/fwlink/?LinkId=394248)中的 "报告和邮件跟踪数据可用性和延迟" 部分。
    
### <a name="limits-across-eop-options"></a>各个 EOP 选项的限制

|**功能**|****独立 EOP****|****EOP 功能Exchange Online****|****Exchange 企业版 CAL 带服务****|
|:-----|:-----|:-----|:-----|
|域限制  <br/> |900  <br/> |900  <br/> |900  <br/> |
|邮件大小限制（包括附件）  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|收件人限制  <br/> |请参阅以上"收件人限制"  <br/> |从托管的邮箱发送时含 500 个收件人；请参阅以上用于其他方案的"收件人限制''  <br/> |请参阅以上"收件人限制"  <br/> |
|安全发件人限制  <br/> |1024 个条目  <br/> |1024 个条目  <br/> ||
|每个策略阻止的发件人限制  <br/> |1024 个条目  <br/> |1024 个条目  <br/> ||
|IP 允许列表或 IP 阻止列表限制  <br/> |1273 个条目  <br/> |1273 个条目  <br/> |1273 个条目  <br/> |
|邮件延迟限制  <br/> |1天，每15分钟重试一次  <br/> |1天，每15分钟重试一次  <br/> |1天，每15分钟重试一次  <br/> |
|垃圾邮件隔离的保留期  <br/> |30天（默认为30天），但可以降低  <br/> |30天（默认为30天），但可以降低  <br/> |30天（默认为30天），但可以降低  <br/> |
|最终用户垃圾邮件隔离通知  <br/> |默认为 3 天，可配置为 1 到 15 天  <br/> |默认为 3 天，可配置为 1 到 15 天  <br/> |默认为 3 天，可配置为 1 到 15 天  <br/> |
   

