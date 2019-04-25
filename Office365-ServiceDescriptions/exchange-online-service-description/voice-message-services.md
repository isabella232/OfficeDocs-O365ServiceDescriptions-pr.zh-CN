---
title: 语音消息服务
ms.author: sharik
author: skjerland
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
ms.openlocfilehash: 3879252927a26f47cd5d92f0fbcfbdecf4466c2a
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/25/2019
ms.locfileid: "33246468"
---
# <a name="voice-message-services"></a><span data-ttu-id="32619-102">语音消息服务</span><span class="sxs-lookup"><span data-stu-id="32619-102">Voice Message Services</span></span>

## <a name="voice-mail"></a><span data-ttu-id="32619-103">语音邮件</span><span class="sxs-lookup"><span data-stu-id="32619-103">Voice mail</span></span>

<span data-ttu-id="32619-104">Microsoft Exchange Online 提供托管语音邮件服务，其中包括：</span><span class="sxs-lookup"><span data-stu-id="32619-104">Microsoft Exchange Online offers hosted voice mail services, which provide:</span></span>
  
- <span data-ttu-id="32619-105">电话应答（语音邮件）</span><span class="sxs-lookup"><span data-stu-id="32619-105">Call answering (voice mail)</span></span>
    
- <span data-ttu-id="32619-106">Exchange 的拨号用户界面 (Outlook Voice Access)</span><span class="sxs-lookup"><span data-stu-id="32619-106">Dial-in user interface to Exchange (Outlook Voice Access)</span></span>
    
- <span data-ttu-id="32619-107">呼叫者的拨号界面（自动助理）</span><span class="sxs-lookup"><span data-stu-id="32619-107">Dial-in interface for callers (auto attendant)</span></span>
    
<span data-ttu-id="32619-108">托管语音留言服务允许公司将内部电话系统连接到 Exchange Online 提供的语音留言服务中。</span><span class="sxs-lookup"><span data-stu-id="32619-108">Hosted voice messaging services allow a company to connect its on-premises phone system to voice mail services provided by Exchange Online.</span></span> <span data-ttu-id="32619-109">语音邮件记录和存储在 Exchange Online 基础结构中, 允许用户从 outlook、outlook 网页版或移动电话访问其语音邮件。</span><span class="sxs-lookup"><span data-stu-id="32619-109">Voice mail messages are recorded and stored in the Exchange Online infrastructure, allowing users to access their voice messages from Outlook, Outlook on the web, or mobile phones.</span></span> <span data-ttu-id="32619-110">所有与 Exchange Online 的电话连接均需使用 voice-over-IP (VoIP) 协议。</span><span class="sxs-lookup"><span data-stu-id="32619-110">All telephony connections to Exchange Online require voice-over-IP (VoIP) protocols.</span></span> <span data-ttu-id="32619-111">通过使用 VoIP 介质网关和会话边界控制器 (SBC)，管理员可以将内部 IP PBX 或 PBX 电话系统连接到 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="32619-111">Administrators can connect on-premises IP PBXs or PBX phone systems using VoIP media gateways and session border controllers (SBCs) to Exchange Online.</span></span> <span data-ttu-id="32619-112">如果客户已部署 IP PBX，或者 PBX 直接支持 VoIP 且可与 Exchange 语音留言服务进行互操作，则无需使用 VoIP 介质。</span><span class="sxs-lookup"><span data-stu-id="32619-112">A VoIP media gateway is not required if the customer has deployed an IP PBX or if a PBX supports VoIP directly and is interoperable with Exchange voice messaging services.</span></span> <span data-ttu-id="32619-113">SBC 部署在客户网络外围且与内部电话网络连接，有助于确保通信（和客户网络）安全，防止窃听和入侵。</span><span class="sxs-lookup"><span data-stu-id="32619-113">SBCs are deployed in the perimeter of the customer network to connect an on-premises telephony network and help secure the communications (and the customer network) against eavesdropping and intrusion.</span></span> <span data-ttu-id="32619-114">此外，它还支持与 Microsoft Lync Server 2010 和 2013 语音功能的互操作性。</span><span class="sxs-lookup"><span data-stu-id="32619-114">Interoperability with the voice capabilities of Microsoft Lync Server 2010 and 2013 is also supported.</span></span>
  
<span data-ttu-id="32619-115">Exchange Online 中提供的语音邮件服务功能与本地 Exchange Server 2016 中提供的功能类似。</span><span class="sxs-lookup"><span data-stu-id="32619-115">The voice messaging services features available in Exchange Online are similar to those offered in on-premises Exchange Server 2016.</span></span> <span data-ttu-id="32619-116">具体包括：</span><span class="sxs-lookup"><span data-stu-id="32619-116">These include:</span></span>
  
- <span data-ttu-id="32619-117">在 outlook 和 web 上的 outlook 中播放电话。</span><span class="sxs-lookup"><span data-stu-id="32619-117">Play on phone from Outlook and Outlook on the web.</span></span>
    
- <span data-ttu-id="32619-118">未接来电通知。</span><span class="sxs-lookup"><span data-stu-id="32619-118">Missed call notifications.</span></span>
    
- <span data-ttu-id="32619-119">呼叫者 ID（使用全局地址列表中的信息、用户的个人联系人、自定义联系人文件夹、以及外部社交网络的联系人）。</span><span class="sxs-lookup"><span data-stu-id="32619-119">Caller ID (using information in the Global Address List, users' personal contacts, custom Contacts folder, and contacts from external social networks).</span></span>
    
- <span data-ttu-id="32619-120">从 outlook 网页和 outlook 重置的语音邮件 PIN (请参阅[重置语音邮件 pin](https://go.microsoft.com/fwlink/p/?LinkId=286328))。</span><span class="sxs-lookup"><span data-stu-id="32619-120">Voice mail PIN reset from Outlook on the web and Outlook (see [Reset a Voice Mail PIN](https://go.microsoft.com/fwlink/p/?LinkId=286328)).</span></span>
    
- <span data-ttu-id="32619-121">邮件等待指示器（有关详细信息，请参阅 [Exchange Online 中的 MWI](https://go.microsoft.com/fwlink/p/?LinkId=271794)）。</span><span class="sxs-lookup"><span data-stu-id="32619-121">Message Waiting Indicator (see [MWI in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271794) for details).</span></span> 
    
- <span data-ttu-id="32619-122">电话应答规则（有关详细信息，请参阅[允许语音邮件用户转接来电](https://go.microsoft.com/fwlink/p/?LinkId=271795)）。</span><span class="sxs-lookup"><span data-stu-id="32619-122">Call Answering Rules (see [Allow Voice Mail Users to Forward Calls](https://go.microsoft.com/fwlink/p/?LinkId=271795) for details).</span></span> 
    
- <span data-ttu-id="32619-123">Exchange Online 中受保护的语音邮件（有关详细信息，请参阅 [Protected Voice Mail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271796)（Exchange Online 中受保护的语音邮件））。</span><span class="sxs-lookup"><span data-stu-id="32619-123">Protected Voice Mail in Exchange Online (see [Protected Voice Mail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271796) for details).</span></span> 
    
- <span data-ttu-id="32619-124">语音邮件预览（有关支持的语言列表，请参阅 [Allow Users to See a Voice Mail Transcript](https://go.microsoft.com/fwlink/p/?LinkId=271797)（允许用户查看语音邮件转录））。</span><span class="sxs-lookup"><span data-stu-id="32619-124">Voice Mail Preview (see [Allow Users to See a Voice Mail Transcript](https://go.microsoft.com/fwlink/p/?LinkId=271797) for a list of supported languages).</span></span> 
    
- <span data-ttu-id="32619-125">语音访问电子邮件、语音邮件、日历、个人联系人和个人联系人组。</span><span class="sxs-lookup"><span data-stu-id="32619-125">Speech access to email, voice mail, calendar, personal contacts, and personal contact groups.</span></span>
    
- <span data-ttu-id="32619-126">通过 Outlook Voice Access 或自动助理进行目录搜索。</span><span class="sxs-lookup"><span data-stu-id="32619-126">Directory search through Outlook Voice Access or an auto attendant.</span></span>
    
- <span data-ttu-id="32619-127">管理员使用 Exchange 管理中心 (EAC) 配置并管理语音留言服务的互操作性。</span><span class="sxs-lookup"><span data-stu-id="32619-127">Administrators configure and manage voice messaging services interoperability by using the Exchange admin center (EAC).</span></span>
    
<span data-ttu-id="32619-128">有关语音邮件功能的详细信息，请参阅 [Exchange Online 中的语音邮件](https://go.microsoft.com/fwlink/p/?LinkId=271798)。</span><span class="sxs-lookup"><span data-stu-id="32619-128">For more information about voice mail features, see [Voice Mail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271798).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="32619-p103">对于 Outlook Voice Access 用户或使用语音命令的自动助理呼叫者，自动语言识别 (ASR) 功能在菜单导航或目录搜索中不可用。 > 客户必须使用 VoIP 网关和 PBX、IP PBX 或 Skype for Business Server 2015 提供来自公用电话交换网 (PSTN) 的电话连接。 > 客户必须提供内部 SBC 硬件设备，并确保 SBC 已正确配置为连接到联机语音邮件服务。这包括通过使用证书以及公用和专用 IP 接口，并支持正确的 TCP 端口通过内部防火墙，从而配置适当的安全级别。 > 只有 Exchange Online 计划 2 和 Office 365 企业版 E3 订阅者才能使用托管语音邮件。</span><span class="sxs-lookup"><span data-stu-id="32619-p103">The Automatic Speech Recognition (ASR) feature isn't available in menu navigation or directory search for Outlook Voice Access users or auto attendant callers using voice commands. > The customer must provide a telephony connection from the public switched telephone network (PSTN) using a VoIP gateway and PBX, IP PBX, or Skype for Business Server 2015. > The customer must provide the on-premises SBC hardware devices and ensure that the SBCs are correctly configured to connect to the online voice mail services. This includes configuring the appropriate level of security by using certificates and public and private IP interfaces and by enabling the correct TCP ports through their on-premises firewalls. > Hosted voice mail is available only to Exchange Online Plan 2 and Office 365 Enterprise E3 subscribers.</span></span> 
  
## <a name="third-party-voice-mail-interoperability"></a><span data-ttu-id="32619-134">第三方语音邮件互操作性</span><span class="sxs-lookup"><span data-stu-id="32619-134">Third-party voice mail interoperability</span></span>

<span data-ttu-id="32619-p104">如果第三方提供商提供的内部语音留言解决方案能够通过 SMTP 转发语音留言，或者支持 Microsoft Exchange Web 服务，则可与 Exchange Online 进行互操作。如果语音邮件系统本身不支持通过 SMTP 转发语音留言，则电子邮件服务器可保存在内部，以便接收语音邮件系统中的邮件，然后使用 SMTP 将其转发到云。由于许多第三方语音邮件系统均使用 MAPI/CDO 与 Exchange Server 进行互操作，以便提供高级 UM 功能，因此当 SMTP 用于与 Exchange Online 进行互操作时，这些系统的完整功能将无法使用。</span><span class="sxs-lookup"><span data-stu-id="32619-p104">On-premises voice mail solutions from third-party providers can interoperate with Exchange Online if they can forward voice messages through SMTP or if they support Microsoft Exchange Web Services. If the voice mail system does not natively support forwarding voice messages through SMTP, an email server can be kept on-premises to receive messages from the voice mail system and then forward them to the cloud using SMTP. Because many third-party voice mail systems use MAPI/CDO to interoperate with Exchange Server for advanced UM features, the full capabilities of these systems may not be available when SMTP is used for interoperability with Exchange Online.</span></span>
  
> [!NOTE]
> <span data-ttu-id="32619-138">Exchange Online UM 对第三方 PBX 系统的支持通过从客户端运营的直接连接来实现。2018年7月将结束。</span><span class="sxs-lookup"><span data-stu-id="32619-138">Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018.</span></span> <span data-ttu-id="32619-139">有关详细信息, 请参阅[停产支持 Exchange Online 统一消息中的会话边界控制器](https://blogs.technet.microsoft.com/exchange/2017/07/18/discontinuation-of-support-for-session-border-controllers-in-exchange-online-unified-messaging/)。</span><span class="sxs-lookup"><span data-stu-id="32619-139">Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://blogs.technet.microsoft.com/exchange/2017/07/18/discontinuation-of-support-for-session-border-controllers-in-exchange-online-unified-messaging/) for more information.</span></span> 
  
## <a name="skype-for-business-integration"></a><span data-ttu-id="32619-140">Skype for Business 集成</span><span class="sxs-lookup"><span data-stu-id="32619-140">Skype for Business integration</span></span>

<span data-ttu-id="32619-141">组织可以将 Skype for Business Online 作为独立服务或 Microsoft Office 365 的一部分进行购买。</span><span class="sxs-lookup"><span data-stu-id="32619-141">Organizations can purchase Skype for Business Online as a standalone service or as part of Microsoft Office 365.</span></span> <span data-ttu-id="32619-142">此外, 还支持 Skype for business 2015 内部部署。</span><span class="sxs-lookup"><span data-stu-id="32619-142">Skype for Business 2015 on-premises is also supported.</span></span> <span data-ttu-id="32619-143">若要详细了解 Skype for Business Online，请参阅 [Skype for Business Online 服务说明](../skype-for-business-online-service-description/skype-for-business-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="32619-143">To learn more about Skype for Business Online, see [Skype for Business Online Service Description](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="32619-144">功能可用性</span><span class="sxs-lookup"><span data-stu-id="32619-144">Feature Availability</span></span>

<span data-ttu-id="32619-145">若要查看在各个 Office 365 计划、独立选项和内部部署解决方案之间的功能可用性，请参阅 [Exchange Online 服务说明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="32619-145">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

