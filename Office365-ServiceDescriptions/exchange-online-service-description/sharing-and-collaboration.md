---
title: Compartilhamento e colaboração
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-sharing-and-collaboration
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 862dab54-701f-4014-a594-0b71e03772d2
ms.openlocfilehash: 8e5ce6ce41f206c5736241340c393833ae78fea7
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132585"
---
# <a name="sharing-and-collaboration"></a>Compartilhamento e colaboração

## <a name="federated-sharing"></a>Compartilhamento federado

A Federação se refere à infraestrutura de confiança subjacente que oferece suporte ao compartilhamento federado, um método para os usuários do Microsoft Exchange Online compartilharem dados de calendário de disponibilidade e informações de contato com destinatários em outras organizações federadas externas ou com usuários com acesso à Internet. Isso inclui as organizações que são também hospedadas pelo Exchange Online ou pelas organizações externas do Microsoft Exchange Server 2010 ou Exchange Server 2013. Usando relações de organização e políticas de compartilhamento, os administradores do Exchange Online podem permitir que os usuários enviem convites de compartilhamento de calendário do Microsoft Outlook na Web ou do Microsoft Outlook 2010 ou posterior.
  
> [!IMPORTANT]
>  As organizações do External Exchange 2010 e do Exchange 2013 devem configurar uma confiança de federação com o Microsoft Federation Gateway como parte da configuração do compartilhamento federado. As organizações do Exchange Online não precisam configurar uma confiança de Federação — a confiança de Federação com o Microsoft Federation Gateway é criada automaticamente quando a organização 365 da Microsoft é criada. 
>
>  As organizações do Exchange Online devem configurar um relacionamento de organização ou uma política de compartilhamento para permitir o compartilhamento federado. 
>
>  O compartilhamento de listas de acesso global (GALs) ou a transferência de caixas de correio do usuário entre as organizações do Exchange Online em diferentes planos da Microsoft não são suportados no compartilhamento federado. 
  
Para saber mais sobre o compartilhamento federado, confira [Compartilhando no Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271774).
  
## <a name="site-mailboxes"></a>Caixas de correio locais

Email and documents are traditionally kept in two unique and separate data repositories. Most teams collaborate by using both email and documents. The challenge is that email and documents are accessed by using different clients. This usually results in a reduction in user productivity and a degraded user experience.
  
The site mailbox is a new concept in Exchange 2013 that attempts to solve this problem. Site mailboxes improve collaboration and user productivity by using the same client interface to allow access to both Microsoft SharePoint 2013 documents and Exchange email. A site mailbox functionally consists of SharePoint 2013 site membership (owners and members), shared storage through an Exchange 2013 mailbox for email messages and a SharePoint 2013 site for documents, and a management interface that addresses provisioning and life cycle needs.
  
> [!IMPORTANT]
> O plano deve incluir o SharePoint. As caixas de correio de site requerem que os usuários tenham licenças de SharePoint e Exchange. 
  
Para saber mais sobre caixas de correio de sites, confira [Caixas de correio de sites](https://go.microsoft.com/fwlink/p/?LinkId=271789).
  
## <a name="public-folders"></a>Pastas públicas

As pastas públicas no Exchange Online foram modernizadas para aproveitar as tecnologias existentes de alta disponibilidade e armazenamento do banco de dados de caixa de correio. A hierarquia de pasta pública usa caixas de correio designadas especialmente para armazenar o conteúdo da pasta pública e a hierarquia. Isso significa que não há mais um banco de dados de pasta pública separado. A replicação de pasta pública agora usa o modelo de replicação contínua. A alta disponibilidade da hierarquia e das caixas de correio de conteúdo é fornecida por um grupo de disponibilidade de banco de dados (DAG) no data center. No Exchange Online, você está limitado a 1000 caixas de correio de pasta pública. Cada caixa de correio da pasta pública também possui um tamanho máximo de armazenamento. Para obter mais informações, consulte a seção "limites da pasta da caixa de correio" em [limites do Exchange Online](exchange-online-limits.md). As caixas de correio da pasta pública possuem os mesmos limites de alerta de capacidade, mensagem, destinatário do que as caixas de correio normais. Para obter mais informações, consulte [Destinatários](recipients.md). 
  
Para saber mais sobre pastas públicas, confira [Pastas públicas](https://go.microsoft.com/fwlink/p/?LinkId=271790).
  
## <a name="group-and-shared-mailboxes"></a>Grupos e caixas de correio compartilhadas

Grupos e caixas de correio compartilhadas facilitam um grupo específico de pessoas a monitorar e enviar emails de uma conta comum, como endereços de email públicos (por exemplo, info@contoso.com ou contact@contoso.com). Quando uma pessoa no grupo responde a uma mensagem enviada para a caixa de correio compartilhada, o email parece ser da caixa de correio compartilhada, e não do usuário individual.
  
Normalmente, grupos ou caixas de correio compartilhadas não exigem uma licença de usuário separada. No entanto, para habilitar o arquivo morto in-loco para um grupo ou uma caixa de correio compartilhada, você deve atribuir uma licença do Exchange Online plano 1 ou do Exchange Online plano 2 a ele. Depois que a licença for atribuída, o tamanho da caixa de correio aumentará de acordo com o plano licenciado. Para colocar uma caixa de correio compartilhada em bloqueio in-loco, você deve atribuir uma licença do Exchange Online Plan 2 a ela. Observe que as caixas de correio de grupo não podem ser atribuídas neste momento, mas devem ser contabilizadas no total de licenças.
  
O Arquivo-Morto no Local pode ser usado para arquivar e-mails para um único usuário ou uma entidade (como uma caixa de correio Compartilhada) para a qual uma licença foi aplicada. É proibido usar o Arquivo Morto no Local para armazenar os emails de vários usuários ou entidades. Por exemplo, um administrador de TI não pode criar uma caixa de correio compartilhada e fazer com que os usuários a copiem (pelo campo Cc ou Cco ou por meio de uma regra de transporte) para o expresso fim de arquivamento. Observe que uma caixa de correio compartilhada usada por várias pessoas não armazena os emails desses usuários individuais. Vários usuários têm acesso a ela e enviam emails em nome da caixa de correio compartilhada. Portanto, os únicos emails armazenados na caixa de correio compartilhada são aqueles enviados para ou dele, como a caixa de correio compartilhada.
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos nos planos, nas opções autônomas e nas soluções locais, consulte [Descrição do serviço do Exchange Online](exchange-online-service-description.md).
  

