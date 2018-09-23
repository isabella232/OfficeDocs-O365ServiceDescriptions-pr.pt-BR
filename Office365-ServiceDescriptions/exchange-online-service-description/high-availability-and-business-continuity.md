---
title: Alta Disponibilidade e Continuidade de Negócios
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-high-availability-and-business-continuity
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7b03465e-3b9c-4500-8956-a83377f4c2c3
description: Microsoft Exchange Online oferece retenção extensiva e suporte de recuperação para infraestrutura de email da organização. Isso inclui a replicação de caixa de correio em data centers e a capacidade de restaurar itens excluídos e excluídos caixas de correio.
ms.openlocfilehash: 3f926223a278bd671fa6121b2ee59b96da1f9fe1
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24034857"
---
# <a name="high-availability-and-business-continuity"></a>Alta Disponibilidade e Continuidade de Negócios

Microsoft Exchange Online oferece retenção extensiva e suporte de recuperação para infraestrutura de email da organização. Isso inclui a replicação de caixa de correio em data centers e a capacidade de restaurar itens excluídos e excluídos caixas de correio.
  
## <a name="mailbox-replication-at-data-centers"></a>Replicação de caixa de correio em data centers

As caixas de correio do Exchange Online são replicadas continuamente para várias cópias de banco de dados, em data centers da Microsoft geograficamente dispersos, para fornecer recurso de restauração de dados no caso de falha da infraestrutura de mensagens local. Para falhas em grande escala, são iniciados procedimentos de gerenciamento de continuidade de serviço.
  
Para saber mais sobre como a Microsoft protege seus dados, confira [Central de Confiabilidade do Office 365](https://go.microsoft.com/fwlink/p/?LinkId=299135). Se você estiver usando o Office 365 operado pela 21Vianet, confira a [Central de confiabilidade da 21Vianet](http://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl).
  
## <a name="deleted-mailbox-recovery"></a>Recuperação de caixa de correio excluída

Os administradores podem excluir caixas de correio Exchange Online usando o centro de administração do Office 365 para excluir a conta de usuário correspondente ou remover a licença do Exchange Online ou usando o cmdlet **Remove-Mailbox** no Windows PowerShell remoto. Quando uma caixa de correio é excluída, o Exchange Online mantém a caixa de correio e seu conteúdo por 30 dias, por padrão. Após 30 dias, a caixa de correio não pode ser recuperada. Uma caixa de correio recuperada contém todos os dados armazenados no momento em que foi excluída. Os administradores podem recuperar uma caixa de correio excluída dentro do período de retenção usando o centro de administração do Office 365. Para recuperar uma caixa de correio excluída, os administradores precisam restaurar a conta de usuário do Office 365 correspondente ou transferir uma licença do Exchange Online para a conta de usuário. Para saber mais, confira [Excluir ou restaurar caixas de correio do usuário no Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=286992).
  
## <a name="deleted-item-recovery"></a>Recuperação de itens excluídos

O Exchange Online permite que os usuários restaurem itens que excluíram de qualquer pasta de email, incluindo a pasta Itens Excluídos. Quando um item é excluído, ele é mantido na pasta Itens Excluídos do usuário. Ele permanece lá até que seja removido manualmente pelo usuário ou automaticamente removido por políticas de retenção. Os administradores podem personalizar as políticas de retenção no EAC ou usando o Windows PowerShell remoto.
  
Após um item ser removido da pasta Itens Excluídos, ele permanece na pasta Itens Recuperáveis por mais 14 dias antes de ser removido permanentemente, mas os administradores podem aumentar esse tempo até um máximo de 30 dias usando o Windows PowerShell remoto. Os usuários podem recuperar o item durante este período de tempo usando o recurso Recuperar Itens Excluídos no Outlook Web App ou no Outlook. Saiba como [alterar o período de retenção de item excluído](https://go.microsoft.com/fwlink/p/?LinkId=286940).
  
Se um usuário remover manualmente um item da pasta Itens Recuperáveis, um administrador poderá recuperar o item dentro do mesmo período de 14 dias usando o recurso de Recuperação de Item Único e o Windows PowerShell remoto. Por padrão, a Recuperação de Item Único será desabilitada quando a caixa de correio for criada. Para saber mais, confira [Habilitar ou desabilitar a recuperação de item único para uma caixa de correio](https://go.microsoft.com/fwlink/p/?LinkID=286941).
  
Para preservar mensagens por mais de 30 dias na pasta de Itens Recuperáveis, as organizações podem implementar a preservação de email de longo prazo ou Bloqueios In-loco baseados em tempo. Saiba mais sobre como [colocar uma caixa de correio em Bloqueio In-loco](https://go.microsoft.com/fwlink/p/?LinkId=271746).
  
## <a name="feature-availability"></a>Disponibilidade do recurso

Para exibir a disponibilidade de recursos nos planos do Office 365 nas opções autônomas e nas soluções locais, consulte [Descrição de Serviço do Exchange Online](exchange-online-service-description.md).
  

