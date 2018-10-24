---
title: GCC 高和 DoD
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 5/23/2018
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0821204d-5515-43de-8ed6-ab84bd1693c1
description: Microsoft 提供受到国际流量在 Arm 法规 (ITAR)，或以满足美国防御部门以及承包商的唯一和发展要求按住或处理 DoD 控制未分类的信息 (CUI)GCC 高和 DoD 环境。可通过批量许可，感的组织经过验证过程以确保资格建立环境之前。Trials 此时不可用。
ms.openlocfilehash: 4fd893157eb12f470c78f8d8c88fa1ab6e5c1772
ms.sourcegitcommit: de65f864b9c82d5e163a2c59beb2aaec7bb3f5d5
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/23/2018
ms.locfileid: "25719066"
---
# <a name="gcc-high-and-dod"></a>GCC 高和 DoD

Microsoft 提供受到国际流量在 Arm 法规 (ITAR)，或以满足美国防御部门以及承包商的唯一和发展要求按住或处理 DoD 控制未分类的信息 (CUI)GCC 高和 DoD 环境。可通过批量许可，感的组织经过验证过程以确保资格建立环境之前。Trials 此时不可用。 
  
若要了解详细信息或启动验证流程，请与你的帐户团队或首选合作伙伴联系。
  
## <a name="how-to-use-this-service-description-section"></a>如何使用本服务说明部分

Office 365 美国政府版 服务说明旨在作为常规 Office 365 服务说明的整体进行说明。它定义了唯一承诺以及与 Office 365 企业版产品的差异。
  
## <a name="compliance"></a>合规性

GCC 高和 DoD 满足以下认证和资格鉴定的合规性要求： 
  
- 符合 Moderate 基准（FedRAMP Moderate）的联邦风险和授权管理计划，其中包括美国国家标准技术研究院 (NIST) 特种出版物 800-53 中所述的这些安全控制和增强控制。
    
- 高至影响级别 5 (L5) 的信息的美国国防部云计算安全要求指南 (SRG) 的安全控制和增强控制。
    
部门的防御到 Office 365 的订阅者将收到来自 DOD 独占环境符合 DOD SRG L5 提供服务。非-部防御订阅者将收到来自评估在 L5，但使用第 4 细分的美国政府国防环境的服务。
  
## <a name="background-screening"></a>背景筛选

Office 365 人员没有位置访问 GCC 高和 DoD 生产。任何员工他们请求临时权限提升的会授予对客户内容的访问权限必须首先过去的以下背景检查。
  
|||
|:-----|:-----|
|**Microsoft 人员筛查和背景调查** <br/> |**说明** <br/> |
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
   
## <a name="feature-nuances-based-on-compliant-cloud-architecture"></a>功能细微基于符合云体系结构

GCC 高和 DoD 环境中的 office 365 订阅包括核心 Exchange Online、 SharePoint Online 和 Skype 业务功能。在给定所增加的证书和基础结构的评审机制，有一些常规商业 Office 365 产品和可用之间 GCC 高和 DoD 中的功能差异。
  
### <a name="exchange-online"></a>Exchange Online

 **Exchange Online 统一消息支持的本地 IP-PBX** -与 Exchange Online 统一消息集成的本地 IP PBX 系统的支持不支持在高 GCC 和 DoD 订阅。 
  
### <a name="sharepoint-online"></a>SharePoint Online

 **文档共享**-SharePoint Online 和 OneDrive for Business 启用无缝信息共享和用户和团队之间的协作。文档所有者可以将其他用户提供访问其文档通过 web 界面或在 Outlook 中的现代附件。共享文档，当有多个选项可用于管理权限： 
  
1. 只有我
    
2. 公司内的任何人
    
3. 与此链接的任何人
    
4. 特定的某个人
    
使用 SharePoint Online 和 OneDrive for GCC 高或 DoD 环境中的业务可以保留文档专用客户 （首选项），与任何人共享其组织中 （第二个选项），与任何人都指向该文档的链接共享 （第三个选项），和共享与 GCC 高和 DoD 环境中特定的用户 （第四个选项）;当然，这些选项可以限制基于以及租户级访问控制。
  
GCC 高租户可以仅与其他 GCC 高租户共享。例如：
  
- GCC 高租户 A 可以分享 GCC 高租户 b。
    
- 非 GCC 租户 C 可以共享与 GCC 高租户 A 或 b。
    
- GCC 高租户 A 或 B 无法共享与非 GCC 高租户 c。
    
此外，附加到用户配置文件的非 GCC 高电子邮件地址不受支持，并且不允许发送的通知电子邮件。例如，在本地用户 A 是分配 Gmail 电子邮件地址，然后同步到 Azure GCC 高租户。用户 A 导航到库，并创建通知的任何更改。通知不会发送到 Gmail 地址。
  
 **外部应用程序访问**-与的加载项等数据源的外部应用程序的连接仅限于位于 GCC 高和 DoD 所支持的系统安全范围内的源。 
  
 **Business Connectivity Services** -BCS 功能支持在其中的数据源保持云服务对安全边界内可访问的连接性方案。 
  
 **沙盒解决方案**-此功能已被弃用并且不可用。任何沙盒解决方案应迁移到[SharePoint 外接程序扩展性模型]( https://msdn.microsoft.com/en-us/library/office/fp179930.aspx)。
  
### <a name="skype-for-business-online"></a>Skype for Business Online

 **PSTN 呼叫&amp;PSTN 会议**-由于公共公用电话交换网 (PSTN) 用于面向电话的服务，PSTN 呼叫的要求&amp;PSTN 会议服务将当前不可用 GCC 高和 DoD 中。 
  
### <a name="identity"></a>身份

使用联合身份模型的多重身份验证允许使用 PIV 和 CAC 卡。
  
### <a name="yammer"></a>Yammer

Yammer 不可用 GCC 高和 DoD 环境中。
  

