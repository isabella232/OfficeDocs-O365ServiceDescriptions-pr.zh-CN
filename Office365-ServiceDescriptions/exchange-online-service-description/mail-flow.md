---
title: 邮件流
ms.author: sharik
author: skjerland
manager: mnirkhe
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
description: '对于大多数使用 Office 365 的组织，我们可以为其托管邮箱并处理邮件流。这是最简单的配置，意味着 Office 365 管理所有邮箱和筛选。但是，某些组织需要进行更复杂的邮件流设置来确保它们遵守特定的法规或业务需要。你可以在这里找到这些选项的信息。 '
ms.openlocfilehash: d21a5742ccbd032abbad822d4a686174ce5b8baf
ms.sourcegitcommit: 96dc758c790ddaf05f5c2b836451b417729cf119
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/18/2019
ms.locfileid: "35776783"
---
# <a name="mail-flow"></a>邮件流

对于大多数使用 Office 365 的组织，我们可以为其托管邮箱并处理邮件流。这是最简单的配置，意味着 Office 365 管理所有邮箱和筛选。但是，某些组织需要进行更复杂的邮件流设置来确保它们遵守特定的法规或业务需要。你可以在这里找到这些选项的信息。  
  
## <a name="custom-routing-of-outbound-email"></a>出站电子邮件的自定义路由

Microsoft Exchange Online 可通过本地服务器或托管服务（有时称为"智能托管"）路由来自组织的邮件流。这支持贵组织使用数据丢失防护 (DLP) 设备，执行传出电子邮件的自定义后期处理，并通过专用网络将电子邮件传递给业务合作伙伴。Exchange Online 还支持地址重写，其中，传出电子邮件将通过修改地址的本地网关路由。使用此功能，你可以隐藏子域，使多域组织中的电子邮件显示为单个域，或使合作伙伴中继的电子邮件显示为从组织内部发出。管理员在 Exchange 管理中心 (EAC) 内配置自定义的电子邮件路由。
  
有关详细信息，请参阅[Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx)。
  
> [!IMPORTANT]
> Exchange Online 可将邮件流传入和传出组织。 
  
## <a name="secure-messaging-with-a-trusted-partner"></a>与受信任合作伙伴的安全邮件

作为 Exchange Online 客户，你可以使用 Office 365 连接器设置与受信任合作伙伴的安全邮件流。Office 365 支持通过传输层安全性 (TLS) 的安全通信。可以创建一个连接器，强制通过 TLS 进行加密。[TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx) 是通过 Internet 为通信提供安全的加密协议。通过使用连接器，可以使用自签名证书或经证书颁发机构 (CA) 验证的证书配置强制的入站和出站 TLS。还可以应用其他安全限制，如指定合作伙伴组织发送邮件时使用的域名或 IP 地址范围。 
  
有关详细信息，请参阅[Set up connectors for secure mail flow with a partner organization](http://technet.microsoft.com/library/1ce4d6a4-41ba-4d1e-9ca9-e826252c1041.aspx)。
  
> [!IMPORTANT]
> 可能需要经 CA 验证的证书。 
  
## <a name="conditional-mail-routing"></a>有条件的邮件路由

你可以使用连接器和传输规则将邮件直接传递到特定站点。通过基于条件的路由，你可以基于特定条件选择连接器。
  
有关详细信息，请参阅[Scenario: Conditional mail routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx)。
  
## <a name="incoming-mail-safe-list"></a>传入邮件安全列表

你可以将受信任的合作伙伴的 IP 地址添加到安全列表中，以确保合作伙伴发送给你的邮件不经过反垃圾邮件筛选。为此，你可以使用连接筛选器的 IP 允许列表。
  
有关详细信息，请参阅[Configure the connection filter policy](http://technet.microsoft.com/library/6ae78c12-7bbe-44fa-ab13-c3768387d0e3.aspx)。
  
## <a name="hybrid-email-routing"></a>混合电子邮件路由

混合部署使组织可以将随其现有本地 Microsoft Exchange 组织提供的功能丰富的体验和管理控制扩展到云。通过混合传输，在任一组织中的收件人之间发送的邮件会经过身份验证、加密并使用传输层安全性 (TLS) 传输，并且向 Exchange 组件（如传输规则、日记和反垃圾邮件策略）显示为"内部"。通过使用 Exchange Server 中的混合配置向导配置混合传输。
  
若要详细了解混合部署中的邮件路由，请参阅 [Exchange 混合部署中的传输路由](https://go.microsoft.com/fwlink/p/?LinkId=271757)。
  
[Microsoft Exchange Server 部署助理](https://go.microsoft.com/fwlink/p/?LinkId=287036)还提供了有关混合部署预配和混合邮件传输的详细指导。 
  
### <a name="shared-address-space-with-on-premises-routing-control-mx-points-to-on-premises"></a>含内部路由控制的共享地址空间（MX 指向内部）

含本地路由控制的共享地址空间（MX 指向本地）是一种混合部署邮件路由方案。在这种方案中，一部分邮箱在 Exchange Online 中托管，一部分在本地托管，且传入和传出 Internet 邮件流均通过本地 Exchange 组织路由。此方案也称为"集中式邮件传输"。在此方案中，Exchange Online 设置为使用 EOP，入站 Internet 邮件将先路由至本地邮件服务器，然后路由至 EOP，最后路由至 Exchange Online 托管的邮箱中。此外，Exchange Online 邮箱的出站邮件将通过本地 Exchange 组织路由，以便邮件发送到外部收件人。使用此配置，你可以针对本地 Exchange 组织和 Exchange Online 组织中的所有邮箱使用一个 SMTP 域命名空间。 
  
若要详细了解混合部署中的传输选项，请参阅 [Exchange 混合部署的传输选项](https://go.microsoft.com/fwlink/p/?LinkID=271758)。
  
### <a name="shared-address-space-without-on-premises-routing-control-mx-points-to-eop"></a>不含内部路由控制的共享地址空间（MX 指向 EOP）

不含本地路由控制的共享地址空间（MX 指向 EOP）是一种混合路由方案。在这种方案中，一部分邮箱托管在使用 Exchange Online 的云中，一部分托管在本地中，且 MX 记录指向 EOP。使用 Office 365 服务来托管组织的部分邮箱并且需要 EOP 保护本地邮箱和云邮箱时，此方案将适用。在此方案中，发送到你组织内收件人的邮件最初通过 EOP（从而筛选垃圾邮件和策略）路由，然后才到达你的本地邮箱和云邮箱。 
  
若要详细了解混合部署中的传输选项，请参阅 [Exchange 混合部署的传输选项](https://go.microsoft.com/fwlink/p/?LinkID=271758)。
  
### <a name="troubleshooting-a-deployment-with-the-hybrid-configuration-wizard"></a>使用混合配置向导解决部署问题

在 Microsoft Exchange Server 中使用混合配置向导来配置混合部署将极大地减少混合部署出现问题的可能性。然而，这里有一些混合配置向导范围之外的典型区域，如果配置不当的话，可能导致混合部署出现问题。这些配置包括正确的客户端访问服务器配置，以及正确的证书安装和配置。
  
若要详细了解如何使用混合配置向导解决部署问题，请参阅[混合部署故障排除](https://go.microsoft.com/fwlink/p/?LinkId=271040)。
  
### <a name="managing-a-hybrid-configuration"></a>管理混合配置

通过更改混合配置向导中的设置，您可以修改现有混合配置。方案包括禁用集中式传输或禁用安全邮件传输。
  
若要详细了解如何管理混合部署配置，请参阅[管理混合部署](https://go.microsoft.com/fwlink/p/?LinkId=271044)。
  
### <a name="hybrid-deployment-requirements"></a>混合部署要求

若要详细了解混合部署要求，请参阅[混合部署先决条件](https://go.microsoft.com/fwlink/p/?LinkId=271759)。
  
> [!IMPORTANT]
> 在某些混合配置中，您必须为内部邮箱购买 Exchange Online Protection 许可证。 
  
## <a name="feature-availability"></a>功能可用性

若要查看在各个 Office 365 计划、独立选项和本地解决方案之间的功能可用性，请参阅 [Exchange Online 服务说明](exchange-online-service-description.md)。
  

