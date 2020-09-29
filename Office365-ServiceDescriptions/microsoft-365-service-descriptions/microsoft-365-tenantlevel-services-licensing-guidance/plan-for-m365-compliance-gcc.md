---
title: Planejar a conformidade com o Microsoft 365 – GCC
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Esta orientação é para profissionais de ti que estão conduzindo implantações do Office 365 em entidades governamentais, estaduais, locais, tribal ou de governos da região, ou outras entidades que lidam com os dados sujeitos a normas e requisitos governamentais, onde o uso do Microsoft 365 governamental-GCC é adequado para atender a esses requisitos.
ms.openlocfilehash: 564c8c55b1659d80ffa18802e623634088740ba5
ms.sourcegitcommit: e342174df76128430dfc8c971716da5c4b2942ac
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/28/2020
ms.locfileid: "48293867"
---
# <a name="plan-for-microsoft-365-compliance--gcc"></a>Planejar a conformidade com a Microsoft 365 – GCC

Esta orientação é para profissionais de ti que estão conduzindo implantações do Office 365 em entidades governamentais, estaduais, locais, tribal ou de governos da região, ou outras entidades que lidam com os dados sujeitos a normas e requisitos governamentais, onde o uso do Microsoft 365 governamental-GCC é adequado para atender a esses requisitos.

> [!NOTE]
> Se sua organização já atendeu aos requisitos de qualificação do governo Microsoft 365 e foram aplicados e foram aceitos no programa, você pode ignorar as etapas 1 e 2 e ir diretamente para a etapa 3.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---gcc-and-meets-eligibility-requirements"></a>Etapa 1. Determinar se sua organização precisa do Microsoft 365 governamentais-GCC e atende aos requisitos de qualificação

O ambiente Microsoft 365 governamental-GCC está em conformidade com os requisitos do governo dos EUA para serviços de nuvem, incluindo FedRAMP moderado e requisitos para justiça criminal e sistemas de informações de tributação Federal (tipos de dados CJI e FTI).

Além de aproveitar os recursos e as funcionalidades do Office 365, as organizações se beneficiam dos seguintes recursos, que são exclusivos do Microsoft 365 governamental-GCC:

- O conteúdo do cliente da sua organização é logicamente separado do conteúdo do cliente nos serviços comerciais do Office 365 da Microsoft.

- O conteúdo do cliente da sua organização é armazenado dentro dos Estados Unidos.

- O acesso ao conteúdo do cliente da sua organização é restrito à equipes selecionadas da Microsoft.

- O Microsoft 365 governamental-GCC está em conformidade com certificações e confirações necessárias para os clientes do setor público nos EUA.

Você pode encontrar mais informações sobre a oferta Microsoft 365 governamentais-GCC para clientes do governo dos EUA nos [planos do governo do Office 365](https://products.office.com/government/compare-office-365-government-plans), incluindo requisitos de qualificação.

A [Descrição do serviço governo dos EUA do Office 365](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government) descreve os benefícios da plataforma, que são centralizados em atender aos requisitos de conformidade nos Estados Unidos.

> [!TIP]
> Você pode querer transferir as tabelas de informações na descrição do serviço para uma pasta de trabalho do Excel e adicionar duas colunas: **relevantes para minha organização**   e **atender às necessidades da minha organização y/n**. Em seguida, você pode revisar essa lista com seus colegas para confirmar que esse serviço atende às necessidades da sua organização.

> [!NOTE]
> O Microsoft 365 governamental-GCC só está disponível nos Estados Unidos. Clientes governamentais não americanos podem escolher entre vários [planos governamentais do Office 365](https://products.office.com/government/compare-office-365-government-plans).

**Pontos de decisão**: <br/>
- *Decida se o Microsoft 365 governamentais-GCC é apropriado para sua organização.*
- *Confirme se a sua organização atende aos requisitos de qualificação.*

## <a name="step-2-apply-for-microsoft-365-government---gcc"></a>Etapa 2. Aplicar para o Microsoft 365 governamental-GCC

Para ter decidido que esse serviço é adequado para sua organização, inicie o processo de [aplicação desse serviço](https://products.office.com/government/eligibility-validation).

## <a name="step-3-understand-microsoft-365-government---gcc-default-security-settings"></a>Etapa 3. Entender as configurações de segurança padrão do Microsoft 365 governo-GCC

Recomendamos que você reserve um tempo para revisar cuidadosamente suas configurações de administrador e segurança antes de modificá-las e considere o impacto sobre a conformidade antes de fazer qualquer alteração nas configurações de segurança padrão.

**Ponto de decisão**: *decida se você modificará qualquer uma das configurações de segurança do Microsoft 365 governo-gcc padrão, resolvendo para entender primeiro o impacto de qualquer alteração que você possa fazer.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gccsup1sup"></a>Etapa 4. Entender quais recursos estão atualmente indisponíveis ou estão desabilitados por padrão no Microsoft 365 governamentais – GCC<sup>1</sup>

Para acomodar os requisitos de nossos clientes de nuvem governamental, há algumas diferenças entre os planos Microsoft 365 governamentais-GCC e Enterprise. Consulte a tabela a seguir para ver quais recursos estão disponíveis.<br><br>

| Área | Recurso | Status de GCC |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Proteção de informações**              | Rótulo unificado e rótulos de confidencialidade         | Disponível              |
|                                         | Rótulos de contêiner para o SharePoint Online, grupos do Office          | Implementando              |
|                                         | Rotular automaticamente com base em tipos de dados confidenciais para o Excel online, SharePoint Online, OneDrive for Business                      | Implementando              |
|                                         | Rótulos baseados em tipos de dados confidenciais para clientes do Microsoft Win32 e do Mac            | Na Backlog de engenharia |
|                                         | Rotular automaticamente com base em tipos de dados confidenciais para o Win 32, Mac |  Na Backlog de engenharia              |
|                                         | Rotular automaticamente com base em tipos de dados confidenciais para o Teams                                       |Na Backlog de engenharia              |
|                                         | Rotular automaticamente com base em tipos de dados confidenciais para dispositivos móveis                            |Na Backlog de engenharia |
|                                         | Rótulos e políticas associadas com base em consultas                            | Disponível |
|                                         | Explorador de Atividade de Rótulo                           | Na Backlog de engenharia  |
|                                         | Classificadores de treinamento                              | Na Backlog de engenharia              |
|                                         | Criptografia básica de mensagens do Office 365 (E3)                            | Disponível              |
|                                         | Criptografia avançada de mensagem do Office 365 (E5)  | Disponível              |
|                                         | Chave de Cliente do Office 365    | Disponível |
|                                         | Traga sua chave (BYOK) para o ciclo de vida de provisionamento de chave gerenciado pelo cliente                            | Disponível |
|                                         | Manter sua própria chave (HYOK) que abrange a proteção de informações do Azure e o Active Directory (AD) Rights Management para cenários altamente regulamentados (versão prévia)                         | Disponível |
|                                         | Criptografia de Chave Dupla                           | Na Backlog de engenharia |
|                                         | Prevenção de perda de dados (DLP) para arquivos e email         | Disponível |
|                                         | DLP para chat de equipes e conversas de canal         | Implementando |
|                                         | Correspondência exata dos dados de DLP | Na Backlog de engenharia |
|                                         | Ponto de extremidade de DLP | Na Backlog de engenharia |
| **Governança de informações** | Arquivamento de email                                       | Disponível              |
|                                         | Bloqueio de preservação          | Disponível              |
|                                         | Importar PST                      | Disponível              |
|                                         | Rótulos manuais de retenção de não registros            | Disponível |
|                                         | Rótulos de retenção padrão para bibliotecas, pastas e conjuntos de documentos do SharePoint/OneDrive for Business; Caixas de entrada do Exchange; e grupos do Office 365 | Disponível              |
|                                         | Políticas de retenção para toda a organização; locais ou usuários específicos; e automaticamente com base em uma condição específica (por exemplo, palavras-chave ou informações confidenciais)                                       | Disponível              |
|                                         | Políticas de retenção com classificador treinado                            | Na Backlog de engenharia |
|                                         | Políticas de retenção para o Yammer e o Microsoft Teams                            | Na Backlog de engenharia |
|                                         | Rótulos de registros manuais                           | Disponível              |
|                                         | Rótulos de registro padrão para bibliotecas, pastas e conjuntos de documentos do SharePoint, do OneDrive for Business; e grupos do Office 365                              | Disponível              |
|                                         | Políticas de registro automático com base em condições específicas (por exemplo, palavras-chave ou informações confidenciais); e com base em um evento                            | Disponível              |
|                                         | Revisão de disposição  | Disponível              |
|                                         | Gerente de planejamento de arquivos    | Disponível |
|                                         | Prova de alienação                            | Disponível |
|                                         | Registros normativos                         | Na Backlog de engenharia |
|                                         | Imposição de licenciamento de gerenciamento de registros                           | Na Backlog de engenharia |
|                                         | Análise de disposição de vários estágios de gerenciamento de registros | Na Backlog de engenharia |
|                                         | Explorador de Atividade de Rótulo | Na Backlog de engenharia |
|                                         | Classificadores de treinamento | Na Backlog de engenharia |
|                                         | Rótulo unificado e rótulos de confidencialidade         | Na Backlog de engenharia |
| **Gerenciamento de risco interno**             | Sistema de Proteção de Dados do cliente                                | Disponível            |
|                                         | Indicadores do Office para Teams, sites do SharePoint, mensagens de email                         | Implementando |
|                                         | Roubo de dados por parte de usuários                        | Implementando |
|                                         | Vazamentos de dados gerais                                | Implementando              |
|                                         | Investigar alertas de gerenciamento de risco do insider                                   | Implementando              
|                                         | Painel de casos de gerenciamento de risco do Insider, navegador de conteúdo e modelos de aviso | Implementando |
|                                         | Escalonar para investigação de descoberta eletrônica avançada | Implementando|
|                                         | Vazamentos de dados por usuários de prioridade (visualização) | na Backlog de engenharia |
|                                         | Vazamentos de dados por usuários descontentes (visualização) | na Backlog de engenharia |
|                                         | Violações de política de segurança geral (versão prévia) | na Backlog de engenharia |
|                                         | Violações de política de segurança por usuários de prioridade, que fazem parte de usuários, usuários insatisfeitos (visualização) | na Backlog de engenharia |
|                                         | Personalização de política (versão prévia) | na Backlog de engenharia |
|                                         | Exportar alertas (versão prévia) | na Backlog de engenharia |
|                                         | Grupos de usuários de prioridade (visualização) | na Backlog de engenharia |
|                                         | Criar políticas de cliente, 3 pré-configurado para conformidade de comunicação (incl. políticas de supervisão)  | Implementando |
|                                         | Conformidade de comunicação (incl. políticas de supervisão) suporte à mensagem de Teams, Exchange e remove Teams | Implementando |
|                                         | Conformidade de comunicação (incluindo políticas de supervisão) alertas de acesso; modelos de aviso; painel de política de comunicação | Implementando  |
|                                         | Conformidade de comunicação (incluindo políticas de supervisão) escalonar para investigação para descoberta eletrônica avançada | Implementando |
|                                         | Conformidade de comunicação (incluindo políticas de supervisão) detectar conteúdo adulto | Implementando |
|                                         | Barreiras de informações | Na Backlog de engenharia |
|                                         | Gerenciamento de acesso privilegiado                    | Na Backlog de engenharia |
| **Descobrir & responder**                  | Descoberta eletrônica principal: preservação no local                            | Disponível              |
|                                         | Descoberta eletrônica principal: gerenciamento de casos                                 | Disponível              |
|                                         | Descoberta eletrônica principal: pesquisa                                          | Disponível              |
|                                         | Descoberta eletrônica principal: exportar                                          | Disponível              |
|                                         | Descoberta eletrônica principal: descriptografia do RMS                                  | Disponível              |
|                                         | Descoberta eletrônica principal: exportação nativa                                   | Disponível              |
|                                         | Descoberta eletrônica principal: auditoria                                        | Disponível              |
|                                         | Descoberta eletrônica avançada: processamento avançado                             | Disponível |
|                                         | Descoberta eletrônica avançada: encadeamento de email                                 | Disponível |
|                                         | Descoberta eletrônica avançada: identificação próxima duplicada                   | Disponível |
|                                         | Descoberta eletrônica avançada: temas                                          | Disponível |
|                                         | Descoberta eletrônica avançada: codificação de previsão                               | Disponível |
|                                         | Descoberta eletrônica avançada: exportação processada com o arquivo de carregamento                 | Disponível |
|                                         | Descoberta eletrônica avançada: marcação                                         | Disponível |
|                                         | Descoberta eletrônica avançada: visualizadores                                         | Disponível |
|                                         | Descoberta eletrônica avançada: redaçãos                                      | Disponível |
|                                         | Descoberta eletrônica avançada: filtragem                                       | Disponível |
|                                         | Descoberta eletrônica avançada: mapeamento de carga de trabalho                   | Disponível |
|                                         | Descoberta eletrônica avançada: comunicações de responsáveis                        | Disponível |
|                                         | Descoberta eletrônica avançada: conjuntos de revisão                                     | Disponível |
|                                         | Descoberta eletrônica avançada: revisar e anotar                             | Disponível |
|                                         | Descoberta eletrônica avançada: inclusão de não-Office 365                        | Disponível |
|                                         | Descoberta eletrônica avançada: relatório de termos de pesquisa                              | Disponível |
|                                         | Auditoria básica                              | Disponível |
|                                         | Auditoria avançada: acesso a eventos cruciais (por exemplo, mailitemsaccessed)                              | Implementando |
|                                         | Retenção de log de auditoria avançada (1 ano)                               | Implementando |
|                                         | Auditoria avançada maior largura de banda para API de atividade de gerenciamento                              | Implementando |
|    **Gerenciamento de Conformidade**            | Gerente de conformidade e Pontuação                              | Na Backlog de engenharia |




<sup>1</sup> o status identificado está sujeito a alterações à medida que os planos e as prioridades do projeto são reavaliados.<br/>
<sup>2</sup> o aplicativo manual de rótulos requer o [cliente de proteção de informações do Azure (AIP) versão 1](https://docs.microsoft.com/azure/information-protection/rms-client/client-version-release-history).


**Ponto de decisão**: *decida se os recursos de conformidade atendem às necessidades da sua organização.*
