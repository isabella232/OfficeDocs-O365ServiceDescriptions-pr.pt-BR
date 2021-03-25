---
title: Descrição do serviço Microsoft Teams
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
description: O Microsoft Teams fornece mensagens instantâneas, colaboração de arquivos e dados, chamada de áudio e vídeo, reuniões online ricas, experiências móveis e recursos extensivos de webconferência.
ms.openlocfilehash: ba8642a3b1260767fe4884a68d79aac5a511f4c4
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/24/2021
ms.locfileid: "51174036"
---
# <a name="microsoft-teams-service-description"></a>Descrição do serviço Microsoft Teams

O Microsoft Teams é o hub do trabalho em equipe no Microsoft 365. O serviço do Teams habilita mensagens instantâneas, chamada de áudio e vídeo, reuniões online ricas, experiências móveis e recursos extensivos de webconferência. Além disso, o Teams fornece recursos de colaboração de arquivos e dados e extensibilidade e integra-se com o Microsoft 365 e outros aplicativos microsoft e parceiros.

O Skype for Business Online será retirado em 31 de [](https://techcommunity.microsoft.com/t5/Microsoft-Teams-Blog/Skype-for-Business-Online-to-Be-Retired-in-2021/ba-p/777833) julho de 2021, que foi anunciado em 30 de julho de 2019. O Microsoft Teams é um serviço totalmente novo, criado para a nuvem do zero aproveitando o Azure e outras inovações de serviço da Microsoft. O Microsoft Teams é criado em grupos do Microsoft 365, Microsoft Graph e com a mesma segurança, conformidade e capacidade de gerenciamento de nível empresarial que o restante do Office 365. O Teams aproveita identidades armazenadas no Azure Active Directory (Azure AD). Esses serviços são fornecidos de data centers da Microsoft e são acessíveis aos usuários em uma ampla variedade de dispositivos de dentro de uma rede corporativa ou pela Internet. Para obter mais informações, consulte os cartazes de soluções de telefonia e arquitetura de TI do [Microsoft Teams.](/microsoftteams/teams-architecture-solutions-posters)

A Microsoft permanece comprometida com a segurança de seus dados e [com a acessibilidade](https://www.microsoft.com/trust-center/compliance/accessibility) de nossos serviços. Para obter mais informações, consulte [o Centro de Confiação da Microsoft](https://www.microsoft.com/trust-center) e o Centro de Acessibilidade do [Office.](https://support.office.com/article/Office-Accessibility-Center-Resources-for-people-with-disabilities-ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)

Para obter informações detalhadas sobre o plano sobre assinaturas que permitem usuários para o Microsoft Teams, consulte a [tabela de comparação de assinatura completa](https://go.microsoft.com/fwlink/?linkid=2139145). Para obter mais planos do Office 365 no Governo, consulte [Office 365 Government plans](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans). O Office 365 G1 a G5 inclui acesso aos recursos do Teams.

Para obter orientações detalhadas sobre a implementação de recursos do produto, consulte a documentação de [administração do Microsoft Teams.](/MicrosoftTeams) Esta descrição de serviço detalha as principais diferenças entre os serviços fornecidos em várias instalações na nuvem. As principais funcionalidades do Microsoft Teams não diferem entre as assinaturas. A disponibilidade dos recursos de conformidade depende do nível de assinatura. Para saber mais, confira [Segurança e conformidade no Microsoft Teams.](/microsoftteams/security-compliance-overview) Para ver uma lista detalhada dos recursos disponíveis em cada assinatura, consulte a descrição do serviço da plataforma [do Microsoft 365 e do Office 365.](./office-365-platform-service-description/office-365-platform-service-description.md)

**Recursos de voz** na nuvem : para audioconferência, sua organização deve comprar e atribuir uma licença de audioconferência a cada usuário que estará configurando reuniões discados. Para os recursos do Teams que exigem planos de chamada, cada usuário precisa de um sistema de telefonia e um plano de chamadas domésticas ou domésticas e internacionais. Para saber mais, confira [Licenças de complemento do Microsoft Teams.](/microsoftteams/teams-add-on-licensing/microsoft-teams-add-on-licensing)

**Eventos ao vivo**: Essa oferta no Office 365 substitui a Transmissão de Reunião do Skype reformada. Os recursos de eventos ao vivo estão disponíveis para planos de licenciamento, conforme detalhado no serviço Stream. Confira os detalhes [de licenciamento do Microsoft Stream aqui](/stream/license-overview). O serviço eventos ao vivo pode ser acessado por meio de Stream, Yammer ou Microsoft Teams. Para saber mais sobre os recursos de eventos ao vivo, consulte Eventos ao vivo no [Microsoft 365 no Yammer, Microsoft Teams e Microsoft Stream.](/stream/live-event-m365)

Todos os planos de assinatura com suporte estão qualificados para acesso ao cliente Web do Microsoft Teams, clientes de área de trabalho e aplicativos móveis.

O Microsoft Teams não está disponível como um serviço autônomo.

## <a name="feature-category-reference"></a>Referência de categoria de recurso

Esta tabela lista a disponibilidade de recursos do Microsoft Teams em planos de licenciamento ou instâncias de nuvem. Certas advertências se aplicam. Confira as notas de rodapé para obter mais informações. Esta tabela pode mudar sem aviso prévio. Consulte notificações do Centro de Mensagens do Microsoft 365 para mensagens de alteração de serviço principais e para a documentação de referência de termos de licenciamento [da Microsoft.](https://www.microsoft.com/licensing/product-licensing/products)<br><br>

| Recurso | Pequena empresa | Planos empresariais | CCG | GCC - Alta | DOD | Educação |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Chat  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Teams  <br/> |Sim <br/> |Sim <br/> |Sim <br/> |Sim<sup>1</sup>  <br/> |Sim<sup>1</sup>  <br/> |Sim  <br/> |
|Canais - Standard  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Canais - Privado  <br/> |Sim  <br/> |Sim<sup>2</sup>  <br/> |Sim <br/> |Não  <br/> |Não <br/> |Sim  <br/> |
|Reuniões  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Área de trabalho de áudio/vídeo do PowerPoint de compartilhamento de tela <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Voz  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim<sup>3</sup>  <br/> |Sim<sup>3</sup>  <br/> |Sim  <br/> |
|Audioconferência  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim<sup>3</sup>  <br/> |Sim<sup>3</sup>  <br/> |Sim  <br/> |
|Aplicativos, Bots, & Conectores  <br/> |Sim  <br/> |Sim  <br/> |Sim<sup>5</sup>  <br/> |Sim<sup>5</sup>  <br/> |Sim<sup>4,5</sup>  <br/> |Sim  <br/> |
|Eventos ao vivo  <br/> |Não  <br/> |Sim  <br/> |Sim  <br/> |Não<sup>6</sup>  <br/> |Não<sup>6</sup>  <br/> |Sim  <br/> |

> <sup>1</sup>  O Microsoft Teams GCC-High e o DOD suportam 2500 membros em uma equipe individual.<br/>
> <sup>2</sup> O Microsoft Planner não está disponível no momento para acessar em canais privados.<br/>
> <sup>3</sup> O roteamento direto deve ser configurado para que a voz e a audioconferência do Microsoft Teams funcionem no GCCH e no DoD.<br/>
> <sup>4</sup> O Microsoft OneNote não está disponível nas nuvens do DOD.<br/>
> <sup>5</sup> Aplicativos de terceiros e publicação de aplicativos não estão disponíveis nessas nuvens no momento.<br/>
> <sup>6</sup> Eventos Ao Vivo não estão disponíveis no GCC-High ou no DOD no momento.<br/>

## <a name="next-steps"></a>Próximas etapas

Comece a planejar sua implantação do Microsoft Teams visitando a [documentação técnica do Microsoft Teams.](/MicrosoftTeams/) Mantenha-se atualizado sobre os recursos e recursos do Teams, [juntando-se à](https://aka.ms/TeamsBlog)nossa comunidade e visitando nosso blog do Microsoft Teams.

Para entender mais sobre os recursos do Teams pela plataforma do sistema operacional, revise os [recursos do Teams pelo artigo de suporte da plataforma](https://aka.ms/teamsfeaturesbyplatform).