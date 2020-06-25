---
title: Limites do SharePoint
ms.author: sharik
author: skjerland
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Saiba mais sobre os limites do SharePoint para o Microsoft 365 e planos autônomos.
ms.openlocfilehash: 1df1b5914d26e46798db04732b0574203ec1fab9
ms.sourcegitcommit: 83047250183f758d8330b67116cd257a799e1ea9
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/24/2020
ms.locfileid: "44873611"
---
# <a name="sharepoint-limits"></a>Limites do SharePoint

Saiba mais sobre os limites de serviço no SharePoint para o Microsoft 365.
  
## <a name="limits-by-plan"></a>Limites por plano 

|||||
|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Microsoft 365 Business Basic ou Business Premium** <br/> |**Office 365 Enterprise E1, E3 ou e5, ou SharePoint plano 1 ou 2** <br/> | **Office 365 Enterprise F3** <br/> |
|Armazenamento total por organização<sup>1, 2, 6</sup> <br/> |1 TB mais 10 GB por licença adquirida  <br/> |1 TB mais 10 GB por licença adquirida<sup>3</sup> <br/> |1 TB<sup>3</sup> <br/> |
|Armazenamento máximo por site (conjunto de sites)<sup>4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB<sup>5</sup> <br/> |
|Sites (conjuntos de sites) por organização  <br/> |2 milhões<sup>6</sup> <br/> |2 milhões<sup>6</sup> <br/> |2 milhões<br/> |
|Número de usuários  <br/> |Até 300  <br/> |1 a 500.000<sup>7</sup> <br/> |1 a 500.000<sup>7</sup> <br/> |
   
<sup>1</sup> [saiba como encontrar o armazenamento total e disponível para sua organização](/sharepoint/manage-site-collection-storage-limits). Você pode adquirir uma quantidade ilimitada de armazenamento adicional do SharePoint. Consulte [Alterar o espaço de armazenamento de sua assinatura](/office365/admin/subscriptions-and-billing/add-storage-space). 
<br/><sup>2</sup> Recomendamos monitorar a Lixeira e esvaziá-la regularmente. O espaço de armazenamento que ele usa faz parte do limite total de armazenamento da organização. 
<br/> <sup>3</sup> se você tiver uma assinatura do Microsoft 365 e um complemento de armazenamento de arquivos extra do Office 365, os valores de armazenamento serão adicionados. 
<br/> <sup>4</sup> este é o *limite* de armazenamento para um único site (anteriormente chamado de "conjunto de sites"), não a quantidade de armazenamento *fornecida* para cada site. Este limite se aplica a todos os tipos de sites, incluindo sites de equipe conectados ao grupo do Office 365 e o OneDrive. Os administradores do SharePoint podem [definir manualmente os limites de armazenamento menores](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits). 
<br/> <sup>5</sup> os funcionários de primeiro lugar não podem administrar sites do SharePoint. 
<br/> <sup>6</sup> não incluindo o onedrive criado para cada usuário licenciado. 
<br/> <sup>7</sup> Se você tiver mais de 500.000 usuários, entre em contato com um representante da Microsoft. 
  
## <a name="service-limits-for-all-plans"></a>Limites de serviço para todos os planos

### <a name="items-in-lists-and-libraries"></a>Itens em listas e bibliotecas

Uma lista pode ter até 30 milhões itens e uma biblioteca pode ter até 30 milhões arquivos e pastas. Quando uma lista, uma biblioteca ou uma pasta contiver mais de 100.000 itens, você não poderá interromper a herança de permissões na lista, biblioteca ou pasta. Nem é possível herdar novamente as permissões. No entanto, você ainda pode quebrar a herança nos itens individuais dentro dessa lista, biblioteca ou pasta, até o número máximo de permissões exclusivas na lista ou biblioteca (consulte a próxima seção). Para saber mais sobre outras restrições para exibir listas grandes, confira [gerenciar grandes listas e bibliotecas no Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784). 

> [!NOTE]
> Não há limite para o número de bibliotecas de documentos que você pode ter em um site.

### <a name="unique-permissions-for-items-in-a-list-or-library"></a>Permissões exclusivas para itens em uma lista ou biblioteca

O limite com suporte é 50.000, mas o limite geral recomendado é 5.000. Fazer alterações em mais de 5.000 itens com permissões exclusivas por vez leva mais tempo. Para listas grandes, design para ter o menor número possível de permissões exclusivas.

### <a name="file-size-and-file-path-length"></a>Tamanho do arquivo e comprimento do caminho do arquivo

100 GB. O tamanho máximo para arquivos anexados a itens de lista é de 250 MB. Para saber mais sobre restrições e limites ao usar o novo aplicativo de sincronização do OneDrive (OneDrive.exe), confira [nomes de arquivo e tipos de arquivo inválidos](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

### <a name="moving-and-copying-across-sites"></a>Movendo e copiando entre sites

100 GB por operação. O navegador da Web deve permanecer aberto.

### <a name="sync"></a>Sincronizar

**Novo aplicativo de sincronização do onedrive** – para obter o desempenho ideal, recomendamos armazenar no máximo 300.000 arquivos em todas as bibliotecas de documentos sincronizadas, mesmo que você esteja usando arquivos por demanda ou escolhendo apenas algumas pastas dentro das bibliotecas para sincronizar.

**Aplicativo de sincronização anterior do onedrive for Business (Groove.exe)** -você pode sincronizar até 20.000 itens de total em todas as bibliotecas sincronizadas. Isso inclui as bibliotecas do OneDrive, as bibliotecas do site de equipe ou ambas. Separadamente do limite geral de sincronização, há limites para o número de itens que podem ser sincronizados para cada tipo de biblioteca:

   - Você pode sincronizar até 20.000 itens em uma biblioteca do OneDrive. Isso inclui pastas e arquivos. 
   - Você pode sincronizar até 5.000 itens em uma biblioteca do SharePoint. Isso inclui pastas e arquivos. São as bibliotecas que você encontra em vários sites do SharePoint, como sites de equipe e sites de comunidade, bibliotecas que outras pessoas criaram ou que você criou na página sites. Você pode sincronizar várias bibliotecas do SharePoint. Qualquer site de equipe que você sincronizar também contará com o limite de itens de 20.000 geral em todas as bibliotecas sincronizadas.

> [!NOTE]
> Se os usuários precisarem sincronizar arquivos em bibliotecas de documentos com centenas de milhares de arquivos, você poderá "Ocultar" pastas do aplicativo de sincronização definindo o nível de permissão das pastas como "leitura restrita". 

### <a name="versions"></a>Versões

50.000 versões principais e 511 versões secundárias.

### <a name="sharepoint-groups"></a>Grupos do SharePoint

Um usuário pode pertencer a 5.000 grupos e cada grupo pode ter até 5.000 usuários. Você pode ter até 10.000 grupos por site (conjunto de sites).

> [!NOTE]
> Para limites de grupos do Azure AD, confira [limites e restrições do serviço do Azure ad](/azure/active-directory/users-groups-roles/directory-service-limits-restrictions) , pois esses limites podem afetar o gerenciamento de associação de sites de grupos públicos e privados. 

### <a name="managed-metadata"></a>Metadados gerenciados

200.000 termos no repositório de termos, 1.000 conjuntos de termos globais, grupos 1.000.

### <a name="overall-site-metadata"></a>Metadados gerais do site

1000 GB por site (metadados raramente atingem esse tamanho).

### <a name="subsites"></a>Subsites 

2.000 por site (conjunto de sites). Recomendamos criar sites e organizá-los em hubs, em vez de criar subsites. Se você usar subsites, recomendamos limitar o número (especialmente em sites com muito tráfico).

### <a name="sharepoint-hosted-applications"></a>Aplicativos hospedados no SharePoint

20.000 instâncias por organização.

### <a name="people-editing-a-document-at-the-same-time"></a>Pessoas que estão editando um documento ao mesmo tempo

99 as pessoas podem ter um documento aberto para edição ao mesmo tempo. Se mais de 10 pessoas editarem um documento simultaneamente, suas edições serão mais prováveis de entrar em conflito e a experiência do usuário será gradualmente degradar.

### <a name="users"></a>Usuários

2 milhões por site (conjunto de sites).
   
> [!NOTE]
> Não há limite para o número de convidados que você pode convidar para sites do SharePoint. Para obter mais informações sobre o compartilhamento externo, consulte [visão geral do compartilhamento externo](/sharepoint/external-sharing-overview).

## <a name="see-also"></a>Confira também

[Limites de pesquisa para o SharePoint](/sharepoint/search-limits)
