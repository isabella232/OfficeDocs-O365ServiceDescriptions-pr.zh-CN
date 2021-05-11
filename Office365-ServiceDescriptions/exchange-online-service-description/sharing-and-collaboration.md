---
title: 共享和协作
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-sharing-and-collaboration
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 862dab54-701f-4014-a594-0b71e03772d2
ms.openlocfilehash: 1afee4f2868a8bf0f0a1662e2d70bd8de3f2043a
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653294"
---
# <a name="sharing-and-collaboration"></a>共享和协作

## <a name="federated-sharing"></a>联合共享

联合身份验证是指支持联合共享的基础信任基础结构，这是 Microsoft Exchange Online 用户与其他外部联盟组织的收件人或具有 Internet 访问权限的用户共享忙/闲日历数据和联系人信息的方法。 这些组织还包括由 Exchange Online、外部 Microsoft Exchange Server 2010 或 Exchange Server 2013 组织托管的组织。 通过使用组织关系和共享策略，Exchange Online管理员可以允许用户从 Microsoft Outlook 网页或 Microsoft Outlook 2010 或更高版本发送日历共享邀请。
  
> [!IMPORTANT]
>  外部 Exchange 2010 和 Exchange 2013 组织必须将使用 Microsoft 联合身份验证网关的联合身份验证信任作为配置联合共享的一部分加以配置。 Exchange Online组织不必配置联合身份验证信任 -创建联合身份验证Microsoft Federation Gateway创建联合身份验证信任Microsoft 365自动创建。 
>
>  Exchange Online 组织必须配置组织关系或共享策略，以支持联合共享。 
>
>  联合共享不支持 (全局访问列表) 或在不同 Microsoft 计划中Exchange Online组织之间移动用户邮箱的全局访问列表。 
  
有关联合共享的详细信息，请参阅 [Exchange Online 中的共享](/exchange/sharing/sharing)。
  
## <a name="site-mailboxes"></a>站点邮箱

电子邮件和文档传统上保存在两个唯一且单独的数据存储库中。大多数团队通过使用电子邮件和文档进行协作。难题在于使用不同的客户端访问电子邮件和文档。这通常会导致用户工作效率降低和用户体验降级。
  
站点邮箱是 Exchange 2013 中尝试解决此问题的新概念。站点邮箱通过允许使用相同客户端接口同时访问 Microsoft SharePoint 2013 文档和 Exchange 电子邮件，从而改进协作和用户工作效率。站点邮箱在功能上由 SharePoint 2013 网站成员资格（所有者和成员）、共享存储（对于电子邮件，通过 Exchange 2013 邮箱来实现，对于文档则通过 SharePoint 2013 站点来实现）以及满足设置和生命周期需求的管理接口组成。
  
> [!IMPORTANT]
> 您的计划必须包含SharePoint。 站点邮箱要求用户具有 SharePoint 和 Exchange 的许可证。 
  
有关网站邮箱的详细信息，请参阅[网站邮箱](/exchange/collaboration-exo/collaboration-exo)。
  
## <a name="public-folders"></a>公用文件夹

Exchange Online 中的公用文件夹已进行了改进，可利用邮箱数据库现有的高可用性和存储技术。 公用文件夹体系结构使用专门设计的邮箱来存储层次结构和公用文件夹内容。 这也意味着单独的公用文件夹数据库已不存在。 公用文件夹复制现在使用连续复制模型。 层次结构和内容邮箱的高可用性由数据中心的数据库可用性组 (DAG) 提供。 在Exchange Online中，您限制为 1000 个公用文件夹邮箱。 每个公用文件夹邮箱还具有最大存储大小。 有关详细信息，请参阅邮箱限制中的"邮箱文件夹Exchange Online[部分](exchange-online-limits.md)。 公用文件夹邮箱的邮件、收件人和容量警报限制与普通邮箱相同。 有关详细信息，请参阅 [收件人](recipients.md)。 
  
有关公用文件夹的详细信息，请参阅[公用文件夹](/exchange/collaboration-exo/public-folders/public-folders)。
  
## <a name="group-and-shared-mailboxes"></a>组邮箱和共享邮箱

通过组邮箱和共享邮箱，特定组用户可以轻松监视和发送电子邮件自公用帐户，如公用电子邮件地址 (例如，info@contoso.com 或 contact@contoso.com) 。 当组内人员答复发送到共享邮箱的邮件时，电子邮件看起来好像来自共享邮箱，而不是来自单个用户。
  
通常，组邮箱或共享邮箱不需要单独的用户许可证。 但是，若要为In-Place或共享邮箱启用 Exchange Online 存档，必须为其分配Exchange Online计划 1 或 Exchange Online 2 许可证。 分配许可证后，邮箱大小将增加到授权的计划的邮箱大小。 若要将共享邮箱置于In-Place保留状态，您必须为其分配Exchange Online计划 2 许可证。 请注意，目前无法分配组邮箱，但应在许可证总数中考虑到这一点。
  
就地存档仅可用于为应用了许可证的单个用户或实体（如共享邮箱）存档邮件。 禁止使用就地存档存储多个用户或实体的邮件。 例如，IT 管理员无法创建共享邮箱，也无法让用户复制（通过"抄送"或"密件抄送"字段，或通过传输规则）共享邮箱以便进行显式存档。 请注意，多个用户使用的共享邮箱实际上并不存储这些单个用户的电子邮件。 多个用户拥有访问权限，且他们以共享邮箱发送电子邮件。 因此，共享邮箱中仅存储以共享邮箱的名义往来发送的电子邮件。
  
## <a name="feature-availability"></a>功能可用性

若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅Exchange Online[说明](exchange-online-service-description.md)。
