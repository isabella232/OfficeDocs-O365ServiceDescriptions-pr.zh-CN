---
title: 规划 Microsoft 365 合规性-GCC
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 本指南适用于在美国联邦、州、本地、部落或 territorial 政府实体或其他处理受政府法规和要求（在其中使用 Microsoft）的数据的公司中部署 Office 365 的 IT 专业人员。365政府版-GCC 适用于满足这些要求。
ms.openlocfilehash: ed9625972b6a12c17527fadf35413806fedd4015
ms.sourcegitcommit: 7ceeebe425223c2cc8d6bd26a4a79b1e1d329b6f
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/14/2019
ms.locfileid: "38319490"
---
# <a name="plan-for-microsoft-365-compliance--gcc"></a>规划 Microsoft 365 合规性– GCC

本指南适用于在美国联邦、州、本地、部落或 territorial 政府实体或其他处理受政府法规和要求（在其中使用 Microsoft）的数据的公司中部署 Office 365 的 IT 专业人员。365政府版-GCC 适用于满足这些要求。

> [!NOTE]
> 如果您的组织已满足 Microsoft 365 政府-GCC 的资格要求，并已应用并接受到程序，则可以跳过步骤1和步骤2，直接转到步骤3。

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---gcc-and-meets-eligibility-requirements"></a>第 1 步： 确定您的组织是否需要 Microsoft 365 政府-GCC 并满足资格要求

Microsoft 365 政府版的环境符合美国政府对云服务的要求，包括 FedRAMP 中型和刑事审判和联邦税务信息系统的要求（CJI 和 FTI data types）。

除了享受 Office 365 的特性和功能外，组织还可以受益于 Microsoft 365 政府-GCC 所特有的以下功能：

- 您的组织的客户内容在 Microsoft 的商业版 Office 365 服务中从逻辑上隔离。

- 您组织的客户内容存储在美国境内。

- 对组织的客户内容的访问权限只限于屏蔽的 Microsoft 员工。

- Microsoft 365 政府版-GCC 遵守美国公共事业部门客户所需的认证和资格鉴定。

您可以在[Office 365 政府版计划](https://products.office.com/government/compare-office-365-government-plans)中找到有关适用于美国政府客户的 Microsoft 365 政府-GCC 产品的详细信息，包括资格要求。

[Office 365 美国政府版服务说明](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government)介绍了平台的优势，这些优点在美国的符合合规性要求中居中显示。

> [!TIP]
> 您可能需要将服务说明中的信息表转移到 Excel 工作簿中，并添加两列： **与我的组织的相关信息 y/n** 相关并 **满足我的组织的需要 y/n**。 然后，您可以与同事一起查看此列表，以确认此服务是否满足组织的需求。

> [!NOTE]
> Microsoft 365 政府版-GCC 仅适用于美国。 非美国政府客户可以从多个[Office 365 政府计划](https://products.office.com/government/compare-office-365-government-plans)中进行选择。

**决策点**： <br/>
- *确定 Microsoft 365 政府版（GCC）是否适合您的组织。*
- *确认您的组织满足资格要求。*

## <a name="step-2-apply-for-microsoft-365-government---gcc"></a>第 2 步： 适用于 Microsoft 365 政府版-GCC

如果认为此服务适合您的组织，请启动[应用此服务](https://products.office.com/government/eligibility-validation)的过程。

## <a name="step-3-understand-microsoft-365-government---gcc-default-security-settings"></a>第 3 步： 了解 Microsoft 365 政府版-GCC 默认安全设置

我们建议您在修改管理员和安全设置之前，先仔细检查管理员和安全设置，并考虑对合规性产生的影响，然后再对默认安全设置进行任何更改。

**决策点**：*决定是否要修改任何默认的 Microsoft 365 政府-GCC 安全设置，先解决以了解您可能进行的任何更改的影响。*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gccsup1sup"></a>第 4 步： 了解默认情况下在 Microsoft 365 政府中当前不可用或禁用的功能（GCC<sup>1</sup> ）

为了满足政府云客户的要求，Microsoft 365 政府-GCC 和企业版计划存在一些差异。 请参阅下表以查看哪些功能可用。

|                                         | **功能**                                     | **GCC 状态**         |
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
| **内幕风险管理**             | 高级邮件加密                     | 可用              |
|                                         | 沟通合规性                        | 在工程工作积压 |
|                                         | 客户密码箱                                | 可用              |
|                                         | 客户密钥                                    | 可用              |
|                                         | 特权访问管理                    | 在工程工作积压 |
| **发现 & 响应**                  | 就地保留                            | 可用              |
|                                         | 案例管理                                 | 可用              |
|                                         | 搜索                                          | 可用              |
|                                         | 导出                                          | 可用              |
|                                         | RMS 解密                                  | 可用              |
|                                         | 本机导出                                   | 可用              |
|                                         | 审核                                        | 可用              |
|                                         | 高级处理                             | 在工程工作积压 |
|                                         | 电子邮件会话                                 | 在工程工作积压 |
|                                         | 临近重复标识                   | 在工程工作积压 |
|                                         | 主题                                          | 在工程工作积压 |
|                                         | 预测编码                               | 在工程工作积压 |
|                                         | 已使用加载文件处理导出                 | 在工程工作积压 |
|                                         | 带                                         | 在工程工作积压 |
|                                         | 查看者                                         | 在工程工作积压 |
|                                         | 密文                                      | 在工程工作积压 |
|                                         | 筛选                                       | 在工程工作积压 |
|                                         | 保管人到工作负载映射                   | 在工程工作积压 |
|                                         | 保管人通信                        | 在工程工作积压 |
|                                         | 评审集                                     | 在工程工作积压 |
|                                         | 审阅和批注                             | 在工程工作积压 |
|                                         | 非 Office 365 摄取                        | 在工程工作积压 |
|                                         | 搜索词报告                              | 在工程工作积压 |

<sup>1</sup>标识的状态可能会随着项目计划和优先级的重新评估而发生更改。<br/>
<sup>2</sup>手动应用标签需要[Azure 信息保护（AIP）客户端版本 1](https://docs.microsoft.com/azure/information-protection/rms-client/client-version-release-history)。


**决策点**：*决定合规性功能是否满足组织的需求。*
