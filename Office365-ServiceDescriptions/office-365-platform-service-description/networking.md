---
title: Sistema de rede
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: A Microsoft oferece suporte aos recursos de rede a seguir.
ms.openlocfilehash: 0f0554bdd907a6f0a37299dc3e38e5f778e7187e
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132325"
---
# <a name="networking"></a>Rede

A Microsoft oferece suporte aos recursos de rede a seguir.
  
## <a name="ports-protocols-and-ip-addresses"></a>Portas, protocolos e endereços IP

A Microsoft usa endereços IPv4 e IPv6. O uso de endereçamento IPv6 é opcional e não é obrigatório para estabelecer conexão com o Office 365. Nem todos os recursos do Microsoft 365 estão totalmente habilitados usando IPv6. Para obter mais informações sobre o suporte a IPv6, confira [suporte a IPv6 nos serviços Microsoft](https://docs.microsoft.com/office365/enterprise/ipv6-support).
  
A Microsoft mantém uma lista de endereços IP permitidos na ajuda da Microsoft. Para obter mais informações, consulte [URLs e intervalos de endereços IP](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges). No caso do Office 365 operado pela 21Vianet, confira [URLs e endereços IP para o Office 365 operado pela 21Vianet](https://docs.microsoft.com/office365/enterprise/managing-office-365-endpoints). Em relação ao Office 365 Germany, confira [Pontos de extremidade do Office 365 Germany](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).
  
> [!IMPORTANT]
> We strongly recommend that you enable routing to the root domain names listed in the articles above (such as \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com) instead of routing to specific IP address subnets. Relying on IP address subnets runs the risk of outages for your users as changes are made. 
  
## <a name="bandwidth-requirements"></a>Requisitos de largura de banda

Para saber mais sobre os requisitos de largura de banda, confira o artigo [Planejamento de rede e ajuste de desempenho do Office 365](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance).
  
## <a name="connecting-to-microsoft"></a>Conexão com a Microsoft

Todas as conexões com a Microsoft são realizadas pela Internet pública ou por uma conexão expressa do Azure para o Azure e são protegidas por SSL, conforme apropriado. O Azure ExpressRoute permite a conexão direta com a rede global da Microsoft, ignorando a Internet. Um parceiro de rede da Microsoft fornece a conectividade com a rede global da Microsoft.
  
Para saber mais sobre o Azure ExpressRoute, confira [Azure ExpressRoute para Office 365.](https://aka.ms/expressrouteoffice365)
  
### <a name="wan-accelerators"></a>Aceleradores da WAN

Microsoft does not provide support for customer-owned WAN acceleration and caching devices with Office 365. If you decide to use a WAN optimization controller to improve performance under conditions of high latency or low bandwidth, you'll need to disable it while troubleshooting service requests with Microsoft, and work with your device vendor for device support. For more information, see [WAN Acceleration and caching devices with Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).
  
## <a name="the-global-microsoft-network"></a>A rede global de Microsoft

A infraestrutura de rede da Microsoft é composta por um amplo portfólio global de data centers, servidores, redes de distribuição de conteúdo, nós de computação de borda e redes de fibra ótica para fornecer distribuição global de serviços. Instrumentação e monitoramento de serviços sofisticados se integram aos níveis mais profundos com cada componente, oferecendo visibilidade no datacenter, backbone de rede, trocas de internet e muito mais para ajudar a localizar, diagnosticar e gerenciar a causa das interrupções que surgirem. A rede é construída para manter a capacidade suficiente, mesmo para interrupções de rede em larga escala, sem degradação de desempenho. Para obter mais informações, consulte [Microsoft Global Network](https://docs.microsoft.com/azure/networking/microsoft-global-network). 
  
Para manter a confidencialidade e integridade dos dados do cliente, a Microsoft mantém as redes de serviços de consumidor separadas das redes Microsoft. Várias técnicas são usadas para controlar fluxos de informações, incluindo, mas não limitadas a:
  
- Physical separation. Network segments are physically separated by routers that are configured to prevent specific communication patterns.
    
- Logical separation. Virtual LAN (VLAN) technology is used to further separate communications.
    
- Firewalls. Firewalls e outros pontos de imposição de segurança de rede são usados para limitar trocas de dados com sistemas expostos à Internet e para isolar sistemas de sistemas de back-end gerenciados pela Microsoft. 
    
- Restrições de protocolo.
    
Para saber mais, visite a [Central de Confiabilidade do Office 365](https://www.microsoft.com/trust-center). 
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos nos planos, consulte [Microsoft 365 and Office 365 Platform Service Description](office-365-platform-service-description.md).
  

