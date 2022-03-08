---
title: Microsoft 365 合规性计划 - GCC High
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: 本指南适用于在美国政府实体或其他处理受政府法规和要求（使用 Microsoft 365 政府版 – GCC 高）适合满足这些要求的实体中推动 Office 365 部署的 IT 专业人员。
ms.openlocfilehash: 7bbbcdf84dab98d92f9043fd3e4dfec39c947c57
ms.sourcegitcommit: 36cce83d0f146c904ca02a251ba02a5ab913e3ef
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/08/2022
ms.locfileid: "63382703"
---
# <a name="plan-for-microsoft-365-compliance--gcc-high"></a>规划Microsoft 365合规性 – GCC高

本指南适用于在美国政府实体或其他处理受政府法规和要求（使用 Microsoft 365 政府版 – GCC 高）适合满足这些要求的实体中推动 Office 365 部署的 IT 专业人员。

> [!NOTE]
>如果你的组织已满足 Microsoft 365 Government – GCC High 资格要求，并且已申请并被接受加入该计划，你可以跳过步骤 1 和步骤 2，直接转到步骤 3。
 
## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government--gcc-high-and-meets-eligibility-requirements"></a>步骤 1. 确定你的组织是否需要Microsoft 365政府 – GCC高并满足资格要求

美国政府Microsoft 365 - GCC高环境符合美国政府云服务的要求。 除了享受 Office 365 的功能之外，组织还可从政府特有的以下功能Microsoft 365 – GCC高：

- 组织的客户内容在逻辑上与 Microsoft 商业服务中的客户Office 365隔离。
- 您组织的客户内容存储在美国境内。
- 对组织的客户内容的访问权限只限于屏蔽的 Microsoft 员工。
- Microsoft 365政府 – GCC高符合美国公共部门客户所需的认证和资格鉴定。

有关美国政府Microsoft 365 - GCC高产品/服务（包括资格Office 365 政府版[）详细信息](https://products.office.com/government/compare-office-365-government-plans)。

美国政府[Office 365](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md)说明介绍了该平台的好处，其中心内容是满足美国的合规性要求。

> [!TIP]
> 您可能希望将服务说明中的信息表转移到 Excel 工作簿并添加两列："与我的组织 **Y/N** 相关"和"满足我的组织 **Y/N** 的需求"。 然后，您可以与同事一起查看此列表，以确认此服务满足您组织的需求。

**决策点**：<br/>

- *决定Microsoft 365政府 – GCC-High是否适合你的组织。*
- *确认你的组织满足资格要求。*

> [!NOTE]
> Microsoft 365政府 - GCC高仅在美国可用。 非美国政府客户可以从多个计划Office 365 政府版[选择](https://products.office.com/government/compare-office-365-government-plans)。

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>步骤 2. 申请Microsoft 365政府 – GCC-High

确定此服务适合贵组织后，开始 [应用此服务的过程](https://products.office.com/government/eligibility-validation)。

## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>第 3 步。 了解Microsoft 365政府 – GCC-High默认安全设置

建议在修改管理员和安全设置之前，花些时间仔细查看这些设置，并考虑对合规性的影响，然后再对默认安全设置进行更改。

**决策点**：决定是否要修改任何默认的 Microsoft 365 政府 – GCC-High安全设置，解决以首先了解您可能进行的任何 *更改的影响。*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-highsup1sup"></a>步骤 4. 了解当前在政府 /Microsoft 365 中当前不可用或禁用的功能 – <sup>GCC-High1</sup>

为满足政府云客户的要求，Microsoft 365政府计划与企业GCC-High存在一些差异。 请参阅下表，了解哪些功能可用。 请参阅[此处](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent)，了解发布在 Microsoft 365 路线图上的最新合规性产品更新。<br><br>

| 领域 | 功能 | GCC高状态 |
|------|---------|-----------------|
| **信息保护** |  |  |
| 敏感信息类型 | 精确数据匹配 | 可用 |
|  | 命名实体敏感信息类型和策略创作模板 | 工程积压工作 |
| 敏感度标签 | 统一标记客户端和扫描程序  | 可用 |
|  | 对上载到联机文档库的未标记SharePoint应用"默认标签" | 开发中 |
|  | 应用默认标签策略以确保正在编辑的文档 | 开发中 |
|  | Exchange Online、SharePoint Online 和 OneDrive 的自动分类和OneDrive | 可用 |
|  | 跨平台 Office 应用 (Word、Excel、PowerPoint、Outlook) 、 (Web、Android、iOS、Windows 和 Mac) 的自动分类和)  | 可用 |
|  | 移动版客户端Office自动 (和)  | 工程积压工作 |
|  | 自动分类和标记Teams、Microsoft 365组SharePoint网站 | 可用 |
|  | 共同创作加密Microsoft 信息保护文档 | 可用 |
|  | 增强的模拟和位置支持，支持在 SharePoint Online 和 OneDrive for Business | 即将推出 |
|  | 使用 Microsoft Azure 访问 Azure 中的资产扩展内置敏感度标签 | 开发中 |
|  | 通过适用于在线网站的"敏感度标签"细化SharePoint访问策略 | 工程积压工作 |
|  | 强制标签 | 可用 |
|  | 手动标签 | 可用 |
|  | 自动标记的新条件Exchange Online | 开发中 |
| 分析 | 数据分类分析：概述和内容资源管理器 | 可用 |
|  | Office应用程序中的审核和分析 | 可用 |
|  | 活动资源管理器包括Power BI敏感度标签数据 | 可用 |
|  | 活动资源管理器内置筛选器 | 可用 |
|  | 内容资源管理器包括Teams数据 | 开发中 |
|  | 在应用/客户端上自动标记Office机器学习分类器 | 可用 |
| 加密 | 基本 Office 365 邮件加密 (E3)  | 可用 |
|  | 高级Office 365 邮件加密 (E5)  | 可用 |
|  | Office 365 的客户密钥 | 可用 |
|  | 客户密钥：静态数据加密Microsoft 365 | 可用 |
|  | 客户密钥：SharePoint Online 和 OneDrive for Business | 可用 |
|  | 将你自己的密钥 (BYOK) 客户管理的密钥预配生命周期 | 可用 |
|  | 双密钥加密 | 可用 |
|  | Exchange Online Microsoft 托管密钥进行服务加密 | 可用 |
| 数据丢失防护 | 数据丢失防护：警报仪表板和警报体验 | 可用 |
|  | 文件和电子邮件的数据丢失防护 | 可用 |
|  | 数据丢失防护：活动资源管理器中显示的数据 | 可用 |
|  | 数据丢失防护：终结点  | 可用 |
|  | 数据丢失防护：Microsoft Defender for Cloud Apps (以前Microsoft Cloud App Security) 集成 | 可用 |
|  | On-prem 的数据丢失防护 | 开发中 |
|  | 数据丢失防护：概述页 | 可用 |
|  | 数据丢失防护：Teams聊天和频道对话  | 可用 |
| **信息治理** |  |  |
| 信息管理政策 | 信息治理：保留和标记策略的自适应范围 | 可用 |
| | 信息治理：在保留期结束时应用保留标签操作 | 工程积压工作 |
| | 信息治理：将默认保留标签应用于SharePoint、OneDrive for Business库、文件夹和文档集;Exchange收件箱;Office 365组  | 可用 |
| | 信息治理：配置用于阻止编辑记录元数据的能力的选项 | 开发中 |
| | 信息治理：禁用记录解锁 | 开发中 |
| | 信息治理：电子邮件存档 | 可用 |
| | 信息治理：导入 PST | 可用 |
| | 信息治理：手动非记录保留标签 | 可用 |
| | 信息治理：保留锁定 | 可用 |
| | 信息治理：SharePoint Online 和 OneDrive for Business | 可用 |
| | 信息治理：保留标签删除行为在SharePoint | 开发中 |
| | 信息治理：整个组织的保留策略;特定位置或用户;根据特定条件自动 (，例如关键字或敏感信息) ;和 基于事件 | 可用 |
| | 信息治理：保留策略Teams | 可用 |
| | 信息治理：会议录制Teams策略 | 可用 |
| | 信息治理：专用Teams保留策略 | 可用 |
| 记录管理 | 记录管理：删除记录标签的能力 | 可用 |
| | 记录管理：允许记录标签启动"解锁"以用于手动记录声明 | 开发中 |
| | 记录管理：手动应用记录标签 | 可用 |
| | 记录管理：将默认记录标签应用于SharePoint、OneDrive for Business库、文件夹和文档集以及Office 365组 | 可用 |
| | 记录管理：根据特定条件自动应用记录策略 (例如，关键字或敏感信息) ;和 基于事件 | 可用 |
| | 记录管理：使用可训练分类器自动应用记录策略  | 开发中 |
| | 记录管理：禁用记录解锁 | 开发中 |
| | 记录管理：处置评审 | 可用 |
| | 记录管理：文件计划管理器 | 可用 |
| | 记录管理：多阶段处置评审 | 工程积压工作 |
| | 记录管理：Outlook管理提供客户端支持 | 开发中 |
| | 记录管理：Power Automate集成 | 工程积压工作 |
| | 记录管理：处置证明 | 可用 |
| | 记录管理：记录版本控制 | 可用 |
| | 记录管理：法规记录 | 可用 |
| **风险管理** |  |  |
| 客户密码箱 | 客户密码箱 | 可用 |
| 通信合规性 | 通信合规性：为通信合规性策略设置保留期的能力 | 公共预览版 |
| | 通信合规性：访问警报;通知模板;通信策略仪表板 | 可用 |
| | 通信合规性：Teams邮箱的用户的聊天数据 | 可用 |
| | 通信合规性：自动Teams用户是其中成员的所有通信 | 可用 |
| | 通信合规性：冲突模板 | 可用 |
| | 通信合规性：创建客户策略，3 个预配置 | 可用 |
| | 通信合规性：检测成人内容 | 可用 |
| | 通信合规性：检测一段时间的重复行为违反代码 | 可用 |
| | 通信合规性：分类器 | 即将推出 |
| | 通信合规性：升级以进行调查Advanced eDiscovery | 可用 |
| | 通信合规性：Exchange和Teams支持 | 可用 |
| | 通信合规性：策略运行状况检查和暂停策略的能力 | 开发中 |
| | 通信合规性：Power Automate集成 | 开发中 |
| | 通信合规性：从Teams聊天或频道Teams消息 | 可用 |
| | 通信合规性：每个位置报告的敏感信息类型  | 开发中 |
| | 通信合规性：支持七种语言用于威胁、针对性攻击和亵亵分类器 | 可用 |
| | 通信合规性：支持更精细的权限 | 可用 |
| | 通信合规性：支持Teams、Exchange以及删除邮件Teams功能 | 可用 |
| | 通信合规性：Teams对话上下文 | 可用 |
| | 通信合规性：调查期间翻译内容 | 可用 |
| 信息屏障 | 信息屏障 | 可用 |
| 内部风险管理 | 内部风险管理：导出警报的能力 | 可用 |
| | 内部风险管理：显示活动资源管理器数据 | 可用 |
| | 内部风险管理：分析 | 公共预览版 |
| | 内部风险管理：案例仪表板 | 可用 |
| | 内部风险管理：内容资源管理器增强功能 | 可用 |
| | 内部风险管理：解除限制的用户泄露数据 | 开发中 |
| | 内部风险管理：通过离职用户窃取数据 | 可用 |
| | 内部风险管理：按优先用户窃取数据 | 公共预览版 |
| | 内部风险管理：上报以进行调查Advanced eDiscovery | 可用 |
| | 内部风险管理：导出警报 | 公共预览版 |
| | 内部风险管理：常规数据泄露 | 可用 |
| | 内部风险管理：常规安全策略违反 | 开发中 |
| | 内部风险管理：违反安全策略的指标 | 开发中 |
| | 内部风险管理：适用于终结点警报的 Microsoft Defender 指示器 | 开发中 |
| | 内部风险管理：电子邮件Office (Teams、SharePoint、电子邮件)  | 可用  |
| | 内部风险管理：终结点Windows 10指示器 | 公共预览版  |
| | 内部风险管理：对域设置的智能支持 | 可用 |
| | 内部风险管理：Microsoft Teams集成 | 公共预览版 |
| | 内部风险管理：本机触发器 (信号、指示器选择、自定义和活动资源管理器 | 可用 |
| | 内部风险管理：Office、Teams网站SharePoint电子邮件的指示器 | 可用 |
| | 内部风险管理：策略自定义、策略运行状况检查和增强的策略创建向导 | 可用 |
| | 内部风险管理：解除限制的用户泄露数据的策略模板 | 公共预览版 |
| | 内部风险管理：优先用户泄露数据的策略模板 | 公共预览版 |
| | 内部风险管理：用于常规安全策略违反的策略模板 | 开发中 |
| | 内部风险管理：针对优先用户、离职用户和解除限制用户违反安全策略的策略模板 | 开发中 |
| | 内部风险管理：Power Automate集成 | 开发中 |
| | 内部风险管理：优先用户组 | 公共预览版 |
| | 内部风险管理：离开用户违反安全策略 | 开发中 |
| | 内部风险管理：解除限制的用户违反安全策略 | 开发中 |
| | 内部风险管理：优先级用户违反安全策略 | 开发中 |
| | 内部风险管理：支持本机触发器Azure Active Directory删除帐户 | 可用 |
| | 内部风险管理：用户活动报告 | 公共预览版 |
| | 内部风险管理："观察观察者"审核线索 | 可用 |
| **发现 &amp; 响应** |  |  |
| 电子数据展示 | 核心电子数据展示：审核 | 可用 |
| | 核心电子数据展示：案例管理 | 可用 |
| | 核心电子数据展示：OneDrive for Business | 可用 |
| | 核心电子数据展示：导出 | 可用 |
| | 核心电子数据展示：就地保留 | 可用 |
| | 核心电子数据展示：本机导出 | 可用 |
| | 核心电子数据展示：RMS 解密 | 可用 |
| | 核心电子数据展示：搜索 | 可用 |
| | 核心电子数据展示：Microsoft 合规性中心扩展了对在回收站和回收站中搜索SharePoint OneDrive for Business项的支持 | 可用 |
| | Advanced eDiscovery：高级处理 | 可用 |
| | Advanced eDiscovery：案例限制增强功能 | 开发中 |
| | Advanced eDiscovery：收集和查看SharePoint和/或加密OneDrive for Business | 可用 |
| | Advanced eDiscovery：作为脚本Teams对话的集合 | 开发中 |
| | Advanced eDiscovery：通信模板和颁发主管设置 | 开发中 |
| | Advanced eDiscovery：保管人到工作负荷映射 | 可用 |
| | Advanced eDiscovery：保管人通信 | 可用 |
| | Advanced eDiscovery：仪表板 | 可用 |
| | Advanced eDiscovery：数据清除功能Microsoft Teams  | 开发中 |
| | Advanced eDiscovery：深度爬网/索引 | 可用 |
| | Advanced eDiscovery：双字节字符支持 (中文、日语、朝鲜语)  | 可用 |
| | Advanced eDiscovery：电子邮件线程 | 可用 |
| | Advanced eDiscovery：增强的导入保管人向导体验 | 开发中 |
| | Advanced eDiscovery：导出 (下载、导出、添加到另一个视图集)  | 可用 |
| | Advanced eDiscovery：筛选 | 可用 |
| | Advanced eDiscovery：Graph API | 开发中 |
| | Advanced eDiscovery：历史版本 | 开发中 |
| | Advanced eDiscovery：保留优化 | 开发中 |
| | Advanced eDiscovery：将Teams标识为数据源 | 工程积压工作 |
| | Advanced eDiscovery：合法保留Teams私人频道消息 | 可用 |
| | Advanced eDiscovery：Microsoft 合规中心扩展了对在回收站和回收站中搜索SharePoint OneDrive for Business项的支持 | 开发中 |
| | Advanced eDiscovery：近重复标识 | 可用 |
| | Advanced eDiscovery：Core 和 Advanced eDiscovery  | 开发中 |
| | Advanced eDiscovery：新的预测编码模块和处理 | 工程积压工作 |
| | Advanced eDiscovery：非资源数据源 | 可用 |
| | Advanced eDiscovery：非Office 365的 | 可用 |
| | Advanced eDiscovery：预测编码 | 可用 |
| | Advanced eDiscovery：使用加载文件处理导出 | 可用 |
| | Advanced eDiscovery：Redactions | 可用 |
| | Advanced eDiscovery：审阅集 | 可用 |
| | Advanced eDiscovery：查看数据 (查询数据、智能标记、仪表板) 并注释 (修订)  | 可用 |
| | Advanced eDiscovery：搜索词报告 | 可用 |
| | Advanced eDiscovery：单个项目错误修正 | 可用 |
| | Advanced eDiscovery：支持 PST 导出 | 可用 |
| | Advanced eDiscovery：支持来自 OneDrive 和 SharePoint Online (新式附件)  | 可用 |
| | Advanced eDiscovery：支持Teams反应 | 开发中 |
| | Advanced eDiscovery：标记 | 可用 |
| | Advanced eDiscovery：租户报告 | 可用 |
| | Advanced eDiscovery：主题 | 可用 |
| | Advanced eDiscovery：查看者 | 可用 |
| | Advanced eDiscovery：Yammer Advanced eDiscovery Microsoft 合规中心内 | 可用 |
| Audit | 基本审核 | 可用 |
| | 高级审核：访问关键事件 (例如 *MailItemsAccessed*)  | 可用 |
| | 高级审核：审核保留仪表板 | 可用 |
| | 高级审核：审核搜索增强功能 | 工程积压工作 |
| | 高级审核：增加管理活动 API 的带宽 | 可用 |
| | 高级审核：合法保留Teams私人频道消息 | 可用 |
| | 高级审核：记录保留期 (1 年)  | 可用 |
| | 高级审核：审核日志的更长期保留期 (10 年)  | 可用 |
| | 高级审核：邮件转发和邮件发送事件 | 可用 |
| | 高级审核：Microsoft 365安全与合规中心 | 可用 |
| | 高级审核：在 Exchange Online 和 SharePoint Online 中搜索术语事件 | 可用 |
| **遵从性管理** |  |  |
| 合规性管理 | Microsoft 365 合规中心 | 可用 |
| | 合规性管理器 | 可用 |
| | 合规性管理器：持续合规性评估 | 开发中 |
| | 合规性管理器：非资产资产Microsoft 365评估 | 可用 |
| | 双字节字符支持 | 可用 |
| | Microsoft Defender for Cloud Apps (以前是 Microsoft Cloud App Security)  | 可用 |
| **生态系统** |  |  |
| 生态系统 | 第一方数据连接器：HR  | 可用 |
| | 第一方数据连接器：HR 1.2 | 可用 |
| | 第一方数据连接器：物理保护 | 可用 |
| | Graph API Advanced eDiscovery  | 开发中 |
| | Graph公共预览版中的记录 (API)  | 开发中 |
| | Graph导出数据的 Teams API | 开发中 |
| **隐私** |  |  |
| 隐私管理 | Microsoft Priva | 开发中 |

<sup>1</sup> 在重新评估项目计划和优先级时，标识的状态可能会更改。<br/>

**决策点***：确定合规性功能是否满足组织的需求。*
