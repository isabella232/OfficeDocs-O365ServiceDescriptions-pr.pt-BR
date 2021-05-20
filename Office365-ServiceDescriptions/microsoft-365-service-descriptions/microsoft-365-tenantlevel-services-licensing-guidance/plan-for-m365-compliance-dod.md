---
title: Planejar a conformidade com o Microsoft 365 – implantações do DoD
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Essa orientação é para profissionais de TI que estão conduzindo implantações de Office 365 em entidades do governo federal dos EUA ou outras entidades que lidam com dados que estão sujeitos a regulamentos e requisitos governamentais, onde o uso de Microsoft 365 Governo – O DoD é apropriado para atender a esses requisitos.
ms.openlocfilehash: bc6d69c32db6801763e47984c0513da9c16ba0f8
ms.sourcegitcommit: adcacf68ac75c4db2229ebf55be9c75aecd3070b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52545998"
---
# <a name="plan-for-microsoft-365-compliance---dod-deployments"></a>Planejar a conformidade com o Microsoft 365 – implantações do DoD

Essa orientação é para profissionais de TI que estão conduzindo implantações de Office 365 em entidades do governo federal dos EUA ou outras entidades que lidam com dados que estão sujeitos a regulamentos e requisitos governamentais, onde o uso de Microsoft 365 Governo – O DoD é apropriado para atender a esses requisitos.

> [!NOTE]
> Se sua organização já cumpriu os requisitos de elegibilidade Microsoft 365 Governo – DoD e se candidatou e foi aceito no programa, você pode pular as etapas 1 e 2 e ir diretamente para a etapa 3.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---dod-and-meets-eligibility-requirements"></a>Etapa 1. Determine se sua organização precisa de Microsoft 365 Governo - DoD e atenda aos requisitos de elegibilidade

O ambiente Microsoft 365 Governo - DoD cumpre os requisitos do governo dos EUA para serviços em nuvem.

Além de desfrutar dos recursos e capacidades de Office 365, as organizações se beneficiam dos seguintes recursos exclusivos do Governo Microsoft 365 – DoD:

- O conteúdo do cliente da sua organização é logicamente segregado do conteúdo do cliente nos serviços de Office 365 comerciais da Microsoft.
- O conteúdo do cliente da sua organização é armazenado dentro dos Estados Unidos.
- O acesso ao conteúdo do cliente da sua organização é restrito à equipes selecionadas da Microsoft.
- Microsoft 365 Governo - O DoD cumpre as certificações e credenciamentos necessários para os clientes do setor público dos EUA.

Você pode encontrar mais informações sobre o governo Microsoft 365 - Oferta do DoD para clientes do governo dos EUA [em planos Office 365 Government](https://products.office.com/government/compare-office-365-government-plans), incluindo requisitos de elegibilidade.

A [descrição Office 365 serviço do governo dos EUA](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) descreve os benefícios da plataforma, que estão centrados no cumprimento dos requisitos de conformidade nos Estados Unidos.

> [!TIP]
> Você pode querer transferir as tabelas de informações na descrição do serviço para uma Excel livro de trabalho e adicionar duas colunas: **Relevante para minha organização Y/N** e atende às necessidades da minha organização **Y/N**. Em seguida, você pode rever esta lista com seus colegas para confirmar que este serviço atende às necessidades da sua organização.

**Pontos de decisão**:<br/>
- *Decida se Microsoft 365 Governo - O DoD é apropriado para sua organização.*
- *Confirme se sua organização atende aos requisitos de elegibilidade.*

> [!NOTE]
> Microsoft 365 Governo - O DoD só está disponível nos Estados Unidos. Os clientes do governo não-norte-americano podem escolher entre uma série de [planos Office 365 Government](https://products.office.com/government/compare-office-365-government-plans).

## <a name="step-2-apply-for-microsoft-365-government---dod"></a>Etapa 2. Inscreva-se para Microsoft 365 Governo - DoD

Tendo decidido que esse serviço é adequado para sua organização, inicie o processo de [solicitação desse serviço.](https://products.office.com/government/eligibility-validation)

## <a name="step-3-understand-microsoft-365-government---dod-default-security-settings"></a>Etapa 3. Entenda Microsoft 365 Governo - Configurações de segurança padrão do DoD

Recomendamos que você tenha tempo para revisar cuidadosamente suas configurações de administração e segurança antes de modificá-las e considerar o impacto na conformidade antes de fazer quaisquer alterações nas configurações de segurança padrão.

**Ponto de decisão**: *Decida se você modificará alguma das configurações de segurança padrão Microsoft 365 Governo - DoD, resolvendo primeiro entender o impacto de quaisquer alterações que você possa fazer.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--dodsup1sup"></a>Etapa 4. Entenda quais recursos estão atualmente indisponíveis ou desativados por padrão no Governo Microsoft 365 – DoD<sup>1</sup>

Para atender aos requisitos de nossos clientes de nuvem do governo, existem algumas diferenças entre Microsoft 365 Governo - DoD e planos corporativos. Consulte a tabela a seguir para ver quais recursos estão disponíveis. Veja [aqui](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) as últimas atualizações de produtos de conformidade publicadas no roteiro Microsoft 365.<br><br>

| Área | Recurso | DoD Status |
|------|---------|------------|
| **Proteção de informações** | Cliente e scanner de rotulagem unificados | Disponível |
| | Correspondência exata de dados | Disponível |
| | Classificação automática e rotulagem para Exchange Online, SharePoint Online e OneDrive for Business | Em implantação |
| | Classificação automática e rotulagem para aplicativos de Office (Word, Excel, PowerPoint, Outlook) em todas as plataformas (web, Windows e Mac) | Disponível |
| | Classificação automática e rotulagem para clientes Office - Mobile | Em backlog de engenharia |
| | Classificação automática e rotulagem para sites de Teams, Microsoft 365 e SharePoint | Disponível |
| | Rotulagem obrigatória | Disponível |
| | Rotulagem de sensibilidade manual em aplicativos Office (iOS, Android, Windows) | Disponível |
| | Configuração de etiqueta de sensibilidade para proteção somente criptografada em mensagens Outlook | Em implantação |
| **Analytics** | Classificação de dados: Visão geral e explorador de conteúdo | Em implantação |
| | Analytics: Classificadores de aprendizado de máquina com rotulagem automática no lado do serviço | Em desenvolvimento |
| | Analytics: Classificadores de aprendizado de máquina com rotulagem automática em Office aplicativos/lado do cliente | Em implantação |
| **Encryption** | Criptografia de Mensagens do Office 365 Básica (E3) | Disponível |
| | Criptografia de Mensagens do Office 365 Avançada (E5) | Disponível |
| | Traga sua própria chave (BYOK) para o ciclo de vida de provisionamento de chaves gerenciado pelo cliente | Disponível |
| | Chave de Cliente do Office 365 | Disponível |
| | Criptografia de Chave Dupla | Disponível |
| **Prevenção contra perda de dados** | Prevenção de perda de dados (DLP) para arquivos e e-mail | Disponível |
| | DLP para Teams conversas de bate-papo e canal | Disponível |
| | DLP: Painel de alertas | Em implantação |
| | Ponto final do DLP | Em desenvolvimento |
| | DLP On-prem | Em backlog de engenharia |
| | Página de visão geral do DLP | Em desenvolvimento |
| **Governança de informações** | Governança de informações: Arquivamento de e-mails | Disponível |
| | Governança da informação: Bloqueio de preservação | Disponível |
| | Governança da informação: Importação PST | Disponível |
| | Governança de informações: Aplique etiquetas de retenção de não-registros manualmente | Disponível |
| | Governança de informações: Aplique etiquetas de retenção padrão para bibliotecas, pastas e conjuntos de documentos de SharePoint/OneDrive for Business; caixas de entrada Exchange; e grupos Office 365 | Disponível |
| | Governança de informações: Aplique um único rótulo de retenção padrão a toda a organização; locais ou usuários específicos; e automaticamente com base em condições específicas (por exemplo, palavras-chave ou informações confidenciais) | Disponível |
| | Governança da informação: Aplique um rótulo padrão para caixas de entrada Exchange | Disponível |
| | Governança da informação: Revisão de disposição em vários estágios | Em backlog de engenharia |
| | Governança da informação: Políticas de retenção com classificadores de classe capacitáveis | Em desenvolvimento |
| | Governança da informação: Políticas de retenção para Teams chat | Em implantação |
| | Governança da informação: Políticas de retenção para gravação de Teams de reunião | Disponível |
| | Governança da informação: Políticas de retenção para Teams mensagens de canais privados | Em backlog de engenharia |
| | Governança de informações: Políticas de retenção e rotulagem de escopos adaptativos | Em desenvolvimento |
| | Gerenciamento de registros: Aplique etiqueta de gravação manualmente | Disponível |
| | Gerenciamento de registros: Aplique uma etiqueta de registro padrão para SharePoint, bibliotecas de OneDrive for Business, pastas e conjuntos de documentos; e grupos Office 365 | Disponível |
| | Gerenciamento de registros: Políticas automáticas de registro baseadas em condições específicas (por exemplo, palavras-chave ou informações confidenciais); e com base em um evento | Disponível |
| | Gerenciamento de registros: Revisão de descarte | Disponível |
| | Gerenciamento de registros: Gerenciador de planos de arquivos | Disponível |
| | Gerenciamento de registros: Comprovante de descarte | Disponível |
| | Gerenciamento de registros: Versão de registros | Disponível |
| | Gerenciamento de registros: Registros regulatórios | Disponível |
| | Gerenciamento de registros: Use SharePoint classificação Syntex para aplicar gravadoras | Em backlog de engenharia |
| **Gerenciamento de risco interno** | Sistema de Proteção de Dados do cliente | Disponível |
| | Gerenciamento de risco interno: painel de casos, explorador de conteúdo e modelos de aviso | Em implantação |
| | Gestão de riscos internos: intensificação para investigação de Advanced eDiscovery | Em implantação |
| | Insider Risk Management: Roubo de dados por usuários que partem | Em implantação |
| | Gerenciamento de riscos insider: vazamentos gerais de dados | Em implantação |
| | Insider Risk Management: investigue alertas de gerenciamento de riscos de insider | Em implantação |
| | Insider Risk Management: indicadores de Office para Teams, sites de SharePoint, mensagens de e-mail | Em implantação |
| | Explorador de atividades de gerenciamento de risco insider | Em backlog de engenharia |
| | Gerenciamento de risco interno: indicadores de dispositivos para atividade na Windows 10 Build 1809 e superior | Em backlog de engenharia |
| | Insider Risk Management: Indicadores para o Microsoft Defender para alertas de endpoint | Em backlog de engenharia |
| | Gerenciamento de riscos internos: Indicadores para violação de políticas de segurança | Em backlog de engenharia |
| | Insider Risk Management: Modelos de políticas para vazamentos de dados por usuários descontentes | Em backlog de engenharia |
| | Insider Risk Management: Modelos de políticas para vazamentos de dados por usuários prioritários | Em backlog de engenharia |
| | Gerenciamento de riscos internos: modelos de políticas para violações de políticas gerais de segurança | Em backlog de engenharia |
| | Insider Risk Management: Modelos de políticas para violações de políticas de segurança por usuários prioritários, usuários que saem, usuários descontentes (visualização) | Em backlog de engenharia |
| | Gerenciamento de riscos privilegiado: personalização de políticas | Em backlog de engenharia |
| | Gerenciamento de riscos internos: alertas de exportação | Em backlog de engenharia |
| | Gerenciamento de riscos insider: integração Microsoft Teams | Em backlog de engenharia |
| | Gerenciamento de riscos privilegiados: grupos de usuários prioritários | Em backlog de engenharia |
| | Conformidade com a comunicação: Crie políticas de clientes, 3 pré-configuradas | Disponível |
| | Conformidade de comunicação: Suporte para Teams, Exchange e remover mensagem Teams | Disponível |
| | Conformidade de Comunicação: Alertas de acesso; modelos de aviso; painel política de comunicação | Disponível |
| | Conformidade com a Comunicação: Intensificação para investigação de Advanced eDiscovery | Disponível |
| | Conformidade com a comunicação: detecta violação de código de conduta repetida ao longo do tempo | Disponível |
| | Conformidade com a comunicação: Suporte para permissões mais granulares | Disponível |
| | Conformidade com a comunicação: analise Teams dados de bate-papo dos usuários com caixa de correio on-prem | Disponível |
| | Conformidade de Comunicação: Modelo de conflito de interesses | Disponível |
| | Conformidade com a comunicação: Capacidade de ignorar assinatura de e-mail ou isenção de responsabilidade | Em desenvolvimento |
| | Conformidade com a comunicação: Capacidade de definir um período de retenção para uma política de conformidade de comunicação | Em backlog de engenharia |
| | Conformidade com a comunicação: detecte conteúdo adulto | Em backlog de engenharia |
| | Conformidade com a comunicação: entrega de gerenciamento de riscos insider | Em desenvolvimento |
| | Conformidade com a comunicação: Verificação de política de saúde e capacidade de pausar a política | Em desenvolvimento |
| | Conformidade com a comunicação: Suporte 7 idiomas para ameaças, assédio direcionado e classificadores de palavrões | Em desenvolvimento |
| | Conformidade com a Comunicação: Traduza conteúdo em saúde durante a investigação | Em desenvolvimento |
| | Barreiras de informações | Em implantação |
| | Gerenciamento de acesso privilegiado | Em backlog de engenharia |
| **Descubra & responder** | Núcleo de eDiscovery: Preservação no local | Disponível |
| | Core eDiscovery: Gerenciamento de casos | Disponível |
| | Core eDiscovery: Pesquisa | Disponível |
| | Núcleo de eDiscovery: Exportação | Disponível |
| | Core eDiscovery: descriptografia RMS | Disponível |
| | Core eDiscovery: Exportação nativa | Disponível |
| | Core eDiscovery: Auditoria | Disponível |
| | Core eDiscovery: Limites de conformidade para OneDrive for Business | Em implantação |
| | Advanced eDiscovery: Processamento avançado | Disponível |
| | Advanced eDiscovery: Suporte de byte CJK/Double para Advanced eDiscovery | Disponível |
| | Advanced eDiscovery: Custodiante para mapeamento de carga de trabalho | Disponível |
| | Advanced eDiscovery: Comunicações de custódia | Disponível |
| | Advanced eDiscovery: Painel | Disponível |
| | Advanced eDiscovery: Threading de e-mail | Disponível |
| | Advanced eDiscovery: Exportar (baixar, exportar, adicionar a outro conjunto de revisão) | Disponível |
| | Advanced eDiscovery: Filtragem | Disponível |
| | Advanced eDiscovery: Identificação quase duplicada | Disponível |
| | Advanced eDiscovery: Codificação preditiva | Disponível |
| | Advanced eDiscovery: Exportação processada com arquivo de carga | Disponível |
| | Advanced eDiscovery: Redações | Disponível |
| | Advanced eDiscovery: Conjuntos de revisão | Disponível |
| | Advanced eDiscovery: Reveja e anote | Disponível |
| | Advanced eDiscovery: Relatório do Termo de Pesquisa | Disponível |
| | Advanced eDiscovery: Suporte ao conteúdo vinculado de OneDrive e SharePoint Online (anexos modernos) | Disponível |
| | Advanced eDiscovery: Marcação | Disponível |
| | Advanced eDiscovery: apoio de reações Teams | Disponível |
| | Advanced eDiscovery: Relatórios de inquilinos | Disponível |
| | Advanced eDiscovery: Temas | Disponível |
| | Advanced eDiscovery: Telespectadores | Disponível |
| | Advanced eDiscovery: Yammer Advanced eDiscovery no Microsoft Compliance Center | Disponível |
| | Advanced eDiscovery: Manter otimizações | Em desenvolvimento |
| | Advanced eDiscovery: o Microsoft Compliance Center expandiu o suporte para pesquisa e exportação de itens em SharePoint, OneDrive for Business, Lixeira em Núcleo e Advanced eDiscovery | Em desenvolvimento |
| | Advanced eDiscovery: Ação legal para Teams mensagens de canais privados | Em desenvolvimento |
| | Advanced eDiscovery: Novo módulo de codificação preditiva | Em desenvolvimento |
| | Advanced eDiscovery: Ingestão não Office 365 | Em backlog de engenharia |
| | Advanced eDiscovery: Relatórios de inquilinos | Em desenvolvimento |
| | Auditoria básica | Disponível |
| | Auditoria Avançada: Acesso a eventos cruciais (por exemplo, mailitemsaccessed) | Disponível |
| | Auditoria Avançada: Aumento da largura de banda para API de atividade de gerenciamento | Disponível |
| | Auditoria Avançada: Retenção de log (1 ano) | Disponível |
| | Auditoria Avançada: Envio de correio e envio de correio | Disponível |
| | Auditoria Avançada: Disponibilidade do Centro de Segurança e Conformidade | Disponível |
| | Auditoria Avançada: Retenção de longo prazo em logs de auditoria (10 anos) | Em desenvolvimento |
| | Auditoria Avançada: Pesquise eventos de termo em Exchange Online e SharePoint Online | Em backlog de engenharia |
| **Gerenciamento de Conformidade** | Microsoft 365 Centro de Segurança e Conformidade | Disponível |
| | Microsoft Cloud App Security | Em desenvolvimento |
| | Gerenciador de Conformidade | Disponível |
| | Suporte de caractere duplo byte | Disponível |
| **ecossistema** | Conectores de dados de primeira parte: HR | Disponível |
| | Conectores de dados de primeira parte: Instant Bloomberg, Bloomberg Mail, LinkedIn Business pages, ICE Chat | Em backlog de engenharia |
| | Conectores de dados de terceiros | Em backlog de engenharia |
| | Graph APIs para Advanced eDiscovery | Em desenvolvimento |
| | Graph APIs para dados de exportação de Teams | Em backlog de engenharia |

<sup>1</sup> O status identificado está sujeito a alterações à medida que os planos e prioridades do projeto são reavaliados.<br/>

**Ponto de decisão**: *Decida se os recursos de conformidade atendem às necessidades da sua organização.*
