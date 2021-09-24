---
title: Microsoft 365 合规性计划 - DoD 部署
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: 本指南适用于在美国政府实体或其他处理受政府法规和要求（使用 Microsoft 365 Government – DoD 适合满足这些要求的实体）中部署 Office 365 的 IT 专业人员。
ms.openlocfilehash: 6ad0f21c8cbd9cf6690af4664c958c4ffdab7746
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/24/2021
ms.locfileid: "59671612"
---
# <a name="plan-for-microsoft-365-compliance---dod-deployments"></a>Microsoft 365 合规性计划 - DoD 部署

本指南适用于在美国政府实体或其他处理受政府法规和要求（使用 Microsoft 365 Government – DoD 适合满足这些要求的实体）中部署 Office 365 的 IT 专业人员。

> [!NOTE]
> 如果你的组织已满足 Microsoft 365 政府 – DoD 资格要求，并且已申请并被接受加入该计划，你可以跳过步骤 1 和步骤 2，直接转到步骤 3。

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---dod-and-meets-eligibility-requirements"></a>步骤 1. 确定你的组织是否需要Microsoft 365政府 - DoD 并满足资格要求

美国政府Microsoft 365 DoD 环境符合美国政府云服务要求。

除了享受组织功能外，Office 365还受益于政府 – doD Microsoft 365独有的功能：

- 从逻辑上说，组织的客户内容与 Microsoft 商业或Office 365内容隔离。
- 您组织的客户内容存储在美国境内。
- 对组织的客户内容的访问权限只限于屏蔽的 Microsoft 员工。
- Microsoft 365政府 - DoD 符合美国公共部门客户所需的认证和资格鉴定。

有关美国政府 /Microsoft 365 DoD 产品/服务（包括资格[Office 365 政府版）详细信息](https://products.office.com/government/compare-office-365-government-plans)，

美国政府[Office 365](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md)说明介绍了该平台的好处，这些优势以满足美国内的合规性要求为中心。

> [!TIP]
> 您可能需要将服务说明中的信息表转移到 Excel 工作簿，并添加两列："与我的组织 **Y/N** 相关"和"满足我的组织 **Y/N 的需求"。** 然后，您可以与同事一起查看此列表，以确认此服务满足您组织的需求。

**决策点**：<br/>
- *决定Microsoft 365政府 - DoD 是否适用于你的组织。*
- *确认你的组织满足资格要求。*

> [!NOTE]
> Microsoft 365政府 - DoD 仅在美国可用。 非美国政府客户可以从多个计划Office 365 政府版[选择](https://products.office.com/government/compare-office-365-government-plans)。

## <a name="step-2-apply-for-microsoft-365-government---dod"></a>步骤 2. 申请政府Microsoft 365 - DoD

在决定此服务适合你的组织后，开始 [应用此服务的过程](https://products.office.com/government/eligibility-validation)。

## <a name="step-3-understand-microsoft-365-government---dod-default-security-settings"></a>步骤 3. 了解Microsoft 365政府 - DoD 默认安全设置

建议在修改管理员和安全设置之前，花些时间仔细查看这些设置，并考虑对合规性的影响，然后再对默认安全设置进行更改。

**决策点**：决定是否要修改任何默认的 Microsoft 365 政府 - DoD 安全设置，通过解析可以先了解可能进行的任何 *更改的影响。*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--dodsup1sup"></a>步骤 4. 了解当前在政府/Microsoft 365不可用或禁用的功能 – DoD<sup>1</sup>

为满足政府云客户的要求，政府版 -doD 和企业Microsoft 365有一些差异。 请参阅下表，了解哪些功能可用。 有关[在](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent)Microsoft 365 路线图上发布的最新合规性产品更新，请参阅此处。<br><br>

| 领域  | 功能  | DoD 状态  |
|-------|----------|-------------|
| **信息保护**  | | |
| 敏感信息类型  | 精确数据匹配  | 可用  |
| 敏感度标签  | Exchange Online、SharePoint Online 和 OneDrive for Business 的自动分类和OneDrive for Business  | 可用 |
| | Office Web、Windows 和 Mac)  (平台Office Word、Excel、PowerPoint、Outlook)  (应用的自动分类和Windows)   | 可用  |
| | 自动分类和标记客户端Office - 移动  | 工程积压工作  |
| | 自动分类和标记Teams、Microsoft 365组SharePoint网站  | 可用  |
| | 强制标记  | 可用  |
| | iOS、Android 和 Office 应用中 (敏感度Windows)   | 可用  |
| | 对邮件进行仅加密保护的敏感度Outlook配置  | 可用  |
| | 统一标记客户端和扫描程序  | 可用  |
| 分析  | 数据分类：概述和内容资源管理器  | 即将推出  |
| | 分析：在应用/客户端上自动标记Office机器学习分类器  | 开发中 |
| 加密  | 基本 Office 365 邮件加密 (E3)   | 可用  |
| | 高级Office 365 邮件加密 (E5)   | 可用  |
| | 将你自己的密钥 (BYOK) 客户管理的密钥预配生命周期  | 可用  |
| | Office 365 的客户密钥  | 可用  |
| | 用于多Microsoft 365加密的客户密钥 | 开发中  |
| | SharePoint Online 和 OneDrive for Business 的客户密钥 | 可用 |
| | 双密钥加密  | 可用  |
| 数据丢失防护  | 文件和电子邮件 (DLP) 数据丢失防护  | 可用  |
| | DLP：警报仪表板和警报体验  | 可用  |
| | 用于聊天Teams对话的 DLP  | 可用  |
| | DLP 终结点 (公共预览)   | 公共预览版 |
| | DLP 概述页  | 即将推出  |
| **信息治理**  | | |
| 信息管理政策  | 信息治理：保留和标记策略的自适应范围 | 工程积压工作  |
| | 信息治理：为收件箱应用Exchange标签  | 可用  |
| | 信息治理：电子邮件存档  | 可用  |
| | 信息治理：导入 PST  | 可用  |
| | 信息治理：保留锁定  | 可用  |
| | 信息治理：具有可训练分类器保留策略  | 开发中  |
| | 信息治理：聊天Teams策略  | 可用  |
| | 信息治理：会议录制Teams策略  | 可用  |
| | 信息治理：私人Teams邮件的保留策略  | 开发中  |
| | 信息治理：保留和标记策略自适应范围  | 开发中  |
| 记录管理  | 记录管理：手动应用记录标签  | 可用  |
| | 记录管理：将默认记录标签应用于SharePoint、OneDrive for Business库、文件夹和文档集;和 Office 365 组  | 可用  |
| | 记录管理：基于特定条件自动记录策略 (例如，关键字或敏感信息) ;和 基于事件  | 可用  |
| | 记录管理：处置评审  | 可用  |
| | 记录管理：文件计划管理器  | 可用  |
| | 记录管理：多阶段处置评审  | 开发中  |
| | 记录管理：云附件的保留和自动标记  | 开发中  |
| | 记录管理：处置证明  | 可用  |
| | 记录管理：记录版本控制  | 可用  |
| | 记录管理：法规记录  | 可用  |
| **风险管理**  | | |
| 客户密码箱 | 客户密码箱  | 可用  |
| 通信合规性  | 通信合规性：在公共预览版中为通信合规性策略 (保留)   | 工程积压工作  |
| | 通信合规性：访问警报;通知模板;通信策略仪表板  | 可用  |
| | 通信合规性：Teams邮箱的用户的聊天数据  | 可用  |
| | 通信合规性：冲突模板  | 可用  |
| | 通信合规性：创建客户策略，3 个预配置  | 可用  |
| | 通信合规性：检测成人内容  | 工程积压工作  |
| | 通信合规性：检测一段时间的重复行为违反代码  | 可用  |
| | 通信合规性：升级以进行调查Advanced eDiscovery  | 可用  |
| | 通信合规性：利用 OCR (光学字符) 提取和评估消息  | 可用  |
| | 通信合规性：Microsoft Teams集成  | 开发中  |
| | 通信合规性：策略运行状况检查和暂停策略的能力  | 开发中  |
| | 通信合规性：Power Automate集成  | 工程积压工作  |
| | 通信合规性：每个位置报告的敏感信息类型  | 开发中  |
| | 通信合规性：支持Teams、Exchange和删除Teams邮件  | 可用  |
| | 通信合规性：支持更精细的权限  | 可用  |
| | 通信合规性：支持 7 种语言的威胁、针对性攻击和亵亵分类器  | 可用  |
| | 通信合规性：调查期间翻译运行状况内容  | 开发中  |
| 信息屏障  | 信息屏障  | 即将推出  |
| 内部风险管理  | 内部风险管理：审核日志  | 公共预览版  |
| | 内部风险管理：案例仪表板  | 可用  |
| | 内部风险管理：活动资源管理器中显示的数据  | 公共预览版  |
| | 内部风险管理：数据在内容资源管理器中显示  | 开发中  |
| | 内部风险管理：通过离职用户窃取数据  | 可用  |
| | 内部风险管理：终结点上活动Windows 10指示器  | 开发中  |
| | 内部风险管理：升级Advanced eDiscovery  | 可用  |
| | 内部风险管理：导出警报  | 公共预览版  |
| | 内部风险管理：常规数据泄露  | 可用  |
| | 内部风险管理：对内部风险管理中的域设置的智能支持  | 公共预览版  |
| | 内部风险管理：适用于终结点警报的 Microsoft Defender 指示器  | 工程积压工作  |
| | 内部风险管理：违反安全策略的指标  | 开发中  |
| | 内部风险管理：终结点Windows 10指示器 | 公共预览版  |
| | 内部风险管理：调查内部风险管理警报  | 可用  |
| | 内部风险管理：Microsoft Teams Power Automate集成  | 开发中  |
| | 内部风险管理：本机触发器支持Azure Active Directory帐户删除 | 公共预览版  |
| | 内部风险管理：通知模板  | 可用  |
| | 内部风险管理：Office、Teams网站SharePoint电子邮件的指示器  | 可用  |
| | 内部风险管理：解除限制的用户泄露数据的策略模板  | 工程积压工作  |
| | 内部风险管理：优先用户泄露数据的策略模板  | 公共预览版  |
| | 内部风险管理：用于常规安全策略违反的策略模板  | 工程积压工作  |
| | 内部风险管理：优先用户和离职用户违反安全策略的策略模板 | 公共预览版 |
| | 内部风险管理：解除限制的用户违反安全策略的策略模板 | 工程积压工作  |
| | 内部风险管理：策略自定义、策略运行状况检查和增强的策略创建向导  | 公共预览版  |
| | 内部风险管理：优先用户组  | 公共预览版  |
| | 内部风险管理：支持本机触发器Azure Active Directory删除帐户 | 公共预览版  |
| | 内部风险管理："观察观察程序"审核线索 | 公共预览版  |
| **发现&响应**  | | |
| 电子数据展示 | 核心电子数据展示：审核  | 可用  |
| | 核心电子数据展示：案例管理  | 可用  |
| | 核心电子数据展示：OneDrive for Business  | 可用  |
| | 核心电子数据展示：导出  | 可用  |
| | 核心电子数据展示：就地保留  | 可用  |
| | 核心电子数据展示：本机导出  | 可用  |
| | 核心电子数据展示：RMS 解密  | 可用  |
| | 核心电子数据展示：搜索  | 可用  |
| | Advanced eDiscovery：高级处理  | 可用  |
| | Advanced eDiscovery：保管人到工作负荷映射  | 可用  |
| | Advanced eDiscovery：保管人通信  | 可用  |
| | Advanced eDiscovery：仪表板  | 可用  |
| | Advanced eDiscovery：数据清除功能Microsoft Teams  | 工程积压工作  |
| | Advanced eDiscovery：深度爬网/索引  | 可用  |
| | Advanced eDiscovery：对中文、日语和朝鲜语的双字节支持  | 可用  |
| | Advanced eDiscovery：电子邮件线程  | 可用  |
| | Advanced eDiscovery：导出 (下载、导出、添加到其他审阅集)   | 可用  |
| | Advanced eDiscovery：筛选  | 可用  |
| | Advanced eDiscovery：保留优化  | 开发中  |
| | Advanced eDiscovery：合法保留Teams私人频道消息  | 开发中  |
| | Advanced eDiscovery：Microsoft 合规中心扩展了对搜索和导出核心回收站SharePoint、OneDrive for Business回收站和回收站中的Advanced eDiscovery  | 开发中  |
| | Advanced eDiscovery：近重复标识  | 可用  |
| | Advanced eDiscovery：新的预测编码模块  | 开发中  |
| | Advanced eDiscovery：非资源数据源  | 可用  |
| | Advanced eDiscovery：非Office 365的  | 工程积压工作  |
| | Advanced eDiscovery：预测编码  | 可用  |
| | Advanced eDiscovery：使用加载文件处理导出  | 可用  |
| | Advanced eDiscovery：Redactions  | 可用  |
| | Advanced eDiscovery：审阅集  | 可用  |
| | Advanced eDiscovery：查看数据 (查询数据、智能标记、仪表板) 并注释 (修订)   | 可用  |
| | Advanced eDiscovery：搜索词报告  | 可用  |
| | Advanced eDiscovery：支持来自 OneDrive 和 SharePoint Online (新式)   | 可用  |
| | Advanced eDiscovery：支持Teams反应  | 工程积压工作  |
| | Advanced eDiscovery：标记  | 可用  |
| | Advanced eDiscovery：租户报告  | 可用  |
| | Advanced eDiscovery：主题  | 可用  |
| | Advanced eDiscovery：查看者  | 可用  |
| | Advanced eDiscovery：Yammer Advanced eDiscovery Microsoft 合规中心内  | 可用  |
| Audit  | 基本审核  | 可用  |
| | 高级审核：访问关键事件 (例如 mailitemsaccessed)   | 可用  |
| | 高级审核：增加管理活动 API 的带宽  | 可用  |
| | 高级审核：1 年后 (保留)   | 可用  |
| | 高级审核：审核日志的更长期保留期 (10 年)   | 即将推出  |
| | 高级审核：邮件转发和邮件发送事件  | 可用  |
| | 高级审核：安全与合规中心可用性  | 可用  |
| | 高级审核：在 Exchange Online 和 SharePoint Online 中搜索术语事件  | 开发中  |
| | 高级审核：Teams对邮件的反应  | 工程积压工作  |
| **遵从性管理** | | |
| 合规性管理  | Microsoft 365 合规中心  | 可用  |
| | Microsoft Cloud App Security  | 可用  |
| | 合规性管理器  | 可用  |
| | 双字节字符支持  | 可用  |
| **生态系统** | | |
| 生态系统  | 第一方数据连接器：HR  | 开发中 |
| | 第一方数据连接器：物理保护  | 开发中  |
| | Graph适用于 Advanced eDiscovery  | 工程积压工作  |

<sup>1</sup> 在重新评估项目计划和优先级时，标识的状态可能会更改。<br/>

**决策点***：确定合规性功能是否满足组织的需求。*
