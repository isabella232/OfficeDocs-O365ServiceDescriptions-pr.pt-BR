---
title: Recursos de arquivamento no arquivamento do Exchange Online
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- archive-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 38abfbd2-5aaa-444a-a431-5e71c566f3e4
description: As seções a seguir descrevem os recursos de arquivamento do arquivamento do Microsoft Exchange Online.
ms.openlocfilehash: 7f6b5863d94862644fb90d1d0d85c3765ad05e9b
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45131525"
---
# <a name="archive-features-in-exchange-online-archiving"></a>Recursos de arquivamento no arquivamento do Exchange Online

As seções a seguir descrevem os recursos de arquivamento do arquivamento do Microsoft Exchange Online.
  
## <a name="archive-mailbox"></a>Caixa de correio de arquivamento

O Arquivamento do Exchange Online oferece aos usuários recursos avançados de arquivamento com o recurso da caixa de correio de arquivamento. Uma caixa de correio de arquivo morto é uma caixa de correio especializada que aparece junto com as pastas de caixa de correio principais dos usuários no Outlook ou no Outlook na Web. Os usuários podem acessar o arquivamento da mesma forma como acessam suas caixas de correio primárias. Além disso, eles podem pesquisar seus arquivos e caixas de correio primárias.
  
Administrators can use the Exchange admin center (EAC) or remote Windows PowerShell to enable the archive feature for specific users. For more information, see [Enable or disable archive mailboxes in Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes).
  
> [!IMPORTANT]
>  O uso em registro no diário, regras de transporte ou de encaminhamento automático para copiar mensagens para o Arquivamento do Exchange Online com a finalidade de arquivamento não é permitido. <br/>
>  A caixa de correio de arquivo morto de um usuário destina-se somente a esse usuário. A Microsoft reserva-se o direito de negar o arquivamento ilimitado em casos em que a caixa de correio de arquivo morto de um usuário é usada para armazenar dados de arquivo para outros usuários ou em outros casos de uso inadequado.
  
### <a name="move-messages-to-exchange-online-archiving"></a>Mover mensagens para o arquivamento do Exchange Online

Os usuários podem arrastar e soltar as mensagens dos arquivos .pst no arquivamento para terem um acesso online fácil. Os usuários também podem mover automaticamente os itens de email da caixa de correio primária para a caixa de correio de arquivamento, usando as Políticas de arquivamento, para reduzir o tamanho e melhorar o desempenho da caixa de correio primária. 
  
### <a name="import-data-to-the-archive"></a>Importar dados para o arquivamento

Os usuários podem importar dados para o arquivamento das seguintes maneiras:
  
- Importar dados de um arquivo .pst usando o assistente de Importação e Exportação do Outlook.
    
- Arrastar as mensagens de e-mail dos arquivos .pst para o arquivamento.
    
- Arrastar as mensagens de e-mail da caixa de correio primária para o arquivamento.
    
- Let archive policies automatically move email messages from the primary mailbox, based on the age of the messages. For more information, see [Retention Tags and Retention Policies](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).
    
> [!NOTE]
> Administrators can also use Office 365 Import service to import .pst files to users' cloud-based archive mailboxes. For more information, see [Use network upload to import PST files to Office 365](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files). 
  
## <a name="deleted-item-recovery"></a>Recuperação de itens excluídos

Users can restore items they have deleted from any email folder in their archive. When an item is deleted, it is kept in the archive's Deleted Items folder. It remains there until it is manually removed by the user, or automatically removed by retention policies.
  
Após um item ter sido removido da pasta Itens excluídos do arquivamento, ele é mantido na pasta Itens recuperáveis por mais 14 dias, até ser removido permanentemente. Os usuários podem recuperar esses itens usando o recurso **recuperar itens excluídos** no Microsoft Outlook ou no Outlook na Web. 
  
If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same 14 day window, through a feature called Single Item Recovery. This feature allows administrators to conduct a multi-mailbox search to find purged items and then use the  `Search-Mailbox` Windows PowerShell cmdlet to move the items from the discovery mailbox to users' mailboxes. For more information, see [Enable or disable single item recovery for a mailbox](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).
  
> [!NOTE]
>  O período de Recuperação de Item Único é de 14 dias por padrão, mas pode ser personalizado em algumas circunstâncias. <br/>
>  Se um administrador colocou a caixa de correio de um usuário em bloqueio in-loco ou retenção de litígio, os itens removidos serão mantidos indefinidamente e a janela de 14 dias não se aplicará. 
  
## <a name="deleted-mailbox-recovery"></a>Recuperação da caixa de correio excluída

Quando os administradores excluem os usuários do Exchange Server local, os arquivamentos dos usuários também serão excluídos. Se as caixas de correio de arquivo morto excluídas precisarem ser recuperadas, a equipe de suporte da Microsoft poderá realizar essa recuperação. Um arquivamento recuperado conterá todos os e-mails armazenados no momento em que foi excluído.
  
> [!IMPORTANT]
> Administrators have 30 days from the time a user's mailbox is deleted to request an archive mailbox recovery. After 30 days, the archive mailbox is not recoverable. 
  
## <a name="mailbox-service-redundancy"></a>Redundância de serviço de caixa de correio

As caixas de correio de arquivamento no Arquivamento do Exchange Online são replicadas em várias cópias do banco de dados, em centros de dados da Microsoft geograficamente dispersos, para fornecer a capacidade de restauração dos dados no caso de falha da infraestrutura de mensagens. Para as falhas em grande escala, o gerenciamento de continuidade de negócios é iniciado. 
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos nos planos, nas opções autônomas e nas soluções locais, consulte [Descrição do serviço de arquivamento do Exchange Online](exchange-online-archiving-service-description.md).
  
