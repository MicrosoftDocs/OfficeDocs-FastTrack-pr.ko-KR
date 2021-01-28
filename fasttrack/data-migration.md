---
title: 데이터 마이그레이션
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/27/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack은 원본 환경의 메일 및 파일 데이터를 Office 365(Exchange Online, SharePoint Online 및 비즈니스용 OneDrive)로 마이그레이션하는 데 도움이 됩니다. Microsoft가 제공하는 지원 유형은 Office 365 라이선스 수에 따라 다릅니다.
ms.openlocfilehash: 0ecfdfab7c7f7ae8879ea6374c3560dcaeb2f283
ms.sourcegitcommit: cd8426ce64dda56439933576e7da75b1c27f5de1
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/27/2021
ms.locfileid: "50016474"
---
# <a name="data-migration"></a><span data-ttu-id="9e421-104">데이터 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="9e421-104">Data Migration</span></span>

<span data-ttu-id="9e421-105">FastTrack은 원본 환경의 메일 및 파일 데이터를 Office 365(Exchange Online, SharePoint Online 및 비즈니스용 OneDrive)로 마이그레이션하는 데 도움이 됩니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="9e421-106">Microsoft가 제공하는 지원 유형은 Office 365 라이선스 수에 따라 달라집니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="9e421-107">**150-499 라이선스를 보유한 Office 365 테넌트**: FastTrack은 마이그레이션 안내만 제공하며 데이터 마이그레이션을 수행해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="9e421-108">셀프 서비스 마이그레이션을 수행하기 위해 무료 도구를 계획하고 사용하는 데 도움이 되는 문서를 안내합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="9e421-109">**라이선스가 500개 이상인 Office 365 테넌트**: FastTrack은 마이그레이션 안내 및 데이터 마이그레이션 서비스를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="9e421-110">Microsoft는 마이그레이션 계획, 소스 환경 및 Office 365 테넌트 구성, 데이터 마이그레이션 서비스를 활용하여 데이터를 마이그레이션하는 데 도움이 되는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="9e421-111">마이그레이션 이벤트를 생성하고 예약합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-111">You create and schedule your migration events.</span></span> <span data-ttu-id="9e421-112">스케줄에 따라 마이그레이션 이벤트를 시작하고 진행률을 모니터링하며 상태 보고서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="9e421-113">2017년 9월 1일 이전에 상업용 계획을 구입하거나 갱신한 경우 데이터 마이그레이션 서비스를 받으려면 150개의 라이선스만 있으면 됩니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="9e421-114">교육 계획의 경우 유급 직원 및 직원 라이선스만 데이터 마이그레이션 서비스를 받을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="9e421-115">고려 사항</span><span class="sxs-lookup"><span data-stu-id="9e421-115">Considerations</span></span>

  - <span data-ttu-id="9e421-116">Office 365로 데이터를 마이그레이션하려면 소스 환경이 특정 기대치를 충족해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="9e421-117">Exchange, SharePoint 및 비즈니스용 OneDrive에 대한 소스 환경에 대한 자세한 내용은 [제품 및 기능](products-and-capabilities.md)을 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="9e421-118">데이터 마이그레이션 서비스를 제공하려면 소스 환경과 Office 365 테넌트에 대한 적절한 액세스 및 사용 권한이 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="9e421-119">Microsoft의 데이터 마이그레이션 서비스는 특별한 법적 또는 규제 요건에 따른 데이터용으로 설계되거나 설계되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="9e421-120">데이터를 마이그레이션할 때 FastTrack 마이그레이션 프로젝트에 별도로 제공된 경우를 제외하고, 이 데이터는 시설을 유지하는 모든 위치로 전송, 저장 및 처리될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="9e421-121">메일 또는 파일 마이그레이션 속도를 보장할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="9e421-122">소스 환경에서 읽을 수 없거나 손상된 항목과 같은 예기치 않은 문제로 인해 일부 데이터 항목을 마이그레이션하지 못할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="9e421-123">외부 요인(예: 타사 API(응용 프로그램 프로그래밍 인터페이스) 변경)은 데이터 마이그레이션 서비스의 변경, 지연 또는 중단으로 이어질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="9e421-124">마이그레이션 서비스를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-124">Migration service availability</span></span>

  - <span data-ttu-id="9e421-125">**상업 및 영국 정부 고객:** 당사는 24시간, 주 7일(24x7) 데이터 마이그레이션 서비스를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="9e421-126">**미국 정부/DOD 고객:** 당사는 하루 24시간, 주 5일 영업일(24x5) 데이터 마이그레이션 서비스를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="9e421-127">Exchange Online으로 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="9e421-127">Migration to Exchange Online</span></span>

<span data-ttu-id="9e421-128">FastTrack을 사용하여 Exchange Online으로 이메일을 마이그레이션하도록 선택하면 마이그레이션 안내 및 데이터 마이그레이션 서비스를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="9e421-129">Microsoft는 마이그레이션을 계획하고, 소스 환경과 Exchange Online을 구성하고, 데이터 마이그레이션 서비스를 활용하여 편지함을 마이그레이션하는 데 도움이 되는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="9e421-130">마이그레이션 이벤트를 생성하고 예약합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-130">You create and schedule your migration events.</span></span> <span data-ttu-id="9e421-131">스케줄에 따라 마이그레이션 이벤트를 시작하고 진행률을 모니터링하며 상태 보고서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="9e421-132">마이그레이션 이벤트가 완료되면 해당 소스 환경의 적절한 예약 및 적격 소스 사서함에서 온 메일이 Exchange Online으로 마이그레이션될 것으로 예상할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="9e421-133">고려 사항</span><span class="sxs-lookup"><span data-stu-id="9e421-133">Considerations</span></span>

  - <span data-ttu-id="9e421-134">마이그레이션하기 전에 Exchange Online용 FastTrack 코어 온보딩을 완료해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="9e421-135">직접 온보드 탑재를 수행한 경우 필요한 검사 및 필수 구성 요소를 통과해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="9e421-136">자세한 내용은 [제품 및 기능](products-and-capabilities.md)을(를) 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="9e421-137">FastTrack은 활성 Office 365 사서함으로만 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="9e421-138">온-프레미스 Exchange 환경에서 마이그레이션하려면 특정 요구 사항을 충족해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="9e421-139">자세한 내용은 [하이브리드 배포 필수 구성 요소](https://go.microsoft.com/fwlink/?LinkId=787528)를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="9e421-140">각 소스 환경은 소스 환경의 각 제품에 대한 최신 서비스 팩(SP) 및 롤업(RU)/누적 업데이트(CU) 레벨에 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="9e421-141">사내 Active Directory에 있는 메일 그룹(*MailEnabledGroup* 개체) 및 외부 연락처(*MailEnableContact* 개체)는 사서함 데이터 마이그레이션의 일부가 아닙니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="9e421-142">그러나 Azure AD(Azure Active Directory) 연결을 사용하여 동기화할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="9e421-143">원본 환경</span><span class="sxs-lookup"><span data-stu-id="9e421-143">Source environments</span></span>

<span data-ttu-id="9e421-144">Microsoft의 데이터 마이그레이션 서비스는 다음과 같은 소스 환경에서 데이터를 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="9e421-145">Exchange 조직이 하나 또는 여러 개인 Active Directory 포리스트(각 Exchange 메일 시스템은 Exchange 2010 이상이어야 함)입니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="9e421-146">단일 IMAP 지원 전자 메일 환경</span><span class="sxs-lookup"><span data-stu-id="9e421-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="9e421-147">G Suite 환경(Gmail, 연락처 및 Outlook 일정만 해당)입니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="9e421-148">다음 표에서는 각 소스 환경에 대한 마이그레이션 세부 정보를 보여 줍니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="9e421-149"><strong>원본 환경</strong></span><span class="sxs-lookup"><span data-stu-id="9e421-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="9e421-150"><strong>마이그레이션 유형</strong></span><span class="sxs-lookup"><span data-stu-id="9e421-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="9e421-151"><strong>마이그레이트 대상</strong></span><span class="sxs-lookup"><span data-stu-id="9e421-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="9e421-152"><strong>마이그레이션되지 않는 사항</strong></span><span class="sxs-lookup"><span data-stu-id="9e421-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="9e421-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="9e421-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="9e421-154">
<strong>참고:</strong> On-premises Exchange 종속성에 대한 자세한 내용은 하이브리드 배포 선행 <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">구성을 참조합니다.</span></a></span><span class="sxs-lookup"><span data-stu-id="9e421-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="9e421-155">하이브리드 배포를 사용하는 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="9e421-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="9e421-156">전자 메일</span><span class="sxs-lookup"><span data-stu-id="9e421-156">Emails</span></span></li>
<li><span data-ttu-id="9e421-157">서버 쪽 사서함 규칙</span><span class="sxs-lookup"><span data-stu-id="9e421-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="9e421-158">위임</span><span class="sxs-lookup"><span data-stu-id="9e421-158">Delegates</span></span></li>
<li><span data-ttu-id="9e421-159">사서함 연락처</span><span class="sxs-lookup"><span data-stu-id="9e421-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="9e421-160">일정</span><span class="sxs-lookup"><span data-stu-id="9e421-160">Calendar</span></span> </li>
<li> <span data-ttu-id="9e421-161">작업</span><span class="sxs-lookup"><span data-stu-id="9e421-161">Tasks</span></span> </li>
<li> <span data-ttu-id="9e421-162">권한 관리 전자 메일</span><span class="sxs-lookup"><span data-stu-id="9e421-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="9e421-163">암호화된 전자 메일</span><span class="sxs-lookup"><span data-stu-id="9e421-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="9e421-164">서명</span><span class="sxs-lookup"><span data-stu-id="9e421-164">Signatures</span></span> </li>
<li> <span data-ttu-id="9e421-165">사용자 사서함과 함께 마이그레이션된 개인 보관 파일</span><span class="sxs-lookup"><span data-stu-id="9e421-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="9e421-166">복구 가능한 항목</span><span class="sxs-lookup"><span data-stu-id="9e421-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="9e421-167">공용 폴더</span><span class="sxs-lookup"><span data-stu-id="9e421-167">Public folders</span></span> </li>
<li> <span data-ttu-id="9e421-168">메시지 크기 제한을 초과하는 모든 전자 메일</span><span class="sxs-lookup"><span data-stu-id="9e421-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="9e421-169">저널링 보관 또는 모든 타사 보관 솔루션</span><span class="sxs-lookup"><span data-stu-id="9e421-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="9e421-170">차단되거나 비활성 상태인 사용자</span><span class="sxs-lookup"><span data-stu-id="9e421-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="9e421-171">PST(Personal Storage Table) 파일의 보관 데이터</span><span class="sxs-lookup"><span data-stu-id="9e421-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="9e421-172">손상된 항목</span><span class="sxs-lookup"><span data-stu-id="9e421-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="9e421-173">비활성 사서함</span><span class="sxs-lookup"><span data-stu-id="9e421-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="9e421-174">클라이언트 쪽 사서함 규칙</span><span class="sxs-lookup"><span data-stu-id="9e421-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="9e421-175"><strong>G 제품군 환경(Gmail, 연락처 및 캘린더만)</strong></span><span class="sxs-lookup"><span data-stu-id="9e421-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="9e421-176">
<strong>참고:</strong> G Suite 환경은 G Suite 마이그레이션 수행에 설명된 선행 요구 <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">사항을 충족해야 합니다.</a></span><span class="sxs-lookup"><span data-stu-id="9e421-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="9e421-177">단독형 또는 미리 구성</span><span class="sxs-lookup"><span data-stu-id="9e421-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="9e421-178">전자 메일</span><span class="sxs-lookup"><span data-stu-id="9e421-178">Emails</span></span> </li>
<li> <span data-ttu-id="9e421-179">사서함 연락처(연락처당 최대 3개의 전자 메일 주소가 마이그레이션됨)</span><span class="sxs-lookup"><span data-stu-id="9e421-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="9e421-180">일정</span><span class="sxs-lookup"><span data-stu-id="9e421-180">Calendar</span></span> </li>
<li> <span data-ttu-id="9e421-181">레이블</span><span class="sxs-lookup"><span data-stu-id="9e421-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="9e421-182">규칙</span><span class="sxs-lookup"><span data-stu-id="9e421-182">Rules</span></span> </li>
<li> <span data-ttu-id="9e421-183">위임</span><span class="sxs-lookup"><span data-stu-id="9e421-183">Delegates</span></span> </li>
<li> <span data-ttu-id="9e421-184">서명</span><span class="sxs-lookup"><span data-stu-id="9e421-184">Signatures</span></span> </li>
<li> <span data-ttu-id="9e421-185">작업</span><span class="sxs-lookup"><span data-stu-id="9e421-185">Tasks</span></span> </li>
<li> <span data-ttu-id="9e421-186">메시지 크기 제한을 초과하는 모든 전자 메일 또는 첨부 파일</span><span class="sxs-lookup"><span data-stu-id="9e421-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="9e421-187">차단되거나 비활성 상태인 사용자</span><span class="sxs-lookup"><span data-stu-id="9e421-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="9e421-188">PST 파일 또는 모든 타사 보관 솔루션(예: Google Vault)의 보관 데이터</span><span class="sxs-lookup"><span data-stu-id="9e421-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="9e421-189">권한 관리 또는 암호화된 전자 메일</span><span class="sxs-lookup"><span data-stu-id="9e421-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="9e421-190">손상된 항목</span><span class="sxs-lookup"><span data-stu-id="9e421-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="9e421-191">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="9e421-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="9e421-192">Google Groups</span><span class="sxs-lookup"><span data-stu-id="9e421-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="9e421-193">리소스 사서함</span><span class="sxs-lookup"><span data-stu-id="9e421-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="9e421-194">비활성 사서함</span><span class="sxs-lookup"><span data-stu-id="9e421-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="9e421-195">휴가 설정 및 자동 회신 설정</span><span class="sxs-lookup"><span data-stu-id="9e421-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="9e421-196">공유 일정, 클라우드 첨부 파일, Google Hangout 링크, 이벤트 색상</span><span class="sxs-lookup"><span data-stu-id="9e421-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="9e421-197">\*\*라벨로 저장된 행아웃 대화를 마이그레이트합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="9e421-198"><strong>IMAP4 원본(Domino, GroupWise 또는 Zimbra 등)</strong></span><span class="sxs-lookup"><span data-stu-id="9e421-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="9e421-199">기본 IMAP4 도구를 사용한 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="9e421-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="9e421-200">전자 메일</span><span class="sxs-lookup"><span data-stu-id="9e421-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="9e421-201">규칙</span><span class="sxs-lookup"><span data-stu-id="9e421-201">Rules</span></span> </li>
<li> <span data-ttu-id="9e421-202">위임</span><span class="sxs-lookup"><span data-stu-id="9e421-202">Delegates</span></span> </li>
<li> <span data-ttu-id="9e421-203">메일 그룹</span><span class="sxs-lookup"><span data-stu-id="9e421-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="9e421-204">외부 연락처</span><span class="sxs-lookup"><span data-stu-id="9e421-204">External contacts</span></span> </li>
<li> <span data-ttu-id="9e421-205">메일을 사용하는 사용자</span><span class="sxs-lookup"><span data-stu-id="9e421-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="9e421-206">차단되거나 비활성 상태인 사용자</span><span class="sxs-lookup"><span data-stu-id="9e421-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="9e421-207">사서함 연락처</span><span class="sxs-lookup"><span data-stu-id="9e421-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="9e421-208">일정</span><span class="sxs-lookup"><span data-stu-id="9e421-208">Calendar</span></span> </li>
<li> <span data-ttu-id="9e421-209">서명</span><span class="sxs-lookup"><span data-stu-id="9e421-209">Signatures</span></span> </li>
<li> <span data-ttu-id="9e421-210">작업</span><span class="sxs-lookup"><span data-stu-id="9e421-210">Tasks</span></span> </li>
<li> <span data-ttu-id="9e421-211">메시지 크기 제한을 초과하는 모든 전자 메일</span><span class="sxs-lookup"><span data-stu-id="9e421-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="9e421-212">보관 데이터</span><span class="sxs-lookup"><span data-stu-id="9e421-212">Archive data</span></span> </li>
<li> <span data-ttu-id="9e421-213">암호화된 전자 메일</span><span class="sxs-lookup"><span data-stu-id="9e421-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="9e421-214">손상된 항목</span><span class="sxs-lookup"><span data-stu-id="9e421-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="9e421-215">비활성 사서함</span><span class="sxs-lookup"><span data-stu-id="9e421-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="9e421-216">FastTrack 책임</span><span class="sxs-lookup"><span data-stu-id="9e421-216">FastTrack responsibilities</span></span>

<span data-ttu-id="9e421-217">Microsoft의 FastTrack 전문가는 마이그레이션 프로젝트 중에 표준 작업을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="9e421-218">자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="9e421-219">또한 Microsoft의 FastTrack 전문가는 Exchange 마이그레이션과 관련된 다음과 같은 활동을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="9e421-220">해당하는 경우 원본 환경과 Exchange 온라인 간에 SMTP 메일 라우팅 공존을 사용하도록 설정하는 데 도움이 되는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="9e421-221">귀하의 책임</span><span class="sxs-lookup"><span data-stu-id="9e421-221">Your responsibilities</span></span>

<span data-ttu-id="9e421-222">마이그레이션 프로젝트 중에 표준 작업을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="9e421-223">자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="9e421-224">Exchange 마이그레이션과 관련된 다음 작업도 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="9e421-225">Exchange Online용 FastTrack 코어 온보딩을 완료합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="9e421-226">직접 온보드 탑재를 수행한 경우 필요한 검사 및 필수 구성 요소를 통과해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="9e421-227">자세한 내용은 [제품 및 기능](products-and-capabilities.md)을(를) 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="9e421-228">Office 365 지침에 따라 적절한 수준의 클라이언트 소프트웨어를 설치합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="9e421-229">자세한 내용은 [최신 작업 공간](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="9e421-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="9e421-230">사내 Exchange 환경에서 마이그레이션하려는 경우 특정 요구 사항을 충족합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="9e421-231">자세한 내용은 [하이브리드 배포 필수 구성 요소](https://go.microsoft.com/fwlink/?LinkId=787528)를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="9e421-232">해당되는 경우 각 소스 환경이 최신 서비스 팩(SP) 및 롤업(RU)/누적 업데이트(CU) 레벨에 있는지 확인합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="9e421-233">해당되는 경우 원본 환경과 Exchange 온라인 간의 SMTP 메일 라우팅 공존을 구성하고 검증합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="9e421-234">원본 사서함 크기가 대상 사서함 할당량을 초과하지 않도록 합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="9e421-235">원본 플랫폼에 따라 소스 데이터를 대상 사서함 할당량의 85%로 제한해야 할 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="9e421-236">필요한 경우 클라이언트 측 데이터를 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="9e421-237">여기에는 로컬 주소록, 로컬 PST 파일의 데이터, Outlook 규칙 및 로컬 Outlook 설정이 포함되지만 이에 국한되지는 않습니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="9e421-238">최종 사용자가 클라이언트 측 마이그레이션 문제를 해결할 수 있도록 지원합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="9e421-239">SharePoint Online으로 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="9e421-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="9e421-240">FastTrack을 사용하여 SharePoint Online으로 파일을 마이그레이션하도록 선택하면 마이그레이션 안내 및 데이터 마이그레이션 서비스를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="9e421-241">Microsoft는 마이그레이션 계획, 소스 환경 및 SharePoint 온라인 구성, 데이터 마이그레이션 서비스를 활용하여 파일을 마이그레이션하는 데 도움이 되는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="9e421-242">마이그레이션 이벤트를 생성하고 예약합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-242">You create and schedule your migration events.</span></span> <span data-ttu-id="9e421-243">스케줄에 따라 마이그레이션 이벤트를 시작하고 진행률을 모니터링하며 상태 보고서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="9e421-244">마이그레이션 이벤트가 완료되면 적절한 예약 소스 및 적합한 소스 소스의 파일이 SharePoint 온라인으로 마이그레이션될 것으로 예상할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="9e421-245">고려 사항</span><span class="sxs-lookup"><span data-stu-id="9e421-245">Considerations</span></span>

  - <span data-ttu-id="9e421-246">모든 마이그레이션은 SharePoint 온라인 할당량을 따릅니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="9e421-247">자세한 내용은 [<span class="underline">SharePoint 온라인 및 OneDrive for Business: 소프트웨어 경계 및 제한</span>](https://go.microsoft.com/fwlink/?LinkId=698855)을(를) 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-247">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="9e421-248">전체 마이그레이션 양을 사용 권한이 있는 전체 SharePoint 온라인 스토리지 할당량의 75%로 제한하는 것이 좋습니다(별도로 구입한 추가 스토리지 포함).</span><span class="sxs-lookup"><span data-stu-id="9e421-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="9e421-249">소스 환경 세부 정보</span><span class="sxs-lookup"><span data-stu-id="9e421-249">Source environment details</span></span>

<span data-ttu-id="9e421-250">Microsoft의 데이터 마이그레이션 서비스는 다음과 같은 소스 환경에서 데이터를 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="9e421-251">파일 공유(SMB 2.0 이상 지원 장치에서 SMB(서버 메시지 블록) 파일 공유).</span><span class="sxs-lookup"><span data-stu-id="9e421-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="9e421-252">단일 G 제품군 환경(Google Drive만 해당)</span><span class="sxs-lookup"><span data-stu-id="9e421-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="9e421-253">Box(Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="9e421-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="9e421-254">Teams용 Dropbox (표준 및 고급)</span><span class="sxs-lookup"><span data-stu-id="9e421-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="9e421-255">다음 표에서는 각 소스 환경에 대한 마이그레이션 세부 정보를 보여 줍니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="9e421-256"><strong>원본 환경</strong></span><span class="sxs-lookup"><span data-stu-id="9e421-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="9e421-257"><strong>마이그레이션 유형</strong></span><span class="sxs-lookup"><span data-stu-id="9e421-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="9e421-258"><strong>마이그레이트 대상</strong></span><span class="sxs-lookup"><span data-stu-id="9e421-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="9e421-259"><strong>마이그레이션되지 않는 사항</strong></span><span class="sxs-lookup"><span data-stu-id="9e421-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="9e421-260"><strong>SMB 2.0 이상을 지원하는 모든 파일 공유 장치</strong></span><span class="sxs-lookup"><span data-stu-id="9e421-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="9e421-261">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="9e421-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="9e421-262">문서</span><span class="sxs-lookup"><span data-stu-id="9e421-262">Documents</span></span> </li>
<li> <span data-ttu-id="9e421-263">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="9e421-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="9e421-264">사용자 수준 파일 및 폴더 권한\*</span><span class="sxs-lookup"><span data-stu-id="9e421-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="9e421-265">그룹 수준 파일 및 폴더 권한\*</span><span class="sxs-lookup"><span data-stu-id="9e421-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="9e421-266">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="9e421-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="9e421-267">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="9e421-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="9e421-268">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="9e421-268">Created date</span></span> </li>
<li> <span data-ttu-id="9e421-269">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="9e421-269">Modified date</span></span> </li>
<li> <span data-ttu-id="9e421-270">만든 사람</span><span class="sxs-lookup"><span data-stu-id="9e421-270">Created by</span></span> </li>
<li> <span data-ttu-id="9e421-271">마지막 수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="9e421-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="9e421-272">\* 디렉터리 동기화 구성이 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="9e421-273">Windows 파일 탐색기에 표시된 NTFS 권한만 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="9e421-274">파일 공유 장치에서 직접 관리되는 사용 권한은 마이그레이션되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="9e421-275">데이터가 SMB 2.0 장치에 저장된 경우 SMB 프로토콜에 의해 노출된 NTFS 동등 사용 권한이 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="9e421-276">소유권 기록 및 이전 버전</span><span class="sxs-lookup"><span data-stu-id="9e421-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="9e421-277">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="9e421-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="9e421-278">이전 버전</span><span class="sxs-lookup"><span data-stu-id="9e421-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="9e421-279">Windows 파일 및 폴더 특성(예: 읽기 전용 및 숨김)</span><span class="sxs-lookup"><span data-stu-id="9e421-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="9e421-280">Windows가 아닌 NTFS(New Technology File System) 및 NTFS 고급 사용 권한 및 특수 설정:</span><span class="sxs-lookup"><span data-stu-id="9e421-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="9e421-281">명시적 거부 사용 권한(마이그레이션 후 제거됨, 콘텐츠는 병렬 사용 권한 또는 상위 폴더의 사용 권한에 따름)</span><span class="sxs-lookup"><span data-stu-id="9e421-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="9e421-282">NTFS 감사 구성</span><span class="sxs-lookup"><span data-stu-id="9e421-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="9e421-283">FCI(파일 분류 인프라)에 의해 제공되는 추가 파일 메타데이터</span><span class="sxs-lookup"><span data-stu-id="9e421-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="9e421-284">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="9e421-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="9e421-285">숨겨진 공유</span><span class="sxs-lookup"><span data-stu-id="9e421-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="9e421-286">공유(예: 공유 수준에 부여된 사용 권한)</span><span class="sxs-lookup"><span data-stu-id="9e421-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="9e421-287">현재 SharePoint Online 제한 사항을 초과하는 파일 또는 <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">폴더</span></a> </span><span class="sxs-lookup"><span data-stu-id="9e421-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="9e421-288"><strong>단일 G 제품군 환경(Google Drive만 해당)</strong></span><span class="sxs-lookup"><span data-stu-id="9e421-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="9e421-289">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="9e421-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="9e421-290">Google 문서, 스프레드시트 및 슬라이드(파일이 동등한 Office 형식으로 변환됨 / 10MB 초과하는 파일 포함)</span><span class="sxs-lookup"><span data-stu-id="9e421-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="9e421-291">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="9e421-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="9e421-292">사용자 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="9e421-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9e421-293">그룹 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="9e421-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9e421-294">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="9e421-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="9e421-295">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="9e421-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="9e421-296">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="9e421-296">Created date</span></span> </li>
<li> <span data-ttu-id="9e421-297">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="9e421-297">Modified date</span></span> </li>
<li> <span data-ttu-id="9e421-298">만든 사람</span><span class="sxs-lookup"><span data-stu-id="9e421-298">Created by</span></span> </li>
<li> <span data-ttu-id="9e421-299">마지막 수정 날짜</span><span class="sxs-lookup"><span data-stu-id="9e421-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="9e421-300">공유 드라이브(폴더 및 파일)</span><span class="sxs-lookup"><span data-stu-id="9e421-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="9e421-301">Google Drive 계정이 소유한 공유 콘텐츠를 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="9e421-302">소유권 기록, 이전 버전 및 메모</span><span class="sxs-lookup"><span data-stu-id="9e421-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="9e421-303">파일 및 폴더 설명, 폴더 색상</span><span class="sxs-lookup"><span data-stu-id="9e421-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="9e421-304">사용자 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="9e421-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="9e421-305">그룹 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="9e421-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="9e421-306">고급 메타 데이터</span><span class="sxs-lookup"><span data-stu-id="9e421-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="9e421-307">파일 잠금 특성</span><span class="sxs-lookup"><span data-stu-id="9e421-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="9e421-308">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="9e421-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="9e421-309">휴지통 항목</span><span class="sxs-lookup"><span data-stu-id="9e421-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="9e421-310">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="9e421-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="9e421-311">차단되거나 비활성 상태인 사용자</span><span class="sxs-lookup"><span data-stu-id="9e421-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="9e421-312">Google Photos. Forms, Maps 및 기타 연결된 앱</span><span class="sxs-lookup"><span data-stu-id="9e421-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="9e421-313">Google 드로잉</span><span class="sxs-lookup"><span data-stu-id="9e421-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="9e421-314">조직 외부로 공유된 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="9e421-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="9e421-315">마이그레이션할 Google Drive 계정에서 소유하지 않은 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="9e421-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="9e421-316">외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>): Google Drive Admin 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="9e421-317">최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="9e421-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="9e421-318">공유 드라이브 구성원 권한(<strong>참고</strong>): Google Drive Admin 보고서를 사용하여 공유 드라이브 구성원 자격을 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="9e421-319">마이그레이션하기 전에 최종 사용자에게 대상에서 이러한 구성원 자격 설정을 구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="9e421-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="9e421-320">제한된 파일 또는 복사할 수 없는 것으로 표시된 파일</span><span class="sxs-lookup"><span data-stu-id="9e421-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="9e421-321">현재 SharePoint Online 제한 사항을 초과하는 파일 또는 <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">폴더</span></a> </span><span class="sxs-lookup"><span data-stu-id="9e421-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="9e421-322"><strong>Box(Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="9e421-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="9e421-323">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="9e421-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="9e421-324">문서</span><span class="sxs-lookup"><span data-stu-id="9e421-324">Documents</span></span> </li>
<li> <span data-ttu-id="9e421-325">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="9e421-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="9e421-326">사용자 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="9e421-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9e421-327">그룹 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="9e421-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9e421-328">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="9e421-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="9e421-329">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="9e421-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="9e421-330">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="9e421-330">Created date</span></span> </li>
<li> <span data-ttu-id="9e421-331">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="9e421-331">Modified date</span></span> </li>
<li> <span data-ttu-id="9e421-332">만든 사람</span><span class="sxs-lookup"><span data-stu-id="9e421-332">Created by</span></span> </li>
<li> <span data-ttu-id="9e421-333">마지막 수정 날짜</span><span class="sxs-lookup"><span data-stu-id="9e421-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="9e421-334">Box 계정이 소유한 공유 콘텐츠가 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="9e421-335">Box Notes(Word 문서 형식으로 변환)</span><span class="sxs-lookup"><span data-stu-id="9e421-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="9e421-336">소유권 기록, 이전 버전 및 메모</span><span class="sxs-lookup"><span data-stu-id="9e421-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="9e421-337">파일 및 폴더 설명</span><span class="sxs-lookup"><span data-stu-id="9e421-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="9e421-338">사용자 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="9e421-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="9e421-339">그룹 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="9e421-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="9e421-340">Box 태그와 고급 메타데이터</span><span class="sxs-lookup"><span data-stu-id="9e421-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="9e421-341">파일 잠금 특성</span><span class="sxs-lookup"><span data-stu-id="9e421-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="9e421-342">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="9e421-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="9e421-343">휴지통 항목</span><span class="sxs-lookup"><span data-stu-id="9e421-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="9e421-344">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="9e421-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="9e421-345">차단되거나 비활성 상태인 사용자</span><span class="sxs-lookup"><span data-stu-id="9e421-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="9e421-346">Box 앱, 책갈피, 즐겨찾기 및 워크플로</span><span class="sxs-lookup"><span data-stu-id="9e421-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="9e421-347">마이그레이션된 상자 계정에서 소유하지 않은 콘텐츠입니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="9e421-348">외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>): Box 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="9e421-349">최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="9e421-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="9e421-350">현재 SharePoint Online 제한 사항을 초과하는 파일 또는 <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">폴더</span></a> </span><span class="sxs-lookup"><span data-stu-id="9e421-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="9e421-351"><strong>Teams용 Dropbox(표준 및 고급)</strong></span><span class="sxs-lookup"><span data-stu-id="9e421-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="9e421-352">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="9e421-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="9e421-353">문서</span><span class="sxs-lookup"><span data-stu-id="9e421-353">Documents</span></span> </li>
<li> <span data-ttu-id="9e421-354">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="9e421-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="9e421-355">사용자 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="9e421-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9e421-356">그룹 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="9e421-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9e421-357">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="9e421-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="9e421-358">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="9e421-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="9e421-359">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="9e421-359">Created date</span></span> </li>
<li> <span data-ttu-id="9e421-360">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="9e421-360">Modified date</span></span> </li>
<li> <span data-ttu-id="9e421-361">만든 사람</span><span class="sxs-lookup"><span data-stu-id="9e421-361">Created by</span></span> </li>
<li> <span data-ttu-id="9e421-362">마지막 수정 날짜</span><span class="sxs-lookup"><span data-stu-id="9e421-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="9e421-363">공유 팀 폴더 및 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="9e421-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="9e421-364">Dropbox 계정이 소유한 공유 콘텐츠가 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="9e421-365">소유권 기록, 이전 버전 및 메모</span><span class="sxs-lookup"><span data-stu-id="9e421-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="9e421-366">파일 및 폴더 설명</span><span class="sxs-lookup"><span data-stu-id="9e421-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="9e421-367">사용자 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="9e421-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="9e421-368">그룹 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="9e421-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="9e421-369">고급 메타 데이터</span><span class="sxs-lookup"><span data-stu-id="9e421-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="9e421-370">파일 잠금 특성</span><span class="sxs-lookup"><span data-stu-id="9e421-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="9e421-371">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="9e421-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="9e421-372">휴지통 항목</span><span class="sxs-lookup"><span data-stu-id="9e421-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="9e421-373">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="9e421-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="9e421-374">연결 해제된 Dropbox 폴더</span><span class="sxs-lookup"><span data-stu-id="9e421-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="9e421-375">삭제되거나 연결이 끊어진 사용자</span><span class="sxs-lookup"><span data-stu-id="9e421-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="9e421-376">Dropbox Paper, Showcases 및 Spaces</span><span class="sxs-lookup"><span data-stu-id="9e421-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="9e421-377">Dropbox 앱 및 즐겨찾기(핀/별)</span><span class="sxs-lookup"><span data-stu-id="9e421-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="9e421-378">마이그레이션된 Dropbox 계정이 소유하지 않은 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="9e421-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="9e421-379">외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>: Dropbox 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="9e421-380">최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="9e421-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="9e421-381">현재 SharePoint Online 제한 사항을 초과하는 파일 또는 <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">폴더</span></a> </span><span class="sxs-lookup"><span data-stu-id="9e421-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="9e421-382">FastTrack 책임</span><span class="sxs-lookup"><span data-stu-id="9e421-382">FastTrack responsibilities</span></span>

<span data-ttu-id="9e421-383">Microsoft의 FastTrack 전문가는 마이그레이션 프로젝트 중에 표준 작업을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="9e421-384">자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="9e421-385">귀하의 책임</span><span class="sxs-lookup"><span data-stu-id="9e421-385">Your responsibilities</span></span>

<span data-ttu-id="9e421-386">마이그레이션 프로젝트 중에 표준 작업을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="9e421-387">자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="9e421-388">또한 SharePoint 온라인 마이그레이션과 관련된 다음 작업도 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="9e421-389">모든 SharePoint 팀 사이트를 마이그레이션 이벤트의 대상으로 프로비저닝합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="9e421-390">비즈니스용 OneDrive로 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="9e421-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="9e421-391">FastTrack을 사용하여 파일을 비즈니스용 OneDrive로 마이그레이션하도록 선택하면 마이그레이션 안내 및 데이터 마이그레이션 서비스를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="9e421-392">Microsoft는 마이그레이션 계획, 소스 환경 및 비즈니스용 OneDrive 구성, 데이터 마이그레이션 서비스를 활용하여 파일을 마이그레이션하는 데 도움이 되는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="9e421-393">마이그레이션 이벤트를 생성하고 예약합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-393">You create and schedule your migration events.</span></span> <span data-ttu-id="9e421-394">스케줄에 따라 마이그레이션 이벤트를 시작하고 진행률을 모니터링하며 상태 보고서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="9e421-395">마이그레이션 이벤트가 완료되면 적절한 소스 환경의 적절한 예약 소스 및 적합한 원본의 파일이 비즈니스용 OneDrive로 마이그레이션될 것으로 예상할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="9e421-396">고려 사항</span><span class="sxs-lookup"><span data-stu-id="9e421-396">Considerations</span></span>

  - <span data-ttu-id="9e421-397">모든 마이그레이션에는 비즈니스용 OneDrive 할당량이 적용됩니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-397">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="9e421-398">자세한 내용은 [<span class="underline">SharePoint Online 및 비즈니스용 OneDrive: 소프트웨어 경계 및 제한</span>](https://go.microsoft.com/fwlink/?LinkId=698855)을 참조하시기 바랍니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-398">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="9e421-399">마이그레이션하는 전체 데이터 양을 권한이 부여된 전체 SharePoint 온라인 스토리지 할당량의 75%로 제한하는 것이 좋습니다(별도로 구입한 추가 스토리지 포함).</span><span class="sxs-lookup"><span data-stu-id="9e421-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="9e421-400">FastTrack은 활성 비즈니스용 OneDrive 드라이브로만 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="9e421-401">소스 환경 세부 정보</span><span class="sxs-lookup"><span data-stu-id="9e421-401">Source environment details</span></span>

<span data-ttu-id="9e421-402">Microsoft의 데이터 마이그레이션 서비스는 다음과 같은 소스 환경에서 데이터를 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="9e421-403">파일 공유(SMB 2.0 이상 지원 장치에서 SMB 파일 공유)</span><span class="sxs-lookup"><span data-stu-id="9e421-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="9e421-404">단일 G 제품군 환경(Google Drive만 해당)</span><span class="sxs-lookup"><span data-stu-id="9e421-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="9e421-405">Box(Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="9e421-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="9e421-406">Teams용 Dropbox (표준 및 고급)</span><span class="sxs-lookup"><span data-stu-id="9e421-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="9e421-407">다음 표에서는 각 소스 환경에 대한 마이그레이션 세부 정보를 보여 줍니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="9e421-408"><strong>원본 환경</strong></span><span class="sxs-lookup"><span data-stu-id="9e421-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="9e421-409"><strong>마이그레이션 유형</strong></span><span class="sxs-lookup"><span data-stu-id="9e421-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="9e421-410"><strong>마이그레이트 대상</strong></span><span class="sxs-lookup"><span data-stu-id="9e421-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="9e421-411"><strong>마이그레이션되지 않는 사항</strong></span><span class="sxs-lookup"><span data-stu-id="9e421-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="9e421-412"><strong>SMB 2.0 이상을 지원하는 모든 파일 공유 장치</strong></span><span class="sxs-lookup"><span data-stu-id="9e421-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="9e421-413">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="9e421-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="9e421-414">문서</span><span class="sxs-lookup"><span data-stu-id="9e421-414">Documents</span></span> </li>
<li> <span data-ttu-id="9e421-415">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="9e421-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="9e421-416">사용자 수준 파일 및 폴더 권한\*</span><span class="sxs-lookup"><span data-stu-id="9e421-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="9e421-417">그룹 수준 파일 및 폴더 권한\*</span><span class="sxs-lookup"><span data-stu-id="9e421-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="9e421-418">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="9e421-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="9e421-419">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="9e421-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="9e421-420">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="9e421-420">Created date</span></span> </li>
<li> <span data-ttu-id="9e421-421">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="9e421-421">Modified date</span></span> </li>
<li> <span data-ttu-id="9e421-422">만든 사람</span><span class="sxs-lookup"><span data-stu-id="9e421-422">Created by</span></span> </li>
<li> <span data-ttu-id="9e421-423">마지막 수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="9e421-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="9e421-424">\* 디렉터리 동기화 구성이 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="9e421-425">Windows 파일 탐색기에 표시된 NTFS 권한만 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="9e421-426">파일 공유 장치에서 직접 관리되는 사용 권한은 마이그레이션되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="9e421-427">데이터가 SMB 2.0 장치에 저장된 경우 SMB 프로토콜에 의해 노출된 NTFS 동등 사용 권한이 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="9e421-428">소유권 기록 및 이전 버전</span><span class="sxs-lookup"><span data-stu-id="9e421-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="9e421-429">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="9e421-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="9e421-430">이전 버전</span><span class="sxs-lookup"><span data-stu-id="9e421-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="9e421-431">Windows 파일 및 폴더 특성(예: 읽기 전용 및 숨김)</span><span class="sxs-lookup"><span data-stu-id="9e421-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="9e421-432">Windows가 아닌 NTFS(New Technology File System) 및 NTFS 고급 사용 권한 및 특수 설정:</span><span class="sxs-lookup"><span data-stu-id="9e421-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="9e421-433">명시적 거부 사용 권한(마이그레이션 후 제거됨, 콘텐츠는 병렬 사용 권한 또는 상위 폴더의 사용 권한에 따름)</span><span class="sxs-lookup"><span data-stu-id="9e421-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="9e421-434">NTFS 감사 구성</span><span class="sxs-lookup"><span data-stu-id="9e421-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="9e421-435">FCI(파일 분류 인프라)에 의해 제공되는 추가 파일 메타데이터</span><span class="sxs-lookup"><span data-stu-id="9e421-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="9e421-436">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="9e421-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="9e421-437">숨겨진 공유</span><span class="sxs-lookup"><span data-stu-id="9e421-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="9e421-438">공유(예: 공유 수준에 부여된 사용 권한)</span><span class="sxs-lookup"><span data-stu-id="9e421-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="9e421-439">현재 SharePoint Online 제한 사항을 초과하는 파일 또는 <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">폴더</span></a> </span><span class="sxs-lookup"><span data-stu-id="9e421-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="9e421-440"><strong>단일 G 제품군 환경(Google Drive만 해당)</strong></span><span class="sxs-lookup"><span data-stu-id="9e421-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="9e421-441">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="9e421-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="9e421-442">Google 문서, 스프레드시트 및 슬라이드(파일이 동등한 Office 형식으로 변환됨 / 10MB 초과하는 파일 포함)</span><span class="sxs-lookup"><span data-stu-id="9e421-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="9e421-443">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="9e421-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="9e421-444">사용자 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="9e421-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9e421-445">그룹 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="9e421-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9e421-446">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="9e421-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="9e421-447">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="9e421-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="9e421-448">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="9e421-448">Created date</span></span> </li>
<li> <span data-ttu-id="9e421-449">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="9e421-449">Modified date</span></span> </li>
<li> <span data-ttu-id="9e421-450">만든 사람</span><span class="sxs-lookup"><span data-stu-id="9e421-450">Created by</span></span> </li>
<li> <span data-ttu-id="9e421-451">마지막 수정 날짜</span><span class="sxs-lookup"><span data-stu-id="9e421-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="9e421-452">공유 드라이브(폴더 및 파일)</span><span class="sxs-lookup"><span data-stu-id="9e421-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="9e421-453">Google Drive 계정이 소유한 공유 콘텐츠를 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="9e421-454">소유권 기록, 이전 버전 및 메모</span><span class="sxs-lookup"><span data-stu-id="9e421-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="9e421-455">파일 및 폴더 설명, 폴더 색상</span><span class="sxs-lookup"><span data-stu-id="9e421-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="9e421-456">사용자 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="9e421-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="9e421-457">그룹 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="9e421-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="9e421-458">고급 메타 데이터</span><span class="sxs-lookup"><span data-stu-id="9e421-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="9e421-459">파일 잠금 특성</span><span class="sxs-lookup"><span data-stu-id="9e421-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="9e421-460">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="9e421-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="9e421-461">휴지통 항목</span><span class="sxs-lookup"><span data-stu-id="9e421-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="9e421-462">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="9e421-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="9e421-463">차단되거나 비활성 상태인 사용자</span><span class="sxs-lookup"><span data-stu-id="9e421-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="9e421-464">Google Photos. Forms, Maps 및 기타 연결된 앱</span><span class="sxs-lookup"><span data-stu-id="9e421-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="9e421-465">Google 드로잉</span><span class="sxs-lookup"><span data-stu-id="9e421-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="9e421-466">조직 외부로 공유된 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="9e421-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="9e421-467">마이그레이션할 Google Drive 계정에서 소유하지 않은 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="9e421-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="9e421-468">외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>): Google Drive Admin 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="9e421-469">최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="9e421-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="9e421-470">공유 드라이브 구성원 권한(<strong>참고</strong>): Google Drive Admin 보고서를 사용하여 공유 드라이브 구성원 자격을 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="9e421-471">마이그레이션하기 전에 최종 사용자에게 대상에서 이러한 구성원 자격 설정을 구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="9e421-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="9e421-472">현재 SharePoint Online 제한 사항을 초과하는 파일 또는 <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">폴더</span></a> </span><span class="sxs-lookup"><span data-stu-id="9e421-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="9e421-473"><strong>Box(Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="9e421-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="9e421-474">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="9e421-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="9e421-475">문서</span><span class="sxs-lookup"><span data-stu-id="9e421-475">Documents</span></span> </li>
<li> <span data-ttu-id="9e421-476">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="9e421-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="9e421-477">사용자 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="9e421-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9e421-478">그룹 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="9e421-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9e421-479">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="9e421-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="9e421-480">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="9e421-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="9e421-481">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="9e421-481">Created date</span></span> </li>
<li> <span data-ttu-id="9e421-482">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="9e421-482">Modified date</span></span> </li>
<li> <span data-ttu-id="9e421-483">만든 사람</span><span class="sxs-lookup"><span data-stu-id="9e421-483">Created by</span></span> </li>
<li> <span data-ttu-id="9e421-484">마지막 수정 날짜</span><span class="sxs-lookup"><span data-stu-id="9e421-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="9e421-485">Box 계정이 소유한 공유 콘텐츠가 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="9e421-486">소유권 기록, 이전 버전 및 메모</span><span class="sxs-lookup"><span data-stu-id="9e421-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="9e421-487">파일 및 폴더 설명</span><span class="sxs-lookup"><span data-stu-id="9e421-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="9e421-488">사용자 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="9e421-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="9e421-489">그룹 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="9e421-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="9e421-490">Box 태그와 고급 메타데이터</span><span class="sxs-lookup"><span data-stu-id="9e421-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="9e421-491">파일 잠금 특성</span><span class="sxs-lookup"><span data-stu-id="9e421-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="9e421-492">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="9e421-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="9e421-493">휴지통 항목</span><span class="sxs-lookup"><span data-stu-id="9e421-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="9e421-494">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="9e421-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="9e421-495">차단되거나 비활성 상태인 사용자</span><span class="sxs-lookup"><span data-stu-id="9e421-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="9e421-496">Box 앱, 책갈피, 즐겨찾기 및 워크플로</span><span class="sxs-lookup"><span data-stu-id="9e421-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="9e421-497">마이그레이션된 상자 계정에서 소유하지 않은 콘텐츠입니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="9e421-498">외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>): Box 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="9e421-499">최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="9e421-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="9e421-500">현재 SharePoint Online 제한 사항을 초과하는 파일 또는 <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">폴더</span></a> </span><span class="sxs-lookup"><span data-stu-id="9e421-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="9e421-501"><strong>Teams용 Dropbox(표준 및 고급)</strong></span><span class="sxs-lookup"><span data-stu-id="9e421-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="9e421-502">단일 또는 멀티패스</span><span class="sxs-lookup"><span data-stu-id="9e421-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="9e421-503">문서</span><span class="sxs-lookup"><span data-stu-id="9e421-503">Documents</span></span> </li>
<li> <span data-ttu-id="9e421-504">파일 및 폴더 구조</span><span class="sxs-lookup"><span data-stu-id="9e421-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="9e421-505">사용자 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="9e421-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9e421-506">그룹 수준 폴더 권한</span><span class="sxs-lookup"><span data-stu-id="9e421-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9e421-507">15GB 미만 파일</span><span class="sxs-lookup"><span data-stu-id="9e421-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="9e421-508">기본 문서 및 폴더 메타데이터:</span><span class="sxs-lookup"><span data-stu-id="9e421-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="9e421-509">만든 날짜</span><span class="sxs-lookup"><span data-stu-id="9e421-509">Created date</span></span> </li>
<li> <span data-ttu-id="9e421-510">수정한 날짜</span><span class="sxs-lookup"><span data-stu-id="9e421-510">Modified date</span></span> </li>
<li> <span data-ttu-id="9e421-511">만든 사람</span><span class="sxs-lookup"><span data-stu-id="9e421-511">Created by</span></span> </li>
<li> <span data-ttu-id="9e421-512">마지막 수정 날짜</span><span class="sxs-lookup"><span data-stu-id="9e421-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="9e421-513">공유 팀 폴더 및 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="9e421-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="9e421-514">Dropbox 계정이 소유한 공유 콘텐츠가 마이그레이션됩니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="9e421-515">소유권 기록, 이전 버전 및 메모</span><span class="sxs-lookup"><span data-stu-id="9e421-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="9e421-516">파일 및 폴더 설명</span><span class="sxs-lookup"><span data-stu-id="9e421-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="9e421-517">사용자 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="9e421-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="9e421-518">그룹 수준 파일 권한</span><span class="sxs-lookup"><span data-stu-id="9e421-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="9e421-519">고급 메타 데이터</span><span class="sxs-lookup"><span data-stu-id="9e421-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="9e421-520">파일 잠금 특성</span><span class="sxs-lookup"><span data-stu-id="9e421-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="9e421-521">콘텐츠에 포함된 URL 변환</span><span class="sxs-lookup"><span data-stu-id="9e421-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="9e421-522">휴지통 항목</span><span class="sxs-lookup"><span data-stu-id="9e421-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="9e421-523">액세스할 수 없거나 손상된 문서</span><span class="sxs-lookup"><span data-stu-id="9e421-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="9e421-524">연결 해제된 Dropbox 폴더</span><span class="sxs-lookup"><span data-stu-id="9e421-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="9e421-525">삭제되거나 연결이 끊어진 사용자</span><span class="sxs-lookup"><span data-stu-id="9e421-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="9e421-526">Dropbox Paper, Showcases 및 Spaces</span><span class="sxs-lookup"><span data-stu-id="9e421-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="9e421-527">Dropbox 앱 및 즐겨찾기(핀/별)</span><span class="sxs-lookup"><span data-stu-id="9e421-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="9e421-528">마이그레이션된 Dropbox 계정이 소유하지 않은 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="9e421-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="9e421-529">외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>: Dropbox 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="9e421-530">최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.)</span><span class="sxs-lookup"><span data-stu-id="9e421-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="9e421-531">현재 SharePoint Online 제한 사항을 초과하는 파일 또는 <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">폴더</span></a> </span><span class="sxs-lookup"><span data-stu-id="9e421-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="9e421-532">FastTrack 책임</span><span class="sxs-lookup"><span data-stu-id="9e421-532">FastTrack responsibilities</span></span>

<span data-ttu-id="9e421-533">Microsoft의 FastTrack 전문가는 마이그레이션 프로젝트 중에 표준 작업을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="9e421-534">자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="9e421-535">귀하의 책임</span><span class="sxs-lookup"><span data-stu-id="9e421-535">Your responsibilities</span></span>

<span data-ttu-id="9e421-536">마이그레이션 프로젝트 중에 표준 작업을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="9e421-537">자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="9e421-538">또한 비즈니스용 OneDrive 마이그레이션과 관련된 다음 작업도 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="9e421-539">마이그레이션 이벤트의 대상이 되는 비즈니스 사이트를 위해 모든 OneDrive를 프로비저닝합니다.</span><span class="sxs-lookup"><span data-stu-id="9e421-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
