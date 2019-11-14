---
title: Planejar as implantações do Microsoft 365 Compliance-DoD
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Esta orientação é para profissionais de ti que estão conduzindo implantações do Office 365 em entidades governamentais americanas ou outras entidades que lidam com os dados sujeitos a regulamentações e requisitos governamentais, em que o uso do Microsoft 365 governamentais – DoD é adequado para atender a esses requisitos.
ms.openlocfilehash: 5356c019351108478c6fd27af3fa451dd2ec036a
ms.sourcegitcommit: 7ceeebe425223c2cc8d6bd26a4a79b1e1d329b6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 11/14/2019
ms.locfileid: "38319479"
---
# <a name="plan-for-microsoft-365-compliance---dod-deployments"></a>Planejar as implantações do Microsoft 365 Compliance-DoD

Esta orientação é para profissionais de ti que estão conduzindo implantações do Office 365 em entidades governamentais americanas ou outras entidades que lidam com os dados sujeitos a regulamentações e requisitos governamentais, em que o uso do Microsoft 365 governamentais – DoD é adequado para atender a esses requisitos.

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

Para atender aos requisitos de nossos clientes de nuvem governamental, há algumas diferenças entre os planos Microsoft 365 governamentais-DoD e Enterprise. Consulte a tabela a seguir para ver quais recursos estão disponíveis.


|         |Recurso  |Status do DoD  |
|---------|---------|---------|
|**Governança de proteção de informações &** |Arquivamento                                       |  Disponível             |
|                                        |Rótulos e políticas manuais<sup>2</sup>          |  Disponível             |
|                                        |Aplicação automática de rótulos                      | Na Backlog de engenharia |
|                                        |Rótulos baseados em tipos de dados confidenciais            | Na Backlog de engenharia |
|                                        |Rótulos e políticas associadas com base em consultas | Na Backlog de engenharia |
|                                        |Plano de arquivos                                       | Na Backlog de engenharia |
|                                        |Políticas recomendadas                            | Na Backlog de engenharia |
|                                        |Filtros de importação inteligente                            | Na Backlog de engenharia |  
|                                        |Retenção baseada em eventos                           | Na Backlog de engenharia |
|                                        |Análise de disposição                              | Na Backlog de engenharia |
|                                        |Barreiras de informações                            | Disponível              |
|                                        |Prevenção de perda de dados (DLP) para arquivos e email  | Disponível              |
|                                        |DLP para chat de equipes e conversas de canal    | Na Backlog de engenharia |
|**Gerenciamento de risco do insider**             |Criptografia de mensagem avançada                     | Disponível              |
|                                        |Conformidade em comunicações                        | Na Backlog de engenharia |
|                                        |Sistema de Proteção de Dados do Cliente                                | Disponível              |
|                                        |Chave de Cliente                                    | Disponível              |
|                                        |Gerenciamento de acesso privilegiado                    | Na Backlog de engenharia |
|**Descobrir & responder**                  |Reserva in-loco                            | Disponível              |
|                                        |Gerenciamento de casos                                 | Disponível              |
|                                        |Pesquisa                                          | Disponível              |
|                                        |Exportar                                          | Disponível              |
|                                        |Descriptografia do RMS                                  | Disponível              |
|                                        |Exportação nativa                                   | Disponível              |
|                                        |Processamento avançado                             | Na Backlog de engenharia |
|                                        |Threading de emails                                 | Na Backlog de engenharia |
|                                        |Identificação próxima duplicada                   | Na Backlog de engenharia |
|                                        |Temas                                          | Na Backlog de engenharia |
|                                        |Codificação preditiva                               | Na Backlog de engenharia |
|                                        |Exportação processada com o arquivo de carregamento                 | Na Backlog de engenharia |
|                                        |Marcação                                         | Na Backlog de engenharia |
|                                        |Visualizadores                                         | Na Backlog de engenharia |
|                                        |Redaçãos                                      | Na Backlog de engenharia |
|                                        |Filtragem                                       | Na Backlog de engenharia |
|                                        |Mapeamento de carga de trabalho                   | Na Backlog de engenharia |
|                                        |Comunicações de responsáveis                        | Na Backlog de engenharia |
|                                        |Revisar conjuntos                                     | Na Backlog de engenharia |
|                                        |Revisar e anotar                             | Na Backlog de engenharia |
|                                        |Ingestão de 365 não-Office                        | Na Backlog de engenharia |
|                                        |Relatório de termos de pesquisa                              | Na Backlog de engenharia |

<sup>1</sup> o status identificado está sujeito a alterações à medida que os planos e as prioridades do projeto são reavaliados.<br/>
<sup>2</sup> o aplicativo manual de rótulos requer o [cliente de proteção de informações do Azure (AIP) versão 1](https://docs.microsoft.com/azure/information-protection/rms-client/client-version-release-history).


**Ponto de decisão**: *decida se os recursos de conformidade atendem às necessidades da sua organização.*
