---
title: Continuidade e Integridade do Serviço
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-service-health
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0483499d-8972-4a8f-97bd-b82f5b138991
description: Os administradores do Microsoft Office 365 podem exibir o status dos serviços e descobrir quando a manutenção está agendada. As informações de integridade do serviço estão disponíveis a qualquer momento entrando no Office 365.
ms.openlocfilehash: 010d93d70ce69717d4b02e752fcafc7734851b5e
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/07/2019
ms.locfileid: "30466948"
---
# <a name="service-health-and-continuity"></a>Continuidade e Integridade do Serviço

Os administradores do Microsoft Office 365 podem exibir o status dos serviços e descobrir quando a manutenção está agendada. As informações de integridade do serviço estão disponíveis a qualquer momento entrando no Office 365.
  
> [!NOTE]
> Se você estiver usando o Office 365 operado pela 21Vianet, algumas das informações abaixo podem não se aplicar. Em vez disso, confira o [Contrato de Nível de Serviço da 21Vianet](http://www.21vbluecloud.com/office365/O365-SLA/). 
  
## <a name="view-status-of-services"></a>Exibir status dos serviços

A seção integridade do serviço do Office 365 mostra o status atual do serviço e os detalhes sobre interrupções de serviço e interrupções. As informações de manutenção planejadas estão disponíveis no centro de mensagens. Saiba mais em [Exibir o status dos seus serviços](https://docs.microsoft.com/office365/enterprise/view-service-health). 
  
## <a name="service-incidents"></a>Incidentes de serviço

Um incidente de serviço é um evento que afeta a disponibilidade de um serviço. Os incidentes de serviço podem ser causados por falhas de hardware ou software no centro de dados da Microsoft, uma conexão de rede com falha entre o cliente e a Microsoft ou um grande desafio de data center, como incêndio, inundação ou catástrofe regional. A maioria dos incidentes de serviço podem ser solucionados usando soluções de tecnologia e de processo da Microsoft e são resolvidos dentro de um curto período de tempo. No entanto, alguns incidentes de serviço são mais graves e podem levar a interrupções de longa duração.
  
Há dois tipos de notificações sobre os horários em que os serviços podem não estar disponíveis:
  
- **Eventos de manutenção planejados:** A manutenção planejada é atualizações regulares de serviços iniciados pela Microsoft para a infraestrutura e os aplicativos de software. Notificações de manutenção planejada informam aos clientes sobre o trabalho de serviço que podem afetar a funcionalidade de um serviço do Office 365. Os clientes são notificados não mais após cinco dias antes de todas as manutenções planejadas por meio do centro de mensagens no portal de administração do Office 365. A Microsoft normalmente planeja a manutenção para horários em que o uso do serviço é historicamente o mais baixo com base em fusos horários regionais. 
    
- **Tempo de inatividade não planejado:** incidentes de serviço não planejados ocorrem quando um dos serviços no pacote do Office 365 não está disponível ou não responde. 
    
## <a name="notification-policy"></a>Diretiva de notificação

Quando um incidente de serviço ocorre, a Microsoft reconhece que comunicações oportunas, direcionadas e precisas são essenciais para os clientes. A Microsoft notifica os administradores do Office 365 atualizando o painel de integridade de serviço específico do locatário (SDH) no portal de administração do Office 365. As atualizações de incidentes de serviço são fornecidas em uma cadência por hora ou, se uma cadência diferente for necessária, ela será definida no lançamento de comunicação do SDH. 
  
## <a name="service-health-communication-channels"></a>Canais de Comunicação do Serviço de Integridade

### <a name="office-365-admin-app"></a>Aplicativo de Administração do Office 365

O aplicativo admin para administradores de locatários do Office 365 oferece a capacidade de se conectar ao status do serviço do Office 365 da sua organização em qualquer lugar. Os administradores de locatários do Office 365 terão a capacidade de exibir as informações de integridade do serviço e as atualizações de status de manutenção de seus dispositivos móveis. Saiba mais na página [Perguntas frequentes sobre o aplicativo de administração](https://docs.microsoft.com/en-us/office365/admin/admin-overview/admin-mobile-app?view=o365-worldwide).
  
### <a name="office-365-management-pack-for-microsoft-system-center-2012-r2"></a>Pacote de Gerenciamento do Office 365 para Microsoft System Center 2012 R2

O Microsoft System Center é uma plataforma de gerenciamento integrada que ajuda a gerenciar o data center, os dispositivos clientes e os ambientes híbridos de TI na nuvem. Os administradores do Office 365 que usam o System Center agora têm a opção de importar o pacote de gerenciamento do Office 365, que permite exibir todas as comunicações de serviço no Operations Manager no System Center. O uso dessa ferramenta fornece acesso ao status dos seus serviços assinados, aos incidentes de serviço ativos e resolvidos e às comunicações do seu Centro de Mensagens. Saiba mais na postagem do blog [Novas ferramentas de administração do Office 365](https://blogs.office.com/2014/07/29/new-office-365-admin-tools/). 
  
### <a name="office-365-service-communications-api"></a>API de Comunicações de Serviço do Office 365

A API de Comunicações de Serviço do Office 365 permite que você acesse as comunicações de serviço do Office 365 da maneira desejada. Com essa nova ferramenta de administração, você pode criar ou conectar suas ferramentas às comunicações de serviço do Office 365, simplificando seu modo de monitoramento do ambiente. A API de Comunicações de Serviço permite que você monitore o seguinte em seu ambiente:
  
- Integridade do serviço em tempo real
    
- Comunicações do Centro de Mensagens
    
- Notificações de manutenção planejada
    
Saiba mais na postagem do blog [Novas ferramentas de administração do Office 365](https://blogs.office.com/2014/07/29/new-office-365-admin-tools/). 
  
## <a name="post-incident-reviews"></a>Análise de Pós-incidente

O compromisso da Microsoft com a melhoria contínua envolve a análise de impacto ao cliente de incidentes de serviço não planejados para minimizar a recorrência futura. 
  
Incidentes de serviço não planejados são definidos como interrupções de serviço de vários locatários que afetam o uso do serviço conforme definido por nossos SLAs de serviço e foram declarados como tal no painel de integridade do serviço.
  
 Para incidentes de serviço não planejados de impacto do cliente nos quais houve impacto abrangente e notável em um grande número de organizações, uma revisão preliminar após o incidente (PIR) será entregue através do painel de integridade do serviço dentro de 48 horas de incidente resolução, seguida de PIR finais dentro de cinco dias úteis. O relatório detalhado do PIR inclui: 
  
- Impacto na experiência do cliente e do usuário
    
- Data/hora de início e término do Incidente
    
- Linha do tempo detalhada de medidas de impacto e resolução
    
- Análise de causa principal e ações executadas para o aprimoramento contínuo
    
Para todos os outros incidentes de serviço, o painel de integridade do serviço fornecerá um resumo de feriados de incidentes, incluindo um resumo final do evento, a causa raiz preliminar, as horas de início e de término e detalhando as próximas etapas. Para essa categoria de incidente de serviço, uma PIR não é gerada. 
  
## <a name="service-continuity"></a>Continuidade do Serviço

As ofertas do Microsoft Office 365 são disponibilizadas por sistemas altamente resilientes que ajudam a manter o desempenho máximo do serviço. As provisões de continuidade do serviço são parte do design do sistema Office 365. Essas provisões permitem que o Office 365 se recupere rapidamente de eventos inesperados, como falha de hardware ou do aplicativo, corrupção de dados ou outros incidentes que afetam os usuários. Essas soluções de continuidade de serviço aplicam-se também durante paralisações catastróficas (por exemplo, catástrofes naturais ou um incidente dentro de um data center da Microsoft que torna todo o data center inoperável).
  
Observe que, após a recuperação de interrupções catastróficas, há um período de tempo antes de a redundância completa do data center ser restaurada para o serviço. Por exemplo, quando o Data Center 1 falha, os serviços são restaurados por recursos no Data Center 2. Entretanto, pode haver um período de tempo até que os serviços no Data Center 2 tenham suporte de continuidade de serviço, seja pelos recursos restaurados no Data Center 1 ou por novos recursos no Data Center 3. O [Contrato de Nível de Serviço](https://technet.microsoft.com/en-us/library/office-365-service-level-agreement.aspx) (SLA) do Office 365 se aplica durante esse tempo. O Office 365 operado pela 21Vianet tem um SLA diferente. Saiba mais no [site da 21Vianet](http://www.21vbluecloud.com/office365/O365-SLA/). 
  
## <a name="ensuring-data-availability"></a>Garantir a disponibilidade de dados

A Microsoft garante que os dados do cliente estarão disponíveis sempre que forem necessários, através dos seguires recursos:
  
- **Armazenamento de dados e redundância:** os dados dos clientes são armazenados em um ambiente redundante com recursos de proteção de dados robustos para permitir disponibilidade, continuidade dos negócios e recuperação rápida. Vários níveis de redundância de dados são implementados, variando desde discos redundantes para proteger contra falhas de disco local, a uma replicação de dados contínua, completa e até um data center geograficamente diversificado. 
    
- **Monitoramento de dados:** os serviços do Office 365 mantêm altos níveis de desempenho por meio do seguinte: 
    
  - **Bancos de dados de monitoramento:**
    
  - Processos bloqueados
    
  - Perda de pacote
    
  - Processos em fila
    
  - Latência de consulta
    
- **Realização de manutenção preventiva:** a manutenção preventiva inclui verificações de consistência de banco de dados, compressão periódica de dados e revisão de registros de erros. 
    
## <a name="support"></a>Suporte

As equipes de desenvolvimento e operações do Office 365 são complementadas por uma organização de suporte dedicado do Office 365, que desempenha um papel importante em fornecer aos clientes a continuidade de negócios. A equipe de suporte tem um profundo conhecimento do serviço e de seus aplicativos associados, bem como acesso direto aos especialistas da Microsoft em arquitetura, desenvolvimento e teste.
  
A organização de suporte se alinha intimamente com as operações e o desenvolvimento de produtos, oferece tempos de resolução rápidos e um canal para ouvir a opinião dos clientes. O feedback dos clientes fornece dados para os processos de planejamento, de desenvolvimento e de operações.
  
- **Acompanhamento de problemas online:** os clientes precisam saber que seus problemas serão abordados e precisam ter a possibilidade de acompanhar a resolução em tempo hábil. O portal do Office 365 fornece uma única interface baseada na Web para suporte. Os clientes podem usar o portal para adicionar e monitorar as solicitações de serviço e receber feedback de equipes de suporte da Microsoft. 
    
- **Autoajuda, apoiada pelo suporte pessoal contínuo:** o Office 365 oferece uma ampla variedade de recursos de autoajuda e ferramentas que podem ajudar os clientes a resolver problemas relacionados a serviços, sem exigir o suporte da Microsoft. 
    
Antes de os clientes necessitarem enviar solicitações de serviço, eles podem acessar os artigos da base de conhecimento e de Perguntas frequentes que fornecem ajuda imediata para os problemas mais comuns. Esses recursos são continuamente atualizados com as últimas informações, o que ajuda a evitar atrasos, fornecendo soluções para problemas conhecidos. No entanto, quando surge um problema que precisa da ajuda de um suporte profissional, os membros da equipe estão disponíveis para assistência imediata, por telefone e através do portal de administração, 24 horas por dia, 7 dias por semana.
  
Saiba mais no tópico [Suporte](https://technet.microsoft.com/en-us/library/office-365-support.aspx). 
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos nos planos do Office 365, consulte [Descrição de Serviço da Plataforma Office 365](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx).
  

