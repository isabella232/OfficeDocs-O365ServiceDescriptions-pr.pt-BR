---
title: Recursos de conformidade e segurança no arquivamento do Exchange Online
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- compliance-and-security-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7482322a-39fe-4a99-b29c-63cb1bc3cf1f
ms.openlocfilehash: b03c74e0c760cf22c12e6973a544553d119471fe
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132735"
---
# <a name="compliance-and-security-features-in-exchange-online-archiving"></a>Recursos de conformidade e segurança no arquivamento do Exchange Online

## <a name="compliance-features-in-exchange-online-archiving"></a>Recursos de conformidade no Exchange Online

As seções a seguir descrevem os recursos de conformidade do Microsoft Arquivamento do Exchange Online.
  
### <a name="retention-policies"></a>Políticas de retenção

O Arquivamento do Exchange Online oferece políticas de retenção para ajudar as organizações a reduzir as obrigações associadas ao email e a outros meios de comunicação. Com essas políticas, os administradores podem aplicar configurações de retenção a pastas específicas nas caixas de entrada dos usuários. Os administradores também podem fornecer aos usuários um menu de políticas de retenção e permitir que eles apliquem as políticas a itens específicos, conversas ou pastas usando o Outlook 2010 ou posterior ou o Outlook na Web. No Arquivamento do Exchange Online, os administradores gerenciam políticas de retenção da infraestrutura no local.
  
Exchange Online Archiving offers two types of policies: archive and delete. Both types can be applied to the same item or folder. For example, a user can tag an email message so that it is automatically moved to the personal archive in a specified number of days and deleted after another span of days.
  
Com o Outlook 2010 e posterior e o Outlook na Web, os usuários podem aplicar políticas de retenção a pastas, conversas ou mensagens individuais e também podem exibir as políticas de retenção aplicadas e datas de exclusão esperadas nas mensagens. Os usuários de outros clientes de email podem ter emails excluídos ou arquivados com base nas políticas de retenção do lado do servidor provisionadas pelo administrador, mas não têm o mesmo nível de visibilidade e controle.
  
The retention policy capabilities offered in Exchange Online Archiving are the same as those offered in Exchange Server 2010 Service Pack 2 (SP2) and later. Administrators can manage retention policies from on-premises Exchange Server 2010 and later environments. Managed Folders, an older approach to messaging records management that was introduced in Exchange 2007, are not available in and not compatible with Exchange Online Archiving. For more details, see [Retention Tags and Retention Policies](https://go.microsoft.com/fwlink/p/?LinkID=314153).
  
### <a name="in-place-hold-and-litigation-hold"></a>Bloqueio In-loco e Retenção de Litígio

When a reasonable expectation of litigation exists, organizations are required to preserve electronically stored information (ESI), including email that's relevant to the case. This expectation can occur before the specifics of the case are known, and preservation is often broad. Organizations may preserve all email related to a specific topic, or all email for certain individuals.
  
No Exchange Online, é possível usar a Retenção local ou a Retenção de litígio para cumprir os seguintes objetivos:
  
- Permitir que os usuários sejam retidos e preservar itens de caixa de correio imutavelmente
    
- Preservar itens de caixa de correio excluídos por usuários ou por processos de exclusão automática, como o MRM
    
- Proteger os itens da caixa de correio contra violações, alterações feitas por um usuário ou processos automáticos salvando uma cópia do item original.
    
- Preservar itens indefinidamente ou por um período específico
    
- Manter as retenções transparentes para o usuário não tendo que suspender o MRM
    
- Usar o Descoberta Eletrônica local para pesquisar os itens da caixa de correio, incluindo os itens colocados em espera
    
Além disso, você pode usar a Retenção local para:
  
- Pesquisar e manter os itens que correspondem aos critérios especificados
    
- Colocar um usuário em várias Retenções locais para casos diferentes ou investigações
    
> [!NOTE]
> Ao colocar uma caixa de correio em Bloqueio In-loco ou Retenção por Litígio, a retenção é aplicada à caixa de correio primária e a caixa de correio de arquivo morto. 
  
Confira mais informações em [Bloqueio In-loco e Retenção Local](https://go.microsoft.com/fwlink/p/?LinkId=271746).
  
> [!NOTE]
> A cota padrão para a Pasta Itens Recuperáveis é de 100 GB para os usuários do Arquivamento do Exchange Online. 
  
### <a name="in-place-ediscovery"></a>Descoberta Eletrônica In-loco

Exchange Online Archiving supports In-Place eDiscovery for searching the contents of mailboxes in an organization. Using the Exchange admin center or remote Windows PowerShell from an on-premises Exchange 2013 server, administrators or authorized Discovery managers can search a variety of mailbox items - including email messages, attachments, calendar appointments, tasks, and contacts. In-Place eDiscovery can search simultaneously across primary mailboxes and archives. Rich filtering capabilities include sender, receiver, message types, sent date, received date, carbon copy, and blind carbon copy, along with Keyword Query Language (KQL) syntax. For more details, see [In-Place eDiscovery](https://go.microsoft.com/fwlink/p/?LinkId=314169).
  
The Exchange admin center and remote Windows PowerShell can be used to search up to 5,000 mailboxes at a time in an In-Place eDiscovery search. For details about using remote Windows PowerShell to run In-Place eDiscovery searches, see [New-MailboxSearch](https://go.microsoft.com/fwlink/p/?LinkId=314170). 
  
> [!NOTE]
> In remote Windows PowerShell, the  `Search-Mailbox` cmdlet can be used to search more than 5,000 mailboxes. For details about searching large numbers of mailboxes using remote Windows PowerShell, see [Search-Mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314171). 
  
Results of an In-Place eDiscovery search can be previewed in the Exchange admin center, exported to a .pst file, or copied to a special type of mailbox, called a discovery mailbox. Administrators or compliance officers can connect to the discovery mailbox to review messages. For details, see [Create an In-Place eDiscovery Search](https://go.microsoft.com/fwlink/p/?LinkId=314172).
  
> [!NOTE]
> When copying search results for an In-Place eDiscovery search performed across on-premises and cloud-based mailboxes or archives, you must select an on-premises discovery mailbox. Messages from the on-premises primary mailbox and the cloud-based archive are copied to the on-premises discovery mailbox. 
  
Administrators can also search for and delete inappropriate email messages sent to multiple mailboxes across their organizations. For example, if confidential salary information was accidentally sent to all employees, an administrator can delete the email from the users' mailboxes. This type of search is not available in the Exchange admin center. It must be performed using Remote PowerShell. For details on how to delete messages from users' mailboxes, see [Search and Delete Messages](https://go.microsoft.com/fwlink/p/?LinkId=314173).
  
## <a name="security-features-in-exchange-online-archiving"></a>Recursos de segurança no Arquivamento do Exchange Online

As seções a seguir descrevem os recursos de segurança da Microsoft Arquivamento do Exchange Online.
  
### <a name="encryption-between-on-premises-servers-and-exchange-online-archiving"></a>Criptografia entre servidores no local e o Arquivamento do Exchange Online

TLS é usado para criptografar a conexão entre servidores de email para ajudar a evitar a falsificação e fornecer confidencialidade para mensagens em trânsito. O TLS também é usado para proteger o tráfego do servidor de emails no local para o arquivamento do Exchange Online.
  
### <a name="encrypting-between-clients-and-exchange-online-archiving"></a>Criptografia entre clientes e o Arquivamento do Exchange Online

Conexões de cliente a Arquivamento do Exchange Online use os seguintes métodos de criptografia para aumentar a segurança:
  
- O SSL é usado para proteger o Outlook, o Outlook na Web e o tráfego de serviços Web do Exchange, usando a porta TCP 443.
    
- Conexões de cliente com servidores locais não são alteradas com a introdução do Arquivamento do Exchange Online.
    
### <a name="encryption-smime-and-pgp"></a>Criptografia: S/MIME e PGP

Exchange Online Archiving will store Secure/Multipurpose Internet Mail Extensions (S/MIME) messages. However, Exchange Online Archiving does not host S/MIME functions or host the public keys, nor does it provide key repository, key management, or key directory services because all of these services attach to the on-premises Exchange infrastructure.
  
Semelhantemente, Arquivamento do Exchange Online armazena mensagens que são criptografadas usando soluções de terceiros do lado do cliente como o PGP.
  
### <a name="information-rights-management"></a>Gerenciamento de Direitos de Informação

Exchange Online Archiving does not provide hosted Information Rights Management (IRM) services, but administrators can use on-premises Active Directory Rights Management Services (AD RMS). If an AD RMS server is deployed, Outlook can communicate directly with that server, enabling users to compose and read IRM-protected messages. If interoperability between the AD RMS server and the on-premises Exchange environment is configured, users will be able to compose and read IRM-protected messages.
  
#### <a name="support-for-irm-in-outlook-on-the-web"></a>Suporte para IRM no Outlook na Web

Os usuários podem ler e criar mensagens protegidas por IRM nativamente no Outlook na Web, assim como podem no Outlook. As mensagens protegidas por IRM no Outlook na Web podem ser acessadas por meio do Internet Explorer, Firefox, Safari e Chrome (sem nenhum plug-in necessário). Os recursos de visualização incluem pesquisa de texto completo, exibição de conversa e o painel de visualização. Interoperabilidade entre o servidor do Active Directory Rights Management Services e o ambiente do Exchange no local deve ser configurada para habilitar isso.
  
#### <a name="irm-search"></a>Pesquisa IRM

As mensagens protegidas por IRM são indexadas e pesquisáveis, incluindo cabeçalhos, assunto, corpo e anexos. Os usuários podem pesquisar itens protegidos por IRM no Outlook e no Outlook na Web, e os administradores podem pesquisar itens protegidos por IRM usando a descoberta eletrônica in-loco ou o cmdlet **Search-Mailbox** .
  
### <a name="auditing"></a>Auditoria

Arquivamento do Exchange Online fornece dois tipos de recursos de auditoria internos:
  
- **Registro de auditoria do administrador**. Permite aos clientes rastrearem mudanças realizadas pelos seus administradores no ambiente do Arquivamento do Exchange Online, incluindo mudanças nas funções do RBAC ou políticas e configurações do Exchange. 
    
- **Log de auditoria de caixa de correio** Auditoria de caixa de correio log permite que os clientes controlar o acesso a caixas de correio por usuários que não seja o proprietário de caixa de correio. 
    
Several predefined audit reports are available in the Exchange admin center, including Administrator Role Changes, Litigation Hold, and Non-Owner Mailbox Access. Administrators can filter reports by date and role, and they can export all audit events for specified mailboxes in XML format for long-term retention or custom reporting.
  
Administrator audit logging is on by default, and mailbox audit logging is off by default. Administrators can use remote Windows PowerShell to enable mailbox audit logging for some or all mailboxes in their organization. For more information, see [Auditing Reports](https://go.microsoft.com/fwlink/p/?LinkId=314175).
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos nos planos, nas opções autônomas e nas soluções locais, consulte [Descrição do serviço de arquivamento do Exchange Online](exchange-online-archiving-service-description.md).
  

