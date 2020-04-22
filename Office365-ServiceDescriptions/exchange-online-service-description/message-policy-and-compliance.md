---
title: Política e conformidade de mensagens
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-message-policy-recovery-and-compliance
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5c43c8eb-f8f7-4b5a-a743-b1dab7dc2fc8
ms.openlocfilehash: 4d81cef3f2b3edefe21e40b0cde6a6edcc0fc1af
ms.sourcegitcommit: 7a68dc894dde0d06fab014c56914a78aa8cda847
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/21/2020
ms.locfileid: "43638912"
---
# <a name="message-policy-and-compliance"></a>Política e conformidade de mensagens

## <a name="archiving-exchange-online-based-mailboxes"></a>Arquivamento de Caixas de Correio baseadas no Exchange Online

As caixas de correio do Exchange Online residem na nuvem, e o arquivamento delas requer ambientes de hospedagem exclusivos. Em alguns casos, o Exchange Online pode ser usado também para arquivar caixas de correio locais na nuvem. As opções de arquivamento com o Exchange Online são descritas nesta seção.
  
O Exchange Online oferece recursos de arquivamento interno para caixas de correio baseadas em nuvem, incluindo um Arquivo Morto In-loco que oferece aos usuários um local conveniente para armazenar mensagens de email antigas. Um arquivo morto in-loco é um tipo especial de caixa de correio que aparece junto com as pastas de caixa de correio principais de um usuário no Outlook e no Outlook na Web. Os usuários podem acessar e pesquisar o arquivo morto da mesma forma que acessam e pesquisam suas caixas de correio principais. A funcionalidade disponível depende do cliente em uso:
  
- **Outlook 2016, outlook 2013, outlook 2010 e Outlook na Web** Os usuários têm acesso a todos os recursos do arquivamento, bem como os recursos de conformidade relacionados, como controle sobre políticas de retenção e arquivamento. 
    
- **Outlook 2007** Os usuários têm suporte básico para o Arquivo Morto In Loco, mas nem todos os recursos de arquivamento e de conformidade estão disponíveis. Por exemplo, os usuários não podem aplicar políticas de retenção ou de arquivamento a itens de caixa de correio e devem se basear em políticas provisionadas pelo administrador. 
    
Os administradores usam o Centro de administração do Exchange ou o Windows PowerShell remoto para habilitar o recurso de arquivo morto pessoal para usuários específicos.
  
Para obter mais informações, consulte:
  
- [Arquivar caixas de correio no Exchange Online](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-archiving-service-description/archive-features)
    
- [Habilitar ou desabilitar uma caixa de correio de arquivo morto no Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes)
    
### <a name="archive-sizes"></a>Tamanhos de arquivo morto

Apenas os dados de mensagens de um usuário podem ser armazenados em cada arquivo morto pessoal. A alocação de armazenamento depende do plano de assinatura. Para obter mais informações sobre tamanhos de caixa de correio de arquivo morto, consulte a seção "limites de armazenamento de caixa de correio" em [limites do Exchange Online](exchange-online-limits.md).
  
> [!IMPORTANT]
> - O uso de registro no diário, regras de transporte ou regras de encaminhamento automático para copiar mensagens para uma caixa de correio do Exchange Online com a finalidade de arquivamento não é permitido. A Microsoft reserva-se o direito de negar o arquivamento ilimitado em casos em que um arquivo de caixa de correio não está sendo usado em um cenário pessoal ou em outros casos de uso inadequado.
> - O Arquivo Morto In Loco tem requisitos de licenciamento específico para usuários do Outlook. Os usuários do Outlook 2007 devem ter a Atualização Cumulativa do Office 2007 para fevereiro de 2011 para acessarem o arquivo morto pessoal. 
> - O Exchange Online não dá suporte ao cmdlet _New-MailboxImportRequest_ do Windows PowerShell do Exchange Server 2010 Service Pack 1 ou posterior para a importação controlada pelo administrador de arquivos. pst em um arquivo morto pessoal. Se um usuário tiver a caixa de correio principal e o arquivo morto no Exchange Online, um administrador poderá usar o PST Capture, uma ferramenta gratuita, para importar dados de arquivo .pst para o arquivo morto ou a caixa de correio principal do usuário.

## <a name="cloud-based-archiving-of-on-premises-mailboxes"></a>Arquivamento baseado em nuvem de caixas de correio no local

Usar o Exchange Online para arquivamento baseado em nuvem de caixas de correio do Exchange Server 2010 ou posteriores no local é possível com o Arquivamento do Microsoft Exchange Online, uma solução de arquivamento hospedada da Microsoft. Isso requer que a organização no local esteja no modo Híbrido ou seja configurada para o Arquivamento do Exchange Online.
  
> [!IMPORTANT]
> Os usuários com uma caixa de correio no local em um servidor de Caixa de Correio do Exchange 2010 que possuem uma política de Pasta Gerenciada aplicada não podem ter um Arquivo Morto In-loco no local ou baseado em nuvem habilitado. 
  
## <a name="retention-tags-and-retention-policies"></a>Marcas e políticas de retenção

O Exchange Online oferece políticas de retenção para ajudar as organizações a reduzir as obrigações associadas ao email e a outros meios de comunicação. Com essas políticas, os administradores podem aplicar configurações de retenção a pastas específicas nas caixas de entrada dos usuários. Os administradores também podem fornecer aos usuários um menu de políticas de retenção e permitir que eles apliquem as políticas a itens específicos, conversas ou pastas usando o Outlook 2010 ou posterior ou o Outlook na Web.
  
No Exchange Online, os administradores gerenciam as políticas de retenção usando o Centro de administração do Exchange (EAC) ou o Windows PowerShell remoto.
  
O Exchange Online oferece dois tipos de políticas: políticas de arquivo morto e políticas de exclusão. Ambos os tipos podem ser combinados no mesmo item ou pasta. Por exemplo, o usuário pode marcar uma mensagem de email para ser movida automaticamente para o Arquivo Morto In-loco em um número especificado de dias e excluída após outro intervalo de dias.
  
Com o Outlook 2010 ou posterior e o Outlook na Web, os usuários podem aplicar políticas de retenção a pastas, conversas ou mensagens individuais. Eles podem também exibir as políticas de retenção aplicadas e as datas de exclusão esperadas em mensagens. Os usuários de outros clientes de email podem apenas ter mensagens de email excluídas ou arquivadas com base nas políticas de retenção do lado de servidor definidas pelo administrador.
  
Os recursos de política de retenção oferecidos no Exchange Online são iguais aos oferecidos no Exchange Server 2010 Service Pack 2 RU4. Os administradores podem usar o Windows PowerShell remoto para migrar políticas de retenção de ambientes do Exchange Server 2010 ou posterior locais para o Exchange Online.
  
> [!IMPORTANT]
> Pastas Gerenciadas, uma abordagem mais antiga ao gerenciamento de registros de mensagens introduzida no Exchange Server 2007, não estão disponíveis no Exchange Online. 
  
Confira mais informações em [Marcas e políticas de retenção](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/retention-tags-and-policies).
  
## <a name="encryption-of-data-at-rest"></a>Criptografia de dados em repouso

A criptografia de dados do cliente em repouso é fornecida por várias tecnologias do lado do serviço, incluindo BitLocker, DKM, criptografia do serviço de armazenamento do Azure e criptografia de serviço no Exchange Online, Skype for Business, OneDrive for Business e SharePoint Online. A criptografia de serviço do Office 365 inclui uma opção para usar chaves de criptografia gerenciadas pelo cliente armazenadas no Azure Key Vault. Essa opção de chave gerenciada pelo cliente, chamada de [chave do cliente](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key?redirectSourcePath=%252fen-us%252farticle%252fControlling-your-data-in-Office-365-using-Customer-Key-f2cd475a-e592-46cf-80a3-1bfb0fa17697), está disponível para o Exchange Online, o SharePoint Online e o onedrive for Business. 
  
### <a name="bitlocker"></a>BitLocker

Os servidores da Microsoft usam o BitLocker para criptografar as unidades de disco que contêm os dados do cliente em repouso no nível do volume. A criptografia BitLocker é um recurso de proteção de dados interno do Windows. O BitLocker é uma das tecnologias usadas para proteger contra ameaças caso haja interrupções em outros processos ou controles (por exemplo, controle de acesso ou reciclagem de hardware) que podem levar a alguém obtendo acesso físico a discos que contêm dados do cliente. Nesse caso, o BitLocker elimina a possibilidade de roubo de dados ou exposição por causa de computadores e discos perdidos, roubados ou indevidamente descomissionados. 
  
### <a name="distributed-key-manager"></a>Distributed Key Manager

Além do BitLocker, usamos uma tecnologia chamada DKM (Distributed Key Manager). O DKM é uma funcionalidade do lado do cliente que usa um conjunto de chaves secretas para criptografar e descriptografar informações. Somente membros de um grupo de segurança específico nos serviços de domínio Active Directory podem acessar essas chaves para descriptografar os dados que são criptografados pelo DKM. No Exchange Online, apenas certas contas de serviço, sob as quais os processos do Exchange são executados, fazem parte do grupo de segurança. Como parte do procedimento operacional padrão no datacenter, nenhum humano recebe credenciais que fazem parte deste grupo de segurança e, portanto, nenhuma pessoa tem acesso às chaves que podem descriptografar esses segredos.
  
## <a name="customer-key"></a>Chave de Cliente

Com a chave do cliente, você controla as chaves de criptografia da organização e as configura para criptografar seus dados em repouso nos datacenters da Microsoft. Os dados em repouso incluem dados do Exchange Online e do Skype for Business que são armazenados em caixas de correio e arquivos armazenados no SharePoint Online e no OneDrive for Business. Para obter mais informações, consulte [controle dos dados no usando a chave do cliente](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key) e [a criptografia de serviço com as principais perguntas frequentes do cliente](https://docs.microsoft.com/office365/securitycompliance/service-encryption-with-customer-key-faq).
  
## <a name="office-365-message-encryption"></a>Criptografia de Mensagem do Office 365

A criptografia de mensagem do Office 365 permite que os usuários de email enviem mensagens de email criptografadas para qualquer pessoa. Anunciamos novos recursos na criptografia de mensagens do Office que aproveitam os recursos de proteção na criptografia de informações do Azure. Esses novos recursos forneciam experiências aprimoradas do usuário final que facilitam o compartilhamento e a colaboração em mensagens protegidas com qualquer pessoa dentro ou fora da organização. Os novos recursos de criptografia de mensagens do Office possuem alguns requisitos de configuração. Confira configurar os novos recursos de criptografia de mensagem do Office 365 criados sobre a proteção de informações do Azure. Os clientes da criptografia de mensagens herdadas do Office 365 não obtêm os novos recursos sem seguir a orientação de configuração fornecida acima. Leia as [perguntas frequentes](https://support.office.com/article/Office-365-Message-Encryption-FAQ-0432dce9-d9b6-4e73-8a13-4a932eb0081e) para obter mais detalhes sobre o que está incluído nos novos recursos do vs. legacy Office 365 Message Encryption. 

A criptografia de mensagem avançada do Office 365 fornece proteção adicional, permitindo a expiração e revogação de mensagens.  Você também pode criar vários modelos para emails criptografados provenientes da sua organização.  A criptografia de mensagem avançada está incluída no Microsoft 365 e5, Office 365 e5, Microsoft 365 E5 (precificação de pessoas sem fins lucrativos), Office 365 Enterprise E5 (precificação de pessoal sem fins lucrativos) ou Office 365 Education. Se sua organização tem uma assinatura que não inclui a criptografia de mensagem avançada do Office 365, você pode comprar o Microsoft 365 E5 conformidade ou a SKU de conformidade avançada do Office 365 como um complemento.

## <a name="securemultipurpose-internet-mail-extensions-smime"></a>S/MIME (Secure/Multipurpose Internet Mail Extensions)

O S/MIME permite a proteção de informações confidenciais através do envio de emails assinados e criptografados dentro de sua empresa. Os administradores podem usar o PowerShell remoto do Windows para configurar o S/MIME após estabelecer e emitir certificados PKI para os usuários. Esses certificados devem ser sincronizados a partir do Serviço de Certificados do Active Directory local.
  
O S/MIME é compatível com o Microsoft Edge e o Internet Explorer 11. Atualmente, o Firefox, o Opera ou o Chrome não oferecem suporte ao S/MIME. Confira mais informações em [S/MIME para assinatura e criptografia de mensagens](https://docs.microsoft.com/Exchange/policy-and-compliance/smime?view=exchserver-2019).
  
## <a name="in-place-hold-and-litigation-hold"></a>Bloqueio In-loco e Retenção de Litígio

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
  
Confira mais informações em [Bloqueio In-loco e Retenção Local](https://docs.microsoft.com/exchange/security-and-compliance/in-place-and-litigation-holds).
  
## <a name="in-place-ediscovery"></a>Descoberta Eletrônica In-loco

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
    
Para obter mais informações, consulte [Descoberta Eletrônica In-loco](https://docs.microsoft.com/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery).
  
## <a name="mail-flow-rules"></a>Regras do fluxo de email

Você pode usar regras de fluxo de emails para procurar condições específicas em mensagens que passam pela sua organização e as agem. As regras de fluxo de emails permitem que você aplique políticas de mensagens a mensagens de email, mensagens seguras, proteger sistemas de mensagens e evitar vazamento de informações.
  
Atualmente, várias organizações são obrigadas por lei, requisitos reguladores ou diretivas da empresa a aplicar diretivas de mensagens que limitam a interação entre destinatários e remetentes, dentro e fora da organização. Além de limitar as interações entre os indivíduos, grupos de departamentos dentro da organização e entidades fora da organização, algumas organizações estão sujeitas também aos seguintes requisitos de diretivas de mensagens:
  
- Evitar que conteúdo inadequado entre ou saia da organização
    
- Filtrar informações confidenciais da organização
    
- Controlar ou copiar mensagens enviadas ou recebidas de determinadas pessoas
    
- Redirecionar mensagens de entrada e de saída para inspeção antes da entrega
    
- Aplicar avisos de isenção às mensagens transmitidas pela organização
    
> [!IMPORTANT]
> Os tipos de arquivo de anexo que exigem a instalação de iFilters de terceiros no servidor de email (como Adobe. pdf) não podem ser inspecionados usando regras de fluxo de emails até que um iFilter apropriado seja instalado. Para obter mais informações sobre tipos de arquivo que são compatíveis com as regras de fluxo de emails, consulte [usar regras de fluxo de emails para inspecionar anexos de mensagens no Office 365](https://docs.microsoft.com/exchange/security-and-compliance/mail-flow-rules/inspect-message-attachments).
  
Para obter mais informações sobre regras de fluxo de emails, consulte [Mail Flow Rules in Exchange 2016](https://docs.microsoft.com/Exchange/policy-and-compliance/mail-flow-rules/mail-flow-rules?view=exchserver-2019).
  
## <a name="data-loss-prevention"></a>Prevenção contra perda de dados

O recurso de prevenção contra perda de dados (DLP) o ajudará a identificar, monitorar e proteger informações confidenciais em sua organização por meio de análise de conteúdo profunda. DLP é um recurso superior cada vez mais importante para sistemas de mensagens corporativos porque o email crucial para os negócios inclui dados confidenciais que precisam ser protegidos. O recurso DLP no Exchange Online permite proteger dados confidenciais sem afetar a produtividade do trabalhador.
  
Você pode configurar políticas de DLP na interface de gerenciamento do Centro de administração do Exchange (EAC), que lhe permite: 
  
- Iniciar com um modelo de política pré-configurado que pode ajudar a detectar tipos específicos de informações confidenciais, como dados PCI-DSS, dados do Gramm-Leach-Bliley Act ou até mesmo informações de identificação pessoal (PII) específicas de localidade.
    
- Use todo o poder dos critérios e das ações de regras de transporte existentes e adicione novas regras de transporte.
    
- Teste a eficácia das suas políticas de DLP antes de impô-las totalmente.
    
- Incorpore seus próprios modelos personalizados de política de DLP e tipos de informações confidenciais.
    
- Detectar informações confidenciais em anexos de mensagens, texto do corpo ou linhas de assunto e ajustar o nível de confiança em que o Exchange Online atua.
    
- Detecte dados confidenciais por meio de impressão digital do documento. A impressão digital de documentos ajuda você a criar facilmente tipos de informações confidenciais personalizadas com base em formulários baseados em texto que você pode usar para definir as regras de transporte e políticas de DLP.
    
- Adicionar dicas de política, que podem ajudar a reduzir a perda de dados, exibindo um aviso para o Outlook 2016, Outlook 2013, Outlook na Web e OWA para dispositivos usuários e também podem melhorar a eficácia de suas políticas, permitindo relatórios falsos positivos. 
    
- Revise os dados de incidentes em relatórios de DLP ou adicione seus próprios relatórios específicos usando uma ação de geração de relatórios de incidentes.
    
Confira mais informações sobre DLP em [Prevenção contra perda de dados](https://docs.microsoft.com/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention).
  
## <a name="journaling"></a>Registro no diário

Você pode configurar o Exchange Online para registrar em diário cópias de email em qualquer caixa de correio existente que possa receber mensagens via SMTP. O registro em diário pode ajudar a organização a atender requisitos legais, regulatórios e organizacionais de conformidade, registrando a comunicação por emails de entrada e de saída. Durante o planejamento para retenção e conformidade de mensagens, é importante compreender o registro no diário e como ele se adapta às políticas de conformidade da organização.
  
Você pode gerenciar regras de diário usando o Centro de administração do Exchange ou o Windows PowerShell remoto. Você pode configurar o registro no diário por usuário e por lista de distribuição e optar por registrar em diário somente mensagens internas, somente externas ou ambas. As mensagens registradas em diário incluem não só a mensagem original, mas também informações sobre o remetente, destinatários, cópias e cópias ocultas.
  
Para garantir uma solução de registro no diário bem-sucedida e confiável, é necessário concluir as seguintes tarefas:
  
- Verifique se o destino do registro no diário não é uma caixa de correio do Exchange Online.
    
- Crie no diretório de cliente um objeto de contato para o endereço de email de destino SMTP a ser usado para registro no diário.
    
- Crie um segundo objeto de contato como uma caixa de correio de registro no diário alternativa para capturar todos os relatórios de registro no diário quando a caixa de correio de registro no diário principal estiver indisponível.
    
- Manter os níveis adequados de gerenciamento, redundância, disponibilidade, desempenho e funcionalidade do destino SMTP para garantir uma aceitação bem-sucedida de emails.
    
- Forneça a respectiva interoperabilidade com o Exchange Server e o transporte do Exchange, incluindo formatos de mensagem, integração de informações de remetente/destinatário e conversão de conteúdo apropriada.
    
Confira mais informações sobre o registro no diário em [Registro no diário](https://docs.microsoft.com/exchange/security-and-compliance/journaling/journaling).
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos nos planos, nas opções autônomas e nas soluções locais, consulte [Descrição do serviço do Exchange Online](exchange-online-service-description.md).
  

