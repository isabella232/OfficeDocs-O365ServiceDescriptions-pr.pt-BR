---
title: Alta disponibilidade e continuidade de negócios
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-high-availability-and-business-continuity
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7b03465e-3b9c-4500-8956-a83377f4c2c3
description: O Microsoft Exchange Online oferece amplo suporte de retenção e recuperação para a infraestrutura de email de uma organização. Isso inclui a replicação de caixa de correio em data centers e a capacidade de restaurar caixas de correio e itens excluídos.
ms.openlocfilehash: 395977f77d4293d18c5cf53e02d43566ca9f7313
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45131965"
---
# <a name="high-availability-and-business-continuity"></a>Alta disponibilidade e continuidade de negócios

O Microsoft Exchange Online oferece amplo suporte de retenção e recuperação para a infraestrutura de email de uma organização. Isso inclui a replicação de caixa de correio em data centers e a capacidade de restaurar caixas de correio e itens excluídos.
  
## <a name="mailbox-replication-at-data-centers"></a>Replicação de caixa de correio em data centers

Exchange Online mailboxes are continuously replicated to multiple database copies, in geographically dispersed Microsoft data centers, to provide data restoration capability in the event of a local messaging infrastructure failure. For large-scale failures, service continuity management procedures are initiated.
  
For more information about how Microsoft protects your data, see [Office 365 Trust Center](https://go.microsoft.com/fwlink/p/?LinkId=299135). If you are using Office 365 operated by 21Vianet, see the [21Vianet Trust Center](https://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl).
  
## <a name="deleted-mailbox-recovery"></a>Recuperação da caixa de correio excluída

Os administradores podem excluir caixas de correio do Exchange Online usando o centro de administração do Microsoft 365 para excluir a conta de usuário correspondente ou remover a licença do Exchange Online ou usando o cmdlet **Remove-Mailbox** no Windows PowerShell remoto. Quando uma caixa de correio é excluída, o Exchange Online mantém a caixa de correio e seu conteúdo por 30 dias, por padrão. Após 30 dias, a caixa de correio não pode ser recuperada. Uma caixa de correio recuperada contém todos os dados armazenados no momento em que foi excluída. Os administradores podem recuperar uma caixa de correio excluída dentro do período de retenção usando o centro de administração do Microsoft 365. Para recuperar uma caixa de correio excluída, os administradores precisam restaurar a conta de usuário correspondente ou reatribuir uma licença do Exchange Online à conta de usuário. Para saber mais, confira [Excluir ou restaurar caixas de correio do usuário no Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=286992).
  
## <a name="deleted-item-recovery"></a>Recuperação de itens excluídos

O Exchange Online permite que os usuários restaurem itens que foram excluídos de qualquer pasta de email, incluindo a pasta itens excluídos. Quando um item é excluído, ele é mantido na pasta Itens Excluídos do usuário. Ele permanece lá até que seja removido manualmente pelo usuário ou automaticamente removido por políticas de retenção. Os administradores podem personalizar as políticas de retenção no EAC ou usando o Windows PowerShell remoto.
  
Após um item ser removido da pasta Itens Excluídos, ele permanece na pasta Itens Recuperáveis por mais 14 dias antes de ser removido permanentemente, mas os administradores podem aumentar esse tempo até um máximo de 30 dias usando o Windows PowerShell remoto. Os usuários podem recuperar o item durante esse período de tempo usando o recurso recuperar itens excluídos no Outlook na Web ou no Outlook. Saiba como [alterar o período de retenção de item excluído](https://go.microsoft.com/fwlink/p/?LinkId=286940).
  
If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same time period by using the Single Item Recovery feature with remote Windows PowerShell. By default, Single Item Recovery is enabled when a mailbox is created. To learn more, see [Enable or disable single item recovery for a mailbox](https://go.microsoft.com/fwlink/p/?LinkID=286941).
  
To preserve messages for longer than 30 days in the Recoverable Items folder, organizations can implement longer-term email preservation or time-based In-Place Holds. Learn more about [placing a mailbox on In-Place Hold](https://go.microsoft.com/fwlink/p/?LinkId=271746).
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos nos planos, nas opções autônomas e nas soluções locais, consulte [Descrição do serviço do Exchange Online](exchange-online-service-description.md).
  