---
title: SharePoint 限制
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: 了解 Microsoft 365 和独立计划的 SharePoint 限制。
ms.openlocfilehash: 5dd9a0d414c5b5ddaac1d92254b73660fab0ac4725dbe656868df8889faa674d
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/06/2021
ms.locfileid: "54702601"
---
# <a name="sharepoint-limits"></a>SharePoint 限制

了解 SharePoint for Microsoft 365 中的服务限制。
  
## <a name="limits-by-plan"></a>按计划确定限制 

| 功能 | Microsoft 365 商业基础版、商业标准版或商业高级版 | Microsoft 365 E3 或 E5、Office 365 E1、E3 或 E5、或 SharePoint 计划 1 或 2 | Microsoft 365 F1 或 F3、Office 365 F3 |
|:-----|:-----|:-----|:-----|
|每个组织的总存储空间 <sup>1、2、6</sup> <br/> |购买的每个许可证 1 TB 加上 10 GB <sup>3</sup>  <br/> |购买的每个许可证 1 TB 加上 10 GB <sup>3</sup> <br/> |1 TB <sup>3</sup> <br/> |
|每个网站（网站集）的最大存储空间 <sup>4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB <sup>5</sup> <br/> |
|每个组织的网站（网站集）  <br/> |200 万 <sup>6</sup> <br/> |200 万 <sup>6</sup> <br/> |200 万<br/> |
|用户数  <br/> |最多 300 个  <br/> |1- 500,000<sup>7</sup> <br/> |1- 500,000<sup>7</sup> <br/> |
   
<sup>1</sup> [了解如何查找组织的总存储空间和可用存储空间。](/sharepoint/manage-site-collection-storage-limits) 可以购买的额外存储空间不受限制。 请参阅 [添加订阅的存储空间](/office365/admin/subscriptions-and-billing/add-storage-space)。 
<br/><sup>2</sup> 建议监视并定期清空回收站。 其所用存储空间是组织总存储限制的一部分。 
<br/> <sup>3</sup> 如果具有 Microsoft 365 订阅和 Office 365 额外文件存储加载项，则存储量将增加。 
<br/> <sup>4</sup> 这是单个网站（以前称为“网站集”）的存储 *限制*，而不是为每个站点 *提供的* 存储量。 此限制适用于所有类型的网站，包括 Office 365 组连接团队网站和 OneDrive。 SharePoint 管理员可以 [手动设置较低的存储限制](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits)。 
<br/> <sup>5</sup>一线工作人员无法管理SharePoint网站。 
<br/> <sup>6</sup> 不包括为每个许可用户创建的 OneDrive。 
<br/> <sup>7</sup> 如果用户数超过 500,000，请与 Microsoft 代表联系。 
  
## <a name="service-limits-for-all-plans"></a>所有计划的服务限制

### <a name="items-in-lists-and-libraries"></a>列表和库中的项

一个列表最多可具有 3 千万个项目，一个库最多可具有 3 千万个文件和文件夹。 当列表、库或文件夹包含超过 100,000 个项目时，不能中断对列表、库或文件夹的权限继承。 也不能对其重新继承权限。 但是，你仍然可以中断对该列表、库或文件夹中单个项的继承，最多可到列表或库中唯一权限的上限（请参阅下一部分）。 要详细了解查看大型列表的其他限制，请参阅 [在 Office 365 中管理大型列表和库](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784)。

### <a name="unique-security-scopes-per-list-or-library"></a>每个列表或库的唯一安全作用域

对于大型列表，设计具有尽可能少的唯一权限，并且总计保持在 5,000 以下。

### <a name="file-size-and-file-path-length"></a>文件大小和文件路径长度

- **250 GB - 文件上传限制** 适用于上传到 Microsoft Teams 文件选项卡、SharePoint 文档库、OneDrive 文件夹和 Yammer 对话的每个单个文件。

- **250 MB - 附加到列表项的文件。** 适用于 Microsoft Lists和 SharePoint Lists - 二者都基于相同的列表平台。

要详细了解使用新的 OneDrive 同步应用 (OneDrive.exe) 时的限制和约束，请参阅 [无效的文件名和文件类型](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)。

### <a name="moving-and-copying-across-sites"></a>跨网站移动和复制

在单个操作中复制/移动多个文件有三个要求：

- 总文件大小不超过 100 GB
- 不超过 30,000 个文件
- 每个文件必须小于 15 GB。

### <a name="sync"></a>同步

为获得最佳性能，建议在单个 OneDrive 或团队网站库中存储不超过 300,000 个文件。 尽管 SharePoint Online 可以在每个库中存储 3 千万个文档，但为获得最佳性能，建议跨所有文档库同步不超过 30 万个文件。 此外，如果在要同步的所有库中存在 30 万个或以上的项目，即使不同步这些库中的所有项目，也可能出现相同的性能问题。 如果使用以前的 OneDrive for Business 同步客户端 (Groove.exe)，则每个库的同步限制为 2 万项（包括每个团队网站的 5 千项）。

### <a name="versions"></a>版本

50,000 个主要版本和 511 个次要版本。

### <a name="sharepoint-groups"></a>SharePoint 组

用户可附属于每个网站（网站集）5,000 个组，每个组最多可有 5,000 名用户。每个网站（网站集）最多可有 10,000 个组。

> [!NOTE]
> 有关 Azure AD 组限制，请参阅 [Azure AD 服务限制和约束](/azure/active-directory/users-groups-roles/directory-service-limits-restrictions)，因为此类限制可能影响公共和专用组网站成员身份管理。

### <a name="managed-metadata"></a>托管元数据

共有 100 万个术语，总计 200 万个术语标签和 100 万个术语属性（这些限制用于全局和站点级术语组合）。 1,000 个全局术语集和 1,000 个全局组。

### <a name="overall-site-metadata"></a>整体网站元数据

每个网站 1000 GB（元数据很少达到此大小）。

### <a name="subsites"></a>子网站

每个网站（网站集）2,000 个 建议创建网站并将其组织到中心，而不是创建子网站。 如果确实使用子网站，我们建议限制子网站的数量（尤其是在流量很大的网站上）。

> [!NOTE]
> 你的组织限制为 2,000 个中心网站。 可能不需要为每个功能都设置一个中心网站，因此在创建中心之前，请务必进行规划。 有关详细信息，请访问 [规划 SharePoint 中心网站](/sharepoint/planning-hub-sites)。

### <a name="sharepoint-hosted-applications"></a>SharePoint 托管应用程序

每个组织 20,000 个实例。

### <a name="users"></a>用户

每个网站集 200 万个。

> [!NOTE]
> 对于可以邀请到 SharePoint 网站的来宾数量没有明显的限制。 有关外部共享的详细信息，请参阅 [外部共享概述](/sharepoint/external-sharing-overview)。

## <a name="see-also"></a>另请参阅

[SharePoint 的搜索限制](/sharepoint/search-limits)