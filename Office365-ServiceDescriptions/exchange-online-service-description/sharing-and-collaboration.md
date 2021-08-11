---
title: Compartilhamento e colaboração
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-sharing-and-collaboration
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 862dab54-701f-4014-a594-0b71e03772d2
ms.openlocfilehash: 25df0c4b4ff71ce8b3543cf7810bb0a4dd3c45fbe1037e1fd8bad4e586dd6292
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 08/06/2021
ms.locfileid: "54663634"
---
# <a name="sharing-and-collaboration"></a>Compartilhamento e colaboração

## <a name="federated-sharing"></a>Compartilhamento federado

Federação refere-se à infraestrutura de confiança subjacente que dá suporte ao compartilhamento federado, um método para que os usuários Microsoft Exchange Online compartilhem dados de calendário de livre/ocupado e informações de contato com destinatários em outras organizações federadas externas ou com usuários que tenham acesso à Internet. Isso inclui as organizações que são também hospedadas pelo Exchange Online ou pelas organizações externas do Microsoft Exchange Server 2010 ou Exchange Server 2013. Usando relações de organização e políticas de compartilhamento, os administradores Exchange Online podem permitir que os usuários enviem convites de compartilhamento de calendário da Microsoft Outlook na Web ou Microsoft Outlook 2010 ou posterior.
  
> [!IMPORTANT]
>  As organizações do External Exchange 2010 e do Exchange 2013 devem configurar uma confiança de federação com o Microsoft Federation Gateway como parte da configuração do compartilhamento federado. Exchange Online organizações não precisam configurar uma confiança de federação— a confiança de federação com o Microsoft Federation Gateway é criada automaticamente quando a organização Microsoft 365 é criada. 
>
>  As organizações do Exchange Online devem configurar um relacionamento de organização ou uma política de compartilhamento para permitir o compartilhamento federado. 
>
>  O compartilhamento de listas de acesso global (GALs) ou a movimentação de caixas de correio de usuário entre Exchange Online organizações em diferentes planos da Microsoft não são suportados no compartilhamento federado. 
  
Para saber mais sobre o compartilhamento federado, confira [Compartilhando no Exchange Online](/exchange/sharing/sharing).
  
## <a name="site-mailboxes"></a>Caixas de correio locais

Emails e documentos são tradicionalmente mantidos em dois repositórios de dados exclusivos e separados. A maioria das equipes colabora usando emails e documentos. O desafio é que os emails e os documentos são acessados usando-se clientes diferentes. Isso geralmente resulta em uma redução da produtividade do usuário e em uma experiência degradada para ele.
  
A caixa de correio de site é um conceito novo no Exchange 2013 que tenta resolver esse problema. As caixas de correio de site melhoram a colaboração e a produtividade do usuário usando a mesma interface de cliente para permitir acesso aos documentos do Microsoft SharePoint 2013 e ao email do Exchange. Uma caixa de correio de site é composta funcionalmente pela associação ao site do SharePoint 2013 (proprietários e membros), armazenamento compartilhado através de uma caixa de correio do Exchange 2013 para emails e um site do SharePoint 2013 para documentos e uma interface de gerenciamento que lida com as necessidades de provisionamento e ciclo de vida.
  
> [!IMPORTANT]
> Seu plano deve incluir SharePoint. As caixas de correio de site requerem que os usuários tenham licenças de SharePoint e Exchange. 
  
Para saber mais sobre caixas de correio de sites, confira [Caixas de correio de sites](/exchange/collaboration-exo/collaboration-exo).
  
## <a name="public-folders"></a>Pastas públicas

As pastas públicas no Exchange Online foram modernizadas para aproveitar as tecnologias existentes de alta disponibilidade e armazenamento do banco de dados de caixa de correio. A hierarquia de pasta pública usa caixas de correio designadas especialmente para armazenar o conteúdo da pasta pública e a hierarquia. Isso significa que não há mais um banco de dados de pasta pública separado. A replicação de pasta pública agora usa o modelo de replicação contínua. A alta disponibilidade da hierarquia e das caixas de correio de conteúdo é fornecida por um grupo de disponibilidade de banco de dados (DAG) no data center. Em Exchange Online, você está limitado a 1.000 caixas de correio de pasta pública. Cada caixa de correio da pasta pública também possui um tamanho máximo de armazenamento. Para obter mais informações, consulte a seção "Limites da pasta de caixa de correio" [Exchange Online limites](exchange-online-limits.md). As caixas de correio da pasta pública possuem os mesmos limites de alerta de capacidade, mensagem, destinatário do que as caixas de correio normais. Para obter mais informações, consulte [Destinatários](recipients.md). 
  
Para saber mais sobre pastas públicas, confira [Pastas públicas](/exchange/collaboration-exo/public-folders/public-folders).
  
## <a name="group-and-shared-mailboxes"></a>Caixas de correio de grupo e compartilhadas

As caixas de correio de grupo e compartilhadas facilitam que um grupo específico de pessoas monitore e envie emails de uma conta comum, como endereços de email públicos (por exemplo, info@contoso.com ou contact@contoso.com). Quando uma pessoa no grupo responde a uma mensagem enviada à caixa de correio compartilhada, o email parece ser da caixa de correio Compartilhada, não do usuário individual.
  
Normalmente, caixas de correio de grupo ou compartilhadas não exigem uma licença de usuário separada. No entanto, para habilitar In-Place arquivo morto para um grupo ou uma caixa de correio compartilhada, você deve atribuir uma licença Exchange Online Plano 1 ou Exchange Online Plano 2 a ele. Depois que a licença for atribuída, o tamanho da caixa de correio aumentará de acordo com o plano licenciado. Para colocar uma caixa de correio compartilhada em In-Place, você deve atribuir uma licença Exchange Online Plano 2 a ela. Observe que as caixas de correio de grupo não podem ser atribuídas no momento, mas devem ser contabiladas no total de licenças.
  
O Arquivo-Morto no Local pode ser usado para arquivar e-mails para um único usuário ou uma entidade (como uma caixa de correio Compartilhada) para a qual uma licença foi aplicada. É proibido usar o Arquivo Morto no Local para armazenar os emails de vários usuários ou entidades. Por exemplo, um administrador de TI não pode criar uma caixa de correio compartilhada e fazer com que os usuários a copiem (pelo campo Cc ou Cco ou por meio de uma regra de transporte) para o expresso fim de arquivamento. Observe que uma caixa de correio compartilhada usada por várias pessoas não armazena os emails desses usuários individuais. Vários usuários têm acesso a ela e enviam emails em nome da caixa de correio compartilhada. Portanto, os únicos emails armazenados na caixa de correio compartilhada são aqueles que foram enviados por ela e para ela, como a caixa de correio compartilhada.
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos entre planos, opções autônomas e soluções locais, consulte [Exchange Online descrição do serviço.](exchange-online-service-description.md)
