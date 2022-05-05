---
title: 美国政府环境Exchange Online
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: 本文概述了美国政府云与商业云之间的功能差异，如Exchange Online服务说明中所列。
ms.openlocfilehash: 5885a10d1018fead185f373d1b24139c4765c410
ms.sourcegitcommit: e4bf187c926340f4afb68bfe51d38b303664ae00
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/05/2022
ms.locfileid: "65218168"
---
# <a name="exchange-online-for-us-government-environments"></a>美国政府环境Exchange Online

本文概述了美国政府云与商业云之间的功能差异，如[Exchange Online服务说明](../../exchange-online-service-description/exchange-online-service-description.md)中所列。 Exchange Online适用于政府社区云 (GCC) 、GCC高和国防部 (DoD) 环境。

有关政府云的详细信息，包括资格和购买，请[参阅Microsoft 365政府 - 如何购买](./microsoft-365-government-how-to-buy.md)。 若要比较Office 365 政府版计划，[请参阅Office 365 政府版计划](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)。

若要了解管理网络连接时所需的终结点，请参阅[Office 365美国政府GCC高级终结点](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business)或[Office 365美国政府 DoD 终结点](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)。

除了享受Office 365的功能外，组织还受益于美国政府云环境特有的以下功能：

- 组织的客户内容在逻辑上与商业Office 365服务中的客户内容隔离。

- 组织的客户内容存储在美国中。

- 对组织的客户内容的访问权限只限于屏蔽的 Microsoft 员工。

- 政府云环境通常符合美国公共部门客户所需的认证和认证。

我们的一般意图是将所有Exchange商业功能和功能交付给政府云环境。 也就是说，由于政府云客户的要求，某些功能不可用。 其他功能将进入政府环境，但尚不可用。 请参阅以下部分，了解政府云环境中的功能可用性。

## <a name="exchange-online-features"></a>Exchange Online 功能

下表概述了指定的Exchange Online功能是否在GCC、GCC高和 DoD 环境中可用。 如果支持声明 (或缺乏) 存在细微差别，则会提供其他上下文。<br><br>

| 功能 | GCC | GCC 高 | DoD | 关键注意事项 |
|:-----|:-----|:-----|:-----|:-----|
|**[规划和部署](/exchange/plan-and-deploy/plan-and-deploy)**|||||
|支持的混合部署|是|是|是|为了与本地Exchange Server共存，Microsoft 需要安装至少一个 Exchange Server 2013 客户端访问服务器 (或 Exchange Server 2016.) 。 不支持Exchange Server 2010 及更早版本。|
|支持的 IMAP 迁移|是|是|是||
|支持的直接转换迁移|是|是|是||
|支持的暂存迁移|是|是|是|高GCC和 DoD 不支持 GSuite 迁移。 有关详细信息，请参阅 <a href="/exchange/mailbox-migration/perform-g-suite-migration">“执行 GSuite 迁移</a>”。|
|**[权限](/exchange/permissions-exo/permissions-exo)**|**GCC**|**GCC 高级**|**DoD**|**关键注意事项**|
|基于角色的权限|是|是|是||
|角色组|是|是|是||
|角色分配策略|是|是|是||
|**[邮件策略和合规性](/exchange/policy-and-compliance/policy-and-compliance)**|**GCC**|**GCC 高级**|**DoD**|**关键注意事项**|
|存档基于 Exchange Online 的邮箱|是|是|是||
|内部部署邮箱的基于云的存档|是|是|是||
|Messaging Records Management (MRM) |是|是|是||
|手动保留策略、标签和标记 |是|是|是||
|静态状态时的数据加密 (BitLocker)|是|是|是||
|使用 Azure 信息保护的 IRM|是|是|是|有关 GCC High 和 DoD 中 AIP 限制的详细信息，<a href="/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description">请参阅 Azure 信息保护 高级版政府服务说明</a>。<br><br>Azure 信息保护不包括在 G1/F3 中，但可以将其作为单独的加载项购买，并启用支持的信息权限管理 (IRM) 功能。 某些 Azure 信息保护功能需要订阅Office 365 专业增强版，但不包含在 Office 365 政府版 G1 或 Office 365 政府版 F3 中。|
|使用 Windows Server AD RMS 的 IRM|是|是|是|Windows Server AD RMS 是必须单独购买和管理才能启用支持的 IRM 功能的本地服务器。|
|Office 365 邮件加密|是|是|是|请参阅本文Office 365 GCC[高/DoD 边界内的消息加密行为](#office-365-message-encryptionbehavior-across-gcc-highdod-boundary)，以及<a href="/microsoft-365/compliance/ome-version-comparison#unique-characteristics-of-office-365-message-encryption-in-a-gcc-high-deployment">GCC高部署中Office 365消息加密的独特特征</a>，其中记录了在GCC高/DoD 和非- 之间发送消息时Office 365消息加密的行为细微差别GCC高/多维用户。|
|客户密钥|是|是|是|需要 G5 服务计划。|
|S/MIME|是|是|是||
|就地保留和诉讼保留|是|是|是|需要 G3 或 G5 服务计划。|
|就地电子数据展示|是|是|是||
|邮件流规则|是|是|是||
|数据丢失预防|是|是|是|需要 G3 或 G5 服务计划。|
|日记功能 |是|是|是||
|**[反垃圾邮件和反恶意软件保护](/exchange/antispam-and-antimalware/antispam-and-antimalware)**|**GCC**|**GCC 高级**|**DoD**|**关键注意事项**|
|内置反垃圾邮件保护|是|是|是||
|自定义反垃圾邮件策略|是|是|是||
|内置反恶意软件保护|是|是|是||
|自定义反恶意软件策略|是|是|是||
|隔离 - 管理员管理|是|是|是||
|隔离 - 最终用户自我管理|是|是|是||
|Microsoft Defender for Office 365|是|是|是|需要 G5 服务计划 (或购买加载项) 。<br><br>GCC High 和 DoD 中尚不提供针对用户和域模拟和欺骗智能的反网络钓鱼。|
|**[邮件流](/exchange/security-and-compliance/mail-flow-rules/mail-flow-rules)**|**GCC**|**GCC 高级**|**DoD**|**关键注意事项**|
|出站邮件的自定义路由|是|是|是||
|与受信任合作伙伴的安全邮件|是|是|是||
|有条件的邮件路由|是|是|是||
|向入站安全列表添加合作伙伴|是|是|是||
|混合电子邮件路由|是|是|是||
|**[收件人](/exchange/recipients-in-exchange-online/recipients-in-exchange-online)**|**GCC**|**GCC 高级**|**DoD**|**关键注意事项**|
|容量报警|是|是|是||
|混乱邮件|是|是|是||
|MailTips|是|是|是||
|委托访问|是|是|是||
|收件箱规则|是|是|是||
|已连接帐户|是|否|否|由于与第三方服务的出站连接受到限制，GCC高或 DoD 不支持此功能。 有关受影响功能的详细信息，请参阅本文中第 [三方服务的连接](#connectivity-with-third-party-services) 。|
|非活动邮箱|是|是|是|需要 G3 或 G5 服务计划。|
|脱机通讯簿|是|是|是||
|通讯簿策略|是|是|是||
|分层通讯簿|是|是|是||
|地址列表和全局地址列表|是|是|是||
|Office 365 组|是|是|是|GCC高和 DoD 环境中不支持来宾访问Office 365组。 有关详细信息，请参阅<a href="/azure/azure-government/documentation-government-services-securityandidentity">Azure 政府安全 + 标识</a>。|
|通讯组|是|是|是||
|外部联系人（全局）|是|是|是|在 GCC High 和 DoD 环境中，受组织关系协作限制的限制。 |
|社交网络的联系人链接|是|否|否|高GCC或 DoD 不支持此功能。|
|资源邮箱|是|是|是||
|会议室管理|是|是|是||
|“外出”回复|是|是|是||
|Internet 日历共享|是|否|否|在“GCC高”中，Internet 日历发布/共享适用于与GCC高用户共享的日历的入站连接，但不适用于GCC高用户，这些用户在出站连接到 GCC High 之外的共享日历。<br><br>在 DoD-Internet 日历中，由于要求在该环境中列出入站/出站连接，因此不支持共享。|
|**[报告功能和疑难解答工具](../../exchange-online-service-description/reporting-features-and-troubleshooting-tools.md)**|**GCC**|**GCC 高级**|**DoD**|**关键注意事项**|
|Microsoft 365 管理中心报告|是|是|否|报表不适用于 DoD。 有关更新/当前可用性，请参阅Office 365美国政府服务说明中的<a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">平台功能</a>部分。|
|Web 服务报表|是|是|否|报表不适用于 DoD。 有关更新/当前可用性，请参阅Office 365美国政府服务说明中的<a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">平台功能</a>部分。|
|邮件跟踪|是|是|是||
|审核报告|是|是|否|报表不适用于 DoD。 有关更新/当前可用性，请参阅Office 365美国政府服务说明中的<a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">平台功能</a>部分。|
|统一消息报告|是|否|否||
|**[共享和协作](/exchange/sharing/sharing)**|**GCC**|**GCC 高级**|**DoD**|**关键注意事项**|
|联合共享（包括日历发布）|是|是|是|高GCC和 DoD 中都存在限制。 请参阅本文中的 [“忙/忙”联合身份验证](#freebusy-federation) 。|
|网站邮箱|是|是|是||
|公用文件夹|是|是|是||
|**[客户端和移动设备](/exchange/clients-and-mobile-in-exchange-online/clients-and-mobile-in-exchange-online)**|**GCC**|**GCC 高级**|**DoD**|**关键注意事项**|
|Web 上的微软待办|是|否|否||
|Outlook for Windows|是|是|是|若要满足GCC高和 DoD 符合性要求，必须至少运行版本 1803 的Office 365 专业增强版。 G1 或 F3 不包含Office 365 专业增强版。|
|Outlook 网页版<sup>1</sup>|是|是|是||
|Outlook for Mac|是|是|是|若要满足GCC高和 DoD 符合性要求，必须至少运行版本 1803 的Office 365 专业增强版。 G1 或 F3 不包含Office 365 专业增强版。|
|IOS 和 Android 版 Outlook|是|是|是||
|Exchange ActiveSync|是|是|是||
|Microsoft 365的基本移动性和安全性|是|否|否||
|POP 和 IMAP|是|是|是||
|SMTP|是|是|是||
|EWS 应用程序支持 <sup>2</sup>|是|是|是||
|**[语音消息服务](/exchange/plan-and-deploy/integration-with-sharepoint-and-skype/integration-with-sharepoint-and-skype)**|**GCC**|**GCC 高级**|**DoD**|**关键注意事项**|
|语音邮件|否|否|否|不支持将本地 IP-PBX 系统与Exchange Online统一消息传送进行集成。|
|语音邮件与第三方传真的集成|否|否|否|不支持将本地 IP-PBX 系统与Exchange Online统一消息传送进行集成。|
|第三方语音邮件互操作性|否|否|否|不支持将本地 IP-PBX 系统与Exchange Online统一消息传送进行集成。|
|Skype for Business 集成|是|是|是||
|**[高可用性和业务连续性](/exchange/high-availability/high-availability)**|**GCC**|**GCC 高级**|**DoD**|**关键注意事项**|
|数据中心的邮箱复制|是|是|是||
|已删除邮箱的恢复|是|是|是||
|已删除邮件的恢复|是|是|是||
|单个项目恢复|是|是|是||
|**[互操作性、连接性和兼容性](/exchange/security-and-compliance/interoperability-connectivity-and-compatiblity)**|**GCC**|**GCC 高级**|**DoD**|**关键注意事项**|
|OWA 和 Outlook 中的状态|是|是|是||
|SharePoint 互操作性|是|是|是||
|EWS 连接性支持|是|是|是||
|SMTP 中继支持|是|是|是||
|**[Exchange Online 设置和管理](/exchange/architecture/client-access/exchange-admin-center)**|**GCC**|**GCC 高级**|**DoD**|**关键注意事项**|
|Microsoft Office 365 门户访问|是|是|否|报表不适用于 DoD。 有关更新/当前可用性，请参阅Office 365美国政府服务说明中的<a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">平台功能</a>部分。|
|Microsoft 365 管理中心访问|是|是|否|报表不适用于 DoD。 有关更新/当前可用性，请参阅Office 365美国政府服务说明中的<a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">平台功能</a>部分。|
|Exchange 管理中心访问|是|是|是||
|远程 Windows PowerShell 访问|是|是|是||
|移动设备的 ActiveSync 策略|是|是|是||
|使用情况报告|是|是|否|报表不适用于 DoD。 有关更新/当前可用性，请参阅Office 365美国政府服务说明中的<a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">平台功能</a>部分。|
|**[扩展服务 - 自定义、外接程序和资源](../../exchange-online-service-description/exchange-online-service-description.md)**|**GCC**|**GCC 高级**|**DoD**|**关键注意事项**|
|Outlook 加载项和 Outlook MAPI|是|是|是|只有一些 OWA 和 Outlook 加载项在 GCC High 和 DoD 中可用。 请参阅本文[Outlook和Outlook Web App中的加载](#add-insin-outlook-and-outlook-web-app)项。|

当Windows Outlook因跨界限制而无法显示受 IRM 保护的消息 (GCC高/非GCC高方案) 时，可以使用 Web 上的 <sup>1</sup> 个Outlook。</br>
<sup>2</sup> 仅流出到客户可以证明其拥有的特定地址空间是允许的，因此这排除了移动设备使用的第三方服务和广泛的 IP 范围。

## <a name="feature-nuances-within-gcc-high-and-dod-environments"></a>高GCC和 DoD 环境中的特征细微差别

### <a name="connectivity-with-third-party-services"></a>与第三方服务的连接  

GCC高和 DoD 环境都是需要显式审批和配置出站连接的限制环境。 此外，Microsoft 无法适应允许从这些环境到商业云服务的出站访问请求， (商业Office 365、Google GSuite、Amazon Web Services 等) 。

由于这些限制，通常不支持依赖于来自GCC高/DoD 环境的此出站连接的功能，包括：

- 连接的帐户 - 用户无法 (Google、POP/IMAP 等) 添加/同步帐户。

- 支持第三方文件存储提供程序 - 只有用户在 *GCC High/DoD 中的OneDrive for Business* 帐户才能从各种Outlook客户端中访问，以便附加/共享文件。 无法添加第三方存储帐户 (Dropbox、Box、Google 云端硬盘) 。

- 与社交网络（如 Facebook 或 LinkedIn）的连接。

### <a name="azure-active-directory-b2b-collaboration"></a>Azure Active Directory B2B 协作

Azure Active Directory B2B 协作目前仅在 Azure 美国政府云中且都支持 B2B 协作的组织之间受支持

此外，GCC高和 DoD 环境中不支持 B2B 用户作为Office 365组中的来宾。 

有关详细信息和最新更新，[请参阅Azure 政府安全 + 标识](/azure/azure-government/documentation-government-services-securityandidentity)。

### <a name="office-365-message-encryption-behavior-across-gcc-highdod-boundary"></a>跨高/DoD 边界GCC Office 365消息加密行为

如果计划在高GCC环境中使用Office 365消息加密，请注意这些有关收件人体验的独特特征：  

- 将加密电子邮件从 GCC High 或 DoD 发送到同一环境中的收件人时：
    
    - 发件人可以在电脑和 Mac 和 Outlook 网页版 的Outlook中手动加密电子邮件，或者组织可以设置策略以使用Exchange邮件流规则加密电子邮件。
    - GCC高/DoD 中的收件人可在电脑和 Mac 的Outlook中获得与所有其他Office 365用户相同的内联阅读体验Outlook 网页版。

<!-- end list -->

- 将加密电子邮件从 GCC High 发送到该环境外部的收件人时 (包括 DoD、GCC 和商业) ：

    - GCC High 内的发件人可以在高边界GCC外发送加密电子邮件。
    - GCC High 之外的所有收件人（包括 DoD、商业Office 365用户、Outlook.com 用户以及其他电子邮件提供商的其他用户）都会收到通知邮件。 此通知邮件将收件人重定向到加密邮件门户，收件人可在门户中读取和答复邮件。
    - 目前无法与商业云中的用户共享文档和下载的电子邮件附件。  加密附件只能在加密的消息门户中预览。

### <a name="freebusy-federation"></a>忙/忙联合

联合共享（包括闲/忙信息）目前受到 DoD 环境中的几个重要限制。

在高GCC环境中：

- 联合信任 (包括双向自由/忙碌共享) 支持在 GCC High 中的租户、GCC 和商业云中的租户之间，以及通过混合共存 (Exchange 2013 或更高版本) 。

在 DoD 环境中：

  - 联合信任 (包括闲/忙共享) 目前仅在 DoD 环境中的租户之间受支持。 DoD 租户和GCC、GCC高租户或商业租户之间不支持此功能。

### <a name="client-configuration"></a>客户端配置

部署和配置 Office ProPlus (（包括Outlook) ）涉及其他步骤。 有关这些步骤的详细说明，请参阅[有关在高GCC或 DoD 环境中部署Microsoft 365 企业应用版的指南](/deployoffice/deploy-microsoft-365-apps-gcc-high-dod)。

适用于 iOS 和 Android 的Outlook也适用于GCC高和 DoD 环境。 若要详细了解这些环境中的功能限制和管理，请参阅[政府社区云中为 iOS 和 Android 使用Outlook](/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud)。

### <a name="add-ins-in-outlook-and-outlook-web-app"></a>Outlook和Outlook Web App中的加载项  

只有一些 OWA 和 Outlook 加载项在 GCC High 和 DoD 中可用。 “我的模板”和“建议的会议”可用并且有望正常运行。 仅支持五个默认 OWA 加载项。 与第三方应用程序集成是可能的，但是，Microsoft 针对 GCC High 或 DoD 的合规性承诺并未涵盖这些集成。 在为组织配置加载项之前，客户应熟悉第三方数据处理做法和合规性承诺。

## <a name="feature-nuances-within-gcc-environments-for-microsoft-to-do"></a>微软待办GCC环境中的特征细微差别

| 功能 | 说明 | WW | GCC中的可用性 |
|:-----|:-----|:-----|:-----|
|支持的平台|Web、Android、iOS、Mac、Windows|全部|仅 Web|
|M365 中心支持|与 Outlook、Teams、Planner 的集成|全部|Outlook，Planner (Teams可用于Teams任务应用) |
|奇妙清单迁移|允许 wunderlist 用户将数据迁移到 Web 上的微软待办|是|否|
|推送通知|向最终用户发送推送通知以获取提醒等。|是|否|
|Helpshift 支持|使用 helpshift 接口创建支持请求|是|否|
|我的一天|规划你的一天|是|是|
|计划列表|查看截止日期的所有任务|是|是|
|分配给你的列表|在共享列表、Planner 或 WXP 中分配给你的所有任务 (将来) |是|是|
|已标记的电子邮件|查看 Outlook 中标记为任务的电子邮件|是|是|
|多帐户支持|在一个窗格中使用家庭和办公室帐户|是|是|
|列表共享|与同一组织中的同事共享列表|是|是|
|跨租户共享|在组织外部共享任务列表|是|否|
|提醒和重复|为任务设置提醒 |是|是|

*未提及的任何其他功能均可在这两个环境中使用。