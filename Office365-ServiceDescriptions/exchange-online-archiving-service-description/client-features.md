---
title: Exchange Online Archiving 中的客户端功能
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- clients-and-devices-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c8d5f97a-607f-4949-a4f7-0b9e3b246851
description: 阅读本文，了解 Microsoft Exchange Online Archiving 中提供的客户端功能。
ms.openlocfilehash: 54f066562b08eeeed90b8c9b465c4740bcc3f0df
ms.sourcegitcommit: e342174df76128430dfc8c971716da5c4b2942ac
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/28/2020
ms.locfileid: "48293634"
---
# <a name="client-features-in-exchange-online-archiving"></a>Exchange Online Archiving 中的客户端功能

Microsoft Exchange Online存档允许用户从各种设备和平台连接到其存档邮箱。 用户存档的所有网络连接都通过 Internet 进行，无需虚拟专用 (VPN) 连接。 组织可以发布一个本地客户端访问服务器，通过此服务器，用户可以使用 Outlook 无处不在 （而无需通过 VPN 连接）访问其主邮箱。 如果需要 VPN 接入以访问位于本地服务器上的用户主邮箱，此要求不会更改。
  
> [!IMPORTANT]
> Microsoft 保留阻止或限制从任何会对 Exchange Online Archiving 服务的运行状况带来负面影响的客户端软件连接的权利。
  
## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook 是一款丰富的电子邮件程序，包括对日历、联系人和任务的支持。Exchange Online Archiving 支持 Outlook 2013、Outlook 2010 和 Outlook 2007。关键功能包括：
  
- **Outlook Anywhere** - Outlook Anywhere Outlook使用户无需 VPN 连接Exchange Server Exchange Online Archiving Internet 连接到 Exchange Server 和 Exchange Online Archiving。 Outlook 和 Exchange Online Archiving 之间的通信通过 SSL 保护的隧道使用 RPC-over-HTTP Windows 网络组件进行。    
- **自动发现**- Exchange自动发现服务自动配置Outlook以使用Exchange Online Archiving。 自动发现Outlook用户可以在 (第一次登录时直接从 Exchange 收到其所需的配置文件设置) 此后的固定时间间隔使用其电子邮件地址和密码登录。 

Outlook 2010 Outlook及更高版本及 Web 上的网站集为用户提供了存档的完整功能，以及保留和存档策略等相关功能。
  
Outlook 2007 提供对存档的基本支持，但并非所有存档和合规性功能在 Outlook 2007 中均可用。例如，在 Outlook 2007 中，用户无法将保留和存档策略应用于其邮箱中的项目，而必须依赖管理员设置的策略。Outlook 2007 用户必须具有 2011 年 2 月的 Office 2007 累积更新才能访问存档。
  
> [!NOTE]
> Exchange Online Archiving 不提供 Outlook。 Microsoft 365 企业应用版 (包括 Microsoft Outlook) 包含在一些计划中，可以单独订阅购买。 有关详细信息，请参阅Microsoft 365[计划选项](../office-365-platform-service-description/office-365-plan-options.md)。 有关应用程序Microsoft 365 企业应用版，请参阅 Office[应用程序服务说明](../office-applications-service-description/office-applications-service-description.md)。 
  
### <a name="clients-supported-by-exchange-online-archiving"></a>Exchange Online Archiving 支持的客户端

下表列出了 Exchange Online Archiving 支持的客户端：<br><br>
  
| Client | EOA 支持 |
|:-----|:-----|
|Outlook 2013 及更高版本  <br/> |支持 Exchange Online Archiving 中的最新功能。<sup>1</sup> <br/> |
|Outlook 2010  <br/> |仅在 2020 Exchange Online Archiving 2020 年 10 月 13 日之前支持最新功能|
|Outlook 2007  <br/> |不支持 |
|Outlook 2003  <br/> |不支持  <br/> |
|Outlook for Mac 2011  <br/> |不支持  <br/> |
|Outlook for Mac  <br/> |支持与 Exchange Online Archiving。<sup>3</sup> <br/> |
|Microsoft Office Entourage 2008 Web Services Edition  <br/> |不支持  <br/> |
|IMAP 和 POP  <br/> |不支持  <br/> |
|Exchange ActiveSync (移动设备)   <br/> |不支持  <br/> |
   
> [!NOTE]
> <sup>1</sup> 不支持 Microsoft Office Standard 随附的 Outlook。 若要了解详细信息，请参阅 [License requirements for Personal Archive and retention policies](https://support.office.com/article/Outlook-license-requirements-for-Exchange-features-46B6B7C5-C3CA-43E5-8424-1E2807917C99)（个人存档和保留策略的许可证要求）。 <br/> 
<sup>2</sup> 必须更新才能启用存档支持。 Outlook 2007 用户无法查看保留或存档策略，也无法将其应用于存档邮箱中的项，而必须依赖管理员预配的策略。 此外，Outlook 2007 用户无法同时搜索本地邮箱和存档。 <br/> 
<sup>3</sup>如果使用 Outlook 2016 for Mac 或 Outlook for Mac 其他任何版本的 Outlook (（例如 Outlook 2016 for Windows) ）将文件夹、日历项目、联系人、任务或便笺移动或复制到存档邮箱中，或者查看存档邮箱中的邮件，则不能使用它们。 有关详细信息，请参阅将[联机存档与 Outlook 2016 for Mac。](https://support.office.com/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238) 

## <a name="outlook-on-the-web"></a>Web 上的 Outlook

Outlook 网页版是 Web 版 Outlook 电子邮件程序，可与 Exchange Online 结合使用。 无论用户是家庭、办公室还是路旁连接到 Internet，他们都可以通过Outlook &mdash; &mdash; 访问电子邮件。
  
用户可以使用同一 URL 登录Outlook本地 (访问存档) 。 存档会显示在主邮箱旁边，Outlook Web 上的邮箱。 没有从 Web 上的直接Outlook访问存档的显式方法。
  
## <a name="feature-availability"></a>功能可用性

若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅Exchange Online Archiving[说明](exchange-online-archiving-service-description.md)。