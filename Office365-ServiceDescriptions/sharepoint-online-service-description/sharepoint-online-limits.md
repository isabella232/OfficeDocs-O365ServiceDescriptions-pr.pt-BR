---
title: Limites do SharePoint
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Conheça os limites do SharePoint para Microsoft 365 e planos autônomos.
ms.openlocfilehash: c228774bbbb1db9b6edc1d3cc05ff159b1ca9a3e
ms.sourcegitcommit: 95e48bdbe2167ca3f7b4d9830330b4a594f296b2
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/23/2021
ms.locfileid: "53537217"
---
# <a name="sharepoint-limits"></a>Limites do SharePoint

Saiba mais sobre os limites de serviço no SharePoint para Microsoft 365.
  
## <a name="limits-by-plan"></a>Limites por plano 

| Recurso | Microsoft 365 Business Basic, Business Standard ou Business Premium | Microsoft 365 E3 ou E5, Office 365 E1, E3 ou E5 ou SharePoint Plano 1 ou 2 | Microsoft 365 F1 ou F3, Office 365 F3 |
|:-----|:-----|:-----|:-----|
|Armazenamento total por organização<sup>1, 2, 6</sup> <br/> |1 TB mais 10 GB por licença adquirida<sup>3</sup>  <br/> |1 TB mais 10 GB por licença adquirida<sup>3</sup> <br/> |1 TB<sup>3</sup> <br/> |
|Armazenamento máximo por site (conjunto de sites)<sup>4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB<sup>5</sup> <br/> |
|Sites (conjuntos de sites) por organização  <br/> |2 milhões<sup>6</sup> <br/> |2 milhões<sup>6</sup> <br/> |Dois milhões<br/> |
|Número de usuários  <br/> |Até 300  <br/> |1 a 500.000<sup>7</sup> <br/> |1 a 500.000<sup>7</sup> <br/> |
   
<sup>1</sup> [Saiba como localizar o armazenamento total e disponível para sua organização](/sharepoint/manage-site-collection-storage-limits). Você pode adquirir um volume ilimitado de armazenamento adicional do SharePoint. Confira [Adicionar espaço de armazenamento à sua assinatura](/office365/admin/subscriptions-and-billing/add-storage-space). 
<br/><sup>2</sup> Recomendamos monitorar a Lixeira e esvaziá-la regularmente. O espaço de armazenamento que ela usa faz parte do limite de armazenamento de arquivo total da organização. 
<br/> <sup>3</sup> Se você tiver uma assinatura Microsoft 365 e um complemento de Armazenamento de Arquivos Extra do Office 365, os valores de armazenamento serão adicionados. 
<br/> <sup>4</sup> Este é o *limite* de armazenamento para um único site (anteriormente chamado de "conjunto de sites"), não a quantidade de armazenamento *fornecida* para cada site. Esse limite se aplica a todos os tipos de sites, incluindo sites de equipe conectados a grupos do Office 365 e OneDrive. Os administradores do SharePoint podem [definir manualmente limites de armazenamento mais baixos](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits). 
<br/> <sup>5 Os</sup> trabalhadores de linha de frente não podem administrar SharePoint sites. 
<br/> <sup>6</sup> Não incluir o OneDrive criado para cada usuário licenciado. 
<br/> <sup>7</sup> Se você tiver mais de 500 mil usuários, entre em contato com um representante da Microsoft. 
  
## <a name="service-limits-for-all-plans"></a>Limites de serviço para todos os planos

### <a name="items-in-lists-and-libraries"></a>Itens em listas e bibliotecas

Uma lista pode ter até 30 milhões de itens, e uma biblioteca pode ter até 30 milhões de arquivos e pastas. Quando uma lista, biblioteca ou pasta contém mais de 100 mil itens, você não pode interromper a herança de permissões na lista, biblioteca ou pasta. Também não é possível herdar novamente as permissões nele. No entanto, você ainda pode interromper a herança nos itens individuais dentro dessa lista, biblioteca ou pasta, até o número máximo de permissões exclusivas na lista ou biblioteca (consulte a próxima seção). Para saber mais sobre outras restrições para a visualização de listas grandes, confira [Gerenciar listas e bibliotecas grandes no Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784).

### <a name="unique-security-scopes-per-list-or-library"></a>Escopos de segurança exclusivos por lista ou biblioteca

Para listas grandes, o design deve ter o mínimo de permissões exclusivas possível e permanecer abaixo de 5 mil no total.

### <a name="file-size-and-file-path-length"></a>Tamanho do arquivo e comprimento do caminho do arquivo

- **250 GB: limite de upload de arquivos.** Aplica-se a cada arquivo individual carregado na guia Arquivos do Microsoft Teams, bibliotecas de documentos do SharePoint, pastas do OneDrive e conversas do Yammer.

- **250 MB: arquivo anexado a um item de lista.** Aplica-se às listas do Microsoft Lists e do SharePoint , ambas com base na mesma plataforma de listas.

Para saber mais sobre restrições e limites ao usar o novo aplicativo de sincronização do OneDrive (OneDrive.exe), consulte [Nomes de arquivo e tipos de arquivo inválidos](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

### <a name="moving-and-copying-across-sites"></a>Movendo e copiando entre sites

Há três requisitos para Copiar ou Mover vários arquivos em uma única operação:

- No máximo 100 GB de tamanho total de arquivo
- Não mais que 30 mil arquivos
- Um arquivo deve ter menos de 15 GB.

### <a name="sync"></a>Sincronização

Para obter um desempenho d sincronização ideal, recomendamos armazenar no máximo 300 mil arquivos em uma única biblioteca do site de equipe ou do OneDrive. Embora o SharePoint Online possa armazenar 30 milhões de documentos por biblioteca, para obter um desempenho ideal é recomendável sincronizar não mais que 300 mil arquivos em todas as bibliotecas de documentos. Além disso, os problemas de desempenho podem ocorrer mesmo se você tiver 300 mil itens ou mais em todas as bibliotecas que você está sincronizando, mesmo que não esteja sincronizando todos os itens dessas bibliotecas. Se você usa o cliente de sincronização anterior do OneDrive for Business (Groove.exe), o limite de sincronização por biblioteca é de 20 mil itens (incluindo 5 mil itens por site de equipe).

### <a name="versions"></a>Versões

50 mil versões principais e 511 versões secundárias.

### <a name="sharepoint-groups"></a>Grupos do SharePoint

Um usuário pode pertencer a 5 mil grupos por site (conjunto de sites) e cada grupo pode ter até 5 mil usuários. Você pode ter até 10 mil grupos por conjunto de sites.

> [!NOTE]
> Para limites de grupo do Azure AD, consulte [Restrições e limites de serviço do Azure AD](/azure/active-directory/users-groups-roles/directory-service-limits-restrictions) pois esses limites podem afetar o gerenciamento de associação de sites de grupo públicos e privados.

### <a name="managed-metadata"></a>Metadados gerenciados

1 milhão de termos totais, com um total de 2 milhões de rótulos de termos e 1 milhão de propriedades de termos (esses limites são para termos globais e de nível de site combinados). 1.000 conjuntos de termos globais e 1.000 grupos globais.

### <a name="overall-site-metadata"></a>Metadados gerais do site

1000 GB por site (os metadados raramente atingem esse tamanho).

### <a name="subsites"></a>Subsites

2 mil por conjunto de sites Recomendamos criar sites e organizá-los em hubs em vez de criar subsites. Se você usar subsites, recomendamos limitar o número (especialmente em sites com tráfego pesado).

> [!NOTE]
> Sua organização está limitada a 2 mil sites de hub. Talvez você não precise de um site de hub para cada função e é importante fazer algum planejamento antes de criar hubs. Para obter mais informações, visite [Planejamento de sites do hub do SharePoint](/sharepoint/planning-hub-sites).

### <a name="sharepoint-hosted-applications"></a>Aplicativos hospedados pelo SharePoint

20 mil instâncias por organização.

### <a name="users"></a>Usuários

2 milhões por conjunto de sites

> [!NOTE]
> Não há nenhum limite distinto para o número de convidados que você pode convidar para sites do SharePoint. Para obter mais informações sobre compartilhamento externo, consulte [Visão geral do compartilhamento externo](/sharepoint/external-sharing-overview).

## <a name="see-also"></a>Confira também:

[Limites de pesquisa do SharePoint](/sharepoint/search-limits)