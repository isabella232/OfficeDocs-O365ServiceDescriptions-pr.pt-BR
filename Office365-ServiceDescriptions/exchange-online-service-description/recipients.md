---
title: Destinatários
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-recipients
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: da22b03a-c981-49c6-9928-4312c2c5e2ee
description: Este tópico descreve os recursos relacionados ao destinatário que fazem parte do Microsoft Exchange Online. Isso inclui e-mail, contatos, grupos de distribuição, agenda e as capacidades de agendamento.
ms.openlocfilehash: 775d47e9a8db4e516f60bc98e9763f61becf5b70
ms.sourcegitcommit: fb245074a57da585566096f6956d37325f451262
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/26/2019
ms.locfileid: "37734199"
---
# <a name="recipients"></a>Destinatários

Este tópico descreve os recursos relacionados ao destinatário que fazem parte do Microsoft Exchange Online. Isso inclui e-mail, contatos, grupos de distribuição, agenda e as capacidades de agendamento.
  
## <a name="email"></a>Email

Cada assinante do Microsoft Exchange Online recebe uma caixa de correio, e caixas de correio especiais estão disponíveis para o agendamento dos recursos de facilidades (como salas de conferência) e para o acesso multiusuário aos endereços de email compartilhados. Limites máximos de armazenamento se aplicam à maioria das caixas de correio, e os administradores podem controlar os tamanhos permitidos da caixa de correio. Notificações e restrições automáticas podem alertar os usuários quando suas caixas de correio atingirem sua capacidade ou estarem próximos de atingir. O Exchange Online também tem vários tipos de limitações de mensagenstamanho da mensagem, velocidade da mensagem e limites da lista de destinatários. Os detalhes de todos esses recursos e limites são fornecidos abaixo.
  
> [!NOTE]
> Não há mais suporte para Endereços catch-all no Exchange Online. Devido à filtragem de destinatários no local para proteção contra mensagens de spam em potencial, endereços de email que não existam no seu locatário do Office 365 serão rejeitados. 
  
### <a name="mailbox-types-storage-limits-and-capacity-alerts"></a>Tipos de caixa de correio, limites de armazenamento e alertas de capacidade

A quantidade de armazenamento da caixa de correio disponível para um usuário e o tamanho da caixa de correio padrão são determinados pelo tipo de caixa e licença de assinatura do usuário. Os administradores podem reduzir o tamanho máximo da caixa de correio por usuário ou globalmente. O Exchange Online também fornece notificações quando a caixa de correio de um usuário está perto de sua capacidade ou atingiu a capacidade.
  
Para mais informações, consulte as seções "Limites de armazenamento da caixa de correio" e "Alertas de capacidade" no tópico [Limites do Exchange Online](exchange-online-limits.md).
  
### <a name="mailtips"></a>MailTips

Dicas de Email são mensagens informativas e automáticas que aparecem acima da linha Para: enquanto os usuários estão redigindo ou endereçando uma mensagem. Elas são projetadas para ajudar a prevenir entregas acidentais, violações de políticas ou NDRs desnecessárias. Por exemplo, as Dicas de Email podem gerar um alerta caso os remetentes tentem enviar mensagens para grupos excessivamente grandes, para grupos com destinatários externos ou para um grupo de distribuição moderado ou restrito. Para saber mais, confira [Dicas de Email](https://go.microsoft.com/fwlink/p/?LinkId=401472).
  
### <a name="delegate-access"></a>Acesso de representante

O Exchange Online dá suporte ao acesso delegadoa habilidade para os usuários permitirem outros usuários a gerenciarem seus emails e calendários. O acesso delegado é normalmente usado entre um gerente e um assistente, no qual o assistente processa as mensagens de email de entrada do gerente e coordena a agenda do gerente. O acesso de representante pode ser habilitado por usuários do Exchange Online no Outlook ou no Outlook na Web ou por administradores no centro de administração do Exchange. 
  
Os representantes podem ter dois tipos de acesso:
  
- **Permissões Enviar em Nome de** O representante pode compor mensagens de email e inserir o nome de outra pessoa no campo De, onde será exibido "[nome do representante] em nome de [nome da pessoa]." 
    
- **Permissões Enviar como** O representante pode enviar mensagens a partir da caixa de correio de outra pessoa, como se o representante fosse o proprietário da caixa de correio. Esse cenário é comum onde há uma caixa de correio compartilhada da qual vários funcionários enviam mensagens de email, ao invés de enviá-las de suas próprias contas do Exchange Online. 
    
Para saber mais sobre como delegar acesso, consulte [Gerenciar Permissões de Destinatários](https://technet.microsoft.com/library/jj919240%28v=exchg.160%29.aspx).
  
### <a name="inbox-rules"></a>Regras da Caixa de Entrada

O Exchange Online permite que os usuários criem regras de caixa de entrada que desempenhem ações específicas, baseadas em critérios e de forma automática, nas mensagens, conforme elas chegam. Por exemplo, eles podem criar uma regra para mover automaticamente todos os emails para uma pasta específica, caso o email tenha sido enviado para um determinado grupo de distribuição. Os usuários gerenciam as regras de caixa de entrada do Outlook ou do Outlook na Web. Os administradores podem bloquear determinados tipos de regras da caixa de entrada, desabilitando o encaminhamento e/ou as respostas automáticas do servidor. Por exemplo, ao desabilitar o encaminhamento de emails do servidor, é possível evitar que os usuários encaminhem emails automaticamente para contas pessoais. Semelhantemente, ao desabilitar as respostas automáticas do servidor, é possível evitar que partes externas usem essas respostas para identificar endereços de email válidos. Essas alterações são feitas por meio do Windows PowerShell remoto.
  
### <a name="clutter"></a>Email secundário

O Email secundário foi desenvolvido para ajudar você a focar nas mensagens mais importantes da caixa de entrada. Ele utiliza o aprendizado de máquina para limpar a sua caixa de entrada movendo as mensagens de prioridade baixa para uma nova pasta do Email secundário. O Email secundário respeita as regras existentes do email; portanto, se você criou regras para organizar seu email, essas regras continuarão a ser aplicadas e o Email secundário não executará ações nestas mensagens. Por padrão, o Email secundário é desabilitado para a sua caixa de entrada. Para saber mais, confira [Limpar sua caixa de entrada no Office 365]( https://blogs.office.com/2014/11/11/de-clutter-inbox-office-365/).
  
### <a name="connected-accounts"></a>Contas conectadas

O recurso de contas conectadas permite que os usuários do Exchange Online conectem contas de email externas (como contas pessoais) às suas contas de email internas no Exchange Online e, em seguida, use o Outlook na Web para interagir com todas as suas mensagens em um só lugar. Contas conectadas são sincronizadas automaticamente após entrar no Outlook na Web; os usuários também podem sincronizar manualmente as contas do Outlook na Web. Os administradores podem habilitar e desabilitar esse recurso para usuários específicos ou todos os usuários por meio do [centro de administração do Exchange](https://go.microsoft.com/fwlink/?LinkID=785297&amp;clcid=0x409).
  
### <a name="inactive-mailboxes"></a>Caixas de correio inativas

O Exchange Online oferece a capacidade de preservar indefinidamente o conteúdo das caixas de correio excluídas. Esse recurso é chamado de caixas de correio inativas. Uma caixa de correio torna-se inativa quando uma Retenção local ou uma Retenção de litígio é aplicada na caixa de correio antes de ser excluída. Isso resulta no conteúdo da caixa de correio sendo preservado indefinidamente. Administradores, agentes de conformidade e gerentes de registro podem usar o recurso Descoberta Eletrônica Local no Exchange Online para acessar o conteúdo de uma caixa de correio inativa.
  
Habilitar uma caixa de correio inativa exige que a caixa de correio seja atribuída com uma licença do Exchange Online (plano 2) ou tenha uma assinatura do Exchange Online Archiving para que uma Retenção local ou uma Retenção de litígio possa ser aplicada na caixa de correio antes de ser excluída.
  
> [!IMPORTANT]
> Se não for aplicada uma espera à caixa de correio antes dela ser excluída, o conteúdo da caixa não será preservado nem poderá ser descoberto. A caixa de correio pode ser recuperada dentro de 30 dias após a exclusão, mas a caixa e seu conteúdo serão apagados de modo permanente após 30 dias se ela não for recuperada. 
  
Para mais informações, consulte:
  
- [Gerenciar caixas de correio inativas no Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=286991)
    
- [Bloqueio In-loco e Retenção de Litígio](https://go.microsoft.com/fwlink/p/?LinkId=271746)
    
- [Descoberta Eletrônica Local](https://go.microsoft.com/fwlink/p/?LinkId=271747)
    
## <a name="contacts-and-distribution-groups"></a>Contatos e grupos de distribuição

### <a name="offline-address-book"></a>Offline address book

O recurso catálogo de endereços offline fornece um instantâneo das informações do Active Directory disponíveis na GAL (lista de endereços global) do Outlook. Ele é colocado em cache localmente no Outlook, para que esteja disponível quando um usuário estiver trabalhando offline.
  
### <a name="address-book-policies"></a>Políticas do catálogo de endereços

O Exchange Online oferece suporte a políticas de catálogo de endereços. Políticas de catálogo de endereços (ABPs) permitem segmentar usuários em grupos específicos para fornecer visualizações personalizadas da GAL (lista de endereços global) da sua organização. Ao criar uma ABP, atribua uma GAL, um OAB (catálogo de endereços offline), uma lista de salas e uma ou mais listas de endereços para a política. Você pode atribuir o ABP aos usuários de caixa de correio, fornecendo acesso a uma GAL personalizada no Outlook e no Outlook na Web. Os administradores podem configurar as políticas do catálogo de endereços usando o Windows PowerShell remoto. Para saber mais sobre as Políticas de Catálogos de Endereços, confira [Catálogo de Endereços no Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=394203).
  
### <a name="address-lists"></a>Listas de endereços

O Exchange Online oferece suporte à personalização de listas de endereços e GALs. Uma GAL é um diretório para toda a organização de todos os usuários habilitados para email, grupos de distribuição e contatos externos. Os administradores podem ocultar usuários, grupos de distribuição e contatos da GAL usando a ferramenta de sincronização de diretório ou o Windows PowerShell remoto.
  
### <a name="hierarchical-address-books"></a>Catálogos de endereços hierárquicos

 Os catálogos de endereços hierárquicos permitem que os usuários finais pesquisem por destinatários no Exchange da sua empresa usando a hierarquia organizacional. Os administradores podem personalizar o catálogo de endereços por tempo de serviço e classificação, em vez de listagens alfabéticas. 
  
### <a name="distribution-groups-global"></a>Grupos de distribuição (global)

Um grupo de distribuição (ou lista de distribuição) é um conjunto de usuários, contatos e outros grupos de distribuição disponíveis para todos os usuários em uma empresa. Os usuários endereçam emails para um alias do grupo de distribuição, para enviar mensagens para todas as pessoas do grupo. Os grupos de distribuição são semelhantes aos grupos de distribuição pessoais criados por indivíduos no Outlook, somente suas listas de membros são globalmente disponíveis para a empresa. Os administradores criam grupos de distribuição no centro de administração do Exchange. Os grupos também podem ser sincronizados com o Exchange Online a partir do Active Directory local. Eles aparecem na GAL no Outlook. O Exchange Online suporta as capacidades avançadas do grupo de distribuição, incluindo as descritas abaixo:
  
- **Grupos restritos de distribuição** Por padrão, qualquer um pode mandar e-mails para qualquer grupo de distribuição. Os administradores podem alterar as permissões para permitir que apenas indivíduos específicos enviem emails para um determinado grupopor exemplo, para desencorajar o uso inadequado de listas grandes de distribuição. Os administradores podem também impedir que fontes externas enviem emails para grupos de distribuição, para ajudar a evitar spam. Para os grupos de distribuição sincronizados a partir do Active Directory local, usando a ferramenta de Sincronização de Diretório, os atributos para restrição são sincronizados com a nuvem automaticamente. Para saber mais, consulte [Gerenciar Grupos de Distribuição](https://technet.microsoft.com/library/mt577270%28v=exchg.160%29.aspx).
    
- **Grupos dinâmicos de distribuição** A lista de associação para um grupo dinâmico de distribuição (também conhecido como lista dinâmica de distribuição ou lista de distribuição baseada em consultas) é calculada sempre que uma mensagem é enviada ao grupo. Esse cálculo baseia-se nos filtros e nas condições definidas pelo administrador. Eles são gerenciados no Exchange Online pelo Windows PowerShell remoto. Para saber mais sobre grupos dinâmicos de distribuição, consulte [Gerenciar Grupos Dinâmicos de Distribuição](https://technet.microsoft.com/library/bb123722%28v=exchg.160%29.aspx).
    
    > [!IMPORTANT]
    > A ferramenta de Sincronização de Diretório do Office 365 ignora os grupos dinâmicos de distribuição no Active Directory local, e não sincroniza esses grupos com o Exchange Online. As organizações que usam a ferramenta de Sincronização de Diretório devem usar uma convenção de nomenclatura que evite conflitos entre grupos de distribuição comuns, que são gerenciados no local, e grupos dinâmicos de distribuição, que são gerenciados no Exchange Online. 
  
- **Grupos moderados de distribuição** Os administradores podem selecionar um moderador para regular o fluxo das mensagens enviadas a um grupo de distribuição. Com os grupos moderados de distribuição, qualquer pessoa pode enviar emails ao alias do grupo de distribuição, porém, antes que a mensagem seja entregue aos membros do grupo, um moderador deverá revisá-la e aprová-la. Para saber mais sobre moderação, consulte a seção Aprovação de Mensagens em [Gerenciar Grupos de Distribuição](https://technet.microsoft.com/library/mt577270%28v=exchg.160%29.aspx).
    
- **Grupos de distribuição de autosserviço** Os administradores podem dar aos usuários a capacidade de gerenciar sua própria associação ao grupo de distribuição em uma interface baseada na Web. Os usuários podem receber permissões para criar, excluir, integrar ou deixar grupos de distribuição. Essas capacidades são habilitadas por padrão para todos os usuários do Exchange Online. Os administradores podem desabilitá-las para que apenas o departamento de TI possa gerenciar os grupos de distribuição, caso seja desejado. Eles também podem criar políticas de nomenclatura para padronizar e gerenciar os nomes dos grupos de distribuição criados por seus usuários. Por exemplo, eles podem adicionar um prefixo ou sufixo ao nome do grupo de distribuição quando for criado, ou impedir que palavras específicas sejam usadas no nome do grupo. 
    
    > [!IMPORTANT]
    > As capacidades de autoatendimento não estão disponíveis para os grupos de distribuição sincronizados a partir do Active Directory local para o Exchange Online. As organizações que usam a Sincronização de Diretório devem usar uma convenção de nomenclatura que evite conflitos entre grupos de distribuição que são gerenciados no local, e grupos de distribuição que são gerenciados na nuvem. 
  
### <a name="external-contacts-global"></a>Contatos externos (global)

Um contato externo é um registro com informações sobre uma pessoa que trabalha fora de uma organização específica. Os contatos externos são semelhantes aos contatos pessoais criados por indivíduos no Outlook, a única diferença é que são globalmente disponíveis para a empresa. Os administradores criam contatos externos usando o centro de administração do Exchange ou o Windows PowerShell remoto. Esses contatos também podem ser sincronizados com o Exchange Online a partir do Active Directory local. Eles aparecem na GAL no Outlook.
  
Para saber mais sobre contatos externos, consulte [Criar um relacionamento de organização no Exchange Online](https://technet.microsoft.com/library/jj916671%28v=exchg.150%29.aspx).
  
## <a name="calendar-and-scheduling"></a>Calendário e agendamento

### <a name="resource-mailboxes"></a>Caixas de correio de recurso

A caixa de correio de recursos (como para salas de conferência e equipamentos físicos) representa as salas de reuniões de uma empresa ou outras facilidades ou recursos. Os usuários podem reservar salas ou recursos adicionando o alias de email do recurso às solicitações de reunião no Outlook ou no Outlook na Web. As salas de conferência e os recursos aparecem na GAL no Outlook e no Outlook na Web.
  
Os administradores criam caixas de correio de recurso usando o centro de administração do Exchange ou o Windows PowerShell remoto. As caixas de correio também podem ser sincronizadas com o Exchange Online a partir do Active Directory local.
  
Para obter mais informações sobre caixas de correio de recursos, consulte:
  
- [Criar e gerenciar caixas de correio de sala](https://go.microsoft.com/fwlink/?LinkId=717533&amp;clcid=0x409)
    
- [Gerenciar caixas de correio de equipamento](https://go.microsoft.com/fwlink/?LinkId=717534)
    
### <a name="conference-room-management"></a>Gerenciamento da sala de conferência

O Exchange Online inclui o RBA (Atendente de Reserva de Recursos), que automatiza o agendamento de salas de conferência e outros recursos. Uma caixa de correio de recursos configurada com RBA aceita, rejeita ou reconhece as solicitações de reuniões de um organizador de reuniões baseado na disponibilidade do calendário do recurso. 
  
Os administradores podem personalizar as respostas de sala de conferência automatizadas e configurar as políticas de reserva no Outlook na Web. Essas políticas incluem quem pode agendar o recurso, quando o recurso pode ser agendado, quais informações de reuniões são visíveis no calendário de recursos e a porcentagem de conflitos de agendamento permitida. Os administradores podem desabilitar o Atendente de Reserva de Recursos e determinar usuários específicos para gerenciar manualmente as solicitações de reuniões para salas de conferência.
  
Os administradores devem definir e gerenciar as configurações RBA pelo Windows PowerShell remoto.
  
### <a name="out-of-office-replies"></a>Respostas de Ausência Temporária

As mensagens de ausência temporária são respostas automáticas para as mensagens de entrada que o Exchange Online envia em nome de um usuário. Os usuários podem agendar mensagens de ausência temporária com antecedência, com datas de início e de término específicas, e podem configurar mensagens de ausência temporária separadas para destinatários internos e externos. Eles também podem definir mensagens de ausência temporária a partir de dispositivos móveis que suportam esse recurso do Exchange ActiveSync. Lixo eletrônico e reconhecimento da lista de email no Exchange Online evita que os usuários enviem mensagens de ausência temporária externas para listas de email estendidas e remetentes de spam potenciais. Os administradores também podem evitar que os usuários enviem mensagens de ausência temporária para usuários externos, usando o Windows PowerShell remoto.
  
### <a name="calendar-sharing"></a>Compartilhamento de calendário

Os usuários podem compartilhar seu calendário pessoal de duas maneiras:
  
- **Compartilhamento de agendas federado** Federação se refere à infraestrutura confiável subjacente que suporta o compartilhamento federado, um método fácil para os usuários do Exchange compartilharem dados da agenda de disponibilidade e informações de contato com destinatários de outras organizações federadas externas. Isto inclui organizações do Exchange Online ou organizações que executam o Exchange Server 2010 ou o Exchange Server 2013 local. Os administradores do Exchange Online não precisam configurar uma relação de confiança com o Microsoft Federation Gateway, porque essa relação de confiança é pré-configurada para todos os clientes do Exchange Online, quando o serviço do locatário do Office 365 é criado. Uma política de compartilhamento padrão permite que os usuários enviem convites de compartilhamento de calendário do Outlook na Web ou do Outlook 2010. Os administradores usam o Windows PowerShell remoto para desabilitar essa política ou para configurar o nível de disponibilidade dos dados de calendário que os usuários podem compartilhar. Os administradores também podem criar um relacionamento de organização para organização com outra organização federada, que permite que o nível desejado de informações de disponibilidade para cada usuário seja visível na organização, sem que os usuários individuais tenham que fazer um convite compartilhado. Dentro do escopo das Políticas de Compartilhamento definidas pelo administrador e/ou dos relacionamentos de organização para organização, os usuários podem limitar individualmente ainda mais o detalhe de seu compartilhamento. 
    
- **Compartilhamento de agendas da Internet** O Exchange Online permite que os usuários publiquem suas agendas usando o formato iCal para o acesso anônimo por qualquer um dentro ou fora da organização. Os destinatários podem estar usando o Exchange, outra plataforma ou simplesmente um navegador da web. Os usuários do Exchange Online também podem se inscrever em calendários que outras pessoas publicaram em locais da Internet por meio do iCal. Esse compartilhamento de calendário pessoal é diferente do compartilhamento de calendário federado, que é configurado por um administrador e fornece compartilhamento de disponibilidade de organização para organização. Nenhum usuário pode publicar dados de calendário no formato iCal até que o administrador tenha definido e aplicado uma política de compartilhamento que o permita. Os administradores podem desabilitar a publicação e as assinaturas iCal para os usuários de uma organização, usando o Windows PowerShell remoto.
    
Para saber mais sobre o compartilhamento federado, confira [Compartilhando no Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271774).
  
### <a name="outlook-2010-room-finder"></a>Localizador de Sala do Outlook 2010

O Exchange Online suporta o recurso do Localizador de Salas do Outlook 2010, que organiza as salas em listas (por exemplo, uma lista chamada "Salas do prédio 5") para facilitar a localização de uma sala próxima, ao agendar uma reunião. Para aparecer na lista de salas, um grupo de distribuição deve ser especialmente marcado, usando dois métodos: 
  
- Uma nova lista de salas pode ser criada, usando o Windows PowerShell remoto. 
    
- Qualquer grupo de distribuição que contenha apenas salas pode ser convertido em uma lista de salas pelo Windows PowerShell remoto.
    
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos nos planos do Office 365, nas opções autônomas e nas soluções locais, consulte [Descrição do serviço do Exchange Online](exchange-online-service-description.md).
  