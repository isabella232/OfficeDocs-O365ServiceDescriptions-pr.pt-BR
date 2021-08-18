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
description: Em resposta aos requisitos exclusivos e em evolução do setor público dos Estados Unidos, a Microsoft criou planos do Office 365 para o Governo norte-americano (ou Office 365 Government). Este artigo fornece uma visão geral dos recursos que são específicos Office 365 Government ambientes dos EUA.
ms.openlocfilehash: efcef9de537f1d3750a0b282a40d1f015c8bb82c
ms.sourcegitcommit: e072b0e70346cb60f106188fe1aef54cf2b35ee2
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 08/17/2021
ms.locfileid: "58371778"
---
# <a name="office-365-government"></a>Office 365 Government

> [!IMPORTANT]
> Microsoft Teams está enfrentando um aumento enorme em chamadas online e conferência de áudio/vídeo devido à pandemia do coronavírus (COVID-19).<br/>
>
>Em resposta ao aumento sem precedentes de chamadas e para garantir a continuidade e a disponibilidade, a Microsoft está permitindo que Microsoft Teams GCC servidores de áudio/vídeo aproveitem a capacidade de processamento em nossos datacenters comerciais, bem como em nossos datacenters governamentais.<br/>
>
>Esses servidores Microsoft Azure de áudio/vídeo residem dentro dos servidores de limite de alta credenciamento fedRAMP nos Estados Unidos e não armazenam conteúdo do cliente. No entanto, esses servidores estão processamento de áudio e vídeo para chamadas e conferências e estão operando sob nossa equipe comercial durante esse período provisório.<br/>
>
>Equipes qualificadas e monitoradas estão monitorando esses servidores para acesso potencial aos dados do cliente, revendo qualquer log interativo para esses servidores. A equipe qualificada GCC requisitos de acesso ao conteúdo do cliente. Para obter detalhes sobre os requisitos de triagem, consulte [GCC descrição do serviço.](gcc.md)<br/>
>
>Obrigado por seu suporte à medida que as etapas são tomadas para garantir que nossos serviços permaneçam disponíveis e confiáveis nesses tempos extraordinários.<br/>

Em resposta aos requisitos exclusivos e em evolução do setor público dos Estados Unidos, a Microsoft criou Office 365 Government planos (ou Office 365 Government). Essa descrição de serviço fornece uma visão geral dos recursos que são específicos Office 365 Government ambientes dos EUA. Recomendamos que você leia essa descrição de serviço juntamente [com outras Microsoft 365 e Office 365 de serviço](../../office-365-service-descriptions-technet-library.md).

## <a name="how-to-use-this-service-description"></a>Como usar a descrição deste serviço

A Office 365 Government de serviço foi projetada para servir como uma sobreposição para a descrição geral Office 365 serviço. Ela define as diferenças e os compromissos exclusivos em comparação com as ofertas do Office 365 Enterprise.

## <a name="about-office-365-government-environments"></a>Sobre Office 365 Government ambientes

Office 365 Government planos são assinaturas mensais e podem ser licenciados para um número ilimitado de usuários.

- O **Office 365 GCC** ambiente fornece conformidade com os requisitos federais para serviços de nuvem, incluindo FedRAMP High e requisitos para a justiça criminal e sistemas de informações fiscais federais (tipos de dados CJI e FTI).

- Os Office 365 GCC ambientes High e **DoD** oferecem conformidade com as Diretrizes de Requisitos de Segurança do Departamento de Defesa, Suplemento de Regulamentos de Aquisição Federal de Defesa (DFARS) e Itar (International Traffic in Arms Regulations).

Além dos recursos e recursos da Office 365, as organizações que usam Office 365 Government se beneficiam dos seguintes recursos exclusivos para Office 365 Government:

- O conteúdo do cliente de sua organização é logicamente separado do conteúdo dos Serviços do Office 365 do cliente comercial da Microsoft.

- O conteúdo do cliente da sua organização é armazenado dentro dos Estados Unidos.

- O acesso ao conteúdo do cliente da sua organização é restrito à equipes selecionadas da Microsoft.

- Office 365 Government está em conformidade com certificações e acreditações necessárias para clientes do Setor Público dos EUA.

## <a name="customer-eligibility"></a>Qualificação do cliente

Office 365 Government está disponível para (1) entidades governamentais federais, estaduais, locais, tribais e territoriais dos EUA e (2) outras entidades que lidam com dados sujeitos a regulamentos e requisitos governamentais e onde o uso do Office 365 Government é apropriado para atender a esses requisitos, sujeito à validação da qualificação. A validação de qualificação feita pela Microsoft incluirá a confirmação da manipulação de dados sujeitos ao ITAR (International Traffic in Arms Regulations), dados para a aplicação da lei sujeitos à política do Criminal Justice Information Services (CJIS) do FBI ou outros dados controlados ou regulamentados pelo governo. A validação poderá exigir a prova do registro no Departamento de Estado dos Estados Unidos para os dados do ITAR ou o aval de uma entidade governamental com requisitos específicos para a manipulação de dados. O Office 365 ambiente do DoD é para uso exclusivo do Departamento de Defesa dos Estados Unidos.

Embora os critérios de qualificação sejam consistentes entre Office 365 Government ofertas, a Microsoft só concordará com o idioma de contrato DFARS e ITAR para o ambiente GCC High.

Entidades com perguntas sobre qualificação para Office 365 Government devem consultar sua equipe de conta.

Após a renovação do contrato de um cliente para Office 365 Government, a revalidação da qualificação é necessária.

## <a name="customer-content-located-within-the-united-states"></a>Conteúdo de cliente localizado nos Estados Unidos

Office 365 Government serviços são fornecidos de datacenters fisicamente localizados nos Estados Unidos. O seguinte conteúdo de cliente é armazenado em repouso em datacenters fisicamente localizados apenas nos EUA:

- Exchange Online de caixa de correio (corpos de email, entradas de calendário e o conteúdo de anexos de email)

- SharePoint Conteúdo do site online e os arquivos armazenados nesse site

- Skype for Business conversas arquivadas, documentos carregados e sessões de quadro de diálogo

- Microsoft Teams de chat persistente

> [!NOTE]
> Normalmente, o Skype for Business não armazena conteúdo de clientes, mas se ocorrer algum armazenamento, ele será feito em datacenters nos EUA.

Se os usuários estão localizados nos EUA enquanto usam o Office para a Web (anteriormente conhecido como aplicativos Web do Office) ou se você adotar o uso do AD FS (Serviços de Federação do Active Directory) 2.0 e configurar políticas para ajudar a garantir que seus usuários se conectem aos serviços por meio de uma única conexão, qualquer conteúdo do cliente temporariamente armazenado em cache no Office para a Web estará localizado nos EUA.

A página de uso do site para SharePoint sites está disponível para planos governamentais, embora por conformidade, existem alguns recursos desta página que estão disponíveis apenas para clientes comerciais. Para saber mais, confira [Página de uso do site para SharePoint sites em Microsoft 365](https://support.microsoft.com/office/2fa8ddc2-c4b3-4268-8d26-a772dc55779e).

## <a name="office-365-government-and-third-party-services"></a>Office 365 Government e serviços de terceiros

Office 365 oferece a capacidade de integrar aplicativos de terceiros em sites online do SharePoint, aplicativos Skype for Business, Office incluídos no Microsoft 365 Apps para Grandes Empresas (como Word, Excel, PowerPoint e Outlook) e Outlook Web App. Além disso, o Office 365 suporta a integração com provedores de serviços de terceiros. Estes aplicativos e serviços de terceiros podem envolver o armazenamento, a transmissão e o processamento dos dados de cliente da sua organização em sistemas de terceiros que estão localizados fora da infraestrutura do Office 365 e, portanto, não são cobertos pelos compromissos de conformidade e proteção de dados do Office 365. Recomendamos que você analise as instruções de privacidade e conformidade fornecidas por terceiros quando estiver avaliando o uso apropriado destes serviços para sua organização.

## <a name="restricted-data-access-by-administrators"></a>Acesso restrito aos dados pelos administradores

O acesso Office 365 Government conteúdo do cliente pelos administradores da Microsoft é restrito à equipe de tela. Para obter detalhes de níveis de triagem, consulte a página de descrição do serviço para cada ambiente respectivo (GCC ou GCC Alta e DoD).

## <a name="fasttrack-center-onboarding-assistance"></a>FastTrack Assistência de integração central

Com o FastTrack Center Benefit para Office 365<sup>1</sup>, você trabalha remotamente com especialistas do FastTrack para preparar seu ambiente Office 365 para uso e planejar a distribuição e o uso em sua organização. O processo FastTrack oferece integração e serviços de adoção do usuário. 

A integração consiste em:

- Integração principal - São tarefas necessárias para a configuração do locatário e a integração com o Azure Active Directory (Azure AD), se necessário. A integração básica também fornece a linha de base para integração de outros serviços qualificados.

- Integração e migração de serviço - As tarefas de integração de serviço permitem cenários em seu locatário. A migração de dados (incluindo email e arquivos) é abordada em [Migração de Dados](/FastTrack/data-migration). <sup>2</sup>

Os serviços de adoção do usuário são compostos de tarefas que fornecem orientações para garantir que os usuários estão cientes dos serviços qualificados e podem usá-los para impulsionar o valor comercial. Esta assistência ocorre paralelamente às atividades de integração.

Informações específicas sobre o processo FastTrack Central podem ser encontradas [aqui](/FastTrack/us-gov-appendix-overview). Para uma divisão de funções e responsabilidades de envolvimento, [revise FastTrack Responsabilidades,](/FastTrack/us-gov-appendix-fasttrack-responsibilities) bem como [Suas Responsabilidades.](/FastTrack/us-gov-appendix-your-responsibilities)

> <sup>1</sup> Você deve comprar pelo menos 150 licenças da lista dos planos qualificados [para](/fasttrack/eligibility) receber FastTrack serviços.
<br/><sup>2</sup> Os serviços de Migração de Dados estão disponíveis Office 365 locatários com 500 ou mais licenças.

## <a name="data-migrations-performed-by-fasttrack"></a>Migrações de dados executadas por FastTrack

Os clientes que escolherem o [benefício FastTrack](https://fasttrack.microsoft.com/) migração precisarão conceder acesso à equipe que gerencia suas migrações de dados. Esses funcionários são cidadãos dos EUA e passam pelas seguintes verificações em segundo plano antes de executar migrações para clientes de Office 365 serviços do Governo dos EUA.<br><br>

|Triagem em segundo plano|CCG|GCC alto e DoD|
|---|---|---|
|Verificação da cidadania dos EUA|Sim|Sim|
|Verificação do histórico de empregos|Sim|Sim|
|Verificação educacional|Sim|Sim|
|Pesquisa de Número de Segurança Social (SSN)|Sim|Sim|
|Verificação de histórico criminal (7 anos)|Sim|Sim|

## <a name="office-365-us-government-and-azure-government-expressroute"></a>Office 365 US Government e Microsoft Azure Government ExpressRoute

Office 365 Os clientes do Governo dos EUA podem usar os serviços do Azure Government ExpressRoute para se conectarem privadamente aos serviços de Office 365 em vez de se conectarem pela Internet pública.

Para obter detalhes, como provedores com suporte, modelos de preços e muito mais, revise as informações do [Azure ExpressRoute.](/azure/expressroute/)

Para obter detalhes Office 365 suporte ao Azure ExpressRoute, consulte [Azure ExpressRoute for Office 365](/microsoft-365/enterprise/azure-expressroute)

## <a name="system-requirements"></a>Requisitos do sistema

Para requisitos de sistema dos planos do Office 365 US Government, confira [Requisitos de sistema do Office](https://go.microsoft.com/fwlink/?LinkID=626095&amp;clcid=0x409) no site de produtos do [office.com](https://go.microsoft.com/fwlink/?LinkID=509817&amp;clcid=0x409).

## <a name="security-amp-compliance-center"></a>Security &amp; Compliance Center

Para obter informações sobre o Centro de Conformidade de Segurança e links para &amp; informações e disponibilidade adicionais, consulte Security Compliance [ &amp; Center](../../office-365-platform-service-description/office-365-securitycompliance-center.md).

## <a name="service-availability-for-each-plan"></a>Disponibilidade do serviço para cada plano

Cada plano do Office 365 inclui alguns serviços individuais, como o Exchange Online e o SharePoint Online. A tabela a seguir mostra os serviços disponíveis em cada plano do Office 365 US Government.<br><br>

|Serviço do Office 365|Office 365 Government G1|Office 365 Government G3|Office 365 Government G5|Office 365 Government F3|
|---|---|---|---|---|
|Exchange Online|Sim|Sim|Sim|Sim|
|Proteção do Exchange Online|Sim|Sim|Sim|Sim|
|Microsoft 365 Apps para Grandes Empresas|Não|Sim|Sim|Não|
|Office na Web|Sim|Sim|Sim|Sim|
|OneDrive for Business|Sim|Sim|Sim|Sim|
|Power BI Pro|Não<sup>2</sup>|Não<sup>2</sup>|Sim|Não<sup>2</sup>|
|Project Online|Não<sup>2</sup>|Não<sup>2</sup>|Não<sup>2</sup>|Não<sup>2</sup>|
|SharePoint Online|Sim|Sim|Sim|Sim|
|SharePoint Syntex|Sim|Sim|Sim|Sim|
|Skype for Business (Instant Messaging &amp; Presence)|Sim<sup>1</sup>|Sim|Sim|Sim<sup>1</sup>|
|Voz - Sistema de Telefonia, Audioconferência|Não<sup>2</sup>|Não<sup>2</sup>|Sim<sup>5</sup>|Não|
|Visio para a Web|Não<sup>6</sup>|Não<sup>6</sup>|Não<sup>6</sup>|Não<sup>6</sup>|
|Yammer Enterprise|Não<sup>4</sup>|Não<sup>4</sup>|Não<sup>4</sup>|Não<sup>4</sup>|

> <sup>1</sup> Skype for Business Basic está disponível para todos os clientes. O cliente de desktop do Skype for Business é um aplicativo instalado localmente que fornece recursos de presença, mensagens instantâneas e conferências para planos do Office 365 que incluem o Skype for Business online. Microsoft 365 Apps para Grandes Empresas, G3 e G5 incluem o aplicativo de Skype completo, que inclui recursos adicionais, como suporte avançado à telefonia, arquivamento e recursos de conformidade. A Skype for Business Online license must be assigned for each user.
<br/><sup>2</sup> Não incluído, mas pode ser comprado como um complemento separado. Project Online inclui Project Online Desktop Client como parte da assinatura.
<br/> <sup>3</sup> Ainda não está disponível em GCC planos High ou DoD, mas em breve.
<br/><sup>4</sup> Yammer Enterprise não é um componente do Office 365 Us Government, mas pode ser adquirido sem custo como uma oferta autônoma para cada usuário licenciado para Office 365 no GCC. No momento, essa oferta está limitada aos clientes que compram Office 365 GCC em contratos Enterprise e contratos de assinatura Enterprise assinatura. Yammer não está disponível no GCC High ou DoD.
<br/><sup>5</sup> Plano de Chamada é um complemento.
<br/><sup>6</sup> Não incluído, mas pode ser comprado como um complemento separado. Visio para a Web inclui o Visio da área de trabalho como parte da assinatura.

## <a name="platform-features"></a>Recursos da plataforma 

A tabela a seguir exibe os recursos e serviços da plataforma que estão disponíveis nos planos do Office 365 US Government.<br><br>

|Recurso|Office 365 Government G1|Office 365 Government G3|Office 365 Government G5|Office 365 Government F3|
|---|---|---|---|---|
|**Administração do Office 365**|||||
|Use o Centro de administração do Microsoft 365 para administrar Office 365|Sim<sup>16</sup>|Sim<sup>16</sup>|Sim|Sim<sup>16</sup>|
|Gerenciar as configurações de serviço principal do Office 365|Sim|Sim|Sim|Sim|
|Usar o Windows PowerShell para gerenciar Office 365|Sim|Sim|Sim|Sim|
|Proteger o conteúdo usando a Proteção de Informações do Azure|No<sup>1</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|No<sup>1</sup>|
|**[Recursos do Pacote do Office 365](../../office-365-platform-service-description/office-365-suite-features.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|Microsoft Bookings|Não|Sim<sup>21</sup>|Sim<sup>21</sup>|Não|
|Email do Microsoft Briefing|Não|Não|Não|Não|
|Microsoft Power Automate|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|
|Microsoft Forms|Sim|Sim|Sim<br/>|Sim</sup>|
|API do Microsoft Graph|Sim|Sim|Sim|Sim|
|Microsoft MyAnalytics|Não|Não|Sim<sup>17</sup>|Não|
|Microsoft Planner|Sim|Sim|Sim|Sim|
|Microsoft PowerApps|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|
|Microsoft StaffHub|Não|Não|Não|Não<br/>|
|Microsoft Stream|Sim<sup>9, 15</sup>|Sim<sup>9, 15</sup>|Sim<sup>9, 15</sup>|Sim<sup>9, 15, 20</sup>|
|Microsoft Sway|Não|Não|Não|Não|
|Microsoft Teams|Sim|Sim|Sim|Sim|
|Office Delve|Sim<sup>17</sup>|Sim<sup>17</sup>|Sim|Sim<sup>17</sup>|
|Grupos do Office 365|Sim|Sim|Sim|Sim|
|**[Gerenciamento de contas de usuário](../../office-365-platform-service-description/user-account-management.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|Identidade de nuvem|Sim|Sim|Sim|Sim|
|Identidade federada (logon único)|Sim|Sim|Sim|Sim|
|Autenticação multifator|Sim|Sim|Sim|Sim|
|Telefone fator|Sim<sup>9</sup>|Sim<sup>9</sup>|Sim|Sim<sup>9</sup>|
|Configuração de área de trabalho do Office 365|Sim|Sim|Sim|Sim|
|Gerenciar usuários com o Office 365|Sim|Sim|Sim|Sim|
|Carregamento em massa usando .csv arquivos|Sim<sup>9</sup>|Sim<sup>9</sup>|Sim|Sim<sup>9</sup>|
|Ferramenta de Sincronização de Diretórios|Sim|Sim|Sim|Sim|
|Migração simples (substituição) do Exchange|Sim|Sim|Sim|Sim|
|Excluir contas usando o Office 365|Sim<sup>3</sup>|Sim<sup>3</sup>|Sim<sup>3</sup>|Sim<sup>3</sup>|
|O administrador pode redefinir a senha de usuário no Office 365 ou usando o Windows PowerShell|Sim<sup>4</sup>|Sim<sup>4</sup>|Sim<sup>4</sup>|Sim<sup>4</sup>|
|Os usuários podem alterar sua própria senha|Sim<sup>5</sup>|Sim<sup>5</sup>|Sim<sup>5</sup>|Sim<sup>5</sup>|
|Gerenciar licenças|Sim<sup>7, 8</sup>|Sim<sup>7, 8</sup>|Sim<sup>7, 8</sup>|Sim<sup>7,8</sup>|
|Gerenciar grupos de segurança do Office 365|Sim|Sim|Sim|Sim|
|Várias funções de administrador disponíveis|Sim|Sim|Sim|Sim|
|Permitir que um parceiro administre o Office 365 para você|Sim<sup>11</sup>|Sim<sup>11</sup>|Sim<sup>11</sup>|Sim<sup>11</sup>|
|Serviços do Azure Active Directory|Sim|Sim|Sim|Sim|
|**[Domínios](../../office-365-platform-service-description/domains.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|Adicionar domínios de segundo nível personalizados, como fourthcoffee.com|Sim|Sim|Sim|Sim|
|Adicionar domínios de terceiro nível personalizados, como marketing.fourthcoffee.com|Sim|Sim|Sim|Sim|
|Adicionar até 900 domínios personalizados|Sim|Sim|Sim|Sim|
|Verificação de propriedade de domínio necessária para domínios personalizados|Sim|Sim|Sim|Sim|
|**[Continuidade e integridade do serviço](../../office-365-platform-service-description/service-health-and-continuity.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|Informação de status disponível na página **Integridade do serviço** ou **Status do serviço**|Sim<sup>9, 15</sup>|Sim<sup>9, 15</sup>|Sim<sup>9, 15</sup>|Sim<sup>9, 15</sup>|
|Status dos alertas individuais disponíveis no painel Centro de administração do Microsoft 365 painel|Sim<sup>9, 15</sup>|Sim<sup>9, 15</sup>|Sim<sup>9, 15</sup>|Sim<sup>9, 15</sup>|
|RSS feed de **Integridade do serviço**|Sim|Sim|Sim|Sim|
|**[Relatórios](../../office-365-platform-service-description/reports.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|Caixas postais ativas e inativas|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|
|Caixas de correio novas e excluídas|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|
|Grupos novos e excluídos|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|
|Uso da caixa de correio|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|
|Tipos de conexões da caixa de correio|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|
|Emails enviados e recebidos|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|
|Principais remetentes e destinatários|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|
|Detecções de spam|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|
|Detecções de malware|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|
|Principal malware para email|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|
|Correspondências de regra para email|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|
|Principais correspondências de regra para email|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|
|Principais correspondências de política DLP para email|Não|Sim<sup>15</sup>|Sim<sup>15</sup>|Não|
|Correspondências de política DLP por gravidade para email|Não|Sim<sup>15</sup>|Sim<sup>15</sup>|Não|
|Correspondências, substituições e falsos positivos de política DLP para email|Não|Sim<sup>15</sup>|Sim<sup>15</sup>|Não|
|Principais correspondências de regra DLP para email|Não|Sim<sup>15</sup>|Sim<sup>15</sup>|Não|
|Sessões de mensagens instantâneas e áudio|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|
|Compartilhamento de aplicativos, Webconferência e conferência discada|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|
|Vídeo, compartilhamento de aplicativos e sessões de transferência de arquivos|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|
|Mensagens instantâneas e conferências de áudio/vídeo|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|
|Relatórios de proteção de email para download|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|
|Navegador usado|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|
|Sistema operacional usado|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|
|Criar seus próprios relatórios usando Microsoft 365 web de relatórios|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|
|**[Atualizações de serviço](../../office-365-platform-service-description/service-updates.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|Atualizações regulares fornecidas a todos os clientes|Sim|Sim|Sim|Sim|
|Notificações enviadas para o Centro de Mensagens quando uma ação é necessária|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|
|Success.office.com/pt-br/roadmap para alguns serviços updates|Não<sup>há 10, 13</sup>|Não<sup>há 10, 13</sup>|Não<sup>há 10, 13</sup>|Não<sup>há 10, 13</sup>|
|Opção para ativar a versão direcionada|Sim<sup>10</sup>|Sim<sup>10</sup>|Sim<sup>10</sup>|Sim<sup>10</sup>|
|**[Ajuda e treinamento](../../office-365-platform-service-description/help-and-training.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|Ajuda online|Sim|Sim|Sim|Sim|
|Comunidade|Sim|Sim|Sim|Sim|
|Outros recursos de autoajuda|Sim|Sim|Sim|Sim|
|Treinamento individual|Sim|Sim|Sim|Sim|
|**[Sistema de rede](../../office-365-platform-service-description/networking.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|Protocolos IPv4 e IPv6|Sim|Sim|Sim|Sim|
|**Confiança**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|**[Privacidade, segurança e transparência](../../office-365-platform-service-description/privacy-security-and-transparency.md)**|||||
|Advanced Data Governance|No<sup>12</sup>|No<sup>12</sup>|Sim|No<sup>12</sup>|
|Segurança no Aplicativo na Nuvem|No<sup>12, 19</sup>|No<sup>12, 19</sup>|Sim<sup>19</sup>|No<sup>12, 19</sup>|
|Microsoft Defender para Office 365|No<sup>12, 18</sup>|No<sup>12, 18</sup>|Sim<sup>18</sup>|No<sup>12, 18</sup>|
|Sistema de Proteção de Dados do cliente|No<sup>12</sup>|No<sup>12</sup>|Sim|No<sup>12</sup>|
|Descoberta Eletrônica Avançada|No<sup>12</sup>|No<sup>12</sup>|Sim|No<sup>12</sup>|
|Pontuação<sup>Segura 14</sup>|Sim<sup>9, 15</sup>|Sim<sup>9</sup>|Sim<sup>9, 15</sup>|Sim<sup>9, 15</sup>|
|Office Criptografia de Mensagens|Não|Sim|Sim|Não|
|Inteligência contra Ameaças|No<sup>12</sup>|No<sup>12</sup>|Sim|No<sup>12</sup>|
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
|Criar convites para avaliação e ordens de compra para um cliente que está usando o plano especificado|No<sup>11</sup>|No<sup>11</sup>|No<sup>11</sup>|No<sup>11</sup>|
|Fornecer administração delegada|No<sup>11</sup>|No<sup>11</sup>|No<sup>11</sup>|No<sup>11</sup>|
|**[Contrato de Nível de Serviço](../../office-365-platform-service-description/service-level-agreement.md)**|Sim|Sim|Sim|Sim|
|**[Direitos de uso do produto](../../office-365-platform-service-description/product-use-rights.md)**|Sim|Sim|Sim|Sim|

> <sup>1</sup> A Proteção de Informações do Azure não está incluída, mas pode ser comprada como um complemento separado e habilita os recursos de Gerenciamento de Direitos de Informação (IRM) com suporte. Alguns recursos da Proteção de Informações do Azure exigem uma assinatura para Microsoft 365 Apps para Grandes Empresas, que não está incluída no Office 365 para o Governo G1 ou Office 365 Government F3. >
<br/><sup>2</sup> Os clientes existentes da BBCS e do BIS podem continuar a usar o serviço. No momento, não aceitamos novos clientes.
<br/><sup>3</sup> Se estiver usando a sincronização de diretórios, você deverá excluir contas ou alterar senhas usando o Active Directory, em vez do portal Office 365 ou usando o módulo Azure Active Directory para Windows PowerShell.
<br/><sup>4 Se</sup> estiver usando a sincronização de senhas, os usuários deverão alterar suas senhas no Active Directory local.
<br/><sup>5</sup> Para saber como definir políticas de gerenciamento de senhas autoatendidas para usuários, consulte [Manage Passwords in Azure AD](/azure/active-directory/user-help/active-directory-passwords-update-your-own-password).
<br/><sup>6</sup> Você pode ter apenas um site público com Office 365, a menos que tenha atualizado de uma versão anterior do Office 365. Nesse caso, é possível ter dois sites públicos, mas somente um deles pode ser hospedado com um nome de domínio personalizado. Para obter mais informações sobre como trabalhar com os dois sites de assinaturas para Empresas, consulte Trabalhar com seus dois Office 365 [sites públicos.](https://go.microsoft.com/fwlink/p/?LinkID=271589) Se você tiver uma assinatura diferente, saiba mais sobre sites públicos em Saiba mais sobre hospedagem de sites de parceiros e sites públicos [em Office 365](https://go.microsoft.com/fwlink/p/?LinkID=325009).
<br/><sup>7</sup> A redução de assentos comprados com um desconto de termos pode estar sujeita a uma taxa de encerramento antecipada. Isso não é aplicável a assinaturas pagas mensalmente.
<br/><sup>8</sup> Os planos a seguir não suportam alterações de assento de licença do Centro de administração do Microsoft 365: Office 365 para o Governo G1, Office 365 para o Governo G3, Office 365 Government F3.
<br/><sup>9</sup> Ainda não está disponível no GCC High, mas em breve.
<br/><sup>10</sup> Para Office 365 para o Governo G1, G3 e F3, a versão direcionada e o Office 365 de negócios se aplicam; no entanto, pode haver algumas diferenças ou atrasos para atualizações de serviço específicas devido aos requisitos [de conformidade.](https://www.microsoft.com/trust-center)
<br/><sup>11</sup> Ainda não está disponível em Office 365 Government ofertas, mas em breve.
<br/><sup>12</sup> Não incluído, mas pode ser comprado como um complemento separado no GCC.
<br/><sup>13</sup> Não há suporte para Office 365 Government ofertas.
<br/><sup>14</sup> Disponível em [https://securescore.office.com](https://securescore.office.com) . Requer permissões de administrador. Saiba mais em [Apresentando a Classificação de Segurança do Office 365](/microsoft-365/security/mtp/microsoft-secure-score).
).
<br/><sup>15</sup> Ainda não está disponível no ambiente do DoD, mas em breve.
<br/><sup>16</sup> O Centro de administração não inclui análise de uso no DoD ou GCC ambientes High.
<br/><sup>17</sup> Não há suporte para ambientes GCC High ou DoD.
<br/><sup>18</sup> O anti-phishing para a representação de usuário e domínio e a inteligência de spoof ainda não estão disponíveis GCC Alta e DoD.
<br/><sup>19</sup> Ainda não está disponível no GCC ambiente, mas em breve.
<br/><sup>20</sup> Consumo somente para o Microsoft Stream: sem publicação ou compartilhamento.
<br/><sup>21</sup> Não disponível para a API Graph microsoft ou Microsoft Teams.

## <a name="office-application-availability-and-enterprise-value"></a>Office disponibilidade de aplicativos e valor empresarial

A tabela a seguir mostra os recursos do aplicativo do Office que estão disponíveis nos planos do Office 365 US Government.<br><br>

|Aplicativo/recurso|Office 365 Government G1|Office 365 Government G3|Office 365 Government G5|Office 365 Government F3|
|---|---|---|---|---|
|**Aplicativos do Office**|||||
|[Microsoft Word](../../office-applications-service-description/office-applications.md#microsoft-word)<sup>7</sup>|Não|Sim|Sim|Não|
|[Microsoft Excel](../../office-applications-service-description/office-applications.md#microsoft-excel)<sup>7</sup>|Não|Sim|Sim|Não|
|[Microsoft PowerPoint](../../office-applications-service-description/office-applications.md#microsoft-powerpoint)<sup>7</sup>|Não|Sim|Sim|Não|
|[Microsoft OneNote](../../office-applications-service-description/office-applications.md#microsoft-onenote)<sup>7</sup>|Não|Sim|Sim|Não|
|[Microsoft Outlook](../../office-applications-service-description/office-applications.md#microsoft-outlook)<sup>7</sup>|Não|Sim|Sim|Não|
|Microsoft Forms<sup>7</sup>|Sim|Sim <br/>|Sim|Não|
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
|Gerenciamento de Direitos de Informação usando a Proteção de Informações do Azure|No<sup>1</sup>|Sim<sup>6</sup>|Sim<sup>6</sup>|No<sup>1</sup>|
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

> <sup>1</sup> A Proteção de Informações do Azure não está incluída, mas pode ser comprada como um complemento separado e habilita os recursos de Gerenciamento de Direitos de Informação (IRM) com suporte. Alguns recursos da Proteção de Informações do Azure exigem uma assinatura para Microsoft 365 Apps para Grandes Empresas, que não está incluída no Office 365 para o Governo G1 ou Office 365 Government F3.
<br/><sup>2</sup> Windows Server AD RMS é um servidor local que deve ser comprado e gerenciado separadamente para habilitar os recursos de IRM com suporte.
<br/><sup>3</sup> Skype for Business Basic está disponível para todos os clientes. O cliente de desktop do Skype for Business é um aplicativo instalado localmente que fornece recursos de presença, mensagens instantâneas e conferências para planos do Office 365 que incluem o Skype for Business online. Microsoft 365 Apps para Grandes Empresas e Office 365 Enterprise E3 incluem o aplicativo de Skype completo, que inclui recursos adicionais, como suporte avançado à telefonia, arquivamento e recursos de conformidade. A Skype for Business Online license must be assigned for each user. For more information on Lync Basic features, see [Skype for Business Online client comparison tables](/lyncserver/lync-server-2013-desktop-client-comparison-tables).
<br/><sup>4</sup> Ainda não está disponível GCC ambientes High ou DoD, mas em breve.
<br/><sup>5</sup> Consulte [Usando Outlook para iOS](/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud) e Android no Nuvem da Comunidade Governamental para obter mais detalhes.
<br/><sup>6</sup> Ainda não está disponível no Office 365 do DoD, mas em breve.
<br/><sup>7</sup> Os aplicativos estão totalmente disponíveis nas nuvens do governo, com exceção dos recursos específicos não disponíveis no momento. Consulte [Office disponibilidade de recursos do aplicativo](#office-application-and-feature-availability-in-government-plans) para obter detalhes.

## <a name="office-application-and-feature-availability-in-government-plans"></a>Office disponibilidade de recursos e aplicativos em planos governamentais

Os seguintes Office aplicativos estão disponíveis nas nuvens do governo; no entanto, alguns recursos baseados em nuvem podem não estar disponíveis no momento, conforme indicado na tabela.<br><br>

|Aplicativo/recurso|Recurso acessibilidade|CCG|CCG Alto|DOD|
|---|---|---|---|---|
|[**Microsoft Excel**](../../office-applications-service-description/office-applications.md#microsoft-excel) está totalmente disponível nas nuvens do governo, exceto os seguintes recursos, que não **estão** disponíveis no momento:|||||
|Animações 3D incorporadas e modelos 3D|Sim|Não|Não|Não|
|Tipos de dados||Não|Não|Não|
|Preenchimento flash||Não|Não|Não|
|Ideias (Insight Services)|Sim|Não|Não|Não|
|Integração aprimorada com Power BI (elementos visuais personalizados, crie gráficos PBI diretamente Excel)||Não|Não|Não|
|Tinta Digital Inteligente|Sim|Não|Não|Não|
|Grupos do Office 365||Não|Não|Não|
|Dados de Gráficos Dinâmicas conectados a Tabelas Dinâmicas||Não|Não|Não|
|PowerPivot||Não|Não|Não|
|Publicar no Power BI||Não|Não|Não|
|Colaboração em tempo real (presença, coautorização regular, chat no documento)|Alguns|Não|Não|Não|
|Shared with Me||Não|Não|Não|
|Pesquisa Inteligente|Sim|Não|Não|Não|
|Gráficos: mapa do sol, cascata, histograma, mapas, linha do tempo, funil||Não|Não|Não|
|Histórico de versão|Sim|Não|Não|Não|
|[**O Microsoft Forms**](https://support.office.com/article/5cbd407a-eef7-431e-8e3a-eb666eab4b4c) está totalmente disponível nas nuvens do governo, exceto os seguintes recursos, que não **estão** disponíveis no momento:||**GCC**|**GCC Alta**|**DOD**|
|Notificação de email||No<sup>1</sup>|No<sup>1</sup>|Não|
|Inserir uma imagem||No<sup>1</sup>|No<sup>1</sup>|Não|
|Inserir um vídeo||No<sup>1</sup>|No<sup>1</sup>|Não|
|Matemática||No<sup>1</sup>|No<sup>1</sup>|Não|
|Office integração||No<sup>1</sup>|No<sup>1</sup>|Não|
|Formulários de grupo mais recentes||Não<sup>4</sup>|Sim|Sim|
|Compartilhamento externo<sup>3</sup>||Sim|Não|Não|
|Formulários Pro||Não|Não|Não|
|[**Microsoft OneNote**](../../office-applications-service-description/office-applications.md#microsoft-onenote) está totalmente disponível nas nuvens do governo, exceto os seguintes recursos, que não **estão** disponíveis no momento:||**GCC**|**GCC Alta**|**DOD**|
|Pesquisador|Sim|Não|Não|Não|
|Tinta Digital Inteligente|Sim|Não|Não|Não|
|Enviar email para OneNote (me@onenote.com)|Sim|Não|Não|Não|
|Web Clipper||Não|Não|Não|
|[**O Microsoft Outlook**](../../office-applications-service-description/office-applications.md#microsoft-outlook) está totalmente disponível nas nuvens do governo, exceto os seguintes recursos, que não estão disponíveis em todas as Nuvens de Governo, conforme indicado na tabela abaixo.||**GCC**|**GCC Alta**|**DOD**|
|Office sons (alguns)|Sim|Não|Não|Não|
|DDE (Dynamic Data Exchange) desabilitado por padrão||Não|Não|Não|
|Ditado|Sim|Sim|Sim|No<sup>1</sup>|
|[**O Microsoft PowerPoint**](../../office-applications-service-description/office-applications.md#microsoft-powerpoint) está totalmente disponível nas nuvens do governo, exceto os seguintes recursos, que não estão disponíveis em todas as Nuvens de Governo, conforme indicado na tabela abaixo.||**GCC**|**GCC Alta**|**DOD**|
|Pesquisa Inteligente|Sim|Não|Não|Não|
|Office sons (alguns)||Não|Não|Não|
|Modelos 3D e animações 3D incorporadas||Não|Não|Não|
|Gráficos: mapas||Não|Não|Não|
|Tinta Digital Inteligente|Sim|Não|Não|Não|
|Legendas e legendas ao vivo PowerPoint|Sim|Sim|Sim|Não|
|Apresentações ao vivo||Não|Não|Não|
|Leitura Avançada|Sim|Não|Não|Não|
|Técnico de Apresentador|Sim|Não|Não|Não|
|Shared with Me||Não|Não|Não|
|Skype for Business integração com o compartilhamento||Não|Não|Não|
|Histórico de versão|Sim|Não|Não|Não|
|Grupos do Office 365||Não|Não|Não|
|Colaboração em tempo real (presença, coautorização regular, chat no documento)|Alguns|Não|Não|Não|
|Ditado|Sim|Sim|Sim|No<sup>1</sup>|
|Reutilizar slides||Não|Não|Não|
|**Microsoft Whiteboard** nas nuvens do governo está disponível apenas em clientes Hub e não na área de trabalho.||**GCC**<sup>2</sup>|**GCC Alta**<sup>2</sup>|**DOD**<sup>2</sup>|
|Inserir anotações, texto e imagens grudentas||Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|
|Tinta para forma e tinta para tabela|Sim|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|
|Autenticação de tinta|Sim|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|
|Converter imagem em tinta|Sim|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|
|Verificação de acessibilidade|Sim|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|
|Modelos dinâmicos (KANBAN, SWOT e assim por diante)|Sim|Não|Não|Não|
|Colaboração em tempo real|Sim|Não|Não|Não|
|Presença em tempo real|Sim|Não|Não|Não|
|Reações no conteúdo|Sim|Não|Não|Não|
|Galeria de quadro de whiteboards, incluindo compartilhado com você||Não|Não|Não|
|[**Microsoft Word**](../../office-applications-service-description/office-applications.md#microsoft-word) está totalmente disponível nas nuvens do governo, exceto os seguintes recursos, que não estão disponíveis em todas as Nuvens de Governo, conforme indicado na tabela abaixo.||**GCC**|**GCC Alta**|**DOD**|
|Pesquisa Inteligente|Sim|Não|Não|Não|
|Pesquisador|Sim|Não|Não|Não|
|Office sons||Não|Não|Não|
|Modelos 3D||Não|Não|Não|
|Animações 3D incorporadas||Não|Não|Não|
|Toque||Não|Não|Não|
|Assistente de Currículos|Sim|Não|Não|Não|
|Mapear gráficos||Não|Não|Não|
|Tinta Digital Inteligente|Sim|Não|Não|Não|
|Shared with Me||Não|Não|Não|
|Tradução||Sim<sup>5</sup>|Sim<sup>5</sup>|Sim<sup>5</sup>|
|Skype for Business integração com o compartilhamento||Não|Não|Não|
|Histórico de versão|Sim|Não|Não|Não|
|Grupos do Office 365||Não|Não|Não|
|Chat contextual com coautor: converse com coautor dentro do documento||Não|Não|Não|
|Ditado|Sim|Sim|Sim|No<sup>1</sup>|

Para disponibilidade de recursos para Microsoft Teams em GCC/GCC High/DoD, visite [Microsoft Teams descrição do serviço.](../../teams-service-description.md)
> <sup>1</sup> Disponibilidade futura.
<br/><sup>2</sup> Disponibilidade no Surface Hub local (não está assinada).
<br/><sup>3</sup> O compartilhamento externo está disponível para o GCC ambiente. Saiba mais sobre como desativar ou ativar [o Microsoft Forms](https://support.office.com/article/cc52287a-4550-464d-9a1b-457bf9df2240#PickTab=Configure) para sua organização. O compartilhamento externo está desabilitado GCC ambientes High e DOD; os usuários em sua organização podem fazer o seguinte: concluir um formulário e enviar [respostas,](https://support.office.com/article/82ea9d8a-260a-47a0-afdb-497f3d746e3f)duplicar e compartilhar um formulário como um modelo, [coautor](https://support.office.com/article/d5bb5cf0-8401-4c15-bb8c-8e108cd7e69b)ou colaborar em um formulário e acessar resultados [do formulário](https://support.office.com/article/02859424-341d-406f-b32a-9a0fbaf357af).
<br/><sup>4</sup> O recurso de formulários de grupo recente está desabilitado para o GCC ambiente. Os usuários, no entanto, ainda podem acessar formulários de grupo selecionando um grupo específico na guia Formulários de grupo.
<br/><sup>5</sup> Word, Excel PowerPoint Windows cliente, não Web, MacOS, iOS ou Android.
