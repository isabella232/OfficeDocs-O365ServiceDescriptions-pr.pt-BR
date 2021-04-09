---
title: Recursos de arquivamento em Arquivamento do Exchange Online
ms.author: office365servicedesc
author: pamelaar
manager: gailw
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
description: Saiba mais sobre os recursos de arquivo morto disponíveis Microsoft Exchange Online Arquivamento.
ms.openlocfilehash: cfc5832e3167f29465f387253694e56b66b932fd
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653093"
---
# <a name="archive-features-in-exchange-online-archiving"></a>Recursos de arquivamento em Arquivamento do Exchange Online

As seções a seguir descrevem os recursos de arquivo morto Microsoft Exchange Online Arquivamento.
  
## <a name="archive-mailbox"></a>Caixa de correio de arquivamento

O Arquivamento do Exchange Online oferece aos usuários recursos avançados de arquivamento com o recurso da caixa de correio de arquivamento. Uma caixa de correio de arquivo morto é uma caixa de correio especializada que aparece junto com as pastas de caixa de correio principais dos usuários no Outlook ou no Outlook na Web. Os usuários podem acessar o arquivamento da mesma forma como acessam suas caixas de correio primárias. Além disso, eles podem pesquisar seus arquivos e caixas de correio primárias.
  
Os administradores podem usar o Centro de administração do Exchange (EAC) ou o Windows PowerShell remoto para ativar o recurso de arquivamento para usuários específicos. Confira mais informações em [Habilitar ou desabilitar as caixas de correio de arquivo morto no Exchange Online](/office365/securitycompliance/enable-archive-mailboxes).
  
> [!IMPORTANT]
>  O uso em registro no diário, regras de transporte ou de encaminhamento automático para copiar mensagens para o Arquivamento do Exchange Online com a finalidade de arquivamento não é permitido. <br/>
>  A caixa de correio de arquivo morto de um usuário destina-se somente a esse usuário. A Microsoft reserva o direito de negar o arquivamento ilimitado em situações onde a caixa de correio de arquivo morto do usuário é usada para armazenar dados de arquivo morto de outros usuários.
  
### <a name="move-messages-to-exchange-online-archiving"></a>Mover mensagens para o arquivamento do Exchange Online

Os usuários podem arrastar e soltar as mensagens dos arquivos .pst no arquivamento para terem um acesso online fácil. Os usuários também podem mover automaticamente os itens de email da caixa de correio primária para a caixa de correio de arquivamento, usando as Políticas de arquivamento, para reduzir o tamanho e melhorar o desempenho da caixa de correio primária. 
  
### <a name="import-data-to-the-archive"></a>Importar dados para o arquivamento

Os usuários podem importar dados para o arquivamento das seguintes maneiras:
  
- Importar dados de um arquivo .pst usando o assistente de Importação e Exportação do Outlook.
    
- Arrastar as mensagens de e-mail dos arquivos .pst para o arquivamento.
    
- Arrastar as mensagens de e-mail da caixa de correio primária para o arquivamento.
    
- Permitir que as políticas de arquivamento movam automaticamente as mensagens de email da caixa de correio primária, com base na idade das mensagens. Confira mais informações em [Marcas de retenção e políticas de retenção](/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).
    
> [!NOTE]
> Os administradores também podem usar serviço de Importação do Office 365 para importar arquivos .pst para caixas de correio de arquivo morto baseadas na nuvem dos usuários. Confira mais informações em [Usar o carregamento da rede para importar arquivos PST para o Office 365](/office365/securitycompliance/use-network-upload-to-import-pst-files). 
  
## <a name="deleted-item-recovery"></a>Recuperação de itens excluídos

Os usuários poderão restaurar os itens que eles excluíram de qualquer pasta de e-mail em seu arquivo. Quando um item é excluído, ele é mantido na pasta Itens excluídos do arquivo. Ele permanecerá lá até ser removido manualmente pelo usuário ou removido automaticamente pelas políticas de retenção.
  
Após um item ter sido removido da pasta Itens excluídos do arquivamento, ele é mantido na pasta Itens recuperáveis por mais 14 dias, até ser removido permanentemente. Os usuários podem recuperar esses itens usando o **recurso Recuperar Itens Excluídos** no Microsoft Outlook ou outlook na Web. 
  
Se um usuário tiver removido manualmente um item da pasta Itens recuperáveis, um administrador poderá recuperar o item dentro do mesmo período de 14 dias usando o recurso chamado Recuperação de um item. Este recurso permite que os administradores façam uma pesquisa em várias caixas de correio para encontrar os itens removidos, então, usem o cmdlet  `Search-Mailbox` do Windows PowerShell para mover os itens da caixa de correio de descoberta para as caixas de correio dos usuários. Para mais informações, confira [Ativar ou desativar recuperação de item único para uma caixa de correio](/office365/securitycompliance/use-network-upload-to-import-pst-files).
  
> [!NOTE]
>  O período de Recuperação de Item Único é de 14 dias por padrão, mas pode ser personalizado em algumas circunstâncias. <br/>
>  Se um administrador tiver colocado a caixa de correio de um usuário em uma In-Place de responsabilidade ou de litígio, os itens limpos serão mantidos indefinidamente e a janela de 14 dias não se aplicará. 
  
## <a name="deleted-mailbox-recovery"></a>Recuperação da caixa de correio excluída

Quando os administradores excluem os usuários do Exchange Server local, os arquivamentos dos usuários também serão excluídos. Se as caixas de correio de arquivo morto excluídas precisarem ser recuperadas, a equipe de suporte da Microsoft poderá executar essa recuperação. Um arquivamento recuperado conterá todos os e-mails armazenados no momento em que foi excluído.
  
> [!IMPORTANT]
> Os administradores têm 30 dias a partir do momento em que a caixa de correio de um usuário é apagada para solicitar uma recuperação da caixa de correio de arquivamento. Após 30 dias, a caixa de correio de arquivamento não poderá ser recuperada. 
  
## <a name="mailbox-service-redundancy"></a>Redundância de serviço de caixa de correio

As caixas de correio de arquivamento no Arquivamento do Exchange Online são replicadas em várias cópias do banco de dados, em centros de dados da Microsoft geograficamente dispersos, para fornecer a capacidade de restauração dos dados no caso de falha da infraestrutura de mensagens. Para as falhas em grande escala, o gerenciamento de continuidade de negócios é iniciado. 
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos entre planos, opções autônomas e soluções locais, consulte [Arquivamento do Exchange Online descrição do serviço.](exchange-online-archiving-service-description.md)
