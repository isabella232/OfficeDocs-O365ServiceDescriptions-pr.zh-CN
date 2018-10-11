---
title: Exchange Online 限制
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 7/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 70b38a05-6cfa-4ced-a137-116019262fed
description: 查找各个服务方面的 Exchange Online 限制，包括通讯簿限制、邮箱存储空间限制以及报告和邮件跟踪限制等。
ms.openlocfilehash: 26fc2f55bc678103b92607978d3a5c746d5df8cc
ms.sourcegitcommit: 0b61418567c542fe1f22da3174627b427218e18d
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/10/2018
ms.locfileid: "25492792"
---
# <a name="exchange-online-limits"></a>Exchange Online 限制

查找各个服务方面的 Exchange Online 限制，包括通讯簿限制、邮箱存储空间限制以及报告和邮件跟踪限制等。
  
> [!NOTE]
>  如果需要任务协助，或者如果正在对问题进行故障排除，以下文章可能会很有帮助：  <br/> ？[电子邮件](https://support.office.com/en-us/article/Email-94275804-7147-4332-9ccd-5d421760a9ed?ui=en-US&amp;rs=en-US&amp;ad=US)（以帮助创建和发送电子邮件）  <br/> •[业务-管理帮助的 Office 365 中的电子邮件](https://go.microsoft.com/fwlink/?linkid=529722) <br/>   •[修复 Outlook 和 Microsoft 支持和恢复时的助理程序适用于 Office 365 的 Office 365 问题](https://diagnostics.office.com/) <br/>  • [Office 365 中的电子邮件未送达报告](https://go.microsoft.com/fwlink/?linkid=526653) <br/> • [Exchange Online 的帮助](https://go.microsoft.com/fwlink/?linkid=825607) <br/>
  
Microsoft Exchange Online 中的限制分为以下类别之一：
  
- [通讯簿限制](#address-book-limits)
    
- [邮箱存储限制](#mailbox-storage-limits)
    
- [容量报警](#capacity-alerts)
    
- [邮箱文件夹限制](#mailbox-folder-limits)
    
- [邮件限制](#message-limits)

- [接收和发送限制](#receiving-and-sending-limits)
    
- [报告和邮件跟踪限制](#reporting-and-message-trace-limits)
    
- [保留限制](#retention-limits)
    
- [通讯组限制](#distribution-group-limits)
    
- [日记、 传输和收件箱规则限制](#journal-transport-and-inbox-rule-limits)
    
- [审阅限制](#moderation-limits)
    
- [Exchange ActiveSync 限制](#exchange-activesync-limits)
    
> [!IMPORTANT]
>  • 应用于 Microsoft Office 365 组织的限制可能会有所不同具体取决于长组织具有已注册服务中。<br/> • 时限制更改在 Microsoft 数据中心，它可以花一些时间来更改应用于所有现有客户。<br/> • 不能修改大部分这些限制，但您和您的用户应了解它们。<br/> • 这些限制适用于内部和外部收件人。<br/> 默认情况下，Exchange Online Protection (EOP) • 保护 Exchange Online 邮箱。有关适用于 EOP 功能在 Exchange Online 的限制，请参阅[Exchange Online Protection Limits](../exchange-online-protection-service-description/exchange-online-protection-limits.md)。<br/> 有关 Office 365 组限制的信息 • 请参阅"如何管理我 groups?"中[了解有关 Office 365 组](https://go.microsoft.com/fwlink/?linkid=846714)。 
  
## <a name="address-book-limits"></a>通讯簿限制

- **地址列表限制** 在 Exchange Online 或 Exchange Server 2013 组织中可以创建的地址列表最大数量。此数目包括 Exchange Online 中的默认地址列表，如"所有联系人"和"所有组"。 
    
    > [!NOTE]
    > 最多可以将 20 个地址列表分配给一个脱机通讯簿 (OAB)。 
  
- **脱机通讯簿限制** 在 Exchange Online 或 Exchange Server 2013 组织中可以创建的脱机通讯簿 (OAB) 最大数量。 
    
- **通讯簿策略限制** 在 Exchange Online 或 Exchange Server 2013 组织中可以创建的通讯簿策略 (ABP) 最大数量。 
    
- **全局地址列表** 在 Exchange Online 或 Exchange Server 2013 组织中可以创建的全局地址列表 (GAL) 最大数量。 
    
### <a name="address-book-limits-across-office-365-options"></a>各个 Office 365 选项的通讯簿限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 商业协作版** <br/> |**Office 365 商业高级版** <br/> |**Office 365 企业版 E1** <br/> |**Office 365 企业版 E3** <br/> |**Office 365 企业版 E5** <br/> |**Office 365 企业版 F1** <br/> |
|地址列表限制  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |
|脱机通讯簿 (OAB) 限制  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|通讯簿策略 (ABP) 限制  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|全局地址列表限制  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
   
### <a name="address-book-limits-across-standalone-plans"></a>各个独立计划的通讯簿限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 计划 1** <br/> |**Exchange Online 计划 2** <br/> |**Exchange Online Kiosk** <br/> |
|地址列表限制  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |
|脱机通讯簿 (OAB) 限制  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|通讯簿策略 (ABP) 限制  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|全局地址列表限制  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
   
## <a name="mailbox-storage-limits"></a>邮箱存储限制

可用邮箱存储量由邮箱类型和用户的订阅许可证决定。管理员可以减小每位用户或全局的最大邮箱大小。
  
> [!NOTE]
> 不允许使用日记、传输规则或自动转发规则将邮件复制到 Exchange Online 邮箱中来进行存档。用户的存档邮箱只供该用户使用。Microsoft 保留拒绝在用户存档邮箱用于存储其他用户存档数据的情况下进行无限制存档的权利。 
  
### <a name="storage-limits-across-office-365-options"></a>跨 Office 365 选项的存储限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 商业协作版** <br/> |**Office 365 商业高级版** <br/> |**Office 365 企业版 E1** <br/> |**Office 365 企业版 E3** <br/> |**Office 365 企业版 E5** <br/> |**Office 365 企业版 F1** <br/> |
|用户邮箱  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |100 GB  <br/> |100 GB  <br/> |2 GB  <br/> |
|存档邮箱<sup>7、8</sup> <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |不受限制的<sup>1</sup> <br/> |不受限制的<sup>1</sup> <br/> |不可用<sup>4</sup> <br/> |
|共享邮箱  <br/> |50 GB<sup>2</sup> <br/> |50 GB<sup>2</sup> <br/> |50 GB<sup>2</sup> <br/> |50 GB<sup>2、 9</sup> <br/> |50 GB<sup>2、 9</sup> <br/> |50 GB<sup>2</sup> <br/> |
|资源邮箱  <br/> |50 GB<sup>3</sup> <br/> |50 GB<sup>3</sup> <br/> |50 GB<sup>3</sup> <br/> |50 GB<sup>3,9</sup> <br/> |50 GB<sup>3,9</sup> <br/> |50 GB<sup>3</sup> <br/> |
|网站邮箱<sup>5</sup> <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |不可用  <br/> |
|公用文件夹邮箱  <br/> |50 GB<sup>6</sup> <br/> |50 GB<sup>6</sup> <br/> |50 GB<sup>6</sup> <br/> |100 GB<sup>6</sup> <br/> |100 GB<sup>6</sup> <br/> |不可用  <br/> |
|组邮箱  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |
   
> [!NOTE]
> <sup>1</sup>每个用户最初在存档邮箱中接收 100 GB 的存储。自动扩展存档打开时，达到 100 GB 存储容量时，会自动添加额外的存储空间。有关详细信息，请参阅[Overview of Office 365 中的无限制存档](https://go.microsoft.com/fwlink/?linkid=844060)。请参阅[Office 365 路线图](http://go.microsoft.com/fwlink/?LinkId=509914)有关可用性的详细信息。<br/>  <sup>2</sup>访问共享的邮箱，用户必须拥有 Exchange Online 许可。共享的邮箱不需要单独的许可证。但是，没有许可证，共享的邮箱被限制为 50 GB。若要增加的邮箱大小，必须分配一个 E3 或 E5 许可证。这将增加到 100 GB 的邮箱。如果您想要启用存档邮箱或置于诉讼保留共享邮箱，然后 Exchange Online 计划 2 许可证或 Exchange Online 计划 1 与 Exchange Online Archiving 许可证则需要。如果您启用存档邮箱和共享邮箱的自动扩展存档，达到存档邮箱的 100 GB 存储容量时，会自动添加额外的存储空间。<br/>  <sup>3</sup>资源邮箱不需要许可证。但是，没有许可证，共享的邮箱被限制为 50 GB。若要增加的邮箱大小，必须分配一个 E3 或 E5 许可证。这将增加到 100 GB 的邮箱。<br/>  <sup>4</sup>存档邮箱不包括在 Exchange Online 网亭中。但是，他们可以通过 Exchange Online Archiving 作为购买。有关详细信息，请参阅[Exchange Online 存档 Service Description](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md)。<br/>  站点邮箱的创建和管理 SharePoint Online 中的<sup>5</sup> 。有关详细信息，请参阅[使用 Office 365 中的站点邮箱的准备](http://go.microsoft.com/fwlink/p/?LinkId=299131)。<br/>  仅限于 1000 个公用文件夹邮箱的<sup>6</sup>和所有公用文件夹邮箱的最大总大小为 50 TB。层次结构提供邮箱被限制为 100 个公用文件夹邮箱。<br/>  <sup>7</sup>存档邮箱可以仅用于存档的已应用许可证为单个用户或实体 （如共享邮箱） 的邮件。作为一种存储来自多个用户或实体的邮件使用存档邮箱已被禁止。例如，IT 管理员不能创建共享的邮箱，并让用户将其用于存档的显式目的 （通过抄送或密件抄送字段中，或通过传输规则） 复制。请注意多个联系人使用共享的邮箱不实际存储这些单个用户的电子邮件。多个用户具有访问权限，并为共享邮箱发送电子邮件。因此，仅存储在共享邮箱的电子邮件那些发送到或来自它，*为*共享邮箱。<br/>  <sup>8</sup>如果您已在 Exchange Online 中创建保留策略，消息将自动移动到用户的存档邮箱仅当用户的主邮箱已超过 10 MB。小于 10 MB 的邮箱，将保留策略将不会自动运行。<br/>  <sup>9</sup>共享和资源邮箱不需要许可证。但是，没有许可证，共享的邮箱被限制为 50 GB。若要增加的邮箱大小，必须分配一个 E3 或 E5 许可证。这将增加到 100 GB 的邮箱。 
  
### <a name="storage-limits-across-standalone-plans"></a>跨独立计划的存储限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 计划 1** <br/> |**Exchange Online 计划 2** <br/> |**Exchange Online Kiosk** <br/> |
|用户邮箱  <br/> |2 GB<sup>1</sup> <br/> |50 GB  <br/> |100 GB  <br/> |2 GB  <br/> |
|存档邮箱<sup>8、9</sup> <br/> |100 GB<sup>1</sup> <br/> |50 GB  <br/> |不受限制的<sup>2</sup> <br/> |不可用<sup>5</sup> <br/> |
|共享邮箱  <br/> |2 GB<sup>1</sup> <br/> |50 GB<sup>3</sup> <br/> |50 GB<sup>3,10</sup> <br/> |50 GB<sup>3</sup> <br/> |
|资源邮箱  <br/> |2 GB<sup>1</sup> <br/> |50 GB<sup>4</sup> <br/> |50 GB<sup>4,10</sup> <br/> |50 GB<sup>4</sup> <br/> |
|公用文件夹邮箱  <br/> |2 GB<sup>6</sup> <br/> |50 GB<sup>7</sup> <br/> |100 GB<sup>7</sup> <br/> |不可用  <br/> |
|组邮箱  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |
   
> [!NOTE]
> <sup>1</sup> ，这是 Exchange Server 2013 组织的默认邮箱大小。管理员可以更改此值为其组织。没有内部部署邮箱的最大存储限制。<br/>  <sup>2</sup>每个用户最初在存档邮箱中接收 100 GB 的存储。自动扩展存档打开时，达到 100 GB 存储容量时，会自动添加额外的存储空间。有关详细信息，请参阅[Overview of Office 365 中的无限制存档](https://go.microsoft.com/fwlink/?linkid=844060)。[Office 365 路线图](http://go.microsoft.com/fwlink/?LinkId=509914)有关的自动扩展可用性的详细信息，请参阅存档。<br/> <sup>3</sup>访问共享的邮箱，用户必须拥有 Exchange Online 许可。共享的邮箱不需要单独的许可证。但是，没有许可证，共享的邮箱被限制为 50 GB。若要增加的邮箱大小，必须分配的 Exchange Online 计划 2 许可证。这将增加到 100 GB 的邮箱。如果您想要启用存档邮箱或置于诉讼保留共享邮箱，然后 Exchange Online 计划 2 许可证或 Exchange Online 计划 1 与 Exchange Online Archiving 许可证则需要。如果您启用存档邮箱和共享邮箱的自动扩展存档，达到存档邮箱的 100 GB 存储容量时，会自动添加额外的存储空间。<br/> <sup>4</sup>资源邮箱不需要许可证。但是，没有许可证，共享的邮箱被限制为 50 GB。若要增加的邮箱大小，必须分配的 Exchange Online 计划 2 许可证。这将增加到 100 GB 的邮箱。<br/>  <sup>5</sup>存档邮箱不包括在 Exchange Online 网亭中。但是，他们可以通过 Exchange Online Archiving 作为购买。有关详细信息，请参阅[Exchange Online 存档 Service Description](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md)。<br/>  <sup>6</sup>这是 Microsoft Exchange Server 2013 组织的默认邮箱大小。管理员可以更改此值为其组织。在 Exchange Server 2013，您是限制为 100 个公用文件夹邮箱，并且所有公用文件夹邮箱的最大总大小为 50 TB。<br/>  <sup>7</sup> In Exchange Online 中，您是限制为 1000 个公用文件夹邮箱，并且所有公用文件夹邮箱的最大总大小为 50 TB。<br/>  <sup>8</sup>存档邮箱可以仅用于存档的单个用户或已为其应用许可证的实体的邮件。作为一种方法使用存档邮箱存储来自多个用户或实体的邮件已被禁止。例如，IT 管理员不能创建共享的邮箱，并让用户将复制 （通过抄送或密件抄送字段中，或通过传输规则） 共享的邮箱的存档的显式目的。<br/>  <sup>9</sup>如果您已在 Exchange Online 中创建保留策略，消息将自动移动到用户的存档邮箱仅当用户的主邮箱已超过 10 MB。小于 10 MB 的邮箱，将保留策略将不会自动运行。<br/>  <sup>10</sup>共享和资源邮箱不需要分配的许可证。但是，没有许可证，这些邮箱被限制为 50 GB。若要增加邮箱大小，Exchange Online 计划 2 许可证必须要分配。这将增加到 100 GB 的邮箱。 
  
> [!NOTE]
> 共享的邮箱不是直接登录。共享邮箱本身的用户帐户**禁用**（或"断开连接"） 中应保持状态。 
  
## <a name="capacity-alerts"></a>容量报警

Exchange Online 将在用户的邮箱接近或达到最大容量时提供三种通知类型：
  
- **警告** 用户收到电子邮件警告，其中指出邮箱正接近最大大小限制。此警告旨在建议用户删除不需要的邮件。 
    
- **禁止发送** 达到邮箱大小限制时，用户将收到禁止发送的通知电子邮件。在删除足够邮件以便邮箱低于大小限制之前，用户将无法发送新邮件。 
    
- **禁止发送/接收** Exchange Online 将在达到邮箱大小限制时拒绝任何传入邮件，并发送未送达报告 (NDR) 给发件人。发件人可选择稍后尝试重新发送该邮件。若要再次接收邮件，用户必须删除邮件，直到邮箱的使用容量低于大小限制为止。 
    
### <a name="capacity-alerts-across-office-365-options"></a>跨 Office 365 选项的容量警报

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 商业协作版** <br/> |**Office 365 商业高级版** <br/> |**Office 365 企业版 E1** <br/> |**Office 365 企业版 E3** <br/> |**Office 365 企业版 E5** <br/> |**Office 365 企业版 F1** <br/> |
|警告  <br/> |49 GB  <br/> |49 GB  <br/> |49 GB  <br/> |98 GB  <br/> |98 GB  <br/> |1.96 GB  <br/> |
|禁止发送  <br/> |49.5 GB  <br/> |49.5 GB  <br/> |49.5 GB  <br/> |99 GB  <br/> |99 GB  <br/> |1.98 GB  <br/> |
|禁止发送/接收  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |100 GB  <br/> |100 GB  <br/> |2 GB  <br/> |
   
### <a name="capacity-alerts-across-standalone-plans"></a>跨独立计划的容量警报

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 计划 1** <br/> |**Exchange Online 计划 2** <br/> |**Exchange Online Kiosk** <br/> |
|警告  <br/> |1.9 GB<sup>1</sup> <br/> |49 GB  <br/> |98 GB  <br/> |1.96 GB  <br/> |
|禁止发送  <br/> |2 GB<sup>1</sup> <br/> |49.5 GB  <br/> |99 GB  <br/> |1.98 GB  <br/> |
|禁止发送/接收  <br/> |2.3 GB<sup>1</sup> <br/> |50 GB  <br/> |100 GB  <br/> |2 GB  <br/> |
   
> [!NOTE]
> <sup>1</sup> 这是 Exchange Server 2013 组织的默认值。管理员可以为其组织更改此值。 
  
## <a name="mailbox-folder-limits"></a>邮箱文件夹限制

这些限制旨在将邮箱限制为在 Exchange Online 中受支持的已知尺寸。这些限制旨在防止文件夹中存在不限数量的邮箱项目，邮箱中存在不限数量的文件夹或 Exchange Online 组织中存在不限数量的公用文件夹。出于实用目的，邮箱文件夹限制实际上不受限制，足以支持大多数迁移到 Exchange Online 的 Exchange Online 邮箱和内部部署邮箱。
  
- **每个邮箱文件夹的邮件的最大数量** 为邮箱文件夹指定邮件的最大数量。达到该限制时，将无法传递新邮件或无法将其保存在某个文件夹中。 
    
- **每个邮箱文件夹的邮件数量的警告** 指定 Exchange Online 向邮箱所有者发送警告邮件前邮箱文件夹可以保留的邮件数量。达到此配额时，将每天发送一次警告消息。 
    
- **"可恢复邮件"文件夹中的每个文件夹的邮件最大数量** 指定"可恢复邮件"文件夹中每个文件夹可以包含的邮件的最大数量。文件夹超出此限制时，将无法存储新邮件。例如，如果"可恢复邮件"文件夹中的"删除"文件夹超出邮件计数限制，而邮箱所有者试图从邮箱中永久删除邮件，删除将会失败。 
    
- **"可恢复邮件"文件夹中的每个文件夹的邮件数量警告** 指定 Exchange Online 将事件记录到应用程序事件日志前，"可恢复邮件"文件夹中的每个文件夹可以保留的邮件数量。 
    
- **每个邮箱文件夹的子文件夹的最大数量** 指定可以在邮箱文件夹中创建的子文件夹的最大数量。达到此限制时，邮箱所有者将不能创建新的子文件夹。 
    
- **每个邮箱文件夹的子文件夹数量的警告** 指定 Exchange Online 向邮箱所有者发送警告消息之前，可以在邮箱文件夹中创建的子文件夹数量。达到此配额时，将每天发送一次警告消息。 
    
- **最大文件夹层次结构的深度** 指定邮箱的文件夹层次结构中级别的最大数量。达到此限制时，邮箱所有者将无法在邮箱文件夹的文件夹层次结构中创建其他级别。 
    
- **文件夹层次结构深度的警告** 指定 Exchange Online 向邮箱所有者发送警告消息之前，可以创建的邮箱文件夹的文件夹层次结构中的级别数量。达到此配额时，将每天发送一次警告消息。 
    
- **公用文件夹最大数** 指定完整公用文件夹层次结构中公用文件夹最大数。达到此限制后，必须删除现有公用文件夹，才可以创建新的公用文件夹。 
    
- **每个公用文件夹的子文件夹的最大数量** 指定可以在公用文件夹中创建的子文件夹的最大数量。当达到此限制时，无法在公用文件夹中创建新的子文件夹。 
    
- **每个公用文件夹的子文件夹数量的警告** 指定 Exchange Online 向文件夹所有者发送警告消息之前，可以在公用文件夹中创建的子文件夹数量。如果不存在所有者，则警告消息会发送到具有所有者权限的用户。达到此配额时，将每天发送一次警告消息。 
    
### <a name="mailbox-folder-limits-across-office-365-options"></a>跨 Office 365 选项的邮箱文件夹限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 商业协作版** <br/> |**Office 365 商业高级版** <br/> |**Office 365 企业版 E1** <br/> |**Office 365 企业版 E3** <br/> |**Office 365 企业版 E5** <br/> |**Office 365 企业版 F1** <br/> |
|每个邮箱文件夹的邮件的最大数量  <br/> |1 百万  <br/> |1 百万  <br/> |1 百万  <br/> |1 百万  <br/> |1 百万  <br/> |1 百万  <br/> |
|每个邮箱文件夹的邮件数量的警告  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |
|"可恢复邮件"文件夹中的每个文件夹的邮件最大数量  <br/> |3 百万  <br/> |3 百万  <br/> |3 百万  <br/> |3 百万  <br/> |3 百万  <br/> |3 百万  <br/> |
|主邮箱（未处于保留状态）中"可恢复的项目"文件夹的存储配额  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |
|主邮箱（处于保留状态）中"可恢复的项目"文件夹的存储配额  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |
|存档邮箱（未处于保留状态）中"可恢复的项目"文件夹的存储配额  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |不受限制的<sup>2</sup> <br/> |不受限制的<sup>2</sup> <br/> |30 GB  <br/> |
|存档邮箱（处于保留状态）中"可恢复的项目"文件夹的存储配额  <br/> |100 GB<sup>1</sup> <br/> |100 GB<sup>1</sup> <br/> |100 GB<sup>1</sup> <br/> |不受限制的<sup>2</sup> <br/> |不受限制的<sup>2</sup> <br/> |100 GB<sup>1</sup> <br/> |
|"可恢复邮件"文件夹中的每个文件夹的邮件数量警告  <br/> |2.75 百万  <br/> |2.75 百万  <br/> |2.75 百万  <br/> |2.75 百万  <br/> |2.75 百万  <br/> |2.75 百万  <br/> |
|每个邮箱文件夹的子文件夹的最大数量  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |
|每个邮箱文件夹的子文件夹数量的警告  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |
|最大文件夹层次结构深度  <br/> |300  <br/> |300  <br/> |300  <br/> |300  <br/> |300  <br/> |300  <br/> |
|文件夹层次结构深度的警告  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|公用文件夹最大数  <br/> |500,000  <br/> |500,000  <br/> |500,000  <br/> |500,000  <br/> |500,000  <br/> |不可用  <br/> |
|每个公用文件夹的子文件夹的最大数量  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |不可用  <br/> |
|每个公用文件夹的子文件夹数量的警告  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |不可用  <br/> |
   
> [!NOTE]
> <sup>1</sup> ，这是可恢复邮件文件夹中，不整个存档邮箱的配额的存储配额。存档邮箱的存储配额是无限为使用 Exchange Online 计划 2 的许可证的用户或用户拥有 Exchange Online 计划 1 和 Exchange Online Archiving 的许可证。有关增加可恢复的项目配额的信息，请参阅[提高可恢复的项目上的邮箱配额保留](http://technet.microsoft.com/library/a8bdcbdd-9298-462f-b889-df26037a990c.aspx)。<br/> <sup>2</sup>存档邮箱中的可恢复项目文件夹的初始存储配额为 100 GB。自动扩展存档打开时，达到可恢复邮件文件夹的存储容量时，会自动添加额外的存储空间。有关详细信息，请参阅[Overview of Office 365 中的无限制存档](https://go.microsoft.com/fwlink/?linkid=844060)。[Office 365 路线图](http://go.microsoft.com/fwlink/?LinkId=509914)有关的自动扩展可用性的详细信息，请参阅存档。 
  
### <a name="mailbox-folder-limits-across-standalone-plans"></a>跨独立计划的邮箱文件夹限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 计划 1** <br/> |**Exchange Online 计划 2** <br/> |**Exchange Online Kiosk** <br/> |
|每个邮箱文件夹的邮件的最大数量  <br/> |无限制<sup>1</sup> <br/> |1 百万  <br/> |1 百万  <br/> |1 百万  <br/> |
|每个邮箱文件夹的邮件数量的警告  <br/> |无限制  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |
|"可恢复邮件"文件夹中的每个文件夹的邮件最大数量  <br/> |无限制  <br/> |3 百万  <br/> |3 百万  <br/> |3 百万  <br/> |
|主邮箱（未处于保留状态）中"可恢复的项目"文件夹的存储配额  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |
|主邮箱（处于保留状态）中"可恢复的项目"文件夹的存储配额  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |
|存档邮箱（未处于保留状态）中"可恢复的项目"文件夹的存储配额  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |
|存档邮箱（处于保留状态）中"可恢复的项目"文件夹的存储配额  <br/> |100 GB<sup>2</sup> <br/> |100 GB<sup>2</sup> <br/> |不受限制的<sup>3</sup> <br/> |不受限制的<sup>3</sup> <br/> |
|"可恢复邮件"文件夹中的每个文件夹的邮件数量警告  <br/> |无限制  <br/> |2.75 百万  <br/> |2.75 百万  <br/> |2.75 百万  <br/> |
|每个邮箱文件夹的子文件夹的最大数量  <br/> |无限制  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |
|每个邮箱文件夹的子文件夹数量的警告  <br/> |无限制  <br/> |900  <br/> |900  <br/> |900  <br/> |
|最大文件夹层次结构深度  <br/> |无限制  <br/> |300  <br/> |300  <br/> |300  <br/> |
|文件夹层次结构深度的警告  <br/> |无限制  <br/> |250  <br/> |250  <br/> |250  <br/> |
|公用文件夹最大数  <br/> |1,000,000  <br/> |100,000  <br/> |100,000  <br/> |不可用  <br/> |
|每个公用文件夹的子文件夹的最大数量  <br/> |不适用  <br/> |1,000  <br/> |1,000  <br/> |不可用  <br/> |
|每个公用文件夹的子文件夹数量的警告  <br/> |不适用  <br/> |900  <br/> |900  <br/> |不可用  <br/> |
   
> [!NOTE]
> <sup>1</sup> Microsoft 建议每个邮箱文件夹不能超过 1,000,000 消息。><br/> <sup>2</sup>这是可恢复邮件文件夹中，不整个存档邮箱的配额的存储配额。存档邮箱的存储配额是无限为使用 Exchange Online 计划 2 的许可证的用户或用户拥有 Exchange Online 计划 1 和 Exchange Online Archiving 的许可证。有关增加可恢复的项目配额的信息，请参阅[提高可恢复的项目上的邮箱配额保留](http://technet.microsoft.com/library/a8bdcbdd-9298-462f-b889-df26037a990c.aspx)。<br/> <sup>3</sup>存档邮箱中的可恢复项目文件夹的初始存储配额为 100 GB。自动扩展存档打开时，达到可恢复邮件文件夹的存储容量时，会自动添加额外的存储空间。有关详细信息，请参阅[Overview of Office 365 中的无限制存档](https://go.microsoft.com/fwlink/?linkid=844060)。[Office 365 路线图](http://go.microsoft.com/fwlink/?LinkId=509914)有关的自动扩展可用性的详细信息，请参阅存档。 
  
## <a name="message-limits"></a>邮件限制

下列限制适用于每封电子邮件。
  
- **邮件大小限制** 需要邮件大小限制以防止大型邮件阻止送达其他邮件，并影响所有用户的服务性能。这些限制包括一些附件，并且适用于组织范围的所有邮件（入站、出站和内部）。将不送达超过该限制的邮件，同时发件人将收到未送达报告 (NDR)。尽管可以向上、向下或按每个用户配置邮件大小限制，但管理员仍可以创建传输规则以限制任何单个附件的最大大小。若要了解详细信息，请参阅 [Office 365 现在支持更大的电子邮件](https://blogs.office.com/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/)。
    
    > [!NOTE]
    > 特别电子邮件客户端可能具有更小的邮件大小限制，或者可能限制单个文件附件的大小为小于 Exchange Online 邮件大小限制的值。 
  
- **主题长度限制** 电子邮件的主题行中允许的文本字符的最大数目。 
    
- **文件附件限制** 电子邮件中允许的最大文件附件数。即使所有文件附件的总大小并不违反邮件大小限制，邮件中允许的附件数量也仍具有限制。限制由多部分邮件限制进行控制。 
    
- **文件附件大小限制** 单个附件的最大文件大小。 
    
    > [!NOTE]
    > 此为单个附件的最大文件大小。个别客户端程序（包括 Outlook Web App）可能会将附件大小限制为低于此最大值。Exchange ActiveSync 不基于个别附件实施附件大小限制。Exchange ActiveSync 邮件的所有附件总大小必须低于邮件大小限制。 
  
- **多部分邮件限制** MIME 多部分邮件中允许的邮件正文部分的最大数目。此限制还会控制邮件中允许的文件附件的最大数量。 
    
- **邮件嵌入深度限制** 电子邮件中允许的最大转发电子邮件数。 
    
### <a name="message-limits-across-office-365-options"></a>跨 Office 365 选项的邮件限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 商业协作版** <br/> |**Office 365 商业高级版** <br/> |**Office 365 企业版 E1** <br/> |**Office 365 企业版 E3** <br/> |**Office 365 企业版 E5** <br/> |**Office 365 企业版 F1** <br/> |
|邮件大小限制 - Outlook  <br/> |150 MB<sup>1、2</sup> <br/> |150 MB<sup>1、2</sup> <br/> |150 MB<sup>1、2</sup> <br/> |150 MB<sup>1、2</sup> <br/> |150 MB<sup>1、2</sup> <br/> |150 MB<sup>1、2</sup> <br/> |
|邮件大小限制 - OWA  <br/> |112 MB<sup>1、3</sup> <br/> |112 MB<sup>1、3</sup> <br/> |112 MB<sup>1、3</sup> <br/> |112 MB<sup>1、3</sup> <br/> |112 MB<sup>1、3</sup> <br/> |112 MB<sup>1、3</sup> <br/> |
|邮件大小限制 - Outlook for Mac  <br/> |150 MB<sup>1、2</sup> <br/> |150 MB<sup>1、2</sup> <br/> |150 MB<sup>1、2</sup> <br/> |150 MB<sup>1、2</sup> <br/> |150 MB<sup>1、2</sup> <br/> |150 MB<sup>1、2</sup> <br/> |
|邮件大小限制 - 迁移  <br/> |150 MB <sup>4</sup> <br/> |150 MB <sup>4</sup> <br/> |150 MB <sup>4</sup> <br/> |150 MB <sup>4</sup> <br/> |150 MB <sup>4</sup> <br/> |150 MB <sup>4</sup> <br/> |
|加密邮件的大小限制（针对使用包含新功能的 Office 365 邮件加密的订阅服务器）<sup>5</sup> <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|加密邮件的大小限制（针对使用旧版 Office 365 邮件加密的订阅服务器）<sup>5</sup> <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
|主题长度限制  <br/> |255 个字符  <br/> |255 个字符  <br/> |255 个字符  <br/> |255 个字符  <br/> |255 个字符  <br/> |255 个字符  <br/> |
|文件附件限制  <br/> |250 个附件  <br/> |250 个附件  <br/> |250 个附件  <br/> |250 个附件  <br/> |250 个附件  <br/> |250 个附件  <br/> |
|文件附件大小限制 - Outlook  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|文件附件大小限制 - OWA<sup>6</sup> <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |
|文件附件大小限制 - Outlook for Mac  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|多部分邮件限制  <br/> |250 个部分  <br/> |250 个部分  <br/> |250 个部分  <br/> |250 个部分  <br/> |250 个部分  <br/> |250 个部分  <br/> |
|邮件嵌入深度限制  <br/> |30 封嵌入邮件  <br/> |30 封嵌入邮件  <br/> |30 封嵌入邮件  <br/> |30 封嵌入邮件  <br/> |30 封嵌入邮件  <br/> |30 封嵌入邮件  <br/> |
   
> [!NOTE]
> <sup>1</sup>的 Office 365 邮箱的默认最大邮件大小为 25 MB。Office 365 管理员可以指定自定义 1 MB 和 150 MB 之间限制。但是，您可以发送或接收的邮件的大小也取决于您的电子邮件客户端或解决方案的支持。有关自定义您的组织的最大允许的邮件大小的详细信息，请参阅[Office 365 现在支持较大的电子邮件](https://blogs.office.com/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/)。<br/> <sup>2</sup>可以发送和接收 150 MB （其中邮件永远不会保留 Office 365 数据中心） 的 Office 365 用户之间的邮件。Office 365 数据中心外部路由的消息将受到其他 33%的翻译编码的增加，在其中案例最大邮件大小为 112 MB。<br/> <sup>3</sup> OWA 帐户消息可能受到编码增加 33%和限制的邮件大小的可能性可以发送给 25%小于配置的设置。例如，如果您在自定义您的设置为 100 MB 的最大邮件大小，您可以发送消息不大于 75 MB。<br/> <sup>4</sup>Exchange Online 计算移到 Exchange Online 的邮件大小。版本低于 Exchange Server 2013 的 Exchange 可能会报告较小的项大小。此限制适用于使用任何受支持 Exchange 邮箱复制服务的移动式迁移。其他迁移方法（直接转换、分步、IMAP、PST）和其他第三方工具受常规邮件大小限制。<br/> <sup>5</sup> OME 有关使用新功能的信息，请参阅[设置新的 Office 365 邮件加密功能构建到 Azure 信息保护的顶部](https://support.office.com/en-us/article/Set-up-new-Office-365-Message-Encryption-capabilities-built-on-top-of-Azure-Information-Protection-7ff0c040-b25c-4378-9904-b1b50210d00e?ui=en-US&amp;rs=en-US&amp;ad=US)。<br/> <sup>6</sup>无法附加超过 35MB 的单个文件。此外，还无法附加总大小超过 35MB 的文件。例如，如果附加了一个 34MB 的文件，只能另外附加一个 1MB 的文件。 
  
### <a name="message-limits-across-standalone-options"></a>跨独立选项的邮件限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 计划 1** <br/> |**Exchange Online 计划 2** <br/> |**Exchange Online Kiosk** <br/> |
|邮件大小限制 - Outlook  <br/> |10 MB<sup>4</sup> <br/> |150 MB<sup>1、2</sup> <br/> |150 MB<sup>1、2</sup> <br/> |150 MB<sup>2</sup> <br/> |
|邮件大小限制 - OWA  <br/> |10 MB<sup>4</sup> <br/> |112 MB<sup>1、3</sup> <br/> |112 MB<sup>1、3</sup> <br/> |150 MB<sup>1、2</sup> <br/> |
|邮件大小限制 - Outlook for Mac  <br/> |10 MB<sup>4</sup> <br/> |150 MB  <br/> |150 MB  <br/> ||
|邮件大小限制 - 迁移  <br/> |不适用  <br/> |150 MB <sup>5</sup> <br/> |150 MB <sup>5</sup> <br/> |150 MB <sup>5</sup> <br/> |
|加密邮件的大小限制（针对使用包含新功能的 Office 365 邮件加密的订阅服务器）<sup>6</sup> <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|加密邮件的大小限制（针对使用旧版 Office 365 邮件加密的订阅服务器）<sup>6</sup> <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
|主题长度限制  <br/> |255 个字符  <br/> |255 个字符  <br/> |255 个字符  <br/> |255 个字符  <br/> |
|文件附件限制  <br/> |1024 附件<sup>4</sup> <br/> |250 个附件  <br/> |250 个附件  <br/> |250 个附件  <br/> |
|文件附件大小限制 - Outlook  <br/> |35 MB<sup>4</sup> <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|文件附件大小限制 - OWA  <br/> |35 MB<sup>4</sup> <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |
|文件附件大小限制 - Outlook for Mac  <br/> |35 MB<sup>4</sup> <br/> |150 MB  <br/> |150 MB  <br/> |35 MB  <br/> |
|多部分邮件限制  <br/> |250 个部分  <br/> |250 个部分  <br/> |250 个部分  <br/> |250 个部分  <br/> |
|邮件嵌入深度限制  <br/> |30 封嵌入邮件  <br/> |30 封嵌入邮件  <br/> |30 封嵌入邮件  <br/> |30 封嵌入邮件  <br/> |
   
> [!NOTE]
> <sup>1</sup> office 365 管理员可以指定自定义 1 MB 和 150 MB 之间限制。但是，您可以发送或接收的邮件的大小也取决于您的电子邮件客户端或解决方案的支持。有关自定义您的组织的最大允许的邮件大小的详细信息，请参阅[Office 365 现在支持较大的电子邮件](https://blogs.office.com/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/)。<br/> <sup>2</sup>可以发送和接收 150 MB （其中邮件永远不会保留 Office 365 数据中心） 的 Office 365 用户之间的邮件。Office 365 数据中心外部路由的消息将受到其他 33%的翻译编码的增加，在其中案例最大邮件大小为 112 MB。<br/> <sup>3</sup> OWA 帐户消息可能受到编码增加 33%和限制的邮件大小的可能性可以发送给 25%小于配置的设置。例如，如果您在自定义您的设置为 100 MB 的最大邮件大小，您可以发送消息不大于 75 MB。<br/> <sup>4</sup> ，这是 Exchange Server 2013 组织的默认限制。管理员可以更改此值为其组织。<br/> <sup>5</sup>通过 Exchange Online 来计算的邮件被移动到 Exchange Online 的大小。Exchange Server 2013 之前的 Exchange 版本可能会报告较小的项目。<br/> <sup>6</sup> OME 有关使用新功能的信息，请参阅[设置新的 Office 365 邮件加密功能构建到 Azure 信息保护的顶部](https://support.office.com/en-us/article/Set-up-new-Office-365-Message-Encryption-capabilities-built-on-top-of-Azure-Information-Protection-7ff0c040-b25c-4378-9904-b1b50210d00e?ui=en-US&amp;rs=en-US&amp;ad=US)。 
  
## <a name="receiving-and-sending-limits"></a>接收和发送限制

接收和发送限制可用于防止出现垃圾邮件和大量邮件蠕虫或病毒。这些限制可以帮助保护系统的运行状况和我们用户的安全。
  
### <a name="receiving-limits"></a>接收限制

接收限制应用于用户、组或公用文件夹每小时可以接收的邮件数。这适用于从 Internet 和本地服务器收到的邮件。超出接收限制时，只要有电子邮件发送到此邮箱，都会收到未送达报告，指出邮箱已超出最大发送阈值。一个小时后，限制会进行刷新，邮箱将能够再次接收邮件。
  
||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 商业协作版** <br/> |**Office 365 商业高级版 Office** <br/> |**Office 365 企业版 E1** <br/> |**Office 365 企业版 E3** <br/> |**Office 365 企业版 E5** <br/> |**Office 365 企业版 F1** <br/> |
|接收的邮件数  <br/> |每小时 3600 消息  <br/> |每小时 3600 消息  <br/> |每小时 3600 消息  <br/> |每小时 3600 消息  <br/> |每小时 3600 封邮件  <br/> |每小时 3600 封邮件  <br/> |
   
### <a name="sending-limits"></a>发送限制

发送限制应用于收件人数、邮件数和用户可以从其 Exchange Online 帐户发送的每封邮件的收件人数。
  
> [!NOTE]
> 对于存储在组织的通讯簿中的通讯组，这类组计数为一个收件人。对于存储在邮箱的"联系人"文件夹中的通讯组，单独计数组的各个成员。 
  
- **收件人速率限制** 为了阻止送达未经请求的批量邮件，Exchange Online 提供收件人限制以防止用户和应用程序发送大量电子邮件。这些限制适用于每个用户的所有出站和内部邮件。 
    
    > [!NOTE]
    > 需要发送合法批量电子邮件的 Exchange Online 客户（例如，客户新闻通讯）应使用专门提供这些服务的第三方提供商。 
  
- **收件人限制** 一封电子邮件的"收件人:"、"抄送:"和"密件抄送:"字段中允许的最大邮件收件人数。 
    
    > [!NOTE]
    > 出于收件人速率限制和收件人限制的目的，组织共享通讯簿中存储的通讯组作为一个收件人计数。在个人通讯列表中，每个收件人单独计数。 
  
- **邮件速率限制** 邮件速率限制确定用户在指定时间段内可以从其 Exchange Online 帐户发送的邮件数。此限制有助于防止单个发件人过多消耗系统资源。如果用户提交邮件的速度超过了通过 SMTP 客户端提交邮件的限制，邮件将被拒绝，并且客户端将需要重试。 
    
#### <a name="sending-limits-across-office-365-options"></a>跨 Office 365 选项的发送限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 商业协作版** <br/> |**Office 365 商业高级版** <br/> |**Office 365 企业版 E1** <br/> |**Office 365 企业版 E3** <br/> |**Office 365 企业版 E5** <br/> |**Office 365 企业版 F1** <br/> |
|收件人速率限制  <br/> |每天 10,000 个收件人  <br/> |每天 10,000 个收件人  <br/> |每天 10,000 个收件人  <br/> |每天 10,000 个收件人  <br/> |每天 10,000 个收件人  <br/> |每天 10,000 个收件人  <br/> |
|收件人限制  <br/> |500 个收件人  <br/> |500 个收件人  <br/> |500 个收件人  <br/> |500 个收件人  <br/> |500 个收件人  <br/> |500 个收件人  <br/> |
|收件人代理服务器地址限制  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |
|邮件速率限制（仅适用于 SMTP 客户端提交）  <br/> |每分钟 30 封邮件  <br/> |每分钟 30 封邮件  <br/> |每分钟 30 封邮件  <br/> |每分钟 30 封邮件  <br/> |每分钟 30 封邮件  <br/> |每分钟 30 封邮件  <br/> |
   
#### <a name="sending-limits-across-standalone-options"></a>跨独立选项的发送限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 计划 1** <br/> |**Exchange Online 计划 2** <br/> |**Exchange Online Kiosk** <br/> |
|收件人速率限制  <br/> |无限制<sup>1</sup> <br/> |每天 10,000 个收件人  <br/> |每天 10,000 个收件人  <br/> |每天 10,000 个收件人  <br/> |
|收件人限制  <br/> |500 个收件人<sup>1</sup> <br/> |500 个收件人  <br/> |500 个收件人  <br/> |500 个收件人  <br/> |
|收件人代理服务器地址限制  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |
   
> [!NOTE]
> <sup>1</sup> 这是 Exchange Server 2013 组织的默认限制。管理员可以为其组织更改此值。 
  
## <a name="reporting-and-message-trace-limits"></a>报告和邮件跟踪限制
<a name="bkmk_Reporting_Message_Trace_Limits"> </a>

有关报告和邮件跟踪限制，请参阅 [Exchange Online Protection 中的报告和邮件跟踪](http://go.microsoft.com/fwlink/p/?LinkId=394248)中的"报告和邮件跟踪数据可用性和延迟"部分。
  
## <a name="retention-limits"></a>保留限制
<a name="RetentionLimits"> </a>

这些限制控制可以访问收件箱中特定文件夹中的项目的时间长度。
  
- **"已删除邮件"文件夹保留期** 邮件在被自动删除之前可在"已删除邮件"文件夹中保留的最大天数。 
    
- **保留期从已删除邮件文件夹**永久删除之前保留从已删除邮件文件夹中删除项目的最大天数。 
    
- **"垃圾邮件"文件夹保留期** 邮件在被自动删除之前可在"垃圾邮件"文件夹中保留的最大天数。 
    
### <a name="retention-limits-across-office-365-options"></a>跨 Office 365 选项的保留限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 商业协作版** <br/> |**Office 365 商业高级版** <br/> |**Office 365 企业版 E1** <br/> |**Office 365 企业版 E3** <br/> |**Office 365 企业版 E5** <br/> |**Office 365 企业版 F1** <br/> |
|"已删除邮件"文件夹保留期  <br/> |无限制<sup>1</sup> <br/> |无限制<sup>1</sup> <br/> |无限制<sup>1</sup> <br/> |无限制<sup>1</sup> <br/> |无限制<sup>1</sup> <br/> |无限制<sup>1</sup> <br/> |
|从"已删除邮件"文件夹中删除的邮件的保留期  <br/> |14 天<sup>1</sup> <br/> |14 天<sup>1</sup> <br/> |14 天<sup>1</sup> <br/> |14 天<sup>1</sup> <br/> |14 天<sup>1</sup> <br/> |14 天<sup>1</sup> <br/> |
|"垃圾邮件"文件夹保留期  <br/> |30 天  <br/> |30 天  <br/> |30 天  <br/> |30 天  <br/> |30 天  <br/> |30 天  <br/> |
   
> [!NOTE]
> <sup>1</sup> 这是默认限制。管理员可以为其组织更改此值。 
  
### <a name="retention-limits-across-standalone-options"></a>跨独立选项的保留限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 计划 1** <br/> |**Exchange Online 计划 2** <br/> |**Exchange Online Kiosk** <br/> |
|"已删除邮件"文件夹保留期  <br/> |无限制<sup>1</sup> <br/> |无限制<sup>1</sup> <br/> |无限制<sup>1</sup> <br/> |无限制<sup>1</sup> <br/> |
|从"已删除邮件"文件夹中删除的邮件的保留期  <br/> |14 天<sup>1</sup> <br/> |14 天<sup>2</sup> <br/> |14 天<sup>2</sup> <br/> |14 天<sup>2</sup> <br/> |
|"垃圾邮件"文件夹保留期  <br/> |2 年<sup>1</sup> <br/> |30 天  <br/> |30 天  <br/> |30 天  <br/> |
   
> [!NOTE]
> <sup>1</sup> 这是默认限制。管理员可以为其组织更改此值。<br/> <sup>2</sup>这是 Exchange Online 组织的默认值。管理员可以更改此值为 30 天内的组织中的邮箱的最大值。 
  
## <a name="distribution-group-limits"></a>通讯组限制

这些限制适用于组织的共享地址簿中的通讯组。
  
- **通讯组成员的最大数目**通讯组扩展后确定总收件人计数。 
    
- **限制向大型通讯组发送邮件** 包含此限制所指定数目的成员的通讯组必须已配置传递管理或邮件审批选项。传递管理选项将指定一个允许向通讯组发送邮件的发件人的列表。邮件审批选项将指定一个或多个必须审批发送到通讯组的所有邮件的审阅人。 
    
- **大型通讯组的最大邮件大小** 如果将一封邮件发送给 5,000 个收件人或更多收件人，则此邮件的大小不能超出此限制。如果此邮件的大小超出此限制，则不会传递此邮件，并且发件人会收到一份未送达报告 (NDR)。在通讯组扩展后确定总收件人计数。 
    
### <a name="distribution-group-limits-across-office-365-options"></a>跨 Office 365 选项的通讯组限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 商业协作版** <br/> |**Office 365 商业高级版** <br/> |**Office 365 企业版 E1** <br/> |**Office 365 企业版 E3** <br/> |**Office 365 企业版 E5** <br/> |**Office 365 企业版 F1** <br/> |
|通讯组成员的最大数目<sup>1</sup> <br/> |100,000 个成员  <br/> |100,000 个成员  <br/> |100,000 个成员  <br/> |100,000 个成员  <br/> |100,000 个成员  <br/> |100,000 个成员  <br/> |
|限制向大型通讯组发送邮件  <br/> |5,000 个成员或更多成员  <br/> |5,000 个成员或更多成员  <br/> |5,000 个成员或更多成员  <br/> |5,000 个成员或更多成员  <br/> |5,000 个成员或更多成员  <br/> |5,000 个成员或更多成员  <br/> |
|至 100,000 5,000 个成员的通讯组的最大邮件大小  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
|通讯组的 100,000 或多个成员的最大邮件大小  <br/> |5 MB  <br/> |5 MB  <br/> |5 MB  <br/> |5 MB  <br/> |5 MB  <br/> |5 MB  <br/> |
|通讯组所有者的最大数量  <br/> |10   <br/> |10   <br/> |10   <br/> |10   <br/> |10   <br/> |10   <br/> |
|用户可创建的组的最大数目  <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup>如果您使用的 Azure Active Directory 目录同步，您可以从您的本地 Active Directory 同步到 Azure Active Directory 的通讯组成员的最大数目是 15000。如果您使用 Azure AD 连接，该号码是 50,000 个。<br/> <sup>2</sup> 此限制同样适用于管理员。 
  
### <a name="distribution-group-limits-across-standalone-options"></a>跨独立选项的通讯组限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 计划 1** <br/> |**Exchange Online 计划 2** <br/> |**Exchange Online Kiosk** <br/> |
|通讯组成员的最大数目  <br/> |100,000 个成员<sup>1</sup> <br/> |100,000 个成员  <br/> |100,000 个成员  <br/> |100,000 个成员  <br/> |
|限制向大型通讯组发送邮件  <br/> |5,000 个成员或更多成员<sup>1</sup> <br/> |5,000 个成员或更多成员  <br/> |5,000 个成员或更多成员  <br/> |5,000 个成员或更多成员  <br/> |
|通讯组所有者的最大数量  <br/> |10   <br/> |10   <br/> |10   <br/> |10   <br/> |
|用户可创建的组的最大数目  <br/> |250<sup>2</sup> <br/> |250<sup>2</sup> <br/> |250<sup>2</sup> <br/> |250<sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> 这是 Exchange Server 2013 组织的默认限制。管理员可以为其组织更改此值。<br/> <sup>2</sup> 此限制同样适用于管理员。 
  
## <a name="journal-transport-and-inbox-rule-limits"></a>日记、传输和收件箱规则限制

以下列表包含适用于日记规则、传输规则的限制（也称为组织范围规则）以及适用于收件箱规则的限制。收件箱规则由单个用户设置，并适用于该用户邮箱发送和接收的邮件。
  
- **最大日记规则数** 组织中可具有的日志规则的最大数目。 
    
- **最大传输规则数** 组织中可具有的规则的最大数目。 
    
- **单个传输规则的最大大小**最大可在单个传输规则中使用的字符数。条件、 例外和操作中使用的字符。 
    
- **所有传输规则中使用的所有正则表达式的字符限制** 组织的所有传输规则条件和例外中的所有正则表达式所使用的字符总数。可具有少量使用长而复杂的正则表达式的规则，也可具有多个使用简单正则表达式的规则。 
    
- **附件内容的扫描限制** 传输规则条件使你可以检查邮件附件的内容，但只能检查从附件提取的文本中的前 1 MB 内容。1 MB 的限制指的是从附件中提取的文本，而不是附件的文件大小。例如，一个 2 MB 的文件可能包含小于 1 MB 的文本，因此将检查整个文本 
    
- **所有传输规则向一封邮件添加的收件人的最大数目** 当一封邮件由不同的传输规则使用时，只能向该邮件添加有限数目的收件人。在达到此限制后，不会再向该邮件添加任何其余的收件人。此外，传输规则不能向邮件添加通讯组。 
    
- **转发邮件的收件人限制** 可以为收件箱或包含重定向操作的传输规则配置的收件人的最大数目。如果某个规则配置为将邮件重定向到比此数目多的收件人，则不应用该规则，任何满足该规则条件的邮件将不重定向到该规则中列出的任何收件人。 
    
- **重定向邮件的次数** 将根据收件箱规则自动重定向、转发或答复邮件的次数。例如，用户 A 有一个根据发件人将邮件重定向到用户 B 的收件箱规则。用户 B 有一个根据主题行中的关键字将邮件转发到用户 C 的收件箱规则。如果某邮件同时满足这两个条件，则由于仅允许一次重定向，该邮件仅发送到用户 B，不会转发到用户 C。在这种情况下，邮件将被丢弃，而不会向用户 B 发送未送达报告 (NDR) 以指明邮件未发送给用户 C。 
    
### <a name="journal-transport-and-inbox-rule-limits-across-office-365-options"></a>跨 Office 365 选项的日记、传输和收件箱规则限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 商业协作版** <br/> |**Office 365 商业高级版** <br/> |**Office 365 企业版 E1** <br/> |**Office 365 企业版 E3** <br/> |**Office 365 企业版 E5** <br/> |**Office 365 企业版 F1** <br/> |
|日记规则的最大数目  <br/> |10 条规则  <br/> |10 条规则  <br/> |10 条规则  <br/> |10 条规则  <br/> |10 条规则  <br/> |10 条规则  <br/> |
|传输规则的最大数目  <br/> |300 条规则  <br/> |300 条规则  <br/> |300 条规则  <br/> |300 条规则  <br/> |300 条规则  <br/> |300 条规则  <br/> |
|单个传输规则的最大大小  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |
|所有传输规则中使用的所有正则表达式的字符限制  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |
|附件内容的扫描限制  <br/> |1 MB  <br/> |1 MB  <br/> |1 MB  <br/> |1 MB  <br/> |1 MB  <br/> |1 MB  <br/> |
|所有传输规则添加到邮件的收件人的最大数目  <br/> |100 个收件人  <br/> |100 个收件人  <br/> |100 个收件人  <br/> |100 个收件人  <br/> |100 个收件人  <br/> |100 个收件人  <br/> |
|转发邮件的收件人限制  <br/> |10 个收件人  <br/> |10 个收件人  <br/> |10 个收件人  <br/> |10 个收件人  <br/> |10 个收件人  <br/> |10 个收件人  <br/> |
|重定向邮件的次数  <br/> |1 次重定向  <br/> |1 次重定向  <br/> |1 次重定向  <br/> |1 次重定向  <br/> |1 次重定向  <br/> |1 次重定向  <br/> |
   
### <a name="journal-transport-and-inbox-rule-limits-across-standalone-options"></a>跨独立选项的日记、传输和收件箱规则限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 计划 1** <br/> |**Exchange Online 计划 2** <br/> |**Exchange Online Kiosk** <br/> |
|日记规则的最大数目  <br/> |无限制  <br/> |10 条规则  <br/> |10 条规则  <br/> |10 条规则  <br/> |
|传输规则的最大数目  <br/> |无限制  <br/> |300 条规则  <br/> |300 条规则  <br/> |300 条规则  <br/> |
|单个传输规则的最大大小  <br/> |40 KB  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |
|所有传输规则中使用的所有正则表达式的字符限制  <br/> |无限制  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |
|所有传输规则添加到邮件的收件人的最大数目  <br/> |无限制  <br/> |100 个收件人  <br/> |100 个收件人  <br/> |100 个收件人  <br/> |
|转发邮件的收件人限制  <br/> |无限制  <br/> |10 个收件人  <br/> |10 个收件人  <br/> |10 个收件人  <br/> |
|重定向邮件的次数  <br/> |3 次重定向  <br/> |1 次重定向  <br/> |1 次重定向  <br/> |1 次重定向  <br/> |
  
## <a name="moderation-limits"></a>审阅限制
<a name="ModerationLimits"> </a>

这些限制将控制用于适用于通讯组和传输规则的邮件审批的审阅设置。
  
- **仲裁邮箱的最大大小** 如果仲裁邮箱超出此限制，则以未送达报告 (NDR) 形式将需要审阅的邮件返回给发件人。 
    
- **审阅人的最大数量**您可以分配给单个审阅的通讯组或的审阅人的最大数量可以添加到使用单个传输规则的邮件。请注意，不能仲裁人为指定通讯组。 
    
- **等待审阅的邮件的过期时间** 默认情况下，等待审阅的邮件在 2 天后过期。但每 7 天将处理一次已过期的中继邮件。这意味着，中继邮件会在 2 到 9 天内随时过期。 
    
- **过期的审阅通知邮件的最大速率** 此限制将设置 1 个小时内过期中继邮件的通知邮件的最大数目。对数据中心内的每个邮箱数据库施加了此限制。 
    
    在使用率较高的时段内，一些发件人可能无法收到已过期的中继邮件的通知邮件。但仍可使用送达报告来发现这些通知。
    
### <a name="moderation-limits-across-office-365-options"></a>跨 Office 365 选项的审阅限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 商业协作版** <br/> |**Office 365 商业高级版** <br/> |**Office 365 企业版 E1** <br/> |**Office 365 企业版 E3** <br/> |**Office 365 企业版 E5** <br/> |**Office 365 企业版 F1** <br/> |
|仲裁邮箱的最大大小  <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |
|审阅人的最大数目  <br/> |10 个审阅人  <br/> |10 个审阅人  <br/> |10 个审阅人  <br/> |10 个审阅人  <br/> |10 个审阅人  <br/> |10 个审阅人  <br/> |
|等待审阅的邮件的过期时间  <br/> |2 天  <br/> |2 天  <br/> |2 天  <br/> |2 天  <br/> |2 天  <br/> |2 天  <br/> |
|过期的审阅通知邮件的最大速率  <br/> |每小时 300 个过期通知  <br/> |每小时 300 个过期通知  <br/> |每小时 300 个过期通知  <br/> |每小时 300 个过期通知  <br/> |每小时 300 个过期通知  <br/> |每小时 300 个过期通知  <br/> |
   
### <a name="moderation-limits-across-standalone-options"></a>跨独立选项的审阅限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 计划 1** <br/> |**Exchange Online 计划 2** <br/> |**Exchange Online Kiosk** <br/> |
|仲裁邮箱的最大大小  <br/> |无限制<sup>1</sup> <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |
|审阅人的最大数目  <br/> |无限制  <br/> |10 个审阅人  <br/> |10 个审阅人  <br/> |10 个审阅人  <br/> |
|等待审阅的邮件的过期时间  <br/> |5 天<sup>1</sup> <br/> |2 天  <br/> |2 天  <br/> |2 天  <br/> |
|过期的审阅通知邮件的最大速率  <br/> |每小时 300 个过期通知  <br/> |每小时 300 个过期通知  <br/> |每小时 300 个过期通知  <br/> |每小时 300 个过期通知  <br/> |
   
> [!NOTE]
> <sup>1</sup> 这是 Exchange Server 2013 组织的默认限制。管理员可以为其组织更改此值。 
  
## <a name="exchange-activesync-limits"></a>Exchange ActiveSync 限制
<a name="BKMK_ExchangeActiveSync_Limits"> </a>

以下限制适用于 Microsoft Exchange ActiveSync，一个在移动设备和 Exchange 之间同步邮箱数据的客户端协议。 
  
- **Exchange ActiveSync 设备限制** 每个邮箱中的 Exchange ActiveSync 设备的最大数量。 
    
- **Exchange ActiveSync 设备删除限制** Exchange 管理员在一个月内可删除的 Exchange ActiveSync 设备的最大数量。 
    
- **Exchange ActiveSync 文件附件限制** Exchange ActiveSync 设备可以发送或接收的消息文件附件的最大大小。 
    
### <a name="exchange-activesync-limits-across-office-365-options"></a>Office 365 选项中的 Exchange ActiveSync 限制

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 商业协作版** <br/> |**Office 365 商业高级版** <br/> |**Office 365 企业版 E1** <br/> |**Office 365 企业版 E3** <br/> |**Office 365 企业版 E5** <br/> |**Office 365 企业版 F1** <br/> |
|Exchange ActiveSync 设备限制  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |
|Exchange ActiveSync 设备删除限制  <br/> |20  <br/> |20  <br/> |20  <br/> |20  <br/> |20  <br/> |20  <br/> |
|Exchange ActiveSync 文件附件限制  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
   
### <a name="exchange-activesync-limits-across-standalone-options"></a>独立选项中的 Exchange ActiveSync 限制

||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 计划 1** <br/> |**Exchange Online 计划 2** <br/> |**Exchange Online Kiosk** <br/> |
|Exchange ActiveSync 设备限制  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |
|Exchange ActiveSync 设备删除限制  <br/> |20  <br/> |20  <br/> |20  <br/> |20  <br/> |
|Exchange ActiveSync 文件附件限制  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
