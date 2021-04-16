---
title: Descrição do serviço Microsoft Teams
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
description: Saiba mais sobre a disponibilidade de recursos e serviços do Microsoft Teams nos planos do Microsoft 365 e do Office 365.
ms.openlocfilehash: 8828199a8af848dcd2bf6945b111e0fd082c7a95
ms.sourcegitcommit: c3cdb8074129fd7dff942a10a4fe8604fca563b6
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/14/2021
ms.locfileid: "51767451"
---
# <a name="microsoft-teams-service-description"></a>Descrição do serviço Microsoft Teams

O Microsoft Teams é o hub do trabalho em equipe no Microsoft 365. O serviço do Teams habilita mensagens instantâneas, chamada de áudio e vídeo, reuniões online ricas, experiências móveis e recursos extensivos de webconferência. Além disso, o Teams fornece recursos de colaboração de arquivos e dados e extensibilidade e integra-se com o Microsoft 365 e outros aplicativos microsoft e parceiros.

O Skype for Business Online se retira em 31 [](https://techcommunity.microsoft.com/t5/Microsoft-Teams-Blog/Skype-for-Business-Online-to-Be-Retired-in-2021/ba-p/777833) de julho de 2021, que foi anunciado em 30 de julho de 2019. O Microsoft Teams é um serviço totalmente novo, criado para a nuvem do zero aproveitando o Azure e outras inovações de serviço da Microsoft. O Microsoft Teams é criado em grupos do Microsoft 365, Microsoft Graph e com a mesma segurança, conformidade e capacidade de gerenciamento de nível empresarial que o restante do Office 365. O Teams aproveita identidades armazenadas no Azure Active Directory (Azure AD). Esses serviços são fornecidos de data centers da Microsoft e são acessíveis aos usuários em uma ampla variedade de dispositivos de dentro de uma rede corporativa ou pela Internet. Para obter mais informações, consulte os cartazes de soluções de telefonia e arquitetura de TI do [Microsoft Teams.](/microsoftteams/teams-architecture-solutions-posters)

Esta descrição de serviço detalha as principais diferenças entre os serviços fornecidos em várias instalações na nuvem. As principais funcionalidades do Microsoft Teams não diferem entre as assinaturas. A disponibilidade dos recursos de conformidade depende do nível de assinatura. Para saber mais sobre segurança e conformidade do Teams, consulte [Segurança e conformidade no Microsoft Teams](/microsoftteams/security-compliance-overview).

Se os usuários foram migrados totalmente online, eles devem ter licenças do Teams e do Skype for Business Online para a funcionalidade completa do Teams, mesmo que o Skype for Business Online não seja usado.

## <a name="available-plans"></a>Planos disponíveis

Para obter informações detalhadas sobre o plano sobre assinaturas que permitem usuários para o Teams, consulte [Encontre o Microsoft Teams certo para sua empresa.](https://www.microsoft.com/microsoft-teams/compare-microsoft-teams-options) Detalhes adicionais podem ser encontrados na tabela de comparação [de soluções da Microsoft.](https://go.microsoft.com/fwlink/?linkid=2139145)

Os planos governamentais que suportam o Teams incluem o Office 365 G1 até o G5. Para obter mais informações, consulte [Planos do Office 365 Government](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans).

Todos os planos de assinatura com suporte estão qualificados para acesso ao cliente Web do Microsoft Teams, clientes de área de trabalho e aplicativos móveis.

O Microsoft Teams não está disponível como um serviço autônomo.

## <a name="feature-availability"></a>Disponibilidade de recursos

A tabela a seguir lista os principais recursos do Teams disponíveis nos planos. Certas advertências se aplicam. Consulte as notas de rodapé para obter mais informações. Esta tabela pode mudar sem aviso prévio.

Para entender mais sobre os recursos do Teams pela plataforma do sistema operacional, consulte [Recursos do Teams por plataforma](https://aka.ms/teamsfeaturesbyplatform).

Para a lista mais atualizada dos recursos do Teams nos planos do Microsoft 365 e do Office 365, consulte Encontre o Microsoft Teams certo [para sua empresa.](https://www.microsoft.com/microsoft-teams/compare-microsoft-teams-options)<br><br>

| Recurso | Planos de pequenas empresas | Planos empresariais | CCG | GCC - Alta | DOD | Planos de educação |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Chat  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Teams  <br/> |Sim <br/> |Sim <br/> |Sim <br/> |Sim<sup>1</sup>  <br/> |Sim<sup>1</sup>  <br/> |Sim  <br/> |
|Canais - Standard  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Canais - Privado  <br/> |Sim  <br/> |Sim<sup>2</sup>  <br/> |Sim <br/> |Não  <br/> |Não <br/> |Sim  <br/> |
|Reuniões  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Área de trabalho de áudio/vídeo do PowerPoint de compartilhamento de tela <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Voz  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim<sup>3</sup>  <br/> |Sim<sup>3</sup>  <br/> |Sim  <br/> |
|Audioconferência  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim<sup>3</sup>  <br/> |Sim<sup>3</sup>  <br/> |Sim  <br/> |
|Aplicativos, Bots, & Conectores  <br/> |Sim  <br/> |Sim  <br/> |Sim<sup>4</sup>  <br/> |Sim<sup>4</sup>  <br/> |Sim<sup>4</sup>  <br/> |Sim  <br/> |
|Eventos ao vivo  <br/> |Não  <br/> |Sim  <br/> |Sim  <br/> |Não<sup>5</sup>  <br/> |Não<sup>5</sup>  <br/> |Sim  <br/> |

<sup>1</sup> O Microsoft Teams GCC-High e o DOD suportam 2500 membros em uma equipe individual.<br/>
<sup>2</sup> O Microsoft Planner não está disponível no momento para acessar em canais privados.<br/>
<sup>3</sup> O roteamento direto deve ser configurado para que a voz e a audioconferência do Microsoft Teams funcionem no GCCH e no DoD.<br/>
<sup>4</sup> Aplicativos de terceiros e publicação de aplicativos não estão disponíveis nessas nuvens no momento.<br/>
<sup>5</sup> Eventos Ao Vivo não estão disponíveis no GCC-High ou no DOD no momento.<br/>

### <a name="cloud-voice-features"></a>Recursos de voz na nuvem

Para a audioconferência, sua organização deve comprar e atribuir uma licença de audioconferência a cada usuário que configura reuniões discar. Para os recursos do Teams que exigem planos de chamada, cada usuário precisa de um sistema de telefonia e um plano de chamadas domésticas ou domésticas e internacionais. Para saber mais, confira [Licenças de complemento do Microsoft Teams.](/microsoftteams/teams-add-on-licensing/microsoft-teams-add-on-licensing)

### <a name="live-events"></a>Eventos ao vivo

Essa oferta no Office 365 substitui a Transmissão de Reunião do Skype. Os recursos de eventos ao vivo estão disponíveis para planos de licenciamento, conforme detalhado no serviço Stream. Para obter mais informações, consulte a visão [geral de licenciamento do Microsoft Stream.](/stream/license-overview) O serviço de eventos ao vivo pode ser acessado por meio de Stream, Yammer ou Microsoft Teams. Para saber mais sobre os recursos de eventos ao vivo, consulte Eventos ao vivo no [Microsoft 365 no Yammer, Microsoft Teams e Microsoft Stream.](/stream/live-event-m365)

## <a name="learn-more"></a>Saiba mais

Para obter mais informações sobre o Teams, confira os seguintes recursos:
 
- [Documentação de administração do Microsoft Teams](/MicrosoftTeams)
- [Comunidade técnica do Microsoft Teams](https://techcommunity.microsoft.com/t5/microsoft-teams/ct-p/MicrosoftTeams)
- [Blog do Microsoft Teams](https://aka.ms/TeamsBlog)

### <a name="licensing-terms"></a>Termos de licenciamento

Para termos e condições de licenciamento para produtos e serviços adquiridos por meio de Programas de Licenciamento por Volume Comercial da Microsoft, consulte o [site Termos do Produto](https://www.microsoft.com/licensing/terms/). 

### <a name="messaging"></a>Mensagens

Para se manter informado das próximas alterações, incluindo recursos novos e alterados, manutenção planejada ou outros comunicados importantes, visite o Centro de Mensagens. Para obter mais informações, consulte [Central de mensagens](/microsoft-365/admin/manage/message-center).

### <a name="accessibility"></a>Acessibilidade

A Microsoft permanece comprometida com a segurança de seus dados e com a acessibilidade de nossos serviços. Para obter mais informações, consulte [o Centro de Confiação da Microsoft](https://www.microsoft.com/trust-center) e o Centro de Acessibilidade do [Office.](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)
