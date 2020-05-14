---
title: Descrição do serviço do Exchange Online Protection
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: Obter informações sobre recursos e requisitos para o Exchange Online Protection. Incluído é uma lista de planos que fornecem proteção do Exchange Online, bem como uma comparação de recursos entre esses planos.
ms.openlocfilehash: 661d2359d53fe740c5217aaecaf2f86e5f741d5c
ms.sourcegitcommit: 5716c242365d632aec3d06bd090184481b2c3f9c
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/14/2020
ms.locfileid: "44226200"
---
# <a name="exchange-online-protection-service-description"></a>Descrição do serviço do Exchange Online Protection

Obter informações sobre recursos e requisitos para o Exchange Online Protection. Incluído é uma lista de planos que fornecem proteção do Exchange Online, bem como uma comparação de recursos entre esses planos.

O Microsoft Proteção do Exchange Online (EOP) é um serviço de filtragem de e-mails baseado na nuvem que ajuda a proteger sua organização contra spam e malware, e inclui recursos para defender sua organização das violações da política de mensagens. O EOP pode simplificar o gerenciamento de seu ambiente de mensagem e reduzir muitos dos problemas que surgem na manutenção do hardware e do software locais.

A lista a seguir descreve as principais maneiras de usar o EOP para proteção de mensagens:

- **Em um cenário autônomo: o**EOP fornece proteção de email baseada em nuvem para seu ambiente de email local (Exchange Server ou outras soluções de email SMTP no local).

- **Como parte do Microsoft Exchange Online**: por padrão, o EOP protege caixas de correio hospedadas na nuvem do Exchange Online. Para saber mais sobre o Exchange Online, confira a [Descrição de serviço do Exchange Online](../exchange-online-service-description/exchange-online-service-description.md).

- **Em uma implantação híbrida: o**EOP pode ser configurado para proteger seu ambiente de mensagens e controlar o roteamento de email quando você tem uma combinação de caixas de correio locais e em nuvem.

Para comparar recursos entre planos, consulte [poderosas ferramentas para dar suporte à sua empresa](https://products.office.com/business/compare-more-office-365-for-business-plans).

Para comprar o Proteção do Exchange Online, confira [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).

> [!NOTE]
> EOP substituiu o Forefront Online Protection for Exchange (FOPE). Todos os clientes do FOPE foram migrados para o EOP.

## <a name="whats-new-in-exchange-online-protection-eop"></a>Novidades no Exchange Online Protection (EOP)

O [Microsoft 365 Roadmap](https://office.microsoft.com/products/office-365-roadmap-FX104343353.aspx) é um bom recurso para encontrar informações sobre os novos recursos do futuro.

## <a name="exchange-online-protection-eop-plans"></a>Planos do Exchange Online Protection (EOP)

O EOP está disponível nos seguintes planos de assinatura:

|**Plano**|**Descrição**|
|:-----|:-----|
|[EOP autônomo](https://products.office.com/exchange/exchange-email-security-spam-protection)|Um serviço separado baseado em nuvem que protege sua organização de email local.|
|[Recursos do EOP no Exchange Online](https://products.office.com/exchange/compare-microsoft-exchange-online-plans)|A proteção interna para suas caixas de correio hospedadas na nuvem do Exchange Online.|
|[Exchange Enterprise CAL com Serviços](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)|Licenças de complemento adquiridas para sua organização do Exchange local que incluem o EOP e outros recursos baseados em nuvem (consulte a próxima seção para obter detalhes).|

### <a name="exchange-enterprise-cal-with-services-features"></a>Recursos do Exchange Enterprise CAL com Serviços

O Microsoft Exchange Enterprise CAL com serviços fornece os recursos de proteção de email do EOP e os seguintes recursos adicionais baseados em nuvem:

- [Prevenção de perda de dados (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)

- [Criar relatórios usando serviços Web](reporting-and-message-trace.md#reporting-using-web-services)

Para obter mais informações sobre o licenciamento do Exchange Enterprise CAL com serviços, confira [perguntas frequentes sobre licenciamento do Exchange](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business).

Se você tiver licenças do Exchange Enterprise CAL com serviços e quiser provisionar o EOP, siga as instruções em [Configure Your EOP Service](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-your-eop-service). As etapas de configuração são as mesmas para a configuração do EOP autônomo.

> [!NOTE]
> Novos recursos do Exchange Enterprise CAL com Serviços são implantados ao mesmo tempo que o Exchange Online, não que o EOP autônomo. Esteja ciente de que os cronogramas de implantação para o EOP autônomo e o Exchange Online/Exchange Enterprise CAL com Serviços podem ser ligeiramente diferentes.

## <a name="requirements-for-exchange-online-protection-eop"></a>Requisitos para o Exchange Online Protection (EOP)

O EOP pode ser usado com qualquer agente de transferência de email SMTP, como o Microsoft Exchange Server. Para obter informações sobre os sistemas operacionais, navegadores da Web e idiomas suportados pelo EOP, consulte as seções "Navegadores suportados" e "idiomas com suporte" no [centro de administração do Exchange no Exchange Online Protection](https://docs.microsoft.com/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop).

## <a name="limits"></a>Limites

Para limites no EOP, consulte [limites do Exchange Online Protection](exchange-online-protection-limits.md).

## <a name="feature-availability-across-exchange-online-protection-eop-plans"></a>Disponibilidade de recursos nos planos da Proteção do Exchange Online (EOP)

Cada recurso é listado abaixo. Para obter informações mais detalhadas sobre os recursos EOP, clique nos links na tabela. Quando o Exchange Online é mencionado, normalmente se refere à família de serviços do Office 365 Enterprise.

|||||
|:-----|:-----|:-----|:-----|
|**Recurso**|**EOP autônomo**|**Recursos do EOP no <br/> Exchange Online**|**Exchange Enterprise <br/> Cal com serviços**|
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
|[Suplemento de mensagem de relatório para o Outlook](https://docs.microsoft.com/microsoft-365/security/office-365-security/enable-the-report-message-add-in)|Sim|Sim|Sim|
|[Relatórios de lixo eletrônico no Outlook na Web](https://docs.microsoft.com/microsoft-365/security/office-365-security/report-junk-email-and-phishing-scams-in-outlook-on-the-web-eop)|Sim|Sim|Sim|
|[Rotear email entre a Microsoft e seus próprios servidores de email](mail-flow-eop.md#routing-email-between-microsoft-and-your-own-email-servers)|Sim|Sim|Sim|
|[Mensagens seguras com um parceiro confiável](mail-flow-eop.md#secure-messaging-with-a-trusted-partner)|Sim|Sim|Sim|
|[Lista segura de endereço IP de um parceiro](mail-flow-eop.md#safe-listing-a-partners-ip-address)|Sim|Sim|Sim|
|[Roteamento de email condicional](mail-flow-eop.md#conditional-mail-routing)|Sim|Sim|Sim|
|[Roteamento híbrido de email](mail-flow-eop.md#hybrid-mail-routing)|Sim|Sim|Sim|
|[Relatórios do centro de administração do Microsoft 365](reporting-and-message-trace.md#microsoft-365-admin-center-reports)<br/> |Sim<sup>9</sup>|Sim<sup>10</sup>|Sim <sup>9, 10</sup>|
|[Criar relatórios usando serviços Web](reporting-and-message-trace.md#reporting-using-web-services)|Não|Sim|Sim|
|[Rastreamento de mensagens](reporting-and-message-trace.md#message-trace)|Sim<sup>15</sup>|Sim<sup>15</sup>|Sim|
|[Acesso ao centro de administração do Microsoft 365](administration-and-management-eop.md#access-to-the-microsoft-365-admin-center)|Sim|Sim|Sim|
|[Acesso ao centro de administração do Exchange](administration-and-management-eop.md#access-to-the-exchange-admin-center (EAC))|Sim|Sim|Sim|
|[Remote Windows PowerShell access](administration-and-management-eop.md#remote-windows-powershell-access)|Sim|Sim|Sim|

<sup>1</sup> Os usuários de email são definidos como "Caixas de Correio" e, juntamente com os contatos externos de email, podem ser adicionados, removidos e gerenciados diretamente no Centro de administração do Exchange (EAC). <br/>
<sup>2</sup> Sem personalização de RBAC. Apenas funções de administrador. <br/>
<sup>3</sup> Os domínios gerenciados podem ser visualizados e os tipos de domínio podem ser editados no EAC. Todos os outros gerenciamento de domínio devem ser feitos no centro de administração do Microsoft 365.<br/>
<sup>4</sup> as regras de fluxo de emails (também conhecidas como regras de transporte) no EOP são descritas em [regras de fluxo de emails (regras de transporte) no Exchange Online Protection](https://docs.microsoft.com/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0). As condições, exceções e ações da regra de fluxo de emails diferem levemente entre o EOP e o Exchange Online. Essas diferenças são observadas nas [condições e exceções de regra de fluxo de emails (predicados) no Exchange Online](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions) e [ações de regra de fluxo de email no Exchange Online](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions).<br/>
<sup>5</sup> Os relatórios de auditoria do EOP são um subconjunto dos relatórios de auditoria do Exchange Online que excluem informações sobre caixas de correio. <br/>
<sup>6</sup> Dicas de política de DLP não estão disponíveis para clientes do Exchange Enterprise CAL com Serviços.  <br/>
<sup>7</sup> A ação padrão do filtro de conteúdo é mover as mensagens de spam para a pasta Lixo Eletrônico do destinatário. Para que isso funcione com caixas de correio locais do Exchange, você também precisa configurar duas regras de transporte em sua organização do Exchange local para detectar os cabeçalhos de spam adicionados pelo EOP. Para obter mais informações, consulte [Configurar o EOP autônomo para entregar spam à pasta lixo eletrônico em ambientes híbridos](https://docs.microsoft.com/microsoft-365/security/office-365-security/ensure-that-spam-is-routed-to-each-user-s-junk-email-folder). <br/>
<sup>9</sup> Os relatórios do EOP são um subconjunto dos relatórios do Exchange Online que excluem informações sobre caixas de correio.<br/>
<sup>10</sup> Inclui relatórios de DLP. <br/>
<sup>12</sup> suportado para clientes locais que compram a proteção de informações do Azure e usem o Exchange Online Protection para rotear emails pelo Exchange Online. <br/>
<sup>13</sup> Examina as mensagens de entrada e saída, mas não verifica as mensagens internas enviadas de um remetente em sua organização para um destinatário em sua organização. <br/>
<sup>15</sup> A configuração híbrida não está disponível por meio do Assistente Híbrido, mas poderá ser configurada manualmente se você tiver o Exchange SP1.
