---
title: Sistema de rede
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: O Microsoft Office 365 oferece suporte aos recursos de rede a seguir.
ms.openlocfilehash: 2245e2e60333d0f1eb85e1243c49c0a04a4f62ec
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/07/2019
ms.locfileid: "30467898"
---
# <a name="networking"></a>Sistema de rede

O Microsoft Office 365 oferece suporte aos recursos de rede a seguir.
  
## <a name="ports-protocols-and-ip-addresses"></a>Portas, protocolos e endereços IP

O Office 365 usa endereços IPv4 e IPv6. O uso de endereçamento IPv6 é opcional e não é obrigatório para estabelecer conexão com o Office 365. Nem todos os recursos do Office 365 estão plenamente habilitados para uso com IPv6. Para saber mais sobre suporte a IPv6 no Office 365, confira [Suporte a IPv6 nos serviços do Office 365](https://go.microsoft.com/fwlink/?LinkID=785121&amp;clcid=0x409).
  
O Office 365 mantém uma lista de endereços IP permitidos na Ajuda do Office 365. Para saber mais, confira [URLs e intervalos de endereços IP do Office 365](https://go.microsoft.com/fwlink/p/?LinkID=243567). No caso do Office 365 operado pela 21Vianet, confira [URLs e endereços IP para o Office 365 operado pela 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733351&amp;clcid=0x409). Em relação ao Office 365 Germany, confira [Pontos de extremidade do Office 365 Germany](https://support.office.com/en-us/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).
  
> [!IMPORTANT]
> Nós recomendamos enfaticamente que você habilite o roteamento para os nomes de domínio raiz listados acima (como \*.Outlook.com, \*.MicrosoftOnline.com e \*.SharePoint.com) em vez de fazer o roteamento para sub-redes de endereços IP específicos. A dependência de sub-redes de endereço IP apresenta o risco de falhas para seus usuários à medida que as alterações são feitas. 
  
## <a name="bandwidth-requirements"></a>Requisitos de largura de banda

Para saber mais sobre os requisitos de largura de banda, confira o artigo [Planejamento de rede e ajuste de desempenho do Office 365](https://go.microsoft.com/fwlink/p/?LinkID=282467).
  
## <a name="connecting-to-office-365"></a>Conectando-se ao Office 365

Todas as conexões com o Office 365 são realizadas pela Internet pública ou por uma conexão da Rota Expressa do Microsoft Azure particular e são protegidas por SSL conforme apropriado. A Rota Expressa do Microsoft Azure permite a conexão direta com a rede global da Microsoft, ignorando a Internet. Um parceiro de rede da Microsoft fornece a conectividade com a rede global da Microsoft.
  
Para saber mais sobre o Azure ExpressRoute, confira [Azure ExpressRoute para Office 365.](https://aka.ms/expressrouteoffice365)
  
### <a name="wan-accelerators"></a>Aceleradores da WAN

A Microsoft não fornece suporte para dispositivos de aceleração de WAN e cache com o Office 365. Se optar por usar um controlador de otimização de WAN para aumentar o desempenho em condições de alta latência ou baixa largura de banda, você deve desabilitá-lo enquanto soluciona problemas de solicitações de serviço com a Microsoft e solicitar suporte ao fornecedor do dispositivo. Para saber mais, confira o artigo [Usando dispositivos de aceleração de WAN e cache com o Office 365](https://go.microsoft.com/fwlink/p/?LinkID=282468).
  
## <a name="the-global-microsoft-network"></a>A rede global de Microsoft

A infraestrutura de rede do Office 365 é composta por um grande portfólio global de datacenters, servidores, redes de distribuição de conteúdo, nós de computação de borda e redes de fibra óptica para oferecer uma distribuição global de serviços. Instrumentação e monitoramento de serviços sofisticados se integram aos níveis mais profundos com cada componente, oferecendo visibilidade no datacenter, backbone de rede, trocas de internet e muito mais para ajudar a localizar, diagnosticar e gerenciar a causa das interrupções que surgirem. A rede é construída para manter a capacidade suficiente, mesmo para interrupções de rede em larga escala, sem degradação de desempenho. Para saber mais, confira o [Global Foundation Services](https://go.microsoft.com/fwlink/p/?LinkID=282622). 
  
Para manter a confidencialidade e a integridade dos dados do cliente, a Microsoft mantém as redes de serviços ao consumidor separadas das redes do Office 365. Várias técnicas são usadas para controlar fluxos de informações, incluindo, mas não limitadas a:
  
- Separação física. Os segmentos de rede são fisicamente separados por roteadores que são configurados para evitar padrões de comunicação específicos.
    
- Separação lógica. A tecnologia Virtual LAN (VLAN) é usada para separar ainda mais a comunicação.
    
- Firewalls. Firewalls e outros pontos de imposição de segurança de rede são usados para limitar as trocas de dados com sistemas expostos à Internet e para isolar sistemas de sistemas de back-end gerenciados pela Microsoft. 
    
- Restrições de protocolo.
    
Para saber mais, visite a [Central de Confiabilidade do Office 365](https://go.microsoft.com/fwlink/p/?LinkID=282621). 
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos nos planos do Office 365, consulte [Descrição de Serviço da Plataforma Office 365](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx).
  

