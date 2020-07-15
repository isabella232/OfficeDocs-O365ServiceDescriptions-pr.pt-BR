---
title: Permissões
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-permissions
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7803d7c0-93e6-43a2-b2a4-3a39abe25500
description: Microsoft Exchange Online uses a Role Based Access Control (RBAC) model to allow organization administrators to finely control what users and IT employees can do in the service. For example, if a compliance officer is responsible for mailbox search requests, the administrator can delegate this administrative feature to the officer through RBAC. Exchange Online uses the same RBAC framework as Microsoft Exchange Server 2013.
ms.openlocfilehash: 0593c98857a7ce0c487c628018097395d7a5fe50
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132685"
---
# <a name="permissions"></a>Permissões

Microsoft Exchange Online uses a Role Based Access Control (RBAC) model to allow organization administrators to finely control what users and IT employees can do in the service. For example, if a compliance officer is responsible for mailbox search requests, the administrator can delegate this administrative feature to the officer through RBAC. Exchange Online uses the same RBAC framework as Microsoft Exchange Server 2013. 
  
At its highest level, RBAC is made up of management roles, management role groups, and management role assignment policies. The following sections provide more information about each RBAC component.
  
Confira mais informações sobre o modelo de permissões do RBAC usado no Exchange Online em [Permissões](https://go.microsoft.com/fwlink/p/?LinkId=271935).
  
## <a name="role-based-permissions"></a>Permissões baseadas em função

In Exchange Online, the permissions that you grant to administrators and users are based on management roles. A role defines the set of tasks that an administrator or user can perform. For example, a management role called  `Mail Recipients` defines the tasks that someone can perform on a set of mailboxes, contacts, and distribution groups. When a role is assigned to an administrator or user, that person is granted the permissions provided by the role. 
  
Existem dois tipos de funções, funções administrativas e de usuário final:
  
- **Funções administrativas** Essas funções contêm permissões que podem ser atribuídas a administradores ou usuários especialistas que utilizam grupos de funções que gerenciam uma parte da organização do Exchange Online, como destinatários, servidores ou bancos de dados. 
    
- **Funções de usuário final** Essas funções, atribuídas por meio de diretivas de atribuição de função, permitem que os usuários gerenciem aspectos de suas próprias caixas de correio e grupos de distribuição de sua propriedade. As funções de usuário final começam com o prefixo  `My`.
    
Roles give administrators and users permissions to perform tasks by making cmdlets available to those who are assigned the roles. Because the Exchange admin center (EAC) and Exchange Management Shell use cmdlets to manage Exchange Online, granting access to a cmdlet gives the administrator or user permission to perform the task in each of the Exchange Online management interfaces.
  
The role-based permissions for Microsoft Online Services overlap with those of Exchange Online RBAC in two ways. First, users who are Global Administrators or Service Administrators in Microsoft Online are automatically assigned to the Organization Management role group in Exchange Online. Second, users who are Help Desk Administrators in Microsoft Online are automatically assigned to the Help Desk role group in Exchange Online. Otherwise, the two security models are managed separately.
  
> [!IMPORTANT]
> Algumas funções disponíveis na versão local do Microsoft Exchange Server 2013 podem não estar disponíveis no Exchange Online. 
  
Confira mais informações sobre permissões no Exchange Online em [Permissões Baseadas em Função](https://go.microsoft.com/fwlink/p/?LinkId=271936).
  
## <a name="role-groups"></a>Grupos de função

Grupos de funções de Gerenciamento associam papéis de gerenciamento a um grupo de administradores ou usuários especialistas. Os administradores gerenciam uma ampla configuração de organização ou destinatário do Exchange Online. Usuários especialistas gerenciam os recursos específicos do Exchange Online, como conformidade, ou podem ter recursos de gerenciamento limitados, como membros de Suporte Técnico, mas não recebem amplos direitos administrativos. Grupos de função geralmente associam funções de gerenciamento administrativo que permitem que administradores e usuários especialistas gerenciem a configuração de sua organização e seus destinatários. Por exemplo, grupos de função controlam se administradores podem gerenciar destinatários ou usar recursos de descoberta da caixa de correio. 
  
> [!IMPORTANT]
> Alguns grupos de funções disponíveis na versão local do Microsoft Exchange Server 2013 podem não estar disponíveis no Exchange Online. 
  
Confira mais informações sobre grupos de funções em [Grupos de funções e políticas de atribuição de funções](https://go.microsoft.com/fwlink/p/?LinkId=271937).
  
## <a name="role-assignment-policies"></a>Diretivas de atribuição de função

Management role assignment policies associate end-user management roles to users. Role assignment policies consist of roles that control what users can do with their mailboxes or distribution groups. These roles don't allow management of features that aren't directly associated with the user. When you create a role assignment policy, you define everything a user can do with his or her mailbox. For example, a role assignment policy might allow a user to set the display name, set up voice mail, and configure Inbox rules. Another role assignment policy might allow a user to change the address, use text messaging, and set up distribution groups. Every user with an Exchange Online mailbox, including administrators, is given a role assignment policy by default. You can decide which role assignment policy should be assigned by default, choose what the default role assignment policy should include, override the default for certain mailboxes, or not assign any role assignment policies by default.
  
> [!IMPORTANT]
> Algumas atribuições de funções disponíveis na versão local do Microsoft Exchange Server 2013 podem não estar disponíveis no Exchange Online. 
  
Confira mais informações sobre políticas de atribuição de funções em [Grupos de funções e políticas de atribuição de funções](https://go.microsoft.com/fwlink/p/?LinkId=271937).
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos nos planos, nas opções autônomas e nas soluções locais, consulte [Descrição do serviço do Exchange Online](exchange-online-service-description.md).
  

