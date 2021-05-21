---
title: Microsoft 365 de licenciamento para conformidade & segurança
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.reviewer: v-trscho
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Este artigo fornece diretrizes de licenciamento Microsoft 365 conformidade para ajudar a evitar possíveis interrupções no serviço devido ao acesso não licenciado.
ms.openlocfilehash: d4ddb9c492cccef13c86e450c64a2eb6efe61eaa
ms.sourcegitcommit: adcacf68ac75c4db2229ebf55be9c75aecd3070b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52546008"
---
# <a name="microsoft-365-licensing-guidance-for-security-amp-compliance"></a>Microsoft 365 de licenciamento para conformidade com &amp; a segurança

Para os fins deste artigo, um serviço de nível de locatário é um serviço online que, quando comprado para qualquer usuário no locatário (autônomo ou como parte dos planos do Office 365 ou Microsoft 365) é ativado em parte ou completo para todos os usuários no &mdash; &mdash; locatário. Embora alguns usuários não autorizados possam, tecnicamente, acessar o serviço, uma licença é necessária para qualquer usuário que você pretenda beneficiar com o serviço.

> [!NOTE]
> Alguns serviços de locatários atualmente não são capazes de limitar benefícios a usuários específicos. Os esforços devem ser feitos para limitar os benefícios do serviço aos usuários licenciados. Isso ajudará a evitar possíveis interrupções de serviço para sua organização depois que os recursos de direcionamento estão disponíveis.

Para ver as opções de licenciamento de seus usuários para se beneficiarem de Microsoft 365 de conformidade, baixe a Comparação detalhada Microsoft 365 Licenciamento de Conformidade. [(PDF)](https://www.microsoft.com/download/details.aspx?id=103010)  |  [(Excel)](https://www.microsoft.com/download/details.aspx?id=103006)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure Active Directory A Proteção de Identidade é um recurso do plano P2 do Azure Active Directory Premium que permite detectar possíveis vulnerabilidades que afetam as identidades da sua organização, configurar respostas automatizadas para ações suspeitas detectadas relacionadas às identidades da sua organização e investigar incidentes suspeitos e tomar as medidas apropriadas para resolvê-los.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os analistas e profissionais de segurança da SecOps se beneficiam de ter exibições consolidadas de usuários sinalizados e eventos de risco com base em algoritmos de aprendizado de máquina. Os usuários finais se beneficiam da proteção automática fornecida por meio do Acesso Condicional baseado em risco e da segurança aprimorada fornecida atuando em vulnerabilidades.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Enterprise Mobility + Security O E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security e o Azure Active Directory Premium Plano 2 fornecem os direitos para que um usuário se beneficie Azure Active Directory Proteção de Identidade.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos da Proteção de Identidade do Azure AD são habilitados no nível do locatário para todos os usuários do locatário. Para obter informações sobre a Proteção de Identidade do Azure AD, consulte [O que é a Proteção de Identidade?](/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os administradores podem escopo da Proteção de Identidade do Azure AD atribuindo políticas de risco que definem o nível de redefinições de senha e permitindo o acesso apenas para usuários licenciados. Para obter instruções sobre como escopo das implantações da Proteção de Identidade do Azure AD, consulte Como configurar [e habilitar políticas de risco.](/azure/active-directory/identity-protection/howto-sign-in-risk-policy)

## <a name="azure-active-directory-identity-governance"></a>Azure Active Directory Governança de Identidade

Azure Active Directory A Governança de Identidade permite equilibrar a necessidade da sua organização de segurança e produtividade dos funcionários com os processos corretos e a visibilidade. Ele usa gerenciamento de direitos, avaliações de acesso, gerenciamento de identidade privilegiada e políticas de termos de uso para garantir que as pessoas certas tenham acesso aos recursos corretos.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Azure Active Directory A Governança de Identidade aumenta a produtividade dos usuários, facilitando a solicitação de acesso a aplicativos, grupos e Microsoft Teams em um pacote de acesso. Os usuários também podem ser configurados como aprovadores, sem envolver administradores. Para análises de acesso, os usuários podem revisar associações de grupos com recomendações inteligentes para tomar medidas em intervalos regulares.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Enterprise Mobility + Security O E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security e o Azure Active Directory Premium Plano 2 fornecem os direitos para que um usuário se beneficie Azure Active Directory Governança de Identidade.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Os recursos de Governança de Identidade do Azure AD estão habilitados no nível do locatário, mas implementados por usuário. Para obter informações sobre a Governança de Identidade do Azure AD, consulte O que é a Governança de Identidade do [Azure AD?](/azure/active-directory/governance/identity-governance-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os administradores podem escopo da Governança de Identidade do Azure AD atribuindo pacotes de acesso, análises de acesso ou gerenciamento de identidade privilegiada apenas para usuários licenciados. Para obter instruções sobre como escopo das implantações de Governança de Identidade do Azure AD, consulte:

- [Requisitos de licença de gerenciamento de direitos do Azure AD](/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Requisitos de licença de revisão de acesso do Azure AD](/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [Requisitos de licença para usar Privileged Identity Management](/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="microsoft-defender-for-identity"></a>Microsoft Defender para Identidade?

O Microsoft Defender for Identity (anteriormente a Proteção Avançada contra Ameaças do Azure) é um serviço de nuvem que ajuda a proteger ambientes híbridos corporativos contra vários tipos de ataques cibernéticos direcionados avançados e ameaças internas.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os analistas secOp e profissionais de segurança se beneficiam da capacidade do Microsoft Defender for Identity de detectar e investigar ameaças avançadas, identidades comprometidas e ações internas mal-intencionadas. Os usuários finais se beneficiam tendo seus dados monitorados pelo Microsoft Defender para Identidade.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Enterprise Mobility + Security O E5/A5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security e o Microsoft Defender for Identity para Usuários fornecem os direitos de benefício do Microsoft Defender para Identidade.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos do Microsoft Defender para Identidade são habilitados no nível do locatário para todos os usuários dentro do locatário. Para obter informações sobre como configurar o Azure ATP, consulte [Create your Microsoft Defender for Identity instance](/defender-for-identity/install-step1).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

No momento, os serviços do Microsoft Defender para Identidade não são capazes de limitar recursos a usuários específicos. Você deve licenciar todos os usuários que pretende beneficiar.

## <a name="microsoft-defender-for-office-365"></a>Microsoft Defender para Office 365

O Microsoft Defender para Office 365 (anteriormente Office 365 Proteção Avançada contra Ameaças) ajuda a proteger as organizações contra ataques sofisticados, como phishing e malware de dia zero. O Microsoft Defender para Office 365 também fornece informações ativas correlacionando sinais de uma ampla variedade de dados para ajudar a identificar, priorizar e fornecer recomendações sobre como lidar com possíveis ameaças.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

O Microsoft Defender para Office 365 protege os usuários contra ataques sofisticados, como phishing e malware de dia zero. Para ver a lista completa de serviços fornecidos no Plano 1 e no Plano 2, consulte [Microsoft Defender for Office 365](/microsoft-365/security/office-365-security/office-365-atp).

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço? 

O Microsoft Defender para planos 1 e 2 do Office 365, Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security e Microsoft 365 Business Premium fornecem os direitos para um usuário se beneficiar do Microsoft Defender para Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, o Microsoft Defender para Office 365 recursos são habilitados no nível de locatário para todos os usuários dentro do locatário. Para obter informações sobre como configurar o Microsoft Defender para Office 365 para usuários licenciados, consulte [Microsoft Defender for Office 365](/microsoft-365/security/office-365-security/office-365-atp).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Para escopo do Microsoft Defender para Office 365, siga as políticas de implantação Cofre Links e Cofre Anexos:

- Para obter informações sobre como configurar Cofre links para usuários licenciados, consulte [Cofre Links no Microsoft Defender para Office 365](/microsoft-365/security/office-365-security/atp-safe-links).

- Para obter informações sobre como configurar Cofre anexos para usuários [licenciados,](/microsoft-365/security/office-365-security/atp-safe-attachments)consulte Cofre Anexos no Microsoft Defender para Office 365 .

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security (OCAS) é um subconjunto de Microsoft Cloud App Security, com recursos limitados a Office 365 e sem segurança adicional para aplicativos de nuvem de terceiros e serviços IaaS.

O OCAS dá visibilidade às organizações sobre seus aplicativos e serviços de nuvem de produtividade, fornece análises sofisticadas para identificar e combater ameaças cibernéticas e permite que elas controlem como os dados viajam através &mdash; Office 365.

Para comparar recursos, consulte [Diferenças entre Microsoft Cloud App Security e Office 365 Cloud App Security](/cloud-app-security/editions-cloud-app-security-o365).

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

O OCAS descobre o Shadow IT, fornece proteção contra ameaças em Office 365 e pode controlar quais aplicativos têm permissão para acessar dados.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Office 365 O E5/A3/A5/G5 fornece os direitos para um usuário se beneficiar do OCAS.
Para obter mais informações, consulte Microsoft Cloud App Security [Datasheet de Licenciamento.](https://www.aka.ms/mcaslicensing)

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos do OCAS são habilitados no nível do locatário para todos os usuários dentro do locatário.

Para obter informações sobre como configurar o serviço, consulte [Configuração básica para Cloud App Security](/cloud-app-security/general-setup).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os administradores podem escopo de implantações OCAS para impor como determinados aplicativos são acessados e limitar grupos de usuários monitorados por Office 365 Cloud App Security. Para obter mais informações, consulte [Implantação com escopo](/cloud-app-security/scoped-deployment).

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) é uma solução CASB (Agente de Segurança do Cloud Access) que dá às organizações visibilidade de seus aplicativos e serviços de nuvem, fornece análises sofisticadas para identificar e combater ameaças cibernéticas e permite que elas controlem como os dados viajam por qualquer aplicativo de &mdash; nuvem.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

O MCAS descobre e avalia o Shadow IT, fornece proteção contra ameaças em aplicativos de nuvem de terceiros e primeiro e protege informações em aplicativos de nuvem de terceiros e primeiro.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

MCAS, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security, conformidade Microsoft 365 E5/A5/G5 e Microsoft 365 Proteção e Governança de Informações fornecem os direitos para um usuário se beneficiar do MCAS.

O Azure AD P1 fornece os direitos para que um usuário se beneficie dos recursos de Descoberta no MCAS.

Para se beneficiar dos recursos de Controle de Aplicativo de Acesso Condicional no MCAS, os usuários também devem ser licenciados para o Azure Active Directory P1, que está incluído no Enterprise Mobility + Security E3/A3/G3, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E3/A3/G3, Microsoft 365 E5/A5/G5 e Microsoft 365 E5/A5/G5 Security.

Para se beneficiar da rotulagem automática do lado do cliente, os usuários devem ser licenciados para o Azure Information Protection P2, que está incluído no Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, conformidade com Microsoft 365 E5/A5/G5 e Microsoft 365 Proteção e Governança de Informações.

> [!NOTE]
> A rotulagem automática do lado do servidor requer Proteção de Informações para Office 365 - Premium licenças ( `MIP_S_CLP2` ou `efb0351d-3b08-4503-993d-383af8de41e3` ). Para referência, consulte [Nomes de produto e identificadores de](/azure/active-directory/enterprise-users/licensing-service-plan-reference)plano de serviço para licenciamento .

Para obter mais informações, consulte Microsoft Cloud App Security [Datasheet de Licenciamento.](https://www.aka.ms/mcaslicensing)

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos MCAS são habilitados no nível do locatário para todos os usuários dentro do locatário.

Para obter informações sobre como configurar Microsoft Cloud App Security políticas para usuários licenciados, [consulte Microsoft Cloud App Security visão geral](/cloud-app-security/what-is-cloud-app-security).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os administradores podem escopo de implantações MCAS para usuários licenciados usando os recursos de implantação com escopo disponíveis no serviço. Para obter mais informações, consulte [Implantação com escopo](/cloud-app-security/scoped-deployment).

## <a name="compliance-manager"></a>Gerenciador de Conformidade

Simplifique a conformidade e ajude a reduzir o risco com o Gerenciador de Conformidade. O Gerenciador de Conformidade ajuda as organizações a atender aos requisitos de regulamentos, padrões, políticas da empresa ou outras estruturas de controle desejadas.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

A seguir estão os benefícios para os usuários do serviço Gerenciador de Conformidade:

- Converte regulamentações complicadas, padrões, políticas da empresa ou outras estruturas de controle desejadas em linguagem simples
- Fornece acesso a uma grande biblioteca de avaliações e avaliações personalizadas exclusivas para atender às necessidades exclusivas de conformidade
- Mapas regulamentação para ações recomendadas de melhoria
- Fornece orientações passo a passo sobre como implementar as soluções para atender aos requisitos regulatórios
- Ajuda os usuários a priorizar ações que terão o maior impacto em sua conformidade organizacional associando uma pontuação a cada ação

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Os clientes com licenças E1 e E3/G3 poderão acessar apenas a avaliação padrão da Linha de Base de Proteção de Dados. Os clientes com licenças do Office 365 E5/A5 e Microsoft 365 E5/A5 (Conformidade, Governança de Proteção de Informações & e SKUs de Descoberta Eletrônica e Auditoria incluídas) poderão acessar avaliações in-loco da Linha de Base de Proteção de Dados, RGPD, NIST 800-53 e ISO 27001. Os clientes com o Office 365 G5 e o Microsoft 365 G5 poderão acessar os níveis de Linha de Base de Proteção de Dados, RGPD, NIST 800-53, ISO 27001 e Certificação do Modelo de Maturidade da Segurança Cibernética (CMMC) níveis 1 a 5 avaliações in-loco. O recurso de avaliação personalizado e avaliações premium são reservados para clientes do Office 365 E5/A5/G5 e Microsoft 365 E5/A5/G5. Premium avaliações, como FedRAMP Moderate, FedRAMP High e outras, estarão disponíveis para compra para clientes com licenças E5/A5/G5 durante o primeiro semestre de 2021 por meio de VL, CSP e WebDirect. Entre em contato com o vendedor da Microsoft ou o Microsoft Partner para comprar por meio de canais VL ou CSP, respectivamente. Para comprar por meio do WebDirect, consulte [WebDirect](https://aka.ms/ComplianceManager/WebDirect).

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

O Gerenciador de Conformidade é provisionado por padrão para seu locatário. Os administradores configuram permissões de usuário e atribuem funções para que usuários não administradores em sua organização possam começar a usar o Gerenciador de Conformidade. Para obter mais informações, [consulte Get started with Compliance Manager: Set user permissions and assign roles](/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles).

## <a name="microsoft-defender-for-endpoint"></a>Microsoft Defender para Ponto de Extremidade

O Microsoft Defender for Endpoint (anteriormente Microsoft Defender ATP) é uma solução de segurança de ponto de extremidade que inclui Gerenciamento de Vulnerabilidades e avaliação baseadas em riscos; recursos de redução de superfície de ataque; proteção de próxima geração baseada em comportamento e com energia na nuvem; detecção e resposta de ponto de extremidade (EDR); investigação automática e correção; e serviços de busca gerenciados. Consulte [a página do Microsoft Defender para Ponto de](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) Extremidade para saber mais.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Os usuários licenciados do Windows 10 Enterprise E5, Windows 10 Education A5, Microsoft 365 E5/G5, que inclui o Windows 10 Enterprise E5, Microsoft 365 E5/A5/G5 Security, podem se beneficiar do Microsoft Defender para Ponto de Extremidade.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os analistas secOps e profissionais de segurança se beneficiam dos recursos de segurança do ponto de extremidade do Microsoft Defender para o Ponto de Extremidade para fazer proteção preventiva, detecção pós-violação, investigação automatizada e resposta a ameaças avançadas. Os usuários finais se beneficiam por ter eventos mal-intencionados monitorados pelo Microsoft Defender para Ponto de Extremidade.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos do Microsoft Defender para Ponto de Extremidade são habilitados no nível do locatário para todos os usuários dentro do locatário. Para obter informações sobre a implantação, consulte [Fases de implantação.](/windows/security/threat-protection/microsoft-defender-atp/deployment-phases)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os administradores do Microsoft Defender for Endpoint podem usar o controle de acesso baseado em função (RBAC) para criar funções e grupos dentro da equipe de operações de segurança para conceder acesso apropriado ao Central de Segurança do Microsoft Defender. Para obter mais informações, consulte [Manage portal access using role-based access control](/windows/security/threat-protection/microsoft-defender-atp/rbac).

## <a name="microsoft-365-data-classification-analytics-overview-content-amp-activity-explorer"></a>Microsoft 365 análise de classificação de dados: Visão geral do Explorador de &amp; Atividades de Conteúdo

Os recursos de análise de classificação de dados estão disponíveis Microsoft 365 experiência do centro de conformidade. Visão geral mostra os locais do conteúdo digital e os rótulos e tipos de informações confidenciais mais comuns presentes. O Explorador de Conteúdo fornece visibilidade da quantidade e tipos de dados confidenciais e permite que os usuários filtrem por rótulo ou tipo de sensibilidade para obter uma visão detalhada dos locais onde os dados confidenciais são armazenados. O Explorador de Atividades mostra atividades relacionadas a dados confidenciais e rótulos, como downgrades de rótulos ou compartilhamento externo que podem expor seu conteúdo a riscos.

O Explorador de Atividades fornece um único painel de vidro para os administradores obterem visibilidade sobre atividades relacionadas a informações confidenciais que estão sendo usadas pelos usuários finais. Esses dados incluem atividades de rótulo, logs de prevenção contra perda de dados (DLP), rotulagem automática, DLP de ponto de extremidade e muito mais.

O Explorador de Conteúdo oferece aos administradores a capacidade de indexar os documentos confidenciais armazenados em cargas de trabalho Microsoft 365 com suporte e identificar as informações confidenciais que eles estão armazenando. Além disso, o Explorador de Conteúdo ajuda a identificar documentos que são classificados com rótulos de confidencialidade e retenção.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os administradores de proteção e conformidade de informações podem acessar o serviço para obter acesso a esses logs e dados indexados para entender onde os dados confidenciais são armazenados e quais atividades estão relacionadas a esses dados e executadas pelos usuários finais.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Os usuários licenciados do Microsoft 365 E5/A5/G5, conformidade Microsoft 365 E5/A5/G5, governança de proteção de informações do Microsoft 365 E5/A5/G5 e o Office 365 E5 podem se beneficiar da análise de classificação de dados &amp; Microsoft 365. 

Microsoft 365 E3/A3/G3 e Office 365 E3/A3/G3 permitem que os usuários se beneficiem apenas da agregação de dados do Explorador de Conteúdo.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos do Overview Content and Activity Explorer são habilitados no nível do locatário para todos os usuários dentro do locatário. Para obter informações sobre como configurar a análise de classificação de dados para usuários licenciados, consulte:

- **Explorador de** Conteúdo : [Começar com o explorador de conteúdo - Microsoft 365 Conformidade | Microsoft Docs](/microsoft-365/compliance/data-classification-content-explorer).
- **Explorador de** Atividades : Começar com o explorador de atividades [- Microsoft 365 Conformidade | Microsoft Docs](/microsoft-365/compliance/data-classification-activity-explorer).
- **Notas de versão de classificação de dados**: Notas de versão de classificação de dados - Microsoft 365 conformidade [| Microsoft Docs](/microsoft-365/compliance/data-classification-pub-preview-relnotes).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Esse recurso precisa ser escopo para usuários que usam a solução ativamente dentro Microsoft 365 Portal de Conformidade.

## <a name="information-protection"></a>Proteção de Informações

A Proteção de Informações ajuda as organizações a descobrir, classificar, rotular e proteger documentos e emails confidenciais. Os administradores podem definir regras e condições para aplicar rótulos automaticamente, os usuários podem aplicar rótulos manualmente ou uma combinação dos dois pode ser usada, onde os usuários receberão recomendações sobre a aplicação de rótulos.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam por terem a capacidade de aplicar manualmente rótulos de confidencialidade ao conteúdo ou por terem seu conteúdo automaticamente classificado.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, Office 365 E5/A5/E3/A3/F3, Plano AIP 1 e Plano AIP 2 fornecem os direitos para um usuário se beneficiar da rotulagem de sensibilidade manual.

O Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, Plano 1 da AIP e Plano 2 da AIP fornecem os direitos para um usuário se beneficiar da aplicação e exibição de rótulos de sensibilidade no Power BI e para proteger dados quando eles são exportados do Power BI para Excel, PowerPoint ou PDF. 

> [!NOTE]
> Power BI está incluído no Microsoft 365 E5/A5/G5; em todos os outros planos, Power BI deve ser licenciado separadamente.

Microsoft 365 E5/A5/G5, conformidade Microsoft 365 E5/A5/G5, proteção de informações do Microsoft 365 E5/A5/G5 e Governança, Office 365 E5, Enterprise Mobility + Security E5/A5/G5 e Plano 2 da AIP fornecem os direitos para um usuário se beneficiar da rotulagem automática de sensibilidade.

Para direitos específicos por licença, consulte a comparação de licenciamento de conformidade Microsoft 365 conformidade detalhada. [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx) Não inclui direitos de classificação automática com base em Machine Learning (classificadores treináveis).

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos de proteção de informações são habilitados no nível do locatário para todos os usuários dentro do locatário. Para obter informações sobre como configurar políticas para usuários licenciados, consulte Ativando o Gerenciamento de Direitos do Azure.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Exceto ao usar o recurso de scanner AIP, as políticas podem ser escopo para grupos específicos ou usuários e registros podem ser editadas para impedir que usuários não licenças executam recursos de classificação ou rotulagem. Para obter instruções sobre como escopo de implantações AIP, consulte [Configuring the Azure Information Protection policy](/azure/information-protection/configure-policy).

Para o recurso de scanner AIP, a Microsoft não se compromete a fornecer recursos de classificação, rotulagem ou proteção de arquivos para usuários que não estão licenciados.

## <a name="information-governance"></a>Governança de Informações

A Governança de Informações ajuda as organizações a gerenciar seus riscos por meio da descoberta, classificação, rotulagem e controle de seus dados. A Governança de Informações permite que as organizações atendem aos requisitos comerciais e regulatórios, bem como reduzem sua superfície de ataque, fornecendo recursos de retenção e exclusão em seus Microsoft 365 e dados de terceiros.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam por serem capazes de classificar dados para fins de retenção para manter políticas e regulamentos específicos.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Microsoft 365 F3/Business Premium, Office 365 E1/A1/F3 e planos de Exchange autônomos fornecem os direitos para que um usuário se beneficie da aplicação manual de rótulos de retenção não registrado aos dados da caixa de correio.

os planos Microsoft 365 F3/F1/Business Premium, Office 365 E1/A1/F3 e SharePoint autônomos fornecem os direitos para que um usuário se beneficie da aplicação manual de rótulos de retenção não registrado a arquivos no SharePoint ou OneDrive. 

Microsoft 365 E5/A5/G5/E3/A3/Business Premium, Office 365 E5/A5/G5/E3/A3, Exchange Plano 2 e Arquivamento do Exchange Online fornecem os direitos para que um usuário se beneficie de uma política básica de retenção de caixa de correio em toda a organização ou local e/ou para aplicar manualmente uma rotulagem de retenção não-registro aos dados da caixa de correio.

Microsoft 365 E5/A5/G5/E3/A3, Office 365 E5/A5/G5/E3/A3 e SharePoint Plano 2 fornecem os direitos para um usuário se beneficiar de uma política de retenção básica SharePoint ou OneDrive e/ou aplicar manualmente um rótulo de retenção não registrado a arquivos no SharePoint ou OneDrive.

Microsoft 365 E5/A5/G5/E3/A3 e Office 365 E5/A5/G5/E3/A3 fornecem os direitos para um usuário se beneficiar de uma política de retenção Teams.

Microsoft 365 E5/A5/G5, conformidade Microsoft 365 E5/A5/G5, Microsoft 365 Proteção de Informações e Governança E5/A5/G5, e o Office 365 E5/A5 fornecem os direitos para que um usuário se beneficie da aplicação automática de rótulos ou políticas de retenção, da aplicação de rótulos ou políticas de retenção padrão, iniciando o período de retenção de um rótulo de retenção com base em um evento personalizado, disparando uma revisão de disposição manual no final do período de retenção do rótulo, importando dados de terceiros por meio de conectores de dados nativos, declarando um arquivo um registro, descobrindo o conteúdo rotulado e monitorando a atividade de rotulagem.

Microsoft 365 E5/A5/G5, conformidade Microsoft 365 E5/A5/G5, proteção de informações do Microsoft 365 E5/A5/G5 e Governança fornecem os direitos para que um usuário se beneficie da aplicação automática de rótulos de retenção com base em classificadores treináveis.

Para direitos específicos por licença, consulte a comparação de licenciamento de conformidade Microsoft 365 conformidade detalhada. [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos de Governança de Informações são habilitados no nível do locatário para todos os usuários dentro do locatário. Para obter informações sobre como configurar a Governança de Informações para aplicar o auto-rótulo e políticas para usuários licenciados, consulte [Microsoft Information Governance in Microsoft 365](/microsoft-365/compliance/manage-information-governance).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os recursos de Governança de Informações podem ser aplicados a usuários licenciados em locais específicos (sites de equipe, sites de grupo, etc.). Para obter informações sobre como configurar a Governança de Informações para aplicar o auto-rótulo e políticas para usuários licenciados, consulte [Microsoft Information Governance in Microsoft 365](/microsoft-365/compliance/manage-information-governance).

## <a name="records-management"></a>Gerenciamento de Registros

O Gerenciamento de Registros ajuda as organizações a cumprir suas obrigações de manutenção de registros comerciais e regulamentais por meio da descoberta, classificação, rotulagem, retenção e exclusão defensíveis em seus Microsoft 365 e dados de terceiros.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 Proteção de Informações e Governança E5/A5/G5 e Office 365 E5/A5/G5 fornecem os direitos para um usuário se beneficiar do Gerenciamento de Registros, incluindo declarar itens como registros ou registros regulamentares, aplicar automaticamente rótulos de retenção ou registro e executar processos de revisão de disposição (excluindo automaticamente a aplicação de um rótulo de retenção com base em classificadores treineis).

Microsoft 365 E5/A5/G5, conformidade Microsoft 365 E5/A5/G5 e Microsoft 365 Proteção de Informações e Governança fornecem os direitos para que um usuário se beneficie da aplicação automática de rótulos de retenção ou registro com base em classificadores com treinamento.

Para direitos específicos por licença, consulte a comparação de licenciamento de conformidade Microsoft 365 conformidade detalhada. [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam ao poder declarar o conteúdo como um registro e gerenciar o processo de registros completos a partir da definição e declaração de política por meio do descarte defensible.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos de Gerenciamento de Registros são habilitados no nível do locatário para todos os usuários dentro do locatário. Para obter informações sobre como configurar o Gerenciamento de Registros a ser aplicado a usuários licenciados, consulte Saiba mais sobre gerenciamento de [registros em Microsoft 365](/microsoft-365/compliance/records-management).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os recursos de Gerenciamento de Registros podem ser aplicados a usuários licenciados em locais específicos (sites de equipe, sites de grupo, etc.). Para obter informações sobre como configurar o Gerenciamento de Registros a ser aplicado a usuários licenciados, consulte Saiba mais sobre gerenciamento de [registros em Microsoft 365](/microsoft-365/compliance/records-management).

## <a name="data-connectors"></a>Conectores de Dados 

A Microsoft fornece conectores de dados de terceiros que podem ser configurados no Microsoft 365 de conformidade. Para ver uma lista de conectores de dados fornecidos pela Microsoft, consulte a tabela Conectores de dados [de terceiros.](/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) Esta tabela também resume as soluções de conformidade que você pode aplicar a dados de terceiros depois de importar e arquivar dados em Microsoft 365 e links para as instruções passo a passo para cada conector.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

O principal benefício do uso de conectores de dados para importar e arquivar dados de terceiros no Microsoft 365 é que você pode aplicar várias soluções de conformidade Microsoft 365 aos dados depois que eles são importados. Isso ajuda a garantir que os dados que não são da Microsoft da sua organização estão em conformidade com os regulamentos e padrões que afetam sua organização.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

As licenças a seguir fornecem os direitos para que um usuário se beneficie dos Conectores de Dados:

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 Info Protection &amp; Governance
- Microsoft 365 E5/A5/G5 Conformidade
- Microsoft 365 E5/A5/G5 Insider Risk Management
- Microsoft 365 E5/A5/G5 e Auditoria
- Office 365 E5/A5/G5

Para conectores de dados no Centro de Conformidade Microsoft 365 Segurança fornecidos por um parceiro da Microsoft, sua organização precisará de uma relação de negócios com o parceiro antes de poder implantar &amp; esses conectores.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Os conectores são configurados usando o Centro &amp; de Conformidade de Segurança e o Catálogo de Conectores.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os serviços de Conectores de Dados são um valor no nível do locatário. Todos os usuários destinados a se beneficiar desse serviço devem ser licenciados.

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp"></a>APIs Graph Microsoft para Teams prevenção contra perda de dados (DLP)

No início deste ano, [anunciamos a visualização](https://go.microsoft.com/fwlink/?linkid=2143888)pública da API de Notificação de Alterações do Microsoft Graph para mensagens em Teams . Essa API permite que os desenvolvedores criem aplicativos que podem ouvir Microsoft Teams mensagens em tempo quase real e habilitar implementações de cenário de DLP para clientes e ISVs. Além disso, a API Graph Patch da Microsoft permite aplicar ações DLP a Teams mensagens.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os recursos de prevenção contra perda de dados [(DLP)](/microsoft-365/compliance/dlp-microsoft-teams) são amplamente usados no Microsoft Teams, especialmente quando as organizações mudaram para o trabalho remoto. Se sua organização tiver DLP, agora você pode definir políticas que impedem que as pessoas compartilhem informações confidenciais em um Microsoft Teams canal ou sessão de chat.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Você precisará de uma das seguintes licenças para obter suporte para a proteção DLP em Teams Chat:

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 Conformidade
- Microsoft 365 E5/A5/G5 Proteção e Governança de Informações
- Office 365 E5/A5/G5 

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

O acesso à API é configurado no nível do locatário.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

A API Graph microsoft para Teams DLP é um valor de nível de locatário. Todos os usuários destinados a se beneficiar desse serviço devem ser licenciados.

## <a name="ediscovery"></a>Descoberta eletrônica

A Descoberta eDiscovery fornece soluções de investigação e descoberta de eDiscovery para departamentos de TI e jurídicos dentro das corporações para identificar, coletar, preservar, reduzir e revisar conteúdo relacionado a uma investigação ou litígio antes de exportar para fora do sistema Microsoft 365.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Um usuário se beneficia Advanced eDiscovery quando o usuário é selecionado como um custodiante de dados (uma pessoa que tem controle administrativo de um documento ou arquivo eletrônico) para uma ocorrência.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Microsoft 365 E5/A5/G5/E3/A3/G3, Office 365 E5/A5/G5/E3/A3/G3 fornecem os direitos para um usuário se beneficiar da Descoberta Interna.

Microsoft 365 E5/A5/G5, conformidade Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 e Auditoria e Office 365 E5/A5/G5 fornecem os direitos para um usuário se beneficiar do Advanced eDiscovery.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, Advanced eDiscovery recursos são habilitados no nível de locatário para todos os usuários dentro do locatário quando os administradores atribuem permissões de Descoberta eDiscovery no Centro &amp; de Conformidade e Segurança.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os administradores de Descoberta Digital podem selecionar usuários específicos como custodiantes de dados para um caso usando a ferramenta de gerenciamento de custodia interna no Advanced eDiscovery conforme descrito em [Adicionar custodiantes a](/microsoft-365/compliance/add-custodians-to-case)um caso Advanced eDiscovery .

## <a name="customer-key-for-microsoft-365"></a>Chave do cliente para Microsoft 365

Com a Chave do Cliente, você controla as chaves de criptografia da sua organização e configura Microsoft 365 usá-las para criptografar seus dados em repouso nos data centers da Microsoft. Em outras palavras, a Chave do Cliente permite adicionar uma camada de criptografia que pertence a você, usando suas próprias chaves. Os dados em repouso incluem dados de Exchange Online e Skype for Business que são armazenados em caixas de correio e arquivos no SharePoint Online e OneDrive for Business.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam da Chave do Cliente, tendo seus dados em repouso criptografados na camada do aplicativo usando chaves de criptografia fornecidas, controladas e gerenciadas por sua própria organização.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Microsoft 365 E5/A5/G5, conformidade Microsoft 365 E5/A5/G5, proteção e governança de informações do Microsoft 365 E5/A5/G5 e o Office 365 E5/A5/G5 fornecem os direitos para um usuário se beneficiar da Chave do Cliente. Para obter o benefício completo da Chave do Cliente, você também deve ter uma assinatura do Azure Key Vault.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

A Chave do Cliente para Microsoft 365 chaves de criptografia pode ser habilitada para todos os dados armazenados em caixas de correio Exchange Online e Skype for Business e SharePoint Online, OneDrive for Business e Teams arquivos. Para obter mais informações sobre a Chave do Cliente, incluindo como começar, consulte [Criptografia de serviço com Chave do Cliente](/microsoft-365/compliance/customer-key-overview).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Para Exchange Online e Skype for Business, as caixas de correio podem ser criptografadas usando a Chave do Cliente. Você deve configurar o Azure antes de poder usar a Chave do Cliente para Microsoft 365. Consulte [Set up Customer Key](/microsoft-365/compliance/customer-key-set-up) for the steps you need to follow to create and configure the required Azure resources and the steps for setting up Customer Key in Microsoft 365. Depois de concluir a configuração do Azure, determine qual política e, portanto, quais chaves atribuir a caixas de correio e arquivos em sua organização. Para obter mais informações sobre a Chave do Cliente e o conteúdo sobre dados do Exchange Online, Skype for Business, SharePoint Online, OneDrive for Business e Teams, consulte [Criptografia](/microsoft-365/compliance/customer-key-overview)de serviço com Chave do Cliente.

## <a name="office-365-customer-lockbox"></a>Sistema de Proteção de Dados do Cliente do Office 365

O Customer Lockbox fornece uma camada adicional de controle, oferecendo aos clientes a capacidade de dar autorização de acesso explícito para operações de serviço. Ao demonstrar que existem procedimentos para autorização explícita de acesso a dados, o Customer Lockbox também pode ajudar as organizações a cumprir determinadas obrigações de conformidade, como HIPAA e FedRAMP.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

O Customer Lockbox garante que ninguém na Microsoft possa acessar o conteúdo do cliente para executar uma operação de serviço sem a aprovação explícita do cliente. O Customer Lockbox traz o cliente para o fluxo de trabalho de aprovação para solicitações para acessar seu conteúdo. Ocasionalmente, os engenheiros da Microsoft estão envolvidos durante o processo de suporte para solucionar problemas e corrigir problemas relatados pelo cliente. Na maioria dos casos, os problemas são corrigidos por meio de ferramentas extensivas de telemetria e depuração que a Microsoft tem em seus serviços. No entanto, pode haver casos que exigem que um engenheiro da Microsoft acesse o conteúdo do cliente para determinar a causa raiz e corrigir o problema. O Sistema de Proteção de Dados do Cliente exige que o engenheiro solicite acesso do cliente como uma etapa final no fluxo de trabalho de aprovação. Isso oferece às organizações a opção de aprovar ou negar essas solicitações, o que lhes dá controle direto sobre se um engenheiro da Microsoft pode acessar os dados do usuário final das organizações.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Office 365 O E5/A5/G5, Microsoft 365 E5/A5/G5, conformidade Microsoft 365 E5/A5/G5 e o Gerenciamento de Riscos do Insider do Microsoft 365 E5/A5/G5 fornecem os direitos para um usuário se beneficiar do Customer Lockbox.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Os administradores podem ativar o Customer Lockbox no Microsoft 365 de administração. Para obter mais informações, consulte [Customer Lockbox in Office 365](/microsoft-365/compliance/customer-lockbox-requests). Quando o Customer Lockbox está ligado, a Microsoft é obrigada a obter a aprovação de uma organização antes de acessar qualquer um de seus conteúdos.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Atualmente, o serviço de Caixa de Bloqueio do Cliente não pode ser limitado a usuários específicos. Você deve licenciar todos os usuários que pretende beneficiar.

## <a name="privileged-access-management-in-office-365"></a>O Privileged Access Management no Office 365

[O GERENCIAMENTO de acesso privilegiado (PAM)](/microsoft-365/compliance/privileged-access-management-configuration) fornece controle de acesso granular sobre tarefas de administrador privilegiados Office 365. Depois de habilenciar o PAM, para concluir tarefas elevadas e privilegiadas, os usuários precisarão solicitar acesso just-in-time por meio de um fluxo de trabalho de aprovação com escopo alto e limite de tempo.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Habilenciar o PAM permite que as organizações operem sem privilégios de posição zero. Os usuários se beneficiam da camada de defesa adicionada contra vulnerabilidades resultantes do acesso administrativo permanente que fornece acesso não proporcionado aos seus dados.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço? 

Office 365 E5/A5, Microsoft 365 E5/A5, conformidade Microsoft 365 E5/A5 e proteção e governança de informações Microsoft 365 E5/A5 fornecem os direitos para um usuário se beneficiar do PAM.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos PAM são habilitados no nível de locatário para todos os usuários dentro do locatário. Para obter informações sobre como configurar políticas pam, consulte [Get started with privileged access management](/microsoft-365/compliance/privileged-access-management-configuration).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os clientes podem gerenciar o PAM por usuário por meio de políticas de acesso e grupo de aprovadores, que podem ser aplicadas a usuários licenciados. Para obter mais informações, consulte [Privileged access management in Office 365](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751).

## <a name="double-key-encryption-for-microsoft-365"></a>Criptografia de Chave Dupla para Microsoft 365 

A Criptografia de Chave Dupla Microsoft 365 permite proteger seus dados altamente confidenciais para atender aos requisitos especializados e manter o controle total da chave de criptografia. A Criptografia de Chave Dupla usa duas chaves para proteger seus dados, com uma chave em seu controle e a segunda chave armazenada com segurança por Microsoft Azure. Para exibir os dados, você deve ter acesso às duas chaves. Como a Microsoft pode acessar apenas uma chave, sua chave e também seus dados não estão disponíveis para a Microsoft, garantindo que você tenha controle total sobre a privacidade e a segurança de seus dados.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam da Criptografia de Chave Dupla por serem capazes de migrar seus dados criptografados para a nuvem, o que impede o acesso de terceiros desde que a chave permaneça no controle dos usuários. Os usuários podem proteger e consumir conteúdo criptografado de Chave Dupla semelhante a qualquer outro conteúdo protegido por rótulo de sensibilidade.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Microsoft 365 E5/A5/G5, conformidade Microsoft 365 E5/A5/G5, Proteção e Governança de Informações do Microsoft 365 E5/A5/G5 e o Office 365 E5/A5/G5 fornecem os direitos para um usuário se beneficiar da Criptografia de Chave Dupla.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

A Criptografia de Chave Dupla dá suporte à versão da área de trabalho Microsoft Office para Windows.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Para atribuir chaves de criptografia aos dados em uma organização Office 365 e/ou Microsoft 365 para usuários licenciados, siga as instruções de implantação de Criptografia de Chave Dupla.

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Office 365 prevenção contra perda de dados para Exchange Online, SharePoint Online e OneDrive for Business

Com Office 365 prevenção contra perda de dados (DLP) para Exchange Online, SharePoint Online e OneDrive for Business, as organizações podem identificar, monitorar e proteger automaticamente informações confidenciais em emails e arquivos (incluindo arquivos armazenados em repositórios de arquivo Microsoft Teams).

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam da DLP para Exchange Online, SharePoint Online e OneDrive for Business quando seus emails e arquivos estão sendo inspecionados para obter informações confidenciais, conforme configurado na política de DLP da organização.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Microsoft 365 E3/A3/Business Premium, Office 365 E3/A3 e Office 365 Prevenção contra Perda de Dados fornecem os direitos para que um usuário se beneficie da DLP do Office 365 para Exchange Online, SharePoint Online e OneDrive for Business.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, Exchange Online emails, sites SharePoint e contas OneDrive são locais *habilitados (cargas* de trabalho) para esses recursos de DLP para todos os usuários no locatário. Para obter mais informações sobre como usar políticas DLP, consulte [Overview of data loss prevention](/microsoft-365/compliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os administradores podem personalizar locais (cargas de trabalho), usuários incluídos e usuários excluídos no Centro de Conformidade de Segurança, em Locais de prevenção &amp; **contra perda de**  >  **dados.**

## <a name="communication-data-loss-prevention-for-teams"></a>Prevenção contra perda de dados de comunicação para Teams

Com a DLP de comunicação para Teams, as organizações podem bloquear chats e mensagens de canal que contenham informações confidenciais, como informações financeiras, informações de identificação pessoal, informações relacionadas à saúde ou outras informações confidenciais.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Os usuários licenciados do Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5 e Microsoft 365 E5/A5/G5 Information Protection and Governance podem se beneficiar da DLP de comunicação para Teams.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os envios se beneficiam por ter informações confidenciais em seus chats de saída e mensagens de canal inspecionadas para obter informações confidenciais, conforme configurado na política de DLP da organização.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, Teams mensagens de chat e canal são um *Local habilitado (carga* de trabalho) para esses recursos DLP para todos os usuários dentro do locatário. Para obter mais informações sobre como usar políticas DLP, consulte [Overview of data loss prevention](/office365/securitycompliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os administradores podem personalizar locais (cargas de trabalho), usuários incluídos e usuários excluídos no Centro de Conformidade de Segurança, em Locais de prevenção &amp; **contra perda de**  >  **dados.**

## <a name="information-barriers"></a>Barreiras de informações

Os obstáculos de informação são políticas que um administrador pode configurar para impedir que indivíduos ou grupos se comunique entre si. Isso será útil se, por exemplo, um departamento estiver manipulando informações que não devem ser compartilhadas com outros departamentos ou um grupo precisar ser impedido de se comunicar com contatos externos. As políticas de barreira de informações também impedem pesquisa e descoberta. Isso significa que, se você tentar se comunicar com alguém com quem não deve se comunicar, não encontrará esse usuário no selador de pessoas.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam dos recursos avançados de conformidade das barreiras de informações quando estão impedidos de se comunicar com outras pessoas. As políticas de barreiras de informações podem ser definidas para impedir que determinado segmentos de usuários se comuniquem com cada um ou permitir que segmentos específicos se comuniquem apenas com determinados outros segmentos. Para obter mais informações sobre como definir políticas de barreira de informações, consulte [Definir políticas de barreira de informações](/microsoft-365/compliance/information-barriers-policies). Para cenários em que dois grupos não podem se comunicar uns com os outros, os usuários em ambos os grupos exigem uma licença para se beneficiar do serviço (consulte o exemplo abaixo).<br><br>

| Cenário | Who requer uma licença? |
|:------|:------|
| Dois grupos (Grupo 1 e Grupo 2) não podem se comunicar uns com os outros (ou seja, os usuários do Grupo 1 são impedidos de se comunicar com usuários do Grupo 2 e os usuários do Grupo 2 são impedidos de se comunicar com usuários do &nbsp; &nbsp; Grupo &nbsp; &nbsp; &nbsp; &nbsp; 1. | Usuários do Grupo &nbsp; 1 e do Grupo &nbsp; 2 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Microsoft 365 E5/A5/G5, conformidade com Microsoft 365 E5/A5/G5, gerenciamento de riscos do Microsoft 365 E5/A5/G5 Insider e Office 365 E5/A5/G5, fornecem os direitos para que um usuário se beneficie das barreiras de informações.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Os administradores criam e gerenciam políticas de barreira de informações usando cmdlets do PowerShell no Centro &amp; de Conformidade e Segurança. Os administradores devem ser atribuídos Microsoft 365 Enterprise administrador global, Office 365 administrador global ou administrador de conformidade para criar uma política de barreira de informações. Por padrão, essas políticas se aplicam a todos os usuários no locatário. Para obter mais informações sobre barreiras de informações, consulte [Barreiras de informações em Microsoft Teams](/MicrosoftTeams/information-barriers-in-teams).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os administradores podem personalizar locais (cargas de trabalho), usuários incluídos e usuários excluídos no Centro &amp; de Conformidade de Segurança. Por exemplo, se todos os usuários são licenciados para o Office 365 E3 e nenhum é licenciado para o Conformidade Avançada do Office 365/E5, eles não precisariam criar nenhuma política de barreira de informações para a organização. Para obter mais informações, consulte [Barreiras de informações no Microsoft Teams](/MicrosoftTeams/information-barriers-in-teams).

## <a name="office-365-message-encryption"></a>Criptografia de Mensagem do Office 365

Criptografia de Mensagens do Office 365 (OME) é um serviço integrado ao Azure Rights Management (Azure RMS) que permite o envio de emails criptografados para pessoas dentro ou fora da sua organização, independente do endereço de email de destino (Gmail, Yahoo! Email, Outlook.com, etc.).

Para exibir mensagens criptografadas, os destinatários podem obter uma senha avulsa, entrar com uma conta da Microsoft ou com uma conta corporativa ou de estudante associada ao Office 365. Os destinatários também podem enviar respostas criptografadas. Eles não precisam de uma assinatura para exibir mensagens criptografadas ou enviar respostas criptografadas.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os envios de mensagens se beneficiam do controle adicionado sobre emails confidenciais fornecidos pelo Criptografia de Mensagens do Office 365.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Microsoft 365 E3/A3/G3, Office 365 E3/A3/G3 e o Plano 1 de Proteção de Informações do Azure fornecem os direitos para um usuário se beneficiar do Criptografia de Mensagens do Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Os administradores criam e gerenciam Criptografia de Mensagens do Office 365 políticas no centro de administração Exchange em **Regras de fluxo de**  >  **email.** Por padrão, essas regras se aplicam a todos os usuários no locatário. Para obter mais informações sobre como configurar novos recursos Criptografia de Mensagens do Office 365, consulte [Configurar novos recursos de Criptografia de Mensagem.](/office365/securitycompliance/set-up-new-message-encryption-capabilities)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os administradores devem aplicar regras de fluxo de emails Criptografia de Mensagens do Office 365 somente a usuários licenciados. Para obter mais informações sobre como definir regras de fluxo de emails, consulte [Define mail flow rules to encrypt email messages](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="office-365-advanced-message-encryption"></a>Criptografia de Mensagem Avançada do Office 365

Criptografia de Mensagem Avançada do Office 365 ajuda os clientes a cumprir obrigações de conformidade que exigem controles mais flexíveis sobre destinatários externos e seu acesso a emails criptografados. Com a Criptografia Avançada de Mensagens, os administradores podem controlar emails confidenciais compartilhados fora da organização usando políticas automáticas que podem detectar tipos de informações confidenciais (por exemplo, identificando pessoalmente informações ou IDs financeiras ou de saúde) ou podem usar palavras-chave para aprimorar a proteção aplicando modelos de email personalizados e expirando o acesso a emails criptografados por meio de um portal web seguro. Além disso, os administradores podem controlar ainda mais os emails criptografados acessados externamente por meio de um portal da Web seguro revogando o acesso a qualquer momento.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os envios de mensagens se beneficiam do controle adicionado sobre emails confidenciais fornecidos pela Criptografia Avançada de Mensagens.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, conformidade com Microsoft 365 E5/A5/G5 e Microsoft 365 E5/A5/G5 Information Protection and Governance fornecem os direitos para um usuário se beneficiar da Criptografia Avançada de Mensagens.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Os administradores criam e gerenciam políticas avançadas de Criptografia de Mensagens no Exchange de administração em **Regras de fluxo de**  >  **email.** Por padrão, essas regras se aplicam a todos os usuários no locatário. Para obter mais informações sobre como configurar novos recursos de Criptografia de Mensagens, consulte [Configurar novos recursos Criptografia de Mensagens do Office 365 mensagens.](/office365/securitycompliance/set-up-new-message-encryption-capabilities)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os administradores devem aplicar regras de fluxo de emails para Criptografia Avançada de Mensagens somente para usuários licenciados. Para obter mais informações sobre como definir regras de fluxo de emails, consulte [Define mail flow rules to encrypt email messages in Office 365](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="communication-compliance"></a>Conformidade em comunicações

A conformidade de comunicação Microsoft 365 ajuda a minimizar os riscos de comunicação, ajudando você a detectar, capturar e realizar ações de correção para mensagens inadequadas em sua organização. Você pode definir políticas específicas que capturam emails internos e externos, Microsoft Teams ou comunicações de terceiros em sua organização. Os revisadores podem tomar as ações de correção apropriadas para garantir que eles estão em conformidade com os padrões de mensagens da sua organização.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os especialistas em conformidade se beneficiam do serviço, tendo as comunicações da organização monitoradas pelas políticas de conformidade de comunicação.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, conformidade com Microsoft 365 E5/A5/G5 e Microsoft 365 E5/A5/G5 Insider Risk Management fornecem os direitos para que um usuário se beneficie da conformidade de comunicação.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Os administradores e especialistas em conformidade criam políticas de conformidade de comunicação no Microsoft 365 de conformidade. Essas políticas definem quais comunicações e usuários estão sujeitos a revisão na organização, definem condições personalizadas que as comunicações devem atender e especificam quem deve executar avaliações.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os administradores escolhem usuários ou grupos específicos para incluir em uma política de conformidade de comunicação. Ao escolher um grupo, eles também podem selecionar usuários específicos no grupo para excluir da política de conformidade de comunicação. Para obter mais informações sobre políticas de conformidade de comunicação, consulte [Get started with communication compliance in Microsoft 365](/microsoft-365/compliance/communication-compliance-configure).

## <a name="insider-risk-management"></a>Gerenciamento de riscos internos

O gerenciamento de riscos internos é uma solução Microsoft 365 ajuda a minimizar riscos internos, deixando você detectar, investigar e tomar medidas sobre atividades arriscadas em sua organização.

As políticas personalizadas permitem que você detecte e tome medidas em atividades mal-intencionadas e inadvertidamente arriscadas em sua organização, incluindo a escalada de casos para o Microsoft Advanced eDiscovery, se necessário. Os analistas de risco em sua organização podem tomar rapidamente as ações apropriadas para garantir que os usuários sejam compatíveis com os padrões de conformidade da sua organização.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam por terem suas atividades monitoradas em busca de risco.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Microsoft 365 E5/A5/G5, conformidade Microsoft 365 E5/A5/G5 e o gerenciamento de riscos do Microsoft 365 E5/A5/G5 Insider fornecem os direitos para que um usuário se beneficie do Insider Risk Management.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

As políticas de Gerenciamento de Riscos do Insider devem ser criadas no centro de conformidade Microsoft 365 e atribuídas aos usuários.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Ao criar uma política no centro de conformidade do Microsoft 365,  na página Escolher usuários e grupos, selecione Escolher usuários ou grupos para  selecionar apenas usuários licenciados ou, se todos os seus usuários estão licenciados, você pode selecionar a caixa de seleção Todos os usuários e grupos habilitados para email.  Para obter mais informações, [consulte Get started with insider risk management](/microsoft-365/compliance/insider-risk-management-configure).

## <a name="conditional-access-policies"></a>Políticas de Acesso Condicional

O acesso condicional é a ferramenta usada pelo Azure Active Directory para reunir sinais, tomar decisões e impor políticas organizacionais. O Acesso Condicional está no centro do controle controlado por identidade. Políticas de Acesso Condicional, em suas instruções mais simples, são instruções if-then. Se um usuário quiser acessar um recurso, ele deverá concluir uma ação. Exemplo: um gerente de folha de pagamento deseja acessar o aplicativo de folha de pagamento e é necessário executar a autenticação multifafação para acessá-lo.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Os usuários licenciados do Enterprise Mobility + Security E3/A3, Microsoft 365 F3/E3/A3/Business Premium e Azure Active Directory Premium Plano 1 podem se beneficiar das políticas de Acesso Condicional. Os usuários licenciados do Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft E5/G5 Security e Azure Active Directory Premium Plan 2 podem se beneficiar da Proteção de Identidade (políticas de Acesso Condicional baseadas em risco).

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os analistas de operações de segurança e profissionais de segurança se beneficiam com a capacidade de impor políticas organizacionais aos usuários, exigindo que eles atendem a determinados critérios antes de conceder acesso ao conteúdo corporativo. Os usuários finais se beneficiam ao poder acessar seu trabalho onde e quando escolherem, enquanto protegem os ativos da organização.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos de Acesso Condicional são habilitados no nível do locatário para todos os usuários dentro do locatário.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Para Proteção de Identidade e Acesso Condicional especificamente, um usuário deve ser incluído em um Grupo ou ser adicionado a uma política de Acesso Condicional. A condição de usuários e grupos é obrigatória em uma política de Acesso Condicional. Em sua política, você pode selecionar Todos os **usuários** ou grupos e usuários específicos. Você deve selecionar apenas usuários e grupos licenciados adequadamente. Para obter mais informações, consulte [Acesso Condicional: Condições](/azure/active-directory/conditional-access/conditions).

## <a name="advanced-audit"></a>Auditoria Avançada

A Auditoria Avançada no Microsoft 365 fornece retenção de logs de auditoria de um ano para atividades de usuários e administradores e oferece a capacidade de criar políticas de retenção de log de auditoria personalizadas para gerenciar a retenção de log de auditoria para outros serviços Microsoft 365. Ele também fornece acesso a eventos cruciais para investigações e acesso de alta largura de banda à API Office 365 Atividade de Gerenciamento. Para obter mais informações, consulte [Auditoria Avançada em Microsoft 365](/microsoft-365/compliance/advanced-audit).

Você também pode habilitar um período de retenção de 10 anos com uma SKU de complemento. A SKU de complemento será necessária a partir do início de 2021.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Os usuários licenciados do Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, conformidade Microsoft 365 E5/A5/G5 e Microsoft 365 E5/A5/G5 e Auditoria podem se beneficiar da Auditoria Avançada.

Os usuários licenciados com Auditoria Avançada e o complemento retenção de log de auditoria de 10 anos podem se beneficiar da Retenção de Log de Auditoria de 10 anos.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam da Auditoria Avançada porque os registros de auditoria relacionados à atividade do usuário Microsoft 365 serviços podem ser mantidos por até um ano. Além disso, eventos de auditoria de alto valor são registrados, como quando itens na caixa de correio de um usuário são acessados ou lidos. Para obter mais informações, consulte [Auditoria Avançada em Microsoft 365](/microsoft-365/compliance/advanced-audit).

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, a Auditoria Avançada é habilitada no nível de locatário para todas as organizações que tenham uma assinatura do Office 365 ou Microsoft 365 E5/A5/G5 e fornece automaticamente retenção de um ano de logs de auditoria para atividades (executadas pelos usuários com a licença apropriada) no Azure Active Directory, Exchange e SharePoint. Além disso, as organizações podem usar políticas de retenção de log de auditoria para gerenciar o período de retenção para registros de auditoria gerados pela atividade em outros serviços Microsoft 365 serviços. A funcionalidade de Retenção de Log de Auditoria de 10 anos também está habilitada usando as mesmas políticas de retenção. Para saber mais, confira [Gerenciar políticas de retenção de log de auditoria](/microsoft-365/compliance/audit-log-retention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

A retenção de um ano de logs de auditoria e a auditoria de eventos cruciais só se aplicam aos usuários com a licença apropriada. Além disso, os administradores podem usar políticas de retenção de log de auditoria para especificar durações de retenção mais curtas para os logs de auditoria de usuários específicos.

A retenção de 10 anos de logs de auditoria só se aplica aos usuários com a licença de complemento apropriada. A SKU de complemento será necessária a partir do início de 2021.