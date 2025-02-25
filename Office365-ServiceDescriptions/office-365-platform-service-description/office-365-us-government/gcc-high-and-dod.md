---
title: Office 365 GCC High 和 DoD
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: 0821204d-5515-43de-8ed6-ab84bd1693c1
description: 了解高和 doD Office 365 GCC与商业环境相比的独特承诺Office 365差异。
ms.openlocfilehash: 0404713baf8bcdb9933943ae616fc74d469be178
ms.sourcegitcommit: aa6f9785881e60517888ff74e982e38261e6ebde
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/24/2022
ms.locfileid: "63937291"
---
# <a name="office-365-gcc-high-and-dod"></a>Office 365 GCC High 和 DoD

为满足美国国防部独特的且不断发展的要求，以及拥有或处理 DoD 控制的未分类信息 (CUI) 或受国际武器贸易条例 (ITAR) 限制的承包商的要求，Microsoft 提供 GCC High 和 DoD 环境。 为确保有资格建立环境，感兴趣的组织可以通过批量许可完成验证流程。 暂不提供试用。 
  
联系你的帐户团队或首选合作伙伴，了解更多信息或启动验证流程。 若要详细了解如何购买，请参阅Microsoft 365[政府 - 如何购买](./microsoft-365-government-how-to-buy.md)。
  
## <a name="how-to-use-this-service-description"></a>如何使用本服务说明

美国政府Office 365说明旨在作为常规服务说明Office 365覆盖。 它定义了与企业产品/服务Office 365的独特承诺和差异。
  
## <a name="compliance"></a>合规性

Office 365 GCC高和 DoD 满足以下认证和资格鉴定的合规性要求：
  
- Office 365 GCC高和 DoD：FedRAMP High 的联邦风险和授权管理计划，包括美国国家标准和技术协会 (NIST) 800-53 特别出版物中概述的安全控制和控制措施增强功能。
    
- Office 365 DoD：美国国防部云计算安全要求指南 (SRG) 的安全控制和增强功能，可获取影响级别 5 (L5) 。
    
根据 DoD 要求，只有国防部实体Office 365 DoD 环境认证的 DoD SRG L5 许可证。 满足适当资格要求的非国防部实体可能会购买 Office 365 GCC 高[](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy#microsoft-365-government-eligibility-and-validation)环境的许可证，该环境在 FedRAMP High 中进行评估，可以证明与 IL4 等效或 CMMC 的必要继承。
  
## <a name="background-screening"></a>背景屏蔽

Office 365员工不能长期访问 GCC High 和 DoD 生产。 任何请求临时权限提升以授予客户内容访问权限的员工都必须首先通过以下背景调查。<br><br>
  
| Microsoft 人员筛选和背景检查<sup>1</sup> | 说明 |
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

<sup>1</sup> 仅适用于具有临时或长期访问美国云或 DOD 云中托管的客户Office 365GCC-High的人员。
## <a name="feature-nuances-based-on-compliant-cloud-architecture"></a>基于合规云体系结构的功能细微差别

高GCC DoD 环境中订阅包括核心Exchange Online、SharePoint和Skype for Business功能。 鉴于基础结构的认证和资格鉴定的增加，常规商业产品/服务Office 365高和 DoD 中提供的功能GCC差异。
  
### <a name="exchange-online"></a>Exchange Online

 **Exchange Online IP-PBX** 统一消息支持 - GCC High 和 DoD 订阅不支持将本地 IP-PBX 系统与 Exchange Online 统一消息集成。 
  
### <a name="file-sharing"></a>文件共享

用户有多个选项可以共享 SharePoint 和 OneDrive 中的文件和文件夹。 所有选项均在高GCC DoD 环境中可用。 有关管理这些选项的详细信息，请参阅管理 [共享设置](/sharepoint/turn-external-sharing-on-or-off)。 GCC-High中的用户只能与 GCC-High 中的其他组织共享。 此外，不支持GCC附加到用户配置文件的高电子邮件地址，并且不允许发送通知电子邮件。 例如，本地用户 A 分配有 Gmail 电子邮件地址，然后同步到 Azure GCC High 组织。 用户 A 导航到库并创建任何更改的警报。 不会将警报发送到 Gmail 地址。

> [!NOTE]
> 当前GCC-High中的用户无法与非高级GCC用户共享。

[文件请求](https://support.office.com/article/f54aa7f8-2589-4421-b351-d415fc3b83af)不适用于Office 365 政府版。

### <a name="skype-for-business-online"></a>Skype for Business Online

 **PSTN 呼叫&amp;PSTN** 会议 - 由于要求将公用电话交换网 (PSTN) 用于面向电话的服务，PSTN 呼叫 &amp; PSTN 会议服务当前在 GCC High 和 DoD 中不可用。

### <a name="microsoft-teams"></a>Microsoft Teams

**电话系统通过** 直接路由 (- 电话系统 和音频会议（适用于 GCC 高和 DoD 环境）的) 和音频会议通过直接路由提供。 有关详细信息，请参阅此处的服务级别文档：

- [电话系统直接路由进行路由](/microsoftteams/here-s-what-you-get-with-phone-system)
- [适用于 GCC High 和 DoD 且含直接路由的音频会议](/microsoftteams/audio-conferencing-with-direct-routing-for-gcch-and-dod)

### <a name="identity"></a>标识

使用联合身份模型的多重身份验证允许使用 PIV 和 CAC 卡。
  
### <a name="yammer"></a>Yammer

Yammer高和 DoD 环境中GCC企业版。
  
## <a name="customer-support"></a>客户支持

Microsoft 提醒你在使用 Office 365 GCC High/DOD 时，不要将任何受控、敏感或机密信息作为支持事件的一部分与客户支持人员共享，至少直到你确认支持代理授权查看或访问此类数据。

Microsoft 致力于 [保护你的隐私](https://privacy.microsoft.com/privacystatement)) 。 但是Office 365 GCC认证边界中不包含高/DoD 支持，也不提供 FedRAMP、DOD SRG、ITAR、IRS 1075 或 CJIS 数据处理合规性保证。
