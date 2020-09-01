---
title: Descrição do serviço da Proteção Avançada contra Ameaças do Office 365
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
description: A proteção avançada contra ameaças do Microsoft Office 365 (ATP) é um serviço de filtragem de email baseado em nuvem que ajuda a proteger sua organização contra malware e vírus desconhecidos, fornecendo proteção robusta de dia zero e inclui recursos para proteger sua organização contra links prejudiciais em tempo real.
ms.openlocfilehash: 0e9c7e76cabd9f39a13c16689a4255732617b09d
ms.sourcegitcommit: 0f2d249dfc93432e17344f70b8317a455204f018
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/01/2020
ms.locfileid: "47318938"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Descrição do serviço da Proteção Avançada contra Ameaças do Office 365

A proteção avançada contra ameaças do Microsoft Office 365 (ATP) é um serviço de filtragem de email baseado em nuvem que ajuda a proteger sua organização contra malware e vírus desconhecidos, fornecendo proteção robusta de dia zero e inclui recursos para proteger sua organização contra links prejudiciais em tempo real. A ATP tem recursos ricos de relatórios e de rastreamento de URL que dão aos administradores a percepção do tipo de ataques que ocorrem na sua organização.

Veja a seguir as principais maneiras de usar a ATP para proteção de mensagens:

- Em um cenário de somente filtragem do Office 365, ATP fornece proteção de email baseada na nuvem para seu ambiente local do Exchange Server ou para qualquer outra solução de email SMTP local.

- A ATP do Office 365 pode ser habilitada para proteger caixas de correio do Exchange Online hospedadas na nuvem. Para saber mais sobre o Exchange Online, confira a [Descrição de serviço do Exchange Online](exchange-online-service-description/exchange-online-service-description.md).

- Em uma implantação híbrida, a ATP pode ser configurada para proteger seu ambiente de mensagens e controlar o roteamento de emails quando você tem uma combinação de caixas de email locais e na nuvem com a Proteção do Exchange Online para filtragem de emails recebidos.

## <a name="office-365-advanced-threat-protection-atp-availability"></a>Disponibilidade de proteção avançada contra ameaças (ATP) do Office 365

O plano 2 do Office 365 ATP está incluído no Office 365 e5, no Office 365 a5 e no Microsoft 365 e5. O Plano 1 do Office 365 ATP está incluído no Microsoft 365 Business Premium.

Você pode adicionar a ATP aos seguintes planos de assinatura do Exchange e do Microsoft 365:

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

Para comprar a proteção avançada contra ameaças do Office 365, confira [office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).

Para comparar recursos entre planos, consulte [poderosas ferramentas para dar suporte à sua empresa](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) e [transformar sua empresa com o Microsoft 365](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans).

## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>O que há de novo no Office 365 proteção avançada contra ameaças (ATP)

Continuamos a adicionar novos recursos ao Office 365 ATP. Para saber mais sobre os novos recursos vindos à ATP (ou Microsoft 365 em geral), confira os seguintes recursos:

- [Roteiro do Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Novidades na ATP do Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Requisitos para a proteção avançada contra ameaças do Office 365 (ATP)

A ATP pode ser usada com qualquer agente de transferência de email SMTP, como o Microsoft Exchange Server. Para obter informações sobre os sistemas operacionais, navegadores da Web e idiomas suportados pela ATP, consulte as seções "navegadores compatíveis" e "idiomas com suporte" no [centro de administração do Exchange no Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).

## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>Disponibilidade de recursos nos planos de proteção avançada contra ameaças (ATP)

Todos os recursos estão listados abaixo. Quando o Exchange Online é mencionado, ele normalmente refere-se à família de serviços do Office 365 Enterprise.

|**Recurso**|**Plano ATP 1**<br>(anteriormente ATP autônomo)|**Plano ATP 2**<br>(anteriormente inteligência de ameaças <br>autônomo| Segurança da Microsoft 365 E5/e5|
|:-----|:-----|:-----|:-----|
|*Configuração, proteção e detecção*|
|[Anexos Seguros](#safe-attachments)|Sim|Sim|Sim|
|Anexos seguros no Teams|Sim|Sim|Sim|
|[Links Seguros](#safe-links)|Sim|Sim|Sim|
|[Documentos seguros](#safe-documents)|Não|Não|Sim|
|Links seguros no Teams|Sim|Sim|Sim|
|[ATP para SharePoint, OneDrive e Microsoft Teams](#atp-for-sharepoint-onedrive-and-microsoft-teams)|Sim|Sim|Sim|
|[Políticas anti-phishing](#anti-phishing-policies)|Sim|Sim|Sim|
|[Relatórios em tempo real](#real-time-reports)|Sim|Sim|Sim|
|*Automação, investigação, correção e educação*|
|[Controladores de Ameaças](#threat-trackers)|Não|Sim|Sim|
|Investigação de ameaças (investigação avançada de ameaças)|[Detecções em tempo real](#real-time-detections)|[Explorador](#explorer)|[Explorador](#explorer)|
|[Resposta de incidente automatizada](#automated-incident-response)|Não|Sim|Sim|
|[Simulador de Ataque](#attack-simulator)|Não|Sim|Sim|

> [!TIP]
> Deseja uma lista de diferenças baixáveis entre o Office 365 ATP Plan 1 e o plano 2? [Obter o PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf). 

## <a name="advanced-threat-protection-atp-capabilities"></a>Recursos de Proteção Avançada contra Ameaças (ATP)

### <a name="safe-attachments"></a>Anexos seguros

Os [anexos seguros de ATP](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) protegem contra malware e vírus desconhecidos e fornecem proteção de dia zero para proteger seu sistema de mensagens. Todas as mensagens e os anexos que não tenham uma assinatura de vírus/malware conhecida são roteados para um ambiente especial onde a ATP usa uma variedade de técnicas de aprendizagem e análise automática para detectar conteúdo mal-intencionado. Se nenhuma atividade suspeita for detectada, a mensagem será liberada para entrega na caixa de correio.

> [!NOTE]
> A verificação de anexos seguros de ATP ocorre na mesma região onde seus dados do Office 365 residem. Para obter mais informações sobre a geografia do Data Center, confira [onde estão seus dados?](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>Links seguros

O recurso [links seguros de ATP](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) protege seus usuários contra URLs mal-intencionadas em uma mensagem ou em um documento do Office. A proteção permanece sempre que eles selecionam o link, pois links mal-intencionados são bloqueados dinamicamente, enquanto o acesso a links legítimos é permitido.

Os links seguros estão disponíveis para URLs nos seguintes aplicativos:

- Microsoft 365 aplicativos para empresas no Windows ou Mac

- Office para a Web (Word para a Web, Excel para a Web, PowerPoint para a Web e OneNote para a Web)

- Word, Excel, PowerPoint e Visio no Windows, bem como aplicativos do Office em dispositivos iOS e Android

- Canais e chats do Microsoft Teams

> [!NOTE]
> Os usuários devem ser licenciados para a ATP <sup>\*</sup> , devem ser incluídos nas políticas de links seguros de ATP e devem estar conectados em seus dispositivos para que a proteção seja realizada.
>
> <sup>\*</sup> Para licenças ATP em toda a organização (por exemplo, ATP_ENTERPRISE_FACULTY), você não precisa atribuir licenças ATP a usuários individuais.
>
> Para obter mais informações sobre a proteção de links seguros de ATP, confira [como os links seguros de ATP funcionam com URLs em documentos do Office](https://docs.microsoft.com/microsoft-365/security/office-365-security/how-atp-safe-links-works#how-atp-safe-links-works-with-urls-in-office-documents).

### <a name="safe-documents"></a>Documentos seguros

O recurso [documentos seguros de ATP](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs) usa a [proteção avançada contra ameaças do Microsoft defender](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) para verificar documentos e arquivos abertos no [modo de exibição protegido](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653).

O que você precisa saber antes de começar?

- Agora, os documentos seguros estão disponíveis para usuários com o Office versão 2004 (12730. x) ou mais. Esse recurso está desativado por padrão e deverá ser habilitado pelo administrador de segurança.

- Este recurso está disponível apenas para usuários com a licença de segurança do Microsoft 365 E5 ou do Microsoft 365 E5 (não incluída nos planos ATP do Office 365).

- Word, Excel, PowerPoint e Visio no Windows, bem como aplicativos do Office em dispositivos iOS e Android

- Canais e chats do Microsoft Teams

> [!NOTE]
> Os usuários devem ser licenciados para a Microsoft 365 E5 ou para a segurança do Microsoft 365 E5 <sup>\*</sup> , devem ser incluídos nas políticas de documentos seguros de ATP e devem estar conectados em seus dispositivos para que a proteção seja estabelecida.
>
> Para obter mais informações sobre a proteção de documentos seguros de ATP, consulte [documentos seguros no Microsoft 365 E5](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs).

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP para SharePoint, OneDrive e Microsoft Teams

[ATP para SharePoint, onedrive e Microsoft Teams](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  ajuda a detectar e bloquear arquivos identificados como mal-intencionados em sites de equipe e bibliotecas de documentos. Além disso, a proteção de links seguros de ATP agora está disponível nos canais e chats do Microsoft Teams.

### <a name="anti-phishing-policies"></a>Políticas anti-phishing

A [ATP anti-phishing](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) verifica mensagens de entrada para indicadores que uma mensagem pode ser uma tentativa de phishing. Quando os usuários são protegidos por políticas ATP (Anexos Seguros, Links Seguros ou anti-phishing), as mensagens de entrada são avaliadas por vários modelos de aprendizagem de computador que analisam mensagens e a ação adequada é realizada, com base nas políticas configuradas.

### <a name="real-time-reports"></a>Relatórios em tempo real

Os recursos de monitoramento disponíveis no centro de conformidade e segurança & incluem [relatórios em tempo real e insights](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) que permitem que seus administradores de segurança e conformidade se concentrem em problemas de alta prioridade, como ataques de segurança ou uma maior atividade suspeita. Além de destacar áreas problemáticas, relatórios inteligentes e insights incluem recomendações e links para exibir e explorar dados e também realizar ações rápidas.

### <a name="explorer"></a>Explorador

O Explorador (também chamado de Explorador de Ameaças) é um relatório em tempo real que permite aos usuários autorizados identificar e analisar ameaças recentes. Por padrão, este relatório mostra dados dos últimos 7 dias, no entanto, os modos de exibição podem ser alterados para exibir dados dos últimos 30 dias.

O Explorer contém modos de exibição, como malware (para email e conteúdo), envios, Phish e todos os emails. Para ver como o Explorer compara com as detecções em tempo real, [Baixe este PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Para obter mais informações sobre o Explorer (no Office 365 Advanced Threat Protection Plan 2) e detecções em tempo real (no Office 365 Advanced Threat Protection Plan 1), consulte [Threat Explorer and real-time detecções](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).

### <a name="real-time-detections"></a>Detecções em tempo real

As detecções em tempo real são um relatório em tempo real que permite aos usuários autorizados identificar e analisar ameaças recentes. Assim como o Explorador, esse relatório mostra os dados dos últimos 7 dias.

As detecções em tempo real contêm modos de exibição, como malware (para email e conteúdo), envios e phishing. Para ver como as detecções em tempo real são comparadas com o Explorer, [Baixe este PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Para obter mais informações sobre o Explorer (no Office 365 Advanced Threat Protection Plan 2) e detecções em tempo real (no Office 365 Advanced Threat Protection Plan 1), consulte [Threat Explorer (and real-time detecções)](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).

### <a name="threat-trackers"></a>Rastreadores de Ameaças

Os [rastreadores de ameaças](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) são widgets informativos e modos de exibição que oferecem aos usuários autorizados problemas de cybersecurity que podem afetar sua organização.

### <a name="automated-incident-response"></a>Resposta de incidente automatizada

Recursos de [resposta de incidente automatizado](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) (Air) disponíveis no Office 365 ATP Plan 2 permite que você execute processos de investigação automatizados em resposta a ameaças bem conhecidas que existem hoje. Por meio de determinadas tarefas de investigação, a equipe de operações de segurança pode operar de forma mais eficiente e eficaz. As ações de correção, como excluir mensagens de email mal-intencionadas, são tomadas após a aprovação da equipe de operações de segurança. Para saber mais, veja [como o Air funciona no Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office).

### <a name="attack-simulator"></a>Simulador de Ataque

O [simulador de ataques](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) permite que os usuários autorizados executem cenários de ataque realísticos em sua organização. Vários tipos diferentes de ataques estão disponíveis, incluindo o nome de exibição de um ataque de spear-phishing, um ataque de irrigação de senha e um ataque de senha de força bruta.
