---
title: Relatórios e rastreamento de mensagem no Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- reporting-and-message-trace-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9263f99-5921-44fd-bb4c-0d487b59a656
description: Leia este artigo para saber mais sobre Relatórios e rastreamento de mensagens no Microsoft Exchange Online Protection (EOP).
ms.openlocfilehash: 8b593faea343d742c2f57ce430457e1803ba75b5a135d46f338eaed0e76d2ca6
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 08/06/2021
ms.locfileid: "54664074"
---
# <a name="reporting-and-message-trace-in-exchange-online-protection"></a>Relatórios e rastreamento de mensagem no Exchange Online Protection

O Microsoft Proteção do Exchange Online (EOP) oferece muitos relatórios diferentes que podem ajudá-lo a determinar o status e a integridade gerais de sua organização. Alguns relatórios estão disponíveis no Centro de administração do Microsoft 365, enquanto outros estão disponíveis no centro de administração Exchange (EAC).

Você está procurando informações sobre todas as características EOP? Consulte a [descrição Proteção do Exchange Online serviço](exchange-online-protection-service-description.md).

## <a name="microsoft-365-admin-center-reports"></a>Relatórios do Centro de administração do Microsoft 365

A página Relatórios no Centro de administração do Microsoft 365 fornece informações sobre tráfego de mensagens, detecções de spam e malware e mensagens afetadas por regras de fluxo de emails (também conhecidas como regras de transporte) ou políticas de prevenção contra perda de dados (DLP). Os relatórios aprimorados para proteção, regras e DLP fornecem uma experiência interativa de relatório aos administradores do EOP. Esses relatórios fornecem dados resumidos e a capacidade de busca detalhada em cada mensagem.

Para obter informações mais detalhadas sobre esses relatórios, consulte [Use mail protection reports to view data about malware, spam, and rule detections](/exchange/monitoring/use-mail-protection-reports).

## <a name="reporting-using-web-services"></a>Criar relatórios usando serviços Web

> [!NOTE]
> Muitos dos recursos de relatório baseados em REST e cmdlets relacionados foram preterido em janeiro de 2018. Para obter informações sobre os relatórios de substituição disponíveis da Microsoft Graph no Office 365, consulte os subtópicos de Trabalhar com relatórios de uso no [Microsoft Graph](/graph/api/resources/report).

Não disponível para clientes autônomos do EOP. Você pode usar o serviço Web REST/OData Tenant Reporting para coletar de forma programática relatórios resumidos e detalhados sobre dados de mensagens, e você pode exibir os dados em uma página da Web em um portal de gerenciamento da Web personalizado.

## <a name="message-trace"></a>Rastreamento de mensagens

O recurso de rastreamento de mensagens no EAC permite que você, como administrador, siga mensagens de email enquanto elas passam pelo EOP. Ele o ajuda a determinar se uma mensagem de email direcionada foi recebida, rejeitada, adiada ou entregue pelo serviço. Mostra também quais as ações ocorreram com a mensagem antes do status final. Obtendo informações detalhadas sobre uma mensagem específica permite que você responde com eficiência às perguntas do usuário, solucione problemas de fluxo de email, valide alterações de política e alivie a necessidade de entrar em contato com o suporte técnico para assistência. Para obter mais informações, [consulte Run a message trace and view the results in the Exchange admin center](/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results).

## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos entre planos, opções autônomas e soluções locais, consulte [Proteção do Exchange Online descrição do serviço.](exchange-online-protection-service-description.md)