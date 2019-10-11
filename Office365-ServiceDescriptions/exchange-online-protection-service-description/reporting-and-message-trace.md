---
title: Rastreamento de mensagens e relatórios
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- reporting-and-message-trace-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9263f99-5921-44fd-bb4c-0d487b59a656
description: O Microsoft Proteção do Exchange Online (EOP) oferece muitos relatórios diferentes que podem ajudá-lo a determinar o status e a integridade gerais de sua organização. Alguns relatórios estão disponíveis no centro de administração do Microsoft 365, enquanto outros estão disponíveis no centro de administração do Exchange (Eat).
ms.openlocfilehash: b87d81210cce585d8e5ccf9d8d52456286bfab91
ms.sourcegitcommit: 3d180fb603896239b30d9db6ba865843c29801b0
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/10/2019
ms.locfileid: "37442706"
---
# <a name="reporting-and-message-trace"></a>Rastreamento de mensagens e relatórios

O Microsoft Proteção do Exchange Online (EOP) oferece muitos relatórios diferentes que podem ajudá-lo a determinar o status e a integridade gerais de sua organização. Alguns relatórios estão disponíveis no centro de administração do Microsoft 365, enquanto outros estão disponíveis no centro de administração do Exchange (Eat).

Você está procurando informações sobre todas as características EOP? Confira o [Descrição do serviço de proteção do Exchange Online](exchange-online-protection-service-description.md).

## <a name="microsoft-365-admin-center-reports"></a>Relatórios do centro de administração do Microsoft 365

A página de relatórios no centro de administração do Microsoft 365 fornece informações sobre o tráfego de mensagens, detecções de spam e malware e mensagens afetadas por regras de fluxo de emails (também conhecidas como regras de transporte) ou políticas de prevenção de perda de dados (DLP). Os relatórios aprimorados para proteção, regras e DLP fornecem uma experiência interativa de relatório aos administradores do EOP. Esses relatórios fornecem dados resumidos e a capacidade de busca detalhada em cada mensagem.

Para obter informações mais detalhadas sobre esses relatórios, consulte [usar relatórios de proteção de email no Office 365 para exibir dados sobre detecções de malware, spam e de regra](https://docs.microsoft.com/exchange/monitoring/use-mail-protection-reports).

## <a name="reporting-using-web-services"></a>Criar relatórios usando serviços Web

> [!NOTE]
> Muitos dos recursos de relatórios baseados em REST e cmdlets relacionados foram preteridos em janeiro de 2018. Para obter informações sobre os relatórios do Microsoft Graph substitutos disponíveis no Office 365, consulte os subtópicos sobre [como trabalhar com os relatórios de uso do Office 365 no Microsoft Graph](https://go.microsoft.com/fwlink/p/?LinkID=865135).

Não disponível para clientes autônomos do EOP. Você pode usar o serviço Web de relatório de locatários do REST/OData para coletar programaticamente relatórios resumidos e detalhados sobre dados de mensagens e pode exibir os dados em uma página da Web em um portal de gerenciamento da Web personalizado.

## <a name="message-trace"></a>Rastreamento de mensagens

O recurso de rastreamento de mensagens no EAC permite que um administrador acompanhe as mensagens de email conforme elas passam pelo EOP. Ele o ajuda a determinar se uma mensagem de email direcionada foi recebida, rejeitada, adiada ou entregue pelo serviço. Mostra também quais as ações ocorreram com a mensagem antes do status final. Obtendo informações detalhadas sobre uma mensagem específica permite que você responde com eficiência às perguntas do usuário, solucione problemas de fluxo de email, valide alterações de política e alivie a necessidade de entrar em contato com o suporte técnico para assistência. Para obter mais informações, consulte [executar um rastreamento de mensagem e exibir os resultados no centro de administração do Exchange](https://docs.microsoft.com/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results).

## <a name="feature-availability"></a>Disponibilidade do recurso

Para exibir a disponibilidade de recursos nos planos do Office 365 nas opções autônomas e nas soluções locais, consulte [Descrição do serviço de proteção do Exchange Online](exchange-online-protection-service-description.md).
