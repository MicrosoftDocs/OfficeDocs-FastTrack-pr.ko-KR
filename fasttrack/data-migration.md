---
title: 데이터 마이그레이션
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 8/17/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: FastTrack은 원본 환경의 메일 및 파일 데이터를 Office 365(Exchange Online, SharePoint Online 및 비즈니스용 OneDrive)로 마이그레이션하는 데 도움이 됩니다. Microsoft가 제공하는 지원 유형은 Office 365 라이선스 수에 따라 다릅니다.
ms.openlocfilehash: fc7f07aea6104fdc6f06b3d624778919b351b34d
ms.sourcegitcommit: 81ad135578a329f8b0a3325c4e43bb8f90648597
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/17/2020
ms.locfileid: "46777024"
---
# <a name="data-migration"></a><span data-ttu-id="0254c-104">데이터 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="0254c-104">Data Migration</span></span>

<span data-ttu-id="0254c-105">FastTrack은 원본 환경의 메일 및 파일 데이터를 Office 365(Exchange Online, SharePoint Online 및 비즈니스용 OneDrive)로 마이그레이션하는 데 도움이 됩니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="0254c-106">Microsoft가 제공하는 지원 유형은 Office 365 라이선스 수에 따라 달라집니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="0254c-107">**150-499 라이선스를 보유한 Office 365 테넌트**: FastTrack은 마이그레이션 안내만 제공하며 데이터 마이그레이션을 수행해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="0254c-108">셀프 서비스 마이그레이션을 수행하기 위해 무료 도구를 계획하고 사용하는 데 도움이 되는 문서를 안내합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="0254c-109">**라이선스가 500개 이상인 Office 365 테넌트**: FastTrack은 마이그레이션 안내 및 데이터 마이그레이션 서비스를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="0254c-110">Microsoft는 마이그레이션 계획, 소스 환경 및 Office 365 테넌트 구성, 데이터 마이그레이션 서비스를 활용하여 데이터를 마이그레이션하는 데 도움이 되는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="0254c-111">마이그레이션 이벤트를 생성하고 예약합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-111">You create and schedule your migration events.</span></span> <span data-ttu-id="0254c-112">스케줄에 따라 마이그레이션 이벤트를 시작하고 진행률을 모니터링하며 상태 보고서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="0254c-113">2017년 9월 1일 이전에 상업용 계획을 구입하거나 갱신한 경우 데이터 마이그레이션 서비스를 받으려면 150개의 라이선스만 있으면 됩니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="0254c-114">교육 계획의 경우 유급 직원 및 직원 라이선스만 데이터 마이그레이션 서비스를 받을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="0254c-115">고려 사항</span><span class="sxs-lookup"><span data-stu-id="0254c-115">Considerations</span></span>

  - <span data-ttu-id="0254c-116">Office 365로 데이터를 마이그레이션하려면 소스 환경이 특정 기대치를 충족해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="0254c-117">Exchange, SharePoint 및 비즈니스용 OneDrive에 대한 소스 환경에 대한 자세한 내용은 [제품 및 기능](products-and-capabilities.md)을 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="0254c-118">데이터 마이그레이션 서비스를 제공하려면 소스 환경과 Office 365 테넌트에 대한 적절한 액세스 및 사용 권한이 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="0254c-119">Microsoft의 데이터 마이그레이션 서비스는 특별한 법적 또는 규제 요건에 따른 데이터용으로 설계되거나 설계되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="0254c-120">데이터를 마이그레이션할 때 FastTrack 마이그레이션 프로젝트에 별도로 제공된 경우를 제외하고, 이 데이터는 시설을 유지하는 모든 위치로 전송, 저장 및 처리될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="0254c-121">메일 또는 파일 마이그레이션 속도를 보장할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="0254c-122">소스 환경에서 읽을 수 없거나 손상된 항목과 같은 예기치 않은 문제로 인해 일부 데이터 항목을 마이그레이션하지 못할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="0254c-123">외부 요인(예: 타사 API(응용 프로그램 프로그래밍 인터페이스) 변경)은 데이터 마이그레이션 서비스의 변경, 지연 또는 중단으로 이어질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="0254c-124">마이그레이션 서비스를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-124">Migration service availability</span></span>

  - <span data-ttu-id="0254c-125">**상업 및 영국 정부 고객:** 당사는 24시간, 주 7일(24x7) 데이터 마이그레이션 서비스를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="0254c-126">**미국 정부/DOD 고객:** 당사는 하루 24시간, 주 5일 영업일(24x5) 데이터 마이그레이션 서비스를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="0254c-127">Exchange Online으로 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="0254c-127">Migration to Exchange Online</span></span>

<span data-ttu-id="0254c-128">FastTrack을 사용하여 Exchange Online으로 이메일을 마이그레이션하도록 선택하면 마이그레이션 안내 및 데이터 마이그레이션 서비스를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="0254c-129">Microsoft는 마이그레이션을 계획하고, 소스 환경과 Exchange Online을 구성하고, 데이터 마이그레이션 서비스를 활용하여 편지함을 마이그레이션하는 데 도움이 되는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="0254c-130">마이그레이션 이벤트를 생성하고 예약합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-130">You create and schedule your migration events.</span></span> <span data-ttu-id="0254c-131">스케줄에 따라 마이그레이션 이벤트를 시작하고 진행률을 모니터링하며 상태 보고서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="0254c-132">마이그레이션 이벤트가 완료되면 해당 소스 환경의 적절한 예약 및 적격 소스 사서함에서 온 메일이 Exchange Online으로 마이그레이션될 것으로 예상할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="0254c-133">고려 사항</span><span class="sxs-lookup"><span data-stu-id="0254c-133">Considerations</span></span>

  - <span data-ttu-id="0254c-134">마이그레이션하기 전에 Exchange Online용 FastTrack 코어 온보딩을 완료해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="0254c-135">직접 온보드 탑재를 수행한 경우 필요한 검사 및 필수 구성 요소를 통과해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="0254c-136">자세한 내용은 [제품 및 기능](products-and-capabilities.md)을(를) 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="0254c-137">FastTrack은 활성 Office 365 사서함으로만 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="0254c-138">온-프레미스 Exchange 환경에서 마이그레이션하려면 특정 요구 사항을 충족해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="0254c-139">자세한 내용은 [하이브리드 배포 필수 구성 요소](https://go.microsoft.com/fwlink/?LinkId=787528)를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="0254c-140">각 소스 환경은 소스 환경의 각 제품에 대한 최신 서비스 팩(SP) 및 롤업(RU)/누적 업데이트(CU) 레벨에 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="0254c-141">사내 Active Directory에 있는 메일 그룹(*MailEnabledGroup* 개체) 및 외부 연락처(*MailEnableContact* 개체)는 사서함 데이터 마이그레이션의 일부가 아닙니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="0254c-142">그러나 Azure AD(Azure Active Directory) 연결을 사용하여 동기화할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="0254c-143">원본 환경</span><span class="sxs-lookup"><span data-stu-id="0254c-143">Source environments</span></span>

<span data-ttu-id="0254c-144">Microsoft의 데이터 마이그레이션 서비스는 다음과 같은 소스 환경에서 데이터를 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="0254c-145">Exchange 조직이 하나 또는 여러 개인 Active Directory 포리스트(각 Exchange 메일 시스템은 Exchange 2010 이상이어야 함)입니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="0254c-146">단일 IMAP 지원 전자 메일 환경</span><span class="sxs-lookup"><span data-stu-id="0254c-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="0254c-147">G Suite 환경(Gmail, 연락처 및 Outlook 일정만 해당)입니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="0254c-148">다음 표에서는 각 소스 환경에 대한 마이그레이션 세부 정보를 보여 줍니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="0254c-149"><strong>원본 환경</strong></span><span class="sxs-lookup"><span data-stu-id="0254c-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="0254c-150"><strong>마이그레이션 유형</strong></span><span class="sxs-lookup"><span data-stu-id="0254c-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="0254c-151"><strong>마이그레이트 대상</strong></span><span class="sxs-lookup"><span data-stu-id="0254c-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="0254c-152"><strong>마이그레이션되지 않는 사항</strong></span><span class="sxs-lookup"><span data-stu-id="0254c-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="0254c-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="0254c-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="0254c-154">
<strong>참고:</strong> 사내 Exchange 종속성에 대해서는  <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">하이브리드 배포 필수 구성 요소</span>를 참조하십시오.</a></span><span class="sxs-lookup"><span data-stu-id="0254c-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="0254c-155">하이브리드 배포를 사용하는 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="0254c-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="0254c-156">전자 메일</span><span class="sxs-lookup"><span data-stu-id="0254c-156">Emails</span></span></li>
<li><span data-ttu-id="0254c-157">사서함 규칙</span><span class="sxs-lookup"><span data-stu-id="0254c-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="0254c-158">위임</span><span class="sxs-lookup"><span data-stu-id="0254c-158">Delegates</span></span></li>
<li><span data-ttu-id="0254c-159">사서함 연락처</span><span class="sxs-lookup"><span data-stu-id="0254c-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="0254c-160">일정</span><span class="sxs-lookup"><span data-stu-id="0254c-160">Calendar</span></span> </li>
<li> <span data-ttu-id="0254c-161">작업</span><span class="sxs-lookup"><span data-stu-id="0254c-161">Tasks</span></span> </li>
<li> <span data-ttu-id="0254c-162">권한 관리 전자 메일</span><span class="sxs-lookup"><span data-stu-id="0254c-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="0254c-163">암호화된 전자 메일</span><span class="sxs-lookup"><span data-stu-id="0254c-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="0254c-164">서명</span><span class="sxs-lookup"><span data-stu-id="0254c-164">Signatures</span></span> </li>
<li> <span data-ttu-id="0254c-165">사용자 사서함과 함께 마이그레이션된 개인 보관 파일</span><span class="sxs-lookup"><span data-stu-id="0254c-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="0254c-166">복구 가능한 항목</span><span class="sxs-lookup"><span data-stu-id="0254c-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="0254c-167">공용 폴더</span><span class="sxs-lookup"><span data-stu-id="0254c-167">Public folders</span></span> </li>
<li> <span data-ttu-id="0254c-168">메시지 크기 제한을 초과하는 모든 전자 메일</span><span class="sxs-lookup"><span data-stu-id="0254c-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="0254c-169">저널링 보관 또는 모든 타사 보관 솔루션</span><span class="sxs-lookup"><span data-stu-id="0254c-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="0254c-170">차단되거나 비활성 상태인 사용자</span><span class="sxs-lookup"><span data-stu-id="0254c-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="0254c-171">PST(Personal Storage Table) 파일의 보관 데이터</span><span class="sxs-lookup"><span data-stu-id="0254c-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="0254c-172">손상된 항목</span><span class="sxs-lookup"><span data-stu-id="0254c-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="0254c-173">비활성 사서함</span><span class="sxs-lookup"><span data-stu-id="0254c-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0254c-174"><strong>G 제품군 환경(Gmail, 연락처 및 캘린더만)</strong></span><span class="sxs-lookup"><span data-stu-id="0254c-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="0254c-175">
<strong>참고:</strong> G Suite 환경이 <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration"> G Suite 마이그레이션 수행</a>에 설명된 필수 구성 요소를 충족해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="0254c-176">단독형 또는 미리 구성</span><span class="sxs-lookup"><span data-stu-id="0254c-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="0254c-177">전자 메일</span><span class="sxs-lookup"><span data-stu-id="0254c-177">Emails</span></span> </li>
<li> <span data-ttu-id="0254c-178">사서함 연락처(연락처당 최대 3개의 전자 메일 주소가 마이그레이션됨)</span><span class="sxs-lookup"><span data-stu-id="0254c-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="0254c-179">일정</span><span class="sxs-lookup"><span data-stu-id="0254c-179">Calendar</span></span> </li>
<li> <span data-ttu-id="0254c-180">레이블</span><span class="sxs-lookup"><span data-stu-id="0254c-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="0254c-181">규칙</span><span class="sxs-lookup"><span data-stu-id="0254c-181">Rules</span></span> </li>
<li> <span data-ttu-id="0254c-182">위임</span><span class="sxs-lookup"><span data-stu-id="0254c-182">Delegates</span></span> </li>
<li> <span data-ttu-id="0254c-183">서명</span><span class="sxs-lookup"><span data-stu-id="0254c-183">Signatures</span></span> </li>
<li> <span data-ttu-id="0254c-184">작업</span><span class="sxs-lookup"><span data-stu-id="0254c-184">Tasks</span></span> </li>
<li> <span data-ttu-id="0254c-185">메시지 크기 제한을 초과하는 모든 전자 메일 또는 첨부 파일</span><span class="sxs-lookup"><span data-stu-id="0254c-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="0254c-186">차단되거나 비활성 상태인 사용자</span><span class="sxs-lookup"><span data-stu-id="0254c-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="0254c-187">PST 파일 또는 모든 타사 보관 솔루션(예: Google Vault)의 보관 데이터</span><span class="sxs-lookup"><span data-stu-id="0254c-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="0254c-188">권한 관리 또는 암호화된 전자 메일</span><span class="sxs-lookup"><span data-stu-id="0254c-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="0254c-189">손상된 항목</span><span class="sxs-lookup"><span data-stu-id="0254c-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="0254c-190">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="0254c-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="0254c-191">Google Groups</span><span class="sxs-lookup"><span data-stu-id="0254c-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="0254c-192">리소스 사서함</span><span class="sxs-lookup"><span data-stu-id="0254c-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="0254c-193">비활성 사서함</span><span class="sxs-lookup"><span data-stu-id="0254c-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="0254c-194">휴가 설정 및 자동 회신 설정</span><span class="sxs-lookup"><span data-stu-id="0254c-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="0254c-195">공유 일정, 클라우드 첨부 파일, Google Hangout 링크, 이벤트 색상</span><span class="sxs-lookup"><span data-stu-id="0254c-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="0254c-196">\*\*라벨로 저장된 행아웃 대화를 마이그레이트합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0254c-197"><strong>IMAP4 원본(Domino, GroupWise 또는 Zimbra 등)</strong></span><span class="sxs-lookup"><span data-stu-id="0254c-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="0254c-198">기본 IMAP4 도구를 사용한 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="0254c-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="0254c-199">전자 메일</span><span class="sxs-lookup"><span data-stu-id="0254c-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="0254c-200">규칙</span><span class="sxs-lookup"><span data-stu-id="0254c-200">Rules</span></span> </li>
<li> <span data-ttu-id="0254c-201">위임</span><span class="sxs-lookup"><span data-stu-id="0254c-201">Delegates</span></span> </li>
<li> <span data-ttu-id="0254c-202">메일 그룹</span><span class="sxs-lookup"><span data-stu-id="0254c-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="0254c-203">외부 연락처</span><span class="sxs-lookup"><span data-stu-id="0254c-203">External contacts</span></span> </li>
<li> <span data-ttu-id="0254c-204">메일을 사용하는 사용자</span><span class="sxs-lookup"><span data-stu-id="0254c-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="0254c-205">차단되거나 비활성 상태인 사용자</span><span class="sxs-lookup"><span data-stu-id="0254c-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="0254c-206">사서함 연락처</span><span class="sxs-lookup"><span data-stu-id="0254c-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="0254c-207">일정</span><span class="sxs-lookup"><span data-stu-id="0254c-207">Calendar</span></span> </li>
<li> <span data-ttu-id="0254c-208">서명</span><span class="sxs-lookup"><span data-stu-id="0254c-208">Signatures</span></span> </li>
<li> <span data-ttu-id="0254c-209">작업</span><span class="sxs-lookup"><span data-stu-id="0254c-209">Tasks</span></span> </li>
<li> <span data-ttu-id="0254c-210">메시지 크기 제한을 초과하는 모든 전자 메일</span><span class="sxs-lookup"><span data-stu-id="0254c-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="0254c-211">보관 데이터</span><span class="sxs-lookup"><span data-stu-id="0254c-211">Archive data</span></span> </li>
<li> <span data-ttu-id="0254c-212">암호화된 전자 메일</span><span class="sxs-lookup"><span data-stu-id="0254c-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="0254c-213">손상된 항목</span><span class="sxs-lookup"><span data-stu-id="0254c-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="0254c-214">비활성 사서함</span><span class="sxs-lookup"><span data-stu-id="0254c-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="0254c-215">FastTrack 책임</span><span class="sxs-lookup"><span data-stu-id="0254c-215">FastTrack responsibilities</span></span>

<span data-ttu-id="0254c-216">Microsoft의 FastTrack 전문가는 마이그레이션 프로젝트 중에 표준 작업을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="0254c-217">자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="0254c-218">또한 Microsoft의 FastTrack 전문가는 Exchange 마이그레이션과 관련된 다음과 같은 활동을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="0254c-219">해당하는 경우 원본 환경과 Exchange 온라인 간에 SMTP 메일 라우팅 공존을 사용하도록 설정하는 데 도움이 되는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="0254c-220">귀하의 책임</span><span class="sxs-lookup"><span data-stu-id="0254c-220">Your responsibilities</span></span>

<span data-ttu-id="0254c-221">마이그레이션 프로젝트 중에 표준 작업을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="0254c-222">자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="0254c-223">Exchange 마이그레이션과 관련된 다음 작업도 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="0254c-224">Exchange Online용 FastTrack 코어 온보딩을 완료합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="0254c-225">직접 온보드 탑재를 수행한 경우 필요한 검사 및 필수 구성 요소를 통과해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="0254c-226">자세한 내용은 [제품 및 기능](products-and-capabilities.md)을(를) 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="0254c-227">Office 365 지침에 따라 적절한 수준의 클라이언트 소프트웨어를 설치합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="0254c-228">자세한 내용은 [최신 작업 공간](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="0254c-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="0254c-229">사내 Exchange 환경에서 마이그레이션하려는 경우 특정 요구 사항을 충족합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="0254c-230">자세한 내용은 [하이브리드 배포 필수 구성 요소](https://go.microsoft.com/fwlink/?LinkId=787528)를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="0254c-231">해당되는 경우 각 소스 환경이 최신 서비스 팩(SP) 및 롤업(RU)/누적 업데이트(CU) 레벨에 있는지 확인합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="0254c-232">해당되는 경우 원본 환경과 Exchange 온라인 간의 SMTP 메일 라우팅 공존을 구성하고 검증합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="0254c-233">원본 사서함 크기가 대상 사서함 할당량을 초과하지 않도록 합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="0254c-234">원본 플랫폼에 따라 소스 데이터를 대상 사서함 할당량의 85%로 제한해야 할 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="0254c-235">필요한 경우 클라이언트 측 데이터를 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="0254c-236">여기에는 로컬 주소록, 로컬 PST 파일의 데이터, Outlook 규칙 및 로컬 Outlook 설정이 포함되지만 이에 국한되지는 않습니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="0254c-237">최종 사용자가 클라이언트 측 마이그레이션 문제를 해결할 수 있도록 지원합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="0254c-238">SharePoint Online으로 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="0254c-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="0254c-239">FastTrack을 사용하여 SharePoint Online으로 파일을 마이그레이션하도록 선택하면 마이그레이션 안내 및 데이터 마이그레이션 서비스를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="0254c-240">Microsoft는 마이그레이션 계획, 소스 환경 및 SharePoint 온라인 구성, 데이터 마이그레이션 서비스를 활용하여 파일을 마이그레이션하는 데 도움이 되는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="0254c-241">마이그레이션 이벤트를 생성하고 예약합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-241">You create and schedule your migration events.</span></span> <span data-ttu-id="0254c-242">스케줄에 따라 마이그레이션 이벤트를 시작하고 진행률을 모니터링하며 상태 보고서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="0254c-243">마이그레이션 이벤트가 완료되면 적절한 예약 소스 및 적합한 소스 소스의 파일이 SharePoint 온라인으로 마이그레이션될 것으로 예상할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="0254c-244">고려 사항</span><span class="sxs-lookup"><span data-stu-id="0254c-244">Considerations</span></span>

  - <span data-ttu-id="0254c-245">모든 마이그레이션은 SharePoint 온라인 할당량을 따릅니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="0254c-246">자세한 내용은 [<span class="underline">SharePoint 온라인 및 OneDrive for Business: 소프트웨어 경계 및 제한</span>](https://go.microsoft.com/fwlink/?LinkId=698855)을(를) 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="0254c-247">전체 마이그레이션 양을 사용 권한이 있는 전체 SharePoint 온라인 스토리지 할당량의 75%로 제한하는 것이 좋습니다(별도로 구입한 추가 스토리지 포함).</span><span class="sxs-lookup"><span data-stu-id="0254c-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="0254c-248">소스 환경 세부 정보</span><span class="sxs-lookup"><span data-stu-id="0254c-248">Source environment details</span></span>

<span data-ttu-id="0254c-249">Microsoft의 데이터 마이그레이션 서비스는 다음과 같은 소스 환경에서 데이터를 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="0254c-250">파일 공유(SMB 2.0 이상 지원 장치에서 SMB(서버 메시지 블록) 파일 공유).</span><span class="sxs-lookup"><span data-stu-id="0254c-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="0254c-251">단일 G 제품군 환경(Google Drive만 해당)</span><span class="sxs-lookup"><span data-stu-id="0254c-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="0254c-252">Box(Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="0254c-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="0254c-253">Teams용 Dropbox (표준 및 고급)</span><span class="sxs-lookup"><span data-stu-id="0254c-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="0254c-254">다음 표에서는 각 소스 환경에 대한 마이그레이션 세부 정보를 보여 줍니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="0254c-255"><strong>원본 환경</strong></span><span class="sxs-lookup"><span data-stu-id="0254c-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="0254c-256"><strong>마이그레이션 유형</strong></span><span class="sxs-lookup"><span data-stu-id="0254c-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="0254c-257"><strong>마이그레이트 대상</strong></span><span class="sxs-lookup"><span data-stu-id="0254c-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="0254c-258"><strong>마이그레이션되지 않는 사항</strong></span><span class="sxs-lookup"><span data-stu-id="0254c-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="0254c-259"><strong>SMB 2.0 이상을 지원하는 모든 파일 공유 장치</strong></span><span class="sxs-lookup"><span data-stu-id="0254c-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="0254c-260">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="0254c-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="0254c-261">문서</span><span class="sxs-lookup"><span data-stu-id="0254c-261">Documents</span></span> </li>
<li> <span data-ttu-id="0254c-262">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="0254c-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="0254c-263">사용자 수준 파일 및 폴더 권한\*</span><span class="sxs-lookup"><span data-stu-id="0254c-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="0254c-264">그룹 수준 파일 및 폴더 권한\*</span><span class="sxs-lookup"><span data-stu-id="0254c-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="0254c-265">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="0254c-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="0254c-266">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="0254c-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="0254c-267">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="0254c-267">Created date</span></span> </li>
<li> <span data-ttu-id="0254c-268">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="0254c-268">Modified date</span></span> </li>
<li> <span data-ttu-id="0254c-269">만든 사람</span><span class="sxs-lookup"><span data-stu-id="0254c-269">Created by</span></span> </li>
<li> <span data-ttu-id="0254c-270">마지막 수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="0254c-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="0254c-271">\* 디렉터리 동기화 구성이 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="0254c-272">Windows 파일 탐색기에 표시된 NTFS 권한만 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="0254c-273">파일 공유 장치에서 직접 관리되는 사용 권한은 마이그레이션되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="0254c-274">데이터가 SMB 2.0 장치에 저장된 경우 SMB 프로토콜에 의해 노출된 NTFS 동등 사용 권한이 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="0254c-275">소유권 기록 및 이전 버전</span><span class="sxs-lookup"><span data-stu-id="0254c-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="0254c-276">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="0254c-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="0254c-277">이전 버전</span><span class="sxs-lookup"><span data-stu-id="0254c-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="0254c-278">Windows 파일 및 폴더 특성(예: 읽기 전용 및 숨김)</span><span class="sxs-lookup"><span data-stu-id="0254c-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="0254c-279">Windows가 아닌 NTFS(New Technology File System) 및 NTFS 고급 사용 권한 및 특수 설정:</span><span class="sxs-lookup"><span data-stu-id="0254c-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="0254c-280">명시적 거부 사용 권한(마이그레이션 후 제거됨, 콘텐츠는 병렬 사용 권한 또는 상위 폴더의 사용 권한에 따름)</span><span class="sxs-lookup"><span data-stu-id="0254c-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="0254c-281">NTFS 감사 구성</span><span class="sxs-lookup"><span data-stu-id="0254c-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="0254c-282">FCI(파일 분류 인프라)에 의해 제공되는 추가 파일 메타데이터</span><span class="sxs-lookup"><span data-stu-id="0254c-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="0254c-283">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="0254c-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="0254c-284">숨겨진 공유</span><span class="sxs-lookup"><span data-stu-id="0254c-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="0254c-285">공유(예: 공유 수준에 부여된 사용 권한)</span><span class="sxs-lookup"><span data-stu-id="0254c-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="0254c-286">파일 또는 폴더가 현재 <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint 온라인 제한 및 제한</span></a> 를 초과합니다. </span><span class="sxs-lookup"><span data-stu-id="0254c-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0254c-287"><strong>단일 G 제품군 환경(Google Drive만 해당)</strong></span><span class="sxs-lookup"><span data-stu-id="0254c-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="0254c-288">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="0254c-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="0254c-289">Google 문서, 스프레드시트 및 슬라이드(파일이 동등한 Office 형식으로 변환됨 / 10MB 초과하는 파일 포함)</span><span class="sxs-lookup"><span data-stu-id="0254c-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="0254c-290">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="0254c-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="0254c-291">사용자 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="0254c-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0254c-292">그룹 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="0254c-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0254c-293">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="0254c-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="0254c-294">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="0254c-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="0254c-295">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="0254c-295">Created date</span></span> </li>
<li> <span data-ttu-id="0254c-296">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="0254c-296">Modified date</span></span> </li>
<li> <span data-ttu-id="0254c-297">만든 사람</span><span class="sxs-lookup"><span data-stu-id="0254c-297">Created by</span></span> </li>
<li> <span data-ttu-id="0254c-298">마지막 수정 날짜</span><span class="sxs-lookup"><span data-stu-id="0254c-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="0254c-299">공유 드라이브(폴더 및 파일)</span><span class="sxs-lookup"><span data-stu-id="0254c-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="0254c-300">Google Drive 계정이 소유한 공유 콘텐츠를 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="0254c-301">소유권 기록, 이전 버전 및 메모</span><span class="sxs-lookup"><span data-stu-id="0254c-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="0254c-302">파일 및 폴더 설명, 폴더 색상</span><span class="sxs-lookup"><span data-stu-id="0254c-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="0254c-303">사용자 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="0254c-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="0254c-304">그룹 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="0254c-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="0254c-305">고급 메타 데이터</span><span class="sxs-lookup"><span data-stu-id="0254c-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="0254c-306">파일 잠금 특성</span><span class="sxs-lookup"><span data-stu-id="0254c-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="0254c-307">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="0254c-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="0254c-308">휴지통 항목</span><span class="sxs-lookup"><span data-stu-id="0254c-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="0254c-309">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="0254c-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="0254c-310">차단되거나 비활성 상태인 사용자</span><span class="sxs-lookup"><span data-stu-id="0254c-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="0254c-311">Google Photos. Forms, Maps 및 기타 연결된 앱</span><span class="sxs-lookup"><span data-stu-id="0254c-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="0254c-312">Google 드로잉</span><span class="sxs-lookup"><span data-stu-id="0254c-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="0254c-313">조직 외부로 공유된 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="0254c-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="0254c-314">마이그레이션할 Google Drive 계정에서 소유하지 않은 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="0254c-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="0254c-315">외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>): Google Drive Admin 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="0254c-316">최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="0254c-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="0254c-317">공유 드라이브 구성원 권한(<strong>참고</strong>): Google Drive Admin 보고서를 사용하여 공유 드라이브 구성원 자격을 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="0254c-318">마이그레이션하기 전에 최종 사용자에게 대상에서 이러한 구성원 자격 설정을 구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="0254c-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="0254c-319">파일 또는 폴더가 현재 <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint 온라인 제한 및 제한</span></a> 를 초과합니다. </span><span class="sxs-lookup"><span data-stu-id="0254c-319">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0254c-320"><strong>Box(Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="0254c-320"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="0254c-321">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="0254c-321">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="0254c-322">문서</span><span class="sxs-lookup"><span data-stu-id="0254c-322">Documents</span></span> </li>
<li> <span data-ttu-id="0254c-323">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="0254c-323">File and folder structure</span></span> </li>
<li> <span data-ttu-id="0254c-324">사용자 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="0254c-324">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0254c-325">그룹 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="0254c-325">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0254c-326">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="0254c-326">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="0254c-327">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="0254c-327">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="0254c-328">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="0254c-328">Created date</span></span> </li>
<li> <span data-ttu-id="0254c-329">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="0254c-329">Modified date</span></span> </li>
<li> <span data-ttu-id="0254c-330">만든 사람</span><span class="sxs-lookup"><span data-stu-id="0254c-330">Created by</span></span> </li>
<li> <span data-ttu-id="0254c-331">마지막 수정 날짜</span><span class="sxs-lookup"><span data-stu-id="0254c-331">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="0254c-332">Box 계정이 소유한 공유 콘텐츠가 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-332">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="0254c-333">소유권 기록, 이전 버전 및 메모</span><span class="sxs-lookup"><span data-stu-id="0254c-333">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="0254c-334">파일 및 폴더 설명</span><span class="sxs-lookup"><span data-stu-id="0254c-334">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="0254c-335">사용자 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="0254c-335">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="0254c-336">그룹 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="0254c-336">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="0254c-337">Box 태그와 고급 메타데이터</span><span class="sxs-lookup"><span data-stu-id="0254c-337">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="0254c-338">파일 잠금 특성</span><span class="sxs-lookup"><span data-stu-id="0254c-338">File lock attributes</span></span> </li>
<li> <span data-ttu-id="0254c-339">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="0254c-339">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="0254c-340">휴지통 항목</span><span class="sxs-lookup"><span data-stu-id="0254c-340">Trashed items</span></span> </li>
<li> <span data-ttu-id="0254c-341">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="0254c-341">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="0254c-342">차단되거나 비활성 상태인 사용자</span><span class="sxs-lookup"><span data-stu-id="0254c-342">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="0254c-343">Box 앱, 책갈피, 즐겨찾기 및 워크플로</span><span class="sxs-lookup"><span data-stu-id="0254c-343">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="0254c-344">마이그레이션된 상자 계정에서 소유하지 않은 콘텐츠입니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-344">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="0254c-345">외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>): Box 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-345">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="0254c-346">최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="0254c-346">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="0254c-347">파일 또는 폴더가 현재 <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint 온라인 제한 및 제한</span></a> 를 초과합니다. </span><span class="sxs-lookup"><span data-stu-id="0254c-347">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0254c-348"><strong>Teams용 Dropbox(표준 및 고급)</strong></span><span class="sxs-lookup"><span data-stu-id="0254c-348"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="0254c-349">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="0254c-349">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="0254c-350">문서</span><span class="sxs-lookup"><span data-stu-id="0254c-350">Documents</span></span> </li>
<li> <span data-ttu-id="0254c-351">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="0254c-351">File and folder structure</span></span> </li>
<li> <span data-ttu-id="0254c-352">사용자 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="0254c-352">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0254c-353">그룹 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="0254c-353">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0254c-354">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="0254c-354">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="0254c-355">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="0254c-355">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="0254c-356">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="0254c-356">Created date</span></span> </li>
<li> <span data-ttu-id="0254c-357">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="0254c-357">Modified date</span></span> </li>
<li> <span data-ttu-id="0254c-358">만든 사람</span><span class="sxs-lookup"><span data-stu-id="0254c-358">Created by</span></span> </li>
<li> <span data-ttu-id="0254c-359">마지막 수정 날짜</span><span class="sxs-lookup"><span data-stu-id="0254c-359">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="0254c-360">공유 팀 폴더 및 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="0254c-360">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="0254c-361">Dropbox 계정이 소유한 공유 콘텐츠가 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-361">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="0254c-362">소유권 기록, 이전 버전 및 메모</span><span class="sxs-lookup"><span data-stu-id="0254c-362">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="0254c-363">파일 및 폴더 설명</span><span class="sxs-lookup"><span data-stu-id="0254c-363">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="0254c-364">사용자 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="0254c-364">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="0254c-365">그룹 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="0254c-365">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="0254c-366">고급 메타 데이터</span><span class="sxs-lookup"><span data-stu-id="0254c-366">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="0254c-367">파일 잠금 특성</span><span class="sxs-lookup"><span data-stu-id="0254c-367">File lock attributes</span></span> </li>
<li> <span data-ttu-id="0254c-368">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="0254c-368">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="0254c-369">휴지통 항목</span><span class="sxs-lookup"><span data-stu-id="0254c-369">Trashed items</span></span> </li>
<li> <span data-ttu-id="0254c-370">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="0254c-370">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="0254c-371">연결 해제된 Dropbox 폴더</span><span class="sxs-lookup"><span data-stu-id="0254c-371">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="0254c-372">삭제되거나 연결이 끊어진 사용자</span><span class="sxs-lookup"><span data-stu-id="0254c-372">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="0254c-373">Dropbox Paper, Showcases 및 Spaces</span><span class="sxs-lookup"><span data-stu-id="0254c-373">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="0254c-374">Dropbox 앱 및 즐겨찾기(핀/별)</span><span class="sxs-lookup"><span data-stu-id="0254c-374">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="0254c-375">마이그레이션된 Dropbox 계정이 소유하지 않은 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="0254c-375">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="0254c-376">외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>: Dropbox 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-376">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="0254c-377">최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="0254c-377">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="0254c-378">파일 또는 폴더가 현재 <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint 온라인 제한 및 제한</span></a> 를 초과합니다. </span><span class="sxs-lookup"><span data-stu-id="0254c-378">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="0254c-379">FastTrack 책임</span><span class="sxs-lookup"><span data-stu-id="0254c-379">FastTrack responsibilities</span></span>

<span data-ttu-id="0254c-380">Microsoft의 FastTrack 전문가는 마이그레이션 프로젝트 중에 표준 작업을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-380">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="0254c-381">자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-381">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="0254c-382">귀하의 책임</span><span class="sxs-lookup"><span data-stu-id="0254c-382">Your responsibilities</span></span>

<span data-ttu-id="0254c-383">마이그레이션 프로젝트 중에 표준 작업을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-383">You perform standard activities during the migration project.</span></span> <span data-ttu-id="0254c-384">자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="0254c-385">또한 SharePoint 온라인 마이그레이션과 관련된 다음 작업도 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-385">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="0254c-386">모든 SharePoint 팀 사이트를 마이그레이션 이벤트의 대상으로 프로비저닝합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-386">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="0254c-387">비즈니스용 OneDrive로 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="0254c-387">Migration to OneDrive for Business</span></span>

<span data-ttu-id="0254c-388">FastTrack을 사용하여 파일을 비즈니스용 OneDrive로 마이그레이션하도록 선택하면 마이그레이션 안내 및 데이터 마이그레이션 서비스를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-388">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="0254c-389">Microsoft는 마이그레이션 계획, 소스 환경 및 비즈니스용 OneDrive 구성, 데이터 마이그레이션 서비스를 활용하여 파일을 마이그레이션하는 데 도움이 되는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-389">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="0254c-390">마이그레이션 이벤트를 생성하고 예약합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-390">You create and schedule your migration events.</span></span> <span data-ttu-id="0254c-391">스케줄에 따라 마이그레이션 이벤트를 시작하고 진행률을 모니터링하며 상태 보고서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-391">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="0254c-392">마이그레이션 이벤트가 완료되면 적절한 소스 환경의 적절한 예약 소스 및 적합한 원본의 파일이 비즈니스용 OneDrive로 마이그레이션될 것으로 예상할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-392">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="0254c-393">고려 사항</span><span class="sxs-lookup"><span data-stu-id="0254c-393">Considerations</span></span>

  - <span data-ttu-id="0254c-394">모든 마이그레이션에는 비즈니스용 OneDrive 할당량이 적용됩니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-394">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="0254c-395">자세한 내용은 [<span class="underline">SharePoint Online 및 비즈니스용 OneDrive: 소프트웨어 경계 및 제한</span>](https://go.microsoft.com/fwlink/?LinkId=698855)을 참조하시기 바랍니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-395">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="0254c-396">마이그레이션하는 전체 데이터 양을 권한이 부여된 전체 SharePoint 온라인 스토리지 할당량의 75%로 제한하는 것이 좋습니다(별도로 구입한 추가 스토리지 포함).</span><span class="sxs-lookup"><span data-stu-id="0254c-396">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="0254c-397">FastTrack은 활성 비즈니스용 OneDrive 드라이브로만 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-397">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="0254c-398">소스 환경 세부 정보</span><span class="sxs-lookup"><span data-stu-id="0254c-398">Source environment details</span></span>

<span data-ttu-id="0254c-399">Microsoft의 데이터 마이그레이션 서비스는 다음과 같은 소스 환경에서 데이터를 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-399">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="0254c-400">파일 공유(SMB 2.0 이상 지원 장치에서 SMB 파일 공유)</span><span class="sxs-lookup"><span data-stu-id="0254c-400">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="0254c-401">단일 G 제품군 환경(Google Drive만 해당)</span><span class="sxs-lookup"><span data-stu-id="0254c-401">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="0254c-402">Box(Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="0254c-402">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="0254c-403">Teams용 Dropbox (표준 및 고급)</span><span class="sxs-lookup"><span data-stu-id="0254c-403">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="0254c-404">다음 표에서는 각 소스 환경에 대한 마이그레이션 세부 정보를 보여 줍니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-404">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="0254c-405"><strong>원본 환경</strong></span><span class="sxs-lookup"><span data-stu-id="0254c-405"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="0254c-406"><strong>마이그레이션 유형</strong></span><span class="sxs-lookup"><span data-stu-id="0254c-406"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="0254c-407"><strong>마이그레이트 대상</strong></span><span class="sxs-lookup"><span data-stu-id="0254c-407"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="0254c-408"><strong>마이그레이션되지 않는 사항</strong></span><span class="sxs-lookup"><span data-stu-id="0254c-408"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="0254c-409"><strong>SMB 2.0 이상을 지원하는 모든 파일 공유 장치</strong></span><span class="sxs-lookup"><span data-stu-id="0254c-409"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="0254c-410">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="0254c-410">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="0254c-411">문서</span><span class="sxs-lookup"><span data-stu-id="0254c-411">Documents</span></span> </li>
<li> <span data-ttu-id="0254c-412">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="0254c-412">File and folder structure</span></span> </li>
<li> <span data-ttu-id="0254c-413">사용자 수준 파일 및 폴더 권한\*</span><span class="sxs-lookup"><span data-stu-id="0254c-413">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="0254c-414">그룹 수준 파일 및 폴더 권한\*</span><span class="sxs-lookup"><span data-stu-id="0254c-414">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="0254c-415">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="0254c-415">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="0254c-416">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="0254c-416">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="0254c-417">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="0254c-417">Created date</span></span> </li>
<li> <span data-ttu-id="0254c-418">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="0254c-418">Modified date</span></span> </li>
<li> <span data-ttu-id="0254c-419">만든 사람</span><span class="sxs-lookup"><span data-stu-id="0254c-419">Created by</span></span> </li>
<li> <span data-ttu-id="0254c-420">마지막 수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="0254c-420">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="0254c-421">\* 디렉터리 동기화 구성이 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-421">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="0254c-422">Windows 파일 탐색기에 표시된 NTFS 권한만 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-422">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="0254c-423">파일 공유 장치에서 직접 관리되는 사용 권한은 마이그레이션되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-423">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="0254c-424">데이터가 SMB 2.0 장치에 저장된 경우 SMB 프로토콜에 의해 노출된 NTFS 동등 사용 권한이 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-424">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="0254c-425">소유권 기록 및 이전 버전</span><span class="sxs-lookup"><span data-stu-id="0254c-425">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="0254c-426">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="0254c-426">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="0254c-427">이전 버전</span><span class="sxs-lookup"><span data-stu-id="0254c-427">Previous versions</span></span> </li>
<li> <span data-ttu-id="0254c-428">Windows 파일 및 폴더 특성(예: 읽기 전용 및 숨김)</span><span class="sxs-lookup"><span data-stu-id="0254c-428">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="0254c-429">Windows가 아닌 NTFS(New Technology File System) 및 NTFS 고급 사용 권한 및 특수 설정:</span><span class="sxs-lookup"><span data-stu-id="0254c-429">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="0254c-430">명시적 거부 사용 권한(마이그레이션 후 제거됨, 콘텐츠는 병렬 사용 권한 또는 상위 폴더의 사용 권한에 따름)</span><span class="sxs-lookup"><span data-stu-id="0254c-430">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="0254c-431">NTFS 감사 구성</span><span class="sxs-lookup"><span data-stu-id="0254c-431">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="0254c-432">FCI(파일 분류 인프라)에 의해 제공되는 추가 파일 메타데이터</span><span class="sxs-lookup"><span data-stu-id="0254c-432">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="0254c-433">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="0254c-433">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="0254c-434">숨겨진 공유</span><span class="sxs-lookup"><span data-stu-id="0254c-434">Hidden shares</span></span> </li>
<li> <span data-ttu-id="0254c-435">공유(예: 공유 수준에 부여된 사용 권한)</span><span class="sxs-lookup"><span data-stu-id="0254c-435">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="0254c-436">파일 또는 폴더가 현재 <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint 온라인 제한 및 제한</span></a> 를 초과합니다. </span><span class="sxs-lookup"><span data-stu-id="0254c-436">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0254c-437"><strong>단일 G 제품군 환경(Google Drive만 해당)</strong></span><span class="sxs-lookup"><span data-stu-id="0254c-437"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="0254c-438">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="0254c-438">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="0254c-439">Google 문서, 스프레드시트 및 슬라이드(파일이 동등한 Office 형식으로 변환됨 / 10MB 초과하는 파일 포함)</span><span class="sxs-lookup"><span data-stu-id="0254c-439">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="0254c-440">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="0254c-440">File and folder structure</span></span> </li>
<li> <span data-ttu-id="0254c-441">사용자 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="0254c-441">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0254c-442">그룹 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="0254c-442">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0254c-443">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="0254c-443">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="0254c-444">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="0254c-444">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="0254c-445">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="0254c-445">Created date</span></span> </li>
<li> <span data-ttu-id="0254c-446">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="0254c-446">Modified date</span></span> </li>
<li> <span data-ttu-id="0254c-447">만든 사람</span><span class="sxs-lookup"><span data-stu-id="0254c-447">Created by</span></span> </li>
<li> <span data-ttu-id="0254c-448">마지막 수정 날짜</span><span class="sxs-lookup"><span data-stu-id="0254c-448">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="0254c-449">공유 드라이브(폴더 및 파일)</span><span class="sxs-lookup"><span data-stu-id="0254c-449">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="0254c-450">Google Drive 계정이 소유한 공유 콘텐츠를 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-450">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="0254c-451">소유권 기록, 이전 버전 및 메모</span><span class="sxs-lookup"><span data-stu-id="0254c-451">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="0254c-452">파일 및 폴더 설명, 폴더 색상</span><span class="sxs-lookup"><span data-stu-id="0254c-452">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="0254c-453">사용자 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="0254c-453">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="0254c-454">그룹 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="0254c-454">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="0254c-455">고급 메타 데이터</span><span class="sxs-lookup"><span data-stu-id="0254c-455">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="0254c-456">파일 잠금 특성</span><span class="sxs-lookup"><span data-stu-id="0254c-456">File lock attributes</span></span> </li>
<li> <span data-ttu-id="0254c-457">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="0254c-457">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="0254c-458">휴지통 항목</span><span class="sxs-lookup"><span data-stu-id="0254c-458">Trashed items</span></span> </li>
<li> <span data-ttu-id="0254c-459">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="0254c-459">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="0254c-460">차단되거나 비활성 상태인 사용자</span><span class="sxs-lookup"><span data-stu-id="0254c-460">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="0254c-461">Google Photos. Forms, Maps 및 기타 연결된 앱</span><span class="sxs-lookup"><span data-stu-id="0254c-461">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="0254c-462">Google 드로잉</span><span class="sxs-lookup"><span data-stu-id="0254c-462">Google Drawings</span></span> </li>
<li> <span data-ttu-id="0254c-463">조직 외부로 공유된 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="0254c-463">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="0254c-464">마이그레이션할 Google Drive 계정에서 소유하지 않은 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="0254c-464">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="0254c-465">외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>): Google Drive Admin 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-465">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="0254c-466">최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="0254c-466">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="0254c-467">공유 드라이브 구성원 권한(<strong>참고</strong>): Google Drive Admin 보고서를 사용하여 공유 드라이브 구성원 자격을 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-467">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="0254c-468">마이그레이션하기 전에 최종 사용자에게 대상에서 이러한 구성원 자격 설정을 구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="0254c-468">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="0254c-469">파일 또는 폴더가 현재 <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint 온라인 제한 및 제한</span></a> 를 초과합니다. </span><span class="sxs-lookup"><span data-stu-id="0254c-469">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0254c-470"><strong>Box(Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="0254c-470"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="0254c-471">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="0254c-471">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="0254c-472">문서</span><span class="sxs-lookup"><span data-stu-id="0254c-472">Documents</span></span> </li>
<li> <span data-ttu-id="0254c-473">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="0254c-473">File and folder structure</span></span> </li>
<li> <span data-ttu-id="0254c-474">사용자 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="0254c-474">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0254c-475">그룹 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="0254c-475">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0254c-476">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="0254c-476">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="0254c-477">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="0254c-477">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="0254c-478">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="0254c-478">Created date</span></span> </li>
<li> <span data-ttu-id="0254c-479">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="0254c-479">Modified date</span></span> </li>
<li> <span data-ttu-id="0254c-480">만든 사람</span><span class="sxs-lookup"><span data-stu-id="0254c-480">Created by</span></span> </li>
<li> <span data-ttu-id="0254c-481">마지막 수정 날짜</span><span class="sxs-lookup"><span data-stu-id="0254c-481">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="0254c-482">Box 계정이 소유한 공유 콘텐츠가 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-482">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="0254c-483">소유권 기록, 이전 버전 및 메모</span><span class="sxs-lookup"><span data-stu-id="0254c-483">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="0254c-484">파일 및 폴더 설명</span><span class="sxs-lookup"><span data-stu-id="0254c-484">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="0254c-485">사용자 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="0254c-485">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="0254c-486">그룹 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="0254c-486">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="0254c-487">Box 태그와 고급 메타데이터</span><span class="sxs-lookup"><span data-stu-id="0254c-487">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="0254c-488">파일 잠금 특성</span><span class="sxs-lookup"><span data-stu-id="0254c-488">File lock attributes</span></span> </li>
<li> <span data-ttu-id="0254c-489">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="0254c-489">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="0254c-490">휴지통 항목</span><span class="sxs-lookup"><span data-stu-id="0254c-490">Trashed items</span></span> </li>
<li> <span data-ttu-id="0254c-491">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="0254c-491">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="0254c-492">차단되거나 비활성 상태인 사용자</span><span class="sxs-lookup"><span data-stu-id="0254c-492">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="0254c-493">Box 앱, 책갈피, 즐겨찾기 및 워크플로</span><span class="sxs-lookup"><span data-stu-id="0254c-493">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="0254c-494">마이그레이션된 상자 계정에서 소유하지 않은 콘텐츠입니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-494">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="0254c-495">외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>): Box 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-495">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="0254c-496">최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="0254c-496">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="0254c-497">파일 또는 폴더가 현재 <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint 온라인 제한 및 제한</span></a> 를 초과합니다. </span><span class="sxs-lookup"><span data-stu-id="0254c-497">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0254c-498"><strong>Teams용 Dropbox(표준 및 고급)</strong></span><span class="sxs-lookup"><span data-stu-id="0254c-498"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="0254c-499">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="0254c-499">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="0254c-500">문서</span><span class="sxs-lookup"><span data-stu-id="0254c-500">Documents</span></span> </li>
<li> <span data-ttu-id="0254c-501">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="0254c-501">File and folder structure</span></span> </li>
<li> <span data-ttu-id="0254c-502">사용자 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="0254c-502">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0254c-503">그룹 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="0254c-503">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0254c-504">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="0254c-504">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="0254c-505">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="0254c-505">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="0254c-506">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="0254c-506">Created date</span></span> </li>
<li> <span data-ttu-id="0254c-507">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="0254c-507">Modified date</span></span> </li>
<li> <span data-ttu-id="0254c-508">만든 사람</span><span class="sxs-lookup"><span data-stu-id="0254c-508">Created by</span></span> </li>
<li> <span data-ttu-id="0254c-509">마지막 수정 날짜</span><span class="sxs-lookup"><span data-stu-id="0254c-509">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="0254c-510">공유 팀 폴더 및 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="0254c-510">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="0254c-511">Dropbox 계정이 소유한 공유 콘텐츠가 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-511">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="0254c-512">소유권 기록, 이전 버전 및 메모</span><span class="sxs-lookup"><span data-stu-id="0254c-512">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="0254c-513">파일 및 폴더 설명</span><span class="sxs-lookup"><span data-stu-id="0254c-513">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="0254c-514">사용자 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="0254c-514">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="0254c-515">그룹 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="0254c-515">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="0254c-516">고급 메타 데이터</span><span class="sxs-lookup"><span data-stu-id="0254c-516">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="0254c-517">파일 잠금 특성</span><span class="sxs-lookup"><span data-stu-id="0254c-517">File lock attributes</span></span> </li>
<li> <span data-ttu-id="0254c-518">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="0254c-518">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="0254c-519">휴지통 항목</span><span class="sxs-lookup"><span data-stu-id="0254c-519">Trashed items</span></span> </li>
<li> <span data-ttu-id="0254c-520">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="0254c-520">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="0254c-521">연결 해제된 Dropbox 폴더</span><span class="sxs-lookup"><span data-stu-id="0254c-521">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="0254c-522">삭제되거나 연결이 끊어진 사용자</span><span class="sxs-lookup"><span data-stu-id="0254c-522">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="0254c-523">Dropbox Paper, Showcases 및 Spaces</span><span class="sxs-lookup"><span data-stu-id="0254c-523">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="0254c-524">Dropbox 앱 및 즐겨찾기(핀/별)</span><span class="sxs-lookup"><span data-stu-id="0254c-524">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="0254c-525">마이그레이션된 Dropbox 계정이 소유하지 않은 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="0254c-525">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="0254c-526">외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>: Dropbox 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-526">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="0254c-527">최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="0254c-527">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="0254c-528">파일 또는 폴더가 현재 <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint 온라인 제한 및 제한</span></a> 를 초과합니다. </span><span class="sxs-lookup"><span data-stu-id="0254c-528">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="0254c-529">FastTrack 책임</span><span class="sxs-lookup"><span data-stu-id="0254c-529">FastTrack responsibilities</span></span>

<span data-ttu-id="0254c-530">Microsoft의 FastTrack 전문가는 마이그레이션 프로젝트 중에 표준 작업을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-530">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="0254c-531">자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-531">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="0254c-532">귀하의 책임</span><span class="sxs-lookup"><span data-stu-id="0254c-532">Your responsibilities</span></span>

<span data-ttu-id="0254c-533">마이그레이션 프로젝트 중에 표준 작업을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-533">You perform standard activities during the migration project.</span></span> <span data-ttu-id="0254c-534">자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="0254c-535">또한 비즈니스용 OneDrive 마이그레이션과 관련된 다음 작업도 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-535">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="0254c-536">마이그레이션 이벤트의 대상이 되는 비즈니스 사이트를 위해 모든 OneDrive를 프로비저닝합니다.</span><span class="sxs-lookup"><span data-stu-id="0254c-536">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
