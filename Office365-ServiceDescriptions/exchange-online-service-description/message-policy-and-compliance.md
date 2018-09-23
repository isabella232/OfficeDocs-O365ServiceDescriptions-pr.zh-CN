---
title: 邮件策略和合规性
ms.author: pebaum
author: pebaum
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
ms.openlocfilehash: fd5062df19298720417566d91667f3c3b237b164
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035224"
---
# <a name="message-policy-and-compliance"></a>邮件策略和合规性

## <a name="archiving-exchange-online-based-mailboxes"></a>存档基于 Exchange Online 的邮箱

Exchange Online 邮箱位于云中，对其进行存档需要独特的托管环境。在有些情况下，也可使用 Exchange Online 来将内部部署的邮箱存档到云中。本节介绍使用 Exchange Online 进行存档的各种选择。
  
Exchange Online 为基于云的邮箱提供了内置存档功能，包括可为用户提供存储较旧电子邮件的便利位置的就地存档。就地存档是一种特殊类型的邮箱，它会随 Outlook 和 Outlook Web App 中的用户主邮箱文件夹一同显示出来。用户可以按他们访问和搜索其主邮箱的相同方式访问和搜索此存档。可用功能取决于所使用的客户端：
  
- **Outlook 2016、Outlook 2013、Outlook 2010 和 Outlook Web App** 用户可以访问存档的所有功能以及相关的合规性功能，如对保留和存档策略进行控制。 
    
- **Outlook 2007** 用户具有就地存档的基本支持，但不是所有的存档和合规性功能都可用。例如，用户无法将保留或存档策略应用到邮箱中的邮件，而是必须依赖管理员设置的策略。 
    
管理员使用 Exchange 管理中心或远程 Windows PowerShell 为特定用户启用个人存档功能。
  
有关详细信息，请参阅：
  
- [Exchange Online 中的存档邮箱](https://go.microsoft.com/fwlink/p/?LinkId=404421)
    
- [在 Exchange Online 中启用或禁用存档邮箱](https://go.microsoft.com/fwlink/p/?LinkId=404425)
    
### <a name="archive-sizes"></a>存档大小

每个个人存档中只能存储一个用户的邮件数据。存储空间分配取决于订阅计划。有关存档邮箱大小的详细信息，请参阅[Exchange Online 限制](exchange-online-limits.md)中的"邮箱存储限制"部分。
  
> [!IMPORTANT]
> 不允许使用日记、传输规则或自动转发规则将邮件复制到 Exchange Online 邮箱中来进行存档。Microsoft 保留拒绝在个人未使用邮箱存档的情况下进行无限制存档的权利。 > 就地存档对 Outlook 用户有特定的许可要求。Outlook 2007 用户必须具有 2011 年 2 月的 Office 2007 累积更新才能访问个人存档。 > Exchange Online 不支持 Exchange Server 2010 Service Pack 1 或更高版本的  _New-MailboxImportRequest_ Windows PowerShell cmdlet，管理员无法将 .pst 文件导入到个人存档中。如果用户在 Exchange Online 中具有主邮箱和此存档，则管理员可以使用 PST Capture 这款免费工具来将 .pst 文件数据导入到用户的主邮箱或存档中。 
  
## <a name="cloud-based-archiving-of-on-premises-mailboxes"></a>内部部署邮箱的基于云的存档

通过 Microsoft Exchange Online Archiving（Microsoft 提供的托管存档解决方案），可以对内部部署 Exchange Server 2010 或更高版本的基于云的存档使用 Exchange Online。这要求内部部署组织处于混合模式下，或已针对 Exchange Online Archiving 进行了相关设置。
  
> [!IMPORTANT]
> 在 Exchange 2010 邮箱服务器上具有内部部署邮箱且应用了“托管文件夹”策略的用户无法启用内部部署或基于云的就地存档。 
  
## <a name="retention-tags-and-retention-policies"></a>保留标记和保留策略

Exchange Online 提供了保留策略，可帮助组织减少与电子邮件和其他通信关联的义务。通过这些策略，管理员可以将保留策略应用于用户收件箱中的特定文件夹。管理员也可以为用户提供保留策略的菜单，让他们使用 Outlook 2010 或更高版本或 Outlook Web App 将这些策略应用于特定的项目、会话或文件夹。
  
在 Exchange Online 中，管理员通过使用 Exchange 管理中心 (EAC) 或远程 Windows PowerShell 管理保留策略。
  
Exchange Online 提供了两种类型的策略：存档策略和删除策略。可以在相同的项目或文件夹中结合使用这两种类型。例如，用户可以将某个电子邮件标记为在特定天数之后自动移动到就地存档，并在若干天后自动删除。
  
使用 Outlook 2010 或更高版本和 Outlook Web App，用户可以将保留策略应用到文件夹、会话或各个邮件中。他们也可以查看对邮件应用的保留策略和预期的删除日期。其他电子邮件客户端的用户只能根据管理员设置的服务器端保留策略删除或存档电子邮件。
  
Exchange Online 中提供的保留策略功能与 Exchange Server 2010 Service Pack 2 RU4 中的提供的保留策略功能相同。管理员可以使用远程 Windows PowerShell 来将保留策略从内部部署 Exchange Server 2010 或更高版本环境迁移到 Exchange Online。
  
> [!IMPORTANT]
> 托管文件夹在 Exchange Online 中不可用，托管文件夹是在 Exchange Server 2007 中引入的一种比较旧的邮件记录管理方法。 
  
有关详细信息，请参阅[保留标记和保留策略](https://go.microsoft.com/fwlink/p/?LinkId=271745)。
  
## <a name="encryption-of-data-at-rest"></a>静态数据的加密

加密的 Office 365 客户静态数据是由提供多个服务端技术，包括 BitLocker、 DKM、 Azure 存储服务加密和服务加密在 Exchange Online、 Skype for Business、 OneDrive for Business 和 SharePoint联机。Office 365 服务加密包括选项，可使用 Azure 键存储库中存储的客户管理加密密钥。此客户托管密钥选项，请调用[Office 365 客户参数](https://go.microsoft.com/fwlink/?linkid=863349)，仅供 Exchange Online、 SharePoint Online 和 OneDrive for Business。 
  
### <a name="bitlocker"></a>BitLocker

Office 365 服务器使用 BitLocker 加密磁盘驱动器包含客户数据在 rest 的音量级别。BitLocker 加密是一种 Windows 中内置的数据保护功能。BitLocker 是硬件的用于有停止其他进程或可能会导致物理磁盘包含客户数据访问某人的控件 （例如，访问控制或回收） 的情况下保护抵御威胁的技术之一。在这种情况下，BitLocker 消除数据盗窃或暴露可能由于丢失、 盗取或配置取消不当计算机和磁盘。 
  
### <a name="distributed-key-manager"></a>分布式密钥管理器

除了 BitLocker，我们使用称为分布式密钥管理器 (DKM) 的技术。DKM 是使用一的机密密钥加密和解密信息的客户端的功能。只有在 Active Directory 域服务中的特定安全组的成员可以访问这些键来解密按 DKM 加密的数据。在 Exchange Online 中，某些 Exchange 进程所运行的服务帐户是该安全组的一部分。作为数据中心中的标准操作过程的一部分，没有人授予属于该安全组的凭据，因此没有人有权访问可以解密这些机密的键。
  
## <a name="customer-key"></a>客户密钥

与客户参数，您将控制组织的加密密钥，然后配置 Office 365 使用它们在 Microsoft 数据中心中的 rest 数据进行加密。静态数据包括 Exchange Online 和 Skype for Business 内的邮箱和 SharePoint Online 中存储的文件中存储和 OneDrive for Business 中的数据。有关详细信息，请参阅[控制您使用客户密钥的 Office 365 中的数据](https://go.microsoft.com/fwlink/?linkid=863349)和[服务与 Office 365 常见问题客户密钥的加密](https://go.microsoft.com/fwlink/?linkid=869438)。
  
## <a name="office-365-message-encryption"></a>Office 365 邮件加密
<a name="bkmk_O365_MessageEncryption"> </a>

Office 365 邮件加密允许任何人发送加密的电子邮件的电子邮件用户。我们宣布 Office 邮件加密的利用中 Azure 信息加密的保护功能的新功能。这些新功能提供增强更加轻松地共享与协作受保护的邮件与任何人组织内外的最终用户体验。新 Office 邮件加密功能具有一些安装要求。请参阅 Set up 内置到 Azure 信息保护顶部的新 Office 365 邮件加密功能。在旧的 Office 365 邮件加密的客户不不关注上面提供的指南设置获得的新功能。请阅读[常见问题](https://support.office.com/en-us/article/Office-365-Message-Encryption-FAQ-0432dce9-d9b6-4e73-8a13-4a932eb0081e)的更多详细信息在新旧的 Office 365 邮件加密功能与包括的内容。 
  
## <a name="securemultipurpose-internet-mail-extensions-smime"></a>安全/多用途 Internet 邮件扩展 (S/MIME)
<a name="bkmk_O365_MessageEncryption"> </a>

借助 S/MIME，您可以通过在组织内发送签名的加密电子邮件来保护敏感信息。在创建 PKI 证书并将其分发给用户后，管理员可以使用远程 Windows PowerShell 设置 S/MIME。必须从本地 Active Directory 证书服务同步这些证书。
  
Internet Explorer 9 或更高版本支持 S/MIME。目前，Firefox、Opera 和 Chrome 不支持 S/MIME。有关详细信息，请参阅[邮件签名和加密的 S/MIME](https://go.microsoft.com/fwlink/p/?LinkID=393973)。
  
## <a name="in-place-hold-and-litigation-hold"></a>就地保留和诉讼保留
<a name="bkmk_O365_MessageEncryption"> </a>

当存在诉讼的合理预期时，需要组织保留与事实相关的以电子方式存储的信息 (ESI)，包括电子邮件。这种预期可能在知道事实的细节之前发生，并且保留内容通常很广泛。组织可能保留与特定主题相关的所有电子邮件，或特定个人的所有电子邮件。
  
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
  
## <a name="in-place-ediscovery"></a>就地电子数据展示
<a name="bkmk_O365_MessageEncryption"> </a>

Exchange Online 可让用户使用基于 Web 的界面在整个组织中搜索邮箱内容。管理员或有权执行就地电子数据展示搜索（通过分配）的合规性和安全性管理人员可以搜索电子邮件、附件、日历约会、任务、联系人和其他项目。就地电子数据展示可以同时搜索主邮箱和存档。丰富的筛选功能包括发件人、收件人、邮件类型、发送/接收日期、抄送/密送以及 KQL 语法。搜索结果也包含"已删除邮件"中的邮件（如果这些邮件与搜索查询条件匹配）。
  
就地电子数据展示搜索的结果可以在基于 Web 的界面中预览、导出到 PST 文件中或复制到名为发现邮箱的特殊类型的邮箱中。发现邮箱具有 50 GB 的配额用于存储搜索结果。管理员还可以将 Outlook 连接到发现邮箱以访问搜索结果，并将搜索结果导出到 .pst 文件中。
  
管理员可以使用 Exchange 管理中心或远程 Windows PowerShell 来执行多邮箱搜索。Exchange 管理中心可以提供只读的搜索结果预览，让管理员可以快速验证搜索，并在需要时使用不同的参数再次运行此搜索。在优化搜索之后，管理员可以将搜索结果复制到发现邮箱中。
  
默认情况下，为每个组织创建一个发现邮箱，但管理员可以使用远程 Windows PowerShell 创建其他发现邮箱。发现邮箱不能用于存储就地电子数据展示搜索结果之外的任何目的。
  
管理员可以使用 Exchange 管理中心或远程 Windows PowerShell 来执行就地电子数据展示搜索。Exchange 管理中心可以提供只读的搜索结果预览，让管理员可以快速验证搜索，并在需要时使用不同的参数再次运行此搜索。在优化搜索之后，管理员可以将搜索结果复制到发现邮箱中或将搜索结果导出到 PST 文件中。
  
管理员可以使用 Exchange 管理中心或远程 Windows PowerShell 以在就地电子数据展示搜索中一次搜索最多 10,000 个邮箱。 
  
在 Exchange Online 中，授权用户可以执行就地电子数据展示并选择以下选项之一：
  
- **估计搜索结果** 获取搜索会返回的估计邮件数，包括关键字统计信息以确定搜索中使用的关键字有效性并在需要时调整搜索参数。 
    
- **预览搜索结果**
    
- 将搜索结果中返回的邮件复制到发现邮箱。
    
有关详细信息，请参阅[就地电子数据展示](http://go.microsoft.com/fwlink/p/?LinkId=271747)。
  
## <a name="mail-flow-rules"></a>邮件流规则
<a name="bkmk_O365_MessageEncryption"> </a>

邮件流规则可用于查找在通过您的组织和对其进行操作的消息的特定条件。邮件流规则，让您应用以电子邮件、 邮件安全、 保护消息系统和防止信息泄露的邮件策略。
  
当今，法律、法规或公司政策要求许多组织应用邮件策略，以便限制组织内部和外部的收件人和发件人之间的交互。除了对个人、组织内部的部门小组以及组织外部的实体之间的交互进行限制以外，某些组织还要满足下列邮件策略要求：
  
- 防止不适当的内容进入或离开组织
    
- 筛选机密组织信息
    
- 对特定个人发送或接收的邮件进行跟踪或复制
    
- 在传递之前重定向入站和出站邮件以便进行检查
    
- 对通过组织的邮件应用免责声明
    
> [!IMPORTANT]
> 需要使用之前的邮件流规则，安装相应 iFilter 后无法检查的第三方 Ifilter （如 Adobe.pdf) 的电子邮件服务器上安装的附件文件类型。有关支持的邮件流规则文件类型的详细信息，请参阅[Use 邮件流 rules to inspect message attachments 位于 Office 365](https://go.microsoft.com/fwlink/p/?LinkId=271748)。 
  
有关邮件流规则的详细信息，请参阅[邮件的流规则在 Exchange 2016](https://go.microsoft.com/fwlink/p/?LinkId=296488)。
  
## <a name="data-loss-prevention"></a>数据丢失预防
<a name="bkmk_O365_MessageEncryption"> </a>

防止数据丢失 (DLP) 功能可帮助您通过深入的内容分析标识、监控和保护您组织中的敏感信息。DLP 是一项对于企业邮件系统而言越来越重要的高级功能，因为对于企业非常重要的电子邮件包含需要保护的敏感信息。Exchange Online 中的 DLP 功能可让您保护敏感数据，而不会影响工作人员的生产率。
  
您可以在 Exchange 管理中心 (EAC) 管理界面中配置 DLP 策略，以便您执行下列操作： 
  
- 启动预配置的策略模板，此模板可帮助您检测特定类型的敏感信息，如 PCI-DSS 数据、格雷姆-里奇-比利雷法案数据，甚至是区域设置特定的个人身份信息 (PII)。
    
- 使用现有传输规则条件和操作的强大功能，并添加新的传输规则。
    
- 在全面执行前，测试您的 DLP 策略的有效性。
    
- 整合您自己的自定义 DLP 策略模板和敏感的信息类型。
    
- 检测邮件附件、 正文文本或主题行中的敏感信息，然后调整的 Exchange Online 操作的信任级别。
    
- 通过使用文档指纹检测敏感型数据。文档指纹可以帮助您基于文本形式（您可以用其定义传输规则和 DLP 策略）轻松地创建自定义敏感信息类型。
    
- 添加策略提示，它可通过向 Outlook 2016、Outlook 2013、Outlook Web App 和适用于设备的 OWA 的用户显示通知来帮助减少数据丢失，还可以通过允许误报报告来提高策略的有效性。 
    
- 查看 DLP 报告中的事件数据，或通过使用生成事件报告操作来添加自己的特定报告。
    
有关 DLP 的详细信息，请参阅[数据丢失防护](https://go.microsoft.com/fwlink/p/?LinkId=271749)。
  
## <a name="journaling"></a>日记
<a name="bkmk_O365_MessageEncryption"> </a>

您可以配置 Exchange Online，以将电子邮件的副本记录到通过 SMTP 接收邮件的任何外部邮箱中。通过记录入站和出站电子邮件通信，日记功能可以帮助组织对法律、法规和组织遵从性要求做出响应。规划邮件保留和合规性时，了解日记功能及其如何适应组织的合规性策略，这一点非常重要。
  
您可以使用 Exchange 管理中心或远程 Windows PowerShell 管理日记规则。您可以按用户和通讯组列表来配置日记，并选择仅记录内部邮件日记、仅记录外部邮件日记或这两者。日记邮件不仅包含原始邮件，还包含有关发件人、收件人、副本和密送副本的信息。
  
若要确保成功和可靠的日记解决方案，您需要完成以下任务：
  
- 请确保日记目标不是 Exchange Online 邮箱。
    
- 在客户目录中为要用于日记记录的 SMTP 目标电子邮件地址创建联系人对象。
    
- 将第二个联系人对象创建为备用日记邮箱，用于在主日记邮箱不可用时捕获任何日记报告。
    
- 维护正确管理、 冗余、 可用性、 性能和 SMTP 目标，以确保始终接收成功的邮件的功能级别。
    
- 提供与 Exchange Server 和 Exchange 传输的具体互操作性，包括邮件格式、发件人/收件人信息集成和正确的内容转换。
    
有关日记的详细信息，请参阅[日记](https://go.microsoft.com/fwlink/p/?LinkId=271750)。
  
## <a name="feature-availability"></a>功能可用性
<a name="bkmk_O365_MessageEncryption"> </a>

若要查看在各个 Office 365 计划、独立选项和内部部署解决方案之间的功能可用性，请参阅 [Exchange Online 服务说明](exchange-online-service-description.md)。
  

