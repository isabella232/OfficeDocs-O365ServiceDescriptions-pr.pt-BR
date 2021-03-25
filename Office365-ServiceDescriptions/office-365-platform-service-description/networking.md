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
description: A Microsoft dá suporte aos seguintes recursos de rede.
ms.openlocfilehash: 318437ce65c5ced55d42e798bf76774cda6708f9
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173016"
---
# <a name="networking"></a>Rede

A Microsoft dá suporte aos seguintes recursos de rede.
  
## <a name="ports-protocols-and-ip-addresses"></a>Portas, protocolos e endereços IP

A Microsoft usa endereços IPv4 e IPv6. O uso de endereçamento IPv6 é opcional e não é obrigatório para estabelecer conexão com o Office 365. Nem todos os recursos do Microsoft 365 estão totalmente habilitados usando IPv6. Para obter mais informações sobre o suporte a Ipv6, consulte [Suporte para IPv6 nos serviços microsoft](/office365/enterprise/ipv6-support).
  
A Microsoft mantém uma lista de endereços IP permitidos na ajuda da Microsoft. Para obter mais informações, [consulte URLs e intervalos de endereços IP](/office365/enterprise/urls-and-ip-address-ranges). No caso do Office 365 operado pela 21Vianet, confira [URLs e endereços IP para o Office 365 operado pela 21Vianet](/office365/enterprise/managing-office-365-endpoints). Em relação ao Office 365 Germany, confira [Pontos de extremidade do Office 365 Germany](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).
  
> [!IMPORTANT]
> Nós recomendamos enfaticamente que você habilite o roteamento para os nomes de domínio raiz listados acima (como \*.Outlook.com, \*.MicrosoftOnline.com e \*.SharePoint.com) em vez de fazer o roteamento para sub-redes de endereços IP específicos. A dependência de sub-redes de endereço IP apresenta o risco de falhas para seus usuários à medida que as alterações são feitas. 
  
## <a name="bandwidth-requirements"></a>Requisitos de largura de banda

Para saber mais sobre os requisitos de largura de banda, confira o artigo [Planejamento de rede e ajuste de desempenho do Office 365](/office365/enterprise/network-planning-and-performance).
  
## <a name="connecting-to-microsoft"></a>Conectando-se à Microsoft

Todas as conexões com a Microsoft são feitas pela Internet pública ou por meio de uma conexão privada do Azure ExpressRoute e são protegidas pelo SSL conforme apropriado. O Azure ExpressRoute permite conectar-se diretamente à rede global da Microsoft, ignorando a Internet. Um parceiro de rede da Microsoft fornece a conectividade com a rede global da Microsoft.
  
Para saber mais sobre o Azure ExpressRoute, confira [Azure ExpressRoute para Office 365.](/microsoft-365/enterprise/azure-expressroute)
  
### <a name="wan-accelerators"></a>Aceleradores da WAN

A Microsoft não fornece suporte para dispositivos de aceleração de WAN e cache com o Office 365. Se optar por usar um controlador de otimização de WAN para aumentar o desempenho em condições de alta latência ou baixa largura de banda, você deve desabilitá-lo enquanto soluciona problemas de solicitações de serviço com a Microsoft e solicitar suporte ao fornecedor do dispositivo. Para saber mais, confira o artigo [Usando dispositivos de aceleração de WAN e cache com o Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).
  
## <a name="the-global-microsoft-network"></a>A rede global de Microsoft

A infraestrutura de rede da Microsoft é composta por um grande portfólio global de data centers, servidores, redes de distribuição de conteúdo, nós de computação de borda e redes de fibra óptica para fornecer distribuição global de serviços. Instrumentação e monitoramento de serviços sofisticados se integram aos níveis mais profundos com cada componente, oferecendo visibilidade no datacenter, backbone de rede, trocas de internet e muito mais para ajudar a localizar, diagnosticar e gerenciar a causa das interrupções que surgirem. A rede é construída para manter a capacidade suficiente, mesmo para interrupções de rede em larga escala, sem degradação de desempenho. Para obter mais informações, consulte [Microsoft Global Network](/azure/networking/microsoft-global-network). 
  
Para manter a confidencialidade e a integridade dos dados do cliente, a Microsoft mantém as redes de serviços de consumidor separadas das redes da Microsoft. Várias técnicas são usadas para controlar fluxos de informações, incluindo, mas não limitadas a:
  
- Separação física. Os segmentos de rede são fisicamente separados por roteadores que são configurados para evitar padrões de comunicação específicos.
    
- Separação lógica. A tecnologia Virtual LAN (VLAN) é usada para separar ainda mais a comunicação.
    
- Firewalls. Firewalls e outros pontos de imposição de segurança de rede são usados para limitar as trocas de dados com sistemas expostos à Internet e para isolar sistemas de sistemas back-end gerenciados pela Microsoft. 
    
- Restrições de protocolo.
    
Para saber mais, visite a [Central de Confiabilidade do Office 365](https://www.microsoft.com/trust-center). 
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos entre planos, consulte a descrição do serviço da plataforma [do Microsoft 365 e do Office 365.](office-365-platform-service-description.md)
