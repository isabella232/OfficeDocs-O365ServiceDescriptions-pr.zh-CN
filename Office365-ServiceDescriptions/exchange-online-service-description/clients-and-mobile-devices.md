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
# <a name="clients-and-mobile-devices"></a>客户端和移动设备

## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook 是一个电子邮件程序，包括支持日历、 联系人、 任务和以下关键功能：
  
- **MAPI over HTTP**通过 HTTP 消息应用程序接口 (MAPI) 允许 Outlook 用户通过 Internet 从其组织的防火墙之外连接到 Exchange Online 邮箱。MAPI over HTTP，长期替换为 Outlook Anywhere。此连接方法提供了改进了的连接恢复能力、 更安全登录、 扩展性，以及增强 IT 和支持。若要了解详细信息，请参阅[RPC over HTTP 达到结束的 Office 365 中的支持](https://go.microsoft.com/fwlink/?linkid=863890)和[MAPI over HTTP](https://go.microsoft.com/fwlink/?linkid=393041)。
    
- **自动发现** 自动发现服务功能自动配置 Outlook 以用于 Exchange Online。首次使用电子邮件地址和密码登录时，Outlook 用户可以直接从 Exchange Online 收到他们的所需配置文件设置。这些设置可以使用创建和维护用户配置文件所需的信息自动更新 Outlook 客户端。使用自动发现服务需要 SSL 证书。此 SSL 证书仅限于单个主 SSL 域。 
    
- **缓存 Exchange 模式** 缓存 Exchange 模式功能允许 Outlook 用户在未连接到互联网时访问其 Exchange Online 邮箱的本地副本。缓存 Exchange 模式在 Outlook 中保存用户 Exchange 邮箱的客户端副本，并与电子邮件服务器自动同步该副本。我们建议在缓存 Exchange 模式中使用 Outlook，因为它提供脱机访问并帮助提供响应用户体验，即使客户端和服务器之间的网络条件不理想。 
    
默认情况下，所有用户启用 Outlook 访问。管理员可以通过 Windows PowerShell 禁用对特定用户的访问权限。我们建议使用最新版本的 Outlook装有最新的 service pack以访问 Exchange Online。 
  
若要了解 Exchange 2016 和 Exchange Online 支持的 Outlook 客户端，请参阅 [Exchange 2016 系统要求](https://go.microsoft.com/fwlink/?LinkID=828972)中的"支持的客户端"。
  
> [!IMPORTANT]
>  Outlook 不作为 Exchange Online 订阅价格一部分提供。Microsoft Office Pro Plus（包括 Microsoft Outlook）包含在一些 Office 365 计划中，同时可以作为单独订阅购买。 >  如果使用 POP 连接到 Exchange Online 电子邮件帐户，会发现存在以下限制： >  无日历信息 >  无忙/闲信息 >  无全局地址列表 >  无电子邮件推送 >  当通过 POP 连接时，所有邮件将下载到客户端，同时多台计算机或设备之间没有任何同步（如笔记本电脑和电话之间）。 
  
## <a name="outlook-on-the-web"></a>Web 上的 Outlook

Outlook 网页版是 Web 版 Outlook 电子邮件程序，可与 Exchange Online 结合使用。使用它，用户可以在有 Internet 连接的地方，通过 Web 浏览器查看电子邮件、日历和联系人。若要了解支持的浏览器，请参阅 [Outlook 网页版支持的浏览器（适用于企业）](https://go.microsoft.com/fwlink/p/?LinkId=287032)。
  
Outlook 网页版具有两个客户端版本，这两个都可用于 Exchange Online：
  
- **Outlook 网页版** 标准的 Outlook 网页版为 Exchange Online 用户提供最类似于 Outlook 用户的邮件体验。它支持大部分新版 Web 浏览器，同时经过优化可用于平板电脑和智能电话以及台式机和笔记本电脑。用户可以阅读和发送邮件、整理联系人，并能安排约会和会议。基于活动的默认超时设置为 6 小时，但 [管理员可在 Windows PowerShell 中配置](https://go.microsoft.com/fwlink/p/?LinkId=399155)为介于 5 分钟到 8 小时中的一个值。此超时取决于 Web 应用中的用户交互，如单击按钮或选择邮件。此外，还有单独的安全驱动超时，此超时不可配置，无论用户活动如何都会发生。如果用户登录了 8 小时，OWA 会自动注销用户，并要求其重新进行身份验证。 
    
- **轻型 Outlook 网页版** 使用轻型 Outlook 网页版，Exchange Online 用户可以使用几乎所有 Web 浏览器访问邮箱。用户可以阅读和发送邮件、整理联系人，并能安排约会和会议。基于活动的默认超时设置为 6 小时，但 [管理员可在 Windows PowerShell 中配置](https://go.microsoft.com/fwlink/p/?LinkId=399155)为介于 5 分钟到 8 小时中的一个值。此超时取决于 Web 应用中的用户交互，如单击按钮或选择邮件。此外，还有单独的安全驱动超时，此超时不可配置，无论用户活动如何都会发生。如果用户登录了 8 小时，OWA 会自动注销用户，并要求其重新进行身份验证。 
    
Outlook 网页版还提供移动版本。有关详细信息，请参阅此[此页面](http://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409)。
  
## <a name="outlook-for-mac"></a>Outlook for Mac

Exchange Online 支持 Microsoft Outlook for Mac，它提供电子邮件、 日历、 通讯簿、 任务列表和便笺列表。
  
## <a name="outlook-for-ios-android-and-windows-phone"></a>IOS、 Android，和 Windows Phone 的 outlook

Exchange Online 适用于 Outlook 相关应用程序可用于 iOS、 Android 和 Windows Phone。在任何这些设备上使用应用程序商店找到 Outlook 应用程序。下面是通过移动 OS 细分。
  
|||||
|:-----|:-----|:-----|:-----|
|设备  <br/> |Android  <br/> |iOS  <br/> |Windows Phone  <br/> |
|Outlook 移动应用程序可用性  <br/> |是  <br/> [获取 Outlook for Android](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |是  <br/> [获取适用于 iOS 的 Outlook](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |内置  <br/> |
|与 Exchange Online 兼容的内置电子邮件应用程序  <br/> |Gmail 应用程序/三星电子邮件应用程序  <br/> |iOS 邮件应用程序  <br/> |Outlook 邮件、 日历、 联系人  <br/> |
|更多信息  <br/> |[Android 移动安装程序](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[iPhone 或 iPad 的安装程序](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[Windows Phone 安装程序](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |
   
还有设备，包括 Blackberry 使用 Exchange Online 的选项。
  
### <a name="feature-availability"></a>功能可用性

Outlook 中，为用户提供快速、 直观电子邮件和日历体验，他们希望从现代的移动应用程序时要仅应用程序的 Office 365 的最佳功能提供支持。它是唯一电子邮件应用程序专门用于支持完整的 Office 365 体验，请为用户提供一致的体验从桌面到移动。Outlook 与 Intune、 企业移动性和安全性和 Exchange 控件，以保护数据和用户安全集成。
  
Outlook 使用户能够：
  
- 从移动设备管理其整个天。
    
- 连接到的应用程序和服务所需提高生产效率，同时保持其工作和个人信息单独和安全。
    
使用 Outlook 针对 iOS，for Android，Outlook 或 Outlook for Windows Phone，用户可以： 
  
- 受益于重点收件箱的优先级重要电子邮件
    
- 自定义向内轻扫手势匹配其唯一的电子邮件习惯
    
- 创建可以添加直接到日历，提供快速的关键信息的旅行路线
    
- 从收件箱 RSVP 加入会议。
    
- 帮助他们快速处理信息的电子邮件和日历约会在使用直观的图标
    
- 在所有设备上使用一致和熟悉的 Outlook 体验
    
- 轻松启动并加入 Skype 会议从日历
    
- 读取和响应 IRM 加密和受保护的电子邮件
    
- OneDrive for Business 中存储的共享文件
    
- 设置与点击的自动答复
    
- 查看和管理共享和委派日历
    
- 搜索与几次点击其公司的全局地址列表
    
- 查看同事的可用性和计划的会议时间的适用于所有人
    
- 请参阅被邀请者暂定接受和拒绝状态
    
- 共享日历直接从其电话
    
- 开始和加入 Skype 会议右从日历
    
- 访问工作和个人日历在一个位置，而无需切换应用程序
    
## <a name="exchange-activesync"></a>Exchange ActiveSync

Exchange Online 支持 Microsoft Exchange ActiveSync 协议，这将在移动设备和 Exchange Online 之间同步邮箱，以便用户可以随身访问他们的电子邮件、日历、联系人和任务。
  
范围广泛的移动设备使用 Exchange ActiveSync，包括 Microsoft Windows Phone、 Apple iPhone 和 iPad 和 Android 电话和平板电脑中。除了移动电话和设备，在 Windows Phone 中的邮件应用程序使用 Exchange ActiveSync 连接到 Exchange Online。在 Exchange ActiveSync 许可站点位于当前 Exchange ActiveSync 许可证的完整列表。
  
有关 Exchange ActiveSync 的详细信息，请参阅[Exchange ActiveSync](https://go.microsoft.com/fwlink/p/?LinkId=271792)。
  
> [!IMPORTANT]
> 每个邮箱的 Exchange ActiveSync 设备的最大数量为 100。 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a>使用 Exchange Web Services（EWS）开发的应用程序

 通过使用 Exchange Web 服务 (EWS) 或 EWS 托管 API 开发的应用程序，管理员可以访问使用 Exchange Online 存储的、来自本地、Azure 或其他托管服务运行的应用程序的数据。 
  
若要详细了解使用 Exchange Web 服务开发的应用程序，请参阅 [Exchange Web 服务](https://go.microsoft.com/fwlink/?LinkId=325346)。
  
## <a name="pop-and-imap"></a>POP 和 IMAP

Exchange Online 通过 POP3 和 IMAP4 协议支持邮箱访问。POP 和 IMAP 访问要求使用 SSL 加密。默认情况下，为所有用户启用 POP。用户可以在 Outlook 网页版中查看他们的 POP 和 IMAP 连接设置。管理员可以在每个用户的基础上禁用 POP 和 IMAP 访问。
  
有关 POP3 和 IMAP4 连接性的详细信息，请参阅 [POP3 和 IMAP4](https://go.microsoft.com/fwlink/p/?LinkId=272070)。
  
## <a name="smtp"></a>SMTP

简单邮件传输协议 (SMTP) 用于为通过 IMAP 或 POP 连接到 Exchange Online 的客户端发送出站邮件。它是通过 Exchange Server 路由和递送的主协议。Exchange Online 支持两种类型的 SMTP 中继服务，用于需要 SMTP 邮件提交的授权内部客户应用程序：
  
- SMTP 邮件提交给托管环境内的用户。
    
- 通过身份验证的 SMTP 邮件中继到托管环境外的地址。
    
> [!IMPORTANT]
> 授权源服务器的 IP 地址需要允许 SMTP 中继。当使用 SMTP 发送电子邮件时需要传输层安全性 (TLS) 加密和身份验证。 
  
## <a name="blackberry-devices"></a>BlackBerry® 设备

Office 365 电子邮件是通过 Exchange ActiveSync BlackBerry® 设备上可用。若要查找什么是您的选项，请参阅下列主题：
  
- [将 BlackBerry 设备上的电子邮件设置](https://go.microsoft.com/fwlink/?linkid=863394)
    
- [BlackBerry 设备 7.1 上设置电子邮件 OS 和更早版本](https://go.microsoft.com/fwlink/?linkid=863403)
    
有关详细信息，请参阅 [BlackBerry](../office-365-platform-service-description/blackberry.md)。
  
> [!NOTE]
> 如果使用的是由中国世纪互联运营的 Office 365，则 BlackBerry 商业云服务 不可用，但是你可以使用 Exchange ActiveSync 设备和 Research in Motion（RIM，BlackBerry 无线电子邮件解决方案）中的产品运行 Blackberry Enterprise Server (BES)。 
  
## <a name="feature-availability"></a>功能可用性

若要查看在各个 Office 365 计划、独立选项和内部部署解决方案之间的功能可用性，请参阅 [Exchange Online 服务说明](exchange-online-service-description.md)。
  

