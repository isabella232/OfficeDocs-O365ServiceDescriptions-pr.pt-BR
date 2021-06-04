---
title: Clientes e dispositivos móveis
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
description: Exchange Online funciona com versões desktop e móveis de Outlook, bem como Outlook na Web.
ms.openlocfilehash: 3aa0c2bbdf9b55b6a3544919143fd9d5e5cfed24
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653113"
---
# <a name="clients-and-mobile-devices"></a>Clientes e dispositivos móveis

## <a name="microsoft-outlook"></a>Microsoft Outlook

O Microsoft Outlook é um programa de email que inclui suporte para calendário, contatos, tarefas e os seguintes recursos principais:
  
- **MAPI sobre HTTP** - Interface do Programa de Aplicativo de Mensagens (MAPI) sobre HTTP permite que Outlook usuários se conectem Exchange Online caixas de correio pela Internet de fora do firewall da organização. MAPI sobre HTTP, a substituição de longo prazo para Outlook Em Qualquer Lugar. Esse método de conectividade oferece uma resiliência de conexão aprimorada, uma conexão mais segura, extensibilidade, bem como aprimoramentos para a ÁREA de TRABALHO e suporte. Para saber mais, confira [RPC sobre HTTP atinge o fim](/exchange/troubleshoot/administration/rpc-over-http-end-of-support) do suporte em Office 365 e [MAPI sobre HTTP](/exchange/mapi-over-http-exchange-2013-help).

- **Descoberta Automática** - O recurso de serviço de Descoberta Automática configura automaticamente Outlook para trabalhar com Exchange Online. Os usuários do Outlook podem receber suas configurações de perfil necessárias diretamente do Exchange Online na primeira vez em que eles entrarem com seu endereço de email e senha. Essas configurações atualizam automaticamente o cliente Outlook com as informações necessárias, para a criação e manutenção do perfil do usuário. É necessário um certificado SSL para usar o serviço de Descoberta Automática. Esse certificado SSL é limitado a um domínio primário de SSL único. 

- **Modo Exchange** cache - O recurso Modo de Exchange cache permite que os usuários Outlook acessem cópias locais de suas caixas de correio Exchange Online quando não estão conectados à Internet. O Modo em Cache do Exchange mantém uma cópia do lado do cliente da caixa de correio do Exchange dos usuários no Outlook e sincroniza essa cópia automaticamente com o servidor de email. É recomendado o uso do Outlook no Modo em Cache do Exchange, porque ele disponibiliza acesso offline e ajuda a fornecer uma experiência do usuário com capacidade de resposta, mesmo que as condições de rede entre o cliente e o servidor não sejam ideais. 

Por padrão, o acesso ao Outlook é habilitado para todos os usuários. Os administradores podem desabilitar o acesso para usuários específicos ou grupos através do Windows PowerShell. É recomendado o uso da última versão do Outlook — com o último service pack instalado — para acessar o Exchange Online. 
  
Para obter informações sobre Outlook clientes com suporte do Exchange 2016 e Exchange Online, consulte [System Requirements for Office](https://products.office.com/office-system-requirements). 

Microsoft 365 foi projetado para trabalhar com os navegadores e versões mais recentes do Office. Se você usar navegadores mais antigos e versões de Office que não estão no suporte principal:

- A Microsoft não o impedirá deliberadamente de se conectar ao serviço, mas a qualidade da sua experiência pode diminuir com o tempo.
- A Microsoft não fornecerá atualizações de software para resolver problemas não relacionados à segurança.

> [!IMPORTANT]
> O Outlook não é fornecido como parte do preço de assinatura do Exchange Online. Microsoft 365 Apps para Grandes Empresas (que inclui o Microsoft Outlook) está incluído em alguns planos e pode ser comprado como uma assinatura separada. Se usar POP para se conectar a uma conta de email Exchange Online, você verá as seguintes limitações:
> - Nenhuma informação de calendário
>- Nenhuma informação de disponibilidade
>- Nenhuma Lista de Endereços Global
>- Nenhum email por push
>- Ao conectar-se por POP, todas as mensagens serão baixadas para o cliente e não haverá sincronização entre vários computadores ou dispositivos (como laptops e telefones). 
  
## <a name="outlook-on-the-web"></a>Outlook na Web

O Outlook na Web App é uma versão baseada na Web do programa de email do Outlook usado com o Exchange Online. Ele permite que os usuários acessem seus emails, calendários e contatos por meio de um navegador da Web de onde quer que se conectem à Internet. Para saber mais sobre os navegadores com suporte, confira [Navegadores com suporte para o Outlook na Web para empresas](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006).
  
O Outlook na Web vem com duas versões para clientes, ambas podem ser usadas com o Exchange Online:
  
- **Outlook na Web** - A versão padrão do Outlook na Web fornece Exchange Online usuários com uma experiência de mensagens mais semelhante à dos usuários Outlook. Ela dá suporte aos mais navegadores da Web mais recentes e é otimizada para o uso em tablets e smartphones, assim como em desktops e laptops. Os usuários podem ler e enviar mensagens, organizar contatos e agendar compromissos e reuniões. O tempo limite padrão com base na atividade é de seis horas, mas pode ser [configurado por um administrador no Windows PowerShell](/powershell/module/exchange/set-organizationconfig) de 5 minutos a 8 horas. Esse tempo de saída depende das interações do usuário no aplicativo Web, como selecionar um botão ou selecionar uma mensagem. Há também um tempo limite separado controlado pela segurança, que não é configurável e não depende da atividade do usuário para ocorrer. Se um usuário estiver conectado por 8 horas, o OWA desconectará automaticamente o usuário e exigirá uma nova autenticação. 

- **A versão** light do Outlook na Web - A versão light do Outlook na Web fornece aos usuários Exchange Online acesso à caixa de correio usando praticamente qualquer navegador da Web. Os usuários podem ler e enviar mensagens, organizar contatos e agendar compromissos e reuniões. O tempo limite padrão com base na atividade é de seis horas, mas pode ser [configurado por um administrador no Windows PowerShell](/powershell/module/exchange/set-organizationconfig) de 5 minutos a 8 horas. Esse tempo de saída depende das interações do usuário no aplicativo Web, como selecionar um botão ou selecionar uma mensagem. Há também um tempo limite separado controlado pela segurança, que não é configurável e não depende da atividade do usuário para ocorrer. Se um usuário estiver conectado por 8 horas, a versão light do OWA desconectará o usuário automaticamente e exigirá uma nova autenticação. 

O Outlook na Web também está disponível em versões para celular. Para saber mais, confira [esta página](https://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409).
  
## <a name="outlook-for-mac"></a>Outlook para Mac

Exchange Online suporta Microsoft Outlook para Mac, que fornece email, calendário, um livro de endereços, uma lista de tarefas e uma lista de anotações.
  
## <a name="outlook-for-ios-android-and-windows-phone"></a>Outlook para iOS, Android e Windows Phone

Exchange Online funciona com Outlook disponíveis para iOS, Android e Windows Phone. Em qualquer um desses dispositivos, use a loja de aplicativos para encontrar o Outlook app. Aqui está um detalhamento pelo sistema operacional móvel.<br><br>
  
| Dispositivo | Android | iOS | Windows Phone |
|:-----|:-----|:-----|:-----|
|Outlook de aplicativo móvel  <br/> |Sim  <br/> [Obter Outlook para Android](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |Sim  <br/> [Obter Outlook para iOS](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |Integrado  <br/> |
|Aplicativos de email integrados compatíveis com Exchange Online  <br/> |Aplicativo do Gmail/aplicativo de Email da Samsung  <br/> |Aplicativo de email do iOS  <br/> |Outlook Email, calendário, contatos  <br/> |
|Mais informações  <br/> |[Instalação móvel do Android](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[iPhone ou iPad configuração](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[Windows Phone configuração](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |

Também há opções para usar Exchange Online com dispositivos, incluindo Blackberry.
  
### <a name="feature-availability"></a>Disponibilidade de recursos

Outlook oferece aos usuários a experiência rápida e intuitiva de email e calendário que eles esperam de um aplicativo móvel moderno, sendo o único aplicativo a oferecer suporte para os melhores recursos. É o único aplicativo de email projetado especificamente para dar suporte à experiência completa da Microsoft, dando aos usuários uma experiência coerente da área de trabalho para o celular. Outlook é integrado ao Intune, mobilidade empresarial e segurança e controles Exchange para manter dados e usuários seguros.
  
Com Outlook, os usuários podem:
  
- Gerencie seu dia inteiro a partir de um dispositivo móvel.

- Conexão para os aplicativos e serviços que precisam ser produtivos, mantendo suas informações pessoais e de trabalho separadas e seguras.

Com Outlook para iOS, Outlook para Android ou Outlook para Windows Phone, os usuários podem: 
  
- Beneficiar de uma caixa de entrada focada que prioriza emails importantes

- Personalizar gestos de passar o dedo para corresponder aos seus hábitos de email exclusivos

- Criar itinerários de viagem que podem ser adicionados diretamente ao calendário, com informações importantes disponíveis rapidamente

- RSVP para reuniões da caixa de entrada.

- Usar ícones intuitivos em compromissos de email e calendário que os ajudam a processar informações rapidamente

- Use uma experiência consistente e Outlook em todos os dispositivos

- Iniciar e participar facilmente Skype reuniões do calendário

- Ler e responder a emails criptografados e protegidos por IRM

- Compartilhar arquivos armazenados em OneDrive for Business

- Definir Respostas Automáticas com um toque

- Exibir e gerenciar calendários compartilhados e delegados

- Pesquisar a lista de endereços global da empresa com alguns toques

- Exibir a disponibilidade do colega de trabalho e agendar um horário de reunião que funcione para todos

- Consulte o status de aceitação, tentativa e recusa de convites

- Compartilhar calendários direto de seus telefones

- Iniciar e participar Skype reuniões de um calendário

- Acessar calendários pessoais e de trabalho em um só lugar, sem alternar aplicativos
    
## <a name="exchange-activesync"></a>Exchange ActiveSync

O Exchange Online suporta o protocolo do Microsoft Exchange ActiveSync, que sincroniza os dados da caixa de correio entre dispositivos móveis e o Exchange Online, para que os usuários possam acessar seu email, calendário, contatos e tarefas, de onde estiverem.
  
Uma ampla variedade de dispositivos móveis funcionam com o Exchange ActiveSync, incluindo o Microsoft Windows Phone, iPhone e iPad da Apple e telefones e tablets Android. Além de telefones e dispositivos móveis, o aplicativo mail em Windows Phone usa Exchange ActiveSync para se conectar a Exchange Online. Uma lista completa das licenças atuais do Exchange ActiveSync está disponível no site de licenciamento do Exchange ActiveSync.
  
Para obter mais informações sobre Exchange ActiveSync, [consulte Exchange ActiveSync](/exchange/clients-and-mobile-in-exchange-online/clients-and-mobile-in-exchange-online).
  
> [!IMPORTANT]
> O número máximo de dispositivos do Exchange ActiveSync por caixa de correio é de 100. 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a>Aplicativos desenvolvidos com os Serviços Web Exchange (EWS)

 Os aplicativos desenvolvidos usando o EWS (Serviços Web do Exchange) ou a API gerenciada do EWS permitem que os administradores acessem os dados armazenados com o Exchange Online a partir de aplicativos executados no local, no Azure ou em outros serviços hospedados. 
  
Para saber mais sobre os aplicativos que foram desenvolvidos usando os Serviços Web do Exchange, confira [Serviços Web no Exchange](/exchange/client-developer/exchange-web-services/explore-the-ews-managed-api-ews-and-web-services-in-exchange).
  
## <a name="pop-and-imap"></a>POP e IMAP

O Exchange Online suporta o acesso à caixa de correio tanto pelo protocolo POP3, como pelo protocolo IMAP4. O acesso POP e IMAP requer criptografia usando SSL. POP é habilitado por padrão para todos os usuários. Os usuários podem visualizar as configurações de conexão POP e IMAP no Outlook na Web. Os administradores podem desabilitar o acesso POP e IMAP baseado no usuário.
  
Para saber mais sobre conectividade de POP3 e de IMAP4, confira [POP3 e IMAP4](/exchange/pop3-and-imap4-in-exchange-server-2013-exchange-2013-help).
  
## <a name="smtp"></a>SMTP

O Protocolo SMTP é usado para enviar emails de saída para os clientes que se conectam ao Exchange Online por IMAP ou POP. É o protocolo primário para o roteamento e a entrega através do Exchange Server. O Exchange Online suporta dois tipos de serviços de retransmissão SMTP para os aplicativos de clientes internos autorizados que exigem envio de email SMTP:
  
- O Envio de mensagem SMTP para usuários dentro do ambiente gerenciado.

- Retransmissão de mensagem SMTP autenticada para endereços fora do ambiente gerenciado.

> [!IMPORTANT]
> Os endereços IP para servidores de origem autorizados são necessários para autorizar a retransmissão SMTP. A criptografia e autenticação do protocolo TLS são necessárias ao usar o SMTP para enviar emails. 
  
## <a name="blackberry-devices"></a>Dispositivos BlackBerry

O email está disponível em dispositivos BlackBerry &reg; por Exchange ActiveSync. Para descobrir quais são suas opções, consulte estes tópicos:
  
- [Configurar email em um dispositivo BlackBerry](https://go.microsoft.com/fwlink/?linkid=863394)

- [Configurar email em um sistema operacional BlackBerry 7.1 e anterior](https://go.microsoft.com/fwlink/?linkid=863403)

Para mais informações, consulte [BlackBerry](../office-365-platform-service-description/blackberry.md).
  
> [!NOTE]
> Se você estiver usando o Office 365 operado pela 21Vianet na China, o BlackBerry Business Cloud Services não estará disponível, mas será possível usar os dispositivos com o Exchange ActiveSync ou uma oferta da RIM (Research in Motion, a solução de email sem fio da BlackBerry) para executar o BES (Blackberry Enterprise Server). 
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos entre planos, opções autônomas e soluções locais, consulte [Exchange Online descrição do serviço.](exchange-online-service-description.md)
