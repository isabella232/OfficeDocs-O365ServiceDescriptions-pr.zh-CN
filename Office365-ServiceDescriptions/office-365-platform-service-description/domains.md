---
title: 域
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-domains
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 5c374309-8016-4f18-8f2a-bceeb863ca67
description: 添加域时，分步向导可帮助您添加用户并将电子邮件地址和其他服务转换为您的公司名称。 完成向导后，你的企业电子邮件将开始发送到 Microsoft，而不是发送到当前的电子邮件提供商。 若要了解更多信息，请参阅将用户和域添加到 Microsoft。 如果您使用由世纪互联运营的 Office 365，请参阅验证您的域。
ms.openlocfilehash: 591364950fda2ebc070255a010435a74c4f2e6c41882236a1e35b987ba54c605
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/06/2021
ms.locfileid: "54662985"
---
# <a name="domains"></a>域

添加域时，分步向导可帮助您添加用户并将电子邮件地址和其他服务转换为您的公司名称。 完成向导后，你的企业电子邮件将开始发送到 Microsoft，而不是发送到当前的电子邮件提供商。 若要了解更多信息，请参阅[将用户和域添加到 Microsoft。](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611) 如果您使用由世纪互联运营的 Office 365，请参阅[验证您的域](/office365/admin/setup/add-domain)。
  
## <a name="custom-domains"></a>自定义域

你最多可以将 900 个域添加到订阅 (包括子域) 。 无法将域添加到已Microsoft 365 Microsoft 云服务中已使用的域。 这意味着不能将同一个域添加到多个订阅。 有关详细信息，请参阅域 [常见问题](https://support.office.com/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a)解答。
  
### <a name="second-and-third-level-domains"></a>第二级域和第三级域

使用 Office 365 企业版 和 Microsoft 365 商业应用版，可以添加任何级别的域，包括第三级域（如 marketing.contoso.com）。 请参阅 [向 Microsoft 添加自定义子域或多个域](/office365/admin/setup/domains-faq)。 如果您使用的是由世纪互联运营的 Office 365，请参阅[将自定义子域或多个域添加到由世纪互联运营的 Office 365](/office365/admin/setup/domains-faq)。
  
## <a name="domain-verification-and-managing-dns-records"></a>域验证和管理 DNS 记录

使用 Microsoft 365，可以在 DNS 托管提供商中管理所有 DNS 记录，或者选择让 Microsoft 设置和管理域的 DNS 记录。 如果继续管理记录，则根据需要将特定记录更改为Microsoft 服务记录。 有关我们提供用于添加记录的分步说明的域注册机构列表，包括要用于每条记录的特定值，请参阅创建[DNS](/office365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider)记录，或者，如果你使用的是由世纪银行运营的 Office 365，请参阅在任何提供商处为由世纪银行运营的 Office 365 创建 DNS 记录。 
  
如果 Microsoft 为您管理您的域的 DNS 记录，则必须先将域的名称服务器记录切换为指向 Microsoft，然后 Microsoft 设置您的服务，然后在 Microsoft 中管理您的域的 DNS 记录。
  
如果你的域在 GoDaddy 注册，Microsoft 可以在 GoDaddy 上创建所需的记录。 
  
无论您的 DNS 记录在何处托管，都可以将 DNS 记录设置为将域用于 Microsoft 或其他宿主提供商托管的公共网站的 URL。 
  
Microsoft 主动检查 DNS 记录，以查找并帮助解决 DNS 问题。 如果您的 DNS 记录与我们希望的不匹配，您将收到 Microsoft 365 管理中心 中的通知，以及告诉您如何解决已识别的可能问题的信息。
  
有关详细信息，请参阅 Microsoft 如何管理[DNS](/office365/admin/setup/domains-faq)记录，或者，有关由世纪Office 365运营的 DNS 记录，请参阅管理 DNS 记录时Office 365创建 DNS[记录](/office365/admin/services-in-china/create-dns-records-when-you-manage-your-dns-records)。
  
## <a name="sharing-a-domain"></a>共享域

你可以试用 Microsoft 上的域的一些电子邮件地址，以及之前的电子邮件提供商的一些电子邮件地址。 建议仅在试点期间使用，因为它需要额外的设置步骤，并且对Microsoft 服务。 有关详细信息，请参阅：
  
- [小型企业Microsoft 365试用](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [针对Microsoft 365大型企业的 (试用FastTrack) ](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>功能可用性

若要查看跨业务Microsoft 365、独立选项和本地解决方案的功能可用性，请参阅 Microsoft 365 和 Office 365[平台服务说明](office-365-platform-service-description.md)。
