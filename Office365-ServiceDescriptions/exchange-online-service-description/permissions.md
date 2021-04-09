---
title: Permissões
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-permissions
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7803d7c0-93e6-43a2-b2a4-3a39abe25500
description: O Microsoft Exchange Online usa um modelo de Controle de Acesso Baseado em Função (RBAC) para permitir que os administradores da organização controlem detalhadamente o que usuários e funcionários de TI podem fazer no serviço. Por exemplo, se um responsável pela conformidade for responsável por solicitações de pesquisa de caixa de correio, o administrador poderá delegar esse recurso administrativo ao responsável por meio de RBAC. O Exchange Online usa a mesma estrutura de RBAC do Microsoft Exchange Server 2013.
ms.openlocfilehash: a9c326e647470e1941f448a9ae61598fd746709e
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653313"
---
# <a name="permissions"></a>Permissions

O Microsoft Exchange Online usa um modelo de Controle de Acesso Baseado em Função (RBAC) para permitir que os administradores da organização controlem detalhadamente o que usuários e funcionários de TI podem fazer no serviço. Por exemplo, se um responsável pela conformidade for responsável por solicitações de pesquisa de caixa de correio, o administrador poderá delegar esse recurso administrativo ao responsável por meio de RBAC. O Exchange Online usa a mesma estrutura de RBAC do Microsoft Exchange Server 2013. 
  
Em seu nível mais alto, o RBAC é composto por funções de gerenciamento, grupos de funções de gerenciamento e políticas de atribuição de função de gerenciamento. As seções a seguir fornecem mais informações sobre cada componente do RBAC.
  
Confira mais informações sobre o modelo de permissões do RBAC usado no Exchange Online em [Permissões](/exchange/permissions-exchange-2013-help).
  
## <a name="role-based-permissions"></a>Permissões baseadas em função

No Exchange Online, as permissões concedidas a administradores e usuários são baseadas em funções de gerenciamento. Uma função define o conjunto de tarefas que um administrador ou usuário pode realizar. Por exemplo, uma função de gerenciamento chamada  `Mail Recipients` define as tarefas que alguém pode realizar em um conjunto de caixas de correio, contatos e grupos de distribuição. Quando uma função é atribuída a um administrador ou usuário, essa pessoa recebe as permissões fornecidas pela função. 
  
Existem dois tipos de funções, funções administrativas e de usuário final:
  
- **Funções administrativas** Essas funções contêm permissões que podem ser atribuídas a administradores ou usuários especialistas que utilizam grupos de funções que gerenciam uma parte da organização do Exchange Online, como destinatários, servidores ou bancos de dados. 
    
- **Funções de usuário final** Essas funções, atribuídas usando políticas de atribuição de função, permitem que os usuários gerenciem aspectos de suas próprias caixas de correio e grupos de distribuição que eles têm. As funções de usuário final começam com o prefixo  `My`.
    
As funções atribuem permissões aos administradores e usuários para executar tarefas por meio da disponibilização de cmdlets. Como o EAC (centro de administração do Exchange) e o Shell de Gerenciamento do Exchange usam cmdlets para gerenciar o Exchange Online, conceder acesso a um cmdlet fornece ao administrador ou usuário a permissão para executar a tarefa em cada uma das interfaces de gerenciamento do Exchange Online.
  
As permissões baseadas em função do Microsoft Online Services sobrepõem as do RBAC do Exchange Online de duas formas. Primeiro, os usuários que são Administradores Globais ou Administradores de Serviço no Microsoft Online são automaticamente atribuídos ao grupo de função de Gerenciamento da Organização no Exchange Online. Segundo, os usuários que são Administradores do Suporte Técnico no Microsoft Online são automaticamente atribuídos ao grupo de função de Suporte Técnico no Exchange Online. Caso contrário, os dois modelos de segurança são gerenciados separadamente.
  
> [!IMPORTANT]
> Algumas funções disponíveis na versão local do Microsoft Exchange Server 2013 podem não estar disponíveis no Exchange Online. 
  
Confira mais informações sobre permissões no Exchange Online em [Permissões Baseadas em Função](/exchange/permissions-exchange-2013-help).
  
## <a name="role-groups"></a>Grupos de função

Grupos de funções de Gerenciamento associam papéis de gerenciamento a um grupo de administradores ou usuários especialistas. Os administradores gerenciam uma ampla configuração de organização ou destinatário do Exchange Online. Usuários especialistas gerenciam os recursos específicos do Exchange Online, como conformidade, ou podem ter recursos de gerenciamento limitados, como membros de Suporte Técnico, mas não recebem amplos direitos administrativos. Os grupos de funções geralmente associam funções de gerenciamento administrativas que permitem que administradores e usuários especialistas gerenciem a configuração de sua organização e destinatários. Por exemplo, grupos de função controlam se administradores podem gerenciar destinatários ou usar recursos de descoberta da caixa de correio. 
  
> [!IMPORTANT]
> Alguns grupos de funções disponíveis na versão local do Microsoft Exchange Server 2013 podem não estar disponíveis no Exchange Online. 
  
Confira mais informações sobre grupos de funções em [Grupos de funções e políticas de atribuição de funções](/exchange/permissions-exchange-2013-help).
  
## <a name="role-assignment-policies"></a>Diretivas de atribuição de função

Diretivas de atribuição de função de gerenciamento associam funções de gerenciamento de usuários finais a usuários. As políticas de atribuição de função consistem de funções que controlam o que os usuários podem fazer com suas caixas de correio ou grupos de distribuição. Estas funções não permitem o gerenciamento de recursos que não estejam associados diretamente ao usuário. Quando uma diretiva de atribuição de função é criada, tudo que o usuário pode fazer com sua caixa de correio é definido. Por exemplo, uma política de atribuição de função pode permitir que um usuário estabeleça o nome de exibição, defina a caixa postal e configure regras da Caixa de Entrada. Outra diretiva de atribuição de função poderia permitir que um usuário modificasse o endereço, usasse a transmissão de mensagens de texto e definisse grupos de distribuição. A cada usuário com uma caixa de correio do Exchange Online, incluindo administradores, é dada uma política de atribuição de função por padrão. É possível decidir qual política de atribuição de função deve ser atribuída por padrão, escolher o que a política de atribuição de função padrão deve incluir, substituir o padrão por certas caixas de correio ou não atribuir políticas de atribuição de função por padrão.
  
> [!IMPORTANT]
> Algumas atribuições de funções disponíveis na versão local do Microsoft Exchange Server 2013 podem não estar disponíveis no Exchange Online. 
  
Confira mais informações sobre políticas de atribuição de funções em [Grupos de funções e políticas de atribuição de funções](/exchange/permissions-exchange-2013-help).
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos entre planos, opções autônomas e soluções locais, consulte a descrição [do serviço do Exchange Online.](exchange-online-service-description.md)
