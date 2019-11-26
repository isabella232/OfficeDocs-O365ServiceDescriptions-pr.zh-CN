---
title: 互操作性、连接性和兼容性
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-interoperability-connectivity-compatibility
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cdfe686d-a059-4f4d-bb8d-9c2c0ebfa423
ms.openlocfilehash: 2da88139da1d779c5fb72d3b8fe72a077c1f9e16
ms.sourcegitcommit: 2b9f68f7731dfd6f9d3f33e31e6303e81985ebb2
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/26/2019
ms.locfileid: "39262655"
---
# <a name="interoperability-connectivity-and-compatibility"></a>互操作性、连接性和兼容性

## <a name="interoperability-with-other-microsoft-products"></a>与其他 Microsoft 产品的互操作性

### <a name="skype-for-business-online"></a>Skype for Business Online

对于已经本地部署了 Microsoft Lync Server 2010、Lync Server 2013 或 Microsoft Office Communications Server 2007 R2 的客户来说，通过使用 Exchange Web Services 访问"外出"邮件和日历数据，Microsoft Office Communicator 可以连接到 Microsoft Exchange Online。
  
本地 Lync Server 2010 和 Lync Server 2013 可以使用两种其他方式与 Exchange Online 进行互操作：
  
- Outlook 网页网站中的 IM 和状态互操作性
    
- 语音邮件互操作性
    
若要详细了解如何使用 Exchange Online 配置 Skype for Business Server 2015，请参阅[配置本地 Skype for Business Server 2015 与 Exchange Online 之间的集成](https://go.microsoft.com/fwlink/p/?LinkId=271804)。有关混合配置，请参阅[支持的 Skype for Business Server 2015 混合配置](https://go.microsoft.com/fwlink/?LinkID=513084)。
  
### <a name="microsoft-sharepoint"></a>Microsoft SharePoint

对于已经部署 Microsoft SharePoint Server 或 SharePoint Online 作为 Office 365 订阅计划一部分的客户来说，SharePoint 可以作为集成服务连接到 Exchange Online。
  
若要详细了解如何将 SharePoint 连接到 Exchange Online，请参阅 [Use SharePoint Online on a custom domain together with other services](https://go.microsoft.com/fwlink/?LinkId=271805)（在自定义域上结合使用 SharePoint Online 与其他服务）。
  
## <a name="features-for-external-connectivity"></a>用于外部连接性的功能

Exchange Online 提供以下功能以与外部应用程序和设备连接：
  
- **通过 MAPI over HTTP、SMTP、POP3、IMAP4 或 Exchange Web Services 等消息协议** 通过使用 MAPI over HTTP、SMTP、POP3 和 IMAP4 等消息协议，本地运行的、在 Azure 或其他托管服务中运行的外部应用程序可以访问使用 Exchange Online 存储的数据。建议为应用程序开发使用 Exchange Web Services 或 Exchange Web Services 托管 API。 
    
- **作为 SMTP 中继** Exchange Online 可以设置为 SMTP 送达服务，以中继来自传真网关、网络设备和自定义应用程序的电子邮件消息。 
    
### <a name="exchange-web-services"></a>Exchange Web 服务

Exchange Web 服务 (EWS) 是 Exchange Server 和 Exchange Online 的首选开发 API。 使用 EWS 或 EWS 托管 API，管理员可以访问使用 Exchange Online 存储，来自内部部署、在 Azure 或其他托管服务运行应用程序的数据。 EWS 使管理员可以执行专门的操作，例如查询邮箱内容、发布日历事件、创建任务或根据电子邮件的内容触发特定操作。 通过授予对客户账户的应用程序权限，Exchange Online 可以启用 EWS 功能。 这些权限允许客户应用程序访问应用程序邮箱并添加内容。 Exchange Impersonation 是一种用于授予应用程序权限的方法。 有关如何将 Exchange Web Services 用于 Exchange Online 的详细信息，请参阅 Exchange Online 开发人员中心的技术文章。
  
### <a name="smtp-relay"></a>SMTP 中继

Exchange Online 可以作为 SMTP 送达服务设置，以中继来自传真网关、网络设备和定制应用程序的电子邮件消息。例如，如果业务线应用程序发送电子邮件报警给用户，它可配置以使用 Exchange Online 作为邮件送达系统。应用程序或服务必须使用经过许可的有效 Exchange Online 邮箱的用户名和密码进行身份验证，并使用传输层安全性 (TLS) 连接。
  
## <a name="feature-availability"></a>功能可用性

若要查看跨 Office 365 计划、独立选项和本地解决方案的功能可用性，请参阅[Exchange Online 服务说明](exchange-online-service-description.md)。
  

