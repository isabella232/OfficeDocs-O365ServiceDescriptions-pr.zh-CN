---
title: 权限
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-permissions
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7803d7c0-93e6-43a2-b2a4-3a39abe25500
description: Microsoft Exchange Online 使用基于角色的访问控制 (RBAC) 模型，支持组织管理员有效控制用户和 IT 员工可以在该服务中执行的操作。例如，如果合规专员负责处理邮箱搜索请求，则管理员可通过 RBAC 将此管理功能委派给该专员。Exchange Online 使用与 Microsoft Exchange Server 2013 相同的 RBAC 框架。
ms.openlocfilehash: a9c326e647470e1941f448a9ae61598fd746709e
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653314"
---
# <a name="permissions"></a><span data-ttu-id="2a40b-105">权限</span><span class="sxs-lookup"><span data-stu-id="2a40b-105">Permissions</span></span>

<span data-ttu-id="2a40b-p102">Microsoft Exchange Online 使用基于角色的访问控制 (RBAC) 模型，支持组织管理员有效控制用户和 IT 员工可以在该服务中执行的操作。例如，如果合规专员负责处理邮箱搜索请求，则管理员可通过 RBAC 将此管理功能委派给该专员。Exchange Online 使用与 Microsoft Exchange Server 2013 相同的 RBAC 框架。</span><span class="sxs-lookup"><span data-stu-id="2a40b-p102">Microsoft Exchange Online uses a Role Based Access Control (RBAC) model to allow organization administrators to finely control what users and IT employees can do in the service. For example, if a compliance officer is responsible for mailbox search requests, the administrator can delegate this administrative feature to the officer through RBAC. Exchange Online uses the same RBAC framework as Microsoft Exchange Server 2013.</span></span> 
  
<span data-ttu-id="2a40b-p103">在其最高级别中，RBAC 由管理角色、管理角色组和管理角色分配策略组成。以下部分提供有关每个 RBAC 组件的详细信息。</span><span class="sxs-lookup"><span data-stu-id="2a40b-p103">At its highest level, RBAC is made up of management roles, management role groups, and management role assignment policies. The following sections provide more information about each RBAC component.</span></span>
  
<span data-ttu-id="2a40b-111">若要详细了解 Exchange Online 中使用的 RBAC 权限模型，请参阅[权限](/exchange/permissions-exchange-2013-help)。</span><span class="sxs-lookup"><span data-stu-id="2a40b-111">For more information about the RBAC permissions model that's used in Exchange Online, see [Permissions](/exchange/permissions-exchange-2013-help).</span></span>
  
## <a name="role-based-permissions"></a><span data-ttu-id="2a40b-112">基于角色的权限</span><span class="sxs-lookup"><span data-stu-id="2a40b-112">Role-based permissions</span></span>

<span data-ttu-id="2a40b-p104">在 Exchange Online 中，授予管理员和用户的权限基于管理角色。角色定义了管理员或用户可以执行的任务集。例如，名为  `Mail Recipients` 的管理角色定义了某人可以对一组邮箱、联系人和通讯组执行的任务。为管理员或用户分配角色的同时，也会授予此人该角色所提供的权限。</span><span class="sxs-lookup"><span data-stu-id="2a40b-p104">In Exchange Online, the permissions that you grant to administrators and users are based on management roles. A role defines the set of tasks that an administrator or user can perform. For example, a management role called  `Mail Recipients` defines the tasks that someone can perform on a set of mailboxes, contacts, and distribution groups. When a role is assigned to an administrator or user, that person is granted the permissions provided by the role.</span></span> 
  
<span data-ttu-id="2a40b-117">角色分为两种类型，即管理角色和最终用户角色：</span><span class="sxs-lookup"><span data-stu-id="2a40b-117">There are two types of roles, administrative roles and end-user roles:</span></span>
  
- <span data-ttu-id="2a40b-118">**管理角色** 可以使用管理 Exchange Online 组织的一部分（如收件人、服务器或数据库）的角色组，将这些角色包含的权限分配给管理员或专家用户。</span><span class="sxs-lookup"><span data-stu-id="2a40b-118">**Administrative roles** These roles contain permissions that can be assigned to administrators or specialist users by using role groups that manage a part of the Exchange Online organization, such as recipients, servers, or databases.</span></span> 
    
- <span data-ttu-id="2a40b-119">**最终用户角色** 通过使用策略分配这些角色分配，用户可以管理其自己的邮箱及其拥有通讯组的各个方面。</span><span class="sxs-lookup"><span data-stu-id="2a40b-119">**End-user roles** These roles, assigned by using role assignment policies, let users manage aspects of their own mailboxes and distribution groups that they own.</span></span> <span data-ttu-id="2a40b-120">最终用户角色以前缀  `My` 开头。</span><span class="sxs-lookup"><span data-stu-id="2a40b-120">End-user roles begin with the prefix  `My`.</span></span>
    
<span data-ttu-id="2a40b-p106">角色通过向已分配角色的用户提供 cmdlet 来授予管理员和用户执行任务的权限。由于 Exchange 管理中心 (EAC) 和 Exchange 命令行管理程序使用 cmdlet 管理 Exchange Online，因此授予对 cmdlet 的访问权限将给予管理员或用户在每个 Exchange Online 管理界面中执行任务的权限。</span><span class="sxs-lookup"><span data-stu-id="2a40b-p106">Roles give administrators and users permissions to perform tasks by making cmdlets available to those who are assigned the roles. Because the Exchange admin center (EAC) and Exchange Management Shell use cmdlets to manage Exchange Online, granting access to a cmdlet gives the administrator or user permission to perform the task in each of the Exchange Online management interfaces.</span></span>
  
<span data-ttu-id="2a40b-p107">基于角色的 Microsoft Online Services 权限与 Exchange Online RBAC 权限通过以下两种方式重叠。首先，Microsoft Online 中的"全局管理员"或"服务管理员"用户将自动分配给 Exchange Online 中的"组织管理"角色组。其次，Microsoft Online 中的"技术支持管理员"用户将自动分配给 Exchange Online 中的"技术支持"角色组。否则，两种安全模型将分别单独管理。</span><span class="sxs-lookup"><span data-stu-id="2a40b-p107">The role-based permissions for Microsoft Online Services overlap with those of Exchange Online RBAC in two ways. First, users who are Global Administrators or Service Administrators in Microsoft Online are automatically assigned to the Organization Management role group in Exchange Online. Second, users who are Help Desk Administrators in Microsoft Online are automatically assigned to the Help Desk role group in Exchange Online. Otherwise, the two security models are managed separately.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="2a40b-127">Microsoft Exchange Server 2013 内部部署版本中的某些角色在 Exchange Online 中可能不存在。</span><span class="sxs-lookup"><span data-stu-id="2a40b-127">Some roles available in the on-premises version of Microsoft Exchange Server 2013 may not be available in Exchange Online.</span></span> 
  
<span data-ttu-id="2a40b-128">若要详细了解 Exchange Online 中的权限，请参阅[基于角色的权限](/exchange/permissions-exchange-2013-help)。</span><span class="sxs-lookup"><span data-stu-id="2a40b-128">For more information about permissions in Exchange Online, see [Role-Based Permissions](/exchange/permissions-exchange-2013-help).</span></span>
  
## <a name="role-groups"></a><span data-ttu-id="2a40b-129">角色组</span><span class="sxs-lookup"><span data-stu-id="2a40b-129">Role groups</span></span>

<span data-ttu-id="2a40b-130">"管理角色组"可将管理角色与一组管理员或专家用户进行关联。</span><span class="sxs-lookup"><span data-stu-id="2a40b-130">Management role groups associate management roles to a group of administrators or specialist users.</span></span> <span data-ttu-id="2a40b-131">管理员管理众多 Exchange Online 组织或收件人配置。</span><span class="sxs-lookup"><span data-stu-id="2a40b-131">Administrators manage a broad Exchange Online organization or recipient configuration.</span></span> <span data-ttu-id="2a40b-132">专家用户则管理 Exchange Online 的特定功能（如遵从性），或者具备有限的管理能力（如技术支持成员），但没有广泛的管理权限。</span><span class="sxs-lookup"><span data-stu-id="2a40b-132">Specialist users manage the specific features of Exchange Online, such as compliance, or they may have limited management abilities, such as Help desk members, but aren't given broad administrative rights.</span></span> <span data-ttu-id="2a40b-133">角色组通常关联管理管理角色，使管理员和专家用户可以管理其组织和收件人的配置。</span><span class="sxs-lookup"><span data-stu-id="2a40b-133">Role groups typically associate administrative management roles that let administrators and specialist users manage the configuration of their organization and recipients.</span></span> <span data-ttu-id="2a40b-134">例如，管理员能否管理收件人或使用邮箱发现功能是通过角色组控制的。</span><span class="sxs-lookup"><span data-stu-id="2a40b-134">For example, whether administrators can manage recipients or use mailbox discovery features is controlled by using role groups.</span></span> 
  
> [!IMPORTANT]
> <span data-ttu-id="2a40b-135">Microsoft Exchange Server 2013 内部部署版本中的某些角色组在 Exchange Online 中可能不存在。</span><span class="sxs-lookup"><span data-stu-id="2a40b-135">Some role groups available in the on-premises version of Microsoft Exchange Server 2013 may not be available in Exchange Online.</span></span> 
  
<span data-ttu-id="2a40b-136">若要详细了解角色组，请参阅[角色组和角色分配策略](/exchange/permissions-exchange-2013-help)。</span><span class="sxs-lookup"><span data-stu-id="2a40b-136">For more information about role groups, see [Role groups and role assignment policies](/exchange/permissions-exchange-2013-help).</span></span>
  
## <a name="role-assignment-policies"></a><span data-ttu-id="2a40b-137">角色分配策略</span><span class="sxs-lookup"><span data-stu-id="2a40b-137">Role assignment policies</span></span>

<span data-ttu-id="2a40b-p109">管理角色分配策略可将最终用户管理角色与用户进行关联。角色分配策略由角色组成，这些角色可以控制用户可对其邮箱或通讯组执行的操作。这些角色不允许管理未与用户直接关联的功能。创建角色分配策略时，可以定义用户可对其邮箱执行的所有操作。例如，某个角色分配策略可能会允许用户设置显示名、设置语音邮件和配置收件箱规则。另一个角色分配策略可能会允许用户更改地址、使用短信服务以及设置通讯组。默认情况下，每个具有 Exchange Online 邮箱的用户（包括管理员）都会获得一个角色分配策略。您可决定默认情况下应分配哪个角色分配策略、选择默认角色分配策略应包括的内容、忽略某些邮箱的默认策略或默认情况下不分配任何角色分配策略。</span><span class="sxs-lookup"><span data-stu-id="2a40b-p109">Management role assignment policies associate end-user management roles to users. Role assignment policies consist of roles that control what users can do with their mailboxes or distribution groups. These roles don't allow management of features that aren't directly associated with the user. When you create a role assignment policy, you define everything a user can do with his or her mailbox. For example, a role assignment policy might allow a user to set the display name, set up voice mail, and configure Inbox rules. Another role assignment policy might allow a user to change the address, use text messaging, and set up distribution groups. Every user with an Exchange Online mailbox, including administrators, is given a role assignment policy by default. You can decide which role assignment policy should be assigned by default, choose what the default role assignment policy should include, override the default for certain mailboxes, or not assign any role assignment policies by default.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="2a40b-146">Microsoft Exchange Server 2013 内部部署版本中的某些角色分配在 Exchange Online 中可能不存在。</span><span class="sxs-lookup"><span data-stu-id="2a40b-146">Some role assignments available in the on-premises version of Microsoft Exchange Server 2013 may not be available in Exchange Online.</span></span> 
  
<span data-ttu-id="2a40b-147">若要详细了解角色分配策略，请参阅[角色组和角色分配策略](/exchange/permissions-exchange-2013-help)。</span><span class="sxs-lookup"><span data-stu-id="2a40b-147">For more information about role assignment policies, see [Role groups and role assignment policies](/exchange/permissions-exchange-2013-help).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="2a40b-148">功能可用性</span><span class="sxs-lookup"><span data-stu-id="2a40b-148">Feature availability</span></span>

<span data-ttu-id="2a40b-149">若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅Exchange Online[说明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="2a40b-149">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online service description](exchange-online-service-description.md).</span></span>
