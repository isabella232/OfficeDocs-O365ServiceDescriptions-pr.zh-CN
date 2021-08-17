---
title: Exchange Online美国政府环境
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 本文概述了美国政府云与商业云之间的功能差异，如 Exchange Online service description 中所列。
ms.openlocfilehash: 1c0b3c415b388f1c84c49e09aae0ed243e436b6f
ms.sourcegitcommit: 4ef127c684c8a6ad630a2b9bce2fe3fb25aa3e25
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/16/2021
ms.locfileid: "58363608"
---
# <a name="exchange-online-for-us-government-environments"></a>Exchange Online美国政府环境

本文概述了美国政府云与商业云之间的功能差异，如 Exchange Online [service description 中所列](../../exchange-online-service-description/exchange-online-service-description.md)。 Exchange Online DoD 政府社区云 (GCC) 、GCC、国防部 (DoD) 可用。

有关政府云（包括资格[和购买）Microsoft 365政府 - 如何购买](./microsoft-365-government-how-to-buy.md)。 若要比较Office 365 政府版，请参阅Office 365 政府版[计划](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)。

若要了解管理网络连接时所需的终结点，请参阅 Office 365 美国政府 GCC[高](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business)终结点或 Office 365 美国政府[DoD 终结点](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)。

除了享受云解决方案的功能Office 365，组织还可从美国政府云环境特有的以下功能中获益：

- 组织的客户内容在逻辑上与商业服务中的客户内容Office 365隔离。

- 你的组织的客户内容存储在美国的其余位置。

- 对组织的客户内容的访问权限只限于屏蔽的 Microsoft 员工。

- 政府云环境符合美国公共部门客户通常需要的认证和资格鉴定。

我们的一般意图是Exchange商业特性和功能到政府云环境。 也就是说，由于政府云客户的要求，某些功能不可用。 其他功能将进入政府环境，但尚不可用。 请参阅以下部分，了解政府云环境中的功能可用性。

## <a name="exchange-online-features"></a>Exchange Online 功能

下表概述了指定的Exchange Online功能在 GCC、GCC 高和 DoD 环境中是否可用。 当支持声明存在细微差别时 (或缺少) ，则提供其他上下文。<br><br>

| 功能 | GCC | GCC 高 | DoD | 主要注意事项 |
|:-----|:-----|:-----|:-----|:-----|
|**[规划和部署](../../exchange-online-service-description/planning-and-deployment.md)**|||||
|支持的混合部署|是|是|是|为了与本地Exchange Server共存，Microsoft 需要安装至少一台 Exchange Server 2013 客户端访问服务器 (或 Exchange Server 2016.) 。 Exchange Server 2010 及更早版本不受支持。|
|支持的 IMAP 迁移|是|是|是||
|支持的直接转换迁移|是|是|是||
|支持的暂存迁移|是|是|是|高和 doD 不支持 GCC GSuite 迁移。 有关详细信息，请参阅执行 <a href="/exchange/mailbox-migration/perform-g-suite-migration">GSuite 迁移</a>。|
|**[权限](../../exchange-online-service-description/permissions.md)**|**GCC**|**GCC 高级**|**DoD**|**主要注意事项**|
|基于角色的权限|是|是|是||
|角色组|是|是|是||
|角色分配策略|是|是|是||
|**[邮件策略和合规性](../../exchange-online-service-description/message-policy-and-compliance.md)**|**GCC**|**GCC 高级**|**DoD**|**主要注意事项**|
|存档基于 Exchange Online 的邮箱|是|是|是||
|内部部署邮箱的基于云的存档|是|是|是||
|Messaging Records Management (MRM) |是|是|是||
|手动保留策略、标签和标记 |是|是|是||
|静态状态时的数据加密 (BitLocker)|是|是|是||
|使用 Azure 信息保护的 IRM|是|是|是|有关高和 DoD 中 AIP 限制GCC，请参阅 Azure 信息保护高级版<a href="/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description">政府服务说明</a>。<br><br>Azure 信息保护不包含在 G1/F3 中，但可以单独购买为附加项，并启用受支持的信息权限管理 (IRM) 功能。 某些 Azure 信息保护功能需要订阅 Office 365 专业增强版，但 F3 中Office 365 政府版 G1或Office 365 政府版订阅。|
|使用 Windows Server AD RMS 的 IRM|是|是|是|Windows Server ADRMS 是一种本地服务器，必须单独购买和管理，才能启用受支持的 IRM 功能。|
|Office 365 邮件加密|是|是|是|请参阅[本文Office 365 邮件加密 GCC High/DoD](#office-365-message-encryptionbehavior-across-gcc-highdod-boundary)边界的 Office 365 邮件加密 行为以及<a href="/microsoft-365/compliance/ome-version-comparison#unique-characteristics-of-office-365-message-encryption-in-a-gcc-high-deployment">GCC 高</a>部署中 Office 365 邮件加密 的唯一特征，其中记录了 Office 365 邮件加密 在 GCC High/DoD 和非 GCC High/DoD 用户之间发送消息时的行为细微差别。|
|客户密钥|是|是|是|需要 G5 服务计划。|
|S/MIME|是|是|是||
|就地保留和诉讼保留|是|是|是|需要 G3 或 G5 服务计划。|
|就地电子数据展示|是|是|是||
|邮件流规则|是|是|是||
|数据丢失预防|是|是|是|需要 G3 或 G5 服务计划。|
|日记功能 |是|是|是||
|**[反垃圾邮件和反恶意软件保护](../../exchange-online-service-description/anti-spam-and-anti-malware-protection.md)**|**GCC**|**GCC 高级**|**DoD**|**主要注意事项**|
|内置反垃圾邮件保护|是|是|是||
|自定义反垃圾邮件策略|是|是|是||
|内置反恶意软件保护|是|是|是||
|自定义反恶意软件策略|是|是|是||
|隔离 - 管理员管理|是|是|是||
|隔离 - 最终用户自我管理|是|是|是||
|Microsoft Defender for Office 365|是|是|是|需要 G5 服务 (或购买加载项) 。<br><br>高和 DoD 中尚未提供针对用户和域模拟和欺骗智能GCC网络钓鱼。|
|**[邮件流](../../exchange-online-service-description/mail-flow.md)**|**GCC**|**GCC 高级**|**DoD**|**主要注意事项**|
|出站邮件的自定义路由|是|是|是||
|与受信任合作伙伴的安全邮件|是|是|是||
|有条件的邮件路由|是|是|是||
|向入站安全列表添加合作伙伴|是|是|是||
|混合电子邮件路由|是|是|是||
|**[收件人](../../exchange-online-service-description/recipients.md)**|**GCC**|**GCC 高级**|**DoD**|**主要注意事项**|
|容量报警|是|是|是||
|混乱邮件|是|是|是||
|MailTips|是|是|是||
|委托访问|是|是|是||
|收件箱规则|是|是|是||
|已连接帐户|是|否|否|此功能在高GCC DoD 中不受支持，因为第三方服务的出站连接受到限制。 有关影响的功能详细信息，请参阅本文中的第 [三方](#connectivity-with-third-party-services) 服务连接。|
|非活动邮箱|是|是|是|需要 G3 或 G5 服务计划。|
|脱机通讯簿|是|是|是||
|通讯簿策略|是|是|是||
|分层通讯簿|是|是|是||
|地址列表和全局地址列表|是|是|是||
|Office 365 组|是|是|是|在高Office 365 DoD 环境中不支持GCC组来宾访问。 有关详细信息，请参阅 <a href="/azure/azure-government/documentation-government-services-securityandidentity">Azure 政府安全 + 标识</a>。|
|通讯组|是|是|是||
|外部联系人（全局）|是|是|是|受组织关系协作限制的限制，GCC DoD 环境中。 |
|社交网络的联系人链接|是|否|否|此功能在高或GCC DoD 中不受支持。|
|资源邮箱|是|是|是||
|会议室管理|是|是|是||
|“外出”回复|是|是|是||
|Internet 日历共享|是|否|否|在 GCC High 中，Internet 日历发布/共享适用于与 GCC High 用户共享的日历的入站连接，但适用于将出站连接到 GCC High 外部的共享日历的 GCC High 用户。<br><br>在 DoD 中，不支持 Internet 日历共享，因为要求该环境中存在入站/出站连接允许列表。|
|**[报告功能和疑难解答工具](../../exchange-online-service-description/reporting-features-and-troubleshooting-tools.md)**|**GCC**|**GCC 高级**|**DoD**|**主要注意事项**|
|Microsoft 365 管理中心报告|是|是|否|报告对 DoD 不可用。 有关更新<a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">/当前</a>可用性Office 365请参阅美国政府服务说明的平台功能部分。|
|Web 服务报告|是|是|否|报告对 DoD 不可用。 有关更新<a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">/当前</a>可用性Office 365请参阅美国政府服务说明的平台功能部分。|
|邮件跟踪|是|是|是||
|审核报告|是|是|否|报告对 DoD 不可用。 有关更新<a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">/当前</a>可用性Office 365请参阅美国政府服务说明的平台功能部分。|
|统一消息报告|是|否|否||
|**[共享和协作](../../exchange-online-service-description/sharing-and-collaboration.md)**|**GCC**|**GCC 高级**|**DoD**|**主要注意事项**|
|联合共享（包括日历发布）|是|是|是|高和 doD GCC存在限制。 请参阅 [本文中的忙/](#freebusy-federation) 闲联合。|
|网站邮箱|是|是|是||
|公用文件夹|是|是|是||
|**[客户端和移动设备](../../exchange-online-service-description/clients-and-mobile-devices.md)**|**GCC**|**GCC 高级**|**DoD**|**主要注意事项**|
|微软待办 Web 上显示|是|否|否||
|Outlook for Windows|是|是|是|为满足GCC高和 DoD 合规性要求，必须至少运行版本 1803 的 Office 365 专业增强版。 Office 365 专业增强版 G1 或 F3 中不包含。|
|Outlook 网页版<sup>1</sup>|是|是|是||
|Outlook for Mac|是|是|是|为满足GCC高和 DoD 合规性要求，必须至少运行版本 1803 的 Office 365 专业增强版。 Office 365 专业增强版 G1 或 F3 中不包含。|
|Outlook for iOS 和 Android|是|是|是||
|Exchange ActiveSync|是|是|是||
|基本移动性和安全性Microsoft 365|是|否|否||
|POP 和 IMAP|是|是|是||
|SMTP|是|是|是||
|EWS 应用程序支持|是|是|是||
|**[语音消息服务](../../exchange-online-service-description/voice-message-services.md)**|**GCC**|**GCC 高级**|**DoD**|**主要注意事项**|
|语音邮件|否|否|否|不支持将本地 IP-PBX 系统与Exchange Online统一消息集成。|
|语音邮件与第三方传真的集成|否|否|否|不支持将本地 IP-PBX 系统与Exchange Online统一消息集成。|
|第三方语音邮件互操作性|否|否|否|不支持将本地 IP-PBX 系统与Exchange Online统一消息集成。|
|Skype for Business 集成|是|是|是||
|**[高可用性和业务连续性](../../exchange-online-service-description/high-availability-and-business-continuity.md)**|**GCC**|**GCC 高级**|**DoD**|**主要注意事项**|
|数据中心的邮箱复制|是|是|是||
|已删除邮箱的恢复|是|是|是||
|已删除邮件的恢复|是|是|是||
|单个项目恢复|是|是|是||
|**[互操作性、连接性和兼容性](../../exchange-online-service-description/interoperability-connectivity-and-compatibility.md)**|**GCC**|**GCC 高级**|**DoD**|**主要注意事项**|
|OWA 和 Outlook|是|是|是||
|SharePoint 互操作性|是|是|是||
|EWS 连接性支持|是|是|是||
|SMTP 中继支持|是|是|是||
|**[Exchange Online 设置和管理](../../exchange-online-service-description/exchange-online-setup-and-administration.md)**|**GCC**|**GCC 高级**|**DoD**|**主要注意事项**|
|Microsoft Office 365 门户访问|是|是|否|报告对 DoD 不可用。 有关更新<a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">/当前</a>可用性Office 365请参阅美国政府服务说明的平台功能部分。|
|Microsoft 365 管理中心访问|是|是|否|报告对 DoD 不可用。 有关更新<a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">/当前</a>可用性Office 365请参阅美国政府服务说明的平台功能部分。|
|Exchange 管理中心访问|是|是|是||
|远程 Windows PowerShell 访问|是|是|是||
|移动设备的 ActiveSync 策略|是|是|是||
|使用情况报告|是|是|否|报告对 DoD 不可用。 有关更新<a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">/当前</a>可用性Office 365请参阅美国政府服务说明的平台功能部分。|
|**[扩展服务 - 自定义、外接程序和资源](../../exchange-online-service-description/exchange-online-service-description.md)**|**GCC**|**GCC 高级**|**DoD**|**主要注意事项**|
|Outlook 加载项和 Outlook MAPI|是|是|是|只有部分 OWA Outlook外接程序可用于 GCC High 和 DoD。 请参阅[本文中的Outlook Outlook Web App](#add-insin-outlook-and-outlook-web-app)外接程序。|

1 Outlook在 Outlook for Windows 由于跨边界限制（高/非 GCC) 高）无法显示受 I (GCC RM 保护的邮件的情况下，可以使用<sup>1。</sup>

## <a name="feature-nuances-within-gcc-high-and-dod-environments"></a>高和 doD GCC的功能细微差别

### <a name="connectivity-with-third-party-services"></a>第三方服务连接  

高GCC DoD 环境都是需要明确批准和配置出站连接的受限环境。 此外，Microsoft 无法容纳允许从这些环境出站访问商业云服务 (商业 Office 365、Google GSuite、Amazon Web 服务等) 。

由于这些限制，通常不支持依赖于高/doD GCC此出站连接的功能，包括：

- 已连接帐户 - 用户无法 (Google、POP/IMAP 等帐户添加/同步) 。

- 支持第三方文件存储提供程序 - 只有 *GCC High/DoD* 中的用户的 OneDrive for Business 帐户可以从各种 Outlook 客户端中访问，以便附加/共享文件。 无法添加第三 (Dropbox、Box Google 云端硬盘) 存储帐户。

- 与社交网络（如 Facebook 或 LinkedIn）的连接。

### <a name="azure-active-directory-b2b-collaboration"></a>Azure Active DirectoryB2B 协作

Azure Active Directory目前，仅在 Azure 美国政府云中且都支持 B2B 协作的组织之间支持 B2B 协作

此外，在高和 doD Office 365不支持 B2B 用户作为 GCC组中的来宾。 

有关详细信息和最新更新，请参阅 Azure [政府安全 + 标识](/azure/azure-government/documentation-government-services-securityandidentity)。

### <a name="office-365-message-encryption-behavior-across-gcc-highdod-boundary"></a>Office 365 邮件加密高/GCC边界的异常行为

如果计划在高Office 365 邮件加密使用GCC，请注意有关收件人体验的以下独特特征：  

- 从高GCC DoD 向相同环境中收件人发送加密电子邮件时：
    
    - 发件人可以在 Outlook for PC 和 Mac 及 Outlook 网页版 中手动加密电子邮件，或者组织可以设置策略以使用 Exchange 流规则加密电子邮件。
    
    - GCC/DoD 内的收件人在 Outlook for PC 和 Mac 中接收相同的内联阅读体验，Outlook 网页版所有其他Office 365体验。

<!-- end list -->

- 将加密电子邮件从 GCC High 或 DoD 发送到该环境外部的收件人时 (包括GCC商业) ：
    
    - 高GCC/DoD 内的发件人可以在高/DoD 边界GCC发送加密电子邮件。
    
    - 高/GCC外部的所有收件人（包括商业 Office 365 用户、Outlook.com 用户和其他电子邮件提供商的其他用户）将收到包装邮件。 此包装邮件将收件人重定向到收件人可在其中阅读和回复邮件的 OME 门户。

有关详细信息和最新更新，请参阅 [比较 OME 的版本](/microsoft-365/compliance/ome-version-comparison)。

### <a name="freebusy-federation"></a>忙/闲联盟

联合共享（包括忙/闲信息）目前受到 DoD 环境中的几个重要限制。

在GCC高环境中：

-  (High 内的租户、GCC 和商业云中的租户之间以及通过混合共存 GCC (Exchange 2013 或更高版本) 支持联盟信任关系，包括双向忙/闲共享) 。

在 DoD 环境中：

  - 目前 (DoD) 租户之间支持联盟信任关系（包括忙/闲共享）。 DoD 租户与商业租户GCC、GCC高或商业租户之间不受支持。

### <a name="client-configuration"></a>客户端配置

部署和配置 Office 专业增强版 (包括Outlook) 。 有关这些步骤的详细说明，请参阅[D guidance for deploying Microsoft 365 企业应用版 in a GCC High or DoD environment。](/deployoffice/deploy-microsoft-365-apps-gcc-high-dod)

Outlook适用于 iOS 和 Android 的 GCC 也适用于高和 DoD 环境。 若要详细了解这些环境中的功能限制和管理，请参阅在 政府社区云 中使用[适用于 iOS](/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud)Outlook for Android Outlook。

### <a name="add-ins-in-outlook-and-outlook-web-app"></a>加载项和加载项Outlook Outlook Web App  

只有部分 OWA Outlook外接程序可用于 GCC High 和 DoD。 My Templates and Suggested Meetings are available and expected to function. 仅支持五个默认 OWA 加载项。 但是，Microsoft 针对高或 DoD 的合规性承诺未涵盖这些集成GCC第三方应用程序。 在为组织配置加载项之前，客户应熟悉第三方数据处理做法和合规性承诺。

## <a name="feature-nuances-within-gcc-environments-for-microsoft-to-do"></a>GCC环境中的功能微软待办

| 功能 | 说明 | WW | 在 GCC |
|:-----|:-----|:-----|:-----|
|支持的平台|Web、Android、iOS、Mac、Windows|全部|仅 Web|
|M365 中心支持|与 planner、Outlook、Teams 的集成|全部|Outlook，planner (Teams可用于Teams任务应用) |
|奇妙清单迁移|允许 wunderlist 用户将数据微软待办 Web 上的服务器|是|否|
|推送通知|向最终用户发送推送通知，提醒等。|是|否|
|帮助临时支持|使用 helpshift 接口创建支持请求|是|否|
|My Day|规划您的一天|是|是|
|计划列表|查看具有截止日期的所有任务|是|是|
|已分配给你列表|在共享列表、Planner 或 WXP 中分配给你的所有任务 (将来) |是|是|
|已标记的电子邮件|查看 outlook 中标记为任务的电子邮件|是|是|
|多帐户支持|在一个窗格中使用家庭帐户和办公室帐户|是|是|
|列表共享|与同一组织的同事共享列表|是|是|
|跨租户共享|在组织外部共享任务列表|是|否|
|提醒和定期|设置任务的提醒 |是|是|

*两种环境中均提供未提及的其他任何功能。