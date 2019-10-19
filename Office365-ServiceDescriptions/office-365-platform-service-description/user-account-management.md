---
title: 用户帐户管理
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-user-account-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: e7616079-5b13-4f1c-99ed-b20174e0808d
description: Microsoft Office 365 支持以下用于创建、管理和对用户进行身份验证的方法。
ms.openlocfilehash: f51e06e64722b5db8820a4f164beca0997796a4b
ms.sourcegitcommit: 19591e97b35c1b2a99e04a496d83af27dc6530d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/18/2019
ms.locfileid: "37582168"
---
# <a name="user-account-management"></a>用户帐户管理

Microsoft Office 365 支持以下用于创建、管理和对用户进行身份验证的方法。 
  
> [!NOTE]
> 本主题不包含有关允许或禁止访问单个 Office 365 资源的安全性功能的信息（例如，Microsoft Exchange Online 的基于角色的访问控制或配置 Microsoft SharePoint Online 的安全性）。有关这些功能的详细信息，请参阅 [Exchange Online 服务说明](../exchange-online-service-description/exchange-online-service-description.md)和 [SharePoint Online 服务说明](../sharepoint-online-service-description/sharepoint-online-service-description.md)。 
  
如果需要有关可以帮助你执行管理任务的工具的信息，请参阅 [Tools to manage Office 365 accounts](https://docs.microsoft.com/office365/enterprise/manage-office-365-accounts)（用于管理 Office 365 帐户的工具）。要了解如何执行日常管理任务，请参阅 [Common management tasks for Office 365](https://docs.microsoft.com/office365/admin/manage/manage)（Office 365 的常见管理任务）。
  
## <a name="need-help-signing-in-installing-or-uninstalling-or-canceling-your-subscription"></a>需要获取有关登录、安装/卸载或取消订阅方面的帮助吗？

Get help with [signing into Office 365](https://support.office.com/article/where-to-sign-in-to-office-365-for-business-e9eb7d51-5430-4929-91ab-6157c5a050b4) | [Installing or uninstalling Office](https://support.office.com/article/download-and-install-or-reinstall-office-365-or-office-2019-on-a-pc-or-mac-4414eaaf-0478-48be-9c42-23adc4716658) | [Canceling Office 365](https://support.office.com/article/Cancel-Office-365-for-business-b1bc0bef-4608-4601-813a-cdd9f746709a)
  
如果对 Office 365 有其他问题，请访问 [Microsoft 支持中心](https://support.microsoft.com/contactus/)。若要获取由中国的世纪互联运营的 Office 365 的支持，请联系[世纪互联支持团队](https://support.office.com/article/Get-technical-billing-and-subscription-support-for-Office-365-operated-by-21Vianet-671FB12E-F5D8-4CDF-B3E9-E8068A9AA496)。对于 Office 365 Germany，请联系 [Office 365 Germany 支持团队](https://support.office.com/article/Get-technical-and-billing-support-for-Office-365-Germany-83ef2266-2543-48d7-a41a-1b56b403a8e9?ui=en-US&amp;rs=en-US&amp;ad=US&amp;fromAR=1)。 
  
## <a name="sign-in-options"></a>登录选项

Office 365 具有两个可用于用户标识的系统：
  
- **工作或学校帐户（云身份）** 用户将收到 Azure Active Directory 云凭据独立于其他桌面或企业凭据以用于登录 Office 365 和其他 Microsoft 云服务。这是默认标识，推荐使用此标识以最大限度地减少部署的复杂度。工作或学校的帐户密码使用 Azure Active Directory [密码策略](https://docs.microsoft.com/previous-versions/azure/jj943764(v=azure.100))。
    
- **联合帐户（联合身份）** 对于具有本地 Active Directory 且使用单一登录 (SSO) 的组织中的所有订阅，用户可以使用他们的 Active Directory 凭据登录 Office 365 服务。公司 Active Directory 将存储和控制密码策略。若要了解 SSO，请参阅 [单一登录路线图](https://docs.microsoft.com/previous-versions/azure/azure-services/hh967643(v=azure.100))。
    
身份类型将影响用户体验和用户账户管理选项，以及硬件和软件要求和其他部署考虑。
  
### <a name="custom-domains-and-identity-options"></a>自定义域和身份选项

当您创建新用户时，用户的登录名和电子邮件地址将被分配给 Microsoft 365 管理中心中设置的默认域。 若要了解详细信息，请参阅[将用户和域添加到 Office 365](https://support.office.com/article/Add-your-users-and-domain-to-Office-365-6383f56d-3d09-4dcb-9b41-b5f5a5efd611)。 
  
默认情况下，Office 365 订阅使用通过此帐户创建的 \< _company name_\> **.onmicrosoft.com**域。\*你可以添加一个或多个自定义域给 Office 365，而不是保留 onmicrosoft.com 域，并可以分配用户以使用任何经过验证的域登录。每个用户的分配域是出现在已发送和已接收电子邮件消息中的电子邮件地址。 
  
您可以在 Office 365 中托管多达900个注册的 internet 域，每个域都由不同的命名空间表示。 
  
对于使用单点登录的组织，同一域中的所有用户都必须使用相同的身份系统：云身份或联合身份。 例如，您的一个用户组可以仅需要一个云身份，因为他们无需访问内部部署系统，同时另一个用户组使用 Office 365 和内部部署系统。 将两个域添加到 Office 365，如 contractors.contoso.com 和 staff.contoso.com，并且只为其中一个域设置 SSO。 整个域可以从云身份转换为联合身份，也可以从联合身份转换为云身份。
  
有关 Office 365 中的域的详细信息，请参阅[域](domains.md)服务说明。 
  
\* 如果你使用的是由中国世纪互联运营的 Office 365，则默认域是 \<companyname\> **.onmsChina.cn**。如果你使用的是 Office 365 Germany，则默认域是 \<companyname\> **.onmicrosoft.de**
  
## <a name="authentication"></a>身份验证

除了使用 SharePoint Online 创建的匿名访问的互联网站点之外，用户在访问 Office 365 服务时必须进行身份验证。 
  
- **新式验证**新式验证将基于 Active Directory Authentication Library (ADAL) 的登录引入跨平台的 Office 客户端应用。这将启用部分登录功能，如 Multi-Factor Authentication (MFA)、使用 Office 客户端应用程序的基于 SAML 的第三方身份提供程序，以及智能卡和基于证书的身份验证。它还让 Microsoft Outlook 无需使用基本身份验证协议。有关详细信息，包括跨 Office 应用程序的新式验证的可用性等，请参阅[新式验证在 Office 2013 和 Office 2016 客户端应用中的工作原理](https://docs.microsoft.com/office365/enterprise/modern-auth-for-office-2013-and-2016)和[在 Office 客户端中使用 Office 365 新式验证](https://docs.microsoft.com/office365/enterprise/modern-auth-for-office-2013-and-2016)。
    
    默认情况下，Exchange Online 未启用新式验证。若要了解如何启用，请参阅[为 Exchange Online 启用新式验证](https://docs.microsoft.com/Exchange/clients-and-mobile-in-exchange-online/enable-or-disable-modern-authentication-in-exchange-online)。
    
- **云身份身份验证** 具有云身份的用户将使用传统挑战/回复进行身份验证。Web 浏览器被重定向到 Office 365 登录服务，您需要键入工作或学校帐户的用户名和密码。登录服务将对您的凭据进行身份验证并生成服务令牌，以便 Web 浏览器发送到请求的服务并登录。 
    
- **联合身份验证** 具有联合身份的用户将使用 Active Directory 联合身份验证服务 (AD FS) 2.0 或其他安全令牌服务进行身份验证。Web 浏览器重定向到 Office 365 登录服务，以便你可以在窗体中键入公司 ID 和用户主体名称（UPN；例如，isabel@contoso.com）。登录服务会确定你是否属于联盟域，并建议将你重定向到本地联合服务器进行身份验证。如果已登录桌面（域加入），则已经过身份验证（使用 Kerberos 或 NTLMv2），同时本地安全令牌服务会生成登录令牌，Web 浏览器会发布给 Office 365 登录服务。使用登录令牌，登录服务会生成 Web 浏览器发布给请求的服务的服务令牌，并将你登入。有关可用安全令牌服务的列表，请参阅 [单一登录路线图](https://docs.microsoft.com/previous-versions/azure/azure-services/hh967643(v=azure.100))。
    
Office 365 使用基于表单的身份验证，同时始终使用端口 443 以 TLS/SSL 加密通过网络的身份验证流量。身份验证流量占用 Office 365 服务的可以忽略的带宽百分比。 
  
### <a name="multi-factor-authentication-for-office-365"></a>适用于 Office 365 的 Multi-Factor Authentication

对于 Office 365 的多重身份验证，用户在正确输入密码后需要确认电话呼叫、短信或智能手机上的应用通知。 只有经过这第二次身份验证后，用户才可以登录。 Office 365 管理员可以在 Microsoft 365 管理中心内为用户注册多重身份验证。 详细了解 [Office 365 多重身份验证](https://docs.microsoft.com/office365/admin/security-and-compliance/set-up-multi-factor-authentication)。
  
### <a name="rich-client-authentication"></a>富客户端身份验证

对于 Microsoft Office 桌面应用程序等丰富客户端，身份验证以两种方式进行：
  
- **Microsoft Online Services 登录助手** Office 365 桌面安装程序 安装的 登录助手 包含客户端服务，其中包括来自 Office 365 登录服务的客户端服务，并返回富客户端。 
    
  - 如果拥有云身份，则将收到凭据提示。客户端服务需要发送该凭据给 Office 365 登录服务进行身份验证（使用 WS-Trust）。
    
  - 如果拥有联合身份，客户端服务将首先与 AD FS 2.0 服务器联系，以对凭据进行身份验证（使用 Kerberos 或 NTLMv2），并获得要发送给 Office 365 登录服务的登录令牌（使用 WS-Federation 和 WS-Trust）。
    
- **通过 SSL 的基本/代理身份验证** Outlook 客户端通过 SSL 将基本身份验证凭据传递给 Exchange Online。Exchange Online 将身份验证请求代理至 Office 365 标识平台，然后代理至本地 Active Directory 联合服务器（用于 SSO）。 
    
为了确保正确发现和验证 Office 365 服务，管理员必须向每个使用富客户端（如 Microsoft Office 2010）并连接到 Office 365 的工作站应用一套组件和更新程序。Office 365 桌面设置是使用所需更新程序配置工作站的自动工具。有关详细信息，请参阅 [Use my current Office desktop apps with Office 365](https://support.office.com/article/set-up-office-2010-desktop-programs-to-work-with-office-365-for-business-3324b8b8-dceb-45e2-ac24-c642720108f7?ocmsassetID=HA102817827&CorrelationId=8eb1b198-827a-4999-a584-05a05a92d224&ui=en-US&rs=en-US&ad=US)（结合使用最新 Office 桌面应用与 Office 365）。
  
### <a name="sign-in-experience"></a>登录体验

登录体验变化取决于使用的 Office 365 身份类型：
  
||**云身份**|**联合身份**|
|:-----|:-----|:-----|
|Outlook 2016  <br/> |每次会话登录 <sup>1</sup> <br/> |每次会话登录 <sup>2</sup> <br/> |
|Outlook 2013  <br/> |每次会话登录 <sup>1</sup> <br/> |每次会话登录 <sup>2</sup> <br/> |
|Windows 7 上的 Outlook 2010 或 Office 2007。  <br/> |每次会话登录 <sup>1</sup> <br/> |每次会话登录 <sup>2</sup> <br/> |
|Windows Vista 上的 Outlook 2010 或 Office Outlook 2007。  <br/> |每次会话登录 <sup>1</sup> <br/> |每次会话登录 <sup>2</sup> <br/> |
|Microsoft Exchange ActiveSync  <br/> |每次会话登录 <sup>1</sup> <br/> |每次会话登录 <sup>2</sup> <br/> |
|POP、IMAP、Outlook for Mac  <br/> |每次会话登录 <sup>1</sup> <br/> |每次会话登录 <sup>2</sup> <br/> |
|Web 体验：适用于 web 的 Office 365 portal/Outlook Web App/SharePoint Online/Office  <br/> |每次浏览器会话登录 <sup>4</sup> <br/> |每次会话登录 <sup>3</sup> <br/> |
|使用 SharePoint Online 的 Office 2010 或 Office 2007。  <br/> |每次 SharePoint Online 会话登录 <sup>4</sup> <br/> |每次 SharePoint Online 会话登录 <sup>3</sup> <br/> |
|Skype for Business Online  <br/> |每次会话登录 <sup>1</sup> <br/> |无提示  <br/> |
|Outlook for Mac  <br/> |每次会话登录 <sup>1</sup> <br/> |每次会话登录 <sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup>当首次收到提示时，您可以保存密码以供将来使用。 在更改密码之前，你将不会收到另一个提示。 <br/> 
<sup>2</sup>输入公司凭据。 你可以保存密码，并且在更改密码之前不会再次提示你。 <br/> 
<sup>3</sup>所有应用程序都要求你输入或选择你的用户名以登录。 如果你的计算机已加入域，将不会提示你输入密码。 如果选择 **"使我保持登录状态"** ，则在您注销之前不会再次提示您。 <br/> 
<sup>4</sup>如果选择 **"使我保持登录状态"** ，则在您注销之前不会再次提示。 
  
## <a name="creating-user-accounts"></a>创建用户帐户

有多种方法可以将用户添加到 Office 365。 若要了解详细信息，请参阅[在 Microsoft 365 管理中心预览版中](https://support.office.com/article/add-remove-and-manage-users-in-the-new-office-365-admin-center-6e80db58-c36b-4add-b1c8-cc5135f111f3?amp%3Bclcid=0x409&ui=en-US&rs=en-US&ad=US)[单独或批量添加用户到 Office 365-管理员帮助](https://docs.microsoft.com/office365/admin/add-users/add-users)和添加、删除和管理用户。 如果使用的是由世纪互联在中国运营的 Office 365，请参阅[在由世纪互联运营的 Office 365 中创建或编辑用户帐户 - 管理帮助](https://docs.microsoft.com/office365/admin/add-users/add-users)。
  
## <a name="deleting-accounts"></a>删除帐户

如何删除账户取决于是否正在使用目录同步。 
  
- 如果未使用目录同步，则可以使用 Office 365 管理页面或使用 Windows PowerShell 删除账户。
    
- 如果正在使用目录同步，您必须从本地 Active Directory 而不是 Office 365 删除用户。
    
帐户删除后，它将变为非活动状态。 若要在删除后大约30天，可以还原帐户。 若要详细了解如何删除和还原帐户，请参阅[在 office 365 中删除用户](https://docs.microsoft.com/office365/admin/add-users/delete-a-user)和[在 Office 365 中还原用户](https://docs.microsoft.com/office365/admin/add-users/restore-user)或者，如果在中国使用由世纪互联运营的 office 365，请参阅[在 office 365 中创建或编辑用户帐户世纪互联-管理员帮助](https://docs.microsoft.com/office365/admin/add-users/add-users)。
  
## <a name="password-management"></a>密码管理

密码管理策略和程序取决于身份系统。
  
 **云身份密码管理：**
  
当使用云身份时，将在创建账户时自动生成密码。
  
- 有关云身份密码强度要求的信息，请参阅[密码策略](https://docs.microsoft.com/previous-versions/azure/jj943764(v=azure.100))。
    
- 为提高安全性，用户在首次访问 Office 365 服务时必须更改密码。由此，在用户能够访问 Office 365 服务之前，他们必须登录 Office 365 门户，其中将提示他们更改密码。
    
- 管理员可以设置密码过期策略。 有关详细信息，请参阅[设置用户的密码过期策略](https://docs.microsoft.com/office365/admin/manage/set-password-expiration-policy)。
    
可通过以下几个工具为拥有云身份的用户重置密码：
  
- **管理员重置密码** 如果用户丢失或忘记密码，管理员可以在 Office 365 门户或使用 Windows PowerShell 重置用户密码。只有在知道自己现有密码的情况下，用户才能更改密码。 
    
    对于企业计划，如果管理员丢失或忘记了密码，则具有全局管理员角色的不同管理员可以在 Microsoft 365 管理中心或使用 Windows PowerShell 重置管理员密码。 有关详细信息，请参阅[重置管理员密码](https://docs.microsoft.com/office365/admin/add-users/reset-passwords)。 如果使用的是由世纪互联在中国运营的 Office 365，请参阅[在由世纪互联运营的 Office 365 中更改或重置密码](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b)。
    
- **用户使用 Outlook Web App 更改密码** Outlook Web App 选项页面中包含"更改密码"超链接，可将用户重定向到" **更改密码**"页面。用户必须知道旧密码。有关详细信息，请参阅[更改密码](https://support.office.com/article/change-password-in-outlook-web-app-50bb1309-6f53-4c24-8bfd-ed24ca9e872c)。如果使用的是由世纪互联在中国运营的 Office 365，请参阅[在由世纪互联运营的 Office 365 中更改或重置密码](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b)。
    
- **基于角色的重置密码权限** 对于企业版计划，可以向支持人员等授权用户分配" **重置密码**"用户权限，以及使用 Office 365 预定义或自定义角色更改密码的权限，而不必成为拥有完全管理权限的管理员。 默认情况下，在企业版计划中，具有"全局管理员"、"密码管理员"或"用户管理管理员"角色的管理员可以更改密码。 有关详细信息，请参阅[分配管理员角色](https://docs.microsoft.com/office365/admin/add-users/assign-admin-roles)。
    
- **"使用 Windows PowerShell 重置密码"** 服务管理员可以使用 Windows PowerShell 重置密码。 
    
 **联合身份密码管理：**
  
当使用联合身份时，密码将在 Active Directory 中管理。 本地安全令牌服务将身份验证与 Office 365 联合网关协商，而无需通过 internet 将用户的本地 Active Directory 密码传递到 Office 365。 使用本地密码策略，或针对 Web 客户端进行双因素身份验证。 Outlook Web App 中不包含"更改密码"超链接。 用户可以使用标准、内部部署工具或通过他们的桌面 PC 登录选项更改密码。
  
如果你在 Office 365 环境中启用了[使用单一登录 (SSO) 的目录同步](https://docs.microsoft.com/previous-versions/azure/azure-services/dn441213(v=azure.100))，并且存在影响联合身份提供程序的中断，可使用联合登录的密码同步备份，手动将域切换为密码同步。使用密码同步，你的用户可以在修复中断期间访问 Office 365。了解 [How To Switch From Single Sign-On To Password Sync](https://go.microsoft.com/fwlink/p/?LinkId=509832)（如何从单一登录切换为密码同步）。
  
## <a name="license-management"></a>许可证管理

用户可通过 Office 365 许可证访问一组 Office 365 服务。对于需要访问权限的服务，管理员可以向每位用户分配许可证。例如，您可以向用户分配 Skype for Business Online（而不是 SharePoint Online）的访问权限。
  
Office 365 帐务管理员可以更改订阅详细信息，如用户许可证数量和公司使用的附加服务数量。请参阅 [Assign or remove a license in Office 365](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users)（在 Office 365 中分配或删除许可证）。如果使用的是由世纪互联运营的 Office 365，请参阅[在由世纪互联运营的 Office 365 中分配或删除许可证](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users)。
  
## <a name="group-management"></a>组管理

在 SharePoint Online 中使用安全组以控制对站点的访问权限。 可以在 Microsoft 365 管理中心中创建安全组。 有关安全组的详细信息，请参阅[创建、编辑或删除安全组](https://docs.microsoft.com/office365/admin/email/create-edit-or-delete-a-security-group)。
  
## <a name="administrator-roles"></a>管理员角色

Office 365 企业版采用基于角色的访问控制 (RBAC) 模型：权限和功能由管理角色定义。 为其组织注册 Office 365 的用户自动成为全局管理员或顶级管理员。 有五种管理员角色：全局管理员、帐务管理员、密码管理员、服务管理员和用户管理管理员。 若要详细了解 Office 365 企业版中的管理员角色（包括如何将这些角色应用于 Exchange Online、SharePoint Online 和 Skype for Business Online 管理），请参阅[分配管理员角色](https://docs.microsoft.com/previous-versions/windows/it-pro/windows-server-2012-R2-and-2012/jj878348(v=ws.11))。 如果您在中国使用由世纪互联运营的 Office 365，请参阅[在 Office 365 for business 中分配管理员角色](https://docs.microsoft.com/office365/admin/add-users/assign-admin-roles)。
  
## <a name="delegated-administration-and-support-for-partners"></a>合作伙伴的委派管理和支持

可以授权合作伙伴代表客户管理帐户。 当授予委派管理权限时，客户既不需要提供用户帐户给合作伙伴，也不需要使用 Office 365 许可证。 合作伙伴可以向其组织内的用户分配完整或受限访问权限。 受限访问权限包括重置密码、管理服务请求和监视服务运行状况。 
  
> [!NOTE]
> 将合作伙伴用作或指定为委派管理员的功能因地区而异。 
  
## <a name="azure-active-directory-services"></a>Azure Active Directory 服务

Azure Active Directory (AD) 将身份和访问管理综合功能引入 Office 365。不仅整合了目录服务、高级身份管理、应用程序访问管理，并为开发者提供了一个基于标准的丰富平台。若要详细了解 Office 365 中的 AD 功能，请参阅 [Sign in page branding and cloud user self-service password reset](https://blogs.office.com/2015/02/17/sign-page-branding-cloud-user-self-service-password-reset-office-365/)（登录页品牌塑造和云用户自助服务密码重置）。详细了解 [Free, Basic, and Premium editions of Azure Active Directory](https://msdn.microsoft.com/library/azure/dn532272.aspx)（Azure Active Directory 免费版、基本版和高级版）。 
  
## <a name="feature-availability"></a>功能可用性

若要查看跨 Office 365 计划、独立选项和本地解决方案的功能可用性，请参阅[office 365 Platform Service Description](office-365-platform-service-description.md)。
  
