---
title: Fluxo de emails na Proteção do Exchange Online
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: Leia este artigo para saber mais sobre o fluxo de emails no Microsoft Exchange Online Protection (EOP).
ms.openlocfilehash: 1d8cbe7d3483ee0cfc73e8cea372e0d36dbc7b6d
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173786"
---
# <a name="mail-flow-in-exchange-online-protection"></a>Fluxo de emails na Proteção do Exchange Online

Para a maioria das organizações que usam a Microsoft, hospedamos suas caixas de correio e cuidamos do fluxo de emails. É a configuração mais simples e significa que a Microsoft gerencia todas as caixas de correio e filtragem. No entanto, algumas organizações têm a necessidade comercial de manter todas as caixas de correio no local. A Proteção do Exchange Online (EOP) permite que você faça isso e fornece processamento de email antivírus e anti-spam na nuvem. Para mais informações e adquirir a EOP, acesse [Proteção do Exchange Online](https://products.office.com/exchange/exchange-email-security-spam-protection).
  
Procurando informações sobre o gerenciamento de domínio ou o Bloqueio de Borda Baseado em Diretório (DBEB)? Consulte [Recipient, domain, and company management](recipient-domain-and-company-management.md). Para saber mais sobre todos os recursos do EOP, consulte a descrição do [serviço de Proteção do Exchange Online.](exchange-online-protection-service-description.md)
  
## <a name="routing-email-between-microsoft-and-your-own-email-servers"></a>Roteamento de emails entre a Microsoft e seus próprios servidores de email

Você pode configurar um conector para habilitar o fluxo de emails entre a Microsoft (incluindo o Exchange Online ou o EOP) e um servidor de email baseado em SMTP, como o Exchange. Confira mais detalhes sobre isso em [Do I need a connector](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)? E [Configurar conectores para rotear emails entre a Microsoft e seus próprios servidores de email.](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail)
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Secure messaging with a trusted partner

Como cliente EOP, você pode configurar o fluxo de emails seguro com um parceiro confiável usando conectores da Microsoft. A Microsoft dá suporte à comunicação segura por meio do TLS (Transport Layer Security) e você pode criar um conector para impor a criptografia por meio de TLS. [O TLS](/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections) é um protocolo criptográfico que fornece segurança para comunicações pela Internet. Usando conectores, você configura o TLS forçado tanto de entrada quanto de saída usando certificados autoassinados ou certificados validados pela AC (autoridade de certificação). Você também aplica outras restrições de segurança, como especificar nomes de domínio ou intervalos de endereços IP, dos quais a organização parceira envia emails. 
  
Saiba mais em [Configurar conectores para fluxo de email seguro com uma organização parceira](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner)
  
## <a name="safe-listing-a-partners-ip-address"></a>Lista segura de endereço IP de um parceiro

Você pode adicionar o endereço IP de um parceiro de confiança a uma lista segura para garantir que as mensagens enviadas por ele não fiquem sujeitas ao filtro antispam. Para tanto, você pode usar a Lista de IPs Permitidos do filtro de conexão. Saiba mais em [Configure a política de filtro de conexão](/microsoft-365/security/office-365-security/configure-the-connection-filter-policy).
  
## <a name="conditional-mail-routing"></a>Roteamento de email condicional

Você pode configurar um conector com uma regra de Transporte que roteia emails para um site específico, com base em condições. Saiba mais em [Scenario: Conditional email routing](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).
  
## <a name="hybrid-mail-routing"></a>Roteamento híbrido de email

Híbrido significa que você hospeda parte das caixas de correio no local e parte na nuvem (Exchange Online). Você pode mudar de uma implantação autônoma (no local) para uma híbrida.
  
Se tiver uma implantação híbrida, poderá proteger suas caixas de correio locais e na nuvem com a EOP. São necessárias licenças autônomas para as caixas de correio locais protegidas por EOP. Confira mais informações sobre o roteamento de emails em uma implantação híbrida em [Roteamento de Transporte em implantações híbridas do Exchange](/exchange/transport-routing).
  
O [Assistente de Implantação do Microsoft Exchange Server](/exchange/exchange-deployment-assistant) também oferece um provisionamento de implantação híbrida e um guia de transporte de mensagens híbrido. 
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos entre planos, opções autônomas e soluções locais, consulte Descrição do serviço [de Proteção do Exchange Online.](exchange-online-protection-service-description.md)