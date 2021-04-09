---
title: Descrição do serviço do Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: Obter informações sobre recursos e requisitos para o Exchange Online Protection. Incluído está uma lista de planos que fornecem a Proteção do Exchange Online, bem como uma comparação de recursos entre esses planos.
ms.openlocfilehash: 172e07db12590e51720c2446974418244f3234e4
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653033"
---
# <a name="exchange-online-protection-service-description"></a>Descrição do serviço do Exchange Online Protection

Obter informações sobre recursos e requisitos para o Exchange Online Protection. Incluído está uma lista de planos que fornecem a Proteção do Exchange Online, bem como uma comparação de recursos entre esses planos.

O Microsoft Proteção do Exchange Online (EOP) é um serviço de filtragem de e-mails baseado na nuvem que ajuda a proteger sua organização contra spam e malware, e inclui recursos para defender sua organização das violações da política de mensagens. O EOP pode simplificar o gerenciamento de seu ambiente de mensagem e reduzir muitos dos problemas que surgem na manutenção do hardware e do software locais.

A lista a seguir descreve as principais maneiras de usar o EOP para proteção de mensagens:

- **Em um** cenário autônomo: o EOP fornece proteção de email baseada em nuvem para seu ambiente de email local (Exchange Server ou outras soluções de email SMTP locais).

- **Como parte do Microsoft Exchange Online**: Por padrão, o EOP protege caixas de correio hospedadas na nuvem do Exchange Online. Para saber mais sobre o Exchange Online, consulte a descrição [do serviço do Exchange Online.](../exchange-online-service-description/exchange-online-service-description.md)

- **Em uma implantação** híbrida : o EOP pode ser configurado para proteger seu ambiente de mensagens e controlar o roteamento de emails quando você tem uma combinação de caixas de correio locais e de nuvem.

## <a name="available-plans"></a>Planos disponíveis

Para obter informações detalhadas sobre o plano sobre assinaturas que permitem usuários para a Proteção do Exchange Online, consulte a [tabela de comparação de assinatura completa](https://go.microsoft.com/fwlink/?linkid=2139145).

Para comprar o Proteção do Exchange Online, confira [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).

> [!NOTE]
> O EOP substituiu o Forefront Online Protection for Exchange (FOPE). Todos os clientes do FOPE foram transitivos para o EOP.

## <a name="whats-new-in-exchange-online-protection-eop"></a>Novidades no Exchange Online Protection (EOP)

O [roteiro do Microsoft 365](https://office.microsoft.com/products/office-365-roadmap-FX104343353.aspx) é um bom recurso para descobrir informações sobre os novos recursos futuros.

## <a name="exchange-online-protection-eop-plans"></a>Planos do Exchange Online Protection (EOP)

O EOP está disponível nos seguintes planos de assinatura:<br><br>

| Planejar | Descrição |
|:-----|:-----|
|[EOP autônomo](https://products.office.com/exchange/exchange-email-security-spam-protection)|Um serviço separado baseado em nuvem que protege sua organização de email local.|
|[Recursos do EOP no Exchange Online](https://products.office.com/exchange/compare-microsoft-exchange-online-plans)|A proteção interna para suas caixas de correio hospedadas na nuvem do Exchange Online.|
|[Exchange Enterprise CAL com Serviços](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)|Licenças de complemento que você compra para sua organização local do Exchange que incluem o EOP e outros recursos baseados em nuvem (consulte a próxima seção para obter detalhes).|

### <a name="exchange-enterprise-cal-with-services-features"></a>Recursos do Exchange Enterprise CAL com Serviços

O Microsoft Exchange Enterprise CAL com Serviços fornece os recursos de proteção de email do EOP e os seguintes recursos adicionais baseados em nuvem:

- [Prevenção de perda de dados (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)

- [Criar relatórios usando serviços Web](reporting-and-message-trace.md#reporting-using-web-services)

Para obter mais informações sobre o licenciamento do Exchange Enterprise CAL com Serviços, consulte [Perguntas frequentes sobre licenciamento do Exchange.](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)

Se você tiver licenças do Exchange Enterprise CAL com Serviços e quiser provisionar o EOP, siga as instruções em [Configurar seu serviço EOP](/microsoft-365/security/office-365-security/set-up-your-eop-service). As etapas de configuração são as mesmas para a configuração do EOP autônomo.

> [!NOTE]
> Novos recursos do Exchange Enterprise CAL com Serviços são implantados ao mesmo tempo que o Exchange Online, não que o EOP autônomo. Esteja ciente de que os cronogramas de implantação para o EOP autônomo e o Exchange Online/Exchange Enterprise CAL com Serviços podem ser ligeiramente diferentes.

## <a name="requirements-for-exchange-online-protection-eop"></a>Requisitos para o Exchange Online Protection (EOP)

O EOP pode ser usado com qualquer agente de transferência de email SMTP, como Microsoft Exchange Server. Para obter informações sobre os sistemas operacionais, navegadores da Web e idiomas suportados pelo EOP, consulte as seções "Navegadores com suporte" e "Idiomas com suporte" no Centro de administração do Exchange na Proteção do [Exchange Online.](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop)

## <a name="limits"></a>Limites

Para limites no EOP, consulte [Limites da Proteção do Exchange Online.](exchange-online-protection-limits.md)

## <a name="feature-availability-across-exchange-online-protection-eop-plans"></a>Disponibilidade de recursos nos planos da Proteção do Exchange Online (EOP)

Cada recurso é listado abaixo. Para obter informações mais detalhadas sobre os recursos EOP, clique nos links na tabela. Quando o Exchange Online é mencionado, normalmente se refere à família de serviços do Office 365 Enterprise.<br><br>

| Recurso | EOP autônomo | Recursos do EOP no Exchange Online | Exchange Enterprise CAL com Serviços|
|:-----|:-----|:-----|:-----|
|[Destinatários de email](recipient-domain-and-company-management.md#mail-recipients)|Sim<sup>1</sup>|Sim<sup>1</sup>|Sim|
|[Permissões do grupo de funções de administrador](recipient-domain-and-company-management.md#admin-role-group-permissions)|Sim<sup>2</sup>|Sim|Sim|
|[Gerenciamento de domínio](recipient-domain-and-company-management.md#domain-management)|Sim<sup>3</sup>|Sim<sup>3</sup>|Sim<sup>3</sup>|
|[Corresponder subdomínios](recipient-domain-and-company-management.md#match-subdomains)|Sim|Sim|Não|
|[Bloqueio de borda baseado em diretório (DBEB)](recipient-domain-and-company-management.md#directory-based-edge-blocking-dbeb)|Sim|Sim|Sim|
|[Regras de fluxo de emails](../exchange-online-service-description/message-policy-and-compliance.md#mail-flow-rules)|Sim<sup>4</sup>|Sim<sup>4, 6</sup>|Sim|
|[Registro em log de auditoria](messaging-policy-and-compliance-servicedesc.md#audit-logging)|Sim<sup>5</sup>|Sim|Sim|
|[Prevenção de perda de dados (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)|Não|Sim|Sim<sup>6</sup>|
|[Criptografia de mensagem do Office 365](messaging-policy-and-compliance-servicedesc.md#office-365-message-encryption)|Sim<sup>12</sup>|Sim|Sim<sup>12</sup>|
|[Proteção antispam](anti-spam-and-anti-malware-protection-eop.md#anti-spam-protection) (integrado)|Sim|Sim|Sim|
|[Personalize as diretrizes contra spam](anti-spam-and-anti-malware-protection-eop.md#customize-anti-spam-policies)|Sim<sup>7</sup>|Sim|Sim|
|[Proteção antimalware](anti-spam-and-anti-malware-protection-eop.md#anti-malware-protection) (integrado)|Sim<sup>13</sup>|Sim|Sim|
|[Personalize as diretrizes contra malware](anti-spam-and-anti-malware-protection-eop.md#customize-anti-malware-policies)|Sim|Sim|Sim|
|[Quarentena](anti-spam-and-anti-malware-protection-eop.md#quarantine): gerenciamento do administrador|Sim|Sim|Sim|
|[Quarentena](anti-spam-and-anti-malware-protection-eop.md#quarantine): autogerenciamento de usuário final|Sim|Sim|Sim|
|[Envio](anti-spam-and-anti-malware-protection-eop.md#report-messages-to-microsoft-for-analysis)|Não|Sim|Não|
|[Report Message add-in for Outlook](/microsoft-365/security/office-365-security/enable-the-report-message-add-in)|Sim|Sim|Sim|
|[Relatório de lixo eletrônico no Outlook na Web](/microsoft-365/security/office-365-security/report-junk-email-and-phishing-scams-in-outlook-on-the-web-eop)|Sim|Sim|Sim|
|[Roteamento de emails entre a Microsoft e seus próprios servidores de email](mail-flow-eop.md#routing-email-between-microsoft-and-your-own-email-servers)|Sim|Sim|Sim|
|[Mensagens seguras com um parceiro confiável](mail-flow-eop.md#secure-messaging-with-a-trusted-partner)|Sim|Sim|Sim|
|[Lista segura de endereço IP de um parceiro](mail-flow-eop.md#safe-listing-a-partners-ip-address)|Sim|Sim|Sim|
|[Roteamento de email condicional](mail-flow-eop.md#conditional-mail-routing)|Sim|Sim|Sim|
|[Roteamento híbrido de email](mail-flow-eop.md#hybrid-mail-routing)|Sim|Sim|Sim|
|[Relatórios do Centro de administração do Microsoft 365](reporting-and-message-trace.md#microsoft-365-admin-center-reports)<br/> |Sim<sup>9</sup>|Sim<sup>10</sup>|Sim <sup>9, 10</sup>|
|[Criar relatórios usando serviços Web](reporting-and-message-trace.md#reporting-using-web-services)|Não|Sim|Sim|
|[Rastreamento de mensagens](reporting-and-message-trace.md#message-trace)|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim|
|[Acesso ao centro de administração do Microsoft 365](administration-and-management-eop.md#access-to-the-microsoft-365-admin-center)|Sim|Sim|Sim|
|[Acesso ao centro de administração do Exchange](administration-and-management-eop.md#access-to-the-exchange-admin-center (EAC))|Sim|Sim|Sim|
|[Remote Windows PowerShell access](administration-and-management-eop.md#remote-windows-powershell-access)|Sim|Sim|Sim|

<sup>1</sup> Os usuários de email são definidos como "Caixas de Correio" e, juntamente com os contatos externos de email, podem ser adicionados, removidos e gerenciados diretamente no Centro de administração do Exchange (EAC). <br/>
<sup>2</sup> Sem personalização de RBAC. Apenas funções de administrador. <br/>
<sup>3</sup> Os domínios gerenciados podem ser visualizados e os tipos de domínio podem ser editados no EAC. Todos os outros gerenciamentos de domínio devem ser feitos no Centro de administração do Microsoft 365.<br/>
<sup>4</sup> As regras de fluxo de email (também conhecidas como regras de transporte) no EOP são descritas em Regras de fluxo de emails (regras de [transporte) na Proteção do Exchange Online.](/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0) As condições de regra de fluxo de emails disponíveis, exceções e ações diferem ligeiramente entre o EOP e o Exchange Online. Essas diferenças são notadas nas condições de regra de fluxo de email e exceções [(predicados)](/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions) no Exchange Online e ações de regra de fluxo de email [no Exchange Online](/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions).<br/>
<sup>5</sup> Os relatórios de auditoria do EOP são um subconjunto dos relatórios de auditoria do Exchange Online que excluem informações sobre caixas de correio. <br/>
<sup>6</sup> Dicas de política de DLP não estão disponíveis para clientes do Exchange Enterprise CAL com Serviços.  <br/>
<sup>7</sup> A ação padrão do filtro de conteúdo é mover as mensagens de spam para a pasta Lixo Eletrônico do destinatário. Para que isso funcione com caixas de correio locais do Exchange, você também precisa configurar duas regras de transporte em sua organização local do Exchange para detectar os headers de spam adicionados pelo EOP. Para obter mais informações, consulte [Configure standalone EOP to deliver spam to the Junk Email folder in hybrid environments](/microsoft-365/security/office-365-security/ensure-that-spam-is-routed-to-each-user-s-junk-email-folder). <br/>
<sup>9</sup> Os relatórios do EOP são um subconjunto dos relatórios do Exchange Online que excluem informações sobre caixas de correio.<br/>
<sup>10</sup> Inclui relatórios de DLP. <br/>
<sup>12</sup> Suportado para clientes locais que compram a Proteção de Informações do Azure e usam a Proteção de Informações do Exchange Online para rotear emails pelo Exchange Online. <br/>
<sup>13</sup> Examina as mensagens de entrada e saída, mas não verifica as mensagens internas enviadas de um remetente em sua organização para um destinatário em sua organização. <br/>
<sup>15</sup> A configuração híbrida não está disponível por meio do Assistente Híbrido, mas poderá ser configurada manualmente se você tiver o Exchange SP1.