---
title: Exchange Online ambientes governamentais dos EUA
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: Este artigo fornece uma visão geral das diferenças de recursos entre a nuvem governamental dos EUA e a nuvem comercial, conforme listado na descrição Exchange Online serviço.
ms.openlocfilehash: 674d2e50b11624f206797cfef97883e9fda87df5
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/24/2021
ms.locfileid: "59671070"
---
# <a name="exchange-online-for-us-government-environments"></a>Exchange Online ambientes governamentais dos EUA

Este artigo fornece uma visão geral das diferenças de recursos entre a nuvem governamental dos EUA e a nuvem comercial, conforme listado na descrição [Exchange Online serviço.](../../exchange-online-service-description/exchange-online-service-description.md) Exchange Online está disponível para os ambientes Nuvem da Comunidade Governamental (GCC), GCC Alta e Departamento de Defesa (DoD).

Para obter mais informações sobre a nuvem governamental, incluindo qualificação e compras, [consulte Microsoft 365 Government - how to buy](./microsoft-365-government-how-to-buy.md). Para comparar Office 365 Government planos, consulte [Office 365 Government planos](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements).

Para saber mais sobre os pontos de extremidade necessários ao gerenciar [Office 365](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) conectividade de rede, consulte os pontos de extremidade do GCC [Office 365 DoD](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)do governo dos EUA.

Além de aproveitar os recursos e recursos do Office 365, as organizações se beneficiam dos seguintes recursos exclusivos para os ambientes de nuvem do governo dos EUA:

- O conteúdo do cliente da sua organização é logicamente segregado do conteúdo do cliente nos serviços de Office 365 comerciais.

- O conteúdo do cliente da sua organização é armazenado em repouso nos Estados Unidos.

- O acesso ao conteúdo do cliente da sua organização é restrito à equipes selecionadas da Microsoft.

- Os ambientes de nuvem do governo estão em conformidade com certificações e acreditações geralmente necessárias para clientes do Setor Público dos EUA.

É nossa intenção geral fornecer todos os recursos Exchange comerciais e funcionalidades para o ambiente de nuvem governamental. Dito isso, alguns recursos não estão disponíveis devido aos requisitos dos clientes de nuvem do governo. Outros recursos estão chegando aos ambientes governamentais, mas ainda não estão disponíveis. Consulte as seções a seguir para saber mais sobre a disponibilidade de recursos nos ambientes de nuvem do governo.

## <a name="exchange-online-features"></a>Recursos do Exchange Online 

A tabela a seguir descreve se os recursos Exchange Online especificados estão disponíveis nos ambientes GCC, GCC Alta e DoD. Quando há nuances em relação à instrução de suporte (ou falta dele), o contexto adicional é fornecido.<br><br>

| Recurso | CCG | CCG Alto | DoD | Principais considerações |
|:-----|:-----|:-----|:-----|:-----|
|**[Planejamento e implantação](../../exchange-online-service-description/planning-and-deployment.md)**|||||
|Suporte para implantação híbrida|Sim|Sim|Sim|Para coexistência com Exchange Server local, a Microsoft requer a instalação de pelo menos um servidor de Acesso para Cliente Exchange Server 2013 (ou Exchange Server 2016).). Exchange Server 2010 e anteriores não são suportados.|
|Suporte para migração IMAP|Sim|Sim|Sim||
|Suporte para migração de substituição|Sim|Sim|Sim||
|Suporte para migração em estágios|Sim|Sim|Sim|A migração GSuite não é suportada para GCC Alta e DoD. Para obter mais informações, <a href="/exchange/mailbox-migration/perform-g-suite-migration">consulte Perform a GSuite migration</a>.|
|**[Permissões](../../exchange-online-service-description/permissions.md)**|**GCC**|**GCC Alta**|**DoD**|**Principais considerações**|
|Permissões baseadas em função|Sim|Sim|Sim||
|Grupos de função|Sim|Sim|Sim||
|Diretivas de atribuição de função|Sim|Sim|Sim||
|**[Política e conformidade de mensagens](../../exchange-online-service-description/message-policy-and-compliance.md)**|**GCC**|**GCC Alta**|**DoD**|**Principais considerações**|
|Arquivamento de Caixas de Correio baseadas no Exchange Online|Sim|Sim|Sim||
|Arquivamento baseado em nuvem de caixas de correio no local|Sim|Sim|Sim||
|Messaging Records Management (MRM) |Sim|Sim|Sim||
|Políticas de retenção manual, rótulos e marcas |Sim|Sim|Sim||
|Criptografia de dados de tempo de parada (BitLocker)|Sim|Sim|Sim||
|IRM usando a Proteção de Informações do Azure|Sim|Sim|Sim|Para obter mais informações sobre limitações da AIP no GCC High e DoD, consulte <a href="/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description">Azure Information Protection Premium Government Service Description</a>.<br><br>A Proteção de Informações do Azure não está incluída no G1/F3, mas pode ser comprada como um complemento separado e permitirá os recursos de Gerenciamento de Direitos de Informação (IRM) com suporte. Alguns recursos da Proteção de Informações do Azure exigem uma assinatura Office 365 ProPlus, que não está incluída no Office 365 para o Governo G1 ou Office 365 Government F3.|
|IRM usando Windows Server AD RMS|Sim|Sim|Sim|Windows Server AD O RMS é um servidor local que deve ser comprado e gerenciado separadamente para habilitar os recursos de IRM com suporte.|
|Criptografia de Mensagem do Office 365|Sim|Sim|Sim|Consulte Criptografia de Mensagens do Office 365 comportamento no limite de [GCC High/DoD](#office-365-message-encryptionbehavior-across-gcc-highdod-boundary) neste artigo e Características exclusivas do Criptografia de Mensagens do Office 365 em uma implantação do <a href="/microsoft-365/compliance/ome-version-comparison#unique-characteristics-of-office-365-message-encryption-in-a-gcc-high-deployment">GCC High</a>, que documentam nuances comportamentais do Criptografia de Mensagens do Office 365 ao enviar mensagens entre usuários do GCC High/DoD e usuários não GCC High/DoD.|
|Chave de Cliente|Sim|Sim|Sim|Requer plano de serviço G5.|
|S/MIME|Sim|Sim|Sim||
|Bloqueio In-loco e Retenção de Litígio|Sim|Sim|Sim|Requer plano de serviço G3 ou G5.|
|Descoberta Eletrônica In-loco|Sim|Sim|Sim||
|Regras do fluxo de email|Sim|Sim|Sim||
|Prevenção contra perda de dados|Sim|Sim|Sim|Requer plano de serviço G3 ou G5.|
|Registro em Diário|Sim|Sim|Sim||
|**[Proteção antispam e antimalware](../../exchange-online-service-description/anti-spam-and-anti-malware-protection.md)**|**GCC**|**GCC Alta**|**DoD**|**Principais considerações**|
|Proteção anti-spam integrado|Sim|Sim|Sim||
|Customize anti-spam policies|Sim|Sim|Sim||
|Proteção anti-malware integrado|Sim|Sim|Sim||
|Customize antimalware policies|Sim|Sim|Sim||
|Quarentena - gerenciamento de administrador|Sim|Sim|Sim||
|Quarentena - auto-gerenciamento de usuário final|Sim|Sim|Sim||
|Microsoft Defender para Office 365|Sim|Sim|Sim|Requer plano de serviço G5 (ou compra de complemento).<br><br>O anti-phishing para a representação de usuário e domínio e a inteligência de spoof ainda não estão disponíveis no GCC High e DoD.|
|**[Fluxo de mensagens](../../exchange-online-service-description/mail-flow.md)**|**GCC**|**GCC Alta**|**DoD**|**Principais considerações**|
|Roteamento personalizado de emails de saída|Sim|Sim|Sim||
|Secure messaging with a trusted partner|Sim|Sim|Sim||
|Conditional mail routing|Sim|Sim|Sim||
|Adicionar um parceiro a uma lista segura de entrada|Sim|Sim|Sim||
|Roteamento de email híbrido|Sim|Sim|Sim||
|**[Destinatários](../../exchange-online-service-description/recipients.md)**|**GCC**|**GCC Alta**|**DoD**|**Principais considerações**|
|Alertas de capacidade|Sim|Sim|Sim||
|Email secundário|Sim|Sim|Sim||
|MailTips|Sim|Sim|Sim||
|Acesso de representante|Sim|Sim|Sim||
|Regras da caixa de entrada|Sim|Sim|Sim||
|Contas conectadas|Sim|Não|Não|Esse recurso não é suportado no GCC High ou DoD devido a restrições em conexões de saída para serviços de terceiros. Para obter mais informações sobre os recursos afetados, consulte [Conectividade com](#connectivity-with-third-party-services) serviços de terceiros neste artigo.|
|Caixas de correio inativas|Sim|Sim|Sim|Requer plano de serviço G3 ou G5.|
|Offline address book|Sim|Sim|Sim||
|Políticas do catálogo de endereços|Sim|Sim|Sim||
|Catálogo de endereços hierárquico|Sim|Sim|Sim||
|Listas de endereços e lista de endereços global|Sim|Sim|Sim||
|Grupos do Office 365|Sim|Sim|Sim|O acesso de convidados Office 365 grupos não é suportado GCC ambientes High e DoD. Para obter mais informações, consulte <a href="/azure/azure-government/documentation-government-services-securityandidentity">Azure Government Security + Identity</a>.|
|Grupos de Distribuição|Sim|Sim|Sim||
|Contatos externos (global)|Sim|Sim|Sim|Sujeito a limitações de colaboração de relacionamento organizacional GCC ambientes High e DoD. |
|Vínculo de contato com redes sociais|Sim|Não|Não|Esse recurso não é suportado em GCC High ou DoD.|
|Caixas de correio de recurso|Sim|Sim|Sim||
|Gerenciamento da sala de conferência|Sim|Sim|Sim||
|Respostas de Ausência Temporária|Sim|Sim|Sim||
|Compartilhamento de Calendário da Internet|Sim|Não|Não|No GCC High, a publicação/compartilhamento do Calendário da Internet funciona para conexão de entrada com calendários compartilhados por usuários do GCC High, mas não para usuários do GCC High que se conectam a um calendário compartilhado fora do GCC High.<br><br>No compartilhamento do Calendário do DoD-Internet não há suporte devido ao requisito de listagem de conexões de entrada/saída nesse ambiente.|
|**[Recursos de relatórios e ferramentas de solução de problemas](../../exchange-online-service-description/reporting-features-and-troubleshooting-tools.md)**|**GCC**|**GCC Alta**|**DoD**|**Principais considerações**|
|Relatórios do Centro de administração do Microsoft 365|Sim|Sim|Não|Relatórios não disponíveis para DoD. Consulte a seção <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">recursos da plataforma</a> da descrição do serviço Office 365 US Government para atualizações/disponibilidade atual.|
|Relatórios de Serviços Web|Sim|Sim|Não|Relatórios não disponíveis para DoD. Consulte a seção <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">recursos da plataforma</a> da descrição do serviço Office 365 US Government para atualizações/disponibilidade atual.|
|Message trace|Sim|Sim|Sim||
|Relatórios de auditoria|Sim|Sim|Não|Relatórios não disponíveis para DoD. Consulte a seção <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">recursos da plataforma</a> da descrição do serviço Office 365 US Government para atualizações/disponibilidade atual.|
|Relatórios de Unificação de Mensagens|Sim|Não|Não||
|**[Compartilhamento e colaboração](../../exchange-online-service-description/sharing-and-collaboration.md)**|**GCC**|**GCC Alta**|**DoD**|**Principais considerações**|
|Compartilhamento federado (incluindo publicação de calendário)|Sim|Sim|Sim|As limitações existem GCC Alta e DoD. Consulte [Federação de Livre/Ocupado](#freebusy-federation) neste artigo.|
|Caixas de correio local|Sim|Sim|Sim||
|Pastas públicas|Sim|Sim|Sim||
|**[Clientes e dispositivos móveis](../../exchange-online-service-description/clients-and-mobile-devices.md)**|**GCC**|**GCC Alta**|**DoD**|**Principais considerações**|
|To Do na Web|Sim|Não|Não||
|Outlook para Windows|Sim|Sim|Sim|Para atender GCC requisitos de conformidade high e DoD, você deve estar executando pelo menos a versão 1803 do Office 365 ProPlus. Office 365 ProPlus não está incluído no G1 ou F3.|
|Outlook na Web<sup>1</sup>|Sim|Sim|Sim||
|Outlook para Mac|Sim|Sim|Sim|Para atender GCC requisitos de conformidade high e DoD, você deve estar executando pelo menos a versão 1803 do Office 365 ProPlus. Office 365 ProPlus não está incluído no G1 ou F3.|
|Outlook para iOS e Android|Sim|Sim|Sim||
|Exchange ActiveSync|Sim|Sim|Sim||
|Basic Mobility and Security for Microsoft 365|Sim|Não|Não||
|POP e IMAP|Sim|Sim|Sim||
|SMTP|Sim|Sim|Sim||
|Suporte a aplicativos EWS|Sim|Sim|Sim||
|**[Serviços de mensagens de voz](../../exchange-online-service-description/voice-message-services.md)**|**GCC**|**GCC Alta**|**DoD**|**Principais considerações**|
|Caixa postal|Não|Não|Não|Não há suporte para integração de sistemas IP-PBX locais Exchange Online Unificação de Mensagens.|
|Integração entre caixa postal e FAX de terceiros|Não|Não|Não|Não há suporte para integração de sistemas IP-PBX locais Exchange Online Unificação de Mensagens.|
|Interoperabilidade de caixa postal de terceiros|Não|Não|Não|Não há suporte para integração de sistemas IP-PBX locais Exchange Online Unificação de Mensagens.|
|Skype for Business integração|Sim|Sim|Sim||
|**[Alta disponibilidade e continuidade de negócios](../../exchange-online-service-description/high-availability-and-business-continuity.md)**|**GCC**|**GCC Alta**|**DoD**|**Principais considerações**|
|Replicação de caixa de correio em datacenters|Sim|Sim|Sim||
|Recuperação da caixa de correio excluída|Sim|Sim|Sim||
|Recuperação de itens excluídos|Sim|Sim|Sim||
|Recuperação de item único|Sim|Sim|Sim||
|**[Interoperabilidade, conectividade e compatibilidade](../../exchange-online-service-description/interoperability-connectivity-and-compatibility.md)**|**GCC**|**GCC Alta**|**DoD**|**Principais considerações**|
|Presença no OWA e Outlook|Sim|Sim|Sim||
|SharePoint interoperabilidade|Sim|Sim|Sim||
|Suporte à conectividade EWS|Sim|Sim|Sim||
|Suporte a retransmissão SMTP|Sim|Sim|Sim||
|**[Instalação e administração do Exchange Online](../../exchange-online-service-description/exchange-online-setup-and-administration.md)**|**GCC**|**GCC Alta**|**DoD**|**Principais considerações**|
|Acesso ao portal do Microsoft Office 365|Sim|Sim|Não|Relatórios não disponíveis para DoD. Consulte a seção <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">recursos da plataforma</a> da descrição do serviço Office 365 US Government para atualizações/disponibilidade atual.|
|Centro de administração do Microsoft 365 acesso|Sim|Sim|Não|Relatórios não disponíveis para DoD. Consulte a seção <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">recursos da plataforma</a> da descrição do serviço Office 365 US Government para atualizações/disponibilidade atual.|
|Acesso ao centro de administração do Exchange|Sim|Sim|Sim||
|Acesso Remoto do Windows PowerShell|Sim|Sim|Sim||
|Políticas activeSync para dispositivos móveis|Sim|Sim|Sim||
|Relatório de uso|Sim|Sim|Não|Relatórios não disponíveis para DoD. Consulte a seção <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">recursos da plataforma</a> da descrição do serviço Office 365 US Government para atualizações/disponibilidade atual.|
|**[Estendendo o serviço - personalização, complementos e recursos](../../exchange-online-service-description/exchange-online-service-description.md)**|**GCC**|**GCC Alta**|**DoD**|**Principais considerações**|
|Outlook e Outlook MAPI|Sim|Sim|Sim|Somente alguns OWA e Outlook estão disponíveis no GCC High e DoD. Consulte [Add-ins in Outlook e Outlook Web App](#add-insin-outlook-and-outlook-web-app) neste artigo.|

<sup>1</sup> Outlook na Web pode ser usado em cenários quando o Outlook para Windows não consegue exibir as mensagens protegidas por IRM devido a restrições de limites cruzados (GCC cenários High /Non-GCC High).

## <a name="feature-nuances-within-gcc-high-and-dod-environments"></a>Nuances de recursos em GCC ambientes High e DoD

### <a name="connectivity-with-third-party-services"></a>Conectividade com serviços de terceiros  

Tanto GCC ambientes High quanto DoD são ambientes restritos que exigem aprovação explícita e configuração de conexões de saída. Além disso, a Microsoft não pode acomodar solicitações para permitir o acesso de saída desses ambientes a serviços de nuvem comercial (serviços comerciais Office 365, Google GSuite, Amazon Web Services e assim por diante).

Devido a essas restrições, os recursos que dependem dessa conectividade de saída do GCC ambientes High/DoD geralmente não são suportados, incluindo:

- Contas conectadas - Os usuários não podem adicionar/sincronizar contas (Google, POP/IMAP e assim por diante).

- Suporte para provedores de armazenamento de arquivos de terceiros - Somente a conta de OneDrive for Business do usuário no *GCC High/DoD* pode ser acessada de dentro dos vários clientes Outlook com a finalidade de anexar/compartilhar arquivos. Contas de armazenamento de terceiros (Dropbox, Box, Google Drive) não podem ser adicionadas.

- Conectividade com redes sociais, como Facebook ou LinkedIn.

### <a name="azure-active-directory-b2b-collaboration"></a>Azure Active Directory Colaboração B2B

Azure Active Directory No momento, a colaboração B2B só tem suporte entre organizações que estão na nuvem do Azure US Government e que suportam a colaboração B2B

Além disso, os usuários B2B como convidados Office 365 grupos não são suportados em ambientes high GCC DoD e High. 

Para obter mais informações e as atualizações mais recentes, consulte [Azure Government Security + Identity](/azure/azure-government/documentation-government-services-securityandidentity).

### <a name="office-365-message-encryption-behavior-across-gcc-highdod-boundary"></a>Criptografia de Mensagens do Office 365 comportamento no GCC limite High/DoD

Se você planeja usar o Criptografia de Mensagens do Office 365 em um ambiente GCC Alto, esteja ciente dessas características exclusivas sobre a experiência do destinatário:  

- Ao enviar emails criptografados do GCC High ou DoD para destinatários no mesmo ambiente:
    
    - Os envios podem criptografar emails manualmente no Outlook para PC e Mac e Outlook na Web, ou as organizações podem configurar uma política para criptografar emails usando Exchange de fluxo de emails.
    
    - Os destinatários dentro GCC High/DoD recebem a mesma experiência de leitura em linha no Outlook para PC e Mac e Outlook na Web como todos os outros Office 365 usuários.

<!-- end list -->

- Ao enviar emails criptografados do GCC High para destinatários fora desse ambiente (incluindo DoD, GCC e Comercial):

    - Os senders dentro GCC High podem enviar emails criptografados fora do limite GCC Alto.
    - Todos os destinatários fora do GCC High, incluindo usuários do DoD, Office 365 comerciais, usuários Outlook.com e outros usuários de outros provedores de email, recebem um email de wrapper. Esse email de wrapper redireciona o destinatário para o Portal OME onde o destinatário pode ler e responder mensagens.

Para obter mais informações e as atualizações mais recentes, consulte [Comparar versões do OME](/microsoft-365/compliance/ome-version-comparison).

### <a name="freebusy-federation"></a>Federação de livre/ocupado

O compartilhamento federado, incluindo informações de livre/ocupado, está atualmente sujeito a várias limitações importantes nos ambientes do DoD.

No ambiente GCC Alto:

- A confiança de federação (incluindo o compartilhamento bidirecional de livre/ocupado) é suportada entre locatários no GCC High, para locatários em GCC e nuvens comerciais e por meio da coexistência híbrida (Exchange 2013 ou posterior).

No ambiente DoD:

  - No momento, a confiança de federação (incluindo o compartilhamento de livre/ocupado) é suportada apenas entre locatários no ambiente do DoD. Não há suporte entre locatários do DoD e GCC, GCC Alto ou locatários comerciais.

### <a name="client-configuration"></a>Configuração do cliente

Etapas adicionais estão envolvidas na implantação e configuração Office ProPlus (incluindo Outlook). Para obter uma descrição detalhada dessas etapas, consulte [Guidance for deploying Microsoft 365 Apps para Grandes Empresas in a GCC High or DoD environment](/deployoffice/deploy-microsoft-365-apps-gcc-high-dod).

Outlook para iOS e Android também está disponível para GCC ambientes High e DoD. Para saber mais sobre limitações de recursos e gerenciamento nesses ambientes, consulte [Using Outlook for iOS](/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud)and Android in the Nuvem da Comunidade Governamental .

### <a name="add-ins-in-outlook-and-outlook-web-app"></a>Os Outlook e Outlook Web App  

Somente alguns OWA e Outlook estão disponíveis no GCC High e DoD. Meus Modelos e Reuniões Sugeridas estão disponíveis e devem funcionar. Somente os cinco complementos OWA padrão são suportados. A integração com aplicativos de terceiros é possível, no entanto, essas integrações não são cobertas pelas promessas de conformidade da Microsoft para GCC Alta ou DoD. Os clientes devem se familiarizar com práticas de tratamento de dados de terceiros e promessas de conformidade antes de configurar o complemento para sua organização.

## <a name="feature-nuances-within-gcc-environments-for-microsoft-to-do"></a>Nuances de recursos em GCC ambientes para Microsoft To Do

| Recurso | Descrição | WW | Disponibilidade no GCC |
|:-----|:-----|:-----|:-----|
|Plataformas com suporte|Web, Android, iOS, Mac, Windows|Todos|Somente Web|
|Suporte para hub M365|Integrações com Outlook, Teams, Planner|Todos|Outlook, Planner (Teams estar disponível com Teams aplicativo de tarefas)|
|Migração Wunderlist|Permitir que os usuários wunderlist migrem dados para To Do na Web|Sim|Não|
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