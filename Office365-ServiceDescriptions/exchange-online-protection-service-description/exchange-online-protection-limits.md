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
description: Exchange Online Protection 目前存在以下限制。 除非另行指定，否则这些限制不可配置。
ms.openlocfilehash: 6c399c359d39f50a4bd359833fdf595415872bff
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173797"
---
# <a name="exchange-online-protection-limits"></a>Exchange Online Protection 限制

Exchange Online Protection 目前存在以下限制。 除非另行指定，否则这些限制不可配置。 
  
> [!TIP]
> 有关 Exchange Online 中限制的信息，请参阅 [Exchange Online 限制](../exchange-online-service-description/exchange-online-limits.md)。 传输规则限制也适用于 EOP 独立客户。 Exchange Online 的收件人比率和邮件比率限制不适用于 EOP 独立客户。 
  
- **域限制** - 每个租户最多可以添加 900 个域。 这 900 个域的限制包含子域，也可以根据需要使用笼统选项对子域进行匹配。 有关详细信息，请参阅 [在 EOP 中管理接受的域](/microsoft-365/security/office-365-security/exchange-online-protection-overview)。

- **远程域限制** - 每个租户最多可以添加 200 个远程域。
    
- **邮件大小限制** - EOP 独立客户（包括附件）的最大邮件大小为 150 MB。 
    
- **发送的出** 站邮件数 - 通过 EOP 发送的出站邮件数限制较高，足以确保正常的电子邮件通信不会被视为垃圾邮件。 如果您想要批量发送商业电子邮件，而不是通过 EOP 发送出站邮件，则我们建议您要么使用第三方电子邮件服务提供商 (ESP)，要么通过本地电子邮件服务器发送邮件。 
    
- **收件人** 限制 - 只要发送主机可以将邮件拆分为少于 500 个收件人的"区块"，就未定义显式限制。 但是，每个"区块"将被有效地视为一封新邮件。 邮件如果在短时间里聚集过多、或来自信誉不佳的主机，或含可疑内容，就会受到限制或阻止。 
    
- **IP** 允许或 IP 阻止列表限制 - 在连接筛选器中配置 IP 允许列表或 IP 阻止列表时，最多可以指定 1273 个条目，其中条目可以是单个 IP 地址或 IP 地址的 CIDR 范围，范围为 /24 到 /32。 
    
- **邮件延迟限制** - 延迟的邮件将在我们的队列中保留 24 小时。 重试发送邮件的依据为从收件人的邮件系统收到的错误类型。 邮件每 15 分钟重试一次。 
    
- **垃圾邮件隔离保留期** - 默认情况下，发送到隔离邮箱的垃圾邮件将保留 30 天。 管理员可通过内容筛选器策略降低此值。 
    
- **最终用户垃圾邮件隔离通知** - 默认情况下，如果启用，则每 3 天发送一次最终用户垃圾邮件隔离通知。 它们可以配置为每 1 至 15 天发送一次。 
    
- **报告和邮件跟踪限制** - 有关报告和邮件跟踪限制，请参阅 Exchange Online Protection 中的报告和邮件跟踪中的"报告和邮件跟踪数据的可用性和延迟 ["部分](/microsoft-365/security/office-365-security/reporting-and-message-trace-in-exchange-online-protection)。
    
### <a name="limits-across-eop-options"></a>各个 EOP 选项的限制

| 功能 | 独立 EOP | Exchange Online 中的 EOP 功能 | Exchange 企业版 CAL 带服务 |
|:-----|:-----|:-----|:-----|
|域限制  <br/> |900  <br/> |900  <br/> |900  <br/> |
|远程域限制  <br/> |200  <br/> |200  <br/> |200  <br/> |
|邮件大小限制（包括附件）  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|收件人限制  <br/> |请参阅以上"收件人限制"  <br/> |从托管的邮箱发送时含 500 个收件人；请参阅以上用于其他方案的"收件人限制''  <br/> |请参阅以上"收件人限制"  <br/> |
|安全发件人限制  <br/> |1024 个条目  <br/> |1024 个条目  <br/> ||
|每个策略的阻止发件人限制  <br/> |1024 个条目  <br/> |1024 个条目  <br/> ||
|IP 允许列表或 IP 阻止列表限制  <br/> |1273 个条目  <br/> |1273 个条目  <br/> |1273 个条目  <br/> |
|邮件延迟限制  <br/> |1 天，每 15 分钟重试一次  <br/> |1 天，每 15 分钟重试一次  <br/> |1 天，每 15 分钟重试一次  <br/> |
|垃圾邮件隔离的保留期  <br/> |默认为 30 天，但可以减少  <br/> |默认为 30 天，但可以减少  <br/> |默认为 30 天，但可以减少  <br/> |
|最终用户垃圾邮件隔离通知  <br/> |默认为 3 天，可配置为 1 到 15 天  <br/> |默认为 3 天，可配置为 1 到 15 天  <br/> |默认为 3 天，可配置为 1 到 15 天  <br/> |
