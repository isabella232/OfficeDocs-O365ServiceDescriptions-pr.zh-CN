---
title: 规划和部署
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-planning-and-deployment
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: e44e5e61-1f5d-4e68-981d-77a42f0ea0d4
description: 了解在部署中Microsoft Exchange Online。
ms.openlocfilehash: eabef8014f64295058b4f41ccd9835a8dea473d8
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652696"
---
# <a name="planning-and-deployment"></a>计划和部署

## <a name="planning-for-service-changes-and-growth"></a>计划服务更改和增长

组织应基于他们的源电子邮件系统、所需结束状态（完全托管或部分托管）、要迁移的用户数量和实现最终状态的速度选择迁移选项。
  
## <a name="deployment-options"></a>部署选项

- **仅云部署**- 组织拥有托管在云中的Exchange Online。 
    
- **Exchange混合** 部署 - 您的组织有一些用户邮箱托管在本地 Exchange 组织中，有些用户邮箱托管在 Exchange Online。 
    
### <a name="cloud-only"></a>仅限云

仅限于部署是您在 Exchange Online 服务中的组织不与内部部署 Exchange 组织连接的部署。所有用户和邮箱在 Exchange Online 和 Office 365 中托管和管理。
  
### <a name="hybrid"></a>混合

对 Microsoft Exchange 2003、Exchange 2007、Exchange 2010 和 Exchange 2013 内部部署组织可用的混合部署提供与一些在内部部署托管的邮箱和一些在 Exchange Online 邮箱托管的长期共存配置，或托管 Exchange Online 所有用户邮箱的迁移路径。混合部署使组织可以将随其现有内部部署 Microsoft Exchange 组织提供的功能丰富的体验和管理控制扩展到云。混合部署功能包括安全邮件传输、共享日历闲/忙信息以及内部部署和 Exchange Online 组织之间的邮件跟踪。
  
有关混合部署的详细信息，请参阅 [Exchange Server 2013 混合部署](/exchange/exchange-hybrid)。如果使用的是由世纪互联运营的 Office 365，请参阅[使用由世纪互联运营的 Office 365 配置 Exchange 混合部署功能](https://go.microsoft.com/fwlink/?LinkID=733373&amp;clcid=0x409)。
  
> [!IMPORTANT]
> 本地 Exchange 2003 组织至少必须安装一个 Exchange 2010 客户端访问/邮箱服务器，才能使用 Exchange Online 配置混合部署。本地 Exchange 2007 组织至少必须安装一个 Exchange 2010 或 Exchange 2013 客户端访问和邮箱服务器，才能使用 Exchange Online 配置混合部署。本地 Exchange 2010 和 Exchange 2013 组织使用 Exchange Online 本地支持混合部署。若要详细了解混合部署中的 Exchange 服务器兼容性，请参阅[混合部署先决条件](/exchange/hybrid-deployment-prerequisites)。 > 本地 Exchange 组织必须为其组织配置混合部署。我们强烈建议管理员使用 Exchange Server 部署助理和"混合配置"向导配置混合部署。有关详细信息，请参阅 [Exchange Server 部署助理](/exchange/exchange-deployment-assistant)
  
## <a name="migration-options"></a>迁移选项

组织应基于他们的源电子邮件系统、所需结束状态（完全托管或部分托管）、要迁移的用户数量和实现最终状态的速度选择迁移选项。可能的迁移选项是：
  
- **IMAP 迁移**- 将邮箱数据从基于 IMAP 的电子邮件系统迁移到Exchange Online。 
    
- Exchange迁移 **-** 在单个转换迁移中，将邮箱从 Exchange Server 2003、Exchange Server 2007、Exchange Server 2010、Exchange 2013 和托管 Exchange 系统迁移到 Exchange Online。 
    
- 分 **Exchange** 迁移 - 执行分步迁移，使用基于 Web 的迁移工具从 Exchange Server 2003 或 Exchange Server 2007 迁移邮箱，并尽量减少对本地基础结构的更改。 
    
- **远程移动迁移**- 将本地Exchange邮箱迁移到Exchange Online混合Exchange中。 必须拥有 Exchange 混合部署，才能使用远程移动迁移。 
    
有关将电子邮件和邮箱迁移到 Exchange Online 的详细信息，请参阅[到 Exchange Online 的邮箱迁移](https://support.office.com/article/-a3e3bddb-582e-4133-8670-e61b9f58627e)。
  
### <a name="imap-migration"></a>IMAP 迁移

Exchange Online 提供基于 Web 的工具，以从支持 IMAP 的电子邮件系统迁移邮箱数据。它将指导管理员完成以下迁移步骤： 
  
1. 为组织中的用户在云中创建空邮箱（这通常通过上载 .csv 文件或使用远程 Windows PowerShell 完成）。
    
2. 输入远程服务器连接设置。
    
3. 使用 CSV 文件指定将迁移其数据到 Exchange Online 邮箱的邮箱。
    
4. 输入该信息后，Exchange Online 开始通过 IMAP 迁移邮箱内容（日历项目、联系人、任务和其他非邮件项目将不迁移）。
    
有关 IMAP 迁移的详细信息，请参阅[将电子邮件从 IMAP 服务器迁移到 Exchange Online 邮箱](https://support.office.com/en-ie/article/Migrate-your-IMAP-mailboxes-to-Office-365-3fe19996-29bc-4879-aab9-5a622b2f1481)和[迁移其他类型的 IMAP 邮箱](https://support.office.com/en-ie/article/Migrate-other-types-of-IMAP-mailboxes-to-Office-365-58890ccd-ce5e-4d94-be75-560a3b70a706)。
  
> [!IMPORTANT]
> 为避免在迁移期间过度使用远程服务器的资源和带宽，Exchange Online 将创建不超过 10 个与 IMAP 服务器的连接。 
  
### <a name="cutover-exchange-migration"></a>切换 Exchange 迁移

Exchange Online 提供基于 Web 的工具，以从内部部署 Exchange Server 2003、Exchange Server 2007 或 Exchange Server 2010 环境迁移数据。它将指导管理员完成以下迁移步骤：
  
1. 为内部部署管理员帐户使用电子邮件地址和凭据，Exchange Online 使用自动发现服务连接到内部部署电子邮件组织。
    
2. Exchange Online 使用 RPC/HTTP 连接读取远程服务器的目录信息，并在 Exchange Online 中创建邮箱。
    
3. Exchange Online 同步邮箱内容到云邮箱。用户保持连接到原始邮箱，同时他们的数据将被迁移到 Exchange Online。
    
4. 在完成初始迁移后，会每 24 小时将更改同步到云，直到管理员停止或删除此迁移批次。
    
若要将用户切换到云邮箱，管理员需要将其 MX 记录配置为指向 Microsoft，并重新配置用户Outlook。 当用户切换到云邮箱时，将重新同步他们的本地脱机文件夹（.ost 文件），以下载迁移的邮件到客户端工作站。 迁移后，用户可以在他们的邮箱中回复旧邮件。
  
有关直接转换 Exchange 迁移的详细信息，请参阅[有关直接转换电子邮件迁移到 Office 365 您需要了解的信息](https://support.office.com/article/365-961978ef-f434-472d-a811-1801733869da)。
  
> [!IMPORTANT]
> 组织可使用直接转换 Exchange 迁移将最多 2,000 个 Exchange 2003、Exchange 2007、Exchange 2010 或 Exchange 2013 邮箱迁移到云。 > Exchange Online 必须连接到内部部署 Exchange Server，以便内部部署服务器必须拥有受信任的证书颁发机构颁发的证书和公共 IP 地址。 
  
### <a name="staged-exchange-migration"></a>暂存 Exchange 迁移

对于暂存迁移，用户可以使用基于 Web 的 Exchange 迁移工具和目录同步工具迁移到云。与一次性迁移所有用户的直接转换 Exchange 迁移不同的是，管理员可以分批迁移用户。这可通过上载 .csv 文件以指定要迁移的部分用户列表实现。在暂存迁移中，组织中的所有用户可以共享相同的电子邮件域名。
  
暂存 Exchange 迁移要求管理员使用 Online Services 目录同步工具。这将为用户提供统一全局地址列表 (GAL)，其中在线环境与内部部署环境持续同步。
  
有关暂存 Exchange 迁移的详细信息，请参阅[有关暂存电子邮件迁移您需要了解的信息](https://support.office.com/en-ie/article/365-7e2c82be-5f3d-4e36-bc6b-e5b4d411e207)。
  
> [!IMPORTANT]
> 组织无法使用暂存 Exchange 迁移来迁移 Exchange 2010 和 Exchange 2013 邮箱。如果您组织中的 Exchange 2010 或 Exchange 2013 邮箱数少于 2,000，则可使用直接转换 Exchange 迁移。如果您的 Exchange 2010 或 Exchange 2013 邮箱数多于 2,000，则可实施混合部署。 > 在迁移期间，管理员必须使用 Online Services 目录同步工具为用户提供统一全局地址列表，其中在线环境与内部部署环境持续同步。 
  
## <a name="migration-tools"></a>迁移工具

Microsoft 提供几个工具帮助迁移现有电子邮件环境到 Exchange Online。适用工具取决于组织的当前环境和部署目标：
  
- **迁移仪表板**- 管理员可以使用 Exchange 管理中心中的迁移仪表板管理到 Exchange Online 的邮箱迁移（在Exchange迁移中）。 管理员还可以使用主控板，将用户邮箱的内容从内部部署 IMAP 服务器迁移到 Exchange Online 的现有邮箱。 主控板为管理员提供了以下功能： 
    
  - **创建并启动多个迁移批处理** - 管理员可以创建最多 100 个迁移批处理并排入队列。 一次仅能运行一个迁移批次，但是管理员可以排队多个批次，以便在完成一个迁移批次后运行队列的下一个批次。 
    
  - 失败 **后** 重新启动迁移批处理 - 迁移批处理的初始同步（其中项目从本地邮箱复制到迁移批处理中每个用户的云邮箱）后，某些邮箱可能无法同步。 管理员可以重新启动该迁移批次，以重试同步失败的邮箱。 
    
  - 获取有关跳过项目的详细信息 **-** 对于 IMAP 迁移、切换迁移和分步迁移，迁移仪表板会显示有关跳过的特定项目的信息，包括跳过原因以及项目在用户邮箱中的位置。 
    
  - **打开迁移报告** - 管理员可以从仪表板打开迁移批处理的迁移统计信息或迁移错误报告。 
    
  - **编辑迁移** 批处理 - 如果分步迁移或 IMAP Exchange迁移的迁移批处理位于迁移队列中，但当前未运行，则管理员可以编辑迁移批处理。 
    
- **Azure Active Directory同步** 工具 - Azure Active Directory 同步工具在迁移到混合电子邮件方案（同时利用 Exchange Online 和本地邮箱）Exchange Server。 该工具将执行从 Active Directory 到 Exchange Online 的单向同步。 完成迁移后，管理员仅需要使用 Exchange Online 就可管理 Active Directory 用户和组。 该工具还为用户提供统一全局地址列表，其中在线环境与内部部署环境持续同步。 
    
    有关 Azure Active Directory 同步工具的详细信息，请参阅 [Directory synchronization: Roadmap](/azure/active-directory/hybrid/whatis-hybrid-identity)（目录同步：路线图）。
    
- **混合配置向导**- 混合配置向导通过简化功能和服务Exchange Online配置来简化混合部署过程。 作为 Exchange Server 2010 Service Pack 2 一部分推出的混合配置向导仅在内部部署组织中运行，同时拥有以下组件： 
    
  - Exchange 管理中心 (EAC) 向导指导管理员完成配置混合部署的端到端流程。
    
  - 一组安排配置流程的 Exchange 命令行管理程序 (EMS) 命令。
    
    有关"混合配置"向导的详细信息，请参阅["混合配置"向导](/exchange/hybrid-configuration-wizard)。
    
- **远程Windows PowerShell** - 作为 2011 年 12 月Exchange Online更新的一部分，远程Windows PowerShell可用于帮助解决迁移错误。 例如，管理员可以显示迁移批次的诊断信息，以及迁移统计数据和基于主 SMTP 地址为用户显示诊断信息。 
    
## <a name="feature-availability"></a>功能可用性

若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅Exchange Online[说明](exchange-online-service-description.md)。
