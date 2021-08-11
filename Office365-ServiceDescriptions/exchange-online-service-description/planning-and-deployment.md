---
title: Planejamento e implantação
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-planning-and-deployment
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: e44e5e61-1f5d-4e68-981d-77a42f0ea0d4
description: Saiba mais sobre planejamento e implantação Microsoft Exchange Online.
ms.openlocfilehash: 60edd1a35112f7344eaf4e0badf8a49f04c0daa99d7b11b94220ed9973b6faf6
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 08/06/2021
ms.locfileid: "54663664"
---
# <a name="planning-and-deployment"></a>Planejamento e implantação

## <a name="planning-for-service-changes-and-growth"></a>Planejamento para alterações e crescimento do serviço

As organizações devem escolher as opções de migração baseadas em seus sistemas de origem de email, os estados finais desejados (totalmente ou parcialmente hospedados), o número de usuários a serem migrados e de quanto tempo o estado final precisa para ser atingido.
  
## <a name="deployment-options"></a>Opções de implantação

- **Implantação somente na nuvem** - Sua organização tem todas as caixas de correio de usuário hospedadas no Exchange Online. 
    
- **Exchange** implantação híbrida - Sua organização tem algumas caixas de correio de usuário hospedadas em uma organização Exchange local e algumas caixas de correio de usuário hospedadas em Exchange Online. 
    
### <a name="cloud-only"></a>Apenas Nuvem

Uma implantação somente em nuvem representa a modalidade em que sua organização no serviço Exchange Online não está conectada a uma organização local do Exchange. Todos os usuários e caixas de correio estão hospedados e são gerenciados no Exchange Online e no Office 365.
  
### <a name="hybrid"></a>Híbrido

Disponível para organizações locais do Microsoft Exchange 2003, Exchange 2007, Exchange 2010 e Exchange 2013, uma implantação híbrida oferece tanto uma configuração de coexistência de longo prazo, com algumas caixas de correio hospedadas no local e outras hospedadas no Exchange Online, ou um caminho de migração para hospedar todas as caixas de correio do usuário no Exchange Online. Uma implantação híbrida oferece às organizações a capacidade de levar a experiência e o controle administrativo cheio de recursos que elas possuem em suas organizações locais do Microsoft Exchange para a nuvem. Os recursos da implantação híbrida incluem transporte de email seguro, informações de disponibilidade do calendário compartilhado e acompanhamento de mensagens entre as organizações locais e do Exchange Online.
  
Para saber mais sobre implantações híbridas, confira [Implantações híbridas do Exchange Server 2013](/exchange/exchange-hybrid). Se você estiver usando o Office 365 operado pela 21Vianet, confira [Configurando recursos de implantação híbrida do Exchange com o Office 365 operado pela 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733373&amp;clcid=0x409).
  
> [!IMPORTANT]
> As organizações locais do Exchange 2003 devem instalar no mínimo um servidor de Acesso de Cliente/Caixa de Correio do Exchange 2010, para configurar uma implantação híbrida com o Exchange Online. As organizações locais do Exchange 2007 devem instalar no mínimo um servidor de Acesso de Cliente e Caixa de Correio do Exchange 2010, ou do Exchange 2013, para configurar uma implantação híbrida com o Exchange Online. As organizações locais do Exchange 2010 e Exchange 2013 suportam, de forma nativa, as implantações híbridas com o Exchange Online. Para saber mais sobre a compatibilidade do servidor Exchange em implantações híbridas, confira [Pré-requisitos da implantação híbrida](/exchange/hybrid-deployment-prerequisites)> As organizações locais do Exchange devem configurar sua organização para uma implantação híbrida. É altamente recomendável que os administradores usem o Assistente de Implantação do Exchange Server e o Assistente de Configuração Híbrida, para configurar a implantação híbrida. Saiba mais em [Assistente de Implantação do Exchange Server](/exchange/exchange-deployment-assistant)
  
## <a name="migration-options"></a>Opções de Migração

As organizações devem escolher as opções de migração baseadas em seus sistemas de origem de email, os estados finais desejados (totalmente ou parcialmente hospedados), o número de usuários a serem migrados e de quanto tempo o estado final precisa para ser atingido. As opções de migração possíveis são:
  
- **Migração IMAP** - Migrar dados de caixa de correio de sistemas de email baseados em IMAP para Exchange Online. 
    
- Migração de **Exchange** - Migrar caixas de correio do Exchange Server 2003, Exchange Server 2007, Exchange Server 2010, Exchange 2013 e sistemas Exchange hospedados para Exchange Online em uma única migração de recortamento. 
    
- Migração em **estágios Exchange** - Realize uma migração em estágios para migrar caixas de correio do Exchange Server 2003 ou Exchange Server 2007 com ferramentas de migração baseadas na Web e alterações mínimas na infraestrutura local. 
    
- **Migração de movimentação** remota - Migre caixas de correio locais Exchange para Exchange Online em uma implantação Exchange híbrida. Você deve ter uma implantação híbrida do Exchange para usar uma migração de movimentação remota. 
    
Para saber mais sobre a migração de email e caixas de correio para o Exchange Online, consulte [Migração de Caixa de Correio para o Exchange Online ](https://support.office.com/article/-a3e3bddb-582e-4133-8670-e61b9f58627e).
  
### <a name="imap-migration"></a>Migração IMAP

O Exchange Online oferece uma ferramenta com base na web, para migrar dados da caixa de correio de sistemas de email que suportam IMAP. Ele orienta os administradores com as seguintes etapas de migração: 
  
1. Crie caixas de correio vazias na nuvem para usuários da organização (normalmente, isso é feito ao carregar um arquivo .csv ou usando o Windows PowerShell remoto).
    
2. Insira as configurações de conexão do servidor remoto.
    
3. Utilize um arquivo CSV para especificar as caixas de correio cujos dados serão migrados para as caixas de correio do Exchange Online.
    
4. Após inserir essa informação, o Exchange Online iniciará a migração do conteúdo da caixa de correio pelo IMAP (itens de calendário, contatos, tarefas e outros itens não relacionados a email não são migrados).
    
Para saber mais sobre migração IMAP, consulte [Migrar Email de um Servidor IMAP para Caixas de Correio do Exchange Online](https://support.office.com/en-ie/article/Migrate-your-IMAP-mailboxes-to-Office-365-3fe19996-29bc-4879-aab9-5a622b2f1481) e [Migrar outros tipos de caixas de correio IMAP](https://support.office.com/en-ie/article/Migrate-other-types-of-IMAP-mailboxes-to-Office-365-58890ccd-ce5e-4d94-be75-560a3b70a706).
  
> [!IMPORTANT]
> Para evitar o uso excessivo dos recursos remotos do servidor e largura de banda durante a migração, o Exchange Online cria menos de 10 conexões para o servidor IMAP. 
  
### <a name="cutover-exchange-migration"></a>Migração de substituição do Exchange

O Exchange Online oferece uma ferramenta com base na web para migrar dados dos ambientes locais do Exchange Server 2003, Exchange Server 2007 ou Exchange Server 2010. Ele orienta o administrador com as seguintes etapas de migração:
  
1. Usando o endereço de email e as credenciais para uma conta de administrador local, o Exchange Online se conecta à organização de email local, usando o serviço de Descoberta Automática.
    
2. O Exchange Online usa uma conexão RPC/HTTP para ler informações do diretório a partir do servidor remoto e criar caixas de correio no Exchange Online.
    
3. O Exchange Online sincroniza o conteúdo da caixa de correio para as caixas de correio da nuvem. Os usuários permanecem conectados às caixas de correio originais enquanto seus dados são migrados para o Exchange Online.
    
4. Após a conclusão da migração inicial, quaisquer mudanças serão sincronizadas com a nuvem a cada 24 horas, até que o administrador pare ou exclua o lote de migração.
    
Para alternar os usuários para suas caixas de correio de nuvem, os administradores configuram seu registro MX para apontar para a Microsoft e reconfigurar os perfis dos usuários no Outlook. Quando os usuários alternam para suas caixas de correio da nuvem, suas pastas offline locais (arquivos .ost) serão sincronizadas novamente, resultando no download do email migrado para a estação de trabalho do cliente. Os usuários podem responder às mensagens antigas em suas caixas de correio após a migração.
  
Para saber mais sobre uma migração de substituição do Exchange migration, consulte [O que você precisa saber sobre uma migração de substituição de email para o Office 365](https://support.office.com/article/365-961978ef-f434-472d-a811-1801733869da).
  
> [!IMPORTANT]
> Uma organização pode migrar um máximo de 2.000 caixas de correio do Exchange 2003, do Exchange 2007, do Exchange 2010 ou do Exchange 2013 para a nuvem usando uma migração de substituição do Exchange. > O Exchange Online deve conectar-se ao Exchange Server local, para que o servidor local tenha um certificado emitido por uma autoridade certificada confiável e um endereço IP público. 
  
### <a name="staged-exchange-migration"></a>Migração do Exchange por estágio

Com uma migração em estágios, os usuários podem ser migrados para a nuvem, usando a ferramenta de migração do Exchange com base na web e a ferramenta de Sincronização de Diretório. Ao invés de migrar todos os usuários de uma só vez, como a migração de substituição do Exchange, os administradores migram os usuários em lotes. Essa ação é realizada ao carregar um arquivo .csv para especificar uma lista parcial dos usuários a serem migrados. Em uma migração em estágios, todos os usuários em uma organização podem compartilhar o mesmo nome de domínio do email.
  
A migração em estágios do Exchange requer que os administradores usem a ferramenta de Sincronização de Diretório dos Serviços Online. Ela fornece aos usuários uma Lista de Endereços Global (GAL) unificada, na qual o ambiente online é continuamente sincronizado com o ambiente local.
  
Para saber mais sobre migração em estágios no Exchange, consulte [O que você precisa saber sobre uma migração em estágios de email](https://support.office.com/en-ie/article/365-7e2c82be-5f3d-4e36-bc6b-e5b4d411e207).
  
> [!IMPORTANT]
> As organizações não podem usar uma migração em estágios do Exchange para migrar caixas de correio do Exchange 2010 e do Exchange 2013. Se você tiver menos de 2.000 caixas de correio do Exchange 2010 ou do Exchange 2013 em sua organização, poderá usar uma migração de substituição do Exchange. Se você possui mais de 2.000 caixas de correio do Exchange 2010 ou do Exchange 2013, poderá implementar uma implantação híbrida. > Durante a migração, os administradores devem usar a ferramenta de Sincronização de Diretório dos Serviços Online para fornecer aos usuários uma Lista de Endereços Global, na qual o ambiente online é continuamente sincronizado com o ambiente local. 
  
## <a name="migration-tools"></a>Ferramentas de migração

A Microsoft oferece diversas ferramentas para ajudar na migração de um ambiente de email existente para o Exchange Online. Quais delas serão adequadas dependerá do ambiente atual da organização e dos objetivos da implantação:
  
- **Painel de** migração - Os administradores podem usar o painel de migração no centro de administração Exchange para gerenciar a migração de caixa de correio para Exchange Online em uma migração de Exchange de recortamento ou em estágios. Os administradores também podem usar o painel para migrar o conteúdo das caixas de correio dos usuários de um servidor IMAP local para caixas de correio existentes do Exchange Online. O painel oferece aos administradores as seguintes capacidades: 
    
  - **Criar e iniciar vários lotes de migração** - Os administradores podem criar e enfilar até 100 lotes de migração. Apenas um lote de migração é processado por vez, porém, os administradores podem colocar em fila diversos lotes, para que, quando um lote de migração for processado, o próximo lote da fila será iniciado. 
    
  - **Reiniciar** um lote de migração com falhas - Após a sincronização inicial para um lote de migração, onde os itens são copiados de caixas de correio locais para as caixas de correio de nuvem para cada usuário no lote de migração, algumas caixas de correio podem falhar na sincronização. Os administradores podem reiniciar esse lote de migração para tentar sincronizar as caixas de correio que apresentaram falha. 
    
  - Obter detalhes sobre itens ignorados **-** Para migrações IMAP, migrações de recortamento e migrações em estágios, o painel de migração exibe informações sobre os itens específicos que foram ignorados, incluindo o motivo e onde o item está localizado na caixa de correio do usuário. 
    
  - **Relatórios de migração** abertos - Os administradores podem abrir estatísticas de migração ou o relatório de erro de migração para um lote de migração direto do painel. 
    
  - **Editar um lote de** migração - Se um lote de migração para uma migração em estágios Exchange ou uma migração IMAP estiver na fila de migração, mas não estiver em execução no momento, os administradores poderão editar o lote de migração. 
    
- **Azure Active Directory Ferramenta de** sincronização - a ferramenta Azure Active Directory Sync desempenha um papel importante na migração para cenários de email híbridos que utilizam o Exchange Online e um Exchange Server. A ferramenta desempenha uma sincronização unidirecional do Active Directory local para o Exchange Online. Após a conclusão da migração, os administradores precisam apenas usar o Exchange Online para gerenciar os usuários e os grupos do Active Directory. A ferramenta também oferece aos usuários uma Lista de Endereços Global unificada em que o ambiente online é continuamente sincronizado com o ambiente local. 
    
    Para saber mais sobre o Ferramenta de Sincronização do Microsoft Azure Active Directory, confira [Sincronização de diretórios: mapa](/azure/active-directory/hybrid/whatis-hybrid-identity).
    
- **Assistente de Configuração** Híbrida - O Assistente de Configuração Híbrida simplifica o processo de implantação híbrida simplificando a configuração local e Exchange Online de recursos e serviços. Introduzido como parte do Exchange Server 2010 Service Pack 2, o Assistente de Configuração Híbrida é executado apenas nas organizações locais e possui os seguintes componentes: 
    
  - Um assistente do Centro de Administração do Exchange (EAC) que orienta os administradores por meio do processo ponta a ponta para configurar uma implantação híbrida.
    
  - Um conjunto de comandos do EMS (Shell de Gerenciamento do Exchange) orquestram o processo de configuração.
    
    Para saber mais sobre o Assistente de Configuração Híbrida, confira [Assistente de Configuração Híbrida](/exchange/hybrid-configuration-wizard).
    
- **Controle remoto Windows PowerShell** - Como parte da Atualização de Serviço Exchange Online de dezembro de 2011, os Windows PowerShell remotos podem ser usados para ajudar a solucionar erros de migração. Por exemplo, os administradores podem exibir informações de diagnósticos para lotes de migração, assim como as estatísticas de migração e as informações de diagnóstico para usuários baseadas em seus endereços SMTP principais. 
    
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos entre planos, opções autônomas e soluções locais, consulte, [Exchange Online descrição do serviço.](exchange-online-service-description.md)
