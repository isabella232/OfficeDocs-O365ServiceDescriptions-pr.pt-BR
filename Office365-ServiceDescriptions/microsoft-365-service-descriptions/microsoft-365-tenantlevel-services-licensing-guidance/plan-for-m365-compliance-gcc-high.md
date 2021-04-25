---
title: Planejar a conformidade com o Microsoft 365 – GCC High
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Esta orientação é para profissionais de IT que estão orientando implantações do Office 365 em entidades do Governo Federal dos EUA ou outras entidades que lidam com dados sujeitos a regulamentos e requisitos do governo, onde o uso do Microsoft 365 Government – GCC High é apropriado para atender a esses requisitos.
ms.openlocfilehash: 357cf30350ff2a3b21d7d9326e91c2c01d119b21
ms.sourcegitcommit: f7874215059c1e5a9d383da0539f87b6f85a57e6
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/25/2021
ms.locfileid: "52001907"
---
# <a name="plan-for-microsoft-365-compliance--gcc-high"></a>Planejar a conformidade do Microsoft 365 – GCC High

Esta orientação é para profissionais de IT que estão orientando implantações do Office 365 em entidades do Governo Federal dos EUA ou outras entidades que lidam com dados sujeitos a regulamentos e requisitos do governo, onde o uso do Microsoft 365 Government – GCC High é apropriado para atender a esses requisitos.

> [!NOTE]
>Se sua organização já tiver atendido aos requisitos de alta qualificação do Microsoft 365 Government – GCC High e aplicados e aceitos no programa, você poderá ignorar as etapas 1 e 2 e ir diretamente para a etapa 3.
 
## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government--gcc-high-and-meets-eligibility-requirements"></a>Etapa 1. Determinar se sua organização precisa do Microsoft 365 Government – GCC High e atende aos requisitos de qualificação

O ambiente Microsoft 365 Government - GCC High está em conformidade com os requisitos do Governo dos EUA para serviços de nuvem. Além de aproveitar os recursos e recursos do Office 365, as organizações se beneficiam dos seguintes recursos exclusivos do Microsoft 365 Government – GCC High:

- O conteúdo do cliente da sua organização é logicamente segregado do conteúdo do cliente nos serviços comerciais do Office 365 da Microsoft.
- O conteúdo do cliente da sua organização é armazenado dentro dos Estados Unidos.
- O acesso ao conteúdo do cliente da sua organização é restrito à equipes selecionadas da Microsoft.
- Microsoft 365 Government – GCC High está em conformidade com certificações e acreditações necessárias para clientes do setor público dos EUA.

Você pode encontrar mais informações sobre a oferta do Microsoft 365 Government – GCC High para clientes do Governo dos EUA em planos do [Office 365 Government,](https://products.office.com/government/compare-office-365-government-plans)incluindo requisitos de qualificação.

A descrição do serviço do [Office 365 US Government](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) descreve os benefícios da plataforma, que são centralizados em atender aos requisitos de conformidade nos Estados Unidos.

> [!TIP]
> Talvez você queira transferir as tabelas de informações na descrição do serviço para uma planilha do Excel e adicionar duas colunas: relevantes para minha organização **Y/N** e atende às necessidades da minha organização **Y/N**. Em seguida, você pode revisar essa lista com seus colegas para confirmar se esse serviço atende às necessidades da sua organização.

**Pontos de decisão**:<br/>
- *Decida se o Microsoft 365 Government – GCC-High é apropriado para sua organização.*
- *Confirme se sua organização atende aos requisitos de qualificação.*

> [!NOTE]
> Microsoft 365 Government - GCC High só está disponível nos Estados Unidos. Os clientes do Governo não-EUA podem escolher entre vários planos [do Office 365 Government.](https://products.office.com/government/compare-office-365-government-plans)

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>Etapa 2. Aplicar-se ao Microsoft 365 Government – GCC-High

Depois de decidir que esse serviço é o correto para sua organização, inicie o processo [de solicitação para este serviço](https://products.office.com/government/eligibility-validation).
 
## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>Etapa 3. Entenda o Microsoft 365 Government – GCC-High configurações de segurança padrão

Recomendamos que você tenha tempo para revisar cuidadosamente suas configurações de administração e segurança antes de modificá-las e considerar o impacto na conformidade antes de fazer alterações nas configurações de segurança padrão.

**Ponto de** decisão : decida se você modificará qualquer uma das configurações de segurança padrão do *Microsoft 365 Government – GCC-High,* resolvendo primeiro entender o impacto de quaisquer alterações que você possa fazer.

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-highsup1sup"></a>Etapa 4. Entenda quais recursos estão indisponíveis ou desabilitados por padrão no Microsoft 365 Government – GCC-High<sup>1</sup>

Para atender aos requisitos de nossos clientes de nuvem governamental, existem algumas diferenças entre o Microsoft 365 Government – GCC-High e os planos empresariais. Consulte a tabela a seguir para ver quais recursos estão disponíveis. Confira [aqui](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) as atualizações mais recentes do produto de conformidade publicadas no roteiro do Microsoft 365.<br><br>

| Área | Recurso | Status alto GCC |
|------|---------|-----------------|
| **Proteção de informações** | Cliente de rotulagem unificada e scanner | Disponível |
| | Match de dados exatos | Disponível |
| Rotulagem de sensibilidade | Classificação automática e rotulagem para Exchange Online, SharePoint Online e OneDrive | Disponível |
| Rotulagem de sensibilidade | Classificação automática e rotulagem para aplicativos do Office (Word, Excel, PowerPoint, Outlook) na Web, Android, iOS, Windows e Mac | Disponível |
| Rotulagem de sensibilidade | Classificação automática e rotulagem para clientes do Office (Mobile) | No backlog de engenharia |
| Rotulagem de sensibilidade | Classificação automática e rotulagem para teams, grupos do Microsoft 365 e sites do SharePoint | Disponível |
| Análise | Análise de classificação de dados: Visão geral e Explorador de Conteúdo | Disponível |
| Análise | Análise: classificadores de aprendizado de máquina com rotulagem automática no lado do serviço | No backlog de engenharia |
| Análise | Análise: classificadores de aprendizado de máquina com rotulagem automática em aplicativos do Office/lado do cliente | Em implantação |
| Criptografia | Criptografia básica de mensagens do Office 365 (E3) | Disponível |
| Criptografia | Criptografia avançada de mensagens do Office 365 (E5) | Disponível |
| Criptografia | Chave de Cliente do Office 365 | Disponível |
| Criptografia | Chave do cliente: criptografia de dados em repouso para o Microsoft 365 | Em implantação |
| Criptografia | Traga sua própria chave (BYOK) para o ciclo de vida de provisionamento de chaves gerenciadas pelo cliente | Disponível |
| Criptografia | Criptografia de Chave Dupla | Disponível |
| Criptografia | Criptografia de serviço do Exchange Online usando chaves gerenciadas da Microsoft | Disponível |
| Prevenção contra perda de dados | Prevenção contra perda de dados (DLP) para arquivos e email | Disponível |
| Prevenção contra perda de dados | DLP para conversas de chat e canal do Teams | Disponível |
| Prevenção contra perda de dados | Ponto de extremidade DLP | No desenvolvimento |
| Prevenção contra perda de dados | Painel de alertas | No desenvolvimento |
| Prevenção contra perda de dados | Página Visão Geral | No desenvolvimento |
| **Governança de informações** | Escopos adaptáveis para políticas de retenção e rotulagem | No backlog de engenharia |
| | Governança de informações: Arquivamento de Email | Disponível |
| | Governança de informações: Rótulos de retenção padrão para bibliotecas, pastas e conjuntos de documentos do SharePoint/OneDrive for Business; Caixas de entrada do Exchange; e grupos do Office 365 | Disponível |
| | Governança de informações: Importar PST | Disponível |
| | Governança de informações: Rótulos manuais de retenção não registrado | Disponível |
| | Governança de informações: bloqueio de preservação | Disponível |
| | Governança de informações: políticas de retenção para toda a organização; locais ou usuários específicos; automaticamente com base em condições específicas (por exemplo, palavras-chave ou informações confidenciais); e com base em um evento | Disponível |
| | Governança de informações: políticas de retenção para o Teams | Em implantação |
| | Governança de informações: políticas de retenção para gravação de reuniões do Teams | No desenvolvimento |
| | Governança de informações: políticas de retenção para canais privados do Teams | No backlog de engenharia |
| | Governança de informações: políticas de retenção para canais compartilhados do Teams | No backlog de engenharia |
| | Governança de informações: políticas de retenção com classificadores com treinamento | No desenvolvimento |
| | Governança de informações: políticas de retenção para o Yammer | No backlog de engenharia |
| Gerenciamento de registros | Capacidade de excluir um rótulo de registro | No desenvolvimento |
| Gerenciamento de registros | Aplicar um rótulo de registro manualmente | Disponível |
| Gerenciamento de registros | Aplicar rótulos de registro padrão para o SharePoint, bibliotecas, pastas e conjuntos de documentos do OneDrive for Business; e grupos do Office 365 | Disponível |
| Gerenciamento de registros | Aplicar políticas de registro automaticamente com base em condições específicas (por exemplo, palavras-chave ou informações confidenciais); e com base em um evento | Disponível |
| Gerenciamento de Registros | Aplicar políticas de registro automaticamente com classificadores treináveis | No desenvolvimento |
| Gerenciamento de registros | Revisão de disposição | Disponível |
| Gerenciamento de registros | Gerente de planejamento de arquivos | Disponível |
| Gerenciamento de registros | Revisão de disposição em vários estágios | No backlog de engenharia |
| Gerenciamento de registros | Prova de descarte | Disponível |
| Gerenciamento de registros | Power Automate Flow no final do período de retenção | No backlog de engenharia |
| Gerenciamento de registros | Preservação e rotulagem automática de anexos de nuvem | No backlog de engenharia |
| Gerenciamento de registros | Registros de versão | Disponível |
| Gerenciamento de registros | Registros regulatórios | Disponível |
| Gerenciamento de registros | Usar a classificação de Syntex do SharePoint para aplicar rótulos de registro | No backlog de engenharia |
| **Gerenciamento de risco interno** | Sistema de Proteção de Dados do cliente | Disponível |
| Conformidade em comunicações | Capacidade de ignorar assinatura de email ou aviso de isenção de responsabilidade | No desenvolvimento |
| Conformidade em comunicações | Capacidade de definir um período de retenção para uma política de Conformidade de Comunicação | No desenvolvimento |
| Conformidade em comunicações | Alertas de acesso; modelos de aviso; painel de política de comunicação | Disponível |
| Conformidade em comunicações | Analisar dados de chat do Teams de usuários com caixa de correio no ato | Disponível |
| Conformidade em comunicações | Modelo de conflito de interesses | Disponível |
| Conformidade em comunicações | Criar políticas de cliente, 3 pré-configuradas | Disponível |
| Conformidade em comunicações | Detectar conteúdo adulto | No backlog de engenharia |
| Conformidade em comunicações | Detecta a violação de código de conduta repetida ao longo do tempo | Disponível |
| Conformidade em comunicações | Escalonar para investigação para Descoberta Avançada da Descoberta Interna | Disponível |
| Conformidade em comunicações | Entrega de gerenciamento de riscos insider | No backlog de engenharia |
| Conformidade em comunicações | Aproveitar o reconhecimento óptico de caracteres para extrair e avaliar mensagens | No desenvolvimento |
| Conformidade em comunicações | Nova exibição simplificada para empresas muito pequenas | No desenvolvimento |
| Conformidade em comunicações | Verificação de saúde da política e capacidade de pausar política | No backlog de engenharia |
| Conformidade em comunicações | Integração do Power Automate | No backlog de engenharia |
| Conformidade em comunicações | Oferece suporte a sete idiomas para a ameaça, o assédio direcionado e os classificadores de profanidades | No backlog de engenharia |
| Conformidade em comunicações | Suporte para permissões mais granulares | Disponível |
| Conformidade em comunicações | Suporte para Teams, Exchange e capacidade de remover mensagem do Teams | Disponível |
| Conformidade em comunicações | Integração com o Microsoft Teams | No backlog de engenharia |
| Conformidade em comunicações | Contexto de conversa do Teams | No backlog de engenharia |
| Conformidade em comunicações | Traduzir conteúdo durante a investigação | No backlog de engenharia |
| Sistema de Proteção de Dados do cliente | Sistema de Proteção de Dados do cliente | Disponível |
| Barreiras de informações | Barreiras de informações | No desenvolvimento |
| Gerenciamento de riscos internos | Painel de casos | Disponível |
| Gerenciamento de riscos internos | Roubo de dados ao separar usuários | Disponível |
| Gerenciamento de riscos internos | Indicadores de dispositivo para atividade no Windows 10 Build 1809 e superior | No backlog de engenharia |
| Gerenciamento de riscos internos | Escalonar para investigação para Descoberta Avançada da Descoberta Interna | Disponível |
| Gerenciamento de riscos internos | Exportar alertas | No backlog de engenharia |
| Gerenciamento de riscos internos | Vazamentos gerais de dados | Disponível |
| Gerenciamento de riscos internos | Indicadores para violação de política de segurança | No backlog de engenharia |
| Gerenciamento de riscos internos | Indicadores para alertas do Microsoft Defender para Ponto de Extremidade | No backlog de engenharia |
| Gerenciamento de riscos internos | Insider risk management Activity Explorer | No desenvolvimento |
| Gerenciamento de riscos internos | Insider risk management Content Explorer | No desenvolvimento |
| Gerenciamento de riscos internos | Investigar alertas de gerenciamento de riscos insider | Disponível |
| Gerenciamento de riscos internos | Modelos de aviso | Disponível |
| Gerenciamento de riscos internos | Indicadores do Office para Teams, sites do SharePoint, mensagens de email | Disponível |
| Gerenciamento de riscos internos | Modelos de política para vazamentos de dados por usuários prioritários | No backlog de engenharia |
| Gerenciamento de riscos internos | Modelos de política para vazamentos de dados por usuários insatisfeitos | No backlog de engenharia |
| Gerenciamento de riscos internos | Modelos de política para violações gerais de política de segurança | No backlog de engenharia |
| Gerenciamento de riscos internos | Modelos de política para violações de política de segurança por usuários prioritários, usuários de saída, usuários insatisfeitos | No backlog de engenharia |
| Gerenciamento de riscos internos | Personalização de política | No backlog de engenharia |
| Gerenciamento de riscos internos | Grupos de usuários prioritários | No backlog de engenharia |
| Gerenciamento de riscos internos | Integração do Power Automate | No desenvolvimento |
| Gerenciamento de riscos internos | Integração com o Microsoft Teams | No backlog de engenharia |
| Gerenciamento de acesso privilegiado | Gerenciamento de acesso privilegiado | No backlog de engenharia |
| **Descobrir &amp; responder** | Descoberta Interna: Auditoria | Disponível |
| Descoberta eletrônica | Descoberta Principal: Gerenciamento de Caso | Disponível |
| Descoberta eletrônica | Descoberta Principal: Exportar | Disponível |
| Descoberta eletrônica | Descoberta Principal: Preservação in-local | Disponível |
| Descoberta eletrônica | Descoberta Principal: Exportação nativa | Disponível |
| Descoberta eletrônica | Descoberta Principal de EDiscovery: descriptografia rms | Disponível |
| Descoberta eletrônica | Descoberta Principal da Descoberta e: Pesquisa | Disponível |
| Descoberta eletrônica | Descoberta Avançada em EDiscovery: Processamento avançado | Disponível |
| Descoberta eletrônica | Descoberta Digital Avançada: Custodiatário para mapeamento de carga de trabalho | Disponível |
| Descoberta eletrônica | Descoberta Eletrônica Avançada: Comunicações custodiais | Disponível |
| Descoberta eletrônica | Descoberta Virtual Avançada: Painel | Disponível |
| Descoberta eletrônica | Descoberta Avançada: Suporte de byte duplo para chinês, japonês e coreano | Disponível |
| Descoberta eletrônica | Descoberta Eletrônico Avançada: Threading de email | Disponível |
| Descoberta eletrônica | Descoberta Avançada: Exportar (baixar, exportar, adicionar a outro conjunto de revisão) | Disponível |
| Descoberta eletrônica | Descoberta Avançada: Filtragem | Disponível |
| Descoberta eletrônica | Descoberta Avançada: Otimizações de espera | No desenvolvimento |
| Descoberta eletrônica | Descoberta Avançada: Responsabilidade legal para mensagens de canais privados do Teams | Disponível |
| Descoberta eletrônica | Descoberta e Descoberta Avançada: o Centro de Conformidade da Microsoft expandiu o suporte para pesquisar e exportar itens no SharePoint e na Lixeira do OneDrive for Business | No desenvolvimento |
| Descoberta eletrônica | Descoberta Avançada: Identificação quase duplicada | Disponível |
| Descoberta eletrônica | Descoberta Eletrônico Avançada: Novo módulo de codificação preditiva | No backlog de engenharia |
| Descoberta eletrônica | Descoberta eDiscoveria Avançada: fontes de dados não custodiais | Disponível |
| Descoberta eletrônica | Descoberta eDiscoveria Avançada: ingestão não do Office 365 | Disponível |
| Descoberta eletrônica | Descoberta Avançada: Codificação Preditiva | Disponível |
| Descoberta eletrônica | Descoberta Avançada: Exportação processada com arquivo de carga | Disponível |
| Descoberta eletrônica | Descoberta Avançada de EDiscovery: Redactions | Disponível |
| Descoberta eletrônica | Descoberta Avançada de EDiscovery: Conjuntos de revisão | Disponível |
| Descoberta eletrônica | Descoberta Virtual Avançada: Revisar dados (dados de consulta, marcas inteligentes, painel) e anotações (redact) | Disponível |
| Descoberta eletrônica | Descoberta eDiscoveria Avançada: Relatório de Termos de Pesquisa | Disponível |
| Descoberta eletrônica | Descoberta eDiscoveria Avançada: Correção de erro de item único | Disponível |
| Descoberta eletrônica | Descoberta eDiscoveria Avançada: Suporte à exportação PST | Disponível |
| Descoberta eletrônica | Descoberta Virtual Avançada: Suporte ao conteúdo vinculado do OneDrive e do SharePoint Online (anexos modernos) | Disponível |
| Descoberta eletrônica | Descoberta Avançada: Suportar reações do Teams | No backlog de engenharia |
| Descoberta eletrônica | Descoberta Avançada: Marcação | Disponível |
| Descoberta eletrônica | Descoberta eDiscoveria Avançada: Relatórios de locatários | Disponível |
| Descoberta eletrônica | Descoberta Avançada em EDiscovery: Temas | Disponível |
| Descoberta eletrônica | Descoberta Interna Avançada: Visualizadores | Disponível |
| Descoberta eletrônica | Descoberta Eletrônico Avançada: Descoberta Avançada do Yammer no Centro de Conformidade da Microsoft | Disponível |
| Auditoria | Auditoria básica | Disponível |
| Auditoria | Auditoria Avançada: Acesso a eventos cruciais (por exemplo, *MailItemsAccessed*) | Disponível |
| Auditoria | Auditoria Avançada: Maior largura de banda para API de atividade de gerenciamento | Disponível |
| Auditoria | Auditoria Avançada: responsabilidade legal para mensagens de canais privados do Teams | Disponível |
| Auditoria | Auditoria Avançada: Retenção de log (1 ano) | Disponível |
| Auditoria | Auditoria Avançada: retenção de longo prazo em logs de auditoria (10 anos) | No desenvolvimento |
| Auditoria | Auditoria Avançada: eventos de envio de email e envio de emails | Disponível |
| Auditoria | Auditoria Avançada: disponibilidade do Centro de Conformidade e Segurança do Microsoft 365 | Disponível |
| Auditoria | Auditoria Avançada: eventos de termos de pesquisa no Exchange Online e no SharePoint Online | No backlog de engenharia |
| **Gerenciamento de Conformidade** | Centro de Conformidade e Segurança do Microsoft 365 | Disponível |
| | Gerenciador de Conformidade | Disponível |
| | Suporte a caracteres de byte duplo | Disponível |
| | Microsoft Cloud App Security | Disponível |
| **Ecossistema** | APIs do Graph para Descoberta Avançada | No desenvolvimento |
| | APIs gráficas para os dados de exportação do Teams | No backlog de engenharia |
| | Conectores de dados de primeira parte | No backlog de engenharia |
| | Conectores de dados de terceiros | No desenvolvimento |

<sup>1</sup> O status identificado está sujeito a alterações à medida que os planos e prioridades do projeto são reavaliados.<br/>

**Ponto de decisão:** *decida se os recursos de conformidade atendem às necessidades da sua organização.*