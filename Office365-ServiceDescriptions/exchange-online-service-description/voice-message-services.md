---
title: 语音消息服务
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: 23cc82d51d1afcbd2662e86dd6bc2aeebfb22346
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652676"
---
# <a name="voice-message-services"></a>语音消息服务

## <a name="voice-mail"></a>语音邮件

Microsoft Exchange Online 提供托管语音邮件服务，其中包括：
  
- 电话应答（语音邮件）
    
- Exchange 的拨号用户界面 (Outlook Voice Access)
    
- 呼叫者的拨号界面（自动助理）
    
托管语音留言服务允许公司将内部电话系统连接到 Exchange Online 提供的语音留言服务中。 语音邮件记录和存储在 Exchange Online 基础结构中，允许用户从 Outlook、Outlook 网页版或移动电话访问其语音邮件。 所有与 Exchange Online 的电话连接均需使用 voice-over-IP (VoIP) 协议。 通过使用 VoIP 介质网关和会话边界控制器 (SBC)，管理员可以将内部 IP PBX 或 PBX 电话系统连接到 Exchange Online。 如果客户已部署 IP PBX，或者 PBX 直接支持 VoIP 且可与 Exchange 语音留言服务进行互操作，则无需使用 VoIP 介质。 SBC 部署在客户网络外围且与内部电话网络连接，有助于确保通信（和客户网络）安全，防止窃听和入侵。 此外，它还支持与 Microsoft Lync Server 2010 和 2013 语音功能的互操作性。
  
Exchange Online 中提供的语音邮件服务功能与 2016 年本地部署中提供的Exchange Server功能类似。 具体包括：
  
- 从 Outlook 和 Web 上的 Outlook 在电话上播放。
    
- 未接来电通知。
    
- 呼叫者 ID（使用全局地址列表中的信息、用户的个人联系人、自定义联系人文件夹、以及外部社交网络的联系人）。
    
- 从 Outlook 网页和 Outlook 网页中的语音邮件 PIN 重置 (重置 [语音邮件 PIN](/exchange/voice-mail-unified-messaging/set-outlook-voice-access-pin-security/reset-a-voice-mail-pin)) 。
    
- 邮件等待指示器（有关详细信息，请参阅 [Exchange Online 中的 MWI](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/mwi-in-exchange-online)）。 
    
- 呼叫应答规则 (请参阅 [允许语音邮件](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-voice-mail-users-to-forward-calls) 用户转发呼叫，了解) 。
    
- Exchange Online 中的受保护语音邮件 (请参阅保护 [Exchange Online](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/protect-voice-mail) 中的语音邮件，了解) 。
    
- 语音邮件预览 (请参阅允许用户 [查看](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-users-to-see-a-voice-mail-transcript) 语音邮件脚本，了解支持的语言列表) 。
    
- 语音访问电子邮件、语音邮件、日历、个人联系人和个人联系人组。
    
- 通过 Outlook Voice Access 或自动助理进行目录搜索。
    
- 管理员使用 Exchange 管理中心 (EAC) 配置并管理语音留言服务的互操作性。
    
有关语音邮件功能的信息，请参阅 Exchange [Online 中的语音邮件](/exchange/voice-mail-unified-messaging/voice-mail-unified-messaging)。
  
> [!IMPORTANT]
> 对于 Outlook Voice Access 用户或使用语音命令的自动助理呼叫者，自动语言识别 (ASR) 功能在菜单导航或目录搜索中不可用。 
>
> 客户必须使用 VoIP 网关和 PBX、IP PBX 或 Skype for Business Server 2015 提供来自公用电话交换网 (PSTN) 的电话连接。 
>
> 客户必须提供内部 SBC 硬件设备，并确保 SBC 已正确配置为连接到联机语音邮件服务。这包括通过使用证书以及公用和专用 IP 接口，并支持正确的 TCP 端口通过内部防火墙，从而配置适当的安全级别。 
>
> 托管语音邮件仅适用于 Exchange Online 计划 2 和 Office 365 企业版 E3 订阅者。 
  
## <a name="third-party-voice-mail-interoperability"></a>第三方语音邮件互操作性

如果第三方提供商提供的内部语音留言解决方案能够通过 SMTP 转发语音留言，或者支持 Microsoft Exchange Web 服务，则可与 Exchange Online 进行互操作。如果语音邮件系统本身不支持通过 SMTP 转发语音留言，则电子邮件服务器可保存在内部，以便接收语音邮件系统中的邮件，然后使用 SMTP 将其转发到云。由于许多第三方语音邮件系统均使用 MAPI/CDO 与 Exchange Server 进行互操作，以便提供高级 UM 功能，因此当 SMTP 用于与 Exchange Online 进行互操作时，这些系统的完整功能将无法使用。
  
> [!NOTE]
> 通过客户运营 SDC 的直接连接为第三方 PBX 系统的 Exchange Online UM 支持将于 2018 年 7 月结束。 有关详细信息 [，请参阅不再支持 Exchange Online 统](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117) 一消息中的会话边界控制器。 
  
## <a name="skype-for-business-integration"></a>Skype for Business 集成

组织可以将 Skype for Business Online 作为独立服务或 Microsoft Office 365 的一部分进行购买。 也支持本地 Skype for Business 2015。 若要了解有关 Skype for Business Online 的更多信息，请参阅 [Skype for Business Online 服务说明](../skype-for-business-online-service-description/skype-for-business-online-service-description.md)。
  
## <a name="feature-availability"></a>功能可用性

若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅 [Exchange Online 服务说明](exchange-online-service-description.md)。
