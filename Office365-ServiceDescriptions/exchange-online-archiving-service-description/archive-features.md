---
title: Exchange Online Archiving 中的存档功能
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- archive-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 38abfbd2-5aaa-444a-a431-5e71c566f3e4
description: 以下部分介绍了 Microsoft Exchange Online 存档的存档功能。
ms.openlocfilehash: 7f6b5863d94862644fb90d1d0d85c3765ad05e9b
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/14/2020
ms.locfileid: "45131526"
---
# <a name="archive-features-in-exchange-online-archiving"></a>Exchange Online Archiving 中的存档功能

以下部分介绍了 Microsoft Exchange Online 存档的存档功能。
  
## <a name="archive-mailbox"></a>存档邮箱

Exchange Online Archiving 通过存档邮箱功能为用户提供了高级存档功能。 存档邮箱是在 Outlook 或 web 上的 Outlook 中显示在用户的主邮箱文件夹旁边的专用邮箱。 用户可以像访问其主邮箱一样访问存档。 此外，用户还可以搜索归档邮箱和主邮箱。
  
Administrators can use the Exchange admin center (EAC) or remote Windows PowerShell to enable the archive feature for specific users. For more information, see [Enable or disable archive mailboxes in Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes).
  
> [!IMPORTANT]
>  不允许使用日记、传输规则或自动转发规则将邮件复制到 Exchange Online Archiving 中来进行存档。 <br/>
>  用户的存档邮箱只供该用户使用。 Microsoft 保留在用户的存档邮箱用于存储其他用户的存档数据或不适当使用的情况下，拒绝无限存档的权利。
  
### <a name="move-messages-to-exchange-online-archiving"></a>将邮件移动到 Exchange Online Archiving

用户可以将邮件从 .pst 文件拖放到存档中，以便于联机访问。 用户还可以使用存档策略自动将电子邮件项从主邮箱移到存档邮箱中，从而降低主邮箱的大小，并提升主邮箱的性能。 
  
### <a name="import-data-to-the-archive"></a>将数据导入到存档

用户可以通过以下方式将数据导入到存档：
  
- 使用 Outlook 导入和导出向导从 .pst 文件导入数据。
    
- 将电子邮件从 .pst 文件拖到存档中。
    
- 将电子邮件从主邮箱拖到存档中。
    
- Let archive policies automatically move email messages from the primary mailbox, based on the age of the messages. For more information, see [Retention Tags and Retention Policies](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).
    
> [!NOTE]
> Administrators can also use Office 365 Import service to import .pst files to users' cloud-based archive mailboxes. For more information, see [Use network upload to import PST files to Office 365](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files). 
  
## <a name="deleted-item-recovery"></a>已删除邮件的恢复

Users can restore items they have deleted from any email folder in their archive. When an item is deleted, it is kept in the archive's Deleted Items folder. It remains there until it is manually removed by the user, or automatically removed by retention policies.
  
After an item has been removed from the archive's Deleted Items folder, the item is kept in the archive's Recoverable Items folder for an additional 14 days before being permanently removed. 用户可以使用 Microsoft Outlook 或 web 上的 Outlook 中的 "**恢复已删除邮件**" 功能来恢复这些项目。 
  
If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same 14 day window, through a feature called Single Item Recovery. This feature allows administrators to conduct a multi-mailbox search to find purged items and then use the  `Search-Mailbox` Windows PowerShell cmdlet to move the items from the discovery mailbox to users' mailboxes. For more information, see [Enable or disable single item recovery for a mailbox](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).
  
> [!NOTE]
>  默认情况下，单项目恢复期是 14 天，但在某些情况下可对其进行自定义。 <br/>
>  如果管理员已将用户的邮箱置于就地保留或诉讼保留中，则清除的项目将无限期保留，并且14天的窗口不会应用。 
  
## <a name="deleted-mailbox-recovery"></a>已删除邮箱的恢复

当管理员将用户从本地 Exchange Server 删除时，也将删除用户的存档。 如果需要恢复已删除的存档邮箱，Microsoft 支持团队可以执行此恢复。 恢复的存档将包含删除时其中存储的所有邮件。
  
> [!IMPORTANT]
> Administrators have 30 days from the time a user's mailbox is deleted to request an archive mailbox recovery. After 30 days, the archive mailbox is not recoverable. 
  
## <a name="mailbox-service-redundancy"></a>邮箱服务冗余

Exchange Online Archiving 中的存档邮箱不断复制为多个数据库副本，存储在多个地理位置分散的 Microsoft 数据中心内，以便在邮件基础结构出现故障的情况下，能够为客户提供数据恢复功能。 对于大规模故障，将会启动业务连续性管理。 
  
## <a name="feature-availability"></a>功能可用性

若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅[Exchange Online 存档服务说明](exchange-online-archiving-service-description.md)。
  
