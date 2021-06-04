---
title: Descrição do serviço Microsoft Teams
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
description: Saiba mais sobre Microsoft Teams disponibilidade de recursos e serviços em Microsoft 365 e Office 365 planos.
ms.openlocfilehash: 721c4bd99fd8f81e471ea79e6725c2d6c53d1791
ms.sourcegitcommit: c455501e86037b0f86e0afc9d6d6d04afdfd3442
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/28/2021
ms.locfileid: "52074482"
---
# <a name="microsoft-teams-service-description"></a>Descrição do serviço Microsoft Teams

Microsoft Teams é o hub do trabalho em equipe Microsoft 365. O Teams permite mensagens instantâneas, chamada de áudio e vídeo, reuniões online ricas, experiências móveis e recursos extensivos de webconferência. Além disso, o Teams fornece recursos de colaboração e extensibilidade de arquivos e dados e se integra com Microsoft 365 e outros aplicativos da Microsoft e parceiros.

Skype for Business O online se retira em 31 de julho de 2021, que foi anunciado em 30 de julho de 2019. [](https://techcommunity.microsoft.com/t5/Microsoft-Teams-Blog/Skype-for-Business-Online-to-Be-Retired-in-2021/ba-p/777833) Microsoft Teams é um serviço totalmente novo, criado para a nuvem do zero aproveitando o Azure e outras inovações de serviço da Microsoft. Microsoft Teams é criado com base em grupos Microsoft 365, Microsoft Graph e com a mesma segurança, conformidade e capacidade de gerenciamento de nível empresarial que o restante Office 365. Teams utiliza identidades armazenadas no Azure Active Directory (Azure AD). Esses serviços são fornecidos de data centers da Microsoft e são acessíveis aos usuários em uma ampla variedade de dispositivos de dentro de uma rede corporativa ou pela Internet. Para obter mais informações, consulte os [cartazes Microsoft Teams de soluções](/microsoftteams/teams-architecture-solutions-posters)de telefonia e arquitetura de TI.

Esta descrição de serviço detalha as principais diferenças entre os serviços fornecidos em várias instalações na nuvem. Microsoft Teams principais funcionalidades não diferem entre as assinaturas. A disponibilidade dos recursos de conformidade depende do nível de assinatura. Para saber mais sobre Teams segurança e conformidade, consulte [Segurança e conformidade em Microsoft Teams](/microsoftteams/security-compliance-overview).

Se os usuários foram migrados totalmente online, eles devem ter licenças de equipe e Skype for Business Online para funcionalidade completa Teams, mesmo que o Skype for Business Online não seja usado.

## <a name="available-plans"></a>Planos disponíveis

Para obter informações detalhadas sobre o plano de assinaturas que habilitam os usuários para Teams, consulte Encontre a [Microsoft Teams correta para sua empresa](https://www.microsoft.com/microsoft-teams/compare-microsoft-teams-options). Detalhes adicionais podem ser encontrados na tabela de comparação [de soluções da Microsoft.](https://go.microsoft.com/fwlink/?linkid=2139145)

Planos governamentais que suportam Teams incluem Office 365 G1 a G5. Para obter mais informações, [consulte Office 365 Government planos](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans).

Todos os planos de assinatura com suporte estão qualificados para acesso ao cliente Microsoft Teams Web, clientes de área de trabalho e aplicativos móveis.

Microsoft Teams não está disponível como um serviço autônomo.

## <a name="feature-availability"></a>Disponibilidade de recursos

A tabela a seguir lista os principais recursos Teams disponíveis nos planos. Certas advertências se aplicam. Consulte as notas de rodapé para obter mais informações. Esta tabela pode mudar sem aviso prévio.

Para entender mais sobre Teams recursos pela plataforma do sistema operacional, [consulte Teams recursos por plataforma](https://aka.ms/teamsfeaturesbyplatform).

Para a lista mais atualizada e completa dos recursos Teams entre os planos Microsoft 365 e Office 365, consulte Encontre o Microsoft Teams correto [para sua empresa.](https://www.microsoft.com/microsoft-teams/compare-microsoft-teams-options)<br><br>

| Recurso | Planos de pequenas empresas | Enterprise planos | CCG | GCC - Alto | DOD | Planos de educação |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Chat  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Teams  <br/> |Sim <br/> |Sim <br/> |Sim <br/> |Sim<sup>1</sup>  <br/> |Sim<sup>1</sup>  <br/> |Sim  <br/> |
|Canais - Standard  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Canais - Privado  <br/> |Sim  <br/> |Sim<sup>2</sup>  <br/> |Sim <br/> |Não  <br/> |Não <br/> |Sim  <br/> |
|Reuniões  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Compartilhamento de tela PowerPoint área de trabalho de áudio/vídeo <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Voz  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim<sup>3</sup>  <br/> |Sim<sup>3</sup>  <br/> |Sim  <br/> |
|Audioconferência  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim<sup>3</sup>  <br/> |Sim<sup>3</sup>  <br/> |Sim  <br/> |
|Aplicativos, Bots, & Conectores  <br/> |Sim  <br/> |Sim  <br/> |Sim<sup>4</sup>  <br/> |Sim<sup>4</sup>  <br/> |Sim<sup>4</sup>  <br/> |Sim  <br/> |
|Eventos ao vivo  <br/> |Não  <br/> |Sim  <br/> |Sim  <br/> |Não<sup>5</sup>  <br/> |Não<sup>5</sup>  <br/> |Sim  <br/> |

<sup>1</sup> Microsoft Teams no GCC-High e o DOD suportam 2500 membros em uma equipe individual.<br/>
<sup>2</sup> O Microsoft Planner não está disponível no momento para acessar em canais privados.<br/>
<sup>3</sup> O roteamento direto deve ser configurado para que Microsoft Teams voz e audioconferência funcionem no GCCH e no DoD.<br/>
<sup>4</sup> Aplicativos de terceiros e publicação de aplicativos não estão disponíveis nessas nuvens no momento. Os conectores não têm suporte no GCCH e no DOD.<br/>
<sup>5</sup> Eventos Ao Vivo não estão disponíveis no GCC-High ou no DOD no momento.<br/>

### <a name="cloud-voice-features"></a>Recursos de voz na nuvem

Para a audioconferência, sua organização deve comprar e atribuir uma licença de audioconferência a cada usuário que configura reuniões discar. Para Teams recursos que exigem planos de chamadas, cada usuário precisa de um sistema de telefonia e um plano de chamadas domésticas ou domésticas e internacionais. Para saber mais, confira [Microsoft Teams licenças de complemento.](/microsoftteams/teams-add-on-licensing/microsoft-teams-add-on-licensing)

### <a name="live-events"></a>Eventos ao vivo

Essa oferta em Office 365 substitui o programa Reunião do Skype Broadcast. Os recursos de eventos ao vivo estão disponíveis para planos de licenciamento, conforme detalhado no serviço Stream. Para obter mais informações, consulte a visão [geral de licenciamento do Microsoft Stream.](/stream/license-overview) O serviço de eventos ao vivo pode ser acessado por meio do Stream, Yammer ou Microsoft Teams. Para saber mais sobre os recursos de eventos ao vivo, consulte [Live events across Microsoft 365 in Yammer, Microsoft Teams e Microsoft Stream](/stream/live-event-m365). Para saber mais sobre como planejar eventos ao vivo, incluindo requisitos de licença, consulte [Plan for live events in Microsoft Teams](/microsoftteams/teams-live-events/plan-for-teams-live-events).

## <a name="learn-more"></a>Saiba mais

Para obter mais informações Teams, confira os seguintes recursos:
 
- [Documentação de administração do Microsoft Teams](/MicrosoftTeams)
- [Microsoft Teams de tecnologia](https://techcommunity.microsoft.com/t5/microsoft-teams/ct-p/MicrosoftTeams)
- [Microsoft Teams blog](https://aka.ms/TeamsBlog)

### <a name="licensing-terms"></a>Termos de licenciamento

Para termos e condições de licenciamento para produtos e serviços adquiridos por meio de Programas de Licenciamento por Volume Comercial da Microsoft, consulte o [site Termos do Produto](https://www.microsoft.com/licensing/terms/). 

### <a name="messaging"></a>Mensagens

Para se manter informado das próximas alterações, incluindo recursos novos e alterados, manutenção planejada ou outros comunicados importantes, visite o Centro de Mensagens. Para obter mais informações, consulte [Central de mensagens](/microsoft-365/admin/manage/message-center).

### <a name="accessibility"></a>Acessibilidade

A Microsoft permanece comprometida com a segurança de seus dados e com a acessibilidade de nossos serviços. Para obter mais informações, consulte [o Centro de Confiação da Microsoft](https://www.microsoft.com/trust-center) e o Centro Office [Acessibilidade.](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)
