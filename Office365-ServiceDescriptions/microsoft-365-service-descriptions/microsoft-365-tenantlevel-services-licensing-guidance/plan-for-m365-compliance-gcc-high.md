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
ms.openlocfilehash: f81f2382f41d2ba1aa6fcd5dabc593b20eba7bc1
ms.sourcegitcommit: d4025c73f14b663ffcaa1ef8db4174b51debdae7
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/23/2020
ms.locfileid: "45388068"
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

您可以在[Office 365 政府版计划](https://products.office.com/government/compare-office-365-government-plans)（包括资格要求）中找到有关 Microsoft 365 政府– GCC 高级版的详细信息。

[Office 365 美国政府版服务说明](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government)介绍了平台的优势，这些优点在美国的符合合规性要求中居中显示。

> [!TIP]
> 您可能需要将服务说明中的信息表转移到 Excel 工作簿中，并添加两列： **与我的组织的相关信息 y/n 相关**   并 **满足我的组织的需要 y/n**。 然后，您可以与同事一起查看此列表，以确认此服务是否满足组织的需求。

**决策点**：<br/>
- *确定 Microsoft 365 政府–高级版是否适合您的组织。*
- *确认您的组织满足资格要求。*

> [!NOTE]
> Microsoft 365 政府版-GCC 高版仅适用于美国国家/地区。 非美国政府客户可以从多个[Office 365 政府计划](https://products.office.com/government/compare-office-365-government-plans)中进行选择。

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>步骤 2. 适用于 Microsoft 365 政府– GCC-高

如果认为此服务适合您的组织，请启动[应用此服务](https://products.office.com/government/eligibility-validation)的过程。
 
## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>步骤 3. 了解 Microsoft 365 政府– GCC-高默认安全设置

我们建议您在修改管理员和安全设置之前，先仔细检查管理员和安全设置，并考虑对合规性产生的影响，然后再对默认安全设置进行任何更改。

**决策点**：*决定是否要修改任何默认的 Microsoft 365 政府– GCC-高安全设置，先解决，以了解您可能进行的任何更改的影响。*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-highsup1sup"></a>步骤 4. 了解默认情况下在 Microsoft 365 政府中目前不可用或禁用的功能。 GCC-高<sup>1</sup>

为满足我们政府云客户的要求，Microsoft 365 政府– GCC-高和企业版计划之间存在一些差异。 请参阅下表以查看哪些功能可用。

|                                         | 功能                                         | GCC 高状态        |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **信息保护 & 治理** | 存档                                       | 可用              |
|                                         | 手动标签和策略<sup>2</sup>          | 可用              |
|                                         | 标签的自动应用                      | 在工程工作积压 |
|                                         | 基于敏感数据类型的标签            | 在工程工作积压 |
|                                         | 基于查询的标签和关联策略 | 在工程工作积压 |
|                                         | 文件计划                                       | 在工程工作积压 |
|                                         | 推荐的策略                            | 在工程工作积压 |
|                                         | 智能导入筛选器                            | 在工程工作积压 |
|                                         | 基于事件的保留                           | 在工程工作积压 |
|                                         | 处置评审                              | 在工程工作积压 |
|                                         | 信息屏障                            | 可用              |
|                                         | 文件和电子邮件的数据丢失防护（DLP）  | 可用              |
|                                         | 适用于团队聊天和频道对话的 DLP    | 在工程工作积压 |
|                                         | DLP 精确数据匹配                            | 在工程工作积压 |
|                                         | 标签活动资源管理器                         | 在工程工作积压 |
|                                         | Trainable 类元                           | 在工程工作积压 |
|                                         | 统一的标签和敏感度标签         | 在工程工作积压 |
| **内部风险管理**             | 高级邮件加密                     | 可用              |
|                                         | 内部风险管理                         | 在工程工作积压 |
|                                         | 通信合规性                        | 在工程工作积压 |
|                                         | 客户密码箱                                | 可用              |
|                                         | 客户密钥                                    | 可用              |
|                                         | 特权访问管理                    | 在工程工作积压 |
| **发现 & 响应**                  | 核心电子数据展示：就地保留                            | 可用              |
|                                         | 核心电子数据展示：案例管理                                 | 可用              |
|                                         | 核心电子数据展示：搜索                                          | 可用              |
|                                         | 核心电子数据展示：导出                                          | 可用              |
|                                         | 核心电子数据展示： RMS 解密                                  | 可用              |
|                                         | 核心电子数据展示：本地导出                                   | 可用              |
|                                         | 核心电子数据展示：高级处理                             | 可用              |
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
| **遵从性管理**               | 合规性分数                                | 在工程工作积压 |

<sup>1</sup>标识的状态可能会随着项目计划和优先级的重新评估而发生更改。<br/>
<sup>2</sup>手动应用标签需要[Azure 信息保护（AIP）客户端版本 1](https://docs.microsoft.com/azure/information-protection/rms-client/client-version-release-history)。 


**决策点**：*决定合规性功能是否满足组织的需求。*
