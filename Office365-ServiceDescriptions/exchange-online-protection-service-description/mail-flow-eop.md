---
title: 邮件流 [EOP]
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: 对于大多数使用 Office 365 的组织，我们可以为其托管邮箱并处理邮件流。 这是最简单的配置，意味着 Microsoft 管理所有邮箱和筛选。 但是，某些组织有需要将所有邮箱保留在本地的业务。 Exchange Online Protection （EOP）允许你执行此操作，并在云中提供防病毒和反垃圾邮件处理。
ms.openlocfilehash: 751551ef6b3ae710646b2fb63960eee5983d6c47
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132816"
---
# <a name="mail-floweop"></a><span data-ttu-id="1411a-106">邮件流 [EOP]</span><span class="sxs-lookup"><span data-stu-id="1411a-106">Mail flow[EOP]</span></span>

<span data-ttu-id="1411a-107">对于大多数使用 Microsoft 的组织，我们会托管邮箱并处理邮件流。</span><span class="sxs-lookup"><span data-stu-id="1411a-107">For most organizations that use Microsoft, we host your mailboxes and take care of mail flow.</span></span> <span data-ttu-id="1411a-108">这是最简单的配置，意味着 Microsoft 管理所有邮箱和筛选。</span><span class="sxs-lookup"><span data-stu-id="1411a-108">It's the simplest configuration and means that Microsoft manages all mailboxes and filtering.</span></span> <span data-ttu-id="1411a-109">但是，某些组织有需要将所有邮箱保留在本地的业务。</span><span class="sxs-lookup"><span data-stu-id="1411a-109">However, some organizations have a business need to keep all their mailboxes on premises.</span></span> <span data-ttu-id="1411a-110">Exchange Online Protection （EOP）允许你执行此操作，并在云中提供防病毒和反垃圾邮件处理。</span><span class="sxs-lookup"><span data-stu-id="1411a-110">Exchange Online Protection (EOP) lets you to do that and provides antivirus and anti-spam mail processing in the cloud.</span></span> <span data-ttu-id="1411a-111">有关详细信息以及购买 EOP 的信息，请转到 [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection)。</span><span class="sxs-lookup"><span data-stu-id="1411a-111">For more information and to purchase EOP, go to [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).</span></span>
  
<span data-ttu-id="1411a-112">正在查找关于域管理或基于目录的边缘阻止 (DBEB) 的信息？</span><span class="sxs-lookup"><span data-stu-id="1411a-112">Looking for information about domain management or Directory Based Edge Blocking (DBEB)?</span></span> <span data-ttu-id="1411a-113">请参阅[收件人、域和公司管理](recipient-domain-and-company-management.md)。</span><span class="sxs-lookup"><span data-stu-id="1411a-113">See [Recipient, domain, and company management](recipient-domain-and-company-management.md).</span></span> <span data-ttu-id="1411a-114">若要了解有关所有 EOP 功能的详细信息，请参阅[Exchange Online Protection 服务说明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="1411a-114">To learn more about all EOP features, see the [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="routing-email-between-microsoft-and-your-own-email-servers"></a><span data-ttu-id="1411a-115">在 Microsoft 和您自己的电子邮件服务器之间路由电子邮件</span><span class="sxs-lookup"><span data-stu-id="1411a-115">Routing email between Microsoft and your own email servers</span></span>

<span data-ttu-id="1411a-116">您可以将连接器配置为在 Microsoft （包括 Exchange Online 或 EOP）和基于 SMTP 的电子邮件服务器（如 Exchange）之间启用邮件流。</span><span class="sxs-lookup"><span data-stu-id="1411a-116">You can configure a connector to enable mail flow between Microsoft (including Exchange Online or EOP) and an SMTP-based email server such as Exchange.</span></span> <span data-ttu-id="1411a-117">有关详细信息，请参阅[Do I need a connector](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)？</span><span class="sxs-lookup"><span data-stu-id="1411a-117">For details about this, see [Do I need a connector](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)?</span></span> <span data-ttu-id="1411a-118">并[将连接器设置为在 Microsoft 和您自己的电子邮件服务器之间路由邮件](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail)。</span><span class="sxs-lookup"><span data-stu-id="1411a-118">And [Set up connectors to route mail between Microsoft and your own email servers](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail).</span></span>
  
## <a name="secure-messaging-with-a-trusted-partner"></a><span data-ttu-id="1411a-119">与受信任合作伙伴的安全邮件</span><span class="sxs-lookup"><span data-stu-id="1411a-119">Secure messaging with a trusted partner</span></span>

<span data-ttu-id="1411a-120">作为 EOP 客户，您可以使用 Microsoft 连接器建立与受信任合作伙伴的安全邮件流。</span><span class="sxs-lookup"><span data-stu-id="1411a-120">As an EOP customer, you can set up secure mail flow with a trusted partner by using Microsoft connectors.</span></span> <span data-ttu-id="1411a-121">Microsoft 支持通过传输层安全性（TLS）进行安全通信，并且可以创建连接器以通过 TLS 强制执行加密。</span><span class="sxs-lookup"><span data-stu-id="1411a-121">Microsoft supports secure communication through Transport Layer Security (TLS), and you can create a connector to enforce encryption via TLS.</span></span> <span data-ttu-id="1411a-122">[TLS](https://docs.microsoft.com/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections)是一种加密协议，提供通过 internet 进行通信的安全性。</span><span class="sxs-lookup"><span data-stu-id="1411a-122">[TLS](https://docs.microsoft.com/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections) is a cryptographic protocol that provides security for communications over the internet.</span></span> <span data-ttu-id="1411a-123">通过使用连接器，可以使用自签名证书或经证书颁发机构 (CA) 验证的证书配置强制的入站和出站 TLS。</span><span class="sxs-lookup"><span data-stu-id="1411a-123">By using connectors, you can configure both forced incoming and outgoing TLS using self-signed or certification authority (CA)-validated certificates.</span></span> <span data-ttu-id="1411a-124">还可以应用其他安全限制，如指定合作伙伴组织发送邮件时使用的域名或 IP 地址范围。</span><span class="sxs-lookup"><span data-stu-id="1411a-124">You can also apply other security restrictions, such as specifying domain names or IP address ranges from which your partner organization sends mail.</span></span> 
  
<span data-ttu-id="1411a-125">有关详细信息，请参阅[将连接器设置为确保与合作伙伴组织之间实现安全的邮件流](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner)。</span><span class="sxs-lookup"><span data-stu-id="1411a-125">For more information, see [Set up connectors for secure mail flow with a partner organization](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).</span></span>
  
## <a name="safe-listing-a-partners-ip-address"></a><span data-ttu-id="1411a-126">合作伙伴 IP 地址安全列表</span><span class="sxs-lookup"><span data-stu-id="1411a-126">Safe listing a partner's IP address</span></span>

<span data-ttu-id="1411a-p106">可以将受信任伙伴的 IP 地址添加到安全列表中，以确保他们发送给你的邮件不经过垃圾邮件筛选。为此，可以使用连接筛选器的 IP 允许列表。有关详细信息，请参阅[配置连接筛选器策略](https://go.microsoft.com/fwlink/p/?LinkID=287108)。</span><span class="sxs-lookup"><span data-stu-id="1411a-p106">You can add a trusted partner's IP address to a safe list to ensure that messages they send to you are not subject to spam filtering. To do this, you can use the connection filter's IP Allow list. For more information, see [Configure the connection filter policy](https://go.microsoft.com/fwlink/p/?LinkID=287108).</span></span>
  
## <a name="conditional-mail-routing"></a><span data-ttu-id="1411a-130">有条件的邮件路由</span><span class="sxs-lookup"><span data-stu-id="1411a-130">Conditional mail routing</span></span>

<span data-ttu-id="1411a-p107">可以使用传输规则配置连接器，以便根据条件将邮件路由到特定的站点。有关详细信息，请参阅[Scenario: Conditional email routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing)。</span><span class="sxs-lookup"><span data-stu-id="1411a-p107">You can configure a connector with a Transport rule that routes mail to a specific site, based on conditions. For more information, see [Scenario: Conditional email routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).</span></span>
  
## <a name="hybrid-mail-routing"></a><span data-ttu-id="1411a-133">混合邮件路由</span><span class="sxs-lookup"><span data-stu-id="1411a-133">Hybrid mail routing</span></span>

<span data-ttu-id="1411a-p108">混合表示将一部分邮箱托管于本地上，而另一部分托管于云 (Exchange Online) 中。可以从独立（本地）部署移动到混合部署。</span><span class="sxs-lookup"><span data-stu-id="1411a-p108">Hybrid means that you host a portion of your mailboxes on premises, and a portion in the cloud (Exchange Online). You can move from a standalone (on-premises) deployment to a hybrid deployment.</span></span>
  
<span data-ttu-id="1411a-p109">如果拥有混合部署，则可以使用 EOP 保护云和本地邮箱。使用 EOP 进行保护时，本地邮箱需要独立许可证。有关混合部署中的邮件路由的详细信息，请参阅 [Exchange 混合部署中的传输路由](https://go.microsoft.com/fwlink/p/?LinkId=271757)。</span><span class="sxs-lookup"><span data-stu-id="1411a-p109">If you have a hybrid deployment, you can protect your cloud and on-premises mailboxes with EOP. Standalone licenses are required for on-premises mailboxes, when they are protected by EOP. For more information about mail routing in a hybrid deployment, see [Transport routing in Exchange hybrid deployments](https://go.microsoft.com/fwlink/p/?LinkId=271757).</span></span>
  
<span data-ttu-id="1411a-139">[Microsoft Exchange Server 部署助理](https://go.microsoft.com/fwlink/p/?LinkId=287036)还提供了有关混合部署预配和混合邮件传输的详细指导。</span><span class="sxs-lookup"><span data-stu-id="1411a-139">The [Microsoft Exchange Server Deployment Assistant](https://go.microsoft.com/fwlink/p/?LinkId=287036) also provides detailed hybrid deployment provisioning and hybrid message transport guidance.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="1411a-140">功能可用性</span><span class="sxs-lookup"><span data-stu-id="1411a-140">Feature availability</span></span>

<span data-ttu-id="1411a-141">若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅[Exchange Online Protection 服务说明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="1411a-141">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>
