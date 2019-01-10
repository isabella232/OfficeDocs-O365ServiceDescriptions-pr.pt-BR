---
title: Descrição do Serviço da Proteção Avançada contra Ameaças do Office 365
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 01/02/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 avançadas ameaça proteção (ATP) é um serviço que ajuda a proteger sua organização contra malware desconhecido e vírus, fornecendo proteção robusta de dia zero e inclui recursos para a proteção de filtragem de email baseada em nuvem sua organização de links prejudiciais em tempo real. ATP tem reporting rica e capacidades de rastreamento de URL que oferecem aos administradores percepção o tipo de ataque acontecendo na organização.
ms.openlocfilehash: f8a44cdebebafe575f5c22a3a491671f57b05d49
ms.sourcegitcommit: d1d7309e864398e7d029956231cbaee054a2a0cf
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 01/09/2019
ms.locfileid: "27784863"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Descrição do Serviço da Proteção Avançada contra Ameaças do Office 365

Microsoft Office 365 avançadas ameaça proteção (ATP) é um serviço que ajuda a proteger sua organização contra malware desconhecido e vírus, fornecendo proteção robusta de dia zero e inclui recursos para a proteção de filtragem de email baseada em nuvem sua organização de links prejudiciais em tempo real. ATP tem reporting rica e capacidades de rastreamento de URL que oferecem aos administradores percepção o tipo de ataque acontecendo na organização.
  
A seguir estão as formas básicas ATP podem ser usados para a proteção de mensagem:
  
- Em um cenário de filtragem somente Office 365 ATP ATP fornece proteção de email baseada em nuvem para seu ambiente do Exchange Server 2013 local, versões herdadas do Exchange Server ou qualquer outra solução de email SMTP local.
    
- O Office 365 ATP pode ser habilitado para proteger as caixas de correio Exchange Online hospedado na nuvem. Para saber mais sobre o Exchange Online, consulte o [Exchange Online Service Description](exchange-online-service-description/exchange-online-service-description.md).
    
- Em uma implantação híbrida, ATP pode ser configurado para proteger seu ambiente de mensagens e controlar o roteamento de email quando você tem uma combinação de locais e na nuvem de caixas de correio com o Exchange Online Protection para filtragem de email de entrada.
    
## <a name="office-365-advanced-threat-protection-atp-availability"></a>Disponibilidade de proteção de ameaça avançadas (ATP) do Office 365

ATP está incluído no Office 365 Enterprise E5, A5 de educação do Office 365 e Microsoft 365 Business. 
  
> [!NOTE]
> Recursos de ATP de cliente dependentes no Microsoft 365 Business estarão disponíveis 2018 de verão. 
  
Você pode adicionar a ATP aos seguintes planos de assinatura do Exchange e do Office 365: 
  
- Plano 1 do Exchange Online
    
- Plano 2 do Exchange Online
    
- Quiosque do Exchange Online
    
- Proteção do Exchange Online
    
- Office 365 Business Essentials
    
- Office 365 Business Premium
    
- Office 365 Enterprise E1
    
- Office 365 Enterprise E3
    
- Office 365 Enterprise F1
    
- Office 365 A1
    
- Office 365 A3
    
Para adquirir a proteção de ameaça avançadas do Office 365, consulte [Proteção de ameaça avançadas do Office 365](https://go.microsoft.com/fwlink/p/?LinkId=294201).
  
Para comparar os recursos entre os planos, confira [Comparar planos do Office 365 for Business](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409).
  
## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>O que há de novo no Office 365 avançadas ameaça proteção (ATP)

Para obter informações sobre novos recursos no ATP, consulte [novos recursos no ATP](https://docs.microsoft.com/office365/securitycompliance/office-365-atp#new-features-are-continually-being-added-to-atp).
  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Requisitos para o Office 365 proteção avançada (ATP)

A ATP pode ser usada com qualquer agente de transferência de emails SMTP, como o Microsoft Exchange Server 2013. Para saber mais sobre os sistemas operacionais, navegadores da Web e idiomas suportados pela ATP, veja as seções "Navegadores com suporte" e "Idiomas com suporte" em [Centro de administração do Exchange no Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>Disponibilidade de recursos nos planos de proteção de ameaça avançadas (ATP)

Todos os recursos estão listados abaixo. Quando o Exchange Online é mencionado, ele normalmente refere-se à família de serviços do Office 365 Enterprise.
  
|**Recurso**|**ATP autônoma**|**Proteção do Exchange Online**|
|:-----|:-----|:-----|
|Links Seguros  <br/> |Sim  <br/> |Não  <br/> |
|Anexos Seguros  <br/> |Sim  <br/> |Não  <br/> |
|Realizar a falsificação de inteligência de dados  <br/> |Sim  <br/> |Não  <br/> |
|Quarentena  <br/> |Sim  <br/> |Sim  <br/> |
|Recursos avançados de AntiPhishing  <br/> |Sim  <br/> |Não  <br/> |
   
## <a name="advanced-threat-protection-atp-capabilities"></a>Recursos de proteção (ATP) de ameaça avançado

### <a name="safe-links"></a>Links Seguros

O recurso de Links de seguros ATP protege proativamente seus usuários contra hyperlinks maliciosos em uma mensagem. A proteção permanece sempre que clicarem no link, como links mal-intencionado dinamicamente são bloqueadas enquanto boa links podem ser acessados.
  
### <a name="safe-attachments"></a>Anexos Seguros

O recurso Anexos Seguros protege você contra vírus e malware desconhecidos e fornece proteção de dia zero para seu sistema de mensagens. Todas as mensagens e os anexos que não tenham uma assinatura de vírus/malware conhecida são roteados para um ambiente especial onde a ATP usa uma variedade de técnicas de aprendizagem e análise automática para detectar conteúdo mal-intencionado. Se nenhuma atividade suspeita for detectada, a mensagem será liberada para entrega na caixa de correio. 
  
### <a name="spoof-intelligence"></a>Realizar a falsificação de inteligência de dados

Realizar a falsificação intelligence detecta quando um remetente parece estar enviando emails em nome de uma ou mais contas de usuário dentro de um dos domínios da sua organização. Ele permite que você revise todos os remetentes que são falsificação de seu domínio e então optar por permitir que o remetente continuar ou bloquear o destinatário. Realizar a falsificação de inteligência de dados está disponível na segurança &amp; Centro de conformidade, na página Configurações do anti-spam.
  
### <a name="quarantine"></a>Quarentena

Mensagens identificadas pelo serviço do Office 365 como spam, emails em massa, email de phishing, que contêm malware, ou porque elas correspondem a uma regra de fluxo de email pode ser enviada para quarentena. Por padrão, o Office 365 envia mensagens de phishing e mensagens que contêm malware diretamente para a quarentena. Os usuários autorizados podem examinar, excluir ou gerenciar mensagens de email enviadas para quarentena.
  
### <a name="advanced-anti-phishing-capabilities"></a>Recursos avançados de AntiPhishing

Esse recurso usa os modelos de aprendizado de máquina para detectar mensagens de phishing. 
  
