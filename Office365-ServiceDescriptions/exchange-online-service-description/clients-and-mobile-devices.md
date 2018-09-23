---
title: 客户端和移动设备
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
ms.openlocfilehash: ad19845f7a06cfb01a74507fdb794813091c1c2b
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035144"
---
# <a name="clients-and-mobile-devices"></a><span data-ttu-id="b97b7-102">客户端和移动设备</span><span class="sxs-lookup"><span data-stu-id="b97b7-102">Clients and Mobile Devices</span></span>

## <a name="microsoft-outlook"></a><span data-ttu-id="b97b7-103">Microsoft Outlook</span><span class="sxs-lookup"><span data-stu-id="b97b7-103">Microsoft Outlook</span></span>

<span data-ttu-id="b97b7-104">Microsoft Outlook 是一个电子邮件程序，包括支持日历、 联系人、 任务和以下关键功能：</span><span class="sxs-lookup"><span data-stu-id="b97b7-104">Microsoft Outlook is an email program that includes support for calendar, contacts, tasks, and the following key features:</span></span>
  
- <span data-ttu-id="b97b7-p101">**MAPI over HTTP**通过 HTTP 消息应用程序接口 (MAPI) 允许 Outlook 用户通过 Internet 从其组织的防火墙之外连接到 Exchange Online 邮箱。MAPI over HTTP，长期替换为 Outlook Anywhere。此连接方法提供了改进了的连接恢复能力、 更安全登录、 扩展性，以及增强 IT 和支持。若要了解详细信息，请参阅[RPC over HTTP 达到结束的 Office 365 中的支持](https://go.microsoft.com/fwlink/?linkid=863890)和[MAPI over HTTP](https://go.microsoft.com/fwlink/?linkid=393041)。</span><span class="sxs-lookup"><span data-stu-id="b97b7-p101">**MAPI over HTTP** Messaging Application Program Interface (MAPI) over HTTP allows Outlook users to connect to Exchange Online mailboxes over the Internet from outside their organization's firewall. MAPI over HTTP, the long term replacement for Outlook Anywhere. This connectivity method offers improved connection resiliency, more secure sign-in, extensibility, as well as enhancements for IT and support. To learn more, see [RPC over HTTP reaches end of support in Office 365](https://go.microsoft.com/fwlink/?linkid=863890) and [MAPI over HTTP](https://go.microsoft.com/fwlink/?linkid=393041).</span></span>
    
- <span data-ttu-id="b97b7-p102">**自动发现** 自动发现服务功能自动配置 Outlook 以用于 Exchange Online。首次使用电子邮件地址和密码登录时，Outlook 用户可以直接从 Exchange Online 收到他们的所需配置文件设置。这些设置可以使用创建和维护用户配置文件所需的信息自动更新 Outlook 客户端。使用自动发现服务需要 SSL 证书。此 SSL 证书仅限于单个主 SSL 域。</span><span class="sxs-lookup"><span data-stu-id="b97b7-p102">**Autodiscover** The Autodiscover service feature automatically configures Outlook to work with Exchange Online. Outlook users can receive their required profile settings directly from Exchange Online the first time they sign in with their email address and password. These settings automatically update the Outlook client with the information necessary to create and maintain the user's profile. An SSL certificate is required to use the Autodiscover service. This SSL certificate is limited to a single primary SSL domain.</span></span> 
    
- <span data-ttu-id="b97b7-p103">**缓存 Exchange 模式** 缓存 Exchange 模式功能允许 Outlook 用户在未连接到互联网时访问其 Exchange Online 邮箱的本地副本。缓存 Exchange 模式在 Outlook 中保存用户 Exchange 邮箱的客户端副本，并与电子邮件服务器自动同步该副本。我们建议在缓存 Exchange 模式中使用 Outlook，因为它提供脱机访问并帮助提供响应用户体验，即使客户端和服务器之间的网络条件不理想。</span><span class="sxs-lookup"><span data-stu-id="b97b7-p103">**Cached Exchange Mode** The Cached Exchange Mode feature allows Outlook users to access local copies of their Exchange Online mailboxes when they are not connected to the Internet. Cached Exchange Mode retains a client-side copy of users' Exchange mailboxes in Outlook and automatically synchronizes this copy with the email server. We recommend using Outlook in Cached Exchange Mode because it provides offline access and helps to provide a responsive user experience even when network conditions between the client and the server are not ideal.</span></span> 
    
<span data-ttu-id="b97b7-p104">默认情况下，所有用户启用 Outlook 访问。管理员可以通过 Windows PowerShell 禁用对特定用户的访问权限。我们建议使用最新版本的 Outlook装有最新的 service pack以访问 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="b97b7-p104">By default, Outlook access is enabled for all users. Administrators can disable access for specific users or groups through Windows PowerShell. We recommend using the latest version of Outlook—with the latest service pack installed—to access Exchange Online.</span></span> 
  
<span data-ttu-id="b97b7-120">若要了解 Exchange 2016 和 Exchange Online 支持的 Outlook 客户端，请参阅 [Exchange 2016 系统要求](https://go.microsoft.com/fwlink/?LinkID=828972)中的"支持的客户端"。</span><span class="sxs-lookup"><span data-stu-id="b97b7-120">For information about which Outlook clients are supported by Exchange 2016 and Exchange Online, see "Supported clients" in [Exchange 2016 system requirements](https://go.microsoft.com/fwlink/?LinkID=828972).</span></span>
  
> [!IMPORTANT]
>  <span data-ttu-id="b97b7-p105">Outlook 不作为 Exchange Online 订阅价格一部分提供。Microsoft Office Pro Plus（包括 Microsoft Outlook）包含在一些 Office 365 计划中，同时可以作为单独订阅购买。 >  如果使用 POP 连接到 Exchange Online 电子邮件帐户，会发现存在以下限制： >  无日历信息 >  无忙/闲信息 >  无全局地址列表 >  无电子邮件推送 >  当通过 POP 连接时，所有邮件将下载到客户端，同时多台计算机或设备之间没有任何同步（如笔记本电脑和电话之间）。</span><span class="sxs-lookup"><span data-stu-id="b97b7-p105">Outlook is not provided as part of the Exchange Online subscription price. Microsoft Office Pro Plus (which includes Microsoft Outlook) is included in some Office 365 plans and can be purchased as a separate subscription. >  You will see the following limitations if you use POP to connect to an Exchange Online email account: >  No calendar information >  No free/busy information >  No Global Address List >  No push email >  When connecting through POP, all messages will be downloaded to the client and there will be no synchronization between multiple computers or devices (such as between a laptop and a phone).</span></span> 
  
## <a name="outlook-on-the-web"></a><span data-ttu-id="b97b7-124">Web 上的 Outlook</span><span class="sxs-lookup"><span data-stu-id="b97b7-124">Outlook on the web</span></span>

<span data-ttu-id="b97b7-p106">Outlook 网页版是 Web 版 Outlook 电子邮件程序，可与 Exchange Online 结合使用。使用它，用户可以在有 Internet 连接的地方，通过 Web 浏览器查看电子邮件、日历和联系人。若要了解支持的浏览器，请参阅 [Outlook 网页版支持的浏览器（适用于企业）](https://go.microsoft.com/fwlink/p/?LinkId=287032)。</span><span class="sxs-lookup"><span data-stu-id="b97b7-p106">Outlook on the web is a web-based version of the Outlook email program that is used with Exchange Online. It enables users to access their email, calendar, and contacts through a web browser from wherever they connect to the Internet. For information about supported browsers, see [Supported browsers for Outlook on the web for business](https://go.microsoft.com/fwlink/p/?LinkId=287032).</span></span>
  
<span data-ttu-id="b97b7-128">Outlook 网页版具有两个客户端版本，这两个都可用于 Exchange Online：</span><span class="sxs-lookup"><span data-stu-id="b97b7-128">Outlook on the web comes in two client versions, both of which can be used with Exchange Online:</span></span>
  
- <span data-ttu-id="b97b7-p107">**Outlook 网页版** 标准的 Outlook 网页版为 Exchange Online 用户提供最类似于 Outlook 用户的邮件体验。它支持大部分新版 Web 浏览器，同时经过优化可用于平板电脑和智能电话以及台式机和笔记本电脑。用户可以阅读和发送邮件、整理联系人，并能安排约会和会议。基于活动的默认超时设置为 6 小时，但 [管理员可在 Windows PowerShell 中配置](https://go.microsoft.com/fwlink/p/?LinkId=399155)为介于 5 分钟到 8 小时中的一个值。此超时取决于 Web 应用中的用户交互，如单击按钮或选择邮件。此外，还有单独的安全驱动超时，此超时不可配置，无论用户活动如何都会发生。如果用户登录了 8 小时，OWA 会自动注销用户，并要求其重新进行身份验证。</span><span class="sxs-lookup"><span data-stu-id="b97b7-p107">**Outlook on the web** The standard version of Outlook on the web provides Exchange Online users with a messaging experience most similar to that of Outlook users. It supports most newer web browsers and is optimized for use on tablets and smartphones as well as desktops and laptops. Users can read and send messages, organize contacts, and schedule appointments and meetings. The default activity-based time-out is set at six hours, but it can be [configured by an administrator in Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) from 5 minutes to 8 hours. This time-out depends on user interactions within the web app, such as clicking a button or selecting a message. There is also a separate security-driven time-out, which is not configurable and will occur regardless of user activity. If a user is logged in for 8 hours, OWA will automatically log the user out and ask for re-authentication.</span></span> 
    
- <span data-ttu-id="b97b7-p108">**轻型 Outlook 网页版** 使用轻型 Outlook 网页版，Exchange Online 用户可以使用几乎所有 Web 浏览器访问邮箱。用户可以阅读和发送邮件、整理联系人，并能安排约会和会议。基于活动的默认超时设置为 6 小时，但 [管理员可在 Windows PowerShell 中配置](https://go.microsoft.com/fwlink/p/?LinkId=399155)为介于 5 分钟到 8 小时中的一个值。此超时取决于 Web 应用中的用户交互，如单击按钮或选择邮件。此外，还有单独的安全驱动超时，此超时不可配置，无论用户活动如何都会发生。如果用户登录了 8 小时，OWA 会自动注销用户，并要求其重新进行身份验证。</span><span class="sxs-lookup"><span data-stu-id="b97b7-p108">**The light version of Outlook on the web** The light version of Outlook on the web provides Exchange Online users access to the mailbox using almost any web browser. Users can read and send messages, organize contacts, and schedule appointments and meetings. The default activity-based time-out is set at six hours, but it can be [configured by an administrator in Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) from 5 minutes to 8 hours. This time-out depends on user interactions within the web app, such as clicking a button or selecting a message. There is also a separate security-driven time-out, which is not configurable and will occur regardless of user activity. If a user is logged in for 8 hours, the light version of OWA will automatically log the user out and ask for re-authentication.</span></span> 
    
<span data-ttu-id="b97b7-p109">Outlook 网页版还提供移动版本。有关详细信息，请参阅此[此页面](http://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409)。</span><span class="sxs-lookup"><span data-stu-id="b97b7-p109">Outlook on the web also is available in mobile versions. For more information, see [this page](http://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409).</span></span>
  
## <a name="outlook-for-mac"></a><span data-ttu-id="b97b7-144">Outlook for Mac</span><span class="sxs-lookup"><span data-stu-id="b97b7-144">Outlook for Mac</span></span>

<span data-ttu-id="b97b7-145">Exchange Online 支持 Microsoft Outlook for Mac，它提供电子邮件、 日历、 通讯簿、 任务列表和便笺列表。</span><span class="sxs-lookup"><span data-stu-id="b97b7-145">Exchange Online supports Microsoft Outlook for Mac, which provides email, calendar, an address book, a task list, and a note list.</span></span>
  
## <a name="outlook-for-ios-android-and-windows-phone"></a><span data-ttu-id="b97b7-146">IOS、 Android，和 Windows Phone 的 outlook</span><span class="sxs-lookup"><span data-stu-id="b97b7-146">Outlook for iOS, Android, and Windows Phone</span></span>

<span data-ttu-id="b97b7-p110">Exchange Online 适用于 Outlook 相关应用程序可用于 iOS、 Android 和 Windows Phone。在任何这些设备上使用应用程序商店找到 Outlook 应用程序。下面是通过移动 OS 细分。</span><span class="sxs-lookup"><span data-stu-id="b97b7-p110">Exchange Online works with Outlook apps available for iOS, Android, and Windows Phone. On any of these devices, use the app store to find the Outlook app. Here's a breakdown by mobile OS.</span></span>
  
|||||
|:-----|:-----|:-----|:-----|
|<span data-ttu-id="b97b7-150">设备</span><span class="sxs-lookup"><span data-stu-id="b97b7-150">Device</span></span>  <br/> |<span data-ttu-id="b97b7-151">Android</span><span class="sxs-lookup"><span data-stu-id="b97b7-151">Android</span></span>  <br/> |<span data-ttu-id="b97b7-152">iOS</span><span class="sxs-lookup"><span data-stu-id="b97b7-152">iOS</span></span>  <br/> |<span data-ttu-id="b97b7-153">Windows Phone</span><span class="sxs-lookup"><span data-stu-id="b97b7-153">Windows Phone</span></span>  <br/> |
|<span data-ttu-id="b97b7-154">Outlook 移动应用程序可用性</span><span class="sxs-lookup"><span data-stu-id="b97b7-154">Outlook mobile app availability</span></span>  <br/> |<span data-ttu-id="b97b7-155">是</span><span class="sxs-lookup"><span data-stu-id="b97b7-155">Yes</span></span>  <br/> [<span data-ttu-id="b97b7-156">获取 Outlook for Android</span><span class="sxs-lookup"><span data-stu-id="b97b7-156">Get Outlook for Android</span></span>](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |<span data-ttu-id="b97b7-157">是</span><span class="sxs-lookup"><span data-stu-id="b97b7-157">Yes</span></span>  <br/> [<span data-ttu-id="b97b7-158">获取适用于 iOS 的 Outlook</span><span class="sxs-lookup"><span data-stu-id="b97b7-158">Get Outlook for iOS</span></span>](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |<span data-ttu-id="b97b7-159">内置</span><span class="sxs-lookup"><span data-stu-id="b97b7-159">Built-in</span></span>  <br/> |
|<span data-ttu-id="b97b7-160">与 Exchange Online 兼容的内置电子邮件应用程序</span><span class="sxs-lookup"><span data-stu-id="b97b7-160">Built-in email apps compatible with Exchange Online</span></span>  <br/> |<span data-ttu-id="b97b7-161">Gmail 应用程序/三星电子邮件应用程序</span><span class="sxs-lookup"><span data-stu-id="b97b7-161">Gmail app/Samsung Email app</span></span>  <br/> |<span data-ttu-id="b97b7-162">iOS 邮件应用程序</span><span class="sxs-lookup"><span data-stu-id="b97b7-162">iOS Mail app</span></span>  <br/> |<span data-ttu-id="b97b7-163">Outlook 邮件、 日历、 联系人</span><span class="sxs-lookup"><span data-stu-id="b97b7-163">Outlook Mail, calendar, contacts</span></span>  <br/> |
|<span data-ttu-id="b97b7-164">更多信息</span><span class="sxs-lookup"><span data-stu-id="b97b7-164">More information</span></span>  <br/> |[<span data-ttu-id="b97b7-165">Android 移动安装程序</span><span class="sxs-lookup"><span data-stu-id="b97b7-165">Android mobile setup</span></span>](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[<span data-ttu-id="b97b7-166">iPhone 或 iPad 的安装程序</span><span class="sxs-lookup"><span data-stu-id="b97b7-166">iPhone or iPad setup</span></span>](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[<span data-ttu-id="b97b7-167">Windows Phone 安装程序</span><span class="sxs-lookup"><span data-stu-id="b97b7-167">Windows Phone setup</span></span>](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |
   
<span data-ttu-id="b97b7-168">还有设备，包括 Blackberry 使用 Exchange Online 的选项。</span><span class="sxs-lookup"><span data-stu-id="b97b7-168">There are also options for using Exchange Online with devices, including Blackberry.</span></span>
  
### <a name="feature-availability"></a><span data-ttu-id="b97b7-169">功能可用性</span><span class="sxs-lookup"><span data-stu-id="b97b7-169">Feature availability</span></span>

<span data-ttu-id="b97b7-p111">Outlook 中，为用户提供快速、 直观电子邮件和日历体验，他们希望从现代的移动应用程序时要仅应用程序的 Office 365 的最佳功能提供支持。它是唯一电子邮件应用程序专门用于支持完整的 Office 365 体验，请为用户提供一致的体验从桌面到移动。Outlook 与 Intune、 企业移动性和安全性和 Exchange 控件，以保护数据和用户安全集成。</span><span class="sxs-lookup"><span data-stu-id="b97b7-p111">Outlook gives users the fast, intuitive email and calendar experience that they expect from a modern mobile app, while being the only app to provide support for the best features of Office 365. It is the only email app specifically designed to support the full Office 365 experience, giving users a coherent experience from desktop to mobile. Outlook is integrated with Intune, enterprise mobility and security, and Exchange controls to keep data and users safe.</span></span>
  
<span data-ttu-id="b97b7-173">Outlook 使用户能够：</span><span class="sxs-lookup"><span data-stu-id="b97b7-173">Outlook enables users to:</span></span>
  
- <span data-ttu-id="b97b7-174">从移动设备管理其整个天。</span><span class="sxs-lookup"><span data-stu-id="b97b7-174">Manage their entire day from a mobile device.</span></span>
    
- <span data-ttu-id="b97b7-175">连接到的应用程序和服务所需提高生产效率，同时保持其工作和个人信息单独和安全。</span><span class="sxs-lookup"><span data-stu-id="b97b7-175">Connect to the apps and services they need to be productive, while keeping their work and personal information separate and secure.</span></span>
    
<span data-ttu-id="b97b7-176">使用 Outlook 针对 iOS，for Android，Outlook 或 Outlook for Windows Phone，用户可以：</span><span class="sxs-lookup"><span data-stu-id="b97b7-176">With Outlook for iOS, Outlook for Android, or Outlook for Windows Phone, users can:</span></span> 
  
- <span data-ttu-id="b97b7-177">受益于重点收件箱的优先级重要电子邮件</span><span class="sxs-lookup"><span data-stu-id="b97b7-177">Benefit from a focused inbox that priorities important email</span></span>
    
- <span data-ttu-id="b97b7-178">自定义向内轻扫手势匹配其唯一的电子邮件习惯</span><span class="sxs-lookup"><span data-stu-id="b97b7-178">Customize swipe gestures to match their unique email habits</span></span>
    
- <span data-ttu-id="b97b7-179">创建可以添加直接到日历，提供快速的关键信息的旅行路线</span><span class="sxs-lookup"><span data-stu-id="b97b7-179">Create travel itineraries that can be added directly to the calendar, with key information available at a glance</span></span>
    
- <span data-ttu-id="b97b7-180">从收件箱 RSVP 加入会议。</span><span class="sxs-lookup"><span data-stu-id="b97b7-180">RSVP to meetings from the inbox.</span></span>
    
- <span data-ttu-id="b97b7-181">帮助他们快速处理信息的电子邮件和日历约会在使用直观的图标</span><span class="sxs-lookup"><span data-stu-id="b97b7-181">Use intuitive icons in email and calendar appointments that help them process information quickly</span></span>
    
- <span data-ttu-id="b97b7-182">在所有设备上使用一致和熟悉的 Outlook 体验</span><span class="sxs-lookup"><span data-stu-id="b97b7-182">Use a consistent and familiar Outlook experience across all devices</span></span>
    
- <span data-ttu-id="b97b7-183">轻松启动并加入 Skype 会议从日历</span><span class="sxs-lookup"><span data-stu-id="b97b7-183">Easily launch and join Skype meetings from the calendar</span></span>
    
- <span data-ttu-id="b97b7-184">读取和响应 IRM 加密和受保护的电子邮件</span><span class="sxs-lookup"><span data-stu-id="b97b7-184">Read and respond to IRM encrypted and protected emails</span></span>
    
- <span data-ttu-id="b97b7-185">OneDrive for Business 中存储的共享文件</span><span class="sxs-lookup"><span data-stu-id="b97b7-185">Share files stored in OneDrive for Business</span></span>
    
- <span data-ttu-id="b97b7-186">设置与点击的自动答复</span><span class="sxs-lookup"><span data-stu-id="b97b7-186">Set Automatic Replies with a tap</span></span>
    
- <span data-ttu-id="b97b7-187">查看和管理共享和委派日历</span><span class="sxs-lookup"><span data-stu-id="b97b7-187">View and manage shared and delegated calendars</span></span>
    
- <span data-ttu-id="b97b7-188">搜索与几次点击其公司的全局地址列表</span><span class="sxs-lookup"><span data-stu-id="b97b7-188">Search their company's global address list with a few taps</span></span>
    
- <span data-ttu-id="b97b7-189">查看同事的可用性和计划的会议时间的适用于所有人</span><span class="sxs-lookup"><span data-stu-id="b97b7-189">View coworker's availability and schedule a meeting time that works for everyone</span></span>
    
- <span data-ttu-id="b97b7-190">请参阅被邀请者暂定接受和拒绝状态</span><span class="sxs-lookup"><span data-stu-id="b97b7-190">See invitees accept, tentative, and decline status</span></span>
    
- <span data-ttu-id="b97b7-191">共享日历直接从其电话</span><span class="sxs-lookup"><span data-stu-id="b97b7-191">Share calendars right from their phones</span></span>
    
- <span data-ttu-id="b97b7-192">开始和加入 Skype 会议右从日历</span><span class="sxs-lookup"><span data-stu-id="b97b7-192">Start and join Skype meetings right from a calendar</span></span>
    
- <span data-ttu-id="b97b7-193">访问工作和个人日历在一个位置，而无需切换应用程序</span><span class="sxs-lookup"><span data-stu-id="b97b7-193">Access work and personal calendars in one place, without switching apps</span></span>
    
## <a name="exchange-activesync"></a><span data-ttu-id="b97b7-194">Exchange ActiveSync</span><span class="sxs-lookup"><span data-stu-id="b97b7-194">Exchange ActiveSync</span></span>

<span data-ttu-id="b97b7-195">Exchange Online 支持 Microsoft Exchange ActiveSync 协议，这将在移动设备和 Exchange Online 之间同步邮箱，以便用户可以随身访问他们的电子邮件、日历、联系人和任务。</span><span class="sxs-lookup"><span data-stu-id="b97b7-195">Exchange Online supports the Microsoft Exchange ActiveSync protocol, which synchronizes mailbox data between mobile devices and Exchange Online, so users can access their email, calendar, contacts, and tasks on the go.</span></span>
  
<span data-ttu-id="b97b7-p112">范围广泛的移动设备使用 Exchange ActiveSync，包括 Microsoft Windows Phone、 Apple iPhone 和 iPad 和 Android 电话和平板电脑中。除了移动电话和设备，在 Windows Phone 中的邮件应用程序使用 Exchange ActiveSync 连接到 Exchange Online。在 Exchange ActiveSync 许可站点位于当前 Exchange ActiveSync 许可证的完整列表。</span><span class="sxs-lookup"><span data-stu-id="b97b7-p112">A wide range of mobile devices work with Exchange ActiveSync, including Microsoft Windows Phone, Apple iPhone and iPad, and Android phones and tablets. In addition to mobile phones and devices, the Mail application in Windows Phone uses Exchange ActiveSync to connect to Exchange Online. A complete list of current Exchange ActiveSync licensees is available at the Exchange ActiveSync Licensing site.</span></span>
  
<span data-ttu-id="b97b7-199">有关 Exchange ActiveSync 的详细信息，请参阅[Exchange ActiveSync](https://go.microsoft.com/fwlink/p/?LinkId=271792)。</span><span class="sxs-lookup"><span data-stu-id="b97b7-199">For more information about Exchange ActiveSync, see [Exchange ActiveSync](https://go.microsoft.com/fwlink/p/?LinkId=271792).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="b97b7-200">每个邮箱的 Exchange ActiveSync 设备的最大数量为 100。</span><span class="sxs-lookup"><span data-stu-id="b97b7-200">The maximum number of Exchange ActiveSync devices per mailbox is 100.</span></span> 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a><span data-ttu-id="b97b7-201">使用 Exchange Web Services（EWS）开发的应用程序</span><span class="sxs-lookup"><span data-stu-id="b97b7-201">Applications developed with Exchange Web Services (EWS)</span></span>

 <span data-ttu-id="b97b7-202">通过使用 Exchange Web 服务 (EWS) 或 EWS 托管 API 开发的应用程序，管理员可以访问使用 Exchange Online 存储的、来自本地、Azure 或其他托管服务运行的应用程序的数据。</span><span class="sxs-lookup"><span data-stu-id="b97b7-202">Applications developed using Exchange Web Services (EWS) or the EWS Managed API let administrators access data stored with Exchange Online from applications that are running on-premises, in Azure, or in other hosted services.</span></span> 
  
<span data-ttu-id="b97b7-203">若要详细了解使用 Exchange Web 服务开发的应用程序，请参阅 [Exchange Web 服务](https://go.microsoft.com/fwlink/?LinkId=325346)。</span><span class="sxs-lookup"><span data-stu-id="b97b7-203">For more information on applications developed with Exchange Web Services, see [Web Services in Exchange](https://go.microsoft.com/fwlink/?LinkId=325346).</span></span>
  
## <a name="pop-and-imap"></a><span data-ttu-id="b97b7-204">POP 和 IMAP</span><span class="sxs-lookup"><span data-stu-id="b97b7-204">POP and IMAP</span></span>

<span data-ttu-id="b97b7-p113">Exchange Online 通过 POP3 和 IMAP4 协议支持邮箱访问。POP 和 IMAP 访问要求使用 SSL 加密。默认情况下，为所有用户启用 POP。用户可以在 Outlook 网页版中查看他们的 POP 和 IMAP 连接设置。管理员可以在每个用户的基础上禁用 POP 和 IMAP 访问。</span><span class="sxs-lookup"><span data-stu-id="b97b7-p113">Exchange Online supports mailbox access through both POP3 and IMAP4 protocols. POP and IMAP access requires encryption using SSL. POP is enabled by default for all users. Users can view their POP and IMAP connection settings in Outlook on the web. Administrators can disable POP and IMAP access on a per-user basis.</span></span>
  
<span data-ttu-id="b97b7-210">有关 POP3 和 IMAP4 连接性的详细信息，请参阅 [POP3 和 IMAP4](https://go.microsoft.com/fwlink/p/?LinkId=272070)。</span><span class="sxs-lookup"><span data-stu-id="b97b7-210">For more information about POP3 and IMAP4 connectivity, see [POP3 and IMAP4](https://go.microsoft.com/fwlink/p/?LinkId=272070).</span></span>
  
## <a name="smtp"></a><span data-ttu-id="b97b7-211">SMTP</span><span class="sxs-lookup"><span data-stu-id="b97b7-211">SMTP</span></span>

<span data-ttu-id="b97b7-p114">简单邮件传输协议 (SMTP) 用于为通过 IMAP 或 POP 连接到 Exchange Online 的客户端发送出站邮件。它是通过 Exchange Server 路由和递送的主协议。Exchange Online 支持两种类型的 SMTP 中继服务，用于需要 SMTP 邮件提交的授权内部客户应用程序：</span><span class="sxs-lookup"><span data-stu-id="b97b7-p114">Simple Mail Transfer Protocol (SMTP) is used to send outbound mail for clients that connect to Exchange Online through IMAP or POP. It is the primary protocol for routing and delivery through Exchange Server. Exchange Online supports two types of SMTP relay services for authorized internal customer applications that require SMTP mail submission:</span></span>
  
- <span data-ttu-id="b97b7-215">SMTP 邮件提交给托管环境内的用户。</span><span class="sxs-lookup"><span data-stu-id="b97b7-215">SMTP message submission to users inside the managed environment.</span></span>
    
- <span data-ttu-id="b97b7-216">通过身份验证的 SMTP 邮件中继到托管环境外的地址。</span><span class="sxs-lookup"><span data-stu-id="b97b7-216">Authenticated SMTP message relay to addresses outside the managed environment.</span></span>
    
> [!IMPORTANT]
> <span data-ttu-id="b97b7-p115">授权源服务器的 IP 地址需要允许 SMTP 中继。当使用 SMTP 发送电子邮件时需要传输层安全性 (TLS) 加密和身份验证。</span><span class="sxs-lookup"><span data-stu-id="b97b7-p115">IP addresses for authorized source servers are required to allow SMTP relay. Transport Layer Security (TLS) encryption and authentication is required when using SMTP to send email.</span></span> 
  
## <a name="blackberry-devices"></a><span data-ttu-id="b97b7-219">BlackBerry® 设备</span><span class="sxs-lookup"><span data-stu-id="b97b7-219">BlackBerry® devices</span></span>

<span data-ttu-id="b97b7-p116">Office 365 电子邮件是通过 Exchange ActiveSync BlackBerry® 设备上可用。若要查找什么是您的选项，请参阅下列主题：</span><span class="sxs-lookup"><span data-stu-id="b97b7-p116">Office 365 email is available on BlackBerry® devices via Exchange ActiveSync. To find out what your options are, see these topics:</span></span>
  
- [<span data-ttu-id="b97b7-222">将 BlackBerry 设备上的电子邮件设置</span><span class="sxs-lookup"><span data-stu-id="b97b7-222">Set up email on a BlackBerry device</span></span>](https://go.microsoft.com/fwlink/?linkid=863394)
    
- [<span data-ttu-id="b97b7-223">BlackBerry 设备 7.1 上设置电子邮件 OS 和更早版本</span><span class="sxs-lookup"><span data-stu-id="b97b7-223">Set up email on a BlackBerry device 7.1 OS and earlier</span></span>](https://go.microsoft.com/fwlink/?linkid=863403)
    
<span data-ttu-id="b97b7-224">有关详细信息，请参阅 [BlackBerry](../office-365-platform-service-description/blackberry.md)。</span><span class="sxs-lookup"><span data-stu-id="b97b7-224">For more information, see [BlackBerry](../office-365-platform-service-description/blackberry.md).</span></span>
  
> [!NOTE]
> <span data-ttu-id="b97b7-p117">如果使用的是由中国世纪互联运营的 Office 365，则 BlackBerry 商业云服务 不可用，但是你可以使用 Exchange ActiveSync 设备和 Research in Motion（RIM，BlackBerry 无线电子邮件解决方案）中的产品运行 Blackberry Enterprise Server (BES)。</span><span class="sxs-lookup"><span data-stu-id="b97b7-p117">If you are using Office 365 operated by 21Vianet in China, BlackBerry Business Cloud Services is not available. However, you can use Exchange ActiveSync devices or an offering from Research in Motion (RIM, the BlackBerry wireless email solution) to run Blackberry Enterprise Server (BES).</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="b97b7-227">功能可用性</span><span class="sxs-lookup"><span data-stu-id="b97b7-227">Feature Availability</span></span>

<span data-ttu-id="b97b7-228">若要查看在各个 Office 365 计划、独立选项和内部部署解决方案之间的功能可用性，请参阅 [Exchange Online 服务说明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="b97b7-228">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

