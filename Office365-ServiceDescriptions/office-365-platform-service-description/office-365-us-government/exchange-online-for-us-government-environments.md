---
title: Exchange Online para ambientes governamentais dos EUA
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Este artigo fornece uma visão geral das diferenças de recursos entre a nuvem governamental dos EUA e a nuvem comercial, conforme listado na descrição do serviço do Exchange Online.
ms.openlocfilehash: cf1b995f8497ff2249504b195ecaf1b2f7c6f62c
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653283"
---
# <a name="exchange-online-for-us-government-environments"></a>Exchange Online para ambientes governamentais dos EUA

Este artigo fornece uma visão geral das diferenças de recursos entre a nuvem governamental dos EUA e a nuvem comercial, conforme listado na descrição do [serviço do Exchange Online.](../../exchange-online-service-description/exchange-online-service-description.md) O Exchange Online está disponível para os ambientes GCC (Government Community Cloud), GCC High e Department of Defense (DoD).

Para obter mais informações sobre a nuvem governamental, incluindo qualificação e compra, consulte [Microsoft 365 Government - how to buy](./microsoft-365-government-how-to-buy.md). Para comparar os planos do Office 365 Government, consulte [Office 365 Government plans](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements).

Para saber mais sobre os pontos de extremidade necessários ao gerenciar a conectividade de rede, consulte os pontos de extremidade do [Office 365 Government GCC High endpoints](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) ou pontos de extremidade do [Office 365 U.S. Government DoD](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business).

Além de aproveitar os recursos e recursos do Office 365, as organizações se beneficiam dos seguintes recursos exclusivos para os ambientes de nuvem do governo dos EUA:

- O conteúdo do cliente da sua organização é logicamente segregado do conteúdo do cliente nos serviços comerciais do Office 365.

- O conteúdo do cliente da sua organização é armazenado em repouso nos Estados Unidos.

- O acesso ao conteúdo do cliente da sua organização é restrito à equipes selecionadas da Microsoft.

- Os ambientes de nuvem do governo estão em conformidade com certificações e acreditações geralmente necessárias para clientes do Setor Público dos EUA.

É nossa intenção geral fornecer todos os recursos comerciais e funcionalidades do Exchange para o ambiente de nuvem governamental. Dito isso, alguns recursos não estão disponíveis devido aos requisitos dos clientes de nuvem do governo. Outros recursos estão chegando aos ambientes governamentais, mas ainda não estão disponíveis. Consulte as seções a seguir para saber mais sobre a disponibilidade de recursos nos ambientes de nuvem do governo.

## <a name="exchange-online-features"></a>Recursos do Exchange Online 

A tabela a seguir descreve se os recursos especificados do Exchange Online estão disponíveis nos ambientes GCC, GCC High e DoD. Quando há nuances em relação à instrução de suporte (ou falta dele), o contexto adicional é fornecido.<br><br>

| Recurso | CCG | CCG Alto | DoD | Principais considerações |
|:-----|:-----|:-----|:-----|:-----|
|**[Planejamento e implantação](../../exchange-online-service-description/planning-and-deployment.md)**|||||
|Suporte para implantação híbrida|Sim|Sim|Sim|Para coexistência com o Exchange Server local, a Microsoft requer a instalação de pelo menos um servidor de acesso para cliente Exchange Server 2013 (ou Exchange Server 2016).). Exchange Server 2010 e anteriores não são suportados.|
|Suporte para migração IMAP|Sim|Sim|Sim||
|Suporte para migração de substituição|Sim|Sim|Sim||
|Suporte para migração em estágios|Sim|Sim|Sim|Não há suporte para migração GSuite para GCC High e DoD. Para obter mais informações, <a href="/exchange/mailbox-migration/perform-g-suite-migration">consulte Perform a GSuite migration</a>.|
|**[Permissões](../../exchange-online-service-description/permissions.md)**|**GCC**|**CCG Alto**|**DoD**|**Principais considerações**|
|Permissões baseadas em função|Sim|Sim|Sim||
|Grupos de função|Sim|Sim|Sim||
|Diretivas de atribuição de função|Sim|Sim|Sim||
|**[Política e conformidade de mensagens](../../exchange-online-service-description/message-policy-and-compliance.md)**|**GCC**|**CCG Alto**|**DoD**|**Principais considerações**|
|Arquivamento de Caixas de Correio baseadas no Exchange Online|Sim|Sim|Sim||
|Arquivamento baseado em nuvem de caixas de correio no local|Sim|Sim|Sim||
|Messaging Records Management (MRM) |Sim|Sim|Sim||
|Políticas de retenção manual, rótulos e marcas |Sim|Sim|Sim||
|Criptografia de dados de tempo de parada (BitLocker)|Sim|Sim|Sim||
|IRM usando a Proteção de Informações do Azure|Sim|Sim|Sim|Para obter mais informações sobre limitações da AIP no GCC High e NoD, consulte <a href="/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description">Azure Information Protection Premium Government Service Description</a>.<br><br>A Proteção de Informações do Azure não está incluída no G1/F3, mas pode ser comprada como um complemento separado e permitirá os recursos de Gerenciamento de Direitos de Informação (IRM) com suporte. Alguns recursos da Proteção de Informações do Azure exigem uma assinatura do Office 365 ProPlus, que não está incluído no Office 365 Government G1 ou no Office 365 Government F3.|
|IRM usando Windows Server AD RMS|Sim|Sim|Sim|O Windows Server AD RMS é um servidor local que deve ser comprado e gerenciado separadamente para habilitar os recursos de IRM com suporte.|
|Criptografia de Mensagem do Office 365|Sim|Sim|Sim|Consulte o comportamento de Criptografia de Mensagens do Office 365 no limite [GCC High/DoD](#office-365-message-encryptionbehavior-across-gcc-highdod-boundary) neste artigo e Características exclusivas da Criptografia de Mensagens do <a href="/microsoft-365/compliance/ome-version-comparison#unique-characteristics-of-office-365-message-encryption-in-a-gcc-high-deployment">Office 365</a>em uma implantação GCC High , que documentam nuances comportamentais da Criptografia de Mensagens do Office 365 ao enviar mensagens entre usuários GCC High/DoD e não-GCC High/DoD.|
|Chave de Cliente|Sim|Sim|Sim|Requer plano de serviço G5.|
|S/MIME|Sim|Sim|Sim||
|Bloqueio In-loco e Retenção de Litígio|Sim|Sim|Sim|Requer plano de serviço G3 ou G5.|
|Descoberta Eletrônica In-loco|Sim|Sim|Sim||
|Regras do fluxo de email|Sim|Sim|Sim||
|Prevenção contra perda de dados|Sim|Sim|Sim|Requer plano de serviço G3 ou G5.|
|Registro em Diário|Sim|Sim|Sim||
|**[Proteção antispam e antimalware](../../exchange-online-service-description/anti-spam-and-anti-malware-protection.md)**|**GCC**|**CCG Alto**|**DoD**|**Principais considerações**|
|Proteção anti-spam integrado|Sim|Sim|Sim||
|Customize anti-spam policies|Sim|Sim|Sim||
|Proteção anti-malware integrado|Sim|Sim|Sim||
|Customize antimalware policies|Sim|Sim|Sim||
|Quarentena - gerenciamento de administrador|Sim|Sim|Sim||
|Quarentena - auto-gerenciamento de usuário final|Sim|Sim|Sim||
|Obter o Microsoft Defender para Office 365|Sim|Sim|Sim|Requer plano de serviço G5 (ou compra de complemento).<br><br>O anti-phishing para a representação de usuário e domínio e a inteligência de spoof ainda não estão disponíveis no GCC High e no DoD.|
|**[Fluxo de mensagens](../../exchange-online-service-description/mail-flow.md)**|**GCC**|**CCG Alto**|**DoD**|**Principais considerações**|
|Roteamento personalizado de emails de saída|Sim|Sim|Sim||
|Secure messaging with a trusted partner|Sim|Sim|Sim||
|Conditional mail routing|Sim|Sim|Sim||
|Adicionar um parceiro a uma lista segura de entrada|Sim|Sim|Sim||
|Roteamento de email híbrido|Sim|Sim|Sim||
|**[Destinatários](../../exchange-online-service-description/recipients.md)**|**GCC**|**CCG Alto**|**DoD**|**Principais considerações**|
|Alertas de capacidade|Sim|Sim|Sim||
|Email secundário|Sim|Sim|Sim||
|MailTips|Sim|Sim|Sim||
|Acesso de representante|Sim|Sim|Sim||
|Regras da Caixa de Entrada|Sim|Sim|Sim||
|Contas conectadas|Sim|Não|Não|Esse recurso não é suportado em GCC High ou DoD devido a restrições em conexões de saída para serviços de terceiros. Para obter mais informações sobre os recursos afetados, consulte [Conectividade com](#connectivity-with-third-party-services) serviços de terceiros neste artigo.|
|Caixas de correio inativas|Sim|Sim|Sim|Requer plano de serviço G3 ou G5.|
|Offline address book|Sim|Sim|Sim||
|Políticas do catálogo de endereços|Sim|Sim|Sim||
|Catálogo de endereços hierárquico|Sim|Sim|Sim||
|Listas de endereços e lista de endereços global|Sim|Sim|Sim||
|Grupos do Office 365|Sim|Sim|Sim|O acesso de convidados aos grupos do Office 365 não é suportado em ambientes GCC High e DoD. Para obter mais informações, consulte <a href="/azure/azure-government/documentation-government-services-securityandidentity">Azure Government Security + Identity</a>.|
|Grupos de Distribuição|Sim|Sim|Sim||
|Contatos externos (global)|Sim|Sim|Sim|Sujeito a limitações de colaboração de relacionamento organizacional em ambientes GCC High e DoD. |
|Vínculo de contato com redes sociais|Sim|Não|Não|Esse recurso não é suportado no GCC High ou no DoD.|
|Caixas de correio de recurso|Sim|Sim|Sim||
|Gerenciamento da sala de conferência|Sim|Sim|Sim||
|Respostas de Ausência Temporária|Sim|Sim|Sim||
|Compartilhamento de Calendário da Internet|Sim|Não|Não|No GCC High, a publicação/compartilhamento do Calendário da Internet funciona para conexão de entrada com calendários compartilhados por usuários do GCC High, mas não para usuários do GCC High que conectam saída a um calendário compartilhado fora do GCC High.<br><br>No compartilhamento do Calendário do DoD-Internet não há suporte devido ao requisito de listagem de conexões de entrada/saída nesse ambiente.|
|**[Recursos de relatórios e ferramentas de solução de problemas](../../exchange-online-service-description/reporting-features-and-troubleshooting-tools.md)**|**GCC**|**CCG Alto**|**DoD**|**Principais considerações**|
|Relatórios do Centro de administração do Microsoft 365|Sim|Sim|Não|Relatórios não disponíveis para DoD. Consulte a seção <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">recursos da plataforma</a> da descrição do serviço do Office 365 US Government para atualizações/disponibilidade atual.|
|Relatórios de Serviços Web|Sim|Sim|Não|Relatórios não disponíveis para DoD. Consulte a seção <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">recursos da plataforma</a> da descrição do serviço do Office 365 US Government para atualizações/disponibilidade atual.|
|Message trace|Sim|Sim|Sim||
|Relatórios de auditoria|Sim|Sim|Não|Relatórios não disponíveis para DoD. Consulte a seção <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">recursos da plataforma</a> da descrição do serviço do Office 365 US Government para atualizações/disponibilidade atual.|
|Relatórios de Unificação de Mensagens|Sim|Não|Não||
|**[Compartilhamento e colaboração](../../exchange-online-service-description/sharing-and-collaboration.md)**|**GCC**|**CCG Alto**|**DoD**|**Principais considerações**|
|Compartilhamento federado (incluindo publicação de calendário)|Sim|Sim|Sim|Existem limitações no GCC High e no DoD. Consulte [Federação de Livre/Ocupado](#freebusy-federation) neste artigo.|
|Caixas de correio local|Sim|Sim|Sim||
|Pastas públicas|Sim|Sim|Sim||
|**[Clientes e dispositivos móveis](../../exchange-online-service-description/clients-and-mobile-devices.md)**|**GCC**|**CCG Alto**|**DoD**|**Principais considerações**|
|Fazer na Web|Sim|Não|Não||
|Outlook para Windows|Sim|Sim|Sim|Para atender aos requisitos de conformidade GCC High e DoD, você deve estar executando pelo menos a versão 1803 do Office 365 ProPlus. O Office 365 ProPlus não está incluído no G1 ou F3.|
|Outlook na Web|Sim|Sim|Sim||
|Outlook para Mac|Sim|Sim|Sim|Para atender aos requisitos de conformidade GCC High e DoD, você deve estar executando pelo menos a versão 1803 do Office 365 ProPlus. O Office 365 ProPlus não está incluído no G1 ou F3.|
|Outlook para iOS e Android|Sim|Sim|Sim||
|Exchange ActiveSync|Sim|Sim|Sim||
|Basic Mobility and Security for Microsoft 365|Sim|Não|Não||
|POP e IMAP|Sim|Sim|Sim||
|SMTP|Sim|Sim|Sim||
|Suporte a aplicativos EWS|Sim|Sim|Sim||
|**[Serviços de mensagens de voz](../../exchange-online-service-description/voice-message-services.md)**|**GCC**|**CCG Alto**|**DoD**|**Principais considerações**|
|Caixa postal|Não|Não|Não|Não há suporte para integração de sistemas IP-PBX locais com a Unificação de Mensagens do Exchange Online.|
|Integração entre caixa postal e FAX de terceiros|Não|Não|Não|Não há suporte para integração de sistemas IP-PBX locais com a Unificação de Mensagens do Exchange Online.|
|Interoperabilidade de caixa postal de terceiros|Não|Não|Não|Não há suporte para integração de sistemas IP-PBX locais com a Unificação de Mensagens do Exchange Online.|
|Integração do Skype for Business|Sim|Sim|Sim||
|**[Alta disponibilidade e continuidade de negócios](../../exchange-online-service-description/high-availability-and-business-continuity.md)**|**GCC**|**CCG Alto**|**DoD**|**Principais considerações**|
|Replicação de caixa de correio em datacenters|Sim|Sim|Sim||
|Recuperação da caixa de correio excluída|Sim|Sim|Sim||
|Recuperação de itens excluídos|Sim|Sim|Sim||
|Recuperação de item único|Sim|Sim|Sim||
|**[Interoperabilidade, conectividade e compatibilidade](../../exchange-online-service-description/interoperability-connectivity-and-compatibility.md)**|**GCC**|**CCG Alto**|**DoD**|**Principais considerações**|
|Presença no OWA e no Outlook|Sim|Sim|Sim||
|Interoperabilidade do SharePoint|Sim|Sim|Sim||
|Suporte à conectividade EWS|Sim|Sim|Sim||
|Suporte a retransmissão SMTP|Sim|Sim|Sim||
|**[Instalação e administração do Exchange Online](../../exchange-online-service-description/exchange-online-setup-and-administration.md)**|**GCC**|**CCG Alto**|**DoD**|**Principais considerações**|
|Acesso ao portal do Microsoft Office 365|Sim|Sim|Não|Relatórios não disponíveis para DoD. Consulte a seção <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">recursos da plataforma</a> da descrição do serviço do Office 365 US Government para atualizações/disponibilidade atual.|
|Acesso ao centro de administração do Microsoft 365|Sim|Sim|Não|Relatórios não disponíveis para DoD. Consulte a seção <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">recursos da plataforma</a> da descrição do serviço do Office 365 US Government para atualizações/disponibilidade atual.|
|Acesso ao centro de administração do Exchange|Sim|Sim|Sim||
|Acesso Remoto do Windows PowerShell|Sim|Sim|Sim||
|Políticas activeSync para dispositivos móveis|Sim|Sim|Sim||
|Relatório de uso|Sim|Sim|Não|Relatórios não disponíveis para DoD. Consulte a seção <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">recursos da plataforma</a> da descrição do serviço do Office 365 US Government para atualizações/disponibilidade atual.|
|**[Estendendo o serviço - personalização, complementos e recursos](../../exchange-online-service-description/exchange-online-service-description.md)**|**GCC**|**CCG Alto**|**DoD**|**Principais considerações**|
|Complementos do Outlook e MAPI do Outlook|Sim|Sim|Sim|Apenas alguns complementos do OWA e do Outlook estão disponíveis no GCC High e no DoD. Consulte [Add-ins in Outlook and Outlook Web App](#add-insin-outlook-and-outlook-web-app) neste artigo.|

## <a name="feature-nuances-within-gcc-high-and-dod-environments"></a>Nuances de recursos em ambientes GCC High e DoD

### <a name="connectivity-with-third-party-services"></a>Conectividade com serviços de terceiros  

Os ambientes GCC High e DoD são ambientes restritos que exigem aprovação explícita e configuração de conexões de saída. Além disso, a Microsoft não pode acomodar solicitações para permitir o acesso de saída desses ambientes a serviços de nuvem comercial (Commercial Office 365, Google GSuite, Amazon Web Services e assim por diante).

Devido a essas restrições, os recursos que dependem dessa conectividade de saída dos ambientes GCC High/DoD geralmente não são suportados, incluindo:

- Contas conectadas - Os usuários não podem adicionar/sincronizar contas (Google, POP/IMAP e assim por diante).

- Suporte para provedores de armazenamento de arquivos de terceiros - Somente a conta do OneDrive for Business do usuário no *GCC High/DoD* pode ser acessada de dentro dos vários clientes do Outlook com a finalidade de anexar/compartilhar arquivos. Contas de armazenamento de terceiros (Dropbox, Box, Google Drive) não podem ser adicionadas.

- Conectividade com redes sociais, como Facebook ou LinkedIn.

### <a name="azure-active-directory-b2b-collaboration"></a>Colaboração B2B do Azure Active Directory

Atualmente, a colaboração B2B do Azure Active Directory só tem suporte entre organizações que estão na nuvem do Azure US Government e que ambas suportam a colaboração B2B

Além disso, os usuários B2B como convidados nos grupos do Office 365 não têm suporte em ambientes GCC High e DoD. 

Para obter mais informações e as atualizações mais recentes, consulte [Azure Government Security + Identity](/azure/azure-government/documentation-government-services-securityandidentity).

### <a name="office-365-message-encryption-behavior-across-gcc-highdod-boundary"></a>Comportamento de Criptografia de Mensagens do Office 365 no limite GCC High/DoD

Se você planeja usar a Criptografia de Mensagens do Office 365 em um ambiente GCC High, esteja ciente dessas características exclusivas sobre a experiência do destinatário:  

- Ao enviar emails criptografados do GCC High ou do DoD para destinatários no mesmo ambiente:
    
    - Os envios podem criptografar emails manualmente no Outlook para PC e Mac e Outlook na Web, ou as organizações podem configurar uma política para criptografar emails usando regras de fluxo de emails do Exchange.
    
    - Os destinatários dentro do GCC High/DoD recebem a mesma experiência de leitura em linha no Outlook para PC e Mac e Outlook na Web como todos os outros usuários do Office 365.

<!-- end list -->

- Ao enviar emails criptografados do GCC High ou do DoD para destinatários fora desse ambiente (incluindo GCC e Comercial):
    
    - Os envios dentro do GCC High/DoD podem enviar emails criptografados fora do limite GCC High/DoD.
    
    - Todos os destinatários fora do GCC High/DoD, incluindo usuários comerciais do Office 365, Outlook.com usuários e outros usuários de outros provedores de email, recebem um email de wrapper. Esse email de wrapper redireciona o destinatário para o Portal OME onde o destinatário pode ler e responder à mensagem.

Para obter mais informações e as atualizações mais recentes, consulte [Comparar versões do OME](/microsoft-365/compliance/ome-version-comparison).

### <a name="freebusy-federation"></a>Federação de livre/ocupado

O compartilhamento federado, incluindo informações de livre/ocupado, está atualmente sujeito a várias limitações importantes nos ambientes GCC High e DoD.

No ambiente GCC High:

- A confiança de federação (incluindo o compartilhamento bidirecional de livre/ocupado) é suportada entre locatários no GCC High e por meio da coexistência híbrida (Exchange 2013 ou posterior).

- O compartilhamento federado não é suportado entre locatários no GCC High e GCC ou comercial do Office 365. As conexões de saída do ambiente GCC High para nuvens comerciais (incluindo GCC e comercial do Office 365) não são permitidas no momento. Como resultado, os usuários do GCC High não conseguem fazer a solicitação de saída necessária ao GCC/comercial para acessar informações de calendário compartilhado.

No ambiente DoD:

  - No momento, a confiança de federação (incluindo o compartilhamento de livre/ocupado) é suportada apenas entre locatários no ambiente do DoD. Não há suporte entre locatários do DoD e GCC ou locatários comerciais.

### <a name="client-configuration"></a>Configuração do cliente

Etapas adicionais estão envolvidas na implantação e configuração do Office ProPlus (incluindo o Outlook). Para obter uma descrição detalhada dessas etapas, consulte [Guidance for deploying Microsoft 365 Apps for enterprise in a GCC High or DoD environment](/deployoffice/deploy-microsoft-365-apps-gcc-high-dod).

O Outlook para iOS e Android também está disponível para ambientes GCC High e DoD. Para saber mais sobre limitações de recursos e gerenciamento nesses ambientes, consulte [Using Outlook for iOS and Android in the Government Community Cloud](/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud).

### <a name="add-ins-in-outlook-and-outlook-web-app"></a>Complementos no Outlook e no Outlook Web App  

Apenas alguns complementos do OWA e do Outlook estão disponíveis no GCC High e no DoD. Meus Modelos e Reuniões Sugeridas estão disponíveis e devem funcionar. Somente os cinco complementos OWA padrão são suportados. A integração com aplicativos de terceiros é possível, no entanto, essas integrações não são cobertas pelas promessas de conformidade da Microsoft para GCC High ou DoD. Os clientes devem se familiarizar com práticas de tratamento de dados de terceiros e promessas de conformidade antes de configurar o complemento para sua organização.

## <a name="feature-nuances-within-gcc-environments-for-microsoft-to-do"></a>Nuances de recursos em ambientes GCC para Microsoft To Do

| Recurso | Descrição | WW | Disponibilidade no GCC |
|:-----|:-----|:-----|:-----|
|Plataformas com suporte|Web, Android, iOS, Mac, Windows|Todos|Somente Web|
|Suporte para hub M365|Integrações com Outlook, Teams, Planner|Todos|Outlook, Planner (Teams para estar disponível com o aplicativo de tarefas do Teams)|
|Migração Wunderlist|Permitir que os usuários wunderlist migrem dados para Fazer na Web|Sim|Não|
|Notificação por Push|Enviar notificações por push para usuários finais para lembretes etc.|Sim|Não|
|Suporte a helpshift|Usar a interface de ajuda para criar solicitação de suporte|Sim|Não|
|Meu Dia|Planejar seu dia|Sim|Sim|
|Lista planejada|Consulte todas as tarefas com data de vencimento|Sim|Sim|
|Atribuído à sua lista|Todas as tarefas atribuídas a você em uma lista compartilhada, Planner ou WXP (futuro)|Sim|Sim|
|Email sinalizado|Consulte emails sinalizados no Outlook como tarefas|Sim|Sim|
|Suporte a várias contas|Usar conta de escritório e home em um painel|Sim|Sim|
|Compartilhamento de lista|Compartilhar listas com colegas na mesma organização|Sim|Sim|
|Compartilhamento cruzado de locatários|Compartilhar lista de tarefas fora da sua organização|Sim|Não|
|Lembretes e recorrência|Definir lembretes para sua tarefa |Sim|Sim|

*Quaisquer outros recursos não mencionados estão disponíveis em ambos os ambientes.