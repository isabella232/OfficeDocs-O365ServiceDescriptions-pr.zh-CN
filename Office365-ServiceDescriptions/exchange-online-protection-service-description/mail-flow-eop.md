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
ms.openlocfilehash: 5a581c8004bcdc001160a2499cd623c6eee772f2
ms.sourcegitcommit: 3d180fb603896239b30d9db6ba865843c29801b0
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/10/2019
ms.locfileid: "37442727"
---
# <a name="mail-floweop"></a><span data-ttu-id="6ff84-107">邮件流[EOP]</span><span class="sxs-lookup"><span data-stu-id="6ff84-107">Mail Flow[EOP]</span></span>

<span data-ttu-id="6ff84-108">对于大多数使用 Office 365 的组织，我们可以为其托管邮箱并处理邮件流。</span><span class="sxs-lookup"><span data-stu-id="6ff84-108">For most organizations that use Office 365, we host your mailboxes and take care of mail flow.</span></span> <span data-ttu-id="6ff84-109">这是最简单的配置，意味着 Office 365 管理所有邮箱和筛选。</span><span class="sxs-lookup"><span data-stu-id="6ff84-109">It's the simplest configuration and means that Office 365 manages all mailboxes and filtering.</span></span> <span data-ttu-id="6ff84-110">但是，某些组织有需要将所有邮箱保留在本地的业务。</span><span class="sxs-lookup"><span data-stu-id="6ff84-110">However, some organizations have a business need to keep all their mailboxes on premises.</span></span> <span data-ttu-id="6ff84-111">借助 Exchange Online Protection (EOP)，可以实现上述功能，并在云中提供防病毒和反垃圾邮件处理。</span><span class="sxs-lookup"><span data-stu-id="6ff84-111">Exchange Online Protection (EOP) enables you to do that and provides antivirus and anti-spam mail processing in the cloud.</span></span> <span data-ttu-id="6ff84-112">有关详细信息以及购买 EOP 的信息，请转到 [Exchange Online Protection](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection)。</span><span class="sxs-lookup"><span data-stu-id="6ff84-112">For more information and to purchase EOP, go to [Exchange Online Protection](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection).</span></span>
  
<span data-ttu-id="6ff84-p103">正在查找关于域管理或基于目录的边缘阻止 (DBEB) 的信息？请参阅[收件人、域和公司管理](recipient-domain-and-company-management.md)。有关所有 EOP 功能的详细信息，请参阅[Exchange Online Protection 服务说明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="6ff84-p103">Looking for information about domain management or Directory Based Edge Blocking (DBEB)? See [Recipient, Domain, and Company Management](recipient-domain-and-company-management.md). To learn more about all EOP features, see the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="routing-email-between-office-365-and-your-own-email-servers"></a><span data-ttu-id="6ff84-116">在 Office 365 和自己的电子邮件服务器之间路由电子邮件</span><span class="sxs-lookup"><span data-stu-id="6ff84-116">Routing email between Office 365 and your own email servers</span></span>

<span data-ttu-id="6ff84-p104">可以配置连接器以启用 Office 365（包括 Exchange Online 或 EOP）与基于 SMTP 的电子邮件服务器（如 Exchange）之间的邮件流。有关详细信息，请参阅[Do I need a connector](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)？和[Set up connectors to route mail between Office 365 and your own email servers](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail)。</span><span class="sxs-lookup"><span data-stu-id="6ff84-p104">You can configure a connector to enable mail flow between Office 365 (including Exchange Online or EOP) and an SMTP-based email server such as Exchange. For details about this, see [Do I need a connector](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)? And [Set up connectors to route mail between Office 365 and your own email servers](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail).</span></span>
  
## <a name="secure-messaging-with-a-trusted-partner"></a><span data-ttu-id="6ff84-120">与受信任合作伙伴的安全邮件</span><span class="sxs-lookup"><span data-stu-id="6ff84-120">Secure messaging with a trusted partner</span></span>

<span data-ttu-id="6ff84-121">作为 EOP 客户，你可以使用 Office 365 连接器设置与受信任合作伙伴的安全邮件流。</span><span class="sxs-lookup"><span data-stu-id="6ff84-121">As an EOP customer, you can set up secure mail flow with a trusted partner by using Office 365 connectors.</span></span> <span data-ttu-id="6ff84-122">Office 365 支持通过传输层安全性 (TLS) 的安全通信，并且你可以创建一个连接器，强制通过 TLS 进行加密。</span><span class="sxs-lookup"><span data-stu-id="6ff84-122">Office 365 supports secure communication through Transport Layer Security (TLS), and you can create a connector to enforce encryption via TLS.</span></span> <span data-ttu-id="6ff84-123">[TLS](https://docs.microsoft.com/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections)是一种加密协议，提供通过 internet 进行通信的安全性。</span><span class="sxs-lookup"><span data-stu-id="6ff84-123">[TLS](https://docs.microsoft.com/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections) is a cryptographic protocol that provides security for communications over the internet.</span></span> <span data-ttu-id="6ff84-124">通过使用连接器，可以使用自签名证书或经证书颁发机构 (CA) 验证的证书配置强制的入站和出站 TLS。</span><span class="sxs-lookup"><span data-stu-id="6ff84-124">By using connectors, you can configure both forced incoming and outgoing TLS using self-signed or certification authority (CA)-validated certificates.</span></span> <span data-ttu-id="6ff84-125">还可以应用其他安全限制，如指定合作伙伴组织发送邮件时使用的域名或 IP 地址范围。</span><span class="sxs-lookup"><span data-stu-id="6ff84-125">You can also apply other security restrictions, such as specifying domain names or IP address ranges from which your partner organization sends mail.</span></span> 
  
<span data-ttu-id="6ff84-126">有关详细信息，请参阅[将连接器设置为确保与合作伙伴组织之间实现安全的邮件流](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner)。</span><span class="sxs-lookup"><span data-stu-id="6ff84-126">For more information, see [Set up connectors for secure mail flow with a partner organization](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).</span></span>
  
## <a name="safe-listing-a-partners-ip-address"></a><span data-ttu-id="6ff84-127">合作伙伴 IP 地址安全列表</span><span class="sxs-lookup"><span data-stu-id="6ff84-127">Safe listing a partner's IP address</span></span>

<span data-ttu-id="6ff84-p106">可以将受信任伙伴的 IP 地址添加到安全列表中，以确保他们发送给你的邮件不经过垃圾邮件筛选。为此，可以使用连接筛选器的 IP 允许列表。有关详细信息，请参阅[配置连接筛选器策略](https://go.microsoft.com/fwlink/p/?LinkID=287108)。</span><span class="sxs-lookup"><span data-stu-id="6ff84-p106">You can add a trusted partner's IP address to a safe list to ensure that messages they send to you are not subject to spam filtering. To do this, you can use the connection filter's IP Allow list. For more information, see [Configure the connection filter policy](https://go.microsoft.com/fwlink/p/?LinkID=287108).</span></span>
  
## <a name="conditional-mail-routing"></a><span data-ttu-id="6ff84-131">有条件的邮件路由</span><span class="sxs-lookup"><span data-stu-id="6ff84-131">Conditional mail routing</span></span>

<span data-ttu-id="6ff84-p107">可以使用传输规则配置连接器，以便根据条件将邮件路由到特定的站点。有关详细信息，请参阅[Scenario: Conditional email routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing)。</span><span class="sxs-lookup"><span data-stu-id="6ff84-p107">You can configure a connector with a Transport rule that routes mail to a specific site, based on conditions. For more information, see [Scenario: Conditional email routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).</span></span>
  
## <a name="hybrid-mail-routing"></a><span data-ttu-id="6ff84-134">混合邮件路由</span><span class="sxs-lookup"><span data-stu-id="6ff84-134">Hybrid mail routing</span></span>

<span data-ttu-id="6ff84-p108">混合表示将一部分邮箱托管于本地上，而另一部分托管于云 (Exchange Online) 中。可以从独立（本地）部署移动到混合部署。</span><span class="sxs-lookup"><span data-stu-id="6ff84-p108">Hybrid means that you host a portion of your mailboxes on premises, and a portion in the cloud (Exchange Online). You can move from a standalone (on-premises) deployment to a hybrid deployment.</span></span>
  
<span data-ttu-id="6ff84-p109">如果拥有混合部署，则可以使用 EOP 保护云和本地邮箱。使用 EOP 进行保护时，本地邮箱需要独立许可证。有关混合部署中的邮件路由的详细信息，请参阅 [Exchange 混合部署中的传输路由](https://go.microsoft.com/fwlink/p/?LinkId=271757)。</span><span class="sxs-lookup"><span data-stu-id="6ff84-p109">If you have a hybrid deployment, you can protect your cloud and on-premises mailboxes with EOP. Standalone licenses are required for on-premises mailboxes, when they are protected by EOP. For more information about mail routing in a hybrid deployment, see [Transport routing in Exchange hybrid deployments](https://go.microsoft.com/fwlink/p/?LinkId=271757).</span></span>
  
<span data-ttu-id="6ff84-140">[Microsoft Exchange Server 部署助理](https://go.microsoft.com/fwlink/p/?LinkId=287036)还提供了有关混合部署预配和混合邮件传输的详细指导。</span><span class="sxs-lookup"><span data-stu-id="6ff84-140">The [Microsoft Exchange Server Deployment Assistant](https://go.microsoft.com/fwlink/p/?LinkId=287036) also provides detailed hybrid deployment provisioning and hybrid message transport guidance.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="6ff84-141">功能可用性</span><span class="sxs-lookup"><span data-stu-id="6ff84-141">Feature Availability</span></span>

<span data-ttu-id="6ff84-142">若要查看在各个 Office 365 计划、独立选项和内部部署解决方案之间的功能可用性，请参阅 [Exchange Online Protection 服务说明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="6ff84-142">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
