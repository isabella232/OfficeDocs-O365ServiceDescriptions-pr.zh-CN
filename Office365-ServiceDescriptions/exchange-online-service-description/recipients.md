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
ms.openlocfilehash: a2d1f37bf4f86399522573d18177f6c397fd761c
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132636"
---
# <a name="recipients"></a>收件人

This topic describes recipient-related features included with Microsoft Exchange Online. This includes email, contacts, distribution groups, and calendar and scheduling capabilities.
  
## <a name="email"></a>电子邮件

Every Microsoft Exchange Online subscriber receives a mailbox, and specialty mailboxes are available for scheduling facilities resources (such as conference rooms) and for multiuser access to shared email addresses. Maximum storage limits apply to most mailboxes, and administrators can control allowable mailbox sizes. Automated notifications and restrictions can alert users when their mailboxes are nearing, or at, capacity. Exchange Online also has several types of message limitations—message size, message rate, and recipient list limits. Details of all these features and limits are provided below.
  
> [!NOTE]
> Exchange Online 不再支持 Catch-all 地址。 由于收件人筛选功能可防止潜在的垃圾邮件，因此组织中不存在的电子邮件地址将被拒绝。 
  
### <a name="mailbox-types-storage-limits-and-capacity-alerts"></a>邮箱类型、存储限制和容量警报

The amount of mailbox storage available to a user and the default mailbox size are determined by the mailbox type and the user's subscription license. Administrators can reduce maximum mailbox sizes per user or globally. Exchange Online also provides notifications when a user's mailbox is nearing, or at, capacity.
  
有关详细信息，请参阅[Exchange Online 限制](exchange-online-limits.md)主题中的 "邮箱存储限制" 和 "容量警报" 部分。
  
### <a name="mailtips"></a>邮件提示

MailTips are automated, informative messages that appear above the To: line while users are composing or addressing a message. They are designed to help prevent accidental delivery, policy violations, or unnecessary non-delivery reports (NDRs). For example, MailTips can generate an alert if senders try to send messages to overly large groups, to groups that contain external recipients, or to a distribution group that is moderated or restricted. For more information, see [MailTips](https://go.microsoft.com/fwlink/p/?LinkId=401472).
  
### <a name="delegate-access"></a>委派访问

Exchange Online 支持委派访问用户允许其他用户管理他们的电子邮件和日历的能力。 委派访问通常用于经理和助理之间，其中助理可以处理经理的入站电子邮件消息并协调经理的计划。 代理访问可由 Outlook 或 web 上的 Outlook 中的 Exchange Online 用户或 Exchange 管理中心中的管理员启用。 
  
委派有两种类型的访问权限：
  
- **代表发送权限** 委派可以撰写电子邮件消息并在"发件人"字段输入其他人的姓名，其中它将显示为"代表 [人员姓名] 的 [代理人姓名]"。 
    
- **Send As permissions** The delegate can send messages from the other person's mailbox as if the delegate were the mailbox owner. This scenario is common where there is a shared mailbox and several employees send email messages from that shared mailbox instead of from their Exchange Online accounts. 
    
有关委派访问权限的详细信息，请参阅[管理收件人权限](https://technet.microsoft.com/library/jj919240%28v=exchg.160%29.aspx)。
  
### <a name="inbox-rules"></a>收件箱规则

Exchange Online 允许用户创建收件箱规则，在邮件抵达后基于条件对它们自动执行特定操作。 例如，如果邮件被发送给某个通讯组，他们可以创建规则以自动移动所有邮件到特定文件夹。 用户在 Outlook 或 web 上的 Outlook 中管理收件箱规则。 通过禁用服务器端转发和/或服务器端自动回复，管理员可以阻止某些类型的收件箱规则。 例如，禁用服务器端电子邮件转发可以防止用户自动转发电子邮件给个人账户。 同样，禁用服务器端自动回复可以防止外部方使用这些回复识别有效的电子邮件地址。 通过远程 Windows PowerShell 进行这些更改。
  
### <a name="clutter"></a>混乱邮件

Clutter is designed to help you focus on the most important messages in your inbox. It uses machine learning to de-clutter your inbox by moving lower priority messages out of your way and into a new Clutter folder. Clutter respects your existing email rules, so if you have created rules to organize your email those rules continue to be applied and Clutter won't act on those messages. Clutter is disabled by default for your inbox. To learn more, see [De-clutter your inbox in Office 365](https://www.microsoft.com/en-us/microsoft-365/blog/2014/11/11/de-clutter-inbox-office-365/).
  
### <a name="connected-accounts"></a>已连接帐户

通过 "已连接帐户" 功能，Exchange Online 用户可以将外部电子邮件帐户（如个人帐户）连接到 Exchange Online 中的内部电子邮件帐户，然后使用 web 上的 Outlook 将其所有邮件与一个位置进行交互。 在登录到 Outlook 网页时，已连接的帐户将自动同步。用户还可以手动从 web 上的 Outlook 同步帐户。 通过 [Exchange 管理中心](https://go.microsoft.com/fwlink/?LinkID=785297&amp;clcid=0x409)，管理员可以为特定用户或所有用户启用和禁用该功能。
  
### <a name="inactive-mailboxes"></a>非活动邮箱

Exchange Online provides the capability to preserve the contents of deleted mailboxes indefinitely. This feature is called inactive mailboxes. A mailbox becomes inactive when an In-Place Hold or a Litigation Hold is placed on the mailbox before it's deleted. This results in the contents of the mailbox being preserved indefinitely. Administrators, compliance officers, or record managers can use the In-Place eDiscovery feature in Exchange Online to access the contents of an inactive mailbox.
  
启用非活动邮箱要求为邮箱分配 Exchange Online（计划 2）许可证或拥有 Exchange Online Archiving 订阅，这样可以在删除邮箱之前设置"就地保留"或"诉讼保留"功能。
  
> [!IMPORTANT]
> If a hold isn't placed on a mailbox before it's deleted, the contents of the mailbox will not be preserved or discoverable. The mailbox can be recovered within 30 days of deletion, but the mailbox and its contents will be permanently deleted after 30 days if it isn't recovered. 
  
有关详细信息，请参阅：
  
- [在 Exchange Online 中管理非活动邮箱](https://go.microsoft.com/fwlink/p/?LinkId=286991)
    
- [就地保留和诉讼保留](https://go.microsoft.com/fwlink/p/?LinkId=271746)
    
- [就地电子数据展示](https://go.microsoft.com/fwlink/p/?LinkId=271747)
    
## <a name="contacts-and-distribution-groups"></a>联系人和通讯组

### <a name="offline-address-book"></a>脱机通讯簿

脱机通讯簿功能提供了 Outlook 全局地址列表（GAL）中可用的 Active Directory 信息的快照。 它在 Outlook 中本地缓存，以便在用户脱机工作时可用。
  
### <a name="address-book-policies"></a>通讯簿策略

Exchange Online 支持通讯簿策略。 通过通讯簿策略 (ABP)，可以将用户分割成特定的组，以提供组织全局通讯簿 (GAL) 的自定义视图。 在创建 ABP 时，可以为策略指定一个 GAL、一个脱机通讯簿 (OAB)、一个房间列表以及一个或多个地址列表。 然后，您可以将 ABP 分配给邮箱用户，向他们提供对 Outlook 和 web 上的 Outlook 中的自定义 GAL 的访问权限。 管理员可以使用远程 Windows PowerShell 来配置通讯簿策略。 若要详细了解通讯簿策略，请参阅 [Exchange Online 中的通讯簿](https://go.microsoft.com/fwlink/p/?LinkId=394203)。
  
### <a name="address-lists"></a>地址列表

Exchange Online 支持自定义地址列表和 Gal。 GAL 是所有启用邮件的用户、通讯组和外部联系人的组织范围的目录。 管理员可以使用目录同步工具或远程 Windows PowerShell 来隐藏 GAL 中的用户、通讯组和联系人。
  
### <a name="hierarchical-address-books"></a>分层通讯簿

 Hierarchical address books allow end users to browse for recipients in their Exchange organization using an organizational hierarchy. Administrators can customize the address book by seniority and rank rather than alphabetical listings. 
  
### <a name="distribution-groups-global"></a>通讯组（全局）

通讯组（或通讯组列表）是对公司所有用户可用的用户、联系人和其他通讯组的集合。 用户定址电子邮件给通讯组别名以发送邮件给该组中的所有人员。 通讯组类似于个人在 Outlook 中创建的个人通讯组，唯一区别是他们的成员列表在公司全局可用。 管理员在 Exchange 管理中心创建通讯组。 还可从内部部署 Active Directory 将该组与 Exchange Online 同步。 它们显示在 Outlook 中的 GAL 中。 Exchange Online 支持高级通讯组功能，包括如下介绍的这些功能：
  
- **Restricted distribution groups** By default, anyone can send emails to any distribution group. Administrators can change permissions to allow only specific individuals to send emails to a particular group—for example, to discourage inappropriate use of large distribution lists. Administrators can also block external sources from sending email to distribution groups to help prevent spam. For distribution groups that are synchronized from on-premises Active Directory using the Directory Synchronization tool, the attributes for restriction are synchronized to the cloud automatically. For more information, see [Manage Distribution Groups](https://technet.microsoft.com/library/mt577270%28v=exchg.160%29.aspx).
    
- **Dynamic distribution groups** The membership list for a dynamic distribution group (also known as a dynamic distribution list, or query-based distribution list) is calculated every time a message is sent to the group. This calculation is based on filters and conditions that the administrator defines. They are managed in Exchange Online through remote Windows PowerShell. For more information about dynamic distribution groups, see [Manage Dynamic Distribution Groups](https://technet.microsoft.com/library/bb123722%28v=exchg.160%29.aspx).
    
    > [!IMPORTANT]
    > The Office 365 Directory Synchronization tool ignores dynamic distribution groups in on-premises Active Directory, and does not synchronize these to Exchange Online. Organizations that use the Directory Synchronization tool should use a naming convention that avoids conflicts between the regular distribution groups that are managed on-premises and the dynamic distribution groups that are managed in Exchange Online. 
  
- **Moderated distribution groups** Administrators can select a moderator to regulate the flow of messages to a distribution group. With moderated distribution groups, anyone can email the distribution group alias, but before the message is delivered to the members of the group, a moderator must review and approve it. For more information about moderation, see the Message Approval section in [Manage Distribution Groups](https://technet.microsoft.com/library/mt577270%28v=exchg.160%29.aspx).
    
- **Self-Service distribution groups** Administrators can give users the ability to manage their own distribution group membership from a web-based interface. Users can be given permissions to create, delete, join, or leave distribution groups. These capabilities are enabled by default for all Exchange Online users. Administrators can disable them so that only the IT department can manage distribution groups, if desired. They can also create naming policies to standardize and manage the names of distribution groups that their users create. For example, they can add a specific prefix or suffix to the distribution group name when it is created, or block specific words from being used in the group's name. 
    
    > [!IMPORTANT]
    > Self-service capabilities are not available for distribution groups that are synchronized from on-premises Active Directory to Exchange Online. Organizations that use Directory Synchronization should use a naming convention that avoids conflicts between distribution groups that are managed on-premises and distribution groups that are managed in the cloud. 
  
### <a name="external-contacts-global"></a>外部联系人（全局）

外部联系人是在指定组织之外工作的人员信息的记录。 外部联系人类似于个人在 Outlook 中创建的个人通讯组，唯一区别是他们对公司全局可用。 管理员可以使用 Exchange 管理中心或远程 Windows PowerShell 创建外部联系人。 还可从内部部署 Active Directory 将这些联系人与 Exchange Online 同步。 它们显示在 Outlook 中的 GAL 中。
  
有关外部联系人的详细信息，请参阅[在 Exchange Online 中创建组织关系](https://technet.microsoft.com/library/jj916671%28v=exchg.150%29.aspx)。
  
## <a name="calendar-and-scheduling"></a>日历和计划

### <a name="resource-mailboxes"></a>资源邮箱

资源邮箱（如用于会议室和物理设备）代表公司的会议室或其他设施或资源。 用户可以通过在 Outlook 或 web 上的 Outlook 中将资源的电子邮件别名添加到会议请求中，来保留会议室或资源。 会议室和资源显示在 Outlook 和 web 上的 Outlook 中的 GAL 中。
  
Administrators create resource mailboxes using the Exchange admin center or remote Windows PowerShell. The mailboxes can also be synchronized with Exchange Online from on-premises Active Directory.
  
有关资源邮箱的详细信息，请参阅：
  
- [创建和管理会议室邮箱](https://go.microsoft.com/fwlink/?LinkId=717533&amp;clcid=0x409)
    
- [管理设备邮箱](https://go.microsoft.com/fwlink/?LinkId=717534)
    
### <a name="conference-room-management"></a>会议室管理

Exchange Online includes the Resource Booking Attendant (RBA), which automates scheduling of conference rooms and other resources. A resource mailbox that is RBA-configured accepts, declines, or acknowledges meeting requests from a meeting organizer based on the resource's calendar availability. 
  
管理员可以自定义自动会议室响应，并在 web 上的 Outlook 中配置预订策略。 这些策略包括可以计划资源的人员、何时计划资源、什么会议信息在资源日历上可见和允许的计划冲突百分比。 管理员可以禁用资源预订助理并分配特定用户以手动管理会议室的会议请求。
  
管理员必须通过远程 Windows PowerShell 定义和管理 RBA 设置。
  
### <a name="out-of-office-replies"></a>“外出”回复

Out-of-office messages are automatic replies to incoming messages that Exchange Online sends on behalf of a user. Users can schedule out-of-office messages in advance, with specific start and end times, and can configure separate out-of-office messages for internal and external recipients. They can also set out-of-office messages from mobile devices that support this Exchange ActiveSync feature. Junk-email and mailing-list awareness within Exchange Online prevents users from sending external out-of-office messages to extended mailing lists and potential spammers. Administrators can also prevent users from sending out-of-office messages to external users using remote Windows PowerShell.
  
### <a name="calendar-sharing"></a>日历共享

用户可以使用以下两种方法之一共享他们的个人日历：
  
- **联合日历共享** 联合身份验证指支持"联盟共享"（Exchange 用户与其他外部联盟组织中的收件人共享闲/忙日历数据和联系人信息的一种简单方法）的基本信任基础结构。 这包括 Exchange Online 组织或运行 Exchange Server 2010 或 Exchange Server 2013 内部部署的组织。 Exchange Online 管理员无需设置与 Microsoft 联合网关的信任，因为在创建 Microsoft 服务时，将为所有 Exchange Online 客户预配置此信任。 默认共享策略允许用户从 web 或 Outlook 2010 发送来自 Outlook 的日历共享邀请。 管理员使用远程 Windows PowerShell 禁用该策略，或配置用户可以共享的闲/忙日历数据级别。 管理员还可以创建与另一个联合组织的组织对组织关系，这允许所需闲/忙信息级别对跨组织的每个用户可见，而无需单个用户进行共享邀请。 在管理员定义的共享策略和/或组织对组织关系范围内，用户可以单独进一步限制他们共享的详细信息。 
    
- **Internet 日历共享** Exchange Online 允许用户使用 iCal 格式发布他们的日历，以由组织内外的任何人匿名访问。 收件人可以使用 Exchange（另一个平台）或仅仅使用 Web 浏览器。 Exchange Online 用户也可以通过 iCal 订阅其他人已发布到 internet 位置的日历。 该个人日历共享与联合日历共享不同，它由管理员配置并提供组织对组织的闲/忙共享。 任何用户都不能以 iCal 格式发布日历数据，直到管理员设置并应用了允许它的共享策略。 管理员可以使用远程 Windows PowerShell，禁用组织用户的 iCal 发布和 iCal 订阅。
    
有关联合共享的详细信息，请参阅 [Exchange Online 中的共享](https://go.microsoft.com/fwlink/p/?LinkId=271774)。
  
### <a name="outlook-2010-room-finder"></a>Outlook 2010 会议室查找工具

Exchange Online supports the Room Finder feature of Outlook 2010, which arranges rooms into lists (for example, a list called "Building 5 rooms") to make it easier to find a nearby room when scheduling a meeting. To appear in the room list, a distribution group must be specially marked using one of two methods: 
  
- 可以使用远程 Windows PowerShell 创建新房间列表。 
    
- 可以通过远程 Windows PowerShell 转换任何仅包含房间的通讯组为房间列表。
    
## <a name="feature-availability"></a>功能可用性

若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅[Exchange Online 服务说明](exchange-online-service-description.md)。
  