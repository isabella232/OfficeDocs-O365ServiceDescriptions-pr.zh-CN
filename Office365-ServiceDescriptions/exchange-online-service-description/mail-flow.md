---
title: 邮件流
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-mail-flow
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 8e5267e6-d224-485b-a081-c71a1fd0c4c3
description: 对于大多数组织来说，我们托管邮箱并处理邮件流。 这是最简单的配置，意味着 Microsoft 管理所有邮箱和筛选。 但是，某些组织需要进行更复杂的邮件流设置来确保它们遵守特定的法规或业务需要。 你可以在这里找到这些选项的信息。
ms.openlocfilehash: 1ada5a3199e6ae65c6aaa99873f13a4025366a8d
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132716"
---
# <a name="mail-flow"></a>邮件流

对于大多数组织来说，我们托管邮箱并处理邮件流。 这是最简单的配置，意味着 Microsoft 管理所有邮箱和筛选。 但是，某些组织需要进行更复杂的邮件流设置来确保它们遵守特定的法规或业务需要。 你可以在这里找到这些选项的信息。 
  
## <a name="custom-routing-of-outbound-email"></a>出站电子邮件的自定义路由

Microsoft Exchange Online 可通过本地服务器或托管服务（有时称为"智能托管"）路由来自组织的邮件流。 这样，你的组织可以使用数据丢失防护（DLP）设备，对传出电子邮件执行自定义后续处理，并通过专用网络将电子邮件传递给业务合作伙伴。 Exchange Online 还支持地址重写，其中，传出电子邮件将通过修改地址的本地网关路由。 此功能使您可以隐藏子域，使来自多域组织的电子邮件显示为单个域，或使合作伙伴中继电子邮件显示为从组织内部发送。 管理员在 Exchange 管理中心 (EAC) 内配置自定义的电子邮件路由。
  
有关详细信息，请参阅[设置连接器以在 Microsoft 和您自己的电子邮件服务器之间路由邮件](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail)。
  
> [!IMPORTANT]
> Exchange Online 可将邮件流传入和传出组织。 如果您的收件人域托管在 Exchange Online 中，且 DNS MX 记录指向 Exchange Online Protection，则从您的租户到收件人的邮件流将不会通过 internet 传输。
  
## <a name="secure-messaging-with-a-trusted-partner"></a>与受信任合作伙伴的安全邮件

作为 Exchange Online 客户，您可以使用 Microsoft 连接器设置受信任合作伙伴的安全邮件流。 Microsoft 支持通过传输层安全性（TLS）进行安全通信，并且可以创建连接器以通过 TLS 强制执行加密。 [TLS](https://docs.microsoft.com/office365/securitycompliance/exchange-online-uses-tls-to-secure-email-connections)是一种加密协议，提供通过 internet 进行通信的安全性。 通过使用连接器，可以使用自签名证书或经证书颁发机构 (CA) 验证的证书配置强制的入站和出站 TLS。 还可以应用其他安全限制，如指定合作伙伴组织发送邮件时使用的域名或 IP 地址范围。 
  
有关详细信息，请参阅[Set up connectors for secure mail flow with a partner organization](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner)。
  
> [!IMPORTANT]
> 可能需要经 CA 验证的证书。 
  
## <a name="conditional-mail-routing"></a>有条件的邮件路由

You can direct mail to specific sites by using connectors and transport rules. With criteria-based routing, you can choose a connector based on specific conditions.
  
有关详细信息，请参阅[Scenario: Conditional mail routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing)。
  
## <a name="incoming-mail-safe-list"></a>传入邮件安全列表

You can add a trusted partner's IP address to a safe list to ensure that messages the partner sends to you are not subject to anti-spam filtering. To do this, you can use the connection filter's IP Allow list.
  
有关详细信息，请参阅[Configure the connection filter policy](https://docs.microsoft.com/office365/SecurityCompliance/configure-the-connection-filter-policy)。
  
## <a name="hybrid-email-routing"></a>混合电子邮件路由

A hybrid deployment gives organizations the ability to extend the feature-rich experience and administrative control they have with their existing on-premises Microsoft Exchange organization to the cloud. With hybrid transport, messages sent between recipients in either organization are authenticated, encrypted, and transferred using Transport Layer Security (TLS), and appear as "internal" to Exchange components such as transport rules, journaling, and anti-spam policies. You configure hybrid transport by using the Hybrid Configuration Wizard in Exchange Server.
  
若要详细了解混合部署中的邮件路由，请参阅 [Exchange 混合部署中的传输路由](https://go.microsoft.com/fwlink/p/?LinkId=271757)。
  
[Microsoft Exchange Server 部署助理](https://go.microsoft.com/fwlink/p/?LinkId=287036)还提供了有关混合部署预配和混合邮件传输的详细指导。 
  
### <a name="shared-address-space-with-on-premises-routing-control-mx-points-to-on-premises"></a>含内部路由控制的共享地址空间（MX 指向内部）

具有本地路由控制的共享地址空间（MX 指向本地）是一种混合部署邮件路由方案，其中邮箱托管在 Exchange Online 和部分内部部署中，传入和传出 internet 邮件流通过内部部署 Exchange 组织进行路由。 此方案也称为集中邮件传输。 在这种情况下，将使用 EOP 设置 Exchange Online，并将传入 internet 邮件路由到您的本地邮件服务器，然后再将其路由到 EOP，并最终路由到 Exchange Online 中托管的邮箱。 此外，来自 Exchange Online 邮箱的传出邮件通过内部部署 Exchange 组织路由，以获取发送给外部收件人的邮件。 使用此配置，您可以对内部部署 Exchange 组织和 Exchange Online 组织中的所有邮箱使用一个 SMTP 域名称空间。 
  
若要详细了解混合部署中的传输选项，请参阅 [Exchange 混合部署的传输选项](https://go.microsoft.com/fwlink/p/?LinkID=271758)。
  
### <a name="shared-address-space-without-on-premises-routing-control-mx-points-to-eop"></a>不含内部路由控制的共享地址空间（MX 指向 EOP）

没有本地路由控制的共享地址空间（MX 指向 EOP）是一种混合邮件路由方案，在该方案中，邮箱使用 Exchange Online 和部分内部部署在云中进行了部分托管，并且 MX 记录指向 EOP。 当您使用 Microsoft 托管您的组织的某些邮箱，并且您希望 EOP 保护您的内部部署和云邮箱时，此方案适用。 在这种情况下，发送到组织中的收件人的邮件最初通过 EOP 路由，在垃圾邮件和策略筛选发生之前，它将进入您的本地邮箱和云邮箱。 
  
若要详细了解混合部署中的传输选项，请参阅 [Exchange 混合部署的传输选项](https://go.microsoft.com/fwlink/p/?LinkID=271758)。
  
### <a name="troubleshooting-a-deployment-with-the-hybrid-configuration-wizard"></a>使用混合配置向导解决部署问题

Using the Hybrid Configuration Wizard to configure a hybrid deployment in Microsoft Exchange Server greatly minimizes the potential that the hybrid deployment will experience problems. However, there are some typical areas outside the scope of the Hybrid Configuration Wizard that, if misconfigured, may present problems in a hybrid deployment. These include proper Client Access server configuration and proper certificate installation and configuration.
  
若要详细了解如何使用混合配置向导解决部署问题，请参阅[混合部署故障排除](https://go.microsoft.com/fwlink/p/?LinkId=271040)。
  
### <a name="managing-a-hybrid-configuration"></a>管理混合配置

You can modify an existing hybrid configuration by changing settings in the Hybrid Configuration Wizard. Scenarios include disabling centralized transport or disabling secure mail transport.
  
若要详细了解如何管理混合部署配置，请参阅[管理混合部署](https://go.microsoft.com/fwlink/p/?LinkId=271044)。
  
### <a name="hybrid-deployment-requirements"></a>混合部署要求

若要详细了解混合部署要求，请参阅[混合部署先决条件](https://go.microsoft.com/fwlink/p/?LinkId=271759)。
  
> [!IMPORTANT]
> 在某些混合配置中，您必须为内部邮箱购买 Exchange Online Protection 许可证。 
  
## <a name="feature-availability"></a>功能可用性

若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅[Exchange Online 服务说明](exchange-online-service-description.md)。
  