---
title: 邮件策略和合规性[ServiceDesc]
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: Microsoft Exchange Online Protection (EOP) 提供邮件策略和合规性功能，可帮助您管理电子邮件数据。
ms.openlocfilehash: f88cd016586384f4617cd4899708c811a32af980
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035025"
---
# <a name="messaging-policy-and-complianceservicedesc"></a><span data-ttu-id="b3f25-103">邮件策略和合规性[ServiceDesc]</span><span class="sxs-lookup"><span data-stu-id="b3f25-103">Messaging Policy and Compliance[ServiceDesc]</span></span>

<span data-ttu-id="b3f25-104">Microsoft Exchange Online Protection (EOP) 提供邮件策略和合规性功能，可帮助您管理电子邮件数据。</span><span class="sxs-lookup"><span data-stu-id="b3f25-104">Microsoft Exchange Online Protection (EOP) provides messaging policy and compliance features that can help you manage your email data.</span></span>
  
<span data-ttu-id="b3f25-p101">想了解 EOP 的所有功能？请参阅 [Exchange Online Protection 服务说明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="b3f25-p101">Looking for information about all EOP features? See the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="transport-rules"></a><span data-ttu-id="b3f25-107">传输规则</span><span class="sxs-lookup"><span data-stu-id="b3f25-107">Transport rules</span></span>
<span data-ttu-id="b3f25-108"><a name="BKMK_transportrules"> </a></span><span class="sxs-lookup"><span data-stu-id="b3f25-108"></span></span>

<span data-ttu-id="b3f25-p102">使用传输规则，可以灵活地向电子邮件应用你自己的公司专属策略。传输规则由灵活条件构成，可方便你根据条件定义条件、异常和要采取的措施。若要详细了解 EOP 中的传输规则，请参阅[传输规则](https://go.microsoft.com/fwlink/p/?LinkId=320399)。</span><span class="sxs-lookup"><span data-stu-id="b3f25-p102">Transport rules provide you with the flexibility to apply your own company-specific policies to email. Transport rules are made up of flexible criteria, which allow you to define conditions and exceptions, and actions to take based on the criteria. For more information about Transport rules in EOP, see [Transport Rules](https://go.microsoft.com/fwlink/p/?LinkId=320399).</span></span>
  
## <a name="audit-logging"></a><span data-ttu-id="b3f25-112">审核日志记录</span><span class="sxs-lookup"><span data-stu-id="b3f25-112">Audit logging</span></span>
<span data-ttu-id="b3f25-113"><a name="BKMK_auditlogging"> </a></span><span class="sxs-lookup"><span data-stu-id="b3f25-113"></span></span>

<span data-ttu-id="b3f25-p103">使用审核日志记录，可以跟踪管理员对组织做出的特定更改。这些报告可帮助你遵守法规、符合性和诉讼要求。有关详细信息，请参阅 [EOP 中的审核报告](https://go.microsoft.com/fwlink/p/?LinkId=314258)。</span><span class="sxs-lookup"><span data-stu-id="b3f25-p103">Audit logging lets you track specific changes made by administrators to your organization. These reports help you meet regulatory, compliance, and litigation requirements. For more information, see [Auditing Reports in EOP](https://go.microsoft.com/fwlink/p/?LinkId=314258).</span></span>
  
## <a name="data-loss-prevention-dlp"></a><span data-ttu-id="b3f25-117">数据丢失防护 (DLP)</span><span class="sxs-lookup"><span data-stu-id="b3f25-117">Data loss prevention (DLP)</span></span>
<span data-ttu-id="b3f25-118"><a name="BKMK_datalossprevention"> </a></span><span class="sxs-lookup"><span data-stu-id="b3f25-118"></span></span>

<span data-ttu-id="b3f25-p104">对独立 EOP 客户不可用。数据丢失防护 (DLP) 可进行深入内容分析，帮助识别、监视和保护您组织中的敏感信息。DLP 对于企业邮件系统而言越来越重要，因为对于企业非常重要的电子邮件包含需要保护的敏感信息。DLP 功能可让您保护敏感数据，而不会影响工作人员的生产率。</span><span class="sxs-lookup"><span data-stu-id="b3f25-p104">Not available to EOP standalone customers. Data loss prevention (DLP) helps you identify, monitor, and protect sensitive information in your organization through deep content analysis. DLP is increasingly important for enterprise message systems because business-critical email includes sensitive data that needs to be protected. The DLP feature enables you to protect sensitive data without affecting worker productivity.</span></span>
  
<span data-ttu-id="b3f25-123">您可以在 EAC 中配置 DLP 策略，从而能够：</span><span class="sxs-lookup"><span data-stu-id="b3f25-123">You can configure DLP policies in the EAC, which allows you to:</span></span>
  
- <span data-ttu-id="b3f25-124">启动预配置的策略模板，此模板可帮助您检测特定类型的敏感信息，如 PCI-DSS 数据、格雷姆-里奇-比利雷法案数据，甚至是区域设置特定的个人身份信息 (PII)。</span><span class="sxs-lookup"><span data-stu-id="b3f25-124">Start with a pre-configured policy template that can help you detect specific types of sensitive information such as PCI-DSS data, Gramm-Leach-Bliley act data, or even locale-specific personally identifiable information (PII).</span></span>
    
- <span data-ttu-id="b3f25-125">使用现有传输规则条件和操作的强大功能，并添加新的传输规则。</span><span class="sxs-lookup"><span data-stu-id="b3f25-125">Use the full power of existing transport rule criteria and actions and add new transport rules.</span></span>
    
- <span data-ttu-id="b3f25-126">在全面执行前，测试您的 DLP 策略的有效性。</span><span class="sxs-lookup"><span data-stu-id="b3f25-126">Test the effectiveness of your DLP policies before fully enforcing them.</span></span>
    
- <span data-ttu-id="b3f25-127">整合您自己的自定义 DLP 策略模板和敏感的信息类型。</span><span class="sxs-lookup"><span data-stu-id="b3f25-127">Incorporate your own custom DLP policy templates and sensitive information types.</span></span>
    
- <span data-ttu-id="b3f25-128">检测邮件附件、正文文本或主题行中的敏感信息，然后调整该服务采取措施的置信度水平。</span><span class="sxs-lookup"><span data-stu-id="b3f25-128">Detect sensitive information in message attachments, body text, or subject lines and adjust the confidence level at which the service takes action.</span></span>
    
- <span data-ttu-id="b3f25-p105">通过使用文档指纹检测敏感型数据。文档指纹可以帮助您基于文本形式（您可以用其定义传输规则和 DLP 策略）轻松地创建自定义敏感信息类型。</span><span class="sxs-lookup"><span data-stu-id="b3f25-p105">Detect sensitive form data by using Document Fingerprinting. Document Fingerprinting helps you easily create custom sensitive information types based on text-based forms that you can use to define transport rules and DLP policies.</span></span>
    
- <span data-ttu-id="b3f25-131">添加策略提示，它可通过向 Outlook 2013、Outlook Web App 和适用于设备的 OWA 的用户显示通知来帮助减少数据丢失，还可以通过允许误报报告来提高策略的有效性。</span><span class="sxs-lookup"><span data-stu-id="b3f25-131">Add Policy Tips, which can help reduce data loss by displaying a notice to your Outlook 2013, Outlook Web App, and OWA for Devices users and can also improve the effectiveness of your policies by allowing false-positive reporting.</span></span>
    
- <span data-ttu-id="b3f25-132">查看 DLP 报告中的事件数据，或通过使用生成事件报告操作来添加自己的特定报告。</span><span class="sxs-lookup"><span data-stu-id="b3f25-132">Review incident data in DLP reports or add your own specific reports by using a generate incident report action.</span></span>
    
> [!NOTE]
> <span data-ttu-id="b3f25-p106">DLP 策略仅适用于传进或传出组织的邮件。组织内（内部）邮件没有适用的 DLP 策略，除非您运行包含本地 DLP 的 Exchange Server 2013。这还适用于 DLP 策略提示，可以在敏感数据被错误发送到未经授权收件人之前通知用户潜在的策略违反。</span><span class="sxs-lookup"><span data-stu-id="b3f25-p106">DLP policies are applied only to mail that passes in or out of the organization. Intra-organizational (internal) mail does not have DLP policies applied unless you run Exchange Server 2013 with DLP on-premises. This also applies to DLP policy tips, which inform users about potential policy violations before sensitive data is mistakenly sent to unauthorized recipients.</span></span> 
  
<span data-ttu-id="b3f25-136">若要详细了解 DLP，请参阅[数据丢失防护](https://go.microsoft.com/fwlink/p/?LinkId=320398)。</span><span class="sxs-lookup"><span data-stu-id="b3f25-136">To learn more about DLP, see [Data Loss Prevention](https://go.microsoft.com/fwlink/p/?LinkId=320398).</span></span>
  
## <a name="office-365-message-encryption"></a><span data-ttu-id="b3f25-137">Office 365 邮件加密</span><span class="sxs-lookup"><span data-stu-id="b3f25-137">Office 365 Message Encryption</span></span>
<span data-ttu-id="b3f25-138"><a name="BKMK_OME_in_EOP"> </a></span><span class="sxs-lookup"><span data-stu-id="b3f25-138"></span></span>

<span data-ttu-id="b3f25-p107">Office 365 邮件加密，一部分 Azure 信息保护，是允许任何人发送加密的电子邮件的电子邮件用户的联机服务。本地客户可以通过购买 Azure 信息保护和使用 Exchange Online Protection 设置邮件流通过 Exchange Online 中访问 Office 365 邮件加密。若要详细了解 Office 365 邮件加密在 Exchange Online，请参阅 Exchange Online Service Description 中的[Office 365 邮件加密](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption)。</span><span class="sxs-lookup"><span data-stu-id="b3f25-p107">Office 365 Message Encryption, a part of Azure Information Protection, is an online service that allows email users to send encrypted email messages to anyone. On-premises customers can access Office 365 Message Encryption by purchasing Azure Information Protection and using Exchange Online Protection to set up mail flow through Exchange Online. To learn more about Office 365 Message Encryption in Exchange Online, see [Office 365 Message Encryption](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption) in the Exchange Online Service Description.</span></span> 
  
## <a name="messaging-policy-and-compliance-features-across-eop-options"></a><span data-ttu-id="b3f25-142">跨 EOP 选项的邮件策略和合规性功能</span><span class="sxs-lookup"><span data-stu-id="b3f25-142">Messaging policy and compliance features across EOP options</span></span>
<span data-ttu-id="b3f25-143"><a name="BKMK_OME_in_EOP"> </a></span><span class="sxs-lookup"><span data-stu-id="b3f25-143"></span></span>

|<span data-ttu-id="b3f25-144">**功能**</span><span class="sxs-lookup"><span data-stu-id="b3f25-144">**Feature**</span></span>|<span data-ttu-id="b3f25-145">**独立 EOP**</span><span class="sxs-lookup"><span data-stu-id="b3f25-145">**EOP standalone**</span></span>|<span data-ttu-id="b3f25-146">**Exchange Online 中的 EOP 功能**</span><span class="sxs-lookup"><span data-stu-id="b3f25-146">**EOP features in Exchange Online**</span></span>|<span data-ttu-id="b3f25-147">**Exchange Enterprise CAL with Services**</span><span class="sxs-lookup"><span data-stu-id="b3f25-147">**Exchange Enterprise CAL with Services**</span></span>|
|:-----|:-----|:-----|:-----|
|<span data-ttu-id="b3f25-148">传输规则</span><span class="sxs-lookup"><span data-stu-id="b3f25-148">Transport rules</span></span>  <br/> |<span data-ttu-id="b3f25-149">是<sup>1</sup></span><span class="sxs-lookup"><span data-stu-id="b3f25-149">Yes<sup>1</sup></span></span> <br/> |<span data-ttu-id="b3f25-150">是<sup>1</sup></span><span class="sxs-lookup"><span data-stu-id="b3f25-150">Yes<sup>1</sup></span></span> <br/> |<span data-ttu-id="b3f25-151">是</span><span class="sxs-lookup"><span data-stu-id="b3f25-151">Yes</span></span>  <br/> |
|<span data-ttu-id="b3f25-152">审核日志记录</span><span class="sxs-lookup"><span data-stu-id="b3f25-152">Audit logging</span></span>  <br/> |<span data-ttu-id="b3f25-153">是<sup>2</sup></span><span class="sxs-lookup"><span data-stu-id="b3f25-153">Yes<sup>2</sup></span></span> <br/> |<span data-ttu-id="b3f25-154">是</span><span class="sxs-lookup"><span data-stu-id="b3f25-154">Yes</span></span>  <br/> |<span data-ttu-id="b3f25-155">是</span><span class="sxs-lookup"><span data-stu-id="b3f25-155">Yes</span></span>  <br/> |
|<span data-ttu-id="b3f25-156">数据丢失防护 (DLP)</span><span class="sxs-lookup"><span data-stu-id="b3f25-156">Data Loss Prevention (DLP)</span></span>  <br/> |<span data-ttu-id="b3f25-157">否</span><span class="sxs-lookup"><span data-stu-id="b3f25-157">No</span></span>  <br/> |<span data-ttu-id="b3f25-158">是</span><span class="sxs-lookup"><span data-stu-id="b3f25-158">Yes</span></span>  <br/> |<span data-ttu-id="b3f25-159">是<sup>3</sup></span><span class="sxs-lookup"><span data-stu-id="b3f25-159">Yes<sup>3</sup></span></span> <br/> |
|<span data-ttu-id="b3f25-160">Office 365 邮件加密</span><span class="sxs-lookup"><span data-stu-id="b3f25-160">Office 365 Message Encryption</span></span>  <br/> |<span data-ttu-id="b3f25-161">是<sup>4</sup></span><span class="sxs-lookup"><span data-stu-id="b3f25-161">Yes<sup>4</sup></span></span> <br/> |<span data-ttu-id="b3f25-162">是</span><span class="sxs-lookup"><span data-stu-id="b3f25-162">Yes</span></span>  <br/> |<span data-ttu-id="b3f25-163">是<sup>4</sup></span><span class="sxs-lookup"><span data-stu-id="b3f25-163">Yes<sup>4</sup></span></span> <br/> |
   
> [!NOTE]
> <span data-ttu-id="b3f25-p108">EOP 和 Exchange Online 之间不同<sup>1</sup>的可用条件和操作。有关可用条件和操作在 EOP 中的列表，请参阅[传输规则条件](https://go.microsoft.com/fwlink/p/?LinkId=320392)和[Transport Rule Actions](https://go.microsoft.com/fwlink/p/?LinkId=320393)。有关可用条件和操作 Exchange Online 中的列表，请参阅[传输规则条件](https://go.microsoft.com/fwlink/p/?LinkId=320394)和[Transport Rule Actions](https://go.microsoft.com/fwlink/p/?LinkId=320395)。> <sup>2</sup> EOP 审核报告的子集 Exchange Online 审核不包括邮箱信息的报告。> <sup>3</sup> DLP 策略提示不可用于 Exchange Enterprise CAL with Services 客户。> <sup>4</sup>受支持的本地客户购买的 Azure 信息保护加载项并通过 Exchange Online 路由电子邮件中使用 Exchange Online Protection。对于桌面体验，除了 Azure 信息保护加载项，Office 365 ProPlus 需要购买。</span><span class="sxs-lookup"><span data-stu-id="b3f25-p108"><sup>1</sup> The available criteria and actions differ between EOP and Exchange Online. For a list of available criteria and actions in EOP, see [Transport Rule Criteria](https://go.microsoft.com/fwlink/p/?LinkId=320392) and [Transport Rule Actions](https://go.microsoft.com/fwlink/p/?LinkId=320393). For a list of available criteria and actions in Exchange Online, see [Transport Rule Criteria](https://go.microsoft.com/fwlink/p/?LinkId=320394) and [Transport Rule Actions](https://go.microsoft.com/fwlink/p/?LinkId=320395). > <sup>2</sup> EOP auditing reports are a subset of Exchange Online auditing reports that exclude information about mailboxes. > <sup>3</sup> DLP policy tips are not available for Exchange Enterprise CAL with Services customers. > <sup>4</sup> Supported for on-premises customers who purchase the Azure Information Protection add-on and use Exchange Online Protection to route email through Exchange Online. For the desktop experience, in addition to the Azure Information Protection add-on, Office 365 ProPlus needs to be purchased.</span></span> 
  

