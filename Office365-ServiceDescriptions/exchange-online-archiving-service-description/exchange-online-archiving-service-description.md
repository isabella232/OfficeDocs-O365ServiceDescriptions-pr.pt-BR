---
title: Descrição do serviço de arquivamento do Exchange Online
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-archiving-service-description
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 21ebd4bb-7d88-489f-a8aa-376e2536900c
description: Leia este artigo para saber mais sobre Microsoft Exchange Online Arquivamento.
ms.openlocfilehash: 5030c265b309641a0d69e79c1aa8942c45360550
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/24/2021
ms.locfileid: "59670682"
---
# <a name="exchange-online-archiving-service-description"></a>Descrição do serviço de arquivamento do Exchange Online

Microsoft Exchange Online O arquivamento é uma Microsoft 365 de arquivamento de classe corporativa baseada em nuvem para organizações que implantaram o Microsoft Exchange Server 2019, Microsoft Exchange Server 2016, Microsoft Exchange Server 2013, Microsoft Exchange Server 2010 (SP2 e posterior) ou assinar determinados planos Exchange Online ou Microsoft365. O Arquivamento do Exchange Online auxilia essas organizações com o seus competitivos arquivamento, conformidade, regulamentação, e eDiscovery ao mesmo tempo em que simplifica a infraestrutura no local e, desse modo, reduz custos e facilita os encargos de TI.
  
Como um serviço online da Microsoft, o Arquivamento do Exchange Online foi projetado para ajudar a atender à necessidade de segurança robusta, confiabilidade e produtividade do usuário. Para obter mais informações sobre Microsoft 365, incluindo recursos comuns a todos os serviços online da Microsoft, consulte Microsoft 365 descrição do serviço [Office 365 plataforma.](../office-365-platform-service-description/office-365-platform-service-description.md)
  
Para comprar Arquivamento do Exchange Online, consulte [Arquivamento do Exchange Online para servidor](https://products.office.com/exchange/microsoft-exchange-online-archiving-email).
  
## <a name="available-plans"></a>Planos disponíveis

Para obter informações detalhadas sobre o plano sobre assinaturas que permitem usuários para Arquivamento do Exchange Online, consulte a [tabela de comparação de assinatura completa](https://go.microsoft.com/fwlink/?linkid=2139145).
  
> [!TIP]
> Você pode exportar, salvar e imprimir páginas nas descrições do serviço. Saiba como exportar [resultados da pesquisa de conteúdo.](/office365/securitycompliance/export-search-results) 
  
## <a name="exchange-online-archiving-plans"></a>Planos de Arquivamento do Exchange Online

Arquivamento do Exchange Online está disponível pelos planos a seguir.<br><br>
  
| Planejar | Descrição |
|:-----|:-----|
|**Arquivamento do Exchange Online para Exchange Server** <br/> |Arquivo morto baseado em nuvem para usuários com caixas de correio primárias no Exchange Server 2019, Exchange Server 2016, Exchange Server 2013 ou Exchange 2010 (SP2 ou posterior). <br/> Se quiser adicionar um arquivo baseado na nuvem a uma caixa de correio principal localizada em um servidor do Exchange no local, você precisa configurar uma implantação híbrida. Para obter mais informações sobre implantações híbridas, [consulte Exchange Server implantações híbridas.](/exchange/exchange-hybrid) <br/> |
|**Arquivamento do Exchange Online para Exchange Server (via Enterprise CAL Suite)** <br/> |Arquivo morto baseado em nuvem para usuários com caixas de correio primárias no Exchange Server 2019, Exchange Server 2016, Exchange Server 2013 ou Exchange 2010 (SP2 ou posterior). Para obter detalhes, consulte [Client Access Licenses and Management Licenses](https://www.microsoft.com/licensing/product-licensing/client-access-license). <br/> |
|**Arquivamento do Exchange Online para Exchange Online** <br/> | Arquivamento baseado em nuvem e espera in-locar como complemento para os seguintes planos<sup>1,2,3</sup>:<br/> Exchange Online Plano 1 <br/> Quiosque do Exchange Online <br/> Microsoft 365 Business Basic <br/> Microsoft 365 Business Standard <br/> Microsoft 365 Business Premium <br/> Office 365 E1 <br/> Office 365 A1 <br/> Office 365 G1 <br/> Office 365 F3 <br/> Microsoft 365 F3<br/> <b>Observação:</b> Os planos a seguir já incluem arquivamento e não exigem Arquivamento do Exchange Online como complemento:<br/>Office 365 A3 <br/> Office 365 A5 <br/> Office 365 E3 <br/> Office 365 E5 <br/> Plano 2 do Exchange Online <br/>Microsoft 365 E3 <br/> Microsoft 365 E5 <br/> Microsoft 365 Conformidade com F5 <br/> Para obter detalhes sobre os recursos de arquivamento de Exchange Online caixas de correio, consulte [Archive features in Arquivamento do Exchange Online](./archive-features.md).|

<sup>1</sup> Uma implantação híbrida não é necessária para as organizações somente na nuvem, onde nenhuma caixa de correio está localizada em um servidor Exchange local. No entanto, se houver caixas de correio locais, será preciso uma implantação híbrida.
<br/>
<sup>2</sup> Exchange Online Plano 1, Office 365 E1/A1/G1 e Microsoft 365 Business Basic/Standard/Premium têm um limite de tamanho na caixa de correio e no arquivo morto. Para obter mais informações, confira [Limites do Exchange Online](../exchange-online-service-description/exchange-online-limits.md). O complemento Arquivamento do Exchange Online para o Exchange Online adiciona arquivo morto baseado em nuvem ilimitado e [Retenção local e Retenção de litígio](compliance-and-security-features.md#in-place-hold-and-litigation-hold).
<br/>
<sup>3</sup> Inclui planos GCC, GCC-High e DoD para o Governo dos EUA.

Procurando informações sobre todos os Microsoft 365 planos? Microsoft 365 está disponível em vários planos para atender melhor às necessidades da sua organização. Para obter informações sobre planos diferentes, incluindo opções de plano autônomo e informações sobre como mudar de um plano para outro, [consulte Office 365 opções de plano](../office-365-platform-service-description/office-365-plan-options.md).
  
## <a name="requirements"></a>Requisitos

Para usar Arquivamento do Exchange Online para Exchange Server, as caixas de correio de usuário devem residir no Exchange Server 2019, Exchange Server 2016, Exchange Server 2013 ou Exchange Server 2010 (SP2 ou posterior).
  
### <a name="federated-identity-and-single-sign-on"></a>Identidade federada e logon único

Os administradores podem usar uma abordagem de login único para autenticação com o Active Directory local. Para fazer isso, os administradores podem configurar os Serviços de Federação do Active Directory local, um serviço do Microsoft Windows Server &reg; 2008, para se federar com o Microsoft Federation Gateway. Depois que os Serviços de Federação do Active Directory são configurados, todos os usuários cujas identidades são baseadas no domínio federado podem usar seu logon corporativo existente para autenticar automaticamente para Office 365.
  
### <a name="user-subscriptions"></a>Inscrições de usuário

Cada usuário que acessa o serviço do Arquivamento do Exchange Online deve ter uma assinatura do Arquivamento do Exchange Online. Cada assinatura de arquivo de email pode ser usada somente para armazenamento de um usuário de mensagens de dados.
  
## <a name="unlimited-archive-storage-quota"></a>Cota de armazenamento de arquivo morto ilimitada

 O recurso de arquivamento ilimitado (chamado *de arquivamento com expansão automática*) fornece espaço de armazenamento adicional em caixas de correio de arquivo morto. Cada assinante do Arquivamento do Exchange Online recebe inicialmente 100 GB de armazenamento na caixa de correio de arquivo morto. Quando o arquivamento de expansão automática é ativado, o espaço de armazenamento adicional é adicionado automaticamente quando a capacidade de armazenamento de 100 GB é atingida. Em implantações híbridas do Exchange, o arquivamento de expansão automática só é suportado para caixas de correio de arquivo morto baseadas em nuvem quando a caixa de correio do usuário local reside no Exchange Server 2019, Exchange Server 2016 ou Exchange Server 2013 (SP1 ou posterior). Confira mais informações em [Visão geral do arquivamento ilimitado](/office365/securitycompliance/unlimited-archiving).
  
> [!IMPORTANT]
> Os administradores não podem ajustar a cota de armazenamento.<br/>
> O arquivamento de expansão automática não é suportado para caixas de correio residentes no Exchange Server 2010.
  
> [!IMPORTANT]
> O arquivamento de expansão automática só é suportado para caixas de correio usadas para usuários individuais ou caixas de correio compartilhadas com uma taxa de crescimento que não exceda *1 &nbsp; GB por dia.* O uso em registro no diário, regras de transporte ou de encaminhamento automático para copiar mensagens para o Arquivamento do Exchange Online com a finalidade de arquivamento não é permitido. A caixa de correio de arquivo morto de um usuário destina-se somente a esse usuário. A Microsoft reserva o direito de negar o arquivamento ilimitado em situações onde a caixa de correio de arquivo morto do usuário é usada para armazenar dados de arquivo morto de outros usuários.
  
## <a name="feature-availability-across-exchange-online-archiving-plans"></a>Disponibilidade de recursos nos planos do Arquivamento do Exchange Online

| Recurso | Arquivamento do Exchange Online para Exchange Server<sup>1</sup> | Arquivamento do Exchange Online para Exchange Online<sup>2</sup> |
|:-----|:-----|:-----|
|**[Recursos de arquivamento no Arquivamento do Exchange Online](archive-features.md)** <br/> |||
|Caixa de correio de arquivamento  <br/> |Sim  <br/> |Sim  <br/> |
|Mover mensagens usando a política de arquivo morto  <br/> |Sim  <br/> |Sim  <br/> |
|Importar dados para o arquivamento  <br/> |Sim  <br/> |Sim  <br/> |
|Recuperação de itens excluídos  <br/> |Sim  <br/> |Sim  <br/> |
|Recuperação da caixa de correio excluída  <br/> |Sim  <br/> |Sim  <br/> |
|Backup da caixa de correio  <br/> |Sim  <br/> |Sim  <br/> |
|**[Recursos do cliente em Arquivamento do Exchange Online](client-features.md)** <br/> |||
|Outlook<sup>3</sup> <br/> |Sim  <br/> |Sim  <br/> |
|Outlook na Web  <br/> |Sim  <br/> |Sim  <br/> |
|**[Recursos de conformidade e segurança em Arquivamento do Exchange Online](compliance-and-security-features.md)** <br/> |||
|Diretivas de retenção  <br/> |Sim  <br/> |Sim  <br/> |
|Bloqueio In-loco e Retenção de Litígio<sup>6</sup> <br/> |Sim  <br/> |Sim  <br/> |
|Descoberta Eletrônica In-loco  <br/> |Sim  <br/> |Sim  <br/> |
|Criptografia entre servidores no local e o Arquivamento do Exchange Online  <br/> |Sim  <br/> |Sim  <br/> |
|Criptografia entre clientes e o Arquivamento do Exchange Online  <br/> |Sim  <br/> |Sim  <br/> |
|Criptografia: S/MIME e PGP  <br/> |Sim  <br/> |Sim  <br/> |
|IRM usando a Proteção de Informações do Azure  <br/> |Não  <br/> |Não<sup>4</sup> <br/> |
|IRM usando Windows Server AD RMS  <br/> |Sim<sup>5</sup> <br/> |Sim<sup>5</sup> <br/> |
|Auditoria  <br/> |Sim  <br/> |Sim  <br/> |
   

<sup>1</sup> As caixas de correio do usuário devem residir no Exchange 2010 SP2 ou posterior.
<br/>
<sup>2</sup> Um In-Place arquivo morto só pode ser usado para arquivar emails para um único usuário ou entidade para o qual uma licença foi aplicada. É proibido o uso de um Arquivo-Morto no Local como meio de armazenamento de emails de vários usuários ou entidades. Por exemplo, os administradores de TI não podem criar caixas de correio compartilhadas e fazer com que os usuários copiem (com o campo Cc ou Cco ou com uma regra de transporte) uma caixa de correio compartilhada explicitamente para o arquivamento. <br/> 
<sup>3 Para</sup> ver uma lista de versões com suporte da Microsoft Outlook, consulte [Recursos do cliente em Arquivamento do Exchange Online](client-features.md). <br/>
<sup>4</sup> A Proteção de Informações do Azure não está incluída, mas pode ser comprada como um complemento separado e habilita os recursos de IRM (Gerenciamento de Direitos de Informação) com suporte. Alguns recursos da Proteção de Informações do Azure exigem uma assinatura para o Microsoft 365 Apps para Grandes Empresas, que não está incluído no Microsoft 365 Business Basic, Microsoft 365 Business Standard, Office 365 Enterprise E1, Office 365 Education ou Office 365 Enterprise F3. <br/>
<sup>5</sup> O AD RMS para Windows Server é um servidor local que precisa ser adquirido e gerenciado separadamente de forma a permitir os recursos de IRM com suporte. <br/>
<sup>6</sup> Ao colocar uma caixa de correio em Bloqueio In-loco e Retenção de Litígio, a retenção é aplicada à caixa de correio primária e à caixa de correio de arquivo morto.