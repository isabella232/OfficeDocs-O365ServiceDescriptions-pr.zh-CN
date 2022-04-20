---
title: Microsoft Purview 计划 - GCC高
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: 本指南适用于推动在美国联邦政府实体或其他实体中部署Office 365的 IT 专业人员，这些实体处理受政府法规和要求约束的数据，其中使用Microsoft 365政府 - GCC High 适合满足这些要求。
ms.openlocfilehash: 49721220910c2aaacc2870d4b0e727a9d9df6a84
ms.sourcegitcommit: 0d84043f435e5368e23e1a738fbc019b9979839b
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/19/2022
ms.locfileid: "64931199"
---
# <a name="plan-for-microsoft-purview--gcc-high-deployments"></a>规划 Microsoft Purview - GCC高部署

本指南适用于推动在美国联邦政府实体或其他实体中部署Office 365的 IT 专业人员，这些实体处理受政府法规和要求约束的数据，其中使用Microsoft 365政府 - GCC High 适合满足这些要求。

> [!NOTE]
>如果你的组织已经满足Microsoft 365政府 - GCC高资格要求，并申请并已接受该计划，你可以跳过步骤 1 和 2，直接转到步骤 3。
 
## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government--gcc-high-and-meets-eligibility-requirements"></a>步骤 1. 确定组织是否需要Microsoft 365政府 - GCC高且符合资格要求

Microsoft 365政府 - GCC高环境符合美国政府对云服务的要求。 除了享受Office 365的特性和功能外，组织还受益于Microsoft 365政府特有的以下功能 - GCC高：

- 组织的客户内容在逻辑上与 Microsoft 商业Office 365服务中的客户内容分离。
- 您组织的客户内容存储在美国境内。
- 对组织的客户内容的访问权限只限于屏蔽的 Microsoft 员工。
- Microsoft 365政府 - GCC高符合美国公共部门客户所需的认证和认证。

你可以在Office 365 政府版计划（包括资格要求）中找到有关Microsoft 365政府的详细信息 - GCC美国政府客户的高产品[/](https://products.office.com/government/compare-office-365-government-plans)服务。

[Office 365美国政府服务说明](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md)介绍了平台的优势，其重点是满足美国中的合规性要求。

> [!TIP]
> 你可能希望将服务说明中的信息表传输到Excel工作簿中，并添加两列：**与组织 Y/N 相关** 并 **满足组织 Y/N 的需求**。 然后，可以与同事一起查看此列表，确认此服务是否满足组织的需求。

**决策点**：<br/>

- *确定Microsoft 365政府 - GCC-High是否适合你的组织。*
- *确认你的组织符合资格要求。*

> [!NOTE]
> Microsoft 365政府 - GCC高仅在美国中可用。 非美国政府客户可以从多个[Office 365 政府版计划](https://products.office.com/government/compare-office-365-government-plans)中进行选择。

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>步骤 2. 申请Microsoft 365政府 - GCC-High

确定此服务适合你的组织后，请开始 [应用此服务](https://products.office.com/government/eligibility-validation)的过程。

## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>步骤 3. 了解Microsoft 365政府 - GCC-High默认安全设置

建议在修改管理员和安全设置之前，请花些时间仔细查看它们，并在对默认安全设置进行任何更改之前考虑对合规性的影响。

**决策点**：*确定是否要修改任何默认Microsoft 365政府 - GCC-High安全设置，解决首先了解可能进行的任何更改的影响。*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-highsup1sup"></a>步骤 4. 了解Microsoft 365政府中当前不可用或禁用的功能 - <sup>GCC-High1</sup>

为了满足政府云客户的要求，Microsoft 365政府计划与GCC-High计划之间存在一些差异。 请参阅下表，了解哪些功能可用。 有关Microsoft 365路线图上发布的最新符合性产品更新，请参阅[此](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent)处。<br><br>

| 领域 | 功能 | GCC高状态 |
|------|---------|-----------------|
| **信息保护** |  |  |
| 敏感信息类型 | 精确数据匹配 | 可用 |
|  | 命名实体敏感信息类型和策略创作模板 | 在工程积压工作上 |
| 敏感度标记 | 统一标记客户端和扫描程序  | 可用 |
|  | 将“默认标签”应用于上传到SharePoint联机文档库的未标记文件 | 在开发中 |
|  | 应用默认标签策略以确保编辑文档 | 在开发中 |
|  | Exchange Online、SharePoint Online 和 OneDrive 的自动分类和标记 | 可用 |
|  | Office 应用 (Word、Excel、PowerPoint、Outlook) 的自动分类和标记， (Web、Android、iOS、Windows 和 Mac)  | 可用 |
|  | 移动)  (Office客户端的自动分类和标记 | 在工程积压工作上 |
|  | Teams、Microsoft 365 组 和SharePoint站点的自动分类和标记 | 可用 |
|  | 共同创作Microsoft 信息保护加密文档 | 可用 |
|  | 增强了对联机和SharePoint中自动标记的模拟和位置支持OneDrive for Business | 即将推出 |
|  | 使用 Microsoft Azure Purview 将内置敏感度标签扩展到 Azure 中的资产 | 在开发中 |
|  | 通过“敏感度标签”为SharePoint联机网站提供粒度条件访问策略 | 在工程积压工作上 |
|  | 必需标签 | 可用 |
|  | 手动标签 | 可用 |
|  | Exchange Online中自动标记的新条件 | 在开发中 |
| 分析 | 数据分类分析：概述和内容资源管理器 | 可用 |
|  | Office应用中的审核和分析 | 可用 |
|  | 活动资源管理器包含Power BI敏感度标签数据 | 可用 |
|  | 活动资源管理器内置筛选器 | 可用 |
|  | 内容资源管理器包含Teams数据 | 在开发中 |
|  | Office应用/客户端上具有自动标记的机器学习分类器 | 可用 |
| 加密 | 基本Office 365消息加密 (E3)  | 可用 |
|  | 高级Office 365消息加密 (E5)  | 可用 |
|  | Office 365 的客户密钥 | 可用 |
|  | 客户密钥：Microsoft 365的静态数据加密 | 可用 |
|  | 客户密钥：SharePoint联机和OneDrive for Business | 可用 |
|  | 为客户管理的密钥预配生命周期自带密钥 (BYOK)  | 可用 |
|  | 双密钥加密 | 可用 |
|  | 使用 Microsoft 托管密钥Exchange Online服务加密 | 可用 |
| 数据丢失防护 | 数据丢失防护：警报仪表板和警报体验 | 可用 |
|  | 文件和电子邮件的数据丢失防护 | 可用 |
|  | 数据丢失防护：活动资源管理器中显示的数据 | 可用 |
|  | 数据丢失防护：终结点  | 可用 |
|  | 数据丢失防护：Microsoft Defender for Cloud Apps (以前Microsoft Cloud App Security) 集成 | 可用 |
|  | 本地数据丢失防护 | 在开发中 |
|  | 数据丢失防护：概述页 | 可用 |
|  | 数据丢失防护：Teams聊天和频道对话  | 可用 |
| **信息治理** |  |  |
| 信息管理政策 | 信息治理：保留和标记策略的自适应作用域 | 可用 |
| | 信息治理：在保留期结束时应用保留标签操作 | 在工程积压工作上 |
| | 信息治理：对SharePoint、OneDrive for Business库、文件夹和文档集应用默认保留标签;Exchange收件箱;和Office 365组  | 可用 |
| | 信息治理：配置选项以阻止编辑记录元数据的功能 | 在开发中 |
| | 信息治理：禁用对记录的解锁 | 在开发中 |
| | 信息治理：电子邮件存档 | 可用 |
| | 信息治理：导入 PST | 可用 |
| | 信息治理：手动使用非记录保留标签 | 可用 |
| | 信息治理：保留锁 | 可用 |
| | 信息治理：联机和OneDrive for Business SharePoint保留改进 | 可用 |
| | 信息治理：保留标签删除行为更改SharePoint | 在开发中 |
| | 信息治理：将策略保留到整个组织;特定位置或用户;自动基于特定条件 (，例如关键字或敏感信息) ;并基于事件 | 可用 |
| | 信息治理：用于Teams的保留策略 | 可用 |
| | 信息治理：用于Teams会议录制的保留策略 | 可用 |
| | 信息治理：Teams专用频道的保留策略 | 可用 |
| 记录管理 | 记录管理：删除记录标签的功能 | 可用 |
| | 记录管理：允许记录标签启动手动记录声明的“解锁” | 在开发中 |
| | 记录管理：手动应用记录标签 | 可用 |
| | 记录管理：对SharePoint、OneDrive for Business库、文件夹和文档集应用默认记录标签;Office 365组 | 可用 |
| | 记录管理：根据特定条件自动应用记录策略 (例如关键字或敏感信息) ：并基于事件 | 可用 |
| | 记录管理：使用可训练分类器自动应用记录策略  | 在开发中 |
| | 记录管理：禁用对记录的解锁 | 在开发中 |
| | 记录管理：处置评审 | 可用 |
| | 记录管理：文件计划管理器 | 可用 |
| | 记录管理：多阶段处置评审 | 在工程积压工作上 |
| | 记录管理：Outlook客户端对记录管理的支持 | 在开发中 |
| | 记录管理：Power Automate集成 | 在工程积压工作上 |
| | 记录管理：处置证明 | 可用 |
| | 记录管理：记录版本控制 | 可用 |
| | 记录管理：法规记录 | 可用 |
| **风险管理** |  |  |
| 客户密码箱 | 客户密码箱 | 可用 |
| 通信合规性 | 通信符合性：能够为通信合规性策略设置保留期 | 公共预览版 |
| | 通信符合性：访问警报;通知模板;通信策略仪表板 | 可用 |
| | 通信合规性：使用本地邮箱分析用户Teams聊天数据 | 可用 |
| | 通信符合性：自动监视用户所属的所有Teams | 可用 |
| | 通信符合性：利益冲突模板 | 可用 |
| | 通信合规性：创建客户策略，3 个预配置 | 可用 |
| | 通信符合性：检测成人内容 | 可用 |
| | 通信合规性：检测随时间推移的重复行为准则冲突 | 可用 |
| | 通信符合性：歧视分类器 | 即将推出 |
| | 通信合规性：升级以供调查Advanced eDiscovery | 可用 |
| | 通信合规性：Exchange和Teams支持 | 可用 |
| | 通信符合性：策略运行状况检查和暂停策略的能力 | 在开发中 |
| | 通信符合性：Power Automate集成 | 在开发中 |
| | 通信合规性：从Teams聊天或频道中删除Teams消息 | 可用 |
| | 通信符合性：每个位置报表的敏感信息类型  | 在开发中 |
| | 通信合规性：支持七种语言来处理威胁、有针对性的骚扰和亵渎分类器 | 可用 |
| | 通信符合性：支持更精细的权限 | 可用 |
| | 通信符合性：支持Teams、Exchange和删除Teams消息的能力 | 可用 |
| | 通信符合性：Teams对话上下文 | 可用 |
| | 通信符合性：在调查期间翻译内容 | 可用 |
| 信息屏障 | 信息屏障 | 可用 |
| 内部风险管理 | 预览体验成员风险管理：导出警报的能力 | 可用 |
| | 预览体验成员风险管理：活动资源管理器数据浮出水面 | 可用 |
| | 预览体验成员风险管理：分析 | 公共预览版 |
| | 预览体验成员风险管理：案例仪表板 | 可用 |
| | 预览体验成员风险管理：内容资源管理器增强功能 | 可用 |
| | 预览体验成员风险管理：心怀不满的用户泄露数据 | 在开发中 |
| | 预览体验成员风险管理：离开用户的数据盗窃 | 可用 |
| | 预览体验成员风险管理：优先级用户的数据盗窃 | 公共预览版 |
| | 预览体验成员风险管理：升级以供调查Advanced eDiscovery | 可用 |
| | 预览体验成员风险管理：导出警报 | 公共预览版 |
| | 预览体验成员风险管理：常规数据泄漏 | 可用 |
| | 预览体验成员风险管理：一般安全策略冲突 | 在开发中 |
| | 预览体验成员风险管理：安全策略违规指标 | 在开发中 |
| | 预览体验成员风险管理：警报Microsoft Defender for Endpoint指标 | 在开发中 |
| | 预览体验成员风险管理：Office (Teams、SharePoint网站、电子邮件) 指标 | 可用  |
| | 预览体验成员风险管理：Windows 10终结点活动的指标 | 公共预览版  |
| | 预览体验成员风险管理：对域设置的智能支持 | 可用 |
| | 预览体验成员风险管理：Microsoft Teams集成 | 公共预览版 |
| | 预览体验成员风险管理：本机触发器 (新信号、指示器选择、自定义和活动资源管理器 | 可用 |
| | 预览体验成员风险管理：Teams、SharePoint网站、电子邮件的Office指标 | 可用 |
| | 预览体验成员风险管理：策略自定义、策略运行状况检查和增强型策略创建向导 | 可用 |
| | 预览体验成员风险管理：心怀不满的用户数据泄露的策略模板 | 公共预览版 |
| | 预览体验成员风险管理：优先级用户数据泄露的策略模板 | 公共预览版 |
| | 预览体验成员风险管理：一般安全策略冲突的策略模板 | 在开发中 |
| | 预览体验成员风险管理：优先级用户、离任用户、心怀不满的用户违反安全策略的策略模板 | 在开发中 |
| | 预览体验成员风险管理：Power Automate集成 | 在开发中 |
| | 预览体验成员风险管理：优先级用户组 | 公共预览版 |
| | 预览体验成员风险管理：离任用户违反安全策略 | 在开发中 |
| | 预览体验成员风险管理：心怀不满的用户违反安全策略 | 在开发中 |
| | 预览体验成员风险管理：优先级用户违反安全策略 | 在开发中 |
| | 预览体验成员风险管理：支持用于Azure Active Directory帐户删除的本机触发器 | 可用 |
| | 预览体验成员风险管理：用户活动报告 | 公共预览版 |
| | 预览体验成员风险管理：“观察观察者”审核线索 | 可用 |
| **发现 &amp; 响应** |  |  |
| 电子数据展示 | 核心电子数据展示：审核 | 可用 |
| | 核心电子数据展示：案例管理 | 可用 |
| | 核心电子数据展示：OneDrive for Business中的符合性边界 | 可用 |
| | 核心电子数据展示：导出 | 可用 |
| | 核心电子数据展示：就地保存 | 可用 |
| | 核心电子数据展示：本机导出 | 可用 |
| | 核心电子数据展示：RMS 解密 | 可用 |
| | 核心电子数据展示：搜索 | 可用 |
| | 核心电子数据展示：Microsoft 合规中心扩展了对在SharePoint和OneDrive for Business回收站中搜索和导出项目的支持 | 可用 |
| | Advanced eDiscovery：高级处理 | 可用 |
| | Advanced eDiscovery：大小写限制增强功能 | 在开发中 |
| | Advanced eDiscovery：收集和审阅SharePoint和/或OneDrive for Business中的加密内容 | 可用 |
| | Advanced eDiscovery：Teams对话作为脚本的集合 | 在开发中 |
| | Advanced eDiscovery：通信模板和颁发官员设置 | 在开发中 |
| | Advanced eDiscovery：保管人到工作负荷映射 | 可用 |
| | Advanced eDiscovery：保管人通信 | 可用 |
| | Advanced eDiscovery：仪表板 | 可用 |
| | Advanced eDiscovery：用于Microsoft Teams的数据清除功能  | 在开发中 |
| | Advanced eDiscovery：深度爬网/索引 | 可用 |
| | Advanced eDiscovery：中文、日语、韩语 (双字节字符支持)  | 可用 |
| | Advanced eDiscovery：电子邮件线程 | 可用 |
| | Advanced eDiscovery：增强的导入保管人向导体验 | 在开发中 |
| | Advanced eDiscovery：导出 (下载、导出、添加到另一个视图集)  | 可用 |
| | Advanced eDiscovery：筛选 | 可用 |
| | Advanced eDiscovery：Graph API | 在开发中 |
| | Advanced eDiscovery：历史版本 | 在开发中 |
| | Advanced eDiscovery：保留优化 | 在开发中 |
| | Advanced eDiscovery：将Teams标识为数据源 | 在工程积压工作上 |
| | Advanced eDiscovery：Teams专用频道消息的法律保留 | 可用 |
| | Advanced eDiscovery：Microsoft 合规中心扩大了对在SharePoint和OneDrive for Business回收站中搜索和导出项目的支持 | 在开发中 |
| | Advanced eDiscovery：近乎重复的标识 | 可用 |
| | Advanced eDiscovery：适用于 Core 和 Advanced eDiscovery 的新导出体验  | 在开发中 |
| | Advanced eDiscovery：新的预测编码模块和处理 | 在工程积压工作上 |
| | Advanced eDiscovery：非存储数据源 | 可用 |
| | Advanced eDiscovery：非Office 365引入 | 可用 |
| | Advanced eDiscovery：预测编码 | 可用 |
| | Advanced eDiscovery：使用负载文件进行处理的导出 | 可用 |
| | Advanced eDiscovery：修订 | 可用 |
| | Advanced eDiscovery：审阅集 | 可用 |
| | Advanced eDiscovery：查看数据 (查询数据、智能标记、仪表板) 和批注 (修订)  | 可用 |
| | Advanced eDiscovery：搜索词报表 | 可用 |
| | Advanced eDiscovery：单项错误修正 | 可用 |
| | Advanced eDiscovery：支持 PST 导出 | 可用 |
| | Advanced eDiscovery：支持OneDrive和联机SharePoint链接内容 (新式附件)  | 可用 |
| | Advanced eDiscovery：支持Teams反应 | 在开发中 |
| | Advanced eDiscovery：标记 | 可用 |
| | Advanced eDiscovery：租户报告 | 可用 |
| | Advanced eDiscovery：主题 | 可用 |
| | Advanced eDiscovery：查看者 | 可用 |
| | Advanced eDiscovery：Microsoft 合规中心中的Yammer Advanced eDiscovery | 可用 |
| Audit | 基本审核 | 可用 |
| | 高级审核：访问关键事件 (例如 *MailItemsAccessed*)  | 可用 |
| | 高级审核：审核保留期仪表板 | 可用 |
| | 高级审核：审核搜索增强功能 | 在工程积压工作上 |
| | 高级审核：管理活动 API 的带宽增加 | 可用 |
| | 高级审核：Teams专用频道消息的法律保留 | 可用 |
| | 高级审核：日志保留期 (1 年)  | 可用 |
| | 高级审核：审核日志的长期保留期 (10 年)  | 可用 |
| | 高级审核：邮件转发和邮件发送事件 | 可用 |
| | 高级审核：Microsoft 365安全与合规中心 | 可用 |
| | 高级审核：在Exchange Online和联机SharePoint搜索术语事件 | 可用 |
| **遵从性管理** |  |  |
| 合规性管理 | Microsoft 365 合规中心 | 可用 |
| | 合规性管理器 | 可用 |
| | 合规性管理器：持续合规性评估 | 在开发中 |
| | 合规性管理器：非Microsoft 365资产的现新评估 | 可用 |
| | 双字节字符支持 | 可用 |
| | Microsoft Defender for Cloud Apps (以前是 Microsoft Cloud App Security)  | 可用 |
| **生态** |  |  |
| 生态 | 第一方数据连接器：HR  | 可用 |
| | 第一方数据连接器：HR 1.2 | 可用 |
| | 第一方数据连接器：物理损坏 | 可用 |
| | Graph API for Advanced eDiscovery  | 在开发中 |
| | 记录管理Graph API (公共预览)  | 在开发中 |
| | Graph API 用于Teams导出数据 | 在开发中 |
| **隐私** |  |  |
| 隐私管理 | Microsoft Priva | 在开发中 |

<sup>1</sup> 当重新评估项目计划和优先级时，标识的状态可能会更改。<br/>

**决策点**： *确定符合性功能是否满足组织的需求。*
