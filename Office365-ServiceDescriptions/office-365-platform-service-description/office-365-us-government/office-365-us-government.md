---
title: Office 365 US Government
ms.author: danarl
author: danarl
manager: dianap
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 3f482abc-993f-41bf-8754-0f489a7e4861
description: Em resposta aos requisitos exclusivos e em evolução do setor público de Estados Unidos, a Microsoft criou os planos do governo dos EUA do Office 365 (ou o governo do Office 365). Esta seção fornece uma visão geral dos recursos que são específicos para os ambientes do governo dos EUA do Office 365. Recomendamos que você leia esta seção suplementar junto com as descrições de serviço do Office 365.
ms.openlocfilehash: ca251b876b2cc69d1f35524471e089003e71c4de
ms.sourcegitcommit: d21d9e6ea5780fab9a5987a10501cbf75cf107b7
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 12/18/2019
ms.locfileid: "40614830"
---
# <a name="office-365-us-government"></a>Office 365 US Government

Em resposta aos requisitos exclusivos e em evolução do setor público de Estados Unidos, a Microsoft criou os planos do governo dos EUA do Office 365 (ou o governo do Office 365). Esta seção fornece uma visão geral dos recursos que são específicos para os ambientes do governo dos EUA do Office 365. Recomendamos que você leia esta seção suplementar junto com as [descrições de serviço do Office 365 ](../../office-365-service-descriptions-technet-library.md).
  
## <a name="how-to-use-this-service-description-section"></a>Como usar a seção Descrição de Serviço

A Descrição de Serviço do Office 365 US Government foi criada para servir como uma sobreposição à Descrição de Serviço geral do Office 365. Ela define as diferenças e os compromissos exclusivos em comparação com as ofertas do Office 365 Enterprise.
  
## <a name="about-office-365-us-government-environments"></a>Sobre os ambientes do governo dos EUA do Office 365

Os planos do Office 365 US Government são assinaturas mensais e podem ser licenciados para um número ilimitado de usuários. 
  
- O ambiente do **Office 365 gcc** oferece conformidade com os requisitos federais para serviços de nuvem, incluindo FedRAMP moderados e requisitos para justiça criminal e sistemas de informações de tributação Federal (tipos de dados CJI e FTI). 
    
- Os ambientes do **Office 365 gcc High e DOD** oferecem conformidade com as diretrizes de requisitos de segurança do departamento de defesa, defesa Federal de aquisição de regulamentações (DFARS) e tráfego internacional em normas de braços (ITAR). 
    
Além dos recursos e capacidades do Office 365, as organizações que usam o Office 365 US Government se beneficiam dos seguintes recursos, que são exclusivos do Office 365 US Government:
  
- O conteúdo do cliente de sua organização é logicamente separado do conteúdo dos Serviços do Office 365 do cliente comercial da Microsoft.
    
- O conteúdo do cliente da sua organização é armazenado dentro dos Estados Unidos.
    
- O acesso ao conteúdo do cliente da sua organização é restrito à equipes selecionadas da Microsoft.
    
- O Office 365 US Government é compatível com certificações e reconhecimentos necessários para os clientes do Setor Público dos Estados Unidos.
    
[Seção como usar esta descrição de serviço](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="customer-eligibility"></a>Qualificação do cliente

O Office 365 US Government está disponível para (1) entidades governamentais federais, estaduais, locais, tribais e territoriais dos Estados Unidos e (2) outras entidades que manipulam dados sujeitos a requisitos e regulamentações do governo, em que o uso do Office 365 US Government é apropriado para satisfazer essas regulamentações que estão sujeitas a validação de qualificação. A validação de qualificação feita pela Microsoft incluirá a confirmação da manipulação de dados sujeitos ao ITAR (International Traffic in Arms Regulations), dados para a aplicação da lei sujeitos à política do Criminal Justice Information Services (CJIS) do FBI ou outros dados controlados ou regulamentados pelo governo. A validação poderá exigir a prova do registro no Departamento de Estado dos Estados Unidos para os dados do ITAR ou o aval de uma entidade governamental com requisitos específicos para a manipulação de dados. O ambiente do Office 365 DoD-é para uso exclusivo do departamento de defesa dos Estados Unidos.
  
Embora os critérios de qualificação sejam consistentes nas ofertas governamentais do Office 365, a Microsoft só concorda com a linguagem de contrato do DFARS e do ITAR para o ambiente de alta GCC.
  
As entidades que tenham dúvidas em relação à qualificação para o Office 365 US Government devem consultar a equipe de contas.
  
A qualificação precisa ser revalidada no momento da renovação do contrato do cliente para o Office 365 US Government.
  
[Seção como usar esta descrição de serviço](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="customer-content-located-within-the-united-states"></a>Conteúdo de cliente localizado nos Estados Unidos

Os serviços do Office 365 US Government são fornecidos por datacenters fisicamente localizados nos Estados Unidos. O seguinte conteúdo de cliente é armazenado em repouso em datacenters fisicamente localizados apenas nos EUA: 
  
- Conteúdo de caixa de correio do Exchange Online (corpos de email, entradas de calendário e conteúdo de anexos de email)
    
- Conteúdo do site do SharePoint Online e os arquivos armazenados nesse site
    
- Conversas arquivadas do Skype for Business, documentos carregados e sessões de quadro de comunicações

- Threads de chat persistente do Microsoft Teams
    
> [!NOTE]
> Normalmente, o Skype for Business não armazena conteúdo de clientes, mas se ocorrer algum armazenamento, ele será feito em datacenters nos EUA. 
  
Se os seus usuários estiverem localizados dentro dos Estados Unidos ao usar o Office para a Web (anteriormente conhecido como Office Web Apps) ou se você adotar o uso dos serviços de Federação do Active Directory (AD FS) 2,0 e configurar políticas para ajudar a garantir que os usuários se conectem aos serviços por meio de si mesmo GN-ligado, qualquer conteúdo do cliente que esteja temporariamente armazenado no Office para a Web estará localizado nos Estados Unidos.
  
[Seção como usar esta descrição de serviço](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="office-365-us-government-and-third-party-services"></a>Office 365 US Governmente serviços de terceiros

O Office 365 fornece a capacidade de integrar aplicativos de terceiros nos sites do SharePoint Online, no Skype for Business, nos aplicativos do Office incluídos no Office 365 (como o Word, Excel, PowerPoint e Outlook) e no Outlook Web App. Além disso, o Office 365 suporta a integração com provedores de serviços de terceiros. Estes aplicativos e serviços de terceiros podem envolver o armazenamento, a transmissão e o processamento dos dados de cliente da sua organização em sistemas de terceiros que estão localizados fora da infraestrutura do Office 365 e, portanto, não são cobertos pelos compromissos de conformidade e proteção de dados do Office 365. Recomendamos que você analise as instruções de privacidade e conformidade fornecidas por terceiros quando estiver avaliando o uso apropriado destes serviços para sua organização.
  
[Seção como usar esta descrição de serviço](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="restricted-data-access-by-administrators"></a>Acesso restrito aos dados pelos administradores

Acesso ao Office 365 o conteúdo do cliente governamental dos administradores da Microsoft está restrito ao pessoal em tela. Para obter detalhes sobre níveis de triagem, consulte a página de descrição do serviço para cada um dos respectivos ambientes (GCC ou GCC alta e DoD). 

  
## <a name="fasttrack-center-onboarding-assistance"></a>Assistência de integração do FastTrack Center

Com o benefício do FastTrack Center para o Office 365<sup>1</sup>, você trabalha remotamente com especialistas do FastTrack para que o seu ambiente do Office 365 fique pronto para uso e planeje a distribuição e o uso em sua organização. O processo FastTrack oferece integração e serviços de adoção do usuário.  
  
A integração consiste em:
  
- Integração básica-essas tarefas são necessárias para a configuração do locatário e a integração com o Azure Active Directory (Azure AD), se necessário. A integração básica também fornece a linha de base para integração de outros serviços qualificados.
    
- As tarefas de integração e integração do serviço de migração permitem cenários em seu locatário. A migração de dados (incluindo emails e arquivos) é abordada na [migração de dados](https://aka.ms/whatcanmigrate). <sup>2</sup>
    
Os serviços de adoção do usuário são compostos por tarefas que oferecem orientações para garantir que os usuários estejam cientes dos serviços qualificados e de que podem usá-los para impulsionar o valor comercial. Esta assistência ocorre paralelamente às atividades de integração.
  
As informações específicas sobre o processo do centro FastTrack podem ser encontradas [aqui](https://aka.ms/whatistheprocess). Para uma análise das funções e responsabilidades do contrato, revise as [responsabilidades do FastTrack](https://aka.ms/whatdoesftcdo) , bem como [suas responsabilidades](https://aka.ms/whatdowedo).
  
<sup>1</sup> você deve adquirir pelo menos 50 licenças da lista de [planos qualificados](https://aka.ms/whocanbenefit) para receber serviços do FastTrack, 
  
<sup>2</sup> os serviços de migração de dados estão disponíveis para locatários do Office 365 com 500 ou mais licenças. 
  
## <a name="data-migrations-performed-by-fasttrack"></a>Migrações de dados realizadas pelo FastTrack

Os clientes que escolhem o benefício de migração do [FastTrack](https://fasttrack.microsoft.com/) precisarão conceder acesso à equipe para gerenciar suas migrações de dados. Esses funcionários são cidadãos americanos e sofrem as verificações de segundo plano a seguir antes de realizar migrações para clientes dos serviços do governo dos EUA do Office 365. 
  
||||
|:-----|:-----|:-----|
|**Verificação de antecedentes** <br/> |**GCC** <br/> |**GCC alto e DoD** <br/> |
|Verificação de cidadania dos EUA  <br/> |Sim  <br/> |Sim  <br/> |
|Verificação do histórico de empregos  <br/> |Sim  <br/> |Sim  <br/> |
|Verificação de nível escolar  <br/> |Sim  <br/> |Sim  <br/> |
|Pesquisa de número de seguridade social (SSN)  <br/> |Sim  <br/> |Sim  <br/> |
|Verificação de antecedentes criminais dos últimos sete anos  <br/> |Sim  <br/> |Sim  <br/> |
   
[Seção como usar esta descrição de serviço](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="office-365-us-government-and-azure-government-expressroute"></a>Office 365 US Government e Microsoft Azure Government ExpressRoute

Os clientes do governo dos EUA do Office 365 podem usar os serviços do Azure governamental ExpressRoute para se conectarem de forma privada a serviços do Office 365 compatíveis, em vez de se conectarem pela Internet pública.
  
Para obter detalhes como provedores com suporte, modelos de preços e muito mais, examine as [informações do Azure ExpressRoute](https://go.microsoft.com/fwlink/?LinkID=798220&amp;clcid=0x409).
  
Para obter detalhes sobre o suporte do Office 365 para o Azure ExpressRoute, confira [Azure ExpressRoute para Office 365](https://go.microsoft.com/fwlink/?LinkID=798216&amp;clcid=0x409).
  
[Seção como usar esta descrição de serviço](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="system-requirements"></a>Requisitos do sistema

Para requisitos de sistema dos planos do Office 365 US Government, confira [Requisitos de sistema do Office](https://go.microsoft.com/fwlink/?LinkID=626095&amp;clcid=0x409) no site de produtos do [office.com](https://go.microsoft.com/fwlink/?LinkID=509817&amp;clcid=0x409). 
  
[Seção como usar esta descrição de serviço](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="security-amp-compliance-center"></a>Security &amp; Compliance Center

Para obter informações sobre o &amp; centro de conformidade de segurança e links para informações adicionais e disponibilidade, consulte o [centro de conformidade de &amp; segurança do Office 365](../../office-365-platform-service-description/office-365-securitycompliance-center.md).
  
## <a name="service-availability-for-each-plan"></a>Disponibilidade do serviço para cada plano

Cada plano do Office 365 inclui alguns serviços individuais, como o Exchange Online e o SharePoint Online. A tabela a seguir mostra os serviços disponíveis em cada plano do Office 365 US Government.
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**Serviços do Office 365** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 governo F1** <br/> |
|Office para a Web  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Office 365 ProPlus  <br/> |Não <br/> |Sim <br/> |Sim <br/> |Não  <br/> |
|Exchange Online  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Proteção do Exchange Online  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|SharePoint Online  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|OneDrive for Business  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Skype for Business (Instant Messaging &amp; Presence)  <br/> |Sim<sup>1</sup> <br/> |Sim  <br/> |Sim  <br/> |Sim<sup>1</sup> <br/> |
| Sistema de telefonia de voz, audioconferência  <br/> |Não<sup>2, 3</sup> <br/> |Não<sup>2, 3</sup> <br/> |Sim <sup>3, 5</sup> <br/> |Não  <br/> |
|Power BI Pro  <br/> |Não<sup>2</sup> <br/> |Não<sup>2</sup> <br/> |Sim  <br/> |Não<sup>2</sup> <br/> |
|Project Online  <br/> |Não<sup>2</sup> <br/> |Não<sup>2</sup> <br/> |Não<sup>2</sup> <br/> |Não<sup>2</sup> <br/> |
|Visio para a Web  <br/> |Não<sup>6</sup> <br/> |Não<sup>6</sup> <br/> |Não<sup>6</sup> <br/> |Não<sup>6</sup> <br/> |
|Yammer Enterprise  <br/> |No<sup>4</sup> <br/> |No<sup>4</sup> <br/> |No<sup>4</sup> <br/> |No<sup>4</sup> <br/> |
   
> <sup>1</sup> o Skype for Business Basic está disponível para todos os clientes. O cliente de desktop do Skype for Business é um aplicativo instalado localmente que fornece recursos de presença, mensagens instantâneas e conferências para planos do Office 365 que incluem o Skype for Business online. O Office 365 ProPlus, G3 e G5 incluem o aplicativo completo do Skype, que inclui recursos adicionais, como suporte avançado para telefonia, arquivamento e recursos de conformidade. A Skype for Business Online license must be assigned for each user.
<br/><sup>2</sup> não está incluído, mas pode ser adquirido como um complemento separado. O Project online inclui o cliente da área de trabalho do Project online como parte da assinatura.
<br/> <sup>3</sup> ainda não está disponível nos planos gcc High ou DOD, mas estará chegando em breve. 
<br/><sup>4</sup> o Yammer Enterprise não é um componente do governo dos EUA do Office 365, mas pode ser adquirido sem custo como uma oferta autônoma para cada usuário licenciado para o Office 365 em GCC. Atualmente, essa oferta é limitada a clientes que compram o Office 365 GCC sob acordos corporativos e contratos de assinatura corporativa. O Yammer não está disponível no GCC High ou no DoD.
<br/><sup>5</sup> o plano de chamadas é um complemento. 
<br/><sup>6</sup> não incluído, mas pode ser adquirido como um complemento separado. O Visio para a Web inclui o aplicativo da área de trabalho Visio como parte da assinatura.
## <a name="platform-features"></a>Recursos da plataforma 

A tabela a seguir exibe os recursos e serviços da plataforma que estão disponíveis nos planos do Office 365 US Government.
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 governo F1** <br/> |
|**Administração do Office 365** <br/> |||||
|Use o centro de administração do Microsoft 365 para administrar o Office 365  <br/> |Sim<sup>16</sup> <br/> |Sim<sup>16</sup> <br/> |Sim  <br/> |Sim<sup>16</sup> <br/> |
|Gerenciar as configurações de serviço principal do Office 365  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Usar o Windows PowerShell para gerenciar Office 365  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Proteger o conteúdo usando a Proteção de Informações do Azure  <br/> |Não<sup>1</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup>  <br/> |Não<sup>1</sup> <br/> |
|**[Recursos do Pacote do Office 365](../../office-365-platform-service-description/office-365-suite-features.md)** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 governo F1** <br/> |
|Microsoft Bookings  <br/> |Não  <br/> |Não  <br/> |Não  <br/> |Não  <br/> |
|Email de resumo da Microsoft  <br/> |Não  <br/> |Não  <br/> |Não  <br/> |Não  <br/> |
|Microsoft Flow  <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |
|Microsoft Forms  <br/> |Sim <br/> |Sim <br/> |Sim<br/> |Sim</sup> <br/> |
|API do Microsoft Graph  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Microsoft MyAnalytics  <br/> |Não <br/> |Não <br/> |Sim<sup>17</sup> <br/> |Não <br/> |
|Microsoft Planner  <br/> |Sim <br/> |Sim <br/> |Sim <br/> |Sim <br/> |
|Microsoft PowerApps  <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |
|Microsoft StaffHub  <br/> |Não <br/> |Não <br/> |Não <br/> |Não<br/> |
|Microsoft Stream  <br/> |Sim<sup>9, 15</sup> <br/> |Sim<sup>9, 15</sup> <br/> |Sim<sup>9, 15</sup> <br/> |Não  <br/> |
|Microsoft Sway  <br/> |Não <br/> |Não <br/> |Não <br/> |Não <br/> |
|Microsoft Teams  <br/> |Sim <br/> |Sim <br/> |Sim <br/> |Sim <br/> |
|Office Delve  <br/> |Sim<sup>17</sup> <br/> |Sim<sup>17</sup> <br/> |Sim  <br/> |Sim<sup>17</sup> <br/> |
|Grupos do Office 365  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|**[Gerenciamento de contas de usuário](../../office-365-platform-service-description/user-account-management.md)** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 governo F1** <br/> |
|Identidade de nuvem  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Identidade federada (logon único)  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Multi-factor Authentication  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Autenticação do fator de telefone  <br/> |Sim<sup>9</sup> <br/> |Sim<sup>9</sup> <br/> |Sim  <br/> |Sim<sup>9</sup> <br/> |
|Configuração de área de trabalho do Office 365  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Gerenciar usuários com o Office 365  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Carregamento em massa usando arquivos. csv  <br/> |Sim<sup>9</sup> <br/> |Sim<sup>9</sup> <br/> |Sim  <br/> |Sim<sup>9</sup> <br/> |
|Ferramenta de Sincronização de Diretórios  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Migração simples (substituição) do Exchange  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Excluir contas usando o Office 365  <br/> |Sim <sup>3</sup> <br/> |Sim <sup>3</sup> <br/> |Sim <sup>3</sup> <br/> |Sim <sup>3</sup> <br/> |
|O administrador pode redefinir a senha de usuário no Office 365 ou usando o Windows PowerShell  <br/> |Sim <sup>4</sup> <br/> |Sim <sup>4</sup> <br/> |Sim <sup>4</sup> <br/> |Sim <sup>4</sup> <br/> |
|Os usuários podem alterar sua própria senha  <br/> |Sim <sup>5</sup> <br/> |Sim <sup>5</sup> <br/> |Sim <sup>5</sup> <br/> |Sim <sup>5</sup> <br/> |
|Gerenciar licenças  <br/> |Sim<sup>7, 8</sup> <br/> |Sim<sup>7, 8</sup> <br/> |Sim<sup>7, 8</sup> <br/> |Sim<sup>7,8</sup> <br/> |
|Gerenciar grupos de segurança do Office 365  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Várias funções de administrador disponíveis  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Permitir que um parceiro administre o Office 365 para você  <br/> |Sim<sup>11</sup> <br/> |Sim<sup>11</sup> <br/> |Sim<sup>11</sup> <br/> |Sim<sup>11</sup> <br/> |
|Serviços do Azure Active Directory  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|**[Domínios](../../office-365-platform-service-description/domains.md)** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 governo F1** <br/> |
|Adicionar domínios de segundo nível personalizados, como fourthcoffee.com  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Adicionar domínios de terceiro nível personalizados, como marketing.fourthcoffee.com  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Adicionar até 900 domínios personalizados  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Verificação de propriedade de domínio necessária para domínios personalizados  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|**[Continuidade e integridade do serviço](../../office-365-platform-service-description/service-health-and-continuity.md)** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 governo F1** <br/> |
|Informação de status disponível na página **Integridade do serviço** ou **Status do serviço**  <br/> |Sim<sup>9, 15</sup> <br/> |Sim<sup>9, 15</sup> <br/> |Sim<sup>9, 15</sup> <br/> |Sim<sup>9, 15</sup> <br/> |
|Status de alertas individuais disponíveis no painel do centro de administração do 365 da Microsoft  <br/> |Sim<sup>9, 15</sup> <br/> |Sim<sup>9, 15</sup> <br/> |Sim<sup>9, 15</sup> <br/> |Sim<sup>9, 15</sup> <br/> |
|RSS feed de **Integridade do serviço**  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|**[Relatórios](../../office-365-platform-service-description/reports.md)** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 governo F1** <br/> |
|Caixas postais ativas e inativas  <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |
|Caixas de correio novas e excluídas  <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |
|Grupos novos e excluídos  <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |
|Uso da caixa de correio  <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |
|Tipos de conexões da caixa de correio  <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |
|Emails enviados e recebidos  <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |
|Principais remetentes e destinatários  <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |
|Detecções de spam  <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |
|Detecções de malware  <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |
|Principal malware para email  <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |
|Correspondências de regra para email  <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |
|Principais correspondências de regra para email  <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |
|Principais correspondências de política DLP para email  <br/> |Não  <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |
|Correspondências de política DLP por gravidade para email  <br/> |Não  <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |
|Correspondências, substituições e falsos positivos de política DLP para email  <br/> |Não  <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |
|Principais correspondências de regra DLP para email  <br/> |Não  <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |
|Sessões de mensagens instantâneas e áudio  <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |
|Compartilhamento de aplicativos, Webconferência e conferência discada  <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |
|Vídeo, compartilhamento de aplicativos e sessões de transferência de arquivos  <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |
|Mensagens instantâneas e conferências de áudio/vídeo  <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |
|Relatórios de proteção de email para download  <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |
|Navegador usado  <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |
|Sistema operacional usado  <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |
|Criar seus próprios relatórios usando serviços da Web de relatório do Office 365  <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |
|**[Atualizações de serviço](../../office-365-platform-service-description/service-updates.md)** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 governo F1** <br/> |
|Atualizações regulares fornecidas a todos os clientes  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Notificações enviadas para o Centro de Mensagens quando uma ação é necessária  <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |Sim<sup>15</sup> <br/> |
|Success.office.com/pt-br/roadmap para alguns serviços updates  <br/> |No<sup>10, 13</sup> <br/> |No<sup>10, 13</sup> <br/> |No<sup>10, 13</sup> <br/> |No<sup>10, 13</sup> <br/> |
|Opção para ativar a versão de destino  <br/> |Sim<sup>10</sup> <br/> |Sim<sup>10</sup> <br/> |Sim<sup>10</sup> <br/> |Sim<sup>10</sup> <br/> |
|**[Ajuda e treinamento](../../office-365-platform-service-description/help-and-training.md)** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 governo F1** <br/> |
|Ajuda online  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Comunidade  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Outros recursos de autoajuda  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Treinamento individual  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|**[Sistema de rede](../../office-365-platform-service-description/networking.md)** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 governo F1** <br/> |
|Protocolos IPv4 e IPv6  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|**Confiança** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 governo F1** <br/> |
|**[Privacidade, segurança e transparência](../../office-365-platform-service-description/privacy-security-and-transparency.md)** <br/> |||||
|Advanced Data Governance  <br/> |Nenhum<sup>12</sup> <br/> |Nenhum<sup>12</sup> <br/> |Sim <br/> |Nenhum<sup>12</sup> <br/> |
|Segurança no Aplicativo na Nuvem  <br/> |Nenhum<sup>12, 15, 19</sup> <br/> |Nenhum<sup>12, 15, 19</sup> <br/> |Sim<sup>15, 19</sup> <br/> |Nenhum<sup>12, 15, 19</sup> <br/> |
|Proteção Avançada contra Ameaças  <br/> |Nenhum<sup>12, 18</sup> <br/> |Nenhum<sup>12, 18</sup> <br/> |Sim<sup>18</sup>  <br/> |Nenhum<sup>12, 18</sup> <br/> |
|Sistema de Proteção de Dados do Cliente  <br/> |Nenhum<sup>12</sup> <br/> |Nenhum<sup>12</sup> <br/> |Sim <br/> |Nenhum<sup>12</sup> <br/> |
|Descoberta Eletrônica Avançada do Office 365  <br/> |Nenhum<sup>12</sup> <br/> |Nenhum<sup>12</sup> <br/> |Sim  <br/> |Nenhum<sup>12</sup> <br/> |
|Pontuação segura<sup>14</sup> <br/> |Sim<sup>9, 15</sup> <br/> |Sim<sup>9</sup> <br/> |Sim<sup>9, 15</sup> <br/> |Sim<sup>9, 15</sup> <br/> |
|Criptografia de mensagem do Office  <br/> |Não  <br/> |Sim <br/> |Sim <br/> |Não  <br/> |
|Inteligência contra Ameaças  <br/> |Nenhum<sup>12</sup> <br/> |Nenhum<sup>12</sup> <br/> |Sim <br/> |Nenhum<sup>12</sup> <br/> |
|**[Conformidade](../../office-365-platform-service-description/compliance-servicedesc.md)** <br/> |||||
|Avaliações SAS 70 / SSAE16  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Certificado ISO 27001  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Cláusulas do modelo da UE  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Safe Harbor da UE  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|HIPAA-Contrato de Associado de Negócios  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Autoridade FISMA para Operar  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Acordo de processamento de dados da Microsoft  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|PCI DSS nível um  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Dados de PAN controlados por PCI  <br/> |Não  <br/> |Não  <br/> |Não  <br/> |Não  <br/> |
|**[Continuidade de serviço](../../office-365-platform-service-description/service-health-and-continuity.md)** <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|**[BlackBerry](../../office-365-platform-service-description/blackberry.md)** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 governo F1** <br/> |
|Usar BIS (BlackBerry Internet Service)  <br/> |Não<sup>2</sup> <br/> |Não<sup>2</sup> <br/> |Não<sup>2</sup> <br/> |Não<sup>2</sup> <br/> |
|**[Parceiros](../../office-365-platform-service-description/partners.md)** <br/> |||||
|Criar convites para avaliação e ordens de compra para um cliente que está usando o plano especificado  <br/> |No<sup>11</sup> <br/> |No<sup>11</sup> <br/> |No<sup>11</sup> <br/> |No<sup>11</sup> <br/> |
|Fornecer administração delegada  <br/> |No<sup>11</sup> <br/> |No<sup>11</sup> <br/> |No<sup>11</sup> <br/> |No<sup>11</sup> <br/> |
|**[Contrato de Nível de Serviço](../../office-365-platform-service-description/service-level-agreement.md)** <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|**[Direitos de uso do produto](../../office-365-platform-service-description/product-use-rights.md)** <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
   
> <sup>1</sup> a proteção de informações do Azure não está incluída, mas pode ser adquirida como um complemento separado e habilitar os recursos de IRM (gerenciamento de direitos de informação) compatíveis. Alguns recursos de proteção de informações do Azure exigem uma assinatura do Office 365 ProPlus, que não está incluído no Office 365 governo G1 ou no Office 365 governo F1. > 
<br/><sup>2</sup> os clientes do BBCs e do BIS existentes podem continuar a usar o serviço. No momento, não aceitamos novos clientes. 
<br/><sup>3</sup> se estiver usando a sincronização de diretório, você deve excluir as contas ou alterar as senhas usando o Active Directory, em vez do portal do Office 365, ou usando o módulo do Azure Active Directory para Windows PowerShell. 
<br/><sup>4</sup> se estiver usando a sincronização de senha, os usuários devem alterar suas senhas no Active Directory local. 
<br/><sup>5</sup> para saber como configurar políticas de gerenciamento de senha de autoatendimento para usuários, confira [gerenciar senhas no Azure ad](https://azure.microsoft.com/documentation/articles/active-directory-manage-passwords/). 
<br/><sup>6</sup> você só pode ter um site público com o Office 365, a menos que tenha atualizado de uma versão anterior do Office 365. Nesse caso, é possível ter dois sites públicos, mas somente um deles pode ser hospedado com um nome de domínio personalizado. Para obter mais informações sobre como trabalhar com os dois sites para assinaturas comerciais, confira [trabalhar com seus dois sites públicos do Office 365](https://go.microsoft.com/fwlink/p/?LinkID=271589). Se você tiver uma assinatura diferente, saiba mais sobre sites públicos em [saiba mais sobre hospedagem de site de parceiros e sites públicos no Office 365](https://go.microsoft.com/fwlink/p/?LinkID=325009). 
<br/><sup>7</sup> a redução de estações que foram compradas com um desconto de termo pode estar sujeita a uma taxa de término antecipado. Isso não é aplicável a assinaturas pagas mensalmente. 
<br/><sup>8</sup> os planos a seguir não oferecem suporte a alterações de assentos de licenças do centro de administração do Microsoft 365: Office 365 governo G1, Office 365 governo G3, Office 365 governamental F1. 
<br/><sup>9</sup> ainda não está disponível no gcc High, mas está chegando em breve.
<br/><sup>10</sup> para o Office 365 governo G1, G3 e F1, lançamento direcionado e o mapa do Office 365 para empresas se aplicam; no entanto, pode haver algumas diferenças ou atrasos para atualizações de serviço específicas devido aos [requisitos de conformidade](https://www.microsoft.com/trust-center).
<br/><sup>11</sup> ainda não está disponível nas ofertas governamentais do Office 365, mas em breve. 
<br/><sup>12</sup> não está incluído, mas pode ser adquirido como um complemento separado no gcc. 
<br/><sup>13</sup> não têm suporte para ofertas governamentais do Office 365. 
<br/><sup>14</sup> disponível em [https://securescore.office.com](https://securescore.office.com). Requer permissões de administrador. Saiba mais em [Apresentando a Classificação de Segurança do Office 365](https://go.microsoft.com/fwlink/?linkid=836894). 
<br/><sup>15</sup> ainda não está disponível no ambiente DOD, mas estará chegando em breve. 
<br/><sup>16</sup> o centro de administração não inclui a análise de uso em ambientes do DoD ou gcc.
<br/><sup>17</sup> não tem suporte para ambientes gcc altos ou DOD.
<br/><sup>18</sup> o anti-phishing para representação de usuário e de domínio e inteligência de falsificação ainda não estão disponíveis no gcc High e no DOD.
<br/><sup>19</sup> ainda não está disponível no ambiente gcc, mas estará chegando em breve.
  
[Seção como usar esta descrição de serviço](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="office-application-features"></a>Recursos do aplicativo do Office  

A tabela a seguir mostra os recursos do aplicativo do Office que estão disponíveis nos planos do Office 365 US Government.
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 governo F1** <br/> |
|**Aplicativos do Office** <br/> |||||
|[Microsoft Word](../../office-applications-service-description/office-applications.md#microsoft-word) <br/> |Não  <br/> |Sim  <br/> |Sim  <br/> |Não  <br/> |
|[Microsoft Excel](../../office-applications-service-description/office-applications.md#microsoft-excel) <br/> |Não  <br/> |Sim  <br/> |Sim  <br/> |Não  <br/> |
|[Microsoft PowerPoint](../../office-applications-service-description/office-applications.md#microsoft-powerpoint) <br/> |Não  <br/> |Sim  <br/> |Sim  <br/> |Não  <br/> |
|[Microsoft OneNote](../../office-applications-service-description/office-applications.md#microsoft-onenote) <br/> |Não  <br/> |Sim  <br/> |Sim  <br/> |Não  <br/> |
|[Microsoft Outlook](../../office-applications-service-description/office-applications.md#microsoft-outlook) <br/> |Não  <br/> |Sim  <br/> |Sim  <br/> |Não  <br/> |
|[Microsoft Publisher](../../office-applications-service-description/office-applications.md#microsoft-publisher) <br/> |Não  <br/> |Sim  <br/> |Sim  <br/> |Não  <br/> |
|[Microsoft Access](../../office-applications-service-description/office-applications.md#microsoft-access) <br/> |Não  <br/> |Sim  <br/> |Sim  <br/> |Não  <br/> |
|[Skype for Business](../../office-applications-service-description/office-applications.md#skype-for-business) <br/> |Sim<sup>3</sup> <br/> |Sim  <br/> |Sim  <br/> |Sim<sup>3</sup> <br/> |
|[Office para Mac para o Office 365](https://support.office.com/article/General-requirements-for-Outlook-2016-for-Mac-A07A593D-B383-4906-A6C1-962D5543ED57) <br/> |Não  <br/> |Sim  <br/> |Sim  <br/> |Não  <br/> |
|[Office Mobile para iPad/iPhone](../../office-applications-service-description/office-applications.md#office-mobile-for-ipadiphone) <br/> |Sim  <br/> |Sim<sup></sup> <br/> |Sim<sup></sup> <br/> |Sim  <br/> |
|[Office Mobile para Android](../../office-applications-service-description/office-applications.md#office-mobile-for-android) <br/> |Sim  <br/> |Sim<sup></sup> <br/> |Sim<sup></sup> <br/> |Sim  <br/> |
|[Office Mobile para Windows Phone](../../office-applications-service-description/office-applications.md#office-mobile-for-windows-phone) <br/> |Sim  <br/> |Sim<sup>4</sup> <br/> |Sim<sup>4</sup> <br/> |Sim  <br/> |
|Office Mobile for Windows 10 tablets <br/> |Sim  <br/> |Sim<sup></sup> <br/> |Sim<sup></sup> <br/> |Sim  <br/> |
|Outlook para iOS e Android<sup>5, 4</sup>  <br/> |Sim <br/> |Sim <br/> |Sim <br/> |Sim <br/> |
|**Valor Corporativo** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 governo F1** <br/> |
|5 instalações por usuário em PC ou Mac  <br/> |Não  <br/> |Sim  <br/> |Sim  <br/> |Não  <br/> |
|Provisionamento automatizado de contas de usuário  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Interface de usuário multilíngue  <br/> |Não  <br/> |Sim  <br/> |Sim  <br/> |Não  <br/> |
|Implantação de push de cliente  <br/> |Não  <br/> |Sim<sup>4</sup> <br/> |Sim<sup>4</sup> <br/> |Não  <br/> |
|Suporte ao cliente para Exchange local  <br/> |Não  <br/> |Sim  <br/> |Sim  <br/> |Não  <br/> |
|Suporte ao cliente para SharePoint local  <br/> |Não  <br/> |Sim  <br/> |Sim  <br/> |Não  <br/> |
|Controle de atualizações de software  <br/> |Não  <br/> |Sim  <br/> |Sim  <br/> |Não  <br/> |
|Comparação de Banco de Dados  <br/> |Não  <br/> |Sim  <br/> |Sim  <br/> |Não  <br/> |
|Virtualização de área de trabalho  <br/> |Não  <br/> |Sim  <br/> |Sim  <br/> |Não  <br/> |
|Comparação de planilhas do Excel  <br/> |Não  <br/> |Sim  <br/> |Sim  <br/> |Não  <br/> |
|Pesquisa de planilhas do Excel  <br/> |Não  <br/> |Sim  <br/> |Sim  <br/> |Não  <br/> |
|Armazenamento e conformidade do Exchange Online e do SharePoint Online  <br/> |Não  <br/> |Sim  <br/> |Sim  <br/> |Não  <br/> |
|Suporte à Política de Grupo  <br/> |Não  <br/> |Sim  <br/> |Sim  <br/> |Não  <br/> |
|Gerenciamento de direitos de informação usando a proteção de informações do Azure  <br/> |Não<sup>1</sup> <br/> |Sim<sup>6</sup> <br/> |Sim<sup>6</sup> <br/> |Não<sup>1</sup> <br/> |
|Information Rights Management usando o Windows Server AD RMS  <br/> |Sim<sup>2</sup> <br/> |Sim<sup>2</sup> <br/> |Sim<sup>2</sup> <br/> |Sim<sup>2</sup> <br/> |
|Suporte a suplementos do Office, ActiveX e BHO  <br/> |Não  <br/> |Sim  <br/> |Sim  <br/> |Não  <br/> |
|Acesso de cliente do OneNote aos blocos de anotações no SharePoint Server, SharePoint Online, OneDrive for Business e Office 365  <br/> |Não  <br/> |Sim  <br/> |Sim  <br/> |Não  <br/> |
|Office Lens  <br/> |Não  <br/> |Não  <br/> |Não  <br/> |Não  <br/> |
|Telemetria do Office  <br/> |Não  <br/> |Sim<sup>4</sup> <br/> |Sim<sup>4</sup> <br/> |Não  <br/> |
|Suporte offline a aplicativos do cliente  <br/> |Não  <br/> |Sim  <br/> |Sim  <br/> |Não  <br/> |
|Instalação otimizada de cliente lado a lado  <br/> |Não  <br/> |Sim  <br/> |Sim  <br/> |Não  <br/> |
|Power Map para Excel  <br/> |Não  <br/> |Sim<sup>4</sup> <br/> |Sim<sup>4</sup> <br/> |Não  <br/> |
|Power Pivot para Excel  <br/> |Não  <br/> |Sim<sup>4</sup> <br/> |Sim<sup>4</sup> <br/> |Não  <br/> |
|Power Query para Excel  <br/> |Não  <br/> |Sim<sup>4</sup> <br/> |Sim<sup>4</sup> <br/> |Não  <br/> |
|Power View para Excel  <br/> |Não  <br/> |Sim<sup>4</sup> <br/> |Sim<sup>4</sup> <br/> |Não  <br/> |
|Configurações de roaming  <br/> |Não  <br/> |Sim<sup></sup> <br/> |Sim<sup></sup> <br/> |Não  <br/> |
|Ativação de computador compartilhado  <br/> |Não  <br/> |Sim<sup>4</sup> <br/> |Sim<sup>4</sup> <br/> |Não  <br/> |
|Suporte a bloqueio de armazenamento de arquivo baseado em nuvem  <br/> |Não  <br/> |Sim  <br/> |Sim  <br/> |Não  <br/> |
|Atualizações de versão  <br/> |Não  <br/> |Sim<sup>4</sup> <br/> |Sim<sup>4</sup> <br/> |Não  <br/> |
|Volume activation (KMS/MAK)  <br/> |Não  <br/> |Não  <br/> |Não  <br/> |Não  <br/> |
   
> <sup>1</sup> a proteção de informações do Azure não está incluída, mas pode ser adquirida como um complemento separado e habilitar os recursos de IRM (gerenciamento de direitos de informação) compatíveis. Alguns recursos de proteção de informações do Azure exigem uma assinatura do Office 365 ProPlus, que não está incluído no Office 365 governo G1 ou no Office 365 governo F1. 
<br/><sup>2</sup> o AD RMS para Windows Server é um servidor local que deve ser adquirido e gerenciado separadamente para habilitar os recursos de IRM compatíveis. 
<br/><sup>3</sup> o Skype for Business Basic está disponível para todos os clientes. O cliente de desktop do Skype for Business é um aplicativo instalado localmente que fornece recursos de presença, mensagens instantâneas e conferências para planos do Office 365 que incluem o Skype for Business online. O Office 365 ProPlus e o Office 365 Enterprise E3 incluem o aplicativo completo do Skype, que inclui recursos adicionais, como suporte avançado para telefonia, arquivamento e recursos de conformidade. A Skype for Business Online license must be assigned for each user. For more information on Lync Basic features, see [Skype for Business Online client comparison tables](https://docs.microsoft.com/lyncserver/lync-server-2013-desktop-client-comparison-tables). 
<br/><sup>4</sup> ainda não está disponível nos ambientes gcc High ou DOD, mas estará chegando em breve.
<br/><sup>5</sup> consulte [usando o Outlook para IOS e o Android na nuvem da Comunidade governamental](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud) para obter mais detalhes.
  <br/><sup>6</sup> ainda indisponível no ambiente do Office 365 DOD, mas disponível em breve.
<br/><br/>[Seção como usar esta descrição de serviço](office-365-us-government.md#how-to-use-this-service-description-section)
