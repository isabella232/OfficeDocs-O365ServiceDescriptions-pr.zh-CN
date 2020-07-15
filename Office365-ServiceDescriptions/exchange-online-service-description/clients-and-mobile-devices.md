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
# <a name="clients-and-mobile-devices"></a>客户端和移动设备

## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook 是一个电子邮件程序，其中包括对日历、联系人、任务和以下关键功能的支持：
  
- **MAPI OVER HTTP**通过 HTTP 的邮件应用程序接口（MAPI）允许 Outlook 用户从其组织的防火墙外部连接到 internet 上的 Exchange Online 邮箱。 MAPI over HTTP，适用于 Outlook 无处不在的长期替换。 此连接方法提供改进的连接弹性、更安全的登录、可扩展性以及 IT 和支持的增强功能。 若要了解详细信息，请参阅[RPC OVER http 在 Office 365](https://go.microsoft.com/fwlink/?linkid=863890)和[MAPI over http](https://go.microsoft.com/fwlink/?linkid=393041)中达到支持的结尾。

- **Autodiscover** The Autodiscover service feature automatically configures Outlook to work with Exchange Online. Outlook users can receive their required profile settings directly from Exchange Online the first time they sign in with their email address and password. These settings automatically update the Outlook client with the information necessary to create and maintain the user's profile. An SSL certificate is required to use the Autodiscover service. This SSL certificate is limited to a single primary SSL domain. 

- **缓存 Exchange 模式**当 Outlook 用户未连接到 internet 时，缓存 Exchange 模式功能允许 Outlook 用户访问其 Exchange Online 邮箱的本地副本。 缓存 Exchange 模式在 Outlook 中保存用户 Exchange 邮箱的客户端副本，并与电子邮件服务器自动同步该副本。 我们建议在缓存 Exchange 模式中使用 Outlook，因为它提供脱机访问并帮助提供响应用户体验，即使客户端和服务器之间的网络条件不理想。 

By default, Outlook access is enabled for all users. Administrators can disable access for specific users or groups through Windows PowerShell. We recommend using the latest version of Outlook—with the latest service pack installed—to access Exchange Online. 
  
有关 Exchange 2016 和 Exchange Online 支持的 Outlook 客户端的信息，请参阅[Office 的系统要求](https://products.office.com/office-system-requirements)。 

Microsoft 365 旨在适用于 Office 的最新浏览器和版本。 如果使用的是旧版不在主流支持中的浏览器和 Office 版本：

- Microsoft 不会有意阻止您连接到该服务，但您的体验质量可能会随着时间的推移而降低。
- Microsoft 不会提供软件更新来解决与安全无关的问题。

> [!IMPORTANT]
>  Outlook 不作为 Exchange Online 订阅价格一部分提供。 Microsoft 365 企业版应用程序（包括 Microsoft Outlook）包含在一些计划中，可以作为单独的订阅进行购买。 如果您使用 POP 连接到 Exchange Online 电子邮件帐户，您将看到以下限制： > 无日历信息 > 无 > 全局地址列表 > 没有推送电子邮件 > 通过 POP 连接时，所有邮件都将下载到客户端，并且在多台计算机或设备（如膝上型电脑和手机之间）之间不会进行任何同步。 
  
## <a name="outlook-on-the-web"></a>Web 上的 Outlook

Outlook 网页版是 Web 版 Outlook 电子邮件程序，可与 Exchange Online 结合使用。 它允许用户通过 web 浏览器访问其电子邮件、日历和联系人（无论它们连接到 internet）。 若要了解支持的浏览器，请参阅 [Outlook 网页版支持的浏览器（适用于企业）](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006)。
  
Outlook 网页版具有两个客户端版本，这两个都可用于 Exchange Online：
  
- **Outlook 网页版** 标准的 Outlook 网页版为 Exchange Online 用户提供最类似于 Outlook 用户的邮件体验。 它支持大部分新版 Web 浏览器，同时经过优化可用于平板电脑和智能电话以及台式机和笔记本电脑。 用户可以阅读和发送邮件、整理联系人，并能安排约会和会议。 基于活动的默认超时设置为 6 小时，但 [管理员可在 Windows PowerShell 中配置](https://go.microsoft.com/fwlink/p/?LinkId=399155)为介于 5 分钟到 8 小时中的一个值。 此超时取决于用户在 web 应用程序中的交互，例如，选择一个按钮或选择一封邮件。 此外，还有单独的安全驱动超时，此超时不可配置，无论用户活动如何都会发生。 如果用户登录了 8 小时，OWA 会自动注销用户，并要求其重新进行身份验证。 

- **轻型 Outlook 网页版** 使用轻型 Outlook 网页版，Exchange Online 用户可以使用几乎所有 Web 浏览器访问邮箱。 用户可以阅读和发送邮件、整理联系人，并能安排约会和会议。 基于活动的默认超时设置为 6 小时，但 [管理员可在 Windows PowerShell 中配置](https://go.microsoft.com/fwlink/p/?LinkId=399155)为介于 5 分钟到 8 小时中的一个值。 此超时取决于用户在 web 应用程序中的交互，例如，选择一个按钮或选择一封邮件。 此外，还有单独的安全驱动超时，此超时不可配置，无论用户活动如何都会发生。 如果用户登录了 8 小时，OWA 会自动注销用户，并要求其重新进行身份验证。 

Outlook 网页版还提供移动版本。 有关详细信息，请参阅此[此页面](https://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409)。
  
## <a name="outlook-for-mac"></a>Outlook for Mac

Exchange Online 支持 Microsoft Outlook for Mac，它提供电子邮件、日历、通讯簿、任务列表和便笺列表。
  
## <a name="outlook-for-ios-android-and-windows-phone"></a>适用于 iOS、Android 和 Windows Phone 的 Outlook

Exchange Online 适用于适用于 iOS、Android 和 Windows Phone 的 Outlook 应用程序。 在这些设备中的任何设备上，使用应用商店查找 Outlook 应用程序。 以下是移动 OS 的细目分类。
  
|||||
|:-----|:-----|:-----|:-----|
|设备  <br/> |Android  <br/> |iOS  <br/> |Windows Phone  <br/> |
|Outlook 移动应用可用性  <br/> |是  <br/> [获取适用于 Android 的 Outlook](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |是  <br/> [获取适用于 iOS 的 Outlook](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |内置  <br/> |
|与 Exchange Online 兼容的内置电子邮件应用程序  <br/> |Gmail app/Samsung 电子邮件应用程序  <br/> |iOS 邮件应用程序  <br/> |Outlook 邮件、日历、联系人  <br/> |
|更多信息  <br/> |[Android 手机设置](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[iPhone 或 iPad 安装程序](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[Windows Phone 安装程序](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |

此外，还提供了有关将 Exchange Online 与设备（包括 Blackberry）结合使用的选项。
  
### <a name="feature-availability"></a>功能可用性

Outlook 为用户提供了从新式移动应用程序获得的快速、直观的电子邮件和日历体验，同时也是唯一可提供最佳功能支持的应用程序。 它是唯一专为支持完整的 Microsoft 体验而设计的电子邮件应用程序，为用户提供桌面到移动的一致体验。 Outlook 与 Intune、企业移动性和安全性以及 Exchange 控件相集成，以保持数据和用户安全。
  
通过 Outlook，用户可以：
  
- 从移动设备管理其全天。

- 连接到需要提高工作效率的应用程序和服务，同时保持其工作和个人信息的安全。

使用 Outlook for iOS、Outlook for Android 或 Outlook for Windows Phone，用户可以： 
  
- 受益于重点收件箱的优先级重要电子邮件

- 自定义轻扫手势以适应其独特的电子邮件习惯

- 创建可直接添加到日历中的旅行路线，并提供概览的关键信息

- 从收件箱到会议的 RSVP。

- 在电子邮件和日历约会中使用直观图标帮助他们快速处理信息

- 在所有设备中使用一致和熟悉的 Outlook 体验

- 轻松启动和加入日历中的 Skype 会议

- 阅读和响应 IRM 加密和受保护的电子邮件

- 共享 OneDrive for Business 中存储的文件

- 通过点击设置自动答复

- 查看和管理共享和委派的日历

- 通过几分路器搜索其公司的全球通讯簿

- 查看同事的可用性并安排适用于每个人的会议时间

- 请参阅被邀请者接受、暂定和拒绝状态

- 从电话中共享日历

- 从日历中启动和加入 Skype 会议

- 在一个位置访问工作和个人日历，而无需切换应用程序
    
## <a name="exchange-activesync"></a>Exchange ActiveSync

Exchange Online 支持 Microsoft Exchange ActiveSync 协议，这将在移动设备和 Exchange Online 之间同步邮箱，以便用户可以随身访问他们的电子邮件、日历、联系人和任务。
  
各种移动设备均使用 Exchange ActiveSync，包括 Microsoft Windows Phone、Apple iPhone 和 iPad 以及 Android 手机和平板电脑。 除了移动电话和设备，Windows Phone 中的邮件应用程序还使用 Exchange ActiveSync 连接到 Exchange Online。 有关当前 Exchange ActiveSync 被许可人的完整列表，请访问 Exchange ActiveSync 许可网站。
  
有关 Exchange ActiveSync 的详细信息，请参阅[Exchange activesync](https://go.microsoft.com/fwlink/p/?LinkId=271792)。
  
> [!IMPORTANT]
> 每个邮箱的 Exchange ActiveSync 设备的最大数量为 100。 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a>使用 Exchange Web Services（EWS）开发的应用程序

 通过使用 Exchange Web 服务 (EWS) 或 EWS 托管 API 开发的应用程序，管理员可以访问使用 Exchange Online 存储的、来自本地、Azure 或其他托管服务运行的应用程序的数据。 
  
若要详细了解使用 Exchange Web 服务开发的应用程序，请参阅 [Exchange Web 服务](https://go.microsoft.com/fwlink/?LinkId=325346)。
  
## <a name="pop-and-imap"></a>POP 和 IMAP

Exchange Online supports mailbox access through both POP3 and IMAP4 protocols. POP and IMAP access requires encryption using SSL. POP is enabled by default for all users. Users can view their POP and IMAP connection settings in Outlook on the web. Administrators can disable POP and IMAP access on a per-user basis.
  
有关 POP3 和 IMAP4 连接性的详细信息，请参阅 [POP3 和 IMAP4](https://go.microsoft.com/fwlink/p/?LinkId=272070)。
  
## <a name="smtp"></a>SMTP

Simple Mail Transfer Protocol (SMTP) is used to send outbound mail for clients that connect to Exchange Online through IMAP or POP. It is the primary protocol for routing and delivery through Exchange Server. Exchange Online supports two types of SMTP relay services for authorized internal customer applications that require SMTP mail submission:
  
- SMTP 邮件提交给托管环境内的用户。

- 通过身份验证的 SMTP 邮件中继到托管环境外的地址。

> [!IMPORTANT]
> IP addresses for authorized source servers are required to allow SMTP relay. Transport Layer Security (TLS) encryption and authentication is required when using SMTP to send email. 
  
## <a name="blackberryreg-devices"></a>BlackBerry &reg; 设备

可通过 Exchange ActiveSync 在 BlackBerry 设备上提供电子邮件 &reg; 。 若要了解你的选项是什么，请参阅以下主题：
  
- [在 BlackBerry 设备上设置电子邮件](https://go.microsoft.com/fwlink/?linkid=863394)

- [在 BlackBerry 设备 7.1 OS 和更低版本上设置电子邮件](https://go.microsoft.com/fwlink/?linkid=863403)

有关详细信息，请参阅 [BlackBerry](../office-365-platform-service-description/blackberry.md)。
  
> [!NOTE]
> If you are using Office 365 operated by 21Vianet in China, BlackBerry Business Cloud Services is not available. However, you can use Exchange ActiveSync devices or an offering from Research in Motion (RIM, the BlackBerry wireless email solution) to run Blackberry Enterprise Server (BES). 
  
## <a name="feature-availability"></a>功能可用性

若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅[Exchange Online 服务说明](exchange-online-service-description.md)。
  