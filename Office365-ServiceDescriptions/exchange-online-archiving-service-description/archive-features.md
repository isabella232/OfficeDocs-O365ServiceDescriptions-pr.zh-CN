---
title: Exchange Online Archiving 中的存档功能
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- archive-features-in-exchange-online-archiving
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 38abfbd2-5aaa-444a-a431-5e71c566f3e4
description: 了解 Microsoft Exchange Online Archiving 中提供的存档功能。
ms.openlocfilehash: 1271018444f001e98fde5f628a4ef0a8c3abe782
ms.sourcegitcommit: 28c7d4dc2c98364ca9a2c9ba91744f2db89950bf
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/30/2021
ms.locfileid: "60015686"
---
# <a name="archive-features-in-exchange-online-archiving"></a>Exchange Online Archiving 中的存档功能

以下各节介绍存档的存档Microsoft Exchange Online功能。
  
## <a name="archive-mailbox"></a>存档邮箱

Exchange Online Archiving 通过存档邮箱功能为用户提供了高级存档功能。 存档邮箱是一种特殊邮箱，显示在用户主邮箱文件夹旁边或Outlook Outlook 网页版。 用户可以像访问其主邮箱一样访问存档。 此外，用户还可以搜索归档邮箱和主邮箱。
  
管理员可以使用 Exchange 管理中心 (EAC) 或远程 Windows PowerShell 为特定用户启用存档功能。有关详细信息，请参阅 [Enable or disable archive mailboxes in Exchange Online](/office365/securitycompliance/enable-archive-mailboxes)（在 Exchange Online 中启用或禁用存档邮箱）。
  
> [!IMPORTANT]
>  不允许使用日记、传输规则或自动转发规则将邮件复制到 Exchange Online Archiving 中来进行存档。
>
>  用户的存档邮箱只供该用户使用。 Microsoft 保留拒绝在用户的存档邮箱用于存储其他用户的存档数据或其他不当使用情况下的额外存档存储空间的权利。
  
### <a name="move-messages-to-exchange-online-archiving"></a>将邮件移动到 Exchange Online Archiving

用户可以将邮件从 .pst 文件拖放到存档中，以便于联机访问。 用户还可以使用存档策略自动将电子邮件项从主邮箱移到存档邮箱中，从而降低主邮箱的大小，并提升主邮箱的性能。 
  
### <a name="import-data-to-the-archive"></a>将数据导入到存档

用户可以通过以下方式将数据导入到存档：
  
- 使用 Outlook 导入和导出向导从 .pst 文件导入数据。
    
- 将电子邮件从 .pst 文件拖到存档中。
    
- 将电子邮件从主邮箱拖到存档中。
    
- 让存档策略根据邮件的存在时间自动移动主邮箱中的电子邮件。有关详细信息，请参阅[保留标记和保留策略](/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies)。
    
> [!NOTE]
> 管理员还可以使用 Office 365 导入服务将 .pst 文件导入用户的基于云的存档邮箱。有关详细信息，请参阅 [Use network upload to import PST files to Office 365](/office365/securitycompliance/use-network-upload-to-import-pst-files)（使用网络上载将 PST 文件导入 Office 365）。 
  
## <a name="deleted-item-recovery"></a>已删除邮件的恢复

用户可以从其存档中的任何电子邮件文件夹中恢复已删除的邮件。邮件删除之后，邮件仍保留在存档的"已删除邮件"文件夹中。它将一直保留，直到用户手动删除或通过保留策略自动删除为止。
  
After an item has been removed from the archive's Deleted Items folder, the item is kept in the archive's Recoverable Items folder for an additional 14 days before being permanently removed. 用户可以使用 Microsoft Outlook或 Outlook 网页版 中的"恢复已删除邮件"功能恢复这些项目。 
  
如果用户已从"可恢复的项目"文件夹中手动清除邮件，管理员可以使用"单个项目恢复"功能在 14 天（同一期限）内恢复邮件。使用此功能，管理员可以执行多邮箱搜索来查找已清除的邮件，然后使用  `Search-Mailbox` Windows PowerShell cmdlet 将邮件从发现邮箱移到用户邮箱中。有关详细信息，请参阅 [Enable or disable single item recovery for a mailbox](/office365/securitycompliance/use-network-upload-to-import-pst-files)（为邮箱启用或禁用"单个项目恢复"）。
  
> [!NOTE]
>  默认情况下，单项目恢复期是 14 天，但在某些情况下可对其进行自定义。
>
>  如果管理员将用户的邮箱置于"In-Place保留"或"诉讼保留"状态，则清除的项目将无限期保留，并且 14 天期限不适用。 
  
## <a name="deleted-mailbox-recovery"></a>已删除邮箱的恢复

当管理员将用户从本地 Exchange Server 删除时，也将删除用户的存档。 如果需要恢复已删除的存档邮箱，Microsoft 支持团队可以执行此恢复。 恢复的存档将包含删除时其中存储的所有邮件。
  
> [!IMPORTANT]
> 用户邮箱删除后 30 天内，管理员可以请求恢复存档邮箱。30 天后，存档邮箱不可恢复。 
  
## <a name="mailbox-service-redundancy"></a>邮箱服务冗余

Exchange Online Archiving 中的存档邮箱不断复制为多个数据库副本，存储在多个地理位置分散的 Microsoft 数据中心内，以便在邮件基础结构出现故障的情况下，能够为客户提供数据恢复功能。 对于大规模故障，将会启动业务连续性管理。 
  
## <a name="feature-availability"></a>功能可用性

若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅Exchange Online Archiving[说明](exchange-online-archiving-service-description.md)。
