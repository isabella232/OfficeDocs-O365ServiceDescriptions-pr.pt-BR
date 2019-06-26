---
title: Limites do SharePoint Online
ms.author: sharik
author: skjerland
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Localize os limites do SharePoint Online para os planos do Office 365 Enterprise e os planos autônomos.
ms.openlocfilehash: 2e99bcd4ed05f345757323359350a00161780b03
ms.sourcegitcommit: e77906b172913bb7b3359d649da59c5d2ee1123f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/26/2019
ms.locfileid: "35233528"
---
# <a name="sharepoint-online-limits"></a>Limites do SharePoint Online 

Encontre os limites do SharePoint para planos do Office 365 e planos autônomos do SharePoint Online.
  
## <a name="limits-by-plan"></a>Limites por plano 

|||||
|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Office 365 Business Essentials ou Business Premium** <br/> |**Office 365 Enterprise E1, E3 ou e5, ou SharePoint Online plano 1 ou 2** <br/> | **Office 365 Enterprise F1** <br/> |
|Armazenamento total por organização<sup>1, 2</sup> <br/> |1 TB mais 10 GB por licença adquirida  <br/> |1 TB mais 10 GB por licença adquirida<sup>3</sup> <br/> |1 TB<sup>3</sup> <br/> |
|Máximo de armazenamento por conjunto de sites<sup>4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB<sup>5</sup> <br/> |
|Conjuntos de sites por organização  <br/> |1 milhão<sup>6</sup> <br/> |1 milhão<sup>6</sup> <br/> |1 milhão<br/> |
|Número de usuários  <br/> |Até 300  <br/> |1 a 500.000<sup>7</sup> <br/> |1 a 500.000<sup>7</sup> <br/> |
   
<sup>1</sup> você pode adquirir uma quantidade ilimitada de armazenamento adicional do SharePoint. Consulte [Alterar o espaço de armazenamento de sua assinatura](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/add-storage-space). 
<br/><sup>2</sup> Recomendamos monitorar a Lixeira e esvaziá-la regularmente. O espaço de armazenamento que ele usa faz parte do limite total de armazenamento da organização. 
<br/> <sup>3</sup> se você tiver uma assinatura do Office 365 e um complemento de armazenamento de arquivos extra do Office 365, os valores de armazenamento serão adicionados. 
<br/> <sup>4</sup> este é o limite de armazenamento para um único conjunto de sites, não a quantidade de armazenamento fornecida para cada conjunto de sites. Este limite se aplica a todos os tipos de conjuntos de sites, incluindo sites de equipe conectados ao grupo do Office 365 e o OneDrive. Os administradores do SharePoint podem [definir manualmente os limites de armazenamento menores](https://docs.microsoft.com/sharepoint/manage-site-collection-storage-limits). 
<br/> <sup>5</sup> os funcionários de primeiro lugar não podem administrar conjuntos de sites do SharePoint. 
<br/> <sup>6</sup> não incluindo o onedrive criado para cada usuário licenciado. 
<br/> <sup>7</sup> Se você tiver mais de 500.000 usuários, entre em contato com um representante da Microsoft. 
  
## <a name="service-limits-for-all-plans"></a>Limites de serviço para todos os planos

- **Itens em listas e bibliotecas** -uma lista pode ter até 30 milhões itens e uma biblioteca pode ter até 30 milhões arquivos e pastas. Depois que 100.000 itens são adicionados a uma lista, biblioteca ou pasta, a herança de permissão para a lista, biblioteca ou pasta não pode ser alterada. Para saber mais sobre outras restrições para exibir listas grandes, confira [gerenciar grandes listas e bibliotecas no Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784). Para obter informações sobre caracteres que não podem ser usados em nomes de arquivos, confira [caracteres inválidos em nomes de arquivos e pastas](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

- **Tamanho do arquivo e comprimento do caminho do arquivo** -15 GB. Para saber mais sobre restrições e limites ao usar o novo cliente de sincronização do OneDrive (OneDrive. exe), confira nomes de arquivos [e tipos de arquivos inválidos no onedrive, no onedrive for Business e no SharePoint](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

- **Movimentação e cópia nos conjuntos de sites** – 100 GB por operação. O navegador da Web deve permanecer aberto.

- **Sync** -para obter o desempenho ideal, recomendamos armazenar até 300.000 arquivos em todas as bibliotecas de documentos sincronizadas, mesmo que você esteja usando arquivos por demanda ou escolhendo apenas algumas pastas dentro das bibliotecas para sincronizar. Se você usar o cliente de sincronização anterior do OneDrive for Business (Groove. exe), o limite de sincronização por biblioteca será de 20.000 itens (incluindo 5.000 itens por site de equipe).

    > [!NOTE]
    > Se os usuários precisarem sincronizar arquivos em bibliotecas de documentos com centenas de milhares de arquivos, você poderá "Ocultar" as pastas do cliente de sincronização definindo o nível de permissão das pastas como "leitura restrita". 

- **Versões** -50.000 versões principais e 511 versões secundárias.

- **Grupos do SharePoint** : um usuário pode pertencer a 5.000 grupos e cada grupo pode ter até 5.000 usuários. Você pode ter até 10.000 grupos por conjunto de sites.
    > [!NOTE]
    > Para limites de grupos do Azure AD, confira [limites e restrições do serviço do Azure ad](https://docs.microsoft.com/azure/active-directory/users-groups-roles/directory-service-limits-restrictions) , pois esses limites podem afetar o gerenciamento de associação de sites de grupos públicos e privados. 
- **Metadados gerenciados** -200.000 termos no repositório de termos 1.000, conjuntos de termos globais, 1.000 grupos.

- **** Subsites-2.000 por conjunto de sites.

- **Aplicativos hospedados do SharePoint** -instâncias de 20.000 por organização.

- Escopos de **segurança exclusivos por lista ou biblioteca** -5.000. Para listas grandes, design para ter o menor número possível de permissões exclusivas.

- **Users** -2 milhões por conjunto de sites.
    > [!NOTE]
    > Não há limite para o número de convidados que você pode convidar para os conjuntos de sites do SharePoint. Para obter mais informações sobre o compartilhamento externo, consulte [visão geral do compartilhamento externo](https://docs.microsoft.com/sharepoint/external-sharing-overview).
## <a name="see-also"></a>Confira também

[Limites de pesquisa para o SharePoint Online](https://docs.microsoft.com/sharepoint/search-limits)
