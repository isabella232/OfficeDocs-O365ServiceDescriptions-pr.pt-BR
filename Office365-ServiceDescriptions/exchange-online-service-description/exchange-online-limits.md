---
title: Limites do Exchange Online
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-limits
ms.service: o365-administration
localization_priority: Priority
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 70b38a05-6cfa-4ced-a137-116019262fed
description: Encontre os limites do Exchange Online para diversas áreas de serviço, incluindo limites de catálogo de endereços, limites de armazenamento de caixa de correio e limites de rastreamento de mensagem e relatórios, para mencionar apenas alguns exemplos.
ms.openlocfilehash: 06017db419d1f62c907e5bd5004d8d2eef2f54c1
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173706"
---
# <a name="exchange-online-limits"></a>Limites do Exchange Online

Encontre os limites do Exchange Online para diversas áreas de serviço, incluindo limites de catálogo de endereços, limites de armazenamento de caixa de correio e limites de rastreamento de mensagem e relatórios, para mencionar apenas alguns exemplos.

> [!NOTE]
> Se você precisar de ajuda com uma tarefa, ou se estiver solucionando um problema, talvez considere estes artigos úteis:
> - [Email](https://support.office.com/article/94275804-7147-4332-9ccd-5d421760a9ed) (para obter ajuda para criar e enviar email)
>- [Email no Microsoft 365 para negócios - Ajuda do Administrador](/microsoft-365/admin/email/)
>- [Corrigir problemas do Outlook e do Microsoft 365 com o Assistente de Recuperação e Suporte da Microsoft](https://diagnostics.office.com/)
>- [Relatórios de falha na entrega de email](/Exchange/mail-flow-best-practices/non-delivery-reports-in-exchange-online/non-delivery-reports-in-exchange-online)
>- [Ajuda online do Exchange](/exchange/exchange-online)

Os limites no Microsoft Exchange Online podem ser classificados em uma das seguintes categorias:

- [Limites de catálogo de endereços](#address-book-limits)

- [Limites de armazenamento de caixa de correio](#mailbox-storage-limits)

- [Alertas de capacidade](#capacity-alerts)

- [Limites da pasta da caixa de correio](#mailbox-folder-limits)

- [Limites de mensagem](#message-limits)

- [Receber e enviar limites](#receiving-and-sending-limits)

- [Limites de rastreamento de mensagens e relatórios](#reporting-and-message-trace-limits)

- [Limites de retenção](#retention-limits)

- [Limites de grupos de distribuição](#distribution-group-limits)

- [Limites de regras de diário, transporte e caixa de entrada](#journal-transport-and-inbox-rule-limits)

- [Limites de moderação](#moderation-limits)

- [Limites do Exchange ActiveSync](#exchange-activesync-limits)

> [!IMPORTANT]
> - Os limites aplicados a uma organização Microsoft 365 podem ser diferentes dependendo de quanto tempo a organização está inscrita no serviço.
> - Quando um limite é alterado nos datacenters da Microsoft, pode demorar algum tempo para que a alteração seja aplicada a todos os clientes existentes.
> - Não é possível modificar a maioria desses limites, mas você e seus usuários devem conhecê-los.
> - Esses limites se aplicam a destinatários internos e externos.
> - Por padrão, a Proteção do Exchange Online (EOP) protege as caixas de correio do Exchange Online. Para os limites que se aplicam aos recursos EOP no Exchange Online, confira [Limites da Proteção do Exchange Online](../exchange-online-protection-service-description/exchange-online-protection-limits.md).
> - Para saber mais sobre limites de grupo do Office 365, confira "Como gerenciar meus grupos?" em [Saiba mais sobre os grupos do Microsoft 365](https://go.microsoft.com/fwlink/?linkid=846714).

## <a name="address-book-limits"></a>Limites de catálogo de endereços

- **Limite da lista de endereços**: o número máximo de listas de endereços que podem ser criadas em uma organização do Exchange Online ou Exchange Server 2013. Esse número inclui listas de endereços padrão no Exchange Online, como Todos os Contatos e Todos os Grupos.

    > [!NOTE]
    > Um máximo de 20 listas de endereços podem ser atribuídas a um único catálogo de endereços offline (OAB).

- **Limite do catálogo de endereços offline**: o número máximo de catálogos de endereços offline (OAB) que podem ser criados em uma organização do Exchange Online ou Exchange Server 2013.

- **Limite de políticas de catálogo de endereços**: o número máximo de políticas de catálogo de endereços (ABP) que são criadas em uma organização do Exchange Online ou Exchange Server 2013.

- **Listas de endereços globais**: o número máximo de listas de endereços globais (GAL) que são criadas em uma organização do Exchange Online ou Exchange Server 2013.

### <a name="address-book-limits"></a>Limites de catálogo de endereços

| Recurso | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Limite de lista de endereços|1000|1000|1000|1000|1000|1000|
|Limite do catálogo de endereços offline (OAB)|250|250|250|250|250|250|
|Limite das políticas de catálogo de endereços (ABP)|250|250|250|250|250|250|
|Limite de listas de endereços globais|250|250|250|250|250|250|

### <a name="address-book-limits-across-standalone-plans"></a>Limites de catálogo de endereços em planos autônomos

| Recurso | Exchange Server 2013 | Exchange Online Plano 1 | Plano 2 do Exchange Online | Quiosque do Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Limite de lista de endereços|1000|1000|1000|1000|
|Limite do catálogo de endereços offline (OAB)|250|250|250|250|
|Limite das políticas de catálogo de endereços (ABP)|250|250|250|250|
|Limite de listas de endereços globais|250|250|250|250|

## <a name="mailbox-storage-limits"></a>Limites de armazenamento de caixa de correio

A quantidade de armazenamento de caixa de correio disponível é determinada pelo tipo de caixa de correio e pela licença da assinatura do usuário. Os administradores podem reduzir o tamanho máximo da caixa de correio por usuário ou globalmente.

> [!NOTE]
> O uso de registro no diário, regras de transporte ou regras de encaminhamento automático para copiar mensagens para uma caixa de correio do Exchange Online com a finalidade de arquivamento não é permitido. A caixa de correio de arquivo morto de um usuário destina-se somente a esse usuário. A Microsoft reserva o direito de negar o arquivamento ilimitado em situações onde a caixa de correio de arquivo morto do usuário é usada para armazenar dados de arquivo morto de outros usuários.

### <a name="storage-limits"></a>Limites de armazenamento

| Recurso | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Caixas de correio de usuário|50 GB|50 GB|50 GB|100 GB|100 GB|2 GB|
|Arquivar caixas de correio<sup>7,8</sup>|50 GB|50 GB|50 GB|Ilimitado<sup>1</sup>|Unlimited<sup>1</sup>|Não disponível<sup>4</sup>|
|Caixas de correio compartilhadas<sup>10</sup>|50 GB<sup>2</sup>|50 GB<sup>2</sup>|50 GB<sup>2</sup>|50/100 GB<sup>2,9</sup>|50/100 GB<sup>2,9</sup>|50 GB<sup>2</sup>|
|Caixas de correio de recurso|50 GB<sup>3</sup>|50 GB<sup>3</sup>|50 GB<sup>3</sup>|50 GB<sup>3,9</sup>|50 GB<sup>3,9</sup>|50 GB<sup>3</sup>|
|Caixas de correio de site<sup>5</sup>|50 GB|50 GB|50 GB|50 GB|50 GB|Não disponível|
|Caixas de correio de pastas públicas|100 GB<sup>6</sup>|100 GB<sup>6</sup>|100 GB<sup>6</sup>|100 GB<sup>6</sup>|100 GB<sup>6</sup>|100 GB<sup>6</sup>|
|Caixas de correio de grupo|50 GB|50 GB|50 GB|50 GB|50 GB|50 GB|

> [!NOTE]
> <sup>1</sup> Cada usuário recebe inicialmente 100 GB de armazenamento na caixa de correio de arquivo morto. Quando o arquivamento de expansão automática está ativado, o armazenamento adicional é incluído automaticamente quando é alcançada a capacidade de armazenamento de 100 GB. Confira mais informações em [Visão geral de arquivamento ilimitado no Office 365](/microsoft-365/compliance/unlimited-archiving). <br/> <sup>2</sup> Para acessar uma caixa de correio compartilhada, um usuário deve ter uma licença do Exchange Online, mas a caixa de correio compartilhada não requer uma licença separada. Sem uma licença, as caixas de correio compartilhadas são limitadas a 50 GB. Para aumentar o limite de tamanho para 100 GB, a caixa de correio compartilhada deve ser atribuída uma licença do Plano 2 do Exchange Online ou uma licença do Plano 1 do Exchange Online com uma licença complementar de Arquivamento do Exchange Online. Isso também permitirá que você habilite o arquivamento automático para uma quantidade ilimitada de capacidade de armazenamento de arquivos. Da mesma forma, se você deseja colocar uma caixa de correio compartilhada em retenção de litígio, a caixa de correio compartilhada deve ter uma licença Exchange Online Plano 2 ou uma licença Exchange Online Plano 1 com uma licença complementar de Arquivamento do Exchange Online. Se você deseja aplicar recursos avançados, como Microsoft Defender para Office 365, Descoberta Eletrônica Avançada ou políticas de retenção automática, a caixa de correio compartilhada deve ser licenciada para esses recursos. <br/> <sup>3</sup> Caixas de correio de recursos não necessitam de uma licença. No entanto, sem uma licença, as caixas de correio de recursos são limitadas a 50 GB. Para aumentar o tamanho da caixa de correio, é preciso atribuir uma licença E3 ou E5. Isso aumentará à caixa de correio para 100 GB. <br/> <sup>4</sup> caixas de correio de arquivo morto não são incluídas no Quiosque do Exchange Online. No entanto, podem ser comprados como um suplemento por meio do arquivamento do Exchange Online. Para obter mais informações, confira [A descrição do serviço de Arquivamento do Exchange Online](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md). <br/> <sup>5</sup> Caixas de correio de site foram removidas do Exchange Online e do Microsoft Office SharePoint Online em 2017. <br/> <sup>6</sup> Você está limitado a 1.000 caixas de correio de pasta pública e o tamanho máximo total de todas as caixas de correio de pasta pública é de 100 TB. Caixas de correio de serviços de hierarquia são limitadas a 100 caixas de correio de pastas públicas. <br/> <sup>7</sup> As caixas de correio de arquivo-morto só podem ser usadas para arquivar emails para um só usuário ou uma entidade (como uma caixa de correio compartilhada) para a qual uma licença tenha sido aplicada. É proibido usar caixas de correio de arquivo morto como um meio de armazenar emails de vários usuários ou entidades.  Por exemplo, um administrador de TI não pode criar uma caixa de correio compartilhada e fazer com que os usuários a copiem (pelo campo Cc ou Cco ou por meio de uma regra de transporte) para o expresso fim de arquivamento. Observe que uma caixa de correio compartilhada usada por várias pessoas não armazena os emails desses usuários individuais. Vários usuários têm acesso a ela e enviam emails em nome da caixa de correio compartilhada. Portanto, os únicos emails armazenados na caixa de correio compartilhada são aqueles que foram enviados por ela e para ela, *como* a caixa de correio compartilhada. <br/> <sup>8</sup> Se você criou uma política de retenção no Exchange Online, as mensagens serão automaticamente transferidas para a caixa de correio de arquivo morto de um usuário somente se a caixa de correio primária do usuário for maior que 10 MB. A política de retenção não será executada automaticamente para caixas de correio menores do que 10 MB. <br/> <sup>9</sup> Caixas de correio de recursos não necessitam de uma licença. No entanto, sem uma licença, essas caixas de correio estão limitadas a 50 GB. Para aumentar o tamanho da caixa de correio, é preciso atribuir uma licença E3 ou E5. Isso aumentará à caixa de correio para 100 GB. <br/> <sup>10</sup> Por padrão, as caixas de correio compartilhadas têm uma conta de usuário ativa associada a uma senha gerada pelo sistema (desconhecido). Para bloquear a entrada da conta de caixa de correio compartilhada associada, confira [Bloquear a entrada da conta de caixa de correio compartilhada](/office365/admin/email/create-a-shared-mailbox#block-sign-in-for-the-shared-mailbox-account).

### <a name="storage-limits-across-standalone-plans"></a>Limites de armazenamento em planos autônomos

| Recurso | Exchange Server 2013 | Exchange Online Plano 1 | Plano 2 do Exchange Online | Quiosque do Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Caixas de correio de usuário|2 GB<sup>1</sup>|50 GB|100 GB|2 GB|
|Caixas de correio de arquivo morto<sup>8, 9</sup>|100 GB<sup>1</sup>|50 GB|Ilimitado<sup>2</sup>|Indisponível<sup>5</sup>|
|Caixas de correio compartilhadas<sup>11</sup>|2 GB<sup>1</sup>|50 GB<sup>3</sup>|50 GB<sup>3,10</sup>|50 GB<sup>3</sup>|
|Caixas de correio de recurso|2 GB<sup>1</sup>|50 GB<sup>4</sup>|50 GB<sup>4,10</sup>|50 GB<sup>4</sup>|
|Caixas de correio de pastas públicas|2 GB<sup>6</sup>|50 GB<sup>7</sup>|100 GB<sup>7</sup>|Não disponível|
|Caixas de correio de grupo|50 GB|50 GB|50 GB|50 GB|

> [!NOTE]
> <sup>1</sup> Este é o tamanho da caixa de correio padrão para organizações do Exchange Server 2013. Os administradores podem alterar esse valor para sua organização. Não há um limite máximo de armazenamento para caixas de correio locais. <br/> <sup>2</sup> Cada usuário recebe inicialmente 100 GB de armazenamento na caixa de correio de arquivo morto. Quando o arquivamento de expansão automática está ativado, o armazenamento adicional é incluído automaticamente quando é alcançada a capacidade de armazenamento de 100 GB. Confira mais informações em [Visão geral de arquivamento ilimitado no Office 365](/microsoft-365/compliance/unlimited-archiving). Confira o [Roteiro do Microsoft 365](https://go.microsoft.com/fwlink/?LinkId=509914) para obter detalhes sobre a disponibilidade para arquivamento de expansão automática. <br/> <sup>3</sup> Para acessar uma caixa de correio compartilhada, o usuário deve ter uma licença do Exchange Online, mas a caixa de correio compartilhada não requer uma licença separada. Sem uma licença, as caixas de correio compartilhadas são limitadas a 50 GB. Para aumentar o limite de tamanho para 100 GB, a caixa de correio compartilhada deve ser atribuída uma licença do Plano 2 do Exchange Online ou uma licença do Plano 1 do Exchange Online com uma licença complementar de Arquivamento do Exchange Online. Isso também permitirá que você habilite o arquivamento automático para uma quantidade ilimitada de capacidade de armazenamento de arquivos. Da mesma forma, se você deseja colocar uma caixa de correio compartilhada em retenção de litígio, a caixa de correio compartilhada deve ter uma licença Exchange Online Plano 2 ou uma licença Exchange Online Plano 1 com uma licença complementar de Arquivamento do Exchange Online. Se você deseja aplicar recursos avançados, como Microsoft Defender para Office 365, Descoberta Eletrônica Avançada ou políticas de retenção automática, a caixa de correio compartilhada deve ser licenciada para esses recursos. <br/> <sup>4</sup> Caixas de correio de recursos não necessitam de uma licença. No entanto, sem uma licença, as caixas de correio de recursos são limitadas a 50 GB. Para aumentar o tamanho da caixa de correio, é preciso atribuir uma licença do Exchange Online plano 2. Isso aumentará à caixa de correio para 100 GB. <br/> <sup>5</sup> caixas de correio de arquivo morto não são incluídas no Quiosque do Exchange Online. No entanto, podem ser comprados como um suplemento por meio do arquivamento do Exchange Online. Para obter mais informações, confira [A descrição do serviço de Arquivamento do Exchange Online](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md). <br/> <sup>6</sup> Este é o tamanho de caixa de correio padrão para organizações do Microsoft Exchange Server 2013. Os administradores podem alterar esse valor para sua organização. No Exchange Server 2013, você está limitado a cem caixas de correio de pasta pública, e o tamanho máximo total de todas as caixas de correio de pasta pública é de 50 TB. <br/> <sup>7</sup> No Exchange Online, você está limitado a 1.000 caixas de correio de pasta pública, e o tamanho total máximo de todas as caixas de correio de pasta pública é de 50 TB.  <br/> <sup>8</sup> As caixa de correio de arquivo morto pode ser usada apneas para arquivar emails para um único usuário ou entidade na qual uma licença foi aplicada. É proibido o uso de caixas de correio de arquivo morto como meio de armazenamento de emails de vários usuários ou entidades. Por exemplo, os administradores de TI não podem criar caixas de correio compartilhadas e fazer com que os usuários copiem (com o campo Cc ou Cco ou com uma regra de transporte) uma caixa de correio compartilhada explicitamente para o arquivamento. <br/> <sup>9</sup> Se você criou uma política de retenção no Exchange Online, as mensagens serão automaticamente transferidas para a caixa de correio de arquivo morto de um usuário somente se a caixa de correio primária do usuário for maior que 10 MB. A política de retenção não será executada automaticamente para caixas de correio menores do que 10 MB. <br/> <sup>10</sup> Caixas de correio compartilhadas e de recursos não requerem uma licença. No entanto, sem uma licença, essas caixas de correio estão limitadas a 50 GB. Para aumentar o tamanho da caixa de correio, é importante atribuir uma licença do Exchange Online plano 2. Isso aumentará à caixa de correio para 100 GB. <br/> <sup>11</sup> Por padrão, as caixas de correio compartilhadas têm uma conta de usuário ativa associada a uma senha gerada pelo sistema (desconhecida). Para bloquear a entrada da conta de caixa de correio compartilhada associada, confira [Bloquear a entrada da conta de caixa de correio compartilhada](/office365/admin/email/create-a-shared-mailbox#block-sign-in-for-the-shared-mailbox-account).

## <a name="capacity-alerts"></a>Alertas de capacidade

O Exchange Online oferece três tipos de notificações quando uma caixa de correio do usuário atinge ou está se aproximando de sua capacidade máxima:

- **Aviso**: o usuário recebe um email avisando que a caixa de correio está se aproximando do limite máximo de tamanho. Esse aviso se destina a incentivar os usuários a excluir emails indesejados.

- **Proibir Envio**: o usuário recebe um email de notificação de proibição de envio quando o limite de tamanho da caixa de correio é atingido. O usuário não pode enviar novas mensagens até que um email suficiente seja excluído para deixar a caixa de correio abaixo do limite de tamanho.

- **Proibir o Envio/Recebimento**: o Exchange Online rejeita qualquer mensagem recebida quando o limite de tamanho da caixa de correio é atingido, e envia uma notificação de falha na entrega (NDR) ao remetente. O remetente tem a opção de tentar reenviar o email mais tarde. Para receber mensagens novamente, o usuário deve excluir emails até que a caixa de correio fique abaixo do limite de tamanho.

### <a name="capacity-alerts"></a>Alertas de capacidade

| Recurso | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Aviso|49 GB|49 GB|49 GB|98 GB|98 GB|1,96 GB|
|Proibir Envio|49.5 GB|49.5 GB|49,5 GB|99 GB|99 GB|1,98 GB|
|Proibir Envio/Recebimento|50 GB|50 GB|50 GB|100 GB|100 GB|2 GB|

### <a name="capacity-alerts-across-standalone-plans"></a>Alertas de capacidade em planos autônomos

| Recurso | Exchange Server 2013 | Exchange Online Plano 1 | Plano 2 do Exchange Online | Quiosque do Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Aviso|1,9 GB<sup>1</sup>|49 GB|98 GB|1,96 GB|
|Proibir Envio|2 GB<sup>1</sup>|49,5 GB|99 GB|1,98 GB|
|Proibir Envio/Recebimento|2,3 GB<sup>1</sup>|50 GB|100 GB|2 GB|

> [!NOTE]
> <sup>1</sup>Este é o valor padrão para organizações do Exchange Server 2013. Os administradores podem alterar esse valor para sua organização.

## <a name="mailbox-folder-limits"></a>Limites da pasta da caixa de correio

Estes limites são para limitar as caixas de correios para tamanhos conhecidos que podem ser suportados pelo Exchange Online. O objetivo desses limites é impedir uma quantidade infinita de itens de caixa de correio por pasta, de pastas por caixa de correio ou de pastas públicas por organização do Exchange Online. Por razões práticas, os limites da pasta da caixa de correio são ilimitadas e o suficiente para suportar a maioria das caixas de correio do Exchange Online e caixas de correio locais que são migradas para o Exchange Online.

- **Número máximo de mensagens por pasta de caixa de correio**: especifica o número máximo de mensagens para uma pasta de caixa de correio. Novas mensagens não poderão ser entregues ou salvas em uma pasta quando esse limite for atingido.

- **Aviso para o número de mensagens por pasta de caixa de correio**: especifica o número de mensagens que uma pasta de caixa de correio pode conter antes que o Exchange Online envie uma mensagem de aviso ao proprietário da caixa de correio. Quando esta cota é alcançada, as mensagens de aviso são enviadas diariamente.

- **Número máximo de mensagens por pasta na pasta de Itens Recuperáveis** especifica o número de mensagens que pode ser armazenado em cada pasta na pasta de Itens Recuperáveis. Quando uma pasta excede este limite, ela não pode mais armazenar novas mensagens. Por exemplo, se a pasta Excluídos na pasta de Itens Recuperáveis tiver excedido o limite de mensagens e o proprietário da caixa de correio tentar excluir permanentemente itens da mesma, a exclusão irá falhar.

- **Aviso para o número de mensagens por pasta na pasta Itens Recuperáveis**: especifica o número de mensagens que cada pasta na pasta Itens Recuperáveis pode conter antes que o Exchange Online registre um evento no log de eventos do aplicativo.

- **Número máximo de subpastas por pasta da caixa de correio**: especifica o número máximo de subpastas que podem ser criadas em uma pasta da caixa de correio. O proprietário da caixa de correio não conseguirá criar uma nova subpasta quando este limite for atingido.

- **Aviso para o número de subpastas por pasta da caixa de correio**: especifica o número de subpastas que podem ser criadas em uma pasta da caixa de correio antes que o Exchange Online envie uma mensagem de aviso ao proprietário da caixa de correio. Quando esta cota é alcançada, as mensagens de aviso são enviadas diariamente.

- **Nível máximo de hierarquia da pasta**: especifica o número máximo de níveis na hierarquia da pasta de uma caixa de correio. O proprietário da caixa de correio não poderá criar outro nível na hierarquia de pastas da pasta da caixa de correio quando esse limite for atingido.

- **Aviso para profundidade de hierarquia de pasta**: especifica o número de níveis na hierarquia de pasta de uma pasta de caixa de correio que podem ser criados antes que o Exchange Online envie uma mensagem de aviso ao proprietário da caixa de correio. Quando esta cota é alcançada, as mensagens de aviso são enviadas diariamente.

- **Número máximo de pastas públicas**: especifica o número máximo de pastas públicas na hierarquia de pastas públicas completa. Quando este limite é atingido, as pastas públicas existentes devem ser excluídas antes de novas pastas poderem ser criadas.

- **Número máximo de subpastas por pasta pública**: especifica o número máximo de subpastas que podem ser criadas em uma pasta pública. Novas subpastas não podem ser criadas em uma pasta pública quando esse limite é atingido.

- **Aviso para o número de subpastas por pasta pública**: especifica o número de subpastas que podem ser criadas em uma pasta pública antes que o Exchange Online envie uma mensagem de aviso ao proprietário da pasta. Se não existir nenhum proprietário, as mensagens de aviso serão enviadas para usuários com permissões de Proprietário. Quando esta cota é alcançada, as mensagens de aviso são enviadas diariamente.

### <a name="mailbox-folder-limits"></a>Limites da pasta da caixa de correio

| Recurso | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Número máximo de mensagens por pasta de caixa de correio|1 milhão|1 milhão|1 milhão|1 milhão|1 milhão|1 milhão|
|Aviso para o número de mensagens por pasta da caixa de correio|900.000|900.000|900.000|900.000|900.000|900.000|
|Número máximo de mensagens por pasta na pasta de Itens Recuperáveis|3 milhões|3 milhões|3 milhões|3 milhões|3 milhões|3 milhões|
|Cota de armazenamento da pasta Itens Recuperáveis na caixa de correio primária (não em espera)|30 GB|30 GB|30 GB|30 GB|30 GB|30 GB|
|Cota de armazenamento da pasta Itens Recuperáveis na caixa de correio primária (em espera)|100 GB|100 GB|100 GB|100 GB|100 GB|100 GB|
|Cota de armazenamento da pasta Itens Recuperáveis na caixa de correio de arquivo morto (não em espera)|30 GB|30 GB|30 GB|Unlimited<sup>2</sup>|Unlimited<sup>2</sup>|30 GB|
|Cota de armazenamento da pasta Itens Recuperáveis na caixa de correio de arquivo morto (em espera)|100 GB<sup>1</sup>|100 GB<sup>1</sup>|100 GB<sup>1</sup>|Unlimited<sup>2</sup>|Unlimited<sup>2</sup>|100 GB<sup>1</sup>|
|Aviso para o número de mensagens por pasta na pasta de Itens Recuperáveis|2,75 milhões|2,75 milhões|2,75 milhões|2,75 milhões|2,75 milhões|2,75 milhões|
|Número máximo de subpastas por pasta de caixa de correio|10,000<sup>2</sup>|10,000<sup>2</sup>|10,000<sup>2</sup>|10,000<sup>2</sup>|10,000<sup>2</sup>|10,000<sup>2</sup>|
|Aviso para o número de subpastas por pasta de caixa de correio|9000|9000|9000|9000|9000|9000|
|Profundidade máxima de hierarquia de pasta|300|300|300|300|300|300|
|Aviso para a profundidade de hierarquia de pasta|250|250|250|250|250|250|
|Número máximo de pastas públicas|US$ 500.000|US$ 500.000|US$ 500.000|US$ 500.000|US$ 500.000|Não disponível|
|Número máximo de subpastas por pasta pública|10.000|10.000|10.000|10.000|10.000|Não disponível|
|Aviso para o número de subpastas por pasta pública|9000|9000|9000|9000|9000|Não disponível|

> [!NOTE]
> <sup>1</sup> Esta é a cota de armazenamento da pasta Itens Recuperáveis, não a cota da caixa de correio de arquivo morto inteira. A cota de armazenamento da caixa de correio de arquivo morto é ilimitada para usuários com uma licença do Exchange Online Plano 2 ou para usuários que têm uma licença do Exchange Online Plano 1 e de Arquivamento do Exchange Online. Confira informações sobre aumentar a cota da pasta itens recuperáveis, confira [aumente a cota da pasta itens recuperáveis para caixas de correio em espera](/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold). <br/> <sup>2</sup> A cota de armazenamento inicial da pasta Itens Recuperáveis em uma caixa de correio de arquivo morto é de 100 GB. Quando o arquivamento de expansão automática está ativado, o armazenamento adicional é incluído automaticamente quando é alcançada a capacidade da pasta de Itens Recuperáveis. Confira mais informações em [Visão geral de arquivamento ilimitado no Office 365](/microsoft-365/compliance/unlimited-archiving). Confira o [Roteiro do Microsoft 365](https://go.microsoft.com/fwlink/?LinkId=509914) para obter detalhes sobre a disponibilidade de arquivamento de expansão automática.
> <sup>2</sup> Este é um limite do repositório; é uma das restrições de formato da caixa de correio. Só pode haver 10.000 pastas filhas diretas para um determinado pai. Isso se aplica independentemente da migração ou outros clientes criando pastas.

### <a name="mailbox-folder-limits-across-standalone-plans"></a>Limites da pasta da caixa de correio nos planos autônomos

| Recurso | Exchange Server 2013 | Exchange Online Plano 1 | Plano 2 do Exchange Online | Quiosque do Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Número máximo de mensagens por pasta de caixa de correio|Sem limites<sup>1</sup>|1 milhão|1 milhão|1 milhão|
|Aviso para o número de mensagens por pasta da caixa de correio|Sem limites|900.000|900.000|900.000|
|Número máximo de mensagens por pasta na pasta de Itens Recuperáveis|Sem limite|3 milhões|3 milhões|3 milhões|
|Cota de armazenamento da pasta Itens Recuperáveis na caixa de correio primária (não em espera)|30 GB|30 GB|30 GB|30 GB|
|Cota de armazenamento da pasta Itens Recuperáveis na caixa de correio primária (em espera)|100 GB|100 GB|100 GB|100 GB|
|Cota de armazenamento da pasta Itens Recuperáveis na caixa de correio de arquivo morto (não em espera)|30 GB|30 GB|30 GB|30 GB|
|Cota de armazenamento da pasta Itens Recuperáveis na caixa de correio de arquivo morto (em espera)|100 GB<sup>2</sup>|100 GB<sup>2</sup>|Unlimited<sup>3</sup>|Unlimited<sup>3</sup>|
|Aviso para o número de mensagens por pasta na pasta de Itens Recuperáveis|Sem limite|2,75 milhões|2,75 milhões|2,75 milhões|
|Número máximo de subpastas por pasta de caixa de correio|Sem limites|1000|1000|1000|
|Aviso para o número de subpastas por pasta de caixa de correio|Sem limites|900|900|900|
|Profundidade máxima de hierarquia de pasta|Sem limites|300|300|300|
|Aviso para a profundidade de hierarquia de pasta|Sem limites|250|250|250|
|Número máximo de pastas públicas|1.000.000|100.000|100.000|Não disponível|
|Número máximo de subpastas por pasta pública|N/D|1.000|1.000|Não disponível|
|Aviso para o número de subpastas por pasta pública|N/D|900|900|Não disponível|

> [!NOTE]
> <sup>1</sup> A Microsoft recomenda até 1.000.000 mensagens por pasta da caixa de correio. > <br/> <sup>2</sup> Esta é a cota de armazenamento da pasta Itens Recuperáveis, não a cota da caixa de correio de arquivo morto inteira.  A cota de armazenamento da caixa de correio de arquivo morto é ilimitada para usuários com uma licença do Exchange Online Plano 2 ou para usuários que têm uma licença do Exchange Online Plano 1 e de Arquivamento do Exchange Online. Confira informações sobre aumentar a cota da pasta itens recuperáveis, confira [aumente a cota da pasta itens recuperáveis para caixas de correio em espera](/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold). <br/> <sup>3</sup> A cota de armazenamento inicial da pasta Itens Recuperáveis em uma caixa de correio de arquivo morto é de 100 GB. Quando o arquivamento de expansão automática está ativado, o armazenamento adicional é incluído automaticamente quando é alcançada a capacidade da pasta de Itens Recuperáveis. Confira mais informações em [Visão geral de arquivamento ilimitado no Office 365](/microsoft-365/compliance/unlimited-archiving). Confira o [Roteiro do Microsoft 365](https://go.microsoft.com/fwlink/?LinkId=509914) para obter detalhes sobre a disponibilidade de arquivamento de expansão automática.

## <a name="message-limits"></a>Limites de mensagem

Os limites a seguir são aplicados a todas as mensagens de email.

- **Limite de tamanho de mensagem**: os limites de tamanho de mensagem são necessários para evitar que mensagens grandes bloqueiem a entrega de outras mensagens e afetem o desempenho do serviço para todos os usuários. Esses limites incluem anexos e são aplicáveis em toda a organização a todas as mensagens (de entrada, de saída e internas). Mensagens maiores do que esse limite não serão entregues, e o remetente receberá uma NDR (notificação de falha na entrega). Embora os limites de tamanho de mensagem não possam ser configurados como maiores, menores ou para usuários individuais, os administradores também podem criar regras de transporte para limitar o tamanho máximo de qualquer anexo individual. Para saber mais, confira [Microsoft suporta mensagens de email maiores](https://go.microsoft.com/fwlink/?linkid=2144144).

    > [!NOTE]
    > Alguns clientes de email podem ter limites de tamanho de mensagem mais baixos ou podem limitar o tamanho de um anexo de arquivo individual a um valor inferior ao limite de tamanho de mensagem do Exchange Online.

- **Limite de tamanho do cabeçalho da mensagem**: especifica o tamanho máximo de todos os campos do cabeçalho da mensagem em uma mensagem. O limite atual é 256 KB. Se o tamanho total de todos os cabeçalhos de mensagem exceder 256 KB, o Exchange Online rejeitará a mensagem com o erro "552 5.3.4 O tamanho do cabeçalho excedeu o tamanho máximo fixo." O tamanho do corpo ou dos anexos da mensagem não é considerado. Como os campos de cabeçalho são texto não criptografado, o tamanho do cabeçalho é determinado pelo número de caracteres em cada campo de cabeçalho e pelo número total de campos de cabeçalho. Cada caractere de texto consome 1 byte.

- **Limite de tamanho do assunto**:o número máximo de caracteres de texto permitido na linha de assunto de uma mensagem de email.

- **Limite de anexos de arquivo**: o número máximo de anexos de arquivo permitido em uma mensagem de email. Mesmo se o tamanho total de todos os anexos de arquivo não violar o limite de tamanho da mensagem, ainda haverá um limite na quantidade de anexos permitida na mensagem. Este limite é controlado pelo limite da mensagem em várias partes.

- **Limite de tamanho de anexo de arquivo**: o tamanho máximo de arquivo de um único anexo.

    > [!NOTE]
    > Esse é o tamanho máximo de um único anexo. Programas de clientes individuais, incluindo o Outlook na Web, podem limitar o tamanho dos anexos abaixo desse máximo. O Exchange ActiveSync não implementa limites de tamanho de anexos para anexos individuais. O tamanho total de todos os anexos para uma mensagem do Exchange ActiveSync deve ser menor do que o limite de tamanho de mensagem.

- **Limite de mensagem multiparte**: o número máximo de partes do corpo da mensagem que são permitidas em uma mensagem MIME multiparte. Esse limite também controla a quantidade máxima de anexos permitidos em uma mensagem.

- **Limite de profundidade de mensagem incorporada**: o número máximo de mensagens de email encaminhadas que são permitidas em uma mensagem de email.

### <a name="message-limits"></a>Limites de mensagem

| Recurso | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Limite de tamanho de mensagem - Outlook|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|
|Limite de tamanho de mensagem - OWA|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|
|Limite de tamanho de mensagem - Outlook para Mac|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|
|Limite de tamanho de mensagem - migração|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|
|Limite de tamanho de mensagem - Outlook para iOS e Android | 33 MB| 33 MB| 33 MB| 33 MB| 33 MB| 33 MB|
|Limite de tamanho para mensagens criptografadas (para assinantes usando a Criptografia de Mensagem do Office 365 com novas capacidades)<sup>5</sup>|25 MB|25 MB|25 MB|25 MB|25 MB|25 MB|
|Limite de tamanho para mensagens criptografadas (para assinantes usando a versão herdada da Criptografia de Mensagem do Office 365)<sup>5</sup>|25 MB|25 MB|25 MB|25 MB|25 MB|25 MB|
|Limite de comprimento de assunto|255 caracteres|255 caracteres|255 caracteres|255 caracteres|255 caracteres|255 caracteres|
|Limite de anexos de arquivo|250 anexos|250 anexos|250 anexos|250 anexos|250 anexos|250 anexos|
|Limite de tamanho de anexo de arquivo - Outlook|150 MB|150 MB|150 MB|150 MB|150 MB|150 MB|
|Limite de tamanho de anexo de arquivo - OWA |112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|
|Limite de tamanho de anexo de arquivo - Outlook para Mac|150 MB|150 MB|150 MB|150 MB|150 MB|150 MB|
|Limite de tamanho de anexo de arquivo - Outlook para iOS e Android|33 MB |33 MB |33 MB |33 MB |33 MB |33 MB |
|Limite de mensagem com várias partes|250 partes|250 partes|250 partes|250 partes|250 partes|250 partes|
|Limite de profundidade de mensagem inserida|30 mensagens inseridas|30 mensagens inseridas|30 mensagens inseridas|30 mensagens inseridas|30 mensagens inseridas|30 mensagens inseridas|

> [!NOTE]
> <sup>1</sup> O tamanho máximo padrão da mensagem para as caixas de correio da Microsoft é 25 MB. Os administradores da Microsoft podem especificar um limite personalizado entre 1 MB e 150 MB. No entanto, o tamanho da mensagem que você pode enviar ou receber também depende do que seu cliente ou solução de email suporta. Para obter mais informações sobre como personalizar o tamanho máximo permitido de mensagem para sua organização, confira a[Microsoft oferece suporte a mensagens de email maiores](https://go.microsoft.com/fwlink/?linkid=2144144). 
<br/> <sup>2</sup>É possível enviar e receber mensagens de até 150 MB entre usuários (onde a mensagem nunca sai dos datacenters da Microsoft). As mensagens roteadas fora dos datacenters da Microsoft estão sujeitas a um aumento adicional de 33% na codificação da tradução, caso em que o tamanho máximo da mensagem é 112 MB. <br/> 
<sup>3</sup> O OWA considera a possibilidade de sua mensagem estar sujeita a um aumento de codificação de 33% e restringe o tamanho da mensagem que você pode enviar a 25% menos do que a configuração configurada. Por exemplo, se você personalizar as configurações para um tamanho de mensagem máximo de 100 MB, não será possível enviar mensagens maiores do que 75 MB. 
<br/> <sup>4</sup> O tamanho das mensagens a serem movidas para o Exchange Online será calculado pelo Exchange Online. Versões do Exchange anteriores ao Exchange Server 2013 podem relatar um tamanho menor de item. Esse limite se aplica a migrações baseadas em movimentação usando qualquer Serviço de Replicação de Caixa de Correio do Exchange compatível. Outros métodos de migração (Cutover, Staged, IMAP, PST) e outras ferramentas de terceiros são limitados pelo limite de tamanho de mensagem geral. <br/> 
<sup>5</sup> Para obter informações sobre OME com novos recursos, confira [Configurar novos recursos da Criptografia de Mensagens do Office 365 criados com base na Proteção de Informações do Azure](https://support.office.com/article/7ff0c040-b25c-4378-9904-b1b50210d00e).<br/> 
<sup>6</sup> Os anexos de arquivo clássicos têm um limite de 112 MB, mas os anexos de arquivo do OneDrive podem ter até 2 GB.


### <a name="message-limits-across-standalone-options"></a>Limites de mensagem em opções autônomas

| Recurso | Exchange Server 2013 | Exchange Online Plano 1 | Plano 2 do Exchange Online | Quiosque do Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Limite de tamanho de mensagem - Outlook|10 MB<sup>4</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>2</sup>|
|Limite de tamanho de mensagem - OWA|10 MB<sup>4</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|150 MB<sup>1, 2</sup>|
|Limite de tamanho de mensagem - Outlook para Mac|10 MB<sup>4</sup>|150 MB|150 MB||
|Limite de tamanho de mensagem - migração|Não aplicável|150 MB <sup>5</sup>|150 MB <sup>5</sup>|150 MB <sup>5</sup>|
|Limite de tamanho de mensagem - Outlook para iOS e Android |25 MB |33 MB |33 MB |33 MB |
|Limite de tamanho para mensagens criptografadas (para assinantes usando a Criptografia de Mensagem do Office 365 com novas capacidades)<sup>6</sup>|150 MB|150 MB|150 MB|150 MB|
|Limite de tamanho para mensagens criptografadas (para assinantes usando a versão herdada da Criptografia de Mensagem do Office 365)<sup>6</sup>|25 MB|25 MB|25 MB|25 MB|
|Limite de comprimento de assunto|255 caracteres|255 caracteres|255 caracteres|255 caracteres|
|Limite de anexos de arquivo|1024 attachments<sup>4</sup>|250 anexos|250 anexos|250 anexos|
|Limite de tamanho de anexo de arquivo - Outlook|35 MB<sup>4</sup>|150 MB|150 MB|150 MB|
|Limite de tamanho de anexo de arquivo - OWA|35 MB<sup>4</sup>|112 MB<sup>3</sup>|112 MB<sup>3</sup>|112 MB<sup>3</sup>|
|Limite de tamanho de anexo de arquivo - Outlook para Mac|35 MB<sup>4</sup>|150 MB|150 MB|35 MB|
|Limite de tamanho de anexo de arquivo - Outlook para iOS e Android|25 MB |33 MB|33 MB|33 MB|
|Limite de mensagem com várias partes|250 partes|250 partes|250 partes|250 partes|
|Limite de profundidade de mensagem inserida|30 mensagens inseridas|30 mensagens inseridas|30 mensagens inseridas|30 mensagens inseridas|

> [!NOTE]
> <sup>1</sup> Os administradores da Microsoft podem especificar um limite personalizado entre 1 MB e 150 MB. No entanto, o tamanho da mensagem que você pode enviar ou receber também depende do que seu cliente ou solução de email suporta. Para obter mais informações sobre como personalizar o tamanho máximo permitido de mensagem para sua organização, confira a[Microsoft oferece suporte a mensagens de email maiores](https://go.microsoft.com/fwlink/?linkid=2144144). <br/> <sup>2</sup>É possível enviar e receber mensagens de até 150 MB entre usuários (onde a mensagem nunca sai dos datacenters da Microsoft). As mensagens roteadas fora dos datacenters da Microsoft estão sujeitas a um aumento adicional de 33% na codificação da tradução, caso em que o tamanho máximo da mensagem é 112 MB. <br/> 
<sup>3</sup> O OWA considera a possibilidade de sua mensagem estar sujeita a um aumento de codificação de 33% e restringe o tamanho da mensagem que você pode enviar a 25% menos do que a configuração configurada. Por exemplo, se você personalizar as configurações para um tamanho de mensagem máximo de 100 MB, não será possível enviar mensagens maiores do que 75 MB. <br/> 
<sup>4</sup> Este é o limite padrão para organizações do Exchange Server 2013. Os administradores podem alterar esse valor para sua organização. <br/> 
<sup>5</sup> O tamanho das mensagens a serem movidas para o Exchange Online será calculado pelo Exchange Online. Versões do Exchange anteriores ao Exchange Server 2013 podem relatar um tamanho menor de item. <br/> 
<sup>6</sup> Para obter informações sobre OME com os novos recursos, confira [Configurar novos recursos da Criptografia de Mensagens do Office 365 criados sobre a Proteção de Informações do Azure](https://support.office.com/article/7ff0c040-b25c-4378-9904-b1b50210d00e).

## <a name="receiving-and-sending-limits"></a>Receber e enviar limites

Os limites de recebimento e envio são aplicados para combater spam e worms em emails em massa ou vírus. Esses limites ajudam a proteger a integridade dos seus sistemas e a manter seus usuários seguros.

### <a name="receiving-limits"></a>Limites de recebimento

Os limites de recebimento se aplicam ao número de mensagens que um usuário, grupo ou pasta pública pode receber por hora. Isso se aplica a mensagens recebidas da Internet e de servidores locais. Se exceder o limite de recebimento, os emails enviados para essa caixa de correio receberão uma notificação de falha na entrega informando que a caixa de correio excedeu o limite máximo de entrega. Após uma hora, o limite será atualizado, e a caixa de correio poderá receber mensagens novamente.

| Recurso | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Mensagens recebidas|3,600 mensagens por hora|3,600 mensagens por hora|3,600 mensagens por hora|3,600 mensagens por hora|3.600 mensagens por hora|3.600 mensagens por hora|

### <a name="sending-limits"></a>Limites de envio

Os limites de envio se aplicam ao número de destinatários, número de mensagens e número de destinatários por mensagem que um usuário pode enviar da própria conta do Exchange Online.

> [!NOTE]
> Para grupos de distribuição armazenados no catálogo de endereços de uma organização, o grupo é contado como um destinatário. Para grupos de distribuição armazenados na pasta Contatos de uma caixa de correio, os membros do grupo são contados individualmente.

- **Limite de taxa de destinatário**: para desencorajar a entrega de mensagens em massa não solicitadas, o Exchange Online tem limites de destinatário que evitam que usuários e aplicativos enviem grandes volumes de email. Esses limites são aplicados por usuário para todas as mensagens de saída e internas.

    > [!NOTE]
    > Os clientes do Exchange Online que precisam enviar emails comerciais em massa legítimos (por exemplo, boletins informativos para clientes) devem usar provedores de terceiros especializados nesses serviços.

- **Limite de destinatários**: este é o número máximo de destinatários permitidos nos campos Para :, Cc: e Cco: para uma única mensagem de email.

    > [!NOTE]
    > Para o limite de taxa de destinatários e o limite de destinatários, um grupo de distribuição que está armazenado no catálogo de endereços compartilhado da organização conta como um destinatário. Em uma lista de distribuição pessoal, cada destinatário é contado separadamente.

- **Limite de endereço de proxy de destinatário**: o limite de endereço de proxy de destinatário é o número máximo de aliases (endereços de email) que uma caixa de correio de destinatário pode ter. 

- **Limite de taxa de mensagem**: os limites de taxa de mensagem determinam quantas mensagens um usuário pode enviar de sua conta do Exchange Online em um período de tempo especificado. Esse limite ajuda a evitar o consumo excessivo de recursos do sistema por um único remetente. Se um usuário envia mensagens a uma taxa que excede o limite por meio de envio de cliente SMTP, as mensagens são rejeitadas e o cliente precisa repetir.

#### <a name="sending-limits"></a>Limites de envio

| Recurso | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Limite de taxa de destinatário<sup>1</sup>|10.000 destinatários por dia|10.000 destinatários por dia|10.000 destinatários por dia|10.000 destinatários por dia|10.000 destinatários por dia|10.000 destinatários por dia|
|Limite de destinatário<sup>2</sup>|Personalizável para até 1000 destinatários|Personalizável para até 1000 destinatários|Personalizável para até 1000 destinatários|Personalizável para até 1000 destinatários|Personalizável para até 1000 destinatários|Personalizável para até 1000 destinatários|
|Limite de endereço proxy do destinatário|400|400|400|400|400|400|
|Limite de taxa de mensagem <sup>3</sup>|30 mensagens por minuto|30 mensagens por minuto|30 mensagens por minuto|30 mensagens por minuto|30 mensagens por minuto|30 mensagens por minuto|

> [!NOTE]
> <sup>1</sup> Depois que o limite de taxa de destinatário é atingido, as mensagens não podem ser enviadas da caixa de correio até que o número de destinatários que receberam mensagens nas últimas 24 horas fique abaixo do limite. Por exemplo, um usuário envia uma mensagem de email para 5.000 destinatários às 09:00, depois envia outra mensagem para 2.500 destinatários às 10:00 e, em seguida, envia outra mensagem para 2.500 destinatários às 11:00, atingindo o limite de 10.000 mensagens. O usuário não será capaz de enviar mensagens novamente até 09:00 do próximo dia.  
> <sup>2</sup>É possível personalizar os limites de destinatários entre 1 e 1.000 para caixas de correio existentes e para novas caixas de correio que serão criadas no futuro. Edite o limite de destinatários nas caixas de correio existentes individualmente ou em massa usando o Centro de administração do Exchange e personalize a configuração padrão para novas caixas de correio por meio do Windows PowerShell Remoto. Para obter mais informações, confira [Limites de destinatário personalizáveis no Office 365](https://techcommunity.microsoft.com/t5/exchange-team-blog/customizable-recipient-limits-in-office-365/ba-p/1183228).  
> <sup>3</sup> Quando os volumes de mensagens de saída ultrapassam o limite da taxa de mensagens, qualquer excesso no envio de mensagens será limitado e sucessivamente transportado para os minutos seguintes. Isso normalmente não bloqueará a conta do remetente, mas o Exchange Online não é adequado para acomodar cenários de email em massa. Para este caso de uso, as opções 2 e 3 [aqui](/exchange/mail-flow-best-practices/how-to-set-up-a-multifunction-device-or-application-to-send-email-using-microsoft-365-or-office-365) são recomendadas.

#### <a name="sending-limits-across-standalone-options"></a>Limites de envio nas opções autônomas

| Recurso | Exchange Server 2013 | Exchange Online Plano 1 | Plano 2 do Exchange Online | Quiosque do Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Limite de taxa de destinatários|Sem limites<sup>1</sup>|10.000 destinatários por dia<sup>2</sup>|10.000 destinatários por dia<sup>2</sup>|10.000 destinatários por dia<sup>2</sup>|
|Limite de destinatários|1000 destinatários<sup>1</sup>|1000 destinatários|1000 destinatários|1000 destinatários|
|Limite de endereço proxy do destinatário|400|400|400|400|
|Limite de taxa de mensagens|30 mensagens por minuto|30 mensagens por minuto|30 mensagens por minuto|30 mensagens por minuto|

> [!NOTE]
> <sup>1</sup> Este é o limite padrão para organizações do Exchange Server 2013. Os administradores podem alterar esse valor para sua organização.<br/>
<sup>2</sup> Depois que o limite de taxa de destinatários é atingido, as mensagens não podem ser enviadas da caixa de correio até que o número de destinatários que receberam mensagens nas últimas 24 horas caia abaixo do limite. Por exemplo, um usuário envia uma mensagem de email para 5.000 destinatários às 09:00, depois envia outra mensagem para 2.500 destinatários às 10:00 e, em seguida, envia outra mensagem para 2.500 destinatários às 11:00, atingindo o limite de 10.000 mensagens. O usuário não será capaz de enviar mensagens novamente até 09:00 do próximo dia.

## <a name="reporting-and-message-trace-limits"></a>Limites de rastreamento de mensagens e relatórios

Para relatórios e limites de rastreamento de mensagens, confira a seção "Relatórios e disponibilidade de dados de rastreamento de mensagens e latência" em [Relatórios e rastreamento de mensagens na Proteção do Exchange Online](/microsoft-365/security/office-365-security/reporting-and-message-trace-in-exchange-online-protection).

## <a name="retention-limits"></a>Limites de retenção

Esses limites controlam o tempo pelo qual itens em pastas específicas na caixa de entrada podem ser acessados.

- **Período de retenção da pasta Itens Excluídos**: O número máximo de dias que os itens podem permanecer na pasta Itens Excluídos antes de serem removidos automaticamente.

- **Período de retenção para itens removidos da pasta Itens Excluídos**: o número máximo de dias que os itens removidos da pasta Itens Excluídos são retidos antes de serem excluídos permanentemente.

- **Período de retenção da pasta de Lixo Eletrônico**: o número máximo de dias que os itens podem permanecer na pasta de Lixo Eletrônico antes de serem removidos automaticamente.

> [!NOTE]
> Uma caixa de correio de usuário excluída por software&mdash; uma caixa de correio excluída usando o Centro de administração do Microsoft 365 ou o cmdlet Remove-a caixa de correio no Exchange Online Windows PowerShell e que ainda está na lixeira do Azure Active Directory&mdash;pode ser recuperada em 30 dias.

### <a name="retention-limits"></a>Limites de retenção

| Recurso | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Período de retenção na pasta Itens Excluídos|Sem limites<sup>1</sup>|Sem limites<sup>1</sup>|Sem limites<sup>1</sup>|Sem limites<sup>1</sup>|Sem limites<sup>1</sup>|Sem limites<sup>1</sup>|
|Período de retenção para itens removidos da pasta Itens Excluídos|14 dias<sup>1</sup>|14 dias<sup>1</sup>|14 dias<sup>1</sup>|14 dias<sup>1</sup>|14 dias<sup>1</sup>|14 dias<sup>1</sup>|
|Período de retenção na pasta Lixo Eletrônico|30 dias|30 dias|30 dias|30 dias|30 dias|30 dias|

> [!NOTE]
> <sup>1</sup> Este é o valor padrão para organizações Microsoft 365. Os administradores podem alterar esse valor para um máximo de 30 dias para caixas de correio em sua organização.

### <a name="retention-limits-across-standalone-options"></a>Limites de retenção em opções autônomas

| Recurso | Exchange Server 2013 | Exchange Online Plano 1 | Plano 2 do Exchange Online | Quiosque do Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Período de retenção na pasta Itens Excluídos|Sem limites<sup>1</sup>|Sem limites<sup>1</sup>|Sem limites<sup>1</sup>|Sem limites<sup>1</sup>|
|Período de retenção para itens removidos da pasta Itens Excluídos|14 dias<sup>1</sup>|14 dias<sup>2</sup>|14 dias<sup>2</sup>|14 dias<sup>2</sup>|
|Período de retenção na pasta Lixo Eletrônico|2 anos<sup>1</sup>|30 dias|30 dias|30 dias|

> [!NOTE]
> <sup>1</sup> Este é o limite padrão. Os administradores podem alterar esse valor para suas organizações.<br/> <sup>2</sup> Este é o valor padrão para organizações do Exchange Online. Os administradores podem alterar esse valor para um máximo de 30 dias para caixas de correio em sua organização.

## <a name="distribution-group-limits"></a>Limites de grupos de distribuição

Estes limites se aplicam a grupos de distribuição no catálogo de endereços compartilhado de sua organização.

- **Número máximo de membros do grupo de distribuição** A contagem total de destinatários é determinada após a expansão do grupo de distribuição.

- **Limite de envio de mensagens para grupos de distribuição grandes** Grupos de distribuição que contêm o número de membros especificado por esse limite devem ter opções de gerenciamento de entrega ou de aprovação de mensagens configurados. O gerenciamento de entrega especifica uma lista de remetentes que podem enviar mensagens para o grupo de distribuição. A aprovação de mensagens especifica um ou mais moderadores que devem aprovar todas as mensagens enviadas ao grupo de distribuição.

- **Tamanho máximo de mensagem para grupos de distribuição grandes** Se uma mensagem for enviada a 5.000 ou mais destinatários, o tamanho da mensagem não poderá exceder esse limite. Se o tamanho da mensagem exceder o limite, a mensagem não será entregue, e o remetente receberá uma NDR (notificação de falha na entrega).

### <a name="distribution-group-limits"></a>Limites de grupos de distribuição

| Recurso | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Número máximo de membros do grupo de distribuição<sup>1</sup>|100.000 membros|100.000 membros|100.000 membros|100.000 membros|100.000 membros|100.000 membros|
|Limite de envio de mensagens para grupos de distribuição grandes|5.000 ou mais membros|5.000 ou mais membros|5.000 ou mais membros|5.000 ou mais membros|5.000 ou mais membros|5.000 ou mais membros|
|Tamanho máximo das mensagens de grupos de distribuição com membros de 5.000 para 99.999|25 MB|25 MB|25 MB|25 MB|25 MB|25 MB|
|Tamanho máximo das mensagens de grupos de distribuição com 100.000 membros|5 MB|5 MB|5 MB|5 MB|5 MB|5 MB|
|Número máximo de proprietários do grupo de distribuição|10|10|10|10|10|10|
|Número máximo de grupos que um usuário pode criar|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|

> [!NOTE]
> <sup>1</sup> Se você estiver usando o DirSync do Azure Active Directory, o número máximo de membros do grupo de distribuição que pode ser sincronizado do Active Directory local para o Azure Active Directory é 15.000. Se estiver usando o Azure AD Connect, esse número será 50.000. <br/> <sup>2</sup> Esse limite também se aplica a administradores.

### <a name="distribution-group-limits-across-standalone-options"></a>Limites de grupos de distribuição em opções autônomas

| Recurso | Exchange Server 2013 | Exchange Online Plano 1 | Plano 2 do Exchange Online | Quiosque do Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Número máximo de membros do grupo de distribuição|100.000 membros<sup>1</sup>|100.000 membros|100.000 membros|100.000 membros|
|Limite de envio de mensagens para grupos de distribuição grandes|5.000 ou mais membros<sup>1</sup>|5.000 ou mais membros|5.000 ou mais membros|5.000 ou mais membros|
|Número máximo de proprietários do grupo de distribuição|10|10|10|10|
|Número máximo de grupos que um usuário pode criar|250<sup>2</sup>|250<sup>2</sup>|250<sup>2</sup>|250<sup>2</sup>|

> [!NOTE]
> <sup>1</sup> Este é o limite padrão para organizações do Exchange Server 2013. Os administradores podem alterar esse valor para sua organização. <br/> <sup>2</sup> Esse limite também se aplica a administradores.

## <a name="journal-transport-and-inbox-rule-limits"></a>Limites de regras de diário, transporte e caixa de entrada

A lista a seguir inclui os limites que se aplicam às regras de diário, de transporte (também conhecidas como regras da organização) e os limites que se aplicam às regras da Caixa de Entrada. As regras da caixa de entrada são configuradas por usuários individuais e aplicadas às mensagens enviadas e recebidas pela caixa de correio do usuário individual.

- **Número máximo de regras de diário**: o número máximo de regras de diário que podem existir na organização.

- **Número máximo de regras de transporte**: o número máximo de regras que podem existir na organização.

- **Tamanho máximo de uma regra de transporte individual**: o número máximo de caracteres que podem ser usados em uma única regra de transporte. Os caracteres são usados nas condições, exceções e ações.

- **Limite de caracteres para todas as expressões regulares usadas em todas as regras de transporte**: o número total de caracteres usados, incluindo todas as expressões regulares em todas as condições e exceções das regras de transporte na organização. Você pode ter algumas regras que usam expressões regulares longas e complexas ou pode ter muitas regras que usam expressões regulares simples.

- **Os limites de verificação de conteúdo do anexo**: as condições da regra de transporte permitem que você examine o conteúdo dos anexos de mensagens, mas somente os primeiros 1 MB do texto extraído de um anexo são inspecionados. Esse limite de 1 MB refere-se ao texto extraído do anexo, não o tamanho do arquivo do anexo. Por exemplo, um arquivo de 2 MB pode conter menos de 1 MB de texto, para que todo ele seja inspecionado.

- **Número máximo de destinatários adicionados a uma mensagem por todas as regras de transporte**: Quando uma mensagem é afetada por diferentes regras de transporte, apenas um número finito de destinatários pode ser adicionado à mensagem. Depois que o limite é atingido, os destinatários restantes não são adicionados à mensagem. Além disso, grupos de distribuição não podem ser adicionados a uma mensagem por meio de uma regra de transporte.

- **Limite para encaminhamento** O número máximo de destinatários que podem ser configurados para uma regra de caixa de entrada ou de transporte com uma ação de redirecionamento. Se uma regra for configurada para redirecionar uma mensagem a um número de destinatários maior do que esse, a regra não será aplicada e qualquer mensagem que satisfaça à condição de regra não será redirecionada para nenhum dos destinatários listados na regra.
    
- **Número de vezes que uma mensagem é redirecionada**: o número de vezes que uma mensagem será redirecionado, encaminhada ou respondida automaticamente com base em regras de Caixa de Entrada. Por exemplo, o Usuário A tem uma regra de Caixa de Entrada que redireciona mensagens para o Usuário B, com base no remetente. O Usuário B tem uma regra de Caixa de Entrada que encaminha mensagens para o Usuário C com base em palavras-chave na linha de assunto. Se uma mensagem satisfaz a ambas as condições, ela é enviada apenas ao Usuário B; ela não é encaminhada ao Usuário C, porque somente um redirecionamento é permitido. Nesse caso, a mensagem será descartada sem enviar uma notificação de falha na entrega (NDR) para o usuário B, indicando que a mensagem não foi entregue ao usuário C. Usamos o cabeçalho X-MS-Exchange-inbox-Rules-loop para determinar o número de vezes em que uma mensagem foi redirecionada. Esse cabeçalho continua também entre os limites organizacionais do Exchange.

- **Número de vezes em que uma mensagem é redirecionada por regras de transporte**: o número de vezes que uma mensagem será redirecionada com base em regras de transporte. Por exemplo, a organização do Exchange Tailspin Toys tem uma regra de transporte para redirecionar todas as mensagens enviadas ao usuário A para o usuário B, que está localizado na organização do Exchange Contoso. Na organização Contoso do Exchange, há uma regra de transporte em vigor para redirecionar todas as mensagens enviadas ao Usuário B para o Usuário C, que está localizado na organização A. Datum Corporation do Exchange. Nesse caso, a mensagem é descartada e um relatório de falha na entrega (NDR) com código de status e mensagem de rejeição *550 5.7.128 TRANSPORT.RULES.RejectMessage; A contagem de loop das regras de transporte foi excedida e a mensagem rejeitada* é enviada ao Usuário A. Usamos o cabeçalho X-MS-Exchange-Transport-Rules-Loop para determinar o número de vezes que uma mensagem foi redirecionada pelas regras de transporte. Esse cabeçalho continua também entre os limites organizacionais do Exchange.

### <a name="journal-transport-and-inbox-rule-limits"></a>Limites de regras de diário, transporte e caixa de entrada

| Recurso | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Número máximo de regras de diário|300 regras|300 regras|300 regras|300 regras|300 regras|300 regras|
|Número máximo de regras de transporte|300 regras|300 regras|300 regras|300 regras|300 regras|300 regras|
|Tamanho máximo de uma regra de transporte individual|8 KB|8 KB|8 KB|8 KB|8 KB|8 KB|
|Limite de caracteres para todas as expressões regulares usadas em todas as regras de transporte|20 KB|20 KB|20 KB|20 KB|20 KB|20 KB|
|Limites de verificação de conteúdos de anexos|1 MB|1 MB|1 MB|1 MB|1 MB|1 MB|
|Número máximo de destinatários adicionados a uma mensagem por todas as regras de transporte|100 destinatários|100 destinatários|100 destinatários|100 destinatários|100 destinatários|100 destinatários|
|Limite de encaminhamento|10 destinatários|10 destinatários|10 destinatários|10 destinatários|10 destinatários|10 destinatários|
|Número de vezes que uma mensagem é redirecionada|1 redirecionamento|1 redirecionamento|1 redirecionamento|1 redirecionamento|1 redirecionamento|1 redirecionamento|
|Número de vezes que uma mensagem é redirecionada por regras de transporte|1 redirecionamento|1 redirecionamento|1 redirecionamento|1 redirecionamento|1 redirecionamento|1 redirecionamento|
|Número de vezes que uma mensagem é redirecionada|1 redirecionamento|1 redirecionamento|1 redirecionamento|1 redirecionamento|1 redirecionamento|1 redirecionamento|
|Regra de caixa de entrada|256kb<sup>1</sup>|256kb<sup>1</sup>|256kb<sup>1</sup>|256kb<sup>1</sup>|256kb<sup>1</sup>|256kb<sup>1</sup>|

> [!NOTE]
> <sup>1</sup> se uma caixa de correio foi migrada para o Exchange Online, o limite da regra da caixa de entrada pode ser definido para o valor menor que o valor de EXO padrão. Se esse for o caso, o valor da regra da caixa de entrada poderá ser aumentado. Para obter instruções, confira [Modificar o espaço usado pelas regras da caixa de entrada no Exchange Online](/exchange/clients-and-mobile-in-exchange-online/outlook-on-the-web/increase-the-space-used-by-inbox-rules). 

### <a name="journal-transport-and-inbox-rule-limits-across-standalone-options"></a>Limites de regra de Diário, Transporte e Caixa de Entrada entre opções independentes

| Recurso | Exchange Server 2013 | Exchange Online Plano 1 | Plano 2 do Exchange Online | Quiosque do Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Número máximo de regras de diário|Sem limites|50 regras|50 regras|50 regras|
|Número máximo de regras de transporte|Sem limite|300 regras|300 regras|300 regras|
|Tamanho máximo de uma regra de transporte individual|40 KB|8 KB|8 KB|8 KB|
|Limite de caracteres para todas as expressões regulares usadas em todas as regras de transporte|Sem limite|20 KB|20 KB|20 KB|
|Número máximo de destinatários adicionados a uma mensagem por todas as regras de transporte|Sem limite|100 destinatários|100 destinatários|100 destinatários|
|Limite de encaminhamento|Sem limite|10 destinatários|10 destinatários|10 destinatários|
|Número de vezes que uma mensagem é redirecionada|3 redirecionamentos|1 redirecionamento|1 redirecionamento|1 redirecionamento|
|Número de vezes que uma mensagem é redirecionada por regras de transporte|Sem limite|1 redirecionamento|1 redirecionamento|1 redirecionamento|

## <a name="moderation-limits"></a>Limites de moderação

Estes limites controlam as configurações de moderação que são usadas para aprovação de mensagens aplicadas a grupos de distribuição e regras de transporte.

- **Tamanho máximo da caixa de correio de arbitragem**: se a caixa de correio de arbitragem exceder esse limite, as mensagens que requerem moderação serão devolvidas ao remetente em uma NDR (notificação de falha na entrega).

- **Número máximo de moderadores**: o número máximo de moderadores que você pode atribuir a um único grupo de distribuição moderado ou que podem ser adicionados a uma mensagem por meio de uma única regra de transporte. Observe que você não pode especificar um grupo de distribuição como um moderador.

- **Expiração para mensagens aguardando moderação** Por padrão, uma mensagem que está aguardando moderação expira após dois dias. No entanto, o processamento de mensagens moderadas expiradas é executado a cada sete dias. Isso significa que uma mensagem moderada pode expirar a qualquer momento entre dois e nove dias.

- **Taxa máxima para mensagens de notificação de moderação expiradas** Este limite define o número máximo de mensagens de notificação para mensagens moderadas expiradas em um período de uma hora. Esse limite é imposto a todos os bancos de dados de caixas de correio no datacenter.

Durante os períodos de pesado intenso, alguns remetentes podem não receber mensagens de notificação para mensagens moderadas que expiraram. No entanto, essas notificações ainda são detectáveis com o uso de relatórios de entrega.

### <a name="moderation-limits"></a>Limites de moderação

| Recurso | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Tamanho máximo da caixa de correio de arbitragem|10 GB|10 GB|10 GB|10 GB|10 GB|10 GB|
|Número máximo de moderadores|10 moderadores|10 moderadores|10 moderadores|10 moderadores|10 moderadores|10 moderadores|
|Expiração para mensagens aguardando moderação|2 dias|2 dias|2 dias|2 dias|2 dias|2 dias|
|Taxa máxima para mensagens de notificação de moderação expiradas|300 notificações de expiração por hora|300 notificações de expiração por hora|300 notificações de expiração por hora|300 notificações de expiração por hora|300 notificações de expiração por hora|300 notificações de expiração por hora|

### <a name="moderation-limits-across-standalone-options"></a>Limites de moderação em opções autônomas

| Recurso | Exchange Server 2013 | Exchange Online Plano 1 | Plano 2 do Exchange Online | Quiosque do Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Tamanho máximo da caixa de correio de arbitragem|Sem limites<sup>1</sup>|10 GB|10 GB|10 GB|
|Número máximo de moderadores|Sem limite|10 moderadores|10 moderadores|10 moderadores|
|Expiração para mensagens aguardando moderação|5 dias<sup>1</sup>|2 dias|2 dias|2 dias|
|Taxa máxima para mensagens de notificação de moderação expiradas|300 notificações de expiração por hora|300 notificações de expiração por hora|300 notificações de expiração por hora|300 notificações de expiração por hora|

> [!NOTE]
> <sup>1</sup> Este é o limite padrão para organizações do Exchange Server 2013. Os administradores podem alterar esse valor para sua organização.

## <a name="exchange-activesync-limits"></a>Limites do Exchange ActiveSync

Os seguintes limites se aplicam ao Microsoft Exchange ActiveSync, um protocolo de cliente que sincroniza dados de caixa de correio entre dispositivos móveis e o Exchange.

- **limite do dispositivo Exchange ActiveSync** O número máximo de dispositivos do Exchange ActiveSync por caixa de correio.

- **Limite de exclusão de dispositivo Exchange ActiveSync**: o número máximo de dispositivos do Exchange ActiveSync que um administrador do Exchange pode excluir em um único mês.

### <a name="exchange-activesync-limits"></a>Limites do Exchange ActiveSync

| Recurso | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Limite do dispositivo do Exchange ActiveSync|100|100|100|100|100|100|
|Limite de exclusão do dispositivo do Exchange ActiveSync|20|20|20|20|20|20|

### <a name="exchange-activesync-limits-across-standalone-options"></a>Limites do Exchange ActiveSync nas opções independentes

| Recurso | Exchange Server 2013 | Exchange Online Plano 1 | Plano 2 do Exchange Online | Quiosque do Exchange Online |
|:-----|:-----|:-----|:-----|:-----|
|Limite do dispositivo do Exchange ActiveSync|100|100|100|100|
|Limite de exclusão do dispositivo do Exchange ActiveSync|20|20|20|20|