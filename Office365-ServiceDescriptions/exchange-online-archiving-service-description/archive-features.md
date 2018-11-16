---
title: Recursos de arquivamento no Arquivamento do Exchange Online
ms.author: pebaum
author: pebaum
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
ms.openlocfilehash: f14d8e5c6acefef6fd08cf8e8edf5f33acb9f9df
ms.sourcegitcommit: 433b170b26fbd9c2e9b0e520adfef6f0804df25a
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 11/08/2018
ms.locfileid: "26215346"
---
# <a name="archive-features-in-exchange-online-archiving"></a>Recursos de arquivamento no Arquivamento do Exchange Online

As seções a seguir descrevem os recursos de arquivamento do arquivamento do Microsoft Exchange Online.
  
## <a name="archive-mailbox"></a>Caixa de correio de arquivamento

O Arquivamento do Exchange Online oferece aos usuários recursos avançados de arquivamento com o recurso da caixa de correio de arquivamento. Uma caixa de correio de arquivamento é uma caixa especializada que aparece lado a lado com as pastas primárias da caixa de correio dos usuários no Outlook ou no Outlook Web App. Os usuários podem acessar o arquivamento da mesma forma como acessam suas caixas de correio primárias. Além disso, eles podem pesquisar seus arquivos e caixas de correio primárias.
  
Os administradores podem usar o Centro de administração do Exchange (EAC) ou o Windows PowerShell remoto para ativar o recurso de arquivamento para usuários específicos. Confira mais informações em [Habilitar ou desabilitar as caixas de correio de arquivo morto no Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404425).
  
> [!IMPORTANT]
>  O uso de registro no diário, regras de transporte ou de encaminhamento automático para copiar mensagens para o Arquivamento do Exchange Online com a finalidade de arquivamento não é permitido. >  A caixa de correio de arquivo morto de um usuário destina-se somente a esse usuário. A Microsoft se reserva o direito de negar o arquivamento ilimitado em situações onde a caixa de correio de arquivo morto do usuário é usada para armazenar dados de arquivo morto de outros usuários. 
  
### <a name="move-messages-to-exchange-online-archiving"></a>Mover mensagens para o arquivamento do Exchange Online

Os usuários podem arrastar e soltar mensagens de arquivos. pst para o arquivamento, para facilitar o acesso online. Os usuários também podem mover itens de email da caixa de correio principal para a caixa de correio de arquivo morto automaticamente, usando políticas de arquivamento para reduzir o tamanho e aprimorar o desempenho da caixa de correio principal. Embora esse comportamento é diferente do Exchange Hosted Archive, que criará uma cópia secundária de cada mensagem no arquivo morto, requisitos de retenção podem ser alcançados em um cenário. 
  
### <a name="import-data-to-the-archive"></a>Importar dados para o arquivamento

Os usuários podem importar dados para o arquivamento das seguintes maneiras:
  
- Importar dados de um arquivo .pst usando o assistente de Importação e Exportação do Outlook.
    
- Arrastar as mensagens de e-mail dos arquivos .pst para o arquivamento.
    
- Arrastar as mensagens de e-mail da caixa de correio primária para o arquivamento.
    
- Permitir que as políticas de arquivamento movam automaticamente as mensagens de email da caixa de correio primária, com base na idade das mensagens. Confira mais informações em [Marcas de retenção e políticas de retenção](https://go.microsoft.com/fwlink/p/?LinkId=314153).
    
> [!NOTE]
> Os administradores também podem usar serviço de Importação do Office 365 para importar arquivos .pst para caixas de correio de arquivo morto baseadas na nuvem dos usuários. Confira mais informações em [Usar o carregamento da rede para importar arquivos PST para o Office 365](https://go.microsoft.com/fwlink/p/?linkid=823074). 
  
## <a name="deleted-item-recovery"></a>Recuperação do item excluído

Os usuários poderão restaurar os itens que eles excluíram de qualquer pasta de e-mail em seu arquivo. Quando um item é excluído, ele é mantido na pasta Itens excluídos do arquivo. Ele permanecerá lá até ser removido manualmente pelo usuário ou removido automaticamente pelas políticas de retenção.
  
Após um item ter sido removido da pasta Itens excluídos do arquivamento, ele é mantido na pasta Itens recuperáveis por mais 14 dias, até ser removido permanentemente. Os usuários podem recuperar esses itens usando o recurso **Recuperar itens excluídos** no Microsoft Outlook ou no Outlook Web App. 
  
Se um usuário tiver removido manualmente um item da pasta Itens recuperáveis, um administrador poderá recuperar o item dentro do mesmo período de 14 dias usando o recurso chamado Recuperação de um item. Este recurso permite que os administradores façam uma pesquisa em várias caixas de correio para encontrar os itens removidos, então, usem o cmdlet  `Search-Mailbox` do Windows PowerShell para mover os itens da caixa de correio de descoberta para as caixas de correio dos usuários. Para mais informações, confira [Ativar ou desativar recuperação de item único para uma caixa de correio](https://go.microsoft.com/fwlink/p/?LinkId=314155).
  
> [!NOTE]
>  O período de Recuperação de Item Único é de 14 dias por padrão, mas pode ser personalizado em algumas circunstâncias. >  Se um administrador colocou a caixa de correio de um usuário na Retenção local ou Retenção de Litígio, os itens removidos serão mantidos indefinidamente e o período de 14 dias não se aplicará. 
  
## <a name="deleted-mailbox-recovery"></a>Recuperação da caixa de correio excluída

Quando os administradores excluem os usuários do Exchange Server local, os arquivamentos dos usuários também serão excluídos. Se as caixas de correio de arquivamento excluídas precisarem ser recuperadas, a equipe de suporte do Office 365 poderá fazer essa recuperação. Um arquivamento recuperado conterá todos os e-mails armazenados no momento em que foi excluído.
  
> [!IMPORTANT]
> Os administradores têm 30 dias a partir do momento em que a caixa de correio de um usuário é apagada para solicitar uma recuperação da caixa de correio de arquivamento. Após 30 dias, a caixa de correio de arquivamento não poderá ser recuperada. 
  
## <a name="mailbox-service-redundancy"></a>Redundância de serviço de caixa de correio

Caixas de correio de arquivamento no arquivamento do Exchange Online são replicadas para várias cópias de banco de dados, em centros de dados geograficamente dispersos da Microsoft, para fornecer a capacidade de restauração de dados no caso de falha de infraestrutura de mensagens. Para falhas em grande escala, gerenciamento de continuidade de negócios é iniciado. 
  
## <a name="feature-availability"></a>Disponibilidade do recurso

Para exibir a disponibilidade de recursos nos planos do Office 365 nas opções autônomas e nas soluções locais, consulte [Descrição do Serviço de Arquivamento do Exchange Online](exchange-online-archiving-service-description.md).
  
