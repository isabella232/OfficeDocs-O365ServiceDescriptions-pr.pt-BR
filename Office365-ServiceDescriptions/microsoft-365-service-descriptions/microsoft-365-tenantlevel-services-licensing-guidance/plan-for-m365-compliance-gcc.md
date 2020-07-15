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
ms.openlocfilehash: 650a4131e7d028222d46d48a1d7304363acd6167
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132455"
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

Para acomodar os requisitos de nossos clientes de nuvem governamental, há algumas diferenças entre os planos Microsoft 365 governamentais-GCC e Enterprise. Consulte a tabela a seguir para ver quais recursos estão disponíveis.

|                                         | **Recurso**                                     | **Status de GCC**         |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Governança de proteção de informações &** | Arquivamento                                       | Disponível              |
|                                         | Rótulos e políticas manuais<sup>2</sup>          | Disponível              |
|                                         | Aplicação automática de rótulos                      | Disponível              |
|                                         | Rótulos baseados em tipos de dados confidenciais            | Na Backlog de engenharia |
|                                         | Rótulos e políticas associadas com base em consultas | Disponível              |
|                                         | Plano de arquivos                                       | Disponível              |
|                                         | Políticas recomendadas                            | Na Backlog de engenharia |
|                                         | Filtros de importação inteligente                            | Na Backlog de engenharia |
|                                         | Retenção baseada em eventos                           | Disponível              |
|                                         | Análise de disposição                              | Disponível              |
|                                         | Barreiras de informações                            | Disponível              |
|                                         | Prevenção de perda de dados (DLP) para arquivos e email  | Disponível              |
|                                         | DLP para chat de equipes e conversas de canal    | Na Backlog de engenharia |
|                                         | Correspondência exata dos dados de DLP                            | Na Backlog de engenharia |
|                                         | Explorador de Atividade de Rótulo                         | Na Backlog de engenharia |
|                                         | Classificadores estagiários                           | Na Backlog de engenharia |
|                                         | Rótulo unificado e rótulos de confidencialidade         | Na Backlog de engenharia |
| **Gerenciamento de risco interno**             | Criptografia de mensagem avançada                     | Disponível              |
|                                         | Gerenciamento de riscos internos                         | Na Backlog de engenharia |
|                                         | Conformidade em comunicações                        | Na Backlog de engenharia |
|                                         | Sistema de Proteção de Dados do cliente                                | Disponível              |
|                                         | Chave de Cliente                                    | Disponível              |
|                                         | Gerenciamento de acesso privilegiado                    | Na Backlog de engenharia |
| **Descobrir & responder**                  | Reserva in-loco                            | Disponível              |
|                                         | Gerenciamento de casos                                 | Disponível              |
|                                         | Search                                          | Disponível              |
|                                         | Exportação                                          | Disponível              |
|                                         | Descriptografia do RMS                                  | Disponível              |
|                                         | Exportação nativa                                   | Disponível              |
|                                         | Auditoria                                        | Disponível              |
|                                         | Processamento avançado                             | Na Backlog de engenharia |
|                                         | Threading de emails                                 | Na Backlog de engenharia |
|                                         | Identificação próxima duplicada                   | Na Backlog de engenharia |
|                                         | Temas                                          | Na Backlog de engenharia |
|                                         | Codificação preditiva                               | Na Backlog de engenharia |
|                                         | Exportação processada com o arquivo de carregamento                 | Na Backlog de engenharia |
|                                         | Marcação                                         | Na Backlog de engenharia |
|                                         | Visualizadores                                         | Na Backlog de engenharia |
|                                         | Redaçãos                                      | Na Backlog de engenharia |
|                                         | Filtragem                                       | Na Backlog de engenharia |
|                                         | Mapeamento de carga de trabalho                   | Na Backlog de engenharia |
|                                         | Comunicações de responsáveis                        | Na Backlog de engenharia |
|                                         | Revisar conjuntos                                     | Na Backlog de engenharia |
|                                         | Revisar e anotar                             | Na Backlog de engenharia |
|                                         | Ingestão de 365 não-Office                        | Na Backlog de engenharia |
|                                         | Relatório de termos de pesquisa                              | Na Backlog de engenharia |

<sup>1</sup> o status identificado está sujeito a alterações à medida que os planos e as prioridades do projeto são reavaliados.<br/>
<sup>2</sup> o aplicativo manual de rótulos requer o [cliente de proteção de informações do Azure (AIP) versão 1](https://docs.microsoft.com/azure/information-protection/rms-client/client-version-release-history).


**Ponto de decisão**: *decida se os recursos de conformidade atendem às necessidades da sua organização.*
