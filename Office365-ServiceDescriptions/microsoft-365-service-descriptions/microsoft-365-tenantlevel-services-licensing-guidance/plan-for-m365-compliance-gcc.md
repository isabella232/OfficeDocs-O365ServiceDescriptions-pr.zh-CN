---
title: Microsoft 365 合规性计划 - GCC
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 本指南适用于在美国联邦、州、地方、地方、地区或地区政府实体或其他处理受政府法规和要求（如果适合使用 Microsoft 365 政府版 - GCC 以满足这些要求的实体）中部署 Office 365 的 IT 专业人员。
ms.openlocfilehash: 44dd4a10560fb5bd0d1c0f36f3290b621798d03d390573d789b99d62047bad1e
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/06/2021
ms.locfileid: "54663265"
---
# <a name="plan-for-microsoft-365-compliance--gcc"></a>规划Microsoft 365合规性 – GCC

本指南适用于在美国联邦、州、地方、地方、地区或地区政府实体或其他处理受政府法规和要求（如果适合使用 Microsoft 365 政府版 - GCC 以满足这些要求的实体）中部署 Office 365 的 IT 专业人员。

> [!NOTE]
> 如果你的组织已满足 Microsoft 365 Government - GCC 资格要求，并且已申请并被接受加入该计划，你可以跳过步骤 1 和步骤 2，直接转到步骤 3。

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---gcc-and-meets-eligibility-requirements"></a>步骤 1. 确定你的组织是否需要Microsoft 365政府 - GCC并满足资格要求

政府版 Microsoft 365 - GCC 环境符合美国政府对云服务（包括 FedRAMP 中等）的要求，以及针对刑事犯罪和联邦税务信息系统 (CJI 和 FTI 数据类型的要求) 。

除了享受组织的Office 365功能之外，组织还可从政府特有的以下功能Microsoft 365 - GCC：

- 在逻辑上，组织的客户内容与 Microsoft 商业或Office 365内容隔离。

- 您组织的客户内容存储在美国境内。

- 对组织的客户内容的访问权限只限于屏蔽的 Microsoft 员工。

- Microsoft 365政府 - GCC符合美国公共部门客户所需的认证和资格鉴定。

有关美国政府政府 - Microsoft 365产品/GCC产品/服务Office 365 政府版[计划，](https://products.office.com/government/compare-office-365-government-plans)包括资格要求。

美国政府[Office 365](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md)说明介绍了该平台的好处，这些优势以满足美国的合规性要求为中心。

> [!TIP]
> 您可能希望将服务说明中的信息表转移到 Excel 工作簿，并添加两列："与我的组织 **Y/N** 相关"和"满足我的组织 **Y/N 的需求"。** 然后，您可以与同事一起查看此列表，以确认此服务满足您组织的需求。

> [!NOTE]
> Microsoft 365政府 - GCC仅适用于美国。 非美国政府客户可以从多个计划Office 365 政府版[选择](https://products.office.com/government/compare-office-365-government-plans)。

**决策点**： <br/>
- *决定Microsoft 365政府 - GCC是否适合你的组织。*
- *确认你的组织满足资格要求。*

## <a name="step-2-apply-for-microsoft-365-government---gcc"></a>步骤 2. 申请政府Microsoft 365 - GCC

在决定此服务适合你的组织后，开始 [应用此服务的过程](https://products.office.com/government/eligibility-validation)。

## <a name="step-3-understand-microsoft-365-government---gcc-default-security-settings"></a>步骤 3. 了解 Microsoft 365 政府 - GCC默认安全设置

建议在修改管理员和安全设置之前，花些时间仔细查看这些设置，并考虑对合规性的影响，然后再对默认安全设置进行更改。

**决策点**：决定是否要修改任何默认的政府Microsoft 365 - GCC安全设置，解决以首先了解可能进行的任何 *更改的影响。*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gccsup1sup"></a>步骤 4. 了解当前在政府/Microsoft 365不可用或禁用的功能 – GCC<sup>1</sup>

为了适应政府云客户的要求，政府版政府计划与企业Microsoft 365计划GCC存在一些差异。 请参阅下表，了解哪些功能可用。 有关[在](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent)Microsoft 365 路线图上发布的最新合规性产品更新，请参阅此处。<br><br>

| 区域 | 功能 | GCC状态 |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **信息保护**              | 统一标记客户端和扫描程序         | 可用              |
|                                         | 精确数据匹配          | 可用              |
| 敏感度标签                    | Exchange Online、SharePoint Online 和 OneDrive 的自动分类和OneDrive                      | 可用         |
| 敏感度标签                    | 跨平台 Office 应用 (Word、Excel、PowerPoint、Outlook) 的自动分类和Outlook)  (Web、Android、iOS、Windows 和 Mac)  |  可用              |
| 敏感度标签                    | 移动版客户端的自动分类Office (标记)                                        | 工程积压工作              |
| 敏感度标签                    | 自动分类和标记Teams、Microsoft 365组SharePoint网站                            | 可用 |
| 分析                               | 数据分类分析：概述和内容资源管理器                            | 可用 |
| 分析                               | 分析：在服务器端使用自动标记的机器学习分类器                           | 工程积压工作  |
| 分析                               | 分析：在应用/客户端上自动标记Office机器学习分类器                           | 即将推出 |
| 加密                              | 基本 Office 365 邮件加密 (E3)                             | 可用              |
| 加密                              | 高级Office 365 邮件加密 (E5)   | 可用              |
| 加密                              | Office 365 的客户密钥    | 可用 |
| 加密                              | 客户密钥：静态数据加密Microsoft 365    | 即将推出 |
| 加密                              | 将你自己的密钥 (BYOK) 客户管理的密钥预配生命周期                            | 可用 |
| 加密                              | 双密钥加密                           | 可用 |
| 加密                              | Exchange Online Microsoft 托管密钥进行服务加密         | 可用 |
| 数据丢失防护                    | 文件和电子邮件 (DLP) 数据丢失防护         | 可用 |
| 数据丢失防护                    | 用于聊天Teams对话的 DLP         | 可用 |
| 数据丢失防护                    | DLP 终结点 | 即将推出 |
| 数据丢失防护                    | 警报仪表板 | 开发中 |
| 数据丢失防护                    | “概述”页 | 开发中 |
| **信息治理** | 保留和标记策略的自适应范围                 | 工程积压工作              |
| 信息治理                 | 电子邮件存档          | 可用              |
| 信息治理                 | 文档、文档SharePoint、OneDrive for Business文件夹和文档集的默认保留标签;Exchange收件箱;和 Office 365 组          | 可用              |
| 信息治理                 | 导入 PST                      | 可用              |
| 信息治理                 | 手动非记录保留标签            | 可用 |
| 信息治理                 | 保留锁定            | 可用 |
| 信息治理                 | 整个组织的保留策略;特定位置或用户;根据特定条件自动 (，例如关键字或敏感信息) ;和 基于事件                                       | 可用              |
| 信息治理                 | 保留策略Teams                            | 可用 |
| 信息治理                 | 用于会议录制Teams策略                            | 开发中 |
| 信息治理                 | 私人频道Teams策略                            | 工程积压工作 |
| 信息治理                 | 共享频道Teams策略                            | 工程积压工作 |
| 信息治理                 | 具有可训练分类器保留策略                            | 工程积压工作 |
| 信息治理                 | 保留策略Yammer                            | 工程积压工作 |
| 记录管理                     | 删除记录标签的能力                           | 开发中              |
| 记录管理                     | 手动应用记录标签                            | 可用              |
| 记录管理                     | 将默认记录标签应用于SharePoint、OneDrive for Business库、文件夹和文档集;和 Office 365 组                              | 可用              |
| 记录管理                     | 根据特定条件自动应用记录策略 (例如，关键字或敏感信息) ;和 基于事件                            | 可用              |
| 记录管理                     | 使用可训练分类器自动应用记录策略  | 开发中              |
| 记录管理                     | 处置评审  | 可用              |
| 记录管理                     | 文件计划管理器    | 可用 |
| 记录管理                     | 多阶段处置评审    | 工程积压工作 |
| 记录管理                     | Outlook记录管理的客户端支持    | 工程积压工作 |
| 记录管理                     | Power Automate Flow保留期结束时的保留时间    | 工程积压工作 |
| 记录管理                     | 云附件的保留和自动标记    | 工程积压工作 |
| 记录管理                     | 处置证明                            | 可用 |
| 记录管理                     | 记录版本控制                            | 可用 |
| 记录管理                     | 法规记录                         | 可用 |
| 记录管理                     | 使用SharePoint Syntex分类应用记录标签 | 工程积压工作 |
| **内部风险管理**             | 客户密码箱                                | 可用            |
| 通信合规性                | 忽略电子邮件签名或免责声明的能力                         | 开发中 |
| 通信合规性                | 为通信合规性策略设置保留期的能力                         | 开发中 |
| 通信合规性                | 访问警报;通知模板;通信策略仪表板                         | 可用 |
| 通信合规性                | 分析Teams邮箱的用户的聊天数据                         | 可用 |
| 通信合规性                | 自动监视Teams用户是成员的所有信息                         | 可用 |
| 通信合规性                | 冲突模板                         | 可用 |
| 通信合规性                | 创建客户策略，3 个预配置                         | 可用 |
| 通信合规性                | 检测成人内容                         | 可用 |
| 通信合规性                | 检测一段时间的重复行为违反代码                         | 可用 |
| 通信合规性                | 升级以进行调查Advanced eDiscovery                         | 可用 |
| 通信合规性                | 内部风险管理下手                         | 工程积压工作 |
| 通信合规性                | 利用光学字符识别提取和评估消息                         | 开发中 |
| 通信合规性                | 针对非常小型企业的新简化视图                         | 开发中 |
| 通信合规性                | 策略运行状况检查和暂停策略的能力                         | 开发中 |
| 通信合规性                | Power Automate 集成                         | 开发中 |
| 通信合规性                | 支持更精细的权限                         | 可用 |
| 通信合规性                | 支持针对威胁的七种语言，目标攻击和亵亵分类器                         | 开发中 |
| 通信合规性                | Microsoft Teams集成                         | 工程积压工作 |
| 通信合规性                | Teams对话上下文                         | 开发中 |
| 通信合规性                | 调查期间翻译内容                         | 工程积压工作 |
| 客户密码箱                | 客户密码箱                         | 可用 |
| 信息屏障                | 信息屏障                         | 可用 |
| 内部风险管理             | 案例仪表板                         | 可用 |
| 内部风险管理             | 离职用户窃取数据                        | 可用 |
| 内部风险管理             | 内部版本 1809 Windows 10上活动的设备指示器                        | 工程积压工作 |
| 内部风险管理             | 升级以进行调查Advanced eDiscovery                        | 可用 |
| 内部风险管理             | 导出警报                        | 工程积压工作 |
| 内部风险管理             | 常规数据泄露                                | 可用              |
| 内部风险管理             | 安全策略违反指示器                   | 工程积压工作              |
| 内部风险管理             | 适用于终结点警报的 Microsoft Defender 指示器      | 工程积压工作              |
| 内部风险管理             | 内部风险管理活动资源管理器      | 开发中              |
| 内部风险管理             | 内部风险管理内容资源管理器      | 开发中              |
| 内部风险管理             | 调查内部风险管理警报      | 可用              |
| 内部风险管理             | 通知模板      | 可用              |
| 内部风险管理             | Office、Teams网站SharePoint电子邮件的指示器      | 可用              |
| 内部风险管理             | 策略自定义      | 工程积压工作              |
| 内部风险管理             | 解除限制的用户泄露数据的策略模板      | 工程积压工作              |
| 内部风险管理             | 按优先级用户泄露数据的策略模板 | 工程积压工作 |
| 内部风险管理             | 用于常规安全策略违反的策略模板 | 工程积压工作 |
| 内部风险管理             | 针对优先级用户、离职用户和解除限制用户违反安全策略的策略模板 | 工程积压工作 |
| 内部风险管理             | 优先级用户组 | 工程积压工作 |
| 内部风险管理             | Power Automate 集成 | 开发中 |
| 内部风险管理             | Microsoft Teams集成 | 工程积压工作 |
| Privileged Access Management        | 特权访问管理 | 工程积压工作 |
| **发现&响应**                  | 核心电子数据展示：审核                            | 可用              |
| 电子数据展示                              | 核心电子数据展示：案例管理                                 | 可用              |
| 电子数据展示                              | 核心电子数据展示：导出                                          | 可用              |
| 电子数据展示                              | 核心电子数据展示：就地保留                           | 可用              |
| 电子数据展示                              | 核心电子数据展示：本机导出                                  | 可用              |
| 电子数据展示                              | 核心电子数据展示：RMS 解密                                   | 可用              |
| 电子数据展示                              | 核心电子数据展示：搜索                                   | 可用              |
| 电子数据展示                              | 核心电子数据展示：Microsoft 合规性中心扩展了对搜索和导出回收站中SharePoint OneDrive for Business的支持                                        | 可用              |
| 电子数据展示                              | Advanced eDiscovery：高级处理                             | 可用 |
| 电子数据展示                              | Advanced eDiscovery：工作负荷映射                             | 可用 |
| 电子数据展示                              | Advanced eDiscovery：保管人通信                             | 可用 |
| 电子数据展示                              | Advanced eDiscovery：仪表板                                 | 可用 |
| 电子数据展示                              | Advanced eDiscovery：双字节字符支持 (中文、日语、朝鲜语)                                  | 可用 |
| 电子数据展示                              | Advanced eDiscovery：电子邮件线程                   | 可用 |
| 电子数据展示                              | Advanced eDiscovery：导出 (下载、导出、添加到其他视图集)                                           | 可用 |
| 电子数据展示                              | Advanced eDiscovery：筛选                               | 可用 |
| 电子数据展示                              | Advanced eDiscovery：保留优化                      | 开发中 |
| 电子数据展示                              | Advanced eDiscovery：合法保留Teams私人频道消息            | 可用 |
| 电子数据展示                              | Advanced eDiscovery：Microsoft 合规性中心扩展了对在回收站和回收站中搜索SharePoint OneDrive for Business项的支持            | 开发中 |
| 电子数据展示                              | Advanced eDiscovery：近重复标识                               | 可用 |
| 电子数据展示                              | Advanced eDiscovery：新的预测编码模块                   | 工程积压工作 |
| 电子数据展示                              | Advanced eDiscovery：非资源数据源                                  | 可用 |
| 电子数据展示                              | Advanced eDiscovery：非Office 365的                                    | 可用 |
| 电子数据展示                              | Advanced eDiscovery：预测编码                                       | 可用 |
| 电子数据展示                              | Advanced eDiscovery：使用加载文件处理导出                   | 可用 |
| 电子数据展示                              | Advanced eDiscovery：Redactions                        | 可用 |
| 电子数据展示                              | Advanced eDiscovery：审阅集                                     | 可用 |
| 电子数据展示                              | Advanced eDiscovery：查看数据 (查询数据、智能标记、仪表板) 并注释 (修订)                              | 可用 |
| 电子数据展示                              | Advanced eDiscovery：搜索词报告                        | 可用 |
| 电子数据展示                              | Advanced eDiscovery：单个项目错误修正                              | 可用 |
| 电子数据展示                              | Advanced eDiscovery：支持 PST 导出                              | 可用 |
| 电子数据展示                              | Advanced eDiscovery：支持来自 OneDrive 和 SharePoint Online (新式附件)                               | 可用 |
| 电子数据展示                              | Advanced eDiscovery：支持Teams反应                      | 工程积压工作 |
| 电子数据展示                              | Advanced eDiscovery：标记                              | 可用 |
| 电子数据展示                              | Advanced eDiscovery：租户报告                              | 可用 |
| 电子数据展示                              | Advanced eDiscovery：主题                              | 可用 |
| 电子数据展示                              | Advanced eDiscovery：查看者                              | 可用 |
| 电子数据展示                              | Advanced eDiscovery：Yammer Advanced eDiscovery Microsoft 合规中心内                              | 可用 |
| Audit                                   | 基本审核                              | 可用 |
| Audit                                   | 高级审核：访问关键事件 (例如 *MailItemsAccessed*)                               | 可用 |
| Audit                                   | 高级审核：增加管理活动 API 的带宽                   | 可用 |
| Audit                                   | 高级审核：合法保留Teams私人频道消息                   | 可用 |
| Audit                                   | 高级审核：记录保留期 (1 年)                                | 可用 |
| Audit                                   | 高级审核：审核日志的更长期保留期 (10 年)               | 开发中 |
| Audit                                   | 高级审核：邮件转发和邮件发送事件                               | 可用 |
| Audit                                   | 高级审核：Microsoft 365安全与合规中心                    | 可用 |
| Audit                                   | 高级审核：Exchange Online和 SharePoint Online 中的搜索词事件                              | 工程积压工作 |
|    **遵从性管理**            | Microsoft 365安全与合规中心                              | 可用 |
|                                         | 合规性管理器                              | 可用 |
|                                         | 双字节字符支持                              | 可用 |
|                                         | Microsoft Cloud App Security                              | 工程积压工作 |
|    **生态系统**            | Graph适用于 Advanced eDiscovery                              | 开发中 |
|                                         | Graph用于导出Teams API                              | 工程积压工作 |
|                                         | 第一方数据连接器                              | 工程积压工作 |
|                                         | 第三方数据连接器                              | 开发中 |




<sup>1</sup> 在重新评估项目计划和优先级时，标识的状态可能会更改。<br/>

**决策点***：确定合规性功能是否满足组织的需求。*
