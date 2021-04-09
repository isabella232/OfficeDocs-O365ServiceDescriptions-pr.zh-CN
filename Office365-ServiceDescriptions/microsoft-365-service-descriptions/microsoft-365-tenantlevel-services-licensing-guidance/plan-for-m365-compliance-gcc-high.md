---
title: Microsoft 365 合规性计划 - GCC High
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 本指南适用于在美国政府实体或其他实体中推动 Office 365 部署的 IT 专业人员，这些实体处理受政府法规和要求（使用 Microsoft 365 政府版 – GCC High 适合满足这些要求）的数据。
ms.openlocfilehash: 016b3596829337cffb2c5a14813c5927f010e432
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652606"
---
# <a name="plan-for-microsoft-365-compliance--gcc-high"></a>Microsoft 365 合规性计划 – GCC High

本指南适用于在美国政府实体或其他实体中推动 Office 365 部署的 IT 专业人员，这些实体处理受政府法规和要求（使用 Microsoft 365 政府版 – GCC High 适合满足这些要求）的数据。

> [!NOTE]
>如果你的组织已满足 Microsoft 365 政府版 – GCC 高资格要求，并且已申请并被接受加入该计划，你可以跳过步骤 1 和步骤 2，直接转到步骤 3。
 
## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government--gcc-high-and-meets-eligibility-requirements"></a>步骤 1. 确定你的组织是否需要 Microsoft 365 政府版 – GCC High 并满足资格要求

Microsoft 365 政府版 - GCC 高环境符合美国政府云服务要求。 除了享受 Office 365 的特性和功能之外，组织还可从 Microsoft 365 政府版 - GCC High 独有的以下功能中获益：

- 组织的客户内容在逻辑上与 Microsoft 商业 Office 365 服务中的客户内容隔离。
- 您组织的客户内容存储在美国境内。
- 对组织的客户内容的访问权限只限于屏蔽的 Microsoft 员工。
- Microsoft 365 政府版 – GCC High 符合美国公共部门客户所需的认证和资格鉴定。

有关 Microsoft 365 政府版 – GCC 高产品/服务（适用于美国政府版客户）的信息，请参阅 [Office 365 政府](https://products.office.com/government/compare-office-365-government-plans)版计划，包括资格要求。

[Office 365 美国政府](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md)版服务说明介绍了该平台的好处，其中心内容是满足美国的合规性要求。

> [!TIP]
> 您可能需要将服务说明中的信息表转移到 Excel 工作簿，并添加两列："与我的组织 **Y/N** 相关"和"满足我的组织 **Y/N 的需求"。** 然后，您可以与同事一起查看此列表，以确认此服务满足您组织的需求。

**决策点**：<br/>
- *确定 Microsoft 365 政府版 - GCC-High是否适合你的组织。*
- *确认你的组织满足资格要求。*

> [!NOTE]
> Microsoft 365 政府版 - GCC High 仅在美国可用。 非美国政府客户可以从多个 [Office 365 政府版计划中选择](https://products.office.com/government/compare-office-365-government-plans)。

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>步骤 2. 适用于 Microsoft 365 政府版 – GCC-High

在决定此服务适合你的组织后，开始 [应用此服务的过程](https://products.office.com/government/eligibility-validation)。
 
## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>步骤 3. 了解 Microsoft 365 政府版 – GCC-High默认设置

建议在修改管理员和安全设置之前，花些时间仔细查看这些设置，并考虑对合规性的影响，然后再对默认安全设置进行更改。

**决策点**：决定是否要修改任何默认的 *Microsoft 365* 政府版 - GCC-High安全设置，解决后首先要了解可能进行的任何更改的影响。

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-highsup1sup"></a>步骤 4. 了解 Microsoft 365 政府版中当前不可用或默认禁用的功能 – GCC-High<sup>1</sup>

为满足政府云客户的要求，Microsoft 365 政府版与企业版计划之间存在GCC-High差异。 请参阅下表，了解哪些功能可用。 有关 [Microsoft](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) 365 路线图上发布的最新合规性产品更新，请参阅此处。<br><br>

| 区域                                    | 功能                                         | GCC 状态             |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **信息保护**              | 统一标记客户端和扫描程序         | 可用              |
|                                         | 精确数据匹配          | 可用              |
|                                         | Exchange Online、SharePoint Online 和 OneDrive 的自动分类和标记                      | 即将推出              |
|                                         | Office 应用的自动分类和标签 (Word、Excel、PowerPoint、Outlook) Web、Android、iOS、Windows 和 Mac            | 开发中 |
|                                         | Office 客户端的自动分类和标记 (移动)                                        | 工程积压工作              |
|                                         | Teams 的自动分类和标记                            | 工程积压工作 |
|                                         | 数据分类分析：概述和内容资源管理器                            | 工程积压工作 |
|                                         | 分析：在服务器端使用自动标记的机器学习分类器                           | 工程积压工作  |
|                                         | 分析：使用 Office 应用/客户端上的自动标记的机器学习分类器                           | 工程积压工作  |
|                                         | 基本 Office 365 邮件加密 (E3)                             | 可用              |
|                                         | 高级 Office 365 邮件加密 (E5)   | 可用              |
|                                         | Office 365 的客户密钥    | 可用 |
|                                         | 将你自己的密钥 (BYOK) 客户管理的密钥预配生命周期                            | 可用 |
|                                         | 保留 (跨 Azure 信息保护和 Active Directory (AD) Rights Management 的 HYOK) 自己的密钥 (预览版)                          | 可用 |
|                                         | 双密钥加密                           | 可用 |
|                                         | 加密：使用 WXP Web 应用共同创作加密文档         | 工程积压工作 |
|                                         | 文件和电子邮件 (DLP) 数据丢失防护         | 可用 |
|                                         | 用于 Teams 聊天和频道对话的 DLP | 工程积压工作 |
|                                         | DLP 终结点 | 工程积压工作 |
| **信息治理** | 信息治理：电子邮件存档                                       | 可用              |
|                                         | 信息治理：保留锁定          | 可用              |
|                                         | 信息治理：导入 PST                      | 可用              |
|                                         | 信息治理：手动非记录保留标签            | 可用 |
|                                         | 信息治理：SharePoint/OneDrive for Business 库、文件夹和文档集的默认保留标签;Exchange 收件箱;和 Office 365 组 | 可用              |
|                                         | 信息治理：整个组织的保留策略;特定位置或用户;根据特定条件自动 (，例如关键字或敏感信息) ;和 基于事件                                       | 可用              |
|                                         | 信息治理：Teams 的保留策略                            | 工程积压工作 |
|                                         | 信息治理：使用 SharePoint 合成分类的保留标签                            | 工程积压工作 |
|                                         | 信息治理：具有可训练分类器保留策略                            | 工程积压工作 |
|                                         | 信息治理：Teams 会议录制的保留策略                            | 工程积压工作 |
|                                         | 信息治理：Yammer 的保留策略                            | 工程积压工作 |
|                                         | 记录管理：记录标签的手动分类                           | 可用              |
|                                         | 记录管理：SharePoint、OneDrive for Business 库、文件夹和文档集的默认记录标签;和 Office 365 组                              | 可用              |
|                                         | 记录管理：基于特定条件（例如，关键字 (敏感信息）的自动记录) ;和 基于事件                            | 可用              |
|                                         | 记录管理：处置评审  | 可用              |
|                                         | 记录管理：文件计划管理器    | 可用 |
|                                         | 记录管理：处置证明                            | 可用 |
|                                         | 记录管理：记录版本控制                         | 可用 |
|                                         | 记录管理：法规记录                         | 工程积压工作 |
|                                         | 记录管理：多阶段处置评审 | 工程积压工作 |
|                                         | 记录管理：使用 SharePoint Syntex 分类应用记录标签 | 工程积压工作 |
| **内部风险管理**             | 客户密码箱                                | 可用            |
|                                         | 内部风险管理：Teams、SharePoint 网站和电子邮件的 Office 指标                         | 开发中 |
|                                         | 内部风险管理：通过离职用户窃取数据                        | 开发中 |
|                                         | 内部风险管理：常规数据泄露                                | 开发中              |
|                                         | 内部风险管理：调查内部风险管理警报                                   | 开发中              |
|                                         | 内部风险管理：案例仪表板、内容资源管理器和通知模板 | 开发中 |
|                                         | 内部风险管理：升级以调查高级电子数据展示 | 开发中|
|                                         | 内部风险管理：Windows 10 版本 1809 及更高版本上活动的设备指示器 | 工程积压工作|
|                                         | 内部风险管理：安全策略违反 (预览版)  | 工程积压工作|
|                                         | 内部风险管理：适用于终结点警报的 Microsoft Defender (预览版)  | 工程积压工作|
|                                         | 内部风险管理：用于按优先用户泄露数据的策略模板 (预览)  | 工程积压工作 |
|                                         | 内部风险管理：针对预览版中解除限制的用户 (泄露)  | 工程积压工作 |
|                                         | 内部风险管理：预览版中用于常规安全策略违反 (策略)  | 工程积压工作 |
|                                         | 内部风险管理：针对优先级用户、离职用户、解除限制的用户违反安全策略的策略模板 (预览)  | 工程积压工作 |
|                                         | 内部风险管理：策略自定义 (预览)  | 工程积压工作 |
|                                         | 内部风险管理：导出警报 (预览)  | 工程积压工作 |
|                                         | 内部风险管理：优先用户组 (预览)  | 工程积压工作 |
|                                         | 通信合规性 (incl。监督策略) ：创建客户策略，3 个预配置  | 开发中 |
|                                         | 通信合规性 (incl。监督策略) ：支持 Teams、Exchange 和删除 Teams 消息 | 开发中 |
|                                         | 通信合规性 (incl。监督策略) ：访问警报;通知模板;通信策略仪表板 | 开发中  |
|                                         | 通信合规性 (incl。监督策略) ：升级以调查高级电子数据展示 | 开发中 |
|                                         | 通信合规性 (incl。监督策略) ：检测成人内容 | 开发中 |
|                                         | 通信合规性 (incl。监督策略) ：检测一段时间的重复行为违反代码 | 即将推出 |
|                                         | 通信合规性 (incl。监督策略) ：支持更精细的权限 | 即将推出 |
|                                         | 通信合规性 (incl。监督策略) ：分析具有 On-prem 邮箱的用户的 Teams 聊天数据 | 即将推出 |
|                                         | 通信合规性 (incl。监督策略) ：冲突模板 | 工程积压工作 |
|                                         | 通信合规性 (incl。监督策略) ：忽略电子邮件签名或免责声明的能力 | 工程积压工作 |
|                                         | 通信合规性 (incl。监督策略) ：内部风险管理措施 | 工程积压工作 |
|                                         | 通信合规性 (incl。监督策略) ：策略运行状况检查和暂停策略的能力 | 工程积压工作 |
|                                         | 通信合规性 (incl。监督策略) ：调查期间翻译运行状况内容 | 工程积压工作 |
|                                         | 通信合规性 (incl。监督策略) ：消耗和检测 | 工程积压工作 |
|                                         | 信息屏障 | 工程积压工作 |
|                                         | 特权访问管理                    | 工程积压工作 |
| **发现&响应**                  | 核心电子数据展示：就地保留                            | 可用              |
|                                         | 核心电子数据展示：案例管理                                 | 可用              |
|                                         | 核心电子数据展示：搜索                                          | 可用              |
|                                         | 核心电子数据展示：导出                                          | 可用              |
|                                         | 核心电子数据展示：RMS 解密                                  | 可用              |
|                                         | 核心电子数据展示：本机导出                                   | 可用              |
|                                         | 核心电子数据展示：审核                                        | 可用              |
|                                         | 核心电子数据展示：Microsoft 合规性中心扩展了对 SharePoint 和 OneDrive for Business 回收站中项目的搜索和导出支持                                        | 开发中              |
|                                         | 高级电子数据展示：高级处理                             | 可用 |
|                                         | 高级电子数据展示：保管人到工作负荷的映射                             | 可用 |
|                                         | 高级电子数据展示：保管人通信                             | 可用 |
|                                         | 高级电子数据展示：仪表板                             | 可用 |
|                                         | 高级电子数据展示：电子邮件线程                                 | 可用 |
|                                         | 高级电子数据展示： (下载、导出、添加到另一审阅集)                    | 可用 |
|                                         | 高级电子数据展示：筛选                                          | 可用 |
|                                         | 高级电子数据展示：Teams 私人频道消息的法律保留                               | 可用 |
|                                         | 高级电子数据展示：近重复标识                 | 可用 |
|                                         | 高级电子数据展示：非安全数据源                                         | 可用 |
|                                         | 高级电子数据展示：非 Office 365 ingestion                                         | 可用 |
|                                         | 高级电子数据展示：预测编码                                      | 可用 |
|                                         | 高级电子数据展示：使用加载文件处理导出                                       | 可用 |
|                                         | 高级电子数据展示：Redactions                   | 可用 |
|                                         | 高级电子数据展示：审阅集                        | 可用 |
|                                         | 高级电子数据展示：查看 (查询数据、智能标记、仪表板) ，并注释 (修订)                                      | 可用 |
|                                         | 高级电子数据展示：搜索词报告                             | 可用 |
|                                         | 高级电子数据展示：单个项目错误修正                        | 可用 |
|                                         | 高级电子数据展示：支持 PST 导出                              | 即将推出 |
|                                         | 高级电子数据展示：支持从 OneDrive 和 SharePoint Online 链接的内容 (新式)                               | 可用 |
|                                         | 高级电子数据展示：标记                              | 可用 |
|                                         | 高级电子数据展示：租户报告                              | 可用 |
|                                         | 高级电子数据展示：主题                               | 可用 |
|                                         | 高级电子数据展示：查看者                              | 可用 |
|                                         | 高级电子数据展示：Microsoft 合规性中心中的 Yammer 高级电子数据展示                              | 可用 |
|                                         | 高级电子数据展示：高级电子数据展示的 CJK/Double 字节支持                              | 开发中 |
|                                         | 高级电子数据展示：支持 Teams 反应                             | 开发中 |
|                                         | 高级电子数据展示：Microsoft 合规性中心扩展了对 SharePoint 和 OneDrive for Business 回收站中项目的搜索和导出支持                               | 工程积压工作 |
|                                         | 基本审核                              | 可用 |
|                                         | 高级审核：访问关键事件 (例如 mailitemsaccessed)                               | 可用 |
|                                         | 高级审核：增加管理活动 API 的带宽                              | 可用 |
|                                         | 高级审核：Teams 私人频道消息的法律保留                              | 可用 |
|                                         | 高级审核：记录保留期 (1 年)                               | 即将推出 |
|                                         | 高级审核：安全与合规中心可用性                              | 可用 |
|                                         | 高级审核：审核日志的更长期保留期 (10 年)                               | 工程积压工作 |
|                                         | 高级审核：邮件转发和邮件发送事件                              | 工程积压工作 |
|                                         | 高级审核：已处理的审核见解                              | 工程积压工作 |
|                                         | 高级审核：Exchange Online 和 SharePoint Online 中的搜索词事件                              | 工程积压工作 |
|    **遵从性管理**            | Microsoft 365 安全与合规中心                              | 可用 |
|                                         | 合规性管理器                                 | 可用              |
|                                         | Microsoft Cloud App Security                                 | 可用              |
|                                         | 双字节字符支持                                 | 工程积压工作              |
|    **生态系统**            | 适用于高级电子数据展示的图形 API                              | 开发中 |
|                                         | 第一方数据连接器                                 | 工程积压工作              |
|                                         | 第三方数据连接器                                 | 工程积压工作              |
|                                         | Teams 导出数据的图形 API                                 | 工程积压工作              |

<sup>1</sup> 在重新评估项目计划和优先级时，标识的状态可能会更改。<br/>

**决策点***：确定合规性功能是否满足组织的需求。*