---
title: Destinatários
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-recipients
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: da22b03a-c981-49c6-9928-4312c2c5e2ee
description: Este tópico descreve os recursos relacionados ao destinatário que fazem parte do Microsoft Exchange Online. Isso inclui e-mail, contatos, grupos de distribuição, agenda e as capacidades de agendamento.
ms.openlocfilehash: a2d1f37bf4f86399522573d18177f6c397fd761c
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132635"
---
# <a name="recipients"></a>Destinatários

This topic describes recipient-related features included with Microsoft Exchange Online. This includes email, contacts, distribution groups, and calendar and scheduling capabilities.
  
## <a name="email"></a>E-mail

Every Microsoft Exchange Online subscriber receives a mailbox, and specialty mailboxes are available for scheduling facilities resources (such as conference rooms) and for multiuser access to shared email addresses. Maximum storage limits apply to most mailboxes, and administrators can control allowable mailbox sizes. Automated notifications and restrictions can alert users when their mailboxes are nearing, or at, capacity. Exchange Online also has several types of message limitations—message size, message rate, and recipient list limits. Details of all these features and limits are provided below.
  
> [!NOTE]
> Não há mais suporte para Endereços catch-all no Exchange Online. Devido à filtragem de destinatários no local para proteção contra possíveis mensagens de spam, os endereços de email que não existem na sua organização serão rejeitados. 
  
### <a name="mailbox-types-storage-limits-and-capacity-alerts"></a>Tipos de caixa de correio, limites de armazenamento e alertas de capacidade

The amount of mailbox storage available to a user and the default mailbox size are determined by the mailbox type and the user's subscription license. Administrators can reduce maximum mailbox sizes per user or globally. Exchange Online also provides notifications when a user's mailbox is nearing, or at, capacity.
  
Para obter mais informações, consulte as seções "limites de armazenamento de caixa de correio" e "alertas de capacidade" no tópico [limites do Exchange Online](exchange-online-limits.md).
  
### <a name="mailtips"></a>MailTips

MailTips are automated, informative messages that appear above the To: line while users are composing or addressing a message. They are designed to help prevent accidental delivery, policy violations, or unnecessary non-delivery reports (NDRs). For example, MailTips can generate an alert if senders try to send messages to overly large groups, to groups that contain external recipients, or to a distribution group that is moderated or restricted. For more information, see [MailTips](https://go.microsoft.com/fwlink/p/?LinkId=401472).
  
### <a name="delegate-access"></a>Acesso de representante

O Exchange Online dá suporte ao acesso delegadoa habilidade para os usuários permitirem outros usuários a gerenciarem seus emails e calendários. O acesso delegado é normalmente usado entre um gerente e um assistente, no qual o assistente processa as mensagens de email de entrada do gerente e coordena a agenda do gerente. O acesso de representante pode ser habilitado por usuários do Exchange Online no Outlook ou no Outlook na Web ou por administradores no centro de administração do Exchange. 
  
Os representantes podem ter dois tipos de acesso:
  
- **Permissões Enviar em Nome de** O representante pode compor mensagens de email e inserir o nome de outra pessoa no campo De, onde será exibido "[nome do representante] em nome de [nome da pessoa]." 
    
- **Send As permissions** The delegate can send messages from the other person's mailbox as if the delegate were the mailbox owner. This scenario is common where there is a shared mailbox and several employees send email messages from that shared mailbox instead of from their Exchange Online accounts. 
    
Para saber mais sobre como delegar acesso, consulte [Gerenciar Permissões de Destinatários](https://technet.microsoft.com/library/jj919240%28v=exchg.160%29.aspx).
  
### <a name="inbox-rules"></a>Regras da Caixa de Entrada

O Exchange Online permite que os usuários criem regras de caixa de entrada que desempenhem ações específicas, baseadas em critérios e de forma automática, nas mensagens, conforme elas chegam. Por exemplo, eles podem criar uma regra para mover automaticamente todos os emails para uma pasta específica, caso o email tenha sido enviado para um determinado grupo de distribuição. Os usuários gerenciam as regras de caixa de entrada do Outlook ou do Outlook na Web. Os administradores podem bloquear determinados tipos de regras da caixa de entrada, desabilitando o encaminhamento e/ou as respostas automáticas do servidor. Por exemplo, ao desabilitar o encaminhamento de emails do servidor, é possível evitar que os usuários encaminhem emails automaticamente para contas pessoais. Semelhantemente, ao desabilitar as respostas automáticas do servidor, é possível evitar que partes externas usem essas respostas para identificar endereços de email válidos. Essas alterações são feitas por meio do Windows PowerShell remoto.
  
### <a name="clutter"></a>Email secundário

Clutter is designed to help you focus on the most important messages in your inbox. It uses machine learning to de-clutter your inbox by moving lower priority messages out of your way and into a new Clutter folder. Clutter respects your existing email rules, so if you have created rules to organize your email those rules continue to be applied and Clutter won't act on those messages. Clutter is disabled by default for your inbox. To learn more, see [De-clutter your inbox in Office 365](https://www.microsoft.com/en-us/microsoft-365/blog/2014/11/11/de-clutter-inbox-office-365/).
  
### <a name="connected-accounts"></a>Contas conectadas

O recurso de contas conectadas permite que os usuários do Exchange Online conectem contas de email externas (como contas pessoais) às suas contas de email internas no Exchange Online e, em seguida, use o Outlook na Web para interagir com todas as suas mensagens em um só lugar. Contas conectadas são sincronizadas automaticamente após entrar no Outlook na Web; os usuários também podem sincronizar manualmente as contas do Outlook na Web. Os administradores podem habilitar e desabilitar esse recurso para usuários específicos ou todos os usuários por meio do [centro de administração do Exchange](https://go.microsoft.com/fwlink/?LinkID=785297&amp;clcid=0x409).
  
### <a name="inactive-mailboxes"></a>Caixas de correio inativas

Exchange Online provides the capability to preserve the contents of deleted mailboxes indefinitely. This feature is called inactive mailboxes. A mailbox becomes inactive when an In-Place Hold or a Litigation Hold is placed on the mailbox before it's deleted. This results in the contents of the mailbox being preserved indefinitely. Administrators, compliance officers, or record managers can use the In-Place eDiscovery feature in Exchange Online to access the contents of an inactive mailbox.
  
Habilitar uma caixa de correio inativa exige que a caixa de correio seja atribuída com uma licença do Exchange Online (plano 2) ou tenha uma assinatura do Exchange Online Archiving para que uma Retenção local ou uma Retenção de litígio possa ser aplicada na caixa de correio antes de ser excluída.
  
> [!IMPORTANT]
> If a hold isn't placed on a mailbox before it's deleted, the contents of the mailbox will not be preserved or discoverable. The mailbox can be recovered within 30 days of deletion, but the mailbox and its contents will be permanently deleted after 30 days if it isn't recovered. 
  
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

 Hierarchical address books allow end users to browse for recipients in their Exchange organization using an organizational hierarchy. Administrators can customize the address book by seniority and rank rather than alphabetical listings. 
  
### <a name="distribution-groups-global"></a>Grupos de distribuição (global)

Um grupo de distribuição (ou lista de distribuição) é um conjunto de usuários, contatos e outros grupos de distribuição disponíveis para todos os usuários em uma empresa. Os usuários endereçam emails para um alias do grupo de distribuição, para enviar mensagens para todas as pessoas do grupo. Os grupos de distribuição são semelhantes aos grupos de distribuição pessoais criados por indivíduos no Outlook, somente suas listas de membros são globalmente disponíveis para a empresa. Os administradores criam grupos de distribuição no centro de administração do Exchange. Os grupos também podem ser sincronizados com o Exchange Online a partir do Active Directory local. Eles aparecem na GAL no Outlook. O Exchange Online suporta as capacidades avançadas do grupo de distribuição, incluindo as descritas abaixo:
  
- **Restricted distribution groups** By default, anyone can send emails to any distribution group. Administrators can change permissions to allow only specific individuals to send emails to a particular group—for example, to discourage inappropriate use of large distribution lists. Administrators can also block external sources from sending email to distribution groups to help prevent spam. For distribution groups that are synchronized from on-premises Active Directory using the Directory Synchronization tool, the attributes for restriction are synchronized to the cloud automatically. For more information, see [Manage Distribution Groups](https://technet.microsoft.com/library/mt577270%28v=exchg.160%29.aspx).
    
- **Dynamic distribution groups** The membership list for a dynamic distribution group (also known as a dynamic distribution list, or query-based distribution list) is calculated every time a message is sent to the group. This calculation is based on filters and conditions that the administrator defines. They are managed in Exchange Online through remote Windows PowerShell. For more information about dynamic distribution groups, see [Manage Dynamic Distribution Groups](https://technet.microsoft.com/library/bb123722%28v=exchg.160%29.aspx).
    
    > [!IMPORTANT]
    > The Office 365 Directory Synchronization tool ignores dynamic distribution groups in on-premises Active Directory, and does not synchronize these to Exchange Online. Organizations that use the Directory Synchronization tool should use a naming convention that avoids conflicts between the regular distribution groups that are managed on-premises and the dynamic distribution groups that are managed in Exchange Online. 
  
- **Moderated distribution groups** Administrators can select a moderator to regulate the flow of messages to a distribution group. With moderated distribution groups, anyone can email the distribution group alias, but before the message is delivered to the members of the group, a moderator must review and approve it. For more information about moderation, see the Message Approval section in [Manage Distribution Groups](https://technet.microsoft.com/library/mt577270%28v=exchg.160%29.aspx).
    
- **Self-Service distribution groups** Administrators can give users the ability to manage their own distribution group membership from a web-based interface. Users can be given permissions to create, delete, join, or leave distribution groups. These capabilities are enabled by default for all Exchange Online users. Administrators can disable them so that only the IT department can manage distribution groups, if desired. They can also create naming policies to standardize and manage the names of distribution groups that their users create. For example, they can add a specific prefix or suffix to the distribution group name when it is created, or block specific words from being used in the group's name. 
    
    > [!IMPORTANT]
    > Self-service capabilities are not available for distribution groups that are synchronized from on-premises Active Directory to Exchange Online. Organizations that use Directory Synchronization should use a naming convention that avoids conflicts between distribution groups that are managed on-premises and distribution groups that are managed in the cloud. 
  
### <a name="external-contacts-global"></a>Contatos externos (global)

Um contato externo é um registro com informações sobre uma pessoa que trabalha fora de uma organização específica. Os contatos externos são semelhantes aos contatos pessoais criados por indivíduos no Outlook, a única diferença é que são globalmente disponíveis para a empresa. Os administradores criam contatos externos usando o centro de administração do Exchange ou o Windows PowerShell remoto. Esses contatos também podem ser sincronizados com o Exchange Online a partir do Active Directory local. Eles aparecem na GAL no Outlook.
  
Para saber mais sobre contatos externos, consulte [Criar um relacionamento de organização no Exchange Online](https://technet.microsoft.com/library/jj916671%28v=exchg.150%29.aspx).
  
## <a name="calendar-and-scheduling"></a>Calendário e agendamento

### <a name="resource-mailboxes"></a>Caixas de correio de recurso

A caixa de correio de recursos (como para salas de conferência e equipamentos físicos) representa as salas de reuniões de uma empresa ou outras facilidades ou recursos. Os usuários podem reservar salas ou recursos adicionando o alias de email do recurso às solicitações de reunião no Outlook ou no Outlook na Web. As salas de conferência e os recursos aparecem na GAL no Outlook e no Outlook na Web.
  
Administrators create resource mailboxes using the Exchange admin center or remote Windows PowerShell. The mailboxes can also be synchronized with Exchange Online from on-premises Active Directory.
  
Para obter mais informações sobre caixas de correio de recursos, consulte:
  
- [Criar e gerenciar caixas de correio de sala](https://go.microsoft.com/fwlink/?LinkId=717533&amp;clcid=0x409)
    
- [Gerenciar caixas de correio de equipamento](https://go.microsoft.com/fwlink/?LinkId=717534)
    
### <a name="conference-room-management"></a>Gerenciamento da sala de conferência

Exchange Online includes the Resource Booking Attendant (RBA), which automates scheduling of conference rooms and other resources. A resource mailbox that is RBA-configured accepts, declines, or acknowledges meeting requests from a meeting organizer based on the resource's calendar availability. 
  
Os administradores podem personalizar as respostas de sala de conferência automatizadas e configurar as políticas de reserva no Outlook na Web. Essas políticas incluem quem pode agendar o recurso, quando o recurso pode ser agendado, quais informações de reuniões são visíveis no calendário de recursos e a porcentagem de conflitos de agendamento permitida. Os administradores podem desabilitar o Atendente de Reserva de Recursos e determinar usuários específicos para gerenciar manualmente as solicitações de reuniões para salas de conferência.
  
Os administradores devem definir e gerenciar as configurações RBA pelo Windows PowerShell remoto.
  
### <a name="out-of-office-replies"></a>Respostas de Ausência Temporária

Out-of-office messages are automatic replies to incoming messages that Exchange Online sends on behalf of a user. Users can schedule out-of-office messages in advance, with specific start and end times, and can configure separate out-of-office messages for internal and external recipients. They can also set out-of-office messages from mobile devices that support this Exchange ActiveSync feature. Junk-email and mailing-list awareness within Exchange Online prevents users from sending external out-of-office messages to extended mailing lists and potential spammers. Administrators can also prevent users from sending out-of-office messages to external users using remote Windows PowerShell.
  
### <a name="calendar-sharing"></a>Compartilhamento de calendário

Os usuários podem compartilhar seu calendário pessoal de duas maneiras:
  
- **Compartilhamento de agendas federado** Federação se refere à infraestrutura confiável subjacente que suporta o compartilhamento federado, um método fácil para os usuários do Exchange compartilharem dados da agenda de disponibilidade e informações de contato com destinatários de outras organizações federadas externas. Isto inclui organizações do Exchange Online ou organizações que executam o Exchange Server 2010 ou o Exchange Server 2013 local. Os administradores do Exchange Online não precisam configurar uma relação de confiança com o Microsoft Federation Gateway porque essa confiança é pré-configurada para todos os clientes do Exchange Online quando o serviço Microsoft é criado. Uma política de compartilhamento padrão permite que os usuários enviem convites de compartilhamento de calendário do Outlook na Web ou do Outlook 2010. Os administradores usam o Windows PowerShell remoto para desabilitar essa política ou para configurar o nível de disponibilidade dos dados de calendário que os usuários podem compartilhar. Os administradores também podem criar um relacionamento de organização para organização com outra organização federada, que permite que o nível desejado de informações de disponibilidade para cada usuário seja visível na organização, sem que os usuários individuais tenham que fazer um convite compartilhado. Dentro do escopo das Políticas de Compartilhamento definidas pelo administrador e/ou dos relacionamentos de organização para organização, os usuários podem limitar individualmente ainda mais o detalhe de seu compartilhamento. 
    
- **Compartilhamento de agendas da Internet** O Exchange Online permite que os usuários publiquem suas agendas usando o formato iCal para o acesso anônimo por qualquer um dentro ou fora da organização. Os destinatários podem estar usando o Exchange, outra plataforma ou simplesmente um navegador da web. Os usuários do Exchange Online também podem se inscrever em calendários que outras pessoas publicaram em locais da Internet por meio do iCal. Esse compartilhamento de calendário pessoal é diferente do compartilhamento de calendário federado, que é configurado por um administrador e fornece compartilhamento de disponibilidade de organização para organização. Nenhum usuário pode publicar dados de calendário no formato iCal até que o administrador tenha definido e aplicado uma política de compartilhamento que o permita. Os administradores podem desabilitar a publicação e as assinaturas iCal para os usuários de uma organização, usando o Windows PowerShell remoto.
    
Para saber mais sobre o compartilhamento federado, confira [Compartilhando no Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271774).
  
### <a name="outlook-2010-room-finder"></a>Localizador de Sala do Outlook 2010

Exchange Online supports the Room Finder feature of Outlook 2010, which arranges rooms into lists (for example, a list called "Building 5 rooms") to make it easier to find a nearby room when scheduling a meeting. To appear in the room list, a distribution group must be specially marked using one of two methods: 
  
- Uma nova lista de salas pode ser criada, usando o Windows PowerShell remoto. 
    
- Qualquer grupo de distribuição que contenha apenas salas pode ser convertido em uma lista de salas pelo Windows PowerShell remoto.
    
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos nos planos, nas opções autônomas e nas soluções locais, consulte [Descrição do serviço do Exchange Online](exchange-online-service-description.md).
  