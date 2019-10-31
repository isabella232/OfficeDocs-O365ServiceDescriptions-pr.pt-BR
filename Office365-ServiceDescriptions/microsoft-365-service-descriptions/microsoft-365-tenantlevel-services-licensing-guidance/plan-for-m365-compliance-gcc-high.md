---
title: Plano para o Microsoft 365 Compliance-GCC alto
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ROBOTS: NOINDEX, NOFOLLOW
description: Esta orientação é para profissionais de ti que estão conduzindo implantações do Office 365 em entidades governamentais americanas ou outras entidades que lidam com os dados sujeitos a regulamentações e requisitos governamentais, em que o uso do Microsoft 365 governamental – GCC High é apropriado para atender a esses requisitos.
ms.openlocfilehash: 4ddc98b4784741e62d0cdabefb9d36d7b11ac560
ms.sourcegitcommit: f69656f34dcb4f4e9a5857d8c4236084c94a05b1
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/31/2019
ms.locfileid: "37890458"
---
# <a name="plan-for-microsoft-365-compliance--gcc-high"></a>Plano para conformidade com o Microsoft 365 – GCC High

Esta orientação é para profissionais de ti que estão conduzindo implantações do Office 365 em entidades governamentais americanas ou outras entidades que lidam com os dados sujeitos a regulamentações e requisitos governamentais, em que o uso do Microsoft 365 governamental – GCC High é apropriado para atender a esses requisitos.

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
> Você pode querer transferir as tabelas de informações na descrição do serviço para uma pasta de trabalho do Excel e adicionar duas colunas: **relevantes para minha organização** e **atender às necessidades da minha organização y/n**. Em seguida, você pode revisar essa lista com seus colegas para confirmar que esse serviço atende às necessidades da sua organização.

**Pontos de decisão**:<br/>
- *Decida se o Microsoft 365 governamentais – GCC-alto é apropriado para sua organização.*
- *Confirme se a sua organização atende aos requisitos de qualificação.*

> [!NOTE]
> O Microsoft 365 governamental-GCC High só está disponível nos Estados Unidos. Clientes governamentais não americanos podem escolher entre vários [planos governamentais do Office 365](https://products.office.com/government/compare-office-365-government-plans).

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>Etapa 2. Aplicar para o Microsoft 365 governamentais – GCC-alto

Para ter decidido que esse serviço é adequado para sua organização, inicie o processo de [aplicação desse serviço](https://products.office.com/government/eligibility-validation).
 
## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>Etapa 3. Entender as configurações de segurança padrão do Microsoft 365 governo – GCC-High

Recomendamos que você reserve um tempo para revisar cuidadosamente suas configurações de administrador e segurança antes de modificá-las e considere o impacto sobre a conformidade antes de fazer qualquer alteração nas configurações de segurança padrão.

**Ponto de decisão**: *decida se você modificará qualquer uma das configurações de segurança padrão do governo Microsoft 365 – gcc-alta, resolvendo para entender primeiro o impacto de qualquer alteração que você possa fazer.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-high"></a>Etapa 4. Entender quais recursos estão atualmente indisponíveis ou estão desabilitados por padrão no Microsoft 365 governamentais – GCC-alto * *

Para atender aos requisitos de nossos clientes de nuvem governamental, há algumas diferenças entre os planos Microsoft 365 governamentais – GCC-High e Enterprise. Consulte a tabela a seguir para ver quais recursos estão disponíveis.

|                                         | Recurso                                         | Status alto do GCC        |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Governança de proteção de informações &** | Arquivamento                                       | Disponível              |
|                                         | Rótulos e políticas manuais                      | Disponível              |
|                                         | Aplicação automática de rótulos                      | Na Backlog de engenharia |
|                                         | Rótulos baseados em tipos de dados confidenciais            | Na Backlog de engenharia |
|                                         | Rótulos e políticas associadas com base em consultas | Na Backlog de engenharia |
|                                         | Plano de arquivos                                       | Na Backlog de engenharia |
|                                         | Políticas recomendadas                            | Na Backlog de engenharia |
|                                         | Filtros de importação inteligente                            | Na Backlog de engenharia |
|                                         | Retenção baseada em eventos                           | Na Backlog de engenharia |
|                                         | Análise de disposição                              | Na Backlog de engenharia |
|                                         | Barreiras de informações                            | Disponível              |
|                                         | Prevenção de perda de dados (DLP) para arquivos e email  | Disponível              |
|                                         | DLP para chat de equipes e conversas de canal    | Na Backlog de engenharia |
| **Gerenciamento de risco do insider**             | Criptografia de mensagem avançada                     | Disponível              |
|                                         | Conformidade de comunicação                        | Na Backlog de engenharia |
|                                         | Sistema de Proteção de Dados do Cliente                                | Disponível              |
|                                         | Chave de Cliente                                    | Disponível              |
|                                         | Gerenciamento de acesso privilegiado                    | Na Backlog de engenharia |
| **Descobrir & responder**                  | Reserva in-loco                            | Disponível              |
|                                         | Gerenciamento de casos                                 | Disponível              |
|                                         | Pesquisa                                          | Disponível              |
|                                         | Exportar                                          | Disponível              |
|                                         | Descriptografia do RMS                                  | Disponível              |
|                                         | Exportação nativa                                   | Disponível              |
|                                         | Processamento avançado                             | Disponível              |
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

**Ponto de decisão**: *decida se os recursos de conformidade atendem às necessidades da sua organização.*
