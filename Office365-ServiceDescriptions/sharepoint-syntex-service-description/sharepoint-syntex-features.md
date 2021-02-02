---
title: SharePoint 合成功能
ms.author: office365servicedesc
author: pamelaar
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
description: 了解符合条件的 Microsoft 365、Office 365 和 SharePoint Online 计划中提供的主要 SharePoint 合成器功能。
ms.openlocfilehash: 998443a635b7816705553374d8a029f37a669fe0
ms.sourcegitcommit: 68b900488bafad6be4b7216f5a8c5899f159707f
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 02/02/2021
ms.locfileid: "50072428"
---
# <a name="sharepoint-syntex-features"></a>SharePoint 合成功能 

以下各节介绍符合条件的[](sharepoint-syntex-service-description.md)Microsoft 365、Office 365 和 SharePoint Online 计划中提供的主要 SharePoint 合成功能。 可用功能可能会更改，无需通知。 有关最新、完整的功能列表，请参阅 [SharePoint 整合计划和定价页](https://www.microsoft.com/microsoft-365/enterprise/sharepoint-syntex)。

## <a name="syntex-content-center"></a>合成内容中心

Syntex 提供了一个称为内容中心的网站模板，用于大规模管理内容、集成元数据和 &mdash;  &mdash; 工作流以及提供合规性自动化。 内容中心提供的功能可以指导云如何以手动方式读取和处理文档。 Syntex 使用这些见解自动识别内容、提取重要信息并应用元数据标记。 此外，您还可以使用集成的可视化分析跟踪模型的有效性。

若要了解有关内容中心以及如何创建它们，请参阅在 [SharePoint Syntex 中](/microsoft-365/contentunderstanding/create-a-content-center)创建内容中心。

## <a name="object-recognition"></a>对象识别

通过使用包含成千上万个常用对象的新视觉字典，合成可以自动标记图像。 此外，Syntex 还可以识别手写文本并将其转换为标记，供搜索和进一步处理使用。

若要了解有关 Syntex 中的对象识别以及如何配置图像标记，请参阅 [SharePoint Syntex 中的图像标记](/microsoft-365/contentunderstanding/image-tagging)。

## <a name="document-understanding"></a>文档理解

你可以教 Syntex 以读取内容的方式使用计算机教学来构建没有代码的 AI (AI) 模型。 Syntex 可以自动建议或创建元数据，调用自定义 Power Automate 工作流，并附加合规性标签以强制实施保留或记录管理策略。

文档了解模型基于 Azure 认知服务中的语言理解模型。 这些模型是在 Syntex 内容中心中创建和管理的，你可以在整个 Syntex 中将模型发布并更新到任何内容中心的任何库。

若要了解有关文档理解的信息，请参阅"[文档理解概述"。](/microsoft-365/contentunderstanding/document-understanding-overview)

## <a name="form-processing"></a>表单处理

Syntex 包括一个基于 AI Builder 的强大表单处理引擎，可用于自动识别和提取半结构化或结构化文档（如日期、图表、名称或地址）中的通用值。 这些模型无需代码即可生成，并且只需要几个文档即可获得可靠结果。

若要详细了解表单处理，请参阅["表单处理概述"。](/microsoft-365/contentunderstanding/form-processing-overview)

## <a name="microsoft-graph-content-connectors"></a>Microsoft Graph 内容连接器

Syntex 使用 Microsoft Graph 连接器将文件共享、Azure SQL 或第三方源（如 Box 和 IBM FileNet）集成到 Microsoft Graph 中，使其在整个 &mdash; Microsoft 365 中可搜索和可用。 &mdash;

使用 Microsoft Graph 连接器，客户可以索引外部存储库中的项目，以包含在 Microsoft 搜索结果中。 Microsoft 365 E5 和 Office 365 E5 包括使用 Microsoft 搜索服务 Microsoft Graph 连接器对最多 500 个项目编制索引 (A5) 。 具有包括 SharePoint 或 OneDrive 计划的套件或独立许可证的任何用户都可以查看来自 Microsoft 搜索的 Microsoft Graph 连接器的搜索结果。

现在，Microsoft 或我们的合作伙伴之一提供了超过 130 个源的连接器。 若要了解更多信息，请参阅 [Microsoft Graph 连接器概述](https://aka.ms/iwantconnectors)。

## <a name="advanced-taxonomy-services"></a>高级分类服务

Syntex 包括一些功能，可让你在整个 Microsoft 365 中观看和分析术语创建和使用。 这些报告在 SharePoint 管理中心中提供。

可通过 SharePoint 中心网站将共享内容类型发布到 [SharePoint 和](/sharepoint/dev/features/hub-site/hub-site-overview)Microsoft Teams。 将内容类型从中央库发布到中心网站提供了一种更为灵活的方法，以确保根据需要，可跨体系结构的广泛部分快速部署和升级常用内容类型（通过内容理解增强）。 连接到中心的网站将自动接收已发布和更新的内容类型。
