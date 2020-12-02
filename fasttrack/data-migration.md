---
title: 데이터 마이그레이션
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 12/1/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack은 원본 환경의 메일 및 파일 데이터를 Office 365(Exchange Online, SharePoint Online 및 비즈니스용 OneDrive)로 마이그레이션하는 데 도움이 됩니다. Microsoft가 제공하는 지원 유형은 Office 365 라이선스 수에 따라 다릅니다.
ms.openlocfilehash: 5a64bcbecffa3fd78f54b9a5e0f3f07e76d0b316
ms.sourcegitcommit: d69d3e1e478a817f8279e9da98880499e9302665
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 12/01/2020
ms.locfileid: "49525363"
---
# <a name="data-migration"></a><span data-ttu-id="2dcd0-104">데이터 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="2dcd0-104">Data Migration</span></span>

<span data-ttu-id="2dcd0-105">FastTrack은 원본 환경의 메일 및 파일 데이터를 Office 365(Exchange Online, SharePoint Online 및 비즈니스용 OneDrive)로 마이그레이션하는 데 도움이 됩니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="2dcd0-106">Microsoft가 제공하는 지원 유형은 Office 365 라이선스 수에 따라 달라집니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="2dcd0-107">**150-499 라이선스를 보유한 Office 365 테넌트**: FastTrack은 마이그레이션 안내만 제공하며 데이터 마이그레이션을 수행해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="2dcd0-108">셀프 서비스 마이그레이션을 수행하기 위해 무료 도구를 계획하고 사용하는 데 도움이 되는 문서를 안내합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="2dcd0-109">**라이선스가 500개 이상인 Office 365 테넌트**: FastTrack은 마이그레이션 안내 및 데이터 마이그레이션 서비스를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="2dcd0-110">Microsoft는 마이그레이션 계획, 소스 환경 및 Office 365 테넌트 구성, 데이터 마이그레이션 서비스를 활용하여 데이터를 마이그레이션하는 데 도움이 되는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="2dcd0-111">마이그레이션 이벤트를 생성하고 예약합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-111">You create and schedule your migration events.</span></span> <span data-ttu-id="2dcd0-112">스케줄에 따라 마이그레이션 이벤트를 시작하고 진행률을 모니터링하며 상태 보고서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="2dcd0-113">2017년 9월 1일 이전에 상업용 계획을 구입하거나 갱신한 경우 데이터 마이그레이션 서비스를 받으려면 150개의 라이선스만 있으면 됩니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="2dcd0-114">교육 계획의 경우 유급 직원 및 직원 라이선스만 데이터 마이그레이션 서비스를 받을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="2dcd0-115">고려 사항</span><span class="sxs-lookup"><span data-stu-id="2dcd0-115">Considerations</span></span>

  - <span data-ttu-id="2dcd0-116">Office 365로 데이터를 마이그레이션하려면 소스 환경이 특정 기대치를 충족해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="2dcd0-117">Exchange, SharePoint 및 비즈니스용 OneDrive에 대한 소스 환경에 대한 자세한 내용은 [제품 및 기능](products-and-capabilities.md)을 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="2dcd0-118">데이터 마이그레이션 서비스를 제공하려면 소스 환경과 Office 365 테넌트에 대한 적절한 액세스 및 사용 권한이 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="2dcd0-119">Microsoft의 데이터 마이그레이션 서비스는 특별한 법적 또는 규제 요건에 따른 데이터용으로 설계되거나 설계되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="2dcd0-120">데이터를 마이그레이션할 때 FastTrack 마이그레이션 프로젝트에 별도로 제공된 경우를 제외하고, 이 데이터는 시설을 유지하는 모든 위치로 전송, 저장 및 처리될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="2dcd0-121">메일 또는 파일 마이그레이션 속도를 보장할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="2dcd0-122">소스 환경에서 읽을 수 없거나 손상된 항목과 같은 예기치 않은 문제로 인해 일부 데이터 항목을 마이그레이션하지 못할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="2dcd0-123">외부 요인(예: 타사 API(응용 프로그램 프로그래밍 인터페이스) 변경)은 데이터 마이그레이션 서비스의 변경, 지연 또는 중단으로 이어질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="2dcd0-124">마이그레이션 서비스를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-124">Migration service availability</span></span>

  - <span data-ttu-id="2dcd0-125">**상업 및 영국 정부 고객:** 당사는 24시간, 주 7일(24x7) 데이터 마이그레이션 서비스를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="2dcd0-126">**미국 정부/DOD 고객:** 당사는 하루 24시간, 주 5일 영업일(24x5) 데이터 마이그레이션 서비스를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="2dcd0-127">Exchange Online으로 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="2dcd0-127">Migration to Exchange Online</span></span>

<span data-ttu-id="2dcd0-128">FastTrack을 사용하여 Exchange Online으로 이메일을 마이그레이션하도록 선택하면 마이그레이션 안내 및 데이터 마이그레이션 서비스를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="2dcd0-129">Microsoft는 마이그레이션을 계획하고, 소스 환경과 Exchange Online을 구성하고, 데이터 마이그레이션 서비스를 활용하여 편지함을 마이그레이션하는 데 도움이 되는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="2dcd0-130">마이그레이션 이벤트를 생성하고 예약합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-130">You create and schedule your migration events.</span></span> <span data-ttu-id="2dcd0-131">스케줄에 따라 마이그레이션 이벤트를 시작하고 진행률을 모니터링하며 상태 보고서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="2dcd0-132">마이그레이션 이벤트가 완료되면 해당 소스 환경의 적절한 예약 및 적격 소스 사서함에서 온 메일이 Exchange Online으로 마이그레이션될 것으로 예상할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="2dcd0-133">고려 사항</span><span class="sxs-lookup"><span data-stu-id="2dcd0-133">Considerations</span></span>

  - <span data-ttu-id="2dcd0-134">마이그레이션하기 전에 Exchange Online용 FastTrack 코어 온보딩을 완료해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="2dcd0-135">직접 온보드 탑재를 수행한 경우 필요한 검사 및 필수 구성 요소를 통과해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="2dcd0-136">자세한 내용은 [제품 및 기능](products-and-capabilities.md)을(를) 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="2dcd0-137">FastTrack은 활성 Office 365 사서함으로만 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="2dcd0-138">온-프레미스 Exchange 환경에서 마이그레이션하려면 특정 요구 사항을 충족해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="2dcd0-139">자세한 내용은 [하이브리드 배포 필수 구성 요소](https://go.microsoft.com/fwlink/?LinkId=787528)를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="2dcd0-140">각 소스 환경은 소스 환경의 각 제품에 대한 최신 서비스 팩(SP) 및 롤업(RU)/누적 업데이트(CU) 레벨에 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="2dcd0-141">사내 Active Directory에 있는 메일 그룹(*MailEnabledGroup* 개체) 및 외부 연락처(*MailEnableContact* 개체)는 사서함 데이터 마이그레이션의 일부가 아닙니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="2dcd0-142">그러나 Azure AD(Azure Active Directory) 연결을 사용하여 동기화할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="2dcd0-143">원본 환경</span><span class="sxs-lookup"><span data-stu-id="2dcd0-143">Source environments</span></span>

<span data-ttu-id="2dcd0-144">Microsoft의 데이터 마이그레이션 서비스는 다음과 같은 소스 환경에서 데이터를 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="2dcd0-145">Exchange 조직이 하나 또는 여러 개인 Active Directory 포리스트(각 Exchange 메일 시스템은 Exchange 2010 이상이어야 함)입니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="2dcd0-146">단일 IMAP 지원 전자 메일 환경</span><span class="sxs-lookup"><span data-stu-id="2dcd0-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="2dcd0-147">G Suite 환경(Gmail, 연락처 및 Outlook 일정만 해당)입니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="2dcd0-148">다음 표에서는 각 소스 환경에 대한 마이그레이션 세부 정보를 보여 줍니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="2dcd0-149"><strong>원본 환경</strong></span><span class="sxs-lookup"><span data-stu-id="2dcd0-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="2dcd0-150"><strong>마이그레이션 유형</strong></span><span class="sxs-lookup"><span data-stu-id="2dcd0-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="2dcd0-151"><strong>마이그레이트 대상</strong></span><span class="sxs-lookup"><span data-stu-id="2dcd0-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="2dcd0-152"><strong>마이그레이션되지 않는 사항</strong></span><span class="sxs-lookup"><span data-stu-id="2dcd0-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="2dcd0-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="2dcd0-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="2dcd0-154">
<strong>참고:</strong> 온-프레미스 Exchange 종속성의 경우 <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">하이브리드 배포 필수 구성 요소</span></a>를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="2dcd0-155">하이브리드 배포를 사용하는 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="2dcd0-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="2dcd0-156">전자 메일</span><span class="sxs-lookup"><span data-stu-id="2dcd0-156">Emails</span></span></li>
<li><span data-ttu-id="2dcd0-157">사서함 규칙</span><span class="sxs-lookup"><span data-stu-id="2dcd0-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="2dcd0-158">위임</span><span class="sxs-lookup"><span data-stu-id="2dcd0-158">Delegates</span></span></li>
<li><span data-ttu-id="2dcd0-159">사서함 연락처</span><span class="sxs-lookup"><span data-stu-id="2dcd0-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="2dcd0-160">일정</span><span class="sxs-lookup"><span data-stu-id="2dcd0-160">Calendar</span></span> </li>
<li> <span data-ttu-id="2dcd0-161">작업</span><span class="sxs-lookup"><span data-stu-id="2dcd0-161">Tasks</span></span> </li>
<li> <span data-ttu-id="2dcd0-162">권한 관리 전자 메일</span><span class="sxs-lookup"><span data-stu-id="2dcd0-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="2dcd0-163">암호화된 전자 메일</span><span class="sxs-lookup"><span data-stu-id="2dcd0-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="2dcd0-164">서명</span><span class="sxs-lookup"><span data-stu-id="2dcd0-164">Signatures</span></span> </li>
<li> <span data-ttu-id="2dcd0-165">사용자 사서함과 함께 마이그레이션된 개인 보관 파일</span><span class="sxs-lookup"><span data-stu-id="2dcd0-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="2dcd0-166">복구 가능한 항목</span><span class="sxs-lookup"><span data-stu-id="2dcd0-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="2dcd0-167">공용 폴더</span><span class="sxs-lookup"><span data-stu-id="2dcd0-167">Public folders</span></span> </li>
<li> <span data-ttu-id="2dcd0-168">메시지 크기 제한을 초과하는 모든 전자 메일</span><span class="sxs-lookup"><span data-stu-id="2dcd0-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="2dcd0-169">저널링 보관 또는 모든 타사 보관 솔루션</span><span class="sxs-lookup"><span data-stu-id="2dcd0-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="2dcd0-170">차단되거나 비활성 상태인 사용자</span><span class="sxs-lookup"><span data-stu-id="2dcd0-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="2dcd0-171">PST(Personal Storage Table) 파일의 보관 데이터</span><span class="sxs-lookup"><span data-stu-id="2dcd0-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="2dcd0-172">손상된 항목</span><span class="sxs-lookup"><span data-stu-id="2dcd0-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="2dcd0-173">비활성 사서함</span><span class="sxs-lookup"><span data-stu-id="2dcd0-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="2dcd0-174"><strong>G 제품군 환경(Gmail, 연락처 및 캘린더만)</strong></span><span class="sxs-lookup"><span data-stu-id="2dcd0-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="2dcd0-175">
<strong>참고:</strong> G Suite 환경은 <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">g suite 마이그레이션 수행</a>에 설명 된 필수 구성 요소를 충족 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="2dcd0-176">단독형 또는 미리 구성</span><span class="sxs-lookup"><span data-stu-id="2dcd0-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="2dcd0-177">전자 메일</span><span class="sxs-lookup"><span data-stu-id="2dcd0-177">Emails</span></span> </li>
<li> <span data-ttu-id="2dcd0-178">사서함 연락처(연락처당 최대 3개의 전자 메일 주소가 마이그레이션됨)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="2dcd0-179">일정</span><span class="sxs-lookup"><span data-stu-id="2dcd0-179">Calendar</span></span> </li>
<li> <span data-ttu-id="2dcd0-180">레이블</span><span class="sxs-lookup"><span data-stu-id="2dcd0-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="2dcd0-181">규칙</span><span class="sxs-lookup"><span data-stu-id="2dcd0-181">Rules</span></span> </li>
<li> <span data-ttu-id="2dcd0-182">위임</span><span class="sxs-lookup"><span data-stu-id="2dcd0-182">Delegates</span></span> </li>
<li> <span data-ttu-id="2dcd0-183">서명</span><span class="sxs-lookup"><span data-stu-id="2dcd0-183">Signatures</span></span> </li>
<li> <span data-ttu-id="2dcd0-184">작업</span><span class="sxs-lookup"><span data-stu-id="2dcd0-184">Tasks</span></span> </li>
<li> <span data-ttu-id="2dcd0-185">메시지 크기 제한을 초과하는 모든 전자 메일 또는 첨부 파일</span><span class="sxs-lookup"><span data-stu-id="2dcd0-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="2dcd0-186">차단되거나 비활성 상태인 사용자</span><span class="sxs-lookup"><span data-stu-id="2dcd0-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="2dcd0-187">PST 파일 또는 모든 타사 보관 솔루션(예: Google Vault)의 보관 데이터</span><span class="sxs-lookup"><span data-stu-id="2dcd0-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="2dcd0-188">권한 관리 또는 암호화된 전자 메일</span><span class="sxs-lookup"><span data-stu-id="2dcd0-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="2dcd0-189">손상된 항목</span><span class="sxs-lookup"><span data-stu-id="2dcd0-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="2dcd0-190">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="2dcd0-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="2dcd0-191">Google Groups</span><span class="sxs-lookup"><span data-stu-id="2dcd0-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="2dcd0-192">리소스 사서함</span><span class="sxs-lookup"><span data-stu-id="2dcd0-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="2dcd0-193">비활성 사서함</span><span class="sxs-lookup"><span data-stu-id="2dcd0-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="2dcd0-194">휴가 설정 및 자동 회신 설정</span><span class="sxs-lookup"><span data-stu-id="2dcd0-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="2dcd0-195">공유 일정, 클라우드 첨부 파일, Google Hangout 링크, 이벤트 색상</span><span class="sxs-lookup"><span data-stu-id="2dcd0-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="2dcd0-196">\*\*라벨로 저장된 행아웃 대화를 마이그레이트합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="2dcd0-197"><strong>IMAP4 원본(Domino, GroupWise 또는 Zimbra 등)</strong></span><span class="sxs-lookup"><span data-stu-id="2dcd0-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="2dcd0-198">기본 IMAP4 도구를 사용한 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="2dcd0-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="2dcd0-199">전자 메일</span><span class="sxs-lookup"><span data-stu-id="2dcd0-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="2dcd0-200">규칙</span><span class="sxs-lookup"><span data-stu-id="2dcd0-200">Rules</span></span> </li>
<li> <span data-ttu-id="2dcd0-201">위임</span><span class="sxs-lookup"><span data-stu-id="2dcd0-201">Delegates</span></span> </li>
<li> <span data-ttu-id="2dcd0-202">메일 그룹</span><span class="sxs-lookup"><span data-stu-id="2dcd0-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="2dcd0-203">외부 연락처</span><span class="sxs-lookup"><span data-stu-id="2dcd0-203">External contacts</span></span> </li>
<li> <span data-ttu-id="2dcd0-204">메일을 사용하는 사용자</span><span class="sxs-lookup"><span data-stu-id="2dcd0-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="2dcd0-205">차단되거나 비활성 상태인 사용자</span><span class="sxs-lookup"><span data-stu-id="2dcd0-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="2dcd0-206">사서함 연락처</span><span class="sxs-lookup"><span data-stu-id="2dcd0-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="2dcd0-207">일정</span><span class="sxs-lookup"><span data-stu-id="2dcd0-207">Calendar</span></span> </li>
<li> <span data-ttu-id="2dcd0-208">서명</span><span class="sxs-lookup"><span data-stu-id="2dcd0-208">Signatures</span></span> </li>
<li> <span data-ttu-id="2dcd0-209">작업</span><span class="sxs-lookup"><span data-stu-id="2dcd0-209">Tasks</span></span> </li>
<li> <span data-ttu-id="2dcd0-210">메시지 크기 제한을 초과하는 모든 전자 메일</span><span class="sxs-lookup"><span data-stu-id="2dcd0-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="2dcd0-211">보관 데이터</span><span class="sxs-lookup"><span data-stu-id="2dcd0-211">Archive data</span></span> </li>
<li> <span data-ttu-id="2dcd0-212">암호화된 전자 메일</span><span class="sxs-lookup"><span data-stu-id="2dcd0-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="2dcd0-213">손상된 항목</span><span class="sxs-lookup"><span data-stu-id="2dcd0-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="2dcd0-214">비활성 사서함</span><span class="sxs-lookup"><span data-stu-id="2dcd0-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="2dcd0-215">FastTrack 책임</span><span class="sxs-lookup"><span data-stu-id="2dcd0-215">FastTrack responsibilities</span></span>

<span data-ttu-id="2dcd0-216">Microsoft의 FastTrack 전문가는 마이그레이션 프로젝트 중에 표준 작업을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="2dcd0-217">자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="2dcd0-218">또한 Microsoft의 FastTrack 전문가는 Exchange 마이그레이션과 관련된 다음과 같은 활동을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="2dcd0-219">해당하는 경우 원본 환경과 Exchange 온라인 간에 SMTP 메일 라우팅 공존을 사용하도록 설정하는 데 도움이 되는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="2dcd0-220">귀하의 책임</span><span class="sxs-lookup"><span data-stu-id="2dcd0-220">Your responsibilities</span></span>

<span data-ttu-id="2dcd0-221">마이그레이션 프로젝트 중에 표준 작업을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="2dcd0-222">자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="2dcd0-223">Exchange 마이그레이션과 관련된 다음 작업도 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="2dcd0-224">Exchange Online용 FastTrack 코어 온보딩을 완료합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="2dcd0-225">직접 온보드 탑재를 수행한 경우 필요한 검사 및 필수 구성 요소를 통과해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="2dcd0-226">자세한 내용은 [제품 및 기능](products-and-capabilities.md)을(를) 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="2dcd0-227">Office 365 지침에 따라 적절한 수준의 클라이언트 소프트웨어를 설치합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="2dcd0-228">자세한 내용은 [최신 작업 공간](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="2dcd0-229">사내 Exchange 환경에서 마이그레이션하려는 경우 특정 요구 사항을 충족합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="2dcd0-230">자세한 내용은 [하이브리드 배포 필수 구성 요소](https://go.microsoft.com/fwlink/?LinkId=787528)를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="2dcd0-231">해당되는 경우 각 소스 환경이 최신 서비스 팩(SP) 및 롤업(RU)/누적 업데이트(CU) 레벨에 있는지 확인합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="2dcd0-232">해당되는 경우 원본 환경과 Exchange 온라인 간의 SMTP 메일 라우팅 공존을 구성하고 검증합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="2dcd0-233">원본 사서함 크기가 대상 사서함 할당량을 초과하지 않도록 합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="2dcd0-234">원본 플랫폼에 따라 소스 데이터를 대상 사서함 할당량의 85%로 제한해야 할 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="2dcd0-235">필요한 경우 클라이언트 측 데이터를 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="2dcd0-236">여기에는 로컬 주소록, 로컬 PST 파일의 데이터, Outlook 규칙 및 로컬 Outlook 설정이 포함되지만 이에 국한되지는 않습니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="2dcd0-237">최종 사용자가 클라이언트 측 마이그레이션 문제를 해결할 수 있도록 지원합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="2dcd0-238">SharePoint Online으로 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="2dcd0-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="2dcd0-239">FastTrack을 사용하여 SharePoint Online으로 파일을 마이그레이션하도록 선택하면 마이그레이션 안내 및 데이터 마이그레이션 서비스를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="2dcd0-240">Microsoft는 마이그레이션 계획, 소스 환경 및 SharePoint 온라인 구성, 데이터 마이그레이션 서비스를 활용하여 파일을 마이그레이션하는 데 도움이 되는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="2dcd0-241">마이그레이션 이벤트를 생성하고 예약합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-241">You create and schedule your migration events.</span></span> <span data-ttu-id="2dcd0-242">스케줄에 따라 마이그레이션 이벤트를 시작하고 진행률을 모니터링하며 상태 보고서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="2dcd0-243">마이그레이션 이벤트가 완료되면 적절한 예약 소스 및 적합한 소스 소스의 파일이 SharePoint 온라인으로 마이그레이션될 것으로 예상할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="2dcd0-244">고려 사항</span><span class="sxs-lookup"><span data-stu-id="2dcd0-244">Considerations</span></span>

  - <span data-ttu-id="2dcd0-245">모든 마이그레이션은 SharePoint 온라인 할당량을 따릅니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="2dcd0-246">자세한 내용은 [<span class="underline">SharePoint 온라인 및 OneDrive for Business: 소프트웨어 경계 및 제한</span>](https://go.microsoft.com/fwlink/?LinkId=698855)을(를) 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="2dcd0-247">전체 마이그레이션 양을 사용 권한이 있는 전체 SharePoint 온라인 스토리지 할당량의 75%로 제한하는 것이 좋습니다(별도로 구입한 추가 스토리지 포함).</span><span class="sxs-lookup"><span data-stu-id="2dcd0-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="2dcd0-248">소스 환경 세부 정보</span><span class="sxs-lookup"><span data-stu-id="2dcd0-248">Source environment details</span></span>

<span data-ttu-id="2dcd0-249">Microsoft의 데이터 마이그레이션 서비스는 다음과 같은 소스 환경에서 데이터를 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="2dcd0-250">파일 공유(SMB 2.0 이상 지원 장치에서 SMB(서버 메시지 블록) 파일 공유).</span><span class="sxs-lookup"><span data-stu-id="2dcd0-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="2dcd0-251">단일 G 제품군 환경(Google Drive만 해당)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="2dcd0-252">Box(Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="2dcd0-253">Teams용 Dropbox (표준 및 고급)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="2dcd0-254">다음 표에서는 각 소스 환경에 대한 마이그레이션 세부 정보를 보여 줍니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="2dcd0-255"><strong>원본 환경</strong></span><span class="sxs-lookup"><span data-stu-id="2dcd0-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="2dcd0-256"><strong>마이그레이션 유형</strong></span><span class="sxs-lookup"><span data-stu-id="2dcd0-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="2dcd0-257"><strong>마이그레이트 대상</strong></span><span class="sxs-lookup"><span data-stu-id="2dcd0-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="2dcd0-258"><strong>마이그레이션되지 않는 사항</strong></span><span class="sxs-lookup"><span data-stu-id="2dcd0-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="2dcd0-259"><strong>SMB 2.0 이상을 지원하는 모든 파일 공유 장치</strong></span><span class="sxs-lookup"><span data-stu-id="2dcd0-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="2dcd0-260">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="2dcd0-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="2dcd0-261">문서</span><span class="sxs-lookup"><span data-stu-id="2dcd0-261">Documents</span></span> </li>
<li> <span data-ttu-id="2dcd0-262">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="2dcd0-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="2dcd0-263">사용자 수준 파일 및 폴더 권한\*</span><span class="sxs-lookup"><span data-stu-id="2dcd0-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="2dcd0-264">그룹 수준 파일 및 폴더 권한\*</span><span class="sxs-lookup"><span data-stu-id="2dcd0-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="2dcd0-265">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="2dcd0-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="2dcd0-266">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="2dcd0-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="2dcd0-267">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="2dcd0-267">Created date</span></span> </li>
<li> <span data-ttu-id="2dcd0-268">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="2dcd0-268">Modified date</span></span> </li>
<li> <span data-ttu-id="2dcd0-269">만든 사람</span><span class="sxs-lookup"><span data-stu-id="2dcd0-269">Created by</span></span> </li>
<li> <span data-ttu-id="2dcd0-270">마지막 수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="2dcd0-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="2dcd0-271">\* 디렉터리 동기화 구성이 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="2dcd0-272">Windows 파일 탐색기에 표시된 NTFS 권한만 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="2dcd0-273">파일 공유 장치에서 직접 관리되는 사용 권한은 마이그레이션되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="2dcd0-274">데이터가 SMB 2.0 장치에 저장된 경우 SMB 프로토콜에 의해 노출된 NTFS 동등 사용 권한이 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="2dcd0-275">소유권 기록 및 이전 버전</span><span class="sxs-lookup"><span data-stu-id="2dcd0-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="2dcd0-276">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="2dcd0-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="2dcd0-277">이전 버전</span><span class="sxs-lookup"><span data-stu-id="2dcd0-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="2dcd0-278">Windows 파일 및 폴더 특성(예: 읽기 전용 및 숨김)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="2dcd0-279">Windows가 아닌 NTFS(New Technology File System) 및 NTFS 고급 사용 권한 및 특수 설정:</span><span class="sxs-lookup"><span data-stu-id="2dcd0-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="2dcd0-280">명시적 거부 사용 권한(마이그레이션 후 제거됨, 콘텐츠는 병렬 사용 권한 또는 상위 폴더의 사용 권한에 따름)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="2dcd0-281">NTFS 감사 구성</span><span class="sxs-lookup"><span data-stu-id="2dcd0-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="2dcd0-282">FCI(파일 분류 인프라)에 의해 제공되는 추가 파일 메타데이터</span><span class="sxs-lookup"><span data-stu-id="2dcd0-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="2dcd0-283">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="2dcd0-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="2dcd0-284">숨겨진 공유</span><span class="sxs-lookup"><span data-stu-id="2dcd0-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="2dcd0-285">공유(예: 공유 수준에 부여된 사용 권한)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="2dcd0-286">현재 <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online 제한 사항 및 제한 사항을 초과 하</span> 는 파일 또는 폴더</a> </span><span class="sxs-lookup"><span data-stu-id="2dcd0-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="2dcd0-287"><strong>단일 G 제품군 환경(Google Drive만 해당)</strong></span><span class="sxs-lookup"><span data-stu-id="2dcd0-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="2dcd0-288">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="2dcd0-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="2dcd0-289">Google 문서, 스프레드시트 및 슬라이드(파일이 동등한 Office 형식으로 변환됨 / 10MB 초과하는 파일 포함)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="2dcd0-290">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="2dcd0-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="2dcd0-291">사용자 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="2dcd0-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2dcd0-292">그룹 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="2dcd0-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2dcd0-293">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="2dcd0-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="2dcd0-294">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="2dcd0-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="2dcd0-295">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="2dcd0-295">Created date</span></span> </li>
<li> <span data-ttu-id="2dcd0-296">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="2dcd0-296">Modified date</span></span> </li>
<li> <span data-ttu-id="2dcd0-297">만든 사람</span><span class="sxs-lookup"><span data-stu-id="2dcd0-297">Created by</span></span> </li>
<li> <span data-ttu-id="2dcd0-298">마지막 수정 날짜</span><span class="sxs-lookup"><span data-stu-id="2dcd0-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="2dcd0-299">공유 드라이브(폴더 및 파일)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="2dcd0-300">Google Drive 계정이 소유한 공유 콘텐츠를 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="2dcd0-301">소유권 기록, 이전 버전 및 메모</span><span class="sxs-lookup"><span data-stu-id="2dcd0-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="2dcd0-302">파일 및 폴더 설명, 폴더 색상</span><span class="sxs-lookup"><span data-stu-id="2dcd0-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="2dcd0-303">사용자 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="2dcd0-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="2dcd0-304">그룹 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="2dcd0-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="2dcd0-305">고급 메타 데이터</span><span class="sxs-lookup"><span data-stu-id="2dcd0-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="2dcd0-306">파일 잠금 특성</span><span class="sxs-lookup"><span data-stu-id="2dcd0-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="2dcd0-307">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="2dcd0-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="2dcd0-308">휴지통 항목</span><span class="sxs-lookup"><span data-stu-id="2dcd0-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="2dcd0-309">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="2dcd0-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="2dcd0-310">차단되거나 비활성 상태인 사용자</span><span class="sxs-lookup"><span data-stu-id="2dcd0-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="2dcd0-311">Google Photos. Forms, Maps 및 기타 연결된 앱</span><span class="sxs-lookup"><span data-stu-id="2dcd0-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="2dcd0-312">Google 드로잉</span><span class="sxs-lookup"><span data-stu-id="2dcd0-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="2dcd0-313">조직 외부로 공유된 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="2dcd0-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="2dcd0-314">마이그레이션할 Google Drive 계정에서 소유하지 않은 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="2dcd0-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="2dcd0-315">외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>): Google Drive Admin 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="2dcd0-316">최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="2dcd0-317">공유 드라이브 구성원 권한(<strong>참고</strong>): Google Drive Admin 보고서를 사용하여 공유 드라이브 구성원 자격을 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="2dcd0-318">마이그레이션하기 전에 최종 사용자에게 대상에서 이러한 구성원 자격 설정을 구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="2dcd0-319">파일이 제한 된 것으로 표시 되었거나 복사 가능 하지 않음</span><span class="sxs-lookup"><span data-stu-id="2dcd0-319">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="2dcd0-320">현재 <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online 제한 사항 및 제한 사항을 초과 하</span> 는 파일 또는 폴더</a> </span><span class="sxs-lookup"><span data-stu-id="2dcd0-320">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="2dcd0-321"><strong>Box(Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="2dcd0-321"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="2dcd0-322">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="2dcd0-322">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="2dcd0-323">문서</span><span class="sxs-lookup"><span data-stu-id="2dcd0-323">Documents</span></span> </li>
<li> <span data-ttu-id="2dcd0-324">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="2dcd0-324">File and folder structure</span></span> </li>
<li> <span data-ttu-id="2dcd0-325">사용자 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="2dcd0-325">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2dcd0-326">그룹 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="2dcd0-326">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2dcd0-327">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="2dcd0-327">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="2dcd0-328">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="2dcd0-328">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="2dcd0-329">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="2dcd0-329">Created date</span></span> </li>
<li> <span data-ttu-id="2dcd0-330">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="2dcd0-330">Modified date</span></span> </li>
<li> <span data-ttu-id="2dcd0-331">만든 사람</span><span class="sxs-lookup"><span data-stu-id="2dcd0-331">Created by</span></span> </li>
<li> <span data-ttu-id="2dcd0-332">마지막 수정 날짜</span><span class="sxs-lookup"><span data-stu-id="2dcd0-332">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="2dcd0-333">Box 계정이 소유한 공유 콘텐츠가 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-333">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="2dcd0-334">Box Notes (Word 문서 형식으로 변환 됨)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-334">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="2dcd0-335">소유권 기록, 이전 버전 및 메모</span><span class="sxs-lookup"><span data-stu-id="2dcd0-335">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="2dcd0-336">파일 및 폴더 설명</span><span class="sxs-lookup"><span data-stu-id="2dcd0-336">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="2dcd0-337">사용자 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="2dcd0-337">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="2dcd0-338">그룹 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="2dcd0-338">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="2dcd0-339">Box 태그와 고급 메타데이터</span><span class="sxs-lookup"><span data-stu-id="2dcd0-339">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="2dcd0-340">파일 잠금 특성</span><span class="sxs-lookup"><span data-stu-id="2dcd0-340">File lock attributes</span></span> </li>
<li> <span data-ttu-id="2dcd0-341">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="2dcd0-341">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="2dcd0-342">휴지통 항목</span><span class="sxs-lookup"><span data-stu-id="2dcd0-342">Trashed items</span></span> </li>
<li> <span data-ttu-id="2dcd0-343">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="2dcd0-343">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="2dcd0-344">차단되거나 비활성 상태인 사용자</span><span class="sxs-lookup"><span data-stu-id="2dcd0-344">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="2dcd0-345">Box 앱, 책갈피, 즐겨찾기 및 워크플로</span><span class="sxs-lookup"><span data-stu-id="2dcd0-345">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="2dcd0-346">마이그레이션된 상자 계정에서 소유하지 않은 콘텐츠입니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-346">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="2dcd0-347">외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>): Box 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-347">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="2dcd0-348">최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-348">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="2dcd0-349">현재 <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online 제한 사항 및 제한 사항을 초과 하</span> 는 파일 또는 폴더</a> </span><span class="sxs-lookup"><span data-stu-id="2dcd0-349">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="2dcd0-350"><strong>Teams용 Dropbox(표준 및 고급)</strong></span><span class="sxs-lookup"><span data-stu-id="2dcd0-350"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="2dcd0-351">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="2dcd0-351">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="2dcd0-352">문서</span><span class="sxs-lookup"><span data-stu-id="2dcd0-352">Documents</span></span> </li>
<li> <span data-ttu-id="2dcd0-353">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="2dcd0-353">File and folder structure</span></span> </li>
<li> <span data-ttu-id="2dcd0-354">사용자 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="2dcd0-354">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2dcd0-355">그룹 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="2dcd0-355">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2dcd0-356">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="2dcd0-356">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="2dcd0-357">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="2dcd0-357">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="2dcd0-358">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="2dcd0-358">Created date</span></span> </li>
<li> <span data-ttu-id="2dcd0-359">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="2dcd0-359">Modified date</span></span> </li>
<li> <span data-ttu-id="2dcd0-360">만든 사람</span><span class="sxs-lookup"><span data-stu-id="2dcd0-360">Created by</span></span> </li>
<li> <span data-ttu-id="2dcd0-361">마지막 수정 날짜</span><span class="sxs-lookup"><span data-stu-id="2dcd0-361">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="2dcd0-362">공유 팀 폴더 및 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="2dcd0-362">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="2dcd0-363">Dropbox 계정이 소유한 공유 콘텐츠가 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-363">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="2dcd0-364">소유권 기록, 이전 버전 및 메모</span><span class="sxs-lookup"><span data-stu-id="2dcd0-364">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="2dcd0-365">파일 및 폴더 설명</span><span class="sxs-lookup"><span data-stu-id="2dcd0-365">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="2dcd0-366">사용자 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="2dcd0-366">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="2dcd0-367">그룹 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="2dcd0-367">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="2dcd0-368">고급 메타 데이터</span><span class="sxs-lookup"><span data-stu-id="2dcd0-368">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="2dcd0-369">파일 잠금 특성</span><span class="sxs-lookup"><span data-stu-id="2dcd0-369">File lock attributes</span></span> </li>
<li> <span data-ttu-id="2dcd0-370">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="2dcd0-370">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="2dcd0-371">휴지통 항목</span><span class="sxs-lookup"><span data-stu-id="2dcd0-371">Trashed items</span></span> </li>
<li> <span data-ttu-id="2dcd0-372">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="2dcd0-372">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="2dcd0-373">연결 해제된 Dropbox 폴더</span><span class="sxs-lookup"><span data-stu-id="2dcd0-373">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="2dcd0-374">삭제되거나 연결이 끊어진 사용자</span><span class="sxs-lookup"><span data-stu-id="2dcd0-374">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="2dcd0-375">Dropbox Paper, Showcases 및 Spaces</span><span class="sxs-lookup"><span data-stu-id="2dcd0-375">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="2dcd0-376">Dropbox 앱 및 즐겨찾기(핀/별)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-376">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="2dcd0-377">마이그레이션된 Dropbox 계정이 소유하지 않은 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="2dcd0-377">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="2dcd0-378">외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>: Dropbox 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-378">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="2dcd0-379">최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-379">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="2dcd0-380">현재 <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online 제한 사항 및 제한 사항을 초과 하</span> 는 파일 또는 폴더</a> </span><span class="sxs-lookup"><span data-stu-id="2dcd0-380">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="2dcd0-381">FastTrack 책임</span><span class="sxs-lookup"><span data-stu-id="2dcd0-381">FastTrack responsibilities</span></span>

<span data-ttu-id="2dcd0-382">Microsoft의 FastTrack 전문가는 마이그레이션 프로젝트 중에 표준 작업을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-382">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="2dcd0-383">자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-383">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="2dcd0-384">귀하의 책임</span><span class="sxs-lookup"><span data-stu-id="2dcd0-384">Your responsibilities</span></span>

<span data-ttu-id="2dcd0-385">마이그레이션 프로젝트 중에 표준 작업을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-385">You perform standard activities during the migration project.</span></span> <span data-ttu-id="2dcd0-386">자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-386">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="2dcd0-387">또한 SharePoint 온라인 마이그레이션과 관련된 다음 작업도 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-387">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="2dcd0-388">모든 SharePoint 팀 사이트를 마이그레이션 이벤트의 대상으로 프로비저닝합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-388">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="2dcd0-389">비즈니스용 OneDrive로 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="2dcd0-389">Migration to OneDrive for Business</span></span>

<span data-ttu-id="2dcd0-390">FastTrack을 사용하여 파일을 비즈니스용 OneDrive로 마이그레이션하도록 선택하면 마이그레이션 안내 및 데이터 마이그레이션 서비스를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-390">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="2dcd0-391">Microsoft는 마이그레이션 계획, 소스 환경 및 비즈니스용 OneDrive 구성, 데이터 마이그레이션 서비스를 활용하여 파일을 마이그레이션하는 데 도움이 되는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-391">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="2dcd0-392">마이그레이션 이벤트를 생성하고 예약합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-392">You create and schedule your migration events.</span></span> <span data-ttu-id="2dcd0-393">스케줄에 따라 마이그레이션 이벤트를 시작하고 진행률을 모니터링하며 상태 보고서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-393">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="2dcd0-394">마이그레이션 이벤트가 완료되면 적절한 소스 환경의 적절한 예약 소스 및 적합한 원본의 파일이 비즈니스용 OneDrive로 마이그레이션될 것으로 예상할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-394">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="2dcd0-395">고려 사항</span><span class="sxs-lookup"><span data-stu-id="2dcd0-395">Considerations</span></span>

  - <span data-ttu-id="2dcd0-396">모든 마이그레이션에는 비즈니스용 OneDrive 할당량이 적용됩니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-396">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="2dcd0-397">자세한 내용은 [<span class="underline">SharePoint Online 및 비즈니스용 OneDrive: 소프트웨어 경계 및 제한</span>](https://go.microsoft.com/fwlink/?LinkId=698855)을 참조하시기 바랍니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-397">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="2dcd0-398">마이그레이션하는 전체 데이터 양을 권한이 부여된 전체 SharePoint 온라인 스토리지 할당량의 75%로 제한하는 것이 좋습니다(별도로 구입한 추가 스토리지 포함).</span><span class="sxs-lookup"><span data-stu-id="2dcd0-398">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="2dcd0-399">FastTrack은 활성 비즈니스용 OneDrive 드라이브로만 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-399">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="2dcd0-400">소스 환경 세부 정보</span><span class="sxs-lookup"><span data-stu-id="2dcd0-400">Source environment details</span></span>

<span data-ttu-id="2dcd0-401">Microsoft의 데이터 마이그레이션 서비스는 다음과 같은 소스 환경에서 데이터를 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-401">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="2dcd0-402">파일 공유(SMB 2.0 이상 지원 장치에서 SMB 파일 공유)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-402">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="2dcd0-403">단일 G 제품군 환경(Google Drive만 해당)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-403">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="2dcd0-404">Box(Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-404">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="2dcd0-405">Teams용 Dropbox (표준 및 고급)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-405">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="2dcd0-406">다음 표에서는 각 소스 환경에 대한 마이그레이션 세부 정보를 보여 줍니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-406">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="2dcd0-407"><strong>원본 환경</strong></span><span class="sxs-lookup"><span data-stu-id="2dcd0-407"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="2dcd0-408"><strong>마이그레이션 유형</strong></span><span class="sxs-lookup"><span data-stu-id="2dcd0-408"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="2dcd0-409"><strong>마이그레이트 대상</strong></span><span class="sxs-lookup"><span data-stu-id="2dcd0-409"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="2dcd0-410"><strong>마이그레이션되지 않는 사항</strong></span><span class="sxs-lookup"><span data-stu-id="2dcd0-410"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="2dcd0-411"><strong>SMB 2.0 이상을 지원하는 모든 파일 공유 장치</strong></span><span class="sxs-lookup"><span data-stu-id="2dcd0-411"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="2dcd0-412">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="2dcd0-412">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="2dcd0-413">문서</span><span class="sxs-lookup"><span data-stu-id="2dcd0-413">Documents</span></span> </li>
<li> <span data-ttu-id="2dcd0-414">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="2dcd0-414">File and folder structure</span></span> </li>
<li> <span data-ttu-id="2dcd0-415">사용자 수준 파일 및 폴더 권한\*</span><span class="sxs-lookup"><span data-stu-id="2dcd0-415">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="2dcd0-416">그룹 수준 파일 및 폴더 권한\*</span><span class="sxs-lookup"><span data-stu-id="2dcd0-416">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="2dcd0-417">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="2dcd0-417">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="2dcd0-418">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="2dcd0-418">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="2dcd0-419">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="2dcd0-419">Created date</span></span> </li>
<li> <span data-ttu-id="2dcd0-420">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="2dcd0-420">Modified date</span></span> </li>
<li> <span data-ttu-id="2dcd0-421">만든 사람</span><span class="sxs-lookup"><span data-stu-id="2dcd0-421">Created by</span></span> </li>
<li> <span data-ttu-id="2dcd0-422">마지막 수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="2dcd0-422">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="2dcd0-423">\* 디렉터리 동기화 구성이 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-423">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="2dcd0-424">Windows 파일 탐색기에 표시된 NTFS 권한만 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-424">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="2dcd0-425">파일 공유 장치에서 직접 관리되는 사용 권한은 마이그레이션되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-425">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="2dcd0-426">데이터가 SMB 2.0 장치에 저장된 경우 SMB 프로토콜에 의해 노출된 NTFS 동등 사용 권한이 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-426">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="2dcd0-427">소유권 기록 및 이전 버전</span><span class="sxs-lookup"><span data-stu-id="2dcd0-427">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="2dcd0-428">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="2dcd0-428">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="2dcd0-429">이전 버전</span><span class="sxs-lookup"><span data-stu-id="2dcd0-429">Previous versions</span></span> </li>
<li> <span data-ttu-id="2dcd0-430">Windows 파일 및 폴더 특성(예: 읽기 전용 및 숨김)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-430">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="2dcd0-431">Windows가 아닌 NTFS(New Technology File System) 및 NTFS 고급 사용 권한 및 특수 설정:</span><span class="sxs-lookup"><span data-stu-id="2dcd0-431">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="2dcd0-432">명시적 거부 사용 권한(마이그레이션 후 제거됨, 콘텐츠는 병렬 사용 권한 또는 상위 폴더의 사용 권한에 따름)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-432">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="2dcd0-433">NTFS 감사 구성</span><span class="sxs-lookup"><span data-stu-id="2dcd0-433">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="2dcd0-434">FCI(파일 분류 인프라)에 의해 제공되는 추가 파일 메타데이터</span><span class="sxs-lookup"><span data-stu-id="2dcd0-434">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="2dcd0-435">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="2dcd0-435">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="2dcd0-436">숨겨진 공유</span><span class="sxs-lookup"><span data-stu-id="2dcd0-436">Hidden shares</span></span> </li>
<li> <span data-ttu-id="2dcd0-437">공유(예: 공유 수준에 부여된 사용 권한)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-437">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="2dcd0-438">현재 <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online 제한 사항 및 제한 사항을 초과 하</span> 는 파일 또는 폴더</a> </span><span class="sxs-lookup"><span data-stu-id="2dcd0-438">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="2dcd0-439"><strong>단일 G 제품군 환경(Google Drive만 해당)</strong></span><span class="sxs-lookup"><span data-stu-id="2dcd0-439"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="2dcd0-440">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="2dcd0-440">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="2dcd0-441">Google 문서, 스프레드시트 및 슬라이드(파일이 동등한 Office 형식으로 변환됨 / 10MB 초과하는 파일 포함)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-441">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="2dcd0-442">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="2dcd0-442">File and folder structure</span></span> </li>
<li> <span data-ttu-id="2dcd0-443">사용자 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="2dcd0-443">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2dcd0-444">그룹 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="2dcd0-444">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2dcd0-445">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="2dcd0-445">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="2dcd0-446">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="2dcd0-446">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="2dcd0-447">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="2dcd0-447">Created date</span></span> </li>
<li> <span data-ttu-id="2dcd0-448">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="2dcd0-448">Modified date</span></span> </li>
<li> <span data-ttu-id="2dcd0-449">만든 사람</span><span class="sxs-lookup"><span data-stu-id="2dcd0-449">Created by</span></span> </li>
<li> <span data-ttu-id="2dcd0-450">마지막 수정 날짜</span><span class="sxs-lookup"><span data-stu-id="2dcd0-450">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="2dcd0-451">공유 드라이브(폴더 및 파일)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-451">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="2dcd0-452">Google Drive 계정이 소유한 공유 콘텐츠를 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-452">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="2dcd0-453">소유권 기록, 이전 버전 및 메모</span><span class="sxs-lookup"><span data-stu-id="2dcd0-453">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="2dcd0-454">파일 및 폴더 설명, 폴더 색상</span><span class="sxs-lookup"><span data-stu-id="2dcd0-454">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="2dcd0-455">사용자 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="2dcd0-455">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="2dcd0-456">그룹 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="2dcd0-456">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="2dcd0-457">고급 메타 데이터</span><span class="sxs-lookup"><span data-stu-id="2dcd0-457">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="2dcd0-458">파일 잠금 특성</span><span class="sxs-lookup"><span data-stu-id="2dcd0-458">File lock attributes</span></span> </li>
<li> <span data-ttu-id="2dcd0-459">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="2dcd0-459">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="2dcd0-460">휴지통 항목</span><span class="sxs-lookup"><span data-stu-id="2dcd0-460">Trashed items</span></span> </li>
<li> <span data-ttu-id="2dcd0-461">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="2dcd0-461">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="2dcd0-462">차단되거나 비활성 상태인 사용자</span><span class="sxs-lookup"><span data-stu-id="2dcd0-462">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="2dcd0-463">Google Photos. Forms, Maps 및 기타 연결된 앱</span><span class="sxs-lookup"><span data-stu-id="2dcd0-463">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="2dcd0-464">Google 드로잉</span><span class="sxs-lookup"><span data-stu-id="2dcd0-464">Google Drawings</span></span> </li>
<li> <span data-ttu-id="2dcd0-465">조직 외부로 공유된 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="2dcd0-465">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="2dcd0-466">마이그레이션할 Google Drive 계정에서 소유하지 않은 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="2dcd0-466">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="2dcd0-467">외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>): Google Drive Admin 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-467">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="2dcd0-468">최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-468">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="2dcd0-469">공유 드라이브 구성원 권한(<strong>참고</strong>): Google Drive Admin 보고서를 사용하여 공유 드라이브 구성원 자격을 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-469">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="2dcd0-470">마이그레이션하기 전에 최종 사용자에게 대상에서 이러한 구성원 자격 설정을 구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-470">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="2dcd0-471">현재 <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online 제한 사항 및 제한 사항을 초과 하</span> 는 파일 또는 폴더</a> </span><span class="sxs-lookup"><span data-stu-id="2dcd0-471">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="2dcd0-472"><strong>Box(Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="2dcd0-472"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="2dcd0-473">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="2dcd0-473">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="2dcd0-474">문서</span><span class="sxs-lookup"><span data-stu-id="2dcd0-474">Documents</span></span> </li>
<li> <span data-ttu-id="2dcd0-475">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="2dcd0-475">File and folder structure</span></span> </li>
<li> <span data-ttu-id="2dcd0-476">사용자 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="2dcd0-476">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2dcd0-477">그룹 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="2dcd0-477">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2dcd0-478">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="2dcd0-478">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="2dcd0-479">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="2dcd0-479">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="2dcd0-480">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="2dcd0-480">Created date</span></span> </li>
<li> <span data-ttu-id="2dcd0-481">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="2dcd0-481">Modified date</span></span> </li>
<li> <span data-ttu-id="2dcd0-482">만든 사람</span><span class="sxs-lookup"><span data-stu-id="2dcd0-482">Created by</span></span> </li>
<li> <span data-ttu-id="2dcd0-483">마지막 수정 날짜</span><span class="sxs-lookup"><span data-stu-id="2dcd0-483">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="2dcd0-484">Box 계정이 소유한 공유 콘텐츠가 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-484">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="2dcd0-485">소유권 기록, 이전 버전 및 메모</span><span class="sxs-lookup"><span data-stu-id="2dcd0-485">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="2dcd0-486">파일 및 폴더 설명</span><span class="sxs-lookup"><span data-stu-id="2dcd0-486">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="2dcd0-487">사용자 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="2dcd0-487">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="2dcd0-488">그룹 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="2dcd0-488">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="2dcd0-489">Box 태그와 고급 메타데이터</span><span class="sxs-lookup"><span data-stu-id="2dcd0-489">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="2dcd0-490">파일 잠금 특성</span><span class="sxs-lookup"><span data-stu-id="2dcd0-490">File lock attributes</span></span> </li>
<li> <span data-ttu-id="2dcd0-491">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="2dcd0-491">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="2dcd0-492">휴지통 항목</span><span class="sxs-lookup"><span data-stu-id="2dcd0-492">Trashed items</span></span> </li>
<li> <span data-ttu-id="2dcd0-493">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="2dcd0-493">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="2dcd0-494">차단되거나 비활성 상태인 사용자</span><span class="sxs-lookup"><span data-stu-id="2dcd0-494">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="2dcd0-495">Box 앱, 책갈피, 즐겨찾기 및 워크플로</span><span class="sxs-lookup"><span data-stu-id="2dcd0-495">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="2dcd0-496">마이그레이션된 상자 계정에서 소유하지 않은 콘텐츠입니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-496">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="2dcd0-497">외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>): Box 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-497">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="2dcd0-498">최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-498">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="2dcd0-499">현재 <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online 제한 사항 및 제한 사항을 초과 하</span> 는 파일 또는 폴더</a> </span><span class="sxs-lookup"><span data-stu-id="2dcd0-499">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="2dcd0-500"><strong>Teams용 Dropbox(표준 및 고급)</strong></span><span class="sxs-lookup"><span data-stu-id="2dcd0-500"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="2dcd0-501">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="2dcd0-501">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="2dcd0-502">문서</span><span class="sxs-lookup"><span data-stu-id="2dcd0-502">Documents</span></span> </li>
<li> <span data-ttu-id="2dcd0-503">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="2dcd0-503">File and folder structure</span></span> </li>
<li> <span data-ttu-id="2dcd0-504">사용자 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="2dcd0-504">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2dcd0-505">그룹 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="2dcd0-505">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2dcd0-506">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="2dcd0-506">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="2dcd0-507">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="2dcd0-507">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="2dcd0-508">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="2dcd0-508">Created date</span></span> </li>
<li> <span data-ttu-id="2dcd0-509">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="2dcd0-509">Modified date</span></span> </li>
<li> <span data-ttu-id="2dcd0-510">만든 사람</span><span class="sxs-lookup"><span data-stu-id="2dcd0-510">Created by</span></span> </li>
<li> <span data-ttu-id="2dcd0-511">마지막 수정 날짜</span><span class="sxs-lookup"><span data-stu-id="2dcd0-511">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="2dcd0-512">공유 팀 폴더 및 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="2dcd0-512">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="2dcd0-513">Dropbox 계정이 소유한 공유 콘텐츠가 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-513">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="2dcd0-514">소유권 기록, 이전 버전 및 메모</span><span class="sxs-lookup"><span data-stu-id="2dcd0-514">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="2dcd0-515">파일 및 폴더 설명</span><span class="sxs-lookup"><span data-stu-id="2dcd0-515">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="2dcd0-516">사용자 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="2dcd0-516">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="2dcd0-517">그룹 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="2dcd0-517">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="2dcd0-518">고급 메타 데이터</span><span class="sxs-lookup"><span data-stu-id="2dcd0-518">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="2dcd0-519">파일 잠금 특성</span><span class="sxs-lookup"><span data-stu-id="2dcd0-519">File lock attributes</span></span> </li>
<li> <span data-ttu-id="2dcd0-520">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="2dcd0-520">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="2dcd0-521">휴지통 항목</span><span class="sxs-lookup"><span data-stu-id="2dcd0-521">Trashed items</span></span> </li>
<li> <span data-ttu-id="2dcd0-522">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="2dcd0-522">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="2dcd0-523">연결 해제된 Dropbox 폴더</span><span class="sxs-lookup"><span data-stu-id="2dcd0-523">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="2dcd0-524">삭제되거나 연결이 끊어진 사용자</span><span class="sxs-lookup"><span data-stu-id="2dcd0-524">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="2dcd0-525">Dropbox Paper, Showcases 및 Spaces</span><span class="sxs-lookup"><span data-stu-id="2dcd0-525">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="2dcd0-526">Dropbox 앱 및 즐겨찾기(핀/별)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-526">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="2dcd0-527">마이그레이션된 Dropbox 계정이 소유하지 않은 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="2dcd0-527">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="2dcd0-528">외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>: Dropbox 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-528">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="2dcd0-529">최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="2dcd0-529">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="2dcd0-530">현재 <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online 제한 사항 및 제한 사항을 초과 하</span> 는 파일 또는 폴더</a> </span><span class="sxs-lookup"><span data-stu-id="2dcd0-530">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="2dcd0-531">FastTrack 책임</span><span class="sxs-lookup"><span data-stu-id="2dcd0-531">FastTrack responsibilities</span></span>

<span data-ttu-id="2dcd0-532">Microsoft의 FastTrack 전문가는 마이그레이션 프로젝트 중에 표준 작업을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-532">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="2dcd0-533">자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-533">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="2dcd0-534">귀하의 책임</span><span class="sxs-lookup"><span data-stu-id="2dcd0-534">Your responsibilities</span></span>

<span data-ttu-id="2dcd0-535">마이그레이션 프로젝트 중에 표준 작업을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-535">You perform standard activities during the migration project.</span></span> <span data-ttu-id="2dcd0-536">자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-536">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="2dcd0-537">또한 비즈니스용 OneDrive 마이그레이션과 관련된 다음 작업도 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-537">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="2dcd0-538">마이그레이션 이벤트의 대상이 되는 비즈니스 사이트를 위해 모든 OneDrive를 프로비저닝합니다.</span><span class="sxs-lookup"><span data-stu-id="2dcd0-538">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
