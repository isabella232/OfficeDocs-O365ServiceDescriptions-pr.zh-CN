---
title: Exchange Online Archiving 中的合规性功能和安全功能
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- compliance-and-security-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7482322a-39fe-4a99-b29c-63cb1bc3cf1f
ms.openlocfilehash: b03c74e0c760cf22c12e6973a544553d119471fe
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132736"
---
# <a name="compliance-and-security-features-in-exchange-online-archiving"></a>Exchange Online Archiving 中的合规性功能和安全功能

## <a name="compliance-features-in-exchange-online-archiving"></a>Exchange Online Archiving 中的合规性功能

以下部分介绍了 Microsoft Exchange Online Archiving 的合规性功能。
  
### <a name="retention-policies"></a>保留策略

Exchange Online Archiving 提供了保留策略，可帮助组织减少与电子邮件和其他通信有关的义务。 通过这些策略，管理员可以将保留策略应用于用户收件箱中的特定文件夹。 管理员还可以向用户提供保留策略的菜单，并允许他们使用 Outlook 2010 或更高版本或 web 上的 Outlook 将策略应用于特定项目、对话或文件夹。 在 Exchange Online Archiving 中，管理员负责管理内部部署基础结构中的保留策略。
  
Exchange Online Archiving offers two types of policies: archive and delete. Both types can be applied to the same item or folder. For example, a user can tag an email message so that it is automatically moved to the personal archive in a specified number of days and deleted after another span of days.
  
在 Outlook 2010 及更高版本和 web 上的 Outlook 中，用户可以将保留策略应用到文件夹、对话或单个邮件，还可以查看已应用的保留策略和邮件的预期删除日期。 其他电子邮件客户端的用户可根据管理员设置的服务器端保留策略删除或存档电子邮件，但他们的可见性和控制级别并不相同。
  
The retention policy capabilities offered in Exchange Online Archiving are the same as those offered in Exchange Server 2010 Service Pack 2 (SP2) and later. Administrators can manage retention policies from on-premises Exchange Server 2010 and later environments. Managed Folders, an older approach to messaging records management that was introduced in Exchange 2007, are not available in and not compatible with Exchange Online Archiving. For more details, see [Retention Tags and Retention Policies](https://go.microsoft.com/fwlink/p/?LinkID=314153).
  
### <a name="in-place-hold-and-litigation-hold"></a>就地保留和诉讼保留

When a reasonable expectation of litigation exists, organizations are required to preserve electronically stored information (ESI), including email that's relevant to the case. This expectation can occur before the specifics of the case are known, and preservation is often broad. Organizations may preserve all email related to a specific topic, or all email for certain individuals.
  
在 Exchange Online 中，您可以使用就地保留或诉讼保留来完成以下目标：
  
- 允许将用户置于保留中并永久保留邮箱项目
    
- 保留由用户或自动删除过程删除的邮箱项目，例如 MRM
    
- 保护邮箱项目不被用户或通过保存原始项目副本的自动过程篡改、更改
    
- 无限期保留项目或保留特定的持续时间
    
- 通过不必挂起 MRM 使保留对用户是透明的
    
- 使用就地电子数据展示搜索邮箱项目，包括保留项目
    
此外，您可以使用就地保留进行以下操作：
  
- 搜索并保留与指定条件匹配的项目
    
- 将用户置于多个就地保留以用于不同的案件或调查
    
> [!NOTE]
> 当您将邮箱置于就地保留或诉讼保留中时，该保留将置于主邮箱和存档邮箱中。 
  
有关详细信息，请参阅[就地保留和诉讼保留](https://go.microsoft.com/fwlink/p/?LinkId=271746)。
  
> [!NOTE]
> 对于 Exchange Online Archiving 用户，"可恢复的项目"文件夹的默认配额为 100 GB。 
  
### <a name="in-place-ediscovery"></a>就地电子数据展示

Exchange Online Archiving supports In-Place eDiscovery for searching the contents of mailboxes in an organization. Using the Exchange admin center or remote Windows PowerShell from an on-premises Exchange 2013 server, administrators or authorized Discovery managers can search a variety of mailbox items - including email messages, attachments, calendar appointments, tasks, and contacts. In-Place eDiscovery can search simultaneously across primary mailboxes and archives. Rich filtering capabilities include sender, receiver, message types, sent date, received date, carbon copy, and blind carbon copy, along with Keyword Query Language (KQL) syntax. For more details, see [In-Place eDiscovery](https://go.microsoft.com/fwlink/p/?LinkId=314169).
  
The Exchange admin center and remote Windows PowerShell can be used to search up to 5,000 mailboxes at a time in an In-Place eDiscovery search. For details about using remote Windows PowerShell to run In-Place eDiscovery searches, see [New-MailboxSearch](https://go.microsoft.com/fwlink/p/?LinkId=314170). 
  
> [!NOTE]
> In remote Windows PowerShell, the  `Search-Mailbox` cmdlet can be used to search more than 5,000 mailboxes. For details about searching large numbers of mailboxes using remote Windows PowerShell, see [Search-Mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314171). 
  
Results of an In-Place eDiscovery search can be previewed in the Exchange admin center, exported to a .pst file, or copied to a special type of mailbox, called a discovery mailbox. Administrators or compliance officers can connect to the discovery mailbox to review messages. For details, see [Create an In-Place eDiscovery Search](https://go.microsoft.com/fwlink/p/?LinkId=314172).
  
> [!NOTE]
> When copying search results for an In-Place eDiscovery search performed across on-premises and cloud-based mailboxes or archives, you must select an on-premises discovery mailbox. Messages from the on-premises primary mailbox and the cloud-based archive are copied to the on-premises discovery mailbox. 
  
Administrators can also search for and delete inappropriate email messages sent to multiple mailboxes across their organizations. For example, if confidential salary information was accidentally sent to all employees, an administrator can delete the email from the users' mailboxes. This type of search is not available in the Exchange admin center. It must be performed using Remote PowerShell. For details on how to delete messages from users' mailboxes, see [Search and Delete Messages](https://go.microsoft.com/fwlink/p/?LinkId=314173).
  
## <a name="security-features-in-exchange-online-archiving"></a>Exchange Online Archiving 的安全功能

以下部分介绍了 Microsoft Exchange Online Archiving 的安全功能。
  
### <a name="encryption-between-on-premises-servers-and-exchange-online-archiving"></a>在本地服务器和 Exchange Online Archiving 之间加密

TLS 用于加密电子邮件服务器之间的连接，以帮助阻止电子诈骗并为传送中的邮件提供保密性。 TLS 还可用于将本地邮件服务器通信的安全保护到 Microsoft 数据中心以进行 Exchange Online 存档。
  
### <a name="encrypting-between-clients-and-exchange-online-archiving"></a>在客户端和 Exchange Online Archiving 之间加密

到 Exchange Online Archiving 的客户端连接使用以下加密方法来提高安全性：
  
- SSL 用于保护 Outlook、web 上的 Outlook 以及 Exchange Web 服务流量（使用 TCP 端口443）。
    
- 引入 Exchange Online Archiving 并未更改到内部部署服务器的客户端连接。
    
### <a name="encryption-smime-and-pgp"></a>加密：S/MIME 和 PGP

Exchange Online Archiving will store Secure/Multipurpose Internet Mail Extensions (S/MIME) messages. However, Exchange Online Archiving does not host S/MIME functions or host the public keys, nor does it provide key repository, key management, or key directory services because all of these services attach to the on-premises Exchange infrastructure.
  
同样，Exchange Online Archiving 将会存储通过第三方客户端加密解决方案（如 Pretty Good Privacy (PGP)）加密的邮件。
  
### <a name="information-rights-management"></a>信息权限管理

Exchange Online Archiving does not provide hosted Information Rights Management (IRM) services, but administrators can use on-premises Active Directory Rights Management Services (AD RMS). If an AD RMS server is deployed, Outlook can communicate directly with that server, enabling users to compose and read IRM-protected messages. If interoperability between the AD RMS server and the on-premises Exchange environment is configured, users will be able to compose and read IRM-protected messages.
  
#### <a name="support-for-irm-in-outlook-on-the-web"></a>在 Outlook 网页版中支持 IRM

用户可以在 web 上的 Outlook 中以本机方式读取和创建受 IRM 保护的邮件，就像在 Outlook 中一样。 可以通过 Internet Explorer、Firefox、Safari 和 Chrome （无需插件）访问 web 上的 Outlook 中的受 IRM 保护的邮件。 邮件包括全文搜索、会话视图和预览窗格。 要启用此功能，请务必配置 Active Directory 权限管理服务服务器和内部部署 Exchange 环境之间的互操作性。
  
#### <a name="irm-search"></a>IRM 搜索

受 IRM 保护的邮件已编制索引，可以进行搜索，包括标头、主题、正文和附件。 用户可以在 Outlook 和 web 上的 Outlook 中搜索受 IRM 保护的项，管理员可以使用就地电子数据展示或**搜索邮箱**cmdlet 搜索受 irm 保护的项。
  
### <a name="auditing"></a>审核

Exchange Online Archiving 提供两种内置审核功能：
  
- **管理员审核日志记录** 管理员审核日志记录允许客户在 Exchange Online Archiving 环境中跟踪其管理员所做的更改，包括对 RBAC 角色或 Exchange 策略和设置的更改。 
    
- **邮箱审核日志记录** 邮箱审核日志记录允许客户按用户跟踪邮箱访问，而不是根据邮箱所有者进行跟踪。 
    
Several predefined audit reports are available in the Exchange admin center, including Administrator Role Changes, Litigation Hold, and Non-Owner Mailbox Access. Administrators can filter reports by date and role, and they can export all audit events for specified mailboxes in XML format for long-term retention or custom reporting.
  
Administrator audit logging is on by default, and mailbox audit logging is off by default. Administrators can use remote Windows PowerShell to enable mailbox audit logging for some or all mailboxes in their organization. For more information, see [Auditing Reports](https://go.microsoft.com/fwlink/p/?LinkId=314175).
  
## <a name="feature-availability"></a>功能可用性

若要查看跨计划、独立选项和内部部署解决方案的功能可用性，请参阅[Exchange Online 存档服务说明](exchange-online-archiving-service-description.md)。
  

