---
title: User account management
ms.author: office365servicedesc
author: pamelaar
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
description: A Microsoft dá suporte aos seguintes métodos para criar, gerenciar e autenticar usuários.
ms.openlocfilehash: 31fe2a1df472b6fc22df5cb7ff29b8658519cbc7
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/24/2021
ms.locfileid: "51172776"
---
# <a name="user-account-management"></a>User account management

A Microsoft dá suporte aos seguintes métodos para criar, gerenciar e autenticar usuários. 
  
> [!NOTE]
> Este tópico não inclui informações sobre recursos de segurança que permitem ou proíbem o acesso a recursos individuais da Microsoft (por exemplo, controle de acesso baseado em função no Microsoft Exchange Online ou configurando a segurança no Microsoft SharePoint Online). Para obter detalhes sobre esses recursos, consulte a descrição do [serviço do Exchange Online](../exchange-online-service-description/exchange-online-service-description.md) e a descrição do serviço do [SharePoint Online.](../sharepoint-online-service-description/sharepoint-online-service-description.md) 
  
Se você precisar de informações sobre ferramentas que podem ajudá-lo a executar tarefas administrativas, consulte [Ferramentas para gerenciar contas da Microsoft.](/office365/enterprise/manage-office-365-accounts) Para saber como executar tarefas de gerenciamento diárias, consulte [Tarefas comuns de gerenciamento.](/office365/admin/manage/manage)
  
## <a name="need-help-with-signing-in-installing-or-uninstalling-or-canceling-your-subscription"></a>Precisa de ajuda para entrar, instalar ou desinstalar ou cancelar sua assinatura?

Obter ajuda com: [entrar em Instalar](https://support.office.com/article/where-to-sign-in-to-office-365-for-business-e9eb7d51-5430-4929-91ab-6157c5a050b4)ou  |  [desinstalar o Office](https://support.office.com/article/download-and-install-or-reinstall-office-365-or-office-2019-on-a-pc-or-mac-4414eaaf-0478-48be-9c42-23adc4716658)  |  [Canceling Office 365](https://support.office.com/article/Cancel-Office-365-for-business-b1bc0bef-4608-4601-813a-cdd9f746709a)
  
Para outros problemas, visite o centro [de suporte da Microsoft](https://support.microsoft.com/contactus/). Para suporte para o Office 365 operado pela 21Vianet na China, fale com a [Equipe de suporte técnico da 21Vianet](https://support.office.com/article/Get-technical-billing-and-subscription-support-for-Office-365-operated-by-21Vianet-671FB12E-F5D8-4CDF-B3E9-E8068A9AA496). Em relação ao Office 365 Germany, fale com a [Equipe de suporte do Office 365 Germany](https://support.office.com/article/83ef2266-2543-48d7-a41a-1b56b403a8e9). 
  
## <a name="sign-in-options"></a>Opções de entrada

A Microsoft tem dois sistemas que podem ser usados para identidades de usuário:
  
- **Conta corporativa ou** de estudante (identidade na nuvem) - Os usuários recebem credenciais de nuvem do Azure Active Directory, separadas de outras credenciais corporativas ou de área de trabalho, para entrar nos serviços de nuvem da Microsoft. Esta é a identidade padrão que recomendamos para minimizar a complexidade da implantação. As senhas de contas corporativas ou de estudante usam a política de senha de Azure Active Directory [](/previous-versions/azure/jj943764(v=azure.100)).
    
- **Conta federada (identidade federada)** - Para todas as assinaturas em organizações com o Active Directory local que usam SSO (login único), os usuários podem entrar nos serviços da Microsoft usando suas credenciais do Active Directory. O Active Directory corporativo armazena e controla a política de senha. Para saber mais sobre o SSO, confira [Mapa do logon único](/previous-versions/azure/azure-services/hh967643(v=azure.100)).
    
O tipo de identidade afeta a experiência do usuário e as opções de gerenciamento de conta de usuário, bem como hardware e requisitos de software e outras considerações de implantação.
  
### <a name="custom-domains-and-identity-options"></a>Domínios personalizados e opções de identidade

Quando você cria um novo usuário, o nome de entrada do usuário e o endereço de email são atribuídos ao domínio padrão, conforme definido no centro de administração do Microsoft 365. Para saber mais, confira [Adicionar seus usuários e domínio](https://support.office.com/article/Add-your-users-and-domain-to-Office-365-6383f56d-3d09-4dcb-9b41-b5f5a5efd611). 
  
Por padrão, a assinatura usa o <*nome* da empresa > **.onmicrosoft.com** domínio criado com a conta. Se você estiver usando o Office 365 operado pela 21Vianet na China, o domínio padrão será <*nome* da empresa > **.onmsChina.cn**. Se você estiver usando o Office 365 Germany, o domínio padrão será <*nome* da empresa > **.onmicrosoft.de**. Você pode adicionar um ou mais domínios personalizados à Microsoft em vez de reter o domínio onmicrosoft.com e pode atribuir usuários **para** entrar com qualquer um dos domínios validados. O domínio atribuído a cada usuário é o endereço de email que aparecerá em mensagens de email enviadas e recebidas. 
  
Você pode hospedar até 900 domínios da Internet registrados, cada um representado por um namespace diferente. 
  
Para organizações usando o logon único, todos os usuários em um domínio devem usar o mesmo sistema de identidade: identidade de nuvem ou identidade federada. Por exemplo, você pode ter um grupo de usuários que só precisa de uma identidade na nuvem porque eles não acessam sistemas locais e outro grupo de usuários que usam a Microsoft e sistemas locais. Você adicionaria dois domínios ao Office 365, como contractors.contoso.com e **staff.contoso.com**, e configuraria apenas o SSO para um deles.  Um domínio inteiro pode ser convertido da identidade da nuvem para a identidade federada ou da identidade federada para a identidade na nuvem.
  
Para obter mais informações sobre domínios no Office 365, consulte a descrição de serviço de [Domínios](domains.md). 
  
## <a name="authentication"></a>Autenticação

Com exceção de sites da Internet para acesso anônimo criado com o SharePoint Online, os usuários devem ser autenticados ao acessar os serviços da Microsoft. 
  
- **Autenticação moderna** - A autenticação moderna traz entrada baseada na Biblioteca de Autenticação da Microsoft para aplicativos cliente do Office em plataformas. Isso permite os recursos de logon, como a Autenticação de Vários Fatores (MFA), provedores de identidade de terceiros baseada em SAML com aplicativos clientes do Office e cartão inteligente e autenticação baseada em certificado. Ele também elimina a necessidade do Microsoft Outlook de usar o protocolo de autenticação básica. Para obter mais informações, incluindo a disponibilidade da autenticação moderna entre aplicativos do Office, consulte Como funciona a autenticação moderna para aplicativos cliente do [Office 2013 e do Office 2016.](/office365/enterprise/modern-auth-for-office-2013-and-2016)
    
    A autenticação moderna está 100% 100%. Para saber como ative ou desativar, consulte [Habilitar autenticação moderna no Exchange Online](/exchange/clients-and-mobile-in-exchange-online/enable-or-disable-modern-authentication-in-exchange-online).
    
- **Autenticação de identidade na** nuvem - Os usuários com identidades de nuvem são autenticados usando desafio/resposta tradicional. O navegador da Web é redirecionado para o serviço de login da Microsoft, onde você digita o nome de usuário e a senha para sua conta de trabalho ou de estudante. O serviço de entrada autentica as credenciais e gera um token de serviço, que o navegador da Web envia para o serviço solicitado e o conecta. 
    
- **Autenticação de identidade federada** - Os usuários com identidades federadas são autenticados usando o AD FS (Serviços de Federação do Active Directory) 2.0 ou outros Serviços de Token de Segurança. O navegador da Web é redirecionado para o serviço de login da Microsoft, onde você digita sua ID corporativa no formato upn (nome de entidade de usuário), por exemplo: *isabel@contoso.com*. O serviço de entrada determina que você é parte de um domínio federado e oferece redirecioná-lo para o servidor de Federação no local para autenticação. Se você estiver conectado à área de trabalho (domínio ingressado), será autenticado (usando Kerberos ou NTLMv2) e o Serviço de Token de Segurança local gerará um token de logon, que o navegador da Web posta no serviço de logon da Microsoft. Usando o token de logon, o serviço de entrada gera um token de serviço que o navegador da web envia para o serviço solicitado e o conecta. Para uma lista de Serviços de Token de Segurança disponíveis, confira [Mapa de logon único](/previous-versions/azure/azure-services/hh967643(v=azure.100)).
    
A Microsoft usa autenticação baseada em formulários e o tráfego de autenticação pela rede é sempre criptografado com TLS/SSL usando a porta 443. O tráfego de autenticação usa uma porcentagem insignificante de largura de banda para serviços Microsoft. 
  
### <a name="multi-factor-authentication"></a>Autenticação Multifator

Com a Autenticação Multifa factor, os usuários são obrigados a reconhecer uma chamada telefônica, uma mensagem de texto ou uma notificação de aplicativo em seus smartphones depois de inserir corretamente a senha. Somente após esta segunda autenticação é que o usuário pode iniciar a sessão. Os administradores da Microsoft podem registrar usuários para autenticação multifafação no Centro de administração do Microsoft 365. Saiba mais sobre [a Autenticação Multifa factor](/office365/admin/security-and-compliance/set-up-multi-factor-authentication).
  
### <a name="rich-client-authentication"></a>Autenticação de cliente avançado

Para clientes avançados como os aplicativos da área de trabalho do Microsoft Office, a autenticação pode ser feita de duas maneiras:
  
- **Microsoft Online Services Sign-In** Assistente - O assistente de entrada, que é instalado pela configuração da área de trabalho, contém um serviço de cliente que obtém um token de serviço do serviço de entrada e o retorna ao cliente rico. 
    
  - Se você tiver uma identidade na nuvem, receberá um prompt de credenciais, que o serviço cliente envia para o serviço de entrada para autenticação (usando WS-Trust).
    
  - Se você tiver uma identidade federada, o serviço cliente contatará primeiro o servidor do AD FS 2.0 para autenticar as credenciais (usando Kerberos ou NTLMv2) e obter um token de logon enviado para o serviço de entrada (usando o WS-Federation e o WS-Trust).
    
- **Autenticação básica/proxy por SSL** - O cliente do Outlook passa credenciais de autenticação básicas por SSL para o Exchange Online. O Exchange Online proxies a solicitação de autenticação para a plataforma de identidade e, em seguida, para o Servidor de Federação do Active Directory local (para SSO). 
    
Para garantir a descoberta e a autenticação adequadas dos serviços microsoft, os administradores devem aplicar um conjunto de componentes e atualizações a cada estação de trabalho que usa clientes ricos (como o Microsoft Office 2010) e se conecta ao Office 365. A configuração da área de trabalho é uma ferramenta automatizada para configurar estações de trabalho com as atualizações necessárias. Para obter mais informações, [consulte Use my current Office desktop apps](https://support.office.com/article/3324b8b8-dceb-45e2-ac24-c642720108f7).
  
### <a name="sign-in-experience"></a>Experiência de entrada

A experiência de login muda dependendo do tipo de identidade em uso:<br><br>
  
| Serviço | Identidade de nuvem | Identidade federada |
|:-----|:-----|:-----|
|Outlook 2016  <br/> |Entrar em cada sessão <sup>1</sup> <br/> |Entrar em cada sessão <sup>2</sup> <br/> |
|Outlook 2013  <br/> |Entrar em cada sessão <sup>1</sup> <br/> |Entrar em cada sessão <sup>2</sup> <br/> |
|Outlook 2010 ou Office 2007 no Windows 7  <br/> |Entrar em cada sessão <sup>1</sup> <br/> |Entrar em cada sessão <sup>2</sup> <br/> |
|Outlook 2010 ou Office Outlook 2007 no Windows Vista  <br/> |Entrar em cada sessão <sup>1</sup> <br/> |Entrar em cada sessão <sup>2</sup> <br/> |
|Microsoft Exchange ActiveSync  <br/> |Entrar em cada sessão <sup>1</sup> <br/> |Entrar em cada sessão <sup>2</sup> <br/> |
|POP, IMAP, Outlook para Mac  <br/> |Entrar em cada sessão <sup>1</sup> <br/> |Entrar em cada sessão <sup>2</sup> <br/> |
|Experiências da Web: Centro de administração do Microsoft 365 / Outlook na Web/ SharePoint Online / Office para a Web  <br/> |Entrar em cada sessão do navegador<sup>4</sup> <br/> |Entrar em cada sessão <sup>3</sup> <br/> |
|Office 2010 ou Office 2007 usando SharePoint Online  <br/> |Entrar em cada sessão do SharePoint Online<sup>4</sup> <br/> |Entrar em cada sessão do SharePoint Online<sup>3</sup> <br/> |
|Skype for Business online  <br/> |Entrar em cada sessão <sup>1</sup> <br/> |Nenhum alerta  <br/> |
|Outlook para Mac  <br/> |Entrar em cada sessão <sup>1</sup> <br/> |Entrar em cada sessão <sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> Quando solicitado pela primeira vez, você pode salvar sua senha para uso futuro. Você não receberá outra solicitação até alterar a senha. <br/> 
<sup>2</sup> Insira suas credenciais corporativas. Você pode salvar a senha, e não haverá nova solicitação até que a senha seja alterada. <br/> 
<sup>3</sup> Todos os aplicativos exigem que você insira ou selecione seu nome de usuário para entrar. A senha não será solicitada se o computador estiver associado ao domínio. Se você selecionar **Keep me signed in** you will not be prompted again until you sign out. <br/> 
<sup>4 Se</sup> você selecionar **Manter-me dentro,** você não será solicitado novamente até sair. 
  
## <a name="create-user-accounts"></a>Create user accounts

Há várias maneiras de adicionar usuários. Para saber mais, confira Adicionar usuários [individualmente](/office365/admin/add-users/add-users) ou em massa - Ajuda do Administrador e Adicionar, remover e gerenciar usuários no Centro de administração [do Microsoft 365 Preview](https://support.office.com/article/6e80db58-c36b-4add-b1c8-cc5135f111f3). Se você estiver usando o Office 365 operado pela 21Vianet na China, confira [Criar ou editar contas de usuário no Office 365 operado pela 21Vianet - Ajuda do administrador](/office365/admin/add-users/add-users).
  
## <a name="delete-user-accounts"></a>Excluir contas de usuário

A maneira de excluir contas depende de se estar usando a sincronização de diretório: 
  
- Se você não estiver usando a sincronização de diretórios, as contas poderão ser excluídas usando a página de administrador ou usando Windows PowerShell.
    
- Se você estiver usando a sincronização de diretório, você deve excluir os usuários do Active Directory local, em vez do Office 365.
    
Quando uma conta é excluída, ela se torna inativa. Por um período de aproximadamente 30 dias após ter sido excluída, ainda é possível restaurar a conta. Para obter mais informações sobre como excluir e [](/office365/admin/add-users/restore-user) restaurar contas, consulte [Excluir](/office365/admin/add-users/delete-a-user) usuários e restaurar usuários ou, se você estiver usando o Office 365 operado pela 21Vianet na China, consulte Create or edit user [accounts in Office 365 operated by 21Vianet - Admin Help](/office365/admin/add-users/add-users).
  
## <a name="password-management"></a>Gerenciamento de senhas

As políticas e procedimentos para gerenciamento de senhas dependem do sistema de identidade.
  
### <a name="cloud-identity-password-management"></a>Gerenciamento de senha de identidade na nuvem
  
Ao utilizar as identidades de nuvem, as senhas são geradas automaticamente quando a conta é criada.
  
- Para requisitos de força da senha da identidade da nuvem, confira [Política de senha](/previous-versions/azure/jj943764(v=azure.100)).
    
- Para aumentar a segurança, os usuários devem alterar suas senhas quando acessam pela primeira vez os serviços da Microsoft. Como resultado, antes que os usuários possam acessar os serviços da Microsoft, eles devem entrar no centro de administração do Microsoft 365, onde são solicitados a alterar suas senhas.
    
- Administradores podem definir a política de expiração de senha. Confira mais informações em [Definir uma política de expiração de senha do usuário](/office365/admin/manage/set-password-expiration-policy).
    
Existem várias ferramentas para redefinir senhas de usuários com identidades da nuvem:
  
- **Administrador redefine senha** - Se os usuários perderem ou esquecerem suas senhas, os administradores poderão redefinir as senhas dos usuários no centro de administração ou usando Windows PowerShell. Os usuários poderão alterar suas senhas apenas se souberem suas senhas antigas. 
    
    Para planos corporativos, se os administradores perderem ou esquecerem suas senhas, um administrador diferente com a função Administrador Global poderá redefinir as senhas dos administradores no centro de administração do Microsoft 365 ou usando o Windows PowerShell. Para saber mais, confira [Redefinir senhas para administradores](/office365/admin/add-users/reset-passwords). Se você estiver trabalhando no Office 365 operado pela 21Vianet na China, confira [Alterar ou redefinir senhas no Office 365 operado pela 21Vianet](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b).
    
- **O usuário altera senhas** com o Outlook na Web - A página opções do Outlook na Web inclui um hiperlink Alterar senha, que redireciona os usuários para a página **Alterar Senha.** O usuário deve saber sua senha anterior. Para saber mais, confira [Alterar senha](https://support.office.com/article/change-password-in-outlook-web-app-50bb1309-6f53-4c24-8bfd-ed24ca9e872c). Se você estiver usando o Office 365 operado pela 21Vianet na China, confira [Alterar ou redefinir senhas no Office 365 operado pela 21Vianet](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b).
    
- Direitos **de** redefinição de senha baseados em função - Para planos  corporativos, os usuários autorizados, como a equipe de assistência técnica, podem ter o direito de redefinir senha e o direito de alterar senhas usando funções predefinidas ou personalizadas sem se tornarem administradores de serviços completos. Por padrão, em planos corporativos, os administradores com a função Administrador Global, Administrador de Senha ou Administrador de Gerenciamento de Usuário podem alterar senhas. Para saber mais, veja [Atribuindo funções de administrador](/office365/admin/add-users/assign-admin-roles).
    
- **Redefinir senhas usando Windows PowerShell** - Os administradores de serviço podem usar Windows PowerShell redefinir senhas. 
    
### <a name="federated-identity-password-management"></a>Gerenciamento de senha de identidade federada
  
Ao usar identidades federadas, as senhas são gerenciadas no Active Directory. O Serviço de Token de Segurança local negocia a autenticação com o Gateway de Federação sem passar senhas locais do Active Directory dos usuários pela Internet para o Office 365. As políticas de senha locais são usadas ou, para clientes web, identificação de dois fatores. O Outlook na Web não inclui um hiperlink Alterar Senha. Os usuários podem alterar suas senhas usando ferramentas padrão, no local ou através das opções de logon de seu PC desktop.
  
Se você tiver a Sincronização de Diretórios com o [SSO (SSO)](/previous-versions/azure/azure-services/dn441213(v=azure.100)) único habilitado no ambiente da organização e houver uma paralisação que afeta seu provedor de identidade federada, o Backup de Sincronização de Senhas para Login Federado oferece a opção de alternar manualmente seu domínio para a Sincronização de Senhas. O uso da Sincronização de Senha permitirá que seus usuários acessem enquanto a paralisação é corrigida. Saiba [como alternar do Single Sign-On para a Sincronização de Senhas.](https://go.microsoft.com/fwlink/p/?LinkId=509832)
  
## <a name="license-management"></a>Gerenciamento de licenças

Uma licença dá a um usuário acesso a um conjunto de serviços da Microsoft. Um administrador atribui a cada usuário uma licença para o serviço para o qual ele precisa de acesso. Por exemplo, você pode atribuir a um usuário acesso para o Skype for Business online, mas não para o SharePoint Online.
  
Os administradores de cobrança da Microsoft podem fazer alterações nos detalhes da assinatura, como o número de licenças de usuário e o número de serviços adicionais que sua empresa usa. Confira Atribuir [ou remover uma licença](/office365/admin/subscriptions-and-billing/assign-licenses-to-users). Se você estiver usando o Office 365 operado pela 21Vianet, confira [Atribuir ou remover licenças no Office 365 operado pela 21Vianet](/office365/admin/subscriptions-and-billing/assign-licenses-to-users).
  
## <a name="group-management"></a>Gerenciamento de grupos

Os grupos de segurança são usados no SharePoint Online para controlar o acesso aos sites. Os grupos de segurança podem ser criados no Centro de administração do Microsoft 365. Para saber mais sobre grupos de segurança, confira [Criar, editar ou excluir um grupo de segurança](/office365/admin/email/create-edit-or-delete-a-security-group).
  
## <a name="administrator-roles"></a>Funções de administrador

O Office 365 para empresas segue um modelo de controle de acesso baseado em função (RBAC): as permissões e os recursos são definidos por funções de gerenciamento. A pessoa que assina o Office 365 para sua organização se torna automaticamente um administrador global ou administrador de nível superior. Existem cinco funções de administrador: administrador global, administrador de cobrança, administrador de senhas, administrador de serviço e administrador de gerenciamento de usuário. Para obter mais informações sobre funções de administrador no Office 365 para empresas, incluindo como elas se aplicam à administração do Exchange Online, do SharePoint Online e do Skype for Business Online, consulte [Assigning administrator roles](/previous-versions/windows/it-pro/windows-server-2012-R2-and-2012/jj878348(v=ws.11)). Se você estiver usando o Office 365 operado pela 21Vianet na China, confira [Atribuir funções de administrador no Office 365 para empresas](/office365/admin/add-users/assign-admin-roles).
  
## <a name="delegated-administration-and-support-for-partners"></a>Suporte para parceiros e administração delegada

Parceiros podem ser autorizados a administrar contas em nome de clientes. O cliente não exige uma conta de usuário para os parceiros usarem e não consome uma licença ao conceder autoridade de administração delegada. Parceiros podem atribuir acesso completo ou limitado a usuários dentro de sua organização. Acesso limitado inclui direitos para redefinir senhas, gerenciar solicitações de serviço e monitorar a integridade do serviço. 
  
> [!NOTE]
> A capacidade de usar e especificar um parceiro como administrador delegado varia de acordo com a região. 
  
## <a name="azure-active-directory-services"></a>Serviços do Azure Active Directory

O Active Directory (AD) do Azure oferece recursos abrangentes de gerenciamento de identidade e acesso ao Office 365. Ele combina os serviços de diretório, gerenciamento avançado de identidades, gerenciamento de acesso a aplicativos e uma plataforma avançada baseada em padrões para os desenvolvedores. Para saber mais sobre os recursos do AD no Office 365, consulte Entrar com a identidade visual da página e redefinir a senha de [autoatendados do usuário na nuvem.]() https://go.microsoft.com/fwlink/?linkid=2144147 Saiba mais sobre as [Edições Gratuita, Basic e Premium do Azure Active Directory](/previous-versions/azure/dn532272(v=azure.100)). 
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos entre planos, opções autônomas e soluções locais, consulte a descrição do serviço de plataforma do [Microsoft 365 e do Office 365.](office-365-platform-service-description.md)
