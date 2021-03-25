---
title: Saúde e continuidade do serviço
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-service-health
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0483499d-8972-4a8f-97bd-b82f5b138991
description: Os administradores da Microsoft podem exibir o status dos serviços e descobrir quando a manutenção está agendada. As informações de saúde do serviço estão disponíveis a qualquer momento ao entrar.
ms.openlocfilehash: ea9beb020d2f868eb51638c4729924a7ac873b7b
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/24/2021
ms.locfileid: "51174136"
---
# <a name="service-health-and-continuity"></a>Saúde e continuidade do serviço

Os administradores da Microsoft podem exibir o status dos serviços e descobrir quando a manutenção está agendada. As informações de saúde do serviço estão disponíveis a qualquer momento ao entrar.
  
> [!NOTE]
> Se você estiver usando o Office 365 operado pela 21Vianet, algumas das informações abaixo podem não se aplicar. Em vez disso, confira o [Contrato de Nível de Serviço da 21Vianet](https://www.21vbluecloud.com/office365/O365-SLA/). 
  
## <a name="view-status-of-services"></a>Exibir status dos serviços

A seção Saúde do serviço mostra o status atual do serviço e detalhes sobre interrupções e interrupções de serviço. Informações de manutenção planejadas estão disponíveis no Centro de Mensagens. Saiba mais em [Exibir o status dos seus serviços](/office365/enterprise/view-service-health). 
  
## <a name="service-incidents"></a>Incidentes de serviço

Um incidente de serviço é um evento que afeta a disponibilidade de um serviço. Incidentes de serviço podem ser causados por falha de hardware ou software no data center da Microsoft, uma conexão de rede defeituoso entre o cliente e a Microsoft ou um grande desafio do data center, como incêndio, inundação ou catástrofe regional. A maioria dos incidentes de serviço podem ser solucionados usando soluções de tecnologia e de processo da Microsoft e são resolvidos dentro de um curto período de tempo. No entanto, alguns incidentes de serviço são mais graves e podem levar a interrupções de longa duração.
  
Há dois tipos de notificações sobre os horários em que os serviços podem não estar disponíveis:
  
- **Eventos de manutenção planejados:** Manutenção planejada são atualizações regulares de serviço iniciadas pela Microsoft para a infraestrutura e aplicativos de software. As notificações de manutenção planejadas informam aos clientes sobre o trabalho de serviço que pode afetar a funcionalidade de um serviço da Microsoft. Os clientes são notificados com até cinco dias de antecedência de toda a manutenção planejada por meio do Centro de Mensagens no Centro de administração do Microsoft 365. Normalmente, a Microsoft planeja a manutenção para momentos em que o uso do serviço está historicamente em seu menor nível com base em fusos horários regionais. 
    
- **Tempo de inatividade não planejado:** Incidentes de serviço não planejados ocorrem quando um dos serviços não está disponível ou não responde. 

### <a name="recent-worldwide-uptimes"></a>Tempos de atividade recentes em todo o mundo

Mudar para um serviço de nuvem não deve significar perder a capacidade de saber o que está acontecendo. Com o Office 365, não. Nosso objetivo é ser transparente em nossas operações para que você possa monitorar o estado do seu serviço, controlar problemas e ter uma visão histórica da disponibilidade. As tabelas a seguir mostram dados recentes de tempo de atividade em todo o mundo.

**2020**

| P1 | P2 | Q3 | Q4 |
|:-----|:-----|:-----|:-----|
| 99.98% <br/> | 99,99%<br/> | 99.97%<br/> | 99.97%<br/> |

<br>

**2019**

| P1 | P2 | Q3 | Q4 |
|:-----|:-----|:-----|:-----|
| 99.97% <br/> | 99.97% <br/> | 99.98% <br/> | 99.98% <br/> |

<br>

**2018**

| P1 | P2 | Q3 | Q4 |
|:-----|:-----|:-----|:-----|
| 99,99% <br/> | 99.98% <br/> | 99.97% <br/> | 99.98% <br/> |

<br>

**2017**

| P1 | P2 | Q3 | Q4 |
|:-----|:-----|:-----|:-----|
| 99,99% <br/> | 99.97% <br/> | 99.98% <br/> | 99,99% <br/> |

## <a name="notification-policy"></a>Diretiva de notificação

Quando um incidente de serviço ocorre, a Microsoft reconhece que comunicações oportunas, direcionadas e precisas são essenciais para os clientes. A Microsoft notifica os administradores atualizando o ShD (Service Health Dashboard) específico do locatário no centro de administração do Microsoft 365. As atualizações de incidentes de serviço são fornecidas em uma cadência por hora ou, se uma cadência diferente for necessária, ela será afirmada na postagem de comunicação shd. 
  
## <a name="service-health-communication-channels"></a>Canais de comunicação de saúde do serviço

### <a name="admin-app"></a>Aplicativo de Administração

O Aplicativo de Administração para administradores da organização oferece a capacidade de se conectar com o status de serviço da Microsoft da sua organização em uso. Os administradores da Microsoft terão a capacidade de exibir as atualizações de status de manutenção e informações de saúde do serviço a partir de seus dispositivos móveis. Para saber mais, visite as [Perguntas frequentes do aplicativo de administração](/office365/admin/admin-overview/admin-mobile-app).
  
### <a name="office-365-management-pack-for-microsoft-system-center-2012-r2"></a>Pacote de Gerenciamento do Office 365 para Microsoft System Center 2012 R2

O Microsoft System Center é uma plataforma de gerenciamento integrada que ajuda a gerenciar o data center, os dispositivos clientes e os ambientes híbridos de TI na nuvem. Os administradores da Microsoft que usam o System Center agora têm a opção de importar o Pacote de Gerenciamento do Office 365, o que permite que eles ex view todas as comunicações de serviço no Operations Manager no System Center. O uso dessa ferramenta fornece acesso ao status dos seus serviços assinados, aos incidentes de serviço ativos e resolvidos e às comunicações do seu Centro de Mensagens. Para obter mais informações, obter o [Microsoft System Center Management Pack para Office 365](https://www.microsoft.com/download/details.aspx?id=43708) no Centro de Download da Microsoft. 
  
### <a name="office-365-service-communications-api"></a>API de Comunicações de Serviço do Office 365

A API de Comunicações de Serviço do Office 365 permite acessar as comunicações de serviço da maneira que você deseja. Com essa API, você tem a capacidade de criar ou conectar suas ferramentas às comunicações de serviço, simplificando potencialmente a maneira como você monitora seu ambiente. A API de Comunicações de Serviço permite que você monitore os seguintes itens do seu ambiente:
  
- Integridade do serviço em tempo real
    
- Comunicações do Centro de Mensagens
    
Para obter mais informações, consulte a referência da API de Comunicações de Serviço [do Office 365.](/office/office-365-management-api/office-365-service-communications-api-reference) 
  
## <a name="post-incident-reviews"></a>Análise de Pós-incidente

O compromisso da Microsoft com a melhoria contínua envolve a análise de impacto ao cliente de incidentes de serviço não planejados para minimizar a recorrência futura. 
  
Incidentes de serviço não planejados são definidos como interrupções de serviço de vários locatários que impactam o uso do serviço conforme definido por nossos contratos de nível de serviço (SLAs) e foram declarados como tal no Painel de Saúde do Serviço.
  
 Para incidentes de serviço não planejados que impactam o cliente nos quais houve um impacto amplo e perceptível em um grande número de organizações, uma REVISÃO preliminar pós-incidente (PIR) será entregue por meio do Painel de Saúde do Serviço dentro de 48 horas após a resolução de incidentes, seguido por um PIR final dentro de cinco dias úteis. O relatório PIR detalhado inclui: 
  
- Impacto na experiência do cliente e do usuário
    
- Data/hora de início e término do Incidente
    
- Linha do tempo detalhada das medidas de impacto e resolução
    
- Análise de causa principal e ações executadas para o aprimoramento contínuo
    
Para todos os outros incidentes de serviço, o Painel de Saúde do Serviço fornecerá um resumo de encerramento de incidentes, incluindo um resumo final do evento, causa raiz preliminar, horários de início e término e informações que detalham as próximas etapas. Para essa categoria de incidente de serviço, uma PIR não é gerada. 
  
## <a name="service-continuity"></a>Continuidade do serviço

As ofertas da Microsoft são entregues por sistemas altamente resilientes que ajudam a manter o desempenho de serviço de pico. As provisões de continuidade de serviço fazem parte do design do sistema. Essas disposições permitem que a Microsoft se recupere rapidamente de eventos inesperados, como falha de hardware ou aplicativo, corrupção de dados ou outros incidentes que afetam os usuários. Essas soluções de continuidade de serviço aplicam-se também durante paralisações catastróficas (por exemplo, catástrofes naturais ou um incidente dentro de um data center da Microsoft que torna todo o data center inoperável).
  
Observe que, após a recuperação de interrupções catastróficas, há um período de tempo antes de a redundância completa do data center ser restaurada para o serviço. Por exemplo, quando o Data Center 1 falha, os serviços são restaurados por recursos no Data Center 2. Entretanto, pode haver um período de tempo até que os serviços no Data Center 2 tenham suporte de continuidade de serviço, seja pelos recursos restaurados no Data Center 1 ou por novos recursos no Data Center 3. O Contrato [de Nível de](service-level-agreement.md) Serviço da Microsoft (SLA) se aplica durante esse tempo. O Office 365 operado pela 21Vianet tem um SLA diferente. Para obter mais informações, consulte o [site da 21Vianet](https://www.21vbluecloud.com/office365/O365-SLA/). 
  
## <a name="ensuring-data-availability"></a>Garantir a disponibilidade de dados

A Microsoft garante que os dados do cliente estarão disponíveis sempre que forem necessários, através dos seguires recursos:
  
- **Armazenamento de dados e redundância:** os dados dos clientes são armazenados em um ambiente redundante com recursos de proteção de dados robustos para permitir disponibilidade, continuidade dos negócios e recuperação rápida. Vários níveis de redundância de dados são implementados, variando desde discos redundantes para proteger contra falhas de disco local, a uma replicação de dados contínua, completa e até um data center geograficamente diversificado. 
    
- **Monitoramento de dados:** Os serviços da Microsoft mantêm altos níveis de desempenho monitorando: 
    
  - Bancos de dados
    
  - Processos bloqueados
    
  - Perda de pacote
    
  - Processos em fila
    
  - Latência de consulta
    
- **Realização de manutenção preventiva:** a manutenção preventiva inclui verificações de consistência de banco de dados, compressão periódica de dados e revisão de registros de erros. 
    
## <a name="support"></a>Suporte

As equipes de desenvolvimento e operações da Microsoft são complementadas por uma organização de suporte dedicada, que desempenha um papel importante no fornecimento de continuidade de negócios aos clientes. A equipe de suporte tem um profundo conhecimento do serviço e de seus aplicativos associados, bem como acesso direto aos especialistas da Microsoft em arquitetura, desenvolvimento e teste.
  
A organização de suporte intimamente se alinha com as operações e desenvolvimento de produtos, oferece tempos de resolução rápidos e um canal para ouvir a opinião dos clientes. O feedback dos clientes fornece dados para os processos de planejamento, desenvolvimento e operação.
  
- **Acompanhamento de problemas online:** os clientes precisam saber que seus problemas serão abordados e precisam ter a possibilidade de acompanhar a resolução em tempo hábil. O Centro de administração do Microsoft 365 fornece uma única interface baseada na Web para suporte. Os clientes podem usar o portal para adicionar e monitorar as solicitações de serviço e receber feedback de equipes de suporte da Microsoft. 
    
- **Auto-ajuda, com suporte contínuo da equipe:** A Microsoft oferece uma ampla variedade de recursos e ferramentas de auto-ajuda que podem ajudar os clientes a resolver problemas relacionados ao serviço sem exigir o suporte da Microsoft. 
    
Antes de os clientes necessitarem enviar solicitações de serviço, eles podem acessar os artigos da base de conhecimento e de Perguntas frequentes que fornecem ajuda imediata para os problemas mais comuns. Esses recursos são continuamente atualizados com as últimas informações, o que ajuda a evitar atrasos, fornecendo soluções para problemas conhecidos. No entanto, quando surge um problema que precisa da ajuda de um suporte profissional, os membros da equipe estão disponíveis para assistência imediata, por telefone e através do portal de administração, 24 horas por dia, 7 dias por semana.
  
Para obter mais informações sobre suporte, consulte o [artigo Suporte.](support.md) 
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos entre planos, consulte a descrição do serviço da plataforma [do Microsoft 365 e do Office 365.](office-365-platform-service-description.md)
