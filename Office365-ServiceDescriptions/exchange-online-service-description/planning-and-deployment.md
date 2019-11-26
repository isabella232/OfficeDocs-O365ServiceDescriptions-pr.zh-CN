---
title: 规划和部署
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-planning-and-deployment
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: e44e5e61-1f5d-4e68-981d-77a42f0ea0d4
ms.openlocfilehash: 30d1c68976bf450a87ace792af0b219b0fce21d4
ms.sourcegitcommit: 2b9f68f7731dfd6f9d3f33e31e6303e81985ebb2
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/26/2019
ms.locfileid: "39262735"
---
# <a name="planning-and-deployment"></a><span data-ttu-id="64a5d-102">计划和部署</span><span class="sxs-lookup"><span data-stu-id="64a5d-102">Planning and deployment</span></span>

## <a name="planning-for-service-changes-and-growth"></a><span data-ttu-id="64a5d-103">计划服务更改和增长</span><span class="sxs-lookup"><span data-stu-id="64a5d-103">Planning for service changes and growth</span></span>

<span data-ttu-id="64a5d-104">组织应基于他们的源电子邮件系统、所需结束状态（完全托管或部分托管）、要迁移的用户数量和实现最终状态的速度选择迁移选项。</span><span class="sxs-lookup"><span data-stu-id="64a5d-104">Organizations should choose migration options based on their source email systems, the desired end state (fully hosted or partially hosted), the number of users to migrate, and how quickly the end state needs to be reached.</span></span>
  
## <a name="deployment-options"></a><span data-ttu-id="64a5d-105">部署选项</span><span class="sxs-lookup"><span data-stu-id="64a5d-105">Deployment options</span></span>

- <span data-ttu-id="64a5d-106">**仅限云部署** 您的组织拥有在 Exchange Online 中托管的所有用户邮箱。</span><span class="sxs-lookup"><span data-stu-id="64a5d-106">**Cloud-only deployment** Your organization has all user mailboxes hosted in Exchange Online.</span></span> 
    
- <span data-ttu-id="64a5d-107">**Exchange 混合部署** 您的组织有一些在内部部署 Exchange 组织托管的用户邮箱，同时一些在 Exchange Online 中托管的用户邮箱。</span><span class="sxs-lookup"><span data-stu-id="64a5d-107">**Exchange hybrid deployment** Your organization has some user mailboxes hosted in an on-premises Exchange organization and some user mailboxes hosted in Exchange Online.</span></span> 
    
### <a name="cloud-only"></a><span data-ttu-id="64a5d-108">仅限云</span><span class="sxs-lookup"><span data-stu-id="64a5d-108">Cloud-only</span></span>

<span data-ttu-id="64a5d-p101">仅限于部署是您在 Exchange Online 服务中的组织不与内部部署 Exchange 组织连接的部署。所有用户和邮箱在 Exchange Online 和 Office 365 中托管和管理。</span><span class="sxs-lookup"><span data-stu-id="64a5d-p101">A cloud-only deployment is one where your organization in the Exchange Online service isn't connected with an on-premises Exchange organization. All users and mailboxes are hosted and managed in Exchange Online and Office 365.</span></span>
  
### <a name="hybrid"></a><span data-ttu-id="64a5d-111">混合</span><span class="sxs-lookup"><span data-stu-id="64a5d-111">Hybrid</span></span>

<span data-ttu-id="64a5d-p102">对 Microsoft Exchange 2003、Exchange 2007、Exchange 2010 和 Exchange 2013 内部部署组织可用的混合部署提供与一些在内部部署托管的邮箱和一些在 Exchange Online 邮箱托管的长期共存配置，或托管 Exchange Online 所有用户邮箱的迁移路径。混合部署使组织可以将随其现有内部部署 Microsoft Exchange 组织提供的功能丰富的体验和管理控制扩展到云。混合部署功能包括安全邮件传输、共享日历闲/忙信息以及内部部署和 Exchange Online 组织之间的邮件跟踪。</span><span class="sxs-lookup"><span data-stu-id="64a5d-p102">Available for Microsoft Exchange 2003, Exchange 2007, Exchange 2010 and Exchange 2013 on-premises organizations, a hybrid deployment offers either a long-term coexistence configuration with some mailboxes hosted on-premises and some mailboxes hosted in Exchange Online or a migration path to hosting all user mailboxes in Exchange Online. A hybrid deployment offers organizations the ability to extend the feature-rich experience and administrative control they have with their existing on-premises Microsoft Exchange organization to the cloud. Hybrid deployment features include secure mail transport, shared calendar free/busy information, and message tracking between the on-premises and Exchange Online organizations.</span></span>
  
<span data-ttu-id="64a5d-p103">有关混合部署的详细信息，请参阅 [Exchange Server 2013 混合部署](https://go.microsoft.com/fwlink/p/?LinkId=287035)。如果使用的是由世纪互联运营的 Office 365，请参阅[使用由世纪互联运营的 Office 365 配置 Exchange 混合部署功能](https://go.microsoft.com/fwlink/?LinkID=733373&amp;clcid=0x409)。</span><span class="sxs-lookup"><span data-stu-id="64a5d-p103">For more information about hybrid deployments, see [Exchange Server 2013 Hybrid Deployments](https://go.microsoft.com/fwlink/p/?LinkId=287035). If you are using Office 365 operated by 21Vianet, see [Configuring Exchange hybrid deployment features with Office 365 operated by 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733373&amp;clcid=0x409).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="64a5d-p104">本地 Exchange 2003 组织至少必须安装一个 Exchange 2010 客户端访问/邮箱服务器，才能使用 Exchange Online 配置混合部署。本地 Exchange 2007 组织至少必须安装一个 Exchange 2010 或 Exchange 2013 客户端访问和邮箱服务器，才能使用 Exchange Online 配置混合部署。本地 Exchange 2010 和 Exchange 2013 组织使用 Exchange Online 本地支持混合部署。若要详细了解混合部署中的 Exchange 服务器兼容性，请参阅[混合部署先决条件](https://go.microsoft.com/fwlink/p/?LinkId=243541)。 > 本地 Exchange 组织必须为其组织配置混合部署。我们强烈建议管理员使用 Exchange Server 部署助理和"混合配置"向导配置混合部署。有关详细信息，请参阅 [Exchange Server 部署助理](https://go.microsoft.com/fwlink/p/?LinkId=287036)</span><span class="sxs-lookup"><span data-stu-id="64a5d-p104">On-premises Exchange 2003 organizations must install at least one Exchange 2010 Client Access/Mailbox server to configure a hybrid deployment with Exchange Online. On-premises Exchange 2007 organizations must install at least one Exchange 2010 or Exchange 2013 Client Access and Mailbox server to configure a hybrid deployment with Exchange Online. On-premises Exchange 2010 and Exchange 2013 organizations natively support hybrid deployments with Exchange Online. For more information about Exchange server compatibility in hybrid deployments, see [Hybrid Deployment Prerequisites](https://go.microsoft.com/fwlink/p/?LinkId=243541)> On-premises Exchange organizations must configure their organization for a hybrid deployment. We strongly recommend that administrators use the Exchange Server Deployment Assistant and the Hybrid Configuration Wizard to configure the hybrid deployment. Learn more at [Exchange Server Deployment Assistant](https://go.microsoft.com/fwlink/p/?LinkId=287036)</span></span>
  
## <a name="migration-options"></a><span data-ttu-id="64a5d-123">迁移选项</span><span class="sxs-lookup"><span data-stu-id="64a5d-123">Migration options</span></span>

<span data-ttu-id="64a5d-p105">组织应基于他们的源电子邮件系统、所需结束状态（完全托管或部分托管）、要迁移的用户数量和实现最终状态的速度选择迁移选项。可能的迁移选项是：</span><span class="sxs-lookup"><span data-stu-id="64a5d-p105">Organizations should choose migration options based on their source email systems, the desired end state (fully hosted or partially hosted), the number of users to migrate, and how quickly the end state needs to be reached. Possible migration options are:</span></span>
  
- <span data-ttu-id="64a5d-126">**IMAP 迁移** 从基于 IMAP 的电子邮件系统迁移邮箱数据到 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="64a5d-126">**IMAP migration** Migrate mailbox data from IMAP-based email systems to Exchange Online.</span></span> 
    
- <span data-ttu-id="64a5d-127">**直接转换 Exchange 迁移** 在单个直接转换迁移中，从 Exchange Server 2003、Exchange Server 2007、Exchange Server 2010、Exchange 2013 和托管 Exchange 系统迁移邮箱到 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="64a5d-127">**Cutover Exchange migration** Migrate mailboxes from Exchange Server 2003, Exchange Server 2007, Exchange Server 2010, Exchange 2013 and Hosted Exchange systems to Exchange Online in a single cutover migration.</span></span> 
    
- <span data-ttu-id="64a5d-128">**暂存 Exchange 迁移** 执行暂存迁移，以使用基于 Web 的迁移工具从 Exchange Server 2003 或 Exchange Server 2007 迁移邮箱，并减少内部部署基础结构的变化。</span><span class="sxs-lookup"><span data-stu-id="64a5d-128">**Staged Exchange migration** Perform a staged migration to migrate mailboxes from Exchange Server 2003 or Exchange Server 2007 with web-based migration tools and minimal changes to on-premises infrastructure.</span></span> 
    
- <span data-ttu-id="64a5d-p106">**远程移动迁移** 将内部部署 Exchange 邮箱迁移至 Exchange 混合部署中的 Exchange Online。必须拥有 Exchange 混合部署，才能使用远程移动迁移。</span><span class="sxs-lookup"><span data-stu-id="64a5d-p106">**Remote move migration** Migrate on-premises Exchange mailboxes to Exchange Online in an Exchange hybrid deployment. You must have an Exchange hybrid deployment to use a remote move migration.</span></span> 
    
<span data-ttu-id="64a5d-131">有关将电子邮件和邮箱迁移到 Exchange Online 的详细信息，请参阅[到 Exchange Online 的邮箱迁移](https://support.office.com/en-us/article/-a3e3bddb-582e-4133-8670-e61b9f58627e)。</span><span class="sxs-lookup"><span data-stu-id="64a5d-131">For more information about migrating email and mailboxes to Exchange Online, see [Mailbox Migration to Exchange Online ](https://support.office.com/en-us/article/-a3e3bddb-582e-4133-8670-e61b9f58627e).</span></span>
  
### <a name="imap-migration"></a><span data-ttu-id="64a5d-132">IMAP 迁移</span><span class="sxs-lookup"><span data-stu-id="64a5d-132">IMAP migration</span></span>

<span data-ttu-id="64a5d-p107">Exchange Online 提供基于 Web 的工具，以从支持 IMAP 的电子邮件系统迁移邮箱数据。它将指导管理员完成以下迁移步骤：</span><span class="sxs-lookup"><span data-stu-id="64a5d-p107">Exchange Online offers a web-based tool for migrating mailbox data from email systems that support IMAP. It guides administrators through the following migration steps:</span></span> 
  
1. <span data-ttu-id="64a5d-135">为组织中的用户在云中创建空邮箱（这通常通过上载 .csv 文件或使用远程 Windows PowerShell 完成）。</span><span class="sxs-lookup"><span data-stu-id="64a5d-135">Create empty mailboxes in the cloud for users in the organization (typically this is done by uploading a .csv file or using remote Windows PowerShell).</span></span>
    
2. <span data-ttu-id="64a5d-136">输入远程服务器连接设置。</span><span class="sxs-lookup"><span data-stu-id="64a5d-136">Enter the remote server connection settings.</span></span>
    
3. <span data-ttu-id="64a5d-137">使用 CSV 文件指定将迁移其数据到 Exchange Online 邮箱的邮箱。</span><span class="sxs-lookup"><span data-stu-id="64a5d-137">Use a CSV file to specify the mailboxes whose data will be migrated to Exchange Online mailboxes.</span></span>
    
4. <span data-ttu-id="64a5d-138">输入该信息后，Exchange Online 开始通过 IMAP 迁移邮箱内容（日历项目、联系人、任务和其他非邮件项目将不迁移）。</span><span class="sxs-lookup"><span data-stu-id="64a5d-138">After this information is entered, Exchange Online begins to migrate mailbox content via IMAP (calendar items, contacts, tasks, and other non-mail items are not migrated).</span></span>
    
<span data-ttu-id="64a5d-139">有关 IMAP 迁移的详细信息，请参阅[将电子邮件从 IMAP 服务器迁移到 Exchange Online 邮箱](https://support.office.com/en-ie/article/Migrate-your-IMAP-mailboxes-to-Office-365-3fe19996-29bc-4879-aab9-5a622b2f1481)和[迁移其他类型的 IMAP 邮箱](https://support.office.com/en-ie/article/Migrate-other-types-of-IMAP-mailboxes-to-Office-365-58890ccd-ce5e-4d94-be75-560a3b70a706)。</span><span class="sxs-lookup"><span data-stu-id="64a5d-139">For more information about IMAP migration, see [Migrate Email from an IMAP Server to Exchange Online Mailboxes](https://support.office.com/en-ie/article/Migrate-your-IMAP-mailboxes-to-Office-365-3fe19996-29bc-4879-aab9-5a622b2f1481) and [Migrate other types of IMAP mailboxes](https://support.office.com/en-ie/article/Migrate-other-types-of-IMAP-mailboxes-to-Office-365-58890ccd-ce5e-4d94-be75-560a3b70a706).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="64a5d-140">为避免在迁移期间过度使用远程服务器的资源和带宽，Exchange Online 将创建不超过 10 个与 IMAP 服务器的连接。</span><span class="sxs-lookup"><span data-stu-id="64a5d-140">To avoid overusing the remote server's resources and bandwidth during the migration, Exchange Online creates fewer than 10 connections to the IMAP server.</span></span> 
  
### <a name="cutover-exchange-migration"></a><span data-ttu-id="64a5d-141">切换 Exchange 迁移</span><span class="sxs-lookup"><span data-stu-id="64a5d-141">Cutover Exchange migration</span></span>

<span data-ttu-id="64a5d-p108">Exchange Online 提供基于 Web 的工具，以从内部部署 Exchange Server 2003、Exchange Server 2007 或 Exchange Server 2010 环境迁移数据。它将指导管理员完成以下迁移步骤：</span><span class="sxs-lookup"><span data-stu-id="64a5d-p108">Exchange Online offers a web-based tool for migrating data from on-premises Exchange Server 2003, Exchange Server 2007, or Exchange Server 2010 environments. It guides an administrator through the following migration steps:</span></span>
  
1. <span data-ttu-id="64a5d-144">为内部部署管理员帐户使用电子邮件地址和凭据，Exchange Online 使用自动发现服务连接到内部部署电子邮件组织。</span><span class="sxs-lookup"><span data-stu-id="64a5d-144">Using the email address and credentials for an on-premises administrator account, Exchange Online connects to the on-premises email organization by using the Autodiscover service.</span></span>
    
2. <span data-ttu-id="64a5d-145">Exchange Online 使用 RPC/HTTP 连接读取远程服务器的目录信息，并在 Exchange Online 中创建邮箱。</span><span class="sxs-lookup"><span data-stu-id="64a5d-145">Exchange Online uses an RPC/HTTP connection to read directory information from the remote server and create mailboxes in Exchange Online.</span></span>
    
3. <span data-ttu-id="64a5d-p109">Exchange Online 同步邮箱内容到云邮箱。用户保持连接到原始邮箱，同时他们的数据将被迁移到 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="64a5d-p109">Exchange Online synchronizes the mailbox content to the cloud mailboxes. Users remain connected to their original mailboxes while their data is being migrated to Exchange Online.</span></span>
    
4. <span data-ttu-id="64a5d-148">在完成初始迁移后，会每 24 小时将更改同步到云，直到管理员停止或删除此迁移批次。</span><span class="sxs-lookup"><span data-stu-id="64a5d-148">After the initial migration is complete, any changes are synchronized to the cloud every 24 hours until the administrator stops or deletes the migration batch.</span></span>
    
<span data-ttu-id="64a5d-p110">要切换用户到云邮箱，管理员可以配置 MX 记录指向 Office 365 并在 Outlook 中重新配置用户配置文件。当用户切换到云邮箱时，将重新同步他们的本地脱机文件夹（.ost 文件），以下载迁移的邮件到客户端工作站。迁移后，用户可以在他们的邮箱中回复旧邮件。</span><span class="sxs-lookup"><span data-stu-id="64a5d-p110">To switch users to their cloud mailboxes, administrators configure their MX record to point to Office 365 and reconfigure the users' profiles in Outlook. When users switch to their cloud mailboxes, their local offline folders (.ost files) will resynchronize, resulting in the download of migrated mail to the client workstation. Users can reply to old messages in their mailboxes after migration.</span></span>
  
<span data-ttu-id="64a5d-152">有关直接转换 Exchange 迁移的详细信息，请参阅[有关直接转换电子邮件迁移到 Office 365 您需要了解的信息](https://support.office.com/en-us/article/What-you-need-to-know-about-a-cutover-email-migration-to-Office-365-961978ef-f434-472d-a811-1801733869da)。</span><span class="sxs-lookup"><span data-stu-id="64a5d-152">For more information about a cutover Exchange migration, see [What you need to know about a cutover email migration to Office 365](https://support.office.com/en-us/article/What-you-need-to-know-about-a-cutover-email-migration-to-Office-365-961978ef-f434-472d-a811-1801733869da).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="64a5d-p111">组织可使用直接转换 Exchange 迁移将最多 2,000 个 Exchange 2003、Exchange 2007、Exchange 2010 或 Exchange 2013 邮箱迁移到云。 > Exchange Online 必须连接到内部部署 Exchange Server，以便内部部署服务器必须拥有受信任的证书颁发机构颁发的证书和公共 IP 地址。</span><span class="sxs-lookup"><span data-stu-id="64a5d-p111">An organization can migrate a maximum of 2,000 Exchange 2003, Exchange 2007, Exchange 2010, or Exchange 2013 mailboxes to the cloud using a cutover Exchange migration. > Exchange Online must connect to an on-premises Exchange Server, so the on-premises server must have a certificate issued by a trusted certificate authority and a public IP address.</span></span> 
  
### <a name="staged-exchange-migration"></a><span data-ttu-id="64a5d-155">暂存 Exchange 迁移</span><span class="sxs-lookup"><span data-stu-id="64a5d-155">Staged Exchange migration</span></span>

<span data-ttu-id="64a5d-p112">对于暂存迁移，用户可以使用基于 Web 的 Exchange 迁移工具和目录同步工具迁移到云。与一次性迁移所有用户的直接转换 Exchange 迁移不同的是，管理员可以分批迁移用户。这可通过上载 .csv 文件以指定要迁移的部分用户列表实现。在暂存迁移中，组织中的所有用户可以共享相同的电子邮件域名。</span><span class="sxs-lookup"><span data-stu-id="64a5d-p112">With a staged migration, users can be migrated to the cloud using the web-based Exchange migration tool and the Directory Synchronization tool. Instead of migrating all users at once, like a cutover Exchange migration, administrators migrate users in batches. This is accomplished by uploading a .csv file to specify a partial list of users to migrate. In a staged migration, all of the users in an organization can share the same email domain name.</span></span>
  
<span data-ttu-id="64a5d-p113">暂存 Exchange 迁移要求管理员使用 Online Services 目录同步工具。这将为用户提供统一全局地址列表 (GAL)，其中在线环境与内部部署环境持续同步。</span><span class="sxs-lookup"><span data-stu-id="64a5d-p113">Staged Exchange migration requires administrators to use the Online Services Directory Synchronization tool. This provides users with a unified Global Address List (GAL) where the online environment is continuously synchronized with the on-premises environment.</span></span>
  
<span data-ttu-id="64a5d-162">有关暂存 Exchange 迁移的详细信息，请参阅[有关暂存电子邮件迁移您需要了解的信息](https://support.office.com/en-ie/article/What-you-need-to-know-about-a-staged-email-migration-to-Office-365-7e2c82be-5f3d-4e36-bc6b-e5b4d411e207)。</span><span class="sxs-lookup"><span data-stu-id="64a5d-162">For more information about staged Exchange migrations, see [What you need to know about a staged email migration](https://support.office.com/en-ie/article/What-you-need-to-know-about-a-staged-email-migration-to-Office-365-7e2c82be-5f3d-4e36-bc6b-e5b4d411e207).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="64a5d-p114">组织无法使用暂存 Exchange 迁移来迁移 Exchange 2010 和 Exchange 2013 邮箱。如果您组织中的 Exchange 2010 或 Exchange 2013 邮箱数少于 2,000，则可使用直接转换 Exchange 迁移。如果您的 Exchange 2010 或 Exchange 2013 邮箱数多于 2,000，则可实施混合部署。 > 在迁移期间，管理员必须使用 Online Services 目录同步工具为用户提供统一全局地址列表，其中在线环境与内部部署环境持续同步。</span><span class="sxs-lookup"><span data-stu-id="64a5d-p114">Organizations can't use a staged Exchange migration to migrate Exchange 2010 and Exchange 2013 mailboxes. If you have fewer than 2,000 Exchange 2010 or Exchange 2013 mailboxes in your organization, you can use a cutover Exchange migration. If you have more than 2,000 Exchange 2010 or Exchange 2013 mailboxes, you can implement a hybrid deployment. > During migration, administrators must use the Online Services Directory Synchronization tool to provide users with a unified Global Address List where the online environment is continuously synchronized with the on-premises environment.</span></span> 
  
## <a name="migration-tools"></a><span data-ttu-id="64a5d-167">迁移工具</span><span class="sxs-lookup"><span data-stu-id="64a5d-167">Migration tools</span></span>

<span data-ttu-id="64a5d-p115">Microsoft 提供几个工具帮助迁移现有电子邮件环境到 Exchange Online。适用工具取决于组织的当前环境和部署目标：</span><span class="sxs-lookup"><span data-stu-id="64a5d-p115">Microsoft provides several tools to help migrate an existing email environment to Exchange Online. Which ones are appropriate depends on the organization's current environment and deployment goals:</span></span>
  
- <span data-ttu-id="64a5d-p116">**迁移主控板** 管理员可以使用 Exchange 管理中心的迁移主控板，在直接转换或暂存 Exchange 迁移中管理 Exchange Online 的邮箱迁移。管理员还可以使用主控板，将用户邮箱的内容从内部部署 IMAP 服务器迁移到 Exchange Online 的现有邮箱。主控板为管理员提供了以下功能：</span><span class="sxs-lookup"><span data-stu-id="64a5d-p116">**Migration dashboard** Administrators can use the Migration dashboard in the Exchange admin center to manage mailbox migration to Exchange Online in a cutover or staged Exchange migration. Administrators can also use the dashboard to migrate the contents of users' mailboxes from an on-premises IMAP server to existing Exchange Online mailboxes. The dashboard gives administrators the following capabilities:</span></span> 
    
  - <span data-ttu-id="64a5d-p117">**创建并启动多个迁移批次** 管理员可以创建并排队多达 100 个迁移批次。一次仅能运行一个迁移批次，但是管理员可以排队多个批次，以便在完成一个迁移批次后运行队列的下一个批次。</span><span class="sxs-lookup"><span data-stu-id="64a5d-p117">**Create and start multiple migration batches** Administrators can create and queue up to 100 migration batches. Only one migration batch runs at a time, but administrators can queue up multiple batches, so when a migration batch is finished running the next batch in the queue starts.</span></span> 
    
  - <span data-ttu-id="64a5d-p118">**失败后重新启动迁移批次** 在初始同步迁移批次后（其中为迁移批次中的每个用户从内部部署邮箱复制项目到云邮箱），一些邮箱可能同步失败。管理员可以重新启动该迁移批次，以重试同步失败的邮箱。</span><span class="sxs-lookup"><span data-stu-id="64a5d-p118">**Restart a migration batch with failures** After the initial synchronization for a migration batch, where items are copied from on-premises mailboxes to the cloud mailboxes for each user in the migration batch, some mailboxes may fail synchronization. Administrators can restart that migration batch to try to synchronize the failed mailboxes.</span></span> 
    
  - <span data-ttu-id="64a5d-177">**获得有关跳过项目的详细信息** 对于 IMAP 迁移、直接转换迁移和暂存迁移，迁移主控板将显示跳过的特定项目的有关信息，包括跳过原因和跳过项目在用户邮箱中的位置。</span><span class="sxs-lookup"><span data-stu-id="64a5d-177">**Get details about skipped items** For IMAP migrations, cutover migrations, and staged migrations, the Migration dashboard displays information about the specific items that were skipped, including the reason why and where the item is located in the user's mailbox.</span></span> 
    
  - <span data-ttu-id="64a5d-178">**打开迁移报告** 管理员可以直接从主控板打开迁移批次的迁移统计数据或迁移错误报告。</span><span class="sxs-lookup"><span data-stu-id="64a5d-178">**Open migration reports** Administrators can open migration statistics or the migration error report for a migration batch right from the dashboard.</span></span> 
    
  - <span data-ttu-id="64a5d-179">**编辑迁移批次** 如果暂存 Exchange 迁移或 IMAP 迁移的迁移批次位于迁移队列但是当前未运行，管理员可以编辑迁移批次。</span><span class="sxs-lookup"><span data-stu-id="64a5d-179">**Edit a migration batch** If a migration batch for a staged Exchange migration or an IMAP migration is in the migration queue but not currently running, administrators can edit the migration batch.</span></span> 
    
- <span data-ttu-id="64a5d-p119">**Azure Active Directory 同步工具**Azure Active Directory 同步工具在使用 Exchange Online 和内部部署 Exchange Server 的混合电子邮件方案迁移中具有重要作用。该工具将执行从 Active Directory 到 Exchange Online 的单向同步。完成迁移后，管理员仅需要使用 Exchange Online 就可管理 Active Directory 用户和组。该工具还为用户提供统一全局地址列表，其中在线环境与内部部署环境持续同步。</span><span class="sxs-lookup"><span data-stu-id="64a5d-p119">**Azure Active Directory Sync tool** The Azure Active Directory Sync tool plays an important role in migration to hybrid email scenarios that utilize both Exchange Online and an on-premises Exchange Server. The tool performs a one-way synchronization from on-premises Active Directory to Exchange Online. After migration is complete, administrators only need to use Exchange Online to manage Active Directory users and groups. The tool also provides users with a unified Global Address List where the online environment is continuously synchronized with the on-premises environment.</span></span> 
    
    <span data-ttu-id="64a5d-184">有关 Azure Active Directory 同步工具的详细信息，请参阅 [Directory synchronization: Roadmap](https://go.microsoft.com/fwlink/p/?LinkId=287034)（目录同步：路线图）。</span><span class="sxs-lookup"><span data-stu-id="64a5d-184">For more information about the Azure Active Directory Sync tool, see [Directory synchronization: Roadmap](https://go.microsoft.com/fwlink/p/?LinkId=287034).</span></span>
    
- <span data-ttu-id="64a5d-p120">**混合配置向导** 混合配置向导可简化内部部署和 Exchange Online 配置的功能和服务，从而简化混合部署流程。作为 Exchange Server 2010 Service Pack 2 一部分推出的混合配置向导仅在内部部署组织中运行，同时拥有以下组件：</span><span class="sxs-lookup"><span data-stu-id="64a5d-p120">**Hybrid Configuration Wizard** The Hybrid Configuration Wizard streamlines the hybrid deployment process by simplifying the on-premises and Exchange Online configuration of features and services. Introduced as part of Exchange Server 2010 Service Pack 2, the Hybrid Configuration Wizard is run only in on-premises organizations and has the following components:</span></span> 
    
  - <span data-ttu-id="64a5d-187">Exchange 管理中心 (EAC) 向导指导管理员完成配置混合部署的端到端流程。</span><span class="sxs-lookup"><span data-stu-id="64a5d-187">An Exchange admin center (EAC) wizard that guides administrators through the end-to-end process for configuring a hybrid deployment.</span></span>
    
  - <span data-ttu-id="64a5d-188">一组安排配置流程的 Exchange 命令行管理程序 (EMS) 命令。</span><span class="sxs-lookup"><span data-stu-id="64a5d-188">A set of Exchange Management Shell (EMS) commands that orchestrate the configuration process.</span></span>
    
    <span data-ttu-id="64a5d-189">有关"混合配置"向导的详细信息，请参阅["混合配置"向导](https://go.microsoft.com/fwlink/p/?LinkId=271734)。</span><span class="sxs-lookup"><span data-stu-id="64a5d-189">For more information about the Hybrid Configuration Wizard, see [Hybrid Configuration Wizard](https://go.microsoft.com/fwlink/p/?LinkId=271734).</span></span>
    
- <span data-ttu-id="64a5d-p121">**远程 Windows PowerShell** 作为 Exchange Online 2011 年 11 月服务更新的远程 Windows PowerShell 可用于帮助故障排除迁移错误。例如，管理员可以显示迁移批次的诊断信息，以及迁移统计数据和基于主 SMTP 地址为用户显示诊断信息。</span><span class="sxs-lookup"><span data-stu-id="64a5d-p121">**Remote Windows PowerShell** As part of the Exchange Online December 2011 Service Update, remote Windows PowerShell can be used to help troubleshoot migration errors. For instance, administrators can display diagnostic information for migration batches, as well as migration statistics and diagnostic information for users based on their primary SMTP addresses.</span></span> 
    
## <a name="feature-availability"></a><span data-ttu-id="64a5d-192">功能可用性</span><span class="sxs-lookup"><span data-stu-id="64a5d-192">Feature availability</span></span>

<span data-ttu-id="64a5d-193">若要查看跨 Office 365 计划、独立选项和内部部署解决方案的功能可用性，请参阅[Exchange Online 服务说明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="64a5d-193">To view feature availability across Office 365 plans, standalone options, and on-premises solutions see, [Exchange Online service description](exchange-online-service-description.md).</span></span>
  

