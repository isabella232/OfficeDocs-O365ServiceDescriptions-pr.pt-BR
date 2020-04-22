---
title: Sistema de rede
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: A Microsoft oferece suporte aos recursos de rede a seguir.
ms.openlocfilehash: 62a474c9fe0161f7b4d876d8ca462e6bfe5e962d
ms.sourcegitcommit: 7a68dc894dde0d06fab014c56914a78aa8cda847
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/21/2020
ms.locfileid: "43639759"
---
# <a name="networking"></a><span data-ttu-id="fb8ca-103">Rede</span><span class="sxs-lookup"><span data-stu-id="fb8ca-103">Networking</span></span>

<span data-ttu-id="fb8ca-104">A Microsoft oferece suporte aos recursos de rede a seguir.</span><span class="sxs-lookup"><span data-stu-id="fb8ca-104">Microsoft supports the following networking features.</span></span>
  
## <a name="ports-protocols-and-ip-addresses"></a><span data-ttu-id="fb8ca-105">Portas, protocolos e endereços IP</span><span class="sxs-lookup"><span data-stu-id="fb8ca-105">Ports, protocols, and IP addresses</span></span>

<span data-ttu-id="fb8ca-106">A Microsoft usa endereços IPv4 e IPv6.</span><span class="sxs-lookup"><span data-stu-id="fb8ca-106">Microsoft uses IPv4 and IPv6 addresses.</span></span> <span data-ttu-id="fb8ca-107">O uso de endereçamento IPv6 é opcional e não é obrigatório para estabelecer conexão com o Office 365.</span><span class="sxs-lookup"><span data-stu-id="fb8ca-107">Use of IPv6 addressing is optional and not required for connectivity with Office 365.</span></span> <span data-ttu-id="fb8ca-108">Nem todos os recursos do Microsoft 365 estão totalmente habilitados usando IPv6.</span><span class="sxs-lookup"><span data-stu-id="fb8ca-108">Not all Microsoft 365 features are fully enabled using IPv6.</span></span> <span data-ttu-id="fb8ca-109">Para obter mais informações sobre o suporte a IPv6, confira [suporte a IPv6 nos serviços Microsoft](https://docs.microsoft.com/office365/enterprise/ipv6-support).</span><span class="sxs-lookup"><span data-stu-id="fb8ca-109">For more information about Ipv6 support, see [IPv6 support in Microsoft services](https://docs.microsoft.com/office365/enterprise/ipv6-support).</span></span>
  
<span data-ttu-id="fb8ca-110">A Microsoft mantém uma lista de endereços IP permitidos na ajuda da Microsoft.</span><span class="sxs-lookup"><span data-stu-id="fb8ca-110">Microsoft maintains a list of allowed IP addresses in the Microsoft help.</span></span> <span data-ttu-id="fb8ca-111">Para obter mais informações, consulte [URLs e intervalos de endereços IP](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).</span><span class="sxs-lookup"><span data-stu-id="fb8ca-111">For more information, see [URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).</span></span> <span data-ttu-id="fb8ca-112">No caso do Office 365 operado pela 21Vianet, confira [URLs e endereços IP para o Office 365 operado pela 21Vianet](https://docs.microsoft.com/office365/enterprise/managing-office-365-endpoints).</span><span class="sxs-lookup"><span data-stu-id="fb8ca-112">For Office 365 operated by 21Vianet, see [URLs and IP Addresses for Office 365 operated by 21Vianet](https://docs.microsoft.com/office365/enterprise/managing-office-365-endpoints).</span></span> <span data-ttu-id="fb8ca-113">Em relação ao Office 365 Germany, confira [Pontos de extremidade do Office 365 Germany](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).</span><span class="sxs-lookup"><span data-stu-id="fb8ca-113">For Office 365 Germany, see [Office 365 Germany endpoints](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="fb8ca-p103">Nós recomendamos enfaticamente que você habilite o roteamento para os nomes de domínio raiz listados acima (como \*.Outlook.com, \*.MicrosoftOnline.com e \*.SharePoint.com) em vez de fazer o roteamento para sub-redes de endereços IP específicos. A dependência de sub-redes de endereço IP apresenta o risco de falhas para seus usuários à medida que as alterações são feitas.</span><span class="sxs-lookup"><span data-stu-id="fb8ca-p103">We strongly recommend that you enable routing to the root domain names listed in the articles above (such as \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com) instead of routing to specific IP address subnets. Relying on IP address subnets runs the risk of outages for your users as changes are made.</span></span> 
  
## <a name="bandwidth-requirements"></a><span data-ttu-id="fb8ca-116">Requisitos de largura de banda</span><span class="sxs-lookup"><span data-stu-id="fb8ca-116">Bandwidth requirements</span></span>

<span data-ttu-id="fb8ca-117">Para saber mais sobre os requisitos de largura de banda, confira o artigo [Planejamento de rede e ajuste de desempenho do Office 365](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance).</span><span class="sxs-lookup"><span data-stu-id="fb8ca-117">For information on bandwidth requirements, see [Internet bandwidth planning](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance).</span></span>
  
## <a name="connecting-to-microsoft"></a><span data-ttu-id="fb8ca-118">Conexão com a Microsoft</span><span class="sxs-lookup"><span data-stu-id="fb8ca-118">Connecting to Microsoft</span></span>

<span data-ttu-id="fb8ca-119">Todas as conexões com a Microsoft são realizadas pela Internet pública ou por uma conexão expressa do Azure para o Azure e são protegidas por SSL, conforme apropriado.</span><span class="sxs-lookup"><span data-stu-id="fb8ca-119">All Connections to Microsoft are done over the public internet or over a private Azure ExpressRoute connection, and are secured by SSL as appropriate.</span></span> <span data-ttu-id="fb8ca-120">O Azure ExpressRoute permite a conexão direta com a rede global da Microsoft, ignorando a Internet.</span><span class="sxs-lookup"><span data-stu-id="fb8ca-120">Azure ExpressRoute allows connecting directly to the global Microsoft network, bypassing the internet.</span></span> <span data-ttu-id="fb8ca-121">Um parceiro de rede da Microsoft fornece a conectividade com a rede global da Microsoft.</span><span class="sxs-lookup"><span data-stu-id="fb8ca-121">A Microsoft networking partner provides the connectivity to the global Microsoft network.</span></span>
  
<span data-ttu-id="fb8ca-122">Para saber mais sobre o Azure ExpressRoute, confira [Azure ExpressRoute para Office 365.](https://aka.ms/expressrouteoffice365)</span><span class="sxs-lookup"><span data-stu-id="fb8ca-122">For more information about Azure ExpressRoute, see [Azure ExpressRoute for Office 365.](https://aka.ms/expressrouteoffice365)</span></span>
  
### <a name="wan-accelerators"></a><span data-ttu-id="fb8ca-123">Aceleradores da WAN</span><span class="sxs-lookup"><span data-stu-id="fb8ca-123">WAN accelerators</span></span>

<span data-ttu-id="fb8ca-p105">A Microsoft não fornece suporte para dispositivos de aceleração de WAN e cache com o Office 365. Se optar por usar um controlador de otimização de WAN para aumentar o desempenho em condições de alta latência ou baixa largura de banda, você deve desabilitá-lo enquanto soluciona problemas de solicitações de serviço com a Microsoft e solicitar suporte ao fornecedor do dispositivo. Para saber mais, confira o artigo [Usando dispositivos de aceleração de WAN e cache com o Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).</span><span class="sxs-lookup"><span data-stu-id="fb8ca-p105">Microsoft does not provide support for customer-owned WAN acceleration and caching devices with Office 365. If you decide to use a WAN optimization controller to improve performance under conditions of high latency or low bandwidth, you'll need to disable it while troubleshooting service requests with Microsoft, and work with your device vendor for device support. For more information, see [WAN Acceleration and caching devices with Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).</span></span>
  
## <a name="the-global-microsoft-network"></a><span data-ttu-id="fb8ca-127">A rede global de Microsoft</span><span class="sxs-lookup"><span data-stu-id="fb8ca-127">The global Microsoft network</span></span>

<span data-ttu-id="fb8ca-128">A infraestrutura de rede da Microsoft é composta por um amplo portfólio global de data centers, servidores, redes de distribuição de conteúdo, nós de computação de borda e redes de fibra ótica para fornecer distribuição global de serviços.</span><span class="sxs-lookup"><span data-stu-id="fb8ca-128">The Microsoft networking infrastructure is comprised of a large global portfolio of data centers, servers, content distribution networks, edge computing nodes, and fiber optic networks to provide global distribution of services.</span></span> <span data-ttu-id="fb8ca-129">Instrumentação e monitoramento de serviços sofisticados se integram aos níveis mais profundos com cada componente, oferecendo visibilidade no datacenter, backbone de rede, trocas de internet e muito mais para ajudar a localizar, diagnosticar e gerenciar a causa das interrupções que surgirem.</span><span class="sxs-lookup"><span data-stu-id="fb8ca-129">Sophisticated service instrumentation and monitoring integrates at the deepest levels with each component, giving visibility into the data center, network backbone, internet exchanges and beyond, to help spot, diagnose and manage the cause of disruptions that arise.</span></span> <span data-ttu-id="fb8ca-130">A rede é construída para manter a capacidade suficiente, mesmo para interrupções de rede em larga escala, sem degradação de desempenho.</span><span class="sxs-lookup"><span data-stu-id="fb8ca-130">The network is built to maintain sufficient capacity even for large scale network interruptions without degradation of performance.</span></span> <span data-ttu-id="fb8ca-131">Para obter mais informações, consulte [Microsoft Global Network](https://docs.microsoft.com/azure/networking/microsoft-global-network).</span><span class="sxs-lookup"><span data-stu-id="fb8ca-131">For more information, see [Microsoft Global Network](https://docs.microsoft.com/azure/networking/microsoft-global-network).</span></span> 
  
<span data-ttu-id="fb8ca-132">Para manter a confidencialidade e integridade dos dados do cliente, a Microsoft mantém as redes de serviços de consumidor separadas das redes Microsoft.</span><span class="sxs-lookup"><span data-stu-id="fb8ca-132">To maintain the confidentiality and integrity of customer data, Microsoft keeps consumer services networks separate from Microsoft networks.</span></span> <span data-ttu-id="fb8ca-133">Várias técnicas são usadas para controlar fluxos de informações, incluindo, mas não limitadas a:</span><span class="sxs-lookup"><span data-stu-id="fb8ca-133">Multiple techniques are used to control information flows, including but not limited to:</span></span>
  
- <span data-ttu-id="fb8ca-p108">Separação física. Os segmentos de rede são fisicamente separados por roteadores que são configurados para evitar padrões de comunicação específicos.</span><span class="sxs-lookup"><span data-stu-id="fb8ca-p108">Physical separation. Network segments are physically separated by routers that are configured to prevent specific communication patterns.</span></span>
    
- <span data-ttu-id="fb8ca-p109">Separação lógica. A tecnologia Virtual LAN (VLAN) é usada para separar ainda mais a comunicação.</span><span class="sxs-lookup"><span data-stu-id="fb8ca-p109">Logical separation. Virtual LAN (VLAN) technology is used to further separate communications.</span></span>
    
- <span data-ttu-id="fb8ca-138">Firewalls.</span><span class="sxs-lookup"><span data-stu-id="fb8ca-138">Firewalls.</span></span> <span data-ttu-id="fb8ca-139">Firewalls e outros pontos de imposição de segurança de rede são usados para limitar trocas de dados com sistemas expostos à Internet e para isolar sistemas de sistemas de back-end gerenciados pela Microsoft.</span><span class="sxs-lookup"><span data-stu-id="fb8ca-139">Firewalls and other network security enforcement points are used to limit data exchanges with systems that are exposed to the internet, and to isolate systems from back-end systems managed by Microsoft.</span></span> 
    
- <span data-ttu-id="fb8ca-140">Restrições de protocolo.</span><span class="sxs-lookup"><span data-stu-id="fb8ca-140">Protocol restrictions.</span></span>
    
<span data-ttu-id="fb8ca-141">Para saber mais, visite a [Central de Confiabilidade do Office 365](https://www.microsoft.com/trust-center).</span><span class="sxs-lookup"><span data-stu-id="fb8ca-141">For more information, see the [Office 365 Trust Center](https://www.microsoft.com/trust-center).</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="fb8ca-142">Disponibilidade de recursos</span><span class="sxs-lookup"><span data-stu-id="fb8ca-142">Feature availability</span></span>

<span data-ttu-id="fb8ca-143">Para exibir a disponibilidade de recursos nos planos, consulte [Descrição do serviço da plataforma do Office 365](office-365-platform-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="fb8ca-143">To view feature availability across plans, see [Office 365 platform service description](office-365-platform-service-description.md).</span></span>
  

