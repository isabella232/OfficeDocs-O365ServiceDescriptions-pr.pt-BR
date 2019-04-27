---
title: Limites do SharePoint Online
ms.author: sharik
author: skjerland
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Localize os limites do SharePoint Online para os planos do Office 365 Enterprise e os planos autônomos.
ms.openlocfilehash: 4615eeefe2f9f172a5baa43ce3a506015bfe159e
ms.sourcegitcommit: 2b88e04bd6850094e7dc21e61d52a46016fa6617
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/27/2019
ms.locfileid: "33368364"
---
# <a name="sharepoint-online-limits"></a>Limites do SharePoint Online

Encontre os limites do SharePoint para planos do Office 365 e planos autônomos do SharePoint Online.
  
## <a name="limits-by-plan"></a>Limites por plano

|||||
|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Office 365 Business Essentials ou Business Premium** <br/> |**Office 365 Enterprise E1, E3 ou e5, ou SharePoint Online plano 1 ou 2** <br/> | **Office 365 Enterprise F1** <br/> |
|Armazenamento<sup>1, 2</sup> <br/> |1 TB por organização mais 10 GB por licença adquirida  <br/> |1 TB por organização mais 10 GB por licença adquirida<sup>3</sup> <br/> |1 TB por organização <sup>3</sup> <br/> |
|Armazenamento para conjuntos de sites  <br/> |Até 25 TB por conjunto de sites ou grupo<sup>4</sup> <br/> |Até 25 TB por conjunto de sites ou grupo<sup>4</sup> <br/> |Até 25 TB por conjunto de sites ou grupo<sup>5</sup> <br/> |
|Conjuntos de sites por organização  <br/> |500.000<sup>6</sup> <br/> |500.000<sup>6</sup> <br/> |US$ 500.000<br/> |
|Número de usuários  <br/> |Até 300  <br/> |1 a 500.000<sup>7</sup> <br/> |1 a 500.000<sup>7</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> Você pode adquirir um volume ilimitado de armazenamento adicional do SharePoint Online. Consulte [Alterar o espaço de armazenamento de sua assinatura](https://support.office.com/article/96EA3533-DE64-4B01-839A-C560875A662C). 
<br/><sup>2</sup> Recomendamos monitorar a Lixeira e esvaziá-la regularmente. O espaço de armazenamento que ela usa faz parte do limite de armazenamento de arquivo total da organização. 
<br/> <sup>3</sup> Quando você tiver uma assinatura do Office 365 e um plano autônomo do SharePoint Online, os valores de armazenamento serão adicionados. 
<br/><sup>4</sup> os administradores do SharePoint Online podem definir limites de armazenamento para conjuntos de sites e sites.
<br/> <sup>5</sup> Os funcionários de quiosque não podem administrar os conjuntos de sites do SharePoint Online. Você precisa de pelo menos uma licença de usuário do Enterprise para gerenciar conjuntos de sites de quiosque. 
<br/> <sup>6</sup> Não incluindo os conjuntos de sites do OneDrive Business criados para cada usuário licenciado. 
<br/><sup>7</sup> Se você tiver mais de 500.000 usuários, entre em contato com um representante da Microsoft. 
  

  
## <a name="service-limits-for-all-plans"></a>Limites de serviço para todos os planos

- **Itens em listas e bibliotecas** -uma lista pode ter até 30 milhões itens e uma biblioteca pode ter até 30 milhões arquivos e pastas. Após 100, os itens 00 são adicionados a uma lista, biblioteca ou pasta, a herança de permissão para a lista, biblioteca ou pasta não pode ser alterada. Para saber mais sobre outras restrições para exibir listas grandes, confira [gerenciar grandes listas e bibliotecas no Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784). Para obter informações sobre caracteres que não podem ser usados em nomes de arquivos, confira [caracteres inválidos em nomes de arquivos e pastas](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

- **Tamanho do arquivo e comprimento do caminho do arquivo** -15 GB. Para saber mais sobre restrições e limites ao usar o novo cliente de sincronização do OneDrive (OneDrive. exe), confira nomes de arquivos [e tipos de arquivos inválidos no onedrive, no onedrive for Business e no SharePoint](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

- **Movimentação e cópia nos conjuntos de sites** – 100 GB por operação. O navegador da Web deve permanecer aberto.

- **Sync** -para obter o desempenho ideal, recomendamos armazenar até 300.000 arquivos em uma única biblioteca de sites do onedrive ou de equipe. Embora o SharePoint Online possa armazenar documentos de 30 milhões por biblioteca, para o desempenho ideal, recomendamos sincronizar no máximo 300.000 arquivos em todas as bibliotecas de documentos. Além disso, os mesmos problemas de desempenho podem ocorrer se você tiver 300.000 itens ou mais em todas as bibliotecas que estiver sincronizando, mesmo que não esteja sincronizando todos os itens dessas bibliotecas. Se você usar o cliente de sincronização anterior do OneDrive for Business (Groove. exe), o limite de sincronização por biblioteca será de 20.000 itens (incluindo 5.000 itens por site de equipe).

- **Versões** -50.000 versões principais e 511 versões secundárias.

- **Grupos do SharePoint** : um usuário pode pertencer a 5.000 grupos e cada grupo pode ter até 5.000 usuários. Você pode ter até 10.000 grupos por conjunto de sites.

- **Metadados gerenciados** -200.000 termos no repositório de termos, conjuntos de termos globais, 1.000 grupos.

- **** Subsites-até 2.000 por conjunto de sites.

- **Aplicativos hospedados do SharePoint** -instâncias de 20.000 por organização.

- Escopos de **segurança exclusivos por lista ou biblioteca** -5.000. Para listas grandes, design para ter o menor número possível de permissões exclusivas.

- **Users** -2 milhões por conjunto de sites.

> [!NOTE]
> Não há limite para o número de usuários externos que você pode convidar para seus conjuntos de sites do SharePoint Online. Para saber mais, confira [Gerenciar o compartilhamento externo para seu ambiente do SharePoint Online](/sharepoint/external-sharing-overview).

## <a name="see-also"></a>Confira também

[Limites de pesquisa para o SharePoint Online](/sharepoint/search-limits)
