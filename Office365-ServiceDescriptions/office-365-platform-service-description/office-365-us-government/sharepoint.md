---
title: SharePoint para ambientes do governo dos EUA
ms.author: mkashman
author: kaarins
manager: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Saiba mais sobre a disponibilidade de recursos do SharePoint para clientes de nuvem do governo dos EUA.
ms.openlocfilehash: 4e09ec8fda62fb5ce7a6e886799c5f35edd32cf5
ms.sourcegitcommit: e342174df76128430dfc8c971716da5c4b2942ac
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/28/2020
ms.locfileid: "48294187"
---
# <a name="sharepoint-for-us-government-environments"></a>SharePoint para ambientes do governo dos EUA

Este artigo fornece uma visão geral das diferenças de recursos entre a nuvem do governo dos EUA e a nuvem comercial, conforme listado na [Descrição do serviço do SharePoint](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-service-description). O SharePoint está disponível para os ambientes GCC (nuvem da Comunidade governamental), GCC alta e DoD. 

Para obter mais informações sobre a nuvem governamental, incluindo qualificação e compra, consulte [Microsoft 365 governamentais-como comprar](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy). Para comparar os planos do governo do Office 365, confira [office 365 governamental Plans](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements).

Para saber mais sobre pontos de extremidade necessários ao gerenciar a conectividade de rede, confira os pontos de extremidade do [office 365 governo dos EUA](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) ou do [Office 365 governo dos EUA](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business).

Além de aproveitar os recursos e as funcionalidades do Office 365, as organizações se beneficiam dos seguintes recursos, que são exclusivos dos ambientes de nuvem do governo dos EUA:

-   O conteúdo do cliente da sua organização é logicamente separado do conteúdo do cliente nos serviços comerciais do Office 365 da Microsoft.
-   O conteúdo do cliente da sua organização é armazenado dentro dos Estados Unidos.
-   O acesso ao conteúdo do cliente da sua organização é restrito à equipes selecionadas da Microsoft.
-   Os ambientes de nuvem governamentais estão em conformidade com certificações e confirações necessárias para os clientes do setor público dos EUA.

É nossa meta fornecer todos os recursos comerciais e funcionalidades do SharePoint aos ambientes de nuvem governamentais. Alguns recursos não estão disponíveis devido aos requisitos de clientes em nuvem governamental. Outros recursos estão chegando aos ambientes governamentais, mas ainda não estão disponíveis. Consulte as seções a seguir para saber mais sobre a disponibilidade de recursos nos ambientes de nuvem governamentais.

## <a name="developer-features"></a>Recursos para desenvolvedores

Não há diferenças conhecidas entre os recursos de desenvolvedor para clientes comerciais e aqueles para clientes da nuvem governamental.

- As conexões com aplicativos externos, como fontes de dados para suplementos, estão limitadas às fontes localizadas dentro dos limites de segurança do sistema suportados pelo seu ambiente governamental.
- A funcionalidade de serviços corporativos de conectividade (BCS) é suportada em cenários de conectividade nos quais as fontes de dados permanecem acessíveis dentro do limite de segurança para o seu serviço de nuvem.

Se você usar aplicativos de terceiros em sites, revise as declarações de privacidade e conformidade fornecidas por terceiros ao avaliar o uso apropriado desses serviços para sua organização. Aplicativos e serviços de terceiros podem envolver o armazenamento, a transmissão e o processamento dos dados do cliente da sua organização em sistemas de terceiros que estão fora da nuvem governamental e, portanto, não são cobertos por seus compromissos de conformidade e proteção de dados. 

## <a name="it-admin-features"></a>Recursos de administração de ti

Aqui estão as diferenças entre os recursos de administração de ti para clientes comerciais e aqueles para clientes da nuvem governamental.

- A alteração de um endereço de site não está disponível para clientes do GCC superior
- O SharePoint Server híbrido não está disponível para todos os clientes de nuvem governamental
- A ferramenta de migração do SharePoint e o Gerenciador de migração exigem uma alteração na configuração. Para obter informações, consulte [suporte à nuvem do SPMT governamental](/sharepointmigration/spmt-install-issues#government-cloud-support).
- Ainda não há suporte para Mover.io
- Multigeográfico não está disponível para todos os clientes de nuvem do governo

Para obter informações sobre a migração do FastTrack, consulte a [Descrição do serviço do governo dos EUA do Office 365](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#data-migrations-performed-by-fasttrack).

## <a name="security-and-compliance-features"></a>Recursos de segurança e conformidade

Não há diferenças conhecidas entre os recursos de segurança e conformidade para clientes comerciais e para os clientes de nuvem governamental.

Para obter informações sobre os seguintes recursos, consulte a [Descrição do serviço do governo dos EUA do Office 365](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features):
- Sistema de Proteção de Dados do cliente
- Prevenção de perda de dados (DLP)
- Descoberta eletrônica (pesquisa de conteúdo, retenção, exportação)
- Proteção Avançada contra Ameaças do Office 365 (ATP)
- Rótulos de confidencialidade

Para obter informações sobre os recursos do Azure Active Directory para o governo, consulte a [documentação de segurança e identidade do Azure governamental](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory). 

Para obter informações sobre os recursos de proteção de informações do Azure para o governo, consulte a [Descrição do serviço do governo Premium de proteção de informações do Azure](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description) 

## <a name="sites-and-content"></a>Sites e conteúdo

Aqui estão as diferenças entre os recursos de sites e de conteúdo para clientes comerciais e aqueles para clientes da nuvem governamental:

- As Web Parts que dependem de conexões com os serviços de Internet, como o Amazon Kindle, o Bing Maps, o Twitter e o YouTube Web Parts, não funcionarão conforme o esperado
- A biblioteca de ativos da organização não está disponível
- A adição de listas e páginas ao Teams não está disponível para clientes GCC altos e DoD

## <a name="search-features"></a>Recursos de pesquisa

Aqui estão as diferenças entre os recursos de pesquisa para clientes comerciais e aqueles para clientes da nuvem governamental:

- A integração com o Microsoft Search não está disponível.

## <a name="sharing-and-sync"></a>Compartilhamento e sincronização

Para obter diferenças de recursos entre a nuvem comercial e os ambientes de nuvem governamentais, consulte [compartilhamento de arquivos](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/gcc-high-and-dod#file-sharing).

## <a name="plan-for-governance"></a>Planejar governança

Sua mudança para a nuvem oferece experiências de transformativa com controles de administração internos. Determine seus requisitos de governança e como você pode atendê-los. Vá para [plano de governança para transformar o trabalho em equipe com o Microsoft 365](https://resources.techcommunity.microsoft.com/teamwork-governance/) para obter mais informações. Você encontrará orientações sobre grupos do Office 365, SharePoint, Teams e muito mais.

## <a name="deploy-sharepoint-for-collaboration"></a>Implantar o SharePoint para colaboração

Depois de configurar sua organização na nuvem do governo dos EUA da Microsoft, siga o caminho de implantação recomendado descrito na [central de recursos de adoção do SharePoint](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/). Não se esqueça de envolver seus campeões de adoção e de gerenciamento de mudanças.
Você também pode trabalhar com o [FastTrack](https://www.microsoft.com/fasttrack) ou seu parceiro escolhido para distribuir o serviço para os seus usuários.
Visite a [central de confiabilidade da Microsoft](https://www.microsoft.com/trust-center) para saber mais sobre como a Microsoft aborda segurança, privacidade e conformidade, princípios fundamentais sobre como capacitar as organizações a atender seus clientes.
