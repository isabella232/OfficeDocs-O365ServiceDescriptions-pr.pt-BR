---
title: Exchange Online para ambientes do governo dos EUA
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Este artigo fornece uma visão geral das diferenças de recursos entre a nuvem do governo dos EUA e a nuvem comercial, conforme listado na descrição do serviço do Exchange Online.
ms.openlocfilehash: e8e552076f7e318db9a4de17ad605d3c260b2295
ms.sourcegitcommit: 09b52ff24e7153457c7b4f775ea809079103f6e9
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 11/10/2020
ms.locfileid: "48988078"
---
# <a name="exchange-online-for-us-government-environments"></a>Exchange Online para ambientes do governo dos EUA

Este artigo fornece uma visão geral das diferenças de recursos entre a nuvem do governo dos EUA e a nuvem comercial, conforme listado na [Descrição do serviço do Exchange Online](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-service-description). O Exchange Online está disponível para os ambientes GCC (nuvem da Comunidade governamental), GCC alto e departamento de defesa (DoD).

Para obter mais informações sobre a nuvem governamental, incluindo qualificação e aquisição, consulte [Microsoft 365 governamentais-como comprar](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy). Para comparar os planos do governo do Office 365, confira [office 365 governamental Plans](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements).

Para saber mais sobre pontos de extremidade necessários ao gerenciar a conectividade de rede, confira os pontos de extremidade do [office 365 governo dos EUA](https://docs.microsoft.com/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) ou do [Office 365 governo dos EUA](https://docs.microsoft.com/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business).

Além de aproveitar os recursos e as funcionalidades do Office 365, as organizações se beneficiam dos seguintes recursos exclusivos dos ambientes de nuvem do governo dos EUA:

- O conteúdo do cliente da sua organização é logicamente separado do conteúdo do cliente nos serviços comerciais do Office 365.

- O conteúdo do cliente da sua organização é armazenado em repouso nos Estados Unidos.

- O acesso ao conteúdo do cliente da sua organização é restrito à equipes selecionadas da Microsoft.

- Os ambientes de nuvem governamentais estão em conformidade com certificações e procertificações geralmente necessárias para os clientes do setor público dos EUA.

É nossa intenção geral fornecer todos os recursos comerciais e a funcionalidade do Exchange para o ambiente de nuvem do governo. Dito isso, alguns recursos não estão disponíveis devido aos requisitos de clientes de nuvem governamentais. Outros recursos estão chegando aos ambientes governamentais, mas ainda não estão disponíveis. Consulte as seções a seguir para saber mais sobre a disponibilidade de recursos nos ambientes de nuvem governamentais.

## <a name="exchange-online-features"></a>Recursos do Exchange Online 

A tabela a seguir descreve se os recursos especificados do Exchange Online estão disponíveis nos ambientes GCC, GCC High e DoD. Quando há nuances em relação à declaração de suporte (ou ausência deles), é fornecido um contexto adicional.<br><br>

| Recurso | CCG | CCG Alto | DoD | Principais considerações |
|:-----|:-----|:-----|:-----|:-----|
|**[Planejamento e implantação](../../exchange-online-service-description/planning-and-deployment.md)**|||||
|Suporte para implantação híbrida|Sim|Sim|Sim|Para a coexistência com o Exchange Server local, a Microsoft exige a instalação de pelo menos um servidor de acesso para cliente do Exchange Server 2013 (ou o Exchange Server 2016.). Não há suporte para o Exchange Server 2010 e versões anteriores.|
|Suporte para migração IMAP|Sim|Sim|Sim||
|Suporte para migração de substituição|Sim|Sim|Sim||
|Suporte para migração em estágios|Sim|Sim|Sim|A migração do GSuite não é suportada para o GCC elevado e o DoD. Para obter mais informações, consulte <a href="https://docs.microsoft.com/exchange/mailbox-migration/perform-g-suite-migration">perform a GSuite Migration</a>.|
|**[Permissões](../../exchange-online-service-description/permissions.md)**|**GCC**|**CCG Alto**|**DoD**|**Principais considerações**|
|Permissões baseadas em função|Sim|Sim|Sim||
|Grupos de função|Sim|Sim|Sim||
|Diretivas de atribuição de função|Sim|Sim|Sim||
|**[Política e conformidade de mensagens](../../exchange-online-service-description/message-policy-and-compliance.md)**|**GCC**|**CCG Alto**|**DoD**|**Principais considerações**|
|Arquivamento de Caixas de Correio baseadas no Exchange Online|Sim|Sim|Sim||
|Arquivamento baseado em nuvem de caixas de correio no local|Sim|Sim|Sim||
|Messaging Records Management (MRM) |Sim|Sim|Sim||
|Políticas de retenção, rótulos e marcas manuais |Sim|Sim|Sim||
|Criptografia de dados de tempo de parada (BitLocker)|Sim|Sim|Sim||
|IRM usando a Proteção de Informações do Azure|Sim|Sim|Sim|Para obter mais informações sobre as limitações do AIP em GCC alta e DoD, consulte <a href="https://docs.microsoft.com/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description">Azure Information Protection Premium governamental Service Description</a>.<br><br>A proteção de informações do Azure não está incluída em G1/F3, mas pode ser adquirida como um complemento separado e habilitar os recursos de IRM (gerenciamento de direitos de informação) compatíveis. Alguns recursos de proteção de informações do Azure exigem uma assinatura do Office 365 ProPlus, que não está incluído no Office 365 governo G1 ou no Office 365 governo F3.|
|IRM usando Windows Server AD RMS|Sim|Sim|Sim|O Windows Server AD RMS é um servidor local que deve ser adquirido e gerenciado separadamente para habilitar os recursos de IRM compatíveis.|
|Criptografia de Mensagem do Office 365|Sim|Sim|Sim|Confira o comportamento de criptografia 365 <a href="https://docs.microsoft.com/microsoft-365/compliance/ome-version-comparison#unique-characteristics-of-office-365-message-encryption-in-a-gcc-high-deployment">365 de</a> [mensagem do Office 365](#office-365-message-encryptionbehavior-across-gcc-highdod-boundary) no @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @/DOD|
|Chave de Cliente|Sim|Sim|Sim|Requer o plano de serviço do G5.|
|S/MIME|Sim|Sim|Sim||
|Bloqueio In-loco e Retenção de Litígio|Sim|Sim|Sim|Requer o plano de serviço G3 ou G5.|
|Descoberta Eletrônica In-loco|Sim|Sim|Sim||
|Regras do fluxo de email|Sim|Sim|Sim||
|Prevenção contra perda de dados|Sim|Sim|Sim|Requer o plano de serviço G3 ou G5.|
|Registro em Diário|Sim|Sim|Sim||
|**[Proteção antispam e antimalware](../../exchange-online-service-description/anti-spam-and-anti-malware-protection.md)**|**GCC**|**CCG Alto**|**DoD**|**Principais considerações**|
|Proteção antispam interna|Sim|Sim|Sim||
|Customize anti-spam policies|Sim|Sim|Sim||
|Proteção Antimalware interna|Sim|Sim|Sim||
|Customize antimalware policies|Sim|Sim|Sim||
|Quarentena - gerenciamento de administrador|Sim|Sim|Sim||
|Quarentena - auto-gerenciamento de usuário final|Sim|Sim|Sim||
|Proteção Avançada contra Ameaças|Sim|Sim|Sim|Requer o plano de serviço do G5 (ou compra de complemento).<br><br>O anti-phishing para representação de usuário e domínio e inteligência de falsificação ainda não estão disponíveis no GCC High e no DoD.|
|**[Fluxo de mensagens](../../exchange-online-service-description/mail-flow.md)**|**GCC**|**CCG Alto**|**DoD**|**Principais considerações**|
|Roteamento personalizado de email de saída|Sim|Sim|Sim||
|Secure messaging with a trusted partner|Sim|Sim|Sim||
|Conditional mail routing|Sim|Sim|Sim||
|Adicionando um parceiro a uma lista segura de entrada|Sim|Sim|Sim||
|Roteamento de email híbrido|Sim|Sim|Sim||
|**[Destinatários](../../exchange-online-service-description/recipients.md)**|**GCC**|**CCG Alto**|**DoD**|**Principais considerações**|
|Alertas de capacidade|Sim|Sim|Sim||
|Email secundário|Sim|Sim|Sim||
|MailTips|Sim|Sim|Sim||
|Acesso de representante|Sim|Sim|Sim||
|Regras da Caixa de Entrada|Sim|Sim|Sim||
|Contas conectadas|Sim|Não|Não|Esse recurso não é suportado no GCC High ou no DoD devido a restrições nas conexões de saída para serviços de terceiros. Para obter mais informações sobre os recursos afetados, confira [conectividade com serviços de terceiros](#connectivity-with-third-party-services) neste artigo.|
|Caixas de correio inativas|Sim|Sim|Sim|Requer o plano de serviço G3 ou G5.|
|Offline address book|Sim|Sim|Sim||
|Políticas do catálogo de endereços|Sim|Sim|Sim||
|Catálogo de endereços hierárquico|Sim|Sim|Sim||
|Listas de endereços e lista de endereços global|Sim|Sim|Sim||
|Grupos do Office 365|Sim|Sim|Sim|O acesso de convidados aos grupos do Office 365 não é suportado em ambientes GCC High e DoD. Para obter mais informações, consulte <a href="https://docs.microsoft.com/azure/azure-government/documentation-government-services-securityandidentity">Azure governamentais Security + Identity</a>.|
|Grupos de Distribuição|Sim|Sim|Sim||
|Contatos externos (global)|Sim|Sim|Sim|Sujeito às limitações de colaboração de relações de organização nos ambientes GCC High e DoD. |
|Link de contato com redes sociais|Sim|Não|Não|Esse recurso não é suportado no GCC High ou no DoD.|
|Caixas de correio de recurso|Sim|Sim|Sim||
|Gerenciamento da sala de conferência|Sim|Sim|Sim||
|Respostas de Ausência Temporária|Sim|Sim|Sim||
|Compartilhamento de calendários da Internet|Sim|Não|Não|No @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @ @<br><br>No DoD – o compartilhamento de calendários da Internet não é suportado devido à necessidade de listagem de permissão de conexão de entrada/saída nesse ambiente.|
|**[Recursos de relatórios e ferramentas de solução de problemas](../../exchange-online-service-description/reporting-features-and-troubleshooting-tools.md)**|**GCC**|**CCG Alto**|**DoD**|**Principais considerações**|
|Relatórios do centro de administração do Microsoft 365|Sim|Sim|Não|Relatórios não disponíveis para o DoD. Consulte a seção <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">recursos da plataforma</a> da descrição do serviço governo dos EUA do Office 365 para atualizações/disponibilidade atual.|
|Relatórios de serviços Web|Sim|Sim|Não|Relatórios não disponíveis para o DoD. Consulte a seção <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">recursos da plataforma</a> da descrição do serviço governo dos EUA do Office 365 para atualizações/disponibilidade atual.|
|Message trace|Sim|Sim|Sim||
|Relatórios de auditoria|Sim|Sim|Não|Relatórios não disponíveis para o DoD. Consulte a seção <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">recursos da plataforma</a> da descrição do serviço governo dos EUA do Office 365 para atualizações/disponibilidade atual.|
|Relatórios de Unificação de Mensagens|Sim|Não|Não||
|**[Compartilhamento e colaboração](../../exchange-online-service-description/sharing-and-collaboration.md)**|**GCC**|**CCG Alto**|**DoD**|**Principais considerações**|
|Compartilhamento federado (incluindo publicação de calendário)|Sim|Sim|Sim|Há limitações no GCC High e no DoD. Consulte [Federação de disponibilidade](#freebusy-federation) neste artigo.|
|Caixas de correio local|Sim|Sim|Sim||
|Pastas públicas|Sim|Sim|Sim||
|**[Clientes e dispositivos móveis](../../exchange-online-service-description/clients-and-mobile-devices.md)**|**GCC**|**CCG Alto**|**DoD**|**Principais considerações**|
|Tarefas pendentes da Web|Sim|Não|Não||
|Outlook para Windows|Sim|Sim|Sim|Para atender aos requisitos de conformidade do GCC High e DoD, você deve estar executando pelo menos a versão 1803 do Office 365 ProPlus. O Office 365 ProPlus não está incluído em G1 ou F3.|
|Outlook na Web|Sim|Sim|Sim||
|Outlook para Mac|Sim|Sim|Sim|Para atender aos requisitos de conformidade do GCC High e DoD, você deve estar executando pelo menos a versão 1803 do Office 365 ProPlus. O Office 365 ProPlus não está incluído em G1 ou F3.|
|Outlook para iOS e Android|Sim|Sim|Sim||
|Exchange ActiveSync|Sim|Sim|Sim||
|Mobilidade básica e segurança para o Microsoft 365|Sim|Não|Não||
|POP e IMAP|Sim|Sim|Sim||
|SMTP|Sim|Sim|Sim||
|Suporte a aplicativos EWS|Sim|Sim|Sim||
|**[Serviços de mensagens de voz](../../exchange-online-service-description/voice-message-services.md)**|**GCC**|**CCG Alto**|**DoD**|**Principais considerações**|
|Caixa postal|Não|Não|Não|A integração de sistemas IP-PBX no local com a Unificação de mensagens do Exchange Online não é suportada.|
|Integração entre caixa postal e FAX de terceiros|Não|Não|Não|A integração de sistemas IP-PBX no local com a Unificação de mensagens do Exchange Online não é suportada.|
|Interoperabilidade de caixa postal de terceiros|Não|Não|Não|A integração de sistemas IP-PBX no local com a Unificação de mensagens do Exchange Online não é suportada.|
|Integração do Skype for Business|Sim|Sim|Sim||
|**[Alta disponibilidade e continuidade de negócios](../../exchange-online-service-description/high-availability-and-business-continuity.md)**|**GCC**|**CCG Alto**|**DoD**|**Principais considerações**|
|Replicação de caixa de correio em datacenters|Sim|Sim|Sim||
|Recuperação da caixa de correio excluída|Sim|Sim|Sim||
|Recuperação de itens excluídos|Sim|Sim|Sim||
|Recuperação de item único|Sim|Sim|Sim||
|**[Interoperabilidade, conectividade e compatibilidade](../../exchange-online-service-description/interoperability-connectivity-and-compatibility.md)**|**GCC**|**CCG Alto**|**DoD**|**Principais considerações**|
|Presença no OWA e no Outlook|Sim|Sim|Sim||
|Interoperabilidade do SharePoint|Sim|Sim|Sim||
|Suporte à conectividade do EWS|Sim|Sim|Sim||
|Suporte a retransmissão SMTP|Sim|Sim|Sim||
|**[Instalação e administração do Exchange Online](../../exchange-online-service-description/exchange-online-setup-and-administration.md)**|**GCC**|**CCG Alto**|**DoD**|**Principais considerações**|
|Acesso ao portal do Microsoft Office 365|Sim|Sim|Não|Relatórios não disponíveis para o DoD. Consulte a seção <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">recursos da plataforma</a> da descrição do serviço governo dos EUA do Office 365 para atualizações/disponibilidade atual.|
|Acesso ao centro de administração do Microsoft 365|Sim|Sim|Não|Relatórios não disponíveis para o DoD. Consulte a seção <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">recursos da plataforma</a> da descrição do serviço governo dos EUA do Office 365 para atualizações/disponibilidade atual.|
|Acesso ao centro de administração do Exchange|Sim|Sim|Sim||
|Acesso Remoto do Windows PowerShell|Sim|Sim|Sim||
|Políticas do ActiveSync para dispositivos móveis|Sim|Sim|Sim||
|Relatórios de uso|Sim|Sim|Não|Relatórios não disponíveis para o DoD. Consulte a seção <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">recursos da plataforma</a> da descrição do serviço governo dos EUA do Office 365 para atualizações/disponibilidade atual.|
|**[Estendendo o serviço-personalização, suplementos e recursos](../../exchange-online-service-description/exchange-online-service-description.md)**|**GCC**|**CCG Alto**|**DoD**|**Principais considerações**|
|Suplementos do Outlook e MAPI do Outlook|Sim|Sim|Sim|Apenas alguns suplementos OWA e Outlook estão disponíveis no GCC High e no DoD. Confira [suplementos no Outlook e no Outlook Web App](#add-insin-outlook-and-outlook-web-app) neste artigo.|

## <a name="feature-nuances-within-gcc-high-and-dod-environments"></a>Nuances de recursos em ambientes GCC High e DoD

### <a name="connectivity-with-third-party-services"></a>Conectividade com serviços de terceiros  

Os ambientes GCC High e DoD são ambientes restritos que exigem aprovação e configuração explícitas de conexões de saída. Além disso, a Microsoft não pode acomodar solicitações para permitir o acesso de saída desses ambientes aos serviços de nuvem comercial (comercial 365, Google GSuite, serviços Web da Amazon e assim por diante).

Devido a essas restrições, os recursos que dependem dessa conectividade de saída dos ambientes GCC High/DoD geralmente não são suportados, incluindo:

- Contas conectadas: os usuários não podem adicionar/sincronizar contas (Google, POP/IMAP e assim por diante).

- Suporte para provedores de armazenamento de arquivos de terceiros – somente a conta do OneDrive for Business do usuário *no gcc High/DOD* pode ser acessada de dentro dos vários clientes do Outlook com o objetivo de anexar/compartilhar arquivos. As contas de armazenamento de terceiros (Dropbox, Box, Google Drive) não podem ser adicionadas.

- Conectividade com redes sociais, como Facebook ou LinkedIn.

### <a name="azure-active-directory-b2b-collaboration"></a>Colaboração B2B do Azure Active Directory

Atualmente, a colaboração B2B do Azure Active Directory só é suportada entre organizações que estão na nuvem do governo dos EUA do Azure e que ambos oferecem suporte à colaboração B2B

Além disso, os usuários B2B como convidados nos grupos do Office 365 não têm suporte nos ambientes GCC High e DoD. 

Para obter mais informações e as atualizações mais recentes, consulte [Azure governamental Security + Identity](https://docs.microsoft.com/azure/azure-government/documentation-government-services-securityandidentity).

### <a name="office-365-message-encryption-behavior-across-gcc-highdod-boundary"></a>Comportamento de criptografia de mensagem do Office 365 entre os limites de GCC alta/DoD

Se você usar a criptografia de mensagem do Office 365 em um ambiente de maior GCC, esteja ciente dessas características exclusivas sobre a experiência do destinatário:  

- Ao enviar emails criptografados de GCC alta ou DoD para destinatários no mesmo ambiente:
    
    - Os remetentes podem criptografar manualmente emails no Outlook para PC e Mac e Outlook na Web, ou as organizações podem configurar uma política para criptografar emails usando regras de fluxo de email do Exchange.
    
    - Os destinatários dentro do GCC High/DoD recebem a mesma experiência de leitura embutida no Outlook para PC e Mac e Outlook na Web como todos os outros usuários do Office 365.

<!-- end list -->

- Ao enviar emails criptografados de GCC alta ou DoD para destinatários fora desse ambiente (incluindo GCC e comercial):
    
    - Os remetentes dentro do GCC High/DoD podem enviar emails criptografados fora dos limites do GCC High/DoD.
    
    - Todos os destinatários fora do GCC High/DoD, incluindo os usuários do Office 365 comercial, os usuários do Outlook.com e outros usuários de outros provedores de email, recebem um email de conteúdo adicional. Este email de invólucro redireciona o destinatário para o portal do OME, onde o destinatário pode ler e responder à mensagem.

Para obter mais informações e as atualizações mais recentes, consulte [Compare versions of ome](https://docs.microsoft.com/microsoft-365/compliance/ome-version-comparison).

### <a name="freebusy-federation"></a>Federação de disponibilidade

O compartilhamento federado, incluindo informações de disponibilidade, estão sujeitos a várias limitações importantes nos ambientes GCC High e DoD.

No ambiente GCC High:

- A confiança de Federação (incluindo compartilhamento bidirecional de disponibilidade) é suportada entre os locatários dentro de GCC alta e por meio de coexistência híbrida (Exchange 2013 ou posterior).

- O compartilhamento federado não tem suporte entre locatários no GCC High e GCC ou no Office 365 Commercial. As conexões de saída do ambiente de alta do GCC para as nuvens comerciais (incluindo GCC e Office 365 comercial) não são permitidas no momento. Como resultado, os usuários mais altos não podem fazer a solicitação de saída necessária para GCC/comercial acessar informações de calendário compartilhadas.

No ambiente DoD:

  - A confiança de Federação (incluindo compartilhamento de disponibilidade) é suportada atualmente somente entre os locatários no ambiente do DoD. Não há suporte entre locatários DoD e locatários de GCC ou de negócios.

### <a name="client-configuration"></a>Configuração do cliente

Etapas adicionais estão envolvidas na implantação e configuração do Office ProPlus (inclusive Outlook). Para obter uma descrição detalhada dessas etapas, consulte [diretrizes para implantar o Microsoft 365 aplicativos para empresas em um ambiente gcc High ou DOD](https://docs.microsoft.com/deployoffice/deploy-microsoft-365-apps-gcc-high-dod).

O Outlook para iOS e o Android também estão disponíveis para ambientes GCC High e DoD. Para saber mais sobre limitações de recursos e gerenciamento nesses ambientes, consulte [using Outlook for Ios and Android na nuvem da Comunidade governamental](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud).

### <a name="add-ins-in-outlook-and-outlook-web-app"></a>Suplementos no Outlook e no Outlook Web App  

Apenas alguns suplementos OWA e Outlook estão disponíveis no GCC High e no DoD. Meus modelos e reuniões sugeridas estão disponíveis e espera-se que funcionem. Só há suporte para os cinco suplementos padrão do OWA. A integração com aplicativos de terceiros é possível, no entanto, essas integrações não são cobertas pelas promessas de conformidade da Microsoft para GCC alta ou DoD. Os clientes devem se familiarizar com as práticas de manipulação de dados de terceiros e as promessas de conformidade antes de configurar o complemento para sua organização.

## <a name="feature-nuances-within-gcc-environments"></a>Nuances de recursos em ambientes GCC

| Recurso | Descrição | PARCEIROS | Disponibilidade em GCC |
|:-----|:-----|:-----|:-----|
|Plataformas suportadas|Web, Android, iOS, Mac, Windows|Todos|Somente Web|
|O Hub M365 suporta|Integração com o Outlook, o Microsoft Teams, o Planner|Todos|Outlook, planejador (as equipes a serem disponibilizadas com o aplicativo de tarefas do Teams)|
|Migração do Wunderlist|Permitir que os usuários do Wunderlist migrem dados para tarefas pendentes|Sim|Não|
|Notificação por Push|Envie notificações por push para usuários finais para lembretes, etc.|Sim|Não|
|Suporte do Helpshift|Usar a interface helpshift para criar a solicitação de suporte|Sim|Não|
|Meu dia|Planejar seu dia|Sim|Sim|
|Lista planejada|Ver todas as tarefas com uma data de conclusão|Sim|Sim|
|Atribuído à lista|Todas as tarefas atribuídas a você em uma lista compartilhada, planejador ou WXP (futuro)|Sim|Sim|
|Email sinalizado|Ver emails sinalizados no Outlook como tarefas|Sim|Sim|
|Suporte a várias contas|Usar a conta de casa e do escritório em um painel|Sim|Sim|
|Compartilhamento de lista|Compartilhar listas com colegas na mesma organização|Sim|Sim|
|Compartilhamento entre locatários|Compartilhar lista de tarefas fora da organização|Sim|Não|
|Lembretes e recorrência|Definir lembretes para a tarefa |Sim|Sim|

* Qualquer outro recurso não mencionado estará disponível nos dois ambientes.
