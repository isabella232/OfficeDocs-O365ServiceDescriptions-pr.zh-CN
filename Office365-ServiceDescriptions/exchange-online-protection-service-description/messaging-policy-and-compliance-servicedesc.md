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
# <a name="messaging-policy-and-complianceservicedesc"></a>邮件策略和合规性[ServiceDesc]

Microsoft Exchange Online Protection (EOP) 提供邮件策略和合规性功能，可帮助您管理电子邮件数据。
  
想了解 EOP 的所有功能？请参阅 [Exchange Online Protection 服务说明](exchange-online-protection-service-description.md)。
  
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

Office 365 邮件加密，一部分 Azure 信息保护，是允许任何人发送加密的电子邮件的电子邮件用户的联机服务。本地客户可以通过购买 Azure 信息保护和使用 Exchange Online Protection 设置邮件流通过 Exchange Online 中访问 Office 365 邮件加密。若要详细了解 Office 365 邮件加密在 Exchange Online，请参阅 Exchange Online Service Description 中的[Office 365 邮件加密](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption)。 
  
## <a name="messaging-policy-and-compliance-features-across-eop-options"></a>跨 EOP 选项的邮件策略和合规性功能
<a name="BKMK_OME_in_EOP"> </a>

|**功能**|**独立 EOP**|**Exchange Online 中的 EOP 功能**|**Exchange Enterprise CAL with Services**|
|:-----|:-----|:-----|:-----|
|传输规则  <br/> |是<sup>1</sup> <br/> |是<sup>1</sup> <br/> |是  <br/> |
|审核日志记录  <br/> |是<sup>2</sup> <br/> |是  <br/> |是  <br/> |
|数据丢失防护 (DLP)  <br/> |否  <br/> |是  <br/> |是<sup>3</sup> <br/> |
|Office 365 邮件加密  <br/> |是<sup>4</sup> <br/> |是  <br/> |是<sup>4</sup> <br/> |
   
> [!NOTE]
> EOP 和 Exchange Online 之间不同<sup>1</sup>的可用条件和操作。有关可用条件和操作在 EOP 中的列表，请参阅[传输规则条件](https://go.microsoft.com/fwlink/p/?LinkId=320392)和[Transport Rule Actions](https://go.microsoft.com/fwlink/p/?LinkId=320393)。有关可用条件和操作 Exchange Online 中的列表，请参阅[传输规则条件](https://go.microsoft.com/fwlink/p/?LinkId=320394)和[Transport Rule Actions](https://go.microsoft.com/fwlink/p/?LinkId=320395)。> <sup>2</sup> EOP 审核报告的子集 Exchange Online 审核不包括邮箱信息的报告。> <sup>3</sup> DLP 策略提示不可用于 Exchange Enterprise CAL with Services 客户。> <sup>4</sup>受支持的本地客户购买的 Azure 信息保护加载项并通过 Exchange Online 路由电子邮件中使用 Exchange Online Protection。对于桌面体验，除了 Azure 信息保护加载项，Office 365 ProPlus 需要购买。 
  

