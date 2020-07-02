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
ms.openlocfilehash: 0aa98b787af20c12f851033b0524d450fd0fcb87
ms.sourcegitcommit: 850211891e549e582e649a1dacdc2aa79b520b39
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/01/2020
ms.locfileid: "45011516"
---
# <a name="windows-10"></a><span data-ttu-id="d8805-103">Windows 10</span><span class="sxs-lookup"><span data-stu-id="d8805-103">Windows 10</span></span>

<span data-ttu-id="d8805-104">FastTrack은 Windows 10 배포 지침을 제공하여 Windows 7 Professional 및 Windows 8.1 Professional에서 Windows 10 Enterprise로 업그레이드하는 데 도움을 줍니다.</span><span class="sxs-lookup"><span data-stu-id="d8805-104">FastTrack provides Windows 10 deployment guidance to help you for upgrade from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span> <span data-ttu-id="d8805-105">FastTrack 전문가와 협력하여 다음을 수행할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d8805-105">You work with FastTrack Specialists to:</span></span>

- <span data-ttu-id="d8805-106">Microsoft Endpoint Configuration Manager 또는 Microsoft 365를 사용하여 Windows 10 Enterprise를 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="d8805-106">Deploy Windows 10 Enterprise using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>
- <span data-ttu-id="d8805-107">Microsoft 365 앱을 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="d8805-107">Deploy Microsoft 365 Apps.</span></span> 
- <span data-ttu-id="d8805-108">Microsoft Endpoint Configuration Manager 또는 Microsoft 365를 사용하여 Windows 10 Enterprise 및 Microsoft 365 앱을 업데이트합니다.</span><span class="sxs-lookup"><span data-stu-id="d8805-108">Update Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>
- <span data-ttu-id="d8805-109">Microsoft Intune을 사용하여 구성 관리자를 클라우드로 연결하거나 단독 클라우드 관리 솔루션으로 Intune을 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="d8805-109">Cloud-attach Configuration Manager with Microsoft Intune or deploy Intune as the sole cloud management solution.</span></span>
  
> [!NOTE]
> <span data-ttu-id="d8805-110">FastTrack에서는 빠르고 예측 가능한 결과를 제공하도록 설계된 권장 접근 방법, 지침 및 모범 사례를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="d8805-110">FastTrack provides customers with a recommended approach, guidance, and best practices engineered to deliver quick and predictable outcomes.</span></span> <span data-ttu-id="d8805-111">이 지침 이외의 내용을 배포하도록 선택한 경우 사용자 환경에 영향을 줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d8805-111">If you choose to deploy outside of this guidance, your experience may be impacted.</span></span> <span data-ttu-id="d8805-112">지침은 구두 및 서면 지원의 조합으로 정의됩니다.</span><span class="sxs-lookup"><span data-stu-id="d8805-112">Guidance is defined as a combination of verbal and written assistance.</span></span> <span data-ttu-id="d8805-113">FastTrack Specialists에서 지침을 제공하는 경우 FastTrack 담당자는 사용자 대신 작업할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="d8805-113">When FastTrack Specialists provide guidance, FastTrack personnel can't act on your behalf.</span></span> <span data-ttu-id="d8805-114">구독 중인 경우에는 FastTrack 서비스를 적격 계획에 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d8805-114">You can use FastTrack services for qualifying plans as long as your subscription is current.</span></span>  
    
<span data-ttu-id="d8805-115">다음 표에는 프로세스에 대한 역할 및 책임이 나와 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d8805-115">The following table lists roles and responsibilities for the process.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="d8805-116">**역할**</span><span class="sxs-lookup"><span data-stu-id="d8805-116">**Role**</span></span> <br/> |<span data-ttu-id="d8805-117">**책임**</span><span class="sxs-lookup"><span data-stu-id="d8805-117">**Responsibility**</span></span> <br/> |
|<span data-ttu-id="d8805-118">**FastTrack Specialist**</span><span class="sxs-lookup"><span data-stu-id="d8805-118">**FastTrack Specialist**</span></span> <br/> |<span data-ttu-id="d8805-119">원격으로 모든 배포 및 업데이트 서비스를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="d8805-119">Provides all deployment and update services remotely.</span></span>  <br/> <span data-ttu-id="d8805-120">도구, 게시된 설명서를 조합해서 원격으로 사용자를 지원합니다.</span><span class="sxs-lookup"><span data-stu-id="d8805-120">Assists you remotely by using a combination of tools and published documentation.</span></span> <br/> <span data-ttu-id="d8805-121">사용자와 직접 또는 대리인과 작업할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d8805-121">Works directly with you or your representative.</span></span>|
|<span data-ttu-id="d8805-122">**FastTrack 센터**</span><span class="sxs-lookup"><span data-stu-id="d8805-122">**FastTrack Center**</span></span>  <br/> |<span data-ttu-id="d8805-123">Windows 10 Enterprise를 계획하고 배포할 수 있는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="d8805-123">Provides guidance to plan and deploy Windows 10 Enterprise.</span></span>   <br/> <span data-ttu-id="d8805-124">지원을 제공하며 지정된 지역의 일반 업무 시간 동안 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d8805-124">Provides assistance and is available during normal business hours for a given region.</span></span> <br/> <span data-ttu-id="d8805-125">중국어 번체, 중국어 간체(지원 담당자가 만다린어만 사용), 영어, 프랑스어, 독일어, 이탈리아어, 일본어, 한국어, 포르투갈어(브라질), 스페인어, 태국어 및 베트남어로 지원이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="d8805-125">Provides assistance in Traditional Chinese and Simplified Chinese (resources speak Mandarin only), English, French, German, Italian, Japanese, Korean, Portuguese (Brazil), Spanish, Thai, and Vietnamese.</span></span>|
 
<span data-ttu-id="d8805-126">[Microsoft 365 관리 센터](https://go.microsoft.com/fwlink/?linkid=2032704) 또는 [FastTrack 사이트](https://go.microsoft.com/fwlink/?linkid=780698)를 통해 도움을 얻을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d8805-126">You can get help through the [Microsoft 365 admin center](https://go.microsoft.com/fwlink/?linkid=2032704) or the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> <span data-ttu-id="d8805-127">로그인하려면 활성 테넌트에 활성 회사 또는 학교 계정(조직 ID 또는 Azure Active Directory ID)이 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="d8805-127">To sign in, you must have an active work or school account (organizational ID or Azure Active Directory ID) on an active tenant.</span></span> 

<span data-ttu-id="d8805-128">[FastTrack 사이트](https://go.microsoft.com/fwlink/?linkid=780698)에서 도움을 얻으려면</span><span class="sxs-lookup"><span data-stu-id="d8805-128">To get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698):</span></span> 
1.    <span data-ttu-id="d8805-129">[FastTrack 사이트](https://go.microsoft.com/fwlink/?linkid=780698)에 로그인합니다.</span><span class="sxs-lookup"><span data-stu-id="d8805-129">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.    <span data-ttu-id="d8805-130">방문 페이지 상단의 **빠른 작업**에서 또는 배포 카드에서 **Microsoft 365에 대한 지원 요청**을 선택하여 **Microsoft 365에 대한 지원 요청**을 선택하십시오.</span><span class="sxs-lookup"><span data-stu-id="d8805-130">Select **Request assistance for Microsoft 365** from the **quick actions** on the top of your landing page or by selecting **Request assistance for Microsoft 365** on the deploy card.</span></span>
3.    <span data-ttu-id="d8805-131">**Microsoft 365에 대한 지원 요청서**를 작성하세요.</span><span class="sxs-lookup"><span data-stu-id="d8805-131">Complete the **Request Assistance for Microsoft 365** form.</span></span>
  
<span data-ttu-id="d8805-132">Partners can also get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698) on behalf of a customer.</span><span class="sxs-lookup"><span data-stu-id="d8805-132">Partners can also get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698) on behalf of a customer.</span></span> <span data-ttu-id="d8805-133">To do so:</span><span class="sxs-lookup"><span data-stu-id="d8805-133">To do so:</span></span>
1.    <span data-ttu-id="d8805-134">[FastTrack 사이트](https://go.microsoft.com/fwlink/?linkid=780698)에 로그인합니다.</span><span class="sxs-lookup"><span data-stu-id="d8805-134">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.    <span data-ttu-id="d8805-135">**내 고객**을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="d8805-135">Select **My Customers**.</span></span>
3.    <span data-ttu-id="d8805-136">고객을 검색하거나 고객 목록에서 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="d8805-136">Search for your customer or select them from your customer list.</span></span>
4.    <span data-ttu-id="d8805-137">**서비스**를 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="d8805-137">Select **Services**.</span></span>
5.    <span data-ttu-id="d8805-138">**Microsoft 365에 대한 지원 요청서**를 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="d8805-138">Select the **Request Assistance for Microsoft 365** form.</span></span>
6.    <span data-ttu-id="d8805-139">Windows 10 제품 옵션을 선택하고 양식을 작성합니다.</span><span class="sxs-lookup"><span data-stu-id="d8805-139">Select the Windows 10 product option and complete the form.</span></span>
 
