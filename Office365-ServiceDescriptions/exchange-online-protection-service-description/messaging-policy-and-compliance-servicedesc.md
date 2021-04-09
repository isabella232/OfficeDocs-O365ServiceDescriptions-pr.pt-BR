---
title: Política e conformidade de mensagens na Proteção do Exchange Online
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: Leia este artigo para saber mais sobre a política de mensagens e os recursos de conformidade no Microsoft Exchange Online Protection (EOP).
ms.openlocfilehash: 81228b13036e831df630cca6f27b4ad285705f29
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653343"
---
# <a name="messaging-policy-and-compliance-in-exchange-online-protection"></a>Política e conformidade de mensagens na Proteção do Exchange Online

Microsoft Exchange Online Protection (EOP) fornece recursos de política e conformidade de mensagens que podem ajudá-lo a gerenciar seus dados de email.

Você está procurando informações sobre todas as características EOP? Consulte a descrição [do serviço de Proteção do Exchange Online](exchange-online-protection-service-description.md).

## <a name="mail-flow-rules"></a>Regras do fluxo de email

As regras de fluxo de emails (também conhecidas como regras de transporte) oferecem flexibilidade para aplicar suas próprias políticas específicas da empresa ao email. As regras de fluxo de emails são feitas de critérios flexíveis, que permitem definir condições, exceções e ações a ser tomadas com base nos critérios. Para obter mais informações, consulte [Mail flow rules (transport rules) in Exchange Online Protection](/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0).

## <a name="audit-logging"></a>Registro em log de auditoria

O registro em log de auditoria permite que você controle as alterações específicas feitas pelos administradores em sua organização. Esses relatórios ajudam você a cumprir requisitos de regulamentações, conformidade e litígio. Para saber mais, veja [Relatórios de auditoria no EOP](/microsoft-365/security/office-365-security/auditing-reports-in-eop).

## <a name="data-loss-prevention-dlp"></a>Prevenção de perda de dados (DLP)

Não disponível para clientes autônomos do EOP. A Prevenção de Perda de Dados (DLP) ajuda a identificar, monitorar e proteger informações confidenciais de sua organização por meio de análise profunda de conteúdo. DLP é cada vez mais importante para sistemas de mensagens corporativos porque o email crucial para os negócios inclui dados confidenciais que precisam ser protegidos. O recurso DLP permite proteger dados confidenciais sem afetar a produtividade do trabalho.

Você pode configurar as políticas de DLP no EAC, que permitem:

- Iniciar com um modelo de política pré-configurado que pode ajudar a detectar tipos específicos de informações confidenciais, como dados PCI-DSS, dados do Gramm-Leach-Bliley Act ou até mesmo informações de identificação pessoal (PII) específicas de localidade.

- Use o poder total dos critérios e ações de regra de fluxo de emails existentes e adicione novas regras de fluxo de emails.

- Teste a eficácia das suas políticas de DLP antes de impô-las totalmente.

- Incorpore seus próprios modelos personalizados de política de DLP e tipos de informações confidenciais.

- Detectar informações confidenciais em anexos de mensagens, texto do corpo ou linhas de assunto e ajustar o nível de confiança em que o serviço age.

- Detecte dados confidenciais por meio de impressão digital do documento. A impressão digital de documento ajuda você a criar facilmente tipos de informações confidenciais personalizadas com base em formulários baseados em texto que você pode usar para definir regras de fluxo de emails e políticas de DLP.

- Adicione Dicas de Política, que podem ajudar a reduzir a perda de dados exibindo um aviso para os usuários do Outlook 2013, do Outlook na Web e do OWA para Dispositivos e também podem melhorar a eficácia de suas políticas permitindo relatórios falsos positivos.

- Revise os dados de incidentes em relatórios de DLP ou adicione seus próprios relatórios específicos usando uma ação de geração de relatórios de incidentes.

> [!NOTE]
> As políticas de DLP são aplicadas apenas ao email que entra ou sai da organização. Os emails intraorganizacionais (internos) não têm políticas de DLP aplicadas, a menos que você execute o Exchange Server 2013 com DLP local. Isso também se aplica às dicas de política de DLP, que informam aos usuários sobre possíveis violações de política antes que dados confidenciais sejam enviados por engano a destinatários não autorizados.

Para saber mais sobre DLP, consulte [Prevenção contra perda de dados no Exchange Online](/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention).

## <a name="office-365-message-encryption"></a>Criptografia de Mensagem do Office 365

A Criptografia de Mensagens do Office 365, parte da Proteção de Informações do Azure, é um serviço online que permite que os usuários de email enviem mensagens de email criptografadas para qualquer pessoa. Os clientes locais podem acessar a Criptografia de Mensagens do Office 365 comprando a Proteção de Informações do Azure e usando a Proteção do Exchange Online para configurar o fluxo de emails por meio do Exchange Online. Para saber mais sobre a Criptografia de Mensagens do Office 365 no Exchange Online, consulte Criptografia de Mensagens do [Office 365](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption) na descrição do serviço do Exchange Online.

## <a name="messaging-policy-and-compliance-features-across-eop-options"></a>Recursos de diretiva e conformidade de mensagens através de opções EOP

| Recurso | EOP autônomo | Recursos do EOP em <br/> Exchange Online | Exchange Enterprise <br/> CAL com Serviços |
|:-----|:-----|:-----|:-----|
|Regras do fluxo de email|Sim<sup>1</sup>|Sim<sup>1</sup>|Sim<sup>1, 3</sup>|
|Registro em log de auditoria|Sim<sup>2</sup>|Sim|Sim|
|Prevenção de perda de dados (DLP)|Não|Sim|Sim<sup>3</sup>|
|Criptografia de Mensagem do Office 365|Sim<sup>4</sup>|Sim|Sim<sup>4</sup>|

> [!NOTE]
> <sup>1</sup> As condições de regra de fluxo de emails disponíveis, exceções e ações diferem ligeiramente entre o EOP e o Exchange Online. Essas diferenças são notadas nas condições de regra de fluxo de email e exceções [(predicados)](/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions) no Exchange Online e ações de regra de fluxo de email [no Exchange Online](/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions). <br/>
> <sup>2</sup> Os relatórios de auditoria do EOP são um subconjunto dos relatórios de auditoria do Exchange Online que excluem informações sobre caixas de correio. <br/>
> <sup>3</sup> Dicas de política de DLP não estão disponíveis para clientes do Exchange Enterprise CAL com Serviços. <br/>
> <sup>4</sup> Suportado para clientes locais que compram o complemento da Proteção de Informações do Azure e usam a Proteção do Exchange Online para rotear emails pelo Exchange Online. Para a experiência da área de trabalho, além do complemento proteção de informações do Azure, os Aplicativos do Microsoft 365 para empresas precisam ser comprados. <br/>