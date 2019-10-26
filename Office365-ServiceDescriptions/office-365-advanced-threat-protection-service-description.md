---
title: Descrição do Serviço da Proteção Avançada contra Ameaças do Office 365
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: A proteção avançada contra ameaças do Microsoft Office 365 (ATP) é um serviço de filtragem de email baseado em nuvem que ajuda a proteger sua organização contra malware e vírus desconhecidos, fornecendo proteção robusta de dia zero e inclui recursos para proteger seus organização contra links prejudiciais em tempo real.
ms.openlocfilehash: 3295bf261c9412f5881a16e3bc17088f32b4a18e
ms.sourcegitcommit: fb245074a57da585566096f6956d37325f451262
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/26/2019
ms.locfileid: "37734169"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Descrição do Serviço da Proteção Avançada contra Ameaças do Office 365

A proteção avançada contra ameaças do Microsoft Office 365 (ATP) é um serviço de filtragem de email baseado em nuvem que ajuda a proteger sua organização contra malware e vírus desconhecidos, fornecendo proteção robusta de dia zero e inclui recursos para proteger seus organização contra links prejudiciais em tempo real. A ATP tem recursos ricos de relatórios e de rastreamento de URL que dão aos administradores a percepção do tipo de ataques que ocorrem na sua organização.

A seguir estão as principais maneiras de usar a ATP para proteção de mensagens:

- Em um cenário somente de filtragem ATP do Office 365, a ATP fornece proteção de email baseada em nuvem para seu ambiente local do Exchange Server ou qualquer outra solução de email SMTP local.

- O Office 365 ATP pode ser habilitado para proteger caixas de correio hospedadas na nuvem do Exchange Online. Para saber mais sobre a Exchange Online, consulte [Descrição de Serviço do Exchange Online](exchange-online-service-description/exchange-online-service-description.md).

- Em uma implantação híbrida, a ATP pode ser configurada para proteger seu ambiente de mensagens e controlar o roteamento de email quando você tem uma combinação de caixas de correio locais e em nuvem com o Exchange Online Protection para filtragem de email de entrada.

## <a name="office-365-advanced-threat-protection-atp-availability"></a>Disponibilidade de proteção avançada contra ameaças (ATP) do Office 365

A ATP está incluída no Office 365 Enterprise e5, no Office 365 Education e no Microsoft 365 Business.

Você pode adicionar a ATP aos seguintes planos de assinatura do Exchange e do Office 365:

- Exchange Online Plano 1

- Plano 2 do Exchange Online

- Quiosque do Exchange Online

- Proteção do Exchange Online

- Office 365 Business Essentials

- Office 365 Business Premium

- Office 365 Enterprise E1

- Office 365 Enterprise E3

- Office 365 Enterprise F1

- Office 365 A1

- Office 365 A3

Para comprar a proteção avançada contra ameaças do Office 365, confira [office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).

Para comparar recursos entre planos, confira [Compare Office 365 for Business Plans](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) e [Descubra a solução Microsoft 365 Enterprise que é adequada para você](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans).

## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>O que há de novo no Office 365 proteção avançada contra ameaças (ATP)

Continuamos a adicionar novos recursos ao Office 365 ATP. Para saber mais sobre os novos recursos vindos à ATP (ou Microsoft 365 em geral), confira os seguintes recursos:

- [Roteiro do Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Novidades na ATP do Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Requisitos para a proteção avançada contra ameaças do Office 365 (ATP)

A ATP pode ser usada com qualquer agente de transferência de email SMTP, como o Microsoft Exchange Server. Para saber mais sobre os sistemas operacionais, navegadores da Web e idiomas suportados pela ATP, veja as seções "Navegadores com suporte" e "Idiomas com suporte" em [Centro de administração do Exchange no Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).

## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>Disponibilidade de recursos nos planos de proteção avançada contra ameaças (ATP)

Todos os recursos estão listados abaixo. Quando o Exchange Online é mencionado, ele normalmente refere-se à família de serviços do Office 365 Enterprise.

|**Recurso**|**Plano ATP 1**<br>(anteriormente ATP autônomo)|**Plano ATP 2**<br>(anteriormente inteligência de ameaças <br>autônomo| Office 365 Enterprise E5|
|:-----|:-----|:-----|:-----|
|*Configuração, proteção e detecção*|
|Anexos Seguros|Sim|Sim|Sim|
|Links Seguros|Sim|Sim|Sim|
|Políticas anti-phishing|Sim|Sim|Sim|
|ATP para SharePoint, OneDrive e Microsoft Teams|Sim|Sim|Sim|
|Anexos seguros no Teams|Sim|Sim|Sim|
|Links seguros no Teams|Não|Não|Não|
|Relatórios em tempo real|Sim|Sim|Sim|
|*Automação, investigação, correção e educação*|
|Rastreadores de Ameaças|Não|Sim|Sim|
|Explorer (investigação avançada de ameaças)|Não|Sim|Sim|
|Resposta de incidente automatizada|Não|Sim|Sim|
|Simulador de ataque|Não|Sim|Sim|

## <a name="advanced-threat-protection-atp-capabilities"></a>Recursos de proteção avançada contra ameaças (ATP)

### <a name="safe-attachments"></a>Anexos Seguros

Os [anexos seguros de ATP](https://docs.microsoft.com/office365/securitycompliance/atp-safe-attachments) protegem contra malware e vírus desconhecidos e fornecem proteção de dia zero para proteger seu sistema de mensagens. Todas as mensagens e os anexos que não tenham uma assinatura de vírus/malware conhecida são roteados para um ambiente especial onde a ATP usa uma variedade de técnicas de aprendizagem e análise automática para detectar conteúdo mal-intencionado. Se nenhuma atividade suspeita for detectada, a mensagem será liberada para entrega na caixa de correio.

> [!NOTE]
> A verificação de anexos seguros de ATP ocorre na mesma região onde seus dados do Office 365 residem. Para obter mais informações sobre a geografia do Data Center, confira [onde estão seus dados?](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>Links seguros

O recurso [links seguros de ATP](https://docs.microsoft.com/Office365/SecurityCompliance/atp-safe-links) protege seus usuários contra URLs mal-intencionadas em uma mensagem ou em um documento do Office. A proteção permanece sempre que o link é selecionado, pois links mal-intencionados são bloqueados dinamicamente enquanto bons links podem ser acessados.

Os links seguros estão disponíveis para URLs nos seguintes aplicativos:

- Office 365 ProPlus no Windows ou Mac

- Office para a Web (Word para a Web, Excel para a Web, PowerPoint para a Web e OneNote para a Web)

- Word, Excel, PowerPoint e Visio no Windows, bem como aplicativos do Office em dispositivos iOS e Android

> [!NOTE]
> Os usuários devem ser licenciados<sup>\*</sup>para a ATP, devem ser incluídos nas políticas de links seguros de ATP e devem estar conectados em seus dispositivos para que a proteção seja realizada.

<sup>\*</sup>Para licenças ATP em toda a organização (por exemplo, ATP_ENTERPRISE_FACULTY), você não precisa atribuir licenças ATP a usuários individuais.

### <a name="anti-phishing-policies"></a>Políticas anti-phishing

A [ATP anti-phishing](https://docs.microsoft.com/office365/securitycompliance/atp-anti-phishing) verifica mensagens de entrada para indicadores que uma mensagem pode ser uma tentativa de phishing. Quando os usuários são cobertos por políticas ATP (anexos seguros, links seguros ou anti-phishing), as mensagens de entrada são avaliadas por vários modelos de aprendizado de máquina que analisam mensagens e a ação apropriada é executada, com base nas políticas configuradas.

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP para SharePoint, OneDrive e Microsoft Teams

[ATP para SharePoint, onedrive e Microsoft Teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams) ajuda a detectar e bloquear arquivos identificados como mal-intencionados em sites de equipe e bibliotecas de documentos.

### <a name="real-time-reports"></a>Relatórios em tempo real

Os recursos de monitoramento disponíveis no centro de conformidade & segurança do Office 365 incluem [relatórios e insights em tempo real](https://docs.microsoft.com/office365/securitycompliance/view-reports-for-atp) que permitem aos administradores de segurança e conformidade se concentrarem em problemas de alta prioridade, como ataques de segurança ou maior atividade suspeita. Além de destacar áreas problemáticas, relatórios inteligentes e insights incluem recomendações e links para exibir e explorar dados e também realizar ações rápidas.

### <a name="threat-trackers"></a>Rastreadores de Ameaças

Os [rastreadores de ameaças](https://docs.microsoft.com/office365/securitycompliance/threat-trackers) são widgets informativos e modos de exibição que oferecem aos usuários autorizados problemas de cybersecurity que podem afetar sua organização.

### <a name="explorer"></a>Explorer

Explorer (também chamado de Gerenciador de ameaças) é um relatório em tempo real que permite que os usuários autorizados identifiquem e analisem ameaças recentes. Por padrão, esse relatório mostra dados dos últimos 7 dias; no entanto, os modos de exibição podem ser modificados para mostrar dados nos últimos 30 dias.

Para obter mais informações sobre o Explorer (no Office 365 Advanced Threat Protection Plan 2) e detecções em tempo real (no Office 365 Advanced Threat Protection Plan 1), consulte [Threat Explorer (and real-time detecções)](https://docs.microsoft.com/office365/securitycompliance/threat-explorer).

### <a name="attack-simulator"></a>Simulador de ataque

O [simulador de ataques](https://docs.microsoft.com/office365/SecurityCompliance/attack-simulator) permite que os usuários autorizados executem cenários de ataque realísticos em sua organização. Vários tipos diferentes de ataques estão disponíveis, incluindo o nome de exibição de um ataque de spear-phishing, um ataque de irrigação de senha e um ataque de senha de força bruta.
