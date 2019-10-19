---
title: Clientes e dispositivos móveis
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
ms.openlocfilehash: 0b5768720514572299814dd5ecd9c3a200f1958a
ms.sourcegitcommit: 19591e97b35c1b2a99e04a496d83af27dc6530d6
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/18/2019
ms.locfileid: "37581917"
---
# <a name="clients-and-mobile-devices"></a>Clientes e dispositivos móveis

## <a name="microsoft-outlook"></a>Microsoft Outlook

O Microsoft Outlook é um programa de email que inclui suporte para calendário, contatos, tarefas e os seguintes recursos principais:
  
- **MAPI sobre http** O MAPI (Messaging Application Program interface) sobre HTTP permite que os usuários do Outlook se conectem às caixas de correio do Exchange Online pela Internet de fora do firewall da sua organização. MAPI sobre HTTP, a substituição de longo prazo do Outlook em qualquer lugar. Este método de conectividade oferece maior resiliência de conexão, entrada mais segura, extensibilidade, além de aprimoramentos para ti e suporte. Para saber mais, veja [RPC sobre http atinge o fim do suporte no Office 365](https://go.microsoft.com/fwlink/?linkid=863890) e [MAPI sobre http](https://go.microsoft.com/fwlink/?linkid=393041).

- **Descoberta Automática** O recurso do serviço da Descoberta Automática configura automaticamente o Outlook para trabalhar com o Exchange Online. Os usuários do Outlook podem receber suas configurações de perfil necessárias diretamente do Exchange Online na primeira vez em que eles entrarem com seu endereço de email e senha. Essas configurações atualizam automaticamente o cliente Outlook com as informações necessárias, para a criação e manutenção do perfil do usuário. É necessário um certificado SSL para usar o serviço de Descoberta Automática. Esse certificado SSL é limitado a um domínio primário de SSL único. 

- **Modo cache do Exchange** O recurso de modo cache do Exchange permite que os usuários do Outlook acessem cópias locais de suas caixas de correio do Exchange Online quando não estão conectados à Internet. O Modo em Cache do Exchange mantém uma cópia do lado do cliente da caixa de correio do Exchange dos usuários no Outlook e sincroniza essa cópia automaticamente com o servidor de email. É recomendado o uso do Outlook no Modo em Cache do Exchange, porque ele disponibiliza acesso offline e ajuda a fornecer uma experiência do usuário com capacidade de resposta, mesmo que as condições de rede entre o cliente e o servidor não sejam ideais. 

Por padrão, o acesso ao Outlook é habilitado para todos os usuários. Os administradores podem desabilitar o acesso para usuários específicos ou grupos através do Windows PowerShell. É recomendado o uso da última versão do Outlook  com o último service pack instalado  para acessar o Exchange Online. 
  
Para saber mais sobre quais clientes do Outlook são compatíveis com o Exchange 2016 e o Exchange Online, confira "Clientes com suporte" em [Requisitos de sistema do Exchange 2016](https://go.microsoft.com/fwlink/?LinkID=828972).
  
> [!IMPORTANT]
>  O Outlook não é fornecido como parte do preço de assinatura do Exchange Online. O Microsoft Office Pro Plus (que inclui o Microsoft Outlook) foi incluído em alguns dos planos do Office 365 e pode ser adquirido como uma assinatura separada. Você verá as seguintes limitações se usar o POP para se conectar a uma conta de email do Exchange Online: > nenhuma informação de calendário > nenhuma informação de disponibilidade > nenhuma lista de endereços global > sem envio de email > ao se conectar por POP, todas as mensagens serão baixadas t o cliente e não haverá sincronização entre vários computadores ou dispositivos (como entre um laptop e um telefone). 
  
## <a name="outlook-on-the-web"></a>Outlook na Web

O Outlook na Web App é uma versão baseada na Web do programa de email do Outlook usado com o Exchange Online. Ele permite que os usuários acessem seus emails, calendários e contatos por meio de um navegador da Web de onde eles se conectam à Internet. Para saber mais sobre os navegadores com suporte, confira [Navegadores com suporte para o Outlook na Web para empresas](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006).
  
O Outlook na Web vem com duas versões para clientes, ambas podem ser usadas com o Exchange Online:
  
- **Outlook na Web** A versão padrão do Outlook na Web fornece aos usuários do Exchange Online uma experiência com mensagens semelhante à dos usuários do Outlook. Ela dá suporte aos mais navegadores da Web mais recentes e é otimizada para o uso em tablets e smartphones, assim como em desktops e laptops. Os usuários podem ler e enviar mensagens, organizar contatos e agendar compromissos e reuniões. O tempo limite padrão com base na atividade é de seis horas, mas pode ser [configurado por um administrador no Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) de 5 minutos a 8 horas. Esse tempo limite depende das interações do usuário no aplicativo Web, como a seleção de um botão ou a seleção de uma mensagem. Há também um tempo limite separado controlado pela segurança, que não é configurável e não depende da atividade do usuário para ocorrer. Se um usuário estiver conectado por 8 horas, o OWA desconectará automaticamente o usuário e exigirá uma nova autenticação. 

- **Versão light do Outlook na Web** A versão light do Outlook na Web fornece aos usuários do Exchange Online acesso à caixa de correio, usando quase nenhum navegador da web. Os usuários podem ler e enviar mensagens, organizar contatos e agendar compromissos e reuniões. O tempo limite padrão com base na atividade é de seis horas, mas pode ser [configurado por um administrador no Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) de 5 minutos a 8 horas. Esse tempo limite depende das interações do usuário no aplicativo Web, como a seleção de um botão ou a seleção de uma mensagem. Há também um tempo limite separado controlado pela segurança, que não é configurável e não depende da atividade do usuário para ocorrer. Se um usuário estiver conectado por 8 horas, a versão light do OWA desconectará o usuário automaticamente e exigirá uma nova autenticação. 

O Outlook na Web também está disponível em versões para celular. Para saber mais, confira [esta página](http://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409).
  
## <a name="outlook-for-mac"></a>Outlook para Mac

O Exchange Online suporta o Microsoft Outlook para Mac, que fornece email, calendário, catálogo de endereços, lista de tarefas e lista de anotações.
  
## <a name="outlook-for-ios-android-and-windows-phone"></a>Outlook para iOS, Android e Windows Phone

O Exchange Online funciona com aplicativos do Outlook disponíveis para iOS, Android e Windows Phone. Em qualquer um desses dispositivos, use a loja de aplicativos para localizar o aplicativo do Outlook. Aqui está uma divisão por um sistema operacional móvel.
  
|||||
|:-----|:-----|:-----|:-----|
|Dispositivo  <br/> |Android  <br/> |iOS  <br/> |Windows Phone  <br/> |
|Disponibilidade do aplicativo móvel do Outlook  <br/> |Sim  <br/> [Obter o Outlook para Android](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |Sim  <br/> [Obter o Outlook para iOS](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |Interno  <br/> |
|Aplicativos de email internos compatíveis com o Exchange Online  <br/> |Aplicativo de email do Gmail/Samsung  <br/> |aplicativo de email iOS  <br/> |Email, calendário, contatos do Outlook  <br/> |
|Mais informações  <br/> |[Configuração móvel do Android](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[configuração de iPhone ou iPad](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[Configuração do Windows Phone](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |

Há também opções para usar o Exchange Online com dispositivos, incluindo Blackberry.
  
### <a name="feature-availability"></a>Disponibilidade de recursos

O Outlook oferece aos usuários a experiência de email e de calendário rápida e intuitiva que eles esperam de um aplicativo móvel moderno, enquanto é o único aplicativo a oferecer suporte aos melhores recursos do Office 365. É o único aplicativo de email projetado especificamente para oferecer suporte à experiência completa do Office 365, oferecendo aos usuários uma experiência coerente de desktop para celular. O Outlook é integrado ao Intune, mobilidade corporativa e segurança e aos controles do Exchange para manter os dados e os usuários seguros.
  
Com o Outlook, os usuários podem:
  
- Gerenciar o dia inteiro de um dispositivo móvel.

- Conecte-se aos aplicativos e serviços que eles precisam para serem produtivos, ao mesmo tempo em que as informações pessoais e de trabalho estão separadas e protegidas.

Com o Outlook para iOS, Outlook para Android ou Outlook para Windows Phone, os usuários podem: 
  
- Benefício de uma caixa de entrada destaques que prioriza emails importantes

- Personalizar gestos de passar o dedo para corresponder aos seus hábitos de email exclusivos

- Criar itinerários de viagem que podem ser adicionados diretamente ao calendário, com informações importantes disponíveis rapidamente

- RSVP para reuniões da caixa de entrada.

- Use ícones intuitivos nos compromissos de email e calendário que os ajudam a processar rapidamente as informações

- Usar uma experiência consistente e familiar do Outlook em todos os dispositivos

- Iniciar e ingressar em reuniões do Skype com facilidade no calendário

- Ler e responder a emails criptografados e protegidos por IRM

- Compartilhar arquivos armazenados no OneDrive for Business

- Definir respostas automáticas com um toque

- Exibir e gerenciar calendários compartilhados e delegados

- Pesquisar a lista de endereços global de sua empresa com alguns toques

- Exibir a disponibilidade de um colaborador e agendar um horário de reunião que funcione para todos

- Confira o status aceitar, provisório e recusar

- Compartilhar calendários diretamente de seus telefones

- Iniciar e ingressar em reuniões do Skype diretamente de um calendário

- Acessar calendários pessoais e de trabalho em um só lugar, sem trocar aplicativos
    
## <a name="exchange-activesync"></a>Exchange ActiveSync

O Exchange Online suporta o protocolo do Microsoft Exchange ActiveSync, que sincroniza os dados da caixa de correio entre dispositivos móveis e o Exchange Online, para que os usuários possam acessar seu email, calendário, contatos e tarefas, de onde estiverem.
  
Uma ampla variedade de dispositivos móveis funcionam com o Exchange ActiveSync, incluindo o Microsoft Windows Phone, iPhone e iPad da Apple e telefones e tablets Android. Além de telefones celulares e dispositivos, o aplicativo de email no Windows Phone usa o Exchange ActiveSync para se conectar ao Exchange Online. Uma lista completa das licenças atuais do Exchange ActiveSync está disponível no site de licenciamento do Exchange ActiveSync.
  
Para obter mais informações sobre o Exchange ActiveSync, confira [Exchange ActiveSync](https://go.microsoft.com/fwlink/p/?LinkId=271792).
  
> [!IMPORTANT]
> O número máximo de dispositivos do Exchange ActiveSync por caixa de correio é de 100. 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a>Aplicativos desenvolvidos com os Serviços Web Exchange (EWS)

 Os aplicativos desenvolvidos usando o EWS (Serviços Web do Exchange) ou a API gerenciada do EWS permitem que os administradores acessem os dados armazenados com o Exchange Online a partir de aplicativos executados no local, no Azure ou em outros serviços hospedados. 
  
Para saber mais sobre os aplicativos que foram desenvolvidos usando os Serviços Web do Exchange, confira [Serviços Web no Exchange](https://go.microsoft.com/fwlink/?LinkId=325346).
  
## <a name="pop-and-imap"></a>POP e IMAP

O Exchange Online suporta o acesso à caixa de correio tanto pelo protocolo POP3, como pelo protocolo IMAP4. O acesso POP e IMAP requer criptografia usando SSL. POP é habilitado por padrão para todos os usuários. Os usuários podem visualizar as configurações de conexão POP e IMAP no Outlook na Web. Os administradores podem desabilitar o acesso POP e IMAP baseado no usuário.
  
Para saber mais sobre conectividade de POP3 e de IMAP4, confira [POP3 e IMAP4](https://go.microsoft.com/fwlink/p/?LinkId=272070).
  
## <a name="smtp"></a>SMTP

O Protocolo SMTP é usado para enviar emails de saída para os clientes que se conectam ao Exchange Online por IMAP ou POP. É o protocolo primário para o roteamento e a entrega através do Exchange Server. O Exchange Online suporta dois tipos de serviços de retransmissão SMTP para os aplicativos de clientes internos autorizados que exigem envio de email SMTP:
  
- O Envio de mensagem SMTP para usuários dentro do ambiente gerenciado.

- Retransmissão de mensagem SMTP autenticada para endereços fora do ambiente gerenciado.

> [!IMPORTANT]
> Os endereços IP para servidores de origem autorizados são necessários para autorizar a retransmissão SMTP. A criptografia e autenticação do protocolo TLS são necessárias ao usar o SMTP para enviar emails. 
  
## <a name="blackberry-devices"></a>Dispositivos BlackBerry®

O email do Office 365 está disponível nos dispositivos BlackBerry® por meio do Exchange ActiveSync. Para saber quais são as suas opções, consulte estes tópicos:
  
- [Configurar o email em um dispositivo BlackBerry](https://go.microsoft.com/fwlink/?linkid=863394)

- [Configurar o email em um dispositivo BlackBerry 7,1 so e anterior](https://go.microsoft.com/fwlink/?linkid=863403)

Para mais informações, consulte [BlackBerry](../office-365-platform-service-description/blackberry.md).
  
> [!NOTE]
> Se você estiver usando o Office 365 operado pela 21Vianet na China, o BlackBerry Business Cloud Services não estará disponível, mas será possível usar os dispositivos com o Exchange ActiveSync ou uma oferta da RIM (Research in Motion, a solução de email sem fio da BlackBerry) para executar o BES (Blackberry Enterprise Server). 
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos nos planos do Office 365, nas opções autônomas e nas soluções locais, consulte [Descrição do serviço do Exchange Online](exchange-online-service-description.md).
  