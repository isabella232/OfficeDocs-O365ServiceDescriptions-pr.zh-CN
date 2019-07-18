---
title: 邮件流[EOP]
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: 对于大多数使用 Office 365 的组织，我们可以为其托管邮箱并处理邮件流。 这是最简单的配置，意味着 Office 365 管理所有邮箱和筛选。 但是，某些组织有需要将所有邮箱保留在本地的业务。 借助 Exchange Online Protection (EOP)，可以实现上述功能，并在云中提供防病毒和反垃圾邮件处理。 有关详细信息以及购买 EOP 的信息，请转到 Exchange Online Protection。
ms.openlocfilehash: 59ccec07af154275697c671014aae6e204710031
ms.sourcegitcommit: 96dc758c790ddaf05f5c2b836451b417729cf119
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/18/2019
ms.locfileid: "35776623"
---
# <a name="mail-floweop"></a>邮件流[EOP]

对于大多数使用 Office 365 的组织，我们可以为其托管邮箱并处理邮件流。 这是最简单的配置，意味着 Office 365 管理所有邮箱和筛选。 但是，某些组织有需要将所有邮箱保留在本地的业务。 借助 Exchange Online Protection (EOP)，可以实现上述功能，并在云中提供防病毒和反垃圾邮件处理。 有关详细信息以及购买 EOP 的信息，请转到 [Exchange Online Protection](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection)。
  
正在查找关于域管理或基于目录的边缘阻止 (DBEB) 的信息？请参阅[收件人、域和公司管理](recipient-domain-and-company-management.md)。有关所有 EOP 功能的详细信息，请参阅[Exchange Online Protection 服务说明](exchange-online-protection-service-description.md)。
  
## <a name="routing-email-between-office-365-and-your-own-email-servers"></a>在 Office 365 和自己的电子邮件服务器之间路由电子邮件
<a name="BKMK_outboundmailrouting"> </a>

可以配置连接器以启用 Office 365（包括 Exchange Online 或 EOP）与基于 SMTP 的电子邮件服务器（如 Exchange）之间的邮件流。有关详细信息，请参阅[Do I need a connector](http://technet.microsoft.com/library/16731ae9-c909-49dd-bffc-a46e6151fc29.aspx)？和[Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx)。
  
## <a name="secure-messaging-with-a-trusted-partner"></a>与受信任合作伙伴的安全邮件
<a name="BKMK_securemessagingwithatrustedpartner"> </a>

作为 EOP 客户，你可以使用 Office 365 连接器设置与受信任合作伙伴的安全邮件流。Office 365 支持通过传输层安全性 (TLS) 的安全通信，并且你可以创建一个连接器，强制通过 TLS 进行加密。[TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx) 是通过 Internet 为通信提供安全的加密协议。通过使用连接器，可以使用自签名证书或经证书颁发机构 (CA) 验证的证书配置强制的入站和出站 TLS。还可以应用其他安全限制，如指定合作伙伴组织发送邮件时使用的域名或 IP 地址范围。 
  
有关详细信息，请参阅[将连接器设置为确保与合作伙伴组织之间实现安全的邮件流](https://technet.microsoft.com/en-us/library/dn751021%28v=exchg.150%29.aspx)。
  
## <a name="safe-listing-a-partners-ip-address"></a>合作伙伴 IP 地址安全列表
<a name="BKMK_safelistingapartnersipaddress"> </a>

可以将受信任伙伴的 IP 地址添加到安全列表中，以确保他们发送给你的邮件不经过垃圾邮件筛选。为此，可以使用连接筛选器的 IP 允许列表。有关详细信息，请参阅[配置连接筛选器策略](https://go.microsoft.com/fwlink/p/?LinkID=287108)。
  
## <a name="conditional-mail-routing"></a>有条件的邮件路由
<a name="BKMK_conditionalmailrouting"> </a>

可以使用传输规则配置连接器，以便根据条件将邮件路由到特定的站点。有关详细信息，请参阅[Scenario: Conditional email routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx)。
  
## <a name="hybrid-mail-routing"></a>Hybrid mail routing
<a name="BKMK_hybridmailrouting"> </a>

混合表示将一部分邮箱托管于本地上，而另一部分托管于云 (Exchange Online) 中。可以从独立（本地）部署移动到混合部署。
  
如果拥有混合部署，则可以使用 EOP 保护云和本地邮箱。使用 EOP 进行保护时，本地邮箱需要独立许可证。有关混合部署中的邮件路由的详细信息，请参阅 [Exchange 混合部署中的传输路由](https://go.microsoft.com/fwlink/p/?LinkId=271757)。
  
[Microsoft Exchange Server 部署助理](https://go.microsoft.com/fwlink/p/?LinkId=287036)还提供了有关混合部署预配和混合邮件传输的详细指导。 
  
## <a name="feature-availability"></a>功能可用性
<a name="BKMK_hybridmailrouting"> </a>

若要查看在各个 Office 365 计划、独立选项和内部部署解决方案之间的功能可用性，请参阅 [Exchange Online Protection 服务说明](exchange-online-protection-service-description.md)。
  

