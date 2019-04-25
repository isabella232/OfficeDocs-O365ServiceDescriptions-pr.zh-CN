---
title: 高可用性和业务连续性
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-high-availability-and-business-continuity
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7b03465e-3b9c-4500-8956-a83377f4c2c3
description: Microsoft Exchange Online 为组织的电子邮件基础结构提供了广泛的保留和恢复支持。 这包括数据中心的邮箱复制，以及恢复已删除邮箱和已删除的邮件。
ms.openlocfilehash: 2da41ba335faa4cf18228a64fbb1b420d438e503
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/25/2019
ms.locfileid: "33244898"
---
# <a name="high-availability-and-business-continuity"></a>High Availability and Business Continuity

Microsoft Exchange Online 为组织的电子邮件基础结构提供了广泛的保留和恢复支持。 这包括数据中心的邮箱复制，以及恢复已删除邮箱和已删除的邮件。
  
## <a name="mailbox-replication-at-data-centers"></a>数据中心的邮箱复制

Exchange Online 邮箱不断复制为多个数据库副本，存储在多个地理位置分散的 Microsoft 数据中心内，以便在本地邮件基础结构出现故障的情况下，能够为客户提供数据恢复功能。对于大规模的故障，启动服务连续性管理程序。
  
若要详细了解 Microsoft 如何保护数据，请访问 [Office 365 信任中心](https://go.microsoft.com/fwlink/p/?LinkId=299135)。如果使用的是由世纪互联运行的 Office 365，请访问[世纪互联信任中心](http://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl)。
  
## <a name="deleted-mailbox-recovery"></a>已删除邮箱的恢复

管理员可以通过使用 Microsoft 365 管理中心删除相应的用户帐户或删除 exchange online 许可证, 或使用远程 Windows PowerShell 中的**移除邮箱**cmdlet 删除 exchange online 邮箱。 默认情况下，邮箱删除之后，Exchange Online 仍将邮箱及其内容保留 30 天。 30 天后，邮箱不可恢复。 已恢复邮箱包含邮箱删除时存储在其中的所有数据。 管理员可以使用 Microsoft 365 管理中心在保留期内恢复已删除的邮箱。 若要恢复已删除邮箱，管理员必须还原相应的 Office 365 用户帐户，或者将 Exchange Online 许可证重新分配给用户帐户。 有关详细信息，请参阅 [在 Exchange Online 中删除或还原用户邮箱](https://go.microsoft.com/fwlink/p/?LinkId=286992)。
  
## <a name="deleted-item-recovery"></a>已删除邮件的恢复

Exchange Online 支持用户恢复已从任何电子邮件文件夹中删除的邮件，包括"已删除邮件"文件夹。邮件删除之后，邮件仍保留在用户的"已删除邮件"文件夹中。它将一直保留，直到用户手动删除或通过保留策略自动删除该邮件为止。管理员可以在 EAC 中或使用远程 Windows PowerShell 自定义保留策略。
  
邮件从"已删除邮件"文件夹中删除之后，将在"可恢复邮件"文件夹中继续保留 14 天，然后永久删除，但管理员可以使用远程 Windows PowerShell 最多将保留期限延长至 30 天。在此期间，用户可以使用 Outlook Web App 或 Outlook 中的"恢复已删除邮件"功能恢复邮件。了解如何[更改已删除邮件的保留期限](https://go.microsoft.com/fwlink/p/?LinkId=286940)。
  
如果用户已从"可恢复邮件"文件夹中手动清除邮件，管理员可以结合使用"单个项目恢复"功能和远程 Windows PowerShell 恢复同期邮件。默认情况下，创建邮箱时会启用"单个项目恢复"功能。若要了解详细信息，请参阅[启用或禁用邮箱的单个项目恢复](https://go.microsoft.com/fwlink/p/?LinkID=286941)。
  
若要在"可恢复邮件"文件夹中保留邮件 30 天以上，组织可以实现长期电子邮件保留或基于时间的就地保留。详细了解如何[将邮箱置于就地保留](https://go.microsoft.com/fwlink/p/?LinkId=271746)。
  
## <a name="feature-availability"></a>功能可用性

若要查看在各个 Office 365 计划、独立选项和内部部署解决方案之间的功能可用性，请参阅 [Exchange Online 服务说明](exchange-online-service-description.md)。
  

