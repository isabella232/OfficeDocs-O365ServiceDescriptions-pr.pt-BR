---
title: Recursos de relatórios e ferramentas de solução de problemas
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: O Microsoft Exchange Online oferece uma variedade de recursos de relatório dentro e fora do centro de administração do Exchange (Eat).
ms.openlocfilehash: f2cc51c9923be8d399fa2837e5b5fabe3117d5ba
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132595"
---
# <a name="reporting-features-and-troubleshooting-tools"></a>Recursos de relatórios e ferramentas de solução de problemas

O Microsoft Exchange Online oferece uma variedade de recursos de relatório dentro e fora do centro de administração do Exchange (Eat).
  
## <a name="reporting-features"></a>Recursos de relatório

Os clientes do Exchange Online podem acessar relatórios no centro de administração do Microsoft 365, baixando uma pasta de trabalho de relatórios do Excel ou usando serviços Web.
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a>Relatórios no centro de administração do Microsoft 365

Há relatórios na página relatórios no centro de administração do Microsoft 365 que fornecem informações resumidas sobre caixas de correio e grupos. Por exemplo, um relatório lista o número de grupos criados e excluídos por dia, semana, mês ou ano. Há também relatórios resumidos de caixas de correio novas e excluídas e caixas de correio ativas e inativas. 
  
Além disso, a página de relatórios no centro de administração do Microsoft 365 contém relatórios de dados de mensagens, que fornecem informações sobre o tráfego de mensagens, detecções de spam e malware e mensagens afetadas pelas regras de transporte do Exchange ou políticas de DLP (prevenção contra perda de dados). Os relatórios aprimorados para proteção, regras e DLP fornecem uma experiência interativa de relatório aos administradores do Exchange Online. Esses relatórios fornecem dados resumidos e a capacidade de busca detalhada em cada mensagem.
  
Para obter mais informações sobre quais relatórios estão disponíveis em cada assinatura, consulte [reports](../office-365-platform-service-description/reports.md). Para obter informações mais detalhadas sobre a página de relatórios no centro de administração do Microsoft 365, consulte [Exibir e baixar relatórios sobre o uso do serviço no Office 365](https://go.microsoft.com/fwlink/p/?LinkId=401187) e [usar relatórios de proteção de email para exibir dados sobre detecções de malware, spam e de regra](https://go.microsoft.com/fwlink/p/?LinkID=401102).
  
### <a name="reporting-using-the-excel-reporting-workbook"></a>Relatórios usando a pasta de trabalho de relatório do Excel

Você também pode usar a pasta de trabalho de relatórios do Excel 2013 para visualizar relatórios resumidos com recursos de busca detalhada. No entanto, recomendamos o uso dos relatórios do centro de administração do Microsoft 365 aprimorados. A pasta de trabalho de relatórios do Excel 2013 está prevista para ficar obsoleta no futuro. Para saber mais de visão geral e links para baixar e instalar a pasta de trabalho, confira a seguinte [página de download](https://go.microsoft.com/fwlink/p/?LinkId=271776). Para informações sobre como usar a pasta de trabalho, confira [Relatórios de Proteção de Email usando a Pasta de Trabalho de Relatório do Excel](https://go.microsoft.com/fwlink/p/?LinkId=285211). 
  
### <a name="reporting-using-web-services"></a>Criar relatórios usando serviços Web

O acesso aos relatórios de resumo e detalhado sobre caixas de correio, grupos e dados de mensagens está disponível usando o serviço Web de relatório de locatários do REST/OData, que é uma interface programática que permite criar relatórios personalizados. Para obter mais informações, consulte [Office 365 Reporting Web Services](https://go.microsoft.com/fwlink/p/?LinkId=287041).
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a>Ferramentas de recursos e solução de problemas de relatório no EAC

As ferramentas de recursos de relatório e de solução de problemas a seguir estão disponíveis no centro de administração do Exchange.
  
### <a name="trace-an-email-message"></a>Rastrear uma mensagem de email

O recurso de rastreamento de mensagens permite que você, como administrador, siga as mensagens de email à medida que elas passam pelo serviço do Exchange Online. Ele o ajuda a determinar se uma mensagem de email direcionada foi recebida, rejeitada, adiada ou entregue pelo serviço. Isso permite responder com eficiências às perguntas dos usuários e solucionar problemas de fluxo de emails e diminui a necessidade de entrar em contato com o suporte técnico para solicitar assistência.
  
> [!IMPORTANT]
> For troubleshooting general issues and trends, use the reporting tools to obtain such data. For single point specifics where details are needed about a message, use the message trace tool. 
  
Para saber mais sobre o recurso de rastreamento de mensagens, confira [Rastrear uma Mensagem de Email](https://go.microsoft.com/fwlink/p/?LinkId=271777).
  
### <a name="auditing-reports"></a>Relatórios de auditoria

You can use audit logging to troubleshoot configuration issues by tracking specific changes made by administrators and to help you meet regulatory, compliance, and litigation requirements. Exchange Online provides two types of audit logging:
  
- Administrator audit logging records any action performed by an administrator. This can help you troubleshoot configuration issues or identify the cause of security-related or compliance-related problems. 
    
- Mailbox audit logging records whenever a mailbox is accessed by someone other than the person who owns the mailbox. This can help you determine who has accessed a mailbox and what they've done. 
    
Para saber mais sobre o log de auditoria, confira [Relatórios de Auditoria](https://go.microsoft.com/fwlink/p/?LinkId=271779).
  
### <a name="unified-messaging-reports"></a>Relatórios de Unificação de Mensagens

You can use these reports to monitor and troubleshoot Unified Messaging (UM) in your Exchange Online organization. For more information, see [Run Reports for Voice Mail Calls](https://go.microsoft.com/fwlink/p/?LinkId=287042).
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos nos planos, nas opções autônomas e nas soluções locais, consulte [Descrição do serviço do Exchange Online](exchange-online-service-description.md).
  

