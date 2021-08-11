---
title: 邮件策略和合规性
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-message-policy-recovery-and-compliance
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5c43c8eb-f8f7-4b5a-a743-b1dab7dc2fc8
description: 了解邮件策略和邮件Exchange Online。
ms.openlocfilehash: 135a928aef14695e5dd4d459c3ac60f24ea81a0b91585a3017f6e50591b03226
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/06/2021
ms.locfileid: "54663765"
---
# <a name="message-policy-and-compliance"></a>邮件策略和合规性

## <a name="archiving-exchange-online-based-mailboxes"></a>存档基于 Exchange Online 的邮箱

Exchange Online 邮箱位于云中，对其进行存档需要独特的托管环境。在有些情况下，也可使用 Exchange Online 来将内部部署的邮箱存档到云中。本节介绍使用 Exchange Online 进行存档的各种选择。
  
Exchange Online 为基于云的邮箱提供了内置存档功能，包括可为用户提供存储较旧电子邮件的便利位置的就地存档。 "In-Place 存档"是一种特殊类型的邮箱，它显示在用户的主邮箱文件夹旁边Outlook Outlook 网页版。 用户可以按他们访问和搜索其主邮箱的相同方式访问和搜索此存档。 可用功能取决于所使用的客户端：
  
- **Outlook 2016 2013 Outlook 2010 Outlook 2010 和 Outlook 网页版** 用户可以访问存档的全部功能，以及相关的合规性功能，如对保留和存档策略的控制。 
    
- **Outlook 2007** 用户具有就地存档的基本支持，但不是所有的存档和合规性功能都可用。例如，用户无法将保留或存档策略应用到邮箱中的邮件，而是必须依赖管理员设置的策略。 
    
管理员使用 Exchange 管理中心或远程 Windows PowerShell 为特定用户启用个人存档功能。
  
有关详细信息，请参阅：
  
- [Exchange Online 中的存档邮箱](../exchange-online-archiving-service-description/archive-features.md)
    
- [在 Exchange Online 中启用或禁用存档邮箱](/office365/securitycompliance/enable-archive-mailboxes)
    
### <a name="archive-sizes"></a>存档大小

每个个人存档中只能存储一个用户的邮件数据。 存储空间分配取决于订阅计划。 有关存档邮箱大小的信息，请参阅邮箱限制中的"邮箱存储Exchange Online[部分](exchange-online-limits.md)。
  
> [!IMPORTANT]
> - 不允许使用日记、传输规则或自动转发规则将邮件复制到 Exchange Online 邮箱中来进行存档。 Microsoft 保留拒绝在个人方案或其他不当使用情况下使用邮箱存档的情况下进行无限制存档的权利。
> - 就地存档对 Outlook 用户有特定的许可要求。Outlook 2007 用户必须具有 2011 年 2 月的 Office 2007 累积更新才能访问个人存档。 
> - Exchange Online不支持管理员驱动的将 .pst 文件导入到个人存档的 Exchange Server 2010 Service Pack 1 或更高版本的 _New-MailboxImportRequest_ Windows PowerShell cmdlet。 如果用户在 Exchange Online 中具有主邮箱和此存档，则管理员可以使用 PST Capture 这款免费工具来将 .pst 文件数据导入到用户的主邮箱或存档中。

## <a name="cloud-based-archiving-of-on-premises-mailboxes"></a>内部部署邮箱的基于云的存档

通过 Microsoft Exchange Online Archiving（Microsoft 提供的托管存档解决方案），可以对内部部署 Exchange Server 2010 或更高版本的基于云的存档使用 Exchange Online。这要求内部部署组织处于混合模式下，或已针对 Exchange Online Archiving 进行了相关设置。
  
> [!IMPORTANT]
> 在 Exchange 2010 邮箱服务器上具有内部部署邮箱且应用了“托管文件夹”策略的用户无法启用内部部署或基于云的就地存档。 
  
## <a name="retention-tags-and-retention-policies"></a>保留标记和保留策略

Exchange Online 提供了保留策略，可帮助组织减少与电子邮件和其他通信关联的义务。 通过这些策略，管理员可以将保留策略应用于用户收件箱中的特定文件夹。 管理员还可以为用户提供保留策略菜单，让他们使用 Outlook 2010 或更高版本或 Outlook 网页版 将策略应用于特定项目、对话或文件夹。
  
在 Exchange Online 中，管理员通过使用 Exchange 管理中心 (EAC) 或远程 Windows PowerShell 管理保留策略。
  
Exchange Online 提供了两种类型的策略：存档策略和删除策略。可以在相同的项目或文件夹中结合使用这两种类型。例如，用户可以将某个电子邮件标记为在特定天数之后自动移动到就地存档，并在若干天后自动删除。
  
使用 Outlook 2010 或更高版本Outlook 网页版，用户可以将保留策略应用于文件夹、对话或单个邮件。 他们也可以查看对邮件应用的保留策略和预期的删除日期。 其他电子邮件客户端的用户只能根据管理员设置的服务器端保留策略删除或存档电子邮件。
  
Exchange Online 中提供的保留策略功能与 Exchange Server 2010 Service Pack 2 RU4 中的提供的保留策略功能相同。管理员可以使用远程 Windows PowerShell 来将保留策略从内部部署 Exchange Server 2010 或更高版本环境迁移到 Exchange Online。
  
> [!IMPORTANT]
> 托管文件夹在 Exchange Online 中不可用，托管文件夹是在 Exchange Server 2007 中引入的一种比较旧的邮件记录管理方法。 
  
有关详细信息，请参阅[保留标记和保留策略](/exchange/security-and-compliance/messaging-records-management/retention-tags-and-policies)。
  
## <a name="encryption-of-data-at-rest"></a>静态数据的加密

静态客户数据的加密由多种服务端技术提供，包括 Exchange Online、Skype for Business、OneDrive for Business 和 SharePoint Online 中的 BitLocker、DKM、Azure 存储 服务加密和服务加密。 Office 365服务加密包括使用存储在 Azure 密钥保管库中的客户管理的加密密钥的选项。 此客户管理的密钥选项称为[客户密钥](/microsoft-365/compliance/customer-key-overview)，可用于 Exchange Online、SharePoint Online 和 OneDrive for Business。 
  
### <a name="bitlocker"></a>BitLocker

Microsoft 服务器使用 BitLocker 在卷级别加密包含客户数据的其余磁盘驱动器。 BitLocker 加密是内置于 Windows。 BitLocker 是一种技术，当其他过程或控制 (（例如访问控制或硬件) 的回收）存在故障时，用于防范威胁，这可能会导致某人获得对包含客户数据的磁盘的物理访问权限。 在这种情况下，BitLocker 消除了由于丢失、被盗或不当停用计算机和磁盘而发生数据盗窃或泄露的可能性。 
  
### <a name="distributed-key-manager"></a>分布式密钥管理器

除了 BitLocker 之外，我们还使用名为分布式密钥管理器 (DKM) 。 DKM 是一种客户端功能，它使用一组密钥来加密和解密信息。 只有 Active Directory 域服务中特定安全组的成员可以访问这些密钥，以解密由 DKM 加密的数据。 在Exchange Online中，只有运行 Exchange 进程的某些服务帐户是该安全组的一部分。 作为数据中心中标准操作过程一部分，不会向人员提供属于此安全组的凭据，因此，人员无法访问可解密这些密钥的密钥。
  
## <a name="customer-key"></a>客户密钥

使用客户密钥，可以控制组织的加密密钥，然后将它们配置为对 Microsoft 数据中心中的静态数据进行加密。 其余数据包括存储在 Exchange Online 和 Skype for Business 中的数据和存储在 SharePoint Online 和 OneDrive for Business 中的文件。 有关详细信息，请参阅使用客户密钥和服务 [加密](/office365/securitycompliance/controlling-your-data-using-customer-key) 和客户密钥 [常见问题解答来控制你的数据](/office365/securitycompliance/service-encryption-with-customer-key-faq)。
  
## <a name="office-365-message-encryption"></a>Office 365 邮件加密

Office 365 邮件加密电子邮件用户向任何人发送加密电子邮件。 我们宣布在邮件加密Office利用 Azure 信息加密中的保护功能的新功能。 这些新功能提供了增强的最终用户体验，可更轻松地与组织内外的任何人共享和协作处理受保护的邮件。 新的邮件Office功能有一些设置要求。 请参阅设置基于 Azure Office 365 邮件加密构建的新功能。 使用传统Office 365 邮件加密客户如果没有遵循上面提供的设置指南，将不会获得新功能。 请阅读[常见问题解答](https://support.office.com/article/Office-365-Message-Encryption-FAQ-0432dce9-d9b6-4e73-8a13-4a932eb0081e)，详细了解新功能与旧版 Office 365 邮件加密功能。 

Office 365 高级邮件加密允许邮件过期和吊销，从而提供额外的保护。  您还可以为来自组织的加密电子邮件创建多个模板。  高级邮件加密包含在 Microsoft 365 E5、Office 365 E5、Microsoft 365 E5 (非营利组织员工) 、Office 365 企业版 E5 (非营利组织员工定价) 或 Office 365 教育版 A5 中。 如果您的组织订阅不包含Office 365 高级邮件加密，您可以购买 Microsoft 365 E5 合规 或 Office 365 高级合规版 SKU 作为加载项。

## <a name="securemultipurpose-internet-mail-extensions-smime"></a>安全/多用途 Internet 邮件扩展 (S/MIME)

借助 S/MIME，您可以通过在组织内发送签名的加密电子邮件来保护敏感信息。在创建 PKI 证书并将其分发给用户后，管理员可以使用远程 Windows PowerShell 设置 S/MIME。必须从本地 Active Directory 证书服务同步这些证书。
  
S/MIME 在 Microsoft Edge 11 Internet Explorer受支持。 目前，Firefox、Opera 和 Chrome 不支持 S/MIME。 有关详细信息，请参阅[邮件签名和加密的 S/MIME](/Exchange/policy-and-compliance/smime?preserve-view=true&view=exchserver-2019)。
  
## <a name="in-place-hold-and-litigation-hold"></a>就地保留和诉讼保留

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
  
有关详细信息，请参阅[就地保留和诉讼保留](/exchange/security-and-compliance/in-place-and-litigation-holds)。
  
## <a name="in-place-ediscovery"></a>就地电子数据展示

Exchange Online允许客户使用基于 Web 的界面搜索组织中邮箱的内容。 管理员或有权执行就地电子数据展示搜索（通过分配）的合规性和安全性管理人员可以搜索电子邮件、附件、日历约会、任务、联系人和其他项目。 就地电子数据展示可以同时搜索主邮箱和存档。 丰富的筛选功能包括发件人、收件人、邮件类型、发送/接收日期、抄送/密送以及 KQL 语法。 搜索结果也包含"已删除邮件"中的邮件（如果这些邮件与搜索查询条件匹配）。
  
就地电子数据展示搜索的结果可以在基于 Web 的界面中预览、导出到 PST 文件中或复制到名为发现邮箱的特殊类型的邮箱中。发现邮箱具有 50 GB 的配额用于存储搜索结果。管理员还可以将 Outlook 连接到发现邮箱以访问搜索结果，并将搜索结果导出到 .pst 文件中。
  
管理员可以使用 Exchange 管理中心或远程 Windows PowerShell 来执行多邮箱搜索。Exchange 管理中心可以提供只读的搜索结果预览，让管理员可以快速验证搜索，并在需要时使用不同的参数再次运行此搜索。在优化搜索之后，管理员可以将搜索结果复制到发现邮箱中。
  
默认情况下，为每个组织创建一个发现邮箱，但管理员可以使用远程 Windows PowerShell 创建其他发现邮箱。发现邮箱不能用于存储就地电子数据展示搜索结果之外的任何目的。
  
管理员可以使用 Exchange 管理中心或远程 Windows PowerShell 来执行就地电子数据展示搜索。Exchange 管理中心可以提供只读的搜索结果预览，让管理员可以快速验证搜索，并在需要时使用不同的参数再次运行此搜索。在优化搜索之后，管理员可以将搜索结果复制到发现邮箱中或将搜索结果导出到 PST 文件中。
  
管理员可以使用 Exchange 管理中心或远程 Windows PowerShell 以在就地电子数据展示搜索中一次搜索最多 10,000 个邮箱。 
  
在 Exchange Online 中，授权用户可以执行就地电子数据展示并选择以下选项之一：
  
- **估计搜索结果** 获取搜索会返回的估计邮件数，包括关键字统计信息以确定搜索中使用的关键字有效性并在需要时调整搜索参数。 
    
- **预览搜索结果**
    
- 将搜索结果中返回的邮件复制到发现邮箱。
    
有关详细信息，请参阅[就地电子数据展示](/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery)。
  
## <a name="mail-flow-rules"></a>邮件流规则

可以使用邮件流规则来查找通过组织传递的邮件的特定条件，并处理它们。 邮件流规则使你可以将邮件策略应用于电子邮件、保护邮件、保护邮件系统并防止信息泄露。
  
当今，法律、法规或公司政策要求许多组织应用邮件策略，以便限制组织内部和外部的收件人和发件人之间的交互。除了对个人、组织内部的部门小组以及组织外部的实体之间的交互进行限制以外，某些组织还要满足下列邮件策略要求：
  
- 防止不适当的内容进入或离开组织
    
- 筛选机密组织信息
    
- 对特定个人发送或接收的邮件进行跟踪或复制
    
- 在传递之前重定向入站和出站邮件以便进行检查
    
- 对通过组织的邮件应用免责声明
    
> [!IMPORTANT]
> 在安装适当的 iFilter 之前，无法使用邮件流规则检查需要在电子邮件服务器 (（如 Adobe .pdf) ）上安装第三方 iFilter 的附件文件类型。 有关邮件流规则支持的文件类型详细信息，[请参阅使用邮件](/exchange/security-and-compliance/mail-flow-rules/inspect-message-attachments)流规则检查邮件流Office 365。
  
有关邮件流规则详细信息，请参阅 mail [flow rules in Exchange 2016。](/Exchange/policy-and-compliance/mail-flow-rules/mail-flow-rules?preserve-view=true&view=exchserver-2019)
  
## <a name="data-loss-prevention"></a>防止数据丢失

防止数据丢失 (DLP) 功能可帮助您通过深入的内容分析标识、监控和保护您组织中的敏感信息。 DLP 是一项对于企业邮件系统而言越来越重要的高级功能，因为对于企业非常重要的电子邮件包含需要保护的敏感信息。 利用 DLP 功能Exchange Online保护敏感数据，而不会影响工作者的工作效率。
  
您可以在 Exchange 管理中心 (EAC) 管理界面中配置 DLP 策略，以便您执行下列操作： 
  
- 启动预配置的策略模板，此模板可帮助您检测特定类型的敏感信息，如 PCI-DSS 数据、格雷姆-里奇-比利雷法案数据，甚至是区域设置特定的个人身份信息 (PII)。
    
- 使用现有传输规则条件和操作的强大功能，并添加新的传输规则。
    
- 在全面执行前，测试您的 DLP 策略的有效性。
    
- 整合您自己的自定义 DLP 策略模板和敏感的信息类型。
    
- 检测邮件附件、正文文本或主题行中的敏感信息，并调整邮件附件行为Exchange Online级别。
    
- 通过使用文档指纹检测敏感型数据。文档指纹可以帮助您基于文本形式（您可以用其定义传输规则和 DLP 策略）轻松地创建自定义敏感信息类型。
    
- 添加策略 使用技巧，这可以通过向 Outlook 2016、Outlook 2013、Outlook 网页版 和适用于设备的 OWA 用户显示通知来帮助减少数据丢失，还可通过允许误报报告来提高策略的有效性。 
    
- 查看 DLP 报告中的事件数据，或通过使用生成事件报告操作来添加自己的特定报告。
    
有关 DLP 的详细信息，请参阅[数据丢失防护](/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention)。
  
## <a name="journaling"></a>日记功能 

您可以配置 Exchange Online，以将电子邮件的副本记录到通过 SMTP 接收邮件的任何外部邮箱中。通过记录入站和出站电子邮件通信，日记功能可以帮助组织对法律、法规和组织遵从性要求做出响应。规划邮件保留和合规性时，了解日记功能及其如何适应组织的合规性策略，这一点非常重要。
  
您可以使用 Exchange 管理中心或远程 Windows PowerShell 管理日记规则。您可以按用户和通讯组列表来配置日记，并选择仅记录内部邮件日记、仅记录外部邮件日记或这两者。日记邮件不仅包含原始邮件，还包含有关发件人、收件人、副本和密送副本的信息。
  
若要确保成功可靠的日记解决方案，您需要完成以下任务：
  
- 确保日记目标不是邮箱Exchange Online邮箱。
    
- 在客户目录中为要用于日记记录的 SMTP 目标电子邮件地址创建联系人对象。
    
- 将第二个联系人对象创建为备用日记邮箱，用于在主日记邮箱不可用时捕获任何日记报告。
    
- 保持 SMTP 目标的正确管理、冗余、可用性、性能和功能级别，以确保始终成功接受邮件。
    
- 提供与 Exchange Server 和 Exchange 传输的具体互操作性，包括邮件格式、发件人/收件人信息集成和正确的内容转换。
    
有关日记的详细信息，请参阅[日记](/exchange/security-and-compliance/journaling/journaling)。
  
## <a name="feature-availability"></a>功能可用性

若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅Exchange Online[说明](exchange-online-service-description.md)。
