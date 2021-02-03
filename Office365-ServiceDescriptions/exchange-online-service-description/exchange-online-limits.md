---
title: Exchange Online 限制
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-limits
ms.service: o365-administration
localization_priority: High
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 70b38a05-6cfa-4ced-a137-116019262fed
description: 查找各个服务方面的 Exchange Online 限制，包括通讯簿限制、邮箱存储空间限制以及报告和邮件跟踪限制等。
ms.openlocfilehash: 325396d0046e857d1c7812f9d8640a95018c248b
ms.sourcegitcommit: bd0cf8920c64e171967d7dd61b7f988bd093c073
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 02/02/2021
ms.locfileid: "50080288"
---
# <a name="exchange-online-limits"></a>Exchange Online 限制

查找各个服务方面的 Exchange Online 限制，包括通讯簿限制、邮箱存储空间限制以及报告和邮件跟踪限制等。

> [!NOTE]
> 如果需要任务协助，或者如果正在对问题进行故障排除，以下文章可能会很有帮助：
> - [电子邮件](https://support.office.com/article/94275804-7147-4332-9ccd-5d421760a9ed) (帮助创建和发送电子邮件) 
>- [Microsoft 365 商业版中的电子邮件 - 管理员帮助](https://go.microsoft.com/fwlink/?linkid=529722)
>- [使用 Microsoft 支持和恢复助手修复 Outlook 和 Microsoft 365 问题](https://diagnostics.office.com/)
>- [电子邮件未送达报告](https://go.microsoft.com/fwlink/?linkid=526653)
>- [Exchange Online 帮助](https://go.microsoft.com/fwlink/?linkid=825607)

Microsoft Exchange Online 的限制可归为以下几个类别：

- [通讯簿限制](#address-book-limits)

- [邮箱存储限制](#mailbox-storage-limits)

- [容量报警](#capacity-alerts)

- [Mailbox folder limits](#mailbox-folder-limits)

- [邮件限制](#message-limits)

- [接收和发送限制](#receiving-and-sending-limits)

- [Reporting and message trace limits](#reporting-and-message-trace-limits)

- [保留限制](#retention-limits)

- [通讯组限制](#distribution-group-limits)

- [日记、传输和收件箱规则限制](#journal-transport-and-inbox-rule-limits)

- [审阅限制](#moderation-limits)

- [Exchange ActiveSync 限制](#exchange-activesync-limits)

> [!IMPORTANT]
> - 应用于 Microsoft 365 组织的限制可能因组织已在服务中注册时间而不同。
> - 如果 Microsoft 数据中心内的限制更改，可能需要一段时间，才能将更改应用于所有现有客户。
> - 虽然您无法修改其中大多数限制，但您和您的用户应了解它们。
> - 这些限制适用于内部收件人和外部收件人。
> - Exchange Online Protection (EOP) 默认保护 Exchange Online 邮箱。 有关适用于 Exchange Online 中的 EOP 功能的限制，请参阅 [Exchange Online Protection 限制](../exchange-online-protection-service-description/exchange-online-protection-limits.md)。
> - 有关 Office 365 组限制的信息，请参阅"如何管理我的组？" 在 ["了解 Microsoft 365 组"中](https://go.microsoft.com/fwlink/?linkid=846714)。

## <a name="address-book-limits"></a>通讯簿限制

- **地址列表限制**：可以在 Exchange Online 或 2013 Exchange Server创建的地址列表的最大数量。 此数目包括 Exchange Online 中的默认地址列表，如"所有联系人"和"所有组"。

    > [!NOTE]
    > 最多可以将 20 个地址列表分配给一个脱机通讯簿 (OAB)。

- **脱机通讯簿限制**：可以在 Exchange Online 或 (2013) 中创建的脱机通讯簿的最大 Exchange Server OAB 通讯簿数。

- **通讯簿策略限制**：在 Exchange Online 或 (2013) 中创建的 ABP 策略Exchange Server数量。

- **全局地址列表**：在 Exchange Online 或 (2013) 中创建的全局地址列表Exchange Server GAL 列表。

### <a name="address-book-limits"></a>通讯簿限制

| 功能 | Microsoft 365 商业基础版 | Microsoft 365 商业标准版 | Office 365 企业版 E1 | Office 365 企业版 E3 | Office 365 企业版 E5 | Office 365 企业版 F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|地址列表限制|1000|1000|1000|1000|1000|1000|
|脱机通讯簿 (OAB) 限制|250|250|250|250|250|250|
|通讯簿策略 (ABP) 限制|250|250|250|250|250|250|
|全局地址列表限制|250|250|250|250|250|250|

### <a name="address-book-limits-across-standalone-plans"></a>各个独立计划的通讯簿限制

| 功能 | Exchange Server 2013 | Exchange Online 计划 1 | Exchange Online 计划 2 | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|地址列表限制|1000|1000|1000|1000|
|脱机通讯簿 (OAB) 限制|250|250|250|250|
|通讯簿策略 (ABP) 限制|250|250|250|250|
|全局地址列表限制|250|250|250|250|

## <a name="mailbox-storage-limits"></a>邮箱存储限制

可用邮箱存储量由邮箱类型和用户的订阅许可证决定。管理员可以减小每位用户或全局的最大邮箱大小。

> [!NOTE]
> 不允许使用日记、传输规则或自动转发规则将邮件复制到 Exchange Online 邮箱中来进行存档。 用户的存档邮箱只供该用户使用。 在用户的存档邮箱用于存储其他用户的存档数据或其他不当使用的情况下，Microsoft 保留拒绝无限制存档的权利。

### <a name="storage-limits"></a>存储限制

| 功能 | Microsoft 365 商业基础版 | Microsoft 365 商业标准版 | Office 365 企业版 E1 | Office 365 企业版 E3 | Office 365 企业版 E5 | Office 365 企业版 F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|用户邮箱|50 GB|50 GB|50 GB|100 GB|100 GB|2 GB|
|存档邮箱<sup>7，8</sup>|50 GB|50 GB|50 GB|Unlimited<sup>1</sup>|Unlimited<sup>1</sup>|不可用<sup>4</sup>|
|共享邮箱<sup>10</sup>|50 GB<sup>2</sup>|50 GB<sup>2</sup>|50 GB<sup>2</sup>|50/100 GB<sup>2，9</sup>|50/100 GB<sup>2，9</sup>|50 GB<sup>2</sup>|
|资源邮箱|50 GB<sup>3</sup>|50 GB<sup>3</sup>|50 GB<sup>3</sup>|50 GB<sup>3,9</sup>|50 GB<sup>3,9</sup>|50 GB<sup>3</sup>|
|网站邮箱<sup>5</sup>|50 GB|50 GB|50 GB|50 GB|50 GB|不可用|
|公用文件夹邮箱|100 GB<sup>6</sup>|100 GB<sup>6</sup>|100 GB<sup>6</sup>|100 GB<sup>6</sup>|100 GB<sup>6</sup>|100 GB<sup>6</sup>|
|组邮箱|50 GB|50 GB|50 GB|50 GB|50 GB|50 GB|

> [!NOTE]
> <sup>1</sup> 每个用户最初都会获得 100 GB 的存档邮箱存储空间。 启用自动扩展存档后，只要达到 100 GB 存储容量，就会自动添加额外存储空间。 有关详细信息，请参阅 [Overview of unlimited archiving in Office 365](https://go.microsoft.com/fwlink/?linkid=844060)（Office 365 中的无限制存档概述）。 <br/> <sup>2</sup> 若要访问共享邮箱，用户必须具有 Exchange Online 许可证，但共享邮箱不需要单独的许可证。 如果没有许可证，共享邮箱限制为 50 GB。 若要将大小限制提高至 100 GB，必须为共享邮箱分配 Exchange Online 计划 2 许可证或具有 Exchange Online Archiving 附加许可证的 Exchange Online 计划 1 许可证。 这还使您能够为无限量的存档存储容量启用自动扩展存档。 同样，如果要将共享邮箱置于诉讼保留状态，共享邮箱必须具有 Exchange Online 计划 2 许可证或 Exchange Online 计划 1 许可证以及Exchange Online Archiving许可证。 如果要应用高级功能，如 Microsoft Defender for Office 365、高级电子数据展示或自动保留策略，共享邮箱必须获得这些功能 (许可) 。 <br/> <sup>3</sup> 资源邮箱不需要许可证。 但是，如果没有许可证，资源邮箱限制为 50 GB。 若要增加邮箱大小，必须分配 E3 或 E5 许可证。 这会将邮箱大小增加至 100 GB。 <br/> <sup>4</sup>存档邮箱不包含在 Exchange Online Kiosk 中。 不过，可以通过 Exchange Online Archiving 以附加内容的形式购买。 有关详细信息，请参阅服务Exchange Online Archiving [说明](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md)。 <br/> <sup>2017</sup> 年从 Exchange Online 和 SharePoint Online 中删除了 5 个网站邮箱。 <br/> <sup>6</sup> 限制为 1，000 个公用文件夹邮箱，所有公用文件夹邮箱的最大总大小为 100 TB。 层次结构服务邮箱限制为 100 个公共文件夹邮箱。 <br/> <sup>7</sup> 存档邮箱仅可用于为已应用其许可证的单个用户或实体（例如共享邮箱）存档邮件。 禁止将存档邮箱用作为一种多个用户或实体存储邮件的方式。 例如，IT 管理员无法创建共享邮箱，也无法让用户复制（通过"抄送"或"密件抄送"字段，或通过传输规则）共享邮箱以便进行显式存档。 请注意，多个用户使用的共享邮箱实际上并不存储这些单个用户的电子邮件。 多个用户拥有访问权限，且他们以共享邮箱发送电子邮件。 因此，共享邮箱中仅存储以共享邮箱的 *名义* 往来发送的电子邮件。 <br/> <sup>8</sup> 如果在 Exchange Online 中创建了保留策略，则仅当用户的主邮箱大于 10 MB 时，邮件才会自动移动到用户的存档邮箱。 小于 10 MB 的邮箱不会自动运行保留策略。 <br/> <sup>9</sup> 共享和资源邮箱无需许可证。 但是，如果没有许可证，则这些邮箱具有 50 GB 限制。 若要增加邮箱大小，必须分配 E3 或 E5 许可证。 这会将邮箱大小增加至 100 GB。 <br/> <sup>10</sup> 默认情况下，共享邮箱具有一个关联的活动用户帐户，该帐户具有系统生成 (未知) 密码。 若要阻止登录关联的共享邮箱帐户，请参阅"阻止[登录共享邮箱帐户"。](https://docs.microsoft.com/office365/admin/email/create-a-shared-mailbox#block-sign-in-for-the-shared-mailbox-account)

### <a name="storage-limits-across-standalone-plans"></a>跨独立计划的存储限制

| 功能 | Exchange Server 2013 | Exchange Online 计划 1 | Exchange Online 计划 2 | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|用户邮箱|2 GB<sup>1</sup>|50 GB|100 GB|2 GB|
|存档邮箱<sup>8、9</sup>|100 GB<sup>1</sup>|50 GB|Unlimited<sup>2</sup>|不可用<sup>5</sup>|
|共享邮箱<sup>11</sup>|2 GB<sup>1</sup>|50 GB<sup>3</sup>|50 GB<sup>3,10</sup>|50 GB<sup>3</sup>|
|资源邮箱|2 GB<sup>1</sup>|50 GB<sup>4</sup>|50 GB<sup>4,10</sup>|50 GB<sup>4</sup>|
|公用文件夹邮箱|2 GB<sup>6</sup>|50 GB<sup>7</sup>|100 GB<sup>7</sup>|不可用|
|组邮箱|50 GB|50 GB|50 GB|50 GB|

> [!NOTE]
> <sup>1</sup> 这是 Exchange Server 2013 组织的默认邮箱大小。 管理员可以为其组织更改此值。 本地邮箱没有最大存储限制。 <br/> <sup>2</sup> 每个用户的存档邮箱中最初会有 100 GB 存储空间。 启用自动扩展存档后，只要达到 100 GB 存储容量，就会自动添加额外存储空间。 有关详细信息，请参阅 [Overview of unlimited archiving in Office 365](https://go.microsoft.com/fwlink/?linkid=844060)（Office 365 中的无限制存档概述）。 有关自动扩展存档的可用性的详细信息，请参阅 [Microsoft 365](https://go.microsoft.com/fwlink/?LinkId=509914) 路线图。 <br/> <sup>3</sup> 若要访问共享邮箱，用户必须具有 Exchange Online 许可证，但共享邮箱不需要单独的许可证。 如果没有许可证，共享邮箱限制为 50 GB。 若要将大小限制提高至 100 GB，必须为共享邮箱分配 Exchange Online 计划 2 许可证或具有 Exchange Online Archiving 附加许可证的 Exchange Online 计划 1 许可证。 这还使您能够为无限量的存档存储容量启用自动扩展存档。 同样，如果要将共享邮箱置于诉讼保留状态，共享邮箱必须具有 Exchange Online 计划 2 许可证或 Exchange Online 计划 1 许可证以及Exchange Online Archiving许可证。 如果要应用高级功能，如 Microsoft Defender for Office 365、高级电子数据展示或自动保留策略，共享邮箱必须获得这些功能 (许可) 。 <br/> <sup>4</sup> 资源邮箱无需许可证。 但是，如果没有许可证，资源邮箱限制为 50 GB。 若要增加邮箱大小，必须分配 Exchange Online 套餐 2 许可证。 这会将邮箱大小增加至 100 GB。 <br/> <sup>5</sup> 存档邮箱不包含在 Exchange Online Kiosk 中。 不过，可以通过 Exchange Online Archiving 以附加内容的形式购买。 有关详细信息，请参阅服务Exchange Online Archiving [说明](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md)。 <br/> <sup>6</sup> 这是 Microsoft Exchange Server 2013 组织的默认邮箱大小。 管理员可以为其组织更改此值。 Exchange Server 2013 具有 100 个公共文件夹邮箱的限制，且所有公共文件夹邮箱的最大总大小为 50 TB。 <br/> <sup>7</sup> Exchange Server 具有 1,000 个公共文件夹邮箱的限制，且所有公共文件夹邮箱的最大总大小为 50 TB。  <br/> <sup>8</sup> 存档邮箱仅可用于为已应用其许可证的单个用户或实体存档邮件。 禁止将存档邮箱作为一种为多个用户存档邮件的方式。 例如，IT 管理员无法创建共享邮箱且无法使用户复制（通过"抄送"或"密件抄送"字段，或通过传输规则）共享邮箱以便进行显式存档。 <br/> <sup>9</sup> 如果已在 Exchange Online 中创建保留策略，则仅当用户的主邮箱大于 10 MB 时邮件才会自动移至用户的存档邮箱。 小于 10 MB 的邮箱不会自动运行保留策略。 <br/> <sup>10</sup> 个共享和资源邮箱不需要许可证。 但是，如果没有许可证，则这些邮箱具有 50 GB 限制。 若要增加邮箱大小，必须分配 Exchange Online 套餐 2 许可证。 这会将邮箱大小增加至 100 GB。 <br/> <sup>11</sup> 默认情况下，共享邮箱具有一个关联的活动用户帐户，该帐户具有系统生成 (未知) 密码。 若要阻止登录关联的共享邮箱帐户，请参阅"阻止[登录共享邮箱帐户"。](https://docs.microsoft.com/office365/admin/email/create-a-shared-mailbox#block-sign-in-for-the-shared-mailbox-account)

## <a name="capacity-alerts"></a>容量报警

Exchange Online 将在用户的邮箱接近或达到最大容量时提供三种通知类型：

- **警告**：用户收到一封电子邮件警告，指出邮箱接近最大大小限制。 此警告旨在建议用户删除不需要的邮件。

- **禁止发送**：达到邮箱大小限制时，用户会收到禁止发送的通知电子邮件。 在删除足够的电子邮件以将邮箱置于大小限制以下之前，用户无法发送新邮件。

- **禁止发送/** 接收：Exchange Online 在达到邮箱大小限制时拒绝任何传入邮件，并将未送达报告 (NDR) 发件人。 发件人可选择稍后尝试重新发送该邮件。 若要再次接收邮件，用户必须删除邮件，直到邮箱的使用容量低于大小限制为止。

### <a name="capacity-alerts"></a>容量报警

| 功能 | Microsoft 365 商业基础版 | Microsoft 365 商业标准版 | Office 365 企业版 E1 | Office 365 企业版 E3 | Office 365 企业版 E5 | Office 365 企业版 F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|警告|49 GB|49 GB|49 GB|98 GB|98 GB|1.96 GB|
|禁止发送|49.5 GB|49.5 GB|49.5 GB|99 GB|99 GB|1.98 GB|
|禁止发送/接收|50 GB|50 GB|50 GB|100 GB|100 GB|2 GB|

### <a name="capacity-alerts-across-standalone-plans"></a>跨独立计划的容量警报

| 功能 | Exchange Server 2013 | Exchange Online 计划 1 | Exchange Online 计划 2 | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|警告|1.9 GB<sup>1</sup>|49 GB|98 GB|1.96 GB|
|禁止发送|2 GB<sup>1</sup>|49.5 GB|99 GB|1.98 GB|
|禁止发送/接收|2.3 GB<sup>1</sup>|50 GB|100 GB|2 GB|

> [!NOTE]
> <sup>1</sup> 这是 Exchange Server 2013 组织的默认值。管理员可以为其组织更改此值。

## <a name="mailbox-folder-limits"></a>邮箱文件夹限制

这些限制旨在将邮箱限制为在 Exchange Online 中受支持的已知尺寸。这些限制旨在防止文件夹中存在不限数量的邮箱项目，邮箱中存在不限数量的文件夹或 Exchange Online 组织中存在不限数量的公用文件夹。出于实用目的，邮箱文件夹限制实际上不受限制，足以支持大多数迁移到 Exchange Online 的 Exchange Online 邮箱和内部部署邮箱。

- **每个邮箱文件夹的最大邮件数**：指定邮箱文件夹的最大邮件数。 达到该限制时，将无法传递新邮件或无法将其保存在某个文件夹中。

- **每个邮箱文件夹** 的邮件数量的警告：指定 Exchange Online 向邮箱所有者发送警告邮件之前邮箱文件夹可以保留的邮件数。 达到此配额时，将每天发送一次警告消息。

- **"可** 恢复邮件"文件夹中每个文件夹的最大邮件数：指定"可恢复邮件"文件夹的每个文件夹中可包含的最大邮件数。 文件夹超出此限制时，将无法存储新邮件。 例如，如果"可恢复邮件"文件夹中的"删除"文件夹超出邮件计数限制，而邮箱所有者试图从邮箱中永久删除邮件，删除将会失败。

- **"可** 恢复的项目"文件夹中每个文件夹的邮件数量的警告：指定 Exchange Online 将事件记录到应用程序事件日志之前，"可恢复的项目"文件夹中每个文件夹可以保留的邮件数。

- **每个邮箱文件夹的最大** 子文件夹数：指定可以在邮箱文件夹中创建的子文件夹的最大数量。 达到此限制时，邮箱所有者将不能创建新的子文件夹。

- **每个邮箱** 文件夹的子文件夹数量的警告：指定 Exchange Online 向邮箱所有者发送警告消息之前，可以在邮箱文件夹中创建的子文件夹数量。 达到此配额时，将每天发送一次警告消息。

- **最大文件夹层次结构深度**：指定邮箱的文件夹层次结构中的最大级别数。 达到此限制时，邮箱所有者将无法在邮箱文件夹的文件夹层次结构中创建其他级别。

- **文件夹层次结构深度** 警告：指定在 Exchange Online 向邮箱所有者发送警告消息之前，可以在邮箱文件夹的文件夹层次结构中创建的级别数。 达到此配额时，将每天发送一次警告消息。

- **公用文件夹的最大数量**：指定整个公用文件夹层次结构中公用文件夹的最大数量。 达到此限制后，必须删除现有公用文件夹，才可以创建新的公用文件夹。

- **每个公用文件夹的最大子文件夹数**：指定可以在公用文件夹中创建的子文件夹的最大数量。 当达到此限制时，无法在公用文件夹中创建新的子文件夹。

- **每个公用文件夹的子** 文件夹数量的警告：指定在 Exchange Online 向文件夹所有者发送警告消息之前可以在公用文件夹中创建的子文件夹的数量。 如果不存在所有者，则警告消息会发送到具有所有者权限的用户。 达到此配额时，将每天发送一次警告消息。

### <a name="mailbox-folder-limits"></a>邮箱文件夹限制

| 功能 | Microsoft 365 商业基础版 | Microsoft 365 商业标准版 | Office 365 企业版 E1 | Office 365 企业版 E3 | Office 365 企业版 E5 | Office 365 企业版 F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|每个邮箱文件夹的邮件的最大数量|1 百万|1 百万|1 百万|1 百万|1 百万|1 百万|
|每个邮箱文件夹的邮件数量的警告|900,000|900,000|900,000|900,000|900,000|900,000|
|“可恢复邮件”文件夹中的每个文件夹的邮件最大数量|3 百万|3 百万|3 百万|3 百万|3 百万|3 百万|
|主邮箱（未处于保留状态）中“可恢复的项目”文件夹的存储配额|30 GB|30 GB|30 GB|30 GB|30 GB|30 GB|
|主邮箱（处于保留状态）中“可恢复的项目”文件夹的存储配额|100 GB|100 GB|100 GB|100 GB|100 GB|100 GB|
|存档邮箱（未处于保留状态）中“可恢复的项目”文件夹的存储配额|30 GB|30 GB|30 GB|Unlimited<sup>2</sup>|Unlimited<sup>2</sup>|30 GB|
|存档邮箱（处于保留状态）中“可恢复的项目”文件夹的存储配额|100 GB<sup>1</sup>|100 GB<sup>1</sup>|100 GB<sup>1</sup>|Unlimited<sup>2</sup>|Unlimited<sup>2</sup>|100 GB<sup>1</sup>|
|“可恢复邮件”文件夹中的每个文件夹的邮件数量警告|2.75 百万|2.75 百万|2.75 百万|2.75 百万|2.75 百万|2.75 百万|
|每个邮箱文件夹的子文件夹的最大数量|10，000<sup>2</sup>|10，000<sup>2</sup>|10，000<sup>2</sup>|10，000<sup>2</sup>|10，000<sup>2</sup>|10，000<sup>2</sup>|
|每个邮箱文件夹的子文件夹数量的警告|9000|9000|9000|9000|9000|9000|
|最大文件夹层次结构深度|300|300|300|300|300|300|
|文件夹层次结构深度的警告|250|250|250|250|250|250|
|公用文件夹最大数|500,000|500,000|500,000|500,000|500,000|不可用|
|每个公用文件夹的子文件夹的最大数量|10,000|10,000|10,000|10,000|10,000|不可用|
|每个公用文件夹的子文件夹数量的警告|9000|9000|9000|9000|9000|不可用|

> [!NOTE]
> <sup>1</sup> 这是"可恢复的项目"文件夹的存储配额，不是整个存档邮箱的配额。 对于拥有 Exchange Online 套餐 2 许可证的用户或者拥有 Exchange Online 套餐 1 和 Exchange Online Archiving 许可证的用户，存档邮箱的存储配额没有限制。 有关提高可恢复项目配额的信息，请参阅[提高保留邮箱的可恢复项目配额](https://docs.microsoft.com/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold)。 <br/> <sup>2</sup> 存档邮箱中的可恢复项目文件夹的初始存储配额为 100 GB。 启用自动扩展存档后，只要达到“可恢复的项目”文件夹的存储容量，就会自动添加额外存储空间。 有关详细信息，请参阅 [在 Office 365 中不受限制地存档概述](https://go.microsoft.com/fwlink/?linkid=844060)。 有关自动扩展存档的可用性的详细信息，请参阅 [Microsoft 365](https://go.microsoft.com/fwlink/?LinkId=509914) 路线图。
> <sup>2</sup> 这是存储限制;它是邮箱形状约束之一。 任何给定父级只能有 10，000 个直接子文件夹。 无论迁移或其他创建文件夹的客户端如何，这都适用。

### <a name="mailbox-folder-limits-across-standalone-plans"></a>跨独立计划的邮箱文件夹限制

| 功能 | Exchange Server 2013 | Exchange Online 计划 1 | Exchange Online 计划 2 | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|每个邮箱文件夹的邮件的最大数量|无限制<sup>1</sup>|1 百万|1 百万|1 百万|
|每个邮箱文件夹的邮件数量的警告|无限制|900,000|900,000|900,000|
|“可恢复邮件”文件夹中的每个文件夹的邮件最大数量|无限制|3 百万|3 百万|3 百万|
|主邮箱（未处于保留状态）中“可恢复的项目”文件夹的存储配额|30 GB|30 GB|30 GB|30 GB|
|主邮箱（处于保留状态）中“可恢复的项目”文件夹的存储配额|100 GB|100 GB|100 GB|100 GB|
|存档邮箱（未处于保留状态）中“可恢复的项目”文件夹的存储配额|30 GB|30 GB|30 GB|30 GB|
|存档邮箱（处于保留状态）中“可恢复的项目”文件夹的存储配额|100 GB<sup>2</sup>|100 GB<sup>2</sup>|Unlimited<sup>3</sup>|Unlimited<sup>3</sup>|
|“可恢复邮件”文件夹中的每个文件夹的邮件数量警告|无限制|2.75 百万|2.75 百万|2.75 百万|
|每个邮箱文件夹的子文件夹的最大数量|无限制|1000|1000|1000|
|每个邮箱文件夹的子文件夹数量的警告|无限制|900|900|900|
|最大文件夹层次结构深度|无限制|300|300|300|
|文件夹层次结构深度的警告|无限制|250|250|250|
|公用文件夹最大数|1,000,000|100,000|100,000|不可用|
|每个公用文件夹的子文件夹的最大数量|不适用|1,000|1,000|不可用|
|每个公用文件夹的子文件夹数量的警告|不适用|900|900|不可用|

> [!NOTE]
> <sup>1</sup> Microsoft 建议每个邮箱文件夹不超过 1,000,000 封邮件。 > <br/> <sup>2</sup> 这是可恢复项目文件夹的存储配额，而非整个存档邮箱的配额。 对于拥有 Exchange Online 套餐 2 许可证的用户或者拥有 Exchange Online 套餐 1 和 Exchange Online Archiving 许可证的用户，存档邮箱的存储配额没有限制。 有关提高可恢复项目配额的信息，请参阅[提高保留邮箱的可恢复项目配额](https://docs.microsoft.com/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold)。 <br/> <sup>3</sup> 存档邮箱中的可恢复项目文件夹的初始存储配额为 100 GB。 启用自动扩展存档后，只要达到“可恢复的项目”文件夹的存储容量，就会自动添加额外存储空间。 有关详细信息，请参阅 [在 Office 365 中不受限制地存档概述](https://go.microsoft.com/fwlink/?linkid=844060)。 有关自动扩展存档的可用性的详细信息，请参阅 [Microsoft 365](https://go.microsoft.com/fwlink/?LinkId=509914) 路线图。

## <a name="message-limits"></a>邮件限制

下列限制适用于每封电子邮件。

- **邮件大小** 限制：邮件大小限制是阻止大型邮件阻止传递其他邮件并影响所有用户的服务性能所必需的。 这些限制包括一些附件，并且适用于组织范围的所有邮件（入站、出站和内部）。 将不送达超过该限制的邮件，同时发件人将收到未送达报告 (NDR)。 尽管可以向上、向下或按每个用户配置邮件大小限制，但管理员仍可以创建传输规则以限制任何单个附件的最大大小。 若要了解更多信息，请参阅 [Microsoft 支持更大的电子邮件](https://go.microsoft.com/fwlink/?linkid=2144144)。

    > [!NOTE]
    > 某些电子邮件客户端可能具有较低的邮件大小限制，或者可能会将单个文件附件的大小限制为小于 Exchange Online 邮件大小限制的值。

- **邮件头大小限制**：指定邮件中所有邮件头字段的最大大小。 当前限制为 256 KB。 如果所有邮件头的总大小超过 256 KB，则 Exchange Online 将会拒绝邮件，并显示错误消息“552 5.3.4 邮件头大小超过固定的最大大小”。 不考虑邮件正文或附件的大小。 因为邮件头字段是纯文本，所以邮件头的大小由每个邮件头的字符数和邮件头字段的总数确定。 每个文本字符占用 1 字节。

- **主题长度限制**：电子邮件的主题行中允许的最大文本字符数。

- **文件附件限制**：电子邮件中允许的最大文件附件数。 即使所有文件附件的总大小并不违反邮件大小限制，邮件中允许的附件数量也仍具有限制。 限制由多部分邮件限制进行控制。

- **文件附件大小限制**：单个附件的最大文件大小。

    > [!NOTE]
    > 此为单个附件的最大文件大小。 单个客户端程序（包括 Web 上的 Outlook）可能会限制附件的大小低于此最大值。 Exchange ActiveSync 不基于个别附件实施附件大小限制。 Exchange ActiveSync 邮件的所有附件总大小必须低于邮件大小限制。

- **多部分邮件限制**：MIME 多部分邮件中允许的邮件正文部分的最大数量。 此限制还会控制邮件中允许的文件附件的最大数量。

- **嵌入邮件深度限制**：电子邮件中允许的最大转发电子邮件数。

### <a name="message-limits"></a>邮件限制

| 功能 | Microsoft 365 商业基础版 | Microsoft 365 商业标准版 | Office 365 企业版 E1 | Office 365 企业版 E3 | Office 365 企业版 E5 | Office 365 企业版 F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|邮件大小限制 - Outlook|150 MB<sup>1, 2</sup>|150 MB<sup>1、2</sup>|150 MB<sup>1、2</sup>|150 MB<sup>1、2</sup>|150 MB<sup>1、2</sup>|150 MB<sup>1, 2</sup>|
|邮件大小限制 - OWA|112 MB<sup>1, 3</sup>|112 MB<sup>1、3</sup>|112 MB<sup>1、3</sup>|112 MB<sup>1、3</sup>|112 MB<sup>1、3</sup>|112 MB<sup>1、3</sup>|
|邮件大小限制 - Outlook for Mac|150 MB<sup>1、2</sup>|150 MB<sup>1、2</sup>|150 MB<sup>1、2</sup>|150 MB<sup>1、2</sup>|150 MB<sup>1、2</sup>|150 MB<sup>1、2</sup>|
|邮件大小限制 - 迁移|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|
|邮件大小限制 - Outlook for iOS 和 Outlook for Android | 33 MB| 33 MB| 33 MB| 33 MB| 33 MB| 33 MB|
|加密邮件的大小限制（针对使用包含新功能的 Office 365 邮件加密的订阅服务器）<sup>5</sup>|25 MB|25 MB|25 MB|25 MB|25 MB|25 MB|
|加密邮件的大小限制（针对使用旧版 Office 365 邮件加密的订阅服务器）<sup>5</sup>|25 MB|25 MB|25 MB|25 MB|25 MB|25 MB|
|主题长度限制|255 个字符|255 个字符|255 个字符|255 个字符|255 个字符|255 个字符|
|文件附件限制|250 个附件|250 个附件|250 个附件|250 个附件|250 个附件|250 个附件|
|文件附件大小限制 - Outlook|150 MB|150 MB|150 MB|150 MB|150 MB|150 MB|
|文件附件大小限制 - OWA |112 MB<sup>3、6</sup>|112 MB<sup>3、6</sup>|112 MB<sup>3、6</sup>|112 MB<sup>3、6</sup>|112 MB<sup>3、6</sup>|112 MB<sup>3、6</sup>|
|文件附件大小限制 - Outlook for Mac|150 MB|150 MB|150 MB|150 MB|150 MB|150 MB|
|文件附件大小限制 - Outlook for iOS 和 Outlook for Android|33 MB |33 MB |33 MB |33 MB |33 MB |33 MB |
|多部分邮件限制|250 个部分|250 个部分|250 个部分|250 个部分|250 个部分|250 个部分|
|邮件嵌入深度限制|30 封嵌入邮件|30 封嵌入邮件|30 封嵌入邮件|30 封嵌入邮件|30 封嵌入邮件|30 封嵌入邮件|

> [!NOTE]
> <sup>1</sup> Microsoft 邮箱的默认最大邮件大小为 25 MB。 Microsoft 管理员可以指定 1 MB 到 150 MB 之间的自定义限制。 不过，你可以发送或接收的邮件大小还取决于你的电子邮件客户端或解决方案的支持范围。 有关为组织自定义允许的最大邮件大小详细信息，请参阅 [Microsoft 支持较大的电子邮件](https://go.microsoft.com/fwlink/?linkid=2144144)。 
<br/> <sup>2</sup> 您可以在用户之间发送和接收最多 150 MB 的邮件 (其中邮件永远不会离开 Microsoft 数据中心) 。 在 Microsoft 数据中心之外路由的邮件需要额外增加 33% 的转换编码，在这种情况下，最大邮件大小为 112 MB。 <br/> 
<sup>3</sup> OWA 会考虑您的邮件可能需要增加 33% 的编码，并将可以发送的邮件大小限制为比配置设置低 25% 的邮件大小。 例如，如果将设置自定义为 100 MB 最大邮件大小，则你可以发送不超过 75 MB 的邮件。 
<br/> <sup>4</sup> 要移至 Exchange Online 的邮件大小由 Exchange Online 计算。 Exchange Server 2013 之前的 Exchange 版本可能会报告较小的邮件大小。 此限制适用于使用任何受支持的 Exchange 邮箱复制服务的基于移动的迁移。 其他迁移 (、阶段、IMAP、PST) 和其他第三方工具受常规邮件大小限制的限制。 <br/> 
<sup>5</sup> 有关具有新功能的 OME 的信息，请参阅设置基于 Azure 信息保护构建的新 [Office 365](https://support.office.com/article/7ff0c040-b25c-4378-9904-b1b50210d00e)邮件加密功能。 <br/> 
<sup>6</sup> 个经典文件附件限制为 112 MB，但 OneDrive 文件附件最多为 2 GB。


### <a name="message-limits-across-standalone-options"></a>跨独立选项的邮件限制

| 功能 | Exchange Server 2013 | Exchange Online 计划 1 | Exchange Online 计划 2 | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|邮件大小限制 - Outlook|10 MB<sup>4</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>2</sup>|
|邮件大小限制 - OWA|10 MB<sup>4</sup>|112 MB<sup>1、3</sup>|112 MB<sup>1、3</sup>|150 MB<sup>1、2</sup>|
|邮件大小限制 - Outlook for Mac|10 MB<sup>4</sup>|150 MB|150 MB||
|邮件大小限制 - 迁移|不适用|150 MB <sup>5</sup>|150 MB <sup>5</sup>|150 MB <sup>5</sup>|
|邮件大小限制 - Outlook for iOS 和 Outlook for Android |25 MB |33 MB |33 MB |33 MB |
|加密邮件的大小限制（针对使用包含新功能的 Office 365 邮件加密的订阅服务器）<sup>6</sup>|150 MB|150 MB|150 MB|150 MB|
|加密邮件的大小限制（针对使用旧版 Office 365 邮件加密的订阅服务器）<sup>6</sup>|25 MB|25 MB|25 MB|25 MB|
|主题长度限制|255 个字符|255 个字符|255 个字符|255 个字符|
|文件附件限制|1024 attachments<sup>4</sup>|250 个附件|250 个附件|250 个附件|
|文件附件大小限制 - Outlook|35 MB<sup>4</sup>|150 MB|150 MB|150 MB|
|文件附件大小限制 - OWA|35 MB<sup>4</sup>|112 MB<sup>3</sup>|112 MB<sup>3</sup>|112 MB<sup>3</sup>|
|文件附件大小限制 - Outlook for Mac|35 MB<sup>4</sup>|150 MB|150 MB|35 MB|
|文件附件大小限制 - Outlook for iOS 和 Outlook for Android|25 MB |33 MB|33 MB|33 MB|
|多部分邮件限制|250 个部分|250 个部分|250 个部分|250 个部分|
|邮件嵌入深度限制|30 封嵌入邮件|30 封嵌入邮件|30 封嵌入邮件|30 封嵌入邮件|

> [!NOTE]
> <sup>1</sup> Microsoft 管理员可以指定 1 MB 到 150 MB 之间的自定义限制。 不过，你可以发送或接收的邮件大小还取决于你的电子邮件客户端或解决方案的支持范围。 有关为组织自定义允许的最大邮件大小详细信息，请参阅 [Microsoft 支持较大的电子邮件](https://go.microsoft.com/fwlink/?linkid=2144144)。 <br/> <sup>2</sup> 您可以在用户之间发送和接收最多 150 MB 的邮件 (其中邮件永远不会离开 Microsoft 数据中心) 。 在 Microsoft 数据中心之外路由的邮件需要额外增加 33% 的转换编码，在这种情况下，最大邮件大小为 112 MB。 <br/> 
<sup>3</sup> OWA 会考虑您的邮件可能需要增加 33% 的编码，并将可以发送的邮件大小限制为比配置设置低 25% 的邮件大小。 例如，如果将设置自定义为 100 MB 最大邮件大小，则你可以发送不超过 75 MB 的邮件。 <br/> 
<sup>4</sup> 这是 2013 Exchange Server的默认限制。 管理员可以为其组织更改此值。 <br/> 
<sup>5</sup> 要移动到 Exchange Online 的邮件大小由 Exchange Online 计算。 Exchange Server 2013 之前的 Exchange 版本可能会报告较小的项目大小。 <br/> 
<sup>6</sup> 有关具有新功能的 OME 的信息，请参阅设置基于 Azure 信息保护构建的新 [Office 365](https://support.office.com/article/7ff0c040-b25c-4378-9904-b1b50210d00e)邮件加密功能。

## <a name="receiving-and-sending-limits"></a>接收和发送限制

接收和发送限制可用于防止出现垃圾邮件和大量邮件蠕虫或病毒。这些限制可以帮助保护系统的运行状况和我们用户的安全。

### <a name="receiving-limits"></a>接收限制

接收限制应用于用户、组或公用文件夹每小时可以接收的邮件数。 这适用于从 Internet 和本地服务器接收的邮件。 超出接收限制时，只要有电子邮件发送到此邮箱，都会收到未送达报告，指出邮箱已超出最大发送阈值。 一个小时后，限制会进行刷新，邮箱将能够再次接收邮件。

| 功能 | Microsoft 365 商业基础版 | Microsoft 365 商业标准版 Office | Office 365 企业版 E1 | Office 365 企业版 E3 | Office 365 企业版 E5 | Office 365 企业版 F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|接收的邮件数|每小时 3,600 封邮件|每小时 3,600 封邮件|每小时 3,600 封邮件|每小时 3,600 封邮件|每小时 3600 封邮件|每小时 3600 封邮件|

### <a name="sending-limits"></a>发送限制

发送限制应用于收件人数、邮件数和用户可以从其 Exchange Online 帐户发送的每封邮件的收件人数。

> [!NOTE]
> 对于存储在组织的通讯簿中的通讯组，这类组计数为一个收件人。对于存储在邮箱的“联系人”文件夹中的通讯组，单独计数组的各个成员。

- **收件人速率限制**：为了阻止传递未经请求的批量邮件，Exchange Online 具有收件人限制，可阻止用户和应用程序发送大量电子邮件。 这些限制适用于每个用户的所有出站和内部邮件。

    > [!NOTE]
    > 需要发送合法批量电子邮件的 Exchange Online 客户（例如，客户新闻通讯）应使用专门提供这些服务的第三方提供商。

- **收件人限制**：这是单个电子邮件的"收件人："、"抄送："和"密件抄送："字段中允许的最大收件人数。

    > [!NOTE]
    > 出于收件人速率限制和收件人限制的目的，组织共享通讯簿中存储的通讯组作为一个收件人计数。在个人通讯列表中，每个收件人单独计数。

- **收件人代理地址限制**：收件人代理地址限制是收件人 (邮箱) 的最大别名数。 

- **邮件速率限制**：邮件速率限制确定用户可在指定的时段内从 Exchange Online 帐户发送的邮件数。 此限制有助于防止单个发件人过度使用系统资源。 如果用户提交邮件的速度超过了通过 SMTP 客户端提交邮件的限制，邮件将被拒绝，并且客户端将需要重试。

#### <a name="sending-limits"></a>发送限制

| 功能 | Microsoft 365 商业基础版 | Microsoft 365 商业标准版 | Office 365 企业版 E1 | Office 365 企业版 E3 | Office 365 企业版 E5 | Office 365 企业版 F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|收件人速率限制<sup>1</sup>|每天 10,000 个收件人|每天 10,000 个收件人|每天 10,000 个收件人|每天 10,000 个收件人|每天 10,000 个收件人|每天 10,000 个收件人|
|收件人限制<sup>2</sup>|可自定义的收件人数最多为 1000 个|可自定义的收件人数最多为 1000 个|可自定义的收件人数最多为 1000 个|可自定义的收件人数最多为 1000 个|可自定义的收件人数最多为 1000 个|可自定义的收件人数最多为 1000 个|
|收件人代理服务器地址限制|400|400|400|400|400|400|
|邮件速率限制<sup>3</sup>|每分钟 30 封邮件|每分钟 30 封邮件|每分钟 30 封邮件|每分钟 30 封邮件|每分钟 30 封邮件|每分钟 30 封邮件|

> [!NOTE]
> <sup>1</sup> 达到收件人速率限制后，无法从邮箱发送邮件，直到过去 24 小时内已发送邮件的收件人数低于该限制。 例如，用户在上午 09：00 向 5000 个收件人发送电子邮件，然后在上午 10：00 向 2500 个收件人发送另一封邮件，然后在 11：00 AM 向 2500 个收件人发送另一封邮件，达到 10，000 封邮件的限制。 用户将无法再次发送邮件，直到第二天上午 09：00。  
> <sup>2</sup> 您可以为现有邮箱和将来将创建的新邮箱自定义 1 到 1000 之间的收件人限制。 使用 Exchange 管理中心单独或批量编辑现有邮箱的收件人限制，然后通过远程 PowerShell 自定义新邮箱的默认设置。 有关详细信息，请参阅 [Office 365 中的可自定义收件人限制](https://techcommunity.microsoft.com/t5/exchange-team-blog/customizable-recipient-limits-in-office-365/ba-p/1183228)。  
> <sup>3</sup> 当出站邮件卷超过邮件速率限制时，邮件提交中任何多余内容将受到限制，并连续进行到以下分钟。 这通常不会阻止发件人的帐户，但 Exchange Online 不适合容纳群发邮件方案。 对于此用例，建议改为使用此处的选项 2 [和](https://docs.microsoft.com/exchange/mail-flow-best-practices/how-to-set-up-a-multifunction-device-or-application-to-send-email-using-microsoft-365-or-office-365) 3。

#### <a name="sending-limits-across-standalone-options"></a>跨独立选项的发送限制

| 功能 | Exchange Server 2013 | Exchange Online 计划 1 | Exchange Online 计划 2 | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|收件人速率限制|无限制<sup>1</sup>|每天 10，000 个<sup>收件人（第 2 天）</sup>|每天 10，000 个<sup>收件人（第 2 天）</sup>|每天 10，000 个<sup>收件人（第 2 天）</sup>|
|收件人限制|1000 个收件人<sup>1</sup>|1000 个收件人|1000 个收件人|1000 个收件人|
|收件人代理服务器地址限制|400|400|400|400|
|邮件速率限制|每分钟 30 封邮件|每分钟 30 封邮件|每分钟 30 封邮件|每分钟 30 封邮件|

> [!NOTE]
> <sup>1</sup> 这是 Exchange Server 2013 组织的默认限制。 管理员可以为其组织更改此值。<br/>
<sup>2</sup> 达到收件人速率限制后，无法从邮箱发送邮件，直到过去 24 小时内发送邮件的收件人数低于该限制。 例如，用户在上午 09：00 向 5000 个收件人发送电子邮件，然后在上午 10：00 向 2500 个收件人发送另一封邮件，然后在 11：00 AM 向 2500 个收件人发送另一封邮件，达到 10，000 封邮件的限制。 用户将无法再次发送邮件，直到第二天上午 09：00。

## <a name="reporting-and-message-trace-limits"></a>报告和邮件跟踪限制

有关报告和邮件跟踪限制，请参阅 Exchange Online Protection 中的报告和邮件跟踪中的"报告和邮件跟踪数据的可用性和延迟 ["部分](https://go.microsoft.com/fwlink/p/?LinkId=394248)。

## <a name="retention-limits"></a>保留限制

这些限制控制可以访问收件箱中特定文件夹中的项目的时间长度。

- **"已删除邮件"文件夹保留期**：邮件在自动删除之前可在"已删除邮件"文件夹中保留的最大天数。

- **从"已删除** 邮件"文件夹中删除的项目的保留期：从"已删除邮件"文件夹中删除的项目在永久删除之前保留的最大天数。

- **垃圾邮件文件夹保留期**：邮件在被自动删除之前可在"垃圾邮件"文件夹中保留的最大天数。

> [!NOTE]
> 使用 Microsoft 365 管理中心或 Exchange Online PowerShell 中的 Remove-Mailbox cmdlet 删除但仍位于 Azure Active Directory 回收站中的软删除用户邮箱可以在 &mdash; 30 天内恢复。 &mdash;

### <a name="retention-limits"></a>保留限制

| 功能 | Microsoft 365 商业基础版 | Microsoft 365 商业标准版 | Office 365 企业版 E1 | Office 365 企业版 E3 | Office 365 企业版 E5 | Office 365 企业版 F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|“已删除邮件”文件夹保留期|无限制<sup>1</sup>|无限制<sup>1</sup>|无限制<sup>1</sup>|无限制<sup>1</sup>|无限制<sup>1</sup>|无限制<sup>1</sup>|
|从“已删除邮件”文件夹中删除的邮件的保留期|14 天<sup>1</sup>|14 天<sup>1</sup>|14 天<sup>1</sup>|14 天<sup>1</sup>|14 天<sup>1</sup>|14 天<sup>1</sup>|
|“垃圾邮件”文件夹保留期|30 天|30 天|30 天|30 天|30 天|30 天|

> [!NOTE]
> <sup>1</sup> 这是 Microsoft 365 组织的默认值。 管理员可以将其组织中的邮箱的此值更改为最大 30 天。

### <a name="retention-limits-across-standalone-options"></a>跨独立选项的保留限制

| 功能 | Exchange Server 2013 | Exchange Online 计划 1 | Exchange Online 计划 2 | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|“已删除邮件”文件夹保留期|无限制<sup>1</sup>|无限制<sup>1</sup>|无限制<sup>1</sup>|无限制<sup>1</sup>|
|从“已删除邮件”文件夹中删除的邮件的保留期|14 天<sup>1</sup>|14 天<sup>2</sup>|14 天<sup>2</sup>|14 天<sup>2</sup>|
|“垃圾邮件”文件夹保留期|2 年<sup>1</sup>|30 天|30 天|30 天|

> [!NOTE]
> <sup>1</sup> 这是默认限制。管理员可以为其组织更改此值。<br/> <sup>2</sup> 这是 Exchange Online 组织的默认值。 管理员可以将其组织中的邮箱的此值更改为最大 30 天。

## <a name="distribution-group-limits"></a>通讯组限制

这些限制适用于组织的共享地址簿中的通讯组。

- **通讯组的最大成员数**：在展开通讯组后确定收件人总数。

- **限制向大型通讯组发送邮件**：包含此限制所指定成员数的通讯组必须配置传递管理或邮件审批选项。 传递管理选项将指定一个允许向通讯组发送邮件的发件人的列表。 邮件审批选项将指定一个或多个必须审批发送到通讯组的所有邮件的审阅人。

- **大型通讯组的最大邮件大小**：如果将邮件发送给 5，000 个或多个收件人，则邮件大小不能超过此限制。 如果此邮件的大小超出此限制，则不会传递此邮件，并且发件人会收到一份未送达报告 (NDR)。

### <a name="distribution-group-limits"></a>通讯组限制

| 功能 | Microsoft 365 商业基础版 | Microsoft 365 商业标准版 | Office 365 企业版 E1 | Office 365 企业版 E3 | Office 365 企业版 E5 | Office 365 企业版 F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|通讯组成员的最大数目<sup>1</sup>|100,000 个成员|100,000 个成员|100,000 个成员|100,000 个成员|100,000 个成员|100,000 个成员|
|限制向大型通讯组发送邮件|5,000 个成员或更多成员|5,000 个成员或更多成员|5,000 个成员或更多成员|5,000 个成员或更多成员|5,000 个成员或更多成员|5,000 个成员或更多成员|
|拥有 5,000 到 99,999 个成员的分配组的最大邮件大小|25 MB|25 MB|25 MB|25 MB|25 MB|25 MB|
|拥有 100,000 个成员的分配组的最大邮件大小|5 MB|5 MB|5 MB|5 MB|5 MB|5 MB|
|通讯组所有者的最大数量|10 |10 |10 |10 |10 |10 |
|用户可创建的组的最大数目|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|

> [!NOTE]
> <sup>1</sup> 如果您正在使用 Azure Active Directory DirSync，您可以从您的本地 Active Directory 同步到 Azure Active Directory 的分发组成员的最大数量是 15,000。 如果您正在使用 Azure AD Connect，该数字为 50,000。 <br/> <sup>2</sup> 此限制也适用于管理员。

### <a name="distribution-group-limits-across-standalone-options"></a>跨独立选项的通讯组限制

| 功能 | Exchange Server 2013 | Exchange Online 计划 1 | Exchange Online 计划 2 | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|通讯组成员的最大数目|100,000 个成员<sup>1</sup>|100,000 个成员|100,000 个成员|100,000 个成员|
|限制向大型通讯组发送邮件|5,000 个成员或更多成员<sup>1</sup>|5,000 个成员或更多成员|5,000 个成员或更多成员|5,000 个成员或更多成员|
|通讯组所有者的最大数量|10 |10 |10 |10 |
|用户可创建的组的最大数目|250<sup>2</sup>|250<sup>2</sup>|250<sup>2</sup>|250<sup>2</sup>|

> [!NOTE]
> <sup>1</sup> 这是 Exchange Server 2013 组织的默认限制。 管理员可以为其组织更改此值。 <br/> <sup>2</sup> 此限制也适用于管理员。

## <a name="journal-transport-and-inbox-rule-limits"></a>日记、传输和收件箱规则限制

以下列表包括适用于日记规则的限制、 (规则（也称为组织范围规则) 规则）以及适用于收件箱规则的限制。 收件箱规则由单个用户设置，并适用于该用户邮箱发送和接收的邮件。

- **最大日记规则数**：组织中可存在的日记规则的最大数目。

- **最大传输规则数**：组织中可存在的最大规则数。

- **单个传输规则的最大大小**：可在单个传输规则中使用的最大字符数。 The characters are used in the conditions, exceptions, and actions.

- **所有传输规则** 中使用的所有正则表达式的字符限制：在组织的所有传输规则条件和例外中包括所有正则表达式的字符总数。 可具有少量使用长而复杂的正则表达式的规则，也可具有多个使用简单正则表达式的规则。

- **附件内容的** 扫描限制：传输规则条件使你可以检查邮件附件的内容，但仅检查从附件中提取的前 1 MB 文本。 1 MB 的限制指的是从附件中提取的文本，而不是附件的文件大小。 例如，一个 2 MB 的文件可能包含小于 1 MB 的文本，因此将检查整个文本。

- **所有传输** 规则向邮件添加的最大收件人数：当邮件由不同的传输规则处理时，只能向该邮件添加有限数量的收件人。 在达到此限制后，不会再向该邮件添加任何其余的收件人。 此外，传输规则不能向邮件添加通讯组。

- **转发者限制**：可以使用重定向操作为收件箱或传输规则配置的最大收件人数。 如果某个规则配置为将邮件重定向到比此数目多的收件人，则不应用该规则，任何满足该规则条件的邮件将不重定向到该规则中列出的任何收件人。
    
- **邮件重定向** 次数：根据收件箱规则自动重定向、转发或答复邮件次数。 例如，用户 A 有一个根据发件人将邮件重定向到用户 B 的收件箱规则。 用户 B 有一个根据主题行中的关键字将邮件转发到用户 C 的收件箱规则。 如果某邮件同时满足这两个条件，则由于仅允许一次重定向，该邮件仅发送到用户 B，不会转发到用户 C。 在这种情况下，邮件将被删除，而不会向用户 (NDR) 发送未送达报告，表明邮件未传递到用户 C。我们使用 X-MS-Exchange-Inbox-Rules-Loop 标头来确定邮件重定向次数。 此标头还跨 Exchange 组织边界保留。

- **传输规则** 重定向邮件次数：根据传输规则重定向邮件次数。 例如，Exchange 组织 Tailspin Toys 有一个传输规则，将发送到用户 A 的每封邮件重定向到位于 Exchange 组织 Contoso 中的用户 B。 在 Exchange 组织 Contoso 中，有一个传输规则将发送到用户 B 的每封邮件重定向到用户 C，用户 C 位于 Exchange 组织 A. Datum Corporation 中。 在这种情况下，邮件将被删除，并且未送达报告 (NDR) ，并拒绝邮件 *550 5.7.128 传输。规则。RejectMessage;超过传输规则循环计数，拒绝的邮件* 将发送给用户 A。我们使用 X-MS-Exchange-Transport-Rules-Loop 标头来确定传输规则重定向邮件的时间。 此标头还跨 Exchange 组织边界保留。

### <a name="journal-transport-and-inbox-rule-limits"></a>日记、传输和收件箱规则限制

| 功能 | Microsoft 365 商业基础版 | Microsoft 365 商业标准版 | Office 365 企业版 E1 | Office 365 企业版 E3 | Office 365 企业版 E5 | Office 365 企业版 F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|日记规则的最大数目|300 条规则|300 条规则|300 条规则|300 条规则|300 条规则|300 条规则|
|传输规则的最大数目|300 条规则|300 条规则|300 条规则|300 条规则|300 条规则|300 条规则|
|单个传输规则的最大大小|8 KB|8 KB|8 KB|8 KB|8 KB|8 KB|
|所有传输规则中使用的所有正则表达式的字符限制|20 KB|20 KB|20 KB|20 KB|20 KB|20 KB|
|附件内容的扫描限制|1 MB|1 MB|1 MB|1 MB|1 MB|1 MB|
|所有传输规则添加到邮件的收件人的最大数目|100 位收件人|100 位收件人|100 位收件人|100 位收件人|100 位收件人|100 位收件人|
|转发邮件的收件人限制|10 位收件人|10 个收件人|10 个收件人|10 个收件人|10 个收件人|10 个收件人|
|重定向邮件的次数|1 次重定向|1 次重定向|1 次重定向|1 次重定向|1 次重定向|1 次重定向|
|传输规则重定向邮件次数|1 次重定向|1 次重定向|1 次重定向|1 次重定向|1 次重定向|1 次重定向|
|重定向邮件的次数|1 次重定向|1 次重定向|1 次重定向|1 次重定向|1 次重定向|1 次重定向|
|收件箱规则|256kb<sup>1</sup>|256kb<sup>1</sup>|256kb<sup>1</sup>|256kb<sup>1</sup>|256kb<sup>1</sup>|256kb<sup>1</sup>|

> [!NOTE]
> <sup>1</sup> 如果邮箱已迁移到 Exchange Online，则收件箱规则限制可能设置为小于默认 EXO 值的值。 如果是这种情况，可以增加收件箱规则值。 有关说明，请参阅["修改 Exchange Online 中收件箱规则使用的空间"。](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-on-the-web/increase-the-space-used-by-inbox-rules) 

### <a name="journal-transport-and-inbox-rule-limits-across-standalone-options"></a>跨独立选项的日记、传输和收件箱规则限制

| 功能 | Exchange Server 2013 | Exchange Online 计划 1 | Exchange Online 计划 2 | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|日记规则的最大数目|无限制|50 个规则|50 个规则|50 个规则|
|传输规则的最大数目|无限制|300 条规则|300 条规则|300 条规则|
|单个传输规则的最大大小|40 KB|8 KB|8 KB|8 KB|
|所有传输规则中使用的所有正则表达式的字符限制|无限制|20 KB|20 KB|20 KB|
|所有传输规则添加到邮件的收件人的最大数目|无限制|100 位收件人|100 位收件人|100 位收件人|
|转发邮件的收件人限制|无限制|10 个收件人|10 个收件人|10 个收件人|
|重定向邮件的次数|3 次重定向|1 次重定向|1 次重定向|1 次重定向|
|传输规则重定向邮件次数|无限制|1 次重定向|1 次重定向|1 次重定向|

## <a name="moderation-limits"></a>审阅限制

这些限制将控制用于适用于通讯组和传输规则的邮件审批的审阅设置。

- **仲裁** 邮箱的最大大小：如果仲裁邮箱超过此限制，需要仲裁的邮件将返回到 NDR 邮箱中未送达 (发件人) 。

- **最大审阅人** 数：可以分配给单个仲裁通讯组或可以使用单个传输规则添加到邮件的审阅人的最大数目。 Note that you can't specify a distribution group as a moderator.

- **等待审核的邮件** 过期时间：默认情况下，等待审核的邮件在两天后过期。 但每 7 天将处理一次已过期的中继邮件。 这意味着，中继邮件会在 2 到 9 天内随时过期。

- **过期的审核** 通知邮件的最大速率：此限制设置 1 小时内过期的已审核邮件的通知邮件的最大数量。 对数据中心内的每个邮箱数据库施加了此限制。

在使用率较高的时段内，一些发件人可能无法收到已过期的中继邮件的通知邮件。但仍可使用送达报告来发现这些通知。

### <a name="moderation-limits"></a>审阅限制

| 功能 | Microsoft 365 商业基础版 | Microsoft 365 商业标准版 | Office 365 企业版 E1 | Office 365 企业版 E3 | Office 365 企业版 E5 | Office 365 企业版 F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|仲裁邮箱的最大大小|10 GB|10 GB|10 GB|10 GB|10 GB|10 GB|
|审阅人的最大数目|10 个审阅人|10 个审阅人|10 个审阅人|10 个审阅人|10 个审阅人|10 个审阅人|
|等待审阅的邮件的过期时间|2 天|2 天|2 天|2 天|2 天|2 天|
|过期的审阅通知邮件的最大速率|每小时 300 个过期通知|每小时 300 个过期通知|每小时 300 个过期通知|每小时 300 个过期通知|每小时 300 个过期通知|每小时 300 个过期通知|

### <a name="moderation-limits-across-standalone-options"></a>跨独立选项的审阅限制

| 功能 | Exchange Server 2013 | Exchange Online 计划 1 | Exchange Online 计划 2 | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|仲裁邮箱的最大大小|无限制<sup>1</sup>|10 GB|10 GB|10 GB|
|审阅人的最大数目|无限制|10 个审阅人|10 个审阅人|10 个审阅人|
|等待审阅的邮件的过期时间|5 天<sup>1</sup>|2 天|2 天|2 天|
|过期的审阅通知邮件的最大速率|每小时 300 个过期通知|每小时 300 个过期通知|每小时 300 个过期通知|每小时 300 个过期通知|

> [!NOTE]
> <sup>1</sup> 这是 Exchange Server 2013 组织的默认限制。管理员可以为其组织更改此值。

## <a name="exchange-activesync-limits"></a>Exchange ActiveSync 限制

以下限制适用于 Microsoft Exchange ActiveSync，一个在移动设备和 Exchange 之间同步邮箱数据的客户端协议。

- **Exchange ActiveSync限制**：每个邮箱Exchange ActiveSync设备的最大数量。

- **Exchange ActiveSync删除** 限制：Exchange Exchange ActiveSync在一个月内可以删除的最大设备数。

### <a name="exchange-activesync-limits"></a>Exchange ActiveSync 限制

| 功能 | Microsoft 365 商业基础版 | Microsoft 365 商业标准版 | Office 365 企业版 E1 | Office 365 企业版 E3 | Office 365 企业版 E5 | Office 365 企业版 F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Exchange ActiveSync 设备限制|100|100|100|100|100|100|
|Exchange ActiveSync 设备删除限制|20|20|20|20|20|20|

### <a name="exchange-activesync-limits-across-standalone-options"></a>独立选项中的 Exchange ActiveSync 限制

| 功能 | Exchange Server 2013 | Exchange Online 计划 1 | Exchange Online 计划 2 | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|Exchange ActiveSync 设备限制|100|100|100|100|
|Exchange ActiveSync 设备删除限制|20|20|20|20|
