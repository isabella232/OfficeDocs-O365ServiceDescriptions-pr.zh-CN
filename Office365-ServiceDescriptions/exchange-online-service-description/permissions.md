---
title: 权限
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-permissions
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7803d7c0-93e6-43a2-b2a4-3a39abe25500
description: Microsoft Exchange Online uses a Role Based Access Control (RBAC) model to allow organization administrators to finely control what users and IT employees can do in the service. For example, if a compliance officer is responsible for mailbox search requests, the administrator can delegate this administrative feature to the officer through RBAC. Exchange Online uses the same RBAC framework as Microsoft Exchange Server 2013.
ms.openlocfilehash: 0593c98857a7ce0c487c628018097395d7a5fe50
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132686"
---
# <a name="permissions"></a>权限

Microsoft Exchange Online uses a Role Based Access Control (RBAC) model to allow organization administrators to finely control what users and IT employees can do in the service. For example, if a compliance officer is responsible for mailbox search requests, the administrator can delegate this administrative feature to the officer through RBAC. Exchange Online uses the same RBAC framework as Microsoft Exchange Server 2013. 
  
At its highest level, RBAC is made up of management roles, management role groups, and management role assignment policies. The following sections provide more information about each RBAC component.
  
若要详细了解 Exchange Online 中使用的 RBAC 权限模型，请参阅[权限](https://go.microsoft.com/fwlink/p/?LinkId=271935)。
  
## <a name="role-based-permissions"></a>基于角色的权限

In Exchange Online, the permissions that you grant to administrators and users are based on management roles. A role defines the set of tasks that an administrator or user can perform. For example, a management role called  `Mail Recipients` defines the tasks that someone can perform on a set of mailboxes, contacts, and distribution groups. When a role is assigned to an administrator or user, that person is granted the permissions provided by the role. 
  
角色分为两种类型，即管理角色和最终用户角色：
  
- **管理角色** 可以使用管理 Exchange Online 组织的一部分（如收件人、服务器或数据库）的角色组，将这些角色包含的权限分配给管理员或专家用户。 
    
- **最终用户角色**通过使用角色分配策略分配的这些角色，使用户可以管理自己的邮箱及其拥有的通讯组的各个方面。 最终用户角色以前缀  `My` 开头。
    
Roles give administrators and users permissions to perform tasks by making cmdlets available to those who are assigned the roles. Because the Exchange admin center (EAC) and Exchange Management Shell use cmdlets to manage Exchange Online, granting access to a cmdlet gives the administrator or user permission to perform the task in each of the Exchange Online management interfaces.
  
The role-based permissions for Microsoft Online Services overlap with those of Exchange Online RBAC in two ways. First, users who are Global Administrators or Service Administrators in Microsoft Online are automatically assigned to the Organization Management role group in Exchange Online. Second, users who are Help Desk Administrators in Microsoft Online are automatically assigned to the Help Desk role group in Exchange Online. Otherwise, the two security models are managed separately.
  
> [!IMPORTANT]
> Microsoft Exchange Server 2013 内部部署版本中的某些角色在 Exchange Online 中可能不存在。 
  
若要详细了解 Exchange Online 中的权限，请参阅[基于角色的权限](https://go.microsoft.com/fwlink/p/?LinkId=271936)。
  
## <a name="role-groups"></a>角色组

"管理角色组"可将管理角色与一组管理员或专家用户进行关联。 管理员管理众多 Exchange Online 组织或收件人配置。 专家用户则管理 Exchange Online 的特定功能（如遵从性），或者具备有限的管理能力（如技术支持成员），但没有广泛的管理权限。 角色组通常会关联管理管理角色，以便管理员和专家用户可以管理其组织和收件人的配置。 例如，管理员能否管理收件人或使用邮箱发现功能是通过角色组控制的。 
  
> [!IMPORTANT]
> Microsoft Exchange Server 2013 内部部署版本中的某些角色组在 Exchange Online 中可能不存在。 
  
若要详细了解角色组，请参阅[角色组和角色分配策略](https://go.microsoft.com/fwlink/p/?LinkId=271937)。
  
## <a name="role-assignment-policies"></a>角色分配策略

Management role assignment policies associate end-user management roles to users. Role assignment policies consist of roles that control what users can do with their mailboxes or distribution groups. These roles don't allow management of features that aren't directly associated with the user. When you create a role assignment policy, you define everything a user can do with his or her mailbox. For example, a role assignment policy might allow a user to set the display name, set up voice mail, and configure Inbox rules. Another role assignment policy might allow a user to change the address, use text messaging, and set up distribution groups. Every user with an Exchange Online mailbox, including administrators, is given a role assignment policy by default. You can decide which role assignment policy should be assigned by default, choose what the default role assignment policy should include, override the default for certain mailboxes, or not assign any role assignment policies by default.
  
> [!IMPORTANT]
> Microsoft Exchange Server 2013 内部部署版本中的某些角色分配在 Exchange Online 中可能不存在。 
  
若要详细了解角色分配策略，请参阅[角色组和角色分配策略](https://go.microsoft.com/fwlink/p/?LinkId=271937)。
  
## <a name="feature-availability"></a>功能可用性

若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅[Exchange Online 服务说明](exchange-online-service-description.md)。
  

