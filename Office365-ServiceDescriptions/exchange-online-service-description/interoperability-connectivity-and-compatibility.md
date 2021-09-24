---
title: Interoperabilidade, conectividade e compatibilidade
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-interoperability-connectivity-compatibility
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: cdfe686d-a059-4f4d-bb8d-9c2c0ebfa423
ms.openlocfilehash: cae4f051e788073223e67364cf36af102e06f4e2
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/24/2021
ms.locfileid: "59671951"
---
# <a name="interoperability-connectivity-and-compatibility"></a>Interoperabilidade, conectividade e compatibilidade

## <a name="interoperability-with-other-microsoft-products"></a>Interoperabilidade com outros produtos da Microsoft

### <a name="skype-for-business-online"></a>Skype for Business Online

Para clientes que implantaram o Microsoft Lync Server 2010, o Lync Server 2013 ou o Microsoft Office Communications Server 2007 R2 localmente, o Microsoft Office Communicator poderá se conectar ao Microsoft Exchange Online usando os Serviços Web do Exchange para acessar dados de calendário e mensagens de ausência temporária.
  
O Lync Server 2010 e o Lync Server 2013 locais poderão interoperar com o Exchange Online de duas maneiras adicionais:
  
- Interoperabilidade de IM e presença no Outlook na Web
    
- Interoperabilidade de caixa postal
    
Para saber mais sobre como configurar o Skype for Business Server 2015 com o Exchange Online, confira [Configurando a integração local do Skype for Business Server 2015 com o Exchange Online](/skypeforbusiness/deploy/integrate-with-exchange-server/outlook-web-app). Para configurações híbridas, confira [Configurações híbridas do Skype for Business Server 2015 compatíveis](/skypeforbusiness/skype-for-business-hybrid-solutions/integration-with-exchange-and-sharepoint).
  
### <a name="microsoft-sharepoint"></a>Microsoft SharePoint

Para clientes que implantaram o Microsoft SharePoint Server ou SharePoint Online como parte de um plano de assinatura, o SharePoint pode se conectar ao Exchange Online para serviços integrados.
  
Para saber mais sobre conectar o SharePoint ao Exchange Online, confira [Utilizar o SharePoint Online em um domínio personalizado junto com outros serviços](https://go.microsoft.com/fwlink/?LinkId=271805).
  
## <a name="features-for-external-connectivity"></a>Recursos para conectividade externa

O Exchange Online oferece os seguintes recursos para a conexão com aplicativos e dispositivos externos:
  
- **Por meio de protocolos de mensagem, como MAPI sobre HTTP, SMTP, POP3, IMAP4 ou Serviços Web do Exchange** Os aplicativos externos que estão sendo executados no local, no Azure ou em outros serviços hospedados podem acessar os dados armazenados com o Exchange Online usando protocolos de mensagem, como MAPI sobre HTTP, SMTP, POP3 e IMAPv4. Os Serviços Web Exchange, ou API de Serviços Gerenciados do Web Exchange são recomendados para o desenvolvimento do aplicativo. 
    
- **Como uma retransmissão SMTP** O Exchange Online pode ser configurado como um serviço de entrega SMTP para retransmitir mensagens de email enviadas por gateways de fax, dispositivos de rede e aplicativos personalizados. 
    
### <a name="exchange-web-services"></a>Serviços Web do Exchange

Serviços Web Exchange (EWS) são o API de desenvolvimento preferencial para o Exchange Server e o Exchange Online. Usando o EWS ou a API gerenciada do EWS, os administradores podem acessar os dados armazenados com o Exchange Online a partir dos aplicativos executados no local, no Azure ou em outros serviços hospedados. O EWS permite que os administradores executem ações especializadas, como consultar o conteúdo de uma caixa de correio, postar um evento de calendário, criar uma tarefa ou disparar uma ação específica com base no conteúdo de uma mensagem de email. O Exchange Online habilita a funcionalidade EWS, concedendo permissões de aplicativo para as contas de clientes. Essas permissões permitem que o aplicativo de cliente acesse a caixa de correio do aplicativo e adicione conteúdo. A Representação do Exchange é um método usado para conceder permissões de aplicativo. Para obter mais detalhes sobre como usar os Serviços Web do Exchange com o Exchange Online, consulte os artigos técnicos no Centro de Desenvolvimento do Exchange Online.
  
### <a name="smtp-relay"></a>Retransmissão SMTP

O Exchange Online pode ser usado como um serviço de entrega SMTP, para retransmitir as mensagens de email enviadas de gateways de fax, dispositivos de rede e aplicativos personalizados. Por exemplo, se um aplicativo de linha de negócios envia alertas de email para usuários, ele pode ser configurado para usar o Exchange Online como o sistema de entrega de email. O aplicativo ou serviço deve ser autenticado com o nome de usuário e senha de uma caixa de correio válida e licenciada do Exchange Online, e conectar-se usando o protocolo TLS (Transport Layer Security).
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos entre planos, opções autônomas e soluções locais, consulte [Exchange Online descrição do serviço.](exchange-online-service-description.md)
