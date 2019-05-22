---
title: 开发人员
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 05/20/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- sharepoint-online-developer-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 415c9536-ae70-4d4b-b481-5255cb03cc32
description: SharePoint Online 是基于 Web 的工具和技术的集合, 可帮助您的组织存储、共享和管理数字信息。 此托管服务基于 Microsoft SharePoint Server 2013 构建，是处理项目、在中心位置存储数据和文档以及与他人共享信息的理想服务。 以下功能可为要构建应用和解决方案的开发人员扩展 SharePoint 功能提供支持。
ms.openlocfilehash: c1b9bd6e86b14d8328edabc0ebf1d81fb592fb21
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/22/2019
ms.locfileid: "34342511"
---
# <a name="developer"></a>开发人员

SharePoint Online 是基于 Web 的工具和技术的集合, 可帮助您的组织存储、共享和管理数字信息。 此托管服务基于 Microsoft SharePoint Server 2013 构建，是处理项目、在中心位置存储数据和文档以及与他人共享信息的理想服务。 以下功能可为要构建应用和解决方案的开发人员扩展 SharePoint 功能提供支持。
  
## <a name="app-catalog-sharepoint"></a>App Catalog (SharePoint)
<a name="bkmk_AppCatalogSharePoint"> </a>

将应用程序发布到 SharePoint 部署中托管的内部企业目录，以供有权访问 SharePoint 部署的用户使用。详细了解如何[发布 Office 和 SharePoint 相关应用程序](https://docs.microsoft.com/office/dev/store/submit-to-the-office-store)。
  
## <a name="app-deployment-cloud-hosted-apps"></a>App Deployment: Cloud-Hosted Apps
<a name="bkmk_AppDeploymentCloudHostedApps"> </a>

云托管的 SharePoint 相关应用程序至少包含一个远程组件，还可能包含 SharePoint 托管的组件。详细了解 [SharePoint 相关应用程序的托管选项](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/choose-patterns-for-developing-and-hosting-your-sharepoint-add-in)。 
  
## <a name="app-deployment-sharepoint-hosted-apps"></a>App Deployment: SharePoint-Hosted Apps
<a name="bkmk_AppDeploymentSharePointHostedApps"> </a>

借助 SharePoint 托管的应用程序，可以重用常见的 SharePoint 项目，如列表和 Web 部件。采用这种方法时，只能使用 JavaScript，不得使用任何服务器端代码。详细了解 [SharePoint 相关应用程序的托管选项](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/choose-patterns-for-developing-and-hosting-your-sharepoint-add-in)。
  
## <a name="app-management-services"></a>App Management Services
<a name="bkmk_AppManagementServices"> </a>

应用程序管理服务数据库存储所有 SharePoint 应用程序的许可信息。 
  
## <a name="bcs-app-scoped-external-content-types-ects"></a>BCS: App Scoped External Content Types (ECTs)
<a name="bkmk_AppScopedExternalContentTypes"> </a>

在 SharePoint 中添加新的应用程序模型后, Business Connectivity Services (BCS) 现在可以在应用程序级别而不是在服务器场级别对外部内容类型进行作用域。 这样, 应用程序开发人员可以在应用程序中使用外部数据, 从而为应用程序开发人员提供极大的灵活性。 详细了解[在应用程序一级限定的外部内容类型](https://docs.microsoft.com/sharepoint/dev/general-development/add-in-scoped-external-content-types-in-sharepoint)。
  
## <a name="bcs-business-data-web-parts"></a>BCS: 业务数据 Web 部件
<a name="bkmk_BCSBusinessDataWebparts"> </a>

业务数据 Web 部件是使用外部数据的特殊 Web 部件。 它们可以像标准 SharePoint Web 部件一样使用, 而是基于外部内容类型, 这是对外部数据的连接的 XML 说明。 
  
## <a name="bcs-external-list"></a>BCS: External List
<a name="bkmk_BCSExternalList"> </a>

外部列表是一种用于显示外部数据源数据的特殊 SharePoint 列表。此类列表在描述数据源的外部内容类型的基础之上生成，以便用户能够在熟悉的 SharePoint 界面中处理数据。详细了解[外部内容类型](https://docs.microsoft.com/SharePoint/administration/deploy-an-on-premises-solution)。 
  
## <a name="bcs-odata-connector"></a>BCS: OData connector
<a name="bkmk_OdataConnector"> </a>

OData 连接器是 SharePoint 的新组件。它可让 Business Connectivity Services (BCS) 将 RESTful OData 端点用作外部列表、业务数据 Web 部件和用户自定义界面的数据源。
  
## <a name="bcs-rich-client-integration"></a>BCS: Rich Client Integration
<a name="bkmk_BCSRichClientIntegration"> </a>

SharePoint Online 客户无法使用此功能。Business Connectivity Services (BCS) 使用免费的客户端和服务器端体系结构，让 Office 客户端（如 Outlook 和 Excel）直接处理通过外部内容类型向 SharePoint 公开的外部数据。详细了解 [Business Connectivity Services 客户端运行时](https://docs.microsoft.com/previous-versions/office/developer/sharepoint-2010/ee559310(v=office.14))。
  
## <a name="client-object-model-om"></a>Client Object Model (OM)
<a name="bkmk_ClientObjectModel"> </a>

SharePoint 2013 有三种用于托管代码的客户端对象模型：.NET、Silverlight 和移动。此外，SharePoint 包含 JavaScript 客户端对象模型。详细了解如何[在 SharePoint 2013 中选择正确的 API 集](https://docs.microsoft.com/sharepoint/dev/general-development/choose-the-right-api-set-in-sharepoint)。
  
## <a name="custom-site-provisioning-page"></a>自定义站点设置页面
<a name="bkmk_CustomSiteProvisioning"> </a>

对 SharePoint Online 客户不可用。SharePoint Server 2013 客户可以让用户快速简单地请求站点并快速开始使用其站点。
  
## <a name="developer-site"></a>开发人员站点
<a name="bkmk_DeveloperSite"> </a>

将 Office 365 开发人员网站用作开发和测试环境，以缩短设置时间，并开始创建、测试和部署 SharePoint 相关应用程序。详细了解如何[注册 Office 365 开发人员网站](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/create-a-developer-site-on-an-existing-office-365-subscription)。
  
## <a name="forms-based-applications"></a>Forms Based Applications
<a name="bkmk_FormsBasedApplications"> </a>

窗体视图基本上是一个包含控件的视图。使用基于窗体的应用程序，用户可以在应用程序中创建和使用一个或多个窗体。详细了解[基于窗体的应用程序](https://docs.microsoft.com/previous-versions/visualstudio/visual-studio-6.0/aa733955(v=vs.60))。
  
## <a name="full-trust-solutions"></a>Full-Trust Solutions
<a name="bkmk_FullTrustSolutions"> </a>

SharePoint Online 客户无法使用此功能。SharePoint Server 2013 客户可以创建完全信任解决方案（亦称为"场解决方案"）。与 SharePoint 相关应用程序不同，场解决方案包含部署到 SharePoint 服务器且调用 SharePoint 服务器对象模型的代码。这些程序集始终以完全信任级别运行。场解决方案应用于自定义 SharePoint 管理功能，如自定义计时器作业、自定义 Windows PowerShell cmdlet 和扩展管理中心。详细了解如何[在 SharePoint 2013 中生成场解决方案](https://docs.microsoft.com/sharepoint/dev/general-development/build-farm-solutions-in-sharepoint)。
  
## <a name="infopath-forms-services"></a>InfoPath Forms Services
<a name="bkmk_InfoPathFormsServices"> </a>

窗体服务根据 InfoPath 中设计的窗体模板，在 SharePoint 中提供 Web 浏览器窗体填充体验。详细了解 [InfoPath Forms Services](https://docs.microsoft.com/previous-versions/office/developer/sharepoint-2007/ms540731(v=office.12))。
  
## <a name="javascript-object-model"></a>JavaScript 对象模型
<a name="bkmk_JavaScriptObjectModel"> </a>

SharePoint 提供了用于内联脚本或各个 .js 文件的 JavaScript 对象模型。它包括与 .NET Framework 和 Silverlight 客户端对象模型一样的所有功能。JavaScript 对象模型是在应用程序中包含自定义 SharePoint 代码的有效方法。借助此模型，Web 开发者还可以利用掌握的现有 JavaScript 技能创建 SharePoint 应用程序，尽可能缩短学习曲线。详细了解 [SharePoint 2013 JavaScript API 参考](https://docs.microsoft.com/previous-versions/office/sharepoint-visio/jj193034(v=office.15))。
  
## <a name="remote-event-receiver"></a>远程事件接收器
<a name="bkmk_RemoteEventReceiver"> </a>

若要处理 SharePoint 相关应用程序中的事件，开发者可创建远程事件接收器和应用程序事件接收器。远程事件接收器可处理应用程序中某个项目（如列表、列表项或 Web）发生的事件。详细了解如何[处理 SharePoint 相关应用程序中的事件](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/handle-events-in-sharepoint-add-ins)。 
  
## <a name="rest-apis"></a>REST API
<a name="bkmk_RESTAPI"> </a>

SharePoint 2013 实现了表述性状态转移 (REST) Web 服务，此服务使用 OData 协议对 SharePoint 列表数据执行 CRUD 操作。如果必须通过不使用 JavaScript 且不是在 .NET Framework 或 Microsoft Silverlight 平台基础之上生成的客户端技术访问 SharePoint 数据，请使用此 API。详细了解如何[使用 SharePoint 2013 REST 服务进行编程](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/use-odata-query-operations-in-sharepoint-rest-requests)。
  
## <a name="sharepoint-design-manager"></a>SharePoint Design Manager
<a name="bkmk_SharePointDesignerManager"> </a>

使用此设计管理器，可以分步创建用于确定网站品牌的设计资产。上载设计资产（图像、HTML、CSS 等），然后创建母版页和页面布局。详细了解 [SharePoint 2013 网站开发](https://docs.microsoft.com/sharepoint/dev/general-development/what-s-new-with-sharepoint-site-development)。
  
## <a name="sharepoint-designer-2013"></a>SharePoint Designer 2013
<a name="bkmk_SharePointDesigner"> </a>

使用 SharePoint Designer，高级用户和开发者可以快速创建 SharePoint 解决方案，以满足业务需求。详细了解[面向开发者的 SharePoint Designer](https://go.microsoft.com/fwlink/?LinkId=271294)。
  
## <a name="sharepoint-framework"></a>SharePoint 框架
<a name="bkmk_SharePointFramework"> </a>

SharePoint Framework (SPFx) 是提供客户端 SharePoint 开发和与 SharePoint 数据简单集成完全支持及开放源代码工具支持的页面和 Web 部件模型。 了解有关[SharePoint 框架](https://docs.microsoft.com/sharepoint/dev/spfx/sharepoint-framework-overview)的详细信息。
  
## <a name="sharepoint-2010-workflows-out-of-the-box"></a>SharePoint 2010 工作流（现成）
<a name="bkmk_Worflow2010outofthebox"> </a>

使用 SharePoint 附随的开箱即用工作流对常用业务过程建模。
  
## <a name="sharepoint-2013-and-sharepoint-2016-workflows"></a>SharePoint 2013 和 SharePoint 2016 工作流
<a name="bkmk_Workflow2013"> </a>

SharePoint 2013 和 SharePoint 2016 工作流由 Windows Workflow Foundation 4 (WF) 提供支持, 这是从早期版本中显著重新设计的。 或许新工作流基础结构的最显著的功能是引入 Azure 作为工作流执行主机。 了解有关[SharePoint 的工作流的新增功能的](https://docs.microsoft.com/sharepoint/dev/general-development/what-s-new-in-workflows-for-sharepoint)详细信息。
  
## <a name="feature-availability"></a>功能可用性
<a name="bkmk_Workflow2013"> </a>

若要查看在各个 Office 365 计划、独立选项和内部部署解决方案之间的功能可用性，请参阅 [SharePoint Online 服务说明](sharepoint-online-service-description.md)。
  

