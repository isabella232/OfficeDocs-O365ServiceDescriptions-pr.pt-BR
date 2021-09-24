---
title: Office 365 GCC Alta e DoD
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: 0821204d-5515-43de-8ed6-ab84bd1693c1
description: Saiba mais sobre os compromissos exclusivos e as diferenças dos ambientes Office 365 GCC Alta e DoD em comparação com o ambiente Office 365 comercial.
ms.openlocfilehash: e23093e2fdebad45175746aa57bedc0c87728d4b
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/24/2021
ms.locfileid: "59670326"
---
# <a name="office-365-gcc-high-and-dod"></a>Office 365 GCC Alta e DoD

Para atender aos requisitos exclusivos e em evolução do Departamento de Defesa dos Estados Unidos, bem como os contratados que têm ou processam informações não classificadas controladas pelo DoD (CUI) ou sujeitos ao ITAR (International Traffic in Arms Regulations), a Microsoft oferece ambientes GCC de Alta e DoD. Disponíveis por meio de Licenciamento por Volume, as organizações interessadas passam por um processo de validação para garantir a qualificação, antes do estabelecimento de um ambiente. As avaliações gratuitas não estão disponíveis no momento. 
  
Envolva sua equipe de conta ou parceiro preferencial para saber mais ou iniciar o processo de validação. Para obter mais informações sobre como comprar, [consulte Microsoft 365 Government - How to Buy](./microsoft-365-government-how-to-buy.md).
  
## <a name="how-to-use-this-service-description"></a>Como usar a descrição deste serviço

A Office 365 de serviço do Governo dos EUA foi projetada para servir como uma sobreposição para a descrição geral Office 365 serviço. Ele define os compromissos e diferenças exclusivos em comparação com Office 365 para ofertas corporativas.
  
## <a name="compliance"></a>Conformidade

GCC High e DoD atendem aos requisitos de conformidade para as seguintes certificações e acreditações: 
  
- O Programa Federal de Gerenciamento de Riscos e Autorizações no FedRAMP High, incluindo esses controles de segurança e aprimoramentos de controle, conforme descrito no National Institute of Standards and Technology (NIST) Special Publication 800-53.
    
- Os controles de segurança e aprimoramentos de controle para o Guia de Requisitos de Segurança de Computação em Nuvem (SRG) do Departamento de Defesa dos Estados Unidos para informações até o Nível de Impacto 5 (L5).
    
Os assinantes do Departamento de Defesa Office 365 receberão serviços fornecidos do ambiente exclusivo do DOD que atende ao DOD SRG L5. Os assinantes que não são do Departamento de Defesa receberão serviços do ambiente de Defesa do Governo dos EUA que é avaliado em L5, mas usa segmentação L4.
  
## <a name="background-screening"></a>Triagem em segundo plano

Office 365 funcionários não têm acesso permanente GCC alta e produção do DoD. Qualquer equipe que solicite a elevação de permissão temporária que concederia acesso ao conteúdo do cliente deve primeiro ter passado as seguintes verificações em segundo plano.<br><br>
  
| Verificação de plano de fundo e triagem de equipe da Microsoft<sup>1</sup> | Descrição |
|:-----|:-----|
|Cidadania dos EUA  <br/> |Verificação de cidadania dos EUA  <br/> |
|Verificação do histórico de empregos  <br/> |Verificação do histórico de empregos dos últimos sete anos  <br/> |
|Verificação de nível escolar  <br/> |Verificação do grau mais elevado concluído  <br/> |
|Pesquisa de Número do Seguro Social (SSN) dos EUA  <br/> |Verificação de validade do SSN fornecido  <br/> |
|Verificação de antecedentes criminais  <br/> |Verificação de antecedentes criminais dos últimos sete anos para crimes e contravenções, em nível local, municipal, estadual e federal  <br/> |
|Lista da OFAC (Agência de Controle de Ativos Estrangeiros)  <br/> |Validação da lista de grupos do Departamento do Tesouro com os quais os cidadãos dos EUA não têm permissão para participar de transações comerciais ou financeiras  <br/> |
|Lista do BIS (Gabinete de Indústria e Segurança)  <br/> |Validação da lista de pessoas e entidades do Departamento de Comércio impedidas de participar de atividades de exportação  <br/> |
|Lista do DDTC (Pessoas Impedidas pela Agência de Controle de Comércio de Armas)  <br/> |Validação da lista de pessoas e entidades do Departamento de Estado impedidas de participar de atividades de exportação relacionadas à indústria de armas  <br/> |
|Verificação de impressão digital  <br/> |Verificação de antecedentes por impressão digital dos bancos de dados do FBI (Agência Federal de Investigação)  <br/> |
|Departamento de Defesa IT-2  <br/> |Equipe solicitando permissões elevadas aos dados do cliente ou acesso administrativo privilegiado aos recursos do serviço de SRG do Departamento de Defesa L5 deve passar por adjudicação do Departamento de Defesa IT-2 com base em uma investigação bem-sucedida do OPM Nível 3  <br/> |

<sup>1</sup> Aplica-se somente a funcionários com acesso temporário ou permanente ao conteúdo do cliente hospedado em Office 365 nuvens GCC-High OU DOD dos EUA.
## <a name="feature-nuances-based-on-compliant-cloud-architecture"></a>Nuances de recursos com base na arquitetura de nuvem compatível

As assinaturas nos GCC ambientes High e DoD incluem os recursos Exchange Online, SharePoint e Skype for Business principais. Devido ao aumento da certificação e do credenciamento da infraestrutura, há algumas diferenças de recursos entre as ofertas de Office 365 comerciais gerais e as disponíveis no GCC High e DoD.
  
### <a name="exchange-online"></a>Exchange Online

 Exchange Online Suporte de Unificação de Mensagens para **IP-PBX** local - O suporte para integração de sistemas IP-PBX locais com Exchange Online Unificação de Mensagens não é suportado em assinaturas high and DoD do GCC. 
  
### <a name="file-sharing"></a>Compartilhamento de arquivos

Os usuários têm várias opções para compartilhar arquivos e pastas em SharePoint e OneDrive. Todas as opções estão disponíveis nos ambientes GCC High e DoD. Para obter mais informações sobre como gerenciar essas opções, consulte [Gerenciar configurações de compartilhamento](/sharepoint/turn-external-sharing-on-or-off). Os usuários GCC-High poderão compartilhar somente com outras organizações no GCC-High. Além disso, não há GCC endereços de email altos anexados aos perfis de usuário e não permitem que emails de alerta sejam enviados. Por exemplo, no local, o Usuário A recebe um endereço de email do Gmail e sincronizado com uma organização do Azure GCC High. O Usuário A navega até uma biblioteca e cria um alerta para quaisquer alterações. O alerta não será enviado para o endereço do Gmail.

> [!NOTE]
> Os usuários GCC-High atualmente não podem compartilhar com usuários em organizações não GCC High.

[As solicitações](https://support.office.com/article/f54aa7f8-2589-4421-b351-d415fc3b83af) de arquivo não estão disponíveis para Office 365 Government.

### <a name="skype-for-business-online"></a>Skype for Business Online

 **Chamada PSTN &amp; Conferência PSTN** - Devido à exigência de usar a PSTN (Rede Telefônica Pública Comucionada) para serviços orientados para telefonia, os serviços de Conferência PSTN de Chamada PSTN não estão disponíveis no momento no GCC High e &amp; DoD.

### <a name="microsoft-teams"></a>Microsoft Teams

**Sistema de Telefonia e Audioconferência (via** Roteamento Direto) - Sistema de Telefonia e Audioconferência para GCC ambientes High e DoD estão sendo entregues por meio de Roteamento Direto. Para obter mais informações, consulte a documentação de nível de serviço aqui:

- [Sistema de Telefonia roteamento direto](/microsoftteams/here-s-what-you-get-with-phone-system)
- [Conferências de Áudio com Roteamento Direto para GCC Alto e DoD](/microsoftteams/audio-conferencing-with-direct-routing-for-gcch-and-dod)

### <a name="identity"></a>Identidade

A autenticação multifator usando um modelo de identidade federado permite o uso de cartões PIV e CAC.
  
### <a name="yammer"></a>Yammer

Yammer para empresas não está disponível nos ambientes GCC High e DoD.
  
## <a name="customer-support"></a>Suporte ao cliente

A Microsoft lembra que você não deve compartilhar informações controladas, confidenciais ou confidenciais com a equipe de suporte ao cliente como parte do incidente de suporte ao usar o Office 365 GCC High/DOD, pelo menos até confirmar a autorização do agente de suporte para exibir ou acessar esses dados.

A Microsoft está comprometida em proteger sua [privacidade](https://privacy.microsoft.com/privacystatement)). No entanto, Office 365 GCC suporte a High/DoD não está incluído no limite de credenciamento de serviço e não fornece garantias de conformidade de conformidade com FedRAMP, DOD SRG, ITAR, IRS 1075 ou CJIS.