---
title: Gerenciamento de destinatário, domínios e de empresa
ms.author: sharik
author: skjerland
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
ms.openlocfilehash: ff773ca3e19c9f9419ad907ed102f6af8a3567c2
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/25/2019
ms.locfileid: "33246267"
---
# <a name="recipient-domain-and-company-management"></a><span data-ttu-id="8cef6-104">Gerenciamento de destinatário, domínios e de empresa</span><span class="sxs-lookup"><span data-stu-id="8cef6-104">Recipient, Domain, and Company Management</span></span>

<span data-ttu-id="8cef6-105">O Microsoft proteção do Exchange Online (EOP) oferece vários meios de gerenciamento das informações de destinatário, domínio e da empresa.</span><span class="sxs-lookup"><span data-stu-id="8cef6-105">Microsoft Exchange Online Protection (EOP) offers several means of managing your recipient, domain, and company information.</span></span> <span data-ttu-id="8cef6-106">Como administrador, você pode executar determinadas tarefas de gerenciamento no centro de administração do Exchange (Eat) e verificar outras tarefas de gerenciamento executadas no centro de administração do Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="8cef6-106">As an administrator, you can perform certain management tasks within the Exchange admin center (EAC), and verify other management tasks performed in the Microsoft 365 admin center.</span></span>
  
<span data-ttu-id="8cef6-107">Você está procurando informações sobre todas as características EOP?</span><span class="sxs-lookup"><span data-stu-id="8cef6-107">Looking for information about all EOP features?</span></span> <span data-ttu-id="8cef6-108">Confira o [Descrição do serviço de proteção do Exchange Online](exchange-online-protection-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="8cef6-108">See the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="mail-recipients"></a><span data-ttu-id="8cef6-109">Mail recipients</span><span class="sxs-lookup"><span data-stu-id="8cef6-109">Mail recipients</span></span>
<span data-ttu-id="8cef6-110"><a name="BKMK_mailrecipients"> </a></span><span class="sxs-lookup"><span data-stu-id="8cef6-110"></span></span>

<span data-ttu-id="8cef6-111">Os destinatários de email são categorizados como grupos ou usuários de email e podem ser gerenciados por meio da sincronização do diretório, diretamente no EAC ou via Windows PowerShell remoto.</span><span class="sxs-lookup"><span data-stu-id="8cef6-111">Mail recipients are categorized as mail users or groups and can be managed through directory synchronization, directly in the EAC, or via remote Windows PowerShell.</span></span> <span data-ttu-id="8cef6-112">Se estiver gerenciando destinatários locais, você deverá executar a sincronização de diretório para que seus destinatários de email sejam refletidos no EAC.</span><span class="sxs-lookup"><span data-stu-id="8cef6-112">If you're managing your recipients on-premises, you must run directory synchronization in order for your mail recipients to be reflected in the EAC.</span></span> <span data-ttu-id="8cef6-113">Os usuários gerenciados exclusivamente no centro de administração do Microsoft 365 não são visíveis no Eat, mas podem ser adicionados ou removidos da associação em um grupo de funções de administrador no Eat.</span><span class="sxs-lookup"><span data-stu-id="8cef6-113">Users managed solely in the Microsoft 365 admin center aren't viewable in the EAC, but they can be added to or removed from membership in an administrator role group in the EAC.</span></span> <span data-ttu-id="8cef6-114">Confira mais informações sobre destinatários no EOP em [Destinatários no EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).</span><span class="sxs-lookup"><span data-stu-id="8cef6-114">For more information about recipients in EOP, see [Recipients in EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).</span></span>
  
## <a name="admin-role-group-permissions"></a><span data-ttu-id="8cef6-115">Admin role group permissions</span><span class="sxs-lookup"><span data-stu-id="8cef6-115">Admin role group permissions</span></span>
<span data-ttu-id="8cef6-116"><a name="BKMK_adminrolegrouppermissions"> </a></span><span class="sxs-lookup"><span data-stu-id="8cef6-116"></span></span>

<span data-ttu-id="8cef6-p105">No EOP você pode configurar apenas funções de administrador. Os usuários podem ser adicionados e removidos dos grupos de função de administrador padrão diretamente no EAC. Não há personalização de RBAC disponível. Confira mais informações em [Gerenciar permissões do grupo de funções de administrador no EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).</span><span class="sxs-lookup"><span data-stu-id="8cef6-p105">In EOP, you can configure administrative roles only. Users can be added and removed from default admin role groups directly in the EAC. No RBAC customization is available. For more information, see [Manage Admin Role Group Permissions in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).</span></span>
  
## <a name="domain-management"></a><span data-ttu-id="8cef6-121">Domain management</span><span class="sxs-lookup"><span data-stu-id="8cef6-121">Domain management</span></span>
<span data-ttu-id="8cef6-122"><a name="BKMK_domainmanagement"> </a></span><span class="sxs-lookup"><span data-stu-id="8cef6-122"></span></span>

<span data-ttu-id="8cef6-123">Domínios gerenciados são domínios protegidos pelo EOP.</span><span class="sxs-lookup"><span data-stu-id="8cef6-123">Managed domains are domains that are protected by EOP.</span></span> <span data-ttu-id="8cef6-124">Os domínios gerenciados podem ser visualizados e os tipos de domínio podem ser editados no EAC.</span><span class="sxs-lookup"><span data-stu-id="8cef6-124">Managed domains can be viewed and domain types can be edited in the EAC.</span></span> <span data-ttu-id="8cef6-125">O provisionamento e o gerenciamento de domínios ocorrem no centro de administração do Microsoft 365 e as alterações são refletidas no Eat.</span><span class="sxs-lookup"><span data-stu-id="8cef6-125">Domain provisioning and management occurs in the Microsoft 365 admin center and changes are reflected in the EAC.</span></span> <span data-ttu-id="8cef6-126">Confira mais informações em [Exibir ou editar domínios gerenciados no EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).</span><span class="sxs-lookup"><span data-stu-id="8cef6-126">For more information, see [View or Edit Managed Domains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).</span></span>
  
## <a name="match-subdomains"></a><span data-ttu-id="8cef6-127">Corresponder subdomínios</span><span class="sxs-lookup"><span data-stu-id="8cef6-127">Match subdomains</span></span>
<span data-ttu-id="8cef6-128"><a name="BKMK_EOP_Match_Subdomains"> </a></span><span class="sxs-lookup"><span data-stu-id="8cef6-128"></span></span>

<span data-ttu-id="8cef6-p107">No EOP, você pode ativar o fluxo de mensagens para os subdomínios de um domínio gerenciado. Confira mais informações em [Ativar o fluxo de email para os subdomínios no EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213).</span><span class="sxs-lookup"><span data-stu-id="8cef6-p107">In EOP, you can enable mail flow to subdomains of a managed domain. For more information, see [Enable Email Flow for Subdomains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213).</span></span> 
  
## <a name="directory-based-edge-blocking-dbeb"></a><span data-ttu-id="8cef6-131">Directory Based Edge Blocking (DBEB)</span><span class="sxs-lookup"><span data-stu-id="8cef6-131">Directory Based Edge Blocking (DBEB)</span></span>
<span data-ttu-id="8cef6-132"><a name="BKMK_DBEB"> </a></span><span class="sxs-lookup"><span data-stu-id="8cef6-132"></span></span>

<span data-ttu-id="8cef6-p108">O recurso Bloqueio de borda baseado em diretório permite rejeitar mensagens para destinatários inválidos no perímetro da rede de serviços. O DBEB permite que os administradores adicionem destinatários habilitados para email ao Office 365 e bloqueie todas as mensagens enviadas para os endereços de email que não estão presentes no Office 365. Se uma mensagem for enviada para um endereço de email válido presente no Office 365, ela continuará pelo restante das camadas de filtragem de serviços (antimalware, antispam, regras de transporte). Se o endereço não estiver presente, o serviço bloqueia a mensagem antes mesmo da filtragem ocorrer e uma notificação de falha na entrega (NDR) é enviada para o remetente informando que a mensagem não foi entregue.</span><span class="sxs-lookup"><span data-stu-id="8cef6-p108">The Directory Based Edge Blocking feature lets you reject messages for invalid recipients at the service network perimeter. DBEB lets admins add mail-enabled recipients to Office 365 and block all messages sent to email addresses that aren't present in Office 365. If a message is sent to a valid email address present in Office 365, the message continues through the rest of the service filtering layers (anti-malware, anti-spam, transport rules). If the address is not present, the service blocks the message before filtering even occurs, and a non-delivery report (NDR) is sent to the sender informing them that their message was not delivered.</span></span> 
  
<span data-ttu-id="8cef6-p109">Para ativar o DBEB é preciso fazer algumas configurações de domínio e de usuário. Confira mais informações em [Usar Bloqueio de Borda Baseado em Diretório para Rejeitar Mensagens Enviadas a Destinatários Inválidos](https://go.microsoft.com/fwlink/p/?LinkId=390676).</span><span class="sxs-lookup"><span data-stu-id="8cef6-p109">Enabling DBEB requires some user and domain configuration. For more information, see [Use Directory Based Edge Blocking to Reject Messages Sent to Invalid Recipients](https://go.microsoft.com/fwlink/p/?LinkId=390676).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="8cef6-139">Disponibilidade do recurso</span><span class="sxs-lookup"><span data-stu-id="8cef6-139">Feature Availability</span></span>
<span data-ttu-id="8cef6-140"><a name="BKMK_DBEB"> </a></span><span class="sxs-lookup"><span data-stu-id="8cef6-140"></span></span>

<span data-ttu-id="8cef6-141">Para exibir a disponibilidade de recursos nos planos do Office 365 nas opções autônomas e nas soluções locais, consulte [Descrição do serviço de proteção do Exchange Online](exchange-online-protection-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="8cef6-141">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  

