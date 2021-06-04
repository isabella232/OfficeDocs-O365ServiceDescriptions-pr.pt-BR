---
title: Recursos do cliente em Arquivamento do Exchange Online
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
description: Leia este artigo para saber mais sobre os recursos do cliente disponíveis Microsoft Exchange Online Arquivamento.
ms.openlocfilehash: 54f066562b08eeeed90b8c9b465c4740bcc3f0df
ms.sourcegitcommit: e342174df76128430dfc8c971716da5c4b2942ac
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/28/2020
ms.locfileid: "48293633"
---
# <a name="client-features-in-exchange-online-archiving"></a>Recursos do cliente em Arquivamento do Exchange Online

Microsoft Exchange Online O arquivamento permite que os usuários se conectem às suas caixas de correio de arquivo morto de vários dispositivos e plataformas. Toda a conectividade de rede com o arquivo morto do usuário ocorre pela Internet e as conexões vpn (rede virtual privada) não são necessárias. As organizações podem publicar um servidor de Acesso para Cliente para permitir que os usuários acessem sua caixa de correio primária usando o Outlook em Qualquer Lugar, sem requerer uma conexão VPN. Se o acesso VPN for requerido para acessar a caixa de correio primária do usuário localizada em um servidor local, esse requisito não mudará.
  
> [!IMPORTANT]
> A Microsoft reserva-se o direito de bloquear ou acelerar as conexões de qualquer software do cliente que impacte negativamente na integridade do serviço do Arquivamento do Exchange Online.
  
## <a name="microsoft-outlook"></a>Microsoft Outlook

O Microsoft Outlook é um sofisticado programa de email que inclui suporte ao calendário, contatos e tarefas. O Arquivamento do Exchange Online dá suporte para o Outlook 2013, o Outlook 2010 e o Outlook 2007. Os principais recursos incluem:
  
- **Outlook Em Qualquer** Lugar - Outlook em Qualquer Lugar permite que Outlook usuários se conectem ao Exchange Server e Arquivamento do Exchange Online pela Internet sem a necessidade de uma conexão VPN. A comunicação entre o Outlook e o Arquivamento do Exchange Online ocorre via túnel com segurança SSL, usando o componente de rede Windows RPC-over-HTTP.    
- **Descoberta Automática** - O serviço Exchange Descoberta Automática configura automaticamente Outlook para trabalhar com Arquivamento do Exchange Online. A Descoberta Automática permite que Outlook os usuários recebam suas configurações de perfil necessárias diretamente do Exchange da primeira vez (e em intervalos fixos posteriormente) que eles entrarão com seu endereço de email e senha. 

Outlook 2010 e posteriores e Outlook na Web fornecem aos usuários os recursos completos do arquivo morto, bem como recursos relacionados, como políticas de retenção e arquivamento.
  
O Outlook 2007 oferece suporte básico ao arquivamento, mas nem todos os recursos de arquivamento e conformidade estão disponíveis no Outlook 2007. Por exemplo, com o Outlook 2007, os usuários não podem aplicar políticas de retenção ou de arquivamento aos itens em suas caixas de correio. Eles devem usar as políticas provisionadas pelo administrador. Os usuários do Outlook 2007 devem ter a Atualização Cumulativa do Office 2007 de fevereiro de 2011 para acessarem o arquivamento.
  
> [!NOTE]
> O Outlook não é fornecido com o Arquivamento do Exchange Online. Microsoft 365 Apps para Grandes Empresas (que inclui o Microsoft Outlook) está incluído em alguns planos e pode ser comprado como uma assinatura separada. Para obter mais informações, [consulte Microsoft 365 opções de plano](../office-365-platform-service-description/office-365-plan-options.md). Para obter mais informações sobre Microsoft 365 Apps para Grandes Empresas, consulte a [descrição do serviço Office aplicativos .](../office-applications-service-description/office-applications-service-description.md) 
  
### <a name="clients-supported-by-exchange-online-archiving"></a>Clientes suportados pelo Arquivamento do Exchange Online

A tabela a seguir lista os clientes suportados pelo Arquivamento do Exchange Online:<br><br>
  
| Cliente | Suporte ao EOA |
|:-----|:-----|
|Outlook 2013 e posterior  <br/> |Oferece suporte para os recursos mais recentes no Arquivamento do Exchange Online.<sup>1</sup> <br/> |
|Outlook 2010  <br/> |Oferece suporte aos recursos mais recentes Arquivamento do Exchange Online somente até 13 de outubro de 2020|
|Outlook 2007  <br/> |Sem suporte |
|Outlook 2003  <br/> |Sem suporte  <br/> |
|Outlook para Mac 2011  <br/> |Sem suporte  <br/> |
|Outlook para Mac  <br/> |Suportado para uso com Arquivamento do Exchange Online. <sup>3</sup> <br/> |
|Microsoft Office Entourage 2008 Web Services Edition  <br/> |Sem suporte  <br/> |
|IMAP e POP  <br/> |Sem suporte  <br/> |
|Exchange ActiveSync (dispositivos móveis)  <br/> |Sem suporte  <br/> |
   
> [!NOTE]
> <sup>1</sup> Não há suporte para o Outlook incluído com o Microsoft Office Standard. Para saber mais, confira [Requisitos de licença para políticas de retenção e arquivamento pessoal](https://support.office.com/article/Outlook-license-requirements-for-Exchange-features-46B6B7C5-C3CA-43E5-8424-1E2807917C99). <br/> 
<sup>2</sup> Requer atualização para ativar o suporte ao arquivamento. Os usuários do Outlook 2007 não podem exibir ou aplicar as políticas de retenção ou de arquivamento nos itens em suas caixas de correio de arquivamento; eles devem usar as políticas fornecidas pelo administrador. E mais, os usuários do Outlook 2007 não podem pesquisar a caixa de correio local e o arquivamento ao mesmo tempo. <br/> 
<sup>3</sup> Você não pode usar o Outlook 2016 para Mac ou Outlook para Mac para mover ou copiar pastas, itens de calendário, contatos, tarefas ou anotações para seu arquivo morto ou exibi-los na caixa de correio de arquivo morto, se os itens foram movidos anteriormente para lá usando qualquer outra versão do Outlook (como Outlook 2016 para Windows). Para obter mais informações, [consulte Use your online archive with Outlook 2016 para Mac](https://support.office.com/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238). 

## <a name="outlook-on-the-web"></a>Outlook na Web

O Outlook na Web App é uma versão baseada na Web do programa de email do Outlook usado com o Exchange Online. Onde quer que os usuários estejam conectados à Internet em casa, no escritório ou na estrada, eles podem acessar seus emails Outlook &mdash; &mdash; na Web.
  
Os usuários podem acessar seus arquivos de arquivo morto Outlook na Web local (usando a mesma URL). O arquivo morto aparece junto com sua caixa de correio principal Outlook na Web. Não há nenhuma maneira explícita de acessar o arquivo morto diretamente Outlook na Web.
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos entre planos, opções autônomas e soluções locais, consulte [Arquivamento do Exchange Online descrição do serviço.](exchange-online-archiving-service-description.md)