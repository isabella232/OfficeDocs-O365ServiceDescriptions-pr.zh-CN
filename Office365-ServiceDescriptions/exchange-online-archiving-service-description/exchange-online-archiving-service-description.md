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
ms.openlocfilehash: 98c04ff716a1280f3e0b8d59fcfcc5c3518018e1
ms.sourcegitcommit: 35fc15ee2aa0a893567420254e13db9eb97b2e01
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/11/2021
ms.locfileid: "60268246"
---
# <a name="exchange-online-archiving-service-description"></a>Exchange Online Archiving 服务说明

Microsoft Exchange Online存档是Microsoft 365 Microsoft Exchange Server 2019、Microsoft Exchange Server 2016、Microsoft Exchange Server 2013 或订阅特定存档的组织基于云的企业级存档解决方案 Exchange Online或Microsoft 365计划。 Exchange Online Archiving帮助组织解决存档、合规性、法规和电子数据展示难题。

作为 Microsoft 在线服务，Exchange Online Archiving 旨在满足用户对强有力的安全性、可靠性和工作效率的需求。 有关其他Microsoft 365，包括所有 Microsoft 联机服务通用的功能，请参阅 Microsoft 365 和 Office 365[平台服务说明](../office-365-platform-service-description/office-365-platform-service-description.md)。

## <a name="exchange-online-archiving-plans"></a>Exchange Online Archiving 计划

有关允许用户使用 Exchange Online Archiving 订阅的详细计划信息[，请参阅](https://www.microsoft.com/microsoft-365/exchange/microsoft-exchange-online-archiving-email)Exchange Online Archiving。

可通过以下计划使用 Exchange Online Archiving。<br><br>
  
| 计划 | 说明 |
|:-----|:-----|
|**适用于 Exchange Server 的 Exchange Online Archiving** |基于云的存档，适用于在 Exchange Server 2019、Exchange Server 2016、Exchange Server 2013 或 Exchange 2010 (SP2 或更高版本) 。 <br/> 如果想要将基于云的存档添加到位于本地 Exchange 服务器上的主邮箱，则需要配置混合部署。 有关混合部署的信息，请参阅混合[Exchange Server部署](/exchange/exchange-hybrid)。 |
|**适用于 Exchange Server 的 Exchange Online Archiving（通过 Enterprise CAL Suite）** |基于云的存档，适用于在 Exchange Server 2019、Exchange Server 2016、Exchange Server 2013 或 Exchange 2010 (SP2 或更高版本) 。 有关详细信息，请参阅客户端 [访问许可证和管理许可证](https://www.microsoft.com/licensing/product-licensing/client-access-license)。 |
|**适用于 Exchange Online 的 Exchange Online Archiving** | 作为以下计划<sup>1，2，3</sup>的加载项的基于云的存档和就地保留：<br/> • Exchange Online计划 1 <br/> • Exchange Online Kiosk <br/> • Microsoft 365 商业基础版 <br/> • Microsoft 365 商业标准版 <br/> • Microsoft 365 商业高级版 (Exchange Online Archiving包含在计划)  <br/> • Office 365 E1 <br/> • Office 365 A1 <br/> • Office 365 G1 <br/> • Office 365 F3 <br/> • Microsoft 365 F3<br/> <b>注意：</b>以下计划已包含存档，不需要Exchange Online Archiving加载项：<br/> • Office 365 A3 <br/> • Office 365 A5 <br/> • Office 365 E3 <br/> • Office 365 E5 <br/> • Exchange Online计划 2 <br/> • Microsoft 365 E3 <br/> • Microsoft 365 E5 <br/> • Microsoft 365 F5 合规性 <br/> 有关邮箱的存档功能Exchange Online，请参阅存档[Exchange Online Archiving。](./archive-features.md)|

<sup>1</sup> 仅使用云的组织无需混合部署，此类组织的 Exchange 本地服务器上没有邮箱。 但是，如果存在本地邮箱，则需要配置混合部署。
<br/>
<sup>2</sup> Exchange Online计划 1、Office 365 E1/A1/G1 和 Microsoft 365 商业基础版/Standard/高级版 对邮箱和存档具有大小限制。 有关详细信息，请参阅 [Exchange Online 限制](../exchange-online-service-description/exchange-online-limits.md)。 Exchange Online 适用的 Exchange Online Archiving加载项添加了自动扩展存档和[就地保留和诉讼保留](compliance-and-security-features.md#in-place-hold-and-litigation-hold)。
<br/>
<sup>3</sup>包括美国政府GCC、GCC-高和 DoD 计划。

要查找有关所有计划Microsoft 365的信息？ Microsoft 365提供了各种计划，以最好地满足组织的需求。 有关不同计划的信息，包括独立计划选项和从一个计划移动到另一个计划的信息，请参阅Office 365[计划选项。](../office-365-platform-service-description/office-365-plan-options.md)

有关不同计划的信息，请参阅完整的 [订阅比较表](https://go.microsoft.com/fwlink/?linkid=2139145)。

> [!TIP]
> 可以在服务说明中导出、保存和打印页面。 了解如何导出 [**内容搜索结果**](/microsoft-365/compliance/export-search-results)。

## <a name="feature-availability-across-exchange-online-archiving-plans"></a>跨 Exchange Online Archiving 计划的功能可用性

下表列出了跨计划Exchange Online Archiving的主要功能， (某些注意事项) 。 此表可能发生更改，恕不另行通知。 有关详细信息，请参阅脚注。 有关最新、完整的功能列表，请参阅 [支持企业的强大工具](https://products.office.com/business/compare-more-office-365-for-business-plans)。

| 功能 | Exchange Online Archiving for Exchange Server<sup>1</sup> | Exchange Online Archiving for Exchange Online<sup>2</sup> |
|---------|------------------------------------------------|------------------------------------------------|
| [**Exchange Online Archiving 中的存档功能**](/office365/servicedescriptions/exchange-online-archiving-service-description/archive-features) | | |
| 存档邮箱 | 是 | 是 |
| 使用存档策略移动邮件 | 是 | 是 |
| 将数据导入到存档 | 是 | 是 |
| 已删除邮件的恢复 | 是 | 是 |
| 已删除邮箱的恢复 | 是 | 是 |
| 邮箱备份 | 是 | 是 |
| [**Exchange Online Archiving 中的客户端功能**](/office365/servicedescriptions/exchange-online-archiving-service-description/client-features) | | |
| Outlook<sup>3</sup> | 是 | 是 |
| Outlook 网页版 | 是 | 是 |
| [**Exchange Online Archiving 中的合规性功能和安全功能**](/office365/servicedescriptions/exchange-online-archiving-service-description/compliance-and-security-features) | | |
| 保留策略 | 是 | 是 |
| 就地保留和诉讼保留<sup>6</sup> | 是 | 是 |
| 就地电子数据展示 | 是 | 是 |
| 在本地服务器和 Exchange Online Archiving 之间加密 | 是 | 是 |
| 在客户端和 Exchange Online Archiving 之间加密 | 是 | 是 |
| 加密：S/MIME 和 PGP | 是 | 是 |
| 使用 Azure 信息保护的 IRM | 否 | 否<sup>4</sup> |
| 使用 Windows Server AD RMS 的 IRM | 是<sup>5</sup> | 是<sup>5</sup> |
| 审核 | 是 | 是 |

<sup>1</sup>用户邮箱必须驻留在 Exchange 2013 或更高版本上。 <br/>
<sup>2</sup> 存档邮箱只能用于存档已应用许可证的单个用户或实体的邮件。 禁止将存档邮箱用作存储来自多个用户或实体的邮件的方式。 例如，IT 管理员无法创建共享邮箱且无法使用户复制（通过“抄送”或“密件抄送”字段，或通过传输规则）共享邮箱以便进行显式存档。 <br/>
<sup>3</sup>有关受支持的 Microsoft Outlook的列表，请参阅客户端[Exchange Online Archiving。](/office365/servicedescriptions/exchange-online-archiving-service-description/client-features) <br/>
<sup>4</sup> Azure 信息保护不包括在内，但作为单独的加载项购买，并且将启用受支持的信息权限管理 (IRM) 功能。 某些 Azure 信息保护功能需要订阅 Microsoft 365 企业应用版，Microsoft 365 商业基础版、Microsoft 365 商业标准版、Office 365 企业版 E1、Office 365 教育版 或 Office 365 企业版 F3 中未包含此订阅。 <br/>
<sup>5</sup> Windows Server AD RMS 是一款本地服务器，必须单独购买并管理，才能启用支持的 IRM 功能。 <br/>
<sup>6</sup> 当您将邮箱置于就地保留或诉讼保留中时，该保留将置于主邮箱和存档邮箱中。

## <a name="licensing-terms"></a>许可条款

有关通过 Microsoft 商业批量许可计划购买的产品和服务的许可条款和条件，请参阅[产品条款网站](https://www.microsoft.com/licensing/terms/)。

## <a name="messaging"></a>消息传递

若要跟踪即将发生的更改，包括新功能和已更改的功能、计划的维护或其他重要公告，请访问“消息中心”。有关详细信息，请参阅 [消息中心](/microsoft-365/admin/manage/message-center)。

## <a name="accessibility"></a>辅助功能

Microsoft 始终致力于确保数据的安全性以及服务的[辅助功能](https://www.microsoft.com/trust-center/compliance/accessibility)。 有关详细信息，请参阅 [Microsoft 信任中心](https://www.microsoft.com/trust-center)和 [Office 辅助功能中心](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)。

## <a name="learn-more"></a>了解详细信息

有关此Exchange Online Archiving，请查看以下资源：

- 了解如何使用合规中心启用存档邮箱以支持组织的邮件保留、电子数据展示和保留要求：在安全与合规中心启用存档邮箱 - Microsoft 365[ &amp; 合规性](/microsoft-365/compliance/enable-archive-mailboxes)。
- 了解 Microsoft Exchange Online Archiving： Archive features in [Exchange Online Archiving - Service Descriptions 中提供的存档功能](/office365/servicedescriptions/exchange-online-archiving-service-description/archive-features)。
- 了解如何在 Microsoft 365 中创建存档和删除策略，以自动将项目移动到用户的存档邮箱：为组织中邮箱设置存档和删除策略 - Microsoft 365[合规性](/microsoft-365/compliance/set-up-an-archive-and-deletion-policy-for-mailboxes)。
- 若要查找Exchange Online服务区域（包括通讯簿、邮箱存储、报告和邮件跟踪限制）的限制，请参阅 Exchange Online [limits - Service Descriptions](/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits)。
- 管理员可以了解已删除邮件的恢复选项以及用于保护邮箱Exchange Online的高级别方法：[在](/exchange/back-up-email)Exchange Online 中备份电子邮件。
- 管理员可以搜索和恢复用户邮箱中的已删除电子邮件：恢复用户邮箱中的已删除邮件[Exchange Online。](/exchange/recipients-in-exchange-online/manage-user-mailboxes/recover-deleted-messages)

### <a name="requirements"></a>要求

若要使用Exchange Server 适用的 Exchange Online Archiving，用户邮箱必须位于 Exchange Server 2019、Exchange Server 2016 或 Exchange Server 2013。

### <a name="user-subscriptions"></a>用户订阅

访问 Exchange Online Archiving 服务的每个用户都必须拥有一个 Exchange Online Archiving 订阅。每个电子邮件存档订阅只能用于存储一名用户的邮件数据。

### <a name="federated-identity-and-single-sign-on"></a>联合身份和单一登录

管理员可以使用单一登录方法对本地 Active Directory 进行身份验证。 为此，管理员可以将本地 Active Directory 联合身份验证服务（Microsoft Windows Server 2008 服务）配置为与 &reg; Microsoft Federation Gateway。 配置 Active Directory 联合身份验证服务后，其标识基于联盟域的所有用户都可以使用其现有公司登录名自动Office 365。

### <a name="archive-storage-quota"></a>存档存储配额

管理员无法调整存储配额。 存档功能 (自动扩展存档) 存档邮箱中提供额外存储空间，最大为 1.5 TB。 每个 Exchange Online Archiving 订阅者最初都会获得 100 GB 的存档邮箱存储空间。 启用自动扩展存档后，当达到 100 GB 存储容量时，将自动增加额外的存储空间。 在 Exchange 混合部署中，只有当本地用户的邮箱驻留在 Exchange Server 2019、Exchange Server 2016 或 Exchange Server 2013 SP1 及更高版本上时，基于云的存档邮箱才支持自动扩展存档。

自动扩展存档仅支持用于单个用户的邮箱或每天增长不超过 *1 GB* 的共享邮箱。 不允许使用日记、传输规则或自动转发规则将邮件复制到 Exchange Online Archiving 中来进行存档。 用户的存档邮箱只供该用户使用。 Microsoft 保留拒绝在用户的存档邮箱用于存储其他用户的存档数据或其他不当使用情况下的存档数据的权利。

## <a name="auto-expanding-archiving"></a>自动扩展存档

称为自动扩展存档 *的存档功能* 在存档邮箱中提供额外的存储空间。 每个 Exchange Online Archiving 订阅者最初都会获得 100 GB 的存档邮箱存储空间。 启用自动扩展存档后，当达到 100 GB 存储容量时，将自动增加额外的存储空间。 此存储空间增量增加将继续，直到存档存储空间达到 1.5 TB。 在 Exchange 混合部署中，只有当本地用户的邮箱位于 Exchange Server 2019、Exchange Server 2016 或 Exchange Server 2013 (SP1 或更高版本) 上时，基于云的存档邮箱才支持自动扩展存档。 有关详细信息，请参阅 [自动扩展存档概述](/microsoft-365/compliance/autoexpanding-archiving)。
  
> [!IMPORTANT]
> 管理员无法调整存储配额。
>
> 驻留在 Exchange Server 2010 上的邮箱不支持自动扩展存档。
  
> [!IMPORTANT]
> 自动扩展存档仅支持用于单个用户的邮箱或每天增长不超过 *1 &nbsp; GB* 的共享邮箱。 不允许使用日记、传输规则或自动转发规则将邮件复制到 Exchange Online Archiving 中来进行存档。 用户的存档邮箱只供该用户使用。 Microsoft 保留拒绝在用户的存档邮箱用于存储其他用户的存档数据或其他不当使用情况下的额外存档存储的权利。
