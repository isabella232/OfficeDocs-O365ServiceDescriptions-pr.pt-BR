---
title: Planejar a conformidade com o Microsoft 365 – implantações do DoD
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Esta orientação é para profissionais de ti que estão conduzindo implantações do Office 365 em entidades governamentais americanas ou outras entidades que lidam com os dados sujeitos a regulamentações e requisitos governamentais, onde o uso do Microsoft 365 governamental – DoD é adequado para atender a esses requisitos.
ms.openlocfilehash: a619943b5eed63007b78613ab9b6715a52ef467d
ms.sourcegitcommit: d0ca41de5b242d2d5688d92d55064d9eecbb89a9
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 12/08/2020
ms.locfileid: "49601716"
---
# <a name="plan-for-microsoft-365-compliance---dod-deployments"></a>Planejar a conformidade com o Microsoft 365 – implantações do DoD

Esta orientação é para profissionais de ti que estão conduzindo implantações do Office 365 em entidades governamentais americanas ou outras entidades que lidam com os dados sujeitos a regulamentações e requisitos governamentais, onde o uso do Microsoft 365 governamental – DoD é adequado para atender a esses requisitos.

> [!NOTE]
> Se sua organização já atendeu aos requisitos de qualificação do governo Microsoft 365 e foram aplicados e foram aceitos no programa, você pode ignorar as etapas 1 e 2 e ir diretamente para a etapa 3.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---dod-and-meets-eligibility-requirements"></a>Etapa 1. Determinar se sua organização precisa do Microsoft 365 governamentais-DoD e atende aos requisitos de qualificação

O ambiente Microsoft 365 governamental-DoD cumpre os requisitos governamentais dos EUA para serviços em nuvem.

Além de aproveitar os recursos e as funcionalidades do Office 365, as organizações se beneficiam dos seguintes recursos, que são exclusivos para o governo da Microsoft 365 – DoD:

- O conteúdo do cliente da sua organização é logicamente separado do conteúdo do cliente nos serviços comerciais do Office 365 da Microsoft.
- O conteúdo do cliente da sua organização é armazenado dentro dos Estados Unidos.
- O acesso ao conteúdo do cliente da sua organização é restrito à equipes selecionadas da Microsoft.
- O Microsoft 365 governamental-DoD está em conformidade com certificações e confirações necessárias para os clientes do setor público dos EUA.

Você pode encontrar mais informações sobre a oferta Microsoft 365 governamentais-DoD para clientes do governo dos EUA em [planos governamentais do Office 365](https://products.office.com/government/compare-office-365-government-plans), incluindo requisitos de qualificação.

A [Descrição do serviço governo dos EUA do Office 365](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government) descreve os benefícios da plataforma, que são centralizados em atender aos requisitos de conformidade nos Estados Unidos.

> [!TIP]
> Você pode querer transferir as tabelas de informações na descrição do serviço para uma pasta de trabalho do Excel e adicionar duas colunas: **relevantes para minha organização** e **atender às necessidades da minha organização y/n**. Em seguida, você pode revisar essa lista com seus colegas para confirmar que esse serviço atende às necessidades da sua organização.

**Pontos de decisão**:<br/>
- *Decida se o Microsoft 365 governamentais-DoD é adequado para sua organização.*
- *Confirme se a sua organização atende aos requisitos de qualificação.*

> [!NOTE]
> O Microsoft 365 governamental-DoD só está disponível nos Estados Unidos. Clientes governamentais não americanos podem escolher entre vários [planos governamentais do Office 365](https://products.office.com/government/compare-office-365-government-plans).

## <a name="step-2-apply-for-microsoft-365-government---dod"></a>Etapa 2. Aplicar para o Microsoft 365 governamentais-DoD

Para ter decidido que esse serviço é adequado para sua organização, inicie o processo de [aplicação desse serviço](https://products.office.com/government/eligibility-validation).

## <a name="step-3-understand-microsoft-365-government---dod-default-security-settings"></a>Etapa 3. Entender as configurações de segurança padrão do governo Microsoft 365-DoD

Recomendamos que você reserve um tempo para revisar cuidadosamente suas configurações de administrador e segurança antes de modificá-las e considere o impacto sobre a conformidade antes de fazer qualquer alteração nas configurações de segurança padrão.

**Ponto de decisão**: *decida se você modificará qualquer uma das configurações de segurança governamentais-DOD padrão da Microsoft 365, resolvendo para entender primeiro o impacto de qualquer alteração que você possa fazer.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--dodsup1sup"></a>Etapa 4. Entender quais recursos estão atualmente indisponíveis ou estão desabilitados por padrão no Microsoft 365 governamentais – DoD<sup>1</sup>

Para atender aos requisitos de nossos clientes de nuvem governamental, há algumas diferenças entre os planos Microsoft 365 governamentais-DoD e Enterprise. Consulte a tabela a seguir para ver quais recursos estão disponíveis. Confira [aqui](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) as atualizações de produtos de conformidade mais recentes publicadas no Microsoft 365 Roadmap.<br><br>

| Área                                    | Recurso                                         | Status de GCC             |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Proteção de informações**              | Cliente e scanner de rótulo unificado         | Disponível              |
|                                         | Correspondência de dados exata          | Disponível               |
|                                         | Classificação automática e rótulo para o Exchange Online, o SharePoint Online e o OneDrive                      | Implementando              |
|                                         | Classificação automática e rotulamento para aplicativos do Office (Word, Excel, PowerPoint, Outlook) entre plataformas (Web, Android, iOS, Windows e Mac)            | Em desenvolvimento |
|                                         | Classificação automática e rotulamento para dispositivos móveis                                       | Na Backlog de engenharia              |
|                                         | Classificação automática e rotulamento para o Microsoft Teams                            | Na Backlog de engenharia |
|                                         | Classificação de dados: visão geral e Gerenciador de conteúdo                            | Em desenvolvimento |
|                                         | Análise: classificadores de aprendizado de máquina com rótulo automático no lado do serviço                           | Na Backlog de engenharia  |
|                                         | Análise: classificadores de aprendizado de máquina com rotulação automática em aplicativos do Office/lado do cliente                           | Na Backlog de engenharia  |
|                                         | Criptografia básica de mensagens do Office 365 (E3)                            | Disponível              |
|                                         | Criptografia avançada de mensagem do Office 365 (E5)  | Disponível              |
|                                         | Chave de Cliente do Office 365    | Disponível |
|                                         | Traga sua chave (BYOK) para o ciclo de vida de provisionamento de chave gerenciado pelo cliente                            | Disponível |
|                                         | Manter sua própria chave (HYOK) que abrange a proteção de informações do Azure e o Active Directory (AD) Rights Management para cenários altamente regulamentados (versão prévia)                         | Disponível |
|                                         | Criptografia de Chave Dupla                           | Implementando |
|                                         | Prevenção de perda de dados (DLP) para arquivos e email         | Disponível |
|                                         | DLP para chat de equipes e conversas de canal         | Na Backlog de engenharia |
|                                         | Correspondência exata dos dados de DLP         | Na Backlog de engenharia |
|                                         | Ponto de extremidade de DLP | Na Backlog de engenharia |
| **Governança de informações** | Governança de informações: arquivamento de E-mails                                       | Disponível              |
|                                         | Governança de informações: bloqueio de preservação          | Disponível              |
|                                         | Governança de informações: importar PST                      | Disponível              |
|                                         | Governança de informações: rótulos manuais de retenção de não registros            | Disponível |
|                                         | Governança de informações: rótulos de retenção padrão para bibliotecas do SharePoint/OneDrive for Business, pastas e conjuntos de documentos; Caixas de entrada do Exchange; e grupos do Office 365 | Disponível              |
|                                         | Governança de informações: políticas de retenção para toda a organização; locais ou usuários específicos; e automaticamente com base em uma condição específica (por exemplo, palavras-chave ou informações confidenciais)                                       | Disponível              |
|                                         | Governança de informações: políticas de retenção com classificadores estagiários                            | Na Backlog de engenharia |
|                                         | Governança de informações: políticas de retenção para gravação de reuniões do teams                            | Na Backlog de engenharia |
|                                         | Governança de informações: políticas de retenção para o Yammer e o Microsoft Teams                           | Na Backlog de engenharia              |
|                                         | Gerenciamento de registros: classificação manual para rótulos de registro                              | Disponível              |
|                                         | Gerenciamento de registros: rótulos de registro padrão para o SharePoint, bibliotecas do OneDrive for Business, pastas e conjuntos de documentos; e grupos do Office 365                            | Disponível              |
|                                         | Gerenciamento de registros: políticas de registro automático com base em condições específicas (por exemplo, palavras-chave ou informações confidenciais); e com base em um evento  | Disponível              |
|                                         | Gerenciamento de registros: análise de disposição    | Disponível |
|                                         | Gerenciamento de registros: Gerenciador de planos de arquivo                            | Disponível |
|                                         | Gerenciamento de registros: prova de alienação                         | Disponível |
|                                         | Gerenciamento de registros: registros normativos | Na Backlog de engenharia |
|                                         | Gerenciamento de registros: análise de disposição de vários estágios | Na Backlog de engenharia |
|                                         | Gerenciamento de registros: usar a classificação do Syntex do SharePoint para aplicar rótulos de registros         | Na Backlog de engenharia |
| **Gerenciamento de risco interno**             | Sistema de Proteção de Dados do cliente                                | Disponível            |
|                                         | Gerenciamento de risco do insider: indicadores do Office para Teams, sites do SharePoint, mensagens de email                         | Na Backlog de engenharia |
|                                         | Gerenciamento de risco do insider: roubo de dados por parte de usuários                        | Na Backlog de engenharia |
|                                         | Gerenciamento de risco do insider: vazamentos de dados gerais                                | Na Backlog de engenharia              |
|                                         | Gerenciamento de risco do insider: investigar alertas de gerenciamento de risco                                   | Na Backlog de engenharia              |
|                                         | Gerenciamento de risco do insider: painel de casos, Gerenciador de conteúdo e modelos de aviso | Na Backlog de engenharia |
|                                         | Gerenciamento de risco do insider: escalonar para investigação de descoberta eletrônica avançada |Na Backlog de engenharia|
|                                         | Gerenciamento de risco do insider: indicadores de dispositivo para atividade no Windows 10 Build 1809 e superior |Na Backlog de engenharia|
|                                         | Gerenciamento de risco do insider: indicadores de violação de política de segurança (visualização) |Na Backlog de engenharia|
|                                         | Gerenciamento de risco do insider: indicadores para o Microsoft defender para alertas de ponto de extremidade (versão prévia) |Na Backlog de engenharia|
|                                         | Gerenciamento de risco do insider: modelos de política para vazamentos de dados por usuários prioritários (visualização) | Na Backlog de engenharia |
|                                         | Gerenciamento de risco do insider: modelos de política para vazamentos de dados por usuários descontentes (visualização) | Na Backlog de engenharia |
|                                         | Gerenciamento de risco do insider: modelos de política para violações de política de segurança geral (versão prévia) | Na Backlog de engenharia |
|                                         | Gerenciamento de risco do insider: modelos de política para violações de política de segurança por usuários de prioridade, usuários de parte, usuários descontentes (visualização) | Na Backlog de engenharia |
|                                         | Gerenciamento de risco do insider: personalização de política (visualização) | Na Backlog de engenharia |
|                                         | Gerenciamento de risco do insider: exportar alertas (visualização) | Na Backlog de engenharia |
|                                         | Gerenciamento de risco do insider: grupos de usuários de prioridade (visualização) | Na Backlog de engenharia |
|                                         | Conformidade de comunicação (incl. políticas de supervisão): criar políticas de cliente, 3 pré-configurado  | Na Backlog de engenharia |
|                                         | Conformidade de comunicação (incl. políticas de supervisão): suporte à mensagem de Teams, Exchange e remove Teams | Na Backlog de engenharia |
|                                         | Conformidade de comunicação (incl. políticas de supervisão): alertas de acesso; modelos de aviso; painel de política de comunicação | Na Backlog de engenharia  |
|                                         | Conformidade de comunicação (incl. políticas de supervisão): escalonar para investigação para descoberta eletrônica avançada | Na Backlog de engenharia |
|                                         | Conformidade de comunicação (incl. políticas de supervisão): detectar conteúdo adulto | Na Backlog de engenharia |
|                                         | Conformidade de comunicação (incl. políticas de supervisão): detecta o código de repetição de violação de conduta ao longo do tempo | Implementando |
|                                         | Conformidade de comunicação (incl. políticas de supervisão): suporte para permissões mais granulares | Implementando |
|                                         | Conformidade de comunicação (incl. políticas de supervisão): analisar os dados de chat de equipes de usuários com a caixa de correio local | Implementando |
|                                         | Conformidade de comunicação (incl. políticas de supervisão): conflito do modelo de juros | Na Backlog de engenharia |
|                                         | Conformidade de comunicação (incluindo políticas de supervisão): capacidade de ignorar assinatura de email ou isenção de responsabilidade | Na Backlog de engenharia |
|                                         | Conformidade de comunicação (incluindo políticas de supervisão): gerenciamento de risco do insider | Na Backlog de engenharia |
|                                         | Conformidade de comunicação (incl. políticas de supervisão): verificação de integridade da política e capacidade de pausar política | Na Backlog de engenharia |
|                                         | Conformidade de comunicação (incl. políticas de supervisão): converter o conteúdo de integridade durante a investigação | Na Backlog de engenharia |
|                                         | Conformidade de comunicação (incl. políticas de supervisão): detecção de Burnout e Suicide | Na Backlog de engenharia |
|                                         | Barreiras de informações | Na Backlog de engenharia |
|                                         | Gerenciamento de acesso privilegiado                    | Na Backlog de engenharia |
| **Descobrir & responder**                  | Descoberta eletrônica principal: preservação no local                            | Disponível              |
|                                         | Descoberta eletrônica principal: gerenciamento de casos                                 | Disponível              |
|                                         | Descoberta eletrônica principal: pesquisa                                          | Disponível              |
|                                         | Descoberta eletrônica principal: exportar                                          | Disponível              |
|                                         | Descoberta eletrônica principal: descriptografia do RMS                                  | Disponível              |
|                                         | Descoberta eletrônica principal: exportação nativa                                   | Disponível              |
|                                         | Descoberta eletrônica principal: auditoria                                        | Disponível              |
|                                         | Descoberta eletrônica avançada: processamento avançado                                 | Implementando |
|                                         | Descoberta eletrônica avançada: mapeamento de carga de trabalho                                 | Implementando |
|                                         | Descoberta eletrônica avançada: comunicações de responsáveis                                 | Implementando |
|                                         | Descoberta eletrônica avançada: painel                   | Implementando |
|                                         | Descoberta eletrônica avançada: encadeamento de email                                          | Implementando |
|                                         | Descoberta eletrônica avançada: exportar (baixar, exportar, adicionar a outro conjunto de revisão)                               | Implementando |
|                                         | Descoberta eletrônica avançada: filtragem                 | Implementando |
|                                         | Descoberta eletrônica avançada: bloqueio legal para mensagens de canais privadas do teams                                         | Implementando |
|                                         | Descoberta eletrônica avançada: identificação próxima duplicada                                         | Implementando |
|                                         | Descoberta eletrônica avançada: inclusão de não-Office 365                                      | Implementando |
|                                         | Descoberta eletrônica avançada: codificação de previsão                                       | Implementando |
|                                         | Descoberta eletrônica avançada: exportação processada com o arquivo de carregamento                   | Implementando |
|                                         | Descoberta eletrônica avançada: redaçãos                        | Implementando |
|                                         | Descoberta eletrônica avançada: conjuntos de revisão                                     | Implementando |
|                                         | Descoberta eletrônica avançada: revisar e anotar                             | Implementando |
|                                         | Descoberta eletrônica avançada: relatório de termos de pesquisa                        | Implementando |
|                                         | Descoberta eletrônica avançada: suporte a conteúdo vinculado do OneDrive e do SharePoint Online (anexos modernos)                        | Implementando |
|                                         | Descoberta eletrônica avançada: marcação                              | Implementando |
|                                         | Descoberta eletrônica avançada: suporte a reações de equipes                              | Implementando |
|                                         | Descoberta eletrônica avançada: relatórios de locatário                              | Implementando |
|                                         | Descoberta eletrônica avançada: temas                              | Implementando |
|                                         | Descoberta eletrônica avançada: visualizadores                              | Implementando |
|                                         | Descoberta eletrônica avançada: descoberta eletrônica avançada do Yammer no centro de conformidade da Microsoft                              | Implementando |
|                                         | Descoberta eletrônica avançada: suporte a CJK/dobrar byte para descoberta eletrônica avançada                              | Em desenvolvimento |
|                                         | Auditoria básica                              | Disponível |
|                                         | Auditoria avançada: acesso a eventos cruciais (por exemplo, mailitemsaccessed)                              | Implementando |
|                                         | Auditoria avançada: maior largura de banda para a API de atividade de gerenciamento                              | Implementando |
|                                         | Auditoria avançada: retenção de logs (1 ano)                              | Implementando |
|                                         | Auditoria avançada: disponibilidade do centro de conformidade e segurança                              | Disponível |
|                                         | Auditoria avançada: retenção de longo prazo em logs de auditoria (10 anos)                              | Na Backlog de engenharia |
|                                         | Auditoria avançada: eventos de envio de email direto e email                              | Na Backlog de engenharia |
|                                         | Auditoria avançada: insights de auditoria processados                              | Na Backlog de engenharia |
|                                         | Auditoria avançada: eventos de termos de pesquisa no Exchange Online e no SharePoint Online                              | Na Backlog de engenharia |
|    **Gerenciamento de Conformidade**            | Centro de conformidade e segurança do Microsoft 365                              | Disponível |
|                                         | Segurança no aplicativo na nuvem da Microsoft                              | Na Backlog de engenharia |
|                                         | Gerenciador de Conformidade                              | Na Backlog de engenharia |
|                                         | Suporte a caracteres de dois bytes                              | Na Backlog de engenharia |
|    **Enorme**            | APIs de gráfico para descoberta eletrônica avançada                              | Em desenvolvimento |
|                                         | Conectores de dados primários                              | Na Backlog de engenharia |
|                                         | Conectores de dados de terceiros                              | Na Backlog de engenharia |
|                                         | APIs de gráfico para o Microsoft Teams exportar dados                              | Na Backlog de engenharia |

<sup>1</sup> o status identificado está sujeito a alterações à medida que os planos e as prioridades do projeto são reavaliados.<br/>

**Ponto de decisão**: *decida se os recursos de conformidade atendem às necessidades da sua organização.*
