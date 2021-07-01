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
description: Obter informações sobre recursos e requisitos para o Exchange Online Protection. Incluído está uma lista de planos que fornecem Proteção do Exchange Online, bem como uma comparação de recursos entre esses planos.
ms.openlocfilehash: fbfbe39931e6037b358bb76c124937904a408783
ms.sourcegitcommit: 427dbb27426a12e8c5dba7d8b4cbaf2bedb3aaba
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/30/2021
ms.locfileid: "53222478"
---
# <a name="exchange-online-protection-service-description"></a>Descrição do serviço do Exchange Online Protection

Obter informações sobre recursos e requisitos para o Exchange Online Protection. Incluído está uma lista de planos que fornecem Proteção do Exchange Online, bem como uma comparação de recursos entre esses planos.

Microsoft Exchange Online A Proteção (EOP) é um serviço de filtragem de email baseado em nuvem que ajuda a proteger sua organização contra spam e malware e inclui recursos para proteger sua organização contra violações de política de mensagens. A EOP pode simplificar o gerenciamento de seu ambiente de mensagem e reduzir muitos dos problemas que surgem na manutenção do hardware e do software locais.

A lista a seguir descreve as principais maneiras de usar o EOP para proteção de mensagens:

- **Em um** cenário autônomo: o EOP fornece proteção de email baseada em nuvem para seu ambiente de email local (Exchange Server ou outras soluções de email SMTP locais).

- **Como parte do Microsoft Exchange Online:** por padrão, o EOP protege Exchange Online caixas de correio hospedadas na nuvem. Para saber mais sobre Exchange Online, consulte Exchange Online [descrição do serviço.](../exchange-online-service-description/exchange-online-service-description.md)

- **Em uma implantação** híbrida : o EOP pode ser configurado para proteger seu ambiente de mensagens e controlar o roteamento de emails quando você tem uma combinação de caixas de correio locais e de nuvem.

## <a name="available-plans"></a>Planos disponíveis

A tabela a seguir mostra os planos que incluem Proteção do Exchange Online para que você possa escolher a solução que melhor atenda às necessidades da sua organização. Para obter informações detalhadas sobre o plano, [consulte Proteção do Exchange Online](https://products.office.com/exchange/exchange-email-security-spam-protection).

Para obter informações detalhadas sobre o plano sobre assinaturas que permitem usuários para Proteção do Exchange Online, consulte a [tabela de comparação de assinatura completa](https://www.microsoft.com/microsoft-365/compare-microsoft-365-enterprise-plans).

### <a name="exchange-enterprise-cal-with-services-features"></a>Recursos do Exchange Enterprise CAL com Serviços

O Microsoft Exchange Enterprise CAL com Serviços fornece os recursos de proteção de email do EOP e os seguintes recursos adicionais baseados em nuvem:

- [Prevenção contra perda de dados](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)

- [Criar relatórios usando serviços Web](reporting-and-message-trace.md#reporting-using-web-services)

Para obter mais informações sobre Exchange Enterprise cal com licenciamento de serviços, [consulte Exchange perguntas frequentes sobre licenciamento.](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)

Se você tiver Exchange Enterprise CAL com licenças de Serviços e quiser provisionar o EOP, siga as instruções em [Configurar seu serviço EOP](/microsoft-365/security/office-365-security/set-up-your-eop-service). As etapas de configuração são as mesmas para a configuração do EOP autônomo.

> [!NOTE]
> Novos recursos do Exchange Enterprise CAL com Serviços são implantados ao mesmo tempo que o Exchange Online, não que o EOP autônomo. Esteja ciente de que os cronogramas de implantação para o EOP autônomo e o Exchange Online/Exchange Enterprise CAL com Serviços podem ser ligeiramente diferentes.

## <a name="requirements-for-exchange-online-protection-eop"></a>Requisitos para o Exchange Online Protection (EOP)

O EOP pode ser usado com qualquer agente de transferência de email SMTP, como Microsoft Exchange Server. Para obter informações sobre os sistemas operacionais, navegadores da Web e idiomas suportados pelo EOP, consulte [as](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop)seções "Navegadores com suporte" e "Idiomas suportados" no centro de administração do Exchange em Proteção do Exchange Online .

## <a name="limits"></a>Limites

Para limites no EOP, consulte [Proteção do Exchange Online limites](exchange-online-protection-limits.md).

## <a name="feature-availability"></a>Disponibilidade de recursos

A tabela a seguir lista os principais recursos Proteção do Exchange Online disponíveis nos planos. Algumas advertências se aplicam. Veja as notas de rodapé para mais informações. Esta tabela pode ser alterada sem aviso prévio. Para a lista mais atualizada e completa de recursos, consulte [Ferramentas poderosas para dar suporte à sua empresa.](https://products.office.com/business/compare-more-office-365-for-business-plans)

| Recurso | EOP autônomo | EOP em EE CAL w/ Services | Recursos do EOP no Exchange Online |
|:-----|:-----|:-----|:-----|
|**Protection**||||
|Políticas anti-malware (internas e personalizadas)|Sim|Sim|Sim|
|Políticas anti-spam de entrada (internas e personalizadas)|Sim|Sim|Sim|
|Políticas anti-spam de saída (internas e personalizadas)|Sim|Sim|Sim|
|Filtragem de conexão (lista de ip allow e lista de bloqueios de IP)|Sim|Sim|Sim|
|Políticas anti-phishing (internas e personalizadas)|Sim|Sim|Sim|
|Proteção anti-spoofing (integrado e personalizado)|Sim|Sim|Sim|
|Limpeza automática zero hora (ZAP) para mensagens de malware, spam e phishing<sup>entregues 10</sup>|Não|Não|Sim|
|Predefinir políticas de segurança|Sim|Sim|Sim|
|Analisador de configuração para políticas de proteção|Sim|Sim|Sim|
|Lista de locatários que permitem/bloqueiam|Sim|Sim|Sim|
|Bloquear listas de envios de mensagens|Sim|Sim|Sim|
|Permitir listas para envios de mensagens|Sim|Sim|Sim|
|Bloqueio de borda|Sim|Sim|Sim|
|Bloqueio de Borda Baseado em Diretório (DBEB) para destinatários inexistentes|Sim|Sim|Sim|
|**Quarentena e envios**||||
|Envio de administrador<sup>10</sup>|Não|Não|Sim|
|Envio de usuário (caixa de correio personalizada)<sup>10</sup>|Não|Não|Sim|
|Quarentena de administrador|Sim|Sim|Sim|
|Quarentena do usuário final|Sim|Sim|Sim|
|Report Message add-in and Report Phishing add-in for Outlook|Sim|Sim|Sim|
|**Fluxo de mensagens**||||
|Regras de fluxo de emails (regras de transporte)<sup>4</sup>|Sim|Sim<sup>6</sup>|Sim|
|Domínios aceitos<sup>3</sup> |Sim|Sim|Sim|
|Conectores|Sim|Sim|Sim|
|Filtragem aprimorada para conectores (ignorar listagem)|Sim|Sim|Sim|
|**Monitoramento**||||
|Message trace|Sim|Sim|Sim|
|Relatórios de email e segurança no Centro de administração do Microsoft 365|Sim<sup>7</sup>|Sim<sup>7,8</sup>|Sim<sup>8</sup>|
|Relatórios de segurança no centro Microsoft 365 segurança|Sim<sup>7</sup>|Sim<sup>7,8</sup>|Sim<sup>8</sup>|
|Relatórios de email no EAC|Sim<sup>7</sup>|Sim<sup>7,8</sup>|Sim<sup>8</sup>|
|Log de auditoria de<sup>administrador 5</sup>|Sim|Sim|Sim|
|**Usuários** ||||
|Usuários de email e contatos de email<sup>1</sup>|Sim|Sim|Sim|
|Caixas de correio|Não|Não|Sim<sup>1a</sup>|
|Controle de acesso baseado em função (RBAC)<sup>2</sup>|Sim|Sim|Sim|
|**Conformidade**||||
|Prevenção contra perda de dados para email|Não|Sim|Sim|
|Criptografia de Mensagem do Office 365|Não<sup>9</sup>|Não<sup>9</sup>|Sim|
|**Administração**||||
|Centro de administração do Microsoft 365|Sim|Sim|Sim|
|Centro de administração do Exchange|Sim|Sim|Sim|
|Centro de segurança do Microsoft 365|Sim|Sim|Sim|
|Standalone Proteção do Exchange Online PowerShell|Sim|Não|Não|
|PowerShell do Exchange Online|Não|Sim|Sim|

<sup>1</sup> Você cria, remove e edita usuários de email e contatos de email no EAC. <br/>
<sup>1a</sup> Você cria e remove caixas de correio no Centro de administração do Microsoft 365. Você pode editar caixas de correio existentes no EAC. <br/>
<sup>2</sup> No EOP autônomo e EE CAL com Serviços, não há funções de usuário final ou políticas de atribuição de função.<br/>
<sup>3</sup> Você adiciona e remove domínios no Centro de administração do Microsoft 365.  No EAC, você configura domínios como Autoritativo ou Não Autoritativo.<br/>
<sup>4</sup> Algumas condições de regra, exceções e ações não estão disponíveis no EOP autônomo ou no EOP em EE CAL com Serviços. Essas diferenças são claramente notadas no Exchange Online de regras de fluxo de emails. <br/>
<sup>5</sup> No EOP autônomo e EE CAL com Serviços:

- Os relatórios de auditoria de caixa de correio não estão disponíveis.
- O relatório do grupo de função de administrador e o relatório de log de auditoria de administrador são os únicos relatórios de auditoria de administrador no EAC.
- Exportação de log de auditoria disponível apenas por meio do PowerShell. <br/>

<sup>6 Dicas</sup> de política de DLP não estão disponíveis no EE CAL com Serviços. <br/>
<sup>7</sup> Relatórios no EOP autônomo e EE CAL com Serviços são um subconjunto de relatórios Exchange Online (relatórios que lidam com caixas de correio).<br/>
<sup>8</sup> Inclui relatórios DLP. <br/>
<sup>9</sup> Você pode comprar a Proteção de Informações do Azure como uma assinatura de complemento e usar o OME se configurar seu ambiente de email local para rotear emails de e para a Internet por meio do EOP. <br/>
<sup>10</sup> Esse recurso requer Exchange Online caixas de correio. <br/>

## <a name="learn-more"></a>Saiba mais

Para obter informações técnicas sobre Proteção do Exchange Online, confira os seguintes recursos:

O [Microsoft 365 é](https://office.microsoft.com/products/office-365-roadmap-FX104343353.aspx) um bom recurso para descobrir informações sobre os novos recursos futuros.

### <a name="licensing-terms"></a>Termos de licenciamento

Para os termos e condições de licenciamento de produtos e serviços adquiridos por meio dos Programas de Licenciamento por Volume Comercial da Microsoft, consulte o [Site de Termos do Produto](https://www.microsoft.com/licensing/terms/).

### <a name="messaging"></a>Mensagens

Para acompanhar as mudanças futuras, incluindo recursos novos e alterados, manutenções planejadas ou outros anúncios importantes, visite a Central de Mensagens. Para obter mais informações, consulte [Centro de mensagens](/microsoft-365/admin/manage/message-center).

### <a name="accessibility"></a>Acessibilidade

A Microsoft continua comprometida com a segurança dos seus dados e com a [acessibilidade](https://www.microsoft.com/trust-center/compliance/accessibility) de nossos serviços. Para obter mais informações, consulte a [Central de Confiabilidade da Microsoft](https://www.microsoft.com/trust-center) e a [Central de Acessibilidade do Office](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d).
