---
title: Interoperabilidade, conectividade e compatibilidade
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-interoperability-connectivity-compatibility
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cdfe686d-a059-4f4d-bb8d-9c2c0ebfa423
ms.openlocfilehash: 5308770ff7fc6ab6c44f27293ff89ebbffa6e72f
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132745"
---
# <a name="interoperability-connectivity-and-compatibility"></a>Interoperabilidade, conectividade e compatibilidade

## <a name="interoperability-with-other-microsoft-products"></a>Interoperabilidade com outros produtos da Microsoft

### <a name="skype-for-business-online"></a>Skype for Business Online

Para clientes que implantaram o Microsoft Lync Server 2010, o Lync Server 2013 ou o Microsoft Office Communications Server 2007 R2 localmente, o Microsoft Office Communicator poderá se conectar ao Microsoft Exchange Online usando os Serviços Web do Exchange para acessar dados de calendário e mensagens de ausência temporária.
  
O Lync Server 2010 e o Lync Server 2013 locais poderão interoperar com o Exchange Online de duas maneiras adicionais:
  
- Interoperabilidade de IM e presença no Outlook na Web
    
- Interoperabilidade de caixa postal
    
For more information about how to configure Skype for Business Server 2015 with Exchange Online, see [Configuring On-premises Skype for Business Server 2015 Integration with Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804). For hybrid configurations, see [Supported Skype for Business Server 2015 hybrid configurations](https://go.microsoft.com/fwlink/?LinkID=513084).
  
### <a name="microsoft-sharepoint"></a>Microsoft SharePoint

Para clientes que implantaram o Microsoft SharePoint Server ou o SharePoint Online como parte de um plano de assinatura, o SharePoint pode se conectar ao Exchange Online para serviços integrados.
  
Para saber mais sobre conectar o SharePoint ao Exchange Online, confira [Utilizar o SharePoint Online em um domínio personalizado junto com outros serviços](https://go.microsoft.com/fwlink/?LinkId=271805).
  
## <a name="features-for-external-connectivity"></a>Recursos para conectividade externa

O Exchange Online oferece os seguintes recursos para a conexão com aplicativos e dispositivos externos:
  
- **Through messaging protocols such as MAPI over HTTP, SMTP, POP3, IMAP4, or Exchange Web Services** External applications that are running on-premises, in Azure, or in other hosted services can access data stored with Exchange Online by using messaging protocols such as MAPI over HTTP, SMTP, POP3, and IMAPv4. Exchange Web Services or the Exchange Web Services Managed API is recommended for application development. 
    
- **Como uma retransmissão SMTP** O Exchange Online pode ser configurado como um serviço de entrega SMTP para retransmitir mensagens de email enviadas por gateways de fax, dispositivos de rede e aplicativos personalizados. 
    
### <a name="exchange-web-services"></a>Serviços Web do Exchange

Serviços Web Exchange (EWS) são o API de desenvolvimento preferencial para o Exchange Server e o Exchange Online. Usando o EWS ou a API gerenciada do EWS, os administradores podem acessar os dados armazenados com o Exchange Online a partir dos aplicativos executados no local, no Azure ou em outros serviços hospedados. O EWS permite que os administradores realizem ações especializadas, como consultar o conteúdo de uma caixa de correio, postar um evento de calendário, criar uma tarefa ou acionar uma ação específica com base no conteúdo de uma mensagem de email. O Exchange Online habilita a funcionalidade EWS, concedendo permissões de aplicativo para as contas de clientes. Essas permissões permitem que o aplicativo de cliente acesse a caixa de correio do aplicativo e adicione conteúdo. A Representação do Exchange é um método usado para conceder permissões de aplicativo. Para obter mais detalhes sobre como usar os Serviços Web do Exchange com o Exchange Online, consulte os artigos técnicos no Centro de Desenvolvimento do Exchange Online.
  
### <a name="smtp-relay"></a>Retransmissão SMTP

Exchange Online can be used as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications. For example, if a line-of-business application sends email alerts to users, it can be configured to use Exchange Online as the mail delivery system. The application or service must authenticate with the username and password of a valid, licensed Exchange Online mailbox, and connect by using Transport Layer Security (TLS).
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos nos planos, nas opções autônomas e nas soluções locais, consulte [Descrição do serviço do Exchange Online](exchange-online-service-description.md).
  

