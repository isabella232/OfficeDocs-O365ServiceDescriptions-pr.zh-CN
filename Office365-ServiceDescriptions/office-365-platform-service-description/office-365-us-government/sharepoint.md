---
title: 适用于美国政府环境的 SharePoint
ms.author: office365servicedesc
author: pamelaar
ms.reviewer: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 了解美国政府云客户的 SharePoint 功能可用性。
ms.openlocfilehash: 505be0509dbef718e64983377c8dc75a23adfd26
ms.sourcegitcommit: bf25a64ef2b5c1a1c1e5b94babbebf8d2eb7a1a1
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 02/08/2021
ms.locfileid: "50145979"
---
# <a name="sharepoint-for-us-government-environments"></a>适用于美国政府环境的 SharePoint

本文概述了美国政府云与商业云之间的功能差异，如 [SharePoint 服务说明所列](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-service-description)。 SharePoint 适用于政府社区云 (GCC) GCC High 和 DoD 环境。 

有关政府云（包括资格和购买）详细信息，请参阅 [Microsoft 365 政府版 - 如何购买](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy)。 若要比较 Office 365 政府版计划，请参阅 [Office 365 政府版计划](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)。

若要了解管理网络连接时所需的终结点，请参阅 [Office 365 美国政府版 GCC 高](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) 终结点或 Office [365 美国政府 DoD 终结点](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)。

除了享受 Office 365 的特性和功能外，组织还可从美国政府云环境特有的以下功能中获益：

-   组织的客户内容在逻辑上与 Microsoft 商业 Office 365 服务中的客户内容隔离。
-   您组织的客户内容存储在美国境内。
-   对组织的客户内容的访问权限只限于屏蔽的 Microsoft 员工。
-   政府云环境符合美国公共部门客户所需的认证和资格鉴定。

我们的目标是向政府云环境提供所有 SharePoint 商业特性和功能。 由于政府云客户的要求，某些功能不可用。 其他功能将进入政府环境，但尚未提供。 请参阅以下部分，了解政府云环境中的功能可用性。

## <a name="developer-features"></a>开发人员功能

商业客户的开发人员功能与政府云客户的开发人员功能之间没有已知的差异。

- 与外部应用程序（如外接程序的数据源）的连接仅限于位于政府环境支持的系统安全边界内的源。
- Business Connectivity Services (BCS) 功能支持连接方案，其中数据源在云服务的安全边界内仍然可用。

如果您在网站上使用第三方应用程序，请查看第三方在评估这些服务对组织的适当使用时提供的隐私和合规性声明。 第三方应用程序和服务可能涉及在政府云之外的第三方系统上存储、传输和处理组织的客户数据，因此其合规性和数据保护承诺未涵盖这些系统。 

## <a name="it-admin-features"></a>IT 管理员功能

以下是商业客户的 IT 管理员功能与政府云客户的 IT 管理员功能之间的差异。

- 更改站点地址不适用于 GCC 高客户
- 混合 SharePoint Server 并非适用于所有政府云客户
- SharePoint 迁移工具和迁移管理器需要更改配置。 有关信息，请参阅 [SPMT 政府云支持](/sharepointmigration/spmt-install-issues#government-cloud-support)。
- Mover.io尚不支持
- 多地理位置并非适用于所有政府云客户

有关 FastTrack 迁移的信息，请参阅 [Office 365 美国政府版服务说明](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#data-migrations-performed-by-fasttrack)。

## <a name="security-and-compliance-features"></a>安全性和合规性功能

商业客户和政府云客户的安全性和合规性功能之间没有已知的差异。

有关安全性和合规性功能的信息，请参阅安全与合规& [中心](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-securitycompliance-center)。

有关政府版 Azure Active Directory 功能的信息，请参阅 [Azure 政府安全 + 标识文档](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory)。 

有关政府版 Azure 信息保护功能的信息，请参阅 [Azure 信息保护高级政府服务说明](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description)。 

## <a name="sites-and-content"></a>网站和内容

以下是商业客户的网站和内容功能与政府云客户的网站和内容功能之间的差异：

- 依赖于连接到 Internet 服务的 Web 部件（如 Amazon Tube、必应地图、Twitter 和 YouTube Web 部件）无法正常工作
- 组织资产库不可用
- 向 Teams 添加列表和页面不适用于 GCC High 和 DoD 客户
- SharePoint Online 中适用于 GCC High 的图形功能当前已禁用。 依赖 Microsoft Graph 的任何服务当前可能不可用
- 依赖于 Internet 服务连接的功能（如股票图像选项卡）无法按预期工作

## <a name="search-features"></a>搜索功能

以下是商业客户搜索功能与政府云客户搜索功能之间的差异：

- Microsoft 搜索集成不可用。

## <a name="sharing-and-sync"></a>共享和同步

有关商业云和政府云环境之间的功能差异，请参阅 [文件共享](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/gcc-high-and-dod#file-sharing)。

## <a name="plan-for-governance"></a>规划治理

移动到云后，内置管理控件可提供变革性体验。 确定管理要求以及如何满足这些要求。 有关详细信息 [，请转到"规划治理"以通过 Microsoft 365](https://resources.techcommunity.microsoft.com/teamwork-governance/) 转变团队合作。 你将找到有关 Office 365 组、SharePoint、Teams 等的指南。

## <a name="deploy-sharepoint-for-collaboration"></a>部署 SharePoint 进行协作

在 Microsoft 美国政府云中设置组织后，请按照 SharePoint 采用资源中心中概述 [的建议部署路径操作](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/)。 请务必与采用和变更管理冠军合作。
还可以与 [FastTrack 或](https://www.microsoft.com/fasttrack) 所选的合作伙伴合作，向用户推出服务。
访问 [Microsoft 信任中心](https://www.microsoft.com/trust-center) ，详细了解 Microsoft 如何采用安全性、隐私和合规性方法，以及我们如何使组织能够为客户提供服务的核心原则。
