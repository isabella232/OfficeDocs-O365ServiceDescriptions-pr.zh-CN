---
title: 收件人、域和公司管理
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: Microsoft Exchange Online Protection （EOP）提供了几种管理您的收件人、域和公司信息的方法。 作为管理员，您可以在 Exchange 管理中心（EAC）内执行某些管理任务，并验证在 Microsoft 365 管理中心中执行的其他管理任务。
ms.openlocfilehash: 1183a90754edc2bab698fb4d8d8b97acff90370c
ms.sourcegitcommit: 83c602d9c498df5a2fe0095c6fb0a267c8a708b7
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/17/2020
ms.locfileid: "42687831"
---
# <a name="recipient-domain-and-company-management"></a><span data-ttu-id="f225b-104">收件人、域和公司管理</span><span class="sxs-lookup"><span data-stu-id="f225b-104">Recipient, domain, and company management</span></span>

<span data-ttu-id="f225b-105">Microsoft Exchange Online Protection （EOP）提供了几种管理您的收件人、域和公司信息的方法。</span><span class="sxs-lookup"><span data-stu-id="f225b-105">Microsoft Exchange Online Protection (EOP) offers several means of managing your recipient, domain, and company information.</span></span> <span data-ttu-id="f225b-106">作为管理员，您可以在 Exchange 管理中心（EAC）内执行某些管理任务，并验证在 Microsoft 365 管理中心中执行的其他管理任务。</span><span class="sxs-lookup"><span data-stu-id="f225b-106">As an administrator, you can perform certain management tasks within the Exchange admin center (EAC), and verify other management tasks performed in the Microsoft 365 admin center.</span></span>
  
<span data-ttu-id="f225b-107">要查找有关 EOP 所有功能的信息吗？</span><span class="sxs-lookup"><span data-stu-id="f225b-107">Looking for information about all EOP features?</span></span> <span data-ttu-id="f225b-108">请参阅[Exchange Online Protection 服务说明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="f225b-108">See the [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="mail-recipients"></a><span data-ttu-id="f225b-109">Mail recipients</span><span class="sxs-lookup"><span data-stu-id="f225b-109">Mail recipients</span></span>

<span data-ttu-id="f225b-110">邮件收件人被归为邮件用户或组，可直接在 EAC 中或使用远程 Windows PowerShell 通过目录同步进行管理。</span><span class="sxs-lookup"><span data-stu-id="f225b-110">Mail recipients are categorized as mail users or groups and can be managed through directory synchronization, directly in the EAC, or via remote Windows PowerShell.</span></span> <span data-ttu-id="f225b-111">如果要在本地管理收件人，必须运行目录同步，这样邮件收件人才能反映在 EAC 中。</span><span class="sxs-lookup"><span data-stu-id="f225b-111">If you're managing your recipients on-premises, you must run directory synchronization in order for your mail recipients to be reflected in the EAC.</span></span> <span data-ttu-id="f225b-112">仅在 Microsoft 365 管理中心内管理的用户无法在 EAC 中查看，但可以在 EAC 的管理员角色组中的成员身份添加或删除它们。</span><span class="sxs-lookup"><span data-stu-id="f225b-112">Users managed solely in the Microsoft 365 admin center aren't viewable in the EAC, but they can be added to or removed from membership in an administrator role group in the EAC.</span></span> <span data-ttu-id="f225b-113">若要详细了解 EOP 中的收件人，请参阅 [EOP 中的收件人](https://go.microsoft.com/fwlink/p/?LinkId=280011)。</span><span class="sxs-lookup"><span data-stu-id="f225b-113">For more information about recipients in EOP, see [Recipients in EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).</span></span>
  
## <a name="admin-role-group-permissions"></a><span data-ttu-id="f225b-114">Admin role group permissions</span><span class="sxs-lookup"><span data-stu-id="f225b-114">Admin role group permissions</span></span>

<span data-ttu-id="f225b-p105">在 EOP 中，只能配置管理角色。在 EAC 中，可以将用户直接添加到默认管理员角色组中，也可以直接从中删除。无可用 RBAC 自定义项。有关详细信息，请参阅[管理 EOP 中的管理员角色组权限](https://go.microsoft.com/fwlink/p/?LinkId=282238)。</span><span class="sxs-lookup"><span data-stu-id="f225b-p105">In EOP, you can configure administrative roles only. Users can be added and removed from default admin role groups directly in the EAC. No RBAC customization is available. For more information, see [Manage Admin Role Group Permissions in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).</span></span>
  
## <a name="domain-management"></a><span data-ttu-id="f225b-119">域管理</span><span class="sxs-lookup"><span data-stu-id="f225b-119">Domain management</span></span>

<span data-ttu-id="f225b-120">托管域是指受 EOP 保护的域。</span><span class="sxs-lookup"><span data-stu-id="f225b-120">Managed domains are domains that are protected by EOP.</span></span> <span data-ttu-id="f225b-121">可以在 EAC 中查看托管域并编辑域类型。</span><span class="sxs-lookup"><span data-stu-id="f225b-121">Managed domains can be viewed and domain types can be edited in the EAC.</span></span> <span data-ttu-id="f225b-122">域设置和管理在 Microsoft 365 管理中心发生，并且更改在 EAC 中反映出来。</span><span class="sxs-lookup"><span data-stu-id="f225b-122">Domain provisioning and management occurs in the Microsoft 365 admin center and changes are reflected in the EAC.</span></span> <span data-ttu-id="f225b-123">有关详细信息，请参阅[查看或编辑 EOP 中的托管域](https://go.microsoft.com/fwlink/p/?LinkId=282239)。</span><span class="sxs-lookup"><span data-stu-id="f225b-123">For more information, see [View or Edit Managed Domains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).</span></span>
  
## <a name="match-subdomains"></a><span data-ttu-id="f225b-124">Match subdomains</span><span class="sxs-lookup"><span data-stu-id="f225b-124">Match subdomains</span></span>

<span data-ttu-id="f225b-p107">在 EOP 中，可以启用流向托管域的子域的邮件流。有关详细信息，请参阅[在 EOP 中为子域启用电子邮件流](https://go.microsoft.com/fwlink/p/?LinkId=397213)。</span><span class="sxs-lookup"><span data-stu-id="f225b-p107">In EOP, you can enable mail flow to subdomains of a managed domain. For more information, see [Enable Email Flow for Subdomains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213).</span></span> 
  
## <a name="directory-based-edge-blocking-dbeb"></a><span data-ttu-id="f225b-127">Directory Based Edge Blocking (DBEB)</span><span class="sxs-lookup"><span data-stu-id="f225b-127">Directory Based Edge Blocking (DBEB)</span></span>

<span data-ttu-id="f225b-p108">通过基于目录的边缘阻止功能，您可以在服务网络外围拒绝发送至无效收件人的邮件。通过 DBEB，管理员可以向 Office 365 添加已启用邮件的收件人，并阻止发送到 Office 365 中不存在的电子邮件地址的所有邮件。如果邮件发送到 Office 365 中存在的有效电子邮件地址，则会继续通过其余服务筛选层（反恶意邮件、反垃圾邮件、传输规则）。如果地址不存在，服务甚至会在进行筛选之前阻止邮件，并向发件人发送未送达报告 (NDR) 以通知其邮件未送达。</span><span class="sxs-lookup"><span data-stu-id="f225b-p108">The Directory Based Edge Blocking feature lets you reject messages for invalid recipients at the service network perimeter. DBEB lets admins add mail-enabled recipients to Office 365 and block all messages sent to email addresses that aren't present in Office 365. If a message is sent to a valid email address present in Office 365, the message continues through the rest of the service filtering layers (anti-malware, anti-spam, transport rules). If the address is not present, the service blocks the message before filtering even occurs, and a non-delivery report (NDR) is sent to the sender informing them that their message was not delivered.</span></span> 
  
<span data-ttu-id="f225b-p109">必须执行一些用户和域配置，才能启用 DBEB。有关详细信息，请参阅[使用基于目录的边缘阻止拒绝发送给无效收件人的邮件](https://go.microsoft.com/fwlink/p/?LinkId=390676)。</span><span class="sxs-lookup"><span data-stu-id="f225b-p109">Enabling DBEB requires some user and domain configuration. For more information, see [Use Directory Based Edge Blocking to Reject Messages Sent to Invalid Recipients](https://go.microsoft.com/fwlink/p/?LinkId=390676).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="f225b-134">功能可用性</span><span class="sxs-lookup"><span data-stu-id="f225b-134">Feature availability</span></span>

<span data-ttu-id="f225b-135">若要查看跨 Office 365 计划、独立选项和本地解决方案的功能可用性，请参阅[Exchange Online Protection 服务说明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="f225b-135">To view feature availability across Office 365 plans, standalone options, and on-premises solutions, see [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>
