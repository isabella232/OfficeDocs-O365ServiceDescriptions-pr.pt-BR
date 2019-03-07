---
title: Domínios
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/10/2017
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-domains
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 5c374309-8016-4f18-8f2a-bceeb863ca67
description: Ao adicionar um domínio, um assistente passo a passo ajuda você a adicionar usuários e converter os endereços de email do Office 365 e outros serviços para o nome da empresa. Após concluir o assistente, seu email comercial será redirecionado para o Office 365 em vez do atual provedor de email. Para saber mais, confira Adicionar seus usuários e domínios ao Office 365. Se você usar o Office 365 operado pela 21Vianet, confira verificar seu domínio.
ms.openlocfilehash: 1dc6d23afea52dd292d97b414e5b491d6d332dd7
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/07/2019
ms.locfileid: "30466368"
---
# <a name="domains"></a>Domínios

Ao adicionar um domínio, um assistente passo a passo ajuda você a adicionar usuários e converter os endereços de email do Office 365 e outros serviços para o nome da empresa. Após concluir o assistente, seu email comercial será redirecionado para o Office 365 em vez do atual provedor de email. Para saber mais, confira [Adicionar seus usuários e domínios ao Office 365](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611). Se você usa o Office 365 operado pela 21Vianet, confira [Verificar seu domínio](http://go.microsoft.com/fwlink/?LinkID=733344&amp;clcid=0x409).
  
## <a name="custom-domains"></a>Domínios personalizados
<a name="BKMK_CustomDomains"> </a>

Você pode adicionar até 900 domínios à sua assinatura do Office 365. Entretanto, não é possível adicionar um domínio ao Office 365 que já está usando em outro serviço de nuvem da Microsoft. Isso significa que você não pode adicionar o mesmo domínio a várias assinaturas do Office 365. Para saber mais, confira [perguntas frequentes sobre domínios](https://support.office.com/en-us/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a).
  
### <a name="second-and-third-level-domains"></a>Domínios de segundo e terceiro nível
<a name="BKMK_SecondAndThirdLevelDomains"> </a>

Com o Office 365 Enterprise e o Office 365 Business, você pode adicionar domínios de qualquer nível, incluindo domínios de terceiro nível, como marketing.contoso.com. Confira [Adicionar subdomínios personalizados ou vários domínios ao Office 365](http://go.microsoft.com/fwlink/?LinkID=733345&amp;clcid=0x409). Se você estiver usando o Office 365 operado pela 21Vianet, confira [Adicionar subdomínios personalizados ou vários domínios ao Office 365 operado pela 21Vianet](http://go.microsoft.com/fwlink/?LinkID=733346&amp;clcid=0x409).
  
## <a name="domain-verification-and-managing-dns-records"></a>Verificação de domínio e gerenciamento de registros DNS
<a name="BKMK_ManagingDNSRecords"> </a>

Com o Office 365, você pode gerenciar todos os seus registros DNS no seu provedor de host DNS ou permitir que o Office 365 configure e gerencie os registros DNS do seu domínio para você. Se continuar a gerenciar os registros, você vai alterar registros específicos para apontar para os serviços do Office 365, conforme necessário. Veja a lista de registradores de domínio para os quais fornecemos instruções passo a passo para adicionar os registros, inclusive os valores específicos a usar para cada registro, em [Criar registros DNS para o Office 365](https://go.microsoft.com/fwlink/p/?LinkID=270173) ou, se estiver usando o Office 365 operado pela 21Vianet, confira Criar registros DNS em qualquer provedor para o Office 365 operado pela 21Vianet. 
  
Se o Office 365 gerencia os registros DNS do seu domínio, você precisa primeiro mudar os registros de nameserver do seu domínio para apontar para o Office 365. Desse modo, o Office 365 vai configurar seus serviços do Office 365 e os registros DNS do seu domínio serão gerenciados no Office 365.
  
Se seu domínio estiver registrado no GoDaddy, o Office 365 poderá criar os registros necessários nesse serviço para você. 
  
Não importa onde seus registros DNS estão hospedados, você pode configurar os registros DNS para usar o seu domínio para a URL para um site público hospedado no Office 365 ou com um provedor de hospedagem diferente. 
  
Office 365 verifica proativamente seus registros DNS para localizar e ajudar a corrigir problemas de DNS. Se os seus registros DNS não coincidirem com o que esperamos que sejam, você receberá uma notificação no centro de administração do Microsoft 365, juntamente com informações que dizem como corrigir os possíveis problemas identificados.
  
Saiba mais em [Como o Office 365 gerencia registros DNS](https://go.microsoft.com/fwlink/p/?LinkID=270144) ou, para o Office 365 operado pela 21Vianet, confira [Criar registros DNS para o Office 365 ao gerenciar seus registros DNS](http://go.microsoft.com/fwlink/?LinkID=817326&amp;clcid=0x409).
  
## <a name="sharing-a-domain"></a>Compartilhamento de um domínio
<a name="BKMK_ManagingDNSRecords"> </a>

Você pode usar o Office 365 com alguns endereços de email para um domínio em Office 365, e alguns no seu provedor de email anterior. Isso é recomendado apenas para uso durante um piloto do Office 365, pois requer etapas de configuração adicionais e tem algumas limitações para os serviços do Office 365. Para obter mais informações, consulte:
  
- [Versão piloto do Office 365 para pequenas empresas](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [Versão piloto do Office 365 para grandes empresas (usando FastTrack)](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>Disponibilidade de recursos
<a name="BKMK_ManagingDNSRecords"> </a>

Para exibir a disponibilidade de recursos nos planos do Office 365, nas opções independentes e nas soluções locais, consulte [Descrição de serviço da plataforma Office 365](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx).
  

