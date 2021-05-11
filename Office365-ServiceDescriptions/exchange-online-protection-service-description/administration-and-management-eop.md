---
title: 管理中的Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- administration-and-management-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9448f39-5e8a-48a4-80bc-b12b6fb72544
description: 本文介绍可供 EOP 管理员Microsoft Exchange Online EOP (管理) 接口。
ms.openlocfilehash: f4b1aa1e9345740528763ff45a3fc99858fbd71a
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653064"
---
# <a name="administration-and-management-in-exchange-online-protection"></a><span data-ttu-id="d15d3-103">管理中的Exchange Online Protection</span><span class="sxs-lookup"><span data-stu-id="d15d3-103">Administration and management in Exchange Online Protection</span></span>

<span data-ttu-id="d15d3-104">本文介绍可供 EOP 管理员Microsoft Exchange Online EOP (管理) 接口。</span><span class="sxs-lookup"><span data-stu-id="d15d3-104">This article describes management interfaces that are available to Microsoft Exchange Online Protection (EOP) administrators.</span></span>
  
<span data-ttu-id="d15d3-105">要查找有关 EOP 所有功能的信息吗？</span><span class="sxs-lookup"><span data-stu-id="d15d3-105">Looking for information about all EOP features?</span></span> <span data-ttu-id="d15d3-106">请参阅Exchange Online Protection[服务说明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="d15d3-106">See the [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="access-to-the-microsoft-365-admin-center"></a><span data-ttu-id="d15d3-107">访问 Microsoft 365 管理中心</span><span class="sxs-lookup"><span data-stu-id="d15d3-107">Access to the Microsoft 365 admin center</span></span>

<span data-ttu-id="d15d3-108">管理Microsoft 365中心是一个 Web 门户，每个公司的服务管理员可以从该门户管理他们订阅的每个Microsoft 服务和设置。</span><span class="sxs-lookup"><span data-stu-id="d15d3-108">The Microsoft 365 admin center is the web portal from which each company's service administrator can manage user accounts and settings for each of the Microsoft services to which they subscribe.</span></span> <span data-ttu-id="d15d3-109">在管理Microsoft 365内，管理员可以访问指向 EAC 的链接，可以在其中管理特定于 EOP 的设置。</span><span class="sxs-lookup"><span data-stu-id="d15d3-109">From within the Microsoft 365 admin center, administrators can follow links to the EAC, where they can manage settings specific to EOP.</span></span>
  
## <a name="access-to-the-exchange-admin-center"></a><span data-ttu-id="d15d3-110">对 Exchange 管理中心的访问权限</span><span class="sxs-lookup"><span data-stu-id="d15d3-110">Access to the Exchange admin center</span></span>

<span data-ttu-id="d15d3-111">Exchange 管理中心 (EAC) 是一个统一管理控制台，不仅易于使用，还针对所有类型的部署进行了优化。</span><span class="sxs-lookup"><span data-stu-id="d15d3-111">The Exchange admin center (EAC) is a single unified management console that allows for ease of use and is optimized for all types of deployments.</span></span> <span data-ttu-id="d15d3-112">新推出的改进后 EAC 替代了 Forefront Online Protection for Exchange 管理中心。</span><span class="sxs-lookup"><span data-stu-id="d15d3-112">The new and improved EAC replaces the Forefront Online Protection for Exchange Administration Center.</span></span> <span data-ttu-id="d15d3-113">EAC 提供与 Microsoft 365 的紧密集成，以及跨 Exchange 2013 (Microsoft Exchange Online Microsoft Exchange Server 一致的无缝 UI) 。</span><span class="sxs-lookup"><span data-stu-id="d15d3-113">EAC provides a tighter integration with Microsoft 365 and a consistent, seamless UI experience across Exchange products (Microsoft Exchange Online and Microsoft Exchange Server 2013).</span></span> <span data-ttu-id="d15d3-114">有关 EAC 的详细信息，请参阅 [Exchange Online Protection 中的 Exchange 管理中心](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop)。</span><span class="sxs-lookup"><span data-stu-id="d15d3-114">For more information about the EAC, see [Exchange Admin Center in Exchange Online Protection](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop).</span></span>
  
## <a name="remote-windows-powershell-access"></a><span data-ttu-id="d15d3-115">远程 Windows PowerShell 访问</span><span class="sxs-lookup"><span data-stu-id="d15d3-115">Remote Windows PowerShell access</span></span>

 <span data-ttu-id="d15d3-p104">管理员可以使用远程 Windows PowerShell 命令行执行管理任务。若要详细了解如何使用 Windows PowerShell（包括如何创建远程 Shell 会话以及每个 cmdlet 的相关文档），请参阅 [Exchange Online PowerShell](/powershell/exchange/exchange-online-powershell)。</span><span class="sxs-lookup"><span data-stu-id="d15d3-p104">Administrators can use Remote Windows PowerShell to perform management tasks from the command line. For more information about how to use Windows PowerShell, including information about creating a remote Shell session and documentation about each cmdlet, see [Exchange Online PowerShell](/powershell/exchange/exchange-online-powershell).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="d15d3-118">功能可用性</span><span class="sxs-lookup"><span data-stu-id="d15d3-118">Feature availability</span></span>

<span data-ttu-id="d15d3-119">若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅Exchange Online Protection[说明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="d15d3-119">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>
