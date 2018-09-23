---
title: Fluxo de mensagens [EOP]
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: Para a maioria das organizações que usam o Office 365, podemos hospedar suas caixas de correio e cuida de fluxo de emails. É a configuração mais simples e significa que o Office 365 gerencia todas as caixas de correio e filtragem. No entanto, algumas organizações têm uma empresa precisa manter todas as suas caixas de correio no local. Exchange Online Protection (EOP) permite que você fizer isso e fornece o email de antivírus e antispam processamento na nuvem. Para obter mais informações e adquirir EOP, vá para o Exchange Online Protection.
ms.openlocfilehash: 6c43d308db3c4f62e4c6891cb87263560d9478a7
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24034783"
---
# <a name="mail-floweop"></a><span data-ttu-id="066b7-107">Fluxo de mensagens [EOP]</span><span class="sxs-lookup"><span data-stu-id="066b7-107">Mail Flow[EOP]</span></span>

<span data-ttu-id="066b7-p102">Para a maioria das organizações que usam o Office 365, podemos hospedar suas caixas de correio e cuida de fluxo de emails. É a configuração mais simples e significa que o Office 365 gerencia todas as caixas de correio e filtragem. No entanto, algumas organizações têm uma empresa precisa manter todas as suas caixas de correio no local. Exchange Online Protection (EOP) permite que você fizer isso e fornece o email de antivírus e antispam processamento na nuvem. Para obter mais informações e adquirir EOP, vá para o [Exchange Online Protection](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection).</span><span class="sxs-lookup"><span data-stu-id="066b7-p102">For most organizations that use Office 365, we host your mailboxes and take care of mail flow. It's the simplest configuration and means that Office 365 manages all mailboxes and filtering. However, some organizations have a business need to keep all their mailboxes on premises. Exchange Online Protection (EOP) enables you to do that and provides antivirus and anti-spam mail processing in the cloud. For more information and to purchase EOP, go to [Exchange Online Protection](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection).</span></span>
  
<span data-ttu-id="066b7-p103">Procurando informações sobre o gerenciamento de domínio ou o Bloqueio de Borda Baseado em Diretório (DBEB)? Consulte [Gerenciamento de destinatário, domínios e de empresa](recipient-domain-and-company-management.md). Para saber mais sobre todos os recursos do EOP, consulte [Descrição do serviço de proteção do Exchange Online](exchange-online-protection-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="066b7-p103">Looking for information about domain management or Directory Based Edge Blocking (DBEB)? See [Recipient, Domain, and Company Management](recipient-domain-and-company-management.md). To learn more about all EOP features, see the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="routing-email-between-office-365-and-your-own-email-servers"></a><span data-ttu-id="066b7-116">Direcionar os emails entre seus próprios servidores de email e o Office 365</span><span class="sxs-lookup"><span data-stu-id="066b7-116">Routing email between Office 365 and your own email servers</span></span>
<span data-ttu-id="066b7-117"><a name="BKMK_outboundmailrouting"> </a></span><span class="sxs-lookup"><span data-stu-id="066b7-117"><a name="BKMK_outboundmailrouting"> </a></span></span>

<span data-ttu-id="066b7-p104">Você pode configurar um conector para permitir o fluxo de emails entre o Office 365 (incluindo o Exchange Online ou a EOP) e um servidor de emails baseado em SMTP, como o Exchange. Confira mais detalhes sobre isso em [Do I need a connector](http://technet.microsoft.com/library/16731ae9-c909-49dd-bffc-a46e6151fc29.aspx)? e [Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx).</span><span class="sxs-lookup"><span data-stu-id="066b7-p104">You can configure a connector to enable mail flow between Office 365 (including Exchange Online or EOP) and an SMTP-based email server such as Exchange. For details about this, see [Do I need a connector](http://technet.microsoft.com/library/16731ae9-c909-49dd-bffc-a46e6151fc29.aspx)? And [Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx).</span></span>
  
## <a name="secure-messaging-with-a-trusted-partner"></a><span data-ttu-id="066b7-121">Mensagens seguras com um parceiro confiável</span><span class="sxs-lookup"><span data-stu-id="066b7-121">Secure messaging with a trusted partner</span></span>
<span data-ttu-id="066b7-122"><a name="BKMK_securemessagingwithatrustedpartner"> </a></span><span class="sxs-lookup"><span data-stu-id="066b7-122"></span></span>

<span data-ttu-id="066b7-p105">Como cliente da EOP, você configura um fluxo de emails seguro com um parceiro de confiança usando os conectores do Office 365. O Office 365 dá suporte à comunicação segura por meio de TLS (Transport Layer Security), e você cria um conector para impor criptografia por meio de TLS. O [TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx) é um protocolo criptográfico que oferece segurança para comunicações pela Internet. Usando conectores, você configura o TLS forçado tanto de entrada quanto de saída usando certificados autoassinados ou certificados validados pela AC (autoridade de certificação). Você também aplica outras restrições de segurança, como especificar nomes de domínio ou intervalos de endereços IP, dos quais a organização parceira envia emails.</span><span class="sxs-lookup"><span data-stu-id="066b7-p105">As an EOP customer, you can set up secure mail flow with a trusted partner by using Office 365 connectors. Office 365 supports secure communication through Transport Layer Security (TLS), and you can create a connector to enforce encryption via TLS. [TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx) is a cryptographic protocol that provides security for communications over the Internet. By using connectors, you can configure both forced incoming and outgoing TLS using self-signed or certification authority (CA)-validated certificates. You can also apply other security restrictions, such as specifying domain names or IP address ranges from which your partner organization sends mail.</span></span> 
  
<span data-ttu-id="066b7-128">Saiba mais em [Configurar conectores para fluxo de email seguro com uma organização parceira](https://technet.microsoft.com/en-us/library/dn751021%28v=exchg.150%29.aspx)</span><span class="sxs-lookup"><span data-stu-id="066b7-128">For more information, see [Set up connectors for secure mail flow with a partner organization](https://technet.microsoft.com/en-us/library/dn751021%28v=exchg.150%29.aspx).</span></span>
  
## <a name="safe-listing-a-partners-ip-address"></a><span data-ttu-id="066b7-129">Lista segura de endereço IP de um parceiro</span><span class="sxs-lookup"><span data-stu-id="066b7-129">Safe listing a partner's IP address</span></span>
<span data-ttu-id="066b7-130"><a name="BKMK_safelistingapartnersipaddress"> </a></span><span class="sxs-lookup"><span data-stu-id="066b7-130"><a name="BKMK_safelistingapartnersipaddress"> </a></span></span>

<span data-ttu-id="066b7-p106">Você pode adicionar o endereço IP de um parceiro de confiança a uma lista segura para garantir que as mensagens enviadas por ele não fiquem sujeitas ao filtro antispam. Para tanto, você pode usar a Lista de IPs Permitidos do filtro de conexão. Saiba mais em [Configure a política de filtro de conexão](https://go.microsoft.com/fwlink/p/?LinkID=287108).</span><span class="sxs-lookup"><span data-stu-id="066b7-p106">You can add a trusted partner's IP address to a safe list to ensure that messages they send to you are not subject to spam filtering. To do this, you can use the connection filter's IP Allow list. For more information, see [Configure the connection filter policy](https://go.microsoft.com/fwlink/p/?LinkID=287108).</span></span>
  
## <a name="conditional-mail-routing"></a><span data-ttu-id="066b7-134">Roteamento de email condicional</span><span class="sxs-lookup"><span data-stu-id="066b7-134">Conditional mail routing</span></span>
<span data-ttu-id="066b7-135"><a name="BKMK_conditionalmailrouting"> </a></span><span class="sxs-lookup"><span data-stu-id="066b7-135"></span></span>

<span data-ttu-id="066b7-p107">Você pode configurar um conector com uma regra de Transporte que roteia emails para um site específico, com base em condições. Saiba mais em [Scenario: Conditional email routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx).</span><span class="sxs-lookup"><span data-stu-id="066b7-p107">You can configure a connector with a Transport rule that routes mail to a specific site, based on conditions. For more information, see [Scenario: Conditional email routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx).</span></span>
  
## <a name="hybrid-mail-routing"></a><span data-ttu-id="066b7-138">Roteamento híbrido de email</span><span class="sxs-lookup"><span data-stu-id="066b7-138">Hybrid mail routing</span></span>
<span data-ttu-id="066b7-139"><a name="BKMK_hybridmailrouting"> </a></span><span class="sxs-lookup"><span data-stu-id="066b7-139"></span></span>

<span data-ttu-id="066b7-p108">Híbrido significa que você hospeda parte das caixas de correio no local e parte na nuvem (Exchange Online). Você pode mudar de uma implantação autônoma (no local) para uma híbrida.</span><span class="sxs-lookup"><span data-stu-id="066b7-p108">Hybrid means that you host a portion of your mailboxes on premises, and a portion in the cloud (Exchange Online). You can move from a standalone (on-premises) deployment to a hybrid deployment.</span></span>
  
<span data-ttu-id="066b7-p109">Se tiver uma implantação híbrida, poderá proteger suas caixas de correio locais e na nuvem com a EOP. São necessárias licenças autônomas para as caixas de correio locais protegidas por EOP. Confira mais informações sobre o roteamento de emails em uma implantação híbrida em [Roteamento de Transporte em implantações híbridas do Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271757).</span><span class="sxs-lookup"><span data-stu-id="066b7-p109">If you have a hybrid deployment, you can protect your cloud and on-premises mailboxes with EOP. Standalone licenses are required for on-premises mailboxes, when they are protected by EOP. For more information about mail routing in a hybrid deployment, see [Transport routing in Exchange hybrid deployments](https://go.microsoft.com/fwlink/p/?LinkId=271757).</span></span>
  
<span data-ttu-id="066b7-145">O [Assistente de Implantação do Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036) também oferece um provisionamento de implantação híbrida e um guia de transporte de mensagens híbrido.</span><span class="sxs-lookup"><span data-stu-id="066b7-145">The [Microsoft Exchange Server Deployment Assistant](https://go.microsoft.com/fwlink/p/?LinkId=287036) also provides detailed hybrid deployment provisioning and hybrid message transport guidance.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="066b7-146">Disponibilidade de recursos</span><span class="sxs-lookup"><span data-stu-id="066b7-146">Feature Availability</span></span>
<span data-ttu-id="066b7-147"><a name="BKMK_hybridmailrouting"> </a></span><span class="sxs-lookup"><span data-stu-id="066b7-147"></span></span>

<span data-ttu-id="066b7-148">Para exibir a disponibilidade de recursos nos planos do Office 365 nas opções autônomas e nas soluções locais, consulte [Descrição do serviço de proteção do Exchange Online](exchange-online-protection-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="066b7-148">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  

