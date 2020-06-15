---
title: Diretrizes de licenciamento da Microsoft 365 para segurança & conformidade
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
ms.date: 4/13/2020
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Este artigo fornece orientações de licenciamento para a conformidade do Microsoft 365 para ajudar a evitar possíveis interrupções de serviço devido ao acesso não licenciado.
ms.openlocfilehash: 4664f782fcd15f3357ae2394b54a4a4302834073
ms.sourcegitcommit: 0637fd2740c83655379773f5f5d0adcf3cde693c
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/12/2020
ms.locfileid: "44711131"
---
# <a name="microsoft-365-licensing-guidance-for-security--compliance"></a>Diretrizes de licenciamento da Microsoft 365 para segurança & conformidade

Para os fins deste artigo, um serviço de nível de locatário é um serviço online que, &mdash; quando adquirido para qualquer usuário no locatário (autônomo ou como parte do Office 365 ou Microsoft 365 Plans), &mdash; é ativado em parte ou de forma completa para todos os usuários no locatário. Embora alguns usuários não licenciados possam tecnicamente acessar o serviço, uma licença é necessária para qualquer usuário que você pretende aproveitar do serviço.

> [!NOTE]
> Alguns serviços de locatário atualmente não são capazes de limitar benefícios a usuários específicos. Devem ser tomadas esforços para limitar os benefícios do serviço aos usuários licenciados. Isso ajudará a evitar a interrupção de serviço em potencial para sua organização quando os recursos de direcionamento estiverem disponíveis.

Para ver as opções de licenciamento dos seus usuários para se beneficiarem dos recursos de conformidade da Microsoft 365 a partir de 1º de abril de 2020, baixe a comparação detalhada de licenciamento de conformidade da Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

## <a name="azure-active-directory-identity-protection"></a>Proteção de Identidade do Azure Active Directory

A proteção de identidade do Active Directory do Azure é um recurso do plano do Azure Active Directory Premium P2 que permite que você detecte possíveis vulnerabilidades que afetam as identidades da sua organização, configure as respostas automáticas para as ações suspeitas detectadas que estão relacionadas às identidades da sua organização e investigue incidentes suspeitos e tome as medidas apropriadas para resolvê-los.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os analistas e profissionais de segurança do SecOps se beneficiam de ter visualizações consolidadas de usuários com sinalizadores e eventos de risco baseados em algoritmos de aprendizado de máquina Os usuários finais se beneficiam da proteção automática fornecida por meio de acesso condicional com base em risco e a segurança aprimorada oferecida por atuar em vulnerabilidades.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Enterprise Mobility + Security E5/a5, Microsoft 365 E5/a5, a segurança da Microsoft 365 E5/a5 e o Azure Active Directory Premium plano 2 fornecem os direitos para um usuário se beneficiar da proteção de identidade do Azure Active Directory.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos de proteção de identidade do Azure AD estão habilitados no nível do locatário para todos os usuários no locatário. Para obter informações sobre a proteção de identidade do Azure AD, consulte [o que é a proteção de identidade do Azure Active Directory?](https://docs.microsoft.com/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Os administradores podem definir o escopo da proteção de identidade do Azure AD atribuindo políticas de risco que definem o nível de redefinições de senha e permitindo o acesso somente a usuários licenciados. Para obter instruções sobre como fazer o escopo de implantações de proteção de identidade do Azure AD, consulte [Configurar a política de risco de entrada](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy).

## <a name="azure-advanced-threat-protection"></a>Proteção Avançada contra Ameaças do Azure

A ATP (proteção avançada contra ameaças) do Azure é um serviço de nuvem que ajuda a proteger ambientes híbridos corporativos de vários tipos de ataques avançados e insidedos.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os analistas e profissionais de segurança do SecOp se beneficiam da capacidade do Azure ATP de detectar e investigar ameaças avançadas, identidades comprometidas e ações mal-intencionadas de insider. Os usuários finais se beneficiam com seus dados monitorados pelo Azure ATP.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Enterprise Mobility + Security E5/a5, Microsoft 365 E5/a5, a segurança da Microsoft 365 E5/a5 e a proteção avançada contra ameaças do Azure para usuários fornecem os direitos para se beneficiar do Azure ATP.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos do Azure ATP estão habilitados no nível do locatário para todos os usuários no locatário. Para obter informações sobre como configurar o Azure ATP, consulte [criar sua instância do Azure ATP](https://docs.microsoft.com/azure-advanced-threat-protection/install-atp-step1).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Os serviços do Azure ATP atualmente não são capazes de limitar recursos para usuários específicos. Você deve licenciar todos os usuários que pretende beneficiar.

## <a name="office-365-advanced-threat-protection"></a>Proteção Avançada contra Ameaças do Office 365

A proteção avançada contra ameaças (ATP) ajuda a proteger as organizações contra ataques sofisticados, como phishing e malwares de zero dias. Também fornece informações acionáveis ao se correlacionar sinais de uma ampla variedade de dados para ajudar a identificar, priorizar e fornecer recomendações sobre como lidar com ameaças potenciais.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

A ATP protege os usuários contra ataques sofisticados, como phishing e malwares de zero dias. Para obter a lista completa de serviços fornecidos no plano 1 e no plano 2, confira [proteção avançada contra ameaças do Office 365](https://products.office.com/exchange/advance-threat-protection).

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço? 

Office 365 proteção avançada contra ameaças, Office 365 E5/a5/G5, Microsoft 365 E5/a5/G5, Microsoft 365 E5/a5/G5 Security, Microsoft 365 Business Premium e Office 365 ATP Plans 1 e 2 fornecem os direitos para o usuário se beneficiar da proteção avançada contra ameaças.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos ATP são habilitados no nível do locatário para todos os usuários dentro do locatário. Para obter informações sobre como configurar as políticas ATP para usuários licenciados, consulte [Office 365 Advanced Threat Protection](https://docs.microsoft.com/office365/securitycompliance/office-365-atp).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Para escopo ATP, siga as políticas de implantação de links seguros e de anexos seguros:

- Para obter informações sobre como configurar links seguros para usuários licenciados, consulte [set up Office 365 ATP Safe links Policies](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-atp-safe-links-policies).

- Para obter informações sobre a configuração de anexos seguros para usuários licenciados, consulte [set up Office 365 ATP Safe Attachments Policies](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-atp-safe-attachments-policies).

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

O Office 365 Cloud app Security (OCAS) é um subconjunto do Microsoft Cloud app Security, com recursos limitados ao Office 365 e sem segurança adicional para aplicativos de nuvem de terceiros e serviços IaaS.

O OCAS fornece visibilidade de organizações a seus aplicativos e serviços em nuvem de produtividade, fornece uma análise sofisticada para identificar e combater ameaças de Cyber e permite que eles controlem como os dados são transferidos &mdash; no Office 365.

Para comparar recursos, confira [diferenças entre o Microsoft Cloud app Security e o Office 365 Cloud app Security](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365).

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

O OCAS descobre o ti de sombra, oferece proteção contra ameaças no Office 365 e pode controlar quais aplicativos têm permissão para acessar dados.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

O Office 365 E5/a5/G5 fornece os direitos para o usuário se beneficiar do OCAS.
Para obter mais informações, consulte a folha de dados de [Licenciamento do Microsoft Cloud app Security](https://www.aka.ms/mcaslicensing).

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos do OCAS são habilitados no nível do locatário para todos os usuários dentro do locatário.

Para obter informações sobre como configurar o serviço, consulte [configuração básica para o Cloud app Security](https://docs.microsoft.com/cloud-app-security/general-setup).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Os administradores podem fazer o escopo de implantações do OCAS para impor como determinados aplicativos são acessados e limitar os grupos de usuários monitorados pelo Office 365 Cloud app Security. Para obter mais informações, consulte [implantação com escopo](https://docs.microsoft.com/cloud-app-security/scoped-deployment).

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

O Microsoft Cloud app Security (MCAS) é uma solução do CASB (Cloud Access Security Broker) que oferece aos seus aplicativos de nuvem e serviços, fornece uma análise sofisticada para identificar e combater as ameaças da Cyber e permite que elas controlem como os dados são transferidos &mdash; em qualquer aplicativo de nuvem.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

O MCAS descobre e avalia o sombreamento, oferece proteção contra ameaças em aplicativos de nuvem de primeiro e terceiro, e protege as informações em aplicativos de nuvem de primeiro e terceiro.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

MCAS, Enterprise Mobility + Security E5/a5/G5, Microsoft 365 E5/a5/G5, Microsoft 365 E5/a5/G5 Security e a proteção e governança de informações do Microsoft 365 fornecem os direitos para um usuário se beneficiar do MCAS.

O Azure AD P1 fornece os direitos para um usuário se beneficiar dos recursos de descoberta no MCAS.

Para se beneficiar dos recursos de controle de aplicativo de acesso condicional no MCAS, os usuários também devem ser licenciados para o Azure Active Directory P1, que está incluído no Enterprise Mobility + Security E3/a3/G3, Enterprise Mobility + Security E5/a5/G5, Microsoft 365 E3/a3/G3, Microsoft 365 E5/a5/G5 e segurança do Microsoft 365 E5/a5/G5.

Para se beneficiar do rotulamento automático, os usuários devem ser licenciados para a proteção de informações do Azure P2, que está incluída no Enterprise Mobility + Security E5/a5/G5, Microsoft 365 E5/a5/G5, Microsoft 365 E5/a5/G5 conformidade e proteção e governança de informações do Microsoft 365.

Para obter mais informações, consulte a folha de dados de [Licenciamento do Microsoft Cloud app Security](https://www.aka.ms/mcaslicensing).

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos do MCAS são habilitados no nível do locatário para todos os usuários dentro do locatário.

Para obter informações sobre como configurar as políticas de segurança do aplicativo Cloud da Microsoft para usuários licenciados, consulte [Microsoft Cloud app Security Overview](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Os administradores podem fazer o escopo de implantações do MCAS para usuários licenciados usando os recursos de implantação com escopo disponíveis no serviço. Para obter mais informações, consulte [implantação com escopo](https://docs.microsoft.com/cloud-app-security/scoped-deployment).

## <a name="microsoft-defender-atp"></a>Microsoft Defender ATP

O Microsoft defender ATP é uma solução de segurança de ponto de extremidade que inclui gerenciamento e avaliação de vulnerabilidades baseados em riscos; recursos de redução da superfície de ataque; proteção com base no comportamento e na próxima geração da nuvem; detecção de pontos de extremidade e resposta (EDR); investigação e correção automáticas; e serviços gerenciados de busca. Confira a página [do Microsoft defender ATP](https://www.microsoft.com/microsoft-365/windows/microsoft-defender-atp?rtc=1) para saber mais.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Usuários licenciados do Windows 10 Enterprise e5, Windows 10 Education a5, Microsoft 365 E5 (M365 E5) que inclui o Windows 10 Enterprise e5, o Microsoft 365 E5 Security, o Microsoft 365 a5 (M365 a5) pode se beneficiar do Microsoft defender ATP.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os analistas e profissionais de segurança do SecOps se beneficiam dos recursos de segurança do ponto de extremidade do Microsoft defender ATP para fazer proteção preventiva, detecção de pós-violação, investigação automatizada e resposta a ameaças avançadas. Os usuários finais se beneficiam com eventos mal-intencionados monitorados pelo Microsoft defender ATP.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos ATP do Microsoft defender estão habilitados no nível do locatário para todos os usuários no locatário. Para obter informações sobre a implantação, consulte o [Guia de implantação](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/deployment-phases).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Os administradores do Microsoft defender ATP podem utilizar o [controle de acesso baseado em função (RBAC)](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/rbac) para criar funções e grupos dentro da equipe de operações de segurança para conceder o acesso apropriado ao centro de segurança do Microsoft defender.

## <a name="information-protection"></a>Proteção de Informações

A proteção de informações ajuda as organizações a descobrir, classificar, rotular e proteger documentos confidenciais e emails. Os administradores podem definir regras e condições para aplicar rótulos automaticamente, os usuários podem aplicar os rótulos manualmente ou uma combinação dos dois pode ser usada, onde os usuários recebem recomendações sobre a aplicação de rótulos.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam com a capacidade de aplicar manualmente os rótulos de sensibilidade ao conteúdo ou fazer com que seu conteúdo seja classificado automaticamente.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Microsoft 365 E5/a5/G5/E3/a3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/e5, Office 365 E5/a5/E3/a3/F3, o plano do AIP 1 e o plano do AIP 2 fornecem os direitos para o usuário se beneficiar do rótulo de confidencialidade manual.

O Microsoft 365 E5/a5/G5/E3/a3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/e5, o plano do AIP 1 e o plano 2 do AIP fornecem os direitos para o usuário se beneficiar da aplicação e visualização dos rótulos de confidencialidade no Power BI e para proteger os dados quando exportados do Power BI para o Excel 

> [!NOTE]
> O Power BI está incluído no Microsoft 365 E5/a5/G5; em todos os outros planos, o Power BI deve ser licenciado separadamente.

Microsoft 365 E5/a5/G5, Microsoft 365 E5/a5/G5 conformidade, proteção e governança de informações da Microsoft 365, Office 365 e5, Office 365 Advanced Compliance, Enterprise Mobility + Security E5 e AIP Plan 2 fornecem os direitos para um usuário se beneficiar do rótulo de confidencialidade automática.

Para obter direitos específicos por licença, consulte a comparação detalhada de licenciamento de conformidade da Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx) Não inclui direitos para classificação automática com base no aprendizado da máquina (classificadores treinado).

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos de proteção de informações são habilitados no nível do locatário para todos os usuários no locatário. Para obter informações sobre como configurar políticas para usuários licenciados, consulte Ativando o Azure Rights Management.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Exceto ao usar o recurso de scanner AIP, as políticas podem ser modeladas para grupos específicos ou usuários e registros podem ser editados para impedir que usuários não licenciados executem recursos de classificação ou rotulação. Para obter instruções sobre como fazer o escopo de implantações de AIP, consulte [Configurando a política de proteção de informações do Azure](https://docs.microsoft.com/azure/information-protection/configure-policy).

Para o recurso de scanner do AIP, a Microsoft não compromete o fornecimento de recursos de classificação, rótulo ou proteção de arquivos para usuários que não estão licenciados.

## <a name="information-governance"></a>Governança de informações

O controle de informações ajuda as organizações a gerenciar seus riscos por meio da descoberta, classificação, rotulação e controle de seus dados. O controle de informações permite que as organizações atendam aos requisitos normativos e de negócios, além de reduzir a superfície de ataque fornecendo recursos de retenção e exclusão nos seus dados do Microsoft 365 e de terceiros.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam com a possibilidade de classificar dados para fins de retenção a fim de obter políticas e regulamentações específicas.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

O Microsoft 365 E5/a5/E3/a3, o Office 365 E5/a5/E3 fornece os direitos para um usuário se beneficiar de uma única política de retenção em toda a organização ou de todo o local e/ou uma etiqueta de retenção manual.

Microsoft 365 E5/a5, Microsoft 365 E5/a5 conformidade, proteção e governança de informações do Microsoft 365 o Office 365 E5/a5 e o Office 365 Advanced Compliance fornecem os direitos para que um usuário se beneficie de aplicar automaticamente rótulos de retenção ou políticas, iniciando o período de retenção de um rótulo de retenção com base em um evento personalizado, disparando uma revisão de disposição manual no final do período de retenção do rótulo, importando dados de terceiros por meio de conectores de dados nativos

Microsoft 365 E5/a5, Microsoft 365 E5/a5 conformidade, proteção e governança de informações da Microsoft 365 fornecem os direitos para que um usuário se beneficie de aplicar automaticamente os rótulos de retenção com base em classificadores estagiários.

Para obter direitos específicos por licença, consulte a comparação detalhada de licenciamento de conformidade da Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

Não inclui direitos para retenção automática com base no aprendizado da máquina (classificadores estagiários).

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos de governança de informações são habilitados no nível do locatário para todos os usuários no locatário. Para obter informações sobre como configurar o controle de informações para aplicar rotulamento automático e políticas para usuários licenciados, consulte [Manage Information Governance](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Os recursos de controle de informações podem ser aplicados aos usuários licenciados em locais específicos (sites de equipe, sites de grupo, etc.). Para obter informações sobre como configurar o controle de informações para aplicar rotulamento automático e políticas para usuários licenciados, consulte [Manage Information Governance](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance).

## <a name="records-management"></a>Gerenciamento de Registros

O gerenciamento de registros ajuda as organizações a cumprir as obrigações de manutenção de registros e de negócios por meio da descoberta, classificação, rotulação, retenção e recursos de exclusão do defensible em seus dados do Microsoft 365 e de terceiros.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Microsoft 365 E5/a5, conformidade da Microsoft 365 E5/a5, proteção e governança de informações da Microsoft 365, Office 365 E5/a5, Office 365 Advanced Compliance fornecem os direitos para um usuário se beneficiar do gerenciamento de registros, incluindo a declaração de itens como registros, a aplicação automática de rótulos de retenção ou registro e a execução de processos de análise de descarte

Microsoft 365 E5/a5, Microsoft 365 E5/a5 conformidade, proteção e governança de informações da Microsoft 365 fornecem os direitos para que um usuário se beneficie de aplicar automaticamente os rótulos de retenção ou registro com base em classificadores estagiários.

Para obter direitos específicos por licença, consulte a comparação detalhada de licenciamento de conformidade da Microsoft 365. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam com a possibilidade de declarar conteúdo como registro e gerenciar o processo de registros completos da definição e declaração de políticas através da alienação defensible.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos de gerenciamento de registros estão habilitados no nível do locatário para todos os usuários no locatário. Para obter informações sobre como configurar o gerenciamento de registros a ser aplicado a usuários licenciados, consulte [Gerenciamento de registros no Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/records-management).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Os recursos de gerenciamento de registros podem ser aplicados aos usuários licenciados em locais específicos (sites de equipe, sites de grupo, etc.). Para obter informações sobre como configurar o gerenciamento de registros a ser aplicado a usuários licenciados, consulte [Gerenciamento de registros no Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/records-management).

## <a name="ediscovery"></a>Descoberta eletrônica

a descoberta eletrônica fornece soluções de investigação e descoberta eletrônica para departamentos jurídicos e de ti em corporações para identificar, coletar, preservar, reduzir e revisar o conteúdo relacionado a uma investigação ou litígio antes de exportar do sistema Microsoft 365.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Um usuário se beneficia da descoberta eletrônica avançada quando o usuário é selecionado como um funcionário de dados (uma pessoa com controle administrativo de um documento ou arquivo eletrônico) para um caso.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Microsoft 365 E5/a5/G5/E3/a3/G3, Office 365 E5/a5/G5/E3/a3/G3 e Office 365 Advanced Compliance fornecem os direitos para um usuário se beneficiar da descoberta eletrônica principal.
Microsoft 365 E5/a5/G5, Microsoft 365 E5/a5/G5 conformidade, Microsoft 365 E5/a5 eDiscovery e auditoria, Office 365 E5/a5/G5 e Office 365 conformidade avançada fornecem os direitos para um usuário se beneficiar da descoberta eletrônica avançada.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos de descoberta eletrônica avançada são habilitados no nível do locatário para todos os usuários no locatário quando os administradores atribuem permissões de descoberta eletrônica no centro de conformidade do & de segurança.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

os administradores de descoberta eletrônica podem selecionar usuários específicos como responsáveis por dados para um caso usando a ferramenta de gerenciamento do responsáveis pela descoberta eletrônica avançada, conforme descrito em [Adicionar responsáveis a um caso de descoberta eletrônica avançada](https://docs.microsoft.com/microsoft-365/compliance/add-custodians-to-case).

## <a name="office-365-customer-key"></a>Chave de cliente do Office 365

Com a chave do cliente, você controla as chaves de criptografia da sua organização e configura o Office 365 para usá-las para criptografar seus dados em repouso nos data centers da Microsoft. Em outras palavras, a chave do cliente permite que você adicione uma camada de criptografia que pertença a você, usando suas próprias chaves. Os dados em repouso incluem dados do Exchange Online e do Skype for Business que são armazenados em caixas de correio e arquivos no SharePoint Online e no OneDrive for Business.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam da chave do cliente, mantendo seus dados em repouso criptografados na camada de aplicativo usando chaves de criptografia fornecidas, controladas e gerenciadas por sua própria organização.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Microsoft 365 E5/a5, Microsoft 365 E5/a5 conformidade, Microsoft 365 Information Protection e governança, Office 365 E5/a5 e Office 365 Advanced Compliance fornecem os direitos para um usuário se beneficiar da chave do cliente. Para obter o benefício completo da chave do cliente, você também deve ter uma assinatura do Azure Key Vault.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

As chaves de criptografia de chave do cliente do Office 365 podem ser habilitadas para todos os dados armazenados nas caixas de correio do Exchange Online e do Skype for Business, e os arquivos do SharePoint Online, do OneDrive for Business e do teams. Para obter mais informações sobre a chave do cliente do Office 365, incluindo como começar, confira [criptografia de serviço com a chave do cliente no Office 365](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Para atribuir chaves de criptografia a dados dentro de uma organização do Office 365 e/ou do Microsoft 365 para usuários licenciados, siga as instruções de implantação das chaves de criptografia de chave do cliente.

- Para os arquivos do SharePoint Online, do OneDrive for Business e do Teams, os arquivos em um ou mais sites podem ser criptografados usando a chave do cliente.

- Para o Exchange Online e o Skype for Business, as caixas de correio podem ser criptografadas usando a chave do cliente.

## <a name="office-365-customer-lockbox"></a>Sistema de Proteção de Dados do Cliente do Office 365

A Lockbox do cliente fornece uma camada adicional de controle, oferecendo aos clientes a capacidade de fornecer autorização de acesso explícito para operações de serviço. Ao demonstrar que os procedimentos estão em vigor para autorização explícita de acesso a dados, a Lockbox de clientes também pode ajudar as organizações a cumprir determinadas obrigações de conformidade, como HIPAA e FEDRAMP.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam da Lockbox de clientes garantindo que ninguém da Microsoft possa acessar seu conteúdo para executar uma operação de serviço sem a aprovação explícita do cliente. O cliente de lockbox traz o cliente para o fluxo de trabalho de aprovação para solicitações de acesso ao seu conteúdo. Ocasionalmente, os engenheiros da Microsoft estão envolvidos durante o processo de suporte para solucionar e corrigir problemas relatados pelo cliente. Na maioria dos casos, os problemas são corrigidos por meio de ferramentas abrangentes de telemetria e depuração que a Microsoft tem em vigor para seus serviços. No entanto, pode haver casos que exijam que um engenheiro da Microsoft acesse o conteúdo do cliente para determinar a causa raiz e corrigir o problema. A Lockbox do cliente exige que o engenheiro solicite acesso do cliente como uma etapa final no fluxo de trabalho de aprovação. Isso oferece às organizações a opção de aprovar ou negar essas solicitações, o que fornece a eles um controle direto sobre se um engenheiro da Microsoft pode acessar os dados de usuário final da organização.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Office 365 E5/a5/G5, Microsoft 365 E5/a5/G5, Microsoft 365 E5/a5/G5 conformidade, gerenciamento de riscos do Microsoft 365 Insider e Office 365 conformidade avançada fornecem os direitos para um usuário se beneficiar da Lockbox do cliente.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Os administradores podem ativar os controles de lockbox do cliente no centro de administração do Microsoft 365. Para obter mais informações, consulte [Lockbox de cliente no Office 365](https://docs.microsoft.com/microsoft-365/compliance/customer-lockbox-requests). Quando a Lockbox do cliente está ativada, a Microsoft é obrigada a obter a aprovação de uma organização antes de acessar qualquer um de seus conteúdos.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

A Microsoft fornece solicitações de aprovação de controle de acesso de lockbox de cliente para usuários em sua organização.

## <a name="privileged-access-management-in-office-365"></a>O Privileged Access Management no Office 365

O [Gerenciamento de acesso privilegiado (PAM)](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration) fornece controle de acesso granular sobre tarefas administrativas privilegiadas no Office 365. Depois de habilitar o PAM, os usuários precisarão solicitar acesso just-in-time por meio de um fluxo de trabalho de aprovação com alto escopo e limite de tempo para concluir tarefas elevadas e privilegiadas.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Habilitar o PAM permite que as organizações operem com privilégios zero. Os usuários se beneficiam da camada adicional de defesa contra as vulnerabilidades decorrentes de um acesso administrativo em posição, que fornece acesso de unfettered a seus dados.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço? 

Office 365 E5/a5, Microsoft 365 E5/a5, Microsoft 365 E5/a5 conformidade e proteção e governança de informações do Microsoft 365 E5/a5 fornecem os direitos para um usuário se beneficiar do PAM.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos do PAM são habilitados no nível do locatário para todos os usuários dentro do locatário. Para obter informações sobre como configurar as políticas do PAM, confira [introdução ao gerenciamento de acesso privilegiado](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Os clientes podem gerenciar o PAM por usuário por meio de grupos de aprovadores e políticas de acesso, que podem ser aplicados a usuários licenciados. Para obter mais informações, consulte [Gerenciamento de acesso privilegiado no Office 365](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751).

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Prevenção de perda de dados do Office 365 para o Exchange Online, o SharePoint Online e o OneDrive for Business

Com o Office 365 Data Loss Prevention (DLP) para o Exchange Online, o SharePoint Online e o OneDrive for Business, as organizações podem identificar, monitorar e proteger automaticamente informações confidenciais entre emails e arquivos (incluindo arquivos armazenados em repositórios de arquivos do Microsoft Teams).

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam da DLP para o Exchange Online, o SharePoint Online e o OneDrive for Business quando seus emails e arquivos estão sendo inspecionados em busca de informações confidenciais, conforme configurado na política de DLP da organização.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Microsoft 365 a1/E3/a3/Business, Office 365 E3/a3 e Office 365 Data Loss Prevention fornecem os direitos para um usuário se beneficiar do Office 365 DLP para Exchange Online, SharePoint Online e OneDrive for Business.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os emails do Exchange Online, os sites do SharePoint e as contas do OneDrive são *locais (cargas de trabalho) habilitados* para esses recursos de DLP para todos os usuários no locatário. Para obter mais informações sobre como usar políticas de DLP, consulte [Overview of Data Loss Prevention](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Os administradores podem personalizar locais (cargas de trabalho), usuários incluídos e usuários excluídos no centro de conformidade & segurança, em locais de **prevenção de perda de dados**  >  **Locations**.

## <a name="communication-data-loss-prevention-for-teams"></a>Prevenção de perda de dados de comunicação para o Microsoft Teams

Com a comunicação DLP para Teams, as organizações podem bloquear chats e mensagens de canal que contenham informações confidenciais, como informações financeiras, informações de identificação pessoal, informações relacionadas à saúde ou outras informações confidenciais.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Usuários licenciados do Office 365 E5/a5, Microsoft 365 E5/a5, Microsoft 365 Information Protection and Governance e Office 365 Advanced Compliance podem se beneficiar do Communication DLP for Teams.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os remetentes se beneficiam com informações confidenciais em seus chat de saída e mensagens de canal inspecionadas para obter informações confidenciais, conforme configurado na política de DLP da organização.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, as mensagens de chat e de canal do teams são um *local habilitado (carga de trabalho)* para esses recursos de DLP para todos os usuários no locatário. Para obter mais informações sobre como usar políticas de DLP, consulte [Overview of Data Loss Prevention](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Os administradores podem personalizar locais (cargas de trabalho), usuários incluídos e usuários excluídos no centro de conformidade & segurança, em locais de **prevenção de perda de dados**  >  **Locations**.

## <a name="information-barriers"></a>Barreiras de informações

As barreiras de informação são políticas que um administrador pode configurar para impedir que pessoas ou grupos se comuniquem entre si. Isso é útil se, por exemplo, um departamento estiver lidando com informações que não deveriam ser compartilhadas com outros departamentos, ou se um grupo precisar ser impedido de se comunicar com contatos externos. As políticas de barreira de informações também impedem pesquisas e descoberta. Isso significa que se você tentar se comunicar com alguém com o qual você não deve se comunicar, não encontrará esse usuário no seletor de pessoas.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam dos recursos avançados de conformidade das barreiras de informação quando estão restritos à comunicação com outras pessoas. Por exemplo:

| Cenário | Quem requer uma licença? |
|:-------|:------|
| Dois grupos (grupo 1 e grupo 2) não podem se comunicar uns com os outros (ou seja, os usuários do grupo 1 estão restritos à comunicação com usuários do grupo 2 e os usuários do grupo 2 estão restritos à comunicação com usuários do grupo 1. | Usuários no grupo 1 e no grupo 2 |
| Os usuários no grupo 1 estão restritos à comunicação com o restante da empresa. | Usuários somente no grupo 1 |
| O restante da empresa está restrito à comunicação com o grupo 1. | Todos os usuários, exceto aqueles no grupo 1 |
| Os usuários do grupo 1 estão restritos à comunicação com usuários do grupo 2, mas os usuários do grupo 2 podem se comunicar com usuários do grupo 1. | Usuários somente no grupo 1 ||

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Microsoft 365 E5/a5, Microsoft 365 E5/a5 conformidade, Microsoft 365 Insider Risk Management, Office 365 E5/a5 e Office 365 Advanced Compliance fornecem os direitos para o usuário se beneficiar de barreiras de informação.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Administradores criem e gerenciem políticas de barreira de informações usando cmdlets do PowerShell no centro de conformidade do & de segurança. Os administradores devem receber a função de administrador global do Microsoft 365 Enterprise, administrador global do Office 365 ou administrador de conformidade para criar uma política de barreira de informações. Por padrão, essas políticas se aplicam a todos os usuários no locatário. Para obter mais informações sobre as barreiras de informação, confira [barreiras de informações no Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Os administradores podem personalizar locais (cargas de trabalho), usuários incluídos e usuários excluídos no centro de conformidade do & de segurança. Por exemplo, se todos os usuários estiverem licenciados para o Office 365 E3, e nenhum for licenciado para o Office 365 Advanced Compliance/e5, não precisará criar nenhuma política de barreira de informações para a organização. Para obter mais informações, consulte [barreiras de informações no Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams).

## <a name="office-365-message-encryption"></a>Criptografia de Mensagem do Office 365

Criptografia de Mensagens do Office 365 (OME) é um serviço integrado ao Azure Rights Management (Azure RMS) que permite o envio de emails criptografados para pessoas dentro ou fora da sua organização, independente do endereço de email de destino (Gmail, Yahoo! Email, Outlook.com, etc.).

Para exibir mensagens criptografadas, os destinatários podem obter uma senha avulsa, entrar com uma conta da Microsoft ou com uma conta corporativa ou de estudante associada ao Office 365. Os destinatários também podem enviar respostas criptografadas. Eles não precisam de uma assinatura para exibir mensagens criptografadas ou enviar respostas criptografadas.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os remetentes de mensagens se beneficiam do controle adicionado sobre emails confidenciais fornecidos pela criptografia de mensagens do Office 365.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Microsoft 365 E3/a3, Office 365 E3/a3 e o plano de proteção de informações do Azure 1 fornecem os direitos para um usuário se beneficiar da criptografia de mensagens do Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Os administradores criam e gerenciam as políticas de criptografia de mensagens do Office 365 no centro de administração do Exchange em regras de **fluxo de emails**  >  **Rules**. Por padrão, essas regras se aplicam a todos os usuários no locatário. Para obter mais informações sobre como configurar os novos recursos de criptografia de mensagens do Office 365, consulte [configurar novos recursos de criptografia de mensagens do office 365](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Os administradores devem aplicar regras de fluxo de email para a criptografia de mensagens do Office 365 somente a usuários licenciados. Para obter mais informações sobre a definição de regras de fluxo de emails, consulte [definir regras de fluxo de email para criptografar mensagens de email no Office 365](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="office-365-advanced-message-encryption"></a>Criptografia de Mensagem Avançada do Office 365

Office 365 Advanced Message Encryption ajuda os clientes a cumprir as obrigações de conformidade que exigem controles mais flexíveis sobre destinatários externos e seu acesso a emails criptografados. Com a criptografia avançada de mensagens, os administradores podem controlar emails confidenciais compartilhados fora da organização usando políticas automáticas que podem detectar tipos de informações confidenciais (por exemplo, informações de identificação pessoal ou IDs financeiras ou de integridade) ou podem usar palavras-chave para melhorar a proteção aplicando modelos de email personalizados e expirando o acesso a emails criptografados por meio de um portal da Web seguro. Além disso, os administradores podem controlar ainda mais os emails criptografados acessados externamente por meio de um portal da Web seguro revogando o acesso a qualquer momento.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os remetentes de mensagens se beneficiam do controle adicionado sobre emails confidenciais fornecidos pela criptografia avançada de mensagens.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Office 365 E5/a5, Microsoft 365 E5/a5, conformidade com a Microsoft 365 E5/a5, proteção e governança de informações do Microsoft 365 e Office 365 Advanced Compliance forneça os direitos para um usuário se beneficiar da criptografia de mensagens avançadas.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Os administradores criam e gerenciam políticas avançadas de criptografia de mensagens no centro de administração do Exchange em regras de fluxo de emails. Por padrão, essas regras se aplicam a todos os usuários no locatário. Para obter mais informações sobre como configurar os novos recursos de criptografia de mensagens, consulte [configurar novos recursos de criptografia de mensagens do Office 365](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Os administradores devem aplicar regras de fluxo de email para a criptografia de mensagens avançada somente a usuários licenciados. Para obter mais informações sobre a definição de regras de fluxo de emails, consulte [definir regras de fluxo de email para criptografar mensagens de email no Office 365](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="communication-compliance"></a>Conformidade em comunicações

A conformidade de comunicação no Microsoft 365 ajuda a minimizar os riscos de comunicação ajudando você a detectar, capturar e realizar ações de correção para mensagens inadequadas em sua organização. Você pode definir políticas específicas que capturam emails internos e externos, Microsoft Teams ou comunicações de terceiros em sua organização. Os revisores podem tomar as ações de correção apropriadas para garantir que eles estejam em conformidade com os padrões de mensagem da sua organização.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os especialistas de conformidade se beneficiam do serviço com a comunicação da organização monitorada por políticas de conformidade de comunicação.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

Office 365 E5/a5, Microsoft 365 E5/a5, conformidade com o Microsoft 365 E5/a5 e o gerenciamento de risco do Microsoft 365 Insider fornecem os direitos para o usuário se beneficiar da conformidade com a comunicação.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Administradores e especialistas em conformidade criam políticas de conformidade de comunicação no centro de conformidade da Microsoft 365. Essas políticas definem quais comunicações e usuários estão sujeitos a análise na organização, definem condições personalizadas que as comunicações devem atender e especificam quem deve realizar revisões.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Os administradores escolhem usuários ou grupos específicos para incluir em uma política de conformidade de comunicação. Ao escolher um grupo, também é possível selecionar usuários específicos no grupo para excluir da política de conformidade de comunicação. Para obter mais informações sobre políticas de conformidade de comunicação, consulte [conformidade de comunicação no Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/communication-compliance-configure).

## <a name="insider-risk-management"></a>Gerenciamento de riscos internos

O gerenciamento de riscos do Insider é uma solução no Microsoft 365 que ajuda a minimizar riscos internos, permitindo que você detecte, investigue e execute ações em atividades arriscadas em sua organização.
As políticas personalizadas permitem que você detecte e execute ações em atividades mal-intencionadas e inadvertidamente arriscadas em sua organização, incluindo casos de escalonamento para o eDiscovery avançado da Microsoft, se necessário. Os analistas de risco em sua organização podem tomar as ações apropriadas rapidamente para garantir que os usuários estejam em conformidade com os padrões de conformidade da sua organização.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam com suas atividades monitoradas por risco.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Quais licenças fornecem os direitos para um usuário se beneficiar do serviço?

O Microsoft 365 E5/a5, a conformidade da Microsoft 365 E5/a5 e o gerenciamento de risco do Microsoft 365 Insider fornecem os direitos para o usuário se beneficiar do gerenciamento de risco do insider.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

As políticas de gerenciamento de risco do insider devem ser criadas no centro de conformidade da Microsoft 365 e atribuídas aos usuários.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Ao criar uma política no centro de conformidade da Microsoft 365, na página **escolher usuários e grupos** , selecione **escolher usuários ou grupos** para selecionar apenas os usuários licenciados ou, se todos os seus usuários estiverem licenciados, você poderá selecionar a caixa de seleção **todos os usuários e grupos habilitados para email** . Para obter mais informações, consulte [introdução ao gerenciamento de risco do insider](https://docs.microsoft.com/microsoft-365/compliance/insider-risk-management-configure).

## <a name="conditional-access-policies"></a>Políticas de Acesso Condicional

O acesso condicional é a ferramenta usada pelo Azure Active Directory para trazer sinais juntos, para tomar decisões e impor políticas organizacionais. O acesso condicional está no coração do plano de controle de identidade controlada. As políticas de acesso condicional em suas mais simples são instruções if-then. Se um usuário quiser acessar um recurso, ele deverá concluir uma ação. Exemplo: um gerente de folha de pagamento deseja acessar o aplicativo de folha de pagamento e é necessário para executar a autenticação multifator para acessá-lo.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Usuários licenciados da Enterprise Mobility + Security E3/a3, Microsoft 365 F3/E3/a3 e Azure Active Directory Premium plano 1 podem se beneficiar de políticas de acesso condicional. Usuários licenciados da Enterprise Mobility + Security E5/a5/G5, Microsoft 365 E5/a5, Microsoft E5 Security e Azure Active Directory Premium plano 2 podem se beneficiar da proteção de identidade (políticas de acesso condicional com base em risco).

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os analistas de operações de segurança e os profissionais de segurança se beneficiam com a capacidade de impor políticas organizacionais aos usuários, exigindo que eles atendam a determinados critérios antes de conceder acesso ao conteúdo corporativo. Os usuários finais se beneficiam pela capacidade de acessar o trabalho em qualquer lugar e sempre que escolherem, enquanto protegem os ativos da organização.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos de acesso condicional estão habilitados no nível do locatário para todos os usuários no locatário.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Para obter proteção de identidade e acesso condicional especificamente, um usuário deve ser incluído em um grupo ou ser adicionado a uma política de acesso condicional. A condição usuários e grupos é obrigatória em uma política de acesso condicional. Na política, você pode selecionar todos os **usuários** ou usuários e grupos específicos. Você deve selecionar apenas os usuários e grupos licenciados adequadamente. Para obter mais informações, consulte [o que são condições no acesso condicional do Azure Active Directory?](https://docs.microsoft.com/azure/active-directory/conditional-access/conditions).

## <a name="advanced-audit"></a>Auditoria Avançada

Auditoria avançada no Microsoft 365 fornece retenção de um ano de logs de auditoria para atividades de usuário e administrador e fornece a capacidade de criar políticas de retenção de log de auditoria personalizadas para gerenciar a retenção de logs de auditoria para outros serviços do Microsoft 365. Também fornece acesso a eventos cruciais para investigações e acesso de alta largura de banda à API da atividade de gerenciamento do Office 365. Para obter mais informações, consulte [Advanced Audit in Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit).

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Os usuários licenciados do Office 365 e5, o Microsoft 365 e5, o Microsoft 365 E5 Compliance e o Microsoft 365 eDiscovery e a auditoria podem se beneficiar da auditoria avançada.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Um usuário se beneficia da auditoria avançada, pois os registros de auditoria relacionados à atividade do usuário nos serviços do Microsoft 365 podem ser retidos por até um ano. Além disso, eventos de auditoria de alto valor são registrados como quando os itens da caixa de correio de um usuário são acessados ou lidos. Para obter mais informações, consulte [Advanced Audit in Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit).

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, a auditoria avançada é habilitada no nível do locatário para todas as organizações que têm uma assinatura do Office 365 ou do Microsoft 365 E5 e fornece automaticamente retenção de um ano de logs de auditoria para atividades (realizadas por usuários com a licença apropriada) no Azure Active Directory, no Exchange e no SharePoint. Além disso, as organizações podem usar políticas de retenção de log de auditoria para gerenciar o período de retenção de registros de auditoria gerados pela atividade em outros serviços do Microsoft 365. Para saber mais, confira [Gerenciar políticas de retenção de log de auditoria](https://docs.microsoft.com/microsoft-365/compliance/audit-log-retention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Retenção de um ano de logs de auditoria e a auditoria de eventos cruciais só se aplicam a usuários com a licença apropriada. Além disso, os administradores podem usar políticas de retenção de log de auditoria para especificar durações de retenção mais curtas para os logs de auditoria de usuários específicos.
