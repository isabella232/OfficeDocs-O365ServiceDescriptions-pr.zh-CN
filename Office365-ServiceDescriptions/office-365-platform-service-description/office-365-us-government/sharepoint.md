---
title: 适用于美国政府环境的 SharePoint
ms.author: mkashman
author: kaarins
manager: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 了解有关美国政府云客户的 SharePoint 功能可用性。
ms.openlocfilehash: c360bc7ebda3c1a4041e0dcd8c2d5cb9699b8820
ms.sourcegitcommit: 6b7918dd0f125b49d81b11672617c95ebd676b01
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 02/20/2020
ms.locfileid: "42174990"
---
# <a name="sharepoint-for-us-government-environments"></a>适用于美国政府环境的 SharePoint

本文概述了美国政府云和商业云之间的功能差异，如[SharePoint 服务说明](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-service-description)中所示。 SharePoint 适用于政府社区云（GCC）、GCC （GCC）和 DoD 环境。 

有关政府云（包括资格和购买）的详细信息，请参阅[Microsoft 365 政府-如何购买](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy)。 若要比较 Office 365 政府版计划，请参阅[office 365 政府版计划](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)。

若要了解管理网络连接时所需的终结点，请参阅[office 365 美国政府版高终结点](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business)或[Office 365 美国政府 DoD 终结点](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)。

除了享受 Office 365 的特性和功能外，组织还可受益于美国政府云环境所特有的以下功能：

-   您的组织的客户内容在 Microsoft 的商业版 Office 365 服务中从逻辑上隔离。
-   您组织的客户内容存储在美国境内。
-   对组织的客户内容的访问权限只限于屏蔽的 Microsoft 员工。
-   政府云环境符合美国公共事业部门客户所需的认证和资格鉴定。

我们的目标是将所有 SharePoint 商业版特性和功能传递给政府云环境。 有些功能因政府云客户的要求而不可用。 其他功能将进入政府环境，但尚不可用。 请参阅以下各节，了解政府云环境中的功能可用性。

## <a name="developer-features"></a>开发人员功能

商业客户的开发人员功能与政府云客户的开发人员功能没有任何已知差异。

- 与外部应用程序（如外接程序的数据源）的连接仅限于位于政府环境支持的系统安全边界内的源。
- Business Connectivity Services （BCS）功能受支持的连接方案，其中数据源在云服务的安全边界内仍可访问。

如果您在网站上使用第三方应用程序，请查看第三方在评估您的组织的这些服务的适当使用时提供的隐私和合规性声明。 第三方应用程序和服务可能涉及在政府云外部的第三方系统上存储、传输和处理您的组织的客户数据，因此不受其合规性和数据保护的覆盖承诺. 

## <a name="it-admin-features"></a>IT 管理员功能

以下是商业客户和政府云客户的 IT 管理员功能之间的区别。

- 更改网站地址对 GCC 高级客户不可用
- 混合 SharePoint Server 对所有政府云客户不可用
- SharePoint 迁移工具和迁移管理器需要配置更改。 有关信息，请参阅[SPMT 政府云支持](/sharepointmigration/spmt-install-issues#government-cloud-support)。
- 尚不支持 Mover.io
- 多地理位置不适用于所有政府云客户

有关 FastTrack 迁移的信息，请参阅[Office 365 US 政府服务说明](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#data-migrations-performed-by-fasttrack)。

## <a name="security-and-compliance-features"></a>安全性和合规性功能

商业客户和政府云客户的安全与合规功能之间没有已知的区别。

有关以下功能的信息，请参阅[Office 365 US 政府服务说明](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features)：
- 客户密码箱
- 数据丢失防护 (DLP)
- 电子数据展示（内容搜索、保留、导出）
- Office 365 高级威胁防护（ATP）
- 敏感度标签

有关适用于政府的 Azure Active Directory 功能的信息，请参阅[Azure 政府安全性 + 标识文档](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory)。 

有关适用于政府的 Azure 信息保护功能的信息，请参阅[Azure 信息保护 Premium 政府服务说明](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description) 

## <a name="sites-and-content"></a>网站和内容

以下是商业客户的网站和内容功能与政府云客户的网站和内容功能之间的区别：

- 依赖于 Internet 服务连接的 Web 部件（如 Amazon Kindle、Bing 地图、Twitter 和 YouTube web 部件）将无法按预期工作
- 组织资产库不可用
- 将列表和页面添加到团队不适用于 GCC 高级和 DoD 客户

## <a name="search-features"></a>搜索功能

以下是商业客户的搜索功能与政府云客户的搜索功能之间的区别：

- Microsoft Search 集成不可用。

## <a name="sharing-and-sync"></a>共享和同步

有关商业云和政府云环境之间的功能差异，请参阅[文件共享](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/gcc-high-and-dod#file-sharing)。

## <a name="plan-for-governance"></a>规划管理

您的迁移到云可提供内置管理控件的 transformative 体验。 确定您的治理要求以及如何满足这些要求。 若要详细了解详细信息，请转到[计划进行管理以将团队转换为 Microsoft 365](https://resources.techcommunity.microsoft.com/teamwork-governance/) 。 你将找到有关 Office 365 组、SharePoint、团队等方面的指导。

## <a name="deploy-sharepoint-for-collaboration"></a>部署 SharePoint 以进行协作

在 Microsoft 美国政府版中设置组织后，请按照[SharePoint 采用资源中心](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/)中概述的建议部署路径操作。 确保与您的采用和变更管理拥护者接洽。
你还可以与[FastTrack](https://www.microsoft.com/fasttrack)或你选择的合作伙伴合作，向你的用户推出该服务。
请访问[Microsoft 信任中心](https://www.microsoft.com/en-us/trust-center)，以详细了解 microsoft 如何为我们的客户提供服务的安全、隐私和合规性、核心原则。
