---
title: 邮件流Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: 阅读本文，了解 Microsoft Exchange Online Protection (EOP) 中的邮件流。
ms.openlocfilehash: 4cc64692eb9cfb338e4fa9ab1ad7d7b4f889e280
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/24/2021
ms.locfileid: "59672333"
---
# <a name="mail-flow-in-exchange-online-protection"></a>邮件流Exchange Online Protection

对于大多数使用 Microsoft 的组织，我们将托管您的邮箱并处理邮件流。 这是最简单的配置，意味着 Microsoft 管理所有邮箱和筛选。 但是，某些组织有需要将所有邮箱保留在本地的业务。 Exchange Online Protection (EOP) ，您可以在云中执行这一操作并提供防病毒和反垃圾邮件处理。 有关详细信息以及购买 EOP 的信息，请转到 [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection)。
  
正在查找关于域管理或基于目录的边缘阻止 (DBEB) 的信息？ 请参阅 [收件人、域和公司管理](recipient-domain-and-company-management.md)。 若要详细了解所有 EOP 功能，请参阅 Exchange Online Protection[服务说明](exchange-online-protection-service-description.md)。
  
## <a name="routing-email-between-microsoft-and-your-own-email-servers"></a>在 Microsoft 和自己的电子邮件服务器之间路由电子邮件

您可以配置连接器以在 Microsoft (（包括 Exchange Online 或 EOP) ）与基于 SMTP 的电子邮件服务器（如 Exchange）之间启用邮件流。 有关详细信息，请参阅[Do I need a connector](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)？ 设置 [连接器以在 Microsoft 和您自己的电子邮件服务器之间路由邮件](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail)。
  
## <a name="secure-messaging-with-a-trusted-partner"></a>与受信任合作伙伴的安全邮件

作为 EOP 客户，您可以使用 Microsoft 连接器设置与受信任合作伙伴的安全邮件流。 Microsoft 支持通过传输层安全性 (TLS) 安全通信，并且您可以创建连接器以通过 TLS 强制实施加密。 [TLS](/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections) 是一种加密协议，它为通过 Internet 的通信提供安全性。 通过使用连接器，可以使用自签名证书或经证书颁发机构 (CA) 验证的证书配置强制的入站和出站 TLS。 还可以应用其他安全限制，如指定合作伙伴组织发送邮件时使用的域名或 IP 地址范围。 
  
有关详细信息，请参阅[将连接器设置为确保与合作伙伴组织之间实现安全的邮件流](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner)。
  
## <a name="safe-listing-a-partners-ip-address"></a>合作伙伴 IP 地址安全列表

可以将受信任伙伴的 IP 地址添加到安全列表中，以确保他们发送给你的邮件不经过垃圾邮件筛选。为此，可以使用连接筛选器的 IP 允许列表。有关详细信息，请参阅[配置连接筛选器策略](/microsoft-365/security/office-365-security/configure-the-connection-filter-policy)。
  
## <a name="conditional-mail-routing"></a>有条件的邮件路由

可以使用传输规则配置连接器，以便根据条件将邮件路由到特定的站点。有关详细信息，请参阅[Scenario: Conditional email routing](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing)。
  
## <a name="hybrid-mail-routing"></a>混合邮件路由

混合表示将一部分邮箱托管于本地上，而另一部分托管于云 (Exchange Online) 中。可以从独立（本地）部署移动到混合部署。
  
如果拥有混合部署，则可以使用 EOP 保护云和本地邮箱。使用 EOP 进行保护时，本地邮箱需要独立许可证。有关混合部署中的邮件路由的详细信息，请参阅 [Exchange 混合部署中的传输路由](/exchange/transport-routing)。
  
[Microsoft Exchange Server 部署助理](/exchange/exchange-deployment-assistant)还提供了有关混合部署预配和混合邮件传输的详细指导。 
  
## <a name="feature-availability"></a>功能可用性

若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅Exchange Online Protection[说明](exchange-online-protection-service-description.md)。