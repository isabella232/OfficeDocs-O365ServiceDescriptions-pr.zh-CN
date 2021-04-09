---
title: Exchange Online Protection 中的邮件流
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: 阅读本文，了解 Microsoft Exchange Online Protection (EOP) 中的邮件流。
ms.openlocfilehash: 0923f31ccb639271303654cbdccf4890b2a55062
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653134"
---
# <a name="mail-flow-in-exchange-online-protection"></a><span data-ttu-id="36158-103">Exchange Online Protection 中的邮件流</span><span class="sxs-lookup"><span data-stu-id="36158-103">Mail flow in Exchange Online Protection</span></span>

<span data-ttu-id="36158-104">对于大多数使用 Microsoft 的组织，我们将托管您的邮箱并处理邮件流。</span><span class="sxs-lookup"><span data-stu-id="36158-104">For most organizations that use Microsoft, we host your mailboxes and take care of mail flow.</span></span> <span data-ttu-id="36158-105">这是最简单的配置，意味着 Microsoft 管理所有邮箱和筛选。</span><span class="sxs-lookup"><span data-stu-id="36158-105">It's the simplest configuration and means that Microsoft manages all mailboxes and filtering.</span></span> <span data-ttu-id="36158-106">但是，某些组织有需要将所有邮箱保留在本地的业务。</span><span class="sxs-lookup"><span data-stu-id="36158-106">However, some organizations have a business need to keep all their mailboxes on premises.</span></span> <span data-ttu-id="36158-107">Exchange Online Protection (EOP) 允许您执行这一操作，并可以在云中提供防病毒和反垃圾邮件处理。</span><span class="sxs-lookup"><span data-stu-id="36158-107">Exchange Online Protection (EOP) lets you do that and provides antivirus and anti-spam mail processing in the cloud.</span></span> <span data-ttu-id="36158-108">有关详细信息以及购买 EOP 的信息，请转到 [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection)。</span><span class="sxs-lookup"><span data-stu-id="36158-108">For more information and to purchase EOP, go to [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).</span></span>
  
<span data-ttu-id="36158-109">正在查找关于域管理或基于目录的边缘阻止 (DBEB) 的信息？</span><span class="sxs-lookup"><span data-stu-id="36158-109">Looking for information about domain management or Directory Based Edge Blocking (DBEB)?</span></span> <span data-ttu-id="36158-110">请参阅 [收件人、域和公司管理](recipient-domain-and-company-management.md)。</span><span class="sxs-lookup"><span data-stu-id="36158-110">See [Recipient, domain, and company management](recipient-domain-and-company-management.md).</span></span> <span data-ttu-id="36158-111">若要详细了解所有 EOP 功能，请参阅 [Exchange Online Protection 服务说明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="36158-111">To learn more about all EOP features, see the [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="routing-email-between-microsoft-and-your-own-email-servers"></a><span data-ttu-id="36158-112">在 Microsoft 和自己的电子邮件服务器之间路由电子邮件</span><span class="sxs-lookup"><span data-stu-id="36158-112">Routing email between Microsoft and your own email servers</span></span>

<span data-ttu-id="36158-113">您可以配置连接器以启用 Microsoft (包括 Exchange Online 或 EOP) 与基于 SMTP 的电子邮件服务器（如 Exchange）之间的邮件流。</span><span class="sxs-lookup"><span data-stu-id="36158-113">You can configure a connector to enable mail flow between Microsoft (including Exchange Online or EOP) and an SMTP-based email server such as Exchange.</span></span> <span data-ttu-id="36158-114">有关详细信息，请参阅[Do I need a connector](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)？</span><span class="sxs-lookup"><span data-stu-id="36158-114">For details about this, see [Do I need a connector](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)?</span></span> <span data-ttu-id="36158-115">设置 [连接器以在 Microsoft 和您自己的电子邮件服务器之间路由邮件](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail)。</span><span class="sxs-lookup"><span data-stu-id="36158-115">And [Set up connectors to route mail between Microsoft and your own email servers](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail).</span></span>
  
## <a name="secure-messaging-with-a-trusted-partner"></a><span data-ttu-id="36158-116">与受信任合作伙伴的安全邮件</span><span class="sxs-lookup"><span data-stu-id="36158-116">Secure messaging with a trusted partner</span></span>

<span data-ttu-id="36158-117">作为 EOP 客户，您可以使用 Microsoft 连接器设置与受信任合作伙伴的安全邮件流。</span><span class="sxs-lookup"><span data-stu-id="36158-117">As an EOP customer, you can set up secure mail flow with a trusted partner by using Microsoft connectors.</span></span> <span data-ttu-id="36158-118">Microsoft 支持通过传输层安全性 (TLS) 安全通信，并且您可以创建连接器以通过 TLS 强制实施加密。</span><span class="sxs-lookup"><span data-stu-id="36158-118">Microsoft supports secure communication through Transport Layer Security (TLS), and you can create a connector to enforce encryption via TLS.</span></span> <span data-ttu-id="36158-119">[TLS](/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections) 是一种加密协议，它为通过 Internet 的通信提供安全性。</span><span class="sxs-lookup"><span data-stu-id="36158-119">[TLS](/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections) is a cryptographic protocol that provides security for communications over the internet.</span></span> <span data-ttu-id="36158-120">通过使用连接器，可以使用自签名证书或经证书颁发机构 (CA) 验证的证书配置强制的入站和出站 TLS。</span><span class="sxs-lookup"><span data-stu-id="36158-120">By using connectors, you can configure both forced incoming and outgoing TLS using self-signed or certification authority (CA)-validated certificates.</span></span> <span data-ttu-id="36158-121">还可以应用其他安全限制，如指定合作伙伴组织发送邮件时使用的域名或 IP 地址范围。</span><span class="sxs-lookup"><span data-stu-id="36158-121">You can also apply other security restrictions, such as specifying domain names or IP address ranges from which your partner organization sends mail.</span></span> 
  
<span data-ttu-id="36158-122">有关详细信息，请参阅[将连接器设置为确保与合作伙伴组织之间实现安全的邮件流](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner)。</span><span class="sxs-lookup"><span data-stu-id="36158-122">For more information, see [Set up connectors for secure mail flow with a partner organization](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).</span></span>
  
## <a name="safe-listing-a-partners-ip-address"></a><span data-ttu-id="36158-123">合作伙伴 IP 地址安全列表</span><span class="sxs-lookup"><span data-stu-id="36158-123">Safe listing a partner's IP address</span></span>

<span data-ttu-id="36158-p105">可以将受信任伙伴的 IP 地址添加到安全列表中，以确保他们发送给你的邮件不经过垃圾邮件筛选。为此，可以使用连接筛选器的 IP 允许列表。有关详细信息，请参阅[配置连接筛选器策略](/microsoft-365/security/office-365-security/configure-the-connection-filter-policy)。</span><span class="sxs-lookup"><span data-stu-id="36158-p105">You can add a trusted partner's IP address to a safe list to ensure that messages they send to you are not subject to spam filtering. To do this, you can use the connection filter's IP Allow list. For more information, see [Configure the connection filter policy](/microsoft-365/security/office-365-security/configure-the-connection-filter-policy).</span></span>
  
## <a name="conditional-mail-routing"></a><span data-ttu-id="36158-127">有条件的邮件路由</span><span class="sxs-lookup"><span data-stu-id="36158-127">Conditional mail routing</span></span>

<span data-ttu-id="36158-p106">可以使用传输规则配置连接器，以便根据条件将邮件路由到特定的站点。有关详细信息，请参阅[Scenario: Conditional email routing](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing)。</span><span class="sxs-lookup"><span data-stu-id="36158-p106">You can configure a connector with a Transport rule that routes mail to a specific site, based on conditions. For more information, see [Scenario: Conditional email routing](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).</span></span>
  
## <a name="hybrid-mail-routing"></a><span data-ttu-id="36158-130">混合邮件路由</span><span class="sxs-lookup"><span data-stu-id="36158-130">Hybrid mail routing</span></span>

<span data-ttu-id="36158-p107">混合表示将一部分邮箱托管于本地上，而另一部分托管于云 (Exchange Online) 中。可以从独立（本地）部署移动到混合部署。</span><span class="sxs-lookup"><span data-stu-id="36158-p107">Hybrid means that you host a portion of your mailboxes on premises, and a portion in the cloud (Exchange Online). You can move from a standalone (on-premises) deployment to a hybrid deployment.</span></span>
  
<span data-ttu-id="36158-p108">如果拥有混合部署，则可以使用 EOP 保护云和本地邮箱。使用 EOP 进行保护时，本地邮箱需要独立许可证。有关混合部署中的邮件路由的详细信息，请参阅 [Exchange 混合部署中的传输路由](/exchange/transport-routing)。</span><span class="sxs-lookup"><span data-stu-id="36158-p108">If you have a hybrid deployment, you can protect your cloud and on-premises mailboxes with EOP. Standalone licenses are required for on-premises mailboxes, when they are protected by EOP. For more information about mail routing in a hybrid deployment, see [Transport routing in Exchange hybrid deployments](/exchange/transport-routing).</span></span>
  
<span data-ttu-id="36158-136">[Microsoft Exchange Server 部署助理](/exchange/exchange-deployment-assistant)还提供了有关混合部署预配和混合邮件传输的详细指导。</span><span class="sxs-lookup"><span data-stu-id="36158-136">The [Microsoft Exchange Server Deployment Assistant](/exchange/exchange-deployment-assistant) also provides detailed hybrid deployment provisioning and hybrid message transport guidance.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="36158-137">功能可用性</span><span class="sxs-lookup"><span data-stu-id="36158-137">Feature availability</span></span>

<span data-ttu-id="36158-138">若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅 [Exchange Online Protection 服务说明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="36158-138">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>