---
title: SharePoint ambientes governamentais dos EUA
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.reviewer: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Saiba mais sobre a SharePoint de recursos para clientes de nuvem do governo dos EUA.
ms.openlocfilehash: cec996804ab0d402d2bcccd89b8bbfb5e7f70905
ms.sourcegitcommit: c34f7acea5e172eb2b29ae42f71e69932def6ac0
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/20/2021
ms.locfileid: "51900771"
---
# <a name="sharepoint-for-us-government-environments"></a>SharePoint ambientes governamentais dos EUA

Este artigo fornece uma visão geral das diferenças de recursos entre a nuvem governamental dos EUA e a nuvem comercial, conforme listado na descrição [SharePoint serviço.](../../sharepoint-online-service-description/sharepoint-online-service-description.md) SharePoint está disponível para os ambientes Nuvem da Comunidade Governamental (GCC), GCC High e DoD. 

Para obter mais informações sobre a nuvem governamental, incluindo [qualificação](./microsoft-365-government-how-to-buy.md)e compras, consulte Microsoft 365 Government - how to buy . Para comparar Office 365 Government planos, consulte [Office 365 Government planos](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements).

Para saber mais sobre os pontos de extremidade necessários ao gerenciar [Office 365](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) conectividade de rede, consulte os pontos de extremidade do GCC [Office 365 DoD](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)do governo dos EUA.

Além de aproveitar os recursos e recursos do Office 365, as organizações se beneficiam dos seguintes recursos exclusivos para os ambientes de nuvem do governo dos EUA:

-   O conteúdo do cliente da sua organização é logicamente segregado do conteúdo do cliente nos serviços comerciais Office 365 da Microsoft.
-   O conteúdo do cliente da sua organização é armazenado dentro dos Estados Unidos.
-   O acesso ao conteúdo do cliente da sua organização é restrito à equipes selecionadas da Microsoft.
-   Os ambientes de nuvem do governo estão em conformidade com certificações e acreditações necessárias para clientes do Setor Público dos EUA.

Nosso objetivo é fornecer todos os recursos e funcionalidades SharePoint comerciais para os ambientes de nuvem do governo. Alguns recursos não estão disponíveis devido aos requisitos dos clientes de nuvem do governo. Outros recursos estão chegando aos ambientes governamentais, mas ainda não estão disponíveis. Consulte as seções a seguir para saber mais sobre a disponibilidade de recursos nos ambientes de nuvem do governo.

## <a name="developer-features"></a>Recursos para desenvolvedores

Não há diferenças conhecidas entre os recursos de desenvolvedor para clientes comerciais e aqueles para clientes de nuvem do governo.

- As conexões com aplicativos externos, como fontes de dados para os complementos, são limitadas a fontes localizadas dentro dos limites de segurança do sistema suportados pelo seu ambiente governamental.
- Serviços Corporativos de Conectividade funcionalidade (BCS) é suportada para cenários de conectividade nos quais as fontes de dados permanecem acessíveis dentro do limite de segurança para seu serviço de nuvem.

Se você usar aplicativos de terceiros em sites, revise as instruções de privacidade e conformidade fornecidas pelos terceiros ao avaliar o uso apropriado desses serviços para sua organização. Aplicativos e serviços de terceiros podem envolver o armazenamento, a transmissão e o processamento dos dados do cliente da sua organização em sistemas de terceiros que estejam fora da nuvem governamental e, portanto, não cobertos por seus compromissos de conformidade e proteção de dados. 

## <a name="it-admin-features"></a>Recursos de administrador de IT

Aqui estão as diferenças entre os recursos de administrador de IT para clientes comerciais e aqueles para clientes de nuvem governamental.

- Alterar um endereço de site não está disponível para clientes GCC High
- O SharePoint Server híbrido não está disponível para todos os clientes de nuvem do governo
- A SharePoint de Migração e o Gerenciador de Migração exigem uma alteração de configuração. Para obter informações, consulte [Suporte a nuvem governamental do SPMT.](/sharepointmigration/spmt-install-issues#government-cloud-support)
- Mover.io ainda não há suporte
- Multi-geo não está disponível para todos os clientes de nuvem do governo

Para obter informações sobre a migração do FastTrack, consulte [Office 365 descrição do serviço do Governo dos EUA.](./office-365-us-government.md#data-migrations-performed-by-fasttrack)

## <a name="security-and-compliance-features"></a>Recursos de segurança e conformidade

Não há diferenças conhecidas entre os recursos de segurança e conformidade para clientes comerciais e para clientes de nuvem do governo.

Para obter informações sobre recursos de segurança e conformidade, consulte [o Centro de Conformidade & Segurança.](../office-365-securitycompliance-center.md)

Para obter informações sobre Azure Active Directory recursos para o governo, consulte a documentação segurança do [Azure Government + Identity.](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory) 

Para obter informações sobre os recursos de Proteção de Informações do Azure para o governo, consulte a Descrição do serviço do [Azure Information Protection Premium Government Service .](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description) 

## <a name="sites-and-content"></a>Sites e conteúdo

Aqui estão as diferenças entre os sites e os recursos de conteúdo para clientes comerciais e aqueles para clientes de nuvem do governo:

- Web Parts que dependem de conexões com serviços da Internet, como o Amazon Kindle, Bing Mapas, Twitter e Web Parts do YouTube, não funcionarão conforme esperado
- A biblioteca de ativos da organização não está disponível
- Adicionar listas e páginas Teams não está disponível para clientes GCC High e DoD
- Graph funcionalidade no SharePoint Online para GCC High está desabilitada no momento. Qualquer serviço que depende do Microsoft Graph pode não estar disponível no momento
- Recursos que dependem de conexões com serviços da Internet, como a guia imagens de ações, não funcionarão conforme o esperado
- As notificações para atividade de arquivo e site não estão disponíveis
- A Web Part de notícias só receberá notícias do site atual. As notícias de sites selecionados ou de acúmulos de notícias de hub de sites associados não estão disponíveis para clientes GCC High e DoD

## <a name="search-features"></a>Recursos de pesquisa

Aqui estão as diferenças entre os recursos de pesquisa para clientes comerciais e aqueles para clientes de nuvem governamental:

- A Pesquisa da Microsoft não está disponível no GCC.

## <a name="sharing-and-sync"></a>Compartilhamento e sincronização

Para diferenças de recursos entre a nuvem comercial e os ambientes de nuvem do governo, consulte [Compartilhamento de arquivos](./gcc-high-and-dod.md#file-sharing).

## <a name="plan-for-governance"></a>Plano de governança

Sua mudança para a nuvem oferece experiências transformativas com controles de administrador internos. Determine seus requisitos de governança e como você pode atender a eles. Acesse [Plan for governance to transform teamwork with Microsoft 365](https://resources.techcommunity.microsoft.com/teamwork-governance/) for more information. Você encontrará orientações sobre Office 365 grupos, SharePoint, Teams e muito mais.

## <a name="deploy-sharepoint-for-collaboration"></a>Implantar SharePoint colaboração

Depois de configurar sua organização na nuvem governamental do Microsoft US, siga o caminho de implantação recomendado descrito no centro de recursos SharePoint [adoção.](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/) Certifique-se de se envolver com seus campeões de Gerenciamento de Alterações e Adoção.
Você também pode trabalhar com [o FastTrack ou](https://www.microsoft.com/fasttrack) seu parceiro escolhido para lançar o serviço para seus usuários.
Visite o [Centro de Confiamento](https://www.microsoft.com/trust-center) da Microsoft para saber mais sobre como a Microsoft aborda a segurança, privacidade e conformidade, princípios fundamentais para como capacitamos as organizações a atender seus clientes.
