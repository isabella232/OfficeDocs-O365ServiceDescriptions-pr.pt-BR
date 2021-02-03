---
title: Diretrizes de licenciamento do Microsoft 365 para conformidade & segurança
ms.author: office365servicedesc
author: pamelaar
ms.reviewer: v-trscho
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Este artigo fornece diretrizes de licenciamento para a conformidade com o Microsoft 365 para ajudar a evitar possíveis interrupções no serviço devido a acesso não licenciado.
ms.openlocfilehash: bceb0f3648aac36f5e748886240ae3594eac7617
ms.sourcegitcommit: bd0cf8920c64e171967d7dd61b7f988bd093c073
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 02/02/2021
ms.locfileid: "50080277"
---
# <a name="microsoft-365-licensing-guidance-for-security--compliance"></a>Diretrizes de licenciamento do Microsoft 365 para conformidade & segurança

Para os fins deste artigo, um serviço no nível do locatário é um serviço online que, quando adquirido para qualquer usuário no locatário (autônomo ou como parte dos planos do &mdash; Office 365 ou microsoft 365) é ativado em parte ou totalmente para todos os usuários no locatário. &mdash; Embora alguns usuários não autorizados possam acessar tecnicamente o serviço, é necessária uma licença para qualquer usuário que você pretenda beneficiar do serviço.

> [!NOTE]
> Alguns serviços de locatário atualmente não são capazes de limitar benefícios a usuários específicos. Esforços devem ser feitos para limitar os benefícios do serviço aos usuários licenciados. Isso ajudará a evitar possíveis interrupções de serviço em sua organização quando os recursos de direcionamento estão disponíveis.

Para ver as opções de licenciamento para que seus usuários se beneficiem dos recursos de conformidade do Microsoft 365 a partir de 1º de abril de 2020, baixe a Comparação detalhada de licenciamento de conformidade do Microsoft 365. [(PDF)](https://www.microsoft.com/download/details.aspx?id=102403)  |  [(Excel)](https://www.microsoft.com/download/details.aspx?id=102427)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

O Azure Active Directory Identity Protection é um recurso do plano Azure Active Directory Premium P2 que permite detectar possíveis vulnerabilidades que afetam as identidades da sua organização, configurar respostas automatizadas para ações suspeitas detectadas relacionadas às identidades da sua organização e investigar incidentes suspeitos e tomar as medidas apropriadas para resolvê-los.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os analistas e profissionais de segurança da SecOps se beneficiam de ter visualizações consolidadas de usuários sinalizados e eventos de risco com base em algoritmos de aprendizado de máquina. Os usuários finais se beneficiam da proteção automática fornecida por meio do Acesso Condicional baseado em risco e da segurança aprimorada fornecida por meio da ação de vulnerabilidades.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para que um usuário se beneficie do serviço?

O Enterprise Mobility + Security E5/A5, o Microsoft 365 E5/A5, o Microsoft 365 E5/A5 Security e o Azure Active Directory Premium Plano 2 fornecem os direitos para que um usuário se beneficie do Azure Active Directory Identity Protection.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos do Azure AD Identity Protection estão habilitados no nível do locatário para todos os usuários no locatário. Para saber mais sobre o Azure AD Identity Protection, confira [O que é a Proteção de Identidade?](https://docs.microsoft.com/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os administradores podem definir o escopo do Azure AD Identity Protection atribuindo políticas de risco que definem o nível de redefinições de senha e permitindo o acesso somente a usuários licenciados. Para obter instruções sobre como definir o escopo de implantações do Azure AD Identity Protection, consulte Como configurar e [habilitar políticas de risco.](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy)

## <a name="azure-active-directory-identity-governance"></a>Governança de Identidade do Azure Active Directory

O Azure Active Directory Identity Governance permite equilibrar a necessidade de segurança e produtividade dos funcionários da sua organização com os processos e visibilidade corretos. Ele usa gerenciamento de direitos, revisões de acesso, gerenciamento de identidade privilegiada e políticas de termos de uso para garantir que as pessoas certas tenham o acesso certo aos recursos certos.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

O Azure Active Directory Identity Governance aumenta a produtividade dos usuários, facilitando a solicitação de acesso a aplicativos, grupos e Microsoft Teams em um pacote de acesso. Os usuários também podem ser configurados como aprovadores, sem envolver administradores. Para revisões de acesso, os usuários podem revisar associações de grupos com recomendações inteligentes para agir em intervalos regulares.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para que um usuário se beneficie do serviço?

O Enterprise Mobility + Security E5/A5, o Microsoft 365 E5/A5, o Microsoft 365 E5/A5 Security e o Azure Active Directory Premium Plano 2 fornecem os direitos para que um usuário se beneficie do Azure Active Directory Identity Governance.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Os recursos de Governança de Identidade do Azure AD estão habilitados no nível do locatário, mas implementados por usuário. Para saber mais sobre o Azure AD Identity Governance, confira [O que é o Azure AD Identity Governance?](https://docs.microsoft.com/azure/active-directory/governance/identity-governance-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os administradores podem analisar o Azure AD Identity Governance atribuindo pacotes de acesso, revisões de acesso ou gerenciamento de identidade privilegiada somente para usuários licenciados. Para obter instruções sobre como escopo das implantações do Azure AD Identity Governance, confira:

- [Requisitos de licença de gerenciamento de direitos do Azure AD](https://docs.microsoft.com/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Requisitos de licença de revisão de acesso do Azure AD](https://docs.microsoft.com/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [Requisitos de licença para usar o Privileged Identity Management](https://docs.microsoft.com/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="microsoft-defender-for-identity"></a>Microsoft Defender para Identidade?

O Microsoft Defender for Identity (anteriormente Azure Advanced Threat Protection) é um serviço de nuvem que ajuda a proteger ambientes híbridos corporativos contra vários tipos de ataques cibernéticos direcionados avançados e ameaças internas.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os analistas e profissionais de segurança da SecOp se beneficiam da capacidade do Microsoft Defender for Identity de detectar e investigar ameaças avançadas, identidades comprometidas e ações internas mal-intencionadas. Os usuários finais se beneficiam por terem seus dados monitorados pelo Microsoft Defender for Identity.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para que um usuário se beneficie do serviço?

O Enterprise Mobility + Security E5/A5, o Microsoft 365 E5/A5, o Microsoft 365 E5/A5 Security e o Microsoft Defender for Identity para Usuários fornecem os direitos de benefício do Microsoft Defender para Identidade.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos do Microsoft Defender para Identidade estão habilitados no nível do locatário para todos os usuários no locatário. Para obter informações sobre como configurar a ATP do Azure, consulte [Criar o Microsoft Defender para a instância de identidade.](https://docs.microsoft.com/defender-for-identity/install-step1)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

No momento, o Microsoft Defender para serviços de identidade não é capaz de limitar recursos a usuários específicos. Você deve licenciar todos os usuários que pretende beneficiar.

## <a name="microsoft-defender-for-office-365"></a>Microsoft Defender para Office 365

O Microsoft Defender para Office 365 (antigo Proteção Avançada contra Ameaças do Office 365) ajuda a proteger as organizações contra ataques sofisticados, como phishing e malware de dia zero. O Microsoft Defender para Office 365 também fornece informações ativas correlacionando sinais de uma ampla variedade de dados para ajudar a identificar, priorizar e fornecer recomendações sobre como lidar com possíveis ameaças.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

O Microsoft Defender para Office 365 protege os usuários contra ataques sofisticados, como phishing e malware de dia zero. Para ver a lista completa de serviços fornecidos no Plano 1 e no Plano 2, confira [o Microsoft Defender para Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp)

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para que um usuário se beneficie do serviço? 

O Microsoft Defender para Office 365 Planos 1 e 2, o Office 365 E5/A5/G5, o Microsoft 365 E5/A5/G5, o Microsoft 365 E5/A5/G5 Security e o Microsoft 365 Business Premium fornecem os direitos para que um usuário se beneficie do Microsoft Defender para Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos do Microsoft Defender para Office 365 estão habilitados no nível do locatário para todos os usuários no locatário. Para obter informações sobre como configurar as políticas do Microsoft Defender para Office 365 para usuários licenciados, consulte [o Microsoft Defender para Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Para escopo do Microsoft Defender para Office 365, siga as políticas de implantação links seguros e anexos seguros:

- Para obter informações sobre como configurar Links seguros para usuários licenciados, consulte Links seguros [no Microsoft Defender para Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)

- Para obter informações sobre como configurar Anexos Seguros para usuários licenciados, consulte Anexos seguros no [Microsoft Defender para Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments)

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

O OCAS (Office 365 Cloud App Security) é um subconjunto do Microsoft Cloud App Security, com recursos limitados ao Office 365 e sem segurança adicional para aplicativos de nuvem de terceiros e serviços IaaS.

O OCAS dá às organizações visibilidade de seus serviços e aplicativos de nuvem de produtividade, fornece análises sofisticadas para identificar e combater ameaças cibernéticas e permite que elas controlem como os dados viajam pelo &mdash; Office 365.

Para comparar recursos, consulte Diferenças entre o Microsoft Cloud App Security e o [Office 365 Cloud App Security.](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365)

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

O OCAS descobre o Shadow IT, fornece proteção contra ameaças no Office 365 e pode controlar quais aplicativos têm permissão para acessar dados.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para que um usuário se beneficie do serviço?

O Office 365 E5/A3/A5/G5 fornece os direitos para que um usuário se beneficie do OCAS.
Para obter mais informações, consulte a Folha de Dados de Licenciamento do [Microsoft Cloud App Security.](https://www.aka.ms/mcaslicensing)

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos do OCAS são habilitados no nível do locatário para todos os usuários no locatário.

Para obter informações sobre como configurar o serviço, consulte [Configuração básica para o Cloud App Security](https://docs.microsoft.com/cloud-app-security/general-setup).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os administradores podem criar escopos de implantações do OCAS para impor como determinados aplicativos são acessados e limitar os grupos de usuários monitorados pelo Office 365 Cloud App Security. Para obter mais informações, consulte [Implantação com escopo.](https://docs.microsoft.com/cloud-app-security/scoped-deployment)

## <a name="microsoft-cloud-app-security"></a>Segurança no aplicativo na nuvem da Microsoft

O Microsoft Cloud App Security (MCAS) é uma solução CASB (Agente de Segurança de Acesso à Nuvem) que dá às organizações visibilidade de seus aplicativos e serviços em nuvem, fornece análises sofisticadas para identificar e combater ameaças cibernéticas e permite que elas controlem como os dados viajam em qualquer aplicativo de &mdash; nuvem.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

O MCAS descobre e avalia a SOMBRA DE IT, fornece proteção contra ameaças em aplicativos de nuvem de terceiros e em aplicativos de nuvem de terceiros e protege as informações em aplicativos de nuvem de terceiros e primeiro.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para que um usuário se beneficie do serviço?

MCAS, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security, Microsoft 365 E5/A5/G5 Compliance e Microsoft 365 Information Protection and Governance fornecem os direitos para um usuário se beneficiar do MCAS.

O Azure AD P1 fornece os direitos para que um usuário se beneficie dos recursos de Descoberta no MCAS.

Para se beneficiar dos recursos de Controle de Aplicativo de Acesso Condicional no MCAS, os usuários também devem estar licenciados para o Azure Active Directory P1, que está incluído no Enterprise Mobility + Security E3/A3/G3, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E3/A3/G3, Microsoft 365 E5/A5/G5 e Microsoft 365 E5/A5/G5 Security.

Para se beneficiar da rotulagem automática do lado do cliente, os usuários devem estar licenciados para a Proteção de Informações do Azure P2, incluída no Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance e Microsoft 365 Information Protection and Governance.

> [!NOTE]
> A rotulagem automática do lado do servidor requer Proteção de Informações para o Office 365 – licenças Premium ( `MIP_S_CLP2` ou `efb0351d-3b08-4503-993d-383af8de41e3` ). Para referência, consulte [Nomes de produtos e identificadores de plano de serviço para licenciamento.](https://docs.microsoft.com/azure/active-directory/enterprise-users/licensing-service-plan-reference)

Para obter mais informações, consulte a Folha de Dados de Licenciamento do [Microsoft Cloud App Security.](https://www.aka.ms/mcaslicensing)

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos do MCAS são habilitados no nível do locatário para todos os usuários no locatário.

Para obter informações sobre como configurar as políticas do Microsoft Cloud App Security para usuários licenciados, consulte [a visão geral do Microsoft Cloud App Security.](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os administradores podem criar um escopo de implantações MCAS para usuários licenciados usando os recursos de implantação com escopo disponíveis no serviço. Para obter mais informações, consulte [Implantação com escopo.](https://docs.microsoft.com/cloud-app-security/scoped-deployment)

## <a name="compliance-manager"></a>Gerenciador de Conformidade

Simplifique a conformidade e reduza os riscos com o Gerenciador de Conformidade. O Gerenciador de Conformidade ajuda as organizações a atender aos requisitos de regulamentos, padrões, políticas da empresa ou outras estruturas de controle desejadas.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

A seguir estão os benefícios para os usuários do serviço gerenciador de conformidade:

- Converte regulamentos, padrões, políticas da empresa ou outras estruturas de controle desejadas para um idioma simples
- Fornece acesso a uma grande biblioteca de avaliações e avaliações personalizadas para atender às necessidades exclusivas de conformidade
- Mapeia controles regulatórios para ações de melhoria recomendadas
- Fornece orientações passo a passo sobre como implementar as soluções para atender aos requisitos regulatórios
- Ajuda os usuários a priorizar ações que terão o maior impacto em sua conformidade organizacional associando uma pontuação a cada ação

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para que um usuário se beneficie do serviço?

Os clientes com licenças E1 e E3 poderão acessar apenas a avaliação padrão da Linha de Base de Proteção de Dados. Os clientes com licenças do Office 365 E5/A5 e do Microsoft 365 E5/A5 (Conformidade, Governança de Proteção de Informações e Descoberta Eletrônica e SKUs de Auditoria incluídas) poderão acessar as avaliações de Linha de Base de Proteção de &amp; Dados, RGPD, NIST 800-53 e ISO 27001. O recurso de avaliação personalizada e as avaliações premium são reservados para clientes do Office 365 E5/A5 e microsoft 365 E5/A5. As avaliações premium estarão disponíveis para compra durante o primeiro semestre de 2021 por meio de VL, CSP e WebDirect. 

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

O Gerenciador de Conformidade é provisionado por padrão para seu locatário. Os administradores configuram permissões de usuário e atribuem funções para que usuários não administradores em sua organização possam começar a usar o Gerenciador de Conformidade. Para saber mais, confira [Começar a trabalhar com o Gerenciador de Conformidade: definir permissões de usuário e atribuir funções.](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

O acesso ao Gerenciador de Conformidade é controlado pela definição de permissões do usuário e pela atribuição de funções. Para obter mais informações, [consulte Começar a trabalhar com o Gerenciador de Conformidade: definir permissões de usuário e atribuir funções.](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles)

## <a name="microsoft-defender-for-endpoint"></a>Proteção Avançada contra Ameaças do Microsoft Defender

O Microsoft Defender for Endpoint (antigo Microsoft Defender ATP) é uma solução de segurança de ponto de extremidade que inclui avaliação e gerenciamento de vulnerabilidades baseadas em risco; recursos de redução de superfície de ataque; proteção de última geração baseada em comportamento e baseada em nuvem; detecção e resposta de ponto de extremidade (EDR); investigação e correção automáticas; e serviços de busca gerenciados. Confira [a página Do Microsoft Defender para Pontos de](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) Extremidade para saber mais.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Os usuários licenciados do Windows 10 Enterprise E5, do Windows 10 Education A5, do Microsoft 365 E5 (M365 E5), que inclui o Windows 10 Enterprise E5, o Microsoft 365 E5 Security, o Microsoft 365 A5 (M365 A5) podem se beneficiar do Microsoft Defender para o Ponto de Extremidade.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os analistas e profissionais de segurança da SecOps se beneficiam dos recursos de segurança de ponto de extremidade do Microsoft Defender for Endpoint para fazer proteção preventiva, detecção pós-violação, investigação automatizada e resposta a ameaças avançadas. Os usuários finais se beneficiam com eventos mal-intencionados monitorados pelo Microsoft Defender para o Ponto de Extremidade.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos do Microsoft Defender para Ponto de Extremidade estão habilitados no nível do locatário para todos os usuários no locatário. Para obter informações sobre implantação, consulte [Fases de implantação.](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/deployment-phases)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os administradores do Microsoft Defender para Pontos de Extremidade podem usar o controle de acesso baseado em função (RBAC) para criar funções e grupos dentro da equipe de operações de segurança para conceder o acesso apropriado à Central de Segurança do Microsoft Defender. Para obter mais informações, consulte [Gerenciar o acesso ao portal usando o controle de acesso baseado em função.](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/rbac)

## <a name="information-protection"></a>Proteção de Informações

A Proteção de Informações ajuda as organizações a descobrir, classificar, rotular e proteger emails e documentos confidenciais. Os administradores podem definir regras e condições para aplicar rótulos automaticamente, os usuários podem aplicar rótulos manualmente ou uma combinação dos dois pode ser usada— onde os usuários receberem recomendações sobre a aplicação de rótulos.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam com a capacidade de aplicar manualmente rótulos de confidencialidade ao seu conteúdo ou ao classificar automaticamente o conteúdo.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para que um usuário se beneficie do serviço?

O Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, Office 365 E5/A5/E3/A3/F3, AIP Plan 1 e AIP Plan 2 oferecem direitos para que um usuário se beneficie da rotulagem de sensibilidade manual.

O Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, AIP Plan 1 e AIP Plan 2 fornecem os direitos para que um usuário se beneficie da aplicação e da exibição de rótulos de sensibilidade no Power BI e para proteger dados quando exportados do Power BI para Excel, PowerPoint ou PDF. 

> [!NOTE]
> O Power BI está incluído no Microsoft 365 E5/A5/G5; em todos os outros planos, o Power BI deve ser licenciado separadamente.

O Microsoft 365 E5/A5/G5, a conformidade com o Microsoft 365 E5/A5/G5, a Proteção de Informações do Microsoft 365 e Governança, o Office 365 E5, a Conformidade Avançada do Office 365, o Enterprise Mobility + Security E5 e o Plano 2 do AIP oferecem os direitos para que um usuário se beneficie da rotulagem de sensibilidade automática.

Para direitos específicos por licença, confira a Comparação detalhada de licenciamento de conformidade do Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx) Não inclui direitos de classificação automática com base no Aprendizado de Máquina (classificadores de treinamento).

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos de proteção de informações são habilitados no nível do locatário para todos os usuários no locatário. Para obter informações sobre como configurar políticas para usuários licenciados, consulte Ativando o Azure Rights Management.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Exceto ao usar o recurso de scanner do AIP, as políticas podem ter escopo para grupos ou usuários específicos e os registros podem ser editados para impedir que usuários não licenças executam recursos de classificação ou rotulagem. Para obter instruções sobre como escopo de implantações do AIP, consulte Configurando a política de Proteção de [Informações do Azure.](https://docs.microsoft.com/azure/information-protection/configure-policy)

Para o recurso de scanner do AIP, a Microsoft não se compromete a fornecer recursos de classificação, rotulagem ou proteção de arquivos para usuários que não estão licenciados.

## <a name="information-governance"></a>Governança de Informações

A Governança de Informações ajuda as organizações a gerenciar seus riscos por meio da descoberta, classificação, rotulação e controle de seus dados. A Governança de Informações permite que as organizações atendem aos requisitos regulatórios e comerciais, além de reduzir sua superfície de ataque, fornecendo recursos de retenção e exclusão em seus dados do Microsoft 365 e de terceiros.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam com a capacidade de classificar dados para fins de retenção para preservar políticas e regulamentos específicos.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para que um usuário se beneficie do serviço?

Os planos do Microsoft 365 F3/Business Premium, Office 365 E1/A1/F3 e Autônomo do Exchange fornecem direitos para que um usuário se beneficie da aplicação manual de rótulos de retenção sem registro aos dados da caixa de correio.

O Microsoft 365 F3/F1/Business Premium, o Office 365 E1/A1/F3 e os planos autônomos do SharePoint fornecem direitos para que um usuário se beneficie da aplicação manual de rótulos de retenção sem registro a arquivos no SharePoint ou no OneDrive. 

O Microsoft 365 E5/A5/E3/A3/Business Premium, Office 365 E5/A5/E3/A3, Exchange Plan 2 e Arquivamento do Exchange Online fornecem os direitos para que um usuário se beneficie de uma política básica de retenção de caixa de correio em toda a organização ou de todo o local e/ou aplique manualmente uma rotulagem de retenção sem registro aos dados da caixa de correio.

O Microsoft 365 E5/A5/E3/A3, o Office 365 E5/A5/E3/A3 e o SharePoint Plan 2 fornecem os direitos para que um usuário se beneficie de uma política de retenção básica do SharePoint ou do OneDrive e/ou aplique manualmente um rótulo de retenção sem registro a arquivos no SharePoint ou no OneDrive.

O Microsoft 365 E5/A5/E3/A3 e o Office 365 E5/A5/E3/A3 fornecem os direitos para que um usuário se beneficie de uma política de retenção do Teams.

Microsoft 365 E5/A5, Conformidade com o Microsoft 365 E5/A5, Proteção e Governança de Informações do Microsoft 365, O Office 365 E5/A5 e a Conformidade Avançada do Office 365 fornecem os direitos para que um usuário se beneficie automaticamente da aplicação automática de rótulos ou políticas de retenção, da aplicação de rótulos ou políticas de retenção padrão, do início do período de retenção de um rótulo com base em um evento personalizado, do acionamento de uma revisão de disposição manual no final do período de retenção do rótulo, da importação de dados de terceiros por meio de conectores de dados nativos, declaração de um arquivo de registro, descoberta de conteúdo rotulado e monitoramento da atividade de rotulação.

O Microsoft 365 E5/A5, a conformidade com o Microsoft 365 E5/A5, a Proteção de Informações do Microsoft 365 e a Governança fornecem direitos para que um usuário se beneficie da aplicação automática de rótulos de retenção com base em classificadores de treinamento.

Para direitos específicos por licença, confira a Comparação detalhada de licenciamento de conformidade do Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos de Governança de Informações estão habilitados no nível do locatário para todos os usuários no locatário. Para obter informações sobre como configurar a Governança de Informações para aplicar rótulo automático e políticas para usuários licenciados, consulte [Microsoft Information Governance no Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os recursos de Governança de Informações podem ser aplicados a usuários licenciados em locais específicos (sites de equipe, sites de grupo etc.). Para obter informações sobre como configurar a Governança de Informações para aplicar rótulo automático e políticas para usuários licenciados, consulte [Microsoft Information Governance no Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance).

## <a name="records-management"></a>Gerenciamento de Registros

O Gerenciamento de Registros ajuda as organizações a cumprir suas obrigações de manutenção de registros comerciais e regulatórias por meio de descoberta, classificação, rotulagem, retenção e recursos de exclusão defensável em seus dados do Microsoft 365 e de terceiros.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para que um usuário se beneficie do serviço?

Microsoft 365 E5/A5/G5, A Conformidade do Microsoft 365 E5/A5/G5, a Governança e Proteção de Informações do Microsoft 365, o Office 365 E5/A5/G5, a Conformidade Avançada do Office 365 fornecem os direitos para que um usuário se beneficie do Gerenciamento de Registros, incluindo declarar itens como registros ou registros regulamentares, aplicar automaticamente rótulos de retenção ou registros e executar processos de revisão de disposição (excluindo automaticamente a aplicação de um rótulo de retenção com base em classificadores de treinamento).

O Microsoft 365 E5/A5, a conformidade com o Microsoft 365 E5/A5 e a Proteção de Informações e Governança do Microsoft 365 fornecem direitos para que um usuário se beneficie da aplicação automática de rótulos de retenção ou registro com base em classificadores de treinamento.

Para direitos específicos por licença, confira a Comparação detalhada de licenciamento de conformidade do Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam com a capacidade de declarar o conteúdo como registro e gerenciar o processo de registros completos a partir da definição e declaração da política por meio do descarte desfensável.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos de Gerenciamento de Registros são habilitados no nível do locatário para todos os usuários no locatário. Para obter informações sobre como configurar o Gerenciamento de Registros a ser aplicado a usuários licenciados, consulte Saiba mais sobre o Gerenciamento de [Registros no Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/records-management)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os recursos de Gerenciamento de Registros podem ser aplicados a usuários licenciados em locais específicos (sites de equipe, sites de grupo etc.). Para obter informações sobre como configurar o Gerenciamento de Registros a ser aplicado a usuários licenciados, consulte Saiba mais sobre o Gerenciamento de [Registros no Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/records-management)

## <a name="data-connectors"></a>Conectores de dados 

A Microsoft fornece conectores de dados de terceiros que podem ser configurados no centro de conformidade do Microsoft 365. Para uma lista de conectores de dados fornecidos pela Microsoft, consulte a [tabela conectores de dados de](https://docs.microsoft.com/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) terceiros. Esta tabela também resume as soluções de conformidade que você pode aplicar a dados de terceiros depois de importar e arquivar dados no Microsoft 365 e links para as instruções passo a passo para cada conector.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

A principal vantagem de usar conectores de dados para importar e arquivar dados de terceiros no Microsoft 365 é que você pode aplicar várias soluções de conformidade do Microsoft 365 aos dados depois que eles são importados. Isso ajuda a garantir que os dados que não são da Microsoft da sua organização estão em conformidade com os regulamentos e padrões que afetam sua organização.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para que um usuário se beneficie do serviço?

As licenças a seguir fornecem os direitos para que um usuário se beneficie dos Conectores de Dados:

- Microsoft 365 E5/A5
- Microsoft 365 E5/A5 Proteção e Governança da Informação
- Conformidade Microsoft 365 E5/A5
- Gerenciamento de riscos insider do Microsoft 365 E5/A5
- Descoberta e Auditoria do Microsoft 365 E5/A5
- Office 365 E5/A5
- Conformidade Avançada do Office 365

Para conectores de dados no Centro de Conformidade e Segurança & do M365 que são fornecidos por um parceiro da Microsoft, sua organização precisará de um relacionamento comercial com o parceiro antes de implantar esses conectores.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Os conectores são configurados usando o Centro de & segurança e o Catálogo de Conectores.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os serviços de Conectores de Dados são um valor no nível do locatário. Todos os usuários destinados a se beneficiar desse serviço devem ser licenciados.

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp"></a>APIs do Microsoft Graph para DLP (Prevenção contra Perda de Dados) do Teams

No início deste ano, [anunciamos a visualização pública da API de](https://go.microsoft.com/fwlink/?linkid=2143888)Notificação de Alteração do Microsoft Graph para mensagens no Teams. Essa API permite que os desenvolvedores criem aplicativos que podem ouvir as mensagens do Microsoft Teams quase em tempo real e habilitar implementações de cenário de DLP para clientes e ISVs. Além disso, a API de Patch do Microsoft Graph permite a aplicação de ações DLP às mensagens do Teams.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os recursos de prevenção contra perda de dados [(DLP)](https://docs.microsoft.com/microsoft-365/compliance/dlp-microsoft-teams) são amplamente usados no Microsoft Teams, especialmente quando as organizações mudaram para o trabalho remoto. Se sua organização tiver DLP, agora você pode definir políticas que impedem que as pessoas compartilhem informações confidenciais em um canal ou sessão de chat do Microsoft Teams.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para que um usuário se beneficie do serviço?

Você precisará de uma das seguintes licenças do E5 para obter suporte para proteção de DLP no Chat do Teams:

- Microsoft 365 E5/A5
- Conformidade Microsoft 365 E5/A5
- Governança e proteção de informações do Microsoft 365 E5/A5
- Office 365 E5/A5 

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

O acesso à API é configurado no nível do locatário.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

A API do Microsoft Graph para DLP do Teams é um valor no nível do locatário. Todos os usuários destinados a se beneficiar desse serviço devem ser licenciados.

## <a name="ediscovery"></a>Descoberta eletrônica

A Descoberta EDiscovery oferece soluções de investigação e Descobertas De eDiscovery para departamentos de TI e jurídicos dentro de corporações para identificar, coletar, preservar, reduzir e analisar conteúdo relacionado a uma investigação ou litígio antes de exportar o sistema do Microsoft 365.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Um usuário se beneficia da Descoberta Eletrônica Avançada quando o usuário é selecionado como um custodiante de dados (uma pessoa com controle administrativo de um documento ou arquivo eletrônico) para uma ocorrência.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para que um usuário se beneficie do serviço?

O Microsoft 365 E5/A5/G5/E3/A3/G3, Office 365 E5/A5/G5/E3/A3/G3 e Office 365 Advanced Compliance fornecem os direitos para que um usuário se beneficie da Descoberta Principal.

A Conformidade do Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Descoberta e Auditoria do Microsoft 365 E5/A5, Office 365 E5/A5/G5 e Conformidade Avançada do Office 365 fornecem os direitos para que um usuário se beneficie da Descoberta Avançada.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos avançados de Descoberta eDiscovery são habilitados no nível do locatário para todos os usuários no locatário quando os administradores atribuem permissões de Descoberta eDiscovery no Centro de Conformidade e Segurança &.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os administradores de Descobertas Do EDiscovery podem selecionar usuários específicos como custodiantes de dados para uma ocorrência usando a ferramenta de gerenciamento custodiante interna na Descoberta Avançada, conforme descrito em Adicionar [custodiantes](https://docs.microsoft.com/microsoft-365/compliance/add-custodians-to-case)a um caso de Descoberta Bancária Avançada.

## <a name="office-365-customer-key"></a>Chave do Cliente do Office 365

Com a Chave do Cliente, você controla as chaves de criptografia da sua organização e configura o Office 365 para usá-las para criptografar seus dados em repouso nos data centers da Microsoft. Em outras palavras, a Chave do Cliente permite adicionar uma camada de criptografia que pertence a você, usando suas próprias chaves. Os dados em repouso incluem dados do Exchange Online e do Skype for Business armazenados em caixas de correio e arquivos no SharePoint Online e no OneDrive for Business.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam da Chave do Cliente com seus dados em repouso criptografados na camada do aplicativo usando chaves de criptografia fornecidas, controladas e gerenciadas por sua própria organização.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para que um usuário se beneficie do serviço?

O Microsoft 365 E5/A5, a Conformidade do Microsoft 365 E5/A5, a Proteção e Governança de Informações do Microsoft 365, o Office 365 E5/A5 e a Conformidade Avançada do Office 365 fornecem os direitos para que um usuário se beneficie da Chave do Cliente. Para obter o benefício completo da Chave do Cliente, você também deve ter uma assinatura do Azure Key Vault.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

As chaves de criptografia da Chave de Cliente do Office 365 podem ser habilitadas para todos os dados armazenados nas caixas de correio do Exchange Online e do Skype for Business e nos arquivos do SharePoint Online, oneDrive for Business e Teams. Para obter mais informações sobre a Chave de Cliente do Office 365, incluindo como começar, consulte Criptografia de serviço [com Chave de Cliente.](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Para o Exchange Online e o Skype for Business, as caixas de correio podem ser criptografadas usando a Chave do Cliente. Você deve configurar o Azure para poder usar a Chave de Cliente do Office 365. Confira [Configurar a](https://docs.microsoft.com/microsoft-365/compliance/customer-key-set-up) Chave do Cliente para as etapas que você precisa seguir para criar e configurar os recursos necessários do Azure e as etapas para configurar a Chave do Cliente no Office 365. Depois de concluir a configuração do Azure, determine qual política e, portanto, quais chaves atribuir a caixas de correio e arquivos em sua organização. Caixas de correio e arquivos para os quais você não atribui uma política usarão políticas de criptografia controladas e gerenciadas pela Microsoft. Para obter mais informações sobre a Chave do Cliente ou para obter uma visão geral, consulte [Criptografia de serviço com a Chave do Cliente.](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview)

## <a name="office-365-customer-lockbox"></a>Sistema de Proteção de Dados do Cliente do Office 365

O Sistema de Proteção de Dados do Cliente oferece uma camada adicional de controle, oferecendo aos clientes a capacidade de dar autorização explícita de acesso para operações de serviço. Ao demonstrar que os procedimentos estão em uso para autorização explícita de acesso a dados, o Sistema de Proteção de Dados do Cliente também pode ajudar as organizações a cumprir determinadas obrigações de conformidade, como HIPAA e FEDRAMP.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

O Sistema de Bloqueio do Cliente garante que ninguém da Microsoft possa acessar o conteúdo do cliente para executar uma operação de serviço sem a aprovação explícita do cliente. O Sistema de Bloqueio do Cliente traz o cliente para o fluxo de trabalho de aprovação para solicitações de acesso ao conteúdo. Ocasionalmente, os engenheiros da Microsoft estão envolvidos durante o processo de suporte para solucionar e corrigir problemas relatados pelo cliente. Na maioria dos casos, os problemas são corrigidos por meio de ferramentas abrangentes de telemetria e depuração que a Microsoft tem para seus serviços. No entanto, pode haver casos que exigem que um engenheiro da Microsoft acesse o conteúdo do cliente para determinar a causa raiz e corrigir o problema. O Sistema de Bloqueio do Cliente exige que o engenheiro solicite o acesso do cliente como uma etapa final no fluxo de trabalho de aprovação. Isso dá às organizações a opção de aprovar ou negar essas solicitações, o que lhes dá controle direto sobre se um engenheiro da Microsoft pode acessar os dados do usuário final da organização.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para que um usuário se beneficie do serviço?

O Office 365 E5/A5/G5, o Microsoft 365 E5/A5/G5, o Microsoft 365 E5/A5/G5 Compliance, o Gerenciamento de Riscos do Microsoft 365 Insider e a Conformidade Avançada do Office 365 fornecem os direitos para que um usuário se beneficie do Sistema de Bloqueio do Cliente.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Os administradores podem ativar o Sistema de Bloqueio de Clientes no Centro de administração do Microsoft 365. Para saber mais, confira [o Sistema de Bloqueio de Clientes no Office 365.](https://docs.microsoft.com/microsoft-365/compliance/customer-lockbox-requests) Quando o Sistema de Bloqueio do Cliente está ligado, a Microsoft é obrigada a obter a aprovação de uma organização antes de acessar qualquer conteúdo.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Atualmente, o serviço Sistema de Bloqueio do Cliente não pode ser limitado a usuários específicos. Você deve licenciar todos os usuários que pretende beneficiar.

## <a name="privileged-access-management-in-office-365"></a>O Privileged Access Management no Office 365

[O PAM (Privileged Access Management)](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration) fornece controle de acesso granular sobre tarefas de administração privilegiadas no Office 365. Depois de permitir o PAM, para concluir tarefas elevadas e privilegiadas, os usuários precisarão solicitar acesso just-in-time por meio de um fluxo de trabalho de aprovação com escopo altamente delimitado e com limite de tempo.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

A habilitação do PAM permite que as organizações operem com zero privilégios permanentes. Os usuários se beneficiam da camada adicional de defesa contra vulnerabilidades decorrentes do acesso administrativo permanente que fornece acesso não organizado a seus dados.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para que um usuário se beneficie do serviço? 

O Office 365 E5/A5, o Microsoft 365 E5/A5, a Conformidade com o Microsoft 365 E5/A5 e a Governança e Proteção de Informações do Microsoft 365 E5/A5 fornecem os direitos para que um usuário se beneficie do PAM.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos PAM são habilitados no nível do locatário para todos os usuários no locatário. Para obter informações sobre como configurar políticas PAM, consulte [Começar a trabalhar com o gerenciamento de acesso privilegiado.](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os clientes podem gerenciar o PAM por usuário por meio de políticas de acesso e grupo aprovador, que podem ser aplicadas a usuários licenciados. Para saber mais, confira [Gerenciamento de acesso privilegiado no Office 365.](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751)

## <a name="double-key-encryption-for-microsoft-365"></a>Criptografia de Chave Dupla para o Microsoft 365 

A Criptografia de Chave Dupla do Microsoft 365 permite proteger seus dados altamente confidenciais para atender a requisitos especializados e manter o controle total da chave de criptografia. A Criptografia de Chave Dupla usa duas chaves para proteger seus dados, com uma chave em seu controle e a segunda armazenada com segurança pelo Microsoft Azure. Para exibir os dados, você deve ter acesso às duas teclas. Como a Microsoft pode acessar apenas uma chave, sua chave e seus dados não estão disponíveis para a Microsoft, garantindo que você tenha controle total sobre a privacidade e a segurança de seus dados.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam com a Criptografia de Chave Dupla, podendo migrar seus dados criptografados para a nuvem, o que impede o acesso de terceiros, desde que a chave permaneça no controle dos usuários. Os usuários podem proteger e consumir conteúdo criptografado com chave dupla semelhante a qualquer outro conteúdo protegido por rótulo de sensibilidade.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para que um usuário se beneficie do serviço?

O Microsoft 365 E5/A5, a Conformidade do Microsoft 365 E5/A5, a Proteção e Governança de Informações do Microsoft 365, o Office 365 E5/A5 e a Conformidade Avançada do Office 365 fornecem os direitos para que um usuário se beneficie da Criptografia de Chave Dupla.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

A Criptografia de Chave Dupla dá suporte à versão da área de trabalho do Microsoft Office para Windows.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Para atribuir chaves de criptografia a dados em uma organização do Office 365 e/ou Microsoft 365 para usuários licenciados, siga as instruções de implantação da Criptografia de Chave Dupla.

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Prevenção contra perda de dados do Office 365 para Exchange Online, SharePoint Online e OneDrive for Business

Com a prevenção contra perda de dados (DLP) do Office 365 para o Exchange Online, o SharePoint Online e o OneDrive for Business, as organizações podem identificar, monitorar e proteger automaticamente informações confidenciais em emails e arquivos (incluindo arquivos armazenados em repositórios de arquivos do Microsoft Teams).

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam da DLP para o Exchange Online, o SharePoint Online e o OneDrive for Business quando seus emails e arquivos estão sendo inspecionados em busca de informações confidenciais, conforme configurado na política DLP da organização.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para que um usuário se beneficie do serviço?

O Microsoft 365 E3/A3/Business Premium, o Office 365 E3/A3 e a Prevenção contra Perda de Dados do Office 365 fornecem os direitos para que um usuário se beneficie da DLP do Office 365 para Exchange Online, SharePoint Online e OneDrive for Business.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, emails do Exchange Online, sites do SharePoint e contas do OneDrive são locais *habilitados (cargas* de trabalho) para esses recursos de DLP para todos os usuários no locatário. Para obter mais informações sobre como usar políticas de DLP, consulte [Visão geral da prevenção contra perda de dados.](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os administradores podem personalizar locais (cargas de trabalho), usuários incluídos e usuários excluídos no Centro de Conformidade & segurança, em Locais de prevenção contra perda **de**  >  **dados.**

## <a name="communication-data-loss-prevention-for-teams"></a>Prevenção contra perda de dados de comunicação para o Teams

Com a DLP de Comunicação para o Teams, as organizações podem bloquear chats e mensagens de canal que contenham informações confidenciais, como informações financeiras, identificação pessoal de informações, informações relacionadas à saúde ou outras informações confidenciais.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Os usuários licenciados do Office 365 E5/A5, Microsoft 365 E5/A5, Proteção e Governança de Informações do Microsoft 365 e Conformidade Avançada do Office 365 podem se beneficiar da DLP de comunicação para o Teams.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os envios se beneficiam por terem informações confidenciais em suas mensagens de canal e chat de saída inspecionadas em busca de informações confidenciais, conforme configurado na política de DLP da organização.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, as mensagens de chat e canal do Teams são um Local *habilitado (carga* de trabalho) para esses recursos de DLP para todos os usuários dentro do locatário. Para obter mais informações sobre como usar políticas de DLP, consulte [Visão geral da prevenção contra perda de dados.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os administradores podem personalizar locais (cargas de trabalho), usuários incluídos e usuários excluídos no Centro de Conformidade & segurança, em Locais de prevenção contra perda **de**  >  **dados.**

## <a name="information-barriers"></a>Barreiras de informações

Barreiras de informações são políticas que um administrador pode configurar para impedir que indivíduos ou grupos se comuniquem entre si. Isso será útil se, por exemplo, um departamento estiver lidando com informações que não devem ser compartilhadas com outros departamentos ou se um grupo precisar ser impedido de se comunicar com contatos externos. As políticas de barreira de informações também impedem pesquisa e descoberta. Isso significa que, se você tentar se comunicar com alguém com quem não deve se comunicar, não encontrará esse usuário no selador de pessoas.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam dos recursos avançados de conformidade das barreiras de informações quando estão impedidos de se comunicar com outras pessoas. Por exemplo:<br><br>

| Cenário | Quem precisa de uma licença? |
|:------|:------|:------|
| Dois grupos (Grupo 1 e Grupo 2) não podem se comunicar uns com os outros (ou seja, os usuários do Grupo 1 são impedidos de se comunicar com usuários do Grupo 2 e os usuários do Grupo 2 são impedidos de se comunicar com usuários do &nbsp; &nbsp; Grupo &nbsp; &nbsp; &nbsp; &nbsp; 1. | Usuários do Grupo &nbsp; 1 e do Grupo &nbsp; 2 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para que um usuário se beneficie do serviço?

O Microsoft 365 E5/A5, a Conformidade do Microsoft 365 E5/A5, o Gerenciamento de Riscos do Microsoft 365 Insider, o Office 365 E5/A5 e a Conformidade Avançada do Office 365 fornecem os direitos para que um usuário se beneficie das barreiras de informações.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Os administradores criam e gerenciam políticas de barreira de informações usando cmdlets do PowerShell no Centro de Conformidade & Segurança. Os administradores devem ter a função Administrador Global do Microsoft 365 Enterprise, Administrador Global do Office 365 ou Administrador de Conformidade para criar uma política de barreira de informações. Por padrão, essas políticas se aplicam a todos os usuários no locatário. Para saber mais sobre barreiras de informações, confira [Barreiras de informações no Microsoft Teams.](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os administradores podem personalizar locais (cargas de trabalho), usuários incluídos e usuários excluídos no Centro de Conformidade & Segurança. Por exemplo, se todos os usuários são licenciados para o Office 365 E3 e nenhum está licenciado para o Office 365 Advanced Compliance/E5, eles não precisariam criar nenhuma política de barreira de informações para a organização. Para saber mais, confira [Barreiras de informações no Microsoft Teams.](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)

## <a name="office-365-message-encryption"></a>Criptografia de Mensagem do Office 365

Criptografia de Mensagens do Office 365 (OME) é um serviço integrado ao Azure Rights Management (Azure RMS) que permite o envio de emails criptografados para pessoas dentro ou fora da sua organização, independente do endereço de email de destino (Gmail, Yahoo! Email, Outlook.com, etc.).

Para exibir mensagens criptografadas, os destinatários podem obter uma senha avulsa, entrar com uma conta da Microsoft ou com uma conta corporativa ou de estudante associada ao Office 365. Os destinatários também podem enviar respostas criptografadas. Eles não precisam de uma assinatura para exibir mensagens criptografadas ou enviar respostas criptografadas.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os envios de mensagens se beneficiam do controle adicionado sobre emails confidenciais fornecidos pela Criptografia de Mensagens do Office 365.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para que um usuário se beneficie do serviço?

O Microsoft 365 E3/A3, o Office 365 E3/A3 e o Plano 1 de Proteção de Informações do Azure fornecem os direitos para que um usuário se beneficie da Criptografia de Mensagens do Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Os administradores criam e gerenciam políticas de Criptografia de Mensagem do Office 365 no Centro de administração do Exchange em **Regras de fluxo de**  >  **emails.** Por padrão, essas regras se aplicam a todos os usuários no locatário. Para obter mais informações sobre como configurar novos recursos de Criptografia de Mensagens do Office 365, consulte Configurar novos recursos [de Criptografia de Mensagem.](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os administradores devem aplicar regras de fluxo de emails para a Criptografia de Mensagens do Office 365 somente a usuários licenciados. Para obter mais informações sobre como definir regras de fluxo de emails, consulte Definir regras [de fluxo de emails para criptografar mensagens de email.](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)

## <a name="office-365-advanced-message-encryption"></a>Criptografia de Mensagem Avançada do Office 365

A Criptografia Avançada de Mensagens do Office 365 ajuda os clientes a cumprir obrigações de conformidade que exigem controles mais flexíveis sobre destinatários externos e seu acesso a emails criptografados. Com a Criptografia Avançada de Mensagens, os administradores podem controlar emails confidenciais compartilhados fora da organização usando políticas automáticas que podem detectar tipos de informações confidenciais (por exemplo, informações de identificação pessoal ou IDs financeiras ou de saúde) ou podem usar palavras-chave para aprimorar a proteção aplicando modelos de email personalizados e expirando o acesso a emails criptografados por meio de um portal da Web seguro. Além disso, os administradores podem controlar ainda mais os emails criptografados acessados externamente por meio de um portal da Web seguro revogando o acesso a qualquer momento.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os envios de mensagens se beneficiam do controle adicionado sobre emails confidenciais fornecidos pela Criptografia Avançada de Mensagens.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para que um usuário se beneficie do serviço?

O Office 365 E5/A5, o Microsoft 365 E5/A5, a conformidade com o Microsoft 365 E5/A5, a Proteção e Governança de Informações do Microsoft 365 e a Conformidade Avançada do Office 365 fornecem os direitos para que um usuário se beneficie da Criptografia Avançada de Mensagens.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Os administradores criam e gerenciam políticas de Criptografia de Mensagens Avançadas no Centro de administração do Exchange em **Regras de fluxo de**  >  **emails.** Por padrão, essas regras se aplicam a todos os usuários no locatário. Para obter mais informações sobre como configurar novos recursos de Criptografia de Mensagem, consulte Configurar novos recursos de Criptografia de Mensagem do [Office 365.](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os administradores devem aplicar regras de fluxo de emails para a Criptografia Avançada de Mensagens somente a usuários licenciados. Para obter mais informações sobre como definir regras de fluxo de emails, consulte Definir regras de fluxo de [emails para criptografar mensagens de email no Office 365.](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)

## <a name="communication-compliance"></a>Conformidade em comunicações

A conformidade de comunicação no Microsoft 365 ajuda a minimizar os riscos de comunicação, ajudando você a detectar, capturar e realizar ações de correção para mensagens inadequadas em sua organização. Você pode definir políticas específicas que capturam emails internos e externos, Microsoft Teams ou comunicações de terceiros em sua organização. Os revisadores podem tomar as ações de correção apropriadas para garantir que eles estão em conformidade com os padrões de mensagens da sua organização.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os especialistas em conformidade se beneficiam do serviço, fazendo com que as comunicações da organização seja monitoradas pelas políticas de conformidade de comunicação.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para que um usuário se beneficie do serviço?

O Office 365 E5/A5, o Microsoft 365 E5/A5, o Microsoft 365 E5/A5 Compliance e o Microsoft 365 Insider Risk Management fornecem os direitos para que um usuário se beneficie da conformidade de comunicação.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Administradores e especialistas em conformidade criam políticas de conformidade de comunicação no centro de conformidade do Microsoft 365. Essas políticas definem quais comunicações e usuários estão sujeitos à revisão na organização, definem condições personalizadas que as comunicações devem atender e especificam quem deve realizar as revisões.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Os administradores escolhem usuários ou grupos específicos para incluir em uma política de conformidade de comunicação. Ao escolher um grupo, eles também podem selecionar usuários específicos no grupo para excluir da política de conformidade de comunicação. Para obter mais informações sobre políticas de conformidade de comunicação, confira [Começar a conformidade de comunicação no Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/communication-compliance-configure)

## <a name="insider-risk-management"></a>Gerenciamento de riscos internos

O gerenciamento de riscos internos é uma solução no Microsoft 365 que ajuda a minimizar os riscos internos, ao permitir que você detecte, investigue e tome medidas em atividades arriscadas em sua organização.

As políticas personalizadas permitem que você detecte e tome medidas em atividades mal-intencionadas e inadvertidamente arriscadas em sua organização, incluindo o escalonamento de casos para a Descoberta Avançada da Microsoft, se necessário. Os analistas de risco em sua organização podem tomar rapidamente as medidas apropriadas para garantir que os usuários sejam compatíveis com os padrões de conformidade da sua organização.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam por terem suas atividades monitoradas em busca de risco.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para que um usuário se beneficie do serviço?

O Microsoft 365 E5/A5, a conformidade com o Microsoft 365 E5/A5 e o Gerenciamento de Riscos Insider do Microsoft 365 fornecem os direitos para que um usuário se beneficie do Gerenciamento de Riscos Do Insider.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

As políticas de Gerenciamento de Riscos Insider devem ser criadas no centro de conformidade do Microsoft 365 e atribuídas aos usuários.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Ao criar uma política no centro de conformidade  do Microsoft 365, na página Escolher usuários e grupos, selecione Escolher usuários ou  grupos para selecionar somente usuários licenciados ou, se todos os seus usuários estão licenciados, você pode marcar a caixa de seleção Todos os usuários e grupos habilitados para email.  Para obter mais informações, [consulte Começar a trabalhar com o gerenciamento de riscos insider.](https://docs.microsoft.com/microsoft-365/compliance/insider-risk-management-configure)

## <a name="conditional-access-policies"></a>Políticas de Acesso Condicional

O Acesso Condicional é a ferramenta usada pelo Azure Active Directory para reunir sinais, tomar decisões e impor políticas organizacionais. O Acesso Condicional está no centro do controle controlado por identidade. As políticas de Acesso Condicional, em suas instruções mais simples, são instruções if-then. Se um usuário quiser acessar um recurso, ele deverá concluir uma ação. Exemplo: um gerente de folha de pagamento deseja acessar o aplicativo de folha de pagamento e é necessário para executar a autenticação multifa factor para acessá-lo.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Os usuários licenciados do Enterprise Mobility + Security E3/A3, Do Microsoft 365 F3/E3/A3/Business Premium e do Azure Active Directory Premium Plano 1 podem se beneficiar das políticas de Acesso Condicional. Os usuários licenciados do Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5, Microsoft E5 Security e Azure Active Directory Premium Plano 2 podem se beneficiar da Proteção de Identidade (políticas de Acesso Condicional baseadas em risco).

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Analistas de operações de segurança e profissionais de segurança se beneficiam com a capacidade de impor políticas organizacionais aos usuários, exigindo que eles atendem a determinados critérios antes de conceder acesso ao conteúdo corporativo. Os usuários finais se beneficiam com a capacidade de acessar seu trabalho onde quer que eles escolham, ao mesmo tempo em que protegem os ativos da organização.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos de Acesso Condicional são habilitados no nível do locatário para todos os usuários no locatário.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

Especificamente para a Proteção de Identidade e o Acesso Condicional, um usuário deve ser incluído em um Grupo ou ser adicionado a uma política de Acesso Condicional. A condição de usuários e grupos é obrigatória em uma política de Acesso Condicional. Em sua política, você pode selecionar todos **os usuários ou** usuários e grupos específicos. Você deve selecionar apenas usuários e grupos licenciados adequadamente. Para obter mais informações, [consulte Acesso Condicional: Condições.](https://docs.microsoft.com/azure/active-directory/conditional-access/conditions)

## <a name="advanced-audit"></a>Auditoria Avançada

A Auditoria Avançada no Microsoft 365 oferece retenção de um ano de logs de auditoria para atividades de usuários e administradores e oferece a capacidade de criar políticas de retenção de log de auditoria personalizadas para gerenciar a retenção de log de auditoria para outros serviços do Microsoft 365. Ele também fornece acesso a eventos cruciais para investigações e acesso de alta largura de banda à API da Atividade de Gerenciamento do Office 365. Para saber mais, confira [Auditoria Avançada no Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit)

Você também pode habilitar um período de retenção de 10 anos com uma SKU de complemento. A SKU do complemento será necessária a partir do início de 2021.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Os usuários licenciados do Office 365 E5, Microsoft 365 E5, Conformidade do Microsoft 365 E5 e Descoberta e Auditoria do Microsoft 365 podem se beneficiar da Auditoria Avançada.

Os usuários licenciados com Auditoria Avançada e o complemento retenção de log de auditoria de 10 anos podem se beneficiar da retenção de log de auditoria de 10 anos.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam da Auditoria Avançada porque os registros de auditoria relacionados à atividade do usuário nos serviços do Microsoft 365 podem ser retidos por até um ano. Além disso, eventos de auditoria de alto valor são registrados, como quando itens na caixa de correio de um usuário são acessados ou lidos. Para saber mais, confira [Auditoria Avançada no Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit)

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, a Auditoria Avançada é habilitada no nível de locatário para todas as organizações que têm uma assinatura do Office 365 ou microsoft 365 E5 e fornece automaticamente retenção de um ano de logs de auditoria para atividades (realizadas por usuários com a licença apropriada) no Azure Active Directory, Exchange e SharePoint. Além disso, as organizações podem usar políticas de retenção de log de auditoria para gerenciar o período de retenção para registros de auditoria gerados por atividades em outros serviços do Microsoft 365. A funcionalidade retenção de log de auditoria de 10 anos também é habilitada usando as mesmas políticas de retenção. Para saber mais, confira [Gerenciar políticas de retenção de log de auditoria](https://docs.microsoft.com/microsoft-365/compliance/audit-log-retention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário licenciados para o serviço?

A retenção de um ano de logs de auditoria e a auditoria de eventos cruciais só se aplicam aos usuários com a licença apropriada. Além disso, os administradores podem usar políticas de retenção de log de auditoria para especificar durações de retenção mais curtas para os logs de auditoria de usuários específicos.

A retenção de 10 anos de logs de auditoria só se aplica aos usuários com a licença de complemento apropriada. A SKU do complemento será necessária a partir do início de 2021.
