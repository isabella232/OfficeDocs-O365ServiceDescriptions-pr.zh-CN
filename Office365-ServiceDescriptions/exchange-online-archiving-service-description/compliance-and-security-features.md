---
title: Exchange Online Archiving 中的合规性功能和安全功能
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- compliance-and-security-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7482322a-39fe-4a99-b29c-63cb1bc3cf1f
ms.openlocfilehash: c54ec8f37c6f881dc934307f7784f79d01c7a878
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035043"
---
# <a name="compliance-and-security-features-in-exchange-online-archiving"></a>Exchange Online Archiving 中的合规性功能和安全功能

## <a name="compliance-features-in-exchange-online-archiving"></a>Exchange Online Archiving 中的合规性功能

以下部分介绍了 Microsoft Exchange Online Archiving 的合规性功能。
  
### <a name="retention-policies"></a>保留策略
<a name="BKMK_Retentionpolicies"> </a>

Exchange Online Archiving 提供了保留策略，可帮助组织减少与电子邮件和其他通信有关的义务。通过这些策略，管理员可以将保留策略应用于用户收件箱中的特定文件夹。管理员也可以为用户提供保留策略的菜单，让他们使用 Outlook 2010 或更高版本或 Outlook Web App 将这些策略应用于特定的项目、会话或文件夹。在 Exchange Online Archiving 中，管理员负责管理内部部署基础结构中的保留策略。
  
Exchange Online Archiving 提供两种策略：存档和删除。这两种策略可以应用于相同的项目或文件夹。例如，用户可以标记电子邮件以便在特定天数后自动将其移到个人存档，再过几天后将其删除。
  
使用 Outlook 2010 和更高版本以及 Outlook Web App，用户可以将保留策略应用于文件夹、对话或单个邮件，还可以查看应用的保留策略和预计删除邮件的日期。其他电子邮件客户端的用户可根据管理员设置的服务器端保留策略删除或存档电子邮件，但他们的可见性和控制级别并不相同。
  
Exchange Online Archiving 中提供的保留策略功能与 Exchange Server 2010 Service Pack 2 (SP2) 及更高版本中提供的保留策略功能相同。管理员可以管理本地 Exchange Server 2010 及更高版本环境中的保留策略。托管文件夹是 Exchange 2007 中引入的邮件记录管理旧方法，在 Exchange Online Archiving 中不可用且不兼容。有关详细信息，请参阅[保留标记和保留策略](https://go.microsoft.com/fwlink/p/?LinkID=314153)。
  
### <a name="in-place-hold-and-litigation-hold"></a>就地保留和诉讼保留
<a name="BKMK_In_placehold"> </a>

当存在诉讼的合理预期时，需要组织保留与事实相关的以电子方式存储的信息 (ESI)，包括电子邮件。这种预期可能在知道事实的细节之前发生，并且保留内容通常很广泛。组织可能保留与特定主题相关的所有电子邮件，或特定个人的所有电子邮件。
  
> [!NOTE]
> 就地保留和诉讼保留目前不适用于使用 POP 或 IMAP 客户端或通过使用 SMTP 协议的自定义应用程序发送的电子邮件。 
  
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
<a name="BKMK_In_placehold"> </a>

Exchange Online Archiving 支持就地电子数据展示，可在组织中搜索邮箱内容。通过本地 Exchange 2013 服务器中的 Exchange 管理中心或远程 Windows PowerShell，管理员或或授权的发现管理员可以搜索各种邮箱项目（包括电子邮件、附件、日历约会、任务和联系人）。就地电子数据展示可以同时搜索主邮箱和存档。丰富的筛选功能包括发件人、收件人、邮件类型、发送日期、接收日期、抄送、密送以及关键字查询语言 (KQL) 语法。如需了解更多详情，请参阅[就地电子数据展示](https://go.microsoft.com/fwlink/p/?LinkId=314169)。
  
Exchange 管理中心和远程 Windows PowerShell 可用于在就地电子数据展示搜索中一次最多搜索 5,000 个邮箱。若要详细了解如何使用远程 Windows PowerShell 运行就地电子数据展示搜索，请参阅 [New-MailboxSearch](https://go.microsoft.com/fwlink/p/?LinkId=314170)。 
  
> [!NOTE]
> 在远程 Windows PowerShell 中， `Search-Mailbox` cmdlet 可用于搜索超过 5,000 个邮箱。若要详细了解如何使用远程 Windows PowerShell 搜索大量邮箱，请参阅 [Search-Mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314171)。 
  
就地电子数据展示搜索的结果可以在 Exchange 管理中心内进行预览、导出到 .pst 文件中或复制到一种特殊类型的邮箱（即发现邮箱）中。管理员或合规部主管可以连接发现邮箱来查看邮件。有关详细信息，请参阅[创建就地电子数据展示搜索](https://go.microsoft.com/fwlink/p/?LinkId=314172)。
  
> [!NOTE]
> 在复制跨内部部署和基于云的邮箱或存档执行的就地电子数据展示搜索的搜索结果时，您必须选择一个内部部署发现邮箱。将内部部署主邮箱和基于云的存档中的邮件复制到内部部署发现邮箱。 
  
管理员还可以搜索并删除发送到跨组织的多个邮箱的不当电子邮件。例如，如果不小心将机密的工资信息发送给了所有员工，管理员可以从用户邮箱中删除此邮件。无法 Exchange 管理中心内执行此类搜索。必须使用远程 PowerShell 执行。若要详细了解如何从用户邮箱中删除邮件，请参阅[搜索和删除邮件](https://go.microsoft.com/fwlink/p/?LinkId=314173)。
  
## <a name="security-features-in-exchange-online-archiving"></a>Exchange Online Archiving 的安全功能

以下部分介绍了 Microsoft Exchange Online Archiving 的安全功能。
  
### <a name="encryption-between-on-premises-servers-and-exchange-online-archiving"></a>在内部部署服务器和 Exchange Online Archiving 之间加密

TLS 用于加密电子邮件服务器之间的连接，以帮助阻止电子诈骗并为传送中的邮件提供保密性。TLS 还可以用来确保到 Exchange Online Archiving 的 Office 365 数据中心的内部部署邮件服务器通信安全。
  
### <a name="encrypting-between-clients-and-exchange-online-archiving"></a>在客户端和 Exchange Online Archiving 之间加密

到 Exchange Online Archiving 的客户端连接使用以下加密方法来提高安全性：
  
- 通过 TCP 端口 443 使用 SSL 来确保 Outlook、Outlook Web App 和 Exchange Web Services 通信的安全。
    
- 引入 Exchange Online Archiving 并未更改到内部部署服务器的客户端连接。
    
### <a name="encryption-smime-and-pgp"></a>加密：S/MIME 和 PGP

Exchange Online Archiving 将会存储安全/多用途 Internet 邮件扩展 (S/MIME) 邮件。但是，Exchange Online Archiving 不托管 S/MIME 功能或公共密钥，也不提供密钥存储库、密钥管理或关键目录服务，因为这些服务附加在内部部署 Exchange 基础结构上。
  
同样，Exchange Online Archiving 将会存储通过第三方客户端加密解决方案（如 Pretty Good Privacy (PGP)）加密的邮件。
  
### <a name="information-rights-management"></a>信息权限管理

Exchange Online Archiving 不提供托管信息权限管理 (IRM) 服务，但管理员可以使用内部部署 Active Directory 权限管理服务 (AD RMS)。如果部署了 AD RMS 服务器，则 Outlook 可以直接与此服务器通信，让用户可以撰写和读取受 IRM 保护的邮件。如果在 AD RMS 服务器和内部部署 Exchange 环境之间配置了互操作性，则用户可以撰写和读取受 IRM 保护的邮件。
  
#### <a name="support-for-irm-in-outlook-web-app"></a>Outlook Web App 中的 IRM 支持

用户可以像在 Outlook 中那样，在 Outlook Web App 中以本机方式阅读和创建受 IRM 保护的邮件。用户可以通过 Internet Explorer、Firefox、Safari 和 Chrome 在 Outlook Web App 中访问受 IRM 保护的邮件，并且无需使用任何插件。邮件包括全文搜索、会话视图和预览窗格。要启用此功能，请务必配置 Active Directory 权限管理服务服务器和内部部署 Exchange 环境之间的互操作性。
  
#### <a name="irm-search"></a>IRM 搜索

受 IRM 保护的邮件已编制索引，可以进行搜索，包括标头、主题、正文和附件。用户可以在 Outlook 和 Outlook Web App 中搜索受 IRM 保护的项目，管理员可以通过就地电子数据展示或 **Search-Mailbox** cmdlet 搜索受 IRM 保护的项目。 
  
### <a name="auditing"></a>审核

Exchange Online Archiving 提供两种内置审核功能：
  
- **管理员审核日志记录** 管理员审核日志记录允许客户在 Exchange Online Archiving 环境中跟踪其管理员所做的更改，包括对 RBAC 角色或 Exchange 策略和设置的更改。 
    
- **邮箱审核日志记录** 邮箱审核日志记录允许客户按用户跟踪邮箱访问，而不是根据邮箱所有者进行跟踪。 
    
Exchange 管理中心提供几个预定义审核报告，包括管理员角色更改、诉讼保留和非所有者邮箱访问。管理员可以按日期和角色筛选报告，用 XML 格式导出指定邮箱的所有审核事件以用于长期保留或自定义报告。
  
管理员审核日志记录默认启用，而邮箱审核日志记录则默认禁用。管理员可以使用远程 Windows PowerShell 为组织中的部分或全部邮箱启用邮箱审核日志记录。有关详细信息，请参阅[审核报告](https://go.microsoft.com/fwlink/p/?LinkId=314175)。
  
## <a name="feature-availability"></a>功能可用性

若要查看在各个 Office 365 计划、独立选项和内部部署解决方案之间的功能可用性，请参阅 [Exchange Online Archiving 服务说明](exchange-online-archiving-service-description.md)。
  

