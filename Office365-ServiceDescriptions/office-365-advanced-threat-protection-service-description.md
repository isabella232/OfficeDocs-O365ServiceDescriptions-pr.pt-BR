---
title: Descrição do serviço do Microsoft Defender para Office 365
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: O Microsoft Defender para Office 365 é um serviço de filtragem de email baseado na nuvem que ajuda a proteger sua organização contra vírus e malware desconhecidos, fornecendo proteção robusta de dia zero e inclui recursos para proteger sua organização contra links prejudiciais em tempo real.
ms.openlocfilehash: fd2869eb98b64fca4f241339497486a392815402
ms.sourcegitcommit: bab0eaae59d5c801f88eadbd29fd0d16de387c82
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 01/07/2021
ms.locfileid: "49780005"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Descrição do serviço do Microsoft Defender para Office 365

O Microsoft Defender para Office 365 é um serviço de filtragem de email baseado na nuvem que ajuda a proteger sua organização contra vírus e malware desconhecidos, fornecendo proteção robusta de dia zero e inclui recursos para proteger sua organização contra links prejudiciais em tempo real. O Defender para Office 365 tem recursos avançados de rastreamento de URL e relatórios que dão aos administradores informações sobre os tipos de ataques que ocorrem em sua organização.

Veja a seguir as principais maneiras de usar o Defender for Office 365 para proteção de mensagens:

- Em um cenário somente de filtragem do Defender para Office 365, o Defender para Office 365 fornece proteção de email baseada em nuvem para seu ambiente local do Exchange Server ou qualquer outra solução de email SMTP local.

- O Defender para Office 365 pode ser habilitado para proteger caixas de correio do Exchange Online hospedadas na nuvem. Para saber mais sobre o Exchange Online, consulte a [descrição do serviço do Exchange Online.](exchange-online-service-description/exchange-online-service-description.md)

- Em uma implantação híbrida, o Defender para Office 365 pode ser configurado para proteger seu ambiente de mensagens e controlar o roteamento de email quando você tiver uma combinação de caixas de correio locais e na nuvem com o Proteção do Exchange Online para filtragem de email de entrada.

## <a name="microsoft-defender-for-office-365-availability"></a>Disponibilidade do Microsoft Defender para Office 365

O Defender para Office 365 Plano 2 está incluído no Office 365 E5, no Office 365 A5 e no Microsoft 365 E5. O Defender para Office 365 Plano 1 está incluído no Microsoft 365 Business Premium.

Você pode adicionar o Defender para Office 365 aos seguintes planos de assinatura do Exchange e do Microsoft 365:

- Exchange Online Plano 1

- Plano 2 do Exchange Online

- Quiosque do Exchange Online

- Proteção do Exchange Online

- Microsoft 365 Business Basic

- Microsoft 365 Business Standard

- Office 365 Enterprise E1

- Office 365 Enterprise E3

- Office 365 Enterprise F3

- Office 365 A1

- Office 365 A3

Para comprar o Microsoft Defender para Office 365, confira [o Microsoft Defender para Office 365.](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)

Para comparar recursos entre planos, confira [Ferramentas poderosas para dar](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) suporte à sua empresa e transformar sua empresa com o Microsoft [365.](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans)

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Novidades no Microsoft Defender para Office 365

Estamos continuamente adicionando novos recursos ao Defender para Office 365. Para saber mais sobre os novos recursos do Defender para Office 365 (ou o Microsoft 365 em geral), confira os seguintes recursos:

- [Roteiro do Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Novidades no Microsoft Defender para Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Requisitos do Microsoft Defender para Office 365

O Defender para Office 365 pode ser usado com qualquer agente de transferência de email SMTP, como o Microsoft Exchange Server. Para saber mais sobre os sistemas operacionais, navegadores da Web e idiomas suportados pelo Defender para Office 365, confira as seções "Navegadores com suporte" e "Idiomas com suporte" no Centro de administração do Exchange no [Exchange Online Protection.](https://go.microsoft.com/fwlink/p/?LinkId=282381)

## <a name="feature-availability-across-defender-for-office-365-plans"></a>Disponibilidade de recursos nos planos do Defender para Office 365

Todos os recursos estão listados abaixo. Quando o Exchange Online é mencionado, ele normalmente refere-se à família de serviços do Office 365 Enterprise.<br><br>

| Recurso | Defender para Office 365 Plano 1 | Defender para Office 365 Plano 2 | Microsoft 365 E5 / E5 Security|
|:-----|:-----|:-----|:-----|
|*Configuração, proteção e detecção*|
|[Anexos Seguros](#safe-attachments)|Sim|Sim|Sim|
|Anexos seguros no Teams|Sim|Sim|Sim|
|[Links Seguros](#safe-links)|Sim|Sim|Sim|
|[Documentos Seguros](#safe-documents)|Não|Não|Sim|
|Links Seguros no Teams|Sim|Sim|Sim|
|[ATP para SharePoint, OneDrive e Microsoft Teams](#atp-for-sharepoint-onedrive-and-microsoft-teams)|Sim|Sim|Sim|
|[Políticas anti-phishing](#anti-phishing-policies)|Sim|Sim|Sim|
|[Relatórios em tempo real](#real-time-reports)|Sim|Sim|Sim|
|*Automação, investigação, correção e educação*|
|[Controladores de Ameaças](#threat-trackers)|Não|Sim|Sim|
|Investigação de ameaças (investigação avançada de ameaças)|[Detecções em tempo real](#real-time-detections)|[Explorador](#explorer)|[Explorador](#explorer)|
|[Resposta automatizada a incidentes](#automated-incident-response)|Não|Sim|Sim|
|[Simulador de Ataque](#attack-simulator)|Não|Sim|Sim|
|*Integração com o Microsoft 365 Defender*|Não|Sim|Sim|

> [!TIP]
> Deseja uma lista baixável das diferenças entre o Defender para Office 365 Plano 1 e o Plano 2? [Obter o PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

> [!NOTE]
> Se seu locatário tiver apenas uma licença de avaliação do Office ATP P2 ou uma licença de avaliação do Office 365 E5, sem outra licença qualificada para a Proteção contra Ameaças da Microsoft, você não poderá acessar a Proteção contra Ameaças da Microsoft. Para saber mais sobre a licença MTP, consulte <https://docs.microsoft.com/microsoft-365/security/mtp/prerequisites>

## <a name="defender-for-office-365-capabilities"></a>Recursos do Defender para Office 365

### <a name="safe-attachments"></a>Anexos seguros

[Os Anexos Seguros](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) protegem contra vírus e malware desconhecidos e fornece proteção de dia zero para proteger seu sistema de mensagens. Todas as mensagens e anexos que não têm uma assinatura de vírus/malware conhecida são roteados para um ambiente especial em que o Defender para Office 365 usa uma variedade de técnicas de aprendizagem e análise de máquina para detectar intenção maliciosa. Se nenhuma atividade suspeita for detectada, a mensagem será liberada para entrega na caixa de correio.

> [!NOTE]
> A verificação de Anexos Seguros ocorre na mesma região em que seus dados do Office 365 residem. Para obter mais informações sobre geografia do data center, consulte [Onde seus dados estão localizados?](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>Links seguros

O [recurso Links Seguros](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) protege proativamente seus usuários contra URLs mal-intencionadas em uma mensagem ou em um documento do Office. A proteção permanece sempre que eles selecionam o link, pois links mal-intencionados são bloqueados dinamicamente, enquanto o acesso a links legítimos é permitido.

Os links seguros estão disponíveis para URLs nos seguintes aplicativos:

- Aplicativos do Microsoft 365 para empresas no Windows ou Mac

- Office na Web (Word para a Web, Excel para a Web, PowerPoint para a Web e OneNote para a Web)

- Word, Excel e PowerPoint no Windows

- Canais e chats do Microsoft Teams

> [!NOTE]
> Os usuários devem estar licenciados para o Defender para Office 365, devem estar incluídos nas políticas de Links seguros e devem estar conectados em seus dispositivos para que a proteção <sup>\*</sup> seja realizada.
>
> <sup>\*</sup> Para licenças do Defender para Office 365 em toda a organização (por exemplo, ATP_ENTERPRISE_FACULTY), você não precisa atribuir licenças do Defender para Office 365 a usuários individuais.
>
> Para obter mais informações sobre a proteção de Links seguros, consulte [Links seguros no Microsoft Defender para Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)

### <a name="safe-documents"></a>Documentos Seguros

O [recurso Documentos Seguros](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs) usa o Microsoft Defender para [Ponto](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) de Extremidade para verificar documentos e arquivos abertos no [Exibição Protegido.](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)

O que você precisa saber antes de começar?

- Os Documentos Seguros agora estão geralmente disponíveis para usuários com o Office Versão 2004 (12730.x) ou superior! Esse recurso está desabilitado por padrão e precisará ser habilitado pelo Administrador de Segurança.

- Esse recurso só está disponível para usuários com a licença do Microsoft 365 E5 ou do Microsoft 365 E5 Security (não incluído no Defender para planos do Office 365).

- Word, Excel e PowerPoint no Windows

- Canais e chats do Microsoft Teams

> [!NOTE]
> Os usuários devem estar licenciados para o Microsoft 365 E5 ou o Microsoft 365 E5 Security , devem estar incluídos nas políticas documentos seguros e devem estar conectados em seus dispositivos para que a proteção seja <sup>\*</sup> realizada.
>
> Para obter mais informações sobre a proteção de Documentos Seguros, consulte [Documentos Seguros no Microsoft 365 E5.](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs)

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP para SharePoint, OneDrive e Microsoft Teams

[A ATP para SharePoint, OneDrive](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  e Microsoft Teams ajuda a detectar e bloquear arquivos identificados como mal-intencionados em sites de equipe e bibliotecas de documentos. Além disso, a proteção de Links seguros agora está disponível nos canais e chats do Microsoft Teams.

### <a name="anti-phishing-policies"></a>Políticas anti-phishing

[O anti-phishing](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) verifica as mensagens de entrada em busca de indicadores de que uma mensagem pode ser uma tentativa de phishing. Quando os usuários são cobertos pelas políticas do Defender para Office 365 (Anexos Seguros, Links Seguros ou anti-phishing), as mensagens de entrada são avaliadas por vários modelos de aprendizado de máquina que analisam mensagens e a ação apropriada é tomada, com base nas políticas configuradas.

### <a name="real-time-reports"></a>Relatórios em tempo real

Os recursos de monitoramento disponíveis no Centro de Conformidade e Segurança incluem relatórios e informações em tempo [real](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) que permitem que seus administradores de segurança e conformidade se concentrem em problemas de alta prioridade, como ataques de segurança ou aumento de atividades suspeitas. & Além de destacar áreas problemáticas, relatórios inteligentes e ideias incluem recomendações e links para exibir e explorar dados e também tomar ações rápidas.

### <a name="explorer"></a>Explorador

O Explorador (também chamado de Explorador de Ameaças) é um relatório em tempo real que permite aos usuários autorizados identificar e analisar ameaças recentes. Por padrão, este relatório mostra dados dos últimos 7 dias, no entanto, os modos de exibição podem ser alterados para exibir dados dos últimos 30 dias.

O Explorer contém exibições, como Malware (para email e conteúdo), Envios, Phishing e Todos os Emails. Para ver como o Explorer se compara com detecções em tempo real, [baixe este PDF.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Para obter mais informações sobre o Explorer (no Microsoft Defender para Office 365 Plano 2) e detecções em tempo real (no Microsoft Defender para Office 365 Plano 1), consulte Explorador de Ameaças e detecções em tempo [real.](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)

### <a name="real-time-detections"></a>Detecções em tempo real

As detecções em tempo real são um relatório em tempo real que permite aos usuários autorizados identificar e analisar ameaças recentes. Assim como o Explorador, esse relatório mostra os dados dos últimos 7 dias.

As detecções em tempo real contêm exibições, como Malware (para email e conteúdo), Envios e Phishing. Para ver como as detecções em tempo real se comparam com o Explorer, [baixe este PDF.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Para obter mais informações sobre o Explorer (no Microsoft Defender para Office 365 Plano 2) e detecções em tempo real (no Microsoft Defender para Office 365 Plano 1), consulte Explorador de Ameaças (e detecções em tempo [real).](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)

### <a name="threat-trackers"></a>Rastreadores de Ameaças

[Os Rastreadores de Ameaças](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) são widgets informativos e exibições que fornecem aos usuários autorizados inteligência sobre problemas de segurança cibernética que podem afetar sua organização.

### <a name="automated-incident-response"></a>Resposta automatizada a incidentes

[Os recursos](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) automatizados de resposta a incidentes (AIR) disponíveis no Defender para Office 365 Plano 2 permitem que você execute processos de investigação automatizados em resposta a ameaças conhecidas que existem hoje. Ao automatizar determinadas tarefas de investigação, sua equipe de operações de segurança pode operar com mais eficiência e eficiência. Ações de correção, como excluir mensagens de email mal-intencionadas, são tomadas mediante aprovação da sua equipe de operações de segurança. Para saber mais, confira [Como o AIR funciona no Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office)

### <a name="attack-simulator"></a>Simulador de Ataque

[O Simulador](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) de Ataque permite que os usuários autorizados executem cenários de ataque realistas em sua organização. Vários tipos diferentes de ataques estão disponíveis, incluindo um ataque de phishing de nome para exibição, um ataque de pulverização de senha e um ataque de senha de força bruta.
