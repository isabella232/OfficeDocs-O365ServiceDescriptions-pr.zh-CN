---
title: 客户端和移动设备
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
ms.openlocfilehash: a09609e81d9d179dcd156db886913d3124b2e16f
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132966"
---
# <a name="clients-and-mobile-devices"></a><span data-ttu-id="a13e5-102">客户端和移动设备</span><span class="sxs-lookup"><span data-stu-id="a13e5-102">Clients and mobile devices</span></span>

## <a name="microsoft-outlook"></a><span data-ttu-id="a13e5-103">Microsoft Outlook</span><span class="sxs-lookup"><span data-stu-id="a13e5-103">Microsoft Outlook</span></span>

<span data-ttu-id="a13e5-104">Microsoft Outlook 是一个电子邮件程序，其中包括对日历、联系人、任务和以下关键功能的支持：</span><span class="sxs-lookup"><span data-stu-id="a13e5-104">Microsoft Outlook is an email program that includes support for calendar, contacts, tasks, and the following key features:</span></span>
  
- <span data-ttu-id="a13e5-105">**MAPI OVER HTTP**通过 HTTP 的邮件应用程序接口（MAPI）允许 Outlook 用户从其组织的防火墙外部连接到 internet 上的 Exchange Online 邮箱。</span><span class="sxs-lookup"><span data-stu-id="a13e5-105">**MAPI over HTTP** Messaging Application Program Interface (MAPI) over HTTP allows Outlook users to connect to Exchange Online mailboxes over the internet from outside their organization's firewall.</span></span> <span data-ttu-id="a13e5-106">MAPI over HTTP，适用于 Outlook 无处不在的长期替换。</span><span class="sxs-lookup"><span data-stu-id="a13e5-106">MAPI over HTTP, the long term replacement for Outlook Anywhere.</span></span> <span data-ttu-id="a13e5-107">此连接方法提供改进的连接弹性、更安全的登录、可扩展性以及 IT 和支持的增强功能。</span><span class="sxs-lookup"><span data-stu-id="a13e5-107">This connectivity method offers improved connection resiliency, more secure sign-in, extensibility, as well as enhancements for IT and support.</span></span> <span data-ttu-id="a13e5-108">若要了解详细信息，请参阅[RPC OVER http 在 Office 365](https://go.microsoft.com/fwlink/?linkid=863890)和[MAPI over http](https://go.microsoft.com/fwlink/?linkid=393041)中达到支持的结尾。</span><span class="sxs-lookup"><span data-stu-id="a13e5-108">To learn more, see [RPC over HTTP reaches end of support in Office 365](https://go.microsoft.com/fwlink/?linkid=863890) and [MAPI over HTTP](https://go.microsoft.com/fwlink/?linkid=393041).</span></span>

- <span data-ttu-id="a13e5-p102">**自动发现** 自动发现服务功能自动配置 Outlook 以用于 Exchange Online。首次使用电子邮件地址和密码登录时，Outlook 用户可以直接从 Exchange Online 收到他们的所需配置文件设置。这些设置可以使用创建和维护用户配置文件所需的信息自动更新 Outlook 客户端。使用自动发现服务需要 SSL 证书。此 SSL 证书仅限于单个主 SSL 域。</span><span class="sxs-lookup"><span data-stu-id="a13e5-p102">**Autodiscover** The Autodiscover service feature automatically configures Outlook to work with Exchange Online. Outlook users can receive their required profile settings directly from Exchange Online the first time they sign in with their email address and password. These settings automatically update the Outlook client with the information necessary to create and maintain the user's profile. An SSL certificate is required to use the Autodiscover service. This SSL certificate is limited to a single primary SSL domain.</span></span> 

- <span data-ttu-id="a13e5-114">**缓存 Exchange 模式**当 Outlook 用户未连接到 internet 时，缓存 Exchange 模式功能允许 Outlook 用户访问其 Exchange Online 邮箱的本地副本。</span><span class="sxs-lookup"><span data-stu-id="a13e5-114">**Cached Exchange Mode** The Cached Exchange Mode feature allows Outlook users to access local copies of their Exchange Online mailboxes when they are not connected to the internet.</span></span> <span data-ttu-id="a13e5-115">缓存 Exchange 模式在 Outlook 中保存用户 Exchange 邮箱的客户端副本，并与电子邮件服务器自动同步该副本。</span><span class="sxs-lookup"><span data-stu-id="a13e5-115">Cached Exchange Mode retains a client-side copy of users' Exchange mailboxes in Outlook and automatically synchronizes this copy with the email server.</span></span> <span data-ttu-id="a13e5-116">我们建议在缓存 Exchange 模式中使用 Outlook，因为它提供脱机访问并帮助提供响应用户体验，即使客户端和服务器之间的网络条件不理想。</span><span class="sxs-lookup"><span data-stu-id="a13e5-116">We recommend using Outlook in Cached Exchange Mode because it provides offline access and helps to provide a responsive user experience even when network conditions between the client and the server are not ideal.</span></span> 

<span data-ttu-id="a13e5-p104">默认情况下，所有用户启用 Outlook 访问。管理员可以通过 Windows PowerShell 禁用对特定用户的访问权限。我们建议使用最新版本的 Outlook装有最新的 service pack以访问 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="a13e5-p104">By default, Outlook access is enabled for all users. Administrators can disable access for specific users or groups through Windows PowerShell. We recommend using the latest version of Outlook—with the latest service pack installed—to access Exchange Online.</span></span> 
  
<span data-ttu-id="a13e5-120">有关 Exchange 2016 和 Exchange Online 支持的 Outlook 客户端的信息，请参阅[Office 的系统要求](https://products.office.com/office-system-requirements)。</span><span class="sxs-lookup"><span data-stu-id="a13e5-120">For information about which Outlook clients are supported by Exchange 2016 and Exchange Online, see [System Requirements for Office](https://products.office.com/office-system-requirements).</span></span> 

<span data-ttu-id="a13e5-121">Microsoft 365 旨在适用于 Office 的最新浏览器和版本。</span><span class="sxs-lookup"><span data-stu-id="a13e5-121">Microsoft 365 is designed to work with the latest browsers and versions of Office.</span></span> <span data-ttu-id="a13e5-122">如果使用的是旧版不在主流支持中的浏览器和 Office 版本：</span><span class="sxs-lookup"><span data-stu-id="a13e5-122">If you use older browsers and versions of Office that aren't in mainstream support:</span></span>

- <span data-ttu-id="a13e5-123">Microsoft 不会有意阻止您连接到该服务，但您的体验质量可能会随着时间的推移而降低。</span><span class="sxs-lookup"><span data-stu-id="a13e5-123">Microsoft won't deliberately prevent you from connecting to the service, but the quality of your experience may diminish over time.</span></span>
- <span data-ttu-id="a13e5-124">Microsoft 不会提供软件更新来解决与安全无关的问题。</span><span class="sxs-lookup"><span data-stu-id="a13e5-124">Microsoft won't provide software updates to resolve non-security related problems.</span></span>

> [!IMPORTANT]
>  <span data-ttu-id="a13e5-125">Outlook 不作为 Exchange Online 订阅价格一部分提供。</span><span class="sxs-lookup"><span data-stu-id="a13e5-125">Outlook is not provided as part of the Exchange Online subscription price.</span></span> <span data-ttu-id="a13e5-126">Microsoft 365 企业版应用程序（包括 Microsoft Outlook）包含在一些计划中，可以作为单独的订阅进行购买。</span><span class="sxs-lookup"><span data-stu-id="a13e5-126">Microsoft 365 Apps for enterprise (which includes Microsoft Outlook) is included in some plans and can be purchased as a separate subscription.</span></span> <span data-ttu-id="a13e5-127">如果您使用 POP 连接到 Exchange Online 电子邮件帐户，您将看到以下限制： > 无日历信息 > 无 > 全局地址列表 > 没有推送电子邮件 > 通过 POP 连接时，所有邮件都将下载到客户端，并且在多台计算机或设备（如膝上型电脑和手机之间）之间不会进行任何同步。</span><span class="sxs-lookup"><span data-stu-id="a13e5-127">You will see the following limitations if you use POP to connect to an Exchange Online email account: >  No calendar information >  No free/busy information >  No Global Address List >  No push email >  When connecting through POP, all messages will be downloaded to the client and there will be no synchronization between multiple computers or devices (such as between a laptop and a phone).</span></span> 
  
## <a name="outlook-on-the-web"></a><span data-ttu-id="a13e5-128">Web 上的 Outlook</span><span class="sxs-lookup"><span data-stu-id="a13e5-128">Outlook on the web</span></span>

<span data-ttu-id="a13e5-129">Outlook 网页版是 Web 版 Outlook 电子邮件程序，可与 Exchange Online 结合使用。</span><span class="sxs-lookup"><span data-stu-id="a13e5-129">Outlook on the web is a web-based version of the Outlook email program that is used with Exchange Online.</span></span> <span data-ttu-id="a13e5-130">它允许用户通过 web 浏览器访问其电子邮件、日历和联系人（无论它们连接到 internet）。</span><span class="sxs-lookup"><span data-stu-id="a13e5-130">It lets users access their email, calendar, and contacts through a web browser from wherever they connect to the internet.</span></span> <span data-ttu-id="a13e5-131">若要了解支持的浏览器，请参阅 [Outlook 网页版支持的浏览器（适用于企业）](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006)。</span><span class="sxs-lookup"><span data-stu-id="a13e5-131">For information about supported browsers, see [Supported browsers for Outlook on the web for business](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006).</span></span>
  
<span data-ttu-id="a13e5-132">Outlook 网页版具有两个客户端版本，这两个都可用于 Exchange Online：</span><span class="sxs-lookup"><span data-stu-id="a13e5-132">Outlook on the web comes in two client versions, both of which can be used with Exchange Online:</span></span>
  
- <span data-ttu-id="a13e5-133">**Outlook 网页版** 标准的 Outlook 网页版为 Exchange Online 用户提供最类似于 Outlook 用户的邮件体验。</span><span class="sxs-lookup"><span data-stu-id="a13e5-133">**Outlook on the web** The standard version of Outlook on the web provides Exchange Online users with a messaging experience most similar to that of Outlook users.</span></span> <span data-ttu-id="a13e5-134">它支持大部分新版 Web 浏览器，同时经过优化可用于平板电脑和智能电话以及台式机和笔记本电脑。</span><span class="sxs-lookup"><span data-stu-id="a13e5-134">It supports most newer web browsers and is optimized for use on tablets and smartphones as well as desktops and laptops.</span></span> <span data-ttu-id="a13e5-135">用户可以阅读和发送邮件、整理联系人，并能安排约会和会议。</span><span class="sxs-lookup"><span data-stu-id="a13e5-135">Users can read and send messages, organize contacts, and schedule appointments and meetings.</span></span> <span data-ttu-id="a13e5-136">基于活动的默认超时设置为 6 小时，但 [管理员可在 Windows PowerShell 中配置](https://go.microsoft.com/fwlink/p/?LinkId=399155)为介于 5 分钟到 8 小时中的一个值。</span><span class="sxs-lookup"><span data-stu-id="a13e5-136">The default activity-based time-out is set at six hours, but it can be [configured by an administrator in Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) from 5 minutes to 8 hours.</span></span> <span data-ttu-id="a13e5-137">此超时取决于用户在 web 应用程序中的交互，例如，选择一个按钮或选择一封邮件。</span><span class="sxs-lookup"><span data-stu-id="a13e5-137">This time-out depends on user interactions within the web app, such as selecting a button or selecting a message.</span></span> <span data-ttu-id="a13e5-138">此外，还有单独的安全驱动超时，此超时不可配置，无论用户活动如何都会发生。</span><span class="sxs-lookup"><span data-stu-id="a13e5-138">There is also a separate security-driven time-out, which is not configurable and will occur regardless of user activity.</span></span> <span data-ttu-id="a13e5-139">如果用户登录了 8 小时，OWA 会自动注销用户，并要求其重新进行身份验证。</span><span class="sxs-lookup"><span data-stu-id="a13e5-139">If a user is logged in for 8 hours, OWA will automatically log the user out and ask for re-authentication.</span></span> 

- <span data-ttu-id="a13e5-140">**轻型 Outlook 网页版** 使用轻型 Outlook 网页版，Exchange Online 用户可以使用几乎所有 Web 浏览器访问邮箱。</span><span class="sxs-lookup"><span data-stu-id="a13e5-140">**The light version of Outlook on the web** The light version of Outlook on the web provides Exchange Online users access to the mailbox using almost any web browser.</span></span> <span data-ttu-id="a13e5-141">用户可以阅读和发送邮件、整理联系人，并能安排约会和会议。</span><span class="sxs-lookup"><span data-stu-id="a13e5-141">Users can read and send messages, organize contacts, and schedule appointments and meetings.</span></span> <span data-ttu-id="a13e5-142">基于活动的默认超时设置为 6 小时，但 [管理员可在 Windows PowerShell 中配置](https://go.microsoft.com/fwlink/p/?LinkId=399155)为介于 5 分钟到 8 小时中的一个值。</span><span class="sxs-lookup"><span data-stu-id="a13e5-142">The default activity-based time-out is set at six hours, but it can be [configured by an administrator in Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) from 5 minutes to 8 hours.</span></span> <span data-ttu-id="a13e5-143">此超时取决于用户在 web 应用程序中的交互，例如，选择一个按钮或选择一封邮件。</span><span class="sxs-lookup"><span data-stu-id="a13e5-143">This time-out depends on user interactions within the web app, such as selecting a button or selecting a message.</span></span> <span data-ttu-id="a13e5-144">此外，还有单独的安全驱动超时，此超时不可配置，无论用户活动如何都会发生。</span><span class="sxs-lookup"><span data-stu-id="a13e5-144">There is also a separate security-driven time-out, which is not configurable and will occur regardless of user activity.</span></span> <span data-ttu-id="a13e5-145">如果用户登录了 8 小时，OWA 会自动注销用户，并要求其重新进行身份验证。</span><span class="sxs-lookup"><span data-stu-id="a13e5-145">If a user is logged in for 8 hours, the light version of OWA will automatically log the user out and ask for re-authentication.</span></span> 

<span data-ttu-id="a13e5-146">Outlook 网页版还提供移动版本。</span><span class="sxs-lookup"><span data-stu-id="a13e5-146">Outlook on the web also is available in mobile versions.</span></span> <span data-ttu-id="a13e5-147">有关详细信息，请参阅此[此页面](https://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409)。</span><span class="sxs-lookup"><span data-stu-id="a13e5-147">For more information, see [this page](https://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409).</span></span>
  
## <a name="outlook-for-mac"></a><span data-ttu-id="a13e5-148">Outlook for Mac</span><span class="sxs-lookup"><span data-stu-id="a13e5-148">Outlook for Mac</span></span>

<span data-ttu-id="a13e5-149">Exchange Online 支持 Microsoft Outlook for Mac，它提供电子邮件、日历、通讯簿、任务列表和便笺列表。</span><span class="sxs-lookup"><span data-stu-id="a13e5-149">Exchange Online supports Microsoft Outlook for Mac, which provides email, calendar, an address book, a task list, and a note list.</span></span>
  
## <a name="outlook-for-ios-android-and-windows-phone"></a><span data-ttu-id="a13e5-150">适用于 iOS、Android 和 Windows Phone 的 Outlook</span><span class="sxs-lookup"><span data-stu-id="a13e5-150">Outlook for iOS, Android, and Windows Phone</span></span>

<span data-ttu-id="a13e5-151">Exchange Online 适用于适用于 iOS、Android 和 Windows Phone 的 Outlook 应用程序。</span><span class="sxs-lookup"><span data-stu-id="a13e5-151">Exchange Online works with Outlook apps available for iOS, Android, and Windows Phone.</span></span> <span data-ttu-id="a13e5-152">在这些设备中的任何设备上，使用应用商店查找 Outlook 应用程序。</span><span class="sxs-lookup"><span data-stu-id="a13e5-152">On any of these devices, use the app store to find the Outlook app.</span></span> <span data-ttu-id="a13e5-153">以下是移动 OS 的细目分类。</span><span class="sxs-lookup"><span data-stu-id="a13e5-153">Here's a breakdown by mobile OS.</span></span>
  
|||||
|:-----|:-----|:-----|:-----|
|<span data-ttu-id="a13e5-154">设备</span><span class="sxs-lookup"><span data-stu-id="a13e5-154">Device</span></span>  <br/> |<span data-ttu-id="a13e5-155">Android</span><span class="sxs-lookup"><span data-stu-id="a13e5-155">Android</span></span>  <br/> |<span data-ttu-id="a13e5-156">iOS</span><span class="sxs-lookup"><span data-stu-id="a13e5-156">iOS</span></span>  <br/> |<span data-ttu-id="a13e5-157">Windows Phone</span><span class="sxs-lookup"><span data-stu-id="a13e5-157">Windows Phone</span></span>  <br/> |
|<span data-ttu-id="a13e5-158">Outlook 移动应用可用性</span><span class="sxs-lookup"><span data-stu-id="a13e5-158">Outlook mobile app availability</span></span>  <br/> |<span data-ttu-id="a13e5-159">是</span><span class="sxs-lookup"><span data-stu-id="a13e5-159">Yes</span></span>  <br/> [<span data-ttu-id="a13e5-160">获取适用于 Android 的 Outlook</span><span class="sxs-lookup"><span data-stu-id="a13e5-160">Get Outlook for Android</span></span>](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |<span data-ttu-id="a13e5-161">是</span><span class="sxs-lookup"><span data-stu-id="a13e5-161">Yes</span></span>  <br/> [<span data-ttu-id="a13e5-162">获取适用于 iOS 的 Outlook</span><span class="sxs-lookup"><span data-stu-id="a13e5-162">Get Outlook for iOS</span></span>](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |<span data-ttu-id="a13e5-163">内置</span><span class="sxs-lookup"><span data-stu-id="a13e5-163">Built-in</span></span>  <br/> |
|<span data-ttu-id="a13e5-164">与 Exchange Online 兼容的内置电子邮件应用程序</span><span class="sxs-lookup"><span data-stu-id="a13e5-164">Built-in email apps compatible with Exchange Online</span></span>  <br/> |<span data-ttu-id="a13e5-165">Gmail app/Samsung 电子邮件应用程序</span><span class="sxs-lookup"><span data-stu-id="a13e5-165">Gmail app/Samsung Email app</span></span>  <br/> |<span data-ttu-id="a13e5-166">iOS 邮件应用程序</span><span class="sxs-lookup"><span data-stu-id="a13e5-166">iOS Mail app</span></span>  <br/> |<span data-ttu-id="a13e5-167">Outlook 邮件、日历、联系人</span><span class="sxs-lookup"><span data-stu-id="a13e5-167">Outlook Mail, calendar, contacts</span></span>  <br/> |
|<span data-ttu-id="a13e5-168">更多信息</span><span class="sxs-lookup"><span data-stu-id="a13e5-168">More information</span></span>  <br/> |[<span data-ttu-id="a13e5-169">Android 手机设置</span><span class="sxs-lookup"><span data-stu-id="a13e5-169">Android mobile setup</span></span>](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[<span data-ttu-id="a13e5-170">iPhone 或 iPad 安装程序</span><span class="sxs-lookup"><span data-stu-id="a13e5-170">iPhone or iPad setup</span></span>](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[<span data-ttu-id="a13e5-171">Windows Phone 安装程序</span><span class="sxs-lookup"><span data-stu-id="a13e5-171">Windows Phone setup</span></span>](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |

<span data-ttu-id="a13e5-172">此外，还提供了有关将 Exchange Online 与设备（包括 Blackberry）结合使用的选项。</span><span class="sxs-lookup"><span data-stu-id="a13e5-172">There are also options for using Exchange Online with devices, including Blackberry.</span></span>
  
### <a name="feature-availability"></a><span data-ttu-id="a13e5-173">功能可用性</span><span class="sxs-lookup"><span data-stu-id="a13e5-173">Feature availability</span></span>

<span data-ttu-id="a13e5-174">Outlook 为用户提供了从新式移动应用程序获得的快速、直观的电子邮件和日历体验，同时也是唯一可提供最佳功能支持的应用程序。</span><span class="sxs-lookup"><span data-stu-id="a13e5-174">Outlook gives users the fast, intuitive email and calendar experience that they expect from a modern mobile app, while being the only app to provide support for the best features.</span></span> <span data-ttu-id="a13e5-175">它是唯一专为支持完整的 Microsoft 体验而设计的电子邮件应用程序，为用户提供桌面到移动的一致体验。</span><span class="sxs-lookup"><span data-stu-id="a13e5-175">It is the only email app specifically designed to support the full Microsoft experience, giving users a coherent experience from desktop to mobile.</span></span> <span data-ttu-id="a13e5-176">Outlook 与 Intune、企业移动性和安全性以及 Exchange 控件相集成，以保持数据和用户安全。</span><span class="sxs-lookup"><span data-stu-id="a13e5-176">Outlook is integrated with Intune, enterprise mobility and security, and Exchange controls to keep data and users safe.</span></span>
  
<span data-ttu-id="a13e5-177">通过 Outlook，用户可以：</span><span class="sxs-lookup"><span data-stu-id="a13e5-177">With Outlook, users can:</span></span>
  
- <span data-ttu-id="a13e5-178">从移动设备管理其全天。</span><span class="sxs-lookup"><span data-stu-id="a13e5-178">Manage their entire day from a mobile device.</span></span>

- <span data-ttu-id="a13e5-179">连接到需要提高工作效率的应用程序和服务，同时保持其工作和个人信息的安全。</span><span class="sxs-lookup"><span data-stu-id="a13e5-179">Connect to the apps and services they need to be productive, while keeping their work and personal information separate and secure.</span></span>

<span data-ttu-id="a13e5-180">使用 Outlook for iOS、Outlook for Android 或 Outlook for Windows Phone，用户可以：</span><span class="sxs-lookup"><span data-stu-id="a13e5-180">With Outlook for iOS, Outlook for Android, or Outlook for Windows Phone, users can:</span></span> 
  
- <span data-ttu-id="a13e5-181">受益于重点收件箱的优先级重要电子邮件</span><span class="sxs-lookup"><span data-stu-id="a13e5-181">Benefit from a focused inbox that priorities important email</span></span>

- <span data-ttu-id="a13e5-182">自定义轻扫手势以适应其独特的电子邮件习惯</span><span class="sxs-lookup"><span data-stu-id="a13e5-182">Customize swipe gestures to match their unique email habits</span></span>

- <span data-ttu-id="a13e5-183">创建可直接添加到日历中的旅行路线，并提供概览的关键信息</span><span class="sxs-lookup"><span data-stu-id="a13e5-183">Create travel itineraries that can be added directly to the calendar, with key information available at a glance</span></span>

- <span data-ttu-id="a13e5-184">从收件箱到会议的 RSVP。</span><span class="sxs-lookup"><span data-stu-id="a13e5-184">RSVP to meetings from the inbox.</span></span>

- <span data-ttu-id="a13e5-185">在电子邮件和日历约会中使用直观图标帮助他们快速处理信息</span><span class="sxs-lookup"><span data-stu-id="a13e5-185">Use intuitive icons in email and calendar appointments that help them process information quickly</span></span>

- <span data-ttu-id="a13e5-186">在所有设备中使用一致和熟悉的 Outlook 体验</span><span class="sxs-lookup"><span data-stu-id="a13e5-186">Use a consistent and familiar Outlook experience across all devices</span></span>

- <span data-ttu-id="a13e5-187">轻松启动和加入日历中的 Skype 会议</span><span class="sxs-lookup"><span data-stu-id="a13e5-187">Easily launch and join Skype meetings from the calendar</span></span>

- <span data-ttu-id="a13e5-188">阅读和响应 IRM 加密和受保护的电子邮件</span><span class="sxs-lookup"><span data-stu-id="a13e5-188">Read and respond to IRM encrypted and protected emails</span></span>

- <span data-ttu-id="a13e5-189">共享 OneDrive for Business 中存储的文件</span><span class="sxs-lookup"><span data-stu-id="a13e5-189">Share files stored in OneDrive for Business</span></span>

- <span data-ttu-id="a13e5-190">通过点击设置自动答复</span><span class="sxs-lookup"><span data-stu-id="a13e5-190">Set Automatic Replies with a tap</span></span>

- <span data-ttu-id="a13e5-191">查看和管理共享和委派的日历</span><span class="sxs-lookup"><span data-stu-id="a13e5-191">View and manage shared and delegated calendars</span></span>

- <span data-ttu-id="a13e5-192">通过几分路器搜索其公司的全球通讯簿</span><span class="sxs-lookup"><span data-stu-id="a13e5-192">Search their company's global address list with a few taps</span></span>

- <span data-ttu-id="a13e5-193">查看同事的可用性并安排适用于每个人的会议时间</span><span class="sxs-lookup"><span data-stu-id="a13e5-193">View coworker's availability and schedule a meeting time that works for everyone</span></span>

- <span data-ttu-id="a13e5-194">请参阅被邀请者接受、暂定和拒绝状态</span><span class="sxs-lookup"><span data-stu-id="a13e5-194">See invitees accept, tentative, and decline status</span></span>

- <span data-ttu-id="a13e5-195">从电话中共享日历</span><span class="sxs-lookup"><span data-stu-id="a13e5-195">Share calendars right from their phones</span></span>

- <span data-ttu-id="a13e5-196">从日历中启动和加入 Skype 会议</span><span class="sxs-lookup"><span data-stu-id="a13e5-196">Start and join Skype meetings right from a calendar</span></span>

- <span data-ttu-id="a13e5-197">在一个位置访问工作和个人日历，而无需切换应用程序</span><span class="sxs-lookup"><span data-stu-id="a13e5-197">Access work and personal calendars in one place, without switching apps</span></span>
    
## <a name="exchange-activesync"></a><span data-ttu-id="a13e5-198">Exchange ActiveSync</span><span class="sxs-lookup"><span data-stu-id="a13e5-198">Exchange ActiveSync</span></span>

<span data-ttu-id="a13e5-199">Exchange Online 支持 Microsoft Exchange ActiveSync 协议，这将在移动设备和 Exchange Online 之间同步邮箱，以便用户可以随身访问他们的电子邮件、日历、联系人和任务。</span><span class="sxs-lookup"><span data-stu-id="a13e5-199">Exchange Online supports the Microsoft Exchange ActiveSync protocol, which synchronizes mailbox data between mobile devices and Exchange Online, so users can access their email, calendar, contacts, and tasks on the go.</span></span>
  
<span data-ttu-id="a13e5-200">各种移动设备均使用 Exchange ActiveSync，包括 Microsoft Windows Phone、Apple iPhone 和 iPad 以及 Android 手机和平板电脑。</span><span class="sxs-lookup"><span data-stu-id="a13e5-200">A wide range of mobile devices work with Exchange ActiveSync, including Microsoft Windows Phone, Apple iPhone and iPad, and Android phones and tablets.</span></span> <span data-ttu-id="a13e5-201">除了移动电话和设备，Windows Phone 中的邮件应用程序还使用 Exchange ActiveSync 连接到 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="a13e5-201">In addition to mobile phones and devices, the Mail application in Windows Phone uses Exchange ActiveSync to connect to Exchange Online.</span></span> <span data-ttu-id="a13e5-202">有关当前 Exchange ActiveSync 被许可人的完整列表，请访问 Exchange ActiveSync 许可网站。</span><span class="sxs-lookup"><span data-stu-id="a13e5-202">A complete list of current Exchange ActiveSync licensees is available at the Exchange ActiveSync Licensing site.</span></span>
  
<span data-ttu-id="a13e5-203">有关 Exchange ActiveSync 的详细信息，请参阅[Exchange activesync](https://go.microsoft.com/fwlink/p/?LinkId=271792)。</span><span class="sxs-lookup"><span data-stu-id="a13e5-203">For more information about Exchange ActiveSync, see [Exchange ActiveSync](https://go.microsoft.com/fwlink/p/?LinkId=271792).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="a13e5-204">每个邮箱的 Exchange ActiveSync 设备的最大数量为 100。</span><span class="sxs-lookup"><span data-stu-id="a13e5-204">The maximum number of Exchange ActiveSync devices per mailbox is 100.</span></span> 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a><span data-ttu-id="a13e5-205">使用 Exchange Web Services（EWS）开发的应用程序</span><span class="sxs-lookup"><span data-stu-id="a13e5-205">Applications developed with Exchange Web Services (EWS)</span></span>

 <span data-ttu-id="a13e5-206">通过使用 Exchange Web 服务 (EWS) 或 EWS 托管 API 开发的应用程序，管理员可以访问使用 Exchange Online 存储的、来自本地、Azure 或其他托管服务运行的应用程序的数据。</span><span class="sxs-lookup"><span data-stu-id="a13e5-206">Applications developed using Exchange Web Services (EWS) or the EWS Managed API let administrators access data stored with Exchange Online from applications that are running on-premises, in Azure, or in other hosted services.</span></span> 
  
<span data-ttu-id="a13e5-207">若要详细了解使用 Exchange Web 服务开发的应用程序，请参阅 [Exchange Web 服务](https://go.microsoft.com/fwlink/?LinkId=325346)。</span><span class="sxs-lookup"><span data-stu-id="a13e5-207">For more information on applications developed with Exchange Web Services, see [Web Services in Exchange](https://go.microsoft.com/fwlink/?LinkId=325346).</span></span>
  
## <a name="pop-and-imap"></a><span data-ttu-id="a13e5-208">POP 和 IMAP</span><span class="sxs-lookup"><span data-stu-id="a13e5-208">POP and IMAP</span></span>

<span data-ttu-id="a13e5-p114">Exchange Online 通过 POP3 和 IMAP4 协议支持邮箱访问。POP 和 IMAP 访问要求使用 SSL 加密。默认情况下，为所有用户启用 POP。用户可以在 Outlook 网页版中查看他们的 POP 和 IMAP 连接设置。管理员可以在每个用户的基础上禁用 POP 和 IMAP 访问。</span><span class="sxs-lookup"><span data-stu-id="a13e5-p114">Exchange Online supports mailbox access through both POP3 and IMAP4 protocols. POP and IMAP access requires encryption using SSL. POP is enabled by default for all users. Users can view their POP and IMAP connection settings in Outlook on the web. Administrators can disable POP and IMAP access on a per-user basis.</span></span>
  
<span data-ttu-id="a13e5-214">有关 POP3 和 IMAP4 连接性的详细信息，请参阅 [POP3 和 IMAP4](https://go.microsoft.com/fwlink/p/?LinkId=272070)。</span><span class="sxs-lookup"><span data-stu-id="a13e5-214">For more information about POP3 and IMAP4 connectivity, see [POP3 and IMAP4](https://go.microsoft.com/fwlink/p/?LinkId=272070).</span></span>
  
## <a name="smtp"></a><span data-ttu-id="a13e5-215">SMTP</span><span class="sxs-lookup"><span data-stu-id="a13e5-215">SMTP</span></span>

<span data-ttu-id="a13e5-p115">简单邮件传输协议 (SMTP) 用于为通过 IMAP 或 POP 连接到 Exchange Online 的客户端发送出站邮件。它是通过 Exchange Server 路由和递送的主协议。Exchange Online 支持两种类型的 SMTP 中继服务，用于需要 SMTP 邮件提交的授权内部客户应用程序：</span><span class="sxs-lookup"><span data-stu-id="a13e5-p115">Simple Mail Transfer Protocol (SMTP) is used to send outbound mail for clients that connect to Exchange Online through IMAP or POP. It is the primary protocol for routing and delivery through Exchange Server. Exchange Online supports two types of SMTP relay services for authorized internal customer applications that require SMTP mail submission:</span></span>
  
- <span data-ttu-id="a13e5-219">SMTP 邮件提交给托管环境内的用户。</span><span class="sxs-lookup"><span data-stu-id="a13e5-219">SMTP message submission to users inside the managed environment.</span></span>

- <span data-ttu-id="a13e5-220">通过身份验证的 SMTP 邮件中继到托管环境外的地址。</span><span class="sxs-lookup"><span data-stu-id="a13e5-220">Authenticated SMTP message relay to addresses outside the managed environment.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="a13e5-p116">授权源服务器的 IP 地址需要允许 SMTP 中继。当使用 SMTP 发送电子邮件时需要传输层安全性 (TLS) 加密和身份验证。</span><span class="sxs-lookup"><span data-stu-id="a13e5-p116">IP addresses for authorized source servers are required to allow SMTP relay. Transport Layer Security (TLS) encryption and authentication is required when using SMTP to send email.</span></span> 
  
## <a name="blackberryreg-devices"></a><span data-ttu-id="a13e5-223">BlackBerry &reg; 设备</span><span class="sxs-lookup"><span data-stu-id="a13e5-223">BlackBerry&reg; devices</span></span>

<span data-ttu-id="a13e5-224">可通过 Exchange ActiveSync 在 BlackBerry 设备上提供电子邮件 &reg; 。</span><span class="sxs-lookup"><span data-stu-id="a13e5-224">Email is available on BlackBerry&reg; devices via Exchange ActiveSync.</span></span> <span data-ttu-id="a13e5-225">若要了解你的选项是什么，请参阅以下主题：</span><span class="sxs-lookup"><span data-stu-id="a13e5-225">To find out what your options are, see these topics:</span></span>
  
- [<span data-ttu-id="a13e5-226">在 BlackBerry 设备上设置电子邮件</span><span class="sxs-lookup"><span data-stu-id="a13e5-226">Set up email on a BlackBerry device</span></span>](https://go.microsoft.com/fwlink/?linkid=863394)

- [<span data-ttu-id="a13e5-227">在 BlackBerry 设备 7.1 OS 和更低版本上设置电子邮件</span><span class="sxs-lookup"><span data-stu-id="a13e5-227">Set up email on a BlackBerry device 7.1 OS and earlier</span></span>](https://go.microsoft.com/fwlink/?linkid=863403)

<span data-ttu-id="a13e5-228">有关详细信息，请参阅 [BlackBerry](../office-365-platform-service-description/blackberry.md)。</span><span class="sxs-lookup"><span data-stu-id="a13e5-228">For more information, see [BlackBerry](../office-365-platform-service-description/blackberry.md).</span></span>
  
> [!NOTE]
> <span data-ttu-id="a13e5-p118">如果使用的是由中国世纪互联运营的 Office 365，则 BlackBerry 商业云服务 不可用，但是你可以使用 Exchange ActiveSync 设备和 Research in Motion（RIM，BlackBerry 无线电子邮件解决方案）中的产品运行 Blackberry Enterprise Server (BES)。</span><span class="sxs-lookup"><span data-stu-id="a13e5-p118">If you are using Office 365 operated by 21Vianet in China, BlackBerry Business Cloud Services is not available. However, you can use Exchange ActiveSync devices or an offering from Research in Motion (RIM, the BlackBerry wireless email solution) to run Blackberry Enterprise Server (BES).</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="a13e5-231">功能可用性</span><span class="sxs-lookup"><span data-stu-id="a13e5-231">Feature availability</span></span>

<span data-ttu-id="a13e5-232">若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅[Exchange Online 服务说明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="a13e5-232">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online service description](exchange-online-service-description.md).</span></span>
  