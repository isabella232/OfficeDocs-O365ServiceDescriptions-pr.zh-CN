---
title: Exchange Online Archiving 服务说明
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 02/14/2019
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
description: microsoft exchange Online 存档是 microsoft Office 365 基于云的企业级存档解决方案, 适用于已部署 microsoft exchange server 2016、microsoft exchange server 2013、microsoft exchange server 2010 (SP2 及更高版本) 的组织。), 或订阅特定的 Exchange Online 或 Office 365 计划。Exchange Online 存档在简化本地基础结构的同时帮助这些组织解决其存档、遵从性、法规和电子数据展示方面的难题, 从而降低成本并减轻 IT 负担。
ms.openlocfilehash: baf73ca4819f2970b3709cbce2f137483064e01a
ms.sourcegitcommit: e71991e4ababa6e0aa6d9df0979105e45646da2e
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 02/15/2019
ms.locfileid: "30056642"
---
# <a name="exchange-online-archiving-service-description"></a>Exchange Online Archiving 服务说明

microsoft exchange Online 存档是 microsoft Office 365 基于云的企业级存档解决方案, 适用于已部署 microsoft exchange server 2016、microsoft exchange server 2013、microsoft exchange server 2010 (SP2 及更高版本) 的组织。), 或订阅特定的 Exchange Online 或 Office 365 计划。Exchange Online 存档在简化本地基础结构的同时帮助这些组织解决其存档、遵从性、法规和电子数据展示方面的难题, 从而降低成本并减轻 IT 负担。
  
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
|**适用于 Exchange Server 的 Exchange Online Archiving** <br/> |在 exchange server 2016、exchange server 2013 或 exchange 2010 (SP2 或更高版本) 中具有主邮箱的用户的基于云的存档。  <br/> 如果想要将基于云的存档添加到位于本地 Exchange 服务器上的主邮箱，则需要配置混合部署。有关混合部署的详细信息，请参阅 [Exchange Server 混合部署](https://technet.microsoft.com/library/jj200581%28v=exchg.150%29.aspx)。  <br/> |
|**适用于 Exchange Server 的 Exchange Online Archiving（通过 Enterprise CAL Suite）** <br/> |在 exchange server 2016、exchange server 2013 或 exchange 2010 (SP2 或更高版本) 中具有主邮箱的用户的基于云的存档。有关详细信息, 请参阅[许可简述-许可核心 CAL 套件和企业 CAL 套件](https://go.microsoft.com/fwlink/p/?LinkId=314160)。<br/> |
|**适用于 Exchange Online 的 Exchange Online Archiving** <br/> | 基于云的存档和就地保留作为以下计划的附加内容： <sup>1、2</sup>  <br/>  Exchange Online 计划 1  <br/>  Exchange Online Kiosk  <br/>  Office 365 商业协作版  <br/>  Office 365 商业高级版  <br/>  Office 365 企业版 E1  <br/>  Office 365 企业版 F1  <br/>  <b>注意:</b>以下计划已包含存档, 不需要作为加载项的 Exchange Online 存档: > office 365 教育版 A1 > office 365 教育版 > Office 365 教育版 > > Office 365 企业版 E3 > office 365 Enterprise E5 Exchange online Plan 2 > 有关 Exchange online 邮箱的存档功能的详细信息, 请参阅[exchange online 中的存档邮箱](https://go.microsoft.com/fwlink/p/?LinkId=404421)。           |
   
> [!NOTE]
> <sup>1</sup>只有云的组织 (在本地 Exchange 服务器上没有邮箱) 不需要混合部署。但是, 如果存在本地邮箱, 则需要混合部署。<br/> <sup>2</sup> Exchange Online 计划1和 Office 365 商业版计划的[邮箱和存档大小限制](https://go.microsoft.com/fwlink/?LinkId=330039)。exchange online 存档 for exchange online 加载项添加了无限制的基于云的存档和[就地保留和诉讼保留](compliance-and-security-features.md#in-place-hold-and-litigation-hold)。
  
寻找有关所有 Office 365 计划的信息？Office 365 推出了各种计划，旨在最大限度地满足组织需求。若要了解不同计划（包括独立计划选项），以及如何从一个计划迁移到另一个计划，请参阅 [Office 365 计划选项](../office-365-platform-service-description/office-365-plan-options.md)。
  
## <a name="requirements"></a>要求
<a name="bkmk_EOA_Plans"> </a>

为了对 exchange server 使用 exchange Online 存档, 用户邮箱必须驻留在 exchange server 2016、exchange server 2013 或 exchange server 2010 (SP2 或更高版本) 上。
  
### <a name="federated-identity-and-single-sign-on"></a>联合身份和单一登录

管理员可以使用单一登录方法完成本地 Active Directory 的 Office 365 身份验证。为此，管理员可以配置本地 Active Directory 联合身份验证服务（一项 Microsoft Windows Server® 2008 服务）与 Microsoft Federation Gateway 进行联合。在 Active Directory 联合身份验证服务配置完成后，身份基于联盟域的所有 Office 365 用户都可以使用现有的公司登录信息自动完成 Office 365 的身份验证。
  
### <a name="user-subscriptions"></a>用户订阅

访问 Exchange Online Archiving 服务的每个用户都必须拥有一个 Exchange Online Archiving 订阅。每个电子邮件存档订阅只能用于存储一名用户的邮件数据。
  
## <a name="unlimited-archive-storage-quota"></a>无限制存档存储配额
<a name="bkmk_EOA_Plans"> </a>

 Office 365 中的无限制存档功能 (称为自动扩展存档) 在存档邮箱中提供了不受限制的存储量。仅当用户的邮箱驻留在 exchange server 2016 或 exchange server 2013 (SP1 或更高版本) 上时, 混合配置才支持自动扩展存档。每个 Exchange Online 存档订阅者最初都会收到 100 GB 的存档邮箱存储空间。启用自动扩展存档后, 将在达到 100 GB 存储容量时自动添加额外的存储空间。有关详细信息, 请参阅[Office 365 中的无限制存档概述](https://go.microsoft.com/fwlink/?linkid=844060)。有关可用性的详细信息, 请参阅[Office 365 路线图](http://go.microsoft.com/fwlink/?LinkId=509914)。 
  
> [!IMPORTANT]
> 管理员无法调整存储配额。
>
> 驻留在 Exchange Server 2010 上的邮箱不支持自动扩展存档。
  
> [!IMPORTANT]
> 仅对单个用户或共享邮箱使用自动扩展存档, 这些邮箱的增长速度*不超过每天的&nbsp;1 GB*。不允许使用日记、传输规则或自动转发规则将邮件复制到 Exchange Online 存档以用于存档目的。用户的存档邮箱仅供该用户使用。Microsoft 保留在用户的存档邮箱用于存储其他用户的存档数据的情况下拒绝无限存档的权利。 
  
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
|Outlook Web App  <br/> |是  <br/> |必需  <br/> |
|**[Exchange Online Archiving 中的合规性功能和安全功能](compliance-and-security-features.md)** <br/> |||
|保留策略  <br/> |是  <br/> |是  <br/> |
|就地保留和诉讼保留<sup>6</sup> <br/> |是  <br/> |是  <br/> |
|就地电子数据展示  <br/> |是  <br/> |是  <br/> |
|在本地服务器和 Exchange Online Archiving 之间加密  <br/> |是  <br/> |是  <br/> |
|在客户端和 Exchange Online Archiving 之间加密  <br/> |是  <br/> |是  <br/> |
|加密：S/MIME 和 PGP  <br/> |是  <br/> |是  <br/> |
|使用 Azure 信息保护的 IRM  <br/> |否  <br/> |无<sup>4</sup> <br/> |
|使用 Windows Server AD RMS 的 IRM  <br/> |是<sup>5</sup> <br/> |是<sup>5</sup> <br/> |
|审核  <br/> |是  <br/> |是  <br/> |
   

> <sup>1</sup>用户邮箱必须位于 Exchange 2010 SP2 或更高版本上。
 <br/><sup>2</sup>就地存档仅可用于存档已应用了许可证的单个用户或实体的邮件。禁止将就地存档用作存储来自多个用户或实体的邮件的方法。例如, IT 管理员无法创建共享邮箱, 并使用户能够复制 (通过 "抄送" 或 "密件抄送" 字段, 或通过传输规则) 共享邮箱以实现存档的明确目的。 <br/> <sup>3</sup>有关受支持的 Microsoft Outlook 版本的列表, 请参阅[Exchange Online 存档中的客户端功能](client-features.md)。 
 <br/><sup>4</sup>不包含 Azure 信息保护, 但可作为单独的附加项购买, 并将启用受支持的信息权限管理 (IRM) 功能。某些 Azure 信息保护功能需要订阅 office 365 专业增强版, 该订阅不包含在 office 365 商业协作版、office 365 商业高级版、office 365 企业版 E1、office 365 教育版或 office 365 enterprise F1 中。 <br/><sup>5</sup> Windows Server AD RMS 是一款本地服务器，必须单独购买并管理，才能启用支持的 IRM 功能。 
 <br/><sup>6</sup> 当您将邮箱置于就地保留或诉讼保留中时，该保留将置于主邮箱和存档邮箱中。 