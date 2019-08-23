---
title: Office 365 GCC 高和 DoD
ms.author: danarl
author: danarl
manager: dianap
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0821204d-5515-43de-8ed6-ab84bd1693c1
description: 为了满足美国国防部的独特和不断发展的要求, 以及持有或处理 DoD 控制的未分类信息 (CUI) 或遵守了 Arm 规章 (ITAR) 的国际流量的承包商, Microsoft 提供了GCC 高和 DoD 环境。 为确保有资格建立环境，感兴趣的组织可以通过批量许可完成验证流程。 暂不提供试用。
ms.openlocfilehash: 65a8362ba02fe000c2f0f6a4c172b3067a5663e6
ms.sourcegitcommit: f7a5c67a0fb1ab100d471bd190e0a58628e76ce5
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/23/2019
ms.locfileid: "36568115"
---
# <a name="office-365-gcc-high-and-dod"></a>Office 365 GCC 高和 DoD

为了满足美国国防部的独特和不断发展的要求, 以及持有或处理 DoD 控制的未分类信息 (CUI) 或遵守了 Arm 规章 (ITAR) 的国际流量的承包商, Microsoft 提供了GCC 高和 DoD 环境。 为确保有资格建立环境，感兴趣的组织可以通过批量许可完成验证流程。 暂不提供试用。 
  
若要了解详细信息或启动验证流程，请与你的帐户团队或首选合作伙伴联系。 有关如何购买的详细信息, 请参阅[Microsoft 365 政府-如何购买](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy)。
  
## <a name="how-to-use-this-service-description-section"></a>如何使用本服务说明部分

Office 365 美国政府版 服务说明旨在作为常规 Office 365 服务说明的整体进行说明。它定义了唯一承诺以及与 Office 365 企业版产品的差异。
  
## <a name="compliance"></a>合规性

GCC High and DoD 满足以下认证和资格鉴定的合规性要求: 
  
- 符合 Moderate 基准（FedRAMP Moderate）的联邦风险和授权管理计划，其中包括美国国家标准技术研究院 (NIST) 特种出版物 800-53 中所述的这些安全控制和增强控制。
    
- 高至影响级别 5 (L5) 的信息的美国国防部云计算安全要求指南 (SRG) 的安全控制和增强控制。
    
Office 365 的国防部订阅者将从符合 DOD SRG L5 的 DOD 独家环境中接收服务。 非防御部门订阅者将接收来自美国政府防御环境的服务, 这些服务在 L5 进行评估, 但使用 L4 分段。
  
## <a name="background-screening"></a>后台筛选

Office 365 员工不具有对 GCC 高和 DoD 生产的长期访问权限。 任何请求临时权限提升（以获得客户内容访问权限）的工作人员都必须先通过以下背景调查。
  
|||
|:-----|:-----|
|**Microsoft 人员筛选和背景检查**<sup>1</sup> <br/> |**说明** <br/> |
|美国公民身份  <br/> |核实美国公民身份  <br/> |
|工作经历调查  <br/> |核实七 (7) 年的工作经历  <br/> |
|核实教育背景  <br/> |核实最高学历  <br/> |
|搜索社会安全号码 (SSN)  <br/> |核实所提供的 SSN 是否有效  <br/> |
|犯罪记录调查  <br/> |调查州、县、地方级和联邦级七 (7) 年的重罪和轻罪犯罪记录  <br/> |
|海外资产控制办公室 (OFAC) 名单  <br/> |核实是否被归入美国财政部发布的美国公民不得与之有贸易或金融往来的团体名单  <br/> |
|工业安全局 (BIS) 名单  <br/> |核实是否被归入美国商务部发布的禁止从事出口活动的个人和实体名单  <br/> |
|国防贸易管制办公室 (DDTC) 禁止人员名单  <br/> |核实是否被归入美国国务院发布的禁止从事与国防工业有关的出口活动的个人和实体名单  <br/> |
|指纹检查  <br/> |根据 FBI 数据库进行指纹背景调查  <br/> |
|国防部 IT-2  <br/> |请求对客户数据提升的权限或对国防部 SRG L5 服务功能的特权管理访问权限的员工必须通过国防部 IT-2 裁定，该裁定基于成功的 OPM 第 3 层调查。  <br/> |

<sup>1</sup>仅适用于具有临时或有权访问托管在 OFFICE 365 美国 GCC (高或 DOD 云) 中的客户内容的人员。
## <a name="feature-nuances-based-on-compliant-cloud-architecture"></a>基于符合性云体系结构的功能细微

在 GCC 高和 DoD 环境中的 Office 365 订阅包括核心 Exchange Online、SharePoint Online 和 Skype for Business 功能。 如果基础结构的认证和资格鉴定增多, 则一般商业版 Office 365 产品与 GCC 高和 DoD 中提供的功能之间存在一些功能差异。
  
### <a name="exchange-online"></a>Exchange Online

 **适用于本地 ip-pbx 的 Exchange Online 统一消息支持**-支持将本地 IP-pbx 系统与 Exchange Online 统一消息集成在 GCC 高级和 DoD 订阅中不受支持。 
  
### <a name="sharepoint-online"></a>SharePoint Online

 **文档共享**-SharePoint Online 和 OneDrive for business 实现了用户和团队之间的无缝信息共享和协作。 文档所有者可以通过 web 界面或 Outlook 中的新式附件向其他用户提供对其文档的访问权限。 共享文档时, 有多个选项可用于管理权限: 
  
1. 仅我
    
2. 公司内的任何人
    
3. 具有此链接的任何人
    
4. 特定人员
    
在 GCC 高或 DoD 环境中使用 SharePoint Online 和 OneDrive for business 的客户可以让文档保持专用 (第一个选项), 与组织中的任何人共享 (第二个选项), 与任何有该文档链接的人共享 (第三个选项), 以及与特定人员共享 (第四个选项)。 这些选项也可以基于租户级别的访问控制进行限制。

当与特定人员共享时, SharePoint 将验证用户是否为链接的预期收件人, 方法是向其发送一次性密码到共享的电子邮件地址。 但是, 当与另一个 GCC-高租户共享 GCC 高租户时, 将在 Azure AD 中为该收件人创建来宾帐户, 并且他们将使用用户名和密码登录。
  
其他示例:
  
- GCC High 租户 A 可以与 GCC 高租户 B 共享, 而 B 用户使用 Azure AD 用户名和密码登录。
    
- 非 GCC 高租户 C 可以与 GCC 高租户 A 或 B 共享, A 或 B 用户使用一次性密码进行登录。
    
- GCC High 租户 A 或 B 可以与非 GCC 高租户 C 共享, 而 C 用户则使用一次性密码登录。
    
此外, 不支持附加到用户配置文件的非 GCC 高电子邮件地址, 也不允许发送警报电子邮件。 例如, 在本地用户 A 分配了 Gmail 电子邮件地址, 然后同步到 Azure GCC High 租户。 用户 A 导航到库并为任何更改创建警报。 将不会向 Gmail 地址发送通知。
  
 **外部应用程序访问**-与外部应用程序 (如外接程序的数据源) 的连接仅限于位于 GCC High and DoD 支持的系统安全边界内的源。 
  
 **Business Connectivity Services** -BCS 功能受支持的连接方案, 其中数据源在云服务的安全边界内仍可访问。 
  
 **沙盒解决方案**-此功能已被弃用, 不可用。 应将任何沙盒解决方案迁移到[SharePoint 加载项扩展性模型]( https://msdn.microsoft.com/library/office/fp179930.aspx)。
  
### <a name="skype-for-business-online"></a>Skype for Business Online

 **PSTN 呼叫&amp; pstn 会议**-由于需要使用面向电话服务的公用电话交换网 (PSTN), 因此在 GCC 高和 DOD 中, Pstn &amp;呼叫 pstn 会议服务目前不可用。 
  
### <a name="identity"></a>标识

使用联合身份模型的多重身份验证允许使用 PIV 和 CAC 卡。
  
### <a name="yammer"></a>Yammer

Yammer Enterprise 在 GCC 高和 DoD 环境中不可用。
  
## <a name="customer-support"></a>客户支持

如果使用 Office 365 GCC High/DOD 时, Microsoft 会提醒您不要将任何受控制、敏感或机密的信息与客户支持人员共享, 在您确认支持代理的授权以查看或访问此类数据。

Microsoft 致力于保护你的[隐私](https://privacy.microsoft.com/privacystatement)。 但是, 服务资格鉴定边界中不包含 Office 365 GCC High/DoD 支持, 也不提供 FedRAMP、DOD SRG、ITAR、IRS 1075 或 CJIS 数据处理合规性保证。
