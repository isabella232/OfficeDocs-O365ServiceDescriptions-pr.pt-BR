---
title: Gerenciamento de destinatário, domínios e de empresa
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: O Microsoft proteção do Exchange Online (EOP) oferece vários meios de gerenciamento das informações de destinatário, domínio e da empresa. Como administrador, você pode executar determinadas tarefas de gerenciamento no centro de administração do Exchange (Eat) e verificar outras tarefas de gerenciamento executadas no centro de administração do Microsoft 365.
ms.openlocfilehash: fcae2c3ad93b977fb197089e2c8809b74ada7bd7
ms.sourcegitcommit: 4abe1be8a63406e8a8c1a4a69f95386906ea1499
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 02/22/2019
ms.locfileid: "30210324"
---
# <a name="recipient-domain-and-company-management"></a>Gerenciamento de destinatário, domínios e de empresa

O Microsoft proteção do Exchange Online (EOP) oferece vários meios de gerenciamento das informações de destinatário, domínio e da empresa. Como administrador, você pode executar determinadas tarefas de gerenciamento no centro de administração do Exchange (Eat) e verificar outras tarefas de gerenciamento executadas no centro de administração do Microsoft 365.
  
Está procurando informações sobre todos os recursos do EOP? Consulte a [Descrição do serviço de proteção do Exchange Online](exchange-online-protection-service-description.md).
  
## <a name="mail-recipients"></a>Destinatários de email
<a name="BKMK_mailrecipients"> </a>

Os destinatários de email são categorizados como usuários ou grupos de emails e podem ser gerenciados por meio da sincronização de diretório, diretamente no Eat ou pelo Windows PowerShell remoto. Se você estiver gerenciando seus destinatários no local, você deve executar a sincronização de diretório para que seus destinatários de email sejam refletidos no Eat. Os usuários gerenciados exclusivamente no centro de administração do Microsoft 365 não são visíveis no Eat, mas podem ser adicionados ou removidos da associação em um grupo de funções de administrador no Eat. Para obter mais informações sobre os destinatários no EOP, consulte [Recipients in EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).
  
## <a name="admin-role-group-permissions"></a>Permissões do grupo de funções de administrador
<a name="BKMK_adminrolegrouppermissions"> </a>

No EOP você pode configurar apenas funções de administrador. Os usuários podem ser adicionados e removidos dos grupos de função de administrador padrão diretamente no EAC. Não há personalização de RBAC disponível. Confira mais informações em [Gerenciar permissões do grupo de funções de administrador no EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).
  
## <a name="domain-management"></a>Gerenciamento de domínio
<a name="BKMK_domainmanagement"> </a>

Os domínios gerenciados são domínios protegidos pelo EOP. Os domínios gerenciados podem ser exibidos e os tipos de domínio podem ser editados no Eat. O provisionamento e o gerenciamento de domínios ocorrem no centro de administração do Microsoft 365 e as alterações são refletidas no Eat. Para obter mais informações, consulte [Exibir ou editar domínios gerenciados no EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).
  
## <a name="match-subdomains"></a>Corresponder subdomínios
<a name="BKMK_EOP_Match_Subdomains"> </a>

No EOP, você pode ativar o fluxo de mensagens para os subdomínios de um domínio gerenciado. Confira mais informações em [Ativar o fluxo de email para os subdomínios no EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213). 
  
## <a name="directory-based-edge-blocking-dbeb"></a>Bloqueio de borda baseado em diretório (DBEB)
<a name="BKMK_DBEB"> </a>

O recurso Bloqueio de borda baseado em diretório permite rejeitar mensagens para destinatários inválidos no perímetro da rede de serviços. O DBEB permite que os administradores adicionem destinatários habilitados para email ao Office 365 e bloqueie todas as mensagens enviadas para os endereços de email que não estão presentes no Office 365. Se uma mensagem for enviada para um endereço de email válido presente no Office 365, ela continuará pelo restante das camadas de filtragem de serviços (antimalware, antispam, regras de transporte). Se o endereço não estiver presente, o serviço bloqueia a mensagem antes mesmo da filtragem ocorrer e uma notificação de falha na entrega (NDR) é enviada para o remetente informando que a mensagem não foi entregue. 
  
Para ativar o DBEB é preciso fazer algumas configurações de domínio e de usuário. Confira mais informações em [Usar Bloqueio de Borda Baseado em Diretório para Rejeitar Mensagens Enviadas a Destinatários Inválidos](https://go.microsoft.com/fwlink/p/?LinkId=390676).
  
## <a name="feature-availability"></a>Disponibilidade do recurso
<a name="BKMK_DBEB"> </a>

Para exibir a disponibilidade de recursos nos planos do Office 365 nas opções autônomas e nas soluções locais, consulte [Descrição do serviço de proteção do Exchange Online](exchange-online-protection-service-description.md).
  

