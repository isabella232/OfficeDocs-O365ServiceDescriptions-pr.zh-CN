---
title: 规划和部署
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-planning-and-deployment
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: e44e5e61-1f5d-4e68-981d-77a42f0ea0d4
ms.openlocfilehash: e722bec332e67e93647b10bbbf4916e7e059c1b7
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132656"
---
# <a name="planning-and-deployment"></a>计划和部署

## <a name="planning-for-service-changes-and-growth"></a>计划服务更改和增长

组织应基于他们的源电子邮件系统、所需结束状态（完全托管或部分托管）、要迁移的用户数量和实现最终状态的速度选择迁移选项。
  
## <a name="deployment-options"></a>部署选项

- **仅限云部署** 您的组织拥有在 Exchange Online 中托管的所有用户邮箱。 
    
- **Exchange 混合部署** 您的组织有一些在内部部署 Exchange 组织托管的用户邮箱，同时一些在 Exchange Online 中托管的用户邮箱。 
    
### <a name="cloud-only"></a>仅限云

A cloud-only deployment is one where your organization in the Exchange Online service isn't connected with an on-premises Exchange organization. All users and mailboxes are hosted and managed in Exchange Online and Office 365.
  
### <a name="hybrid"></a>混合

Available for Microsoft Exchange 2003, Exchange 2007, Exchange 2010 and Exchange 2013 on-premises organizations, a hybrid deployment offers either a long-term coexistence configuration with some mailboxes hosted on-premises and some mailboxes hosted in Exchange Online or a migration path to hosting all user mailboxes in Exchange Online. A hybrid deployment offers organizations the ability to extend the feature-rich experience and administrative control they have with their existing on-premises Microsoft Exchange organization to the cloud. Hybrid deployment features include secure mail transport, shared calendar free/busy information, and message tracking between the on-premises and Exchange Online organizations.
  
For more information about hybrid deployments, see [Exchange Server 2013 Hybrid Deployments](https://go.microsoft.com/fwlink/p/?LinkId=287035). If you are using Office 365 operated by 21Vianet, see [Configuring Exchange hybrid deployment features with Office 365 operated by 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733373&amp;clcid=0x409).
  
> [!IMPORTANT]
> On-premises Exchange 2003 organizations must install at least one Exchange 2010 Client Access/Mailbox server to configure a hybrid deployment with Exchange Online. On-premises Exchange 2007 organizations must install at least one Exchange 2010 or Exchange 2013 Client Access and Mailbox server to configure a hybrid deployment with Exchange Online. On-premises Exchange 2010 and Exchange 2013 organizations natively support hybrid deployments with Exchange Online. For more information about Exchange server compatibility in hybrid deployments, see [Hybrid Deployment Prerequisites](https://go.microsoft.com/fwlink/p/?LinkId=243541)> On-premises Exchange organizations must configure their organization for a hybrid deployment. We strongly recommend that administrators use the Exchange Server Deployment Assistant and the Hybrid Configuration Wizard to configure the hybrid deployment. Learn more at [Exchange Server Deployment Assistant](https://go.microsoft.com/fwlink/p/?LinkId=287036)
  
## <a name="migration-options"></a>迁移选项

Organizations should choose migration options based on their source email systems, the desired end state (fully hosted or partially hosted), the number of users to migrate, and how quickly the end state needs to be reached. Possible migration options are:
  
- **IMAP 迁移** 从基于 IMAP 的电子邮件系统迁移邮箱数据到 Exchange Online。 
    
- **直接转换 Exchange 迁移** 在单个直接转换迁移中，从 Exchange Server 2003、Exchange Server 2007、Exchange Server 2010、Exchange 2013 和托管 Exchange 系统迁移邮箱到 Exchange Online。 
    
- **暂存 Exchange 迁移** 执行暂存迁移，以使用基于 Web 的迁移工具从 Exchange Server 2003 或 Exchange Server 2007 迁移邮箱，并减少内部部署基础结构的变化。 
    
- **Remote move migration** Migrate on-premises Exchange mailboxes to Exchange Online in an Exchange hybrid deployment. You must have an Exchange hybrid deployment to use a remote move migration. 
    
有关将电子邮件和邮箱迁移到 Exchange Online 的详细信息，请参阅[到 Exchange Online 的邮箱迁移](https://support.office.com/en-us/article/-a3e3bddb-582e-4133-8670-e61b9f58627e)。
  
### <a name="imap-migration"></a>IMAP 迁移

Exchange Online offers a web-based tool for migrating mailbox data from email systems that support IMAP. It guides administrators through the following migration steps: 
  
1. 为组织中的用户在云中创建空邮箱（这通常通过上载 .csv 文件或使用远程 Windows PowerShell 完成）。
    
2. 输入远程服务器连接设置。
    
3. 使用 CSV 文件指定将迁移其数据到 Exchange Online 邮箱的邮箱。
    
4. 输入该信息后，Exchange Online 开始通过 IMAP 迁移邮箱内容（日历项目、联系人、任务和其他非邮件项目将不迁移）。
    
有关 IMAP 迁移的详细信息，请参阅[将电子邮件从 IMAP 服务器迁移到 Exchange Online 邮箱](https://support.office.com/en-ie/article/Migrate-your-IMAP-mailboxes-to-Office-365-3fe19996-29bc-4879-aab9-5a622b2f1481)和[迁移其他类型的 IMAP 邮箱](https://support.office.com/en-ie/article/Migrate-other-types-of-IMAP-mailboxes-to-Office-365-58890ccd-ce5e-4d94-be75-560a3b70a706)。
  
> [!IMPORTANT]
> 为避免在迁移期间过度使用远程服务器的资源和带宽，Exchange Online 将创建不超过 10 个与 IMAP 服务器的连接。 
  
### <a name="cutover-exchange-migration"></a>切换 Exchange 迁移

Exchange Online offers a web-based tool for migrating data from on-premises Exchange Server 2003, Exchange Server 2007, or Exchange Server 2010 environments. It guides an administrator through the following migration steps:
  
1. 为内部部署管理员帐户使用电子邮件地址和凭据，Exchange Online 使用自动发现服务连接到内部部署电子邮件组织。
    
2. Exchange Online 使用 RPC/HTTP 连接读取远程服务器的目录信息，并在 Exchange Online 中创建邮箱。
    
3. Exchange Online synchronizes the mailbox content to the cloud mailboxes. Users remain connected to their original mailboxes while their data is being migrated to Exchange Online.
    
4. 在完成初始迁移后，会每 24 小时将更改同步到云，直到管理员停止或删除此迁移批次。
    
若要将用户切换到其云邮箱，管理员需要将其 MX 记录配置为指向 Microsoft 并在 Outlook 中重新配置用户的配置文件。 当用户切换到云邮箱时，将重新同步他们的本地脱机文件夹（.ost 文件），以下载迁移的邮件到客户端工作站。 迁移后，用户可以在他们的邮箱中回复旧邮件。
  
有关直接转换 Exchange 迁移的详细信息，请参阅[有关直接转换电子邮件迁移到 Office 365 您需要了解的信息](https://support.office.com/en-us/article/What-you-need-to-know-about-a-cutover-email-migration-to-Office-365-961978ef-f434-472d-a811-1801733869da)。
  
> [!IMPORTANT]
> An organization can migrate a maximum of 2,000 Exchange 2003, Exchange 2007, Exchange 2010, or Exchange 2013 mailboxes to the cloud using a cutover Exchange migration. > Exchange Online must connect to an on-premises Exchange Server, so the on-premises server must have a certificate issued by a trusted certificate authority and a public IP address. 
  
### <a name="staged-exchange-migration"></a>暂存 Exchange 迁移

With a staged migration, users can be migrated to the cloud using the web-based Exchange migration tool and the Directory Synchronization tool. Instead of migrating all users at once, like a cutover Exchange migration, administrators migrate users in batches. This is accomplished by uploading a .csv file to specify a partial list of users to migrate. In a staged migration, all of the users in an organization can share the same email domain name.
  
Staged Exchange migration requires administrators to use the Online Services Directory Synchronization tool. This provides users with a unified Global Address List (GAL) where the online environment is continuously synchronized with the on-premises environment.
  
有关暂存 Exchange 迁移的详细信息，请参阅[有关暂存电子邮件迁移您需要了解的信息](https://support.office.com/en-ie/article/What-you-need-to-know-about-a-staged-email-migration-to-Office-365-7e2c82be-5f3d-4e36-bc6b-e5b4d411e207)。
  
> [!IMPORTANT]
> Organizations can't use a staged Exchange migration to migrate Exchange 2010 and Exchange 2013 mailboxes. If you have fewer than 2,000 Exchange 2010 or Exchange 2013 mailboxes in your organization, you can use a cutover Exchange migration. If you have more than 2,000 Exchange 2010 or Exchange 2013 mailboxes, you can implement a hybrid deployment. > During migration, administrators must use the Online Services Directory Synchronization tool to provide users with a unified Global Address List where the online environment is continuously synchronized with the on-premises environment. 
  
## <a name="migration-tools"></a>迁移工具

Microsoft provides several tools to help migrate an existing email environment to Exchange Online. Which ones are appropriate depends on the organization's current environment and deployment goals:
  
- **Migration dashboard** Administrators can use the Migration dashboard in the Exchange admin center to manage mailbox migration to Exchange Online in a cutover or staged Exchange migration. Administrators can also use the dashboard to migrate the contents of users' mailboxes from an on-premises IMAP server to existing Exchange Online mailboxes. The dashboard gives administrators the following capabilities: 
    
  - **Create and start multiple migration batches** Administrators can create and queue up to 100 migration batches. Only one migration batch runs at a time, but administrators can queue up multiple batches, so when a migration batch is finished running the next batch in the queue starts. 
    
  - **Restart a migration batch with failures** After the initial synchronization for a migration batch, where items are copied from on-premises mailboxes to the cloud mailboxes for each user in the migration batch, some mailboxes may fail synchronization. Administrators can restart that migration batch to try to synchronize the failed mailboxes. 
    
  - **获得有关跳过项目的详细信息** 对于 IMAP 迁移、直接转换迁移和暂存迁移，迁移主控板将显示跳过的特定项目的有关信息，包括跳过原因和跳过项目在用户邮箱中的位置。 
    
  - **打开迁移报告** 管理员可以直接从主控板打开迁移批次的迁移统计数据或迁移错误报告。 
    
  - **编辑迁移批次** 如果暂存 Exchange 迁移或 IMAP 迁移的迁移批次位于迁移队列但是当前未运行，管理员可以编辑迁移批次。 
    
- **Azure Active Directory Sync tool** The Azure Active Directory Sync tool plays an important role in migration to hybrid email scenarios that utilize both Exchange Online and an on-premises Exchange Server. The tool performs a one-way synchronization from on-premises Active Directory to Exchange Online. After migration is complete, administrators only need to use Exchange Online to manage Active Directory users and groups. The tool also provides users with a unified Global Address List where the online environment is continuously synchronized with the on-premises environment. 
    
    有关 Azure Active Directory 同步工具的详细信息，请参阅 [Directory synchronization: Roadmap](https://go.microsoft.com/fwlink/p/?LinkId=287034)（目录同步：路线图）。
    
- **Hybrid Configuration Wizard** The Hybrid Configuration Wizard streamlines the hybrid deployment process by simplifying the on-premises and Exchange Online configuration of features and services. Introduced as part of Exchange Server 2010 Service Pack 2, the Hybrid Configuration Wizard is run only in on-premises organizations and has the following components: 
    
  - Exchange 管理中心 (EAC) 向导指导管理员完成配置混合部署的端到端流程。
    
  - 一组安排配置流程的 Exchange 命令行管理程序 (EMS) 命令。
    
    有关"混合配置"向导的详细信息，请参阅["混合配置"向导](https://go.microsoft.com/fwlink/p/?LinkId=271734)。
    
- **Remote Windows PowerShell** As part of the Exchange Online December 2011 Service Update, remote Windows PowerShell can be used to help troubleshoot migration errors. For instance, administrators can display diagnostic information for migration batches, as well as migration statistics and diagnostic information for users based on their primary SMTP addresses. 
    
## <a name="feature-availability"></a>功能可用性

若要查看跨计划、独立选项和内部部署解决方案的功能可用性，请参阅[Exchange Online 服务说明](exchange-online-service-description.md)。
  

