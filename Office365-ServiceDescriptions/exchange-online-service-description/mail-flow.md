---
title: Fluxo de mensagens
ms.author: office365servicedesc
author: pamelaar
manager: gailw
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
description: Para a maioria das organizações, hospedamos suas caixas de correio e cuidamos do fluxo de emails. É a configuração mais simples e significa que a Microsoft gerencia todas as caixas de correio e filtragem. Entretanto, algumas organizações precisam de configurações de fluxo de emails mais complexas para garantir que eles atendam às necessidades regulamentares ou de negócios específicas. Saiba mais sobre essas opções aqui.
ms.openlocfilehash: 0fe7cf2f0e8619bce911457ba634bee41ee4e113
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653323"
---
# <a name="mail-flow"></a>Fluxo de mensagens

Para a maioria das organizações, hospedamos suas caixas de correio e cuidamos do fluxo de emails. É a configuração mais simples e significa que a Microsoft gerencia todas as caixas de correio e filtragem. Entretanto, algumas organizações precisam de configurações de fluxo de emails mais complexas para garantir que eles atendam às necessidades regulamentares ou de negócios específicas. Saiba mais sobre essas opções aqui. 
  
## <a name="custom-routing-of-outbound-email"></a>Roteamento personalizado de email de saída

O Microsoft Exchange Online pode rotear os emails que estão saindo da sua organização por meio de um servidor local ou um serviço hospedado (às vezes chamado de "host inteligente"). Isso permite que sua organização use dispositivos de prevenção contra perda de dados (DLP), execute o pós-processamento personalizado de emails de saída e entregue emails para parceiros de negócios por meio de redes privadas. O Exchange Online também dá suporte à Regravação de Endereço, que encaminha emails de saída por meio de um gateway local que modifica os endereços. Esse recurso permite ocultar sub-domínios, fazer com que os emails de uma organização de vários domínios apareçam como um único domínio ou façam com que os emails repassados por parceiros apareçam como se fossem enviados de dentro da sua organização. Os administradores configuram o roteamento do email personalizado dentro do EAC (Centro de Administração do Exchange).
  
Para obter mais informações, consulte [Configurar conectores para rotear emails entre a Microsoft e seus próprios servidores de email.](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail)
  
> [!IMPORTANT]
> O Exchange Online entrega emails fluindo para dentro ou para fora da organização. Se o domínio do destinatário estiver hospedado no Exchange Online com registros MX DNS apontando para a Proteção do Exchange Online, o fluxo de emails do seu locatário para o destinatário não passará pela Internet.
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Secure messaging with a trusted partner

Como cliente do Exchange Online, você pode configurar o fluxo de emails seguro com um parceiro confiável usando conectores da Microsoft. A Microsoft dá suporte à comunicação segura por meio do TLS (Transport Layer Security) e você pode criar um conector para impor a criptografia por meio de TLS. [O TLS](/office365/securitycompliance/exchange-online-uses-tls-to-secure-email-connections) é um protocolo criptográfico que fornece segurança para comunicações pela Internet. Usando conectores, você configura o TLS forçado tanto de entrada quanto de saída usando certificados autoassinados ou certificados validados pela AC (autoridade de certificação). Você também aplica outras restrições de segurança, como especificar nomes de domínio ou intervalos de endereços IP, dos quais a organização parceira envia emails. 
  
Saiba mais em [Set up connectors for secure mail flow with a partner organization](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).
  
> [!IMPORTANT]
> Pode ser necessário um certificado validado por CA. 
  
## <a name="conditional-mail-routing"></a>Roteamento de email condicional

É possível enviar mala direta para sites específicos usando conectores e regras de transporte. Com o roteamento baseado em critérios, você escolhe um conector com base em condições específicas.
  
Saiba mais em [Scenario: Conditional mail routing](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).
  
## <a name="incoming-mail-safe-list"></a>Lista segura de emails de entrada

É possível adicionar o endereço IP de um parceiro confiável a uma lista segura para garantir que as mensagens enviadas pelos parceiros não fiquem sujeitas ao filtro antispam. Para isso, você usa a lista Permitir IP do filtro de conexão.
  
Saiba mais em [Configure the connection filter policy](/office365/SecurityCompliance/configure-the-connection-filter-policy).
  
## <a name="hybrid-email-routing"></a>Roteamento de email híbrido

Uma implantação híbrida oferece às organizações a capacidade de levar a experiência e o controle administrativo cheio de recursos que elas possuem em suas organizações locais do Microsoft Exchange para a nuvem. O transporte híbrido faz com que as mensagens que trafegam entre destinatários das organizações sejam autenticadas, criptografadas e transferidas usando TLS (Transport Layer Security) e apareçam como "internas" para componentes do Exchange, como regras de transporte, registro no diário e diretivas antispam. Configure o transporte híbrido usando o Assistente de Configuração Híbrida no Exchange Server.
  
Para saber mais sobre o roteamento de emails em uma implantação híbrida, confira [Roteamento de Transporte em Implantações Híbridas do Exchange](/exchange/transport-routing).
  
O [Assistente de Implantação do Microsoft Exchange Server](/exchange/exchange-deployment-assistant) também oferece um provisionamento de implantação híbrida e um guia de transporte de mensagens híbrido. 
  
### <a name="shared-address-space-with-on-premises-routing-control-mx-points-to-on-premises"></a>Espaço de endereço compartilhado com controle de roteamento local (MX aponta para local)

Espaço de Endereço Compartilhado com Controle de Roteamento Local (Pontos MX para Local) é um cenário de roteamento de email de implantação híbrida no qual suas caixas de correio são hospedadas parcialmente no Exchange Online e parcialmente no local, e o fluxo de emails de entrada e saída da Internet é roteado pela organização local do Exchange. Esse cenário é também chamado de transporte de email centralizado. Nesse cenário, o Exchange Online é provisionado com o EOP e os emails de entrada da Internet são roteados para o servidor de email local antes de serem roteados para o EOP e, finalmente, para caixas de correio hospedadas no Exchange Online. Além disso, o email de saída das caixas de correio do Exchange Online é encaminhado por meio da organização do Exchange local para mensagens enviadas a destinatários externos. Com essa configuração, você usa um namespace de domínio SMTP único para todas as caixas de correio na organização do Exchange local e na sua organização do Exchange Online. 
  
Para saber mais sobre as opções de transporte em uma implantação híbrida, confira [Opções de Transporte em Implantações Híbridas do Exchange](/exchange/transport-options).
  
### <a name="shared-address-space-without-on-premises-routing-control-mx-points-to-eop"></a>Espaço de endereço compartilhado sem controle de roteamento local (MX aponta para EOP)

Espaço de Endereço Compartilhado sem Controle de Roteamento Local (o MX aponta para o EOP) é um cenário de roteamento de email híbrido no qual suas caixas de correio são hospedadas parcialmente na nuvem usando o Exchange Online e parcialmente o Exchange local, e seu registro MX aponta para o EOP. Esse cenário é apropriado quando você usa a Microsoft para hospedar algumas das caixas de correio da sua organização e deseja que o EOP proteja suas caixas de correio locais e na nuvem. Neste cenário, o email enviado aos destinatários na organização é inicialmente encaminhado por meio do EOP, em que a filtragem de spam e de política ocorre, antes de chegar às caixas de correio locais e na nuvem. 
  
Para saber mais sobre as opções de transporte em uma implantação híbrida, confira [Opções de Transporte em Implantações Híbridas do Exchange](/exchange/transport-options).
  
### <a name="troubleshooting-a-deployment-with-the-hybrid-configuration-wizard"></a>Solucionando problemas de uma implantação com o Assistente de Configuração Híbrida

Usar o Assistente de Configuração Híbrida para configurar uma implantação híbrida no Microsoft Exchange Server reduz bastante o potencial de que a implantação híbrida enfrente problemas. Entretanto, existem algumas áreas típicas fora do escopo do Assistente de Configuração Híbrida que, se configuradas incorretamente, podem representar problemas em uma implantação híbrida. Entre elas estão a configuração correta do servidor de Acesso para Cliente e a instalação e a configuração adequadas do certificado.
  
Saiba mais sobre a solução de problemas de uma implantação com o Assistente de Configuração Híbrida em [Solucionar problemas de implantação híbrida](/exchange/hybrid-deployment/troubleshoot-a-hybrid-deployment).
  
### <a name="managing-a-hybrid-configuration"></a>Gerenciando uma configuração híbrida

Você pode modificar uma configuração híbrida existente alterando as configurações no Assistente de Configuração Híbrida. Os cenários incluem desabilitação de transporte centralizado ou desabilitação de transporte de email seguro.
  
Saiba mais sobre o gerenciamento de uma configuração de implantação híbrida em [Gerenciar uma Implantação Híbrida](/previous-versions/exchange-server/exchange-150/jj200791(v=exchg.150)).
  
### <a name="hybrid-deployment-requirements"></a>Requisitos de implantação híbrida

Saiba mais sobre os requisitos de implantação híbrida em [Pré-requisitos da implantação híbrida](/exchange/hybrid-deployment-prerequisites).
  
> [!IMPORTANT]
> Em algumas configurações híbrida, pode ser preciso adquirir as licenças da Proteção do Exchange Online para as suas caixas de correio local. 
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos entre planos, opções autônomas e soluções locais, consulte a descrição do [serviço do Exchange Online.](exchange-online-service-description.md)
