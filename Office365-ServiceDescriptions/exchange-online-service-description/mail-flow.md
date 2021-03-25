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
description: 对于大多数组织，我们将托管您的邮箱并处理邮件流。 这是最简单的配置，意味着 Microsoft 管理所有邮箱和筛选。 但是，某些组织需要进行更复杂的邮件流设置来确保它们遵守特定的法规或业务需要。 你可以在这里找到这些选项的信息。
ms.openlocfilehash: cc00cd942f3b5b6ad5e919b981879ca44c48cec9
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173647"
---
# <a name="mail-flow"></a><span data-ttu-id="859c0-106">邮件流</span><span class="sxs-lookup"><span data-stu-id="859c0-106">Mail flow</span></span>

<span data-ttu-id="859c0-107">对于大多数组织，我们将托管您的邮箱并处理邮件流。</span><span class="sxs-lookup"><span data-stu-id="859c0-107">For most organizations, we host your mailboxes and take care of mail flow.</span></span> <span data-ttu-id="859c0-108">这是最简单的配置，意味着 Microsoft 管理所有邮箱和筛选。</span><span class="sxs-lookup"><span data-stu-id="859c0-108">It's the simplest configuration and means that Microsoft manages all mailboxes and filtering.</span></span> <span data-ttu-id="859c0-109">但是，某些组织需要进行更复杂的邮件流设置来确保它们遵守特定的法规或业务需要。</span><span class="sxs-lookup"><span data-stu-id="859c0-109">However, some organizations need more complex mail flow setups to make sure that they comply with specific regulatory or business needs.</span></span> <span data-ttu-id="859c0-110">你可以在这里找到这些选项的信息。</span><span class="sxs-lookup"><span data-stu-id="859c0-110">You can find out about those options here.</span></span> 
  
## <a name="custom-routing-of-outbound-email"></a><span data-ttu-id="859c0-111">出站电子邮件的自定义路由</span><span class="sxs-lookup"><span data-stu-id="859c0-111">Custom routing of outbound email</span></span>

<span data-ttu-id="859c0-112">Microsoft Exchange Online 可通过本地服务器或托管服务（有时称为"智能托管"）路由来自组织的邮件流。</span><span class="sxs-lookup"><span data-stu-id="859c0-112">Microsoft Exchange Online can route mail flowing from your organization through an on-premises server or a hosted service (sometimes called "smart hosting").</span></span> <span data-ttu-id="859c0-113">这使贵组织可以使用 DLP (设备) 数据丢失防护、执行传出电子邮件的自定义后处理，以及通过专用网络将电子邮件传送给业务合作伙伴。</span><span class="sxs-lookup"><span data-stu-id="859c0-113">This lets your organization to use data loss prevention (DLP) appliances, perform custom post-processing of outgoing email, and deliver email to business partners through private networks.</span></span> <span data-ttu-id="859c0-114">Exchange Online 还支持地址重写，其中，传出电子邮件将通过修改地址的本地网关路由。</span><span class="sxs-lookup"><span data-stu-id="859c0-114">Exchange Online also supports Address Rewrite, which routes outgoing email through an on-premises gateway that modifies the addresses.</span></span> <span data-ttu-id="859c0-115">此功能允许你隐藏子域、使来自多域组织的电子邮件显示为单个域，或使合作伙伴中继的电子邮件看起来就像从组织内部发送一样。</span><span class="sxs-lookup"><span data-stu-id="859c0-115">This feature lets you hide sub-domains, make email from a multi-domain organization appear as a single domain, or make partner-relayed email appear as if it were sent from inside your organization.</span></span> <span data-ttu-id="859c0-116">管理员在 Exchange 管理中心 (EAC) 内配置自定义的电子邮件路由。</span><span class="sxs-lookup"><span data-stu-id="859c0-116">Administrators configure custom email routing within the Exchange admin center (EAC).</span></span>
  
<span data-ttu-id="859c0-117">有关详细信息，请参阅设置连接器以在 Microsoft 和 [您自己的电子邮件服务器之间路由邮件](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail)。</span><span class="sxs-lookup"><span data-stu-id="859c0-117">For more information, see [Set up connectors to route mail between Microsoft and your own email servers](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="859c0-118">Exchange Online 可将邮件流传入和传出组织。</span><span class="sxs-lookup"><span data-stu-id="859c0-118">Exchange Online can deliver mail flowing into and out of your organization.</span></span> <span data-ttu-id="859c0-119">如果收件人域托管在 Exchange Online 中，DNS MX 记录指向 Exchange Online Protection，则从租户到收件人的邮件流不会通过 Internet 传输。</span><span class="sxs-lookup"><span data-stu-id="859c0-119">If your recipient domain is hosted in Exchange Online with DNS MX records pointing to Exchange Online Protection, mail flow from your tenant to the recipient will not travel over the internet.</span></span>
  
## <a name="secure-messaging-with-a-trusted-partner"></a><span data-ttu-id="859c0-120">与受信任合作伙伴的安全邮件</span><span class="sxs-lookup"><span data-stu-id="859c0-120">Secure messaging with a trusted partner</span></span>

<span data-ttu-id="859c0-121">作为 Exchange Online 客户，您可以使用 Microsoft 连接器设置与受信任合作伙伴的安全邮件流。</span><span class="sxs-lookup"><span data-stu-id="859c0-121">As an Exchange Online customer, you can set up secure mail flow with a trusted partner by using Microsoft connectors.</span></span> <span data-ttu-id="859c0-122">Microsoft 支持通过传输层安全性 (TLS) 安全通信，并且您可以创建连接器以通过 TLS 强制实施加密。</span><span class="sxs-lookup"><span data-stu-id="859c0-122">Microsoft supports secure communication through Transport Layer Security (TLS), and you can create a connector to enforce encryption via TLS.</span></span> <span data-ttu-id="859c0-123">[TLS](/office365/securitycompliance/exchange-online-uses-tls-to-secure-email-connections) 是一种加密协议，它为通过 Internet 的通信提供安全性。</span><span class="sxs-lookup"><span data-stu-id="859c0-123">[TLS](/office365/securitycompliance/exchange-online-uses-tls-to-secure-email-connections) is a cryptographic protocol that provides security for communications over the internet.</span></span> <span data-ttu-id="859c0-124">通过使用连接器，可以使用自签名证书或经证书颁发机构 (CA) 验证的证书配置强制的入站和出站 TLS。</span><span class="sxs-lookup"><span data-stu-id="859c0-124">By using connectors, you can configure both forced incoming and outgoing TLS using self-signed or certification authority (CA)-validated certificates.</span></span> <span data-ttu-id="859c0-125">还可以应用其他安全限制，如指定合作伙伴组织发送邮件时使用的域名或 IP 地址范围。</span><span class="sxs-lookup"><span data-stu-id="859c0-125">You can also apply other security restrictions, such as specifying domain names or IP address ranges from which your partner organization sends mail.</span></span> 
  
<span data-ttu-id="859c0-126">有关详细信息，请参阅[Set up connectors for secure mail flow with a partner organization](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner)。</span><span class="sxs-lookup"><span data-stu-id="859c0-126">For more information, see [Set up connectors for secure mail flow with a partner organization](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="859c0-127">可能需要经 CA 验证的证书。</span><span class="sxs-lookup"><span data-stu-id="859c0-127">A CA-validated certificate may be required.</span></span> 
  
## <a name="conditional-mail-routing"></a><span data-ttu-id="859c0-128">有条件的邮件路由</span><span class="sxs-lookup"><span data-stu-id="859c0-128">Conditional mail routing</span></span>

<span data-ttu-id="859c0-p106">你可以使用连接器和传输规则将邮件直接传递到特定站点。通过基于条件的路由，你可以基于特定条件选择连接器。</span><span class="sxs-lookup"><span data-stu-id="859c0-p106">You can direct mail to specific sites by using connectors and transport rules. With criteria-based routing, you can choose a connector based on specific conditions.</span></span>
  
<span data-ttu-id="859c0-131">有关详细信息，请参阅[Scenario: Conditional mail routing](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing)。</span><span class="sxs-lookup"><span data-stu-id="859c0-131">For more information, see [Scenario: Conditional mail routing](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).</span></span>
  
## <a name="incoming-mail-safe-list"></a><span data-ttu-id="859c0-132">传入邮件安全列表</span><span class="sxs-lookup"><span data-stu-id="859c0-132">Incoming mail safe list</span></span>

<span data-ttu-id="859c0-p107">你可以将受信任的合作伙伴的 IP 地址添加到安全列表中，以确保合作伙伴发送给你的邮件不经过反垃圾邮件筛选。为此，你可以使用连接筛选器的 IP 允许列表。</span><span class="sxs-lookup"><span data-stu-id="859c0-p107">You can add a trusted partner's IP address to a safe list to ensure that messages the partner sends to you are not subject to anti-spam filtering. To do this, you can use the connection filter's IP Allow list.</span></span>
  
<span data-ttu-id="859c0-135">有关详细信息，请参阅[Configure the connection filter policy](/office365/SecurityCompliance/configure-the-connection-filter-policy)。</span><span class="sxs-lookup"><span data-stu-id="859c0-135">For more information, see [Configure the connection filter policy](/office365/SecurityCompliance/configure-the-connection-filter-policy).</span></span>
  
## <a name="hybrid-email-routing"></a><span data-ttu-id="859c0-136">混合电子邮件路由</span><span class="sxs-lookup"><span data-stu-id="859c0-136">Hybrid email routing</span></span>

<span data-ttu-id="859c0-p108">混合部署使组织可以将随其现有本地 Microsoft Exchange 组织提供的功能丰富的体验和管理控制扩展到云。通过混合传输，在任一组织中的收件人之间发送的邮件会经过身份验证、加密并使用传输层安全性 (TLS) 传输，并且向 Exchange 组件（如传输规则、日记和反垃圾邮件策略）显示为"内部"。通过使用 Exchange Server 中的混合配置向导配置混合传输。</span><span class="sxs-lookup"><span data-stu-id="859c0-p108">A hybrid deployment gives organizations the ability to extend the feature-rich experience and administrative control they have with their existing on-premises Microsoft Exchange organization to the cloud. With hybrid transport, messages sent between recipients in either organization are authenticated, encrypted, and transferred using Transport Layer Security (TLS), and appear as "internal" to Exchange components such as transport rules, journaling, and anti-spam policies. You configure hybrid transport by using the Hybrid Configuration Wizard in Exchange Server.</span></span>
  
<span data-ttu-id="859c0-140">若要详细了解混合部署中的邮件路由，请参阅 [Exchange 混合部署中的传输路由](/exchange/transport-routing)。</span><span class="sxs-lookup"><span data-stu-id="859c0-140">For more information about mail routing in a hybrid deployment, see [Transport routing in Exchange hybrid deployments](/exchange/transport-routing).</span></span>
  
<span data-ttu-id="859c0-141">[Microsoft Exchange Server 部署助理](/exchange/exchange-deployment-assistant)还提供了有关混合部署预配和混合邮件传输的详细指导。</span><span class="sxs-lookup"><span data-stu-id="859c0-141">The [Microsoft Exchange Server Deployment Assistant](/exchange/exchange-deployment-assistant) also provides detailed hybrid deployment provisioning and hybrid message transport guidance.</span></span> 
  
### <a name="shared-address-space-with-on-premises-routing-control-mx-points-to-on-premises"></a><span data-ttu-id="859c0-142">含内部路由控制的共享地址空间（MX 指向内部）</span><span class="sxs-lookup"><span data-stu-id="859c0-142">Shared Address Space with On-Premises Routing Control (MX Points to On-Premises)</span></span>

<span data-ttu-id="859c0-143">具有本地路由控制共享地址空间 (MX 指向本地) 是一种混合部署邮件路由方案，其中邮箱部分托管在 Exchange Online 中，部分托管在本地，传入和传出 Internet 邮件流通过内部部署 Exchange 组织路由。</span><span class="sxs-lookup"><span data-stu-id="859c0-143">Shared Address Space with On-Premises Routing Control (MX Points to On-Premises) is a hybrid deployment mail-routing scenario in which your mailboxes are hosted partially in Exchange Online and partially on-premises, and incoming and outgoing internet mail flow is routed through the on-premises Exchange organization.</span></span> <span data-ttu-id="859c0-144">此方案也称为集中邮件传输。</span><span class="sxs-lookup"><span data-stu-id="859c0-144">This scenario is also called centralized mail transport.</span></span> <span data-ttu-id="859c0-145">在此方案中，使用 EOP 预配 Exchange Online，传入 Internet 邮件将路由到内部部署邮件服务器，然后再路由到 EOP，最后路由到 Exchange Online 中托管的邮箱。</span><span class="sxs-lookup"><span data-stu-id="859c0-145">In this scenario, Exchange Online is provisioned with EOP and incoming internet mail is routed to your on-premises mail server before being routed to EOP and finally to mailboxes hosted in Exchange Online.</span></span> <span data-ttu-id="859c0-146">此外，来自 Exchange Online 邮箱的传出邮件通过内部部署 Exchange 组织路由发送给外部收件人的邮件。</span><span class="sxs-lookup"><span data-stu-id="859c0-146">Additionally, outgoing mail from Exchange Online mailboxes is routed through the on-premises Exchange organization for messages sent to external recipients.</span></span> <span data-ttu-id="859c0-147">使用此配置，您可以为内部部署 Exchange 组织和 Exchange Online 组织的所有邮箱使用单个 SMTP 域命名空间。</span><span class="sxs-lookup"><span data-stu-id="859c0-147">With this configuration, you can use a single SMTP domain namespace for all mailboxes in both your on-premises Exchange organization and your Exchange Online organization.</span></span> 
  
<span data-ttu-id="859c0-148">若要详细了解混合部署中的传输选项，请参阅 [Exchange 混合部署的传输选项](/exchange/transport-options)。</span><span class="sxs-lookup"><span data-stu-id="859c0-148">For more information about transport options in a hybrid deployment, see [Transport options in Exchange hybrid deployments](/exchange/transport-options).</span></span>
  
### <a name="shared-address-space-without-on-premises-routing-control-mx-points-to-eop"></a><span data-ttu-id="859c0-149">不含内部路由控制的共享地址空间（MX 指向 EOP）</span><span class="sxs-lookup"><span data-stu-id="859c0-149">Shared Address Space without On-Premises Routing Control (MX Points to EOP)</span></span>

<span data-ttu-id="859c0-150">没有本地路由控制的共享地址空间 (MX 指向 EOP) 是一种混合邮件路由方案，其中邮箱使用 Exchange Online 部分托管在云中，部分本地托管，而 MX 记录指向 EOP。</span><span class="sxs-lookup"><span data-stu-id="859c0-150">Shared Address Space without On-Premises Routing Control (MX Points to EOP) is a hybrid mail-routing scenario in which your mailboxes are hosted partially in the cloud using Exchange Online and partially on-premises, and your MX record points to EOP.</span></span> <span data-ttu-id="859c0-151">当你使用 Microsoft 托管组织的一些邮箱，并且希望 EOP 同时保护本地邮箱和云邮箱时，此方案很适用。</span><span class="sxs-lookup"><span data-stu-id="859c0-151">This scenario is appropriate when you use Microsoft to host some of your organization's mailboxes and you want EOP to protect both your on-premises and cloud mailboxes.</span></span> <span data-ttu-id="859c0-152">在此方案中，发送给组织内部收件人的邮件最初通过 EOP 进行路由，其中垃圾邮件和策略筛选发生在到达内部部署邮箱和云邮箱之前。</span><span class="sxs-lookup"><span data-stu-id="859c0-152">In this scenario, mail sent to recipients within your organization is initially routed through EOP, where spam and policy filtering occurs, before it reaches your on-premises mailboxes and cloud mailboxes.</span></span> 
  
<span data-ttu-id="859c0-153">若要详细了解混合部署中的传输选项，请参阅 [Exchange 混合部署的传输选项](/exchange/transport-options)。</span><span class="sxs-lookup"><span data-stu-id="859c0-153">For more information about transport options in a hybrid deployment, see [Transport options in Exchange hybrid deployments](/exchange/transport-options).</span></span>
  
### <a name="troubleshooting-a-deployment-with-the-hybrid-configuration-wizard"></a><span data-ttu-id="859c0-154">使用混合配置向导解决部署问题</span><span class="sxs-lookup"><span data-stu-id="859c0-154">Troubleshooting a deployment with the Hybrid Configuration Wizard</span></span>

<span data-ttu-id="859c0-p111">在 Microsoft Exchange Server 中使用混合配置向导来配置混合部署将极大地减少混合部署出现问题的可能性。然而，这里有一些混合配置向导范围之外的典型区域，如果配置不当的话，可能导致混合部署出现问题。这些配置包括正确的客户端访问服务器配置，以及正确的证书安装和配置。</span><span class="sxs-lookup"><span data-stu-id="859c0-p111">Using the Hybrid Configuration Wizard to configure a hybrid deployment in Microsoft Exchange Server greatly minimizes the potential that the hybrid deployment will experience problems. However, there are some typical areas outside the scope of the Hybrid Configuration Wizard that, if misconfigured, may present problems in a hybrid deployment. These include proper Client Access server configuration and proper certificate installation and configuration.</span></span>
  
<span data-ttu-id="859c0-158">若要详细了解如何使用混合配置向导解决部署问题，请参阅[混合部署故障排除](/exchange/hybrid-deployment/troubleshoot-a-hybrid-deployment)。</span><span class="sxs-lookup"><span data-stu-id="859c0-158">For more information about troubleshooting a deployment with the Hybrid Configuration Wizard, see [Troubleshoot a hybrid deployment](/exchange/hybrid-deployment/troubleshoot-a-hybrid-deployment).</span></span>
  
### <a name="managing-a-hybrid-configuration"></a><span data-ttu-id="859c0-159">管理混合配置</span><span class="sxs-lookup"><span data-stu-id="859c0-159">Managing a hybrid configuration</span></span>

<span data-ttu-id="859c0-p112">通过更改混合配置向导中的设置，您可以修改现有混合配置。方案包括禁用集中式传输或禁用安全邮件传输。</span><span class="sxs-lookup"><span data-stu-id="859c0-p112">You can modify an existing hybrid configuration by changing settings in the Hybrid Configuration Wizard. Scenarios include disabling centralized transport or disabling secure mail transport.</span></span>
  
<span data-ttu-id="859c0-162">若要详细了解如何管理混合部署配置，请参阅[管理混合部署](/previous-versions/exchange-server/exchange-150/jj200791(v=exchg.150))。</span><span class="sxs-lookup"><span data-stu-id="859c0-162">For more information about managing a hybrid deployment configuration, see [Manage a hybrid deployment](/previous-versions/exchange-server/exchange-150/jj200791(v=exchg.150)).</span></span>
  
### <a name="hybrid-deployment-requirements"></a><span data-ttu-id="859c0-163">混合部署要求</span><span class="sxs-lookup"><span data-stu-id="859c0-163">Hybrid deployment requirements</span></span>

<span data-ttu-id="859c0-164">若要详细了解混合部署要求，请参阅[混合部署先决条件](/exchange/hybrid-deployment-prerequisites)。</span><span class="sxs-lookup"><span data-stu-id="859c0-164">For more information about hybrid deployment requirements, see [Hybrid deployment prerequisites](/exchange/hybrid-deployment-prerequisites).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="859c0-165">在某些混合配置中，您必须为内部邮箱购买 Exchange Online Protection 许可证。</span><span class="sxs-lookup"><span data-stu-id="859c0-165">In some hybrid configurations, you may need to purchase Exchange Online Protection licenses for your on-premises mailboxes.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="859c0-166">功能可用性</span><span class="sxs-lookup"><span data-stu-id="859c0-166">Feature availability</span></span>

<span data-ttu-id="859c0-167">若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅 Exchange Online [服务说明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="859c0-167">To view feature availability across plans, standalone options, and on-premises solutions, see the [Exchange Online service description](exchange-online-service-description.md).</span></span>
