---
title: Interoperabilidade, Conectividade e Compatibilidade
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-interoperability-connectivity-compatibility
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cdfe686d-a059-4f4d-bb8d-9c2c0ebfa423
ms.openlocfilehash: 80d4248da8fd9d3600789df35085c24e6e436433
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/22/2019
ms.locfileid: "34342680"
---
# <a name="interoperability-connectivity-and-compatibility"></a>Interoperabilidade, Conectividade e Compatibilidade

## <a name="interoperability-with-other-microsoft-products"></a>Interoperabilidade com outros produtos da Microsoft

### <a name="skype-for-business-online"></a>Skype for Business Online

Para clientes que implantaram o Microsoft Lync Server 2010, o Lync Server 2013 ou o Microsoft Office Communications Server 2007 R2 localmente, o Microsoft Office Communicator poderá se conectar ao Microsoft Exchange Online usando os Serviços Web do Exchange para acessar dados de calendário e mensagens de ausência temporária.
  
O Lync Server 2010 e o Lync Server 2013 locais poderão interoperar com o Exchange Online de duas maneiras adicionais:
  
- IM (Mensagens instantâneas) e interoperabilidade de presença no Outlook Web App
    
- Interoperabilidade de caixa postal
    
Para saber mais sobre como configurar o Skype for Business Server 2015 com o Exchange Online, confira [Configurando a integração local do Skype for Business Server 2015 com o Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804). Para configurações híbridas, confira [Configurações híbridas do Skype for Business Server 2015 compatíveis](https://go.microsoft.com/fwlink/?LinkID=513084).
  
### <a name="microsoft-sharepoint"></a>Microsoft SharePoint

Para os clientes que implantaram o Microsoft SharePoint Server ou o SharePoint Online, como parte de um plano de assinatura do Office 365, o SharePoint pode conectar-se ao Exchange Online para serviços integrados.
  
Para saber mais sobre conectar o SharePoint ao Exchange Online, confira [Utilizar o SharePoint Online em um domínio personalizado junto com outros serviços](https://go.microsoft.com/fwlink/?LinkId=271805).
  
## <a name="features-for-external-connectivity"></a>Recursos para conectividade externa

O Exchange Online oferece os seguintes recursos para a conexão com aplicativos e dispositivos externos:
  
- **Por meio de protocolos de mensagem, como MAPI sobre HTTP, SMTP, POP3, IMAP4 ou Serviços Web do Exchange** Os aplicativos externos que estão sendo executados no local, no Azure ou em outros serviços hospedados podem acessar os dados armazenados com o Exchange Online usando protocolos de mensagem, como MAPI sobre HTTP, SMTP, POP3 e IMAPv4. Os Serviços Web Exchange, ou API de Serviços Gerenciados do Web Exchange são recomendados para o desenvolvimento do aplicativo. 
    
- **Como uma retransmissão SMTP** O Exchange Online pode ser configurado como um serviço de entrega SMTP para retransmitir mensagens de email enviadas por gateways de fax, dispositivos de rede e aplicativos personalizados. 
    
### <a name="exchange-web-services"></a>Serviços Web do Exchange

Serviços Web Exchange (EWS) são o API de desenvolvimento preferencial para o Exchange Server e o Exchange Online. Usando o EWS ou a API gerenciada do EWS, os administradores podem acessar os dados armazenados com o Exchange Online a partir dos aplicativos executados no local, no Azure ou em outros serviços hospedados. O EWS permite que os administradores realizem ações especializadas, como consultar o conteúdo de uma caixa de correio em fila, publicar um evento de calendário, criar uma tarefa ou disparar uma ação específica baseada no conteúdo de uma mensagem de email. O Exchange Online habilita a funcionalidade EWS, concedendo permissões de aplicativo para as contas de clientes. Essas permissões permitem que o aplicativo de cliente acesse a caixa de correio do aplicativo e adicione conteúdo. A Representação do Exchange é um método usado para conceder permissões de aplicativo. Para obter mais detalhes sobre como usar os Serviços Web do Exchange com o Exchange Online, consulte os artigos técnicos no Centro de Desenvolvimento do Exchange Online.
  
### <a name="smtp-relay"></a>Retransmissão SMTP

O Exchange Online pode ser usado como um serviço de entrega SMTP, para retransmitir as mensagens de email enviadas de gateways de fax, dispositivos de rede e aplicativos personalizados. Por exemplo, se um aplicativo de linha de negócios envia alertas de email para usuários, ele pode ser configurado para usar o Exchange Online como o sistema de entrega de email. O aplicativo ou serviço deve ser autenticado com o nome de usuário e senha de uma caixa de correio válida e licenciada do Exchange Online, e conectar-se usando o protocolo TLS (Transport Layer Security).
  
## <a name="feature-availability"></a>Disponibilidade do recurso

Para exibir a disponibilidade de recursos nos planos do Office 365 nas opções autônomas e nas soluções locais, consulte [Descrição de Serviço do Exchange Online](exchange-online-service-description.md).
  

