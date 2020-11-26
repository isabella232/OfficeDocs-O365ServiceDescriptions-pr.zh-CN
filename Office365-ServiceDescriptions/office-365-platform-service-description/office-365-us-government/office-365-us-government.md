---
title: Office 365 美国政府版
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 3f482abc-993f-41bf-8754-0f489a7e4861
description: 根据美国公共事业部门的独特和不断发展的要求，Microsoft 已创建 Office 365 美国政府版计划 (或 Office 365 政府) 。 本文概述了特定于 Office 365 政府美国环境的功能。
ms.openlocfilehash: 583d901990feca273421f6c66a5f611cd3591200
ms.sourcegitcommit: ace6cd97a0d3823959e1629929be77489f79b520
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/25/2020
ms.locfileid: "49411611"
---
# <a name="office-365-government"></a>Office 365 政府版

> [!IMPORTANT]
> 由于 coronavirus (COVID-19) pandemic，Microsoft 团队在在线通话和音频/视频会议方面遇到了极大的峰值。<br/>
>
>为了响应更空前的呼叫增长，并确保连续性和可用性，Microsoft 允许 Microsoft 团队拥有的音频/视频服务器利用我们的商业数据中心中的处理能力以及我们的政府数据中心。<br/>
>
>这些音频/视频服务器驻留在美国的 Microsoft Azure FedRAMP 高资格鉴定边界服务器中，并且不存储任何客户内容。 但是，这些服务器正在处理通话和会议的音频和视频，并在此中间期间在商业员工下运行。<br/>
>
>合格的屏蔽人员通过查看这些服务器的任何交互式登录项来监视这些服务器，以获取客户数据的潜在访问权限。 合格的人员可满足对客户内容的访问权限的 GCC 要求。 有关筛选要求的详细信息，请参阅 [GCC 服务说明](gcc.md)。<br/>
>
>感谢你的支持，因为我们采取措施以确保我们的服务在这些特别时间内保持可用和可靠。<br/>

为了响应美国公共事业部门的独特和不断发展的需求，Microsoft 已创建 Office 365 政府计划 (或 Office 365 政府) 。 此服务说明提供了特定于 Office 365 政府美国环境的功能的概述。 我们建议您阅读此服务说明及其他 [Microsoft 365 和 Office 365 服务说明](../../office-365-service-descriptions-technet-library.md)。

## <a name="how-to-use-this-service-description"></a>如何使用本服务说明

Office 365 政府服务说明旨在用作常规 Office 365 服务说明的覆盖。 它定义了唯一承诺以及与 Office 365 企业版产品的差异。

## <a name="about-office-365-government-environments"></a>关于 Office 365 政府环境

Office 365 政府版计划为每月订阅，可以授权给无数用户。

- **Office 365 GCC** 环境为云服务（包括 FedRAMP 高）的联邦要求和 CJI 和 FTI 税信息系统 (和 FTI data types) 提供了合规性要求。

- **Office 365 GCC 高和 DoD** 环境符合国防部安全要求准则、防御联邦收购规章补充 (DFARS) ，以及 arm 规章 (ITAR) 中的国际流量。

除了 Office 365 的特性和功能之外，使用 Office 365 政府的组织还可受益于 Office 365 政府独有的以下功能：

- 您组织的客户内容与 Microsoft 商业 Office 365 服务中的客户内容在逻辑上是隔离的。

- 您组织的客户内容存储在美国境内。

- 对组织的客户内容的访问权限只限于屏蔽的 Microsoft 员工。

- Office 365 政府符合美国公共事业部门客户所需的认证和资格鉴定。

## <a name="customer-eligibility"></a>客户资格

Office 365 政府可用于 (1) 美国联邦、州、local、部落和 territorial 政府实体，以及 (2) 处理受政府法规和要求约束的数据的其他实体，以及 Office 365 政府在哪种情况下适用于符合这些要求的使用情况（受资格验证）。 Microsoft 的资格验证包括确认处理的是受符合国际武器贸易条例 (ITAR) 约束的数据，还是受 FBI 的刑事司法信息服务 (CJIS) 政策约束的执法数据，亦或是其他受政府监管或控制的数据。 对于 ITAR 数据，资格验证可能需要提供美国国务院注册证明；对于数据处理的具体要求，可能需要提供政府机构资助证明。 Office 365 DoD 环境专用于美国国防部的专属使用。

虽然符合各 Office 365 政府产品的资格标准，但 Microsoft 仅同意 DFARS 和 ITAR 合同语言 for GCC 的高环境。

包含有关 Office 365 政府资格的问题的实体应咨询其帐户团队。

续订了客户的 Office 365 政府合同后，需要重新验证资格。

## <a name="customer-content-located-within-the-united-states"></a>位于美国境内的客户内容

Office 365 政府服务是从实际位于美国的数据中心提供的。 下面的客户内容存储在仅物理上位于美国的数据中心中的其余部分：

- Exchange Online 邮箱内容 (电子邮件正文、日历条目和电子邮件附件的内容) 

- SharePoint Online 网站内容和该网站中存储的文件

- Skype for Business 存档的对话、已上载的文档和白板会话

- Microsoft 团队持久聊天线索

> [!NOTE]
> 对于一般用途，Skype for Business 不存储客户内容，但如果存储，内容会存储在美国的数据中心内。

如果你的用户在美国中使用 Office (以前称为 Office Web Apps) 或者采用 Active Directory 联合身份验证服务 (AD FS) 2.0 并设置策略以帮助确保用户通过单一登录连接到服务，则在 Office 中临时缓存的任何客户内容都将位于美国中。

## <a name="office-365-government-and-third-party-services"></a>Office 365 政府和第三方服务

Office 365 提供了将第三方应用程序集成到 SharePoint Online 网站、Skype for Business、Office (相关应用程序（如 Word、Excel、PowerPoint 和 Outlook) 和 Outlook Web App）365中的 Office 应用程序的功能。 此外，Office 365 还支持与第三方服务提供商集成。 这些第三方应用程序和服务可能参与存储、传输和处理组织在 Office 365 基础结构外部的第三方系统上的客户数据，因此未涵盖在 Office 365 合规性和数据保护协议中。 我们建议您在为组织评估这些服务的相应使用情况时，查看第三方提供的隐私和合规性声明。

## <a name="restricted-data-access-by-administrators"></a>管理员受限数据访问

Microsoft 管理员对 Office 365 政府客户内容的访问权限仅限于被筛选的人员。 有关筛选级别的详细信息，请参阅每个各自的环境的 "服务说明" 页面 (GCC 或 GCC 高和 DoD) 。

## <a name="fasttrack-center-onboarding-assistance"></a>FastTrack Center 载入帮助

使用适用于 Office 365<sup>1</sup>的 FastTrack 中心权益，您可以与 FastTrack 专家远程合作，让您的 Office 365 环境准备就绪，并在您的组织内规划部署和使用情况。 FastTrack 流程提供了载入和用户采用服务。

载入包括：

- 核心载入-这些是租户配置所需的任务，以及与 Azure Active Directory (Azure AD) （如果需要）的集成。 核心载入还为载入其他符合条件的服务提供了基线。

- 服务载入和迁移-服务载入任务可在租户中启用方案。 数据迁移 (包括电子邮件和文件) 在 [数据迁移](https://aka.ms/whatcanmigrate)中介绍。<sup>2</sup>

用户采用服务由任务组成，这些任务为您提供指导，以确保您的用户了解符合条件的服务，并可以使用它们推动业务价值。 此协助与载入活动并行发生。

可在 [此处](https://aka.ms/whatistheprocess)找到有关 FastTrack 中心流程的特定信息。 有关接洽角色和责任的细分，请查看 [FastTrack 责任](https://aka.ms/whatdoesftcdo) 以及您的 [责任](https://aka.ms/whatdowedo)。

> <sup>1</sup> 您必须从 [符合条件的计划](https://aka.ms/whocanbenefit) 列表中至少购买50许可证，才能接收 FastTrack 服务。
<br/><sup>2</sup> 数据迁移服务可用于包含500或更多许可证的 Office 365 租户。

## <a name="data-migrations-performed-by-fasttrack"></a>FastTrack 执行的数据迁移

选择 [FastTrack](https://fasttrack.microsoft.com/) 迁移权益的客户将需要向管理其数据迁移的团队授予访问权限。 在为 Office 365 美国政府版的客户执行迁移之前，这些人员都是美国公民，并进行了以下背景检查。<br><br>

|后台筛选|GCC|GCC High 和 DoD|
|---|---|---|
|验证美国公民|是|是|
|就业历史记录检查|是|是|
|教育版验证|是|是|
| (SSN) 搜索的社会安全号码|是|是|
|犯罪历史记录检查 (7 年) |是|是|

## <a name="office-365-us-government-and-azure-government-expressroute"></a>Office 365 美国政府版和 Azure 政府 ExpressRoute

Office 365 美国政府版客户可以使用 Azure 政府 ExpressRoute 服务来私下连接到受支持的 Office 365 服务，而不是通过公共 internet 进行连接。

有关详细信息（如受支持的提供商、定价模型等），请查看 [Azure ExpressRoute 信息](https://go.microsoft.com/fwlink/?LinkID=798220&amp;clcid=0x409)。

有关 Office 365 支持 Azure ExpressRoute 的详细信息，请参阅 [Azure expressroute For office 365](https://go.microsoft.com/fwlink/?LinkID=798216&amp;clcid=0x409)

## <a name="system-requirements"></a>系统要求

有关 Office 365 美国政府版 计划的系统要求，请参阅 [office.com](https://go.microsoft.com/fwlink/?LinkID=626095&amp;clcid=0x409) 产品网站上的 [Office 的系统要求](https://go.microsoft.com/fwlink/?LinkID=509817&amp;clcid=0x409)。

## <a name="security-amp-compliance-center"></a>Security &amp; Compliance Center

有关安全 &amp; 合规性中心的信息以及指向其他信息和可用性的链接，请参阅 [安全 &amp; 合规中心](../../office-365-platform-service-description/office-365-securitycompliance-center.md)。

## <a name="service-availability-for-each-plan"></a>每个计划的服务可用性

每个 Office 365 计划都包括许多单个服务，例如 Exchange Online 和 SharePoint Online。下表显示了每个 Office 365 美国政府版 计划中可用的服务。<br><br>

|Office 365 服务|Office 365 政府版 G1|Office 365 政府版 G3|Office 365 政府版 G5|Office 365 政府 F3|
|---|---|---|---|---|
|Office 网页版|是|是|是|是|
|Microsoft 365 企业应用版|否|是|是|否|
|Exchange Online|是|是|是|是|
|Exchange Online Protection|是|是|是|是|
|SharePoint Online|是|是|是|是|
|OneDrive for Business|是|是|是|是|
|Skype for Business (Instant Messaging &amp; Presence)|是<sup>1</sup>|是|是|是<sup>1</sup>|
|语音电话系统、音频会议|否<sup>2</sup>|否<sup>2</sup>|是<sup>5</sup>|否|
|Power BI Pro|否<sup>2</sup>|否<sup>2</sup>|是|否<sup>2</sup>|
|Project Online|否<sup>2</sup>|否<sup>2</sup>|否<sup>2</sup>|否<sup>2</sup>|
|Visio 网页版|否<sup>6</sup>|否<sup>6</sup>|否<sup>6</sup>|否<sup>6</sup>|
|Yammer 企业版|否<sup>4</sup>|否<sup>4</sup>|否<sup>4</sup>|否<sup>4</sup>|

> <sup>1</sup> Skype For business Basic 适用于所有客户。 Skype for Business 桌面客户端是在本地安装的应用程序，为包含 Skype for Business Online 的 Office 365 计划提供状态、即时消息和会议功能。 适用于企业、G3 和 G5 的 Microsoft 365 应用程序包括完整的 Skype 应用程序，其中包括高级电话支持、存档和合规性功能等附加功能。 必须为每个用户分配 Skype for Business Online 许可证。
<br/><sup>2</sup> 不包括在内，但可以作为单独的附加项购买。 Project Online 包括 Project Online 桌面客户端作为订阅的一部分。
<br/> <sup>3</sup> 尚不可用于 GCC 高或 DoD 计划，但即将推出。
<br/><sup>4</sup> Yammer 企业不是 OFFICE 365 美国政府的一个组件，但可以免费获得，作为在 GCC 中为 Office 365 许可的每个用户提供的独立服务。 此优惠目前仅限于在企业协议和企业订阅协议下购买 Office 365 GCC 的客户。 Yammer 在 GCC High 或 DoD 中不可用。
<br/><sup>5</sup> 通话套餐是一个附加项。
<br/><sup>6</sup> 不包括在内，但可以作为单独的附加项购买。 Visio for web 将 Visio 桌面应用程序作为订阅的一部分包括在其中。

## <a name="platform-features"></a>平台功能

下表列出了Office 365 美国政府版 计划中所提供的平台功能和服务。<br><br>

|功能|Office 365 政府版 G1|Office 365 政府版 G3|Office 365 政府版 G5|Office 365 政府 F3|
|---|---|---|---|---|
|**Office 365 管理**|||||
|使用 Microsoft 365 管理中心管理 Office 365|是<sup>16</sup>|是<sup>16</sup>|是|是<sup>16</sup>|
|从 Office 365 中管理核心服务设置|是|是|是|是|
|使用 Windows PowerShell 管理 Office 365|是|是|是|是|
|使用 Azure 信息保护保护内容|否<sup>1</sup>|是<sup>15</sup>|是<sup>15</sup>|否<sup>1</sup>|
|**[Office 365 套件功能](../../office-365-platform-service-description/office-365-suite-features.md)**|**Office 365 政府版 G1**|**Office 365 政府版 G3**|**Office 365 政府版 G5**|**Office 365 政府 F3**|
|Microsoft Bookings|否|是<sup>21</sup>|是<sup>21</sup>|否|
|Microsoft 简报电子邮件|否|否|否|否|
|Microsoft Power Automate|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|Microsoft Forms|是|是|是<br/>|是</sup>|
|Microsoft Graph API|是|是|是|是|
|Microsoft MyAnalytics|否|否|是<sup>17</sup>|否|
|Microsoft Planner|是|是|是|是|
|Microsoft PowerApps|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|Microsoft StaffHub|否|否|否|否<br/>|
|Microsoft Stream|是<sup>9，15</sup>|是<sup>9，15</sup>|是<sup>9，15</sup>|是<sup>9、15、20</sup>|
|Microsoft Sway|否|否|否|否|
|Microsoft Teams|是|是|是|是|
|Office Delve|是<sup>17</sup>|是<sup>17</sup>|是|是<sup>17</sup>|
|Office 365 组|是|是|是|是|
|**[用户帐户管理](../../office-365-platform-service-description/user-account-management.md)**|**Office 365 政府版 G1**|**Office 365 政府版 G3**|**Office 365 政府版 G5**|**Office 365 政府 F3**|
|云身份|是|是|是|是|
|联合身份（单点登录）|是|是|是|是|
|多重身份验证|是|是|是|是|
|电话系数身份验证|是<sup>9</sup>|是<sup>9</sup>|是|是<sup>9</sup>|
|Office 365 桌面设置|是|是|是|是|
|使用 Office 365 管理用户|是|是|是|是|
|使用 .csv 文件批量上载|是<sup>9</sup>|是<sup>9</sup>|是|是<sup>9</sup>|
|目录同步工具|是|是|是|是|
|Exchange 简单（直接转换）迁移|是|是|是|是|
|通过使用 Office 365 删除帐户|是<sup>3</sup>|是<sup>3</sup>|是<sup>3</sup>|是<sup>3</sup>|
|管理员可以从 Office 365 中或通过使用 Windows PowerShell 重新设置用户密码|是<sup>4</sup>|是<sup>4</sup>|是<sup>4</sup>|是<sup>4</sup>|
|用户可以更改自己的密码|是<sup>5</sup>|是<sup>5</sup>|是<sup>5</sup>|是<sup>5</sup>|
|管理许可证|是<sup>7、8</sup>|是<sup>7、8</sup>|是<sup>7、8</sup>|是<sup>7、8</sup>|
|从 Office 365 管理安全组|是|是|是|是|
|多个管理员角色可用|是|是|是|是|
|允许合作伙伴为您管理 Office 365|是<sup>11</sup>|是<sup>11</sup>|是<sup>11</sup>|是<sup>11</sup>|
|Azure Active Directory 服务|是|是|是|是|
|**[域](../../office-365-platform-service-description/domains.md)**|**Office 365 政府版 G1**|**Office 365 政府版 G3**|**Office 365 政府版 G5**|**Office 365 政府 F3**|
|添加第二级自定义域，如 fourthcoffee.com|是|是|是|是|
|添加第三级自定义域，如 marketing.fourthcoffee.com是|是|是|是|是|
|添加多达 900 个自定义域|是|是|是|是|
|自定义域需要域所有权验证|是|是|是|是|
|**[服务运行状况和连续性](../../office-365-platform-service-description/service-health-and-continuity.md)**|**Office 365 政府版 G1**|**Office 365 政府版 G3**|**Office 365 政府版 G5**|**Office 365 政府 F3**|
|“服务运行状况”或“服务状态”页面中显示状态信息|是<sup>9，15</sup>|是<sup>9，15</sup>|是<sup>9，15</sup>|是<sup>9，15</sup>|
|Microsoft 365 管理中心仪表板中显示的单个警报的状态|是<sup>9，15</sup>|是<sup>9，15</sup>|是<sup>9，15</sup>|是<sup>9，15</sup>|
|是|是|是|是|是|
|**[报告](../../office-365-platform-service-description/reports.md)**|**Office 365 政府版 G1**|**Office 365 政府版 G3**|**Office 365 政府版 G5**|**Office 365 政府 F3**|
|活动邮箱和非活动邮箱|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|新邮箱和已删除的邮箱|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|新组和已删除的组|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|邮箱使用情况|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|邮箱连接类型|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|已发送和已接收邮件|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|主要发件人和收件人|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|垃圾邮件检测|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|恶意软件检测|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|邮件的主要恶意软件|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|邮件的规则匹配|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|邮件的主要规则匹配|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|邮件的主要 DLP 策略匹配|否|是<sup>15</sup>|是<sup>15</sup>|否|
|按邮件严重性显示的 DLP 策略匹配|否|是<sup>15</sup>|是<sup>15</sup>|否|
|邮件的 DLP 策略匹配、重写和误报|否|是<sup>15</sup>|是<sup>15</sup>|否|
|邮件的主要 DLP 规则匹配|否|是<sup>15</sup>|是<sup>15</sup>|否|
|IM 和音频会话|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|应用程序共享、Web 和电话拨入式会议|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|视频、应用程序共享和文件传输会话|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|IM 和音频/视频会议|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|可下载的邮件保护报告|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|使用的浏览器|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|使用的操作系统|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|使用 Microsoft 365 报告 web 服务创建自己的报告|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|**[服务更新](../../office-365-platform-service-description/service-updates.md)**|**Office 365 政府版 G1**|**Office 365 政府版 G3**|**Office 365 政府版 G5**|**Office 365 政府 F3**|
|向所有客户提供的定期更新|是|是|是|是|
|通知发送给 消息中心（当需要操作时）|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|针对某些服务更新的 Roadmap.office.com|无<sup>10、13</sup>|无<sup>10、13</sup>|无<sup>10、13</sup>|无<sup>10、13</sup>|
|启用目标版本的选项|是<sup>10</sup>|是<sup>10</sup>|是<sup>10</sup>|是<sup>10</sup>|
|**[帮助和培训](../../office-365-platform-service-description/help-and-training.md)**|**Office 365 政府版 G1**|**Office 365 政府版 G3**|**Office 365 政府版 G5**|**Office 365 政府 F3**|
|联机帮助|是|是|是|是|
|社区|是|是|是|是|
|其他自助资源|是|是|是|是|
|自学培训|是|是|是|是|
|**[网络](../../office-365-platform-service-description/networking.md)**|**Office 365 政府版 G1**|**Office 365 政府版 G3**|**Office 365 政府版 G5**|**Office 365 政府 F3**|
|IPv4 和 IPv6 协议|是|是|是|是|
|**信任**|**Office 365 政府版 G1**|**Office 365 政府版 G3**|**Office 365 政府版 G5**|**Office 365 政府 F3**|
|**[隐私、安全性和透明度](../../office-365-platform-service-description/privacy-security-and-transparency.md)**|||||
|高级数据治理|无<sup>12</sup>|无<sup>12</sup>|是|无<sup>12</sup>|
|云应用安全|无<sup>12、15、19</sup>|无<sup>12、15、19</sup>|是<sup>15、19</sup>|无<sup>12、15、19</sup>|
|高级威胁防护|无<sup>12、18</sup>|无<sup>12、18</sup>|是<sup>18</sup>|无<sup>12、18</sup>|
|客户密码箱|无<sup>12</sup>|无<sup>12</sup>|是|无<sup>12</sup>|
|高级电子数据展示|无<sup>12</sup>|无<sup>12</sup>|是|无<sup>12</sup>|
|安全分数<sup>14</sup>|是<sup>9，15</sup>|是<sup>9</sup>|是<sup>9，15</sup>|是<sup>9，15</sup>|
|Office 邮件加密|否|是|是|否|
|威胁智能|无<sup>12</sup>|无<sup>12</sup>|是|无<sup>12</sup>|
|**[合规性](https://docs.microsoft.com/microsoft-365/compliance/offering-home)**|||||
|SAS 70 / SSAE16 评估|是|是|是|是|
|ISO 27001 认证|是|是|是|是|
|欧盟模式条款|是|是|是|是|
|欧盟安全港|是|是|是|是|
|HIPAA 业务关联协议|是|是|是|是|
|FISMA 操作授权|是|是|是|是|
|Microsoft 数据处理协议|是|是|是|是|
|一级 PCI DSS|是|是|是|是|
|PCI 监管的 PAN 数据|否|否|否|否|
|**[服务连续性](../../office-365-platform-service-description/service-health-and-continuity.md)**|是|是|是|是|
|**[BlackBerry](../../office-365-platform-service-description/blackberry.md)**|**Office 365 政府版 G1**|**Office 365 政府版 G3**|**Office 365 政府版 G5**|**Office 365 政府 F3**|
|是|否<sup>2</sup>|否<sup>2</sup>|否<sup>2</sup>|否<sup>2</sup>|
|**[合作伙伴](../../office-365-platform-service-description/partners.md)**|||||
|是|无<sup>11</sup>|无<sup>11</sup>|无<sup>11</sup>|无<sup>11</sup>|
|是|无<sup>11</sup>|无<sup>11</sup>|无<sup>11</sup>|无<sup>11</sup>|
|**[服务级别协议](../../office-365-platform-service-description/service-level-agreement.md)**|是|是|是|是|
|**[产品使用权限](../../office-365-platform-service-description/product-use-rights.md)**|是|是|是|是|

> <sup>1</sup> Azure 信息保护不包括在内，但可以作为单独的附加项购买，并将启用受支持的信息权限管理 (IRM) 功能。 某些 Azure 信息保护功能需要订阅适用于企业的 Microsoft 365 应用程序，该订阅不包含在 Office 365 政府 G1 或 Office 365 政府 F3 中。 >
<br/><sup>2</sup> 现有的 BBCS 和 BIS 客户可继续使用服务。 不接受新客户。
<br/><sup>3</sup> 如果使用目录同步，您必须使用 Active Directory（而不是 Office 365 门户）或使用 Windows PowerShell 的 Azure Active Directory 模块来删除帐户或更改密码。
<br/><sup>4</sup> 如果使用密码同步，用户必须更改本地 Active Directory 中的密码。
<br/><sup>5</sup> 若要了解如何为用户设置自助服务密码管理策略，请参阅 [管理 Azure AD 中的密码](https://azure.microsoft.com/documentation/articles/active-directory-manage-passwords/)。
<br/><sup>6</sup> Office 365 只能有一个公共网站，除非你已升级旧版 Office 365。 如果已升级，可以拥有两个公共网站，但其中只有一个能够使用自定义域名托管。 若要详细了解如何处理商业版订阅的两个网站，请参阅 [处理两个 Office 365 公共网站](https://go.microsoft.com/fwlink/p/?LinkID=271589)。 如果有其他订阅，请参阅[在 Office 365 中了解合作伙伴网站托管和公共网站](https://go.microsoft.com/fwlink/p/?LinkID=325009)，详细了解公共网站。
<br/><sup>7</sup> 减少按费用折扣购买的席位可能会导致提前终止费用。 这不适用于按月支付的订阅。
<br/><sup>8</sup> 以下计划不支持来自 Microsoft 365 管理中心的许可证座位更改： Office 365 政府 G1、Office 365 政府 G3、Office 365 政府 F3。
<br/><sup>9</sup> 在 GCC 高版中尚不可用，但即将推出。
<br/><sup>10</sup> 个用于 Office 365 政府 G1、G3 和 F3，目标版本和 office 365 For business 路线图适用;但是，由于 [合规性要求](https://www.microsoft.com/trust-center)，特定服务更新可能会存在一些差异或延迟。
<br/><sup>11</sup> 尚不可用于 Office 365 政府产品，但即将推出。
<br/><sup>12</sup> 不包括在内，但可以作为单独的附加项在 GCC 中购买。
<br/><sup>13</sup> 不支持 Office 365 政府版产品。
<br/><sup>14</sup> 可在中找到 [https://securescore.office.com](https://securescore.office.com) 。 必须拥有管理员权限。 有关详细信息，请参阅 [简介 Office 365 安全分数](https://docs.microsoft.com/microsoft-365/security/mtp/microsoft-secure-score)。
).
<br/><sup>15</sup> 在 DoD 环境中尚不可用，但即将推出。
<br/><sup>16</sup> 管理中心不包括 DOD 或 GCC 高级环境中的使用情况分析。
<br/><sup>17</sup> 不支持 GCC 高或 DoD 环境。
<br/><sup>18</sup> 在 GCC 高和 DoD 中尚不提供用于用户和域模拟和欺骗情报的反网络钓鱼。
<br/><sup>19</sup> 尚无法在 GCC 环境中使用，但即将推出。
<br/><sup>20</sup> 个仅适用于 Microsoft Stream 的消耗量：不发布或共享。
<br/><sup>21</sup> 不适用于 MICROSOFT Graph API 或 microsoft 团队。

## <a name="office-application-availability-and-enterprise-value"></a>Office 应用程序可用性和企业价值

下表显示 Office 365 美国政府版计划中所提供的 Office 应用程序功能。<br><br>

|应用程序/功能|Office 365 政府版 G1|Office 365 政府版 G3|Office 365 政府版 G5|Office 365 政府 F3|
|---|---|---|---|---|
|**Office 应用程序**|||||
|[Microsoft Word](../../office-applications-service-description/office-applications.md#microsoft-word)<sup>7</sup>|否|是|是|否|
|[Microsoft Excel](../../office-applications-service-description/office-applications.md#microsoft-excel)<sup>7</sup>|否|是|是|否|
|[Microsoft PowerPoint](../../office-applications-service-description/office-applications.md#microsoft-powerpoint)<sup>7</sup>|否|是|是|否|
|[Microsoft OneNote](../../office-applications-service-description/office-applications.md#microsoft-onenote)<sup>7</sup>|否|是|是|否|
|[Microsoft Outlook](../../office-applications-service-description/office-applications.md#microsoft-outlook)<sup>7</sup>|否|是|是|否|
|Microsoft Forms<sup>7</sup>|是|是 <br/>|是|否|
|Microsoft 白板<sup>7</sup>|否|是|是|否|
|[Microsoft Publisher](../../office-applications-service-description/office-applications.md#microsoft-publisher)|否|是|是|否|
|[Microsoft Access](../../office-applications-service-description/office-applications.md#microsoft-access)|否|是|是|否|
|[Skype for Business](../../office-applications-service-description/office-applications.md#skype-for-business)|是<sup>3</sup>|是|是|是<sup>3</sup>|
|[适用于 Office 365 的 Office for Mac](https://support.office.com/article/General-requirements-for-Outlook-2016-for-Mac-A07A593D-B383-4906-A6C1-962D5543ED57)|否|是|是|否|
|[Office Mobile for iPad/iPhone](../../office-applications-service-description/office-applications.md#office-mobile-for-ipadiphone)|是|是<sup></sup>|是<sup></sup>|是|
|[Office Mobile for Android](../../office-applications-service-description/office-applications.md#office-mobile-for-android)|是|是<sup></sup>|是<sup></sup>|是|
|[Office Mobile for Windows Phone](../../office-applications-service-description/office-applications.md#office-mobile-for-windows-phone)|是|是<sup>4</sup>|是<sup>4</sup>|是|
|Office Mobile for Windows 10 tablets|是|是<sup></sup>|是<sup></sup>|是|
|Outlook for iOS 和 Android<sup>5，4</sup>|是|是|是|是|
|**企业价值**|**Office 365 政府版 G1**|**Office 365 政府版 G3**|**Office 365 政府版 G5**|**Office 365 政府 F3**|
|每个用户可在 5 台 PC 或 Mac 上进行安装|否|是|是|否|
|自动化用户帐户配置|是|是|是|是|
|多语言用户界面|否|是|是|否|
|客户端推送部署|否|是<sup>4</sup>|是<sup>4</sup>|否|
|内部部署 Exchange 的客户端支持|否|是|是|否|
|内部部署 SharePoint 的客户端支持|否|是|是|否|
|控制软件更新|否|是|是|否|
|数据库比较|否|是|是|否|
|桌面虚拟化|否|是|是|否|
|Excel 电子表格比较|否|是|是|否|
|Excel 电子表格查询|否|是|是|否|
|Exchange Online 和 SharePoint Online 存档和合规性|否|是|是|否|
|组策略支持|否|是|是|否|
|使用 Azure 信息保护的信息权限管理|否<sup>1</sup>|是<sup>6</sup>|是<sup>6</sup>|否<sup>1</sup>|
|使用 Windows Server AD RMS 的信息权限管理|是<sup>2</sup>|是<sup>2</sup>|是<sup>2</sup>|是<sup>2</sup>|
|Office 插件、ActiveX 和 BHO 支持|否|是|是|否|
|在 SharePoint Server、SharePoint Online、OneDrive for Business 和 Office 365 上对笔记本的 OneNote 客户端访问|否|是|是|否|
|Office Lens|否|否|否|否|
|Office 遥测|否|是<sup>4</sup>|是<sup>4</sup>|否|
|客户端应用程序的脱机支持|否|是|是|否|
|优化并排客户端安装|否|是|是|否|
|Power Map for Excel|否|是<sup>4</sup>|是<sup>4</sup>|否|
|Power Pivot for Excel|否|是<sup>4</sup>|是<sup>4</sup>|否|
|Power Query for Excel|否|是<sup>4</sup>|是<sup>4</sup>|否|
|Power View for Excel|否|是<sup>4</sup>|是<sup>4</sup>|否|
|漫游设置|否|是<sup></sup>|是<sup></sup>|否|
|共享计算机激活|否|是|是|否|
|支持阻止基于云的文件存储|否|是|是|否|
|版本升级|否|是<sup>4</sup>|是<sup>4</sup>|否|
|批量激活 (KMS/MAK)|否|否|否|否|

> <sup>1</sup> Azure 信息保护不包括在内，但可以作为单独的附加项购买，并将启用受支持的信息权限管理 (IRM) 功能。 某些 Azure 信息保护功能需要订阅适用于企业的 Microsoft 365 应用程序，该订阅不包含在 Office 365 政府 G1 或 Office 365 政府 F3 中。
<br/><sup>2</sup> WINDOWS SERVER AD RMS 是一台本地服务器，必须单独购买并管理，才能启用受支持的 IRM 功能。
<br/><sup>3</sup> Skype For business Basic 适用于所有客户。 Skype for Business 桌面客户端是在本地安装的应用程序，为包含 Skype for Business Online 的 Office 365 计划提供状态、即时消息和会议功能。 适用于企业的 Microsoft 365 应用和 Office 365 企业版 E3 包括完整的 Skype 应用程序，其中包括高级电话支持、存档和合规性功能等附加功能。 A Skype for Business Online license must be assigned for each user. For more information on Lync Basic features, see [Skype for Business Online client comparison tables](https://docs.microsoft.com/lyncserver/lync-server-2013-desktop-client-comparison-tables).
<br/><sup>4</sup> 在 GCC 高或 DoD 环境中尚不可用，但即将推出。
<br/><sup>5</sup> 有关更多详细信息，请参阅 [在政府社区云中使用 Outlook For iOS 和 Outlook for Android](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud) 。
<br/><sup>6</sup> 在 Office 365 DoD 环境中尚不可用，但即将推出。
<br/><sup>7</sup> 应用程序在政府群中完全可用，但目前尚不可用的特定功能除外。 有关详细信息，请参阅 [Office 应用程序功能可用性](#office-application-and-feature-availability-in-government-plans) 。

## <a name="office-application-and-feature-availability-in-government-plans"></a>政府计划中的 Office 应用程序和功能可用性

政府群中提供了以下 Office 应用程序;但是，一些基于云的功能目前可能不可用，如表中所示。<br><br>

|应用程序/功能|GCC|GCC 高|DOD|
|---|---|---|---|
|[**Microsoft Excel**](../../office-applications-service-description/office-applications.md#microsoft-excel)在政府群中完全可用，但以下功能除外 **，目前不可用：**||||
|3D 嵌入动画和3D 模型|否|否|否|
|数据类型|否|否|否|
|快速填充|否|否|否|
| (真知灼见 Services) 的想法|否|否|否|
|改进了与 Power BI (自定义视觉对象的集成，从 Excel 中直接创建 PBI 图表) |否|否|否|
|智能数字墨迹|否|否|否|
|Office 365 组|否|否|否|
|连接到数据透视表的数据透视图数据|否|否|否|
|PowerPivot|否|否|否|
|发布到 Power BI|否|否|否|
|实时协作 (状态、常规合著和文档内聊天) |否|否|否|
|已与我共享|否|否|否|
|智能查找|否|否|否|
|图表：旭日树状图、瀑布图、直方图、地图、timeline、漏斗|否|否|否|
|版本历史记录|否|否|否|
|[**Microsoft Forms**](https://support.office.com/article/5cbd407a-eef7-431e-8e3a-eb666eab4b4c)在政府群中完全可用，但以下功能除外 **，目前不可用：**|**GCC**|**GCC 高**|**DOD**|
|电子邮件通知|否<sup>1</sup>|否<sup>1</sup>|否|
|插入图片|否<sup>1</sup>|否<sup>1</sup>|否|
|插入视频|否<sup>1</sup>|否<sup>1</sup>|否|
|数学|否<sup>1</sup>|否<sup>1</sup>|否|
|Office 集成|否<sup>1</sup>|否<sup>1</sup>|否|
|最近的组窗体|否<sup>4</sup>|是|是|
|外部共享<sup>3</sup>|是|否|否|
|Forms Pro|否|否|否|
|[**Microsoft OneNote**](../../office-applications-service-description/office-applications.md#microsoft-onenote) 在政府群中完全可用，但以下 **功能（此时不可用）** 除外：|**GCC**|**GCC 高**|**DOD**|
|研究工具|否|否|否|
|智能数字墨迹|否|否|否|
|[**Microsoft Outlook**](../../office-applications-service-description/office-applications.md#microsoft-outlook)在政府群中完全可用，但以下功能除外 **，目前不可用：**|**GCC**|**GCC 高**|**DOD**|
| (一些) 的 Office 声音|否|否|否|
|默认情况下禁用动态数据交换 (DDE) |否|否|否|
|语音听写|否<sup>1</sup>|否<sup>1</sup>|否<sup>1</sup>|
|[**Microsoft PowerPoint**](../../office-applications-service-description/office-applications.md#microsoft-powerpoint)在政府群中完全可用，但以下功能除外 **，目前不可用：**|**GCC**|**GCC 高**|**DOD**|
|智能查找|否|否|否|
| (一些) 的 Office 声音|否|否|否|
|3D 模型和3D 嵌入动画|否|否|否|
|图表：地图|否|否|否|
|智能数字墨迹|否|否|否|
|PowerPoint 中的 Live 字幕和副标题|否|否|否|
|演示者指导|否|否|否|
|已与我共享|否|否|否|
|Skype for business 与共享的集成|否|否|否|
|版本历史记录|否|否|否|
|Office 365 组|否|否|否|
|实时协作 (状态、常规合著和文档内聊天) |否|否|否|
|语音听写|否<sup>1</sup>|否<sup>1</sup>|否<sup>1</sup>|
|重用幻灯片|否|否|否|
|政府群中的 **Microsoft 白板** 目前仅适用于中心客户端，而不是在桌面上。|**GCC**<sup>2</sup>|**GCC High**<sup>2</sup>|**DOD**<sup>2</sup>|
|插入粘滞便笺、文本和图像|是<sup>2</sup> <br/>|是<sup>2</sup> <br/>|是<sup>2</sup> <br/>|
|将墨迹转换为形状和将墨迹转换为表格|是<sup>2</sup> <br/>|是<sup>2</sup> <br/>|是<sup>2</sup> <br/>|
|墨迹 beautification|是<sup>2</sup> <br/>|是<sup>2</sup> <br/>|是<sup>2</sup> <br/>|
|将图像转换为墨迹|是<sup>2</sup> <br/>|是<sup>2</sup> <br/>|是<sup>2</sup> <br/>|
|辅助功能检查器|是<sup>2</sup> <br/>|是<sup>2</sup> <br/>|是<sup>2</sup> <br/>|
|动态模板 (看板、SWOT 等) |否|否|否|
|实时协作|否|否|否|
|实时状态|否|否|否|
|对内容的反应|否|否|否|
|板卡库，包括与你共享的白板|否|否|否|
|[**Microsoft Word**](../../office-applications-service-description/office-applications.md#microsoft-word)在政府群中完全可用，但以下功能除外 **，目前不可用：**|**GCC**|**GCC 高**|**DOD**|
|智能查找|否|否|否|
|研究工具|否|否|否|
|Office 声音|否|否|否|
|3D 模型|否|否|否|
|3D 嵌入动画|否|否|否|
|点击|否|否|否|
|简历助手|否|否|否|
|地图图表|否|否|否|
|智能数字墨迹|否|否|否|
|已与我共享|否|否|否|
|Translation|否|否|否|
|Skype for business 与共享的集成|否|否|否|
|版本历史记录|否|否|否|
|Office 365 组|否|否|否|
|与共同作者的上下文聊天：与文档中的共同作者聊天|否|否|否|
|语音听写|否<sup>1</sup>|否<sup>1</sup>|否<sup>1</sup>|

若要了解适用于 GCC/GCC 高/DoD 中的 Microsoft 团队的功能可用性，请访问 [Microsoft 团队服务说明](https://docs.microsoft.com/office365/servicedescriptions/teams-service-description)。
> <sup>1</sup> 可用性即将推出。
<br/><sup>2</sup> 在本地 Surface Hub 上的可用性 (未在) 中登录。
<br/><sup>3</sup> 外部共享适用于 GCC 环境。 了解有关如何为你的组织 [关闭或打开 Microsoft 表单](https://support.office.com/article/cc52287a-4550-464d-9a1b-457bf9df2240#PickTab=Configure) 的详细信息。 为 GCC 的高和 DOD 环境禁用外部共享;您组织中的用户可以执行以下操作：填写表单并提交响应、 [复制表单并将其共享为模板](https://support.office.com/article/82ea9d8a-260a-47a0-afdb-497f3d746e3f)、 [共同创作或协作处理表单](https://support.office.com/article/d5bb5cf0-8401-4c15-bb8c-8e108cd7e69b)以及 [访问表单结果](https://support.office.com/article/02859424-341d-406f-b32a-9a0fbaf357af)。
<br/><sup>4</sup> 已为 GCC 环境禁用最近使用的组表单功能。 但是，用户仍可以通过在 "组窗体" 选项卡上选择特定的组来访问组窗体。
