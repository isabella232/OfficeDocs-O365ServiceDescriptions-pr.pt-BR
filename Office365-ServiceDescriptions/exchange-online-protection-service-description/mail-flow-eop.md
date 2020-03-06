---
title: Fluxo de mensagens [EOP]
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: Hospedamos as caixas de correio e cuidamos do fluxo de emails da maioria das organizações que usam o Office 365. É a configuração mais simples e significa que o Office 365 gerencia todas as caixas de correio e filtros. No entanto, algumas organizações têm a necessidade comercial de manter todas as caixas de correio no local. O proteção do Exchange Online (EOP) permite que você faça isso e fornece antivírus e processamento de email antispam na nuvem.
ms.openlocfilehash: c6a41df3e8b8c157d599f6a9d55be4b7f826e1d9
ms.sourcegitcommit: b957054b6d0a96dbb2b9ced39b5c9935aa07111c
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/05/2020
ms.locfileid: "42545814"
---
# <a name="mail-floweop"></a>Fluxo de mensagens [EOP]

Hospedamos as caixas de correio e cuidamos do fluxo de emails da maioria das organizações que usam o Office 365. É a configuração mais simples e significa que o Office 365 gerencia todas as caixas de correio e filtros. No entanto, algumas organizações têm a necessidade comercial de manter todas as caixas de correio no local. O proteção do Exchange Online (EOP) permite que você faça isso e fornece antivírus e processamento de email antispam na nuvem. Para mais informações e adquirir a EOP, acesse [Proteção do Exchange Online](https://products.office.com/exchange/exchange-email-security-spam-protection).
  
Procurando informações sobre o gerenciamento de domínio ou o Bloqueio de Borda Baseado em Diretório (DBEB)? Confira [Gerenciamento de destinatários, domínios e da empresa](recipient-domain-and-company-management.md). Para saber mais sobre todos os recursos do EOP, consulte a [Descrição do serviço de proteção do Exchange Online](exchange-online-protection-service-description.md).
  
## <a name="routing-email-between-office-365-and-your-own-email-servers"></a>Direcionar os emails entre seus próprios servidores de email e o Office 365

Você pode configurar um conector para permitir o fluxo de emails entre o Office 365 (incluindo o Exchange Online ou a EOP) e um servidor de emails baseado em SMTP, como o Exchange. Confira mais detalhes sobre isso em [Do I need a connector](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)? e [Set up connectors to route mail between Office 365 and your own email servers](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail).
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Mensagens seguras com um parceiro confiável

Como cliente da EOP, você configura um fluxo de emails seguro com um parceiro de confiança usando os conectores do Office 365. O Office 365 dá suporte à comunicação segura por meio de TLS (Transport Layer Security), e você cria um conector para impor criptografia por meio de TLS. O [TLS](https://docs.microsoft.com/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections) é um protocolo criptográfico que oferece segurança para comunicações pela Internet. Usando conectores, você configura o TLS forçado tanto de entrada quanto de saída usando certificados autoassinados ou certificados validados pela AC (autoridade de certificação). Você também aplica outras restrições de segurança, como especificar nomes de domínio ou intervalos de endereços IP, dos quais a organização parceira envia emails. 
  
Saiba mais em [Configurar conectores para fluxo de email seguro com uma organização parceira](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner)
  
## <a name="safe-listing-a-partners-ip-address"></a>Lista segura de endereço IP de um parceiro

Você pode adicionar o endereço IP de um parceiro de confiança a uma lista segura para garantir que as mensagens enviadas por ele não fiquem sujeitas ao filtro antispam. Para tanto, você pode usar a Lista de IPs Permitidos do filtro de conexão. Saiba mais em [Configure a política de filtro de conexão](https://go.microsoft.com/fwlink/p/?LinkID=287108).
  
## <a name="conditional-mail-routing"></a>Roteamento de email condicional

Você pode configurar um conector com uma regra de Transporte que roteia emails para um site específico, com base em condições. Saiba mais em [Scenario: Conditional email routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).
  
## <a name="hybrid-mail-routing"></a>Roteamento híbrido de email

Híbrido significa que você hospeda parte das caixas de correio no local e parte na nuvem (Exchange Online). Você pode mudar de uma implantação autônoma (no local) para uma híbrida.
  
Se tiver uma implantação híbrida, poderá proteger suas caixas de correio locais e na nuvem com a EOP. São necessárias licenças autônomas para as caixas de correio locais protegidas por EOP. Confira mais informações sobre o roteamento de emails em uma implantação híbrida em [Roteamento de Transporte em implantações híbridas do Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271757).
  
O [Assistente de Implantação do Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036) também oferece um provisionamento de implantação híbrida e um guia de transporte de mensagens híbrido. 
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos nos planos do Office 365, nas opções autônomas e nas soluções locais, consulte [Descrição do serviço de proteção do Exchange Online](exchange-online-protection-service-description.md).
