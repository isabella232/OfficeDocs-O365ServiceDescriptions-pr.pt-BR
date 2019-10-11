---
title: Compartilhamento e Colaboração
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-sharing-and-collaboration
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 862dab54-701f-4014-a594-0b71e03772d2
ms.openlocfilehash: 2bb90afe0011d1799a9faf71ea025261d586692d
ms.sourcegitcommit: 3d180fb603896239b30d9db6ba865843c29801b0
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/10/2019
ms.locfileid: "37442536"
---
# <a name="sharing-and-collaboration"></a>Compartilhamento e Colaboração

## <a name="federated-sharing"></a>Compartilhamento federado

A Federação se refere à infraestrutura de confiança subjacente que oferece suporte ao compartilhamento federado, um método para os usuários do Microsoft Exchange Online compartilharem dados de calendário de disponibilidade e informações de contato com destinatários em outras organizações federadas externas ou com usuários com acesso à Internet. Isso inclui as organizações que são também hospedadas pelo Exchange Online ou pelas organizações externas do Microsoft Exchange Server 2010 ou Exchange Server 2013. Usando relacionamentos de organização e políticas de compartilhamento, os administradores do Exchange Online podem permitir que os usuários enviem convites de compartilhamento de calendário usando o Microsoft Outlook Web App ou o Microsoft Outlook 2010 ou posterior.
  
> [!IMPORTANT]
>  As organizações do External Exchange 2010 e do Exchange 2013 devem configurar uma confiança de federação com o Microsoft Federation Gateway como parte da configuração do compartilhamento federado. As organizações do Exchange Online não precisam configurar uma confiança de federação - a confiança de federação com o Microsoft Federation Gateway é criada automaticamente quando o locatário do Office 365 é criado. >  As organizações do Exchange Online devem configurar um relacionamento de organização ou uma política de compartilhamento para permitir o compartilhamento federado. >  Compartilhar a lista de acesso global (GAL) ou mover as caixas de correio do usuário entre as organizações do Exchange Online em diferentes locatários do Office 365 não são suportados no compartilhamento federado. 
  
Para saber mais sobre o compartilhamento federado, confira [Compartilhando no Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271774).
  
## <a name="site-mailboxes"></a>Caixas de correio locais

Emails e documentos são tradicionalmente mantidos em dois repositórios de dados exclusivos e separados. A maioria das equipes colabora usando emails e documentos. O desafio é que os emails e os documentos são acessados usando-se clientes diferentes. Isso geralmente resulta em uma redução da produtividade do usuário e em uma experiência degradada para ele.
  
A caixa de correio de site é um conceito novo no Exchange 2013 que tenta resolver esse problema. As caixas de correio de site melhoram a colaboração e a produtividade do usuário usando a mesma interface de cliente para permitir acesso aos documentos do Microsoft SharePoint 2013 e ao email do Exchange. Uma caixa de correio de site é composta funcionalmente pela associação ao site do SharePoint 2013 (proprietários e membros), armazenamento compartilhado através de uma caixa de correio do Exchange 2013 para emails e um site do SharePoint 2013 para documentos e uma interface de gerenciamento que lida com as necessidades de provisionamento e ciclo de vida.
  
> [!IMPORTANT]
> Seu plano de Office 365 deve incluir o SharePoint. As caixas de correio de site requerem que os usuários tenham licenças de SharePoint e Exchange. 
  
Para saber mais sobre caixas de correio de sites, confira [Caixas de correio de sites](https://go.microsoft.com/fwlink/p/?LinkId=271789).
  
## <a name="public-folders"></a>Pastas públicas

As pastas públicas no Exchange Online foram modernizadas para aproveitar as tecnologias existentes de alta disponibilidade e armazenamento do banco de dados de caixa de correio. A hierarquia de pasta pública usa caixas de correio designadas especialmente para armazenar o conteúdo da pasta pública e a hierarquia. Isso significa que não há mais um banco de dados de pasta pública separado. A replicação de pasta pública agora usa o modelo de replicação contínua. A alta disponibilidade da hierarquia e das caixas de correio de conteúdo é fornecida por um grupo de disponibilidade de banco de dados (DAG) no data center. No Exchange Online, você está limitado a 1000 caixas de correio de pasta pública. Cada caixa de correio da pasta pública também possui um tamanho máximo de armazenamento. Para obter mais informações, consulte a seção "Limites de pasta da caixa de correio" em [Limites do Exchange Online](exchange-online-limits.md). As caixas de correio da pasta pública possuem os mesmos limites de alerta de capacidade, mensagem, destinatário do que as caixas de correio normais. Para obter mais informações, consulte [Destinatários](recipients.md). 
  
Para saber mais sobre pastas públicas, confira [Pastas públicas](https://go.microsoft.com/fwlink/p/?LinkId=271790).
  
## <a name="group-and-shared-mailboxes"></a>Caixas de correio Compartilhadas e de Grupo

Com as caixas de correio Compartilhadas e de Grupo, um grupo específico de pessoas pode monitorar e enviar emails com mais facilidade de uma conta comum, como endereços de email públicos (por exemplo, info@contoso.com ou contato@contoso.com). Quando uma pessoa no grupo responde a uma mensagem enviada à caixa de correio Compartilhada, o email parece ser da caixa de correio Compartilhada, não do usuário individual.
  
Normalmente, as caixas de correio de Grupo ou Compartilhadas não exigem uma licença de usuário separada. No entanto, para habilitar o Arquivo-Morto no Local para uma caixa de correio de Grupo ou Compartilhada, você deve atribuir um Plano 1 do Exchange Online ou uma licença do Plano 2 do Exchange Online a ela. Depois que a licença for atribuída, o tamanho da caixa de correio aumentará de acordo com o plano licenciado. Para colocar uma caixa de correio Compartilhada em um Bloqueio In-loco, você deve atribuir uma licença do Plano 2 do Exchange Online a ela. Observe que as caixas de correio de Grupo não podem ser atribuídas neste momento, mas devem ser contabilizadas no total de suas licenças.
  
O Arquivo-Morto no Local pode ser usado para arquivar e-mails para um único usuário ou uma entidade (como uma caixa de correio Compartilhada) para a qual uma licença foi aplicada. É proibido usar o Arquivo Morto no Local para armazenar os emails de vários usuários ou entidades. Por exemplo, um administrador de TI não pode criar uma caixa de correio Compartilhada e fazer com que os usuários a copiem (pelo campo Cc ou Cco ou por meio de uma regra de transporte) para o expresso fim de arquivamento. Observe que uma caixa de correio Compartilhada usada por várias pessoas não armazena os emails desses usuários individuais. Vários usuários têm acesso a ela e enviam emails em nome da caixa de correio Compartilhada. Portanto, os únicos emails armazenados na caixa de correio Compartilhada são aqueles foram enviados por ela ou para ela, como caixa de correio Compartilhada.
  
## <a name="feature-availability"></a>Disponibilidade do recurso

Para exibir a disponibilidade de recursos nos planos do Office 365 nas opções autônomas e nas soluções locais, consulte [Descrição de Serviço do Exchange Online](exchange-online-service-description.md).
  

