---
title: Planejar a conformidade com o Microsoft 365 – GCC High
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: Esta orientação é para profissionais de IT que estão conduzindo implantações do Office 365 em entidades do Governo Federal dos EUA ou outras entidades que lidam com dados sujeitos a regulamentos e requisitos governamentais, onde o uso do Microsoft 365 Government – GCC High é apropriado para atender a esses requisitos.
ms.openlocfilehash: 9237de0625a481ce8f82411ad3f8ac384a9acf63
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/24/2021
ms.locfileid: "59670380"
---
# <a name="plan-for-microsoft-365-compliance--gcc-high"></a>Plan for Microsoft 365 compliance – GCC High

Esta orientação é para profissionais de IT que estão conduzindo implantações do Office 365 em entidades do Governo Federal dos EUA ou outras entidades que lidam com dados sujeitos a regulamentos e requisitos governamentais, onde o uso do Microsoft 365 Government – GCC High é apropriado para atender a esses requisitos.

> [!NOTE]
>Se Microsoft 365 sua organização já tiver atendido aos requisitos de alta qualificação do GCC e aplicados e aceitos no programa, você poderá ignorar as etapas 1 e 2 e ir diretamente para a etapa 3.
 
## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government--gcc-high-and-meets-eligibility-requirements"></a>Etapa 1. Determinar se sua organização precisa Microsoft 365 Governo – GCC Alta e atende aos requisitos de qualificação

O Microsoft 365 Government - GCC ambiente high está em conformidade com os requisitos do Governo dos EUA para serviços de nuvem. Além de aproveitar os recursos e recursos do Office 365, as organizações se beneficiam dos seguintes recursos exclusivos do Microsoft 365 Government – GCC High:

- O conteúdo do cliente da sua organização é logicamente segregado do conteúdo do cliente nos serviços comerciais Office 365 da Microsoft.
- O conteúdo do cliente da sua organização é armazenado dentro dos Estados Unidos.
- O acesso ao conteúdo do cliente da sua organização é restrito à equipes selecionadas da Microsoft.
- Microsoft 365 Governo – GCC Alta está em conformidade com certificações e acreditações necessárias para clientes do setor público dos EUA.

Você pode encontrar mais informações sobre a Microsoft 365 do GCC alta oferta para clientes do Governo dos EUA em Office 365 Government [planos,](https://products.office.com/government/compare-office-365-government-plans)incluindo requisitos de qualificação.

A [Office 365 de serviço do Governo](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) dos EUA descreve os benefícios da plataforma, que são centralizados em atender aos requisitos de conformidade nos Estados Unidos.

> [!TIP]
> Talvez você queira transferir as tabelas de informações na descrição do serviço para uma Excel de trabalho e adicionar duas colunas: relevantes para minha organização **Y/N** e atende às necessidades da minha organização **Y/N**. Em seguida, você pode revisar essa lista com seus colegas para confirmar se esse serviço atende às necessidades da sua organização.

**Pontos de decisão**:<br/>

- *Decida se Microsoft 365 governo – GCC-High é apropriado para sua organização.*
- *Confirme se sua organização atende aos requisitos de qualificação.*

> [!NOTE]
> Microsoft 365 Government - GCC High só está disponível nos Estados Unidos. Os clientes do Governo não-EUA podem escolher entre vários planos [Office 365 Government .](https://products.office.com/government/compare-office-365-government-plans)

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>Etapa 2. Aplicar-se Microsoft 365 Governo – GCC-High

Depois de decidir que esse serviço é o correto para sua organização, inicie o processo [de solicitação para este serviço](https://products.office.com/government/eligibility-validation).

## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>Etapa 3. Entender Microsoft 365 Governo – GCC-High configurações de segurança padrão

Recomendamos que você tenha tempo para revisar cuidadosamente suas configurações de administração e segurança antes de modificá-las e considerar o impacto na conformidade antes de fazer alterações nas configurações de segurança padrão.

**Ponto de** decisão : decida se você modificará qualquer uma das configurações padrão Microsoft 365 Government – GCC-High de segurança, resolvendo primeiro entender o impacto de quaisquer alterações que você *possa fazer.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-highsup1sup"></a>Etapa 4. Entender quais recursos estão atualmente indisponíveis ou desabilitados por padrão no Microsoft 365 Government – GCC-High<sup>1</sup>

Para atender aos requisitos de nossos clientes de nuvem governamental, há algumas diferenças entre Microsoft 365 Government – GCC-High e planos empresariais. Consulte a tabela a seguir para ver quais recursos estão disponíveis. Confira [aqui](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) as atualizações mais recentes do produto de conformidade publicadas no Microsoft 365 roteiro.<br><br>

| Área | Recurso | GCC Alto Status |
|------|---------|-----------------|
| **Proteção de informações** |  |  |
| Tipos de informações confidenciais | Match de dados exatos | Disponível |
| Rotulagem de sensibilidade | Cliente de rotulagem unificada e scanner  | Disponível |
|  | Classificação automática e rotulagem para Exchange Online, SharePoint Online e OneDrive | Disponível |
|  | Classificação automática e rotulagem para aplicativos Office (Word, Excel, PowerPoint, Outlook) na Web, Windows e Mac | Disponível |
|  | Classificação automática e rotulagem para Office clientes (Mobile) | No backlog de engenharia |
|  | Classificação automática e rotulagem para Teams, Microsoft 365 grupos e SharePoint sites | Disponível |
| Análise | Análise de classificação de dados: Visão geral e Explorador de Conteúdo | Disponível |
|  | Auditoria e análise em Office aplicativos | Disponível |
|  | Análise: classificadores de aprendizado de máquina com rotulagem automática Office aplicativos/lado do cliente | No desenvolvimento |
| Criptografia | Básico Criptografia de Mensagens do Office 365 (E3) | Disponível |
|  | Advanced Criptografia de Mensagens do Office 365 (E5) | Disponível |
|  | Chave de Cliente do Office 365 | Disponível |
|  | Chave do cliente para Microsoft 365 criptografia de várias cargas de trabalho | No desenvolvimento |
|  | Chave do cliente para SharePoint Online e OneDrive for Business | Disponível |
|  | Traga sua própria chave (BYOK) para o ciclo de vida de provisionamento de chaves gerenciadas pelo cliente | Disponível |
|  | Criptografia de Chave Dupla | Disponível |
|  | Exchange Online de serviço usando chaves gerenciadas da Microsoft | Disponível |
| Prevenção contra perda de dados | Prevenção contra perda de dados (DLP) para arquivos e email | Disponível |
|  | DLP para Teams conversas de canal e chat | Disponível |
|  | Ponto de extremidade DLP | Visualização pública |
|  | Painel de alertas de DLP e experiência de alerta | Disponível |
|  | Página Visão geral de DLP | Em implantação |
| **Governança de informações** |  |  |
| Governança de informações | Governança de informações: escopos adaptáveis para políticas de retenção e rotulagem | No backlog de engenharia |
| | Governança de informações: Arquivamento de Email | Disponível |
| | Governança de informações: Rótulos de retenção padrão para SharePoint/OneDrive for Business bibliotecas, pastas e conjuntos de documentos; Exchange caixas de entrada; e Office 365 Grupos | Disponível |
| | Governança de informações: Importar PST | Disponível |
| | Governança de informações: Rótulos manuais de retenção não registrado | Disponível |
| | Governança de informações: bloqueio de preservação | Disponível |
| | Governança de informações: políticas de retenção para toda a organização; locais ou usuários específicos; automaticamente com base em condições específicas (por exemplo, palavras-chave ou informações confidenciais); e com base em um evento | Disponível |
| | Governança de informações: políticas de retenção para Teams (chat) | Disponível |
| | Governança de informações: políticas de retenção para Teams de reunião | Disponível |
| | Governança de informações: políticas de retenção para Teams canais privados | Disponível |
| | Governança de informações: políticas de retenção para Teams canais compartilhados | No backlog de engenharia |
| | Governança de informações: políticas de retenção para Yammer | No backlog de engenharia |
| Gerenciamento de registros | Gerenciamento de registros: capacidade de excluir um rótulo de registro | Disponível |
| | Gerenciamento de registros: aplicar um rótulo de registro manualmente | Disponível |
| | Gerenciamento de registros: aplicar rótulos de registro padrão para SharePoint, OneDrive for Business bibliotecas, pastas e conjuntos de documentos; e Office 365 grupos | Disponível |
| | Gerenciamento de registros: aplicar políticas de registro automaticamente com base em condições específicas (por exemplo, palavras-chave ou informações confidenciais); e com base em um evento | Disponível |
| | Gerenciamento de registros: Revisão de disposição | Disponível |
| | Gerenciamento de registros: Gerenciador de plano de arquivos | Disponível |
| | Gerenciamento de registros: revisão de disposição em vários estágios | No desenvolvimento |
| | Gerenciamento de registros: preservação e rotulagem automática de anexos de nuvem | No desenvolvimento |
| | Gerenciamento de registros: Prova de descarte | Disponível |
| | Gerenciamento de registros: preservação e rotulagem automática de anexos de nuvem | No backlog de engenharia |
| | Gerenciamento de registros: controle de versão de registros | Disponível |
| | Gerenciamento de registros: registros regulatórios | Disponível |
| **Gerenciamento de risco** |  |  |
| Sistema de Proteção de Dados do cliente | Sistema de Proteção de Dados do cliente | Disponível |
| Conformidade em comunicações | Conformidade de comunicação: capacidade de definir um período de retenção para uma política de Conformidade de Comunicação | No desenvolvimento |
| | Conformidade de comunicação: alertas de acesso; modelos de aviso; painel de política de comunicação | Disponível |
| | Conformidade de comunicação: analisar Teams dados de chat de usuários com caixa de correio no site | Disponível |
| | Conformidade de Comunicação: Modelo de conflito de interesse | Disponível |
| | Conformidade de Comunicação: Criar políticas de cliente, 3 pré-configuradas | Disponível |
| | Conformidade de Comunicação: Detectar conteúdo adulto | No backlog de engenharia |
| | Conformidade de comunicação: detecta violação de código de conduta repetido ao longo do tempo | Disponível |
| | Conformidade de comunicação: Escalonar para investigação para Advanced eDiscovery | Disponível |
| | Conformidade de comunicação: aproveitar o reconhecimento óptico de caracteres para extrair e avaliar mensagens | Disponível |
| | Conformidade de comunicação: verificação de saúde da política e capacidade de pausar política | No desenvolvimento |
| | Conformidade de comunicação: Power Automate integração | No desenvolvimento |
| | Conformidade de comunicação: remover Teams mensagem | Disponível |
| | Conformidade de comunicação: tipos de informações confidenciais por relatório de localização  | No desenvolvimento |
| | Conformidade de comunicação: oferece suporte a sete idiomas para ameaças, assédio direcionado e classificadores de profanidades | Disponível |
| | Conformidade de Comunicação: Suporte para permissões mais granulares | Disponível |
| | Conformidade de comunicação: suporte para Teams, Exchange e capacidade de remover Teams mensagem | Disponível |
| | Conformidade de comunicação: Teams de conversa | No backlog de engenharia |
| | Conformidade de comunicação: traduzir conteúdo durante a investigação | No backlog de engenharia |
| Barreiras de informações | Barreiras de informações | Em implantação |
| Gerenciamento de riscos internos | Insider Risk Management: Log de auditoria | Visualização pública |
| | Insider Risk Management: Painel de caso | Disponível |
| | Gerenciamento de riscos do Insider: aprimoramentos do Explorador de Conteúdo e do Explorador de Conteúdo | Disponível |
| | Gerenciamento de riscos do Insider: dados que surgiram no Explorador de Atividades | Disponível |
| | Insider Risk Management: Roubo de dados ao separar usuários | Disponível |
| | Gerenciamento de Riscos Do Insider: Indicadores de dispositivo para atividade Windows 10 pontos de extremidade | Visualização pública |
| | Insider Risk Management: Escalone para investigação para Advanced eDiscovery | Disponível |
| | Insider Risk Management: Exportar alertas | Visualização pública |
| | Insider Risk Management: Vazamentos gerais de dados | Disponível |
| | Insider Risk Management: Indicadores para violação de política de segurança | No desenvolvimento |
| | Gerenciamento de riscos do Insider: indicadores para alertas do Microsoft Defender para ponto de extremidade | No backlog de engenharia |
| | Gerenciamento de riscos insider: indicadores para Windows 10 de pontos de extremidade | Visualização Pública  |
| | Gerenciamento de Riscos Do Insider: Suporte inteligente para configurações de domínio no Gerenciamento de Riscos do Insider | Visualização pública |
| | Gerenciamento de riscos do Insider: investigar alertas de gerenciamento de riscos insider | Disponível |
| | Insider Risk Management: Microsoft Teams Power Automate integração | No desenvolvimento |
| | Gerenciamento de riscos do Insider: o nativo dispara o suporte para Azure Active Directory exclusão de conta | Visualização pública |
| | Gerenciamento de riscos do Insider: modelos de aviso | Disponível |
| | Gerenciamento de Riscos do Insider: Office indicadores para Teams, SharePoint sites, mensagens de email | Disponível |
| | Gerenciamento de riscos do Insider: modelos de política para vazamentos de dados por usuários prioritários | Visualização pública |
| | Insider Risk Management: Modelos de política para violações gerais de política de segurança | No backlog de engenharia |
| | Insider Risk Management: modelos de política para violações de política de segurança por usuários prioritários e usuários de saída | Visualização pública |
| | Insider Risk Management: modelos de política para violações de política de segurança por usuários insatisfeitos | No backlog de engenharia |
| | Insider Risk Management: Personalização de política, verificação de saúde da política e assistente de criação de política aprimorado | Visualização pública |
| | Gerenciamento de Riscos Do Insider: Grupos de usuários prioritários | No backlog de engenharia |
| | Gerenciamento de Riscos do Insider: trilha de auditoria "Assista aos watchers" | Disponível |
| **Descobrir &amp; responder** |  |  |
| Descoberta eletrônica | Descoberta Interna: Auditoria | Disponível |
| | Descoberta Principal: Gerenciamento de Caso | Disponível |
| | Descoberta Principal da Descoberta e: Limites de conformidade no OneDrive for Business | Disponível |
| | Descoberta Principal: Exportar | Disponível |
| | Descoberta Principal: Preservação in-local | Disponível |
| | Descoberta Principal: Exportação nativa | Disponível |
| | Descoberta Principal de EDiscovery: descriptografia rms | Disponível |
| | Descoberta Principal da Descoberta e: Pesquisa | Disponível |
| | Advanced eDiscovery: Processamento avançado | Disponível |
| | Advanced eDiscovery: Custodiatário para mapeamento de carga de trabalho | Disponível |
| | Advanced eDiscovery: Comunicações custodiais | Disponível |
| | Advanced eDiscovery: Painel | Disponível |
| | Advanced eDiscovery: recursos de limpeza de dados para Microsoft Teams  | No backlog de engenharia |
| | Advanced eDiscovery: rastreamento/indexação profunda | Disponível |
| | Advanced eDiscovery: suporte de byte duplo para chinês, japonês e coreano | Disponível |
| | Advanced eDiscovery: threading de email | Disponível |
| | Advanced eDiscovery: Exportar (baixar, exportar, adicionar a outro conjunto de revisão) | Disponível |
| | Advanced eDiscovery: Filtragem | Disponível |
| | Advanced eDiscovery: otimizações de espera | No desenvolvimento |
| | Advanced eDiscovery: Responsabilidade legal para Teams de canais privados | No desenvolvimento |
| | Advanced eDiscovery: o Centro de Conformidade da Microsoft expandiu o suporte para pesquisar e exportar itens em SharePoint e OneDrive for Business Lixeira | No desenvolvimento |
| | Advanced eDiscovery: identificação quase duplicada | Disponível |
| | Advanced eDiscovery: nova experiência de exportação para Core e Advanced eDiscovery  | No desenvolvimento |
| | Advanced eDiscovery: Novo módulo de codificação preditiva | No backlog de engenharia |
| | Advanced eDiscovery: fontes de dados não custodiais | Disponível |
| | Advanced eDiscovery: ingestão Office 365 não Office 365 | Disponível |
| | Advanced eDiscovery: codificação preditiva | Disponível |
| | Advanced eDiscovery: Exportação processada com arquivo de carga | Disponível |
| | Advanced eDiscovery: Redactions | Disponível |
| | Advanced eDiscovery: Conjuntos de revisão | Disponível |
| | Advanced eDiscovery: Revisar dados (dados de consulta, marcas inteligentes, painel) e anotações (redact) | Disponível |
| | Advanced eDiscovery: Relatório de Termos de Pesquisa | Disponível |
| | Advanced eDiscovery: Correção de erro de item único | Disponível |
| | Advanced eDiscovery: suporte à exportação PST | Disponível |
| | Advanced eDiscovery: suporte ao conteúdo vinculado do OneDrive e SharePoint Online (anexos modernos) | Disponível |
| | Advanced eDiscovery: suporte Teams reações | No backlog de engenharia |
| | Advanced eDiscovery: Marcação | Disponível |
| | Advanced eDiscovery: relatórios de locatários | Disponível |
| | Advanced eDiscovery: Temas | Disponível |
| | Advanced eDiscovery: Visualizadores | Disponível |
| | Advanced eDiscovery: Yammer Advanced eDiscovery no Centro de Conformidade da Microsoft | Disponível |
| Auditoria | Auditoria básica | Disponível |
| | Auditoria Avançada: Acesso a eventos cruciais (por exemplo, *MailItemsAccessed*) | Disponível |
| | Auditoria Avançada: Maior largura de banda para API de atividade de gerenciamento | Disponível |
| | Auditoria Avançada: espera legal para Teams de canais privados | Disponível |
| | Auditoria Avançada: Retenção de log (1 ano) | Disponível |
| | Auditoria Avançada: retenção de longo prazo em logs de auditoria (10 anos) | Em implantação |
| | Auditoria Avançada: eventos de envio de email e envio de emails | Disponível |
| | Auditoria Avançada: Microsoft 365 disponibilidade do Centro de Conformidade e Segurança | Disponível |
| | Auditoria Avançada: eventos de termos de pesquisa no Exchange Online e SharePoint Online | No desenvolvimento |
| | Auditoria Avançada: Teams reações em mensagens | No backlog de engenharia |
| **Gerenciamento de Conformidade** |  |  |
| Gerenciamento de Conformidade | Centro de conformidade do Microsoft 365 | Disponível |
| | Gerenciador de Conformidade | Disponível |
| | Suporte a caracteres de byte duplo | Disponível |
| | Microsoft Cloud App Security | Disponível |
| **Ecossistema** |  |  |
| Ecossistema | Conectores de dados de primeira parte: RH  | No desenvolvimento |
| | Conectores de dados de primeira parte: problemas físicos | No desenvolvimento |
| | Graph APIs para Advanced eDiscovery  | No desenvolvimento |

<sup>1</sup> O status identificado está sujeito a alterações à medida que os planos e prioridades do projeto são reavaliados.<br/>

**Ponto de decisão:** *decida se os recursos de conformidade atendem às necessidades da sua organização.*
