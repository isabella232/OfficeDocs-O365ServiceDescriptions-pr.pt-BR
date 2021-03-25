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
description: Os seguintes limites atualmente existem para a Proteção do Exchange Online. Esses limites não são configuráveis, a menos que especificado de outra forma.
ms.openlocfilehash: 6c399c359d39f50a4bd359833fdf595415872bff
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173796"
---
# <a name="exchange-online-protection-limits"></a>Limites do Exchange Online Protection

Os seguintes limites atualmente existem para a Proteção do Exchange Online. Esses limites não são configuráveis, a menos que especificado de outra forma. 
  
> [!TIP]
> Para obter mais informações sobre limites no Exchange Online, consulte [Limites do Exchange Online.](../exchange-online-service-description/exchange-online-limits.md) Os limites de regras de transporte também se aplicam aos clientes do EOP autônomo. Os limites de taxas de destinatários e de taxas de mensagens para o Exchange Online não se aplicam aos clientes do EOP autônomo. 
  
- **Limite de** domínio - Você pode adicionar até 900 domínios por locatário. Os subdomínios podem ser incluídos neste limite de 900 ou, caso necessário, como parte de uma opção pega-tudo, podem corresponder a subdomínios. Para saber mais, confira [Gerenciar domínios aceitos no EOP](/microsoft-365/security/office-365-security/exchange-online-protection-overview).

- **Limite de domínio remoto** - Você pode adicionar até 200 domínios remotos por locatário.
    
- **Limite de tamanho da mensagem** - O tamanho máximo da mensagem para clientes autônomos do EOP, incluindo anexos, é de 150 MB. 
    
- **Número de mensagens de** saída enviadas - O limite para o número de mensagens de saída enviadas pelo EOP é alto o suficiente para garantir que a comunicação de email normal não seja tratada como spam. Se quiser enviar mensagens de email comerciais em massa em vez de enviar mensagens de saída pelo EOP, recomendamos usar um provedor de serviço de email (ESP) de terceiros ou enviar as mensagens pelos servidores de email locais. 
    
- **Limite de** destinatários - Desde que o host de envio possa dividir a mensagem em "partes" de menos de 500 destinatários, nenhum limite explícito será definido. No entanto, cada "bloco" será efetivamente tratado como uma nova mensagem. Muitas mensagens em um curto período, mensagens de um host com uma má reputação ou mensagens com conteúdo questionável poderiam ser reduzidas ou bloqueadas. 
    
- Limite de lista ip allow or **IP Block** - Ao configurar uma lista de IIs Permitidos ou uma lista de IIs Bloqueados no filtro de conexão, você pode especificar um máximo de 1273 entradas, onde uma entrada é um único endereço IP ou um intervalo CIDR de endereços IP de /24 a /32. 
    
- **Limite de adiamento de mensagens** - As mensagens em adiamento permanecerão em nossas filas por 24 horas. As tentativas de repetição de mensagens baseiam-se no tipo de erro recebido do sistema de mensagens do destinatário. As mensagens são repetidas a cada 15 minutos. 
    
- **Período de retenção de quarentena de** spam - Por padrão, as mensagens de spam enviadas para a quarentena são mantidas por 30 dias. Os administradores podem reduzir este valor usando as diretivas de filtro de conteúdo. 
    
- **Notificações de quarentena de spam** do usuário final - Por padrão, se habilitadas, as notificações de quarentena de spam do usuário final são enviadas a cada 3 dias. Elas podem ser configuradas para envio diário ou até de 15 em 15 dias. 
    
- **Limites de rastreamento** de relatórios e mensagens - Para limites de rastreamento de relatórios e mensagens, consulte a seção "Disponibilidade e latência de dados de rastreamento de relatórios e mensagens" em [Reporting and message trace in Exchange Online Protection](/microsoft-365/security/office-365-security/reporting-and-message-trace-in-exchange-online-protection).
    
### <a name="limits-across-eop-options"></a>Limites nas opções do EOP

| Recurso | EOP Autônomo | Recursos do EOP no Exchange Online | Exchange Enterprise CAL com Serviços |
|:-----|:-----|:-----|:-----|
|Limite de domínios  <br/> |900  <br/> |900  <br/> |900  <br/> |
|Limite de Domínio Remoto  <br/> |200  <br/> |200  <br/> |200  <br/> |
|Limite de tamanho de mensagens (incluindo anexos)  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|Limite de destinatários  <br/> |Confira "Limite de destinatários" acima  <br/> |500 destinatários durante o envio de uma caixa de correio hospedada; consulte "Limite de destinatários" acima para outros cenários  <br/> |Confira "Limite de destinatários" acima  <br/> |
|Limite de remetentes seguros  <br/> |1.024 entradas  <br/> |1.024 entradas  <br/> ||
|Limite de remetente bloqueado por política  <br/> |1.024 entradas  <br/> |1.024 entradas  <br/> ||
|Limite da lista de IP Permitidos e de IP Bloqueados  <br/> |1273 entradas  <br/> |1273 entradas  <br/> |1273 entradas  <br/> |
|Limite de adiamento de mensagens  <br/> |1 dia, recuperada a cada 15 minutos  <br/> |1 dia, recuperada a cada 15 minutos  <br/> |1 dia, recuperada a cada 15 minutos  <br/> |
|Período de retenção da quarentena de spam  <br/> |30 dias por padrão, mas pode ser baixado  <br/> |30 dias por padrão, mas pode ser baixado  <br/> |30 dias por padrão, mas pode ser baixado  <br/> |
|Notificações da quarentena de spam para usuário final  <br/> |3 dias por padrão, configurável de 1 a 15 dias  <br/> |3 dias por padrão, configurável de 1 a 15 dias  <br/> |3 dias por padrão, configurável de 1 a 15 dias  <br/> |
