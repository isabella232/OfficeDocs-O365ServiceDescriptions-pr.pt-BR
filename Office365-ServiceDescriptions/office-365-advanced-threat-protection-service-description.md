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
description: O Microsoft Defender for Office 365 é um serviço de filtragem de email baseado em nuvem que ajuda a proteger sua organização contra malwares e vírus desconhecidos, fornecendo proteção robusta de dia zero e inclui recursos para proteger sua organização contra links prejudiciais em tempo real.
ms.openlocfilehash: 2f93551be9df45e6108d81da9d7a50bba53be549
ms.sourcegitcommit: 25b208f02689d4ef4b37d36a49135c1b4b5a8204
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/07/2021
ms.locfileid: "52798447"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Descrição do serviço do Microsoft Defender para Office 365

O Microsoft Defender for Office 365 é um serviço de filtragem de email baseado em nuvem que ajuda a proteger sua organização contra malwares e vírus desconhecidos, fornecendo proteção robusta de dia zero e inclui recursos para proteger sua organização contra links prejudiciais em tempo real. O Defender para Office 365 possui recursos avançados de relatório e rastreamento de URL que dão aos administradores informações sobre o tipo de ataques que ocorrem em sua organização.

Veja a seguir as principais maneiras de usar o Defender para Office 365 proteção de mensagens:

- Em um cenário do Defender para Office 365 somente filtragem, o Defender for Office 365 fornece proteção de email baseada em nuvem para seu ambiente Exchange Server local ou qualquer outra solução de email SMTP local.

- O Defender Office 365 pode ser habilitado para proteger Exchange Online caixas de correio hospedadas na nuvem. Para saber mais sobre Exchange Online, consulte Exchange Online [descrição do serviço.](exchange-online-service-description/exchange-online-service-description.md)

- Em uma implantação híbrida, o Defender para Office 365 pode ser configurado para proteger seu ambiente de mensagens e controlar o roteamento de email quando você tiver uma combinação de caixas de correio locais e de nuvem com Proteção do Exchange Online para filtragem de email de entrada.

## <a name="microsoft-defender-for-office-365-availability"></a>Microsoft Defender para Office 365 disponibilidade

O Microsoft Defender para Office 365 Plano 2 está incluído no Office 365 E5, Office 365 A5, Microsoft 365 E5 Security e Microsoft 365 E5 conforme especificado aqui: [https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp](/microsoft-365/security/office-365-security/office-365-atp) . O Defender para Office 365 Plano 1 está incluído no Microsoft 365 Business Premium.

Você pode adicionar o Defender para Office 365 aos seguintes planos Exchange e Microsoft 365 assinatura:

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

Para comprar o Microsoft Defender para Office 365, consulte [Microsoft Defender for Office 365](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).

Para obter informações detalhadas sobre o plano de assinaturas que habilitam os usuários do Microsoft Defender para Office 365, consulte a tabela de comparação [de assinatura completa](https://go.microsoft.com/fwlink/?linkid=2139145).

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Novidades do Microsoft Defender para Office 365

Estamos continuando a adicionar novos recursos ao Defender para Office 365. Para saber mais sobre os novos recursos que vêm para o Defender para Office 365 (ou Microsoft 365 em geral), consulte os seguintes recursos:

- [Roteiro do Microsoft 365](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Novidades no Microsoft Defender para Office 365 - Office 365 | Microsoft Docs](/microsoft-365/security/office-365-security/whats-new-in-defender-for-office-365)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Requisitos do Microsoft Defender para Office 365

O Defender Office 365 pode ser usado com qualquer agente de transferência de email SMTP, como Microsoft Exchange Server. Para obter informações sobre os sistemas operacionais, navegadores da Web e idiomas com suporte do Defender para Office 365, consulte [as](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop)seções "Navegadores com suporte" e "Idiomas suportados" no centro de administração do Exchange em Proteção do Exchange Online .

## <a name="feature-availability-across-defender-for-office-365-plans"></a>Disponibilidade de recursos no Defender para Office 365 planos

Todos os recursos estão listados abaixo. Quando o Exchange Online é mencionado, ele normalmente refere-se à família de serviços do Office 365 Enterprise.<br><br>

| Recurso | Microsoft Defender para Office 365 Plano 1 | Microsoft Defender para Office 365 Plano 2 | Microsoft 365 E5 /A5 Security|
|:-----|:-----|:-----|:-----|
|*Configuração, proteção e detecção*|
|[Anexos seguros](#safe-attachments)|Sim|Sim|Sim|
|Cofre Anexos no Teams|Sim|Sim|Sim|
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
|[Treinamento de simulação de ataque](#attack-simulation-training)|Não|Sim|Sim|
|*Integração [com Microsoft 365 Defender](/microsoft-365/security/mtp/microsoft-threat-protection)*|Não|Sim|Sim|

> [!NOTE]
> Se o locatário tiver apenas o Microsoft Office Defender para uma licença de avaliação do Plano P2 ou uma licença de avaliação do Office 365 E5, sem outra licença qualificada para o Microsoft 365 Defender, você não poderá acessar o Microsoft 365 Defender. Para saber mais sobre a licença MTP, [consulte Microsoft 365 requisitos do Defender.](/microsoft-365/security/mtp/prerequisites)

## <a name="defender-for-office-365-capabilities"></a>Defender para Office 365 recursos

### <a name="safe-attachments"></a>Anexos seguros

[Cofre Anexos](/microsoft-365/security/office-365-security/atp-safe-attachments) protege contra malwares e vírus desconhecidos e fornece proteção de dia zero para proteger seu sistema de mensagens. Todas as mensagens e anexos que não têm uma assinatura de vírus/malware conhecida são roteadas para um ambiente especial em que o Defender para Office 365 usa uma variedade de técnicas de aprendizado e análise de máquina para detectar intenção mal-intencionada. Se nenhuma atividade suspeita for detectada, a mensagem será liberada para entrega na caixa de correio.

> [!NOTE]
> Cofre A verificação de anexos ocorre na mesma região em que seus dados Office 365 residem. Para obter mais informações sobre a geografia do data center, consulte [Where is your data located?](https://products.office.com/where-is-your-data-located?geo=All)

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

Do que você precisa saber para começar?

- Cofre Os documentos agora estão geralmente disponíveis para usuários com Office versão 2004 (12730.x) ou superior! Esse recurso está desligado por padrão e precisará ser habilitado pelo Administrador de Segurança.

- Esse recurso só está disponível para usuários com a licença Microsoft 365 E5 ou Microsoft 365 E5 Security (não incluído no Defender para Office 365 planos).

- Word, Excel e PowerPoint no Windows

- Canais e chats do Microsoft Teams

> [!NOTE]
> Os usuários devem ser licenciados para Microsoft 365 E5 ou Microsoft 365 E5 Security , devem ser incluídos nas políticas Cofre Documentos e devem estar conectados em seus dispositivos para que a proteção seja <sup>\*</sup> realizada.
>
> Para obter mais informações sobre Cofre proteção de documentos, [consulte Cofre Documents no Microsoft 365 E5](/microsoft-365/security/office-365-security/safe-docs).

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP para SharePoint, OneDrive e Microsoft Teams

[A ATP para SharePoint, OneDrive](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) e Microsoft Teams ajuda a detectar e bloquear arquivos identificados como mal-intencionados em sites de equipe e bibliotecas de documentos. Além disso, Cofre proteção de Links agora está disponível Microsoft Teams canais e chats.

### <a name="anti-phishing-policies"></a>Políticas anti-phishing

[O anti-phishing](/microsoft-365/security/office-365-security/atp-anti-phishing) verifica as mensagens de entrada em busca de indicadores de que uma mensagem pode ser uma tentativa de phishing. Quando os usuários são abordados pelo Defender para políticas de Office 365 (anexos do Cofre, links Cofre ou anti-phishing), as mensagens de entrada são avaliadas por vários modelos de aprendizado de máquina que analisam mensagens e a ação apropriada é tomada, com base nas políticas configuradas.

### <a name="real-time-reports"></a>Relatórios em tempo real

Os recursos de monitoramento disponíveis no Centro de Conformidade & segurança ( ) incluem relatórios e percepções em tempo real que permitem que seus administradores de segurança e conformidade se concentrem em problemas de alta prioridade, como ataques de segurança ou aumento de atividades [https://protection.office.com](https://protection.office.com) suspeitas. [](/microsoft-365/security/office-365-security/view-reports-for-atp) Além de destacar áreas de problemas, relatórios inteligentes e insights incluem recomendações e links para exibir e explorar dados e também tomar ações rápidas.

### <a name="explorer"></a>Explorador

O Explorador (também chamado de Explorador de Ameaças) é um relatório em tempo real que permite aos usuários autorizados identificar e analisar ameaças recentes. Por padrão, este relatório mostra dados dos últimos sete dias; no entanto, as exibições podem ser modificadas para mostrar dados dos últimos 30 dias.

O Explorer contém exibições, como Malware (para email e conteúdo), Envios, Phishing e Todos os Emails. Para ver como o Explorer se compara às detecções em tempo real, [baixe este PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Para obter mais informações sobre o Explorer (no Microsoft Defender para Office 365 Plano 2) e detecções em tempo real (no Microsoft Defender para Office 365 Plano 1), consulte Threat Explorer e [detecções](/microsoft-365/security/office-365-security/threat-explorer)em tempo real .

### <a name="real-time-detections"></a>Detecções em tempo real

As detecções em tempo real são um relatório em tempo real que permite aos usuários autorizados identificar e analisar ameaças recentes. Semelhante ao Explorer, por padrão, este relatório mostra dados dos últimos sete dias.

As detecções em tempo real contêm exibições, como Malware (para email e conteúdo), Envios e Phishing. Para ver como as detecções em tempo real se comparam com o Explorer, [baixe este PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Para obter mais informações sobre o Explorer (no Microsoft Defender para Office 365 Plano 2) e detecções em tempo real (no Microsoft Defender para Office 365 Plano 1), consulte [Threat Explorer (e detecções](/microsoft-365/security/office-365-security/threat-explorer)em tempo real) .

### <a name="threat-trackers"></a>Rastreadores de Ameaças

[Os Rastreadores de Ameaças](/microsoft-365/security/office-365-security/threat-trackers) são widgets informativos e exibições que fornecem aos usuários autorizados informações sobre problemas de segurança cibernética que podem afetar sua organização.

### <a name="automated-incident-response"></a>Resposta automatizada a incidentes

[Os recursos de](/microsoft-365/security/office-365-security/office-365-air) resposta a incidentes automatizados (AIR) disponíveis no Defender para Office 365 Plano 2 permitem que você execute processos de investigação automatizados em resposta a ameaças conhecidas que existem hoje. Ao automatizar determinadas tarefas de investigação, sua equipe de operações de segurança pode operar de forma mais eficiente e eficaz. As ações de correção, como a exclusão de mensagens de email mal-intencionadas, são tomadas após aprovação pela sua equipe de operações de segurança. Para saber mais, confira [Como o AIR funciona em Office 365](/microsoft-365/security/office-365-security/automated-investigation-response-office).

### <a name="attack-simulation-training"></a>Treinamento de simulação de ataque

[O treinamento de simulação de](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) ataque é uma ferramenta inteligente de gerenciamento de riscos sociais que automatiza a criação e o gerenciamento de simulações de phishing. As simulações ajudam os clientes a detectar, priorizar e correção de riscos de phishing usando iscas de phishing do mundo real e treinamento hiper-direcionado para alterar os comportamentos dos funcionários.

- O treinamento de simulação de ataque agora está disponível na WW e GCC (estará GCC a partir de 21 de junho).
- Para obter mais informações sobre como começar, consulte [Get started using Attack simulation training](/microsoft-365/security/office-365-security/attack-simulation-training-get-started).
- Várias técnicas de ataque que aplicam cargas de phishing desarmada e reais estão disponíveis que replicam o comportamento de invasor do mundo real para tornar as simulações de phishing relevantes.
- Esse serviço está disponível para organizações que têm licenças Microsoft 365 E5, Office 365 E5 ou Microsoft Defender para Office 365 [Plano 2.](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2) Um subconjunto de recursos é oferecido aos clientes E3 como uma avaliação.
- Para saber mais e experimentar uma simulação, consulte [Simular um ataque de phishing](/microsoft-365/security/office-365-security/attack-simulation-training).