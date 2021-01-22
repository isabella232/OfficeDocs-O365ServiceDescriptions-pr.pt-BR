---
title: Ambientes do SharePoint para o governo dos EUA
ms.author: office365servicedesc
author: pamelaar
ms.reviewer: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Saiba mais sobre a disponibilidade de recursos do SharePoint para clientes de nuvem do governo dos EUA.
ms.openlocfilehash: b0f36ea92b856a3fa9c1bf4ddd4cb4265655d1ae
ms.sourcegitcommit: 9961f5111b2b8b871183afcd03fcfb7fc05da4fc
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 01/21/2021
ms.locfileid: "49919744"
---
# <a name="sharepoint-for-us-government-environments"></a>Ambientes do SharePoint para o governo dos EUA

Este artigo fornece uma visão geral das diferenças de recursos entre a nuvem do governo dos EUA e a nuvem comercial, conforme listado na [descrição do serviço do SharePoint.](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-service-description) O SharePoint está disponível para os ambientes Government Community Cloud (GCC), GCC High e DoD. 

Para obter mais informações sobre a nuvem governamental, incluindo qualificação e compras, consulte [Microsoft 365 Government - como comprar](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy). Para comparar planos do Office 365 Government, confira [planos do Office 365 Government.](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)

Para saber mais sobre os pontos de extremidade necessários ao gerenciar a conectividade de rede, consulte os pontos de extremidade do [Office 365 U.S. Government GCC High](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) ou pontos de extremidade do Office [365 U.S. Government DoD.](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)

Além de aproveitar os recursos e capacidades do Office 365, as organizações se beneficiam dos seguintes recursos exclusivos dos ambientes de nuvem do governo dos EUA:

-   O conteúdo do cliente da sua organização é logicamente separado do conteúdo do cliente nos serviços comerciais do Office 365 da Microsoft.
-   O conteúdo do cliente da sua organização é armazenado dentro dos Estados Unidos.
-   O acesso ao conteúdo do cliente da sua organização é restrito à equipes selecionadas da Microsoft.
-   Os ambientes de nuvem governamentais estão em conformidade com certificações e certificações necessárias para clientes do Setor Público dos EUA.

Nosso objetivo é fornecer todos os recursos comerciais e funcionalidades do SharePoint para os ambientes de nuvem governamentais. Alguns recursos não estão disponíveis devido aos requisitos dos clientes de nuvem governamentais. Outros recursos estão chegando aos ambientes governamentais, mas ainda não estão disponíveis. Consulte as seções a seguir para saber mais sobre a disponibilidade de recursos nos ambientes de nuvem governamentais.

## <a name="developer-features"></a>Recursos para desenvolvedores

Não há diferenças conhecidas entre os recursos de desenvolvedor para clientes comerciais e aqueles para clientes de nuvem governamentais.

- As conexões com aplicativos externos, como fontes de dados para os complementos, são limitadas a fontes localizadas dentro dos limites de segurança do sistema suportados pelo seu ambiente governamental.
- A funcionalidade Business Connectivity Services (BCS) é suportada para cenários de conectividade nos quais as fontes de dados permanecem acessíveis dentro do limite de segurança para seu serviço de nuvem.

Se você usar aplicativos de terceiros em sites, revise as declarações de privacidade e conformidade fornecidas por terceiros ao avaliar o uso apropriado desses serviços para sua organização. Aplicativos e serviços de terceiros podem envolver o armazenamento, a transmissão e o processamento de dados de clientes da sua organização em sistemas de terceiros que estejam fora da nuvem governamental e, portanto, não cobertos por seus compromissos de conformidade e proteção de dados. 

## <a name="it-admin-features"></a>Recursos de administrador de IT

Aqui estão as diferenças entre os recursos de administrador de IT para clientes comerciais e aqueles para clientes de nuvem governamentais.

- Alterar um endereço de site não está disponível para clientes GCC High
- O SharePoint Server híbrido não está disponível para todos os clientes de nuvem governamentais
- A Ferramenta de Migração do SharePoint e o Gerenciador de Migração exigem uma alteração de configuração. Para obter informações, consulte [suporte à nuvem governamental da SPMT.](/sharepointmigration/spmt-install-issues#government-cloud-support)
- Mover.io ainda não é suportado
- A multi-geo não está disponível para todos os clientes de nuvem governamentais

Para obter informações sobre a migração FastTrack, consulte a descrição do serviço [do Office 365 US Government.](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#data-migrations-performed-by-fasttrack)

## <a name="security-and-compliance-features"></a>Recursos de segurança e conformidade

Não há diferenças conhecidas entre os recursos de segurança e conformidade para clientes comerciais e aqueles para clientes de nuvem governamentais.

Para obter informações sobre os recursos de segurança e conformidade, consulte o [Centro de conformidade e & segurança.](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-securitycompliance-center)

Para obter informações sobre os recursos do Azure Active Directory para o governo, consulte a documentação de Segurança [do Azure Government + Identidade.](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory) 

Para saber mais sobre os recursos da Proteção de Informações do Azure para o governo, confira a Descrição do Serviço Governamental premium da Proteção de Informações do [Azure.](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description) 

## <a name="sites-and-content"></a>Sites e conteúdo

Aqui estão as diferenças entre os sites e os recursos de conteúdo para clientes comerciais e aqueles para clientes de nuvem governamentais:

- As Web Parts que dependem de conexões com serviços de Internet, como as web parts Amazon Kindle, Bing Maps, Twitter e YouTube, não funcionarão conforme o esperado
- A biblioteca de ativos da organização não está disponível
- Adicionar listas e páginas ao Teams não está disponível para clientes GCC High e DoD
- A funcionalidade do Graph no SharePoint Online para GCC High está desabilitada no momento. Qualquer serviço que depende do Microsoft Graph pode não estar disponível no momento

## <a name="search-features"></a>Recursos de pesquisa

Aqui estão as diferenças entre os recursos de pesquisa para clientes comerciais e aqueles para clientes de nuvem governamentais:

- A integração com a Pesquisa da Microsoft não está disponível.

## <a name="sharing-and-sync"></a>Compartilhamento e sincronização

Para diferenças de recursos entre a nuvem comercial e os ambientes de nuvem governamental, consulte [Compartilhamento de arquivos.](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/gcc-high-and-dod#file-sharing)

## <a name="plan-for-governance"></a>Planejar a governança

Sua mudança para a nuvem oferece experiências transformativas com controles de administrador internos. Determine seus requisitos de governança e como você pode atender a eles. Vá para [Planejar a governança para transformar o trabalho em equipe com o Microsoft 365](https://resources.techcommunity.microsoft.com/teamwork-governance/) para obter mais informações. Você encontrará orientações sobre Grupos do Office 365, SharePoint, Teams e muito mais.

## <a name="deploy-sharepoint-for-collaboration"></a>Implantar o SharePoint para colaboração

Depois de configurar sua organização na nuvem do governo dos EUA da Microsoft, siga o caminho de implantação recomendado descrito na central de recursos de adoção [do SharePoint.](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/) Certifique-se de se envolver com seus campeões de Adoção e Gerenciamento de Mudanças.
Você também pode trabalhar com [o FastTrack](https://www.microsoft.com/fasttrack) ou seu parceiro escolhido para lançar o serviço para seus usuários.
Visite a [Central de Confiabilidade](https://www.microsoft.com/trust-center) da Microsoft para saber mais sobre como a Microsoft aborda a segurança, privacidade e conformidade, princípios fundamentais de como capacitamos as organizações a atender seus clientes.
