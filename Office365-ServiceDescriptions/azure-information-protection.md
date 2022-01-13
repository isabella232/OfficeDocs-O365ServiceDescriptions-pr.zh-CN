---
title: Azure 信息保护服务说明
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: Microsoft Azure AIP (AIP) 可帮助组织发现、分类、标记和保护敏感文档和电子邮件。
ms.openlocfilehash: b5c5848b6cb7fc44dd744c5aed0a320c0809aa60
ms.sourcegitcommit: 7b178adab989723e535f18fb8509e2c9eb9ea607
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 01/13/2022
ms.locfileid: "62028758"
---
# <a name="azure-information-protection-service-description"></a>Azure 信息保护服务说明

Microsoft Azure AIP (AIP) 可帮助组织发现、分类、标记和保护敏感文档和电子邮件。 管理员可以定义规则和条件以自动应用标签、用户可以手动应用标签或结合使用这两者，其中会为用户提供有关应用标签的建议。 用户还可以从以下功能中获益：能够手动将敏感度标签应用于其内容，或自动对内容进行分类。 有关详细信息，请参阅什么是 [Azure 信息保护？](/azure/information-protection/what-is-information-protection)

## <a name="available-plans"></a>可用计划

Microsoft Azure信息保护可以单独购买，也可通过以下 Microsoft 许可套件之一进行购买：Microsoft 365 企业版 计划、Microsoft 365 合规性计划 (包括 Azure 信息保护 P2) 、Microsoft 365 商业 (包括 Azure 信息保护 P1) 、企业移动性 + 安全性计划。 以下 Azure 信息保护计划作为用户订阅许可证提供：计划 1 (M365 A3、企业移动性 + 安全性 A3 和 M365 商业高级版) 以及适用于 O365 (A3/A5) 的计划 2 (M365 A5、企业移动性 + 安全性 A5) 和 AIP。 有关使用户能够使用 Azure 信息保护的订阅的详细计划信息，请参阅[M365](https://aka.ms/M365BusinessPlans)商业版计划比较[、M365 Enterprise 计划比较和](https://aka.ms/M365EnterprisePlans) [M365 教育](https://aka.ms/EDU-Plan-Comparison)版计划比较页面。

## <a name="feature-availability"></a>功能可用性

下表列出了跨计划提供的 Azure 信息保护功能 (一些注意事项适用 -- 请参阅脚注，了解详细信息) 。 表格可能会更改，无需另行通知。 转到完整 [订阅比较表](https://go.microsoft.com/fwlink/?linkid=2139145)  ，了解跨计划 Azure 信息保护功能的主要列表。

| 功能 | Azure 信息保护Office 365 | Azure 信息保护高级版 P1 | Azure 信息保护高级版 P2 |
|---------|---------|---------|---------|
| Azure 信息保护内容使用 AIP 策略感知应用和服务中的工作或学校帐户 | 是 | 是 | 是 |
| 将你自己的密钥 (BYOK) 客户管理的密钥预配生命周期<sup>2</sup>     | 是 | 是 | 是 |
| 自定义模板，包括部门模板 | 是 | 是 | 是 |
| 通过权限管理连接器Exchange本地SharePoint和内容保护 | 是 | 是 | 是 |
| 使用工作或学校帐户创建 Azure 信息保护内容 | 是 | 是 | 是 |
| 与 Office 365 邮件加密 | 是 | 是 | 是 |
| 管理控制<sup>3</sup> | 是 | 是 | 是 |
| 保护非Microsoft Office文件格式，包括 PTXT、PJPG 和 PFILE (通用)  | 否 | 是 | 是 |
| 手动、默认和强制文档分类 | 否 | 是 | 是 |
| Azure 信息保护扫描程序，用于发现匹配任何敏感信息类型的本地文件的内容 | 否 | 是 | 是 |
| Azure 信息保护扫描程序，用于将标签应用于本地文件服务器或存储库中的所有文件 | 否 | 是 | 是 |
| 文档跟踪和吊销 | 否 | 是 | 是 |
| Microsoft 信息保护 sdk (sdk) 的软件开发工具包，可针对所有平台（Windows、iOS、Mac OSX、Android 和 Linux）的电子邮件和文件应用标签和保护 | 否 | 是 | 是 |
| 配置自动分类和推荐分类的条件 | 否 | 否 | 是 |
| 将标签设置为自动应用预配置的 S/MIME 保护Outlook | 否 | 否 | 是 |
| 使用警告、调整或阻止电子邮件Outlook (控制信息共享)  | 否 | 否 | 是 |
| 为高度管控 (Azure 信息) 和 Active Directory (AD) 权限管理的 HYOK 项目保留自己的密钥 | 否 | 否 | 是 |
| 双密钥加密(DKE) | 否 | 否 | 是 |
| Azure 信息保护扫描程序，用于自动分类、标记和保护受支持的本地文件 | 否 | 否 | 是 |

> <sup>1</sup>某些Office 365订阅还包括使用信息保护Microsoft Azure数据保护。 有关这些Office 365及其包含的数据保护功能的信息，请参阅 [Azure 信息保护许可数据表](https://download.microsoft.com/download/E/C/F/ECF42E71-4EC0-48FF-AA00-577AC14D5B5C/Azure_Information_Protection_licensing_datasheet_EN-US.pdf)。
<br/><sup>2</sup> Azure 订阅，使用配置密钥将你自己的密钥 (BYOK) 。
<br/><sup>3</sup> 包括激活/停用服务、分阶段部署的载入控件、使用率日志记录、电子数据展示和数据恢复的超级用户功能、批量保护/解除文件保护。

## <a name="free"></a>空闲

免费计划的唯一可用功能是 Azure 信息保护内容使用，通过使用 AIP 策略感知应用和服务中的工作或学校帐户。 组织中已发送受 Azure 信息保护保护但无法进行身份验证的敏感文件的用户的自助服务订阅，因为用户的 IT 部门没有在 Azure 中管理其帐户，例如，IT 部门没有 Office 365 或使用 Azure 服务。

## <a name="learn-more"></a>了解详细信息

### <a name="azure-information-protection-details"></a>Azure 信息保护详细信息

- **Azure RMS：Azure** RMS ([Azure RMS](/azure/information-protection/what-is-azure-rms)) Azure 信息保护提供数据保护技术。 Azure RMS 可以与分类和标记一同使用，也可以自行使用。
- **AIP 扫描程序或客户端**：你必须拥有 Azure 信息保护计划，用于使用 Azure 信息保护扫描程序或客户端进行分类、标记和保护。 有关详细信息，[请参阅：Microsoft 365](/office365/servicedescriptions/microsoft-365-service-descriptions/microsoft-365-tenantlevel-services-licensing-guidance/microsoft-365-security-compliance-licensing-guidance#information-protection)安全&许可指南、新式工作计划比较[ (](https://go.microsoft.com/fwlink/?linkid=2139145) PDF 下载) 、Azure Active Directory[定价|Microsoft 安全](https://www.microsoft.com/security/business/identity-access-management/azure-ad-pricing)。
- [**计算器**](https://azure.microsoft.com/pricing/calculator/?service=information-protection)：估计 Azure 服务的每月成本。
- [**文档**](/azure/information-protection/)：查看技术教程、视频和更多资源。
- **Azure 信息保护** 不包括基于可训练分类器机器学习 (自动分类) 。
- **双密钥加密**：有关双密钥加密 for Microsoft 365，请转到信息保护：双密钥加密 [for Microsoft 365。](/office365/servicedescriptions/microsoft-365-service-descriptions/microsoft-365-tenantlevel-services-licensing-guidance/microsoft-365-security-compliance-licensing-guidance#information-protection-double-key-encryption-for-microsoft-365)
- **Power BI** 包含在 Microsoft 365 E5/A5/G5 中;在所有其他计划中，Power BI单独许可。
- [**产品详细信息**](https://azure.microsoft.com/services/information-protection/)：了解有关 Azure 信息保护的详细信息。
- [**购买常见问题**](https://azure.microsoft.com/pricing/faq/)解答：查看 Azure 定价常见问题解答。
- **范围**：除了使用 AIP 扫描程序功能时，可以将策略的范围划分到特定组或用户，并可以编辑注册表以防止未经授权的用户运行分类或标记功能。
- **敏感度标签**：有关详细信息，请转到信息保护：敏感度 [标签](/office365/servicedescriptions/microsoft-365-service-descriptions/microsoft-365-tenantlevel-services-licensing-guidance/microsoft-365-security-compliance-licensing-guidance#information-protection-sensitivity-labeling) 或检查新式 [工作计划比较](https://go.microsoft.com/fwlink/?linkid=2139145)。
- **订阅** 计划：要详细了解如何购买或评估 Azure 信息保护，以及可用于订阅计划的不同功能，请参阅 [Azure 信息保护](https://www.microsoft.com/cloud-platform/azure-information-protection)   网站。

### <a name="general-information"></a>一般信息

- **辅助功能**：Microsoft 始终致力于确保数据的安全性 [以及服务的](https://www.microsoft.com/trust-center/compliance/accessibility)   辅助功能。 有关详细信息，请参阅 Microsoft 信任 [中心和](https://www.microsoft.com/trust-center)   Office [中心](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)。
- **For questions**： If your question is not answered here， review the [Frequently asked questions for Azure Information Protection (AIP)](/azure/information-protection/faqs) which are specific to classification and labeling， or specific to data protection ([FAQs for classification and labeling](/azure/information-protection/faqs-infoprotect)， [FAQs for data protection ， FAQs](/azure/information-protection/faqs-rms) [for the classic client only](/azure/information-protection/faqs-classic)) or see the links and resources listed in Information and support for Azure Information  [Protection](/azure/information-protection/information-support) 或联系你的 Microsoft 客户经理或 [Microsoft 支持部门](/azure/information-protection/information-support#to-contact-microsoft-support)。
- **许可条款**：有关通过 Microsoft 商业批量许可计划购买的产品和服务的许可条款和条件，请参阅产品 [条款网站](https://www.microsoft.com/licensing/terms/)。
- **消息：** 若要随时了解即将进行的更改，包括新功能和已更改的功能、计划的维护或其他重要通知，请访问消息中心。 有关详细信息，请参阅[消息中心](/microsoft-365/admin/manage/message-center)。
- **支持& SLA：** 如果有任何疑问或需要帮助，请访问  [Azure](https://azure.microsoft.com/support/options)支持并选择自助服务或其他任何方法   联系我们获取支持。 我们保证最终用户能够在 99.9% 的时间创建和使用 IRM 文档和电子邮件。 若要了解更多信息，请访问 [SLA](/learn/modules/choose-azure-services-sla-lifecycle)   页面。 有关"独立云"中的支持和 SLA，请联系你的本地帐户。
