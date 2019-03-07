---
title: Conformidade e segurança recursos de Arquivamento do Exchange Online
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- compliance-and-security-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7482322a-39fe-4a99-b29c-63cb1bc3cf1f
ms.openlocfilehash: 6da22293e465f83a69181aec78c47866154a6b79
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/07/2019
ms.locfileid: "30467788"
---
# <a name="compliance-and-security-features-in-exchange-online-archiving"></a>Conformidade e segurança recursos de Arquivamento do Exchange Online

## <a name="compliance-features-in-exchange-online-archiving"></a>Recursos de conformidade no Exchange Online

As seções a seguir descrevem os recursos de conformidade do Microsoft Arquivamento do Exchange Online.
  
### <a name="retention-policies"></a>Diretivas de retenção
<a name="BKMK_Retentionpolicies"> </a>

O Arquivamento do Exchange Online oferece políticas de retenção para ajudar as organizações a reduzir as obrigações associadas ao email e a outros meios de comunicação. Com essas políticas, os administradores podem aplicar configurações de retenção a pastas específicas nas caixas de entrada dos usuários. Os administradores podem também dar aos usuários um menu de políticas de retenção e permitir que eles apliquem as políticas a itens, conversas ou pastas específicos usando o Outlook 2010 ou posterior ou o Outlook Web App. No Arquivamento do Exchange Online, os administradores gerenciam políticas de retenção da infraestrutura no local.
  
O Arquivamento do Exchange Online oferece dois tipos de condições: arquivar e excluir. Ambos os tipos podem ser combinados no mesmo item ou pasta. Por exemplo, um usuário pode marcar um email para ser movido automaticamente para o arquivo morto pessoal em um número específico de dias e excluído após outro intervalo de dias.
  
Com o Outlook 2010 e o Outlook Web App, os usuários têm a flexibilidade de aplicar políticas de retenção a pastas, conversas ou mensagens individuais e também podem exibir as políticas de retenção e as datas de exclusão esperadas das mensagens. Os usuários de outros clientes de email podem ter emails excluídos ou arquivados com base nas políticas de retenção do lado do servidor provisionadas pelo administrador, mas não têm o mesmo nível de visibilidade e controle.
  
Os recursos de política de retenção oferecidos no Arquivamento do Exchange Online são iguais aos oferecidos no Exchange Server 2010 Service Pack 2 (SP2) e posterior. Os administradores podem gerenciar políticas de retenção de local Exchange Server 2010 e em ambientes posteriores. As pastas gerenciadas, uma abordagem mais antiga do gerenciamento de registros de mensagem que foi introduzida no Exchange 2007, não estão disponíveis no Exchange Online. Confira mais informações em [Marcas de retenção e políticas de retenção](https://go.microsoft.com/fwlink/p/?LinkID=314153).
  
### <a name="in-place-hold-and-litigation-hold"></a>Bloqueio In-loco e Retenção de Litígio
<a name="BKMK_In_placehold"> </a>

Quando existe uma expectativa razoável de litígio, as organizações são solicitadas a preservar informações armazenadas eletronicamente (ESI), incluindo emails, pertinentes ao caso. Essa expectativa pode acontecer antes que os detalhes do caso sejam conhecidos, e a preservação geralmente é total. As organizações podem preservar todos os emails relacionados a um tópico específico ou todos os emails de determinados indivíduos.
  
> [!NOTE]
> O bloqueio in-loco e a retenção de litígio atualmente não se aplicam a emails enviados usando clientes POP ou IMAP ou por aplicativos personalizados que usam o protocolo SMTP. 
  
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
<a name="BKMK_In_placehold"> </a>

Arquivamento do Exchange Online eDiscovery suporta no local para pesquisar o conteúdo de caixas de correio em uma organização. Usando o centro de administração do Exchange ou remota do Windows PowerShell de um local Exchange 2013 servidor, os administradores ou gerentes de descoberta autorizados podem pesquisar uma variedade de itens de caixa de correio - incluindo as mensagens de e-mail, anexos, compromissos do calendário, tarefas e contatos. A Descoberta Eletrônica In-loco pode pesquisar simultaneamente em caixas de correio principais e arquivos mortos. Os inúmeros recursos de filtragem incluem remetente, destinatário, tipo de mensagem, data de envio/recebimento e cópia e cópia oculta, além de sintaxe KQL. Confira mais detalhes em [Descoberta Eletrônica In-loco](https://go.microsoft.com/fwlink/p/?LinkId=314169).
  
O centro de administração do Exchange e o Windows PowerShell remoto podem ser usados para pesquisar até 5.000 caixas de correio ao mesmo tempo em uma Descoberta Eletrônica In-loco. Veja mais detalhes sobre como usar o Windows PowerShell remoto para executar pesquisas de Descoberta Eletrônica In-loco em [New-MailboxSearch](https://go.microsoft.com/fwlink/p/?LinkId=314170). 
  
> [!NOTE]
> No Windows PowerShell remoto, o cmdlet  `Search-Mailbox` pode ser usado para pesquisar mais de 5.000 caixas de correio. Veja mais detalhes sobre a pesquisa de um grande número de caixas de correio usando remoto do Windows PowerShell em [Search-Mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314171). 
  
Os resultados das pesquisas de Descoberta Eletrônica In-loco podem ser visualizados na interface baseada na Web, exportados para um arquivo PST ou copiados para um tipo especial de caixa de correio, a caixa de correio de Descoberta. Os administradores ou diretores de conformidade podem se conectar à caixa de correio de descoberta para examinar mensagens. Veja mais detalhes em [criar uma pesquisa de eDiscovery In-loco](https://go.microsoft.com/fwlink/p/?LinkId=314172).
  
> [!NOTE]
> Quando a cópia de resultados de pesquisa para uma pesquisa de Descoberta Eletrônica no local realizadas em local e caixas de correio baseada em nuvem ou arquivos, você deve selecionar uma caixa de correio de descoberta no local. As mensagens de caixa de correio principal do local e o arquivamento baseado em nuvem são copiadas para a caixa de correio de descoberta no local. 
  
Os administradores também podem procurar e excluir mensagens de email inadequado enviadas para várias caixas de correio através de suas organizações. Por exemplo, se informações confidenciais sobre salário tiverem sido enviadas acidentalmente a todos os funcionários por email, um administrador poderá excluir o email das caixas de correio dos usuários. Esse tipo de pesquisa não está disponível no Centro de administração do Exchange. Deve ser executada usando o PowerShell remoto. Veja mais detalhes sobre como excluir mensagens de caixas de correio dos usuários em [Pesquisar e excluir mensagens](https://go.microsoft.com/fwlink/p/?LinkId=314173).
  
## <a name="security-features-in-exchange-online-archiving"></a>Recursos de segurança no Arquivamento do Exchange Online

As seções a seguir descrevem os recursos de segurança da Microsoft Arquivamento do Exchange Online.
  
### <a name="encryption-between-on-premises-servers-and-exchange-online-archiving"></a>Criptografia entre servidores no local e o Arquivamento do Exchange Online

TLS é usado para criptografar a conexão entre servidores de email para ajudar a evitar a falsificação e fornecer confidencialidade para mensagens em trânsito. TLS é usado também para proteger o tráfego de servidor de correio electrónico no local para Office 365 centros de dados para Arquivamento do Exchange Online.
  
### <a name="encrypting-between-clients-and-exchange-online-archiving"></a>Criptografia entre clientes e o Arquivamento do Exchange Online

Conexões de cliente a Arquivamento do Exchange Online use os seguintes métodos de criptografia para aumentar a segurança:
  
- SSL é usado para proteger o Outlook, o Outlook Web App e tráfego de serviços Web do Exchange, usando a porta TCP 443.
    
- Conexões de cliente com servidores locais não são alteradas com a introdução do Arquivamento do Exchange Online.
    
### <a name="encryption-smime-and-pgp"></a>Criptografia: S/MIME e PGP

Arquivamento do Exchange Online irá armazenar mensagens de Secure/Multipurpose Internet Mail Extensions (S/MIME). Entretanto, Arquivamento do Exchange Online não hospeda S/MIME funções ou hospedar as chaves públicas, nem fornecer repositório chave, gerenciamento de chave ou serviços de diretório chave porque todos estes serviços anexar para a infra-estrutura do Exchange no local.
  
Semelhantemente, Arquivamento do Exchange Online armazena mensagens que são criptografadas usando soluções de terceiros do lado do cliente como o PGP.
  
### <a name="information-rights-management"></a>Gerenciamento de Direitos de Informação

O Arquivamento do Exchange Online não oferece serviços hospedados de IRM (Gerenciamento de Direitos de Informação), mas os administradores podem usar o AD RMS (Active Directory Rights Management Services) local com o Exchange Online. Se um servidor AD RMS for implantado, o Outlook poderá se comunicar diretamente com o servidor, permitindo que os usuários redijam e leiam mensagens protegidas pelo AD RMS. Se estiver configurada a interoperabilidade entre o servidor do AD RMS e o ambiente do Exchange no local, os usuários será capazes de compor e ler mensagens protegidas por IRM.
  
#### <a name="support-for-irm-in-outlook-web-app"></a>Suporte para IRM no Outlook Web App

Os usuários podem ler e criar mensagens protegidas por IRM nativamente no Outlook Web App, assim como no Outlook. Eles podem também exibir mensagens protegidas por IRM no Outlook Web App usando os navegadores Internet Explorer, Firefox, Safari e Chrome (sem nenhum plug-in necessário). Os recursos de visualização incluem pesquisa de texto completo, exibição de conversa e o painel de visualização. Interoperabilidade entre o servidor do Active Directory Rights Management Services e o ambiente do Exchange no local deve ser configurada para habilitar isso.
  
#### <a name="irm-search"></a>Pesquisa IRM

As mensagens protegidas por IRM são indexadas e pesquisáveis, incluindo cabeçalhos, assunto, corpo e anexos. Os usuários podem pesquisar itens protegidos por IRM no Outlook e no Outlook Web App e os administradores podem pesquisar itens protegidos por IRM usando a Descoberta Eletrônica In-loco ou o cmdlet **Search-Mailbox**. 
  
### <a name="auditing"></a>Auditoria

Arquivamento do Exchange Online fornece dois tipos de recursos de auditoria internos:
  
- **Registro de auditoria do administrador**. Permite aos clientes rastrearem mudanças realizadas pelos seus administradores no ambiente do Arquivamento do Exchange Online, incluindo mudanças nas funções do RBAC ou políticas e configurações do Exchange. 
    
- **Log de auditoria de caixa de correio** Auditoria de caixa de correio log permite que os clientes controlar o acesso a caixas de correio por usuários que não seja o proprietário de caixa de correio. 
    
Vários relatórios de auditoria pré-definidos estão disponíveis no Painel de Controle do Exchange, incluindo Mudanças na Função do Administrador, Retenção de Litígio e Acesso de Caixa de Correio por Não Proprietário. Os administradores podem filtrar os relatórios por data e função e podem exportar todos os eventos de auditoria para caixas de correio especificadas no formato XML para retenção a longo prazo ou relatório personalizado.
  
Auditoria de administrador consta do registro por padrão e auditoria de caixa de correio Registro em log está desativado por padrão. Os administradores podem usar o PowerShell remoto do Windows para habilitar o log para algumas ou todas as caixas de correio em sua organização de auditoria de caixa de correio. Confira mais informações em [Relatórios de auditoria](https://go.microsoft.com/fwlink/p/?LinkId=314175).
  
## <a name="feature-availability"></a>Disponibilidade do recurso

Para exibir a disponibilidade de recursos nos planos do Office 365 nas opções autônomas e nas soluções locais, consulte [Descrição do Serviço de Arquivamento do Exchange Online](exchange-online-archiving-service-description.md).
  

