---
title: Microsoft Teams 服务说明
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
description: 了解 Microsoft 365 和 Office 365 计划中的 Microsoft Teams 服务和功能可用性。
ms.openlocfilehash: 5a57288f068d877ab7dd646be3444cba35957a01
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653564"
---
# <a name="microsoft-teams-service-description"></a>Microsoft Teams 服务说明

Microsoft Teams 是 Microsoft 365 中团队合作的中心。 Teams 服务支持即时消息、音频和视频呼叫、丰富的联机会议、移动体验和广泛的 Web 会议功能。 此外，Teams 还提供文件和数据协作和扩展性功能，并且与 Microsoft 365 和其他 Microsoft 和合作伙伴应用集成。

Skype for Business Online 将于 2021 年 7[](https://techcommunity.microsoft.com/t5/Microsoft-Teams-Blog/Skype-for-Business-Online-to-Be-Retired-in-2021/ba-p/777833)月 31 日停用，2019 年 7 月 30 日宣布停用。 Microsoft Teams 是一项全新的服务，利用 Microsoft 的 Azure 和其他服务创新，从一开始就为云构建。 Microsoft Teams 基于 Microsoft 365 组、Microsoft Graph 构建，并且与 Office 365 的其余部分具有相同的企业级安全性、合规性和可管理性。 Teams 利用 Azure AD (Azure Active Directory 中) 。 这些服务从 Microsoft 数据中心提供，用户可以从企业网络内部或 Internet 访问各种设备。 有关详细信息，请参阅 Microsoft [Teams IT 体系结构和电话解决方案海报](/microsoftteams/teams-architecture-solutions-posters)。

此服务说明详细介绍了在各种云安装中提供的服务之间的主要差异。 Microsoft Teams 核心功能在订阅之间没有区别。 合规性功能的可用性取决于你的订阅级别。 若要详细了解 Teams 安全性和合规性，请参阅 [Microsoft Teams 中的安全性和合规性](/microsoftteams/security-compliance-overview)。

## <a name="available-plans"></a>可用计划

有关为用户启用 Teams 的订阅的详细计划信息，请参阅[查找适用于你的企业正确的 Microsoft Teams。](https://www.microsoft.com/microsoft-teams/compare-microsoft-teams-options) 可在 Microsoft 解决方案比较表 [找到其他详细信息](https://go.microsoft.com/fwlink/?linkid=2139145)。

支持 Teams 政府版计划包括 Office 365 G1 至 G5。 有关详细信息，请参阅 [Office 365 政府版计划](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans)。

所有受支持的订阅计划都有资格访问 Microsoft Teams Web 客户端、桌面客户端和移动应用。

Microsoft Teams 不作为独立服务提供。

## <a name="feature-availability"></a>功能可用性

下表列出了跨计划提供的主要 Teams 功能。 有一些注意事项适用。 有关详细信息，请参阅脚注。 此表可能会更改，无需另行通知。

若要详细了解操作系统平台的 Teams 功能，请参阅 [按平台查看 Teams 功能](https://aka.ms/teamsfeaturesbyplatform)。

有关 Microsoft 365 和 Office 365 计划中 Teams 功能最新的完整列表，请参阅查找适用于你的企业[正确的 Microsoft Teams。](https://www.microsoft.com/microsoft-teams/compare-microsoft-teams-options)<br><br>

| 功能 | 小型企业计划 | 企业版计划 | GCC | GCC - 高 | DOD | 教育计划 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|聊天  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|Teams  <br/> |是 <br/> |是 <br/> |是 <br/> |是<sup>1</sup>  <br/> |是<sup>1</sup>  <br/> |是  <br/> |
|频道 - 标准  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|频道 - 私人  <br/> |是  <br/> |是<sup>2</sup>  <br/> |是 <br/> |否  <br/> |否 <br/> |是  <br/> |
|会议  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|屏幕共享 PowerPoint 音频/视频桌面 <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |是  <br/> |
|语音  <br/> |是  <br/> |是  <br/> |是  <br/> |是<sup>3</sup>  <br/> |是<sup>3</sup>  <br/> |是  <br/> |
|音频会议  <br/> |是  <br/> |是  <br/> |是  <br/> |是<sup>3</sup>  <br/> |是<sup>3</sup>  <br/> |是  <br/> |
|应用、聊天机器人&连接器  <br/> |是  <br/> |是  <br/> |是<sup>4</sup>  <br/> |是<sup>4</sup>  <br/> |是<sup>4</sup>  <br/> |是  <br/> |
|实时事件  <br/> |否  <br/> |是  <br/> |是  <br/> |否<sup>5</sup>  <br/> |否<sup>5</sup>  <br/> |是  <br/> |

<sup>1 Microsoft</sup> Teams GCC-High DOD 支持单个团队中的 2500 个成员。<br/>
<sup>2</sup> Microsoft Planner 当前不可在私人频道中访问。<br/>
<sup>3</sup> 必须配置直接路由，Microsoft Teams 语音和音频会议在 GCCH 和 DoD 中工作。<br/>
<sup>4</sup> 目前，第三方应用程序和应用程序发布在这些云中不可用。<br/>
<sup>5</sup> Live Events is not available in GCC-High or DOD at this time.<br/>

### <a name="cloud-voice-features"></a>云语音功能

对于音频会议，你的组织必须购买音频会议许可证并将其分配给设置电话拨入式会议的每个用户。 对于需要通话套餐的 Teams 功能，每个用户都需要一个电话系统和一个国内或国内和国际通话套餐。 若要了解更多信息，请参阅 [Microsoft Teams 附加许可证](/microsoftteams/teams-add-on-licensing/microsoft-teams-add-on-licensing)。

### <a name="live-events"></a>实时事件

Office 365 中的此产品/服务取代了已停用的 Skype 会议直播。 实时事件功能可用于 Stream 服务中详述的许可计划。 有关详细信息，请查看 Microsoft [Stream 许可概述](/stream/license-overview)。 可通过 Stream、Yammer 或 Microsoft Teams 访问实时事件服务。 若要详细了解实时事件功能，请参阅 Yammer、Microsoft Teams 和 Microsoft Stream 中跨 [Microsoft 365 实时事件](/stream/live-event-m365)。

## <a name="learn-more"></a>了解详细信息

有关 Teams 详细信息，请查看以下资源：
 
- [Microsoft Teams 管理文档](/MicrosoftTeams)
- [Microsoft Teams 技术社区](https://techcommunity.microsoft.com/t5/microsoft-teams/ct-p/MicrosoftTeams)
- [Microsoft Teams 博客](https://aka.ms/TeamsBlog)

### <a name="licensing-terms"></a>许可条款

有关通过 Microsoft 商业批量许可计划购买的产品和服务的许可条款和条件，请参阅产品 [条款网站](https://www.microsoft.com/licensing/terms/)。 

### <a name="messaging"></a>消息 

若要及时了解即将进行的更改，包括新功能和已更改的功能、计划的维护或其他重要通知，请访问消息中心。 有关详细信息，请参阅消息 [中心](/microsoft-365/admin/manage/message-center)。

### <a name="accessibility"></a>辅助功能

Microsoft 始终致力于确保数据的安全性以及服务的辅助功能。 有关详细信息，请参阅 Microsoft [信任中心和](https://www.microsoft.com/trust-center) Office [辅助功能中心](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)。