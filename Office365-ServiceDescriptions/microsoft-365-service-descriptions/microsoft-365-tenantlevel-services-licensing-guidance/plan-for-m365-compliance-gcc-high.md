---
title: Microsoft 365 合规性计划 - GCC High
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 本指南适用于推动美国联邦政府实体或其他实体（用于处理政府法规和要求的数据）中的 Office 365 部署的 IT 专业人员，其中 Microsoft 365 政府– GCC High 的使用适用于满足这些要求。
ms.openlocfilehash: df0d78d40e91c171b2a512de4b7d8371ceb59995
ms.sourcegitcommit: dcacd13c1cf1c60526c48fc923db5de643facc07
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/20/2020
ms.locfileid: "48626883"
---
# <a name="plan-for-microsoft-365-compliance--gcc-high"></a>规划 Microsoft 365 合规性– GCC High

本指南适用于推动美国联邦政府实体或其他实体（用于处理政府法规和要求的数据）中的 Office 365 部署的 IT 专业人员，其中 Microsoft 365 政府– GCC High 的使用适用于满足这些要求。

> [!NOTE]
>如果您的组织已满足 Microsoft 365 政府– GCC 高资格要求，并已应用并被接受到程序中，则可以跳过步骤1和步骤2，直接转到步骤3。
 
## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government--gcc-high-and-meets-eligibility-requirements"></a>步骤 1. 确定您的组织是否需要 Microsoft 365 政府– GCC 高并满足资格要求

Microsoft 365 政府-GCC 高环境符合美国政府对云服务的要求。 除了享受 Office 365 的特性和功能外，组织还可以受益于 Microsoft 365 政府（GCC 高）所特有的以下功能：

- 您的组织的客户内容在 Microsoft 的商业版 Office 365 服务中从逻辑上隔离。
- 您组织的客户内容存储在美国境内。
- 对组织的客户内容的访问权限只限于屏蔽的 Microsoft 员工。
- Microsoft 365 政府– GCC 高符合美国公共事业部门客户所需的认证和资格鉴定。

您可以在 [Office 365 政府版计划](https://products.office.com/government/compare-office-365-government-plans)（包括资格要求）中找到有关 Microsoft 365 政府– GCC 高级版的详细信息。

[Office 365 美国政府版服务说明](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government)介绍了平台的优势，这些优点在美国的符合合规性要求中居中显示。

> [!TIP]
> 您可能需要将服务说明中的信息表转移到 Excel 工作簿中，并添加两列： **与我的组织的相关信息 y/n 相关**   并 **满足我的组织的需要 y/n**。 然后，您可以与同事一起查看此列表，以确认此服务是否满足组织的需求。

**决策点**：<br/>
- *确定 Microsoft 365 政府– GCC-High 是否适合您的组织。*
- *确认您的组织满足资格要求。*

> [!NOTE]
> Microsoft 365 政府版-GCC 高版仅适用于美国国家/地区。 非美国政府客户可以从多个 [Office 365 政府计划](https://products.office.com/government/compare-office-365-government-plans)中进行选择。

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>步骤 2. 适用于 Microsoft 365 政府– GCC-High

如果认为此服务适合您的组织，请启动 [应用此服务](https://products.office.com/government/eligibility-validation)的过程。
 
## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>步骤 3. 了解 Microsoft 365 政府– GCC-High 默认安全设置

我们建议您在修改管理员和安全设置之前，先仔细检查管理员和安全设置，并考虑对合规性产生的影响，然后再对默认安全设置进行任何更改。

**决策点**： *决定是否要修改任何默认的 Microsoft 365 政府– GCC-High 安全设置，先解决以了解您可能进行的任何更改的影响。*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-highsup1sup"></a>步骤 4. 了解默认情况下在 Microsoft 365 政府中目前不可用或禁用的功能。 GCC-高<sup>1</sup>

为了满足政府云客户的要求，Microsoft 365 GCC-High 政府版和企业版计划之间存在一些差异。 请参阅下表以查看哪些功能可用。


|                                         | 功能                                         | GCC 状态             |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **信息保护**              | 统一标签客户端和扫描程序         | 可用              |
|                                         | 精确数据匹配          | 可用              |
|                                         | Exchange Online、SharePoint Online 和 OneDrive 的自动分类和标记                      | 即将推出              |
|                                         | Office 应用 (Word、Excel、PowerPoint、Outlook) 跨 web、Android、iOS、Windows 和 Mac 的自动分类和标记            | 在开发中 |
|                                         | 使用 Office 365 组的分类驱动策略 |  即将推出              |
|                                         | 移动的自动分类和标签                                       |在工程工作积压              |
|                                         | 工作组的自动分类和标签                            |在工程工作积压 |
|                                         | 数据分类：概述和内容活动资源管理器                            | 在工程工作积压 |
|                                         | 带有自动标记的机器学习分类器                           | 在工程工作积压  |
|                                         | 基本 Office 365 邮件加密 (E3)                             | 可用              |
|                                         | 高级 Office 365 邮件加密 (E5)   | 可用              |
|                                         | Office 365 的客户密钥    | 可用 |
|                                         | 为客户管理的密钥预配生命周期提供你自己的密钥 (BYOK)                             | 可用 |
|                                         | 保留您自己的密钥 (HYOK) ，以跨越 Azure 信息保护和 Active Directory (AD) 对高度管控方案的权限管理 (Preview)                          | 可用 |
|                                         | 双密钥加密                           | 在开发中 |
|                                         | 使用 WXP web apps 对加密文档进行共同创作         | 在工程工作积压 |
|                                         | 文件和电子邮件的数据丢失防护         | 可用 |
|                                         | 工作组聊天和频道对话的数据丢失防护 | 在工程工作积压 |
|                                         | 数据丢失防护终结点 | 在工程工作积压 |
| **信息治理** | 信息治理：电子邮件存档                                       | 可用              |
|                                         | 信息治理：保留锁定          | 可用              |
|                                         | 信息治理：导入 PST                      | 可用              |
|                                         | 信息治理：手动非记录保留标签            | 可用 |
|                                         | 信息治理： SharePoint/OneDrive for Business 库、文件夹和文档集的默认保留标签;Exchange 收件箱;和 Office 365 组 | 可用              |
|                                         | 信息治理：针对整个组织的保留策略;特定位置或用户;根据特定条件自动 (例如，关键字或敏感信息) ;基于事件                                       | 可用              |
|                                         | 信息治理：使用 SharePoint Syntex 分类的保留标签                            | 在工程工作积压 |
|                                         | 信息管理：带有 trainable 分类器的保留策略                            | 在工程工作积压 |
|                                         | 信息治理： Yammer 和团队的保留策略                            | 在工程工作积压 |
|                                         | 记录管理：记录标签的手动分类                           | 可用              |
|                                         | 记录管理： SharePoint、OneDrive for business 库、文件夹和文档集的默认记录标签;和 Office 365 组                              | 可用              |
|                                         | 记录管理：基于特定条件自动记录策略 (例如关键字或敏感信息) ;基于事件                            | 可用              |
|                                         | 记录管理：处置评审  | 可用              |
|                                         | 记录管理：文件计划管理器    | 可用 |
|                                         | 记录管理：处置证明                            | 可用 |
|                                         | 记录管理：记录版本控制                         | 可用 |
|                                         | 记录管理：法规记录                         | 在工程工作积压 |
|                                         | 记录管理：授权实施                           | 在工程工作积压 |
|                                         | 记录管理：多阶段处置评审 | 在工程工作积压 |
|                                         | 记录管理：标签活动资源管理器 | 在工程工作积压 |
|                                         | 记录管理： Trainable 类元 | 在工程工作积压 |
| **内幕风险管理**             | 客户密码箱                                | 可用            |
|                                         | 内幕风险管理：团队、SharePoint 网站、电子邮件消息的 Office 指示器                         | 在开发中 |
|                                         | 内幕风险管理：通过去声用户窃取数据                        | 在开发中 |
|                                         | 内幕风险管理：常规数据泄露                                | 在开发中              |
|                                         | 内幕风险管理：调查内幕风险管理警报                                   | 在开发中              |
|                                         | 内幕风险管理：事例仪表板、内容浏览器和通知模板 | 在开发中 |
|                                         | 内幕风险管理：上报以供调查高级电子数据展示 | 在开发中|
|                                         | 内幕风险管理：按优先级用户 (预览) 的数据泄露的策略模板 | 在工程工作积压 |
|                                         | 内幕风险管理：不满用户 (预览) 的数据泄漏策略模板 | 在工程工作积压 |
|                                         | 内幕风险管理：常规安全策略冲突的策略模板 (预览)  | 在工程工作积压 |
|                                         | 内幕风险管理：安全策略违反的策略模板（按优先级的用户、传出的用户、不满意的用户 (预览）)  | 在工程工作积压 |
|                                         | 内幕风险管理：策略自定义 (预览)  | 在工程工作积压 |
|                                         | 内幕风险管理： (预览中导出警报)  | 在工程工作积压 |
|                                         | 内幕风险管理：优先级用户组 (预览)  | 在工程工作积压 |
|                                         | 包括的通信合规性 (。监察策略) ：创建客户策略，3预配置  | 在开发中 |
|                                         | 包括的通信合规性 (。监察策略) ：对团队、Exchange 和删除团队邮件的支持 | 在开发中 |
|                                         | 包括的通信合规性 (。监督策略) ：访问警报;通知模板;通信策略仪表板 | 在开发中  |
|                                         | 包括的通信合规性 (。监察策略) ：升级以供调查高级电子数据展示 | 在开发中 |
|                                         | 包括的通信合规性 (。监督策略) ：检测成人内容 | 在开发中 |
|                                         | 信息屏障 | 在工程工作积压 |
|                                         | 特权访问管理                    | 在工程工作积压 |
| **发现 & 响应**                  | 核心电子数据展示：就地保留                            | 可用              |
|                                         | 核心电子数据展示：案例管理                                 | 可用              |
|                                         | 核心电子数据展示：搜索                                          | 可用              |
|                                         | 核心电子数据展示：导出                                          | 可用              |
|                                         | 核心电子数据展示： RMS 解密                                  | 可用              |
|                                         | 核心电子数据展示：本地导出                                   | 可用              |
|                                         | 核心电子数据展示：审核                                        | 可用              |
|                                         | 核心电子数据展示： Microsoft 合规性中心扩展了对 SharePoint 和 OneDrive for Business 回收站中的项目的搜索和导出支持                                        | 在开发中              |
|                                         | 高级电子数据展示：高级处理                             | 可用 |
|                                         | 高级电子数据展示：仪表板                             | 可用 |
|                                         | 高级电子数据展示：电子邮件线程                                 | 可用 |
|                                         | 高级电子数据展示：导出 (下载、导出、添加到另一个审阅集)                    | 可用 |
|                                         | 高级电子数据展示：筛选                                          | 可用 |
|                                         | 高级电子数据展示：工作组专用频道消息的合法保留                               | 可用 |
|                                         | 高级电子数据展示：接近重复标识                 | 可用 |
|                                         | 高级电子数据展示：非 custodial 数据源                                         | 可用 |
|                                         | 高级电子数据展示：非 Office 365 摄取                                         | 可用 |
|                                         | 高级电子数据展示：预测编码                                      | 可用 |
|                                         | 高级电子数据展示：已处理加载文件的导出                                       | 可用 |
|                                         | 高级电子数据展示：密文                   | 可用 |
|                                         | 高级电子数据展示：审阅集                        | 可用 |
|                                         | 高级电子数据展示：查看数据 (查询数据、智能标记、仪表板) 并添加批注 (密文)                                      | 可用 |
|                                         | 高级电子数据展示：搜索词报告                             | 可用 |
|                                         | 高级电子数据展示：单个项目错误修正                        | 可用 |
|                                         | 高级电子数据展示：支持 PST 导出                              | 即将推出 |
|                                         | 高级电子数据展示：标记                              | 可用 |
|                                         | 高级电子数据展示：租户报告                              | 可用 |
|                                         | 高级电子数据展示：主题                               | 可用 |
|                                         | 高级电子数据展示：查看者                              | 可用 |
|                                         | Microsoft 合规性中心中的高级电子数据展示： Yammer 高级电子数据展示                              | 可用 |
|                                         | 高级电子数据展示：针对高级电子数据展示的 CJK/双字节支持                              | 在开发中 |
|                                         | 高级电子数据展示：图 Api                              | 在开发中 |
|                                         | 高级电子数据展示：支持团队反应                             | 在开发中 |
|                                         | 高级电子数据展示： Microsoft 合规性中心扩展了对 SharePoint 和 OneDrive for Business 回收站中的项目的搜索和导出支持                               | 在工程工作积压 |
|                                         | 基本审核                              | 可用 |
|                                         | 高级审核：对关键事件的访问 (例如，mailitemsaccessed)                               | 可用 |
|                                         | 高级审核：增加了管理活动 API 的带宽                              | 可用 |
|                                         | 高级审核：工作组专用频道消息的合法保留                              | 可用 |
|                                         | 高级审核：日志保留期 (1 年)                               | 可用 |
|                                         | 高级审核：安全性和合规性中心可用性                              | 可用 |
|                                         | 高级审核：较长的审核日志保留期限                              | 在工程工作积压 |
|                                         | 高级审核：邮件转发和邮件发送事件                              | 在工程工作积压 |
|                                         | 高级审核：已处理审核见解                              | 在工程工作积压 |
|                                         | 高级审核： Exchange Online 和 SharePoint Online 中的搜索词事件                              | 在工程工作积压 |
|    **遵从性管理**            | Microsoft 365 安全与合规中心                              | 可用 |
|                                         | 合规性管理器（预览版）                                 | 在工程工作积压              |
|                                         | Microsoft Cloud App Security                                 | 在工程工作积压              |
|                                         | 双字节字符支持                                 | 在工程工作积压              |

<sup>1</sup> 标识的状态可能会随着项目计划和优先级的重新评估而发生更改。<br/>
<sup>2</sup> 手动应用标签需要 [Azure 信息保护 (AIP) 客户端版本 1](https://docs.microsoft.com/azure/information-protection/rms-client/client-version-release-history)。 


**决策点**： *决定合规性功能是否满足组织的需求。*
