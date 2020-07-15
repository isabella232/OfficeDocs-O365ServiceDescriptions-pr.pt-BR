---
title: Limites do Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: f866fe3b-a183-4e6d-abd9-bbec0a0c7fae
description: Os seguintes limites existem atualmente para o Exchange Online Protection. Esses limites não são configuráveis, a menos que o contrário seja especificado.
ms.openlocfilehash: 3c5a8e0c5f9a19c9cae81b3bc1e39bb153af0137
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132995"
---
# <a name="exchange-online-protection-limits"></a>Limites do Exchange Online Protection

Os seguintes limites existem atualmente para o Exchange Online Protection. Esses limites não são configuráveis, a menos que o contrário seja especificado. 
  
> [!TIP]
> Para obter mais informações sobre limites no Exchange Online, consulte [limites do Exchange Online](../exchange-online-service-description/exchange-online-limits.md). Os limites de regras de transporte também se aplicam aos clientes do EOP autônomo. Os limites de taxas de destinatários e de taxas de mensagens para o Exchange Online não se aplicam aos clientes do EOP autônomo. 
  
- **Domain limit** You can add up to 900 domains per tenant. Subdomains can be included in this 900 limit, or if necessary, as part of a catch-all option, match subdomains. For more information, see [Manage Accepted Domains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).
    
- **Limite de tamanho de mensagens** O tamanho máximo das mensagens para clientes do EOP autônomo, incluindo anexos, é de 150 MB. 
    
- **Number of outbound messages sent** The limit for the number of outbound messages sent through EOP is high enough to ensure that normal email communication is not treated as spam. If you want to send commercial bulk email messages, rather than sending outbound messages through EOP, we recommend that you either use a third-party email service provider (ESP) or send them through your on-premises email servers. 
    
- **Recipient limit** As long as the sending host can split the message into "chunks" of fewer than 500 recipients, no explicit limit is defined. However, each "chunk" is effectively treated as a new message. Too many messages in a short period, messages from a host with a poor reputation, or messages with questionable content could be throttled or blocked. 
    
- **Limite da lista de IP Permitidos e de IP Bloqueados** Ao configurar uma lista de IP Permitidos e de IP Bloqueados no filtro de conexão, você pode especificar um número máximo de 1273 entradas, em que uma entrada é também um endereço IP único ou um intervalo CIDR de endereços IP de /24 a /32. 
    
- **Limite de adiamento de mensagens** As mensagens no adiamento permanecerão nas filas por 24 horas. As tentativas de repetição de mensagens baseiam-se no tipo de erro recebido do sistema de mensagens do destinatário. As mensagens são repetidas a cada 15 minutos. 
    
- **Período de retenção de quarentena de spam** Por padrão, as mensagens de spam enviadas para a quarentena são mantidas por 30 dias. Os administradores podem reduzir este valor usando as diretivas de filtro de conteúdo. 
    
- **End-user spam quarantine notifications** By default, if enabled, end-user spam quarantine notifications are sent every 3 days. They can be configured to be sent every 1 to 15 days. 
    
- **Limites de rastreamento de mensagens e relatórios** Para relatórios e limites de rastreamento de mensagens, consulte a seção "disponibilidade e latência dos dados de relatórios e rastreamento de mensagens" em [relatórios e rastreamento de mensagens no Exchange Online Protection](https://go.microsoft.com/fwlink/?LinkId=394248).
    
### <a name="limits-across-eop-options"></a>Limites nas opções do EOP

|**Recurso**|****EOP Autônomo****|****Recursos do EOP no Exchange Online****|****Exchange Enterprise CAL com Serviços****|
|:-----|:-----|:-----|:-----|
|Limite de domínios  <br/> |900  <br/> |900  <br/> |900  <br/> |
|Limite de tamanho de mensagens (incluindo anexos)  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|Limite de destinatários  <br/> |Confira "Limite de destinatários" acima  <br/> |500 destinatários durante o envio de uma caixa de correio hospedada; consulte "Limite de destinatários" acima para outros cenários  <br/> |Confira "Limite de destinatários" acima  <br/> |
|Limite de remetentes seguros  <br/> |1.024 entradas  <br/> |1.024 entradas  <br/> ||
|Limite de remetentes bloqueados por política  <br/> |1.024 entradas  <br/> |1.024 entradas  <br/> ||
|Limite da lista de IP Permitidos e de IP Bloqueados  <br/> |1273 entradas  <br/> |1273 entradas  <br/> |1273 entradas  <br/> |
|Limite de adiamento de mensagens  <br/> |1 dia, repetido a cada 15 minutos  <br/> |1 dia, repetido a cada 15 minutos  <br/> |1 dia, repetido a cada 15 minutos  <br/> |
|Período de retenção da quarentena de spam  <br/> |30 dias por padrão, mas pode ser reduzido  <br/> |30 dias por padrão, mas pode ser reduzido  <br/> |30 dias por padrão, mas pode ser reduzido  <br/> |
|Notificações da quarentena de spam para usuário final  <br/> |3 dias por padrão, configurável de 1 a 15 dias  <br/> |3 dias por padrão, configurável de 1 a 15 dias  <br/> |3 dias por padrão, configurável de 1 a 15 dias  <br/> |
   

