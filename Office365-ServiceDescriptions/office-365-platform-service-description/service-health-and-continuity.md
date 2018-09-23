---
title: Continuidade e Integridade do Serviço
ms.author: pebaum
author: pebaum
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
description: Os administradores do Microsoft Office 365 podem exibir o status dos serviços e descobrir quando manutenção é agendada. Informações de integridade do serviço estão disponíveis a qualquer momento por entrar no Office 365.
ms.openlocfilehash: cc19a26f7bef070837b1dfa53df927373fd35d3e
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24034935"
---
# <a name="service-health-and-continuity"></a>Continuidade e Integridade do Serviço

Os administradores do Microsoft Office 365 podem exibir o status dos serviços e descobrir quando manutenção é agendada. Informações de integridade do serviço estão disponíveis a qualquer momento por entrar no Office 365.
  
> [!NOTE]
> Se você estiver usando o Office 365 operado pela 21Vianet, algumas das informações abaixo podem não se aplicar. Em vez disso, confira o [Contrato de Nível de Serviço da 21Vianet](http://www.21vbluecloud.com/office365/O365-SLA/). 
  
## <a name="view-status-of-services"></a>Exibir status dos serviços

A seção de integridade do serviço do Office 365 mostra o status atual do serviço e obter detalhes sobre as interrupções no serviço e interrupções. Informações de manutenção planejada estão disponíveis no centro da mensagem. Para obter mais informações, consulte [Exibir o status de seus serviços](https://go.microsoft.com/fwlink/p/?LinkID=270178). 
  
## <a name="service-incidents"></a>Incidentes de serviço

Um incidente de serviço é um evento que afeta a entrega de um serviço. Incidentes de serviço podem ser causados por falhas de hardware ou software no Centro de dados da Microsoft, uma conexão de rede defeituoso entre o cliente e a Microsoft ou um desafio de centro de dados principais como incêndio, inundação ou catástrofe regional. A maioria dos incidentes de serviço podem ser atendidos com o uso de soluções de tecnologia e o processo Microsoft e serão resolvidos dentro de um curto período de tempo. No entanto, alguns incidentes de serviço são mais graves e podem causar interrupções de termos mais.
  
Existem dois tipos de notificações sobre vezes quando os serviços podem não estar disponíveis:
  
- **Planejado eventos de manutenção:** Manutenção planejada é atualizações de serviço de iniciadas pelo Microsoft regulares para os aplicativos de software e infraestrutura. Notificações de manutenção planejada informam os clientes sobre o trabalho de serviço que pode afetar a funcionalidade de um serviço do Office 365. Os clientes são notificados posteriormente de cinco dias antes de começar a todos os manutenção planejada por meio do Centro de mensagens no Portal de administração do Office 365. Microsoft normalmente planos de manutenção para horários quando uso do serviço historicamente mais baixo se baseia em fusos horários regionais. 
    
- **Tempo de inatividade não planejado:** incidentes de serviço não planejados ocorrem quando um dos serviços no pacote do Office 365 não está disponível ou não responde. 
    
## <a name="notification-policy"></a>Diretiva de notificação

Quando um incidente de serviço ocorre, a Microsoft reconhece que a comunicação em tempo hábil, direcionada e precisa é fundamentais para os clientes. Microsoft notifica os administradores do Office 365, atualizando o painel de integridade de serviço (SHD) da específica do locatário no Portal de administração do Office 365. Atualizações de incidentes de serviço são fornecidas em uma cadência por hora ou, se uma cadência diferente for necessária, será declarada no lançamento de comunicação do SHD. 
  
## <a name="service-health-communication-channels"></a>Canais de Comunicação do Serviço de Integridade

### <a name="office-365-admin-app"></a>Aplicativo de Administração do Office 365

O administrador App para administradores de Inquilino do Office 365 oferece a capacidade de se conectar com o status do serviço de Office 365 da sua organização em trânsito. Administradores do Office 365 locatário terão a habilidade de exibir serviço integridade manutenção e informações sobre atualizações de status de seus dispositivos móveis. Para obter mais informações, visite o [FAQ do aplicativo de administração](https://community.office365.com/en-us/w/manage/office-365-admin-app-faq.aspx).
  
### <a name="office-365-management-pack-for-microsoft-system-center-2012-r2"></a>Pacote de Gerenciamento do Office 365 para Microsoft System Center 2012 R2

Microsoft System Center é uma plataforma de gerenciamento integrado que ajuda você a gerenciar Datacenter, dispositivos cliente e híbrido em nuvem ambientes de TI. Os administradores do Office 365 que usam o System Center agora tem a opção de importar o pacote de gerenciamento do Office 365, que permite que eles vejam todas as comunicações de serviço no Operations Manager no System Center. Usando essa ferramenta fornece acesso ao status de seus serviços inscritos, serviço ativas e resolvidas incidentes e suas comunicações do Centro de mensagens. Para obter mais informações, visite a postagem do blog de [Ferramentas de administração do novo Office 365](https://blogs.office.com/2014/07/29/new-office-365-admin-tools/) . 
  
### <a name="office-365-service-communications-api"></a>API de Comunicações de Serviço do Office 365

A API de Comunicações de Serviço do Office 365 permite que você acesse as comunicações de serviço do Office 365 da maneira desejada. Com essa nova ferramenta de administração, você pode criar ou conectar suas ferramentas às comunicações de serviço do Office 365, simplificando seu modo de monitoramento do ambiente. A API de Comunicações de Serviço permite que você monitore o seguinte em seu ambiente:
  
- Integridade do serviço em tempo real
    
- Comunicações do Centro de Mensagens
    
- Notificações de manutenção planejada
    
Saiba mais na postagem do blog [Novas ferramentas de administração do Office 365](https://blogs.office.com/2014/07/29/new-office-365-admin-tools/). 
  
## <a name="post-incident-reviews"></a>Análise de Pós-incidente

O compromisso da Microsoft com a melhoria contínua envolve a análise de impacto ao cliente de incidentes de serviço não planejados para minimizar a recorrência futura. 
  
Incidentes de serviço não planejado são definidos como interrupções do serviço de multilocatário que afetam o uso do serviço conforme definido pela SLAs nosso serviço e tem sido declaradas como tal, no painel de integridade do serviço.
  
 Para não planejado afetar o cliente incidentes de serviço em que houve amplo e perceptível impacto entre um grande número de organizações, uma revisão de pós-incidente preliminar (PIR) será entregue via seu painel de integridade do serviço dentro de um incidente 48 horas resolução, seguida por um PIR final dentro de cinco dias úteis. O relatório detalhado de PIR inclui: 
  
- Impacto na experiência do cliente e do usuário
    
- Data/hora de início e término do Incidente
    
- Linha do tempo detalhada de impacto e resolução de medidas
    
- Análise de causa principal e ações executadas para o aprimoramento contínuo
    
Para todos os outros incidentes de serviço, o painel de integridade do serviço fornecerá um resumo de fechamento de incidentes, incluindo um resumo final do evento, causas preliminar, início e término e informações que detalham as próximas etapas. Para esta categoria de incidente de serviço, um PIR não será gerado. 
  
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

As equipes de desenvolvimento e de operações do Office 365 são complementadas por uma organização de suporte dedicado do Office 365, que desempenha um papel importante em fornecer aos clientes a continuidade de negócios. A equipe de suporte tem um profundo conhecimento do serviço e de seus aplicativos associados, bem como acesso direto aos especialistas da Microsoft em arquitetura, desenvolvimento e teste.
  
A organização de suporte se alinha intimamente com as operações e o desenvolvimento de produtos, oferece tempos de resolução rápidos e um canal para ouvir a opinião dos clientes. O feedback dos clientes fornece dados para os processos de planejamento, de desenvolvimento e de operações.
  
- **Acompanhamento de problemas online:** os clientes precisam saber que seus problemas serão abordados e precisam ter a possibilidade de acompanhar a resolução em tempo hábil. O portal do Office 365 fornece uma única interface baseada na Web para suporte. Os clientes podem usar o portal para adicionar e monitorar as solicitações de serviço e receber feedback de equipes de suporte da Microsoft. 
    
- **Autoajuda, apoiada pelo suporte pessoal contínuo:** o Office 365 oferece uma ampla variedade de recursos de autoajuda e ferramentas que podem ajudar os clientes a resolver problemas relacionados a serviços, sem exigir o suporte da Microsoft. 
    
Antes de os clientes necessitarem enviar solicitações de serviço, eles podem acessar os artigos da base de conhecimento e de Perguntas frequentes que fornecem ajuda imediata para os problemas mais comuns. Esses recursos são continuamente atualizados com as últimas informações, o que ajuda a evitar atrasos, fornecendo soluções para problemas conhecidos. No entanto, quando surge um problema que precisa da ajuda de um suporte profissional, os membros da equipe estão disponíveis para assistência imediata, por telefone e através do portal de administração, 24 horas por dia, 7 dias por semana.
  
Saiba mais no tópico [Suporte](https://technet.microsoft.com/en-us/library/office-365-support.aspx). 
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos nos planos do Office 365, consulte [Descrição de Serviço da Plataforma Office 365](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx).
  

