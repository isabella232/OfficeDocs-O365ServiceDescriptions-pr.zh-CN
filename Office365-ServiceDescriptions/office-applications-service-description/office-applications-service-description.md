---
title: Office 应用程序服务说明
ms.author: office365servicedesc
author: priyarakshith
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-applications-service-description
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 016abc8b-11f0-402a-aba6-32499e39e176
description: Microsoft 365是一项订阅服务，为你提供你已经熟悉的Office桌面应用程序的最新版本，例如 Word、Excel 和PowerPoint。
ms.openlocfilehash: e0f1ebfc5bab0564ab8c16322b1e0b38564ac0bd
ms.sourcegitcommit: 726d287aa050d0d87d28cbf9dd2fd108a55c8be8
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/29/2022
ms.locfileid: "65139017"
---
# <a name="office-applications-service-description"></a>Office 应用程序服务说明

Microsoft 365 (以前Office应用程序) 是一种订阅服务，它为你提供你已经熟悉的最新版本的Microsoft 365应用，例如 Word、Excel 和PowerPoint。

即使它是基于云的服务，Microsoft 365应用也不会在云中运行。 相反，用户会从Microsoft 365门户下载应用，并将其安装在本地计算机上，可在 Windows、Mac、IOS 和 Android 操作系统上使用。 Microsoft 使用即点即用技术使Microsoft 365应用的下载和安装变得快速而简单。 即点即用使用虚拟化技术在本地计算机上独立环境中运行Microsoft 365应用，使用户能够与早期版本的Office并行运行Microsoft 365应用。 Microsoft 365应用在 32 位\*和 64 位版本中可用。

有关为用户启用Microsoft 365应用服务说明的企业订阅的详细计划信息，请参阅[完整的订阅比较表](https://aka.ms/M365EnterprisePlans)。
## <a name="available-plans"></a>可用计划
有关为用户启用Microsoft 365应用的订阅的详细计划信息，请[参阅“比较Microsoft 365 企业版计划](https://www.microsoft.com/microsoft-365/enterprise/compare-office-365-plans)”。
  
## <a name="feature-availability"></a>功能可用性 
下表列出了所有计划中可用的主要Microsoft 365应用功能 (某些注意事项适用 - 请参阅脚注，了解) 的详细信息。 使用该表可比较 2013、Office 2016、Office 2019 和 Office LTSC Microsoft Office计划和批量许可版本的功能可用性。
  
一些业务计划Microsoft 365具有可为订阅购买的加载项。 附加内容可为订阅提供其他功能。 有关详细信息，请 [参阅“购买”或“编辑加载项](https://support.office.com/article/4e7b57d6-b93b-457d-aecd-0ea58bff07a6)”。<br><br>

**跨计划的 MICROSOFT 365 应用功能可用性**

| 应用程序/功能<img width=200/>  | Office Professional Plus 2013/2016/2019 | Office LTSC 2021 | Microsoft 365 企业应用版 | Microsoft 365 商业应用版 | Microsoft 365 商业基础版 | Microsoft 365 商业标准版和高级版 | Office 365 E1 | Office 365 E3/E5 |
| :----- | :----- | :----- | :----- | :----- | :----- | :-----| :----- | :----- |
|[Microsoft Word](/office365/servicedescriptions/office-applications-service-description/office-applications#microsoft-word)<br>[Microsoft Excel](/office365/servicedescriptions/office-applications-service-description/office-applications#microsoft-excel)<br>[Microsoft PowerPoint](/office365/servicedescriptions/office-applications-service-description/office-applications#microsoft-powerpoint)<br>[Microsoft OneNote](/office365/servicedescriptions/office-applications-service-description/office-applications#microsoft-onenote)<br>[Microsoft Outlook](/office365/servicedescriptions/office-applications-service-description/office-applications#microsoft-outlook)<br>[Microsoft Publisher](/office365/servicedescriptions/office-applications-service-description/office-applications#microsoft-publisher)<br>[Microsoft Access](/office365/servicedescriptions/office-applications-service-description/office-applications#microsoft-access) | 是 | 是 | 是 | 是 | 否 | 是 | 否 | 是 |
|[Microsoft InfoPath](/office365/servicedescriptions/office-applications-service-description/office-applications#microsoft-infopath) | 是<sup>1</sup> | 否 | 否 | 否 | 否 | 否 | 否 | 是 |
|[Windows 10 应用](/office365/servicedescriptions/office-applications-service-description/office-applications#windows-10-apps) | 否 | 否 | 是 | 是 | 是 | 是 | 是<sup>2</sup> | 是 |
| Microsoft 365 应用版 for <sup>Mac3</sup><br> 适用于 <sup>Android3</sup> 的Outlook | 否 | 否 | 是 | 是 | 否 | 是 | 否 | 是 |
| [Office Mobile for iPad/iPhone <sup>3</sup>](/office365/servicedescriptions/office-applications-service-description/office-applications#office-mobile-for-ipadiphone)<br> [Office Mobile for <sup>Android3</sup>](/office365/servicedescriptions/office-applications-service-description/office-applications#office-mobile-for-android) | 否 | 否 | 是 | 是 | 是<sup>4</sup> | 是 | <sup>Yes4</sup> | 是 |
|Microsoft Teams  | 否 | 是 | 是 | 是 | 是 | 是 | 是 | 是 | 

**跨计划的企业功能可用性**

| 企业价值<img width=200/> | Office Professional Plus 2013/2016/2019 | Office LTSC 2021| Microsoft 365 企业应用版 | Microsoft 365 商业应用版 | Microsoft 365 商业基础版 | Microsoft 365 商业标准版和高级版 | Office 365 E1 | Office 365 E3/E5  |
| :----- | :----- | :----- | :----- | :----- | :----- | :----- | :----- | :----- |
| 每个用户在电脑或 <sup>Mac3</sup> 上安装 5 个<br>版本升级 | 否 | 否 | 是 | 是 | 否 | 是 | 否 | 是 |
| 自动用户帐户预配 <sup>3</sup><br>Office云策略支持 <sup>6</sup> | 否 | 否 | 是 | 是<sup>11</sup> | 是<sup>12</sup> | 是<sup>11</sup> | 是<sup>12</sup> | 是 |
| 客户端推送部署<br>客户端应用程序的脱机支持 | 是 | 是 | 是 | 是 | 是 | 是 | 否 | 是 |
| 内部部署 Exchange 的客户端支持<br>内部部署 SharePoint 的客户端支持<br>控制软件更新<br>Excel <sup>6</sup> 的PowerPivot | 是 | 是 | 是 | 是 | 否 | 是 | 否 | 是 |
| 数据库比较<sup>6</sup><br> Excel 电子表格比较<sup>6</sup><br>Excel 电子表格查询<sup>6</sup><br>Office 遥测 | 是 | 是 | 是 | 否 | 否 | 否 | 否 | 是 |
| 桌面虚拟化 <sup>6</sup> | 是 | 是 | 是<sup>7</sup> | 否 | 否 | 是<sup>8</sup> | 否 | 是 |
| Exchange Online 和 SharePoint Online 存档和合规性 | 是<sup>9</sup> | 是 | 是<sup>10</sup> | 是 | 否 | 是 | 否 | 是 |
| 信息权限管理 | 是 | 是 | 是 | 是 | 是 | 是 | 是 | 是 |
| [Microsoft 信息保护 - 手动敏感度标记](/office365/servicedescriptions/microsoft-365-service-descriptions/microsoft-365-tenantlevel-services-licensing-guidance/microsoft-365-security-compliance-licensing-guidance#which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service-11) | <sup>No13</sup> | 否 | 是 | 否 | 否 | 是<sup>8</sup> | 是<sup>14</sup> | 是 |
| [Microsoft 信息保护 - 自动敏感度标记](/office365/servicedescriptions/microsoft-365-service-descriptions/microsoft-365-tenantlevel-services-licensing-guidance/microsoft-365-security-compliance-licensing-guidance#which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service-11) |  <sup>No13</sup> | 否 | 是<sup>15</sup> | 否 | 否 | 否 | 否 | Yes<sup>16</sup> |
| 多语言用户界面 | 是 | 是 | 是 | 否 | 否 | 是 | 否 | 是 |
| Office 加载项<br> ActiveX<br>BHO 支持 <sup>6</sup> | <sup>Yes17</sup> | <sup>Yes17</sup> | 是 | 否 | 否 | 是 | 否 | 是 |
| OneNote客户端对SharePoint服务器上的笔记本的访问<br> SharePoint Online<br> OneDrive for Business<br>Microsoft 365 | <sup>Yes18</sup> | <sup>Yes18</sup> | 是 | 是 | 否 | 是 | 否 | 是 |
| power Map for Excel <sup>6</sup> | <sup>Yes19</sup> | 是 | 是 | 否 | 否 | 否 | 否 | 是 |
| PowerQuery for Excel | <sup>Yes20</sup> | 是 | 是 | 否 | 否 | 否 | 否 | 是 |
| PowerView for Excel <sup>6</sup> | 是 | 否 | 否 | 否 | 否 | 否 | 否 | 否 |
| 漫游设置 <sup>6</sup> | 是 | 是 | 是 | 否 | 否 | 否 | 否 | Yes<sup>16</sup> |
| [共享计算机激活](/DeployOffice/overview-shared-computer-activation) <sup>6</sup> | 否 | 否 | 是 | 否 | 否 | 是<sup>8</sup> | 否 | 是 |
| 支持阻止基于云的文件存储 <sup>6</sup> | 是 | 是 | 是 | 是 | 否 | 是<sup>8</sup> | 否 | Yes<sup>16</sup> |
| 对策略 <sup>6</sup> 的支持 | 是 | 是 | 是 | 是<sup>11</sup>| 否 | <sup>Yes11，12</sup> | 否 | 是 |
| 点击可查找并重复使用内容 | 否 | 否 | 否 | 否 | 否 | <sup>Yes6，21</sup> | 否 | 是 |
| 批量激活 (KMS/MAK) | 是 | 是 | <sup>No22</sup> | 否 | 否 | 否 | 否 | 否 |

<sup>1</sup> Infopath 2013 仍受支持，并已Office 专业增强版 2016安装中，但是没有适用于 Office 2016 或更高版本的新版本。 在此处阅读详细 [信息](/lifecycle/products/infopath-2013)。<br>
<sup>2</sup> 不适用于Office 365 F3。<br>
<sup>3</sup> 基于设备的Microsoft 365 企业应用版版本中不可用。 有关[基于设备的Microsoft 365 企业应用版订阅的](/deployoffice/device-based-licensing)详细信息。<br>
<sup>4</sup> 限于具有 10.1 英寸或以下对角线的集成屏幕的设备。<br>
<sup>5</sup> Enterprise计划的Microsoft 365 应用版&#39;不包括Teams服务，但Teams仍会随Microsoft 365 应用版和组织中具有Azure Active Directory (AAD的用户一起安装) 将能够启动Teams的探索体验。 有关此免费试用版和为用户提供访问权限的详细信息，请参阅[“管理Microsoft Teams探索体验](https://go.microsoft.com/fwlink/p/?linkid=2128351)”。<br>
<sup>6</sup> 仅适用于Windows版本的Microsoft 365 应用版。<br>
用户专用虚拟桌面基础结构 (VDI) 支持 <sup>7</sup> Microsoft 365 应用版Enterprise。 Enterprise Microsoft 365 应用版仅支持通过批量许可计划购买的远程桌面服务 (RDS) 。<br>
<sup>8</sup> 不适用于Microsoft 365 商业标准版。<br>
<sup>9</sup> 不适用于 2013 Office Professional Plus。<br>
此版本的 Office 支持 <sup>10</sup> 个存档和符合性功能，但不包括 Exchange Online 和 SharePoint Online 计划，必须单独购买或与受支持的本地服务器等效项一起使用。<br>
<sup>11</sup> 仅限于 Web 应用的策略和客户端应用的隐私策略。<br>
<sup>12</sup> 限制为 Web 应用的策略。<br>
<sup>13</sup> 用于Office的 Azure 信息保护加载项可用于在这些 SKU 中启用敏感度标记。 它不包括在内，但可以作为单独的加载项购买。 有关详细信息，请参阅[信息保护：敏感度标记](/office365/servicedescriptions/microsoft-365-service-descriptions/microsoft-365-tenantlevel-services-licensing-guidance/microsoft-365-security-compliance-licensing-guidance#information-protection-sensitivity-labeling)。<br>
<sup>14</sup> 不适用于Office 365 E1。<br>
<sup>15</sup> 特别需要Microsoft 365 E5、Office 365 E5、EMS E5、Microsoft 365 合规性或Microsoft 365 E5 信息保护&amp;治理。<br>
<sup>16</sup> 不适用于Office 365 E3。<br>
<sup>17</sup> BHO 支持是 Internet Explorer 的扩展技术。<br>
<sup>18</sup> OneNote应用对 SharePoint Server、SharePoint Online、OneDrive for Business 和 Office 365 上的笔记本的访问。<br>
<sup>19</sup> 如果已Office 2013 Professional Plus 或独立版本的 Excel 2013，则可以使用 Power Map Preview for Excel 2013，这是一个不受支持的加载项。 Power Map 预览版的早期版本已过期，&#39;不会适用于任何版本的Excel。 如果安装了早期版本，请从控制面板卸载它，然后下载并安装 Power Map 预览版的当前版本。 此版本的功能与使用 MICROSOFT 365 SP1 发布的 Power Map 版本相同。<br>
<sup>20</sup> Power Query是可在此处下载的免费加载项：[适用于Excel的 Microsoft Power Query。](https://www.microsoft.com/download/details.aspx?id=39379) 启用后，功能区上的“Power Query”选项卡将提供Power Query功能。<br>
<sup>21</sup> 仅适用于Microsoft 365 商业高级版。<br>
<sup>22</sup> Office 365 E3和Microsoft 365 企业应用版的批量激活仅限于 Windows Server 2008 R2 上的安装，以及启用了 RDS 角色或Windows To Go 安装的更高版本。 无论哪种情况，访问这些安装的用户都需要获得Office 365 E3或Microsoft 365 企业应用版的许可用户。<br>
## <a name="microsoft-365-apps-availability-in-plans-for-mac"></a>Microsoft 365 Mac 计划中的应用可用性
以下Office应用程序可用于 Microsoft 365 应用版 for Enterprise for Mac 和 Office LTSC 2021 for Mac：[Microsoft Word](/office365/servicedescriptions/office-applications-service-description/office-applications#microsoft-word)、[Microsoft Excel](/office365/servicedescriptions/office-applications-service-description/office-applications#microsoft-excel)、[MicrosoftPowerPoint](/office365/servicedescriptions/office-applications-service-description/office-applications#microsoft-powerpoint)、[Microsoft OneNote](/office365/servicedescriptions/office-applications-service-description/office-applications#microsoft-onenote)、[Microsoft Outlook](/office365/servicedescriptions/office-applications-service-description/office-applications#microsoft-outlook) 和 [Microsoft Teams](/office365/servicedescriptions/teams-service-description)。
Mac OS 的三个最新版本支持Office for Mac。 由于 Mac OS 的新主要版本已正式发布，Microsoft 将停止支持最早的版本，并支持最新版本和以前的两个版本的 Mac OS。 产品功能和功能可用性可能因旧系统而异。 若要了解详细信息，请参阅[Microsoft 365和Microsoft 365应用资源](https://products.office.com/office-system-requirements)。
以下Office应用程序不适用于 Enterprise for Mac 和 Office LTSC 2021 for Mac 的Microsoft 365 应用版：[Microsoft Publisher](/office365/servicedescriptions/office-applications-service-description/office-applications#microsoft-publisher)、[Microsoft Access](/office365/servicedescriptions/office-applications-service-description/office-applications#microsoft-access) 和 [Microsoft InfoPath](/office365/servicedescriptions/office-applications-service-description/office-applications#microsoft-infopath)。
## <a name="microsoft-365-apps-and-feature-availability-in-government-plans"></a>Microsoft 365政府计划中的应用和功能可用性
以下Office应用程序在政府云中可用;但是，某些基于云的功能目前可能不可用，如[Office应用程序和政府计划中的功能可用性中](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#office-application-and-feature-availability-in-government-plans)所示。
## <a name="microsoft-365-education"></a>Microsoft 365 教育版 
有关Microsoft 365 教育版计划的详细信息，请转到[Microsoft 365 教育版](/office365/servicedescriptions/office-365-platform-service-description/microsoft-365-education)页。
## <a name="learn-more"></a>了解详细信息 
有关Microsoft 365应用的详细信息，请查看以下资源：
- **资源：**[Microsoft 365和Microsoft 365应用资源](https://www.microsoft.com/microsoft-365/microsoft-365-and-office-resources)。
- **支持矩阵：**[Windows和Microsoft 365应用配置支持矩阵](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE2OqRI)。
- **技术Community：**[Microsoft 365 - Microsoft Tech Community](https://techcommunity.microsoft.com/t5/microsoft-365/ct-p/microsoft365)。
- **消息：** 若要随时了解即将发生的更改，包括新功能和更改的功能、计划内维护或其他重要公告，请访问消息中心。 有关详细信息，请参阅[消息中心](/microsoft-365/admin/manage/message-center)。
- **许可条款：** 有关通过 Microsoft 商业批量许可计划购买的产品和服务的许可条款和条件，请参阅 [产品条款网站](https://www.microsoft.com/licensing/terms/)。
- **辅助功能：** Microsoft 仍致力于数据的安全性和服务的 [辅助功能](https://www.microsoft.com/trust-center/compliance/accessibility) 。 有关详细信息，请参阅 [Microsoft 信任中心](https://www.microsoft.com/trust-center)和 [Office 辅助功能中心](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)。
- **隐私：** 隐私对 Microsoft 很重要。 若要了解如何保护你的隐私，请参阅 [Microsoft 的隐私声明](https://privacy.microsoft.com/privacystatement)。 有关详细信息，请转到 [Microsoft 信任中心](https://www.microsoft.com/trust-center)。

