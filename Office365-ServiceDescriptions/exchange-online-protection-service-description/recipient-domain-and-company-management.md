---
title: 收件人、域和公司管理
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: Microsoft Exchange Online Protection (EOP) 提供了几种管理您的收件人、域和公司信息的方法。 作为管理员, 您可以在 Exchange 管理中心 (EAC) 内执行某些管理任务, 并验证在 Microsoft 365 管理中心中执行的其他管理任务。
ms.openlocfilehash: ff773ca3e19c9f9419ad907ed102f6af8a3567c2
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/07/2019
ms.locfileid: "30466899"
---
# <a name="recipient-domain-and-company-management"></a>收件人、域和公司管理

Microsoft Exchange Online Protection (EOP) 提供了几种管理您的收件人、域和公司信息的方法。 作为管理员, 您可以在 Exchange 管理中心 (EAC) 内执行某些管理任务, 并验证在 Microsoft 365 管理中心中执行的其他管理任务。
  
要查找有关 EOP 所有功能的信息吗？ 请参阅 [Exchange Online Protection 服务说明](exchange-online-protection-service-description.md)。
  
## <a name="mail-recipients"></a>Mail recipients
<a name="BKMK_mailrecipients"> </a>

邮件收件人被归为邮件用户或组，可直接在 EAC 中或使用远程 Windows PowerShell 通过目录同步进行管理。 如果要在本地管理收件人，必须运行目录同步，这样邮件收件人才能反映在 EAC 中。 仅在 Microsoft 365 管理中心内管理的用户无法在 eac 中查看, 但可以在 eac 的管理员角色组中的成员身份添加或删除它们。 若要详细了解 EOP 中的收件人，请参阅 [EOP 中的收件人](https://go.microsoft.com/fwlink/p/?LinkId=280011)。
  
## <a name="admin-role-group-permissions"></a>Admin role group permissions
<a name="BKMK_adminrolegrouppermissions"> </a>

在 EOP 中，只能配置管理角色。在 EAC 中，可以将用户直接添加到默认管理员角色组中，也可以直接从中删除。无可用 RBAC 自定义项。有关详细信息，请参阅[管理 EOP 中的管理员角色组权限](https://go.microsoft.com/fwlink/p/?LinkId=282238)。
  
## <a name="domain-management"></a>Domain management
<a name="BKMK_domainmanagement"> </a>

托管域是指受 EOP 保护的域。 可以在 EAC 中查看托管域并编辑域类型。 域设置和管理在 Microsoft 365 管理中心发生, 并且更改在 EAC 中反映出来。 有关详细信息，请参阅[查看或编辑 EOP 中的托管域](https://go.microsoft.com/fwlink/p/?LinkId=282239)。
  
## <a name="match-subdomains"></a>Match subdomains
<a name="BKMK_EOP_Match_Subdomains"> </a>

在 EOP 中，可以启用流向托管域的子域的邮件流。有关详细信息，请参阅[在 EOP 中为子域启用电子邮件流](https://go.microsoft.com/fwlink/p/?LinkId=397213)。 
  
## <a name="directory-based-edge-blocking-dbeb"></a>Directory Based Edge Blocking (DBEB)
<a name="BKMK_DBEB"> </a>

通过基于目录的边缘阻止功能，您可以在服务网络外围拒绝发送至无效收件人的邮件。通过 DBEB，管理员可以向 Office 365 添加已启用邮件的收件人，并阻止发送到 Office 365 中不存在的电子邮件地址的所有邮件。如果邮件发送到 Office 365 中存在的有效电子邮件地址，则会继续通过其余服务筛选层（反恶意邮件、反垃圾邮件、传输规则）。如果地址不存在，服务甚至会在进行筛选之前阻止邮件，并向发件人发送未送达报告 (NDR) 以通知其邮件未送达。 
  
必须执行一些用户和域配置，才能启用 DBEB。有关详细信息，请参阅[使用基于目录的边缘阻止拒绝发送给无效收件人的邮件](https://go.microsoft.com/fwlink/p/?LinkId=390676)。
  
## <a name="feature-availability"></a>功能可用性
<a name="BKMK_DBEB"> </a>

若要查看在各个 Office 365 计划、独立选项和内部部署解决方案之间的功能可用性，请参阅 [Exchange Online Protection 服务说明](exchange-online-protection-service-description.md)。
  

