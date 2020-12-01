---
title: Descrição do serviço do Microsoft defender para Office 365
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
description: O Microsoft defender para Office 365 é um serviço de filtragem de email baseado em nuvem que ajuda a proteger sua organização contra malware e vírus desconhecidos, fornecendo uma proteção robusta de dia zero e inclui recursos para proteger sua organização contra links prejudiciais em tempo real.
ms.openlocfilehash: 1d99b59e089ecb351d436c49a4f4e3986aefa6cd
ms.sourcegitcommit: 0752cc6c082737a19c7dca24c8f3b555ea871f4f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 12/01/2020
ms.locfileid: "49519022"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Descrição do serviço do Microsoft defender para Office 365

O Microsoft defender para Office 365 é um serviço de filtragem de email baseado em nuvem que ajuda a proteger sua organização contra malware e vírus desconhecidos, fornecendo uma proteção robusta de dia zero e inclui recursos para proteger sua organização contra links prejudiciais em tempo real. O defender para Office 365 tem recursos avançados de rastreamento de URL e de relatórios que oferecem aos administradores informações sobre o tipo de ataque que ocorrem na organização.

A seguir estão as principais maneiras de usar o defender para Office 365 para proteção de mensagens:

- Em um único cenário de filtragem do defender para Office 365, o defender para Office 365 fornece proteção de email baseada em nuvem para seu ambiente local do Exchange Server ou qualquer outra solução de email SMTP local.

- O defender para Office 365 pode ser habilitado para proteger caixas de correio hospedadas na nuvem do Exchange Online. Para saber mais sobre o Exchange Online, confira a [Descrição de serviço do Exchange Online](exchange-online-service-description/exchange-online-service-description.md).

- Em uma implantação híbrida, o defender para Office 365 pode ser configurado para proteger seu ambiente de mensagens e controlar o roteamento de email quando você tem uma combinação de caixas de correio locais e em nuvem com o Exchange Online Protection para filtragem de email de entrada.

## <a name="microsoft-defender-for-office-365-availability"></a>Disponibilidade do Microsoft defender para Office 365

O defender for Office 365 plano 2 está incluído no Office 365 e5, no Office 365 a5 e no Microsoft 365 e5. O defender for Office 365 plano 1 está incluído no Microsoft 365 Business Premium.

Você pode adicionar o defender para Office 365 aos seguintes planos de assinatura do Exchange e do Microsoft 365:

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

Para comprar o Microsoft defender para Office 365, confira [Microsoft defender para office 365](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).

Para comparar recursos entre planos, consulte [poderosas ferramentas para dar suporte à sua empresa](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) e [transformar sua empresa com o Microsoft 365](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans).

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>O que há de novo no Microsoft defender para Office 365

Estamos continuando a adicionar novos recursos ao defender para Office 365. Para saber mais sobre os novos recursos que chegam ao defender para Office 365 (ou Microsoft 365 em geral), confira os seguintes recursos:

- [Roteiro do Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [O que há de novo no Microsoft defender para Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Requisitos para o Microsoft defender para Office 365

O defender para Office 365 pode ser usado com qualquer agente de transferência de email SMTP, como o Microsoft Exchange Server. Para obter informações sobre os sistemas operacionais, navegadores da Web e idiomas suportados pelo defender for Office 365, consulte as seções "Navegadores suportados" e "idiomas com suporte" no [centro de administração do Exchange no Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).

## <a name="feature-availability-across-defender-for-office-365-plans"></a>Disponibilidade de recursos nos planos do defender para Office 365

Todos os recursos estão listados abaixo. Quando o Exchange Online é mencionado, ele normalmente refere-se à família de serviços do Office 365 Enterprise.<br><br>

| Recurso | Defender para Office 365 plano 1 | Defender para Office 365 plano 2 | Segurança da Microsoft 365 E5/e5|
|:-----|:-----|:-----|:-----|
|*Configuração, proteção e detecção*|
|[Anexos Seguros](#safe-attachments)|Sim|Sim|Sim|
|Anexos seguros no Teams|Sim|Sim|Sim|
|[Links Seguros](#safe-links)|Sim|Sim|Sim|
|[Documentos Seguros](#safe-documents)|Não|Não|Sim|
|Links seguros no Teams|Sim|Sim|Sim|
|[ATP para SharePoint, OneDrive e Microsoft Teams](#atp-for-sharepoint-onedrive-and-microsoft-teams)|Sim|Sim|Sim|
|[Políticas anti-phishing](#anti-phishing-policies)|Sim|Sim|Sim|
|[Relatórios em tempo real](#real-time-reports)|Sim|Sim|Sim|
|*Automação, investigação, correção e educação*|
|[Controladores de Ameaças](#threat-trackers)|Não|Sim|Sim|
|Investigação de ameaças (investigação avançada de ameaças)|[Detecções em tempo real](#real-time-detections)|[Explorador](#explorer)|[Explorador](#explorer)|
|[Resposta de incidente automatizada](#automated-incident-response)|Não|Sim|Sim|
|[Simulador de Ataque](#attack-simulator)|Não|Sim|Sim|
|*Integração com o Microsoft 365 defender*|Não|Não|Sim|

> [!TIP]
> Deseja uma lista de diferenças baixáveis entre o defender para Office 365 plano 1 e o plano 2? [Obter o PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf). 

## <a name="defender-for-office-365-capabilities"></a>Recursos do defender para Office 365

### <a name="safe-attachments"></a>Anexos seguros

O recurso [anexos seguros](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) protege contra vírus e malware desconhecidos e oferece proteção de dia zero para proteger seu sistema de mensagens. Todas as mensagens e anexos que não têm uma assinatura de vírus/malware conhecida são direcionados para um ambiente especial onde o defender para Office 365 usa uma variedade de técnicas de aprendizado e análise de máquina para detectar más intenções. Se nenhuma atividade suspeita for detectada, a mensagem será liberada para entrega na caixa de correio.

> [!NOTE]
> A verificação de anexos seguros ocorre na mesma região onde seus dados do Office 365 residem. Para obter mais informações sobre a geografia do Data Center, confira [onde estão seus dados?](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>Links seguros

O recurso de [links seguros](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) pró-ativamente protege seus usuários contra URLs mal-intencionadas em uma mensagem ou em um documento do Office. A proteção permanece sempre que eles selecionam o link, pois links mal-intencionados são bloqueados dinamicamente, enquanto o acesso a links legítimos é permitido.

Os links seguros estão disponíveis para URLs nos seguintes aplicativos:

- Microsoft 365 aplicativos para empresas no Windows ou Mac

- Office na Web (Word para a Web, Excel para a Web, PowerPoint para a Web e OneNote para a Web)

- Word, Excel e PowerPoint no Windows

- Canais e chats do Microsoft Teams

> [!NOTE]
> Os usuários devem ser licenciados para o defender para Office 365 <sup>\*</sup> , devem ser incluídos em políticas de links seguros e devem estar conectados em seus dispositivos para que a proteção seja realizada.
>
> <sup>\*</sup> Para licenças de toda a organização do defender for Office 365 (por exemplo, ATP_ENTERPRISE_FACULTY), você não precisa atribuir licenças do defender para Office 365 a usuários individuais.
>
> Para obter mais informações sobre proteção de links seguros, consulte [links seguros no Microsoft defender para Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links).

### <a name="safe-documents"></a>Documentos Seguros

O recurso [documentos seguros](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs) usa o [Microsoft defender para ponto de extremidade](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) para verificar documentos e arquivos abertos no modo de [exibição protegido](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653).

O que você precisa saber antes de começar?

- Agora, os documentos seguros estão disponíveis para usuários com o Office versão 2004 (12730. x) ou mais. Esse recurso está desativado por padrão e deverá ser habilitado pelo administrador de segurança.

- Este recurso está disponível apenas para usuários com a licença de segurança do Microsoft 365 E5 ou Microsoft 365 E5 (não incluída nos planos do defender para Office 365).

- Word, Excel e PowerPoint no Windows

- Canais e chats do Microsoft Teams

> [!NOTE]
> Os usuários devem ser licenciados para a Microsoft 365 E5 ou para a segurança do Microsoft 365 E5 <sup>\*</sup> , deve ser incluído em políticas de documentos seguros e deve estar conectado em seus dispositivos para que a proteção seja realizada.
>
> Para obter mais informações sobre a proteção de documentos seguros, consulte [documentos seguros no Microsoft 365 E5](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs).

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP para SharePoint, OneDrive e Microsoft Teams

[ATP para SharePoint, onedrive e Microsoft Teams](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  ajuda a detectar e bloquear arquivos identificados como mal-intencionados em sites de equipe e bibliotecas de documentos. Além disso, a proteção de links seguros agora está disponível nos canais e chats do Microsoft Teams.

### <a name="anti-phishing-policies"></a>Políticas anti-phishing

O [anti-phishing](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) verifica mensagens de entrada para indicadores de que uma mensagem pode ser uma tentativa de phishing. Quando os usuários são cobertos por políticas do defender for Office 365 (anexos seguros, links seguros ou anti-phishing), as mensagens de entrada são avaliadas por vários modelos de aprendizado de máquina que analisam mensagens e a ação apropriada é executada, com base nas políticas configuradas.

### <a name="real-time-reports"></a>Relatórios em tempo real

Os recursos de monitoramento disponíveis no centro de conformidade e segurança & incluem [relatórios em tempo real e insights](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) que permitem que seus administradores de segurança e conformidade se concentrem em problemas de alta prioridade, como ataques de segurança ou uma maior atividade suspeita. Além de destacar áreas problemáticas, relatórios inteligentes e insights incluem recomendações e links para exibir e explorar dados e também realizar ações rápidas.

### <a name="explorer"></a>Explorador

O Explorador (também chamado de Explorador de Ameaças) é um relatório em tempo real que permite aos usuários autorizados identificar e analisar ameaças recentes. Por padrão, este relatório mostra dados dos últimos 7 dias, no entanto, os modos de exibição podem ser alterados para exibir dados dos últimos 30 dias.

O Explorer contém modos de exibição, como malware (para email e conteúdo), envios, Phish e todos os emails. Para ver como o Explorer compara com as detecções em tempo real, [Baixe este PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Para obter mais informações sobre o Explorer (no Microsoft defender para Office 365 plano 2) e sobre detecções em tempo real (no Microsoft defender para Office 365 plano 1), consulte [Threat Explorer and real-time detecções](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).

### <a name="real-time-detections"></a>Detecções em tempo real

As detecções em tempo real são um relatório em tempo real que permite aos usuários autorizados identificar e analisar ameaças recentes. Assim como o Explorador, esse relatório mostra os dados dos últimos 7 dias.

As detecções em tempo real contêm modos de exibição, como malware (para email e conteúdo), envios e phishing. Para ver como as detecções em tempo real são comparadas com o Explorer, [Baixe este PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Para obter mais informações sobre o Explorer (no Microsoft defender para Office 365 plano 2) e detecções em tempo real (no Microsoft defender para Office 365 plano 1), consulte [Threat Explorer (and real-time detecções)](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).

### <a name="threat-trackers"></a>Rastreadores de Ameaças

Os [rastreadores de ameaças](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) são widgets informativos e modos de exibição que oferecem aos usuários autorizados problemas de cybersecurity que podem afetar sua organização.

### <a name="automated-incident-response"></a>Resposta de incidente automatizada

Os recursos de [resposta de incidente automatizado](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) (Air) disponíveis no defender para Office 365 plano 2 permitem que você execute processos de investigação automatizados em resposta a ameaças bem conhecidas que existem hoje. Por meio de determinadas tarefas de investigação, a equipe de operações de segurança pode operar de forma mais eficiente e eficaz. As ações de correção, como excluir mensagens de email mal-intencionadas, são tomadas após a aprovação da equipe de operações de segurança. Para saber mais, veja [como o Air funciona no Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office).

### <a name="attack-simulator"></a>Simulador de Ataque

O [simulador de ataques](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) permite que os usuários autorizados executem cenários de ataque realísticos em sua organização. Vários tipos diferentes de ataques estão disponíveis, incluindo o nome de exibição de um ataque de spear-phishing, um ataque de irrigação de senha e um ataque de senha de força bruta.
