---
title: Exchange Online for 美国政府环境
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 本文概述了美国政府云和商业云之间的功能差异，如 Exchange Online 服务说明中所示。
ms.openlocfilehash: b2ea792f6a205cbe6c9031c924a22e7f6d1d3030
ms.sourcegitcommit: 1a212a9f9c8d28090bc0b7c6e20e76d1353dad2e
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/13/2020
ms.locfileid: "44213694"
---
# <a name="exchange-online-for-us-government-environments"></a>Exchange Online for 美国政府环境

本文概述了美国政府云和商业云之间的功能差异，如 [Exchange Online 服务说明](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-service-description)中所示。 Exchange Online 适用于政府社区云（GCC）、GCC （gcc）和国防部（DoD）环境。

有关政府云（包括资格和购买）的详细信息，请参阅 [Microsoft 365 政府-如何购买](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy)。 若要比较 Office 365 政府版计划，请参阅 [office 365 政府版计划](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)。

若要了解管理网络连接时所需的终结点，请参阅 [office 365 美国政府版高终结点](https://docs.microsoft.com/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business)   或 [Office 365 美国政府 DoD 终结点](https://docs.microsoft.com/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)。

除了享受 Office 365 的特性和功能外，组织还可以受益于美国政府云环境所特有的以下功能：

- 您的组织的客户内容在商业 Office 365 服务中的客户内容从逻辑上分离。

- 您组织的客户内容存储在美国的 rest 中。

- 对组织的客户内容的访问权限只限于屏蔽的 Microsoft 员工。

- 政府云环境符合美国公共事业部门客户经常需要的认证和资格鉴定。

我们的一般意图是将所有 Exchange 商业版功能和功能传递给政府云环境。 也就是说，有些功能因政府云客户的要求而不可用。 其他功能将进入政府环境，但尚不可用。 请参阅以下各节，了解政府云环境中的功能可用性。

## <a name="exchange-online-features"></a>Exchange Online 功能

下表概述了在 GCC、GCC 高和 DoD 环境中是否提供了指定的 Exchange Online 功能。 如果有关于支持声明（或缺少）的详细说明，则提供其他上下文。

|**功能区**|**GCC**|**GCC 高**|**DoD**|**关键注意事项**|
|:-----|:-----|:-----|:-----|:-----|
|**[规划和部署](../../exchange-online-service-description/planning-and-deployment.md)**|||||
|支持的混合部署|是|是|是|若要与本地 Exchange Server 共存，Microsoft 需要安装至少一个 Exchange Server 2013 客户端访问服务器（或 Exchange Server 2016）。 不支持 Exchange Server 2010 及更早版本。|
|支持的 IMAP 迁移|是|是|是||
|支持的直接转换迁移|是|是|是||
|支持的暂存迁移|是|是|是|GSuite 不支持针对 GCC 高和 DoD 的迁移。 有关详细信息，请参阅 <a href="https://docs.microsoft.com/exchange/mailbox-migration/perform-g-suite-migration">执行 GSuite 迁移</a>。|
|**[权限](../../exchange-online-service-description/permissions.md)**|**GCC**|**GCC 高**|**DoD**|**关键注意事项**|
|基于角色的权限|是|是|是||
|角色组|是|是|是||
|角色分配策略|是|是|是||
|**[邮件策略和合规性](../../exchange-online-service-description/message-policy-and-compliance.md)**|**GCC**|**GCC 高**|**DoD**|**关键注意事项**|
|存档基于 Exchange Online 的邮箱|是|是|是||
|内部部署邮箱的基于云的存档|是|是|是||
|Messaging Records Management (MRM) |是|是|是||
|手动保留策略、标签和标记 |是|是|是||
|静态状态时的数据加密 (BitLocker)|是|是|是||
|使用 Azure 信息保护的 IRM|是|是|是|有关在 GCC 高和 DoD 中 AIP 限制的详细信息，请参阅<a href="https://docs.microsoft.com/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description">Azure 信息保护 Premium 政府服务说明</a>。<br><br>不包括 G1/F3 中的 Azure 信息保护，但可以将其作为单独的附加项购买，并启用受支持的信息权限管理（IRM）功能。 某些 Azure 信息保护功能需要订阅 Office 365 专业增强版，该订阅不包含在 Office 365 政府 G1 或 Office 365 政府 F3 中。|
|使用 Windows Server AD RMS 的 IRM|是|是|是|Windows Server AD RMS 是一台本地服务器，必须单独购买并管理，才能启用支持的 IRM 功能。|
|Office 365 邮件加密|是|是|是|请参阅本文中各项目的[office 365 邮件加密行为](#office-365-message-encryptionbehavior-across-gcc-highdod-boundary)和在 gcc 高<a href="https://docs.microsoft.com/microsoft-365/compliance/ome-version-comparison?view=o365-worldwide#unique-characteristics-of-office-365-message-encryption-in-a-gcc-high-deployment">部署中的 office 365 邮件加密的独特特征</a>，这是在在 gcc 高/DoD 和非 GCC 的高/dod 用户之间发送邮件时，对 office 365 邮件加密的各种行为的细微差别。|
|客户密钥|是|是|是|需要 G5 服务计划。|
|S/MIME|是|是|是||
|就地保留和诉讼保留|是|是|是|需要 G3 或 G5 服务计划。|
|就地电子数据展示|是|是|是||
|邮件流规则|是|是|是||
|数据丢失预防|是|是|是|需要 G3 或 G5 服务计划。|
|日记功能 |是|是|是||
|**[反垃圾邮件和反恶意软件保护](../../exchange-online-service-description/anti-spam-and-anti-malware-protection.md)**|**GCC**|**GCC 高**|**DoD**|**关键注意事项**|
|内置反垃圾邮件保护|是|是|是||
|自定义反垃圾邮件策略|是|是|是||
|内置反恶意软件保护|是|是|是||
|自定义反恶意软件策略|是|是|是||
|隔离 - 管理员管理|是|是|是||
|隔离 - 最终用户自我管理|是|是|是||
|高级强大的威胁保护|是|是|是|需要 G5 服务计划（或购买加载项）。<br><br>在 GCC 高和 DoD 中，用户和域模拟和欺骗情报的反网络钓鱼尚不可用。|
|**[邮件流](../../exchange-online-service-description/mail-flow.md)**|**GCC**|**GCC 高**|**DoD**|**关键注意事项**|
|出站邮件的自定义路由|是|是|是||
|与受信任合作伙伴的安全邮件|是|是|是||
|有条件的邮件路由|是|是|是||
|向入站安全列表添加合作伙伴|是|是|是||
|混合电子邮件路由|是|是|是||
|**[收件人](../../exchange-online-service-description/recipients.md)**|**GCC**|**GCC 高**|**DoD**|**关键注意事项**|
|容量报警|是|是|是||
|混乱邮件|是|是|是||
|MailTips|是|是|是||
|委托访问|是|是|是||
|收件箱规则|是|是|是||
|已连接帐户|可访问|否|否|由于对第三方服务的出站连接受到限制，因此在 GCC High 或 DoD 中不支持此功能。 有关受影响的功能的详细信息，请参阅本文中[与第三方服务的连接](#connectivity-with-third-party-services)。|
|非活动邮箱|是|是|是|需要 G3 或 G5 服务计划。|
|脱机通讯簿|是|是|是||
|通讯簿策略|是|是|是||
|分层通讯簿|是|是|是||
|地址列表和全局地址列表|是|是|是||
|Office 365 组|是|是|是|在 GCC 高和 DoD 环境中，不支持对 Office 365 组的来宾访问。 有关详细信息，请参阅<a href="https://docs.microsoft.com/azure/azure-government/documentation-government-services-securityandidentity">Azure 政府安全性 + Identity</a>。|
|通讯组|是|是|是||
|外部联系人（全局）|是|是|是|在 GCC 高和 DoD 环境中遵守组织关系的协作限制。 |
|社交网络的联系人链接|可访问|否|否|在 GCC High 或 DoD 中不支持此功能。|
|资源邮箱|是|是|是||
|会议室管理|是|是|是||
|“外出”回复|是|是|是||
|Internet 日历共享|可访问|否|否|在 GCC 高版中，Internet 日历发布/共享适用于由 GCC 高级用户共享的日历的入站连接，但不适用于将出站连接到在 GCC 的外部的共享日历的 GCC 高级用户。<br><br>在 DoD –由于对该环境中的入站/出站连接允许列表的要求，不支持 Internet 日历共享。|
|**[报告功能和疑难解答工具](../../exchange-online-service-description/reporting-features-and-troubleshooting-tools.md)**|**GCC**|**GCC 高**|**DoD**|**关键注意事项**|
|Microsoft 365 管理中心报告|是|可访问|否|报表不可用于 DoD。 有关更新/当前可用性的 Office 365 美国政府版服务说明，请参阅 "<a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">平台功能</a>" 部分。|
|Web 服务报告|是|可访问|否|报表不可用于 DoD。 有关更新/当前可用性的 Office 365 美国政府版服务说明，请参阅 "<a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">平台功能</a>" 部分。|
|邮件跟踪|是|是|是||
|审核报告|是|可访问|否|报表不可用于 DoD。 有关更新/当前可用性的 Office 365 美国政府版服务说明，请参阅 "<a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">平台功能</a>" 部分。|
|统一消息报告|可访问|否|否||
|**[共享和协作](../../exchange-online-service-description/sharing-and-collaboration.md)**|**GCC**|**GCC 高**|**DoD**|**关键注意事项**|
|联合共享（包括日历发布）|是|是|是|在 GCC 高和 DoD 中都存在限制。 请参阅本文中的[忙/闲联盟](#freebusy-federation)。|
|网站邮箱|是|是|是||
|公用文件夹|是|是|是||
|**[客户端和移动设备](../../exchange-online-service-description/clients-and-mobile-devices.md)**|**GCC**|**GCC 高**|**DoD**|**关键注意事项**|
|Outlook for Windows|是|是|是|若要满足 GCC 的高和 DoD 合规性要求，必须至少运行版本为1803的 Office 365 专业增强版。 "Office 365 专业增强版" 不包含 G1 或 F3。|
|Outlook 网页版|是|是|是||
|Outlook for Mac|是|是|是|若要满足 GCC 的高和 DoD 合规性要求，必须至少运行版本为1803的 Office 365 专业增强版。 "Office 365 专业增强版" 不包含 G1 或 F3。|
|Outlook for iOS 和 Outlook for Android|是|是|是||
|Exchange ActiveSync|是|是|是||
|Office 365 移动设备管理|是|是|是||
|POP 和 IMAP|是|是|是||
|SMTP|是|是|是||
|EWS 应用程序支持|是|是|是||
|**[语音消息服务](../../exchange-online-service-description/voice-message-services.md)**|**GCC**|**GCC 高**|**DoD**|**关键注意事项**|
|语音邮件|否|否|否|不支持将本地 IP-PBX 系统与 Exchange Online 统一消息集成。|
|语音邮件与第三方传真的集成|否|否|否|不支持将本地 IP-PBX 系统与 Exchange Online 统一消息集成。|
|第三方语音邮件互操作性|否|否|否|不支持将本地 IP-PBX 系统与 Exchange Online 统一消息集成。|
|Skype for Business 集成|是|是|是||
|**[高可用性和业务连续性](../../exchange-online-service-description/high-availability-and-business-continuity.md)**|**GCC**|**GCC 高**|**DoD**|**关键注意事项**|
|数据中心中的邮箱复制|是|是|是||
|已删除邮箱的恢复|是|是|是||
|已删除邮件的恢复|是|是|是||
|单个项目恢复|是|是|是||
|**[互操作性、连接性和兼容性](../../exchange-online-service-description/interoperability-connectivity-and-compatibility.md)**|**GCC**|**GCC 高**|**DoD**|**关键注意事项**|
|在 OWA 和 Outlook 中的状态|是|是|是||
|SharePoint 互操作性|是|是|是||
|EWS 连接性支持|是|是|是||
|SMTP 中继支持|是|是|是||
|**[Exchange Online 设置和管理](../../exchange-online-service-description/exchange-online-setup-and-administration.md)**|**GCC**|**GCC 高**|**DoD**|**关键注意事项**|
|Microsoft Office 365 门户访问|是|可访问|否|报表不可用于 DoD。 有关更新/当前可用性的 Office 365 美国政府版服务说明，请参阅 "<a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">平台功能</a>" 部分。|
|Microsoft 365 管理中心访问|是|可访问|否|报表不可用于 DoD。 有关更新/当前可用性的 Office 365 美国政府版服务说明，请参阅 "<a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">平台功能</a>" 部分。|
|Exchange 管理中心访问|是|是|是||
|远程 Windows PowerShell 访问|是|是|是||
|移动设备的 ActiveSync 策略|是|是|是||
|使用情况报告|是|可访问|否|报表不可用于 DoD。 有关更新/当前可用性的 Office 365 美国政府版服务说明，请参阅 "<a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">平台功能</a>" 部分。|
|**[扩展服务 - 自定义、外接程序和资源](../../exchange-online-service-description/exchange-online-service-description.md)**|**GCC**|**GCC 高**|**DoD**|**关键注意事项**|
|Outlook 加载项和 Outlook MAPI|是|是|是|在 GCC 高和 DoD 中，仅有一些 OWA 和 Outlook 外接程序可用。 请参阅本文中的[outlook 和 Outlook Web App 中的外接](#add-insin-outlook-and-outlook-web-app)程序。|

## <a name="feature-nuances-within-gcc-high-and-dod-environment"></a>GCC 高和 DoD 环境中的功能细微差别

### <a name="connectivity-with-third-party-services"></a>与第三方服务的连接  

GCC 高级和 DoD 环境都是受限制的环境，需要明确批准和配置出站连接。 此外，Microsoft 无法适应允许从这些环境到商业云服务的出站访问（商业 Office 365、Google GSuite、Amazon Web 服务等）的请求。     

由于这些限制，通常不支持依赖于 GCC 高/DoD 环境的此出站连接的功能，包括： 

- 已连接帐户 &mdash; 用户无法添加/同步帐户（Google、POP/IMAP 等）。 

- 对第三方文件存储提供程序的支持 &mdash; 只有用户的 OneDrive for business *within GCC High/DoD*帐户   可以从各种 Outlook 客户端中进行访问，以附加/共享文件。 无法添加第三方存储帐户（收存箱、Box、Google Drive）。 

- 与社交网络（如 Facebook 或 LinkedIn）的连接。 

### <a name="azure-active-directoryb2b-collaboration"></a>Azure Active Directory B2B 协作 

Azure Active Directory B2B 协作目前仅在受 Azure 美国政府云共同支持 B2B 协作的组织之间提供支持

此外，在 GCC 高和 DoD 环境中，不支持将 B2B 用户用作 Office 365 组中的来宾。 

有关更多详细信息和最新更新，请参阅[Azure 政府安全性 + Identity](https://docs.microsoft.com/azure/azure-government/documentation-government-services-securityandidentity)。 

### <a name="office-365-message-encryptionbehavior-across-gcc-highdod-boundary"></a>跨 GCC 高/DoD 界限的 Office 365 邮件加密行为 

如果要在 GCC 高环境中使用 Office 365 邮件加密，请注意有关收件人体验的这些独特特征：  

- 将加密的电子邮件从 GCC High 或 DoD 发送到同一环境中的收件人时：
    
    - 发件人可以在 Outlook 中为电脑和 Mac 和 Outlook 网页版手动加密电子邮件，或者组织可以设置策略以使用 Exchange 邮件流规则对电子邮件进行加密。 
    
    - 在 GCC 中，高/DoD 的收件人在 Outlook 中接收与所有其他 Office 365 用户相同的嵌入式阅读体验（适用于 PC 和 Mac）和 Outlook 网页版。 

<!-- end list -->

- 将加密的电子邮件从 GCC 高或 DoD 发送到该环境之外的收件人（包括 GCC 和商业版）时：
    
    - 在 GCC 高/DoD 内的发件人可以在 GCC 高/DoD 界限之外发送加密电子邮件。 
    
    - 所有收件人都在拥有 GCC 高/DoD 的范围内，包括商业 Office 365 用户、Outlook.com 用户和其他电子邮件提供商的其他用户，接收到包装邮件。 此包装邮件将收件人重定向到 OME 门户，收件人可在其中读取和回复邮件。 

有关更多详细信息和最新更新，请参阅[比较版本的 OME](https://docs.microsoft.com/microsoft-365/compliance/ome-version-comparison?view=o365-worldwide)。

### <a name="freebusy-federation"></a>闲/忙联盟

联合共享（包括闲/忙信息）目前受 GCC 的高和 DoD 环境中的几项重要限制。

在 GCC 高环境中：

- 在 GCC 高版本和通过混合共存（Exchange 2013 或更高版本）之间租户之间支持联合身份验证信任（包括双向忙/闲共享）。

- 在 GCC High 和 GCC 或 Office 365 商业版中的租户之间不支持联合共享。 此时不允许将来自 GCC 高环境的出站连接到商业云（包括 GCC 和 Office 365 商业版）。 因此，GCC 高用户无法向 GCC/商业版发出所需的出站请求来访问共享的日历信息。

在 DoD 环境中：

  - 目前仅支持在 DoD 环境中的租户之间进行联合身份验证信任（包括忙/闲共享）。 在 DoD 租户和 GCC 或商业租户之间不支持此方法。

### <a name="client-configuration"></a>客户端配置 

部署和配置 Office 专业增强版（包括 Outlook）涉及的其他步骤。 有关这些步骤的详细说明，请参阅[在 GCC 高或 DoD 环境中部署适用于企业的 Microsoft 365 应用程序指南 ](https://docs.microsoft.com/deployoffice/deploy-microsoft-365-apps-gcc-high-dod)。

适用于 iOS 和 Android 的 Outlook for iOS 和适用于 GCC 的高和 DoD 环境。 若要了解有关这些环境中的功能限制和管理的详细信息，请参阅[在政府社区云中使用 Outlook For iOS 和 Outlook For Android](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud)。

### <a name="add-insin-outlook-and-outlook-web-app"></a>Outlook 和 Outlook Web App 中的外接程序  

在 GCC 高和 DoD 中，仅有一些 OWA 和 Outlook 外接程序可用。 我的模板和建议的会议可用且应正常运行。 仅支持五个默认 OWA 外接程序。 可以与第三方应用程序集成，但是，对于 GCC 高或 DoD，Microsoft 合规性承诺不会涵盖这些集成。 在为组织配置加载项之前，客户应熟悉第三方数据处理实践和合规性承诺。
