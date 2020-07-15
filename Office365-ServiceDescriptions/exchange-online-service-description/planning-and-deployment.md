---
title: Planejamento e implantação
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-planning-and-deployment
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: e44e5e61-1f5d-4e68-981d-77a42f0ea0d4
ms.openlocfilehash: e722bec332e67e93647b10bbbf4916e7e059c1b7
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132655"
---
# <a name="planning-and-deployment"></a>Planejamento e implantação

## <a name="planning-for-service-changes-and-growth"></a>Planejamento para alterações e crescimento do serviço

As organizações devem escolher as opções de migração baseadas em seus sistemas de origem de email, os estados finais desejados (totalmente ou parcialmente hospedados), o número de usuários a serem migrados e de quanto tempo o estado final precisa para ser atingido.
  
## <a name="deployment-options"></a>Opções de implantação

- **Implantação na Nuvem apenas** Sua organização tem todas as caixas de correio dos usuários hospedadas no Exchange Online. 
    
- **Implantação híbrida do Exchange** Sua organização tem algumas caixas de correio de usuários hospedadas em uma organização do Exchange local, e algumas caixas de correio dos usuários hospedadas no Exchange Online. 
    
### <a name="cloud-only"></a>Apenas Nuvem

A cloud-only deployment is one where your organization in the Exchange Online service isn't connected with an on-premises Exchange organization. All users and mailboxes are hosted and managed in Exchange Online and Office 365.
  
### <a name="hybrid"></a>Híbrido

Available for Microsoft Exchange 2003, Exchange 2007, Exchange 2010 and Exchange 2013 on-premises organizations, a hybrid deployment offers either a long-term coexistence configuration with some mailboxes hosted on-premises and some mailboxes hosted in Exchange Online or a migration path to hosting all user mailboxes in Exchange Online. A hybrid deployment offers organizations the ability to extend the feature-rich experience and administrative control they have with their existing on-premises Microsoft Exchange organization to the cloud. Hybrid deployment features include secure mail transport, shared calendar free/busy information, and message tracking between the on-premises and Exchange Online organizations.
  
For more information about hybrid deployments, see [Exchange Server 2013 Hybrid Deployments](https://go.microsoft.com/fwlink/p/?LinkId=287035). If you are using Office 365 operated by 21Vianet, see [Configuring Exchange hybrid deployment features with Office 365 operated by 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733373&amp;clcid=0x409).
  
> [!IMPORTANT]
> On-premises Exchange 2003 organizations must install at least one Exchange 2010 Client Access/Mailbox server to configure a hybrid deployment with Exchange Online. On-premises Exchange 2007 organizations must install at least one Exchange 2010 or Exchange 2013 Client Access and Mailbox server to configure a hybrid deployment with Exchange Online. On-premises Exchange 2010 and Exchange 2013 organizations natively support hybrid deployments with Exchange Online. For more information about Exchange server compatibility in hybrid deployments, see [Hybrid Deployment Prerequisites](https://go.microsoft.com/fwlink/p/?LinkId=243541)> On-premises Exchange organizations must configure their organization for a hybrid deployment. We strongly recommend that administrators use the Exchange Server Deployment Assistant and the Hybrid Configuration Wizard to configure the hybrid deployment. Learn more at [Exchange Server Deployment Assistant](https://go.microsoft.com/fwlink/p/?LinkId=287036)
  
## <a name="migration-options"></a>Opções de Migração

Organizations should choose migration options based on their source email systems, the desired end state (fully hosted or partially hosted), the number of users to migrate, and how quickly the end state needs to be reached. Possible migration options are:
  
- **Migração IMAP** Migrar dados da caixa de correio a partir de sistemas de email baseados em IMAP para o Exchange Online. 
    
- **Migração de substituição do Exchange** Migrar caixas de correio a partir do Exchange Server 2003, Exchange Server 2007, Exchange Server 2010, Exchange 2013 e sistemas do Hosted Exchange para o Exchange Online em uma única migração de substituição. 
    
- **Migração em estágios do Exchange** Realiza uma migração em estágios para migrar caixas de correio do Exchange Server 2003 ou Exchange Server 2007 com ferramentas de migração com base na web e alterações mínimas para infraestrutura local. 
    
- **Remote move migration** Migrate on-premises Exchange mailboxes to Exchange Online in an Exchange hybrid deployment. You must have an Exchange hybrid deployment to use a remote move migration. 
    
Para saber mais sobre a migração de email e caixas de correio para o Exchange Online, consulte [Migração de Caixa de Correio para o Exchange Online ](https://support.office.com/en-us/article/-a3e3bddb-582e-4133-8670-e61b9f58627e).
  
### <a name="imap-migration"></a>Migração IMAP

Exchange Online offers a web-based tool for migrating mailbox data from email systems that support IMAP. It guides administrators through the following migration steps: 
  
1. Crie caixas de correio vazias na nuvem para usuários da organização (normalmente, isso é feito ao carregar um arquivo .csv ou usando o Windows PowerShell remoto).
    
2. Insira as configurações de conexão do servidor remoto.
    
3. Utilize um arquivo CSV para especificar as caixas de correio cujos dados serão migrados para as caixas de correio do Exchange Online.
    
4. Após inserir essa informação, o Exchange Online iniciará a migração do conteúdo da caixa de correio pelo IMAP (itens de calendário, contatos, tarefas e outros itens não relacionados a email não são migrados).
    
Para saber mais sobre migração IMAP, consulte [Migrar Email de um Servidor IMAP para Caixas de Correio do Exchange Online](https://support.office.com/en-ie/article/Migrate-your-IMAP-mailboxes-to-Office-365-3fe19996-29bc-4879-aab9-5a622b2f1481) e [Migrar outros tipos de caixas de correio IMAP](https://support.office.com/en-ie/article/Migrate-other-types-of-IMAP-mailboxes-to-Office-365-58890ccd-ce5e-4d94-be75-560a3b70a706).
  
> [!IMPORTANT]
> Para evitar o uso excessivo dos recursos remotos do servidor e largura de banda durante a migração, o Exchange Online cria menos de 10 conexões para o servidor IMAP. 
  
### <a name="cutover-exchange-migration"></a>Migração de substituição do Exchange

Exchange Online offers a web-based tool for migrating data from on-premises Exchange Server 2003, Exchange Server 2007, or Exchange Server 2010 environments. It guides an administrator through the following migration steps:
  
1. Usando o endereço de email e as credenciais para uma conta de administrador local, o Exchange Online se conecta à organização de email local, usando o serviço de Descoberta Automática.
    
2. O Exchange Online usa uma conexão RPC/HTTP para ler informações do diretório a partir do servidor remoto e criar caixas de correio no Exchange Online.
    
3. Exchange Online synchronizes the mailbox content to the cloud mailboxes. Users remain connected to their original mailboxes while their data is being migrated to Exchange Online.
    
4. Após a conclusão da migração inicial, quaisquer mudanças serão sincronizadas com a nuvem a cada 24 horas, até que o administrador pare ou exclua o lote de migração.
    
Para mudar os usuários para suas caixas de correio de nuvem, os administradores configuram seu registro MX para apontar para a Microsoft e reconfigurar os perfis dos usuários no Outlook. Quando os usuários alternam para suas caixas de correio da nuvem, suas pastas offline locais (arquivos .ost) serão sincronizadas novamente, resultando no download do email migrado para a estação de trabalho do cliente. Os usuários podem responder às mensagens antigas em suas caixas de correio após a migração.
  
Para saber mais sobre uma migração de substituição do Exchange migration, consulte [O que você precisa saber sobre uma migração de substituição de email para o Office 365](https://support.office.com/en-us/article/What-you-need-to-know-about-a-cutover-email-migration-to-Office-365-961978ef-f434-472d-a811-1801733869da).
  
> [!IMPORTANT]
> An organization can migrate a maximum of 2,000 Exchange 2003, Exchange 2007, Exchange 2010, or Exchange 2013 mailboxes to the cloud using a cutover Exchange migration. > Exchange Online must connect to an on-premises Exchange Server, so the on-premises server must have a certificate issued by a trusted certificate authority and a public IP address. 
  
### <a name="staged-exchange-migration"></a>Migração do Exchange por estágio

With a staged migration, users can be migrated to the cloud using the web-based Exchange migration tool and the Directory Synchronization tool. Instead of migrating all users at once, like a cutover Exchange migration, administrators migrate users in batches. This is accomplished by uploading a .csv file to specify a partial list of users to migrate. In a staged migration, all of the users in an organization can share the same email domain name.
  
Staged Exchange migration requires administrators to use the Online Services Directory Synchronization tool. This provides users with a unified Global Address List (GAL) where the online environment is continuously synchronized with the on-premises environment.
  
Para saber mais sobre migração em estágios no Exchange, consulte [O que você precisa saber sobre uma migração em estágios de email](https://support.office.com/en-ie/article/What-you-need-to-know-about-a-staged-email-migration-to-Office-365-7e2c82be-5f3d-4e36-bc6b-e5b4d411e207).
  
> [!IMPORTANT]
> Organizations can't use a staged Exchange migration to migrate Exchange 2010 and Exchange 2013 mailboxes. If you have fewer than 2,000 Exchange 2010 or Exchange 2013 mailboxes in your organization, you can use a cutover Exchange migration. If you have more than 2,000 Exchange 2010 or Exchange 2013 mailboxes, you can implement a hybrid deployment. > During migration, administrators must use the Online Services Directory Synchronization tool to provide users with a unified Global Address List where the online environment is continuously synchronized with the on-premises environment. 
  
## <a name="migration-tools"></a>Ferramentas de migração

Microsoft provides several tools to help migrate an existing email environment to Exchange Online. Which ones are appropriate depends on the organization's current environment and deployment goals:
  
- **Migration dashboard** Administrators can use the Migration dashboard in the Exchange admin center to manage mailbox migration to Exchange Online in a cutover or staged Exchange migration. Administrators can also use the dashboard to migrate the contents of users' mailboxes from an on-premises IMAP server to existing Exchange Online mailboxes. The dashboard gives administrators the following capabilities: 
    
  - **Create and start multiple migration batches** Administrators can create and queue up to 100 migration batches. Only one migration batch runs at a time, but administrators can queue up multiple batches, so when a migration batch is finished running the next batch in the queue starts. 
    
  - **Restart a migration batch with failures** After the initial synchronization for a migration batch, where items are copied from on-premises mailboxes to the cloud mailboxes for each user in the migration batch, some mailboxes may fail synchronization. Administrators can restart that migration batch to try to synchronize the failed mailboxes. 
    
  - **Obter detalhes sobre itens ignorados** Para migrações de IMAP, migrações de substituição e migrações em estágios, o painel de Migração mostra informações sobre os itens específicos que foram ignorados, incluindo o motivo para isso e onde o item está localizado na caixa de correio do usuário. 
    
  - **Abrir relatórios de migração** Os administradores podem abrir as estatísticas de migração ou o relatório de erros de migração para um lote de migração, diretamente do painel. 
    
  - **Edite um lote de migração** Se um lote de migração para uma migração em estágios ou migração IMAP do Exchange está na fila de migração, mas não está atualmente sendo processado, os administradores podem editar o lote de migração. 
    
- **Azure Active Directory Sync tool** The Azure Active Directory Sync tool plays an important role in migration to hybrid email scenarios that utilize both Exchange Online and an on-premises Exchange Server. The tool performs a one-way synchronization from on-premises Active Directory to Exchange Online. After migration is complete, administrators only need to use Exchange Online to manage Active Directory users and groups. The tool also provides users with a unified Global Address List where the online environment is continuously synchronized with the on-premises environment. 
    
    Para saber mais sobre o Ferramenta de Sincronização do Microsoft Azure Active Directory, confira [Sincronização de diretórios: mapa](https://go.microsoft.com/fwlink/p/?LinkId=287034).
    
- **Hybrid Configuration Wizard** The Hybrid Configuration Wizard streamlines the hybrid deployment process by simplifying the on-premises and Exchange Online configuration of features and services. Introduced as part of Exchange Server 2010 Service Pack 2, the Hybrid Configuration Wizard is run only in on-premises organizations and has the following components: 
    
  - Um assistente do Centro de Administração do Exchange (EAC) que orienta os administradores por meio do processo ponta a ponta para configurar uma implantação híbrida.
    
  - Um conjunto de comandos do EMS (Shell de Gerenciamento do Exchange) orquestram o processo de configuração.
    
    Para saber mais sobre o Assistente de Configuração Híbrida, confira [Assistente de Configuração Híbrida](https://go.microsoft.com/fwlink/p/?LinkId=271734).
    
- **Remote Windows PowerShell** As part of the Exchange Online December 2011 Service Update, remote Windows PowerShell can be used to help troubleshoot migration errors. For instance, administrators can display diagnostic information for migration batches, as well as migration statistics and diagnostic information for users based on their primary SMTP addresses. 
    
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos nos planos, nas opções autônomas e nas soluções locais, consulte [Descrição do serviço do Exchange Online](exchange-online-service-description.md).
  

