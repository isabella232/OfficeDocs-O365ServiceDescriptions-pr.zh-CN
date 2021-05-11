---
title: 域中的收件人、域和公司Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: 阅读本文，了解 Microsoft Exchange Online Protection (EOP) 中的收件人、域和公司) 。
ms.openlocfilehash: f58ffe829be839d8321cfc98f331d1836986e293
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652994"
---
# <a name="recipient-domain-and-company-management-in-exchange-online-protection"></a>域中的收件人、域和公司Exchange Online Protection

Microsoft Exchange OnlineEOP (保护) 提供了几种管理收件人、域和公司信息的方式。 作为管理员，您可以在 Exchange 管理中心 (EAC) 中执行某些管理任务，并验证在 Microsoft 365 管理中心中执行的其他管理任务。
  
要查找有关 EOP 所有功能的信息吗？ 请参阅Exchange Online Protection[服务说明](exchange-online-protection-service-description.md)。
  
## <a name="mail-recipients"></a>Mail recipients

邮件收件人被归为邮件用户或组，可直接在 EAC 中或使用远程 Windows PowerShell 通过目录同步进行管理。 如果要在本地管理收件人，必须运行目录同步，这样邮件收件人才能反映在 EAC 中。 在 EAC 中Microsoft 365管理的用户不可在 EAC 中查看，但可以在 EAC 的管理员角色组成员身份中添加或删除这些用户。 若要详细了解 EOP 中的收件人，请参阅 [EOP 中的收件人](/microsoft-365/security/office-365-security/manage-recipients-in-eop)。
  
## <a name="admin-role-group-permissions"></a>Admin role group permissions

在 EOP 中，只能配置管理角色。在 EAC 中，可以将用户直接添加到默认管理员角色组中，也可以直接从中删除。无可用 RBAC 自定义项。有关详细信息，请参阅[管理 EOP 中的管理员角色组权限](/microsoft-365/security/office-365-security/manage-admin-role-group-permissions-in-eop)。
  
## <a name="domain-management"></a>域管理

托管域是指受 EOP 保护的域。 可以在 EAC 中查看托管域并编辑域类型。 域设置和管理发生在 Microsoft 365中心，更改将反映在 EAC 中。 有关详细信息，请参阅[查看或编辑 EOP 中的托管域](/microsoft-365/security/office-365-security/exchange-online-protection-overview)。
  
## <a name="match-subdomains"></a>Match subdomains

在 EOP 中，可以启用流向托管域的子域的邮件流。有关详细信息，请参阅[在 EOP 中为子域启用电子邮件流](/microsoft-365/security/office-365-security/mail-flow-in-eop)。 
  
## <a name="directory-based-edge-blocking-dbeb"></a>基于目录的边缘阻止 (DBEB)

通过基于目录的边缘阻止功能，您可以在服务网络外围拒绝发送至无效收件人的邮件。 DBEB 允许管理员向 Microsoft 添加启用邮件的收件人并阻止发送到 Microsoft 中不存在的电子邮件地址的所有邮件。 如果将邮件发送到 Microsoft 中提供的有效电子邮件地址，该邮件将继续通过反恶意软件、反垃圾邮件、传输规则 (其他服务筛选) 。 如果地址不存在，服务甚至会在进行筛选之前阻止邮件，并向发件人发送未送达报告 (NDR) 以通知其邮件未送达。 
  
必须执行一些用户和域配置，才能启用 DBEB。有关详细信息，请参阅[使用基于目录的边缘阻止拒绝发送给无效收件人的邮件](/exchange/mail-flow-best-practices/use-directory-based-edge-blocking)。
  
## <a name="feature-availability"></a>功能可用性

若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅Exchange Online Protection[说明](exchange-online-protection-service-description.md)。