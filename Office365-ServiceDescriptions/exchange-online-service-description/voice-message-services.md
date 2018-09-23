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
# <a name="voice-message-services"></a>Serviços de Mensagens de Voz

## <a name="voice-mail"></a>Correio de voz

O Microsoft Exchange Online fornece serviços de caixa postal hospedados, que oferecem:
  
- Atendimento de chamadas (caixa postal)
    
- Interface de usuário de discagem para Exchange (Outlook Voice Access)
    
- Interface de discagem para chamadores (atendedor automático)
    
Serviços de mensagens de voz hospedada permitem a uma empresa conectar seu sistema telefônico de local aos serviços de correio de voz fornecidos pelo Exchange Online. Mensagens de caixa postal são registradas e armazenadas na infraestrutura do Exchange Online, permitindo que os usuários acessem suas mensagens de voz a partir do Outlook, Outlook na web ou celulares. Todas as conexões de telefonia para o Exchange Online exigem protocolos do voice-over-IP (VoIP). Os administradores podem se conectar a local PBXs IP ou PBX sistemas telefônicos usando gateways de mídia de VoIP e controladores de borda de sessão (SBCs) para o Exchange Online. Um gateway de mídia de VoIP não é necessário se o cliente tiver implantado um PBX IP ou um PBX suporta diretamente o VoIP e é interoperável com serviços de mensagens de voz do Exchange. SBCs são implantados no perímetro de rede do cliente para se conectar a uma rede de telefonia no local e ajudar a proteger as comunicações (e a rede do cliente) contra interceptação e invasão. Também há suporte para a interoperabilidade com os recursos de voz do Microsoft Lync Server 2010 e 2013.
  
O recursos de serviços disponíveis no Exchange Online de mensagens de voz são semelhantes aos oferecidos em 2016 de servidor do Exchange local. Elas incluem:
  
- Tocar no telefone do Outlook e do Outlook na web.
    
- Notificações de chamada não atendida.
    
- ID de quem fez a chamada (usando as informações da Lista de Endereços Global, contatos pessoais dos usuários, pasta Contatos personalizada e contatos das redes sociais externas).
    
- Caixa postal PIN redefinido a partir do Outlook na web e Outlook (consulte [Redefinir PIN da caixa postal](https://go.microsoft.com/fwlink/p/?LinkId=286328)).
    
- Indicador de Espera da Mensagem (confira [MWI no Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271794) para ver detalhes). 
    
- Regras para Responder as Chamadas (confira [Permitir que Usuários do Correio de Voz Encaminhem Chamadas](https://go.microsoft.com/fwlink/p/?LinkId=271795) para ver detalhes). 
    
- Correio de Voz Protegido no Exchange Online (confira [Protected Voice Mail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271796) para saber mais detalhes). 
    
- Visualizar Correio de Voz (confira[Permitir que Usuários Vejam a Transcrição do Correio de Voz](https://go.microsoft.com/fwlink/p/?LinkId=271797) para ver uma lista de idiomas suportados). 
    
- Acesso de fala ao e-mail, correio de voz, agenda, contatos pessoais e grupos de contato pessoal.
    
- Pesquisa de diretório por meio do Outlook Voice Access ou de um atendente automático.
    
- Os administradores configuram e gerenciam a interoperabilidade dos serviços de mensagens de voz usando o centro de administração do Exchange (EAC).
    
Para saber mais sobre os recursos do correio de voz, confira [Correio de Voz no Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271798).
  
> [!IMPORTANT]
> O recurso Reconhecimento Automático de Fala (ASR) não está disponível na navegação por menus ou na pesquisa de diretório para usuários do Outlook Voice Access ou de chamadores de atendedor automático que usam comandos de voz. > O cliente deve fornecer uma conexão de telefonia a partir da rede telefônica pública comutada (PSTN) usando um gateway VoIP e PBX, IP PBX ou Skype for Business Server 2015. > O cliente deve fornecer os dispositivos de hardware SBC locais e assegurar que os SBCs sejam configurados corretamente para conectar os serviços do correio de voz on-line. Isso inclui a configuração do nível apropriado de segurança usando certificados e interfaces IP públicas e particulares e habilitando as portas TCP corretas por meio de firewalls locais. > A caixa postal hospedada está disponível somente para o Plano 2 do Exchange Online e assinantes do Office 365 Enterprise E3. 
  
## <a name="third-party-voice-mail-interoperability"></a>Interoperabilidade do correio de voz de terceiros.

As soluções de caixa postal locais de terceiros poderão interoperar com o Exchange Online se puderem encaminhar mensagens de voz por meio de SMTP ou se oferecerem suporte a Serviços Web do Microsoft Exchange. Se o sistema de caixa postal não suportar nativamente o encaminhamento de mensagens de voz por meio de SMTP, um servidor de email poderá ser mantido localmente para receber mensagens do sistema de caixa postal e encaminhá-las à nuvem usando SMTP. Como muitos sistemas de caixa postal de terceiros usam MAPI/CDO para interoperar com o Exchange Server para recursos de UM avançados, todos os recursos desses sistemas poderão não estar disponíveis quando SMTP for usado para interoperabilidade com o Exchange Online.
  
> [!NOTE]
> Exchange Online UM suporte para sistemas de PBX de terceiros por meio de conexões diretas do cliente operado SBCs será finalizado no de 2018 julho. Consulte [suporte para controladores de borda de sessão no Exchange Online Unified Messaging Descontinuado](https://blogs.technet.microsoft.com/exchange/2017/07/18/discontinuation-of-support-for-session-border-controllers-in-exchange-online-unified-messaging/) para obter mais informações. 
  
## <a name="skype-for-business-integration"></a>Integração do Skype for Business

As organizações podem adquirir Skype para Business Online como um serviço autônomo ou como parte do Microsoft Office 365. Skype para negócios 2015 local também é suportada. Para saber mais sobre Skype para Business Online, consulte [Skype para negócios Online Service Description](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).
  
## <a name="feature-availability"></a>Disponibilidade do recurso

Para exibir a disponibilidade de recursos nos planos do Office 365 nas opções autônomas e nas soluções locais, consulte [Descrição de Serviço do Exchange Online](exchange-online-service-description.md).
  

