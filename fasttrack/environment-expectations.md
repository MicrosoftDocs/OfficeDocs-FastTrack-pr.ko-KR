---
title: 원본 환경 요구 조건
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/27/18
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: 533063e2-2630-46f3-9a88-ad07bb7dac9a
description: FastTrack 센터 혜택에는 원본 환경과 일정 수준의 통합을 설정할 수 있도록 지침을 제공합니다(예를 들어, Office 365로 이동하려는 서비스가 원본 환경에 이미 있는 경우).
ms.openlocfilehash: 1ce90a0319a3ec06d61c5b18b0679b89377f97c7
ms.sourcegitcommit: ce2f0b156075cb8f07efa96c02115baf20779b6d
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/30/2018
ms.locfileid: "21498865"
---
# <a name="source-environment-expectations"></a><span data-ttu-id="73aa7-103">원본 환경 요구 조건</span><span class="sxs-lookup"><span data-stu-id="73aa7-103">Source Environment Expectations</span></span>

<span data-ttu-id="73aa7-104">FastTrack 센터 혜택에는 원본 환경과 일정 수준의 통합을 설정할 수 있도록 지침을 제공합니다(예를 들어, Office 365로 이동하려는 서비스가 원본 환경에 이미 있는 경우).</span><span class="sxs-lookup"><span data-stu-id="73aa7-104">[] The FastTrack Center Benefit provides guidance for you to set up levels of integration with your source environment (for example, if you already have services in your source environment that you want to move to Office 365).</span></span>
  
> [!NOTE]
> <span data-ttu-id="73aa7-105">통합이 필요한 경우 원본 환경은 해당 응용 프로그램의 수준 이상이어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="73aa7-105">If integration is required, your source environment must be at a minimum level for that application.</span></span> 
  
<span data-ttu-id="73aa7-106">다음 표에는 온보딩을 위해 기존 원본 환경에서 요구되는 조건이 나와 있습니다.</span><span class="sxs-lookup"><span data-stu-id="73aa7-106">The following table shows expectations for your existing source environment for onboarding.</span></span>

|<span data-ttu-id="73aa7-107">**작업**</span><span class="sxs-lookup"><span data-stu-id="73aa7-107">**Activity**</span></span>|<span data-ttu-id="73aa7-108">**원본 환경 요구 조건**</span><span class="sxs-lookup"><span data-stu-id="73aa7-108">**Source environment expectation**</span></span>|
|:-----|:-----|
|<span data-ttu-id="73aa7-109">핵심 온보딩</span><span class="sxs-lookup"><span data-stu-id="73aa7-109">Core onboarding</span></span> | <span data-ttu-id="73aa7-110">다음 포리스트 구성을 사용하며 포리스트 기능 수준이 Windows Server 2003 이상으로 설정된 Active Directory 포리스트:</span><span class="sxs-lookup"><span data-stu-id="73aa7-110">Active Directory forests with the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>  <br/>      <span data-ttu-id="73aa7-111">단일 Active Directory 포리스트.</span><span class="sxs-lookup"><span data-stu-id="73aa7-111">A single Active Directory forest.</span></span>  <br/>    <span data-ttu-id="73aa7-112">단일 Active Directory 계정 포리스트 및 리소스 포리스트(Exchange 및/또는 Lync 2010, Lync 2013 또는 비즈니스용 Skype) 토폴로지</span><span class="sxs-lookup"><span data-stu-id="73aa7-112">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  <br/>  <span data-ttu-id="73aa7-113">여러 개의 Active Directory 계정 포리스트 및 리소스 포리스트(Exchange 및/또는 Lync 2010, Lync 2013 또는 비즈니스용 Skype) 토폴로지</span><span class="sxs-lookup"><span data-stu-id="73aa7-113">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  <br/>  <span data-ttu-id="73aa7-114">포리스트 중 하나가 Exchange 및/또는 Lync 2010, Lync 2013 또는 비즈니스용 Skype가 있는 중앙 집중식 Active Directory 계정 포리스트인 여러 Active Directory 계정 포리스트</span><span class="sxs-lookup"><span data-stu-id="73aa7-114">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  <br/>  <span data-ttu-id="73aa7-115">각각이 자체 Exchange 조직을 갖는 다중 Active Directory 계정 포리스트</span><span class="sxs-lookup"><span data-stu-id="73aa7-115">Multiple Active Directory account forests, each with its own Exchange organization.</span></span> <br/> <br/> <span data-ttu-id="73aa7-116">**참고**  *여러 포리스트 Active Directory 시나리오의 경우 Lync 2010, Lync 2013 또는 비즈니스용 Skype를 배포할 때 동일한 Active Directory를 Exchange로 배포해야 합니다.*</span><span class="sxs-lookup"><span data-stu-id="73aa7-116">******>  For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>   <br/>  <br/>      <span data-ttu-id="73aa7-117">**참고**  *다중 Active Directory 포리스트를 Exchange 다중 하이브리드 구성의 여러 Exchange 조직으로 구현하는 경우 원본 포리스트 간의 공유된 UPN(사용자 계정 이름) 네임스페이스는 지원되지 않습니다. Exchange 조직 간의 기본 SMTP 네임스페이스도 구분해야 합니다. 자세한 내용은 [다중 Active Directory 포리스트로 하이브리드 배포](https://go.microsoft.com/fwlink/?linkid=845444)를 참조하세요.*</span><span class="sxs-lookup"><span data-stu-id="73aa7-117">When implementing multiple ActiveDirectory_2nd forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren’t supported. Primary SMTP namespaces between Exchange organizations should also be separated. For more information, see  Hybrid deployments with multiple Active Directory forests https://go.microsoft.com/fwlink/?linkid=845444 .</span></span>     <br/>   <br/>   <span data-ttu-id="73aa7-118">**참고**  *모든 다중 포리스트 구성에서 ADFS 배포는 FastTrack 센터 혜택을 받지 않습니다.*</span><span class="sxs-lookup"><span data-stu-id="73aa7-118">******>  For all multiple forests configurations, AD FS deployment is out of scope for the FastTrack Center Benefit.</span></span>           |
|<span data-ttu-id="73aa7-119">Exchange Online 온보딩</span><span class="sxs-lookup"><span data-stu-id="73aa7-119">Exchange Online onboarding</span></span> | <span data-ttu-id="73aa7-120">사용자 환경은 다음 최소 수준 중 하나여야 합니다.</span><span class="sxs-lookup"><span data-stu-id="73aa7-120">Your environment must have one of the following minimum levels:</span></span>  <br/>  <span data-ttu-id="73aa7-121">Exchange Server 2003 이후 버전을 사용하는 단일 또는 다중 Exchange 조직</span><span class="sxs-lookup"><span data-stu-id="73aa7-121">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  <br/>  <span data-ttu-id="73aa7-122">단일 IBM Domino 7.0.3 이상 환경([부록 A: IBM Domino에서 Exchange Online으로 마이그레이션](from-ibm-domino-to-exchange-online.md))</span><span class="sxs-lookup"><span data-stu-id="73aa7-122">A single IBM Domino 7.0.3 onward environment ( [Appendix A - Migration from IBM Domino to Exchange Online](from-ibm-domino-to-exchange-online.md)).</span></span>  <br/>  <span data-ttu-id="73aa7-123">단일 IMAP(Internet Message Access Protocol) 지원 전자 메일 환경</span><span class="sxs-lookup"><span data-stu-id="73aa7-123">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  <br/>  <span data-ttu-id="73aa7-124">단일 G 제품군 환경(Gmail, 연락처 및 캘린더만)</span><span class="sxs-lookup"><span data-stu-id="73aa7-124">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  <br/>  <span data-ttu-id="73aa7-125">단일 Novell GroupWise 7.0.4 이상 환경</span><span class="sxs-lookup"><span data-stu-id="73aa7-125">A single Novell GroupWise 7.0.4 onward environment.</span></span>  <br/><br/> <span data-ttu-id="73aa7-126">**참고**  *Multi-Geo Capabilities에 대한 자세한 내용은 [Exchange Online의 Multi-Geo Capabilities](https://go.microsoft.com/fwlink/?linkid=872776)를 참조하세요.*</span><span class="sxs-lookup"><span data-stu-id="73aa7-126"> >  For information on Multi-Geo Capabilities, see Multi-Geo Capabilities in Exchange Online.</span></span>           |
|<span data-ttu-id="73aa7-127">SharePoint Online 및 비즈니스용 OneDrive 온보딩</span><span class="sxs-lookup"><span data-stu-id="73aa7-127">SharePoint Online and OneDrive for Business onboarding</span></span>  | <span data-ttu-id="73aa7-128">**SharePoint 하이브리드**</span><span class="sxs-lookup"><span data-stu-id="73aa7-128">**SharePoint Hybrid**</span></span>  <br/>  <span data-ttu-id="73aa7-p101">SharePoint 하이브리드 구성에는 온-프레미스에서 단일 대상 SharePoint Online 환경으로 연결된 하이브리드 검색, 사이트, 분류, 콘텐츠 형식, 비즈니스용 OneDrive, 확장된 앱 시작 관리자, 엑스트라넷 사이트 및 셀프 서비스 사이트 만들기 구성이 포함됩니다. SharePoint 하이브리드를 사용하려면 다음 온-프레미스 SharePoint Server 환경 중 하나가 있어야 합니다.  </span><span class="sxs-lookup"><span data-stu-id="73aa7-p101">SharePoint Hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment. To enable SharePoint Hybrid, you must have one of the following on-premises SharePoint Server environments:  </span></span><br/> <br/> <span data-ttu-id="73aa7-131">***SharePoint Server 2013***</span><span class="sxs-lookup"><span data-stu-id="73aa7-131">***SharePoint Server 2013***</span></span>  <br/>  <span data-ttu-id="73aa7-p102">하이브리드 콘텐츠 형식에 대한 2017년 6월 공개 업데이트입니다. 자세한 내용은 [하이브리드 SharePoint 분류 및 하이브리드 콘텐츠 형식 구성](https://go.microsoft.com/fwlink/?linkid=853547)을 참조하세요.  </span><span class="sxs-lookup"><span data-stu-id="73aa7-p102">June 2017 Public Update (PU) for hybrid content types. For more information, see [Configure hybrid SharePoint taxonomy and hybrid content types](https://go.microsoft.com/fwlink/?linkid=853547).  </span></span><br/>  <span data-ttu-id="73aa7-p103">셀프 서비스 사이트 만들기 구성에 대한 2017년 3월 PU(공용 업데이트)입니다. 하이브리드 셀프 서비스 사이트 만들기는 SharePoint Server 2013에서만 지원됩니다. 자세한 내용은 [하이브리드 셀프 서비스 사이트 만들기](https://go.microsoft.com/fwlink/?linkid=846015)를 참조하세요.  </span><span class="sxs-lookup"><span data-stu-id="73aa7-p103">March 2017 PU for self-service site creation configuration. Hybrid self-service site creation is only supported with SharePoint Server 2013. For more information, see [Hybrid self-service site creation](https://go.microsoft.com/fwlink/?linkid=846015).  </span></span><br/>  <span data-ttu-id="73aa7-p104">하이브리드 분류가 있는 2016년 11월 이후 PU입니다. 자세한 내용은 [하이브리드 SharePoint 분류 계획](https://go.microsoft.com/fwlink/?linkid=844867)을 참조하세요.  </span><span class="sxs-lookup"><span data-stu-id="73aa7-p104">November 2016 PU onward with hybrid taxonomy. For more information, see [Plan hybrid SharePoint taxonomy](https://go.microsoft.com/fwlink/?linkid=844867).  </span></span><br/>  <span data-ttu-id="73aa7-139">다른 모든 하이브리드 구성 시나리오에 대한 2016년 7월 이후 PU입니다.</span><span class="sxs-lookup"><span data-stu-id="73aa7-139">July 2016 PU onward for all other hybrid configuration scenarios.</span></span>  <br/><br/> <span data-ttu-id="73aa7-140">**참고**  *SharePoint Server 2013 하이브리드 시나리오는 SharePoint Server 2013에서만 지원됩니다. 이러한 시나리오는 SharePoint Foundation 2013에서는 지원되지 않습니다.*</span><span class="sxs-lookup"><span data-stu-id="73aa7-140">******>  SharePoint Server 2013 hybrid scenarios are only supported with SharePoint Server 2013. These scenarios aren't supported in SharePoint Foundation 2013.            SharePoint Server 2016</span></span>  <br/>   <br/>    <span data-ttu-id="73aa7-141">***SharePoint Server 2016***</span><span class="sxs-lookup"><span data-stu-id="73aa7-141">***SharePoint Server 2016***</span></span>  <br/>  <span data-ttu-id="73aa7-p105">하이브리드 콘텐츠 형식에 대한 2017년 6월 PU입니다. 자세한 내용은 [하이브리드 SharePoint 분류 및 하이브리드 콘텐츠 형식 구성](https://go.microsoft.com/fwlink/?linkid=853547)을 참조하세요.  </span><span class="sxs-lookup"><span data-stu-id="73aa7-p105">June 2017 PU for hybrid content types. For more information, see [Configure hybrid SharePoint taxonomy and hybrid content types](https://go.microsoft.com/fwlink/?linkid=853547).  </span></span><br/>  <span data-ttu-id="73aa7-p106">하이브리드 분류가 있는 2016년 11월 PU(기능 팩 1)입니다. 자세한 내용은 [하이브리드 SharePoint 분류 계획](https://go.microsoft.com/fwlink/?linkid=844867)을 참조하세요.  </span><span class="sxs-lookup"><span data-stu-id="73aa7-p106">November 2016 PU (Feature Pack 1) with hybrid taxonomy. For more information, see [Plan hybrid SharePoint taxonomy](https://go.microsoft.com/fwlink/?linkid=844867).  </span></span><br/>  <span data-ttu-id="73aa7-146">다른 모든 하이브리드 구성 시나리오에 대한 2016년 7월 이후 PU입니다.</span><span class="sxs-lookup"><span data-stu-id="73aa7-146">July 2016 PU onward for all other hybrid configuration scenarios.</span></span>  <br/><br/> <span data-ttu-id="73aa7-147">**참고**  *온-프레미스 SharePoint 환경에서 SharePoint Server 2013 또는 SharePoint Server 2016으로의 업그레이드는 FastTrack 센터 혜택을 통해 제공되지 않습니다. 자세한 내용은 [SharePoint 하이브리드 기능의 공개 업데이트 최소 수준](https://go.microsoft.com/fwlink/?linkid=853548)을 참조하세요.*</span><span class="sxs-lookup"><span data-stu-id="73aa7-147"> >  Upgrade of on-premises SharePoint environments to SharePoint Server 2013 or SharePoint Server 2016 isn't provided by the FastTrack Center Benefit. For more information, see Minimum public update levels for SharePoint hybrid features.           > >  For information on Multi-Geo Capabilities, see Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365.</span></span>   <br/><br/>        <span data-ttu-id="73aa7-148">**참고**  *Multi-Geo Capabilities에 대한 자세한 내용은 [Office 365 OneDrive 및 SharePoint Online의 Multi-Geo Capabilities](https://go.microsoft.com/fwlink/?linkid=831056)를 참조하세요.*</span><span class="sxs-lookup"><span data-stu-id="73aa7-148"> >  For information on Multi-Geo Capabilities, see Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365.</span></span>           |
|<span data-ttu-id="73aa7-149">비즈니스용 Skype Online 온보딩</span><span class="sxs-lookup"><span data-stu-id="73aa7-149">Skype for Business Online onboarding</span></span>  | <span data-ttu-id="73aa7-150">**네트워크 평가**</span><span class="sxs-lookup"><span data-stu-id="73aa7-150">**Network assessment:**</span></span>  <br/>  <span data-ttu-id="73aa7-151">포트 및 끝점 검사</span><span class="sxs-lookup"><span data-stu-id="73aa7-151">Port and endpoint checks.</span></span>  <br/>  <span data-ttu-id="73aa7-152">연결 품질 검사</span><span class="sxs-lookup"><span data-stu-id="73aa7-152">Connection quality checks.</span></span>  <br/>  <span data-ttu-id="73aa7-153">대역폭 예상</span><span class="sxs-lookup"><span data-stu-id="73aa7-153">Bandwidth estimates.</span></span>  <br/><br/>  <span data-ttu-id="73aa7-154">**Lync 하이브리드**</span><span class="sxs-lookup"><span data-stu-id="73aa7-154">**Lync Hybrid:**</span></span>  <br/>  <span data-ttu-id="73aa7-155">단일 온-프레미스 Active Directory 포리스트</span><span class="sxs-lookup"><span data-stu-id="73aa7-155">A single on-premises Active Directory forest.</span></span>  <br/>  <span data-ttu-id="73aa7-156">Lync 2013 관리 도구 또는 비즈니스용 Skype 2015 관리 도구가 있는 Lync 2010 서버 환경 및 Lync 2010 에지 서버 역할</span><span class="sxs-lookup"><span data-stu-id="73aa7-156">A Lync 2010 Server environment with Lync 2013 admin tools or Skype for Business 2015 admin tools and a Lync 2010 edge server role.</span></span>  <br/>  <span data-ttu-id="73aa7-157">Lync 2013 서버 환경 및 Lync 2013 에지 서버 역할</span><span class="sxs-lookup"><span data-stu-id="73aa7-157">A Lync 2013 Server environment and a Lync 2013 edge server role.</span></span>  <br/><br/>  <span data-ttu-id="73aa7-158">**비즈니스용 Skype 온라인 하이브리드**</span><span class="sxs-lookup"><span data-stu-id="73aa7-158">**Skype for Business Online Hybrid:**</span></span>  <br/>  <span data-ttu-id="73aa7-159">단일 온-프레미스 Active Directory 포리스트</span><span class="sxs-lookup"><span data-stu-id="73aa7-159">A single on-premises Active Directory forest.</span></span>  <br/>  <span data-ttu-id="73aa7-160">단일 Active Directory 계정 포리스트 이상 및 리소스 포리스트(Exchange 및/또는 비즈니스용 Skype) 토폴로지</span><span class="sxs-lookup"><span data-stu-id="73aa7-160">A single Active Directory account forest onward and resource forest (Exchange and/or Skype for Business) topologies.</span></span>  <br/>  <span data-ttu-id="73aa7-161">Exchange 및/또는 비즈니스용 Skype에 중앙 집중식 Active Directory 계정 포리스트 하나가 포함된 여러 Active Directory 계정 포리스트</span><span class="sxs-lookup"><span data-stu-id="73aa7-161">Multiple Active Directory account forests, with one forest being a centralized Active Directory account forest with Exchange and/or Skype for Business in it.</span></span>  <br/>  <span data-ttu-id="73aa7-162">비즈니스용 Skype 에지 서버 역할을 포함하는 비즈니스용 Skype Server 2015 환경</span><span class="sxs-lookup"><span data-stu-id="73aa7-162">A Skype for Business Server 2015 environment including a Skype for Business edge server role.</span></span>  <br/><br/> <span data-ttu-id="73aa7-163">**참고**  *이 추가 서비스는 분할 도메인(하이브리드) 작업의 구성 및 유효성 검사용이고, 온-프레미스 구성 요소(예: Lync 2013 관리 도구 또는 Lync 2013/비즈니스용 Skype 온라인 서버 또는 Lync 2010, Lync 2013 또는 비즈니스용 Skype 에지 서버) 도입을 포함하지 않습니다.*</span><span class="sxs-lookup"><span data-stu-id="73aa7-163">******>  This additional service is for configuring and validating of the split domain (hybrid) tasks and doesn't include introducing on-premises components (for example, Lync 2013 admin tools or Lync 2013/Skype for Business Online servers, or Lync 2010, Lync 2013, or Skype for Business edge servers).</span></span>    <br/><br/>        <span data-ttu-id="73aa7-164">**회의실 장치**</span><span class="sxs-lookup"><span data-stu-id="73aa7-164">**Conference room device:**</span></span>  <br/>  <span data-ttu-id="73aa7-165">[비즈니스 솔루션용 Skype 카탈로그](https://go.microsoft.com/fwlink/?LinkId=615775)의 회의실 시스템에 나열된 지원되는 회의실 장치에 필요한 온라인 계정을 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="73aa7-165">Creation of online accounts needed for supported conference room devices listed on the Meeting Room Systems tab in the [Skype for Business Solutions Catalog](https://go.microsoft.com/fwlink/?LinkId=615775).</span></span>  <br/><br/>  <span data-ttu-id="73aa7-166">**오디오 회의 사용**</span><span class="sxs-lookup"><span data-stu-id="73aa7-166">**Enabling Audio Conferencing:**</span></span>  <br/>  <span data-ttu-id="73aa7-167">회의 브리지 기본 설정에 대한 조직 설정</span><span class="sxs-lookup"><span data-stu-id="73aa7-167">Organization setup for conference bridge default settings.</span></span>  <br/>  <span data-ttu-id="73aa7-168">회의 브리지를 라이선스가 있는 사용자에게 할당</span><span class="sxs-lookup"><span data-stu-id="73aa7-168">Assignment of conference bridge to licensed users.</span></span>  <br/><br/>  <span data-ttu-id="73aa7-169">**전화 시스템 및 통화 계획 사용 가이드(영문만)**</span><span class="sxs-lookup"><span data-stu-id="73aa7-169">**Enabling Phone System and Calling Plans guidance (US Only):**</span></span>  <br/>  <span data-ttu-id="73aa7-170">클라우드 음성 기본 설정에 대한 조직 설정</span><span class="sxs-lookup"><span data-stu-id="73aa7-170">Organization setup for Cloud Voice default settings.</span></span>  <br/>  <span data-ttu-id="73aa7-171">라이선스가 있는 사용자에게 번호 할당</span><span class="sxs-lookup"><span data-stu-id="73aa7-171">Assignment of numbers to licensed users.</span></span>  <br/>  <span data-ttu-id="73aa7-172">UI(사용자 인터페이스)를 통해 최대 999개의 지역 번호 이식 지침</span><span class="sxs-lookup"><span data-stu-id="73aa7-172">Local number porting guidance through user interface (UI) up to 999.</span></span>  <br/>  <span data-ttu-id="73aa7-173">999개가 넘는 번호를 지원하는 지역 번호 이식 SR(서비스 요청)</span><span class="sxs-lookup"><span data-stu-id="73aa7-173">Local number porting service request (SR) support over 999.</span></span>  <br/><br/>  <span data-ttu-id="73aa7-174">**비즈니스용 Skype 모임 브로드캐스트 지침을 온보딩하여 사용하도록 설정**</span><span class="sxs-lookup"><span data-stu-id="73aa7-174">**Enabling Skype for Business Meeting Broadcast guidance onboarding:**</span></span>  <br/>  <span data-ttu-id="73aa7-175">모임 브로드캐스트 서비스가 있는 페더레이션에 대한 조직 설정</span><span class="sxs-lookup"><span data-stu-id="73aa7-175">Organization setup for federation with Meeting Broadcast service.</span></span>   |
|<span data-ttu-id="73aa7-176">Microsoft 팀 온보딩</span><span class="sxs-lookup"><span data-stu-id="73aa7-176">Microsoft Teams onboarding</span></span>  | <span data-ttu-id="73aa7-177">Office 365에 대해 Azure Active Directory에서 사용하는 ID.</span><span class="sxs-lookup"><span data-stu-id="73aa7-177">Identities enabled in Azure Active Directory for Office 365.</span></span>  <br/>  <span data-ttu-id="73aa7-178">SharePoint Online에 대해 사용하는 사용자.</span><span class="sxs-lookup"><span data-stu-id="73aa7-178">Users enabled for SharePoint Online.</span></span>  <br/>  <span data-ttu-id="73aa7-179">Exchange 사서함이 존재합니다(Exchange 하이브리드 구성에 있는 온라인 및/또는 온-프레미스).</span><span class="sxs-lookup"><span data-stu-id="73aa7-179">Exchange mailboxes are present (online and/or on-premises in an Exchange hybrid configuration).</span></span>  <br/>  <span data-ttu-id="73aa7-180">Office 365 그룹에서 사용되도록 설정됩니다.</span><span class="sxs-lookup"><span data-stu-id="73aa7-180">Enabled for Office 365 Groups.</span></span>  <br/><br/> <span data-ttu-id="73aa7-181">**참고**  *사용자에게 SharePoint Online 라이선스가 할당되거나 사용되도록 설정되지 않은 경우 Office 365에서 비즈니스용 OneDrive 저장소가 제공되지 않습니다. 파일 공유는 채널에서 계속 작동하지만, Office 365에 비즈니스용 OneDrive 저장소가 없으면 사용자는 채팅 중에 파일을 공유할 수 없습니다. Microsoft Teams는 SharePoint 온-프레미스를 지원하지 않습니다.*</span><span class="sxs-lookup"><span data-stu-id="73aa7-181"> >  If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365. File sharing will continue to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365. Microsoft Teams doesn't support SharePoint on-premises.           > >  The ideal state is for all users to have their mailboxes homed on Exchange Online. Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 Directory through Azure Active Directory Connect. For these Exchange hybrid customers, if the user's mailbox is on-premises, the user can't add or configure Connectors.</span></span>   <br/> <br/>       <span data-ttu-id="73aa7-182">**참고**  *ExchangeOnline에 속한 사서함이 있는 모든 사용자 이상적인 상태입니다. 온-프레미스에 속한 사서함이 있는 사용자는 ID를 Azure Active Directory Connect를 통해 Office 365 디렉터리로 동기화해야 합니다. 이러한 Exchange 하이브리드 고객 중에 사용자 사서함이 온-프레미스인 경우 사용자는 커넥터를 추가하거나 구성할 수 없습니다.*</span><span class="sxs-lookup"><span data-stu-id="73aa7-182">The ideal state is for all users to have their mailboxes homed on ExchangeOnline. Users with mailboxes homed on-premises must have their identities synchronized to the O365_W14_2nd Directory through WindowsAzureActiveDirectory Connect. For these Exchange hybrid customers, if the user's mailbox is on-premises, the user can’t add or configure Connectors.</span></span>          |
|<span data-ttu-id="73aa7-183">Microsoft StaffHub 온보딩</span><span class="sxs-lookup"><span data-stu-id="73aa7-183">Microsoft StaffHub onboarding</span></span>  | <span data-ttu-id="73aa7-184">ID가 Office 365용 Azure Active Directory에서 사용되도록 설정됩니다.</span><span class="sxs-lookup"><span data-stu-id="73aa7-184">Identities enabled in Azure Active Directory for Office 365.</span></span>  <br/><br/> <span data-ttu-id="73aa7-185">**참고**  *Microsoft StaffHub는 기본적으로 사용할 수 있습니다.*</span><span class="sxs-lookup"><span data-stu-id="73aa7-185">Microsoft StaffHub is enabled by default.</span></span>           |
| <span data-ttu-id="73aa7-186">다음을 포함하는 온보딩 서비스:</span><span class="sxs-lookup"><span data-stu-id="73aa7-186">Service onboarding, including:</span></span>  <br/>  <span data-ttu-id="73aa7-187">*Exchange Online  <br/>  SharePoint Online  <br/>  비즈니스용 OneDrive  <br/>  비즈니스용 Skype Online  <br/>  Microsoft Teams  <br/>  Power BI  <br/>  Project Online  <br/>  Yammer  <br/>  Office 365 ProPlus  <br/>  Microsoft StaffHub*</span><span class="sxs-lookup"><span data-stu-id="73aa7-187">*Exchange Online  <br/>  SharePoint Online  <br/>  OneDrive for Business  <br/>  Skype for Business Online  <br/>  Microsoft Teams  <br/>  Power BI  <br/>  Project Online  <br/>  Yammer  <br/>  Office 365 ProPlus  <br/>  Microsoft StaffHub*</span></span>   |<span data-ttu-id="73aa7-188">Project for Office 365, Outlook 클라이언트, 비즈니스용 OneDrive 동기화 클라이언트, Power BI Desktop, 비즈니스용 Skype 등의 온라인 클라이언트 소프트웨어는 [Office용 시스템 요구 사항](https://go.microsoft.com/fwlink/?LinkID=723597)에 정의된 대로 최소 수준이어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="73aa7-188">Online client software like Project for Office 365, Outlook client, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in [System requirements for Office](https://go.microsoft.com/fwlink/?LinkID=723597).</span></span>  <br/> <span data-ttu-id="73aa7-189">Microsoft Teams Windows 및 Mac 데스크톱 클라이언트용 설치 관리자는 [https://go.microsoft.com/fwlink/?linkid=839411](https://go.microsoft.com/fwlink/?linkid=839411)에서 다운로드할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="73aa7-189">The installers for the Microsoft TeamsWindows and Mac desktop clients can be downloaded from [https://go.microsoft.com/fwlink/?linkid=839411](https://go.microsoft.com/fwlink/?linkid=839411).</span></span>   |
   

  
