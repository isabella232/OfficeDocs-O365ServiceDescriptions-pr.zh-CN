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
# <a name="client-features-in-exchange-online-archiving"></a><span data-ttu-id="a7605-106">Exchange Online Archiving 中的客户端功能</span><span class="sxs-lookup"><span data-stu-id="a7605-106">Client Features in Exchange Online Archiving</span></span>

<span data-ttu-id="a7605-p102">Microsoft Exchange Online Archiving 使用户能够从设备和平台的各种连接到其存档邮箱。用户的存档的所有网络连接都发生通过 Internet，并且不需要虚拟专用网络 (VPN) 连接。组织可以发布以允许用户访问而无需 VPN 连接使用 Outlook Anywhere，其主邮箱的本地客户端访问服务器。如果 VPN 访问需要访问位于内部部署服务器的用户的主邮箱，则不会更改此要求。</span><span class="sxs-lookup"><span data-stu-id="a7605-p102">Microsoft Exchange Online Archiving enables users to connect to their archive mailboxes from a variety of devices and platforms. All network connectivity to the user's archive occurs over the Internet, and virtual private network (VPN) connections are not required. Organizations can publish an on-premises Client Access server to allow users to access their primary mailbox using Outlook Anywhere, without requiring a VPN connection. If VPN access is required to access the user's primary mailbox located on an on-premises server, this requirement does not change.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="a7605-111">Microsoft 保留阻止或限制从任何会对 Exchange Online Archiving 服务的运行状况带来负面影响的客户端软件连接的权利。</span><span class="sxs-lookup"><span data-stu-id="a7605-111">Microsoft reserves the right to block or throttle connections from any client software that negatively impacts the health of the Exchange Online Archiving service.</span></span> 
  
## <a name="microsoft-outlook"></a><span data-ttu-id="a7605-112">Microsoft Outlook</span><span class="sxs-lookup"><span data-stu-id="a7605-112">Microsoft Outlook</span></span>

<span data-ttu-id="a7605-p103">Microsoft Outlook 是一款丰富的电子邮件程序，包括对日历、联系人和任务的支持。Exchange Online Archiving 支持 Outlook 2013、Outlook 2010 和 Outlook 2007。关键功能包括：</span><span class="sxs-lookup"><span data-stu-id="a7605-p103">Microsoft Outlook is a rich email program that includes support for calendaring, contacts, and tasks. Exchange Online Archiving supports Outlook 2013, Outlook 2010, and Outlook 2007. Key features include:</span></span>
  
- <span data-ttu-id="a7605-p104">**Outlook 无处不在** Outlook 无处不在 使 Outlook 用户可以通过 Internet （而无需通过 VPN 连接）连接到 Exchange Server 和 Exchange Online Archiving。Outlook 和 Exchange Online Archiving 之间的通信通过 SSL 保护的隧道使用 RPC-over-HTTP Windows 网络组件进行。</span><span class="sxs-lookup"><span data-stu-id="a7605-p104">**Outlook Anywhere** Outlook Anywhere lets Outlook users connect to Exchange Server and Exchange Online Archiving over the Internet with no need for a VPN connection. Communication between Outlook and Exchange Online Archiving occurs via an SSL-secured tunnel, using the RPC-over-HTTP Windows networking component.</span></span> 
    
- <span data-ttu-id="a7605-p105">**自动发现** Exchange 自动发现服务自动配置 Outlook 以用于 Exchange Online Archiving。首次（以及之后在固定的时间间隔）使用电子邮件地址和密码登录时，自动发现使 Outlook 用户可以直接从 Exchange 接收他们所需的配置文件设置。</span><span class="sxs-lookup"><span data-stu-id="a7605-p105">**Autodiscover** The Exchange Autodiscover service automatically configures Outlook to work with Exchange Online Archiving. Autodiscover enables Outlook users to receive their required profile settings directly from Exchange the first time (and at fixed intervals thereafter) that they sign in with their email address and password.</span></span> 
    
<span data-ttu-id="a7605-120">Outlook 2010 及更高版本和 Outlook Web App 向用户提供了存档的完整功能，以及保留和存档策略等相关功能。</span><span class="sxs-lookup"><span data-stu-id="a7605-120">Outlook 2010 and later and Outlook Web App provide users with the full features of the archive, as well as related features like retention and archive policies.</span></span>
  
<span data-ttu-id="a7605-p106">Outlook 2007 提供对存档的基本支持，但并非所有存档和合规性功能在 Outlook 2007 中均可用。例如，在 Outlook 2007 中，用户无法将保留和存档策略应用于其邮箱中的项目，而必须依赖管理员设置的策略。Outlook 2007 用户必须具有 2011 年 2 月的 Office 2007 累积更新才能访问存档。</span><span class="sxs-lookup"><span data-stu-id="a7605-p106">Outlook 2007 provides basic support for the archive, but not all archiving and compliance features are available in Outlook 2007. For example, with Outlook 2007, users cannot apply retention or archive policies to items in their mailboxes. They must rely on administrator-provisioned policies instead. Outlook 2007 users require the Office 2007 Cumulative Update for February 2011 to access the archive.</span></span>
  
> [!NOTE]
> <span data-ttu-id="a7605-p107">Exchange Online Archiving 不提供 Outlook。Microsoft Office 365 ProPlus（包括 Microsoft Outlook）包含在一些 Office 365 计划中，同时可以作为单独订阅购买。有关详细信息，请参阅 [Office 365 计划选项](../office-365-platform-service-description/office-365-plan-options.md)。有关 Office 365 ProPlus 的详细信息，请参阅 [Office Applications 服务说明](../office-applications-service-description/office-applications-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="a7605-p107">Outlook is not provided with Exchange Online Archiving. Microsoft Office 365 ProPlus (which includes Microsoft Outlook) is included in some Office 365 plans and can be purchased as a separate subscription. For more information, see [Office 365 Plan Options](../office-365-platform-service-description/office-365-plan-options.md). For more information about Office 365 ProPlus, see the [Office Applications Service Description](../office-applications-service-description/office-applications-service-description.md).</span></span> 
  
### <a name="clients-supported-by-exchange-online-archiving"></a><span data-ttu-id="a7605-129">Exchange Online Archiving 支持的客户端</span><span class="sxs-lookup"><span data-stu-id="a7605-129">Clients supported by Exchange Online Archiving</span></span>

<span data-ttu-id="a7605-130">下表列出了 Exchange Online Archiving 支持的客户端：</span><span class="sxs-lookup"><span data-stu-id="a7605-130">The table below lists the clients supported by Exchange Online Archiving:</span></span>
  
|<span data-ttu-id="a7605-131">**客户端**</span><span class="sxs-lookup"><span data-stu-id="a7605-131">**Client**</span></span>|<span data-ttu-id="a7605-132">**EOA 支持**</span><span class="sxs-lookup"><span data-stu-id="a7605-132">**EOA Support**</span></span>|
|:-----|:-----|
|<span data-ttu-id="a7605-133">Outlook 2010 及更高版本</span><span class="sxs-lookup"><span data-stu-id="a7605-133">Outlook 2010 and later</span></span>  <br/> |<span data-ttu-id="a7605-134">支持 Exchange Online Archiving 中的最新功能。<sup>1</sup></span><span class="sxs-lookup"><span data-stu-id="a7605-134">Supports the latest features in Exchange Online Archiving.<sup>1</sup></span></span> <br/> |
|<span data-ttu-id="a7605-135">Outlook 2007</span><span class="sxs-lookup"><span data-stu-id="a7605-135">Outlook 2007</span></span>  <br/> |<span data-ttu-id="a7605-136">支持与 Exchange Online Archiving 结合使用。<sup>1、2</sup></span><span class="sxs-lookup"><span data-stu-id="a7605-136">Supported for use with Exchange Online Archiving.<sup>1,2</sup></span></span> <br/> |
|<span data-ttu-id="a7605-137">Outlook 2003</span><span class="sxs-lookup"><span data-stu-id="a7605-137">Outlook 2003</span></span>  <br/> |<span data-ttu-id="a7605-138">不支持</span><span class="sxs-lookup"><span data-stu-id="a7605-138">Not supported</span></span>  <br/> |
|<span data-ttu-id="a7605-139">Outlook for Mac 2011</span><span class="sxs-lookup"><span data-stu-id="a7605-139">Outlook for Mac 2011</span></span>  <br/> |<span data-ttu-id="a7605-140">不支持</span><span class="sxs-lookup"><span data-stu-id="a7605-140">Not supported</span></span>  <br/> |
|<span data-ttu-id="a7605-141">Outlook for Mac</span><span class="sxs-lookup"><span data-stu-id="a7605-141">Outlook for Mac</span></span>  <br/> |<span data-ttu-id="a7605-142">支持用于 Exchange Online Archiving。<sup>3</sup></span><span class="sxs-lookup"><span data-stu-id="a7605-142">Supported for use with Exchange Online Archiving.<sup>3</sup></span></span> <br/> |
|<span data-ttu-id="a7605-143">Microsoft Office Entourage 2008 Web Services Edition</span><span class="sxs-lookup"><span data-stu-id="a7605-143">Microsoft Office Entourage 2008 Web Services Edition</span></span>  <br/> |<span data-ttu-id="a7605-144">不支持</span><span class="sxs-lookup"><span data-stu-id="a7605-144">Not supported</span></span>  <br/> |
|<span data-ttu-id="a7605-145">IMAP 和 POP</span><span class="sxs-lookup"><span data-stu-id="a7605-145">IMAP and POP</span></span>  <br/> |<span data-ttu-id="a7605-146">不支持</span><span class="sxs-lookup"><span data-stu-id="a7605-146">Not supported</span></span>  <br/> |
|<span data-ttu-id="a7605-147">Exchange ActiveSync（移动设备）</span><span class="sxs-lookup"><span data-stu-id="a7605-147">Exchange ActiveSync (Mobile devices)</span></span>  <br/> |<span data-ttu-id="a7605-148">不支持</span><span class="sxs-lookup"><span data-stu-id="a7605-148">Not supported</span></span>  <br/> |
   
> [!NOTE]
> <span data-ttu-id="a7605-p108"><sup>1</sup>不支持 outlook 包含与 Microsoft Office Standard。若要了解详细信息，请参阅[个人存档和保留策略的许可证要求](https://go.microsoft.com/fwlink/?LinkId=389396)。> <sup>2</sup>需要更新，若要启用存档支持。Outlook 2007 用户无法查看或应用保留或存档策略以其存档邮箱; 中的项目它们必须依赖管理员设置策略。此外，Outlook 2007 用户无法搜索内部部署邮箱和同时存档。> <sup>3</sup>无法使用 Outlook 2016 Mac 或 Outlook for Mac 移动或复制文件夹、 日历项、 联系人、 任务或说明您存档或查看它们在存档邮箱中，如果使用任何其他版本的 Outlook （以前存在移动项目如 Outlook 2016 windows)。有关详细信息，请参阅[使用与 Outlook for Mac 的 2016年您联机存档](https://support.office.com/en-us/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238)。</span><span class="sxs-lookup"><span data-stu-id="a7605-p108"><sup>1</sup> Outlook included with Microsoft Office Standard is not supported. To learn more, see [License requirements for Personal Archive and retention policies](https://go.microsoft.com/fwlink/?LinkId=389396). > <sup>2</sup> Requires update to enable archiving support. Outlook 2007 users cannot view or apply retention or archive policies to items in their archive mailboxes; they must rely on administrator-provisioned policies. Additionally, Outlook 2007 users cannot search the on-premises mailbox and the archive at the same time. > <sup>3</sup> You can't use Outlook 2016 for Mac or Outlook for Mac to move or copy folders, calendar items, contacts, tasks, or notes to your archive, or view them in the archive mailbox, if the items were previously moved there by using any other version of Outlook (such as Outlook 2016 for Windows). For more information, see [Use your online archive with Outlook 2016 for Mac](https://support.office.com/en-us/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238).</span></span> 
  
## <a name="outlook-web-app"></a><span data-ttu-id="a7605-156">Outlook Web App</span><span class="sxs-lookup"><span data-stu-id="a7605-156">Outlook Web App</span></span>

<span data-ttu-id="a7605-p109">Outlook Web App 是用于 Exchange Online、基于 Web 的 Outlook 电子邮件程序版本。无论用户是在家里、在办公室或是在路上连接到 Internet，都可以通过 Outlook Web App 访问电子邮件。</span><span class="sxs-lookup"><span data-stu-id="a7605-p109">Outlook Web App is a web-based version of the Outlook email program that is used with Exchange Online. Wherever users are connected to the Internet—at home, at the office, or on the road—they can access their email through Outlook Web App.</span></span>
  
<span data-ttu-id="a7605-p110">用户可以（使用相同的 URL）通过登录到本地 Outlook Web App 来访问其存档。存档显示在 Outlook Web App 中的主邮箱旁边。没有直接从 Outlook Web App 访问存档的显式方法。</span><span class="sxs-lookup"><span data-stu-id="a7605-p110">Users can access their archive by signing in to Outlook Web App on-premises (using the same URL). The archive appears alongside their primary mailbox in Outlook Web App. There is no explicit way to access the archive directly from Outlook Web App.</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="a7605-162">功能可用性</span><span class="sxs-lookup"><span data-stu-id="a7605-162">Feature Availability</span></span>

<span data-ttu-id="a7605-163">若要查看在各个 Office 365 计划、独立选项和内部部署解决方案之间的功能可用性，请参阅 [Exchange Online Archiving 服务说明](exchange-online-archiving-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="a7605-163">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Archiving Service Description](exchange-online-archiving-service-description.md).</span></span>
  

