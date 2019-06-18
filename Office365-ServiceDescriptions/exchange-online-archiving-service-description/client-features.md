---
title: Exchange Online Archiving 中的客户端功能
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- clients-and-devices-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c8d5f97a-607f-4949-a4f7-0b9e3b246851
description: Microsoft Exchange Online 存档使用户能够从各种设备和平台连接到其存档邮箱。 连接到用户存档的所有网络连接都通过 Internet 发生，无需虚拟专用网 (VPN) 连接。 组织可以发布一个本地客户端访问服务器，通过此服务器，用户可以使用 Outlook 无处不在 （而无需通过 VPN 连接）访问其主邮箱。 如果需要 VPN 接入以访问位于本地服务器上的用户主邮箱，此要求不会更改。
ms.openlocfilehash: b4f35a2bdc4e0c9f4ae54ec7be4997c9d946e0d4
ms.sourcegitcommit: af6f6ee0a74831a5af784612c7a4316658a53e28
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/18/2019
ms.locfileid: "35018294"
---
# <a name="client-features-in-exchange-online-archiving"></a>Exchange Online Archiving 中的客户端功能

Microsoft Exchange Online 存档使用户能够从各种设备和平台连接到其存档邮箱。 连接到用户存档的所有网络连接都通过 Internet 发生，无需虚拟专用网 (VPN) 连接。 组织可以发布一个本地客户端访问服务器，通过此服务器，用户可以使用 Outlook 无处不在 （而无需通过 VPN 连接）访问其主邮箱。 如果需要 VPN 接入以访问位于本地服务器上的用户主邮箱，此要求不会更改。
  
> [!IMPORTANT]
> Microsoft 保留阻止或限制从任何会对 Exchange Online Archiving 服务的运行状况带来负面影响的客户端软件连接的权利。 
  
## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook 是一款丰富的电子邮件程序，包括对日历、联系人和任务的支持。Exchange Online Archiving 支持 Outlook 2013、Outlook 2010 和 Outlook 2007。关键功能包括：
  
- **Outlook 无处不在** Outlook 无处不在 使 Outlook 用户可以通过 Internet （而无需通过 VPN 连接）连接到 Exchange Server 和 Exchange Online Archiving。Outlook 和 Exchange Online Archiving 之间的通信通过 SSL 保护的隧道使用 RPC-over-HTTP Windows 网络组件进行。    
- **自动发现** Exchange 自动发现服务自动配置 Outlook 以用于 Exchange Online Archiving。首次（以及之后在固定的时间间隔）使用电子邮件地址和密码登录时，自动发现使 Outlook 用户可以直接从 Exchange 接收他们所需的配置文件设置。 
    
Outlook 2010 及更高版本和 Outlook Web App 向用户提供了存档的完整功能，以及保留和存档策略等相关功能。
  
Outlook 2007 提供对存档的基本支持，但并非所有存档和合规性功能在 Outlook 2007 中均可用。例如，在 Outlook 2007 中，用户无法将保留和存档策略应用于其邮箱中的项目，而必须依赖管理员设置的策略。Outlook 2007 用户必须具有 2011 年 2 月的 Office 2007 累积更新才能访问存档。
  
> [!NOTE]
> Exchange Online Archiving 不提供 Outlook。Microsoft Office 365 ProPlus（包括 Microsoft Outlook）包含在一些 Office 365 计划中，同时可以作为单独订阅购买。有关详细信息，请参阅 [Office 365 计划选项](../office-365-platform-service-description/office-365-plan-options.md)。有关 Office 365 ProPlus 的详细信息，请参阅 [Office Applications 服务说明](../office-applications-service-description/office-applications-service-description.md)。 
  
### <a name="clients-supported-by-exchange-online-archiving"></a>Exchange Online Archiving 支持的客户端

下表列出了 Exchange Online Archiving 支持的客户端：
  
|**客户端**|**EOA 支持**|
|:-----|:-----|
|Outlook 2010 及更高版本  <br/> |支持 Exchange Online Archiving 中的最新功能。<sup>1</sup> <br/> |
|Outlook 2007  <br/> |支持与 Exchange Online Archiving 结合使用。<sup>1、2</sup> <br/> |
|Outlook 2003  <br/> |不支持  <br/> |
|Outlook for Mac 2011  <br/> |不支持  <br/> |
|Outlook for Mac  <br/> |支持与 Exchange Online 存档配合使用。<sup>3</sup> <br/> |
|Microsoft Office Entourage 2008 Web Services Edition  <br/> |不支持  <br/> |
|IMAP 和 POP  <br/> |不支持  <br/> |
|Exchange ActiveSync（移动设备）  <br/> |不支持  <br/> |
   
> [!NOTE]
> <sup>1</sup> 不支持 Microsoft Office Standard 随附的 Outlook。 若要了解详细信息，请参阅 [License requirements for Personal Archive and retention policies](https://support.office.com/article/Outlook-license-requirements-for-Exchange-features-46B6B7C5-C3CA-43E5-8424-1E2807917C99)（个人存档和保留策略的许可证要求）。 <br/> 
<sup>2</sup> 必须更新才能启用存档支持。 Outlook 2007 用户无法查看保留或存档策略，也无法将其应用于存档邮箱中的项，而必须依赖管理员预配的策略。 此外，Outlook 2007 用户无法同时搜索本地邮箱和存档。 <br/> 
<sup>3</sup>不能使用 outlook 2016 for Mac 或 Outlook for mac 将文件夹、日历项目、联系人、任务或笔记移动或复制到存档中, 或在存档邮箱中查看这些项目 (如果以前使用任何其他版本的 Outlook 将其移动到该位置) (如适用于 Windows 的 Outlook 2016)。 有关详细信息, 请参阅[使用适用于 Mac 的 Outlook 2016 的在线存档](https://support.office.com/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238)。 

## <a name="outlook-web-app"></a>Outlook Web App

Outlook Web App 是用于 Exchange Online、基于 Web 的 Outlook 电子邮件程序版本。无论用户是在家里、在办公室或是在路上连接到 Internet，都可以通过 Outlook Web App 访问电子邮件。
  
用户可以（使用相同的 URL）通过登录到本地 Outlook Web App 来访问其存档。存档显示在 Outlook Web App 中的主邮箱旁边。没有直接从 Outlook Web App 访问存档的显式方法。
  
## <a name="feature-availability"></a>功能可用性

若要查看在各个 Office 365 计划、独立选项和内部部署解决方案之间的功能可用性，请参阅 [Exchange Online Archiving 服务说明](exchange-online-archiving-service-description.md)。