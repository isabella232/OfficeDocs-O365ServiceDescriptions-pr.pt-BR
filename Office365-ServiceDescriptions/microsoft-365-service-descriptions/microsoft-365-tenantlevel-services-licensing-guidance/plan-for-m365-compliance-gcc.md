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
ms.openlocfilehash: d3be49d3171e07cfc11e6d6924a8b5ec2395d920
ms.sourcegitcommit: f7874215059c1e5a9d383da0539f87b6f85a57e6
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/25/2021
ms.locfileid: "52001897"
---
# <a name="plan-for-microsoft-365-compliance--gcc"></a>Planejar Microsoft 365 conformidade – GCC

Esta orientação é para profissionais de IT que estão conduzindo implantações do Office 365 em entidades governamentais federais, estaduais, locais, tribais ou territoriais dos EUA ou outras entidades que lidam com dados sujeitos a regulamentos e requisitos governamentais, onde o uso do Microsoft 365 Government - GCC é apropriado para atender a esses requisitos.

> [!NOTE]
> Se sua organização já tiver atendido aos requisitos de qualificação do Microsoft 365 - GCC e aplicados e aceitos no programa, você poderá ignorar as etapas 1 e 2 e ir diretamente para a etapa 3.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---gcc-and-meets-eligibility-requirements"></a>Etapa 1. Determinar se sua organização precisa Microsoft 365 Governo - GCC e atende aos requisitos de qualificação

O Microsoft 365 Government - GCC ambiente atende aos requisitos do governo dos EUA para serviços de nuvem, incluindo FedRAMP Moderado e requisitos para a justiça criminal e sistemas de informações fiscais federais (tipos de dados CJI e FTI).

Além de aproveitar os recursos e recursos do Office 365, as organizações se beneficiam dos seguintes recursos exclusivos do Microsoft 365 Government - GCC:

- O conteúdo do cliente da sua organização é logicamente segregado do conteúdo do cliente nos serviços comerciais Office 365 da Microsoft.

- O conteúdo do cliente da sua organização é armazenado dentro dos Estados Unidos.

- O acesso ao conteúdo do cliente da sua organização é restrito à equipes selecionadas da Microsoft.

- Microsoft 365 Government - GCC está em conformidade com certificações e acreditações necessárias para clientes do setor público dos EUA.

Você pode encontrar mais informações sobre a Microsoft 365 government - GCC para clientes do Governo dos EUA em Office 365 Government [planos](https://products.office.com/government/compare-office-365-government-plans), incluindo requisitos de qualificação.

A [Office 365 de serviço do Governo](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) dos EUA descreve os benefícios da plataforma, que são centralizados em atender aos requisitos de conformidade nos Estados Unidos.

> [!TIP]
> Talvez você queira transferir as tabelas de informações na descrição do serviço para uma Excel de trabalho e adicionar duas colunas: relevantes para minha organização **Y/N** e atende às necessidades da minha organização **Y/N**. Em seguida, você pode revisar essa lista com seus colegas para confirmar se esse serviço atende às necessidades da sua organização.

> [!NOTE]
> Microsoft 365 Government - GCC está disponível apenas nos Estados Unidos. Os clientes do Governo não-EUA podem escolher entre vários planos [Office 365 Government .](https://products.office.com/government/compare-office-365-government-plans)

**Pontos de decisão**: <br/>
- *Decida se Microsoft 365 governo - GCC é apropriado para sua organização.*
- *Confirme se sua organização atende aos requisitos de qualificação.*

## <a name="step-2-apply-for-microsoft-365-government---gcc"></a>Etapa 2. Aplicar-se Microsoft 365 Governo - GCC

Depois de decidir que esse serviço é o correto para sua organização, inicie o processo [de solicitação para este serviço](https://products.office.com/government/eligibility-validation).

## <a name="step-3-understand-microsoft-365-government---gcc-default-security-settings"></a>Etapa 3. Entender Microsoft 365 Governo - GCC configurações de segurança padrão

Recomendamos que você tenha tempo para revisar cuidadosamente suas configurações de administração e segurança antes de modificá-las e considerar o impacto na conformidade antes de fazer alterações nas configurações de segurança padrão.

**Ponto de** decisão : decida se você modificará qualquer uma das configurações de Microsoft 365 padrão GCC de segurança, resolvendo primeiro entender o impacto de quaisquer alterações que você *possa fazer.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gccsup1sup"></a>Etapa 4. Entenda quais recursos estão atualmente indisponíveis ou desabilitados por padrão Microsoft 365 Government – GCC<sup>1</sup>

Para acomodar os requisitos de nossos clientes de nuvem do governo, há algumas diferenças entre Microsoft 365 Government - GCC e planos empresariais. Consulte a tabela a seguir para ver quais recursos estão disponíveis. Confira [aqui](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) as atualizações mais recentes do produto de conformidade publicadas Microsoft 365 roteiro.<br><br>

| Área | Recurso | GCC Status |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Proteção de informações**              | Cliente de rotulagem unificada e scanner         | Disponível              |
|                                         | Match de dados exatos          | Disponível              |
| Rotulagem de sensibilidade                    | Classificação automática e rotulagem para Exchange Online, SharePoint Online e OneDrive                      | Disponível         |
| Rotulagem de sensibilidade                    | Classificação automática e rotulagem para Aplicativo do Office (Word, Excel, PowerPoint, Outlook) em plataformas (Web, Android, iOS, Windows e Mac) |  Disponível              |
| Rotulagem de sensibilidade                    | Classificação automática e rotulagem para Office clientes (Mobile)                                       | No backlog de engenharia              |
| Rotulagem de sensibilidade                    | Classificação automática e rotulagem para Teams, Microsoft 365 Grupos, SharePoint sites                            | Disponível |
| Análise                               | Análise de classificação de dados: Visão geral e Explorador de Conteúdo                            | Disponível |
| Análise                               | Análise: classificadores de aprendizado de máquina com rotulagem automática no lado do serviço                           | No backlog de engenharia  |
| Análise                               | Análise: classificadores de aprendizado de máquina com rotulagem automática Office aplicativos/lado do cliente                           | Em implantação |
| Criptografia                              | Básico Criptografia de Mensagens do Office 365 (E3)                            | Disponível              |
| Criptografia                              | Advanced Criptografia de Mensagens do Office 365 (E5)  | Disponível              |
| Criptografia                              | Chave de Cliente do Office 365    | Disponível |
| Criptografia                              | Chave do cliente: criptografia de dados em repouso para Microsoft 365    | Em implantação |
| Criptografia                              | Traga sua própria chave (BYOK) para o ciclo de vida de provisionamento de chaves gerenciadas pelo cliente                            | Disponível |
| Criptografia                              | Criptografia de Chave Dupla                           | Disponível |
| Criptografia                              | Exchange Online de serviço usando chaves gerenciadas da Microsoft         | Disponível |
| Prevenção contra perda de dados                    | Prevenção contra perda de dados (DLP) para arquivos e email         | Disponível |
| Prevenção contra perda de dados                    | DLP para Teams conversas de canal e chat         | Disponível |
| Prevenção contra perda de dados                    | Ponto de extremidade DLP | Em implantação |
| Prevenção contra perda de dados                    | Painel de alertas | No desenvolvimento |
| Prevenção contra perda de dados                    | Página Visão Geral | No desenvolvimento |
| **Governança de informações** | Escopos adaptáveis para políticas de retenção e rotulagem                 | No backlog de engenharia              |
| Governança de informações                 | Arquivamento de email          | Disponível              |
| Governança de informações                 | Rótulos de retenção padrão para SharePoint, OneDrive for Business bibliotecas, pastas e conjuntos de documentos; Exchange caixas de entrada; e Office 365 Grupos          | Disponível              |
| Governança de informações                 | Importar PST                      | Disponível              |
| Governança de informações                 | Rótulos de retenção manuais que não são de registro            | Disponível |
| Governança de informações                 | Bloqueio de preservação            | Disponível |
| Governança de informações                 | Políticas de retenção para toda a organização; locais ou usuários específicos; automaticamente com base em condições específicas (por exemplo, palavras-chave ou informações confidenciais); e com base em um evento                                       | Disponível              |
| Governança de informações                 | Políticas de retenção para Teams                            | Disponível |
| Governança de informações                 | Políticas de retenção para Teams de reunião                            | No desenvolvimento |
| Governança de informações                 | Políticas de retenção para Teams canais privados                            | No backlog de engenharia |
| Governança de informações                 | Políticas de retenção para Teams canais compartilhados                            | No backlog de engenharia |
| Governança de informações                 | Políticas de retenção com classificadores treineis                            | No backlog de engenharia |
| Governança de informações                 | Políticas de retenção para Yammer                            | No backlog de engenharia |
| Gerenciamento de registros                     | Capacidade de excluir um rótulo de registro                           | No desenvolvimento              |
| Gerenciamento de registros                     | Aplicar um rótulo de registro manualmente                            | Disponível              |
| Gerenciamento de registros                     | Aplicar rótulos de registro padrão para SharePoint, OneDrive for Business bibliotecas, pastas e conjuntos de documentos; e Office 365 grupos                              | Disponível              |
| Gerenciamento de registros                     | Aplicar políticas de registro automaticamente com base em condições específicas (por exemplo, palavras-chave ou informações confidenciais); e com base em um evento                            | Disponível              |
| Gerenciamento de registros                     | Aplicar políticas de registro automaticamente com classificadores treináveis  | No desenvolvimento              |
| Gerenciamento de registros                     | Revisão de disposição  | Disponível              |
| Gerenciamento de registros                     | Gerente de planejamento de arquivos    | Disponível |
| Gerenciamento de registros                     | Revisão de disposição em vários estágios    | No backlog de engenharia |
| Gerenciamento de registros                     | Outlook cliente para Gerenciamento de Registros    | No backlog de engenharia |
| Gerenciamento de registros                     | Power Automate Flow final do período de retenção    | No backlog de engenharia |
| Gerenciamento de registros                     | Preservação e rotulagem automática de anexos de nuvem    | No backlog de engenharia |
| Gerenciamento de registros                     | Prova de descarte                            | Disponível |
| Gerenciamento de registros                     | Registros de versão                            | Disponível |
| Gerenciamento de registros                     | Registros regulatórios                         | Disponível |
| Gerenciamento de registros                     | Usar SharePoint classificação Syntex para aplicar rótulos de registro | No backlog de engenharia |
| **Gerenciamento de riscos insider**             | Sistema de Proteção de Dados do cliente                                | Disponível            |
| Conformidade em comunicações                | Capacidade de ignorar assinatura de email ou aviso de isenção de responsabilidade                         | No desenvolvimento |
| Conformidade em comunicações                | Capacidade de definir um período de retenção para uma política de Conformidade de Comunicação                         | No desenvolvimento |
| Conformidade em comunicações                | Alertas de acesso; modelos de aviso; painel de política de comunicação                         | Disponível |
| Conformidade em comunicações                | Analisar Teams dados de chat de usuários com caixa de correio no site                         | Disponível |
| Conformidade em comunicações                | Monitorar automaticamente todas Teams um usuário é membro de                         | Disponível |
| Conformidade em comunicações                | Modelo de conflito de interesses                         | Disponível |
| Conformidade em comunicações                | Criar políticas de cliente, 3 pré-configuradas                         | Disponível |
| Conformidade em comunicações                | Detectar conteúdo adulto                         | Disponível |
| Conformidade em comunicações                | Detecta a violação de código de conduta repetida ao longo do tempo                         | Disponível |
| Conformidade em comunicações                | Escalonar para investigação para Advanced eDiscovery                         | Disponível |
| Conformidade em comunicações                | Entrega de gerenciamento de riscos insider                         | No backlog de engenharia |
| Conformidade em comunicações                | Aproveitar o reconhecimento óptico de caracteres para extrair e avaliar mensagens                         | No desenvolvimento |
| Conformidade em comunicações                | Nova exibição simplificada para empresas muito pequenas                         | No desenvolvimento |
| Conformidade em comunicações                | Verificação de saúde da política e capacidade de pausar política                         | No desenvolvimento |
| Conformidade em comunicações                | Integração do Power Automate                         | No desenvolvimento |
| Conformidade em comunicações                | Suporte para permissões mais granulares                         | Disponível |
| Conformidade em comunicações                | Oferece suporte a sete idiomas para os classificadores de ameaças, assédio direcionado e profanidades                         | No desenvolvimento |
| Conformidade em comunicações                | Microsoft Teams integração                         | No backlog de engenharia |
| Conformidade em comunicações                | Teams de conversa                         | No desenvolvimento |
| Conformidade em comunicações                | Traduzir conteúdo durante a investigação                         | No backlog de engenharia |
| Sistema de Proteção de Dados do cliente                | Sistema de Proteção de Dados do cliente                         | Disponível |
| Barreiras de informações                | Barreiras de informações                         | Disponível |
| Gerenciamento de riscos internos             | Painel de casos                         | Disponível |
| Gerenciamento de riscos internos             | Furto de dados por usuários em processo de desligamento                        | Disponível |
| Gerenciamento de riscos internos             | Indicadores de dispositivo para atividade no Windows 10 Build 1809 ou superior                        | No backlog de engenharia |
| Gerenciamento de riscos internos             | Escalonar para investigação para Advanced eDiscovery                        | Disponível |
| Gerenciamento de riscos internos             | Exportar alertas                        | No backlog de engenharia |
| Gerenciamento de riscos internos             | Vazamento de dados gerais                                | Disponível              |
| Gerenciamento de riscos internos             | Indicadores para violação de política de segurança                   | No backlog de engenharia              |
| Gerenciamento de riscos internos             | Indicadores para alertas do Microsoft Defender para Ponto de Extremidade      | No backlog de engenharia              |
| Gerenciamento de riscos internos             | Insider risk management Activity Explorer      | No desenvolvimento              |
| Gerenciamento de riscos internos             | Insider risk Management Content Explorer      | No desenvolvimento              |
| Gerenciamento de riscos internos             | Investigar alertas de gerenciamento de riscos insider      | Disponível              |
| Gerenciamento de riscos internos             | Modelos de aviso      | Disponível              |
| Gerenciamento de riscos internos             | Office indicadores para Teams, SharePoint sites, mensagens de email      | Disponível              |
| Gerenciamento de riscos internos             | Personalização de política      | No backlog de engenharia              |
| Gerenciamento de riscos internos             | Modelos de política para vazamentos de dados por usuários insatisfeitos      | No backlog de engenharia              |
| Gerenciamento de riscos internos             | Modelos de política para vazamentos de dados por usuários prioritários | No backlog de engenharia |
| Gerenciamento de riscos internos             | Modelos de política para violações gerais de política de segurança | No backlog de engenharia |
| Gerenciamento de riscos internos             | Modelos de política para violações de política de segurança por usuários prioritários, usuários de saída, usuários insatisfeitos | No backlog de engenharia |
| Gerenciamento de riscos internos             | Grupos de usuários prioritários | No backlog de engenharia |
| Gerenciamento de riscos internos             | Integração do Power Automate | No desenvolvimento |
| Gerenciamento de riscos internos             | Microsoft Teams integração | No backlog de engenharia |
| Gerenciamento de Acesso Privilegiado        | Gerenciamento de acesso privilegiado | No backlog de engenharia |
| **Descobrir & responder**                  | Descoberta Interna: Auditoria                            | Disponível              |
| Descoberta eletrônica                              | Descoberta Principal: Gerenciamento de Caso                                 | Disponível              |
| Descoberta eletrônica                              | Descoberta Principal: Exportar                                          | Disponível              |
| Descoberta eletrônica                              | Descoberta Principal: Preservação in-local                           | Disponível              |
| Descoberta eletrônica                              | Descoberta Principal: Exportação nativa                                  | Disponível              |
| Descoberta eletrônica                              | Descoberta Principal de EDiscovery: descriptografia rms                                   | Disponível              |
| Descoberta eletrônica                              | Descoberta Principal da Descoberta e: Pesquisa                                   | Disponível              |
| Descoberta eletrônica                              | Descoberta Principal da Descoberta e: o Centro de Conformidade da Microsoft expandiu o suporte para pesquisar e exportar itens em SharePoint e OneDrive for Business Lixeira                                        | Disponível              |
| Descoberta eletrônica                              | Advanced eDiscovery: Processamento avançado                             | Disponível |
| Descoberta eletrônica                              | Advanced eDiscovery: Custodial para mapeamento de carga de trabalho                             | Disponível |
| Descoberta eletrônica                              | Advanced eDiscovery: Comunicações custodiais                             | Disponível |
| Descoberta eletrônica                              | Advanced eDiscovery: Painel                                 | Disponível |
| Descoberta eletrônica                              | Advanced eDiscovery: suporte a caracteres de byte duplo (chinês, japonês, coreano)                                 | Disponível |
| Descoberta eletrônica                              | Advanced eDiscovery: threading de email                   | Disponível |
| Descoberta eletrônica                              | Advanced eDiscovery: Exportar (baixar, exportar, adicionar a outro conjunto de exibição)                                          | Disponível |
| Descoberta eletrônica                              | Advanced eDiscovery: Filtragem                               | Disponível |
| Descoberta eletrônica                              | Advanced eDiscovery: otimizações de espera                      | No desenvolvimento |
| Descoberta eletrônica                              | Advanced eDiscovery: Responsabilidade legal para Teams de canais privados            | Disponível |
| Descoberta eletrônica                              | Advanced eDiscovery: o Centro de Conformidade da Microsoft expandiu o suporte para pesquisar e exportar itens em SharePoint e OneDrive for Business Lixeira            | No desenvolvimento |
| Descoberta eletrônica                              | Advanced eDiscovery: identificação quase duplicada                               | Disponível |
| Descoberta eletrônica                              | Advanced eDiscovery: Novo módulo de codificação preditiva                   | No backlog de engenharia |
| Descoberta eletrônica                              | Advanced eDiscovery: fontes de dados não custodiais                                  | Disponível |
| Descoberta eletrônica                              | Advanced eDiscovery: ingestão Office 365 não Office 365                                    | Disponível |
| Descoberta eletrônica                              | Advanced eDiscovery: codificação preditiva                                       | Disponível |
| Descoberta eletrônica                              | Advanced eDiscovery: Exportação processada com arquivo de carga                   | Disponível |
| Descoberta eletrônica                              | Advanced eDiscovery: Redactions                        | Disponível |
| Descoberta eletrônica                              | Advanced eDiscovery: Conjuntos de revisão                                     | Disponível |
| Descoberta eletrônica                              | Advanced eDiscovery: Revisar dados (dados de consulta, marcas inteligentes, painel) e anotações (redact)                             | Disponível |
| Descoberta eletrônica                              | Advanced eDiscovery: Relatório de Termos de Pesquisa                        | Disponível |
| Descoberta eletrônica                              | Advanced eDiscovery: Correção de erro de item único                              | Disponível |
| Descoberta eletrônica                              | Advanced eDiscovery: suporte à exportação PST                              | Disponível |
| Descoberta eletrônica                              | Advanced eDiscovery: suporte ao conteúdo vinculado do OneDrive e SharePoint Online (anexos modernos)                              | Disponível |
| Descoberta eletrônica                              | Advanced eDiscovery: suporte Teams reações                      | No backlog de engenharia |
| Descoberta eletrônica                              | Advanced eDiscovery: Marcação                              | Disponível |
| Descoberta eletrônica                              | Advanced eDiscovery: relatórios de locatários                              | Disponível |
| Descoberta eletrônica                              | Advanced eDiscovery: Temas                              | Disponível |
| Descoberta eletrônica                              | Advanced eDiscovery: Visualizadores                              | Disponível |
| Descoberta eletrônica                              | Advanced eDiscovery: Yammer Advanced eDiscovery no Centro de Conformidade da Microsoft                              | Disponível |
| Auditoria                                   | Auditoria básica                              | Disponível |
| Auditoria                                   | Auditoria Avançada: Acesso a eventos cruciais (por exemplo, *MailItemsAccessed*)                              | Disponível |
| Auditoria                                   | Auditoria Avançada: Maior largura de banda para API de atividade de gerenciamento                   | Disponível |
| Auditoria                                   | Auditoria Avançada: espera legal para Teams de canais privados                   | Disponível |
| Auditoria                                   | Auditoria Avançada: Retenção de log (1 ano)                               | Disponível |
| Auditoria                                   | Auditoria Avançada: retenção de longo prazo em logs de auditoria (10 anos)              | No desenvolvimento |
| Auditoria                                   | Auditoria Avançada: eventos de envio de email e envio de emails                               | Disponível |
| Auditoria                                   | Auditoria Avançada: Microsoft 365 Centro de Conformidade e Segurança                    | Disponível |
| Auditoria                                   | Auditoria Avançada: eventos de termos de pesquisa no Exchange Online e SharePoint Online                              | No backlog de engenharia |
|    **Gerenciamento de Conformidade**            | Microsoft 365 Centro de Segurança e Conformidade                              | Disponível |
|                                         | Gerenciador de Conformidade                              | Disponível |
|                                         | Suporte a caracteres de byte duplo                              | Disponível |
|                                         | Microsoft Cloud App Security                              | No backlog de engenharia |
|    **Ecossistema**            | Graph APIs para Advanced eDiscovery                              | No desenvolvimento |
|                                         | Graph APIs para Teams exportar dados                              | No backlog de engenharia |
|                                         | Conectores de dados de primeira parte                              | No backlog de engenharia |
|                                         | Conectores de dados de terceiros                              | No desenvolvimento |




<sup>1</sup> O status identificado está sujeito a alterações à medida que os planos e prioridades do projeto são reavaliados.<br/>

**Ponto de decisão:** *decida se os recursos de conformidade atendem às necessidades da sua organização.*
