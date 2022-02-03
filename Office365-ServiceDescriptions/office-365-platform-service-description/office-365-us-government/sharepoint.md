---
title: SharePoint美国政府环境
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.reviewer: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: 了解美国政府SharePoint客户的功能可用性。
ms.openlocfilehash: e36cd90748732166c9b3ddfe7ba3362a268c5e1d
ms.sourcegitcommit: 676e301238f7e8b910cc61ec96ba3327b9b4fb73
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 02/03/2022
ms.locfileid: "62332367"
---
# <a name="sharepoint-for-us-government-environments"></a>SharePoint美国政府环境

本文概述了美国政府云与商业云之间的功能差异，如 SharePoint [service description 中所列](../../sharepoint-online-service-description/sharepoint-online-service-description.md)。 SharePoint适用于 政府社区云 (GCC) 、GCC High 和 DoD 环境。 

有关政府云（包括资格和购买）Microsoft 365[政府 - 如何购买](./microsoft-365-government-how-to-buy.md)。 若要比较Office 365 政府版，请参阅Office 365 政府版[计划](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)。

若要了解管理网络连接时所需的终结点，请参阅 Office 365 美国政府 GCC [高](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business)终结点或 Office 365 美国政府 [DoD 终结点](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)。

除了享受云解决方案Office 365，组织还可从美国政府云环境独有的以下功能中获益：

-   在逻辑上，组织的客户内容与 Microsoft 商业服务中的客户Office 365隔离。
-   您组织的客户内容存储在美国境内。
-   对组织的客户内容的访问权限只限于屏蔽的 Microsoft 员工。
-   政府云环境符合美国公共部门客户所需的认证和资格鉴定。

我们的目标是向政府云环境SharePoint商业特性和功能。 由于政府云客户的要求，某些功能不可用。 其他功能将进入政府环境，但尚未提供。 请参阅以下部分，了解政府云环境中的功能可用性。

## <a name="developer-features"></a>开发人员功能

商业客户的开发人员功能与政府云客户的开发人员功能之间没有已知的差异。

- 与外部应用程序（如外接程序的数据源）的连接仅限于位于政府环境支持的系统安全边界内的源。
- 业务连接服务 (BCS) 支持连接功能，在这些方案中，数据源在云服务的安全边界内仍然可用。

如果网站上使用第三方应用程序，请查看第三方在评估这些服务对组织的适当使用时提供的隐私和合规性声明。 第三方应用程序和服务可能涉及在政府云外部的第三方系统上存储、传输和处理组织的客户数据，因此其合规性和数据保护承诺未涵盖这些数据。 

## <a name="it-admin-features"></a>IT 管理员功能

以下是商业客户的 IT 管理员功能与政府云客户的 IT 管理员功能之间的差异。

- 网站地址更改不适用于高GCC客户。
- 迁移SharePoint和迁移管理器需要更改配置。 有关详细信息，请参阅 [SPMT 政府云支持](/sharepointmigration/spmt-install-issues#government-cloud-support)。
- Mover.io 尚不支持。
- 多地理位置并非适用于所有政府云客户。
- GCC 高和 DoD 客户的 SharePoint 管理中心主页上未提供以下卡片：SharePoint 存储使用情况、SharePoint 网站使用情况、OneDrive 使用情况、SharePoint 文件活动和 OneDrive 文件活动。
- [所有政府云](/sharepoint/manage-sites-in-new-admin-center#track-a-view)客户在管理中心SharePoint查看卡。

有关迁移FastTrack，请参阅美国政府Office 365[服务说明](./office-365-us-government.md#data-migrations-performed-by-fasttrack)。

## <a name="security-and-compliance-features"></a>安全性和合规性功能

商业客户的安全性和合规性功能与政府云客户的安全性和合规性功能之间没有已知的差异。

有关安全性和合规性功能的信息，请参阅Microsoft 365[合规性指南&amp;](/office365/servicedescriptions/microsoft-365-service-descriptions/microsoft-365-tenantlevel-services-licensing-guidance/microsoft-365-security-compliance-licensing-guidance)。

有关政府Azure Active Directory的信息，请参阅 [Azure 政府安全 + 标识文档](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory)。 

有关 Azure 信息保护政府功能的信息，请参阅 [Azure 信息保护高级版政府服务说明](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description)。 

有关这些功能SharePoint Syntex，请参阅 SharePoint Syntex [功能服务说明](/office365/servicedescriptions/sharepoint-syntex-service-description/sharepoint-syntex-features)。

## <a name="sites-and-content"></a>网站和内容

以下是商业客户的网站和内容功能与政府云客户的网站和内容功能之间的差异：

- 依赖于 Internet 服务连接的 Web 部件（如 Amazon Tube、必应地图、Twitter 和 YouTube Web 部件）无法如期工作
- 组织资产库不可用
- Graph禁用 SharePoint Online 中GCC高的功能。 任何依赖 Microsoft Graph服务可能当前不可用
- 依赖于 Internet 服务连接的功能（如股票图像选项卡）无法按预期工作
- 文件和网站活动的通知不可用
- 新闻 Web 部件将仅从当前网站拉取新闻。 来自选定网站或中心新闻汇总的关联网站新闻不适用于高GCC DoD 客户

## <a name="search-features"></a>搜索功能

以下是商业客户的搜索功能与政府云客户的搜索功能之间的差异：

- Microsoft 搜索中不可用GCC。

## <a name="sharing-and-sync"></a>共享和同步

有关商业云和政府云环境之间的功能差异，请参阅 [文件共享](./gcc-high-and-dod.md#file-sharing)。

## <a name="plan-for-governance"></a>规划治理

移动到云后，内置管理控件可提供转换式体验。 确定管理要求以及如何满足这些要求。 有关详细信息[，请转到规划治理以通过](https://resources.techcommunity.microsoft.com/teamwork-governance/)Microsoft 365团队。 你将找到有关组Office 365、SharePoint、Teams等的指南。

## <a name="deploy-sharepoint-for-collaboration"></a>部署SharePoint进行协作

在 Microsoft 美国政府云中设置组织后，请按照应用资源中心中列出的SharePoint[部署路径。](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/) 请务必与采用和变更管理冠军合作。
此外，还可与[FastTrack](https://www.microsoft.com/fasttrack)合作伙伴合作，向用户推出服务。
访问 [Microsoft 信任中心](https://www.microsoft.com/trust-center) ，详细了解 Microsoft 如何处理安全、隐私和合规性，以及我们如何授权组织为客户提供服务的核心原则。

## <a name="configuring-sharepoint-hybrid-configuration-wizard-support-for-all-government-cloud-customers"></a>为SharePoint云客户配置混合配置向导支持

混合SharePoint向导包含对具有特殊 SPO SharePoint混合功能的支持。

您必须在安全文件中编辑环境相关参数 **.config，使** 混合SharePoint可用于该环境。 请参阅 [编辑配置文件](#editing-configuration-file)。

> [!NOTE]
> 有关混合功能支持的特殊 SPO SharePoint，请参阅S supported [Environments](#supported-environments)。

## <a name="editing-configuration-file"></a>编辑配置文件

1. 安装或更新混合SharePoint向导。
2. 转到安装混合配置向导SharePoint的文件夹。 例如，`%LOCALAPPDATA%\Apps\HybridSP\HybridSP`
3. 在 **microsoft.online.cse.hybridsp.common.dll.config** 编辑器（如文本编辑器）中启动记事本。
此文件中的内容如以下屏幕截图中所示：

:::image type="content" source="../../media/content.png" alt-text="配置文件中的内容":::

4. 修改参数 `SPOEnvironmentType` 的值。
5. 将更改 **保存在microsoft.online.cse.hybridsp.common.dll.config文件中** 。
6. 重新启动混合SharePoint向导。
   将应用设置，SharePoint配置 SPO 环境中提供混合功能。

## <a name="supported-environments"></a>支持的环境

SharePoint混合功能支持以下 SPO 环境：

- 公共
- PPE
- GCC
- GccHigh
- DoD
- 自定义警报

如果客户将值设置为 `SPOEnvironmentType` **Custom**，则`AuthorityEndPoint`使用 、 `AADGraphEndPoint``MSGraphEndPoint` 和 键来设置该自定义 SPO 环境的终结点。

如果该值`SPOEnvironmentType`设置为 **Custom**`AuthorityEndPoint` 外的任何值，则忽略 、 `AADGraphEndPoint``MSGraphEndPoint` 和 键，SharePoint 混合配置向导将使用适用于这些 SPO 环境类型的硬编码值。
