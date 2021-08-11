---
title: Limites no Yammer
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- yammer-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: ''
description: Saiba mais sobre os limites de serviço no Yammer para Microsoft 365.
ms.openlocfilehash: 6ce13069239cc0b7b39adf2e9850b0cd46a12910f9dca6b61aea2600d7591402
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 08/06/2021
ms.locfileid: "54702260"
---
# <a name="limits-in-yammer"></a>Limites no Yammer

Saiba mais sobre os limites de serviço no Yammer para Microsoft 365.

## <a name="network-limits"></a>Limites de rede

| Recurso | Detalhes |
|---------|---------|
| Modo Nativo | [O modo](/yammer/configure-your-yammer-network/overview-native-mode) nativo é recomendado para o melhor suporte a longo prazo. Yammer redes no modo nativo Microsoft 365 têm recursos diferentes dos Yammer herdado. |
| Atualização em massa para administradores de rede | As atualizações em massa para usuários são suportadas para redes não nativas de 2.000 usuários ou menos. |
| Home Networks | As redes home não podem ser excluídas e recriadas. |

## <a name="file-limits"></a>Limites de arquivo

| Recurso | Detalhes |
|---------|---------|
| Tamanho máximo do arquivo e armazenamento | A migração para Microsoft 365 modo nativo para Yammer é recomendável para garantir que todos os arquivos sejam armazenados no SharePoint Online. <br/>Para Yammer arquivos armazenados em SharePoint: <ul><li>O tamanho máximo para um único anexo de arquivo é de 15 gigabytes (GB).</li><li>Não há limitações de dimensão para imagens, mas as SharePoint de tamanho máximo em sua organização se aplicam.</li><li>Qualquer tipo de arquivo pode ser adicionado, mas a visualização e a edição são limitadas a determinados tipos de arquivo.</li> </ul><br/>[SharePoint limites se](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-limits) aplicam Microsoft 365 [comunidades conectadas](/yammer/manage-yammer-groups/yammer-and-office-365-groups) no Yammer. <br/>Para arquivos armazenados no Yammer de arquivos: <br/><ul><li>O tamanho máximo para um único anexo de arquivo é de 5 gigabytes (GB) para redes Yammer Enterprise e 100 megabytes (MB) para redes Yammer Basic.</li><li>As dimensões máximas têm 7.680 pixels de largura e 4.320 pixels de altura e o tamanho máximo da imagem é de 10 megabytes (MB).</li></ul> <br/>Para obter mais informações sobre o uso da imagem, incluindo modelos e dimensões para fotos de capa, [consulte Yammer Recursos de Adoção.](https://adoption.microsoft.com/yammer/) |
| Número de anexos de arquivo por postagem | Cada postagem pode ter no máximo 100 arquivos. |
| Formatos de vídeo com suporte | Os seguintes tipos de vídeo são suportados para reprodução em linha: .wmv, .avi, .mpeg, .3gp, .flv, .mov, .mp4, .mpg, .ogm, .mkv, .ogv e .ogg. <br/>Yammer usa Serviços de Mídia do Azure para exibir vídeos carregados em Yammer. |
| Reprodução de vídeo em linha | O Microsoft Stream, SharePoint Online, YouTube e Vimeo têm suporte para reprodução em linha. |
| Acesso de convidados | Microsoft 365 O modo nativo para Yammer é necessário para suporte completo de convidados. <br/>Os convidados de nível de rede herdado podem ter problemas de acesso a arquivos. |
| Visualizações de link (abrir Graph objetos) | Links para sistemas internos que não podem ser resolvidos publicamente ou que exigem autenticação não exibirão visualizações válidas porque os metadados não podem ser extraídos. |

## <a name="yammer-live-event-limits"></a>Yammer de eventos ao vivo

| Recurso | Detalhes |
|---------|---------|
| Número de visualizadores de eventos ao vivo | Atualmente, o limite é de 10.000 participantes. Para eventos de um tamanho mais alto, trabalhe por meio do Programa de Assistência a Eventos [Ao Vivo.](https://resources.techcommunity.microsoft.com/live-events/assistance/) |
| Permissões de criação de eventos ao vivo | A permissão para criar eventos ao vivo no Stream é necessária. <br/>Community administradores no Yammer podem criar ou agendar eventos ao vivo. |
| Acesso de convidados | Membros da sua rede canônica podem criar ou participar de eventos ao vivo em Yammer. |
| Legenda fechada | Legendas fechadas não estão disponíveis para eventos ao vivo em Yammer. Uma atualização futura adicionará suporte para legendas fechadas. |
| Duração do evento | 4 horas |
| Eventos ao vivo simultâneos executados em Microsoft 365 ou Office 365 organização | 50 eventos por locatário |
| Limite de apresentadores? | 100 apresentadores |

Para obter mais limites em relação Microsoft Teams eventos e reuniões ao vivo, [consulte Teams Live Events](/microsoftteams/limits-specifications-teams#teams-live-events).

## <a name="yammer-community-limits"></a>Yammer da comunidade

| Recurso | Detalhes |
|---------|---------|
| Número de membros em uma comunidade | Varia com base em se a comunidade está [conectada a](/yammer/manage-yammer-groups/yammer-and-office-365-groups)um grupo Microsoft 365 , é uma comunidade dinâmica [ou](/yammer/manage-yammer-groups/create-a-dynamic-group)é a comunidade [All Company.](/yammer/manage-yammer-groups/yammer-all-company-yammer-community) <br/>Limite dinâmico de associação à comunidade: 500 mil |
| Número de comunidades que você pode ser membro | 7,000 |
| Número de atualizações por meio da importação de livro de endereços para adicionar vários usuários de uma só vez | 200 membros da comunidade por carregamento em lotes. |
| Limite de comunidades dinâmicas | Sem limite |
| Número de administradores por comunidade | No modo nativo, os administradores podem definir um mínimo. As redes de modo não nativo têm um limite de 100 administradores por comunidade. |
| Número de administradores de rede | Varia dependendo da configuração do modo nativo. Nenhum limite de administradores de rede. |
| Comunidades Conectadas e Azure AD Sync | A latência com a sincronização pode ocorrer com uma associação à comunidade com mais de 100 mil. |
| Membros em Todas as Empresas | Inclui todos os usuários no locatário. |
| Número de comunidades oficiais | Sem limite |
| Número de comunidades de favoritos | 10  |
| Community de caracteres de nome | Depende da convenção de nomenis da rede. <br/>Máximo de 255 caracteres, incluindo qualquer prefixo. |
| Community limite de caracteres de descrição | 150 caracteres |
| Community tamanho das informações | Nenhum limite de caracteres (até 1 GB) |
| Limite de recursos fixados | Sem limite |
| Limite de comunidades relacionadas | Nenhum limite para comunidades normais, mas as práticas recomendadas são 3 a 5 comunidades relacionadas. <br/>As comunidades relacionadas não estão disponíveis para Toda a Empresa. |
| Limitar membros pendentes para comunidades privadas | Sem limite. |
| Limites do gerenciamento da comunidade no modo Nativo | Os grupos conectados devem ser gerenciados usando ferramentas projetadas para atualizar grupos Microsoft 365, incluindo o portal de administração do Microsoft 365, o portal do Azure AD e o módulo do Azure AD PowerShell. |
| Postagem por email | Sem limite |

## <a name="yammer-messaging-limitations"></a>Yammer limitações de mensagens

| Recurso | Detalhes |
|---------|---------|
| Limite de caracteres por mensagem | Limite de caracteres de 10K |
| Excluir conversas | Excluir um thread inteiro exige que todas as mensagens sejam excluídas. Excluir o início da conversa promoverá a primeira resposta para se tornar o início do thread. <br/>Os administradores de rede podem excluir mensagens de qualquer thread de conversa se [o Modo de Conteúdo](/yammer/manage-security-and-compliance/monitor-private-content) Privado estiver habilitado. <br/>Community os administradores podem excluir mensagens na comunidade que administram. <br/>O autor original só pode excluir suas próprias postagens. |
| Limite de mensagens por thread de conversa | Uma conversa pode ter até 10.000 postagens. |
| Visualizações de link (abrir Graph metadados) |<ul><li>As visualizações do conteúdo do link só podem ser geradas para conteúdo público e alguns recursos Microsoft 365 suporte.</li><li>A geração de visualização depende da extração bem-sucedida de metadados no momento da postagem, que pode variar com base na disponibilidade do site que está sendo vinculado.</li><li>Links para sistemas dentro do firewall da organização ou que exigem autenticação não são suportados. </li><li>Os metadados de visualização de link podem não ser atualizados após o primeiro uso do link na rede.</li></ul> |
| Modo de conteúdo privado | Os administradores verificados não podem acessar o conteúdo privado por padrão. O modo de conteúdo privado deve estar habilitado para acessar mensagens privadas e comunidades privadas. |
| Respostas aninhadas e threads herdados | Threads herdados permitirão a criação de novas respostas aninhadas. As mensagens mais antigas "em resposta a" permaneceriam como comentários de nível superior, por enquanto. |

## <a name="external-network-limits"></a>Limites de rede externa

| Recurso | Detalhes |
|---------|---------|
| Redes Externas | Limitação de 5 redes externas que um administrador pode criar se essas cinco redes externas têm um único membro (geralmente, esse membro é o criador da rede). <br/> Se houver pelo menos um outro usuário em uma rede externa, ele não contará para esse limite. |
| Arquivos | Os arquivos são armazenados Yammer armazenamento e não são acessíveis por meio SharePoint. |
| Comunidades | As comunidades não estão conectadas a Microsoft 365 Grupos. |
| Modo Nativo | [Os recursos e restrições do modo](/yammer/configure-your-yammer-network/overview-native-mode) nativo não se aplicam a redes externas. |