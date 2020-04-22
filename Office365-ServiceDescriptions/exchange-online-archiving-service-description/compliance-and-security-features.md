---
title: Exchange Online Archiving 中的合规性功能和安全功能
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- compliance-and-security-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7482322a-39fe-4a99-b29c-63cb1bc3cf1f
ms.openlocfilehash: b977fea67c28a660a7468945c76d19677769cd8f
ms.sourcegitcommit: 7a68dc894dde0d06fab014c56914a78aa8cda847
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/21/2020
ms.locfileid: "43638690"
---
# <a name="compliance-and-security-features-in-exchange-online-archiving"></a><span data-ttu-id="a3e2f-102">Exchange Online Archiving 中的合规性功能和安全功能</span><span class="sxs-lookup"><span data-stu-id="a3e2f-102">Compliance and security features in Exchange Online Archiving</span></span>

## <a name="compliance-features-in-exchange-online-archiving"></a><span data-ttu-id="a3e2f-103">Exchange Online Archiving 中的合规性功能</span><span class="sxs-lookup"><span data-stu-id="a3e2f-103">Compliance features in Exchange Online Archiving</span></span>

<span data-ttu-id="a3e2f-104">以下部分介绍了 Microsoft Exchange Online Archiving 的合规性功能。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-104">The following sections describe the compliance features of Microsoft Exchange Online Archiving.</span></span>
  
### <a name="retention-policies"></a><span data-ttu-id="a3e2f-105">保留策略</span><span class="sxs-lookup"><span data-stu-id="a3e2f-105">Retention policies</span></span>

<span data-ttu-id="a3e2f-106">Exchange Online Archiving 提供了保留策略，可帮助组织减少与电子邮件和其他通信有关的义务。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-106">Exchange Online Archiving offers retention policies to help organizations reduce the liabilities associated with email and other communications.</span></span> <span data-ttu-id="a3e2f-107">通过这些策略，管理员可以将保留策略应用于用户收件箱中的特定文件夹。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-107">With these policies, administrators can apply retention settings to specific folders in users' inboxes.</span></span> <span data-ttu-id="a3e2f-108">管理员还可以向用户提供保留策略的菜单，并允许他们使用 Outlook 2010 或更高版本或 web 上的 Outlook 将策略应用于特定项目、对话或文件夹。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-108">Administrators can also give users a menu of retention policies and let them apply the policies to specific items, conversations, or folders using Outlook 2010 or later or Outlook on the web.</span></span> <span data-ttu-id="a3e2f-109">在 Exchange Online Archiving 中，管理员负责管理内部部署基础结构中的保留策略。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-109">In Exchange Online Archiving, administrators manage retention policies from the on-premises infrastructure.</span></span>
  
<span data-ttu-id="a3e2f-p102">Exchange Online Archiving 提供两种策略：存档和删除。这两种策略可以应用于相同的项目或文件夹。例如，用户可以标记电子邮件以便在特定天数后自动将其移到个人存档，再过几天后将其删除。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-p102">Exchange Online Archiving offers two types of policies: archive and delete. Both types can be applied to the same item or folder. For example, a user can tag an email message so that it is automatically moved to the personal archive in a specified number of days and deleted after another span of days.</span></span>
  
<span data-ttu-id="a3e2f-113">在 Outlook 2010 及更高版本和 web 上的 Outlook 中，用户可以将保留策略应用到文件夹、对话或单个邮件，还可以查看已应用的保留策略和邮件的预期删除日期。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-113">With Outlook 2010 and later and Outlook on the web, users can apply retention policies to folders, conversations, or individual messages and can also view the applied retention policies and expected deletion dates on messages.</span></span> <span data-ttu-id="a3e2f-114">其他电子邮件客户端的用户可根据管理员设置的服务器端保留策略删除或存档电子邮件，但他们的可见性和控制级别并不相同。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-114">Users of other email clients can have email deleted or archived based on server-side retention policies provisioned by the administrator, but they do not have the same level of visibility and control.</span></span>
  
<span data-ttu-id="a3e2f-p104">Exchange Online Archiving 中提供的保留策略功能与 Exchange Server 2010 Service Pack 2 (SP2) 及更高版本中提供的保留策略功能相同。管理员可以管理本地 Exchange Server 2010 及更高版本环境中的保留策略。托管文件夹是 Exchange 2007 中引入的邮件记录管理旧方法，在 Exchange Online Archiving 中不可用且不兼容。有关详细信息，请参阅[保留标记和保留策略](https://go.microsoft.com/fwlink/p/?LinkID=314153)。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-p104">The retention policy capabilities offered in Exchange Online Archiving are the same as those offered in Exchange Server 2010 Service Pack 2 (SP2) and later. Administrators can manage retention policies from on-premises Exchange Server 2010 and later environments. Managed Folders, an older approach to messaging records management that was introduced in Exchange 2007, are not available in and not compatible with Exchange Online Archiving. For more details, see [Retention Tags and Retention Policies](https://go.microsoft.com/fwlink/p/?LinkID=314153).</span></span>
  
### <a name="in-place-hold-and-litigation-hold"></a><span data-ttu-id="a3e2f-119">就地保留和诉讼保留</span><span class="sxs-lookup"><span data-stu-id="a3e2f-119">In-Place Hold and Litigation Hold</span></span>

<span data-ttu-id="a3e2f-p105">当存在诉讼的合理预期时，需要组织保留与事实相关的以电子方式存储的信息 (ESI)，包括电子邮件。这种预期可能在知道事实的细节之前发生，并且保留内容通常很广泛。组织可能保留与特定主题相关的所有电子邮件，或特定个人的所有电子邮件。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-p105">When a reasonable expectation of litigation exists, organizations are required to preserve electronically stored information (ESI), including email that's relevant to the case. This expectation can occur before the specifics of the case are known, and preservation is often broad. Organizations may preserve all email related to a specific topic, or all email for certain individuals.</span></span>
  
<span data-ttu-id="a3e2f-123">在 Exchange Online 中，您可以使用就地保留或诉讼保留来完成以下目标：</span><span class="sxs-lookup"><span data-stu-id="a3e2f-123">In Exchange Online, you can use In-Place Hold or Litigation Hold to accomplish the following goals:</span></span>
  
- <span data-ttu-id="a3e2f-124">允许将用户置于保留中并永久保留邮箱项目</span><span class="sxs-lookup"><span data-stu-id="a3e2f-124">Enable users to be placed on hold and preserve mailbox items immutably</span></span>
    
- <span data-ttu-id="a3e2f-125">保留由用户或自动删除过程删除的邮箱项目，例如 MRM</span><span class="sxs-lookup"><span data-stu-id="a3e2f-125">Preserve mailbox items deleted by users or automatic deletion processes such as MRM</span></span>
    
- <span data-ttu-id="a3e2f-126">保护邮箱项目不被用户或通过保存原始项目副本的自动过程篡改、更改</span><span class="sxs-lookup"><span data-stu-id="a3e2f-126">Protect mailbox items from tampering, changes by a user, or automatic processes by saving a copy of the original item</span></span>
    
- <span data-ttu-id="a3e2f-127">无限期保留项目或保留特定的持续时间</span><span class="sxs-lookup"><span data-stu-id="a3e2f-127">Preserve items indefinitely or for a specific duration</span></span>
    
- <span data-ttu-id="a3e2f-128">通过不必挂起 MRM 使保留对用户是透明的</span><span class="sxs-lookup"><span data-stu-id="a3e2f-128">Keep holds transparent from the user by not having to suspend MRM</span></span>
    
- <span data-ttu-id="a3e2f-129">使用就地电子数据展示搜索邮箱项目，包括保留项目</span><span class="sxs-lookup"><span data-stu-id="a3e2f-129">Use In-Place eDiscovery to search mailbox items, including items placed on hold</span></span>
    
<span data-ttu-id="a3e2f-130">此外，您可以使用就地保留进行以下操作：</span><span class="sxs-lookup"><span data-stu-id="a3e2f-130">Additionally, you can use In-Place Hold to:</span></span>
  
- <span data-ttu-id="a3e2f-131">搜索并保留与指定条件匹配的项目</span><span class="sxs-lookup"><span data-stu-id="a3e2f-131">Search and hold items matching specified criteria</span></span>
    
- <span data-ttu-id="a3e2f-132">将用户置于多个就地保留以用于不同的案件或调查</span><span class="sxs-lookup"><span data-stu-id="a3e2f-132">Place a user on multiple In-Place Holds for different cases or investigations</span></span>
    
> [!NOTE]
> <span data-ttu-id="a3e2f-133">当您将邮箱置于就地保留或诉讼保留中时，该保留将置于主邮箱和存档邮箱中。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-133">When you put a mailbox on In-Place Hold or Litigation Hold, the hold is placed on both the primary and the archive mailbox.</span></span> 
  
<span data-ttu-id="a3e2f-134">有关详细信息，请参阅[就地保留和诉讼保留](https://go.microsoft.com/fwlink/p/?LinkId=271746)。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-134">For more information, see [In-Place Hold and Litigation Hold](https://go.microsoft.com/fwlink/p/?LinkId=271746).</span></span>
  
> [!NOTE]
> <span data-ttu-id="a3e2f-135">对于 Exchange Online Archiving 用户，"可恢复的项目"文件夹的默认配额为 100 GB。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-135">The default quota for the Recoverable Items Folder is 100 GB for Exchange Online Archiving users.</span></span> 
  
### <a name="in-place-ediscovery"></a><span data-ttu-id="a3e2f-136">就地电子数据展示</span><span class="sxs-lookup"><span data-stu-id="a3e2f-136">In-Place eDiscovery</span></span>

<span data-ttu-id="a3e2f-p106">Exchange Online Archiving 支持就地电子数据展示，可在组织中搜索邮箱内容。通过本地 Exchange 2013 服务器中的 Exchange 管理中心或远程 Windows PowerShell，管理员或或授权的发现管理员可以搜索各种邮箱项目（包括电子邮件、附件、日历约会、任务和联系人）。就地电子数据展示可以同时搜索主邮箱和存档。丰富的筛选功能包括发件人、收件人、邮件类型、发送日期、接收日期、抄送、密送以及关键字查询语言 (KQL) 语法。如需了解更多详情，请参阅[就地电子数据展示](https://go.microsoft.com/fwlink/p/?LinkId=314169)。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-p106">Exchange Online Archiving supports In-Place eDiscovery for searching the contents of mailboxes in an organization. Using the Exchange admin center or remote Windows PowerShell from an on-premises Exchange 2013 server, administrators or authorized Discovery managers can search a variety of mailbox items - including email messages, attachments, calendar appointments, tasks, and contacts. In-Place eDiscovery can search simultaneously across primary mailboxes and archives. Rich filtering capabilities include sender, receiver, message types, sent date, received date, carbon copy, and blind carbon copy, along with Keyword Query Language (KQL) syntax. For more details, see [In-Place eDiscovery](https://go.microsoft.com/fwlink/p/?LinkId=314169).</span></span>
  
<span data-ttu-id="a3e2f-p107">Exchange 管理中心和远程 Windows PowerShell 可用于在就地电子数据展示搜索中一次最多搜索 5,000 个邮箱。若要详细了解如何使用远程 Windows PowerShell 运行就地电子数据展示搜索，请参阅 [New-MailboxSearch](https://go.microsoft.com/fwlink/p/?LinkId=314170)。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-p107">The Exchange admin center and remote Windows PowerShell can be used to search up to 5,000 mailboxes at a time in an In-Place eDiscovery search. For details about using remote Windows PowerShell to run In-Place eDiscovery searches, see [New-MailboxSearch](https://go.microsoft.com/fwlink/p/?LinkId=314170).</span></span> 
  
> [!NOTE]
> <span data-ttu-id="a3e2f-p108">在远程 Windows PowerShell 中， `Search-Mailbox` cmdlet 可用于搜索超过 5,000 个邮箱。若要详细了解如何使用远程 Windows PowerShell 搜索大量邮箱，请参阅 [Search-Mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314171)。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-p108">In remote Windows PowerShell, the  `Search-Mailbox` cmdlet can be used to search more than 5,000 mailboxes. For details about searching large numbers of mailboxes using remote Windows PowerShell, see [Search-Mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314171).</span></span> 
  
<span data-ttu-id="a3e2f-p109">就地电子数据展示搜索的结果可以在 Exchange 管理中心内进行预览、导出到 .pst 文件中或复制到一种特殊类型的邮箱（即发现邮箱）中。管理员或合规部主管可以连接发现邮箱来查看邮件。有关详细信息，请参阅[创建就地电子数据展示搜索](https://go.microsoft.com/fwlink/p/?LinkId=314172)。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-p109">Results of an In-Place eDiscovery search can be previewed in the Exchange admin center, exported to a .pst file, or copied to a special type of mailbox, called a discovery mailbox. Administrators or compliance officers can connect to the discovery mailbox to review messages. For details, see [Create an In-Place eDiscovery Search](https://go.microsoft.com/fwlink/p/?LinkId=314172).</span></span>
  
> [!NOTE]
> <span data-ttu-id="a3e2f-p110">在复制跨内部部署和基于云的邮箱或存档执行的就地电子数据展示搜索的搜索结果时，您必须选择一个内部部署发现邮箱。将内部部署主邮箱和基于云的存档中的邮件复制到内部部署发现邮箱。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-p110">When copying search results for an In-Place eDiscovery search performed across on-premises and cloud-based mailboxes or archives, you must select an on-premises discovery mailbox. Messages from the on-premises primary mailbox and the cloud-based archive are copied to the on-premises discovery mailbox.</span></span> 
  
<span data-ttu-id="a3e2f-p111">管理员还可以搜索并删除发送到跨组织的多个邮箱的不当电子邮件。例如，如果不小心将机密的工资信息发送给了所有员工，管理员可以从用户邮箱中删除此邮件。无法 Exchange 管理中心内执行此类搜索。必须使用远程 PowerShell 执行。若要详细了解如何从用户邮箱中删除邮件，请参阅[搜索和删除邮件](https://go.microsoft.com/fwlink/p/?LinkId=314173)。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-p111">Administrators can also search for and delete inappropriate email messages sent to multiple mailboxes across their organizations. For example, if confidential salary information was accidentally sent to all employees, an administrator can delete the email from the users' mailboxes. This type of search is not available in the Exchange admin center. It must be performed using Remote PowerShell. For details on how to delete messages from users' mailboxes, see [Search and Delete Messages](https://go.microsoft.com/fwlink/p/?LinkId=314173).</span></span>
  
## <a name="security-features-in-exchange-online-archiving"></a><span data-ttu-id="a3e2f-156">Exchange Online Archiving 的安全功能</span><span class="sxs-lookup"><span data-stu-id="a3e2f-156">Security features in Exchange Online Archiving</span></span>

<span data-ttu-id="a3e2f-157">以下部分介绍了 Microsoft Exchange Online Archiving 的安全功能。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-157">The following sections describe the security features of Microsoft Exchange Online Archiving.</span></span>
  
### <a name="encryption-between-on-premises-servers-and-exchange-online-archiving"></a><span data-ttu-id="a3e2f-158">在本地服务器和 Exchange Online Archiving 之间加密</span><span class="sxs-lookup"><span data-stu-id="a3e2f-158">Encryption between on-premises servers and Exchange Online Archiving</span></span>

<span data-ttu-id="a3e2f-159">TLS 用于加密电子邮件服务器之间的连接，以帮助阻止电子诈骗并为传送中的邮件提供保密性。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-159">TLS is used to encrypt the connection between email servers to help prevent spoofing and provide confidentiality for messages in transit.</span></span> <span data-ttu-id="a3e2f-160">TLS 还可用于将本地邮件服务器通信的安全保护到 Microsoft 数据中心以进行 Exchange Online 存档。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-160">TLS is also used for securing on-premises mail server traffic to Microsoft datacenters for Exchange Online Archiving.</span></span>
  
### <a name="encrypting-between-clients-and-exchange-online-archiving"></a><span data-ttu-id="a3e2f-161">在客户端和 Exchange Online Archiving 之间加密</span><span class="sxs-lookup"><span data-stu-id="a3e2f-161">Encrypting between clients and Exchange Online Archiving</span></span>

<span data-ttu-id="a3e2f-162">到 Exchange Online Archiving 的客户端连接使用以下加密方法来提高安全性：</span><span class="sxs-lookup"><span data-stu-id="a3e2f-162">Client connections to Exchange Online Archiving use the following encryption methods to enhance security:</span></span>
  
- <span data-ttu-id="a3e2f-163">SSL 用于保护 Outlook、web 上的 Outlook 以及 Exchange Web 服务流量（使用 TCP 端口443）。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-163">SSL is used for securing Outlook, Outlook on the web, and Exchange Web Services traffic, using TCP port 443.</span></span>
    
- <span data-ttu-id="a3e2f-164">引入 Exchange Online Archiving 并未更改到内部部署服务器的客户端连接。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-164">Client connections to on-premises servers do not change with the introduction of Exchange Online Archiving.</span></span>
    
### <a name="encryption-smime-and-pgp"></a><span data-ttu-id="a3e2f-165">加密：S/MIME 和 PGP</span><span class="sxs-lookup"><span data-stu-id="a3e2f-165">Encryption: S/MIME and PGP</span></span>

<span data-ttu-id="a3e2f-p113">Exchange Online Archiving 将会存储安全/多用途 Internet 邮件扩展 (S/MIME) 邮件。但是，Exchange Online Archiving 不托管 S/MIME 功能或公共密钥，也不提供密钥存储库、密钥管理或关键目录服务，因为这些服务附加在内部部署 Exchange 基础结构上。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-p113">Exchange Online Archiving will store Secure/Multipurpose Internet Mail Extensions (S/MIME) messages. However, Exchange Online Archiving does not host S/MIME functions or host the public keys, nor does it provide key repository, key management, or key directory services because all of these services attach to the on-premises Exchange infrastructure.</span></span>
  
<span data-ttu-id="a3e2f-168">同样，Exchange Online Archiving 将会存储通过第三方客户端加密解决方案（如 Pretty Good Privacy (PGP)）加密的邮件。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-168">Similarly, Exchange Online Archiving will store messages that are encrypted using client-side, third-party encryption solutions such as Pretty Good Privacy (PGP).</span></span>
  
### <a name="information-rights-management"></a><span data-ttu-id="a3e2f-169">信息权限管理</span><span class="sxs-lookup"><span data-stu-id="a3e2f-169">Information Rights Management</span></span>

<span data-ttu-id="a3e2f-p114">Exchange Online Archiving 不提供托管信息权限管理 (IRM) 服务，但管理员可以使用内部部署 Active Directory 权限管理服务 (AD RMS)。如果部署了 AD RMS 服务器，则 Outlook 可以直接与此服务器通信，让用户可以撰写和读取受 IRM 保护的邮件。如果在 AD RMS 服务器和内部部署 Exchange 环境之间配置了互操作性，则用户可以撰写和读取受 IRM 保护的邮件。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-p114">Exchange Online Archiving does not provide hosted Information Rights Management (IRM) services, but administrators can use on-premises Active Directory Rights Management Services (AD RMS). If an AD RMS server is deployed, Outlook can communicate directly with that server, enabling users to compose and read IRM-protected messages. If interoperability between the AD RMS server and the on-premises Exchange environment is configured, users will be able to compose and read IRM-protected messages.</span></span>
  
#### <a name="support-for-irm-in-outlook-on-the-web"></a><span data-ttu-id="a3e2f-173">在 Outlook 网页版中支持 IRM</span><span class="sxs-lookup"><span data-stu-id="a3e2f-173">Support for IRM in Outlook on the web</span></span>

<span data-ttu-id="a3e2f-174">用户可以在 web 上的 Outlook 中以本机方式读取和创建受 IRM 保护的邮件，就像在 Outlook 中一样。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-174">Users can read and create IRM-protected messages natively in Outlook on the web, just as they can in Outlook.</span></span> <span data-ttu-id="a3e2f-175">可以通过 Internet Explorer、Firefox、Safari 和 Chrome （无需插件）访问 web 上的 Outlook 中的受 IRM 保护的邮件。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-175">IRM-protected messages in Outlook on the web can be accessed through Internet Explorer, Firefox, Safari, and Chrome (with no plug-in required).</span></span> <span data-ttu-id="a3e2f-176">邮件包括全文搜索、会话视图和预览窗格。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-176">The messages include full-text search, conversation view, and the preview pane.</span></span> <span data-ttu-id="a3e2f-177">要启用此功能，请务必配置 Active Directory 权限管理服务服务器和内部部署 Exchange 环境之间的互操作性。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-177">Interoperability between the Active Directory Rights Management Services server and the on-premises Exchange environment must be configured to enable this.</span></span>
  
#### <a name="irm-search"></a><span data-ttu-id="a3e2f-178">IRM 搜索</span><span class="sxs-lookup"><span data-stu-id="a3e2f-178">IRM search</span></span>

<span data-ttu-id="a3e2f-179">受 IRM 保护的邮件已编制索引，可以进行搜索，包括标头、主题、正文和附件。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-179">IRM-protected messages are indexed and searchable, including headers, subject, body, and attachments.</span></span> <span data-ttu-id="a3e2f-180">用户可以在 Outlook 和 web 上的 Outlook 中搜索受 IRM 保护的项，管理员可以使用就地电子数据展示或**搜索邮箱**cmdlet 搜索受 irm 保护的项。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-180">Users can search IRM-protected items in Outlook and Outlook on the web, and administrators can search IRM-protected items by using In-Place eDiscovery or the **Search-Mailbox** cmdlet.</span></span>
  
### <a name="auditing"></a><span data-ttu-id="a3e2f-181">审核</span><span class="sxs-lookup"><span data-stu-id="a3e2f-181">Auditing</span></span>

<span data-ttu-id="a3e2f-182">Exchange Online Archiving 提供两种内置审核功能：</span><span class="sxs-lookup"><span data-stu-id="a3e2f-182">Exchange Online Archiving provides two types of built-in auditing capabilities:</span></span>
  
- <span data-ttu-id="a3e2f-183">**管理员审核日志记录** 管理员审核日志记录允许客户在 Exchange Online Archiving 环境中跟踪其管理员所做的更改，包括对 RBAC 角色或 Exchange 策略和设置的更改。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-183">**Administrator audit logging** Administrator audit logging allows customers to track changes made by their administrators in the Exchange Online Archiving environment, including changes to RBAC roles or Exchange policies and settings.</span></span> 
    
- <span data-ttu-id="a3e2f-184">**邮箱审核日志记录** 邮箱审核日志记录允许客户按用户跟踪邮箱访问，而不是根据邮箱所有者进行跟踪。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-184">**Mailbox audit logging** Mailbox audit logging allows customers to track access to mailboxes by users other than the mailbox owner.</span></span> 
    
<span data-ttu-id="a3e2f-p117">Exchange 管理中心提供几个预定义审核报告，包括管理员角色更改、诉讼保留和非所有者邮箱访问。管理员可以按日期和角色筛选报告，用 XML 格式导出指定邮箱的所有审核事件以用于长期保留或自定义报告。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-p117">Several predefined audit reports are available in the Exchange admin center, including Administrator Role Changes, Litigation Hold, and Non-Owner Mailbox Access. Administrators can filter reports by date and role, and they can export all audit events for specified mailboxes in XML format for long-term retention or custom reporting.</span></span>
  
<span data-ttu-id="a3e2f-p118">管理员审核日志记录默认启用，而邮箱审核日志记录则默认禁用。管理员可以使用远程 Windows PowerShell 为组织中的部分或全部邮箱启用邮箱审核日志记录。有关详细信息，请参阅[审核报告](https://go.microsoft.com/fwlink/p/?LinkId=314175)。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-p118">Administrator audit logging is on by default, and mailbox audit logging is off by default. Administrators can use remote Windows PowerShell to enable mailbox audit logging for some or all mailboxes in their organization. For more information, see [Auditing Reports](https://go.microsoft.com/fwlink/p/?LinkId=314175).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="a3e2f-190">功能可用性</span><span class="sxs-lookup"><span data-stu-id="a3e2f-190">Feature availability</span></span>

<span data-ttu-id="a3e2f-191">若要查看跨计划、独立选项和内部部署解决方案的功能可用性，请参阅[Exchange Online 存档服务说明](exchange-online-archiving-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="a3e2f-191">To view feature availability across plans, standalone options, and on-premise solutions, see [Exchange Online Archiving service description](exchange-online-archiving-service-description.md).</span></span>
  

