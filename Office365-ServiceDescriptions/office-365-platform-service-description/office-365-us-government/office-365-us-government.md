---
title: Office 365 US Government
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 3f482abc-993f-41bf-8754-0f489a7e4861
description: Em resposta aos requisitos exclusivos e em evolução do setor público de Estados Unidos, a Microsoft criou os planos do governo dos EUA do Office 365 (ou o governo do Office 365). Este artigo fornece uma visão geral dos recursos que são específicos para os ambientes do governo dos EUA do Office 365.
ms.openlocfilehash: 63cef3dfac77ae22bc413deab9d375c1cd110b46
ms.sourcegitcommit: 04f9191b177e714a8dbdd50e7a891ff295483dbe
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 12/03/2020
ms.locfileid: "49566673"
---
# <a name="office-365-government"></a>Office 365 Government

> [!IMPORTANT]
> O Microsoft Teams está experimentando um grande pico em chamadas online e conferência de áudio/vídeo devido ao coronavirus (COVID-19) Pandemic.<br/>
>
>Em resposta ao aumento sem precedentes em chamadas e para garantir a continuidade e disponibilidade, a Microsoft está permitindo que os servidores de áudio/vídeo do Microsoft Teams GCC aproveitem a capacidade de processamento em nossos datacenters comerciais, bem como nos datacenters governamentais.<br/>
>
>Esses servidores de áudio/vídeo residem nos servidores de limite de capacitação de alta FedRAMP do Microsoft Azure nos Estados Unidos e não armazenam qualquer conteúdo do cliente. No entanto, esses servidores estão processando áudio e vídeo para chamadas e conferências e estão operando sob nossa equipe comercial durante esse período provisório.<br/>
>
>Qualificado, a equipe filtrada está monitorando esses servidores para obter acesso a dados dos clientes examinando quaisquer logs interativos nesses servidores. O pessoal qualificado atende aos requisitos de GCC para acesso ao conteúdo do cliente. Para obter detalhes sobre os requisitos de filtragem, consulte a [Descrição do serviço gcc](gcc.md).<br/>
>
>Obrigado pelo seu suporte à medida que realizarmos as etapas para garantir que nossos serviços permaneçam disponíveis e confiáveis nesses momentos extraordinários.<br/>

Em resposta aos requisitos exclusivos e em evolução do setor público de Estados Unidos, a Microsoft criou os planos governamentais do Office 365 (ou o governo do Office 365). Esta descrição de serviço fornece uma visão geral dos recursos que são específicos para os ambientes do governo dos EUA do Office 365. Recomendamos que você leia esta descrição de serviço junto com outras [descrições de serviço do Microsoft 365 e do Office 365](../../office-365-service-descriptions-technet-library.md).

## <a name="how-to-use-this-service-description"></a>Como usar a descrição deste serviço

A descrição do serviço do governo do Office 365 foi projetada para servir como uma sobreposição para a descrição geral do serviço do Office 365. Ela define as diferenças e os compromissos exclusivos em comparação com as ofertas do Office 365 Enterprise.

## <a name="about-office-365-government-environments"></a>Sobre ambientes governamentais do Office 365

Os planos governamentais do Office 365 são assinaturas mensais e podem ser licenciados para um número ilimitado de usuários.

- O ambiente do **Office 365 gcc** oferece conformidade com os requisitos federais para serviços de nuvem, incluindo o FedRAMP High e os requisitos para justiça criminal e sistemas de informações de tributação Federal (tipos de dados CJI e FTI).

- Os ambientes do **Office 365 gcc High e DOD** oferecem conformidade com as diretrizes de requisitos de segurança do departamento de defesa, defesa Federal de aquisição de regulamentações (DFARS) e tráfego internacional em normas de braços (ITAR).

Além dos recursos e capacidades do Office 365, as organizações que usam o Office 365 governamental se beneficiam dos seguintes recursos, exclusivos do Office 365 governamentais:

- O conteúdo do cliente de sua organização é logicamente separado do conteúdo dos Serviços do Office 365 do cliente comercial da Microsoft.

- O conteúdo do cliente da sua organização é armazenado dentro dos Estados Unidos.

- O acesso ao conteúdo do cliente da sua organização é restrito à equipes selecionadas da Microsoft.

- O governo do Office 365 cumpre as certificações e as autorizações necessárias para os clientes do setor público dos EUA.

## <a name="customer-eligibility"></a>Qualificação do cliente

O Office 365 governamental está disponível para (1) entidades governamentais, estaduais, locais, tribal e autarquia e outros, e (2) outras entidades que lidam com os dados sujeitos às normas e aos requisitos governamentais e onde o uso do Office 365 governamental é adequado para atender a esses requisitos, sujeito à validação da elegibilidade. A validação de qualificação feita pela Microsoft incluirá a confirmação da manipulação de dados sujeitos ao ITAR (International Traffic in Arms Regulations), dados para a aplicação da lei sujeitos à política do Criminal Justice Information Services (CJIS) do FBI ou outros dados controlados ou regulamentados pelo governo. A validação poderá exigir a prova do registro no Departamento de Estado dos Estados Unidos para os dados do ITAR ou o aval de uma entidade governamental com requisitos específicos para a manipulação de dados. O ambiente do Office 365 DoD é o uso exclusivo do departamento de defesa dos Estados Unidos.

Embora os critérios de qualificação sejam consistentes nas ofertas governamentais do Office 365, a Microsoft só concorda com a linguagem de contrato do DFARS e do ITAR para o ambiente de alta GCC.

As entidades com perguntas sobre a qualificação para o governo do Office 365 devem consultar a equipe de contas.

Após a renovação do contrato do cliente para o governo do Office 365, é necessário revalidar a qualificação.

## <a name="customer-content-located-within-the-united-states"></a>Conteúdo de cliente localizado nos Estados Unidos

Os serviços governamentais do Office 365 são fornecidos de datacenters fisicamente localizados nos Estados Unidos. O seguinte conteúdo de cliente é armazenado em repouso em datacenters fisicamente localizados apenas nos EUA:

- Conteúdo de caixa de correio do Exchange Online (corpos de email, entradas de calendário e conteúdo de anexos de email)

- Conteúdo do site do SharePoint Online e os arquivos armazenados nesse site

- Conversas arquivadas do Skype for Business, documentos carregados e sessões de quadro de comunicações

- Threads de chat persistente do Microsoft Teams

> [!NOTE]
> Normalmente, o Skype for Business não armazena conteúdo de clientes, mas se ocorrer algum armazenamento, ele será feito em datacenters nos EUA.

Se os seus usuários estiverem localizados dentro dos Estados Unidos ao usar o Office para a Web (anteriormente conhecido como Office Web Apps) ou se você adotar o uso dos serviços de Federação do Active Directory (AD FS) 2,0 e configurar políticas para ajudar a garantir que os usuários se conectem aos serviços por meio de logon único, todo o conteúdo do cliente que estiver temporariamente armazenado no Office para a Web estará localizado

A página de uso do site para sites do SharePoint está disponível para planos governamentais, embora por conformidade, há alguns recursos desta página que estão disponíveis apenas para clientes comerciais. Para saber mais, confira [página de uso do site para sites do SharePoint no Microsoft 365](https://support.microsoft.com/office/2fa8ddc2-c4b3-4268-8d26-a772dc55779e).

## <a name="office-365-government-and-third-party-services"></a>Serviços governamentais e de terceiros do Office 365

O Office 365 oferece a capacidade de integrar aplicativos de terceiros em sites do SharePoint Online, Skype for Business, aplicativos do Office incluídos em aplicativos da Microsoft 365 para empresas (como Word, Excel, PowerPoint e Outlook) e Outlook Web App. Além disso, o Office 365 suporta a integração com provedores de serviços de terceiros. Estes aplicativos e serviços de terceiros podem envolver o armazenamento, a transmissão e o processamento dos dados de cliente da sua organização em sistemas de terceiros que estão localizados fora da infraestrutura do Office 365 e, portanto, não são cobertos pelos compromissos de conformidade e proteção de dados do Office 365. Recomendamos que você analise as instruções de privacidade e conformidade fornecidas por terceiros quando estiver avaliando o uso apropriado destes serviços para sua organização.

## <a name="restricted-data-access-by-administrators"></a>Acesso restrito aos dados pelos administradores

Acesso ao Office 365 o conteúdo do cliente governamental por administradores da Microsoft está restrito ao pessoal em tela. Para obter detalhes sobre níveis de filtragem, consulte a página descrição de serviço para cada ambiente (GCC ou GCC elevado e DoD).

## <a name="fasttrack-center-onboarding-assistance"></a>Assistência de integração do FastTrack Center

Com o benefício do FastTrack Center para o Office 365<sup>1</sup>, você trabalha remotamente com especialistas do FastTrack para que o seu ambiente do Office 365 fique pronto para uso e planeje a distribuição e o uso em sua organização. O processo FastTrack oferece integração e serviços de adoção do usuário. 

A integração consiste em:

- Integração básica-essas tarefas são necessárias para a configuração do locatário e a integração com o Azure Active Directory (Azure AD), se necessário. A integração básica também fornece a linha de base para integração de outros serviços qualificados.

- As tarefas de integração e integração do serviço de migração permitem cenários em seu locatário. A migração de dados (incluindo emails e arquivos) é abordada na [migração de dados](https://aka.ms/whatcanmigrate). <sup>2</sup>

Os serviços de adoção do usuário são compostos de tarefas que fornecem orientações para garantir que seus usuários estejam cientes dos serviços qualificados e possam usá-los para agregar valor de negócios. Esta assistência ocorre paralelamente às atividades de integração.

As informações específicas sobre o processo do centro FastTrack podem ser encontradas [aqui](https://aka.ms/whatistheprocess). Para uma análise das funções e responsabilidades do contrato, revise as [responsabilidades do FastTrack](https://aka.ms/whatdoesftcdo) , bem como [suas responsabilidades](https://aka.ms/whatdowedo).

> <sup>1</sup> você deve adquirir pelo menos 50 licenças da lista de [planos qualificados](https://aka.ms/whocanbenefit) para receber os serviços do FastTrack.
<br/><sup>2</sup> os serviços de migração de dados estão disponíveis para locatários do Office 365 com 500 ou mais licenças.

## <a name="data-migrations-performed-by-fasttrack"></a>Migrações de dados realizadas pelo FastTrack

Os clientes que escolhem o benefício de migração do [FastTrack](https://fasttrack.microsoft.com/) precisarão conceder acesso à equipe para gerenciar suas migrações de dados. Esses funcionários são cidadãos americanos e sofrem as verificações de segundo plano a seguir antes de realizar migrações para clientes dos serviços do governo dos EUA do Office 365.<br><br>

|Triagem de plano de fundo|CCG|GCC alto e DoD|
|---|---|---|
|Verificação de cidadania dos EUA|Sim|Sim|
|Verificação do histórico de empregos|Sim|Sim|
|Verificação de educação|Sim|Sim|
|Pesquisa de número de seguridade social (SSN)|Sim|Sim|
|Verificação de histórico criminal (7 anos)|Sim|Sim|

## <a name="office-365-us-government-and-azure-government-expressroute"></a>Office 365 US Government e Microsoft Azure Government ExpressRoute

Os clientes do governo dos EUA do Office 365 podem usar os serviços do Azure governamental ExpressRoute para se conectarem de forma privada a serviços do Office 365 compatíveis, em vez de se conectarem pela Internet pública.

Para obter detalhes, como provedores com suporte, modelos de preços e muito mais, revise as [informações do Azure ExpressRoute](https://go.microsoft.com/fwlink/?LinkID=798220&amp;clcid=0x409).

Para obter detalhes sobre o suporte do Office 365 para o Azure ExpressRoute, confira [Azure expressroute para Office 365](https://go.microsoft.com/fwlink/?LinkID=798216&amp;clcid=0x409)

## <a name="system-requirements"></a>Requisitos do sistema

Para requisitos de sistema dos planos do Office 365 US Government, confira [Requisitos de sistema do Office](https://go.microsoft.com/fwlink/?LinkID=626095&amp;clcid=0x409) no site de produtos do [office.com](https://go.microsoft.com/fwlink/?LinkID=509817&amp;clcid=0x409).

## <a name="security-amp-compliance-center"></a>Security &amp; Compliance Center

Para obter informações sobre o &amp; centro de conformidade de segurança e links para informações adicionais e disponibilidade, consulte [Security &amp; Compliance Center](../../office-365-platform-service-description/office-365-securitycompliance-center.md).

## <a name="service-availability-for-each-plan"></a>Disponibilidade do serviço para cada plano

Cada plano do Office 365 inclui alguns serviços individuais, como o Exchange Online e o SharePoint Online. A tabela a seguir mostra os serviços disponíveis em cada plano do Office 365 US Government.<br><br>

|Serviço do Office 365|Office 365 Government G1|Office 365 Government G3|Office 365 Government G5|Office 365 governo F3|
|---|---|---|---|---|
|Office na Web|Sim|Sim|Sim|Sim|
|Microsoft 365 Apps para empresas|Não|Sim|Sim|Não|
|Exchange Online|Sim|Sim|Sim|Sim|
|Proteção do Exchange Online|Sim|Sim|Sim|Sim|
|SharePoint Online|Sim|Sim|Sim|Sim|
|OneDrive for Business|Sim|Sim|Sim|Sim|
|Skype for Business (Instant Messaging &amp; Presence)|Sim<sup>1</sup>|Sim|Sim|Sim<sup>1</sup>|
|Sistema de telefonia de voz, audioconferência|Não<sup>2</sup>|Não<sup>2</sup>|Sim<sup>5</sup>|Não|
|Power BI Pro|Não<sup>2</sup>|Não<sup>2</sup>|Sim|Não<sup>2</sup>|
|Project Online|Não<sup>2</sup>|Não<sup>2</sup>|Não<sup>2</sup>|Não<sup>2</sup>|
|Visio para a Web|Não<sup>6</sup>|Não<sup>6</sup>|Não<sup>6</sup>|Não<sup>6</sup>|
|Yammer Enterprise|No<sup>4</sup>|No<sup>4</sup>|No<sup>4</sup>|No<sup>4</sup>|

> <sup>1</sup> o Skype for Business Basic está disponível para todos os clientes. O cliente de desktop do Skype for Business é um aplicativo instalado localmente que fornece recursos de presença, mensagens instantâneas e conferências para planos do Office 365 que incluem o Skype for Business online. Os aplicativos do Microsoft 365 para Enterprise, G3 e G5 incluem o aplicativo completo do Skype, que inclui recursos adicionais, como suporte avançado para telefonia, arquivamento e recursos de conformidade. A Skype for Business Online license must be assigned for each user.
<br/><sup>2</sup> não está incluído, mas pode ser adquirido como um complemento separado. O Project online inclui o cliente da área de trabalho do Project online como parte da assinatura.
<br/> <sup>3</sup> ainda não está disponível nos planos gcc High ou DOD, mas estará chegando em breve.
<br/><sup>4</sup> o Yammer Enterprise não é um componente do governo dos EUA do Office 365, mas pode ser adquirido sem custo como uma oferta autônoma para cada usuário licenciado para o Office 365 em GCC. Atualmente, essa oferta é limitada a clientes que compram o Office 365 GCC sob acordos corporativos e contratos de assinatura corporativa. O Yammer não está disponível no GCC High ou no DoD.
<br/><sup>5</sup> o plano de chamadas é um complemento.
<br/><sup>6</sup> não incluído, mas pode ser adquirido como um complemento separado. O Visio para a Web inclui o aplicativo da área de trabalho Visio como parte da assinatura.

## <a name="platform-features"></a>Recursos da plataforma 

A tabela a seguir exibe os recursos e serviços da plataforma que estão disponíveis nos planos do Office 365 US Government.<br><br>

|Recurso|Office 365 Government G1|Office 365 Government G3|Office 365 Government G5|Office 365 governo F3|
|---|---|---|---|---|
|**Administração do Office 365**|||||
|Use o centro de administração do Microsoft 365 para administrar o Office 365|Sim<sup>16</sup>|Sim<sup>16</sup>|Sim|Sim<sup>16</sup>|
|Gerenciar as configurações de serviço principal do Office 365|Sim|Sim|Sim|Sim|
|Usar o Windows PowerShell para gerenciar Office 365|Sim|Sim|Sim|Sim|
|Proteger o conteúdo usando a Proteção de Informações do Azure|Não<sup>1</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|Não<sup>1</sup>|
|**[Recursos do Pacote do Office 365](../../office-365-platform-service-description/office-365-suite-features.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 governo F3**|
|Microsoft Bookings|Não|Sim<sup>21</sup>|Sim<sup>21</sup>|Não|
|Email de resumo da Microsoft|Não|Não|Não|Não|
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
|**[Gerenciamento de contas de usuário](../../office-365-platform-service-description/user-account-management.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 governo F3**|
|Identidade de nuvem|Sim|Sim|Sim|Sim|
|Identidade federada (logon único)|Sim|Sim|Sim|Sim|
|Autenticação multifator|Sim|Sim|Sim|Sim|
|Autenticação do fator de telefone|Sim<sup>9</sup>|Sim<sup>9</sup>|Sim|Sim<sup>9</sup>|
|Configuração de área de trabalho do Office 365|Sim|Sim|Sim|Sim|
|Gerenciar usuários com o Office 365|Sim|Sim|Sim|Sim|
|Carregamento em massa usando arquivos. csv|Sim<sup>9</sup>|Sim<sup>9</sup>|Sim|Sim<sup>9</sup>|
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
|**[Domínios](../../office-365-platform-service-description/domains.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 governo F3**|
|Adicionar domínios de segundo nível personalizados, como fourthcoffee.com|Sim|Sim|Sim|Sim|
|Adicionar domínios de terceiro nível personalizados, como marketing.fourthcoffee.com|Sim|Sim|Sim|Sim|
|Adicionar até 900 domínios personalizados|Sim|Sim|Sim|Sim|
|Verificação de propriedade de domínio necessária para domínios personalizados|Sim|Sim|Sim|Sim|
|**[Continuidade e integridade do serviço](../../office-365-platform-service-description/service-health-and-continuity.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 governo F3**|
|Informação de status disponível na página **Integridade do serviço** ou **Status do serviço**|Sim<sup>9, 15</sup>|Sim<sup>9, 15</sup>|Sim<sup>9, 15</sup>|Sim<sup>9, 15</sup>|
|Status de alertas individuais disponíveis no painel do centro de administração do 365 da Microsoft|Sim<sup>9, 15</sup>|Sim<sup>9, 15</sup>|Sim<sup>9, 15</sup>|Sim<sup>9, 15</sup>|
|RSS feed de **Integridade do serviço**|Sim|Sim|Sim|Sim|
|**[Relatórios](../../office-365-platform-service-description/reports.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 governo F3**|
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
|Criar seus próprios relatórios usando os serviços Web de relatório do Microsoft 365|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|
|**[Atualizações de serviço](../../office-365-platform-service-description/service-updates.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 governo F3**|
|Atualizações regulares fornecidas a todos os clientes|Sim|Sim|Sim|Sim|
|Notificações enviadas para o Centro de Mensagens quando uma ação é necessária|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim<sup>15</sup>|
|Success.office.com/pt-br/roadmap para alguns serviços updates|No<sup>10, 13</sup>|No<sup>10, 13</sup>|No<sup>10, 13</sup>|No<sup>10, 13</sup>|
|Opção para ativar a versão de destino|Sim<sup>10</sup>|Sim<sup>10</sup>|Sim<sup>10</sup>|Sim<sup>10</sup>|
|**[Ajuda e treinamento](../../office-365-platform-service-description/help-and-training.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 governo F3**|
|Ajuda online|Sim|Sim|Sim|Sim|
|Comunidade|Sim|Sim|Sim|Sim|
|Outros recursos de autoajuda|Sim|Sim|Sim|Sim|
|Treinamento individual|Sim|Sim|Sim|Sim|
|**[Sistema de rede](../../office-365-platform-service-description/networking.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 governo F3**|
|Protocolos IPv4 e IPv6|Sim|Sim|Sim|Sim|
|**Confiança**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 governo F3**|
|**[Privacidade, segurança e transparência](../../office-365-platform-service-description/privacy-security-and-transparency.md)**|||||
|Advanced Data Governance|Nenhum<sup>12</sup>|Nenhum<sup>12</sup>|Sim|Nenhum<sup>12</sup>|
|Segurança no Aplicativo na Nuvem|Nenhum<sup>12, 15, 19</sup>|Nenhum<sup>12, 15, 19</sup>|Sim<sup>15, 19</sup>|Nenhum<sup>12, 15, 19</sup>|
|Microsoft defender para Office 365|Nenhum<sup>12, 18</sup>|Nenhum<sup>12, 18</sup>|Sim<sup>18</sup>|Nenhum<sup>12, 18</sup>|
|Sistema de Proteção de Dados do cliente|Nenhum<sup>12</sup>|Nenhum<sup>12</sup>|Sim|Nenhum<sup>12</sup>|
|Descoberta Eletrônica Avançada|Nenhum<sup>12</sup>|Nenhum<sup>12</sup>|Sim|Nenhum<sup>12</sup>|
|Pontuação segura<sup>14</sup>|Sim<sup>9, 15</sup>|Sim<sup>9</sup>|Sim<sup>9, 15</sup>|Sim<sup>9, 15</sup>|
|Criptografia de mensagem do Office|Não|Sim|Sim|Não|
|Inteligência contra Ameaças|Nenhum<sup>12</sup>|Nenhum<sup>12</sup>|Sim|Nenhum<sup>12</sup>|
|**[Conformidade](https://docs.microsoft.com/microsoft-365/compliance/offering-home)**|||||
|Avaliações SAS 70 / SSAE16|Sim|Sim|Sim|Sim|
|Certificado ISO 27001|Sim|Sim|Sim|Sim|
|Cláusulas do modelo da UE|Sim|Sim|Sim|Sim|
|Safe Harbor da UE|Sim|Sim|Sim|Sim|
|HIPAA-Contrato de Associado de Negócios|Sim|Sim|Sim|Sim|
|Autoridade FISMA para Operar|Sim|Sim|Sim|Sim|
|Acordo de processamento de dados da Microsoft|Sim|Sim|Sim|Sim|
|PCI DSS nível um|Sim|Sim|Sim|Sim|
|Dados de PAN controlados por PCI|Não|Não|Não|Não|
|**[Continuidade de serviço](../../office-365-platform-service-description/service-health-and-continuity.md)**|Sim|Sim|Sim|Sim|
|**[BlackBerry](../../office-365-platform-service-description/blackberry.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 governo F3**|
|Usar BIS (BlackBerry Internet Service)|Não<sup>2</sup>|Não<sup>2</sup>|Não<sup>2</sup>|Não<sup>2</sup>|
|**[Parceiros](../../office-365-platform-service-description/partners.md)**|||||
|Criar convites para avaliação e ordens de compra para um cliente que está usando o plano especificado|No<sup>11</sup>|No<sup>11</sup>|No<sup>11</sup>|No<sup>11</sup>|
|Fornecer administração delegada|No<sup>11</sup>|No<sup>11</sup>|No<sup>11</sup>|No<sup>11</sup>|
|**[Contrato de Nível de Serviço](../../office-365-platform-service-description/service-level-agreement.md)**|Sim|Sim|Sim|Sim|
|**[Direitos de uso do produto](../../office-365-platform-service-description/product-use-rights.md)**|Sim|Sim|Sim|Sim|

> <sup>1</sup> a proteção de informações do Azure não está incluída, mas pode ser adquirida como um complemento separado e habilitar os recursos de IRM (gerenciamento de direitos de informação) compatíveis. Alguns recursos de proteção de informações do Azure exigem uma assinatura para o Microsoft 365 aplicativos para empresas, que não está incluído no Office 365 governo G1 ou no Office 365 governo F3. >
<br/><sup>2</sup> os clientes do BBCs e do BIS existentes podem continuar a usar o serviço. No momento, não aceitamos novos clientes.
<br/><sup>3</sup> se estiver usando a sincronização de diretório, você deve excluir as contas ou alterar as senhas usando o Active Directory, em vez do portal do Office 365, ou usando o módulo do Azure Active Directory para Windows PowerShell.
<br/><sup>4</sup> se estiver usando a sincronização de senha, os usuários devem alterar suas senhas no Active Directory local.
<br/><sup>5</sup> para saber como configurar políticas de gerenciamento de senha de autoatendimento para usuários, confira [gerenciar senhas no Azure ad](https://azure.microsoft.com/documentation/articles/active-directory-manage-passwords/).
<br/><sup>6</sup> você só pode ter um site público com o Office 365, a menos que tenha atualizado de uma versão anterior do Office 365. Nesse caso, é possível ter dois sites públicos, mas somente um deles pode ser hospedado com um nome de domínio personalizado. Para obter mais informações sobre como trabalhar com os dois sites para assinaturas comerciais, confira [trabalhar com seus dois sites públicos do Office 365](https://go.microsoft.com/fwlink/p/?LinkID=271589). Se você tiver uma assinatura diferente, saiba mais sobre sites públicos em [saiba mais sobre hospedagem de site de parceiros e sites públicos no Office 365](https://go.microsoft.com/fwlink/p/?LinkID=325009).
<br/><sup>7</sup> a redução de estações que foram compradas com um desconto de termo pode estar sujeita a uma taxa de término antecipado. Isso não é aplicável a assinaturas pagas mensalmente.
<br/><sup>8</sup> os planos a seguir não oferecem suporte a alterações de assentos de licenças do centro de administração do Microsoft 365: Office 365 governo G1, Office 365 governo G3, Office 365 governamental F3.
<br/><sup>9</sup> ainda não está disponível no gcc High, mas está chegando em breve.
<br/><sup>10</sup> para o Office 365 governo G1, G3 e F3, lançamento direcionado e o mapa do Office 365 para empresas se aplicam; no entanto, pode haver algumas diferenças ou atrasos para atualizações de serviço específicas devido aos [requisitos de conformidade](https://www.microsoft.com/trust-center).
<br/><sup>11</sup> ainda não está disponível nas ofertas governamentais do Office 365, mas em breve.
<br/><sup>12</sup> não está incluído, mas pode ser adquirido como um complemento separado no gcc.
<br/><sup>13</sup> não têm suporte para ofertas governamentais do Office 365.
<br/><sup>14</sup> disponível em [https://securescore.office.com](https://securescore.office.com) . Requer permissões de administrador. Saiba mais em [Apresentando a Classificação de Segurança do Office 365](https://docs.microsoft.com/microsoft-365/security/mtp/microsoft-secure-score).
).
<br/><sup>15</sup> ainda não está disponível no ambiente DOD, mas estará chegando em breve.
<br/><sup>16</sup> o centro de administração não inclui a análise de uso em ambientes do DoD ou gcc.
<br/><sup>17</sup> não tem suporte para ambientes gcc altos ou DOD.
<br/><sup>18</sup> o anti-phishing para representação de usuário e de domínio e inteligência de falsificação ainda não estão disponíveis no gcc High e no DOD.
<br/><sup>19</sup> ainda não está disponível no ambiente gcc, mas estará chegando em breve.
<br/><sup>20</sup> consumo somente para o Microsoft Stream: sem publicação ou compartilhamento.
<br/><sup>21</sup> não está disponível para a API do Microsoft Graph ou o Microsoft Teams.

## <a name="office-application-availability-and-enterprise-value"></a>Disponibilidade de aplicativos do Office e valor corporativo

A tabela a seguir mostra os recursos do aplicativo do Office que estão disponíveis nos planos do Office 365 US Government.<br><br>

|Aplicativo/recurso|Office 365 Government G1|Office 365 Government G3|Office 365 Government G5|Office 365 governo F3|
|---|---|---|---|---|
|**Aplicativos do Office**|||||
|[Microsoft Word](../../office-applications-service-description/office-applications.md#microsoft-word)<sup>7</sup>|Não|Sim|Sim|Não|
|[Microsoft Excel](../../office-applications-service-description/office-applications.md#microsoft-excel)<sup>7</sup>|Não|Sim|Sim|Não|
|[Microsoft PowerPoint](../../office-applications-service-description/office-applications.md#microsoft-powerpoint)<sup>7</sup>|Não|Sim|Sim|Não|
|[Microsoft OneNote](../../office-applications-service-description/office-applications.md#microsoft-onenote)<sup>7</sup>|Não|Sim|Sim|Não|
|[Microsoft Outlook](../../office-applications-service-description/office-applications.md#microsoft-outlook)<sup>7</sup>|Não|Sim|Sim|Não|
|Microsoft Forms<sup>7</sup>|Sim|Sim <br/>|Sim|Não|
|Microsoft whiteboard<sup>7</sup>|Não|Sim|Sim|Não|
|[Microsoft Publisher](../../office-applications-service-description/office-applications.md#microsoft-publisher)|Não|Sim|Sim|Não|
|[Microsoft Access](../../office-applications-service-description/office-applications.md#microsoft-access)|Não|Sim|Sim|Não|
|[Skype for Business](../../office-applications-service-description/office-applications.md#skype-for-business)|Sim<sup>3</sup>|Sim|Sim|Sim<sup>3</sup>|
|[Office para Mac para o Office 365](https://support.office.com/article/General-requirements-for-Outlook-2016-for-Mac-A07A593D-B383-4906-A6C1-962D5543ED57)|Não|Sim|Sim|Não|
|[Office Mobile para iPad/iPhone](../../office-applications-service-description/office-applications.md#office-mobile-for-ipadiphone)|Sim|Sim<sup></sup>|Sim<sup></sup>|Sim|
|[Office Mobile para Android](../../office-applications-service-description/office-applications.md#office-mobile-for-android)|Sim|Sim<sup></sup>|Sim<sup></sup>|Sim|
|[Office Mobile para Windows Phone](../../office-applications-service-description/office-applications.md#office-mobile-for-windows-phone)|Sim|Sim<sup>4</sup>|Sim<sup>4</sup>|Sim|
|Office Mobile for Windows 10 tablets|Sim|Sim<sup></sup>|Sim<sup></sup>|Sim|
|Outlook para iOS e Android<sup>5, 4</sup>|Sim|Sim|Sim|Sim|
|**Valor corporativo**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 governo F3**|
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
|Gerenciamento de direitos de informação usando a proteção de informações do Azure|Não<sup>1</sup>|Sim<sup>6</sup>|Sim<sup>6</sup>|Não<sup>1</sup>|
|Information Rights Management usando o Windows Server AD RMS|Sim<sup>2</sup>|Sim<sup>2</sup>|Sim<sup>2</sup>|Sim<sup>2</sup>|
|Suporte a suplementos do Office, ActiveX e BHO|Não|Sim|Sim|Não|
|Acesso de cliente do OneNote aos blocos de anotações no SharePoint Server, SharePoint Online, OneDrive for Business e Office 365|Não|Sim|Sim|Não|
|Office Lens|Não|Não|Não|Não|
|Telemetria do Office|Não|Sim<sup>4</sup>|Sim<sup>4</sup>|Não|
|Suporte offline a aplicativos do cliente|Não|Sim|Sim|Não|
|Instalação otimizada de cliente lado a lado|Não|Sim|Sim|Não|
|Power Map para Excel|Não|Sim<sup>4</sup>|Sim<sup>4</sup>|Não|
|Power Pivot para Excel|Não|Sim<sup>4</sup>|Sim<sup>4</sup>|Não|
|Power Query para Excel|Não|Sim<sup>4</sup>|Sim<sup>4</sup>|Não|
|Power View para Excel|Não|Sim<sup>4</sup>|Sim<sup>4</sup>|Não|
|Configurações de roaming|Não|Sim<sup></sup>|Sim<sup></sup>|Não|
|Ativação de computador compartilhado|Não|Sim|Sim|Não|
|Suporte a bloqueio de armazenamento de arquivo baseado em nuvem|Não|Sim|Sim|Não|
|Atualizações de versão|Não|Sim<sup>4</sup>|Sim<sup>4</sup>|Não|
|Volume activation (KMS/MAK)|Não|Não|Não|Não|

> <sup>1</sup> a proteção de informações do Azure não está incluída, mas pode ser adquirida como um complemento separado e habilitar os recursos de IRM (gerenciamento de direitos de informação) compatíveis. Alguns recursos de proteção de informações do Azure exigem uma assinatura para o Microsoft 365 aplicativos para empresas, que não está incluído no Office 365 governo G1 ou no Office 365 governo F3.
<br/><sup>2</sup> o AD RMS para Windows Server é um servidor local que deve ser adquirido e gerenciado separadamente para habilitar os recursos de IRM compatíveis.
<br/><sup>3</sup> o Skype for Business Basic está disponível para todos os clientes. O cliente de desktop do Skype for Business é um aplicativo instalado localmente que fornece recursos de presença, mensagens instantâneas e conferências para planos do Office 365 que incluem o Skype for Business online. O Microsoft 365 aplicativos para empresas e o Office 365 Enterprise E3 incluem o aplicativo completo do Skype, que inclui recursos adicionais, como suporte avançado para telefonia, arquivamento e recursos de conformidade. A Skype for Business Online license must be assigned for each user. For more information on Lync Basic features, see [Skype for Business Online client comparison tables](https://docs.microsoft.com/lyncserver/lync-server-2013-desktop-client-comparison-tables).
<br/><sup>4</sup> ainda não está disponível nos ambientes gcc High ou DOD, mas estará chegando em breve.
<br/><sup>5</sup> consulte [usando o Outlook para IOS e o Android na nuvem da Comunidade governamental](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud) para obter mais detalhes.
<br/><sup>6</sup> ainda indisponível no ambiente do Office 365 DOD, mas disponível em breve.
<br/><sup>7</sup> os aplicativos estão totalmente disponíveis nas nuvens governamentais, com exceção dos recursos específicos não disponíveis no momento. Confira [disponibilidade de recursos de aplicativos do Office](#office-application-and-feature-availability-in-government-plans) para obter detalhes.

## <a name="office-application-and-feature-availability-in-government-plans"></a>Disponibilidade de recursos e aplicativos do Office em planos governamentais

Os seguintes aplicativos do Office estão disponíveis nas nuvens governamentais; no entanto, alguns recursos baseados na nuvem podem não estar atualmente disponíveis, conforme indicado na tabela.<br><br>

|Aplicativo/recurso|CCG|CCG Alto|DOD|
|---|---|---|---|
|O [**Microsoft Excel**](../../office-applications-service-description/office-applications.md#microsoft-excel) está totalmente disponível nas nuvens governamentais, exceto os seguintes recursos, que **não estão** disponíveis no momento:||||
|animações inseridas 3D e modelos 3D|Não|Não|Não|
|Tipos de dados|Não|Não|Não|
|Preenchimento relâmpago|Não|Não|Não|
|Ideias (serviços de informação)|Não|Não|Não|
|Integração aprimorada com o Power BI (Visual personalizado, criar gráficos do PBI diretamente do Excel)|Não|Não|Não|
|Tinta digital inteligente|Não|Não|Não|
|Grupos do Office 365|Não|Não|Não|
|Dados de gráficos dinâmicos conectados a tabelas dinâmicas|Não|Não|Não|
|PowerPivot|Não|Não|Não|
|Publicar no Power BI|Não|Não|Não|
|Colaboração em tempo real (presença, coautoria regular, chat em documento)|Não|Não|Não|
|Shared with Me|Não|Não|Não|
|Pesquisa Inteligente|Não|Não|Não|
|Gráficos: mapa solar, cascata, histograma, mapas, linha do tempo, funil|Não|Não|Não|
|Histórico de versão|Não|Não|Não|
|O [**Microsoft Forms**](https://support.office.com/article/5cbd407a-eef7-431e-8e3a-eb666eab4b4c) está totalmente disponível nas nuvens governamentais, exceto os seguintes recursos, que **não estão** disponíveis no momento:|**GCC**|**CCG Alto**|**DOD**|
|Notificação por email|Não<sup>1</sup>|Não<sup>1</sup>|Não|
|Inserir uma imagem|Não<sup>1</sup>|Não<sup>1</sup>|Não|
|Inserir um vídeo|Não<sup>1</sup>|Não<sup>1</sup>|Não|
|Matemática|Não<sup>1</sup>|Não<sup>1</sup>|Não|
|Integração do Office|Não<sup>1</sup>|Não<sup>1</sup>|Não|
|Formulários de grupo mais recentes|No<sup>4</sup>|Sim|Sim|
|Compartilhamento externo<sup>3</sup>|Sim|Não|Não|
|Forms pro|Não|Não|Não|
|O [**Microsoft OneNote**](../../office-applications-service-description/office-applications.md#microsoft-onenote) está totalmente disponível nas nuvens governamentais, exceto os seguintes recursos, que **não estão** disponíveis no momento:|**GCC**|**CCG Alto**|**DOD**|
|Pesquisador|Não|Não|Não|
|Tinta digital inteligente|Não|Não|Não|
|O [**Microsoft Outlook**](../../office-applications-service-description/office-applications.md#microsoft-outlook) está totalmente disponível nas nuvens governamentais, exceto os seguintes recursos, que **não estão** disponíveis no momento:|**GCC**|**CCG Alto**|**DOD**|
|Sons do Office (alguns)|Não|Não|Não|
|DDE (troca dinâmica de dados) desabilitado por padrão|Não|Não|Não|
|Ditado|Não<sup>1</sup>|Não<sup>1</sup>|Não<sup>1</sup>|
|O [**Microsoft PowerPoint**](../../office-applications-service-description/office-applications.md#microsoft-powerpoint) está totalmente disponível nas nuvens governamentais, exceto os seguintes recursos, que **não estão** disponíveis no momento:|**GCC**|**CCG Alto**|**DOD**|
|Pesquisa Inteligente|Não|Não|Não|
|Sons do Office (alguns)|Não|Não|Não|
|modelos 3D e animações incorporadas 3D|Não|Não|Não|
|Gráficos: mapas|Não|Não|Não|
|Tinta digital inteligente|Não|Não|Não|
|Legendas ao vivo e legendas no PowerPoint|Não|Não|Não|
|Apresentador|Não|Não|Não|
|Shared with Me|Não|Não|Não|
|Integração do Skype for Business com compartilhamento|Não|Não|Não|
|Histórico de versão|Não|Não|Não|
|Grupos do Office 365|Não|Não|Não|
|Colaboração em tempo real (presença, coautoria regular, chat em documento)|Não|Não|Não|
|Ditado|Não<sup>1</sup>|Não<sup>1</sup>|Não<sup>1</sup>|
|Reutilizar slides|Não|Não|Não|
|**O Microsoft whiteboard** em nuvens governamentais só está disponível atualmente em clientes de Hub, e não na área de trabalho.|**Gcc**<sup>2</sup>|**Gcc**<sup>2</sup> superior|**DOD**<sup>2</sup>|
|Inserir notas auto-adesivas, texto e imagens|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|
|Tinta para forma e tinta para tabela|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|
|Beautification de tinta|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|
|Converter imagem em tinta|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|
|Verificador de acessibilidade|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|Sim<sup>2</sup> <br/>|
|Modelos dinâmicos (KANBAN, SWOT e assim por diante)|Não|Não|Não|
|Colaboração em tempo real|Não|Não|Não|
|Presença em tempo real|Não|Não|Não|
|Reações no conteúdo|Não|Não|Não|
|Galeria de quadros de comunicações, incluindo compartilhado com você|Não|Não|Não|
|O [**Microsoft Word**](../../office-applications-service-description/office-applications.md#microsoft-word) está totalmente disponível nas nuvens governamentais, exceto os seguintes recursos, que **não estão** disponíveis no momento:|**GCC**|**CCG Alto**|**DOD**|
|Pesquisa Inteligente|Não|Não|Não|
|Pesquisador|Não|Não|Não|
|Sons do Office|Não|Não|Não|
|modelos 3D|Não|Não|Não|
|animações inseridas 3D|Não|Não|Não|
|Toque|Não|Não|Não|
|Assistente de Currículos|Não|Não|Não|
|Gráficos de mapa|Não|Não|Não|
|Tinta digital inteligente|Não|Não|Não|
|Shared with Me|Não|Não|Não|
|Tradução|Não|Não|Não|
|Integração do Skype for Business com compartilhamento|Não|Não|Não|
|Histórico de versão|Não|Não|Não|
|Grupos do Office 365|Não|Não|Não|
|Chat contextual com coautores: converse com coautores no documento|Não|Não|Não|
|Ditado|Não<sup>1</sup>|Não<sup>1</sup>|Não<sup>1</sup>|

Para obter disponibilidade de recursos do Microsoft Teams no GCC/GCC High/DoD, visite a [Descrição do serviço do Microsoft Teams](https://docs.microsoft.com/office365/servicedescriptions/teams-service-description).
> <sup>1</sup> disponibilidade em breve.
<br/><sup>2</sup> disponibilidade no Surface Hub local (não conectado).
<br/><sup>3</sup> o compartilhamento externo está disponível para o ambiente gcc. Saiba mais sobre como [desativar ou ativar o Microsoft Forms](https://support.office.com/article/cc52287a-4550-464d-9a1b-457bf9df2240#PickTab=Configure) para sua organização. O compartilhamento externo está desabilitado para ambientes GCC altos e DOD; os usuários da sua organização podem fazer o seguinte: concluir um formulário e enviar respostas, [duplicar e compartilhar um formulário como um modelo](https://support.office.com/article/82ea9d8a-260a-47a0-afdb-497f3d746e3f), [coautoria ou colaborar em um formulário](https://support.office.com/article/d5bb5cf0-8401-4c15-bb8c-8e108cd7e69b)e [acessar os resultados do formulário](https://support.office.com/article/02859424-341d-406f-b32a-9a0fbaf357af).
<br/><sup>4</sup> o recurso de formulários de grupo recentes está desabilitado para o ambiente gcc. No entanto, os usuários ainda podem acessar formulários de grupo selecionando um grupo específico na guia formulários de grupo.
