---
title: Recursos de Relatórios e Ferramentas de Solução de Problemas
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Online oferece uma variedade de recursos e sair do Centro de administração do Exchange (EAC) de relatório.
ms.openlocfilehash: b95ab58d2ec09f5e6bae32a3902e92deb75d789f
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24034801"
---
# <a name="reporting-features-and-troubleshooting-tools"></a>Recursos de Relatórios e Ferramentas de Solução de Problemas

Microsoft Exchange Online oferece uma variedade de recursos e sair do Centro de administração do Exchange (EAC) de relatório.
  
## <a name="reporting-features"></a>Recursos de relatório

Os clientes do Exchange Online podem acessar relatórios no centro de administração do Office 365, baixando uma pasta de trabalho de relatório do Excel ou usando serviços da Web.
  
### <a name="reporting-in-the-office-365-admin-center"></a>Relatórios no centro de administração do Office 365

Há relatórios na página Relatórios do centro de administração do Microsoft Office 365 que fornecem informações resumidas sobre caixas de correio e grupos. Por exemplo, um relatório lista o número de grupos criados e excluídos por dia, semana, mês ou ano. Há também relatórios resumidos de caixas de correio novas e excluídas e caixas de correio ativas e inativas. 
  
Além disso, a página Relatórios do centro de administração do Microsoft Office 365 contém relatórios de dados de mensagens que fornecem informações sobre tráfego de mensagens, detecções de spam e malware e mensagens afetadas pelas Regras de Transporte do Exchange ou políticas de políticas de Prevenção de Perda de Dados (DLP). Os relatórios aprimorados para proteção, regras e DLP fornecem uma experiência interativa de relatório aos administradores do Exchange Online. Esses relatórios fornecem dados resumidos e a capacidade de busca detalhada em cada mensagem.
  
Para saber mais sobre quais relatórios estão disponíveis com cada assinatura do Office 365, confira [Relatórios](../office-365-platform-service-description/reports.md). Para saber mais detalhes sobre a página Relatórios do centro de administração do Office 365, confira [Exibir e baixar relatórios sobre o uso do serviço no Office 365](https://go.microsoft.com/fwlink/p/?LinkId=401187) e [Usar relatórios de proteção de email no Office 365 para exibir dados sobre detecções de malware, spam e de regra](https://go.microsoft.com/fwlink/p/?LinkID=401102).
  
### <a name="reporting-using-the-excel-reporting-workbook"></a>Relatórios usando a pasta de trabalho de relatório do Excel

Você também pode usar a pasta de trabalho de relatórios do Excel 2013 para visualizar relatórios resumidos com recursos de busca detalhada. No entanto, em vez disso, recomendamos a utilização de relatórios aprimorados do centro de administração do Office 365. A pasta de trabalho de relatórios do Excel 2013 está prevista para ficar obsoleta no futuro. Para saber mais de visão geral e links para baixar e instalar a pasta de trabalho, confira a seguinte [página de download](https://go.microsoft.com/fwlink/p/?LinkId=271776). Para informações sobre como usar a pasta de trabalho, confira [Relatórios de Proteção de Email usando a Pasta de Trabalho de Relatório do Excel](https://go.microsoft.com/fwlink/p/?LinkId=285211). 
  
### <a name="reporting-using-web-services"></a>Criar relatórios usando serviços Web

O acesso aos relatórios de resumo e detalhados sobre caixas de correio, grupos e dados de mensagens está disponível por meio do uso do serviço Web de Relatório de Locatário REST/OData, que é uma interface programática que permite criar relatórios personalizados. Para saber mais, confira [Serviços Web de Relatórios do Office 365](https://go.microsoft.com/fwlink/p/?LinkId=287041).
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a>Ferramentas de recursos e solução de problemas de relatório no EAC

As ferramentas de recursos de relatório e de solução de problemas a seguir estão disponíveis no centro de administração do Exchange.
  
### <a name="trace-an-email-message"></a>Rastrear uma mensagem de email

O recurso de rastreamento de mensagem permite que um administrador acompanhe as mensagens de email conforme elas passam pelo serviço Exchange Online. Ele o ajuda a determinar se uma mensagem de email direcionada foi recebida, rejeitada, adiada ou entregue pelo serviço. Isso permite responder com eficiências às perguntas dos usuários e solucionar problemas de fluxo de emails e diminui a necessidade de entrar em contato com o suporte técnico para solicitar assistência.
  
> [!IMPORTANT]
> Para solucionar problemas e tendências gerais, use as ferramentas de relatório para obter esses dados. Para pontos específicos únicos em que são necessários detalhes sobre uma mensagem, use a ferramenta de rastreamento de mensagem. 
  
Para saber mais sobre o recurso de rastreamento de mensagens, confira [Rastrear uma Mensagem de Email](https://go.microsoft.com/fwlink/p/?LinkId=271777).
  
### <a name="auditing-reports"></a>Relatórios de auditoria

Você pode usar o log de auditoria para solucionar problemas de configuração controlando alterações específicas feitas pelos administradores e para ajudar você a atender aos requisitos normativos, de conformidade e de litígio. O Exchange Online fornece dois tipos de log de auditoria:
  
- Log de auditoria do administrador registra qualquer ação executada por um administrador. Isso pode ajudá-lo a solucionar problemas de configuração ou identificar a causa de problemas relacionados a segurança ou conformidade. 
    
- O log de auditoria de caixas de correio grava sempre que uma caixa de correio é acessada por alguém que não seja o proprietário da caixa de correio. Isso pode ajudá-lo a determinar quem acessou a caixa de correio e o que a pessoa fez. 
    
Para saber mais sobre o log de auditoria, confira [Relatórios de Auditoria](https://go.microsoft.com/fwlink/p/?LinkId=271779).
  
### <a name="unified-messaging-reports"></a>Relatórios de Unificação de Mensagens

Você pode usar esses relatórios para monitorar e solucionar problemas de UM (Unificação de Mensagens) em sua organização do Exchange Online. Para saber mais, confira [Executar Relatórios para Chamadas de Caixa Postal](https://go.microsoft.com/fwlink/p/?LinkId=287042).
  
## <a name="feature-availability"></a>Disponibilidade do recurso

Para exibir a disponibilidade de recursos nos planos do Office 365 nas opções autônomas e nas soluções locais, consulte [Descrição de Serviço do Exchange Online](exchange-online-service-description.md).
  

