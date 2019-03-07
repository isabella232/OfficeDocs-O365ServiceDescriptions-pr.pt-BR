---
title: Instalação e Administração do Exchange Online
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-administration-and-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 80c07748-ac57-4b90-97dd-a2d1115009a6
description: Esta seção descreve os controles de administração e o suporte disponíveis para personalizar as configurações do Exchange Online e manter o ambiente do Exchange Online de uma organização em funcionamento, em execução e atualizado. Ela inclui informações sobre ferramentas de administração de autoatendimento e recursos disponíveis para as organizações; responsabilidades de administração e compromissos de desempenho da Microsoft; e atualizações de produtos e serviços.
ms.openlocfilehash: 909806b0bd62b989081f36a8588cd813b1ee1717
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/07/2019
ms.locfileid: "30467798"
---
# <a name="exchange-online-setup-and-administration"></a><span data-ttu-id="c2777-104">Instalação e Administração do Exchange Online</span><span class="sxs-lookup"><span data-stu-id="c2777-104">Exchange Online Setup and Administration</span></span>

<span data-ttu-id="c2777-105">Esta seção descreve os controles de administração e o suporte disponíveis para personalizar as configurações do Exchange Online e manter o ambiente do Exchange Online de uma organização em funcionamento, em execução e atualizado.</span><span class="sxs-lookup"><span data-stu-id="c2777-105">This section describes the administration controls and support that are available to customize Exchange Online settings and keep an organization's Exchange Online environment up, running, and current.</span></span> <span data-ttu-id="c2777-106">Ela inclui informações sobre ferramentas de administração de autoatendimento e recursos disponíveis para as organizações; responsabilidades de administração e compromissos de desempenho da Microsoft; e atualizações de produtos e serviços.</span><span class="sxs-lookup"><span data-stu-id="c2777-106">It includes information about self-service administration tools and capabilities available to organizations; Microsoft administration responsibilities and performance commitments; and service and product upgrades.</span></span>
  
## <a name="self-service-administration-tools"></a><span data-ttu-id="c2777-107">Ferramentas de administração de autoatendimento</span><span class="sxs-lookup"><span data-stu-id="c2777-107">Self-service administration tools</span></span>

<span data-ttu-id="c2777-p103">Embora a Microsoft controle diretamente todos os data centers do Exchange Online e seja responsável pelo desempenho geral do sistema, ela pode controlar apenas uma parte dos elementos combinados para proporcionar a experiência total dos usuários do Office 365. As próprias organizações são responsáveis pelas conexões de rede com os data centers, as LANs e as WANs dos clientes. Além disso, elas são responsáveis pelos dispositivos do usuário e sua configuração. Elas também são responsáveis por manter a licença necessária por usuário para qualquer recurso desejado, incluindo, mas sem limitação, a capacidade de gerenciar esses recursos, para quanto tempo o usuário precisar de acesso ao recurso.</span><span class="sxs-lookup"><span data-stu-id="c2777-p103">Although Microsoft directly controls all Exchange Online data centers and is responsible for overall system performance, it can control only a portion of the elements that combine to provide the total experience for Office 365 users. Organizations themselves are responsible for the network connections to the data centers, the customer's wide area network (WAN), and the customer's local area networks (LANs). Additionally, they are in charge of user devices and their configuration.  They are also responsible for maintaining the required licensing per user for any desired feature, including, but not limited to, the ability to manage these features, for as long as the user needs access to the feature.</span></span>
  
<span data-ttu-id="c2777-112">Por esse motivo, o Exchange Online oferece aos administradores de clientes as seguintes ferramentas, descritas abaixo, para gerenciar uma variedade de tarefas relacionadas a mensagens:</span><span class="sxs-lookup"><span data-stu-id="c2777-112">Exchange Online therefore provides customer administrators with the following tools, described below, to manage a variety of messaging-related tasks:</span></span>
  
- [<span data-ttu-id="c2777-113">Portal do Microsoft Office 365</span><span class="sxs-lookup"><span data-stu-id="c2777-113">Microsoft Office 365 portal</span></span>](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [<span data-ttu-id="c2777-114">Centro de administração do Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="c2777-114">Microsoft 365 admin center</span></span>](exchange-online-setup-and-administration.md#microsoft-office-365-admin-center)
    
- [<span data-ttu-id="c2777-115">Centro de administração do Exchange</span><span class="sxs-lookup"><span data-stu-id="c2777-115">Exchange admin center</span></span>](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [<span data-ttu-id="c2777-116">Windows PowerShell Remoto para o Exchange Online</span><span class="sxs-lookup"><span data-stu-id="c2777-116">Remote Windows PowerShell for Exchange Online</span></span>](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a><span data-ttu-id="c2777-117">Portal do Microsoft Office 365</span><span class="sxs-lookup"><span data-stu-id="c2777-117">Microsoft Office 365 portal</span></span>
<span data-ttu-id="c2777-118"><a name="BKMK_MicrosoftOnlineServicesPortal"> </a></span><span class="sxs-lookup"><span data-stu-id="c2777-118"></span></span>

<span data-ttu-id="c2777-119">O portal do Microsoft Office 365, em [https://portal.office.com](https://portal.office.com), é o site por meio do qual os administradores e os parceiros compram e gerenciam serviços do Office 365 e onde os usuários acessam e usam ferramentas de colaboração do Office 365.</span><span class="sxs-lookup"><span data-stu-id="c2777-119">The Microsoft Office 365 portal, at [https://portal.office.com](https://portal.office.com), is the website through which administrators and partners purchase and manage Office 365 services and where users access and use Office 365 collaborative tools.</span></span>
  
### <a name="microsoft-365-admin-center"></a><span data-ttu-id="c2777-120">Centro de administração do Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="c2777-120">Microsoft 365 admin center</span></span>
<span data-ttu-id="c2777-121"><a name="BKMK_Office365admincenterl"> </a></span><span class="sxs-lookup"><span data-stu-id="c2777-121"></span></span>

<span data-ttu-id="c2777-122">O centro de administração do Microsoft 365 é o portal da Web a partir do qual o administrador de serviço de cada empresa pode gerenciar contas de usuário e configurações para cada um dos serviços do Office 365 aos quais eles se inscrevem.</span><span class="sxs-lookup"><span data-stu-id="c2777-122">The Microsoft 365 admin center is the web portal from which each company's service administrator can manage user accounts and settings for each of the Office 365 services to which they subscribe.</span></span> <span data-ttu-id="c2777-123">No centro de administração do Microsoft 365, os administradores podem seguir links para o centro de administração do Exchange (Eat), onde podem gerenciar configurações específicas do Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="c2777-123">From within the Microsoft 365 admin center, administrators can follow links to the Exchange admin center (EAC), where they can manage settings specific to Exchange Online.</span></span> <span data-ttu-id="c2777-124">Para obter mais informações sobre como começar a usar o centro de administração do Microsoft 365, consulte o seguinte vídeo: [apresentando o Office 365 Enterprise](https://go.microsoft.com/fwlink/p/?LinkId=271806).</span><span class="sxs-lookup"><span data-stu-id="c2777-124">For more information about getting up and running using the Microsoft 365 admin center, see the following video: [Introducing Office 365 Enterprise](https://go.microsoft.com/fwlink/p/?LinkId=271806).</span></span>
  
### <a name="exchange-admin-center"></a><span data-ttu-id="c2777-125">Centro de administração do Exchange</span><span class="sxs-lookup"><span data-stu-id="c2777-125">Exchange admin center</span></span>
<span data-ttu-id="c2777-126"><a name="BKMK_ExchangeAdministrationCenter"> </a></span><span class="sxs-lookup"><span data-stu-id="c2777-126"></span></span>

<span data-ttu-id="c2777-p105">O Exchange Online fornece um console de gerenciamento unificado exclusivo que facilita o uso e é otimizado para o gerenciamento de implantações híbridas, no local ou online. O EAC (centro de administração do Exchange) é o local em que os administradores podem gerenciar configurações específicas do Exchange.</span><span class="sxs-lookup"><span data-stu-id="c2777-p105">Exchange Online provides a single unified management console that allows for ease of use and is optimized for management of on-premises, online, or hybrid deployments. The Exchange admin center (EAC) is where administrators can manage Exchange-specific settings.</span></span>
  
<span data-ttu-id="c2777-129">Para saber mais sobre como usar o EAC para gerenciar o Exchange Online, confira [Centro de administração do Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271807).</span><span class="sxs-lookup"><span data-stu-id="c2777-129">For more information about how to use the EAC to manage Exchange Online, see [Exchange admin center](https://go.microsoft.com/fwlink/p/?LinkId=271807).</span></span>
  
### <a name="remote-windows-powershell-for-exchange-online"></a><span data-ttu-id="c2777-130">Windows PowerShell Remoto para o Exchange Online</span><span class="sxs-lookup"><span data-stu-id="c2777-130">Remote Windows PowerShell for Exchange Online</span></span>
<span data-ttu-id="c2777-131"><a name="BKMK_RemoteWindowsPowerShell"> </a></span><span class="sxs-lookup"><span data-stu-id="c2777-131"></span></span>

<span data-ttu-id="c2777-p106">Usando o Windows PowerShell remoto, os administradores podem se conectar ao Exchange Online para executar tarefas de gerenciamento que não estão disponíveis ou não são práticas, usando o EAC. Elas incluem a capacidade de automatizar tarefas repetitivas, extrair dados de relatórios personalizados, personalizar políticas e conectar o Exchange Online à infraestrutura e aos processos existentes. Para saber mais, confira [Connect to Exchange Online Using Remote PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).</span><span class="sxs-lookup"><span data-stu-id="c2777-p106">Using remote Windows PowerShell, administrators can connect to Exchange Online to perform management tasks that are not available or practical using the EAC. These include the ability to automate repetitive tasks, extract data for custom reports, customize policies, and connect Exchange Online to existing infrastructure and processes. For more information, see [Connect to Exchange Online Using Remote PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).</span></span>
  
<span data-ttu-id="c2777-p107">O Exchange Online usa os mesmos cmdlets do Windows PowerShell que o Exchange Server 2013, com certos comandos e parâmetros indisponíveis porque esses recursos não se aplicam ao Exchange Online. Para ver uma lista de cmdlets para usar com o Exchange Online, confira [Cmdlets do Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span><span class="sxs-lookup"><span data-stu-id="c2777-p107">Exchange Online uses the same Windows PowerShell cmdlets as Exchange Server 2013, with certain commands and parameters unavailable because these features do not apply in Exchange Online. For a list of cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span></span>
  
<span data-ttu-id="c2777-p108">Os administradores não precisam instalar nenhuma ferramenta de gerenciamento ou migração do Exchange Server para usar o Windows PowerShell remoto. Entretanto, os computadores dos administradores precisam executar o Windows Management Framework 3.0, que contém o Windows PowerShell v3 e o WinRM 3.0; e o Windows .NET Framework 4.5. Esses componentes já estão instalados em computadores que executam Windows 8 ou Windows Server 2012. Os administrador podem baixar manualmente esses componentes para computadores que executam o Windows 7 ou o Windows Server 2008 R2.</span><span class="sxs-lookup"><span data-stu-id="c2777-p108">Administrators do not need to install any Exchange Server management or migration tools to use remote Windows PowerShell. However, administrators' computers must be running the Windows Management Framework 3.0, which contains Windows PowerShell v3 and WinRM 3.0; and Windows .NET Framework 4.5. These components are already installed on computers running Windows 8 or Windows Server 2012. Administrators can manually download these components for computers that are running Windows 7 or Windows Server 2008 R2.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="c2777-141">Para ajudar a impedir ataques de negação de serviço (DoS), existe um limite de três conexões abertas do Windows PowerShell para a sua organização do Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="c2777-141">To help prevent denial of service (DoS) attacks, you're limited to three open Windows PowerShell connections to your Exchange Online organization.</span></span> 
  
## <a name="self-service-capabilities-for-exchange-online"></a><span data-ttu-id="c2777-142">Recursos de autoatendimento para o Exchange Online</span><span class="sxs-lookup"><span data-stu-id="c2777-142">Self-service capabilities for Exchange Online</span></span>

<span data-ttu-id="c2777-p109">A seguir estão relacionados recursos importantes disponíveis para gerenciar o Exchange Online usando o EAC, o Windows PowerShell remoto e outras ferramentas. Várias outras configurações podem também ser controladas com essas ferramentas, como descrito no decorrer deste documento.</span><span class="sxs-lookup"><span data-stu-id="c2777-p109">Below are important capabilities that are available for managing Exchange Online by using the EAC, remote Windows PowerShell, and other tools. Many other settings can also be controlled with these tools, as described throughout this document.</span></span>
  
### <a name="mobile-device-security-policies-for-exchange-online"></a><span data-ttu-id="c2777-145">Políticas de segurança de dispositivos móveis para o Exchange Online</span><span class="sxs-lookup"><span data-stu-id="c2777-145">Mobile device security policies for Exchange Online</span></span>

<span data-ttu-id="c2777-p110">O Exchange Online dá suporte às mesmas políticas do ActiveSync para dispositivos móveis que o Exchange Server 2013. Os administradores podem impor e personalizar essas políticas de segurança para usuários e grupos específicos usando o EAC ou o Windows PowerShell remoto.</span><span class="sxs-lookup"><span data-stu-id="c2777-p110">Exchange Online supports the same ActiveSync policies for mobile devices as Exchange Server 2013. Administrators can enforce and customize these security policies for specific users and groups by using the EAC or remote Windows PowerShell.</span></span>
  
### <a name="message-tracking-for-exchange-online"></a><span data-ttu-id="c2777-148">Acompanhamento de mensagens para o Exchange Online</span><span class="sxs-lookup"><span data-stu-id="c2777-148">Message tracking for Exchange Online</span></span>

<span data-ttu-id="c2777-149">O acompanhamento de mensagens por meio do recurso Notificações de Entrega está descrito no seguinte tópico: [Recursos de Relatórios e Ferramentas de Solução de Problemas](reporting-features-and-troubleshooting-tools.md).</span><span class="sxs-lookup"><span data-stu-id="c2777-149">Message tracking via the Delivery Reports feature is described in the following topic: [Reporting Features and Troubleshooting Tools](reporting-features-and-troubleshooting-tools.md).</span></span>
  
### <a name="usage-reporting-for-exchange-online"></a><span data-ttu-id="c2777-150">Uso de relatórios para o Exchange Online</span><span class="sxs-lookup"><span data-stu-id="c2777-150">Usage reporting for Exchange Online</span></span>

<span data-ttu-id="c2777-p111">Os administradores podem usar o Windows PowerShell remoto para recuperar informações sobre como as pessoas em suas organizações utilizam o serviço Exchange Online. As informações disponíveis incluem:</span><span class="sxs-lookup"><span data-stu-id="c2777-p111">Administrators can use remote Windows PowerShell to retrieve information about how people in their organizations use the Exchange Online service. Available information includes:</span></span>
  
- <span data-ttu-id="c2777-153">Mostrar o tamanho de caixa de correio para cada usuário da organização.</span><span class="sxs-lookup"><span data-stu-id="c2777-153">Showing the mailbox size for each user in the organization.</span></span>
    
- <span data-ttu-id="c2777-154">Exibir permissões personalizadas definidas em caixas de correio, como acesso de representante.</span><span class="sxs-lookup"><span data-stu-id="c2777-154">Displaying custom permissions that are set on mailboxes, such as delegate access.</span></span>
    
- <span data-ttu-id="c2777-155">Extrair dados sobre o acesso de dispositivo móvel, como quais usuários estão se conectado por meio do Exchange ActiveSync, quais dispositivos estão usando e quando se conectaram pela última vez.</span><span class="sxs-lookup"><span data-stu-id="c2777-155">Extracting data about mobile device access, such as which users are connecting through Exchange ActiveSync, what devices they are using, and when they last connected.</span></span>
    
<span data-ttu-id="c2777-p112">Os cmdlets do Windows PowerShell remoto que começam com "get-" podem buscar dados do sistema Exchange Online. Os administradores podem exportar essas informações do Windows PowerShell no formato .csv para análise ou relatórios avançados.</span><span class="sxs-lookup"><span data-stu-id="c2777-p112">Remote Windows PowerShell cmdlets that start with "get-" can fetch data from the Exchange Online system. Administrators can export this information from Windows PowerShell in .csv format for advanced analysis or reporting.</span></span>
  
<span data-ttu-id="c2777-158">Para saber mais sobre os cmdlets do Windows PowerShell para uso com o Exchange Online, confira [Cmdlets do Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span><span class="sxs-lookup"><span data-stu-id="c2777-158">For more information about Windows PowerShell cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span></span>
  
### <a name="auditing-for-exchange-online"></a><span data-ttu-id="c2777-159">Auditoria para o Exchange Online</span><span class="sxs-lookup"><span data-stu-id="c2777-159">Auditing for Exchange Online</span></span>

<span data-ttu-id="c2777-160">O recurso de log de auditoria está descrito no tópico a seguir: [Recursos de Relatórios e Ferramentas de Solução de Problemas](reporting-features-and-troubleshooting-tools.md).</span><span class="sxs-lookup"><span data-stu-id="c2777-160">The audit logging feature is described in the following topic: [Reporting Features and Troubleshooting Tools](reporting-features-and-troubleshooting-tools.md).</span></span>
  
## <a name="service-and-product-upgrades-for-exchange-online"></a><span data-ttu-id="c2777-161">Atualizações de produtos e serviços para o Exchange Online</span><span class="sxs-lookup"><span data-stu-id="c2777-161">Service and product upgrades for Exchange Online</span></span>

<span data-ttu-id="c2777-p113">Os clientes do Exchange Online se beneficiam com atualizações periódicas para a tecnologia Exchange mais recente, incluindo novas versões do Exchange Server. Essas atualizações são disponibilizadas sem nenhum custo adicional e garantem que os clientes estejam sempre usando o software Exchange mais recente.</span><span class="sxs-lookup"><span data-stu-id="c2777-p113">Exchange Online customers benefit from periodic upgrades to the latest Exchange technology, including new releases of Exchange Server. These upgrades are made available at no additional charge, and ensure that customers are always using the latest Exchange software.</span></span>
  
<span data-ttu-id="c2777-164">Após uma versão principal do Exchange ser lançada pela Microsoft, os clientes têm até 12 meses para atualizar seu serviço para a nova versão.</span><span class="sxs-lookup"><span data-stu-id="c2777-164">After a major version of Exchange is released by Microsoft, customers have up to 12 months to upgrade their service to the new release.</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="c2777-165">Disponibilidade do recurso</span><span class="sxs-lookup"><span data-stu-id="c2777-165">Feature Availability</span></span>

<span data-ttu-id="c2777-166">Para exibir a disponibilidade de recursos nos planos do Office 365 nas opções autônomas e nas soluções locais, consulte [Descrição de Serviço do Exchange Online](exchange-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="c2777-166">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

