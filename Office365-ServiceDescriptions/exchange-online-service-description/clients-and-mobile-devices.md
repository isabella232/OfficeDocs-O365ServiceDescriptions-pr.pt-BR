---
title: Clientes e dispositivos móveis
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
ms.openlocfilehash: ad19845f7a06cfb01a74507fdb794813091c1c2b
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24034903"
---
# <a name="clients-and-mobile-devices"></a>Clientes e dispositivos móveis

## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook é um programa de email que inclui o suporte para o calendário, contatos, tarefas e os seguintes recursos principais:
  
- **MAPI sobre HTTP** Messaging Application programa Interface (MAPI) sobre HTTP permite que os usuários do Outlook para se conectarem a caixas de correio Exchange Online pela Internet de fora do firewall da sua organização. MAPI sobre HTTP, a substituição de longo prazo do Outlook em qualquer lugar. Este método de conectividade oferece resiliência de conexão aprimorada, entrar mais seguro, extensibilidade, bem como melhorias para IT e suporte. Para saber mais, consulte [RPC sobre HTTP atinge o fim do suporte no Office 365](https://go.microsoft.com/fwlink/?linkid=863890) e [MAPI sobre HTTP](https://go.microsoft.com/fwlink/?linkid=393041).
    
- **Descoberta Automática** O recurso do serviço da Descoberta Automática configura automaticamente o Outlook para trabalhar com o Exchange Online. Os usuários do Outlook podem receber suas configurações de perfil necessárias diretamente do Exchange Online na primeira vez em que eles entrarem com seu endereço de email e senha. Essas configurações atualizam automaticamente o cliente Outlook com as informações necessárias, para a criação e manutenção do perfil do usuário. É necessário um certificado SSL para usar o serviço de Descoberta Automática. Esse certificado SSL é limitado a um domínio primário de SSL único. 
    
- **Modo em Cache do Exchange** O recurso Modo em Cache do Exchange permite que os usuários do Outlook acessem cópias locais de suas caixas de correio do Exchange Online quando não estiverem conectados à internet. O Modo em Cache do Exchange mantém uma cópia do lado do cliente da caixa de correio do Exchange dos usuários no Outlook e sincroniza essa cópia automaticamente com o servidor de email. É recomendado o uso do Outlook no Modo em Cache do Exchange, porque ele disponibiliza acesso offline e ajuda a fornecer uma experiência do usuário com capacidade de resposta, mesmo que as condições de rede entre o cliente e o servidor não sejam ideais. 
    
Por padrão, o acesso ao Outlook é habilitado para todos os usuários. Os administradores podem desabilitar o acesso para usuários específicos ou grupos através do Windows PowerShell. É recomendado o uso da última versão do Outlook  com o último service pack instalado  para acessar o Exchange Online. 
  
Para saber mais sobre quais clientes do Outlook são compatíveis com o Exchange 2016 e o Exchange Online, confira "Clientes com suporte" em [Requisitos de sistema do Exchange 2016](https://go.microsoft.com/fwlink/?LinkID=828972).
  
> [!IMPORTANT]
>  O Outlook não é fornecido como parte do preço de assinatura do Exchange Online. O Microsoft Office Pro Plus (que inclui o Microsoft Outlook) foi incluído em alguns dos planos do Office 365 e pode ser adquirido como uma assinatura separada. >  Se usar POP para se conectar a uma conta de email Exchange Online, você verá as seguintes limitações: >  Nenhuma informação de calendário >  Nenhuma informação de disponibilidade >  Nenhuma Lista de Endereços Global >  Nenhum email por push >  Ao conectar-se por POP, todas as mensagens serão baixadas para o cliente e não haverá sincronização entre vários computadores ou dispositivos (como laptops e telefones). 
  
## <a name="outlook-on-the-web"></a>Outlook na Web

O Outlook na Web App é uma versão baseada na Web do programa de email do Outlook usado com o Exchange Online. Ele permite que os usuários acessem email, calendário e contatos por um navegador da Web, de qualquer lugar em que estiverem conectados à Internet. Para saber mais sobre os navegadores com suporte, confira [Navegadores com suporte para o Outlook na Web para empresas](https://go.microsoft.com/fwlink/p/?LinkId=287032).
  
O Outlook na Web vem com duas versões para clientes, ambas podem ser usadas com o Exchange Online:
  
- **Outlook na Web** A versão padrão do Outlook na Web fornece aos usuários do Exchange Online uma experiência com mensagens semelhante à dos usuários do Outlook. Ela dá suporte aos mais navegadores da Web mais recentes e é otimizada para o uso em tablets e smartphones, assim como em desktops e laptops. Os usuários podem ler e enviar mensagens, organizar contatos e agendar compromissos e reuniões. O tempo limite padrão com base na atividade é de seis horas, mas pode ser [configurado por um administrador no Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) de 5 minutos a 8 horas. Este tempo limite depende das interações do usuário dentro do aplicativo Web, como clicar em um botão ou selecionar uma mensagem. Há também um tempo limite separado controlado pela segurança, que não é configurável e não depende da atividade do usuário para ocorrer. Se um usuário estiver conectado por 8 horas, o OWA desconectará automaticamente o usuário e exigirá uma nova autenticação. 
    
- **Versão light do Outlook na Web** A versão light do Outlook na Web fornece aos usuários do Exchange Online acesso à caixa de correio, usando quase nenhum navegador da web. Os usuários podem ler e enviar mensagens, organizar contatos e agendar compromissos e reuniões. O tempo limite padrão com base na atividade é de seis horas, mas pode ser [configurado por um administrador no Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) de 5 minutos a 8 horas. Este tempo limite depende das interações do usuário dentro do aplicativo Web, como clicar em um botão ou selecionar uma mensagem. Há também um tempo limite separado controlado pela segurança, que não é configurável e não depende da atividade do usuário para ocorrer. Se um usuário estiver conectado por 8 horas, a versão light do OWA desconectará o usuário automaticamente e exigirá uma nova autenticação. 
    
O Outlook na Web também está disponível em versões para celular. Para saber mais, confira [esta página](http://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409).
  
## <a name="outlook-for-mac"></a>Outlook para Mac

O Exchange Online suporta o Microsoft Outlook para Mac, que oferece email, calendário, catálogo de endereços, uma lista de tarefas e uma lista de observação.
  
## <a name="outlook-for-ios-android-and-windows-phone"></a>Outlook para iOS, Android e Windows Phone

O Exchange Online funciona com aplicativos do Outlook disponíveis para o iOS, Android e Windows Phone. Em qualquer um desses dispositivos, use o app store para encontrar o aplicativo do Outlook. Aqui está uma divisão pelo sistema operacional móvel.
  
|||||
|:-----|:-----|:-----|:-----|
|Dispositivo  <br/> |Android  <br/> |iOS  <br/> |Windows Phone  <br/> |
|Disponibilidade de aplicativos móveis do Outlook  <br/> |Sim  <br/> [Obtenha o Outlook para Android](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |Sim  <br/> [Obtenha o Outlook para iOS](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |Integração  <br/> |
|Eletrônico interno aplicativos compatíveis com o Exchange Online  <br/> |Aplicativo de Email do Gmail app/Samsung  <br/> |aplicativo de email iOS  <br/> |Email, calendário, contatos do Outlook  <br/> |
|Mais informações  <br/> |[Instalação móvel Android](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[instalação iPhone ou iPad](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[Instalação do Windows Phone](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |
   
Também há opções para usar o Exchange Online com dispositivos, incluindo Blackberry.
  
### <a name="feature-availability"></a>Disponibilidade de recursos

O Outlook oferece aos usuários para o fast email e calendário experiência intuitiva que eles esperam de um aplicativo móvel moderno, enquanto estiver sendo o aplicativo somente para oferecer suporte aos melhores recursos do Office 365. É o aplicativo de email único projetado especificamente para suportar a experiência completa do Office 365, dando aos usuários uma experiência coerente na área de trabalho para celular. Outlook é integrado com Intune, mobilidade empresarial e segurança e controles do Exchange para manter os dados e os usuários seguros.
  
Outlook permite que os usuários:
  
- Gerencie seu dia inteiro a partir de um dispositivo móvel.
    
- Conecte-se para os aplicativos e serviços que eles precisam para serem produtivos, enquanto mantém seus trabalhos e informações pessoais separadas e seguras.
    
Com o Outlook para iOS, Outlook para Android, ou o Outlook para Windows Phone, os usuários podem: 
  
- Se beneficiam de uma caixa de entrada focada esse email importantes de prioridades
    
- Personalizar gestos passe o dedo para coincidir com seus hábitos de email exclusivo
    
- Criar roteiros de viagens que podem ser adicionados diretamente para o calendário, com as principais informações disponíveis em um relance
    
- RSVP para reuniões da caixa de entrada.
    
- Usar ícones intuitivas no email e compromissos do calendário que os ajudem processam informações rapidamente
    
- Usar uma experiência familiar e consistente do Outlook em todos os dispositivos
    
- Facilmente iniciar e participar de reuniões do Skype do calendário
    
- Ler e responder ao IRM criptografadas e protegidas emails
    
- Compartilhar arquivos armazenados no OneDrive for Business
    
- Definir as respostas automáticas com um toque
    
- Exibir e gerenciar calendários compartilhados e delegados
    
- Pesquisar lista de endereços global da empresa com alguns toques
    
- Exibir disponibilidade do colega de trabalho e agendar um horário de reunião que funciona para todos
    
- Consulte convidados aceitar, provisório e recusar o status
    
- Compartilhar calendários direita de seus telefones
    
- Iniciar e ingressar Skype direita de reuniões a partir de um calendário
    
- Trabalho de acesso e calendários pessoais em um único local, sem trocar de aplicativos
    
## <a name="exchange-activesync"></a>Exchange ActiveSync

O Exchange Online suporta o protocolo do Microsoft Exchange ActiveSync, que sincroniza os dados da caixa de correio entre dispositivos móveis e o Exchange Online, para que os usuários possam acessar seu email, calendário, contatos e tarefas, de onde estiverem.
  
Uma ampla gama de dispositivos móveis funcionam com o Exchange ActiveSync, incluindo Microsoft Windows Phone, Apple iPhone e iPad e Android telefones e tablets. Além dos telefones e dispositivos móveis, o aplicativo de email no Windows Phone usa o Exchange ActiveSync para se conectar ao Exchange Online. Uma lista completa de licenciados do Exchange ActiveSync atuais está disponível no site de licenciamento do Exchange ActiveSync.
  
Para obter mais informações sobre o Exchange ActiveSync, consulte [Exchange ActiveSync](https://go.microsoft.com/fwlink/p/?LinkId=271792).
  
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

Email do Office 365 está disponível em dispositivos BlackBerry® por meio do Exchange ActiveSync. Para descobrir quais são as opções, consulte estes tópicos:
  
- [Configurar email em um dispositivo BlackBerry](https://go.microsoft.com/fwlink/?linkid=863394)
    
- [Configurar email em um dispositivo BlackBerry 7.1 SO e versões anteriores](https://go.microsoft.com/fwlink/?linkid=863403)
    
Para mais informações, consulte [BlackBerry](../office-365-platform-service-description/blackberry.md).
  
> [!NOTE]
> Se você estiver usando o Office 365 operado pela 21Vianet na China, o BlackBerry Business Cloud Services não estará disponível, mas será possível usar os dispositivos com o Exchange ActiveSync ou uma oferta da RIM (Research in Motion, a solução de email sem fio da BlackBerry) para executar o BES (Blackberry Enterprise Server). 
  
## <a name="feature-availability"></a>Disponibilidade do recurso

Para exibir a disponibilidade de recursos nos planos do Office 365 nas opções autônomas e nas soluções locais, consulte [Descrição de Serviço do Exchange Online](exchange-online-service-description.md).
  

