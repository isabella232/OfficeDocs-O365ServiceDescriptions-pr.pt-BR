---
title: Limites do Microsoft Office SharePoint Online
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Saiba os SharePoint para planos Microsoft 365 autônomos e autônomos.
ms.openlocfilehash: 44571cedf74b2a094231173b87731916d9e26975
ms.sourcegitcommit: 10699cc17ddfed6af78ce1466f478b2bd67ba26a
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/08/2021
ms.locfileid: "53338334"
---
# <a name="sharepoint-limits"></a>Limites do Microsoft Office SharePoint Online

Saiba mais sobre os limites de serviço em SharePoint para Microsoft 365.
  
## <a name="limits-by-plan"></a>Limites por plano 

| Recurso | Microsoft 365 Business Basic, Business Standard ou Business Premium | Microsoft 365 E3 ou E5, Office 365 E1, E3 ou E5 ou SharePoint Plano 1 ou 2 | Microsoft 365 F1 ou F3, Office 365 F3 |
|:-----|:-----|:-----|:-----|
|Armazenamento total por<sup>organização 1, 2, 6</sup> <br/> |1 TB mais 10 GB por licença adquirida<sup>3</sup>  <br/> |1 TB mais 10 GB por licença adquirida<sup>3</sup> <br/> |1 TB<sup>3</sup> <br/> |
|Armazenamento máximo por site (conjunto de sites)<sup>4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB<sup>5</sup> <br/> |
|Sites (conjunto de sites) por organização  <br/> |2 milhões<sup>6</sup> <br/> |2 milhões<sup>6</sup> <br/> |2 milhões<br/> |
|Número de usuários  <br/> |Até 300  <br/> |1 a 500.000<sup>7</sup> <br/> |1 a 500.000<sup>7</sup> <br/> |
   
<sup>1</sup> [Saiba como encontrar o armazenamento total e disponível para sua organização.](/sharepoint/manage-site-collection-storage-limits) Você pode comprar uma quantidade ilimitada de armazenamento SharePoint armazenamento adicional. Consulte [Adicionar espaço de armazenamento para sua assinatura](/office365/admin/subscriptions-and-billing/add-storage-space). 
<br/><sup>2</sup> Recomendamos monitorar a Lixeira e esvaziá-la regularmente. O espaço de armazenamento que ele usa faz parte do limite total de armazenamento da organização. 
<br/> <sup>3</sup> Se você tiver uma assinatura Microsoft 365 e um complemento Office 365 com Espaço de Armazenamento Adicional, os valores de armazenamento serão adicionados. 
<br/> <sup>4</sup> Esse é o limite de *armazenamento* para um único site (anteriormente chamado de "conjunto de sites"), não a quantidade de *armazenamento fornecida* para cada site. Esse limite se aplica a todos os tipos de sites, incluindo Office 365 sites de equipe conectados a grupos e OneDrive. SharePoint administradores podem [definir manualmente limites de armazenamento mais baixos.](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits) 
<br/> <sup>5</sup> Os trabalhadores de primeira linha não podem administrar SharePoint sites. 
<br/> <sup>6</sup> Não incluindo a OneDrive criada para cada usuário licenciado. 
<br/> <sup>7</sup> Se você tiver mais de 500.000 usuários, contate um representante da Microsoft. 
  
## <a name="service-limits-for-all-plans"></a>Limites de serviço para todos os planos

### <a name="items-in-lists-and-libraries"></a>Itens em listas e bibliotecas

Uma lista pode ter até 30 milhões de itens e uma biblioteca pode ter até 30 milhões de arquivos e pastas. Quando uma lista, biblioteca ou pasta contém mais de 100.000 itens, você não pode quebrar a herança de permissões na lista, biblioteca ou pasta. Também não é possível herdar permissões nele. No entanto, você ainda pode quebrar a herança nos itens individuais dentro dessa lista, biblioteca ou pasta, até o número máximo de permissões exclusivas na lista ou biblioteca (consulte a próxima seção). Para saber mais sobre outras restrições para exibir listas grandes, consulte [Manage large lists and libraries in Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784).

### <a name="unique-security-scopes-per-list-or-library"></a>Escopos de segurança exclusivos por lista ou biblioteca

Para listas grandes, projete para ter o menor número possível de permissões exclusivas e permaneça abaixo de 5.000 no total.

### <a name="file-size-and-file-path-length"></a>Tamanho do arquivo e comprimento do caminho do arquivo

- **250 GB - Limite de carregamento de arquivo.** Aplica-se a cada arquivo individual carregado na guia Arquivos Microsoft Teams, SharePoint bibliotecas de documentos, OneDrive pastas e Yammer conversas.

- **250 MB - Arquivo anexado a um item de lista.** Aplica-se às listas da Microsoft e SharePoint listas - ambas com base na mesma plataforma de listas.

Para saber mais sobre restrições e limites ao usar o novo aplicativo Sincronização do OneDrive (OneDrive.exe), consulte Nomes de arquivo inválidos [e tipos de arquivo](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

### <a name="moving-and-copying-across-sites"></a>Mover e copiar em sites

Copiar/mover vários arquivos em uma única operação tem três requisitos:

- No máximo 100 GB de tamanho total de arquivo
- Não mais de 30.000 arquivos
- Cada arquivo deve ter menos de 15 GB

### <a name="sync"></a>Sincronizar

Para obter um desempenho ideal, recomendamos armazenar não mais de 300.000 arquivos em um único OneDrive ou biblioteca de sites de equipe. Embora SharePoint Online possa armazenar 30 milhões de documentos por biblioteca, para um desempenho ideal, recomendamos sincronizar não mais de 300.000 arquivos em todas as bibliotecas de documentos. Além disso, os mesmos problemas de desempenho podem ocorrer se você tiver 300.000 itens ou mais em todas as bibliotecas que estiver sincronizando, mesmo se você não estiver sincronizando todos os itens nessas bibliotecas. Se você usar o cliente de sincronização OneDrive for Business anterior (Groove.exe), o limite de sincronização por biblioteca será de 20.000 itens (incluindo 5.000 itens por site de equipe).

### <a name="versions"></a>Versões

50.000 versões principais e 511 versões secundárias.

### <a name="sharepoint-groups"></a>Grupos do SharePoint

Um usuário pode pertencer a 5.000 grupos por site (conjunto de sites), e cada grupo pode ter até 5.000 usuários. Você pode ter até 10.000 grupos por site (conjunto de sites).

> [!NOTE]
> Para limites de grupo do Azure AD, consulte Limites e restrições de serviço do [Azure AD,](/azure/active-directory/users-groups-roles/directory-service-limits-restrictions) pois esses limites podem afetar o gerenciamento de associação de sites públicos e privados.

### <a name="managed-metadata"></a>Metadados gerenciados

1 milhão de termos totais, com um total de 2 milhões de rótulos de termos e 1 milhão de propriedades de termos (esses limites são para termos globais & nível de site combinados). 1.000 conjuntos de termos globais e 1.000 grupos globais.

### <a name="overall-site-metadata"></a>Metadados gerais do site

1000 GB por site (metadados raramente atingem esse tamanho).

### <a name="subsites"></a>Subsites

2.000 por site (conjunto de sites). Recomendamos criar sites e organizá-los em hubs em vez de criar subsites. Se você usar subsites, recomendamos limitar seu número (especialmente em sites com tráfego intenso).

> [!NOTE]
> Sua organização está limitada a 2.000 sites de hub. Talvez você não precise de um site de hub para cada função, e é importante fazer algum planejamento antes de criar hubs. Para obter mais informações, visite [Planning your SharePoint hub sites](/sharepoint/planning-hub-sites).

### <a name="sharepoint-hosted-applications"></a>SharePoint aplicativos hospedados

20.000 instâncias por organização.

### <a name="users"></a>Usuários

2 milhões por conjunto de sites.

> [!NOTE]
> Não há um limite distinto para o número de convidados que você pode convidar para SharePoint sites. Para obter mais informações sobre compartilhamento externo, consulte [Visão geral do compartilhamento externo.](/sharepoint/external-sharing-overview)

## <a name="see-also"></a>Confira também

[Limites de pesquisa para SharePoint](/sharepoint/search-limits)