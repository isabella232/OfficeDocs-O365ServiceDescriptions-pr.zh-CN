---
title: 域中的收件人、域和公司Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: 阅读本文，了解 Microsoft Exchange Online Protection (EOP) 中的收件人、域和公司) 。
ms.openlocfilehash: f58ffe829be839d8321cfc98f331d1836986e293
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652994"
---
# <a name="recipient-domain-and-company-management-in-exchange-online-protection"></a><span data-ttu-id="41d0d-103">域中的收件人、域和公司Exchange Online Protection</span><span class="sxs-lookup"><span data-stu-id="41d0d-103">Recipient, domain, and company management in Exchange Online Protection</span></span>

<span data-ttu-id="41d0d-104">Microsoft Exchange OnlineEOP (保护) 提供了几种管理收件人、域和公司信息的方式。</span><span class="sxs-lookup"><span data-stu-id="41d0d-104">Microsoft Exchange Online Protection (EOP) offers several means of managing your recipient, domain, and company information.</span></span> <span data-ttu-id="41d0d-105">作为管理员，您可以在 Exchange 管理中心 (EAC) 中执行某些管理任务，并验证在 Microsoft 365 管理中心中执行的其他管理任务。</span><span class="sxs-lookup"><span data-stu-id="41d0d-105">As an administrator, you can perform certain management tasks within the Exchange admin center (EAC), and verify other management tasks performed in the Microsoft 365 admin center.</span></span>
  
<span data-ttu-id="41d0d-106">要查找有关 EOP 所有功能的信息吗？</span><span class="sxs-lookup"><span data-stu-id="41d0d-106">Looking for information about all EOP features?</span></span> <span data-ttu-id="41d0d-107">请参阅Exchange Online Protection[服务说明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="41d0d-107">See the [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="mail-recipients"></a><span data-ttu-id="41d0d-108">Mail recipients</span><span class="sxs-lookup"><span data-stu-id="41d0d-108">Mail recipients</span></span>

<span data-ttu-id="41d0d-109">邮件收件人被归为邮件用户或组，可直接在 EAC 中或使用远程 Windows PowerShell 通过目录同步进行管理。</span><span class="sxs-lookup"><span data-stu-id="41d0d-109">Mail recipients are categorized as mail users or groups and can be managed through directory synchronization, directly in the EAC, or via remote Windows PowerShell.</span></span> <span data-ttu-id="41d0d-110">如果要在本地管理收件人，必须运行目录同步，这样邮件收件人才能反映在 EAC 中。</span><span class="sxs-lookup"><span data-stu-id="41d0d-110">If you're managing your recipients on-premises, you must run directory synchronization in order for your mail recipients to be reflected in the EAC.</span></span> <span data-ttu-id="41d0d-111">在 EAC 中Microsoft 365管理的用户不可在 EAC 中查看，但可以在 EAC 的管理员角色组成员身份中添加或删除这些用户。</span><span class="sxs-lookup"><span data-stu-id="41d0d-111">Users managed solely in the Microsoft 365 admin center aren't viewable in the EAC, but they can be added to or removed from membership in an administrator role group in the EAC.</span></span> <span data-ttu-id="41d0d-112">若要详细了解 EOP 中的收件人，请参阅 [EOP 中的收件人](/microsoft-365/security/office-365-security/manage-recipients-in-eop)。</span><span class="sxs-lookup"><span data-stu-id="41d0d-112">For more information about recipients in EOP, see [Recipients in EOP](/microsoft-365/security/office-365-security/manage-recipients-in-eop).</span></span>
  
## <a name="admin-role-group-permissions"></a><span data-ttu-id="41d0d-113">Admin role group permissions</span><span class="sxs-lookup"><span data-stu-id="41d0d-113">Admin role group permissions</span></span>

<span data-ttu-id="41d0d-p104">在 EOP 中，只能配置管理角色。在 EAC 中，可以将用户直接添加到默认管理员角色组中，也可以直接从中删除。无可用 RBAC 自定义项。有关详细信息，请参阅[管理 EOP 中的管理员角色组权限](/microsoft-365/security/office-365-security/manage-admin-role-group-permissions-in-eop)。</span><span class="sxs-lookup"><span data-stu-id="41d0d-p104">In EOP, you can configure administrative roles only. Users can be added and removed from default admin role groups directly in the EAC. No RBAC customization is available. For more information, see [Manage Admin Role Group Permissions in EOP](/microsoft-365/security/office-365-security/manage-admin-role-group-permissions-in-eop).</span></span>
  
## <a name="domain-management"></a><span data-ttu-id="41d0d-118">域管理</span><span class="sxs-lookup"><span data-stu-id="41d0d-118">Domain management</span></span>

<span data-ttu-id="41d0d-119">托管域是指受 EOP 保护的域。</span><span class="sxs-lookup"><span data-stu-id="41d0d-119">Managed domains are domains that are protected by EOP.</span></span> <span data-ttu-id="41d0d-120">可以在 EAC 中查看托管域并编辑域类型。</span><span class="sxs-lookup"><span data-stu-id="41d0d-120">Managed domains can be viewed and domain types can be edited in the EAC.</span></span> <span data-ttu-id="41d0d-121">域设置和管理发生在 Microsoft 365中心，更改将反映在 EAC 中。</span><span class="sxs-lookup"><span data-stu-id="41d0d-121">Domain provisioning and management occurs in the Microsoft 365 admin center and changes are reflected in the EAC.</span></span> <span data-ttu-id="41d0d-122">有关详细信息，请参阅[查看或编辑 EOP 中的托管域](/microsoft-365/security/office-365-security/exchange-online-protection-overview)。</span><span class="sxs-lookup"><span data-stu-id="41d0d-122">For more information, see [View or Edit Managed Domains in EOP](/microsoft-365/security/office-365-security/exchange-online-protection-overview).</span></span>
  
## <a name="match-subdomains"></a><span data-ttu-id="41d0d-123">Match subdomains</span><span class="sxs-lookup"><span data-stu-id="41d0d-123">Match subdomains</span></span>

<span data-ttu-id="41d0d-p106">在 EOP 中，可以启用流向托管域的子域的邮件流。有关详细信息，请参阅[在 EOP 中为子域启用电子邮件流](/microsoft-365/security/office-365-security/mail-flow-in-eop)。</span><span class="sxs-lookup"><span data-stu-id="41d0d-p106">In EOP, you can enable mail flow to subdomains of a managed domain. For more information, see [Enable Email Flow for Subdomains in EOP](/microsoft-365/security/office-365-security/mail-flow-in-eop).</span></span> 
  
## <a name="directory-based-edge-blocking-dbeb"></a><span data-ttu-id="41d0d-126">基于目录的边缘阻止 (DBEB)</span><span class="sxs-lookup"><span data-stu-id="41d0d-126">Directory Based Edge Blocking (DBEB)</span></span>

<span data-ttu-id="41d0d-127">通过基于目录的边缘阻止功能，您可以在服务网络外围拒绝发送至无效收件人的邮件。</span><span class="sxs-lookup"><span data-stu-id="41d0d-127">The Directory Based Edge Blocking feature lets you reject messages for invalid recipients at the service network perimeter.</span></span> <span data-ttu-id="41d0d-128">DBEB 允许管理员向 Microsoft 添加启用邮件的收件人并阻止发送到 Microsoft 中不存在的电子邮件地址的所有邮件。</span><span class="sxs-lookup"><span data-stu-id="41d0d-128">DBEB lets admins add mail-enabled recipients to Microsoft and block all messages sent to email addresses that aren't present in Microsoft.</span></span> <span data-ttu-id="41d0d-129">如果将邮件发送到 Microsoft 中提供的有效电子邮件地址，该邮件将继续通过反恶意软件、反垃圾邮件、传输规则 (其他服务筛选) 。</span><span class="sxs-lookup"><span data-stu-id="41d0d-129">If a message is sent to a valid email address present in Microsoft, the message continues through the rest of the service filtering layers (anti-malware, anti-spam, transport rules).</span></span> <span data-ttu-id="41d0d-130">如果地址不存在，服务甚至会在进行筛选之前阻止邮件，并向发件人发送未送达报告 (NDR) 以通知其邮件未送达。</span><span class="sxs-lookup"><span data-stu-id="41d0d-130">If the address is not present, the service blocks the message before filtering even occurs, and a non-delivery report (NDR) is sent to the sender informing them that their message was not delivered.</span></span> 
  
<span data-ttu-id="41d0d-p108">必须执行一些用户和域配置，才能启用 DBEB。有关详细信息，请参阅[使用基于目录的边缘阻止拒绝发送给无效收件人的邮件](/exchange/mail-flow-best-practices/use-directory-based-edge-blocking)。</span><span class="sxs-lookup"><span data-stu-id="41d0d-p108">Enabling DBEB requires some user and domain configuration. For more information, see [Use Directory Based Edge Blocking to Reject Messages Sent to Invalid Recipients](/exchange/mail-flow-best-practices/use-directory-based-edge-blocking).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="41d0d-133">功能可用性</span><span class="sxs-lookup"><span data-stu-id="41d0d-133">Feature availability</span></span>

<span data-ttu-id="41d0d-134">若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅Exchange Online Protection[说明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="41d0d-134">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>