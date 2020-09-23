---
title: Office 365 GCC High e DoD
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0821204d-5515-43de-8ed6-ab84bd1693c1
description: Saiba mais sobre os compromissos exclusivos e as diferenças dos ambientes do Office 365 GCC High e DoD em comparação com o ambiente comercial do Office 365.
ms.openlocfilehash: 44d66557f426ab236460affd61fbf1970c7f25e6
ms.sourcegitcommit: 8d17d5df1427a817df15d45eae5f2f3e48d7b12d
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/23/2020
ms.locfileid: "48214330"
---
# <a name="office-365-gcc-high-and-dod"></a>Office 365 GCC High e DoD

Para atender aos requisitos exclusivos e em evolução do departamento de defesa dos Estados Unidos, bem como dos contratados que mantêm ou processam informações não classificadas ou sujeitas ao tráfego internacional (ITAR) controlados pelo DoD, a Microsoft oferece ambientes de alta e DoD. Disponíveis por meio de Licenciamento por Volume, as organizações interessadas passam por um processo de validação para garantir a qualificação, antes do estabelecimento de um ambiente. As avaliações gratuitas não estão disponíveis no momento. 
  
Entre em contato com sua equipe de conta ou parceiro preferido para saber mais ou iniciar o processo de validação. Para obter mais informações sobre como comprar, consulte [Microsoft 365 governamentais-como comprar](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy).
  
## <a name="how-to-use-this-service-description-section"></a>Seção como usar esta descrição de serviço

A descrição do serviço do governo dos EUA do Office 365 foi projetada para servir como uma sobreposição para a descrição geral do serviço do Office 365. Ela define as diferenças e os compromissos exclusivos em comparação com as ofertas do Office 365 Enterprise.
  
## <a name="compliance"></a>Conformidade

O GCC elevado e o DoD atendem aos requisitos de conformidade para as seguintes certificações e capacitações: 
  
- O programa de gerenciamento de riscos e autorização federal em FedRAMP High, incluindo esses controles de segurança e aprimoramentos de controle, conforme descrito na publicação especial da National Institute of Standards and Technology (NIST) 800-53.
    
- Os controles de segurança e os aprimoramentos de controle para o departamento de defesa da nuvem da computação em nuvem dos Estados Unidos (SRG) para obter informações sobre o nível 5 (L5) de impacto.
    
Os assinantes do departamento de defesa com o Office 365 receberão serviços fornecidos pelo ambiente exclusivo do DOD que atendem ao DOD SRG L5. Os assinantes de não-departamento de defesa receberão serviços do ambiente de defesa do governo dos EUA que é avaliado em L5, mas usa segmentação L4.
  
## <a name="background-screening"></a>Triagem de plano de fundo

A equipe do Office 365 não tem acesso à produção GCC alta e DoD. Qualquer equipe que solicite a elevação temporária de permissões que concederia acesso ao conteúdo do cliente deve primeiro passar as seguintes verificações em segundo plano.
  
|||
|:-----|:-----|
|**Verificações em segundo plano e tela de pessoal da Microsoft**<sup>1</sup> <br/> |**Descrição** <br/> |
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

<sup>1</sup> aplica-se somente ao pessoal com acesso temporário ou de posição ao conteúdo do cliente hospedado em nuvens do Office 365 gcc-alta ou DOD.
## <a name="feature-nuances-based-on-compliant-cloud-architecture"></a>Nuances de recursos com base na arquitetura de nuvem compatível

As assinaturas nos ambientes de GCC High e DoD incluem os principais recursos do Exchange Online, SharePoint e Skype for Business. Considerando a maior certificação e a capacitação da infraestrutura, há algumas diferenças de recursos entre as ofertas gerais de negócios do Office 365 e as disponíveis no GCC High e no DoD.
  
### <a name="exchange-online"></a>Exchange Online

 O **suporte à unificação de mensagens do Exchange Online para IP-PBX local** -suporte para integração de sistemas IP-PBX com a Unificação de mensagens do Exchange Online não é suportado em assinaturas gcc alta e DOD. 
  
### <a name="file-sharing"></a>Compartilhamento de arquivos

Os usuários têm várias opções para compartilhar arquivos e pastas no SharePoint e no OneDrive. Todas as opções estão disponíveis nos ambientes GCC High e DoD. Para obter mais informações sobre como gerenciar essas opções, consulte [gerenciar configurações de compartilhamento](/sharepoint/turn-external-sharing-on-or-off). Os usuários no GCC-alto poderão compartilhar somente com outras organizações no GCC-alto. Além disso, não há suporte para endereços de email não-GCC anexados a perfis de usuário e não serão enviados emails de alerta. Por exemplo, no usuário local, um endereço de email do Gmail é atribuído e, em seguida, sincronizado para uma organização do Azure GCC High. O usuário A navega para uma biblioteca e cria um alerta para qualquer alteração. O alerta não será enviado para o endereço do gmail.

> [!NOTE]
> Os usuários no GCC-High não podem compartilhar atualmente com usuários em organizações que não são GCC.

[As solicitações de arquivo](https://support.office.com/article/f54aa7f8-2589-4421-b351-d415fc3b83af) não estão disponíveis para o governo do Office 365.

### <a name="skype-for-business-online"></a>Skype for Business Online

 **Chamada &amp; PSTN Conferência PSTN** – devido à necessidade de usar a rede telefônica pública comutada (PSTN) para serviços orientados por telefonia, os serviços de &amp; conferência PSTN de chamadas PSTN não estão disponíveis no gcc High e no DOD.

### <a name="microsoft-teams"></a>Microsoft Teams

**Sistema de telefonia e conferência de áudio (via roteamento direto)**: o sistema de telefonia e a conferência de áudio para ambientes gcc altos e DOD estão sendo entregues por meio do roteamento direto. Para obter mais informações, consulte a documentação do nível de serviço aqui:

- [Sistema de telefonia via roteamento direto](https://docs.microsoft.com/microsoftteams/here-s-what-you-get-with-phone-system)
- [Conferências de Áudio com Roteamento Direto para GCC Alto e DoD](https://docs.microsoft.com/microsoftteams/audio-conferencing-with-direct-routing-for-gcch-and-dod)

### <a name="identity"></a>Identidade

A autenticação multifator usando um modelo de identidade federado permite o uso de cartões PIV e CAC.
  
### <a name="yammer"></a>Yammer

O Yammer Enterprise não está disponível nos ambientes GCC High e DoD.
  
## <a name="customer-support"></a>Suporte ao cliente

A Microsoft o lembra de não compartilhar informações controladas, confidenciais ou confidenciais com a equipe de suporte ao cliente como parte do seu incidente de suporte ao usar o Office 365 GCC High/DOD, pelo menos até que você confirme a autorização do agente de suporte para exibir ou acessar esses dados.

A Microsoft está comprometida em proteger sua [privacidade](https://privacy.microsoft.com/privacystatement). No entanto, o suporte do Office 365 GCC High/DoD não está incluído no limite de capacitação de serviço e não fornece garantias de conformidade de gerenciamento de dados do FedRAMP, DOD SRG, ITAR, IRS 1075 ou CJIS.
