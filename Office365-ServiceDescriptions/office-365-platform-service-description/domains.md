---
title: Domínios
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-domains
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 5c374309-8016-4f18-8f2a-bceeb863ca67
description: Quando você adiciona um domínio, um assistente passo a passo ajuda você a adicionar usuários e converter seus endereços de email e outros serviços em seu nome comercial. Quando você conclui o assistente, seu email comercial começa a chegar à Microsoft em vez de ir para o provedor de email atual. Para saber mais, confira Adicionar seus usuários e domínios à Microsoft. Se você usa o Office 365 operado pela 21Vianet, confira Verificar seu domínio.
ms.openlocfilehash: 591364950fda2ebc070255a010435a74c4f2e6c41882236a1e35b987ba54c605
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 08/06/2021
ms.locfileid: "54662984"
---
# <a name="domains"></a>Domínios

Quando você adiciona um domínio, um assistente passo a passo ajuda você a adicionar usuários e converter seus endereços de email e outros serviços em seu nome comercial. Quando você conclui o assistente, seu email comercial começa a chegar à Microsoft em vez de ir para o provedor de email atual. Para saber mais, confira [Adicionar seus usuários e domínios à Microsoft](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611). Se você usa o Office 365 operado pela 21Vianet, confira [Verificar seu domínio](/office365/admin/setup/add-domain).
  
## <a name="custom-domains"></a>Domínios personalizados

Você pode adicionar até 900 domínios à sua assinatura (incluindo subdomas). Você não pode adicionar um domínio ao Microsoft 365 que já está usando em outro serviço de nuvem da Microsoft. Isso significa que você não pode adicionar o mesmo domínio a várias assinaturas. Para obter mais informações, consulte [Perguntas frequentes sobre domínios.](https://support.office.com/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a)
  
### <a name="second-and-third-level-domains"></a>Domínios de segundo e terceiro nível

Com Office 365 Enterprise e Microsoft 365 Apps para Pequenos e Médios negócios, você pode adicionar qualquer domínio de nível, incluindo domínios de terceiro nível, como marketing.contoso.com. Consulte [Adicionar subdomas personalizados ou vários domínios à Microsoft](/office365/admin/setup/domains-faq). Se você estiver usando o Office 365 operado pela 21Vianet, confira [Adicionar subdomínios personalizados ou vários domínios ao Office 365 operado pela 21Vianet](/office365/admin/setup/domains-faq).
  
## <a name="domain-verification-and-managing-dns-records"></a>Verificação de domínio e gerenciamento de registros DNS

Com Microsoft 365, você pode gerenciar todos os seus registros DNS em seu provedor de hospedagem DNS ou optar por ter a Microsoft configurada e gerenciar os registros DNS do seu domínio para você. Se você continuar a gerenciar os registros, altere registros específicos para apontar para serviços Microsoft conforme necessário. Para uma lista de registradores de domínio para os quais fornecemos instruções passo a passo para adicionar os registros, incluindo os valores específicos a usar para cada registro, consulte [Create DNS records](/office365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider) or, if you are using Office 365 operated by 21Vianet, see Create DNS records at any provider for Office 365 operated by 21Vianet. 
  
Se a Microsoft gerencia os registros DNS do seu domínio para você, primeiro você deve alternar os registros de nameserver do seu domínio para apontar para a Microsoft e, em seguida, a Microsoft configura seus serviços e, em seguida, os registros DNS do seu domínio são gerenciados na Microsoft.
  
Se seu domínio estiver registrado no GoDaddy, a Microsoft poderá criar os registros necessários para você no GoDaddy. 
  
Não importa onde seus registros DNS estão hospedados, você pode configurar os registros DNS para usar seu domínio para a URL de um site público hospedado na Microsoft ou com um provedor de hospedagem diferente. 
  
A Microsoft verifica proativamente seus registros DNS para encontrar e ajudar a corrigir problemas DNS. Se seus registros DNS não corresponderem ao que esperamos que sejam, você receberá uma notificação no Centro de administração do Microsoft 365, juntamente com informações que informam como corrigir os possíveis problemas que foram identificados.
  
Para obter mais informações, consulte [How Microsoft manages DNS records](/office365/admin/setup/domains-faq) or, for Office 365 operated by 21Vianet, see Create DNS records for Office 365 when you manage your DNS [records](/office365/admin/services-in-china/create-dns-records-when-you-manage-your-dns-records).
  
## <a name="sharing-a-domain"></a>Compartilhamento de um domínio

Você pode pilotar alguns endereços de email para um domínio na Microsoft e alguns no provedor de email anterior. Isso é recomendado apenas para uso durante um piloto, pois exige etapas adicionais de instalação e tem algumas limitações para serviços Microsoft. Para saber mais, confira:
  
- [Piloto Microsoft 365 para uma pequena empresa](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [Piloto Microsoft 365 para uma grande empresa (usando FastTrack)](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos Microsoft 365 para planos de negócios, opções autônomas e soluções locais, consulte Microsoft 365 descrição do serviço Office 365 [plataforma.](office-365-platform-service-description.md)
