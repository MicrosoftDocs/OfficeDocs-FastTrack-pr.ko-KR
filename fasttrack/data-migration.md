---
title: 데이터 마이그레이션
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 10/1/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack은 원본 환경의 메일 및 파일 데이터를 Office 365(Exchange Online, SharePoint Online 및 비즈니스용 OneDrive)로 마이그레이션하는 데 도움이 됩니다. Microsoft가 제공하는 지원 유형은 Office 365 라이선스 수에 따라 다릅니다.
ms.openlocfilehash: a8bb82e5a0409c52fe2603d33a4412182288f24a
ms.sourcegitcommit: c2bf382289217ef12913ef3419e6378716fd411a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/30/2020
ms.locfileid: "48319950"
---
# <a name="data-migration"></a><span data-ttu-id="15105-104">데이터 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="15105-104">Data Migration</span></span>

<span data-ttu-id="15105-105">FastTrack은 원본 환경의 메일 및 파일 데이터를 Office 365(Exchange Online, SharePoint Online 및 비즈니스용 OneDrive)로 마이그레이션하는 데 도움이 됩니다.</span><span class="sxs-lookup"><span data-stu-id="15105-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="15105-106">Microsoft가 제공하는 지원 유형은 Office 365 라이선스 수에 따라 달라집니다.</span><span class="sxs-lookup"><span data-stu-id="15105-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="15105-107">**150-499 라이선스를 보유한 Office 365 테넌트**: FastTrack은 마이그레이션 안내만 제공하며 데이터 마이그레이션을 수행해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="15105-108">셀프 서비스 마이그레이션을 수행하기 위해 무료 도구를 계획하고 사용하는 데 도움이 되는 문서를 안내합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="15105-109">**라이선스가 500개 이상인 Office 365 테넌트**: FastTrack은 마이그레이션 안내 및 데이터 마이그레이션 서비스를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="15105-110">Microsoft는 마이그레이션 계획, 소스 환경 및 Office 365 테넌트 구성, 데이터 마이그레이션 서비스를 활용하여 데이터를 마이그레이션하는 데 도움이 되는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="15105-111">마이그레이션 이벤트를 생성하고 예약합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-111">You create and schedule your migration events.</span></span> <span data-ttu-id="15105-112">스케줄에 따라 마이그레이션 이벤트를 시작하고 진행률을 모니터링하며 상태 보고서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="15105-113">2017년 9월 1일 이전에 상업용 계획을 구입하거나 갱신한 경우 데이터 마이그레이션 서비스를 받으려면 150개의 라이선스만 있으면 됩니다.</span><span class="sxs-lookup"><span data-stu-id="15105-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="15105-114">교육 계획의 경우 유급 직원 및 직원 라이선스만 데이터 마이그레이션 서비스를 받을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="15105-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="15105-115">고려 사항</span><span class="sxs-lookup"><span data-stu-id="15105-115">Considerations</span></span>

  - <span data-ttu-id="15105-116">Office 365로 데이터를 마이그레이션하려면 소스 환경이 특정 기대치를 충족해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="15105-117">Exchange, SharePoint 및 비즈니스용 OneDrive에 대한 소스 환경에 대한 자세한 내용은 [제품 및 기능](products-and-capabilities.md)을 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="15105-118">데이터 마이그레이션 서비스를 제공하려면 소스 환경과 Office 365 테넌트에 대한 적절한 액세스 및 사용 권한이 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="15105-119">Microsoft의 데이터 마이그레이션 서비스는 특별한 법적 또는 규제 요건에 따른 데이터용으로 설계되거나 설계되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="15105-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="15105-120">데이터를 마이그레이션할 때 FastTrack 마이그레이션 프로젝트에 별도로 제공된 경우를 제외하고, 이 데이터는 시설을 유지하는 모든 위치로 전송, 저장 및 처리될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="15105-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="15105-121">메일 또는 파일 마이그레이션 속도를 보장할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="15105-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="15105-122">소스 환경에서 읽을 수 없거나 손상된 항목과 같은 예기치 않은 문제로 인해 일부 데이터 항목을 마이그레이션하지 못할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="15105-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="15105-123">외부 요인(예: 타사 API(응용 프로그램 프로그래밍 인터페이스) 변경)은 데이터 마이그레이션 서비스의 변경, 지연 또는 중단으로 이어질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="15105-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="15105-124">마이그레이션 서비스를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="15105-124">Migration service availability</span></span>

  - <span data-ttu-id="15105-125">**상업 및 영국 정부 고객:** 당사는 24시간, 주 7일(24x7) 데이터 마이그레이션 서비스를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="15105-126">**미국 정부/DOD 고객:** 당사는 하루 24시간, 주 5일 영업일(24x5) 데이터 마이그레이션 서비스를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="15105-127">Exchange Online으로 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="15105-127">Migration to Exchange Online</span></span>

<span data-ttu-id="15105-128">FastTrack을 사용하여 Exchange Online으로 이메일을 마이그레이션하도록 선택하면 마이그레이션 안내 및 데이터 마이그레이션 서비스를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="15105-129">Microsoft는 마이그레이션을 계획하고, 소스 환경과 Exchange Online을 구성하고, 데이터 마이그레이션 서비스를 활용하여 편지함을 마이그레이션하는 데 도움이 되는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="15105-130">마이그레이션 이벤트를 생성하고 예약합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-130">You create and schedule your migration events.</span></span> <span data-ttu-id="15105-131">스케줄에 따라 마이그레이션 이벤트를 시작하고 진행률을 모니터링하며 상태 보고서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="15105-132">마이그레이션 이벤트가 완료되면 해당 소스 환경의 적절한 예약 및 적격 소스 사서함에서 온 메일이 Exchange Online으로 마이그레이션될 것으로 예상할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="15105-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="15105-133">고려 사항</span><span class="sxs-lookup"><span data-stu-id="15105-133">Considerations</span></span>

  - <span data-ttu-id="15105-134">마이그레이션하기 전에 Exchange Online용 FastTrack 코어 온보딩을 완료해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="15105-135">직접 온보드 탑재를 수행한 경우 필요한 검사 및 필수 구성 요소를 통과해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="15105-136">자세한 내용은 [제품 및 기능](products-and-capabilities.md)을(를) 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="15105-137">FastTrack은 활성 Office 365 사서함으로만 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="15105-138">온-프레미스 Exchange 환경에서 마이그레이션하려면 특정 요구 사항을 충족해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="15105-139">자세한 내용은 [하이브리드 배포 필수 구성 요소](https://go.microsoft.com/fwlink/?LinkId=787528)를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="15105-140">각 소스 환경은 소스 환경의 각 제품에 대한 최신 서비스 팩(SP) 및 롤업(RU)/누적 업데이트(CU) 레벨에 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="15105-141">사내 Active Directory에 있는 메일 그룹(*MailEnabledGroup* 개체) 및 외부 연락처(*MailEnableContact* 개체)는 사서함 데이터 마이그레이션의 일부가 아닙니다.</span><span class="sxs-lookup"><span data-stu-id="15105-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="15105-142">그러나 Azure AD(Azure Active Directory) 연결을 사용하여 동기화할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="15105-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="15105-143">원본 환경</span><span class="sxs-lookup"><span data-stu-id="15105-143">Source environments</span></span>

<span data-ttu-id="15105-144">Microsoft의 데이터 마이그레이션 서비스는 다음과 같은 소스 환경에서 데이터를 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="15105-145">Exchange 조직이 하나 또는 여러 개인 Active Directory 포리스트(각 Exchange 메일 시스템은 Exchange 2010 이상이어야 함)입니다.</span><span class="sxs-lookup"><span data-stu-id="15105-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="15105-146">단일 IMAP 지원 전자 메일 환경</span><span class="sxs-lookup"><span data-stu-id="15105-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="15105-147">G Suite 환경(Gmail, 연락처 및 Outlook 일정만 해당)입니다.</span><span class="sxs-lookup"><span data-stu-id="15105-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="15105-148">다음 표에서는 각 소스 환경에 대한 마이그레이션 세부 정보를 보여 줍니다.</span><span class="sxs-lookup"><span data-stu-id="15105-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="15105-149"><strong>원본 환경</strong></span><span class="sxs-lookup"><span data-stu-id="15105-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="15105-150"><strong>마이그레이션 유형</strong></span><span class="sxs-lookup"><span data-stu-id="15105-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="15105-151"><strong>마이그레이트 대상</strong></span><span class="sxs-lookup"><span data-stu-id="15105-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="15105-152"><strong>마이그레이션되지 않는 사항</strong></span><span class="sxs-lookup"><span data-stu-id="15105-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="15105-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="15105-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="15105-154">
<strong>참고:</strong> 사내 Exchange 종속성에 대해서는  <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">하이브리드 배포 필수 구성 요소</span>를 참조하십시오.</a></span><span class="sxs-lookup"><span data-stu-id="15105-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="15105-155">하이브리드 배포를 사용하는 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="15105-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="15105-156">전자 메일</span><span class="sxs-lookup"><span data-stu-id="15105-156">Emails</span></span></li>
<li><span data-ttu-id="15105-157">사서함 규칙</span><span class="sxs-lookup"><span data-stu-id="15105-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="15105-158">위임</span><span class="sxs-lookup"><span data-stu-id="15105-158">Delegates</span></span></li>
<li><span data-ttu-id="15105-159">사서함 연락처</span><span class="sxs-lookup"><span data-stu-id="15105-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="15105-160">일정</span><span class="sxs-lookup"><span data-stu-id="15105-160">Calendar</span></span> </li>
<li> <span data-ttu-id="15105-161">작업</span><span class="sxs-lookup"><span data-stu-id="15105-161">Tasks</span></span> </li>
<li> <span data-ttu-id="15105-162">권한 관리 전자 메일</span><span class="sxs-lookup"><span data-stu-id="15105-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="15105-163">암호화된 전자 메일</span><span class="sxs-lookup"><span data-stu-id="15105-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="15105-164">서명</span><span class="sxs-lookup"><span data-stu-id="15105-164">Signatures</span></span> </li>
<li> <span data-ttu-id="15105-165">사용자 사서함과 함께 마이그레이션된 개인 보관 파일</span><span class="sxs-lookup"><span data-stu-id="15105-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="15105-166">복구 가능한 항목</span><span class="sxs-lookup"><span data-stu-id="15105-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="15105-167">공용 폴더</span><span class="sxs-lookup"><span data-stu-id="15105-167">Public folders</span></span> </li>
<li> <span data-ttu-id="15105-168">메시지 크기 제한을 초과하는 모든 전자 메일</span><span class="sxs-lookup"><span data-stu-id="15105-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="15105-169">저널링 보관 또는 모든 타사 보관 솔루션</span><span class="sxs-lookup"><span data-stu-id="15105-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="15105-170">차단되거나 비활성 상태인 사용자</span><span class="sxs-lookup"><span data-stu-id="15105-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="15105-171">PST(Personal Storage Table) 파일의 보관 데이터</span><span class="sxs-lookup"><span data-stu-id="15105-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="15105-172">손상된 항목</span><span class="sxs-lookup"><span data-stu-id="15105-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="15105-173">비활성 사서함</span><span class="sxs-lookup"><span data-stu-id="15105-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="15105-174"><strong>G 제품군 환경(Gmail, 연락처 및 캘린더만)</strong></span><span class="sxs-lookup"><span data-stu-id="15105-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="15105-175">
<strong>참고:</strong> G Suite 환경이 <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration"> G Suite 마이그레이션 수행</a>에 설명된 필수 구성 요소를 충족해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="15105-176">단독형 또는 미리 구성</span><span class="sxs-lookup"><span data-stu-id="15105-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="15105-177">전자 메일</span><span class="sxs-lookup"><span data-stu-id="15105-177">Emails</span></span> </li>
<li> <span data-ttu-id="15105-178">사서함 연락처(연락처당 최대 3개의 전자 메일 주소가 마이그레이션됨)</span><span class="sxs-lookup"><span data-stu-id="15105-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="15105-179">일정</span><span class="sxs-lookup"><span data-stu-id="15105-179">Calendar</span></span> </li>
<li> <span data-ttu-id="15105-180">레이블</span><span class="sxs-lookup"><span data-stu-id="15105-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="15105-181">규칙</span><span class="sxs-lookup"><span data-stu-id="15105-181">Rules</span></span> </li>
<li> <span data-ttu-id="15105-182">위임</span><span class="sxs-lookup"><span data-stu-id="15105-182">Delegates</span></span> </li>
<li> <span data-ttu-id="15105-183">서명</span><span class="sxs-lookup"><span data-stu-id="15105-183">Signatures</span></span> </li>
<li> <span data-ttu-id="15105-184">작업</span><span class="sxs-lookup"><span data-stu-id="15105-184">Tasks</span></span> </li>
<li> <span data-ttu-id="15105-185">메시지 크기 제한을 초과하는 모든 전자 메일 또는 첨부 파일</span><span class="sxs-lookup"><span data-stu-id="15105-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="15105-186">차단되거나 비활성 상태인 사용자</span><span class="sxs-lookup"><span data-stu-id="15105-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="15105-187">PST 파일 또는 모든 타사 보관 솔루션(예: Google Vault)의 보관 데이터</span><span class="sxs-lookup"><span data-stu-id="15105-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="15105-188">권한 관리 또는 암호화된 전자 메일</span><span class="sxs-lookup"><span data-stu-id="15105-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="15105-189">손상된 항목</span><span class="sxs-lookup"><span data-stu-id="15105-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="15105-190">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="15105-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="15105-191">Google Groups</span><span class="sxs-lookup"><span data-stu-id="15105-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="15105-192">리소스 사서함</span><span class="sxs-lookup"><span data-stu-id="15105-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="15105-193">비활성 사서함</span><span class="sxs-lookup"><span data-stu-id="15105-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="15105-194">휴가 설정 및 자동 회신 설정</span><span class="sxs-lookup"><span data-stu-id="15105-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="15105-195">공유 일정, 클라우드 첨부 파일, Google Hangout 링크, 이벤트 색상</span><span class="sxs-lookup"><span data-stu-id="15105-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="15105-196">\*\*라벨로 저장된 행아웃 대화를 마이그레이트합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="15105-197"><strong>IMAP4 원본(Domino, GroupWise 또는 Zimbra 등)</strong></span><span class="sxs-lookup"><span data-stu-id="15105-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="15105-198">기본 IMAP4 도구를 사용한 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="15105-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="15105-199">전자 메일</span><span class="sxs-lookup"><span data-stu-id="15105-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="15105-200">규칙</span><span class="sxs-lookup"><span data-stu-id="15105-200">Rules</span></span> </li>
<li> <span data-ttu-id="15105-201">위임</span><span class="sxs-lookup"><span data-stu-id="15105-201">Delegates</span></span> </li>
<li> <span data-ttu-id="15105-202">메일 그룹</span><span class="sxs-lookup"><span data-stu-id="15105-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="15105-203">외부 연락처</span><span class="sxs-lookup"><span data-stu-id="15105-203">External contacts</span></span> </li>
<li> <span data-ttu-id="15105-204">메일을 사용하는 사용자</span><span class="sxs-lookup"><span data-stu-id="15105-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="15105-205">차단되거나 비활성 상태인 사용자</span><span class="sxs-lookup"><span data-stu-id="15105-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="15105-206">사서함 연락처</span><span class="sxs-lookup"><span data-stu-id="15105-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="15105-207">일정</span><span class="sxs-lookup"><span data-stu-id="15105-207">Calendar</span></span> </li>
<li> <span data-ttu-id="15105-208">서명</span><span class="sxs-lookup"><span data-stu-id="15105-208">Signatures</span></span> </li>
<li> <span data-ttu-id="15105-209">작업</span><span class="sxs-lookup"><span data-stu-id="15105-209">Tasks</span></span> </li>
<li> <span data-ttu-id="15105-210">메시지 크기 제한을 초과하는 모든 전자 메일</span><span class="sxs-lookup"><span data-stu-id="15105-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="15105-211">보관 데이터</span><span class="sxs-lookup"><span data-stu-id="15105-211">Archive data</span></span> </li>
<li> <span data-ttu-id="15105-212">암호화된 전자 메일</span><span class="sxs-lookup"><span data-stu-id="15105-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="15105-213">손상된 항목</span><span class="sxs-lookup"><span data-stu-id="15105-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="15105-214">비활성 사서함</span><span class="sxs-lookup"><span data-stu-id="15105-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="15105-215">FastTrack 책임</span><span class="sxs-lookup"><span data-stu-id="15105-215">FastTrack responsibilities</span></span>

<span data-ttu-id="15105-216">Microsoft의 FastTrack 전문가는 마이그레이션 프로젝트 중에 표준 작업을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="15105-217">자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="15105-218">또한 Microsoft의 FastTrack 전문가는 Exchange 마이그레이션과 관련된 다음과 같은 활동을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="15105-219">해당하는 경우 원본 환경과 Exchange 온라인 간에 SMTP 메일 라우팅 공존을 사용하도록 설정하는 데 도움이 되는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="15105-220">귀하의 책임</span><span class="sxs-lookup"><span data-stu-id="15105-220">Your responsibilities</span></span>

<span data-ttu-id="15105-221">마이그레이션 프로젝트 중에 표준 작업을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="15105-222">자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="15105-223">Exchange 마이그레이션과 관련된 다음 작업도 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="15105-224">Exchange Online용 FastTrack 코어 온보딩을 완료합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="15105-225">직접 온보드 탑재를 수행한 경우 필요한 검사 및 필수 구성 요소를 통과해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="15105-226">자세한 내용은 [제품 및 기능](products-and-capabilities.md)을(를) 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="15105-227">Office 365 지침에 따라 적절한 수준의 클라이언트 소프트웨어를 설치합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="15105-228">자세한 내용은 [최신 작업 공간](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="15105-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="15105-229">사내 Exchange 환경에서 마이그레이션하려는 경우 특정 요구 사항을 충족합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="15105-230">자세한 내용은 [하이브리드 배포 필수 구성 요소](https://go.microsoft.com/fwlink/?LinkId=787528)를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="15105-231">해당되는 경우 각 소스 환경이 최신 서비스 팩(SP) 및 롤업(RU)/누적 업데이트(CU) 레벨에 있는지 확인합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="15105-232">해당되는 경우 원본 환경과 Exchange 온라인 간의 SMTP 메일 라우팅 공존을 구성하고 검증합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="15105-233">원본 사서함 크기가 대상 사서함 할당량을 초과하지 않도록 합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="15105-234">원본 플랫폼에 따라 소스 데이터를 대상 사서함 할당량의 85%로 제한해야 할 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="15105-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="15105-235">필요한 경우 클라이언트 측 데이터를 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="15105-236">여기에는 로컬 주소록, 로컬 PST 파일의 데이터, Outlook 규칙 및 로컬 Outlook 설정이 포함되지만 이에 국한되지는 않습니다.</span><span class="sxs-lookup"><span data-stu-id="15105-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="15105-237">최종 사용자가 클라이언트 측 마이그레이션 문제를 해결할 수 있도록 지원합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="15105-238">SharePoint Online으로 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="15105-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="15105-239">FastTrack을 사용하여 SharePoint Online으로 파일을 마이그레이션하도록 선택하면 마이그레이션 안내 및 데이터 마이그레이션 서비스를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="15105-240">Microsoft는 마이그레이션 계획, 소스 환경 및 SharePoint 온라인 구성, 데이터 마이그레이션 서비스를 활용하여 파일을 마이그레이션하는 데 도움이 되는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="15105-241">마이그레이션 이벤트를 생성하고 예약합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-241">You create and schedule your migration events.</span></span> <span data-ttu-id="15105-242">스케줄에 따라 마이그레이션 이벤트를 시작하고 진행률을 모니터링하며 상태 보고서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="15105-243">마이그레이션 이벤트가 완료되면 적절한 예약 소스 및 적합한 소스 소스의 파일이 SharePoint 온라인으로 마이그레이션될 것으로 예상할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="15105-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="15105-244">고려 사항</span><span class="sxs-lookup"><span data-stu-id="15105-244">Considerations</span></span>

  - <span data-ttu-id="15105-245">모든 마이그레이션은 SharePoint 온라인 할당량을 따릅니다.</span><span class="sxs-lookup"><span data-stu-id="15105-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="15105-246">자세한 내용은 [<span class="underline">SharePoint 온라인 및 OneDrive for Business: 소프트웨어 경계 및 제한</span>](https://go.microsoft.com/fwlink/?LinkId=698855)을(를) 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="15105-247">전체 마이그레이션 양을 사용 권한이 있는 전체 SharePoint 온라인 스토리지 할당량의 75%로 제한하는 것이 좋습니다(별도로 구입한 추가 스토리지 포함).</span><span class="sxs-lookup"><span data-stu-id="15105-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="15105-248">소스 환경 세부 정보</span><span class="sxs-lookup"><span data-stu-id="15105-248">Source environment details</span></span>

<span data-ttu-id="15105-249">Microsoft의 데이터 마이그레이션 서비스는 다음과 같은 소스 환경에서 데이터를 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="15105-250">파일 공유(SMB 2.0 이상 지원 장치에서 SMB(서버 메시지 블록) 파일 공유).</span><span class="sxs-lookup"><span data-stu-id="15105-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="15105-251">단일 G 제품군 환경(Google Drive만 해당)</span><span class="sxs-lookup"><span data-stu-id="15105-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="15105-252">Box(Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="15105-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="15105-253">Teams용 Dropbox (표준 및 고급)</span><span class="sxs-lookup"><span data-stu-id="15105-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="15105-254">다음 표에서는 각 소스 환경에 대한 마이그레이션 세부 정보를 보여 줍니다.</span><span class="sxs-lookup"><span data-stu-id="15105-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="15105-255"><strong>원본 환경</strong></span><span class="sxs-lookup"><span data-stu-id="15105-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="15105-256"><strong>마이그레이션 유형</strong></span><span class="sxs-lookup"><span data-stu-id="15105-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="15105-257"><strong>마이그레이트 대상</strong></span><span class="sxs-lookup"><span data-stu-id="15105-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="15105-258"><strong>마이그레이션되지 않는 사항</strong></span><span class="sxs-lookup"><span data-stu-id="15105-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="15105-259"><strong>SMB 2.0 이상을 지원하는 모든 파일 공유 장치</strong></span><span class="sxs-lookup"><span data-stu-id="15105-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="15105-260">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="15105-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="15105-261">문서</span><span class="sxs-lookup"><span data-stu-id="15105-261">Documents</span></span> </li>
<li> <span data-ttu-id="15105-262">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="15105-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="15105-263">사용자 수준 파일 및 폴더 권한\*</span><span class="sxs-lookup"><span data-stu-id="15105-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="15105-264">그룹 수준 파일 및 폴더 권한\*</span><span class="sxs-lookup"><span data-stu-id="15105-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="15105-265">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="15105-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="15105-266">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="15105-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="15105-267">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="15105-267">Created date</span></span> </li>
<li> <span data-ttu-id="15105-268">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="15105-268">Modified date</span></span> </li>
<li> <span data-ttu-id="15105-269">만든 사람</span><span class="sxs-lookup"><span data-stu-id="15105-269">Created by</span></span> </li>
<li> <span data-ttu-id="15105-270">마지막 수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="15105-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="15105-271">\* 디렉터리 동기화 구성이 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="15105-272">Windows 파일 탐색기에 표시된 NTFS 권한만 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="15105-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="15105-273">파일 공유 장치에서 직접 관리되는 사용 권한은 마이그레이션되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="15105-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="15105-274">데이터가 SMB 2.0 장치에 저장된 경우 SMB 프로토콜에 의해 노출된 NTFS 동등 사용 권한이 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="15105-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="15105-275">소유권 기록 및 이전 버전</span><span class="sxs-lookup"><span data-stu-id="15105-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="15105-276">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="15105-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="15105-277">이전 버전</span><span class="sxs-lookup"><span data-stu-id="15105-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="15105-278">Windows 파일 및 폴더 특성(예: 읽기 전용 및 숨김)</span><span class="sxs-lookup"><span data-stu-id="15105-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="15105-279">Windows가 아닌 NTFS(New Technology File System) 및 NTFS 고급 사용 권한 및 특수 설정:</span><span class="sxs-lookup"><span data-stu-id="15105-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="15105-280">명시적 거부 사용 권한(마이그레이션 후 제거됨, 콘텐츠는 병렬 사용 권한 또는 상위 폴더의 사용 권한에 따름)</span><span class="sxs-lookup"><span data-stu-id="15105-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="15105-281">NTFS 감사 구성</span><span class="sxs-lookup"><span data-stu-id="15105-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="15105-282">FCI(파일 분류 인프라)에 의해 제공되는 추가 파일 메타데이터</span><span class="sxs-lookup"><span data-stu-id="15105-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="15105-283">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="15105-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="15105-284">숨겨진 공유</span><span class="sxs-lookup"><span data-stu-id="15105-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="15105-285">공유(예: 공유 수준에 부여된 사용 권한)</span><span class="sxs-lookup"><span data-stu-id="15105-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="15105-286">파일 또는 폴더가 현재 <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint 온라인 제한 및 제한</span></a> 를 초과합니다. </span><span class="sxs-lookup"><span data-stu-id="15105-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="15105-287"><strong>단일 G 제품군 환경(Google Drive만 해당)</strong></span><span class="sxs-lookup"><span data-stu-id="15105-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="15105-288">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="15105-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="15105-289">Google 문서, 스프레드시트 및 슬라이드(파일이 동등한 Office 형식으로 변환됨 / 10MB 초과하는 파일 포함)</span><span class="sxs-lookup"><span data-stu-id="15105-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="15105-290">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="15105-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="15105-291">사용자 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="15105-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="15105-292">그룹 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="15105-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="15105-293">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="15105-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="15105-294">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="15105-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="15105-295">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="15105-295">Created date</span></span> </li>
<li> <span data-ttu-id="15105-296">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="15105-296">Modified date</span></span> </li>
<li> <span data-ttu-id="15105-297">만든 사람</span><span class="sxs-lookup"><span data-stu-id="15105-297">Created by</span></span> </li>
<li> <span data-ttu-id="15105-298">마지막 수정 날짜</span><span class="sxs-lookup"><span data-stu-id="15105-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="15105-299">공유 드라이브(폴더 및 파일)</span><span class="sxs-lookup"><span data-stu-id="15105-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="15105-300">Google Drive 계정이 소유한 공유 콘텐츠를 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="15105-301">소유권 기록, 이전 버전 및 메모</span><span class="sxs-lookup"><span data-stu-id="15105-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="15105-302">파일 및 폴더 설명, 폴더 색상</span><span class="sxs-lookup"><span data-stu-id="15105-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="15105-303">사용자 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="15105-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="15105-304">그룹 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="15105-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="15105-305">고급 메타 데이터</span><span class="sxs-lookup"><span data-stu-id="15105-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="15105-306">파일 잠금 특성</span><span class="sxs-lookup"><span data-stu-id="15105-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="15105-307">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="15105-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="15105-308">휴지통 항목</span><span class="sxs-lookup"><span data-stu-id="15105-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="15105-309">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="15105-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="15105-310">차단되거나 비활성 상태인 사용자</span><span class="sxs-lookup"><span data-stu-id="15105-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="15105-311">Google Photos. Forms, Maps 및 기타 연결된 앱</span><span class="sxs-lookup"><span data-stu-id="15105-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="15105-312">Google 드로잉</span><span class="sxs-lookup"><span data-stu-id="15105-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="15105-313">조직 외부로 공유된 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="15105-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="15105-314">마이그레이션할 Google Drive 계정에서 소유하지 않은 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="15105-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="15105-315">외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>): Google Drive Admin 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="15105-316">최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="15105-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="15105-317">공유 드라이브 구성원 권한(<strong>참고</strong>): Google Drive Admin 보고서를 사용하여 공유 드라이브 구성원 자격을 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="15105-318">마이그레이션하기 전에 최종 사용자에게 대상에서 이러한 구성원 자격 설정을 구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="15105-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="15105-319">파일이 제한 된 것으로 표시 되었거나 복사 가능 하지 않음</span><span class="sxs-lookup"><span data-stu-id="15105-319">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="15105-320">파일 또는 폴더가 현재 <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint 온라인 제한 및 제한</span></a> 를 초과합니다. </span><span class="sxs-lookup"><span data-stu-id="15105-320">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="15105-321"><strong>Box(Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="15105-321"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="15105-322">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="15105-322">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="15105-323">문서</span><span class="sxs-lookup"><span data-stu-id="15105-323">Documents</span></span> </li>
<li> <span data-ttu-id="15105-324">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="15105-324">File and folder structure</span></span> </li>
<li> <span data-ttu-id="15105-325">사용자 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="15105-325">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="15105-326">그룹 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="15105-326">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="15105-327">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="15105-327">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="15105-328">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="15105-328">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="15105-329">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="15105-329">Created date</span></span> </li>
<li> <span data-ttu-id="15105-330">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="15105-330">Modified date</span></span> </li>
<li> <span data-ttu-id="15105-331">만든 사람</span><span class="sxs-lookup"><span data-stu-id="15105-331">Created by</span></span> </li>
<li> <span data-ttu-id="15105-332">마지막 수정 날짜</span><span class="sxs-lookup"><span data-stu-id="15105-332">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="15105-333">Box 계정이 소유한 공유 콘텐츠가 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="15105-333">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="15105-334">소유권 기록, 이전 버전 및 메모</span><span class="sxs-lookup"><span data-stu-id="15105-334">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="15105-335">파일 및 폴더 설명</span><span class="sxs-lookup"><span data-stu-id="15105-335">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="15105-336">사용자 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="15105-336">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="15105-337">그룹 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="15105-337">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="15105-338">Box 태그와 고급 메타데이터</span><span class="sxs-lookup"><span data-stu-id="15105-338">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="15105-339">파일 잠금 특성</span><span class="sxs-lookup"><span data-stu-id="15105-339">File lock attributes</span></span> </li>
<li> <span data-ttu-id="15105-340">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="15105-340">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="15105-341">휴지통 항목</span><span class="sxs-lookup"><span data-stu-id="15105-341">Trashed items</span></span> </li>
<li> <span data-ttu-id="15105-342">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="15105-342">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="15105-343">차단되거나 비활성 상태인 사용자</span><span class="sxs-lookup"><span data-stu-id="15105-343">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="15105-344">Box 앱, 책갈피, 즐겨찾기 및 워크플로</span><span class="sxs-lookup"><span data-stu-id="15105-344">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="15105-345">마이그레이션된 상자 계정에서 소유하지 않은 콘텐츠입니다.</span><span class="sxs-lookup"><span data-stu-id="15105-345">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="15105-346">외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>): Box 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-346">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="15105-347">최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="15105-347">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="15105-348">파일 또는 폴더가 현재 <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint 온라인 제한 및 제한</span></a> 를 초과합니다. </span><span class="sxs-lookup"><span data-stu-id="15105-348">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="15105-349"><strong>Teams용 Dropbox(표준 및 고급)</strong></span><span class="sxs-lookup"><span data-stu-id="15105-349"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="15105-350">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="15105-350">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="15105-351">문서</span><span class="sxs-lookup"><span data-stu-id="15105-351">Documents</span></span> </li>
<li> <span data-ttu-id="15105-352">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="15105-352">File and folder structure</span></span> </li>
<li> <span data-ttu-id="15105-353">사용자 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="15105-353">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="15105-354">그룹 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="15105-354">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="15105-355">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="15105-355">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="15105-356">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="15105-356">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="15105-357">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="15105-357">Created date</span></span> </li>
<li> <span data-ttu-id="15105-358">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="15105-358">Modified date</span></span> </li>
<li> <span data-ttu-id="15105-359">만든 사람</span><span class="sxs-lookup"><span data-stu-id="15105-359">Created by</span></span> </li>
<li> <span data-ttu-id="15105-360">마지막 수정 날짜</span><span class="sxs-lookup"><span data-stu-id="15105-360">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="15105-361">공유 팀 폴더 및 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="15105-361">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="15105-362">Dropbox 계정이 소유한 공유 콘텐츠가 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="15105-362">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="15105-363">소유권 기록, 이전 버전 및 메모</span><span class="sxs-lookup"><span data-stu-id="15105-363">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="15105-364">파일 및 폴더 설명</span><span class="sxs-lookup"><span data-stu-id="15105-364">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="15105-365">사용자 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="15105-365">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="15105-366">그룹 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="15105-366">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="15105-367">고급 메타 데이터</span><span class="sxs-lookup"><span data-stu-id="15105-367">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="15105-368">파일 잠금 특성</span><span class="sxs-lookup"><span data-stu-id="15105-368">File lock attributes</span></span> </li>
<li> <span data-ttu-id="15105-369">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="15105-369">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="15105-370">휴지통 항목</span><span class="sxs-lookup"><span data-stu-id="15105-370">Trashed items</span></span> </li>
<li> <span data-ttu-id="15105-371">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="15105-371">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="15105-372">연결 해제된 Dropbox 폴더</span><span class="sxs-lookup"><span data-stu-id="15105-372">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="15105-373">삭제되거나 연결이 끊어진 사용자</span><span class="sxs-lookup"><span data-stu-id="15105-373">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="15105-374">Dropbox Paper, Showcases 및 Spaces</span><span class="sxs-lookup"><span data-stu-id="15105-374">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="15105-375">Dropbox 앱 및 즐겨찾기(핀/별)</span><span class="sxs-lookup"><span data-stu-id="15105-375">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="15105-376">마이그레이션된 Dropbox 계정이 소유하지 않은 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="15105-376">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="15105-377">외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>: Dropbox 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-377">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="15105-378">최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="15105-378">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="15105-379">파일 또는 폴더가 현재 <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint 온라인 제한 및 제한</span></a> 를 초과합니다. </span><span class="sxs-lookup"><span data-stu-id="15105-379">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="15105-380">FastTrack 책임</span><span class="sxs-lookup"><span data-stu-id="15105-380">FastTrack responsibilities</span></span>

<span data-ttu-id="15105-381">Microsoft의 FastTrack 전문가는 마이그레이션 프로젝트 중에 표준 작업을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-381">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="15105-382">자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-382">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="15105-383">귀하의 책임</span><span class="sxs-lookup"><span data-stu-id="15105-383">Your responsibilities</span></span>

<span data-ttu-id="15105-384">마이그레이션 프로젝트 중에 표준 작업을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-384">You perform standard activities during the migration project.</span></span> <span data-ttu-id="15105-385">자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-385">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="15105-386">또한 SharePoint 온라인 마이그레이션과 관련된 다음 작업도 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-386">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="15105-387">모든 SharePoint 팀 사이트를 마이그레이션 이벤트의 대상으로 프로비저닝합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-387">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="15105-388">비즈니스용 OneDrive로 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="15105-388">Migration to OneDrive for Business</span></span>

<span data-ttu-id="15105-389">FastTrack을 사용하여 파일을 비즈니스용 OneDrive로 마이그레이션하도록 선택하면 마이그레이션 안내 및 데이터 마이그레이션 서비스를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-389">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="15105-390">Microsoft는 마이그레이션 계획, 소스 환경 및 비즈니스용 OneDrive 구성, 데이터 마이그레이션 서비스를 활용하여 파일을 마이그레이션하는 데 도움이 되는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-390">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="15105-391">마이그레이션 이벤트를 생성하고 예약합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-391">You create and schedule your migration events.</span></span> <span data-ttu-id="15105-392">스케줄에 따라 마이그레이션 이벤트를 시작하고 진행률을 모니터링하며 상태 보고서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-392">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="15105-393">마이그레이션 이벤트가 완료되면 적절한 소스 환경의 적절한 예약 소스 및 적합한 원본의 파일이 비즈니스용 OneDrive로 마이그레이션될 것으로 예상할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="15105-393">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="15105-394">고려 사항</span><span class="sxs-lookup"><span data-stu-id="15105-394">Considerations</span></span>

  - <span data-ttu-id="15105-395">모든 마이그레이션에는 비즈니스용 OneDrive 할당량이 적용됩니다.</span><span class="sxs-lookup"><span data-stu-id="15105-395">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="15105-396">자세한 내용은 [<span class="underline">SharePoint Online 및 비즈니스용 OneDrive: 소프트웨어 경계 및 제한</span>](https://go.microsoft.com/fwlink/?LinkId=698855)을 참조하시기 바랍니다.</span><span class="sxs-lookup"><span data-stu-id="15105-396">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="15105-397">마이그레이션하는 전체 데이터 양을 권한이 부여된 전체 SharePoint 온라인 스토리지 할당량의 75%로 제한하는 것이 좋습니다(별도로 구입한 추가 스토리지 포함).</span><span class="sxs-lookup"><span data-stu-id="15105-397">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="15105-398">FastTrack은 활성 비즈니스용 OneDrive 드라이브로만 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-398">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="15105-399">소스 환경 세부 정보</span><span class="sxs-lookup"><span data-stu-id="15105-399">Source environment details</span></span>

<span data-ttu-id="15105-400">Microsoft의 데이터 마이그레이션 서비스는 다음과 같은 소스 환경에서 데이터를 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-400">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="15105-401">파일 공유(SMB 2.0 이상 지원 장치에서 SMB 파일 공유)</span><span class="sxs-lookup"><span data-stu-id="15105-401">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="15105-402">단일 G 제품군 환경(Google Drive만 해당)</span><span class="sxs-lookup"><span data-stu-id="15105-402">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="15105-403">Box(Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="15105-403">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="15105-404">Teams용 Dropbox (표준 및 고급)</span><span class="sxs-lookup"><span data-stu-id="15105-404">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="15105-405">다음 표에서는 각 소스 환경에 대한 마이그레이션 세부 정보를 보여 줍니다.</span><span class="sxs-lookup"><span data-stu-id="15105-405">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="15105-406"><strong>원본 환경</strong></span><span class="sxs-lookup"><span data-stu-id="15105-406"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="15105-407"><strong>마이그레이션 유형</strong></span><span class="sxs-lookup"><span data-stu-id="15105-407"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="15105-408"><strong>마이그레이트 대상</strong></span><span class="sxs-lookup"><span data-stu-id="15105-408"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="15105-409"><strong>마이그레이션되지 않는 사항</strong></span><span class="sxs-lookup"><span data-stu-id="15105-409"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="15105-410"><strong>SMB 2.0 이상을 지원하는 모든 파일 공유 장치</strong></span><span class="sxs-lookup"><span data-stu-id="15105-410"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="15105-411">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="15105-411">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="15105-412">문서</span><span class="sxs-lookup"><span data-stu-id="15105-412">Documents</span></span> </li>
<li> <span data-ttu-id="15105-413">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="15105-413">File and folder structure</span></span> </li>
<li> <span data-ttu-id="15105-414">사용자 수준 파일 및 폴더 권한\*</span><span class="sxs-lookup"><span data-stu-id="15105-414">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="15105-415">그룹 수준 파일 및 폴더 권한\*</span><span class="sxs-lookup"><span data-stu-id="15105-415">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="15105-416">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="15105-416">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="15105-417">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="15105-417">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="15105-418">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="15105-418">Created date</span></span> </li>
<li> <span data-ttu-id="15105-419">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="15105-419">Modified date</span></span> </li>
<li> <span data-ttu-id="15105-420">만든 사람</span><span class="sxs-lookup"><span data-stu-id="15105-420">Created by</span></span> </li>
<li> <span data-ttu-id="15105-421">마지막 수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="15105-421">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="15105-422">\* 디렉터리 동기화 구성이 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-422">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="15105-423">Windows 파일 탐색기에 표시된 NTFS 권한만 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="15105-423">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="15105-424">파일 공유 장치에서 직접 관리되는 사용 권한은 마이그레이션되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="15105-424">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="15105-425">데이터가 SMB 2.0 장치에 저장된 경우 SMB 프로토콜에 의해 노출된 NTFS 동등 사용 권한이 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="15105-425">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="15105-426">소유권 기록 및 이전 버전</span><span class="sxs-lookup"><span data-stu-id="15105-426">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="15105-427">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="15105-427">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="15105-428">이전 버전</span><span class="sxs-lookup"><span data-stu-id="15105-428">Previous versions</span></span> </li>
<li> <span data-ttu-id="15105-429">Windows 파일 및 폴더 특성(예: 읽기 전용 및 숨김)</span><span class="sxs-lookup"><span data-stu-id="15105-429">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="15105-430">Windows가 아닌 NTFS(New Technology File System) 및 NTFS 고급 사용 권한 및 특수 설정:</span><span class="sxs-lookup"><span data-stu-id="15105-430">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="15105-431">명시적 거부 사용 권한(마이그레이션 후 제거됨, 콘텐츠는 병렬 사용 권한 또는 상위 폴더의 사용 권한에 따름)</span><span class="sxs-lookup"><span data-stu-id="15105-431">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="15105-432">NTFS 감사 구성</span><span class="sxs-lookup"><span data-stu-id="15105-432">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="15105-433">FCI(파일 분류 인프라)에 의해 제공되는 추가 파일 메타데이터</span><span class="sxs-lookup"><span data-stu-id="15105-433">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="15105-434">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="15105-434">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="15105-435">숨겨진 공유</span><span class="sxs-lookup"><span data-stu-id="15105-435">Hidden shares</span></span> </li>
<li> <span data-ttu-id="15105-436">공유(예: 공유 수준에 부여된 사용 권한)</span><span class="sxs-lookup"><span data-stu-id="15105-436">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="15105-437">파일 또는 폴더가 현재 <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint 온라인 제한 및 제한</span></a> 를 초과합니다. </span><span class="sxs-lookup"><span data-stu-id="15105-437">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="15105-438"><strong>단일 G 제품군 환경(Google Drive만 해당)</strong></span><span class="sxs-lookup"><span data-stu-id="15105-438"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="15105-439">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="15105-439">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="15105-440">Google 문서, 스프레드시트 및 슬라이드(파일이 동등한 Office 형식으로 변환됨 / 10MB 초과하는 파일 포함)</span><span class="sxs-lookup"><span data-stu-id="15105-440">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="15105-441">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="15105-441">File and folder structure</span></span> </li>
<li> <span data-ttu-id="15105-442">사용자 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="15105-442">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="15105-443">그룹 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="15105-443">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="15105-444">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="15105-444">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="15105-445">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="15105-445">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="15105-446">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="15105-446">Created date</span></span> </li>
<li> <span data-ttu-id="15105-447">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="15105-447">Modified date</span></span> </li>
<li> <span data-ttu-id="15105-448">만든 사람</span><span class="sxs-lookup"><span data-stu-id="15105-448">Created by</span></span> </li>
<li> <span data-ttu-id="15105-449">마지막 수정 날짜</span><span class="sxs-lookup"><span data-stu-id="15105-449">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="15105-450">공유 드라이브(폴더 및 파일)</span><span class="sxs-lookup"><span data-stu-id="15105-450">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="15105-451">Google Drive 계정이 소유한 공유 콘텐츠를 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-451">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="15105-452">소유권 기록, 이전 버전 및 메모</span><span class="sxs-lookup"><span data-stu-id="15105-452">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="15105-453">파일 및 폴더 설명, 폴더 색상</span><span class="sxs-lookup"><span data-stu-id="15105-453">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="15105-454">사용자 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="15105-454">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="15105-455">그룹 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="15105-455">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="15105-456">고급 메타 데이터</span><span class="sxs-lookup"><span data-stu-id="15105-456">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="15105-457">파일 잠금 특성</span><span class="sxs-lookup"><span data-stu-id="15105-457">File lock attributes</span></span> </li>
<li> <span data-ttu-id="15105-458">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="15105-458">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="15105-459">휴지통 항목</span><span class="sxs-lookup"><span data-stu-id="15105-459">Trashed items</span></span> </li>
<li> <span data-ttu-id="15105-460">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="15105-460">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="15105-461">차단되거나 비활성 상태인 사용자</span><span class="sxs-lookup"><span data-stu-id="15105-461">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="15105-462">Google Photos. Forms, Maps 및 기타 연결된 앱</span><span class="sxs-lookup"><span data-stu-id="15105-462">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="15105-463">Google 드로잉</span><span class="sxs-lookup"><span data-stu-id="15105-463">Google Drawings</span></span> </li>
<li> <span data-ttu-id="15105-464">조직 외부로 공유된 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="15105-464">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="15105-465">마이그레이션할 Google Drive 계정에서 소유하지 않은 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="15105-465">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="15105-466">외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>): Google Drive Admin 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-466">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="15105-467">최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="15105-467">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="15105-468">공유 드라이브 구성원 권한(<strong>참고</strong>): Google Drive Admin 보고서를 사용하여 공유 드라이브 구성원 자격을 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-468">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="15105-469">마이그레이션하기 전에 최종 사용자에게 대상에서 이러한 구성원 자격 설정을 구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="15105-469">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="15105-470">파일 또는 폴더가 현재 <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint 온라인 제한 및 제한</span></a> 를 초과합니다. </span><span class="sxs-lookup"><span data-stu-id="15105-470">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="15105-471"><strong>Box(Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="15105-471"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="15105-472">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="15105-472">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="15105-473">문서</span><span class="sxs-lookup"><span data-stu-id="15105-473">Documents</span></span> </li>
<li> <span data-ttu-id="15105-474">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="15105-474">File and folder structure</span></span> </li>
<li> <span data-ttu-id="15105-475">사용자 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="15105-475">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="15105-476">그룹 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="15105-476">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="15105-477">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="15105-477">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="15105-478">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="15105-478">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="15105-479">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="15105-479">Created date</span></span> </li>
<li> <span data-ttu-id="15105-480">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="15105-480">Modified date</span></span> </li>
<li> <span data-ttu-id="15105-481">만든 사람</span><span class="sxs-lookup"><span data-stu-id="15105-481">Created by</span></span> </li>
<li> <span data-ttu-id="15105-482">마지막 수정 날짜</span><span class="sxs-lookup"><span data-stu-id="15105-482">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="15105-483">Box 계정이 소유한 공유 콘텐츠가 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="15105-483">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="15105-484">소유권 기록, 이전 버전 및 메모</span><span class="sxs-lookup"><span data-stu-id="15105-484">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="15105-485">파일 및 폴더 설명</span><span class="sxs-lookup"><span data-stu-id="15105-485">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="15105-486">사용자 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="15105-486">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="15105-487">그룹 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="15105-487">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="15105-488">Box 태그와 고급 메타데이터</span><span class="sxs-lookup"><span data-stu-id="15105-488">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="15105-489">파일 잠금 특성</span><span class="sxs-lookup"><span data-stu-id="15105-489">File lock attributes</span></span> </li>
<li> <span data-ttu-id="15105-490">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="15105-490">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="15105-491">휴지통 항목</span><span class="sxs-lookup"><span data-stu-id="15105-491">Trashed items</span></span> </li>
<li> <span data-ttu-id="15105-492">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="15105-492">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="15105-493">차단되거나 비활성 상태인 사용자</span><span class="sxs-lookup"><span data-stu-id="15105-493">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="15105-494">Box 앱, 책갈피, 즐겨찾기 및 워크플로</span><span class="sxs-lookup"><span data-stu-id="15105-494">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="15105-495">마이그레이션된 상자 계정에서 소유하지 않은 콘텐츠입니다.</span><span class="sxs-lookup"><span data-stu-id="15105-495">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="15105-496">외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>): Box 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-496">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="15105-497">최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="15105-497">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="15105-498">파일 또는 폴더가 현재 <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint 온라인 제한 및 제한</span></a> 를 초과합니다. </span><span class="sxs-lookup"><span data-stu-id="15105-498">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="15105-499"><strong>Teams용 Dropbox(표준 및 고급)</strong></span><span class="sxs-lookup"><span data-stu-id="15105-499"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="15105-500">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="15105-500">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="15105-501">문서</span><span class="sxs-lookup"><span data-stu-id="15105-501">Documents</span></span> </li>
<li> <span data-ttu-id="15105-502">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="15105-502">File and folder structure</span></span> </li>
<li> <span data-ttu-id="15105-503">사용자 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="15105-503">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="15105-504">그룹 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="15105-504">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="15105-505">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="15105-505">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="15105-506">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="15105-506">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="15105-507">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="15105-507">Created date</span></span> </li>
<li> <span data-ttu-id="15105-508">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="15105-508">Modified date</span></span> </li>
<li> <span data-ttu-id="15105-509">만든 사람</span><span class="sxs-lookup"><span data-stu-id="15105-509">Created by</span></span> </li>
<li> <span data-ttu-id="15105-510">마지막 수정 날짜</span><span class="sxs-lookup"><span data-stu-id="15105-510">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="15105-511">공유 팀 폴더 및 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="15105-511">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="15105-512">Dropbox 계정이 소유한 공유 콘텐츠가 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="15105-512">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="15105-513">소유권 기록, 이전 버전 및 메모</span><span class="sxs-lookup"><span data-stu-id="15105-513">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="15105-514">파일 및 폴더 설명</span><span class="sxs-lookup"><span data-stu-id="15105-514">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="15105-515">사용자 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="15105-515">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="15105-516">그룹 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="15105-516">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="15105-517">고급 메타 데이터</span><span class="sxs-lookup"><span data-stu-id="15105-517">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="15105-518">파일 잠금 특성</span><span class="sxs-lookup"><span data-stu-id="15105-518">File lock attributes</span></span> </li>
<li> <span data-ttu-id="15105-519">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="15105-519">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="15105-520">휴지통 항목</span><span class="sxs-lookup"><span data-stu-id="15105-520">Trashed items</span></span> </li>
<li> <span data-ttu-id="15105-521">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="15105-521">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="15105-522">연결 해제된 Dropbox 폴더</span><span class="sxs-lookup"><span data-stu-id="15105-522">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="15105-523">삭제되거나 연결이 끊어진 사용자</span><span class="sxs-lookup"><span data-stu-id="15105-523">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="15105-524">Dropbox Paper, Showcases 및 Spaces</span><span class="sxs-lookup"><span data-stu-id="15105-524">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="15105-525">Dropbox 앱 및 즐겨찾기(핀/별)</span><span class="sxs-lookup"><span data-stu-id="15105-525">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="15105-526">마이그레이션된 Dropbox 계정이 소유하지 않은 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="15105-526">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="15105-527">외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>: Dropbox 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-527">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="15105-528">최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="15105-528">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="15105-529">파일 또는 폴더가 현재 <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint 온라인 제한 및 제한</span></a> 를 초과합니다. </span><span class="sxs-lookup"><span data-stu-id="15105-529">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="15105-530">FastTrack 책임</span><span class="sxs-lookup"><span data-stu-id="15105-530">FastTrack responsibilities</span></span>

<span data-ttu-id="15105-531">Microsoft의 FastTrack 전문가는 마이그레이션 프로젝트 중에 표준 작업을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-531">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="15105-532">자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-532">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="15105-533">귀하의 책임</span><span class="sxs-lookup"><span data-stu-id="15105-533">Your responsibilities</span></span>

<span data-ttu-id="15105-534">마이그레이션 프로젝트 중에 표준 작업을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-534">You perform standard activities during the migration project.</span></span> <span data-ttu-id="15105-535">자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-535">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="15105-536">또한 비즈니스용 OneDrive 마이그레이션과 관련된 다음 작업도 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-536">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="15105-537">마이그레이션 이벤트의 대상이 되는 비즈니스 사이트를 위해 모든 OneDrive를 프로비저닝합니다.</span><span class="sxs-lookup"><span data-stu-id="15105-537">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
