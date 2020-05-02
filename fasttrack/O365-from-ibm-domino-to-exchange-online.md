---
title: 부록 A IBM Domino에서 Exchange Online으로 마이그레이션
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 5/01/2020
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: IBM Domino에서 Exchange Online으로의 마이그레이션에는 다음 단계 동안 발생하는 과정을 포함하여 몇 가지 중요한 측면이 포함됩니다.
ms.openlocfilehash: 3038ba8246ede185df3f2c15c548ff4ef8be9427
ms.sourcegitcommit: 2775660fc5ccab2e92aee9383e326dba22b7a16b
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/01/2020
ms.locfileid: "43999882"
---
# <a name="appendix-a---migration-from-ibm-domino-to-exchange-online"></a><span data-ttu-id="3e7ea-103">부록 A - IBM Domino에서 Exchange Online으로 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="3e7ea-103">Appendix A - Migration from IBM Domino to Exchange Online</span></span>

<span data-ttu-id="3e7ea-104">IBM Domino에서 Exchange Online으로의 마이그레이션에는 다음 단계 동안 발생하는 과정을 포함하여 몇 가지 중요한 측면이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-104">Migration from IBM Domino to Exchange Online includes several important aspects, including what happens during the following phases:</span></span> 
- [<span data-ttu-id="3e7ea-105">시작 단계</span><span class="sxs-lookup"><span data-stu-id="3e7ea-105">Initiate phase</span></span>](#initiate-phase)   
- [<span data-ttu-id="3e7ea-106">평가 단계</span><span class="sxs-lookup"><span data-stu-id="3e7ea-106">Assess phase</span></span>](#assess-phase)
- [<span data-ttu-id="3e7ea-107">재구성 단계</span><span class="sxs-lookup"><span data-stu-id="3e7ea-107">Remediate phase</span></span>](#remediate-phase)  
- [<span data-ttu-id="3e7ea-108">사용 단계</span><span class="sxs-lookup"><span data-stu-id="3e7ea-108">Enable phase</span></span>](#enable-phase)  
- [<span data-ttu-id="3e7ea-109">마이그레이션 단계</span><span class="sxs-lookup"><span data-stu-id="3e7ea-109">Migrate phase</span></span>](#migrate-phase)
    
## <a name="identities"></a><span data-ttu-id="3e7ea-110">ID</span><span class="sxs-lookup"><span data-stu-id="3e7ea-110">Identities</span></span>

<span data-ttu-id="3e7ea-111">ID를 만들고 관리하는 일은 사용자가 진행합니다(클라우드 전용, 온-프레미스 Active Directory와 동기화 또는 페더레이션).</span><span class="sxs-lookup"><span data-stu-id="3e7ea-111">You are responsible for creating and managing the identities (cloud only, synchronized, or federated with their on-premises Active Directory).</span></span> <span data-ttu-id="3e7ea-112">온보딩의 초기 단계에서 Domino와 온-프레미스 Active Directory 또는 Azure Active Directory 간에 ID 매핑(아직 없는 경우)을 완료해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-112">You must complete the mapping of identities (if not already present) between Domino and the on-premises Active Directory or Azure Active Directory during the early stages of onboarding.</span></span>
  
## <a name="coexistence"></a><span data-ttu-id="3e7ea-113">동시 사용</span><span class="sxs-lookup"><span data-stu-id="3e7ea-113">Coexistence</span></span>

<span data-ttu-id="3e7ea-114">Office 365용 FastTrack 센터 혜택은 온-프레미스 Domino 환경과 Exchange Online 간 양방향 메일 흐름을 모든 고객에게 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-114">The FastTrack Center Benefit for Office 365 provides bidirectional mail flow between the on-premises Domino environment and Exchange Online to all customers.</span></span>
  
## <a name="migration"></a><span data-ttu-id="3e7ea-115">마이그레이션</span><span class="sxs-lookup"><span data-stu-id="3e7ea-115">Migration</span></span>

<span data-ttu-id="3e7ea-p102">Domino에서 Exchange Online으로 마이그레이션 위한 표준 FastTrack 센터 프로세스에는 Exchange Online 사서함으로 마이그레이션하기 전에 Azure에 대한 Domino 데이터 사전 준비 과정이 포함됩니다. FastTrack 마이그레이션을 위해서는 FastTrack 센터 직원 및 사용자가 다른 온보딩 단계에서 작업을 수행해야 합니다. 이러한 작업은 다음 섹션에서 설명됩니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-p102">The standard FastTrack Center process for migration from Domino to Exchange Online involves pre-staging Domino data to Azure before migration to Exchange Online mailboxes. FastTrack migrations require activities to be performed at different stages of onboarding by FastTrack Center personnel and you. We cover these activities in the following sections.</span></span>
  
> [!NOTE]
> <span data-ttu-id="3e7ea-p103">FastTrack 서비스를 통해 마이그레이션된 데이터는 미국 및 Microsoft에서 시설을 유지 관리는 어디에서나 전송, 저장 및 처리될 수 있습니다. FastTrack 서비스는 특별 법적 또는 규정 요구 사항을 따르는 데이터에 맞게 설계되었거나 이러한 데이터용으로 작성되지 않았습니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-p103">Data migrated through the FastTrack services may be transferred to, stored, and processed in the United States or anywhere that Microsoft maintains facilities. The FastTrack services aren't designed or intended for data subject to special legal or regulatory requirements.</span></span> 
  
## <a name="initiate-phase"></a><span data-ttu-id="3e7ea-121">시작 단계</span><span class="sxs-lookup"><span data-stu-id="3e7ea-121">Initiate phase</span></span>

 <span data-ttu-id="3e7ea-122">**핵심 작업**</span><span class="sxs-lookup"><span data-stu-id="3e7ea-122">**Key actions**</span></span>
  
- <span data-ttu-id="3e7ea-123">Domino를 원본 메일 플랫폼으로 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-123">Identify Domino as the source mail platform.</span></span>   
- <span data-ttu-id="3e7ea-124">FastTrack 센터에서 마이그레이션을 수행할지 여부를 확인합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-124">Determine whether the FastTrack Center performs the migration.</span></span>
    
 <span data-ttu-id="3e7ea-125">**고객 책임**</span><span class="sxs-lookup"><span data-stu-id="3e7ea-125">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="3e7ea-126">원본 메시징 플랫폼에 대한 기본 정보를 제공하고 FastTrack 센터를 사용하여 마이그레이션 의도를 확인합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-126">Provide basic information about the source messaging platform, and confirm the migration intent with the FastTrack Center.</span></span> 
- <span data-ttu-id="3e7ea-127">FastTrack 센터 혜택 프로세스 연습 과정에 참여합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-127">Participate in a walkthrough of the FastTrack Center Benefit processes.</span></span>  
- <span data-ttu-id="3e7ea-128">FastTrack 서비스 계약에 서명합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-128">Sign the FastTrack Services Agreement.</span></span>
    
## <a name="assess-phase"></a><span data-ttu-id="3e7ea-129">평가 단계</span><span class="sxs-lookup"><span data-stu-id="3e7ea-129">Assess phase</span></span>

 <span data-ttu-id="3e7ea-130">**핵심 작업**</span><span class="sxs-lookup"><span data-stu-id="3e7ea-130">**Key actions**</span></span>
  
- <span data-ttu-id="3e7ea-131">FastTrack 센터에서는 고객과 함께 마이그레이션 워크샵을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-131">The FastTrack Center conducts a migration workshop with the customer.</span></span> 
- <span data-ttu-id="3e7ea-132">마이그레이션 설문 조사 및 관리자 워크스테이션 프로비저닝과 같은 마이그레이션 필수 구성 작업을 완료합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-132">You complete the migration prerequisites, like the migration questionnaire and the provisioning of admin workstations.</span></span>    
- <span data-ttu-id="3e7ea-133">Domino에 대한 마이그레이션 평가는 온-프레미스 환경에서 수행됩니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-133">Migration assessment for Domino is performed in your on-premises environment.</span></span>
    
 <span data-ttu-id="3e7ea-134">**고객 책임**</span><span class="sxs-lookup"><span data-stu-id="3e7ea-134">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="3e7ea-135">FastTrack 센터에서 평가, 복제본 만들기, 감사, 마이그레이션 동안의 설정 전달 등의 온보딩 및 마이그레이션 작업을 관리하는 데 사용하는 관리 워크스테이션을 프로비전합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-135">Provision admin workstations that the FastTrack Center uses to administer onboarding and migration tasks, like assessment, replica creation, auditing, setting forwarding during migration, and so on.</span></span>
    > [!NOTE]
    > <span data-ttu-id="3e7ea-p104">성공적인 계획 및 빠른 마이그레이션 실행을 위해 평가는 반드시 필요합니다. 이 작업은 Domino 환경에 대해 특정 액세스를 필요로 하는 마이그레이션 설계자가 수행합니다. 필요한 관리 워크스테이션 구성 요소에는 모든 원본 Domino 메일 서버 및 Azure Domino 복제본 준비 서버에 액세스하도록 구성된 Notes 클라이언트가 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-p104">Assessment is critical for successful planning and execution of velocity migrations. It's performed by a migration architect who needs specific access to the Domino environment. Required admin workstation components include a Notes client configured to access all source Domino mail servers and the Azure Domino replica staging server.</span></span> 
- <span data-ttu-id="3e7ea-p105">평가 및 마이그레이션 작업 수행을 위해 마이그레이션 팀에 관리자 워크스테이션, 계정 및 권한에 대한 원격 액세스를 제공합니다. 여기에는 마이그레이션에 필요한 관리자 권한으로 온-프레미스 및 Exchange Online에서 여러 계정을 프로비전하는 능력도 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-p105">Provide the migration team remote access to the admin workstations, accounts, and permissions for performing assessment and migration activities. This includes provisioning multiple accounts on-premises and in Exchange Online with administrative permissions needed for migration.</span></span>    
- <span data-ttu-id="3e7ea-p106">방화벽 포트를 엽니다. 원본 Domino 메일 서버와 Azure 준비 서버 간에 아웃바운드 포트가 열려 있어야 합니다. 통신을 위한 기타 포트(예: 관리자 워크스테이션, 원본 Domino 서버 및 Exchange Server 온-프레미스(있는 경우))도 열려 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-p106">Open firewall ports. Outbound ports must be opened between the source Domino mail servers and the Azure staging server. Other ports for communication (like admin workstations, source Domino servers, and Exchange servers on-premises (if present)) must also must be opened.</span></span> 
- <span data-ttu-id="3e7ea-p107">원본 Domino 환경과 Azure Domino 준비 서버 간의 상호 인증을 사용하도록 설정하여 복제를 지원합니다. 상호 인증 작업은 고객의 Domino 관리자 및 FastTrack 센터 간에 적절히 조정됩니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-p107">Enable cross-certification between the source Domino environment and the Azure Domino staging server to facilitate replication. Cross-certification tasks are coordinated between the customer's Domino admin and the FastTrack Center.</span></span>  
- <span data-ttu-id="3e7ea-146">Azure에서 마이그레이션 환경(예: 도구, 스크립트 및 마이그레이션 서버)을 구성하는 데 필요한 정보를 캡처하는 마이그레이션 설문 조사를 완료합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-146">Complete the migration questionnaire, which captures information required to configure the migration environment in Azure (like tools, scripts, and migration servers).</span></span>   
- <span data-ttu-id="3e7ea-147">Office 365의 대상 사서함에 메시징 MAPI(Messaging Application Program Interface) 프로토콜이 사용하도록 설정되었는지 확인합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-147">Ensure target mailboxes in Office 365 have Messaging Application Program Interface (MAPI) protocol enabled.</span></span>  
> [!NOTE]
> <span data-ttu-id="3e7ea-p108">일부 Office 365 요금제는 MAPI 프로토콜을 지원하지 않습니다. 데이터를 마이그레이션하려면 마이그레이션 이벤트 전에 이러한 요금제의 사서함이 MAPI를 지원하는 요금제로 전환되어야 합니다. 마이그레이션을 수행하면 이러한 요금제가 원래 상태로 다시 변경됩니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-p108">Some Office 365 plans don't support MAPI protocol. In order to migrate data, mailboxes from these plans need to be converted to a plan that supports MAPI ahead of the migration event. Following migration, these plans can be changed back.</span></span> 
  
## <a name="remediate-phase"></a><span data-ttu-id="3e7ea-151">재구성 단계</span><span class="sxs-lookup"><span data-stu-id="3e7ea-151">Remediate phase</span></span>

 <span data-ttu-id="3e7ea-152">**핵심 작업**</span><span class="sxs-lookup"><span data-stu-id="3e7ea-152">**Key actions**</span></span>
  
- <span data-ttu-id="3e7ea-153">FastTrack 센터는 마이그레이션 평가 보고서를 검토하고 설문 조사를 사용하여 사용자가 제공한 정보를 테스트합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-153">The FastTrack Center reviews the migration assessment report and tests the details that you supply using the questionnaire.</span></span>   
- <span data-ttu-id="3e7ea-154">FastTrack 센터에서 제안한 재구성 항목은 사용자가 완료해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-154">Remediation items suggested by the FastTrack Center must be completed by you.</span></span>
    
 <span data-ttu-id="3e7ea-155">**고객 책임**</span><span class="sxs-lookup"><span data-stu-id="3e7ea-155">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="3e7ea-156">FastTrack 센터에서 제공하는 지침(예: 메일 파일에서 누락된 것으로 확인된 모든 필수 권한 설정)에 따라 Domino 환경을 재구성합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-156">Remediate the Domino environment based on guidelines that the FastTrack Center provides (for example, setting any required permissions that are identified as missing in the mail files).</span></span>  
- <span data-ttu-id="3e7ea-157">Domino 사서함이 마이그레이션 대상으로 허용되는 최대 크기보다 작은지 확인합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-157">Ensure that Domino mailboxes are below the maximum size allowed through migration.</span></span>
    > [!NOTE]
    >  <span data-ttu-id="3e7ea-158">FastTrack은 허용 가능한 총 대상 크기의 85%까지 사서함을 마이그레이션하지만 2GB보다 더 큰 사서함을 마이그레이션하려고 하면 다음과 같은 추가 위험이 발생합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-158">Although FastTrack migrates mailboxes up to 85% of the total allowable target size, attempting to migrate mailboxes larger than 2 GB carries additional risks like:</span></span>    <br/> <span data-ttu-id="3e7ea-p109">마이그레이션 지속 시간 연장    </span><span class="sxs-lookup"><span data-stu-id="3e7ea-p109">Lengthened duration of migrations.    </span></span><br/> <span data-ttu-id="3e7ea-p110">다른 사서함 마이그레이션에 사용될 리소스 사용    </span><span class="sxs-lookup"><span data-stu-id="3e7ea-p110">Using resources otherwise used for migrating other mailboxes.    </span></span><br/> <span data-ttu-id="3e7ea-161">심각한 오류율 증가</span><span class="sxs-lookup"><span data-stu-id="3e7ea-161">A considerable increase in error rates.</span></span> 
- <span data-ttu-id="3e7ea-p111">메일 포함 데이터베이스 및 해당 ACL(액세스 제어 목록)의 마이그레이션 준비 메일 포함 데이터베이스 및 해당 사용 권한을 공유 사서함에 성공적으로 마이그레이션하려면 Exchange Online에서 일부 재구성 단계를 수행해야 합니다. 이러한 단계는 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-p111">Prepare the mail-in databases and their access control lists (ACLs) for migration. You must perform some remediation steps to successfully migrate mail-in databases and their permissions to a shared mailbox in Exchange Online. A few of these steps are as follows:</span></span> 
  - <span data-ttu-id="3e7ea-165">Domino 디렉터리에 있는 기존 메일 포함 데이터베이스 항목을 제거하고 새 개인 레코드를 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-165">Remove existing mail-in database entries in the Domino directory and create new Person records.</span></span>
  - <span data-ttu-id="3e7ea-166">온-프레미스 Active Directory에 Office 365 Azure Active Directory와 동기화되고 Exchange Online에서 공유 사서함에 대한 사용 권한을 구성하는 데 사용되는 메일 사용이 가능한 유니버설 보안 그룹을 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-166">Create mail-enabled universal security groups in the on-premises Active Directory that are synchronized to Office 365 Azure Active Directory and used to configure permissions on the shared mailbox in Exchange Online.</span></span> <span data-ttu-id="3e7ea-167">이렇게 하면 메일 포함 데이터베이스에 대해 설정된 사용 권한이 Exchange Online의 공유 사서함으로 전송됩니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-167">This transfers the permissions set on the mail-in database over to the shared mailbox in Exchange Online.</span></span>
    
> [!NOTE]
> <span data-ttu-id="3e7ea-168">새로운 메시징 시스템 및 클라이언트에 대한 최종 사용자 준비 및 교육 과정을 지금 시작할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-168">End-user readiness and training for the new messaging system and client can be started now.</span></span> 
  
## <a name="enable-phase"></a><span data-ttu-id="3e7ea-169">사용 단계</span><span class="sxs-lookup"><span data-stu-id="3e7ea-169">Enable phase</span></span>

 <span data-ttu-id="3e7ea-170">**핵심 작업**</span><span class="sxs-lookup"><span data-stu-id="3e7ea-170">**Key actions**</span></span>
  
- <span data-ttu-id="3e7ea-171">FastTrack 센터는 다음을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-171">The FastTrack Center:</span></span> 
    - <span data-ttu-id="3e7ea-172">Azure에서 마이그레이션 환경을 설정합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-172">Sets up the migration environment in Azure.</span></span>  
    - <span data-ttu-id="3e7ea-173">온-프레미스 관리자 워크스테이션에서 마이그레이션 도구를 구성합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-173">Configures the migration tools on the on-premises admin workstations.</span></span> 
    - <span data-ttu-id="3e7ea-174">자동 가져오기 도구를 구성하며, 사용 방법을 보여 줍니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-174">Configures and demonstrates how to use the Auto-Import tool.</span></span>  
    - <span data-ttu-id="3e7ea-175">모든 마이그레이션 구성 요소에 대한 유효성 검사를 수행하고 테스트 마이그레이션을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-175">Conducts validation of all migration components and performs test migrations.</span></span>
    
 <span data-ttu-id="3e7ea-176">**고객 책임**</span><span class="sxs-lookup"><span data-stu-id="3e7ea-176">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="3e7ea-p113">사서함 마이그레이션 일정을 담당하는 직원은 자동 가져오기 도구의 사용 방법을 숙지해야 합니다. 이 도구를 사용하여 FastTrack 센터에서 마이그레이션 전 작업을 수행하는 데 사용하는 일정 데이터베이스로 마이그레이션 일정을 가져올 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-p113">Your personnel in charge of scheduling mailbox migration must understand how to use the Auto-Import tool. You use this tool to import the migration schedule into the scheduling database which the FastTrack Center uses to perform pre-migration activities.</span></span> 
- <span data-ttu-id="3e7ea-179">사용자 일정 가져오기, 감사 보고서 분석, 문제 재조정, 문제가 있는 사용자 계정을 다시 가져오기 등의 마이그레이션 전 작업을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-179">Perform pre-migration activities like importing user schedules, analyzing audit reports, remediating any issues, and reimporting user accounts with problems.</span></span>
    
<span data-ttu-id="3e7ea-p114">마이그레이션 전 작업은 사용자와 FastTrack 센터 간에 조정됩니다. 사용자 마이그레이션 일정을 가져온 후에 Azure로의 복제가 시작됩니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-p114">Pre-migration activities are coordinated between you and the FastTrack Center. Replication to Azure begins after the user migration schedule is imported.</span></span> 
    
> [!NOTE]
> <span data-ttu-id="3e7ea-p115">복제에 필요한 시간은 데이터의 양에 따라 달라집니다. 그러면 FastTrack 센터는 감사를 수행하여 마이그레이션 준비 상태를 확인합니다. 감사 결과가 제공되며 일반적으로는 후속 재구성이 필요합니다. 이러한 모든 단계는 사용자의 예약된 마이그레이션에 앞서 시작해야 하므로 "T-minus" 작업이라고 합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-p115">The time required to replicate depends on the amount of data. The FastTrack Center then performs auditing to determine migration readiness. Audit results are provided to you with the understanding that subsequent remediation is normally required. All of these steps are called "T-minus" activities because they must begin in advance of the users' scheduled migration.</span></span> 
  
## <a name="migrate-phase"></a><span data-ttu-id="3e7ea-186">마이그레이션 단계</span><span class="sxs-lookup"><span data-stu-id="3e7ea-186">Migrate phase</span></span>

 <span data-ttu-id="3e7ea-187">**핵심 작업**</span><span class="sxs-lookup"><span data-stu-id="3e7ea-187">**Key actions**</span></span>
  
- <span data-ttu-id="3e7ea-188">FastTrack 센터는 다음을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-188">The FastTrack Center:</span></span>
    - <span data-ttu-id="3e7ea-189">파일럿 및 빠른 마이그레이션을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-189">Performs pilot and velocity migrations.</span></span>  
    - <span data-ttu-id="3e7ea-190">마이그레이션 이벤트 및 T-minus 작업을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-190">Performs migration events and T-minus activities.</span></span>
    - <span data-ttu-id="3e7ea-191">마이그레이션 후 지원을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-191">Provides post-migration assistance.</span></span>
    
 <span data-ttu-id="3e7ea-192">**고객 책임**</span><span class="sxs-lookup"><span data-stu-id="3e7ea-192">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="3e7ea-193">정의된 방법에 대한 일정과 각 마이그레이션 이벤트에 대해 마이그레이션하는 데 필요한 특정 사용자 데이터 목록을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-193">Provide a schedule in a defined method and a list of specific user data to migrate for each migration event.</span></span>
    > [!NOTE]
    > <span data-ttu-id="3e7ea-p116">실제 마이그레이션 날짜(T-0)가 되기 전에 여러 단계에 걸쳐 재구성 및 복제본 생성 재시도가 수행될 수 있으므로 이 작업은 매우 중요합니다. 일부 사서함이 마이그레이션되는 동안 다른 사서함에 대해 T-minus 작업이 수행됩니다. 따라서 적절한 계획과 조정이 필수적입니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-p116">This task is critical because the pre-migration activities involve remediation and possible retries of replica creation at different stages before the actual migration day (T-0). While some mailboxes are migrating, T-minus activities are being performed on others. This makes proper planning and coordination a must.</span></span> 
- <span data-ttu-id="3e7ea-197">T-minus 작업 동안 확인된 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-197">Fix issues identified during T-minus activities.</span></span>
- <span data-ttu-id="3e7ea-198">마이그레이션 작업에 영향을 주는 모든 Domino 서버 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-198">Address and fix any Domino server issues that impact migration activities.</span></span> 
- <span data-ttu-id="3e7ea-199">예정된 마이그레이션 날짜를 최종 사용자에게 알립니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-199">Conduct end-user communications about the upcoming migration date.</span></span>
- <span data-ttu-id="3e7ea-200">새로운 메시징 시스템 및 클라이언트에 대한 최종 사용자 준비 작업 및 교육 과정을 진행합니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-200">Conduct end-user readiness activities and training for the new messaging system and client.</span></span>   
- <span data-ttu-id="3e7ea-p117">마이그레이션 후 문제를 파악해서 보고합니다. FastTrack 센터는 마이그레이션이 있고 T+5일까지 마이그레이션 후 지원을 제공합니다. 그 이후부터는 사용자의 책임이 됩니다. 전자 메일, 일정 항목 및 연락처 누락 또는 사서함의 중복된 항목과 같은 문제에 대해 마이그레이션 후 티켓을 기록할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-p117">Identify and report post-migration issues. The FastTrack Center provides post-migration assistance until T+5 days after migration, after which it becomes your responsibility. You can log post-migration tickets for issues like missing emails, calendar items, and contacts, or for duplicates in the mailbox.</span></span>
    
<span data-ttu-id="3e7ea-204">FastTrack 센터는 디렉터리 준비(Domino-Active Directory 디렉터리 동기화 포함), Notes 응용 프로그램 상호 운용성을 위한 동시 사용 소프트웨어 추가 기능, 셀프 서비스 마이그레이션 또는 보관 파일 마이그레이션과 관련된 배포, 라이선스 요금 또는 지원을 제공하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="3e7ea-204">The FastTrack Center doesn't cover deployment, license fees, or assistance related to directory preparation (including Domino-to-Active Directory directory synchronization), coexistence software add-ons for Notes application interoperability, self-service migration, or archive migration.</span></span>
