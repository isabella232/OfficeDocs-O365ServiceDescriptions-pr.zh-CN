---
title: 收件人
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-recipients
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: da22b03a-c981-49c6-9928-4312c2c5e2ee
description: 本主题介绍 Microsoft Exchange Online 中包含的收件人相关功能。 这包括电子邮件、联系人、通讯组、日历和日程安排功能。
ms.openlocfilehash: 5ede65581fc1962a55e565c54509998b9e05b9d0
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173557"
---
# <a name="recipients"></a>收件人

本主题介绍 Microsoft Exchange Online 中包含的收件人相关功能。这包括电子邮件、联系人、通讯组、日历和日程安排功能。
  
## <a name="email"></a>电子邮件

每个 Microsoft Exchange Online 订户将收到一个邮箱，同时为计划设施资源（如会议室）提供专门资源和多用户访问共享电子邮件地址。最大化存储限制适用于大部分邮箱，同时管理员可以控制允许的邮箱大小。自动通知和限制可在用户的邮箱接近或达到最大容量时提醒他们。Exchange Online 还有几种邮件限制类型—邮件大小、消息速率和收件人列表限制。以下提供了所有这些功能和限制的详细信息。
  
> [!NOTE]
> Exchange Online 不再支持 Catch-all 地址。 由于收件人筛选已就地防止潜在垃圾邮件，组织中不存在的电子邮件地址将被拒绝。 
  
### <a name="mailbox-types-storage-limits-and-capacity-alerts"></a>邮箱类型、存储限制和容量警报

对用户可用的邮箱存储量和默认邮箱大小由邮箱类型和用户的订阅许可证确定。管理员可以减小每位用户或全局的最大邮箱大小。Exchange Online 还在用户的邮箱接近或达到最大容量时提供通知。
  
有关详细信息，请参阅 Exchange Online 限制主题中的"邮箱存储限制"和"容量 [警报"部分](exchange-online-limits.md)。
  
### <a name="mailtips"></a>MailTips

邮件提示是当用户正在撰写或定址邮件时自动显示在"收件人:"行上方的参考信息。旨在帮助防止意外发送、违反政策或生成不必要的未送达报告 (NDR)。例如，如果发件人尝试向超大组、包含外部收件人的组或被审阅或限制的通讯组发送邮件，邮件提示可以生成警报。有关详细信息，请参阅 [MailTips](/exchange/clients-and-mobile-in-exchange-online/mailtips/mailtips)（邮件提示）。
  
### <a name="delegate-access"></a>委派访问

Exchange Online 支持委派访问用户允许其他用户管理他们的电子邮件和日历的能力。 委派访问通常用于经理和助理之间，其中助理可以处理经理的入站电子邮件消息并协调经理的计划。 委派访问权限可通过 Outlook 或 Outlook 网页版中的 Exchange Online 用户或 Exchange 管理中心中的管理员启用。 
  
委派有两种类型的访问权限：
  
- **代表发送权限** 委派可以撰写电子邮件消息并在"发件人"字段输入其他人的姓名，其中它将显示为"代表 [人员姓名] 的 [代理人姓名]"。 
    
- **发送为权限** 如果委派是邮箱所有人，委派可以从其他人的邮箱发送邮件。该情景通常用于以下情况：这里有一个共享邮箱，同时几位员工从该共享邮箱而不是他们的 Exchange Online 帐户发送电子邮件消息。 
    
有关委派访问权限的详细信息，请参阅[管理收件人权限](/Exchange/recipients/mailbox-permissions)。
  
### <a name="inbox-rules"></a>收件箱规则

Exchange Online 允许用户创建收件箱规则，在邮件抵达后基于条件对它们自动执行特定操作。 例如，如果邮件被发送给某个通讯组，他们可以创建规则以自动移动所有邮件到特定文件夹。 用户从 Outlook 或 Web 上的 Outlook 管理收件箱规则。 通过禁用服务器端转发和/或服务器端自动回复，管理员可以阻止某些类型的收件箱规则。 例如，禁用服务器端电子邮件转发可以防止用户自动转发电子邮件给个人账户。 同样，禁用服务器端自动回复可以防止外部方使用这些回复识别有效的电子邮件地址。 通过远程 Windows PowerShell 进行这些更改。
  
### <a name="clutter"></a>混乱邮件

待筛选邮件旨在帮助你重点关注收件箱中最重要的邮件。它优先级较低的邮件移除到新的"待筛选邮件"文件夹，使用机器学习从收件箱删除待筛选邮件。待筛选邮件遵循现有的电子邮件规则。因此，如果已创建电子邮件整理规则，这些规则会继续适用，待筛选邮件功能不会对这些邮件产生影响。默认情况下，收件箱禁用待筛选邮件功能。若要了解详细信息，请参阅 [De-clutter your inbox in Office 365](https://go.microsoft.com/fwlink/?linkid=2144145)（在 Office 365 中从收件箱删除待筛选邮件）。
  
### <a name="connected-accounts"></a>已连接帐户

连接帐户功能允许 Exchange Online 用户将外部电子邮件帐户 (如个人帐户) 连接到其 Exchange Online 中的内部电子邮件帐户，然后使用 Outlook 网页版在一个地方与其所有邮件进行交互。 已连接帐户在登录 Outlook 网页时自动同步;用户还可以手动同步 Outlook 网页中的帐户。 通过 [Exchange 管理中心](/exchange/exchange-admin-center)，管理员可以为特定用户或所有用户启用和禁用该功能。
  
### <a name="inactive-mailboxes"></a>非活动邮箱

Exchange Online 提供无限期保留已删除邮箱内容的功能。此功能称为非活动邮箱。如果删除邮箱之前邮箱中设置了就地保留或诉讼保留，则邮箱将变为非活动状态。这会导致无限期保留该邮箱的内容。管理员、合规部主管或记录管理员可以使用 Exchange Online 中的"就地电子数据展示"功能来访问非活动邮箱的内容。
  
启用非活动邮箱要求为邮箱分配 Exchange Online（计划 2）许可证或拥有 Exchange Online Archiving 订阅，这样可以在删除邮箱之前设置"就地保留"或"诉讼保留"功能。
  
> [!IMPORTANT]
> 如果在删除邮箱之前未设置保留功能，则不会保留或发现邮箱的内容。邮箱可以在删除后 30 天内恢复，但是如果未恢复，则 30 天后将永久删除该邮箱及其内容。 
  
有关详细信息，请参阅：
  
- [在 Exchange Online 中管理非活动邮箱](/microsoft-365/security/office-365-security/exchange-online-protection-overview)
    
- [就地保留和诉讼保留](/exchange/security-and-compliance/in-place-and-litigation-holds)
    
- [就地电子数据展示](/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery)
    
## <a name="contacts-and-distribution-groups"></a>联系人和通讯组

### <a name="offline-address-book"></a>脱机通讯簿

脱机通讯簿功能提供 Outlook 全局地址列表和 GAL (Active Directory) 。 它在 Outlook 中本地缓存，以便在用户脱机工作时可用。
  
### <a name="address-book-policies"></a>通讯簿策略

Exchange Online 支持通讯簿策略。 通过通讯簿策略 (ABP)，可以将用户分割成特定的组，以提供组织全局通讯簿 (GAL) 的自定义视图。 在创建 ABP 时，可以为策略指定一个 GAL、一个脱机通讯簿 (OAB)、一个房间列表以及一个或多个地址列表。 然后，可以将 ABP 分配给邮箱用户，从而为他们提供对 Outlook 和 Web 上的 Outlook 中的自定义 GAL 的访问权限。 管理员可以使用远程 Windows PowerShell 来配置通讯簿策略。 若要详细了解通讯簿策略，请参阅 [Exchange Online 中的通讯簿](/exchange/address-books/address-books)。
  
### <a name="address-lists"></a>地址列表

Exchange Online 支持自定义地址列表和 GAL。 GAL 是组织范围内所有启用邮件的用户、通讯组和外部联系人的目录。 管理员可以使用目录同步工具或远程同步工具从 GAL 中隐藏用户、通讯组和Windows PowerShell。
  
### <a name="hierarchical-address-books"></a>分层通讯簿

 通过使用分层通讯簿，最终用户可以利用组织的分层结构浏览 Exchange 组织中的收件人。管理员可以按资历和排名自定义通讯簿，而不是按字母顺序列表。 
  
### <a name="distribution-groups-global"></a>通讯组（全局）

通讯组（或通讯组列表）是对公司所有用户可用的用户、联系人和其他通讯组的集合。 用户定址电子邮件给通讯组别名以发送邮件给该组中的所有人员。 通讯组类似于个人在 Outlook 中创建的个人通讯组，唯一区别是他们的成员列表在公司全局可用。 管理员在 Exchange 管理中心创建通讯组。 还可从内部部署 Active Directory 将该组与 Exchange Online 同步。 它们显示在 Outlook 中的 GAL 中。 Exchange Online 支持高级通讯组功能，包括如下介绍的这些功能：
  
- **限制通讯组** 默认情况下，任何人都可以向任何通讯组发送电子邮件。管理员可以更改权限，仅允许特定个人发送电子邮件给某个组例如，不鼓励不当使用大型通讯组列表。管理员还可以阻止外部源发送电子邮件给通讯组，以帮助防止垃圾邮件。对于使用目录同步工具从内部部署 Active Directory 同步的通讯组，限制属性将自动同步到云。有关详细信息，请参阅 [管理通讯组](/Exchange/recipients/distribution-groups)。
    
- **动态通讯组** 动态通讯组的成员列表（也称为动态通讯组列表，或基于查询的通讯组列表）在每次向组发送邮件时计算。此计算基于管理员定义的筛选器和条件。通过远程 Windows PowerShell 在 Exchange Online 中托管它们。有关动态通讯组的详细信息，请参阅 [管理动态通讯组](/Exchange/recipients/dynamic-distribution-groups/dynamic-distribution-groups)。
    
    > [!IMPORTANT]
    > Office 365 目录同步工具将忽略内部部署 Active Directory 中的动态通讯组，同时不同步这些到 Exchange Online。使用目录同步工具的组织应使用命名约定，避免内部部署托管的普通通讯组和 Exchange Online 托管的动态通讯组之间的冲突。 
  
- **审阅通讯组** 管理员可以选择审阅人以管理到通讯组的邮件流。对于审阅通讯组，任何人可以发送通讯组别名，但在发送邮件给通讯组成员之前，审阅人必须审核并批准它。有关审阅的详细信息，请参阅 [管理通讯组](/Exchange/recipients/distribution-groups)中的"邮件审批"部分。
    
- **自助通讯组** 管理员可允许用户从基于 Web 的界面管理自己的通讯组成员。可以为用户授予权限以创建、删除、加入或离开通讯组。默认情况下，为所有 Exchange Online 用户启用这些功能。管理员可以禁用它们，以便仅 IT 部门可以在需要时管理通讯组。他们还可以创建命名策略，以标准化和管理其用户创建的通讯组名称。例如，他们可以在创建时添加特定前缀或后缀到通讯组名称，或阻止在组名中使用特定单词。 
    
    > [!IMPORTANT]
    > 自助功能对从内部部署 Active Directory 同步到 Exchange Online 的通讯组不可用。使用目录同步的组织应使用命名约定，避免内部部署托管的通讯组和云中托管的动态通讯组之间的冲突。 
  
### <a name="external-contacts-global"></a>外部联系人（全局）

外部联系人是在指定组织之外工作的人员信息的记录。 外部联系人类似于个人在 Outlook 中创建的个人通讯组，唯一区别是他们对公司全局可用。 管理员可以使用 Exchange 管理中心或远程 Windows PowerShell 创建外部联系人。 还可从内部部署 Active Directory 将这些联系人与 Exchange Online 同步。 它们显示在 Outlook 中的 GAL 中。
  
有关外部联系人的详细信息，请参阅[在 Exchange Online 中创建组织关系](/exchange/sharing/organization-relationships/create-an-organization-relationship)。
  
## <a name="calendar-and-scheduling"></a>日历和计划

### <a name="resource-mailboxes"></a>资源邮箱

资源邮箱（如用于会议室和物理设备）代表公司的会议室或其他设施或资源。 用户可以通过将资源的电子邮件别名添加到 Outlook 或 Web 上的 Outlook 中的会议请求来预留会议室或资源。 会议室和资源显示在 Outlook 和 Outlook 网页中的 GAL 中。
  
管理员使用 Exchange 管理中心或远程 Windows PowerShell 创建资源邮箱。该邮箱还可与来自内部部署 Active Directory 的 Exchange Online 同步。
  
有关资源邮箱的详细信息，请参阅：
  
- [创建和管理会议室邮箱](/Exchange/recipients/room-mailboxes)
    
- [管理设备邮箱](/Exchange/recipients/equipment-mailboxes)
    
### <a name="conference-room-management"></a>会议室管理

Exchange Online 包括资源预订助理 (RBA)，这将自动计划会议室和其他资源。已配置 RBA 的资源邮箱将基于资源的日历可用性接受、拒绝或确认来自会议组织者的会议请求。 
  
管理员可以自定义自动会议室响应，并配置 Outlook 网页中的预订策略。 这些策略包括可以计划资源的人员、何时计划资源、什么会议信息在资源日历上可见和允许的计划冲突百分比。 管理员可以禁用资源预订助理并分配特定用户以手动管理会议室的会议请求。
  
管理员必须通过远程 Windows PowerShell 定义和管理 RBA 设置。
  
### <a name="out-of-office-replies"></a>“外出”回复

外出邮件是 Exchange Online 代表用户发送的入站邮件的自动回复。用户可以使用特定开始和结束时间提前计划外出邮件，并为内部和外部收件人单独配置外出邮件。它们还可以从支持该 Exchange ActiveSync 功能的移动设备设置外出邮件。Exchange Online 内的垃圾邮件和邮件列表意识防止用户发送外部外出邮件到扩展邮件列表和潜在垃圾邮件发送者。管理员还可以使用远程 Windows PowerShell 防止用户发送外出邮件给外部用户。
  
### <a name="calendar-sharing"></a>日历共享

用户可以使用以下两种方法之一共享他们的个人日历：
  
- **联合日历共享** 联合身份验证指支持"联盟共享"（Exchange 用户与其他外部联盟组织中的收件人共享闲/忙日历数据和联系人信息的一种简单方法）的基本信任基础结构。 这包括 Exchange Online 组织或运行 Exchange Server 2010 或 Exchange Server 2013 内部部署的组织。 Exchange Online 管理员无需设置与 Microsoft 联合网关的信任，因为在创建 Microsoft 服务时，会为所有 Exchange Online 客户预配置此信任。 默认共享策略允许用户从 Outlook 网页或 Outlook 2010 发送日历共享邀请。 管理员使用远程 Windows PowerShell 禁用该策略，或配置用户可以共享的闲/忙日历数据级别。 管理员还可以创建与另一个联合组织的组织对组织关系，这允许所需闲/忙信息级别对跨组织的每个用户可见，而无需单个用户进行共享邀请。 在管理员定义的共享策略和/或组织对组织关系范围内，用户可以单独进一步限制他们共享的详细信息。 
    
- **Internet 日历共享** Exchange Online 允许用户使用 iCal 格式发布他们的日历，以由组织内外的任何人匿名访问。 收件人可以使用 Exchange（另一个平台）或仅仅使用 Web 浏览器。 Exchange Online 用户还可以订阅其他人通过 iCal 发布到 Internet 位置的日历。 该个人日历共享与联合日历共享不同，它由管理员配置并提供组织对组织的闲/忙共享。 在管理员设置并应用允许共享的策略之前，任何用户都不得以 iCal 格式发布日历数据。 管理员可以使用远程 Windows PowerShell，禁用组织用户的 iCal 发布和 iCal 订阅。
    
有关联合共享的详细信息，请参阅 [Exchange Online 中的共享](/exchange/sharing/sharing)。
  
### <a name="outlook-2010-room-finder"></a>Outlook 2010 会议室查找工具

Exchange Online 支持 Outlook 2010 的会议室查找工具功能，它可将会议室组织成列表（例如，名为"5 号楼会议室"的列表）以便于在安排会议时轻松查找邻近会议室。要显示在房间列表中，通讯组必须使用两种方法之一特别标记： 
  
- 可以使用远程 Windows PowerShell 创建新房间列表。 
    
- 可以通过远程 Windows PowerShell 转换任何仅包含房间的通讯组为房间列表。
    
## <a name="feature-availability"></a>功能可用性

若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅 [Exchange Online 服务说明](exchange-online-service-description.md)。
