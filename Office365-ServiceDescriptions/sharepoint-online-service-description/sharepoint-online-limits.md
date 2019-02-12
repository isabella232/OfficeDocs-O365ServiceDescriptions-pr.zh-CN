---
title: SharePoint Online 限制
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: 查找 SharePoint Online 限制，Office 365 企业版计划和独立计划。
ms.openlocfilehash: 9d960aa50bef0b200fef2afe63ac1732cf201582
ms.sourcegitcommit: 30a452b9b9a0d8fc288e5911235454cc8f1907be
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 02/12/2019
ms.locfileid: "25848687"
---
# <a name="sharepoint-online-limits"></a>SharePoint Online 限制

查找 Office 365 计划和 SharePoint Online 独立计划的 SharePoint 限制。
  
## <a name="limits-by-plan"></a>按计划的限制

|||||
|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 业务 Essentials 或企业高级版** <br/> |**Office 365 企业版 E1、 E3 或 E5 或 SharePoint Online 计划 1 或 2** <br/> | **Office 365 企业版 F1** <br/> |
|存储<sup>1、 2</sup> <br/> |1 TB 每个组织以及每个许可证购买 10 GB  <br/> |每个组织的 1 TB 加上 10 GB 每个许可证购买<sup>3</sup> <br/> |1 TB / 组织<sup>3</sup> <br/> |
|网站集的存储  <br/> |设置到 25 TB / 网站集或组<sup>4</sup> <br/> |设置到 25 TB / 网站集或组<sup>4</sup> <br/> |设置到 25 TB / 网站集或组<sup>5</sup> <br/> |
|每个组织的网站集  <br/> |500000<sup>6</sup> <br/> |500000<sup>6</sup> <br/> |500,000<br/> |
|用户数  <br/> |最多 300  <br/> |1-500000<sup>7</sup> <br/> |1-500000<sup>7</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup>您可以购买其他 SharePoint Online 存储无限的的量。请参阅[更改为您的订阅的存储空间](https://support.office.com/article/96EA3533-DE64-4B01-839A-C560875A662C)。<br/><sup>2</sup>建议监视回收站并定期清空。它使用的存储空间属于组织的总文件存储限制。<br/> <sup>3</sup>后的 Office 365 订阅和 SharePoint Online 独立计划的操作之后，将添加存储量。<br/><sup>4</sup> SharePoint Online 管理员可以设置网站集和网站的存储限制。<br/> <sup>5</sup>网亭工作者无法管理 SharePoint Online 网站集。需要至少一个企业用户许可证管理网亭网站集。<br/> <sup>6</sup>不包括 OneDrive for Business 的每个许可用户创建的网站集。<br/><sup>7</sup>如果您有 500000 多个用户，请与 Microsoft 代表联系。 
  

  
## <a name="service-limits-for-all-plans"></a>对于所有计划 Service 限制

- **列表和库中的项目**的列表可以具有最多 30 万个项目，它库可以最多 30 万个文件和文件夹。视图可以具有多达 12 个查阅列。若要了解有关查看大型列表的其他限制的详细信息，请参阅[管理大型列表和 Office 365 中的库](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784)。有关无法使用文件名中的字符的信息，请参阅[文件和文件夹名称中的无效字符](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)。

- **文件大小和文件路径长度**-15 GB。若要使用新 OneDrive 同步客户端 (OneDrive.exe) 时，请了解有关限制和限制的详细信息，请参阅[无效的文件的名称和 OneDrive，OneDrive for Business 和 SharePoint 中的文件类型](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)。

- **同步**— 以获得最佳性能，我们建议将不能超过 300000 文件存储在单个 OneDrive 或团队网站库。虽然 SharePoint Online 可以存储每个库 30 万个文档，以获得最佳性能建议跨所有文档库同步不超过 300000 文件。此外，如果您有 300000 项或多跨所有库正在同步，即使不同步这些库中的所有项目，可能出现的相同的性能问题。如果您使用以前的 OneDrive for Business 同步客户端 (Groove.exe) 时，每个库的同步限制为 20,000 项 （包括每个工作组网站 5,000 项）。

- **版本**-50,000 的主要版本和 511 次要版本。

- **SharePoint 组**-用户可以属于 5,000 组，并且每个组可以具有多达 5,000 名用户。您可以每个网站集的最多 10,000 组。

- **托管元数据**-200000 术语库，1,000 全局术语集，1000 组中的条款。

- **子网站**的最多 2,000 个每个网站集。

- **SharePoint 托管应用程序**的每个组织的 20,000 实例。

- **每个列表或库的唯一安全作用域**-5000。对于大型列表设计尽可能具有尽可能少的唯一权限。

- **用户**的每个网站集 200 万个。

> [!NOTE]
> [!注意] 可邀请加入 SharePoint Online 网站集的外部用户数量不受限制。有关详细信息，请参阅[管理您的 SharePoint Online 环境的外部共享](/sharepoint/external-sharing-overview)。

## <a name="see-also"></a>另请参阅

[SharePoint online 搜索限制](/sharepoint/search-limits)