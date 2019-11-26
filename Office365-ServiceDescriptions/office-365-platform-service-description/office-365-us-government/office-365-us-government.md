---
title: Office 365 美国政府版
ms.author: danarl
author: danarl
manager: dianap
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 3f482abc-993f-41bf-8754-0f489a7e4861
description: 为了响应美国公共事业部门的独特和不断发展的需求，Microsoft 创建了 Office 365 美国政府版计划（或 Office 365 政府版）。 本节概述了特定于 Office 365 政府美国环境的功能。 我们建议您在 Office 365 服务说明旁边阅读此补充部分。
ms.openlocfilehash: 5676680e5285b7b825388e8140480a07bef047b6
ms.sourcegitcommit: 2b9f68f7731dfd6f9d3f33e31e6303e81985ebb2
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/26/2019
ms.locfileid: "39262523"
---
# <a name="office-365-us-government"></a>Office 365 美国政府版

为了响应美国公共事业部门的独特和不断发展的需求，Microsoft 创建了 Office 365 美国政府版计划（或 Office 365 政府版）。 本节概述了特定于 Office 365 政府美国环境的功能。 我们建议您在[Office 365 服务说明](../../office-365-service-descriptions-technet-library.md)旁边阅读此补充部分。
  
## <a name="how-to-use-this-service-description-section"></a>如何使用本服务说明部分

Office 365 美国政府版 服务说明旨在作为常规 Office 365 服务说明的整体进行说明。它定义了唯一承诺以及与 Office 365 企业版产品的差异。
  
## <a name="about-office-365-us-government-environments"></a>关于 Office 365 美国政府版环境

Office 365 美国政府版计划为按月订阅，可以授权给任意数量的用户。 
  
- **Office 365 GCC**环境符合云服务的联邦要求，包括 FedRAMP 中型 and 刑事审判和联邦税务信息系统（CJI 和 FTI data types）的要求。 
    
- **Office 365 GCC 高和 DoD**环境遵从国防部安全要求准则、防御联邦收购法规补充（DFARS）和 arm 规章（ITAR）中的国际流量。 
    
除 Office 365 的功能之外，使用 Office 365 美国政府版 的组织还可以从以下 Office 365 美国政府版 独特功能中获益：
  
- 您组织的客户内容与 Microsoft 商业 Office 365 服务中的客户内容在逻辑上是隔离的。
    
- 您组织的客户内容存储在美国境内。
    
- 对组织的客户内容的访问权限只限于屏蔽的 Microsoft 员工。
    
- Office 365 美国政府版符合美国公共部门客户所需的认证和资格鉴定。
    
["如何使用此服务说明" 部分](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="customer-eligibility"></a>客户资格

Office 365 美国政府版适用于 (1) 美国联邦、州、地方、部族和地区政府机构及 (2) 按政府规定和要求处理数据的其他实体（使用Office 365 美国政府版可符合这些要求，使用前须验证资格）。 Microsoft 的资格验证包括确认处理的是受符合国际武器贸易条例 (ITAR) 约束的数据，还是受 FBI 的刑事司法信息服务 (CJIS) 政策约束的执法数据，亦或是其他受政府监管或控制的数据。 对于 ITAR 数据，资格验证可能需要提供美国国务院注册证明；对于数据处理的具体要求，可能需要提供政府机构资助证明。 Office 365 DoD-环境旨在专门使用美国国防部。
  
虽然符合各 Office 365 政府产品的资格标准，但 Microsoft 仅同意 DFARS 和 ITAR 合同语言 for GCC 的高环境。
  
对 Office 365 美国政府版 资格持有疑问的实体应向其帐户团队咨询。
  
客户续订 Office 365 美国政府版 合同后，需要重新验证资格。
  
["如何使用此服务说明" 部分](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="customer-content-located-within-the-united-states"></a>位于美国境内的客户内容

Office 365 美国政府版服务从物理上位于美国的数据中心提供。下面的客户内容存储在仅物理上位于美国的数据中心中的其余部分： 
  
- Exchange Online 邮箱内容（电子邮件正文、日历条目和电子邮件附件的内容）
    
- SharePoint Online 网站内容和该网站中存储的文件
    
- Skype for Business 存档的对话、已上载的文档和白板会话

- Microsoft 团队持久聊天线索
    
> [!NOTE]
> 对于一般用途，Skype for Business 不存储客户内容，但如果存储，内容会存储在美国的数据中心内。 
  
如果您的用户在美国中使用 Office for web （以前称为 Office Web Apps），或者您采用了 Active Directory 联合身份验证服务（AD FS）2.0，并设置了策略以帮助您的用户通过单 si 连接到服务gn-打开在 Office 中临时缓存到 web 的任何客户内容都将位于美国中。
  
["如何使用此服务说明" 部分](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="office-365-us-government-and-third-party-services"></a>Office 365 美国政府版和第三方服务

Office 365 可以将第三方应用程序集成到 SharePoint Online 站点、Skype for Business、Office 365 ProPlus 中的 Office 应用程序（如 Word、Excel、PowerPoint 和 Outlook）以及 Outlook Web App。此外，Office 365 还支持与第三方服务提供商集成。这些第三方应用程序和服务可能参与存储、传输和处理组织在 Office 365 基础结构外部的第三方系统上的客户数据，因此未涵盖在 Office 365 合规性和数据保护协议中。我们建议您在为组织评估这些服务的相应使用情况时，查看第三方提供的隐私和合规性声明。
  
["如何使用此服务说明" 部分](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="restricted-data-access-by-administrators"></a>管理员受限数据访问

Microsoft 管理员对 Office 365 美国政府客户内容的访问权限仅限于被筛选人员。 有关筛选级别的详细信息，请参阅每个各自的环境的 "服务说明" 页面（GCC 或 GCC 高和 DoD）。 

  
## <a name="fasttrack-center-onboarding-assistance"></a>FastTrack Center 载入帮助

使用适用于 Office 365<sup>1</sup>的 FastTrack 中心权益，您可以与 FastTrack 专家远程合作，让您的 Office 365 环境准备就绪，并在您的组织内规划部署和使用情况。 FastTrack 流程提供了载入和用户采用服务。 
  
载入包括：
  
- 核心载入-这些是租户配置和与 Azure Active Directory （Azure AD）集成所需的任务（如果需要）。 核心载入还为载入其他符合条件的服务提供了基线。
    
- 服务载入和迁移-服务载入任务可在租户中启用方案。 数据迁移中介绍了数据迁移（包括电子邮件和文件[）。](https://aka.ms/whatcanmigrate)<sup>2</sup>
    
用户采用服务由多个任务组成，可提供指导以确保你的用户了解符合条件的服务，并可以使用它们推动业务价值。此协助与载入活动并行发生。
  
可在[此处](https://aka.ms/whatistheprocess)找到有关 FastTrack 中心流程的特定信息。 有关接洽角色和责任的细分，请查看[FastTrack 责任](https://aka.ms/whatdoesftcdo)以及[您的责任](https://aka.ms/whatdowedo)。
  
<sup>1</sup>您必须从[符合条件的计划](https://aka.ms/whocanbenefit)列表中至少购买50许可证，才能接收 FastTrack 服务。 
  
<sup>2</sup>数据迁移服务可用于包含500或更多许可证的 Office 365 租户。 
  
## <a name="data-migrations-performed-by-fasttrack"></a>FastTrack 执行的数据迁移

选择[FastTrack](https://fasttrack.microsoft.com/)迁移权益的客户将需要向管理其数据迁移的团队授予访问权限。 在为 Office 365 美国政府版的客户执行迁移之前，这些人员都是美国公民，并进行了以下背景检查。 
  
||||
|:-----|:-----|:-----|
|**背景筛查** <br/> |**GCC** <br/> |**GCC High 和 DoD** <br/> |
|核实美国公民身份  <br/> |是  <br/> |是  <br/> |
|工作经历调查  <br/> |是  <br/> |是  <br/> |
|核实教育背景  <br/> |是  <br/> |是  <br/> |
|社会安全号码（SSN）搜索  <br/> |是  <br/> |是  <br/> |
|犯罪记录调查（7 年）  <br/> |是  <br/> |是  <br/> |
   
["如何使用此服务说明" 部分](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="office-365-us-government-and-azure-government-expressroute"></a>Office 365 美国政府版和 Azure 政府 ExpressRoute

Office 365 美国政府版客户可以使用 Azure 政府 ExpressRoute 服务来私下连接到受支持的 Office 365 服务，而不是通过公共 internet 进行连接。
  
有关受支持的提供商、定价模型及更多详细信息，请查看 [Azure ExpressRoute 信息](https://go.microsoft.com/fwlink/?LinkID=798220&amp;clcid=0x409)。
  
有关 Office 365 Azure ExpressRoute 支持的详细信息，请参阅 [Office 365 的 Azure ExpressRoute ](https://go.microsoft.com/fwlink/?LinkID=798216&amp;clcid=0x409)。
  
["如何使用此服务说明" 部分](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="system-requirements"></a>系统要求

有关 Office 365 美国政府版 计划的系统要求，请参阅 [office.com](https://go.microsoft.com/fwlink/?LinkID=626095&amp;clcid=0x409) 产品网站上的 [Office 的系统要求](https://go.microsoft.com/fwlink/?LinkID=509817&amp;clcid=0x409)。 
  
["如何使用此服务说明" 部分](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="security-amp-compliance-center"></a>Security &amp; Compliance Center

有关安全&amp;合规性中心的信息以及指向其他信息和可用性的链接，请参阅[Office &amp; 365 安全合规中心](../../office-365-platform-service-description/office-365-securitycompliance-center.md)。
  
## <a name="service-availability-for-each-plan"></a>每个计划的服务可用性

每个 Office 365 计划都包括许多单个服务，例如 Exchange Online 和 SharePoint Online。下表显示了每个 Office 365 美国政府版 计划中可用的服务。
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**Office 365 服务** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 政府版 G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府 F1** <br/> |
|Office 网页版  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Office 365 ProPlus  <br/> |否 <br/> |可访问 <br/> |是 <br/> |否  <br/> |
|Exchange Online  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Exchange Online Protection  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|SharePoint Online  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|OneDrive for Business  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Skype for Business (Instant Messaging &amp; Presence)  <br/> |是<sup>1</sup> <br/> |是  <br/> |是  <br/> |是<sup>1</sup> <br/> |
| 语音电话系统、音频会议  <br/> |否<sup>2、3</sup> <br/> |否<sup>2、3</sup> <br/> |是<sup>3，5</sup> <br/> |否  <br/> |
|Power BI Pro  <br/> |无<sup>2</sup> <br/> |无<sup>2</sup> <br/> |是  <br/> |无<sup>2</sup> <br/> |
|Project Online  <br/> |无<sup>2</sup> <br/> |无<sup>2</sup> <br/> |无<sup>2</sup> <br/> |无<sup>2</sup> <br/> |
|Visio 网页版  <br/> |无<sup>6</sup> <br/> |无<sup>6</sup> <br/> |无<sup>6</sup> <br/> |无<sup>6</sup> <br/> |
|Yammer 企业版  <br/> |无<sup>4</sup> <br/> |无<sup>4</sup> <br/> |无<sup>4</sup> <br/> |无<sup>4</sup> <br/> |
   
> <sup>1</sup> Skype For business Basic 适用于所有客户。 Skype for Business 桌面客户端是在本地安装的应用程序，为包含 Skype for Business Online 的 Office 365 计划提供状态、即时消息和会议功能。 Office 365 专业增强版、G3 和 G5 包括完整的 Skype 应用程序，其中包括高级电话支持、存档和合规性功能等附加功能。 A Skype for Business Online license must be assigned for each user.
<br/><sup>2</sup>不包括在内，但可以作为单独的附加项购买。 Project Online 包括 Project Online 桌面客户端作为订阅的一部分。
<br/> <sup>3</sup>尚不可用于 GCC 高或 DoD 计划，但即将推出。 
<br/><sup>4</sup> Yammer 企业不是 OFFICE 365 美国政府的一个组件，但可以免费获得，作为在 GCC 中为 Office 365 许可的每个用户提供的独立服务。 此优惠目前仅限于在企业协议和企业订阅协议下购买 Office 365 GCC 的客户。 Yammer 在 GCC High 或 DoD 中不可用。
<br/><sup>5</sup>通话套餐是一个附加项。 
<br/><sup>6</sup>不包括在内，但可以作为单独的附加项购买。 Visio for web 将 Visio 桌面应用程序作为订阅的一部分包括在其中。
## <a name="platform-features"></a>平台功能 

下表列出了Office 365 美国政府版 计划中所提供的平台功能和服务。
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 政府版 G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府 F1** <br/> |
|**Office 365 管理** <br/> |||||
|使用 Microsoft 365 管理中心管理 Office 365  <br/> |是<sup>16</sup> <br/> |是<sup>16</sup> <br/> |是  <br/> |是<sup>16</sup> <br/> |
|从 Office 365 中管理核心服务设置  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|使用 Windows PowerShell 管理 Office 365  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|使用 Azure 信息保护保护内容  <br/> |无<sup>1</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup>  <br/> |无<sup>1</sup> <br/> |
|**[Office 365 套件功能](../../office-365-platform-service-description/office-365-suite-features.md)** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 政府版 G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府 F1** <br/> |
|Microsoft 预订  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |
|Microsoft 简介电子邮件  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |
|Microsoft Flow  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|Microsoft Forms  <br/> |是 <br/> |是 <br/> |是<br/> |是</sup> <br/> |
|Microsoft Graph API  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Microsoft MyAnalytics  <br/> |否 <br/> |否 <br/> |是<sup>17</sup> <br/> |否 <br/> |
|Microsoft Planner  <br/> |是 <br/> |是 <br/> |是 <br/> |是 <br/> |
|Microsoft PowerApps  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|Microsoft StaffHub  <br/> |否 <br/> |否 <br/> |否 <br/> |否<br/> |
|Microsoft Stream  <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |否  <br/> |
|Microsoft Sway  <br/> |否 <br/> |否 <br/> |否 <br/> |否 <br/> |
|Microsoft Teams  <br/> |是 <br/> |是 <br/> |是 <br/> |是 <br/> |
|Office Delve  <br/> |是<sup>17</sup> <br/> |是<sup>17</sup> <br/> |是  <br/> |是<sup>17</sup> <br/> |
|Office 365 组  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[用户帐户管理](../../office-365-platform-service-description/user-account-management.md)** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 政府版 G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府 F1** <br/> |
|云身份  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|联合身份（单点登录）  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|多重身份验证  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|电话系数身份验证  <br/> |是<sup>9</sup> <br/> |是<sup>9</sup> <br/> |是  <br/> |是<sup>9</sup> <br/> |
|Office 365 桌面设置  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|使用 Office 365 管理用户  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|使用 .csv 文件批量上载  <br/> |是<sup>9</sup> <br/> |是<sup>9</sup> <br/> |是  <br/> |是<sup>9</sup> <br/> |
|目录同步工具  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Exchange 简单（直接转换）迁移  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|通过使用 Office 365 删除帐户  <br/> |是<sup>3</sup> <br/> |是 <sup>3</sup> <br/> |是 <sup>3</sup> <br/> |是 <sup>3</sup> <br/> |
|管理员可以从 Office 365 中或通过使用 Windows PowerShell 重新设置用户密码  <br/> |是<sup>4</sup> <br/> |是 <sup>4</sup> <br/> |是 <sup>4</sup> <br/> |是 <sup>4</sup> <br/> |
|用户可以更改自己的密码  <br/> |是<sup>5</sup> <br/> |是 <sup>5</sup> <br/> |是 <sup>5</sup> <br/> |是 <sup>5</sup> <br/> |
|管理许可证  <br/> |是<sup>7、8</sup> <br/> |是<sup>7、8</sup> <br/> |是<sup>7、8</sup> <br/> |是<sup>7、8</sup> <br/> |
|从 Office 365 中管理安全组  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|多个管理员角色可用  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|允许合作伙伴为您管理 Office 365  <br/> |是<sup>11</sup> <br/> |是<sup>11</sup> <br/> |是<sup>11</sup> <br/> |是<sup>11</sup> <br/> |
|Azure Active Directory 服务  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[域](../../office-365-platform-service-description/domains.md)** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 政府版 G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府 F1** <br/> |
|添加第二级自定义域，如 fourthcoffee.com  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|添加第三级自定义域，如 marketing.fourthcoffee.com是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|添加多达 900 个自定义域  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|自定义域需要域所有权验证  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[服务运行状况和连续性](../../office-365-platform-service-description/service-health-and-continuity.md)** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 政府版 G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府 F1** <br/> |
|Status information available on the **Service health** or **Service status** page  <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |
|Microsoft 365 管理中心仪表板上提供的单个警报的状态  <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |
|**Service health** RSS feed  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[报告](../../office-365-platform-service-description/reports.md)** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 政府版 G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府 F1** <br/> |
|活动邮箱和非活动邮箱  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|新邮箱和已删除的邮箱  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|新组和已删除的组  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|邮箱使用情况  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|邮箱连接类型  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|已发送和已接收邮件  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|主要发件人和收件人  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|垃圾邮件检测  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|恶意软件检测  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|邮件的主要恶意软件  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|邮件的规则匹配  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|邮件的主要规则匹配  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|邮件的主要 DLP 策略匹配  <br/> |否  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|按邮件严重性显示的 DLP 策略匹配  <br/> |否  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|邮件的 DLP 策略匹配、重写和误报  <br/> |否  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|邮件的主要 DLP 规则匹配  <br/> |否  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|IM 和音频会话  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|应用程序共享、Web 和电话拨入式会议  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|视频、应用程序共享和文件传输会话  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|IM 和音频/视频会议  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|可下载的邮件保护报告  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|使用的浏览器  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|使用的操作系统  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|使用 Office 365 报告 Web 服务创建自己的报告  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|**[服务更新](../../office-365-platform-service-description/service-updates.md)** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 政府版 G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府 F1** <br/> |
|向所有客户提供的定期更新  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|通知发送给 消息中心（当需要操作时）  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|针对某些服务更新的 Roadmap.office.com  <br/> |无<sup>10、13</sup> <br/> |无<sup>10、13</sup> <br/> |无<sup>10、13</sup> <br/> |无<sup>10、13</sup> <br/> |
|启用目标版本的选项  <br/> |是<sup>10</sup> <br/> |是<sup>10</sup> <br/> |是<sup>10</sup> <br/> |是<sup>10</sup> <br/> |
|**[帮助和培训](../../office-365-platform-service-description/help-and-training.md)** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 政府版 G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府 F1** <br/> |
|联机帮助  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|社区  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|其他自助资源  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|自学培训  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[网络](../../office-365-platform-service-description/networking.md)** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 政府版 G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府 F1** <br/> |
|IPv4 和 IPv6 协议  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**信任** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 政府版 G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府 F1** <br/> |
|**[隐私、安全性和透明度](../../office-365-platform-service-description/privacy-security-and-transparency.md)** <br/> |||||
|高级数据治理  <br/> |无<sup>12</sup> <br/> |无<sup>12</sup> <br/> |是 <br/> |无<sup>12</sup> <br/> |
|云应用安全  <br/> |无<sup>11、12</sup> <br/> |无<sup>11、12</sup> <br/> |是<sup>11</sup> <br/> |无<sup>11、12</sup> <br/> |
|高级威胁防护  <br/> |无<sup>12、18</sup> <br/> |无<sup>12、18</sup> <br/> |是<sup>18</sup>  <br/> |无<sup>12、18</sup> <br/> |
|客户密码箱  <br/> |无<sup>9、12、15</sup> <br/> |无<sup>9、12、15</sup> <br/> |是<sup>9，15</sup> <br/> |无<sup>9、12、15</sup> <br/> |
|Office 365 高级电子数据展示  <br/> |无<sup>12</sup> <br/> |无<sup>12</sup> <br/> |是  <br/> |无<sup>12</sup> <br/> |
|安全分数<sup>14</sup> <br/> |是<sup>9，15</sup> <br/> |是<sup>9</sup> <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |
|Office 邮件加密  <br/> |否  <br/> |可访问 <br/> |是 <br/> |否  <br/> |
|威胁智能  <br/> |无<sup>12</sup> <br/> |无<sup>12</sup> <br/> |是 <br/> |无<sup>12</sup> <br/> |
|**[Compliance](../../office-365-platform-service-description/compliance-servicedesc.md)** <br/> |||||
|SAS 70 / SSAE16 评估  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|ISO 27001 认证  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|欧盟模式条款  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|欧盟安全港  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|HIPAA 业务关联协议  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|FISMA 操作授权  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Microsoft 数据处理协议  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|一级 PCI DSS  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|PCI 监管的 PAN 数据  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |
|**[服务连续性](../../office-365-platform-service-description/service-health-and-continuity.md)** <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[BlackBerry](../../office-365-platform-service-description/blackberry.md)** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 政府版 G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府 F1** <br/> |
|是  <br/> |无<sup>2</sup> <br/> |无<sup>2</sup> <br/> |无<sup>2</sup> <br/> |无<sup>2</sup> <br/> |
|**[合作伙伴](../../office-365-platform-service-description/partners.md)** <br/> |||||
|是  <br/> |无<sup>11</sup> <br/> |无<sup>11</sup> <br/> |无<sup>11</sup> <br/> |无<sup>11</sup> <br/> |
|是  <br/> |无<sup>11</sup> <br/> |无<sup>11</sup> <br/> |无<sup>11</sup> <br/> |无<sup>11</sup> <br/> |
|**[服务级别协议](../../office-365-platform-service-description/service-level-agreement.md)** <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[产品使用权限](../../office-365-platform-service-description/product-use-rights.md)** <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
   
> <sup>1</sup> Azure 信息保护不包括在内，但可以作为单独的附加项购买，并将启用受支持的信息权限管理（IRM）功能。 某些 Azure 信息保护功能需要订阅 Office 365 专业增强版，该订阅不包含在 Office 365 政府 G1 或 Office 365 政府 F1 中。 > 
<br/><sup>2</sup> 现有的 BBCS 和 BIS 客户可继续使用服务。 不接受新客户。 
<br/><sup>3</sup> 如果使用目录同步，您必须使用 Active Directory（而不是 Office 365 门户）或使用 Windows PowerShell 的 Azure Active Directory 模块来删除帐户或更改密码。 
<br/><sup>4</sup> 如果使用密码同步，用户必须更改本地 Active Directory 中的密码。 
<br/><sup>5</sup> 若要了解如何为用户设置自助服务密码管理策略，请参阅 [管理 Azure AD 中的密码](https://azure.microsoft.com/documentation/articles/active-directory-manage-passwords/)。 
<br/><sup>6</sup> Office 365 只能有一个公共网站，除非你已升级旧版 Office 365。 如果已升级，可以拥有两个公共网站，但其中只有一个能够使用自定义域名托管。 若要详细了解如何处理商业版订阅的两个网站，请参阅 [处理两个 Office 365 公共网站](https://go.microsoft.com/fwlink/p/?LinkID=271589)。 如果有其他订阅，请参阅[在 Office 365 中了解合作伙伴网站托管和公共网站](https://go.microsoft.com/fwlink/p/?LinkID=325009)，详细了解公共网站。 
<br/><sup>7</sup> 减少按费用折扣购买的席位可能会导致提前终止费用。 这不适用于按月支付的订阅。 
<br/><sup>8</sup>以下计划不支持来自 Microsoft 365 管理中心的许可证座位更改： Office 365 政府 G1、Office 365 政府 G3、Office 365 政府 F1。 
<br/><sup>9</sup>在 GCC 高版中尚不可用，但即将推出。
<br/><sup>10</sup> For Office 365 政府 G1、G3 和 F1、目标版本和 Office 365 For business 路线图适用;但是，由于[合规性要求](https://www.microsoft.com/trust-center)，特定服务更新可能会存在一些差异或延迟。
<br/><sup>11</sup>尚不可用于 Office 365 政府产品，但即将推出。 
<br/><sup>12</sup>不包括在内，但可以作为单独的附加项在 GCC 中购买。 
<br/><sup>13</sup>不支持 Office 365 政府版产品。 
<br/><sup>14</sup>可在[https://securescore.office.com](https://securescore.office.com)中找到。 必须拥有管理员权限。 有关详细信息，请参阅[简介 Office 365 安全分数](https://go.microsoft.com/fwlink/?linkid=836894)。 
<br/><sup>15</sup>在 DoD 环境中尚不可用，但即将推出。 
<br/><sup>16</sup>管理中心不包括 DOD 或 GCC 高级环境中的使用情况分析。
<br/><sup>17</sup>不支持 GCC 高或 DoD 环境。
<br/><sup>18</sup>在 GCC 高和 DoD 中尚不提供用于用户和域模拟和欺骗情报的反网络钓鱼。
  
["如何使用此服务说明" 部分](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="office-application-features"></a>Office 应用程序功能  

下表显示 Office 365 美国政府版计划中所提供的 Office 应用程序功能。
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 政府版 G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府 F1** <br/> |
|**Office 应用程序** <br/> |||||
|[Microsoft Word](../../office-applications-service-description/office-applications.md#microsoft-word) <br/> |否  <br/> |可访问  <br/> |是  <br/> |否  <br/> |
|[Microsoft Excel](../../office-applications-service-description/office-applications.md#microsoft-excel) <br/> |否  <br/> |可访问  <br/> |是  <br/> |否  <br/> |
|[Microsoft PowerPoint](../../office-applications-service-description/office-applications.md#microsoft-powerpoint) <br/> |否  <br/> |可访问  <br/> |是  <br/> |否  <br/> |
|[Microsoft OneNote](../../office-applications-service-description/office-applications.md#microsoft-onenote) <br/> |否  <br/> |可访问  <br/> |是  <br/> |否  <br/> |
|[Microsoft Outlook](../../office-applications-service-description/office-applications.md#microsoft-outlook) <br/> |否  <br/> |可访问  <br/> |是  <br/> |否  <br/> |
|[Microsoft Publisher](../../office-applications-service-description/office-applications.md#microsoft-publisher) <br/> |否  <br/> |可访问  <br/> |是  <br/> |否  <br/> |
|[Microsoft Access](../../office-applications-service-description/office-applications.md#microsoft-access) <br/> |否  <br/> |可访问  <br/> |是  <br/> |否  <br/> |
|[Skype for Business](../../office-applications-service-description/office-applications.md#skype-for-business) <br/> |是<sup>3</sup> <br/> |是  <br/> |是  <br/> |是<sup>3</sup> <br/> |
|[适用于 Office 365 的 Office for Mac](https://support.office.com/article/General-requirements-for-Outlook-2016-for-Mac-A07A593D-B383-4906-A6C1-962D5543ED57) <br/> |否  <br/> |可访问  <br/> |是  <br/> |否  <br/> |
|[Office Mobile for iPad/iPhone](../../office-applications-service-description/office-applications.md#office-mobile-for-ipadiphone) <br/> |是  <br/> |是<sup></sup> <br/> |是<sup></sup> <br/> |是  <br/> |
|[Office Mobile for Android](../../office-applications-service-description/office-applications.md#office-mobile-for-android) <br/> |是  <br/> |是<sup></sup> <br/> |是<sup></sup> <br/> |是  <br/> |
|[Office Mobile for Windows Phone](../../office-applications-service-description/office-applications.md#office-mobile-for-windows-phone) <br/> |是  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |是  <br/> |
|Office Mobile for Windows 10 tablets <br/> |是  <br/> |是<sup></sup> <br/> |是<sup></sup> <br/> |是  <br/> |
|Outlook for iOS 和 Android<sup>5，4</sup>  <br/> |是 <br/> |是 <br/> |是 <br/> |是 <br/> |
|**企业价值** <br/> |**Office 365 政府版 G1** <br/> |**Office 365 政府版 G3** <br/> |**Office 365 政府版 G5** <br/> |**Office 365 政府 F1** <br/> |
|每个用户可在 5 台 PC 或 Mac 上进行安装  <br/> |否  <br/> |可访问  <br/> |是  <br/> |否  <br/> |
|自动化用户帐户配置  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|多语言用户界面  <br/> |否  <br/> |可访问  <br/> |是  <br/> |否  <br/> |
|客户端推送部署  <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|内部部署 Exchange 的客户端支持  <br/> |否  <br/> |可访问  <br/> |是  <br/> |否  <br/> |
|内部部署 SharePoint 的客户端支持  <br/> |否  <br/> |可访问  <br/> |是  <br/> |否  <br/> |
|控制软件更新  <br/> |否  <br/> |可访问  <br/> |是  <br/> |否  <br/> |
|数据库比较  <br/> |否  <br/> |可访问  <br/> |是  <br/> |否  <br/> |
|桌面虚拟化  <br/> |否  <br/> |可访问  <br/> |是  <br/> |否  <br/> |
|Excel 电子表格比较  <br/> |否  <br/> |可访问  <br/> |是  <br/> |否  <br/> |
|Excel 电子表格查询  <br/> |否  <br/> |可访问  <br/> |是  <br/> |否  <br/> |
|Exchange Online 和 SharePoint Online 存档和合规性  <br/> |否  <br/> |可访问  <br/> |是  <br/> |否  <br/> |
|组策略支持  <br/> |否  <br/> |可访问  <br/> |是  <br/> |否  <br/> |
|使用 Azure 信息保护的信息权限管理  <br/> |无<sup>1</sup> <br/> |是<sup>6</sup> <br/> |是<sup>6</sup> <br/> |无<sup>1</sup> <br/> |
|使用 Windows Server AD RMS 的信息权限管理  <br/> |是<sup>2</sup> <br/> |是<sup>2</sup> <br/> |是<sup>2</sup> <br/> |是<sup>2</sup> <br/> |
|Office 插件、ActiveX 和 BHO 支持  <br/> |否  <br/> |可访问  <br/> |是  <br/> |否  <br/> |
|在 SharePoint Server、SharePoint Online、OneDrive for Business 和 Office 365 上对笔记本的 OneNote 客户端访问  <br/> |否  <br/> |可访问  <br/> |是  <br/> |否  <br/> |
|Office Lens  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |
|Office 遥测  <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|客户端应用程序的脱机支持  <br/> |否  <br/> |可访问  <br/> |是  <br/> |否  <br/> |
|优化并排客户端安装  <br/> |否  <br/> |可访问  <br/> |是  <br/> |否  <br/> |
|Power Map for Excel  <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|Power Pivot for Excel  <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|Power Query for Excel  <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|Power View for Excel  <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|漫游设置  <br/> |否  <br/> |是<sup></sup> <br/> |是<sup></sup> <br/> |否  <br/> |
|共享计算机激活  <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|支持阻止基于云的文件存储  <br/> |否  <br/> |可访问  <br/> |是  <br/> |否  <br/> |
|版本升级  <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|批量激活 (KMS/MAK)  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |
   
> <sup>1</sup> Azure 信息保护不包括在内，但可以作为单独的附加项购买，并将启用受支持的信息权限管理（IRM）功能。 某些 Azure 信息保护功能需要订阅 Office 365 专业增强版，该订阅不包含在 Office 365 政府 G1 或 Office 365 政府 F1 中。 
<br/><sup>2</sup> WINDOWS SERVER AD RMS 是一台本地服务器，必须单独购买并管理，才能启用受支持的 IRM 功能。 
<br/><sup>3</sup> Skype For business Basic 适用于所有客户。 Skype for Business 桌面客户端是在本地安装的应用程序，为包含 Skype for Business Online 的 Office 365 计划提供状态、即时消息和会议功能。 Office 365 专业增强版和 Office 365 企业版 E3 包括完整的 Skype 应用程序，其中包括高级电话支持、存档和合规性功能等附加功能。 A Skype for Business Online license must be assigned for each user. For more information on Lync Basic features, see [Skype for Business Online client comparison tables](https://docs.microsoft.com/lyncserver/lync-server-2013-desktop-client-comparison-tables). 
<br/><sup>4</sup>在 GCC 高或 DoD 环境中尚不可用，但即将推出。
<br/><sup>5</sup>有关更多详细信息，请参阅[在政府社区云中使用 Outlook For iOS 和 Outlook for Android](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud) 。
  <br/><sup>6</sup>在 Office 365 DoD 环境中尚不可用，但即将推出。
<br/><br/>["如何使用此服务说明" 部分](office-365-us-government.md#how-to-use-this-service-description-section)
