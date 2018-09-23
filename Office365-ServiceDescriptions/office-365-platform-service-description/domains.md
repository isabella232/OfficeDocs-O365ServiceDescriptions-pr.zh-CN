---
title: 域
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/10/2017
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-domains
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 5c374309-8016-4f18-8f2a-bceeb863ca67
description: 当您添加域时，分步向导可帮助您添加用户并将您的 Office 365 电子邮件地址和其他服务转换为您的业务名称。完成向导后，您的业务电子邮件启动变成 Office 365，而不转到当前电子邮件提供商。若要了解详细信息，请参阅将您的用户和域添加到 Office 365。如果您使用 Office 365 由 21Vianet 操作，请参阅 Verify 您的域。
ms.openlocfilehash: 47c378482b8a8d09e2f2516968af99af9472c641
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035039"
---
# <a name="domains"></a>域

当您添加域时，分步向导可帮助您添加用户并将您的 Office 365 电子邮件地址和其他服务转换为您的业务名称。完成向导后，您的业务电子邮件启动变成 Office 365，而不转到当前电子邮件提供商。若要了解详细信息，请参阅[您的用户和域到 Office 365 中添加](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611)。如果您使用 Office 365 由 21Vianet 操作，请参阅[Verify 您的域](http://go.microsoft.com/fwlink/?LinkID=733344&amp;clcid=0x409)。
  
## <a name="custom-domains"></a>自定义域
<a name="BKMK_CustomDomains"> </a>

您可以向 Office 365 订阅中添加多达 900 个域。但是，不能向您已经在另一个 Microsoft 云服务中使用的 Office 365 添加域。这意味着，不能将同一个域添加到多个 Office 365 订阅。有关详细信息，请参阅[域常见问题](https://support.office.com/en-us/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a)。
  
### <a name="second-and-third-level-domains"></a>第二级域和第三级域
<a name="BKMK_SecondAndThirdLevelDomains"> </a>

使用 Office 365 企业版 和 Office 365 商业版，可以添加任何级别的域，包括第三级域，如 marketing.contoso.com。请参阅[将自定义的子域或多个域添加到 Office 365](http://go.microsoft.com/fwlink/?LinkID=733345&amp;clcid=0x409)。如果您使用的是由世纪互联运营的 Office 365，请参阅[将自定义子域或多个域添加到由世纪互联运营的 Office 365](http://go.microsoft.com/fwlink/?LinkID=733346&amp;clcid=0x409)。
  
## <a name="domain-verification-and-managing-dns-records"></a>域验证和管理 DNS 记录
<a name="BKMK_ManagingDNSRecords"> </a>

使用 Office 365，可以在 DNS 托管提供者处管理所有 DNS 记录，也可以选择设置 Office 365 并让其为你管理域 DNS 记录。如果继续管理记录，请根据需要将特定记录更改为指向 Office 365 服务。有关我们为其提供添加记录（包括用于每个记录的特定值）的分步操作说明的域注册机构列表，请参阅[为 Office 365 创建 DNS 记录](https://go.microsoft.com/fwlink/p/?LinkID=270173)。或者，如果使用的是由世纪互联运营的 Office 365，请参阅"在任何提供者处为由世纪互联运营的 Office 365 创建 DNS 记录"。 
  
如果 Office 365 为您管理您的域的 DNS 记录，您必须首先更改域的名称服务器记录以指向 Office 365，然后 Office 365 会设置您的 Office 365 服务，然后您的域的 DNS 记录会在 Office 365 上进行管理。
  
如果您的域是在 GoDaddy 中注册，Office 365 可以在 GoDaddy 上为您创建所需的记录。 
  
无论您将 DNS 记录托管在何处，您都可以设置 DNS 记录将您的域用于托管在 Office 365 或不同宿主提供商的公共网站的 URL。 
  
Office 365 预先检查您的 DNS 记录以查找并帮助解决 DNS 问题。如果您的 DNS 记录与我们预期的不符，您将在 Office 365 管理中心收到一个通知，并附有告诉您如何解决已识别的可能问题的信息。
  
有关详细信息，请参阅 [Office 365 如何管理 DNS 记录](https://go.microsoft.com/fwlink/p/?LinkID=270144)。或者，对于由世纪互联运营的 Office 365，请参阅[管理 DNS 记录时为 Office 365 创建 DNS 记录](http://go.microsoft.com/fwlink/?LinkID=817326&amp;clcid=0x409)。
  
## <a name="sharing-a-domain"></a>共享域
<a name="BKMK_ManagingDNSRecords"> </a>

您可以与 Office 365 上域某些电子邮件地址和一些您以前的电子邮件提供商在试用 Office 365。这被建议仅供使用的 Office 365 试生产期间因为它需要额外的安装步骤，并有一些限制 for Office 365 服务。有关详细信息，请参阅：
  
- [试用 Office 365 小型企业版](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [试用 Office 365 大型企业版（使用 FastTrack）](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>功能可用性
<a name="BKMK_ManagingDNSRecords"> </a>

若要查看整个 Office 365 计划、独立选项和本地解决方案的功能可用性，请参阅 [Office 365 平台服务说明](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx)。
  

