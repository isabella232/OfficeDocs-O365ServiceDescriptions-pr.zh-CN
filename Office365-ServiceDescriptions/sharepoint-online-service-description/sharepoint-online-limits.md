---
title: SharePoint 限制
ms.author: sharik
author: skjerland
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: 了解 Office 365 和独立计划的 SharePoint 限制。
ms.openlocfilehash: 03cf3a792bb88d1a6c6d6048752fe2caaf695f35
ms.sourcegitcommit: 06d43eca33da7d747494beaa9847e98b99367b0d
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 02/26/2020
ms.locfileid: "42279865"
---
# <a name="sharepoint-limits"></a>SharePoint 限制

了解 SharePoint for Microsoft 365 中的服务限制。
  
## <a name="limits-by-plan"></a>按计划限制 

|||||
|:-----|:-----|:-----|:-----|
|**功能** <br/> |**Office 365 业务重点或商业高级版** <br/> |**Office 365 企业版 E1、E3 或 E5 或 SharePoint 计划1或2** <br/> | **Office 365 企业版 F1** <br/> |
|每个组织的总存储量<sup>1、2、6</sup> <br/> |1 TB 加上购买的每个许可证 10 GB  <br/> |1 TB 再加上每个购买的 10 GB 的许可证<sup>3</sup> <br/> |1 TB<sup>3</sup> <br/> |
|每个站点的最大存储（网站集）<sup>4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB<sup>5</sup> <br/> |
|每个组织的网站（网站集）  <br/> |2000000<sup>6</sup> <br/> |2000000<sup>6</sup> <br/> |2000000<br/> |
|用户数  <br/> |最高为300  <br/> |1-500000<sup>7</sup> <br/> |1-500000<sup>7</sup> <br/> |
   
<sup>1</sup> [了解如何查找组织的总存储空间和可用存储空间](/sharepoint/manage-site-collection-storage-limits)。 您可以购买不受限制的额外 SharePoint 存储空间。 请参阅[更改订阅的存储空间](/office365/admin/subscriptions-and-billing/add-storage-space)。 
<br/><sup>2</sup>我们建议您对回收站进行监视并定期清空该回收站。 它使用的存储空间是组织总存储限制的一部分。 
<br/> <sup>3</sup>如果你有 office 365 订阅和 Office 365 额外文件存储加载项，则会添加存储量。 
<br/> <sup>4</sup>这是单个网站（之前称为 "网站集"）的存储*限制*，而不是为每个网站*提供*的存储量。 此限制适用于所有类型的网站，包括 Office 365 组连接的团队网站和 OneDrive。 SharePoint 管理员可以[手动设置较低的存储限制](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits)。 
<br/> <sup>5</sup> Firstline 工作线程无法管理 SharePoint 网站。 
<br/> <sup>6</sup>不包含为每个许可的用户创建的 OneDrive。 
<br/> <sup>7</sup>如果用户数超过500000，请与 Microsoft 代表联系。 
  
## <a name="service-limits-for-all-plans"></a>所有计划的服务限制

### <a name="items-in-lists-and-libraries"></a>列表和库中的项

一个列表最多可以包含30000000个项目，一个库最多可以包含30000000个文件和文件夹。 如果列表、库或文件夹包含的项目超过100000个，则不能断开对列表、库或文件夹的权限继承。 也不能对其重新继承权限。 但是，您仍可以对该列表、库或文件夹中的单个项目（最多为列表或库中的唯一权限数）断开继承（请参阅下一节）。 若要详细了解查看大型列表的其他限制，请参阅[管理大型列表和库在 Office 365 中](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784)。 

> [!NOTE]
> 对网站上可以拥有的文档库的数量没有限制。

### <a name="unique-permissions-for-items-in-a-list-or-library"></a>对列表或库中的项目的独有权限

支持的限制为50000，但建议的常规限制为5000。 一次对超过5000个唯一具有独特权限的项目进行更改会花费更长时间。 对于大型列表，设计应具有尽可能少的唯一权限。

### <a name="file-size-and-file-path-length"></a>文件大小和文件路径长度

15 GB。 附加到列表项的文件的最大大小为 250 MB。 若要了解有关使用新 OneDrive 同步应用（OneDrive）时的限制和限制的详细信息，请参阅[无效文件名和文件类型](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)。

### <a name="moving-and-copying-across-sites"></a>跨网站移动和复制

每个操作 100 GB。 Web 浏览器必须保持打开状态。

### <a name="sync"></a>同步

**新建 OneDrive 同步应用**-为了获得最佳性能，建议在所有已同步的文档库中存储不超过300000个文件，即使您按需使用文件或仅选择库中的某些文件夹进行同步也是如此。

**以前的 OneDrive For business 同步应用（Groove）** -最多可同步所有同步的库中的全部20000个项目。 这包括 OneDrive 库和/或工作组网站库。 与整体同步限制分开，可为每个库类型同步的项目数有限制：

   - 你最长可同步 OneDrive 库中的20000个项目。 其中包括文件夹和文件。 
   - 您可以同步 SharePoint 库中的最大为5000项。 其中包括文件夹和文件。 这些库是在各种 SharePoint 网站上找到的库，如工作组网站和社区网站、其他人创建的库或您通过网站页面创建的库。 您可以同步多个 SharePoint 库。 您同步的任何工作组网站也会在所有同步的库中计算出全部20000项目限制。

> [!NOTE]
> 如果用户需要同步具有成百上千个文件的文档库中的文件，则可以通过将文件夹的权限级别设置为 "限制读取" 来 "隐藏" 文件夹中的文件夹。 

### <a name="versions"></a>版本

50000主要版本和511次要版本。

### <a name="sharepoint-groups"></a>SharePoint 组数

一个用户可以属于5000个组，每个组最长可有5000个用户。 每个站点（网站集）最高可达10000个组。

> [!NOTE]
> 对于 Azure AD 组限制，请参阅[AZURE ad 服务限制和限制](/azure/active-directory/users-groups-roles/directory-service-limits-restrictions)，因为这种限制可能会影响公用和专用组站点成员身份管理。 

### <a name="managed-metadata"></a>托管元数据

200000术语库中的术语，1000全局术语集，1000组。

### <a name="subsites"></a>出错 

每个站点2000（网站集）。 我们建议创建网站并将其组织到中心，而不是创建子网站。 如果您使用子网站，我们建议限制它们的号码（尤其是在大量流量网站上）。

### <a name="sharepoint-hosted-applications"></a>SharePoint 承载的应用程序

每个组织的20000实例。

### <a name="people-editing-a-document-at-the-same-time"></a>同时编辑文档的人

99用户可以同时打开文档进行编辑。 如果有10人以上的用户同时编辑一个文档，则他们的编辑更有可能会发生冲突，用户体验将逐渐降低。

### <a name="users"></a>用户

每个站点2000000（网站集）。
   
> [!NOTE]
> 对可邀请到 SharePoint 网站的来宾数没有限制。 有关外部共享的详细信息，请参阅[external 共享概述](/sharepoint/external-sharing-overview)。

## <a name="see-also"></a>另请参阅

[SharePoint 的搜索限制](/sharepoint/search-limits)
