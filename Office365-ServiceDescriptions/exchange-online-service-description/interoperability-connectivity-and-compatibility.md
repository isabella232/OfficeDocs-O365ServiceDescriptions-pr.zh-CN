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
# <a name="interoperability-connectivity-and-compatibility"></a><span data-ttu-id="9815a-102">互操作性、连接性和兼容性</span><span class="sxs-lookup"><span data-stu-id="9815a-102">Interoperability, connectivity, and compatibility</span></span>

## <a name="interoperability-with-other-microsoft-products"></a><span data-ttu-id="9815a-103">与其他 Microsoft 产品的互操作性</span><span class="sxs-lookup"><span data-stu-id="9815a-103">Interoperability with other Microsoft products</span></span>

### <a name="skype-for-business-online"></a><span data-ttu-id="9815a-104">Skype for Business Online</span><span class="sxs-lookup"><span data-stu-id="9815a-104">Skype for Business Online</span></span>

<span data-ttu-id="9815a-105">对于已经本地部署了 Microsoft Lync Server 2010、Lync Server 2013 或 Microsoft Office Communications Server 2007 R2 的客户来说，通过使用 Exchange Web Services 访问"外出"邮件和日历数据，Microsoft Office Communicator 可以连接到 Microsoft Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="9815a-105">For customers who have deployed Microsoft Lync Server 2010, Lync Server 2013 or Microsoft Office Communications Server 2007 R2 on-premises, Microsoft Office Communicator can connect to Microsoft Exchange Online by using Exchange Web Services to access out-of-office messages and calendar data.</span></span>
  
<span data-ttu-id="9815a-106">本地 Lync Server 2010 和 Lync Server 2013 可以使用两种其他方式与 Exchange Online 进行互操作：</span><span class="sxs-lookup"><span data-stu-id="9815a-106">On-premises Lync Server 2010 and Lync Server 2013 can interoperate with Exchange Online in two additional ways:</span></span>
  
- <span data-ttu-id="9815a-107">Outlook 网页网站中的 IM 和状态互操作性</span><span class="sxs-lookup"><span data-stu-id="9815a-107">IM and presence interoperability in Outlook on the web</span></span>
    
- <span data-ttu-id="9815a-108">语音邮件互操作性</span><span class="sxs-lookup"><span data-stu-id="9815a-108">Voice mail interoperability</span></span>
    
<span data-ttu-id="9815a-109">For more information about how to configure Skype for Business Server 2015 with Exchange Online, see [Configuring On-premises Skype for Business Server 2015 Integration with Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804).</span><span class="sxs-lookup"><span data-stu-id="9815a-109">For more information about how to configure Skype for Business Server 2015 with Exchange Online, see [Configuring On-premises Skype for Business Server 2015 Integration with Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804).</span></span> <span data-ttu-id="9815a-110">For hybrid configurations, see [Supported Skype for Business Server 2015 hybrid configurations](https://go.microsoft.com/fwlink/?LinkID=513084).</span><span class="sxs-lookup"><span data-stu-id="9815a-110">For hybrid configurations, see [Supported Skype for Business Server 2015 hybrid configurations](https://go.microsoft.com/fwlink/?LinkID=513084).</span></span>
  
### <a name="microsoft-sharepoint"></a><span data-ttu-id="9815a-111">Microsoft SharePoint</span><span class="sxs-lookup"><span data-stu-id="9815a-111">Microsoft SharePoint</span></span>

<span data-ttu-id="9815a-112">对于已部署 Microsoft SharePoint Server 或 SharePoint Online 作为订阅计划一部分的客户，SharePoint 可以连接到 Exchange Online 以获取集成服务。</span><span class="sxs-lookup"><span data-stu-id="9815a-112">For customers who have deployed Microsoft SharePoint Server or SharePoint Online as part of an subscription plan, SharePoint can connect to Exchange Online for integrated services.</span></span>
  
<span data-ttu-id="9815a-113">若要详细了解如何将 SharePoint 连接到 Exchange Online，请参阅 [Use SharePoint Online on a custom domain together with other services](https://go.microsoft.com/fwlink/?LinkId=271805)（在自定义域上结合使用 SharePoint Online 与其他服务）。</span><span class="sxs-lookup"><span data-stu-id="9815a-113">For more information about connecting SharePoint to Exchange Online, see [Use SharePoint Online on a custom domain together with other services](https://go.microsoft.com/fwlink/?LinkId=271805).</span></span>
  
## <a name="features-for-external-connectivity"></a><span data-ttu-id="9815a-114">用于外部连接性的功能</span><span class="sxs-lookup"><span data-stu-id="9815a-114">Features for external connectivity</span></span>

<span data-ttu-id="9815a-115">Exchange Online 提供以下功能以与外部应用程序和设备连接：</span><span class="sxs-lookup"><span data-stu-id="9815a-115">Exchange Online offers the following features for connecting with external applications and devices:</span></span>
  
- <span data-ttu-id="9815a-116">**Through messaging protocols such as MAPI over HTTP, SMTP, POP3, IMAP4, or Exchange Web Services** External applications that are running on-premises, in Azure, or in other hosted services can access data stored with Exchange Online by using messaging protocols such as MAPI over HTTP, SMTP, POP3, and IMAPv4.</span><span class="sxs-lookup"><span data-stu-id="9815a-116">**Through messaging protocols such as MAPI over HTTP, SMTP, POP3, IMAP4, or Exchange Web Services** External applications that are running on-premises, in Azure, or in other hosted services can access data stored with Exchange Online by using messaging protocols such as MAPI over HTTP, SMTP, POP3, and IMAPv4.</span></span> <span data-ttu-id="9815a-117">Exchange Web Services or the Exchange Web Services Managed API is recommended for application development.</span><span class="sxs-lookup"><span data-stu-id="9815a-117">Exchange Web Services or the Exchange Web Services Managed API is recommended for application development.</span></span> 
    
- <span data-ttu-id="9815a-118">**作为 SMTP 中继** Exchange Online 可以设置为 SMTP 送达服务，以中继来自传真网关、网络设备和自定义应用程序的电子邮件消息。</span><span class="sxs-lookup"><span data-stu-id="9815a-118">**As an SMTP relay** Exchange Online can be set up as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications.</span></span> 
    
### <a name="exchange-web-services"></a><span data-ttu-id="9815a-119">Exchange Web 服务</span><span class="sxs-lookup"><span data-stu-id="9815a-119">Exchange Web Services</span></span>

<span data-ttu-id="9815a-120">Exchange Web 服务 (EWS) 是 Exchange Server 和 Exchange Online 的首选开发 API。</span><span class="sxs-lookup"><span data-stu-id="9815a-120">Exchange Web Services (EWS) is the preferred development API for Exchange Server and Exchange Online.</span></span> <span data-ttu-id="9815a-121">使用 EWS 或 EWS 托管 API，管理员可以访问使用 Exchange Online 存储，来自内部部署、在 Azure 或其他托管服务运行应用程序的数据。</span><span class="sxs-lookup"><span data-stu-id="9815a-121">Using EWS or the EWS Managed API, administrators can access data stored with Exchange Online from applications that are running on-premises, in Azure, or in other hosted services.</span></span> <span data-ttu-id="9815a-122">EWS 使管理员可以执行专门的操作，例如查询邮箱内容、发布日历事件、创建任务或根据电子邮件的内容触发特定操作。</span><span class="sxs-lookup"><span data-stu-id="9815a-122">EWS lets administrators perform specialized actions, such as querying the contents of a mailbox, posting a calendar event, creating a task, or triggering a specific action based on the content of an email message.</span></span> <span data-ttu-id="9815a-123">通过授予对客户账户的应用程序权限，Exchange Online 可以启用 EWS 功能。</span><span class="sxs-lookup"><span data-stu-id="9815a-123">Exchange Online enables EWS functionality by granting application permissions to customer accounts.</span></span> <span data-ttu-id="9815a-124">这些权限允许客户应用程序访问应用程序邮箱并添加内容。</span><span class="sxs-lookup"><span data-stu-id="9815a-124">These permissions allow the customer application to access the application mailbox and add content.</span></span> <span data-ttu-id="9815a-125">Exchange Impersonation 是一种用于授予应用程序权限的方法。</span><span class="sxs-lookup"><span data-stu-id="9815a-125">Exchange Impersonation is one method used to grant application permissions.</span></span> <span data-ttu-id="9815a-126">有关如何将 Exchange Web Services 用于 Exchange Online 的详细信息，请参阅 Exchange Online 开发人员中心的技术文章。</span><span class="sxs-lookup"><span data-stu-id="9815a-126">For details about how to use Exchange Web Services with Exchange Online, refer to the technical articles at the Exchange Online Developer Center.</span></span>
  
### <a name="smtp-relay"></a><span data-ttu-id="9815a-127">SMTP 中继</span><span class="sxs-lookup"><span data-stu-id="9815a-127">SMTP relay</span></span>

<span data-ttu-id="9815a-128">Exchange Online can be used as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications.</span><span class="sxs-lookup"><span data-stu-id="9815a-128">Exchange Online can be used as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications.</span></span> <span data-ttu-id="9815a-129">For example, if a line-of-business application sends email alerts to users, it can be configured to use Exchange Online as the mail delivery system.</span><span class="sxs-lookup"><span data-stu-id="9815a-129">For example, if a line-of-business application sends email alerts to users, it can be configured to use Exchange Online as the mail delivery system.</span></span> <span data-ttu-id="9815a-130">The application or service must authenticate with the username and password of a valid, licensed Exchange Online mailbox, and connect by using Transport Layer Security (TLS).</span><span class="sxs-lookup"><span data-stu-id="9815a-130">The application or service must authenticate with the username and password of a valid, licensed Exchange Online mailbox, and connect by using Transport Layer Security (TLS).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="9815a-131">功能可用性</span><span class="sxs-lookup"><span data-stu-id="9815a-131">Feature availability</span></span>

<span data-ttu-id="9815a-132">若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅[Exchange Online 服务说明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="9815a-132">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online service description](exchange-online-service-description.md).</span></span>
  

