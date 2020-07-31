---
title: 域
ms.author: office365servicedesc
author: pamelaar
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
description: 当您添加域时，分步向导可帮助您添加用户并将电子邮件地址和其他服务转换为您的业务名称。 完成此向导后，你的业务电子邮件将转到 Microsoft，而不会转到你的当前电子邮件提供商。 若要了解详细信息，请参阅将用户和域添加到 Microsoft。 如果您使用由世纪互联运营的 Office 365，请参阅验证您的域。
ms.openlocfilehash: 109dd15af75c8e3e04406a63c8868e010c12b9c5
ms.sourcegitcommit: 6a9c3c47e7526de046787ad0f02b9c008e541c34
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/31/2020
ms.locfileid: "46531215"
---
# <a name="domains"></a>域

当您添加域时，分步向导可帮助您添加用户并将电子邮件地址和其他服务转换为您的业务名称。 完成此向导后，你的业务电子邮件将转到 Microsoft，而不会转到你的当前电子邮件提供商。 若要了解详细信息，请参阅[将用户和域添加到 Microsoft](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611)。 如果您使用由世纪互联运营的 Office 365，请参阅[验证您的域](https://docs.microsoft.com/office365/admin/setup/add-domain)。
  
## <a name="custom-domains"></a>自定义域

您可以向订阅（包括子域）中添加最多900个域。 您不能将域添加到已在另一个 Microsoft 云服务中使用的 Microsoft 365。 这意味着您不能将同一个域添加到多个订阅。 有关详细信息，请参阅[域 FAQ](https://support.office.com/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a)。
  
### <a name="second-and-third-level-domains"></a>第二级域和第三级域

使用 Office 365 企业版和 Microsoft 365 应用程序，可以添加任何级别的域，包括第三级域，如 marketing.contoso.com。 请参阅[将自定义子域或多个域添加到 Microsoft](https://docs.microsoft.com/office365/admin/setup/domains-faq)。 如果您使用的是由世纪互联运营的 Office 365，请参阅[将自定义子域或多个域添加到由世纪互联运营的 Office 365](https://docs.microsoft.com/office365/admin/setup/domains-faq)。
  
## <a name="domain-verification-and-managing-dns-records"></a>域验证和管理 DNS 记录

使用 Microsoft 365，可以在 DNS 托管提供程序中管理所有 DNS 记录，也可以选择让 Microsoft 为您设置和管理您的域的 DNS 记录。 如果你继续管理记录，则根据需要将特定记录更改为指向 Microsoft 服务。 有关我们为添加记录（包括用于每条记录的特定值）提供分步说明的域注册机构的列表，请参阅[CREATE DNS](https://docs.microsoft.com/office365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider) record; 如果使用由世纪互联运营的 office 365，请参阅在任何提供商处为由世纪互联运营的 Office 365 创建 dns 记录。 
  
如果 Microsoft 为你管理你的域的 DNS 记录，则首先必须将你的域的名称服务器记录切换为指向 Microsoft，然后 Microsoft 设置你的服务，然后在 Microsoft 对你的域的 DNS 记录进行管理。
  
如果您的域是在 GoDaddy 注册的，Microsoft 可以在 GoDaddy 为您创建所需的记录。 
  
无论 DNS 记录的托管位置如何，您都可以将 DNS 记录设置为将您的域用于 Microsoft 或其他托管提供商托管的公共网站的 URL。 
  
Microsoft 主动检查你的 DNS 记录，以查找并帮助解决 DNS 问题。 如果你的 DNS 记录不符合我们的预期，你将在 Microsoft 365 管理中心收到通知，以及告诉你如何修复已确定的可能问题的信息。
  
有关详细信息，请参阅[Microsoft 如何管理 dns 记录](https://docs.microsoft.com/office365/admin/setup/domains-faq)或（针对由世纪互联运营的 office 365）。[管理 dns 记录时，请参阅为 OFFICE 365 创建 DNS 记录](https://docs.microsoft.com/office365/admin/services-in-china/create-dns-records-when-you-manage-your-dns-records)。
  
## <a name="sharing-a-domain"></a>共享域

你可以在 Microsoft 上试用某个域的某些电子邮件地址，而在以前的电子邮件提供商处试用一些电子邮件地址。 建议仅在试验过程中使用此设置，因为这需要额外的设置步骤，并且对 Microsoft 服务有一些限制。 有关详细信息，请参阅：
  
- [试用 Microsoft 365 小型企业版](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [试用 Microsoft 365 大型企业版（使用 FastTrack）](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>功能可用性

若要查看跨 Microsoft 365 的功能可用性、商业计划、独立选项和本地解决方案，请参阅[microsoft 365 和 Office 365 platform service description](office-365-platform-service-description.md)。
  

