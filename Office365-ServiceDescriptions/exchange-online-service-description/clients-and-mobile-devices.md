---
title: 客户端和移动设备
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
description: Exchange Online 适用于 Outlook 的桌面和移动版本，以及 Outlook 网页版。
ms.openlocfilehash: 3aa0c2bbdf9b55b6a3544919143fd9d5e5cfed24
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653114"
---
# <a name="clients-and-mobile-devices"></a><span data-ttu-id="b4a99-103">客户端和移动设备</span><span class="sxs-lookup"><span data-stu-id="b4a99-103">Clients and mobile devices</span></span>

## <a name="microsoft-outlook"></a><span data-ttu-id="b4a99-104">Microsoft Outlook</span><span class="sxs-lookup"><span data-stu-id="b4a99-104">Microsoft Outlook</span></span>

<span data-ttu-id="b4a99-105">Microsoft Outlook 是一个电子邮件程序，包括对日历、联系人、任务和以下关键功能的支持：</span><span class="sxs-lookup"><span data-stu-id="b4a99-105">Microsoft Outlook is an email program that includes support for calendar, contacts, tasks, and the following key features:</span></span>
  
- <span data-ttu-id="b4a99-106">**MAPI over HTTP** - 通过 HTTP (MAPI) 的邮件应用程序接口允许 Outlook 用户从组织防火墙外部通过 Internet 连接到 Exchange Online 邮箱。</span><span class="sxs-lookup"><span data-stu-id="b4a99-106">**MAPI over HTTP** - Messaging Application Program Interface (MAPI) over HTTP allows Outlook users to connect to Exchange Online mailboxes over the internet from outside their organization's firewall.</span></span> <span data-ttu-id="b4a99-107">MAPI over HTTP，Outlook Anywhere 的长期替代项。</span><span class="sxs-lookup"><span data-stu-id="b4a99-107">MAPI over HTTP, the long term replacement for Outlook Anywhere.</span></span> <span data-ttu-id="b4a99-108">此连接方法改进了连接恢复能力、更安全的登录、可扩展性，并增强了 IT 和支持。</span><span class="sxs-lookup"><span data-stu-id="b4a99-108">This connectivity method offers improved connection resiliency, more secure sign-in, extensibility, as well as enhancements for IT and support.</span></span> <span data-ttu-id="b4a99-109">若要了解更多信息，请参阅[RPC over HTTP 到达 Office 365](/exchange/troubleshoot/administration/rpc-over-http-end-of-support)中的停止支持和[MAPI over HTTP。](/exchange/mapi-over-http-exchange-2013-help)</span><span class="sxs-lookup"><span data-stu-id="b4a99-109">To learn more, see [RPC over HTTP reaches end of support in Office 365](/exchange/troubleshoot/administration/rpc-over-http-end-of-support) and [MAPI over HTTP](/exchange/mapi-over-http-exchange-2013-help).</span></span>

- <span data-ttu-id="b4a99-110">**自动发现** - 自动发现服务功能自动配置 Outlook 以使用 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="b4a99-110">**Autodiscover** - The Autodiscover service feature automatically configures Outlook to work with Exchange Online.</span></span> <span data-ttu-id="b4a99-111">首次使用电子邮件地址和密码登录时，Outlook 用户可以直接从 Exchange Online 收到他们的所需配置文件设置。</span><span class="sxs-lookup"><span data-stu-id="b4a99-111">Outlook users can receive their required profile settings directly from Exchange Online the first time they sign in with their email address and password.</span></span> <span data-ttu-id="b4a99-112">这些设置可以使用创建和维护用户配置文件所需的信息自动更新 Outlook 客户端。</span><span class="sxs-lookup"><span data-stu-id="b4a99-112">These settings automatically update the Outlook client with the information necessary to create and maintain the user's profile.</span></span> <span data-ttu-id="b4a99-113">使用自动发现服务需要 SSL 证书。</span><span class="sxs-lookup"><span data-stu-id="b4a99-113">An SSL certificate is required to use the Autodiscover service.</span></span> <span data-ttu-id="b4a99-114">此 SSL 证书仅限于单个主 SSL 域。</span><span class="sxs-lookup"><span data-stu-id="b4a99-114">This SSL certificate is limited to a single primary SSL domain.</span></span> 

- <span data-ttu-id="b4a99-115">**缓存 Exchange 模式** - 缓存 Exchange 模式功能允许 Outlook 用户在未连接到 Internet 时访问其 Exchange Online 邮箱的本地副本。</span><span class="sxs-lookup"><span data-stu-id="b4a99-115">**Cached Exchange Mode** - The Cached Exchange Mode feature allows Outlook users to access local copies of their Exchange Online mailboxes when they are not connected to the internet.</span></span> <span data-ttu-id="b4a99-116">缓存 Exchange 模式在 Outlook 中保存用户 Exchange 邮箱的客户端副本，并与电子邮件服务器自动同步该副本。</span><span class="sxs-lookup"><span data-stu-id="b4a99-116">Cached Exchange Mode retains a client-side copy of users' Exchange mailboxes in Outlook and automatically synchronizes this copy with the email server.</span></span> <span data-ttu-id="b4a99-117">我们建议在缓存 Exchange 模式中使用 Outlook，因为它提供脱机访问并帮助提供响应用户体验，即使客户端和服务器之间的网络条件不理想。</span><span class="sxs-lookup"><span data-stu-id="b4a99-117">We recommend using Outlook in Cached Exchange Mode because it provides offline access and helps to provide a responsive user experience even when network conditions between the client and the server are not ideal.</span></span> 

<span data-ttu-id="b4a99-p104">默认情况下，所有用户启用 Outlook 访问。管理员可以通过 Windows PowerShell 禁用对特定用户的访问权限。我们建议使用最新版本的 Outlook装有最新的 service pack以访问 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="b4a99-p104">By default, Outlook access is enabled for all users. Administrators can disable access for specific users or groups through Windows PowerShell. We recommend using the latest version of Outlook—with the latest service pack installed—to access Exchange Online.</span></span> 
  
<span data-ttu-id="b4a99-121">有关 Exchange 2016 和 Exchange Online 支持哪些 Outlook 客户端的信息，请参阅[System Requirements for Office。](https://products.office.com/office-system-requirements)</span><span class="sxs-lookup"><span data-stu-id="b4a99-121">For information about which Outlook clients are supported by Exchange 2016 and Exchange Online, see [System Requirements for Office](https://products.office.com/office-system-requirements).</span></span> 

<span data-ttu-id="b4a99-122">Microsoft 365 设计用于使用最新浏览器和 Office 版本。</span><span class="sxs-lookup"><span data-stu-id="b4a99-122">Microsoft 365 is designed to work with the latest browsers and versions of Office.</span></span> <span data-ttu-id="b4a99-123">如果你使用的旧版浏览器和 Office 版本不是主流支持：</span><span class="sxs-lookup"><span data-stu-id="b4a99-123">If you use older browsers and versions of Office that aren't in mainstream support:</span></span>

- <span data-ttu-id="b4a99-124">Microsoft 不会有意阻止你连接到服务，但用户体验的质量可能会随着时间的推移而降低。</span><span class="sxs-lookup"><span data-stu-id="b4a99-124">Microsoft won't deliberately prevent you from connecting to the service, but the quality of your experience may diminish over time.</span></span>
- <span data-ttu-id="b4a99-125">Microsoft 不会提供软件更新来解决与安全非相关的问题。</span><span class="sxs-lookup"><span data-stu-id="b4a99-125">Microsoft won't provide software updates to resolve non-security related problems.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="b4a99-126">Outlook 不作为 Exchange Online 订阅价格一部分提供。</span><span class="sxs-lookup"><span data-stu-id="b4a99-126">Outlook is not provided as part of the Exchange Online subscription price.</span></span> <span data-ttu-id="b4a99-127">Microsoft 365 企业应用版 (包括 Microsoft Outlook) 包含在一些计划中，可以单独订阅购买。</span><span class="sxs-lookup"><span data-stu-id="b4a99-127">Microsoft 365 Apps for enterprise (which includes Microsoft Outlook) is included in some plans and can be purchased as a separate subscription.</span></span> <span data-ttu-id="b4a99-128">如果使用 POP 连接到 Exchange Online 电子邮件帐户，会发现存在以下限制：</span><span class="sxs-lookup"><span data-stu-id="b4a99-128">You will see the following limitations if you use POP to connect to an Exchange Online email account:</span></span>
> - <span data-ttu-id="b4a99-129">无日历信息</span><span class="sxs-lookup"><span data-stu-id="b4a99-129">No calendar information</span></span>
>- <span data-ttu-id="b4a99-130">无忙/闲信息</span><span class="sxs-lookup"><span data-stu-id="b4a99-130">No free/busy information</span></span>
>- <span data-ttu-id="b4a99-131">无全局地址列表</span><span class="sxs-lookup"><span data-stu-id="b4a99-131">No Global Address List</span></span>
>- <span data-ttu-id="b4a99-132">无电子邮件推送</span><span class="sxs-lookup"><span data-stu-id="b4a99-132">No push email</span></span>
>- <span data-ttu-id="b4a99-133">当通过 POP 连接时，所有邮件将下载到客户端，同时多台计算机或设备之间没有任何同步（如笔记本电脑和电话之间）。</span><span class="sxs-lookup"><span data-stu-id="b4a99-133">When connecting through POP, all messages will be downloaded to the client and there will be no synchronization between multiple computers or devices (such as between a laptop and a phone).</span></span> 
  
## <a name="outlook-on-the-web"></a><span data-ttu-id="b4a99-134">Web 上的 Outlook</span><span class="sxs-lookup"><span data-stu-id="b4a99-134">Outlook on the web</span></span>

<span data-ttu-id="b4a99-135">Outlook 网页版是 Web 版 Outlook 电子邮件程序，可与 Exchange Online 结合使用。</span><span class="sxs-lookup"><span data-stu-id="b4a99-135">Outlook on the web is a web-based version of the Outlook email program that is used with Exchange Online.</span></span> <span data-ttu-id="b4a99-136">它允许用户从任何连接到 Internet 的 Web 浏览器访问其电子邮件、日历和联系人。</span><span class="sxs-lookup"><span data-stu-id="b4a99-136">It lets users access their email, calendar, and contacts through a web browser from wherever they connect to the internet.</span></span> <span data-ttu-id="b4a99-137">若要了解支持的浏览器，请参阅 [Outlook 网页版支持的浏览器（适用于企业）](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006)。</span><span class="sxs-lookup"><span data-stu-id="b4a99-137">For information about supported browsers, see [Supported browsers for Outlook on the web for business](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006).</span></span>
  
<span data-ttu-id="b4a99-138">Outlook 网页版具有两个客户端版本，这两个都可用于 Exchange Online：</span><span class="sxs-lookup"><span data-stu-id="b4a99-138">Outlook on the web comes in two client versions, both of which can be used with Exchange Online:</span></span>
  
- <span data-ttu-id="b4a99-139">**Outlook 网页版** - 标准版 Outlook 网页版为 Exchange Online 用户提供与 Outlook 用户最相似的邮件体验。</span><span class="sxs-lookup"><span data-stu-id="b4a99-139">**Outlook on the web** - The standard version of Outlook on the web provides Exchange Online users with a messaging experience most similar to that of Outlook users.</span></span> <span data-ttu-id="b4a99-140">它支持大部分新版 Web 浏览器，同时经过优化可用于平板电脑和智能电话以及台式机和笔记本电脑。</span><span class="sxs-lookup"><span data-stu-id="b4a99-140">It supports most newer web browsers and is optimized for use on tablets and smartphones as well as desktops and laptops.</span></span> <span data-ttu-id="b4a99-141">用户可以阅读和发送邮件、整理联系人，并能安排约会和会议。</span><span class="sxs-lookup"><span data-stu-id="b4a99-141">Users can read and send messages, organize contacts, and schedule appointments and meetings.</span></span> <span data-ttu-id="b4a99-142">基于活动的默认超时设置为 6 小时，但 [管理员可在 Windows PowerShell 中配置](/powershell/module/exchange/set-organizationconfig)为介于 5 分钟到 8 小时中的一个值。</span><span class="sxs-lookup"><span data-stu-id="b4a99-142">The default activity-based time-out is set at six hours, but it can be [configured by an administrator in Windows PowerShell](/powershell/module/exchange/set-organizationconfig) from 5 minutes to 8 hours.</span></span> <span data-ttu-id="b4a99-143">此时间退出取决于 Web 应用中的用户交互，例如选择按钮或选择消息。</span><span class="sxs-lookup"><span data-stu-id="b4a99-143">This time-out depends on user interactions within the web app, such as selecting a button or selecting a message.</span></span> <span data-ttu-id="b4a99-144">此外，还有单独的安全驱动超时，此超时不可配置，无论用户活动如何都会发生。</span><span class="sxs-lookup"><span data-stu-id="b4a99-144">There is also a separate security-driven time-out, which is not configurable and will occur regardless of user activity.</span></span> <span data-ttu-id="b4a99-145">如果用户登录了 8 小时，OWA 会自动注销用户，并要求其重新进行身份验证。</span><span class="sxs-lookup"><span data-stu-id="b4a99-145">If a user is logged in for 8 hours, OWA will automatically log the user out and ask for re-authentication.</span></span> 

- <span data-ttu-id="b4a99-146">**Outlook 网页** 版 Light version - Outlook 网页版 Light version provides Exchange Online users access to the mailbox using almost any web browser.</span><span class="sxs-lookup"><span data-stu-id="b4a99-146">**The light version of Outlook on the web** - The light version of Outlook on the web provides Exchange Online users access to the mailbox using almost any web browser.</span></span> <span data-ttu-id="b4a99-147">用户可以阅读和发送邮件、整理联系人，并能安排约会和会议。</span><span class="sxs-lookup"><span data-stu-id="b4a99-147">Users can read and send messages, organize contacts, and schedule appointments and meetings.</span></span> <span data-ttu-id="b4a99-148">基于活动的默认超时设置为 6 小时，但 [管理员可在 Windows PowerShell 中配置](/powershell/module/exchange/set-organizationconfig)为介于 5 分钟到 8 小时中的一个值。</span><span class="sxs-lookup"><span data-stu-id="b4a99-148">The default activity-based time-out is set at six hours, but it can be [configured by an administrator in Windows PowerShell](/powershell/module/exchange/set-organizationconfig) from 5 minutes to 8 hours.</span></span> <span data-ttu-id="b4a99-149">此时间退出取决于 Web 应用中的用户交互，例如选择按钮或选择消息。</span><span class="sxs-lookup"><span data-stu-id="b4a99-149">This time-out depends on user interactions within the web app, such as selecting a button or selecting a message.</span></span> <span data-ttu-id="b4a99-150">此外，还有单独的安全驱动超时，此超时不可配置，无论用户活动如何都会发生。</span><span class="sxs-lookup"><span data-stu-id="b4a99-150">There is also a separate security-driven time-out, which is not configurable and will occur regardless of user activity.</span></span> <span data-ttu-id="b4a99-151">如果用户登录了 8 小时，OWA 会自动注销用户，并要求其重新进行身份验证。</span><span class="sxs-lookup"><span data-stu-id="b4a99-151">If a user is logged in for 8 hours, the light version of OWA will automatically log the user out and ask for re-authentication.</span></span> 

<span data-ttu-id="b4a99-152">Outlook 网页版还提供移动版本。</span><span class="sxs-lookup"><span data-stu-id="b4a99-152">Outlook on the web also is available in mobile versions.</span></span> <span data-ttu-id="b4a99-153">有关详细信息，请参阅此[此页面](https://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409)。</span><span class="sxs-lookup"><span data-stu-id="b4a99-153">For more information, see [this page](https://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409).</span></span>
  
## <a name="outlook-for-mac"></a><span data-ttu-id="b4a99-154">Outlook for Mac</span><span class="sxs-lookup"><span data-stu-id="b4a99-154">Outlook for Mac</span></span>

<span data-ttu-id="b4a99-155">Exchange Online 支持 Microsoft Outlook for Mac，它提供电子邮件、日历、通讯簿、任务列表和便笺列表。</span><span class="sxs-lookup"><span data-stu-id="b4a99-155">Exchange Online supports Microsoft Outlook for Mac, which provides email, calendar, an address book, a task list, and a note list.</span></span>
  
## <a name="outlook-for-ios-android-and-windows-phone"></a><span data-ttu-id="b4a99-156">Outlook for iOS、Android 和 Windows Phone</span><span class="sxs-lookup"><span data-stu-id="b4a99-156">Outlook for iOS, Android, and Windows Phone</span></span>

<span data-ttu-id="b4a99-157">Exchange Online 适用于适用于 iOS、Android 和 Windows Phone 的 Outlook 应用。</span><span class="sxs-lookup"><span data-stu-id="b4a99-157">Exchange Online works with Outlook apps available for iOS, Android, and Windows Phone.</span></span> <span data-ttu-id="b4a99-158">在任一设备上，使用应用商店查找 Outlook 应用。</span><span class="sxs-lookup"><span data-stu-id="b4a99-158">On any of these devices, use the app store to find the Outlook app.</span></span> <span data-ttu-id="b4a99-159">下面按移动操作系统细分。</span><span class="sxs-lookup"><span data-stu-id="b4a99-159">Here's a breakdown by mobile OS.</span></span><br><br>
  
| <span data-ttu-id="b4a99-160">设备</span><span class="sxs-lookup"><span data-stu-id="b4a99-160">Device</span></span> | <span data-ttu-id="b4a99-161">Android</span><span class="sxs-lookup"><span data-stu-id="b4a99-161">Android</span></span> | <span data-ttu-id="b4a99-162">iOS</span><span class="sxs-lookup"><span data-stu-id="b4a99-162">iOS</span></span> | <span data-ttu-id="b4a99-163">Windows Phone</span><span class="sxs-lookup"><span data-stu-id="b4a99-163">Windows Phone</span></span> |
|:-----|:-----|:-----|:-----|
|<span data-ttu-id="b4a99-164">Outlook 移动应用可用性</span><span class="sxs-lookup"><span data-stu-id="b4a99-164">Outlook mobile app availability</span></span>  <br/> |<span data-ttu-id="b4a99-165">是</span><span class="sxs-lookup"><span data-stu-id="b4a99-165">Yes</span></span>  <br/> [<span data-ttu-id="b4a99-166">获取 Outlook for Android</span><span class="sxs-lookup"><span data-stu-id="b4a99-166">Get Outlook for Android</span></span>](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |<span data-ttu-id="b4a99-167">是</span><span class="sxs-lookup"><span data-stu-id="b4a99-167">Yes</span></span>  <br/> [<span data-ttu-id="b4a99-168">获取 Outlook for iOS</span><span class="sxs-lookup"><span data-stu-id="b4a99-168">Get Outlook for iOS</span></span>](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |<span data-ttu-id="b4a99-169">内置</span><span class="sxs-lookup"><span data-stu-id="b4a99-169">Built-in</span></span>  <br/> |
|<span data-ttu-id="b4a99-170">与 Exchange Online 兼容的内置电子邮件应用</span><span class="sxs-lookup"><span data-stu-id="b4a99-170">Built-in email apps compatible with Exchange Online</span></span>  <br/> |<span data-ttu-id="b4a99-171">Gmail 应用/三星电子邮件应用</span><span class="sxs-lookup"><span data-stu-id="b4a99-171">Gmail app/Samsung Email app</span></span>  <br/> |<span data-ttu-id="b4a99-172">iOS 邮件应用程序</span><span class="sxs-lookup"><span data-stu-id="b4a99-172">iOS Mail app</span></span>  <br/> |<span data-ttu-id="b4a99-173">Outlook 邮件、日历、联系人</span><span class="sxs-lookup"><span data-stu-id="b4a99-173">Outlook Mail, calendar, contacts</span></span>  <br/> |
|<span data-ttu-id="b4a99-174">更多信息</span><span class="sxs-lookup"><span data-stu-id="b4a99-174">More information</span></span>  <br/> |[<span data-ttu-id="b4a99-175">Android 移动设置</span><span class="sxs-lookup"><span data-stu-id="b4a99-175">Android mobile setup</span></span>](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[<span data-ttu-id="b4a99-176">iPhone 或 iPad 设置</span><span class="sxs-lookup"><span data-stu-id="b4a99-176">iPhone or iPad setup</span></span>](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[<span data-ttu-id="b4a99-177">Windows Phone 设置</span><span class="sxs-lookup"><span data-stu-id="b4a99-177">Windows Phone setup</span></span>](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |

<span data-ttu-id="b4a99-178">还有一些选项用于将 Exchange Online 与设备（包括 Blackberry）一同使用。</span><span class="sxs-lookup"><span data-stu-id="b4a99-178">There are also options for using Exchange Online with devices, including Blackberry.</span></span>
  
### <a name="feature-availability"></a><span data-ttu-id="b4a99-179">功能可用性</span><span class="sxs-lookup"><span data-stu-id="b4a99-179">Feature availability</span></span>

<span data-ttu-id="b4a99-180">Outlook 为用户提供了从新式移动应用获得快速、直观的电子邮件和日历体验，同时成为唯一提供对最佳功能支持的应用。</span><span class="sxs-lookup"><span data-stu-id="b4a99-180">Outlook gives users the fast, intuitive email and calendar experience that they expect from a modern mobile app, while being the only app to provide support for the best features.</span></span> <span data-ttu-id="b4a99-181">这是唯一专门设计用于支持完整 Microsoft 体验的电子邮件应用，为用户提供从桌面到移动的一致体验。</span><span class="sxs-lookup"><span data-stu-id="b4a99-181">It is the only email app specifically designed to support the full Microsoft experience, giving users a coherent experience from desktop to mobile.</span></span> <span data-ttu-id="b4a99-182">Outlook 与 Intune、企业移动性和安全性以及 Exchange 控件集成在一起，以保持数据和用户的安全。</span><span class="sxs-lookup"><span data-stu-id="b4a99-182">Outlook is integrated with Intune, enterprise mobility and security, and Exchange controls to keep data and users safe.</span></span>
  
<span data-ttu-id="b4a99-183">使用 Outlook，用户可以：</span><span class="sxs-lookup"><span data-stu-id="b4a99-183">With Outlook, users can:</span></span>
  
- <span data-ttu-id="b4a99-184">通过移动设备管理其全天。</span><span class="sxs-lookup"><span data-stu-id="b4a99-184">Manage their entire day from a mobile device.</span></span>

- <span data-ttu-id="b4a99-185">连接到需要高效工作的应用和服务，同时使他们的工作和个人信息保持独立和安全。</span><span class="sxs-lookup"><span data-stu-id="b4a99-185">Connect to the apps and services they need to be productive, while keeping their work and personal information separate and secure.</span></span>

<span data-ttu-id="b4a99-186">使用 Outlook for iOS、Outlook for Android 或 Outlook for Windows Phone，用户可以：</span><span class="sxs-lookup"><span data-stu-id="b4a99-186">With Outlook for iOS, Outlook for Android, or Outlook for Windows Phone, users can:</span></span> 
  
- <span data-ttu-id="b4a99-187">从重点收件箱受益，该收件箱优先处理重要电子邮件</span><span class="sxs-lookup"><span data-stu-id="b4a99-187">Benefit from a focused inbox that priorities important email</span></span>

- <span data-ttu-id="b4a99-188">自定义轻扫手势以匹配其独特的电子邮件习惯</span><span class="sxs-lookup"><span data-stu-id="b4a99-188">Customize swipe gestures to match their unique email habits</span></span>

- <span data-ttu-id="b4a99-189">创建可直接添加到日历的旅行行程，关键信息一目了然</span><span class="sxs-lookup"><span data-stu-id="b4a99-189">Create travel itineraries that can be added directly to the calendar, with key information available at a glance</span></span>

- <span data-ttu-id="b4a99-190">从收件箱到会议的 RSVP。</span><span class="sxs-lookup"><span data-stu-id="b4a99-190">RSVP to meetings from the inbox.</span></span>

- <span data-ttu-id="b4a99-191">在电子邮件和日历约会中使用直观的图标，帮助他们快速处理信息</span><span class="sxs-lookup"><span data-stu-id="b4a99-191">Use intuitive icons in email and calendar appointments that help them process information quickly</span></span>

- <span data-ttu-id="b4a99-192">在所有设备上使用一致且熟悉的 Outlook 体验</span><span class="sxs-lookup"><span data-stu-id="b4a99-192">Use a consistent and familiar Outlook experience across all devices</span></span>

- <span data-ttu-id="b4a99-193">从日历轻松启动和加入 Skype 会议</span><span class="sxs-lookup"><span data-stu-id="b4a99-193">Easily launch and join Skype meetings from the calendar</span></span>

- <span data-ttu-id="b4a99-194">读取和响应 IRM 加密和受保护的电子邮件</span><span class="sxs-lookup"><span data-stu-id="b4a99-194">Read and respond to IRM encrypted and protected emails</span></span>

- <span data-ttu-id="b4a99-195">共享存储在 OneDrive for Business 中的文件</span><span class="sxs-lookup"><span data-stu-id="b4a99-195">Share files stored in OneDrive for Business</span></span>

- <span data-ttu-id="b4a99-196">设置点击的自动答复</span><span class="sxs-lookup"><span data-stu-id="b4a99-196">Set Automatic Replies with a tap</span></span>

- <span data-ttu-id="b4a99-197">查看和管理共享日历和委派日历</span><span class="sxs-lookup"><span data-stu-id="b4a99-197">View and manage shared and delegated calendars</span></span>

- <span data-ttu-id="b4a99-198">点击几下即可搜索其公司的全局地址列表</span><span class="sxs-lookup"><span data-stu-id="b4a99-198">Search their company's global address list with a few taps</span></span>

- <span data-ttu-id="b4a99-199">查看同事的可用性并安排适合所有人的会议时间</span><span class="sxs-lookup"><span data-stu-id="b4a99-199">View coworker's availability and schedule a meeting time that works for everyone</span></span>

- <span data-ttu-id="b4a99-200">请参阅被邀请者接受、暂定和拒绝状态</span><span class="sxs-lookup"><span data-stu-id="b4a99-200">See invitees accept, tentative, and decline status</span></span>

- <span data-ttu-id="b4a99-201">通过手机共享日历</span><span class="sxs-lookup"><span data-stu-id="b4a99-201">Share calendars right from their phones</span></span>

- <span data-ttu-id="b4a99-202">从日历开始并加入 Skype 会议</span><span class="sxs-lookup"><span data-stu-id="b4a99-202">Start and join Skype meetings right from a calendar</span></span>

- <span data-ttu-id="b4a99-203">在一个地方访问工作和个人日历，而无需切换应用</span><span class="sxs-lookup"><span data-stu-id="b4a99-203">Access work and personal calendars in one place, without switching apps</span></span>
    
## <a name="exchange-activesync"></a><span data-ttu-id="b4a99-204">Exchange ActiveSync</span><span class="sxs-lookup"><span data-stu-id="b4a99-204">Exchange ActiveSync</span></span>

<span data-ttu-id="b4a99-205">Exchange Online 支持 Microsoft Exchange ActiveSync 协议，这将在移动设备和 Exchange Online 之间同步邮箱，以便用户可以随身访问他们的电子邮件、日历、联系人和任务。</span><span class="sxs-lookup"><span data-stu-id="b4a99-205">Exchange Online supports the Microsoft Exchange ActiveSync protocol, which synchronizes mailbox data between mobile devices and Exchange Online, so users can access their email, calendar, contacts, and tasks on the go.</span></span>
  
<span data-ttu-id="b4a99-206">各种移动设备均使用 Exchange ActiveSync，包括 Microsoft Windows Phone、Apple iPhone 和 iPad 以及 Android 手机和平板电脑。</span><span class="sxs-lookup"><span data-stu-id="b4a99-206">A wide range of mobile devices work with Exchange ActiveSync, including Microsoft Windows Phone, Apple iPhone and iPad, and Android phones and tablets.</span></span> <span data-ttu-id="b4a99-207">除了移动电话和设备，Windows Phone 中的邮件应用程序还使用 Exchange ActiveSync 连接到 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="b4a99-207">In addition to mobile phones and devices, the Mail application in Windows Phone uses Exchange ActiveSync to connect to Exchange Online.</span></span> <span data-ttu-id="b4a99-208">有关当前 Exchange ActiveSync 被许可人的完整列表，请访问 Exchange ActiveSync 许可网站。</span><span class="sxs-lookup"><span data-stu-id="b4a99-208">A complete list of current Exchange ActiveSync licensees is available at the Exchange ActiveSync Licensing site.</span></span>
  
<span data-ttu-id="b4a99-209">有关此Exchange ActiveSync， [请参阅](/exchange/clients-and-mobile-in-exchange-online/clients-and-mobile-in-exchange-online)Exchange ActiveSync。</span><span class="sxs-lookup"><span data-stu-id="b4a99-209">For more information about Exchange ActiveSync, see [Exchange ActiveSync](/exchange/clients-and-mobile-in-exchange-online/clients-and-mobile-in-exchange-online).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="b4a99-210">每个邮箱的 Exchange ActiveSync 设备的最大数量为 100。</span><span class="sxs-lookup"><span data-stu-id="b4a99-210">The maximum number of Exchange ActiveSync devices per mailbox is 100.</span></span> 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a><span data-ttu-id="b4a99-211">使用 Exchange Web Services（EWS）开发的应用程序</span><span class="sxs-lookup"><span data-stu-id="b4a99-211">Applications developed with Exchange Web Services (EWS)</span></span>

 <span data-ttu-id="b4a99-212">通过使用 Exchange Web 服务 (EWS) 或 EWS 托管 API 开发的应用程序，管理员可以访问使用 Exchange Online 存储的、来自本地、Azure 或其他托管服务运行的应用程序的数据。</span><span class="sxs-lookup"><span data-stu-id="b4a99-212">Applications developed using Exchange Web Services (EWS) or the EWS Managed API let administrators access data stored with Exchange Online from applications that are running on-premises, in Azure, or in other hosted services.</span></span> 
  
<span data-ttu-id="b4a99-213">若要详细了解使用 Exchange Web 服务开发的应用程序，请参阅 [Exchange Web 服务](/exchange/client-developer/exchange-web-services/explore-the-ews-managed-api-ews-and-web-services-in-exchange)。</span><span class="sxs-lookup"><span data-stu-id="b4a99-213">For more information on applications developed with Exchange Web Services, see [Web Services in Exchange](/exchange/client-developer/exchange-web-services/explore-the-ews-managed-api-ews-and-web-services-in-exchange).</span></span>
  
## <a name="pop-and-imap"></a><span data-ttu-id="b4a99-214">POP 和 IMAP</span><span class="sxs-lookup"><span data-stu-id="b4a99-214">POP and IMAP</span></span>

<span data-ttu-id="b4a99-p114">Exchange Online 通过 POP3 和 IMAP4 协议支持邮箱访问。POP 和 IMAP 访问要求使用 SSL 加密。默认情况下，为所有用户启用 POP。用户可以在 Outlook 网页版中查看他们的 POP 和 IMAP 连接设置。管理员可以在每个用户的基础上禁用 POP 和 IMAP 访问。</span><span class="sxs-lookup"><span data-stu-id="b4a99-p114">Exchange Online supports mailbox access through both POP3 and IMAP4 protocols. POP and IMAP access requires encryption using SSL. POP is enabled by default for all users. Users can view their POP and IMAP connection settings in Outlook on the web. Administrators can disable POP and IMAP access on a per-user basis.</span></span>
  
<span data-ttu-id="b4a99-220">有关 POP3 和 IMAP4 连接性的详细信息，请参阅 [POP3 和 IMAP4](/exchange/pop3-and-imap4-in-exchange-server-2013-exchange-2013-help)。</span><span class="sxs-lookup"><span data-stu-id="b4a99-220">For more information about POP3 and IMAP4 connectivity, see [POP3 and IMAP4](/exchange/pop3-and-imap4-in-exchange-server-2013-exchange-2013-help).</span></span>
  
## <a name="smtp"></a><span data-ttu-id="b4a99-221">SMTP</span><span class="sxs-lookup"><span data-stu-id="b4a99-221">SMTP</span></span>

<span data-ttu-id="b4a99-p115">简单邮件传输协议 (SMTP) 用于为通过 IMAP 或 POP 连接到 Exchange Online 的客户端发送出站邮件。它是通过 Exchange Server 路由和递送的主协议。Exchange Online 支持两种类型的 SMTP 中继服务，用于需要 SMTP 邮件提交的授权内部客户应用程序：</span><span class="sxs-lookup"><span data-stu-id="b4a99-p115">Simple Mail Transfer Protocol (SMTP) is used to send outbound mail for clients that connect to Exchange Online through IMAP or POP. It is the primary protocol for routing and delivery through Exchange Server. Exchange Online supports two types of SMTP relay services for authorized internal customer applications that require SMTP mail submission:</span></span>
  
- <span data-ttu-id="b4a99-225">SMTP 邮件提交给托管环境内的用户。</span><span class="sxs-lookup"><span data-stu-id="b4a99-225">SMTP message submission to users inside the managed environment.</span></span>

- <span data-ttu-id="b4a99-226">通过身份验证的 SMTP 邮件中继到托管环境外的地址。</span><span class="sxs-lookup"><span data-stu-id="b4a99-226">Authenticated SMTP message relay to addresses outside the managed environment.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="b4a99-p116">授权源服务器的 IP 地址需要允许 SMTP 中继。当使用 SMTP 发送电子邮件时需要传输层安全性 (TLS) 加密和身份验证。</span><span class="sxs-lookup"><span data-stu-id="b4a99-p116">IP addresses for authorized source servers are required to allow SMTP relay. Transport Layer Security (TLS) encryption and authentication is required when using SMTP to send email.</span></span> 
  
## <a name="blackberry-devices"></a><span data-ttu-id="b4a99-229">BlackBerry 设备</span><span class="sxs-lookup"><span data-stu-id="b4a99-229">BlackBerry devices</span></span>

<span data-ttu-id="b4a99-230">BlackBerry 设备上可通过电子邮件 &reg; Exchange ActiveSync。</span><span class="sxs-lookup"><span data-stu-id="b4a99-230">Email is available on BlackBerry&reg; devices via Exchange ActiveSync.</span></span> <span data-ttu-id="b4a99-231">若要了解你的选项，请参阅以下主题：</span><span class="sxs-lookup"><span data-stu-id="b4a99-231">To find out what your options are, see these topics:</span></span>
  
- [<span data-ttu-id="b4a99-232">在 BlackBerry 设备上设置电子邮件</span><span class="sxs-lookup"><span data-stu-id="b4a99-232">Set up email on a BlackBerry device</span></span>](https://go.microsoft.com/fwlink/?linkid=863394)

- [<span data-ttu-id="b4a99-233">在 BlackBerry 设备 7.1 操作系统和更早版本上设置电子邮件</span><span class="sxs-lookup"><span data-stu-id="b4a99-233">Set up email on a BlackBerry device 7.1 OS and earlier</span></span>](https://go.microsoft.com/fwlink/?linkid=863403)

<span data-ttu-id="b4a99-234">有关详细信息，请参阅 [BlackBerry](../office-365-platform-service-description/blackberry.md)。</span><span class="sxs-lookup"><span data-stu-id="b4a99-234">For more information, see [BlackBerry](../office-365-platform-service-description/blackberry.md).</span></span>
  
> [!NOTE]
> <span data-ttu-id="b4a99-p118">如果使用的是由中国世纪互联运营的 Office 365，则 BlackBerry 商业云服务 不可用，但是你可以使用 Exchange ActiveSync 设备和 Research in Motion（RIM，BlackBerry 无线电子邮件解决方案）中的产品运行 Blackberry Enterprise Server (BES)。</span><span class="sxs-lookup"><span data-stu-id="b4a99-p118">If you are using Office 365 operated by 21Vianet in China, BlackBerry Business Cloud Services is not available. However, you can use Exchange ActiveSync devices or an offering from Research in Motion (RIM, the BlackBerry wireless email solution) to run Blackberry Enterprise Server (BES).</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="b4a99-237">功能可用性</span><span class="sxs-lookup"><span data-stu-id="b4a99-237">Feature availability</span></span>

<span data-ttu-id="b4a99-238">若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅 [Exchange Online 服务说明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="b4a99-238">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online service description](exchange-online-service-description.md).</span></span>
