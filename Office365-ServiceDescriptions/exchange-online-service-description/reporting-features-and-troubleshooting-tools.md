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
description: O Microsoft Exchange Online oferece uma variedade de recursos de relatório dentro e fora do centro de administração do Exchange (Eat).
ms.openlocfilehash: 16bcea7f90115ca3238e502e5b57d756d24025ba
ms.sourcegitcommit: 4abe1be8a63406e8a8c1a4a69f95386906ea1499
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 02/22/2019
ms.locfileid: "30210214"
---
# <a name="reporting-features-and-troubleshooting-tools"></a>Recursos de Relatórios e Ferramentas de Solução de Problemas

O Microsoft Exchange Online oferece uma variedade de recursos de relatório dentro e fora do centro de administração do Exchange (Eat).
  
## <a name="reporting-features"></a>Recursos de relatório

Os clientes do Exchange Online podem acessar relatórios no centro de administração do Microsoft 365, baixando uma pasta de trabalho de relatórios do Excel ou usando serviços Web.
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a>Relatórios no centro de administração do Microsoft 365

Há relatórios na página relatórios no centro de administração do Microsoft 365 que fornecem informações resumidas sobre caixas de correio e grupos. Por exemplo, um relatório lista o número de grupos criados e excluídos por dia, semana, mês ou ano. Também há relatórios resumidos para caixas de correio novas e excluídas e caixas de correio ativas e inativas. 
  
Além disso, a página de relatórios no centro de administração do Microsoft 365 contém relatórios de dados de mensagens, que fornecem informações sobre o tráfego de mensagens, detecções de spam e malware e mensagens afetadas pelas regras de transporte do Exchange ou pela DLP (prevenção contra perda de dados) Diretrizes. Os relatórios aprimorados para proteção, regras e DLP oferecem uma experiência de relatório interativa para administradores do Exchange Online. Esses relatórios fornecem dados de resumo e a capacidade de detalhar detalhes sobre mensagens individuais.
  
Para obter mais informações sobre quais relatórios estão disponíveis em cada assinatura do Office 365 [](../office-365-platform-service-description/reports.md), consulte Reports. Para obter informações mais detalhadas sobre a página de relatórios no centro de administração do Microsoft 365, consulte [Exibir e baixar relatórios sobre o uso do serviço no office 365](https://go.microsoft.com/fwlink/p/?LinkId=401187) e [usar relatórios de proteção de email no Office 365 para exibir dados sobre detecções de malware, spam e regras ](https://go.microsoft.com/fwlink/p/?LinkID=401102).
  
### <a name="reporting-using-the-excel-reporting-workbook"></a>Relatórios usando a pasta de trabalho de relatório do Excel

Você também pode usar a pasta de trabalho de relatórios do Excel 2013 para exibir relatórios resumidos com recursos de busca detalhada. No enTanto, recomendamos o uso dos relatórios do centro de administração do Microsoft 365 aprimorados. A pasta de trabalho de relatórios do Excel 2013 está planejada para ser preterida no futuro. Para obter mais informações gerais e links para baixar e instalar a pasta de trabalho, consulte a [página de download](https://go.microsoft.com/fwlink/p/?LinkId=271776)a seguir. Para obter informações sobre como usar a pasta de trabalho, confira [relatórios de proteção de email usando a pasta de trabalho de relatórios do Excel](https://go.microsoft.com/fwlink/p/?LinkId=285211). 
  
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
  

