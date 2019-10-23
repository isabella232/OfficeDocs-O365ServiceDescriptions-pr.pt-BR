---
title: Gerenciamento de Contas de Usuário
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
description: O Microsoft Office 365 oferece suporte aos seguintes métodos para criar, gerenciar e autenticar usuários.
ms.openlocfilehash: bd6e701c8ff4c699d305bfcde8a68e1867dd0bb2
ms.sourcegitcommit: d6c7836299ee5e86e890cab1c41f3bc21fd282de
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/22/2019
ms.locfileid: "37631650"
---
# <a name="user-account-management"></a>Gerenciamento de Contas de Usuário

O Microsoft Office 365 oferece suporte aos seguintes métodos para criar, gerenciar e autenticar usuários. 
  
> [!NOTE]
> Este tópico não inclui informações sobre recursos de segurança que permitem ou proíbem o acesso a recursos individuais do Office 365 (por exemplo, controle de acesso baseado em função no Microsoft Exchange Online ou configurar a segurança no Microsoft SharePoint Online). Veja detalhes sobre esses recursos em [Descrição de Serviço do Exchange Online](../exchange-online-service-description/exchange-online-service-description.md) e [Descrição do serviço SharePoint Online](../sharepoint-online-service-description/sharepoint-online-service-description.md). 
  
Se você precisa de informações sobre ferramentas para executar tarefas administrativas, confira [Ferramentas para gerenciar contas do Office 365](https://docs.microsoft.com/office365/enterprise/manage-office-365-accounts). Para saber como executar tarefas diárias de gerenciamento, confira [Tarefas comuns de gerenciamento do Office 365](https://docs.microsoft.com/office365/admin/manage/manage).
  
## <a name="need-help-signing-in-installing-or-uninstalling-or-canceling-your-subscription"></a>Precisa de ajuda para entrar, instalar/desinstalar ou cancelar sua assinatura?

Obtenha ajuda sobre [Como entrar no Office 365 para empresas](https://support.office.com/article/where-to-sign-in-to-office-365-for-business-e9eb7d51-5430-4929-91ab-6157c5a050b4) | [Baixar e instalar ou reinstalar o Office 365 ou o Office 2016 em seu PC ou Mac](https://support.office.com/article/download-and-install-or-reinstall-office-365-or-office-2019-on-a-pc-or-mac-4414eaaf-0478-48be-9c42-23adc4716658) | [Cancelar o Office 365 para empresas](https://support.office.com/article/Cancel-Office-365-for-business-b1bc0bef-4608-4601-813a-cdd9f746709a)
  
Para outros problemas com o Office 365, acesse o [Centro de Suporte da Microsoft](https://support.microsoft.com/contactus/). Para suporte para o Office 365 operado pela 21Vianet na China, fale com a [Equipe de suporte técnico da 21Vianet](https://support.office.com/article/Get-technical-billing-and-subscription-support-for-Office-365-operated-by-21Vianet-671FB12E-F5D8-4CDF-B3E9-E8068A9AA496). Em relação ao Office 365 Germany, fale com a [Equipe de suporte do Office 365 Germany](https://support.office.com/article/Get-technical-and-billing-support-for-Office-365-Germany-83ef2266-2543-48d7-a41a-1b56b403a8e9?ui=en-US&amp;rs=en-US&amp;ad=US&amp;fromAR=1). 
  
## <a name="sign-in-options"></a>Opções de entrada

O Office 365 tem dois sistemas que podem ser usados para identidades de usuário:
  
- **Conta corporativa ou de estudante (identidade de nuvem)** Os usuários recebem credenciais de nuvem do Azure Active Directory, separadas de outras credenciais corporativas ou de área de trabalho, para entrar no Office 365 e em outros Serviços em nuvem da Microsoft. Esta é a identidade padrão que recomendamos para minimizar a complexidade da implantação. As senhas de contas corporativas ou de estudante usam a política de senha de Azure Active Directory [](https://docs.microsoft.com/previous-versions/azure/jj943764(v=azure.100)).
    
- **Conta federada (identidade federada)** Para todas as assinaturas em organizações com Active Directory local que usem logon único (SSO), os usuários podem entrar nos serviços do Office 365 usando suas credenciais do Active Directory. O Active Directory corporativo armazena e controla a política de senha. Para saber mais sobre o SSO, confira [Mapa do logon único](https://docs.microsoft.com/previous-versions/azure/azure-services/hh967643(v=azure.100)).
    
O tipo de identidade afeta a experiência do usuário e as opções de gerenciamento de conta de usuário, bem como hardware e requisitos de software e outras considerações de implantação.
  
### <a name="custom-domains-and-identity-options"></a>Domínios personalizados e opções de identidade

Quando você cria um novo usuário, o nome de entrada e o endereço de email do usuário são atribuídos ao domínio padrão, conforme definido no centro de administração do Microsoft 365. Para saber mais, confira [Adicionar seus usuários e domínios ao Office 365](https://support.office.com/article/Add-your-users-and-domain-to-Office-365-6383f56d-3d09-4dcb-9b41-b5f5a5efd611). 
  
Por padrão, a assinatura do Office 365 usa o domínio \< _company name_\> **.onmicrosoft.com** criado com a conta.\* Você pode adicionar um ou mais domínios personalizados ao Office 365, em vez de manter o domínio onmicrosoft.com. Além disso, pode atribuir usuários para entrar com outros domínios validados. O domínio atribuído de cada usuário é o endereço de email que será exibido nas mensagens enviadas e recebidas. 
  
Você pode hospedar até 900 domínios de Internet registrados no Office 365, cada um representado por um namespace diferente. 
  
Para organizações usando o logon único, todos os usuários em um domínio devem usar o mesmo sistema de identidade: identidade de nuvem ou identidade federada. Por exemplo, você poderia ter um grupo de usuários que só precisa de uma identidade de nuvem porque eles não acessam sistemas locais e outro grupo de usuários que utilizam o Office 365 e sistemas locais. Você adicionaria dois domínios ao Office 365, como contractors.contoso.com e staff.contoso.com, e só configurou o SSO para um deles. Um domínio inteiro pode ser convertido da identidade da nuvem para a identidade federada ou da identidade federada para a identidade na nuvem.
  
Para obter mais informações sobre domínios no Office 365, consulte a descrição de serviço de [Domínios](domains.md). 
  
\* Se você está usando o Office 365 operado pela 21Vianet na China, o domínio padrão é \<nomedaempresa\> **.onmsChina.cn**. Se estiver usando o Office 365 Germany, o domínio padrão será \<nomedaempresa\> **.onmicrosoft.de**
  
## <a name="authentication"></a>Autenticação

Com exceção de sites da internet para acesso anônimo criado com o SharePoint Online, os usuários devem ser autenticados quando estiverem acessando serviços do Office 365. 
  
- **Autenticação moderna** A autenticação moderna traz o logon baseado na Biblioteca de Autenticação do Active Directory (ADAL) para aplicativos clientes no Office entre plataformas. Isso permite os recursos de logon, como a Autenticação de Vários Fatores (MFA), provedores de identidade de terceiros baseada em SAML com aplicativos clientes do Office e cartão inteligente e autenticação baseada em certificado. Ele também elimina a necessidade do Microsoft Outlook de usar o protocolo de autenticação básica. Para saber mais, incluindo sobre a disponibilidade de autenticação moderna entre aplicativos do Office, consulte [Como a autenticação moderna funciona para aplicativos clientes do Office 2013 e Office 2016](https://docs.microsoft.com/office365/enterprise/modern-auth-for-office-2013-and-2016) e [Usando a autenticação moderna do Office 365 com clientes do Office](https://docs.microsoft.com/office365/enterprise/modern-auth-for-office-2013-and-2016).
    
    A autenticação moderna não está ativada por padrão para o Exchange Online. Para saber como ativá-la, consulte [Habilitar o Exchange Online para autenticação moderna](https://docs.microsoft.com/Exchange/clients-and-mobile-in-exchange-online/enable-or-disable-modern-authentication-in-exchange-online).
    
- **Autenticação da identidade de nuvem** Os usuários com identidades de nuvem são autenticados pelo tradicional método de desafio/resposta. O navegador da Web é redirecionado para o serviço de entrada do Office 365, onde você digita o nome de usuário e a senha da conta corporativa ou de estudante. O serviço de entrada autentica as credenciais e gera um token de serviço, que o navegador da Web envia para o serviço solicitado e o conecta. 
    
- **Autenticação de identidade federada** Usuários com identidades federadas são autenticados usando o Serviços de Federação do Active Directory (AD FS) 2.0 ou outros Serviço de Token de Segurança. O navegador é redirecionado para o serviço de entrada do Office 365, onde você digita seu ID corporativo na forma de um nome de usuário principal (UPN; por exemplo, isabel@contoso.com). O serviço de entrada determina que você é parte de um domínio federado e oferece redirecioná-lo para o servidor de Federação no local para autenticação. Se você está conectado ao desktop (domínio), você está autenticado (usando Kerberos ou NTLMv2) e o Serviço de Token de Segurança no local gera um token de logon, que o navegador da web envia para o serviço de entrada do Office 365. Usando o token de logon, o serviço de entrada gera um token de serviço que o navegador da web envia para o serviço solicitado e o conecta. Para uma lista de Serviços de Token de Segurança disponíveis, confira [Mapa de logon único](https://docs.microsoft.com/previous-versions/azure/azure-services/hh967643(v=azure.100)).
    
O Office 365 usa autenticação baseada em formulários, e o tráfego de autenticação pela rede é sempre criptografia com TLS/SSL usando a porta 443. O tráfego de autenticação usa uma porcentagem negligenciável de largura de banda para serviços do Office 365. 
  
### <a name="multi-factor-authentication-for-office-365"></a>Autenticação multifator para Office 365

Com a autenticação multifator para o Office 365, os usuários precisam confirmar uma chamada telefônica, uma mensagem de texto ou uma notificação de aplicativo em seu smartphone após a inserção correta da senha. Somente após esta segunda autenticação é que o usuário pode iniciar a sessão. Os administradores do Office 365 podem registrar usuários para a autenticação multifator no centro de administração do Microsoft 365. Saiba mais sobre [Multi-Factor Authentication para Office 365](https://docs.microsoft.com/office365/admin/security-and-compliance/set-up-multi-factor-authentication).
  
### <a name="rich-client-authentication"></a>Autenticação de cliente avançado

Para clientes avançados como os aplicativos da área de trabalho do Microsoft Office, a autenticação pode ser feita de duas maneiras:
  
- **Assistente de Conexão do Microsoft Online Services** O Assistente de Entrada, que é instalado pelo Configuração da área de trabalho do Office 365, contém um serviço de cliente que obtém um token de serviço do serviço de entrada do Office 365 e o retorna para o cliente avançado. 
    
  - Se você tem uma identidade de nuvem, você receberá uma solicitação de credenciais, que o serviço de cliente envia para o serviço de entrada para autenticação do Office 365 (usando o WS-Trust).
    
  - Se você tiver uma identidade federada, o serviço para cliente primeiro entra em contato com o servidor dos AD FS 2.0, para autenticar as credenciais (usando Kerberos ou NTLMv2) e obtém um token de logon que é enviado para o serviço de inscrição do Office 365 (usando WS-Federation e WS-Trust).
    
- **Autenticação básica/por proxy via SSL** O cliente do Outlook passa as credenciais de autenticação básica pelo SSL para o Exchange Online. O Exchange Online transmite por proxy a solicitação de autenticação para a plataforma de identidade do Office 365 e, depois, para o Servidor de Federação do Active Directory (para SSO). 
    
Para garantir a descoberta e autenticação adequadas dos serviços do Office 365, os administradores devem aplicar um conjunto de componentes e atualizações a cada estação de trabalho que usa clientes avançados (como o Microsoft Office 2010) e se conecta ao Office 365. A configuração de área de trabalho do Office 365 é uma ferramenta automatizada para configurar workstations com as atualizações necessárias. Para saber mais, confira [Usar meus aplicativos da área de trabalho do Office atuais com o Office 365](https://support.office.com/article/set-up-office-2010-desktop-programs-to-work-with-office-365-for-business-3324b8b8-dceb-45e2-ac24-c642720108f7?ocmsassetID=HA102817827&CorrelationId=8eb1b198-827a-4999-a584-05a05a92d224&ui=en-US&rs=en-US&ad=US).
  
### <a name="sign-in-experience"></a>Experiência de entrada

A experiência de entrada sofre alterações dependendo do tipo de identidade do Office 365 em uso:
  
||**Identidade de nuvem**|**Identidade federada**|
|:-----|:-----|:-----|
|Outlook 2016  <br/> |Entrar em cada sessão <sup>1</sup> <br/> |Entrar em cada sessão <sup>2</sup> <br/> |
|Outlook 2013  <br/> |Entrar em cada sessão <sup>1</sup> <br/> |Entrar em cada sessão <sup>2</sup> <br/> |
|Outlook 2010 ou Office 2007 no Windows 7  <br/> |Entrar em cada sessão <sup>1</sup> <br/> |Entrar em cada sessão <sup>2</sup> <br/> |
|Outlook 2010 ou Office Outlook 2007 no Windows Vista  <br/> |Entrar em cada sessão <sup>1</sup> <br/> |Entrar em cada sessão <sup>2</sup> <br/> |
|Microsoft Exchange ActiveSync  <br/> |Entrar em cada sessão <sup>1</sup> <br/> |Entrar em cada sessão <sup>2</sup> <br/> |
|POP, IMAP, Outlook para Mac  <br/> |Entrar em cada sessão <sup>1</sup> <br/> |Entrar em cada sessão <sup>2</sup> <br/> |
|Experiências da Web: Office 365 portal/Outlook na Web/SharePoint Online/Office para a Web  <br/> |Entrar em cada sessão do navegador<sup>4</sup> <br/> |Entrar em cada sessão <sup>3</sup> <br/> |
|Office 2010 ou Office 2007 usando SharePoint Online  <br/> |Entrar em cada sessão do SharePoint Online<sup>4</sup> <br/> |Entrar em cada sessão do SharePoint Online<sup>3</sup> <br/> |
|Skype for Business online  <br/> |Entrar em cada sessão <sup>1</sup> <br/> |Nenhum alerta  <br/> |
|Outlook para Mac  <br/> |Entrar em cada sessão <sup>1</sup> <br/> |Entrar em cada sessão <sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> quando solicitado pela primeira vez, você pode salvar sua senha para uso futuro. Você não receberá outra solicitação até alterar a senha. <br/> 
<sup>2</sup> você digita suas credenciais corporativas. Você pode salvar a senha, e não haverá nova solicitação até que a senha seja alterada. <br/> 
<sup>3</sup> todos os aplicativos exigem que você insira ou selecione o nome de usuário para entrar. A senha não será solicitada se o computador estiver associado ao domínio. Se você selecionar **manter-me conectado** , não será solicitado novamente até que você saia. <br/> 
<sup>4</sup> se você selecionar **manter conectado** , não será solicitado novamente até que você saia. 
  
## <a name="creating-user-accounts"></a>Criando contas de usuário

Há várias maneiras de adicionar usuários ao Office 365. Para saber mais, confira [Adicionar usuários individualmente ou em massa ao Office 365-ajuda do administrador](https://docs.microsoft.com/office365/admin/add-users/add-users) e [Adicionar, remover e gerenciar usuários no centro de administração do Microsoft 365](https://support.office.com/article/add-remove-and-manage-users-in-the-new-office-365-admin-center-6e80db58-c36b-4add-b1c8-cc5135f111f3?amp%3Bclcid=0x409&ui=en-US&rs=en-US&ad=US). Se você estiver usando o Office 365 operado pela 21Vianet na China, confira [Criar ou editar contas de usuário no Office 365 operado pela 21Vianet - Ajuda do administrador](https://docs.microsoft.com/office365/admin/add-users/add-users).
  
## <a name="deleting-accounts"></a>Excluindo contas

A maneira de excluir contas depende de se estar usando a sincronização de diretório: 
  
- Se você não estiver usando a sincronização de diretório, as contas podem ser excluídas usando a página de Administração do Office 365 ou usando o Windows PowerShell.
    
- Se você estiver usando a sincronização de diretório, você deve excluir os usuários do Active Directory local, em vez do Office 365.
    
Quando uma conta é excluída, ela se torna inativa. Por um período de aproximadamente 30 dias após ter sido excluída, ainda é possível restaurar a conta. Para obter mais informações sobre como excluir e restaurar contas, consulte [excluir usuários no office 365](https://docs.microsoft.com/office365/admin/add-users/delete-a-user) e [restaurar usuários no Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user) ou, se você estiver usando o Office 365 operado pela 21vianet na China, consulte [create or Edit user accounts in Office 365 operated by 21Vianet-ajuda do administrador](https://docs.microsoft.com/office365/admin/add-users/add-users).
  
## <a name="password-management"></a>Gerenciamento de senhas

As políticas e procedimentos para gerenciamento de senhas dependem do sistema de identidade.
  
 **Gerenciamento de senhas de identidade na nuvem:**
  
Ao utilizar as identidades de nuvem, as senhas são geradas automaticamente quando a conta é criada.
  
- Para requisitos de força da senha da identidade da nuvem, confira [Política de senha](https://docs.microsoft.com/previous-versions/azure/jj943764(v=azure.100)).
    
- Para aumentar a segurança, os usuários devem alterar suas senhas ao acessarem os serviços do Office 365 pela primeira vez. Assim, antes que os usuários possam acessar os serviços do Office 365, eles devem entrar no portal do Office 365, onde serão solicitados a alterar suas senhas.
    
- Administradores podem definir a política de expiração de senha. Confira mais informações em [Definir uma política de expiração de senha do usuário](https://docs.microsoft.com/office365/admin/manage/set-password-expiration-policy).
    
Existem várias ferramentas para redefinir senhas de usuários com identidades da nuvem:
  
- **O administrador redefine a senha** Se os usuários perderem ou esquecerem suas senhas, os administradores podem redefinir as senhas dos usuários no portal do Office 365 ou usando o Windows PowerShell. Os usuários poderão alterar suas senhas apenas se souberem suas senhas antigas. 
    
    Para planos corporativos, se os administradores perderem ou esquecerem suas senhas, um administrador diferente com a função de administrador global poderá redefinir as senhas dos administradores no centro de administração do Microsoft 365 ou usando o Windows PowerShell. Para saber mais, confira [Redefinir senhas para administradores](https://docs.microsoft.com/office365/admin/add-users/reset-passwords). Se você estiver trabalhando no Office 365 operado pela 21Vianet na China, confira [Alterar ou redefinir senhas no Office 365 operado pela 21Vianet](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b).
    
- O **usuário altera as senhas com o Outlook na Web** A página Opções do Outlook na Web inclui um hiperlink alterar senha, que redireciona os usuários para a página **alterar senha** . O usuário deve saber sua senha anterior. Para saber mais, confira [Alterar senha](https://support.office.com/article/change-password-in-outlook-web-app-50bb1309-6f53-4c24-8bfd-ed24ca9e872c). Se você estiver usando o Office 365 operado pela 21Vianet na China, confira [Alterar ou redefinir senhas no Office 365 operado pela 21Vianet](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b).
    
- **Direitos de redefinir senha com base em função** Para planos Corporativos, usuários autorizados, como a equipe do suporte técnico, podem receber o direito de usuário **Redefinir Senha** e o direito de alterar senhas usando funções predefinidas ou personalizadas do Office 365 sem se tornarem administradores de serviços completos. Por padrão, em planos Corporativos, os administradores com a função Administrador Global, Administrador de Senha ou Administrador de Gerenciamento de Usuário podem alterar senhas. Para saber mais, veja [Atribuindo funções de administrador](https://docs.microsoft.com/office365/admin/add-users/assign-admin-roles).
    
- **Redefinir senhas usando o Windows PowerShell** Os administradores de serviços podem usar o Windows PowerShell para redefinir senhas. 
    
 **Gerenciamento de senhas de identidade federada:**
  
Ao usar identidades federadas, as senhas são gerenciadas no Active Directory. O serviço de token de segurança local negocia a autenticação com o gateway de Federação do Office 365 sem passar as senhas locais do Active Directory dos usuários pela Internet para o Office 365. As políticas de senha locais são usadas ou, para clientes web, identificação de dois fatores. O Outlook na Web não inclui um hiperlink alterar senha. Os usuários podem alterar suas senhas usando ferramentas padrão, no local ou através das opções de logon de seu PC desktop.
  
Se você tiver a [Sincronização de Diretórios com SSO (logon único)](https://docs.microsoft.com/previous-versions/azure/azure-services/dn441213(v=azure.100)) habilitada no seu ambiente do Office 365 e houver uma interrupção que afete o seu provedor de identidade federado, o Backup de Sincronização de Senha para Entrada Federada oferece a opção de alterar manualmente seu domínio para a Sincronização de Senha. O uso da Sincronização de Senha permitirá que seus usuários acessem o Office 365 enquanto a interrupção é solucionada. Saiba [como alternar do Logon Único para a Sincronização de Senha](https://go.microsoft.com/fwlink/p/?LinkId=509832).
  
## <a name="license-management"></a>Gerenciamento de licenças

Uma licença do Office 365 fornece ao usuário acesso a um conjunto de serviços do Office 365. Um administrador atribui a cada usuário uma licença para o serviço para o qual ele precisa de acesso. Por exemplo, você pode atribuir a um usuário acesso para o Skype for Business online, mas não para o SharePoint Online.
  
Os administradores de cobrança do Office 365 podem fazer alterações em detalhes da assinatura, como o número de licenças e número de serviços adicionas que a sua empresa usa. Confira [Atribuir ou remover licenças no Office 365](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users). Se você estiver usando o Office 365 operado pela 21Vianet, confira [Atribuir ou remover licenças no Office 365 operado pela 21Vianet](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users).
  
## <a name="group-management"></a>Gerenciamento de grupos

Os grupos de segurança são usados no SharePoint Online para controlar o acesso aos sites. Os grupos de segurança podem ser criados no centro de administração do Microsoft 365. Para saber mais sobre grupos de segurança, confira [Criar, editar ou excluir um grupo de segurança](https://docs.microsoft.com/office365/admin/email/create-edit-or-delete-a-security-group).
  
## <a name="administrator-roles"></a>Funções de administrador

O Office 365 Enterprise segue um modelo RBAC (controle de acesso baseado em função): as permissões e capacidades são definidas pelas funções de gerenciamento. A pessoa que assina o Office 365 para sua organização se torna automaticamente um administrador global ou administrador de nível superior. Existem cinco funções de administrador: administrador global, administrador de cobrança, administrador de senhas, administrador de serviço e administrador de gerenciamento de usuário. Para saber mais sobre funções de administrador no Office 365 Enterprise, incluindo como elas se aplicam à administração do Exchange Online, do SharePoint Online e do Skype for Business online, confira [Atribuindo funções de administrador](https://docs.microsoft.com/previous-versions/windows/it-pro/windows-server-2012-R2-and-2012/jj878348(v=ws.11)). Se você estiver usando o Office 365 operado pela 21Vianet na China, confira [Atribuir funções de administrador no Office 365 para empresas](https://docs.microsoft.com/office365/admin/add-users/assign-admin-roles).
  
## <a name="delegated-administration-and-support-for-partners"></a>Suporte para parceiros e administração delegada

Parceiros podem ser autorizados a administrar contas em nome de clientes. O cliente não requer uma conta de usuário para o uso de parceiros e não utiliza uma licença do Office 365 quando conceder autoridade de administração delegada. Parceiros podem atribuir acesso completo ou limitado a usuários dentro de sua organização. Acesso limitado inclui direitos para redefinir senhas, gerenciar solicitações de serviço e monitorar a integridade do serviço. 
  
> [!NOTE]
> A capacidade de usar e especificar um parceiro como administrador delegado varia de acordo com a região. 
  
## <a name="azure-active-directory-services"></a>Serviços do Azure Active Directory

O Active Directory (AD) do Azure oferece recursos abrangentes de gerenciamento de identidade e acesso ao Office 365. Ele combina os serviços de diretório, gerenciamento avançado de identidades, gerenciamento de acesso a aplicativos e uma plataforma avançada baseada em padrões para os desenvolvedores. Para saber mais sobre os recursos do AD no Office 365, confira [Identidade visual da página de login e redefinição da senha de autoatendimento do usuário da nuvem](https://blogs.office.com/2015/02/17/sign-page-branding-cloud-user-self-service-password-reset-office-365/). Saiba mais sobre as [Edições Gratuita, Basic e Premium do Azure Active Directory](https://msdn.microsoft.com/library/azure/dn532272.aspx). 
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos nos planos do Office 365, nas opções autônomas e nas soluções locais, consulte [Descrição do serviço da plataforma do office 365](office-365-platform-service-description.md).
  
