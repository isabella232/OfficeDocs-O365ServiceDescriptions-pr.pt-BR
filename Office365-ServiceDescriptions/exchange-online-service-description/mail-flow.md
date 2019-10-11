---
title: Fluxo de e-mails
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-mail-flow
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 8e5267e6-d224-485b-a081-c71a1fd0c4c3
description: Para a maioria das organizações que usam o Office 365, hospedamos suas caixas de correio e cuidamos do fluxo de emails. É a configuração mais simples e significa que o Office 365 gerencia todas as caixas de correio e filtros. Entretanto, algumas organizações precisam de configurações de fluxo de emails mais complexas para garantir que eles atendam às necessidades regulamentares ou de negócios específicas. Saiba mais sobre essas opções aqui.
ms.openlocfilehash: bf16ff4034333a2bd85ba798e9c02c621b4d7cfc
ms.sourcegitcommit: 3d180fb603896239b30d9db6ba865843c29801b0
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/10/2019
ms.locfileid: "37442596"
---
# <a name="mail-flow"></a>Fluxo de e-mails

Para a maioria das organizações que usam o Office 365, hospedamos suas caixas de correio e cuidamos do fluxo de emails. É a configuração mais simples e significa que o Office 365 gerencia todas as caixas de correio e filtros. Entretanto, algumas organizações precisam de configurações de fluxo de emails mais complexas para garantir que eles atendam às necessidades regulamentares ou de negócios específicas. Saiba mais sobre essas opções aqui. 
  
## <a name="custom-routing-of-outbound-email"></a>Roteamento personalizado de email de saída

O Microsoft Exchange Online pode rotear os emails que estão saindo da sua organização por meio de um servidor local ou um serviço hospedado (às vezes chamado de "host inteligente"). Isso permite que a organização use dispositivos de DLP (prevenção contra perda de dados), realize pós-processamento personalizado do email de saída e entregue o email a parceiros de negócios por meio de redes privadas. O Exchange Online também dá suporte à Regravação de Endereço, que encaminha emails de saída por meio de um gateway local que modifica os endereços. Esse recurso permite que você oculte subdomínios, faça o email de uma organização com vários domínios parecer um único domínio ou faça email retransmitido por parceiros parecer como se fosse enviado de dentro da sua organização. Os administradores configuram o roteamento do email personalizado dentro do EAC (Centro de Administração do Exchange).
  
Saiba mais em [Set up connectors to route mail between Office 365 and your own email servers](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail).
  
> [!IMPORTANT]
> O Exchange Online entrega emails fluindo para dentro ou para fora da organização. Se o domínio do destinatário estiver hospedado no Exchange Online com registros MX do DNS apontando para a proteção do Exchange Online, o fluxo de emails do seu locatário para o destinatário não viajará pela Internet.
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Secure messaging with a trusted partner

Como cliente do Exchange Online, você configura um fluxo de emails seguro com um parceiro de confiança usando os conectores do Office 365. O Office 365 dá suporte à comunicação segura por meio de TLS (Transport Layer Security), e você cria um conector para impor criptografia por meio de TLS. O [TLS](https://docs.microsoft.com/office365/securitycompliance/exchange-online-uses-tls-to-secure-email-connections) é um protocolo criptográfico que oferece segurança para comunicações pela Internet. Usando conectores, você configura o TLS forçado tanto de entrada quanto de saída usando certificados autoassinados ou certificados validados pela AC (autoridade de certificação). Você também aplica outras restrições de segurança, como especificar nomes de domínio ou intervalos de endereços IP, dos quais a organização parceira envia emails. 
  
Saiba mais em [Set up connectors for secure mail flow with a partner organization](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).
  
> [!IMPORTANT]
> Pode ser necessário um certificado validado por CA. 
  
## <a name="conditional-mail-routing"></a>Roteamento de email condicional

É possível enviar mala direta para sites específicos usando conectores e regras de transporte. Com o roteamento baseado em critérios, você escolhe um conector com base em condições específicas.
  
Saiba mais em [Scenario: Conditional mail routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).
  
## <a name="incoming-mail-safe-list"></a>Lista segura de emails de entrada

É possível adicionar o endereço IP de um parceiro confiável a uma lista segura para garantir que as mensagens enviadas pelos parceiros não fiquem sujeitas ao filtro antispam. Para isso, você usa a lista Permitir IP do filtro de conexão.
  
Saiba mais em [Configure the connection filter policy](https://docs.microsoft.com/office365/SecurityCompliance/configure-the-connection-filter-policy).
  
## <a name="hybrid-email-routing"></a>Roteamento de email híbrido

Uma implantação híbrida oferece às organizações a capacidade de levar a experiência e o controle administrativo cheio de recursos que elas possuem em suas organizações locais do Microsoft Exchange para a nuvem. O transporte híbrido faz com que as mensagens que trafegam entre destinatários das organizações sejam autenticadas, criptografadas e transferidas usando TLS (Transport Layer Security) e apareçam como "internas" para componentes do Exchange, como regras de transporte, registro no diário e diretivas antispam. Configure o transporte híbrido usando o Assistente de Configuração Híbrida no Exchange Server.
  
Para saber mais sobre o roteamento de emails em uma implantação híbrida, confira [Roteamento de Transporte em Implantações Híbridas do Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271757).
  
O [Assistente de Implantação do Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036) também oferece um provisionamento de implantação híbrida e um guia de transporte de mensagens híbrido. 
  
### <a name="shared-address-space-with-on-premises-routing-control-mx-points-to-on-premises"></a>Espaço de endereço compartilhado com controle de roteamento local (MX aponta para local)

Espaço de endereçamento compartilhado com controle de roteamento local (os pontos MX para local) é um cenário de roteamento de email de implantação híbrida no qual suas caixas de correio são hospedadas parcialmente no Exchange Online e no fluxo de email de entrada e saída da Internet o é roteado através da organização do Exchange local. Esse cenário é também chamado de transporte de email centralizado. Neste cenário, o Exchange Online é provisionado com o EOP e o email de entrada da Internet é roteado para o seu servidor de email local antes de ser roteado para o EOP e finalmente para caixas de correio hospedadas no Exchange Online. Além disso, o email de saída das caixas de correio do Exchange Online é encaminhado por meio da organização do Exchange local para mensagens enviadas a destinatários externos. Com essa configuração, você usa um namespace de domínio SMTP único para todas as caixas de correio na organização do Exchange local e na sua organização do Exchange Online. 
  
Para saber mais sobre as opções de transporte em uma implantação híbrida, confira [Opções de Transporte em Implantações Híbridas do Exchange](https://go.microsoft.com/fwlink/p/?LinkID=271758).
  
### <a name="shared-address-space-without-on-premises-routing-control-mx-points-to-eop"></a>Espaço de endereço compartilhado sem controle de roteamento local (MX aponta para EOP)

Espaço de Endereço Compartilhado sem Controle de Roteamento Local (o MX aponta para o EOP) é um cenário de roteamento de email híbrido no qual suas caixas de correio são hospedadas parcialmente na nuvem usando o Exchange Online e parcialmente o Exchange local, e seu registro MX aponta para o EOP. Esse cenário é apropriado quando você usa o serviço do Office 365 para hospedar algumas das caixas de correio da organização e deseja que EOP proteja as caixas de correio locais e na nuvem. Neste cenário, o email enviado aos destinatários na organização é inicialmente encaminhado por meio do EOP, em que a filtragem de spam e de política ocorre, antes de chegar às caixas de correio locais e na nuvem. 
  
Para saber mais sobre as opções de transporte em uma implantação híbrida, confira [Opções de Transporte em Implantações Híbridas do Exchange](https://go.microsoft.com/fwlink/p/?LinkID=271758).
  
### <a name="troubleshooting-a-deployment-with-the-hybrid-configuration-wizard"></a>Solucionando problemas de uma implantação com o Assistente de Configuração Híbrida

Usar o Assistente de Configuração Híbrida para configurar uma implantação híbrida no Microsoft Exchange Server reduz bastante o potencial de que a implantação híbrida enfrente problemas. Entretanto, existem algumas áreas típicas fora do escopo do Assistente de Configuração Híbrida que, se configuradas incorretamente, podem representar problemas em uma implantação híbrida. Entre elas estão a configuração correta do servidor de Acesso para Cliente e a instalação e a configuração adequadas do certificado.
  
Saiba mais sobre a solução de problemas de uma implantação com o Assistente de Configuração Híbrida em [Solucionar problemas de implantação híbrida](https://go.microsoft.com/fwlink/p/?LinkId=271040).
  
### <a name="managing-a-hybrid-configuration"></a>Gerenciando uma configuração híbrida

Você pode modificar uma configuração híbrida existente alterando as configurações no Assistente de Configuração Híbrida. Os cenários incluem desabilitação de transporte centralizado ou desabilitação de transporte de email seguro.
  
Saiba mais sobre o gerenciamento de uma configuração de implantação híbrida em [Gerenciar uma Implantação Híbrida](https://go.microsoft.com/fwlink/p/?LinkId=271044).
  
### <a name="hybrid-deployment-requirements"></a>Requisitos de implantação híbrida

Saiba mais sobre os requisitos de implantação híbrida em [Pré-requisitos da implantação híbrida](https://go.microsoft.com/fwlink/p/?LinkId=271759).
  
> [!IMPORTANT]
> Em algumas configurações híbrida, pode ser preciso adquirir as licenças da Proteção do Exchange Online para as suas caixas de correio local. 
  
## <a name="feature-availability"></a>Disponibilidade do recurso

Confira a disponibilidade de recursos nos planos do Office 365, nas opções autônomas e nas soluções locais em [Descrição de Serviço do Exchange Online](exchange-online-service-description.md).
  