---
title: SharePoint Syntex 功能
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
description: 了解符合条件的 SharePoint Syntex、Microsoft 365、Office 365 和 SharePoint Online 计划中提供的主要SharePoint功能。
ms.openlocfilehash: 7febd3615d61fd2aa219ea8a5075f0d591fe41df5a179a8ca2f2f0d74007f5e7
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/06/2021
ms.locfileid: "54702521"
---
# <a name="sharepoint-syntex-features"></a>SharePoint Syntex 功能 

以下各节介绍符合条件的[](sharepoint-syntex-service-description.md)SharePoint Syntex、Microsoft 365、Office 365 和 SharePoint Online 计划中提供的主要SharePoint功能。 可用功能可能会更改，无需另行通知。 有关最新、完整的功能列表，请参阅SharePoint Syntex[计划和定价页面](https://www.microsoft.com/microsoft-365/enterprise/sharepoint-syntex)。

## <a name="syntex-content-center"></a>合成内容中心

Syntex 提供了一个称为内容中心的网站模板，用于大规模管理内容、集成元数据和工作流以及 &mdash;  &mdash; 提供合规性自动化。 内容中心提供的功能可以指导云如何以手动方式读取和处理文档。 Syntex 使用这些见解自动识别内容、提取重要信息并应用元数据标记。 此外，您还可以使用集成的可视化分析跟踪模型的有效性。

若要了解有关内容中心以及如何创建它们，[请参阅在内容](/microsoft-365/contentunderstanding/create-a-content-center)中心SharePoint Syntex。

## <a name="object-recognition"></a>对象识别

Syntex 可以使用包含成千上万个常见识别对象的新视觉字典自动标记图像。 此外，Syntex 可以识别手写文本并将其转换为标记，供搜索和进一步处理使用。

若要了解有关 Syntex 中的对象识别以及如何配置图像标记的更多信息，请参阅图像标记[SharePoint Syntex。](/microsoft-365/contentunderstanding/image-tagging)

## <a name="document-understanding"></a>文档理解

你可以指导 Syntex 以使用计算机教学的方式读取内容，以使用无代码 (AI) 构建人工智能。 Syntex 可以自动建议或创建元数据、调用自定义Power Automate工作流以及附加合规性标签以强制执行保留或记录管理策略。

文档了解模型基于语言了解 Azure 认知服务中的模型。 这些模型是在 Syntex 内容中心中创建和管理的，你可以在整个 Syntex 中将模型发布并更新到任何内容中心中的库。

若要详细了解文档理解，请参阅文档 [理解概述](/microsoft-365/contentunderstanding/document-understanding-overview)。

## <a name="form-processing"></a>表单处理

Syntex 包括基于 AI 生成器的强大表单处理引擎，可让你自动识别和提取半结构化或结构化文档（如日期、图表、名称或地址）中的常见值。 这些模型无需代码即可生成，并且只需要几个文档即可获得可靠结果。

若要详细了解表单处理，请参阅 [表单处理概述](/microsoft-365/contentunderstanding/form-processing-overview)。

## <a name="microsoft-graph-content-connectors"></a>Microsoft Graph内容连接器

Syntex 使用 Microsoft Graph 连接器将文件共享、Azure SQL 或第三方源（如 Box 和 IBM FileNet）集成到 Microsoft Graph 中，使其在整个 Microsoft 365 中可搜索 &mdash; &mdash; 和可用。

使用 Microsoft Graph连接器，客户可以索引外部存储库中的项目，以包含在Microsoft 搜索结果中。 Microsoft 365 E5和 Office 365 E5包括使用 Microsoft Graph 连接器为 A5 Microsoft 搜索 (未包含的最多 500 个项目编制) 。 具有套件或独立许可证（包括 SharePoint 或 OneDrive 计划）的任何用户都可以看到来自 Microsoft Graph 连接器的搜索结果Microsoft 搜索。

目前，Microsoft 或我们的一个合作伙伴提供了超过 130 个源的连接器。 若要了解更多信息，请参阅[Microsoft Graph连接器概述](/MicrosoftSearch/connectors-overview)。

## <a name="advanced-taxonomy-services"></a>高级分类服务

Syntex 包括一些功能，可让你在整个生命周期中观看和分析Microsoft 365。 这些报告在管理SharePoint中提供。

可以将共享内容类型发布到网站SharePoint，Microsoft Teams中心SharePoint[发布共享内容类型](/sharepoint/dev/features/hub-site/hub-site-overview)。 将内容类型从中央库发布到中心网站提供了一种更为灵活的方法，以确保根据需要跨体系结构的广泛部分快速部署和升级常用内容类型（通过了解内容而增强）。 连接到中心的网站将自动接收已发布和更新的内容类型。