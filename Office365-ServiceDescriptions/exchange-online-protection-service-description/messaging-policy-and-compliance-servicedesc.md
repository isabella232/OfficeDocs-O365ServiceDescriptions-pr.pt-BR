---
title: Política de mensagens e conformidade no Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: Leia este artigo para saber mais sobre os recursos de política e conformidade de mensagens no Microsoft Exchange Online Protection (EOP).
ms.openlocfilehash: 0609c1fe48404035907096eb047e3947a1bf7ace
ms.sourcegitcommit: e342174df76128430dfc8c971716da5c4b2942ac
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/28/2020
ms.locfileid: "48293797"
---
# <a name="messaging-policy-and-compliance-in-exchange-online-protection"></a>Política de mensagens e conformidade no Exchange Online Protection

O Microsoft proteção do Exchange Online (EOP) oferece recursos de política e conformidade de mensagens que podem ajudar você a gerenciar seus dados de email.

Você está procurando informações sobre todas as características EOP? Consulte a [Descrição do serviço de proteção do Exchange Online](exchange-online-protection-service-description.md).

## <a name="mail-flow-rules"></a>Regras do fluxo de email

As regras de fluxo de emails (também conhecidas como regras de transporte) fornecem a flexibilidade para aplicar suas próprias políticas específicas da empresa ao email. As regras de fluxo de email são formadas por critérios flexíveis, que permitem definir condições, exceções e ações a serem tomadas com base nos critérios. Para obter mais informações, consulte [regras de fluxo de emails (regras de transporte) no Exchange Online Protection](https://docs.microsoft.com/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0).

## <a name="audit-logging"></a>Registro em log de auditoria

O registro em log de auditoria permite que você controle as alterações específicas feitas pelos administradores em sua organização. Esses relatórios ajudam você a cumprir requisitos de regulamentações, conformidade e litígio. Para saber mais, veja [Relatórios de auditoria no EOP](https://docs.microsoft.com/microsoft-365/security/office-365-security/auditing-reports-in-eop).

## <a name="data-loss-prevention-dlp"></a>Prevenção de perda de dados (DLP)

Não disponível para clientes autônomos do EOP. A Prevenção de Perda de Dados (DLP) ajuda a identificar, monitorar e proteger informações confidenciais de sua organização por meio de análise profunda de conteúdo. DLP é cada vez mais importante para sistemas de mensagens corporativos porque o email crucial para os negócios inclui dados confidenciais que precisam ser protegidos. O recurso DLP permite proteger dados confidenciais sem afetar a produtividade do trabalhador.

Você pode configurar as políticas de DLP no EAC, que permitem:

- Iniciar com um modelo de política pré-configurado que pode ajudar a detectar tipos específicos de informações confidenciais, como dados PCI-DSS, dados do Gramm-Leach-Bliley Act ou até mesmo informações de identificação pessoal (PII) específicas de localidade.

- Use todo o poder de critérios e ações de regra de fluxo de emails existentes e adicione novas regras de fluxo de email.

- Teste a eficácia das suas políticas de DLP antes de impô-las totalmente.

- Incorpore seus próprios modelos personalizados de política de DLP e tipos de informações confidenciais.

- Detectar informações confidenciais em anexos de mensagens, texto do corpo ou linhas de assunto e ajustar o nível de confiança em que o serviço age.

- Detecte dados confidenciais por meio de impressão digital do documento. A impressão digital de documentos ajuda você a criar facilmente tipos de informações confidenciais personalizados com base em formulários baseados em texto que você pode usar para definir regras de fluxo de email e políticas de DLP.

- Adicionar dicas de política, que podem ajudar a reduzir a perda de dados, exibindo um aviso para o Outlook 2013, Outlook na Web e OWA para dispositivos usuários e também podem melhorar a eficácia de suas políticas, permitindo relatórios falsos positivos.

- Revise os dados de incidentes em relatórios de DLP ou adicione seus próprios relatórios específicos usando uma ação de geração de relatórios de incidentes.

> [!NOTE]
> As políticas de DLP são aplicadas apenas ao email que entra ou sai da organização. Os emails intraorganizacionais (internos) não têm políticas de DLP aplicadas, a menos que você execute o Exchange Server 2013 com DLP local. Isso também se aplica às dicas de política de DLP, que informam aos usuários sobre possíveis violações de política antes que dados confidenciais sejam enviados por engano a destinatários não autorizados.

Para saber mais sobre DLP, confira [prevenção contra perda de dados no Exchange Online](https://docs.microsoft.com/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention).

## <a name="office-365-message-encryption"></a>Criptografia de Mensagem do Office 365

A criptografia de mensagens do Office 365, parte da proteção de informações do Azure, é um serviço online que permite que os usuários de email enviem mensagens de email criptografadas para qualquer pessoa. Os clientes locais podem acessar a criptografia de mensagens do Office 365 adquirindo a proteção de informações do Azure e usando o Exchange Online Protection para configurar o fluxo de emails através do Exchange Online. Para saber mais sobre a criptografia de mensagem do Office 365 no Exchange Online, confira [criptografia de mensagem do office 365](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption) na descrição de serviço do Exchange Online.

## <a name="messaging-policy-and-compliance-features-across-eop-options"></a>Recursos de diretiva e conformidade de mensagens através de opções EOP

| Recurso | EOP autônomo | Recursos do EOP no <br/> Exchange Online | Exchange Enterprise <br/> CAL com serviços |
|:-----|:-----|:-----|:-----|
|Regras do fluxo de email|Sim<sup>1</sup>|Sim<sup>1</sup>|Sim<sup>1, 3</sup>|
|Registro em log de auditoria|Sim<sup>2</sup>|Sim|Sim|
|Prevenção de perda de dados (DLP)|Não|Sim|Sim<sup>3</sup>|
|Criptografia de Mensagem do Office 365|Sim<sup>4</sup>|Sim|Sim<sup>4</sup>|

> [!NOTE]
> <sup>1</sup> as condições, exceções e ações da regra de fluxo de emails diferem levemente entre o EOP e o Exchange Online. Essas diferenças são observadas nas [condições e exceções de regra de fluxo de emails (predicados) no Exchange Online](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions) e [ações de regra de fluxo de email no Exchange Online](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions). <br/>
> <sup>2</sup> Os relatórios de auditoria do EOP são um subconjunto dos relatórios de auditoria do Exchange Online que excluem informações sobre caixas de correio. <br/>
> <sup>3</sup> Dicas de política de DLP não estão disponíveis para clientes do Exchange Enterprise CAL com Serviços. <br/>
> <sup>4</sup> com suporte para clientes locais que compram o complemento de proteção de informações do Azure e use o Exchange Online Protection para rotear emails pelo Exchange Online. Para a experiência de área de trabalho, além do complemento do Azure Information Protection, os aplicativos do Microsoft 365 para Enterprise precisam ser comprados. <br/>
