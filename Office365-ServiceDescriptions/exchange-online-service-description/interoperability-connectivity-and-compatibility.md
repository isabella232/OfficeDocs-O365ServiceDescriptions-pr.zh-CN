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
ms.openlocfilehash: 21df7d4747ae0b92f21a9da56c0d4bc9ff96ccaf
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173317"
---
# <a name="interoperability-connectivity-and-compatibility"></a><span data-ttu-id="90a52-102">互操作性、连接性和兼容性</span><span class="sxs-lookup"><span data-stu-id="90a52-102">Interoperability, connectivity, and compatibility</span></span>

## <a name="interoperability-with-other-microsoft-products"></a><span data-ttu-id="90a52-103">与其他 Microsoft 产品的互操作性</span><span class="sxs-lookup"><span data-stu-id="90a52-103">Interoperability with other Microsoft products</span></span>

### <a name="skype-for-business-online"></a><span data-ttu-id="90a52-104">Skype for Business Online</span><span class="sxs-lookup"><span data-stu-id="90a52-104">Skype for Business Online</span></span>

<span data-ttu-id="90a52-105">对于已经本地部署了 Microsoft Lync Server 2010、Lync Server 2013 或 Microsoft Office Communications Server 2007 R2 的客户来说，通过使用 Exchange Web Services 访问"外出"邮件和日历数据，Microsoft Office Communicator 可以连接到 Microsoft Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="90a52-105">For customers who have deployed Microsoft Lync Server 2010, Lync Server 2013 or Microsoft Office Communications Server 2007 R2 on-premises, Microsoft Office Communicator can connect to Microsoft Exchange Online by using Exchange Web Services to access out-of-office messages and calendar data.</span></span>
  
<span data-ttu-id="90a52-106">本地 Lync Server 2010 和 Lync Server 2013 可以使用两种其他方式与 Exchange Online 进行互操作：</span><span class="sxs-lookup"><span data-stu-id="90a52-106">On-premises Lync Server 2010 and Lync Server 2013 can interoperate with Exchange Online in two additional ways:</span></span>
  
- <span data-ttu-id="90a52-107">Outlook 网页中的 IM 和状态互操作性</span><span class="sxs-lookup"><span data-stu-id="90a52-107">IM and presence interoperability in Outlook on the web</span></span>
    
- <span data-ttu-id="90a52-108">语音邮件互操作性</span><span class="sxs-lookup"><span data-stu-id="90a52-108">Voice mail interoperability</span></span>
    
<span data-ttu-id="90a52-p101">若要详细了解如何使用 Exchange Online 配置 Skype for Business Server 2015，请参阅[配置本地 Skype for Business Server 2015 与 Exchange Online 之间的集成](/skypeforbusiness/deploy/integrate-with-exchange-server/outlook-web-app)。有关混合配置，请参阅[支持的 Skype for Business Server 2015 混合配置](/skypeforbusiness/skype-for-business-hybrid-solutions/integration-with-exchange-and-sharepoint)。</span><span class="sxs-lookup"><span data-stu-id="90a52-p101">For more information about how to configure Skype for Business Server 2015 with Exchange Online, see [Configuring On-premises Skype for Business Server 2015 Integration with Exchange Online](/skypeforbusiness/deploy/integrate-with-exchange-server/outlook-web-app). For hybrid configurations, see [Supported Skype for Business Server 2015 hybrid configurations](/skypeforbusiness/skype-for-business-hybrid-solutions/integration-with-exchange-and-sharepoint).</span></span>
  
### <a name="microsoft-sharepoint"></a><span data-ttu-id="90a52-111">Microsoft SharePoint</span><span class="sxs-lookup"><span data-stu-id="90a52-111">Microsoft SharePoint</span></span>

<span data-ttu-id="90a52-112">对于将 Microsoft SharePoint Server 或 SharePoint Online 作为订阅计划的一部分部署的客户，SharePoint 可以连接到 Exchange Online，获得集成服务。</span><span class="sxs-lookup"><span data-stu-id="90a52-112">For customers who have deployed Microsoft SharePoint Server or SharePoint Online as part of an subscription plan, SharePoint can connect to Exchange Online for integrated services.</span></span>
  
<span data-ttu-id="90a52-113">若要详细了解如何将 SharePoint 连接到 Exchange Online，请参阅 [Use SharePoint Online on a custom domain together with other services](https://go.microsoft.com/fwlink/?LinkId=271805)（在自定义域上结合使用 SharePoint Online 与其他服务）。</span><span class="sxs-lookup"><span data-stu-id="90a52-113">For more information about connecting SharePoint to Exchange Online, see [Use SharePoint Online on a custom domain together with other services](https://go.microsoft.com/fwlink/?LinkId=271805).</span></span>
  
## <a name="features-for-external-connectivity"></a><span data-ttu-id="90a52-114">用于外部连接性的功能</span><span class="sxs-lookup"><span data-stu-id="90a52-114">Features for external connectivity</span></span>

<span data-ttu-id="90a52-115">Exchange Online 提供以下功能以与外部应用程序和设备连接：</span><span class="sxs-lookup"><span data-stu-id="90a52-115">Exchange Online offers the following features for connecting with external applications and devices:</span></span>
  
- <span data-ttu-id="90a52-p102">**通过 MAPI over HTTP、SMTP、POP3、IMAP4 或 Exchange Web Services 等消息协议** 通过使用 MAPI over HTTP、SMTP、POP3 和 IMAP4 等消息协议，本地运行的、在 Azure 或其他托管服务中运行的外部应用程序可以访问使用 Exchange Online 存储的数据。建议为应用程序开发使用 Exchange Web Services 或 Exchange Web Services 托管 API。</span><span class="sxs-lookup"><span data-stu-id="90a52-p102">**Through messaging protocols such as MAPI over HTTP, SMTP, POP3, IMAP4, or Exchange Web Services** External applications that are running on-premises, in Azure, or in other hosted services can access data stored with Exchange Online by using messaging protocols such as MAPI over HTTP, SMTP, POP3, and IMAPv4. Exchange Web Services or the Exchange Web Services Managed API is recommended for application development.</span></span> 
    
- <span data-ttu-id="90a52-118">**作为 SMTP 中继** Exchange Online 可以设置为 SMTP 送达服务，以中继来自传真网关、网络设备和自定义应用程序的电子邮件消息。</span><span class="sxs-lookup"><span data-stu-id="90a52-118">**As an SMTP relay** Exchange Online can be set up as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications.</span></span> 
    
### <a name="exchange-web-services"></a><span data-ttu-id="90a52-119">Exchange Web 服务</span><span class="sxs-lookup"><span data-stu-id="90a52-119">Exchange Web Services</span></span>

<span data-ttu-id="90a52-120">Exchange Web 服务 (EWS) 是 Exchange Server 和 Exchange Online 的首选开发 API。</span><span class="sxs-lookup"><span data-stu-id="90a52-120">Exchange Web Services (EWS) is the preferred development API for Exchange Server and Exchange Online.</span></span> <span data-ttu-id="90a52-121">使用 EWS 或 EWS 托管 API，管理员可以访问使用 Exchange Online 存储，来自内部部署、在 Azure 或其他托管服务运行应用程序的数据。</span><span class="sxs-lookup"><span data-stu-id="90a52-121">Using EWS or the EWS Managed API, administrators can access data stored with Exchange Online from applications that are running on-premises, in Azure, or in other hosted services.</span></span> <span data-ttu-id="90a52-122">EWS 允许管理员执行专门的操作，如查询邮箱内容、发布日历事件、创建任务或基于电子邮件内容触发特定操作。</span><span class="sxs-lookup"><span data-stu-id="90a52-122">EWS lets administrators perform specialized actions, such as querying the contents of a mailbox, posting a calendar event, creating a task, or triggering a specific action based on the content of an email message.</span></span> <span data-ttu-id="90a52-123">通过授予对客户账户的应用程序权限，Exchange Online 可以启用 EWS 功能。</span><span class="sxs-lookup"><span data-stu-id="90a52-123">Exchange Online enables EWS functionality by granting application permissions to customer accounts.</span></span> <span data-ttu-id="90a52-124">这些权限允许客户应用程序访问应用程序邮箱并添加内容。</span><span class="sxs-lookup"><span data-stu-id="90a52-124">These permissions allow the customer application to access the application mailbox and add content.</span></span> <span data-ttu-id="90a52-125">Exchange Impersonation 是一种用于授予应用程序权限的方法。</span><span class="sxs-lookup"><span data-stu-id="90a52-125">Exchange Impersonation is one method used to grant application permissions.</span></span> <span data-ttu-id="90a52-126">有关如何将 Exchange Web Services 用于 Exchange Online 的详细信息，请参阅 Exchange Online 开发人员中心的技术文章。</span><span class="sxs-lookup"><span data-stu-id="90a52-126">For details about how to use Exchange Web Services with Exchange Online, refer to the technical articles at the Exchange Online Developer Center.</span></span>
  
### <a name="smtp-relay"></a><span data-ttu-id="90a52-127">SMTP 中继</span><span class="sxs-lookup"><span data-stu-id="90a52-127">SMTP relay</span></span>

<span data-ttu-id="90a52-p104">Exchange Online 可以作为 SMTP 送达服务设置，以中继来自传真网关、网络设备和定制应用程序的电子邮件消息。例如，如果业务线应用程序发送电子邮件报警给用户，它可配置以使用 Exchange Online 作为邮件送达系统。应用程序或服务必须使用经过许可的有效 Exchange Online 邮箱的用户名和密码进行身份验证，并使用传输层安全性 (TLS) 连接。</span><span class="sxs-lookup"><span data-stu-id="90a52-p104">Exchange Online can be used as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications. For example, if a line-of-business application sends email alerts to users, it can be configured to use Exchange Online as the mail delivery system. The application or service must authenticate with the username and password of a valid, licensed Exchange Online mailbox, and connect by using Transport Layer Security (TLS).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="90a52-131">功能可用性</span><span class="sxs-lookup"><span data-stu-id="90a52-131">Feature availability</span></span>

<span data-ttu-id="90a52-132">若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅 [Exchange Online 服务说明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="90a52-132">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online service description](exchange-online-service-description.md).</span></span>
