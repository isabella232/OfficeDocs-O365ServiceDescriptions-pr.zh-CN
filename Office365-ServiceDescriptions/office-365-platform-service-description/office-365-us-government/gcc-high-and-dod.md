---
title: Office 365 GCC 高和 DoD
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0821204d-5515-43de-8ed6-ab84bd1693c1
description: 了解与 Office 365 商业环境相比的 Office 365 GCC 高和 DoD 环境的独特承诺和差异。
ms.openlocfilehash: 44d66557f426ab236460affd61fbf1970c7f25e6
ms.sourcegitcommit: 8d17d5df1427a817df15d45eae5f2f3e48d7b12d
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/23/2020
ms.locfileid: "48214331"
---
# <a name="office-365-gcc-high-and-dod"></a>Office 365 GCC 高和 DoD

为了满足美国国防部的独特和不断发展的要求，以及持有或处理 DoD 控制的未分类信息的承包商， (CUI) 或遵守 ITAR 规章中的国际流量 () ，Microsoft 提供了 GCC 的高和 DoD 环境。 为确保有资格建立环境，感兴趣的组织可以通过批量许可完成验证流程。 暂不提供试用。 
  
与你的帐户团队或首选合作伙伴联系，了解详细信息或启动验证流程。 有关如何购买的详细信息，请参阅 [Microsoft 365 政府-如何购买](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy)。
  
## <a name="how-to-use-this-service-description-section"></a>"如何使用此服务说明" 部分

Office 365 美国政府版服务说明旨在用作常规 Office 365 服务说明的覆盖。 它定义了唯一承诺以及与 Office 365 企业版产品的差异。
  
## <a name="compliance"></a>合规性

GCC High and DoD 满足以下认证和资格鉴定的合规性要求： 
  
- FedRAMP 高的联邦风险和授权管理计划，包括这些安全控制和控制增强，如美国国家标准和技术协会 (NIST) 特殊出版物800-53 中所述。
    
- 高至影响级别 5 (L5) 的信息的美国国防部云计算安全要求指南 (SRG) 的安全控制和增强控制。
    
Office 365 的国防部订阅者将从符合 DOD SRG L5 的 DOD 独家环境中接收服务。 非防御部门订阅者将接收来自美国政府防御环境的服务，这些服务在 L5 进行评估，但使用 L4 分段。
  
## <a name="background-screening"></a>后台筛选

Office 365 员工不具有对 GCC 高和 DoD 生产的长期访问权限。 任何请求临时权限提升（以授予客户内容访问权限）的人员都必须先通过以下背景检查。
  
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

<sup>1</sup> 仅适用于具有临时或有权访问托管在 OFFICE 365 美国 GCC （高或 DOD 云）中的客户内容的人员。
## <a name="feature-nuances-based-on-compliant-cloud-architecture"></a>基于符合性云体系结构的功能细微

在 GCC 高和 DoD 环境中的订阅包括核心 Exchange Online、SharePoint 和 Skype for Business 功能。 如果基础结构的认证和资格鉴定增多，则一般商业版 Office 365 产品与 GCC 高和 DoD 中提供的功能之间存在一些功能差异。
  
### <a name="exchange-online"></a>Exchange Online

 **适用于本地 ip-pbx 的 Exchange Online 统一消息支持** -支持将本地 IP-pbx 系统与 Exchange Online 统一消息集成在 GCC 高级和 DoD 订阅中不受支持。 
  
### <a name="file-sharing"></a>文件共享

用户可以使用多个选项在 SharePoint 和 OneDrive 中共享文件和文件夹。 所有选项在 GCC 的高和 DoD 环境中都可用。 有关管理这些选项的详细信息，请参阅 [管理共享设置](/sharepoint/turn-external-sharing-on-or-off)。 在 gcc 中，高的用户将能够仅与 GCC 中的其他组织共享。 此外，不支持附加到用户配置文件的非 GCC 高电子邮件地址，也不允许发送警报电子邮件。 例如，在本地用户 A 分配了 Gmail 电子邮件地址，然后同步到 Azure GCC 高组织。 用户 A 导航到库并为任何更改创建警报。 将不会向 Gmail 地址发送通知。

> [!NOTE]
> GCC-高的用户目前无法与非 GCC 的高组织中的用户共享。

[文件请求](https://support.office.com/article/f54aa7f8-2589-4421-b351-d415fc3b83af) 不适用于 Office 365 政府版。

### <a name="skype-for-business-online"></a>Skype for Business Online

 **PSTN 呼叫 &amp; PSTN 会议** -由于需要使用面向电话服务的公开交换电话网络 (pstn) ， &amp; 因此在 GCC 高和 DoD 中，pstn 呼叫 pstn 会议服务目前不可用。

### <a name="microsoft-teams"></a>Microsoft Teams

**通过直接路由)  (的电话系统和音频会议 **：通过直接路由传递针对 GCC 高和 DoD 环境的电话系统和音频会议。 有关详细信息，请参阅此处的服务级别文档：

- [通过直接路由的电话系统](https://docs.microsoft.com/microsoftteams/here-s-what-you-get-with-phone-system)
- [适用于 GCC High 和 DoD 且含直接路由的音频会议](https://docs.microsoft.com/microsoftteams/audio-conferencing-with-direct-routing-for-gcch-and-dod)

### <a name="identity"></a>标识

使用联合身份模型的多重身份验证允许使用 PIV 和 CAC 卡。
  
### <a name="yammer"></a>Yammer

Yammer Enterprise 在 GCC 高和 DoD 环境中不可用。
  
## <a name="customer-support"></a>客户支持

在使用 Office 365 GCC High/DOD 时，Microsoft 会提醒您不要将任何受控制的敏感信息或机密信息作为支持事件的一部分共享，除非您确认支持代理的授权才能查看或访问此类数据。

Microsoft 致力于保护你的 [隐私](https://privacy.microsoft.com/privacystatement)) 。 但是，服务资格鉴定边界中不包含 Office 365 GCC High/DoD 支持，也不提供 FedRAMP、DOD SRG、ITAR、IRS 1075 或 CJIS 数据处理合规性保证。
