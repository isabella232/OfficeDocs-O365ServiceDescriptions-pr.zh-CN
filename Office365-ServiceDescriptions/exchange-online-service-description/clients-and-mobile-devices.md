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
description: Exchange Online 适用于 Outlook 的桌面和移动版本，以及 Outlook 网页版。
ms.openlocfilehash: 4f72bb4f598a0c274b352163142f72b562fa2518
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173687"
---
# <a name="clients-and-mobile-devices"></a>客户端和移动设备

## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook 是一个电子邮件程序，包括对日历、联系人、任务和以下关键功能的支持：
  
- **MAPI over HTTP** - 通过 HTTP (MAPI) 的邮件应用程序接口允许 Outlook 用户从组织防火墙外部通过 Internet 连接到 Exchange Online 邮箱。 MAPI over HTTP，Outlook Anywhere 的长期替代项。 此连接方法改进了连接恢复能力、更安全的登录、可扩展性，并增强了 IT 和支持。 若要了解更多信息，请参阅[RPC over HTTP 到达 Office 365](/exchange/troubleshoot/administration/rpc-over-http-end-of-support)中的停止支持和[MAPI over HTTP。](/exchange/mapi-over-http-exchange-2013-help)

- **自动发现** - 自动发现服务功能自动配置 Outlook 以使用 Exchange Online。 首次使用电子邮件地址和密码登录时，Outlook 用户可以直接从 Exchange Online 收到他们的所需配置文件设置。 这些设置可以使用创建和维护用户配置文件所需的信息自动更新 Outlook 客户端。 使用自动发现服务需要 SSL 证书。 此 SSL 证书仅限于单个主 SSL 域。 

- **缓存 Exchange 模式** - 缓存 Exchange 模式功能允许 Outlook 用户在未连接到 Internet 时访问其 Exchange Online 邮箱的本地副本。 缓存 Exchange 模式在 Outlook 中保存用户 Exchange 邮箱的客户端副本，并与电子邮件服务器自动同步该副本。 我们建议在缓存 Exchange 模式中使用 Outlook，因为它提供脱机访问并帮助提供响应用户体验，即使客户端和服务器之间的网络条件不理想。 

默认情况下，所有用户启用 Outlook 访问。管理员可以通过 Windows PowerShell 禁用对特定用户的访问权限。我们建议使用最新版本的 Outlook装有最新的 service pack以访问 Exchange Online。 
  
有关 Exchange 2016 和 Exchange Online 支持哪些 Outlook 客户端的信息，请参阅[System Requirements for Office。](https://products.office.com/office-system-requirements) 

Microsoft 365 设计用于使用最新浏览器和 Office 版本。 如果你使用的旧版浏览器和 Office 版本不是主流支持：

- Microsoft 不会有意阻止你连接到服务，但用户体验的质量可能会随着时间的推移而降低。
- Microsoft 不会提供软件更新来解决与安全非相关的问题。

> [!IMPORTANT]
> Outlook 不作为 Exchange Online 订阅价格一部分提供。 Microsoft 365 企业应用版 (包括 Microsoft Outlook) 包含在一些计划中，可以单独订阅购买。 如果使用 POP 连接到 Exchange Online 电子邮件帐户，会发现存在以下限制：
> - 无日历信息
>- 无忙/闲信息
>- 无全局地址列表
>- 无电子邮件推送
>- 当通过 POP 连接时，所有邮件将下载到客户端，同时多台计算机或设备之间没有任何同步（如笔记本电脑和电话之间）。 
  
## <a name="outlook-on-the-web"></a>Web 上的 Outlook

Outlook 网页版是 Web 版 Outlook 电子邮件程序，可与 Exchange Online 结合使用。 它允许用户从任何连接到 Internet 的 Web 浏览器访问其电子邮件、日历和联系人。 若要了解支持的浏览器，请参阅 [Outlook 网页版支持的浏览器（适用于企业）](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006)。
  
Outlook 网页版具有两个客户端版本，这两个都可用于 Exchange Online：
  
- **Outlook 网页版** - 标准版 Outlook 网页版为 Exchange Online 用户提供与 Outlook 用户最相似的邮件体验。 它支持大部分新版 Web 浏览器，同时经过优化可用于平板电脑和智能电话以及台式机和笔记本电脑。 用户可以阅读和发送邮件、整理联系人，并能安排约会和会议。 基于活动的默认超时设置为 6 小时，但 [管理员可在 Windows PowerShell 中配置](/powershell/module/exchange/set-organizationconfig)为介于 5 分钟到 8 小时中的一个值。 此时间退出取决于 Web 应用中的用户交互，例如选择按钮或选择消息。 此外，还有单独的安全驱动超时，此超时不可配置，无论用户活动如何都会发生。 如果用户登录了 8 小时，OWA 会自动注销用户，并要求其重新进行身份验证。 

- **Outlook 网页** 版 Light version - Outlook 网页版 Light version provides Exchange Online users access to the mailbox using almost any web browser. 用户可以阅读和发送邮件、整理联系人，并能安排约会和会议。 基于活动的默认超时设置为 6 小时，但 [管理员可在 Windows PowerShell 中配置](/powershell/module/exchange/set-organizationconfig)为介于 5 分钟到 8 小时中的一个值。 此时间退出取决于 Web 应用中的用户交互，例如选择按钮或选择消息。 此外，还有单独的安全驱动超时，此超时不可配置，无论用户活动如何都会发生。 如果用户登录了 8 小时，OWA 会自动注销用户，并要求其重新进行身份验证。 

Outlook 网页版还提供移动版本。 有关详细信息，请参阅此[此页面](https://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409)。
  
## <a name="outlook-for-mac"></a>Outlook for Mac

Exchange Online 支持 Microsoft Outlook for Mac，它提供电子邮件、日历、通讯簿、任务列表和便笺列表。
  
## <a name="outlook-for-ios-android-and-windows-phone"></a>Outlook for iOS、Android 和 Windows Phone

Exchange Online 适用于适用于 iOS、Android 和 Windows Phone 的 Outlook 应用。 在任一设备上，使用应用商店查找 Outlook 应用。 下面按移动操作系统细分。<br><br>
  
| 设备 | Android | iOS | Windows Phone |
|:-----|:-----|:-----|:-----|
|Outlook 移动应用可用性  <br/> |是  <br/> [获取 Outlook for Android](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |是  <br/> [获取 Outlook for iOS](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |内置  <br/> |
|与 Exchange Online 兼容的内置电子邮件应用  <br/> |Gmail 应用/三星电子邮件应用  <br/> |iOS 邮件应用程序  <br/> |Outlook 邮件、日历、联系人  <br/> |
|更多信息  <br/> |[Android 移动设置](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[iPhone 或 iPad 设置](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[Windows Phone 设置](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |

还有一些选项用于将 Exchange Online 与设备（包括 Blackberry）一同使用。
  
### <a name="feature-availability"></a>功能可用性

Outlook 为用户提供了从新式移动应用获得快速、直观的电子邮件和日历体验，同时成为唯一提供对最佳功能支持的应用。 这是唯一专门设计用于支持完整 Microsoft 体验的电子邮件应用，为用户提供从桌面到移动的一致体验。 Outlook 与 Intune、企业移动性和安全性以及 Exchange 控件集成在一起，以保持数据和用户的安全。
  
使用 Outlook，用户可以：
  
- 通过移动设备管理其全天。

- 连接到需要高效工作的应用和服务，同时使他们的工作和个人信息保持独立和安全。

使用 Outlook for iOS、Outlook for Android 或 Outlook for Windows Phone，用户可以： 
  
- 从重点收件箱受益，该收件箱优先处理重要电子邮件

- 自定义轻扫手势以匹配其独特的电子邮件习惯

- 创建可直接添加到日历的旅行行程，关键信息一目了然

- 从收件箱到会议的 RSVP。

- 在电子邮件和日历约会中使用直观的图标，帮助他们快速处理信息

- 在所有设备上使用一致且熟悉的 Outlook 体验

- 从日历轻松启动和加入 Skype 会议

- 读取和响应 IRM 加密和受保护的电子邮件

- 共享存储在 OneDrive for Business 中的文件

- 设置点击的自动答复

- 查看和管理共享日历和委派日历

- 点击几下即可搜索其公司的全局地址列表

- 查看同事的可用性并安排适合所有人的会议时间

- 请参阅被邀请者接受、暂定和拒绝状态

- 通过手机共享日历

- 从日历开始并加入 Skype 会议

- 在一个地方访问工作和个人日历，而无需切换应用
    
## <a name="exchange-activesync"></a>Exchange ActiveSync

Exchange Online 支持 Microsoft Exchange ActiveSync 协议，这将在移动设备和 Exchange Online 之间同步邮箱，以便用户可以随身访问他们的电子邮件、日历、联系人和任务。
  
各种移动设备均使用 Exchange ActiveSync，包括 Microsoft Windows Phone、Apple iPhone 和 iPad 以及 Android 手机和平板电脑。 除了移动电话和设备，Windows Phone 中的邮件应用程序还使用 Exchange ActiveSync 连接到 Exchange Online。 有关当前 Exchange ActiveSync 被许可人的完整列表，请访问 Exchange ActiveSync 许可网站。
  
有关此Exchange ActiveSync， [请参阅](/exchange/clients-and-mobile-in-exchange-online/clients-and-mobile-in-exchange-online)Exchange ActiveSync。
  
> [!IMPORTANT]
> 每个邮箱的 Exchange ActiveSync 设备的最大数量为 100。 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a>使用 Exchange Web Services（EWS）开发的应用程序

 通过使用 Exchange Web 服务 (EWS) 或 EWS 托管 API 开发的应用程序，管理员可以访问使用 Exchange Online 存储的、来自本地、Azure 或其他托管服务运行的应用程序的数据。 
  
若要详细了解使用 Exchange Web 服务开发的应用程序，请参阅 [Exchange Web 服务](/exchange/client-developer/exchange-web-services/explore-the-ews-managed-api-ews-and-web-services-in-exchange)。
  
## <a name="pop-and-imap"></a>POP 和 IMAP

Exchange Online 通过 POP3 和 IMAP4 协议支持邮箱访问。POP 和 IMAP 访问要求使用 SSL 加密。默认情况下，为所有用户启用 POP。用户可以在 Outlook 网页版中查看他们的 POP 和 IMAP 连接设置。管理员可以在每个用户的基础上禁用 POP 和 IMAP 访问。
  
有关 POP3 和 IMAP4 连接性的详细信息，请参阅 [POP3 和 IMAP4](/exchange/pop3-and-imap4-in-exchange-server-2013-exchange-2013-help)。
  
## <a name="smtp"></a>SMTP

简单邮件传输协议 (SMTP) 用于为通过 IMAP 或 POP 连接到 Exchange Online 的客户端发送出站邮件。它是通过 Exchange Server 路由和递送的主协议。Exchange Online 支持两种类型的 SMTP 中继服务，用于需要 SMTP 邮件提交的授权内部客户应用程序：
  
- SMTP 邮件提交给托管环境内的用户。

- 通过身份验证的 SMTP 邮件中继到托管环境外的地址。

> [!IMPORTANT]
> 授权源服务器的 IP 地址需要允许 SMTP 中继。当使用 SMTP 发送电子邮件时需要传输层安全性 (TLS) 加密和身份验证。 
  
## <a name="blackberry-devices"></a>BlackBerry 设备

BlackBerry 设备上可通过电子邮件 &reg; Exchange ActiveSync。 若要了解你的选项，请参阅以下主题：
  
- [在 BlackBerry 设备上设置电子邮件](https://go.microsoft.com/fwlink/?linkid=863394)

- [在 BlackBerry 设备 7.1 操作系统和更早版本上设置电子邮件](https://go.microsoft.com/fwlink/?linkid=863403)

有关详细信息，请参阅 [BlackBerry](../office-365-platform-service-description/blackberry.md)。
  
> [!NOTE]
> 如果使用的是由中国世纪互联运营的 Office 365，则 BlackBerry 商业云服务 不可用，但是你可以使用 Exchange ActiveSync 设备和 Research in Motion（RIM，BlackBerry 无线电子邮件解决方案）中的产品运行 Blackberry Enterprise Server (BES)。 
  
## <a name="feature-availability"></a>功能可用性

若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅 [Exchange Online 服务说明](exchange-online-service-description.md)。
