---
title: Descrição do serviço do Microsoft Defender para Office 365
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: ''
description: Saiba mais sobre os recursos disponíveis no Microsoft Defender para Office 365.
ms.openlocfilehash: a4f7fe00162dc15d7f01be831842066ef448546ad36197fb0551d85dbfba73ef
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 08/06/2021
ms.locfileid: "54663044"
---
# <a name="microsoft-defender-for-office-365-features-service-description"></a>Descrição do serviço do Microsoft Defender para Office 365

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Novidades do Microsoft Defender para Office 365

Estamos continuando a adicionar novos recursos ao Defender para Office 365. Para saber mais sobre os novos recursos que vêm para o Defender para Office 365 (ou Microsoft 365 em geral), consulte os seguintes recursos:

- [Roteiro do Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap)

- [Novidades no Microsoft Defender para Office 365 - Office 365 | Microsoft Docs](/microsoft-365/security/office-365-security/whats-new-in-defender-for-office-365)

## <a name="defender-for-office-365-capabilities"></a>Defender para Office 365 recursos

### <a name="safe-attachments"></a>Anexos seguros

[Cofre Anexos](/microsoft-365/security/office-365-security/atp-safe-attachments) protege contra malwares e vírus desconhecidos e fornece proteção de dia zero para proteger seu sistema de mensagens. Todas as mensagens e anexos que não têm uma assinatura de vírus/malware conhecida são roteadas para um ambiente especial em que o Defender para Office 365 usa uma variedade de técnicas de aprendizado e análise de máquina para detectar intenção mal-intencionada. Se nenhuma atividade suspeita for detectada, a mensagem será liberada para entrega na caixa de correio.

> [!NOTE]
> Cofre A verificação de anexos ocorre na mesma região em que seus dados Office 365 residem. Para obter mais informações sobre a geografia do data center, consulte [Where is your data located?](/microsoft-365/enterprise/o365-data-locations)

### <a name="safe-links"></a>Links seguros

O [Cofre de links](/microsoft-365/security/office-365-security/atp-safe-links) protege proativamente seus usuários contra URLs mal-intencionadas em uma mensagem ou em um documento Office. A proteção permanece sempre que eles selecionam o link, pois links mal-intencionados são bloqueados dinamicamente, enquanto o acesso a links legítimos é permitido.

Os links seguros estão disponíveis para URLs nos seguintes aplicativos:

- Microsoft 365 Apps para Grandes Empresas no Windows ou Mac

- Office na Web (Word para a Web, Excel para a Web, PowerPoint para a Web e OneNote para a Web)

- Word, Excel e PowerPoint no Windows

- Canais e chats do Microsoft Teams

> [!NOTE]
> Os usuários devem ser licenciados para o Defender para Office 365 , devem ser incluídos em políticas Cofre Links e devem estar conectados em seus dispositivos para que a proteção seja <sup>\*</sup> realizada.
>
> <sup>\*</sup>Para licenças do Defender em toda a organização Office 365 (por exemplo, ATP_ENTERPRISE_FACULTY), você não precisa atribuir o Defender para Office 365 licenças a usuários individuais.
>
> Para obter mais informações sobre Cofre de links, consulte [Cofre Links no Microsoft Defender para Office 365](/microsoft-365/security/office-365-security/atp-safe-links).

### <a name="safe-documents"></a>Documentos Seguros

O [Cofre de documentos](/microsoft-365/security/office-365-security/safe-docs) usa o Microsoft Defender para [Ponto](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) de Extremidade para examinar documentos e arquivos abertos [no Protected View](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653).

O que você precisa saber antes de começar?

- Cofre Os documentos agora estão geralmente disponíveis para usuários com Office versão 2004 (12730.x) ou superior! Esse recurso está desligado por padrão e precisará ser habilitado pelo Administrador de Segurança.

- Esse recurso só está disponível para usuários com a licença Microsoft 365 E5 ou Microsoft 365 E5 Security (não incluído no Defender para Office 365 planos).

- Word, Excel e PowerPoint no Windows

- Canais e chats do Microsoft Teams

> [!NOTE]
> Os usuários devem ser licenciados para Microsoft 365 E5 ou Microsoft 365 E5 Security , devem ser incluídos nas políticas Cofre Documentos e devem estar conectados em seus dispositivos para que a proteção seja <sup>\*</sup> realizada.
>
> Para obter mais informações sobre Cofre proteção de documentos, [consulte Cofre Documents no Microsoft 365 E5](/microsoft-365/security/office-365-security/safe-docs).

### <a name="protection-for-sharepoint-onedrive-and-microsoft-teams"></a>Proteção para SharePoint, OneDrive e Microsoft Teams

[A proteção para SharePoint, OneDrive](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) e Microsoft Teams ajuda a detectar e bloquear arquivos identificados como mal-intencionados em sites de equipe e bibliotecas de documentos. Além disso, Cofre proteção de Links agora está disponível Microsoft Teams canais e chats.

### <a name="anti-phishing-policies"></a>Políticas anti-phishing

[O anti-phishing](/microsoft-365/security/office-365-security/atp-anti-phishing) verifica as mensagens de entrada em busca de indicadores de que uma mensagem pode ser uma tentativa de phishing. Quando os usuários são abordados pelo Defender para políticas de Office 365 (anexos do Cofre, links Cofre ou anti-phishing), as mensagens de entrada são avaliadas por vários modelos de aprendizado de máquina que analisam mensagens e a ação apropriada é tomada, com base nas políticas configuradas.

### <a name="real-time-reports"></a>Relatórios em tempo real

Os recursos de monitoramento [](https://protection.office.com) disponíveis no Centro de Conformidade e Segurança & incluem relatórios e percepções em tempo [real](/microsoft-365/security/office-365-security/view-reports-for-atp) que permitem que seus administradores de segurança e conformidade se concentrem em problemas de alta prioridade, como ataques de segurança ou aumento de atividades suspeitas. Além de destacar áreas de problemas, relatórios inteligentes e insights incluem recomendações e links para exibir e explorar dados e também tomar ações rápidas.

### <a name="threat-explorer"></a>Explorador de Ameaças

O Explorador de Ameaças (também conhecido como Explorer) é um relatório em tempo real que permite que os usuários autorizados identifiquem e analisem ameaças recentes. Por padrão, este relatório mostra dados dos últimos sete dias; no entanto, as exibições podem ser modificadas para mostrar dados dos últimos 30 dias.

O Explorer contém exibições, como Malware (para email e conteúdo), Envios, Phishing e Todos os Emails. Para ver como o Explorer se compara às detecções em tempo real, [baixe este PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Para obter mais informações sobre o Explorer (no Microsoft Defender para Office 365 Plano 2) e detecções em tempo real (no Microsoft Defender para Office 365 Plano 1), consulte Threat Explorer e [detecções](/microsoft-365/security/office-365-security/threat-explorer)em tempo real .

### <a name="real-time-detections"></a>Detecções em tempo real

As detecções em tempo real são um relatório em tempo real que permite aos usuários autorizados identificar e analisar ameaças recentes. Semelhante ao Explorer, por padrão, este relatório mostra dados dos últimos sete dias.

As detecções em tempo real contêm exibições, como Malware (para email e conteúdo), Envios e Phishing. Para ver como as detecções em tempo real se comparam com o Explorer, [baixe este PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Para obter mais informações sobre o Explorer (no Microsoft Defender para Office 365 Plano 2) e detecções em tempo real (no Microsoft Defender para Office 365 Plano 1), consulte Threat Explorer e [detecções](/microsoft-365/security/office-365-security/threat-explorer)em tempo real .

### <a name="threat-trackers"></a>Rastreadores de Ameaças

[Os Rastreadores de Ameaças](/microsoft-365/security/office-365-security/threat-trackers) são widgets informativos e exibições que fornecem aos usuários autorizados informações sobre problemas de segurança cibernética que podem afetar sua organização.

### <a name="automated-investigation--response"></a>Resposta & investigação automatizada

[Os recursos](/microsoft-365/security/office-365-security/office-365-air) automatizados de & de resposta (AIR) disponíveis no Defender para Office 365 Plano 2 permitem que você execute processos de investigação automatizados em resposta a ameaças conhecidas que existem hoje. Automatizando determinadas tarefas de investigação, sua equipe de operações de segurança pode operar de forma mais eficiente e eficaz. As ações de correção, como a exclusão de mensagens de email mal-intencionadas, são tomadas após aprovação pela sua equipe de operações de segurança. Para saber mais, confira [Como o AIR funciona em Office 365](/microsoft-365/security/office-365-security/automated-investigation-response-office).

### <a name="attack-simulation-training"></a>Treinamento de simulação de ataque

[O treinamento de simulação de](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) ataque é uma ferramenta inteligente de gerenciamento de riscos sociais que automatiza a criação e o gerenciamento de simulações de phishing. As simulações ajudam os clientes a detectar, priorizar e correção de riscos de phishing usando iscas de phishing do mundo real e treinamento hiper-direcionado para alterar os comportamentos dos funcionários.

- O treinamento de simulação de ataque agora está disponível na WW e GCC (estará GCC a partir de 21 de junho).
- Para obter mais informações sobre como começar, consulte [Get started using Attack simulation training](/microsoft-365/security/office-365-security/attack-simulation-training-get-started).
- Várias técnicas de ataque que aplicam cargas de phishing desarmada e reais estão disponíveis que replicam o comportamento de invasor do mundo real para tornar as simulações de phishing relevantes.
- Esse serviço está disponível para organizações que têm licenças Microsoft 365 E5, Office 365 E5 ou Microsoft Defender para Office 365 [Plano 2.](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2) Um subconjunto de recursos é oferecido aos clientes E3 como uma avaliação.
- Para saber mais e experimentar uma simulação, consulte [Simular um ataque de phishing](/microsoft-365/security/office-365-security/attack-simulation-training).