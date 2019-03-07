---
title: Recursos de arquivamento no Arquivamento do Exchange Online
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
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
ms.openlocfilehash: 78b33911a583c1cc50d910e9ebd6fd2aebbfc697
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/07/2019
ms.locfileid: "30467198"
---
# <a name="archive-features-in-exchange-online-archiving"></a><span data-ttu-id="3efd6-103">Recursos de arquivamento no Arquivamento do Exchange Online</span><span class="sxs-lookup"><span data-stu-id="3efd6-103">Archive Features in Exchange Online Archiving</span></span>

<span data-ttu-id="3efd6-104">As seções a seguir descrevem os recursos de arquivamento do arquivamento do Microsoft Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="3efd6-104">The following sections describe the archive features of Microsoft Exchange Online Archiving.</span></span>
  
## <a name="archive-mailbox"></a><span data-ttu-id="3efd6-105">Caixa de correio de arquivamento</span><span class="sxs-lookup"><span data-stu-id="3efd6-105">Archive mailbox</span></span>

<span data-ttu-id="3efd6-p101">O Arquivamento do Exchange Online oferece aos usuários recursos avançados de arquivamento com o recurso da caixa de correio de arquivamento. Uma caixa de correio de arquivamento é uma caixa especializada que aparece lado a lado com as pastas primárias da caixa de correio dos usuários no Outlook ou no Outlook Web App. Os usuários podem acessar o arquivamento da mesma forma como acessam suas caixas de correio primárias. Além disso, eles podem pesquisar seus arquivos e caixas de correio primárias.</span><span class="sxs-lookup"><span data-stu-id="3efd6-p101">Exchange Online Archiving offers users advanced archiving capabilities with the archive mailbox feature. An archive mailbox is a specialized mailbox that appears alongside the users' primary mailbox folders in Outlook or Outlook Web App. Users can access the archive in the same way that they access their primary mailboxes. In addition, they can search both their archives and primary mailboxes.</span></span>
  
<span data-ttu-id="3efd6-p102">Os administradores podem usar o Centro de administração do Exchange (EAC) ou o Windows PowerShell remoto para ativar o recurso de arquivamento para usuários específicos. Confira mais informações em [Habilitar ou desabilitar as caixas de correio de arquivo morto no Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404425).</span><span class="sxs-lookup"><span data-stu-id="3efd6-p102">Administrators can use the Exchange admin center (EAC) or remote Windows PowerShell to enable the archive feature for specific users. For more information, see [Enable or disable archive mailboxes in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404425).</span></span>
  
> [!IMPORTANT]
>  <span data-ttu-id="3efd6-p103">O uso de registro no diário, regras de transporte ou de encaminhamento automático para copiar mensagens para o Arquivamento do Exchange Online com a finalidade de arquivamento não é permitido. >  A caixa de correio de arquivo morto de um usuário destina-se somente a esse usuário. A Microsoft se reserva o direito de negar o arquivamento ilimitado em situações onde a caixa de correio de arquivo morto do usuário é usada para armazenar dados de arquivo morto de outros usuários.</span><span class="sxs-lookup"><span data-stu-id="3efd6-p103">Using journaling, transport rules, or auto-forwarding rules to copy messages to Exchange Online Archiving for the purposes of archiving is not permitted. >  A user's archive mailbox is intended for just that user. Microsoft reserves the right to deny unlimited archiving in instances where a user's archive mailbox is used to store archive data for other users.</span></span> 
  
### <a name="move-messages-to-exchange-online-archiving"></a><span data-ttu-id="3efd6-115">Mover mensagens para o arquivamento do Exchange Online</span><span class="sxs-lookup"><span data-stu-id="3efd6-115">Move messages to Exchange Online Archiving</span></span>

<span data-ttu-id="3efd6-116">Os usuários podem arrastar e soltar as mensagens dos arquivos .pst no arquivamento para terem um acesso online fácil.</span><span class="sxs-lookup"><span data-stu-id="3efd6-116">Users can drag and drop messages from .pst files into the archive, for easy online access.</span></span> <span data-ttu-id="3efd6-117">Os usuários também podem mover automaticamente os itens de email da caixa de correio primária para a caixa de correio de arquivamento, usando as Políticas de arquivamento, para reduzir o tamanho e melhorar o desempenho da caixa de correio primária.</span><span class="sxs-lookup"><span data-stu-id="3efd6-117">Users can also move email items from the primary mailbox to the archive mailbox automatically, using Archive Polices, to reduce the size and improve the performance of the primary mailbox.</span></span> <span data-ttu-id="3efd6-118">Embora este comportamento seja diferente do Arquivamento hospedado do Exchange, que criará uma cópia secundária de cada mensagem no arquivamento, os requisitos de retenção poderão ser conseguidos em qualquer situação.</span><span class="sxs-lookup"><span data-stu-id="3efd6-118">While this behavior is different than Exchange Hosted Archive, which will create a secondary copy of each message in the archive, retention requirements can be achieved in either scenario.</span></span> 
  
### <a name="import-data-to-the-archive"></a><span data-ttu-id="3efd6-119">Importar dados para o arquivamento</span><span class="sxs-lookup"><span data-stu-id="3efd6-119">Import data to the archive</span></span>

<span data-ttu-id="3efd6-120">Os usuários podem importar dados para o arquivamento das seguintes maneiras:</span><span class="sxs-lookup"><span data-stu-id="3efd6-120">Users can import data to the archive in the following ways:</span></span>
  
- <span data-ttu-id="3efd6-121">Importar dados de um arquivo .pst usando o assistente de Importação e Exportação do Outlook.</span><span class="sxs-lookup"><span data-stu-id="3efd6-121">Import data from a .pst file using Outlook's Import and Export wizard.</span></span>
    
- <span data-ttu-id="3efd6-122">Arrastar as mensagens de e-mail dos arquivos .pst para o arquivamento.</span><span class="sxs-lookup"><span data-stu-id="3efd6-122">Drag email messages from .pst files into the archive.</span></span>
    
- <span data-ttu-id="3efd6-123">Arrastar as mensagens de e-mail da caixa de correio primária para o arquivamento.</span><span class="sxs-lookup"><span data-stu-id="3efd6-123">Drag email messages from the primary mailbox into the archive.</span></span>
    
- <span data-ttu-id="3efd6-p105">Permitir que as políticas de arquivamento movam automaticamente as mensagens de email da caixa de correio primária, com base na idade das mensagens. Confira mais informações em [Marcas de retenção e políticas de retenção](https://go.microsoft.com/fwlink/p/?LinkId=314153).</span><span class="sxs-lookup"><span data-stu-id="3efd6-p105">Let archive policies automatically move email messages from the primary mailbox, based on the age of the messages. For more information, see [Retention Tags and Retention Policies](https://go.microsoft.com/fwlink/p/?LinkId=314153).</span></span>
    
> [!NOTE]
> <span data-ttu-id="3efd6-p106">Os administradores também podem usar serviço de Importação do Office 365 para importar arquivos .pst para caixas de correio de arquivo morto baseadas na nuvem dos usuários. Confira mais informações em [Usar o carregamento da rede para importar arquivos PST para o Office 365](https://go.microsoft.com/fwlink/p/?linkid=823074).</span><span class="sxs-lookup"><span data-stu-id="3efd6-p106">Administrators can also use Office 365 Import service to import .pst files to users' cloud-based archive mailboxes. For more information, see [Use network upload to import PST files to Office 365](https://go.microsoft.com/fwlink/p/?linkid=823074).</span></span> 
  
## <a name="deleted-item-recovery"></a><span data-ttu-id="3efd6-128">Recuperação de itens excluídos</span><span class="sxs-lookup"><span data-stu-id="3efd6-128">Deleted item recovery</span></span>

<span data-ttu-id="3efd6-p107">Os usuários poderão restaurar os itens que eles excluíram de qualquer pasta de e-mail em seu arquivo. Quando um item é excluído, ele é mantido na pasta Itens excluídos do arquivo. Ele permanecerá lá até ser removido manualmente pelo usuário ou removido automaticamente pelas políticas de retenção.</span><span class="sxs-lookup"><span data-stu-id="3efd6-p107">Users can restore items they have deleted from any email folder in their archive. When an item is deleted, it is kept in the archive's Deleted Items folder. It remains there until it is manually removed by the user, or automatically removed by retention policies.</span></span>
  
<span data-ttu-id="3efd6-p108">Após um item ter sido removido da pasta Itens excluídos do arquivamento, ele é mantido na pasta Itens recuperáveis por mais 14 dias, até ser removido permanentemente. Os usuários podem recuperar esses itens usando o recurso **Recuperar itens excluídos** no Microsoft Outlook ou no Outlook Web App.</span><span class="sxs-lookup"><span data-stu-id="3efd6-p108">After an item has been removed from the archive's Deleted Items folder, the item is kept in the archive's Recoverable Items folder for an additional 14 days before being permanently removed. Users can recover these items using the **Recover Deleted Items** feature in Microsoft Outlook or Outlook Web App.</span></span> 
  
<span data-ttu-id="3efd6-p109">Se um usuário tiver removido manualmente um item da pasta Itens recuperáveis, um administrador poderá recuperar o item dentro do mesmo período de 14 dias usando o recurso chamado Recuperação de um item. Este recurso permite que os administradores façam uma pesquisa em várias caixas de correio para encontrar os itens removidos, então, usem o cmdlet  `Search-Mailbox` do Windows PowerShell para mover os itens da caixa de correio de descoberta para as caixas de correio dos usuários. Para mais informações, confira [Ativar ou desativar recuperação de item único para uma caixa de correio](https://go.microsoft.com/fwlink/p/?LinkId=314155).</span><span class="sxs-lookup"><span data-stu-id="3efd6-p109">If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same 14 day window, through a feature called Single Item Recovery. This feature allows administrators to conduct a multi-mailbox search to find purged items and then use the  `Search-Mailbox` Windows PowerShell cmdlet to move the items from the discovery mailbox to users' mailboxes. For more information, see [Enable or disable single item recovery for a mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314155).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="3efd6-p110">O período de Recuperação de Item Único é de 14 dias por padrão, mas pode ser personalizado em algumas circunstâncias. >  Se um administrador colocou a caixa de correio de um usuário na Retenção local ou Retenção de Litígio, os itens removidos serão mantidos indefinidamente e o período de 14 dias não se aplicará.</span><span class="sxs-lookup"><span data-stu-id="3efd6-p110">The Single Item Recovery period is 14 days by default, but it can be customized in some circumstances. >  If an administrator has placed a user's mailbox on In-Place Hold or Litigation Hold, purged items are retained indefinitely and the 14-day window does not apply.</span></span> 
  
## <a name="deleted-mailbox-recovery"></a><span data-ttu-id="3efd6-139">Recuperação da caixa de correio excluída</span><span class="sxs-lookup"><span data-stu-id="3efd6-139">Deleted mailbox recovery</span></span>

<span data-ttu-id="3efd6-p111">Quando os administradores excluem os usuários do Exchange Server local, os arquivamentos dos usuários também serão excluídos. Se as caixas de correio de arquivamento excluídas precisarem ser recuperadas, a equipe de suporte do Office 365 poderá fazer essa recuperação. Um arquivamento recuperado conterá todos os e-mails armazenados no momento em que foi excluído.</span><span class="sxs-lookup"><span data-stu-id="3efd6-p111">When administrators delete users from the on-premises Exchange Server, the users' archives are also deleted. If the deleted archive mailboxes need to be recovered, the Office 365 support team can perform this recovery. A recovered archive will contain all of the mail stored in it at the time it was deleted.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="3efd6-p112">Os administradores têm 30 dias a partir do momento em que a caixa de correio de um usuário é apagada para solicitar uma recuperação da caixa de correio de arquivamento. Após 30 dias, a caixa de correio de arquivamento não poderá ser recuperada.</span><span class="sxs-lookup"><span data-stu-id="3efd6-p112">Administrators have 30 days from the time a user's mailbox is deleted to request an archive mailbox recovery. After 30 days, the archive mailbox is not recoverable.</span></span> 
  
## <a name="mailbox-service-redundancy"></a><span data-ttu-id="3efd6-145">Redundância de serviço de caixa de correio</span><span class="sxs-lookup"><span data-stu-id="3efd6-145">Mailbox service redundancy</span></span>

<span data-ttu-id="3efd6-146">As caixas de correio de arquivamento no Arquivamento do Exchange Online são replicadas em várias cópias do banco de dados, em centros de dados da Microsoft geograficamente dispersos, para fornecer a capacidade de restauração dos dados no caso de falha da infraestrutura de mensagens.</span><span class="sxs-lookup"><span data-stu-id="3efd6-146">Archive mailboxes in Exchange Online Archiving are replicated to multiple database copies, in geographically dispersed Microsoft data centers, to provide data restoration capability in the event of a messaging infrastructure failure.</span></span> <span data-ttu-id="3efd6-147">Para as falhas em grande escala, o gerenciamento de continuidade de negócios é iniciado.</span><span class="sxs-lookup"><span data-stu-id="3efd6-147">For large-scale failures, business continuity management is initiated.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="3efd6-148">Disponibilidade do recurso</span><span class="sxs-lookup"><span data-stu-id="3efd6-148">Feature Availability</span></span>

<span data-ttu-id="3efd6-149">Para exibir a disponibilidade de recursos nos planos do Office 365 nas opções autônomas e nas soluções locais, consulte [Descrição do Serviço de Arquivamento do Exchange Online](exchange-online-archiving-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="3efd6-149">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Archiving Service Description](exchange-online-archiving-service-description.md).</span></span>
  
