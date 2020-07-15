---
title: 互操作性、连接性和兼容性
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-interoperability-connectivity-compatibility
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cdfe686d-a059-4f4d-bb8d-9c2c0ebfa423
ms.openlocfilehash: 5308770ff7fc6ab6c44f27293ff89ebbffa6e72f
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132746"
---
# <a name="interoperability-connectivity-and-compatibility"></a>互操作性、连接性和兼容性

## <a name="interoperability-with-other-microsoft-products"></a>与其他 Microsoft 产品的互操作性

### <a name="skype-for-business-online"></a>Skype for Business Online

对于已经本地部署了 Microsoft Lync Server 2010、Lync Server 2013 或 Microsoft Office Communications Server 2007 R2 的客户来说，通过使用 Exchange Web Services 访问"外出"邮件和日历数据，Microsoft Office Communicator 可以连接到 Microsoft Exchange Online。
  
本地 Lync Server 2010 和 Lync Server 2013 可以使用两种其他方式与 Exchange Online 进行互操作：
  
- Outlook 网页网站中的 IM 和状态互操作性
    
- 语音邮件互操作性
    
For more information about how to configure Skype for Business Server 2015 with Exchange Online, see [Configuring On-premises Skype for Business Server 2015 Integration with Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804). For hybrid configurations, see [Supported Skype for Business Server 2015 hybrid configurations](https://go.microsoft.com/fwlink/?LinkID=513084).
  
### <a name="microsoft-sharepoint"></a>Microsoft SharePoint

对于已部署 Microsoft SharePoint Server 或 SharePoint Online 作为订阅计划一部分的客户，SharePoint 可以连接到 Exchange Online 以获取集成服务。
  
若要详细了解如何将 SharePoint 连接到 Exchange Online，请参阅 [Use SharePoint Online on a custom domain together with other services](https://go.microsoft.com/fwlink/?LinkId=271805)（在自定义域上结合使用 SharePoint Online 与其他服务）。
  
## <a name="features-for-external-connectivity"></a>用于外部连接性的功能

Exchange Online 提供以下功能以与外部应用程序和设备连接：
  
- **Through messaging protocols such as MAPI over HTTP, SMTP, POP3, IMAP4, or Exchange Web Services** External applications that are running on-premises, in Azure, or in other hosted services can access data stored with Exchange Online by using messaging protocols such as MAPI over HTTP, SMTP, POP3, and IMAPv4. Exchange Web Services or the Exchange Web Services Managed API is recommended for application development. 
    
- **作为 SMTP 中继** Exchange Online 可以设置为 SMTP 送达服务，以中继来自传真网关、网络设备和自定义应用程序的电子邮件消息。 
    
### <a name="exchange-web-services"></a>Exchange Web 服务

Exchange Web 服务 (EWS) 是 Exchange Server 和 Exchange Online 的首选开发 API。 使用 EWS 或 EWS 托管 API，管理员可以访问使用 Exchange Online 存储，来自内部部署、在 Azure 或其他托管服务运行应用程序的数据。 EWS 使管理员可以执行专门的操作，例如查询邮箱内容、发布日历事件、创建任务或根据电子邮件的内容触发特定操作。 通过授予对客户账户的应用程序权限，Exchange Online 可以启用 EWS 功能。 这些权限允许客户应用程序访问应用程序邮箱并添加内容。 Exchange Impersonation 是一种用于授予应用程序权限的方法。 有关如何将 Exchange Web Services 用于 Exchange Online 的详细信息，请参阅 Exchange Online 开发人员中心的技术文章。
  
### <a name="smtp-relay"></a>SMTP 中继

Exchange Online can be used as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications. For example, if a line-of-business application sends email alerts to users, it can be configured to use Exchange Online as the mail delivery system. The application or service must authenticate with the username and password of a valid, licensed Exchange Online mailbox, and connect by using Transport Layer Security (TLS).
  
## <a name="feature-availability"></a>功能可用性

若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅[Exchange Online 服务说明](exchange-online-service-description.md)。
  

