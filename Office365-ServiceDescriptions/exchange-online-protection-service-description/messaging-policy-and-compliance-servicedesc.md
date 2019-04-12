---
title: 邮件策略和合规性
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 04/10/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: Microsoft Exchange Online Protection (EOP) 提供了可帮助您管理电子邮件数据的邮件策略和合规性功能。
ms.openlocfilehash: a37ad3c1bcecb73f7c903b553bdcb43935dc9ed7
ms.sourcegitcommit: 7248888900104d79c5f53cafb1000140eefac7eb
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/12/2019
ms.locfileid: "31825180"
---
# <a name="messaging-policy-and-compliance"></a>邮件策略和合规性

Microsoft Exchange Online Protection (EOP) 提供了可帮助您管理电子邮件数据的邮件策略和合规性功能。
  
要查找有关 EOP 所有功能的信息吗？ 请参阅 [Exchange Online Protection 服务说明](exchange-online-protection-service-description.md)。
  
## <a name="transport-rules"></a>传输规则
<a name="BKMK_transportrules"> </a>

使用传输规则，可以灵活地向电子邮件应用你自己的公司专属策略。传输规则由灵活条件构成，可方便你根据条件定义条件、异常和要采取的措施。若要详细了解 EOP 中的传输规则，请参阅[传输规则](https://go.microsoft.com/fwlink/p/?LinkId=320399)。
  
## <a name="audit-logging"></a>审核日志记录
<a name="BKMK_auditlogging"> </a>

使用审核日志记录，可以跟踪管理员对组织做出的特定更改。这些报告可帮助你遵守法规、符合性和诉讼要求。有关详细信息，请参阅 [EOP 中的审核报告](https://go.microsoft.com/fwlink/p/?LinkId=314258)。
  
## <a name="data-loss-prevention-dlp"></a>数据丢失防护 (DLP)
<a name="BKMK_datalossprevention"> </a>

对独立 EOP 客户不可用。数据丢失防护 (DLP) 可进行深入内容分析，帮助识别、监视和保护您组织中的敏感信息。DLP 对于企业邮件系统而言越来越重要，因为对于企业非常重要的电子邮件包含需要保护的敏感信息。DLP 功能可让您保护敏感数据，而不会影响工作人员的生产率。
  
您可以在 EAC 中配置 DLP 策略，从而能够：
  
- 启动预配置的策略模板，此模板可帮助您检测特定类型的敏感信息，如 PCI-DSS 数据、格雷姆-里奇-比利雷法案数据，甚至是区域设置特定的个人身份信息 (PII)。
    
- 使用现有传输规则条件和操作的强大功能，并添加新的传输规则。
    
- 在全面执行前，测试您的 DLP 策略的有效性。
    
- 整合您自己的自定义 DLP 策略模板和敏感的信息类型。
    
- 检测邮件附件、正文文本或主题行中的敏感信息，然后调整该服务采取措施的置信度水平。
    
- 通过使用文档指纹检测敏感型数据。文档指纹可以帮助您基于文本形式（您可以用其定义传输规则和 DLP 策略）轻松地创建自定义敏感信息类型。
    
- 添加策略提示，它可通过向 Outlook 2013、Outlook Web App 和适用于设备的 OWA 的用户显示通知来帮助减少数据丢失，还可以通过允许误报报告来提高策略的有效性。
    
- 查看 DLP 报告中的事件数据，或通过使用生成事件报告操作来添加自己的特定报告。
    
> [!NOTE]
> DLP 策略仅适用于传进或传出组织的邮件。组织内（内部）邮件没有适用的 DLP 策略，除非您运行包含本地 DLP 的 Exchange Server 2013。这还适用于 DLP 策略提示，可以在敏感数据被错误发送到未经授权收件人之前通知用户潜在的策略违反。 
  
若要详细了解 DLP，请参阅[数据丢失防护](https://go.microsoft.com/fwlink/p/?LinkId=320398)。
  
## <a name="office-365-message-encryption"></a>Office 365 邮件加密
<a name="BKMK_OME_in_EOP"> </a>

Office 365 邮件加密是 Azure 信息保护的一部分, 它是一种在线服务, 它允许电子邮件用户将加密的电子邮件发送给任何人。 本地客户可以通过购买 Azure 信息保护并使用 exchange online Protection 设置通过 exchange online 的邮件流, 来访问 Office 365 邮件加密。 有关 Exchange Online 中的 Office 365 邮件加密的详细信息，请参阅 [Exchange Online 服务说明中的 Office 365 Message Encryption](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption)。 
  
## <a name="messaging-policy-and-compliance-features-across-eop-options"></a>跨 EOP 选项的邮件策略和合规性功能
<a name="BKMK_OME_in_EOP"> </a>

|**功能**|**独立 EOP**|**Exchange Online 中的 EOP 功能**|**Exchange Enterprise CAL with Services**|
|:-----|:-----|:-----|:-----|
|传输规则  <br/> |是<sup>1</sup> <br/> |是<sup>1</sup> <br/> |可访问  <br/> |
|审核日志记录  <br/> |是<sup>2</sup> <br/> |可访问  <br/> |可访问  <br/> |
|数据丢失防护 (DLP)  <br/> |否  <br/> |是  <br/> |是<sup>3</sup> <br/> |
|Office 365 邮件加密  <br/> |是<sup>4</sup> <br/> |是  <br/> |是<sup>4</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> EOP 和 Exchange Online 的可用条件和操作不同。 若要获取 EOP 中可用条件和操作的列表，请参阅 [传输规则条件](https://go.microsoft.com/fwlink/p/?LinkId=320392)和[传输规则操作](https://go.microsoft.com/fwlink/p/?LinkId=320393)。 若要获取 Exchange Online 中可用条件和操作的列表，请参阅[传输规则条件](https://go.microsoft.com/fwlink/p/?LinkId=320394)和[传输规则操作](https://go.microsoft.com/fwlink/p/?LinkId=320395)。 <br/>
> <sup>2</sup> EOP 审核报告是部分不包括邮箱信息的 Exchange Online 审核报告。 <br/>
> <sup>3</sup> DLP 策略提示不适用于 Exchange Enterprise CAL with Services 客户。 <br/>
> <sup>4</sup>支持购买 Azure 信息保护加载项并使用 exchange online Protection 通过 exchange online 路由电子邮件的本地客户。 对于桌面体验, 除了 Azure 信息保护加载项外, 还需要购买 Office 365 专业增强版。 <br/>
  

