---
title: Office 365 高级威胁防护服务说明
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 高级威胁保护 (ATP) 是基于云的电子邮件筛选服务，可帮助保护您的组织免受未知的恶意软件和病毒通过提供强大的零时差保护，并包括功能来保护您从实时有害链接的组织。ATP 具有丰富报告和 URL 跟踪功能，为管理员提供深入的组织中发生的攻击的类型。
ms.openlocfilehash: 6c7ce44932312b82293b19d85ebac07137716617
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035109"
---
# <a name="office-365-advanced-threat-protection-service-description"></a><span data-ttu-id="834c5-104">Office 365 高级威胁防护服务说明</span><span class="sxs-lookup"><span data-stu-id="834c5-104">Office 365 Advanced Threat Protection Service Description</span></span>

<span data-ttu-id="834c5-p102">Microsoft Office 365 高级威胁保护 (ATP) 是基于云的电子邮件筛选服务，可帮助保护您的组织免受未知的恶意软件和病毒通过提供强大的零时差保护，并包括功能来保护您从实时有害链接的组织。ATP 具有丰富报告和 URL 跟踪功能，为管理员提供深入的组织中发生的攻击的类型。</span><span class="sxs-lookup"><span data-stu-id="834c5-p102">Microsoft Office 365 Advanced Threat Protection (ATP) is a cloud-based email filtering service that helps protect your organization against unknown malware and viruses by providing robust zero-day protection, and includes features to safeguard your organization from harmful links in real time. ATP has rich reporting and URL trace capabilities that give administrators insight into the kind of attacks happening in your organization.</span></span>
  
<span data-ttu-id="834c5-107">以下是您可以使用 ATP 进行邮件保护的主要方式：</span><span class="sxs-lookup"><span data-stu-id="834c5-107">The following are the primary ways you can use ATP for messaging protection:</span></span>
  
- <span data-ttu-id="834c5-108">在 Office 365 ATP 仅筛选方案中，ATP 提供的基于云的电子邮件保护您的内部部署 Exchange Server 2013 环境、 旧版 Exchange Server 或其他任何本地 SMTP 电子邮件解决方案。</span><span class="sxs-lookup"><span data-stu-id="834c5-108">In an Office 365 ATP filtering-only scenario, ATP provides cloud-based email protection for your on-premises Exchange Server 2013 environment, legacy Exchange Server versions, or any other on-premises SMTP email solution.</span></span>
    
- <span data-ttu-id="834c5-p103">Office 365 ATP 可以启用保护云承载的 Exchange Online 邮箱。若要了解有关 Exchange Online 的详细信息，请参阅[Exchange Online Service Description](https://technet.microsoft.com/en-us/library/exchange-online-service-description.aspx)。</span><span class="sxs-lookup"><span data-stu-id="834c5-p103">Office 365 ATP can be enabled to protect Exchange Online cloud-hosted mailboxes. To learn more about Exchange Online, see the [Exchange Online Service Description](https://technet.microsoft.com/en-us/library/exchange-online-service-description.aspx).</span></span>
    
- <span data-ttu-id="834c5-111">在混合部署中，可以配置 ATP 为保护您的邮件环境并控制邮件路由时具有的内部部署混合和云邮箱与 Exchange Online Protection 入站电子邮件筛选。</span><span class="sxs-lookup"><span data-stu-id="834c5-111">In a hybrid deployment, ATP can be configured to protect your messaging environment and control mail routing when you have a mix of on-premises and cloud mailboxes with Exchange Online Protection for inbound email filtering.</span></span>
    
## <a name="office-365-advanced-threat-protection-atp-availability"></a><span data-ttu-id="834c5-112">Office 365 高级威胁保护 (ATP) 可用性</span><span class="sxs-lookup"><span data-stu-id="834c5-112">Office 365 Advanced Threat Protection (ATP) availability</span></span>

<span data-ttu-id="834c5-113">ATP 包含在 Office 365 企业 E5、 Office 365 教育版 A5 和 Microsoft 365 企业版。</span><span class="sxs-lookup"><span data-stu-id="834c5-113">ATP is included in Office 365 Enterprise E5, Office 365 Education A5, and Microsoft 365 Business.</span></span> 
  
> [!NOTE]
> <span data-ttu-id="834c5-114">Microsoft 365 企业版中的客户端依赖于 ATP 功能将可用夏季完成 2018年。</span><span class="sxs-lookup"><span data-stu-id="834c5-114">Client-dependent ATP features in Microsoft 365 Business will be available Summer 2018.</span></span> 
  
<span data-ttu-id="834c5-115">可以将 ATP 添加到以下 Exchange 和 Office 365 订阅计划中：</span><span class="sxs-lookup"><span data-stu-id="834c5-115">You can add ATP to the following Exchange and Office 365 subscription plans:</span></span> 
  
- <span data-ttu-id="834c5-116">Exchange Online 计划 1</span><span class="sxs-lookup"><span data-stu-id="834c5-116">Exchange Online Plan 1</span></span>
    
- <span data-ttu-id="834c5-117">Exchange Online 计划 2</span><span class="sxs-lookup"><span data-stu-id="834c5-117">Exchange Online Plan 2</span></span>
    
- <span data-ttu-id="834c5-118">Exchange Online Kiosk</span><span class="sxs-lookup"><span data-stu-id="834c5-118">Exchange Online Kiosk</span></span>
    
- <span data-ttu-id="834c5-119">Exchange Online Protection</span><span class="sxs-lookup"><span data-stu-id="834c5-119">Exchange Online Protection</span></span>
    
- <span data-ttu-id="834c5-120">Office 365 商业协作版</span><span class="sxs-lookup"><span data-stu-id="834c5-120">Office 365 Business Essentials</span></span>
    
- <span data-ttu-id="834c5-121">Help and training</span><span class="sxs-lookup"><span data-stu-id="834c5-121">Office 365 Business Premium</span></span>
    
- <span data-ttu-id="834c5-122">Office 365 企业版 E1</span><span class="sxs-lookup"><span data-stu-id="834c5-122">Office 365 Enterprise E1</span></span>
    
- <span data-ttu-id="834c5-123">Office 365 企业版 E3</span><span class="sxs-lookup"><span data-stu-id="834c5-123">Office 365 Enterprise E3</span></span>
    
- <span data-ttu-id="834c5-124">Office 365 企业版 F1</span><span class="sxs-lookup"><span data-stu-id="834c5-124">Office 365 Enterprise F1</span></span>
    
- <span data-ttu-id="834c5-125">Office 365 A1</span><span class="sxs-lookup"><span data-stu-id="834c5-125">Office 365 A1</span></span>
    
- <span data-ttu-id="834c5-126">Office 365 A3</span><span class="sxs-lookup"><span data-stu-id="834c5-126">Office 365 A3</span></span>
    
<span data-ttu-id="834c5-127">若要购买 Office 365 高级威胁保护，请参阅[Office 365 高级威胁保护](https://go.microsoft.com/fwlink/p/?LinkId=294201)。</span><span class="sxs-lookup"><span data-stu-id="834c5-127">To buy Office 365 Advanced Threat Protection, see [Office 365 Advanced Threat Protection](https://go.microsoft.com/fwlink/p/?LinkId=294201).</span></span>
  
<span data-ttu-id="834c5-128">若要跨计划比较功能，请参阅[比较 Office 365 商业版计划](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409)。</span><span class="sxs-lookup"><span data-stu-id="834c5-128">To compare features across plans, see [Compare Office 365 for Business plans](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409).</span></span>
  
## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a><span data-ttu-id="834c5-129">What's new 在 Office 365 高级威胁保护 (ATP)</span><span class="sxs-lookup"><span data-stu-id="834c5-129">What's new in Office 365 Advanced Threat Protection (ATP)</span></span>

<span data-ttu-id="834c5-130">有关 ATP 中的新功能的信息，请参阅[Office 365 中的 ATP 安全链接](https://go.microsoft.com/fwlink/?linkid=846016)。</span><span class="sxs-lookup"><span data-stu-id="834c5-130">For information about new features in ATP, see [ATP safe links in Office 365](https://go.microsoft.com/fwlink/?linkid=846016).</span></span>
  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a><span data-ttu-id="834c5-131">Office 365 的高级的威胁保护 (ATP) 的要求</span><span class="sxs-lookup"><span data-stu-id="834c5-131">Requirements for Office 365 Advanced Threat Protection (ATP)</span></span>

<span data-ttu-id="834c5-p104">ATP 可以与任何 SMTP 邮件传输代理（如 Microsoft Exchange Server 2013）结合使用。若要了解 ATP 支持的操作系统、Web 浏览器和语言，请参阅 [Exchange Online Protection 中的 Exchange 管理中心](https://go.microsoft.com/fwlink/p/?LinkId=282381)的"支持的浏览器"和"支持的语言"部分。</span><span class="sxs-lookup"><span data-stu-id="834c5-p104">ATP can be used with any SMTP mail transfer agent, such as Microsoft Exchange Server 2013. For information about the operating systems, web browsers, and languages that are supported by ATP, see the "Supported browsers" and "Supported languages" sections in [Exchange Admin Center in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).</span></span>
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a><span data-ttu-id="834c5-134">跨高级威胁保护 (ATP) 计划功能可用性</span><span class="sxs-lookup"><span data-stu-id="834c5-134">Feature availability across Advanced Threat Protection (ATP) plans</span></span>

<span data-ttu-id="834c5-p105">下面列出了每个功能。当提到 Exchange Online 时，通常指的是 Office 365 企业版服务系列。</span><span class="sxs-lookup"><span data-stu-id="834c5-p105">Each feature is listed below. When Exchange Online is mentioned, it typically refers to the Office 365 Enterprise service family.</span></span>
  
|<span data-ttu-id="834c5-137">**功能**</span><span class="sxs-lookup"><span data-stu-id="834c5-137">**Feature**</span></span>|<span data-ttu-id="834c5-138">**独立 ATP**</span><span class="sxs-lookup"><span data-stu-id="834c5-138">**ATP standalone**</span></span>|<span data-ttu-id="834c5-139">**Exchange Online Protection**</span><span class="sxs-lookup"><span data-stu-id="834c5-139">**Exchange Online Protection**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="834c5-140">安全链接</span><span class="sxs-lookup"><span data-stu-id="834c5-140">Safe Links</span></span>  <br/> |<span data-ttu-id="834c5-141">是</span><span class="sxs-lookup"><span data-stu-id="834c5-141">Yes</span></span>  <br/> |<span data-ttu-id="834c5-142">否</span><span class="sxs-lookup"><span data-stu-id="834c5-142">No</span></span>  <br/> |
|<span data-ttu-id="834c5-143">安全附件</span><span class="sxs-lookup"><span data-stu-id="834c5-143">Safe Attachments</span></span>  <br/> |<span data-ttu-id="834c5-144">是</span><span class="sxs-lookup"><span data-stu-id="834c5-144">Yes</span></span>  <br/> |<span data-ttu-id="834c5-145">否</span><span class="sxs-lookup"><span data-stu-id="834c5-145">No</span></span>  <br/> |
|<span data-ttu-id="834c5-146">欺骗智能</span><span class="sxs-lookup"><span data-stu-id="834c5-146">Spoof intelligence</span></span>  <br/> |<span data-ttu-id="834c5-147">是</span><span class="sxs-lookup"><span data-stu-id="834c5-147">Yes</span></span>  <br/> |<span data-ttu-id="834c5-148">否</span><span class="sxs-lookup"><span data-stu-id="834c5-148">No</span></span>  <br/> |
|<span data-ttu-id="834c5-149">隔离</span><span class="sxs-lookup"><span data-stu-id="834c5-149">Quarantine</span></span>  <br/> |<span data-ttu-id="834c5-150">是</span><span class="sxs-lookup"><span data-stu-id="834c5-150">Yes</span></span>  <br/> |<span data-ttu-id="834c5-151">是</span><span class="sxs-lookup"><span data-stu-id="834c5-151">Yes</span></span>  <br/> |
|<span data-ttu-id="834c5-152">高级的防钓鱼功能</span><span class="sxs-lookup"><span data-stu-id="834c5-152">Advanced anti-phishing capabilities</span></span>  <br/> |<span data-ttu-id="834c5-153">是</span><span class="sxs-lookup"><span data-stu-id="834c5-153">Yes</span></span>  <br/> |<span data-ttu-id="834c5-154">否</span><span class="sxs-lookup"><span data-stu-id="834c5-154">No</span></span>  <br/> |
   
## <a name="advanced-threat-protection-atp-capabilities"></a><span data-ttu-id="834c5-155">高级的威胁保护 (ATP) 功能</span><span class="sxs-lookup"><span data-stu-id="834c5-155">Advanced Threat Protection (ATP) Capabilities</span></span>

### <a name="safe-links"></a><span data-ttu-id="834c5-156">安全链接</span><span class="sxs-lookup"><span data-stu-id="834c5-156">Safe Links</span></span>

<span data-ttu-id="834c5-p106">ATP 安全链接功能主动保护您的用户从邮件中的恶意超链接。保护保持每次用户单击此链接，可以访问良好的链接时动态阻止恶意链接。</span><span class="sxs-lookup"><span data-stu-id="834c5-p106">The ATP Safe Links feature proactively protects your users from malicious hyperlinks in a message. The protection remains every time they click the link, as malicious links are dynamically blocked while good links can be accessed.</span></span>
  
### <a name="safe-attachments"></a><span data-ttu-id="834c5-159">安全附件</span><span class="sxs-lookup"><span data-stu-id="834c5-159">Safe Attachments</span></span>

<span data-ttu-id="834c5-p107">安全附件可防御未知恶意软件和病毒的攻击，并提供了零日保护，以保护您的邮件系统。所有不带有已知的病毒/恶意软件签名的邮件和附件都被路由到一个特殊的环境中，ATP 将在其中使用多种机器学习和分析技术来检测恶意企图。如果没有检测到可疑的活动，会发布邮件并传递到邮箱中。</span><span class="sxs-lookup"><span data-stu-id="834c5-p107">Safe Attachments protects against unknown malware and viruses, and provides zero-day protection to safeguard your messaging system. All messages and attachments that don't have a known virus/malware signature are routed to a special environment where ATP uses a variety of machine learning and analysis techniques to detect malicious intent. If no suspicious activity is detected, the message is released for delivery to the mailbox.</span></span> 
  
### <a name="spoof-intelligence"></a><span data-ttu-id="834c5-163">欺骗智能</span><span class="sxs-lookup"><span data-stu-id="834c5-163">Spoof intelligence</span></span>

<span data-ttu-id="834c5-p108">欺骗智能检测何时发件人出现在一个组织的域发送邮件代表一个或多个用户帐户。使您可以查看所有发件人在伪造您的域，然后选择要允许发件人继续，或阻止发件人。欺骗智能安全中位于&amp;反垃圾邮件设置页上的合规性中心。</span><span class="sxs-lookup"><span data-stu-id="834c5-p108">Spoof intelligence detects when a sender appears to be sending mail on behalf of one or more user accounts within one of your organization's domains. It enables you to review all senders who are spoofing your domain, and then choose to allow the sender to continue or block the sender. Spoof intelligence is available in the Security &amp; Compliance Center on the Anti-spam settings page.</span></span>
  
### <a name="quarantine"></a><span data-ttu-id="834c5-167">隔离</span><span class="sxs-lookup"><span data-stu-id="834c5-167">Quarantine</span></span>

<span data-ttu-id="834c5-p109">邮件由 Office 365 服务标识为垃圾邮件，批量邮件、 网络钓鱼邮件，包含恶意软件，或因为它们匹配的邮件流规则可以发送到隔离。默认情况下，Office 365 发送网络钓鱼邮件和邮件包含恶意软件直接到隔离。授权的用户可以查看、 删除或管理电子邮件发送到隔离。</span><span class="sxs-lookup"><span data-stu-id="834c5-p109">Messages identified by the Office 365 service as spam, bulk mail, phishing mail, containing malware, or because they matched a mail flow rule can be sent to quarantine. By default, Office 365 sends phishing messages and messages containing malware directly to quarantine. Authorized users can review, delete, or manage email messages sent to quarantine.</span></span>
  
### <a name="advanced-anti-phishing-capabilities"></a><span data-ttu-id="834c5-171">高级的防钓鱼功能</span><span class="sxs-lookup"><span data-stu-id="834c5-171">Advanced anti-phishing capabilities</span></span>

<span data-ttu-id="834c5-172">此功能使用计算机学习模型来检测网络钓鱼邮件。</span><span class="sxs-lookup"><span data-stu-id="834c5-172">This feature uses machine learning models to detect phishing messages.</span></span> 
  
