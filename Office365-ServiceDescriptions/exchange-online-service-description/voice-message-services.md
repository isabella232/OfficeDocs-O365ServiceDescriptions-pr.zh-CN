---
title: 语音消息服务
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: 98591e47ece7c59581824c6df375c41c66b7d2d1
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035134"
---
# <a name="voice-message-services"></a>语音消息服务

## <a name="voice-mail"></a>语音邮件

Microsoft Exchange Online 提供托管语音邮件服务，其中包括：
  
- 电话应答（语音邮件）
    
- Exchange 的拨号用户界面 (Outlook Voice Access)
    
- 呼叫者的拨号界面（自动助理）
    
托管的语音邮件服务允许公司其本地电话系统连接到 Exchange Online 提供语音邮件服务。语音邮件消息记录和存储在 Exchange Online 的基础结构，允许用户从 Outlook、 Outlook web 或移动电话上的访问其语音邮件。所有电话连接到 Exchange Online 都要求的 IP 语音 (VoIP) 协议。管理员可以连接的本地 IP Pbx 或 PBX 电话系统使用 VoIP 媒体网关和到 Exchange Online 的会话边界控制器 (Sbc)。如果客户已经部署了 IP PBX，或者如果 PBX 直接支持 VoIP，进行互操作与 Exchange 语音消息服务，则不需要 VoIP 媒体网关。Sbc 中的客户网络连接的本地电话网络外围部署，并帮助防止窃听和入侵安全通信 （和客户网络）。此外支持与 Microsoft Lync Server 2010 和 2013年的语音功能互操作性。
  
语音消息 Exchange Online 中可用的服务功能类似于中提供的本地 Exchange 服务器 2016年。这些工具包括：
  
- 在电话上播放 Outlook 和 Outlook web 上。
    
- 未接来电通知。
    
- 呼叫者 ID（使用全局地址列表中的信息、用户的个人联系人、自定义联系人文件夹、以及外部社交网络的联系人）。
    
- 语音邮件 PIN 从 Outlook （请参阅[重置语音邮件 PIN](https://go.microsoft.com/fwlink/p/?LinkId=286328)） 的 web 和 Outlook 重置。
    
- 邮件等待指示器（有关详细信息，请参阅 [Exchange Online 中的 MWI](https://go.microsoft.com/fwlink/p/?LinkId=271794)）。 
    
- 电话应答规则（有关详细信息，请参阅[允许语音邮件用户转接来电](https://go.microsoft.com/fwlink/p/?LinkId=271795)）。 
    
- Exchange Online 中受保护的语音邮件（有关详细信息，请参阅 [Protected Voice Mail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271796)（Exchange Online 中受保护的语音邮件））。 
    
- 语音邮件预览（有关支持的语言列表，请参阅 [Allow Users to See a Voice Mail Transcript](https://go.microsoft.com/fwlink/p/?LinkId=271797)（允许用户查看语音邮件转录））。 
    
- 语音访问电子邮件、语音邮件、日历、个人联系人和个人联系人组。
    
- 通过 Outlook Voice Access 或自动助理进行目录搜索。
    
- 管理员使用 Exchange 管理中心 (EAC) 配置并管理语音留言服务的互操作性。
    
有关语音邮件功能的详细信息，请参阅 [Exchange Online 中的语音邮件](https://go.microsoft.com/fwlink/p/?LinkId=271798)。
  
> [!IMPORTANT]
> 对于 Outlook Voice Access 用户或使用语音命令的自动助理呼叫者，自动语言识别 (ASR) 功能在菜单导航或目录搜索中不可用。 > 客户必须使用 VoIP 网关和 PBX、IP PBX 或 Skype for Business Server 2015 提供来自公用电话交换网 (PSTN) 的电话连接。 > 客户必须提供内部 SBC 硬件设备，并确保 SBC 已正确配置为连接到联机语音邮件服务。这包括通过使用证书以及公用和专用 IP 接口，并支持正确的 TCP 端口通过内部防火墙，从而配置适当的安全级别。 > 只有 Exchange Online 计划 2 和 Office 365 企业版 E3 订阅者才能使用托管语音邮件。 
  
## <a name="third-party-voice-mail-interoperability"></a>第三方语音邮件互操作性

如果第三方提供商提供的内部语音留言解决方案能够通过 SMTP 转发语音留言，或者支持 Microsoft Exchange Web 服务，则可与 Exchange Online 进行互操作。如果语音邮件系统本身不支持通过 SMTP 转发语音留言，则电子邮件服务器可保存在内部，以便接收语音邮件系统中的邮件，然后使用 SMTP 将其转发到云。由于许多第三方语音邮件系统均使用 MAPI/CDO 与 Exchange Server 进行互操作，以便提供高级 UM 功能，因此当 SMTP 用于与 Exchange Online 进行互操作时，这些系统的完整功能将无法使用。
  
> [!NOTE]
> Exchange Online UM 支持第三方 PBX 系统通过直接从客户的客户 Sbc 连接将在年 7 月 2018年结束。请有关详细信息，参阅[终止的会话边界控制器在 Exchange Online 统一消息支持](https://blogs.technet.microsoft.com/exchange/2017/07/18/discontinuation-of-support-for-session-border-controllers-in-exchange-online-unified-messaging/)。 
  
## <a name="skype-for-business-integration"></a>Skype for Business 集成

作为独立的服务或 Microsoft Office 365 的一部分，组织可以为业务联机购买 Skype。为业务 2015年本地 Skype 还支持。若要了解业务 online 有关 Skype 的详细信息，请参阅[Skype for Business Online 服务说明](../skype-for-business-online-service-description/skype-for-business-online-service-description.md)。
  
## <a name="feature-availability"></a>功能可用性

若要查看在各个 Office 365 计划、独立选项和内部部署解决方案之间的功能可用性，请参阅 [Exchange Online 服务说明](exchange-online-service-description.md)。
  

