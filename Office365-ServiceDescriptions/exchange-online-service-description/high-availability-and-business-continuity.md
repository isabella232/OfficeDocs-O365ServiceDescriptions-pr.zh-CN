---
title: 高可用性和业务连续性
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-high-availability-and-business-continuity
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7b03465e-3b9c-4500-8956-a83377f4c2c3
description: Microsoft Exchange Online 为组织的电子邮件基础结构提供了广泛的保留和恢复支持。 这包括数据中心的邮箱复制，以及恢复已删除邮箱和已删除的邮件。
ms.openlocfilehash: 17c53172e9b49661118c6e33754246c627e08540
ms.sourcegitcommit: 96dc758c790ddaf05f5c2b836451b417729cf119
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/18/2019
ms.locfileid: "35776823"
---
# <a name="high-availability-and-business-continuity"></a><span data-ttu-id="e37b7-104">High Availability and Business Continuity</span><span class="sxs-lookup"><span data-stu-id="e37b7-104">High Availability and Business Continuity</span></span>

<span data-ttu-id="e37b7-105">Microsoft Exchange Online 为组织的电子邮件基础结构提供了广泛的保留和恢复支持。</span><span class="sxs-lookup"><span data-stu-id="e37b7-105">Microsoft Exchange Online offers extensive retention and recovery support for an organization's email infrastructure.</span></span> <span data-ttu-id="e37b7-106">这包括数据中心的邮箱复制，以及恢复已删除邮箱和已删除的邮件。</span><span class="sxs-lookup"><span data-stu-id="e37b7-106">This includes mailbox replication at data centers and the ability to restore deleted mailboxes and deleted items.</span></span>
  
## <a name="mailbox-replication-at-data-centers"></a><span data-ttu-id="e37b7-107">数据中心的邮箱复制</span><span class="sxs-lookup"><span data-stu-id="e37b7-107">Mailbox replication at data centers</span></span>

<span data-ttu-id="e37b7-p103">Exchange Online 邮箱不断复制为多个数据库副本，存储在多个地理位置分散的 Microsoft 数据中心内，以便在本地邮件基础结构出现故障的情况下，能够为客户提供数据恢复功能。对于大规模的故障，启动服务连续性管理程序。</span><span class="sxs-lookup"><span data-stu-id="e37b7-p103">Exchange Online mailboxes are continuously replicated to multiple database copies, in geographically dispersed Microsoft data centers, to provide data restoration capability in the event of a local messaging infrastructure failure. For large-scale failures, service continuity management procedures are initiated.</span></span>
  
<span data-ttu-id="e37b7-p104">若要详细了解 Microsoft 如何保护数据，请访问 [Office 365 信任中心](https://go.microsoft.com/fwlink/p/?LinkId=299135)。如果使用的是由世纪互联运行的 Office 365，请访问[世纪互联信任中心](http://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl)。</span><span class="sxs-lookup"><span data-stu-id="e37b7-p104">For more information about how Microsoft protects your data, see [Office 365 Trust Center](https://go.microsoft.com/fwlink/p/?LinkId=299135). If you are using Office 365 operated by 21Vianet, see the [21Vianet Trust Center](http://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl).</span></span>
  
## <a name="deleted-mailbox-recovery"></a><span data-ttu-id="e37b7-112">已删除邮箱的恢复</span><span class="sxs-lookup"><span data-stu-id="e37b7-112">Deleted mailbox recovery</span></span>

<span data-ttu-id="e37b7-113">管理员可以通过使用 Microsoft 365 管理中心删除相应的用户帐户或删除 Exchange Online 许可证, 或使用远程 Windows PowerShell 中的**移除邮箱**Cmdlet 删除 exchange online 邮箱。</span><span class="sxs-lookup"><span data-stu-id="e37b7-113">Administrators can delete Exchange Online mailboxes by using the Microsoft 365 admin center to delete the corresponding user account or remove the Exchange Online license, or by using the **Remove-Mailbox** cmdlet in remote Windows PowerShell.</span></span> <span data-ttu-id="e37b7-114">默认情况下，邮箱删除之后，Exchange Online 仍将邮箱及其内容保留 30 天。</span><span class="sxs-lookup"><span data-stu-id="e37b7-114">When a mailbox is deleted, Exchange Online retains the mailbox and its contents for 30 days by default.</span></span> <span data-ttu-id="e37b7-115">30 天后，邮箱不可恢复。</span><span class="sxs-lookup"><span data-stu-id="e37b7-115">After 30 days, the mailbox is not recoverable.</span></span> <span data-ttu-id="e37b7-116">已恢复邮箱包含邮箱删除时存储在其中的所有数据。</span><span class="sxs-lookup"><span data-stu-id="e37b7-116">A recovered mailbox contains all of the data stored in it at the time it was deleted.</span></span> <span data-ttu-id="e37b7-117">管理员可以使用 Microsoft 365 管理中心在保留期内恢复已删除的邮箱。</span><span class="sxs-lookup"><span data-stu-id="e37b7-117">Administrators can recover a deleted mailbox within the retention period by using the Microsoft 365 admin center.</span></span> <span data-ttu-id="e37b7-118">若要恢复已删除邮箱，管理员必须还原相应的 Office 365 用户帐户，或者将 Exchange Online 许可证重新分配给用户帐户。</span><span class="sxs-lookup"><span data-stu-id="e37b7-118">To recover a deleted mailbox, administrators have to restore the corresponding Office 365 user account or reassign an Exchange Online license to the user account.</span></span> <span data-ttu-id="e37b7-119">有关详细信息，请参阅 [在 Exchange Online 中删除或还原用户邮箱](https://go.microsoft.com/fwlink/p/?LinkId=286992)。</span><span class="sxs-lookup"><span data-stu-id="e37b7-119">For more information, see [Delete or Restore User Mailboxes in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=286992).</span></span>
  
## <a name="deleted-item-recovery"></a><span data-ttu-id="e37b7-120">已删除邮件的恢复</span><span class="sxs-lookup"><span data-stu-id="e37b7-120">Deleted item recovery</span></span>

<span data-ttu-id="e37b7-p106">Exchange Online 支持用户恢复已从任何电子邮件文件夹中删除的邮件，包括"已删除邮件"文件夹。邮件删除之后，邮件仍保留在用户的"已删除邮件"文件夹中。它将一直保留，直到用户手动删除或通过保留策略自动删除该邮件为止。管理员可以在 EAC 中或使用远程 Windows PowerShell 自定义保留策略。</span><span class="sxs-lookup"><span data-stu-id="e37b7-p106">Exchange Online enables users to restore items they have deleted from any email folder, including the Deleted Items folder. When an item is deleted, it's kept in a user's Deleted Items folder. It remains there until it's either manually removed by the user or automatically removed by retention policies. Administrators can customize retention policies in the EAC or by using remote Windows PowerShell.</span></span>
  
<span data-ttu-id="e37b7-p107">邮件从"已删除邮件"文件夹中删除之后，将在"可恢复邮件"文件夹中继续保留 14 天，然后永久删除，但管理员可以使用远程 Windows PowerShell 最多将保留期限延长至 30 天。在此期间，用户可以使用 Outlook Web App 或 Outlook 中的"恢复已删除邮件"功能恢复邮件。了解如何[更改已删除邮件的保留期限](https://go.microsoft.com/fwlink/p/?LinkId=286940)。</span><span class="sxs-lookup"><span data-stu-id="e37b7-p107">After an item has been removed from the Deleted Items folder, it's kept in a Recoverable Items folder for an additional 14 days before being permanently removed, but administrators can increase this to a maximum of 30 days by using remote Windows PowerShell. Users can recover the item during this time period by using the Recover Deleted Items feature in Outlook Web App or Outlook. Learn how to [change the deleted item retention period](https://go.microsoft.com/fwlink/p/?LinkId=286940).</span></span>
  
<span data-ttu-id="e37b7-p108">如果用户已从"可恢复邮件"文件夹中手动清除邮件，管理员可以结合使用"单个项目恢复"功能和远程 Windows PowerShell 恢复同期邮件。默认情况下，创建邮箱时会启用"单个项目恢复"功能。若要了解详细信息，请参阅[启用或禁用邮箱的单个项目恢复](https://go.microsoft.com/fwlink/p/?LinkID=286941)。</span><span class="sxs-lookup"><span data-stu-id="e37b7-p108">If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same time period by using the Single Item Recovery feature with remote Windows PowerShell. By default, Single Item Recovery is enabled when a mailbox is created. To learn more, see [Enable or disable single item recovery for a mailbox](https://go.microsoft.com/fwlink/p/?LinkID=286941).</span></span>
  
<span data-ttu-id="e37b7-p109">若要在"可恢复邮件"文件夹中保留邮件 30 天以上，组织可以实现长期电子邮件保留或基于时间的就地保留。详细了解如何[将邮箱置于就地保留](https://go.microsoft.com/fwlink/p/?LinkId=271746)。</span><span class="sxs-lookup"><span data-stu-id="e37b7-p109">To preserve messages for longer than 30 days in the Recoverable Items folder, organizations can implement longer-term email preservation or time-based In-Place Holds. Learn more about [placing a mailbox on In-Place Hold](https://go.microsoft.com/fwlink/p/?LinkId=271746).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="e37b7-133">功能可用性</span><span class="sxs-lookup"><span data-stu-id="e37b7-133">Feature Availability</span></span>

<span data-ttu-id="e37b7-134">若要查看在各个 Office 365 计划、独立选项和内部部署解决方案之间的功能可用性，请参阅 [Exchange Online 服务说明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="e37b7-134">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

