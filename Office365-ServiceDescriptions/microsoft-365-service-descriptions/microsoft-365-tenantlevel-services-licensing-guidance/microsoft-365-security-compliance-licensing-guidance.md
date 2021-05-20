---
title: Microsoft 365 orientação de licenciamento para conformidade & de segurança
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
description: Este artigo fornece orientações de licenciamento para Microsoft 365 conformidade para ajudar a evitar possíveis interrupções no serviço devido ao acesso não licenciado.
ms.openlocfilehash: d4ddb9c492cccef13c86e450c64a2eb6efe61eaa
ms.sourcegitcommit: adcacf68ac75c4db2229ebf55be9c75aecd3070b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52546008"
---
# <a name="microsoft-365-licensing-guidance-for-security-amp-compliance"></a>Microsoft 365 orientação de licenciamento para conformidade de segurança &amp;

Para efeitos deste artigo, um serviço de nível de inquilino é um serviço on-line que &mdash; quando comprado para qualquer usuário no inquilino (autônomo ou como parte de Office 365 ou Microsoft 365 planos) é ativado parcial ou &mdash; integralmente para todos os usuários do inquilino. Embora alguns usuários não licenciados possam tecnicamente acessar o serviço, uma licença é necessária para qualquer usuário que você pretenda se beneficiar do serviço.

> [!NOTE]
> Alguns serviços de inquilinos não são atualmente capazes de limitar benefícios a usuários específicos. Devem ser feitos esforços para limitar os benefícios do serviço aos usuários licenciados. Isso ajudará a evitar possíveis interrupções de serviço em sua organização, uma vez que os recursos de segmentação estejam disponíveis.

Para ver as opções de licenciamento de seus usuários para se beneficiar de recursos de conformidade Microsoft 365, baixe o Detalhado Microsoft 365 Comparação de Licenciamento de Conformidade. [(PDF)](https://www.microsoft.com/download/details.aspx?id=103010)  |  [(Excel)](https://www.microsoft.com/download/details.aspx?id=103006)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure Active Directory A Proteção de Identidade é uma característica do plano P2 Azure Active Directory Premium que permite detectar potenciais vulnerabilidades que afetam as identidades de sua organização, configurar respostas automatizadas para detectar ações suspeitas relacionadas às identidades de sua organização e investigar incidentes suspeitos e tomar as medidas apropriadas para resolvê-las.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Analistas e profissionais de segurança da SecOps se beneficiam de ter visões consolidadas de usuários sinalizados e eventos de risco baseados em algoritmos de aprendizado de máquina. Os usuários finais se beneficiam da proteção automática fornecida através do Acesso Condicional baseado em riscos e da segurança melhorada fornecida pela atuação em vulnerabilidades.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security e Azure Active Directory Premium Plan 2 fornecem os direitos para um usuário se beneficiar de Azure Active Directory Proteção de Identidade.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos de proteção de identidade do Azure AD são habilitados no nível de inquilino para todos os usuários dentro do inquilino. Para obter informações sobre proteção de identidade do Azure AD, consulte [O que é proteção de identidade?](/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado apenas aos usuários do inquilino que são licenciados para o serviço?

Os administradores podem escopo da Proteção de Identidade Azure AD, atribuindo políticas de risco que definem o nível para redefinições de senha e permitindo acesso apenas para usuários licenciados. Para obter instruções sobre como escopo de implantações de proteção de identidade do Azure AD, consulte [Como configurar e habilitar políticas de risco](/azure/active-directory/identity-protection/howto-sign-in-risk-policy).

## <a name="azure-active-directory-identity-governance"></a>Azure Active Directory Governança de Identidade

Azure Active Directory A Governança de Identidade permite equilibrar a necessidade de segurança e produtividade dos funcionários da sua organização com os processos e visibilidade certos. Ele usa gerenciamento de direitos, revisões de acesso, gerenciamento privilegiado de identidade e políticas de termos de uso para garantir que as pessoas certas tenham acesso certo aos recursos certos.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Azure Active Directory A Governança de Identidade aumenta a produtividade dos usuários, facilitando o acesso a aplicativos, grupos e Microsoft Teams em um pacote de acesso. Os usuários também podem ser configurados como aprovadores, sem envolver administradores. Para avaliações de acesso, os usuários podem rever associações de grupos com recomendações inteligentes para agir em intervalos regulares.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Enterprise Mobility + Security O Plano 2 de Segurança Microsoft 365 E5 Microsoft 365 E5/A5 e Azure Active Directory Premium E5/A5 fornecem os direitos para que um usuário se beneficie de Azure Active Directory Governança de Identidade.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Os recursos de Governança de Identidade do AZure AD são habilitados no nível do inquilino, mas implementados por usuário. Para obter informações sobre a Governança de Identidade do Azure AD, consulte [o que é a governança de identidade do Azure AD?](/azure/active-directory/governance/identity-governance-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado apenas aos usuários do inquilino que são licenciados para o serviço?

Os administradores podem escopo de Governança de Identidade AZure AD atribuindo pacotes de acesso, revisões de acesso ou gerenciamento de identidade privilegiado apenas para usuários licenciados. Para obter instruções sobre como escopo de implantações de Governança de Identidade Azure AD, consulte:

- [Requisitos de licença de gerenciamento de direitos do Azure AD](/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Requisitos de licença de revisão de acesso a Azure AD](/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [Requisitos de licença para usar Privileged Identity Management](/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="microsoft-defender-for-identity"></a>Microsoft Defender para Identidade?

O Microsoft Defender for Identity (anteriormente Azure Advanced Threat Protection) é um serviço em nuvem que ajuda a proteger ambientes híbridos corporativos contra vários tipos de ataques cibernéticos direcionados avançados e ameaças internas.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Analistas e profissionais de segurança da SecOp se beneficiam da capacidade do Microsoft Defender for Identity de detectar e investigar ameaças avançadas, identidades comprometidas e ações de insider maliciosas. Os usuários finais se beneficiam por ter seus dados monitorados pelo Microsoft Defender for Identity.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security e Microsoft Defender for Identity for User fornecem os direitos de benefício do Microsoft Defender for Identity.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos do Microsoft Defender for Identity são habilitados no nível de inquilino para todos os usuários dentro do inquilino. Para obter informações sobre a configuração do ATP do Azure, consulte [Criar sua instância Microsoft Defender for Identity](/defender-for-identity/install-step1).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado apenas aos usuários do inquilino que são licenciados para o serviço?

Os serviços Microsoft Defender for Identity não são atualmente capazes de limitar recursos a usuários específicos. Você deve licenciar todos os usuários que pretende beneficiar.

## <a name="microsoft-defender-for-office-365"></a>Microsoft Defender para Office 365

O Microsoft Defender for Office 365 (anteriormente Office 365 Advanced Threat Protection) ajuda a proteger as organizações contra ataques sofisticados, como phishing e malware de zero-day. O Microsoft Defender for Office 365 também fornece insights acionáveis, correlacionando sinais de uma ampla gama de dados para ajudar a identificar, priorizar e fornecer recomendações sobre como lidar com possíveis ameaças.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

O Microsoft Defender for Office 365 protege os usuários de ataques sofisticados, como phishing e malware de zero-day. Para obter a lista completa de serviços prestados no Plano 1 e no Plano 2, consulte [o Microsoft Defender para Office 365](/microsoft-365/security/office-365-security/office-365-atp).

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço? 

Microsoft Defender for Office 365 Plans 1 e 2, Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security e Microsoft 365 Business Premium fornecer os direitos para um usuário se beneficiar do Microsoft Defender por Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos do Microsoft Defender for Office 365 são habilitados no nível de inquilino para todos os usuários dentro do inquilino. Para obter informações sobre a configuração do Microsoft Defender para Office 365 políticas para usuários licenciados, consulte [o Microsoft Defender para Office 365](/microsoft-365/security/office-365-security/office-365-atp).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado apenas aos usuários do inquilino que são licenciados para o serviço?

Para escopo do Microsoft Defender para Office 365, siga as políticas de implantação de links e Cofre anexos Cofre:

- Para obter informações sobre a configuração de links Cofre para usuários licenciados, consulte [Cofre Links no Microsoft Defender para Office 365](/microsoft-365/security/office-365-security/atp-safe-links).

- Para obter informações sobre a configuração de anexos Cofre para usuários licenciados, consulte [Cofre Anexos no Microsoft Defender para Office 365](/microsoft-365/security/office-365-security/atp-safe-attachments).

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security (OCAS) é um subconjunto de Microsoft Cloud App Security, com recursos limitados a Office 365 e sem segurança adicional para aplicativos em nuvem de terceiros e serviços de IaaS.

A OCAS dá às organizações visibilidade de seus aplicativos e serviços em nuvem de produtividade, fornece análises sofisticadas para identificar e combater ameaças cibernéticas e permite que elas controlem como os dados viajam &mdash; através de Office 365.

Para comparar características, consulte [Diferenças entre Microsoft Cloud App Security e Office 365 Cloud App Security](/cloud-app-security/editions-cloud-app-security-o365).

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

O OCAS descobre a SHADOW IT, fornece proteção contra ameaças em Office 365 e pode controlar quais aplicativos têm permissão para acessar dados.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Office 365 E5/A3/A5/G5 fornecem os direitos para um usuário se beneficiar de OCAS.
Para obter mais informações, consulte o [Microsoft Cloud App Security Licensing Datasheet](https://www.aka.ms/mcaslicensing).

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos OCAS são habilitados no nível de inquilino para todos os usuários dentro do inquilino.

Para obter informações sobre a configuração do serviço, consulte [Configuração básica para Cloud App Security](/cloud-app-security/general-setup).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado apenas aos usuários do inquilino que são licenciados para o serviço?

Os administradores podem escopo de implantações OCAS para impor como certos aplicativos são acessados e limitar grupos de usuários monitorados por Office 365 Cloud App Security. Para obter mais informações, consulte [a implantação do Escopo](/cloud-app-security/scoped-deployment).

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) é uma solução CASB (Cloud Access Security Broker, corretora de segurança de acesso à nuvem) que dá às organizações visibilidade de seus aplicativos e serviços em nuvem, fornece análises sofisticadas para identificar e combater ameaças cibernéticas e permite que elas controlem como os dados viajam &mdash; por qualquer aplicativo em nuvem.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

O MCAS descobre e avalia a Shadow IT, fornece proteção contra ameaças em aplicativos de nuvem de terceiros e protege informações em aplicativos de nuvem de terceiros e de terceiros.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

MCAS, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, segurança Microsoft 365 E5/A5/G5, conformidade Microsoft 365 E5/A5/G5 e proteção e governança de informações Microsoft 365 fornecem os direitos para que um usuário se beneficie do MCAS.

O Azure AD P1 fornece os direitos para um usuário se beneficiar dos recursos do Discovery no MCAS.

Para se beneficiar dos recursos do Controle de Aplicativos de Acesso Condicional no MCAS, os usuários também devem ser licenciados para Azure Active Directory P1, que está incluído em Enterprise Mobility + Security E3/A3/G3, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E3/A3/G3, Microsoft 365 E5/A5/G5 e Microsoft 365 E5/A5/G5 Security.

Para se beneficiar da rotulagem automática do lado do cliente, os usuários devem ser licenciados para o Azure Information Protection P2, que está incluído em Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance e Microsoft 365 Information Protection and Governance.

> [!NOTE]
> A rotulagem automática do lado do servidor requer proteção de informações para Office 365 - licenças Premium `MIP_S_CLP2` (ou `efb0351d-3b08-4503-993d-383af8de41e3` ). Para referência, consulte [nomes de produtos e identificadores de planos de serviço para licenciamento](/azure/active-directory/enterprise-users/licensing-service-plan-reference).

Para obter mais informações, consulte o [Microsoft Cloud App Security Licensing Datasheet](https://www.aka.ms/mcaslicensing).

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos do MCAS são habilitados no nível de inquilino para todos os usuários dentro do inquilino.

Para obter informações sobre a configuração de políticas Microsoft Cloud App Security para usuários licenciados, consulte [Microsoft Cloud App Security visão geral](/cloud-app-security/what-is-cloud-app-security).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado apenas aos usuários do inquilino que são licenciados para o serviço?

Os administradores podem escopo de implantações mcas para usuários licenciados usando os recursos de implantação escopo disponíveis no serviço. Para obter mais informações, consulte [a implantação do Escopo](/cloud-app-security/scoped-deployment).

## <a name="compliance-manager"></a>Gerenciador de Conformidade

Simplifique a conformidade e ajude a reduzir o risco com o Compliance Manager. O Compliance Manager ajuda as organizações a atender aos requisitos de regulamentos, normas, políticas da empresa ou outras estruturas de controle desejadas.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

A seguir estão os benefícios para os usuários do serviço Compliance Manager:

- Traduz regulamentos, padrões, políticas da empresa complicadas ou outras estruturas de controle desejadas em linguagem simples
- Fornece acesso a uma vasta biblioteca de avaliações e avaliações personalizadas para atender às necessidades de conformidade únicas
- Mapas controles regulatórios para ações recomendadas de melhoria
- Fornece orientação passo a passo sobre como implementar as soluções para atender aos requisitos regulatórios
- Ajuda os usuários a priorizar ações que terão o maior impacto em sua conformidade organizacional, associando uma pontuação a cada ação

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Os clientes com licenças E1 e E3/G3 poderão acessar apenas a avaliação padrão da Linha de Base de Proteção de Dados. Os clientes com Office 365 licenças E5/A5 e Microsoft 365 E5/A5 (Conformidade, Proteção de Informações & Governança e SKUs de eDiscovery e Auditoria incluídas) poderão acessar avaliações de base de proteção de dados, GDPR, NIST 800-53 e avaliações iso 27001 fora da caixa. Os clientes com Office 365 G5 e Microsoft 365 G5 poderão acessar a Linha de Base de Proteção de Dados, GDPR, NIST 800-53, ISO 27001 e Certificação de Modelo de Maturidade de Cibersegurança (CMMC) Níveis 1 a 5 avaliações fora da caixa. Os recursos de avaliação personalizados e avaliações premium são reservados para Office 365 clientes E5/A5/G5 e Microsoft 365 E5/A5/G5. avaliações Premium, como FedRAMP Moderate, FedRAMP High e outras, estarão disponíveis para compra para clientes com licenças E5/A5/G5 durante o primeiro semestre de 2021 através de VL, CSP e WebDirect. Entre em contato com seu vendedor da Microsoft ou Parceiro Microsoft para comprar através de canais VL ou CSP, respectivamente. Para comprar através do WebDirect, consulte [WebDirect](https://aka.ms/ComplianceManager/WebDirect).

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

O Compliance Manager é provisionado por padrão para o seu inquilino. Os administradores definem as permissões do usuário e atribuem funções para que usuários não administradores em sua organização possam começar a usar o Compliance Manager. Para obter mais informações, consulte [Obter início com o Gerenciador de Conformidade: Definir permissões do usuário e atribuir funções](/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles).

## <a name="microsoft-defender-for-endpoint"></a>Microsoft Defender para Ponto de Extremidade

O Microsoft Defender for Endpoint (anteriormente Microsoft Defender ATP) é uma solução de segurança de ponto final que inclui Gerenciamento de Vulnerabilidades e avaliação baseadas em riscos; capacidades de redução da superfície de ataque; proteção de próxima geração baseada em comportamento e alimentada por nuvens; detecção e resposta de ponto de extremidade (EDR); investigação automática e remediação; e gerenciava serviços de caça. Consulte a página [Do Microsoft Defender para Endpoint](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) para saber mais.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Usuários licenciados de Windows 10 Enterprise E5, Windows 10 Education A5, Microsoft 365 E5/G5, que inclui Windows 10 Enterprise E5, Microsoft 365 E5/A5/G5 Security, podem se beneficiar do Microsoft Defender para endpoint.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Analistas e profissionais de segurança da SecOps se beneficiam dos recursos de segurança do Microsoft Defender for Endpoint para fazer proteção preventiva, detecção pós-violação, investigação automatizada e resposta a ameaças avançadas. Os usuários finais se beneficiam por ter eventos maliciosos monitorados pelo Microsoft Defender para endpoint.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos do Microsoft Defender for Endpoint são habilitados no nível de inquilino para todos os usuários dentro do inquilino. Para obter informações sobre a implantação, consulte [fases de implantação](/windows/security/threat-protection/microsoft-defender-atp/deployment-phases).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado apenas aos usuários do inquilino que são licenciados para o serviço?

Os administradores do Microsoft Defender for Endpoint podem usar o controle de acesso baseado em funções (RBAC) para criar funções e grupos dentro da equipe de operações de segurança para conceder acesso adequado ao Central de Segurança do Microsoft Defender. Para obter mais informações, consulte [Gerenciar o acesso ao portal usando o controle de acesso baseado em papel](/windows/security/threat-protection/microsoft-defender-atp/rbac).

## <a name="microsoft-365-data-classification-analytics-overview-content-amp-activity-explorer"></a>Microsoft 365 análise de classificação de dados: Overview Content &amp; Activity Explorer

Os recursos analíticos de classificação de dados estão disponíveis dentro Microsoft 365 experiência do centro de conformidade. A visão geral mostra as localizações de conteúdo digital e os tipos de informações e rótulos sensíveis mais comuns presentes. O Content Explorer fornece visibilidade sobre quantidade e tipos de dados confidenciais e permite que os usuários filtrem por rótulo ou tipo de sensibilidade para obter uma visão detalhada dos locais onde os dados confidenciais são armazenados. O Activity Explorer mostra atividades relacionadas a dados e rótulos confidenciais, como downgrades de rótulos ou compartilhamento externo que podem expor seu conteúdo a riscos.

O Activity Explorer fornece um único painel de vidro para os administradores obterem visibilidade sobre atividades relacionadas a informações confidenciais que estão sendo usadas pelos usuários finais. Esses dados incluem atividades de rótulos, registros de prevenção de perda de dados (DLP), rotulagem automática, DLP endpoint e muito mais.

O Content Explorer fornece aos administradores a capacidade de indexar os documentos confidenciais armazenados dentro de cargas de trabalho Microsoft 365 suportadas e identificar as informações confidenciais que eles estão armazenando. Além disso, o Content Explorer ajuda a identificar documentos classificados com rótulos de sensibilidade e retenção.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os administradores de proteção e conformidade de informações podem acessar o serviço para ter acesso a esses logs e dados indexados para entender onde os dados confidenciais são armazenados e quais atividades estão relacionadas a esses dados e realizadas pelos usuários finais.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Os usuários licenciados de Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection &amp; Governance e Office 365 E5 podem se beneficiar de Microsoft 365 análise de classificação de dados. 

Microsoft 365 E3/A3/G3 e Office 365 E3/A3/G3 permitem que os usuários se beneficiem apenas da agregação de dados do Content Explorer.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos do Overview Content e activity Explorer são ativados no nível de inquilino para todos os usuários dentro do inquilino. Para obter informações sobre a configuração de análises de classificação de dados para usuários licenciados, consulte:

- **Explorador de conteúdo**: [Comece com explorador de conteúdo - Microsoft 365 compliance | Microsoft Docs](/microsoft-365/compliance/data-classification-content-explorer).
- **Activity Explorer**: [Comece com o explorador de atividades - Microsoft 365 Compliance | Microsoft Docs](/microsoft-365/compliance/data-classification-activity-explorer).
- **Notas de liberação de classificação** de dados : [Notas de liberação de classificação de dados - Microsoft 365 Conformidade | Microsoft Docs](/microsoft-365/compliance/data-classification-pub-preview-relnotes).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado apenas aos usuários do inquilino que são licenciados para o serviço?

Esse recurso precisa ser escopo para usuários que usam ativamente a solução dentro Microsoft 365 portal compliance.

## <a name="information-protection"></a>Proteção de informações

A Proteção de Informações ajuda as organizações a descobrir, classificar, rotular e proteger documentos e e-mails confidenciais. Os administradores podem definir regras e condições para aplicar etiquetas automaticamente, os usuários podem aplicar etiquetas manualmente ou uma combinação dos dois pode ser usada — onde os usuários recebem recomendações sobre a aplicação de rótulos.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam por ter a capacidade de aplicar manualmente rótulos de sensibilidade ao seu conteúdo ou por ter seu conteúdo automaticamente classificado.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Microsoft 365 E5/A5/G5/E3/G3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, Office 365 E5/A5/E3/A3/F3, Plano AIP 1 e Plano AIP 2 fornecem os direitos para que o usuário se beneficie da rotulagem manual de sensibilidade.

Microsoft 365 E5/A5/G5/E3/G3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, AIP Plan 1 e AIP Plan 2 fornecem os direitos para que o usuário se beneficie da aplicação e visualização de etiquetas de sensibilidade em Power BI e para proteger os dados quando é exportado de Power BI para Excel, PowerPoint ou PDF. 

> [!NOTE]
> Power BI está incluído com Microsoft 365 E5/A5/G5; em todos os outros planos, Power BI deve ser licenciado separadamente.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection e Governança, Office 365 E5, Enterprise Mobility + Security E5/A5/G5 e Plano AIP 2 fornecem os direitos para que o usuário se beneficie da rotulagem automática de sensibilidade.

Para obter direitos específicos por licença, consulte a comparação detalhada de licenciamento de conformidade Microsoft 365. [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx) Não inclui direitos de classificação automática com base em Machine Learning (classificadores de formação).

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos de proteção de informações são habilitados no nível do inquilino para todos os usuários dentro do inquilino. Para obter informações sobre a configuração de políticas para usuários licenciados, consulte Ativar o Gerenciamento de Direitos do Azure.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado apenas aos usuários do inquilino que são licenciados para o serviço?

Exceto quando se usa o recurso de scanner AIP, as políticas podem ser escopo para grupos ou usuários específicos e registros podem ser editados para evitar que usuários não licenciados executem recursos de classificação ou rotulagem. Para obter instruções sobre como escopo de implantações AIP, consulte [Configuração da política de Proteção de Informações do Azure](/azure/information-protection/configure-policy).

Para o recurso de scanner AIP, a Microsoft não se compromete a fornecer recursos de classificação, rotulagem ou proteção de arquivos para usuários que não são licenciados.

## <a name="information-governance"></a>Governança da Informação

A Governança da Informação ajuda as organizações a gerenciar seus riscos através da descoberta, classificação, rotulagem e reger seus dados. A Governança de Informações permite que as organizações atendam aos requisitos comerciais e regulatórios, bem como reduzam sua superfície de ataque, fornecendo recursos de retenção e exclusão em seus Microsoft 365 e dados de terceiros.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam por serem capazes de classificar dados para fins de retenção para manter políticas e regulamentos específicos.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Microsoft 365 F3/Premium de negócios, Office 365 E1/A1/F3 e planos Exchange autônomos fornecem os direitos para um usuário se beneficiar da aplicação manual de etiquetas de retenção não-gravadas em dados de caixa de correio.

Microsoft 365 F3/F1/Premium de negócios, Office 365 E1/A1/F3 e planos de SharePoint autônomos fornecem os direitos para que um usuário se beneficie da aplicação manual de etiquetas de retenção não-registros em arquivos em SharePoint ou OneDrive. 

Microsoft 365 E5/A5/G5/E3/A3/Business Premium, Office 365 E5/A5/G5/E3/A3, Exchange Plano 2 e Arquivamento do Exchange Online fornecer os direitos para que um usuário se beneficie de uma política básica de retenção de caixa de correio em toda a organização ou em toda a localização e/ou aplique manualmente uma rotulagem de retenção não registrada aos dados da caixa de correio.

Microsoft 365 E5/A5/G5/E3/A3, Office 365 E5/A5/G5/E3/A3 e SharePoint Plano 2 fornecem os direitos para que um usuário se beneficie de uma política básica de retenção de SharePoint ou OneDrive e/ou aplique manualmente uma etiqueta de retenção não-registro em arquivos em SharePoint ou OneDrive.

Microsoft 365 E5/A5/G5/E3/A3 e Office 365 E5/A5/G5/E3/A3 fornecem os direitos para que um usuário se beneficie de uma política de retenção de Teams.

Microsoft 365 E5/A5/G5, conformidade Microsoft 365 E5/A5/G5, proteção e governança de informações Microsoft 365 E5/A5/G5, e Office 365 E5/A5 fornecem os direitos para que um usuário se beneficie da aplicação automática de rótulos ou políticas de retenção, a aplicação de rótulos ou políticas de retenção padrão, o início do período de retenção de um rótulo de retenção com base em um evento personalizado, desencadeando uma revisão de disposição manual no final do período de retenção da etiqueta, importando dados de terceiros através de conectores de dados nativos, declarando um registro de arquivo, descobrindo conteúdo rotulado e monitorando a atividade de rotulagem.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection e Governança fornecem os direitos para que o usuário se beneficie da aplicação automática de etiquetas de retenção com base em classificadores de classificação de formação.

Para obter direitos específicos por licença, consulte a comparação detalhada de licenciamento de conformidade Microsoft 365. [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos de Governança de Informações são habilitados no nível de inquilino para todos os usuários dentro do inquilino. Para obter informações sobre a configuração de Governança de Informações para aplicar autolabeling e políticas para usuários licenciados, consulte [Microsoft Information Governance em Microsoft 365](/microsoft-365/compliance/manage-information-governance).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado apenas aos usuários do inquilino que são licenciados para o serviço?

Os recursos de governança de informações podem ser aplicados a usuários licenciados em locais específicos (sites de equipe, sites de grupo, etc.). Para obter informações sobre a configuração de Governança de Informações para aplicar autolabeling e políticas para usuários licenciados, consulte [Microsoft Information Governance em Microsoft 365](/microsoft-365/compliance/manage-information-governance).

## <a name="records-management"></a>Gerenciamento de Registros

A Records Management ajuda as organizações a cumprir suas obrigações de registro de negócios e regulamentações através da descoberta, classificação, rotulagem, retenção e exclusão defensável em seus Microsoft 365 e dados de terceiros.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 Information Protection and Governance E5/A5/G5 e Office 365 E5/A5/G5 fornecem os direitos para um usuário se beneficiar do Gerenciamento de Registros, incluindo declarar itens como registros ou registros regulatórios, aplicar automaticamente rótulos de retenção ou registro e executar processos de revisão de eliminação (excluindo a aplicação automática de um rótulo de retenção com base em classificadores de classe de formação.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance e Microsoft 365 Information Protection and Governance fornecem os direitos para que um usuário se beneficie da aplicação automática de etiquetas de retenção ou de registro com base em classificadores de classe capacitáveis.

Para obter direitos específicos por licença, consulte a comparação detalhada de licenciamento de conformidade Microsoft 365. [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam ao poderem declarar o conteúdo como um registro e gerenciar seu processo completo de registros desde a definição e declaração da política por meio do descarte defensável.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos de gerenciamento de registros são habilitados no nível de inquilino para todos os usuários dentro do inquilino. Para obter informações sobre a configuração de gerenciamento de registros para solicitar usuários licenciados, consulte [Aprender sobre gerenciamento de registros em Microsoft 365](/microsoft-365/compliance/records-management).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado apenas aos usuários do inquilino que são licenciados para o serviço?

Os recursos de gerenciamento de registros podem ser aplicados a usuários licenciados em locais específicos (sites de equipe, sites de grupo, etc.). Para obter informações sobre a configuração de gerenciamento de registros para solicitar usuários licenciados, consulte [Aprender sobre gerenciamento de registros em Microsoft 365](/microsoft-365/compliance/records-management).

## <a name="data-connectors"></a>Conectores de dados 

A Microsoft fornece conectores de dados de terceiros que podem ser configurados no centro de conformidade Microsoft 365. Para obter uma lista de conectores de dados fornecidos pela Microsoft, consulte a tabela [de conectores de dados de terceiros.](/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) Esta tabela também resume as soluções de conformidade que você pode aplicar a dados de terceiros depois de importar e arquivar dados em Microsoft 365 e links para as instruções passo a passo de cada conector.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

O principal benefício do uso de conectores de dados para importar e arquivar dados de terceiros em Microsoft 365 é que você pode aplicar várias soluções de conformidade Microsoft 365 aos dados depois de importados. Isso ajuda a garantir que os dados não Microsoft da sua organização estão em conformidade com as normas e padrões que afetam sua organização.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

As seguintes licenças fornecem os direitos para um usuário se beneficiar dos Conectores de Dados:

- Microsoft 365 E5/A5/G5
- governança de proteção de informações Microsoft 365 E5/A5/G5 &amp;
- conformidade Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 Insider Risk Management
- Microsoft 365 E5/A5/G5 eDiscovery and Audit
- Office 365 E5/A5/G5

Para conectores de dados no centro de conformidade de segurança Microsoft 365 &amp; fornecido por um parceiro da Microsoft, sua organização precisará de um relacionamento comercial com o parceiro antes que você possa implantar esses conectores.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Os conectores são configurados usando o Centro de Conformidade de Segurança &amp; e o Catálogo do Conector.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado apenas aos usuários do inquilino que são licenciados para o serviço?

Os serviços de Conectores de dados são um valor de nível de inquilino. Todo usuário destinado a se beneficiar deste serviço deve ser licenciado.

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp"></a>A Microsoft Graph APIs para prevenção de Teams de perda de dados (DLP)

No início deste [ano, anunciamos a visualização pública da API de Notificação de Alteração da Microsoft Graph para mensagens em Teams](https://go.microsoft.com/fwlink/?linkid=2143888). Esta API permite que os desenvolvedores construam aplicativos que possam ouvir Microsoft Teams mensagens em tempo quase real e permitir implementações de cenários DLP para clientes e ISVs. Além disso, a API de Patch Graph da Microsoft permite aplicar ações de DLP para Teams mensagens.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os recursos de [prevenção de perda de dados (DLP)](/microsoft-365/compliance/dlp-microsoft-teams) são amplamente utilizados em Microsoft Teams, particularmente à medida que as organizações mudaram para o trabalho remoto. Se sua organização tiver DLP, agora você pode definir políticas que impeçam as pessoas de compartilhar informações confidenciais em um canal de Microsoft Teams ou sessão de bate-papo.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Você precisará de uma das seguintes licenças para obter suporte para proteção DLP em Teams Chat:

- Microsoft 365 E5/A5/G5
- conformidade Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 Proteção e Governança de Informações
- Office 365 E5/A5/G5 

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

O acesso à API é configurado no nível do inquilino.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado apenas aos usuários do inquilino que são licenciados para o serviço?

A API Graph da Microsoft para Teams DLP é um valor de nível de inquilino. Todo usuário destinado a se beneficiar deste serviço deve ser licenciado.

## <a name="ediscovery"></a>Descoberta eletrônica

O eDiscovery fornece soluções de investigação e eDiscovery para departamentos de TI e jurídicos dentro de corporações para identificar, coletar, preservar, reduzir e revisar conteúdo relacionado a uma investigação ou litígio antes de exportar para fora do sistema Microsoft 365.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Um usuário se beneficia de Advanced eDiscovery quando o usuário é selecionado como um custodiante de dados (uma pessoa que tem controle administrativo de um documento ou arquivo eletrônico) para um caso.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Microsoft 365 E5/A5/G5/E3/A3/G3, Office 365 E5/A5/G5/E3/A3/G3 fornecem os direitos para que um usuário se beneficie do Core eDiscovery.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 eDiscovery and Audit e Office 365 E5/A5/G5 fornecem os direitos para que um usuário se beneficie de Advanced eDiscovery.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos Advanced eDiscovery são habilitados no nível de inquilino para todos os usuários dentro do inquilino quando os administradores atribuem permissões de eDiscovery no &amp; Centro de Conformidade de Segurança.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado apenas aos usuários do inquilino que são licenciados para o serviço?

Os administradores do eDiscovery podem selecionar usuários específicos como guardiões de dados para um caso usando a ferramenta de gerenciamento de custódia incorporada em Advanced eDiscovery como descrito em [Adicionar custodiadores para um caso Advanced eDiscovery](/microsoft-365/compliance/add-custodians-to-case).

## <a name="customer-key-for-microsoft-365"></a>Chave do cliente para Microsoft 365

Com a Chave do Cliente, você controla as chaves de criptografia da sua organização e configura Microsoft 365 usá-las para criptografar seus dados em repouso nos data centers da Microsoft. Em outras palavras, a Chave do Cliente permite que você adicione uma camada de criptografia que pertence a você, usando suas próprias chaves. Os dados em repouso incluem dados de Exchange Online e Skype for Business que são armazenados em caixas de correio e arquivos dentro SharePoint Online e OneDrive for Business.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam da Chave do Cliente tendo seus dados em repouso criptografados na camada do aplicativo usando chaves de criptografia fornecidas, controladas e gerenciadas por sua própria organização.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection and Governance e Office 365 E5/A5/G5 fornecem os direitos para que um usuário se beneficie da Chave do Cliente. Para obter o benefício total da Chave do Cliente, você também deve ter uma assinatura do Azure Key Vault.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

A chave do cliente para Microsoft 365 chaves de criptografia pode ser habilitada para todos os dados armazenados em caixas de correio Exchange Online e Skype for Business, e SharePoint arquivos Online, OneDrive for Business e Teams. Para obter mais informações sobre a Chave do Cliente, incluindo como começar, consulte [criptografia de serviço com chave do cliente](/microsoft-365/compliance/customer-key-overview).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado apenas aos usuários do inquilino que são licenciados para o serviço?

Para Exchange Online e Skype for Business, as caixas de correio podem ser criptografadas usando a Chave do Cliente. Você deve configurar o Azure antes de usar a Chave do Cliente para Microsoft 365. Consulte [Configurar a chave do cliente](/microsoft-365/compliance/customer-key-set-up) para obter as etapas que você precisa seguir para criar e configurar os recursos necessários do Azure e as etapas para configurar a Chave do Cliente em Microsoft 365. Depois de concluir a configuração do Azure, determine qual política e, portanto, quais chaves atribuir a caixas de correio e arquivos em sua organização. Para obter mais informações sobre a Chave do Cliente e conteúdo sobre dados de Exchange Online, Skype for Business, SharePoint Online, OneDrive for Business e Teams, consulte [criptografia de serviço com chave do cliente](/microsoft-365/compliance/customer-key-overview).

## <a name="office-365-customer-lockbox"></a>Sistema de Proteção de Dados do Cliente do Office 365

O Customer Lockbox fornece uma camada adicional de controle, oferecendo aos clientes a capacidade de dar autorização de acesso explícito para operações de serviço. Ao demonstrar que os procedimentos estão em vigor para autorização explícita de acesso a dados, o Customer Lockbox também pode ajudar as organizações a cumprir certas obrigações de conformidade, como HIPAA e FedRAMP.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

O Customer Lockbox garante que ninguém na Microsoft possa acessar o conteúdo do cliente para realizar uma operação de serviço sem a aprovação explícita do cliente. O Customer Lockbox traz o cliente para o fluxo de trabalho de aprovação para solicitações de acesso ao seu conteúdo. Ocasionalmente, os engenheiros da Microsoft estão envolvidos durante o processo de suporte para solucionar problemas e corrigir problemas relatados pelo cliente. Na maioria dos casos, os problemas são corrigidos por meio de extensas ferramentas de telemetria e depuração que a Microsoft tem em vigor para seus serviços. No entanto, pode haver casos que requerem que um engenheiro da Microsoft acesse o conteúdo do cliente para determinar a causa raiz e corrigir o problema. O Sistema de Proteção de Dados do Cliente exige que o engenheiro solicite acesso do cliente como uma etapa final no fluxo de trabalho de aprovação. Isso dá às organizações a opção de aprovar ou negar essas solicitações, o que lhes dá controle direto sobre se um engenheiro da Microsoft pode acessar os dados do usuário final das organizações.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance e Microsoft 365 E5/A5/G5 Insider Risk Management fornecem os direitos para um usuário se beneficiar do Lockbox do Cliente.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Os administradores podem ativar o Customer Lockbox no centro administrativo Microsoft 365. Para obter mais informações, consulte [o Customer Lockbox em Office 365](/microsoft-365/compliance/customer-lockbox-requests). Quando o Customer Lockbox é ligado, a Microsoft é obrigada a obter a aprovação de uma organização antes de acessar qualquer um de seus conteúdos.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado apenas aos usuários do inquilino que são licenciados para o serviço?

Atualmente, o serviço Customer Lockbox não pode ser limitado a usuários específicos. Você deve licenciar todos os usuários que pretende beneficiar.

## <a name="privileged-access-management-in-office-365"></a>O Privileged Access Management no Office 365

[O PAM (Privileged Access Management, gerenciamento de acesso privilegiado)](/microsoft-365/compliance/privileged-access-management-configuration) fornece controle de acesso granular sobre tarefas de administração privilegiadas em Office 365. Depois de habilitar o PAM, para completar tarefas elevadas e privilegiadas, os usuários precisarão solicitar acesso just-in-time através de um fluxo de trabalho de aprovação altamente escopo e vinculado ao tempo.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

A ativação do PAM permite que as organizações operem com zero privilégios permanentes. Os usuários se beneficiam da camada adicional de defesa contra vulnerabilidades decorrentes do acesso administrativo permanente que fornece acesso irrestrito aos seus dados.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço? 

Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance e Microsoft 365 E5/A5 Information Protection and Governance fornecem os direitos para um usuário se beneficiar do PAM.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos PAM são habilitados no nível de inquilino para todos os usuários dentro do inquilino. Para obter informações sobre a configuração de políticas PAM, consulte [Começar com gerenciamento de acesso privilegiado](/microsoft-365/compliance/privileged-access-management-configuration).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado apenas aos usuários do inquilino que são licenciados para o serviço?

Os clientes podem gerenciar o PAM por usuário por meio de políticas de grupo aprovador e de acesso, que podem ser aplicadas a usuários licenciados. Para obter mais informações, consulte [gerenciamento de acesso privilegiado em Office 365](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751).

## <a name="double-key-encryption-for-microsoft-365"></a>Criptografia de chave dupla para Microsoft 365 

A criptografia de chave dupla para Microsoft 365 permite proteger seus dados altamente confidenciais para atender a requisitos especializados e manter o controle total da sua chave de criptografia. O Double Key Encryption usa duas chaves para proteger seus dados, com uma chave no controle e a segunda chave armazenada com segurança Microsoft Azure. Para visualizar os dados, você deve ter acesso a ambas as chaves. Como a Microsoft pode acessar apenas uma chave, sua chave e também seus dados não estão disponíveis para a Microsoft, garantindo que você tenha controle total sobre a privacidade e segurança de seus dados.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam da Criptografia de Tecla Dupla, podendo migrar seus dados criptografados para a nuvem, o que impede o acesso de terceiros enquanto a chave permanecer no controle dos usuários. Os usuários podem proteger e consumir conteúdo criptografado double key semelhante a qualquer outro conteúdo protegido por rótulo de sensibilidade.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection and Governance e Office 365 E5/A5/G5 fornecem os direitos para que um usuário se beneficie da Criptografia de Chave Dupla.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Double Key Encryption suporta a versão desktop de Microsoft Office para Windows.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado apenas aos usuários do inquilino que são licenciados para o serviço?

Para atribuir chaves de criptografia aos dados dentro de uma organização de Office 365 e/ou Microsoft 365 para usuários licenciados, siga as instruções de implantação da Double Key Encryption.

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Office 365 prevenção de perda de dados para Exchange Online, SharePoint Online e OneDrive for Business

Com Office 365 prevenção de perda de dados (DLP) para Exchange Online, SharePoint Online e OneDrive for Business, as organizações podem identificar, monitorar e proteger automaticamente informações confidenciais entre e-mails e arquivos (incluindo arquivos armazenados em repositórios de arquivos Microsoft Teams).

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam do DLP por Exchange Online, SharePoint Online e OneDrive for Business quando seus e-mails e arquivos estão sendo inspecionados para obter informações confidenciais, conforme configurado na política DLP da organização.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Microsoft 365 E3/A3/Premium de negócios, Office 365 E3/A3 e Office 365 Prevenção de Perda de Dados fornecem os direitos para que um usuário se beneficie de Office 365 DLP para Exchange Online, SharePoint Online e OneDrive for Business.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, Exchange Online e-mails, sites de SharePoint e contas OneDrive são *locais habilitados (cargas de trabalho)* para esses recursos DLP para todos os usuários dentro do inquilino. Para obter mais informações sobre o uso de políticas DLP, consulte [Visão geral da prevenção de perda de dados](/microsoft-365/compliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado apenas aos usuários do inquilino que são licenciados para o serviço?

Os administradores podem personalizar locais (cargas de trabalho), usuários incluídos e usuários excluídos no &amp; Centro de Conformidade de Segurança, em Locais de prevenção de perda **de**  >  **dados**.

## <a name="communication-data-loss-prevention-for-teams"></a>Prevenção de perda de dados de comunicação para Teams

Com o DLP de comunicação para Teams, as organizações podem bloquear chats e mensagens de canal que contenham informações confidenciais, como informações financeiras, identificação pessoal de informações, informações relacionadas à saúde ou outras informações confidenciais.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Os usuários licenciados de Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5 e Microsoft 365 E5/A5/G5 Information Protection and Governance podem se beneficiar da DLP de comunicação para Teams.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os remetentes se beneficiam por ter informações confidenciais em seu chat de saída e mensagens de canal inspecionadas para obter informações confidenciais, conforme configurado na política DLP da organização.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, Teams chat e mensagens de canal são uma *localização (carga de trabalho) habilitada* para esses recursos DLP para todos os usuários dentro do inquilino. Para obter mais informações sobre o uso de políticas DLP, consulte [Visão geral da prevenção de perda de dados](/office365/securitycompliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado apenas aos usuários do inquilino que são licenciados para o serviço?

Os administradores podem personalizar locais (cargas de trabalho), usuários incluídos e usuários excluídos no &amp; Centro de Conformidade de Segurança, em Locais de prevenção de perda **de**  >  **dados**.

## <a name="information-barriers"></a>Barreiras de informações

Os obstáculos de informação são políticas que um administrador pode configurar para impedir que indivíduos ou grupos se comunique entre si. Isso é útil se, por exemplo, um departamento estiver lidando com informações que não devem ser compartilhadas com outros departamentos, ou um grupo precisa ser impedido de se comunicar com contatos externos. As políticas de barreira de informação também impedem buscas e descobertas. Isso significa que se você tentar se comunicar com alguém com quem não deve se comunicar, você não encontrará esse usuário no catador de pessoas.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam dos recursos avançados de conformidade das barreiras de informação quando estão proibidos de se comunicar com outros. As políticas de barreiras de informação podem ser definidas para evitar que determinado segmento de usuários se comuniquem com cada um ou permitir que segmentos específicos se comuniquem apenas com determinados outros segmentos. Para obter mais informações sobre a definição de políticas de barreira de informações, consulte [Definir políticas de barreira de informações](/microsoft-365/compliance/information-barriers-policies). Para cenários em que dois grupos não podem se comunicar entre si, os usuários de ambos os grupos exigem uma licença para se beneficiar do serviço (veja abaixo o exemplo).<br><br>

| Cenário | Who requer uma licença? |
|:------|:------|
| Dois grupos (Grupo &nbsp; 1 e Grupo &nbsp; 2) não podem se comunicar entre si (ou seja, os usuários do Grupo &nbsp; 1 estão impedidos de se comunicar com os usuários do Grupo &nbsp; 2, e os usuários do Grupo &nbsp; 2 estão proibidos de se comunicar com os usuários do Grupo &nbsp; 1. | Usuários do Grupo &nbsp; 1 e do Grupo &nbsp; 2 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Insider Risk Management e Office 365 E5/A5/G5, fornecem os direitos para que um usuário se beneficie de barreiras de informação.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Os administradores criam e gerenciam políticas de barreira de informações usando cmdlets do PowerShell no &amp; Centro de Conformidade de Segurança. Os administradores devem ser designados para o Microsoft 365 Enterprise o cargo de administrador global, administrador global Office 365 ou administrador de conformidade para criar uma política de barreira de informações. Por padrão, essas políticas se aplicam a todos os usuários do inquilino. Para obter mais informações sobre barreiras de informação, consulte [barreiras de informação em Microsoft Teams](/MicrosoftTeams/information-barriers-in-teams).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado apenas aos usuários do inquilino que são licenciados para o serviço?

Os administradores podem personalizar locais (cargas de trabalho), usuários incluídos e usuários excluídos no &amp; Centro de Conformidade de Segurança. Por exemplo, se todos os usuários forem licenciados para Office 365 E3 e nenhum for licenciado para Conformidade Avançada do Office 365/E5, eles não precisarão criar nenhuma política de barreira de informações para a organização. Para obter mais informações, consulte [Barreiras de informações no Microsoft Teams](/MicrosoftTeams/information-barriers-in-teams).

## <a name="office-365-message-encryption"></a>Criptografia de Mensagem do Office 365

Criptografia de Mensagens do Office 365 (OME) é um serviço integrado ao Azure Rights Management (Azure RMS) que permite o envio de emails criptografados para pessoas dentro ou fora da sua organização, independente do endereço de email de destino (Gmail, Yahoo! Email, Outlook.com, etc.).

Para exibir mensagens criptografadas, os destinatários podem obter uma senha avulsa, entrar com uma conta da Microsoft ou com uma conta corporativa ou de estudante associada ao Office 365. Os destinatários também podem enviar respostas criptografadas. Eles não precisam de uma assinatura para visualizar mensagens criptografadas ou enviar respostas criptografadas.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os remetentes de mensagens se beneficiam do controle adicional sobre e-mails confidenciais fornecidos pela Criptografia de Mensagens do Office 365.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Microsoft 365 E3/A3/G3, Office 365 E3/A3/G3 e o Plano de Proteção de Informações do Azure 1 fornecem os direitos para que um usuário se beneficie de Criptografia de Mensagens do Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Os administradores criam e gerenciam políticas de Criptografia de Mensagens do Office 365 no centro administrativo Exchange sob regras **de fluxo de**  >  **correio**. Por padrão, essas regras se aplicam a todos os usuários do inquilino. Para obter mais informações sobre a criação de novos recursos de Criptografia de Mensagens do Office 365, consulte [Configurar novos recursos de criptografia de mensagens](/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado apenas aos usuários do inquilino que são licenciados para o serviço?

Os administradores devem aplicar regras de fluxo de correio para Criptografia de Mensagens do Office 365 apenas para usuários licenciados. Para obter mais informações sobre a definição de regras de fluxo de e-mails, consulte [Definir regras de fluxo de e-mail para criptografar mensagens de e-mail](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="office-365-advanced-message-encryption"></a>Criptografia de Mensagem Avançada do Office 365

Criptografia de Mensagem Avançada do Office 365 ajuda os clientes a cumprir obrigações de conformidade que exigem controles mais flexíveis sobre os destinatários externos e seu acesso a e-mails criptografados. Com a Criptografia avançada de mensagens, os administradores podem controlar e-mails confidenciais compartilhados fora da organização usando políticas automáticas que podem detectar tipos de informações confidenciais (por exemplo, identificar pessoalmente informações ou IDs financeiros ou de saúde), ou podem usar palavras-chave para melhorar a proteção, aplicando modelos de e-mail personalizados e expirando acesso a e-mails criptografados através de um portal da Web seguro. Além disso, os administradores podem controlar ainda mais os e-mails criptografados acessados externamente através de um portal da Web seguro, revogando o acesso a qualquer momento.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os remetentes de mensagens se beneficiam do controle adicional sobre e-mails confidenciais fornecidos pela Criptografia avançada de mensagens.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance e Microsoft 365 E5/A5/G5 Information Protection and Governance fornecem os direitos para um usuário se beneficiar da criptografia avançada de mensagens.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Os administradores criam e gerenciam políticas avançadas de criptografia de mensagens no centro administrativo Exchange sob regras **de fluxo de**  >  **correio**. Por padrão, essas regras se aplicam a todos os usuários do inquilino. Para obter mais informações sobre a criação de novos recursos de criptografia de mensagens, consulte [Configurar novos recursos de Criptografia de Mensagens do Office 365](/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado apenas aos usuários do inquilino que são licenciados para o serviço?

Os administradores devem aplicar regras de fluxo de e-mail para criptografia de mensagem avançada apenas para usuários licenciados. Para obter mais informações sobre a definição de regras de fluxo de e-mails, consulte [Definir regras de fluxo de e-mail para criptografar mensagens de e-mail em Office 365](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="communication-compliance"></a>Conformidade em comunicações

A conformidade de comunicação em Microsoft 365 ajuda a minimizar os riscos de comunicação, ajudando você a detectar, capturar e tomar ações de remediação para mensagens inadequadas em sua organização. Você pode definir políticas específicas que capturam comunicações internas e externas, Microsoft Teams ou de terceiros em sua organização. Os revisores podem tomar as ações de remediação apropriadas para garantir que estejam em conformidade com os padrões de mensagens da sua organização.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Especialistas em compliance se beneficiam do serviço por ter as comunicações da organização monitoradas pelas políticas de conformidade de comunicação.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance e Microsoft 365 E5/A5/G5 Insider Risk Management fornecem os direitos para que um usuário se beneficie da conformidade com a comunicação.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Administradores e especialistas em compliance criam políticas de conformidade de comunicação no centro de conformidade Microsoft 365. Essas políticas definem quais comunicações e usuários estão sujeitos a revisão na organização, definem as condições personalizadas que as comunicações devem atender e especificam quem deve realizar as revisões.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado apenas aos usuários do inquilino que são licenciados para o serviço?

Os administradores escolhem usuários ou grupos específicos para incluir em uma política de conformidade de comunicação. Ao escolher um grupo, eles também podem selecionar usuários específicos no grupo para excluir da política de conformidade de comunicação. Para obter mais informações sobre políticas de conformidade de comunicação, consulte [Comece com a conformidade de comunicação em Microsoft 365](/microsoft-365/compliance/communication-compliance-configure).

## <a name="insider-risk-management"></a>Gerenciamento de riscos internos

O gerenciamento de riscos internos é uma solução em Microsoft 365 que ajuda a minimizar os riscos internos, permitindo que você detecte, investigue e tome medidas sobre atividades de risco em sua organização.

As políticas personalizadas permitem detectar e tomar medidas sobre atividades maliciosas e inadvertidamente arriscadas em sua organização, incluindo a escalada de casos para a Microsoft Advanced eDiscovery, se necessário. Analistas de risco em sua organização podem tomar rapidamente as ações apropriadas para garantir que os usuários estejam em conformidade com os padrões de conformidade da sua organização.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam por ter suas atividades monitoradas por risco.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance e Microsoft 365 E5/A5/G5 Insider Risk Management fornecem os direitos para um usuário se beneficiar do Insider Risk Management.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

As políticas de gerenciamento de risco de insider devem ser criadas no Microsoft 365 centro de conformidade e atribuídas aos usuários.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado apenas aos usuários do inquilino que são licenciados para o serviço?

Ao criar uma política na Microsoft 365 centro de conformidade, na página **Escolher usuários e grupos,** selecione **Escolher usuários ou grupos** para selecionar apenas usuários licenciados ou, se todos os seus usuários estiverem licenciados, você pode selecionar a caixa de seleção de todos os usuários e **grupos habilitados para e-mail.** Para obter mais informações, consulte [Começar com gerenciamento de risco interno](/microsoft-365/compliance/insider-risk-management-configure).

## <a name="conditional-access-policies"></a>Políticas de Acesso Condicional

O acesso condicional é a ferramenta usada pelo Azure Active Directory para reunir sinais, tomar decisões e impor políticas organizacionais. O Acesso Condicional está no centro do controle orientado pela identidade. As políticas de Acesso Condicional, em suas declarações mais simples, são declarações if-then. Se um usuário quiser acessar um recurso, então ele deve concluir uma ação. Exemplo: Um gestor de folha de pagamento quer acessar o aplicativo de folha de pagamento e é obrigado a realizar autenticação multifatorial para acessá-lo.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Os usuários licenciados de Enterprise Mobility + Security E3/A3, Microsoft 365 F3/E3/A3/Premium de negócios e Azure Active Directory Premium Plano 1 podem se beneficiar das políticas de Acesso Condicional. Os usuários licenciados do Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft E5/G5 Security e Azure Active Directory Premium Plan 2 podem se beneficiar da Proteção de Identidade (políticas de acesso condicional baseadas em riscos).

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Analistas de operações de segurança e profissionais de segurança se beneficiam por terem a capacidade de impor políticas organizacionais aos usuários, exigindo que eles atendam a determinados critérios antes de conceder acesso a conteúdo corporativo. Os usuários finais se beneficiam ao poderem acessar seu trabalho onde e quando quiserem, protegendo os ativos da organização.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos de Acesso Condicional são habilitados no nível de inquilino para todos os usuários dentro do inquilino.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado apenas aos usuários do inquilino que são licenciados para o serviço?

Para proteção de identidade e acesso condicional especificamente, um usuário deve ser incluído em um grupo ou ser adicionado a uma política de Acesso Condicional. A condição de usuários e grupos é obrigatória em uma política de Acesso Condicional. Em sua política, você pode selecionar **todos os usuários** ou usuários e grupos específicos. Você deve selecionar apenas usuários e grupos devidamente licenciados. Para obter mais informações, consulte [Acesso Condicional: Condições](/azure/active-directory/conditional-access/conditions).

## <a name="advanced-audit"></a>Auditoria Avançada

A Advanced Audit in Microsoft 365 fornece retenção de um ano de logs de auditoria para atividades de usuário e administração e fornece a capacidade de criar políticas personalizadas de retenção de log de auditoria para gerenciar a retenção de log de auditoria para outros serviços Microsoft 365. Também fornece acesso a eventos cruciais para investigações e acesso de alta largura de banda à API de atividade de gerenciamento Office 365. Para obter mais informações, consulte [Auditoria Avançada em Microsoft 365](/microsoft-365/compliance/advanced-audit).

Você também pode habilitar um período de retenção de 10 anos com um SKU adicional. O SKU adicionado será exigido a partir do início de 2021.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Os usuários licenciados de Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance e Microsoft 365 E5/A5/G5 eDiscovery and Audit podem se beneficiar da Auditoria Avançada.

Usuários licenciados com auditoria avançada e o complemento de retenção de log de auditoria de 10 anos podem se beneficiar da retenção de log de auditoria de 10 anos.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam da Auditoria Avançada porque os registros de auditoria relacionados à atividade do usuário em Microsoft 365 serviços podem ser retidos por até um ano. Além disso, eventos de auditoria de alto valor são registrados, como quando os itens na caixa de correio de um usuário são acessados ou lidos. Para obter mais informações, consulte [Auditoria Avançada em Microsoft 365](/microsoft-365/compliance/advanced-audit).

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, a Advanced Audit é habilitada no nível de inquilino para todas as organizações que possuem uma assinatura Office 365 ou Microsoft 365 E5/A5/G5, e fornece automaticamente uma retenção de um ano de logs de auditoria para atividades (realizadas pelos usuários com a licença apropriada) em Azure Active Directory, Exchange e SharePoint. Além disso, as organizações podem usar políticas de retenção de log de auditoria para gerenciar o período de retenção de registros de auditoria gerados pela atividade em outros serviços Microsoft 365. A funcionalidade de retenção de log de auditoria de 10 anos também está habilitada usando as mesmas políticas de retenção. Para saber mais, confira [Gerenciar políticas de retenção de log de auditoria](/microsoft-365/compliance/audit-log-retention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado apenas aos usuários do inquilino que são licenciados para o serviço?

A retenção de um ano de registros de auditoria e a auditoria de eventos cruciais só se aplicam aos usuários com a licença apropriada. Além disso, os administradores podem usar políticas de retenção de log de auditoria para especificar durações de retenção mais curtas para os registros de auditoria de usuários específicos.

A retenção de 10 anos de logs de auditoria só se aplica aos usuários com a licença complementa apropriada. O SKU adicionado será exigido a partir do início de 2021.