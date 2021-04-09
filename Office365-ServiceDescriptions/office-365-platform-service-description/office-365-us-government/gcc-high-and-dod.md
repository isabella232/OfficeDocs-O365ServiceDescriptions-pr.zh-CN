---
title: Office 365 GCC High 和 DoD
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0821204d-5515-43de-8ed6-ab84bd1693c1
description: 了解与 Office 365 商业环境相比 Office 365 GCC High 和 DoD 环境的独特承诺和差异。
ms.openlocfilehash: 5446d5d1e6e10649a75f001c92f0d970e2fae842
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653454"
---
# <a name="office-365-gcc-high-and-dod"></a>Office 365 GCC High 和 DoD

为满足美国国防部独特的且不断发展的要求，以及拥有或处理 DoD 控制的未分类信息 (CUI) 或受国际武器贸易条例 (ITAR) 限制的承包商的要求，Microsoft 提供 GCC High 和 DoD 环境。 为确保有资格建立环境，感兴趣的组织可以通过批量许可完成验证流程。 暂不提供试用。 
  
联系你的帐户团队或首选合作伙伴，了解更多信息或启动验证流程。 若要详细了解如何购买，请参阅 Microsoft [365 政府版 - 如何购买](./microsoft-365-government-how-to-buy.md)。
  
## <a name="how-to-use-this-service-description"></a>如何使用本服务说明

Office 365 美国政府版服务说明旨在作为常规 Office 365 服务说明的覆盖层。 它定义了与 Office 365 企业版产品/服务相比的独特承诺和差异。
  
## <a name="compliance"></a>合规性

GCC High 和 DoD 符合以下认证和资格鉴定的合规性要求： 
  
- FedRAMP High 的联邦风险和授权管理计划，包括美国国家标准和技术协会 (NIST) 800-53 中概述的安全控制和增强功能。
    
- 高至影响级别 5 (L5) 的信息的美国国防部云计算安全要求指南 (SRG) 的安全控制和增强控制。
    
Office 365 的国防部订阅者将收到来自 DOD 独占环境（符合 DOD SRG L5）提供的服务。 非国防部订阅者将收到美国政府国防版环境中评估的 L5 服务，但使用 L4 分段。
  
## <a name="background-screening"></a>背景屏蔽

Office 365 员工无法长期访问 GCC High 和 DoD 生产。 任何请求临时权限提升以授予客户内容访问权限的员工都必须首先通过以下背景调查。<br><br>
  
| Microsoft 人员筛选和背景调查<sup>1</sup> | 说明 |
|:-----|:-----|
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

<sup>1</sup> 仅适用于临时或长期访问 Office 365 美国云或 DOD 云中托管的客户GCC-High人员。
## <a name="feature-nuances-based-on-compliant-cloud-architecture"></a>基于合规云体系结构的功能细微差别

GCC High 和 DoD 环境中订阅包括核心 Exchange Online、SharePoint 和 Skype for Business 功能。 鉴于基础结构的认证和资格鉴定的增加，常规商业 Office 365 产品/服务与 GCC High 和 DoD 中提供的产品/服务之间存在一些功能差异。
  
### <a name="exchange-online"></a>Exchange Online

 Exchange Online 统一消息支持本地 **IP-PBX** - GCC High 和 DoD 订阅不支持将本地 IP-PBX 系统与 Exchange Online 统一消息集成。 
  
### <a name="file-sharing"></a>文件共享

用户在 SharePoint 和 OneDrive 中有多个共享文件和文件夹的选项。 所有选项在 GCC High 和 DoD 环境中可用。 有关管理这些选项的详细信息，请参阅管理 [共享设置](/sharepoint/turn-external-sharing-on-or-off)。 GCC-High用户只能与 GCC-High 中的其他组织共享。 此外，不支持附加到用户配置文件的非 GCC 高电子邮件地址，并且不允许发送通知电子邮件。 例如，本地用户 A 分配有 Gmail 电子邮件地址，然后同步到 Azure GCC High 组织。 用户 A 导航到库并创建任何更改的警报。 不会将警报发送到 Gmail 地址。

> [!NOTE]
> 非 GCC-High 中的用户当前无法与非 GCC High 组织的用户共享。

[文件请求](https://support.office.com/article/f54aa7f8-2589-4421-b351-d415fc3b83af) 不适用于 Office 365 政府版。

### <a name="skype-for-business-online"></a>Skype for Business Online

 **PSTN 呼叫 &amp;PSTN** 会议 - 由于要求将公用电话交换网 (PSTN) 用于面向电话的服务，PSTN 呼叫 PSTN 会议服务当前在 GCC High 和 DoD 中不可用。 &amp;

### <a name="microsoft-teams"></a>Microsoft Teams

**通过直接路由 (** 电话系统和音频) - 用于 GCC High 和 DoD 环境的电话系统和音频会议通过直接路由提供。 有关详细信息，请参阅此处的服务级别文档：

- [通过直接路由的电话系统](/microsoftteams/here-s-what-you-get-with-phone-system)
- [适用于 GCC High 和 DoD 且含直接路由的音频会议](/microsoftteams/audio-conferencing-with-direct-routing-for-gcch-and-dod)

### <a name="identity"></a>标识

使用联合身份模型的多重身份验证允许使用 PIV 和 CAC 卡。
  
### <a name="yammer"></a>Yammer

Yammer for enterprise 在 GCC High 和 DoD 环境中不可用。
  
## <a name="customer-support"></a>客户支持

使用 Office 365 GCC High/DOD 时，Microsoft 提醒你不要将任何受控、敏感或机密信息作为支持事件的一部分与客户支持人员共享，至少直到你确认支持代理授权查看或访问此类数据。

Microsoft 致力于 [保护你的隐私](https://privacy.microsoft.com/privacystatement)) 。 但是，Office 365 GCC High/DoD 支持不包括在服务资格鉴定边界中，并且不提供 FedRAMP、DOD SRG、ITAR、IRS 1075 或 CJIS 数据处理合规性保证。