---
title: Exchange Online Archiving 中的客户端功能
ms.author: sharik
author: skjerland
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
description: Microsoft Exchange Online 存档使用户能够从各种设备和平台连接到其存档邮箱。 连接到用户存档的所有网络连接都通过 Internet 发生，无需虚拟专用网 (VPN) 连接。 组织可以发布一个本地客户端访问服务器，通过此服务器，用户可以使用 Outlook 无处不在 （而无需通过 VPN 连接）访问其主邮箱。 如果需要 VPN 接入以访问位于本地服务器上的用户主邮箱，此要求不会更改。
ms.openlocfilehash: d1f304936d184dc30826d6e60552d4e186bb2a41
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/25/2019
ms.locfileid: "33245058"
---
# <a name="client-features-in-exchange-online-archiving"></a><span data-ttu-id="eaa3f-106">Exchange Online Archiving 中的客户端功能</span><span class="sxs-lookup"><span data-stu-id="eaa3f-106">Client Features in Exchange Online Archiving</span></span>

<span data-ttu-id="eaa3f-107">Microsoft Exchange Online 存档使用户能够从各种设备和平台连接到其存档邮箱。</span><span class="sxs-lookup"><span data-stu-id="eaa3f-107">Microsoft Exchange Online Archiving enables users to connect to their archive mailboxes from a variety of devices and platforms.</span></span> <span data-ttu-id="eaa3f-108">连接到用户存档的所有网络连接都通过 Internet 发生，无需虚拟专用网 (VPN) 连接。</span><span class="sxs-lookup"><span data-stu-id="eaa3f-108">All network connectivity to the user's archive occurs over the Internet, and virtual private network (VPN) connections are not required.</span></span> <span data-ttu-id="eaa3f-109">组织可以发布一个本地客户端访问服务器，通过此服务器，用户可以使用 Outlook 无处不在 （而无需通过 VPN 连接）访问其主邮箱。</span><span class="sxs-lookup"><span data-stu-id="eaa3f-109">Organizations can publish an on-premises Client Access server to allow users to access their primary mailbox using Outlook Anywhere, without requiring a VPN connection.</span></span> <span data-ttu-id="eaa3f-110">如果需要 VPN 接入以访问位于本地服务器上的用户主邮箱，此要求不会更改。</span><span class="sxs-lookup"><span data-stu-id="eaa3f-110">If VPN access is required to access the user's primary mailbox located on an on-premises server, this requirement does not change.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="eaa3f-111">Microsoft 保留阻止或限制从任何会对 Exchange Online Archiving 服务的运行状况带来负面影响的客户端软件连接的权利。</span><span class="sxs-lookup"><span data-stu-id="eaa3f-111">Microsoft reserves the right to block or throttle connections from any client software that negatively impacts the health of the Exchange Online Archiving service.</span></span> 
  
## <a name="microsoft-outlook"></a><span data-ttu-id="eaa3f-112">Microsoft Outlook</span><span class="sxs-lookup"><span data-stu-id="eaa3f-112">Microsoft Outlook</span></span>

<span data-ttu-id="eaa3f-p103">Microsoft Outlook 是一款丰富的电子邮件程序，包括对日历、联系人和任务的支持。Exchange Online Archiving 支持 Outlook 2013、Outlook 2010 和 Outlook 2007。关键功能包括：</span><span class="sxs-lookup"><span data-stu-id="eaa3f-p103">Microsoft Outlook is a rich email program that includes support for calendaring, contacts, and tasks. Exchange Online Archiving supports Outlook 2013, Outlook 2010, and Outlook 2007. Key features include:</span></span>
  
- <span data-ttu-id="eaa3f-p104">**Outlook 无处不在** Outlook 无处不在 使 Outlook 用户可以通过 Internet （而无需通过 VPN 连接）连接到 Exchange Server 和 Exchange Online Archiving。Outlook 和 Exchange Online Archiving 之间的通信通过 SSL 保护的隧道使用 RPC-over-HTTP Windows 网络组件进行。</span><span class="sxs-lookup"><span data-stu-id="eaa3f-p104">**Outlook Anywhere** Outlook Anywhere lets Outlook users connect to Exchange Server and Exchange Online Archiving over the Internet with no need for a VPN connection. Communication between Outlook and Exchange Online Archiving occurs via an SSL-secured tunnel, using the RPC-over-HTTP Windows networking component.</span></span> 
    
- <span data-ttu-id="eaa3f-p105">**自动发现** Exchange 自动发现服务自动配置 Outlook 以用于 Exchange Online Archiving。首次（以及之后在固定的时间间隔）使用电子邮件地址和密码登录时，自动发现使 Outlook 用户可以直接从 Exchange 接收他们所需的配置文件设置。</span><span class="sxs-lookup"><span data-stu-id="eaa3f-p105">**Autodiscover** The Exchange Autodiscover service automatically configures Outlook to work with Exchange Online Archiving. Autodiscover enables Outlook users to receive their required profile settings directly from Exchange the first time (and at fixed intervals thereafter) that they sign in with their email address and password.</span></span> 
    
<span data-ttu-id="eaa3f-120">Outlook 2010 及更高版本和 Outlook Web App 向用户提供了存档的完整功能，以及保留和存档策略等相关功能。</span><span class="sxs-lookup"><span data-stu-id="eaa3f-120">Outlook 2010 and later and Outlook Web App provide users with the full features of the archive, as well as related features like retention and archive policies.</span></span>
  
<span data-ttu-id="eaa3f-p106">Outlook 2007 提供对存档的基本支持，但并非所有存档和合规性功能在 Outlook 2007 中均可用。例如，在 Outlook 2007 中，用户无法将保留和存档策略应用于其邮箱中的项目，而必须依赖管理员设置的策略。Outlook 2007 用户必须具有 2011 年 2 月的 Office 2007 累积更新才能访问存档。</span><span class="sxs-lookup"><span data-stu-id="eaa3f-p106">Outlook 2007 provides basic support for the archive, but not all archiving and compliance features are available in Outlook 2007. For example, with Outlook 2007, users cannot apply retention or archive policies to items in their mailboxes. They must rely on administrator-provisioned policies instead. Outlook 2007 users require the Office 2007 Cumulative Update for February 2011 to access the archive.</span></span>
  
> [!NOTE]
> <span data-ttu-id="eaa3f-p107">Exchange Online Archiving 不提供 Outlook。Microsoft Office 365 ProPlus（包括 Microsoft Outlook）包含在一些 Office 365 计划中，同时可以作为单独订阅购买。有关详细信息，请参阅 [Office 365 计划选项](../office-365-platform-service-description/office-365-plan-options.md)。有关 Office 365 ProPlus 的详细信息，请参阅 [Office Applications 服务说明](../office-applications-service-description/office-applications-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="eaa3f-p107">Outlook is not provided with Exchange Online Archiving. Microsoft Office 365 ProPlus (which includes Microsoft Outlook) is included in some Office 365 plans and can be purchased as a separate subscription. For more information, see [Office 365 Plan Options](../office-365-platform-service-description/office-365-plan-options.md). For more information about Office 365 ProPlus, see the [Office Applications Service Description](../office-applications-service-description/office-applications-service-description.md).</span></span> 
  
### <a name="clients-supported-by-exchange-online-archiving"></a><span data-ttu-id="eaa3f-129">Exchange Online Archiving 支持的客户端</span><span class="sxs-lookup"><span data-stu-id="eaa3f-129">Clients supported by Exchange Online Archiving</span></span>

<span data-ttu-id="eaa3f-130">下表列出了 Exchange Online Archiving 支持的客户端：</span><span class="sxs-lookup"><span data-stu-id="eaa3f-130">The table below lists the clients supported by Exchange Online Archiving:</span></span>
  
|<span data-ttu-id="eaa3f-131">**客户端**</span><span class="sxs-lookup"><span data-stu-id="eaa3f-131">**Client**</span></span>|<span data-ttu-id="eaa3f-132">**EOA 支持**</span><span class="sxs-lookup"><span data-stu-id="eaa3f-132">**EOA Support**</span></span>|
|:-----|:-----|
|<span data-ttu-id="eaa3f-133">Outlook 2010 及更高版本</span><span class="sxs-lookup"><span data-stu-id="eaa3f-133">Outlook 2010 and later</span></span>  <br/> |<span data-ttu-id="eaa3f-134">支持 Exchange Online Archiving 中的最新功能。<sup>1</sup></span><span class="sxs-lookup"><span data-stu-id="eaa3f-134">Supports the latest features in Exchange Online Archiving.<sup>1</sup></span></span> <br/> |
|<span data-ttu-id="eaa3f-135">Outlook 2007</span><span class="sxs-lookup"><span data-stu-id="eaa3f-135">Outlook 2007</span></span>  <br/> |<span data-ttu-id="eaa3f-136">支持与 Exchange Online Archiving 结合使用。<sup>1、2</sup></span><span class="sxs-lookup"><span data-stu-id="eaa3f-136">Supported for use with Exchange Online Archiving.<sup>1,2</sup></span></span> <br/> |
|<span data-ttu-id="eaa3f-137">Outlook 2003</span><span class="sxs-lookup"><span data-stu-id="eaa3f-137">Outlook 2003</span></span>  <br/> |<span data-ttu-id="eaa3f-138">不支持</span><span class="sxs-lookup"><span data-stu-id="eaa3f-138">Not supported</span></span>  <br/> |
|<span data-ttu-id="eaa3f-139">Outlook for Mac 2011</span><span class="sxs-lookup"><span data-stu-id="eaa3f-139">Outlook for Mac 2011</span></span>  <br/> |<span data-ttu-id="eaa3f-140">不支持</span><span class="sxs-lookup"><span data-stu-id="eaa3f-140">Not supported</span></span>  <br/> |
|<span data-ttu-id="eaa3f-141">Outlook for Mac</span><span class="sxs-lookup"><span data-stu-id="eaa3f-141">Outlook for Mac</span></span>  <br/> |<span data-ttu-id="eaa3f-142">支持与 Exchange Online 存档配合使用。<sup>3</sup></span><span class="sxs-lookup"><span data-stu-id="eaa3f-142">Supported for use with Exchange Online Archiving.<sup>3</sup></span></span> <br/> |
|<span data-ttu-id="eaa3f-143">Microsoft Office Entourage 2008 Web Services Edition</span><span class="sxs-lookup"><span data-stu-id="eaa3f-143">Microsoft Office Entourage 2008 Web Services Edition</span></span>  <br/> |<span data-ttu-id="eaa3f-144">不支持</span><span class="sxs-lookup"><span data-stu-id="eaa3f-144">Not supported</span></span>  <br/> |
|<span data-ttu-id="eaa3f-145">IMAP 和 POP</span><span class="sxs-lookup"><span data-stu-id="eaa3f-145">IMAP and POP</span></span>  <br/> |<span data-ttu-id="eaa3f-146">不支持</span><span class="sxs-lookup"><span data-stu-id="eaa3f-146">Not supported</span></span>  <br/> |
|<span data-ttu-id="eaa3f-147">Exchange ActiveSync（移动设备）</span><span class="sxs-lookup"><span data-stu-id="eaa3f-147">Exchange ActiveSync (Mobile devices)</span></span>  <br/> |<span data-ttu-id="eaa3f-148">不支持</span><span class="sxs-lookup"><span data-stu-id="eaa3f-148">Not supported</span></span>  <br/> |
   
> [!NOTE]
> <span data-ttu-id="eaa3f-149"><sup>1</sup> 不支持 Microsoft Office Standard 随附的 Outlook。</span><span class="sxs-lookup"><span data-stu-id="eaa3f-149"><sup>1</sup> Outlook included with Microsoft Office Standard is not supported.</span></span> <span data-ttu-id="eaa3f-150">若要了解详细信息，请参阅 [License requirements for Personal Archive and retention policies](https://go.microsoft.com/fwlink/?LinkId=389396)（个人存档和保留策略的许可证要求）。</span><span class="sxs-lookup"><span data-stu-id="eaa3f-150">To learn more, see [License requirements for Personal Archive and retention policies](https://go.microsoft.com/fwlink/?LinkId=389396).</span></span><span data-ttu-id="eaa3f-151"> > <sup>2</sup> 必须更新才能启用存档支持。</span><span class="sxs-lookup"><span data-stu-id="eaa3f-151"> > <sup>2</sup> Requires update to enable archiving support.</span></span> <span data-ttu-id="eaa3f-152">Outlook 2007 用户无法查看保留或存档策略，也无法将其应用于存档邮箱中的项，而必须依赖管理员预配的策略。</span><span class="sxs-lookup"><span data-stu-id="eaa3f-152">Outlook 2007 users cannot view or apply retention or archive policies to items in their archive mailboxes; they must rely on administrator-provisioned policies.</span></span> <span data-ttu-id="eaa3f-153">此外，Outlook 2007 用户无法同时搜索本地邮箱和存档。</span><span class="sxs-lookup"><span data-stu-id="eaa3f-153">Additionally, Outlook 2007 users cannot search the on-premises mailbox and the archive at the same time.</span></span><span data-ttu-id="eaa3f-154"> > <sup>3</sup>不能使用 outlook 2016 for mac 或 outlook for mac 将文件夹、日历项目、联系人、任务或笔记移动或复制到存档中, 或在存档邮箱中查看这些项目 (如果以前使用任何其他版本的 Outlook 将其移动到该位置) (如适用于 Windows 的 Outlook 2016)。</span><span class="sxs-lookup"><span data-stu-id="eaa3f-154"> > <sup>3</sup> You can't use Outlook 2016 for Mac or Outlook for Mac to move or copy folders, calendar items, contacts, tasks, or notes to your archive, or view them in the archive mailbox, if the items were previously moved there by using any other version of Outlook (such as Outlook 2016 for Windows).</span></span> <span data-ttu-id="eaa3f-155">有关详细信息, 请参阅[使用适用于 Mac 的 Outlook 2016 的在线存档](https://support.office.com/en-us/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238)。</span><span class="sxs-lookup"><span data-stu-id="eaa3f-155">For more information, see [Use your online archive with Outlook 2016 for Mac](https://support.office.com/en-us/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238).</span></span> 
  
## <a name="outlook-web-app"></a><span data-ttu-id="eaa3f-156">Outlook Web App</span><span class="sxs-lookup"><span data-stu-id="eaa3f-156">Outlook Web App</span></span>

<span data-ttu-id="eaa3f-p109">Outlook Web App 是用于 Exchange Online、基于 Web 的 Outlook 电子邮件程序版本。无论用户是在家里、在办公室或是在路上连接到 Internet，都可以通过 Outlook Web App 访问电子邮件。</span><span class="sxs-lookup"><span data-stu-id="eaa3f-p109">Outlook Web App is a web-based version of the Outlook email program that is used with Exchange Online. Wherever users are connected to the Internet—at home, at the office, or on the road—they can access their email through Outlook Web App.</span></span>
  
<span data-ttu-id="eaa3f-p110">用户可以（使用相同的 URL）通过登录到本地 Outlook Web App 来访问其存档。存档显示在 Outlook Web App 中的主邮箱旁边。没有直接从 Outlook Web App 访问存档的显式方法。</span><span class="sxs-lookup"><span data-stu-id="eaa3f-p110">Users can access their archive by signing in to Outlook Web App on-premises (using the same URL). The archive appears alongside their primary mailbox in Outlook Web App. There is no explicit way to access the archive directly from Outlook Web App.</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="eaa3f-162">功能可用性</span><span class="sxs-lookup"><span data-stu-id="eaa3f-162">Feature Availability</span></span>

<span data-ttu-id="eaa3f-163">若要查看在各个 Office 365 计划、独立选项和内部部署解决方案之间的功能可用性，请参阅 [Exchange Online Archiving 服务说明](exchange-online-archiving-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="eaa3f-163">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Archiving Service Description](exchange-online-archiving-service-description.md).</span></span>
  

