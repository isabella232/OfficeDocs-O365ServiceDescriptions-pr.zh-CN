---
title: SharePoint Online 限制
ms.author: sharik
author: skjerland
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: 查找适用于 Office 365 企业版计划和独立计划的 SharePoint Online 限制。
ms.openlocfilehash: c1b6185c46be6f1343e6679a5b887bab5b393708
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/07/2019
ms.locfileid: "30467869"
---
# <a name="sharepoint-online-limits"></a>SharePoint Online 限制

查找适用于 Office 365 计划和 sharepoint Online 独立计划的 SharePoint 限制。
  
## <a name="limits-by-plan"></a>按计划限制

|||||
|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 业务重点或商业高级版** <br/> |**Office 365 企业版 E1、E3 或 E5 或 SharePoint Online 计划1或2** <br/> | **Office 365 企业版 F1** <br/> |
|存储<sup>1、2</sup> <br/> |每个组织 1 TB 加上购买的每个许可证 10 GB  <br/> |每个组织 1 TB 加上购买了 10 GB 的许可证<sup>3</sup> <br/> |每个组织 1 TB <sup>3</sup> <br/> |
|网站集的存储  <br/> |每个网站集或组<sup>4</sup>最高 25 TB <br/> |每个网站集或组<sup>4</sup>最高 25 TB <br/> |每个网站集或组<sup>5</sup>最高 25 TB <br/> |
|每个组织的网站集  <br/> |500000<sup>6</sup> <br/> |500000<sup>6</sup> <br/> |500,000<br/> |
|用户数  <br/> |最高为300  <br/> |1-500000<sup>7</sup> <br/> |1-500000<sup>7</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup>您可以购买无限制的额外 SharePoint Online 存储空间。 请参阅[更改订阅的存储空间](https://support.office.com/article/96EA3533-DE64-4B01-839A-C560875A662C)。 
<br/><sup>2</sup>我们建议您对回收站进行监视并定期清空该回收站。 The storage space it uses is part of the organization's total file storage limit. 
<br/> <sup>3</sup>当你具有 Office 365 订阅和 SharePoint Online 独立计划时, 将添加存储量。 
<br/><sup>4</sup> SharePoint Online 管理员可以设置网站集和网站的存储限制。
<br/> <sup>5</sup>展台工作线程无法管理 SharePoint Online 网站集。 您至少需要一个企业用户许可证来管理展台网站集。 
<br/> <sup>6</sup>不包含为每个许可的用户创建的 OneDrive for business 网站集。 
<br/><sup>7</sup>如果用户数超过 500000, 请与 Microsoft 代表联系。 
  

  
## <a name="service-limits-for-all-plans"></a>所有计划的服务限制

- 列表**和库中的项**-列表最多可包含30000000个项, 库最多可以包含30000000个文件和文件夹。 视图最多可具有 12 个查找列。 若要详细了解查看大型列表的其他限制，请参阅[管理大型列表和库在 Office 365 中](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784)。 有关在文件名中不能使用的字符的信息, 请参阅[file 和 folder names 中的无效字符](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)。

- **文件大小和文件路径长度**-15 GB。 若要了解有关使用新的 OneDrive 同步客户端 (OneDrive) 时的限制和限制的详细信息, 请参阅[onedrive、onedrive for business 和 SharePoint 中的无效文件名和文件类型](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)。

- **跨网站集移动和复制**–每个操作 100 GB。 web 浏览器必须保持打开状态。

- **同步**-若要获得最佳性能, 建议在单个 OneDrive 或工作组网站库中存储不超过300000个文件。 尽管 SharePoint Online 可以将30000000文档存储在每个库中, 但为了获得最佳性能, 建议在所有文档库中同步不超过300000个文件。 此外, 如果要同步的所有库中有300000个或更多的项目, 也可能会出现相同的性能问题, 即使您不同步这些库中的所有项目。 如果使用以前的 OneDrive for business 同步客户端 (Groove), 则每个库的同步限制为20000个项目 (包括每个团队网站的5000个项目)。

- **版本**-50000 主要版本和511次要版本。

- **SharePoint 组**-用户可以属于5000组, 每个组最长可有5000个用户。 每个网站集最多可有 10,000 个组。

- **托管元数据**-200000 术语在术语库中, 1000 全局术语集, 1000 组。

- **子网站**-每个网站集最高为2000。

- **SharePoint 承载的应用程序**-每个组织的20000实例。

- **每个列表或库的唯一安全作用域**-5000。 对于大型列表, 设计应具有尽可能少的唯一权限。

- **用户**-每个网站集2000000。

> [!NOTE]
> [!注意] 可邀请加入 SharePoint Online 网站集的外部用户数量不受限制。有关详细信息，请参阅[管理您的 SharePoint Online 环境的外部共享](/sharepoint/external-sharing-overview)。

## <a name="see-also"></a>另请参阅

[SharePoint Online 的搜索限制](/sharepoint/search-limits)