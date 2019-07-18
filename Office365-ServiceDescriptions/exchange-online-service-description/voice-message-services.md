---
title: Serviços de Mensagens de Voz
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
ms.openlocfilehash: 7f01e3e013ea714735af300a8ecf36dd26984757
ms.sourcegitcommit: 96dc758c790ddaf05f5c2b836451b417729cf119
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/18/2019
ms.locfileid: "35776922"
---
# <a name="voice-message-services"></a>Serviços de Mensagens de Voz

## <a name="voice-mail"></a>Caixa postal

O Microsoft Exchange Online fornece serviços de caixa postal hospedados, que oferecem:
  
- Atendimento de chamadas (caixa postal)
    
- Interface de usuário de discagem para Exchange (Outlook Voice Access)
    
- Interface de discagem para chamadores (atendedor automático)
    
Os serviços de mensagens de voz hospedados permitem que uma empresa conecte seu sistema de telefone local a serviços de caixa postal fornecidos pelo Exchange Online. As mensagens de caixa postal são gravadas e armazenadas na infraestrutura do Exchange Online, permitindo que os usuários acessem suas mensagens de voz do Outlook, do Outlook na Web ou de telefones celulares. Todas as conexões de telefonia do Exchange Online exigem protocolos de voz sobre IP (VoIP). Os administradores podem conectar os IP PBXs ou sistemas de telefone PBX que usam gateways de mídia VoIP e controladores de borda da sessão (SBCs) ao Exchange Online. O gateway de mídia não é necessário se o cliente tiver implantado um IP PBX ou se o PBX compatível com VoIP diretamente e for interoperável com os serviços de mensagens de voz do Exchange. Os SBCs são implantados no perímetro da rede do cliente para conectar uma rede de telefonia local e ajudar a tornar a comunicação (e a rede do cliente) segura contra interceptação e intrusão. A interoperabilidade com as funcionalidades de voz do Microsoft Lync Server 2010 e 2013 também é compatível.
  
Os recursos de serviços de mensagens de voz disponíveis no Exchange Online são semelhantes aos oferecidos no Exchange Server 2016 local. Entre eles:
  
- Tocar no telefone do Outlook e do Outlook na Web.
    
- Notificações de chamada não atendida.
    
- ID de quem fez a chamada (usando as informações da Lista de Endereços Global, contatos pessoais dos usuários, pasta Contatos personalizada e contatos das redes sociais externas).
    
- Redefinição de PIN de caixa postal do Outlook na Web e do Outlook (consulte [redefinir um PIN de caixa postal](https://go.microsoft.com/fwlink/p/?LinkId=286328)).
    
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
> O suporte a UM do Exchange Online para sistemas PBX de terceiros por meio de conexões diretas do SBCs operado pelo cliente terminará em julho de 2018. Confira [descontinuação de suporte para controladores de borda de sessão na Unificação de mensagens do Exchange Online](https://blogs.technet.microsoft.com/exchange/2017/07/18/discontinuation-of-support-for-session-border-controllers-in-exchange-online-unified-messaging/) para obter mais informações. 
  
## <a name="skype-for-business-integration"></a>Integração do Skype for Business

As organizações podem comprar o Skype for Business Online como um serviço independente ou como parte do Microsoft Office 365. O Skype for Business 2015 local também é suportado. Para saber mais sobre o Skype for Business Online, consulte [Descrição do Serviço do Skype for Business Online](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).
  
## <a name="feature-availability"></a>Disponibilidade do recurso

Para exibir a disponibilidade de recursos nos planos do Office 365 nas opções autônomas e nas soluções locais, consulte [Descrição de Serviço do Exchange Online](exchange-online-service-description.md).
  

