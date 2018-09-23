---
title: Política e conformidade no envio e recebimento de mensagens [ServiceDesc]
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: Microsoft Exchange Online Protection (EOP) oferece a diretiva de mensagens e recursos de conformidade que podem ajudar você a gerenciar seus dados de email.
ms.openlocfilehash: f88cd016586384f4617cd4899708c811a32af980
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24034784"
---
# <a name="messaging-policy-and-complianceservicedesc"></a>Política e conformidade no envio e recebimento de mensagens [ServiceDesc]

Microsoft Exchange Online Protection (EOP) oferece a diretiva de mensagens e recursos de conformidade que podem ajudar você a gerenciar seus dados de email.
  
Está procurando informações sobre todos os recursos do EOP? Consulte a [Descrição do serviço de proteção do Exchange Online](exchange-online-protection-service-description.md).
  
## <a name="transport-rules"></a>Regras de transporte
<a name="BKMK_transportrules"> </a>

As regras de transporte fornecem a flexibilidade de aplicar suas próprias políticas específicas da empresa ao email. As regras de transporte são compostas por critérios flexíveis, que permitem definir condições e exceções, e por ações a serem executadas com base nos critérios. Confira mais informações sobre as regras de Transporte no EOP em [Regras de Transporte](https://go.microsoft.com/fwlink/p/?LinkId=320399).
  
## <a name="audit-logging"></a>Registro em log de auditoria
<a name="BKMK_auditlogging"> </a>

O registro em log de auditoria permite que você controle as alterações específicas feitas pelos administradores em sua organização. Esses relatórios ajudam você a cumprir requisitos de regulamentações, conformidade e litígio. Confira mais informações em [Relatórios de auditoria no EOP](https://go.microsoft.com/fwlink/p/?LinkId=314258).
  
## <a name="data-loss-prevention-dlp"></a>Prevenção de perda de dados (DLP)
<a name="BKMK_datalossprevention"> </a>

Não disponível para clientes autônomos do EOP. A Prevenção de Perda de Dados (DLP) ajuda a identificar, monitorar e proteger informações confidenciais de sua organização por meio de análise profunda de conteúdo. DLP é cada vez mais importante para sistemas de mensagens corporativos porque o email crucial para os negócios inclui dados confidenciais que precisam ser protegidos. O recurso DLP permite que você proteja dados confidenciais sem afetar a produtividade do trabalhador.
  
Você pode configurar as políticas de DLP no EAC, que permitem:
  
- Iniciar com um modelo de política pré-configurado que pode ajudar a detectar tipos específicos de informações confidenciais, como dados PCI-DSS, dados do Gramm-Leach-Bliley Act ou até mesmo informações de identificação pessoal (PII) específicas de localidade.
    
- Use todo o poder dos critérios e das ações de regras de transporte existentes e adicione novas regras de transporte.
    
- Teste a eficácia das suas políticas de DLP antes de impô-las totalmente.
    
- Incorpore seus próprios modelos personalizados de política de DLP e tipos de informações confidenciais.
    
- Detectar informações confidenciais em anexos de mensagens, texto do corpo ou linhas de assunto e ajustar o nível de confiança em que o serviço age.
    
- Detecte dados confidenciais por meio de impressão digital do documento. A impressão digital de documentos ajuda você a criar facilmente tipos de informações confidenciais personalizadas com base em formulários baseados em texto que você pode usar para definir as regras de transporte e políticas de DLP.
    
- Adicione Dicas de Política, que podem ajudar a reduzir a perda de dados ao exibirem um aviso para os usuários do Outlook 2013, Outlook Web App e OWA para Dispositivos além de aprimorar a efetividade de suas políticas permitindo o relato de falsos positivos.
    
- Revise os dados de incidentes em relatórios de DLP ou adicione seus próprios relatórios específicos usando uma ação de geração de relatórios de incidentes.
    
> [!NOTE]
> As políticas de DLP são aplicadas apenas ao email que entra ou sai da organização. Os emails intraorganizacionais (internos) não têm políticas de DLP aplicadas, a menos que você execute o Exchange Server 2013 com DLP local. Isso também se aplica às dicas de política de DLP, que informam aos usuários sobre possíveis violações de política antes que dados confidenciais sejam enviados por engano a destinatários não autorizados. 
  
Saiba mais sobre o DLP em [Prevenção de perda de dados](https://go.microsoft.com/fwlink/p/?LinkId=320398).
  
## <a name="office-365-message-encryption"></a>Criptografia de mensagem do Office 365
<a name="BKMK_OME_in_EOP"> </a>

Criptografia de mensagem do Office 365, uma parte da proteção de informações do Windows Azure, é um serviço online que permite que os usuários de email enviar mensagens de email criptografadas para qualquer pessoa. Clientes locais podem acessar o Office 365 Message Encryption adquirindo a proteção de informações do Windows Azure e usando o Exchange Online Protection para configurar o fluxo de emails através do Exchange Online. Para saber mais sobre criptografia de mensagem do Office 365 no Exchange Online, consulte [Criptografia de mensagem do Office 365](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption) no Exchange Online Service Description. 
  
## <a name="messaging-policy-and-compliance-features-across-eop-options"></a>Recursos de diretiva e conformidade de mensagens através de opções EOP
<a name="BKMK_OME_in_EOP"> </a>

|**Recurso**|**EOP autônomo**|**Recursos do EOP no Exchange Online**|**Exchange Enterprise CAL com Serviços**|
|:-----|:-----|:-----|:-----|
|Regras de transporte  <br/> |Sim<sup>1</sup> <br/> |Sim<sup>1</sup> <br/> |Sim  <br/> |
|Registro em log de auditoria  <br/> |Sim<sup>2</sup> <br/> |Sim  <br/> |Sim  <br/> |
|Prevenção de Perda de Dados (DLP)  <br/> |Não  <br/> |Sim  <br/> |Sim<sup>3</sup> <br/> |
|Criptografia de Mensagem do Office 365  <br/> |Sim<sup>4</sup> <br/> |Sim  <br/> |Sim<sup>4</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> os critérios disponíveis e as ações diferem entre o EOP e o Exchange Online. Para obter uma lista de critérios disponíveis e ações no EOP, consulte [Critérios da regra de transporte](https://go.microsoft.com/fwlink/p/?LinkId=320392) e [Transport Rule Actions](https://go.microsoft.com/fwlink/p/?LinkId=320393). Para obter uma lista de critérios disponíveis e ações no Exchange Online, consulte [Critérios da regra de transporte](https://go.microsoft.com/fwlink/p/?LinkId=320394) e [Transport Rule Actions](https://go.microsoft.com/fwlink/p/?LinkId=320395). > <sup>2</sup> EOP relatórios de auditoria é um subconjunto do Exchange Online relatórios que excluem informações sobre caixas de correio de auditoria. > <sup>3</sup> dicas de política DLP não estão disponíveis para o Exchange Enterprise CAL com os clientes de serviços. > <sup>4</sup> suportados para os clientes locais que adquirirem o complemento de proteção de informações do Windows Azure e usarem o Exchange Online Protection para encaminhar emails através do Exchange Online. Para que a experiência no desktop, além do complemento de proteção de informações do Windows Azure, Office 365 ProPlus precisa ser adquirido. 
  

