---
title: Recursos de relatórios e ferramentas de solução de problemas
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Online oferece uma variedade de recursos de relatório dentro e fora do centro de administração Exchange (EAC).
ms.openlocfilehash: fb6af583f9bb51954b57a92d907ab19a935f5f3c6ab9be196f7ca56240189571
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 08/06/2021
ms.locfileid: "54663654"
---
# <a name="reporting-features-and-troubleshooting-tools"></a>Recursos de relatórios e ferramentas de solução de problemas

Microsoft Exchange Online oferece uma variedade de recursos de relatório dentro e fora do centro de administração Exchange (EAC).
  
## <a name="reporting-features"></a>Recursos de relatório

Exchange Online clientes podem acessar relatórios no Centro de administração do Microsoft 365, baixando uma Excel de trabalho de relatório ou usando serviços Web.
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a>Relatórios no Centro de administração do Microsoft 365

Há relatórios na página Relatórios no Centro de administração do Microsoft 365 que fornecem informações resumidas sobre caixas de correio e grupos. Por exemplo, um relatório lista o número de grupos criados e excluídos por dia, semana, mês ou ano. Há também relatórios resumidos de caixas de correio novas e excluídas e caixas de correio ativas e inativas. 
  
Além disso, a página Relatórios no Centro de administração do Microsoft 365 contém relatórios de dados de mensagens, que fornecem informações sobre tráfego de mensagens, detecções de spam e malware e mensagens afetadas por regras de transporte Exchange ou políticas de prevenção contra perda de dados (DLP). Os relatórios aprimorados para proteção, regras e DLP fornecem uma experiência interativa de relatório aos administradores do Exchange Online. Esses relatórios fornecem dados resumidos e a capacidade de busca detalhada em cada mensagem.
  
Para obter mais informações sobre quais relatórios estão disponíveis em cada assinatura, consulte [Reports](../office-365-platform-service-description/reports.md). Para obter informações mais detalhadas sobre a página Relatórios no Centro de administração do Microsoft 365, consulte Exibir e baixar relatórios sobre o uso do serviço no [Office 365](/microsoft-365/admin/activity-reports/activity-reports) e Usar relatórios de proteção de email para exibir dados sobre malware, spam e detecções de [regras.](/exchange/monitoring/use-mail-protection-reports)
  
### <a name="reporting-using-the-excel-reporting-workbook"></a>Relatórios usando a pasta de trabalho de relatório do Excel

Você também pode usar a pasta de trabalho de relatórios do Excel 2013 para visualizar relatórios resumidos com recursos de busca detalhada. No entanto, recomendamos usar os relatórios de Centro de administração do Microsoft 365 aprimorados. A pasta de trabalho de relatórios do Excel 2013 está prevista para ficar obsoleta no futuro. Para saber mais de visão geral e links para baixar e instalar a pasta de trabalho, confira a seguinte [página de download](https://go.microsoft.com/fwlink/p/?LinkId=271776). Para informações sobre como usar a pasta de trabalho, confira [Relatórios de Proteção de Email usando a Pasta de Trabalho de Relatório do Excel](/previous-versions/exchange-server/exchange-150/jj945734(v=exchg.150)). 
  
### <a name="reporting-using-web-services"></a>Criar relatórios usando serviços Web

O acesso a relatórios resumidos e detalhados sobre caixas de correio, grupos e dados de mensagens está disponível usando o serviço Web REST/OData Tenant Reporting, que é uma interface programática que permite criar relatórios personalizados. Para obter mais informações, [consulte Office 365 Relatórios de serviços Web](/previous-versions/office/developer/o365-enterprise-developers/jj984325(v=office.15)).
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a>Ferramentas de recursos e solução de problemas de relatório no EAC

As ferramentas de recursos de relatório e de solução de problemas a seguir estão disponíveis no centro de administração do Exchange.
  
### <a name="trace-an-email-message"></a>Rastrear uma mensagem de email

O recurso de rastreamento de mensagens permite que você, como administrador, siga mensagens de email à medida que elas passam pelo serviço Exchange Online de mensagens. Ele o ajuda a determinar se uma mensagem de email direcionada foi recebida, rejeitada, adiada ou entregue pelo serviço. Isso permite responder com eficiências às perguntas dos usuários e solucionar problemas de fluxo de emails e diminui a necessidade de entrar em contato com o suporte técnico para solicitar assistência.
  
> [!IMPORTANT]
> Para solucionar problemas e tendências gerais, use as ferramentas de relatório para obter esses dados. Para pontos específicos únicos em que são necessários detalhes sobre uma mensagem, use a ferramenta de rastreamento de mensagem. 
  
Para saber mais sobre o recurso de rastreamento de mensagens, confira [Rastrear uma Mensagem de Email](/exchange/monitoring/trace-an-email-message/trace-an-email-message).
  
### <a name="auditing-reports"></a>Relatórios de auditoria

Você pode usar o log de auditoria para solucionar problemas de configuração controlando alterações específicas feitas pelos administradores e para ajudar você a atender aos requisitos normativos, de conformidade e de litígio. O Exchange Online fornece dois tipos de log de auditoria:
  
- Log de auditoria do administrador registra qualquer ação executada por um administrador. Isso pode ajudá-lo a solucionar problemas de configuração ou identificar a causa de problemas relacionados a segurança ou conformidade. 
    
- O log de auditoria de caixas de correio grava sempre que uma caixa de correio é acessada por alguém que não seja o proprietário da caixa de correio. Isso pode ajudá-lo a determinar quem acessou a caixa de correio e o que a pessoa fez. 
    
Para saber mais sobre o log de auditoria, confira [Relatórios de Auditoria](/exchange/security-and-compliance/exchange-auditing-reports/exchange-auditing-reports).
  
### <a name="unified-messaging-reports"></a>Relatórios de Unificação de Mensagens

Você pode usar esses relatórios para monitorar e solucionar problemas de UM (Unificação de Mensagens) em sua organização do Exchange Online. Para saber mais, confira [Executar Relatórios para Chamadas de Caixa Postal](/exchange/voice-mail-unified-messaging/run-voice-mail-call-reports/run-voice-mail-call-reports).
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos entre planos, opções autônomas e soluções locais, consulte [Exchange Online descrição do serviço.](exchange-online-service-description.md)
