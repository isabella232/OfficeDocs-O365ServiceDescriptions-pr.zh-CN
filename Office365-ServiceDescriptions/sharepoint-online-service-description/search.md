---
title: 搜索
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
audience: ITPro
ms.topic: reference
f1_keywords:
- sharepoint-online-search-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cb36484c-0e8f-480e-be88-5daa8bf2d47d
description: SharePoint Online 是基于 Web 的工具和技术的集合, 可帮助您的组织存储、共享和管理数字信息。 此托管服务基于 Microsoft SharePoint Server 2013 构建，是处理项目、在中心位置存储数据和文档以及与他人共享信息的理想服务。 以下搜索功能帮助人们找到完成工作所需的信息。 搜索是相关性、精化和人员的组合。
ms.openlocfilehash: ec249b2b9fdc6e2ffc0efc60ae7a8a00a01424c2
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/22/2019
ms.locfileid: "34342541"
---
# <a name="search"></a>搜索

SharePoint Online 是基于 Web 的工具和技术的集合, 可帮助您的组织存储、共享和管理数字信息。 此托管服务基于 Microsoft SharePoint Server 2013 构建，是处理项目、在中心位置存储数据和文档以及与他人共享信息的理想服务。 以下搜索功能帮助人们找到完成工作所需的信息。 搜索是相关性、精化和人员的组合。
  
## <a name="continuous-crawls"></a>连续爬网
<a name="bkmk_ContinuousCrawl"> </a>

连续爬网经常对 SharePoint 网站中的内容进行爬网，有助于不断更新搜索结果。连续爬网在 SharePoint Online 中启用，爬网频率由 Microsoft 进行管理。在 SharePoint Server 2013 中，管理员可以启用连续爬网，并管理连续爬网频率。详细了解 [SharePoint Server 2013 中的默认爬网文件扩展名和分析文件类型](https://technet.microsoft.com/en-us/library/jj219530.aspx)。详细了解如何[管理连续爬网](https://go.microsoft.com/fwlink/?LinkID=271001)。
  
## <a name="deep-links"></a>Deep links
<a name="bkmk_DeepLink"> </a>

搜索系统会自动创建链接，直接转到经常访问的主页的子部分。此类链接被称为"深层链接"。详细了解 [SharePoint 搜索系统](https://go.microsoft.com/fwlink/p/?LinkId=286608)。
  
## <a name="event-based-relevancy"></a>Event-based relevancy
<a name="bkmk_EventBasedRelevancy"> </a>

搜索系统根据内容连接方式、项在搜索结果中的显示频率和获得单击的搜索结果来确定搜索结果的相关性。分析组件会跟踪和分析此类信息，并用来不断提高相关性。详细了解[分析处理](https://go.microsoft.com/fwlink/?LinkID=271000)。
  
## <a name="expertise-search"></a>Expertise Search
<a name="bkmk_ExpertiseSearch"> </a>

在 SharePoint 中，掌握人员垂直搜索的特定技能或专业知识，查找人员更容易。搜索结果的依据为用户在个人网站上输入的有关自己的元数据，以及已经创建的内容等信息。详细了解如何[更改垂直搜索设置](https://go.microsoft.com/fwlink/p/?LinkId=286610)。
  
## <a name="graphical-refiners"></a>Graphical refiners
<a name="bkmk_GraphicalRefiners"> </a>

使用全新的图形精简条件，可以更直观地筛选搜索结果。详细了解如何[配置"精化"Web 部件](https://go.microsoft.com/fwlink/?LinkId=271017)。
  
## <a name="hybrid-search"></a>混合搜索
<a name="bkmk_HybridSearch"> </a>

在 SharePoint 混合部署中，搜索结果内容可源自 SharePoint Online 和 SharePoint Server 2013 本地网站。若要详细了解混合 SharePoint 环境，请参阅 [SharePoint Server 2013 的混合](https://go.microsoft.com/fwlink/?LinkId=275765)。
  
## <a name="manage-search-schema"></a>管理搜索架构
<a name="bkmk_manage_search_schema"> </a>

当有人在 SharePoint 网站上搜索内容时，搜索索引决定了他们的搜索结果。搜索索引包含网站上所有文档和页面的信息，通过对 SharePoint 网站上的内容进行爬网而生成。搜索架构有助于爬网程序决定要选取的内容和元数据，以及如何编制索引。你可以通过更改搜索架构来为用户提供自定义的搜索体验。详细了解如何[在 SharePoint Online 中管理搜索架构](https://go.microsoft.com/fwlink/p/?LinkId=392427)。
  
## <a name="on-hover-preview"></a>悬停预览
<a name="bkmk_Quickpreview"> </a>

用户可以将指针悬停在搜索结果上，在结果右侧的悬停面板中预览文档或网站内容并与之交互。预览显示丰富的元数据，以及指向文档或网站的主要部分的深层链接。详细了解[搜索提示](https://go.microsoft.com/fwlink/p/?LinkId=286614)。
  
## <a name="phonetic-name-matching"></a>Phonetic name matching
<a name="bkmk_PhoneticNameMatching"> </a>

改进后的拼音名称匹配会在搜索结果中查找发音类似的名称（是 John 还是 Jon？）。详细了解如何[管理结果来源](https://go.microsoft.com/fwlink/p/?LinkId=286609)。
  
## <a name="query-rulesadd-promoted-results"></a>查询规则添加已升级结果
<a name="bkmk_QueryRulesAddpromotedresults"> </a>

在查询规则中，指定条件和相关操作。如果查询满足查询规则中的条件，搜索系统会执行规则中指定的操作。使用"添加已提升的结果"操作，可以提升各个结果，使其显示在搜索结果顶部。详细了解如何[管理查询规则](https://go.microsoft.com/fwlink/p/?LinkId=286607)。
  
## <a name="query-rulesadvanced-actions"></a>Query rules—advanced actions
<a name="bkmk_UserRulesAdvancedActions"> </a>

在查询规则中，可以指定条件和相关操作。使用"添加结果块"操作，可以组的形式显示一部分搜索结果。使用"通过更改查询更改排名结果"操作，可以更改返回的搜索结果的排名。详细了解如何[管理查询规则](https://go.microsoft.com/fwlink/p/?LinkId=286607)。
  
## <a name="query-spelling-correction"></a>Query spelling correction
<a name="bkmk_QuerySpellingCorrection"> </a>

编辑排除和包含列表，决定应在搜索结果页上显示哪些查询的备用查询拼写。此功能通常称为"您的意思是？"。详细了解[查询拼写更正](https://go.microsoft.com/fwlink/?LinkId=271221)。
  
## <a name="query-suggestions"></a>查询建议
<a name="bkmk_Querysuggestions"> </a>

查询建议是用户已搜索过的建议短语。键入查询时，用户会在搜索框下的列表中看到查询建议。查询建议自动生成，同时短语可作为"始终建议"或"从不建议"查询建议添加到系统中。详细了解如何[管理查询建议](https://go.microsoft.com/fwlink/p/?LinkId=286611)。
  
## <a name="ranking-models"></a>分级模型
<a name="bkmk_Ranking_Models"> </a>

SharePoint 使用排名模型向搜索结果分配值，以便最相关的项显示最靠前。排名模型是一组用于计算特定项的排名得分的排名因素。SharePoint Online 和 SharePoint Server 2013 包括多种无需进一步自定义就能提供有效排名的排名模型。然而，如果需要提高搜索结果与最终用户的相关性，可以自定义排名模型。使用排名模型优化应用，SharePoint Online 客户可以创建自定义排名模型。可以在此应用的用户界面上复制现有排名模型，判断一组查询的结果，然后添加或删除排名功能，并调整这些功能的权重，"优化"排名模型。详细了解如何[搜索结果排名](https://go.microsoft.com/fwlink/p/?LinkId=271014)。
  
## <a name="refiners"></a>Refiners
<a name="bkmk_Refiners"> </a>

精简条件将 SharePoint Server 搜索结果中排名靠前的文档归入组中，以便用户可以筛选搜索结果。详细了解如何[配置"精简"Web 部件](https://go.microsoft.com/fwlink/?LinkId=271017)。
  
## <a name="restful-query-apiquery-om"></a>RESTful Query API/Query OM
<a name="bkmk_RESTfulQueryAPI"> </a>

开发人员可以创建 .NET 代码以访问公共搜索对象模型。除了提交搜索查询之外，这还包括搜索管理操作。要与服务端对象模型进行交互，.NET 代码必须在农场的 Web 服务器上运行。可以使用客户端对象模型 (CSOM)，从远程计算机访问对象模式的子集。可以使用基于 REST 的 Web 服务或 oData 访问客户端对象模型 (CSOM) 的功能。这允许开发人员使用流行的 Web 开发工具提交查询给 SharePoint Server 2013 农场。
  
## <a name="search-results-sorting"></a>Search results sorting
<a name="bkmk_Searchresultssorting"> </a>

用户可以选择按不同的条件（例如，相关性、新鲜度和社会距离（人员姓名））对搜索结果进行排序。详细了解[搜索结果排序](https://go.microsoft.com/fwlink/p/?LinkId=286603)。
  
## <a name="this-list-searches"></a>"此列表"搜索
<a name="bkmk_ThisListSearches"> </a>

在 SharePoint Online 和 SharePoint Server 2013 中，可将搜索限制在执行搜索的列表或库中。在 SharePoint Foundation 2013 中，搜索将返回存在于执行搜索的网站或网站下面的所有列表和库中的结果。
  
## <a name="feature-availability"></a>功能可用性
<a name="bkmk_ThisListSearches"> </a>

若要查看在各个 Office 365 计划、独立选项和内部部署解决方案之间的功能可用性，请参阅 [SharePoint Online 服务说明](sharepoint-online-service-description.md)。
  

