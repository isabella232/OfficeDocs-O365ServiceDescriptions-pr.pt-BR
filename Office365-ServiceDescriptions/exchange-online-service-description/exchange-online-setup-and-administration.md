---
title: Instalação e administração do Exchange Online
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-administration-and-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 80c07748-ac57-4b90-97dd-a2d1115009a6
description: Este artigo descreve os controles de administração e o suporte disponíveis para personalizar as configurações do Exchange Online e manter o ambiente do Exchange Online de uma organização em funcionamento, em execução e atualizado. Ela inclui informações sobre ferramentas de administração de autoatendimento e recursos disponíveis para as organizações; responsabilidades de administração e compromissos de desempenho da Microsoft; e atualizações de produtos e serviços.
ms.openlocfilehash: 19ec50b3f502ee111de05e1a115d17f16fec3569
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132996"
---
# <a name="exchange-online-setup-and-administration"></a>Instalação e administração do Exchange Online

Este artigo descreve os controles de administração e o suporte disponíveis para personalizar as configurações do Exchange Online e manter o ambiente do Exchange Online de uma organização em funcionamento, em execução e atualizado. Ela inclui informações sobre ferramentas de administração de autoatendimento e recursos disponíveis para as organizações; responsabilidades de administração e compromissos de desempenho da Microsoft; e atualizações de produtos e serviços.
  
## <a name="self-service-administration-tools"></a>Ferramentas de administração de autoatendimento

Embora a Microsoft controle diretamente todos os data centers do Exchange Online e seja responsável pelo desempenho geral do sistema, ele pode controlar apenas uma parte dos elementos que são combinados para fornecer a experiência total para os usuários. As próprias organizações são responsáveis pelas conexões de rede com os data centers, as LANs e as WANs dos clientes. Além disso, elas são responsáveis pelos dispositivos do usuário e sua configuração.Elas também são responsáveis por manter a licença necessária por usuário para qualquer recurso desejado, incluindo, mas sem limitação, a capacidade de gerenciar esses recursos, para quanto tempo o usuário precisar de acesso ao recurso.
  
Por esse motivo, o Exchange Online oferece aos administradores de clientes as seguintes ferramentas, descritas abaixo, para gerenciar uma variedade de tarefas relacionadas a mensagens:
  
- [Portal do Microsoft Office 365](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [Centro de administração do Microsoft 365](#microsoft-365-admin-center)
    
- [Centro de administração do Exchange](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [Windows PowerShell Remoto para o Exchange Online](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a>Portal do Microsoft Office 365

O portal do Microsoft Office 365, em [https://portal.office.com](https://portal.office.com), é o site por meio do qual os administradores e os parceiros compram e gerenciam serviços do Office 365 e onde os usuários acessam e usam ferramentas de colaboração do Office 365.
  
### <a name="microsoft-365-admin-center"></a>Centro de administração do Microsoft 365

O centro de administração do Microsoft 365 é o portal da Web a partir do qual o administrador de serviço de cada empresa pode gerenciar contas de usuário e configurações para cada um dos serviços da Microsoft que eles assinam. No centro de administração do Microsoft 365, os administradores podem seguir links para o centro de administração do Exchange (Eat), onde podem gerenciar configurações específicas do Exchange Online. Para obter mais informações sobre como começar a usar o centro de administração do Microsoft 365, consulte o seguinte vídeo: [apresentando o Office 365 Enterprise](https://go.microsoft.com/fwlink/p/?LinkId=271806).
  
### <a name="exchange-admin-center"></a>Centro de administração do Exchange

Exchange Online provides a single unified management console that allows for ease of use and is optimized for management of on-premises, online, or hybrid deployments. The Exchange admin center (EAC) is where administrators can manage Exchange-specific settings.
  
Para saber mais sobre como usar o EAC para gerenciar o Exchange Online, confira [Centro de administração do Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271807).
  
### <a name="remote-windows-powershell-for-exchange-online"></a>Windows PowerShell Remoto para o Exchange Online

Using remote Windows PowerShell, administrators can connect to Exchange Online to perform management tasks that are not available or practical using the EAC. These include the ability to automate repetitive tasks, extract data for custom reports, customize policies, and connect Exchange Online to existing infrastructure and processes. For more information, see [Connect to Exchange Online Using Remote PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).
  
Exchange Online uses the same Windows PowerShell cmdlets as Exchange Server 2013, with certain commands and parameters unavailable because these features do not apply in Exchange Online. For a list of cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).
  
Administrators do not need to install any Exchange Server management or migration tools to use remote Windows PowerShell. However, administrators' computers must be running the Windows Management Framework 3.0, which contains Windows PowerShell v3 and WinRM 3.0; and Windows .NET Framework 4.5. These components are already installed on computers running Windows 8 or Windows Server 2012. Administrators can manually download these components for computers that are running Windows 7 or Windows Server 2008 R2.
  
> [!IMPORTANT]
> Para ajudar a impedir ataques de negação de serviço (DoS), existe um limite de três conexões abertas do Windows PowerShell para a sua organização do Exchange Online. 
  
## <a name="self-service-capabilities-for-exchange-online"></a>Recursos de autoatendimento para o Exchange Online

Below are important capabilities that are available for managing Exchange Online by using the EAC, remote Windows PowerShell, and other tools. Many other settings can also be controlled with these tools, as described throughout this document.
  
### <a name="mobile-device-security-policies-for-exchange-online"></a>Políticas de segurança de dispositivos móveis para o Exchange Online

Exchange Online supports the same ActiveSync policies for mobile devices as Exchange Server 2013. Administrators can enforce and customize these security policies for specific users and groups by using the EAC or remote Windows PowerShell.
  
### <a name="message-tracking-for-exchange-online"></a>Acompanhamento de mensagens para o Exchange Online

O controle de mensagens por meio do recurso de relatórios de entrega é descrito no tópico a seguir: [recursos de relatórios e ferramentas de solução de problemas](reporting-features-and-troubleshooting-tools.md).
  
### <a name="usage-reporting-for-exchange-online"></a>Uso de relatórios para o Exchange Online

Administrators can use remote Windows PowerShell to retrieve information about how people in their organizations use the Exchange Online service. Available information includes:
  
- Mostrar o tamanho de caixa de correio para cada usuário da organização.
    
- Exibir permissões personalizadas definidas em caixas de correio, como acesso de representante.
    
- Extrair dados sobre o acesso de dispositivo móvel, como quais usuários estão se conectado por meio do Exchange ActiveSync, quais dispositivos estão usando e quando se conectaram pela última vez.
    
Remote Windows PowerShell cmdlets that start with "get-" can fetch data from the Exchange Online system. Administrators can export this information from Windows PowerShell in .csv format for advanced analysis or reporting.
  
Para saber mais sobre os cmdlets do Windows PowerShell para uso com o Exchange Online, confira [Cmdlets do Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271808).
  
### <a name="auditing-for-exchange-online"></a>Auditoria para o Exchange Online

O recurso de log de auditoria está descrito no tópico a seguir: [recursos de relatório e ferramentas de solução de problemas](reporting-features-and-troubleshooting-tools.md).
  
## <a name="service-and-product-upgrades-for-exchange-online"></a>Atualizações de produtos e serviços para o Exchange Online

Exchange Online customers benefit from periodic upgrades to the latest Exchange technology, including new releases of Exchange Server. These upgrades are made available at no additional charge, and ensure that customers are always using the latest Exchange software.
  
Após uma versão principal do Exchange ser lançada pela Microsoft, os clientes têm até 12 meses para atualizar seu serviço para a nova versão.
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos nos planos, nas opções autônomas e nas soluções locais, consulte [Descrição do serviço do Exchange Online](exchange-online-service-description.md).
  