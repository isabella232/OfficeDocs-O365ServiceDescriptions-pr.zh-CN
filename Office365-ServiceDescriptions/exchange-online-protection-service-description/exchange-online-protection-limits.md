---
title: Exchange Online Protection 限制
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: f866fe3b-a183-4e6d-abd9-bbec0a0c7fae
description: Exchange Online Protection 的当前存在以下限制。除非另外指定，是不可配置，这些限制。
ms.openlocfilehash: 2e2efe4693cb7e5cdf52b4d035512657c39f03c2
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035172"
---
# <a name="exchange-online-protection-limits"></a>Exchange Online Protection 限制

Exchange Online Protection 的当前存在以下限制。除非另外指定，是不可配置，这些限制。 
  
> [!TIP]
> 有关 Exchange Online 中的限制的详细信息，请参阅[Exchange Online 限制](../exchange-online-service-description/exchange-online-limits.md)。传输规则限制也适用于 EOP 独立客户。Exchange Online 的收件人比率和邮件比率限制不适用于 EOP 独立客户。 
  
- **域限制** 最多可以为每个租户添加 900 个域。这 900 个域的限制包含子域，也可以根据需要使用笼统选项对子域进行匹配。有关详细信息，请参阅 [在 EOP 中管理接受的域](https://go.microsoft.com/fwlink/p/?LinkId=282239)。
    
- **邮件大小限制** EOP 独立客户的邮件大小上限（包括附件）为 150 MB。 
    
- **发送的出站邮件的数量** 通过 EOP 发送的出站邮件的数量限制较高，足以保证常规电子邮件通信不会被识别为垃圾邮件通信。如果您想要批量发送商业电子邮件，而不是通过 EOP 发送出站邮件，则我们建议您要么使用第三方电子邮件服务提供商 (ESP)，要么通过本地电子邮件服务器发送邮件。 
    
- **收件人限制** 只要发送主机可以将邮件划分为收件人不足 500 个的"区块"，则对限制没有明确的定义。但是，每个"区块"将被有效地视为一封新邮件。邮件如果在短时间里聚集过多、或来自信誉不佳的主机，或含可疑内容，就会受到限制或阻止。 
    
- **IP 允许列表或 IP 阻止列表限制** 在连接筛选器中配置 IP 允许列表或 IP 阻止列表时，您最多可以指定 1273 个条目，每个条目可以是单个 IP 地址或从 /24 到 /32 的 IP 地址的 CIDR 范围。 
    
- **邮件延期限制** 延期的邮件将在我们的队列中保留 2 天。重试发送邮件的依据为从收件人的邮件系统收到的错误类型。邮件每 15 分钟重试一次。 
    
- **垃圾邮件隔离保留期限** 默认情况下，发送到隔离服务器的垃圾邮件保留 15 天。管理员可通过内容筛选器策略降低此值。 
    
- **最终用户的垃圾邮件隔离通知** 默认情况下，如果启用，最终用户垃圾邮件隔离通知将每 3 天发送一次。它们可以配置为每 1 至 15 天发送一次。 
    
- **报告和邮件跟踪限制** 有关报告和邮件跟踪限制，请参阅 [Exchange Online Protection 中的报告和邮件跟踪](https://go.microsoft.com/fwlink/?LinkId=394248)中的"报告和邮件跟踪数据的可用性与延迟"部分。
    
### <a name="limits-across-eop-options"></a>各个 EOP 选项的限制

|**功能**|****独立 EOP****|****EOP 功能Exchange Online****|****Exchange 企业版 CAL 带服务****|
|:-----|:-----|:-----|:-----|
|域限制  <br/> |900  <br/> |900  <br/> |900  <br/> |
|邮件大小限制（包括附件）  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|收件人限制  <br/> |请参阅以上"收件人限制"  <br/> |从托管的邮箱发送时含 500 个收件人；请参阅以上用于其他方案的"收件人限制''  <br/> |请参阅以上"收件人限制"  <br/> |
|安全发件人限制  <br/> |1024 个条目  <br/> |1024 个条目  <br/> ||
|阻止的发件人限制  <br/> |1024 个条目  <br/> |1024 个条目  <br/> ||
|IP 允许列表或 IP 阻止列表限制  <br/> |1273 个条目  <br/> |1273 个条目  <br/> |1273 个条目  <br/> |
|邮件延迟限制  <br/> |2 天，每 15 分钟重试一次  <br/> |2 天，每 15 分钟重试一次  <br/> |2 天，每 15 分钟重试一次  <br/> |
|垃圾邮件隔离的保留期  <br/> |默认为 15 天，但可以缩短  <br/> |默认为 15 天，但可以缩短  <br/> |默认为 15 天，但可以缩短  <br/> |
|最终用户垃圾邮件隔离通知  <br/> |默认为 3 天，可配置为 1 到 15 天  <br/> |默认为 3 天，可配置为 1 到 15 天  <br/> |默认为 3 天，可配置为 1 到 15 天  <br/> |
   

