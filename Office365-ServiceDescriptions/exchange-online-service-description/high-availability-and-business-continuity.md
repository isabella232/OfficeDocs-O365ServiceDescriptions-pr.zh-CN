---
title: 高可用性和业务连续性
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-high-availability-and-business-continuity
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7b03465e-3b9c-4500-8956-a83377f4c2c3
description: Microsoft Exchange Online 为组织的电子邮件基础结构提供了广泛的保留和恢复支持。 这包括数据中心的邮箱复制，以及恢复已删除邮箱和已删除的邮件。
ms.openlocfilehash: 395977f77d4293d18c5cf53e02d43566ca9f7313
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/14/2020
ms.locfileid: "45131966"
---
# <a name="high-availability-and-business-continuity"></a>高可用性和业务连续性

Microsoft Exchange Online 为组织的电子邮件基础结构提供了广泛的保留和恢复支持。 这包括数据中心的邮箱复制，以及恢复已删除邮箱和已删除的邮件。
  
## <a name="mailbox-replication-at-data-centers"></a>数据中心的邮箱复制

Exchange Online mailboxes are continuously replicated to multiple database copies, in geographically dispersed Microsoft data centers, to provide data restoration capability in the event of a local messaging infrastructure failure. For large-scale failures, service continuity management procedures are initiated.
  
For more information about how Microsoft protects your data, see [Office 365 Trust Center](https://go.microsoft.com/fwlink/p/?LinkId=299135). If you are using Office 365 operated by 21Vianet, see the [21Vianet Trust Center](https://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl).
  
## <a name="deleted-mailbox-recovery"></a>已删除邮箱的恢复

管理员可以通过使用 Microsoft 365 管理中心删除相应的用户帐户或删除 Exchange Online 许可证，或使用远程 Windows PowerShell 中的**移除邮箱**Cmdlet 删除 exchange online 邮箱。 默认情况下，邮箱删除之后，Exchange Online 仍将邮箱及其内容保留 30 天。 30 天后，邮箱不可恢复。 已恢复邮箱包含邮箱删除时存储在其中的所有数据。 管理员可以使用 Microsoft 365 管理中心在保留期内恢复已删除的邮箱。 若要恢复已删除的邮箱，管理员必须还原相应的用户帐户或将 Exchange Online 许可证重新分配给该用户帐户。 有关详细信息，请参阅 [在 Exchange Online 中删除或还原用户邮箱](https://go.microsoft.com/fwlink/p/?LinkId=286992)。
  
## <a name="deleted-item-recovery"></a>已删除邮件的恢复

Exchange Online 允许用户从任何电子邮件文件夹（包括 "已删除邮件" 文件夹）还原已删除的项目。 邮件删除之后，邮件仍保留在用户的"已删除邮件"文件夹中。 它将一直保留，直到用户手动删除或通过保留策略自动删除该邮件为止。 管理员可以在 EAC 中或使用远程 Windows PowerShell 自定义保留策略。
  
邮件从"已删除邮件"文件夹中删除之后，将在"可恢复邮件"文件夹中继续保留 14 天，然后永久删除，但管理员可以使用远程 Windows PowerShell 最多将保留期限延长至 30 天。 在此时间段内，用户可以使用 Outlook 网页或 Outlook 中的 "恢复已删除邮件" 功能来恢复项目。 了解如何[更改已删除邮件的保留期限](https://go.microsoft.com/fwlink/p/?LinkId=286940)。
  
If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same time period by using the Single Item Recovery feature with remote Windows PowerShell. By default, Single Item Recovery is enabled when a mailbox is created. To learn more, see [Enable or disable single item recovery for a mailbox](https://go.microsoft.com/fwlink/p/?LinkID=286941).
  
To preserve messages for longer than 30 days in the Recoverable Items folder, organizations can implement longer-term email preservation or time-based In-Place Holds. Learn more about [placing a mailbox on In-Place Hold](https://go.microsoft.com/fwlink/p/?LinkId=271746).
  
## <a name="feature-availability"></a>功能可用性

若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅[Exchange Online 服务说明](exchange-online-service-description.md)。
  