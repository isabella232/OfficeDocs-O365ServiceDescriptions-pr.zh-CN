---
title: 在 Yammer 中Limits
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- yammer-service-description
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: ''
description: 了解 Yammer for Microsoft 365 中的服务限制。
ms.openlocfilehash: b6f8e271950d248d8dd6b5096b741c9ea48e4f79
ms.sourcegitcommit: 36cce83d0f146c904ca02a251ba02a5ab913e3ef
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/08/2022
ms.locfileid: "63382873"
---
# <a name="limits-in-yammer"></a>在 Yammer 中Limits

了解 Yammer for Microsoft 365 中的服务限制。

## <a name="network-limits"></a>网络限制

| 功能 | 详细信息 |
|---------|---------|
| 本机模式 | [建议](/yammer/configure-your-yammer-network/overview-native-mode) 采用本机模式，以从长期来看提供最佳支持。 Yammer本机模式下Microsoft 365网络的功能与旧版网络Yammer不同。 |
| 网络管理员的批量更新 | 2000 个或更少用户的非本机模式网络支持批量更新用户。 |
| 家庭网络 | 无法删除和重新创建家庭网络。 |

## <a name="file-limits"></a>文件限制

| 功能 | 详细信息 |
|---------|---------|
| 最大文件大小和存储 | 建议迁移到Microsoft 365本机模式Yammer，以确保所有文件都存储在 SharePoint Online 中。 <br/>For Yammer files stored in SharePoint： <ul><li>单个文件附件的最大大小为 15 GB (GB) 。</li><li>图像没有维度限制，但SharePoint最大大小设置适用。</li><li>可以添加任何文件类型，但预览和编辑仅限于某些文件类型。</li> </ul><br/>[SharePoint限制](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-limits)适用于Microsoft 365[连接Yammer](/yammer/manage-yammer-groups/yammer-and-office-365-groups)。 <br/>对于存储在Yammer文件存储中的文件： <br/><ul><li>单个文件附件的最大大小为 5 GB (GB) （对于 Yammer Enterprise 网络）和 100 MB (MB) （对于 Yammer Basic 网络）。</li><li>最大尺寸为 7，680 像素宽，高 4，320 像素，最大图像大小为 10 MB (MB) 。</li></ul> <br/>有关图像使用（包括封面照片的模板和尺寸）[Yammer采用资源](https://adoption.microsoft.com/yammer/)。 |
| 每个帖子的文件附件数 | 每个帖子最多可包含 100 个文件。 |
| 支持的视频格式 | 内联播放支持以下视频类型：.wmv、.avi、.mpeg、.3gp、.flv、.mov、.mp4、.mpg、.ogm、.mkv、.ogv 和 .ogg。 <br/>Yammer使用 Azure 媒体服务 来显示Yammer。 |
| 内联视频播放 | Microsoft Stream、SharePoint Online、YouTube 和 Vimeo 支持内联播放。 |
| 来宾访问权限 | Microsoft 365来宾支持Yammer要求使用本机模式。 <br/>旧版网络级别的来宾可能会遇到文件访问问题。 |
| 链接预览 (打开Graph对象)  | 无法公开解析或要求身份验证的内部系统的链接不会显示有效的预览，因为无法提取元数据。 |

## <a name="yammer-live-event-limits"></a>Yammer实时事件限制

| 功能 | 详细信息 |
|---------|---------|
| 实时事件查看器的数量 | 目前，限制为 10，000 个参与者。 对于大小较高的事件，请通过[实时事件协助计划。](https://resources.techcommunity.microsoft.com/live-events/assistance/) |
| 实时事件创建权限 | 需要拥有在 Stream 中创建实时事件的权限。 <br/>Community管理员Yammer创建或安排实时事件。 |
| 来宾访问权限 | 规范网络的成员可以在会议现场创建或参加Yammer。 |
| 隐藏式字幕 | 隐藏式字幕不适用于 Yammer 中的实时Yammer。 将来的更新将添加对隐藏式字幕的支持。 |
| 事件的持续时间 | 4 小时 |
| 在组织或组织中运行的Microsoft 365实时Office 365事件 | 每个租户 50 个事件 |
| 演示者的限制？ | 100 个演示者 |

有关实时事件和Microsoft Teams的更多限制，请参阅 Teams [Live Events](/microsoftteams/limits-specifications-teams#teams-live-events)。

## <a name="yammer-community-limits"></a>Yammer社区限制

| 功能 | 详细信息 |
|---------|---------|
| 社区中的成员数 | 根据社区是否连接到Microsoft 365[组、](/yammer/manage-yammer-groups/yammer-and-office-365-groups)动态社区还是"所有公司["社区而异](/yammer/manage-yammer-groups/yammer-all-company-yammer-community)。[](/yammer/manage-yammer-groups/create-a-dynamic-group) <br/>动态社区成员身份限制：500，000 |
| 可成为成员的社区数 | 7，000 (建议用户加入的专用组少于 800 个，因为如果用户拥有超过建议数量的社区，他们可能会开始遇到性能问题)  |
| 通过通讯簿导入同时添加多个用户的更新数 | 每个批量上载 200 个社区成员。 |
| 动态社区的限制 | 无限制 |
| 每个社区管理员数 | 在本机模式下，管理员可以设置最小值。 非本机模式网络每个社区限制为 100 个管理员。 |
| 网络管理员数量 | 因本机模式配置而异。 网络管理员没有限制。 |
| 连接的社区和Azure AD Sync | 如果社区成员资格超过 10 万，则可能会发生同步延迟。 |
| 所有公司的成员 | 包括租户中的所有用户。 |
| 官方社区的数量 | 无限制 |
| 收藏夹社区的数量 | 10  |
| Community名称字符限制 | 取决于网络的命名约定。 <br/>最多 255 个字符，包括任何前缀。 |
| Community描述字符限制 | 150 个字符 |
| Community信息长度 | 没有字符限制 (1 GB)  |
| 固定资源的限制 | 无限制 |
| 相关社区的限制 | 正常社区没有限制，但最佳做法是 3-5 个相关社区。 <br/>相关社区不可用于所有公司。 |
| 对私有社区待定成员的限制 | 无限制。 |
| 本机模式下社区管理的限制 | 应该使用旨在更新 Microsoft 365 组的工具（包括 Microsoft 365 管理门户、Azure AD 门户和 Azure AD PowerShell 模块）管理连接的组。 |
| 通过电子邮件发布 | 无限制 |

## <a name="yammer-messaging-limitations"></a>Yammer邮件限制

| 功能 | 详细信息 |
|---------|---------|
| 每封邮件的字符限制 | 10，000 个字符限制 |
| 删除对话 | 删除整个线程需要删除所有消息。 删除会话初学者将提升第一个回复成为线程初学者。 <br/>如果启用了私人内容模式，网络管理员可以从任何对话线程 [中删除](/yammer/manage-security-and-compliance/monitor-private-content) 消息。 <br/>Community管理员可以删除他们管理的社区中的邮件。 <br/>原始作者只能删除自己的帖子。 |
| 每个对话线程的邮件限制 | 对话中最多有 10，000 个帖子。 |
| 链接预览 (开放Graph元数据)  |<ul><li>链接内容的预览只能针对公共内容和一些受支持的资源Microsoft 365预览。</li><li>预览生成取决于发布时是否成功提取元数据，根据要链接到的网站的可用性，元数据提取可能会有所不同。</li><li>不支持指向组织防火墙内部系统的链接或要求进行身份验证的链接。 </li><li>首次使用网络内的链接后，可能不会更新链接预览元数据。</li></ul> |
| 专用内容模式 | 默认情况下，已验证的管理员无法访问私人内容。 必须启用私人内容模式，以访问私人消息和私人社区。 |
| 嵌套答复和旧线程 | 旧线程将允许新建嵌套回复。 目前，较旧的"答复"邮件将保持为顶级评论。 |

## <a name="external-network-limits"></a>外部网络限制

| 功能 | 详细信息 |
|---------|---------|
| 外部网络 | 如果这 5 个外部网络通常只有一个成员，则管理员可以创建 5 个外部网络 (该成员是该网络的创建者) 。 <br/> 如果外部网络中至少有一个其他用户，则不计入该限制。 |
| 文件 | 文件存储在Yammer存储中，不能通过 SharePoint。 |
| 社区 | 社区不会连接到Microsoft 365组。 |
| 本机模式 | [本机模式功能和](/yammer/configure-your-yammer-network/overview-native-mode) 限制不适用于外部网络。 |