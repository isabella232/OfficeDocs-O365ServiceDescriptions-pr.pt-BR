---
title: Gerenciamento de destinatário, domínio e empresa no Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: Leia este artigo para saber mais sobre o gerenciamento de destinatário, domínio e empresa no Microsoft Exchange Online Protection (EOP).
ms.openlocfilehash: a01d572ce239e7d1a6c0c57814fb7494a6670f84
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173716"
---
# <a name="recipient-domain-and-company-management-in-exchange-online-protection"></a>Gerenciamento de destinatário, domínio e empresa no Exchange Online Protection

Microsoft Exchange Online Protection (EOP) oferece vários meios de gerenciar suas informações de destinatário, domínio e empresa. Como administrador, você pode executar determinadas tarefas de gerenciamento no Centro de administração do Exchange (EAC) e verificar outras tarefas de gerenciamento executadas no centro de administração do Microsoft 365.
  
Você está procurando informações sobre todas as características EOP? Consulte a descrição [do serviço de Proteção do Exchange Online](exchange-online-protection-service-description.md).
  
## <a name="mail-recipients"></a>Mail recipients

Os destinatários de email são categorizados como grupos ou usuários de email e podem ser gerenciados por meio da sincronização do diretório, diretamente no EAC ou via Windows PowerShell remoto. Se estiver gerenciando destinatários locais, você deverá executar a sincronização de diretório para que seus destinatários de email sejam refletidos no EAC. Os usuários gerenciados exclusivamente no Centro de administração do Microsoft 365 não podem ser visualizados no EAC, mas podem ser adicionados ou removidos da associação em um grupo de função de administrador no EAC. Confira mais informações sobre destinatários no EOP em [Destinatários no EOP](/microsoft-365/security/office-365-security/manage-recipients-in-eop).
  
## <a name="admin-role-group-permissions"></a>Admin role group permissions

No EOP você pode configurar apenas funções de administrador. Os usuários podem ser adicionados e removidos dos grupos de função de administrador padrão diretamente no EAC. Não há personalização de RBAC disponível. Confira mais informações em [Gerenciar permissões do grupo de funções de administrador no EOP](/microsoft-365/security/office-365-security/manage-admin-role-group-permissions-in-eop).
  
## <a name="domain-management"></a>Gerenciamento de domínio

Domínios gerenciados são domínios protegidos pelo EOP. Os domínios gerenciados podem ser visualizados e os tipos de domínio podem ser editados no EAC. O provisionamento e o gerenciamento de domínios ocorrem no centro de administração do Microsoft 365 e as alterações são refletidas no EAC. Confira mais informações em [Exibir ou editar domínios gerenciados no EOP](/microsoft-365/security/office-365-security/exchange-online-protection-overview).
  
## <a name="match-subdomains"></a>Corresponder subdomínios

No EOP, você pode ativar o fluxo de mensagens para os subdomínios de um domínio gerenciado. Confira mais informações em [Ativar o fluxo de email para os subdomínios no EOP](/microsoft-365/security/office-365-security/mail-flow-in-eop). 
  
## <a name="directory-based-edge-blocking-dbeb"></a>Bloqueio de borda baseado em diretório (DBEB)

O recurso Bloqueio de borda baseado em diretório permite rejeitar mensagens para destinatários inválidos no perímetro da rede de serviços. O DBEB permite que os administradores adicionem destinatários habilitados para email à Microsoft e bloqueiem todas as mensagens enviadas para endereços de email que não estão presentes na Microsoft. Se uma mensagem for enviada para um endereço de email válido presente na Microsoft, a mensagem continuará pelo restante das camadas de filtragem de serviço (anti-malware, anti-spam, regras de transporte). Se o endereço não estiver presente, o serviço bloqueia a mensagem antes mesmo da filtragem ocorrer e uma notificação de falha na entrega (NDR) é enviada para o remetente informando que a mensagem não foi entregue. 
  
Para ativar o DBEB é preciso fazer algumas configurações de domínio e de usuário. Confira mais informações em [Usar Bloqueio de Borda Baseado em Diretório para Rejeitar Mensagens Enviadas a Destinatários Inválidos](/exchange/mail-flow-best-practices/use-directory-based-edge-blocking).
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos entre planos, opções autônomas e soluções locais, consulte Descrição do serviço [de Proteção do Exchange Online.](exchange-online-protection-service-description.md)