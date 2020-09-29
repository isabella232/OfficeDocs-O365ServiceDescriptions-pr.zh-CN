---
title: Microsoft 365 合规性计划 - GCC
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 本指南适用于365促使美国联邦、州、本地、部落或 territorial 政府实体或其他处理受政府法规和要求的数据的 IT 专业人员，以及使用 Microsoft 365 政府-GCC 来满足这些要求的其他实体。
ms.openlocfilehash: 564c8c55b1659d80ffa18802e623634088740ba5
ms.sourcegitcommit: e342174df76128430dfc8c971716da5c4b2942ac
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/28/2020
ms.locfileid: "48293868"
---
# <a name="plan-for-microsoft-365-compliance--gcc"></a>规划 Microsoft 365 合规性– GCC

本指南适用于365促使美国联邦、州、本地、部落或 territorial 政府实体或其他处理受政府法规和要求的数据的 IT 专业人员，以及使用 Microsoft 365 政府-GCC 来满足这些要求的其他实体。

> [!NOTE]
> 如果您的组织已满足 Microsoft 365 政府-GCC 的资格要求，并已应用并接受到程序，则可以跳过步骤1和步骤2，直接转到步骤3。

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---gcc-and-meets-eligibility-requirements"></a>步骤 1. 确定您的组织是否需要 Microsoft 365 政府-GCC 并满足资格要求

Microsoft 365 政府版的环境符合美国政府对云服务的要求，包括 FedRAMP 中型以及刑事审判和联邦税务信息系统的要求 (CJI 和 FTI data types) 。

除了享受 Office 365 的特性和功能外，组织还可以受益于 Microsoft 365 政府-GCC 所特有的以下功能：

- 您的组织的客户内容在 Microsoft 的商业版 Office 365 服务中从逻辑上隔离。

- 您组织的客户内容存储在美国境内。

- 对组织的客户内容的访问权限只限于屏蔽的 Microsoft 员工。

- Microsoft 365 政府版-GCC 遵守美国公共事业部门客户所需的认证和资格鉴定。

您可以在 [Office 365 政府版计划](https://products.office.com/government/compare-office-365-government-plans)中找到有关适用于美国政府客户的 Microsoft 365 政府-GCC 产品的详细信息，包括资格要求。

[Office 365 美国政府版服务说明](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government)介绍了平台的优势，这些优点在美国的符合合规性要求中居中显示。

> [!TIP]
> 您可能需要将服务说明中的信息表转移到 Excel 工作簿中，并添加两列： **与我的组织的相关信息 y/n 相关**   并 **满足我的组织的需要 y/n**。 然后，您可以与同事一起查看此列表，以确认此服务是否满足组织的需求。

> [!NOTE]
> Microsoft 365 政府版-GCC 仅适用于美国。 非美国政府客户可以从多个 [Office 365 政府计划](https://products.office.com/government/compare-office-365-government-plans)中进行选择。

**决策点**： <br/>
- *确定 Microsoft 365 政府版（GCC）是否适合您的组织。*
- *确认您的组织满足资格要求。*

## <a name="step-2-apply-for-microsoft-365-government---gcc"></a>步骤 2. 适用于 Microsoft 365 政府版-GCC

如果认为此服务适合您的组织，请启动 [应用此服务](https://products.office.com/government/eligibility-validation)的过程。

## <a name="step-3-understand-microsoft-365-government---gcc-default-security-settings"></a>步骤 3. 了解 Microsoft 365 政府版-GCC 默认安全设置

我们建议您在修改管理员和安全设置之前，先仔细检查管理员和安全设置，并考虑对合规性产生的影响，然后再对默认安全设置进行任何更改。

**决策点**： *决定是否要修改任何默认的 Microsoft 365 政府-GCC 安全设置，先解决以了解您可能进行的任何更改的影响。*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gccsup1sup"></a>步骤 4. 了解默认情况下在 Microsoft 365 政府中当前不可用或禁用的功能（GCC<sup>1</sup> ）

为了满足政府云客户的要求，Microsoft 365 政府-GCC 和企业版计划存在一些差异。 请参阅下表以查看哪些功能可用。<br><br>

| 区域 | 功能 | GCC 状态 |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **信息保护**              | 统一的标签和敏感度标签         | 可用              |
|                                         | Sharepoint Online 的容器标签、Office 组          | 即将推出              |
|                                         | 基于敏感数据类型（针对 Excel Online、SharePoint Online、OneDrive for Business）自动标记                      | 即将推出              |
|                                         | 基于 Win32 和 Mac Office 客户端的敏感数据类型的标签            | 在工程工作积压 |
|                                         | 基于 Win 32、Mac 的敏感数据类型自动添加标签 |  在工程工作积压              |
|                                         | 基于团队的敏感数据类型自动添加标签                                       |在工程工作积压              |
|                                         | 基于移动的敏感数据类型自动添加标签                            |在工程工作积压 |
|                                         | 基于查询的标签和关联策略                            | 可用 |
|                                         | 标签活动资源管理器                           | 在工程工作积压  |
|                                         | 可训练的分类器                              | 在工程工作积压              |
|                                         | 基本 Office 365 邮件加密 (E3)                             | 可用              |
|                                         | 高级 Office 365 邮件加密 (E5)   | 可用              |
|                                         | Office 365 的客户密钥    | 可用 |
|                                         | 为客户管理的密钥预配生命周期提供你自己的密钥 (BYOK)                             | 可用 |
|                                         | 保留您自己的密钥 (HYOK) ，以跨越 Azure 信息保护和 Active Directory (AD) 对高度管控方案的权限管理 (Preview)                          | 可用 |
|                                         | 双密钥加密                           | 在工程工作积压 |
|                                         | 文件和电子邮件的数据丢失防护 (DLP)          | 可用 |
|                                         | 适用于团队聊天和频道对话的 DLP         | 即将推出 |
|                                         | DLP 精确数据匹配 | 在工程工作积压 |
|                                         | DLP 终结点 | 在工程工作积压 |
| **信息治理** | 电子邮件存档                                       | 可用              |
|                                         | 保留锁定          | 可用              |
|                                         | 导入 PST                      | 可用              |
|                                         | 手动非记录保留标签            | 可用 |
|                                         | SharePoint/OneDrive for Business 库、文件夹和文档集的默认保留标签;Exchange 收件箱;和 Office 365 组 | 可用              |
|                                         | 对整个组织的保留策略;特定位置或用户;并根据特定条件自动 (例如，关键字或敏感信息)                                        | 可用              |
|                                         | 带有 trainable 分类器的保留策略                            | 在工程工作积压 |
|                                         | Yammer 和团队的保留策略                            | 在工程工作积压 |
|                                         | 手动记录标签                           | 可用              |
|                                         | SharePoint、OneDrive for business 库、文件夹和文档集的默认记录标签。和 Office 365 组                              | 可用              |
|                                         | 根据特定条件自动记录策略 (例如关键字或敏感信息) ;基于事件                            | 可用              |
|                                         | 处置评审  | 可用              |
|                                         | 文件计划管理器    | 可用 |
|                                         | 处置证明                            | 可用 |
|                                         | 法规记录                         | 在工程工作积压 |
|                                         | 记录管理许可实施                           | 在工程工作积压 |
|                                         | 记录管理多阶段处置评审 | 在工程工作积压 |
|                                         | 标签活动资源管理器 | 在工程工作积压 |
|                                         | 可训练的分类器 | 在工程工作积压 |
|                                         | 统一的标签和敏感度标签         | 在工程工作积压 |
| **内部风险管理**             | 客户密码箱                                | 可用            |
|                                         | 用于团队、SharePoint 网站、电子邮件消息的 Office 指示器                         | 即将推出 |
|                                         | 通过去声用户窃取数据                        | 即将推出 |
|                                         | 常规数据泄露                                | 即将推出              |
|                                         | 调查内幕风险管理警报                                   | 即将推出              
|                                         | 内幕风险管理案例仪表板、内容浏览器和通知模板 | 即将推出 |
|                                         | 用于调查高级电子数据展示的升级 | 即将推出|
|                                         | 按优先级用户 (预览的数据泄露)  | 在工程工作积压 |
|                                         | 因不满用户 (预览而进行的数据泄露)  | 在工程工作积压 |
|                                         |  (预览的常规安全策略冲突)  | 在工程工作积压 |
|                                         | 安全策略违反：优先级用户、传出用户、不满意的用户 (预览)  | 在工程工作积压 |
|                                         |  (预览的策略自定义)  | 在工程工作积压 |
|                                         |  (预览中导出警报)  | 在工程工作积压 |
|                                         |  (预览的优先级用户组)  | 在工程工作积压 |
|                                         | 创建客户策略，3预配置为符合通信合规性 (包括。监察策略)   | 即将推出 |
|                                         | 包括的通信合规性 (。监督策略) 对团队、Exchange 和删除团队邮件的支持 | 即将推出 |
|                                         | 包括的通信合规性 (。监督策略) 访问警报;通知模板;通信策略仪表板 | 即将推出  |
|                                         | 包括的通信合规性 (。用于调查高级电子数据展示的监察策略) 升级 | 即将推出 |
|                                         | 包括的通信合规性 (。监督策略) 检测成人内容 | 即将推出 |
|                                         | 信息屏障 | 在工程工作积压 |
|                                         | 特权访问管理                    | 在工程工作积压 |
| **发现 & 响应**                  | 核心电子数据展示：就地保留                            | 可用              |
|                                         | 核心电子数据展示：案例管理                                 | 可用              |
|                                         | 核心电子数据展示：搜索                                          | 可用              |
|                                         | 核心电子数据展示：导出                                          | 可用              |
|                                         | 核心电子数据展示： RMS 解密                                  | 可用              |
|                                         | 核心电子数据展示：本地导出                                   | 可用              |
|                                         | 核心电子数据展示：审核                                        | 可用              |
|                                         | 高级电子数据展示：高级处理                             | 可用 |
|                                         | 高级电子数据展示：电子邮件线程                                 | 可用 |
|                                         | 高级电子数据展示：接近重复标识                   | 可用 |
|                                         | 高级电子数据展示：主题                                          | 可用 |
|                                         | 高级电子数据展示：预测编码                               | 可用 |
|                                         | 高级电子数据展示：已处理加载文件的导出                 | 可用 |
|                                         | 高级电子数据展示：标记                                         | 可用 |
|                                         | 高级电子数据展示：查看者                                         | 可用 |
|                                         | 高级电子数据展示：密文                                      | 可用 |
|                                         | 高级电子数据展示：筛选                                       | 可用 |
|                                         | 高级电子数据展示：保管人到工作负载映射                   | 可用 |
|                                         | 高级电子数据展示：保管人通信                        | 可用 |
|                                         | 高级电子数据展示：审阅集                                     | 可用 |
|                                         | 高级电子数据展示：审阅和批注                             | 可用 |
|                                         | 高级电子数据展示：非 Office 365 摄取                        | 可用 |
|                                         | 高级电子数据展示：搜索词报告                              | 可用 |
|                                         | 基本审核                              | 可用 |
|                                         | 高级审核：对关键事件的访问 (例如 mailitemsaccessed)                               | 即将推出 |
|                                         |  (1 年的高级审核日志保留)                                | 即将推出 |
|                                         | 高级审核增加了管理活动 API 的带宽                              | 即将推出 |
|    **遵从性管理**            | 合规性管理器和分数                              | 在工程工作积压 |




<sup>1</sup> 标识的状态可能会随着项目计划和优先级的重新评估而发生更改。<br/>
<sup>2</sup> 手动应用标签需要 [Azure 信息保护 (AIP) 客户端版本 1](https://docs.microsoft.com/azure/information-protection/rms-client/client-version-release-history)。


**决策点**： *决定合规性功能是否满足组织的需求。*
