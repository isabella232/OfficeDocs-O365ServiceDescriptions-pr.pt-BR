---
title: Diretrizes de licenciamento de serviços em nível de locatário do Microsoft 365
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Este artigo fornece orientações de licenciamento para os serviços de nível de locatário do Microsoft 365 para ajudar a evitar possíveis interrupções de serviço devido ao acesso não licenciado.
ms.openlocfilehash: 234bdc341647c0f62ad1d606e2938ef208996107
ms.sourcegitcommit: 6d32bc9501b8cbfa71a1763103a6111898d2cda8
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 08/03/2019
ms.locfileid: "36171671"
---
# <a name="microsoft-365-tenant-level-services-licensing-guidance"></a>Diretrizes de licenciamento de serviços em nível de locatário do Microsoft 365

Para os fins deste artigo, um serviço de nível de locatário é um serviço online que&mdash;, quando adquirido para qualquer usuário no locatário (autônomo ou como parte do Office 365 ou Microsoft 365 Plans)&mdash;, é ativado em parte ou de forma completa para todos os usuários no locatário. Embora alguns usuários não licenciados possam tecnicamente acessar o serviço, uma licença é necessária para qualquer usuário que você pretende aproveitar do serviço.

> [!NOTE]
> Alguns serviços de locatário atualmente não são capazes de limitar benefícios a usuários específicos. Devem ser tomadas esforços para limitar os benefícios do serviço aos usuários licenciados. Isso ajudará a evitar a interrupção de serviço em potencial para sua organização quando os recursos de direcionamento estiverem disponíveis.

## <a name="azure-active-directory-identity-protection"></a>Proteção de identidade do Azure Active Directory

O Azure Active Directory Identity Protection (AADIP) é um recurso do plano do Microsoft Azure Active Directory Premium P2 que permite que você detecte possíveis vulnerabilidades que afetam as identidades da sua organização, configure as respostas automáticas para detectadas suspeitas ações relacionadas às identidades da sua organização e investigue incidentes suspeitos e tome as medidas apropriadas para resolvê-los.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Usuários licenciados da Enterprise Mobility + Security E5/a5/G5, Microsoft 365 E5/a5/G5, Microsoft 365 E5/a5/G5 Security e Azure Active Directory Premium plano 2 podem se beneficiar do AADIP.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os analistas e profissionais de segurança do SecOps se beneficiam de ter visualizações consolidadas de usuários com sinalizadores e eventos de risco baseados em algoritmos de aprendizado de máquina Os usuários finais se beneficiam da proteção automática fornecida por meio de acesso condicional com base em risco e a segurança aprimorada oferecida por atuar em vulnerabilidades.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos do AADIP são habilitados no nível do locatário para todos os usuários dentro do locatário. Para obter informações sobre como configurar o AADIP, consulte Habilitando a [proteção de identidade do Azure Active Directory](https://docs.microsoft.com/azure/active-directory/identity-protection/enable).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Os administradores podem definir o escopo do AADIP atribuindo políticas de risco que definem o nível de redefinições de senha e permitindo o acesso somente a usuários licenciados. Para obter instruções sobre como fazer o escopo de implantações do AADIP, consulte [Configurar a política de risco de entrada](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy).

## <a name="azure-advanced-threat-protection"></a>Proteção Avançada contra Ameaças do Azure

A ATP (proteção avançada contra ameaças) do Azure é um serviço de nuvem que ajuda a proteger ambientes híbridos corporativos de vários tipos de ataques avançados e insidedos.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Usuários licenciados da Enterprise Mobility + Security E5/a5/G5, Microsoft 365 E5/a5/G5, Microsoft 365 E5/a5/G5 Security e proteção avançada contra ameaças do Azure para usuários podem se beneficiar do Azure ATP.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os analistas e profissionais de segurança do SecOp se beneficiam da capacidade do Azure ATP de detectar e investigar ameaças avançadas, identidades comprometidas e ações mal-intencionadas de insider. Os usuários finais se beneficiam com seus dados monitorados pelo Azure ATP.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos do Azure ATP estão habilitados no nível do locatário para todos os usuários no locatário. Para obter informações sobre como configurar o Azure ATP, consulte [criar sua instância do Azure ATP](https://docs.microsoft.com/azure-advanced-threat-protection/install-atp-step1).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

A Microsoft não se compromete a fornecer recursos de detecção de ameaças para usuários que não estão licenciados. Com o tempo, as verificações de licença ou a ferramenta direcionada serão adicionadas ao Azure ATP para garantir que a funcionalidade ATP do Azure seja aplicável somente a usuários licenciados.

## <a name="azure-information-protection"></a>Proteção de Informações do Azure

A proteção de informações do Azure (AIP) ajuda as organizações a descobrir, classificar, rotular e proteger documentos confidenciais e emails. Os administradores podem definir regras e condições para aplicar rótulos automaticamente, os usuários podem aplicar os rótulos manualmente ou uma combinação dos dois pode ser&mdash;usada, onde os usuários recebem recomendações sobre a aplicação de rótulos.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Usuários licenciados do Microsoft 365 F1, Microsoft 365 Business, Microsoft 365 E3/a3/G3 e o plano do AIP 1 podem se beneficiar do plano 1 do AIP. Usuários licenciados do Microsoft 365 E5/a5/G5, Microsoft 365 E5/a5/G5 conformidade e o plano do AIP 2 podem se beneficiar do plano 2 do AIP.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

O recurso de scanner AIP automaticamente classifica, rotula e protege arquivos que residem em repositórios de arquivos locais.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos do AIP estão habilitados no nível do locatário para todos os usuários no locatário. Para obter informações sobre a configuração de políticas do AIP para usuários licenciados, consulte Ativando o [Azure Rights Management](https://docs.microsoft.com/azure/information-protection/activate-service).
### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

As políticas de recurso do AIP (exceto o recurso de scanner) podem ser delimitadas para grupos ou usuários específicos; os registros podem ser editados para impedir que usuários não licenciados executem os recursos de classificação ou rotulação do AIP. Para obter instruções sobre como fazer o escopo de implantações de AIP, consulte Configurando [a política de proteção de informações do Azure](https://docs.microsoft.com/azure/information-protection/configure-policy).

Para o recurso de scanner do AIP, a Microsoft não compromete o fornecimento de recursos de classificação, rótulo ou proteção de arquivos para usuários que não estão licenciados. Com o tempo, as verificações de licença ou a ferramenta direcionada serão adicionadas ao AIP para garantir que o recurso de scanner seja atribuível a usuários licenciados.

## <a name="office-365-advanced-threat-protection"></a>Proteção Avançada contra Ameaças do Office 365

A proteção avançada contra ameaças (ATP) ajuda a proteger as organizações contra ataques sofisticados, como phishing e malwares de zero dias. Também fornece informações acionáveis ao se correlacionar sinais de uma ampla variedade de dados para ajudar a identificar, priorizar e fornecer recomendações sobre como lidar com ameaças potenciais.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Usuários licenciados do Office 365 E5/a5/G5, Microsoft 365 E5/a5/G5, Microsoft 365 E5/a5/G5 Security, Microsoft 365 Business e Office 365 ATP Plans 1 e 2 podem se beneficiar da ATP.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

A ATP protege os usuários contra ataques sofisticados, como phishing e malwares de zero dias. Para obter a lista completa de serviços fornecidos no plano 1 e no plano 2, confira [proteção avançada contra ameaças do Office 365](https://products.office.com/exchange/advance-threat-protection).

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos ATP são habilitados no nível do locatário para todos os usuários dentro do locatário. Para obter informações sobre como configurar as políticas ATP para usuários licenciados, consulte [Office 365 Advanced Threat Protection](https://docs.microsoft.com/office365/securitycompliance/office-365-atp).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Para escopo ATP, siga as políticas de implantação de links seguros e de anexos seguros:

  - Para obter informações sobre como configurar links seguros para usuários licenciados, consulte [set up Office 365 ATP Safe links Policies](https://docs.microsoft.com/office365/securitycompliance/set-up-atp-safe-links-policies).

  - Para obter informações sobre a configuração de anexos seguros para usuários licenciados, consulte [set up Office 365 ATP Safe Attachments Policies](https://docs.microsoft.com/office365/securitycompliance/set-up-atp-safe-attachments-policies).

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

O Office 365 Cloud app Security (OCAS) é um subconjunto do Microsoft Cloud app Security, com recursos limitados ao Office 365 e sem segurança adicional para aplicativos de nuvem de terceiros e serviços IaaS.

O OCAS fornece visibilidade de organizações a seus aplicativos e serviços em nuvem de produtividade, fornece uma análise sofisticada para identificar e combater ameaças de Cyber e&mdash;permite que eles controlem como os dados são transferidos no Office 365.

Para comparar recursos, confira [diferenças entre o Microsoft Cloud app Security e o Office 365 Cloud app Security](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365).

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Usuários licenciados do Office 365 E5/a5/G5 podem se beneficiar do OCAS.

Para obter mais informações, consulte a folha de dados de licenciamento do [Microsoft Cloud app Security](http://www.aka.ms/mcaslicensing).

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

O OCAS descobre o ti de sombra, oferece proteção contra ameaças no Office 365 e pode controlar quais aplicativos têm permissão para acessar os dados do Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos do OCAS são habilitados no nível do locatário para todos os usuários dentro do locatário.

Para obter informações sobre como configurar o serviço, consulte [configuração básica para o Cloud app Security](https://docs.microsoft.com/cloud-app-security/general-setup).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Os administradores podem fazer o escopo de implantações do OCAS para impor como determinados aplicativos são acessados e limitar os grupos de usuários monitorados pelo Office 365 Cloud app Security. Para obter mais informações, consulte [implantação com escopo](https://docs.microsoft.com/cloud-app-security/scoped-deployment).

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

O Microsoft Cloud app Security (MCAS) é uma solução do CASB (Cloud Access Security Broker) que oferece aos seus aplicativos e serviços em nuvem, fornece uma análise sofisticada para identificar e combater ameaças da Cyber e permitir que eles controlem como os dados trafegam&mdash;em qualquer aplicativo na nuvem.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Usuários licenciados do MCAS, Enterprise Mobility + Security E5/a5/G5, Microsoft 365 E5/a5/G5 e a segurança do Microsoft 365 E5/a5/G5 podem se beneficiar do MCAS.

Usuários licenciados do Azure AD P1 podem se beneficiar dos recursos de descoberta no MCAS.

Para se beneficiar dos recursos de [controle de aplicativo de acesso condicional](https://docs.microsoft.com/cloud-app-security/proxy-intro-aad) no MCAS, os usuários também devem ser licenciados para o Azure Active Directory P1, que está incluído no Enterprise Mobility + Security E3/a3/G3, Enterprise Mobility + Security E5/a5/G5, Microsoft 365 E3/ A3/G3, Microsoft 365 E5/a5/G5 e segurança da Microsoft 365 E5/a5/G5.

Para se beneficiar do [rotulamento automático](https://docs.microsoft.com/cloud-app-security/data-protection-policies), os usuários devem ser licenciados para a proteção de informações do Azure P2, que está incluída no Enterprise Mobility + Security E5/a5/G5, Microsoft 365 E5/a5/G5 e conformidade com o Microsoft 365 E5/a5/G5.

Para obter mais informações, consulte a folha de dados de licenciamento do [Microsoft Cloud app Security](http://www.aka.ms/mcaslicensing).

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

O MCAS descobre e avalia o sombreamento, oferece proteção contra ameaças em aplicativos de nuvem de primeiro e terceiro, e protege as informações em aplicativos de nuvem de primeiro e terceiro.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos do MCAS são habilitados no nível do locatário para todos os usuários dentro do locatário.

Para obter informações sobre como configurar as políticas de segurança do aplicativo Cloud da Microsoft para usuários licenciados, consulte [Microsoft Cloud app Security Overview](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Os administradores podem fazer o escopo de implantações do MCAS para usuários licenciados usando os recursos de implantação com escopo disponíveis no serviço. Para obter mais informações, consulte [implantação com escopo](https://docs.microsoft.com/cloud-app-security/scoped-deployment).

## <a name="office-365-advanced-data-governance"></a>Gestão de Dados Avançada do Office 365

A governança de dados avançada (ADG) ajuda as organizações a cumprir os requisitos de governança de informações com políticas para habilitar a retenção e a exclusão. O ADG permite que as organizações rotulem conteúdo automaticamente com base no tipo de informações confidenciais e apliquem políticas de governança a esse conteúdo.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Usuários licenciados do Office 365 E5/a5/G5, Microsoft 365 E5/a5/G5, Microsoft 365 E5/a5/G5 conformidade e Office 365 Advanced Compliance podem se beneficiar do ADG.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

O ADG permite que os usuários apliquem rótulos a dados específicos para optar por políticas específicas, rotular automaticamente o conteúdo como um registro e gerenciar o processo de registros completos da declaração para o descarte.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos do ADG são habilitados no nível do locatário para todos os usuários dentro do locatário. Para obter informações sobre como configurar o ADG para aplicar rotulamento automático e políticas para usuários licenciados, consulte [Overview of Retention Labels](https://docs.microsoft.com/office365/securitycompliance/labels).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

As políticas de retenção do ADG podem ser aplicadas a usuários licenciados em locais específicos (sites de equipe, sites de grupo etc.) por meio da classificação automática. Para obter instruções sobre a aplicação de políticas de retenção do ADG, consulte [aplicando uma política de retenção a uma organização inteira ou locais específicos](https://docs.microsoft.com/office365/securitycompliance/retention-policies#applying-a-retention-policy-to-an-entire-organization-or-specific-locations).

## <a name="office-365-advanced-ediscovery"></a>Descoberta Eletrônica Avançada do Office 365

A descoberta eletrônica avançada do Office 365 fornece soluções de investigação e descoberta eletrônica para departamentos jurídicos e de ti em corporações para identificar, coletar, preservar, reduzir e revisar o conteúdo relacionado a uma investigação ou litígio antes de exportar Sistema do Office 365.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Usuários licenciados do Office 365 E5/a5/G5, Microsoft 365 E5/a5/G5, Microsoft 365 E5/a5/G5 conformidade e Office 365 Advanced Compliance podem se beneficiar da descoberta eletrônica avançada.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Um usuário se beneficia da descoberta eletrônica avançada quando o usuário é selecionado como um funcionário de dados (uma pessoa com controle administrativo de um documento ou arquivo eletrônico) para um caso.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos de descoberta eletrônica avançada são habilitados no nível do locatário para todos os usuários no locatário quando os administradores atribuem permissões de descoberta eletrônica no centro de conformidade do & de segurança.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

os administradores de descoberta eletrônica podem selecionar usuários específicos como responsáveis por dados para um caso usando a ferramenta de gerenciamento do responsáveis pela descoberta eletrônica avançada, conforme descrito em [Adicionar responsáveis a um caso de descoberta eletrônica avançada](https://docs.microsoft.com/office365/securitycompliance/compliance20/add-custodians-to-case).

## <a name="office-365-customer-key"></a>Chave de cliente do Office 365

Com a chave do cliente, você controla as chaves de criptografia da sua organização e configura o Office 365 para usá-las para criptografar seus dados em repouso nos data centers da Microsoft. Em outras palavras, a chave do cliente permite que você adicione uma camada de criptografia que pertença a você, usando suas próprias chaves. Os dados em repouso incluem dados do Exchange Online e do Skype for Business que são armazenados em caixas de correio e arquivos no SharePoint Online e no OneDrive for Business.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Usuários licenciados do Office 365 E5/a5/G5, Microsoft 365 E5/a5/G5, Microsoft 365 E5/a5/G5 conformidade e Office 365 Advanced Compliance podem se beneficiar da chave do cliente. Para obter o benefício completo da chave do cliente, você também deve ter uma assinatura do Azure Key Vault.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam da chave do cliente, mantendo seus dados em repouso criptografados na camada de aplicativo usando chaves de criptografia fornecidas, controladas e gerenciadas por sua própria organização.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

As chaves de criptografia de chave do cliente do Office 365 podem ser habilitadas para todos os dados armazenados nas caixas de correio do Exchange Online e do Skype for Business e arquivos do SharePoint Online e do OneDrive for Business. Para obter informações sobre como configurar a chave do cliente do Office 365 para criptografar seus dados em repouso, consulte [controle dos dados no Office 365 usando a chave do cliente](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Para atribuir chaves de criptografia a dados dentro de um locatário do Office 365 e/ou do Microsoft 365 para usuários licenciados, siga as políticas de implantação das chaves de criptografia de chave do cliente:

  - Para o SharePoint Online, os arquivos em um ou mais sites podem ser criptografados usando a chave do cliente, conforme descrito aqui: [configuração da chave do cliente para o SharePoint Online e o onedrive for Business](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key#office-365-setting-up-customer-key-for-sharepoint-online-and-onedrive-for-business).

  - Para o Exchange Online e o Skype for Business Online, as caixas de correio podem ser criptografadas usando a chave do cliente, conforme descrito aqui: [configuração da chave do cliente para o Exchange Online e o Skype for Business](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key#office-365-setting-up-customer-key-for-exchange-online-and-skype-for-business)

## <a name="office-365-customer-lockbox"></a>Sistema de Proteção de Dados do Cliente do Office 365

A Lockbox do cliente fornece uma camada adicional de controle, oferecendo aos clientes a capacidade de fornecer autorização de acesso explícito para operações de serviço. Ao demonstrar que os procedimentos estão em vigor para autorização explícita de acesso a dados, a Lockbox de clientes também pode ajudar as organizações a cumprir determinadas obrigações de conformidade, como HIPAA e FEDRAMP.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Usuários licenciados do Office 365 E5/a5/G5, Microsoft 365 E5/a5/G5, Microsoft 365 E5/a5/G5 conformidade e a conformidade avançada do Office 365 podem se beneficiar da Lockbox do cliente.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam da Lockbox de clientes garantindo que ninguém da Microsoft possa acessar seu conteúdo para executar uma operação de serviço sem a aprovação explícita do cliente. O cliente de lockbox traz o cliente para o fluxo de trabalho de aprovação para solicitações de acesso ao seu conteúdo. Ocasionalmente, os engenheiros da Microsoft estão envolvidos durante o processo de suporte para solucionar e corrigir problemas relatados pelo cliente. Na maioria dos casos, os problemas são corrigidos por meio de ferramentas abrangentes de telemetria e depuração que a Microsoft tem em vigor para seus serviços. No entanto, pode haver casos que exijam que um engenheiro da Microsoft acesse o conteúdo do cliente para determinar a causa raiz e corrigir o problema. A Lockbox do cliente exige que o engenheiro solicite acesso do cliente como uma etapa final no fluxo de trabalho de aprovação. Isso oferece às organizações a opção de aprovar ou negar essas solicitações, o que fornece a eles um controle direto sobre se um engenheiro da Microsoft pode acessar os dados de usuário final da organização.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Os administradores podem ativar os controles de lockbox do cliente no centro de administração do Microsoft 365. Para obter mais informações, consulte [Lockbox de cliente no Office 365](https://docs.microsoft.com/Office365/Admin/manage/customer-lockbox-requests). Quando a Lockbox do cliente está ativada, a Microsoft é obrigada a obter a aprovação de uma organização antes de acessar qualquer um de seus conteúdos.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

A Microsoft não se compromete a fornecer solicitações de aprovação de controle de acesso de lockbox de cliente para usuários que não estão licenciados. Com o tempo, as verificações de licença ou a ferramenta direcionada serão adicionadas ao Lockbox do cliente para garantir que o Lockbox do cliente seja atribuível a usuários licenciados.

## <a name="privileged-access-management-in-office-365"></a>Gerenciamento de acesso privilegiado no Office 365

O gerenciamento de acesso privilegiado (PAM) fornece controle de acesso granular sobre tarefas administrativas privilegiadas no Office 365. Depois de habilitar o PAM, os usuários precisarão solicitar acesso just-in-time por meio de um fluxo de trabalho de aprovação com alto escopo e limite de tempo para concluir tarefas elevadas e privilegiadas.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Usuários licenciados do Office 365 E5/a5/G5, Microsoft 365 E5/a5/G5, Microsoft 365 E5/a5/G5 conformidade e Office 365 Advanced Compliance podem se beneficiar do PAM.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Habilitar o PAM permite que as organizações operem com privilégios zero. Os usuários se beneficiam da camada adicional de defesa contra as vulnerabilidades decorrentes de um acesso administrativo em posição, que fornece acesso de unfettered a seus dados.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os recursos do PAM são habilitados no nível do locatário para todos os usuários dentro do locatário. Para obter informações sobre a configuração de políticas do PAM, consulte [Configuring Privileged Access Management in Office 365](https://docs.microsoft.com/office365/securitycompliance/privileged-access-management-configuration).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Os clientes podem gerenciar o PAM por usuário por meio de grupos de aprovadores e políticas de acesso, que podem ser aplicados a usuários licenciados. Para obter mais informações, consulte [Gerenciamento de acesso privilegiado no Office 365](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751).

## <a name="data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Prevenção de perda de dados para o Exchange Online, o SharePoint Online e o OneDrive for Business

Com a prevenção de perda de dados (DLP) para o Exchange Online, o SharePoint Online e o OneDrive for Business, as organizações podem identificar, monitorar e proteger automaticamente informações confidenciais entre emails e arquivos (incluindo arquivos armazenados no arquivo do Microsoft Teams repositórios).

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Usuários licenciados do Office 365 E3/a3/G3, Microsoft 365 Business, Microsoft 365 E3/a3/G3 e Office 365 Data Loss Prevention podem se beneficiar do DLP para o Exchange Online, o SharePoint Online e o OneDrive for Business.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam da DLP para o Exchange Online, o SharePoint Online e o OneDrive for Business quando seus emails e arquivos estão sendo inspecionados em busca de informações confidenciais, conforme configurado na política de DLP da organização.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, os emails do Exchange Online, os sites do SharePoint e as contas do OneDrive são *locais (cargas de trabalho) habilitados* para esses recursos de DLP para todos os usuários no locatário. Para obter mais informações sobre como usar políticas de DLP, consulte [Overview of Data Loss Prevention](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Os administradores podem personalizar locais (cargas de trabalho), usuários incluídos e usuários excluídos no centro de conformidade & segurança do Office 365, em**locais**de **prevenção** > de perda de dados.

## <a name="data-loss-prevention-for-teams-chat-and-channel-messages"></a>Prevenção de perda de dados para chat de equipes e mensagens de canal

Com a prevenção de perda de dados (DLP) para mensagens de chat e de canal do Teams, as organizações podem bloquear chats e mensagens de canal que contenham informações confidenciais, como informações financeiras, informações de identificação pessoal, informações relacionadas à saúde ou outras informações confidenciais.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Usuários licenciados do Office 365 E5/a5/G5, Microsoft 365 E5/a5/G5, Microsoft 365 E5/a5/G5 conformidade e Office 365 Advanced Compliance podem se beneficiar do DLP for Teams chat e mensagens de canal.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os remetentes se beneficiam com informações confidenciais em seus chat de saída e mensagens de canal inspecionadas para obter informações confidenciais, conforme configurado na política de DLP da organização.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Por padrão, as mensagens de chat e de canal do teams são um *local habilitado (carga de trabalho)* para esses recursos de DLP para todos os usuários no locatário. Para obter mais informações sobre como usar políticas de DLP, consulte [Overview of Data Loss Prevention](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Os administradores podem personalizar locais (cargas de trabalho), usuários incluídos e usuários excluídos no centro de conformidade & segurança do Office 365, em**locais**de **prevenção** > de perda de dados.

## <a name="information-barriers"></a>Barreiras de informações

As barreiras de informação são políticas que um administrador pode configurar para impedir que pessoas ou grupos se comuniquem entre si. Isso é útil se, por exemplo, um departamento estiver lidando com informações que não deveriam ser compartilhadas com outros departamentos, ou se um grupo precisar ser impedido de se comunicar com contatos externos. As políticas de barreira de informações também impedem pesquisas e descoberta. Isso significa que se você tentar se comunicar com alguém com o qual você não deve se comunicar, não encontrará esse usuário no seletor de pessoas.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Usuários licenciados do Office 365 E5/a5/G5, Microsoft 365 E5/a5/G5, Microsoft 365 E5/a5/G5 conformidade e Office 365 Advanced Compliance podem se beneficiar de barreiras de informação.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam dos recursos avançados de conformidade das barreiras de informação quando estão restritos à comunicação com outras pessoas. Por exemplo:

| Cenário                                                                                                                                                                                                              | Quem requer uma licença? |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| Dois grupos (grupo 1 e grupo 2) não podem se comunicar uns com os outros (ou seja, os usuários do grupo 1 estão restritos à comunicação com usuários do grupo 2 e os usuários do grupo 2 estão restritos à comunicação com usuários do grupo 1. | Usuários no grupo 1 e no grupo 2                    |
| Os usuários no grupo 1 estão restritos à comunicação com o restante da empresa.                                                                                                                                       | Usuários somente no grupo 1                                |
| O restante da empresa está restrito à comunicação com o grupo 1.                                                                                                                                                 | Todos os usuários, exceto aqueles no grupo 1                    |
| Os usuários do grupo 1 estão restritos à comunicação com usuários do grupo 2, mas os usuários do grupo 2 podem se comunicar com usuários do grupo 1.                                                                                              | Usuários somente no grupo 1                                |

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Administradores criem e gerenciem políticas de barreira de informações usando cmdlets do PowerShell no centro de conformidade do & de segurança. Os administradores devem receber a função de administrador global do Microsoft 365 Enterprise, administrador global do Office 365 ou administrador de conformidade para criar uma política de barreira de informações. Por padrão, essas políticas se aplicam a todos os usuários no locatário. Para obter mais informações sobre as barreiras de informação, confira [barreiras de informações no Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Os administradores podem personalizar locais (cargas de trabalho), usuários incluídos e usuários excluídos no centro de conformidade & segurança do Office 365. Por exemplo, se todos os usuários estiverem licenciados para o Office 365 E3, e nenhum for licenciado para o Office 365 Advanced Compliance/e5, não precisará criar nenhuma política de barreira de informações para a organização. Para obter mais informações, consulte [barreiras de informações no Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams).

## <a name="office-365-advanced-message-encryption"></a>Criptografia de mensagem avançada do Office 365

A criptografia avançada de mensagens ajuda os clientes a cumprir as obrigações de conformidade que exigem controles mais flexíveis sobre destinatários externos e seu acesso a emails criptografados. Com a criptografia avançada de mensagens, os administradores podem controlar emails confidenciais compartilhados fora da organização usando políticas automáticas que podem detectar tipos de informações confidenciais (por exemplo, informações de identificação pessoal ou IDs financeiras ou de integridade) ou Eles podem usar palavras-chave para aprimorar a proteção aplicando modelos de email personalizados e expirando o acesso a emails criptografados por meio de um portal da Web seguro. Além disso, os administradores podem controlar ainda mais os emails criptografados acessados externamente por meio de um portal da Web seguro revogando o acesso a qualquer momento.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Usuários licenciados do Office 365 E5/a5/G5, Microsoft 365 E5/a5/G5, Microsoft 365 E5/a5/G5 conformidade e Office 365 Advanced Compliance podem se beneficiar da criptografia avançada de mensagens.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os remetentes de mensagens se beneficiam do controle adicionado sobre emails confidenciais fornecidos pela criptografia avançada de mensagens.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Os administradores criam e gerenciam políticas avançadas de criptografia de mensagens no centro de administração do Exchange em regras de fluxo de emails. Por padrão, essas regras se aplicam a todos os usuários no locatário. Para obter mais informações sobre como configurar os novos recursos de criptografia de mensagens, consulte [configurar novos recursos de criptografia de mensagens do Office 365](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Os administradores devem aplicar regras de fluxo de email para a criptografia de mensagens avançada somente a usuários licenciados. Para obter mais informações sobre a definição de regras de fluxo de emails, consulte [definir regras de fluxo de email para criptografar mensagens de email no Office 365](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="supervision-policies"></a>Políticas de supervisão

As políticas de supervisão no Office 365 permitem que você capture comunicações de funcionários para verificação por revisores designados. Você pode definir políticas específicas que capturam emails internos e externos, Microsoft Teams ou comunicações de terceiros em sua organização. Os revisores podem, então, examinar as mensagens para garantir que estejam em conformidade com os padrões de mensagem da sua organização e as resolvem com o tipo de classificação.

### <a name="which-users-benefit-from-the-service"></a>Quais usuários se beneficiam do serviço?

Usuários licenciados do Office 365 E5/a5/G5, Microsoft 365 E5/a5/G5, Microsoft 365 E5/a5/G5 conformidade e Office 365 Advanced Compliance podem se beneficiar de políticas de supervisão.

### <a name="how-do-users-benefit-from-the-service"></a>Como os usuários se beneficiam do serviço?

Os usuários se beneficiam do serviço com suas comunicações monitoradas por políticas de supervisão.

### <a name="how-is-the-service-provisioneddeployed"></a>Como o serviço é provisionado/implantado?

Os administradores criam políticas de supervisão no centro de conformidade de & de segurança. Essas políticas definem quais comunicações e usuários estão sujeitos a análise na organização, definem condições personalizadas que as comunicações devem atender e especificam quem deve realizar revisões.
 
### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Como o serviço pode ser aplicado somente aos usuários no locatário que estão licenciados para o serviço?

Os administradores escolhem usuários ou grupos específicos para incluir em uma política de supervisão. Ao escolher um grupo, também é possível selecionar usuários específicos no grupo para excluir da política de supervisão. Para obter mais informações sobre políticas de supervisão, consulte [políticas de supervisão no Office 365](https://docs.microsoft.com/office365/SecurityCompliance/supervision-policies).
