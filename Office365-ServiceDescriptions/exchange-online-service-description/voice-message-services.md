---
title: Serviços de mensagens de voz
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: 34a1d6a4cbadfb17054aa606a0ae9f25d80b53ac
ms.sourcegitcommit: 19591e97b35c1b2a99e04a496d83af27dc6530d6
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/18/2019
ms.locfileid: "37581427"
---
# <a name="voice-message-services"></a><span data-ttu-id="6a047-102">Serviços de mensagens de voz</span><span class="sxs-lookup"><span data-stu-id="6a047-102">Voice message services</span></span>

## <a name="voice-mail"></a><span data-ttu-id="6a047-103">Caixa postal</span><span class="sxs-lookup"><span data-stu-id="6a047-103">Voice mail</span></span>

<span data-ttu-id="6a047-104">O Microsoft Exchange Online fornece serviços de caixa postal hospedados, que oferecem:</span><span class="sxs-lookup"><span data-stu-id="6a047-104">Microsoft Exchange Online offers hosted voice mail services, which provide:</span></span>
  
- <span data-ttu-id="6a047-105">Atendimento de chamadas (caixa postal)</span><span class="sxs-lookup"><span data-stu-id="6a047-105">Call answering (voice mail)</span></span>
    
- <span data-ttu-id="6a047-106">Interface de usuário de discagem para Exchange (Outlook Voice Access)</span><span class="sxs-lookup"><span data-stu-id="6a047-106">Dial-in user interface to Exchange (Outlook Voice Access)</span></span>
    
- <span data-ttu-id="6a047-107">Interface de discagem para chamadores (atendedor automático)</span><span class="sxs-lookup"><span data-stu-id="6a047-107">Dial-in interface for callers (auto attendant)</span></span>
    
<span data-ttu-id="6a047-108">Os serviços de mensagens de voz hospedados permitem que uma empresa conecte seu sistema de telefone local a serviços de caixa postal fornecidos pelo Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="6a047-108">Hosted voice messaging services allow a company to connect its on-premises phone system to voice mail services provided by Exchange Online.</span></span> <span data-ttu-id="6a047-109">As mensagens de caixa postal são gravadas e armazenadas na infraestrutura do Exchange Online, permitindo que os usuários acessem suas mensagens de voz do Outlook, do Outlook na Web ou de telefones celulares.</span><span class="sxs-lookup"><span data-stu-id="6a047-109">Voice mail messages are recorded and stored in the Exchange Online infrastructure, allowing users to access their voice messages from Outlook, Outlook on the web, or mobile phones.</span></span> <span data-ttu-id="6a047-110">Todas as conexões de telefonia do Exchange Online exigem protocolos de voz sobre IP (VoIP).</span><span class="sxs-lookup"><span data-stu-id="6a047-110">All telephony connections to Exchange Online require voice-over-IP (VoIP) protocols.</span></span> <span data-ttu-id="6a047-111">Os administradores podem conectar os IP PBXs ou sistemas de telefone PBX que usam gateways de mídia VoIP e controladores de borda da sessão (SBCs) ao Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="6a047-111">Administrators can connect on-premises IP PBXs or PBX phone systems using VoIP media gateways and session border controllers (SBCs) to Exchange Online.</span></span> <span data-ttu-id="6a047-112">O gateway de mídia não é necessário se o cliente tiver implantado um IP PBX ou se o PBX compatível com VoIP diretamente e for interoperável com os serviços de mensagens de voz do Exchange.</span><span class="sxs-lookup"><span data-stu-id="6a047-112">A VoIP media gateway is not required if the customer has deployed an IP PBX or if a PBX supports VoIP directly and is interoperable with Exchange voice messaging services.</span></span> <span data-ttu-id="6a047-113">Os SBCs são implantados no perímetro da rede do cliente para conectar uma rede de telefonia local e ajudar a tornar a comunicação (e a rede do cliente) segura contra interceptação e intrusão.</span><span class="sxs-lookup"><span data-stu-id="6a047-113">SBCs are deployed in the perimeter of the customer network to connect an on-premises telephony network and help secure the communications (and the customer network) against eavesdropping and intrusion.</span></span> <span data-ttu-id="6a047-114">A interoperabilidade com as funcionalidades de voz do Microsoft Lync Server 2010 e 2013 também é compatível.</span><span class="sxs-lookup"><span data-stu-id="6a047-114">Interoperability with the voice capabilities of Microsoft Lync Server 2010 and 2013 is also supported.</span></span>
  
<span data-ttu-id="6a047-115">Os recursos de serviços de mensagens de voz disponíveis no Exchange Online são semelhantes aos oferecidos no Exchange Server 2016 local.</span><span class="sxs-lookup"><span data-stu-id="6a047-115">The voice messaging services features available in Exchange Online are similar to those offered in on-premises Exchange Server 2016.</span></span> <span data-ttu-id="6a047-116">Entre eles:</span><span class="sxs-lookup"><span data-stu-id="6a047-116">These include:</span></span>
  
- <span data-ttu-id="6a047-117">Tocar no telefone do Outlook e do Outlook na Web.</span><span class="sxs-lookup"><span data-stu-id="6a047-117">Play on phone from Outlook and Outlook on the web.</span></span>
    
- <span data-ttu-id="6a047-118">Notificações de chamada não atendida.</span><span class="sxs-lookup"><span data-stu-id="6a047-118">Missed call notifications.</span></span>
    
- <span data-ttu-id="6a047-119">ID de quem fez a chamada (usando as informações da Lista de Endereços Global, contatos pessoais dos usuários, pasta Contatos personalizada e contatos das redes sociais externas).</span><span class="sxs-lookup"><span data-stu-id="6a047-119">Caller ID (using information in the Global Address List, users' personal contacts, custom Contacts folder, and contacts from external social networks).</span></span>
    
- <span data-ttu-id="6a047-120">Redefinição de PIN de caixa postal do Outlook na Web e do Outlook (consulte [redefinir um PIN de caixa postal](https://go.microsoft.com/fwlink/p/?LinkId=286328)).</span><span class="sxs-lookup"><span data-stu-id="6a047-120">Voice mail PIN reset from Outlook on the web and Outlook (see [Reset a Voice Mail PIN](https://go.microsoft.com/fwlink/p/?LinkId=286328)).</span></span>
    
- <span data-ttu-id="6a047-121">Indicador de Espera da Mensagem (confira [MWI no Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271794) para ver detalhes).</span><span class="sxs-lookup"><span data-stu-id="6a047-121">Message Waiting Indicator (see [MWI in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271794) for details).</span></span> 
    
- <span data-ttu-id="6a047-122">Regras de atendimento de chamadas (Confira [permitir que os usuários de caixa postal encaminhem as chamadas](https://go.microsoft.com/fwlink/p/?LinkId=271795) para obter detalhes).</span><span class="sxs-lookup"><span data-stu-id="6a047-122">Call answering rules (see [Allow voice mail users to forward calls](https://go.microsoft.com/fwlink/p/?LinkId=271795) for details).</span></span>
    
- <span data-ttu-id="6a047-123">Caixa postal protegida no Exchange Online (consulte [proteger caixa postal no Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271796) para obter detalhes).</span><span class="sxs-lookup"><span data-stu-id="6a047-123">Protected voice mail in Exchange Online (see [Protect voice mail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271796) for details).</span></span>
    
- <span data-ttu-id="6a047-124">Visualização de caixa postal (consulte [permitir que os usuários vejam uma transcrição](https://go.microsoft.com/fwlink/p/?LinkId=271797) de caixa postal para obter uma lista de idiomas com suporte).</span><span class="sxs-lookup"><span data-stu-id="6a047-124">Voice mail preview (see [Allow users to see a voice mail transcript](https://go.microsoft.com/fwlink/p/?LinkId=271797) for a list of supported languages).</span></span>
    
- <span data-ttu-id="6a047-125">Acesso de fala ao e-mail, correio de voz, agenda, contatos pessoais e grupos de contato pessoal.</span><span class="sxs-lookup"><span data-stu-id="6a047-125">Speech access to email, voice mail, calendar, personal contacts, and personal contact groups.</span></span>
    
- <span data-ttu-id="6a047-126">Pesquisa de diretório por meio do Outlook Voice Access ou de um atendente automático.</span><span class="sxs-lookup"><span data-stu-id="6a047-126">Directory search through Outlook Voice Access or an auto attendant.</span></span>
    
- <span data-ttu-id="6a047-127">Os administradores configuram e gerenciam a interoperabilidade dos serviços de mensagens de voz usando o centro de administração do Exchange (EAC).</span><span class="sxs-lookup"><span data-stu-id="6a047-127">Administrators configure and manage voice messaging services interoperability by using the Exchange admin center (EAC).</span></span>
    
<span data-ttu-id="6a047-128">Para obter mais informações sobre recursos de caixa postal, consulte caixa [postal no Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271798).</span><span class="sxs-lookup"><span data-stu-id="6a047-128">For more information about voice mail features, see [Voice mail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271798).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="6a047-129">O recurso Reconhecimento Automático de Fala (ASR) não está disponível na navegação por menus ou na pesquisa de diretório para usuários do Outlook Voice Access ou de chamadores de atendedor automático que usam comandos de voz.</span><span class="sxs-lookup"><span data-stu-id="6a047-129">The Automatic Speech Recognition (ASR) feature isn't available in menu navigation or directory search for Outlook Voice Access users or auto attendant callers using voice commands.</span></span> 
>
> <span data-ttu-id="6a047-130">O cliente deve fornecer uma conexão de telefonia da rede telefônica pública comutada (PSTN) usando um gateway VoIP e PBX, IP PBX ou Skype for Business Server 2015.</span><span class="sxs-lookup"><span data-stu-id="6a047-130">The customer must provide a telephony connection from the public switched telephone network (PSTN) using a VoIP gateway and PBX, IP PBX, or Skype for Business Server 2015.</span></span> 
>
> <span data-ttu-id="6a047-131">O cliente deve fornecer os dispositivos de hardware de SBC locais e garantir que o SBCs esteja configurado corretamente para se conectar aos serviços de caixa postal online.</span><span class="sxs-lookup"><span data-stu-id="6a047-131">The customer must provide the on-premises SBC hardware devices and ensure that the SBCs are correctly configured to connect to the online voice mail services.</span></span> <span data-ttu-id="6a047-132">Isso inclui a configuração do nível apropriado de segurança usando certificados e interfaces IP públicas e particulares e habilitando as portas TCP corretas por meio de firewalls locais.</span><span class="sxs-lookup"><span data-stu-id="6a047-132">This includes configuring the appropriate level of security by using certificates and public and private IP interfaces and by enabling the correct TCP ports through their on-premises firewalls.</span></span> 
>
> <span data-ttu-id="6a047-133">A caixa postal hospedada está disponível somente para assinantes do Exchange Online Plan 2 e Office 365 Enterprise E3.</span><span class="sxs-lookup"><span data-stu-id="6a047-133">Hosted voice mail is available only to Exchange Online Plan 2 and Office 365 Enterprise E3 subscribers.</span></span> 
  
## <a name="third-party-voice-mail-interoperability"></a><span data-ttu-id="6a047-134">Interoperabilidade do correio de voz de terceiros.</span><span class="sxs-lookup"><span data-stu-id="6a047-134">Third-party voice mail interoperability</span></span>

<span data-ttu-id="6a047-p104">As soluções de caixa postal locais de terceiros poderão interoperar com o Exchange Online se puderem encaminhar mensagens de voz por meio de SMTP ou se oferecerem suporte a Serviços Web do Microsoft Exchange. Se o sistema de caixa postal não suportar nativamente o encaminhamento de mensagens de voz por meio de SMTP, um servidor de email poderá ser mantido localmente para receber mensagens do sistema de caixa postal e encaminhá-las à nuvem usando SMTP. Como muitos sistemas de caixa postal de terceiros usam MAPI/CDO para interoperar com o Exchange Server para recursos de UM avançados, todos os recursos desses sistemas poderão não estar disponíveis quando SMTP for usado para interoperabilidade com o Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="6a047-p104">On-premises voice mail solutions from third-party providers can interoperate with Exchange Online if they can forward voice messages through SMTP or if they support Microsoft Exchange Web Services. If the voice mail system does not natively support forwarding voice messages through SMTP, an email server can be kept on-premises to receive messages from the voice mail system and then forward them to the cloud using SMTP. Because many third-party voice mail systems use MAPI/CDO to interoperate with Exchange Server for advanced UM features, the full capabilities of these systems may not be available when SMTP is used for interoperability with Exchange Online.</span></span>
  
> [!NOTE]
> <span data-ttu-id="6a047-138">O suporte a UM do Exchange Online para sistemas PBX de terceiros por meio de conexões diretas do SBCs operado pelo cliente terminará em julho de 2018.</span><span class="sxs-lookup"><span data-stu-id="6a047-138">Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018.</span></span> <span data-ttu-id="6a047-139">Confira [descontinuação de suporte para controladores de borda de sessão na Unificação de mensagens do Exchange Online](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117) para obter mais informações.</span><span class="sxs-lookup"><span data-stu-id="6a047-139">Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117) for more information.</span></span> 
  
## <a name="skype-for-business-integration"></a><span data-ttu-id="6a047-140">Integração do Skype for Business</span><span class="sxs-lookup"><span data-stu-id="6a047-140">Skype for Business integration</span></span>

<span data-ttu-id="6a047-141">As organizações podem comprar o Skype for Business Online como um serviço independente ou como parte do Microsoft Office 365.</span><span class="sxs-lookup"><span data-stu-id="6a047-141">Organizations can purchase Skype for Business Online as a standalone service or as part of Microsoft Office 365.</span></span> <span data-ttu-id="6a047-142">O Skype for Business 2015 local também é suportado.</span><span class="sxs-lookup"><span data-stu-id="6a047-142">Skype for Business 2015 on-premises is also supported.</span></span> <span data-ttu-id="6a047-143">Para saber mais sobre o Skype for Business Online, consulte [Descrição do Serviço do Skype for Business Online](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="6a047-143">To learn more about Skype for Business Online, see [Skype for Business Online Service Description](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="6a047-144">Disponibilidade de recursos</span><span class="sxs-lookup"><span data-stu-id="6a047-144">Feature availability</span></span>

<span data-ttu-id="6a047-145">Para exibir a disponibilidade de recursos nos planos do Office 365, nas opções autônomas e nas soluções locais, consulte [Descrição do serviço do Exchange Online](exchange-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="6a047-145">To view feature availability across Office 365 plans, standalone options, and on-premises solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

