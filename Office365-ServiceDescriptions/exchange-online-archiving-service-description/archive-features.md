---
title: Exchange Online Archiving 中的存档功能
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- archive-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 38abfbd2-5aaa-444a-a431-5e71c566f3e4
description: 以下各节介绍了 Microsoft Exchange Online Archiving 的存档功能。
ms.openlocfilehash: 2bffa9fccb2c040fde4edcf8a5c80f3bc109bba2
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035107"
---
# <a name="archive-features-in-exchange-online-archiving"></a>Exchange Online Archiving 中的存档功能

以下各节介绍了 Microsoft Exchange Online Archiving 的存档功能。
  
## <a name="archive-mailbox"></a>存档邮箱

Exchange Online Archiving 通过存档邮箱功能为用户提供了高级存档功能。存档邮箱是一种特殊类型的邮箱，它会与用户主邮箱文件夹一同显示在 Outlook 和 Outlook Web App 中。用户可以像访问其主邮箱一样访问存档。此外，用户还可以搜索归档邮箱和主邮箱。
  
管理员可以使用 Exchange 管理中心 (EAC) 或远程 Windows PowerShell 为特定用户启用存档功能。有关详细信息，请参阅 [Enable or disable archive mailboxes in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404425)（在 Exchange Online 中启用或禁用存档邮箱）。
  
> [!IMPORTANT]
>  不允许使用日记、传输规则或自动转发规则将邮件复制到 Exchange Online Archiving 中来进行存档。 >  用户的存档邮箱只供该用户使用。Microsoft 保留拒绝在用户存档邮箱用于存储其他用户存档数据的情况下进行无限制存档的权利。 
  
### <a name="move-messages-to-exchange-online-archiving"></a>将邮件移动到 Exchange Online Archiving

用户可以将邮件从 .pst 文件拖放到存档中，以便于联机访问。用户还可以使用存档策略自动将电子邮件项从主邮箱移到存档邮箱中，从而降低主邮箱的大小，并提升主邮箱的性能。尽管此行为与 Exchange Hosted Archive 为存档中的每封邮件创建辅助副本的行为不同，但两种行为均可达到保留要求。若要详细了解将邮件移到存档的其他方法，请参阅 [Archive mailboxes in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404421)（Exchange Online 中的存档邮箱）。
  
### <a name="import-data-to-the-archive"></a>将数据导入到存档

用户可以通过以下方式将数据导入到存档：
  
- 使用 Outlook 导入和导出向导从 .pst 文件导入数据。
    
- 将电子邮件从 .pst 文件拖到存档中。
    
- 将电子邮件从主邮箱拖到存档中。
    
- 让存档策略根据邮件的存在时间自动移动主邮箱中的电子邮件。有关详细信息，请参阅[保留标记和保留策略](https://go.microsoft.com/fwlink/p/?LinkId=314153)。
    
> [!NOTE]
> 管理员还可以使用 Office 365 导入服务将 .pst 文件导入用户的基于云的存档邮箱。有关详细信息，请参阅 [Use network upload to import PST files to Office 365](https://go.microsoft.com/fwlink/p/?linkid=823074)（使用网络上载将 PST 文件导入 Office 365）。 
  
## <a name="deleted-item-recovery"></a>恢复已删除邮件

用户可以从其存档中的任何电子邮件文件夹中恢复已删除的邮件。邮件删除之后，邮件仍保留在存档的"已删除邮件"文件夹中。它将一直保留，直到用户手动删除或通过保留策略自动删除为止。
  
已从存档已删除邮件文件夹中删除项目后，项目是保留存档的可恢复项目文件夹中永久删除之前其他 14 天。用户可以恢复使用在 Microsoft Outlook 或 Outlook Web App 中的**恢复已删除邮件**功能这些项目。 
  
如果用户已从"可恢复的项目"文件夹中手动清除邮件，管理员可以使用"单个项目恢复"功能在 14 天（同一期限）内恢复邮件。使用此功能，管理员可以执行多邮箱搜索来查找已清除的邮件，然后使用  `Search-Mailbox` Windows PowerShell cmdlet 将邮件从发现邮箱移到用户邮箱中。有关详细信息，请参阅 [Enable or disable single item recovery for a mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314155)（为邮箱启用或禁用"单个项目恢复"）。
  
> [!NOTE]
>  默认情况下，单项目恢复期是 14 天，但在某些情况下可对其进行自定义。 >  如果管理员已将用户邮箱置于就地保留或诉讼保留中，那么清除的邮件将无限期保留，14 天期限则不适用。 
  
## <a name="deleted-mailbox-recovery"></a>恢复已删除邮箱

当管理员将用户从本地 Exchange Server 删除时，也将删除用户的存档。如果需要恢复已删除的存档邮箱，Office 365 支持团队可以执行此恢复。恢复的存档将包含删除时其中存储的所有邮件。
  
> [!IMPORTANT]
> 用户邮箱删除后 30 天内，管理员可以请求恢复存档邮箱。30 天后，存档邮箱不可恢复。 
  
## <a name="mailbox-service-redundancy"></a>邮箱服务冗余

Exchange Online Archiving 中的存档邮箱被复制到多个数据库副本，在地理上分散 Microsoft 数据中心，以提供数据会消息的基础结构发生故障时还原功能。大型失败次数，启动业务连续性管理。 
  
## <a name="feature-availability"></a>功能可用性

若要查看在各个 Office 365 计划、独立选项和内部部署解决方案之间的功能可用性，请参阅 [Exchange Online Archiving 服务说明](exchange-online-archiving-service-description.md)。
  
