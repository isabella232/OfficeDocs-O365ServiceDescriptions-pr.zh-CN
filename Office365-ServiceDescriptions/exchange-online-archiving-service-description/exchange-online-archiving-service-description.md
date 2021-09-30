---
title: Exchange Online Archiving 服务说明
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-archiving-service-description
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 21ebd4bb-7d88-489f-a8aa-376e2536900c
description: 阅读本文以了解 Microsoft Exchange Online Archiving。
ms.openlocfilehash: db1627fdb0955c00a504468841bff88f62e8a67c
ms.sourcegitcommit: 28c7d4dc2c98364ca9a2c9ba91744f2db89950bf
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/30/2021
ms.locfileid: "60015676"
---
# <a name="exchange-online-archiving-service-description"></a>Exchange Online Archiving 服务说明

Microsoft Exchange Online存档是Microsoft 365 Microsoft Exchange Server 2019、Microsoft Exchange Server 2016、Microsoft Exchange Server 2013 的组织基于云的企业级存档解决方案。Microsoft Exchange Server 2010 (SP2 及更高版本) 订阅特定 Exchange Online 或 Microsoft365 计划。 Exchange Online Archiving 可以帮助组织解决存档、相容性、监管和电子数据展示难题，同时简化本地基础结构，从而降低成本和减轻 IT 负担。
  
作为 Microsoft 在线服务，Exchange Online Archiving 旨在满足用户对强有力的安全性、可靠性和工作效率的需求。 有关其他Microsoft 365，包括所有 Microsoft 联机服务通用的功能，请参阅 Microsoft 365 和 Office 365[平台服务说明](../office-365-platform-service-description/office-365-platform-service-description.md)。
  
若要购买Exchange Online Archiving，请参阅 Exchange Online Archiving [for server。](https://products.office.com/exchange/microsoft-exchange-online-archiving-email)
  
## <a name="available-plans"></a>可用计划

有关允许用户进行订阅的详细信息，Exchange Online Archiving完整[订阅比较表](https://go.microsoft.com/fwlink/?linkid=2139145)。
  
> [!TIP]
> 可以在服务说明中导出、保存和打印页面。 了解如何导出 [内容搜索结果](/microsoft-365/compliance/export-search-results)。
  
## <a name="exchange-online-archiving-plans"></a>Exchange Online Archiving 计划

可通过以下计划使用 Exchange Online Archiving。<br><br>
  
| 计划 | 说明 |
|:-----|:-----|
|**适用于 Exchange Server 的 Exchange Online Archiving** |基于云的存档，适用于在 Exchange Server 2019、Exchange Server 2016、Exchange Server 2013 或 Exchange 2010 (SP2 或更高版本) 。 <br/> 如果想要将基于云的存档添加到位于本地 Exchange 服务器上的主邮箱，则需要配置混合部署。 有关混合部署详细信息，请参阅Exchange Server[部署](/exchange/exchange-hybrid)。 |
|**适用于 Exchange Server 的 Exchange Online Archiving（通过 Enterprise CAL Suite）** |基于云的存档，适用于在 Exchange Server 2019、Exchange Server 2016、Exchange Server 2013 或 Exchange 2010 (SP2 或更高版本) 。 有关详细信息，请参阅客户端 [访问许可证和管理许可证](https://www.microsoft.com/licensing/product-licensing/client-access-license)。 |
|**适用于 Exchange Online 的 Exchange Online Archiving** | 作为以下计划<sup>1，2，3</sup>的加载项的基于云的存档和就地保留：<br/> Exchange Online 计划 1 <br/> Exchange Online Kiosk <br/> Microsoft 365 商业基础版 <br/> Microsoft 365 商业标准版 <br/> Microsoft 365 商业高级版 <br/> Office 365 E1 <br/> Office 365 A1 <br/> Office 365G1 <br/> Office 365F3 <br/> Microsoft 365 F3<br/> <b>注意：</b>以下计划已包含存档，不需要Exchange Online Archiving加载项：<br/>Office 365 A3 <br/> Office 365 A5 <br/> Office 365 E3 <br/> Office 365 E5 <br/> Exchange Online 计划 2 <br/>Microsoft 365 E3 <br/> Microsoft 365 E5 <br/> Microsoft 365F5 合规性 <br/> 有关邮箱的存档功能Exchange Online，请参阅存档[邮箱中的Exchange Online Archiving。](./archive-features.md)|

<sup>1</sup> 仅使用云的组织无需混合部署，此类组织的 Exchange 本地服务器上没有邮箱。 但是，如果存在本地邮箱，则需要配置混合部署。
<br/>
<sup>2</sup> Exchange Online计划 1、Office 365 E1/A1/G1 和 Microsoft 365 商业基础版/Standard/高级版 对邮箱和存档具有大小限制。 有关详细信息，请参阅 [Exchange Online 限制](../exchange-online-service-description/exchange-online-limits.md)。 Exchange Online 适用的 Exchange Online Archiving加载项添加了自动扩展存档和[就地保留和诉讼保留](compliance-and-security-features.md#in-place-hold-and-litigation-hold)。
<br/>
<sup>3</sup>包括美国政府GCC、GCC-高和 DoD 计划。

要查找有关所有计划Microsoft 365的信息？ Microsoft 365提供了各种计划，以最好地满足组织的需求。 有关不同计划的信息，包括独立计划选项和从一个计划移动到另一个计划的信息，请参阅Office 365[计划选项](../office-365-platform-service-description/office-365-plan-options.md)。
  
## <a name="requirements"></a>要求

若要使用 Exchange Server 适用的 Exchange Online Archiving，用户邮箱必须位于 Exchange Server 2019、Exchange Server 2016、Exchange Server 2013 或 Exchange Server 2010 (SP2或更高版本) 。
  
### <a name="federated-identity-and-single-sign-on"></a>联合身份和单一登录

管理员可以使用单一登录方法对本地 Active Directory 进行身份验证。 为此，管理员可以将本地 Active Directory 联合身份验证服务（Microsoft Windows Server 2008 服务）配置为与 &reg; Microsoft Federation Gateway。 配置 Active Directory 联合身份验证服务后，其标识基于联盟域的所有用户都可以使用其现有公司登录名自动Office 365。
  
### <a name="user-subscriptions"></a>用户订阅

访问 Exchange Online Archiving 服务的每个用户都必须拥有一个 Exchange Online Archiving 订阅。每个电子邮件存档订阅只能用于存储一名用户的邮件数据。
  
## <a name="auto-expanding-archiving"></a>自动扩展存档

 称为自动扩展存档 *的存档功能* 在存档邮箱中提供额外的存储空间。 每个 Exchange Online Archiving 订阅者最初都会获得 100 GB 的存档邮箱存储空间。 启用自动扩展存档后，当达到 100 GB 存储容量时，将自动增加额外的存储空间。 此存储空间增量增加将继续，直到存档存储空间达到 1.5 TB。 在 Exchange 混合部署中，只有当本地用户的邮箱驻留在 Exchange Server 2019、Exchange Server 2016 或 Exchange Server 2013 (SP1 或更高版本) 上时，基于云的存档邮箱才支持自动扩展存档。 有关详细信息，请参阅 [自动扩展存档概述](/microsoft-365/compliance/autoexpanding-archiving)。
  
> [!IMPORTANT]
> 管理员无法调整存储配额。
>
> 驻留在 Exchange Server 2010 上的邮箱不支持自动扩展存档。
  
> [!IMPORTANT]
> 自动扩展存档仅支持用于单个用户的邮箱或每天增长不超过 *1 &nbsp; GB* 的共享邮箱。 不允许使用日记、传输规则或自动转发规则将邮件复制到 Exchange Online Archiving 中来进行存档。 用户的存档邮箱只供该用户使用。 Microsoft 保留拒绝在用户的存档邮箱用于存储其他用户的存档数据或其他不当使用情况下的额外存档存储的权利。
  
## <a name="feature-availability-across-exchange-online-archiving-plans"></a>跨 Exchange Online Archiving 计划的功能可用性

| 功能 | Exchange Online Archiving for Exchange Server<sup>1</sup> | Exchange Online Archiving for Exchange Online<sup>2</sup> |
|:-----|:-----|:-----|
|**[Exchange Online Archiving 中的存档功能](archive-features.md)** |||
|存档邮箱  |是  |是  |
|使用存档策略移动邮件  |是  |是  |
|将数据导入到存档  |是  |是  |
|已删除邮件的恢复  |是  |是  |
|已删除邮箱的恢复  |是  |是  |
|邮箱备份  |是  |是  |
|**[Exchange Online Archiving 中的客户端功能](client-features.md)** |||
|Outlook<sup>3</sup> |是  |是  |
|Outlook 网页版  |是  |是  |
|**[Exchange Online Archiving 中的合规性功能和安全功能](compliance-and-security-features.md)** |||
|保留策略  |是  |是  |
|就地保留和诉讼保留<sup>6</sup> |是  |是  |
|就地电子数据展示  |是  |是  |
|在本地服务器和 Exchange Online Archiving 之间加密  |是  |是  |
|在客户端和 Exchange Online Archiving 之间加密  |是  |是  |
|加密：S/MIME 和 PGP  |是  |是  |
|使用 Azure 信息保护的 IRM  |否  |否<sup>4</sup> |
|使用 Windows Server AD RMS 的 IRM  |是<sup>5</sup> |是<sup>5</sup> |
|审核  |是  |是  |
   

<sup>1</sup>用户邮箱必须位于 Exchange 2010 SP2 或更高版本上。
<br/>
<sup>2</sup> In-Place 存档只能用于存档已应用许可证的单个用户或实体的邮件。 禁止使用就地存档作为存储多个用户或实体的邮件的方法。 例如，IT 管理员无法创建共享邮箱且无法使用户复制（通过"抄送"或"密件抄送"字段，或通过传输规则）共享邮箱以便进行显式存档。 <br/> 
<sup>3</sup>有关受支持的 Microsoft Outlook列表，请参阅客户端[Exchange Online Archiving。](client-features.md) <br/>
<sup>4</sup> Azure 信息保护不包括在内，但可以单独购买加载项，并启用受支持的信息权限管理 (IRM) 功能。 某些 Azure 信息保护功能需要订阅 Microsoft 365 企业应用版，Microsoft 365 商业基础版、Microsoft 365 商业标准版、Office 365 企业版 E1、Office 365 教育版 或 Office 365 企业版 F3 中未Office 365 企业版订阅。 <br/>
<sup>5</sup> Windows Server AD RMS 是一款本地服务器，必须单独购买并管理，才能启用支持的 IRM 功能。 <br/>
<sup>6</sup> 当您将邮箱置于就地保留或诉讼保留中时，该保留将置于主邮箱和存档邮箱中。