---
title: Serviços de Mensagens de Voz
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: 98591e47ece7c59581824c6df375c41c66b7d2d1
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24034893"
---
# <a name="voice-message-services"></a><span data-ttu-id="e60a0-102">Serviços de Mensagens de Voz</span><span class="sxs-lookup"><span data-stu-id="e60a0-102">Voice Message Services</span></span>

## <a name="voice-mail"></a><span data-ttu-id="e60a0-103">Correio de voz</span><span class="sxs-lookup"><span data-stu-id="e60a0-103">Voice mail</span></span>

<span data-ttu-id="e60a0-104">O Microsoft Exchange Online fornece serviços de caixa postal hospedados, que oferecem:</span><span class="sxs-lookup"><span data-stu-id="e60a0-104">Microsoft Exchange Online offers hosted voice mail services, which provide:</span></span>
  
- <span data-ttu-id="e60a0-105">Atendimento de chamadas (caixa postal)</span><span class="sxs-lookup"><span data-stu-id="e60a0-105">Call answering (voice mail)</span></span>
    
- <span data-ttu-id="e60a0-106">Interface de usuário de discagem para Exchange (Outlook Voice Access)</span><span class="sxs-lookup"><span data-stu-id="e60a0-106">Dial-in user interface to Exchange (Outlook Voice Access)</span></span>
    
- <span data-ttu-id="e60a0-107">Interface de discagem para chamadores (atendedor automático)</span><span class="sxs-lookup"><span data-stu-id="e60a0-107">Dial-in interface for callers (auto attendant)</span></span>
    
<span data-ttu-id="e60a0-p101">Serviços de mensagens de voz hospedada permitem a uma empresa conectar seu sistema telefônico de local aos serviços de correio de voz fornecidos pelo Exchange Online. Mensagens de caixa postal são registradas e armazenadas na infraestrutura do Exchange Online, permitindo que os usuários acessem suas mensagens de voz a partir do Outlook, Outlook na web ou celulares. Todas as conexões de telefonia para o Exchange Online exigem protocolos do voice-over-IP (VoIP). Os administradores podem se conectar a local PBXs IP ou PBX sistemas telefônicos usando gateways de mídia de VoIP e controladores de borda de sessão (SBCs) para o Exchange Online. Um gateway de mídia de VoIP não é necessário se o cliente tiver implantado um PBX IP ou um PBX suporta diretamente o VoIP e é interoperável com serviços de mensagens de voz do Exchange. SBCs são implantados no perímetro de rede do cliente para se conectar a uma rede de telefonia no local e ajudar a proteger as comunicações (e a rede do cliente) contra interceptação e invasão. Também há suporte para a interoperabilidade com os recursos de voz do Microsoft Lync Server 2010 e 2013.</span><span class="sxs-lookup"><span data-stu-id="e60a0-p101">Hosted voice messaging services allow a company to connect its on-premises phone system to voice mail services provided by Exchange Online. Voice mail messages are recorded and stored in the Exchange Online infrastructure, allowing users to access their voice messages from Outlook, Outlook on the web, or mobile phones. All telephony connections to Exchange Online require voice-over-IP (VoIP) protocols. Administrators can connect on-premises IP PBXs or PBX phone systems using VoIP media gateways and session border controllers (SBCs) to Exchange Online. A VoIP media gateway is not required if the customer has deployed an IP PBX or if a PBX supports VoIP directly and is interoperable with Exchange voice messaging services. SBCs are deployed in the perimeter of the customer network to connect an on-premises telephony network and help secure the communications (and the customer network) against eavesdropping and intrusion. Interoperability with the voice capabilities of Microsoft Lync Server 2010 and 2013 is also supported.</span></span>
  
<span data-ttu-id="e60a0-p102">O recursos de serviços disponíveis no Exchange Online de mensagens de voz são semelhantes aos oferecidos em 2016 de servidor do Exchange local. Elas incluem:</span><span class="sxs-lookup"><span data-stu-id="e60a0-p102">The voice messaging services features available in Exchange Online are similar to those offered in on-premises Exchange Server 2016. These include:</span></span>
  
- <span data-ttu-id="e60a0-117">Tocar no telefone do Outlook e do Outlook na web.</span><span class="sxs-lookup"><span data-stu-id="e60a0-117">Play on phone from Outlook and Outlook on the web.</span></span>
    
- <span data-ttu-id="e60a0-118">Notificações de chamada não atendida.</span><span class="sxs-lookup"><span data-stu-id="e60a0-118">Missed call notifications.</span></span>
    
- <span data-ttu-id="e60a0-119">ID de quem fez a chamada (usando as informações da Lista de Endereços Global, contatos pessoais dos usuários, pasta Contatos personalizada e contatos das redes sociais externas).</span><span class="sxs-lookup"><span data-stu-id="e60a0-119">Caller ID (using information in the Global Address List, users' personal contacts, custom Contacts folder, and contacts from external social networks).</span></span>
    
- <span data-ttu-id="e60a0-120">Caixa postal PIN redefinido a partir do Outlook na web e Outlook (consulte [Redefinir PIN da caixa postal](https://go.microsoft.com/fwlink/p/?LinkId=286328)).</span><span class="sxs-lookup"><span data-stu-id="e60a0-120">Voice mail PIN reset from Outlook on the web and Outlook (see [Reset a Voice Mail PIN](https://go.microsoft.com/fwlink/p/?LinkId=286328)).</span></span>
    
- <span data-ttu-id="e60a0-121">Indicador de Espera da Mensagem (confira [MWI no Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271794) para ver detalhes).</span><span class="sxs-lookup"><span data-stu-id="e60a0-121">Message Waiting Indicator (see [MWI in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271794) for details).</span></span> 
    
- <span data-ttu-id="e60a0-122">Regras para Responder as Chamadas (confira [Permitir que Usuários do Correio de Voz Encaminhem Chamadas](https://go.microsoft.com/fwlink/p/?LinkId=271795) para ver detalhes).</span><span class="sxs-lookup"><span data-stu-id="e60a0-122">Call Answering Rules (see [Allow Voice Mail Users to Forward Calls](https://go.microsoft.com/fwlink/p/?LinkId=271795) for details).</span></span> 
    
- <span data-ttu-id="e60a0-123">Correio de Voz Protegido no Exchange Online (confira [Protected Voice Mail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271796) para saber mais detalhes).</span><span class="sxs-lookup"><span data-stu-id="e60a0-123">Protected Voice Mail in Exchange Online (see [Protected Voice Mail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271796) for details).</span></span> 
    
- <span data-ttu-id="e60a0-124">Visualizar Correio de Voz (confira[Permitir que Usuários Vejam a Transcrição do Correio de Voz](https://go.microsoft.com/fwlink/p/?LinkId=271797) para ver uma lista de idiomas suportados).</span><span class="sxs-lookup"><span data-stu-id="e60a0-124">Voice Mail Preview (see [Allow Users to See a Voice Mail Transcript](https://go.microsoft.com/fwlink/p/?LinkId=271797) for a list of supported languages).</span></span> 
    
- <span data-ttu-id="e60a0-125">Acesso de fala ao e-mail, correio de voz, agenda, contatos pessoais e grupos de contato pessoal.</span><span class="sxs-lookup"><span data-stu-id="e60a0-125">Speech access to email, voice mail, calendar, personal contacts, and personal contact groups.</span></span>
    
- <span data-ttu-id="e60a0-126">Pesquisa de diretório por meio do Outlook Voice Access ou de um atendente automático.</span><span class="sxs-lookup"><span data-stu-id="e60a0-126">Directory search through Outlook Voice Access or an auto attendant.</span></span>
    
- <span data-ttu-id="e60a0-127">Os administradores configuram e gerenciam a interoperabilidade dos serviços de mensagens de voz usando o centro de administração do Exchange (EAC).</span><span class="sxs-lookup"><span data-stu-id="e60a0-127">Administrators configure and manage voice messaging services interoperability by using the Exchange admin center (EAC).</span></span>
    
<span data-ttu-id="e60a0-128">Para saber mais sobre os recursos do correio de voz, confira [Correio de Voz no Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271798).</span><span class="sxs-lookup"><span data-stu-id="e60a0-128">For more information about voice mail features, see [Voice Mail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271798).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="e60a0-p103">O recurso Reconhecimento Automático de Fala (ASR) não está disponível na navegação por menus ou na pesquisa de diretório para usuários do Outlook Voice Access ou de chamadores de atendedor automático que usam comandos de voz. > O cliente deve fornecer uma conexão de telefonia a partir da rede telefônica pública comutada (PSTN) usando um gateway VoIP e PBX, IP PBX ou Skype for Business Server 2015. > O cliente deve fornecer os dispositivos de hardware SBC locais e assegurar que os SBCs sejam configurados corretamente para conectar os serviços do correio de voz on-line. Isso inclui a configuração do nível apropriado de segurança usando certificados e interfaces IP públicas e particulares e habilitando as portas TCP corretas por meio de firewalls locais. > A caixa postal hospedada está disponível somente para o Plano 2 do Exchange Online e assinantes do Office 365 Enterprise E3.</span><span class="sxs-lookup"><span data-stu-id="e60a0-p103">The Automatic Speech Recognition (ASR) feature isn't available in menu navigation or directory search for Outlook Voice Access users or auto attendant callers using voice commands. > The customer must provide a telephony connection from the public switched telephone network (PSTN) using a VoIP gateway and PBX, IP PBX, or Skype for Business Server 2015. > The customer must provide the on-premises SBC hardware devices and ensure that the SBCs are correctly configured to connect to the online voice mail services. This includes configuring the appropriate level of security by using certificates and public and private IP interfaces and by enabling the correct TCP ports through their on-premises firewalls. > Hosted voice mail is available only to Exchange Online Plan 2 and Office 365 Enterprise E3 subscribers.</span></span> 
  
## <a name="third-party-voice-mail-interoperability"></a><span data-ttu-id="e60a0-134">Interoperabilidade do correio de voz de terceiros.</span><span class="sxs-lookup"><span data-stu-id="e60a0-134">Third-party voice mail interoperability</span></span>

<span data-ttu-id="e60a0-p104">As soluções de caixa postal locais de terceiros poderão interoperar com o Exchange Online se puderem encaminhar mensagens de voz por meio de SMTP ou se oferecerem suporte a Serviços Web do Microsoft Exchange. Se o sistema de caixa postal não suportar nativamente o encaminhamento de mensagens de voz por meio de SMTP, um servidor de email poderá ser mantido localmente para receber mensagens do sistema de caixa postal e encaminhá-las à nuvem usando SMTP. Como muitos sistemas de caixa postal de terceiros usam MAPI/CDO para interoperar com o Exchange Server para recursos de UM avançados, todos os recursos desses sistemas poderão não estar disponíveis quando SMTP for usado para interoperabilidade com o Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="e60a0-p104">On-premises voice mail solutions from third-party providers can interoperate with Exchange Online if they can forward voice messages through SMTP or if they support Microsoft Exchange Web Services. If the voice mail system does not natively support forwarding voice messages through SMTP, an email server can be kept on-premises to receive messages from the voice mail system and then forward them to the cloud using SMTP. Because many third-party voice mail systems use MAPI/CDO to interoperate with Exchange Server for advanced UM features, the full capabilities of these systems may not be available when SMTP is used for interoperability with Exchange Online.</span></span>
  
> [!NOTE]
> <span data-ttu-id="e60a0-p105">Exchange Online UM suporte para sistemas de PBX de terceiros por meio de conexões diretas do cliente operado SBCs será finalizado no de 2018 julho. Consulte [suporte para controladores de borda de sessão no Exchange Online Unified Messaging Descontinuado](https://blogs.technet.microsoft.com/exchange/2017/07/18/discontinuation-of-support-for-session-border-controllers-in-exchange-online-unified-messaging/) para obter mais informações.</span><span class="sxs-lookup"><span data-stu-id="e60a0-p105">Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018. Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://blogs.technet.microsoft.com/exchange/2017/07/18/discontinuation-of-support-for-session-border-controllers-in-exchange-online-unified-messaging/) for more information.</span></span> 
  
## <a name="skype-for-business-integration"></a><span data-ttu-id="e60a0-140">Integração do Skype for Business</span><span class="sxs-lookup"><span data-stu-id="e60a0-140">Skype for Business integration</span></span>

<span data-ttu-id="e60a0-p106">As organizações podem adquirir Skype para Business Online como um serviço autônomo ou como parte do Microsoft Office 365. Skype para negócios 2015 local também é suportada. Para saber mais sobre Skype para Business Online, consulte [Skype para negócios Online Service Description](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="e60a0-p106">Organizations can purchase Skype for Business Online as a standalone service or as part of Microsoft Office 365. Skype for Business 2015 on-premises is also supported. To learn more about Skype for Business Online, see [Skype for Business Online Service Description](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="e60a0-144">Disponibilidade do recurso</span><span class="sxs-lookup"><span data-stu-id="e60a0-144">Feature Availability</span></span>

<span data-ttu-id="e60a0-145">Para exibir a disponibilidade de recursos nos planos do Office 365 nas opções autônomas e nas soluções locais, consulte [Descrição de Serviço do Exchange Online](exchange-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="e60a0-145">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  
