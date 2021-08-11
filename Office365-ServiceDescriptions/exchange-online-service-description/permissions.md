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
ms.openlocfilehash: e5a67e8d0c6fc649080ddfa0db7f1909e7d933eb832ad030aa864b8033fd5d39
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/06/2021
ms.locfileid: "54663685"
---
# <a name="permissions"></a>权限

Microsoft Exchange Online 使用基于角色的访问控制 (RBAC) 模型，支持组织管理员有效控制用户和 IT 员工可以在该服务中执行的操作。例如，如果合规专员负责处理邮箱搜索请求，则管理员可通过 RBAC 将此管理功能委派给该专员。Exchange Online 使用与 Microsoft Exchange Server 2013 相同的 RBAC 框架。 
  
在其最高级别中，RBAC 由管理角色、管理角色组和管理角色分配策略组成。以下部分提供有关每个 RBAC 组件的详细信息。
  
若要详细了解 Exchange Online 中使用的 RBAC 权限模型，请参阅[权限](/exchange/permissions-exchange-2013-help)。
  
## <a name="role-based-permissions"></a>基于角色的权限

在 Exchange Online 中，授予管理员和用户的权限基于管理角色。角色定义了管理员或用户可以执行的任务集。例如，名为  `Mail Recipients` 的管理角色定义了某人可以对一组邮箱、联系人和通讯组执行的任务。为管理员或用户分配角色的同时，也会授予此人该角色所提供的权限。 
  
角色分为两种类型，即管理角色和最终用户角色：
  
- **管理角色** 可以使用管理 Exchange Online 组织的一部分（如收件人、服务器或数据库）的角色组，将这些角色包含的权限分配给管理员或专家用户。 
    
- **最终用户角色** 通过使用策略分配这些角色分配，用户可以管理其自己的邮箱及其拥有通讯组的各个方面。 最终用户角色以前缀  `My` 开头。
    
角色通过向已分配角色的用户提供 cmdlet 来授予管理员和用户执行任务的权限。由于 Exchange 管理中心 (EAC) 和 Exchange 命令行管理程序使用 cmdlet 管理 Exchange Online，因此授予对 cmdlet 的访问权限将给予管理员或用户在每个 Exchange Online 管理界面中执行任务的权限。
  
基于角色的 Microsoft Online Services 权限与 Exchange Online RBAC 权限通过以下两种方式重叠。首先，Microsoft Online 中的"全局管理员"或"服务管理员"用户将自动分配给 Exchange Online 中的"组织管理"角色组。其次，Microsoft Online 中的"技术支持管理员"用户将自动分配给 Exchange Online 中的"技术支持"角色组。否则，两种安全模型将分别单独管理。
  
> [!IMPORTANT]
> Microsoft Exchange Server 2013 内部部署版本中的某些角色在 Exchange Online 中可能不存在。 
  
若要详细了解 Exchange Online 中的权限，请参阅[基于角色的权限](/exchange/permissions-exchange-2013-help)。
  
## <a name="role-groups"></a>角色组

"管理角色组"可将管理角色与一组管理员或专家用户进行关联。 管理员管理众多 Exchange Online 组织或收件人配置。 专家用户则管理 Exchange Online 的特定功能（如遵从性），或者具备有限的管理能力（如技术支持成员），但没有广泛的管理权限。 角色组通常关联管理管理角色，使管理员和专家用户可以管理其组织和收件人的配置。 例如，管理员能否管理收件人或使用邮箱发现功能是通过角色组控制的。 
  
> [!IMPORTANT]
> Microsoft Exchange Server 2013 内部部署版本中的某些角色组在 Exchange Online 中可能不存在。 
  
若要详细了解角色组，请参阅[角色组和角色分配策略](/exchange/permissions-exchange-2013-help)。
  
## <a name="role-assignment-policies"></a>角色分配策略

管理角色分配策略可将最终用户管理角色与用户进行关联。角色分配策略由角色组成，这些角色可以控制用户可对其邮箱或通讯组执行的操作。这些角色不允许管理未与用户直接关联的功能。创建角色分配策略时，可以定义用户可对其邮箱执行的所有操作。例如，某个角色分配策略可能会允许用户设置显示名、设置语音邮件和配置收件箱规则。另一个角色分配策略可能会允许用户更改地址、使用短信服务以及设置通讯组。默认情况下，每个具有 Exchange Online 邮箱的用户（包括管理员）都会获得一个角色分配策略。您可决定默认情况下应分配哪个角色分配策略、选择默认角色分配策略应包括的内容、忽略某些邮箱的默认策略或默认情况下不分配任何角色分配策略。
  
> [!IMPORTANT]
> Microsoft Exchange Server 2013 内部部署版本中的某些角色分配在 Exchange Online 中可能不存在。 
  
若要详细了解角色分配策略，请参阅[角色组和角色分配策略](/exchange/permissions-exchange-2013-help)。
  
## <a name="feature-availability"></a>功能可用性

若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅Exchange Online[说明](exchange-online-service-description.md)。
