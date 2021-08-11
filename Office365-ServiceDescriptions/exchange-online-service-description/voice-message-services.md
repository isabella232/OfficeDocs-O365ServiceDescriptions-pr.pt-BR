---
title: Serviços de mensagens de voz
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: 42a92a444a49b19d4589dd733426505c92c59e563776728f2ecf02aef53a7b36
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 08/06/2021
ms.locfileid: "54663584"
---
# <a name="voice-message-services"></a>Serviços de mensagens de voz

## <a name="voice-mail"></a>Caixa postal

O Microsoft Exchange Online fornece serviços de caixa postal hospedados, que oferecem:
  
- Atendimento de chamadas (caixa postal)
    
- Interface de usuário de discagem para Exchange (Outlook Voice Access)
    
- Interface de discagem para chamadores (atendedor automático)
    
Os serviços de mensagens de voz hospedados permitem que uma empresa conecte seu sistema de telefone local a serviços de caixa postal fornecidos pelo Exchange Online. As mensagens de caixa postal são gravadas e armazenadas na infraestrutura Exchange Online, permitindo que os usuários acessem suas mensagens de voz de Outlook, Outlook na Web ou telefones celulares. Todas as conexões de telefonia do Exchange Online exigem protocolos de voz sobre IP (VoIP). Os administradores podem conectar os IP PBXs ou sistemas de telefone PBX que usam gateways de mídia VoIP e controladores de borda da sessão (SBCs) ao Exchange Online. O gateway de mídia não é necessário se o cliente tiver implantado um IP PBX ou se o PBX compatível com VoIP diretamente e for interoperável com os serviços de mensagens de voz do Exchange. Os SBCs são implantados no perímetro da rede do cliente para conectar uma rede de telefonia local e ajudar a tornar a comunicação (e a rede do cliente) segura contra interceptação e intrusão. A interoperabilidade com as funcionalidades de voz do Microsoft Lync Server 2010 e 2013 também é compatível.
  
Os recursos de serviços de mensagens de voz disponíveis no Exchange Online são semelhantes aos oferecidos no Exchange Server 2016. Eles incluem:
  
- Reproduza no telefone de Outlook e Outlook na Web.
    
- Notificações de chamada não atendida.
    
- ID de quem fez a chamada (usando as informações da Lista de Endereços Global, contatos pessoais dos usuários, pasta Contatos personalizada e contatos das redes sociais externas).
    
- Pin de caixa postal redefinido Outlook na Web e Outlook (consulte [Redefinir um PIN de Caixa Postal](/exchange/voice-mail-unified-messaging/set-outlook-voice-access-pin-security/reset-a-voice-mail-pin)).
    
- Indicador de Espera da Mensagem (confira [MWI no Exchange Online](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/mwi-in-exchange-online) para ver detalhes). 
    
- Regras de atendimento de chamadas (consulte Permitir que os usuários de [caixa postal encaminhem chamadas](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-voice-mail-users-to-forward-calls) para obter detalhes).
    
- Caixa postal protegida no Exchange Online (consulte [Protect voice mail in Exchange Online](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/protect-voice-mail) para obter detalhes).
    
- Visualização de caixa postal (consulte Permitir que os usuários [vejam uma transcrição](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-users-to-see-a-voice-mail-transcript) de caixa postal para uma lista de idiomas com suporte).
    
- Acesso de fala ao e-mail, correio de voz, agenda, contatos pessoais e grupos de contato pessoal.
    
- Pesquisa de diretório por meio do Outlook Voice Access ou de um atendente automático.
    
- Os administradores configuram e gerenciam a interoperabilidade dos serviços de mensagens de voz usando o centro de administração do Exchange (EAC).
    
Para obter mais informações sobre recursos de caixa postal, consulte [Caixa postal em Exchange Online](/exchange/voice-mail-unified-messaging/voice-mail-unified-messaging).
  
> [!IMPORTANT]
> O recurso Reconhecimento Automático de Fala (ASR) não está disponível na navegação por menus ou na pesquisa de diretório para usuários do Outlook Voice Access ou de chamadores de atendedor automático que usam comandos de voz. 
>
> O cliente deve fornecer uma conexão de telefonia da PSTN (rede telefônica pública comutado) usando um gateway VoIP e PBX, IP PBX ou Skype for Business Server 2015. 
>
> O cliente deve fornecer os dispositivos de hardware SBC locais e garantir que os SBCs estão configurados corretamente para se conectar aos serviços de caixa postal online. Isso inclui a configuração do nível apropriado de segurança usando certificados e interfaces IP públicas e particulares e habilitando as portas TCP corretas por meio de firewalls locais. 
>
> A caixa postal hospedada está disponível apenas para Exchange Online plano 2 e Office 365 Enterprise assinantes do E3. 
  
## <a name="third-party-voice-mail-interoperability"></a>Interoperabilidade do correio de voz de terceiros.

As soluções de caixa postal locais de terceiros poderão interoperar com o Exchange Online se puderem encaminhar mensagens de voz por meio de SMTP ou se oferecerem suporte a Serviços Web do Microsoft Exchange. Se o sistema de caixa postal não suportar nativamente o encaminhamento de mensagens de voz por meio de SMTP, um servidor de email poderá ser mantido localmente para receber mensagens do sistema de caixa postal e encaminhá-las à nuvem usando SMTP. Como muitos sistemas de caixa postal de terceiros usam MAPI/CDO para interoperar com o Exchange Server para recursos de UM avançados, todos os recursos desses sistemas poderão não estar disponíveis quando SMTP for usado para interoperabilidade com o Exchange Online.
  
> [!NOTE]
> Exchange Online O suporte de UM para sistemas PBX de terceiros por meio de conexões diretas de SBCs operados pelo cliente terminará em julho de 2018. Confira [Descontinuação do suporte para Controladores](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117) de Borda de Sessão Exchange Online Unificação de Mensagens para obter mais informações. 
  
## <a name="skype-for-business-integration"></a>Integração do Skype for Business

As organizações podem comprar o Skype for Business Online como um serviço independente ou como parte do Microsoft Office 365. Skype for Business 2015 local também é suportado. Para saber mais sobre o Skype for Business Online, [consulte Skype for Business descrição do serviço Online.](../skype-for-business-online-service-description/skype-for-business-online-service-description.md)
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos entre planos, opções autônomas e soluções locais, consulte [Exchange Online descrição do serviço.](exchange-online-service-description.md)
