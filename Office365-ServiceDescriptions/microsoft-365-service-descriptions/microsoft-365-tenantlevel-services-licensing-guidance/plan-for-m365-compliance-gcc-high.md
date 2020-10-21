---
title: Planejar a conformidade com o Microsoft 365 – GCC High
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Esta orientação é para profissionais de ti que estão gerando implantações do Office 365 em entidades governamentais americanas ou outras entidades que lidam com os dados sujeitos às normas e aos requisitos governamentais, em que o uso do Microsoft 365 governamental – GCC High é adequado para atender a esses requisitos.
ms.openlocfilehash: df0d78d40e91c171b2a512de4b7d8371ceb59995
ms.sourcegitcommit: dcacd13c1cf1c60526c48fc923db5de643facc07
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/20/2020
ms.locfileid: "48626882"
---
# <a name="plan-for-microsoft-365-compliance--gcc-high"></a>Plano para conformidade com o Microsoft 365 – GCC High

Esta orientação é para profissionais de ti que estão gerando implantações do Office 365 em entidades governamentais americanas ou outras entidades que lidam com os dados sujeitos às normas e aos requisitos governamentais, em que o uso do Microsoft 365 governamental – GCC High é adequado para atender a esses requisitos.

> [!NOTE]
>Se sua organização já atendeu aos requisitos de qualificação do governo Microsoft 365 – GCC altos e foram aplicados e foram aceitos no programa, você pode ignorar as etapas 1 e 2 e ir diretamente para a etapa 3.
 
## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government--gcc-high-and-meets-eligibility-requirements"></a>Etapa 1. Determinar se sua organização precisa do Microsoft 365 governamentais – GCC High e atenda aos requisitos de qualificação

O ambiente High Microsoft 365 governamental-GCC é compatível com os requisitos do governo dos EUA para serviços em nuvem. Além de aproveitar os recursos e as funcionalidades do Office 365, as organizações se beneficiam dos seguintes recursos, que são exclusivos do governo da Microsoft 365 – GCC High:

- O conteúdo do cliente da sua organização é logicamente separado do conteúdo do cliente nos serviços comerciais do Office 365 da Microsoft.
- O conteúdo do cliente da sua organização é armazenado dentro dos Estados Unidos.
- O acesso ao conteúdo do cliente da sua organização é restrito à equipes selecionadas da Microsoft.
- Microsoft 365 governamental – GCC é compatível com certificações e confirações necessárias para os clientes do setor público nos EUA.

Você pode encontrar mais informações sobre a oferta do Microsoft 365 governamental – GCC High para clientes do governo dos EUA nos [planos governamentais do Office 365](https://products.office.com/government/compare-office-365-government-plans), incluindo requisitos de qualificação.

A [Descrição do serviço governo dos EUA do Office 365](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government) descreve os benefícios da plataforma, que são centralizados em atender aos requisitos de conformidade nos Estados Unidos.

> [!TIP]
> Você pode querer transferir as tabelas de informações na descrição do serviço para uma pasta de trabalho do Excel e adicionar duas colunas: **relevantes para minha organização**   e **atender às necessidades da minha organização y/n**. Em seguida, você pode revisar essa lista com seus colegas para confirmar que esse serviço atende às necessidades da sua organização.

**Pontos de decisão**:<br/>
- *Decida se o Microsoft 365 governamentais – GCC-High é apropriado para sua organização.*
- *Confirme se a sua organização atende aos requisitos de qualificação.*

> [!NOTE]
> O Microsoft 365 governamental-GCC High só está disponível nos Estados Unidos. Clientes governamentais não americanos podem escolher entre vários [planos governamentais do Office 365](https://products.office.com/government/compare-office-365-government-plans).

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>Etapa 2. Aplicar para o Microsoft 365 governamentais – GCC-High

Para ter decidido que esse serviço é adequado para sua organização, inicie o processo de [aplicação desse serviço](https://products.office.com/government/eligibility-validation).
 
## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>Etapa 3. Entender o Microsoft 365 governamental – GCC-High configurações de segurança padrão

Recomendamos que você reserve um tempo para revisar cuidadosamente suas configurações de administrador e segurança antes de modificá-las e considere o impacto sobre a conformidade antes de fazer qualquer alteração nas configurações de segurança padrão.

**Ponto de decisão**: *decida se você modificará qualquer uma das configurações de segurança do Microsoft 365 governamentais – GCC-High, resolvendo primeiro entender o impacto de qualquer alteração que você possa fazer.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-highsup1sup"></a>Etapa 4. Entender quais recursos estão atualmente indisponíveis ou estão desabilitados por padrão no Microsoft 365 governamentais – GCC-alto<sup>1</sup>

Para atender aos requisitos de nossos clientes de nuvem governamental, há algumas diferenças entre os planos do Microsoft 365 governamentais – GCC-High e Enterprise. Consulte a tabela a seguir para ver quais recursos estão disponíveis.


|                                         | Recurso                                         | Status de GCC             |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Proteção de informações**              | Cliente e scanner de rótulo unificado         | Disponível              |
|                                         | Correspondência de dados exata          | Disponível              |
|                                         | Classificação automática e rótulo para o Exchange Online, o SharePoint Online e o OneDrive                      | Implementando              |
|                                         | Classificação automática e rotulamento para aplicativos do Office (Word, Excel, PowerPoint, Outlook) em Web, Android, iOS, Windows e Mac            | Em desenvolvimento |
|                                         | Políticas orientadas por classificação com grupos do Office 365 |  Implementando              |
|                                         | Classificação automática e rotulamento para dispositivos móveis                                       |Na Backlog de engenharia              |
|                                         | Classificação automática e rotulamento para o Microsoft Teams                            |Na Backlog de engenharia |
|                                         | Classificação de dados: visão geral e explorador de atividade de conteúdo                            | Na Backlog de engenharia |
|                                         | Classificadores de aprendizado de máquina com rotulação automática                           | Na Backlog de engenharia  |
|                                         | Criptografia básica de mensagens do Office 365 (E3)                            | Disponível              |
|                                         | Criptografia avançada de mensagem do Office 365 (E5)  | Disponível              |
|                                         | Chave de Cliente do Office 365    | Disponível |
|                                         | Traga sua chave (BYOK) para o ciclo de vida de provisionamento de chave gerenciado pelo cliente                            | Disponível |
|                                         | Manter sua própria chave (HYOK) que abrange a proteção de informações do Azure e o Active Directory (AD) Rights Management para cenários altamente regulamentados (versão prévia)                         | Disponível |
|                                         | Criptografia de Chave Dupla                           | Em desenvolvimento |
|                                         | Coautoria em documentos criptografados usando aplicativos Web do WXP         | Na Backlog de engenharia |
|                                         | Prevenção de perda de dados para arquivos e email         | Disponível |
|                                         | Prevenção de perda de dados para chat de equipes e conversas de canal | Na Backlog de engenharia |
|                                         | Ponto de extremidade de prevenção contra perda de dados | Na Backlog de engenharia |
| **Governança de informações** | Governança de informações: arquivamento de E-mails                                       | Disponível              |
|                                         | Governança de informações: bloqueio de preservação          | Disponível              |
|                                         | Governança de informações: importar PST                      | Disponível              |
|                                         | Governança de informações: rótulos manuais de retenção de não registros            | Disponível |
|                                         | Governança de informações: rótulos de retenção padrão para bibliotecas do SharePoint/OneDrive for Business, pastas e conjuntos de documentos; Caixas de entrada do Exchange; e grupos do Office 365 | Disponível              |
|                                         | Governança de informações: políticas de retenção para toda a organização; locais ou usuários específicos; automaticamente com base em uma condição específica (por exemplo, palavras-chave ou informações confidenciais); e com base em um evento                                       | Disponível              |
|                                         | Governança de informações: rótulos de retenção usando a classificação do SharePoint Syntex                            | Na Backlog de engenharia |
|                                         | Governança de informações: políticas de retenção com classificador treinado                            | Na Backlog de engenharia |
|                                         | Governança de informações: políticas de retenção para o Yammer e o Microsoft Teams                            | Na Backlog de engenharia |
|                                         | Gerenciamento de registros: classificação manual para rótulos de registro                           | Disponível              |
|                                         | Gerenciamento de registros: rótulos de registro padrão para o SharePoint, bibliotecas do OneDrive for Business, pastas e conjuntos de documentos; e grupos do Office 365                              | Disponível              |
|                                         | Gerenciamento de registros: políticas de registro automático com base em condições específicas (por exemplo, palavras-chave ou informações confidenciais); e com base em um evento                            | Disponível              |
|                                         | Gerenciamento de registros: análise de disposição  | Disponível              |
|                                         | Gerenciamento de registros: Gerenciador de planos de arquivo    | Disponível |
|                                         | Gerenciamento de registros: prova de alienação                            | Disponível |
|                                         | Gerenciamento de registros: controle de versão de registros                         | Disponível |
|                                         | Gerenciamento de registros: registros normativos                         | Na Backlog de engenharia |
|                                         | Gerenciamento de registros: imposição de licenciamento                           | Na Backlog de engenharia |
|                                         | Gerenciamento de registros: análise de disposição de vários estágios | Na Backlog de engenharia |
|                                         | Gerenciamento de registros: explorador de atividade de rótulo | Na Backlog de engenharia |
|                                         | Gerenciamento de registros: classificadores estagiários | Na Backlog de engenharia |
| **Gerenciamento de risco do insider**             | Sistema de Proteção de Dados do cliente                                | Disponível            |
|                                         | Gerenciamento de risco do insider: indicadores do Office para Teams, sites do SharePoint, mensagens de email                         | Em desenvolvimento |
|                                         | Gerenciamento de risco do insider: roubo de dados por parte de usuários                        | Em desenvolvimento |
|                                         | Gerenciamento de risco do insider: vazamentos de dados gerais                                | Em desenvolvimento              |
|                                         | Gerenciamento de risco do insider: investigar alertas de gerenciamento de risco                                   | Em desenvolvimento              |
|                                         | Gerenciamento de risco do insider: painel de casos, Gerenciador de conteúdo e modelos de aviso | Em desenvolvimento |
|                                         | Gerenciamento de risco do insider: escalonar para investigação de descoberta eletrônica avançada | Em desenvolvimento|
|                                         | Gerenciamento de risco do insider: modelos de política para vazamentos de dados por usuários prioritários (visualização) | Na Backlog de engenharia |
|                                         | Gerenciamento de risco do insider: modelos de política para vazamentos de dados por usuários descontentes (visualização) | Na Backlog de engenharia |
|                                         | Gerenciamento de risco do insider: modelos de política para violações de política de segurança geral (versão prévia) | Na Backlog de engenharia |
|                                         | Gerenciamento de risco do insider: modelos de política para violações de política de segurança por usuários de prioridade, usuários de parte, usuários descontentes (visualização) | Na Backlog de engenharia |
|                                         | Gerenciamento de risco do insider: personalização de política (visualização) | Na Backlog de engenharia |
|                                         | Gerenciamento de risco do insider: exportar alertas (visualização) | Na Backlog de engenharia |
|                                         | Gerenciamento de risco do insider: grupos de usuários de prioridade (visualização) | Na Backlog de engenharia |
|                                         | Conformidade de comunicação (incl. políticas de supervisão): criar políticas de cliente, 3 pré-configurado  | Em desenvolvimento |
|                                         | Conformidade de comunicação (incl. políticas de supervisão): suporte à mensagem de Teams, Exchange e remove Teams | Em desenvolvimento |
|                                         | Conformidade de comunicação (incl. políticas de supervisão): alertas de acesso; modelos de aviso; painel de política de comunicação | Em desenvolvimento  |
|                                         | Conformidade de comunicação (incl. políticas de supervisão): escalonar para investigação para descoberta eletrônica avançada | Em desenvolvimento |
|                                         | Conformidade de comunicação (incl. políticas de supervisão): detectar conteúdo adulto | Em desenvolvimento |
|                                         | Barreiras de informações | Na Backlog de engenharia |
|                                         | Gerenciamento de acesso privilegiado                    | Na Backlog de engenharia |
| **Descobrir & responder**                  | Descoberta eletrônica principal: preservação no local                            | Disponível              |
|                                         | Descoberta eletrônica principal: gerenciamento de casos                                 | Disponível              |
|                                         | Descoberta eletrônica principal: pesquisa                                          | Disponível              |
|                                         | Descoberta eletrônica principal: exportar                                          | Disponível              |
|                                         | Descoberta eletrônica principal: descriptografia do RMS                                  | Disponível              |
|                                         | Descoberta eletrônica principal: exportação nativa                                   | Disponível              |
|                                         | Descoberta eletrônica principal: auditoria                                        | Disponível              |
|                                         | Descoberta eletrônica principal: centro de conformidade da Microsoft expandiu o suporte para pesquisar e exportar itens na lixeira do SharePoint e do OneDrive for Business                                        | Em desenvolvimento              |
|                                         | Descoberta eletrônica avançada: processamento avançado                             | Disponível |
|                                         | Descoberta eletrônica avançada: painel                             | Disponível |
|                                         | Descoberta eletrônica avançada: encadeamento de email                                 | Disponível |
|                                         | Descoberta eletrônica avançada: exportar (baixar, exportar, adicionar a outro conjunto de revisão)                   | Disponível |
|                                         | Descoberta eletrônica avançada: filtragem                                          | Disponível |
|                                         | Descoberta eletrônica avançada: bloqueio legal para mensagens de canais privadas do teams                               | Disponível |
|                                         | Descoberta eletrônica avançada: identificação próxima duplicada                 | Disponível |
|                                         | Descoberta eletrônica avançada: fontes de dados não-custodial                                         | Disponível |
|                                         | Descoberta eletrônica avançada: inclusão de não-Office 365                                         | Disponível |
|                                         | Descoberta eletrônica avançada: codificação de previsão                                      | Disponível |
|                                         | Descoberta eletrônica avançada: exportação processada com o arquivo de carregamento                                       | Disponível |
|                                         | Descoberta eletrônica avançada: redaçãos                   | Disponível |
|                                         | Descoberta eletrônica avançada: conjuntos de revisão                        | Disponível |
|                                         | Descoberta eletrônica avançada: analisar dados (dados de consulta, marcas inteligentes, painel) e anotar (redigir)                                     | Disponível |
|                                         | Descoberta eletrônica avançada: relatório de termos de pesquisa                             | Disponível |
|                                         | Descoberta eletrônica avançada: correção de erro de item único                        | Disponível |
|                                         | Descoberta eletrônica avançada: exportação de PST de suporte                              | Implementando |
|                                         | Descoberta eletrônica avançada: marcação                              | Disponível |
|                                         | Descoberta eletrônica avançada: relatórios de locatário                              | Disponível |
|                                         | Descoberta eletrônica avançada: temas                               | Disponível |
|                                         | Descoberta eletrônica avançada: visualizadores                              | Disponível |
|                                         | Descoberta eletrônica avançada: descoberta eletrônica avançada do Yammer no centro de conformidade da Microsoft                              | Disponível |
|                                         | Descoberta eletrônica avançada: suporte a CJK/dobrar byte para descoberta eletrônica avançada                              | Em desenvolvimento |
|                                         | Descoberta eletrônica avançada: APIs de gráfico                              | Em desenvolvimento |
|                                         | Descoberta eletrônica avançada: reações de equipes de suporte                             | Em desenvolvimento |
|                                         | Descoberta eletrônica avançada: centro de conformidade da Microsoft expandiu o suporte para pesquisar e exportar itens na lixeira do SharePoint e do OneDrive for Business                               | Na Backlog de engenharia |
|                                         | Auditoria básica                              | Disponível |
|                                         | Auditoria avançada: acesso a eventos cruciais (por exemplo, mailitemsaccessed)                              | Disponível |
|                                         | Auditoria avançada: maior largura de banda para a API de atividade de gerenciamento                              | Disponível |
|                                         | Auditoria avançada: controle legal para mensagens de canais privadas do teams                              | Disponível |
|                                         | Auditoria avançada: retenção de logs (1 ano)                              | Disponível |
|                                         | Auditoria avançada: disponibilidade do centro de conformidade e segurança                              | Disponível |
|                                         | Auditoria avançada: retenção de longo prazo em logs de auditoria                              | Na Backlog de engenharia |
|                                         | Auditoria avançada: eventos de envio de email direto e email                              | Na Backlog de engenharia |
|                                         | Auditoria avançada: insights de auditoria processados                              | Na Backlog de engenharia |
|                                         | Auditoria avançada: eventos de termos de pesquisa no Exchange Online e no SharePoint Online                              | Na Backlog de engenharia |
|    **Gerenciamento de Conformidade**            | Centro de conformidade e segurança do Microsoft 365                              | Disponível |
|                                         | Gerenciador de Conformidade (Visualização)                                 | Na Backlog de engenharia              |
|                                         | Segurança no aplicativo na nuvem da Microsoft                                 | Na Backlog de engenharia              |
|                                         | Suporte a caracteres de dois bytes                                 | Na Backlog de engenharia              |

<sup>1</sup> o status identificado está sujeito a alterações à medida que os planos e as prioridades do projeto são reavaliados.<br/>
<sup>2</sup> o aplicativo manual de rótulos requer o [cliente de proteção de informações do Azure (AIP) versão 1](https://docs.microsoft.com/azure/information-protection/rms-client/client-version-release-history). 


**Ponto de decisão**: *decida se os recursos de conformidade atendem às necessidades da sua organização.*
