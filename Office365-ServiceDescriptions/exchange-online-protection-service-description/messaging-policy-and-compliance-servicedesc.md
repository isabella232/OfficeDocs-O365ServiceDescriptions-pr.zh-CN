---
title: 邮件策略和遵从性
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: Microsoft Exchange Online Protection （EOP）提供了可帮助您管理电子邮件数据的邮件策略和合规性功能。
ms.openlocfilehash: 9ff12288f0b0432878d920ce4fb4ceccc6075ab2
ms.sourcegitcommit: 19591e97b35c1b2a99e04a496d83af27dc6530d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/18/2019
ms.locfileid: "37581868"
---
# <a name="messaging-policy-and-compliance"></a><span data-ttu-id="31923-103">邮件策略和合规性</span><span class="sxs-lookup"><span data-stu-id="31923-103">Messaging policy and compliance</span></span>

<span data-ttu-id="31923-104">Microsoft Exchange Online Protection （EOP）提供了可帮助您管理电子邮件数据的邮件策略和合规性功能。</span><span class="sxs-lookup"><span data-stu-id="31923-104">Microsoft Exchange Online Protection (EOP) provides messaging policy and compliance features that can help you manage your email data.</span></span>

<span data-ttu-id="31923-105">要查找有关 EOP 所有功能的信息吗？</span><span class="sxs-lookup"><span data-stu-id="31923-105">Looking for information about all EOP features?</span></span> <span data-ttu-id="31923-106">请参阅 [Exchange Online Protection 服务说明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="31923-106">See the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>

## <a name="mail-flow-rules"></a><span data-ttu-id="31923-107">邮件流规则</span><span class="sxs-lookup"><span data-stu-id="31923-107">Mail flow rules</span></span>

<span data-ttu-id="31923-108">邮件流规则（也称为传输规则）为您提供了将自己的特定于公司的策略应用于电子邮件的灵活性。</span><span class="sxs-lookup"><span data-stu-id="31923-108">Mail flow rules (also known as transport rules) provide you with the flexibility to apply your own company-specific policies to email.</span></span> <span data-ttu-id="31923-109">邮件流规则由灵活的条件组成，使您可以根据条件定义条件、例外和要采取的操作。</span><span class="sxs-lookup"><span data-stu-id="31923-109">Mail flow rules are made up of flexible criteria, which allow you to define conditions, exceptions, and actions to take based on the criteria.</span></span> <span data-ttu-id="31923-110">有关详细信息，请参阅[Exchange Online Protection 中的邮件流规则（传输规则）](https://docs.microsoft.com/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0)。</span><span class="sxs-lookup"><span data-stu-id="31923-110">For more information, see [Mail flow rules (transport rules) in Exchange Online Protection](https://docs.microsoft.com/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0).</span></span>

## <a name="audit-logging"></a><span data-ttu-id="31923-111">审核日志记录</span><span class="sxs-lookup"><span data-stu-id="31923-111">Audit logging</span></span>

<span data-ttu-id="31923-112">使用审核日志记录，可以跟踪管理员对组织做出的特定更改。</span><span class="sxs-lookup"><span data-stu-id="31923-112">Audit logging lets you track specific changes made by administrators to your organization.</span></span> <span data-ttu-id="31923-113">这些报告可帮助你遵守法规、符合性和诉讼要求。</span><span class="sxs-lookup"><span data-stu-id="31923-113">These reports help you meet regulatory, compliance, and litigation requirements.</span></span> <span data-ttu-id="31923-114">有关详细信息，请参阅[EOP 中的审核报告](https://docs.microsoft.com/microsoft-365/security/office-365-security/auditing-reports-in-eop)。</span><span class="sxs-lookup"><span data-stu-id="31923-114">For more information, see [Auditing reports in EOP](https://docs.microsoft.com/microsoft-365/security/office-365-security/auditing-reports-in-eop).</span></span>

## <a name="data-loss-prevention-dlp"></a><span data-ttu-id="31923-115">数据丢失防护 (DLP)</span><span class="sxs-lookup"><span data-stu-id="31923-115">Data loss prevention (DLP)</span></span>

<span data-ttu-id="31923-116">对独立 EOP 客户不可用。</span><span class="sxs-lookup"><span data-stu-id="31923-116">Not available to EOP standalone customers.</span></span> <span data-ttu-id="31923-117">数据丢失防护 (DLP) 可进行深入内容分析，帮助识别、监视和保护您组织中的敏感信息。</span><span class="sxs-lookup"><span data-stu-id="31923-117">Data loss prevention (DLP) helps you identify, monitor, and protect sensitive information in your organization through deep content analysis.</span></span> <span data-ttu-id="31923-118">DLP 对于企业邮件系统而言越来越重要，因为对于企业非常重要的电子邮件包含需要保护的敏感信息。</span><span class="sxs-lookup"><span data-stu-id="31923-118">DLP is increasingly important for enterprise message systems because business-critical email includes sensitive data that needs to be protected.</span></span> <span data-ttu-id="31923-119">DLP 功能可让您保护敏感数据，而不会影响工作人员的工作效率。</span><span class="sxs-lookup"><span data-stu-id="31923-119">The DLP feature lets you protect sensitive data without affecting worker productivity.</span></span>

<span data-ttu-id="31923-120">您可以在 EAC 中配置 DLP 策略，从而能够：</span><span class="sxs-lookup"><span data-stu-id="31923-120">You can configure DLP policies in the EAC, which allows you to:</span></span>

- <span data-ttu-id="31923-121">启动预配置的策略模板，此模板可帮助您检测特定类型的敏感信息，如 PCI-DSS 数据、格雷姆-里奇-比利雷法案数据，甚至是区域设置特定的个人身份信息 (PII)。</span><span class="sxs-lookup"><span data-stu-id="31923-121">Start with a pre-configured policy template that can help you detect specific types of sensitive information such as PCI-DSS data, Gramm-Leach-Bliley act data, or even locale-specific personally identifiable information (PII).</span></span>

- <span data-ttu-id="31923-122">使用现有的邮件流规则条件和操作的完整功能，并添加新的邮件流规则。</span><span class="sxs-lookup"><span data-stu-id="31923-122">Use the full power of existing mail flow rule criteria and actions and add new mail flow rules.</span></span>

- <span data-ttu-id="31923-123">在全面执行前，测试您的 DLP 策略的有效性。</span><span class="sxs-lookup"><span data-stu-id="31923-123">Test the effectiveness of your DLP policies before fully enforcing them.</span></span>

- <span data-ttu-id="31923-124">整合您自己的自定义 DLP 策略模板和敏感的信息类型。</span><span class="sxs-lookup"><span data-stu-id="31923-124">Incorporate your own custom DLP policy templates and sensitive information types.</span></span>

- <span data-ttu-id="31923-125">检测邮件附件、正文文本或主题行中的敏感信息，然后调整该服务采取措施的置信度水平。</span><span class="sxs-lookup"><span data-stu-id="31923-125">Detect sensitive information in message attachments, body text, or subject lines and adjust the confidence level at which the service takes action.</span></span>

- <span data-ttu-id="31923-126">通过使用文档指纹检测敏感型数据。</span><span class="sxs-lookup"><span data-stu-id="31923-126">Detect sensitive form data by using Document Fingerprinting.</span></span> <span data-ttu-id="31923-127">文档指纹可帮助您根据可用于定义邮件流规则和 DLP 策略的基于文本的表单，轻松创建自定义敏感信息类型。</span><span class="sxs-lookup"><span data-stu-id="31923-127">Document Fingerprinting helps you easily create custom sensitive information types based on text-based forms that you can use to define mail flow rules and DLP policies.</span></span>

- <span data-ttu-id="31923-128">添加策略提示，通过将通知显示在 Outlook 2013、Outlook 网页版和适用于设备的 OWA 的用户中，可以帮助减少数据丢失，还可以通过允许误报报告来提高策略的有效性。</span><span class="sxs-lookup"><span data-stu-id="31923-128">Add Policy Tips, which can help reduce data loss by displaying a notice to your Outlook 2013, Outlook on the web, and OWA for Devices users and can also improve the effectiveness of your policies by allowing false-positive reporting.</span></span>

- <span data-ttu-id="31923-129">查看 DLP 报告中的事件数据，或通过使用生成事件报告操作来添加自己的特定报告。</span><span class="sxs-lookup"><span data-stu-id="31923-129">Review incident data in DLP reports or add your own specific reports by using a generate incident report action.</span></span>

> [!NOTE]
> <span data-ttu-id="31923-p106">DLP 策略仅适用于传进或传出组织的邮件。组织内（内部）邮件没有适用的 DLP 策略，除非您运行包含本地 DLP 的 Exchange Server 2013。这还适用于 DLP 策略提示，可以在敏感数据被错误发送到未经授权收件人之前通知用户潜在的策略违反。</span><span class="sxs-lookup"><span data-stu-id="31923-p106">DLP policies are applied only to mail that passes in or out of the organization. Intra-organizational (internal) mail does not have DLP policies applied unless you run Exchange Server 2013 with DLP on-premises. This also applies to DLP policy tips, which inform users about potential policy violations before sensitive data is mistakenly sent to unauthorized recipients.</span></span>

<span data-ttu-id="31923-133">若要了解有关 DLP 的详细信息，请参阅[Exchange Online 中的数据丢失防护](https://docs.microsoft.com/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention)。</span><span class="sxs-lookup"><span data-stu-id="31923-133">To learn more about DLP, see [Data loss prevention in Exchange Online](https://docs.microsoft.com/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention).</span></span>

## <a name="office-365-message-encryption"></a><span data-ttu-id="31923-134">Office 365 邮件加密</span><span class="sxs-lookup"><span data-stu-id="31923-134">Office 365 Message Encryption</span></span>

<span data-ttu-id="31923-135">Office 365 邮件加密是 Azure 信息保护的一部分，它是一种在线服务，它允许电子邮件用户将加密的电子邮件发送给任何人。</span><span class="sxs-lookup"><span data-stu-id="31923-135">Office 365 Message Encryption, a part of Azure Information Protection, is an online service that allows email users to send encrypted email messages to anyone.</span></span> <span data-ttu-id="31923-136">本地客户可以通过购买 Azure 信息保护并使用 Exchange Online Protection 设置通过 Exchange Online 的邮件流，来访问 Office 365 邮件加密。</span><span class="sxs-lookup"><span data-stu-id="31923-136">On-premises customers can access Office 365 Message Encryption by purchasing Azure Information Protection and using Exchange Online Protection to set up mail flow through Exchange Online.</span></span> <span data-ttu-id="31923-137">有关 Exchange Online 中的 Office 365 邮件加密的详细信息，请参阅 [Exchange Online 服务说明中的 Office 365 Message Encryption](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption)。</span><span class="sxs-lookup"><span data-stu-id="31923-137">To learn more about Office 365 Message Encryption in Exchange Online, see [Office 365 Message Encryption](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption) in the Exchange Online Service Description.</span></span>

## <a name="messaging-policy-and-compliance-features-across-eop-options"></a><span data-ttu-id="31923-138">跨 EOP 选项的邮件策略和合规性功能</span><span class="sxs-lookup"><span data-stu-id="31923-138">Messaging policy and compliance features across EOP options</span></span>

|<span data-ttu-id="31923-139">**功能**</span><span class="sxs-lookup"><span data-stu-id="31923-139">**Feature**</span></span>|<span data-ttu-id="31923-140">**独立 EOP**</span><span class="sxs-lookup"><span data-stu-id="31923-140">**EOP standalone**</span></span>|<span data-ttu-id="31923-141">**Exchange Online 中<br/>的 EOP 功能**</span><span class="sxs-lookup"><span data-stu-id="31923-141">**EOP features in <br/> Exchange Online**</span></span>|<span data-ttu-id="31923-142">**Exchange Enterprise <br/> CAL with Services**</span><span class="sxs-lookup"><span data-stu-id="31923-142">**Exchange Enterprise <br/> CAL with Services**</span></span>|
|:-----|:-----|:-----|:-----|
|<span data-ttu-id="31923-143">邮件流规则</span><span class="sxs-lookup"><span data-stu-id="31923-143">Mail flow rules</span></span>|<span data-ttu-id="31923-144">是<sup>1</sup></span><span class="sxs-lookup"><span data-stu-id="31923-144">Yes<sup>1</sup></span></span>|<span data-ttu-id="31923-145">是<sup>1</sup></span><span class="sxs-lookup"><span data-stu-id="31923-145">Yes<sup>1</sup></span></span>|<span data-ttu-id="31923-146">是<sup>1、3</sup></span><span class="sxs-lookup"><span data-stu-id="31923-146">Yes<sup>1, 3</sup></span></span>|
|<span data-ttu-id="31923-147">审核日志记录</span><span class="sxs-lookup"><span data-stu-id="31923-147">Audit logging</span></span>|<span data-ttu-id="31923-148">是<sup>2</sup></span><span class="sxs-lookup"><span data-stu-id="31923-148">Yes<sup>2</sup></span></span>|<span data-ttu-id="31923-149">可访问</span><span class="sxs-lookup"><span data-stu-id="31923-149">Yes</span></span>|<span data-ttu-id="31923-150">可访问</span><span class="sxs-lookup"><span data-stu-id="31923-150">Yes</span></span>|
|<span data-ttu-id="31923-151">数据丢失防护 (DLP)</span><span class="sxs-lookup"><span data-stu-id="31923-151">Data loss prevention (DLP)</span></span>|<span data-ttu-id="31923-152">否</span><span class="sxs-lookup"><span data-stu-id="31923-152">No</span></span>|<span data-ttu-id="31923-153">可访问</span><span class="sxs-lookup"><span data-stu-id="31923-153">Yes</span></span>|<span data-ttu-id="31923-154">是<sup>3</sup></span><span class="sxs-lookup"><span data-stu-id="31923-154">Yes<sup>3</sup></span></span>|
|<span data-ttu-id="31923-155">Office 365 邮件加密</span><span class="sxs-lookup"><span data-stu-id="31923-155">Office 365 Message Encryption</span></span>|<span data-ttu-id="31923-156">是<sup>4</sup></span><span class="sxs-lookup"><span data-stu-id="31923-156">Yes<sup>4</sup></span></span>|<span data-ttu-id="31923-157">是</span><span class="sxs-lookup"><span data-stu-id="31923-157">Yes</span></span>|<span data-ttu-id="31923-158">是<sup>4</sup></span><span class="sxs-lookup"><span data-stu-id="31923-158">Yes<sup>4</sup></span></span>|

> [!NOTE]
> <span data-ttu-id="31923-159"><sup>1</sup> EOP 和 Exchange Online 之间的可用邮件流规则条件、例外和操作略有不同。</span><span class="sxs-lookup"><span data-stu-id="31923-159"><sup>1</sup> The available mail flow rule conditions, exceptions, and actions differ slightly between EOP and Exchange Online.</span></span> <span data-ttu-id="31923-160">这些差异在 exchange online 中的[邮件流规则条件和例外（谓词）](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions)中注明， [exchange Online 中的邮件流规则操作](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions)。</span><span class="sxs-lookup"><span data-stu-id="31923-160">These differences are noted in [Mail flow rule conditions and exceptions (predicates) in Exchange Online](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions) and [Mail flow rule actions in Exchange Online](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions).</span></span> <br/>
> <span data-ttu-id="31923-161"><sup>2</sup> EOP 审核报告是部分不包括邮箱信息的 Exchange Online 审核报告。</span><span class="sxs-lookup"><span data-stu-id="31923-161"><sup>2</sup> EOP auditing reports are a subset of Exchange Online auditing reports that exclude information about mailboxes.</span></span> <br/>
> <span data-ttu-id="31923-162"><sup>3</sup> DLP 策略提示不适用于 Exchange Enterprise CAL with Services 客户。</span><span class="sxs-lookup"><span data-stu-id="31923-162"><sup>3</sup> DLP policy tips are not available for Exchange Enterprise CAL with Services customers.</span></span> <br/>
> <span data-ttu-id="31923-163"><sup>4</sup>支持购买 Azure 信息保护加载项并使用 Exchange online Protection 通过 exchange online 路由电子邮件的本地客户。</span><span class="sxs-lookup"><span data-stu-id="31923-163"><sup>4</sup> Supported for on-premises customers who purchase the Azure Information Protection add-on and use Exchange Online Protection to route email through Exchange Online.</span></span> <span data-ttu-id="31923-164">对于桌面体验，除了 Azure 信息保护加载项外，还需要购买 Office 365 专业增强版。</span><span class="sxs-lookup"><span data-stu-id="31923-164">For the desktop experience, in addition to the Azure Information Protection add-on, Office 365 ProPlus needs to be purchased.</span></span> <br/>
