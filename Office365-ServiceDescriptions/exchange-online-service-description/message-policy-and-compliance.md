---
title: 邮件策略和合规性
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-message-policy-recovery-and-compliance
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5c43c8eb-f8f7-4b5a-a743-b1dab7dc2fc8
ms.openlocfilehash: 806476eb165bb4e98fe5c9d73b878aaa7e32b66c
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/25/2019
ms.locfileid: "33246538"
---
# <a name="message-policy-and-compliance"></a><span data-ttu-id="4469e-102">邮件策略和合规性</span><span class="sxs-lookup"><span data-stu-id="4469e-102">Message Policy and Compliance</span></span>

## <a name="archiving-exchange-online-based-mailboxes"></a><span data-ttu-id="4469e-103">存档基于 Exchange Online 的邮箱</span><span class="sxs-lookup"><span data-stu-id="4469e-103">Archiving Exchange Online-based mailboxes</span></span>

<span data-ttu-id="4469e-p101">Exchange Online 邮箱位于云中，对其进行存档需要独特的托管环境。在有些情况下，也可使用 Exchange Online 来将内部部署的邮箱存档到云中。本节介绍使用 Exchange Online 进行存档的各种选择。</span><span class="sxs-lookup"><span data-stu-id="4469e-p101">Exchange Online mailboxes reside in the cloud, and archiving them requires unique hosting environments. In some cases, Exchange Online can also be used to archive on-premises mailboxes in the cloud. The options for archiving with Exchange Online are described in this section.</span></span>
  
<span data-ttu-id="4469e-p102">Exchange Online 为基于云的邮箱提供了内置存档功能，包括可为用户提供存储较旧电子邮件的便利位置的就地存档。就地存档是一种特殊类型的邮箱，它会随 Outlook 和 Outlook Web App 中的用户主邮箱文件夹一同显示出来。用户可以按他们访问和搜索其主邮箱的相同方式访问和搜索此存档。可用功能取决于所使用的客户端：</span><span class="sxs-lookup"><span data-stu-id="4469e-p102">Exchange Online provides built-in archiving capabilities for cloud-based mailboxes, including an In-Place Archive that gives users a convenient place to store older email messages. An In-Place Archive is a special type of mailbox that appears alongside a user's primary mailbox folders in Outlook and Outlook Web App. Users can access and search the archive in the same way they access and search their primary mailboxes. Available functionality depends on the client in use:</span></span>
  
- <span data-ttu-id="4469e-111">**Outlook 2016、Outlook 2013、Outlook 2010 和 Outlook Web App** 用户可以访问存档的所有功能以及相关的合规性功能，如对保留和存档策略进行控制。</span><span class="sxs-lookup"><span data-stu-id="4469e-111">**Outlook 2016, Outlook 2013, Outlook 2010, and Outlook Web App** Users have access to the full features of the archive, as well as related compliance features like control over retention and archive policies.</span></span> 
    
- <span data-ttu-id="4469e-p103">**Outlook 2007** 用户具有就地存档的基本支持，但不是所有的存档和合规性功能都可用。例如，用户无法将保留或存档策略应用到邮箱中的邮件，而是必须依赖管理员设置的策略。</span><span class="sxs-lookup"><span data-stu-id="4469e-p103">**Outlook 2007** Users have basic support for the In-Place Archive, but not all archiving and compliance features are available. For example, users cannot apply retention or archive policies to mailbox items and must rely on administrator-provisioned policies instead.</span></span> 
    
<span data-ttu-id="4469e-114">管理员使用 Exchange 管理中心或远程 Windows PowerShell 为特定用户启用个人存档功能。</span><span class="sxs-lookup"><span data-stu-id="4469e-114">Administrators use the Exchange admin center or remote Windows PowerShell to enable the personal archive feature for specific users.</span></span>
  
<span data-ttu-id="4469e-115">有关详细信息，请参阅：</span><span class="sxs-lookup"><span data-stu-id="4469e-115">For more information, see:</span></span>
  
- [<span data-ttu-id="4469e-116">Exchange Online 中的存档邮箱</span><span class="sxs-lookup"><span data-stu-id="4469e-116">Archive mailboxes in Exchange Online</span></span>](https://go.microsoft.com/fwlink/p/?LinkId=404421)
    
- [<span data-ttu-id="4469e-117">在 Exchange Online 中启用或禁用存档邮箱</span><span class="sxs-lookup"><span data-stu-id="4469e-117">Enable or disable an archive mailbox in Exchange Online</span></span>](https://go.microsoft.com/fwlink/p/?LinkId=404425)
    
### <a name="archive-sizes"></a><span data-ttu-id="4469e-118">存档大小</span><span class="sxs-lookup"><span data-stu-id="4469e-118">Archive sizes</span></span>

<span data-ttu-id="4469e-p104">每个个人存档中只能存储一个用户的邮件数据。存储空间分配取决于订阅计划。有关存档邮箱大小的详细信息，请参阅[Exchange Online 限制](exchange-online-limits.md)中的"邮箱存储限制"部分。</span><span class="sxs-lookup"><span data-stu-id="4469e-p104">Only one user's messaging data can be stored in each personal archive. The allocation of storage depends on the subscription plan. For more information about archive mailbox sizes, see the "Mailbox storage limits" section in [Exchange Online Limits](exchange-online-limits.md).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="4469e-p105">不允许使用日记、传输规则或自动转发规则将邮件复制到 Exchange Online 邮箱中来进行存档。Microsoft 保留拒绝在个人未使用邮箱存档的情况下进行无限制存档的权利。 > 就地存档对 Outlook 用户有特定的许可要求。Outlook 2007 用户必须具有 2011 年 2 月的 Office 2007 累积更新才能访问个人存档。 > Exchange Online 不支持 Exchange Server 2010 Service Pack 1 或更高版本的  _New-MailboxImportRequest_ Windows PowerShell cmdlet，管理员无法将 .pst 文件导入到个人存档中。如果用户在 Exchange Online 中具有主邮箱和此存档，则管理员可以使用 PST Capture 这款免费工具来将 .pst 文件数据导入到用户的主邮箱或存档中。</span><span class="sxs-lookup"><span data-stu-id="4469e-p105">Using journaling, transport rules, or auto-forwarding rules to copy messages to an Exchange Online mailbox for the purposes of archiving is not permitted. Microsoft reserves the right to deny unlimited archiving in instances where a mailbox archive is not being used in a personal scenario. > In-Place Archive has specific licensing requirements for Outlook users. Outlook 2007 users must have the Office 2007 Cumulative Update for February 2011 to access the personal archive. > Exchange Online does not support the  _New-MailboxImportRequest_ Windows PowerShell cmdlet of Exchange Server 2010 Service Pack 1 or later for administrator-driven import of .pst files into a personal archive. If a user has both the primary mailbox and the archive in Exchange Online, an administrator can use PST Capture, a free tool, to import .pst file data to the user's primary mailbox or archive.</span></span> 
  
## <a name="cloud-based-archiving-of-on-premises-mailboxes"></a><span data-ttu-id="4469e-128">内部部署邮箱的基于云的存档</span><span class="sxs-lookup"><span data-stu-id="4469e-128">Cloud-based archiving of on-premises mailboxes</span></span>

<span data-ttu-id="4469e-p106">通过 Microsoft Exchange Online Archiving（Microsoft 提供的托管存档解决方案），可以对内部部署 Exchange Server 2010 或更高版本的基于云的存档使用 Exchange Online。这要求内部部署组织处于混合模式下，或已针对 Exchange Online Archiving 进行了相关设置。</span><span class="sxs-lookup"><span data-stu-id="4469e-p106">Using Exchange Online for cloud-based archiving of on-premises Exchange Server 2010 or later mailboxes is possible with Microsoft Exchange Online Archiving, a hosted archiving solution from Microsoft. This requires that the on-premises organization be in Hybrid mode or be set up for Exchange Online Archiving.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="4469e-131">在 Exchange 2010 邮箱服务器上具有内部部署邮箱且应用了“托管文件夹”策略的用户无法启用内部部署或基于云的就地存档。</span><span class="sxs-lookup"><span data-stu-id="4469e-131">Users with an on-premises mailbox on an Exchange 2010 Mailbox server who have a Managed Folder policy applied cannot have an on-premises or cloud-based In-Place Archive enabled.</span></span> 
  
## <a name="retention-tags-and-retention-policies"></a><span data-ttu-id="4469e-132">保留标记和保留策略</span><span class="sxs-lookup"><span data-stu-id="4469e-132">Retention tags and retention policies</span></span>

<span data-ttu-id="4469e-p107">Exchange Online 提供了保留策略，可帮助组织减少与电子邮件和其他通信关联的义务。通过这些策略，管理员可以将保留策略应用于用户收件箱中的特定文件夹。管理员也可以为用户提供保留策略的菜单，让他们使用 Outlook 2010 或更高版本或 Outlook Web App 将这些策略应用于特定的项目、会话或文件夹。</span><span class="sxs-lookup"><span data-stu-id="4469e-p107">Exchange Online offers retention policies to help organizations reduce the liabilities associated with email and other communications. With these policies, administrators can apply retention settings to specific folders in users' inboxes. Administrators can also give users a menu of retention policies and let them apply the policies to specific items, conversations, or folders using Outlook 2010 or later or Outlook Web App.</span></span>
  
<span data-ttu-id="4469e-136">在 Exchange Online 中，管理员通过使用 Exchange 管理中心 (EAC) 或远程 Windows PowerShell 管理保留策略。</span><span class="sxs-lookup"><span data-stu-id="4469e-136">In Exchange Online, administrators manage retention policies by using the Exchange admin center (EAC) or remote Windows PowerShell.</span></span>
  
<span data-ttu-id="4469e-p108">Exchange Online 提供了两种类型的策略：存档策略和删除策略。可以在相同的项目或文件夹中结合使用这两种类型。例如，用户可以将某个电子邮件标记为在特定天数之后自动移动到就地存档，并在若干天后自动删除。</span><span class="sxs-lookup"><span data-stu-id="4469e-p108">Exchange Online offers two types of policies: archive policies and delete policies. Both types can be combined on the same item or folder. For example, a user can tag an email message to be automatically moved to the In-Place Archive in a specified number of days and deleted after another span of days.</span></span>
  
<span data-ttu-id="4469e-p109">使用 Outlook 2010 或更高版本和 Outlook Web App，用户可以将保留策略应用到文件夹、会话或各个邮件中。他们也可以查看对邮件应用的保留策略和预期的删除日期。其他电子邮件客户端的用户只能根据管理员设置的服务器端保留策略删除或存档电子邮件。</span><span class="sxs-lookup"><span data-stu-id="4469e-p109">With Outlook 2010 or later and Outlook Web App, users can apply retention policies to folders, conversations, or individual messages. They can also view the applied retention policies and expected deletion dates on messages. Users of other email clients can only have email messages deleted or archived based on server-side retention policies set by the administrator.</span></span>
  
<span data-ttu-id="4469e-p110">Exchange Online 中提供的保留策略功能与 Exchange Server 2010 Service Pack 2 RU4 中的提供的保留策略功能相同。管理员可以使用远程 Windows PowerShell 来将保留策略从内部部署 Exchange Server 2010 或更高版本环境迁移到 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="4469e-p110">The retention policy capabilities offered in Exchange Online are the same as those offered in Exchange Server 2010 Service Pack 2 RU4. Administrators can use remote Windows PowerShell to migrate retention policies from on-premises Exchange Server 2010 or later environments to Exchange Online.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="4469e-145">托管文件夹在 Exchange Online 中不可用，托管文件夹是在 Exchange Server 2007 中引入的一种比较旧的邮件记录管理方法。</span><span class="sxs-lookup"><span data-stu-id="4469e-145">Managed Folders, an older approach to messaging records management that was introduced in Exchange Server 2007, are not available in Exchange Online.</span></span> 
  
<span data-ttu-id="4469e-146">有关详细信息，请参阅[保留标记和保留策略](https://go.microsoft.com/fwlink/p/?LinkId=271745)。</span><span class="sxs-lookup"><span data-stu-id="4469e-146">For more information, see [Retention Tags and Retention Policies](https://go.microsoft.com/fwlink/p/?LinkId=271745).</span></span>
  
## <a name="encryption-of-data-at-rest"></a><span data-ttu-id="4469e-147">静态数据的加密</span><span class="sxs-lookup"><span data-stu-id="4469e-147">Encryption of data at rest</span></span>

<span data-ttu-id="4469e-148">Office 365 客户数据的加密由多个服务端技术提供, 其中包括 BitLocker、DKM、Azure 存储服务加密和 Exchange Online 中的服务加密、Skype for business、OneDrive for business 和 SharePoint隐私声明.</span><span class="sxs-lookup"><span data-stu-id="4469e-148">Encryption of Office 365 customer data at rest is provided by multiple service-side technologies, including BitLocker, DKM, Azure Storage Service Encryption, and service encryption in Exchange Online, Skype for Business, OneDrive for Business, and SharePoint Online.</span></span> <span data-ttu-id="4469e-149">Office 365 服务加密包含一个选项, 可使用存储在 Azure Key Vault 中的客户托管的加密密钥。</span><span class="sxs-lookup"><span data-stu-id="4469e-149">Office 365 Service Encryption include an option to use customer-managed encryption keys that are stored in Azure Key Vault.</span></span> <span data-ttu-id="4469e-150">此客户管理的密钥选项称为[Office 365 customer key](https://go.microsoft.com/fwlink/?linkid=863349), 可用于 Exchange online、SharePoint online 和 OneDrive for business。</span><span class="sxs-lookup"><span data-stu-id="4469e-150">This customer-managed key option, called [Office 365 Customer Key](https://go.microsoft.com/fwlink/?linkid=863349), is available for Exchange Online, SharePoint Online, and OneDrive for Business.</span></span> 
  
### <a name="bitlocker"></a><span data-ttu-id="4469e-151">BitLocker</span><span class="sxs-lookup"><span data-stu-id="4469e-151">BitLocker</span></span>

<span data-ttu-id="4469e-152">Office 365 服务器使用 BitLocker 在卷级别加密包含客户数据的磁盘驱动器。</span><span class="sxs-lookup"><span data-stu-id="4469e-152">Office 365 servers use BitLocker to encrypt the disk drives containing customer data at rest at the volume-level.</span></span> <span data-ttu-id="4469e-153">BitLocker 加密是 Windows 中内置的数据保护功能。</span><span class="sxs-lookup"><span data-stu-id="4469e-153">BitLocker encryption is a data protection feature that is built into Windows.</span></span> <span data-ttu-id="4469e-154">BitLocker 是一种用于预防威胁的技术, 以防发生其他进程或控件 (例如, 对硬件的访问控制或回收) 发生时出现的情况, 从而导致某人能够物理访问包含客户数据的磁盘。</span><span class="sxs-lookup"><span data-stu-id="4469e-154">BitLocker is one of the technologies used to safeguard against threats in case there are lapses in other processes or controls (e.g., access control or recycling of hardware) that could lead to someone gaining physical access to disks containing customer data.</span></span> <span data-ttu-id="4469e-155">在这种情况下, BitLocker 可消除因丢失、被盗或取消授权不当的计算机和磁盘而导致数据失窃或泄露的可能性。</span><span class="sxs-lookup"><span data-stu-id="4469e-155">In this case, BitLocker eliminates the potential for data theft or exposure because of lost, stolen, or inappropriately decommissioned computers and disks.</span></span> 
  
### <a name="distributed-key-manager"></a><span data-ttu-id="4469e-156">分布式密钥管理器</span><span class="sxs-lookup"><span data-stu-id="4469e-156">Distributed Key Manager</span></span>

<span data-ttu-id="4469e-157">除了 BitLocker 之外, 我们还使用一种称为 "分布式密钥管理器" (DKM) 的技术。</span><span class="sxs-lookup"><span data-stu-id="4469e-157">In addition to BitLocker, we use a technology called Distributed Key Manager (DKM).</span></span> <span data-ttu-id="4469e-158">DKM 是一种客户端功能, 它使用一组密钥对信息进行加密和解密。</span><span class="sxs-lookup"><span data-stu-id="4469e-158">DKM is a client-side functionality that uses a set of secret keys to encrypt and decrypt information.</span></span> <span data-ttu-id="4469e-159">只有 Active Directory 域服务中特定安全组的成员才能访问这些密钥以解密由 DKM 加密的数据。</span><span class="sxs-lookup"><span data-stu-id="4469e-159">Only members of a specific security group in Active Directory Domain Services can access those keys to decrypt the data that is encrypted by DKM.</span></span> <span data-ttu-id="4469e-160">在 exchange Online 中, 仅在运行 exchange 进程的特定服务帐户是该安全组的一部分。</span><span class="sxs-lookup"><span data-stu-id="4469e-160">In Exchange Online, only certain service accounts under which the Exchange processes run are part of that security group.</span></span> <span data-ttu-id="4469e-161">作为数据中心中的标准操作过程的一部分, 将不会向任何人提供属于此安全组的凭据, 因此没有人能够访问可以解密这些机密的密钥。</span><span class="sxs-lookup"><span data-stu-id="4469e-161">As part of standard operating procedure in the datacenter, no human is given credentials that are part of this security group and therefore no human has access to the keys that can decrypt these secrets.</span></span>
  
## <a name="customer-key"></a><span data-ttu-id="4469e-162">客户密钥</span><span class="sxs-lookup"><span data-stu-id="4469e-162">Customer Key</span></span>

<span data-ttu-id="4469e-163">使用 "客户密钥", 可以控制组织的加密密钥, 然后配置 Office 365 以使用它们在 Microsoft 数据中心中对静态数据进行加密。</span><span class="sxs-lookup"><span data-stu-id="4469e-163">With Customer Key, you control your organization's encryption keys and then configure Office 365 to use them to encrypt your data at rest in Microsoft's data centers.</span></span> <span data-ttu-id="4469e-164">静态数据包含来自 Exchange online 和 Skype for business 的数据, 这些数据存储在存储在 SharePoint online 和 OneDrive for business 中的邮箱和文件中。</span><span class="sxs-lookup"><span data-stu-id="4469e-164">Data at rest includes data from Exchange Online and Skype for Business that is stored in mailboxes and files that are stored in SharePoint Online and OneDrive for Business.</span></span> <span data-ttu-id="4469e-165">有关详细信息, 请参阅[使用客户密钥和服务加密在 office 365 中控制您的数据](https://go.microsoft.com/fwlink/?linkid=863349),[了解 office 365 常见问题解答](https://go.microsoft.com/fwlink/?linkid=869438)。</span><span class="sxs-lookup"><span data-stu-id="4469e-165">For more information, see [Controlling your data in Office 365 using Customer Key](https://go.microsoft.com/fwlink/?linkid=863349) and [Service Encryption with Customer Key for Office 365 FAQ](https://go.microsoft.com/fwlink/?linkid=869438).</span></span>
  
## <a name="office-365-message-encryption"></a><span data-ttu-id="4469e-166">Office 365 邮件加密</span><span class="sxs-lookup"><span data-stu-id="4469e-166">Office 365 Message Encryption</span></span>
<span data-ttu-id="4469e-167"><a name="bkmk_O365_MessageEncryption"> </a></span><span class="sxs-lookup"><span data-stu-id="4469e-167"></span></span>

<span data-ttu-id="4469e-168">Office 365 邮件加密允许电子邮件用户将加密的电子邮件发送给任何人。</span><span class="sxs-lookup"><span data-stu-id="4469e-168">Office 365 Message Encryption allows email users to send encrypted email messages to anyone.</span></span> <span data-ttu-id="4469e-169">我们宣布了 Office 邮件加密中的新功能, 这些功能利用了 Azure 信息加密中的保护功能。</span><span class="sxs-lookup"><span data-stu-id="4469e-169">We announced new capabilities in Office Message Encryption that leverage the protection features in Azure Information Encryption.</span></span> <span data-ttu-id="4469e-170">这些新功能提供了增强的最终用户体验, 使您可以更轻松地与组织内部或外部的任何人共享和协作处理受保护的邮件。</span><span class="sxs-lookup"><span data-stu-id="4469e-170">These new capabilities provided enhanced end user experiences that make it easier to share and collaborate on protected messages with anyone inside or outside the organization.</span></span> <span data-ttu-id="4469e-171">新的 Office 邮件加密功能具有一些设置要求。</span><span class="sxs-lookup"><span data-stu-id="4469e-171">The new Office Message Encryption capabilities have some setup requirements.</span></span> <span data-ttu-id="4469e-172">请参阅设置基于 Azure 信息保护基础构建的新 Office 365 邮件加密功能。</span><span class="sxs-lookup"><span data-stu-id="4469e-172">See Set up new Office 365 Message Encryption capabilities built on top of Azure Information Protection.</span></span> <span data-ttu-id="4469e-173">旧版 Office 365 邮件加密的客户不会获得上述新功能, 而无需遵循上面提供的指导。</span><span class="sxs-lookup"><span data-stu-id="4469e-173">Customers on legacy Office 365 Message Encryption do not get the new capabilities without following the set up guidance provided above.</span></span> <span data-ttu-id="4469e-174">请阅读[FAQ](https://support.office.com/en-us/article/Office-365-Message-Encryption-FAQ-0432dce9-d9b6-4e73-8a13-4a932eb0081e) , 了解新的与旧版本的 Office 365 邮件加密功能中包含的内容的详细信息。</span><span class="sxs-lookup"><span data-stu-id="4469e-174">Please read the [FAQ](https://support.office.com/en-us/article/Office-365-Message-Encryption-FAQ-0432dce9-d9b6-4e73-8a13-4a932eb0081e) for more details on what's included in the new vs. legacy Office 365 Message Encryption capabilities.</span></span> 
  
## <a name="securemultipurpose-internet-mail-extensions-smime"></a><span data-ttu-id="4469e-175">安全/多用途 Internet 邮件扩展 (S/MIME)</span><span class="sxs-lookup"><span data-stu-id="4469e-175">Secure/Multipurpose Internet Mail Extensions (S/MIME)</span></span>
<span data-ttu-id="4469e-176"><a name="bkmk_O365_MessageEncryption"> </a></span><span class="sxs-lookup"><span data-stu-id="4469e-176"></span></span>

<span data-ttu-id="4469e-p116">借助 S/MIME，您可以通过在组织内发送签名的加密电子邮件来保护敏感信息。在创建 PKI 证书并将其分发给用户后，管理员可以使用远程 Windows PowerShell 设置 S/MIME。必须从本地 Active Directory 证书服务同步这些证书。</span><span class="sxs-lookup"><span data-stu-id="4469e-p116">S/MIME allows you to help protect sensitive information by sending signed and encrypted email within your organization. Administrators can use remote Windows PowerShell to set up S/MIME after establishing and issuing PKI certificates to users. These certificates must be synchronized from an on-premises Active Directory Certificate Service.</span></span>
  
<span data-ttu-id="4469e-p117">Internet Explorer 9 或更高版本支持 S/MIME。目前，Firefox、Opera 和 Chrome 不支持 S/MIME。有关详细信息，请参阅[邮件签名和加密的 S/MIME](https://go.microsoft.com/fwlink/p/?LinkID=393973)。</span><span class="sxs-lookup"><span data-stu-id="4469e-p117">S/MIME is supported on Internet Explorer 9 or later. Currently, S/MIME is unsupported on Firefox, Opera, and Chrome. For more information, see [S/MIME for Message Signing and Encryption](https://go.microsoft.com/fwlink/p/?LinkID=393973).</span></span>
  
## <a name="in-place-hold-and-litigation-hold"></a><span data-ttu-id="4469e-183">就地保留和诉讼保留</span><span class="sxs-lookup"><span data-stu-id="4469e-183">In-Place Hold and Litigation Hold</span></span>
<span data-ttu-id="4469e-184"><a name="bkmk_O365_MessageEncryption"> </a></span><span class="sxs-lookup"><span data-stu-id="4469e-184"></span></span>

<span data-ttu-id="4469e-p118">当存在诉讼的合理预期时，需要组织保留与事实相关的以电子方式存储的信息 (ESI)，包括电子邮件。这种预期可能在知道事实的细节之前发生，并且保留内容通常很广泛。组织可能保留与特定主题相关的所有电子邮件，或特定个人的所有电子邮件。</span><span class="sxs-lookup"><span data-stu-id="4469e-p118">When a reasonable expectation of litigation exists, organizations are required to preserve electronically stored information (ESI), including email that's relevant to the case. This expectation can occur before the specifics of the case are known, and preservation is often broad. Organizations may preserve all email related to a specific topic, or all email for certain individuals.</span></span>
  
<span data-ttu-id="4469e-188">在 Exchange Online 中，您可以使用就地保留或诉讼保留来完成以下目标：</span><span class="sxs-lookup"><span data-stu-id="4469e-188">In Exchange Online, you can use In-Place Hold or Litigation Hold to accomplish the following goals:</span></span>
  
- <span data-ttu-id="4469e-189">允许将用户置于保留中并永久保留邮箱项目</span><span class="sxs-lookup"><span data-stu-id="4469e-189">Enable users to be placed on hold and preserve mailbox items immutably</span></span>
    
- <span data-ttu-id="4469e-190">保留由用户或自动删除过程删除的邮箱项目，例如 MRM</span><span class="sxs-lookup"><span data-stu-id="4469e-190">Preserve mailbox items deleted by users or automatic deletion processes such as MRM</span></span>
    
- <span data-ttu-id="4469e-191">保护邮箱项目不被用户或通过保存原始项目副本的自动过程篡改、更改</span><span class="sxs-lookup"><span data-stu-id="4469e-191">Protect mailbox items from tampering, changes by a user, or automatic processes by saving a copy of the original item</span></span>
    
- <span data-ttu-id="4469e-192">无限期保留项目或保留特定的持续时间</span><span class="sxs-lookup"><span data-stu-id="4469e-192">Preserve items indefinitely or for a specific duration</span></span>
    
- <span data-ttu-id="4469e-193">通过不必挂起 MRM 使保留对用户是透明的</span><span class="sxs-lookup"><span data-stu-id="4469e-193">Keep holds transparent from the user by not having to suspend MRM</span></span>
    
- <span data-ttu-id="4469e-194">使用就地电子数据展示搜索邮箱项目，包括保留项目</span><span class="sxs-lookup"><span data-stu-id="4469e-194">Use In-Place eDiscovery to search mailbox items, including items placed on hold</span></span>
    
<span data-ttu-id="4469e-195">此外，您可以使用就地保留进行以下操作：</span><span class="sxs-lookup"><span data-stu-id="4469e-195">Additionally, you can use In-Place Hold to:</span></span>
  
- <span data-ttu-id="4469e-196">搜索并保留与指定条件匹配的项目</span><span class="sxs-lookup"><span data-stu-id="4469e-196">Search and hold items matching specified criteria</span></span>
    
- <span data-ttu-id="4469e-197">将用户置于多个就地保留以用于不同的案件或调查</span><span class="sxs-lookup"><span data-stu-id="4469e-197">Place a user on multiple In-Place Holds for different cases or investigations</span></span>
    
> [!NOTE]
> <span data-ttu-id="4469e-198">当您将邮箱置于就地保留或诉讼保留中时，该保留将置于主邮箱和存档邮箱中。</span><span class="sxs-lookup"><span data-stu-id="4469e-198">When you put a mailbox on In-Place Hold or Litigation Hold, the hold is placed on both the primary and the archive mailbox.</span></span> 
  
<span data-ttu-id="4469e-199">有关详细信息，请参阅[就地保留和诉讼保留](https://go.microsoft.com/fwlink/p/?LinkId=271746)。</span><span class="sxs-lookup"><span data-stu-id="4469e-199">For more information, see [In-Place Hold and Litigation Hold](https://go.microsoft.com/fwlink/p/?LinkId=271746).</span></span>
  
## <a name="in-place-ediscovery"></a><span data-ttu-id="4469e-200">就地电子数据展示</span><span class="sxs-lookup"><span data-stu-id="4469e-200">In-Place eDiscovery</span></span>
<span data-ttu-id="4469e-201"><a name="bkmk_O365_MessageEncryption"> </a></span><span class="sxs-lookup"><span data-stu-id="4469e-201"></span></span>

<span data-ttu-id="4469e-p119">Exchange Online 可让用户使用基于 Web 的界面在整个组织中搜索邮箱内容。管理员或有权执行就地电子数据展示搜索（通过分配）的合规性和安全性管理人员可以搜索电子邮件、附件、日历约会、任务、联系人和其他项目。就地电子数据展示可以同时搜索主邮箱和存档。丰富的筛选功能包括发件人、收件人、邮件类型、发送/接收日期、抄送/密送以及 KQL 语法。搜索结果也包含"已删除邮件"中的邮件（如果这些邮件与搜索查询条件匹配）。</span><span class="sxs-lookup"><span data-stu-id="4469e-p119">Exchange Online enables customers to search the contents of mailboxes across an organization using a web-based interface. Administrators or compliance and security officials who are authorized to perform In-Place eDiscovery search (by assigning) can search email messages, attachments, calendar appointments, tasks, contacts, and other items. In-Place eDiscovery can search simultaneously across primary mailboxes and archives. Rich filtering capabilities include sender, receiver, message type, sent/receive date, and carbon copy/blind carbon copy, along with KQL Syntax. Search results will also include items in the Deleted Items folder if they match the search query.</span></span>
  
<span data-ttu-id="4469e-p120">就地电子数据展示搜索的结果可以在基于 Web 的界面中预览、导出到 PST 文件中或复制到名为发现邮箱的特殊类型的邮箱中。发现邮箱具有 50 GB 的配额用于存储搜索结果。管理员还可以将 Outlook 连接到发现邮箱以访问搜索结果，并将搜索结果导出到 .pst 文件中。</span><span class="sxs-lookup"><span data-stu-id="4469e-p120">Results of In-Place eDiscovery searches can be previewed in the web-based interface, exported to a PST file or copied to a special type of mailbox called a Discovery mailbox. A Discovery mailbox has a 50 GB quota for storing search results. Administrators can also connect Outlook to the Discovery mailbox to access search results, and export the search results to a .pst file.</span></span>
  
<span data-ttu-id="4469e-p121">管理员可以使用 Exchange 管理中心或远程 Windows PowerShell 来执行多邮箱搜索。Exchange 管理中心可以提供只读的搜索结果预览，让管理员可以快速验证搜索，并在需要时使用不同的参数再次运行此搜索。在优化搜索之后，管理员可以将搜索结果复制到发现邮箱中。</span><span class="sxs-lookup"><span data-stu-id="4469e-p121">Administrators use either the Exchange admin center or remote Windows PowerShell to perform multi-mailbox searches. The Exchange admin center can provide a read-only preview of the search results, enabling administrators to quickly verify a search and rerun it, if needed, with different parameters. Once a search is optimized, the administrator can copy the results to the Discovery mailbox.</span></span>
  
<span data-ttu-id="4469e-p122">默认情况下，为每个组织创建一个发现邮箱，但管理员可以使用远程 Windows PowerShell 创建其他发现邮箱。发现邮箱不能用于存储就地电子数据展示搜索结果之外的任何目的。</span><span class="sxs-lookup"><span data-stu-id="4469e-p122">By default, one Discovery mailbox is created for each organization, but administrators can create additional Discovery mailboxes using remote Windows PowerShell. Discovery mailboxes cannot be used for any purpose other than storing In-Place eDiscovery search results.</span></span>
  
<span data-ttu-id="4469e-p123">管理员可以使用 Exchange 管理中心或远程 Windows PowerShell 来执行就地电子数据展示搜索。Exchange 管理中心可以提供只读的搜索结果预览，让管理员可以快速验证搜索，并在需要时使用不同的参数再次运行此搜索。在优化搜索之后，管理员可以将搜索结果复制到发现邮箱中或将搜索结果导出到 PST 文件中。</span><span class="sxs-lookup"><span data-stu-id="4469e-p123">Administrators use either the Exchange admin center or remote Windows PowerShell to perform In-Place eDiscovery searches. The Exchange admin center can provide a read-only preview of the search results, enabling administrators to quickly verify a search and rerun it, if needed, with different parameters. Once a search is optimized, the administrator can copy the results to the Discovery mailbox or export search results to a PST file.</span></span>
  
<span data-ttu-id="4469e-218">管理员可以使用 Exchange 管理中心或远程 Windows PowerShell 以在就地电子数据展示搜索中一次搜索最多 10,000 个邮箱。</span><span class="sxs-lookup"><span data-stu-id="4469e-218">Administrators can use either the Exchange admin center or remote Windows PowerShell to search up to 10,000 mailboxes at a time in an In-Place eDiscovery search.</span></span> 
  
<span data-ttu-id="4469e-219">在 Exchange Online 中，授权用户可以执行就地电子数据展示并选择以下选项之一：</span><span class="sxs-lookup"><span data-stu-id="4469e-219">In Exchange Online, authorized users can perform In-Place eDiscovery and choose one of the following actions:</span></span>
  
- <span data-ttu-id="4469e-220">**估计搜索结果** 获取搜索会返回的估计邮件数，包括关键字统计信息以确定搜索中使用的关键字有效性并在需要时调整搜索参数。</span><span class="sxs-lookup"><span data-stu-id="4469e-220">**Estimate search results** Get an estimate of the number of messages the search will return, including keywords statistics to determine the effectiveness of keywords used in the search and tweak search parameters if required.</span></span> 
    
- <span data-ttu-id="4469e-221">**预览搜索结果**</span><span class="sxs-lookup"><span data-stu-id="4469e-221">**Preview search results**</span></span>
    
- <span data-ttu-id="4469e-222">将搜索结果中返回的邮件复制到发现邮箱。</span><span class="sxs-lookup"><span data-stu-id="4469e-222">Copy messages returned in search results to a Discovery mailbox.</span></span>
    
<span data-ttu-id="4469e-223">有关详细信息，请参阅[就地电子数据展示](http://go.microsoft.com/fwlink/p/?LinkId=271747)。</span><span class="sxs-lookup"><span data-stu-id="4469e-223">For more information, see [In-Place eDiscovery](http://go.microsoft.com/fwlink/p/?LinkId=271747).</span></span>
  
## <a name="mail-flow-rules"></a><span data-ttu-id="4469e-224">邮件流规则</span><span class="sxs-lookup"><span data-stu-id="4469e-224">Mail flow rules</span></span>
<span data-ttu-id="4469e-225"><a name="bkmk_O365_MessageEncryption"> </a></span><span class="sxs-lookup"><span data-stu-id="4469e-225"></span></span>

<span data-ttu-id="4469e-226">您可以使用邮件流规则来查找通过组织传递的邮件的特定条件并对其进行操作。</span><span class="sxs-lookup"><span data-stu-id="4469e-226">You can use mail flow rules to look for specific conditions on messages that pass through your organization and act on them.</span></span> <span data-ttu-id="4469e-227">邮件流规则允许您对电子邮件应用邮件策略、保护邮件安全、保护邮件系统, 并防止信息泄露。</span><span class="sxs-lookup"><span data-stu-id="4469e-227">Mail flow rules let you apply messaging policies to email messages, secure messages, protect messaging systems, and prevent information leakage.</span></span>
  
<span data-ttu-id="4469e-p125">当今，法律、法规或公司政策要求许多组织应用邮件策略，以便限制组织内部和外部的收件人和发件人之间的交互。除了对个人、组织内部的部门小组以及组织外部的实体之间的交互进行限制以外，某些组织还要满足下列邮件策略要求：</span><span class="sxs-lookup"><span data-stu-id="4469e-p125">Many organizations today are required by law, regulatory requirements, or company policies to apply messaging policies that limit the interaction between recipients and senders, both inside and outside the organization. In addition to limiting interactions among individuals, departmental groups inside the organization, and entities outside the organization, some organizations are also subject to the following messaging policy requirements:</span></span>
  
- <span data-ttu-id="4469e-230">防止不适当的内容进入或离开组织</span><span class="sxs-lookup"><span data-stu-id="4469e-230">Preventing inappropriate content from entering or leaving the organization</span></span>
    
- <span data-ttu-id="4469e-231">筛选机密组织信息</span><span class="sxs-lookup"><span data-stu-id="4469e-231">Filtering confidential organization information</span></span>
    
- <span data-ttu-id="4469e-232">对特定个人发送或接收的邮件进行跟踪或复制</span><span class="sxs-lookup"><span data-stu-id="4469e-232">Tracking or copying messages that are sent to or received from specific individuals</span></span>
    
- <span data-ttu-id="4469e-233">在传递之前重定向入站和出站邮件以便进行检查</span><span class="sxs-lookup"><span data-stu-id="4469e-233">Redirecting inbound and outbound messages for inspection before delivery</span></span>
    
- <span data-ttu-id="4469e-234">对通过组织的邮件应用免责声明</span><span class="sxs-lookup"><span data-stu-id="4469e-234">Applying disclaimers to messages as they pass through the organization</span></span>
    
> [!IMPORTANT]
> <span data-ttu-id="4469e-235">需要在电子邮件服务器上安装第三方 ifilter 的附件文件类型 (如 Adobe .pdf) 无法使用邮件流规则进行检查, 直到安装了相应的 iFilter。</span><span class="sxs-lookup"><span data-stu-id="4469e-235">Attachment file types that require installation of third-party iFilters on the email server (such as Adobe .pdf) cannot be inspected using mail flow rules until after an appropriate iFilter is installed.</span></span> <span data-ttu-id="4469e-236">有关邮件流规则支持的文件类型的详细信息, 请参阅[使用邮件流规则检查 Office 365 中的邮件附件](https://go.microsoft.com/fwlink/p/?LinkId=271748)。</span><span class="sxs-lookup"><span data-stu-id="4469e-236">For more information about file types that are supported by mail flow rules, see [Use mail flow rules to inspect message attachments in Office 365](https://go.microsoft.com/fwlink/p/?LinkId=271748).</span></span> 
  
<span data-ttu-id="4469e-237">有关邮件流规则的详细信息, 请参阅[Exchange 2016 中的邮件流规则](https://go.microsoft.com/fwlink/p/?LinkId=296488)。</span><span class="sxs-lookup"><span data-stu-id="4469e-237">For more information about mail flow rules, see [Mail flow rules in Exchange 2016](https://go.microsoft.com/fwlink/p/?LinkId=296488).</span></span>
  
## <a name="data-loss-prevention"></a><span data-ttu-id="4469e-238">数据丢失防护</span><span class="sxs-lookup"><span data-stu-id="4469e-238">Data loss prevention</span></span>
<span data-ttu-id="4469e-239"><a name="bkmk_O365_MessageEncryption"> </a></span><span class="sxs-lookup"><span data-stu-id="4469e-239"></span></span>

<span data-ttu-id="4469e-p127">防止数据丢失 (DLP) 功能可帮助您通过深入的内容分析标识、监控和保护您组织中的敏感信息。DLP 是一项对于企业邮件系统而言越来越重要的高级功能，因为对于企业非常重要的电子邮件包含需要保护的敏感信息。Exchange Online 中的 DLP 功能可让您保护敏感数据，而不会影响工作人员的生产率。</span><span class="sxs-lookup"><span data-stu-id="4469e-p127">The data loss prevention (DLP) feature will help you identify, monitor, and protect sensitive information in your organization through deep content analysis. DLP is a premium feature that is increasingly important for enterprise message systems because business-critical email includes sensitive data that needs to be protected. The DLP feature in Exchange Online enables you to protect sensitive data without affecting worker productivity.</span></span>
  
<span data-ttu-id="4469e-243">您可以在 Exchange 管理中心 (EAC) 管理界面中配置 DLP 策略，以便您执行下列操作：</span><span class="sxs-lookup"><span data-stu-id="4469e-243">You can configure DLP policies in the Exchange admin center (EAC) management interface, which allows you to:</span></span> 
  
- <span data-ttu-id="4469e-244">启动预配置的策略模板，此模板可帮助您检测特定类型的敏感信息，如 PCI-DSS 数据、格雷姆-里奇-比利雷法案数据，甚至是区域设置特定的个人身份信息 (PII)。</span><span class="sxs-lookup"><span data-stu-id="4469e-244">Start with a pre-configured policy template that can help you detect specific types of sensitive information such as PCI-DSS data, Gramm-Leach-Bliley act data, or even locale-specific personally identifiable information (PII).</span></span>
    
- <span data-ttu-id="4469e-245">使用现有传输规则条件和操作的强大功能，并添加新的传输规则。</span><span class="sxs-lookup"><span data-stu-id="4469e-245">Use the full power of existing transport rule criteria and actions and add new transport rules.</span></span>
    
- <span data-ttu-id="4469e-246">在全面执行前，测试您的 DLP 策略的有效性。</span><span class="sxs-lookup"><span data-stu-id="4469e-246">Test the effectiveness of your DLP policies before fully enforcing them.</span></span>
    
- <span data-ttu-id="4469e-247">整合您自己的自定义 DLP 策略模板和敏感的信息类型。</span><span class="sxs-lookup"><span data-stu-id="4469e-247">Incorporate your own custom DLP policy templates and sensitive information types.</span></span>
    
- <span data-ttu-id="4469e-248">检测邮件附件、正文文本或主题行中的敏感信息, 并调整 Exchange Online 的行为可信度。</span><span class="sxs-lookup"><span data-stu-id="4469e-248">Detect sensitive information in message attachments, body text, or subject lines and adjust the confidence level at which Exchange Online acts.</span></span>
    
- <span data-ttu-id="4469e-p128">通过使用文档指纹检测敏感型数据。文档指纹可以帮助您基于文本形式（您可以用其定义传输规则和 DLP 策略）轻松地创建自定义敏感信息类型。</span><span class="sxs-lookup"><span data-stu-id="4469e-p128">Detect sensitive form data by using Document Fingerprinting. Document Fingerprinting helps you easily create custom sensitive information types based on text-based forms that you can use to define transport rules and DLP policies.</span></span>
    
- <span data-ttu-id="4469e-251">添加策略提示，它可通过向 Outlook 2016、Outlook 2013、Outlook Web App 和适用于设备的 OWA 的用户显示通知来帮助减少数据丢失，还可以通过允许误报报告来提高策略的有效性。</span><span class="sxs-lookup"><span data-stu-id="4469e-251">Add Policy Tips, which can help reduce data loss by displaying a notice to your Outlook 2016, Outlook 2013, Outlook Web App, and OWA for Devices users and can also improve the effectiveness of your policies by allowing false-positive reporting.</span></span> 
    
- <span data-ttu-id="4469e-252">查看 DLP 报告中的事件数据，或通过使用生成事件报告操作来添加自己的特定报告。</span><span class="sxs-lookup"><span data-stu-id="4469e-252">Review incident data in DLP reports or add your own specific reports by using a generate incident report action.</span></span>
    
<span data-ttu-id="4469e-253">有关 DLP 的详细信息，请参阅[数据丢失防护](https://go.microsoft.com/fwlink/p/?LinkId=271749)。</span><span class="sxs-lookup"><span data-stu-id="4469e-253">For more information about DLP, see [Data Loss Prevention](https://go.microsoft.com/fwlink/p/?LinkId=271749).</span></span>
  
## <a name="journaling"></a><span data-ttu-id="4469e-254">日记</span><span class="sxs-lookup"><span data-stu-id="4469e-254">Journaling</span></span>
<span data-ttu-id="4469e-255"><a name="bkmk_O365_MessageEncryption"> </a></span><span class="sxs-lookup"><span data-stu-id="4469e-255"></span></span>

<span data-ttu-id="4469e-p129">您可以配置 Exchange Online，以将电子邮件的副本记录到通过 SMTP 接收邮件的任何外部邮箱中。通过记录入站和出站电子邮件通信，日记功能可以帮助组织对法律、法规和组织遵从性要求做出响应。规划邮件保留和合规性时，了解日记功能及其如何适应组织的合规性策略，这一点非常重要。</span><span class="sxs-lookup"><span data-stu-id="4469e-p129">You can configure Exchange Online to journal copies of emails to any external mailbox that can receive messages via SMTP. Journaling can help your organization respond to legal, regulatory, and organizational compliance requirements by recording inbound and outbound email communications. When planning for messaging retention and compliance, it's important to understand journaling and how it fits in with your organization's compliance policies.</span></span>
  
<span data-ttu-id="4469e-p130">您可以使用 Exchange 管理中心或远程 Windows PowerShell 管理日记规则。您可以按用户和通讯组列表来配置日记，并选择仅记录内部邮件日记、仅记录外部邮件日记或这两者。日记邮件不仅包含原始邮件，还包含有关发件人、收件人、副本和密送副本的信息。</span><span class="sxs-lookup"><span data-stu-id="4469e-p130">You can manage journal rules by using the Exchange admin center or remote Windows PowerShell. You can configure journaling on a per-user and per-distribution list basis, and choose to journal only internal messages, only external messages, or both. Journaled messages include not only the original message but also information about the sender, recipients, copies, and blind copies.</span></span>
  
<span data-ttu-id="4469e-262">若要确保成功且可靠的日记解决方案, 需要完成以下任务:</span><span class="sxs-lookup"><span data-stu-id="4469e-262">To ensure a successful and reliable journaling solution, you need to complete the following tasks:</span></span>
  
- <span data-ttu-id="4469e-263">请确保日记目标不是 Exchange Online 邮箱。</span><span class="sxs-lookup"><span data-stu-id="4469e-263">Make sure that the journaling destination is not be an Exchange Online mailbox.</span></span>
    
- <span data-ttu-id="4469e-264">在客户目录中为要用于日记记录的 SMTP 目标电子邮件地址创建联系人对象。</span><span class="sxs-lookup"><span data-stu-id="4469e-264">Create in the customer directory a contact object for the SMTP target email address to be used for journaling.</span></span>
    
- <span data-ttu-id="4469e-265">将第二个联系人对象创建为备用日记邮箱，用于在主日记邮箱不可用时捕获任何日记报告。</span><span class="sxs-lookup"><span data-stu-id="4469e-265">Create a second contact object as an alternative journal mailbox to capture any journal reports when the primary journal mailbox is unavailable.</span></span>
    
- <span data-ttu-id="4469e-266">维护 SMTP 目标的正确管理、冗余、可用性、性能和功能级别, 以确保始终成功地接受邮件。</span><span class="sxs-lookup"><span data-stu-id="4469e-266">Maintain proper management, redundancy, availability, performance, and functionality levels of the SMTP target to ensure successful mail acceptance always.</span></span>
    
- <span data-ttu-id="4469e-267">提供与 Exchange Server 和 Exchange 传输的具体互操作性，包括邮件格式、发件人/收件人信息集成和正确的内容转换。</span><span class="sxs-lookup"><span data-stu-id="4469e-267">Provide respective interoperability with Exchange Server and Exchange transport including message formats, sender/recipient information integration, and appropriate content conversion.</span></span>
    
<span data-ttu-id="4469e-268">有关日记的详细信息，请参阅[日记](https://go.microsoft.com/fwlink/p/?LinkId=271750)。</span><span class="sxs-lookup"><span data-stu-id="4469e-268">For more information about journaling, see [Journaling](https://go.microsoft.com/fwlink/p/?LinkId=271750).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="4469e-269">功能可用性</span><span class="sxs-lookup"><span data-stu-id="4469e-269">Feature Availability</span></span>
<span data-ttu-id="4469e-270"><a name="bkmk_O365_MessageEncryption"> </a></span><span class="sxs-lookup"><span data-stu-id="4469e-270"></span></span>

<span data-ttu-id="4469e-271">若要查看在各个 Office 365 计划、独立选项和内部部署解决方案之间的功能可用性，请参阅 [Exchange Online 服务说明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="4469e-271">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

