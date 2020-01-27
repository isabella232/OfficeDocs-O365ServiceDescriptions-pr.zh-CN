---
title: SharePoint Online 限制
ms.author: sharik
author: skjerland
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: 查找适用于 Office 365 企业版计划和独立计划的 SharePoint Online 限制。
ms.openlocfilehash: b5ba34d3a1ebd80d7833e09e70a76b57882ae6fd
ms.sourcegitcommit: 81ba764537d6bfb99fe6f96cdbd0c0ac1534cae1
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 01/24/2020
ms.locfileid: "41519193"
---
# <a name="sharepoint-online-limits"></a>SharePoint Online 限制

查找适用于 Office 365 计划和 SharePoint Online 独立计划的 SharePoint 限制。
  
## <a name="limits-by-plan"></a>按计划限制 

|||||
|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 业务重点或商业高级版** <br/> |**Office 365 企业版 E1、E3 或 E5 或 SharePoint Online 计划1或2** <br/> | **Office 365 企业版 F1** <br/> |
|每个组织的总存储量<sup>1、2、6</sup> <br/> |1 TB 加上购买的每个许可证 10 GB  <br/> |1 TB 再加上每个购买的 10 GB 的许可证<sup>3</sup> <br/> |1 TB<sup>3</sup> <br/> |
|每个网站集4的最大存储量<sup>4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB<sup>5</sup> <br/> |
|每个组织的网站集  <br/> |2000000<sup>6</sup> <br/> |2000000<sup>6</sup> <br/> |2000000<br/> |
|用户数  <br/> |最高为300  <br/> |1-500000<sup>7</sup> <br/> |1-500000<sup>7</sup> <br/> |
   
<sup>1</sup> [了解如何查找组织的总存储空间和可用存储空间](/sharepoint/manage-site-collection-storage-limits)。 您可以购买不受限制的额外 SharePoint 存储空间。 请参阅[更改订阅的存储空间](/office365/admin/subscriptions-and-billing/add-storage-space)。 
<br/><sup>2</sup>我们建议您对回收站进行监视并定期清空该回收站。 它使用的存储空间是组织总存储限制的一部分。 
<br/> <sup>3</sup>如果你有 office 365 订阅和 Office 365 额外文件存储加载项，则会添加存储量。 
<br/> <sup>4</sup>这是单个网站集的存储限制，而不是为每个网站集提供的存储量。 此限制适用于所有类型的网站集，包括 Office 365 组连接的团队网站和 OneDrive。 SharePoint 管理员可以[手动设置较低的存储限制](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits)。 
<br/> <sup>5</sup> Firstline 工作线程无法管理 SharePoint 网站集。 
<br/> <sup>6</sup>不包含为每个许可的用户创建的 OneDrive。 
<br/> <sup>7</sup>如果用户数超过500000，请与 Microsoft 代表联系。 
  
## <a name="service-limits-for-all-plans"></a>所有计划的服务限制

- 列表**和库中的项**-列表最多可包含30000000个项，库最多可以包含30000000个文件和文件夹。 将100000项添加到列表、库或文件夹后，不能更改列表、库或文件夹的权限继承。 若要详细了解查看大型列表的其他限制，请参阅[管理大型列表和库在 Office 365 中](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784)。 

- **文件大小和文件路径长度**-15 GB。 附加到列表项的文件的最大大小为 250 MB。 若要了解有关使用新的 OneDrive 同步客户端（OneDrive）时的限制和限制的详细信息，请参阅[无效文件名和文件类型](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)。

- **跨网站集移动和复制**–每个操作 100 GB。 Web 浏览器必须保持打开状态。

- **同步**-为了获得最佳性能，建议在所有同步的文档库中存储不超过300000个文件，即使您按需使用文件或仅选择库中的某些文件夹进行同步也是如此。

    如果使用以前的 OneDrive for Business 同步客户端（Groove），则最多可以同步所有同步的库中的全部20000个项目。 这包括 OneDrive for business 库和/或工作组网站库。 与整体同步限制分开，可为每个库类型同步的项目数有限制：
    - 你最长可同步 OneDrive for Business 库中的20000个项目。 其中包括文件夹和文件。 
    - 您可以同步 SharePoint 库中的最大为5000项。 其中包括文件夹和文件。 这些库是在各种 SharePoint 网站上找到的库，如工作组网站和社区网站、其他人创建的库或您通过网站页面创建的库。 您可以同步多个 SharePoint 库。 您同步的任何工作组网站也会在所有同步的库中计算出全部20000项目限制。

    > [!NOTE]
    > 如果用户需要同步具有成百上千个文件的文档库中的文件，则可以通过将文件夹的权限级别设置为 "限制读取" 来从同步客户端中 "隐藏" 文件夹。 

- **版本**-50000 主要版本和511次要版本。

- **SharePoint 组**-用户可以属于5000组，每个组最长可有5000个用户。 每个网站集最多可有 10,000 个组。
    > [!NOTE]
    > 对于 Azure AD 组限制，请参阅[AZURE ad 服务限制和限制](https://docs.microsoft.com/azure/active-directory/users-groups-roles/directory-service-limits-restrictions)，因为这种限制可能会影响公用和专用组站点成员身份管理。 
- **托管元数据**-200000 术语在术语库中，1000全局术语集，1000组。

- **子网站**-每个网站集2000。

- **SharePoint 承载的应用程序**-每个组织的20000实例。

- **每个列表或库的唯一安全作用域**-支持的限制为50000，但建议的常规限制为5000。 在5000以上，访问控制列表（ACL）大小从开始到很重要。 虽然您可以将作用域添加到支持的限制为50000，但 Microsoft 不建议这样做，除非您有一个非常具体的方案需要注意。 对于大型列表，设计应具有尽可能少的唯一权限。

- **用户**-每个网站集2000000。
    > [!NOTE]
    > 您可以邀请到 SharePoint 网站集的来宾数没有限制。 有关外部共享的详细信息，请参阅[external 共享概述](https://docs.microsoft.com/sharepoint/external-sharing-overview)。
## <a name="see-also"></a>另请参阅

[SharePoint Online 的搜索限制](https://docs.microsoft.com/sharepoint/search-limits)
