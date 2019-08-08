---
title: Limites do Exchange Online Protection
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: f866fe3b-a183-4e6d-abd9-bbec0a0c7fae
description: Os seguintes limites existem atualmente para o Exchange Online Protection. Estes limites não são configuráveis, a menos que haja outra regra nesse sentido.
ms.openlocfilehash: fd5dbbe0f52eb7789b2e730faf76e89803033ad6
ms.sourcegitcommit: 5b1670c36e256aef7f222951a49a4411afc3bcb6
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 08/07/2019
ms.locfileid: "36231389"
---
# <a name="exchange-online-protection-limits"></a>Limites do Exchange Online Protection

Os seguintes limites existem atualmente para o Exchange Online Protection. Estes limites não são configuráveis, a menos que haja outra regra nesse sentido. 
  
> [!TIP]
> Para saber mais sobre limites no Exchange Online, consulte [Limites do Exchange Online](../exchange-online-service-description/exchange-online-limits.md). Os limites de regras de transporte também se aplicam aos clientes do EOP autônomo. Os limites de taxas de destinatários e de taxas de mensagens para o Exchange Online não se aplicam aos clientes do EOP autônomo. 
  
- **Limite de domínios** Você pode adicionar até 900 domínios por locatário. Os subdomínios podem ser incluídos neste limite de 900 ou, caso necessário, como parte de uma opção pega-tudo, podem corresponder a subdomínios. Para saber mais, confira [Gerenciar domínios aceitos no EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).
    
- **Limite de tamanho de mensagens** O tamanho máximo das mensagens para clientes do EOP autônomo, incluindo anexos, é de 150 MB. 
    
- **Número de mensagens de saída enviadas** O limite para o número de mensagens de saída enviadas pelo EOP é grande o bastante para garantir que as comunicações normais por email não sejam tratadas como spam. Se quiser enviar mensagens de email comerciais em massa em vez de enviar mensagens de saída pelo EOP, recomendamos usar um provedor de serviço de email (ESP) de terceiros ou enviar as mensagens pelos servidores de email locais. 
    
- **Limite de destinatários** Contanto que o host de envio possa dividir a mensagem em "blocos" de menos de 500 destinatários, não há um limite explícito definido. No entanto, cada "bloco" será efetivamente tratado como uma nova mensagem. Muitas mensagens em um curto período, mensagens de um host com uma má reputação ou mensagens com conteúdo questionável poderiam ser reduzidas ou bloqueadas. 
    
- **Limite da lista de IP Permitidos e de IP Bloqueados** Ao configurar uma lista de IP Permitidos e de IP Bloqueados no filtro de conexão, você pode especificar um número máximo de 1273 entradas, em que uma entrada é também um endereço IP único ou um intervalo CIDR de endereços IP de /24 a /32. 
    
- **Limite de adiamento de mensagens** As mensagens no adiamento permanecerão nas filas por 24 horas. As tentativas de repetição de mensagens baseiam-se no tipo de erro recebido do sistema de mensagens do destinatário. As mensagens são repetidas a cada 15 minutos. 
    
- **Período de retenção de quarentena de spam** Por padrão, as mensagens de spam enviadas para a quarentena são mantidas por 30 dias. Os administradores podem reduzir este valor usando as diretivas de filtro de conteúdo. 
    
- **Notificações da quarentena de spam para usuário final** Por padrão, e se estiverem habilitadas, as notificações da quarentena de spam são enviadas a cada 3 dias. Elas podem ser configuradas para envio diário ou até de 15 em 15 dias. 
    
- **Limites de rastreamento de mensagens e relatórios** Para saber quais são os limites de rastreamento de mensagens e relatórios, confira a seção "Disponibilidade e latência de dados de relatórios e rastreamento de mensagens" em [Relatórios e rastreamento de mensagem no Exchange Online Protection](https://go.microsoft.com/fwlink/?LinkId=394248).
    
### <a name="limits-across-eop-options"></a>Limites nas opções do EOP

|**Recurso**|****EOP Autônomo****|****Recursos do EOP no Exchange Online****|****Exchange Enterprise CAL com Serviços****|
|:-----|:-----|:-----|:-----|
|Limite de domínios  <br/> |900  <br/> |900  <br/> |900  <br/> |
|Limite de tamanho de mensagens (incluindo anexos)  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|Limite de destinatários  <br/> |Confira "Limite de destinatários" acima  <br/> |500 destinatários durante o envio de uma caixa de correio hospedada; consulte "Limite de destinatários" acima para outros cenários  <br/> |Confira "Limite de destinatários" acima  <br/> |
|Limite de remetentes seguros  <br/> |1.024 entradas  <br/> |1.024 entradas  <br/> ||
|Limite de remetentes bloqueados por política  <br/> |1.024 entradas  <br/> |1.024 entradas  <br/> ||
|Limite da lista de IP Permitidos e de IP Bloqueados  <br/> |1273 entradas  <br/> |1273 entradas  <br/> |1273 entradas  <br/> |
|Limite de adiamento de mensagens  <br/> |2 dias, repetida a cada 15 minutos  <br/> |2 dias, repetida a cada 15 minutos  <br/> |2 dias, repetida a cada 15 minutos  <br/> |
|Período de retenção da quarentena de spam  <br/> |30 dias por padrão, mas pode ser reduzido  <br/> |30 dias por padrão, mas pode ser reduzido  <br/> |30 dias por padrão, mas pode ser reduzido  <br/> |
|Notificações da quarentena de spam para usuário final  <br/> |3 dias por padrão, configurável de 1 a 15 dias  <br/> |3 dias por padrão, configurável de 1 a 15 dias  <br/> |3 dias por padrão, configurável de 1 a 15 dias  <br/> |
   

