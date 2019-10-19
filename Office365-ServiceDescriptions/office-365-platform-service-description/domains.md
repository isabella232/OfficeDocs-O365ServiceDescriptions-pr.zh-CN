---
title: 域
ms.author: sharik
author: skjerland
manager: mnirkhe
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
description: 当您添加一个域时，分步向导可帮助您添加用户并将您的 Office 365 电子邮件地址和其他服务转换为您的公司名称。 完成该向导后，您的业务电子邮件将转到 Office 365，而不转到您当前的电子邮件提供商。 若要了解详细信息，请参阅将用户和域添加到 Office 365。 如果您使用由世纪互联运营的 Office 365，请参阅验证您的域。
ms.openlocfilehash: cc88aeb19573b089d06749df5ab6db5de4bbecfa
ms.sourcegitcommit: 3a3c964939acb72e4bac75b324d0cdc19c73d170
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/18/2019
ms.locfileid: "37595216"
---
# <a name="domains"></a>域

当您添加一个域时，分步向导可帮助您添加用户并将您的 Office 365 电子邮件地址和其他服务转换为您的公司名称。 完成该向导后，您的业务电子邮件将转到 Office 365，而不转到您当前的电子邮件提供商。 若要了解详细信息，请参阅[将用户和域添加到 Office 365](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611)。 如果您使用由世纪互联运营的 Office 365，请参阅[验证您的域](https://docs.microsoft.com/office365/admin/setup/add-domain)。
  
## <a name="custom-domains"></a>自定义域

最多可以将 900 个域添加到 Office 365 订阅中。 不过，无法将域添加到已在另一个 Microsoft 云服务中使用的 Office 365 中。 也就是说，无法将同一个域添加到多个 Office 365 订阅中。 有关详细信息，请参阅[域 FAQ](https://support.office.com/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a)。
  
### <a name="second-and-third-level-domains"></a>第二级域和第三级域

使用 Office 365 企业版 和 Office 365 商业版，可以添加任何级别的域，包括第三级域，如 marketing.contoso.com。请参阅[将自定义的子域或多个域添加到 Office 365](https://docs.microsoft.com/office365/admin/setup/domains-faq)。如果您使用的是由世纪互联运营的 Office 365，请参阅[将自定义子域或多个域添加到由世纪互联运营的 Office 365](https://docs.microsoft.com/office365/admin/setup/domains-faq)。
  
## <a name="domain-verification-and-managing-dns-records"></a>域验证和管理 DNS 记录

使用 Office 365，可以在 DNS 托管提供者处管理所有 DNS 记录，也可以选择设置 Office 365 并让其为你管理域 DNS 记录。如果继续管理记录，请根据需要将特定记录更改为指向 Office 365 服务。有关我们为其提供添加记录（包括用于每个记录的特定值）的分步操作说明的域注册机构列表，请参阅[为 Office 365 创建 DNS 记录](https://docs.microsoft.com/office365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider)。或者，如果使用的是由世纪互联运营的 Office 365，请参阅"在任何提供者处为由世纪互联运营的 Office 365 创建 DNS 记录"。 
  
如果 Office 365 为您管理您的域的 DNS 记录，您必须首先更改域的名称服务器记录以指向 Office 365，然后 Office 365 会设置您的 Office 365 服务，然后您的域的 DNS 记录会在 Office 365 上进行管理。
  
如果您的域是在 GoDaddy 中注册，Office 365 可以在 GoDaddy 上为您创建所需的记录。 
  
无论您将 DNS 记录托管在何处，您都可以设置 DNS 记录将您的域用于托管在 Office 365 或不同宿主提供商的公共网站的 URL。 
  
Office 365 预先检查您的 DNS 记录以查找并帮助解决 DNS 问题。 如果你的 DNS 记录不符合我们的预期，你将在 Microsoft 365 管理中心收到通知，以及告诉你如何修复已确定的可能问题的信息。
  
有关详细信息，请参阅 [Office 365 如何管理 DNS 记录](https://docs.microsoft.com/office365/admin/setup/domains-faq)。或者，对于由世纪互联运营的 Office 365，请参阅[管理 DNS 记录时为 Office 365 创建 DNS 记录](https://docs.microsoft.com/office365/admin/services-in-china/create-dns-records-when-you-manage-your-dns-records)。
  
## <a name="sharing-a-domain"></a>共享域

您可以试用 Office 365，将某个域的一些电子邮件地址放在 Office 365 上，另一些放在以前的电子邮件提供商处。 建议仅在运行 Office 365 的过程中使用此方法，因为这需要额外的安装步骤，并且对 Office 365 服务有一些限制。 有关详细信息，请参阅：
  
- [试用 Office 365 小型企业版](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [试用 Office 365 大型企业版（使用 FastTrack）](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>功能可用性

若要查看跨 Office 365 计划、独立选项和本地解决方案的功能可用性，请参阅[office 365 Platform Service Description](office-365-platform-service-description.md)。
  

