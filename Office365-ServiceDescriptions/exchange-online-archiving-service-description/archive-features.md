---
title: Exchange Online 存档中的存档功能
ms.author: sharik
author: skjerland
manager: mnirkhe
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
ms.openlocfilehash: aa3a43a0af668f84adaf14c69ad5b38d7c5cb1eb
ms.sourcegitcommit: 0abb96f4771fd2e2a674589059ddc43c50f55d98
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 01/08/2020
ms.locfileid: "40987574"
---
# <a name="archive-features-in-exchange-online-archiving"></a><span data-ttu-id="d4fa5-103">Exchange Online 存档中的存档功能</span><span class="sxs-lookup"><span data-stu-id="d4fa5-103">Archive features in Exchange Online Archiving</span></span>

<span data-ttu-id="d4fa5-104">以下部分介绍了 Microsoft Exchange Online 存档的存档功能。</span><span class="sxs-lookup"><span data-stu-id="d4fa5-104">The following sections describe the archive features of Microsoft Exchange Online Archiving.</span></span>
  
## <a name="archive-mailbox"></a><span data-ttu-id="d4fa5-105">存档邮箱</span><span class="sxs-lookup"><span data-stu-id="d4fa5-105">Archive mailbox</span></span>

<span data-ttu-id="d4fa5-106">Exchange Online Archiving 通过存档邮箱功能为用户提供了高级存档功能。</span><span class="sxs-lookup"><span data-stu-id="d4fa5-106">Exchange Online Archiving offers users advanced archiving capabilities with the archive mailbox feature.</span></span> <span data-ttu-id="d4fa5-107">存档邮箱是在 Outlook 或 web 上的 Outlook 中显示在用户的主邮箱文件夹旁边的专用邮箱。</span><span class="sxs-lookup"><span data-stu-id="d4fa5-107">An archive mailbox is a specialized mailbox that appears alongside the users' primary mailbox folders in Outlook or Outlook on the web.</span></span> <span data-ttu-id="d4fa5-108">用户可以像访问其主邮箱一样访问存档。</span><span class="sxs-lookup"><span data-stu-id="d4fa5-108">Users can access the archive in the same way that they access their primary mailboxes.</span></span> <span data-ttu-id="d4fa5-109">此外，用户还可以搜索归档邮箱和主邮箱。</span><span class="sxs-lookup"><span data-stu-id="d4fa5-109">In addition, they can search both their archives and primary mailboxes.</span></span>
  
<span data-ttu-id="d4fa5-p102">管理员可以使用 Exchange 管理中心 (EAC) 或远程 Windows PowerShell 为特定用户启用存档功能。有关详细信息，请参阅 [Enable or disable archive mailboxes in Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes)（在 Exchange Online 中启用或禁用存档邮箱）。</span><span class="sxs-lookup"><span data-stu-id="d4fa5-p102">Administrators can use the Exchange admin center (EAC) or remote Windows PowerShell to enable the archive feature for specific users. For more information, see [Enable or disable archive mailboxes in Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes).</span></span>
  
> [!IMPORTANT]
>  <span data-ttu-id="d4fa5-112">不允许使用日记、传输规则或自动转发规则将邮件复制到 Exchange Online Archiving 中来进行存档。</span><span class="sxs-lookup"><span data-stu-id="d4fa5-112">Using journaling, transport rules, or auto-forwarding rules to copy messages to Exchange Online Archiving for the purposes of archiving is not permitted.</span></span> <br/>
>  <span data-ttu-id="d4fa5-113">用户的存档邮箱只供该用户使用。</span><span class="sxs-lookup"><span data-stu-id="d4fa5-113">A user's archive mailbox is intended for just that user.</span></span> <span data-ttu-id="d4fa5-114">Microsoft 保留在用户的存档邮箱用于存储其他用户的存档数据或不适当使用的情况下，拒绝无限存档的权利。</span><span class="sxs-lookup"><span data-stu-id="d4fa5-114">Microsoft reserves the right to deny unlimited archiving in instances where a user's archive mailbox is used to store archive data for other users or in other cases of inappropriate use.</span></span>
  
### <a name="move-messages-to-exchange-online-archiving"></a><span data-ttu-id="d4fa5-115">将邮件移动到 Exchange Online Archiving</span><span class="sxs-lookup"><span data-stu-id="d4fa5-115">Move messages to Exchange Online Archiving</span></span>

<span data-ttu-id="d4fa5-116">用户可以将邮件从 .pst 文件拖放到存档中，以便于联机访问。</span><span class="sxs-lookup"><span data-stu-id="d4fa5-116">Users can drag and drop messages from .pst files into the archive, for easy online access.</span></span> <span data-ttu-id="d4fa5-117">用户还可以使用存档策略自动将电子邮件项从主邮箱移到存档邮箱中，从而降低主邮箱的大小，并提升主邮箱的性能。</span><span class="sxs-lookup"><span data-stu-id="d4fa5-117">Users can also move email items from the primary mailbox to the archive mailbox automatically, using Archive Polices, to reduce the size and improve the performance of the primary mailbox.</span></span> 
  
### <a name="import-data-to-the-archive"></a><span data-ttu-id="d4fa5-118">将数据导入到存档</span><span class="sxs-lookup"><span data-stu-id="d4fa5-118">Import data to the archive</span></span>

<span data-ttu-id="d4fa5-119">用户可以通过以下方式将数据导入到存档：</span><span class="sxs-lookup"><span data-stu-id="d4fa5-119">Users can import data to the archive in the following ways:</span></span>
  
- <span data-ttu-id="d4fa5-120">使用 Outlook 导入和导出向导从 .pst 文件导入数据。</span><span class="sxs-lookup"><span data-stu-id="d4fa5-120">Import data from a .pst file using Outlook's Import and Export wizard.</span></span>
    
- <span data-ttu-id="d4fa5-121">将电子邮件从 .pst 文件拖到存档中。</span><span class="sxs-lookup"><span data-stu-id="d4fa5-121">Drag email messages from .pst files into the archive.</span></span>
    
- <span data-ttu-id="d4fa5-122">将电子邮件从主邮箱拖到存档中。</span><span class="sxs-lookup"><span data-stu-id="d4fa5-122">Drag email messages from the primary mailbox into the archive.</span></span>
    
- <span data-ttu-id="d4fa5-p106">让存档策略根据邮件的存在时间自动移动主邮箱中的电子邮件。有关详细信息，请参阅[保留标记和保留策略](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies)。</span><span class="sxs-lookup"><span data-stu-id="d4fa5-p106">Let archive policies automatically move email messages from the primary mailbox, based on the age of the messages. For more information, see [Retention Tags and Retention Policies](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).</span></span>
    
> [!NOTE]
> <span data-ttu-id="d4fa5-p107">管理员还可以使用 Office 365 导入服务将 .pst 文件导入用户的基于云的存档邮箱。有关详细信息，请参阅 [Use network upload to import PST files to Office 365](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files)（使用网络上载将 PST 文件导入 Office 365）。</span><span class="sxs-lookup"><span data-stu-id="d4fa5-p107">Administrators can also use Office 365 Import service to import .pst files to users' cloud-based archive mailboxes. For more information, see [Use network upload to import PST files to Office 365](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).</span></span> 
  
## <a name="deleted-item-recovery"></a><span data-ttu-id="d4fa5-127">已删除邮件的恢复</span><span class="sxs-lookup"><span data-stu-id="d4fa5-127">Deleted item recovery</span></span>

<span data-ttu-id="d4fa5-p108">用户可以从其存档中的任何电子邮件文件夹中恢复已删除的邮件。邮件删除之后，邮件仍保留在存档的"已删除邮件"文件夹中。它将一直保留，直到用户手动删除或通过保留策略自动删除为止。</span><span class="sxs-lookup"><span data-stu-id="d4fa5-p108">Users can restore items they have deleted from any email folder in their archive. When an item is deleted, it is kept in the archive's Deleted Items folder. It remains there until it is manually removed by the user, or automatically removed by retention policies.</span></span>
  
<span data-ttu-id="d4fa5-131">After an item has been removed from the archive's Deleted Items folder, the item is kept in the archive's Recoverable Items folder for an additional 14 days before being permanently removed.</span><span class="sxs-lookup"><span data-stu-id="d4fa5-131">After an item has been removed from the archive's Deleted Items folder, the item is kept in the archive's Recoverable Items folder for an additional 14 days before being permanently removed.</span></span> <span data-ttu-id="d4fa5-132">用户可以使用 Microsoft Outlook 或 web 上的 Outlook 中的 "**恢复已删除邮件**" 功能来恢复这些项目。</span><span class="sxs-lookup"><span data-stu-id="d4fa5-132">Users can recover these items using the **Recover Deleted Items** feature in Microsoft Outlook or Outlook on the web.</span></span> 
  
<span data-ttu-id="d4fa5-p110">如果用户已从"可恢复的项目"文件夹中手动清除邮件，管理员可以使用"单个项目恢复"功能在 14 天（同一期限）内恢复邮件。使用此功能，管理员可以执行多邮箱搜索来查找已清除的邮件，然后使用  `Search-Mailbox` Windows PowerShell cmdlet 将邮件从发现邮箱移到用户邮箱中。有关详细信息，请参阅 [Enable or disable single item recovery for a mailbox](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files)（为邮箱启用或禁用"单个项目恢复"）。</span><span class="sxs-lookup"><span data-stu-id="d4fa5-p110">If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same 14 day window, through a feature called Single Item Recovery. This feature allows administrators to conduct a multi-mailbox search to find purged items and then use the  `Search-Mailbox` Windows PowerShell cmdlet to move the items from the discovery mailbox to users' mailboxes. For more information, see [Enable or disable single item recovery for a mailbox](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="d4fa5-136">默认情况下，单项目恢复期是 14 天，但在某些情况下可对其进行自定义。</span><span class="sxs-lookup"><span data-stu-id="d4fa5-136">The Single Item Recovery period is 14 days by default, but it can be customized in some circumstances.</span></span> <br/>
>  <span data-ttu-id="d4fa5-137">如果管理员已将用户的邮箱置于就地保留或诉讼保留中，则清除的项目将无限期保留，并且14天的窗口不会应用。</span><span class="sxs-lookup"><span data-stu-id="d4fa5-137">If an administrator has placed a user's mailbox on In-Place Hold or Litigation Hold, purged items are retained indefinitely and the 14-day window does not apply.</span></span> 
  
## <a name="deleted-mailbox-recovery"></a><span data-ttu-id="d4fa5-138">已删除邮箱的恢复</span><span class="sxs-lookup"><span data-stu-id="d4fa5-138">Deleted mailbox recovery</span></span>

<span data-ttu-id="d4fa5-p112">当管理员将用户从本地 Exchange Server 删除时，也将删除用户的存档。如果需要恢复已删除的存档邮箱，Office 365 支持团队可以执行此恢复。恢复的存档将包含删除时其中存储的所有邮件。</span><span class="sxs-lookup"><span data-stu-id="d4fa5-p112">When administrators delete users from the on-premises Exchange Server, the users' archives are also deleted. If the deleted archive mailboxes need to be recovered, the Office 365 support team can perform this recovery. A recovered archive will contain all of the mail stored in it at the time it was deleted.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="d4fa5-p113">用户邮箱删除后 30 天内，管理员可以请求恢复存档邮箱。30 天后，存档邮箱不可恢复。</span><span class="sxs-lookup"><span data-stu-id="d4fa5-p113">Administrators have 30 days from the time a user's mailbox is deleted to request an archive mailbox recovery. After 30 days, the archive mailbox is not recoverable.</span></span> 
  
## <a name="mailbox-service-redundancy"></a><span data-ttu-id="d4fa5-144">邮箱服务冗余</span><span class="sxs-lookup"><span data-stu-id="d4fa5-144">Mailbox service redundancy</span></span>

<span data-ttu-id="d4fa5-145">Exchange Online Archiving 中的存档邮箱不断复制为多个数据库副本，存储在多个地理位置分散的 Microsoft 数据中心内，以便在邮件基础结构出现故障的情况下，能够为客户提供数据恢复功能。</span><span class="sxs-lookup"><span data-stu-id="d4fa5-145">Archive mailboxes in Exchange Online Archiving are replicated to multiple database copies, in geographically dispersed Microsoft data centers, to provide data restoration capability in the event of a messaging infrastructure failure.</span></span> <span data-ttu-id="d4fa5-146">对于大规模故障，将会启动业务连续性管理。</span><span class="sxs-lookup"><span data-stu-id="d4fa5-146">For large-scale failures, business continuity management is initiated.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="d4fa5-147">功能可用性</span><span class="sxs-lookup"><span data-stu-id="d4fa5-147">Feature availability</span></span>

<span data-ttu-id="d4fa5-148">若要查看跨 Office 365 计划、独立选项和本地解决方案的功能可用性，请参阅[Exchange Online 存档服务说明](exchange-online-archiving-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="d4fa5-148">To view feature availability across Office 365 plans, standalone options, and on-premises solutions, see [Exchange Online Archiving service description](exchange-online-archiving-service-description.md).</span></span>
  
