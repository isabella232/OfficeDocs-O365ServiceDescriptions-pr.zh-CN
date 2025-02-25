---
title: User account management
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-user-account-management
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: e7616079-5b13-4f1c-99ed-b20174e0808d
description: Microsoft 支持以下用于创建、管理和验证用户的方法。
ms.openlocfilehash: 914b88ba0e4d003d2df2bda362a8169f41029c01
ms.sourcegitcommit: 4b02d2d928d24a68ff7b0e1c4c5a1bde056ef69c
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/13/2022
ms.locfileid: "64819797"
---
# <a name="user-account-management"></a>User account management

Microsoft 支持以下用于创建、管理和验证用户的方法。 
  
> [!NOTE]
> 本主题不包括有关允许或禁止访问单个 Microsoft 资源的安全功能的信息 (例如，Microsoft Exchange Online中基于角色的访问控制或在Microsoft Office SharePoint Online) 中配置安全性。 有关这些功能的详细信息，请参阅[Exchange Online服务说明](../exchange-online-service-description/exchange-online-service-description.md)和 [SharePoint Online 服务说明](../sharepoint-online-service-description/sharepoint-online-service-description.md)。 
  
如果需要有关可帮助你执行管理任务的工具的信息，请参阅 [用于管理 Microsoft 帐户的工具](/office365/enterprise/manage-office-365-accounts)。 若要了解如何执行日常管理任务，请参阅 [常见管理任务](/office365/admin/manage/manage)。
  
## <a name="need-help-with-signing-in-installing-or-uninstalling-or-canceling-your-subscription"></a>需要有关登录、安装或卸载或取消订阅的帮助？

获取帮助：[登录 InInstalling](https://support.office.com/article/where-to-sign-in-to-office-365-for-business-e9eb7d51-5430-4929-91ab-6157c5a050b4) |  [或卸载Office](https://support.office.com/article/download-and-install-or-reinstall-office-365-or-office-2019-on-a-pc-or-mac-4414eaaf-0478-48be-9c42-23adc4716658) | [注册Office 365](https://support.office.com/article/Cancel-Office-365-for-business-b1bc0bef-4608-4601-813a-cdd9f746709a)
  
有关其他问题，请访问 [Microsoft 支持中心](https://support.microsoft.com/contactus/)。 若要获取由中国的世纪互联运营的 Office 365 的支持，请联系[世纪互联支持团队](https://support.office.com/article/Get-technical-billing-and-subscription-support-for-Office-365-operated-by-21Vianet-671FB12E-F5D8-4CDF-B3E9-E8068A9AA496)。
  
## <a name="sign-in-options"></a>登录选项

Microsoft 有两个可用于用户标识的系统：
  
- **工作或学校帐户 (云标识)** - 用户接收Azure Active Directory云凭据（独立于其他桌面或公司凭据）以登录到 Microsoft 云服务。 这是默认标识，推荐使用此标识以最大限度地减少部署的复杂度。 工作或学校的帐户密码使用 Azure Active Directory [密码策略](/previous-versions/azure/jj943764(v=azure.100))。
    
- **联合帐户 (联合标识)** - 对于具有使用单一登录 (SSO) 的本地 Active Directory组织中的所有订阅，用户可以使用其 Active Directory 凭据登录到Microsoft 服务。 公司 Active Directory 将存储和控制密码策略。 若要了解 SSO，请参阅 [单一登录路线图](/previous-versions/azure/azure-services/hh967643(v=azure.100))。
    
身份类型将影响用户体验和用户账户管理选项，以及硬件和软件要求和其他部署考虑。
  
### <a name="custom-domains-and-identity-options"></a>自定义域和身份选项

创建新用户时，用户的登录名称和电子邮件地址将按照Microsoft 365 管理中心中的设置分配到默认域。 若要了解详细信息，请参阅 [“添加用户和域](https://support.office.com/article/Add-your-users-and-domain-to-Office-365-6383f56d-3d09-4dcb-9b41-b5f5a5efd611)”。 
  
默认情况下，订阅使用使用帐户创建的<*公司名称*>**.onmicrosoft.com** 域。 如果在中国使用由 21Vianet 运营的Office 365，则默认域<*companyname.onmsChina.cn*>。 可以将一个或多个自定义域添加到 Microsoft，而不是保留 **onmicrosoft.com** 域，并可以分配用户以使用任何已验证的域登录。 每个用户分配的域是将显示在发送和接收的电子邮件上的电子邮件地址。
  
最多可以托管 900 个已注册的 Internet 域，每个域都由不同的命名空间表示。 
  
对于使用单点登录的组织，同一域中的所有用户都必须使用相同的身份系统：云身份或联合身份。 例如，可以拥有一组仅需要云标识的用户，因为他们无法访问本地系统，另一组用户使用 Microsoft 和本地系统。 你将向Office 365添加两个域，例如 **contractors.contoso.com** 和 **staff.contoso.com**，并且只为其中一个域设置 SSO。 整个域可以从云身份转换为联合身份，也可以从联合身份转换为云身份。
  
有关 Office 365 中的域的详细信息，请参阅[域](domains.md)服务说明。 
  
## <a name="authentication"></a>身份验证

除了使用 SharePoint Online 创建匿名访问的 Internet 站点外，访问Microsoft 服务时必须对用户进行身份验证。 
  
- **新式身份验证** - 新式身份验证使基于 Microsoft 身份验证库的登录能够跨平台Office客户端应用。 这将启用部分登录功能，如 Multi-Factor Authentication (MFA)、使用 Office 客户端应用程序的基于 SAML 的第三方身份提供程序，以及智能卡和基于证书的身份验证。 它还让 Microsoft Outlook 无需使用基本身份验证协议。 有关详细信息，包括跨Office应用程序提供新式身份验证，请参阅[新式身份验证如何适用于 Office 2013 和 Office 2016 客户端应用](/office365/enterprise/modern-auth-for-office-2013-and-2016)。
    
    默认情况下，为Exchange Online启用新式身份验证。 若要了解如何打开或关闭它，请参阅[Exchange Online中启用新式身份验证](/exchange/clients-and-mobile-in-exchange-online/enable-or-disable-modern-authentication-in-exchange-online)。
    
- **云标识身份验证** - 具有云标识的用户使用传统的质询/响应进行身份验证。 Web 浏览器重定向到 Microsoft 登录服务，在该服务中键入工作或学校帐户的用户名和密码。 登录服务将对您的凭据进行身份验证并生成服务令牌，以便 Web 浏览器发送到请求的服务并登录。 
    
- **联合标识身份验证** - 具有联合标识的用户使用 Active Directory 联合身份验证服务 (AD FS) 2.0 或其他安全令牌服务进行身份验证。 Web 浏览器重定向到 Microsoft 登录服务，在该服务中，以用户主体名称 (UPN) 的形式键入公司 ID，例如： *isabel@contoso.com*。 登录服务会确定你是否属于联盟域，并建议将你重定向到本地联合服务器进行身份验证。 如果登录到已加入桌面 (域) ，则使用 Kerberos 或 NTLMv2)  (进行身份验证，并且本地安全令牌服务将生成登录令牌，Web 浏览器会将该令牌发布到 Microsoft 登录服务。 使用登录令牌，登录服务会生成 Web 浏览器发布给请求的服务的服务令牌，并将你登入。 有关可用安全令牌服务的列表，请参阅 [单一登录路线图](/previous-versions/azure/azure-services/hh967643(v=azure.100))。
    
Microsoft 使用基于表单的身份验证，并且通过网络进行的身份验证流量始终使用端口 443 通过 TLS/SSL 进行加密。 身份验证流量对Microsoft 服务使用可忽略不计的带宽百分比。 
  
### <a name="multi-factor-authentication"></a>多重身份验证

通过多重身份验证，用户在正确输入密码后，必须在智能手机上确认电话呼叫、短信或应用通知。 只有经过这第二次身份验证后，用户才可以登录。 Microsoft 管理员可以在Microsoft 365 管理中心中注册用户进行多重身份验证。 详细了解 [多重身份验证](/office365/admin/security-and-compliance/set-up-multi-factor-authentication)。
  
### <a name="rich-client-authentication"></a>富客户端身份验证

对于 Microsoft Office 桌面应用程序等丰富客户端，身份验证以两种方式进行：
  
- **Microsoft Online Services Sign-In助手** - 由桌面安装程序安装的登录助手包含一个客户端服务，该服务从登录服务获取服务令牌并将其返回给富客户端。 
    
  - 如果有云标识，则会收到凭据提示，客户端服务将凭据发送到登录服务，以便使用 WS-Trust) 进行身份验证 (。
    
  - 如果有联合标识，则客户端服务首先与 AD FS 2.0 服务器联系，以使用 Kerberos 或 NTLMv2) 对凭据 (进行身份验证，并获取使用 WS-Federation 和 WS-Trust) 发送到登录服务 (的登录令牌。
    
- **通过 SSL 进行基本/代理身份验证** - Outlook客户端通过 SSL 将基本的身份验证凭据传递给Exchange Online。 Exchange Online将身份验证请求代理到标识平台，然后本地 Active Directory联合服务器 (用于 SSO) 。 
    
为了确保正确发现和身份验证Microsoft 服务，管理员必须对每个工作站应用一组组件和更新，这些工作站使用丰富的客户端 (（如 Microsoft Office 2010) 和连接到Office 365）。 桌面设置是一种自动化工具，用于使用所需的更新配置工作站。 有关详细信息，请参阅[“使用我当前Office桌面应用](https://support.office.com/article/3324b8b8-dceb-45e2-ac24-c642720108f7)。
  
### <a name="sign-in-experience"></a>登录体验

登录体验会根据正在使用的标识类型而变化：<br><br>
  
| 服务 | 云标识 | 联合身份 |
|:-----|:-----|:-----|
|Outlook 2016  <br/> |每次会话登录 <sup>1</sup> <br/> |每次会话登录 <sup>2</sup> <br/> |
|Outlook 2013  <br/> |每次会话登录 <sup>1</sup> <br/> |每次会话登录 <sup>2</sup> <br/> |
|Windows 7 上的 Outlook 2010 或 Office 2007。  <br/> |每次会话登录 <sup>1</sup> <br/> |每次会话登录 <sup>2</sup> <br/> |
|Windows Vista 上的 Outlook 2010 或 Office Outlook 2007。  <br/> |每次会话登录 <sup>1</sup> <br/> |每次会话登录 <sup>2</sup> <br/> |
|Microsoft Exchange ActiveSync  <br/> |每次会话登录 <sup>1</sup> <br/> |每次会话登录 <sup>2</sup> <br/> |
|POP、IMAP、Outlook for Mac  <br/> |每次会话登录 <sup>1</sup> <br/> |每次会话登录 <sup>2</sup> <br/> |
|Web 体验：Microsoft 365 管理中心/Outlook 网页版/SharePoint联机/Office 网页版  <br/> |每次浏览器会话登录 <sup>4</sup> <br/> |每次会话登录 <sup>3</sup> <br/> |
|使用 SharePoint Online 的 Office 2010 或 Office 2007。  <br/> |每次 SharePoint Online 会话登录 <sup>4</sup> <br/> |每次 SharePoint Online 会话登录 <sup>3</sup> <br/> |
|Skype for Business Online  <br/> |每次会话登录 <sup>1</sup> <br/> |无提示  <br/> |
|Outlook for Mac  <br/> |每次会话登录 <sup>1</sup> <br/> |每次会话登录 <sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> 当首次出现提示时，可以保存密码供将来使用。 在更改密码之前，你将不会收到另一个提示。 <br/> 
<sup>2</sup> 输入公司凭据。 你可以保存密码，并且在更改密码之前不会再次提示你。 <br/> 
<sup>3</sup> 所有应用都需要输入或选择要登录的用户名。 如果你的计算机已加入域，将不会提示你输入密码。 如果选择 **“使我保持登录** 状态”，则在注销之前不会再次提示你。 <br/> 
<sup>4</sup> 如果选择 **“让我登录”** ，则在注销之前不会再次提示你。 
  
## <a name="create-user-accounts"></a>Create user accounts

可以通过多种方式添加用户。 若要了解详细信息，请参阅[单独或批量添加用户 - 管理员帮助](/office365/admin/add-users/add-users)和[添加、删除和管理Microsoft 365 管理中心预览版中的用户](https://support.office.com/article/6e80db58-c36b-4add-b1c8-cc5135f111f3)。 如果使用的是由世纪互联在中国运营的 Office 365，请参阅[在由世纪互联运营的 Office 365 中创建或编辑用户帐户 - 管理帮助](/office365/admin/add-users/add-users)。
  
## <a name="delete-user-accounts"></a>删除用户帐户

如何删除账户取决于是否正在使用目录同步。 
  
- 如果不使用目录同步，可以使用管理员页面或使用Windows PowerShell删除帐户。
    
- 如果正在使用目录同步，您必须从本地 Active Directory 而不是 Office 365 删除用户。
    
删除帐户后，该帐户将变为非活动状态。 在删除后大约 30 天内，可以还原帐户。 有关删除和还原帐户的详细信息，请参阅[“删除用户](/office365/admin/add-users/delete-a-user)和[还原用户](/office365/admin/add-users/restore-user)”，或者，如果使用的是中国世纪互联运营的Office 365，请参阅在[由世纪互联运营的Office 365中创建或编辑用户帐户 - 管理员帮助](/office365/admin/add-users/add-users)。
  
## <a name="password-management"></a>密码管理

密码管理策略和程序取决于身份系统。
  
### <a name="cloud-identity-password-management"></a>云标识密码管理
  
当使用云身份时，将在创建账户时自动生成密码。
  
- 有关云身份密码强度要求的信息，请参阅[密码策略](/previous-versions/azure/jj943764(v=azure.100))。
    
- 为了提高安全性，用户在首次访问Microsoft 服务时必须更改其密码。 因此，在用户访问Microsoft 服务之前，他们必须登录到Microsoft 365 管理中心，系统会提示他们更改密码。
    
- 管理员可以设置密码过期策略。 有关详细信息，请参阅 [“设置用户的密码过期策略](/office365/admin/manage/set-password-expiration-policy)”。
    
可通过以下几个工具为拥有云身份的用户重置密码：
  
- **管理员重置密码** - 如果用户丢失或忘记其密码，管理员可以在管理中心或使用Windows PowerShell重置用户的密码。 只有在知道自己现有密码的情况下，用户才能更改密码。 
    
    对于企业计划，如果管理员丢失或忘记了密码，则具有全局管理员角色的不同管理员可以在Microsoft 365 管理中心或使用Windows PowerShell重置管理员的密码。 有关详细信息，请参阅[重置管理员密码](/office365/admin/add-users/reset-passwords)。 如果使用的是由世纪互联在中国运营的 Office 365，请参阅[在由世纪互联运营的 Office 365 中更改或重置密码](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b)。
    
- **用户使用Outlook 网页版更改密码** - Outlook 网页版选项页包含更改密码超链接，可将用户重定向到 **“更改密码**”页。 用户必须知道旧密码。 有关详细信息，请参阅[更改密码](https://support.office.com/article/change-password-in-outlook-web-app-50bb1309-6f53-4c24-8bfd-ed24ca9e872c)。 如果使用的是由世纪互联在中国运营的 Office 365，请参阅[在由世纪互联运营的 Office 365 中更改或重置密码](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b)。
    
- **基于角色的重置密码权** 限 - 对于企业计划，可以为授权用户（如支持人员）分配 **“重置密码** 用户权限”和“使用预定义或自定义角色更改密码”的权利，而无需成为完整的服务管理员。 默认情况下，在企业计划中，具有全局管理员、密码管理员或用户管理管理员角色的管理员可以更改密码。 有关详细信息，请参阅[分配管理员角色](/office365/admin/add-users/assign-admin-roles)。
    
- **使用Windows PowerShell重置密码** - 服务管理员可以使用Windows PowerShell重置密码。 
    
### <a name="federated-identity-password-management"></a>联合标识密码管理
  
当使用联合身份时，密码将在 Active Directory 中管理。 本地安全令牌服务与联合网关协商身份验证，而无需通过 Internet 将用户的本地 Active Directory 密码传递给Office 365。 使用本地密码策略，或针对 Web 客户端进行双因素身份验证。 Outlook 网页版不包括更改密码超链接。 用户可以使用标准、内部部署工具或通过他们的桌面 PC 登录选项更改密码。
  
如果在组织环境中启用了 [具有单一登录 (SSO) 目录同步 ](/previous-versions/azure/azure-services/dn441213(v=azure.100)) ，并且存在影响联合标识提供者的中断，则联合登录的密码同步备份提供了手动将域切换到密码同步的选项。修复中断时，使用密码同步将允许用户访问。 了解 [如何从单Sign-On切换到密码同步](https://go.microsoft.com/fwlink/p/?LinkId=509832)。
  
## <a name="license-management"></a>许可证管理

许可证允许用户访问一组Microsoft 服务。 对于需要访问权限的服务，管理员可以向每位用户分配许可证。 例如，您可以向用户分配 Skype for Business Online（而不是 SharePoint Online）的访问权限。
  
Microsoft 计费管理员可以更改订阅详细信息，例如用户许可证数和公司使用的其他服务数。 签出 [分配或删除许可证](/office365/admin/subscriptions-and-billing/assign-licenses-to-users)。 如果使用的是由世纪互联运营的 Office 365，请参阅[在由世纪互联运营的 Office 365 中分配或删除许可证](/office365/admin/subscriptions-and-billing/assign-licenses-to-users)。
  
## <a name="group-management"></a>组管理

在 SharePoint Online 中使用安全组以控制对站点的访问权限。 可以在Microsoft 365 管理中心中创建安全组。 有关安全组的详细信息，请参阅[创建、编辑或删除安全组](/office365/admin/email/create-edit-or-delete-a-security-group)。
  
## <a name="administrator-roles"></a>管理员角色

企业Office 365遵循基于角色的访问控制 (RBAC) 模型：权限和功能由管理角色定义。 为其组织注册 Office 365 的用户自动成为全局管理员或顶级管理员。 有五种管理员角色：全局管理员、帐务管理员、密码管理员、服务管理员和用户管理管理员。 有关企业Office 365中的管理员角色的详细信息，包括它们如何应用于Exchange Online、SharePoint联机和Skype for Business联机管理，请参[阅分配管理员角色](/previous-versions/windows/it-pro/windows-server-2012-R2-and-2012/jj878348(v=ws.11))。 如果使用由 21Vianet 在中国运营的Office 365，请[参阅 Office 365 商业版分配管理员角色](/office365/admin/add-users/assign-admin-roles)。
  
## <a name="delegated-administration-and-support-for-partners"></a>合作伙伴的委派管理和支持

可以授权合作伙伴代表客户管理帐户。 客户不需要合作伙伴使用的用户帐户，并且在授予委派的管理权限时不使用许可证。 合作伙伴可以向其组织内的用户分配完整或受限访问权限。 受限访问权限包括重置密码、管理服务请求和监视服务运行状况。 
  
> [!NOTE]
> 将合作伙伴用作或指定为委派管理员的功能因地区而异。 
  
## <a name="azure-active-directory-services"></a>Azure Active Directory 服务

Azure Active Directory (AD) 将身份和访问管理综合功能引入 Office 365。不仅整合了目录服务、高级身份管理、应用程序访问管理，并为开发者提供了一个基于标准的丰富平台。若要详细了解 Office 365 中的 AD 功能，请参阅 [Sign in page branding and cloud user self-service password reset](https://go.microsoft.com/fwlink/?linkid=2144147)（登录页品牌塑造和云用户自助服务密码重置）。详细了解 [Free, Basic, and Premium editions of Azure Active Directory](/previous-versions/azure/dn532272(v=azure.100))（Azure Active Directory 免费版、基本版和高级版）。 
  
## <a name="feature-availability"></a>功能可用性

若要查看跨计划、独立选项和本地解决方案的功能可用性，请参阅[Microsoft 365和Office 365平台服务说明](office-365-platform-service-description.md)。
