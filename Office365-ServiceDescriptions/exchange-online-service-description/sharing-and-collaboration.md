---
title: 共享和协作
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-sharing-and-collaboration
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 862dab54-701f-4014-a594-0b71e03772d2
ms.openlocfilehash: 8e5ce6ce41f206c5736241340c393833ae78fea7
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132586"
---
# <a name="sharing-and-collaboration"></a>共享和协作

## <a name="federated-sharing"></a>联合共享

联合身份验证是指支持联合共享的基础信任基础结构、Microsoft Exchange Online 用户与其他外部联盟组织中的收件人或具有 internet 访问权限的用户共享忙/闲日历数据和联系人信息的方法。 这些组织还包括由 Exchange Online、外部 Microsoft Exchange Server 2010 或 Exchange Server 2013 组织托管的组织。 通过使用组织关系和共享策略，Exchange Online 管理员可以使用户能够从 Microsoft Outlook 在 web 或 Microsoft Outlook 2010 或更高版本上发送日历共享邀请。
  
> [!IMPORTANT]
>  外部 Exchange 2010 和 Exchange 2013 组织必须将使用 Microsoft 联合身份验证网关的联合身份验证信任作为配置联合共享的一部分加以配置。 Exchange Online 组织无需配置联合身份验证信任—在创建 Microsoft 365 组织时，将自动创建与 Microsoft 联合网关的联合身份验证信任。 
>
>  Exchange Online 组织必须配置组织关系或共享策略，以支持联合共享。 
>
>  联合共享不支持在不同 Microsoft 计划中的 Exchange Online 组织之间共享全局访问列表（Gal）或移动用户邮箱。 
  
有关联合共享的详细信息，请参阅 [Exchange Online 中的共享](https://go.microsoft.com/fwlink/p/?LinkId=271774)。
  
## <a name="site-mailboxes"></a>站点邮箱

Email and documents are traditionally kept in two unique and separate data repositories. Most teams collaborate by using both email and documents. The challenge is that email and documents are accessed by using different clients. This usually results in a reduction in user productivity and a degraded user experience.
  
The site mailbox is a new concept in Exchange 2013 that attempts to solve this problem. Site mailboxes improve collaboration and user productivity by using the same client interface to allow access to both Microsoft SharePoint 2013 documents and Exchange email. A site mailbox functionally consists of SharePoint 2013 site membership (owners and members), shared storage through an Exchange 2013 mailbox for email messages and a SharePoint 2013 site for documents, and a management interface that addresses provisioning and life cycle needs.
  
> [!IMPORTANT]
> 您的计划必须包括 SharePoint。 站点邮箱要求用户具有 SharePoint 和 Exchange 的许可证。 
  
有关网站邮箱的详细信息，请参阅[网站邮箱](https://go.microsoft.com/fwlink/p/?LinkId=271789)。
  
## <a name="public-folders"></a>公用文件夹

Exchange Online 中的公用文件夹已进行了改进，可利用邮箱数据库现有的高可用性和存储技术。 公用文件夹体系结构使用专门设计的邮箱来存储层次结构和公用文件夹内容。 这也意味着单独的公用文件夹数据库已不存在。 公用文件夹复制现在使用连续复制模型。 层次结构和内容邮箱的高可用性由数据中心的数据库可用性组 (DAG) 提供。 在 Exchange Online 中，限制为1000公用文件夹邮箱。 每个公用文件夹邮箱还具有最大存储大小。 有关详细信息，请参阅[Exchange Online 限制](exchange-online-limits.md)中的 "邮箱文件夹限制" 部分。 公用文件夹邮箱的邮件、收件人和容量警报限制与普通邮箱相同。 有关详细信息，请参阅 [收件人](recipients.md)。 
  
有关公用文件夹的详细信息，请参阅[公用文件夹](https://go.microsoft.com/fwlink/p/?LinkId=271790)。
  
## <a name="group-and-shared-mailboxes"></a>组和共享邮箱

组和共享邮箱使特定的一组用户可以轻松地从公用帐户（如公用电子邮件地址（例如，info@contoso.com 或 contact@contoso.com）中监视和发送电子邮件。 当组中的某个人答复发送到共享邮箱的邮件时，该电子邮件似乎来自共享邮箱，而不是来自单个用户。
  
通常，组或共享邮箱不需要单独的用户许可证。 但是，若要为组或共享邮箱启用就地存档，必须向其分配 Exchange Online 计划1或 Exchange Online 计划2许可证。 分配许可证后，邮箱大小将增加到授权的计划的邮箱大小。 若要将共享邮箱置于就地保留状态，必须向其分配 Exchange Online 计划2许可证。 请注意，此时无法分配组邮箱，但应在总许可证中对其进行考虑。
  
就地存档仅可用于为应用了许可证的单个用户或实体（如共享邮箱）存档邮件。 禁止使用就地存档存储多个用户或实体的邮件。 例如，IT 管理员无法创建共享邮箱，也无法让用户复制（通过"抄送"或"密件抄送"字段，或通过传输规则）共享邮箱以便进行显式存档。 请注意，多个用户使用的共享邮箱实际上并不存储这些单个用户的电子邮件。 多个用户拥有访问权限，且他们以共享邮箱发送电子邮件。 因此，共享邮箱中仅存储的电子邮件是作为共享邮箱发送或接收的。
  
## <a name="feature-availability"></a>功能可用性

若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅[Exchange Online 服务说明](exchange-online-service-description.md)。
  

