---
title: Recursos do cliente no arquivamento do Exchange Online
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- clients-and-devices-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c8d5f97a-607f-4949-a4f7-0b9e3b246851
description: O arquivamento do Microsoft Exchange Online permite que os usuários se conectem às caixas de correio de arquivo morto de vários dispositivos e plataformas. Toda a conectividade da rede para o arquivamento do usuário ocorre na Internet e as conexões VPN (rede privada virtual) não são requeridas. As organizações podem publicar um servidor de Acesso para Cliente para permitir que os usuários acessem sua caixa de correio primária usando o Outlook em Qualquer Lugar, sem requerer uma conexão VPN. Se o acesso VPN for requerido para acessar a caixa de correio primária do usuário localizada em um servidor local, esse requisito não mudará.
ms.openlocfilehash: b4f35a2bdc4e0c9f4ae54ec7be4997c9d946e0d4
ms.sourcegitcommit: af6f6ee0a74831a5af784612c7a4316658a53e28
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/18/2019
ms.locfileid: "35018293"
---
# <a name="client-features-in-exchange-online-archiving"></a>Recursos do cliente no arquivamento do Exchange Online

O arquivamento do Microsoft Exchange Online permite que os usuários se conectem às caixas de correio de arquivo morto de vários dispositivos e plataformas. Toda a conectividade da rede para o arquivamento do usuário ocorre na Internet e as conexões VPN (rede privada virtual) não são requeridas. As organizações podem publicar um servidor de Acesso para Cliente para permitir que os usuários acessem sua caixa de correio primária usando o Outlook em Qualquer Lugar, sem requerer uma conexão VPN. Se o acesso VPN for requerido para acessar a caixa de correio primária do usuário localizada em um servidor local, esse requisito não mudará.
  
> [!IMPORTANT]
> A Microsoft reserva-se o direito de bloquear ou acelerar as conexões de qualquer software do cliente que impacte negativamente na integridade do serviço do Arquivamento do Exchange Online. 
  
## <a name="microsoft-outlook"></a>Microsoft Outlook

O Microsoft Outlook é um sofisticado programa de email que inclui suporte ao calendário, contatos e tarefas. O Arquivamento do Exchange Online dá suporte para o Outlook 2013, o Outlook 2010 e o Outlook 2007. Os principais recursos incluem:
  
- **Outlook em Qualquer Lugar** O Outlook em Qualquer Lugar permite que os usuários do Outlook conectem o Exchange Server e o Arquivamento do Exchange Online na Internet sem precisar de uma conexão VPN. A comunicação entre o Outlook e o Arquivamento do Exchange Online ocorre via túnel com segurança SSL, usando o componente de rede Windows RPC-over-HTTP.    
- **Descoberta automática** O serviço da Descoberta automática do Exchange configura automaticamente o Outlook para trabalhar com o Arquivamento do Exchange Online. A Descoberta automática permite que os usuários do Outlook recebam diretamente suas configurações de perfil requeridas do Exchange na primeira vez (e em intervalos fixos depois) que usam seu endereço de e-mail e senha. 
    
O Outlook 2010, e posterior, e o Outlook Web App oferecem aos usuários todos os recursos do arquivamento, assim como os recursos relacionados, como políticas de retenção e de arquivamento.
  
O Outlook 2007 oferece suporte básico ao arquivamento, mas nem todos os recursos de arquivamento e conformidade estão disponíveis no Outlook 2007. Por exemplo, com o Outlook 2007, os usuários não podem aplicar políticas de retenção ou de arquivamento aos itens em suas caixas de correio. Eles devem usar as políticas provisionadas pelo administrador. Os usuários do Outlook 2007 devem ter a Atualização Cumulativa do Office 2007 de fevereiro de 2011 para acessarem o arquivamento.
  
> [!NOTE]
> O Outlook não é fornecido com o Arquivamento do Exchange Online. O Microsoft Office 365 ProPlus (que inclui o Microsoft Outlook) foi incluído em alguns dos planos do Office 365 e pode ser adquirido como uma assinatura separada. Para mais informações, consulte [Opções de planos do Office 365](../office-365-platform-service-description/office-365-plan-options.md). Para mais informações sobre o Office 365 ProPlus, consulte [Descrição de serviços dos aplicativos do Office](../office-applications-service-description/office-applications-service-description.md). 
  
### <a name="clients-supported-by-exchange-online-archiving"></a>Clientes suportados pelo Arquivamento do Exchange Online

A tabela a seguir lista os clientes suportados pelo Arquivamento do Exchange Online:
  
|**Cliente**|**Suporte EOA**|
|:-----|:-----|
|Outlook 2010 e posterior  <br/> |Oferece suporte para os recursos mais recentes no Arquivamento do Exchange Online.<sup>1</sup> <br/> |
|Outlook 2007  <br/> |Suportado para usar com o Arquivamento do Exchange Online.<sup>1,2</sup> <br/> |
|Outlook 2003  <br/> |Sem suporte  <br/> |
|Outlook para Mac 2011  <br/> |Sem suporte  <br/> |
|Outlook para Mac  <br/> |Com suporte para uso com o arquivamento do Exchange Online. <sup>3</sup> <br/> |
|Microsoft Office Entourage 2008 Web Services Edition  <br/> |Sem suporte  <br/> |
|IMAP e POP  <br/> |Sem suporte  <br/> |
|Exchange ActiveSync (dispositivos móveis)  <br/> |Sem suporte  <br/> |
   
> [!NOTE]
> <sup>1</sup> Não há suporte para o Outlook incluído com o Microsoft Office Standard. Para saber mais, confira [Requisitos de licença para políticas de retenção e arquivamento pessoal](https://support.office.com/article/Outlook-license-requirements-for-Exchange-features-46B6B7C5-C3CA-43E5-8424-1E2807917C99). <br/> 
<sup>2</sup> Requer atualização para ativar o suporte ao arquivamento. Os usuários do Outlook 2007 não podem exibir ou aplicar as políticas de retenção ou de arquivamento nos itens em suas caixas de correio de arquivamento; eles devem usar as políticas fornecidas pelo administrador. E mais, os usuários do Outlook 2007 não podem pesquisar a caixa de correio local e o arquivamento ao mesmo tempo. <br/> 
<sup>3</sup> você não pode usar o Outlook 2016 para Mac ou o Outlook para Mac para mover ou copiar pastas, itens de calendário, contatos, tarefas ou anotações para o arquivo morto, ou exibi-las na caixa de correio de arquivo morto, se os itens foram movidos anteriormente usando qualquer outra versão do Outlook (como Outlook 2016 para Windows). Para obter mais informações, consulte [usar seu arquivo morto online com o Outlook 2016 para Mac](https://support.office.com/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238). 

## <a name="outlook-web-app"></a>Outlook Web App

O Outlook Web App é uma versão baseada na Web do programa de email Outlook usada com o Exchange Online. Onde quer que os usuários estejam conectados à Internet—em casa, no escritório ou em trânsito—eles poderão acessar seu email com o Outlook Web App.
  
Os usuários podem acessar seu arquivamento se conectando ao Outlook Web App local (usando a mesma URL). O arquivamento aparecerá ao lado de sua caixa de correio principal no Outlook Web App. Não há nenhuma maneira explícita de acessar o arquivamento diretamente do Outlook Web App.
  
## <a name="feature-availability"></a>Disponibilidade do recurso

Para exibir a disponibilidade de recursos nos planos do Office 365 nas opções autônomas e nas soluções locais, consulte [Descrição do Serviço de Arquivamento do Exchange Online](exchange-online-archiving-service-description.md).