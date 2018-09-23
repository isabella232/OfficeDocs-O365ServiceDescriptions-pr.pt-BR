---
title: Política e Conformidade de Mensagens
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-message-policy-recovery-and-compliance
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5c43c8eb-f8f7-4b5a-a743-b1dab7dc2fc8
ms.openlocfilehash: fd5062df19298720417566d91667f3c3b237b164
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24034983"
---
# <a name="message-policy-and-compliance"></a>Política e Conformidade de Mensagens

## <a name="archiving-exchange-online-based-mailboxes"></a>Arquivamento de Caixas de Correio baseadas no Exchange Online

As caixas de correio do Exchange Online residem na nuvem, e o arquivamento delas requer ambientes de hospedagem exclusivos. Em alguns casos, o Exchange Online pode ser usado também para arquivar caixas de correio locais na nuvem. As opções de arquivamento com o Exchange Online são descritas nesta seção.
  
O Exchange Online oferece recursos de arquivamento interno para caixas de correio baseadas em nuvem, incluindo um Arquivo Morto In-loco que oferece aos usuários um local conveniente para armazenar mensagens de email antigas. O Arquivo Morto In-loco é um tipo especial de caixa de correio que aparece ao longo das pastas de caixa de correio principal de um usuário no Outlook e no Outlook Web App. Os usuários podem acessar e pesquisar o arquivo morto da mesma forma que acessam e pesquisam suas caixas de correio principais. A funcionalidade disponível depende do cliente em uso:
  
- **Outlook 2016, Outlook 2013, Outlook 2010 e Outlook Web App** Os usuários têm acesso a todos os recursos do arquivo morto, além de recursos de conformidade relacionados, como controle sobre políticas de arquivo morto e retenção. 
    
- **Outlook 2007** Os usuários têm suporte básico para o Arquivo Morto In Loco, mas nem todos os recursos de arquivamento e de conformidade estão disponíveis. Por exemplo, os usuários não podem aplicar políticas de retenção ou de arquivamento a itens de caixa de correio e devem se basear em políticas provisionadas pelo administrador. 
    
Os administradores usam o Centro de administração do Exchange ou o Windows PowerShell remoto para habilitar o recurso de arquivo morto pessoal para usuários específicos.
  
Para obter mais informações, consulte:
  
- [Arquivar caixas de correio no Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404421)
    
- [Habilitar ou desabilitar uma caixa de correio de arquivo morto no Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404425)
    
### <a name="archive-sizes"></a>Tamanhos de arquivo morto

Apenas os dados de mensagens de um usuário podem ser armazenados em cada arquivo morto pessoal. A alocação de armazenamento depende do plano de assinatura. Para obter mais informações sobre tamanhos de caixa de correio de arquivo morto, consulte a seção "Limites de armazenamento de caixa de correio" em [Limites do Exchange Online](exchange-online-limits.md).
  
> [!IMPORTANT]
> O uso de registro no diário, regras de transporte ou encaminhamento automático de regras para copiar mensagens para uma caixa de correio do Exchange Online com a finalidade de arquivamento não é permitido. A Microsoft reserva-se o direito de negar o arquivamento ilimitado em situações nas quais um arquivamento de caixa de correio não esteja sendo usado em um cenário pessoal. > O Arquivo Morto In Loco tem requisitos de licenciamento específico para usuários do Outlook. Os usuários do Outlook 2007 devem ter a Atualização Cumulativa do Office 2007 para fevereiro de 2011 para acessarem o arquivo morto pessoal. > O Exchange Online não dá suporte ao cmdlet  _New-MailboxImportRequest_ Windows PowerShell do Exchange Server 2010 Service Pack 1 ou posterior para importação realizada por administrador de arquivos .pst em um arquivo morto pessoal. Se um usuário tiver a caixa de correio principal e o arquivo morto no Exchange Online, um administrador poderá usar o PST Capture, uma ferramenta gratuita, para importar dados de arquivo .pst para o arquivo morto ou a caixa de correio principal do usuário. 
  
## <a name="cloud-based-archiving-of-on-premises-mailboxes"></a>Arquivamento baseado em nuvem de caixas de correio no local

Usar o Exchange Online para arquivamento baseado em nuvem de caixas de correio do Exchange Server 2010 ou posteriores no local é possível com o Arquivamento do Microsoft Exchange Online, uma solução de arquivamento hospedada da Microsoft. Isso requer que a organização no local esteja no modo Híbrido ou seja configurada para o Arquivamento do Exchange Online.
  
> [!IMPORTANT]
> Os usuários com uma caixa de correio no local em um servidor de Caixa de Correio do Exchange 2010 que possuem uma política de Pasta Gerenciada aplicada não podem ter um Arquivo Morto In-loco no local ou baseado em nuvem habilitado. 
  
## <a name="retention-tags-and-retention-policies"></a>Marcas e políticas de retenção

O Exchange Online oferece políticas de retenção para ajudar as organizações a reduzir as obrigações associadas ao email e a outros meios de comunicação. Com essas políticas, os administradores podem aplicar configurações de retenção a pastas específicas nas caixas de entrada dos usuários. Os administradores podem também dar aos usuários um menu de políticas de retenção e permitir que eles apliquem as políticas a itens, conversas ou pastas específicos usando o Outlook 2010 ou posterior ou o Outlook Web App.
  
No Exchange Online, os administradores gerenciam as políticas de retenção usando o Centro de administração do Exchange (EAC) ou o Windows PowerShell remoto.
  
O Exchange Online oferece dois tipos de políticas: políticas de arquivo morto e políticas de exclusão. Ambos os tipos podem ser combinados no mesmo item ou pasta. Por exemplo, o usuário pode marcar uma mensagem de email para ser movida automaticamente para o Arquivo Morto In-loco em um número especificado de dias e excluída após outro intervalo de dias.
  
Com o Outlook 2010 ou posterior e Outlook Web App, os usuários podem aplicar políticas de retenção a pastas, conversas ou mensagens individuais. Eles podem também exibir as políticas de retenção aplicadas e as datas de exclusão esperadas em mensagens. Os usuários de outros clientes de email podem apenas ter mensagens de email excluídas ou arquivadas com base nas políticas de retenção do lado de servidor definidas pelo administrador.
  
Os recursos de política de retenção oferecidos no Exchange Online são iguais aos oferecidos no Exchange Server 2010 Service Pack 2 RU4. Os administradores podem usar o Windows PowerShell remoto para migrar políticas de retenção de ambientes do Exchange Server 2010 ou posterior locais para o Exchange Online.
  
> [!IMPORTANT]
> Pastas Gerenciadas, uma abordagem mais antiga ao gerenciamento de registros de mensagens introduzida no Exchange Server 2007, não estão disponíveis no Exchange Online. 
  
Confira mais informações em [Marcas e políticas de retenção](https://go.microsoft.com/fwlink/p/?LinkId=271745).
  
## <a name="encryption-of-data-at-rest"></a>Criptografia de dados em repouso

Criptografia de dados de cliente do Office 365 em repouso é fornecida por várias tecnologias de no lado do serviço, incluindo o BitLocker, DKM, criptografia de serviço de armazenamento do Windows Azure e criptografia de serviço no Exchange Online, Skype for Business, OneDrive for Business e SharePoint Online. O Office 365 criptografia de serviço incluem uma opção para usar as chaves de criptografia gerenciado pelo cliente que são armazenadas no armazenamento de chave do Windows Azure. Essa opção de chave gerenciada do cliente, chamada [Chave de cliente do Office 365](https://go.microsoft.com/fwlink/?linkid=863349), está disponível para o Exchange Online, SharePoint Online e OneDrive for Business. 
  
### <a name="bitlocker"></a>BitLocker

Servidores do Office 365 usam BitLocker para criptografar as unidades de disco que contém os dados em repouso no nível de volume do cliente. Criptografia de disco BitLocker é um recurso de proteção de dados interno do Windows. O BitLocker é uma das tecnologias usadas para a proteção contra ameaças, caso haja falhas em outros processos ou controles (por exemplo, controle de acesso ou reciclagem de hardware) que poderiam levar a alguém que tenha acesso físico nos discos contendo os dados do cliente. Nesse caso, o BitLocker elimina o potencial de dados roubo ou exposição por causa de discos e computadores inadequadamente, perdidos ou roubados. 
  
### <a name="distributed-key-manager"></a>Gerenciador de chave distribuída

Além das BitLocker, usamos uma tecnologia chamada Gerenciador de chave distribuído (DKM). DKM é uma funcionalidade de cliente que usa um conjunto de chaves secretas para criptografar e descriptografar informações. Somente os membros de um grupo de segurança específicas nos serviços de domínio do Active Directory podem acessar essas chaves para descriptografar os dados que são criptografados por DKM. No Exchange Online, apenas certas contas de serviço sob o qual os processos do Exchange executado fazem parte do grupo de segurança. Como parte do procedimento de operacional padrão no datacenter, nenhum humanos recebe as credenciais que fazem parte deste grupo de segurança e, portanto, nenhum humanos tem acesso às chaves que podem descriptografar esses segredos.
  
## <a name="customer-key"></a>Chave do Cliente

Com a chave do cliente, você controlar as chaves de criptografia da sua organização e configurar o Office 365 para usá-los para criptografar dados em repouso em centros de dados da Microsoft. Dados em repouso incluem os dados do Exchange Online e do Skype for Business que é armazenado em caixas de correio e arquivos que são armazenados no SharePoint Online e o OneDrive for Business. Para obter mais informações, consulte [controlar seus dados no Office 365 usando a chave de cliente](https://go.microsoft.com/fwlink/?linkid=863349) e o [Serviço de criptografia com a chave do cliente para perguntas Frequentes do Office 365](https://go.microsoft.com/fwlink/?linkid=869438).
  
## <a name="office-365-message-encryption"></a>Criptografia de Mensagens do Office 365
<a name="bkmk_O365_MessageEncryption"> </a>

Criptografia de mensagem do Office 365 permite que os usuários de email enviar mensagens de email criptografadas para qualquer pessoa. Podemos anunciado novos recursos no Office Message Encryption que aproveitam os recursos de proteção em criptografia de informações do Windows Azure. Esses novos recursos fornecidos aprimorado experiências de usuário final que facilitam a compartilhar e colaborar em mensagens protegidas com qualquer usuário dentro ou fora da organização. Os novos recursos de criptografia de mensagem do Office têm alguns requisitos de instalação. Consulte Set up novos recursos do Office 365 Message Encryption construídos sobre a proteção de informações do Windows Azure. Os clientes herdados do Office 365 Message Encryption não obtêm os novos recursos sem seguir as diretrizes fornecidas acima. Leia o [FAQ](https://support.office.com/en-us/article/Office-365-Message-Encryption-FAQ-0432dce9-d9b6-4e73-8a13-4a932eb0081e) para obter mais detalhes sobre o que está incluído no novo versus herdados recursos do Office 365 Message Encryption. 
  
## <a name="securemultipurpose-internet-mail-extensions-smime"></a>S/MIME (Secure/Multipurpose Internet Mail Extensions)
<a name="bkmk_O365_MessageEncryption"> </a>

O S/MIME permite a proteção de informações confidenciais através do envio de emails assinados e criptografados dentro de sua empresa. Os administradores podem usar o PowerShell remoto do Windows para configurar o S/MIME após estabelecer e emitir certificados PKI para os usuários. Esses certificados devem ser sincronizados a partir do Serviço de Certificados do Active Directory local.
  
O Internet Explorer 9 ou versões posteriores oferecem suporte ao S/MIME. Atualmente, o Firefox, o Opera ou o Chrome não oferecem suporte ao S/MIME. Confira mais informações em [S/MIME para assinatura e criptografia de mensagens](https://go.microsoft.com/fwlink/p/?LinkID=393973).
  
## <a name="in-place-hold-and-litigation-hold"></a>Bloqueio In-loco e Retenção de Litígio
<a name="bkmk_O365_MessageEncryption"> </a>

Quando existe uma expectativa razoável de litígio, as organizações são solicitadas a preservar informações armazenadas eletronicamente (ESI), incluindo emails, pertinentes ao caso. Essa expectativa pode acontecer antes que os detalhes do caso sejam conhecidos, e a preservação geralmente é total. As organizações podem preservar todos os emails relacionados a um tópico específico ou todos os emails de determinados indivíduos.
  
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
  
## <a name="in-place-ediscovery"></a>Descoberta eletrônica In-loco
<a name="bkmk_O365_MessageEncryption"> </a>

O Exchange Online permite que os clientes pesquisem o conteúdo de caixas de correio em uma organização usando uma interface baseada na Web. Os administradores e oficiais de segurança e conformidade autorizados a realizar pesquisa de Descoberta Eletrônica In-loco (por atribuição) podem pesquisar mensagens de email, anexos, compromissos de calendário, tarefas, contatos e outros itens. A Descoberta Eletrônica In-loco pode pesquisar simultaneamente em caixas de correio principais e arquivos mortos. Os inúmeros recursos de filtragem incluem remetente, destinatário, tipo de mensagem, data de envio/recebimento e cópia e cópia oculta, além de sintaxe KQL. Os resultados da pesquisa também incluirão itens da pasta Itens Excluídos se eles corresponderem à consulta da pesquisa.
  
Os resultados das pesquisas de Descoberta Eletrônica In-loco podem ser visualizados na interface baseada na Web, exportados para um arquivo PST ou copiados para um tipo especial de caixa de correio, a caixa de correio de Descoberta. Uma caixa de correio de Descoberta tem uma cota de 50 GB para armazenar os resultados da pesquisa. Os administradores também podem conectar o Outlook à caixa de correio de Descoberta para acessar resultados de pesquisa e exportar os resultados para um arquivo .pst.
  
Os administradores usam o Centro de administração do Exchange ou o Windows PowerShell remoto para realizar pesquisas em várias caixas de correio. O Centro de administração do Exchange pode fornecer uma visualização somente leitura dos resultados da pesquisa, permitindo que os administradores verifiquem rapidamente uma pesquisa e a executem novamente, se necessário, com parâmetros diferentes. Após a otimização da pesquisa, o administrador pode copiar os resultados para a caixa de correio de Descoberta.
  
Por padrão, uma caixa de correio de Descoberta é criada para cada organização, mas os administradores podem criar caixas de correio de Descoberta adicionais usando o Windows PowerShell remoto. As caixas de correio de descoberta não podem ser usadas para outra finalidade que não seja o armazenamento de resultados da pesquisa de Descoberta Eletrônica In-loco.
  
Os administradores usam o Centro de administração do Exchange ou o Windows PowerShell remoto para realizar pesquisas de Descoberta Eletrônica In-loco. O Centro de administração do Exchange pode fornecer uma visualização somente leitura dos resultados da pesquisa, permitindo que os administradores verifiquem rapidamente uma pesquisa e a executem novamente, se necessário, com parâmetros diferentes. Depois de otimizada a pesquisa, o administrador poderá copiar os resultados para a caixa de correio de Descoberta ou exportar os resultados da pesquisa para um arquivo PST.
  
Os administradores podem usar o Centro de administração do Exchange ou o Windows PowerShell remoto para pesquisar até 10.000 caixas de correio por vez em uma pesquisa da Descoberta Eletrônica In-Loco. 
  
No Exchange Online, usuários autorizados podem realizar Descoberta Eletrônica In-loco e escolher uma das seguintes ações:
  
- **Estimar resultados de pesquisa** Obtenha uma estimativa do número de mensagens que a pesquisa irá retornar, incluindo estatísticas de palavras-chave para determinar a eficácia das palavras-chave utilizadas na pesquisa e ajustar parâmetros de busca, se necessário. 
    
- **Visualização de resultados de pesquisa**
    
- Copie mensagens retornadas nos resultados da pesquisa para uma caixa de correio de Descoberta.
    
Para obter mais informações, consulte [Descoberta Eletrônica In-loco](http://go.microsoft.com/fwlink/p/?LinkId=271747).
  
## <a name="mail-flow-rules"></a>Regras do fluxo de email
<a name="bkmk_O365_MessageEncryption"> </a>

Você pode usar as regras de fluxo de correio para procurar condições específicas em mensagens que passam pelo sua organização e agir neles. Regras de fluxo de correio permitem que você aplique políticas de mensagens para as mensagens de email, mensagens seguras, proteger sistemas de mensagens e evitar vazamento de informações.
  
Atualmente, várias organizações são obrigadas por lei, requisitos reguladores ou diretivas da empresa a aplicar diretivas de mensagens que limitam a interação entre destinatários e remetentes, dentro e fora da organização. Além de limitar as interações entre os indivíduos, grupos de departamentos dentro da organização e entidades fora da organização, algumas organizações estão sujeitas também aos seguintes requisitos de diretivas de mensagens:
  
- Evitar que conteúdo inadequado entre ou saia da organização
    
- Filtrar informações confidenciais da organização
    
- Controlar ou copiar mensagens enviadas ou recebidas de determinadas pessoas
    
- Redirecionar mensagens de entrada e de saída para inspeção antes da entrega
    
- Aplicar avisos de isenção às mensagens transmitidas pela organização
    
> [!IMPORTANT]
> Tipos de arquivo de anexo que requerem a instalação do iFilters de terceiros no servidor de email (por exemplo,. PDF do Adobe) não pode ser inspecionada usando regras de fluxo de email até após a instalação do iFilter apropriado. Para obter mais informações sobre os tipos de arquivo que são compatíveis com as regras de fluxo de correio, consulte [usar regras de fluxo de email para inspecionar anexos de mensagens no Office 365](https://go.microsoft.com/fwlink/p/?LinkId=271748). 
  
Para obter mais informações sobre regras de fluxo de correio, consulte [Mail flow regras no Exchange 2016](https://go.microsoft.com/fwlink/p/?LinkId=296488).
  
## <a name="data-loss-prevention"></a>Prevenção contra perda de dados
<a name="bkmk_O365_MessageEncryption"> </a>

O recurso de prevenção contra perda de dados (DLP) o ajudará a identificar, monitorar e proteger informações confidenciais em sua organização por meio de análise de conteúdo profunda. DLP é um recurso superior cada vez mais importante para sistemas de mensagens corporativos porque o email crucial para os negócios inclui dados confidenciais que precisam ser protegidos. O recurso DLP no Exchange Online permite que você proteja dados confidenciais sem afetar a produtividade do trabalhador.
  
Você pode configurar políticas de DLP na interface de gerenciamento do Centro de administração do Exchange (EAC), que lhe permite: 
  
- Iniciar com um modelo de política pré-configurado que pode ajudar a detectar tipos específicos de informações confidenciais, como dados PCI-DSS, dados do Gramm-Leach-Bliley Act ou até mesmo informações de identificação pessoal (PII) específicas de localidade.
    
- Use todo o poder dos critérios e das ações de regras de transporte existentes e adicione novas regras de transporte.
    
- Teste a eficácia das suas políticas de DLP antes de impô-las totalmente.
    
- Incorpore seus próprios modelos personalizados de política de DLP e tipos de informações confidenciais.
    
- Detectar informações confidenciais em anexos de mensagens, texto do corpo ou linhas de assunto e ajustar o nível de confiança em que atua Exchange Online.
    
- Detecte dados sensíveis por meio de impressão digital do documento. A Impressão Digital do Documento ajuda você a criar facilmente tipos de informações sensíveis personalizadas com base em formulários baseados em texto que você pode usar para definir regras de transporte e políticas DLP.
    
- Adicione Dicas de Política, que podem ajudar a reduzir a perda de dados ao exibir um aviso para os usuários do Outlook 2016, Outlook 2013, Outlook Web App e OWA para Dispositivos, além de aumentar a efetividade das políticas permitindo a denúncia de falsos positivos.  
    
- Revise os dados de incidentes em relatórios de DLP ou adicione seus próprios relatórios específicos usando uma ação de geração de relatórios de incidentes.
    
Confira mais informações sobre DLP em [Prevenção contra perda de dados](https://go.microsoft.com/fwlink/p/?LinkId=271749).
  
## <a name="journaling"></a>Registro em Diário
<a name="bkmk_O365_MessageEncryption"> </a>

Você pode configurar o Exchange Online para registrar em diário cópias de email em qualquer caixa de correio existente que possa receber mensagens via SMTP. O registro em diário pode ajudar a organização a atender requisitos legais, regulatórios e organizacionais de conformidade, registrando a comunicação por emails de entrada e de saída. Durante o planejamento para retenção e conformidade de mensagens, é importante compreender o registro no diário e como ele se adapta às políticas de conformidade da organização.
  
Você pode gerenciar regras de diário usando o Centro de administração do Exchange ou o Windows PowerShell remoto. Você pode configurar o registro no diário por usuário e por lista de distribuição e optar por registrar em diário somente mensagens internas, somente externas ou ambas. As mensagens registradas em diário incluem não só a mensagem original, mas também informações sobre o remetente, destinatários, cópias e cópias ocultas.
  
Para garantir uma solução de registro no diário de sucesso e confiável, você precisará concluir as seguintes tarefas:
  
- Certifique-se de que o destino de registro no diário não é ser uma caixa de correio do Exchange Online.
    
- Crie no diretório de cliente um objeto de contato para o endereço de email de destino SMTP a ser usado para registro no diário.
    
- Crie um segundo objeto de contato como uma caixa de correio de registro no diário alternativa para capturar todos os relatórios de registro no diário quando a caixa de correio de registro no diário principal estiver indisponível.
    
- Manter gerenciamento adequado, redundância, disponibilidade, desempenho e os níveis de funcionalidade do destino SMTP para garantir a aceitação de email com êxito sempre.
    
- Forneça a respectiva interoperabilidade com o Exchange Server e o transporte do Exchange, incluindo formatos de mensagem, integração de informações de remetente/destinatário e conversão de conteúdo apropriada.
    
Confira mais informações sobre o registro no diário em [Registro no diário](https://go.microsoft.com/fwlink/p/?LinkId=271750).
  
## <a name="feature-availability"></a>Disponibilidade de recursos
<a name="bkmk_O365_MessageEncryption"> </a>

Para exibir a disponibilidade de recursos nos planos do Office 365 nas opções autônomas e nas soluções locais, consulte [Descrição de Serviço do Exchange Online](exchange-online-service-description.md).
  

