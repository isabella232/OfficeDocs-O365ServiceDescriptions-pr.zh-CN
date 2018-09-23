---
title: 共享和协作
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-sharing-and-collaboration
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 862dab54-701f-4014-a594-0b71e03772d2
ms.openlocfilehash: 13ab2163b76b5ccc4732659a64be5fcead01dc9d
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035049"
---
# <a name="sharing-and-collaboration"></a><span data-ttu-id="2e907-102">共享和协作</span><span class="sxs-lookup"><span data-stu-id="2e907-102">Sharing and Collaboration</span></span>

## <a name="federated-sharing"></a><span data-ttu-id="2e907-103">联合共享</span><span class="sxs-lookup"><span data-stu-id="2e907-103">Federated sharing</span></span>

<span data-ttu-id="2e907-p101">"联合身份验证"指支持"联合共享"（Microsoft Exchange Online 用户与其他外部联盟组织中的收件人或具有 Internet 访问权限的用户共享忙/闲日历数据和联系人信息的一种方法）的基本信任基础结构。这些组织还包括由 Exchange Online、外部 Microsoft Exchange Server 2010 或 Exchange Server 2013 组织托管的组织。通过使用组织关系和共享策略，Exchange Online 管理员使用户能够从 Microsoft Outlook Web App、Microsoft Outlook 2010 或更高版本中发送日历共享邀请。</span><span class="sxs-lookup"><span data-stu-id="2e907-p101">Federation refers to the underlying trust infrastructure that supports federated sharing, a method for Microsoft Exchange Online users to share free/busy calendar data and contact information with recipients in other external federated organizations or with users that have Internet access. These include organizations that are also hosted by Exchange Online, or external Microsoft Exchange Server 2010 or Exchange Server 2013 organizations. Using organization relationships and sharing policies, Exchange Online administrators can enable users to send calendar-sharing invitations from Microsoft Outlook Web App or Microsoft Outlook 2010 or later.</span></span>
  
> [!IMPORTANT]
>  <span data-ttu-id="2e907-p102">外部 Exchange 2010 和 Exchange 2013 组织必须将使用 Microsoft 联合身份验证网关的联合身份验证信任作为配置联合共享的一部分加以配置。由于创建 Office 365 租户时，系统将自动创建使用 Microsoft 联合身份验证网关的联合身份验证信任，因此，Exchange Online 组织无需再配置。 >  Exchange Online 组织必须配置组织关系或共享策略，以支持联合共享。 >  联合共享不支持共享全局访问列表 (GAL)，亦不支持在 Office 365 的不同租户中的 Exchange Online 组织之间移动用户邮箱。</span><span class="sxs-lookup"><span data-stu-id="2e907-p102">External Exchange 2010 and Exchange 2013 organizations must configure a federation trust with the Microsoft Federation Gateway as part of configuring federated sharing. Exchange Online organizations don't have to configure a federation trust—the federation trust with the Microsoft Federation Gateway is automatically created when the Office 365 tenant is created. >  Exchange Online organizations must configure either an organization relationship or a sharing policy to enable federated sharing. >  Sharing of the global access list (GAL) or moving user mailboxes between Exchange Online organizations in different Office 365 tenants is not supported in federated sharing.</span></span> 
  
<span data-ttu-id="2e907-111">有关联合共享的详细信息，请参阅 [Exchange Online 中的共享](https://go.microsoft.com/fwlink/p/?LinkId=271774)。</span><span class="sxs-lookup"><span data-stu-id="2e907-111">For more information about federated sharing, see [Sharing in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271774).</span></span>
  
## <a name="site-mailboxes"></a><span data-ttu-id="2e907-112">站点邮箱</span><span class="sxs-lookup"><span data-stu-id="2e907-112">Site mailboxes</span></span>

<span data-ttu-id="2e907-p103">电子邮件和文档传统上保存在两个唯一且单独的数据存储库中。大多数团队通过使用电子邮件和文档进行协作。难题在于使用不同的客户端访问电子邮件和文档。这通常会导致用户工作效率降低和用户体验降级。</span><span class="sxs-lookup"><span data-stu-id="2e907-p103">Email and documents are traditionally kept in two unique and separate data repositories. Most teams collaborate by using both email and documents. The challenge is that email and documents are accessed by using different clients. This usually results in a reduction in user productivity and a degraded user experience.</span></span>
  
<span data-ttu-id="2e907-p104">站点邮箱是 Exchange 2013 中尝试解决此问题的新概念。站点邮箱通过允许使用相同客户端接口同时访问 Microsoft SharePoint 2013 文档和 Exchange 电子邮件，从而改进协作和用户工作效率。站点邮箱在功能上由 SharePoint 2013 网站成员资格（所有者和成员）、共享存储（对于电子邮件，通过 Exchange 2013 邮箱来实现，对于文档则通过 SharePoint 2013 站点来实现）以及满足设置和生命周期需求的管理接口组成。</span><span class="sxs-lookup"><span data-stu-id="2e907-p104">The site mailbox is a new concept in Exchange 2013 that attempts to solve this problem. Site mailboxes improve collaboration and user productivity by using the same client interface to allow access to both Microsoft SharePoint 2013 documents and Exchange email. A site mailbox functionally consists of SharePoint 2013 site membership (owners and members), shared storage through an Exchange 2013 mailbox for email messages and a SharePoint 2013 site for documents, and a management interface that addresses provisioning and life cycle needs.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="2e907-p105">Office 365 计划必须包括 SharePoint。站点邮箱要求用户具有 SharePoint 和 Exchange 的许可证。</span><span class="sxs-lookup"><span data-stu-id="2e907-p105">Your Office 365 plan must include SharePoint. Site mailboxes require that users have both SharePoint and Exchange licenses.</span></span> 
  
<span data-ttu-id="2e907-122">有关网站邮箱的详细信息，请参阅[网站邮箱](https://go.microsoft.com/fwlink/p/?LinkId=271789)。</span><span class="sxs-lookup"><span data-stu-id="2e907-122">For more information about site mailboxes, see [Site Mailboxes](https://go.microsoft.com/fwlink/p/?LinkId=271789).</span></span>
  
## <a name="public-folders"></a><span data-ttu-id="2e907-123">公用文件夹</span><span class="sxs-lookup"><span data-stu-id="2e907-123">Public folders</span></span>

<span data-ttu-id="2e907-p106">Exchange Online 中的公用文件夹具有已得到改进利用现有高可用性和存储技术的邮箱数据库。公用文件夹体系结构使用专门设计的邮箱存储层次结构和公用文件夹内容。这意味着不再存在一个单独的公用文件夹数据库。公用文件夹复制现在使用连续复制模型。由数据库可用性组 (DAG) 中的数据中心提供高可用性的层次结构和内容的邮箱。在 Exchange Online 中，您仅限于 1000年公用文件夹邮箱。每个公用文件夹邮箱还具有最大存储大小。有关详细信息，请参阅[Exchange Online 限制](exchange-online-limits.md)中的"邮箱文件夹限制"部分。公用文件夹邮箱有相同的邮件、 收件人和容量警报限制为正则邮箱。有关详细信息，请参阅[Recipients](recipients.md)。</span><span class="sxs-lookup"><span data-stu-id="2e907-p106">Public folders in Exchange Online have been modernized to take advantage of the existing high availability and storage technologies of the mailbox database. The public folder architecture uses specially designed mailboxes to store both the hierarchy and the public folder content. This means that there's no longer a separate public folder database. Public folder replication now uses the continuous replication model. High availability for the hierarchy and content mailboxes is provided by a database availability group (DAG) in the data center. In Exchange Online, you are limited to 1000 public folder mailboxes. Each public folder mailbox also has a maximum storage size. For more information, see the "Mailbox folder limits" section in [Exchange Online Limits](exchange-online-limits.md). Public folder mailboxes have the same message, recipient, and capacity alert limits as regular mailboxes. For more information, see [Recipients](recipients.md).</span></span> 
  
<span data-ttu-id="2e907-134">有关公用文件夹的详细信息，请参阅[公用文件夹](https://go.microsoft.com/fwlink/p/?LinkId=271790)。</span><span class="sxs-lookup"><span data-stu-id="2e907-134">For more information about public folders, see [Public Folders](https://go.microsoft.com/fwlink/p/?LinkId=271790).</span></span>
  
## <a name="group-and-shared-mailboxes"></a><span data-ttu-id="2e907-135">组邮箱和共享邮箱</span><span class="sxs-lookup"><span data-stu-id="2e907-135">Group and Shared mailboxes</span></span>

<span data-ttu-id="2e907-p107">组邮箱和共享邮箱可让特定的人员组方便地通过公共帐户（例如 info@contoso.com 或 contact@contoso.com）监视和发送电子邮件。如果组中有人回复发送至共享邮箱的邮件，则该电子邮件可能是从共享邮箱发送而不是从单个用户发送。</span><span class="sxs-lookup"><span data-stu-id="2e907-p107">Group and Shared mailboxes make it easy for a specific group of people to monitor and send email from a common account, like public email addresses (for example, info@contoso.com or contact@contoso.com). When a person in the group replies to a message sent to the Shared mailbox, the email appears to be from the Shared mailbox, not from the individual user.</span></span>
  
<span data-ttu-id="2e907-p108">通常，组邮箱或共享邮箱不需要单独的用户许可证。但是，若要启用组邮箱或共享邮箱的就地存档，就必须向其分配 Exchange Online 计划 1 或 Exchange Online 计划 2 许可证。分配许可证后，邮箱大小将增加到授权的计划的邮箱大小。若要将共享邮箱放置到就地保留上，必须向其分配 Exchange Online 计划 2 许可证。请注意，目前不能分配组邮箱，但应该会计入许可证总数。</span><span class="sxs-lookup"><span data-stu-id="2e907-p108">Typically, Group or Shared mailboxes don't require a separate user license. However, To enable In-Place Archive for a Group or Shared mailbox, you must assign an Exchange Online Plan 1 or Exchange Online Plan 2 license to it. After the license is assigned, the mailbox size increases to that of the licensed plan. To put a Shared mailbox on In-Place Hold, you must assign an Exchange Online Plan 2 license to it. Please note that Group mailboxes cannot be assigned at this time but should be accounted for in your total licenses.</span></span>
  
<span data-ttu-id="2e907-p109">就地存档仅可用于为应用了许可证的单个用户或实体（如共享邮箱）存档邮件。禁止使用就地存档作为从多个用户或实体存储邮件的方法。例如，IT 管理员无法创建共享邮箱且无法使用户复制（通过"抄送"或"密件抄送"字段，或通过传输规则）共享邮箱以便进行显式存档。请注意，多个用户使用的共享邮箱实际上并不存储这些单个用户的电子邮件。多个用户拥有访问权限，且他们以共享邮箱发送电子邮件。因此，共享邮箱中仅存储发送至或来自共享邮箱的电子邮件，作为共享邮箱。</span><span class="sxs-lookup"><span data-stu-id="2e907-p109">In-Place Archive can only be used to archive mail for a single user or entity (such as a Shared mailbox) for which a license has been applied. Using an In-Place Archive as a means of storing mail from multiple users or entities is prohibited. For example, an IT administrator can't create a Shared mailbox and have users copy it (through the Cc or Bcc field, or through a transport rule) for the explicit purpose of archiving. Note that a Shared mailbox that multiple people use does not actually store email for those individual users. Multiple users have access, and they send email as the Shared mailbox. Therefore, the only emails stored in the Shared mailbox are those sent to or from it, as the Shared mailbox.</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="2e907-149">功能可用性</span><span class="sxs-lookup"><span data-stu-id="2e907-149">Feature Availability</span></span>

<span data-ttu-id="2e907-150">若要查看在各个 Office 365 计划、独立选项和内部部署解决方案之间的功能可用性，请参阅 [Exchange Online 服务说明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="2e907-150">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

