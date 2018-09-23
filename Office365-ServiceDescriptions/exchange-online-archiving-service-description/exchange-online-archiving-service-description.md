---
title: Exchange Online Archiving 服务说明
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-archiving-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 21ebd4bb-7d88-489f-a8aa-376e2536900c
description: Microsoft Exchange Online Archiving 是 Microsoft Office 365 基于云的企业级存档的解决方案已部署 Microsoft Exchange Server 2013，Microsoft Exchange Server 2010 的组织 (SP2 和更高版本)，或订阅某些Exchange Online 或 Office 365 计划。Exchange Online Archiving 帮助与其存档，合规性、 法规，这些组织和电子数据展示在简化内部部署基础结构，从而降低成本和减轻了 IT 负担挑战。
ms.openlocfilehash: d88d336f0e5b30a245b6c90c7cc488ca6d5dfc54
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035040"
---
# <a name="exchange-online-archiving-service-description"></a>Exchange Online Archiving 服务说明

Microsoft Exchange Online Archiving 是 Microsoft Office 365 基于云的企业级存档的解决方案已部署 Microsoft Exchange Server 2013，Microsoft Exchange Server 2010 的组织 (SP2 和更高版本)，或订阅某些Exchange Online 或 Office 365 计划。Exchange Online Archiving 帮助与其存档，合规性、 法规，这些组织和电子数据展示在简化内部部署基础结构，从而降低成本和减轻了 IT 负担挑战。
  
作为一种 Microsoft Office 365 在线服务，Exchange Online Archiving 旨在满足强安全性、可靠性和用户工作效率需求。有关 Office 365（包括所有 Office 365 在线服务的常见功能）的详细信息，请参阅 [Office 365 平台服务说明](../office-365-platform-service-description/office-365-platform-service-description.md)。
  
若要购买 Exchange Online Archiving，请参阅 [Exchange Online Archiving](https://go.microsoft.com/fwlink/p/?LinkId=314176)。
  
若要跨计划比较功能，请参阅[比较 Office 365 商业版计划](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409)。
  
> [!TIP]
> 您可以导出、保存以及打印 Office 365 服务说明中的页面。了解如何[导出多个页面](https://go.microsoft.com/fwlink/?LinkId=403349)。 
  
## <a name="exchange-online-archiving-plans"></a>Exchange Online Archiving 计划
<a name="bkmk_EOA_Plans"> </a>

可通过以下计划使用 Exchange Online Archiving。
  
|**计划**|**描述**|
|:-----|:-----|
|**适用于 Exchange Server 的 Exchange Online Archiving** <br/> |基于云的存档，适用于在 Exchange Server 2013 或 Exchange 2010（SP2 或更高版本）中拥有主邮箱的用户。  <br/> 如果想要将基于云的存档添加到位于本地 Exchange 服务器上的主邮箱，则需要配置混合部署。有关混合部署的详细信息，请参阅 [Exchange Server 混合部署](https://technet.microsoft.com/library/jj200581%28v=exchg.150%29.aspx)。  <br/> |
|**适用于 Exchange Server 的 Exchange Online Archiving（通过 Enterprise CAL Suite）** <br/> |基于云的存档，适用于在 Exchange Server 2013 或 Exchange 2010（SP2 或更高版本）中拥有主邮箱的用户。有关详细信息，请参阅 [授权简介 - 授权 Core CAL Suite 和 Enterprise CAL Suite](https://go.microsoft.com/fwlink/p/?LinkId=314160)。  <br/> |
|**适用于 Exchange Online 的 Exchange Online Archiving** <br/> | 基于云的存档和就地保留作为以下计划的附加内容： <sup>1、2</sup>  <br/>  Exchange Online 计划 1  <br/>  Exchange Online Kiosk  <br/>  Office 365 商业协作版  <br/>  Help and training  <br/>  Office 365 企业版 E1  <br/>  Office 365 企业版 F1  <br/> > [!NOTE]> 以下计划已包含存档，因此不要求 Exchange Online Archiving 作为： > Office 365 教育版 A1 > Office 365 教育版 A3 > Office 365 教育版 A5 > Office 365 企业版 E3 > Office 365 企业 E5 > Exchange Online 计划 2 > Exchange Online 邮箱的存档功能的详细信息，请参阅[联机在 Exchange 存档邮箱](https://go.microsoft.com/fwlink/p/?LinkId=404421)。           |
   
> [!NOTE]
> <sup>1</sup> 仅使用云的组织无需混合部署，此类组织的 Exchange 本地服务器上没有邮箱。但是，如果存在本地邮箱，则需要配置混合部署。 > <sup>2</sup> Exchange Online 计划 1 和 Office 365 商业版计划具有 [邮箱和存档大小限制](https://go.microsoft.com/fwlink/?LinkId=330039)。Exchange Online Archiving for Exchange Online 附加项可提供无限制且基于云的存档和[就地保留和诉讼保留](compliance-and-security-features.md#in-place-hold-and-litigation-hold)功能。 
  
寻找有关所有 Office 365 计划的信息？Office 365 推出了各种计划，旨在最大限度地满足组织需求。若要了解不同计划（包括独立计划选项），以及如何从一个计划迁移到另一个计划，请参阅 [Office 365 计划选项](../office-365-platform-service-description/office-365-plan-options.md)。
  
## <a name="requirements"></a>要求
<a name="bkmk_EOA_Plans"> </a>

若要使用 Exchange Server 的 Exchange Online Archiving，用户邮箱必须位于 Exchange Server 2013 或 Exchange Server 2010（SP2 或更高版本）上。
  
### <a name="federated-identity-and-single-sign-on"></a>联合身份和单一登录

管理员可以使用单一登录方法完成本地 Active Directory 的 Office 365 身份验证。为此，管理员可以配置本地 Active Directory 联合身份验证服务（一项 Microsoft Windows Server® 2008 服务）与 Microsoft Federation Gateway 进行联合。在 Active Directory 联合身份验证服务配置完成后，身份基于联盟域的所有 Office 365 用户都可以使用现有的公司登录信息自动完成 Office 365 的身份验证。
  
### <a name="user-subscriptions"></a>用户订阅

访问 Exchange Online Archiving 服务的每个用户都必须拥有一个 Exchange Online Archiving 订阅。每个电子邮件存档订阅只能用于存储一名用户的邮件数据。
  
## <a name="unlimited-archive-storage-quota"></a>无限制存档存储配额
<a name="bkmk_EOA_Plans"> </a>

 Office 365 中的无限制存档功能（称为" 自动扩展存档"）为存档邮箱提供无限量存储空间。每个 Exchange Online Archiving 订阅者最初都会获得 100 GB 的存档邮箱存储空间。启用自动扩展存档后，只要达到 100 GB 存储容量，就会自动添加额外存储空间。有关详细信息，请参阅 [Office 365 中的无限制存档概述](https://go.microsoft.com/fwlink/?linkid=844060)。有关可用性的详细信息，请参阅 [Office 365 路线图](http://go.microsoft.com/fwlink/?LinkId=509914)。 
  
> [!IMPORTANT]
> 管理员无法调整存储配额。 
  
> [!IMPORTANT]
> 不允许使用日记、传输规则或自动转发规则将邮件复制到 Exchange Online Archiving 中来进行存档。用户的存档邮箱只供该用户使用。Microsoft 保留拒绝在用户存档邮箱用于存储其他用户存档数据的情况下进行无限制存档的权利。 
  
## <a name="feature-availability-across-exchange-online-archiving-plans"></a>跨 Exchange Online Archiving 计划的功能可用性
<a name="bkmk_EOA_Plans"> </a>

||||
|:-----|:-----|:-----|
|**功能** <br/> |**Exchange Online Archiving for Exchange Server<sup>1</sup>**          <br/> |**Exchange Online Archiving for Exchange Online<sup>2</sup>** <br/> |
|**[Exchange Online Archiving 中的存档功能](archive-features.md)** <br/> |||
|存档邮箱  <br/> |是  <br/> |是  <br/> |
|使用存档策略移动邮件  <br/> |是  <br/> |是  <br/> |
|将数据导入到存档  <br/> |是  <br/> |是  <br/> |
|已删除邮件的恢复  <br/> |是  <br/> |是  <br/> |
|已删除邮箱的恢复  <br/> |是  <br/> |是  <br/> |
|邮箱备份  <br/> |是  <br/> |是  <br/> |
|**[Exchange Online Archiving 中的客户端功能](client-features.md)** <br/> |||
|Outlook<sup>3</sup> <br/> |是  <br/> |是  <br/> |
|Outlook Web App  <br/> |是  <br/> |是  <br/> |
|**[Exchange Online Archiving 中的合规性功能和安全功能](compliance-and-security-features.md)** <br/> |||
|保留策略  <br/> |是  <br/> |是  <br/> |
|就地保留和诉讼保留<sup>6</sup> <br/> |是  <br/> |是  <br/> |
|就地电子数据展示  <br/> |是  <br/> |是  <br/> |
|在本地服务器和 Exchange Online Archiving 之间加密  <br/> |是  <br/> |是  <br/> |
|在客户端和 Exchange Online Archiving 之间加密  <br/> |是  <br/> |是  <br/> |
|加密：S/MIME 和 PGP  <br/> |是  <br/> |是  <br/> |
|使用 Azure 信息保护的 IRM  <br/> |否  <br/> |没有<sup>4</sup> <br/> |
|使用 Windows Server AD RMS 的 IRM  <br/> |是<sup>5</sup> <br/> |是<sup>5</sup> <br/> |
|审核  <br/> |是  <br/> |是  <br/> |
   

> <sup>1</sup>用户邮箱必须位于 Exchange 2010 SP2 或更高版本上。
 <br/><sup>2</sup>就地存档可仅用于存档的单个用户或已为其应用许可证的实体的邮件。作为一种方法使用就地存档存储来自多个用户或实体的邮件已被禁止。例如，IT 管理员不能创建共享的邮箱，并让用户将复制 （通过抄送或密件抄送字段中，或通过传输规则） 共享的邮箱的存档的显式目的。 <br/> <sup>3</sup>受支持的 Microsoft Outlook 版本的列表，请参阅[Exchange Online Archiving 中的客户端功能](client-features.md)。 
 <br/><sup>4</sup> azure 信息保护不包括在内，但可以作为单独的附加项购买，将启用受支持的信息权限管理 (IRM) 功能。某些 Azure 信息保护功能需要订阅 Office 365 ProPlus，后者不包含 Office 365 业务 Essentials、 Office 365 企业高级版、 Office 365 企业版 E1、 Office 365 教育或 Office 365 企业 F1。 <br/><sup>5</sup> Windows Server AD RMS 是一款本地服务器，必须单独购买并管理，才能启用支持的 IRM 功能。 
 <br/><sup>6</sup> 当您将邮箱置于就地保留或诉讼保留中时，该保留将置于主邮箱和存档邮箱中。 