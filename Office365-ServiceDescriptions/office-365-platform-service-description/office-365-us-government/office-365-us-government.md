---
title: Office 365 美国政府版
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 7/6/2018
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 3f482abc-993f-41bf-8754-0f489a7e4861
description: 在美国公共部门的唯一和发展要求的响应，Microsoft 创建 Office 365 美国政府计划 (orOffice 365 美国政府)。本节提供特定于 Office 365 美国政府的功能的概述。建议您阅读本节补充旁 Office 365 服务说明。
ms.openlocfilehash: 30c7f998d57ddcf47922a39fd5492dcdac560ddf
ms.sourcegitcommit: d1d7309e864398e7d029956231cbaee054a2a0cf
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 01/09/2019
ms.locfileid: "27784904"
---
# <a name="office-365-us-government"></a>Office 365 美国政府版

在美国公共部门的唯一和发展要求的响应，Microsoft Office 365 美国政府计划 （或"Office 365 美国政府"） 创建。本节提供特定于 Office 365 美国政府的功能的概述。建议您阅读本节补充旁[Office 365 服务说明](../../office-365-service-descriptions-technet-library.md)。
  
## <a name="how-to-use-this-service-description-section"></a>如何使用本服务说明部分
<a name="TopOfPage"> </a>

Office 365 美国政府版 服务说明旨在作为常规 Office 365 服务说明的整体进行说明。它定义了唯一承诺以及与 Office 365 企业版产品的差异。
  
## <a name="about-office-365-us-government-environments"></a>有关 Office 365 美国政府环境
<a name="BM1_About"> </a>

Office 365 美国政府版计划为按月订阅，可以授权给任意数量的用户。 
  
- **Office 365 GCC**环境提供了遵守联邦云服务，包括 FedRAMP 适度要求和刑事审判和联邦税费信息系统 （CJI 和 FTI 数据类型） 的要求。 
    
- **Office 365 GCC 高和 DoD**环境提供合规性防御安全要求准则部门、 防御联邦获取法规补充 (DFARS) 和国际通信中 Arm 法规 (ITAR)。 
    
除 Office 365 的功能之外，使用 Office 365 美国政府版 的组织还可以从以下 Office 365 美国政府版 独特功能中获益：
  
- 您组织的客户内容与 Microsoft 商业 Office 365 服务中的客户内容在逻辑上是隔离的。
    
- 您组织的客户内容存储在美国境内。
    
- 对组织的客户内容的访问权限只限于屏蔽的 Microsoft 员工。
    
- Office 365 美国政府版符合美国公共部门客户所需的认证和资格鉴定。
    
[如何使用本服务说明部分](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="customer-eligibility"></a>客户资格
<a name="BM2-customer"> </a>

Office 365 美国政府可供 （1） 美国联邦、 州本地经验和地域政府实体和处理受及政府法规要求约束的数据以及其中的 Office 365 美国政府使用 （2） 其他实体适用于满足这些要求，受到资格验证。由 Microsoft 资格验证将包括处理受到国际流量在 Arm 法规 (ITAR)，受到 FBI 刑事审判信息服务 (CJIS) 策略或其他法律强制数据的数据进行确认政府监管或控制数据。验证可能需要证明注册美国状态部门 ITAR 数据或赞助由政府实体具有用于处理的数据的特定要求。Office 365 DoD 环境适用于美国防御部门独占使用。
  
尽管资格条件是跨 Office 365 美国政府版产品一致，Microsoft 将仅同意 GCC 高环境 DFARS 和 ITAR 合同语言。
  
对 Office 365 美国政府版 资格持有疑问的实体应向其帐户团队咨询。
  
客户续订 Office 365 美国政府版 合同后，需要重新验证资格。
  
[如何使用本服务说明部分](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="customer-content-located-within-the-united-states"></a>位于美国境内的客户内容
<a name="BM3-withinUSA"> </a>

Office 365 美国政府版服务从物理上位于美国的数据中心提供。下面的客户内容存储在仅物理上位于美国的数据中心中的其余部分： 
  
- Exchange Online 邮箱内容（电子邮件正文、日历条目和电子邮件附件的内容）。
    
- SharePoint Online 网站内容和网站中存储的文件。
    
- Skype for Business 已存档的对话、已上载的文档和白板会话。
    
> [!NOTE]
> 对于一般用途，Skype for Business 不存储客户内容，但如果存储，内容会存储在美国的数据中心内。 
  
如果您的用户在使用 Office Online（以前称为 Office Web Apps）时位于美国境内，或者如果您使用 Active Directory 联合身份验证服务 (AD FS) 2.0 并设置策略以确保用户通过单一登录连接到服务，则临时缓存在 Office Online 中的所有客户内容将位于美国境内。
  
[如何使用本服务说明部分](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="office-365-us-government-and-third-party-services"></a>Office 365 美国政府版和第三方服务
<a name="BM4-3rdParty"> </a>

Office 365 可以将第三方应用程序集成到 SharePoint Online 站点、Skype for Business、Office 365 ProPlus 中的 Office 应用程序（如 Word、Excel、PowerPoint 和 Outlook）以及 Outlook Web App。此外，Office 365 还支持与第三方服务提供商集成。这些第三方应用程序和服务可能参与存储、传输和处理组织在 Office 365 基础结构外部的第三方系统上的客户数据，因此未涵盖在 Office 365 合规性和数据保护协议中。我们建议您在为组织评估这些服务的相应使用情况时，查看第三方提供的隐私和合规性声明。
  
[如何使用本服务说明部分](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="restricted-data-access-by-administrators"></a>管理员受限数据访问
<a name="BM5-Restricted"> </a>

Microsoft 管理员对 Office 365 美国政府版客户内容的访问权限仅限于美国公民。这些人员根据相关的政府标准进行背景调查。
  
||||
|:-----|:-----|:-----|
|**背景筛查** <br/> |**GCC** <br/> |**GCC 高和 Dod** <br/> |
|核实美国公民身份  <br/> |是  <br/> |是  <br/> |
|工作经历调查  <br/> |是  <br/> |是  <br/> |
|核实教育背景  <br/> |是  <br/> |是  <br/> |
|搜索社会安全号码 (SSN)  <br/> |是  <br/> |是  <br/> |
|犯罪记录调查（7 年）  <br/> |是  <br/> |是  <br/> |
|海外资产控制办公室 (OFAC) 名单  <br/> |是  <br/> |是  <br/> |
|工业安全局 (BIS) 名单  <br/> |是  <br/> |是  <br/> |
|根据 FBI 犯罪数据库调查指纹  <br/> |是  <br/> |是  <br/> |
|CJIS 犯罪背景调查  <br/> |是  <br/> |否  <br/> |
|基于 OPM 第 3 层调查的 DOD IT-2  <br/> |否  <br/> |仅限 DOD SRG L5 租户  <br/> |
   
[如何使用本服务说明部分](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="fasttrack-center-onboarding-assistance"></a>FastTrack 中心入职培训协助
<a name="BM5-Restricted"> </a>

使用 Office 365<sup>1</sup>FastTrack 中心收益，可以使用远程 FastTrack 专家做好 Office 365 环境使用和计划推出和您的组织内的使用情况。FastTrack 过程提供了入职培训和用户采用服务。 
  
载入包括：
  
- 核心入职培训-的任务所需的租户配置和与 Azure Active Directory (Azure AD) 集成，如果需要。核心入职培训还提供了基线入职培训其他合格的服务。
    
- 服务入职培训和迁移-服务入职培训任务启用租户中的方案。迁移数据 （包括电子邮件和文件） 介绍了[迁移数据](https://aka.ms/whatcanmigrate)。<sup>2</sup>
    
用户采用服务由多个任务组成，可提供指导以确保你的用户了解符合条件的服务，并可以使用它们推动业务价值。此协助与载入活动并行发生。
  
可以找到 FastTrack 中心过程的特定信息[此处](https://aka.ms/whatistheprocess)。有关的细分工作效率的角色及职责，请查看[FastTrack 职责](https://aka.ms/whatdoesftcdo)，以及[您的职责](https://aka.ms/whatdowedo)。
  
<sup>1</sup> ，则必须购买的[合格的计划](https://aka.ms/whocanbenefit)以接收 FastTrack 服务列表中至少 50 许可证 
  
<sup>2</sup>数据迁移服务供与 500 或多个许可证的 Office 365 租户。 
  
## <a name="data-migrations-performed-by-fasttrack"></a>由 FastTrack 执行数据迁移
<a name="BM5-Restricted"> </a>

选择[FastTrack](https://fasttrack.microsoft.com/)迁移好处客户需要授予对管理其数据迁移的团队访问权限。这些人员美国公民，进行以下背景检查之前的 Office 365 美国政府服务客户执行迁移。 
  
||||
|:-----|:-----|:-----|
|**背景筛查** <br/> |**GCC** <br/> |**GCC High 和 DoD** <br/> |
|核实美国公民身份  <br/> |是  <br/> |是  <br/> |
|工作经历调查  <br/> |是  <br/> |是  <br/> |
|核实教育背景  <br/> |是  <br/> |是  <br/> |
|社会保险号码 (SSN) 搜索  <br/> |是  <br/> |是  <br/> |
|犯罪记录调查（7 年）  <br/> |是  <br/> |是  <br/> |
   
[如何使用本服务说明部分](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="office-365-us-government-and-azure-government-expressroute"></a>Office 365 美国政府版和 Azure 政府 ExpressRoute
<a name="BM6-Express"> </a>

Office 365 美国政府版 客户可以使用 Azure Government ExpressRoute 服务单独连接到支持的 Office 365 服务，而不再通过公共 Internet 连接服务。
  
有关受支持的提供商、定价模型及更多详细信息，请查看 [Azure ExpressRoute 信息](http://go.microsoft.com/fwlink/?LinkID=798220&amp;clcid=0x409)。
  
有关 Office 365 Azure ExpressRoute 支持的详细信息，请参阅 [Office 365 的 Azure ExpressRoute ](http://go.microsoft.com/fwlink/?LinkID=798216&amp;clcid=0x409)。
  
[如何使用本服务说明部分](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="system-requirements"></a>系统要求
<a name="BM9-Requirements"> </a>

有关 Office 365 美国政府版 计划的系统要求，请参阅 [office.com](http://go.microsoft.com/fwlink/?LinkID=626095&amp;clcid=0x409) 产品网站上的 [Office 的系统要求](http://go.microsoft.com/fwlink/?LinkID=509817&amp;clcid=0x409)。 
  
[如何使用本服务说明部分](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="security-amp-compliance-center"></a>安全&amp;合规性中心
<a name="BM9-Requirements"> </a>

有关安全性信息&amp;合规性中心和指向其他信息和可用性，请参阅[Office 365 安全性&amp;合规性中心](../../office-365-platform-service-description/office-365-securitycompliance-center.md)。
  
## <a name="service-availability-for-each-plan"></a>每个计划的服务可用性
<a name="BM9-Requirements"> </a>

每个 Office 365 计划都包括许多单个服务，例如 Exchange Online 和 SharePoint Online。下表显示了每个 Office 365 美国政府版 计划中可用的服务。
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**Office 365 服务** <br/> |**Office 365 美国政府版 G1** <br/> |**Office 365 美国政府版 G3** <br/> |**Office 365 美国政府 G5** <br/> |**Office 365 美国政府 F1** <br/> |
|Office Online  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Office 365 ProPlus  <br/> |否 <br/> |是 <br/> |是 <br/> |否  <br/> |
|Exchange Online  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Exchange Online Protection  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|SharePoint Online  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|OneDrive for Business  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Skype for Business (即时消息&amp;状态)  <br/> |是<sup>1</sup> <br/> |是  <br/> |是  <br/> |是<sup>1</sup> <br/> |
| 语音-电话系统，音频会议  <br/> |否<sup>2、3</sup> <br/> |否<sup>2、3</sup> <br/> |是<sup>3，5</sup> <br/> |否  <br/> |
|Power BI Pro  <br/> |没有<sup>2</sup> <br/> |没有<sup>2</sup> <br/> |是  <br/> |没有<sup>2</sup> <br/> |
|Project Online  <br/> |没有<sup>2</sup> <br/> |没有<sup>2</sup> <br/> |没有<sup>2</sup> <br/> |没有<sup>2</sup> <br/> |
|Yammer Enterprise  <br/> |没有<sup>4</sup> <br/> |没有<sup>4</sup> <br/> |没有<sup>4</sup> <br/> |没有<sup>4</sup> <br/> |
   
> <sup>1</sup>是可用于所有客户的业务基本 Skype。业务桌面客户端的 Skype 是为 Office 365 计划，其中包括 Skype 业务 online 提供状态、 即时消息和会议功能的本地安装应用程序。Office 365 ProPlus、 G3 和 G5 包含完整的 Skype 应用程序，包括其他功能，如高级的电话支持、 存档和合规性功能。必须为每个用户分配业务 Online 许可 Skype。<br/><sup>2</sup>不包含但可以作为单独的附加项进行购买。Project Online 包括 Project Online Desktop Client 作为订阅的一部分。<br/> <sup>3</sup> GCC 高或 DoD 计划，但即将推出中尚未提供。 
<br/><sup>4</sup> yammer Enterprise 不是 Office 365 美国政府的组件，但可能获取免费的每个用户的独立报价许可 for Office 365 中 GCC。此服务是当前仅限于购买 Office 365 GCC 下企业协议和企业订阅协议的客户。Yammer GCC 高或 DoD 中不可用。<br/><sup>5</sup>调用规划是加载项。 
  
## <a name="platform-features"></a>平台功能
<a name="BM7-Platform"> </a>

下表列出了Office 365 美国政府版 计划中所提供的平台功能和服务。
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 美国政府版 G1** <br/> |**Office 365 美国政府版 G3** <br/> |**Office 365 美国政府 G5** <br/> |**Office 365 美国政府 F1** <br/> |
|**Office 365 管理** <br/> |||||
|通过使用 Office 365 管理中心管理 Office 365  <br/> |是<sup>16</sup> <br/> |是<sup>16</sup> <br/> |是  <br/> |是<sup>16</sup> <br/> |
|从 Office 365 中管理核心服务设置  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|使用 Windows PowerShell 管理 Office 365  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|使用 Azure 信息保护保护内容  <br/> |没有<sup>1</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup>  <br/> |没有<sup>1</sup> <br/> |
|**[Office 365 套件功能](../../office-365-platform-service-description/office-365-suite-features.md)** <br/> |**Office 365 美国政府版 G1** <br/> |**Office 365 美国政府版 G3** <br/> |**Office 365 美国政府 G5** <br/> |**Office 365 美国政府 F1** <br/> |
|Microsoft 预订  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |
|Microsoft Flow  <br/> |是<sup>11</sup> <br/> |是<sup>11</sup> <br/> |是<sup>11</sup> <br/> |是<sup>11</sup> <br/> |
|Microsoft Forms  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|Microsoft Graph API  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Microsoft MyAnalytics  <br/> |没有<sup>9，12，15</sup> <br/> |没有<sup>9，12，15</sup> <br/> |是<sup>9，15</sup> <br/> |没有<sup>9，12，15</sup> <br/> |
|Microsoft Planner  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|Microsoft PowerApps  <br/> |是<sup>11</sup> <br/> |是<sup>11</sup> <br/> |是<sup>11</sup> <br/> |是<sup>11</sup> <br/> |
|Microsoft StaffHub  <br/> |是<sup>17</sup> <br/> |是<sup>17</sup> <br/> |是<sup>17</sup> <br/> |是<sup>17</sup> <br/> |
|Microsoft Stream  <br/> |是<sup>11</sup> <br/> |是<sup>11</sup> <br/> |是<sup>11</sup> <br/> |否  <br/> |
|Microsoft Sway  <br/> |是<sup>17</sup> <br/> |是<sup>17</sup> <br/> |是<sup>17</sup> <br/> |是<sup>17</sup> <br/> |
|Microsoft Teams  <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |
|Office Delve  <br/> |是<sup>17</sup> <br/> |是<sup>17</sup> <br/> |是  <br/> |是<sup>17</sup> <br/> |
|Office 365 组  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Microsoft Stream  <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |否  <br/> |
|**[用户帐户管理](../../office-365-platform-service-description/user-account-management.md)** <br/> |**Office 365 美国政府版 G1** <br/> |**Office 365 美国政府版 G3** <br/> |**Office 365 美国政府 G5** <br/> |**Office 365 美国政府 F1** <br/> |
|云身份  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|联合身份（单点登录）  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|多重身份验证  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|电话因素身份验证  <br/> |是<sup>9</sup> <br/> |是<sup>9</sup> <br/> |是  <br/> |是<sup>9</sup> <br/> |
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
|**[域](../../office-365-platform-service-description/domains.md)** <br/> |**Office 365 美国政府版 G1** <br/> |**Office 365 美国政府版 G3** <br/> |**Office 365 美国政府 G5** <br/> |**Office 365 美国政府 F1** <br/> |
|添加第二级自定义域，如 fourthcoffee.com  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|添加第三级自定义域，如 marketing.fourthcoffee.com是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|添加多达 900 个自定义域  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|自定义域需要域所有权验证  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[服务运行状况和连续性](../../office-365-platform-service-description/service-health-and-continuity.md)** <br/> |**Office 365 美国政府版 G1** <br/> |**Office 365 美国政府版 G3** <br/> |**Office 365 美国政府 G5** <br/> |**Office 365 美国政府 F1** <br/> |
|在**服务运行状况**或**服务状态**页上可用的状态信息  <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |
|Office 365 管理中心仪表板中显示单个警报状态  <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |
|**服务运行状况**RSS 源  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[报告](../../office-365-platform-service-description/reports.md)** <br/> |**Office 365 美国政府版 G1** <br/> |**Office 365 美国政府版 G3** <br/> |**Office 365 美国政府 G5** <br/> |**Office 365 美国政府 F1** <br/> |
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
|**[服务更新](../../office-365-platform-service-description/service-updates.md)** <br/> |**Office 365 美国政府版 G1** <br/> |**Office 365 美国政府版 G3** <br/> |**Office 365 美国政府 G5** <br/> |**Office 365 美国政府 F1** <br/> |
|向所有客户提供的定期更新  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|通知发送给 消息中心（当需要操作时）  <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |是<sup>15</sup> <br/> |
|针对某些服务更新的 Roadmap.office.com  <br/> |没有<sup>10、 13</sup> <br/> |没有<sup>10、 13</sup> <br/> |没有<sup>10、 13</sup> <br/> |没有<sup>10、 13</sup> <br/> |
|选项打开目标发行版  <br/> |是<sup>10</sup> <br/> |是<sup>10</sup> <br/> |是<sup>10</sup> <br/> |是<sup>10</sup> <br/> |
|**[帮助和培训](../../office-365-platform-service-description/help-and-training.md)** <br/> |**Office 365 美国政府版 G1** <br/> |**Office 365 美国政府版 G3** <br/> |**Office 365 美国政府 G5** <br/> |**Office 365 美国政府 F1** <br/> |
|联机帮助  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|社区  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|其他自助资源  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|自学培训  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[网络](../../office-365-platform-service-description/networking.md)** <br/> |**Office 365 美国政府版 G1** <br/> |**Office 365 美国政府版 G3** <br/> |**Office 365 美国政府 G5** <br/> |**Office 365 美国政府 F1** <br/> |
|IPv4 和 IPv6 协议  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**信任** <br/> |**Office 365 美国政府版 G1** <br/> |**Office 365 美国政府版 G3** <br/> |**Office 365 美国政府 G5** <br/> |**Office 365 美国政府 F1** <br/> |
|**[隐私、安全性和透明度](../../office-365-platform-service-description/privacy-security-and-transparency.md)** <br/> |||||
|高级数据治理  <br/> |没有<sup>12</sup> <br/> |没有<sup>12</sup> <br/> |是 <br/> |没有<sup>12</sup> <br/> |
|云应用安全  <br/> |没有<sup>11、 12</sup> <br/> |没有<sup>11、 12</sup> <br/> |是<sup>11</sup> <br/> |没有<sup>11、 12</sup> <br/> |
|高级威胁防护  <br/> |没有<sup>12</sup> <br/> |没有<sup>12</sup> <br/> |是  <br/> |没有<sup>12</sup> <br/> |
|客户密码箱  <br/> |没有<sup>9，12，15</sup> <br/> |没有<sup>9，12，15</sup> <br/> |是<sup>9，15</sup> <br/> |没有<sup>9，12，15</sup> <br/> |
|Office 365 高级电子数据展示  <br/> |没有<sup>12</sup> <br/> |没有<sup>12</sup> <br/> |是  <br/> |没有<sup>12</sup> <br/> |
|安全功能分数<sup>14</sup> <br/> |是<sup>9，15</sup> <br/> |是<sup>9</sup> <br/> |是<sup>9，15</sup> <br/> |是<sup>9，15</sup> <br/> |
|Office 邮件加密  <br/> |否  <br/> |是 <br/> |是 <br/> |否  <br/> |
|威胁智能  <br/> |没有<sup>12</sup> <br/> |没有<sup>12</sup> <br/> |是 <br/> |没有<sup>12</sup> <br/> |
|**[合规性 [ServiceDesc]](../../office-365-platform-service-description/compliance-servicedesc.md)** <br/> |||||
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
|**[BlackBerry](../../office-365-platform-service-description/blackberry.md)** <br/> |**Office 365 美国政府版 G1** <br/> |**Office 365 美国政府版 G3** <br/> |**Office 365 美国政府 G5** <br/> |**Office 365 美国政府 F1** <br/> |
|是  <br/> |没有<sup>2</sup> <br/> |没有<sup>2</sup> <br/> |没有<sup>2</sup> <br/> |没有<sup>2</sup> <br/> |
|**[合作伙伴](../../office-365-platform-service-description/partners.md)** <br/> |||||
|是  <br/> |没有<sup>11</sup> <br/> |没有<sup>11</sup> <br/> |没有<sup>11</sup> <br/> |没有<sup>11</sup> <br/> |
|是  <br/> |没有<sup>11</sup> <br/> |没有<sup>11</sup> <br/> |没有<sup>11</sup> <br/> |没有<sup>11</sup> <br/> |
|**[服务级别协议](../../office-365-platform-service-description/service-level-agreement.md)** <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|**[产品使用权限](../../office-365-platform-service-description/product-use-rights.md)** <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
   
> <sup>1</sup> azure 信息保护不包括在内，但可以作为单独的附加项购买，并将启用受支持的信息权限管理 (IRM) 功能。某些 Azure 信息保护功能需要订阅 Office 365 ProPlus，这是不包含在 Office 365 美国政府版 G1 或 Office 365 美国政府 F1。><br/><sup>2</sup>现有 BBCS 和 BIS 客户可以继续使用本服务。新客户不被接受。<br/><sup>3</sup> 如果使用目录同步，您必须使用 Active Directory（而不是 Office 365 门户）或使用 Windows PowerShell 的 Azure Active Directory 模块来删除帐户或更改密码。 
<br/><sup>4</sup> 如果使用密码同步，用户必须更改本地 Active Directory 中的密码。 
<br/><sup>5</sup> 若要了解如何为用户设置自助服务密码管理策略，请参阅 [管理 Azure AD 中的密码](https://azure.microsoft.com/en-us/documentation/articles/active-directory-manage-passwords/)。 <br/><sup>6</sup>可以只有一个公共网站与 Office 365，除非您已从早期版本的 Office 365 升级。在这种情况下，您有两个公共网站，但仅有一种可以承载与自定义域名。有关使用企业订阅的两个网站的详细信息，请参阅[使用两个 Office 365 公共网站](https://go.microsoft.com/fwlink/p/?LinkID=271589)。如果您有其他订阅，了解详细信息，[了解有关承载合作伙伴网站和 Office 365 中的公共网站](https://go.microsoft.com/fwlink/p/?LinkID=325009)的公共网站。<br/><sup>7</sup>术语折扣购的减少座位可能会受到早期终止费用。这不是适用于按月付费的订阅。<br/><sup>8</sup>以下计划不支持从 Office 365 管理中心的许可证座位更改： > Office 365 美国政府版 G1 > Office 365 美国政府版 G3 > Office 365 美国政府版 K1 <br/><sup>9</sup>尚未提供 GCC 高，但即将提供。
<br/><sup>10</sup>的 Office 365 美国政府版 G1、 G3 和 f1 键，目标发行版和 Office 365 的业务路线图应用;但是，可能有一些差异内容还是由于[合规性要求](https://products.office.com/en-us/business/office-365-trust-center-cloud-computing-security?legRedir=true&amp;CorrelationId=eeaccba9-85ea-4fa8-9c84-3fb4c9e1547b&amp;tab=7a3a6365-14c0-81ac-34ff-f4a416599263)的特定服务更新的延迟。
<br/><sup>11</sup>尚未提供在 Office 365 美国政府版产品，但即将提供。 ><br/><sup>12</sup>不包含，但可以作为 GCC 在单独的附加项进行购买。 
<br/>不支持 Office 365 美国政府版产品<sup>13</sup> 。 
<br/><sup>14</sup>可在[https://securescore.office.com](https://securescore.office.com)。需要管理员权限。有关详细信息，请参阅[介绍 Office 365 安全分数](https://go.microsoft.com/fwlink/?linkid=836894)。<br/><sup>15</sup> DoD 环境中，但即将推出中尚未提供。 
<br><sup>16</sup> Admin Center 不包括使用情况分析，在 DoD 或 GCC 高环境中
<br><sup>17</sup>不支持 GCC 高或 DoD 环境
  
[如何使用本服务说明部分](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="office-application-features"></a>Office 应用程序功能
<a name="BM11-Applications"> </a>

下表显示 Office 365 美国政府版计划中所提供的 Office 应用程序功能。
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 美国政府版 G1** <br/> |**Office 365 美国政府版 G3** <br/> |**Office 365 美国政府 G5** <br/> |**Office 365 美国政府 F1** <br/> |
|**Office 应用程序** <br/> |||||
|[Microsoft Word](../../office-applications-service-description/office-applications.md#microsoft-word) <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Microsoft Excel](../../office-applications-service-description/office-applications.md#microsoft-excel) <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Microsoft PowerPoint](../../office-applications-service-description/office-applications.md#microsoft-powerpoint) <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Microsoft OneNote](../../office-applications-service-description/office-applications.md#microsoft-onenote) <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Microsoft Outlook](../../office-applications-service-description/office-applications.md#microsoft-outlook) <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Microsoft Publisher](../../office-applications-service-description/office-applications.md#microsoft-publisher) <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Microsoft Access](../../office-applications-service-description/office-applications.md#microsoft-access) <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Skype for Business](../../office-applications-service-description/office-applications.md#skype-for-business) <br/> |是<sup>3</sup> <br/> |是  <br/> |是  <br/> |是<sup>3</sup> <br/> |
|[适用于 Office 365 的 Office for Mac](https://support.office.com/en-us/article/General-requirements-for-Outlook-2016-for-Mac-A07A593D-B383-4906-A6C1-962D5543ED57?ui=en-US&amp;rs=en-US&amp;ad=US) <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|[Office Mobile for iPad/iPhone](../../office-applications-service-description/office-applications.md#office-mobile-for-ipadiphone) <br/> |否  <br/> |是<sup></sup> <br/> |是<sup></sup> <br/> |否  <br/> |
|[Office Mobile for Android](../../office-applications-service-description/office-applications.md#office-mobile-for-android) <br/> |否  <br/> |是<sup></sup> <br/> |是<sup></sup> <br/> |否  <br/> |
|[Office Mobile for Windows Phone](../../office-applications-service-description/office-applications.md#office-mobile-for-windows-phone) <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|适用于 Windows 10 平板电脑的 Office Mobile <br/> |否  <br/> |是<sup></sup> <br/> |是<sup></sup> <br/> |否  <br/> |
|Outlook 开发 iOS 和 Android<sup>5、 4</sup>  <br/> |是 <br/> |是 <br/> |是 <br/> |是 <br/> |
|**企业价值** <br/> |**Office 365 美国政府版 G1** <br/> |**Office 365 美国政府版 G3** <br/> |**Office 365 美国政府 G5** <br/> |**Office 365 美国政府 F1** <br/> |
|每个用户可在 5 台 PC 或 Mac 上进行安装  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|自动化用户帐户配置  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|多语言用户界面  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|客户端推送部署  <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|内部部署 Exchange 的客户端支持  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|内部部署 SharePoint 的客户端支持  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|控制软件更新  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|数据库比较  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|桌面虚拟化  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|Excel 电子表格比较  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|Excel 电子表格查询  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|Exchange Online 和 SharePoint Online 存档和合规性  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|组策略支持  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|信息权限管理使用 Azure 信息保护  <br/> |没有<sup>1</sup> <br/> |是<sup>6</sup> <br/> |是<sup>6</sup> <br/> |没有<sup>1</sup> <br/> |
|使用 Windows Server AD RMS 的信息权限管理  <br/> |是<sup>2</sup> <br/> |是<sup>2</sup> <br/> |是<sup>2</sup> <br/> |是<sup>2</sup> <br/> |
|Office 插件、ActiveX 和 BHO 支持  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|在 SharePoint Server、SharePoint Online、OneDrive for Business 和 Office 365 上对笔记本的 OneNote 客户端访问  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|Office Lens  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |
|Office 遥测  <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|客户端应用程序的脱机支持  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|优化并排客户端安装  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|Power Map for Excel  <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|Power Pivot for Excel  <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|Power Query for Excel  <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|Power View for Excel  <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|漫游设置  <br/> |否  <br/> |是<sup></sup> <br/> |是<sup></sup> <br/> |否  <br/> |
|共享计算机激活  <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|支持阻止基于云的文件存储  <br/> |否  <br/> |是  <br/> |是  <br/> |否  <br/> |
|版本升级  <br/> |否  <br/> |是<sup>4</sup> <br/> |是<sup>4</sup> <br/> |否  <br/> |
|批量激活 (KMS/MAK)  <br/> |否  <br/> |否  <br/> |否  <br/> |否  <br/> |
   
> <sup>1</sup> azure 信息保护不包括在内，但可以作为单独的附加项购买，并将启用受支持的信息权限管理 (IRM) 功能。某些 Azure 信息保护功能需要订阅 Office 365 ProPlus，这是不包含在 Office 365 美国政府版 G1 或 Office 365 美国政府 F1。<br/><sup>2</sup> Windows Server AD RMS 是一款本地服务器，必须在单独购买并管理以启用支持的 IRM 功能。 
<br/><sup>3</sup>的业务基本 Skype 是可用于所有客户。业务桌面客户端的 Skype 是为 Office 365 计划，其中包括 Skype 业务 online 提供状态、 即时消息和会议功能的本地安装应用程序。Office 365 ProPlus 和 Office 365 企业版 E3 包括完整的 Skype 应用程序，包括其他功能，如高级的电话支持、 存档和合规性功能。必须为每个用户分配业务 Online 许可 Skype。Lync 基本功能的详细信息，请参阅[Skype 的业务联机客户端比较表](https://technet.microsoft.com/en-us/library/gg425836%28v=ocs.15%29.aspx)。<br/><sup>4</sup>尚未提供 GCC 高或 DoD 环境，但即将提供。
<br/><sup>5</sup>的详细信息，请参阅[使用 Outlook 中的 iOS 和政府社区云 Android](https://docs.microsoft.com/en-us/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud) 。
  <br/><sup>6</sup>尚未提供 Office 365 DoD 环境中，但即将提供。
<br/><br/>[如何使用本服务说明部分](office-365-us-government.md#how-to-use-this-service-description-section)
