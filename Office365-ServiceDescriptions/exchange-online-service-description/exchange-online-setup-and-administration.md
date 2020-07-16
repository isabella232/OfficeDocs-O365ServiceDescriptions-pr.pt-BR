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

O Exchange Online fornece um console de gerenciamento unificado exclusivo que facilita o uso e é otimizado para o gerenciamento de implantações híbridas, no local ou online. O EAC (centro de administração do Exchange) é o local em que os administradores podem gerenciar configurações específicas do Exchange.
  
Para saber mais sobre como usar o EAC para gerenciar o Exchange Online, confira [Centro de administração do Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271807).
  
### <a name="remote-windows-powershell-for-exchange-online"></a>Windows PowerShell Remoto para o Exchange Online

Usando o Windows PowerShell remoto, os administradores podem se conectar ao Exchange Online para executar tarefas de gerenciamento que não estão disponíveis ou não são práticas, usando o EAC. Elas incluem a capacidade de automatizar tarefas repetitivas, extrair dados de relatórios personalizados, personalizar políticas e conectar o Exchange Online à infraestrutura e aos processos existentes. Para saber mais, confira [Connect to Exchange Online Using Remote PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).
  
O Exchange Online usa os mesmos cmdlets do Windows PowerShell que o Exchange Server 2013, com certos comandos e parâmetros indisponíveis porque esses recursos não se aplicam ao Exchange Online. Para ver uma lista de cmdlets para usar com o Exchange Online, confira [Cmdlets do Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271808).
  
Os administradores não precisam instalar nenhuma ferramenta de gerenciamento ou migração do Exchange Server para usar o Windows PowerShell remoto. Entretanto, os computadores dos administradores precisam executar o Windows Management Framework 3.0, que contém o Windows PowerShell v3 e o WinRM 3.0; e o Windows .NET Framework 4.5. Esses componentes já estão instalados em computadores que executam Windows 8 ou Windows Server 2012. Os administrador podem baixar manualmente esses componentes para computadores que executam o Windows 7 ou o Windows Server 2008 R2.
  
> [!IMPORTANT]
> Para ajudar a impedir ataques de negação de serviço (DoS), existe um limite de três conexões abertas do Windows PowerShell para a sua organização do Exchange Online. 
  
## <a name="self-service-capabilities-for-exchange-online"></a>Recursos de autoatendimento para o Exchange Online

A seguir estão relacionados recursos importantes disponíveis para gerenciar o Exchange Online usando o EAC, o Windows PowerShell remoto e outras ferramentas. Várias outras configurações podem também ser controladas com essas ferramentas, como descrito no decorrer deste documento.
  
### <a name="mobile-device-security-policies-for-exchange-online"></a>Políticas de segurança de dispositivos móveis para o Exchange Online

O Exchange Online dá suporte às mesmas políticas do ActiveSync para dispositivos móveis que o Exchange Server 2013. Os administradores podem impor e personalizar essas políticas de segurança para usuários e grupos específicos usando o EAC ou o Windows PowerShell remoto.
  
### <a name="message-tracking-for-exchange-online"></a>Acompanhamento de mensagens para o Exchange Online

O controle de mensagens por meio do recurso de relatórios de entrega é descrito no tópico a seguir: [recursos de relatórios e ferramentas de solução de problemas](reporting-features-and-troubleshooting-tools.md).
  
### <a name="usage-reporting-for-exchange-online"></a>Uso de relatórios para o Exchange Online

Os administradores podem usar o Windows PowerShell remoto para recuperar informações sobre como as pessoas em suas organizações utilizam o serviço Exchange Online. As informações disponíveis incluem:
  
- Mostrar o tamanho de caixa de correio para cada usuário da organização.
    
- Exibir permissões personalizadas definidas em caixas de correio, como acesso de representante.
    
- Extrair dados sobre o acesso de dispositivo móvel, como quais usuários estão se conectado por meio do Exchange ActiveSync, quais dispositivos estão usando e quando se conectaram pela última vez.
    
Os cmdlets do Windows PowerShell remoto que começam com "get-" podem buscar dados do sistema Exchange Online. Os administradores podem exportar essas informações do Windows PowerShell no formato .csv para análise ou relatórios avançados.
  
Para saber mais sobre os cmdlets do Windows PowerShell para uso com o Exchange Online, confira [Cmdlets do Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271808).
  
### <a name="auditing-for-exchange-online"></a>Auditoria para o Exchange Online

O recurso de log de auditoria está descrito no tópico a seguir: [recursos de relatório e ferramentas de solução de problemas](reporting-features-and-troubleshooting-tools.md).
  
## <a name="service-and-product-upgrades-for-exchange-online"></a>Atualizações de produtos e serviços para o Exchange Online

Os clientes do Exchange Online se beneficiam com atualizações periódicas para a tecnologia Exchange mais recente, incluindo novas versões do Exchange Server. Essas atualizações são disponibilizadas sem nenhum custo adicional e garantem que os clientes estejam sempre usando o software Exchange mais recente.
  
Após uma versão principal do Exchange ser lançada pela Microsoft, os clientes têm até 12 meses para atualizar seu serviço para a nova versão.
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos nos planos, nas opções autônomas e nas soluções locais, consulte [Descrição do serviço do Exchange Online](exchange-online-service-description.md).
  