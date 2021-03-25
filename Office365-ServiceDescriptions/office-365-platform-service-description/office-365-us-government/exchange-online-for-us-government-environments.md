---
title: 适用于美国政府环境的 Exchange Online
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 本文概述了美国政府云与商业云之间的功能差异，如 Exchange Online 服务说明所列。
ms.openlocfilehash: 2ecef2aeaa9c216e715f1084be022c5c4d0cce32
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173967"
---
# <a name="exchange-online-for-us-government-environments"></a>适用于美国政府环境的 Exchange Online

本文概述了美国政府云与商业云之间的功能差异，如 [Exchange Online 服务说明所列](../../exchange-online-service-description/exchange-online-service-description.md)。 Exchange Online 可用于政府社区云 (GCC) 、GCC High 和国防部 (DoD) 环境。

有关政府云（包括资格和购买）详细信息，请参阅 [Microsoft 365 政府版 - 如何购买](./microsoft-365-government-how-to-buy.md)。 若要比较 Office 365 政府版计划，请参阅 [Office 365 政府版计划](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)。

若要了解管理网络连接时所需的终结点，请参阅 [Office 365 美国政府版 GCC 高](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) 终结点或 Office [365 美国政府版 DoD 终结点](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)。

除了享受 Office 365 的特性和功能之外，组织还可从美国政府云环境特有的以下功能中获益：

- 组织的客户内容在逻辑上与商业 Office 365 服务中的客户内容隔离。

- 你的组织的客户内容存储在美国的其余位置。

- 对组织的客户内容的访问权限只限于屏蔽的 Microsoft 员工。

- 政府云环境符合美国公共部门客户通常需要的认证和资格鉴定。

我们的一般意图是，向政府云环境提供所有 Exchange 商业特性和功能。 也就是说，由于政府云客户的要求，某些功能不可用。 其他功能将进入政府环境，但尚不可用。 请参阅以下部分，了解政府云环境中的功能可用性。

## <a name="exchange-online-features"></a>Exchange Online 功能

下表概述了指定的 Exchange Online 功能在 GCC、GCC High 和 DoD 环境中是否可用。 当支持声明存在细微差别或缺少 (时) ，则提供其他上下文。<br><br>

| 功能 | GCC | GCC 高 | DoD | 主要注意事项 |
|:-----|:-----|:-----|:-----|:-----|
|**[规划和部署](../../exchange-online-service-description/planning-and-deployment.md)**|||||
|支持的混合部署|是|是|是|为了与本地Exchange Server共存，Microsoft 需要安装至少一台 Exchange Server 2013 客户端访问服务器 (或 Exchange Server 2016.) 。 Exchange Server 2010 及更早版本不受支持。|
|支持的 IMAP 迁移|是|是|是||
|支持的直接转换迁移|是|是|是||
|支持的暂存迁移|是|是|是|GSuite 迁移不受 GCC High 和 DoD 支持。 有关详细信息，请参阅执行 <a href="/exchange/mailbox-migration/perform-g-suite-migration">GSuite 迁移</a>。|
|**[权限](../../exchange-online-service-description/permissions.md)**|**GCC**|**GCC 高**|**DoD**|**主要注意事项**|
|基于角色的权限|是|是|是||
|角色组|是|是|是||
|角色分配策略|是|是|是||
|**[邮件策略和合规性](../../exchange-online-service-description/message-policy-and-compliance.md)**|**GCC**|**GCC 高**|**DoD**|**主要注意事项**|
|存档基于 Exchange Online 的邮箱|是|是|是||
|内部部署邮箱的基于云的存档|是|是|是||
|Messaging Records Management (MRM) |是|是|是||
|手动保留策略、标签和标记 |是|是|是||
|静态状态时的数据加密 (BitLocker)|是|是|是||
|使用 Azure 信息保护的 IRM|是|是|是|有关 GCC High 和 DoD 中 AIP 的限制详细信息，请参阅 <a href="/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description">Azure 信息保护高级政府服务说明</a>。<br><br>Azure 信息保护不包含在 G1/F3 中，但可以单独购买为附加项，并启用受支持的信息权限管理 (IRM) 功能。 某些 Azure 信息保护功能需要订阅 Office 365 专业增强版，但 Office 365 政府版 G1 或 Office 365 政府版 F3 中未包含此订阅。|
|使用 Windows Server AD RMS 的 IRM|是|是|是|Windows Server AD RMS 是一种本地服务器，必须单独购买和管理，才能启用受支持的 IRM 功能。|
|Office 365 邮件加密|是|是|是|请参阅本文中的跨 [GCC High/DoD 边界的 Office 365](#office-365-message-encryptionbehavior-across-gcc-highdod-boundary) 邮件加密行为以及 GCC High 部署中的 <a href="/microsoft-365/compliance/ome-version-comparison#unique-characteristics-of-office-365-message-encryption-in-a-gcc-high-deployment">Office 365</a>邮件加密的唯一特征，其中记录了在 GCC High/DoD 和非 GCC High/DoD 用户之间发送邮件时 Office 365 邮件加密的行为细微差别。|
|客户密钥|是|是|是|需要 G5 服务计划。|
|S/MIME|是|是|是||
|就地保留和诉讼保留|是|是|是|需要 G3 或 G5 服务计划。|
|就地电子数据展示|是|是|是||
|邮件流规则|是|是|是||
|数据丢失预防|是|是|是|需要 G3 或 G5 服务计划。|
|日记功能 |是|是|是||
|**[反垃圾邮件和反恶意软件保护](../../exchange-online-service-description/anti-spam-and-anti-malware-protection.md)**|**GCC**|**GCC 高**|**DoD**|**主要注意事项**|
|内置反垃圾邮件保护|是|是|是||
|自定义反垃圾邮件策略|是|是|是||
|内置反恶意软件保护|是|是|是||
|自定义反恶意软件策略|是|是|是||
|隔离 - 管理员管理|是|是|是||
|隔离 - 最终用户自我管理|是|是|是||
|Microsoft Defender for Office 365|是|是|是|需要 G5 服务 (购买或购买加载项) 。<br><br>GCC High 和 DoD 中尚未提供针对用户和域模拟以及欺骗智能的防钓鱼功能。|
|**[邮件流](../../exchange-online-service-description/mail-flow.md)**|**GCC**|**GCC 高**|**DoD**|**主要注意事项**|
|出站邮件的自定义路由|是|是|是||
|与受信任合作伙伴的安全邮件|是|是|是||
|有条件的邮件路由|是|是|是||
|向入站安全列表添加合作伙伴|是|是|是||
|混合电子邮件路由|是|是|是||
|**[收件人](../../exchange-online-service-description/recipients.md)**|**GCC**|**GCC 高**|**DoD**|**主要注意事项**|
|容量报警|是|是|是||
|混乱邮件|是|是|是||
|MailTips|是|是|是||
|委托访问|是|是|是||
|收件箱规则|是|是|是||
|已连接帐户|是|否|否|由于对到第三方服务的出站连接的限制，此功能在 GCC High 或 DoD 中不受支持。 有关影响的功能详细信息，请参阅本文 [中的第三方](#connectivity-with-third-party-services) 服务连接。|
|非活动邮箱|是|是|是|需要 G3 或 G5 服务计划。|
|脱机通讯簿|是|是|是||
|通讯簿策略|是|是|是||
|分层通讯簿|是|是|是||
|地址列表和全局地址列表|是|是|是||
|Office 365 组|是|是|是|GCC High 和 DoD 环境不支持对 Office 365 组的来宾访问。 有关详细信息，请参阅 <a href="/azure/azure-government/documentation-government-services-securityandidentity">Azure 政府安全 + 标识</a>。|
|通讯组|是|是|是||
|外部联系人（全局）|是|是|是|受 GCC High 和 DoD 环境中组织关系协作限制的限制。 |
|社交网络的联系人链接|是|否|否|GCC High 或 DoD 不支持此功能。|
|资源邮箱|是|是|是||
|会议室管理|是|是|是||
|“外出”回复|是|是|是||
|Internet 日历共享|是|否|否|在 GCC High 中，Internet 日历发布/共享适用于到 GCC High 用户共享的日历的入站连接，但适用于出站连接到 GCC High 外部共享日历的 GCC High 用户。<br><br>在 DoD 中，不支持 Internet 日历共享，因为要求该环境中存在入站/出站连接允许列表。|
|**[报告功能和疑难解答工具](../../exchange-online-service-description/reporting-features-and-troubleshooting-tools.md)**|**GCC**|**GCC 高**|**DoD**|**主要注意事项**|
|Microsoft 365 管理中心报告|是|是|否|报告对 DoD 不可用。 请参阅 Office <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features"></a> 365 美国政府版服务说明的平台功能部分，获取更新/当前可用性。|
|Web 服务报告|是|是|否|报告对 DoD 不可用。 请参阅 Office <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features"></a> 365 美国政府版服务说明的平台功能部分，获取更新/当前可用性。|
|邮件跟踪|是|是|是||
|审核报告|是|是|否|报告对 DoD 不可用。 请参阅 Office <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features"></a> 365 美国政府版服务说明的平台功能部分，获取更新/当前可用性。|
|统一消息报告|是|否|否||
|**[共享和协作](../../exchange-online-service-description/sharing-and-collaboration.md)**|**GCC**|**GCC 高**|**DoD**|**主要注意事项**|
|联合共享（包括日历发布）|是|是|是|GCC High 和 DoD 都存在限制。 请参阅 [本文中的忙/](#freebusy-federation) 闲联合。|
|网站邮箱|是|是|是||
|公用文件夹|是|是|是||
|**[客户端和移动设备](../../exchange-online-service-description/clients-and-mobile-devices.md)**|**GCC**|**GCC 高**|**DoD**|**主要注意事项**|
|在 Web 上执行|是|否|否||
|Outlook for Windows|是|是|是|若要满足 GCC High 和 DoD 合规性要求，必须至少运行 Office 365 专业增强版版本 1803。 Office 365 专业增强版不包括在 G1 或 F3 中。|
|Outlook 网页版|是|是|是||
|Outlook for Mac|是|是|是|若要满足 GCC High 和 DoD 合规性要求，必须至少运行 Office 365 专业增强版版本 1803。 Office 365 专业增强版不包括在 G1 或 F3 中。|
|IOS 和 Android 版 Outlook|是|是|是||
|Exchange ActiveSync|是|是|是||
|Microsoft 365 的基本移动性和安全性|是|否|否||
|POP 和 IMAP|是|是|是||
|SMTP|是|是|是||
|EWS 应用程序支持|是|是|是||
|**[语音消息服务](../../exchange-online-service-description/voice-message-services.md)**|**GCC**|**GCC 高**|**DoD**|**主要注意事项**|
|语音邮件|否|否|否|不支持将本地 IP-PBX 系统与 Exchange Online 统一消息集成。|
|语音邮件与第三方传真的集成|否|否|否|不支持将本地 IP-PBX 系统与 Exchange Online 统一消息集成。|
|第三方语音邮件互操作性|否|否|否|不支持将本地 IP-PBX 系统与 Exchange Online 统一消息集成。|
|Skype for Business 集成|是|是|是||
|**[高可用性和业务连续性](../../exchange-online-service-description/high-availability-and-business-continuity.md)**|**GCC**|**GCC 高**|**DoD**|**主要注意事项**|
|数据中心的邮箱复制|是|是|是||
|已删除邮箱的恢复|是|是|是||
|已删除邮件的恢复|是|是|是||
|单个项目恢复|是|是|是||
|**[互操作性、连接性和兼容性](../../exchange-online-service-description/interoperability-connectivity-and-compatibility.md)**|**GCC**|**GCC 高**|**DoD**|**主要注意事项**|
|OWA 和 Outlook 中的状态|是|是|是||
|SharePoint 互操作性|是|是|是||
|EWS 连接性支持|是|是|是||
|SMTP 中继支持|是|是|是||
|**[Exchange Online 设置和管理](../../exchange-online-service-description/exchange-online-setup-and-administration.md)**|**GCC**|**GCC 高**|**DoD**|**主要注意事项**|
|Microsoft Office 365 门户访问|是|是|否|报告对 DoD 不可用。 请参阅 Office <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features"></a> 365 美国政府版服务说明的平台功能部分，获取更新/当前可用性。|
|Microsoft 365 管理中心访问|是|是|否|报告对 DoD 不可用。 请参阅 Office <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features"></a> 365 美国政府版服务说明的平台功能部分，获取更新/当前可用性。|
|Exchange 管理中心访问|是|是|是||
|远程 Windows PowerShell 访问|是|是|是||
|移动设备的 ActiveSync 策略|是|是|是||
|使用情况报告|是|是|否|报告对 DoD 不可用。 请参阅 Office <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features"></a> 365 美国政府版服务说明的平台功能部分，获取更新/当前可用性。|
|**[扩展服务 - 自定义、外接程序和资源](../../exchange-online-service-description/exchange-online-service-description.md)**|**GCC**|**GCC 高**|**DoD**|**主要注意事项**|
|Outlook 加载项和 Outlook MAPI|是|是|是|只有一些 OWA 和 Outlook 外接程序在 GCC High 和 DoD 中可用。 请参阅 [本文中的 Outlook 外接程序Outlook Web App](#add-insin-outlook-and-outlook-web-app) 外接程序。|

## <a name="feature-nuances-within-gcc-high-and-dod-environments"></a>GCC High 和 DoD 环境中的功能细微差别

### <a name="connectivity-with-third-party-services"></a>第三方服务连接  

GCC High 和 DoD 环境都是需要明确批准和配置出站连接的受限环境。 此外，Microsoft 无法容纳允许从这些环境出站访问商业云服务 (商业 Office 365、Google GSuite、Amazon Web Services 等) 。

由于这些限制，通常不支持依赖 GCC High/DoD 环境这种出站连接的功能，包括：

- 已连接帐户 - 用户无法 (Google、POP/IMAP 等帐户添加/同步) 。

- 支持第三方文件存储提供程序 - 只有 *GCC High/DoD* 中的用户的 OneDrive for Business 帐户可以从各种 Outlook 客户端中访问，以便附加/共享文件。 不能添加 Dropbox、Box (Google Drive) 第三方存储帐户。

- 与社交网络（如 Facebook 或 LinkedIn）的连接。

### <a name="azure-active-directory-b2b-collaboration"></a>Azure Active Directory B2B 协作

Azure Active Directory B2B 协作当前仅在 Azure 美国政府云中且均支持 B2B 协作的组织之间受支持

此外，GCC High 和 DoD 环境中不支持作为 Office 365 组中来宾的 B2B 用户。 

有关详细信息和最新更新，请参阅 Azure [政府安全 + 标识](/azure/azure-government/documentation-government-services-securityandidentity)。

### <a name="office-365-message-encryption-behavior-across-gcc-highdod-boundary"></a>跨 GCC 高/DoD 边界的 Office 365 邮件加密行为

如果计划在 GCC High 环境中使用 Office 365 邮件加密，请注意以下有关收件人体验的独特特征：  

- 从 GCC High 或 DoD 向相同环境中收件人发送加密电子邮件时：
    
    - 发件人可以手动加密 Outlook for PC 和 Mac 以及 Outlook 网页中的电子邮件，或者组织可以设置策略以使用 Exchange 邮件流规则加密电子邮件。
    
    - GCC High/DoD 内的收件人在 Outlook for PC 和 Mac 以及 Outlook 网页版中与所有其他 Office 365 用户具有相同的内联阅读体验。

<!-- end list -->

- 从 GCC High 或 DoD 向该环境外部的收件人发送加密 (包括 GCC 和商业) ：
    
    - GCC High/DoD 内的发件人可以在 GCC High/DoD 边界外发送加密电子邮件。
    
    - GCC High/DoD 之外的所有收件人（包括商业 Office 365 用户、Outlook.com 用户和其他电子邮件提供商的其他用户）将收到包装邮件。 此包装邮件将收件人重定向到收件人可在其中阅读和回复邮件的 OME 门户。

有关详细信息和最新更新，请参阅 [比较 OME 的版本](/microsoft-365/compliance/ome-version-comparison)。

### <a name="freebusy-federation"></a>忙/闲联盟

联合共享（包括忙/闲信息）目前受到 GCC High 和 DoD 环境中的几个重要限制。

在 GCC High 环境中：

- GCC (High 内的租户之间) Exchange 2013 或更高版本的混合共存支持包括双向忙/闲共享 (在内的联合身份验证信任) 。

- GCC High 和 GCC 或 Office 365 商业版中的租户之间不支持联合共享。 目前不允许从 GCC High 环境到商业云 (包括 GCC 和 Office 365 商业) 的出站连接。 因此，GCC High 用户无法向 GCC/商业发送所需的出站请求来访问共享日历信息。

在 DoD 环境中：

  - 目前 (DoD) 租户之间支持联盟信任关系，包括忙/闲共享) 。 DoD 租户与 GCC 或商业租户之间不支持它。

### <a name="client-configuration"></a>客户端配置

部署和配置 Office 专业增强版（包括 Outlook (）) 。 有关这些步骤的详细说明，请参阅在 GCC High 或 DoD 环境中部署 [Microsoft 365](/deployoffice/deploy-microsoft-365-apps-gcc-high-dod)企业应用版的指导。

Outlook for iOS 和 Outlook for Android 还可用于 GCC High 和 DoD 环境。 若要详细了解这些环境中的功能限制和管理，请参阅在政府社区云中使用 Outlook for iOS 和[Outlook for Android。](/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud)

### <a name="add-ins-in-outlook-and-outlook-web-app"></a>Outlook 和外接程序中的Outlook Web App  

只有一些 OWA 和 Outlook 外接程序在 GCC High 和 DoD 中可用。 My Templates and Suggested Meetings are available and expected to function. 仅支持五个默认 OWA 加载项。 可以集成第三方应用程序，但是，GCC High 或 DoD 的 Microsoft 合规性承诺未涵盖这些集成。 在为组织配置加载项之前，客户应熟悉第三方数据处理做法和合规性承诺。

## <a name="feature-nuances-within-gcc-environments-for-microsoft-to-do"></a>Microsoft To Do 的 GCC 环境中的功能细微差别

| 功能 | 说明 | WW | GCC 中的可用性 |
|:-----|:-----|:-----|:-----|
|支持的平台|Web、Android、iOS、Mac、Windows|全部|仅 Web|
|M365 中心支持|与 Outlook、Teams、Planner 集成|全部|Outlook、Planner (Teams 可用于 Teams 任务应用) |
|Wunderlist 迁移|允许 wunderlist 用户将数据迁移到 Web 上的"要执行"操作|是|否|
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