---
title: Limites do SharePoint Online
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Localize os limites do SharePoint Online para os planos do Office 365 Enterprise e os planos autônomos.
ms.openlocfilehash: 9d960aa50bef0b200fef2afe63ac1732cf201582
ms.sourcegitcommit: 30a452b9b9a0d8fc288e5911235454cc8f1907be
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 02/12/2019
ms.locfileid: "25848686"
---
# <a name="sharepoint-online-limits"></a>Limites do SharePoint Online

Encontre os limites do SharePoint para planos do Office 365 e os planos independentes do SharePoint Online.
  
## <a name="limits-by-plan"></a>Limites por plano

|||||
|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Recursos básicos de negócios do Office 365 ou Business Premium** <br/> |**O Office 365 Enterprise E1, E3, ou E5 ou SharePoint Online plano 1 ou 2** <br/> | **Office 365 Enterprise F1** <br/> |
|Armazenamento<sup>1, 2</sup> <br/> |1 TB por organização mais de 10 GB por licença adquirida  <br/> |1 TB por organização mais de 10 GB por licença adquiriram<sup>3</sup> <br/> |1 TB por organização <sup>3</sup> <br/> |
|Armazenamento para conjuntos de sites  <br/> |Até 25 TB por conjunto de sites ou grupo<sup>4</sup> <br/> |Até 25 TB por conjunto de sites ou grupo<sup>4</sup> <br/> |Até 25 TB por conjunto de sites ou grupo<sup>5</sup> <br/> |
|Conjuntos de sites por organização  <br/> |500.000<sup>6</sup> <br/> |500.000<sup>6</sup> <br/> | 500.000<br/> |
|Número de usuários  <br/> |Até 300  <br/> |1 a 500.000<sup>7</sup> <br/> |1 a 500.000<sup>7</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> você pode adquirir uma quantidade ilimitada de armazenamento do SharePoint Online adicional. Consulte [alterar o espaço de armazenamento para sua assinatura](https://support.office.com/article/96EA3533-DE64-4B01-839A-C560875A662C).<br/><sup>2</sup> , é recomendável monitoramento da Lixeira e esvaziar a ele regularmente. Ele usa o espaço de armazenamento faz parte do limite de armazenamento de arquivo total da organização.<br/> <sup>3</sup> Quando você tiver uma assinatura do Office 365 e um plano autônomo do SharePoint Online, os valores de armazenamento serão adicionados.<br/><sup>4</sup> administradores do SharePoint Online podem definir limites de armazenamento de conjuntos de sites.<br/> <sup>5</sup> os trabalhadores do Quiosque não é possível administrar conjuntos de sites do SharePoint Online. Você precisa pelo menos uma licença de usuário corporativo para gerenciar conjuntos de sites de quiosque.<br/> <sup>6</sup> Não incluindo os conjuntos de sites do OneDrive Business criados para cada usuário licenciado.<br/><sup>7</sup> Se você tiver mais de 500.000 usuários, entre em contato com um representante da Microsoft. 
  

  
## <a name="service-limits-for-all-plans"></a>Limites de serviço para todos os planos

- **Itens em listas e bibliotecas** - uma lista pode ter até 30 milhões de itens e uma biblioteca pode ter os arquivos e pastas até 30 milhões. Modos de exibição podem ter até 12 colunas de pesquisa. Para saber mais sobre outras restrições para exibir listas grandes, consulte [gerenciar grandes listas e bibliotecas no Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784). Para obter informações sobre os caracteres que não podem ser usados nos nomes dos arquivos, consulte [caracteres inválidos em nomes de arquivos e pastas](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

- **Tamanho do arquivo e o comprimento do caminho de arquivo** - 15 GB. Para saber mais sobre os limites e restrições ao usar o novo cliente de sincronização do OneDrive (OneDrive.exe), consulte [nomes de arquivo inválido e tipos de arquivo no OneDrive, OneDrive para negócios e o SharePoint](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

- **Sincronização** - para desempenho ideal, é recomendável armazenar os arquivos não ultrapassa 300.000 em uma única biblioteca de site OneDrive ou equipe. Embora o SharePoint Online pode armazenar documentos 30 milhões por biblioteca, para um desempenho ideal é recomendável está sincronizando não ultrapassa 300.000 arquivos entre todas as bibliotecas de documentos. Além disso, os mesmos problemas de desempenho podem ocorrer se você tiver 300.000 de itens ou mais entre todas as bibliotecas que você está sincronizando, mesmo se você não é está sincronizando todos os itens essas bibliotecas. Se você usar o OneDrive anterior para o cliente de sincronização de negócios (Groove.exe), o limite de sincronização por biblioteca é de 20.000 itens (incluindo 5.000 itens por site de equipe).

- **Versões** - 50.000 versões principais e 511 versões secundárias.

- **Grupos do SharePoint** - um usuário pode pertencer aos grupos de 5.000, e cada grupo pode ter até 5.000 usuários. Você pode ter até 10.000 grupos por conjunto de sites.

- **Metadados gerenciados** - 200.000 termos no repositório de termos, conjuntos de termos globais 1.000, 1.000 grupos.

- **Subsites** - até 2.000 por conjunto de sites.

- **Aplicativos hospedados de SharePoint** - 20.000 instâncias por organização.

- **Escopos de segurança exclusivos por lista ou biblioteca** - 5.000. Para obter listas grandes, design ter permissões exclusivas ao menor número possível.

- **Os usuários** - 2 milhões por conjunto de sites.

> [!NOTE]
> [!OBSERVAçãO] Não há limites para o número de usuários externos que podem ser convidados para seus conjuntos de sites do SharePoint Online. Para saber mais, confira [Gerenciar o compartilhamento externo para seu ambiente do SharePoint Online](/sharepoint/external-sharing-overview).

## <a name="see-also"></a>Confira também

[Limites de pesquisa do SharePoint Online](/sharepoint/search-limits)