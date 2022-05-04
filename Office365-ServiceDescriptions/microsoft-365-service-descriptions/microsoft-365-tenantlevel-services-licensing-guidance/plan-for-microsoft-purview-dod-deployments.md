---
title: 规划 Microsoft Purview - DoD 部署
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: 本指南适用于推动在美国联邦政府实体或其他实体中部署Office 365的 IT 专业人员，这些实体处理受政府法规和要求约束的数据，其中使用Microsoft 365政府 - DoD 适合满足这些要求。
ms.openlocfilehash: dfb160ff6b6cc2f10f0c414e3f5b8733ca2aff7b
ms.sourcegitcommit: c2d2064d8fbebbe9843a4e824860e214b0b54c58
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/04/2022
ms.locfileid: "65187453"
---
# <a name="plan-for-microsoft-purview-compliance-and-risk-management-solutions---dod-deployments"></a>Microsoft Purview 合规性和风险管理解决方案计划 - DoD 部署

本指南适用于推动在美国联邦政府实体或其他实体中部署Office 365的 IT 专业人员，这些实体处理受政府法规和要求约束的数据，其中使用Microsoft 365政府 - DoD 适合满足这些要求。

> [!NOTE]
> 如果你的组织已满足Microsoft 365政府 - DoD 资格要求并申请并已接受该计划，则可以跳过步骤 1 和 2，直接转到步骤 3。

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---dod-and-meets-eligibility-requirements"></a>步骤 1. 确定组织是否需要Microsoft 365政府 - DoD 并满足资格要求

Microsoft 365政府 - DoD 环境符合美国政府对云服务的要求。

除了享受Office 365的特性和功能外，组织还受益于Microsoft 365政府唯一的以下功能 – DoD：

- 组织的客户内容在逻辑上与 Microsoft 商业Office 365服务中的客户内容分离。
- 您组织的客户内容存储在美国境内。
- 对组织的客户内容的访问权限只限于屏蔽的 Microsoft 员工。
- Microsoft 365政府 - DoD 符合美国公共部门客户所需的认证和认证。

你可以在Office 365 政府版[计划](https://products.office.com/government/compare-office-365-government-plans)中找到有关Microsoft 365政府 - DoD 产品/服务的详细信息，包括资格要求。

[Office 365美国政府服务说明](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md)介绍了平台的优势，其重点是满足美国中的合规性要求。

> [!TIP]
> 你可能希望将服务说明中的信息表传输到Excel工作簿中，并添加两列：**与组织 Y/N 相关** 并 **满足组织 Y/N 的需求**。 然后，可以与同事一起查看此列表，确认此服务是否满足组织的需求。

**决策点**：<br/>
- *确定Microsoft 365政府 - DoD 是否适合你的组织。*
- *确认你的组织符合资格要求。*

> [!NOTE]
> Microsoft 365政府 - DoD 仅在美国中提供。 非美国政府客户可以从多个[Office 365 政府版计划](https://products.office.com/government/compare-office-365-government-plans)中进行选择。

## <a name="step-2-apply-for-microsoft-365-government---dod"></a>步骤 2. 申请Microsoft 365政府 - DoD

确定此服务适合你的组织后，请开始 [应用此服务](https://products.office.com/government/eligibility-validation)的过程。

## <a name="step-3-understand-microsoft-365-government---dod-default-security-settings"></a>第 3 步。 了解Microsoft 365政府 - DoD 默认安全设置

建议在修改管理员和安全设置之前，请花些时间仔细查看它们，并在对默认安全设置进行任何更改之前考虑对合规性的影响。

**决策点**：*确定是否修改任何默认Microsoft 365政府 - DoD 安全设置，解决方法是首先了解可能进行的任何更改的影响。*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--dodsup1sup"></a>步骤 4. 了解Microsoft 365政府 - <sup>DoD1</sup> 中当前不可用或默认禁用的功能

为了满足政府云客户的要求，Microsoft 365政府-DoD 和企业计划之间存在一些差异。 请参阅下表，了解哪些功能可用。 有关Microsoft 365路线图上发布的最新符合性产品更新，请参阅[此](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent)处。<br><br>

| 领域  | 功能 | DoD 状态 |
|-------|---------|-------------|
| **数据保护**  | | |
| 敏感信息类型  | 精确数据匹配  | 可用  |
| | 命名实体敏感信息类型和策略创作模板 | 正在开发  |
| 敏感度标记  | 统一标记客户端和扫描程序 | 可用  |
| | 将“默认标签”应用于上传到SharePoint联机文档库的未标记文件 | 正在开发 |
| | 应用默认标签策略以确保编辑文档 | 正在开发 |
| | Exchange Online、SharePoint Online 和 OneDrive for Business 的自动分类和标记  | 可用 |
| | Office 应用 (Word、Excel、PowerPoint、Outlook) 的自动分类和标记， (Web、Android、iOS、Windows 和 Mac)  | 可用  |
| | 移动)  (Office客户端的自动分类和标记 | 在工程积压工作上  |
| | Teams、Microsoft 365 组 和SharePoint站点的自动分类和标记  | 可用  |
| | 自动标记策略支持覆盖手动标签并加密从任何组织收到的邮件 | 可用  |
| | 共同创作Microsoft 信息保护加密文档| 可用  |
| | 增强了对联机和SharePoint中自动标记的模拟和位置支持OneDrive for Business | 可用 |
| | 使用 Microsoft Azure Purview 将内置敏感度标签扩展到 Azure 中的资产 | 正在开发  |
| | 通过“敏感度标签”为SharePoint联机网站提供粒度条件访问策略 | 在工程积压工作上  |
| | 必需标签  | 可用  |
| | 手动标签  | 可用  |
| | Exchange Online中自动标记的新条件| 正在开发 |
| | 可以搜索和电子数据展示使用敏感度标签加密的 PDF 文件 | 在工程积压工作上 |
| 分析  | 数据分类分析：概述和内容资源管理器 | 可用 |
| | Office应用中的审核和分析 | 可用 |
| | 活动资源管理器包含Power BI敏感度标签数据 | 可用 |
| | 活动资源管理器内置筛选器 | 可用 |
| | 活动资源管理器用户体验改进 | 正在开发 |
| | 活动资源管理器Power BI敏感度标签数据 | 可用 |
| | 活动资源管理器安全读取器角色已更新 | 可用 |
| | 内容资源管理器包含Teams数据 | 正在开发 |
| | Office应用/客户端上具有自动标记的机器学习分类器  | 可用 |
| 加密  | Microsoft Purview 消息加密 (E3)  | 可用 |
| | Microsoft Purview 客户密钥 | 可用 |
| | 客户密钥：Microsoft 365的静态数据加密 | 可用 |
| | 客户密钥：SharePoint联机和OneDrive for Business | 可用 |
| | 为客户管理的密钥预配生命周期自带密钥 (BYOK)  | 可用 |
| | Microsoft Purview 双键加密 | 可用 |
| | 使用 Microsoft 托管密钥Exchange Online服务加密 | 可用 |
| 数据丢失防护 | 警报仪表板和警报体验 | 可用 |
|  | 活动资源管理器中显示的数据 | 可用 |
|  | 终结点数据丢失防护 | 可用 |
|  |  (SPO/ODB) 和电子邮件的文件 | 可用 |
|  | Microsoft Defender for Cloud Apps (以前Microsoft Cloud App Security) 集成 | 可用 |
|  | 本地扫描程序 | 可用 |
|  | 解决方案概述页 | 可用 |
|  | Teams聊天和频道对话  | 可用 |
| **数据生命周期管理&记录管理** |  |  |
| 数据生命周期管理 (以前的信息治理)  | 保留和标记策略的自适应范围 | 可用 |
| | 在保留期结束时应用保留标签操作  | 在工程积压工作上 |
| | 对SharePoint、OneDrive for Business库、文件夹和文档集应用默认保留标签;Exchange收件箱;和Office 365组 | 可用 |
| | 配置选项以阻止编辑记录元数据的功能 | 正在开发 |
| | 禁用对记录的解锁 | 正在开发 |
| | 电子邮件存档 | 可用 |
| | 导入 PST | 可用 |
| | 手动非记录保留标签 | 可用 |
| | 保留锁 | 可用 |
| | SharePoint联机和OneDrive for Business的保留改进 | 可用 |
| | 保留标签删除行为在SharePoint中发生更改 | 可用 |
| | 保留整个组织的策略;特定位置或用户;自动基于特定条件 (，例如关键字或敏感信息) ;并基于事件 | 可用 |
| | Teams (聊天) 的保留策略 | 可用 |
| | Teams会议录制的保留策略 | 可用 |
| | Teams专用频道的保留策略 | 可用 |
| 记录管理 | 删除记录标签的功能 | 可用 |
| | 允许记录标签启动手动记录声明的“解锁” | 正在开发 |
| | 手动应用记录标签 | 可用 |
| | 为SharePoint、OneDrive for Business库、文件夹和文档集应用默认记录标签;Office 365组 | 可用 |
| | 根据特定条件自动应用记录策略 (例如关键字或敏感信息) ;并基于事件 | 可用 |
| | 使用可训练分类器自动应用记录策略  | 正在开发 |
| | 禁用对记录的解锁 | 可用 |
| | 处置评审 | 可用 |
| | 文件计划管理器 | 可用 |
| | 多阶段处置评审 | 即将推出 |
| | Outlook客户端对记录管理的支持 | 可用 |
| | Power Automate 集成 | 在工程积压工作上 |
| | 处置证明 | 可用 |
| | 记录版本控制 | 可用 |
| | 法规记录 | 可用 |
| **风险管理**  | | |
| 客户密码箱 | 客户密码箱 | 可用 |
| 通信合规性 | 能够为通信合规性策略设置保留期 | 在工程积压工作上 |
| | 访问警报;通知模板;通信策略仪表板 | 可用 |
| | 使用本地邮箱分析用户Teams聊天数据 | 可用 |
| | 自动监视用户所属的所有Teams | 可用 |
| | 利益冲突模板 | 可用 |
| | 创建客户策略，3 个预配置 | 可用 |
| | 数据丢失防护策略建议 | 可用 |
| | 第零天见解 | 在工程积压工作上 |
| | 检测成人内容 | 可用 |
| | 检测客户投诉  | 正在开发 |
| | 检测随时间推移的重复行为准则冲突 | 可用 |
| | 歧视分类器 | 可用 |
| | 升级以调查电子数据展示 (高级版)  | 可用 |
| | Exchange和Teams支持 | 可用 |
| | 展开光学字符识别以支持手写和打印文本 | 正在开发 |
| | 消息详细信息报告 | 在工程积压工作上 |
| | 新式附件：分析联机和SharePoint链接内容OneDrive for Business | 正在开发 |
| | 策略运行状况检查和暂停策略的能力 | 正在开发 |
| | Power Automate 集成 | 在工程积压工作上 |
| | 从Teams聊天或频道中删除Teams消息 | 可用 |
| | 每个位置报表的敏感信息类型  | 可用 |
| | 支持更精细的权限 | 可用 |
| | 支持针对威胁、定向骚扰和亵渎分类器的七种语言 | 可用 |
| | 支持Teams、Exchange和删除Teams消息的能力 | 可用 |
| | 标记改进 | 可用 |
| | Teams对话上下文 | 可用 |
| | 在调查期间翻译内容 | 可用 |
| 信息屏障 | 信息屏障 | 可用 |
| | 管理员体验：细分和策略登陆页 | 即将推出 |
| 内部风险管理 | 导出警报的功能 | 可用 |
| | 活动资源管理器数据浮出水面 | 可用 |
| | 分析 | 公共预览版 |
| | 案例仪表板 | 可用 |
| | 内容资源管理器增强功能 | 可用 |
| | 心怀不满用户的数据泄露活动 | 正在开发 |
| | 离职用户窃取数据 | 可用 |
| | 优先用户的数据泄露 | 公共预览版 |
| | 增强了对域的支持 | 正在开发 |
| | 升级以调查电子数据展示 (高级版)  | 可用 |
| | 导出警报增强功能 | 正在开发 |
| | 常规数据泄露 | 可用 |
| | 违反常规安全策略 | 正在开发 |
| | 增加了一组第一方指标 | 正在开发 |
| | 安全策略违规指标 | 正在开发 |
| | Microsoft Defender for Endpoint警报的指示器 | 正在开发 |
| | Office (Teams、SharePoint网站、电子邮件) 的指示器 | 可用  |
| | Windows 10终结点活动的指示器 | 可用 |
| | 对域设置的智能支持 | 可用 |
| | Microsoft Defender for Endpoint警报 | 正在开发 |
| | Microsoft Teams集成 | 公共预览版 |
| | 本机触发器 (新信号、指示器选择、自定义和活动资源管理器 | 即将推出 |
| | Office Teams、SharePoint网站、电子邮件的指示器 | 可用 |
| | 策略自定义、策略运行状况检查和增强的策略创建向导 | 可用 |
| | 心怀不满的用户数据泄漏的策略模板 | 公共预览版 |
| | 优先级用户数据泄露的策略模板 | 公共预览版 |
| | 一般安全策略冲突的策略模板 | 正在开发 |
| | 优先级用户、离任用户、心怀不满的用户违反安全策略的策略模板 | 正在开发 |
| | Power Automate 集成 | 正在开发 |
| | 优先级用户组 | 公共预览版 |
| | 识别设备指示器 | 公共预览版 |
| | 离职用户的安全策略违规活动 | 正在开发 |
| | 心怀不满员工的安全策略违规活动 | 正在开发 |
| | 优先用户的安全策略违规 | 正在开发 |
| | 用于Power Automate的 ServiceNow 模板 | 公共预览版 |
| | 支持用于Azure Active Directory帐户删除的本机触发器 | 可用 |
| | 会审和调查改进 | 正在开发 |
| | 用户活动报告 | 公共预览版 |
| | “观看观察者”审核线索 | 可用 |
| 电子数据展示（标准版） | 审核 | 可用 |
| | 案例管理 | 可用 |
| | OneDrive for Business的符合性边界 | 可用 |
| | 导出 | 可用 |
| | 就地保存 | 可用 |
| | 本机导出 | 可用 |
| | RMS 解密 | 可用 |
| | 搜索 | 可用 |
| | Microsoft 合规中心扩展了对在SharePoint和OneDrive for Business回收站中搜索和导出项目的支持 | 可用 |
| 电子数据展示(高级版) | 高级处理 | 可用 |
| | 大小写限制增强功能 | 正在开发 |
| | 收集和审阅SharePoint和/或OneDrive for Business中的加密内容 | 可用 |
| | Teams对话作为脚本的集合 | 正在开发 |
| | 通信模板和颁发官员设置 | 即将推出 |
| | 保管人到工作负荷映射 | 可用 |
| | 保管人通信 | 可用 |
| | 仪表板 | 可用 |
| | Microsoft Teams的数据清除功能  | 正在开发 |
| | 深度爬网/索引 | 可用 |
| | 中文、日语、韩语)  (双字节字符支持 | 可用 |
| | 电子邮件会话 | 可用 |
| | 增强的导入保管人向导体验 | 即将推出 |
| | 导出 (下载、导出、添加到另一个视图集)  | 可用 |
| | 筛选 | 可用 |
| | 图形 API的 | 正在开发 |
| | 历史版本 | 正在开发 |
| | 保留优化 | 正在开发 |
| | 保留报表 | 正在开发 |
| | 将Teams标识为数据源 | 正在开发 |
| | Teams专用频道消息的法律保留 | 可用 |
| | Microsoft Purview 合规性门户扩展了对在SharePoint和OneDrive for Business回收站中搜索和导出项目的支持 | 正在开发 |
| | 近乎重复的标识 | 可用 |
| | 新的预测编码模块 | 在工程积压工作上 |
| | 非存储数据源 | 可用 |
| | 非Office 365引入 | 可用 |
| | 预测编码 | 可用 |
| | 使用负载文件进行处理的导出 | 可用 |
| | 修订 | 可用 |
| | 审阅集 | 可用 |
| | 查看数据 (查询数据、智能标记、仪表板) 和批注 (修订)  | 可用 |
| | 搜索术语报告 | 可用 |
| | 单个项目错误修正 | 可用 |
| | 支持 PST 导出 | 可用 |
| | 支持OneDrive和联机SharePoint链接内容 (新式附件)  | 可用 |
| | 支持Teams反应 | 正在开发 |
| | 标记 | 可用 |
| | 租户报表 | 可用 |
| | 主题 | 可用 |
| | 查看者 | 可用 |
| 审核（标准） | 审核（标准）| 可用 |
| 审核（高级） | 访问关键事件 (例如 MailItemsAccessed)  | 可用 |
| | 审核保留期仪表板 | 可用 |
| | 审核搜索增强功能 | 在工程积压工作上 |
| | 管理活动 API 带宽增加 | 可用 |
| | Teams专用频道消息的法律保留 | 可用 |
| | 日志保留期 (1 年)  | 可用 |
| | 审核日志的长期保留期 (10 年)  | 可用 |
| | 邮件转发和邮件发送事件 | 可用 |
| | Microsoft 365安全与合规中心 | 可用 |
| | 在 Exchange Online 和 SharePoint Online 中搜索术语事件 | 可用 |
| **合规性状况** |  |  |
| 合规性管理 | Microsoft Purview 合规性门户 | 可用 |
| | Microsoft Purview 合规性管理器 | 可用 |
| | 合规性管理器：警报和通知 | 正在开发 |
| | 合规性管理器：持续合规性评估 | 即将推出 |
| | 合规性管理器：非Microsoft 365资产的现新评估 | 可用 |
| | 合规性管理器：用于创建批量评估的建议引擎 | 正在开发 |
| | 双字节字符支持 | 可用 |
| | Microsoft Defender for Cloud Apps | 可用 |
| **生态** |  |  |
| 数据连接器 | 第一方数据连接器：HR  | 可用 |
| | 第一方数据连接器：HR 1.2 | 可用 |
| | 第一方数据连接器：物理损坏 | 可用 |
| | 电子数据展示 (高级版) Graph API | 正在开发 |
| | 记录管理Graph API | 正在开发 |
| | Graph API 用于Teams导出数据 | 正在开发 |
 **隐私** | | |
| 隐私管理 | Microsoft Priva 隐私风险管理 | 正在开发 |
| | Microsoft Priva 使用者权限请求 | 正在开发 |

<sup>1</sup> 当重新评估项目计划和优先级时，标识的状态可能会更改。<br/>

**决策点**： *确定符合性功能是否满足组织的需求。*
