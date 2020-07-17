---
title: Recursos do cliente no arquivamento do Exchange Online
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- clients-and-devices-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c8d5f97a-607f-4949-a4f7-0b9e3b246851
description: O arquivamento do Microsoft Exchange Online permite que os usuários se conectem às caixas de correio de arquivo morto de vários dispositivos e plataformas. Toda a conectividade de rede para o arquivamento do usuário ocorre pela Internet, e as conexões de rede virtual privada (VPN) não são obrigatórias. As organizações podem publicar um servidor de Acesso para Cliente para permitir que os usuários acessem sua caixa de correio primária usando o Outlook em Qualquer Lugar, sem requerer uma conexão VPN. Se o acesso VPN for requerido para acessar a caixa de correio primária do usuário localizada em um servidor local, esse requisito não mudará.
ms.openlocfilehash: b460938b4ce9e0aeb2c0eb4ab99fe7f3fa8a8ea4
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132055"
---
# <a name="client-features-in-exchange-online-archiving"></a>Recursos do cliente no arquivamento do Exchange Online

O arquivamento do Microsoft Exchange Online permite que os usuários se conectem às caixas de correio de arquivo morto de vários dispositivos e plataformas. Toda a conectividade de rede para o arquivamento do usuário ocorre pela Internet, e as conexões de rede virtual privada (VPN) não são obrigatórias. As organizações podem publicar um servidor de Acesso para Cliente para permitir que os usuários acessem sua caixa de correio primária usando o Outlook em Qualquer Lugar, sem requerer uma conexão VPN. Se o acesso VPN for requerido para acessar a caixa de correio primária do usuário localizada em um servidor local, esse requisito não mudará.
  
> [!IMPORTANT]
> A Microsoft reserva-se o direito de bloquear ou acelerar as conexões de qualquer software do cliente que impacte negativamente na integridade do serviço do Arquivamento do Exchange Online.
  
## <a name="microsoft-outlook"></a>Microsoft Outlook

O Microsoft Outlook é um sofisticado programa de email que inclui suporte ao calendário, contatos e tarefas. O Arquivamento do Exchange Online dá suporte para o Outlook 2013, o Outlook 2010 e o Outlook 2007. Os principais recursos incluem:
  
- **Outlook em qualquer lugar** O Outlook em qualquer lugar permite que os usuários do Outlook se conectem ao Exchange Server e ao arquivamento do Exchange Online pela Internet sem a necessidade de uma conexão VPN. A comunicação entre o Outlook e o Arquivamento do Exchange Online ocorre via túnel com segurança SSL, usando o componente de rede Windows RPC-over-HTTP.    
- **Descoberta automática** O serviço da Descoberta automática do Exchange configura automaticamente o Outlook para trabalhar com o Arquivamento do Exchange Online. A descoberta automática permite que os usuários do Outlook recebam suas configurações de perfil necessárias diretamente do Exchange na primeira vez (e em intervalos fixos depois) que eles entrem com seu endereço de email e senha. 

O Outlook 2010 e posterior e o Outlook na Web fornecem aos usuários todos os recursos do arquivo morto, bem como os recursos relacionados, como políticas de retenção e arquivamento.
  
O Outlook 2007 oferece suporte básico ao arquivamento, mas nem todos os recursos de arquivamento e conformidade estão disponíveis no Outlook 2007. Por exemplo, com o Outlook 2007, os usuários não podem aplicar políticas de retenção ou de arquivamento aos itens em suas caixas de correio. Eles devem usar as políticas provisionadas pelo administrador. Os usuários do Outlook 2007 devem ter a Atualização Cumulativa do Office 2007 de fevereiro de 2011 para acessarem o arquivamento.
  
> [!NOTE]
> O Outlook não é fornecido com o Arquivamento do Exchange Online. O Microsoft 365 Apps for Enterprise (que inclui o Microsoft Outlook) está incluído em alguns planos e pode ser adquirido como uma assinatura separada. Para obter mais informações, consulte [Microsoft 365 Plan Options](../office-365-platform-service-description/office-365-plan-options.md). Para obter mais informações sobre os aplicativos do Microsoft 365 para empresas, consulte a [Descrição do serviço aplicativos do Office](../office-applications-service-description/office-applications-service-description.md). 
  
### <a name="clients-supported-by-exchange-online-archiving"></a>Clientes suportados pelo Arquivamento do Exchange Online

A tabela a seguir lista os clientes suportados pelo Arquivamento do Exchange Online:
  
|**Cliente**|**Suporte EOA**|
|:-----|:-----|
|Outlook 2010 e posterior  <br/> |Oferece suporte para os recursos mais recentes no Arquivamento do Exchange Online.<sup>1</sup> <br/> |
|Outlook 2007  <br/> |Suportado para usar com o Arquivamento do Exchange Online.<sup>1,2</sup> <br/> |
|Outlook 2003  <br/> |Incompatível  <br/> |
|Outlook para Mac 2011  <br/> |Incompatível  <br/> |
|Outlook para Mac  <br/> |Com suporte para uso com o arquivamento do Exchange Online. <sup>3</sup> <br/> |
|Microsoft Office Entourage 2008 Web Services Edition  <br/> |Incompatível  <br/> |
|IMAP e POP  <br/> |Sem suporte  <br/> |
|Exchange ActiveSync (dispositivos móveis)  <br/> |Sem suporte  <br/> |
   
> [!NOTE]
> <sup>1</sup> Não há suporte para o Outlook incluído com o Microsoft Office Standard. Para saber mais, confira [Requisitos de licença para políticas de retenção e arquivamento pessoal](https://support.office.com/article/Outlook-license-requirements-for-Exchange-features-46B6B7C5-C3CA-43E5-8424-1E2807917C99). <br/> 
<sup>2</sup> Requer atualização para ativar o suporte ao arquivamento. Os usuários do Outlook 2007 não podem exibir ou aplicar as políticas de retenção ou de arquivamento nos itens em suas caixas de correio de arquivamento; eles devem usar as políticas fornecidas pelo administrador. E mais, os usuários do Outlook 2007 não podem pesquisar a caixa de correio local e o arquivamento ao mesmo tempo. <br/> 
<sup>3</sup> você não pode usar o Outlook 2016 para Mac ou o Outlook para Mac para mover ou copiar pastas, itens de calendário, contatos, tarefas ou anotações para o arquivo morto, ou exibi-las na caixa de correio de arquivo morto, se os itens foram movidos anteriormente usando qualquer outra versão do Outlook (como o Outlook 2016 para Windows). Para obter mais informações, consulte [usar seu arquivo morto online com o Outlook 2016 para Mac](https://support.office.com/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238). 

## <a name="outlook-on-the-web"></a>Outlook na Web

O Outlook na Web App é uma versão baseada na Web do programa de email do Outlook usado com o Exchange Online. Sempre que os usuários estão conectados à Internet &mdash; em casa, no escritório ou em trânsito, &mdash; eles podem acessar seus emails por meio do Outlook na Web.
  
Os usuários podem acessar o arquivo usando a entrada no Outlook na Web local (usando a mesma URL). O arquivo morto aparece junto com a caixa de correio principal no Outlook na Web. Não há uma maneira explícita de acessar o arquivo morto diretamente do Outlook na Web.
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos nos planos, nas opções autônomas e nas soluções locais, consulte [Descrição do serviço de arquivamento do Exchange Online](exchange-online-archiving-service-description.md).