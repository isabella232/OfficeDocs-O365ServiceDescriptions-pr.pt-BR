---
title: Office 365 US Government
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 3f482abc-993f-41bf-8754-0f489a7e4861
description: Em resposta aos requisitos únicos e em evolução do setor público dos Estados Unidos, a Microsoft criou planos do Office 365 para o Governo norte-americano (ou Office 365 Government). Este artigo fornece uma visão geral dos recursos específicos para Office 365 Government ambientes dos EUA.
ms.openlocfilehash: a1c5ed6e166ec3a893c716e5de18e9bc81a3865f
ms.sourcegitcommit: adcacf68ac75c4db2229ebf55be9c75aecd3070b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52545928"
---
# <a name="office-365-government"></a>Office 365 Government

> [!IMPORTANT]
> Microsoft Teams está experimentando um tremendo pico de chamadas online e conferência de áudio/vídeo devido à pandemia coronavírus (COVID-19).<br/>
>
>Em resposta ao aumento sem precedentes de chamadas e para garantir a continuidade e a disponibilidade, a Microsoft está permitindo que Microsoft Teams GCC servidores de áudio/vídeo aproveitem a capacidade de processamento em nossos data centers comerciais, bem como em nossos data centers governamentais.<br/>
>
>Esses servidores de áudio/vídeo residem dentro do Microsoft Azure servidores de limite de credenciamento FedRAMP High nos Estados Unidos e não armazenam qualquer conteúdo do cliente. No entanto, esses servidores estão processando áudio e vídeo para chamadas e conferências e estão operando sob nossa equipe comercial durante este período provisório.<br/>
>
>Pessoal qualificado e selecionado está monitorando esses servidores para acesso potencial aos dados dos clientes, revisando quaisquer log-ons interativos nesses servidores. Pessoal qualificado atende GCC requisitos para acesso ao conteúdo do cliente. Para obter detalhes sobre os requisitos de triagem, consulte a [descrição do serviço GCC](gcc.md).<br/>
>
>Obrigado por seu apoio à medida que tomamos medidas para garantir que nossos serviços permaneçam disponíveis e confiáveis nestes tempos extraordinários.<br/>

Em resposta aos requisitos únicos e em evolução do setor público dos Estados Unidos, a Microsoft criou planos Office 365 Government (ou Office 365 Government). Esta descrição do serviço fornece uma visão geral dos recursos específicos para Office 365 Government ambientes dos EUA. Recomendamos que você leia esta descrição do serviço juntamente com [outras descrições de serviços Microsoft 365 e Office 365](../../office-365-service-descriptions-technet-library.md).

## <a name="how-to-use-this-service-description"></a>Como usar a descrição deste serviço

A descrição do serviço Office 365 Government foi projetada para servir como uma sobreposição à descrição geral do serviço Office 365. Ela define as diferenças e os compromissos exclusivos em comparação com as ofertas do Office 365 Enterprise.

## <a name="about-office-365-government-environments"></a>Sobre Office 365 Government ambientes

Office 365 Government planos são assinaturas mensais e podem ser licenciados para um número ilimitado de usuários.

- O **ambiente Office 365 GCC** fornece o cumprimento dos requisitos federais para serviços em nuvem, incluindo o FedRAMP High, e requisitos para a justiça criminal e sistemas federais de informações fiscais (tipos de dados CJI e FTI).

- Os **ambientes Office 365 GCC de Alta e DoD** fornecem conformidade com as Diretrizes de Requisitos de Segurança do Departamento de Defesa, O Suplemento de Regulamentos federais de aquisição de defesa (DFARS) e regulamentos internacionais de tráfego em armas (ITAR).

Além dos recursos e capacidades de Office 365, as organizações que usam Office 365 Government se beneficiam dos seguintes recursos exclusivos para Office 365 Government:

- O conteúdo do cliente de sua organização é logicamente separado do conteúdo dos Serviços do Office 365 do cliente comercial da Microsoft.

- O conteúdo do cliente da sua organização é armazenado dentro dos Estados Unidos.

- O acesso ao conteúdo do cliente da sua organização é restrito à equipes selecionadas da Microsoft.

- Office 365 Government cumpre as certificações e credenciamentos necessários para os clientes do setor público dos EUA.

## <a name="customer-eligibility"></a>Qualificação do cliente

Office 365 Government está disponível para (1) entidades governamentais federais, estaduais, locais, tribais e territoriais dos EUA, e (2) outras entidades que lidam com dados sujeitos a regulamentos e requisitos governamentais e quando o uso de Office 365 Government é apropriado para atender a esses requisitos, sujeitos à validação da elegibilidade. A validação de qualificação feita pela Microsoft incluirá a confirmação da manipulação de dados sujeitos ao ITAR (International Traffic in Arms Regulations), dados para a aplicação da lei sujeitos à política do Criminal Justice Information Services (CJIS) do FBI ou outros dados controlados ou regulamentados pelo governo. A validação poderá exigir a prova do registro no Departamento de Estado dos Estados Unidos para os dados do ITAR ou o aval de uma entidade governamental com requisitos específicos para a manipulação de dados. O ambiente Office 365 DoD é para uso exclusivo do Departamento de Defesa dos Estados Unidos.

Embora os critérios de elegibilidade sejam consistentes em todas as ofertas Office 365 Government, a Microsoft só concordará com a linguagem de contrato DFARS e ITAR para o ambiente GCC High.

As entidades com dúvidas sobre elegibilidade para Office 365 Government devem consultar sua equipe de conta.

Após a renovação do contrato de um cliente para Office 365 Government, é necessária a revalidação da elegibilidade.

## <a name="customer-content-located-within-the-united-states"></a>Conteúdo de cliente localizado nos Estados Unidos

Office 365 Government serviços são fornecidos a partir de data centers fisicamente localizados nos Estados Unidos. O seguinte conteúdo de cliente é armazenado em repouso em datacenters fisicamente localizados apenas nos EUA:

- Exchange Online conteúdo da caixa de correio (corpos de e-mail, entradas de calendário e o conteúdo de anexos de e-mail)

- SharePoint Conteúdo do site online e os arquivos armazenados dentro desse site

- Skype for Business conversas arquivadas, documentos enviados e sessões de whiteboarding

- Microsoft Teams tópicos de bate-papo persistentes

> [!NOTE]
> Normalmente, o Skype for Business não armazena conteúdo de clientes, mas se ocorrer algum armazenamento, ele será feito em datacenters nos EUA.

Se seus usuários estiverem localizados dentro dos EUA enquanto usam Office para a web (anteriormente conhecido como Office Web Apps) ou se você adotar o uso do Active Directory Federation Services (AD FS) 2.0 e configurar políticas para ajudar a garantir que seus usuários se conectem aos serviços através de login único, qualquer conteúdo do cliente que seja temporariamente armazenado em Office para a web será localizado nos EUA.

A página de uso do Site para sites SharePoint está disponível para planos governamentais, embora por conformidade, existem alguns recursos desta página que estão disponíveis apenas para clientes comerciais. Para saber mais, consulte a [página de uso do Site para sites SharePoint em Microsoft 365](https://support.microsoft.com/office/2fa8ddc2-c4b3-4268-8d26-a772dc55779e).

## <a name="office-365-government-and-third-party-services"></a>Office 365 Government e serviços de terceiros

Office 365 fornece a capacidade de integrar aplicativos de terceiros em sites SharePoint Online, Skype for Business Office aplicativos incluídos em Microsoft 365 Apps para Grandes Empresas (como Word, Excel, PowerPoint e Outlook) e Outlook Web App. Além disso, o Office 365 suporta a integração com provedores de serviços de terceiros. Estes aplicativos e serviços de terceiros podem envolver o armazenamento, a transmissão e o processamento dos dados de cliente da sua organização em sistemas de terceiros que estão localizados fora da infraestrutura do Office 365 e, portanto, não são cobertos pelos compromissos de conformidade e proteção de dados do Office 365. Recomendamos que você analise as instruções de privacidade e conformidade fornecidas por terceiros quando estiver avaliando o uso apropriado destes serviços para sua organização.

## <a name="restricted-data-access-by-administrators"></a>Acesso restrito aos dados pelos administradores

O acesso ao Office 365 Government conteúdo do cliente pelos administradores da Microsoft é restrito ao pessoal selecionado. Para obter detalhes dos níveis de triagem, consulte a página de descrição do serviço para cada ambiente respectivo (GCC ou GCC High e DoD).

## <a name="fasttrack-center-onboarding-assistance"></a>Assistência de onboarding do FastTrack Center

Com o FastTrack Center Benefit for Office 365<sup>1</sup>, você trabalha remotamente com especialistas em FastTrack para deixar seu ambiente Office 365 pronto para uso e planejar o lançamento e o uso dentro de sua organização. O processo FastTrack oferece integração e serviços de adoção do usuário. 

A integração consiste em:

- Onboarding principal - São tarefas necessárias para a configuração e integração do inquilino com Azure Active Directory (Azure AD) se necessário. A integração básica também fornece a linha de base para integração de outros serviços qualificados.

- Onboarding e migração de serviços - Tarefas de onboarding de serviço permitem cenários em seu inquilino. A migração de dados (incluindo e-mail e arquivos) é coberta pela [Migração de Dados](/FastTrack/data-migration). <sup>2</sup>

Os serviços de adoção do usuário são compostos por tarefas que fornecem orientações para que você garanta que seus usuários estejam cientes dos serviços elegíveis e possam usá-los para impulsionar o valor dos negócios. Esta assistência ocorre paralelamente às atividades de integração.

Informações específicas sobre o processo FastTrack Center podem ser encontradas [aqui.](/FastTrack/us-gov-appendix-overview) Para uma divisão de funções e responsabilidades de engajamento, revise [as responsabilidades do FastTrack,](/FastTrack/us-gov-appendix-fasttrack-responsibilities) bem como [suas responsabilidades.](/FastTrack/us-gov-appendix-your-responsibilities)

> <sup>1</sup> Você deve comprar pelo menos 50 licenças da lista dos [planos elegíveis](/fasttrack/eligibility) para receber os serviços FastTrack.
<br/><sup>2</sup> Os serviços de migração de dados estão disponíveis para Office 365 inquilinos com 500 ou mais licenças.

## <a name="data-migrations-performed-by-fasttrack"></a>Migrações de dados realizadas pelo FastTrack

Os clientes que optarem pelo benefício de migração do [FastTrack](https://fasttrack.microsoft.com/) precisarão conceder acesso à equipe que gerencia suas migrações de dados. Esses funcionários são cidadãos dos EUA e passam pelas seguintes verificações de antecedentes antes de realizar migrações para clientes de Office 365 serviços do governo dos EUA.<br><br>

|Triagem de antecedentes|CCG|GCC alto e DoD|
|---|---|---|
|Verificação da cidadania dos EUA|Sim|Sim|
|Verificação do histórico de emprego|Sim|Sim|
|Verificação da educação|Sim|Sim|
|Pesquisa do número da Previdência Social (SSN)|Sim|Sim|
|Verificação de antecedentes criminais (7 anos)|Sim|Sim|

## <a name="office-365-us-government-and-azure-government-expressroute"></a>Office 365 US Government e Microsoft Azure Government ExpressRoute

Office 365 Os clientes do governo dos EUA podem usar os serviços do Azure Government ExpressRoute para se conectar privadamente a serviços de Office 365 suportados em vez de se conectar pela internet pública.

Para obter detalhes, como provedores suportados, modelos de preços e muito mais, revise as informações do [Azure ExpressRoute](/azure/expressroute/).

Para obter detalhes sobre Office 365 suporte ao Azure ExpressRoute, consulte [Azure ExpressRoute para Office 365](/microsoft-365/enterprise/azure-expressroute)

## <a name="system-requirements"></a>Requisitos do sistema

Para requisitos de sistema dos planos do Office 365 US Government, confira [Requisitos de sistema do Office](https://go.microsoft.com/fwlink/?LinkID=626095&amp;clcid=0x409) no site de produtos do [office.com](https://go.microsoft.com/fwlink/?LinkID=509817&amp;clcid=0x409).

## <a name="security-amp-compliance-center"></a>Security &amp; Compliance Center

Para obter informações sobre o Centro de Conformidade de Segurança &amp; e links para informações adicionais e disponibilidade, consulte o Security Compliance [ &amp; Center](../../office-365-platform-service-description/office-365-securitycompliance-center.md).

## <a name="service-availability-for-each-plan"></a>Disponibilidade do serviço para cada plano

Cada plano do Office 365 inclui alguns serviços individuais, como o Exchange Online e o SharePoint Online. A tabela a seguir mostra os serviços disponíveis em cada plano do Office 365 US Government.<br><br>

|Serviço do Office 365|Office 365 Government G1|Office 365 Government G3|Office 365 Government G5|Office 365 Government F3|
|---|---|---|---|---|
|Office na Web|Sim|Sim|Sim|Sim|
|Microsoft 365 Apps para Grandes Empresas|Não|Sim|Sim|Não|
|Exchange Online|Sim|Sim|Sim|Sim|
|Proteção do Exchange Online|Sim|Sim|Sim|Sim|
|SharePoint Online|Sim|Sim|Sim|Sim|
|OneDrive for Business|Sim|Sim|Sim|Sim|
|Skype for Business (Instant Messaging &amp; Presence)|Sim<sup>1</sup>|Sim|Sim|Sim<sup>1</sup>|
|Voz - Sistema de Telefonia, AudioConferência|Não<sup>2</sup>|Não<sup>2</sup>|Sim<sup>5</sup>|Não|
|Power BI Pro|Não<sup>2</sup>|Não<sup>2</sup>|Sim|Não<sup>2</sup>|
|Project Online|Não<sup>2</sup>|Não<sup>2</sup>|Não<sup>2</sup>|Não<sup>2</sup>|
|Visio para a Web|Não<sup>6</sup>|Não<sup>6</sup>|Não<sup>6</sup>|Não<sup>6</sup>|
|Yammer Enterprise|Não<sup>4</sup>|Não<sup>4</sup>|Não<sup>4</sup>|Não<sup>4</sup>|

> <sup>1</sup> Skype for Business Basic está disponível para todos os clientes. O cliente de desktop do Skype for Business é um aplicativo instalado localmente que fornece recursos de presença, mensagens instantâneas e conferências para planos do Office 365 que incluem o Skype for Business online. Microsoft 365 Apps para Grandes Empresas, G3 e G5 incluem o aplicativo de Skype completo, que inclui recursos adicionais, como suporte avançado de telefonia, arquivamento e recursos de conformidade. A Skype for Business Online license must be assigned for each user.
<br/><sup>2</sup> Não incluído, mas pode ser comprado como um complemento separado. Project Online inclui Project Online Cliente de Desktop como parte da assinatura.
<br/> <sup>3</sup> Ainda não disponível nos planos GCC High ou DoD, mas em breve.
<br/><sup>4</sup> Yammer Enterprise não é um componente do governo dos EUA Office 365, mas pode ser adquirida sem custo como uma oferta autônoma para cada usuário licenciado para Office 365 em GCC. Atualmente, essa oferta está limitada aos clientes que compram Office 365 GCC sob Enterprise Acordos e Enterprise Contratos de Assinatura. Yammer não está disponível em GCC High ou DoD.
<br/><sup>5</sup> O plano de chamada é um complemento.
<br/><sup>6</sup> Não incluído, mas pode ser comprado como um complemento separado. Visio para a web inclui o aplicativo de desktop Visio como parte da assinatura.

## <a name="platform-features"></a>Recursos da plataforma 

A tabela a seguir exibe os recursos e serviços da plataforma que estão disponíveis nos planos do Office 365 US Government.<br><br>

|Recurso|Office 365 Government G1|Office 365 Government G3|Office 365 Government G5|Office 365 Government F3|
|---|---|---|---|---|
|**Administração do Office 365**|||||
|Use o centro administrativo de Microsoft 365 para administrar Office 365|Sim,<sup>16.</sup>|Sim,<sup>16.</sup>|Sim|Sim,<sup>16.</sup>|
|Gerenciar as configurações de serviço principal do Office 365|Sim|Sim|Sim|Sim|
|Usar o Windows PowerShell para gerenciar Office 365|Sim|Sim|Sim|Sim|
|Proteger o conteúdo usando a Proteção de Informações do Azure|Não<sup>1</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Não<sup>1</sup>|
|**[Recursos do Pacote do Office 365](../../office-365-platform-service-description/office-365-suite-features.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|Microsoft Bookings|Não|Sim,<sup>21.</sup>|Sim,<sup>21.</sup>|Não|
|E-mail do Microsoft Briefing|Não|Não|Não|Não|
|Microsoft Power Automate|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|
|Microsoft Forms|Sim|Sim|Sim<br/>|Sim</sup>|
|API do Microsoft Graph|Sim|Sim|Sim|Sim|
|Microsoft MyAnalytics|Não|Não|Sim,<sup>17.</sup>|Não|
|Microsoft Planner|Sim|Sim|Sim|Sim|
|Microsoft PowerApps|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|
|Microsoft StaffHub|Não|Não|Não|Não<br/>|
|Microsoft Stream|Sim<sup>9, 15</sup>|Sim<sup>9, 15</sup>|Sim<sup>9, 15</sup>|Sim<sup>9, 15, 20</sup>|
|Microsoft Sway|Não|Não|Não|Não|
|Microsoft Teams|Sim|Sim|Sim|Sim|
|Office Delve|Sim,<sup>17.</sup>|Sim,<sup>17.</sup>|Sim|Sim,<sup>17.</sup>|
|Grupos do Office 365|Sim|Sim|Sim|Sim|
|**[Gerenciamento de contas de usuário](../../office-365-platform-service-description/user-account-management.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|Identidade de nuvem|Sim|Sim|Sim|Sim|
|Identidade federada (logon único)|Sim|Sim|Sim|Sim|
|Autenticação multifator|Sim|Sim|Sim|Sim|
|autenticação de fator Telefone|Sim<sup>9</sup>|Sim<sup>9</sup>|Sim|Sim<sup>9</sup>|
|Configuração de área de trabalho do Office 365|Sim|Sim|Sim|Sim|
|Gerenciar usuários com o Office 365|Sim|Sim|Sim|Sim|
|Upload em massa usando arquivos .csv|Sim<sup>9</sup>|Sim<sup>9</sup>|Sim|Sim<sup>9</sup>|
|Ferramenta de Sincronização de Diretórios|Sim|Sim|Sim|Sim|
|Migração simples (substituição) do Exchange|Sim|Sim|Sim|Sim|
|Excluir contas usando o Office 365|Sim<sup>3</sup>|Sim<sup>3</sup>|Sim<sup>3</sup>|Sim<sup>3</sup>|
|O administrador pode redefinir a senha de usuário no Office 365 ou usando o Windows PowerShell|Sim<sup>4</sup>|Sim<sup>4</sup>|Sim<sup>4</sup>|Sim<sup>4</sup>|
|Os usuários podem alterar sua própria senha|Sim<sup>5</sup>|Sim<sup>5</sup>|Sim<sup>5</sup>|Sim<sup>5</sup>|
|Gerenciar licenças|Sim<sup>7, 8</sup>|Sim<sup>7, 8</sup>|Sim<sup>7, 8</sup>|Sim<sup>7,8</sup>|
|Gerenciar grupos de segurança do Office 365|Sim|Sim|Sim|Sim|
|Várias funções de administrador disponíveis|Sim|Sim|Sim|Sim|
|Permitir que um parceiro administre o Office 365 para você|Sim,<sup>11.</sup>|Sim,<sup>11.</sup>|Sim,<sup>11.</sup>|Sim,<sup>11.</sup>|
|Serviços do Azure Active Directory|Sim|Sim|Sim|Sim|
|**[Domínios](../../office-365-platform-service-description/domains.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|Adicionar domínios de segundo nível personalizados, como fourthcoffee.com|Sim|Sim|Sim|Sim|
|Adicionar domínios de terceiro nível personalizados, como marketing.fourthcoffee.com|Sim|Sim|Sim|Sim|
|Adicionar até 900 domínios personalizados|Sim|Sim|Sim|Sim|
|Verificação de propriedade de domínio necessária para domínios personalizados|Sim|Sim|Sim|Sim|
|**[Saúde e continuidade do serviço](../../office-365-platform-service-description/service-health-and-continuity.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|Informação de status disponível na página **Integridade do serviço** ou **Status do serviço**|Sim<sup>9, 15</sup>|Sim<sup>9, 15</sup>|Sim<sup>9, 15</sup>|Sim<sup>9, 15</sup>|
|Status dos alertas individuais disponíveis no painel central de administração Microsoft 365|Sim<sup>9, 15</sup>|Sim<sup>9, 15</sup>|Sim<sup>9, 15</sup>|Sim<sup>9, 15</sup>|
|RSS feed de **Integridade do serviço**|Sim|Sim|Sim|Sim|
|**[Relatórios](../../office-365-platform-service-description/reports.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|Caixas postais ativas e inativas|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|
|Caixas de correio novas e excluídas|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|
|Grupos novos e excluídos|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|
|Uso da caixa de correio|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|
|Tipos de conexões da caixa de correio|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|
|Emails enviados e recebidos|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|
|Principais remetentes e destinatários|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|
|Detecções de spam|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|
|Detecções de malware|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|
|Principal malware para email|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|
|Correspondências de regra para email|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|
|Principais correspondências de regra para email|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|
|Principais correspondências de política DLP para email|Não|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Não|
|Correspondências de política DLP por gravidade para email|Não|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Não|
|Correspondências, substituições e falsos positivos de política DLP para email|Não|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Não|
|Principais correspondências de regra DLP para email|Não|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Não|
|Sessões de mensagens instantâneas e áudio|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|
|Compartilhamento de aplicativos, Webconferência e conferência discada|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|
|Vídeo, compartilhamento de aplicativos e sessões de transferência de arquivos|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|
|Mensagens instantâneas e conferências de áudio/vídeo|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|
|Relatórios de proteção de email para download|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|
|Navegador usado|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|
|Sistema operacional usado|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|
|Crie seus próprios relatórios usando Microsoft 365 relatórios web|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|
|**[Atualizações de serviço](../../office-365-platform-service-description/service-updates.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|Atualizações regulares fornecidas a todos os clientes|Sim|Sim|Sim|Sim|
|Notificações enviadas para o Centro de Mensagens quando uma ação é necessária|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|Sim,<sup>15.</sup>|
|Success.office.com/pt-br/roadmap para alguns serviços updates|Não<sup>10, 13</sup>|Não<sup>10, 13</sup>|Não<sup>10, 13</sup>|Não<sup>10, 13</sup>|
|Opção para ativar a versão direcionada|Sim,<sup>10.</sup>|Sim,<sup>10.</sup>|Sim,<sup>10.</sup>|Sim,<sup>10.</sup>|
|**[Ajuda e treinamento](../../office-365-platform-service-description/help-and-training.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|Ajuda online|Sim|Sim|Sim|Sim|
|Comunidade|Sim|Sim|Sim|Sim|
|Outros recursos de autoajuda|Sim|Sim|Sim|Sim|
|Treinamento individual|Sim|Sim|Sim|Sim|
|**[Sistema de rede](../../office-365-platform-service-description/networking.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|Protocolos IPv4 e IPv6|Sim|Sim|Sim|Sim|
|**Confiança**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|**[Privacidade, segurança e transparência](../../office-365-platform-service-description/privacy-security-and-transparency.md)**|||||
|Advanced Data Governance|Não<sup>12</sup>|Não<sup>12</sup>|Sim|Não<sup>12</sup>|
|Segurança no Aplicativo na Nuvem|Não<sup>12, 19</sup>|Não<sup>12, 19</sup>|Sim,<sup>19.</sup>|Não<sup>12, 19</sup>|
|Microsoft Defender para Office 365|Não<sup>12, 18</sup>|Não<sup>12, 18</sup>|Sim,<sup>18.</sup>|Não<sup>12, 18</sup>|
|Sistema de Proteção de Dados do cliente|Não<sup>12</sup>|Não<sup>12</sup>|Sim|Não<sup>12</sup>|
|Descoberta Eletrônica Avançada|Não<sup>12</sup>|Não<sup>12</sup>|Sim|Não<sup>12</sup>|
|Pontuação segura<sup>14</sup>|Sim<sup>9, 15</sup>|Sim<sup>9</sup>|Sim<sup>9, 15</sup>|Sim<sup>9, 15</sup>|
|Office Criptografia de mensagens|Não|Sim|Sim|Não|
|Inteligência contra Ameaças|Não<sup>12</sup>|Não<sup>12</sup>|Sim|Não<sup>12</sup>|
|**[Conformidade](/microsoft-365/compliance/offering-home)**|||||
|Avaliações SAS 70 / SSAE16|Sim|Sim|Sim|Sim|
|Certificado ISO 27001|Sim|Sim|Sim|Sim|
|Cláusulas do modelo da UE|Sim|Sim|Sim|Sim|
|Safe Harbor da UE|Sim|Sim|Sim|Sim|
|HIPAA-Contrato de Associado de Negócios|Sim|Sim|Sim|Sim|
|Autoridade FISMA para Operar|Sim|Sim|Sim|Sim|
|Acordo de processamento de dados da Microsoft|Sim|Sim|Sim|Sim|
|PCI DSS nível um|Sim|Sim|Sim|Sim|
|Dados de PAN controlados por PCI|Não|Não|Não|Não|
|**[Continuidade do serviço](../../office-365-platform-service-description/service-health-and-continuity.md)**|Sim|Sim|Sim|Sim|
|**[BlackBerry](../../office-365-platform-service-description/blackberry.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|Usar BIS (BlackBerry Internet Service)|Não<sup>2</sup>|Não<sup>2</sup>|Não<sup>2</sup>|Não<sup>2</sup>|
|**[Parceiros](../../office-365-platform-service-description/partners.md)**|||||
|Criar convites para avaliação e ordens de compra para um cliente que está usando o plano especificado|Não<sup>11</sup>|Não<sup>11</sup>|Não<sup>11</sup>|Não<sup>11</sup>|
|Fornecer administração delegada|Não<sup>11</sup>|Não<sup>11</sup>|Não<sup>11</sup>|Não<sup>11</sup>|
|**[Contrato de Nível de Serviço](../../office-365-platform-service-description/service-level-agreement.md)**|Sim|Sim|Sim|Sim|
|**[Direitos de uso do produto](../../office-365-platform-service-description/product-use-rights.md)**|Sim|Sim|Sim|Sim|

> <sup>1</sup> A Proteção de Informações do Azure não está incluída, mas pode ser comprada como um complemento separado e permitirá os recursos de IRM (Information Rights Management, gerenciamento de direitos de informação) suportados. Alguns recursos de Proteção de Informações do Azure exigem uma assinatura de Microsoft 365 Apps para Grandes Empresas, que não está incluída em Office 365 Government G1 ou Office 365 Government F3. >
<br/><sup>2</sup> Os clientes existentes da BBCS e bis podem continuar usando o serviço. No momento, não aceitamos novos clientes.
<br/><sup>3</sup> Se usar a sincronização do diretório, você deve excluir contas ou alterar senhas usando o Active Directory, em vez do portal Office 365 ou usando o módulo Azure Active Directory para Windows PowerShell.
<br/><sup>4</sup> Se usar a sincronização de senhas, os usuários devem alterar suas senhas no Active Directory local.
<br/><sup>5</sup> Para saber como definir políticas de gerenciamento de senhas de autoatendimento para usuários, consulte [Gerenciar senhas no Azure AD](/azure/active-directory/user-help/active-directory-passwords-update-your-own-password).
<br/><sup>6</sup> Você pode ter apenas um site público com Office 365, a menos que tenha atualizado de uma versão anterior de Office 365. Nesse caso, é possível ter dois sites públicos, mas somente um deles pode ser hospedado com um nome de domínio personalizado. Para obter mais informações sobre como trabalhar com os dois sites para assinaturas de Negócios, consulte [Trabalhar com seus dois Office 365 sites públicos](https://go.microsoft.com/fwlink/p/?LinkID=271589). Se você tem uma assinatura diferente, saiba mais sobre sites públicos em [Aprender sobre hospedagem de sites parceiros e sites públicos em Office 365](https://go.microsoft.com/fwlink/p/?LinkID=325009).
<br/><sup>7</sup> A redução de assentos que foram comprados com desconto a prazo pode estar sujeita a uma taxa de rescisão antecipada. Isso não é aplicável a assinaturas pagas mensalmente.
<br/><sup>8</sup> Os seguintes planos não suportam alterações de assentos de licença do centro administrativo Microsoft 365: Office 365 Government G1, Office 365 Government G3, Office 365 Government F3.
<br/><sup>9</sup> Ainda não está disponível em GCC High, mas em breve.
<br/><sup>10</sup> Para Office 365 Government G1, G3 e F3, a liberação direcionada e o Office 365 para o roteiro de negócios se aplicam; no entanto, pode haver algumas diferenças ou atrasos para atualizações específicas de serviços devido aos requisitos de [conformidade.](https://www.microsoft.com/trust-center)
<br/><sup>11</sup> Ainda não disponível em Office 365 Government ofertas, mas em breve.
<br/><sup>12</sup> Não incluído, mas pode ser comprado como um complemento separado em GCC.
<br/><sup>13</sup> Não é suportado para ofertas de Office 365 Government.
<br/><sup>14</sup> Disponível em [https://securescore.office.com](https://securescore.office.com) . Requer permissões de administrador. Saiba mais em [Apresentando a Classificação de Segurança do Office 365](/microsoft-365/security/mtp/microsoft-secure-score).
).
<br/><sup>15</sup> Ainda não disponível no ambiente DoD, mas em breve.
<br/><sup>16</sup> O centro administrativo não inclui análises de uso em ambientes DoD ou GCC High.
<br/><sup>17</sup> Não suportado para ambientes GCC alto ou doD.
<br/><sup>18</sup> O anti-phishing para imitação de usuário e domínio e inteligência falsa ainda não estão disponíveis em GCC High e DoD.
<br/><sup>19</sup> Ainda não disponível em GCC ambiente, mas em breve.
<br/><sup>20</sup> Consumo apenas para o Microsoft Stream: sem publicação ou compartilhamento.
<br/><sup>21</sup> Não disponível para a API ou Microsoft Teams microsoft Graph.

## <a name="office-application-availability-and-enterprise-value"></a>Office disponibilidade de aplicativos e valor corporativo

A tabela a seguir mostra os recursos do aplicativo do Office que estão disponíveis nos planos do Office 365 US Government.<br><br>

|Aplicativo/recurso|Office 365 Government G1|Office 365 Government G3|Office 365 Government G5|Office 365 Government F3|
|---|---|---|---|---|
|**Aplicativos do Office**|||||
|[Microsoft Word](../../office-applications-service-description/office-applications.md#microsoft-word)<sup>7</sup>|Não|Sim|Sim|Não|
|[Microsoft Excel](../../office-applications-service-description/office-applications.md#microsoft-excel)<sup>7</sup>|Não|Sim|Sim|Não|
|[Microsoft PowerPoint](../../office-applications-service-description/office-applications.md#microsoft-powerpoint)<sup>7</sup>|Não|Sim|Sim|Não|
|[Microsoft OneNote](../../office-applications-service-description/office-applications.md#microsoft-onenote)<sup>7</sup>|Não|Sim|Sim|Não|
|[Microsoft Outlook](../../office-applications-service-description/office-applications.md#microsoft-outlook)<sup>7</sup>|Não|Sim|Sim|Não|
|Formulários Microsoft<sup>7</sup>|Sim|Sim <br/>|Sim|Não|
|Microsoft Whiteboard<sup>7</sup>|Não|Sim|Sim|Não|
|[Microsoft Publisher](../../office-applications-service-description/office-applications.md#microsoft-publisher)|Não|Sim|Sim|Não|
|[Microsoft Access](../../office-applications-service-description/office-applications.md#microsoft-access)|Não|Sim|Sim|Não|
|[Skype for Business](../../office-applications-service-description/office-applications.md#skype-for-business)|Sim<sup>3</sup>|Sim|Sim|Sim<sup>3</sup>|
|[Office para Mac para o Office 365](https://support.office.com/article/General-requirements-for-Outlook-2016-for-Mac-A07A593D-B383-4906-A6C1-962D5543ED57)|Não|Sim|Sim|Não|
|[Office Mobile para iPad/iPhone](../../office-applications-service-description/office-applications.md#office-mobile-for-ipadiphone)|Sim|Sim<sup></sup>|Sim<sup></sup>|Sim|
|[Office Mobile para Android](../../office-applications-service-description/office-applications.md#office-mobile-for-android)|Sim|Sim<sup></sup>|Sim<sup></sup>|Sim|
|[Office Mobile para Windows Phone](../../office-applications-service-description/office-applications.md#office-mobile-for-windows-phone)|Sim|Sim<sup>4</sup>|Sim<sup>4</sup>|Sim|
|Office Mobile for Windows 10 tablets|Sim|Sim<sup></sup>|Sim<sup></sup>|Sim|
|Outlook para iOS e Android<sup>5, 4</sup>|Sim|Sim|Sim|Sim|
|**Enterprise valor**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|5 instalações por usuário em PC ou Mac|Não|Sim|Sim|Não|
|Provisionamento automatizado de contas de usuário|Sim|Sim|Sim|Sim|
|Interface de usuário multilíngue|Não|Sim|Sim|Não|
|Implantação de push de cliente|Não|Sim<sup>4</sup>|Sim<sup>4</sup>|Não|
|Suporte ao cliente para Exchange local|Não|Sim|Sim|Não|
|Suporte ao cliente para SharePoint local|Não|Sim|Sim|Não|
|Controle de atualizações de software|Não|Sim|Sim|Não|
|Comparação de Banco de Dados|Não|Sim|Sim|Não|
|Virtualização de área de trabalho|Não|Sim|Sim|Não|
|Comparação de planilhas do Excel|Não|Sim|Sim|Não|
|Pesquisa de planilhas do Excel|Não|Sim|Sim|Não|
|Armazenamento e conformidade do Exchange Online e do SharePoint Online|Não|Sim|Sim|Não|
|Suporte à Política de Grupo|Não|Sim|Sim|Não|
|Gerenciamento de direitos de informação usando proteção de informações do Azure|Não<sup>1</sup>|Sim<sup>6</sup>|Sim<sup>6</sup>|Não<sup>1</sup>|
|Information Rights Management usando o Windows Server AD RMS|Sim<sup>2</sup>|Sim<sup>2</sup>|Sim<sup>2</sup>|Sim<sup>2</sup>|
|Suporte a suplementos do Office, ActiveX e BHO|Não|Sim|Sim|Não|
|Acesso de cliente do OneNote aos blocos de anotações no SharePoint Server, SharePoint Online, OneDrive for Business e Office 365|Não|Sim|Sim|Não|
|Office Lens|Não|Não|Não|Não|
|Telemetria do Office|Não|Sim<sup>4</sup>|Sim<sup>4</sup>|Não|
|Suporte offline a aplicativos do cliente|Não|Sim|Sim|Não|
|Instalação otimizada de cliente lado a lado|Não|Sim|Sim|Não|
|Power Map para Excel|Não|Não|Não|Não|
|Power Pivot para Excel|Não|Sim<sup>4</sup>|Sim<sup>4</sup>|Não|
|Power Query para Excel|Não|Sim<sup>4</sup>|Sim<sup>4</sup>|Não|
|Power View para Excel|Não|Sim<sup>4</sup>|Sim<sup>4</sup>|Não|
|Configurações de roaming|Não|Sim<sup></sup>|Sim<sup></sup>|Não|
|Ativação de computador compartilhado|Não|Sim|Sim|Não|
|Suporte a bloqueio de armazenamento de arquivo baseado em nuvem|Não|Sim|Sim|Não|
|Atualizações de versão|Não|Sim<sup>4</sup>|Sim<sup>4</sup>|Não|
|Volume activation (KMS/MAK)|Não|Não|Não|Não|

> <sup>1</sup> A Proteção de Informações do Azure não está incluída, mas pode ser comprada como um complemento separado e permitirá os recursos de IRM (Information Rights Management, gerenciamento de direitos de informação) suportados. Alguns recursos de Proteção de Informações do Azure exigem uma assinatura de Microsoft 365 Apps para Grandes Empresas, que não está incluída em Office 365 Government G1 ou Office 365 Government F3.
<br/><sup>2</sup> Windows Server AD RMS é um servidor local que deve ser comprado e gerenciado separadamente para habilitar os recursos irm suportados.
<br/><sup>3</sup> Skype for Business Basic está disponível para todos os clientes. O cliente de desktop do Skype for Business é um aplicativo instalado localmente que fornece recursos de presença, mensagens instantâneas e conferências para planos do Office 365 que incluem o Skype for Business online. Microsoft 365 Apps para Grandes Empresas e Office 365 Enterprise E3 incluem o aplicativo de Skype completo, que inclui recursos adicionais, como suporte avançado de telefonia, arquivamento e recursos de conformidade. A Skype for Business Online license must be assigned for each user. For more information on Lync Basic features, see [Skype for Business Online client comparison tables](/lyncserver/lync-server-2013-desktop-client-comparison-tables).
<br/><sup>4</sup> Ainda não disponível em ambientes GCC High ou DoD, mas em breve.
<br/><sup>5</sup> Veja [Usando Outlook para iOS e Android no Nuvem da Comunidade Governamental](/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud) para mais detalhes.
<br/><sup>6</sup> Ainda não disponível em Office 365 ambiente DoD, mas em breve.
<br/><sup>7</sup> As aplicações estão totalmente disponíveis nas nuvens do governo, com exceção dos recursos específicos não disponíveis no momento. Consulte [Office disponibilidade do recurso de aplicativos](#office-application-and-feature-availability-in-government-plans) para obter detalhes.

## <a name="office-application-and-feature-availability-in-government-plans"></a>Office aplicação e disponibilidade de recursos em planos governamentais

As seguintes Office aplicativos estão disponíveis nas nuvens do governo; no entanto, alguns recursos baseados em nuvem podem não estar disponíveis no momento, como indicado na tabela.<br><br>

|Aplicativo/recurso|CCG|CCG Alto|DOD|
|---|---|---|---|
|[**Microsoft Excel**](../../office-applications-service-description/office-applications.md#microsoft-excel) está totalmente disponível nas nuvens do governo, exceto os **seguintes** recursos, que não estão disponíveis no momento:||||
|Animações incorporadas 3D e modelos 3D|Não|Não|Não|
|Tipos de dados|Não|Não|Não|
|Preenchimento de flash|Não|Não|Não|
|Ideias (Insight Services)|Não|Não|Não|
|Integração melhorada com Power BI (visuais personalizados, criar gráficos PBI diretamente de Excel)|Não|Não|Não|
|Tinta Digital Inteligente|Não|Não|Não|
|Grupos do Office 365|Não|Não|Não|
|Dados do PivotCharts conectados a Tabelas Dinâmicas|Não|Não|Não|
|PowerPivot|Não|Não|Não|
|Publicar no Power BI|Não|Não|Não|
|Colaboração em tempo real (presença, coautoria regular, bate-papo no documento)|Não|Não|Não|
|Shared with Me|Não|Não|Não|
|Pesquisa Inteligente|Não|Não|Não|
|Gráficos: mapa da árvore de explosão solar, cachoeira, histograma, mapas, linha do tempo, funil|Não|Não|Não|
|Histórico de versão|Não|Não|Não|
|[**O Microsoft Forms**](https://support.office.com/article/5cbd407a-eef7-431e-8e3a-eb666eab4b4c) está totalmente disponível nas nuvens do governo, exceto os **seguintes** recursos, que não estão disponíveis no momento:|**GCC**|**CCG Alto**|**DOD**|
|Notificação por e-mail|Não<sup>1</sup>|Não<sup>1</sup>|Não|
|Insira uma imagem|Não<sup>1</sup>|Não<sup>1</sup>|Não|
|Insira um vídeo|Não<sup>1</sup>|Não<sup>1</sup>|Não|
|Matemática|Não<sup>1</sup>|Não<sup>1</sup>|Não|
|integração Office|Não<sup>1</sup>|Não<sup>1</sup>|Não|
|Formas de grupo mais recentes|Não<sup>4</sup>|Sim|Sim|
|Compartilhamento externo<sup>3</sup>|Sim|Não|Não|
|Formulários Pro|Não|Não|Não|
|[**Microsoft OneNote**](../../office-applications-service-description/office-applications.md#microsoft-onenote) está totalmente disponível nas nuvens do governo, exceto os **seguintes** recursos, que não estão disponíveis no momento:|**GCC**|**CCG Alto**|**DOD**|
|Pesquisador|Não|Não|Não|
|Tinta Digital Inteligente|Não|Não|Não|
|Enviar e-mail para OneNote (me@onenote.com)|Não|Não|Não|
|Web Clipper|Não|Não|Não|
|[**O Microsoft Outlook**](../../office-applications-service-description/office-applications.md#microsoft-outlook) está totalmente disponível nas nuvens do governo, exceto nos seguintes recursos, que não estão disponíveis em todas as Nuvens do Governo, conforme indicado na tabela abaixo.|**GCC**|**CCG Alto**|**DOD**|
|Office sons (alguns)|Não|Não|Não|
|Dados dinâmicos Exchange (DDE) desativados por padrão|Não|Não|Não|
|Ditado|Sim|Sim|Não<sup>1</sup>|
|[**O Microsoft PowerPoint**](../../office-applications-service-description/office-applications.md#microsoft-powerpoint) está totalmente disponível nas nuvens do governo, exceto nos seguintes recursos, que não estão disponíveis em todas as Nuvens do Governo, conforme indicado na tabela abaixo.|**GCC**|**CCG Alto**|**DOD**|
|Pesquisa Inteligente|Não|Não|Não|
|Office sons (alguns)|Não|Não|Não|
|Modelos 3D e animações embarcadas 3D|Não|Não|Não|
|Gráficos: mapas|Não|Não|Não|
|Tinta Digital Inteligente|Não|Não|Não|
|Legendas ao vivo e legendas em PowerPoint|Não|Não|Não|
|Treinador de Apresentador|Não|Não|Não|
|Shared with Me|Não|Não|Não|
|Skype for Business integração com o compartilhamento|Não|Não|Não|
|Histórico de versão|Não|Não|Não|
|Grupos do Office 365|Não|Não|Não|
|Colaboração em tempo real (presença, coautoria regular, bate-papo no documento)|Não|Não|Não|
|Ditado|Sim|Sim|Não<sup>1</sup>|
|Reutilizar slides|Não|Não|Não|
|**Microsoft Whiteboard** em nuvens governamentais atualmente só está disponível em clientes Hub, e não no desktop.|**GCC**<sup>2</sup>|**GCC High**<sup>2</sup>|**DOD**<sup>2</sup>|
|Insira notas pegajosas, texto e imagens|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|
|Tinta para moldar e tinta à mesa|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|
|Embelezamento da tinta|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|
|Converter imagem em tinta|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|
|Verificador de acessibilidade|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|
|Modelos dinâmicos (KANBAN, SWOT, e assim por diante)|Não|Não|Não|
|Colaboração em tempo real|Não|Não|Não|
|Presença em tempo real|Não|Não|Não|
|Reações no conteúdo|Não|Não|Não|
|Galeria de quadros de quadros, incluindo compartilhado com você|Não|Não|Não|
|[**Microsoft Word**](../../office-applications-service-description/office-applications.md#microsoft-word) está totalmente disponível nas nuvens do governo, exceto nas seguintes características, que não estão disponíveis em todas as Nuvens do Governo, conforme indicado na tabela abaixo.|**GCC**|**CCG Alto**|**DOD**|
|Pesquisa Inteligente|Não|Não|Não|
|Pesquisador|Não|Não|Não|
|Office sons|Não|Não|Não|
|Modelos 3D|Não|Não|Não|
|Animações incorporadas 3D|Não|Não|Não|
|Toque|Não|Não|Não|
|Assistente de Currículos|Não|Não|Não|
|Gráficos de mapas|Não|Não|Não|
|Tinta Digital Inteligente|Não|Não|Não|
|Shared with Me|Não|Não|Não|
|Tradução|Sim<sup>5</sup>|Sim<sup>5</sup>|Sim<sup>5</sup>|
|Skype for Business integração com o compartilhamento|Não|Não|Não|
|Histórico de versão|Não|Não|Não|
|Grupos do Office 365|Não|Não|Não|
|Bate-papo contextual com coautores: bate-papo com coautores dentro do documento|Não|Não|Não|
|Ditado|Sim|Sim|Não<sup>1</sup>|

Para obter disponibilidade de recursos para Microsoft Teams no GCC/GCC High/DoD, visite a [descrição do serviço Microsoft Teams](../../teams-service-description.md).
> <sup>1</sup> Disponibilidade em breve.
<br/><sup>2</sup> Disponibilidade em Surface Hub locais (não loto).
<br/><sup>3</sup> O compartilhamento externo está disponível para o ambiente GCC. Saiba mais sobre como [desativar ou ativar os Formulários microsoft](https://support.office.com/article/cc52287a-4550-464d-9a1b-457bf9df2240#PickTab=Configure) para sua organização. O compartilhamento externo é desativado para ambientes GCC de alta e doD; os usuários dentro de sua organização podem fazer o seguinte: preencher um formulário e enviar respostas, [duplicar e compartilhar um formulário como modelo,](https://support.office.com/article/82ea9d8a-260a-47a0-afdb-497f3d746e3f) [coautor ou colaborar em um formulário](https://support.office.com/article/d5bb5cf0-8401-4c15-bb8c-8e108cd7e69b)e acessar resultados de [formulários](https://support.office.com/article/02859424-341d-406f-b32a-9a0fbaf357af).
<br/><sup>4</sup> O recurso de formulários de grupo recentes é desativado para o ambiente GCC. Os usuários, no entanto, ainda podem acessar formulários de grupo selecionando um grupo específico na guia Formulários do Grupo.
<br/><sup>5</sup> Word, Excel PowerPoint Windows cliente apenas, não web, MacOS, iOS ou Android.
