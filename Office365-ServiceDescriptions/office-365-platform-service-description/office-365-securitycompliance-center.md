---
title: Centro de conformidade e segurança
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5a693243-2f13-4c7e-af1a-779c0752ae35
description: O Centro &amp; de Conformidade de Segurança foi projetado para ajudá-lo a gerenciar recursos de conformidade no Office 365 para sua organização. Os links de recursos de conformidade existentes do SharePoint e do Exchange reúnem recursos de conformidade no Office 365.
ms.openlocfilehash: 4daf754f5472620482eced63a9970b05a4e61a6c
ms.sourcegitcommit: 02dd535b01c4ca7b19b43188ddd1a1f02c01afb5
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/05/2021
ms.locfileid: "50460190"
---
# <a name="security-amp-compliance-center"></a>Security &amp; Compliance Center

O [Centro &amp; de Conformidade](https://protection.office.com/) de Segurança foi projetado para ajudá-lo a gerenciar recursos de conformidade no Office 365 para sua organização. Links to existing SharePoint and Exchange compliance features bring together compliance capabilities across Office 365.
  
> [!NOTE]
> Currently, many of the compliance features are still accessible through service-specific management interfaces, such as the Exchange admin center (EAC). However, this will change in the future as more service-independent compliance features are added to the Security &amp; Compliance Center.

Para ver as opções de licenciamento de seus usuários para se beneficiar dos recursos de conformidade do Microsoft 365 a partir de 1º de abril de 2020, baixe a Comparação detalhada de Licenciamento de Conformidade do Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)
  
## <a name="security-amp-compliance-center-availability-for-business-and-enterprise-plans"></a>Disponibilidade &amp; do Centro de Conformidade de Segurança para planos corporativos e corporativos

| Recurso | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Microsoft 365 Business Premium | Office 365 E1, Office 365 US Government G1 | Office 365 E3, Office 365 US Government G3 | Office 365 E5 | Office 365 F3, Office 365 US Government F3|
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|[Acesso ao Centro de &amp; Conformidade de Segurança](https://docs.microsoft.com/office365/securitycompliance/go-to-the-securitycompliance-center)  |Sim   |Sim   |Sim   |Sim   |Sim   |Sim   |Sim   |
|[Prevenção contra perda de dados para Exchange Online, SharePoint Online e OneDrive for Business](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies)<sup>2</sup> | Não | Não  |Sim   | Sim | Sim | Sim | Não  |
|[Rótulos de sensibilidade manual](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)<sup>3</sup> | Não | Não  |Não   | Sim | Sim | Sim | Não  |
|[Casos de Descoberta eDiscovery](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases)  |Sim   |Sim   |Sim   |Sim   |Sim   |Sim   |Sim   |
|[Retém descobertas de eDiscovery (incluindo retém de Descoberta eDiscovery baseada em consulta)](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-4-place-content-locations-on-hold)  |Não   |Não   |Não  |Não   |Sim   |Sim   |Não   |
|[Exportação de Descobertas EDiscovery](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-6-export-the-results-of-a-content-search-associated-with-a-case)  |Não   |Não   |Não   |Não   |Sim   |Sim   |Não   |
|[Auditoria Básica](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)<sup>1</sup> |Sim   |Sim   |Sim|Sim   |Sim   |Sim   |Sim   |
|[Criptografia de Mensagens do Office 365 (OME) Básico](https://docs.microsoft.com/microsoft-365/compliance/ome)  |Não   |Não   |Não   |Não   |Sim  |Sim   |Não   |

<sup>1</sup> Os logs de auditoria de todos os planos que incluem a Auditoria Básica (exceto o E5) são mantidos por 90 dias. Como o E5 inclui Auditoria Avançada, os logs de auditoria são mantidos por até um ano. Além disso, você pode usar a API de Atividade de Gerenciamento do [Office 365](https://docs.microsoft.com/office/office-365-management-api/office-365-management-activity-api-reference) para recuperar eventos do log de auditoria unificado.

<sup>2 Requer</sup> o complemento de prevenção contra perda de dados do Office 365.

<sup>3 Os</sup> rótulos de sensibilidade também estão incluídos no Azure Information Protection P1 e P2.

## <a name="security-amp-compliance-center-availability-for-standalone-plans"></a>Disponibilidade &amp; do Centro de Conformidade de Segurança para planos autônomos

| Recurso | Exchange Online Plano 1 | Plano 2 do Exchange Online | Quiosque do Exchange Online | SharePoint Online Plano 1 | SharePoint Online Plano 2 | OneDrive for Business Plano 1 | OneDrive for Business Plano 2 | Skype for Business Online Plano 1 | Skype for Business Online Plano 2|
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|[Acesso ao Centro de &amp; Conformidade de Segurança](https://docs.microsoft.com/office365/securitycompliance/go-to-the-securitycompliance-center)  |Sim   |Sim   |Sim   |Sim   |Sim   |Sim   |Sim   |Sim   |Sim   |
|[Office 365 Cloud App Security](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)  |Não   |Não   |Não   |Não   |Não   |Não   |Não   |Não   |Sim   |
|[Gerenciamento de](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)ameaças , como filtragem de email e anti-malware   |Sim   |Sim   |Sim   |Sim   |Sim   |Sim   |Sim   |Sim   |Sim   |
|[Gerenciamento avançado de ameaças](https://docs.microsoft.com/office365/securitycompliance/office-365-ti), como o explorador de ameaças para campanhas de phishing   |Não   |Não   |Não   |Não   |Não   |Não   |Não   |Não   |Não  |
|[Sistema de Proteção de Dados do Cliente](https://docs.microsoft.com/office365/securitycompliance/customer-lockbox-requests)  |Não   |Não   |Não   |Não   |Não   |Não   |Não   |Não   |Não   |
|[Gerenciamento de dispositivo móvel](https://support.office.com/article/set-up-mobile-device-management-mdm-in-office-365-dd892318-bc44-4eb1-af00-9db5430be3cd)  |Sim   |Sim   |Sim   |Sim   |Sim   |Sim   |Sim   |Sim   |Sim   |
|[Prevenção contra perda de dados para Exchange Online, SharePoint Online e OneDrive for Business](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)<sup>9</sup>  |Não   |Sim   |Não   |Não   |Sim <sup>7<sup>  |Não  |Sim<sup>10</sup> |Não   |Sim   |
|[Prevenção contra perda de dados de comunicação para o Microsoft Teams](https://docs.microsoft.com/microsoft-365/compliance/dlp-microsoft-teams)  |Não   |Não   |Não   |Não   |Não   |Não   |Não   |Não   |Não   |
|[Barreiras de informações](https://docs.microsoft.com/office365/securitycompliance/information-barriers)  |Não   |Não   |Não   |Não   |Não   |Não   |Não   |Não   |Não   |
|[Governança de informações](https://docs.microsoft.com/office365/securitycompliance/retention-policies)<sup>1</sup>  |Sim<sup>2</sup>  |Sim   |Sim   |Sim   |Sim   |Sim<sup>10</sup>  |Sim<sup>10</sup>  |Sim   |Sim   |
|[Governança de informações avançadas](https://docs.microsoft.com/office365/securitycompliance/labels)<sup>3</sup>  |Não   |Não   |Não   |Não   |Não   |Não   |Não   |Não   |Não   |
|[Pesquisa de conteúdo](https://docs.microsoft.com/office365/securitycompliance/search-for-content)  |Sim   |Sim   |Sim   |Sim   |Sim  | Sim<sup>10</sup>  |Sim<sup>10</sup>  |Sim   |Sim   |
|[Casos de Descoberta eDiscovery](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases)  |Sim   |Sim   |Sim   |Sim   |Sim   |Sim<sup>10</sup>  |Sim<sup>10</sup>  |Não   |Não   |
|[Exportação de Descobertas EDiscovery](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-6-export-the-results-of-a-content-search-associated-with-a-case)  |Não   |Sim   |Não   |Não   |Sim   |Não  |Sim<sup>10</sup> |Não<sup>4</sup>  |Não<sup>4</sup>  |
|[Retém descobertas de eDiscovery (incluindo retém de Descoberta eDiscovery baseada em consulta)](https://support.office.com/article/eDiscovery-cases-in-the-Office-365-Security-Compliance-Center-8dd335ab-29d0-41c3-8dd8-9f7c7481e60c#step3_1)  |Não   |Sim   |Não   |Não   |Sim   |Não  |Sim<sup>10</sup> |Não<sup>4</sup>  |Não<sup>4</sup>  |
|[Descoberta Avançada 5](https://docs.microsoft.com/office365/securitycompliance/compliance20/overview-ediscovery-20)<sup></sup>  |Não   |Não   |Não   |Não   |Não   |Não   |Não   |Não   |Não   |
|[Arquivamento](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes)<sup>6</sup>  |Não   |Sim   |Não   |Sim   |Sim   |Sim<sup>10</sup> |Sim<sup>10</sup>  |Não   |Não   |
|[Auditoria Básica](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)<sup>8</sup>|Sim|Sim|Sim|Sim|Sim|Sim<sup>10</sup>|Sim<sup>10</sup>|Não|Não|
|Auditoria Avançada|Não|Não|Não|Não|Não|Não|Não|Não|Não|
|[Conformidade de comunicação (políticas de supervisão)](https://docs.microsoft.com/office365/securitycompliance/supervision-policies)  |Não   |Não   |Não   |Não   |Não   |Não   |Não   |Não   |Não   |
|[Criptografia de Mensagens do Office 365 (OME)](https://docs.microsoft.com/microsoft-365/compliance/ome)  |Não   |Sim   |Não   |Não   |Sim   |Não   |Não|Não|Não|
|[Criptografia de Mensagem Avançada do 365 Office](https://docs.microsoft.com/microsoft-365/compliance/ome-advanced-message-encryption)  |Não   |Não   |Não   |Não   |Sim   |Não   |Não|Não|Não|
|[Gerenciamento de Acesso Privilegiado](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-overview)  |Não   |Não   |Não   |Não   |Sim   |Não   |Não|Não|Não|

<sup>1</sup> A governança de informações permite que os usuários criem, publiquem e apliquem rótulos manualmente a documentos; importar dados usando o envio de unidade ou pela rede. Esses recursos estão disponíveis no E3 e no E5, com disponibilidade limitada apenas no E1. Para ver uma lista completa dos recursos disponíveis no E1, E3 e E5, consulte a Comparação detalhada de Licenciamento de Conformidade do Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

<sup>2</sup> Requer a compra Arquivamento do Exchange Online complemento.

<sup>3</sup> A governança avançada de informações permite que você mantenha informações importantes e exclua informações sem importância classificando informações com base em uma política de retenção ou exclusão ou ambos. Ele inclui ações inteligentes/automatizadas, como recomendar políticas, aplicar rótulos automaticamente aos dados, aplicar rótulos com base em tipos ou consultas de dados confidenciais, revisão de disposição e uso de filtros de importação inteligente. Ele também inclui o recurso Supervisão para revisar as comunicações dos funcionários para fins de segurança e conformidade.

<sup>4</sup> As conversas do Skype são armazenadas como parte da caixa de correio.

<sup>5</sup> A Descoberta Digital Avançada requer o Office 365 E5 ou uma licença de complemento.

<sup>6</sup> O arquivamento do Skype está dentro da caixa de correio do usuário.

<sup>7</sup> Inclui arquivos armazenados em repositórios do Microsoft Teams.

<sup>8</sup> Logs de auditoria para todos os planos que incluem a Auditoria Básica são mantidos por 90 dias. Além disso, você pode usar a API de Atividade de Gerenciamento do [Office 365](https://docs.microsoft.com/office/office-365-management-api/office-365-management-activity-api-reference) para recuperar eventos do log de auditoria unificado.

<sup>9</sup> Requer o complemento de prevenção contra perda de dados do Office 365.

<sup>10</sup> Limitado a arquivos armazenados no OneDrive for Business.

<sup>11</sup> Uma licença do Plano 2 ou Arquivamento do Exchange Online do Exchange Online é necessária para colocar uma caixa de correio de usuário em espera usando uma política de retenção.
  
## <a name="security-amp-compliance-center-availability-in-office-365-operated-by-21vianet"></a>Disponibilidade &amp; do Centro de Conformidade de Segurança no Office 365 operado pela 21Vianet

O Centro de Conformidade está disponível no plano E3 do Office 365 operado pela 21Vianet.
  
## <a name="security-amp-compliance-center-availability-in-office-365-germany"></a>Disponibilidade &amp; do Centro de Conformidade de Segurança no Office 365 Germany

O Centro de Conformidade & segurança está disponível para o Office 365 Germany. Para obter informações sobre o Office 365 Germany, consulte [Office 365 Germany](office-365-germany.md).
