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
description: Essa orientação é para profissionais de IT que estão orientando implantações do Office 365 em entidades do Governo Federal dos EUA ou outras entidades que lidam com dados sujeitos a regulamentos e requisitos governamentais, onde o uso do Microsoft 365 Government – DoD é apropriado para atender a esses requisitos.
ms.openlocfilehash: bc6d69c32db6801763e47984c0513da9c16ba0f8
ms.sourcegitcommit: adcacf68ac75c4db2229ebf55be9c75aecd3070b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52545998"
---
# <a name="plan-for-microsoft-365-compliance---dod-deployments"></a>Planejar a conformidade com o Microsoft 365 – implantações do DoD

Essa orientação é para profissionais de IT que estão orientando implantações do Office 365 em entidades do Governo Federal dos EUA ou outras entidades que lidam com dados sujeitos a regulamentos e requisitos governamentais, onde o uso do Microsoft 365 Government – DoD é apropriado para atender a esses requisitos.

> [!NOTE]
> Se a sua organização já tiver atendido aos requisitos de qualificação do Microsoft 365 – DoD e aplicado e aceito no programa, você poderá ignorar as etapas 1 e 2 e ir diretamente para a etapa 3.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---dod-and-meets-eligibility-requirements"></a>Etapa 1. Determinar se sua organização precisa Microsoft 365 Governo - DoD e atende aos requisitos de qualificação

O Microsoft 365 do Governo - Ambiente do DoD está em conformidade com os requisitos do Governo dos EUA para serviços de nuvem.

Além de aproveitar os recursos e recursos do Office 365, as organizações se beneficiam dos seguintes recursos exclusivos do Microsoft 365 Government – DoD:

- O conteúdo do cliente da sua organização é logicamente segregado do conteúdo do cliente nos serviços comerciais Office 365 da Microsoft.
- O conteúdo do cliente da sua organização é armazenado dentro dos Estados Unidos.
- O acesso ao conteúdo do cliente da sua organização é restrito à equipes selecionadas da Microsoft.
- Microsoft 365 Governo - O DoD está em conformidade com certificações e acreditações necessárias para clientes do setor público dos EUA.

Você pode encontrar mais informações sobre a oferta Microsoft 365 Government - DoD para clientes do Governo dos EUA em planos Office 365 Government [,](https://products.office.com/government/compare-office-365-government-plans)incluindo requisitos de qualificação.

A [Office 365 de serviço do Governo](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) dos EUA descreve os benefícios da plataforma, que são centralizados em atender aos requisitos de conformidade nos Estados Unidos.

> [!TIP]
> Talvez você queira transferir as tabelas de informações na descrição do serviço para uma Excel de trabalho e adicionar duas colunas: relevantes para minha organização **Y/N** e atende às necessidades da minha organização **Y/N**. Em seguida, você pode revisar essa lista com seus colegas para confirmar se esse serviço atende às necessidades da sua organização.

**Pontos de decisão**:<br/>
- *Decida se Microsoft 365 Governo - O DoD é apropriado para sua organização.*
- *Confirme se sua organização atende aos requisitos de qualificação.*

> [!NOTE]
> Microsoft 365 Government - O DoD só está disponível nos Estados Unidos. Os clientes do Governo não-EUA podem escolher entre vários planos [Office 365 Government .](https://products.office.com/government/compare-office-365-government-plans)

## <a name="step-2-apply-for-microsoft-365-government---dod"></a>Etapa 2. Aplicar-se Microsoft 365 Governo - DoD

Depois de decidir que esse serviço é o correto para sua organização, inicie o processo [de solicitação para este serviço](https://products.office.com/government/eligibility-validation).

## <a name="step-3-understand-microsoft-365-government---dod-default-security-settings"></a>Etapa 3. Entender Microsoft 365 Governo - Configurações de segurança padrão do DoD

Recomendamos que você tenha tempo para revisar cuidadosamente suas configurações de administração e segurança antes de modificá-las e considerar o impacto na conformidade antes de fazer alterações nas configurações de segurança padrão.

**Ponto de** decisão : decida se você modificará qualquer uma das configurações de segurança padrão Microsoft 365 *Government - DoD,* resolvendo primeiro entender o impacto de quaisquer alterações que você possa fazer.

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--dodsup1sup"></a>Etapa 4. Entender quais recursos estão indisponíveis ou desabilitados por padrão no Microsoft 365 Government – DoD<sup>1</sup>

Para atender aos requisitos de nossos clientes de nuvem governamental, há algumas diferenças entre o Microsoft 365 Government - DoD e planos empresariais. Consulte a tabela a seguir para ver quais recursos estão disponíveis. Confira [aqui](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) as atualizações mais recentes do produto de conformidade publicadas Microsoft 365 roteiro.<br><br>

| Área | Recurso | DoD Status |
|------|---------|------------|
| **Proteção de informações** | Cliente de rotulagem unificada e scanner | Disponível |
| | Match de dados exatos | Disponível |
| | Classificação automática e rotulagem para Exchange Online, SharePoint Online e OneDrive for Business | Em implantação |
| | Classificação automática e rotulagem para aplicativos Office (Word, Excel, PowerPoint, Outlook) em plataformas (Web, Windows e Mac) | Disponível |
| | Classificação automática e rotulagem para clientes Office - Mobile | No backlog de engenharia |
| | Classificação automática e rotulagem para Teams, Microsoft 365 grupos e SharePoint sites | Disponível |
| | Rotulagem obrigatória | Disponível |
| | Rotulagem de sensibilidade manual em Office aplicativos (iOS, Android, Windows) | Disponível |
| | Configuração de rótulo de sensibilidade para proteção somente criptografada em Outlook mensagens | Em implantação |
| **Analytics** | Classificação de dados: Visão geral e Explorador de Conteúdo | Em implantação |
| | Análise: classificadores de aprendizado de máquina com rotulagem automática no lado do serviço | No desenvolvimento |
| | Análise: classificadores de aprendizado de máquina com rotulagem automática Office aplicativos/lado do cliente | Em implantação |
| **Encryption** | Básico Criptografia de Mensagens do Office 365 (E3) | Disponível |
| | Advanced Criptografia de Mensagens do Office 365 (E5) | Disponível |
| | Traga sua própria chave (BYOK) para o ciclo de vida de provisionamento de chaves gerenciadas pelo cliente | Disponível |
| | Chave de Cliente do Office 365 | Disponível |
| | Criptografia de Chave Dupla | Disponível |
| **Prevenção contra perda de dados** | Prevenção contra perda de dados (DLP) para arquivos e email | Disponível |
| | DLP para Teams conversas de canal e chat | Disponível |
| | DLP: Painel de alertas | Em implantação |
| | Ponto de extremidade DLP | No desenvolvimento |
| | DLP On-prem | No backlog de engenharia |
| | Página Visão geral de DLP | No desenvolvimento |
| **Governança de informações** | Governança de informações: Arquivamento de Email | Disponível |
| | Governança de informações: bloqueio de preservação | Disponível |
| | Governança de informações: Importar PST | Disponível |
| | Governança de informações: aplicar rótulos de retenção não registrado manualmente | Disponível |
| | Governança de informações: aplicar rótulos de retenção padrão SharePoint/OneDrive for Business bibliotecas, pastas e conjuntos de documentos; Exchange caixas de entrada; e Office 365 Grupos | Disponível |
| | Governança de informações: aplicar um único rótulo de retenção padrão a toda a organização; locais ou usuários específicos; e automaticamente com base em uma condição específica (por exemplo, palavras-chave ou informações confidenciais) | Disponível |
| | Governança de informações: aplicar um rótulo padrão para Exchange caixas de entrada | Disponível |
| | Governança de informações: Revisão de disposição em vários estágios | No backlog de engenharia |
| | Governança de informações: políticas de retenção com classificadores com treinamento | No desenvolvimento |
| | Governança de informações: políticas de retenção para Teams chat | Em implantação |
| | Governança de informações: políticas de retenção para Teams de reunião | Disponível |
| | Governança de informações: políticas de retenção para Teams de canal privado | No backlog de engenharia |
| | Governança de informações: Escopos adaptáveis de políticas de retenção e rotulagem | No desenvolvimento |
| | Gerenciamento de registros: aplicar o rótulo de registro manualmente | Disponível |
| | Gerenciamento de registros: aplicar um rótulo de registro padrão para SharePoint, OneDrive for Business bibliotecas, pastas e conjuntos de documentos; e Office 365 grupos | Disponível |
| | Gerenciamento de registros: políticas de registro automático com base em condições específicas (por exemplo, palavras-chave ou informações confidenciais); e com base em um evento | Disponível |
| | Gerenciamento de registros: Revisão de disposição | Disponível |
| | Gerenciamento de registros: Gerenciador de plano de arquivos | Disponível |
| | Gerenciamento de registros: Prova de descarte | Disponível |
| | Gerenciamento de registros: controle de versão de registros | Disponível |
| | Gerenciamento de registros: registros regulatórios | Disponível |
| | Gerenciamento de registros: use SharePoint classificação syntex para aplicar rótulos de registro | No backlog de engenharia |
| **Gerenciamento de riscos insider** | Sistema de Proteção de Dados do cliente | Disponível |
| | Gerenciamento de riscos insider: painel de caso, Explorador de Conteúdo e modelos de aviso | Em implantação |
| | Insider Risk Management: Escalone para investigação para Advanced eDiscovery | Em implantação |
| | Insider Risk Management: Roubo de dados ao separar usuários | Em implantação |
| | Insider Risk Management: Vazamentos gerais de dados | Em implantação |
| | Gerenciamento de riscos do Insider: investigar alertas de gerenciamento de riscos insider | Em implantação |
| | Gerenciamento de Riscos do Insider: Office indicadores para Teams, SharePoint sites, mensagens de email | Em implantação |
| | Insider Risk Management Activity Explorer | No backlog de engenharia |
| | Gerenciamento de Riscos do Insider: Indicadores de dispositivos para atividade Windows 10 Build 1809 e superior | No backlog de engenharia |
| | Gerenciamento de riscos do Insider: indicadores para alertas do Microsoft Defender para ponto de extremidade | No backlog de engenharia |
| | Insider Risk Management: Indicadores para violação de política de segurança | No backlog de engenharia |
| | Insider Risk Management: modelos de política para vazamentos de dados por usuários insatisfeitos | No backlog de engenharia |
| | Gerenciamento de riscos do Insider: modelos de política para vazamentos de dados por usuários prioritários | No backlog de engenharia |
| | Insider Risk Management: Modelos de política para violações gerais de política de segurança | No backlog de engenharia |
| | Insider Risk Management: modelos de política para violações de política de segurança por usuários prioritários, usuários de saída, usuários insatisfeitos (visualização) | No backlog de engenharia |
| | Insider Risk Management: Personalização de política | No backlog de engenharia |
| | Insider Risk Management: Exportar alertas | No backlog de engenharia |
| | Insider Risk Management: Microsoft Teams integração | No backlog de engenharia |
| | Gerenciamento de Riscos Do Insider: Grupos de usuários prioritários | No backlog de engenharia |
| | Conformidade de Comunicação: Criar políticas de cliente, 3 pré-configuradas | Disponível |
| | Conformidade de comunicação: suporte para Teams, Exchange e remover Teams mensagem | Disponível |
| | Conformidade de comunicação: alertas de acesso; modelos de aviso; painel de política de comunicação | Disponível |
| | Conformidade de comunicação: Escalonar para investigação para Advanced eDiscovery | Disponível |
| | Conformidade de comunicação: detecta violação de código de conduta repetido ao longo do tempo | Disponível |
| | Conformidade de Comunicação: Suporte para permissões mais granulares | Disponível |
| | Conformidade de comunicação: analisar Teams dados de chat de usuários com caixa de correio no site | Disponível |
| | Conformidade de Comunicação: Modelo de conflito de interesse | Disponível |
| | Conformidade de comunicação: capacidade de ignorar assinatura de email ou aviso de isenção de responsabilidade | No desenvolvimento |
| | Conformidade de comunicação: capacidade de definir um período de retenção para uma política de Conformidade de Comunicação | No backlog de engenharia |
| | Conformidade de Comunicação: Detectar conteúdo adulto | No backlog de engenharia |
| | Conformidade de Comunicação: Entrega de gerenciamento de riscos do Insider | No desenvolvimento |
| | Conformidade de comunicação: verificação de saúde da política e capacidade de pausar política | No desenvolvimento |
| | Conformidade de Comunicação: Suporte a 7 idiomas para ameaças, assédio direcionado e classificadores de profanidades | No desenvolvimento |
| | Conformidade de comunicação: traduzir conteúdo de saúde durante a investigação | No desenvolvimento |
| | Barreiras de informações | Em implantação |
| | Gerenciamento de acesso privilegiado | No backlog de engenharia |
| **Descobrir & responder** | Descoberta Principal: Preservação in-local | Disponível |
| | Descoberta Principal: Gerenciamento de Caso | Disponível |
| | Descoberta Principal da Descoberta e: Pesquisa | Disponível |
| | Descoberta Principal: Exportar | Disponível |
| | Descoberta Principal de EDiscovery: descriptografia rms | Disponível |
| | Descoberta Principal: Exportação nativa | Disponível |
| | Descoberta Interna: Auditoria | Disponível |
| | Descoberta Principal: Limites de conformidade para OneDrive for Business | Em implantação |
| | Advanced eDiscovery: Processamento avançado | Disponível |
| | Advanced eDiscovery: suporte a byte CJK/Double para Advanced eDiscovery | Disponível |
| | Advanced eDiscovery: Custodiatário para mapeamento de carga de trabalho | Disponível |
| | Advanced eDiscovery: Comunicações custodiais | Disponível |
| | Advanced eDiscovery: Painel | Disponível |
| | Advanced eDiscovery: threading de email | Disponível |
| | Advanced eDiscovery: Exportar (baixar, exportar, adicionar a outro conjunto de revisão) | Disponível |
| | Advanced eDiscovery: Filtragem | Disponível |
| | Advanced eDiscovery: identificação quase duplicada | Disponível |
| | Advanced eDiscovery: codificação preditiva | Disponível |
| | Advanced eDiscovery: Exportação processada com arquivo de carga | Disponível |
| | Advanced eDiscovery: Redactions | Disponível |
| | Advanced eDiscovery: Conjuntos de revisão | Disponível |
| | Advanced eDiscovery: Revisar e anotar | Disponível |
| | Advanced eDiscovery: Relatório de Termos de Pesquisa | Disponível |
| | Advanced eDiscovery: suporte ao conteúdo vinculado do OneDrive e SharePoint Online (anexos modernos) | Disponível |
| | Advanced eDiscovery: Marcação | Disponível |
| | Advanced eDiscovery: suporte Teams reações | Disponível |
| | Advanced eDiscovery: relatórios de locatários | Disponível |
| | Advanced eDiscovery: Temas | Disponível |
| | Advanced eDiscovery: Visualizadores | Disponível |
| | Advanced eDiscovery: Yammer Advanced eDiscovery no Centro de Conformidade da Microsoft | Disponível |
| | Advanced eDiscovery: otimizações de espera | No desenvolvimento |
| | Advanced eDiscovery: o Centro de Conformidade da Microsoft expandiu o suporte para pesquisar e exportar itens em SharePoint, OneDrive for Business, Lixeira no Core e Advanced eDiscovery | No desenvolvimento |
| | Advanced eDiscovery: Responsabilidade legal para Teams de canais privados | No desenvolvimento |
| | Advanced eDiscovery: Novo módulo de codificação preditiva | No desenvolvimento |
| | Advanced eDiscovery: ingestão Office 365 não Office 365 | No backlog de engenharia |
| | Advanced eDiscovery: relatórios de locatários | No desenvolvimento |
| | Auditoria básica | Disponível |
| | Auditoria Avançada: acesso a eventos cruciais (por exemplo, mailitemsaccessed) | Disponível |
| | Auditoria Avançada: Maior largura de banda para API de atividade de gerenciamento | Disponível |
| | Auditoria Avançada: Retenção de log (1 ano) | Disponível |
| | Auditoria Avançada: eventos de envio de email e envio de emails | Disponível |
| | Auditoria Avançada: Disponibilidade do Centro de Conformidade e Segurança | Disponível |
| | Auditoria Avançada: retenção de longo prazo em logs de auditoria (10 anos) | No desenvolvimento |
| | Auditoria Avançada: eventos de termos de pesquisa no Exchange Online e SharePoint Online | No backlog de engenharia |
| **Gerenciamento de Conformidade** | Microsoft 365 Centro de Segurança e Conformidade | Disponível |
| | Microsoft Cloud App Security | No desenvolvimento |
| | Gerenciador de Conformidade | Disponível |
| | Suporte a caracteres de byte duplo | Disponível |
| **Ecossistema** | Conectores de dados de primeira parte: RH | Disponível |
| | Conectores de dados de primeira parte: Instant Bloomberg, Bloomberg Mail, LinkedIn Business pages, ICE Chat | No backlog de engenharia |
| | Conectores de dados de terceiros | No backlog de engenharia |
| | Graph APIs para Advanced eDiscovery | No desenvolvimento |
| | Graph APIs para Teams exportar dados | No backlog de engenharia |

<sup>1</sup> O status identificado está sujeito a alterações à medida que os planos e prioridades do projeto são reavaliados.<br/>

**Ponto de decisão:** *decida se os recursos de conformidade atendem às necessidades da sua organização.*
