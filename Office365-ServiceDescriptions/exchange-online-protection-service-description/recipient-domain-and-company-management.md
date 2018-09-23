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
description: Microsoft Exchange Online Protection (EOP) oferece vários meios de gerenciar destinatário, domínio e informações da empresa. Como administrador, você pode realizar certas tarefas de gerenciamento no Centro de administração do Exchange (EAC) e verifique se a outras tarefas de gerenciamento realizadas no Centro de administração do Microsoft Office 365.
ms.openlocfilehash: 17a87a85611dc286e3d19eaeefe04466a1ac62d0
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24034916"
---
# <a name="recipient-domain-and-company-management"></a><span data-ttu-id="07080-104">Gerenciamento de destinatário, domínios e de empresa</span><span class="sxs-lookup"><span data-stu-id="07080-104">Recipient, Domain, and Company Management</span></span>

<span data-ttu-id="07080-p102">Microsoft Exchange Online Protection (EOP) oferece vários meios de gerenciar destinatário, domínio e informações da empresa. Como administrador, você pode realizar certas tarefas de gerenciamento no Centro de administração do Exchange (EAC) e verifique se a outras tarefas de gerenciamento realizadas no Centro de administração do Microsoft Office 365.</span><span class="sxs-lookup"><span data-stu-id="07080-p102">Microsoft Exchange Online Protection (EOP) offers several means of managing your recipient, domain, and company information. As an administrator, you can perform certain management tasks within the Exchange admin center (EAC), and verify other management tasks performed in the Microsoft Office 365 admin center.</span></span>
  
<span data-ttu-id="07080-p103">Está procurando informações sobre todos os recursos do EOP? Consulte a [Descrição do serviço de proteção do Exchange Online](exchange-online-protection-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="07080-p103">Looking for information about all EOP features? See the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="mail-recipients"></a><span data-ttu-id="07080-109">Destinatários de email</span><span class="sxs-lookup"><span data-stu-id="07080-109">Mail recipients</span></span>
<span data-ttu-id="07080-110"><a name="BKMK_mailrecipients"> </a></span><span class="sxs-lookup"><span data-stu-id="07080-110"></span></span>

<span data-ttu-id="07080-p104">Os destinatários de email são categorizados como grupos ou usuários de email e podem ser gerenciados por meio da sincronização do diretório, diretamente no EAC ou via Windows PowerShell remoto. Se estiver gerenciando destinatários locais, você deverá executar a sincronização de diretório para que seus destinatários de email sejam refletidos no EAC. Os usuários gerenciados unicamente no Centro de administração do Office 365 não estão disponíveis para visualização no EAC, mas podem ser adicionados ou removidos da associação de grupo de funções de administrador no EAC. Confira mais informações sobre destinatários no EOP em [Destinatários no EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).</span><span class="sxs-lookup"><span data-stu-id="07080-p104">Mail recipients are categorized as mail users or groups and can be managed through directory synchronization, directly in the EAC, or via remote Windows PowerShell. If you're managing your recipients on-premises, you must run directory synchronization in order for your mail recipients to be reflected in the EAC. Users managed solely in the Office 365 admin center aren't viewable in the EAC, but they can be added to or removed from membership in an administrator role group in the EAC. For more information about recipients in EOP, see [Recipients in EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).</span></span>
  
## <a name="admin-role-group-permissions"></a><span data-ttu-id="07080-115">Permissões do grupo de funções de administrador</span><span class="sxs-lookup"><span data-stu-id="07080-115">Admin role group permissions</span></span>
<span data-ttu-id="07080-116"><a name="BKMK_adminrolegrouppermissions"> </a></span><span class="sxs-lookup"><span data-stu-id="07080-116"></span></span>

<span data-ttu-id="07080-p105">No EOP você pode configurar apenas funções de administrador. Os usuários podem ser adicionados e removidos dos grupos de função de administrador padrão diretamente no EAC. Não há personalização de RBAC disponível. Confira mais informações em [Gerenciar permissões do grupo de funções de administrador no EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).</span><span class="sxs-lookup"><span data-stu-id="07080-p105">In EOP, you can configure administrative roles only. Users can be added and removed from default admin role groups directly in the EAC. No RBAC customization is available. For more information, see [Manage Admin Role Group Permissions in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).</span></span>
  
## <a name="domain-management"></a><span data-ttu-id="07080-121">Gerenciamento de domínio</span><span class="sxs-lookup"><span data-stu-id="07080-121">Domain management</span></span>
<span data-ttu-id="07080-122"><a name="BKMK_domainmanagement"> </a></span><span class="sxs-lookup"><span data-stu-id="07080-122"></span></span>

<span data-ttu-id="07080-p106">Domínios gerenciados são domínios protegidos pelo EOP. Os domínios gerenciados podem ser visualizados e os tipos de domínio podem ser editados no EAC. O fornecimento e o gerenciamento de domínios ocorrem no centro de administração do Office 365 e as mudanças são refletidas no EAC. Confira mais informações em [Exibir ou editar domínios gerenciados no EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).</span><span class="sxs-lookup"><span data-stu-id="07080-p106">Managed domains are domains that are protected by EOP. Managed domains can be viewed and domain types can be edited in the EAC. Domain provisioning and management occurs in the Office 365 admin center and changes are reflected in the EAC. For more information, see [View or Edit Managed Domains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).</span></span>
  
## <a name="match-subdomains"></a><span data-ttu-id="07080-127">Corresponder subdomínios</span><span class="sxs-lookup"><span data-stu-id="07080-127">Match subdomains</span></span>
<span data-ttu-id="07080-128"><a name="BKMK_EOP_Match_Subdomains"> </a></span><span class="sxs-lookup"><span data-stu-id="07080-128"></span></span>

<span data-ttu-id="07080-p107">No EOP, você pode ativar o fluxo de mensagens para os subdomínios de um domínio gerenciado. Confira mais informações em [Ativar o fluxo de email para os subdomínios no EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213).</span><span class="sxs-lookup"><span data-stu-id="07080-p107">In EOP, you can enable mail flow to subdomains of a managed domain. For more information, see [Enable Email Flow for Subdomains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213).</span></span> 
  
## <a name="directory-based-edge-blocking-dbeb"></a><span data-ttu-id="07080-131">Bloqueio de borda baseado em diretório (DBEB)</span><span class="sxs-lookup"><span data-stu-id="07080-131">Directory Based Edge Blocking (DBEB)</span></span>
<span data-ttu-id="07080-132"><a name="BKMK_DBEB"> </a></span><span class="sxs-lookup"><span data-stu-id="07080-132"></span></span>

<span data-ttu-id="07080-p108">O recurso Bloqueio de borda baseado em diretório permite rejeitar mensagens para destinatários inválidos no perímetro da rede de serviços. O DBEB permite que os administradores adicionem destinatários habilitados para email ao Office 365 e bloqueie todas as mensagens enviadas para os endereços de email que não estão presentes no Office 365. Se uma mensagem for enviada para um endereço de email válido presente no Office 365, ela continuará pelo restante das camadas de filtragem de serviços (antimalware, antispam, regras de transporte). Se o endereço não estiver presente, o serviço bloqueia a mensagem antes mesmo da filtragem ocorrer e uma notificação de falha na entrega (NDR) é enviada para o remetente informando que a mensagem não foi entregue.</span><span class="sxs-lookup"><span data-stu-id="07080-p108">The Directory Based Edge Blocking feature lets you reject messages for invalid recipients at the service network perimeter. DBEB lets admins add mail-enabled recipients to Office 365 and block all messages sent to email addresses that aren't present in Office 365. If a message is sent to a valid email address present in Office 365, the message continues through the rest of the service filtering layers (anti-malware, anti-spam, transport rules). If the address is not present, the service blocks the message before filtering even occurs, and a non-delivery report (NDR) is sent to the sender informing them that their message was not delivered.</span></span> 
  
<span data-ttu-id="07080-p109">Para ativar o DBEB é preciso fazer algumas configurações de domínio e de usuário. Confira mais informações em [Usar Bloqueio de Borda Baseado em Diretório para Rejeitar Mensagens Enviadas a Destinatários Inválidos](https://go.microsoft.com/fwlink/p/?LinkId=390676).</span><span class="sxs-lookup"><span data-stu-id="07080-p109">Enabling DBEB requires some user and domain configuration. For more information, see [Use Directory Based Edge Blocking to Reject Messages Sent to Invalid Recipients](https://go.microsoft.com/fwlink/p/?LinkId=390676).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="07080-139">Disponibilidade do recurso</span><span class="sxs-lookup"><span data-stu-id="07080-139">Feature Availability</span></span>
<span data-ttu-id="07080-140"><a name="BKMK_DBEB"> </a></span><span class="sxs-lookup"><span data-stu-id="07080-140"></span></span>

<span data-ttu-id="07080-141">Para exibir a disponibilidade de recursos nos planos do Office 365 nas opções autônomas e nas soluções locais, consulte [Descrição do serviço de proteção do Exchange Online](exchange-online-protection-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="07080-141">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  

