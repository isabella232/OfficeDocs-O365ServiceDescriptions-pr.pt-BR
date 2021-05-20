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
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: O Microsoft Defender for Office 365 é um serviço de filtragem de e-mails baseado em nuvem que ajuda a proteger sua organização contra malwares e vírus desconhecidos, fornecendo proteção robusta de zero-day, e inclui recursos para proteger sua organização de links prejudiciais em tempo real.
ms.openlocfilehash: 76b4d2e53c8a2942d4b974c5289c9ae4c8854b72
ms.sourcegitcommit: adcacf68ac75c4db2229ebf55be9c75aecd3070b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52545968"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Descrição do serviço do Microsoft Defender para Office 365

O Microsoft Defender for Office 365 é um serviço de filtragem de e-mails baseado em nuvem que ajuda a proteger sua organização contra malwares e vírus desconhecidos, fornecendo proteção robusta de zero-day, e inclui recursos para proteger sua organização de links prejudiciais em tempo real. O Defender for Office 365 possui recursos ricos de rastreamento de relatórios e URL que dão aos administradores uma visão do tipo de ataques que acontecem em sua organização.

A seguir, as principais maneiras que você pode usar o Defender para Office 365 para proteção de mensagens:

- Em um cenário defender for Office 365 somente filtragem, o Defender for Office 365 fornece proteção de e-mail baseada em nuvem para seu ambiente Exchange Server local ou qualquer outra solução de e-mail SMTP no local.

- O Defender for Office 365 pode ser habilitado para proteger Exchange Online caixas de correio hospedadas na nuvem. Para saber mais sobre Exchange Online, consulte a [descrição do serviço Exchange Online](exchange-online-service-description/exchange-online-service-description.md).

- Em uma implantação híbrida, o Defender for Office 365 pode ser configurado para proteger seu ambiente de mensagens e controlar o roteamento de e-mails quando você tiver uma mistura de caixas de correio no local e na nuvem com Proteção do Exchange Online para filtragem de e-mails de entrada.

## <a name="microsoft-defender-for-office-365-availability"></a>Microsoft Defender para disponibilidade de Office 365

O Microsoft Defender for Office 365 Plan 2 está incluído em Office 365 E5, Office 365 A5, Microsoft 365 E5 Security e Microsoft 365 E5 conforme especificado aqui: [https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp](/microsoft-365/security/office-365-security/office-365-atp) . Defensor do Plano 1 Office 365 está incluído em Microsoft 365 Business Premium.

Você pode adicionar o Defender para Office 365 aos seguintes planos de assinatura Exchange e Microsoft 365:

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

Para comprar o Microsoft Defender por Office 365, consulte [o Microsoft Defender para Office 365](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).

Para obter informações detalhadas sobre as assinaturas que permitem aos usuários do Microsoft Defender para Office 365, consulte a [tabela completa de comparação de assinaturas](https://go.microsoft.com/fwlink/?linkid=2139145).

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>O que há de novo no Microsoft Defender para Office 365

Continuamos adicionando novos recursos ao Defender para Office 365. Para saber mais sobre os novos recursos que chegam ao Defender para Office 365 (ou Microsoft 365 em geral), consulte os seguintes recursos:

- [Roteiro do Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [O que há de novo no Microsoft Defender para Office 365](/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Requisitos para o Microsoft Defender para Office 365

O Defender for Office 365 pode ser usado com qualquer agente de transferência de correio SMTP, como Microsoft Exchange Server. Para obter informações sobre os sistemas operacionais, navegadores da Web e idiomas suportados pelo Defender for Office 365, consulte as seções "Navegadores suportados" e "Idiomas suportados" em [Exchange centro administrativo em Proteção do Exchange Online](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop).

## <a name="feature-availability-across-defender-for-office-365-plans"></a>Disponibilidade de recursos no Defender para planos de Office 365

Todos os recursos estão listados abaixo. Quando o Exchange Online é mencionado, ele normalmente refere-se à família de serviços do Office 365 Enterprise.<br><br>

| Recurso | Microsoft Defender para Office 365 Plano 1 | Microsoft Defender para Office 365 Plano 2 | Microsoft 365 E5 / Segurança A5|
|:-----|:-----|:-----|:-----|
|*Configuração, proteção e detecção*|
|[Anexos seguros](#safe-attachments)|Sim|Sim|Sim|
|Cofre Anexos em Teams|Sim|Sim|Sim|
|[Links Seguros](#safe-links)|Sim|Sim|Sim|
|[Documentos Seguros](#safe-documents)|Não|Não|Sim|
|Links Seguros no Teams|Sim|Sim|Sim|
|[ATP para SharePoint, OneDrive e Microsoft Teams](#atp-for-sharepoint-onedrive-and-microsoft-teams)|Sim|Sim|Sim|
|[Políticas anti-phishing](#anti-phishing-policies)|Sim|Sim|Sim|
|[Relatórios em tempo real](#real-time-reports)|Sim|Sim|Sim|
|*Automação, investigação, remediação e educação*|
|[Controladores de Ameaças](#threat-trackers)|Não|Sim|Sim|
|Investigação de ameaças (investigação avançada de ameaças)|[Detecções em tempo real](#real-time-detections)|[Explorador](#explorer)|[Explorador](#explorer)|
|[Resposta automatizada a incidentes](#automated-incident-response)|Não|Sim|Sim|
|[Treinamento de simulação de ataque](#attack-simulation-training)|Não|Sim|Sim|
|*Integração com [Microsoft 365 Defender](/microsoft-365/security/mtp/microsoft-threat-protection)*|Não|Sim|Sim|

> [!NOTE]
> Se o seu inquilino tiver apenas o Microsoft Defender para Office licença de teste Do Plano P2 ou Office 365 licença de teste E5, sem outra licença elegível para Microsoft 365 Defender, você não poderá acessar Microsoft 365 Defender. Para saber mais sobre a licença MTP, consulte [Microsoft 365 os requisitos do Defender](/microsoft-365/security/mtp/prerequisites).

## <a name="defender-for-office-365-capabilities"></a>Defender para recursos de Office 365

### <a name="safe-attachments"></a>Anexos seguros

[Cofre Attachments](/microsoft-365/security/office-365-security/atp-safe-attachments) protege contra malwares e vírus desconhecidos e fornece proteção de zero-day para proteger seu sistema de mensagens. Todas as mensagens e anexos que não possuem uma assinatura conhecida de vírus/malware são encaminhados para um ambiente especial onde o Defender for Office 365 usa uma variedade de técnicas de aprendizado de máquina e análise para detectar intenções maliciosas. Se nenhuma atividade suspeita for detectada, a mensagem será liberada para entrega na caixa de correio.

> [!NOTE]
> Cofre A varredura de anexos ocorre na mesma região onde reside o Office 365 dados. Para obter mais informações sobre a geografia do data center, consulte [onde estão seus dados?](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>Links seguros

O recurso [Cofre Links](/microsoft-365/security/office-365-security/atp-safe-links) protege proativamente seus usuários de URLs mal-intencionados em uma mensagem ou em um documento Office. A proteção permanece sempre que eles selecionam o link, pois links mal-intencionados são bloqueados dinamicamente, enquanto o acesso a links legítimos é permitido.

Os links seguros estão disponíveis para URLs nos seguintes aplicativos:

- Microsoft 365 Apps para Grandes Empresas em Windows ou Mac

- Office na Web (Word para a Web, Excel para a Web, PowerPoint para a Web e OneNote para a Web)

- Palavra, Excel e PowerPoint sobre Windows

- Canais e chats do Microsoft Teams

> [!NOTE]
> Os usuários devem ser licenciados para o Defender para Office 365 <sup>\*</sup> , devem ser incluídos nas políticas de links Cofre e devem ser assinados em seus dispositivos para que a proteção esteja em vigor.
>
> <sup>\*</sup>Para licenças de Office 365 em toda a organização (por exemplo, ATP_ENTERPRISE_FACULTY), você não precisa atribuir o Defender para licenças de Office 365 a usuários individuais.
>
> Para obter mais informações sobre a proteção de links Cofre, consulte [Cofre Links no Microsoft Defender for Office 365](/microsoft-365/security/office-365-security/atp-safe-links).

### <a name="safe-documents"></a>Documentos Seguros

O recurso [Cofre Documentos](/microsoft-365/security/office-365-security/safe-docs) usa o Microsoft Defender [para endpoint](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) para digitalizar documentos e arquivos que são abertos no [Protected View](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653).

O que você precisa saber antes de começar?

- Cofre Os documentos agora estão geralmente disponíveis para usuários com Office Versão 2004 (12730.x) ou superior! Esse recurso está desligado por padrão e precisará ser ativado pelo Administrador de Segurança.

- Esse recurso só está disponível para usuários com a licença Microsoft 365 E5 ou Microsoft 365 E5 Security (não incluída no Defender para Office 365 planos).

- Palavra, Excel e PowerPoint sobre Windows

- Canais e chats do Microsoft Teams

> [!NOTE]
> Os usuários devem ser licenciados para Microsoft 365 E5 ou Microsoft 365 E5 Security <sup>\*</sup> , devem ser incluídos nas políticas de documentos Cofre e devem ser assinados em seus dispositivos para que a proteção esteja em vigor.
>
> Para obter mais informações sobre proteção de documentos Cofre, consulte [Cofre Documentos em Microsoft 365 E5](/microsoft-365/security/office-365-security/safe-docs).

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP para SharePoint, OneDrive e Microsoft Teams

[ATP para SharePoint, OneDrive e Microsoft Teams](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) ajuda a detectar e bloquear arquivos que são identificados como maliciosos em sites de equipe e bibliotecas de documentos. Além disso, a proteção Cofre Links já está disponível em canais e chats Microsoft Teams.

### <a name="anti-phishing-policies"></a>Políticas anti-phishing

[O anti-phishing](/microsoft-365/security/office-365-security/atp-anti-phishing) verifica as mensagens recebidas para obter indicadores de que uma mensagem pode ser uma tentativa de phishing. Quando os usuários são cobertos pelo Defender para políticas de Office 365 (Cofre Anexos, links de Cofre ou anti-phishing), as mensagens recebidas são avaliadas por vários modelos de aprendizado de máquina que analisam mensagens e as medidas apropriadas são tomadas, com base nas políticas configuradas.

### <a name="real-time-reports"></a>Relatórios em tempo real

Os recursos de monitoramento disponíveis no Centro de Conformidade de & de Segurança [https://protection.office.com](https://protection.office.com) () incluem [relatórios e insights](/microsoft-365/security/office-365-security/view-reports-for-atp) em tempo real que permitem que seus administradores de segurança e conformidade se concentrem em questões de alta prioridade, como ataques de segurança ou aumento de atividades suspeitas. Além de destacar áreas problemáticas, relatórios inteligentes e insights incluem recomendações e links para visualizar e explorar dados e também tomar ações rápidas.

### <a name="explorer"></a>Explorador

O Explorador (também chamado de Explorador de Ameaças) é um relatório em tempo real que permite aos usuários autorizados identificar e analisar ameaças recentes. Por padrão, este relatório mostra dados dos últimos sete dias; no entanto, as visualizações podem ser modificadas para mostrar dados nos últimos 30 dias.

O Explorer contém visualizações, como Malware (para e-mail e conteúdo), Submissions, Phish e All Email. Para ver como o Explorer se compara com as detecções em tempo real, [baixe este PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Para obter mais informações sobre o Explorer (no Microsoft Defender for Office 365 Plan 2) e detecções em tempo real (no Microsoft Defender for Office 365 Plan 1), consulte [o Threat Explorer e as detecções](/microsoft-365/security/office-365-security/threat-explorer)em tempo real.

### <a name="real-time-detections"></a>Detecções em tempo real

As detecções em tempo real são um relatório em tempo real que permite aos usuários autorizados identificar e analisar ameaças recentes. Semelhante ao Explorer, por padrão, este relatório mostra dados dos últimos sete dias.

As detecções em tempo real contêm visualizações, como Malware (para e-mail e conteúdo), Submissions e Phish. Para ver como as detecções em tempo real se comparam com o Explorer, [baixe este PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Para obter mais informações sobre o Explorer (no Microsoft Defender for Office 365 Plan 2) e detecções em tempo real (no Microsoft Defender for Office 365 Plan 1), consulte [o Threat Explorer (e detecções em tempo real)](/microsoft-365/security/office-365-security/threat-explorer).

### <a name="threat-trackers"></a>Rastreadores de Ameaças

[Threat Trackers](/microsoft-365/security/office-365-security/threat-trackers) são widgets informativos e visualizações que fornecem aos usuários autorizados informações sobre problemas de segurança cibernética que podem afetar sua organização.

### <a name="automated-incident-response"></a>Resposta automatizada a incidentes

Os recursos [automatizados de resposta](/microsoft-365/security/office-365-security/office-365-air) a incidentes (AIR) disponíveis no Defender para Office 365 Plano 2 permitem executar processos automatizados de investigação em resposta a ameaças bem conhecidas que existem hoje. Ao automatizar certas tarefas de investigação, sua equipe de operações de segurança pode operar de forma mais eficiente e eficaz. Ações de remediação, como a exclusão de mensagens de e-mail maliciosas, são tomadas após aprovação de sua equipe de operações de segurança. Para saber mais, veja [como funciona o AIR em Office 365](/microsoft-365/security/office-365-security/automated-investigation-response-office).

### <a name="attack-simulation-training"></a>Treinamento de simulação de ataque

[O treinamento de simulação de](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) ataque é uma ferramenta inteligente de gerenciamento de riscos sociais que automatiza a criação e o gerenciamento de simulações de phishing. As simulações ajudam os clientes a detectar, priorizar e remediar riscos de phishing usando iscas de phish do mundo real e treinamentos hiper-direcionados para mudar o comportamento dos funcionários.

- O treinamento de simulação de ataque já está disponível na WW e GCC (estará em GCC a partir de 21 de junho).
- Para obter mais informações sobre como começar, consulte [Comece a usar o treinamento de simulação de ataque](/microsoft-365/security/office-365-security/attack-simulation-training-get-started).
- Várias técnicas de ataque que aplicam cargas de phish desarmadas e reais estão disponíveis que replicam o comportamento do atacante do mundo real para tornar as simulações de phishing relevantes.
- Este serviço está disponível para organizações que têm licenças Microsoft 365 E5, Office 365 E5 ou [Microsoft Defender para Office 365 licenças do Plano 2.](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2) Um subconjunto de recursos é oferecido aos clientes E3 como um teste.
- Para saber mais e experimentar uma simulação, consulte [Simular um ataque de phishing](/microsoft-365/security/office-365-security/attack-simulation-training).