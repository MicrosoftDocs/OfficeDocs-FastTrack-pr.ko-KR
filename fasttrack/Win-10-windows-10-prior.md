---
title: Windows 10
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
ms.service: windows-10-administration
localization_priority: Priority
ms.collection: FastTrack
description: FastTrack은 Windows 10 배포 지침을 제공하여 Windows 7 Professional 및 Windows 8.1 Professional에서 Windows 10 Enterprise로 업그레이드하는 데 도움을 줍니다.
ms.openlocfilehash: da069420434a8087c661f77400edd9239f56c366
ms.sourcegitcommit: 81ad135578a329f8b0a3325c4e43bb8f90648597
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/17/2020
ms.locfileid: "46776979"
---
# <a name="windows-10"></a><span data-ttu-id="2b91d-103">Windows 10</span><span class="sxs-lookup"><span data-stu-id="2b91d-103">Windows 10</span></span>

<span data-ttu-id="2b91d-104">FastTrack은 Windows 10 배포 지침을 제공하여 Windows 7 Professional 및 Windows 8.1 Professional에서 Windows 10 Enterprise로 업그레이드하는 데 도움을 줍니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-104">FastTrack provides Windows 10 deployment guidance to help you for upgrade from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span> <span data-ttu-id="2b91d-105">FastTrack 전문가와 협력하여 다음을 수행할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-105">You work with FastTrack Specialists to:</span></span>

- <span data-ttu-id="2b91d-106">Microsoft Endpoint Configuration Manager 또는 Microsoft 365를 사용하여 Windows 10 Enterprise를 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-106">Deploy Windows 10 Enterprise using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>
- <span data-ttu-id="2b91d-107">Microsoft 365 앱을 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-107">Deploy Microsoft 365 Apps.</span></span> 
- <span data-ttu-id="2b91d-108">Microsoft Endpoint Configuration Manager 또는 Microsoft 365를 사용하여 Windows 10 Enterprise 및 Microsoft 365 앱을 업데이트합니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-108">Update Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>
- <span data-ttu-id="2b91d-109">Microsoft Intune을 사용하여 구성 관리자를 클라우드로 연결하거나 단독 클라우드 관리 솔루션으로 Intune을 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-109">Cloud-attach Configuration Manager with Microsoft Intune or deploy Intune as the sole cloud management solution.</span></span>
  
> [!NOTE]
> <span data-ttu-id="2b91d-110">FastTrack에서는 빠르고 예측 가능한 결과를 제공하도록 설계된 권장 접근 방법, 지침 및 모범 사례를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-110">FastTrack provides customers with a recommended approach, guidance, and best practices engineered to deliver quick and predictable outcomes.</span></span> <span data-ttu-id="2b91d-111">이 지침 이외의 내용을 배포하도록 선택한 경우 사용자 환경에 영향을 줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-111">If you choose to deploy outside of this guidance, your experience may be impacted.</span></span> <span data-ttu-id="2b91d-112">지침은 구두 및 서면 지원의 조합으로 정의됩니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-112">Guidance is defined as a combination of verbal and written assistance.</span></span> <span data-ttu-id="2b91d-113">FastTrack Specialists에서 지침을 제공하는 경우 FastTrack 담당자는 사용자 대신 작업할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-113">When FastTrack Specialists provide guidance, FastTrack personnel can't act on your behalf.</span></span> <span data-ttu-id="2b91d-114">구독 중인 경우에는 FastTrack 서비스를 적격 계획에 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-114">You can use FastTrack services for qualifying plans as long as your subscription is current.</span></span>  
    
<span data-ttu-id="2b91d-115">다음 표에는 프로세스에 대한 역할 및 책임이 나와 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-115">The following table lists roles and responsibilities for the process.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="2b91d-116">**역할**</span><span class="sxs-lookup"><span data-stu-id="2b91d-116">**Role**</span></span> <br/> |<span data-ttu-id="2b91d-117">**책임**</span><span class="sxs-lookup"><span data-stu-id="2b91d-117">**Responsibility**</span></span> <br/> |
|<span data-ttu-id="2b91d-118">**FastTrack Specialist**</span><span class="sxs-lookup"><span data-stu-id="2b91d-118">**FastTrack Specialist**</span></span> <br/> |<span data-ttu-id="2b91d-119">원격으로 모든 배포 및 업데이트 서비스를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-119">Provides all deployment and update services remotely.</span></span>  <br/> <span data-ttu-id="2b91d-120">도구, 게시된 설명서를 조합해서 원격으로 사용자를 지원합니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-120">Assists you remotely by using a combination of tools and published documentation.</span></span> <br/> <span data-ttu-id="2b91d-121">사용자와 직접 또는 대리인과 작업할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-121">Works directly with you or your representative.</span></span>|
|<span data-ttu-id="2b91d-122">**FastTrack 센터**</span><span class="sxs-lookup"><span data-stu-id="2b91d-122">**FastTrack Center**</span></span>  <br/> |<span data-ttu-id="2b91d-123">Windows 10 Enterprise를 계획하고 배포할 수 있는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-123">Provides guidance to plan and deploy Windows 10 Enterprise.</span></span>   <br/> <span data-ttu-id="2b91d-124">지원을 제공하며 지정된 지역의 일반 업무 시간 동안 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-124">Provides assistance and is available during normal business hours for a given region.</span></span> <br/> <span data-ttu-id="2b91d-125">중국어 번체, 중국어 간체(지원 담당자가 만다린어만 사용), 영어, 프랑스어, 독일어, 이탈리아어, 일본어, 한국어, 포르투갈어(브라질), 스페인어, 태국어 및 베트남어로 지원이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-125">Provides assistance in Traditional Chinese and Simplified Chinese (resources speak Mandarin only), English, French, German, Italian, Japanese, Korean, Portuguese (Brazil), Spanish, Thai, and Vietnamese.</span></span>|
 
<span data-ttu-id="2b91d-126">[Microsoft 365 관리 센터](https://go.microsoft.com/fwlink/?linkid=2032704) 또는 [FastTrack 사이트](https://go.microsoft.com/fwlink/?linkid=780698)를 통해 도움을 얻을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-126">You can get help through the [Microsoft 365 admin center](https://go.microsoft.com/fwlink/?linkid=2032704) or the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> <span data-ttu-id="2b91d-127">로그인하려면 활성 테넌트에 활성 회사 또는 학교 계정(조직 ID 또는 Azure Active Directory ID)이 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-127">To sign in, you must have an active work or school account (organizational ID or Azure Active Directory ID) on an active tenant.</span></span> 

<span data-ttu-id="2b91d-128">[FastTrack 사이트](https://go.microsoft.com/fwlink/?linkid=780698)에서 도움을 얻으려면</span><span class="sxs-lookup"><span data-stu-id="2b91d-128">To get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698):</span></span> 
1.    <span data-ttu-id="2b91d-129">[FastTrack 사이트](https://go.microsoft.com/fwlink/?linkid=780698)에 로그인합니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-129">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.    <span data-ttu-id="2b91d-130">방문 페이지의 상단의 **빠른 작업**에서 **Microsoft 365 지원 요청**을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-130">Select **Request assistance with Microsoft 365** from the **quick actions** on the top of your landing page.</span></span>
3.    <span data-ttu-id="2b91d-131">**Microsoft 365 지원 요청** 양식을 완료합니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-131">Complete the **Request Assistance with Microsoft 365** form.</span></span>
  
<span data-ttu-id="2b91d-p104">파트너는 고객 대신 [FastTrack 사이트](https://go.microsoft.com/fwlink/?linkid=780698)를 통해 도움을 얻을 수도 있습니다. 이렇게 하려면 다음을 수행합니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-p104">Partners can also get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698) on behalf of a customer. To do so:</span></span>
1.    <span data-ttu-id="2b91d-134">[FastTrack 사이트](https://go.microsoft.com/fwlink/?linkid=780698)에 로그인합니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-134">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.    <span data-ttu-id="2b91d-135">방문 페이지의 상단의 **빠른 작업**에서 **Microsoft 365 지원 요청**을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-135">Select **Request assistance with Microsoft 365** from the **quick actions** on the top of your landing page.</span></span>
3.    <span data-ttu-id="2b91d-136">고객 이름, 도메인 또는 TPID를 입력하여 고객을 검색합니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-136">Search for your customer by entering the customer name, domain, or TPID.</span></span>
4.    <span data-ttu-id="2b91d-137">검색 결과에서 고객을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-137">Select customer from the search results.</span></span>
5.    <span data-ttu-id="2b91d-138">**Microsoft 365 지원 요청** 양식을 완료합니다.</span><span class="sxs-lookup"><span data-stu-id="2b91d-138">Complete the **Request Assistance with Microsoft 365** form.</span></span>
 
