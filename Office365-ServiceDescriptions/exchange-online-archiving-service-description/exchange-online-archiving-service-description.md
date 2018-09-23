---
title: Descrição do Serviço de Arquivamento do Exchange Online
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-archiving-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 21ebd4bb-7d88-489f-a8aa-376e2536900c
description: Arquivamento do Microsoft Exchange Online é uma Microsoft Office 365 baseadas em nuvem corporativo solução de arquivamento para as organizações que implantaram o Microsoft Exchange Server 2013, o Microsoft Exchange Server 2010 (SP2 e posterior), ou se inscrever para certos Planos do Exchange Online ou do Office 365. Arquivamento do Exchange Online auxilia essas organizações com seus arquivamento, conformidade, normas, e desafios de descoberta eletrônica ao mesmo tempo em que simplifica a infraestrutura do local e reduzindo custos e atenuação cargas IT.
ms.openlocfilehash: d88d336f0e5b30a245b6c90c7cc488ca6d5dfc54
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24034799"
---
# <a name="exchange-online-archiving-service-description"></a>Descrição do Serviço de Arquivamento do Exchange Online

Arquivamento do Microsoft Exchange Online é uma Microsoft Office 365 baseadas em nuvem corporativo solução de arquivamento para as organizações que implantaram o Microsoft Exchange Server 2013, o Microsoft Exchange Server 2010 (SP2 e posterior), ou se inscrever para certos Planos do Exchange Online ou do Office 365. Arquivamento do Exchange Online auxilia essas organizações com seus arquivamento, conformidade, normas, e desafios de descoberta eletrônica ao mesmo tempo em que simplifica a infraestrutura do local e reduzindo custos e atenuação cargas IT.
  
Como um serviço on-line do Microsoft Office 365, o Arquivamento do Exchange Online foi projetado para ajudar a atender a necessidade de segurança robusta, de confiabilidade e de produtividade de usuário. Para obter mais informações sobre Office 365, incluindo recursos comuns a todos os serviços on-line do Office 365, consulte [Descrição de serviço da plataforma Office 365](../office-365-platform-service-description/office-365-platform-service-description.md).
  
Para comprar o Arquivamento do Exchange Online, confira [Arquivamento do Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=314176).
  
Para comparar os recursos entre os planos, confira [Comparar planos do Office 365 for Business](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409).
  
> [!TIP]
> Você pode exportar, salvar e imprimir páginas nas Descrições de Serviço do Office 365. Saiba como [exportar várias páginas](https://go.microsoft.com/fwlink/?LinkId=403349). 
  
## <a name="exchange-online-archiving-plans"></a>Planos de Arquivamento do Exchange Online
<a name="bkmk_EOA_Plans"> </a>

Arquivamento do Exchange Online está disponível pelos planos a seguir.
  
|**Plano**|**Descrição**|
|:-----|:-----|
|**Arquivamento do Exchange Online para Exchange Server** <br/> |Arquivamento baseado em nuvem para usuários com caixas de correio primárias em Exchange Server 2013 ou Exchange 2010 (SP2 ou posterior).  <br/> Se quiser adicionar um arquivo baseado na nuvem a uma caixa de correio principal localizada em um servidor do Exchange no local, você precisa configurar uma implantação híbrida. Para saber mais sobre implantações híbridas, confira [Implantações híbridas do Exchange Server](https://technet.microsoft.com/library/jj200581%28v=exchg.150%29.aspx).  <br/> |
|**Arquivamento do Exchange Online para Exchange Server (via Enterprise CAL Suite)** <br/> |Arquivo morto baseado em nuvem para usuários com caixas de correio primárias no Exchange Server 2013 ou Exchange 2010 (SP2 ou posterior). Confira mais detalhes em [Resumo de Licenciamento - Licenciamento do Core CAL Suite e do Enterprise CAL Suite](https://go.microsoft.com/fwlink/p/?LinkId=314160).  <br/> |
|**Arquivamento do Exchange Online para Exchange Online** <br/> | Arquivamento baseado em nuvem e in-loco retenção como um complemento para os seguintes planos: <sup>1, 2</sup>,  <br/>  Plano 1 do Exchange Online  <br/>  Quiosque do Exchange Online  <br/>  Office 365 Business Essentials  <br/>  Office 365 Business Premium  <br/>  Office 365 Enterprise E1  <br/>  Office 365 Enterprise F1  <br/> > [!NOTE]> Os planos a seguir já incluem o arquivamento e não exigem arquivamento do Exchange Online como um complemento: > A1 de educação do Office 365 > A3 de educação do Office 365 > A5 de educação do Office 365 > Office 365 Enterprise E3 > Office 365 Enterprise E5 > Exchan GE Online plano 2 > para obter detalhes sobre os recursos de arquivamento de caixas de correio Exchange Online, consulte [Arquivar caixas de correio no Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404421).           |
   
> [!NOTE]
> <sup>1</sup> Uma implantação híbrida não é necessária para as organizações somente na nuvem, onde nenhuma caixa de correio está localizada em um servidor Exchange local. No entanto, se houver caixas de correio locais, será preciso uma implantação híbrida. > <sup>2</sup> Os planos do Plano 1 do Exchange Online e do Office 365 Business têm um [limite de tamanho na caixa de correio e no arquivo morto](https://go.microsoft.com/fwlink/?LinkId=330039). O complemento Arquivamento do Exchange Online para o Exchange Online adiciona arquivo morto baseado em nuvem ilimitado e [Retenção local e Retenção de litígio](compliance-and-security-features.md#in-place-hold-and-litigation-hold). 
  
Procurando informações sobre todos os planos do Office 365? O Office 365 está disponível em uma variedade de planos para atender melhor às necessidades da sua organização. Para saber mais sobre os diversos planos, inclusive opções de planos autônomos, e ver informações sobre como migrar de um plano para outro, confira [Opções de planos do Office 365](../office-365-platform-service-description/office-365-plan-options.md).
  
## <a name="requirements"></a>Requisitos
<a name="bkmk_EOA_Plans"> </a>

Para usar o Arquivamento do Exchange Online para o Exchange Server, as caixas de correio do usuário devem residir em Exchange Server 2013 ou Exchange Server 2010 (SP2 ou posterior).
  
### <a name="federated-identity-and-single-sign-on"></a>Identidade federada e logon único

Os administradores podem usar uma abordagem de logon único para autenticação do Office 365 com o Active Directory local. Para conseguir isso, os administradores podem configurar serviços de Federação do Active Directory no local — um serviço do Microsoft Windows Server® 2008 — para federar com o Microsoft Federation Gateway. Depois que os serviços de Federação do Active Directory são configurados, todos os usuários do Office 365, cujas identidades são baseadas no domínio federado podem usar seu logon corporativo existente para autenticar automaticamente para o Office 365.
  
### <a name="user-subscriptions"></a>Inscrições de usuário

Cada usuário que acessa o serviço do Arquivamento do Exchange Online deve ter uma assinatura do Arquivamento do Exchange Online. Cada assinatura de arquivo de email pode ser usada somente para armazenamento de um usuário de mensagens de dados.
  
## <a name="unlimited-archive-storage-quota"></a>Cota de armazenamento de arquivo morto ilimitada
<a name="bkmk_EOA_Plans"> </a>

 O recurso de arquivamento ilimitado no Office 365 (chamado arquivamento de expansão automática) fornece um volume ilimitado de armazenamento em caixas de correio de arquivo morto. Cada assinante do Arquivamento do Exchange Online recebe inicialmente 100 GB de armazenamento na caixa de correio de arquivo morto. Quando o arquivamento de expansão automática está ativado, o armazenamento adicional é incluído automaticamente quando é alcançada a capacidade de armazenamento de 100 GB. Confira mais informações em [Visão geral de arquivamento ilimitado no Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Saiba mais sobre disponibilidade em [Mapa do Office 365](http://go.microsoft.com/fwlink/?LinkId=509914). 
  
> [!IMPORTANT]
> Os administradores não podem ajustar a cota de armazenamento. 
  
> [!IMPORTANT]
> O uso em registro no diário, regras de transporte ou de encaminhamento automático para copiar mensagens para o Arquivamento do Exchange Online com a finalidade de arquivamento não é permitido. A caixa de correio de arquivo morto de um usuário destina-se somente a esse usuário. A Microsoft reserva o direito de negar o arquivamento ilimitado em situações onde a caixa de correio de arquivo morto do usuário é usada para armazenar dados de arquivo morto de outros usuários. 
  
## <a name="feature-availability-across-exchange-online-archiving-plans"></a>Disponibilidade de recursos nos planos do Arquivamento do Exchange Online
<a name="bkmk_EOA_Plans"> </a>

||||
|:-----|:-----|:-----|
|**Recurso** <br/> |**Arquivamento do Exchange Online para Exchange Server<sup>1</sup>**          <br/> |**Arquivamento do Exchange Online para Exchange Online<sup>2</sup>** <br/> |
|**[Recursos de arquivamento no Arquivamento do Exchange Online](archive-features.md)** <br/> |||
|Caixa de correio de arquivamento  <br/> |Sim  <br/> |Sim  <br/> |
|Mover mensagens usando a política de arquivamento  <br/> |Sim  <br/> |Sim  <br/> |
|Importar dados para o arquivamento  <br/> |Sim  <br/> |Sim  <br/> |
|Recuperação de itens excluídos  <br/> |Sim  <br/> |Sim  <br/> |
|Recuperação da caixa de correio excluída  <br/> |Sim  <br/> |Sim  <br/> |
|Backup da caixa de correio  <br/> |Sim  <br/> |Sim  <br/> |
|**[Recursos do cliente no arquivamento do Exchange Online](client-features.md)** <br/> |||
|Outlook<sup>3</sup> <br/> |Sim  <br/> |Sim  <br/> |
|Outlook Web App  <br/> |Sim  <br/> |Sim  <br/> |
|**[Conformidade e segurança recursos de Arquivamento do Exchange Online](compliance-and-security-features.md)** <br/> |||
|Diretivas de retenção  <br/> |Sim  <br/> |Sim  <br/> |
|Bloqueio In-loco e Retenção de Litígio<sup>6</sup> <br/> |Sim  <br/> |Sim  <br/> |
|Descoberta Eletrônica In-loco  <br/> |Sim  <br/> |Sim  <br/> |
|Criptografia entre servidores no local e o Arquivamento do Exchange Online  <br/> |Sim  <br/> |Sim  <br/> |
|Criptografia entre clientes e o Arquivamento do Exchange Online  <br/> |Sim  <br/> |Sim  <br/> |
|Criptografia: S/MIME e PGP  <br/> |Sim  <br/> |Sim  <br/> |
|IRM usando a Proteção de Informações do Azure  <br/> |Não  <br/> |Nenhum<sup>4</sup> <br/> |
|IRM usando Windows Server AD RMS  <br/> |Sim<sup>5</sup> <br/> |Sim<sup>5</sup> <br/> |
|Auditoria  <br/> |Sim  <br/> |Sim  <br/> |
   

> <sup>1</sup> As caixas de correio do usuário devem residir no Exchange 2010 SP2 ou posterior.
 <br/><sup>2</sup> um arquivo morto de In-loco só pode ser usado para arquivar o email para um único usuário ou a entidade para a qual uma licença tiver sido aplicada. Usando um arquivamento In-loco como um meio para armazenar os emails de vários usuários ou entidades é proibido. Por exemplo, os administradores de TI não é possível criar caixas de correio compartilhadas e ter usuários copiar (através do campo Cc ou Cco, ou por meio de uma regra de transporte) uma caixa de correio compartilhada o objetivo explícitas de arquivamento. <br/> <sup>3</sup> para obter uma lista de versões suportadas do Microsoft Outlook, consulte [Recursos do cliente no arquivamento do Exchange Online](client-features.md). 
 <br/><sup>4</sup> azure Information Protection não for incluído, mas pode ser adquirido como um complemento separado e habilitará os recursos de gerenciamento de direitos de informação (IRM) compatíveis. Alguns recursos de proteção de informações do Azure exigem uma assinatura para o Office 365 ProPlus, que não está incluído no Office 365 Business Essentials, Business Premium do Office 365, Office 365 Enterprise E1, educação do Office 365 ou F1 do Office 365 Enterprise. <br/><sup>5</sup> O AD RMS para Windows Server é um servidor local que precisa ser adquirido e gerenciado separadamente de forma a permitir os recursos de IRM com suporte. 
 <br/><sup>6</sup> Ao colocar uma caixa de correio em Bloqueio In-loco e Retenção de Litígio, a retenção é aplicada à caixa de correio primária e à caixa de correio de arquivo morto. 