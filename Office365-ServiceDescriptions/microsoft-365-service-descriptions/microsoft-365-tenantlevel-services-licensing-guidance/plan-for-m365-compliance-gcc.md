---
title: Planejar a conformidade com o Microsoft 365 – GCC
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Esta orientação é para profissionais de IT que estão conduzindo implantações do Office 365 em entidades governamentais federais, estaduais, locais, tribais ou territoriais dos EUA ou outras entidades que lidam com dados sujeitos a regulamentos e requisitos governamentais, onde o uso do Microsoft 365 Government - GCC é apropriado para atender a esses requisitos.
ms.openlocfilehash: cf5a5caa5cf0793141e7498006aff1224fbcc659
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652625"
---
# <a name="plan-for-microsoft-365-compliance--gcc"></a>Planejar a conformidade do Microsoft 365 – GCC

Esta orientação é para profissionais de IT que estão conduzindo implantações do Office 365 em entidades governamentais federais, estaduais, locais, tribais ou territoriais dos EUA ou outras entidades que lidam com dados sujeitos a regulamentos e requisitos governamentais, onde o uso do Microsoft 365 Government - GCC é apropriado para atender a esses requisitos.

> [!NOTE]
> Se sua organização já tiver atendido aos requisitos de qualificação do Microsoft 365 Government - GCC e tiver sido aplicada e aceita no programa, você poderá ignorar as etapas 1 e 2 e ir diretamente para a etapa 3.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---gcc-and-meets-eligibility-requirements"></a>Etapa 1. Determinar se sua organização precisa do Microsoft 365 Government - GCC e atende aos requisitos de qualificação

O ambiente governo do Microsoft 365 - GCC está em conformidade com os requisitos do governo dos EUA para serviços de nuvem, incluindo FedRAMP Moderado e requisitos para a justiça criminal e sistemas de informações fiscais federais (tipos de dados CJI e FTI).

Além de aproveitar os recursos e recursos do Office 365, as organizações se beneficiam dos seguintes recursos exclusivos do Microsoft 365 Government - GCC:

- O conteúdo do cliente da sua organização é logicamente segregado do conteúdo do cliente nos serviços comerciais do Office 365 da Microsoft.

- O conteúdo do cliente da sua organização é armazenado dentro dos Estados Unidos.

- O acesso ao conteúdo do cliente da sua organização é restrito à equipes selecionadas da Microsoft.

- Microsoft 365 Government - GCC está em conformidade com certificações e acreditações necessárias para clientes do setor público dos EUA.

Você pode encontrar mais informações sobre a oferta do Microsoft 365 Government - GCC para clientes do Governo dos EUA em planos do [Office 365 Government,](https://products.office.com/government/compare-office-365-government-plans)incluindo requisitos de qualificação.

A descrição do serviço do [Office 365 US Government](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) descreve os benefícios da plataforma, que são centralizados em atender aos requisitos de conformidade nos Estados Unidos.

> [!TIP]
> Talvez você queira transferir as tabelas de informações na descrição do serviço para uma planilha do Excel e adicionar duas colunas: relevantes para minha organização **Y/N** e atende às necessidades da minha organização **Y/N**. Em seguida, você pode revisar essa lista com seus colegas para confirmar se esse serviço atende às necessidades da sua organização.

> [!NOTE]
> Microsoft 365 Government - GCC só está disponível nos Estados Unidos. Os clientes do Governo não-EUA podem escolher entre vários planos [do Office 365 Government.](https://products.office.com/government/compare-office-365-government-plans)

**Pontos de decisão**: <br/>
- *Decida se o Microsoft 365 Government - GCC é apropriado para sua organização.*
- *Confirme se sua organização atende aos requisitos de qualificação.*

## <a name="step-2-apply-for-microsoft-365-government---gcc"></a>Etapa 2. Aplicar-se ao Microsoft 365 Government - GCC

Depois de decidir que esse serviço é o correto para sua organização, inicie o processo [de solicitação para este serviço](https://products.office.com/government/eligibility-validation).

## <a name="step-3-understand-microsoft-365-government---gcc-default-security-settings"></a>Etapa 3. Entenda as configurações de segurança padrão do Microsoft 365 Government - GCC

Recomendamos que você tenha tempo para revisar cuidadosamente suas configurações de administração e segurança antes de modificá-las e considerar o impacto na conformidade antes de fazer alterações nas configurações de segurança padrão.

**Ponto de** decisão : decida se você modificará qualquer uma das configurações de segurança padrão do *Microsoft 365 Government - GCC,* resolvendo primeiro entender o impacto de quaisquer alterações que você possa fazer.

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gccsup1sup"></a>Etapa 4. Entender quais recursos estão indisponíveis ou desabilitados por padrão no Microsoft 365 Government – GCC<sup>1</sup>

Para acomodar os requisitos de nossos clientes de nuvem governamental, há algumas diferenças entre o Microsoft 365 Government - GCC e os planos empresariais. Consulte a tabela a seguir para ver quais recursos estão disponíveis. Confira [aqui](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) as atualizações mais recentes do produto de conformidade publicadas no roteiro do Microsoft 365.<br><br>

| Área | Recurso | GCC Status |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Proteção de informações**              | Cliente de rotulagem unificada e scanner         | Disponível              |
|                                         | Match de dados exatos          | Disponível              |
|                                         | Classificação automática e rotulagem para Exchange Online, SharePoint Online e OneDrive                      | Em implantação              |
|                                         | Classificação automática e rotulagem para aplicativo do Office (Word, Excel, PowerPoint, Outlook) em plataformas (Web, Android, iOS, Windows e Mac) |  No desenvolvimento              |
|                                         | Classificação automática e rotulagem para clientes do Office (Mobile)                                       | No backlog de engenharia              |
|                                         | Classificação automática e rotulagem para o Teams                            | No backlog de engenharia |
|                                         | Análise de classificação de dados: Visão geral e Explorador de Conteúdo                            | No backlog de engenharia |
|                                         | Análise: classificadores de aprendizado de máquina com rotulagem automática no lado do serviço                           | No backlog de engenharia  |
|                                         | Análise: classificadores de aprendizado de máquina com rotulagem automática em aplicativos do Office/lado do cliente                           | No backlog de engenharia  |
|                                         | Criptografia básica de mensagens do Office 365 (E3)                            | Disponível              |
|                                         | Criptografia avançada de mensagens do Office 365 (E5)  | Disponível              |
|                                         | Chave de Cliente do Office 365    | Disponível |
|                                         | Traga sua própria chave (BYOK) para o ciclo de vida de provisionamento de chaves gerenciadas pelo cliente                            | Disponível |
|                                         | Mantenha sua própria chave (HYOK) que abrange a Proteção de Informações do Azure e o Gerenciamento de Direitos do Active Directory (AD) para cenários altamente regulamentados (Visualização)                         | Disponível |
|                                         | Criptografia de Chave Dupla                           | Disponível |
|                                         | Criptografia: coautor em documentos criptografados usando aplicativos Web WXP                           | No backlog de engenharia |
|                                         | Prevenção contra perda de dados (DLP) para arquivos e email         | Disponível |
|                                         | DLP para conversas de chat e canal do Teams         | No desenvolvimento |
|                                         | Ponto de extremidade DLP | No backlog de engenharia |
| **Governança de informações** | Governança de informações: Arquivamento de Email                                       | Disponível              |
|                                         | Governança de informações: bloqueio de preservação          | Disponível              |
|                                         | Governança de informações: Importar PST                      | Disponível              |
|                                         | Governança de informações: Rótulos manuais de retenção não registrado            | Disponível |
|                                         | Governança de informações: Rótulos de retenção padrão para SharePoint, bibliotecas, pastas e conjuntos de documentos do OneDrive for Business; Caixas de entrada do Exchange; e grupos do Office 365 | Disponível              |
|                                         | Governança de informações: políticas de retenção para toda a organização; locais ou usuários específicos; automaticamente com base em condições específicas (por exemplo, palavras-chave ou informações confidenciais); e com base em um evento                                       | Disponível              |
|                                         | Governança de informações: políticas de retenção para o Teams                            | Disponível |
|                                         | Governança de informações: rótulos de retenção usando a classificação do SharePoint Syntex                            | No backlog de engenharia |
|                                         | Governança de informações: políticas de retenção com classificadores com treinamento                            | No backlog de engenharia |
|                                         | Governança de informações: políticas de retenção para gravação de reuniões do Teams                            | No backlog de engenharia |
|                                         | Governança de informações: políticas de retenção para o Yammer                            | No backlog de engenharia |
|                                         | Gerenciamento de registros: Classificação manual para rótulos de registro                           | Disponível              |
|                                         | Gerenciamento de registros: rótulos de registro padrão para o SharePoint, bibliotecas, pastas e conjuntos de documentos do OneDrive for Business; e grupos do Office 365                              | Disponível              |
|                                         | Gerenciamento de registros: políticas de registro automático com base em condições específicas (por exemplo, palavras-chave ou informações confidenciais); e com base em um evento                            | Disponível              |
|                                         | Gerenciamento de registros: Revisão de disposição  | Disponível              |
|                                         | Gerenciamento de registros: Gerenciador de plano de arquivos    | Disponível |
|                                         | Gerenciamento de registros: Prova de descarte                            | Disponível |
|                                         | Gerenciamento de registros: controle de versão de registros                            | Disponível |
|                                         | Gerenciamento de registros: registros regulatórios (Visualização pública)                         | No desenvolvimento |
|                                         | Gerenciamento de registros: revisão de disposição em vários estágios | No backlog de engenharia |
|                                         | Gerenciamento de registros: use a classificação de Syntex do SharePoint para aplicar rótulos de registro | No backlog de engenharia |
| **Gerenciamento de risco interno**             | Sistema de Proteção de Dados do cliente                                | Disponível            |
|                                         | Gerenciamento de riscos do Insider: indicadores do Office para o Teams, sites do SharePoint, mensagens de email                         | No desenvolvimento |
|                                         | Insider Risk Management: Roubo de dados ao separar usuários                        | No desenvolvimento |
|                                         | Insider Risk Management: Vazamentos gerais de dados                                | No desenvolvimento              |
|                                         | Gerenciamento de riscos do Insider: investigar alertas de gerenciamento de riscos insider                                   | No desenvolvimento              |
|                                         | Gerenciamento de riscos insider: painel de caso, explorador de conteúdo e modelos de aviso | No desenvolvimento |
|                                         | Gerenciamento de Riscos Do Insider: Escalonar para investigação para Descoberta Avançada de EDiscovery | No desenvolvimento|
|                                         | Insider Risk Management: Indicadores de dispositivo para atividade no Windows 10 Build 1809 ou superior | No backlog de engenharia|
|                                         | Insider Risk Management: Indicadores para violação de política de segurança (visualização) | No backlog de engenharia|
|                                         | Insider Risk Management: Indicadores para alertas do Microsoft Defender para Ponto de Extremidade (visualização) | No backlog de engenharia|
|                                         | Insider Risk Management: Modelos de política para vazamentos de dados por usuários prioritários (visualização) | No backlog de engenharia |
|                                         | Gerenciamento de Riscos do Insider: modelos de política para vazamentos de dados por usuários insatisfeitos (visualização) | No backlog de engenharia |
|                                         | Insider Risk Management: Modelos de política para violações gerais de política de segurança (visualização) | No backlog de engenharia |
|                                         | Insider Risk Management: modelos de política para violações de política de segurança por usuários prioritários, usuários de saída, usuários insatisfeitos (visualização) | No backlog de engenharia |
|                                         | Insider Risk Management: Personalização de política (visualização) | No backlog de engenharia |
|                                         | Gerenciamento de Riscos do Insider: Exportar alertas (visualização) | No backlog de engenharia |
|                                         | Insider Risk Management: Grupos de usuários prioritários (visualização) | No backlog de engenharia |
|                                         | Conformidade de comunicação (incl. Políticas de supervisão): Criar políticas do cliente, 3 pré-configuradas  | Em implantação |
|                                         | Conformidade de comunicação (incl. Políticas de supervisão): Suporte para Teams, Exchange e remover mensagem do Teams | Em implantação |
|                                         | Conformidade de comunicação (incl. Políticas de supervisão): alertas de acesso; modelos de aviso; painel de política de comunicação | Em implantação  |
|                                         | Conformidade de Comunicação (incl. Políticas de supervisão): Escalonar para investigação para Descoberta Eletrônica Avançada | Em implantação |
|                                         | Conformidade de Comunicação (incl. Políticas de supervisão): Detectar conteúdo adulto | Em implantação |
|                                         | Conformidade de comunicação: detecta violação de código de conduta repetido ao longo do tempo | Em implantação |
|                                         | Conformidade de Comunicação: Suporte para permissões mais granulares | Em implantação |
|                                         | Conformidade de Comunicação: Analisar dados de chat do Teams de usuários com caixa de correio no site | Em implantação |
|                                         | Conformidade de Comunicação: Modelo de conflito de interesse | No backlog de engenharia |
|                                         | Conformidade de comunicação: capacidade de ignorar assinatura de email ou aviso de isenção de responsabilidade | No backlog de engenharia |
|                                         | Conformidade de Comunicação: Entrega de gerenciamento de riscos do Insider | No backlog de engenharia |
|                                         | Conformidade de comunicação: verificação de saúde da política e capacidade de pausar política | No backlog de engenharia |
|                                         | Conformidade de comunicação: traduzir conteúdo de saúde durante a investigação | No backlog de engenharia |
|                                         | Conformidade de comunicação: detecção de burnout e de suicidio | No backlog de engenharia |
|                                         | Barreiras de informações | No backlog de engenharia |
|                                         | Gerenciamento de acesso privilegiado                    | No backlog de engenharia |
| **Descobrir & responder**                  | Descoberta Principal: Preservação in-local                            | Disponível              |
|                                         | Descoberta Interna: Auditoria                                 | Disponível              |
|                                         | Descoberta Principal: Gerenciamento de Caso                                 | Disponível              |
|                                         | Descoberta Principal: Exportar                                          | Disponível              |
|                                         | Descoberta Principal: Exportação nativa                                  | Disponível              |
|                                         | Descoberta Principal de EDiscovery: descriptografia rms                                   | Disponível              |
|                                         | Descoberta Principal: o Centro de Conformidade da Microsoft expandiu o suporte para pesquisar e exportar itens no SharePoint e na Lixeira do OneDrive for Business                                        | No desenvolvimento              |
|                                         | Descoberta Avançada em EDiscovery: Processamento avançado                             | Disponível |
|                                         | Descoberta Virtual Avançada: Painel                                 | Disponível |
|                                         | Descoberta Eletrônico Avançada: Threading de email                   | Disponível |
|                                         | Descoberta eDiscoveria Avançada: Exportar (baixar, exportar, adicionar a outro conjunto de exibição)                                          | Disponível |
|                                         | Descoberta Avançada: Filtragem                               | Disponível |
|                                         | Descoberta Avançada: Responsabilidade legal para mensagens de canais privados do Teams                 | Disponível |
|                                         | Descoberta Avançada: Identificação quase duplicada                                         | Disponível |
|                                         | Descoberta eDiscoveria Avançada: fontes de dados não custodiais                                         | Disponível |
|                                         | Descoberta eDiscoveria Avançada: ingestão não do Office 365                                      | Disponível |
|                                         | Descoberta Avançada: Codificação Preditiva                                       | Disponível |
|                                         | Descoberta Avançada: Exportação processada com arquivo de carga                   | Disponível |
|                                         | Descoberta Avançada de EDiscovery: Redactions                        | Disponível |
|                                         | Descoberta Avançada de EDiscovery: Conjuntos de revisão                                     | Disponível |
|                                         | Descoberta Virtual Avançada: Revisar dados (dados de consulta, marcas inteligentes, painel) e anotações (redact)                             | Disponível |
|                                         | Descoberta eDiscoveria Avançada: Relatório de Termos de Pesquisa                        | Disponível |
|                                         | Descoberta eDiscoveria Avançada: Correção de erro de item único                              | Disponível |
|                                         | Descoberta Avançada: Suporte à Exportação PST                              | Disponível |
|                                         | Descoberta Virtual Avançada: Suporte ao conteúdo vinculado do OneDrive e do SharePoint Online (anexos modernos)                              | Disponível |
|                                         | Descoberta Avançada: Marcação                              | Disponível |
|                                         | Descoberta eDiscoveria Avançada: Relatórios de locatários                              | Disponível |
|                                         | Descoberta Avançada em EDiscovery: Temas                              | Disponível |
|                                         | Descoberta Interna Avançada: Visualizadores                              | Disponível |
|                                         | Descoberta Eletrônico Avançada: Descoberta Avançada do Yammer no Centro de Conformidade da Microsoft                              | Disponível |
|                                         | Descoberta eDiscoveria Avançada: o Centro de Conformidade da Microsoft expandiu o suporte para pesquisar e exportar itens na lixeira do SharePoint e do OneDrive for Business                              | No desenvolvimento |
|                                         | Descoberta eDiscover avançada: suporte a reações do Teams                              | No desenvolvimento |
|                                         | Auditoria básica                              | Disponível |
|                                         | Auditoria Avançada: acesso a eventos cruciais (por exemplo, mailitemsaccessed)                              | Disponível |
|                                         | Auditoria Avançada: Maior largura de banda para API de atividade de gerenciamento                              | Disponível |
|                                         | Auditoria Avançada: responsabilidade legal para mensagens de canais privados do Teams                               | Disponível |
|                                         | Auditoria Avançada: Retenção de log (1 ano)                               | Em implantação |
|                                         | Auditoria Avançada: Centro de Conformidade e Segurança                               | Disponível |
|                                         | Auditoria Avançada: retenção de longo prazo em logs de auditoria (10 anos)                               | No backlog de engenharia |
|                                         | Auditoria Avançada: eventos de envio de email e envio de emails                               | No backlog de engenharia |
|                                         | Auditoria Avançada: insights de auditoria processados                               | No backlog de engenharia |
|                                         | Auditoria Avançada: eventos de termos de pesquisa no Exchange Online e no SharePoint Online                              | No backlog de engenharia |
|    **Gerenciamento de Conformidade**            | Centro de Conformidade e Segurança do Microsoft 365                              | Disponível |
|                                         | Gerenciador de Conformidade                              | Disponível |
|                                         | Microsoft Cloud App Security                              | No backlog de engenharia |
|                                         | Suporte a caracteres de byte duplo                              | No backlog de engenharia |
|    **Ecossistema**            | APIs do Graph para Descoberta Avançada                              | No desenvolvimento |
|                                         | Conectores de dados de primeira parte                              | No backlog de engenharia |
|                                         | Conectores de dados de terceiros                              | No backlog de engenharia |
|                                         | APIs gráficas para os dados de exportação do Teams                              | No backlog de engenharia |




<sup>1</sup> O status identificado está sujeito a alterações à medida que os planos e prioridades do projeto são reavaliados.<br/>

**Ponto de decisão:** *decida se os recursos de conformidade atendem às necessidades da sua organização.*