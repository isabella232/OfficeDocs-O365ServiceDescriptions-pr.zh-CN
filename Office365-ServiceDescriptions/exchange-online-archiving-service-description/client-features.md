---
title: Exchange Online Archiving 中的客户端功能
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- clients-and-devices-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c8d5f97a-607f-4949-a4f7-0b9e3b246851
description: Microsoft Exchange Online Archiving 使用户能够从设备和平台的各种连接到其存档邮箱。用户的存档的所有网络连接都发生通过 Internet，并且不需要虚拟专用网络 (VPN) 连接。组织可以发布以允许用户访问而无需 VPN 连接使用 Outlook Anywhere，其主邮箱的本地客户端访问服务器。如果 VPN 访问需要访问位于内部部署服务器的用户的主邮箱，则不会更改此要求。
ms.openlocfilehash: 90f384e990363294c8972a79e8b500d97ca4a839
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/19/2018
ms.locfileid: "24034997"
---
# <a name="client-features-in-exchange-online-archiving"></a>Exchange Online Archiving 中的客户端功能

Microsoft Exchange Online Archiving 使用户能够从设备和平台的各种连接到其存档邮箱。用户的存档的所有网络连接都发生通过 Internet，并且不需要虚拟专用网络 (VPN) 连接。组织可以发布以允许用户访问而无需 VPN 连接使用 Outlook Anywhere，其主邮箱的本地客户端访问服务器。如果 VPN 访问需要访问位于内部部署服务器的用户的主邮箱，则不会更改此要求。
  
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
|Outlook for Mac  <br/> |支持用于 Exchange Online Archiving。<sup>3</sup> <br/> |
|Microsoft Office Entourage 2008 Web Services Edition  <br/> |不支持  <br/> |
|IMAP 和 POP  <br/> |不支持  <br/> |
|Exchange ActiveSync（移动设备）  <br/> |不支持  <br/> |
   
> [!NOTE]
> <sup>1</sup>不支持 outlook 包含与 Microsoft Office Standard。若要了解详细信息，请参阅[个人存档和保留策略的许可证要求](https://go.microsoft.com/fwlink/?LinkId=389396)。> <sup>2</sup>需要更新，若要启用存档支持。Outlook 2007 用户无法查看或应用保留或存档策略以其存档邮箱; 中的项目它们必须依赖管理员设置策略。此外，Outlook 2007 用户无法搜索内部部署邮箱和同时存档。> <sup>3</sup>无法使用 Outlook 2016 Mac 或 Outlook for Mac 移动或复制文件夹、 日历项、 联系人、 任务或说明您存档或查看它们在存档邮箱中，如果使用任何其他版本的 Outlook （以前存在移动项目如 Outlook 2016 windows)。有关详细信息，请参阅[使用与 Outlook for Mac 的 2016年您联机存档](https://support.office.com/en-us/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238)。 
  
## <a name="outlook-web-app"></a>Outlook Web App

Outlook Web App 是用于 Exchange Online、基于 Web 的 Outlook 电子邮件程序版本。无论用户是在家里、在办公室或是在路上连接到 Internet，都可以通过 Outlook Web App 访问电子邮件。
  
用户可以（使用相同的 URL）通过登录到本地 Outlook Web App 来访问其存档。存档显示在 Outlook Web App 中的主邮箱旁边。没有直接从 Outlook Web App 访问存档的显式方法。
  
## <a name="feature-availability"></a>功能可用性

若要查看在各个 Office 365 计划、独立选项和内部部署解决方案之间的功能可用性，请参阅 [Exchange Online Archiving 服务说明](exchange-online-archiving-service-description.md)。
  

