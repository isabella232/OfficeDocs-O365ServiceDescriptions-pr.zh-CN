---
title: 搜索
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- sharepoint-online-search-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cb36484c-0e8f-480e-be88-5daa8bf2d47d
description: SharePoint Online 是基于 Web 的工具和技术的集合, 可帮助您的组织存储、共享和管理数字信息。 此托管服务基于 Microsoft SharePoint Server 2013 构建，是处理项目、在中心位置存储数据和文档以及与他人共享信息的理想服务。 以下搜索功能帮助人们找到完成工作所需的信息。 搜索是相关性、精化和人员的组合。
ms.openlocfilehash: 689960f76e5de434af90c6d4d8d8f2da82a07f5f
ms.sourcegitcommit: 96dc758c790ddaf05f5c2b836451b417729cf119
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/18/2019
ms.locfileid: "35777863"
---
# <a name="search"></a><span data-ttu-id="cff04-106">搜索</span><span class="sxs-lookup"><span data-stu-id="cff04-106">Search</span></span>

<span data-ttu-id="cff04-107">SharePoint Online 是基于 Web 的工具和技术的集合, 可帮助您的组织存储、共享和管理数字信息。</span><span class="sxs-lookup"><span data-stu-id="cff04-107">SharePoint Online is a collection of Web-based tools and technologies that help your organization store, share, and manage digital information.</span></span> <span data-ttu-id="cff04-108">此托管服务基于 Microsoft SharePoint Server 2013 构建，是处理项目、在中心位置存储数据和文档以及与他人共享信息的理想服务。</span><span class="sxs-lookup"><span data-stu-id="cff04-108">Built on Microsoft SharePoint Server 2013, this hosted service is ideal for working on projects, storing data and documents in a central location, and sharing information with others.</span></span> <span data-ttu-id="cff04-109">以下搜索功能帮助人们找到完成工作所需的信息。</span><span class="sxs-lookup"><span data-stu-id="cff04-109">The following Search features help people find the information that they need to do their jobs.</span></span> <span data-ttu-id="cff04-110">搜索是相关性、精化和人员的组合。</span><span class="sxs-lookup"><span data-stu-id="cff04-110">Search is a combination of relevance, refinement, and people.</span></span>
  
## <a name="continuous-crawls"></a><span data-ttu-id="cff04-111">连续爬网</span><span class="sxs-lookup"><span data-stu-id="cff04-111">Continuous crawls</span></span>
<span data-ttu-id="cff04-112"><a name="bkmk_ContinuousCrawl"> </a></span><span class="sxs-lookup"><span data-stu-id="cff04-112"></span></span>

<span data-ttu-id="cff04-p103">连续爬网经常对 SharePoint 网站中的内容进行爬网，有助于不断更新搜索结果。连续爬网在 SharePoint Online 中启用，爬网频率由 Microsoft 进行管理。在 SharePoint Server 2013 中，管理员可以启用连续爬网，并管理连续爬网频率。详细了解 [SharePoint Server 2013 中的默认爬网文件扩展名和分析文件类型](https://docs.microsoft.com/sharepoint/technical-reference/default-crawled-file-name-extensions-and-parsed-file-types)。详细了解如何[管理连续爬网](https://docs.microsoft.com/SharePoint/search/manage-continuous-crawls)。</span><span class="sxs-lookup"><span data-stu-id="cff04-p103">Continuous crawls help keep search results fresh by frequently crawling content in SharePoint sites. Continuous crawls are enabled in SharePoint Online, with crawl frequencies managed by Microsoft. In SharePoint Server 2013, administrators can enable continuous crawls and manage continuous crawl frequencies. Learn more about [default crawled file name extensions and parsed file types in SharePoint](https://docs.microsoft.com/sharepoint/technical-reference/default-crawled-file-name-extensions-and-parsed-file-types). Learn more about [managing continuous crawls](https://docs.microsoft.com/SharePoint/search/manage-continuous-crawls).</span></span>
  
## <a name="deep-links"></a><span data-ttu-id="cff04-118">Deep links</span><span class="sxs-lookup"><span data-stu-id="cff04-118">Deep links</span></span>
<span data-ttu-id="cff04-119"><a name="bkmk_DeepLink"> </a></span><span class="sxs-lookup"><span data-stu-id="cff04-119"></span></span>

<span data-ttu-id="cff04-p104">搜索系统会自动创建链接，直接转到经常访问的主页的子部分。此类链接被称为"深层链接"。详细了解 [SharePoint 搜索系统](https://docs.microsoft.com/sharepoint/dev/general-development/search-in-sharepoint)。</span><span class="sxs-lookup"><span data-stu-id="cff04-p104">The search system automatically creates links directly to sub-sections of a main page that is frequently visited. These links are called "deep links". Learn more about the [SharePoint search system](https://docs.microsoft.com/sharepoint/dev/general-development/search-in-sharepoint).</span></span>
  
## <a name="event-based-relevancy"></a><span data-ttu-id="cff04-123">Event-based relevancy</span><span class="sxs-lookup"><span data-stu-id="cff04-123">Event-based relevancy</span></span>
<span data-ttu-id="cff04-124"><a name="bkmk_EventBasedRelevancy"> </a></span><span class="sxs-lookup"><span data-stu-id="cff04-124"></span></span>

<span data-ttu-id="cff04-p105">搜索系统根据内容连接方式、项在搜索结果中的显示频率和获得单击的搜索结果来确定搜索结果的相关性。分析组件会跟踪和分析此类信息，并用来不断提高相关性。详细了解[分析处理](https://docs.microsoft.com/SharePoint/search/overview-of-analytics-processing)。</span><span class="sxs-lookup"><span data-stu-id="cff04-p105">The search system determines the relevance of search results in part by how content is connected, how often an item appears in search results, and which search results people click. The analytics component tracks and analyzes this information and uses it to continuously improve relevance. Learn more about [analytics processing](https://docs.microsoft.com/SharePoint/search/overview-of-analytics-processing).</span></span>
  
## <a name="expertise-search"></a><span data-ttu-id="cff04-128">Expertise Search</span><span class="sxs-lookup"><span data-stu-id="cff04-128">Expertise Search</span></span>
<span data-ttu-id="cff04-129"><a name="bkmk_ExpertiseSearch"> </a></span><span class="sxs-lookup"><span data-stu-id="cff04-129"></span></span>

<span data-ttu-id="cff04-p106">在 SharePoint 中，掌握人员垂直搜索的特定技能或专业知识，查找人员更容易。搜索结果的依据为用户在个人网站上输入的有关自己的元数据，以及已经创建的内容等信息。详细了解如何[更改垂直搜索设置](https://docs.microsoft.com/sharepoint/search/configure-properties-of-the-search-navigation-web-part)。</span><span class="sxs-lookup"><span data-stu-id="cff04-p106">In SharePoint, it is easier to find people with specific skills or expertise in the People Search vertical. The search results are based on information such as the metadata users have entered about themselves on their personal sites, and information from the content that they have created. Learn more about [changing search vertical settings](https://docs.microsoft.com/sharepoint/search/configure-properties-of-the-search-navigation-web-part).</span></span>
  
## <a name="graphical-refiners"></a><span data-ttu-id="cff04-133">Graphical refiners</span><span class="sxs-lookup"><span data-stu-id="cff04-133">Graphical refiners</span></span>
<span data-ttu-id="cff04-134"><a name="bkmk_GraphicalRefiners"> </a></span><span class="sxs-lookup"><span data-stu-id="cff04-134"></span></span>

<span data-ttu-id="cff04-p107">使用全新的图形精简条件，可以更直观地筛选搜索结果。详细了解如何[配置"精化"Web 部件](https://support.office.com/article/About-configuring-the-Refinement-Web-Part-7cef67e8-b992-4659-b21a-ba534eea102e)。</span><span class="sxs-lookup"><span data-stu-id="cff04-p107">The new graphical refiners provide a more visual way of filtering search results. Learn more about [configuring the Refinement Web Part](https://support.office.com/article/About-configuring-the-Refinement-Web-Part-7cef67e8-b992-4659-b21a-ba534eea102e).</span></span>
  
## <a name="hybrid-search"></a><span data-ttu-id="cff04-137">混合搜索</span><span class="sxs-lookup"><span data-stu-id="cff04-137">Hybrid search</span></span>
<span data-ttu-id="cff04-138"><a name="bkmk_HybridSearch"> </a></span><span class="sxs-lookup"><span data-stu-id="cff04-138"></span></span>

<span data-ttu-id="cff04-p108">在 SharePoint 混合部署中，搜索结果内容可源自 SharePoint Online 和 SharePoint Server 2013 本地网站。若要详细了解混合 SharePoint 环境，请参阅 [SharePoint Server 2013 的混合](https://docs.microsoft.com/SharePoint/hybrid/hybrid)。</span><span class="sxs-lookup"><span data-stu-id="cff04-p108">In a hybrid deployment of SharePoint, search result content can come from both SharePoint Online and SharePoint Server 2013 on-premises sites. To learn more about a hybrid SharePoint environment, see [Hybrid for SharePoint Server 2013](https://docs.microsoft.com/SharePoint/hybrid/hybrid).</span></span>
  
## <a name="manage-search-schema"></a><span data-ttu-id="cff04-141">管理搜索架构</span><span class="sxs-lookup"><span data-stu-id="cff04-141">Manage search schema</span></span>
<span data-ttu-id="cff04-142"><a name="bkmk_manage_search_schema"> </a></span><span class="sxs-lookup"><span data-stu-id="cff04-142"></span></span>

<span data-ttu-id="cff04-p109">当有人在 SharePoint 网站上搜索内容时，搜索索引决定了他们的搜索结果。搜索索引包含网站上所有文档和页面的信息，通过对 SharePoint 网站上的内容进行爬网而生成。搜索架构有助于爬网程序决定要选取的内容和元数据，以及如何编制索引。你可以通过更改搜索架构来为用户提供自定义的搜索体验。详细了解如何[在 SharePoint Online 中管理搜索架构](https://docs.microsoft.com/sharepoint/manage-search-schema)。</span><span class="sxs-lookup"><span data-stu-id="cff04-p109">When people search for content on your SharePoint sites, it's what's in your search index that determines what they'll find. The search index contains information from all documents and pages on your site and is built by crawling the content on your SharePoint site. The search schema helps the crawler decide what content and metadata to pick up and how to index it. By changing the search schema, you can create a customized search experience for your users. Learn more about [managing search schema in SharePoint Online](https://docs.microsoft.com/sharepoint/manage-search-schema).</span></span>
  
## <a name="on-hover-preview"></a><span data-ttu-id="cff04-148">悬停预览</span><span class="sxs-lookup"><span data-stu-id="cff04-148">On-hover preview</span></span>
<span data-ttu-id="cff04-149"><a name="bkmk_Quickpreview"> </a></span><span class="sxs-lookup"><span data-stu-id="cff04-149"></span></span>

<span data-ttu-id="cff04-p110">用户可以将指针悬停在搜索结果上，在结果右侧的悬停面板中预览文档或网站内容并与之交互。预览显示丰富的元数据，以及指向文档或网站的主要部分的深层链接。详细了解[搜索提示](https://support.office.com/article/Not-getting-the-search-results-you-re-looking-for-in-SharePoint-D80687F7-1010-4E6D-ADD9-584B423289D9)。</span><span class="sxs-lookup"><span data-stu-id="cff04-p110">Users can rest the pointer over a search result to preview and interact with the document or site content in the hover panel to the right of the result. The preview shows rich metadata and has deep links to the main sections of the document or site. Learn more [tips for searching](https://support.office.com/article/Not-getting-the-search-results-you-re-looking-for-in-SharePoint-D80687F7-1010-4E6D-ADD9-584B423289D9).</span></span>
  
## <a name="phonetic-name-matching"></a><span data-ttu-id="cff04-153">Phonetic name matching</span><span class="sxs-lookup"><span data-stu-id="cff04-153">Phonetic name matching</span></span>
<span data-ttu-id="cff04-154"><a name="bkmk_PhoneticNameMatching"> </a></span><span class="sxs-lookup"><span data-stu-id="cff04-154"></span></span>

<span data-ttu-id="cff04-p111">改进后的拼音名称匹配会在搜索结果中查找发音类似的名称（是 John 还是 Jon？）。详细了解如何[管理结果来源](https://docs.microsoft.com/sharepoint/manage-result-sources)。</span><span class="sxs-lookup"><span data-stu-id="cff04-p111">Improved phonetic name matching finds search results for similar sounding names (is it John or Jon?). Learn more about [managing result sources](https://docs.microsoft.com/sharepoint/manage-result-sources).</span></span>
  
## <a name="query-rulesadd-promoted-results"></a><span data-ttu-id="cff04-157">查询规则添加已升级结果</span><span class="sxs-lookup"><span data-stu-id="cff04-157">Query rules—add promoted results</span></span>
<span data-ttu-id="cff04-158"><a name="bkmk_QueryRulesAddpromotedresults"> </a></span><span class="sxs-lookup"><span data-stu-id="cff04-158"></span></span>

<span data-ttu-id="cff04-p112">在查询规则中，指定条件和相关操作。如果查询满足查询规则中的条件，搜索系统会执行规则中指定的操作。使用"添加已提升的结果"操作，可以提升各个结果，使其显示在搜索结果顶部。详细了解如何[管理查询规则](https://docs.microsoft.com/SharePoint/search/manage-query-rules)。</span><span class="sxs-lookup"><span data-stu-id="cff04-p112">In a query rule, specify conditions and correlated actions. When a query meets the conditions in a query rule, the search system performs the actions specified in the rule. The "Add promoted results" action lets you promote individual results so that they appear at the top of search results. Learn more about [managing query rules](https://docs.microsoft.com/SharePoint/search/manage-query-rules).</span></span>
  
## <a name="query-rulesadvanced-actions"></a><span data-ttu-id="cff04-163">Query rules—advanced actions</span><span class="sxs-lookup"><span data-stu-id="cff04-163">Query rules—advanced actions</span></span>
<span data-ttu-id="cff04-164"><a name="bkmk_UserRulesAdvancedActions"> </a></span><span class="sxs-lookup"><span data-stu-id="cff04-164"></span></span>

<span data-ttu-id="cff04-p113">在查询规则中，可以指定条件和相关操作。使用"添加结果块"操作，可以组的形式显示一部分搜索结果。使用"通过更改查询更改排名结果"操作，可以更改返回的搜索结果的排名。详细了解如何[管理查询规则](https://docs.microsoft.com/SharePoint/search/manage-query-rules)。</span><span class="sxs-lookup"><span data-stu-id="cff04-p113">In a query rule, you can specify conditions and correlated actions. The "Add result blocks" action lets you display a subset of the search results as a group. The "Change ranked results by changing the query" action lets you change the ranking of the returned search results. Learn more about [managing query rules](https://docs.microsoft.com/SharePoint/search/manage-query-rules).</span></span>
  
## <a name="query-spelling-correction"></a><span data-ttu-id="cff04-169">Query spelling correction</span><span class="sxs-lookup"><span data-stu-id="cff04-169">Query spelling correction</span></span>
<span data-ttu-id="cff04-170"><a name="bkmk_QuerySpellingCorrection"> </a></span><span class="sxs-lookup"><span data-stu-id="cff04-170"></span></span>

<span data-ttu-id="cff04-p114">编辑排除和包含列表，决定应在搜索结果页上显示哪些查询的备用查询拼写。此功能通常称为"您的意思是？"。详细了解[查询拼写更正](https://docs.microsoft.com/sharepoint/search/manage-query-spelling-correction)。</span><span class="sxs-lookup"><span data-stu-id="cff04-p114">Edit exclusions and inclusions lists to decide which queries the search results page should display alternative query spellings for. This feature is often called "Did you mean?". Learn more about [query spelling correction](https://docs.microsoft.com/sharepoint/search/manage-query-spelling-correction).</span></span>
  
## <a name="query-suggestions"></a><span data-ttu-id="cff04-174">查询建议</span><span class="sxs-lookup"><span data-stu-id="cff04-174">Query suggestions</span></span>
<span data-ttu-id="cff04-175"><a name="bkmk_Querysuggestions"> </a></span><span class="sxs-lookup"><span data-stu-id="cff04-175"></span></span>

<span data-ttu-id="cff04-p115">查询建议是用户已搜索过的建议短语。键入查询时，用户会在搜索框下的列表中看到查询建议。查询建议自动生成，同时短语可作为"始终建议"或"从不建议"查询建议添加到系统中。详细了解如何[管理查询建议](https://docs.microsoft.com/sharepoint/search/manage-query-suggestions)。</span><span class="sxs-lookup"><span data-stu-id="cff04-p115">Query suggestions are suggested phrases that users have already searched for. The suggestions appear in a list below the Search Box as a user types a query. Query suggestions are generated automatically, and phrases can be added to the system as "always" or "never" suggest. Learn more about [managing query suggestions](https://docs.microsoft.com/sharepoint/search/manage-query-suggestions).</span></span>
  
## <a name="ranking-models"></a><span data-ttu-id="cff04-180">分级模型</span><span class="sxs-lookup"><span data-stu-id="cff04-180">Ranking models</span></span>
<span data-ttu-id="cff04-181"><a name="bkmk_Ranking_Models"> </a></span><span class="sxs-lookup"><span data-stu-id="cff04-181"></span></span>

<span data-ttu-id="cff04-p116">SharePoint 使用排名模型向搜索结果分配值，以便最相关的项显示最靠前。排名模型是一组用于计算特定项的排名得分的排名因素。SharePoint Online 和 SharePoint Server 2013 包括多种无需进一步自定义就能提供有效排名的排名模型。然而，如果需要提高搜索结果与最终用户的相关性，可以自定义排名模型。使用排名模型优化应用，SharePoint Online 客户可以创建自定义排名模型。可以在此应用的用户界面上复制现有排名模型，判断一组查询的结果，然后添加或删除排名功能，并调整这些功能的权重，"优化"排名模型。详细了解如何[搜索结果排名](https://docs.microsoft.com/sharepoint/search/overview-of-search-result-ranking)。</span><span class="sxs-lookup"><span data-stu-id="cff04-p116">SharePoint uses ranking models to assign a value to search results so that the most relevant items appear first. A ranking model is a set of ranking factors that calculate the rank score of a particular item. Both SharePoint Online and SharePoint Server 2013 include several ranking models that provide effective rankings without any further customization. However, you can customize your ranking models if you need to make search results even more relevant to your end users. The Ranking Model Tuning App allows SharePoint Online customers to create a custom ranking model. The app provides a user interface to copy an existing ranking model, judge the results for a set of queries, and "tune" it by adding or removing rank features and adjusting the weight of those features. Learn more about [search result ranking](https://docs.microsoft.com/sharepoint/search/overview-of-search-result-ranking).</span></span>
  
## <a name="refiners"></a><span data-ttu-id="cff04-189">Refiners</span><span class="sxs-lookup"><span data-stu-id="cff04-189">Refiners</span></span>
<span data-ttu-id="cff04-190"><a name="bkmk_Refiners"> </a></span><span class="sxs-lookup"><span data-stu-id="cff04-190"></span></span>

<span data-ttu-id="cff04-p117">精简条件将 SharePoint Server 搜索结果中排名靠前的文档归入组中，以便用户可以筛选搜索结果。详细了解如何[配置"精简"Web 部件](https://support.office.com/article/About-configuring-the-Refinement-Web-Part-7cef67e8-b992-4659-b21a-ba534eea102e)。</span><span class="sxs-lookup"><span data-stu-id="cff04-p117">Refiners categorize the top documents in SharePoint Server search results into groups that let users filter the search results. Learn more about [configuring the Refinement Web Part](https://support.office.com/article/About-configuring-the-Refinement-Web-Part-7cef67e8-b992-4659-b21a-ba534eea102e).</span></span>
  
## <a name="restful-query-apiquery-om"></a><span data-ttu-id="cff04-193">RESTful Query API/Query OM</span><span class="sxs-lookup"><span data-stu-id="cff04-193">RESTful Query API/Query OM</span></span>
<span data-ttu-id="cff04-194"><a name="bkmk_RESTfulQueryAPI"> </a></span><span class="sxs-lookup"><span data-stu-id="cff04-194"></span></span>

<span data-ttu-id="cff04-p118">开发人员可以创建 .NET 代码以访问公共搜索对象模型。除了提交搜索查询之外，这还包括搜索管理操作。要与服务端对象模型进行交互，.NET 代码必须在农场的 Web 服务器上运行。可以使用客户端对象模型 (CSOM)，从远程计算机访问对象模式的子集。可以使用基于 REST 的 Web 服务或 oData 访问客户端对象模型 (CSOM) 的功能。这允许开发人员使用流行的 Web 开发工具提交查询给 SharePoint Server 2013 农场。</span><span class="sxs-lookup"><span data-stu-id="cff04-p118">Developers can create .NET code to access the public search object model. This includes search administration operations in addition to submitting search queries. To interact with the service side object model, the .NET code must run on a web server in the farm. A sub-set of the object mode can be accessed from a remote computer by using the Client Side Object Model (CSOM). Features of the Client Side Object model (CSOM) can be accessed by using a REST-based web service or oData. This allows developers to submit queries to the SharePoint Server 2013 farm using popular web development tools.</span></span>
  
## <a name="search-results-sorting"></a><span data-ttu-id="cff04-201">Search results sorting</span><span class="sxs-lookup"><span data-stu-id="cff04-201">Search results sorting</span></span>
<span data-ttu-id="cff04-202"><a name="bkmk_Searchresultssorting"> </a></span><span class="sxs-lookup"><span data-stu-id="cff04-202"></span></span>

<span data-ttu-id="cff04-p119">用户可以选择按不同的条件（例如，相关性、新鲜度和社会距离（人员姓名））对搜索结果进行排序。详细了解[搜索结果排序](https://support.office.com/article/change-settings-for-the-search-results-web-part-40ff85b3-bc5e-4230-b1dd-f088188e487e)。</span><span class="sxs-lookup"><span data-stu-id="cff04-p119">Users can choose to sort search results by different criteria, for example relevance, freshness, and social distance (people names). Learn more about [search results sorting](https://support.office.com/article/change-settings-for-the-search-results-web-part-40ff85b3-bc5e-4230-b1dd-f088188e487e).</span></span>
  
## <a name="this-list-searches"></a><span data-ttu-id="cff04-205">"此列表"搜索</span><span class="sxs-lookup"><span data-stu-id="cff04-205">"This List" searches</span></span>
<span data-ttu-id="cff04-206"><a name="bkmk_ThisListSearches"> </a></span><span class="sxs-lookup"><span data-stu-id="cff04-206"></span></span>

<span data-ttu-id="cff04-p120">在 SharePoint Online 和 SharePoint Server 2013 中，可将搜索限制在执行搜索的列表或库中。在 SharePoint Foundation 2013 中，搜索将返回存在于执行搜索的网站或网站下面的所有列表和库中的结果。</span><span class="sxs-lookup"><span data-stu-id="cff04-p120">In SharePoint Online and SharePoint Server 2013, a search can be limited to the list or library where the search is performed. In SharePoint Foundation 2013, a search will return results from all lists and libraries that exist at or below the site where the search is performed.</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="cff04-209">功能可用性</span><span class="sxs-lookup"><span data-stu-id="cff04-209">Feature Availability</span></span>
<span data-ttu-id="cff04-210"><a name="bkmk_ThisListSearches"> </a></span><span class="sxs-lookup"><span data-stu-id="cff04-210"></span></span>

<span data-ttu-id="cff04-211">若要查看在各个 Office 365 计划、独立选项和内部部署解决方案之间的功能可用性，请参阅 [SharePoint Online 服务说明](sharepoint-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="cff04-211">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [SharePoint Online Service Description](sharepoint-online-service-description.md).</span></span>
  

