---
title: Exchange Online Protection 中的邮件策略和合规性
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: 阅读本文，了解 Microsoft Exchange Online Protection (EOP) 中的邮件策略和合规性) 。
ms.openlocfilehash: a1ed14ed555adb17801014141a3f66616e17d2e1
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173727"
---
# <a name="messaging-policy-and-compliance-in-exchange-online-protection"></a>Exchange Online Protection 中的邮件策略和合规性

Microsoft Exchange Online Protection (EOP) 提供了可帮助您管理电子邮件数据的邮件策略和合规性功能。

要查找有关 EOP 所有功能的信息吗？ 请参阅 [Exchange Online Protection 服务说明](exchange-online-protection-service-description.md)。

## <a name="mail-flow-rules"></a>邮件流规则

邮件流规则 (传输规则) 传输规则）使你可以灵活地将自己的公司特定策略应用于电子邮件。 邮件流规则由灵活的条件所决定，这允许您定义条件、例外和基于条件要采取的操作。 有关详细信息，请参阅 Mail [flow rules (transport rules) in Exchange Online Protection](/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0)。

## <a name="audit-logging"></a>审核日志记录

使用审核日志记录，可以跟踪管理员对组织做出的特定更改。 这些报告可帮助你遵守法规、符合性和诉讼要求。 有关详细信息，请参阅[EOP 中的审核报告](/microsoft-365/security/office-365-security/auditing-reports-in-eop)。

## <a name="data-loss-prevention-dlp"></a>数据丢失防护 (DLP)

对独立 EOP 客户不可用。 数据丢失防护 (DLP) 可进行深入内容分析，帮助识别、监视和保护您组织中的敏感信息。 DLP 对于企业邮件系统而言越来越重要，因为对于企业非常重要的电子邮件包含需要保护的敏感信息。 利用 DLP 功能，您可以保护敏感数据，而不会影响工作者的工作效率。

您可以在 EAC 中配置 DLP 策略，从而能够：

- 启动预配置的策略模板，此模板可帮助您检测特定类型的敏感信息，如 PCI-DSS 数据、格雷姆-里奇-比利雷法案数据，甚至是区域设置特定的个人身份信息 (PII)。

- 使用现有邮件流规则标准和操作的全部功能，并添加新的邮件流规则。

- 在全面执行前，测试您的 DLP 策略的有效性。

- 整合您自己的自定义 DLP 策略模板和敏感的信息类型。

- 检测邮件附件、正文文本或主题行中的敏感信息，然后调整该服务采取措施的置信度水平。

- 通过使用文档指纹检测敏感型数据。 文档指纹可帮助您根据可用于定义邮件流规则和 DLP 策略的基于文本的表单轻松创建自定义敏感信息类型。

- 添加策略提示，通过向 Outlook 2013、Outlook 网页版和适用于设备的 OWA 用户显示通知，可帮助减少数据丢失，还可通过允许误报报告来提高策略的有效性。

- 查看 DLP 报告中的事件数据，或通过使用生成事件报告操作来添加自己的特定报告。

> [!NOTE]
> DLP 策略仅适用于传进或传出组织的邮件。组织内（内部）邮件没有适用的 DLP 策略，除非您运行包含本地 DLP 的 Exchange Server 2013。这还适用于 DLP 策略提示，可以在敏感数据被错误发送到未经授权收件人之前通知用户潜在的策略违反。

若要了解有关 DLP 的更多信息，请参阅 [Exchange Online 中的数据丢失防护](/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention)。

## <a name="office-365-message-encryption"></a>Office 365 邮件加密

Office 365 邮件加密是 Azure 信息保护的一部分，是允许电子邮件用户向任何人发送加密电子邮件的联机服务。 本地客户可以通过购买 Azure 信息保护和使用 Exchange Online Protection 设置通过 Exchange Online 的邮件流来访问 Office 365 邮件加密。 若要详细了解 Exchange Online 中的 Office 365 邮件加密，请参阅 Exchange Online 服务说明中的 [Office 365](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption) 邮件加密。

## <a name="messaging-policy-and-compliance-features-across-eop-options"></a>跨 EOP 选项的邮件策略和合规性功能

| 功能 | 独立 EOP | 中的 EOP 功能 <br/> Exchange Online | Exchange Enterprise <br/> CAL with Services |
|:-----|:-----|:-----|:-----|
|邮件流规则|是<sup>1</sup>|是<sup>1</sup>|是<sup>1、3</sup>|
|审核日志记录|是<sup>2</sup>|是|是|
|数据丢失防护 (DLP)|否|是|是<sup>3</sup>|
|Office 365 邮件加密|是<sup>4</sup>|是|是<sup>4</sup>|

> [!NOTE]
> <sup>1</sup> EOP 和 Exchange Online 之间的可用邮件流规则条件、例外和操作略有不同。 有关这些区别，请参阅 [Exchange Online 中的邮件流规则条件和异常（谓词）](/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions)和 [Exchange Online 中的邮件流规则](/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions)。 <br/>
> <sup>2</sup> EOP 审核报告是部分不包括邮箱信息的 Exchange Online 审核报告。 <br/>
> <sup>3</sup> DLP 策略提示不适用于 Exchange Enterprise CAL with Services 客户。 <br/>
> <sup>4</sup> 支持购买 Azure 信息保护加载项并使用 Exchange Online Protection 通过 Exchange Online 路由电子邮件的本地客户。 对于桌面体验，除了 Azure 信息保护加载项外，还需要购买 Microsoft 365 企业应用版。 <br/>